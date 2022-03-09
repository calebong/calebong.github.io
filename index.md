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



Last Updated: 2022-03-09 10:58:29 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 10:49:15 </td>
   <td style="text-align:left;"> Hang Seng Hits 5-year Low </td>
   <td style="text-align:left;"> HK50 decreased to a 5-year low of 20638 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/indonesia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-09 10:34:00 </td>
   <td style="text-align:left;"> Indonesia 10Y Bond Yield Hits 16-month High </td>
   <td style="text-align:left;"> Indonesia 10 Year Government Bond Yeld increased to a 16-month high of 6.839%, as traders await Thursday’s US CPI report for February. The figure is expected to show prices rising at their fastest pace in 40 years, reflecting a preliminary impact from surging oil prices. At the same time, while the war in Ukraine may have a very limited direct trade impact to the Southeast Asia's largest economy, soaring energy prices and correspondingly fuel cost as well as some basic raw food items could result into significant inflationary pressures ahead of the fasting month of Ramadan and Eid-al-Fitr. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 10:33:00 </td>
   <td style="text-align:left;"> China Stocks Wobble as Traders Mull Inflation Data </td>
   <td style="text-align:left;"> The Shanghai Composite rose 0.1% to around 3,300 while the Shenzhen Component fell 0.3% to 12,210 on Wednesday, as mainland shares struggled to recover from days of heavy selling despite a regional bounce, while traders mulled Chinese inflation data which came largely within expectations. Investors also continued to assess the war in Ukraine and consequent rise in commodity prices, which rattled markets and stoked fears about a slowdown in global growth amid surging inflation. China is targeting slower economic growth of around 5.5% in 2022, with the government citing multiple domestic and external headwinds. Internal components of the Chinese market traded mixed, with gains from Contemporary Amper (1.1%), Kweichow Moutai (2.4%), BYD Company (1.3%) and Anhui Golden Seed (9.2%); while losses were seen from East Money (-2.3%), Tianqi Lithium (-1.7%), Zhejiang Huayou (-10%) and Sungrow Power (-2.9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/08/business/media/smartmatic-fox-news-defamation-case.html </td>
   <td style="text-align:left;"> 2022-03-09 10:18:24 </td>
   <td style="text-align:left;"> Much of Smartmatic Case Against Fox News Can Proceed, Judge Rules - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The judge did dismiss some defamation claims, against Rudolph W. Giuliani, Jeanine Pirro and Sidney Powell.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , By Brooks Barnes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The $2.7 billion defamation lawsuit against Fox News by the election technology company Smartmatic can move forward, a New York judge ruled on Tuesday. But the judge tossed out Smartmatic’s defamation claims against the Fox News host Jeanine Pirro and a network guest, Sidney Powell.                                                                                                                                                                                                                                                                                                                               , Smartmatic sued Rupert Murdoch’s cable news networks last year, along with several Fox hosts and guests. The lawsuit accused them of damaging the company by promoting a false narrative about the 2020 election: that Smartmatic and other voting systems companies tried to rig the race against President Donald J. Trump. Smartmatic later expanded its legal battle against disinformation to the right-wing media outlets Newsmax and One America News Network.                                                                                                                                                     , On Tuesday, Justice David B. Cohen of State Supreme Court in Manhattan said in a 61-page ruling that, “at a minimum, Fox News turned a blind eye to a litany of outrageous claims about plaintiffs, unprecedented in the history of American elections, so inherently improbable that it evinced a reckless disregard for the truth.”                                                                                                                                                                                                                                                                                     , He added, “At this nascent stage of the litigation, this court finds that plaintiffs have pleaded facts sufficient to allow a jury to infer that Fox News acted with actual malice.”                                                                                                                                                                                                                                                                                                                                                                                                                                      , He also declined to dismiss Smartmatic claims against Maria Bartiromo, the Fox Business star, and Lou Dobbs, whose Fox Business show was a frequent clearinghouse for baseless theories of electoral fraud in the weeks after Mr. Trump’s defeat. Fox canceled Mr. Dobbs’s program last year, one day after Smartmatic sued.                                                                                                                                                                                                                                                                                              , Citing a legal technicality, Justice Cohen dismissed most of Smartmatic’s defamation claims against Rudolph W. Giuliani, who, appearing on Fox News as a legal representative for Mr. Trump, said the technology company had “tried-and-true methods for fixing elections,” among other false assertions. Even so, Justice Cohen said there was “substantial” evidence that Mr. Giuliani “acted with actual malice insofar as he evinced a reckless disregard for the truth” and ruled that Smartmatic could try again. The judge allowed another part of Smartmatic’s defamation case against Mr. Giuliani to go forward., Fox News vowed a swift appeal.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , “While we are gratified that Judge Cohen dismissed Smartmatic’s claims against Jeanine Pirro at this early stage, we still plan to appeal the ruling immediately,” the network said in a statement. The network added that it would “continue to litigate these baseless claims by filing a counterclaim for fees and costs” under New York’s anti-SLAPP (strategic lawsuit against public participation) statute, which is meant to quickly set aside lawsuits that may be intended to chill free speech.                                                                                                                , Fox News said it would do so “to prevent the full-blown assault on the First Amendment which stands in stark contrast to the highest tradition of American journalism.”                                                                                                                                                                                                                                                                                                                                                                                                                                                   , In dismissing the claim against Ms. Pirro, Justice Cohen said that while she had asserted on her show that Democrats “stole votes,” she had not specifically blamed Smartmatic’s software.                                                                                                                                                                                                                                                                                                                                                                                                                                , A spokesman for Smartmatic did not reply to a request for comment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Fox News is also battling a related $1.6 billion defamation lawsuit from Dominion Voting Systems, which has accused the channel of advancing lies that devastated its reputation and business. A Delaware judge rejected an attempt by Fox News to dismiss Dominion’s lawsuit in December.                                                                                                                                                                                                                                                                                                                                , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-us-canada-60666251?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-09 09:57:37 </td>
   <td style="text-align:left;"> War in Ukraine: West hits Russia with oil bans and gas curbs </td>
   <td style="text-align:left;"> This video can not be played                                                                                                                                                                                                                                                                                                               , The US and UK are banning Russian oil and the EU is ending its reliance on Russian gas, stepping up the economic response to the invasion of Ukraine.                                                                                                                                                                                      , US President Joe Biden said the move targeted "the main artery of Russia's economy".                                                                                                                                                                                                                                                       , Energy exports are a vital source of revenue for Russia but the move is also likely to impact Western consumers.                                                                                                                                                                                                                           , Major brands have meanwhile continued to pull out of Russia, with McDonald's and Coca-Cola the latest to leave.                                                                                                                                                                                                                            , Russia's economy is heavily dependent on energy. It is the world's third-biggest oil producer, behind Saudi Arabia and the US.                                                                                                                                                                                                             , Before the measures were announced, Russia warned of "catastrophic" consequences for the global economy and said it might close its main gas pipeline to Germany.                                                                                                                                                                          , On the ground in Ukraine, civilians have been evacuated from two under-attack areas while the US has said up to 4,000 Russian troops may have been killed in the conflict.                                                                                                                                                                 , The conflict has already sent petrol prices to record highs in the US and the UK and experts warn they could go even higher.                                                                                                                                                                                                               , However, Venezuela could increase its oil production to help replace Russian oil.                                                                                                                                                                                                                                                          , Reinaldo Quintero, president of the association that represents Venezuelan oil companies told the BBC that the country could potentially raise its production levels by 400,000 barrels a day.                                                                                                                                             , "I think we can reach 1.2 million barrels per day with the infrastructure we have right now at this moment. So that will make us able to supply the need, some of the need, to the North American market," he said.                                                                                                                        , President Biden's announcement followed pressure from both sides of the US political divide to do more to target the Russian economy.                                                                                                                                                                                                      , "We're banning all imports of Russian oil and gas and energy," he said.                                                                                                                                                                                                                                                                    , "That means Russian oil will no longer be acceptable at US ports and the American people will deal another powerful blow to [President Vladimir] Putin."                                                                                                                                                                                   , Mr Biden admitted the move was "not without cost at home," adding the decision was taken "in close consultation" with allies.                                                                                                                                                                                                              , In a similar move, the UK is to phase out Russian oil imports by the end of 2022.                                                                                                                                                                                                                                                          , The UK Prime Minister, Boris Johnson, accepted that the move would not hit Russia immediately but added "what it will do is add to the pressure we're already seeing on Russia and don't forget that the economic impact of the sanctions that the UK has led has been extreme".                                                           , About 8% of US oil and refined product imports come from Russia, while Russia makes up about 6% of the UK's oil imports.                                                                                                                                                                                                                   , By contrast, the EU is much more reliant on Russian energy, so the bloc's response stopped short of a ban.                                                                                                                                                                                                                                 , The European Commission said it would switch to alternative supplies and expand clean energy faster to fill the shortfall, with the aim of making Europe independent from Russian fossil fuels "well before 2030".                                                                                                                         , This video can not be played                                                                                                                                                                                                                                                                                                               , "We're not standing here to say this is going to be in any way easy," said the European Commission's Vice-President Frans Timmermans.                                                                                                                                                                                                      , "But I am also deeply convinced that even if it's not easy, even if it's very hard, it's something we need to do, because now it's also intimately linked to our security."                                                                                                                                                                , Russia later announced plans to ban the exports of certain commodities and raw materials. The details are still to be worked out, but Russia is a major exporter of grain and metals.                                                                                                                                                      , Even countries with low Russian energy imports are set to feel the impact as the measures are likely to boost already high wholesale prices. Inflation is soaring in the US, EU and the UK, adding to the pressure on households.                                                                                                          , The move adds to a long list of economic sanctions imposed against Russia following its invasion of Ukraine - the central bank has had its assets frozen, some Russian banks have been cut off from global payment networks and Germany suspended the Nord Stream 2 pipeline, which would have transported more gas from Russia to Germany., But energy sales have continued to provide a source of cash despite the other financial restrictions.                                                                                                                                                                                                                                      , Zara McDermott uncovers a dangerous 'rape culture' in Britain's classrooms                                                                                                                                                                                                                                                                 , Villanelle curates this mix just for Eve...                                                                                                                                                                                                                                                                                                , Rosemary Laryea reveals the truth about being a 'soccer mum'                                                                                                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 09:54:40 </td>
   <td style="text-align:left;"> Nikkei Bounces from 16-Month Low </td>
   <td style="text-align:left;"> The Nikkei 225 Index jumped 1% to bounce from a 16-month low and trade above 25,000 while the Topix Index rose 0.9% to 1,775 on Wednesday, as investors reassessed risks surrounding the war in Ukraine and its economic ramifications. Investors also scooped up some beaten-down names following days of heavy selling, including stocks in the technology, financial and consumer-related sectors. Notable gainers include SoftBank (6.9%), Keyence (1.5%), Mitsubishi UFJ (2.9%), Sumitomo Mitsui (1.4%), Toyota Motor (3.3%) and Nintendo (2.2%). Resource-related firms also advanced on stronger commodity prices, with gains from Inpex Corp (1.6%), Sumitomo Metal (2.9%), JFE Holdings (2%) and Nippon Steel (3%). Meanwhile, the US announced a ban on Russian oil and other energy imports on Tuesday, with the UK following suit, rattling the markets and stoking fears about a slowdown in global growth amid surging inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/food-inflation </td>
   <td style="text-align:left;"> 2022-03-09 09:43:00 </td>
   <td style="text-align:left;"> China Food Prices Fall the Most in 5 Months </td>
   <td style="text-align:left;"> Food prices in China dropped by 3.9 percent year-on-year in February 2022, following a 3.8 percent fall a month earlier and marking the steepest fall since last September. Pork prices dropped faster (-42.5 percent vs -41.6 percent in January), reflecting a high base of comparison last year following African swine fever in 2020. Also, cost of fresh vegetables decreased  0.1 percent, after a 4.1% drop in January, amid a slowdown in cost of cooking oils (3.7 percent vs 4.1 percent), fresh fruit (6.6 percent vs 8.8 percent), and milk (0.7 percent vs 0.8 percent). Meantime, cost of eggs picked up (2.6 percent vs 1.9 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-09 09:39:00 </td>
   <td style="text-align:left;"> China Inflation Rate Stays at 4-Month Low </td>
   <td style="text-align:left;"> China's annual inflation rate stood at 0.9 percent in February 2022, unchanged from the previous month and in line with market forecasts. Still, the reading was the lowest level since last September, as the cost of food dropped the most in five months (-3.9% vs -3.8% in January) amid a steeper decline in pork prices. Meanwhile, non-food inflation was little changed (2.1% vs 2.0%), with cost continuing to rise for transportation &amp; communication (5.5% vs 5.2%), housing (1.4% vs 1.4%), clothing (0.6% vs 0.5%), household goods and services (2.5% vs 1.6%), education, culture (2.5% vs 2.9%), and healthcare (0.6 percent vs 0.6 percent). In 2021, the CPI rose 0.9%, far below the central bank’s target of around 3%, and much softer than a 2.5% gain in 2020. On a monthly basis, consumer prices were up 0.6%, the most in four months, following a 0.4% rise in January and beating consensus of a 0.3% gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/producer-prices-change </td>
   <td style="text-align:left;"> 2022-03-09 09:38:00 </td>
   <td style="text-align:left;"> China Producer Prices Rise the Least in 8 Months </td>
   <td style="text-align:left;"> China's producer price inflation eased to 8.8% yoy in February 2022 from 9.1% in the prior month and compared with market forecasts of 8.7%. This was the lowest reading since last June, reflecting the further effect of the government's measures to secure supply and control surging commodity prices. Cost of means of production moderated further (11.4% vs 11.8% in January), led by extraction (33% vs 35%), raw materials (17.9% vs 18.2%), and processing (6.6% vs 7%). Meantime, consumer goods inflation edged up (0.9% vs 0.8%), with prices continuing to rise for food (0.5% vs 0.5%), daily use goods (1.5% vs 1.3%), and clothing (1.4% vs 1.4%) while cost of consumer durable inched higher (0.7% vs 0.6%). On a monthly basis, producer prices increased by 0.5% in February, after a 0.2%  fall in January. Considering the first two months of the year, China's factory gate prices grew by 8.9%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-03-09 09:31:00 </td>
   <td style="text-align:left;"> Heating Oil Hits All-time High </td>
   <td style="text-align:left;"> Heating Oil increased to an all-time high of 4.6685 USD/Gal, as the US and the UK are expected to announce a ban on Russian oil imports. The American ban will include LNG and coal imports, according to reports, while the UK move will be phased over the coming months and won’t target natural gas. Meanwhile, the European Union remained divided over the decision, although most utilities and their energy trading partners were already cutting exposure to Russian energy supplies. Russia currently represents 8% of total crude and petroleum products arriving in the US. Earlier, the Russian deputy Prime Minister warned the oil barrel could reach $300 if a global embargo were to be placed, as the country produces 8% of total oil production. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60670120?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-09 09:29:26 </td>
   <td style="text-align:left;"> War in Ukraine: Warning oil sanctions will further hit UK living costs </td>
   <td style="text-align:left;"> Western plans to ban or curb Russian oil and gas imports will further hit UK living standards, analysts say.                                                                                                                                                   , Experts say global commodity prices are set to soar even higher as a result of the UK, US and EU announcing plans to punish Moscow for invading Ukraine.                                                                                                       , The RAC says UK petrol prices could hit £1.60 a litre this week and £1.65 soon.                                                                                                                                                                                , And one think tank warned household disposable incomes could see the biggest fall since 1955 as prices surge in the second quarter of the year.                                                                                                                , The UK, which gets 8% of its oil from Russia, said on Tuesday that it plans to phase out these imports by the end of 2022.                                                                                                                                     , Meanwhile, the US said it would immediately ban Russian oil and gas and the EU vowed to cut is gas imports by two thirds this year.                                                                                                                            , Business Secretary Kwasi Kwarteng tweeted that the UK's transition would give its "market, businesses and supply chains more than enough time to replace Russian imports".                                                                                     , Robert Buckley, an energy analyst at Cornwall Insight, told the BBC the UK ban was "largely symbolic" because Russian oil was such a small part of its overall energy mix.                                                                                     , However, together with the US ban, and widespread boycotts by western companies, the move is likely to increase already high oil prices in the coming weeks, he said.                                                                                          , "This is a global market and you've got to replace that displaced supply somehow," Mr Buckley told the BBC.                                                                                                                                                    , "At the margin, this decision will act to support oil prices which are already extremely high."                                                                                                                                                                , The price of Brent crude - the global oil benchmark - has climbed for weeks, hitting a 14-year high of $139 a barrel at one point on Monday. Prices jumped 7% on Tuesday after the sanctions were announced.                                                   , Brent crude was trading just below $130 on Asian markets on Wednesday morning.                                                                                                                                                                                 , Those rising wholesale costs are feeding through to higher petrol prices at the pump, a trend the RAC expects to accelerate.                                                                                                                                   , "We were at £1.56 per litre for petrol and £1.62 for diesel yesterday, both records," the RAC's fuel spokesman Simon Williamson told the BBC.                                                                                                                  , "In 2016, you could regularly get petrol for under £1 a litre at supermarkets and other low-cost retailers."                                                                                                                                                   , He said he expected prices to remain high as long as the conflict continued, although a deal to unlock supply from Iran or Venezuela - both of which face their own oil sanctions - could ease the pressure.                                                   , "It's not just about what consumers pay at the pump," he added. "Everything in our shops has ultimately been moved by a diesel powered lorry and businesses are obviously likely to pass on these costs."                                                      , Even before Russia invaded Ukraine, the UK's cost of living was rising at its fastest rate in 30 years amid surging global demand for oil and gas as pandemic restrictions eased.                                                                              , But the war has added to this pressure, driving up the cost of not just fuel and energy but also other commodities like wheat and metals.                                                                                                                      , Nathan Piper, an oil and gas analyst at Investec, said the EU's decision on Tuesday to reduce its reliance on Russian gas was also likely to hit the UK.                                                                                                       , Wholesale gas prices have been climbing for months and analysts expect the UK's energy price cap - which limits what consumers pay for gas and electricity - to rise to more than £3,000 a year for the average household when it is next reviewed in October. , "We are on the cusp of a prolonged period of high oil and gas prices, possibly lasting several years," Mr Piper told the BBC.                                                                                                                                  , "You can't just cut the second largest gas producer and third largest oil producer out of global supply and not expect it to have big impact on consumers," he added.                                                                                          , He said there would be "extreme fuel poverty" over the next few years, with the government facing growing pressure to offer more support.                                                                                                                      , In research published on Tuesday, the Centre for Business and Economic Research (CEBR) warned that a combination of rising commodity and oil prices and sanctions was likely to have major impact on the UK economy.                                           , It estimates that GDP growth this year will be more than halved - down from a previously forecast 4.2% to 1.9%.                                                                                                                                                , The CEBR also expects inflation to hit 8.7% in the second quarter of this year and disposable incomes to fall by 4.8% in 2022 - the largest drop since records began in 1955.                                                                                  , "The forecast fall in living standards this year is an estimated £71bn - which amounts to £2,553 per household," it said.                                                                                                                                      , Zara McDermott uncovers a dangerous 'rape culture' in Britain's classrooms                                                                                                                                                                                     , Villanelle curates this mix just for Eve...                                                                                                                                                                                                                    , Rosemary Laryea reveals the truth about being a 'soccer mum'                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/09/irpin-kyiv-ukraine-evacuation-russia-nursing-home-tsr-ward-pkg-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-09 09:25:17 </td>
   <td style="text-align:left;"> 'Mom, I'm alive!': See one mother's reaction after finding son - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/media/2022/03/09/volodymyr-zelensky-social-media-ukraine-todd-dnt-intl-tsr-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-09 09:17:58 </td>
   <td style="text-align:left;"> How Zelensky is using social media to dominate the information war - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 09:00:07 </td>
   <td style="text-align:left;"> Australia Shares Rise as Energy, Tech Stocks Lift </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index rose 0.8% to around 7,035 on Wednesday, as gains in technology and energy stocks outweighed losses in the materials and healthcare sectors, while a weak overnight session on Wall Street dampened sentiment. Investors also continued to assess the war in Ukraine and consequent rise in commodity prices, which rattled markets and stoked fears about a slowdown in global growth amid surging inflation. Australia technology firms advanced following days of heavy selling, with gains from Aristocrat Leisure (3.6%), Xero (1.7%) and Wisetech Global (4%). Energy stocks also gained amid surging oil prices including Woodside Petroleum (1.9%), Santos Ltd (-0.5%) and Beach Energy (1.8%). Elsewhere, gold stocks and banks added points to the benchmark index. Meanwhile, trading in Nickel Mines shares were halted after tumbling 23% as nickel trading at the LME was suspended until Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/russia-suspends-foreign-currency-sales-ruble-ukraine-invasion </td>
   <td style="text-align:left;"> 2022-03-09 08:56:19 </td>
   <td style="text-align:left;"> Russia suspends foreign currency sales as ruble crashes amid economic fallout over Ukraine invasion </td>
   <td style="text-align:left;"> Center for Security Policy President Fred Fleitz discusses what Russia’s next military moves may be and the possibility for diplomacy on ‘Fox Business Tonight.’                                                                                                                                               , Russia’s central bank, faced with unprecedented sanctions and a plummeting ruble, said Wednesday it was suspending the sale of foreign currencies through September.                                                                                                                                           , Between March 9 and September 9, Russian banks "will not be able to sell foreign currencies to citizens," the central bank said in a statement, adding that it will be possible to exchange cash currency for rubles at any time and any amount.                                                               , A Russian national flag above the headquarters of Bank Rossii, Russia's central bank, in Moscow, Russia, on Monday, Feb. 28, 2022.  (Photographer: Andrey Rudakov/Bloomberg via Getty Images)                                                                                                                  , During that window, cash withdrawals from foreign currency accounts at Russian banks will be limited to $10,000. Any withdrawals above that amount would be converted to rubles at the current exchange rates.                                                                                                 , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                           , The bank said clients of all banks can still receive funds from their foreign currency deposits or accounts, but noted that it may take "several days" to bring the required amount of cash to a particular branch.                                                                                            , President Biden sits in the Oval Office of the White House, on March 4, 2022, in Washington.  (AP Photo/Patrick Semansky, File)                                                                                                                                                                                , These new measures, some of the strictest financial controls enacted in Russia since the Soviet era, come amid economic fallout over Russian President Vladimir Putin’s invasion of Ukraine.                                                                                                                   , SOME WESTERN COMPANIES DECLINE TO JOIN CORPORATE EXODUS FROM RUSSIA OVER UKRAINE INVASION                                                                                                                                                                                                                      , The United States and its allies have imposed crippling sanctions on Russia’s economy while many businesses, ranging from tech, to finance, to oil, have ceased operations in the country.                                                                                                                     , Russia's central bank noted that the currency controls were tightened because of the Western sanctions that froze a large share of its hard currency reserves. The crippling blow to the country's financial system prevented Russia from getting foreign cash.                                                , Gideon Rose, a distinguished fellow in U.S. foreign policy at the Council of Foreign Relations and a sanctions expert, said the decline of the ruble was "one of the few things" Putin can do something about.                                                                                                 , "This move is not designed to hit back but rather to try to preserve the strength of the currency," Rose said. "Still, it's too little too late – the measure may temporarily dampen the fall and perhaps stave off a next wave of defaults, but the diminished purchasing power of the ruble is here to say." , A powerful coalition of democracies announced it would cut off some Russian banks from the global payment system Swift. (Anton Vaganov/Reuters)                                                                                                                                                                , President Biden took matters a step further on Tuesday by ordering a ban on Russian oil imports, saying the U.S. "will not be part of subsidizing Putin’s war."                                                                                                                                                , CLICK HERE TO READ MORE FROM FOX BUSINESS                                                                                                                                                                                                                                                                      , Also on Tuesday, American credit rating agency Fitch Ratings downgraded Russia’s credit rating from a "B" to a "C" and suggested that sovereign default is imminent. The ruble has crashed to just 0.0077 against the US dollar on Tuesday.                                                                    , Fox Business’ Andrew Mark Miller and The Associated Press contributed to this report.   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/08/us/politics/biden-oil-ban-russia-ukraine-putin.html </td>
   <td style="text-align:left;"> 2022-03-09 08:50:11 </td>
   <td style="text-align:left;"> Biden Bans Oil Imports From Russia, Warning Gas Prices Will Rise - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Officials said President Biden had struggled for days over the move amid deep concerns about accelerating the already rapid rise in the price of gasoline.                                                                                                                                                                                                                                                                                                                                                                          , By Michael D. Shear                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , WASHINGTON — President Biden on Tuesday banned imports of Russian oil, gas and coal in response to what he called President Vladimir V. Putin’s “vicious war of choice” in Ukraine, but warned Americans that the decision to inflict economic pain on Russia would inevitably mean higher gas prices at home.                                                                                                                                                                                                                      , “Defending freedom is going to cost,” Mr. Biden said in televised remarks announcing the ban at the White House.                                                                                                                                                                                                                                                                                                                                                                                                                    , The president’s move immediately shut off a relatively small flow of oil into the United States, but it was quickly followed by a British pledge to phase out imports of Russian oil by the end of the year and a declaration from the European Commission — the executive arm of the European Union, which is heavily dependent on Russian oil and gas — to make itself independent of that supply in the coming years.                                                                                                            , The impact of the decisions quickly rippled across the global energy market amid fears that the supply of oil would shrink. In the United States, the national average price of a gallon of regular gasoline, which had already surged in recent weeks, reached $4.173, not adjusted for inflation, a new high and an average increase of about 72 cents from only a month ago, according to AAA.                                                                                                                                   , “If we do not respond to Putin’s assault on global peace and stability today, the cost of freedom and to the American people will be even greater tomorrow,” Mr. Biden said.                                                                                                                                                                                                                                                                                                                                                        , He vowed to “do everything I can to minimize Putin’s price hike here at home.”                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Under intense, bipartisan pressure from lawmakers to deny Russia any more oil revenue from Americans, Mr. Biden acted without the unity among allies that has characterized most of the response to Russia’s aggression during the past several months.                                                                                                                                                                                                                                                                             , The moves by Britain and the E.U. fell short of Mr. Biden’s ban. Franck Riester, the French minister for foreign trade, told the Franceinfo radio station on Monday that “everything’s on the table,” but that officials would need to consider “consequences” from an energy ban. In Italy, which imports more than 40 percent of its energy as Russian gas, Prime Minister Mario Draghi has said the overdependence on Russian gas is a strategic weakness for the country.                                                       , Even as Mr. Biden spoke, describing his ban as “another powerful blow to Putin’s war machine,” a new wave of major corporations across the world began shutting down their operations in Russia on Tuesday.                                                                                                                                                                                                                                                                                                                         , Shell, Europe’s largest oil company, said it would begin withdrawing from its involvement “in all Russian hydrocarbons,” including an immediate halt to all spot purchases of Russian crude and the shuttering of its service stations in the country. McDonald’s, Coca-Cola, Pepsico and Starbucks announced that they would temporarily close all restaurants and pause all operations in Russia in response to the invasion in Ukraine. Amazon stopped letting customers in Russia and Belarus open new cloud computing accounts., Officials said Mr. Biden had struggled for days over whether to cut off Russian oil amid fears of accelerating the already rapid rise in the price of gasoline. It is a potent political issue for Americans in an election year and a test of how much voters are willing to sacrifice in defense of Ukraine.                                                                                                                                                                                                                      , Even into the weekend, as a bipartisan group of lawmakers in the House tried to finalize legislation to impose a ban on Russian oil, the White House expressed deep concerns, according to officials monitoring the discussions, who said the administration appeared wary of letting Congress take the lead on enacting a ban.                                                                                                                                                                                                     , A vote on the House bill, which is supported by Speaker Nancy Pelosi of California, was delayed late Tuesday.                                                                                                                                                                                                                                                                                                                                                                                                                       , The president and his aides have discussed a series of additional moves to blunt the impact of the ban, including additional releases from strategic oil reserves. Last week, the United States committed to releasing 30 million barrels of oil, joining 30 other nations for a total release of 60 million barrels.                                                                                                                                                                                                               , Administration officials have also held diplomatic conversations with other oil-producing nations, including Venezuela, about increasing the flow of oil to keep prices stable. Jen Psaki, the White House press secretary, on Monday confirmed discussions with Venezuela about “energy security” and other issues, but declined to elaborate.                                                                                                                                                                                     , Any barrels the United States imports to replace Russian oil will come from a global market that is already stretched. Unless and until Russia finds alternative buyers, the constraint on available supplies is likely to keep prices high.                                                                                                                                                                                                                                                                                        , U.S. consumers are already feeling the squeeze. In California, prices for some types of gas has hovered around $6 in recent days; on Tuesday the state average was well over $5.                                                                                                                                                                                                                                                                                                                                                    , Republicans on Tuesday largely backed Mr. Biden’s decision to cut off Russian oil, giving the president a rare moment of bipartisan support. But even as they did so, many Republicans once again seized on high prices at the pump to criticize him and his party.                                                                                                                                                                                                                                                                 , “Democrats want to blame surging prices on Russia,” Representative Kevin McCarthy of California, the House Republican leader, said on Tuesday. “But the truth is, their out-of-touch policies are why we are here in the first place.”                                                                                                                                                                                                                                                                                              , In his remarks, Mr. Biden cast the decision as a moral one, aimed at further crippling Mr. Putin’s economy as Russian forces continued their brutal bombardment of civilians in several of Ukraine’s cities and suburbs after two grueling weeks of war in Europe.                                                                                                                                                                                                                                                                  , “Ukrainian people have inspired the world and I mean that in the literal sense,” Mr. Biden said. “They’ve inspired the world with their bravery, their patriotism, their defiant determination to live free. Putin’s war has caused enormous suffering and needless loss of life of women, children, and everyone in Ukraine.”                                                                                                                                                                                                      , He added: “Putin seems determined to continue on his murderous path, no matter the cost.”                                                                                                                                                                                                                                                                                                                                                                                                                                           , Battles continued to rage across Ukraine on Tuesday as humanitarian officials reported that two million refugees have fled the country seeking safety. But casualties increased as evacuations though supposed “green corridors” continued to come under fire.                                                                                                                                                                                                                                                                      , About 2,000 civilians were able to escape Irpin, a suburb just northwest of Kyiv, Ukraine’s capital, which has spent days without water, power and heat because of the heavy fighting in the area. In the war-battered city of Sumy, east of Kyiv, one humanitarian corridor lasted long enough to allow hundreds of civilians to escape in a convoy of buses led by the Red Cross.                                                                                                                                                 , But hundreds of thousands of Ukrainians remain trapped in the besieged southern city of Mariupol.                                                                                                                                                                                                                                                                                                                                                                                                                                   , The Ukrainian military claimed to have shot down three Russian fighter jets and a cruise missile early Tuesday, an assertion that appeared to be backed up by several loud explosions over Kyiv, a potential sign that Ukraine’s air defense systems and air force are still functioning.                                                                                                                                                                                                                                           , President Volodymyr Zelensky of Ukraine taunted Mr. Putin on Tuesday with a video showing him in his office in Kyiv and saying: “I’m not hiding. And I’m not afraid of anyone.” Mr. Zelensky also spoke by video link to a packed meeting of Britain’s Parliament.                                                                                                                                                                                                                                                                  , The Pentagon on Tuesday rejected an offer by Poland to send its MiG-29 fighter planes to a U.S. air base in Germany to aid the Ukrainians, saying that for such jets to depart a U.S./NATO base “to fly into airspace that is contested with Russia over Ukraine raises serious concerns for the entire NATO alliance.”                                                                                                                                                                                                             , Separately, the Pentagon said it was sending two Patriot anti-missile batteries to Poland to protect U.S., Polish and other allied troops there, reflecting an increasing fear in Warsaw and in Washington that Russian missiles fired in neighboring Ukraine could end up in Poland, whether on purpose or by accident.                                                                                                                                                                                                            , White House officials said the president signed an executive order on Tuesday that prohibits anyone in the United States from importing “Russian crude oil and certain petroleum products, liquefied natural gas and coal.” It also bans new U.S. investment directly in Russia’s energy sector or in foreign companies that are investing in energy production in Russia, officials said.                                                                                                                                          , In announcing his decision, Mr. Biden acknowledged that some European countries, including Germany and France, would most likely not follow suit because they rely much more heavily on energy from Russia.                                                                                                                                                                                                                                                                                                                         , “A united response to Putin’s aggression has been my overriding focus to keep all of NATO and all of the E.U. and our allies totally united,” Mr. Biden said. “We’re moving forward with this ban understanding that many of our European allies and partners may not be in a position to join us.”                                                                                                                                                                                                                                 , Russian oil imports. President Biden banned Russian oil, natural gas and coal imports into the United States. The move, which effectively shuts off the relatively small flow of Russian fuel into the country, could further rattle global energy markets and raise gas prices.                                                                                                                                                                                                                                                    , A halt to Russian sales. After days of seeming reluctance to take a stance over Russia’s invasion of Ukraine, three high-profile American food and beverage companies — McDonald’s, Coca-Cola and Starbucks — said they were pausing operations in Russia.                                                                                                                                                                                                                                                                          , The key cities. Ukrainian military and civilian soldiers continued to bog down Russian forces, protecting the borders of key cities and inflicting heavy losses against the larger and better equipped Russian army.                                                                                                                                                                                                                                                                                                                , A humanitarian crisis. Indiscriminate Russian shelling has trapped Ukrainian civilians and left tens of thousands without food, water, power or heat in besieged cities. The United Nations said that the number of refugees who have fled Ukraine has reached two million.                                                                                                                                                                                                                                                         , In brief remarks before heading to Texas for an event about the impact of environmental toxins on veterans, Mr. Biden vowed to do what he could to minimize the effect of his decision on gas prices, but he did not specify whether the United States would seek to import oil from other countries already under sanctions, like Venezuela or Iran.                                                                                                                                                                               , And he warned oil companies in the United States not to take advantage of the decision by arbitrarily raising prices.                                                                                                                                                                                                                                                                                                                                                                                                               , “Russia’s aggression is costing us all,” Mr. Biden said. “And it’s no time for profiteering or price gouging.”                                                                                                                                                                                                                                                                                                                                                                                                                      , Concern about disruptions in the flow of oil around the world has pushed up the price of Brent crude, the global benchmark for oil. On Tuesday, it rose 4 percent, to about $128 a barrel, off its earlier high of about $133. Since Russia invaded Ukraine on Feb. 24, oil prices have risen about 30 percent.                                                                                                                                                                                                                     , Stock markets also extended their losses on Tuesday after steep declines on Monday. The S&amp;P 500 dropped 0.7 percent and is down 12.5 percent for the year. Benchmarks in Europe were mostly lower, with the Stoxx Europe 600 slipping 0.5 percent.                                                                                                                                                                                                                                                                                  , But Mr. Biden conceded that Americans were most likely to feel the economic pain when they filled up their gas tanks every week.                                                                                                                                                                                                                                                                                                                                                                                                    , Though gas costs make up a relatively small part of consumer spending and some analysts expect the extreme prices to be short-lived, the price of gas can have an outsized influence on how Americans perceive the U.S. economy. And inflation, which has been rising at its fastest pace in 40 years, had been a concern for many before the Russian invasion.                                                                                                                                                                     , On Tuesday, the president sought to counter the attacks from Republicans, who have already accused the administration of pursuing environmental policies — such as blocking drilling on some public lands — that they say have made the situation worse. Some Republicans have urged the president to allow for more drilling to replace the oil imported from Russia.                                                                                                                                                              , Mr. Biden said that oil companies in the United States already had permission to drill in areas that they had yet to tap.                                                                                                                                                                                                                                                                                                                                                                                                           , “They have 9,000 permits to drill now,” he said. “They could be drilling right now, yesterday, last week, last year. They have 9,000 to drill onshore that are already approved. So let me be clear — let me be clear. They are not using them for production now. That’s their decision. These are the facts.”                                                                                                                                                                                                                     , Even though Republicans and Democrats in Congress had pushed for a ban on Russian energy, the White House is bracing for increased criticism from Republicans as the price of gas and other energy rises over the coming weeks.                                                                                                                                                                                                                                                                                                     , “This crisis is a stark reminder: To protect our economy over the long term, we need to become energy independent,” Mr. Biden said, adding: “It should motivate us to accelerate the transition to clean energy.”                                                                                                                                                                                                                                                                                                                   , The United States and its allies in Europe and elsewhere have already imposed severe sanctions and export restrictions on Russia. The threat of those sanctions was initially intended to try to deter an invasion from happening in the first place                                                                                                                                                                                                                                                                                , Those steps — which failed to prevent the war — include freezing the assets of major Russian banks and Mr. Putin’s wealthy Russian friends, cutting some Russian banks off from the international banking system, and blocking Russia from acquiring certain imports, including high-tech equipment.                                                                                                                                                                                                                                , Mr. Biden and his counterparts had previously exempted energy resources from those sanctions in an effort to ensure the steady flow of natural gas and oil throughout the world.                                                                                                                                                                                                                                                                                                                                                    , Asked on Tuesday whether he has a message for the American people about the increase in gas prices, Mr. Biden was blunt.                                                                                                                                                                                                                                                                                                                                                                                                            , “They’re going to go up,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Asked what he can do about it, Mr. Biden said: “Can’t do much right now. Russia is responsible.”                                                                                                                                                                                                                                                                                                                                                                                                                                    , Reporting was contributed by Catie Edmondson from Washington; Julie Creswell, Coral Murphy Marcos and Marie Solis from New York; Karen Weise from Seattle; Stephen Castle, Mark Landler and Eshe Nelson from London; Lynsey Addario from Irpin, Ukraine; Marc Santora and Maria Varenikova from Lviv, Ukraine; and Jeffrey Gettleman and Monika Pronczuk from Lublin, Poland.                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/rating </td>
   <td style="text-align:left;"> 2022-03-09 08:45:00 </td>
   <td style="text-align:left;"> Fitch Cuts Russia Rating to C </td>
   <td style="text-align:left;"> Fitch Ratings downgraded Russia's sovereign rating by six notches further into the junk territory to 'C' from 'B', saying a default is imminent as sanctions and trade restrictions have undermined its willingness to service debt. Fitch’s added that the "ratcheting up of sanctions" against Russia along with the possibility its energy sector revenue will be reduced increases the probability of a policy response by Russia that includes at least selective non-payment of its sovereign debt obligations. Earlier, Moody's Credit Rating lowered Russia’s long-term issuer and senior unsecured debt ratings to Ca from B3 with a negative outlook, on March 6th. S&amp;P credit rating for Russia was last set at CCC with negative watch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/consumer-confidence </td>
   <td style="text-align:left;"> 2022-03-09 08:31:21 </td>
   <td style="text-align:left;"> Australia Consumer Sentiment Falls to 18-Month Low </td>
   <td style="text-align:left;"> The Consumer Sentiment Index in Australia declined 4.2% MoM to 96.6 points in March 2022, weighed down by concerns over the war in Ukraine, the floods in south-east Queensland and Northern NSW and expectations of higher inflation and interest rates. This is the weakest print since September 2020, which is also the last time the index was below the 100-level indicating that pessimists outnumber optimists. All five sentiment sub-indexes recorded declines in March. The ‘economy, next 12 months’ sub-index fell by 6.7% while the ‘economy, next 5 years’ sub-index was down by 5.8%. The ‘finances vs a year ago’ sub-index also fell by 3.9% and the ‘time to buy a major household item’ sub-index slid 4.4%. The Westpac Melbourne Institute Index of Unemployment Expectations fell 1.1% to 101.8 in March from 102.8 in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/gdp-growth-annualized </td>
   <td style="text-align:left;"> 2022-03-09 08:29:18 </td>
   <td style="text-align:left;"> Japan Q4 GDP Growth Annualized Revised Downward </td>
   <td style="text-align:left;"> The Japanese economy advanced 4.6 percent on an annualized basis in Q4 of 2021, compared with flash data of 5.4 percent and reversing from a revised 2.8 percent contraction in Q3. The rebound marked the strongest pace of expansion since Q4 2020, as COVID-19 situations were under control following a fall in coronavirus cases and surging vaccinations. Household consumption rebounded sharply, increasing the most in five-quarter; business investment bounced back; and net exports contributed further to the GDP, with exports recovering from a decline in Q3 and imports extending their falls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60667067?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-09 08:16:58 </td>
   <td style="text-align:left;"> MPs urge inquiry into bankers jailed for ‘rigging’ rates </td>
   <td style="text-align:left;"> MPs have called for a fresh inquiry into the interest rate-rigging scandal which led to two bankers who blew the whistle at Barclays being jailed.                                                                                                                                                                                                                                                          , It comes after the BBC uncovered audio tapes that suggest the Bank of England and top government officials pressured Barclays to rig interest rates.                                                                                                                                                                                                                                                        , MPs on the current and former Treasury Committees are concerned that the wrong people may have been prosecuted.                                                                                                                                                                                                                                                                                             , The Serious Fraud office told the BBC it conducted a thorough investigation.                                                                                                                                                                                                                                                                                                                                , The calls for a new inquiry follow the broadcast of a BBC Radio investigative podcast which explores traders' allegations that they are the victims of a whole series of miscarriages of justice.                                                                                                                                                                                                           , It revealed that two traders jailed for rigging interest rates, Peter Johnson and Colin Bermingham, were the original whistleblowers of the scandal.                                                                                                                                                                                                                                                        , In the Radio 4 podcast The Lowball Tapes, the BBC revealed leaked audio recordings and documents that implicate both the Bank of England and the government in pressuring banks to rig interest rates.                                                                                                                                                                                                      , The audio recordings and documents were never seen by a previous parliamentary inquiry into the scandal in 2012.                                                                                                                                                                                                                                                                                            , Much of the evidence was also never shown to juries in nine rate-rigging trials of traders and brokers that were held between 2015 and 2019.                                                                                                                                                                                                                                                                , A total of 38 traders were prosecuted, 24 of them in the UK. After nine criminal trials on both sides of the Atlantic, 11 were convicted.                                                                                                                                                                                                                                                                   , Andrew Tyrie, who chaired the committee that investigated the scandal in 2012, told the BBC if they'd known what the BBC has since discovered they would have investigated further, changing the context in which decisions were taken to prosecute 24 traders.                                                                                                                                             , "People have had their lives badly shaken up. And they've had terrible experiences from the trials," he said.                                                                                                                                                                                                                                                                                               , "From what I can tell the whistleblowers were, as the name suggests, trying to do the right thing. Whistleblowing is a crucial part of investigative machinery. And it's very important, it should be seen to function well. And it doesn't seem to work in this case."                                                                                                                                     , The case against the convicted traders was separate to any intervention involving the Bank of England. They were alleged to have entered a conspiracy to commit fraud by asking colleagues to tweak estimates of interest rates up or down by a hundredth of a percentage point (known as a "basis point").                                                                                                 , What the FTSE 100 is to share prices, Libor is to interest rates – an index that tracks the cost of borrowing cash. For most of the past 35 years, 16 banks have answered a question every morning at 11am: At what interest rate could you borrow money?                                                                                                                                                   , They submit their answers (e.g. RBS estimates 3.14%, Lloyds 3.13% etc) and an average is taken to get Libor, short for "London Interbank Offered Rate". To set Euribor, the process is similar but with more banks involved.                                                                                                                                                                                , The evidence against the traders jailed for rate "rigging" consisted entirely of requests they had made to colleagues to tweak those estimated interest rates up or down, typically by one hundredth of a percentage point (known on the money markets as a "basis point").                                                                                                                                 , The hope was that it might shift the Libor average marginally in the right direction to benefit the bank’s trades which went up or down linked to Libor.                                                                                                                                                                                                                                                    , In the other form of rate rigging, known as lowballing, banks pretend to be able to borrow cash much more cheaply than they really can. It is on a much larger scale.                                                                                                                                                                                                                                       , The evidence kept from Andrew Tyrie's committee 10 years ago includes a tape, known to regulators who appeared before the committee, where Barclays trader Peter Johnson is told by his boss Mark Dearlove that the bank has had "very serious pressure from the UK government and the Bank of England about pushing our Libors lower".                                                                     , However, those who gave instructions from above have never been prosecuted.                                                                                                                                                                                                                                                                                                                                 , The Lowball Tapes also reveal that Mr Dearlove says he was pressured directly by then Bank of England executive director Paul Tucker earlier that month that Barclays' Libor rate should be "put down" because it was receiving attention from the government.                                                                                                                                              , Evidence uncovered for the series also suggests that as it sought to manage the credit crunch and the banking crisis that followed it, the Bank of England was intervening in the Libor setting process starting in August 2007.                                                                                                                                                                            , Emails and sworn testimony never shown to MPs nor juries suggest the Bank of England first agreed that senior bank executives should collectively raise Libor on 14 August 2007 because it was too low to reflect the interest rates where cash was changing hands. It then intervened to tell Barclays to lower its Libor submissions on 1 September 2007 following speculation about the bank's solvency. , It also shows that Barclays cash traders Peter Johnson and Colin Bermingham had sought to blow the whistle on lowballing throughout the crisis. But far from being thanked, they were separately prosecuted for a far smaller form of interest rate "rigging" which is now not regarded as a crime in the United States                                                                                     , Barclays' legal department, the UK regulator the Financial Services Authority and the US Department of Justice all had access to this evidence. Yet there was no mention it in the regulatory notices published at the time and no-one informed MPs about it.                                                                                                                                               , The call for a fresh investigation is supported by three other former and current members of the Treasury Committee.                                                                                                                                                                                                                                                                                        , "It needs a new full, judge-led inquiry," said Treasury committee member and campaigner against financial corruption, Kevin Hollinrake. "You cannot have a situation where the rule-setters, the 'masters of the universe' go by one set of rules and the rest of us go by another.                                                                                                                         , "I don't care who these people are: what level of government, what level of the Bank of England, or what level of the FCA - or what level of the banks they're working in. These people have to play by the rules. So there should be an inquiry and investigation to see if they have."                                                                                                                    , Mark Garnier, who sat on the 2012 committee that was told the Bank of England hadn't put pressure on Barclays, said if he were now chairman of the Treasury committee he'd be ordering hearings to get to the truth. Teresa Pearce, a member of the same 2012 committee, said the evidence uncovered by the BBC showed the investigation needed reopening.                                                  , Paul Tucker has declined to comment in response to a BBC right of reply. Barclays didn't respond to our request for comment but former executives have denied they came under pressure from the Bank of England to lower Libor. The Bank of England has also denied that it put pressure on banks and said Libor was not regulated at the time.                                                             , The US Federal Reserve declined to comment. But in a statement from 2012, it said it had received "occasional anecdotal reports from Barclays of problems with Libor" in 2007, and shared suggestions for reform with relevant UK authorities.                                                                                                                                                              , Zara McDermott uncovers a dangerous 'rape culture' in Britain's classrooms                                                                                                                                                                                                                                                                                                                                  , Villanelle curates this mix just for Eve...                                                                                                                                                                                                                                                                                                                                                                 , Rosemary Laryea reveals the truth about being a 'soccer mum'                                                                                                                                                                                                                                                                                                                                                , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/08/business/mcdonalds-russia-starbucks-pepsi-coca-cola.html </td>
   <td style="text-align:left;"> 2022-03-09 08:14:27 </td>
   <td style="text-align:left;"> Food Companies, Long Symbols of the West in Russia, Pause Operations - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , After years of cultivating the Russian market, McDonald’s, Starbucks, PepsiCo and Coca-Cola said they would temporarily close locations or stop selling products there.                                                                                                                                                                                                                                                                                                                                                                                              , By Julie Creswell                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , When McDonald’s opened its doors in Moscow’s Pushkin Square in 1990, it was welcomed by more than 30,000 Russians who happily waited hours in line, eager to spend a sizable chunk of their daily wages for a taste of America.                                                                                                                                                                                                                                                                                                                                      , Through burgers and fries, a food diplomacy was forged, one that flourished over the past three decades as corporations like McDonald’s and PepsiCo, private investment firms, and individuals plunged billions of dollars into building factories and restaurants to bring food, culture and good-old American capitalism to Russia. It was perestroika and glasnost sandwiched between two buns.                                                                                                                                                                   , “McDonald’s was more than the opening of a simple restaurant,” Marc Carena, a former managing director of McDonald’s Russia, told Voice of America in 2020 when the Golden Arches celebrated the 30th anniversary of its first location in what was the Soviet Union. “It came to symbolize the entire opening of the U.S.S.R. to the West.”                                                                                                                                                                                                                         , But Russia’s invasion of Ukraine has changed everything, and food companies and restaurant chains have struggled with how to respond. Amid mounting pressure to act, McDonald’s announced on Tuesday that it was temporarily closing its nearly 850 locations in Russia and halting operations in the country.                                                                                                                                                                                                                                                       , “In the 30-plus years that McDonald’s has operated in Russia, we’ve become an essential part of the 850 communities in which we operate,” Chris Kempczinski, the company’s chief executive, said in a statement announcing the move. He noted that the company employed 62,000 people in the country.                                                                                                                                                                                                                                                                , Soon after the McDonald’s announcement, other prominent food companies and restaurants followed. Starbucks said it, too, was closing all of its locations in Russia, where they are owned and operated by the Kuwaiti conglomerate Alshaya Group. Coca-Cola said it was halting sales there.                                                                                                                                                                                                                                                                         , And PepsiCo, whose products have been in Russia since the early 1970s, said it would no longer sell Pepsi and 7-Up there but would continue to produce dairy and baby food products in the country as a “humanitarian” effort and to keep tens of thousands manufacturing and farm workers employed.                                                                                                                                                                                                                                                                 , Investors, as well as social media users, have been applying pressure on businesses to pull out of Russia, especially fast-food chains, which have been criticized for lagging behind other companies with decisions about their Russia operations.                                                                                                                                                                                                                                                                                                                  , For food companies that have spent decades cultivating the Russian market, the act of pausing or ceasing operations in the country is complex. It involves unwinding often byzantine local supply and manufacturing chains, addressing the fates of tens of thousands of Russian employees, and untangling close ties with Russian banks, investors and others that allowed them to flourish all these years.                                                                                                                                                        , Russian operations make up only 3 percent of McDonald’s operating income but 9 percent of its revenue. Likewise, Russia accounts for $3.4 billion, or 4 percent, of PepsiCo’s annual revenue of $79.4 billion. The company says on its website that it is the largest food and beverage manufacturer in Russia. It owns more than 20 factories in the country.                                                                                                                                                                                                       , “PepsiCo has been there forever. PepsiCo was there under Nixon,” said Bruce W. Bean, a professor emeritus at Michigan State University’s law school who, as an American lawyer in Russia, worked with companies making investments there.                                                                                                                                                                                                                                                                                                                            , “Obviously, PepsiCo can walk away from the business,” Mr. Bean added. “It will hurt them, but it will hurt the Russians who have picked up the business, the Russians that distribute its product — it hurts them more.”                                                                                                                                                                                                                                                                                                                                             , Some companies — like Yum Brands and Papa John’s, which have hundreds of restaurants bearing their names across Russia — most likely have less control over whether those restaurants close because many are owned by individuals or groups of investors through franchise agreements, franchise experts said.                                                                                                                                                                                                                                                       , “It’s messy,” said Ben Lawrence, a professor of franchise entrepreneurship at Georgia State University. As long as the franchisees are meeting the requirements under their agreement and paying the royalty fees, it’s hard to tell them to shut down, he said.                                                                                                                                                                                                                                                                                                     , Yum, which owns KFC and Pizza Hut, said on Tuesday that it was suspending operations at 70 company-owned KFCs and all 50 franchise-owned Pizza Huts in Russia. (The vast majority of the 1,000 KFCs in Russia are franchise-owned and, at this time, not part of these suspensions.) Yum also said it would suspend all “investment and restaurant development” in Russia and divert any profits from the region to humanitarian efforts.                                                                                                                            , McDonald’s, which has invested millions of dollars into building restaurants in Russia and is a symbol of American culture, has felt the impact of geopolitics before. In 2014, when the United States and other nations imposed economic sanctions on Russia over its annexation of Crimea, the authorities suddenly closed down a number of McDonald’s locations in Russia, including in Pushkin Square, citing sanitary conditions. The Pushkin Square location reopened 90 days later.                                                                           , For the better part of the last two decades, Russia has been one of the fastest-growing markets for American brands, particularly fast-food chains. McDonald’s, KFC, Subway and others thrived not only because they were a midday glimpse of Western civilization but also because they were relatively cheap places to grab a meal.                                                                                                                                                                                                                                , Rising concerns. Russia’s attack on Ukraine has started reverberating across the globe, adding to the stock market’s woes and spooking investors. The conflict could cause​​ dizzying spikes in prices for energy and food, and severely affect various countries and industries.                                                                                                                                                                                                                                                                                      , The cost of energy. Oil prices already are the highest since 2014, and they have jumped as the conflict has escalated. Russia is the third-largest producer of oil, providing roughly one of every 10 barrels the global economy consumes.                                                                                                                                                                                                                                                                                                                           , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders have accused Russia’s president, Vladimir V. Putin, of reducing supplies to gain a political edge.                                                                                                                                                                                                                                                                 , Food prices. Russia is the world’s largest supplier of wheat and, together with Ukraine, accounts for nearly a quarter of total global exports. In countries like Egypt and Turkey, that flow of grain makes up more than 70 percent of wheat imports.                                                                                                                                                                                                                                                                                                               , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                                                                                                                                                                                                        , Financial turmoil. Global banks are bracing for the effects of sanctions intended to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                                                                                                                                                                                                                 , Visits to fast-food restaurants in Russia in 2018 grew 13 percent, according to a report by the research firm NPD Group, as consumers turned to the inexpensive restaurants for “the best in terms of price and portion size.” Last year, traffic jumped 21 percent as the industry rebounded from Covid-19, the group noted.                                                                                                                                                                                                                                        , “I could succeed in my sleep, there is so much opportunity here,” Christopher Wynne said in a New York Times interview in 2011. A Colorado native who arrived in Russia with the National Nuclear Security Administration in the early 2000s, Mr. Wynne soon saw other opportunities, buying into and becoming the largest Papa John’s pizza franchisee in Russia. (He also owned restaurants in Poland and Germany.)                                                                                                                                                , In May last year, Mr. Wynne’s company, PJ Western, which now holds the exclusive rights to sell Papa John’s pizza in the region, showed plans to open about 30 stores each year in Russia through 2029 and forecast that sales would more than quadruple during that time.                                                                                                                                                                                                                                                                                           , The document also shows the close ties that Mr. Wynne has forged with others to expand the business in Russia. Partners include Alex Ovechkin, the Washington Capitals hockey star, who has previously expressed support for Vladimir V. Putin, the Russian president; the Finnish private-equity firm CapMan; and the Russian private-equity firm Baring Vostok.                                                                                                                                                                                                    , Emails sent to PJ Western, Papa John’s, Mr. Ovechkin, CapMan and Baring Vostok seeking comment were not returned.                                                                                                                                                                                                                                                                                                                                                                                                                                                    , After McDonald’s recognized the precariousness of its position in 2014, it worked hard to show that it is one of the most “Russified” foreign corporations in the country, said Mr. Carena, the former managing director of McDonald’s Russia. The company, which owns 84 percent of its 847 restaurants in Russia, employed tens of thousands of people, sourced all of its food and packaging locally and was the largest taxpayer to Russia in the food industry, Mr. Carena told CEO Magazine a year ago. (He now works for the confection company Mars Wrigley.), “Over the last two years, we’ve been more proactive in showing the authorities how Russified we are and how much we really do contribute to the economy,” Mr. Carena told the magazine. “We produce everything locally, and, apart from me, everyone else in the company is Russian. We are very much local, and we support local businesses and communities.”                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 08:10:00 </td>
   <td style="text-align:left;"> US Futures Mixed After Volatile Session </td>
   <td style="text-align:left;"> US stock futures were mixed in Asian trade on Wednesday following another volatile session on Wall Street, as the war in Ukraine and resulting surge in commodity prices continued to weigh on investor sentiment. Dow futures rose 0.1%, S&amp;P 500 futures were flat and Nasdaq 100 futures shed 0.2%. In regular trading on Tuesday, the Dow slid 0.56% and the S&amp;P 500 lost 0.72%, with both indexes falling deeper into correction territory, while the Nasdaq shed 0.28% after entering bear market territory on Monday. The consumer defensive, healthcare and basic materials sectors led the declines, while the energy sector outperformed. US president Biden announced a ban on Russian oil and other energy imports on Tuesday, rattling the markets and stoking fears about a slowdown in global growth amid surging inflation. Britain also said it will phase out Russian oil and oil products by the end of 2022, with markets being wary of a ban in Europe given its heavy reliance on Russian energy supplies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/08/politics/zelensky-ukraine-churchill-what-matters/index.html </td>
   <td style="text-align:left;"> 2022-03-09 08:06:22 </td>
   <td style="text-align:left;"> Zelensky is not Churchill. He's a more unlikely hero. - CNNPolitics </td>
   <td style="text-align:left;"> A version of this story appeared in CNN's What Matters newsletter. To get it in your inbox, sign up for free here.                                                                                                                                                                    ,  (CNN)What was he thinking going into the office?                                                                                                                                                                                                                                     , Ukrainian President Volodymyr Zelensky is an obvious target for the Russian invaders. And yet there he was, appearing Monday night from his official workplace in Kyiv, in a video that was part selfie and part doomsday presidential address.                                       , The former comedian started things off with what seemed to be a dark joke about the workweek.                                                                                                                                                                                         , "You know, we used to say: Monday is a hard day," he said, according to a translation. "There is a war in the country. So every day is Monday. And now we are used to the fact that every day and every night are like that."                                                         , Most Americans used to know Zelensky only as a background player -- the President of a smaller country who wouldn't dig up dirt on Joe Biden for Donald Trump in an infamous phone call.                                                                                              , No Trump. But while Trump used social media to beat down opponents like a bully and chip away at confidence in American democracy, Zelensky is using short internet videos and social media posts to build up support for his own democracy as it faces extinction.                   , The Churchill comparison. Zelensky deserves awe and praise, and the comparisons to Winston Churchill are coming from the left, the right and the media. The thinking is that Zelensky has traded Churchill's wireless radio and bowler hat for his own smartphone and a green T-shirt., Zelensky invited the comparison on Tuesday when he riffed on Churchill's most famous speech, delivered at Britain's darkest hour and broadcast to inspire the country.                                                                                                                , As he addressed the UK House of Commons via video, Zelensky compared Ukraine's struggle now to Britain's back then.                                                                                                                                                                   , England under Churchill wouldn't bend to the fascists.                                                                                                                                                                                                                                , Ukraine under Zelensky won't roll over for Vladimir Putin.                                                                                                                                                                                                                            , "We will not give up and we will not lose. We will fight until the end at sea, in the air. We will continue fighting for our land, whatever the cost," he said in his comments translated by an interpreter, echoing some of Churchill's words.                                       , The House of Commons cheered Zelensky and gave him a standing ovation.                                                                                                                                                                                                                , Yet, while the West has imposed crippling sanctions on Russia, it has not yet cut off the supply of Russian oil to Western countries. And it seems unlikely the US will give him the no-fly zone he wants to protect Ukrainians from Russian air power.                               , There could be some kind of half-measure. Poland has offered its Soviet-era MiG fighter jets to Ukraine via the US if the US will give Poland some US-made aircraft.                                                                                                                  , A key difference. Churchill held out hope that the US would join World War II, which it ultimately did.                                                                                                                                                                               , Zelensky has been told definitively that the US will not raise arms against nuclear-armed Russia because it could set off World War III.                                                                                                                                              , Better comparisons. I put the Churchill argument to Douglas Brinkley, the American presidential historian, in a phone call. He rejected them as overwrought.                                                                                                                          , Churchill had already been a wartime leader, a war hero, a scandal survivor and a prolific writer by the time he took over as prime minister in 1940. He was an imperialist rather than a pure believer in democracy.                                                                 , It's more Vaclav Havel than Churchill, argued Brinkley, pointing out that Havel was an absurdist playwright whose movement in Czechoslovakia -- the Velvet Revolution -- was named for a Western rock band, the Velvet Underground.                                                   , "Havel oozed democracy and had seen totalitarianism up close," Brinkley said. "Nobody thought Havel, a playwright, could end up being a great world leader, and he did."                                                                                                              , He pointed to Lech Walesa, a trade unionist in Poland who ended up being a revolutionary and inspirational leader.                                                                                                                                                                    , Both men rode a wave of revolution in Eastern Europe in 1989.                                                                                                                                                                                                                         , He also pointed to Ronald Reagan, who "was making movies with chimpanzees -- 'Bedtime for Bonzo' -- and he ended up being the president to preside over the breakdown of the Berlin Wall."                                                                                            , "Entertainers have an edge, because they're able to communicate with people in a time of crisis. That's what you need most," Brinkley said -- although none of them had a Russian invasion on his hands.                                                                              , Zelensky will go down in history. The Ukrainian President's bravery in the face of impossible odds -- Putin's invasion may be clumsy so far, but Russia has a massive army and resources -- also has a David and Goliath element to it.                                               , It's like the lone protester in Tiananmen Square in Beijing, George Washington in Valley Forge or Davy Crockett at the Alamo, Brinkley said.                                                                                                                                          , "It's the stuff of true grit and courage, and I think Zelensky is going to go down in history as one of these democratic martyrs, you know, a martyr for democracy," he said.                                                                                                         , "He's holed up, surrounded by enemy forces and is able to communicate with the world in such a smart, a charismatic, passionate and visceral way."                                                                                                                                    , What has made Zelensky so inspiring -- his courage -- is what he should now tamp down in order to lead, according to some supporters.                                                                                                                                                 , Rep. Mike Waltz of Florida, a Republican and a combat veteran, said Sunday on CNN that Zelensky is "turning out to be a 21st-century Churchill." But he wants the Ukrainian leader to be a little more careful.                                                                       , "If you look at history, George Washington kept our revolution alive by staying alive," Waltz said, later adding, "At this point, I would like to see him go to ground and at this point, his mission is to live and continue to serve as a symbol of resistance."                    , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/gdp-growth </td>
   <td style="text-align:left;"> 2022-03-09 08:06:00 </td>
   <td style="text-align:left;"> Japan Q4 GDP Growth Revised Lower </td>
   <td style="text-align:left;"> The Japanese economy grew by 1.1% qoq in Q4 2021, compared with a flash figure of 1.3% and after a  0.7% contraction in Q3, as pressures from record COVID-19 infections and rising energy costs heightened. Both household consumption (2.4% vs 2.7% in preliminary reading and after a 1% fall in Q3) and business investment (0.3% vs 0.4% in flash data and after a 2.4% drop previously) grew less than initially anticipated. At the same time, both government spending (-0.4% vs -0.3% in preliminary print and after a 1.1% rise in Q3) and public investment  (-3.8% vs flash data -3.3% and after a 3% fall in Q3) declined more than initially thought. Meanwhile, net external demand contributed positively to the GDP, as exports recovered (0.9% vs 1% in preliminary figure and following a 0.3% fall in Q3) while imports continued to fall (-0.4% vs -0.3% in flash figure and after a -1% decline previously). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 08:00:00 </td>
   <td style="text-align:left;"> Stocks in New Zealand Hit 17-month Low </td>
   <td style="text-align:left;"> NZX 50 decreased to a 17-month low of 11725, tracking global stock markets that fell Tuesday as oil prices rose further amid reports that the US bans Russian oil and other energy imports over Moscow's invasion of Ukraine. Traders were also nervous as they await the US Consumer Price for February later in the week. The figure is expected to climb 7.9% yoy, the highest in four decades, compared with 7.5% in January. Locally, the Reserve Bank of New Zealand said recently that interest rates, which now stands at 1%, are projected to reach 2.2% by the end of this year and 2.57% by March 2023, which is a more aggressive path than the 2.1% and 2.3% seen in November's projections. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/08/politics/poland-jets-ukraine-russia/index.html </td>
   <td style="text-align:left;"> 2022-03-09 07:48:35 </td>
   <td style="text-align:left;"> Poland's proposal to transfer MiG-29 fighter jets to US to give to Ukraine isn't 'tenable,' Pentagon says - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)The Pentagon on Tuesday evening dismissed Poland's proposal floated hours earlier to transfer its MiG-29 fighter jets to the United States for delivery to Ukraine.                                                                                                                                                                                                                                           , Pentagon press secretary John Kirby said in a statement that the Pentagon did not believe Poland's proposal was "tenable," just hours after Polish officials released a statement saying the government was ready to deploy all of its MiG-29 fighter jets to US Air Force's Rammstein Air Base in Germany so they could then be provided to Ukraine in its fight against Russia.                                   , "It is simply not clear to us that there is a substantive rationale for it," Kirby said. "We will continue to consult with Poland and our other NATO allies about this issue and the difficult logistical challenges it presents, but we do not believe Poland's proposal is a tenable one."                                                                                                                        , Kirby said that the decision about transferring Polish-owned planes to Ukraine was "ultimately one for the Polish government," adding that the proposal shows the complexities that the issue presents as Russia has made threatening statements over arms being provided to Ukrainians for use against Russian forces.                                                                                             , The idea as laid out by Poland was too risky, Kirby said, as the US and NATO seek to avoid an outright conflict between the alliance and Russia.                                                                                                                                                                                                                                                                    , "The prospect of fighter jets 'at the disposal of the Government of the United States of America' departing from a U.S./NATO base in Germany to fly into airspace that is contested with Russia over Ukraine raises serious concerns for the entire NATO alliance," Kirby said.                                                                                                                                     , Biden administration caught off guard                                                                                                                                                                                                                                                                                                                                                                               , The Defense Department statement was released Tuesday evening after the Polish proposal caught the Biden administration completely off guard, multiple sources told CNN.                                                                                                                                                                                                                                            , While Ukrainian President Volodymyr Zelensky has pleaded for more aircraft amid the Russian invasion, the offer had not been discussed with the US before making it public and Polish officials did not bring it up with Secretary of State Antony Blinken when he was recently in Poland either.                                                                                                                   , US officials have privately weighed sending aircraft to Ukraine but have repeatedly noted the difficult logistical challenges of doing so.                                                                                                                                                                                                                                                                          , Poland's surprise announcement complicates what had already been a high-stakes visit by Vice President Kamala Harris, who is due to land in Warsaw late Wednesday.                                                                                                                                                                                                                                                  , Harris had been expected to discuss the fighter jet issue while in Poland, according to officials. The White House had previously said it was in discussions with the Polish government about a plan for Poland to supply Ukraine with its Soviet-era fighter jets and the US to backfill the planes with F-16s.                                                                                                    , Harris is still scheduled to depart Wednesday morning for Poland, but now there are intensive conversations within the administration about how to work with Poland to come to some sort of agreement that allows the jets to reach Ukraine.                                                                                                                                                                        , A top State Department official said Tuesday that Poland did not consult with the United States prior to issuing its statement.                                                                                                                                                                                                                                                                                     , "I saw that announcement by the government of Poland as I was literally driving here today," Undersecretary of State for Political Affairs Victoria Nuland said during a Senate Foreign Relations Committee hearing.                                                                                                                                                                                                , Nuland noted that the US and Poland have been in consultations for a couple of days on the possibility, but added she had come to the hearing directly from a meeting "where (she) ought to have heard about."                                                                                                                                                                                                      , "So I think that actually was a surprise move by the Poles," Nuland told lawmakers.                                                                                                                                                                                                                                                                                                                                 , 'Ready to deploy'                                                                                                                                                                                                                                                                                                                                                                                                   , The Polish government said in a statement Tuesday that it is "ready to deploy -- immediately and free of charge -- all their MiG-29 jets to the Ramstein Air Base and place them at the disposal of the Government of the United States of America."                                                                                                                                                                , "At the same time, Poland requests the United States to provide us with used aircraft with corresponding operational capabilities. Poland is ready to immediately establish the conditions of purchase of the planes," the statement said.                                                                                                                                                                          , Speaking to US lawmakers virtually on Saturday, Zelensky asked for American support to facilitate the transfer of Soviet-era fighter jets from Eastern European nations to Ukraine, where pilots have been trained to fly them and could use them to attempt to control the skies as Russia conducts its war against the country.                                                                                   , By Saturday evening, US and Polish officials were in discussions about a potential agreement to supply the country with American F-16 fighter jets in exchange for Poland sending its Russian-made jets to Ukraine.                                                                                                                                                                                                 , "We are working with Poland as we speak to see if we can backfill anything that they provide to the Ukrainians," Blinken said on CBS on Sunday. "But we also want to see if we can be helpful in making sure that, whatever they provide to Ukrainians, something goes to them to make up for any gap in the security for Poland that might result."                                                                , On Monday, a Pentagon spokesman said the Department of Defense was in "interagency" discussions to "examine" the possibility of the US sending fighter jets to other European countries if those countries choose to send fighter jets of their own to Ukraine.                                                                                                                                                     , Prior to the apparent dismissal of Warsaw's proposal by the Biden administration, members of Congress appeared supportive of the move. During Tuesday's Senate Foreign Relations Committee hearing, Democratic Sen. Ben Cardin asked Nuland to ensure the Biden administration notifies Congress if there are going to be any delays getting F-16s to Poland.                                                       , Two European diplomats told CNN on Tuesday, prior to the Pentagon statement, that the complicated logistics behind the idea of Poland giving the jets to Ukraine had not yet been finalized.                                                                                                                                                                                                                        , The Polish announcement came after some Polish officials expressed frustration about how forward leaning the US was on this subject over the weekend, the sources said.                                                                                                                                                                                                                                             , "In fact, we're talking with our Polish friends right now about what we might be able to do to backfill their needs if, in fact, they choose to provide these fighter jets to the Ukrainians. What can we do? How can we help to make sure that they get something to backfill the planes that they're handing over to the Ukrainians? We're in very active discussions with them about that," Blinken said Sunday. , A Polish official told CNN they believed Harris' trip would be a good time for the US to announce more details about aircraft transfers, but the Pentagon statement suggests such a possibility is unlikely.                                                                                                                                                                                                        , Other countries that are in talks with the US about taking part in similar transfers are conducting the conversations quietly, without raising expectations, said a central European diplomat.                                                                                                                                                                                                                      , CNN's Kaitlan Collins, Kevin Liptak and Barbara Starr contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-09 07:15:00 </td>
   <td style="text-align:left;"> Australia 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Australia 10 Year Government Bond Yield increased to a 3-year high of 2.315%, ahead of Thursday’s US CPI report amid heightened risks from the worsening Russia-Ukraine conflict that clouded the outlook for global growth and inflation. The US inflation report for February was set to show prices rising at their fastest pace in 40 years, reflecting  a preliminary impact from surging oil prices. In Australia, the Reserve Bank of Australia mentioned  earlier in the month that the war in Ukraine was a major new source of uncertainty as policymakers held cash rate unchanged at a record low of 0.1%. Meantime, the central bank governor Phillip Lowe recently said the board could raise rates later this year if Australia's economy continued to surprise, with market participants betting on a rate hike as early as July. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/08/europe/kyiv-defense-ukraine-russia-intl-cmd/index.html </td>
   <td style="text-align:left;"> 2022-03-09 07:05:19 </td>
   <td style="text-align:left;"> Kyiv has transformed into a fortress, with its residents determined to defend it - CNN </td>
   <td style="text-align:left;"> Kyiv, Ukraine (CNN)Just two weeks ago, residents of the Ukrainian capital were tending to their shops, teaching schoolchildren or parked at their office desks.                                                                                                                                                                                                                             , The Russian invasion changed all that. Fighting literally for their lives, civilians, turned into volunteer soldiers, helped construct defenses with military precision -- and they are now manning them.                                                                                                                                                                                   , Trenches run deep into the woods that surround the highway leading in Kyiv from the south. Fortified fallback positions are ready for whatever comes next. Huge metal anti-tank barriers known here as "the hedgehogs" because of their spiky shape are placed at regular intervals along the road. And makeshift blockades made of sandbags and huge concrete blocks stand at every exit.. , The people of Kyiv are determined to defend their city.                                                                                                                                                                                                                                                                                                                                     , As Russian forces approach, the resolve of its residents is palpable -- with many appearing in good spirits.                                                                                                                                                                                                                                                                                , Some flash a victory sign as vehicles pass by. The blue and yellow national flag can be seen everywhere.                                                                                                                                                                                                                                                                                    , At one checkpoint en route to Kyiv on Tuesday, volunteer defenders were handing out flowers to women in their cars to mark International Women's Day.                                                                                                                                                                                                                                       , Many volunteers do not seem to be dressed warm enough for the freezing weather. They wear civilian clothes, with big coats and sweatpants an unofficial uniform. Their pants are mostly green, black or camouflage motif  -- not the military kind -- but the civilian pattern made for hunting.                                                                                            , Some, but not all volunteers, are armed with automatic rifles and big knives.                                                                                                                                                                                                                                                                                                               , Oleksiy Goncharenko, a volunteer manning one of the defense positions in Kyiv, told CNN that he works in four-hour shifts at the checkpoint.                                                                                                                                                                                                                                                , His face is red from the cold. "It's OK. Just cold," he says, adding that "locals are giving us soups and things like that."                                                                                                                                                                                                                                                                , Almost 40,000 volunteers joined the Territorial Defense Forces in the first two days after the invasion began, according to the Ukrainian armed forces' chief of staff. In Kyiv alone, 18,000 picked up weapons when authorities called for volunteers and reservists to do so.                                                                                                             , Those who couldn't join the forces (so many people signed up that the Territorial Defense Forces had to start turning people away) are helping in other ways.                                                                                                                                                                                                                               , They are making Molotov cocktails, sewing camouflage nets for barricades, distributing food, hot drinks and cigarettes to those standing guard. They are raising money for the military, building more road blocks and even painting over traffic signs in an attempt to confuse invading forces.                                                                                           , 'You will not be alone'                                                                                                                                                                                                                                                                                                                                                                     , Kateryna Yurko, whose store was destroyed when a Russian missile hit nearby last week, is now spending her time driving back and forth between Kyiv and the Polish border,  bringing humanitarian aid for infants and the elderly. She has also made Molotov cocktails for the troops, she says.                                                                                            , Oleksii Erinchak, who runs a bookstore and coffee shop in central Kyiv, has turned the space into a volunteer hub.                                                                                                                                                                                                                                                                          , "We are trying to prepare ourselves for the worst-case scenario where we would be surrounded by Russian troops and all the supply networks would be destroyed. So we are trying to make sure that everyone and every building is prepared for this," he told CNN.                                                                                                                           , Another project the volunteers are working on is trying to encourage people to get to know their neighbors -- something that's not that common in a big city.                                                                                                                                                                                                                               , "If everything is blocked -- no internet connection, no phone calls -- you will be together with your neighbors (and) they can help you, you will not be alone," Erinchak said. Most of his work now focuses on establishing neighborhood networks for food and medicine distributions.                                                                                                     , But Erinchak is still selling books, too, "...because there should be something normal happening, even in this situation," he said. The coffees, however, are free.                                                                                                                                                                                                                         , Closer to the city center, the defenses are stronger.                                                                                                                                                                                                                                                                                                                                       , But here, it's the professionals manning the checkpoints. Tanks and weapon launchers are in position along the city's main arteries.                                                                                                                                                                                                                                                        , Kyiv's famed Maidan Square, which sits in the heart of the capital, is now a fortress. A big Ukrainian flag flies high above the site of the 2014 protests.                                                                                                                                                                                                                                 , The capital's parks now serve as staging grounds for military vehicles; shopping areas lined with boutiques, hip cafes and fancy restaurants are now bordered with barriers made of sandbags and blocks of concrete.                                                                                                                                                                        , And electronic signs that normally display traffic information and commercials are now calling for "NATO to close the skies" and proclaiming "Glory to Ukraine."                                                                                                                                                                                                                            , One of those signs addresses Russian troops directly. "Russian soldiers, stop. How can you look your children in the eye. Go home and be human," it reads.                                                                                                                                                                                                                                  , Near Kyiv police headquarters, eight men -- two policemen and six National Guards -- man a checkpoint, stopping every vehicle that comes through.                                                                                                                                                                                                                                           , National Guard reservist Oleksandr, who asked CNN to only use his first name for his safety, said that he spends six hours at the post, then takes six hours to rest.                                                                                                                                                                                                                       , Usually, that means four hours sleep and two hours for anything else that needs to be taken care of: a shower, a shave, change of clothes, or a quick message to his family. Six hours is a long time to stand in the snow, he says -- it's cold.                                                                                                                                           , Around the corner, a small shop remains open, even as every other business around it have closed. Liudmyla, who runs the shop, supplies coffee and cigarettes to the soldiers protecting the road in front of her store.                                                                                                                                                                    , There aren't many other customers these days, says Liudmyla, who asked CNN to only be referred by her first name for safety reasons.                                                                                                                                                                                                                                                        , Most people are staying at home and are not venturing into the city center. Instead, they remain huddled in basements and subway stations. Liudmyla says she is determined to stay open and has brought in her husband Dmytro for support. "I work. He is protecting me," she says.                                                                                                         , She says that "there are no words, emotions or reactions that could describe how I feel."                                                                                                                                                                                                                                                                                                   , "We don't know which day of week is today, but we know for sure it's the thirteenth day of war," she says, adding that she believes that Ukrainians will be "victorious."                                                                                                                                                                                                                   , Instead of a goodbye, Liudmyla ends our conversation with what many are thinking here: "Putin is a d***!"                                                                                                                                                                                                                                                                                   , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/08/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-03-09 07:04:32 </td>
   <td style="text-align:left;"> S&amp;P 500 futures are flat as investors continue to assess rising commodities prices and the ongoing war in Ukraine </td>
   <td style="text-align:left;"> , S&amp;P 500 futures were flat Tuesday evening as investors continued to assess a surge in commodity prices and high inflation while the war in Ukraine continues.                                                                                                                                                                                                                                           , Futures tied to the Dow Jones Industrial Average rose 47 points, or 0.1%. S&amp;P 500 futures were flat and Nasdaq 100 futures lost 0.1%.                                                                                                                                                                                                                                                                   , The major averages all closed lower after a day of choppy trading. The Dow gave up a 585-point gain to end the day lower by 184 points, or 0.5%, falling deeper into its correction. The S&amp;P 500 slid 0.7%, also moving into correction territory. The Nasdaq Composite lost 0.2%, after entering bear market territory Monday.                                                                         , The market volatility was driven by uncertainty among investors as they continued to assess surging prices in commodities like oil, gasoline, natural gas and precious metals. That fueled concerns about a slowdown in global growth amid surging inflation.                                                                                                                                           , It remains to be seen if the Federal Reserve will manage a soft economic landing, but the U.S. should be able to avoid a recession, according to Ross Mayfield, investment strategy analyst at Baird.                                                                                                                                                                                                   , "The strength of the U.S. labor market, consumer and aggregate corporate sector should act as the weight to keep us out of recession near-term," he told CNBC. "Overall, volatility is likely to persist, [there's a] wide range of outcomes possible in Ukraine, but the fundamentals of the U.S. economy still look decent, especially if the Fed can navigate raising rates without breaking demand.", Goldman says buy these global stocks to beat the volatility — and gives several over 50% upside                                                                                                                                                                                                                                                                                                         , Wall Street says these Nasdaq stocks have the best shot at bouncing back from the bear market                                                                                                                                                                                                                                                                                                           , Nickel surge just raised the input cost for an electric vehicle by $1,000, Morgan Stanley estimates                                                                                                                                                                                                                                                                                                     , Energy stocks were a bright spot in the market as oil prices continued to climb, jumping to their highs of the session as President Joe Biden announced a ban on Russian fossil imports, including oil, in response to the country's invasion of Ukraine. That was after oil hit a 13-year high of $130 to start the week.                                                                              , Other commodity prices resumed their push higher, including nickel, which touched a new record above $100,000 a metric ton.                                                                                                                                                                                                                                                                             , Treasury yields also spiked, with the benchmark 10-year note adding close to 10 basis points to 1.85%, as inflation fears led investors to shed bonds.                                                                                                                                                                                                                                                  , Earnings continue Wednesday with Campbell Soup, Crowdstrike and Marqeta all set to report.                                                                                                                                                                                                                                                                                                              , On the economic data front, investors are looking forward to homebuying data from the Mortgage Bankers Association as well as the job openings and labor turnover survey, or JOLTS.                                                                                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/manufacturing-sales </td>
   <td style="text-align:left;"> 2022-03-09 06:52:41 </td>
   <td style="text-align:left;"> New Zealand Manufacturing Sales Rebound </td>
   <td style="text-align:left;"> Manufacturing sales in New Zealand advanced 1.2 percent from a year earlier in the third quarter of 2021, rebounding from an upwardly revised 6.4 percent decrease in the previous period. On a seasonally adjusted quarterly basis, total manufacturing sales went up by 12 percent. The largest industry movements were metal (25.8 percent), petroleum and coal products (17.1 percent), and beverage and tobacco (15.8 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 06:29:35 </td>
   <td style="text-align:left;"> Brazilian Stocks Extend Losses to 6-Week Low </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Ibovespa, pared early gains to close 0.4% lower at 111,203, the lowest since January, as losses in commodity-backed stocks more than offset gains in the energy sector. Oil prices rose further following news that the US and the UK announced measures against the imports of Russian oil and energy products, a move that will likely intensify inflationary pressures. Domestically, Vale (-4.4%) led the losses amid the miners. Also, a Brazilian Senate committee has requested that executives of state-run oil company Petrobras (5%) take part in a hearing to explain its dividend policy, at a moment when pressure on the firm grows amid high oil prices. Brazil's government is reportedly considering putting in place a new diesel and gasoline subsidy program to soften the blow of soaring oil prices after Russia's invasion of Ukraine, using dividends from state-run oil firm Petrobras to fund the measure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/xpo-logistics-stock-soars-nearly/story.aspx?guid={CFEE72F8-D761-40FC-BBE7-A1DFF7126B6A}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-09 06:17:58 </td>
   <td style="text-align:left;"> XPO Logistics stock soars nearly 9% after company to split itself into two businesses - MarketWatch </td>
   <td style="text-align:left;"> XPO Logistics Inc. 
        XPO,
        +2.72%
       stock rallied more than 8% in the extended session Tuesday after the logistics company announced plans to split itself into two publicly traded companies, a deal it said would be tax-free to shareholders. One of the companies would encompass XPO's freight brokerage business, which matches loads from shipping customers to available trucks to carry them, and the other its U.S. trucking business. Its European business and North American intermodal operations would be sold. The company said it expects to complete the spin-off in the fourth quarter of 2022, subject to various conditions, including a final approval of the XPO board of directors. In a presentation to shareholders, XPO pegged 2021 revenue from its freight brokerage company at $4.8 billion, and from the trucking business at $4.1 billion. Shares of XPO ended the regular trading day up 2.7%., A Yale professor and his research team are keeping tabs on companies that are still operating in Russia following its invasion of Ukraine --- and the list includes many household names.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 06:11:02 </td>
   <td style="text-align:left;"> Canadian Shares Edge Lower on Tuesday </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite Index closed 0.3% lower at 21,232 on Tuesday, extending last session’s 0.5% decline as jitters of rampant inflation more than offset the gains in commodity-backed stocks. Concerns of slower growth and higher consumer prices pressured tech sector equities to fall 1.8%, while industrials retreated 1.3%. Energy stocks closed muted after trading over 2.5% higher at 5-year highs, following reports that the US and the UK will impose a ban on Russian energy imports in retaliation to Moscow’s invasion of Ukraine. At the same time, inflation fears and supply shortages due to the Russian invasion spurred rallies across bullion and other metals, lifting mining stocks by 0.8%. Among individual shares, Intertape Polymer soared 76.2% after the packaging products maker announced it would taken private by investment firm Clearlake Capital in a deal valued at USD 2.6 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/energy-industry-biden-oil-ban-russia </td>
   <td style="text-align:left;"> 2022-03-09 06:02:56 </td>
   <td style="text-align:left;"> Biden's Russia oil ban: Energy industry reps laud move, say it's 'befuddling' president won't back US energy </td>
   <td style="text-align:left;"> Sean Strawbridge, CEO of Port Corpus Christi, says the US oil and energy sector is facing 'headwinds' from the Biden administration's policies.                                                                                                                                                                                                                                                                                                                                  , HOUSTON – Energy industry representatives Tuesday said that President Biden's ban on Russian oil underscores the need to increase domestic energy production and panned the administration's lack of interest in doing so as "befuddling."                                                                                                                                                                                                                                       , National Ocean Industries Association president Erik Milito touted the resources available just off the United States' coastline as an asset to help keep the U.S. and its allies from being reliant on countries like Russia.                                                                                                                                                                                                                                                   , "That simply highlights the importance of producing and getting our industry here domestically in the U.S. We represent the Gulf of Mexico offshore sector, and we've been getting, you know, a million barrels a day from the Gulf of Mexico for the last 25 years," he said. "Peak production hit right before the pandemic at 2 million barrels per day. So this is a really important asset that we have strategically in our backyard that we need to continue to rely on." , Erik Milito, President of the National Ocean Industries Association, weighs in on the Biden administration's decision to ban Russian oil.                                                                                                                                                                                                                                                                                                                                        , ENERGY INDUSTRY SWIPES BACK AT PSAKI ‘RED HERRING’ COMMENT ON OIL AND GAS LEASES                                                                                                                                                                                                                                                                                                                                                                                                 , Milito made the comment at the CERAWeek by S&amp;P Global energy conference in Houston.                                                                                                                                                                                                                                                                                                                                                                                              , Biden announced the ban on Russian oil imports, which make up just a fraction of U.S. oil imports, on Tuesday morning after more than a week of building pressure from Congress. The president slammed "the Russian Federation’s unjustified, unprovoked, unyielding, and unconscionable war against Ukraine" as the justification for the ban.                                                                                                                                  , He denied that his administration had stymied oil production in the U.S. It's "simply not true that my administration or policies are holding back domestic energy production," Biden said. "We’re approaching record levels of oil and gas production in the United States, and we’re on track to set a record of oil production next year."                                                                                                                                    , President Joe Biden and the White House COVID-19 Response Team participate in a virtual call with the National Governors Association from the South Court Auditorium of the Eisenhower Executive Office Building of the White House Complex on Monday, Dec (Kent Nishimura / Los Angeles Times via Getty Images / Getty Images)                                                                                                                                                  , "Certainly this administration needed to do more if it really wanted Mr. Putin and the Russian economy to be affected by his actions in the Ukraine. It's certainly unsurprising, although it did take him a little longer to come to this conclusion," Port of Corpus Christi CEO Sean Strawbridge also said.                                                                                                                                                                   , He added: "Industry has recognized that Western Europe's dependency on Russian energy has been growing. And yet, at the same time, discouraging American production is certainly something that's befuddling for us."                                                                                                                                                                                                                                                            , BIDEN ANNOUNCES BAN ON US IMPORTS OF RUSSIAN OIL, WARNS GAS PRICES WILL ‘GO UP FURTHER’                                                                                                                                                                                                                                                                                                                                                                                          , Others have highlighted that the administration delayed banning Russian oil imports for about two weeks after Russia began its invasion of Ukraine.                                                                                                                                                                                                                                                                                                                              , A source close to a bipartisan bill in the House of Representatives that would have banned Russian oil imports told Fox News the Biden White House worked to block that bill — and a similar one in the Senate — over the weekend. The source said they believe the White House did not want to appear boxed in by Congress on the issue.                                                                                                                                        , Former Acting Deputy Energy Secretary Jeff Kupfer, who served under former President George W. Bush, told FOX Business Tuesday that despite the fact he agrees with the ban on Russian oil, it still appears Biden was forced into the move.                                                                                                                                                                                                                                     , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                          , "I think it was the right move. They ultimately in some way got pushed into it," Kupfer said. "I mean, they weren't necessarily supportive of it at first, but with the bipartisan pressure from the Hill, it sort of left them no choice but to do it."                                                                                                                                                                                                                         , President of Conserve Energy Jeffrey Kupfer discusses the Biden administration's ban on Russian oil imports with Fox News' Tyler Olson.                                                                                                                                                                                                                                                                                                                                          , Kupfer served as an executive at Chevron and Atlas Energy after his government service. Now he works for the right-leaning group ConserveAmerica, which aims to promote "sound environmental and conservation policy."                                                                                                                                                                                                                                                           , Kupfer also said that the oil ban won't necessarily be as "disruptive" to gas prices as it may have been at the beginning of the war because markets "had already begun to reflect and price in the ban on US imports of Russian oil."                                                                                                                                                                                                                                           , Fox News' Jacqui Heinrich contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60665877?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-09 05:51:12 </td>
   <td style="text-align:left;"> McDonald’s, Coca-Cola and Starbucks halt Russian sales </td>
   <td style="text-align:left;"> Consumer giants including McDonald's, Coca-Cola and Starbucks have joined the list of firms halting business in Russia due to the invasion in Ukraine.                                                                                                                                                                              , McDonald's said it was temporarily closing its roughly 850 restaurants in Russia, while Starbucks also said its 100 coffee shops would shut.                                                                                                                                                                                        , McDonald's said the move was a response to the "needless human suffering unfolding in Ukraine".                                                                                                                                                                                                                                     , The company said it was "impossible to predict" when it would reopen.                                                                                                                                                                                                                                                               , "The conflict in Ukraine and the humanitarian crisis in Europe has caused unspeakable suffering to innocent people," chief executive Chris Kempczinski said in a memo to staff that was shared publicly.                                                                                                                            , "As a system, we join the world in condemning aggression and violence and praying for peace."                                                                                                                                                                                                                                       , McDonald's said it would continue to pay its roughly 62,000 staff in Russia. The firm has also been experiencing supply chain issues there.                                                                                                                                                                                         , McDonald's, Coca-Cola and other companies have been under pressure to act as Russian violence against civilians has escalated.                                                                                                                                                                                                      , #BoycottMcDonalds and #BoycottCocaCola were trending on Twitter on Monday and over the weekend respectively.                                                                                                                                                                                                                        , Dozens of well-known firms including Netflix and Levi's have already suspended sales or stopped providing services in Russia amid severe sanctions imposed by Western allies.                                                                                                                                                       , McDonald's established its presence in Moscow in 1990, as the Soviet Union was opening its economy, drawing thousands for its burgers and fries.                                                                                                                                                                                    , As tensions with the West increased in 2014 over Russia's annexation of Crimea, some of its restaurants were shut as part of an investigation into food standards, which many saw as politically motivated.                                                                                                                         , The closure now likewise carries symbolic weight, and is likely to influence other firms.                                                                                                                                                                                                                                           , McDonald's owns a majority of its stores in Russia. Combined with Ukraine, the restaurants account for about 9% of the firm's revenue and about 2% of global sales.                                                                                                                                                                 , It has also temporarily closed its 108 restaurants in Ukraine, where it continues to pay salaries and has donated $5m to an employee assistance fund.                                                                                                                                                                               , McDonald's said its Ronald McDonald House Charities would remain active in Ukraine and Russia.                                                                                                                                                                                                                                      , Mr Kempczinski said the firm had made the decision over the last week. In addition to staff, the move will affect hundreds of suppliers and the millions of customers McDonald's serves in Russia each day.                                                                                                                         , The fast food chain joins a growing list of western brands to cut ties with Russia over its attack on Ukraine.                                                                                                                                                                                                                      , Coca-Cola on Tuesday said it was suspending operations in Russia, which accounted for roughly 2% of the firm's operating revenue and income. It also has a roughly 20% ownership stake in a bottling and distribution business in Russia.                                                                                           , Starbucks also announced it would stop all business activity in the country, including shipments of Starbucks products.                                                                                                                                                                                                             , The coffee chain's licensee in the country will temporarily shut more than 100 stores it operates there. The licensee, Kuwait-based Alshaya Group, will continue pay its roughly 2,000 employees, Starbucks said.                                                                                                                   , Others joining the backlash on Tuesday included Unilever, maker of Marmite, Dove beauty products and PG Tips among other brands, which said it had suspended trade with Russia and planned to halt its advertising and media spending and investments there.                                                                        , It said it would continue to supply "everyday essential food and hygiene products" that are made in Russia.                                                                                                                                                                                                                         , L'Oreal, the world's biggest cosmetics company, is also shutting its stores and concessions in Russia and suspending online sales.                                                                                                                                                                                                  , However, some firms have have defended plans to continue operating in Russia, including Uniqlo owner Tadashi Yanai, who told Japan's Nikkei newspaper that "clothing is a necessity of life".                                                                                                                                       , Pepsi, which has a much larger presence in Russia than rival Coca-Cola, said it was halting production and sale of Pepsi and other global soda brands in Russia and suspending capital investments and advertising, citing "horrific events" in Ukraine.                                                                            , But the company, which started operating in Russia during the Cold War and now employs 20,000 people there, said it would continue to offer other products.                                                                                                                                                                         , "As a food and beverage company, now more than ever we must stay true to the humanitarian aspect of our business," boss Ramon Laguarta said. "That means we have a responsibility to continue to offer our other products in Russia, including daily essentials such as milk and other dairy offerings, baby formula and baby food.", Zara McDermott uncovers a dangerous 'rape culture' in Britain's classrooms                                                                                                                                                                                                                                                          , Villanelle curates this mix just for Eve...                                                                                                                                                                                                                                                                                         , Rosemary Laryea reveals the truth about being a 'soccer mum'                                                                                                                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60665877?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-09 05:51:12 </td>
   <td style="text-align:left;"> War in Ukraine: McDonald’s, Coca-Cola and Starbucks halt Russian sales </td>
   <td style="text-align:left;"> Consumer giants including McDonald's, Coca-Cola and Starbucks have joined the list of firms halting business in Russia due to the invasion in Ukraine.                                                                                                                                                                              , McDonald's said it was temporarily closing its roughly 850 restaurants in Russia, while Starbucks also said its 100 coffee shops would shut.                                                                                                                                                                                        , McDonald's said the move was a response to the "needless human suffering unfolding in Ukraine".                                                                                                                                                                                                                                     , The company said it was "impossible to predict" when it would reopen.                                                                                                                                                                                                                                                               , "The conflict in Ukraine and the humanitarian crisis in Europe has caused unspeakable suffering to innocent people," chief executive Chris Kempczinski said in a memo to staff that was shared publicly.                                                                                                                            , "As a system, we join the world in condemning aggression and violence and praying for peace."                                                                                                                                                                                                                                       , McDonald's said it would continue to pay its roughly 62,000 staff in Russia. The firm has also been experiencing supply chain issues there.                                                                                                                                                                                         , McDonald's, Coca-Cola and other companies have been under pressure to act as Russian violence against civilians has escalated.                                                                                                                                                                                                      , #BoycottMcDonalds and #BoycottCocaCola were trending on Twitter on Monday and over the weekend respectively.                                                                                                                                                                                                                        , Dozens of well-known firms including Netflix and Levi's have already suspended sales or stopped providing services in Russia amid severe sanctions imposed by Western allies.                                                                                                                                                       , McDonald's established its presence in Moscow in 1990, as the Soviet Union was opening its economy, drawing thousands for its burgers and fries.                                                                                                                                                                                    , As tensions with the West increased in 2014 over Russia's annexation of Crimea, some of its restaurants were shut as part of an investigation into food standards, which many saw as politically motivated.                                                                                                                         , The closure now likewise carries symbolic weight, and is likely to influence other firms.                                                                                                                                                                                                                                           , McDonald's owns a majority of its stores in Russia. Combined with Ukraine, the restaurants account for about 9% of the firm's revenue and about 2% of global sales.                                                                                                                                                                 , It has also temporarily closed its 108 restaurants in Ukraine, where it continues to pay salaries and has donated $5m to an employee assistance fund.                                                                                                                                                                               , McDonald's said its Ronald McDonald House Charities would remain active in Ukraine and Russia.                                                                                                                                                                                                                                      , Mr Kempczinski said the firm had made the decision over the last week. In addition to staff, the move will affect hundreds of suppliers and the millions of customers McDonald's serves in Russia each day.                                                                                                                         , The fast food chain joins a growing list of western brands to cut ties with Russia over its attack on Ukraine.                                                                                                                                                                                                                      , Coca-Cola on Tuesday said it was suspending operations in Russia, which accounted for roughly 2% of the firm's operating revenue and income. It also has a roughly 20% ownership stake in a bottling and distribution business in Russia.                                                                                           , Starbucks also announced it would stop all business activity in the country, including shipments of Starbucks products.                                                                                                                                                                                                             , The coffee chain's licensee in the country will temporarily shut more than 100 stores it operates there. The licensee, Kuwait-based Alshaya Group, will continue pay its roughly 2,000 employees, Starbucks said.                                                                                                                   , Other major global brands joining the backlash on Tuesday included the world's largest music company, Universal Music Group, which said it was suspending all operations in Russia and closing its offices there.                                                                                                                   , "We urge an end to the violence in Ukraine as soon as possible," the firm said in a statement sent to the BBC.                                                                                                                                                                                                                      , Unilever, maker of Marmite, Dove beauty products and PG Tips among other brands, also said it had suspended trade with Russia and planned to halt its advertising and media spending and investments there.                                                                                                                         , It said it would continue to supply "everyday essential food and hygiene products" that are made in Russia.                                                                                                                                                                                                                         , L'Oreal, the world's biggest cosmetics company, is also shutting its stores and concessions in Russia and suspending online sales.                                                                                                                                                                                                  , However, some firms have have defended plans to continue operating in Russia, including Uniqlo owner Fast Retailing, whose founder told Japan's Nikkei newspaper that "clothing is a necessity of life".                                                                                                                            , Pepsi, which has a much larger presence in Russia than rival Coca-Cola, said it was halting the production and sale of Pepsi and other global brands in Russia and suspending capital investments and advertising, citing "horrific events" in Ukraine.                                                                             , But the company, which started operating in Russia during the Cold War and now employs 20,000 people there, said it would continue to offer other products.                                                                                                                                                                         , "As a food and beverage company, now more than ever we must stay true to the humanitarian aspect of our business," boss Ramon Laguarta said. "That means we have a responsibility to continue to offer our other products in Russia, including daily essentials such as milk and other dairy offerings, baby formula and baby food.", Zara McDermott uncovers a dangerous 'rape culture' in Britain's classrooms                                                                                                                                                                                                                                                          , Villanelle curates this mix just for Eve...                                                                                                                                                                                                                                                                                         , Rosemary Laryea reveals the truth about being a 'soccer mum'                                                                                                                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/api-data-reportedly-show-weekly/story.aspx?guid={DE3C9D5A-0E65-48F6-BD61-47BECB66CB4E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-09 05:45:20 </td>
   <td style="text-align:left;"> API data reportedly show a weekly climb in U.S. crude supplies, but product stocks fall - MarketWatch </td>
   <td style="text-align:left;"> The American Petroleum Institute reported late Tuesday that U.S. crude supplies rose by 2.8 million barrels for the week ended March 4, according to sources. The API also reportedly showed weekly inventory declines of nearly 2 million barrels for gasoline and 5.5 million barrels for distillates. Crude stocks at the Cushing, Okla., delivery hub were down by 367,000 barrels last week, sources said. Inventory data from the Energy Information Administration will be released Wednesday. On average, the EIA is expected to show crude inventories down by 700,000 barrels, according to analysts polled by S&amp;P Global Commodity Insights. The survey also showed expectations for weekly supply declines of 2.2 million barrels for gasoline and 1.8 million barrels for distillates. Oil prices extended their gains in the electronic trading session after the API data. April West Texas Intermediate crude 
        CLJ22,
        +2.10%
       was at $124.53 a barrel in electronic trading, after settling Tuesday at $123.70 on the New York Mercantile - the highest finish for a front-month contract since August 2008 after the U.S. announced a ban on oil from Russia.,  The Pentagon on Tuesday rejected Poland’s offer to give the United States its MiG-29 fighter jets for use by Ukraine, in a rare public display of disharmony by NATO allies seeking to boost Ukrainian fighters while avoiding getting caught up in a wider war with Russia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/white-house-blames-putin-for-skyrocketing-gas-prices </td>
   <td style="text-align:left;"> 2022-03-09 05:30:35 </td>
   <td style="text-align:left;"> White House blames Putin for skyrocketing gas prices </td>
   <td style="text-align:left;"> Sen. Bill Cassidy, R-La., argues that Biden should be ‘focused’ on lowering prices at the pump to help create more jobs for Americans.                                                                                                                                                                                                                                                                                                , White House press secretary Jen Psaki and President Biden blamed Russian President Vladimir Putin on Tuesday for rising gas prices in the United States.                                                                                                                                                                                                                                                                              , "Let me first say that Americans are paying a higher price at the pump because of the actions of President Putin," Psaki told reporters during a press gaggle outside Air Force One in Westworth Village, Texas. "This is a Putin spike at the gas pump, not one prompted by our sanctions.                                                                                                                                           , Biden on Tuesday announced a ban on all imports of Russian oil, gas and energy to the United States, targeting "the main artery" of Russia’s economy amid President Vladimir Putin's war on Ukraine.                                                                                                                                                                                                                                  , Biden, though, warned Americans that the ban would cost American families. Americans are experiencing the highest gas prices since the 2008 financial crisis, with the national gas price average reaching more than $4 per gallon, which is the highest average to date, according to AAA.                                                                                                                                           , Motorist swait in long lines for gas on Mar. 8, 2022, at Sams Club in San Bernardino, California. (Will Lester/MediaNews Group/Inland Valley Daily Bulletin / Getty Images)                                                                                                                                                                                                                                                           , "We have seen since President Putin and the Russian military lined up earlier this year, troops at the border, an increase of about 75 cents on average across the country in terms of what impact this will have," Psaki continued, adding that the steps Biden has taken against Putin were in coordination with European partners and intended "to squeeze the circle around President Putin" in an attempt to change his behavior., RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                                                  , BIDEN ANNOUNCES BAN ON US IMPORTS OF RUSSIAN OIL, WARNS GAS PRICES WILL ‘GO UP FURTHER’                                                                                                                                                                                                                                                                                                                                               , Biden also blamed Putin for the price of gas, telling reporters on the tarmac that gas prices are going to "go up," gesturing with his thumb.                                                                                                                                                                                                                                                                                         , "I can't do much right now," he said. "Russia's responsible."                                                                                                                                                                                                                                                                                                                                                                         , Psaki on Monday said that the Keystone XL Pipeline, the construction of which Biden canceled on his first day in office, would not have made a difference in the price of gas.                                                                                                                                                                                                                                                        , President Joe Biden arrives at Naval Air Station Joint Reserve Base Fort Worth near Fort Worth, Texas, on March 8, 2022. (Nicholas Kamm / AFP / Getty Images)                                                                                                                                                                                                                                                                         , Fox News White House correspondent Peter Doocy asked if Biden would consider rescinding his executive order canceling the Keystone XL Pipeline, prompting Psaki to ask if Doocy believes the pipeline would have an impact on gas prices.                                                                                                                                                                                             , "Well, do you think that that would maybe affect prices faster than getting the whole country off of fossil fuels?" Doocy asked.                                                                                                                                                                                                                                                                                                      , White House press secretary Jen Psaki speaks during the daily press briefing at the White House Feb. 22, 2022 in Washington, D.C. (Drew Angerer/Getty Images)                                                                                                                                                                                                                                                                         , PSAKI CLAIMS KEYSTONE XL PIPELINE WOULD MAKE NO DIFFERENCE FOR RISING GAS PRICES                                                                                                                                                                                                                                                                                                                                                      , "I actually don't think it would," Psaki replied. "The Keystone was not an oil field. It's a pipeline. Also, the oil is continuing to flow in just through other means. So it actually would have nothing to do with the current supply imbalance."                                                                                                                                                                                   , CLICK HERE TO GET THE FOX NEWS APP                                                                                                                                                                                                                                                                                                                                                                                                    , Fox Business' Brooke Singman contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stitch-fix-stock-falls-more/story.aspx?guid={4F710025-615D-4F87-8EE6-3BB466C2829E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-09 05:24:38 </td>
   <td style="text-align:left;"> Stitch Fix stock falls more than 16% after quarterly miss, lower guidance - MarketWatch </td>
   <td style="text-align:left;"> Stitch Fix Inc. 
        SFIX,
        +4.36%
       shares fell more than 16% in the extended session Tuesday after company posted a mixed fiscal second quarter and guided for lower sales, saying it continues to face "challenges" in getting people to sign up for its online personal styling services. Stitch FIx said it lost $30.9 million, or 28 cents a share, in the quarter, compared with a loss of $21 million, or 20 cents a share, in the year-ago quarter. Revenue rose 3% to $517 million, the company said. Analysts polled by FactSet called for a loss of 31 cents on sales of $515 million. Stitch Fix continues "to experience challenges with onboarding and conversion of clients, which are not where we want them to be," Chief Executive Elizabeth Spaulding said in a statement. "We remain confident in our long-term strategy, and are resolutely focused on building and enhancing the overall client experience ... with an emphasis on growing active clients." The company guided for fiscal third-quarter revenue between $485 million and $500 million, which would represent a year-on-year decline between 10% and 7% and contrast with analyst expectations around revenue of $559 million for the quarter. The stock ended the regular trading day up 4.4%. , "There is nothing more fundamental to the NFL's success...than upholding the integrity of the game," NFL Commissioner Roger Goodell wrote in a statement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 05:06:00 </td>
   <td style="text-align:left;"> US Stocks Close Volatile Session Lower </td>
   <td style="text-align:left;"> US stocks closed a choppy session lower on Tuesday, extending yesterday’s sharp decline, as the Russian invasion of Ukraine and consequent rise in commodity prices fuelled concerns of a slowdown in global economic growth. The main Wall Street indices fell after US President Biden announced a ban on imports of Russian oil, a move that threatens supply chains and strengthens further inflationary pressure on economies worldwide. After giving up a 585 point gain in the session, the Dow Jones closed 185 points lower at 32,632, while the S&amp;P 500 and the tech-heavy Nasdaq fell 0.7% and 0.3%, respectively. Soaring crude oil prices lifted energy shares, with Chevron (5.1%) booking significant gains. Higher crude prices also carried the renewable energy sector, led by Enphase Energy (10.8%) and SunPower (18.7%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stocks-lose-grip-earlier-gains/story.aspx?guid={CCFF80A7-E6C6-483F-8F94-1309D1AC1F4F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-09 05:01:44 </td>
   <td style="text-align:left;"> Stocks lose grip on earlier gains to end lower Tuesday - MarketWatch </td>
   <td style="text-align:left;"> Stocks finished lower on Tuesday after failing to hold earlier gains, as the Biden administration made good on threats to ban Russian oil imports in a bid to further pressure Moscow to end its invasion of Ukraine. As U.S. oil prices 
        CL00,
        +2.06%
       finished above $123 a barrel, the highest since 2008, the Dow Jones Industrial Average 
        DJIA,
        -0.48%
       gave up about 185 points, or 0.6%, to end deeper in correction territory around 32,631, a day after entering it for the first time in two years. The S&amp;P 500 index 
        SPX,
        -0.72%
       fell about 0.7%, while the battered Nasdaq Composite Index 
        COMP,
        -0.28%
       shed 0.3%, a day after it tumbled into bear-market territory. , All three major U.S. stock benchmarks end lower Tuesday in choppy trade,  with the S&amp;P 500 booking the session's biggest decline, as investors weigh America's ban on imports of Russian oil.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Joy Wiltermuth is a news editor and senior markets reporter based in San Francisco. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/cocacola-starbucks-pepsi-amazon-suspend-operations-sales-russia-ukraine </td>
   <td style="text-align:left;"> 2022-03-09 04:56:10 </td>
   <td style="text-align:left;"> Starbucks, Coca-Cola, PepsiCo suspend operations in Russia; Amazon suspends web services sign-ups </td>
   <td style="text-align:left;"> Former Minister of National Defense of Poland Radek Sikorski argues the ‘most urgent task’ is to prevent Putin from ‘winning’ Russia-Ukraine war.                                                                                                                                                                                                                                                                                                                                                          , Starbucks, Coca-Cola and Amazon have joined the growing list of companies imposing their own punishments on Russia over Vladimir Putin's war on Ukraine.                                                                                                                                                                                                                                                                                                                                                   , In a statement on its website on Monday, Coca-Cola announced it was suspending its business in Russia saying, "Our hearts are with the people who are enduring unconscionable effects from these tragic events in Ukraine" and the beverage giant "We will continue to monitor and assess the situation as circumstances evolve."                                                                                                                                                                          , Starbucks followed suit on Tuesday, with president and CEO Kevin Johnson writing in a public letter to employees, "Today, we have decided to suspend all business activity in Russia, including shipment of all Starbucks products."                                                                                                                                                                                                                                                                       , MCDONALD'S PAUSING RUSSIA OPERATIONS, TEMPORARILY CLOSING RESTAURANTS                                                                                                                                                                                                                                                                                                                                                                                                                                      , The company added, "Our licensed partner has agreed to immediately pause store operations and will provide support to the nearly 2,000 partners in Russia who depend on Starbucks for their livelihood."                                                                                                                                                                                                                                                                                                   , Starbucks has suspended all business in Russia (iStock) (iStock / iStock)                                                                                                                                                                                                                                                                                                                                                                                                                                  , Amazon Web Services also announced Tuesday that it has "stopped allowing new sign-ups for AWS" in either Russia or Belarus, which joined Putin's assault on Ukraine.                                                                                                                                                                                                                                                                                                                                       , ESTEE LAUDER CLOSING ALL OF ITS RUSSIA STORES                                                                                                                                                                                                                                                                                                                                                                                                                                                              , "Unlike other U.S. technology providers, AWS has no data centers, infrastructure, or offices in Russia, and we have a long-standing policy of not doing business with the Russian government," the company noted in a blog post.                                                                                                                                                                                                                                                                           , The logo for Amazon Web Services (AWS) (REUTERS/Chris Helgren/File Photo)  (Reuters / Reuters Photos)                                                                                                                                                                                                                                                                                                                                                                                                      , "Our biggest customers using AWS in Russia are companies who are headquartered outside of the country and have some development teams there," the post explained. "AWS has clear terms of service where if a customer is using AWS services to threaten, incite, promote, or actively encourage violence, terrorism, or other serious harm, they will not be permitted to use our services. Any customer we know of who is participating in this type of behavior will have their access to AWS suspended.", GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                , U.S. firms have increasingly imposed their own punishments on Russia amid worldwide outrage over Putin's invasion of Ukraine, adding to the crippling sanctions imposed on Russia by America and its allies over the attack.                                                                                                                                                                                                                                                                               , But some companies have faced pressure of their own to pull out of Russia. In recent days, the hashtag #BoycottCocaCola began trending on Twitter as users called on the company to pull its products from the country.                                                                                                                                                                                                                                                                                    , Pepsico later announced that it, too, would suspend the sale of its products in Russia, according to Reuters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/coca-cola-suspends-business-russia/story.aspx?guid={20C05575-04D4-B545-7A5C-20D860896A3C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-09 04:54:00 </td>
   <td style="text-align:left;"> Coca-Cola suspends business in Russia - MarketWatch </td>
   <td style="text-align:left;"> Coca-Cola Co. 
        KO,
        -3.96%
       said Tuesday it was suspending its business in Russia following the lead of several companies that have suspended activity because of the invasion of Ukraine. “Our hearts are with the people who are enduring unconscionable effects from these tragic events in Ukraine,” Coca-Cola said in a statement. “We will continue to monitor and assess the situation as circumstances evolve.” On Tuesday, PepsiCo Inc. 
        PEP,
        -2.82%
       said it was exploring options for its business in Russia. Coca-Cola shares were down 3.5% heading into the close, while Pepsi shares were down 2.3%., Investors have sought havens amid the turmoil in stocks. Gold prices approached $2,020 an ounce, getting near to a record closing high of $2,069.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Wallace Witkowski came to MarketWatch from the Associated Press in New York, where he was a business reporter specializing in pharmaceutical companies. He previously reported for trade publications in covering the drug and medical-device industries back to 1998. Based in San Francisco, his focus is on U.S. equities. Follow Wally on Twitter at: @wmwitkowski. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/biden-gas-prices-american-jobs-cassidy </td>
   <td style="text-align:left;"> 2022-03-09 04:39:59 </td>
   <td style="text-align:left;"> Biden should ‘focus’ on lowering gas prices, helping create more American jobs: Sen. Cassidy </td>
   <td style="text-align:left;"> Sen. Bill Cassidy, R-La., argues that Biden should be ‘focused’ on lowering prices at the pump and it will help create more jobs for Americans.                                                                                                                                                                                                                                                                                                            , Sen. Bill Cassidy, R-La., joined "Cavuto: Coast to Coast," Tuesday, arguing that Biden should be "focused" on lowering prices at the pump to help create more jobs for Americans.                                                                                                                                                                                                                                                                          , BIDEN ANNOUNCES BAN ON US IMPORTS OF RUSSIAN OIL, WARNS GAS PRICES WILL 'GO UP FURTHER'                                                                                                                                                                                                                                                                                                                                                                    , SEN. BILL CASSIDY: We need to develop North American energy resources. You've got to look at this as national security, energy, the economy of a country, the economy of a family and the climate. If you ignore one of those four, everything falls apart. The president should be focused upon lowering the price at the pump, which we can do in a healthier, safer way than if we import from Russia…he can do that while creating jobs for Americans. , WATCH THE FULL INTERVIEW BELOW:                                                                                                                                                                                                                                                                                                                                                                                                                            , Sen. Bill Cassidy, R-La., discusses Biden announcing a ban on Russian oil amid the Ukraine invasion.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-03-09 04:39:00 </td>
   <td style="text-align:left;"> Brazilian Real Firms </td>
   <td style="text-align:left;"> The Brazilian real firmed to $5.05 on the second week of March, as rising sugar, corn, and wheat prices encouraged the Brazilian economy to trade agricultural commodities at higher than expected volumes, while investors monitored possible government interventions in Brazilian fuel prices against the backdrop of more expensive petroleum. Crude oil prices increased further in the second week of March after Washington announced a ban on Russian oil, gas, and energy, while the UK is set to phase out Russian energy imports by the end of the year in retaliation to Russia’s invasion of Ukraine. Hawkish stances by Brazil’s central bank previously uplifted the real to 8-month highs in the end of February, as mid-month consumer price data showed that the annual inflation rate accelerated to 10.76%, higher than market expectations and the central bank’s target of 3.5%. Since April last year, COPOM has raised the main Selic rate by 875 bps to 10.75%, the highest since April 2017. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/08/europe/russia-invasion-ukraine-03-08-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-09 04:34:42 </td>
   <td style="text-align:left;"> Civilians flee Sumy after evacuation corridor opens, as 2 million refugees leave Ukraine - CNN </td>
   <td style="text-align:left;"> (CNN)A tense and fleeting evacuation from Ukraine's northeastern city of Sumy took place on Tuesday after Russian airstrikes killed 21 people, including two children, the night before, Ukrainian authorities said.                                                                                                                                       , Ukrainian officials confirmed that an evacuation corridor allowing residents out of the city opened on Tuesday morning, following days of sustained Russian attacks. It came as the United Nations estimated that more than 2 million refugees have fled Ukraine since Moscow's invasion on February 24.                                                    , The agreed ceasefire was set to last until 9 p.m. local time (2 p.m. ET), with final evacuations taking place 90 minutes before that time. Buses have been used to take people to Poltava, around 100 miles away in central Ukraine, said Dmytro Lunin, head of the Poltava regional administration, on his Telegram channel on Tuesday.                    , One convoy was delayed by an outbreak of firing at the outskirts of Sumy, according to the city's regional head, Dmitry Zhyvitsky. But Zhyvitsky was quoted in local media as saying the Russian forces did not shoot on the convoy.                                                                                                                        , "At the moment, citizens are being evacuated by their own vehicles," Zhyvytsky said on Telegram. "After 19:30 the checkpoint closes and it will be impossible to leave Sumy."                                                                                                                                                                               , The frantic rush to escape the city, during a break in its assault by Russian forces, was not replicated in other cities. Officials across the country have condemned Russia in recent days for offering unfeasible routes of escape that lead to Russia or its ally Belarus, and for reneging on ceasefire agreements by opening fire on fleeing civilians., Ukrainian Foreign Minister Dmytro Kuleba said on Tuesday that Russian troops are holding 300,000 civilians "hostage" in the besieged southern city of Mariupol, where he said a child died of dehydration.                                                                                                                                                  , Ukrainian authorities said that a long-awaited convoy of humanitarian aid to the city appeared to have come under fire on Tuesday. Russian troops are not allowing "children, women and the elderly" out of the city, and have launched an attack "precisely in the direction of the humanitarian corridor," Ukraine's Joint Forces Operation said.         , CNN has been unable to verify the status of the convoy and has reached out to the Russian side for a response.                                                                                                                                                                                                                                              , A senior US defense official said Tuesday that Mariupol as of now been "isolated" by Russian forces, though Russian forces are only still bombarding the city and are not inside it "in any significant way."                                                                                                                                               , CNN has previously reported that Mariupol residents have been cut off from water and electricity for days.                                                                                                                                                                                                                                                  , Meanwhile in regions around the capital Kyiv, the humanitarian situation remains fraught.                                                                                                                                                                                                                                                                   , "The main issue today remains humanitarian aid," Oleksiy Kuleba, the head of the Kyiv Regional Military Administration, said in a YouTube video.                                                                                                                                                                                                            , Residents of Bucha, Irpin, Gostomel, Makariv, Borodyanka and Vorzel are "forced to stay in bomb shelters for days without water and food," he said, adding that Moscow is preventing "humanitarian evacuation despite agreements with ICRC (International Committee of the Red Cross) mediation."                                                           , On Tuesday, Human Rights Watch (HRW) said Russian forces "violated their obligations under international humanitarian law not to conduct indiscriminate or disproportionate attacks that harm civilians," following a report that eight civilians were killed over the weekend as they were trying to flee the Russian army's advance in northern Ukraine.  , That warning came after the UK Ministry of Defence, in its latest intelligence assessment. accused Russian forces of targeting evacuation corridors and killing "several civilians" trying to evacuate the town of Irpin.                                                                                                                                   , Zelensky calls for help as Ukrainians flee west                                                                                                                                                                                                                                                                                                             , Ukrainian President Volodymyr Zelensky criticized the international community for remaining on the "sidelines" of the Russian invasion.                                                                                                                                                                                                                     , Addressing the UK's House of Commons on Tuesday via video, Zelensky said that "we will fight to the end," echoing former British Prime Minister Winston Churchill's famous wartime speech.                                                                                                                                                                  , "We will fight in the forests, in the fields, on the shores, in the streets," he said. Zelensky pleaded with British lawmakers to "strengthen the sanctions" against Moscow, requested that the UK recognize Russia "as a terrorist state" and reiterated his request with NATO to establish a no-fly zone over Ukraine.                                    , NATO has assisted Ukraine with equipment and intelligence, but has resisted implementing a no-fly zone over its airspace.                                                                                                                                                                                                                                   , NATO Secretary General Jens Stoltenberg said the military alliance has a "responsibility to ensure that the conflict does not spread beyond Ukraine" during a joint press conference in Riga with the Latvian President Egils Levits.                                                                                                                       , "That would be even more dangerous, destructive, and even more deadly," said Stoltenberg. "The situation could spiral out of control," he said.                                                                                                                                                                                                             , On the ground, fighting continued in multiple locations as the Russian invasion neared the end of its second week.                                                                                                                                                                                                                                          , In the southern city of Mykolaiv, regional administrator Vitali Kim asked residents to gather tires, which will be set on fire to impede Russian troop movement in the city.                                                                                                                                                                                , "In order to limit visibility for the enemy vehicles in the city, I need tires at every intersection in the city," Kim said in a message posted to Telegram. "If the vehicles break through in some direction, the task will be to go out and set fire to the tire so that there is smoke in order to limit visibility."                                    , The senior US defense official said Tuesday that Russian forces have not yet entered Mykolaiv, a key city that could be used as part of a coordinated assault against the city of Odessa, though there has been an increase in bombardment and shelling.                                                                                                    , The official said that Russian forces are still trying to advance on the cities of Kharkiv and Chernihiv, but are still facing resistance and are making more progress in the south of Ukraine than elsewhere in the country.                                                                                                                               , In total Russia has launched "nearly 670" missiles since the beginning of their invasion, a separate senior US defense official told reporters on Tuesday.                                                                                                                                                                                                  , Almost half of the missiles launched have been fired from Russia, "the other half largely from inside Ukraine," the official said. "A little bit more than 70" missiles have been fired from Belarus, and "only a half dozen or so" are coming from the Black Sea, the official added.                                                                      , A humanitarian crisis keeps growing                                                                                                                                                                                                                                                                                                                         , Meanwhile, the humanitarian effect of Russia's invasion were also laid bare on Tuesday, when UN High Commissioner for Refugees Filippo Grandi told French radio station France Inter that more than 2 million people have fled Ukraine since the conflict began.                                                                                            , The milestone is a "terrifying" number, said Grandi. Most of the refugees have traveled to Poland, Moldova and other neighboring countries "where they have connections, family," he added.                                                                                                                                                                 , "What worries me, what we fear is a second wave of persons who have a good deal less resources and connections and who will be much more vulnerable," said Grandi.                                                                                                                                                                                          , At least 1.2 million refugees have crossed the border from Ukraine into Poland since the invasion began, the Polish Border Guard tweeted Tuesday, with 141,500 entering on Monday alone.                                                                                                                                                                    , CNN's Tim Lister, Olga Voitovych, Esha Mitra, Swati Gupta, Anastasia Graham-Yooll, Michael Conte, Ellie Kaufman, Niamh Kennedy and Antonia Mortensen contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/08/politics/russia-ukraine-us-intelligence/index.html </td>
   <td style="text-align:left;"> 2022-03-09 04:03:53 </td>
   <td style="text-align:left;"> US spy chiefs say Putin likely to escalate in Ukraine - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)The US intelligence community believes that Russian President Vladimir Putin views the conflict in Ukraine as a "war he cannot afford to lose," suggesting he is likely to escalate the conflict without any concern for the number of civilians killed, the US's top intelligence chiefs told Congress.                                                                                                                                                          , Director of National Intelligence Avril Haines said at a congressional hearing Tuesday that US intelligence assesses Putin is unlikely to be deterred by the setbacks the Russian military has faced in Ukraine, suggesting he is doubling down on his campaign to keep Ukraine from joining NATO.                                                                                                                                                                      , CIA Director William Burns said Putin had launched the invasion "determined to dominate and control Ukraine" based on a set of assumptions that the conflict would be successful, including that Ukraine was weak, that European allies like France and Germany were risk-averse, that he had "sanctions-proofed" his economy and that his military was capable of a quick and decisive victory at minimal cost.                                                        , "He's been proven wrong on every count," Burns said.                                                                                                                                                                                                                                                                                                                                                                                                                    , The discussion of Putin's motivations that led to Russia's bloody invasion of Ukraine last month -- and the sweeping, crippling sanctions from the West in response -- offered the most public assessment to date of the US view of Putin's ill-fated war in Ukraine. The intelligence community -- which forecast Putin's moves in the lead-up to the invasion -- testified before the House Intelligence Committee on Tuesday at an annual worldwide threats hearing. , "This is a matter of deep personal conviction for him," Burns told the committee. "He's been stewing in a combustible combination of grievance and ambition for many years."                                                                                                                                                                                                                                                                                            , Lt. Gen. Scott Berrier, director of the Defense Intelligence Agency, said the intelligence community estimates with "low confidence" that between 2,000 and 4,000 Russian troops have been killed in Ukraine since Moscow launched its invasion last month.                                                                                                                                                                                                             , Putin's nuclear announcement was 'signaling'                                                                                                                                                                                                                                                                                                                                                                                                                            , Putin's announcement last week that he was elevating the readiness status of his nuclear forces was "very unusual," Haines told lawmakers on Tuesday. But she said that it was better understood as messaging rather than an immediate threat to the United States.                                                                                                                                                                                                     , "We obviously take it very seriously when he's signaling in this way," Haines said. "But we do think [that] he is effectively signaling, that he's attempting to deter" NATO from getting involved in the conflict in Ukraine, she said.                                                                                                                                                                                                                                , "That's been his main purpose in doing so," Haines added.                                                                                                                                                                                                                                                                                                                                                                                                               , Haines also said that the Russian announcement that the country's strategic forces would be placed on "special alert status" did not refer to a "technical term as we understand it within their system"                                                                                                                                                                                                                                                                , The US intelligence community assesses that Russia "does not want a direct conflict with US forces," according to an annual unclassified threat assessment published by the Office of the Director of National Intelligence on Tuesday.                                                                                                                                                                                                                                 , The assessment, which was prepared in January before Russia's invasion of Ukraine, said that Moscow "seeks an accommodation with the United States on mutual noninterference in both countries' domestic affairs and US recognition of Russia's claimed sphere of influence over much of the former Soviet Union."                                                                                                                                                      , Moscow "views its nuclear capabilities as necessary for maintaining deterrence and achieving its goals in a potential conflict against the United States and NATO, and it sees a credible nuclear weapons deterrent as the ultimate guarantor of the Russian Federation," according to the report.                                                                                                                                                                      , Haines said the Russia initially underestimated the strength of Ukraine's resistance                                                                                                                                                                                                                                                                                                                                                                                    , Haines said that US intelligence believes Putin's "nuclear saber-rattling" and public posturing are part of an effort to deter the US and NATO from engaging in the war and from providing additional support to Ukraine.                                                                                                                                                                                                                                               ,  "Putin probably still remains confident that Russia can militarily defeat Ukraine and wants to prevent Western support from tipping the balance and forcing a conflict with NATO," Haines said.                                                                                                                                                                                                                                                                        , She said Russia had initially underestimated the strength of Ukraine's resistance, adding that Moscow's ultimate military objectives remain unclear.                                                                                                                                                                                                                                                                                                                    , "What is unclear at this stage is whether Russia will continue to pursue a maximalist plan to capture all or most of Ukraine, which we assess would require more resources even as the Russian military has begun to loosen its rules of engagements to achieve their military objectives," Haines said.                                                                                                                                                                , The Russian military, she said, is operating "with reckless disregard for the safety of noncombatants as Russian units launch artillery and airstrikes into urban areas."                                                                                                                                                                                                                                                                                               , Burns predicted an "ugly next few weeks" with "scant regard for civilian casualties," given Moscow is unlikely to be able to install a puppet regime or pro-Russian leadership in the face of opposition from the Ukrainian people.                                                                                                                                                                                                                                     , "The Ukrainians are going to continue to resist fiercely and effectively," he added.                                                                                                                                                                                                                                                                                                                                                                                    , Democratic Rep. Adam Schiff of California, the chairman of the committee, told reporters after the hearing that Putin "seriously miscalculated."                                                                                                                                                                                                                                                                                                                        , "I think it's surely the case that Putin understands how much he has taken on with Ukraine," Schiff said. "I think it has been a brutal realization."                                                                                                                                                                                                                                                                                                                   , Haines said an expansive and prolonged military campaign could force Putin to reassess his goals, as opposition to the invasion among Russians continues to increase and sanctions enacted by the US and NATO begin to take effect.                                                                                                                                                                                                                                     ,  "The economic crisis that Russia is experiencing is also exacerbated by the domestic political opposition to Putin's decision to invade," Haines said. "But what he might be willing to accept as a victory may change over time given the significant costs he is incurring."                                                                                                                                                                                         , CNN's Geneva Sands, Aaron Pellish, Jennifer Hansler and Sean Lyngaas contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-03-09 03:43:00 </td>
   <td style="text-align:left;"> Canadian Dollar Weakens to 11-Week Low </td>
   <td style="text-align:left;"> The Canadian dollar weakened to 1.29 per USD in the second week of March, the lowest in 11 weeks, as concerns of lower growth and higher prices continued to pressure risk sensitive currencies, despite higher oil prices, Canada's main export. Crude oil prices continued to rise after Washington announced a ban on Russian oil, gas, and energy, while the UK is set to phase out Russian energy imports by the end of the year in retaliation to Russia’s invasion of Ukraine. The supply shock of fossil fuels and commodities due to Russia’s assault heightened inflation fears in Canada, despite recent rate hikes by the Bank of Canada. The central bank increased its target for the overnight rate by 25bps to 0.5% in its March meeting, the first hike since October 2018, retreating it will use its monetary policy tools to return inflation to the 2% target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-end-nearly/story.aspx?guid={0403EF27-87D1-4665-8240-69FE471FD968}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-09 03:40:44 </td>
   <td style="text-align:left;"> U.S. oil futures end nearly 4% higher as U.S. bans imports of Russian oil - MarketWatch </td>
   <td style="text-align:left;"> Oil futures climbed Tuesday, with U.S. prices up by nearly 4%, after President Joe Biden announced a ban on imports of Russian oil. "How high oil prices will need to go depends primarily on how much and for how long the market will need to shun export barrels from Russia and whether other buyers, such as China, will step in to increase its purchases of oil from Russia," said Bjørnar Tonhaugen, head of oil markets at Rystad Energy. West Texas Intermediate crude for April delivery 
        CLJ22,
        +2.10%
       rose $4.30, or 3.6%, to settle at $123.70 a barrel on the New York Mercantile Exchange. That was the highest front-month finish since August 2008, FactSet data show., Here's what job-seekers need to know.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-09 03:31:05 </td>
   <td style="text-align:left;"> New Zealand 10Y Bond Yield Hits 3-1/2-year High </td>
   <td style="text-align:left;"> New Zealand 10 Year Government Bond Yeld increased to a 3-1/2-year high of 2.888% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 03:23:00 </td>
   <td style="text-align:left;"> US Stocks Continue to Swing </td>
   <td style="text-align:left;"> Volatility continued to grip US equities on Tuesday as investors continued to monitor developments surrounding the war in Ukraine and rising commodity prices. After opening nearly flat, the main indexes fell sharply following the White House announcement of a ban on imports of Russian oil, gas, and energy. In the afternoon trade, the stocks rebounded sharply with the Dow surging as much as 500 points to lose ground again 1 hour before the closing bell. Soaring crude oil prices lifted energy shares with Chevron and Exxon up 5% and 2.5%, respectively while Enphase Energy surged 14% and SunPower 21%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/08/economy/oil-gas-sanctions-russia-ukraine/index.html </td>
   <td style="text-align:left;"> 2022-03-09 03:20:42 </td>
   <td style="text-align:left;"> The West closes in on Russia's last lifeline - CNN </td>
   <td style="text-align:left;"> New York (CNN Business)The United States and Europe have pummeled Russia with unprecedented sanctions over the past several weeks as Vladimir Putin's army bears down on Ukraine. But the West has largely left Russia's largest export untouched: energy.                                                                                                                                                                                                  , Until now.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , European Union officials on Tuesday said the bloc would slash imports of Russian natural gas by two thirds this year, and the EU announced a plan to achieve energy independence from Moscow "well before 2030." That would separate Europe from its single biggest energy supplier.                                                                                                                                                                        , Separately, President Joe Biden announced Tuesday a ban on Russian oil, natural gas and coal imports to the United States. And the UK government said Tuesday it would phase out Russian oil imports by the end of 2022 and explore ways of ending natural gas imports as well.                                                                                                                                                                             , America's ban is largely symbolic. The United States relies very little on Russian energy: The country's crude represented less than 2% of all US oil imports in December, according to the US Energy Information Administration. Overall, Russian crude and petroleum products made up about 5% of US imports at the end of 2021. Similarly, just 8% of UK demand is supplied by Russian oil, according to UK Business and Energy Secretary Kwasi Kwarteng., By contrast, the European Union depends foundationally on Russia for its energy. About 40% of Europe's natural gas and 27% of its oil imports come from Russia. And Russia supplies Europe with 46% of its coal.                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                             , That's why Europe has been so hesitant to take action against Russia's energy sector. Yet as its war on Ukraine continues to shock the world, western countries are running out of other options to add pressure on Russia for the assault.                                                                                                                                                                                                                 , Russia's final lifeline                                                                                                                                                                                                                                                                                                                                                                                                                                     , Existing sanctions have already created a kind of shadow-ban on Russian oil. Traders have grown concerned about access to financing for Russian oil purchases as well as the availability of ports willing to ship it. Urals oil has lately traded at about a $25 discount to Brent crude, the global benchmark. About 70% of Russian seaborne oil was struggling to find buyers, according to JPMorgan.                                                    , But gas continues to flow to Europe, and enough Russian crude and gas is finding buyers to make a difference to the Russian economy. Russia has been bringing in between $500 million and $1 billion a day in crude and gas exports during the war, according to Charles Lichfield, deputy director of the GeoEconomics Center for the Atlantic Council, an international think tank.                                                                       , Restricting energy exports would severely limit Russia's options to keep its economy afloat. Its central bank has been sanctioned, limiting the government's access to cash reserves designed to insulate the country from reliance on the West. Businesses are pulling out or suspending operations in the country and shunning Russian exports.                                                                                                           , "Energy has been Russia's final lifeline," said Lichfield. "Sanctions on oil and gas would put Russia in a much more vulnerable situation."                                                                                                                                                                                                                                                                                                                 , The Russian economy isn't very diverse. It relies heavily on energy exports, and many of its other key industries, including metals and other raw materials, have been sanctioned or shunned.                                                                                                                                                                                                                                                               , Despite the sanctions, the Russian central bank has so far been able to meet many of its debt obligations. Reducing the market for oil and gas could force Russia to rein in spending. For example, government wages and pensions may not be paid on time.                                                                                                                                                                                                  , "Russia has managed to find quick fixes," said Lichfield. "Those won't be available to Russia anymore if its energy is restricted."                                                                                                                                                                                                                                                                                                                         , What Russia does next                                                                                                                                                                                                                                                                                                                                                                                                                                       , One reason Europe is working to act quickly on energy independence: It fears Vladimir Putin could turn it into a weapon, cutting off its gas supply before Europe is ready to act.                                                                                                                                                                                                                                                                          , Russia has already threatened to beat Europe to the punch: Russian Deputy Prime Minister Alexander Novak said in a statement on state television Tuesday that Russia could retaliate against Europe's sanctions by turning off Germany's access to Nord Stream 1, the gas pipeline that supplies the country with Russian natural gas.                                                                                                                      , Novak said Russia would be entirely within its rights to retaliate against the European Union after Germany last month froze the certification of the Nord Stream 2 gas pipeline.                                                                                                                                                                                                                                                                           , "If you want to reject energy supplies from Russia, go ahead. We are ready for it," Novak said. "We know where we could redirect the volumes to."                                                                                                                                                                                                                                                                                                           , -- CNN's Chris Liakos and Reuters contributed to this report                                                                                                                                                                                                                                                                                                                                                                                                , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/08/health/vaping-fda-nicotine.html </td>
   <td style="text-align:left;"> 2022-03-09 03:17:11 </td>
   <td style="text-align:left;"> The Synthetic Nicotine Loophole Fueling a Return to Teenage Vaping - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Sales are rising of flavored e-cigarettes using synthetic nicotine that evades regulatory oversight, a gap that lawmakers are now trying to close.                                                                                                                                                                                                                                                                                                                                                                                                                          , By Christina Jewett                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The Food and Drug Administration’s crackdown on flavored e-cigarettes in 2020 was meant to be a comprehensive, aggressive strategy to curtail the epidemic of teenage vaping.                                                                                                                                                                                                                                                                                                                                                                                               , But two years later, sales of disposable, flavored e-cigarettes have soared. Some companies have moved just beyond the reach of the F.D.A. by swapping out one key ingredient. They have circumvented federal oversight of tobacco plant-derived nicotine by using an unregulated synthetic version.                                                                                                                                                                                                                                                                        , The agency had nearly wiped out the use of flavors in devices like Juul, once the teenage favorite, that could be refilled with pods in flavors like crème brûlée and mango. Jumping into the breach, though, companies like the teen favorite Puff Bar are selling disposable devices filled with candy flavors and tobacco-free or synthetic nicotine.                                                                                                                                                                                                                    , Scientists are just beginning to study the unknown health effects of synthetic nicotine, even as research is expanding into the harm caused by vaping and flavor ingredients alongside continuing cases of devastating vaping-related lung injury. To many public health advocates, new trends in the vaping industry are thwarting the F.D.A.’s efforts to protect a new generation from nicotine addiction.                                                                                                                                                               , “These companies like Puff Bar and others are deliberately driving their trucks of poison through this huge loophole,” said Meredith Berkman, a founder of Parents Against Vaping E-Cigs. She recently hosted a webinar about synthetic nicotine attended by 700 people. “We think we need to regulate these products.”                                                                                                                                                                                                                                                     , Lawmakers on Tuesday proposed language that they want inserted in the Congressional omnibus budget bill that would give the F.D.A. authority to regulate synthetic nicotine, although it is unclear if the issue will be included in the final bill.                                                                                                                                                                                                                                                                                                                        , Representative Frank Pallone Jr., Democrat of New Jersey and chairman of the House Energy and Commerce Committee, said the provision would be a public health victory over “bad actors” who circumvented the F.D.A.’s authority.                                                                                                                                                                                                                                                                                                                                            , “That ends with passage of this bill, which will close this loophole and clarify F.D.A.’s authority to regulate all tobacco products, including those containing synthetic nicotine,” Mr. Pallone said in a statement on Tuesday.                                                                                                                                                                                                                                                                                                                                           , Sales of synthetic or tobacco-free nicotine went from virtually nonexistent in 2020 to taking up shelf space in two-thirds of U.S. vape shops in 2021, according to market research. Those stores said such products accounted for nearly 20 percent of sales, according to ECigIntelligence, which surveys hundreds of the shops each year. The company projected that the U.S. vape market, web sales included, would be nearly $6 billion this year.                                                                                                                     , Federal officials have been in a cat-and-mouse game with some e-cigarette makers. Spurred by a court order, the F.D.A. forced thousands of e-cigarette companies, including Juul, to apply in 2020 for authorization to remain on the market. With the agency focused on the most popular devices, like Juul’s, that used insertable cartridges, makers of disposable vape pens in flavors like gummy bear and candy cane flooded the market. The agency then responded with a stern warning and even product seizures aimed at some of those companies, including Puff Bar., By late last year, more than a million tobacco-sales applications had been denied. Applications to remain on the market by Juul and myriad other companies are pending.                                                                                                                                                                                                                                                                                                                                                                                                     , By early 2021, Puff Bar returned to the market with “tobacco-free” or synthetic nicotine that didn’t fall under F.D.A. oversight, loaded with the fruity flavors prohibited in vapes with tobacco-based nicotine. Other companies imported similar devices containing synthetic or tobacco-free nicotine from factories in Shenzhen, China, according to industry experts.                                                                                                                                                                                                  , Patrick Beltran, who has identified himself in news reports as one of two executives of Puff Bar, did not respond to requests for comment.                                                                                                                                                                                                                                                                                                                                                                                                                                  , Sales data released by the C.D.C. Foundation shows that since the F.D.A. stepped up e-cigarette enforcement in February 2020, sales of disposable fruit- and candy-flavored devices have grown by 290 percent, to 6.46 million devices a month by November 2021. Sales of the F.D.A.-targeted flavored pod and cartridge devices have nearly vanished.                                                                                                                                                                                                                      , Since early 2020, overall e-cigarette sales are up nearly 50 percent to about 22 million units per month, according to Information Resources, a data tracking consultant. The National Youth Tobacco Survey conducted in early 2021, when many students were learning via Zoom, reported that, overall, about 11 percent of high school students used e-cigarettes.                                                                                                                                                                                                         , New e-cigarette suppliers can go into business easily: They contract with a manufacturer in China, set up a website and get space in a warehouse to store and ship devices, said Samantha Shusterman, a senior counsel supervising e-cigarette enforcement for the Massachusetts attorney general’s office. They use shell companies and can quickly withdraw the profits if they face scrutiny.                                                                                                                                                                            , “It’s a whack-a-mole situation,” said Ms. Shusterman, whose state banned all flavored e-cigarettes, except in licensed smoking bars. “They’re not following any of the laws.”                                                                                                                                                                                                                                                                                                                                                                                               , Mitch Zeller, director of the F.D.A.’s Center for Tobacco Products, said the agency recognized the problem.                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , “Disposable e-cigarettes made only with synthetic nicotine pose a particular challenge for the F.D.A. when it comes to our tobacco authorities,” Mr. Zeller said in an email. “The F.D.A. is actively investigating this issue and considering how to best address such products.”                                                                                                                                                                                                                                                                                          , Vaping is still popular among teenagers. Rani Dhiman, 16, said it is highly visible in the bathrooms and stairwells of her high school in the Detroit suburbs.                                                                                                                                                                                                                                                                                                                                                                                                              , She said the stress and loneliness of the pandemic might have been a trigger for some teenagers to start. It’s also portrayed glamorously, she pointed out, in “Euphoria,” a popular HBO series about a teenager kicking drug addiction.                                                                                                                                                                                                                                                                                                                                    , “Sometimes so many people are vaping in the bathrooms, it’s hard to do anything about it,” Ms. Dhiman said, adding that she doesn’t vape.                                                                                                                                                                                                                                                                                                                                                                                                                                   , The F.D.A.’s efforts to limit teenagers’ access to flavored vapes had little effect on Lizzie Burgess’s ability to get them over the last four years in the Indianapolis suburbs. Within weeks of starting to vape at 16, she said, she was addicted. There was always a gas station, older friend or website selling e-cigarettes in flavors like banana ice cream or sour apple, she said.                                                                                                                                                                                , At 19, she said, she was vaping THC and using a device — now advertising tobacco-free nicotine — that has as much nicotine as two packs of cigarettes, every two to three days. She said she fell ill with what started like a cold, which progressed to rapid breathing, almost-gray lips and feeling depleted. By the time she went to the emergency room, her oxygen saturation was 67, far below the normal range of 95 or higher. Ms. Burgess said she was soon in the I.C.U. with vaping-related lung injury.                                                         , She’s struggled to end her nicotine addiction and is down to two cigarettes a day.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , “I think the F.D.A. should take it all off the market now,” Ms. Burgess said of the flavored vapes. “I think it will be very very hard for them to reel it all in. It’s so big and there are so many companies now.”                                                                                                                                                                                                                                                                                                                                                        , Synthetic nicotine remains far more expensive than the tobacco-derived product, leading some industry experts to question whether a device label of “synthetic” is accurate.                                                                                                                                                                                                                                                                                                                                                                                                , The unregulated vaping market at this point is a problem of the F.D.A.’s making, said Gregory Conley, president of the American Vaping Association, an industry trade group. He said the agency fueled the problem by overregulating a product used by millions of adults who find vaping a safer alternative to smoking.                                                                                                                                                                                                                                                   , “This country should learn some lessons from past prohibitions that failed miserably,” Mr. Conley said. “If you don’t fairly regulate a market where there is a great deal of demand from legal adults, you will fuel gray and black markets where the operators are not concerned with checking IDs before selling.”                                                                                                                                                                                                                                                       , Dr. Robert Jackler, who studies tobacco company advertising at Stanford University, has also noted major tobacco retailers entering the synthetic nicotine market with flavored gums called “pouches.” He said his tobacco research group could pose as a teenager and use gift cards to easily buy the flavored synthetic nicotine gums from major retailers and have them shipped to a home in California.                                                                                                                                                                , “When we buy them, there’s no age gating,” Dr. Jackler said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The loopholes are many with synthetic nicotine, he said, allowing the products to avoid hefty tobacco taxes and remain affordable and to evade the algorithms that online retailers use to weed out underage sales of tobacco products. The ease of purchasing was also concerning, Dr. Jackler said, given how little is known about the health effects of flavored, synthetic nicotine.                                                                                                                                                                                   , Recent research has focused in on the chemicals used to simulate butter, which is linked to lung damage, and vanilla, which is associated with birth defects in zebrafish.                                                                                                                                                                                                                                                                                                                                                                                                  , Dr. Sven-Eric Jordt, an associate professor at Duke University who has studied synthetic nicotine, said it posed many unknowns.                                                                                                                                                                                                                                                                                                                                                                                                                                             , About 99 percent of tobacco-derived nicotine is a psychoactive molecule called S-nicotine, he said. But a mirror-image molecule, known as R-nicotine, makes up 50 percent of most types of synthetic nicotine. He said the R-nicotine molecule appears to be less addictive, but very little research has been done on it in animals or humans.                                                                                                                                                                                                                             , “It could alter nerve transmission in the brain in different ways from classic nicotine,” Dr. Jordt said, “but we don’t understand that at this time.”                                                                                                                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ncr-suspends-all-product-sales/story.aspx?guid={CA410767-1C0D-493D-934D-7EE04BAF7A96}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-09 03:06:02 </td>
   <td style="text-align:left;"> NCR suspends all product sales in Russia, stock bounces off 1-year low - MarketWatch </td>
   <td style="text-align:left;"> Shares of NCR Corp. 
        NCR,
        +4.34%
       shot up 4.6% in afternoon trading Tuesday, after the provider of technology that helps run stores, restaurants and self-directed banking said it has suspended sales of all of its products in Russia in the wake of the country's invasion of Ukraine. The stock had slumped 14.2% since the invasion started through Monday's close, which was a one-year low. NCR said revenue in Russia and Ukraine combined represent about 1% of total revenue, which was $7.16 billion in 2021. "We condemn this unjustified invasion and call for an immediate and peaceful resolution to this humanitarian crisis," NCR said in a statement. "As a company, we are committed to the safety of our employees in Ukraine and are in constant contact with our teams to offer support in many forms, including to those in Ukraine who need to evacuate or choose to stay and protect their country from this aggression." NCR shares have tumbled 18.7% over the past three months while the S&amp;P 500 
        SPX,
        -0.72%
       has shed 10.8%., "There is nothing more fundamental to the NFL's success...than upholding the integrity of the game," NFL Commissioner Roger Goodell wrote in a statement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/energy/oil-and-gas-exec-rips-biden-admins-disingenuous-support-of-industry </td>
   <td style="text-align:left;"> 2022-03-09 02:59:27 </td>
   <td style="text-align:left;"> Oil and gas exec rips Biden admin's 'disingenuous' support of industry </td>
   <td style="text-align:left;"> Mack Energy Corp. Director of Government Affairs Claire Chase argues oil prices wouldn't be skyrocketing today had President Biden allowed for  companies to 'continue to drill the way that we were under President Trump.'                                                                                                                                                                                                               , Mack Energy Corp. Director of Government Affairs Claire Chase argued on Tuesday that the United States is currently facing a "crisis of President Biden’s making" as it pertains to oil and gas.                                                                                                                                                                                                                                           , "If he [Biden] had allowed us to continue to drill the way that we were under President Trump I don’t think we would be seeing $130 oil today," she told "Cavuto: Coast to Coast" on Tuesday.                                                                                                                                                                                                                                              , Chase also slammed President Biden's "disingenuous" support for the industry, pointing to his energy policies.                                                                                                                                                                                                                                                                                                                             , In a series of orders aimed at combating climate change, President Biden temporarily suspended the issuance of oil and gas permits on federal lands and waters and canceled the Keystone XL oil pipeline project.                                                                                                                                                                                                                          , President Biden revoked the permit for the 1,700-mile pipeline on his first day in office, ending a project that was expected to employ more than 11,000 Americans last year.                                                                                                                                                                                                                                                              , Chase made the comments as the price of oil continued to soar following the president’s announcement that his administration is banning Russian oil, natural gas and coal imports to the United States in response to Russia's invasion of Ukraine.                                                                                                                                                                                        , "Today I am announcing the United States is targeting the main artery of Russia's economy. We're banning all imports of Russian oil and gas and energy," Biden said during remarks from the White House. "That means Russian oil will no longer be acceptable at US ports and the American people will deal another powerful blow to Putin's war machine."                                                                                 , The decision was made in "close consultation" with U.S. allies and partners around the world, particularly in Europe.                                                                                                                                                                                                                                                                                                                      , The surge in the price of oil past $130 per barrel on Monday was triggered by the possibility the U.S. might bar crude imports from Russia. Oil prices steadied later in the day and were moderately higher Tuesday afternoon at around the $131 level for Brent crude and $127 per barrel for the U.S. benchmark.                                                                                                                         , Chase told host Neil Cavuto on Tuesday that now that Biden has changed his tune regarding banning Russian oil imports, there is now "a hope" that the president will also make "the right move" towards domestic oil production.                                                                                                                                                                                                           , President Biden announces actions to hold Russia 'accountable' for its war on Ukraine.                                                                                                                                                                                                                                                                                                                                                     , "It’s just been really difficult to understand what President Biden has been thinking since the day that he took office," she said. "I mean as we look at his actions, he went ahead and banned the Keystone pipeline almost immediately and signaled that he was going to make it more difficult for us to drill by putting a hold on federal leases, by doing a number of things, and then going ahead and agreeing with Nord Stream 2." , GAS PRICES ABOVE $4 PER GALLON AS RUSSIA-UKRAINE WAR IMPACTS SUPPLY, DISRUPTING GLOBAL MARKET                                                                                                                                                                                                                                                                                                                                              , White House press secretary Jen Psaki Monday sought to dispute claims that Biden administration's policies are preventing domestic drilling.                                                                                                                                                                                                                                                                                               , Referring to a comment she had made earlier during the White House press briefing that the Biden administration was "going to do everything we can" to reduce the prices at the pump, Fox News' Peter Doocy pressed Psaki to clarify why the administration is asking other countries to pump more oil instead of producing more oil at home.                                                                                              , When Psaki claimed federal policies are not limiting the supplies of oil and gas domestically, Doocy pointed out that Biden issued an executive order halting new oil production at public plants.                                                                                                                                                                                                                                         , Psaki said 90% of leases are on public lands and that there are 9,000 unused drilling permits.                                                                                                                                                                                                                                                                                                                                             , Speaking with Cavuto, Chase said that "9,000 leases available is such a misleading number."                                                                                                                                                                                                                                                                                                                                                , She went on to say it is "a complicated situation," noting that "we have permits but, we are facing the same issues that other industries are facing, with the supply chain, with labor shortages. So we can all have all the permits in the world, but if we can’t get the casing to protect the groundwater, then we can’t drill."                                                                                                       , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                , She went on to point out that "we also need to get the rights-of-way for our roads to access that lease or for the lines that we need to move the products," which she said is controlled by the Department of the Interior, which she argued "has been very slow to get us answers on those rights-of-way."                                                                                                                               , Mack Energy Corp. Director of Government Affairs Claire Chase slams President Biden's 'disingenuous' support for the industry.                                                                                                                                                                                                                                                                                                             , "So I think it’s really sort of a disingenuous figure to say, ‘We’re being very supportive’ when from day one the signal to oil and gas companies has been, ‘we don’t want you drilling on federal land.’ So as a result we are making the choice to invest elsewhere and to slow down," Chase continued.                                                                                                                                  , She then went on to say that "we’re ready" and "willing" to increase production. Chase acknowledged that "it’s going to take a little bit of time to get online," but pointed out that "we can supply the world with the cleanest natural gas and fossil fuels on the planet."                                                                                                                                                             , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                    , Fox Business’ Jon Brown and Fox News' Peter Doocy contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/us-russian-oil-ban-stupidest-move-conocophillips-ceo </td>
   <td style="text-align:left;"> 2022-03-09 02:58:19 </td>
   <td style="text-align:left;"> ConocoPhillips CEO: Not much conversation between oil industry and Biden Administration </td>
   <td style="text-align:left;"> Former Venezuelan ambassador to the U.K. weighs in on President Biden's decision to ban Russian oil on 'Cavuto: Coast to Coast.'                                                                                                                                                                                                                                                                                                                                                                                  , Until Russia invaded Ukraine there wasn’t much conversation taking place between the energy industry and the Biden Administration.                                                                                                                                                                                                                                                                                                                                                                                , That’s the view of ConocoPhillips CEO Ryan Lance.                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , "I think it's starting to ramp up, unfortunately, I couldn’t have said that two or three weeks ago. I think wasn't much conversation going on with our administration and in our industry" said Lance during a Q&amp;A moderated by Daniel Yergin at the CERAWeek by S&amp;P Global" conference in Houston. "Certainly, I'll speak for myself and our company, but I think that has ramped up as sort of this whole conversation around national security and energy security is clearly moving, moving to the forefront.", Lance also cautioned the Russia-Ukraine situation may not resolve itself in the short term.                                                                                                                                                                                                                                                                                                                                                                                                                       , "We need to start planning. What does it mean around energy security and national security? You need to think about it in the context of more than just a few months, if you know, heaven forbid this last year or more" warned.                                                                                                                                                                                                                                                                                  , Lance, was not directly asked about President Biden's move to ban all Russian oil imports.                                                                                                                                                                                                                                                                                                                                                                                                                        , EXXON MOBIL CEO SAYS OIL COMPANIES WERE IN TOUGH POSITION BEFORE UKRAINE-RUSSIA WAR                                                                                                                                                                                                                                                                                                                                                                                                                               , GAS PRICES HIT FRESH RECORD                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , The energy giant has $91 billion in total assets across 14 countries and employs 9,000 workers.                                                                                                                                                                                                                                                                                                                                                                                                                   , The energy giant has $91 billion in total assets across 14 countries and employs 9,000 workers. (Reuters/Andrew Kelly/File Photo / Reuters)                                                                                                                                                                                                                                                                                                                                                                       , Oil prices hovered around $126 per barrel Tuesday, while the national average for gas prices hit a record $4.17 a gallon, per AAA.                                                                                                                                                                                                                                                                                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Shares of ConocoPhillips have gained 36% this year through Tuesday while the S&amp;P 500 has declined 12%.                                                                                                                                                                                                                                                                                                                                                                                                            , *This story has been updated to clarify Lance's comments from the moderated Q&amp;A which did not include the U.S. ban of Russian imports.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/gas-prices-california-highest-oklahoma </td>
   <td style="text-align:left;"> 2022-03-09 02:56:17 </td>
   <td style="text-align:left;"> Gas prices: California has highest prices, Oklahoma has lowest </td>
   <td style="text-align:left;"> The US can 'step up' and provide more energy to the world, CEO says                                                                                                                                                                                                                                                                                                                                                                                                    , Unprecedented gas prices are hurting families across the country, but drivers in blue states like California and New York are feeling an even bigger pinch at the pump.                                                                                                                                                                                                                                                                                                , As of Tuesday, the Democratic-led states of Washington, Nevada, Oregon, Illinois, Pennsylvania and New York have the highest gas prices in the country, led by California with an average of $5.44 for a gallon of regular unleaded gas, according to GasBuddy.                                                                                                                                                                                                        , BIDEN ANNOUNCES BAN ON US IMPORTS OF RUSSIAN OIL, WARNS GAS PRICES WILL’GO UP FURTHER’                                                                                                                                                                                                                                                                                                                                                                                 , Gas prices that were already skyrocketing due to inflation and supply chain issues have accelerated after Russia’s invasion of Ukraine two weeks ago. President Biden announced during his State of the Union address that he was releasing 30 million barrels from its Strategic Petroleum Reserve, but it has done little to assuage the rising prices – the U.S. national average hit $4.213 on Tuesday, smashing records previously hit during the 2008 recession. , Gas prices grow along with inflation as this sign at a gas station shows in San Diego, California, U.S. November, 9, 2021.  (REUTERS/Mike Blake/File Photo / Reuters Photos)                                                                                                                                                                                                                                                                                           , Biden announced Tuesday a ban on Russian oil, gas and energy imports to the U.S. in an effort to weaken Russian President Vladimir Putin, but the move is expected to push gas prices even higher.                                                                                                                                                                                                                                                                     , While Republicans have called for expanded domestic oil production as a solution, Democrats have openly opposed the idea. Instead, politically vulnerable Democrats in multiple states are calling for a pause on the federal gas tax of 18.4 cents per gallon through the midterm elections in November. President Biden has said he’s considering all options for lowering gas prices.                                                                               , Republicans have also called for a gas tax holiday, but at the state level. In California, Republicans have proposed a six-month gas tax holiday that would bring the tax to zero during that time period.                                                                                                                                                                                                                                                             , U.S. President Joe Biden speaks in the Roosevelt Room of the White House in Washington, D.C., on Tuesday, March 8, 2022.  (Oliver Contreras/Sipa/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                            , Democrats have opposed the idea. Gov. Gavin Newsom has instead proposed to forgo the annual increase to the existing gas tax that would take effect in July, but state Democrats have voiced opposition to that as well.                                                                                                                                                                                                                                               , "That's something that could potentially jeopardize a tremendous amount of jobs in this state, it could inhibit some economic growth," Assembly Speaker Anthony Rendon told the Associated Press.                                                                                                                                                                                                                                                                      , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                , In Florida, which ranks 11th in the country for high gas taxes, according to the Tax Foundation, Republican Gov. Ron DeSantis has called on state lawmakers to pass legislation that would enact a gas tax holiday for five months.                                                                                                                                                                                                                                    , Florida Gov. Ron DeSantis speaks at a press conference at the Eau Gallie High School aviation hangar in Melbourne, Florida, on March 22, 2021. (Paul Hennessy/SOPA Images/LightRocket via Getty Images / Getty Images)                                                                                                                                                                                                                                                 , "Gas prices have been rising due to inflationary pressures from bad federal policies, so we here in Florida need to step up and provide relief to our citizens," DeSantis said when he announced the proposal in November.                                                                                                                                                                                                                                             , Despite Florida’s high gas tax rate, a gallon of unleaded in the Sunshine State currently costs $4.18, which is similar to states like Idaho and Virginia, according to GasBuddy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-prices-settle-above-2000/story.aspx?guid={20CC46FF-F396-4DCA-A398-4C271162F486}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-09 02:46:54 </td>
   <td style="text-align:left;"> Gold prices settle above $2,000 for the first time in about 19 months - MarketWatch </td>
   <td style="text-align:left;"> Gold futures rose on Tuesday for a fourth straight session, settling above the $2,000-an-ounce mark for the first time since August 2020. Gold's surge today and in recent sessions is "not only a reaction to the Ukraine situation, but also a sign that shorts in the futures markets are abandoning their battle to keep the price corralled," said Brien Lundin, editor of Gold Newsletter. April gold 
        GCJ22,
        +0.72%
       rose $47.40, or 2.4%, to settle at $2,043.30 an ounce after trading as high as $2,078.80. The settlement remained below the record-high finish of $2,069.40 from Aug. 6, 2020.,  The Pentagon on Tuesday rejected Poland’s offer to give the United States its MiG-29 fighter jets for use by Ukraine, in a rare public display of disharmony by NATO allies seeking to boost Ukrainian fighters while avoiding getting caught up in a wider war with Russia.                                                                                                                                                                                                                                                                                                                                                      , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 02:33:00 </td>
   <td style="text-align:left;"> US Stocks Regain Ground </td>
   <td style="text-align:left;"> US stocks rebounded sharply in the afternoon trading after falling shortly after the open as investors continued to monitor developments surrounding the war in Ukraine and rising commodity prices. The US announced a ban on imports of Russian oil, a move that threatened supply chains and heaped further inflationary pressure on economies worldwide. The Dow was up as much as 500 points after falling 200 points earlier, the S&amp;P was up 1.6%, and the Nasdaq surged 2.2%. Soaring crude oil prices lifted energy shares with Chevron and Exxon up 5% and 2.5%, respectively while Enphase Energy surged 14% and SunPower 21%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/zoom-video-workforce-has-nearly/story.aspx?guid={44A33EC6-338F-4717-97B9-4ECC5E94BC7C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-09 02:02:54 </td>
   <td style="text-align:left;"> Zoom Video workforce has nearly tripled in 2 years - MarketWatch </td>
   <td style="text-align:left;"> Zoom Video Communications Inc. 
        ZM,
        +0.57%
       disclosed late Monday that it had 6,787 full-time employees as of Jan. 31, 2022, nearly triple what the videoconferencing-service company's workforce was two years ago, before the pandemic. The latest workforce count, which included 4,009 employees in the U.S., was 53.5% from 4,422 employees (2,662 in the U.S.) as of Jan. 31, 2021, which was up 74.6% from 2,532 employees (1,396 in the U.S.) as of Jan. 31, 2020, according to the company's 10-K filings with the Securities and Exchange Commission. Zoom Video's stock had rocketed 395.8% in 2020, as COVID-19-related shutdowns sparked a buying frenzy in shares of remote-work enabling companies, then dropped 45.5% in 2021 as the frenzy faded with vaccinations and the gradual lifting of restrictions. With the stock down 38.6% year to date, it is now trading 80.1% below its Oct. 19, 2020 record close of $568.34, but is still 66.0% above where it ended 2019. Meanwhile, the S&amp;P 500 
        SPX,
        -0.72%
       has lost 10.7% this year, and is up 31.8% since the end of 2019., A Yale professor and his research team are keeping tabs on companies that are still operating in Russia following its invasion of Ukraine --- and the list includes many household names.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/08/stocks-making-the-biggest-moves-midday-chevron-caterpillar-sunpower-and-more-.html </td>
   <td style="text-align:left;"> 2022-03-09 01:30:12 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Chevron, Caterpillar, SunPower and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                         , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                             , Shell — Shares of Shell popped 2.7% after the company announced it was stopping all spot purchases of Russian crude oil. Shell also apologized for buying a heavily discounted consignment of Russian oil.                                                                                                                                              , Dick's Sporting Goods — Shares of the sporting goods giant jumped 2.1% after the company reported profits and sales growth in its holiday quarter that topped analysts' estimates. Dick's also offered a better-than-expected forecast for 2022 earnings and same-store sales, which it says sets a baseline for future growth coming out of Covid-19.  , Enphase Energy, SunPower — Enphase Energy and SunPower rose 10.8% and 18.7%, respectively, as rising oil prices resulting from the Russia-Ukraine conflict continue to shift attention toward alternative energy sources. President Joe Biden also announced Tuesday a ban on Russian oil and gas imports.                                              , Chevron, Exxon Mobil — Traditional energy stocks are up as oil prices continue to rise, and the U.S. announced a ban on Russian oil and gas imports in response to its war on Ukraine. Shares of Chevron and Exxon rose 5.2% and 0.8%, respectively.                                                                                                    , Dish Network — Shares of the telecom company jumped 5.2% on Tuesday after Dish received an upgrade from UBS to buy. UBS said in a note to clients that Dish's spectrum holdings are undervalued and provide a backstop against downside risk for the stock.                                                                                             , Apple — Apple shares fell 1.2%. The tech giant held its first launch event of the year on Tuesday. The company announced a new affordable iPhone, an update to the iPad Air and its latest, most powerful Mac chip.                                                                                                                                     , Caterpillar — Shares rallied 6.8% after Jefferies upgraded the stock to a buy rating from a hold rating. The firm said the surge in commodities prices sparked by Russia's invasion of Ukraine could boost Caterpillar's performance.                                                                                                                   , Petco —  Shares of Petco rose 8% after the company beat analysts' estimates on the top and bottom lines in the fourth quarter. The pet retailer also issued strong revenue guidance for 2022.                                                                                                                                                           , Okta — Shares rallied more than 3.3% after Mizuho upgraded the stock to a buy rating from neutral. Mizuho said the cybersecurity firm is "difficult to ignore."                                                                                                                                                                                         , ThredUp — Shares of ThredUp closed 0.8% lower after the company reported weaker-than-expected quarterly results. The company posted a loss of 18 cents per share versus the Refinitiv consensus estimate of 17 cents per share. ThredUp's revenue met analysts' estimates, but the company's first-quarter revenue guidance came in lower than expected., — CNBC's Yun Li, Jesse Pound and Maggie Fitzgerald contributed reporting                                                                                                                                                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 01:21:29 </td>
   <td style="text-align:left;"> French Shares Extend Slide </td>
   <td style="text-align:left;"> The CAC 40 erased early gains to close 0.3% lower at 5,962 on a choppy Tuesday session, extending its losing streak further to an 11-month low amid reports that the Euro bloc is considering a joint-bond sale to finance defense spending and a transition towards less dependence on energy imports. Tech shares plunged over 4% on projections of rampant inflation, led by Dassault Systemes (-7.4%) and STMicroelectronics (-2.5%). On the other hand, the energy sector closed 2% higher, underpinned by higher energy prices after the US and the UK announced an embargo on Russian energy imports, driven by CGG (15%) and TotalEnergies (1.9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 01:15:33 </td>
   <td style="text-align:left;"> South African Stocks Fall for 4th Day </td>
   <td style="text-align:left;"> The JSE FTSE All Share index closed 1.3% down at 72,360 on Tuesday, its lowest since January 24th, extending losses for a fourth straight session, as investors assessed the effects of Russia’s invasion of Ukraine on the global economy. Concerns that commodity costs will fuel inflation and choke economic growth have intensified after President Biden announced the US is banning all imports of oil and gas from Russia, with the purpose of targeting “the main artery of Russia’s economy”. On the domestic front, latest lata showed South Africa's economy grew 1.2% in the last quarter of 2021, as the economy recovered from a 1.7% contraction in the previous quarter caused by civil unrest in the country in July 2021, strikes and stricter coronavirus lockdown regulations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/vulnerable-iowa-dem-falsely-claims-that-government-spending-did-not-cause-inflation </td>
   <td style="text-align:left;"> 2022-03-09 01:13:37 </td>
   <td style="text-align:left;"> Vulnerable Iowa Dem falsely claims that government spending did not cause inflation </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines.                                                                                                                                                                                                                                                                                                                                                       , Democratic Rep. Cindy Axne of Iowa denied a link between government spending under President Biden's administration and the skyrocketing rate of inflation sweeping across the U.S. economy during a recent interview.                                                                                                                                                                                , Axne's position conflicts with what economists have said on the issue.                                                                                                                                                                                                                                                                                                                                , In an interview with local radio station KNIA-KRLS last week, Axne was asked whether she believed the unprecedented inflation in the U.S. economy was linked to the White House's spike in spending during and after the pandemic. Axne dismissed this narrative as a "talking point" and said that conclusion was "shortsighted" and not in touch with "the reality of things."                      , "The facts are that although there is inflation, it isn’t just because of – you can’t ever just – listen, I wouldn’t blame inflation on President Trump, and I’m not going to blame it on President Biden," Axne told host Bob Leonard. "To do so is so shortsighted and doesn’t look at the reality of things."                                                                                      , INFLATION AND RECORD GAS PRICES WILL HIT AMERICAN’S PAYCHECKS HARD                                                                                                                                                                                                                                                                                                                                    , Rep. Cindy Axne speaks during a news conference on Jan. 29, 2019, in Washington.  (Getty Images / Getty Images)                                                                                                                                                                                                                                                                                       , "It was decades of moving products out of our country from – you know, from creating them here," Axne continued. "Decades of putting tax policy in place that hurt working-class families but really helped out corporations not paying their fair share. And then you throw on top of it a major worldwide crisis of a pandemic, where we’re seeing supply-chain disruption across the entire world.", "Absolutely we’re going to see this. So let’s fix it. Let’s not just sit there and say, ‘Oh, you know, we’ve got this problem.’ Let’s talk about the solutions, and that’s what the president did last night, and I’m proud to be a part of it," she concluded.                                                                                                                                       , Axne, who previously dismissed inflation concerns as "false advertisements," has been targeted by the National Republican Congressional Committee (NRCC) as a vulnerable House Democrat heading into the 2022 midterms.                                                                                                                                                                               , Despite her claims about the causes of inflation, prominent economists, including Democrats, warned Democrats that their big-spending agenda would cause inflation. Steven Rattner, a former Treasury Department official under the Obama administration, said the spending in President Biden's American Rescue Plan was the "original sin" that caused inflation.                                   , "The original sin was the $1.9 trillion American Rescue Plan, passed in March. The bill – almost completely unfunded – sought to counter the effects of the COVID pandemic by focusing on demand-side stimulus rather than on investment," Rattner said in November 2021. "That has contributed materially to today’s inflation levels."                                                              , INFLATION NATION: THESE STATES ARE PAYING THE HIGHEST PRICES                                                                                                                                                                                                                                                                                                                                          , Larry Summers, president emeritus of Harvard University, speaks during the World Bank/IMF annual meetings in Washington on Oct. 9, 2014. (Reuters/Joshua Roberts / Reuters Photos)                                                                                                                                                                                                                    , Larry Summers, who served in the Obama administration and was the treasury secretary during the Clinton administration, also warned about inflation last year when Democrats were pushing for increased government spending.                                                                                                                                                                          , "I do think that unfortunately some of the predictions that I made about the consequences of stimulus do seem to have come true," Summers told CNN host Brianna Keilar.                                                                                                                                                                                                                               , The Federal Reserve of San Francisco also found last year that Biden’s $1.9 trillion spending bill contributed to driving up inflation.                                                                                                                                                                                                                                                               , President Joe Biden speaks during a news conference at the White House on Jan. 19, 2022. (Oliver Contreras/Sipa/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                            , A new report from the Joint Economic Committee revealed that U.S. households across the country are paying hundreds more each month due to inflation.                                                                                                                                                                                                                                                 , Households in Utah, Colorado, Arizona, New Mexico, Montana, Idaho and Wyoming are paying the highest average of $500 more per month due to 9% regional inflation as of January, the committee reported Wednesday.                                                                                                                                                                                     , On average, monthly costs per household across the U.S. increased from $100 more in April 2021 to over $380 in January 2022, according to the report.                                                                                                                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                           , U.S. inflation rose 7.5% in January – a 40-year high – and prices aren't expected to go down anytime soon as supply-chain disruptions continue into 2022, the committee noted in its report.                                                                                                                                                                                                          , Axne's office did not immediately respond to Fox Business' media inquiry.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-03-09 01:03:00 </td>
   <td style="text-align:left;"> Gold Firms Near Record </td>
   <td style="text-align:left;"> Gold surged to as high as $2,066 an ounce on Tuesday, just 9 dollars shy of its record peak hit in August 2020 as geopolitical and economic uncertainties stemming from the Russia-Ukraine war lifted demand for the safe-haven metal. In the latest developments, the US announced a ban on imports of Russian oil, a move that threatened supply chains and heaped further inflationary pressure on economies worldwide. Soaring commodities prices fuelled fears of stagflation for the global economy, bolstering the metal's appeal as an inflation hedge. On the flip side, the prospect of sharply higher interest rates should keep a lid on prices, with Chair Jerome Powell strongly backing the case for a 25bp rate rise on March 16. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 01:01:30 </td>
   <td style="text-align:left;"> UK Stocks Close Above the Flatline </td>
   <td style="text-align:left;"> The FTSE 100 closed slightly higher at 6,967 on Tuesday, marginally rebounding from the 5-month low touched last session as gains in financial stocks offset concerns about inflation after the UK announced it will phase out Russian oil imports by the end of 2022. The decision came after PM Boris Johnson said the government would set a new energy supply strategy to reduce its dependency on Russia, in retaliation to Moscow’s ongoing assault on Ukraine. Meantime, the Resolution Federation warned that UK household disposable income is set for its biggest decline since 1975 as inflation is forecasted to rise above 8% this spring as the conflict’s impact on global oil and gas prices will add to inflationary pressures. Among single stocks, insurer and asset manager M&amp;G surged over 15% on a 500-million-pound buyback program; and recruitment firm Robert Walters (7%) also gained after reported operating profit up 265% yearly in 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 01:00:00 </td>
   <td style="text-align:left;"> Madrid Stocks Outperform European Peers </td>
   <td style="text-align:left;"> Spain's IBEX 35 closed 1.8% firmer at 7,783 on Tuesday, outperforming its European peers, lifted by renewable energy companies and banks, following a report that the European Union is mulling a joint-bond sale to fund energy and defense spending. Also, energy giant Repsol advanced, tracking rising oil and gas prices. Meanwhile, investors assessed risks of stagflation and escalating sanctions against Russia, including a ban on Russian oil imports, which could push prices even higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/platinum </td>
   <td style="text-align:left;"> 2022-03-09 01:00:00 </td>
   <td style="text-align:left;"> Platinum Hits 9-Month High </td>
   <td style="text-align:left;"> Platinum prices rose to above $1160 per pound, the highest since June on stronger demand and possible supply disruptions. Expanding sanctions on Russia, a major producer of platinum, could make it harder for Russian-linked commodity firms to sell products. For example, Norilsk Nickel (Nornickel), is partly owned by Russia’s Rusal and accounts for 10% of global platinum mine production. Adding additional pressure, the demand for platinum is set to rise as the commodity is a necessity in petroleum refineries and in the chemical industry and is a cheaper alternative to palladium in the production of autocatalysts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 00:54:00 </td>
   <td style="text-align:left;"> European Stocks Close Mostly Lower </td>
   <td style="text-align:left;"> Europe’s major stock indices swung between gains and losses to end mixed on Tuesday, with the DAX and the FTSE 100 finishing flat, while the CAC 40 and the Stoxx 600 edged down 0.3% and 0.4%, each. Market sentiment was dominated by news of embargos on Russia energy goods, massive spending plans in the EU and the ongoing war in Ukraine. The US banned crude oil, LNG and coal imports, while the UK move will be phased over the coming months and won’t target natural gas. The EU was still divided, as Russia plays a much bigger role in oil and gas supplies. Also, the bloc will consider issuing joint bonds to finance energy and defense spending, while Ukrainian and Russian officials ended another round of ceasefire talks with little progress. Among sectors, banks rebounded by 2% from a 1-year low hit on the eve and media firms shed 3.6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-03-09 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Rebound </td>
   <td style="text-align:left;"> The FTSE MIB closed 0.8% higher at 22,338 on Tuesday, recovering from a three-day sell-off that sent the index to an over one-year low in the last session, as reports that the European Union could issue joint bonds to finance energy and defense spending eased concerns of Italy’s surging energy prices and dependency on Russian gas imports. At the same time, energy shares jumped over 2%, led by Saipem (13%), after the UK and US announced plans to ban Russian energy imports. Also, Telecom Italia shares rebounded nearly 6%, following last week’s plunge, as the private equity firm KKR expressed it is still interested in acquiring the Italian Telecom despite its poor Q4 results and spin-off announcements, albeit at EUR 0.4 per share compared to the previous bid of EUR 0.505 per share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-09 00:42:00 </td>
   <td style="text-align:left;"> Brent Crude Climbs on Russia Crude Ban </td>
   <td style="text-align:left;"> Brent crude futures rose 2% to near $127 per barrel on Tuesday, having jumped almost 8% earlier in the session after US President Biden announced a ban on the imports of Russian oil, gas and energy into the US as part of economic penalties for Russia’s invasion of Ukraine. Also, the UK is to phase out the import of Russian oil and oil products by the end of 2022. The ban would cut America’s annual supply of oil and refined products by 8%, with crude falling 3%. In Britain, the move is seen dragging down overall oil supply by 8% and diesel by 18%. Russia is the world’s third-largest oil producer, accounting for more than 10% of global supply, according to US EIA. Its exports account for 7% of the world market, of which around 60% go to Europe, making the continent more reluctant in joining the US and UK. Exxon Mobil Corp., BP PLC and Shell PLC all announced plans to exit Russian operations last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/08/us/politics/food-aid-nonprofits-fraud-investigation.html </td>
   <td style="text-align:left;"> 2022-03-09 00:30:12 </td>
   <td style="text-align:left;"> F.B.I. Sees ‘Massive Fraud’ in Groups’ Food Programs for Needy Children - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                          , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                           , Cracking down on the misuse of pandemic assistance, the agency says nonprofits in the Minneapolis area siphoned off tens of millions of dollars.                                                                                                                                                                                                                                                                                                       , By David A. Fahrenthold                                                                                                                                                                                                                                                                                                                                                                                                                                , MINNEAPOLIS — Last year, with the federal government making available huge new sums of money for programs to feed needy children during the pandemic, a nonprofit organization called Advance Youth Athletic Development set up what it described as an enormous child care operation in northeast Minneapolis that could prepare 5,000 dinners each weeknight.                                                                                        , Based on the group’s claims, the State of Minnesota channeled $3.2 million of the federal food aid to the program.                                                                                                                                                                                                                                                                                                                                     , But on a subzero morning in January, the F.B.I. carried out a series of predawn raids around the region. It revealed a sprawling investigation into Advance Youth Athletic Development and other groups like it — and the much larger nonprofit organization, Feeding Our Future, that was responsible for ensuring that the money provided to the smaller groups was spent properly.                                                                  , In court filings, the F.B.I. said it had discovered a “massive fraud scheme” among groups that Feeding Our Future was supposed to oversee, saying they siphoned off tens of millions of dollars by charging taxpayers for nonexistent meals.                                                                                                                                                                                                           , In affidavits filed in federal court, the Justice Department said it was investigating at least 15 different feeding operations. Together, the F.B.I. said, these groups — all of which were supposed to be overseen by Feeding Our Future — had received more than $65 million from federal food programs during the coronavirus pandemic.                                                                                                            , “Almost none of this money was used to feed children,” the government wrote in one filing. “Instead, conspirators misappropriated the money and used it to purchase real estate, cars and other items.”                                                                                                                                                                                                                                                , When a reporter recently visited the address listed for Advance Youth Athletic Development, there was no sign of a kitchen or a large child care facility. It was a second-story apartment.                                                                                                                                                                                                                                                            , “No. No. No,” said Lul Mohamoud, a neighbor in the apartment across the hall, when asked if she had ever seen 5,000 children there. “I have never seen any kids going in there.”                                                                                                                                                                                                                                                                       , No one has yet been charged in the case, and the leaders of Feeding Our Future, Advance Youth Athletic Development and other nonprofit groups have denied wrongdoing.                                                                                                                                                                                                                                                                                  , But the case has highlighted how the government’s reliance on nonprofits to help carry out an array of programs can increase vulnerability to fraud — a problem that only increased over the past several years, as Washington pumped trillions of dollars into pandemic aid packages.                                                                                                                                                                 , That aid has focused new attention on the role of nonprofits in particular in acting as conduits and overseers of federal money that flows through them via the states and then to smaller organizations that carry out programs. States and the federal government count on groups like Feeding Our Future to guard against corruption — even as the system incentivizes the organizations to push more money out the door by giving them a cut of it., In his State of the Union address last week, President Biden said that “billions” in pandemic aid had been stolen, and that he would soon name a chief prosecutor for pandemic fraud.                                                                                                                                                                                                                                                                  , In Minnesota, state regulators said that even after they grew suspicious of Feeding Our Future, they had been constrained by the courts from stopping the organization. In fact, the state paid the group more than $197 million after the first suspicions were raised.                                                                                                                                                                               , “The scale of this, and the rapidity of it, is astonishing,” said State Senator Roger C. Chamberlain, a Minnesota Republican whose committee oversees the food programs. He said his goal was to understand “why this system failed and collapsed completely. Because it certainly did.”                                                                                                                                                               , In all, more than 200 investigators from the F.B.I. and other agencies raided 15 homes and offices around the Twin Cities.                                                                                                                                                                                                                                                                                                                             , The Minnesota case involves two multibillion-dollar federal food-aid programs, both funded by the Agriculture Department but administered by states. One pays for meals at preschools, emergency shelters and aftercare centers. The other pays for meals at summer activities.                                                                                                                                                                        , In the 1970s, Congress created a role in both programs for nonprofits called sponsors, so that giant state bureaucracies and tiny day care centers did not have to talk to one another directly.                                                                                                                                                                                                                                                       , In theory, the nonprofit groups that fill the sponsor role make sure that feeding sites follow the rules, then hand out federal money to those that do.                                                                                                                                                                                                                                                                                                , The watchdogs can keep as an “administrative fee” up to 15 percent of the funds they pass along. Critics say that creates a perverse incentive: a reason for the watchdog not to bark. The structure, they say, rewards sponsors that pursue bigger networks and larger checks instead of those who crack down on fraud — a problem that has been evident for decades.                                                                                 , “Since the sponsor is essentially the internal control for this program, any disreputable sponsor could abuse the program with little or no chance of being detected,” the Agriculture Department’s inspector general wrote in 1998, after an investigation called Operation Kiddie Care found “fraud on a grand scale” in one of these programs. “In fact, the design of the program may encourage program abuse.”                                    , The Agriculture Department declined a request to interview an official about the case. Instead, the department issued a statement saying that “it takes fraud and the protection of taxpayer dollars very seriously.”                                                                                                                                                                                                                                  , Since the F.B.I. raids, news coverage by The Star-Tribune and Sahan Journal, a local nonprofit media outlet, has revealed that some of the operators of Feeding Our Future sites had criminal records, and that a former top aide to Mayor Jacob Frey of Minneapolis, a Democrat, was among those under investigation. The aide has denied wrongdoing.                                                                                                 , Minnesota first approved Feeding Our Future as a sponsor in 2018. In its first years, the group oversaw only a few feeding sites — and, at times, seemed to struggle with overseeing itself.                                                                                                                                                                                                                                                           , In February 2020, for instance, the I.R.S. revoked the group’s nonprofit status after it failed to file an annual report for three years. (Feeding Our Future says that status was later reinstated, but the I.R.S. still lists it as revoked.)                                                                                                                                                                                                        , In other filings, Feeding Our Future said it had a three-member board to provide outside oversight of its finances. But the man listed as the board’s president from 2018 to 2020, Ben Stayberg, a bartender and electrician, said he had been tricked into taking the job and had “absolutely nothing” to do with overseeing the organization.                                                                                                        , “I had a friend, she was like, ‘Will you just sign, put your name on there?’” he said in an interview. “I was like, ‘All right.’” Mr. Stayberg declined to give the friend’s name.                                                                                                                                                                                                                                                                     , When the pandemic hit, Feeding Our Future’s world changed.                                                                                                                                                                                                                                                                                                                                                                                             , School was out. Children were hungry. Starting in 2020, Congress poured money into the feeding programs and allowed the Agriculture Department to waive rules that had been put in place after previous scandals to make sure states watched the watchdogs. For instance, state officials no longer had to visit feeding sites in person to see whether they were doing what the paperwork said.                                                       , After that, Feeding Our Future began to grow rapidly, adding dozens of new sites to its network. Some of them were start-up nonprofits that had sprung up during the pandemic and never served food before.                                                                                                                                                                                                                                            , From 2019 to 2021, the number of children in Feeding Our Future’s network increased to about 400,000, from about 4,000, according to state records. The revenue flowing through its network increased to $197 million from $3.5 million.                                                                                                                                                                                                               , Feeding Our Future’s share grew to about $19 million, which its founder and president, Aimee Bock, said she spent largely on salaries for her 80 employees and supplies for feeding sites. She said she paid herself $190,000.                                                                                                                                                                                                                         , But there were puzzling features at some of the group’s new sites. In Minneapolis, two Feeding Our Future locations claimed to be running large child care centers out of the same small building — one feeding 2,000 children a day, the other 500, according to state records. (Ms. Bock said the state records were wrong, and she had never claimed that food was served there.)                                                                   , Another operation, housed in the nearby Safari Restaurant, claimed to be feeding 6,000 children a day on its own — more than the total number of children living in the restaurant’s ZIP code. Ms. Bock said the children came from surrounding areas, because the food was appropriate for East African immigrants, many of whom live in the area.                                                                                                    , Advance Youth Athletic Development’s site — the location that turned out to be a second-story apartment — had obtained nonprofit status in June, using a fast-track I.R.S. process for groups that expect to have receipts of less than $50,000 per year. The F.B.I. said that after the nonprofit partnered with Feeding Our Future, it asked for $730,000 in reimbursements in its first month.                                                      , A lawyer for Feeding Our Future said the group never had an accountant on staff.                                                                                                                                                                                                                                                                                                                                                                       , Then came the F.B.I. raids.                                                                                                                                                                                                                                                                                                                                                                                                                            , “My entire house shook,” Ms. Bock said. On the morning of Jan. 20, she said she heard banging and then saw F.B.I. agents at her front door. “All I could see were the spotlight and three guns, and they were just shouting, ‘Get down here! Get your hands up!’”                                                                                                                                                                                      , In an interview, Ms. Bock said she did not believe anyone in her network had cheated the system.                                                                                                                                                                                                                                                                                                                                                       , But if there was fraud, she added, “every test we have in place and every protection we have in place didn’t catch it. Is it possible? Absolutely. And if they got one over on us, I will help hold them accountable.”                                                                                                                                                                                                                                 , Guhaad Said, the leader of Advance Youth Athletic Development, said the state’s numbers were wrong.                                                                                                                                                                                                                                                                                                                                                    , “I don’t know where that number came from,” he said in a phone interview. “I don’t know where the 5,000 children came from.”                                                                                                                                                                                                                                                                                                                           , That number appeared on the group’s application to enroll in one of the food-aid programs, which Feeding Our Future submitted to the state.                                                                                                                                                                                                                                                                                                            , Mr. Said said his group had served meals at the site but declined to cite how many.                                                                                                                                                                                                                                                                                                                                                                    , “There was not proper oversight” from Feeding Our Future, he said. “So people may have made some mistakes here and there. But there was no intention to go out there and waste government money.”                                                                                                                                                                                                                                                      , In Minnesota, state regulators had grown alarmed by Feeding Our Future’s growth and lack of financial controls by summer 2020, a spokeswoman for the state’s Department of Education said. It tried to stop payments for many of the group’s sites. But Feeding Our Future asked a judge to intervene, accusing the state of discrimination because of its work with African immigrants and saying the state had not proved any allegations of fraud.  , If its payments were cut off, the organization told a judge, the results would be catastrophic, leading to bankruptcy, lost jobs and hungry children.                                                                                                                                                                                                                                                                                                  , A judge ruled that the state had not taken the necessary steps to stop the payments. After that, Minnesota officials called in the F.B.I. and continued to channel aid through the group while federal agents conducted a nine-month investigation.                                                                                                                                                                                                    , After the F.B.I. raids, Feeding Our Future was blocked from receiving state food aid. The group sought to formally dissolve in late February.                                                                                                                                                                                                                                                                                                          , Minnesota’s attorney general, Keith Ellison, said on Thursday that he was conducting a separate investigation of the group to determine whether it had violated state nonprofit laws.                                                                                                                                                                                                                                                                  , The state has also sought to cut ties with a second sponsor called Partners in Quality Care, which had supervised some of the nonprofits that worked with Feeding Our Future.                                                                                                                                                                                                                                                                          , A lawyer for Partners in Quality Care said it was fighting the action and had no indication that it was under investigation. As of last year, Feeding Our Future and Partners in Quality Care together oversaw 53 percent of the money that Minnesota disbursed through these two federal aid programs.                                                                                                                                                , But even after the F.B.I. raids, there are suggestions that some people are still trying to game the system.                                                                                                                                                                                                                                                                                                                                           , Lily Crooks, who operates a small day care center in Minneapolis, said she had worked with Feeding Our Future and received about $30 per month for a year for the snacks she served her children. After Feeding Our Future was raided, she said, a new sponsor called to recruit her — and immediately offered a plan to fool the state.                                                                                                               , What if, the woman suggested, Ms. Crooks told the government that her snack was actually a full meal instead? “We could call it breakfast” and make five times more, Ms. Crooks recalled the woman saying.                                                                                                                                                                                                                                             , Ms. Crooks said she declined, and was disheartened by the offer. “They are watchdogs, right?”                                                                                                                                                                                                                                                                                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/car-production </td>
   <td style="text-align:left;"> 2022-03-09 00:28:21 </td>
   <td style="text-align:left;"> Brazil Car Production Rebounds in February </td>
   <td style="text-align:left;"> Car production in Brazil jumped 14.1 percent over a month earlier to 165.9 thousand units in February of 2022, rebounding from a 31.1 percent plunge in the previous month but production fell 15.8 percent compared with February of 2021. Considering the first two months of 2022, output in auto plants contracted 21.7 percent amid the impact of the global semiconductor chip shortage and the more contagious Omicron variant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-09 00:27:00 </td>
   <td style="text-align:left;"> WTI Crude Continues to Rise on Russia Crude Ban </td>
   <td style="text-align:left;"> WTI crude futures surged as much as 8% to almost $130 per barrel before paring some gains after US President Biden announced a ban on the imports of Russian oil, gas and energy into the US as part of economic penalties for Russia’s invasion of Ukraine. Also, the UK is to phase out the import of Russian oil and oil products by the end of 2022. The ban would cut America’s annual supply of oil and refined products by 8%, with crude falling 3%. In Britain, the move is seen dragging down overall oil supply by 8% and diesel by 18%. Russia is the world’s third-largest oil producer, accounting for more than 10% of global supply, according to US EIA. Its exports account for 7% of the world market, of which around 60% go to Europe, making the continent more reluctant in joining the US and UK. Exxon Mobil Corp., BP PLC and Shell PLC all announced plans to exit Russian operations last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/car-registrations </td>
   <td style="text-align:left;"> 2022-03-09 00:22:48 </td>
   <td style="text-align:left;"> Brazil Car Sales Make Shy Comeback in February </td>
   <td style="text-align:left;"> Brazil auto sales rose by 2.2 percent month-over-month to 129.3 thousand units in February of 2022, following a 38.9 percent slump in the previous month but fell 22.8 percent from the same month in 2021. At the same time, exports of vehicles jumped 49.6 percent over the month to 41.4 thousand units and were up 25.4 percent on an annual basis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-03-09 00:19:06 </td>
   <td style="text-align:left;"> UK Gas is down by 5.47% </td>
   <td style="text-align:left;"> Natural Gas UK GBP decreased 5.47% to 510 GBp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/poland/interest-rate </td>
   <td style="text-align:left;"> 2022-03-09 00:09:48 </td>
   <td style="text-align:left;"> Poland Hikes Main Rate to 3.5% </td>
   <td style="text-align:left;"> The National Bank of Poland raised its benchmark reference rate by 75bps to 3.5% on March 8th to its highest level since February of 2013 and above expectations of a 50bps increase. It was the sixth consecutive hike of the main rate, as the NBP aimed to combat inflationary pressures brought by higher prices for energy and agricultural commodities due to Russian military aggression against Ukraine. Uncertainty and potential of raw materials shortages brought by the Russian invasion led the central bank to upwardly revise its 2022 inflation expectations to 9.3-12.2% (vs 5.1-6.5% in the November projection). The country’s latest price inflation reading came at 9.2% in January, the highest in 21 years and significantly above the central bank’s target range of 2.5% plus or minus one percentage point. On the other hand, the Polish economy expanded at 5.7% during 2021, ahead of market expectations. Meanwhile, the Lombard rate was increased to 4% and the rediscount rate was hiked to 3.55%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/consumer-confidence </td>
   <td style="text-align:left;"> 2022-03-09 00:05:00 </td>
   <td style="text-align:left;"> Colombia Consumer Morale Slides to 8-Month Low </td>
   <td style="text-align:left;"> Colombia’s consumer confidence index plunged further to -17.5 in February of 2022, from -13.5 in the previous month. It was the lowest reading since June amid a deterioration in both current economic conditions (-36.8 vs -30 in January), namely the propensity to buy durable goods (-52.2 vs -51.8); and future expectations (-4.7 vs -2.4), mainly for the country's economic situation and household position. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-03-08 23:59:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index at Over 2-Month High </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index rose 5.2% to 2,352 on Tuesday, its highest since December 20th 2021, extending gains into a third straight session, supported by gains across all vessel segments. The panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, was up 140 points to 3,041, its highest since December 10th; and the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, gained 147 points to 1,896. Among smaller vessels, the supramax index rose 93 points to 2,733, its highest in more than four months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-03-08 23:56:00 </td>
   <td style="text-align:left;"> Gasoline Nears All-Time High </td>
   <td style="text-align:left;"> Gasoline futures traded near $3.8 a gallon close to an all-time high of $3.89 hit in the previous session, as crude oil prices surged as much as 8%. US President Biden announced a ban on the imports of Russian oil, gas, and energy and the UK pledged to phase out the import of Russian oil and oil products by the end of 2022. Meanwhile, governments in the EU were more divided, as Russian oil accounts for roughly 30% of the bloc’s imports, although utilities in the region were already cutting their dependence on Russian oil. Earlier, Russia’s deputy Prime Minister warned a global embargo could cause crude prices to reach $300 a barrel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2022-03-08 23:51:00 </td>
   <td style="text-align:left;"> TTF Gas Slip on Tuesday </td>
   <td style="text-align:left;"> EU natural gas prices snapped a record-breaking rally to trade lower around €210 per megawatt-hour on Tuesday, roughly 40% down from a record high of €345 hit in the previous session, as traders continued assessing prospects of Russian supplies. The EU will unveil plans to jointly issue bonds on a potentially massive scale to finance energy and defense spending. Earlier, jitters over supplies were heightened after the Russian deputy Prime Minister Alexander Novak said its country had the right to halt natural gas flows in the Nord Stream 1 pipeline, adding there was intel on possible provocation being planned against pipelines in Ukraine. On Monday, prices climbed as much as 79% before settling at €227 in the most volatile session European markets have ever seen, in reaction to talks of an embargo on Russian energy goods by Western nations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2022-03-08 23:50:00 </td>
   <td style="text-align:left;"> Indian Rupee Hits All-time Low </td>
   <td style="text-align:left;"> The Indian rupee hit an all-time low of 77.1 per USD, tracking a general strength in US dollar and a continued surge in crude oil prices amid escalated tensions between Russia and Ukraine. Crude oil prices are again approaching $130 per barrel as both the US and the UK are set to ban oil imports from Russia. This creates an upward pressure on India’s trade deficit and inflation as the country imports two-thirds of its oil needs. Additionally, India’s GDP growth during the September-December period of 2021 slowed to 5.4% from 8.4% recorded in the previous quarter and came in much below the market estimates of 6% rise as Omicron cases and rising global commodity prices hit the economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-03-08 23:38:00 </td>
   <td style="text-align:left;"> Heating Oil Futures Hit Fresh Record High </td>
   <td style="text-align:left;"> Heating oil futures rallied by more than 10% to a fresh record high of $4.4 per gallon on Tuesday, as the US and the UK are expected to announce a ban on Russian oil imports. The American ban will include LNG and coal imports, according to reports, while the UK move will be phased over the coming months and won’t target natural gas. Meanwhile, the European Union remained divided over the decision, although most utilities and their energy trading partners were already cutting exposure to Russian energy supplies. Russia currently represents 8% of total crude and petroleum products arriving in the US. Earlier, the Russian deputy Prime Minister warned the oil barrel could reach $300 if a global embargo were to be placed, as the country produces 8% of total oil production. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/economic-optimism-index </td>
   <td style="text-align:left;"> 2022-03-08 23:16:00 </td>
   <td style="text-align:left;"> Americans Are the Most Pessimistic since 2013 </td>
   <td style="text-align:left;"> The IBD/TIPP Economic Optimism Index in the US fell to 41 in March of 2022, the lowest since October 2013, as the Russia's invasion of Ukraine sent oil prices higher and the stock market sharply lower. The six-month economic outlook index for the US fell 5 points to 33.9 and the personal finances subindex slid 4.1 points to 47.3, both at the lowest levels since August 2011. The gauge of support for federal economic policies edged up two-tenths of a point to 41.9. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-08 23:15:00 </td>
   <td style="text-align:left;"> US Stocks Remain Under Pressure </td>
   <td style="text-align:left;"> The Dow Jones plunged around 200 points, while the S&amp;P 500, the tech-heavy Nasdaq underperformed, falling 0.9% and 1.3%, respectively, with sentiment still dominated by the war in Ukraine, rising inflation, and higher interest rates. The US announced a ban on imports of Russian oil, a move that threatened supply chains and heaped further inflationary pressure on economies worldwide. However, the Fed is still forecast to raise interest rates by 0.25 percentage points at its March meeting. Still, Powell opened the door for a more aggressive move if inflation does not abate as anticipated. Energy stocks reasserted their dominance, while the high-flying technology sector was again under pressure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/wholesale-inventories </td>
   <td style="text-align:left;"> 2022-03-08 23:07:00 </td>
   <td style="text-align:left;"> US Wholesale Inventories Rise For 18th Month </td>
   <td style="text-align:left;"> Wholesale inventories in the US advanced 0.8 percent month-over-month to $799.9 billion in January of 2022, following an upwardly revised 2.6 percent increase in the prior month and matching a preliminary estimate. It was the 18th consecutive month of gains, amid increases in inventories of both durable goods (0.8 percent vs 3.1 percent in December) and nondurable ones (0.9 percent vs 1.8 percent). On a yearly basis, wholesale inventories advanced 18.1 percent in January, above a preliminary reading of 17.8 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-08 23:04:00 </td>
   <td style="text-align:left;"> Brent Crude Tops Again $130 </td>
   <td style="text-align:left;"> Brent crude futures soared 7% to above $130 per barrel on Tuesday, approaching a 2008-high of $139 hit in the previous session, as US President Biden is expected to announce a ban on imports of Russian oil during the press conference at 10:45 am ET. UK prime minister is also due to unveil a plan to cut UK's oil imports from Russia to zero over the coming months. In 2021, crude oil imports from Russia accounted for around 3% of the total in the US and 11% in the UK. Reduced inventories worldwide and a delay in reviving the Iran nuclear deal after Russia demanded trade guarantees from the US was also pressuring prices. Meanwhile, Russia warned it could stop the flow of natural gas through pipelines from Russia to Germany in response to Berlin's decision last month to halt the opening of the controversial new Nord Stream 2 pipeline and warned that if the West goes ahead with a ban, oil prices could hit $300 per barrel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coal </td>
   <td style="text-align:left;"> 2022-03-08 23:00:00 </td>
   <td style="text-align:left;"> Coal Record Rally Pauses </td>
   <td style="text-align:left;"> Newcastle coal futures consolidated around $400 per tonne in the second trading week of March, just 35 dollars shy of its record peak as mounting sanctions on Russia for invading Ukraine led to an international energy crunch and exacerbated concerns over the commodity's supply. The US is set to announce shortly that it will ban imports of Russian oil, a move that will further jeopardise energy supply chains. On top of that, limited access to European ports led to a rush by utilities in Asia and Europe to find alternative suppliers, such as Australia. Coal prices have more than doubled in value since the beginning of 2022, with earlier bullish sentiment already fueled by supply disruptions in top exporting countries such as Indonesia and Australia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-08 22:58:00 </td>
   <td style="text-align:left;"> Oil Surges By Over 7% Toward 2008 High </td>
   <td style="text-align:left;"> WTI crude futures jumped more than 7% to $128 per barrel on Tuesday, closing in on its highest level since 2008, as US President Biden is expected to announce a ban on imports of Russian oil shortly at the White House. The move will be in concert with the United Kingdom and will be phased in over the coming months. In 2021, crude oil imports from Russia accounted for around 3% of the total in the US and 11% in the UK. Reduced inventories worldwide and a delay in reviving the Iran nuclear deal after Russia demanded trade guarantees from the US was also pressuring prices. US crude stockpiles are expected to have decreased by about 800,000 barrels in the week to March 4. Meanwhile, Russia warned it could stop the flow of natural gas through pipelines from Russia to Germany and that if the West goes ahead with a ban, oil prices could hit $300 per barrel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-08 22:43:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Flat </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Ibovespa, pared early gains to trade around the flatline around 111,473 on Tuesday, as gains in oil companies and airline stocks were offset by losses in heavyweight miner Vale. Meanwhile, concerns over the ongoing conflict in Ukraine and risks of stagflation persisted. At the same time, the US and the UK are expected to announce soon that they will ban imports of Russian oil, a move that will likely intensify inflationary pressures. Domestically, a Brazilian Senate committee has requested that executives of state-run oil company Petrobras take part in a hearing to explain its dividend policy, at a moment when pressure on the firm grows amid high oil prices. Brazil's government is reportedly considering putting in place a new diesel and gasoline subsidy program to soften the blow of soaring oil prices after Russia's invasion of Ukraine, using dividends from state-run oil firm Petrobras to fund the measure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-08 22:41:06 </td>
   <td style="text-align:left;"> Wall Street Braces for More Volatility </td>
   <td style="text-align:left;"> US stock markets opened mixed on Tuesday, with the Dow Jones kicking off in positive territory and the S&amp;P 500 and Nasdaq 100 nearly flat. Market sentiment remains dominated by the war in Ukraine, rising inflation and higher interest rates. The US is expected to announce soon that it will ban imports of Russian oil, a move that could threaten supply chains and heap further inflationary pressure on economies worldwide. However, the Fed is still forecast to raise interest rates by 0.25 percentage points at its March meeting. Still, Powell opened the door for a more aggressive move if inflation does not abate as anticipated. Energy stocks reasserted their dominance, while the high-flying technology sector was again under pressure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60656673?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-08 22:40:39 </td>
   <td style="text-align:left;"> War in Ukraine: Russia says it may cut gas supplies if oil ban goes ahead </td>
   <td style="text-align:left;"> Russia has said it may close its main gas pipeline to Germany if the West goes ahead with a ban on Russian oil.                                                                                                                                                                                                                           , Deputy Prime Minister Alexander Novak said a "rejection of Russian oil would lead to catastrophic consequences for the global market", causing prices to more than double to $300 a barrel.                                                                                                                                               , The US has been exploring a potential ban with allies as a way of punishing Russia for its invasion of Ukraine.                                                                                                                                                                                                                           , But Germany and the Netherlands rejected the plan on Monday.                                                                                                                                                                                                                                                                              , The EU gets about 40% of its gas and 30% of its oil from Russia, and has no easy substitutes if supplies are disrupted.                                                                                                                                                                                                                   , While the UK would not be directly impacted by supply disruption, as it imports less than 5% of its gas from Russia, it would be affected by prices rising in the global markets as demand in Europe increases.                                                                                                                           , Iain Conn, the former boss of British Gas owner Centrica, said natural gas was "less freely" traded compared to oil, and it would be "much more difficult" to replace Russian gas if supplies are affected as it is transported through fixed pipelines from country to country.                                                          , The price of Brent crude - the global benchmark for oil prices - rose to around $130 a barrel on Tuesday following reports that the US and UK will announce its own ban on Russian oil imports.                                                                                                                                           , In an address on Russian state television, Mr Novak said it would be "impossible to quickly find a replacement for Russian oil on the European market".                                                                                                                                                                                   , "It will take years, and it will still be much more expensive for European consumers. Ultimately, they will be hurt the worst by this outcome," he said.                                                                                                                                                                                  , Pointing to Germany's decision last month to freeze certification of Nord Stream 2, a new gas pipeline connecting the two countries, he added that an oil embargo could prompt retaliation.                                                                                                                                               , "We have every right to take a matching decision and impose an embargo on gas pumping through the [existing] Nord Stream 1 gas pipeline," he said.                                                                                                                                                                                        , Russia is the world's second largest gas producer and third largest oil exporter, and any move to impose sanctions on its energy industry would badly damage its own economy.                                                                                                                                                             , Nathan Piper, head of oil and gas research at Investec, said although imposing sanctions on Russia's oil and gas exports was attractive, "practically it is challenging".                                                                                                                                                                 , He said both the global oil and gas markets were tight ahead of the war in Ukraine "with limited spare capacity to replace any disrupted Russian volumes".                                                                                                                                                                                , "The question is now whether US and European leaders are prepared to endure high oil and gas prices to add energy exports to the sanctions list," he told the BBC.                                                                                                                                                                        , "The threat of this action is almost the worst of both worlds, forcing prices up but doing nothing to limit Russian volumes or the revenues flowing to Moscow."                                                                                                                                                                           , Analysts at Capital Economics have forecast oil prices could rise to $160 a barrel if the West imposed sanctions on Russian exports, but David Oxley, senior global economist at the consultancy, told the BBC it was disruption to Russian gas that would hit countries harder, describing it as a "completely different kettle of fish"., He said energy intensive industries across Europe could be hit, with "vast swathes of heavy industry being switched off" as it is much harder finding replacement gas suppliers compared with oil.                                                                                                                                        , EU countries heavily reliant on Russian gas, such as Germany, could switch from gas to coal, he said, but that would run counter to the bloc's climate ambitions and would not be a long-term solution.                                                                                                                                   , The energy markets have been supremely volatile over the past week, and understandably so. There are genuine fears that supplies of oil and gas from Russia could be cut off or disrupted.                                                                                                                                                , Yet the response to Russia's suggestion it could close a major pipeline, depriving northern Europe of a large chunk of its gas supplies, has been pretty muted so far.                                                                                                                                                                    , There are a couple of reasons for this. Firstly, Russia is threatening a tit-for-tat embargo - cutting off its gas exports if the West goes ahead with a ban on Russian oil.                                                                                                                                                              , But despite pressure from the US, such a ban is unlikely. European leaders have already poured cold water on the idea - so Russia's counter-threat carries relatively little weight.                                                                                                                                                      , And then there's the fact that Russia is still making huge sums from sales of oil and gas to Europe every day, helping to fund its war.                                                                                                                                                                                                   , Moscow has everything to gain from exploiting traders' nerves to push up energy prices; but a great deal to lose if it were to carry out its threat.                                                                                                                                                                                      , Ukraine has implored the West to adopt an oil and gas ban, but there are concerns it would send prices soaring. Investor fears of an embargo drove Brent crude oil to $139 (£106) a barrel at one point on Monday - its highest level for almost 14 years.                                                                                , Meanwhile, wholesale gas prices rose to 565p per therm early on Tuesday, but fell to 480p in the afternoon.                                                                                                                                                                                                                               , UK stock markets rose slightly in early trading after a volatile Monday caused by the US's discussions over a potential Russian oil and gas ban.                                                                                                                                                                                          , Early on Tuesday, nickel prices on the London Metal Exchange more than doubled to rise above the $100,000-a-tonne level for the first time, before trading in the metal was suspended.                                                                                                                                                    , Russia supplies the world with about 10% of its nickel needs, mainly for use in stainless steel and electric vehicle batteries.                                                                                                                                                                                                           , Quoting unnamed sources, Reuters news agency reported that the US might be willing to move ahead with an embargo without its allies, although it only gets about 3% of its oil from Russia.                                                                                                                                               , However, German Chancellor Olaf Scholz has dismissed the idea of a wider ban, saying Europe had "deliberately exempted" Russian energy from sanctions because its supply could not be secured "any other way" at the moment.                                                                                                              , European powers have, however, committed to move away from Russian hydrocarbons over time, while some Western companies have boycotted Russian shipments or pledged to sell their stakes in Russian energy companies.                                                                                                                     , Mr Novak said that Russian companies were already feeling the pressure of US and European moves to lower the dependence on Russian energy, despite fulfilling all its contractual obligations to deliver oil and gas to Europe.                                                                                                           , "We are concerned by the discussion and statements we are seeing regarding a possible embargo on Russian oil and petrochemicals, on phasing them out," he said.                                                                                                                                                                           , This video can not be played                                                                                                                                                                                                                                                                                                              , Zara McDermott uncovers a dangerous 'rape culture' in Britain's classrooms                                                                                                                                                                                                                                                                , Villanelle curates this mix just for Eve...                                                                                                                                                                                                                                                                                               , Rosemary Laryea reveals the truth about being a 'soccer mum'                                                                                                                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/currency </td>
   <td style="text-align:left;"> 2022-03-08 22:32:00 </td>
   <td style="text-align:left;"> South Korean Won Depreciates Further </td>
   <td style="text-align:left;"> The South Korean won continued to depreciate in the second week of March, hitting 1230 against USD, the lowest since May 2020 amid general dollar strength and as surging oil prices triggered by the war in Ukraine are intensifying inflationary pressure. South Korea’s inflation rate held above 3% since October, well in excess of the central bank’s 2% target, keeping the pressure on the Bank of Korea despite having raised interest rates three times since August to 1.25%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/musk-andreessen-esg-investment </td>
   <td style="text-align:left;"> 2022-03-08 22:23:19 </td>
   <td style="text-align:left;"> Elon Musk, Marc Andreessen mock ESG investing </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines.                                                                                                                                                                                                                                                                                                                                                                                                                         , Tesla CEO Elon Musk and Andreessen Horowitz co-founder Marc Andreessen have taken aim at Environmental, Social and Governance (ESG) funds and what they view as a bit of hypocrisy, as investors mull whether ESG rules should be updated to allow for investment in defense companies amid Russia's invasion of Ukraine.                                                                                                                                               , STOCKS MIXED WITH OIL ABOVE $120, GOLD CROSSES $2,000                                                                                                                                                                                                                                                                                                                                                                                                                   , Andreessen tweeted out a screenshot on Tuesday of a Reuters article which referenced a note from analysts at Citigroup who noted defense is "likely to be increasingly seen as a necessity that facilitates ESG as an enterprise, as well as maintaining peace, stability and other social goods" following Russia's invasion of Ukraine.                                                                                                                               , "Recent events in Europe, we think, will significantly increase the likelihood of defense's inclusion in the EU's Social Taxonomy", they added.                                                                                                                                                                                                                                                                                                                         , "The plan: ESG funds will invest in defense companies to make the weapons required to fight wars with hostile regimes we buy energy from, because ESG funds won't invest in energy companies," Andreessen tweeted in response.                                                                                                                                                                                                                                          , Musk replied to Andreessen's tweet, adding that ESG rules "have been twisted to insanity."                                                                                                                                                                                                                                                                                                                                                                              , A 2018 European SRI Study found that 63.6% of EU investors excluded "controversial weapons" and 45.7% excluded "all weapons" from their portfolios due to the investments being "increasingly incompatible" with ethical and sustainable objectives.                                                                                                                                                                                                                    , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                 , Sweden's Skandinaviska Enskilda Banken AB recently said it would revise its ESG rules to permit six of its funds to invest in companies that generate more than 5% of their revenue from the defense sector starting April 1.                                                                                                                                                                                                                                           , "It is SEB Investment Management’s view that investments in the defence industry are of key importance to uphold and defend democracy, freedom, stability and human rights," the company told FOX Business in a statement. "At the same time, it is important to keep in mind that many of our customers and unit-holders still do not want to invest in the defence industry, and therefore going forward many of our funds will continue to exclude such investments.", Excluded investments will include companies that manufacture, develop, or sell weapons that violate international conventions, such as cluster bombs, land mines, and chemical and biological weapons, as well as companies that contribute to the development of nuclear arms programs or the production of nuclear weapons.                                                                                                                                           , Defense stocks have soared since the beginning of Russia's invasion, with shares of Raytheon Technologies up more than 11% year-to-date, shares of General Dynamics up more than 17% year-to-date, Huntington Ingalls Industries up more than 16% year-to-date, Lockheed Martin up more than 31% year-to-date and Northrop Grumman up more than 22% year-to-date.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60649214?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-08 22:11:18 </td>
   <td style="text-align:left;"> McDonald's and Coca-Cola boycott calls grow over Russia </td>
   <td style="text-align:left;"> Pressure is growing on Western food and drink giants to pull out of Russia due to the invasion of Ukraine.                                                                                                                                                                                                                                  , McDonald's and Coca-Cola have been criticised on social media for failing to speak out about the attacks and continuing to operate in the country.                                                                                                                                                                                          , Well-known firms including Netflix and Levi's have already suspended sales or stopped providing services in Russia.                                                                                                                                                                                                                         , McDonald's and Coca-Cola have not responded to the BBC's request for comment.                                                                                                                                                                                                                                                               , #BoycottMcDonalds and #BoycottCocaCola were trending on Twitter on Monday and over the weekend respectively.                                                                                                                                                                                                                                , Dragon's Den investor Deborah Meaden also spoke out on social media against the fizzy drinks company, urging people to stop drinking its products.                                                                                                                                                                                          , The criticism comes amid calls for other well-known Western firms such as KFC, Pepsi, Starbucks and Burger King to close their outlets and stop sales in Russia.                                                                                                                                                                            , However, most firms have stayed silent on the issue with Pepsi, Starbucks and Burger King also declining to respond to the BBC's requests for comment.                                                                                                                                                                                      , Fast food chain KFC did not respond initially but its owner Yum Brands, which also owns Pizza Hut, has since announced that it has suspended future investments in Russia.                                                                                                                                                                  , Yum Brands is the world's second-biggest restaurant chain, and there are about 1,000 KFC outlets and 50 Pizza Hut restaurants in Russia. The company was not pulling out entirely, but Yum said that it would "redirect all profits from operations in Russia to humanitarian efforts". It is also donating $1m (£762,000) to the Red Cross., Many of the firms the BBC has contacted have a large number of stores in the country.                                                                                                                                                                                                                                                       , In recently-published information on its website, McDonald's said that it has 847 stores in Russia. The company also owns the majority of these outlets, whereas across the rest of the world most are typically operated by franchisees.                                                                                                   , Both McDonald's and Pepsi, who have had a presence in Russia for decades, have also been singled out by the boss of New York state's pension fund.                                                                                                                                                                                          , Thomas DiNapoli, comptroller of the New York state common retirement fund, wrote letters to the companies, according to Reuters reports, urging them to review their businesses in Russia because they face "significant and growing legal, compliance, operational, human rights and personnel, and reputational risks".                   , Often, franchise owners will be able to take the decision as to whether or not to shut chains down, depending on terms of agreements they might have with big food chains like KFC or Starbucks.                                                                                                                                            , In a recent statement, Kevin Johnson, the boss of Starbucks, described attacks on Ukraine as "unprovoked" and "unjust".                                                                                                                                                                                                                     , But most of its sites in Russia remain open, according to its website. Most of these franchises are run by the Kuwait-based Alshaya Group.                                                                                                                                                                                                  , Kathleen Brooks, director at Minerva Analysis, said McDonald's and Coca-Cola were "very complicated businesses", which would not make it easy to make a decision to leave Russia quickly.                                                                                                                                                   , She told the BBC's Today programme that Coca-Cola had an "incredibly complicated structure" with bottling plants in Russia.                                                                                                                                                                                                                 , "I don't think it's as simple as saying can you just pull out of Russia," she said. "These are complicated businesses and there's a lot to consider, but right now the reputation risk could really hit their share prices so they may have no choice going forward."                                                                       , But Dr Ian Peters, director of the Institute for Business Ethics, told BBC News: "This is not a time to sit on the fence.                                                                                                                                                                                                                   , "The world is likely to judge companies by what they do in such circumstances, and ethical judgement will be as important as complying with any government-led regulations and sanctions."                                                                                                                                                  , He said that most firms would have what they refer to as an "ethical compass" they use to make big decisions.                                                                                                                                                                                                                               , "We would advise firms in such circumstances always to look at the bigger picture and seek to do the right thing, putting the wider interest above short-term profit," he added.                                                                                                                                                            , He cited important ethical dilemmas that might come up for companies when considering to suspend operations in Russia too: What duty of care do these companies hold to employees on the ground? Is it fair to deprive Russian citizens of basic goods?                                                                                     , Professor of business ethics at Henley Business School, Kleio Akrivou, suggested that these types of decisions might be more difficult to reach for food companies than, say, consulting firms.                                                                                                                                             , "When it comes to sanctions which deprive the Russian population of its basic goods and dignity, firms may need to approach the situation more thoughtfully, with an appeal to practical reason."                                                                                                                                           , She said now is the time for fast food giants to balance how real people are affected by such moves, alongside any reputational risk.                                                                                                                                                                                                       , This video can not be played                                                                                                                                                                                                                                                                                                                , Zara McDermott uncovers a dangerous 'rape culture' in Britain's classrooms                                                                                                                                                                                                                                                                  , Villanelle curates this mix just for Eve...                                                                                                                                                                                                                                                                                                 , Rosemary Laryea reveals the truth about being a 'soccer mum'                                                                                                                                                                                                                                                                                , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/imports </td>
   <td style="text-align:left;"> 2022-03-08 21:44:00 </td>
   <td style="text-align:left;"> Canada Imports Fall to 3-Month Low in January </td>
   <td style="text-align:left;"> Imports to Canada fell by 7.4 percent over a month to of CAD 54 billion in January of 2022, falling the most since October  last year. Decreases were observed in 9 out of 10 product sections, with declines led by cars and light trucks (-12.4%) amid lower imports from the United States and engines and parts (-15.4%). Additionally imports fell for electronic and electrical equipment and parts (-9%) due to the disruptions in the global supply chain; consumer goods (-4.5%), on decreased buying of clothing, footwear and accessories (-14.0%), as well as miscellaneous goods and supplies (-6.8%) while purchases also declined for basic and industrial chemical, plastic and rubber products (-8.5%), mainly on lower imports of lubricants and other petroleum refinery products (-16.6%); and fertilizers, pesticides and other chemical products (-13.2%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/imports </td>
   <td style="text-align:left;"> 2022-03-08 21:42:00 </td>
   <td style="text-align:left;"> US Imports Surge 1.2% to New Record </td>
   <td style="text-align:left;"> Imports to the United States increased 1.2 percent, or USD 3.8 billion, to a new record high of USD 314.1 billion in January of 2022. Purchases of goods were up USD 4.8 billion to USD 264.8 billion, due to imports of automotive vehicles, parts, and engines (USD 1.6 billion), industrial supplies and materials (USD 1.5 billion), particularly crude oil (USD 0.9 billion), natural gas (USD 0.6 billion) and copper (USD 0.6 billion). Also, imports grew for foods, feeds, and beverages (USD 1.4 billion) and capital goods (USD 1.1 billion). On the other hand, imports of services decreased USD 1.0 billion to USD 49.3 billion, led by transport (USD 0.8 billion) and travel (USD 0.5 billion). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/exports </td>
   <td style="text-align:left;"> 2022-03-08 21:37:00 </td>
   <td style="text-align:left;"> US Exports Fall 1.7% from Record </td>
   <td style="text-align:left;"> Exports from the United States decreased by 1.7 percent, or USD 3.9 billion, to USD 224.4 billion in January from the previous month's record high. Exports of goods decreased $2.3 billion to $155.9 billion, particularly pharmaceutical preparations (down $3.2 billion) and exports of services decreased $1.6 billion to $68.5 billion, mainly travel ($1.8 billion) and transport ($0.5 billion). On the other hand, sales of capital goods increased by $1.1 billion, due to civilian aircraft ($0.4 billion) and telecommunications equipment ($0.2 billion). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/exports </td>
   <td style="text-align:left;"> 2022-03-08 21:37:00 </td>
   <td style="text-align:left;"> Canada Exports Edge Down 0.2% in January </td>
   <td style="text-align:left;"> Exports from Canada edged down 0.2% over a month to CAD 56.6 billion in January of 2022 with declines observed in 7 of 11 product sections. Sales mainly decreased for passenger cars and light trucks (-15%) as supply chain issues continued to affect the Canadian auto industry in January, forcing most auto manufacturers to reduce production. Also, exports of aircraft and other transportation equipment and parts decreased 25.8%. However,these declines were almost entirely offset by higher exports of energy products (+ 8.7% vs -11.8% in December), particularly natural gas (+66.4%) and coal (+50.7%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/balance-of-trade </td>
   <td style="text-align:left;"> 2022-03-08 21:36:00 </td>
   <td style="text-align:left;"> US Trade Gap Widens to New Record High </td>
   <td style="text-align:left;"> The US trade deficit widened to a record high of $89.7 billion in January of 2022 from an upwardly revised $82 billion in the previous month and above market forecasts of an $87.1 billion gap. It reflects an increase in the goods deficit of $7.1 billion to $108.9 billion, as soaring energy costs pushed imports to a record high while the services surplus narrowed by $0.6 billion to $19.2 billion. Imports increased 1.2% to a new record high of $314.1 billion, boosted by purchases of passenger cars, crude oil, natural gas, copper, food and capital goods. Exports fell 1.7% to $224.4 billion, led by pharmaceutical preparations, travel and services, while shipments increased for civilian aircrafts, telecommunications equipment and financial services. The deficit with Canada increased $2.6 billion to $6.8 billion; the shortfall with Japan widened by $2.1 billion to $7.1 billion; while the gap with India decreased $1.5 billion to $2.4 billion. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-03-09 10:58:45 UTC +8

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
   <td style="text-align:left;"> 2022-03-09 10:58:13 </td>
   <td style="text-align:left;"> $SPY whatever I buy on the low goes down!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:58:02 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $QQQ As long as you remember where all the money from stocks is going to flow, you’ll be fine

https://www.cnbc.com/2022/02/14/with-rates-on-the-rise-tom-lee-sees-money-from-speculative-stocks-eventually-flowing-into-crypto.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:57:57 </td>
   <td style="text-align:left;"> $SPY if Biden disrupts the chip supply further, we are done.  Raimondo you dumb ass.  Never worked in a factory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:57:57 </td>
   <td style="text-align:left;"> $SPY Putin withdraws after McDonald&amp;#39;s announces suspension of sales 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:57:29 </td>
   <td style="text-align:left;"> $SPY Haw many times have you looked back and said &amp;quot;Damn I wish I bought when XYZ happened,  shit was so cheap!&amp;quot; This is your chance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:57:25 </td>
   <td style="text-align:left;"> $XOM $SPY I think people need to know that your technical analysis only goes so far. If something monumental happens in the world, oil and the market doesn&amp;#39;t give a fuck about your ta </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:57:07 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $BTC.X  … I don’t like this 1 bit 👇🏻

https://www.wsj.com/articles/russia-set-to-ban-commodity-exports-following-western-sanctions-11646768260 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:57:02 </td>
   <td style="text-align:left;"> $SPY just remember when this is all said and done, its ronald mcdonalds who will really saved the world by denying the holy big mac sauce. Maybe youll think twice about making fun of clowns. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:56:38 </td>
   <td style="text-align:left;"> $SPY looking at fake bullahs rn... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:56:18 </td>
   <td style="text-align:left;"> $USO $XLE $SPY  Oil will stay high as Putin knows  this is only weapon to survive besides Nukes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:56:06 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $TQQQ $UVXY 
VIX Futures Dripping 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:56:02 </td>
   <td style="text-align:left;"> $SPY early innings of wicked Bear market….act accordingly….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:55:56 </td>
   <td style="text-align:left;"> $SPY damn…They take away his $MCD now? Now he’s got the long cold winter nights with no cup of hot $SBUX or greasy Big Mac? I wouldn’t be surprised if the nukes start flying now…🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:55:53 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ all these fat, old, greedy boomers will finally get what they deserve. From this crash the new generation will take over while you old farts retire in your 2 star retirement homes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:55:52 </td>
   <td style="text-align:left;"> $SPY vol break out tomorrow. Today was the precursor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:55:44 </td>
   <td style="text-align:left;"> $SPY beautiful bull flag in futes rn !!!

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:55:42 </td>
   <td style="text-align:left;"> $SPY phew FJB stay alive for us because Kamalamma  will really fuk things up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:55:38 </td>
   <td style="text-align:left;"> $SPY all you predictors 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:55:15 </td>
   <td style="text-align:left;"> $SPY Nikkei holding, Hang Seng dumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:54:56 </td>
   <td style="text-align:left;"> $SPY ES futures will fade if oil rise.. but I think we are due for a breather.. just like it happen to Wheat today.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:54:55 </td>
   <td style="text-align:left;"> $SPY the war could end &amp;quot;in a moment&amp;quot; if Kyiv agreed to four conditions.
Ukraine would have to end all military action, write into its constitution that it would not join NATO or the European Union, officially recognize annexed Crimea as Russian territory and accept the independence of two breakaway eastern regions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:54:51 </td>
   <td style="text-align:left;"> $SPY tomorrow the Fed ends QE tomorrow…May have 0 buyers and no liquidity. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:54:42 </td>
   <td style="text-align:left;"> $SPY we need Trump to bring oil prices down to $2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:54:31 </td>
   <td style="text-align:left;"> $SPY so far, everyone is relatively on good behavior. A inimal amount of futes ripping/dipping, pamp it, and damp its spoken. Keep it up everyone! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:54:31 </td>
   <td style="text-align:left;"> $SPY $ES_F under 4170 can see 4150 fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:54:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $TSLA I think it says a lot when Saudi Arabia and the UAE refuse to take Joe Biden&amp;#39;s calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:54:12 </td>
   <td style="text-align:left;"> $SPY leave this buy crypto </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:53:55 </td>
   <td style="text-align:left;"> $SPY You think Biden is incompetent….wait til Kamalama is in the White House….U ain’t seen nothing yet…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:53:44 </td>
   <td style="text-align:left;"> $SPY $dwac freaking Biden
https://www.reuters.com/business/energy/us-oil-drilling-likely-accelerate-2022-kemp-2021-11-17/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:53:27 </td>
   <td style="text-align:left;"> $SPY algo pump fading now Since no one took the bait LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:53:16 </td>
   <td style="text-align:left;"> $SPY funny how I mentioned $300 earlier. Look at that...oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:53:04 </td>
   <td style="text-align:left;"> $SPY pump failed again liquidity runinng into gold and others ffs I&amp;#39;m still looking for a ppt pump until open but might just chase gold futures instead lol would hate to chase tho I&amp;#39;m already in gold 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:53:00 </td>
   <td style="text-align:left;"> $SPY hard to be bullish until the heavy weights that actually move this stop making lower highs and lower lows. All the top 10 names have daily RSI under 50, MACD’s negative, and sitting on supports. Not what you want to see for a bullish reversal in the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:52:58 </td>
   <td style="text-align:left;"> $SPY Send this thing to Chechnya </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:52:53 </td>
   <td style="text-align:left;"> $SPY this doesn’t end well for the US or Russia. China comes out on top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:52:43 </td>
   <td style="text-align:left;"> $SPY 300s incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:52:42 </td>
   <td style="text-align:left;"> $SPY there she goes...there she goes again 🎶 🎵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:52:42 </td>
   <td style="text-align:left;"> $SPY using Redbox until my Netflix put is closed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:52:41 </td>
   <td style="text-align:left;"> $SPY bruh moo and Ziggy goin at it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:52:41 </td>
   <td style="text-align:left;"> $SPY Recession 

 $dia $qqq $spx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:52:39 </td>
   <td style="text-align:left;"> $SPY  May GOD have mercy on these devil worshiper so than can see right path 
 
https://www.nytimes.com/2022/03/08/technology/chinese-companies-russia-semiconductors.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:52:39 </td>
   <td style="text-align:left;"> $SPY 

Biden bashers in 321 when we go red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:51:45 </td>
   <td style="text-align:left;"> $SPY Zelensky is an idiot, whole country become trash, Nato not accepting them EU also. What u want now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:51:44 </td>
   <td style="text-align:left;"> Tomorrow is the official end of fed QE…if we notice no more buyers - we know why. 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:51:34 </td>
   <td style="text-align:left;"> $SPY If you voted for Biden administration….Hang your head in shame….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:51:30 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:51:07 </td>
   <td style="text-align:left;"> $SPY  $QQQ  OIL TOPPY - NAS BOTTOMY 
DONT GET GREEDY OR  
YOU BECOME NEEDY 
😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:50:47 </td>
   <td style="text-align:left;"> $SPY Biden’s ban on Russian imports means $150 per barrel of oil, a $5 gallon of gas or higher, and a 1 in 3 recession risk: Moody’s
 https://flip.it/.2sich </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:50:42 </td>
   <td style="text-align:left;"> $SPY Overall rating of Biden: Neither Satisfied nor Dissatisfied. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:50:38 </td>
   <td style="text-align:left;"> $SPY so… are we allowed to buy goods with raw materials sourced from Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:50:14 </td>
   <td style="text-align:left;"> $SPY $QQQ brandon getting rejected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:49:56 </td>
   <td style="text-align:left;"> $SPY so coal is the new oil? Let’s go Brandon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:49:37 </td>
   <td style="text-align:left;"> $SPY Good night, but I think oil has still got room to run, I feel like real fear hasn’t quite hit yet. Unless I’m that stoic already LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:49:34 </td>
   <td style="text-align:left;"> $SPY 

Futes Rippin minions come out for a few quick posts then retreat into their caves for another 23 hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:49:32 </td>
   <td style="text-align:left;"> $USO $SPY  Maduro is a democrat now😂😂😂

05:40: BIDEN ADMINISTRATION HAS ASKED VENEZUELA TO SUPPLY PART OF ITS OIL TO WASHINGTON AS A CONDITION FOR EASING SANCTIONS ON CARACAS - RTRS, 09.03.22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:49:15 </td>
   <td style="text-align:left;"> $SPY remember this shite. These ppl are making out right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:49:01 </td>
   <td style="text-align:left;"> $SPY what is up with ppl claiming I paper trade?  Are they retarded?  I put so much effort into this. I give it my literal all.  And they think I paper trade?  🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:58 </td>
   <td style="text-align:left;"> $SPY 
Biden says bring on the nukes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:57 </td>
   <td style="text-align:left;"> $SPY the usa prez FJB suks so bad saudi Arabia declined to talk to him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:57 </td>
   <td style="text-align:left;"> $SPY biden: I want to speak to Saudi leader regarding oil, please. What you mean he won&amp;#39;t take call? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:41 </td>
   <td style="text-align:left;"> $SPY Don’t Fear!!!Kamala Harris is Here!!!🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:41 </td>
   <td style="text-align:left;"> $SPY wake me up from drunk when this hits 390$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:37 </td>
   <td style="text-align:left;"> $SPY 

Excited to read through the fed financial data will be released soon enough for q1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:36 </td>
   <td style="text-align:left;"> $SPY bro imma visit European countries in December and relay photos of frozen EU humans on Stocktwits free of charge. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:35 </td>
   <td style="text-align:left;"> $SPY - yup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:19 </td>
   <td style="text-align:left;"> $USO $SPY  Maduro is no more a dictator officially 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:18 </td>
   <td style="text-align:left;"> $SPY Asia looking sucky </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:48:08 </td>
   <td style="text-align:left;"> $SPY lolz Cramer bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:47:34 </td>
   <td style="text-align:left;"> $SPY who is this &amp;quot;Russian&amp;quot; guy and how can I contact HR about his negative comments towards my NATO identifying colleagues?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:47:33 </td>
   <td style="text-align:left;"> $SPY lol bulls peeking out of their bunkers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:47:13 </td>
   <td style="text-align:left;"> $SPY thing about markets is that they dont crash when you expect them to... also yall are too overhedged for this crash now, come back in May and Septemeber for the crash but until then its gonna stay chopping and squeezing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:46:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM MUST WATCH for all retail investors! Let me know your thoughts! https://youtu.be/emL-IhpQQFg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:46:56 </td>
   <td style="text-align:left;"> $SPY shit bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:46:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM Interesting subplot with these biolabs in Ukraine, funded by the Pentagon. Already, the NWO’s media juggernaut has pounced on it as fake news and conspiracy theory. China doesn’t seem to think so. 🤔 Kind of makes you wonder if this is simply a reaction to NATO expansionism.  Certainly, there’s a lot more than meets the eye on this whole thing. Putin wouldn’t have risked Russia’s future otherwise. And they’ve just about exhausted all economic tools to punish him, and all Russians; which, to be frank, is fairly extreme, if you think about it. On the one hand, they’re saying Putin is Hitler, and his own people are protesting in the streets. On the other, they’re more than willing to make sure all Russian citizens suffer because of the decision of one man. Heck, they’re willing to make us suffer, too. Have you seen the price of gas? Something doesn’t add up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:46:38 </td>
   <td style="text-align:left;"> $SPY hi bear

How mad are you right now with futes ripping??? 

Scale of 1-10

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:46:17 </td>
   <td style="text-align:left;"> $SPY jfc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:46:16 </td>
   <td style="text-align:left;"> $SPY 🌻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:46:00 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:45:59 </td>
   <td style="text-align:left;"> $SPY who wants $4080 first before $480 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:45:58 </td>
   <td style="text-align:left;"> $SPY Oil is going to $450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:45:48 </td>
   <td style="text-align:left;"> $SPY wonder if hang Seng will dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:45:46 </td>
   <td style="text-align:left;"> $SPY test </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:45:01 </td>
   <td style="text-align:left;"> $SPY day 13 kyiv will fall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:57 </td>
   <td style="text-align:left;"> $SPY of coarse it’s going to drag on .. the US is at risk now. Inflation is going to get worse while Putin posts up. Fuck sakes. We already lost this ppl , thanks to our genius *LEaDeRs* 

Can’t hunter just OD already? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:53 </td>
   <td style="text-align:left;"> $SPY the Chinese taking us down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:51 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
If the market crashes there’s gonna be riots in every major city. Another 2008 coming. Our time is coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:50 </td>
   <td style="text-align:left;"> $SPY when you realize nato ain&amp;#39;t gonna dave you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:41 </td>
   <td style="text-align:left;"> $SPY pump to $430 (bull trap) is my prediction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:38 </td>
   <td style="text-align:left;"> $SPY Sell the Rips instead of Buy the Dips! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:25 </td>
   <td style="text-align:left;"> $SPY pistachio? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:20 </td>
   <td style="text-align:left;"> $SPY 430 tomorrow guaranteed or your money back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:19 </td>
   <td style="text-align:left;"> $SPY so you telling me oil Goes up to 130 on fears of Russian oil being banned then when it actually does get banned it goes down and the fear just disappears huh? Gtfo🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:15 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:02 </td>
   <td style="text-align:left;"> $SPY has an average volume of 116795000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:02 </td>
   <td style="text-align:left;"> $SPY Muppets are the best traders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:44:00 </td>
   <td style="text-align:left;"> $MARPS  🛢🔥👍  $SPY $SARK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:55 </td>
   <td style="text-align:left;"> $SPY Ooooops! I guess there were biolabs! Fake news loses again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:52 </td>
   <td style="text-align:left;"> $SPY eat a nut, save the world! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:50 </td>
   <td style="text-align:left;"> $SPY 

“Fitch Downgrades Russia to &amp;#39;C&amp;#39;”.
It’s like a thief breaking into your house and suing you for not having anything to steal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:42 </td>
   <td style="text-align:left;"> $SPY Zoom out. Nothing about what’s going on in the world is bullish. Nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:38 </td>
   <td style="text-align:left;"> $SPY 2 steps from WW3. Under every the Democrat president the world test us. Pray it doesn’t get any worse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:30 </td>
   <td style="text-align:left;"> Gold moving $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:29 </td>
   <td style="text-align:left;"> $SPY Futes Crippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:21 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:21 </td>
   <td style="text-align:left;"> $SPY this makes ZERO SENSE. Biden needs to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:20 </td>
   <td style="text-align:left;"> $SPY transitory lmfao 🤣 😂 💀 😆 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:19 </td>
   <td style="text-align:left;"> $SPY the rally is over . it was today from 1 to 1:15 pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:18 </td>
   <td style="text-align:left;"> $SPY wait what, I have to phycoanalyze nuts.....because ur kids are what? Can&amp;#39;t eat a nut? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:17 </td>
   <td style="text-align:left;"> $KO $MA $V $SPY  As China and India siding with Russia are these companies getting out from those countries too so I  can short these more ☺️😉☺️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:43:04 </td>
   <td style="text-align:left;"> $SPY does that mean Fed is going to delay..?

https://www.reuters.com/markets/europe/ecb-wait-until-q4-raise-rates-despite-rampant-inflation-2022-03-07/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:42:32 </td>
   <td style="text-align:left;"> $SPY so we’re getting some oil from Venezuela…. or proposed or asked… and i ask the liberals.. why cant we lift restrictions here and pump our own oil…?😆😆😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:42:16 </td>
   <td style="text-align:left;"> $SPY futes no more rippi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:42:08 </td>
   <td style="text-align:left;"> $SPY $TSLA WHEN HOUSING MARKET CRASH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:42:07 </td>
   <td style="text-align:left;"> $SPY I have been posting plans for everyday targets hitting precisely. You had 3 opportunities to make good profits if you followed me. If Its hard to follow with so many posts follow my twitter @optionboys  I lay out trading plan everyday for free on my twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:42:04 </td>
   <td style="text-align:left;"> $SPY Biden’s logic: fight inflation by lowering prices . Okay so do that to gas 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:41:57 </td>
   <td style="text-align:left;"> $NIO loading tomorrow. Sentiment feels very good right now. Emotion has calmed from the massive depression of a market. Haha. $SOFI love this stonk. Amazing growth. $SPY run it. $QQQ be patient been a rough year. $OSCR oscar overreactions. Loading tomorrow many. Lady steps down but remains there for 2 years. I mean for fook sakes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:41:55 </td>
   <td style="text-align:left;"> $SPY Jesus loves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:41:49 </td>
   <td style="text-align:left;"> $SPY Imagine thinking Venezuela&amp;#39;s Maduro is any better than Putin. Snake Biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:41:46 </td>
   <td style="text-align:left;"> BIDEN ADMINISTRATION HAS ASKED VENEZUELA TO SUPPLY PART OF ITS OIL TO WASHINGTON AS A CONDITION FOR EASING SANCTIONS ON CARACAS 
 
$spy $uso $oxy $sco $xom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:41:34 </td>
   <td style="text-align:left;"> $SPY oil will peak when national avg is 4.20 for gas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:41:28 </td>
   <td style="text-align:left;"> $SPY you guys know this isn’t even bear yet right? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:41:26 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:41:18 </td>
   <td style="text-align:left;"> $SPY apparently wierdo people can&amp;#39;t hang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:41:16 </td>
   <td style="text-align:left;"> $SPY Maybe Biden can solve the gas crisis by just putting black dye in water. Same thing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:40:59 </td>
   <td style="text-align:left;"> $SPY Putin using the Democrat … White Supremacist thing about Ukraine … a page right out of the old Democrat Manifesto </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:40:46 </td>
   <td style="text-align:left;"> $SPY 
Every night without failure, Futes Rippin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:40:43 </td>
   <td style="text-align:left;"> $SPY what&amp;#39;s Obama think about Ukraine? Lmfai </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:40:16 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:40:09 </td>
   <td style="text-align:left;"> $SPY Oh, you’re crying over gas prices? 

YEAH, WELL MAYBE YOU SHOULD STOP BEING POOR! YOU POOR PERSON. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:40:09 </td>
   <td style="text-align:left;"> $SPY I heard they put NUTS in gas. So think about </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:40:06 </td>
   <td style="text-align:left;"> $SPY if tomorrow green then Thursday Friday blood bath 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:39:55 </td>
   <td style="text-align:left;"> $SPY gonna waste some money on some lotto 0dte calls first thing in the morning. Nothing big, fk it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:39:37 </td>
   <td style="text-align:left;"> $SPY  $QQQ $AAPL 
Gas going much higher. Higher costs for all people and businesses. 👎  
Bad for Stock Market unfortunately.
7.00 in Las Angels Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:39:35 </td>
   <td style="text-align:left;"> $SPY 😬sub 4100 by thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:39:26 </td>
   <td style="text-align:left;"> $SPY 

Middle finger on the daily lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:39:25 </td>
   <td style="text-align:left;"> $SPY well 430 is out of the question 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:39:20 </td>
   <td style="text-align:left;"> $SPY 430 tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:39:17 </td>
   <td style="text-align:left;"> $SPY 1000% of the time wierd nut people are making ur life harder. 100000% of the time this nourishment sustained us all. Sleep well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:39:10 </td>
   <td style="text-align:left;"> $SPY Going green trmw bears are lunatics </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:39:01 </td>
   <td style="text-align:left;"> $SPY pump feels weak . But who bought the dip today ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:38:50 </td>
   <td style="text-align:left;"> $SPY $QQQ brandon looking for oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:38:28 </td>
   <td style="text-align:left;"> $SPY futures are ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:38:23 </td>
   <td style="text-align:left;"> $SPY   
               OMFG … TOO MANY PUTS,
…MORONS!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:38:18 </td>
   <td style="text-align:left;"> $CL_F $SPY $QQQ Killing the Market, Sky rocket Oil LGB!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:38:11 </td>
   <td style="text-align:left;"> $ES_F 

The S&amp;amp;P 500 index is closing in on a death cross, an ominous chart pattern that underscores the downtrend suffered in an asset.
A death cross appears when the 50-day moving average crosses below the 200-day moving average, an event that many chart watchers view as marking the spot a shorter-term correction morphs into a longer-term downtrend.

At last check, the S&amp;amp;P 500 index SPX was trading down 0.6%, with its 50-day moving average at 4,508.56 and its 200-day at 4,466.34, a differential of 42.22 points, which it could possibly breach by next week at the current pace of decline.

$SPY $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:37:58 </td>
   <td style="text-align:left;"> $QQQ $SPY More than 6,000 everyday products get their start from oil, including dishwashing liquid, solar panels, food preservatives, eyeglasses, DVDs, children&amp;#39;s toys, tires and heart valves. Here are some of the common petroleum products that are an important part of our modern lifestyle. 
 
Inflation is going through the roof. That means more and higher rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:37:57 </td>
   <td style="text-align:left;"> $SPY if the US ban and some western European countries ban  buying Russian oil, but China and other countries still buy Russian oil at a cheaper price, won&amp;#39;t China decrease the amount of oil it buys from other countries?  Not sure if I&amp;#39;m right about this, maybe someone could verify.

Thus, the overall supply is the same, just us and western European countries just give more money to the middle east countries while China, , etc save money...

Sounds like China, and the Middle east countries outplayed USA... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:37:56 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:37:52 </td>
   <td style="text-align:left;"> $SPY Lol now zelensky simps on twitter comparing the comedian to legendary Greek king Leonidas. Nah I can&amp;#39;t take this shit anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:37:51 </td>
   <td style="text-align:left;"> $SPY can we just cull all the wierdo nut people yet?  4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:37:27 </td>
   <td style="text-align:left;"> $SPY 
Taking bets on when the Biden administration begins sending &amp;quot;Energy Inflation Relief&amp;quot; stimulus checks. 🙊🙈🙉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:37:22 </td>
   <td style="text-align:left;"> $SPY I know it’s still early but shocked FUTES are up with energy ban. Like, wut? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:37:02 </td>
   <td style="text-align:left;"> $SPY damn @_Ziggy is clapping moo with facts right now...😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:36:49 </td>
   <td style="text-align:left;"> $SPY 

“Cold beer on a Friday night” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:36:43 </td>
   <td style="text-align:left;"> $SPY $QQQ 

https://news.cgtn.com/news/2022-03-07/Russia-reveals-evidence-of-U-S-funded-bio-program-in-Ukraine-18cUbBlPXhu/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:36:21 </td>
   <td style="text-align:left;"> $SPY The world knows Trump won. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:36:10 </td>
   <td style="text-align:left;"> $SPY gonna eat a little bitta edibles and stalk Hong Kong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:36:10 </td>
   <td style="text-align:left;"> $SPY 
Shiba holding strong thru all this 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:36:00 </td>
   <td style="text-align:left;"> $SPY crypto </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:35:53 </td>
   <td style="text-align:left;"> $SPY Mexico will pay for the wall by closing its southern border and have Guatemala pay for it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:35:50 </td>
   <td style="text-align:left;"> $SPY 15 this morning, now back to 13 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:35:38 </td>
   <td style="text-align:left;"> President Joe Biden’s executive order on #Bitcoin &amp;amp; #Crypto will be announced tomorrow March, 9th 
 
$btc $BTC.X  $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:35:31 </td>
   <td style="text-align:left;"> $SPY Nuts 4 everyone. Easy poison. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:35:14 </td>
   <td style="text-align:left;"> $SPY rally tomorrow n then POOTZ CITY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:58 </td>
   <td style="text-align:left;"> $SPY i think tomorrow will be really bad just a guess lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:57 </td>
   <td style="text-align:left;"> $SPY  $QQQ  NOW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:44 </td>
   <td style="text-align:left;"> $SPY &amp;#39;Saudis, UAE Refuse To Take Biden&amp;#39;s Calls To Discuss Ukraine Situation, Talk To Putin Instead&amp;#39; 
 
Lol, half the worlds population &amp;amp; most commodity based economies now telling us to go pound sand. What a joke we&amp;#39;ve become. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:36 </td>
   <td style="text-align:left;"> $SPY SPY 2022-03-08 Daily Forecast Video: 
https://www.youtube.com/watch?v=FSCPUS2yJIU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:33 </td>
   <td style="text-align:left;"> $SPY anyone tell me why nobody can eat nuts? Like stfu and die already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:30 </td>
   <td style="text-align:left;"> $SPY dems probably initiated this war to drive oil prices up and use that to pass their BBB and shove that bs clean energy on our throats. What a nasty human beings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:28 </td>
   <td style="text-align:left;"> $DWAC truth social should buy twitter and have Mexico pay for it $TWTR $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:27 </td>
   <td style="text-align:left;"> $SPY  death trap 🪤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:23 </td>
   <td style="text-align:left;"> $SPY we are getting divergence in oil, and decent chance topping pattern forming, could see another top though. Info more for tech and spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:14 </td>
   <td style="text-align:left;"> $BTC.X $SPY $ETH.X $ADA.X $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:09 </td>
   <td style="text-align:left;"> $SPY everyone go back to the west or east media and listen how both sides brag about how they won a war, but in reality it will just be a stalemate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:34:07 </td>
   <td style="text-align:left;"> $SPY guaranteed that this will go down under $400 soon. 
Asset prices are still way too high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:55 </td>
   <td style="text-align:left;"> $SPY we did it, Joe. LOL GL Dudes EXTREMELY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:49 </td>
   <td style="text-align:left;"> $SPY $240 is my personal call on oil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:44 </td>
   <td style="text-align:left;"> $SPY do u feel in charge bull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:41 </td>
   <td style="text-align:left;"> $SPY last couple of days, I was busy and I didn’t pay much attention on this. With just my single hand I will make your trillion puts worthless. I will drag the shorts all the way to $666. Mark and print this post. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:36 </td>
   <td style="text-align:left;"> $AAPL $SPY 

Futures trying to breakout but green candles are quickly sold off quick.. Slight green for now.

It&amp;#39;s early morning in Moscow...so..more to come. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:26 </td>
   <td style="text-align:left;"> $SPY Sure sign SPY will drill further here. Big boys not willing to hold in this market is all you need to know. 
 
Today was a great indication where we are heading. And its way lower. 
 
Do not get caught up in the hype folks. Play it safe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:26 </td>
   <td style="text-align:left;"> $SPY I don’t even watch comedies anymore to get my laughs. I just go on this page and listen to people talk on StockTwits and I get my laughter for literally the rest of the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:25 </td>
   <td style="text-align:left;"> $SPY If we invade Venezuela and claim their oil, what&amp;#39;s the worst that happens? We have to learn Spanish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:20 </td>
   <td style="text-align:left;"> With no more help from the Fed in the short term doesn’t mean you stop growing your long term positions think long term $SPY markets move in cycles there will come a time when Fed starts pumping again be patient compound when they are not helping so when they do you portfolio grows fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:16 </td>
   <td style="text-align:left;"> $SPY IM JUST Bull for tomorrow fellow bears HOLD THE LINE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:33:14 </td>
   <td style="text-align:left;"> $SPY did Ucraine sign that they will not sign with NATO again with peace talks or is it rumors? And Europe is and cannot afford to turn down Russian oil?
I&amp;#39;ll ask </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:32:49 </td>
   <td style="text-align:left;"> $SPY The markets might have all the negatives (war, inflation, stagflation, etc.) “priced in” BUT the market has NOT priced in the ACTUAL damage that all of these negatives will cause. There’s no way for the market to price in the Actual damages until they are felt. We have yet to feel the effects of everything, by a long shot. Trade carefully </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:32:47 </td>
   <td style="text-align:left;"> $SPY can we hurry up and move on with this stalemate war. everyone knows whats going to happen no ones invading russia, no ones invading western europe, no ones invading US or china. Thats how the game works. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:32:35 </td>
   <td style="text-align:left;"> $SPY they saying bears fuccd and we ain’t even 1% up on futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:31:59 </td>
   <td style="text-align:left;"> $SPY  I have been posting plans for everyday targets hitting precisely. You had 3 opportunities to make good profits if you followed me. Its hard to follow with so many posts follow my twitter @optionboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:31:58 </td>
   <td style="text-align:left;"> $SPY Hi, I am now announcing the GRAND OPENING of Enterprise-Rent-A-Horse. 

With gas prices this high, switch to carrot energy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:31:55 </td>
   <td style="text-align:left;"> $SPY I will never ever EVER cast my vote for a fucking democrat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:31:38 </td>
   <td style="text-align:left;"> $SPY Now the US has recruited Al Queda/ISIS to help the Nazis and CIA/Soros backed leadership to fight Russians in Ukraine. We seriously need to rethink our foreign policy. 
https://english.almayadeen.net/news/politics/450-arab-and-foreign-extremists-from-idlib-arrive-in-ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:31:34 </td>
   <td style="text-align:left;"> $SPY Dont need no gas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:31:33 </td>
   <td style="text-align:left;"> $SPY 

Why are put printing peasants still penniless ????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:31:07 </td>
   <td style="text-align:left;"> $DWAC Truth social should buy Facebook and Deport Mark Zuckerberg to Venezuela $FB $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:30:59 </td>
   <td style="text-align:left;"> $SPY go pick mushrooms </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:30:55 </td>
   <td style="text-align:left;"> $SPY Pissants looking to form alliances. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:30:51 </td>
   <td style="text-align:left;"> $SPY Why didn’t the MSM play videos of crying Arabs when we invaded the Middle East? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:30:44 </td>
   <td style="text-align:left;"> $SPY a pump back to $430 would set a wicked bull trap and I would full port shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:30:39 </td>
   <td style="text-align:left;"> $SPY all end points have been tested successfully. It is time to fly $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:30:34 </td>
   <td style="text-align:left;"> $SPY So awkwardly wierded out by all of u humans now. Gonna go grow a farm. Ur all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:30:21 </td>
   <td style="text-align:left;"> $SPY $QQQ The price of gas is about to be higher than most peoples credit scores. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:30:16 </td>
   <td style="text-align:left;"> $SPY when can I start taking fake, simulated vacations in the metaverse? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:30:04 </td>
   <td style="text-align:left;"> China $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:57 </td>
   <td style="text-align:left;"> $SPY Calling Dr Fauci 
 
 
China accuses the U.S. military of operating “dangerous” biolabs in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:52 </td>
   <td style="text-align:left;"> $SPY Just ordered my Lambo boys 😎😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:51 </td>
   <td style="text-align:left;"> VENEZUELA HAS RELEASED TWO JAILED U.S. CITIZENS AFTER U.S OFFICIALS VISIT -RTRS 
 
Next would be great if  usa get oil from Venezuela to bring oil prices down 
 
$spy $uso $sco </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:47 </td>
   <td style="text-align:left;"> $SPY  This asshole zelensky could’ve ended the war with Russia if he accepted Putin’s new offer… now we’re all gonna suffer bc of him. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:46 </td>
   <td style="text-align:left;"> $SPY bet you all wish you took physical delivery of your oil futures last year (when it went under $0) and dumped it in your pool now huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:34 </td>
   <td style="text-align:left;"> $SPY can we talk articles and a speech today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:30 </td>
   <td style="text-align:left;"> $SPY Missouri avian flu....chicken 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:15 </td>
   <td style="text-align:left;"> $SPY PUTin Puts will print. Shorting every buy the dip pump. Puts for discount every pump. 🔪🩸🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:03 </td>
   <td style="text-align:left;"> $SPY the death of credit. Money will be really hard to come by. Canned corn to $6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:29:00 </td>
   <td style="text-align:left;"> $SPY War is over green trmw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:28:59 </td>
   <td style="text-align:left;"> $SPY 

We are supposed to think about sticking it to Putin as we will  fill up at the tank according to crazy liberals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:28:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Joe Biden likes to accuse Tyson Foods of price gouging, what about Big Oil companies? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:28:41 </td>
   <td style="text-align:left;"> $SPY Death cross means bad news for all of us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:28:36 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;d be funny if zelenski turns on nato🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:28:33 </td>
   <td style="text-align:left;"> $SPY • </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:28:30 </td>
   <td style="text-align:left;"> $SPY NOWHERE TO GO BUT UP FOLKS🇺🇸🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:28:01 </td>
   <td style="text-align:left;"> $SPY so how many of you believe the earth is moving 66,000 mph through space while spinning at 1,000 mph? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:27:55 </td>
   <td style="text-align:left;"> $SPY FYI, crude oil is still over $120. I wouldn’t be surprised if we see $130+ tomorrow with the news sanctions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:27:45 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:27:29 </td>
   <td style="text-align:left;"> $SPY This oil situation is fracked up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:27:27 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:27:14 </td>
   <td style="text-align:left;"> $SPY 

Alien ships spotted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:27:08 </td>
   <td style="text-align:left;"> $SPY zelenski conceded </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:27:07 </td>
   <td style="text-align:left;"> $SPY bill always tell like it is

Bill Ackman said on Twitter that World War III may have already begun.
&amp;quot;WWIII has likely started, but we have been slow to recognize it,&amp;quot; the billionaire hedge-fund manager said in a tweet thread on Saturday.
&amp;quot;We are in the early innings of Putin&amp;#39;s global aspirations. With each &amp;#39;victory,&amp;#39; he is emboldened to take more. He is testing us, and we are failing the test each time,&amp;quot; he added, referring to Russian President Vladimir Putin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:26:51 </td>
   <td style="text-align:left;"> $SPY $380! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:26:51 </td>
   <td style="text-align:left;"> $SPY people who voted for Biden think this is totally normal, everything&amp;#39;s fine 👽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:26:35 </td>
   <td style="text-align:left;"> Rally of ages comes on anything positive $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:26:35 </td>
   <td style="text-align:left;"> $SPY every time there is a consolidation like this we have a &amp;quot;panic sell&amp;quot; day with crazy dumps and rsi jumping up 30%.  I haven&amp;#39;t seen that yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:26:35 </td>
   <td style="text-align:left;"> $SPY BidenHarris 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:26:35 </td>
   <td style="text-align:left;"> $SPY 

VENEZUELA HAS RELEASED TWO JAILED U.S. CITIZENS AFTER U.S OFFICIALS VISIT -RTRS

Oh, how generous of Maduro… 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:26:21 </td>
   <td style="text-align:left;"> $SPY futures deep red by 3am ✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:26:20 </td>
   <td style="text-align:left;"> $SPX $SPY mid term election year fractal roadmap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:26:15 </td>
   <td style="text-align:left;"> $DWAC $SPY &amp;quot;WHEN BEARS ARE SENT OVER THEY ARENT SENDING THEIR BEST PEOPLE. THEY ARE THUGS, RAPISTS...DRUG DEALERS...CARTELS. SOME I ASSUME ARE GOOD PEOPLE BUT FOLKS THEY HAVE TO GO BACK&amp;quot;

🍊🏆👑🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:25:34 </td>
   <td style="text-align:left;"> $SPY damn holy fuck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:25:30 </td>
   <td style="text-align:left;"> $SPY $FB $AAPL  so McDonald&amp;#39;s, Facebook , coke gone from Russia . 10yr down the lane . Russian are healthy , intelligent, well informed generation. We america will left with freedom . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:25:28 </td>
   <td style="text-align:left;"> $SPY Covid…..🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:25:24 </td>
   <td style="text-align:left;"> $SPY  
Is this some sort of artifact from a divine being? I wanna touch it too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:25:22 </td>
   <td style="text-align:left;"> $SPY Very low GEX means buy the dip on any significant pullback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:25:12 </td>
   <td style="text-align:left;"> $SPY how much you wanna bet Trump 2024 coming like a freight train? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:25:10 </td>
   <td style="text-align:left;"> $SPY FUTURES RIPPIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:25:00 </td>
   <td style="text-align:left;"> $SPY me thinks I should be quiet. 401 actually. It’s absolutely fucked lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:59 </td>
   <td style="text-align:left;"> $SPY I’m calling my quant tomorrow to start bitching about my IRA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:55 </td>
   <td style="text-align:left;"> $SPY vix losing momo spy gaining momo come on Putin spark this biotch with a cease fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:28 </td>
   <td style="text-align:left;"> $SPY Market has a hard on to break lower than the psychological low of $400. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:21 </td>
   <td style="text-align:left;"> $SPY sitting with 90 417c exp 3/14 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:20 </td>
   <td style="text-align:left;"> $SPY Why are the Libs so against American energy independence, what the hell is wrong with them? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:19 </td>
   <td style="text-align:left;"> $SPY US: &amp;quot;Hey Poland, give your jets to Ukraine and we&amp;#39;ll give you F16s&amp;quot; 
Poland: &amp;quot;Ok, here they are. We&amp;#39;ll send them to Germany -- they can use German airbases for strike missions against Russia&amp;quot; 
US: &amp;quot;What? That&amp;#39;s a surprise. What jets&amp;quot; 
Germany: &amp;quot;Um, what?&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:13 </td>
   <td style="text-align:left;"> $SPY gonna crash

Oil spiking again

$SPX $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:08 </td>
   <td style="text-align:left;"> $SPY futes mad rippin tonight my lads 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:06 </td>
   <td style="text-align:left;"> $DWAC $SPY UNDER PRESIDENT TRUMP IN &amp;#39;24 &amp;quot;THE BEST IS YET TO COME&amp;quot;🍊🏆🇺🇸🎉🚀☀️😊

DO IT🍊🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:02 </td>
   <td style="text-align:left;"> $SPY Sell the rumor buy the news. CPI and rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:02 </td>
   <td style="text-align:left;"> $SPY the west never thought our enemies would make moves.  we thought our alliances would appear strong and prevent aggression. wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:24:02 </td>
   <td style="text-align:left;"> $SPY Russian  energy ban! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:23:59 </td>
   <td style="text-align:left;"> $SPY $XBI $QQQ is anyone concerned at how powerful the &amp;quot;Stand with Ukraine&amp;quot; propaganda campaign is? The same people that support arming Ukraine and the Ukraine flag DO NOT SUPPORT THE AMERICAN FLAG AND ARMED AMERICAN CITIZENS. IT IS VERY CONCERNING. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:23:57 </td>
   <td style="text-align:left;"> $SPY yabba dabba doo look at OIL right now wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:23:41 </td>
   <td style="text-align:left;"> $SPY FED will announce new QE around $SPY 380 before they even raise .25 basis points
Watch and learn newbs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:23:35 </td>
   <td style="text-align:left;"> $SPY ….no one believes Biden or Democrats. Theatre of lies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:23:34 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:23:30 </td>
   <td style="text-align:left;"> $AMC $SPY was weirdly in the same zone/price during the June run up ? Yellow lines are the high/low of the spy week of June </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:23:15 </td>
   <td style="text-align:left;"> $SPY Friday I get payed bout to dump 2k on whatever and add more on margin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:23:12 </td>
   <td style="text-align:left;"> $SPY shocking that Poland declined orders from Biden. Someone needs to explain to him that he isn&amp;#39;t the dictator of NATO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:23:04 </td>
   <td style="text-align:left;"> $SPY you&amp;#39;re ready for Recession 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:51 </td>
   <td style="text-align:left;"> Every day work on your goals stay consistent don’t get bent out of shape over people walking out of your life $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:48 </td>
   <td style="text-align:left;"> $SPY if this rips like I think it might I’m taking profits and shorting it for the big one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:47 </td>
   <td style="text-align:left;"> $SPY 
I doubt any rate hikes anymore Gas prices will slow the economy on its own </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:46 </td>
   <td style="text-align:left;"> $DWAC $SPY $TSLA I’ve had enough of Biden’s communist socialist regime. I’m dumping my wife and applying for Russian citizenship, they have beautiful women </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:44 </td>
   <td style="text-align:left;"> $DWAC $spy damn Biden
https://www.wsj.com/articles/american-frackers-show-restraint-as-oil-tops-70-11625823000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:22 </td>
   <td style="text-align:left;"> $Spy US rejects Poland offer of jets for Ukraine as not ‘tenable’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:18 </td>
   <td style="text-align:left;"> $SPY 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:17 </td>
   <td style="text-align:left;"> $SPY I have been posting plans for everyday targets hitting precisely. You had 3 opportunities to make good profits if you followed me. I am also running a paid group if you are interested in joining message me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:13 </td>
   <td style="text-align:left;"> $SPY straight rejecting off EMA..but we ripping ! ✨ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:11 </td>
   <td style="text-align:left;"> $SPY Silly futures rally. Bulls must be hoping that the CPI will be a hot mess of stinking lies (it will), or that Putin will suddenly apologize and go home in shame (he won&amp;#39;t), or that Polands old soviet jets will somehow defeat Russia (they won&amp;#39;t), and miraculously not start WW3 (it will). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:22:03 </td>
   <td style="text-align:left;"> $SPY lesson learned yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:21:57 </td>
   <td style="text-align:left;"> $SPY good think I canceled keystone with an executive order first day in office </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:21:41 </td>
   <td style="text-align:left;"> S&amp;amp;P 500 Biggest Gainers &amp;amp; Losers for 03/08/22- $SPX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:21:12 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m buying when rate hikes get announced tbh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:21:11 </td>
   <td style="text-align:left;"> $SPY Only the libtards believe it&amp;#39;s all Russia&amp;#39;s fault, but we know the truth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:21:04 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:20:52 </td>
   <td style="text-align:left;"> $SPY in putin’s world there is no coke zero. just zero coke 🤔🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:20:39 </td>
   <td style="text-align:left;"> $DWAC $SPY MAGA🍊🏆🚀🇺🇸☀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:20:32 </td>
   <td style="text-align:left;"> $SPY no emotions ever. Don’t need them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:20:09 </td>
   <td style="text-align:left;"> $SPY 40 year plus high Inflation 🔥 maybe we learn something from this big fing crisis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:20:01 </td>
   <td style="text-align:left;"> $TSLA $SPY $DWAC Libs, Dems, social losers love pedophilia. They’re crying because they want kindergarteners to learn about sexuality 

CNN = pedo ring 
Lincoln project = pedo ring 
Weinstein, Clinton

SICK! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:19:53 </td>
   <td style="text-align:left;"> $SPY “Banks will not sell hard currency to citizens during the period of the temporary order,”  https://www.msn.com/en-us/money/markets/russia-bars-purchases-of-dollars-by-citizens-in-sign-of-hard-currency-pinch/ar-AAUO25Y?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:19:49 </td>
   <td style="text-align:left;"> $SPY Russian trolls out in force again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:19:40 </td>
   <td style="text-align:left;"> $SPY no one cares who you side with just let my calls hit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:19:39 </td>
   <td style="text-align:left;"> $SPY I need the biggest down day yet tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:19:36 </td>
   <td style="text-align:left;"> $SPY posted on wrong board lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:19:36 </td>
   <td style="text-align:left;"> $ICL https://tradingeconomics.com/united-states/imports/russia/fertilizers

$SLV $GLD $SPY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:19:32 </td>
   <td style="text-align:left;"> $SPY now I will beg Venezuela..US got the worst leader now..unfortunate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:19:28 </td>
   <td style="text-align:left;"> $SPY the math adds up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:19:00 </td>
   <td style="text-align:left;"> $SPY is exodus wallet headquarters in Nebraska 
I&amp;#39;m looking for a wallet that&amp;#39;s not located in the west that can be trusted or should I use ledger I&amp;#39;m looking to have bitcoin whenever I cross border so carrying a ledger with meni might not want to do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:18:55 </td>
   <td style="text-align:left;"> $spy I&amp;#39;ll save us all 🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-09 10:18:47 </td>
   <td style="text-align:left;"> $BBBY bears big mad. Don’t realize this company is way undervalued  $SPY $QQQ 
🗣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:58:02 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $QQQ As long as you remember where all the money from stocks is going to flow, you’ll be fine

https://www.cnbc.com/2022/02/14/with-rates-on-the-rise-tom-lee-sees-money-from-speculative-stocks-eventually-flowing-into-crypto.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:57:07 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $BTC.X  … I don’t like this 1 bit 👇🏻

https://www.wsj.com/articles/russia-set-to-ban-commodity-exports-following-western-sanctions-11646768260 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:56:54 </td>
   <td style="text-align:left;"> $QQQ this is my favorite gif </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:56:39 </td>
   <td style="text-align:left;"> $QQQ Ready for sub 13k tomorrow? YIKES 😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:55:53 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ all these fat, old, greedy boomers will finally get what they deserve. From this crash the new generation will take over while you old farts retire in your 2 star retirement homes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:55:14 </td>
   <td style="text-align:left;"> $QQQ I wouldn’t dare hold long overnight without puts I bought that were in the money so I could pin it… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:55:03 </td>
   <td style="text-align:left;"> $NIO $AAPL $MSFT $QQQ $TSLA you know sh*t is getting real when Switzerland stops being neutral for the first time in 500 years and starts freezing Russian accounts. There’s a really good chance that we’re going to have WW3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:54:49 </td>
   <td style="text-align:left;"> $IDEX $QQQ $WMT $1800 into $40k in the last 30 days.. If you really want to make huge profits on trading then, Join this winning chat:~~~🚀  livestk-opt-trading.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:54:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $TSLA I think it says a lot when Saudi Arabia and the UAE refuse to take Joe Biden&amp;#39;s calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:52:41 </td>
   <td style="text-align:left;"> $SPY Recession 

 $dia $qqq $spx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:51:44 </td>
   <td style="text-align:left;"> Tomorrow is the official end of fed QE…if we notice no more buyers - we know why. 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:51:29 </td>
   <td style="text-align:left;"> $QQQ lol what was that pump and dump though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:51:07 </td>
   <td style="text-align:left;"> $SPY  $QQQ  OIL TOPPY - NAS BOTTOMY 
DONT GET GREEDY OR  
YOU BECOME NEEDY 
😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:50:14 </td>
   <td style="text-align:left;"> $SPY $QQQ brandon getting rejected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:48:55 </td>
   <td style="text-align:left;"> $QQQ ev sector is going to be a safe haven for money soon.  Fomo will engage soon Tesla rivian ford maybe even the shit hole plug </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:47:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 80374800. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:46:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM MUST WATCH for all retail investors! Let me know your thoughts! https://youtu.be/emL-IhpQQFg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:46:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM Interesting subplot with these biolabs in Ukraine, funded by the Pentagon. Already, the NWO’s media juggernaut has pounced on it as fake news and conspiracy theory. China doesn’t seem to think so. 🤔 Kind of makes you wonder if this is simply a reaction to NATO expansionism.  Certainly, there’s a lot more than meets the eye on this whole thing. Putin wouldn’t have risked Russia’s future otherwise. And they’ve just about exhausted all economic tools to punish him, and all Russians; which, to be frank, is fairly extreme, if you think about it. On the one hand, they’re saying Putin is Hitler, and his own people are protesting in the streets. On the other, they’re more than willing to make sure all Russian citizens suffer because of the decision of one man. Heck, they’re willing to make us suffer, too. Have you seen the price of gas? Something doesn’t add up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:44:51 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
If the market crashes there’s gonna be riots in every major city. Another 2008 coming. Our time is coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:42:26 </td>
   <td style="text-align:left;"> $QQQ I have been posting plans for everyday targets hitting precisely. You had 3 opportunities to make good profits if you followed me. If Its hard to follow with so many posts follow my twitter @optionboys  I lay out trading plan everyday for free on my twitter ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:42:21 </td>
   <td style="text-align:left;"> $QQQ  Price Action remains weak. Down Trend line rejection today after seeing no upside follow through to the hammer bar from last Thursday.  #QQQ  
 
Trend remains down unless otherwise proven.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:41:57 </td>
   <td style="text-align:left;"> $NIO loading tomorrow. Sentiment feels very good right now. Emotion has calmed from the massive depression of a market. Haha. $SOFI love this stonk. Amazing growth. $SPY run it. $QQQ be patient been a rough year. $OSCR oscar overreactions. Loading tomorrow many. Lady steps down but remains there for 2 years. I mean for fook sakes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:41:20 </td>
   <td style="text-align:left;"> $QQQ under 320 tmmrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:39:37 </td>
   <td style="text-align:left;"> $SPY  $QQQ $AAPL 
Gas going much higher. Higher costs for all people and businesses. 👎  
Bad for Stock Market unfortunately.
7.00 in Las Angels Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:38:50 </td>
   <td style="text-align:left;"> $SPY $QQQ brandon looking for oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:38:23 </td>
   <td style="text-align:left;"> $QQQ futes stopped rippin uhoh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:38:18 </td>
   <td style="text-align:left;"> $CL_F $SPY $QQQ Killing the Market, Sky rocket Oil LGB!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:37:58 </td>
   <td style="text-align:left;"> $QQQ $SPY More than 6,000 everyday products get their start from oil, including dishwashing liquid, solar panels, food preservatives, eyeglasses, DVDs, children&amp;#39;s toys, tires and heart valves. Here are some of the common petroleum products that are an important part of our modern lifestyle. 
 
Inflation is going through the roof. That means more and higher rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:36:43 </td>
   <td style="text-align:left;"> $SPY $QQQ 

https://news.cgtn.com/news/2022-03-07/Russia-reveals-evidence-of-U-S-funded-bio-program-in-Ukraine-18cUbBlPXhu/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:34:57 </td>
   <td style="text-align:left;"> $SPY  $QQQ  NOW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:34:09 </td>
   <td style="text-align:left;"> $QQQ $GEVO $ROKU $MU They have helped me to grow my account to almost 2.5 million...... 100% recommend joining! 
 
It&amp;#39;s free joining ~~~~🚀 livestk-opt-trading.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:32:46 </td>
   <td style="text-align:left;"> $QQQ I have been posting plans for everyday targets hitting precisely. You had 3 opportunities to make good profits if you followed me. Its hard to follow with so many posts follow my twitter. @optionboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:32:45 </td>
   <td style="text-align:left;"> $QQQ if this guy had been in charge, there would be no war today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:30:21 </td>
   <td style="text-align:left;"> $SPY $QQQ The price of gas is about to be higher than most peoples credit scores. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:28:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Joe Biden likes to accuse Tyson Foods of price gouging, what about Big Oil companies? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:27:45 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:27:27 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:26:35 </td>
   <td style="text-align:left;"> Rally of ages comes on anything positive $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:24:13 </td>
   <td style="text-align:left;"> $SPY gonna crash

Oil spiking again

$SPX $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:23:59 </td>
   <td style="text-align:left;"> $SPY $XBI $QQQ is anyone concerned at how powerful the &amp;quot;Stand with Ukraine&amp;quot; propaganda campaign is? The same people that support arming Ukraine and the Ukraine flag DO NOT SUPPORT THE AMERICAN FLAG AND ARMED AMERICAN CITIZENS. IT IS VERY CONCERNING. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:23:26 </td>
   <td style="text-align:left;"> $QQQ https://apple.news/AH5yUo7btS1ywM7rVaI4_uA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:22:30 </td>
   <td style="text-align:left;"> $QQQ  I have been posting plans for everyday targets hitting precisely. You had 3 opportunities to make good profits if you followed me. I am also running a paid group if you are interested in joining message me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:19:57 </td>
   <td style="text-align:left;"> $QQQ retail investors bought the dip while hedge funds got out of the market. Who will be right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:18:47 </td>
   <td style="text-align:left;"> $BBBY bears big mad. Don’t realize this company is way undervalued  $SPY $QQQ 
🗣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:17:28 </td>
   <td style="text-align:left;"> $QQQ As bitcoin is on the come-up and its been the Canary in the Coal mine lately, we are seeing green Jesus candles tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:17:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Futes are rippin! This should mean that Oil goes down, I hope becuz I shorted that overbought crap today😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:17:08 </td>
   <td style="text-align:left;"> Financials $XLF Semis $SOXL and $QQQ are all broken.  
 
Clearlization to get a nice rally in $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:16:00 </td>
   <td style="text-align:left;"> $SPY $QQQ My guess is now that we are trading with Venuezala oil prices will go back down shortly! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:13:06 </td>
   <td style="text-align:left;"> $SPY $XBI $QQQ $AKBA have you listened to Putin&amp;#39;s statement?  
youtube.com/watch?v=X6YeIM8... 
Putin says that the Donetsk People&amp;#39;s Republic requested Russia&amp;#39;s assistance to demilitarize and DENAZIFY Ukraine. Ukraine has become a dictatorship that is murdering it&amp;#39;s own civilians and is now threatening Russia.  We are not being told the truth here. Putin then says he does not plan on occupying Ukraine afterwards. Now, I don&amp;#39;t blindly trust Putin either. But there are things we simple are not being told by the lying MSM. That paint him to be a madman who wants to takeover some poor little country. It isn&amp;#39;t true. 
 
He is saying NATO violated agreements and has been building military forces on the Ukraine/Russia border. This war isn&amp;#39;t what it seems. We are being fed propaganda by the MSM. If you want to know why Putin has invaded Ukraine, he was prompted to do so by NATO, and the West. Biden actually said in the SOTU that Russia invaded Ukraine without provocation; that is a big lie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:12:36 </td>
   <td style="text-align:left;"> $VTI $SPY $QQQ 

JP Morgan — 
&amp;quot;In bear markets, stocks return to their rightful owners.&amp;quot; 

Not retiring for another 30 years. Will continue to DCA and live life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:11:37 </td>
   <td style="text-align:left;"> $QQQ RSI Showing some divergence but who cares. There is way more fundamental head winds than one silly RSI divergence can shake off. Will continue lower. PT still at $260 at least. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:09:09 </td>
   <td style="text-align:left;"> $SPY looks like the Biden Administration did not prevent the big energy crisis $XLE $AAPL $QQQ inflation was much higher 7.5% last month January 2022 how much higher will inflation be going forward ? Probably a lot higher inflation is coming … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:09:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $BTC.X  
 
A couple days ago I made a bold prediction that Putin will be dead by years end, and I&amp;#39;d like to provide an update on that. 
 
I now also believe he will be out of power within the coming months, likely much sooner. 
 
1. With an estimated invasion cost of $22 billion / day, it would take 67 days before exhausting their entire 2020 GDP, but that&amp;#39;s not actual tax revenue, which averages 20%. 
 
2. Given a trailing GDP of $1.7 trillion, this would translate to tax revenues of $340 billion, meaning just *15 DAYS* before exhausting it entirely. 
 
3. Anyone remember the classified war plans left behind by Russians confirming US intelligence of a planned Blitzkrieg? It was a *15 DAY* plan, which may be a coincidence but sure as hell an interesting one. 
 
4. Putin is desperate, freezing assets and limiting withdrawals to $10k/mo in a now fully isolated state. Anger and isolation are growing rapidly, ignoring ever harsher penalties. 
 
Vive La Révolution 
 
https://stocktwits.com/Fundy_OracleOfAlpha/message/441718084 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:08:24 </td>
   <td style="text-align:left;"> $QQQ 100w holding with a larger support at 300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:07:41 </td>
   <td style="text-align:left;"> Lmfao &amp;amp; there goes oil to latex0f35267c45b83641dc509a23f3f1824fSpy 380 open.

$SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:07:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $VXX $DIA The next 2 weeks are very important. If my thesis of a two week Russian conquest of Ukraine is going to happen. Then expect the VIX to go from 35 to 17 in a very short amount of time. This will propel markets higher. Oil will fall, gold and silver will fall. Money will leave bonds. And it will have nowhere to go but US equities (and possibly bitcoin since its sitting pretty low at 38k) Staying bullish, but I am very concerned of a possible recession due to the Russian oil ban. We can easily see $7 a gallon in this country very soon, obviously this will have an inflationary effect on top of our inflation spiral that we are currently in. If this war between Ukraine and Russia doesn’t end soon, we’re going to have a recession. So I’m also hoping that this conflict ends within the next two weeks…our Country’s fate hangs in the balance… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:06:37 </td>
   <td style="text-align:left;"> $MULN $SPY $QQQ EV is the next pump sector. Biden administration is already pushing it. We all know it’s BS but the pump is coming either way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:05:19 </td>
   <td style="text-align:left;"> $AMC $QQQ $TSLA   $1800 into $40k in the last 30 days.. If you really want to make huge profits on trading then, Join this winning chat:.   fundamental.stockmarketmovers.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:05:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Biden trolling the earth vainly looking for someone to sell him oil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:01:28 </td>
   <td style="text-align:left;"> $SPY $QQQ Thank you Joe Biden. Lmfao 🤣 https://youtu.be/nWEl4rUwDt0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:01:03 </td>
   <td style="text-align:left;"> $QQQ $SPY honestly not any one of us knows which way this goes tommorow we all just hope it goes the way we bet and gambled on 🙈🤦‍♂️🤷‍♂️🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 10:00:29 </td>
   <td style="text-align:left;"> $QQQ rumour is the futes traders in Chicago just ran out of cocaine, parties over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:58:15 </td>
   <td style="text-align:left;"> $SPY  $QQQ  if u gonna bring the gas up  . bring up the mileage reimbursement for work purposes and half of ur problem is solved Joe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:57:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK

Looks like I’m having Wagyu tomorrow!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:57:41 </td>
   <td style="text-align:left;"> $QQQ 
💸😤
Another day in the books. Easy money to be made if you have the right guidance. 📚📌📈

Check twitter for free option plays 💰🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:57:24 </td>
   <td style="text-align:left;"> $QQQ gonna burn all week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:56:43 </td>
   <td style="text-align:left;"> $QQQ - Deja-vu…..
Sell the rip! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:55:14 </td>
   <td style="text-align:left;"> $QQQ Man, seems to bullish in here and that is never a good sign. I hope market turns around, but it will take incredible news. Sold puts yesterday, sold calls today and bought 2 puts but prepared for a mini pump. I just can’t find anything bullish at all at the moment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:55:07 </td>
   <td style="text-align:left;"> $SPY $QQQ wgen it’s all said and done I believe Biden will go down as the worse president in American history. If you clowns re elect him again get ready for $20 gas… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:53:22 </td>
   <td style="text-align:left;"> $SPY $QQQ 

instead of watching the futes I am proposing a cancellation of California.

This may seem odd, right? San Diego is there and that place is great. Sadly, this state is basically like a monopoly in population and area. I can’t imagine the logistical balloon needed to maintain that. We have broken AT&amp;amp;T up before so let’s just do it to a state and get it overwith. I know some people that may enjoy an electoral college boost as a result 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:53:09 </td>
   <td style="text-align:left;"> $SPY $QQQ Futes holdin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:52:08 </td>
   <td style="text-align:left;"> $SPY  $QQQ  BUY AMERICAN STOCKS 🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:51:24 </td>
   <td style="text-align:left;"> $QQQ still don’t understand why people are pumping. Tech has tripled since COVID. Time to exit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:50:31 </td>
   <td style="text-align:left;"> $QQQ same crap smaller time frame. Not saying TA matters but it worked in the 380s when the first H&amp;amp;S was forming then again here on the 4hr 1 week ago. Bounce soon but target still is 290s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:50:19 </td>
   <td style="text-align:left;"> $QQQ when you taste blood as a short the first time 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:49:52 </td>
   <td style="text-align:left;"> $QQQ futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:47:57 </td>
   <td style="text-align:left;"> $SPY $QQQ they must have signed a new peace deal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:47:14 </td>
   <td style="text-align:left;"> $SPY $QQQ green futures makes me even more confident for a red day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:46:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Wow, I was gonna post a futes rippin’ meme but it’s too much work to scroll that far back on my camera roll. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:46:00 </td>
   <td style="text-align:left;"> $SPY $QQQ We just made Russia the healthiest people on the planet. No McDonalds, Starbucks, Coke, or Netflix. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:45:56 </td>
   <td style="text-align:left;"> $SPY $QQQ lol gas Pt of $5 about to hit this month. On pace for $10. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:44:59 </td>
   <td style="text-align:left;"> $QQQ 310 intraday day low Thursday
Friday close between 310-312
Best charting program ever 🎱🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:43:15 </td>
   <td style="text-align:left;"> $SPY $qqq there will be a massive pump once Kiev surrenders and comedian runs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:42:31 </td>
   <td style="text-align:left;"> $QQQ so who’s selling after a 3 month dump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:40:39 </td>
   <td style="text-align:left;"> $KTB $SPY $QQQ CNN report showing protesters getting arrested in Moscow. Look what’s selling in the background…. “Wrangler” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:40:37 </td>
   <td style="text-align:left;"> $QQQ forget gold, buy lithium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:40:29 </td>
   <td style="text-align:left;"> Powell says gas prices transitory, drive these models until we use our “tools”
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:38:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Mms literally want a Green Day to start the day tomorrow because of cpi on Thursday lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:37:05 </td>
   <td style="text-align:left;"> $QQQ wake me up when it gets close to the trend line. I&amp;#39;ll load up puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:36:48 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $QQQ 

Massive drop in amazon an google as both are dwindling …. Haven’t ordered froM amazon in years, and don’t really use google anymore …. I rather use Duck duck go, (free download link attached) and it  protect your data . Always protect. . Your data is everything Amazon should be below 1500 and so should google that’s where they’re worth it here they will get clobbered lower …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:34:56 </td>
   <td style="text-align:left;"> $SPY $QQQ Tomorrow we may see a little bit of a relief rally. Great opportunity to load up on puts👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:34:50 </td>
   <td style="text-align:left;"> $qqq buy low sell high n make moar then 15% bahhhhh day.   Prorate that???  Fookin 🧠.    🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:34:21 </td>
   <td style="text-align:left;"> $SPY $QQQ lol how long they gonna fake this pump for off of surging oils prices and inflation even more after todays sanction?😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:34:04 </td>
   <td style="text-align:left;"> $TMC Nickel shortage, which has only started, is going to linger for many years because of EV transition. Land Miners need 10-15 years to put a new mine into production. Buy and hold TMC for long term while you hear news about nickel shortage and you will get rewarded handsomely. I have set my sell limit to $100 target because TMC has the largest nickel reserves on the planet. $DJIA $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:33:49 </td>
   <td style="text-align:left;"> What did I tell you … FUTURES GO NUTZ  
 
this market is like purebred horses just ITCHING for that gate to go down give it any excuse to rip beers faces off oh my …. 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:33:35 </td>
   <td style="text-align:left;"> $QQQ good wednesday and another dump by weekend 📈🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:32:55 </td>
   <td style="text-align:left;"> $QQQ Like pulling teeth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:29:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $RIVN $NIO flush it before CPI Thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:26:43 </td>
   <td style="text-align:left;"> $QQQ morning scalp to 330$ in play…. Again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:25:29 </td>
   <td style="text-align:left;"> I was going to go to California for some little Vacations and rent a nice convertible V8 to have fun-- but seems like I&amp;#39;ll stay home, thanks Putin $XLE $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:24:28 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/QVTuQjJMxsM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:23:31 </td>
   <td style="text-align:left;"> $QQQ : got’em by the balls ⚽️… that’s an appropriate expression here .. Brandon and his “no where to be found” VP are running out of the ideas soon .. it’s like CPI gonna be 12% soon $TNX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:21:45 </td>
   <td style="text-align:left;"> $QQQ monster bull candle coming here this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:21:41 </td>
   <td style="text-align:left;"> New Analysis: Why smart money was buying Tuesday&amp;#39;s midday rally: https://cracked.market/2022/03/why-smart-money-was-buying-tuesdays-midday-rally/ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:20:02 </td>
   <td style="text-align:left;"> $SPY  $QQQ   $DIA   

Hey Bear’s Show Putin Your Strength 

Come on the markets closed. Do Show Us </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:20:02 </td>
   <td style="text-align:left;"> $SPY $QQQ  for only 200kbarrels per day you want to find an excuse to hike upthe price that much ? Shame on you just because we can pay doesnt mean you make us pay bitches </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:19:28 </td>
   <td style="text-align:left;"> $QQQ Nasdaq due for a decent bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:19:24 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;m bullish for tomorrow due to a few indicators but it won&amp;#39;t last. Bottom isn&amp;#39;t in yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:18:41 </td>
   <td style="text-align:left;"> $XRT uh oh guys, I know a few things about retail but people are sure to shit on me for that I am sure of it $Spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:17:43 </td>
   <td style="text-align:left;"> $QQQ   The idiot&amp;#39;s commander in chief.  God help us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:16:57 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $DJIA $QQQ --- 
 
LOL ---  this sums up the status of America under Biden  
 
https://www.wsj.com/articles/saudi-emirati-leaders-decline-calls-with-biden-during-ukraine-crisis-11646779430 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:15:42 </td>
   <td style="text-align:left;"> $QQQ the commie bears are lying to you. They want you to be miserable with them in their dystopian society. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:14:05 </td>
   <td style="text-align:left;"> $QQQ $SPY Look at your chart this way and buy puts instead of calls. You make gains right away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:13:09 </td>
   <td style="text-align:left;"> $NASDAQ $SPY $DJIA $QQQ $RUT 

SO glad I executed on this. Took the time to position in myself in bearish plays &amp;amp; commodities. Patience, discipline, strategy, execution, timing, conviction, quality.. 😉

Bearish bull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:11:27 </td>
   <td style="text-align:left;"> Markets want to gap up sooooo bad. They are like a bull in his cage just before it opens.  We got a taste of what happens on the smallest positive news today… are you ready?! 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:10:47 </td>
   <td style="text-align:left;"> $qqq     https://twitter.com/richardmoglen/status/1501302668047773701?s=21

🧠👀🐑👀🍿👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:08:57 </td>
   <td style="text-align:left;"> $QQQ $SPY market wants to bounce, badly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:07:49 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ All those 3/9 calls they made you chase immediately after Biden essentially announced that gas will go through the roof are going to expire worthless tomorrow. The most obvious bull trap of all time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:07:36 </td>
   <td style="text-align:left;"> $QQQ bro!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:07:21 </td>
   <td style="text-align:left;"> $QQQ $SPY wow DoD kawk blocked the MiG29 deal. No jets for  🇺🇦 

https://www.defense.gov/News/Releases/Release/Article/2960180/statement-by-pentagon-press-secretary-john-f-kirby-on-security-assistance-to-uk/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:06:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Y&amp;#39;all can thank Far Left liberals for the Washington Commanders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:05:29 </td>
   <td style="text-align:left;"> $QQQ Ukraine why would you when Russia is so huge...the amount of soliders...one can imagine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:04:36 </td>
   <td style="text-align:left;"> Literally how it feels buying the dip on any stock. 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:02:48 </td>
   <td style="text-align:left;"> $SPY $QQQ CPI this Thursday, if it shows a lower than expected number to show inflation is possibly easing  in the coming months excluding gas then we might have a big rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 09:00:33 </td>
   <td style="text-align:left;"> FUTES RARE RIPPING $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:55:39 </td>
   <td style="text-align:left;"> We could get a rare Green Day tomorrow - don’t forget CPI Thursday $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:54:40 </td>
   <td style="text-align:left;"> $SPY  $QQQ  a comedian who is few weeks and thousands of deaths late </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:54:08 </td>
   <td style="text-align:left;"> $SPY $SQQQ $QQQ The Roth 401k I’m currently trading in (it’s a minor account NOT my actual retirement) restricts you to a cash account with the arbitrary t+2 settlement. I don’t understand how these rules are supposed to protect you, they end up making you less nimble it times of extreme market volatility. I’m basically locked in on the TQQQ positionI switched to from SQQQ today until Thursday or I get a free riding violation. I have a stop loss anyway in case shit hits the fan but it would have been nice to exit when I decide instead of when the fed thinks I should. If I get that violation I’m forced to wait 2 days between every trade for the life of that account if I’m going all in, which I am because it’s a minor account. Anyone know why that rule even exists? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:52:24 </td>
   <td style="text-align:left;"> $SPY $USO $QQQ Interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:52:15 </td>
   <td style="text-align:left;"> SweepCast alerted: $QQQ with Unusual Options Activity Alerted on $326 PUT Expiring: 03-09-2022 worth 38K🐻  Learn Unusual Flow SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:51:29 </td>
   <td style="text-align:left;"> $QQQ $SPY When is CPI data out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:49:30 </td>
   <td style="text-align:left;"> $QQQ $NQ_F above 13,600 is Bullish 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:46:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 80374800. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:44:48 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

Do not be part of the resistance group

Because you will lose.    $4800    🧞‍♂️🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:44:14 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
https://www.cnbc.com/2022/03/08/sheryl-sandberg-on-russia-ukraine-women-led-countries-wouldnt-go-to-war.html?utm_term=Autofeed&amp;amp;utm_medium=Social&amp;amp;utm_content=Main&amp;amp;utm_source=Twitter#Echobox=1646760341 
 
She might be right, women tend to be more peaceful and don&amp;#39;t use violence as often. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:42:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:41:59 </td>
   <td style="text-align:left;"> $SPY $QQQ I am ready to boycott any brand that is no shutting down their businesses in Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:39:42 </td>
   <td style="text-align:left;"> The bastards have stolen 29 billion dollars worth of planes at least……Owners Outfoxed as Russia Absconds With $10 Billion of Jets $spy $brkb $qqq https://www.bloomberg.com/news/articles/2022-03-08/owners-outfoxed-as-russia-absconds-with-10-billion-of-jets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:37:52 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures looking good early on, let&amp;#39;s see if we will finally get the oversold bounce tomorrow. There is no doubt that this market is getting extremely oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:37:51 </td>
   <td style="text-align:left;"> $ABML battery metal, folks. This is sooo undervalued. The najarians have been all in on this. ABTC projects $31 pt. Do some DD on this. You won’t regret it. $SPY $QQQ $TSLA $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:35:39 </td>
   <td style="text-align:left;"> $BB $SPY $QQQ Well thats ironic

https://www.newsweek.com/russia-ukraine-kyiv-convoy-putin-1685806 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:32:47 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM yesterday was panic day...this is a good time to look for a buy (wait for a turnaround).  My analysis signaled longs on 12/7, 12/21, 1/25, 2/25 (might have one later this week).  With trading (long or short), momentum/continuation is needed.  Last 3 months, little to no continuation on the long side...-&amp;gt;&amp;gt;&amp;gt; stop loss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:32:23 </td>
   <td style="text-align:left;"> $SPY $qqq so USA doesn’t want to deliver those fighter jets to Ukraine from Poland. wonder how Tmp the deal maker  would have reacted if he was pres? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:30:33 </td>
   <td style="text-align:left;"> $QQQ what a time to be alive lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:29:55 </td>
   <td style="text-align:left;"> So last week gas was $2.40s today it cost me $5.09 /gallon.. Great job Biden voters. HIGHEST gas prices in US history. Affects us all $QQQ $SPY $HUSA latex3799249560079cdf8ff76dc0e96b1af1tsla ripping 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:29:31 </td>
   <td style="text-align:left;"> $QQQ $NDX is likely going to 13800 at least before any other major selloff; probably even higher if the specter of USA-Russia war goes away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:29:06 </td>
   <td style="text-align:left;"> $QQQ $spy
We will pump and I will have bear steak 🥩 with shredded puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:28:20 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ only down 69% now YTD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:28:03 </td>
   <td style="text-align:left;"> $QQQ $DJIA $SPY 
Billionaire Ray Dalio called the stock market crash of 2008 when everyone was in euphoria. He thinks the next US election neither side will concede to a lost no matter the voting results giving way to a civil war. I hoped he was wrong in 2008 and hope he is wrong now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:27:10 </td>
   <td style="text-align:left;"> $QQQ are we going enter into recession? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:27:02 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:26:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM everything topped out and pulled in today @ 1:10 pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:24:57 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Hear me out I’m longer term bearish…but I bought 417c expiring tomorrow AH today because I think they’re gonna run it up into CPI data on Thursday. VIX being at 35, without a massive shock, the tendency is going to be for VOL to sell off into Thursday IMO.

We’ll see if I’m right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:23:46 </td>
   <td style="text-align:left;"> $spy $qqq futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:23:09 </td>
   <td style="text-align:left;"> $SPY $QQQ futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:22:09 </td>
   <td style="text-align:left;"> BMBL Provides More Evidence For My Bifurcated Market Thesis $SNAP $ARKK $BMBL Also $QQQ $FB https://talkmarkets.com/content/stocks--equities/bmbl-provides-more-evidence-for-my-bifurcated-market-thesis?post=347267 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:21:30 </td>
   <td style="text-align:left;"> $QQQ $SPY Russia banning exports for the year... Good set up for $PLM these EVs need their Nickel
https://www.theglobeandmail.com/business/article-nickel-prices-leap-to-a-record-over-global-supply-fears-and-short/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:21:22 </td>
   <td style="text-align:left;"> $QQQ  $SPY  TIME TO BUY AMERICAN STOCKS 🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:21:17 </td>
   <td style="text-align:left;"> $QQQ double bottom on 321-323… could see a bounce.  Still on sidelines.  Let’s see what tomorrow brings hmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:19:09 </td>
   <td style="text-align:left;"> I’m assuming futes are trying to see if oil has topped out at 130. This is the first time I’ve seen futes green while oil was up at the same time. If oil topped out here I believe tech stocks may have an ok rest of week 
$SPY $QQQ 
$AMD I’m looking to see if this will retrace back below 105 or go above next level of 109 which was rejected today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:17:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLE 

We have become a laughingstock. 🤦

WSJ: Saudi, Emirati Leaders Decline Calls With Biden During Ukraine Crisis 

https://www.wsj.com/articles/saudi-emirati-leaders-decline-calls-with-biden-during-ukraine-crisis-11646779430 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:16:39 </td>
   <td style="text-align:left;"> $QQQ what happened to futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:16:33 </td>
   <td style="text-align:left;"> $SPY $QQQ As the great Matthew McConaughey had once said, &amp;quot;Number one rule of Wall Street, nobody, I don&amp;#39;t care if you&amp;#39;re Warren Buffet or if you&amp;#39;re Jimmy Buffet, nobody knows if the stock is going to go up, down sideways, or in fucking circles, at least to all stock brokers, it&amp;#39;s all a fugazi... We dont create shit, we don&amp;#39;t build anything... all we care about is getting. fucking. rich.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:16:26 </td>
   <td style="text-align:left;"> $QQQ FUTES FUCKING RIPPINNNNNNN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:15:29 </td>
   <td style="text-align:left;"> $QQQ $SPY CAREER IDEA ALERT! We are going to trade the tape well, with ease in fact because that is what we do and it’s good. After we get tired of that and want to level up we will reach out to $WEN and $TWTR. They would be stupid to not recognize this opportunity. Maybe $MCD is ready for that game too who knows what their risk tolerance may be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:14:21 </td>
   <td style="text-align:left;"> $TSLA not gonna lie 😅 I held my puts overnight and I missed this inverted hammer on $SPY daily. We all make mistakes, luckily I held this position and is relatively small compared to the gains we’ve made the past 3 days. Let’s see how it plays out 🤞🏻 on the fence. $QQQ daily looks more like gravestone doji </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:12:07 </td>
   <td style="text-align:left;"> $QQQ https://zolmax.com/investing/rfg-holdings-inc-makes-new-429000-investment-in-invesco-qqq-trust-nasdaqqqq/6918775.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:11:38 </td>
   <td style="text-align:left;"> $QQQ https://seekingalpha.com/article/4493743-invesco-qqq-etf-nasdaq-declines-far-from-over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:11:31 </td>
   <td style="text-align:left;"> $SPY $XLE $QQQ 

Let me see if I understand...

The US is banning the importation of Russian oil...

...with the idea that importing more oil from nations that better respect human rights like Venezuela and possibly Iran is the way to set a good example. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:09:40 </td>
   <td style="text-align:left;"> $QQQ free money!!!

Biden to request $2.6B to promote gender equity worldwide https://thehill.com/homenews/administration/597293-biden-to-request-26b-to-promote-gender-equity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:08:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 
 
Technical analysis for tomorrow. 
 
https://youtu.be/P2nNa7CCQ3w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:06:57 </td>
   <td style="text-align:left;"> $SPY $QQQ In a long run, oil companies are still pretty poor long term investments since the world is quickly moving to the renewables. Trade the oil stocks don&amp;#39;t invest in them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:06:22 </td>
   <td style="text-align:left;"> $QQQ $SPY OMG now Russia is responsible for gas prices &amp;amp; inflation? 😸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:03:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DJIA 
 
***BREAKING: Saudi and UAE leaders declined to have a call with Biden regarding Ukraine and the spike in oil prices. 
 
Russia has them in their pocket. Clearly the Saudis want Joe gone... 
 
Not to long ago: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:03:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLE 

He walks on...
doesn&amp;#39;t look back...
He pretends he can&amp;#39;t hear her...
Starts to whistle as he crosses the street...
Seems embarrassed to be there...

Oh...Think twice
&amp;#39;Cause it&amp;#39;s another day for you and me in paradise... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:02:22 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-08 Trade Analysis Video: 
https://www.youtube.com/watch?v=g7V36QHPHsI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:02:11 </td>
   <td style="text-align:left;"> Stocks Drop On March 8 As Liquidity Thins Out https://mottcapitalmanagement.com/stocks-drop-on-march-8-as-liquidity-thins-out/ $shop $pypl $fdx $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:01:51 </td>
   <td style="text-align:left;"> $QQQ final washout coming into March opex? Or do we have months/years of pain coming? I’m already adding to my long term favorite sectors and names, plus scaling into short puts on $SPY. Lots of cash on the sidelines but still taking it on the chin. Down big in Cathie turds $ARKW $SPOT $ARKK which should have been cut long ago (last spring). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 08:00:30 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Finally… some selling exhaustion? 

Or mere pause before another dumping on Thursday-Friday? 

I think up tomorrow then down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:59:16 </td>
   <td style="text-align:left;"> $SPY $QQQ  Russia the bad guy they said </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:57:14 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Brandon still planning to use taxpayer money to buy weak-minded votes lost at the gas pump. 
 
Just in time for mid-term elections! 
 
Go Brandon!!! 
 
 
 
https://www.cnbc.com/2022/03/04/white-house-may-delay-student-loan-payments-as-it-weighs-debt-forgiveness.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:57:05 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F     💲🧞‍♂️💲.  $QQQ $DIA 

I heard that the S&amp;amp;P in the next 11 days will be $4600 - $4800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:53:26 </td>
   <td style="text-align:left;"> $QQQ $SPY  Japan Q4 GDP growth 4.6% vs est 5.6% 🤣🤣🤣
Print trillions out of the thin air to artificially prop up everything: boom &amp;amp; bust scheme 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:53:14 </td>
   <td style="text-align:left;"> $QQQ when QQQ ads show up on TV, it’s hint hint SELL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:53:01 </td>
   <td style="text-align:left;"> $QQQ Option Alert.. Massive VOLUME 👀 👀  $320 Put for Wednesday, March 9. Roughly 8 Million dollars! 💰💰 WOAH 💰💰 Learn more on StockOrbit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:52:59 </td>
   <td style="text-align:left;"> $QQQ Option Alert.. Massive VOLUME 👀 👀  $330 Call for Wednesday, March 9. Roughly 2 Million dollars! 💰💰💰💰 Learn more on StockOrbit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:52:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $USO $CDEV #JerseyBoy 
 
Must have got caught in a rip and tried to swim against it.  
Tourists need to learn before entering the water. #Hawaii 
 
https://www.msn.com/en-us/news/us/new-jersey-man-missing-after-being-swept-out-to-sea-in-hawaii/ar-AAUN6U3?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:51:42 </td>
   <td style="text-align:left;"> $SPY $QQQ You know if CNBC has a red banner BREAKING headline stating that &amp;quot;futures are flat due to traders trying to digest the rising commodity prices and ban on russian oil&amp;quot;, we are in for a volatile ride. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:51:38 </td>
   <td style="text-align:left;"> $QQQ would you enter a long here or go short? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:51:16 </td>
   <td style="text-align:left;"> $ENSV  2K profit on a $200 stop. 10X!! ENTRY 1.20 exit 7.28 $AA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:50:16 </td>
   <td style="text-align:left;"> $QQQ $SPY Green tommorow because it can&amp;#39;t go lower again lol 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:49:53 </td>
   <td style="text-align:left;"> $SPY $QQQ ngl I thought crude oil would be $180/barrel after Biden banning Russian oil. I guess the US has more stock than the public realizes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:48:35 </td>
   <td style="text-align:left;"> $SPY $qqq    😆
 $LMT $DIA $BTC.x.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:48:15 </td>
   <td style="text-align:left;"> buy high sell low is my new strategy https://www.billionaireclubcollc.com/buy-high-sell-low-is-my-new-strategy/ $SPY $DJIA $QQQ $VIX $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:47:22 </td>
   <td style="text-align:left;"> $QQQ im down with some inflation from supply chains…but the war and expensive gas made me hedge for the first time in my life $QQQ $PSQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:47:03 </td>
   <td style="text-align:left;"> $MARPS $CEI  $QQQ $ICD. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:46:37 </td>
   <td style="text-align:left;"> $NASDAQ $QQQ 

WOW. That momentum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:46:10 </td>
   <td style="text-align:left;"> $QQQ too many bears. We green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:44:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $CVX I remember this article a couple years back.  😵‍💫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:43:38 </td>
   <td style="text-align:left;"> $SPY  The Bears Who Cried “Wolf”

    $nasdaq $NDX $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:42:13 </td>
   <td style="text-align:left;"> $SPY $QQQ stock market knockout soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:39:50 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:39:36 </td>
   <td style="text-align:left;"> $SPY everyone is a chartist now $IWM $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:38:29 </td>
   <td style="text-align:left;"> $QQQ 265 tomorrow. Russia bad. The US prefers oil from a transgender african american jungle country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:38:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Round 3. Portfolio down from 63k to 30k. Down 45% YTD. Hoping we hit the bottom today or this month. Everyone else doing well? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:37:51 </td>
   <td style="text-align:left;"> $AAPL WTF ...Nicolas MurdurO.. # 1🤡Potatoe Joe is seeking oil from Venezuela ,spread the BAD NEWS..$SPY $QQQ.  BEAR BYDEN STRIKES AGAIN!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:35:38 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA I like how everyone is quiet about this… inflation around the world is here to stay 

https://seekingalpha.com/news/3810771-putin-signs-decree-to-restrict-imports-and-exports-until-year-end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:35:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Bears are in for an awakening when Russia calls off the invasion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:35:19 </td>
   <td style="text-align:left;"> $SPY $QQQ Y’all remember this? The good times. I could fill up for below $20. 2020 wasn’t all bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:35:10 </td>
   <td style="text-align:left;"> $UVXY $SPY $SQQQ $QQQ anyone know where to find historical option data? Looking for multiple sources. Ty In advance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:34:17 </td>
   <td style="text-align:left;"> $ROKU  $SPY $QQQ knockout for retailers soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:34:01 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:34:00 </td>
   <td style="text-align:left;"> $SPY $QQQ no jets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:32:39 </td>
   <td style="text-align:left;"> Whoa they came for everyone tonight.... 😳 

$spy $spx $TSLA $nvda $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:32:02 </td>
   <td style="text-align:left;"> $SPY $QQQ Putin put a date on it. Until December 31st no exports from Russia… inflation is here to stay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:31:31 </td>
   <td style="text-align:left;"> $DIA Of the 4 broader averages, the only one so far to have come back inside what I consider trend is $QQQ At some point it will shake off all the Fed pumping, but it still has a ways to go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:31:25 </td>
   <td style="text-align:left;"> $QQQ that’s it? Dump over? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:30:34 </td>
   <td style="text-align:left;"> Last Month CPI for January 2022 came in super hot 🔥 7.5% inflation from 40 years ago. The consumer price index gained 0.6% last month after increasing 0.6% in December, the Labor Department said on Thursday. In the 12 months through January, the CPI jumped 7.5%, the biggest year-on-year increase since February 1982.
Bad businesses. If Inflation remains elevated!
Bad for the Market goes lower. 
$QQQ $AAPL $SPY $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:30:33 </td>
   <td style="text-align:left;"> $QQQ 
Top reasoning for buying overpriced put options……
Biden, who could fuck up a wet dream, no pun intended. Obama can confirm.

Putin - Living in the past, except has more money then ever thanks to Biden

Powell - Knows he has to crush bulls by initiating massive rate hikes and  dumping bonds, notes and equities that he and other fed governors already dumped 🤣

Our VP is worth her weight in Shi…….T

Nancy Pelosi wets herself …….. Hourly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:30:00 </td>
   <td style="text-align:left;"> $SPY    $480      Don’t try fight 

Don’t fight that  $SPX $ES_F $QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:28:52 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ  Tell me one time in history it was a bad decision to buy when the vix was 35 + </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:27:45 </td>
   <td style="text-align:left;"> $spy $qqq $dia $rsx $lukoy
https://consortiumnews.com/2022/03/04/how-zelensky-made-peace-with-neo-nazis/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:26:20 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA the keystone pipeline is and has been fully operational. The XL stood for “export limited.” It was just an idea to run a shortcut across land with the existing, operating line. It was done away with by the Supreme Court on Jan 18, 2020, almost a year before the election, when they upheld a lower courts ruling blocking the environmental permitting needed It was a development proposed by TransCanada, to transport Canadian oil from Alberta south through a larger diameter pipe through Nebraska on south to port where Canada was going to sell its oil to Asian markets. All Biden did was lift the land permits once TC abandoned the project, as the Supreme Court left them no choice. The project was already dead no matter who was elected in 2020. Also, as it was for the sale of Canadian commodities to Asia, it would not have meant more supply or lower cost to any American at the pump. Tucker Carlson and Sean Hannity have been lying to you if you think it would have mattered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:26:15 </td>
   <td style="text-align:left;"> $QQQ Futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:26:12 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA 
https://www.forbes.com/sites/hanktucker/2022/03/01/these-15-stocks-and-10-funds-are-overexposed-to-russia-and-ukraine/?sh=79296b0c6e1f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:24:37 </td>
   <td style="text-align:left;"> PENTAGON SPOKESMAN SAYS FIGHTER JETS OFFERED BY POLAND &amp;quot;RAISES SERIOUS CONCERNS FOR THE ENTIRE NATO ALLIANCE&amp;quot;

Russia already gave them a Warning $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:24:33 </td>
   <td style="text-align:left;"> $TMC congrats to those who bought! TMC has the worlds largest nickel reserves worth $335B. It has more room to run IMO. $QQQ $IWM $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:23:04 </td>
   <td style="text-align:left;"> $SPY $QQQ her friend gonna eat her friend
Tell her friend to save me some 😋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:22:11 </td>
   <td style="text-align:left;"> $AMTX Nasdaq $AMTX is going to the moon. They are a gas and natural gas renewable replacement company with same renewable input cost and much higher selling price now that oil is 🚀🚀Stock analyst had the buy @ 33/share before the oil spike, this thing could be $66/share by tomorrow. Current share price is up 42% this month and 22% today  @15/share. This is going to the moon. Autist strap on your boots we going to the moon.🚀🚀🚀🌘🌖🌗🌕
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:22:09 </td>
   <td style="text-align:left;"> $QQQ if you told me we would open at 324 and spike all the way up to 333 and crash down to end the day at 323.. I would have said &amp;quot;so just another typical day in this crazy market of ours.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:21:42 </td>
   <td style="text-align:left;"> $SPY Bounce or empty the cup?... 
 
$QQQ  $IWM  $AMRN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:19:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA still confused on why the market would go up and the cost of oil down on news of banning Imports of Russian oil😂☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:18:36 </td>
   <td style="text-align:left;"> $QQQ staying out of this for tomorrow, even in a bear market going for 5 red days in a row is risky </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:18:23 </td>
   <td style="text-align:left;"> $UWMC $BTC.X $QQQ $SPY  
 
&amp;quot;A threat to liberty anywhere, is a threat to liberty everywhere.&amp;quot; 
 
&amp;quot;The only thing evil men need to succeed is for good men to stand by and do nothing&amp;quot;  
 
These are axioms that we hold dear as Americans, that is, until it affects gas prices. Then its every man for himself, apparently. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:17:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Bumblin’ Biden is imploding right before our very eyes! His announcement of banning Russian oil combined with his own ban on drilling here at home promises to sink his presidency once and for all. In this video we’ll look at the inevitable costs that are going to skyrocket from this ban on Russia, we’re going to see how Biden is running out of options, and stick with me to the very end of this video when I’ll show you why Russia may end up relatively unscathed by all those, which promises to sink Biden even further; you are not going to want to miss this! https://youtu.be/iO__pWk6OjU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:17:21 </td>
   <td style="text-align:left;"> $EXPR $MYO $QQQ $CRWD $ZIM  
Most Anticipated Earnings Tomorrow 
https://www.financegreater.com/earningscalendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:16:46 </td>
   <td style="text-align:left;"> Caught $QQQ long off 4 Hour Demand (Green) today at 320.89. Bounced over 13 points or 4% right to 4 Hour Supply (Green) at 333.00 and then dropped 11 points of another 4%. Perfect!  
 
Optionsforecast4u.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:16:36 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.usnews.com/news/economy/articles/2022-02-24/gross-domestic-product-rose-7-in-the-fourth-quarter 
 
Buying the dips here is an easy decision when the economy is doing so well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:15:07 </td>
   <td style="text-align:left;"> Biden drew more viewers in otherwise quiet TV week $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/biden-drew-more-viewers-in-otherwise-quiet-tv-week/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:15:03 </td>
   <td style="text-align:left;"> $QQQ call buyers talked so much shit to get crushed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:10:49 </td>
   <td style="text-align:left;"> $TMC has worlds largest known nickel reserves worth $335B. 🚀🚀

https://youtu.be/o1dsDaMw5x0

$SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:09:11 </td>
   <td style="text-align:left;"> $QQQ Monthly interest levels, almost touching the low of 316 of may 2021, it will be hit probably tomorrow. After that 297.45 seems to be next target of bears... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:09:10 </td>
   <td style="text-align:left;"> I’m glad we’re “respected” again $SPY $QQQ $DIA $SPX $NDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:07:39 </td>
   <td style="text-align:left;"> $QQQ so happy I held puts even through that insane pump and dump $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:05:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM We can do it! Lol 😂😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:05:24 </td>
   <td style="text-align:left;"> $QQQ bearish but futures often doesnt matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:04:47 </td>
   <td style="text-align:left;"> Worth noting the nasdaq composite is currently under the weekly 100sma. We haven&amp;#39;t closed under it since March 2020. How we close this week will be important. 
$COMPQ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:04:27 </td>
   <td style="text-align:left;"> $QQQ that&amp;#39;s two daily closes below LT channel. gotta respek the bears here. 2SD move around 315 so good odds at a bounce if you find the market down there this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:04:08 </td>
   <td style="text-align:left;"> $QQQ Can somebody please take Biden for a ride in their convertible down a nice scenic Main Street in a city in Texas🤣🤣🤣🤣💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:03:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $IWM 

Poland: OK they can have the jets, but you have to take them over there

US: but you’re right next door, I thought  you were going to take them over there?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:02:08 </td>
   <td style="text-align:left;"> $QQQ Short Squeeze tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:00:38 </td>
   <td style="text-align:left;"> $SPY $QQQ LFG!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:00:15 </td>
   <td style="text-align:left;"> $QQQ i really believe if we break 317… 299 will be here quick. IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 07:00:11 </td>
   <td style="text-align:left;"> $SPY $DOW $QQQ Ouch stinks for those holding rubles ... reminds me of Legend of Zelda! #Rubles #Russia #War #Currency </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:57:58 </td>
   <td style="text-align:left;"> The volatility of &amp;quot;everything&amp;quot; is spiking. 
 
$SPY $QQQ $VIX $GC_F $CL_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:57:37 </td>
   <td style="text-align:left;"> $QQQ so much manipulation in this market unbelievable and insane </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:55:23 </td>
   <td style="text-align:left;"> $AVCT $qqq big news ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:55:15 </td>
   <td style="text-align:left;"> $BAND If you think Russia is going to agree to anything, you lost your mind, they are going all in soon, and markets will definitely suffer. How many tech companies have lost 5-10% of total revenue bc they pulled out of Russia. This plus all time high inflation and rising rates is a terrible sign for stocks especially tech. $TWLO $QQQ $AAPL $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:54:22 </td>
   <td style="text-align:left;"> $SPY $QQQ Will we go lower then 411/318 or is this the bottom. 
Let&amp;#39;s find out in the upcoming days! Personally I don&amp;#39;t trust the market or the economy enough to go long a short term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:54:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 💀😂🐻🩸📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:54:05 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $DJIA $ERUS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:53:11 </td>
   <td style="text-align:left;"> $SPY $QQQ I moved away from following the $TNX intraday and now I&amp;#39;m tracking $USO . Note I follow the futures market not the ETFs. The breakdown in oil pushed the squeeze in equities and then the lack of follow through and further weakness in crude crushed the rally. These are not exact correlaries but they do weigh on price action and can help with forecasting direction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:52:04 </td>
   <td style="text-align:left;"> $SPY $QQQ If anyone likes good Techno https://www.youtube.com/watch?v=IK3Xb0hlDc8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:50:36 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 3/8/2022 $SPY $XLF $QQQ $TAN $TSLA https://www.chartguys.com/daily-market-videos/4188/trading-the-whipsaw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:50:36 </td>
   <td style="text-align:left;"> The annualized volatility or variation in price over the past year for $MULN is 183.88%, significantly more volatile than $QQQ at 19.83% and $SPY at 14.13%.  
 
One standard deviation or 68% of all daily moves in the past year fall within 11.58%. Three standard deviations or 99.7% of all daily moves fall within 34.74%. 
 
https://twentyontwenty.com/symbol/MULN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:49:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Oil can&amp;#39;t really go that much higher from here before demands begin to collapse in Europe and Asia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:47:36 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:47:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $BTC.X … 

What are 3 uses for nickel?

Nickel steel is used for armour plating. 

Other alloys of nickel are used in boat propeller shafts and turbine blades. 

Nickel is used in batteries, including rechargeable nickel-cadmium 

https://www.rsc.org/periodic-table/element/28/nickel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:45:54 </td>
   <td style="text-align:left;"> $QQQ If not hold, 318, 315 next then 285-290 area, then 260 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:45:43 </td>
   <td style="text-align:left;"> $QQQ first day it rejected the neckline. Could still see this chop back up as index head and shoulder patterns generally don&amp;#39;t trade clean. Momentum clearly down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:45:21 </td>
   <td style="text-align:left;"> $SPY $LMT $QQQ 

“Poland is ready to provide all their MIG-29 fighter jets to US airbase in Germany so the USA can provide them to Ukraine” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:45:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 80374800. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:44:42 </td>
   <td style="text-align:left;"> $SPY $QQQ    
 
https://www.cnn.com/2022/03/08/business/mcdonalds-pepsi-coke-russia/index.html 
 
While Putin is a very bad man but I kinda feel bad for those Russians who won&amp;#39;t get to enjoy Big Mac and coke anymore especially those who are against the war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:43:20 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ 

Anyone actually read the list? Holy sh**…glad I didn’t get it. 

They wanted it secret for 70 years apparently…thank you whoever filed that freedom of information request. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:41:48 </td>
   <td style="text-align:left;"> $SPY $QQQ QE never ended the Fed balance sheet is still going parabolic and the rate hike on CPLie 7.5% (really 15%) and rocketing higher is a 0.25-0.50% nothing burger. The US gov is in a debt and deficit trap. Everything else is jawboning.

The US dollar global reserve currency will be melted down this decade and this could be a signal of the true meltdown starting. We could be at the beginning of the greatest crack up boom in human history and I think the epicenter is the key global commodities that are vital to modern life itself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:41:38 </td>
   <td style="text-align:left;"> My latest blog, “BMBL Provides More Evidence For My Bifurcated Market Thesis”, is available:

https://www.topgunfp.com/bmbl-provides-more-evidence-for-my-bifurcated-market-thesis/

$BMBL $SNAP $QQQ $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:39:14 </td>
   <td style="text-align:left;"> $AAPL Who is the Retail Trader that Buys or Sells when CNBC Traders say something about a stock.  
 
Im sure there is an Algo as well but its always amazing to me watch that happen in the Tech ($qqq) space </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:39:05 </td>
   <td style="text-align:left;"> $WEAT $XLE Food, water, oil are necessities. A new iphone is not. $QQQ. Choose wisely. https://www.reuters.com/business/china-ensure-agricultural-product-supplies-including-grains-2022-03-05/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:38:49 </td>
   <td style="text-align:left;"> NASDAQ ($QQQ) Top Gainers during today $ABNB $MRVL $MCHP $LCID 
  
Learn more: https://www.finscreener.org/screener/top-gainers/stocks/nq100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:37:52 </td>
   <td style="text-align:left;"> $QQQ Priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:36:22 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Do we have another 10% from here or not? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:35:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $NASDAQ  🧞‍♂️ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:34:59 </td>
   <td style="text-align:left;"> I think we may see sub SP 4000 maybe touch 3900s… then reverse…. Writing here to time stamp it … lots of buyers at the 20% draw down .. 

🚨 $SPY $AAPL $TSLA $DIS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:33:46 </td>
   <td style="text-align:left;"> $SPY 🎯… not done yet though. ES will touch the monthly 20ma. 

$QQQ $ES_F $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:32:37 </td>
   <td style="text-align:left;"> $QQQ Double top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:32:00 </td>
   <td style="text-align:left;"> Don&amp;#39;t take my word for it. 
 
Go through the 100 names in the $QQQ and see how many charts are doing what $NFLX is doing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:31:59 </td>
   <td style="text-align:left;"> $QQQ Option Alert.. 👀 👀  $347 Call for Friday, March 11. Roughly 12 Thousand dollars! 💰💰 Learn more on StockOrbit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:31:39 </td>
   <td style="text-align:left;"> Some tech stocks.. literally falling like dot com bubble burst… hate to say it.. but if this is to repeat… they still got more to go…, i cut my losses on PYPL at $180 thinking that was the low… wow 🥵

🥵 $PYPL $QQQ $SHOP $ZM $DKNG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:31:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT $DOGE.X 

Wallstbets did more damage to inexperienced investors than anything I have ever seen.

They could have used their platform and following to actually educate investors, and teach them financial tools that they may not get elsewhere. 

Instead they yolo’d money into shitty stocks at ATH’s and watched that $ drain while screaming “to the moon” 

Knowing that hedge funds move markets, did they really expect the purchasing power of a few reddit users to outweigh hundreds of hedge funds pockets? It’s not possible. They knew this.

There is absolutely no way a group of users came together to pump up a stock for a company that’s been screwing people over on their trade ins, with a dying business model &amp;amp; drying up balance sheet. 

Something tells me a hedge fund was behind that forum and movement as a whole, by teaching people to yolo money and buy bad stocks they’ve created a whole new generation of inexperienced investors to profit on for life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:31:10 </td>
   <td style="text-align:left;"> $SPY $QQQ If Putin ends this war now then he can still save the Russian economy, otherwise it doesn&amp;#39;t benefit him much even if he gets Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:31:09 </td>
   <td style="text-align:left;"> $CRCT on watch for tomorrow👀 It&amp;#39;s amazing how many overvalued stocks there are in the market, and u don&amp;#39;t find out about them until earnings 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:31:04 </td>
   <td style="text-align:left;"> Alert on $SQQQ delivered today at 11:22AM CDT on 3/8/2022 🎯 

Server link in the bio for winning alerts and for those eager to learn. 
$TQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:28:58 </td>
   <td style="text-align:left;"> $QQQ obvious shorting manipulation the past month..covered shorts at lunch today..got back in office and continued their coordinated short attacks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:28:33 </td>
   <td style="text-align:left;"> $UPH $QQQ Just Relax, 6-8/sh is in the cards. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:26:04 </td>
   <td style="text-align:left;"> $QQQ duh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:24:45 </td>
   <td style="text-align:left;"> $QQQ if you know MAD and MAED we are at risk of MAED ATM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:24:30 </td>
   <td style="text-align:left;"> $QQQ lots to be bullish here, 

calling the bottom again,

it&amp;#39;s all priced in,

only up from here! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:23:59 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA    could this be planned,?🤔make people buy more electric cars. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-09 06:23:53 </td>
   <td style="text-align:left;"> $SPY $QQQ Who else is betting on food inflation. Oil and food price shock by summer as we head into midterms. https://m1.finance/h_ayzWceoYWp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:56:06 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $TQQQ $UVXY 
VIX Futures Dripping 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:55:38 </td>
   <td style="text-align:left;"> $AAPL   https://bleacherreport.com/articles/10029107-appletv-to-televise-friday-night-baseball-doubleheader-starting-in-2022-mlb-season </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:55:03 </td>
   <td style="text-align:left;"> $NIO $AAPL $MSFT $QQQ latexb2a82e7a92972937668408b9eb5561f1AMD ↗️

$AAPL  $INTC  $NVDA  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:39:37 </td>
   <td style="text-align:left;"> $SPY  $QQQ $AAPL 
Gas going much higher. Higher costs for all people and businesses. 👎  
Bad for Stock Market unfortunately.
7.00 in Las Angels Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:37:40 </td>
   <td style="text-align:left;"> $AAPL 4hr view from the 2/27 weekend update. Calling for a move lower towards another blue box area where buyers are expected to appear #elliottwave #trading #apple #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:37:12 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 2/20 weekend update presented to members at elliottwave-forecast.com called for a double correction lower to take place #elliottwave #trading #apple #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:33:36 </td>
   <td style="text-align:left;"> $AAPL $SPY 

Futures trying to breakout but green candles are quickly sold off quick.. Slight green for now.

It&amp;#39;s early morning in Moscow...so..more to come. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:32:11 </td>
   <td style="text-align:left;"> $AAPL we def need more buyers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:28:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Joe Biden likes to accuse Tyson Foods of price gouging, what about Big Oil companies? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:25:30 </td>
   <td style="text-align:left;"> $SPY $FB $AAPL  so McDonald&amp;#39;s, Facebook , coke gone from Russia . 10yr down the lane . Russian are healthy , intelligent, well informed generation. We america will left with freedom . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:25:07 </td>
   <td style="text-align:left;"> $NFLX $AAPL  tinyurl.com/bdftnjfz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:22:03 </td>
   <td style="text-align:left;"> $AAPL fast money goons phds says that apple has to go down for the market to bottom 
Crude lower VIX lower more important </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:17:04 </td>
   <td style="text-align:left;"> $AAPL Green to red move:  +2.25% to -0.94%  
 https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan&amp;amp;type=greentoredDaily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:13:16 </td>
   <td style="text-align:left;"> $AAPL In the recent reporting quarter: 6.83% of institutions made no changes to their position https://www.insider-analysis.com/search_whales.php?ticker=TABLE_AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:11:53 </td>
   <td style="text-align:left;"> $AAPL Dam was hoping apple would make a nice phone for poor folks since the country going broke under Biden. The SE3 is just an SE2 with 5G sucks. Apple could give back some but they remain greedy only this time people are really broke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:11:39 </td>
   <td style="text-align:left;"> $AAPL green iPhones LOOOL? Could’ve saved the event for just that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:10:53 </td>
   <td style="text-align:left;"> $AAPL news about the new iPhone with 5 cameras 180 tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:09:09 </td>
   <td style="text-align:left;"> $SPY looks like the Biden Administration did not prevent the big energy crisis $XLE $AAPL $QQQ inflation was much higher 7.5% last month January 2022 how much higher will inflation be going forward ? Probably a lot higher inflation is coming … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 10:08:02 </td>
   <td style="text-align:left;"> $AAPL 120s again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:58:01 </td>
   <td style="text-align:left;"> $AAPL has held up incredibly well but I doubt it can postpone the inevitable mean regression all year - looking at 100w in 130s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:53:23 </td>
   <td style="text-align:left;"> $MSFT $AAPL 
Massive error Microsoft made in purchasing Activision for 85 billion in cash! It’s a video game company!! It’s worth 25 B MAX!!! Microsoft payed more than triple what it’s worth…. Microsoft will be in purgatory an will get crushed lower as people stop playing video games. I haven’t played since high school!!! Turn off that Xbox an do something else ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:53:00 </td>
   <td style="text-align:left;"> $AAPL …. $395 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:45:43 </td>
   <td style="text-align:left;"> $AAPL 165 starting the day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:40:53 </td>
   <td style="text-align:left;"> $AAPL looking for 158.41 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:37:16 </td>
   <td style="text-align:left;"> $AAPL Apple’s new iPhone SE is nearly $250 cheaper than the original iPhone when adjusted for inflation

https://www.cnbc.com/2022/03/08/apples-429-iphone-se-is-one-of-its-cheapest-phones-ever.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:33:34 </td>
   <td style="text-align:left;"> latexe78b1358bf7795fc5a5691fd415d1280AMD DIS 
 
The List: 
$AAPL $TSLA MSFT $NVDA FB  PYPL  AMZN 
 
 
$NIO continues to have a dedicated fanbase.  
 
 
Did you trade any of these stocks? 
 
More 👉 https://bit.ly/3pEk3Xl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:32:22 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-08 Options Analysis Video: 
https://www.youtube.com/watch?v=sugEHSx3N34 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:31:01 </td>
   <td style="text-align:left;"> $AAPL - Apple UltraFusion allows two M1 Max processors to work together, resulting in 20 CPU cores, 64 GPU cores and support for up to 128GB of RAM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:30:52 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple unveils new iPhone SE, iPad Air, Mac Studio, M1 Ultra chip https://www.stck.pro/news/AAPL/24079914 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:26:37 </td>
   <td style="text-align:left;"> $AAPL 11-Mar-22 ATM Implied Vol Increases +0.9%. Straddle Implies a Move of ±3.2% https://tinyurl.com/yysafcy6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:25:13 </td>
   <td style="text-align:left;"> $XOM I am using my dividends payday to buy more XOM shares.  $300 per barrel in 2022!  $SPY $AAPL $TSLA $AMZN  
https://www.cnn.com/2022/03/08/business/oil-price-russia-warning/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:20:25 </td>
   <td style="text-align:left;"> $AAPL buy the dip - this is a good long-term hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:17:33 </td>
   <td style="text-align:left;"> $AAPL where do we think by may? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:12:27 </td>
   <td style="text-align:left;"> $AAPL Perigon Wealth Management, Llc increased their holdings by 3,747%, one of the largest institutional increases this quarter https://www.insider-analysis.com/search_whales.php?ticker=TABLE_AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:12:15 </td>
   <td style="text-align:left;"> SweepCast alerted: $AAPL with Unusual Options Activity Alerted on $162.5 PUT Expiring: 03-11-2022 worth 90K🐻  Learn Unusual Flow SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:10:48 </td>
   <td style="text-align:left;"> $AAPL $AMD $DIS  $BAC  tomorrow will be the fucking squeeze of the year.  DOW will add 800 points while NASDAQ will add 500 points. Another ceasefire in the making. The best day of the year! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:07:57 </td>
   <td style="text-align:left;"> $AAPL lets go to 140  fast
Then 125 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:05:43 </td>
   <td style="text-align:left;"> $AAPL sucks $BA well played, like old days $UVXY sucks $FCEL not bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:04:11 </td>
   <td style="text-align:left;"> $AAPL I don’t think enough rubles exist in circulation to buy one share of this. Is my math right on that? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:02:12 </td>
   <td style="text-align:left;"> $AAPL All the Trumptards crying for the return of their cult leader....this is a buying opportunity, scoop up some more shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:01:44 </td>
   <td style="text-align:left;"> $AAPL how is the most expensive penny stock ever created doing tonight? Just saw it on my iPhone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:00:46 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $157.5 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 09:00:04 </td>
   <td style="text-align:left;"> $AAPL $AMZN $GOOGL $MSFT these are some of the few that made it out of the tech bubble, now there’s a growth bubble which ones will survive? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:59:00 </td>
   <td style="text-align:left;"> $AAPL: The EPS has grown by an impressive 63.57% over the past year. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:56:10 </td>
   <td style="text-align:left;"> $SPY  $AAPL $MSFT $SOXL $TQQQ 
If we had Trump now... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:50:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Why Apple Stock Lagged the Market Today https://www.stck.pro/news/AAPL/24081644 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:42:33 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:37:59 </td>
   <td style="text-align:left;"> $AAPL 165 😊😊😊😊😊😊😊.  A day later . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:37:39 </td>
   <td style="text-align:left;"> $AAPL The OrangeManBad had the country energy independent.. Now eat your Biden azz soup ..$FB Whoooaaaa Somebody&amp;#39;s stop Me.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:36:34 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:34:32 </td>
   <td style="text-align:left;"> $DWAC

I thought you pussies were anti-mask 😂

$AAPL $BA $LMT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:27:40 </td>
   <td style="text-align:left;"> $AAPL All the FAANG stock are part of a BIG COLLECTIVE SELLOFF CABAL..the price swing are set by Jim Lamer CNBC..and Charles Puke Fox Business News.  $FB $GOOG $NFLX $AMZN ..LMAO 🤣 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:26:06 </td>
   <td style="text-align:left;"> $INTC They better up their divy and find a way to get investors excited because with $AAPL M1 Ultra their chips are just sad. Better performance than anything Intel has to offer and drawer of 65% less power, this company is in big trouble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:21:56 </td>
   <td style="text-align:left;"> $AAPL In the recent reporting quarter: 1,244 institutions increased their position, while 1,669 decreased https://www.insider-analysis.com/search_whales.php?ticker=TABLE_AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:21:10 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TSLA $AAPL the last few months price action explained by Michael Scott </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:19:48 </td>
   <td style="text-align:left;"> $AAPL 1600 dollars for a computer screen... They basically took a 4k monitor, added a few pixels, stamped an Apple logo onto it, and viola, new rip off that only the dumbest of the dumbest will pay for...  
 
99.9% of Americans don&amp;#39;t need a 1600 dollar &amp;quot;5k&amp;quot; display (and its only 27 inches at that!) when they can buy a cheap 300-400 dollar 4k ultra-wide monitor. 
 
Im obviously not bearish on Apple but that is just retarded and lazy... But I guess the question is, is it actually retarded if people are willing to pay that much for a logo and bragging rights (I wouldn&amp;#39;t brag about wasting 1600 dollars on a 400 dollar monitor but thats just me)? 
 
https://www.cnbc.com/2022/03/08/apple-event-live-updates.html#107027144-fYOjpo6oc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:10:47 </td>
   <td style="text-align:left;"> Apple announces iPhone SE and Mac Studio, AAPL stock remains bullish  $AAPL  
 
https://risingcandle.com/marketnews/apple-announces-iphone-se-and-mac-studio-aapl-stock-remains-bullish/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:09:30 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Gene Munster breaks down Apple&amp;#39;s latest product launch and the bigger tech landscape https://www.stck.pro/news/AAPL/24080146 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:06:58 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY

IN AND OUT. Only puts until rate hikes. All cash now. Tomorrow another day. Love it.  Please hold or pump 😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:06:20 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $AAPL Breaking: Blockbuster halts plans on expanding into Russia 🦍🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:06:14 </td>
   <td style="text-align:left;"> $SPY I hope Russia raise taxes and interest on all those companies banning him for nato/Usa broken promises and corrupt. STARTINGBTO THINK they all have corrupt business deals there that Putin DADDY is clearing out. $AAL $FB $AAPL latex564e5d82a52ecf1b0c0c9d87364b271aVIX - 67% call flow 
$NVDA - 68% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 08:00:10 </td>
   <td style="text-align:left;"> $AAPL Sentiment is mostly positive right now. 
News mentions: positive (40), negative (1), neutral (17) 
Our Sentiment Score: +1.009 (scale of -1.5 to +1.5) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:51:07 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 77.9K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:50:47 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:48:04 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. Massive VOLUME 👀 👀  $160 Call for Friday, March 11. Roughly 13 Million dollars! 💰💰💰 BIG MONEY 💰💰💰 Learn more on StockOrbit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:44:07 </td>
   <td style="text-align:left;"> $AAPL bought the new MacBook Pro today- BEAUTIFUL machine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:43:39 </td>
   <td style="text-align:left;"> $SPY you mother fuckers

14 years later, after hours bullshit 

$SPX $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:42:41 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $TSLA $AAPL 
.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:38:35 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director WAGNER SUSAN: 
Transacted Derivative Securities on 2022-03-04.  https://s.flashalert.me/HmlPqx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:38:12 </td>
   <td style="text-align:left;"> $AAPL Form 4 (statement of changes in beneficial ownership of securities) filed with the SEC 

https://newsfilter.io/a/da75c5ac59473c5ca5d4a911c6f5affb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:37:51 </td>
   <td style="text-align:left;"> $AAPL WTF ...Nicolas MurdurO.. # 1🤡Potatoe Joe is seeking oil from Venezuela ,spread the BAD NEWS..$SPY $QQQ.  BEAR BYDEN STRIKES AGAIN!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:37:50 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director SUGAR RONALD D: 
Transacted Derivative Securities on 2022-03-04.  https://s.flashalert.me/0bJfcQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:37:43 </td>
   <td style="text-align:left;"> $AAPL reported 5 new insider trades to the SEC in the last 2 minutes.

1,685 shares acquired by Lozano Monica C (Director)   https://newsfilter.io/articles/4-form-1fcf51bf7092f5752fe4c321a5c3a43b
1,685 shares acquired by Gore Albert Jr (Director)   https://newsfilter.io/articles/4-form-7627d48090dc61be56ee671367fcae69
1,685 shares acquired by Jung Andrea (Director)   https://newsfilter.io/articles/4-form-b7de2d19f5c04ae8759f20783a2f3fb5
1,685 shares acquired by Levinson Arthur D (Director)   https://newsfilter.io/articles/4-form-0fd96f0f6e7169130e021d865e18316c
1,685 shares acquired by Sugar Ronald D (Director)   https://newsfilter.io/articles/4-form-f7e99736e95758fc9bd022b2d96273f0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:36:55 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director LOZANO MONICA C: 
Transacted Derivative Securities on 2022-03-04.  https://s.flashalert.me/O9v9O </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:36:34 </td>
   <td style="text-align:left;"> $AAPL new cheaper IPhone means a wider potential customer base- more customers=more phone sales </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:35:56 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director LEVINSON ARTHUR D: 
Transacted Derivative Securities on 2022-03-04.  https://s.flashalert.me/zOyuN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:35:45 </td>
   <td style="text-align:left;"> $AAPL Will dip further. Then Nasdaq will bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:35:38 </td>
   <td style="text-align:left;"> $AAPL What is more important a phone that you cant eat or food....The Sandman says $SANW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:35:08 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director JUNG ANDREA: 
Transacted Derivative Securities on 2022-03-04.  https://s.flashalert.me/p4GE4R </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:34:17 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director Gorsky Alex: 
Transacted Derivative Securities on 2022-03-04.  https://s.flashalert.me/NuxjM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:33:24 </td>
   <td style="text-align:left;"> $AAPL man bumbling brandon keeps getting ragged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:33:12 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director GORE ALBERT JR: 
Transacted Derivative Securities on 2022-03-04.  https://s.flashalert.me/8XeTLu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:32:54 </td>
   <td style="text-align:left;"> $AAPL See you at $100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:32:35 </td>
   <td style="text-align:left;"> $AAPL 📜 SEC Form 4 filed by Bell James A

https://quantisnow.com/i/2543517?utm_source=stocktwits

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:32:13 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director BELL JAMES A: 
Transacted Derivative Securities on 2022-03-04.  https://s.flashalert.me/jGeyC6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:31:56 </td>
   <td style="text-align:left;"> $AAPL Form 4 (statement of changes in beneficial ownership of securities) filed with the SEC 

https://newsfilter.io/a/f96d2ca8e85d3cee0aea1b7c24515c8d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:30:37 </td>
   <td style="text-align:left;"> $AAPL that 8 hour candle though 😯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:30:34 </td>
   <td style="text-align:left;"> Last Month CPI for January 2022 came in super hot 🔥 7.5% inflation from 40 years ago. The consumer price index gained 0.6% last month after increasing 0.6% in December, the Labor Department said on Thursday. In the 12 months through January, the CPI jumped 7.5%, the biggest year-on-year increase since February 1982.
Bad businesses. If Inflation remains elevated!
Bad for the Market goes lower. 
$QQQ $AAPL $SPY $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:30:28 </td>
   <td style="text-align:left;"> $AAPL Keep printing those puts, this SCAM is far from over.. Thanks Timmy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:29:52 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:29:09 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Even an expensive new Mac couldn&amp;#39;t save Apple&amp;#39;s stock today https://www.stck.pro/news/AAPL/24078798 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:27:05 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $157.5 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:25:55 </td>
   <td style="text-align:left;"> $AAPL ..M-28 “Bryza” aircraft flight simulator 
 
N 
Implementation of the project for PZL Mielec S.A (Lockheed Martin Company) - one of the world’s largest aircraft manufacturers. 
N 
The most technologically advanced M-28 aircraft simulator in the world. 
N 
Proprietary technological solutions addressing both military and civilian users’ needs. 
The M-28 aircraft has been produced in several versions, including a military version which is used by the Polish Navy (known as “Bryza”) and by the Polish Air Force. M-28 is a short take-off and landing airplane that can operate from very short runways and unpaved air strips and operate in various weather conditions. “Bryza” is used, among other things, for border patrolling and for search and rescue operations. It is also used by armies in other countries, including the United States, Germany, Estonia and Vietnam. This is $etcc a .30 stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:20:19 </td>
   <td style="text-align:left;"> $SOFI what is happening after hours? Did russia come to terms with ukraine? Seeing weird moves. Sofi would be a banger if so. $SNDL $AAPL let&amp;#39;s go 52wk low $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:19:47 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m actually up $43.00 dollars in my account today after day trading this trash and I&amp;#39;m happier than a Motha Fucka, but I&amp;#39;m sure that&amp;#39;ll change tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:19:04 </td>
   <td style="text-align:left;"> $AAPL &amp;quot;jiggs10&amp;quot; posting wrong information about Poland sending planes to Ukraine.  Poland said they would send them to Ramstein Airforce Base (for exchange) so America can send them to Ukraine. It&amp;#39;s a bluff! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:16:42 </td>
   <td style="text-align:left;"> $AAPL $TSLA $OIL $UCO ➡️ #WTI Just came through with some TREMENDOUS NUMBERS FOR EARNINGS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:15:46 </td>
   <td style="text-align:left;"> $SOXL $AAPL $AMZN $GOOGL Not to worry! McDonald&amp;#39;s has instituted a no frie zone. They invasion will be over soon. Thank you uncle Ronald. Unless Russia determines this is an act of war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:13:31 </td>
   <td style="text-align:left;"> $AAPL In the recent reporting quarter: 1,244 institutions increased their position, while 1,669 decreased https://www.insider-analysis.com/search_whales.php?ticker=TABLE_AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:13:25 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:10:07 </td>
   <td style="text-align:left;"> $AAPL 150 or 160 tomorrow

What seems more logical???

145 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:08:37 </td>
   <td style="text-align:left;"> $AAPL someone bought $175 call 3/11. Size 3 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:06:39 </td>
   <td style="text-align:left;"> $AAPL AAPL HIGHEST OI PUTS FOR 3/18 EXP IS 175 BITCHES!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:05:42 </td>
   <td style="text-align:left;"> $AAPL With Poland Transferring all Mig-29 jets to Ukraine, That is huge news for $ETCC and it&amp;#39;s military Aviation Training simulators </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:03:38 </td>
   <td style="text-align:left;"> $GSAT Eventually SPOT will be gone because your phone will have the same capabilities. That is what is happening with Globalstar and $AAPL right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:02:15 </td>
   <td style="text-align:left;"> $AAPL closed my call when it shoot up , bought puts , closed put at 2.55 and bought call for tomorrow. Apple of my eye </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:01:16 </td>
   <td style="text-align:left;"> $AAPL obv bullish on $AAPL  short term may be bearish but long-term always bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 07:00:23 </td>
   <td style="text-align:left;"> $AAPL Down 4 days in a row. 166.56 | 166.23 | 163.17 | 159.3 | 157.65 |  https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:58:00 </td>
   <td style="text-align:left;"> $AAPL has a Profit Margin of 26.58%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:56:33 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $TSLA $AAPL 
Just 1 litre price in Euros </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:56:11 </td>
   <td style="text-align:left;"> $AAPL Same idiots shorts always calling PT targets and they always wrong 😂..Bears are so Fckn stupid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:55:27 </td>
   <td style="text-align:left;"> $AAPL IN AND OUT ALL DAY, WILL BE INTERESTING THE DAYS FOWARD! 
#CYRN CYBER SECURITY PLAY, W RUSSIA WE NEED IT ! LORD HELP US </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:55:15 </td>
   <td style="text-align:left;"> $BAND If you think Russia is going to agree to anything, you lost your mind, they are going all in soon, and markets will definitely suffer. How many tech companies have lost 5-10% of total revenue bc they pulled out of Russia. This plus all time high inflation and rising rates is a terrible sign for stocks especially tech. $TWLO $QQQ $AAPL $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:55:04 </td>
   <td style="text-align:left;"> $AAPL iPhone 14 sells bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:53:56 </td>
   <td style="text-align:left;"> $AAPL secular decline incoming here... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:51:43 </td>
   <td style="text-align:left;"> $AAPL looks fun so far imma long it I expect a rally some time further analysis available in my discord atm I’m staying neutral </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:49:53 </td>
   <td style="text-align:left;"> $AAPL It has 36 dollars more to drop until fair value. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:49:39 </td>
   <td style="text-align:left;"> $AAPL thankful for the dip baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:49:03 </td>
   <td style="text-align:left;"> $AAPL what’s happening??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:48:55 </td>
   <td style="text-align:left;"> $AAPL great event the green looks sick!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:48:17 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Paul Tudor Jones Boosts 4 Holdings in 4th Quarter https://www.stck.pro/news/AAPL/24076208 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:47:59 </td>
   <td style="text-align:left;"> $AAPL just broke below 50day and 200day, smells like big correction coming here sadly.  
 
Support in the $140 range, $120 range and at $99  
 
iTradeAI™ is not a financial advisor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:45:33 </td>
   <td style="text-align:left;"> $AAPL went to the site to order the new mac studio right after the event and the shipping date was March 18th originally. By the time I finished selecting the options and click check out, delivery went to early April. Just for kicks I tried to order the same system just now and delivery is at end of April/ may. There’s real demand for apple’s products! Supply chain issues might be affecting delivery dates somewhat but there’s no denying historically with every product launch you always have to jump on the ordering if you want your products sooner cos there’s always somebody else that can’t wait to get their hands on anything apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:44:50 </td>
   <td style="text-align:left;"> $AAPL 10% OF DEMAND DISSAPPEARRED OVERNIGHT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:42:42 </td>
   <td style="text-align:left;"> Today $AAPL shows SELL signal (TA) for short term. Technical analysis source: https://stockinvest.us/stock/AAPL?utm_source=stocktwits&amp;amp;utm_medium=autopost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:42:17 </td>
   <td style="text-align:left;"> $AAPL why red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:42:08 </td>
   <td style="text-align:left;"> $AAPL starting to show signs of weakness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:40:43 </td>
   <td style="text-align:left;"> $AAPL 3 shares = 1 iPhone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:40:36 </td>
   <td style="text-align:left;"> $AAPL under $1 next month then reverse split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:39:14 </td>
   <td style="text-align:left;"> $AAPL Who is the Retail Trader that Buys or Sells when CNBC Traders say something about a stock.  
 
Im sure there is an Algo as well but its always amazing to me watch that happen in the Tech ($qqq) space </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:38:36 </td>
   <td style="text-align:left;"> $AAPL every year iPhones presentation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:37:13 </td>
   <td style="text-align:left;"> $AAPL we will open at 170 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:36:00 </td>
   <td style="text-align:left;"> $NVDA $AAPL Get tax return back soon.  Not sure whether to grab Nvidia or Apple after the recent drops from ATH.  All my purchases are for long term holds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:34:59 </td>
   <td style="text-align:left;"> I think we may see sub SP 4000 maybe touch 3900s… then reverse…. Writing here to time stamp it … lots of buyers at the 20% draw down .. 

🚨 $SPY $AAPL $TSLA $DIS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:32:13 </td>
   <td style="text-align:left;"> $AAPL apple event was a doozer 😴, eps growth will probably be negative next quarter!! Gas, shipping, people savings etc. buy 3 month puts on these bad boys !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:31:45 </td>
   <td style="text-align:left;"> $AAPL BUCK FITTY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:31:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT $DOGE.X 

Wallstbets did more damage to inexperienced investors than anything I have ever seen.

They could have used their platform and following to actually educate investors, and teach them financial tools that they may not get elsewhere. 

Instead they yolo’d money into shitty stocks at ATH’s and watched that $ drain while screaming “to the moon” 

Knowing that hedge funds move markets, did they really expect the purchasing power of a few reddit users to outweigh hundreds of hedge funds pockets? It’s not possible. They knew this.

There is absolutely no way a group of users came together to pump up a stock for a company that’s been screwing people over on their trade ins, with a dying business model &amp;amp; drying up balance sheet. 

Something tells me a hedge fund was behind that forum and movement as a whole, by teaching people to yolo money and buy bad stocks they’ve created a whole new generation of inexperienced investors to profit on for life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:30:34 </td>
   <td style="text-align:left;"> $AAPL rip off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:30:17 </td>
   <td style="text-align:left;"> $AAPL right back where I bought in this morning! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:30:17 </td>
   <td style="text-align:left;"> $SPY $AMD $AMZN $AAPL $TSLA  🧞‍♂️💲🧞‍♂️

Stay Long here 🚀🚀🚀🚀🚀🚀🚀🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:29:20 </td>
   <td style="text-align:left;"> $AAPL 37 analysts prediction is right then 154 should be lower.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:29:09 </td>
   <td style="text-align:left;"> $AAPL Was a nice leader today. First, it bounced off 4 Hour Demand (Green) zone at 155.65 for over 7 points or 5%. Price ran right into 2 Hour Supply (White) zone at 162.63 and rejected for 6 points of 4%. Looks ready to break lower to 151.57  
 
Optionsforecast4u.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:27:48 </td>
   <td style="text-align:left;"> $AAPL sad unvieling, now they want to make some products cheaper because of the hard times otherwise they rape you with high prices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:26:53 </td>
   <td style="text-align:left;"> $AAPL $90 was the boogeyman last year. $140 is this year. We did see 116 and we might see 150 but thats about it. It didnt see 116 for more than a minute or two because i pressed the buy button so hard my fingers broke. Still couldnt get a fill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:26:51 </td>
   <td style="text-align:left;"> $AAPL I don&amp;#39;t know how anyone can be bullish here right now. Must just be gambling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:25:42 </td>
   <td style="text-align:left;"> $AAPL going to $140 b/c biden is a pussy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:24:50 </td>
   <td style="text-align:left;"> $PLTR just sold a bunch of $TSLA and $AAPL stocks for $500k worth. Time to consolidate. Adding them here the rest of the month. Not sure if I’ll post as actively as I have </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:24:38 </td>
   <td style="text-align:left;"> $AAPL i just read the m1 ultra specs. Its crazy the stock is being pumped higher but damn thats a powerful system. Boomer tutes will need a few days for their zoomer analysts to explain it to them. But for those who can read, m1 ultra is:
90% more powerful than $intc  flagship intel i9 12th edition 900 series at 70% lower power / 30% of the power used to deliver 90% better performance.

As good as the $NVDA rtx 3090 while consuming 200W less. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:23:11 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. 👀 👀  $175 Call for Friday, November 18. Roughly 3 Million dollars! 💰💰 WOAH 💰💰 Learn more on StockOrbit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:22:43 </td>
   <td style="text-align:left;"> $AAPL no new m2 max today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:22:22 </td>
   <td style="text-align:left;"> $AAPL so the new product line for 2022 consists of 100 additional pixels for 40% price hike? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:21:08 </td>
   <td style="text-align:left;"> $AAPL As much as I like Apple and Apple products today was a shit show 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:20:21 </td>
   <td style="text-align:left;"> $AAPL 4k for a laptop Lmaoooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:20:02 </td>
   <td style="text-align:left;"> $AAPL well was feeling good intraday about my $150 credit put spreads expiring this week  when it hit $162 but now I dont know I go way out of money cuz of my shitty luck and here we are gonna be holding my breath anyway 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:18:42 </td>
   <td style="text-align:left;"> latexe66956111f7e75d1d9ff2096362c56eaAMD ↗️ 

$AAPL $BTC.x $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:12:37 </td>
   <td style="text-align:left;"> $BMBL $AAPL Bumble Stock Surges on Earnings. The Relief Rally Is On. 

https://newsfilter.io/a/a401bd4e85dfce456bcadb7141e9dd5c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:12:34 </td>
   <td style="text-align:left;"> $AAPL 

CNBC bashing Apple 
Guy fuck off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:12:25 </td>
   <td style="text-align:left;"> $AAPL drop after the event and news, makes sense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:11:58 </td>
   <td style="text-align:left;"> $AAPL sell the news event. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:11:30 </td>
   <td style="text-align:left;"> $AAPL $MSFT 4 consecutive red days...yeah ok. The largest market caps should bounce back big tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:11:06 </td>
   <td style="text-align:left;"> $AAPL 4k for a laptop? GTF outta here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:10:35 </td>
   <td style="text-align:left;"> $SPY 
What happend to all the bullish chit chat? 
😕 😞 

$QQQ $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:09:30 </td>
   <td style="text-align:left;"> $AAPL 

Stocktwits needs to chill on the glitches for real hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:09:02 </td>
   <td style="text-align:left;"> $AAPL primed to bounce hard!! Watch it make new low and bounce! APR 160, 165C watching </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:08:22 </td>
   <td style="text-align:left;"> $AAPL proudly own 0 apple products </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:08:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : MarketWatch First Take: Apple&amp;#39;s Mac renaissance is about to get a big boost ‘in a market where everyone counted them out&amp;#39; https://www.stck.pro/news/AAPL/24076133 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:07:37 </td>
   <td style="text-align:left;"> $AAPL falling wedge, almost primed to buy calls. prob june 180c. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:06:27 </td>
   <td style="text-align:left;"> $AAPL I told ya earlier to 150. Who got caught up in the fake pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:05:29 </td>
   <td style="text-align:left;"> $AAPL how is apple down, I didn&amp;#39;t watch the presentation but the new M1 chip looks insane, bet $appl hits $180 by end of year, may actually have to buy some if it dips a bit further </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:04:54 </td>
   <td style="text-align:left;"> $SPY FYI, theyre trying to price this in now. Its going to be bad YoY data. $TSLA $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:04:21 </td>
   <td style="text-align:left;"> $AAPL 145 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:03:33 </td>
   <td style="text-align:left;"> $AAPL 
Who’s buying???? 🤚🏿🤚🏾🤚🏽🤚🏼🤚🏻🤚 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:03:21 </td>
   <td style="text-align:left;"> $AAPL always dollar cost averaging on days like today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:03:13 </td>
   <td style="text-align:left;"> $AAPL Stagflation then imminent recession buyer at 52 week lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:03:11 </td>
   <td style="text-align:left;"> $AAPL why’s this down?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:02:43 </td>
   <td style="text-align:left;"> $AAPL off to 170 tomorrow 💀😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:02:31 </td>
   <td style="text-align:left;"> $7.8K AMD EPYC 7763 destroys the latex484b01b9b5e266a0c73064959161f633AMD ↗️

$AAPL $AMZN $MSFT $INTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:02:22 </td>
   <td style="text-align:left;"> $AAPL Perigon Wealth Management, Llc increased their holdings by 3,747%, one of the largest institutional increases this quarter https://www.insider-analysis.com/search_whales.php?ticker=TABLE_AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:02:20 </td>
   <td style="text-align:left;"> $aapl relative outperformer https://youtu.be/Z7NkoYFU680 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:01:35 </td>
   <td style="text-align:left;"> $TSLA 
breaking news: 
 
&amp;quot;Tesla an apple division&amp;quot; and 
  
elon sails into the sunset with spacex/starlink debuting with an IPO. 
 
How likely is this from a scale of 1-10? 
 
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:01:11 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $TSLA $AAPL  
wow USA holy cow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:00:51 </td>
   <td style="text-align:left;"> $AAPL shorting to 55$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 06:00:28 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-08 Options Analysis Video: 
https://www.youtube.com/watch?v=sugEHSx3N34 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:58:16 </td>
   <td style="text-align:left;"> $AAPL this is going to the $120’s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:57:43 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL), Intel Corporation (NASDAQ: $INTC) – Apple’s ‘Peek Performance’ Reveals: iPhone SE, Versatile iPad Air, Powerful Chip, Mac Studio, MLB And More https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-intel-corporation-nasdaqintc-apples-peek-performance-reveals-iphone-se-versatile-ipad-air-powerful-chip-mac-studio-mlb-and-more/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:56:38 </td>
   <td style="text-align:left;"> $QQQ Big tech charts including $MSFT, $AAPL, $AMD, $NVDA suggesting this is the bottom. I dont know about day trades, but this seems like the right time to buy 4/14 OTM calls, sit back and wait for the rebound. It will come soon and it will be more aggressive than we have ever seen. Not expecting ATH anytime soon but a good rebound with latex851facee71d974ee0d4bc9cd192ef69fAMD ↗️

$AAPL $AMZN $NVDA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:55:43 </td>
   <td style="text-align:left;"> $KO $AAPL  the Russian oligarchs that would want to buy coke and apple products can get them if they really want them.  This really only affects the citizens. Sad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:54:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL  
Mo Money mo problems,  
Less money, even mo mo problems. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:49:31 </td>
   <td style="text-align:left;"> $AAPL if a doorknob ran against a Dem this November it would have my vote. We must have Reps take back the House this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:44:26 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT $AAPL Does this work? Sometimes I can&amp;#39;t tell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:44:23 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOGL $AMZN $NVDA its over guys. Sell ASAP so you don&amp;#39;t lose more money.. major recession coming!! Don&amp;#39;t say I didn&amp;#39;t warn you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:43:21 </td>
   <td style="text-align:left;"> $AAPL 
Rate the apple event on 1 till 10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:42:10 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ load up don’t be a fool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:41:51 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:41:09 </td>
   <td style="text-align:left;"> $AAPL This place is a complete joke.  Mostly Bear Trolls that disappear when the going gets tough for them.  Most don&amp;#39;t have a pot to piss in.  Trading their last meal money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:38:32 </td>
   <td style="text-align:left;"> $SPY 

oil and freight going insane.

Jesus help us all

$SPX $AAPL $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:37:09 </td>
   <td style="text-align:left;"> $AAPL Damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:36:41 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA  if we lost another 10% it will take about 2 to 3 years for recovery, remember: The bull takes the stairs... The bear jumps out the window! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:36:20 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 370.6K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:35:43 </td>
   <td style="text-align:left;"> $AAPL Bullish on the new products announced today.  I see many folks adding - make sure you have the proper risk vs reward ratio when you do: https://youtu.be/CytzoL2ec14 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:35:39 </td>
   <td style="text-align:left;"> $AAPL weekend view @ www.elliottwave-forecast.com. We like looking for a decline further down, where buyers can enter at the blue box for a bounce.  We don’t like to sell it short this close to the blue box though, but we do like to buy it lower at the extreme area where buyers are waiting for a bounce.  Here’s how we saw it this weekend.  #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:35:00 </td>
   <td style="text-align:left;"> $AAPL  new low tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:33:53 </td>
   <td style="text-align:left;"> $AAPL Dow will go to 25,000, Nasdaq to 10,000, and S&amp;amp;P to 3,200. War will drag on because Putin knows nobody will stop him. He doesn’t give a shit about how sanctions hurt the Russian people. He’s a dictator. The only scenario that will work is if he’s taken out by Russians themselves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:33:46 </td>
   <td style="text-align:left;"> What You Missed On Wall Street On Tuesday - $AAPL - http://thefly.com/permalinks/entry.php/AAPLid3473920 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:33:20 </td>
   <td style="text-align:left;"> $AAPL be prepared for a morning pop with calls and follow it immediately with puts. This pops early for 1-5min and dumps as of late. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:33:00 </td>
   <td style="text-align:left;"> $SPY all of this price action today detracted from the fact that $AAPL released yet another identical version of their crappy iPhone and a lackluster apple day. The market is giving the company a ridiculous P/E multiple, as they are no longer a growth company. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:32:57 </td>
   <td style="text-align:left;"> $AAPL Apple was holding all these days for this event .. now  it will go south of 140$s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:32:48 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:32:35 </td>
   <td style="text-align:left;"> $AAPL $INTC Apple&amp;#39;s &amp;#39;Peek Performance&amp;#39; Reveals: iPhone SE, Versatile iPad Air, Powerful Chip, Mac Studio, MLB And More 

https://newsfilter.io/a/4c206127b4c3a1d8c97d0d6d71a9d201 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:32:31 </td>
   <td style="text-align:left;"> $aapl Someones here to play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:32:16 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $GOOG 

https://www.businessinsider.com/ukraines-zelensky-says-he-has-cooled-on-joining-nato-2022-3?amp

In addition to his NATO comments, Zelensky said on Tuesday that he was open to discussions about the control of Russian-backed separatist regions in eastern Ukraine, which could be an opening for peace talks with Russia.

&amp;quot;It is important to me how people who want to be part of Ukraine will live there. I am interested in the opinion of those who see themselves as citizens of the Russian Federation. However, we must discuss this issue,&amp;quot; Zelensky said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:30:01 </td>
   <td style="text-align:left;"> $AAPL WTF happened? Bad ER? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:28:22 </td>
   <td style="text-align:left;"> $AAPL will this hit 145? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:28:20 </td>
   <td style="text-align:left;"> $AAPL Hey Apple Bulls 
How will Apples Profits not be negatively impacted from higher input costs 

$AAPL Apple has Higher input costs for Apple Products from 40 Year High Inflation🚀
Does Apple pass costs to customer or does Apple eat it? Either way Apple Profits may be negatively impacted from High Inflation.iPhone is made of aluminum and glass and other materials. $QQQ $SPY $AMD 
Tech Stocks and Market go lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:28:09 </td>
   <td style="text-align:left;"> Is the Stock Market Going to Crash in 2022? 
$NFLX  $AAPL $AMZN  
Is The Stock Market Going to Crash In 2022? Wow, what a bold statement that is for a headline! Well first thing to keep in mind is not to panic right away. This article is not financial advice for you to buy or sell investments. Always consult with a register financial advisor. We are not a registered financial advisor. This article is here to educate you on the potential economic factors that we see in 2022. 
Let’s first start off explaining what has happened since January 2022: 
 
When we measure the performance of the US equity indices since the start of January 2022 till February 2022, we see the following:  https://teachtactic.com/is-the-stock-market-going-to-crash-in-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:27:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Stock Market Whipsaws Amid Russia Crude Ban; Apple, Quanta Services, Callon Petroleum In Focus https://www.stck.pro/news/AAPL/24074174 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:26:16 </td>
   <td style="text-align:left;"> Amazon Inc. (NASDAQ: $AMZN), Apple Inc. (NASDAQ: $AAPL) – Want To DJ Your Own Live Radio Show? Amazon Launched An App For It https://www.billionaireclubcollc.com/amazon-com-inc-nasdaqamzn-apple-inc-nasdaqaapl-want-to-dj-your-own-live-radio-show-amazon-launched-an-app-for-it/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:25:30 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

IT’S COMING!!!!!!!!!!!! 📉😱🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:23:42 </td>
   <td style="text-align:left;"> $AAPL This will work out well:

U.S. COULD CUT OFF CHINESE FIRMS FROM AMERICAN EQUIPMENT AND SOFTWARE THEY NEED TO MAKE THEIR PRODUCTS IF THEY DEFY U.S. EXPORT RESTRICTIONS - COMMERCE SECRETARY TELLS NYT. $FXI $BABA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:22:47 </td>
   <td style="text-align:left;"> $AAPL https://seekingalpha.com/amp/article/4493318-apple-stock-scenarios-possibilities-manufacture-earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:22:34 </td>
   <td style="text-align:left;"> Apple&amp;#39;s &amp;#39;Peek Performance&amp;#39; Reveals: iPhone SE, Versatile iPad Air, Powerful Chip, Mac Studio, MLB And More $AAPL $INTC https://benzinga.com/z/26048194#.YifJBrRxcL4.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:22:00 </td>
   <td style="text-align:left;"> $AAPL https://finance.yahoo.com/amphtml/video/apple-expected-unveil-low-cost-164949550.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:21:58 </td>
   <td style="text-align:left;"> $AAPL how your 401k now that Brandon is in office </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:21:40 </td>
   <td style="text-align:left;"> $AAPL hurting all Americans and always sticking his crooked nose where it dont belong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:20:55 </td>
   <td style="text-align:left;"> $AAPL trump use to judge his success on the market biden judges his success at the gas pump . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:20:11 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

This is our moment bear brothers to make dr. burry proud!!! lfg!!!!😤

🧸 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:20:00 </td>
   <td style="text-align:left;"> $AAPL  
 
https://www.benzinga.com/trading-ideas/long-ideas/22/03/26046561/is-apple-a-defensive-play-why-this-investor-is-buying-more-stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:19:46 </td>
   <td style="text-align:left;"> $AAPL democrats love high oil prices. Good job on who ever voted for diaper head. Donkeys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:19:45 </td>
   <td style="text-align:left;"> $AAPL what a joke. buying at $50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:17:35 </td>
   <td style="text-align:left;"> 3 Non-Apple Stocks To Play The New iPhone And iPad Air  $AAPL $GLW $TSM $SONY 

https://newsfilter.io/a/33fd07735336a6e580f5a803340f07e9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:17:32 </td>
   <td style="text-align:left;"> $SPY $MSFT $AAPL $TSLA are not in the game yet. Soon, they will be making the cross. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:17:27 </td>
   <td style="text-align:left;"> $AAPL Option Order Flow Sentiment is 59.2% Bullish. https://tinyurl.com/y686h8pj </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:16:29 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:15:51 </td>
   <td style="text-align:left;"> $AAPL don&amp;#39;t be fooled by biden market and gas prices were bad before Russian attack. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:15:29 </td>
   <td style="text-align:left;"> $AAPL should have sold my calls today on the pop. Missed it and I am in negative now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:14:05 </td>
   <td style="text-align:left;"> $AAPL product announcement was amazing. However , if we see 162 by EOW, i might get some puts. The China news is damning. US shouldnt talk about provoking China if it isnt willing to close and commit to it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:13:29 </td>
   <td style="text-align:left;"> $AAPL tomorrow PT folks? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:13:26 </td>
   <td style="text-align:left;"> $AAPL consumers will DEFINITELY buy a phone over food and gas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:13:21 </td>
   <td style="text-align:left;"> $AAPL HA! The Russian economy tanked, And for some reason all the fucking Trump supporters are broke 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:12:57 </td>
   <td style="text-align:left;"> $AAPL maybe BLM will pay your bill this month. Opps sorry they bought mansions with your cash. Dumb fucks. Trump 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:12:42 </td>
   <td style="text-align:left;"> $SPY $AAPL Really fancied loading shorts on that dead cat bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:11:27 </td>
   <td style="text-align:left;"> $AAPL he is for the bums and kids having babies.  We pay for it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:11:27 </td>
   <td style="text-align:left;"> $AAPL WS doesn&amp;#39;t like thought of Budget phone? Delayed reaction? I think great idea. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:11:22 </td>
   <td style="text-align:left;"> $AAPL Likely retest $151.90.  Market turned red and time to “sell the news” on the lackluster product announcement.  🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:10:56 </td>
   <td style="text-align:left;"> $AAPL pathethic market. Going to $140 as long as biden is president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:10:40 </td>
   <td style="text-align:left;"> $AAPL they got rid of trump for this diaper head biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:10:13 </td>
   <td style="text-align:left;"> Apple Unveils Cheaper 5G iPhone, Mac Studio Computer At Spring Product Event https://www.investors.com/news/technology/apple-stock-cheaper-5g-iphone-seen/ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:10:11 </td>
   <td style="text-align:left;"> $spy so some of what we see selling off like $hd &amp;amp; $amzn just screams Margin Calls. $aapl does what it always does after its event but clearly the Market is going to do this move until it stops working for the momo trend followers. 
 
Its a process as painful as it feels </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:10:08 </td>
   <td style="text-align:left;"> $AAPL what a piece of shit market. Created by biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:09:57 </td>
   <td style="text-align:left;"> $AAPL wtf is wrong here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:09:36 </td>
   <td style="text-align:left;"> $AAPL by EOW-  $150.00 even might touch 148.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:07:55 </td>
   <td style="text-align:left;"> $SPY my entire portfolio was green other than $AAPL and my indexes…..traded $CEI and got out before the rug pull. Was a solid day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:07:39 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA lets get a nice 20% haircut on everything before continuing uptrend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:07:21 </td>
   <td style="text-align:left;"> $TSLA $GOOGL $NVDA $V $AAPL basically a snake oil democrat stock market where large caps gain intraday and lose most gains by the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:07:18 </td>
   <td style="text-align:left;"> $AAPL 155 is looking possible tomorrow. Doesn’t stop bleeding short term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:07:12 </td>
   <td style="text-align:left;"> $AAPL $68 tomorrow! Woot woot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:06:54 </td>
   <td style="text-align:left;"> $AAPL looks like puts will print tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:06:32 </td>
   <td style="text-align:left;"> Diversified portfolio proposal: Apple( $AAPL ),… https://www.macroaxis.com/invest/stock-volatility?s=AAPL,MSFT,CLF,SYK,MRO,PCG,WAFD,IBOC,QCOM,FAST,FCX #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:06:26 </td>
   <td style="text-align:left;"> $AAPL you all know it’s going bankrupt right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:06:01 </td>
   <td style="text-align:left;"> $AAPL 9.8 million share dump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:05:16 </td>
   <td style="text-align:left;"> $AAPL I tried to ignore it but we are heading for another 20% hit across the board. There is no relief in sight to improve the market anytime soon. Dow 25,000 and Nasdaq 10,000 incoming. I’m moving from 50% cash to 100% cash this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:04:48 </td>
   <td style="text-align:left;"> $AAPL what a rollercoaster ride today. Still </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:03:39 </td>
   <td style="text-align:left;"> $AAPL glad I held </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:03:37 </td>
   <td style="text-align:left;"> $SPY lol good job to anyone who managed to make money on these fake pumps $AAPL $AMD jt wasn’t easy (stressful a little ) but managed to get some nice 200+% plays on these pumps ,still sad to see this wash all those gains away wasting time for the longer term holders ,it’s sad … how they says peoples time like that we can’t do nothing about it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:03:06 </td>
   <td style="text-align:left;"> $SPY Yeah! Turnaround Tue……oh.  $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:02:35 </td>
   <td style="text-align:left;"> Want To DJ Your Own Live Radio Show? Amazon Launched An App For It  $AMZN $SONY $WMG $AAPL 

https://newsfilter.io/a/eb52e88ad084c5eb7ac866b9634a7035 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:02:13 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:02:03 </td>
   <td style="text-align:left;"> $AAPL 🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:01:58 </td>
   <td style="text-align:left;"> $AAPL It closed - 1.17 %.  The ST Ticker is not correct. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:01:35 </td>
   <td style="text-align:left;"> My g0d.

That selling O.o

$SPY $SPX $MRNA $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:01:28 </td>
   <td style="text-align:left;"> $AAPL Either give me $140 to load or $165 to short!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 05:01:13 </td>
   <td style="text-align:left;"> $DWAC all u idiots want Trump
Back cuz his stock market. IF Y THINK THE MARKET IS DICTATED BY PRESIDENTS THEN you dumb fuks don’t even realize — 

OBAMA SHIT ON TRUMP

NUMBERS DONT LIE

 $SOFI $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:59:58 </td>
   <td style="text-align:left;"> $AAPL Here’s everything Apple just announced: A new iPhone, iPad Air, Mac Studio computer and more

https://www.cnbc.com/2022/03/08/apple-event-live-updates.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:59:20 </td>
   <td style="text-align:left;"> $AAPL calls officially worthless for the week on a Tuesday. Decimated by today alone coupled with yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:59:10 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:57:10 </td>
   <td style="text-align:left;"> $SSNLF $AAPL Samsung needs to cut all business ties with Russia. Come on they already hacked your critical data. Let them use old motorola brick phones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:57:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.38%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:56:38 </td>
   <td style="text-align:left;"> $AAPL Bad close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:56:34 </td>
   <td style="text-align:left;"> $AAPL that’s a big dump eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:55:50 </td>
   <td style="text-align:left;"> $AAPL Coca-Cola suspends business in Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:55:09 </td>
   <td style="text-align:left;"> $AAPL crazy day!  Hope the traders here got a round or two!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:53:39 </td>
   <td style="text-align:left;"> $AAPL If you&amp;#39;re going tech, this is the safest place to be. No one knows what the hell is happening or going to happen. The Bull vs Bear thing is complete nonsense in this market, the musings of kids. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:53:04 </td>
   <td style="text-align:left;"> $AAPL I think some investors are fearing a conflict between China and Taiwan. That would impact Apple&amp;#39;s chip supply. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:53:00 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $AMZN $TQQQ 
Analysts will lower EPS &amp;amp; sales guidance for next quarters due to Russia circumstances,  so that they can beat ERs, just like they did during pandemic peak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:52:12 </td>
   <td style="text-align:left;"> $AAPL so now I won’t be able to watch Yankees on Friday nights because apple will have the rights and you will have to get Apple TV.  That’s it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:51:00 </td>
   <td style="text-align:left;"> $AAPL they dupe both bears and bulls - pump, dump, pump, dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:50:59 </td>
   <td style="text-align:left;"> $aapl $qqq https://twitter.com/deitaone/status/1501298833627791360?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:50:26 </td>
   <td style="text-align:left;"> $AAPL $155 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:50:02 </td>
   <td style="text-align:left;"> $AAPL Key News Update 
MLB Inks Steaming Deal With Apple 
https://www.marketwatch.com/story/apple-reveals-new-iphone-se-deal-to-broadcast-mlb-games-on-friday-night-11646764017 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:49:58 </td>
   <td style="text-align:left;"> $AAPL what happened? Was at work then saw this pumped and dumped. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:49:46 </td>
   <td style="text-align:left;"> $AAPL comeon I need 165 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:48:54 </td>
   <td style="text-align:left;"> $AAPL what a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-09 04:47:42 </td>
   <td style="text-align:left;"> $aapl biden wanted to sell his puts and buy calls. Hence Oil ban. Poor guy doesnt know that his calls will now suck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:56:06 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $TQQQ $UVXY 
VIX Futures Dripping 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:56:00 </td>
   <td style="text-align:left;"> $TSLA shows a strong growth in EPS: 204.86%. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:55:53 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ all these fat, old, greedy boomers will finally get what they deserve. From this crash the new generation will take over while you old farts retire in your 2 star retirement homes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:55:03 </td>
   <td style="text-align:left;"> $NIO $AAPL $MSFT $QQQ $TSLA you know sh*t is getting real when Switzerland stops being neutral for the first time in 500 years and starts freezing Russian accounts. There’s a really good chance that we’re going to have WW3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:54:51 </td>
   <td style="text-align:left;"> $SPY tomorrow the Fed ends QE tomorrow…May have 0 buyers and no liquidity. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:54:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $TSLA I think it says a lot when Saudi Arabia and the UAE refuse to take Joe Biden&amp;#39;s calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:53:34 </td>
   <td style="text-align:left;"> $TSLA 
below 814*** 784-798 target if can take 782, 750 is possible very fast 
***=(with failed test to try to get over + market pushing down) 
if it was me (not advice just my thoughts) i would take the 800 P for 814 -&amp;gt; 784-798 &amp;amp; roll up portion of profits if breaks 782 to the 750 P but thats me lol you got to trade your plan 
here&amp;#39;s a chart:https://www.tradingview.com/chart/TSLA/IG7hkQhP-TSLA-trading-it-3-9/ 
#daytrading #optionstrading #options #stockmarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:51:54 </td>
   <td style="text-align:left;"> $TSLA 

Loosening environmental regulations won’t lower prices. 

But transforming our economy to run on electric vehicles, powered by clean energy, will mean that no one will have to worry about gas prices.

It will mean tyrants like Putin won’t be able to use fossil fuels as a weapon.
—US president Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:50:40 </td>
   <td style="text-align:left;"> latexf8ea623a7b306ddc24d7b390859a4c90AMD ↗️

$AAPL  $INTC  $NVDA  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:46:13 </td>
   <td style="text-align:left;"> $TSLA whales coming in tomorrow 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:45:21 </td>
   <td style="text-align:left;"> $TSLA $1000 coming back real quick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:43:54 </td>
   <td style="text-align:left;"> $TSLA https://www.wallstreetsnaps.com/products/please-mine-more-nickel-t-shirt?_pos=2&amp;amp;_sid=14fa47d77&amp;amp;_ss=r </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:42:19 </td>
   <td style="text-align:left;"> $NIO $PLTR $TSLA $CEI 
Lmfao this guy has zero brain cells </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:42:08 </td>
   <td style="text-align:left;"> $SPY $TSLA WHEN HOUSING MARKET CRASH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:38:46 </td>
   <td style="text-align:left;"> $NIO $XPEV $LI $TSLA $LCID https://cnevpost.com/2022/03/08/some-are-selling-nio-et7-pre-orders-for-double-or-even-triple-the-amount-they-initially-paid/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:38:15 </td>
   <td style="text-align:left;"> $PLTR $TSLA $SQ Start trading over 4 month ago and I lost $3K, Now I&amp;#39;ve made over $147K+ profits after join their chat room and using their alerts. Highly recommended! It&amp;#39;s free to join..! optionminning.mydiscussion.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:34:42 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-08 Daily Forecast Video: 
https://www.youtube.com/watch?v=RTRArzZdM20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:31:08 </td>
   <td style="text-align:left;"> $TSLA 
Tesla vs BYD

https://youtu.be/aSmkl7Yn2VU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:31:07 </td>
   <td style="text-align:left;"> $DWAC Truth social should buy Facebook and Deport Mark Zuckerberg to Venezuela $FB $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:30:44 </td>
   <td style="text-align:left;"> $TSLA $AMZN  tinyurl.com/2p9e489k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:30:32 </td>
   <td style="text-align:left;"> $MULN $LCID $TSLA $WKHS $NIO 

Biden EV pump!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:29:25 </td>
   <td style="text-align:left;"> $TSLA Any thought on this article? 
 
https://www.cnbc.com/2022/03/08/nickel-price-surge-could-threaten-automakers-ev-plans.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:25:49 </td>
   <td style="text-align:left;"> $TSLA $SBUX  $F  $TM 

The national average for a gallon of gas is $4.17 A gallon of Starbucks coffee costs $16.80. Just saying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:24:57 </td>
   <td style="text-align:left;"> $TSLA https://www.teslarati.com/tesla-giga-texas-giga-fest-attendance-figures-time-details-revealed/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:24:03 </td>
   <td style="text-align:left;"> $TSLA  I have been posting plans for everyday targets hitting precisely. You had 3 opportunities to make good profits if you followed me. I am also running a paid group if you are interested in joining message me!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:23:50 </td>
   <td style="text-align:left;"> $WIMI  $TSLA  With the arrival of 5G technology, AR/VR is expected to become the very first battle filed, and gradually bring in the other applications. The UBW high-speed transmission capability and low delay brought by 5G can solve the disadvantages such as insufficient VR/AR rendering capacity, poor interactive experience, weak terminal mobility and vertigo. WIMI is really optimistic in the prospect of 5G market, was planing to expand 5G+AR application scenarios to satisfy the user for a more diverse and complex scenes, define more new capabilities of 5G+AR, maximize the commercial capabilities of 5G platform, and meet the differentiated needs of industry applications. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:23:50 </td>
   <td style="text-align:left;"> $TSLA Ain’t greedy,  we will be happy with 2T cap.  
 
We are Teslanaires! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:22:46 </td>
   <td style="text-align:left;"> $DWAC $SPY $TSLA I’ve had enough of Biden’s communist socialist regime. I’m dumping my wife and applying for Russian citizenship, they have beautiful women </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:20:55 </td>
   <td style="text-align:left;"> $TSLA futures massive dump incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:20:01 </td>
   <td style="text-align:left;"> $TSLA $SPY $DWAC Libs, Dems, social losers love pedophilia. They’re crying because they want kindergarteners to learn about sexuality 

CNN = pedo ring 
Lincoln project = pedo ring 
Weinstein, Clinton

SICK! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:18:15 </td>
   <td style="text-align:left;"> $WKHS let’s f go!!! Ev sector is about to take off!!!!no turning back.  $TSLA $NKLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:17:27 </td>
   <td style="text-align:left;"> $TSLA 

elon didn’t invent tesla, he just bought the company so he could sell you his bags at the top... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:15:42 </td>
   <td style="text-align:left;"> $MULN $TSLA $ $ARKK 
😅🥸🎁🍿📊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:14:35 </td>
   <td style="text-align:left;"> $SPY $DWAC $TSLA I miss our dear leader young and handsome president trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:12:12 </td>
   <td style="text-align:left;"> $TSLA will it continue to climb tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:12:02 </td>
   <td style="text-align:left;"> $TSLA setup to hit $880 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:10:23 </td>
   <td style="text-align:left;"> $TSLA Warren Buffett says never to hold money during a war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:08:07 </td>
   <td style="text-align:left;"> $TSLA 1000 tmr morning Elon releasing news about…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:07:53 </td>
   <td style="text-align:left;"> $LEV $PTRA $TSLA $NIO $NKLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:05:19 </td>
   <td style="text-align:left;"> $AMC $QQQ $TSLA   $1800 into $40k in the last 30 days.. If you really want to make huge profits on trading then, Join this winning chat:.   fundamental.stockmarketmovers.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:04:37 </td>
   <td style="text-align:left;"> That&amp;#39;s exactly right Mr. President, and also what i was underlining that we $TSLA &amp;#39;s responsibility and ultimate goals always share a unite and common future with the society. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:03:35 </td>
   <td style="text-align:left;"> $TSLA 
Bulls showing up to market open tomorrow 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:01:00 </td>
   <td style="text-align:left;"> $TSLA I can’t be bearish on this setup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 10:00:05 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT Who should be the first person I interview for my YouTube channel?  Short(5 minutes or less) zoom interview about investing and making money with any side hustles etc.  Only thing displayed will be your stocktwits username. 

https://youtube.com/channel/UCDOe76iBDhS6D3tXqYeBeLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:58:12 </td>
   <td style="text-align:left;"> $TSLA 📆🎯
Another day in the books. Easy money to be made if you have the right guidance. 📚📌📈

Check twitter for free option plays 💰🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:57:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK

Looks like I’m having Wagyu tomorrow!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:54:00 </td>
   <td style="text-align:left;"> $TSLA you should learn something from Shopify

$324 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:53:09 </td>
   <td style="text-align:left;"> $MULN All Ev companies, in any capacity should do well, as Oil spikes, and the lack of battery inputs slows down the $TSLA and $F of the world. 
 
There are going to be buy-outs like in the Pharm sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:52:32 </td>
   <td style="text-align:left;"> $TSLA 855.54 resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:49:22 </td>
   <td style="text-align:left;"> $TSLA when Klan gathering at Tesla Giga factory? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:45:41 </td>
   <td style="text-align:left;"> $TSLA every shoe in the market has fallen off a cliff except this fkn bloated pig. Every day I add puts. Waiting for 600s lemmings. We are one headline away from $150 oil. China reaching for Taiwan. Putin saying Fk U to the west and world. I will laugh at all you fkn bull turds for being greedy when we get there. for the average retail investor who doesn’t have a clue about the market, but still made gains…reality is coming. Judgement day peasants. If you’ve never tried in a bear market, the time has come. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:45:21 </td>
   <td style="text-align:left;"> $TSLA $NIO $RIVN Cant afford 5-7$ gas? Just buy a 60k-120k Electric car! - dumb ass Biden Voters🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:44:03 </td>
   <td style="text-align:left;"> $TSLA bears 🐻 I feel you now , it’s ok life is a win lose game , better luck another day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:41:35 </td>
   <td style="text-align:left;"> $TSLA Poland’s fighter jets let’s gooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:39:45 </td>
   <td style="text-align:left;"> $TSLA 🤚https://youtu.be/X6-vrGc6ZXU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:36:06 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!

Details of Giga Fest at Giga Texas revealed in major event permit application!! 

🙏🏻🐉🦅
(I’ll be there) 

https://driveteslacanada.ca/news/details-giga-fest-at-giga-texas-revealed-permit-application/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:34:42 </td>
   <td style="text-align:left;"> $TSLA Pete Buttigieg Just Proved Why TSLA Stock Is a Buy Right Now

https://investorplace.com/2022/03/pete-buttigieg-just-proved-why-tsla-stock-is-a-buy-right-now/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:32:39 </td>
   <td style="text-align:left;"> latex1d63712dc841ade9ec9d0fb29ef22883AMD DIS 
 
The List: 
$AAPL $TSLA MSFT $NVDA FB  PYPL  AMZN 
 
 
$NIO continues to have a dedicated fanbase.  
 
 
Did you trade any of these stocks? 
 
More 👉 https://bit.ly/3pEk3Xl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:32:07 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-08 Options Analysis Video: 
https://www.youtube.com/watch?v=Fbkb9n6l9cw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:32:00 </td>
   <td style="text-align:left;"> $SPY $TSLA $XLE

Is this true ?

&amp;quot;MSNBC guest: High gas prices will force Americans to accept ‘the truth’ of green energy
Roben Farzad said the ‘bigger the hurt’ of high gas prices, the more Americans will buy electric.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:31:50 </td>
   <td style="text-align:left;"> BradyOnLithium on Twitter: &amp;quot;#Biden&amp;#39;s firm declaration that the US and EU are determined to move away from #oil and to independent #CleanEnergy basically cemented the #battery age as upon us and that #Lithium will be the chosen #commodity/chemical going forward. Li is the chosen one. $LAC $f $tsla&amp;quot; / Twitter https://mobile.twitter.com/brady1204933030/status/1501292977968201731 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:30:46 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:27:53 </td>
   <td style="text-align:left;"> $TSLA stock analysis based on today&amp;#39;s closing price 

https://youtu.be/JCccebn6RY4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:26:49 </td>
   <td style="text-align:left;"> $IMPP $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:25:13 </td>
   <td style="text-align:left;"> $XOM I am using my dividends payday to buy more XOM shares.  $300 per barrel in 2022!  $SPY $AAPL $TSLA $AMZN  
https://www.cnn.com/2022/03/08/business/oil-price-russia-warning/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:23:52 </td>
   <td style="text-align:left;"> $TSLA let’s hope that tomorrow’s CPI data is what the market expects so it could be a sell the rumour, buy the news event.  If it can breach and hold 840 then we will see 860 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:21:55 </td>
   <td style="text-align:left;"> $TSLA Tomorrow we MOON 🌙!!!  885 close!! 😉 🔥 ♥️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:18:41 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:17:20 </td>
   <td style="text-align:left;"> $WTI As long as during earnings call ceo/cfo don’t give out any negative outlook or goes off about building robots like Elon did during $TSLA call we should 🚀🚀🚀🌙🌙🌙💵💰💵💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:13:26 </td>
   <td style="text-align:left;"> $TSLA  Abd so it begins  
not to be left behind  
Oklahoma passes State Bill 1541, allowing autonomous vehicles to operate on public roads. 
https://www.teslarati.com/oklahoma-senate-sb1541-autonomus-vehicles-public-roads-passes/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:13:11 </td>
   <td style="text-align:left;"> $TSLA 

Remember! No “watchlist”,  No “study”, no “education”, no selling “courses”! Straight up “live” trading with the magician TWOWS🤑🤑🤑Make money! Go home in my Small Account Challenge discord! Rest, HIT THAT FOLLOW💰💰💰💸💸💸💥💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:09:19 </td>
   <td style="text-align:left;"> $TSLA this is still down 30% for the year but $FB is down 43%. In grand picture it hasn’t been hit nearly as hard as I thought it would. I sold a few shares at 1,200. Still holding a 100% gain on this thing. I thought about selling more today to buy some tech and leverage plays but this thing looks like it’s ready to fly more than any of the other beaten down tech stocks. I’m all in holding long term or for life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:08:32 </td>
   <td style="text-align:left;"> $TSLA Wrecking ball arrives when SEC forces Elon to step down from executive member of company. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:07:53 </td>
   <td style="text-align:left;"> $TSLA New insights just appeared:

1. 📜 SEC Form 4: Baglino Andrew D converted options into 1,786 shares and sold $758,316 worth of shares (897 units at $845.39), increasing direct ownership by 5% to 20,138 units
https://quantisnow.com/i/2543727?utm_source=stocktwits
2. 📜 SEC Form 4: Kirkhorn Zachary converted options into 5,623 shares and sold $2,019,639 worth of shares (2,389 units at $845.39), increasing direct ownership by 6% to 59,318 units
https://quantisnow.com/i/2543741?utm_source=stocktwits

#automanufacturing #capitalgoods </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:07:45 </td>
   <td style="text-align:left;"> $TSLA smell the desperation of Tesla Fanboys.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:04:38 </td>
   <td style="text-align:left;"> $TSLA 1000 eow, 1200 eom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:02:14 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $825.0 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 09:00:39 </td>
   <td style="text-align:left;"> $TSLA $850 tomorrow calls at open will pay off can’t wait sweet dreams everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:59:59 </td>
   <td style="text-align:left;"> $MULN  
Keep safe in the market guys... $TSLA  
https://youtu.be/uwSG3-OsK7k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:58:32 </td>
   <td style="text-align:left;"> $TSLA erradicity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:58:22 </td>
   <td style="text-align:left;"> $TSLA  $850 premarket 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:57:24 </td>
   <td style="text-align:left;"> $TSLA https://insideevs.com/news/572065/china-mic-tesla-wholesale-february2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:57:03 </td>
   <td style="text-align:left;"> $TSLA 

it only took two years but wall st bets has produced a trading thesis that is applicable and makes sense. This is going to 420.69. It’s going to be pretty hard on this one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:56:19 </td>
   <td style="text-align:left;"> SweepCast alerted: $TSLA with Unusual Options Activity Alerted on $810 PUT Expiring: 03-11-2022 worth 69K🐻  Learn Unusual Flow SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:55:34 </td>
   <td style="text-align:left;"> $TSLA Why people are buying at 826&amp;#39;s after hours when 827 is the resistance? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:55:31 </td>
   <td style="text-align:left;"> $TSLA Can someone share an Elliot Wave chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:55:17 </td>
   <td style="text-align:left;"> $TSLA Biden treats America like fools... A: we make our own oil prices and B. How would us stopping the oil purchases from Russia leave the blame on Russia for high prices because it would be the exact opposite of Russia’s fault </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:55:05 </td>
   <td style="text-align:left;"> $TSLA cash be nimble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:55:00 </td>
   <td style="text-align:left;"> $TSLA has a good Piotroski-F score of 7.00. This indicates a good health and profitability. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:54:52 </td>
   <td style="text-align:left;"> $TSLA intraday fading has been paying dearly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:53:46 </td>
   <td style="text-align:left;"> $HYZN 

$TSLA $LCID $RIVN $SPY 

https://www.morningbrew.com/emerging-tech/stories/2021/12/13/a-lithium-shortage-is-coming-and-automakers-might-be-unprepared </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:51:59 </td>
   <td style="text-align:left;"> $SPY $TSLA  is runaway stagflation a term? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:48:43 </td>
   <td style="text-align:left;"> $TSLA 
She lied about oil again....... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:46:50 </td>
   <td style="text-align:left;"> $TSLA 860 or 790 tmrr. Tlsa weird af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:46:49 </td>
   <td style="text-align:left;"> $TSLA just got my Rectangle StarLink </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:46:34 </td>
   <td style="text-align:left;"> $TSLA Can still make more lows but price action is very choppy.  It remains in a longer time frame area where a bounce can take place, we don’t like to short sell it in the blue boxes. #Ellliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:46:08 </td>
   <td style="text-align:left;"> Insider Zachary Kirkhorn reports selling 2,389 shares of $TSLA for a total cost of $2,019,639.10 https://fintel.io/n/us/tsla/kirkhorn-zachary?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:45:47 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: Chief Financial Officer Kirkhorn Zachary: 
Disposed 2,389 of Common Stock at price $845.39 and Conv https://s.flashalert.me/746ru </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:45:09 </td>
   <td style="text-align:left;"> $TSLA we’ll see $850 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:45:08 </td>
   <td style="text-align:left;"> $TSLA Form 4 (statement of changes in beneficial ownership of securities) filed with the SEC 

https://newsfilter.io/a/db9ae9e44ca63d1e14b0419324b36fb1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:45:01 </td>
   <td style="text-align:left;"> $SPY $TSLA are there any brave Ukrainians trading options while being shelled by the vodka people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:43:00 </td>
   <td style="text-align:left;"> $TSLA BUY/SELL METER NOW Change 23% + 🚀 https://t8sk.com/TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:42:45 </td>
   <td style="text-align:left;"> $TSLA has global government support to move away from foreign oil, awesome execution, giga berlin start….. is both in Solar and EV… Awesome management… And oil price rising actually benefits this one 🚀🚀🚀 this one can hit ATH and beyond by next earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:42:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:42:21 </td>
   <td style="text-align:left;"> $SPY $TSLA Me when I found out when Russia had a stock market and not use vodka as a currency </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:42:18 </td>
   <td style="text-align:left;"> $TSLA Form 4 (statement of changes in beneficial ownership of securities) filed with the SEC https://newsfilter.io/a/fa30ae2971994682044f0aad44aeccbe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:41:42 </td>
   <td style="text-align:left;"> $TSLA Bears are terrible people who believe Climate change is a hoax. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:39:45 </td>
   <td style="text-align:left;"> $TSLA puts are gonna get slaughtered tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:38:41 </td>
   <td style="text-align:left;"> $SPY $TSLA i smell one more bull trap then an enormous stinky dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:38:25 </td>
   <td style="text-align:left;"> $TSLA moooooooooon!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:37:51 </td>
   <td style="text-align:left;"> $ABML battery metal, folks. This is sooo undervalued. The najarians have been all in on this. ABTC projects $31 pt. Do some DD on this. You won’t regret it. $SPY $QQQ $TSLA $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:37:48 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: SVP Powertrain and Energy Eng. Baglino Andrew D: 
Disposed 897 of Common Stock at price $845.39 and https://s.flashalert.me/QahLa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:37:45 </td>
   <td style="text-align:left;"> Insider Andrew D Baglino reports selling 897 shares of $TSLA for a total cost of $758,315.73 https://fintel.io/n/us/tsla/baglino-andrew-d?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:37:04 </td>
   <td style="text-align:left;"> $TSLA it’s increasing🎈🙌🏿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:34:32 </td>
   <td style="text-align:left;"> $DWAC

I thought you pussies were anti-mask 😂

$AAPL $BA $LMT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:34:14 </td>
   <td style="text-align:left;"> $TSLA 📜 SEC Form 4: Taneja Vaibhav converted options into 3,282 shares and sold $1,297,675 worth of shares (1,535 units at $845.39), increasing direct ownership by 8% to 24,685 units

https://quantisnow.com/i/2543723?utm_source=stocktwits

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:34:12 </td>
   <td style="text-align:left;"> Insider Vaibhav Taneja reports selling 1,535 shares of $TSLA for a total cost of $1,297,675.18 https://fintel.io/n/us/tsla/taneja-vaibhav?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:34:01 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: Chief Accounting Officer Taneja Vaibhav: 
Disposed 1,535 of Common Stock at price $845.39 and Conve https://s.flashalert.me/YlX5hi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:33:26 </td>
   <td style="text-align:left;"> $TSLA FYI THE RECESSION HAS ALREADY STARTED, this will not return to gay ATH this year bubs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:33:25 </td>
   <td style="text-align:left;"> $TSLA Form 4 (statement of changes in beneficial ownership of securities) filed with the SEC 

https://newsfilter.io/a/b4e16027acfd06f750709ce4b2dc23a5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:32:44 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:32:06 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-08 Technical Analysis Video: 
https://www.youtube.com/watch?v=CCdDdmzuBjg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:31:29 </td>
   <td style="text-align:left;"> $DWAC $XOM  $TSLA $GDX yes, even in 2017 we knew all about trump and the russians.   Too bad very few people pay attention. https://newrepublic.com/article/143586/trumps-russian-laundromat-trump-tower-luxury-high-rises-dirty-money-international-crime-syndicate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:31:07 </td>
   <td style="text-align:left;"> $TSLA love how these idiots are buying shares after hours only to sell them as soon as futures dump.  Reading through all the recent court filings, it looks like Musk is trying to get his Consent Judgment set aside, which will not happen.  I think the SEC is seeking to have his ass removed from Tesla.  Keeping buying the dip, Fanboys!!! Moooooon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:31:00 </td>
   <td style="text-align:left;"> $TSLA 

Wen cinematic autonomous drone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:30:57 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TSLA 

Never forget the good times  🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:29:54 </td>
   <td style="text-align:left;"> latexa982a08c21e436bc7a335892dd3acca8tsla ripping 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:29:49 </td>
   <td style="text-align:left;"> $HIMX $tsla &amp;amp;nio China EV sales up 180% YoY in February and expected to hit 5.5 million units sold in 2022

https://news.cgtn.com/news/2022-03-08/Feb-China-s-NEV-sales-up-180-expected-to-hit-5-5m-units-in-2022-18eXSrwQ2Nq/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:29:16 </td>
   <td style="text-align:left;"> $TSLA I see rockets this morning .. $900-1200 PTs for this week. Am waiting.  Pump this please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:28:59 </td>
   <td style="text-align:left;"> $SPY SLAP THAT BIDDD SHORT SELLERS! 📉💥🖐😁👀 Bulls on &amp;quot;SUI&amp;quot; watch after that Bull TRAP today!!! so many chased over $424 - YIKES!!! 🤣🤦‍♂️ $TSLA $SFIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:28:23 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #11 ticker with sweep activity where institutions are trading options urgently with 15.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:28:15 </td>
   <td style="text-align:left;"> $TSLA may be a mini homosexual pump tomorrow but then back to gay bear territory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:28:07 </td>
   <td style="text-align:left;"> $REI wow 😎💰hold strong  longs! Ring Energy’s stock price has definitely not reached it’s peak yet $TSLA $FB $AMD  
https://www.cnbc.com/amp/2022/03/08/russia-warns-of-300-oil-if-ban-goes-ahead-threatens-to-cut-off-european-gas.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:27:34 </td>
   <td style="text-align:left;"> $TSLA bears think they are much smarter than they really are. The way they talk it’s obvious they actually believe they can predict short term accurately. You say the same thing every day and act like you’re smart on the days you happen to be right 🤣. The real and disciplined bulls are forward thinking and don’t have to be right every day, we just need to have balls. Buy shares of good American stocks like Tesla and other clean energy stocks. Wars are won through economics and oil is for the old economy. True it won’t disappear overnight but the time for action here is rapidly approaching and long overdue. This is not about politics, it is about patriotism and the future of humanity. The future is much more important than the unalterable past. Bears are stuck in the past. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:26:03 </td>
   <td style="text-align:left;"> $TSLA DeSantis or Trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:25:44 </td>
   <td style="text-align:left;"> $TSLA doing Tesla thing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:25:44 </td>
   <td style="text-align:left;"> $TSLA  $828🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:24:08 </td>
   <td style="text-align:left;"> $TSLA ok how’s $827 now 🚀🚀🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:23:07 </td>
   <td style="text-align:left;"> $TSLA 800,775,750 😂 today was a big trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:23:01 </td>
   <td style="text-align:left;"> $TSLA I have had enough of this bubble, I want fair value. $80 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:21:48 </td>
   <td style="text-align:left;"> $TSLA let’s see that $826🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:21:10 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TSLA $AAPL the last few months price action explained by Michael Scott </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:18:45 </td>
   <td style="text-align:left;"> $TSLA runnin higher  after hours 🚀🚀🚀🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:18:27 </td>
   <td style="text-align:left;"> $TSLA AOC is the worse. We need a good republican with good policies not that lunatic trump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:17:49 </td>
   <td style="text-align:left;"> $STNE This thing is getting ready to rocket!! $$$20++ EOW fingers crossed!  $TSLA $AMC $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:16:57 </td>
   <td style="text-align:left;"> $IMPP 660% $tsla $oeg $CISO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:16:20 </td>
   <td style="text-align:left;"> $GGPI  
I cant wait for Polestar to be unleashed on the Irish market..... (Gas not being over $10 (€2.07/Ltr) so much to like. Ill be looking to make the move to P2. As for the merger I hope is still at least 2 months away When times are a bit better than now hopefully    
$TSLA  
 https://youtu.be/GGFX8peXpAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:14:30 </td>
   <td style="text-align:left;"> $TSLA Final destination $87.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:14:21 </td>
   <td style="text-align:left;"> $TSLA not gonna lie 😅 I held my puts overnight and I missed this inverted hammer on $SPY daily. We all make mistakes, luckily I held this position and is relatively small compared to the gains we’ve made the past 3 days. Let’s see how it plays out 🤞🏻 on the fence. $QQQ daily looks more like gravestone doji </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:14:03 </td>
   <td style="text-align:left;"> $CXOXF $TSLA 
https://twitter.com/asxsv/status/1501339491424157696?t=Hl-0tqxFhGocP2JXBtf1OQ&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:12:50 </td>
   <td style="text-align:left;"> $WWR a tuit from @Elon_Musk  $TSLA and 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:12:24 </td>
   <td style="text-align:left;"> $TSLA 815 first stop 700 destination </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:11:54 </td>
   <td style="text-align:left;"> $TSLA  TO ALL COMPUTER NERDS ; 
SEND THE TRUTH INTO RUSSIA ANY WAY YOU CAN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:06:58 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY

IN AND OUT. Only puts until rate hikes. All cash now. Tomorrow another day. Love it.  Please hold or pump 😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:06:55 </td>
   <td style="text-align:left;"> $TSLA sad to say this is going back to $800, maniupulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:06:20 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $AAPL Breaking: Blockbuster halts plans on expanding into Russia 🦍🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:06:12 </td>
   <td style="text-align:left;"> latexe2ec99cc7d05982c7869f8679688e72dVIX - 67% call flow 
$NVDA - 68% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 08:00:00 </td>
   <td style="text-align:left;"> $TSLA see ya at 1299 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:59:33 </td>
   <td style="text-align:left;"> $TSLA PLEASE PUMP. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:59:30 </td>
   <td style="text-align:left;"> $TSLA 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:59:20 </td>
   <td style="text-align:left;"> $TSLA movin higher after hours🚀🚀🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:58:58 </td>
   <td style="text-align:left;"> $CEI the problems in this country give me a headache. I need caffeine $PLTR $TSLA $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:58:24 </td>
   <td style="text-align:left;"> $TSLA was thinking if we have a recession how can anyone buy a Tesla, but they can’t even make them fast enough ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:58:06 </td>
   <td style="text-align:left;"> $TSLA shorts like 😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:57:49 </td>
   <td style="text-align:left;"> $TSLA I don’t get it when Democrats are out of office we have to listen to their bullshit narrative and then when they get in it’s just more bullshit narrative... when can we have A fn break you sick fks? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:56:37 </td>
   <td style="text-align:left;"> $TSLA so why isn&amp;#39;t Musk discussing the nickel shortage and prices? Maybe he is too busy playing on Twitter 

A Nickel for Your Ukraine Thoughts https://www.wsj.com/articles/a-nickel-for-your-ukraine-thoughts-russia-metals-market-climate-11646781149 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:54:41 </td>
   <td style="text-align:left;"> $TSLA nice little rebound a long ways to go but good for our long term players!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:54:07 </td>
   <td style="text-align:left;"> $TSLA who tf even knows anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:53:18 </td>
   <td style="text-align:left;"> $TSLA Option Alert.. Massive VOLUME 👀 👀  $900 Call for Friday, March 11. Roughly 6 Million dollars! 💰💰 WOAH 💰💰 Learn more on StockOrbit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:53:16 </td>
   <td style="text-align:left;"> $TSLA Option Alert.. Massive VOLUME 👀 👀  $850 Call for Friday, March 11. Roughly 36 Million dollars! 💰💰💰 MASSIVE MONEY 💰💰💰 Learn more on StockOrbit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:52:02 </td>
   <td style="text-align:left;"> $TSLA I feel like saying nickel is ATH is bearish… Tesla most likely has set price contracts for nicole through the supplier vale. When you’re doing numbers in production you can’t be buying fluctuations most companies set agreements to prevent markets from destroying supply chain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:50:38 </td>
   <td style="text-align:left;"> $TSLA tomorrow we smash thru the 900 resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:49:52 </td>
   <td style="text-align:left;"> $F better than $TSLA Tesla relate to normal people with pricing will be under 500 end of year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:49:38 </td>
   <td style="text-align:left;"> $TSLA nickel is ATH now.. bad news for EV sector </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:48:44 </td>
   <td style="text-align:left;"> $TSLA  low energy company under 500 end of year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:47:23 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #29 ticker with unusual activity from institutional traders with an average of 17% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:46:36 </td>
   <td style="text-align:left;"> $TSLA Tesla Megapack | Soldotna, AK
https://youtu.be/9id7BSPttGs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:43:39 </td>
   <td style="text-align:left;"> $SPY you mother fuckers

14 years later, after hours bullshit 

$SPX $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:43:13 </td>
   <td style="text-align:left;"> $TSLA NEWS - TSLA Ukraine Invasion Affecting Supply Chain For EVs: 
https://www.youtube.com/watch?v=qogswfOVIVg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:42:41 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $TSLA $AAPL 
.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:39:50 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:33:50 </td>
   <td style="text-align:left;"> $TSLA $FB massive green day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:32:39 </td>
   <td style="text-align:left;"> Whoa they came for everyone tonight.... 😳 

$spy $spx $TSLA $nvda $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:31:22 </td>
   <td style="text-align:left;"> $TSLA Your financial advisor can help you process grief after you buy puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:28:52 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ  Tell me one time in history it was a bad decision to buy when the vix was 35 + </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:28:50 </td>
   <td style="text-align:left;"> $TSLA did it just go up at 869 after hours? Sheeesh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:28:36 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $825.0 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:27:11 </td>
   <td style="text-align:left;"> $MULN I think the 450M grant to EV&amp;#39;s would go to $MULN . It would be the best bet. I don&amp;#39;t think it would go to $TSLA because they&amp;#39;re already a profitable, successful business and the extra 450M would give them too much market power. 
 
IDK who the 3rd runner up is but $MULN already has manufacturing plants and the 450M would give them a significant boost to the EV space and give americans additional options outside of $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:24:25 </td>
   <td style="text-align:left;"> $TSLA should be below $ 200 in a fair market. don&amp;#39;t @ me, you pea brains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:23:51 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:23:21 </td>
   <td style="text-align:left;"> $DWAC when do the trials start for the blm and antifa rioters who burned killed and beat up civilians? asking for a friend $tsla $twtr $fb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:21:29 </td>
   <td style="text-align:left;"> $TSLA 825 splitting the two people below </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:20:56 </td>
   <td style="text-align:left;"> $TSLA targeting $791 close tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:20:47 </td>
   <td style="text-align:left;"> $TSLA tomorrow easy 850$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:20:43 </td>
   <td style="text-align:left;"> $TSLA 

The math isn’t sitting correctly here ! 

There’s huge discrepancy between WS estimate n actual numbers Tesla is putting out every Q/Y by 32%  to asses valuation  (FORWARD P/E)! 

More  on that tonight! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:19:43 </td>
   <td style="text-align:left;"> $TSLA my m3 order was delivered on march 3rd. did not go to gas station since nor tracked its prices. Delete gasbuddy app. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:19:38 </td>
   <td style="text-align:left;"> $TSLA I m feeling evil and guilty over watching the dollar go up .92 cents to the Euro this past month while praying the war ends and not wanting it to continue… even if it seems to effect it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:19:18 </td>
   <td style="text-align:left;"> $BTC.X $SPY $USEG $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:17:39 </td>
   <td style="text-align:left;"> $CEI take out a good loan before rates go up so you can pay for gas. Orrrrrr buy a $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:17:10 </td>
   <td style="text-align:left;"> $RIDE when oil hits 300, then lets see where this stock will be at!!! $TSLA is already up and running today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:16:42 </td>
   <td style="text-align:left;"> $AAPL $TSLA $OIL $UCO ➡️ #WTI Just came through with some TREMENDOUS NUMBERS FOR EARNINGS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:16:26 </td>
   <td style="text-align:left;"> $TSLA daily RSI has a very obvious inverse head and shoulders formed now.. ready to rip face </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:15:57 </td>
   <td style="text-align:left;"> $SPY $CL_F $USO $XOM $TSLA 

Who would’ve thought we’d see ATH after this debacle 🤣😂🤣😭🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:12:36 </td>
   <td style="text-align:left;"> $TSLA get it at 800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:12:23 </td>
   <td style="text-align:left;"> $RIDE $tsla $AMC $gme $MSFT...&amp;quot;LOOK!! If you want to sit this out, that&amp;#39;s cool! &amp;quot;BUT YOU DONT PUT IN STOP LOSS ORDERS SO THE MACHINE CAN FK YOU!! going over time × sales today and obviously in  15 minutes of Early  low\slow volume  that happens when traders  are  waiting to see wich way wind blows! MM\Machine\AI\Artificial intelligence Swooped Down And Ate You Up! I see the MM picked up 25k shares @ $2.00 and then took it too $1.99 for a couple token 100 share trades...&amp;quot;STOP LOSS ORDERS ARE FOR FKEN LOOSERS!!!! WAKE THE FK UP! LETTING THE MM WIN IS Like LETTING A LYING STEALING POLITICIAN and his Tv network  BRAIN WASH YOUR STUPID SOUL!..The Machine\ MM is filled with lots of Data (book value) for example! Every time their is a &amp;quot;lull&amp;quot; it&amp;#39;s Stealin Time! And your The &amp;quot;Mark&amp;quot; with your &amp;quot;stop loss order&amp;quot; ..telegraph any financial future move you make @ what do you think results will be when it comes to money?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:09:50 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-08 Daily Forecast Video: 
https://www.youtube.com/watch?v=RTRArzZdM20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:09:45 </td>
   <td style="text-align:left;"> $TSLA https://www.thestreet.com/technology/tesla-may-be-worth-4-trillion-very-soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:09:10 </td>
   <td style="text-align:left;"> $TSLA 

This is way undervalued even by the dummies on  WS with their standard stupid metrics !!  
Very cheap !! 

That’s why I’m loading heavily !! 

Look ahead, don’t be caught with this short term weakness !0.02
🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:08:23 </td>
   <td style="text-align:left;"> $TSLA This should really drive up Tesla stock https://youtu.be/zKX5NGu8kM4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:07:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla tells U.S. lawmakers Autopilot requires &amp;#39;constant monitoring&amp;#39; https://www.stck.pro/news/TSLA/24078640 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:06:18 </td>
   <td style="text-align:left;"> $HYMC told you gonna runnnn!!!! Keep going.   Gonna hit $3’s tomorrow $OAS gonna fly again $TSLA gonna take 8% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:03:26 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:02:39 </td>
   <td style="text-align:left;"> $TSLA 
Price is still at a bearish channel,we are yet to see any CHOC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:02:24 </td>
   <td style="text-align:left;"> $TSLA McDonald&amp;#39;s, Starbucks, Coca-Cola join corporate America’s exit from Russia https://finance.yahoo.com/news/mc-donalds-joins-corporate-americas-exit-from-russia-with-closure-of-850-restaurants-183619416.html?soc_src=social-sh&amp;amp;soc_trk=tw&amp;amp;tsrc=twtr via @Yahoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 07:02:06 </td>
   <td style="text-align:left;"> $TSLA 
Bull case- musk taking this private at 1000000 pps target price 37479034
 
Bear case- your position turns to a college loan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:57:47 </td>
   <td style="text-align:left;"> $TSLA 
What’s wrong with u tards whole market tanks and u pin this to $800 get ready for a $100 drop out of nowhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:56:33 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $TSLA $AAPL 
Just 1 litre price in Euros </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:56:14 </td>
   <td style="text-align:left;"> $TSLA https://techcrunch.com/2021/07/22/tesla-bhp-ink-supply-deal-for-nickel-ahead-of-demand-surge/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:56:02 </td>
   <td style="text-align:left;"> $TSLA 

Why do you think, 90-95% beginner traders lose money? Because, they just want the stock picks without knowing when to enter &amp;amp; exit. Join my Small Account Challenge discord for “live” day trading! Rest, HIT THAT FOLLOW
💸💸💸💰💰💰💥💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:55:28 </td>
   <td style="text-align:left;"> $SPY Is it 2024 yet? Need some pumping,  we got the best cars and bestest planes in the whole world ...so great .. so great ..$TSLA $SPCE $BA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:54:45 </td>
   <td style="text-align:left;"> latexe7c82c2ed2d40185efe1463886fb4bf5, need to break 889$...!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:54:28 </td>
   <td style="text-align:left;"> $TSLA this will hit 860 after an hour. No, maybe? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:54:25 </td>
   <td style="text-align:left;"> $TSLA $900 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:54:01 </td>
   <td style="text-align:left;"> $TSLA 2000 tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:52:44 </td>
   <td style="text-align:left;"> $TSLA 820-900 tomorrow then 700 Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:52:00 </td>
   <td style="text-align:left;"> $TSLA has one of the better Altman-Z scores in its industry: 17.64 vs 2.24. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:51:54 </td>
   <td style="text-align:left;"> $TSLA eat my ass market im not selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:51:20 </td>
   <td style="text-align:left;"> $TSLA Was strong today but I hope you didn&amp;#39;t overstay your welcome. I say that because price ran into Hourly Supply (Yellow) at 849.00 and dropped 30 points or over 3% from that zone.  
 
Optionsforecast4u.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:51:05 </td>
   <td style="text-align:left;"> $TSLA tomorrow it will be 869 sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:50:45 </td>
   <td style="text-align:left;"> $TSLA I’m not selling any Tesla til it tops 3k next year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:50:36 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 3/8/2022 $SPY $XLF $QQQ $TAN $TSLA https://www.chartguys.com/daily-market-videos/4188/trading-the-whipsaw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:49:32 </td>
   <td style="text-align:left;"> $TSLA 1000 baby LFG! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:49:20 </td>
   <td style="text-align:left;"> $TSLA do you guys trade tesla option calss every day .... like buying and selling same day or next day ... if so ... how u will determine entry points by charts and support ... ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:49:12 </td>
   <td style="text-align:left;"> $TSLA why is it up???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:48:30 </td>
   <td style="text-align:left;"> $SPY $TSLA BUY AMERICAN OIL!!!  $IMPP AMERICAN OIL!!!!  USA USA USA!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:45:29 </td>
   <td style="text-align:left;"> $TSLA New support 820? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:45:04 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-model-y-became-the-best-selling-ev-in-the-world-in-january-2022 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:44:10 </td>
   <td style="text-align:left;"> $TSLA people across the pond are getting mad at my jokes and blocking me left and right. Just gonna address the whole lot of you- I’m sorry, wankers😂. Oh btw your parliment totally 100% controls it’s own prices on oil and gas- just like the pussyoles in the whitehouse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:43:37 </td>
   <td style="text-align:left;"> $TSLA maybe if I make a YouTube channel and shitpost everyday about tesla going to the moon then the bulls will like me. 🤣 here’s a list of DANGEROUS people to be leery of following on Stocktwits. They have all blocked me despite me being dead ass accurate just because I have an opposing view! Narrow minded echo chamber clowns!!!

@meetjoeblackbeard
@johnboy75
@bignews
@vinodstrademk
@hoopster34
@oefvet
@azliving21
@brandonnnn
@novusordoseclorum
@swingtrader0000
@agi777
@eboy6666
@kndihopefull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:43:08 </td>
   <td style="text-align:left;"> $TSLA #CYRN WHAT A DAY! ☄️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:42:24 </td>
   <td style="text-align:left;"> $TSLA land mine or dragonfly 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:41:24 </td>
   <td style="text-align:left;"> $TSLA great moves today! 900-1000 by eow, if not tomorrow 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:41:13 </td>
   <td style="text-align:left;"> $TSLA @elonmusk news to help Ukraine with free internet is very generous and also GENIUS. Tesla needs to go back above $893 to confirm a rally towards $2k  
 
iTradeAI™ is not a financial advisor. 
 
#stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:41:07 </td>
   <td style="text-align:left;"> $TSLA short covering tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:40:53 </td>
   <td style="text-align:left;"> $TSLA $760s by end of week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:39:17 </td>
   <td style="text-align:left;"> $TSLA most undervalued stock in the market 😊 💰 💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:38:05 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;ve made a lot of money from tsla up and down but am almost always wrong about the medium term. This stock is like a massive option induced mess. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:37:52 </td>
   <td style="text-align:left;"> $TSLA wow that Put and Call Options is going up and down just crazy at the end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:37:03 </td>
   <td style="text-align:left;"> $TSLA I would like to give a shout-out to myself for buying Calls this morning before the reversal happened and buying Puts right at the resistance level, $849. And to those who did the same, &amp;quot;YOU&amp;#39;RE THE MAN/WOMAN!!! I&amp;#39;m not trying to brag or anything, but when it comes to Trading Tesla, I am the market!!! Bears or Bulls, get MONEY!!! Shout-out to the Market Makers!! Great job!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:36:43 </td>
   <td style="text-align:left;"> $TSLA this will go to 1000 by end of week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:35:13 </td>
   <td style="text-align:left;"> $TSLA Option Alert.. 👀 👀  $800 Put for Friday, March 18. Roughly 2 Million dollars! 💰💰💰💰 Learn more on StockOrbit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:34:59 </td>
   <td style="text-align:left;"> I think we may see sub SP 4000 maybe touch 3900s… then reverse…. Writing here to time stamp it … lots of buyers at the 20% draw down .. 

🚨 $SPY $AAPL $TSLA $DIS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:34:51 </td>
   <td style="text-align:left;"> $TSLA great swing just like I called it this morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:33:58 </td>
   <td style="text-align:left;"> $TSLA yes $MULN is competition. They have a great future ahead ... So your DD!! 

https://insideevs.com/news/550234/mullen-five-reservation-limit-25000/amp/. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:32:23 </td>
   <td style="text-align:left;"> $SPY $DWAC $TSLA Joe Biden’s America is not for me, weak and pathetic will create a depression the likes of which never seen before. I’m applying for Russian citizenship </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:32:19 </td>
   <td style="text-align:left;"> $TSLA If you&amp;#39;re going to buy within this volatility, make sure you have the proper risk vs. reward ratio in place: https://youtu.be/CytzoL2ec14 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:31:51 </td>
   <td style="text-align:left;"> $TSLA I’m not here to toot my own horn but damnit did I nail that shit.. can’t believe I’m posting these trades for free 😫😫😫 up $85k in the last 3 trading days just check my posts 🥱  shorting tesla is too easy. 

$ENSV $BMBL $USEG $CYRN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:31:44 </td>
   <td style="text-align:left;"> $TSLA How Tesla may finish 2022? I am avg 1160$ and 55 shares 😄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:31:32 </td>
   <td style="text-align:left;"> $TSLA take out 850 tomorrow, 900 by friday 🚀🚀🚀🚀🚀😁👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:31:06 </td>
   <td style="text-align:left;"> $TSLA when’s the next Covid spike? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:30:55 </td>
   <td style="text-align:left;"> $NVAX $NIO $AMC $GME $TSLA  https://www.youtube.com/watch?v=jQRb4DZnhn8&amp;amp;ab_channel=10HoursMovies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:30:46 </td>
   <td style="text-align:left;"> $TSLA $tsla is in solar and EV both areas with new spending and support from EU and US to get rid of foreign oil dependency… seems like this should head back to ATH in next few weeks 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:30:17 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC I wish I were gay and not a white male so this administration would care about me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:30:17 </td>
   <td style="text-align:left;"> $SPY $AMD $AMZN $AAPL $TSLA  🧞‍♂️💲🧞‍♂️

Stay Long here 🚀🚀🚀🚀🚀🚀🚀🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:29:08 </td>
   <td style="text-align:left;"> $SPY $DWAC $TSLA Putin knows Joe Biden is weak and pathetic and will attack as he pleases </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:28:36 </td>
   <td style="text-align:left;"> $TSLA there was no shipping crisis or oil shortage- America produced more barrels of oil and shipped more containers than any other year in history last year... ripple effect of people sitting on their asses waiting for a virus to go away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:27:11 </td>
   <td style="text-align:left;"> $TSLA today&amp;#39;s high was $849.99 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:26:35 </td>
   <td style="text-align:left;"> $PLTR remember, when I got $TSLA in the beginning I was down 50-60% as well in the early days. Same with $NIO. It’s the skin you need to really profit handsomely. Hold. Don’t sell. Wait </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:26:14 </td>
   <td style="text-align:left;"> $SPY $TSLA Rolex ,Lamborghini and Ferrari pull out of selling in Russia! 😂🤑 Sucks to be a friend of #Putin #russia #rolex #lambo #vroom ⌚️🏎🏎🏎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:25:46 </td>
   <td style="text-align:left;"> $SHOP Today’s 515-520 buyers may get lucky with this- 50:50 like a coin toss; Oversold hard bounce will come eventually at some point. $SPY $ROKU $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:24:50 </td>
   <td style="text-align:left;"> $PLTR just sold a bunch of $TSLA and $AAPL stocks for $500k worth. Time to consolidate. Adding them here the rest of the month. Not sure if I’ll post as actively as I have </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:23:59 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA    could this be planned,?🤔make people buy more electric cars. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:23:01 </td>
   <td style="text-align:left;"> $TSLA 750 dead imminent off market shits itself tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:22:12 </td>
   <td style="text-align:left;"> $TSLA Lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:21:16 </td>
   <td style="text-align:left;"> $TSLA sh*t is about to get real fanboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:20:41 </td>
   <td style="text-align:left;"> $IMPP AMERICAN OIL TO THE RESCUE!!!!!!! USA USA USA!!! $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:20:22 </td>
   <td style="text-align:left;"> $TSLA announce the stock split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:18:20 </td>
   <td style="text-align:left;"> $TSLA don’t be sheeple - people! Fk the Democrat narrative </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:17:26 </td>
   <td style="text-align:left;"> $DWAC our country desperately needs young and handsome president’s trump elite negotiating skills and firm leadership $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:17:06 </td>
   <td style="text-align:left;"> $GGPI now is a good time to drop that merger date. Oil and energy popped, EVs next. $LCID $FSR $TSLA $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:16:20 </td>
   <td style="text-align:left;"> latex18359d1b04ba0c2a540e7ca890168fefAMD ↗️ 

$AAPL $BTC.x $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:12:10 </td>
   <td style="text-align:left;"> $TSLA how do people still own slaves? ☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:12:03 </td>
   <td style="text-align:left;"> $SPY $DWAC $TSLA I wish weak and pathetic Joe Biden loved everyday Americans as much as he loves illegals and crack addicts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:11:58 </td>
   <td style="text-align:left;"> $IMPP AMERICAN OIL!!!!!!!!  USA USA USA!!!!! $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:11:25 </td>
   <td style="text-align:left;"> $TSLA how’s everyone doing I’d like to thank this stock for assisting into a 50% gain in my doomsday account today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:11:02 </td>
   <td style="text-align:left;"> $TSLA $SPY my neighbor use to ride his gas powered motor bike and make hella noise… it’s been quiet lately Lolol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:10:35 </td>
   <td style="text-align:left;"> $SPY 
What happend to all the bullish chit chat? 
😕 😞 

$QQQ $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:08:16 </td>
   <td style="text-align:left;"> $TSLA https://www.channelchek.com/news-channel/EV_Inflation_Outpacing_Traditional_Cars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:07:51 </td>
   <td style="text-align:left;"> $TSLA oil has been rising for the entire past year and the president called it Putin’s price hike- 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:07:25 </td>
   <td style="text-align:left;"> $SPY $TSLA REMEMBER, BANNING RUSSIAN OIL JUST HURTS US CONSUMERS!!!!  OIL PRICES WILL SKYROCKET TO $150 BY EOW!!! BUY AMERICAN OIL!!!  $IMPP AMERICAN OIL!!  USA USA USA!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:06:28 </td>
   <td style="text-align:left;"> $TSLA 2x x 2 on puts. Dont give up longs. I will make $$ in the interim. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-09 06:05:41 </td>
   <td style="text-align:left;"> $TSLA hey ransomware actors we are watching you 🥸 </td>
  </tr>
</tbody>
</table></div>

---
