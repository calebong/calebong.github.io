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

[View the latest Economic Forecasts](/pdf/Monthly-Market-Outlook--Jan-2022-.pdf)

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



Last Updated: 2022-01-18 14:41:53 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 14:36:00 </td>
   <td style="text-align:left;"> New Zealand Stocks Subdued </td>
   <td style="text-align:left;"> The S&amp;P/NZX 50 was little changed on Tuesday, with traders putting their attention to reports that business mood in New Zealand fell in Q4 amid acute labor shortages triggered by pandemic restrictions as well as persistent inflation pressure. The Reserve Bank of New Zealand raised interest rates for the second straight month in November and warned of more hikes. At the same time, market participants continued to keep their eyes on local COVID-19 situations as health officials are in the process of reviewing the number of people allowed at gatherings. Prime Minister Jacinda Arden said yesterday that it was a "case of when, not if" New Zealand had an Omicron outbreak. Shares of ikeGPS Group Limited gained 8.2% and those of New Zealand Oil &amp; Gas added 6.45% amid declines in Marlin Global Limited (-5.79%) and Greenfern Industries Limited (-4.65%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-18 14:35:12 </td>
   <td style="text-align:left;"> Germany 10Y Bond Yield Hits 32-month High </td>
   <td style="text-align:left;"> Germany 10 Year Government Bond Yeld increased to a 32-month high of -0.009% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 14:24:24 </td>
   <td style="text-align:left;"> Australian Shares Fall as Bond Yields Weigh </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index fell 0.11% to close at 7,409 on Tuesday, reversing gains from earlier in the session as equities came under pressure from rising global bond yields. The benchmark 10-year yield in Australia rose to November 2021 highs around 1.93% on Tuesday, tracking a steady rise in global yields as major economies start normalizing monetary policies this year. Sentiment was also dented after Australian consumer confidence slid to its lowest since October 2020 amid the soaring Covid cases. Healthcare, consumer and financial stocks led the declines, with losses from CSL Ltd (-1.57%), Sonic Healthcare (-0.45%), Commonwealth Bank (-0.37%), Magellan Financial (-2.44%) and Redbubble Ltd (-22.41%). On the virus front, Australia recorded its worst day in Covid deaths on Monday with 74 fatalities, but new cases were seen declining. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/methanol </td>
   <td style="text-align:left;"> 2022-01-18 13:58:22 </td>
   <td style="text-align:left;"> Methanol Hits 4-week High </td>
   <td style="text-align:left;"> Methanol increased to a 4-week high of 2683 CNY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 13:44:48 </td>
   <td style="text-align:left;"> US Futures Slip on Rising Bond Yields </td>
   <td style="text-align:left;"> US stock futures slipped on Tuesday as Treasury yields climbed higher, while investors awaited a fresh batch of corporate earnings reports. Dow and S&amp;P 500 futures fell 0.2% and 0.5%, respectively, while Nasdaq 100 futures lost 1%. The benchmark US 10-year yield climbed to pre-pandemic highs above 1.8% this week on expectations of interest rate hikes in the US. The shortened trading week will also feature quarterly reports from index heavyweights including UnitedHealth, Bank of America, Netflix, Morgan Stanley and Goldman Sachs. Of the 26 S&amp;P 500 companies that have reported fourth-quarter earnings so far, nearly 77% posted better-than-expected results. Forward guidance from companies has also been largely positive for 2022 despite disruptions from the omicron on some businesses. Analysts argued that earnings and business performance become increasingly more important in an environment of rising interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60034050?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-18 13:19:47 </td>
   <td style="text-align:left;"> China's Xi Jinping defends 'common prosperity' crackdowns </td>
   <td style="text-align:left;"> Chinese president Xi Jinping has made a rare defence on the world stage of his "common prosperity" policy, which has seen major crackdowns on businesses.                                                                                                                                                 , His comments came during the World Economic Forum's (WEF) annual meeting of government and corporate leaders.                                                                                                                                                                                             , China says the policy is aimed at narrowing the widening wealth gap, which could threaten the Communist Party's rule if left unaddressed.                                                                                                                                                                 , Technology, education and entertainment firms have been hit by the crackdowns.                                                                                                                                                                                                                            , "The common prosperity we desire is not egalitarianism," Mr Xi told delegates.                                                                                                                                                                                                                            , "We will first make the pie bigger and then divide it properly through reasonable institutional arrangements. As a rising tide lifts all boats, everyone will get a fair share from development, and development gains will benefit all our people in a more substantial and equitable way," he continued., The measures put in place by the common prosperity policies are seen by some as a way to rein in the billionaire owners of some of China's biggest companies to instead give customers and workers more of a say in how firms operate and distribute their earnings.                                      , But with its implementation, billions of dollars have been wiped off the value of some of China's biggest companies as Beijing imposed tough new regulations on them, which has rattled international investors.                                                                                          , During his address Mr Xi moved to ease some of those concerns as he said the country is still open to investment from overseas.                                                                                                                                                                           , "All types of capital are welcome to operate in China, in compliance with laws and regulations, and play a positive role for the development of a country," he said.                                                                                                                                      , Due to the pandemic this year's WEF annual meeting is being held online, rather than at the Swiss resort of Davos.                                                                                                                                                                                        , Mr Xi's comments came as he is expected to be appointed for a third term in office later this year.                                                                                                                                                                                                       , That would cement his position as an equal to Mao Zedong, the founder of the Chinese People's Republic, and his successor Deng Xiaoping, who oversaw major reforms to the country's economy.                                                                                                              , Meanwhile, the Beijing Winter Olympics Games are due to start next month at a time when China is facing international criticism on a number of fronts including for encroaching on democratic freedoms in Hong Kong, its treatment of the Uyghur minority in Xinjiang and its stance on Taiwan.           , This video can not be played                                                                                                                                                                                                                                                                              , Five phrases attributed to famous figures, but did they even say them?!                                                                                                                                                                                                                                   , Specially curated tracks to soothe your mind and spirit                                                                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-01-18 13:17:09 </td>
   <td style="text-align:left;"> Dollar Climbs on Hawkish Fed Expectations </td>
   <td style="text-align:left;"> The dollar index traded firmly above 95.2 on Tuesday, extending a bounce from recent lows as the hawkish US rates outlook remained intact ahead of the Federal Reserve’s January meeting. The US central bank is set to meet on Jan. 25-26, and although it is not expected to move rates, there has been strong hawkish commentary coming from policymakers. Fed chair Jerome Powell said last week that the US economy is ready for the start of tighter monetary policy, while other Fed officials signaled the first potential rate hike in March. Meanwhile, the benchmark 10-year Treasury yield climbed to pre-pandemic highs above 1.8%% this week, lifting the dollar further. The US consumer price index also rose 7% in December from a year earlier, accelerating at its fastest pace in nearly four decades and bolstering the case for a more aggressive tightening by the Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-18/blackrock-ceo-says-nothing-woke-about-stakeholder-capitalism?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-18 13:10:14 </td>
   <td style="text-align:left;"> BlackRock CEO Says Nothing ‘Woke’ About Stakeholder Capitalism </td>
   <td style="text-align:left;"> Larry Fink                                                                                                                                                                                                                 , Silla Brush                                                                                                                                                                                                                , BlackRock Inc. Chief Executive Officer Larry Fink urged companies to engage with all stakeholders to secure long-term profitability, defending his approach to capitalism as the head of the world’s largest asset manager., In his annual letter to CEOs, Fink said capitalism is driven by mutually beneficial relationships “between you and the employees, customers, suppliers, and communities your company relies on to prosper.”  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-01-18 13:08:00 </td>
   <td style="text-align:left;"> Gold Pressured by Rising Yields, Dollar </td>
   <td style="text-align:left;"> Gold traded just below $1,820 an ounce on Tuesday, easing from recent highs as US Treasury yields and the dollar gained on firm hawkish expectations from the Federal Reserve. The benchmark 10-year Treasury yield climbed to pre-pandemic highs above 1.8%% this week, while the dollar index recouped some losses to trade back above the 95 level. The moves came after Fed chair Jerome Powell said last week that the US economy was ready for the start of tighter monetary policy, with other Fed officials signaling the first potential rate hike in March. The US consumer price index also rose 7% in December from a year earlier, accelerating at its fastest pace in nearly four decades and bolstering the case for a more aggressive tightening by the Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/brent-climbs-above-7-year-high-on-mideast-tensions-tight-supply </td>
   <td style="text-align:left;"> 2022-01-18 13:05:32 </td>
   <td style="text-align:left;"> Brent climbs above 7-year high on Mideast tensions, tight supply </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                              , SINGAPORE - Oil prices rose more than $1 on Tuesday to a more than seven-year high on worries about possible supply disruptions after Yemen's Houthi group attacked the United Arab Emirates, escalating hostilities between the Iran-aligned group and a Saudi Arabian-led coalition.                                         , The "new geopolitical tension added to ongoing signs of tightness across the market," ANZ Research analyst said in a note.                                                                                                                                                                                                     , Brent crude futures rose $1.01, or 1.2%, to $87.48 a barrel by 0316 GMT, after earlier hitting a peak of $87.55, their highest since Oct. 29, 2014.                                                                                                                                                                            , GAS PRICES SEEING 'CALM BEFORE THE STORM,' GASBUDDY ANALYST WARNS                                                                                                                                                                                                                                                              , U.S. West Texas Intermediate (WTI) crude futures jumped $1.32, or 1.6%, from Friday's settlement to a three-month high of $85.14 a barrel. Trade on Monday was subdued as it was a U.S. public holiday.                                                                                                                        , After launching drone and missile strikes which set off explosions in fuel trucks and killed three people, the Houthi movement warned it could target more facilities, while the UAE said it reserved the right to "respond to these terrorist attacks."                                                                       , Oil prices rose more than $1 on Tuesday, Jan. 18 2022, to a more than seven-year high on worries about possible supply disruptions after Yemen's Houthi group attacked the United Arab Emirates, escalating hostilities between the Iran-aligned group and                                                                     , UAE oil firm ADNOC said it had activated business continuity plans to ensure uninterrupted supply of products to its local and international customers after an incident at its Mussafah fuel depot.                                                                                                                           , CommSec analysts said oil prices were being supported by colder winter temperatures in the northern hemisphere which were driving up demand for heating fuels.                                                                                                                                                                 , The tight supply-demand balance is unlikely to ease, analysts said, as some producers within the Organization of the Petroleum Exporting Countries are struggling to pump at their allowed capacities, due to underinvestment and outages, under an agreement with Russia and allies to add 400,000 barrels per day each month., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                    , "That should continue to be supportive for oil and increase talk of triple figure prices," said OANDA analyst Craig Erlam. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 13:04:00 </td>
   <td style="text-align:left;"> India Equities Retreat </td>
   <td style="text-align:left;"> The BSE Sensex fell 313 points or 0.51% to 60,991 on Tuesday, amid worries that March will be the start of a tightening cycle in the US. Locally, Prime Minister Narendra Modi said Monday that a collective global effort is needed to deal with the problems posed by cryptocurrencies. India's central bank has also voiced concerns around digital currencies, saying that they may impact financial stability. Traders overlooked reports that India's capital Delhi and financial hub Mumbai had reported a big fall in COVID-19 infections in the past two days and that India's Gennova Biopharmaceuticals is working on an Omicron-specific mRNA vaccine candidate. On Monday, the index finished at a near 11-month high, supported by gains from UltraTech Cement following its upbeat earnings reports.  Markets now await earnings from heavyweight Bajaj Finance later in the day as the third-quarter earnings season entered its second week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/18/mexico-tv-host-anti-vaxxer-rant-hgt-sot-intl-ovn-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-18 12:51:57 </td>
   <td style="text-align:left;"> Mexican TV host unloads on anti-vaxxers in on-air rant - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/industrial-production-mom </td>
   <td style="text-align:left;"> 2022-01-18 12:42:00 </td>
   <td style="text-align:left;"> Japan Industrial Output Growth Hits Record Peak </td>
   <td style="text-align:left;"> Industrial production in Japan jumped 7.0 percent month-on-month in November 2021, compared to a flash reading of a 7.2 percent surge and accelerating sharply from a 1.8 percent rise in the previous month. This marked the second straight month of increase in industrial output and the strongest growth on record, with contribution from the production of motor vehicles leading the way as it benefited from a recovery in global parts supply (43.7 percent vs 15.9 percent in October), followed by that from plastic products (9.7 percent vs 0.6 percent) and iron, steel and non-ferrous metals (6.3 percent vs -2.3 percent). On a yearly basis, industrial output soared 5.1 percent in November, the first yearly increase in the three months, after a 4.1 percent drop in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-18/hsbc-warns-h-k-traders-on-quarantine-after-splitting-teams?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-18 12:25:12 </td>
   <td style="text-align:left;"> HSBC Splits Hong Kong Team to Different Locations to Manage Quarantine Risks </td>
   <td style="text-align:left;"> The HSBC Holdings Plc headquarters at night in Hong Kong.                                                                                                                                                                                                                                                                                                                               , Denise Wee                                                                                                                                                                                                                                                                                                                                                                              , HSBC Holdings Plc warned traders that one of the main risks to business continuity is the city’s quarantine policy as the Asian financial hub tightens to contain a fifth wave of infections.                                                                                                                                                                                           , Hong Kong, which is pursuing a Covid Zero strategy to match mainland China, has employed some of the strictest measures in the world to keep infections at bay. Authorities have sent close contacts of positive cases to quarantine camps for several weeks and also banned flights from eight countries, on top of mandating 21 days in hotel isolation for most incoming travelers.   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-18/china-s-spreading-property-contagion-adds-pressure-on-xi-to-ease?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-18 12:24:59 </td>
   <td style="text-align:left;"> China’s Spreading Property Debt Crisis Pressures Xi to Ease </td>
   <td style="text-align:left;"> Sofia Horta e Costa                                                                                                                                                                                                                                                                                                                                                                                                                                     ,  and Rebecca Choong Wilkins                                                                                                                                                                                                                                                                                                                                                                                                                             , Financial contagion is roaring back in China’s property industry, putting renewed pressure on Xi Jinping’s government to do more to insulate the nation’s stronger developers.                                                                                                                                                                                                                                                                          , Monday was the worst day on record for dollar bonds of Country Garden Holdings Co., China’s largest developer by sales. Some of its notes fell to as low as 62 cents, while its shares sank to an almost five-year low. The selloff also spread to stronger issuers like Longfor Group Holdings Ltd. and China Vanke Co. for the first time, as well as China’s bad-debt managers amid concern over their exposure to the property market, traders said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-18 12:09:00 </td>
   <td style="text-align:left;"> South Korea 10Y Bond Yield Hits 3-1/2-year High </td>
   <td style="text-align:left;"> South Korea 10 Year Government Bond Yield increased to a 3-1/2-year high of 2.598%, on the back of a global rise in bond yields as expectations of hawkish stance at the Fed's upcoming meeting strengthened. At the same time, fears deepened over a drastic upsurge in infections from the Omicron variant ahead of the Lunar New Year holiday, as daily virus cases climbed back above 4,000 Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/17/business/dealbook/larry-fink-blackrock-letter.html </td>
   <td style="text-align:left;"> 2022-01-18 12:00:05 </td>
   <td style="text-align:left;"> Larry Fink’s Letter to CEOs Says Stakeholder Capitalism Is Not ‘Woke’ - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                 , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                  , Larry Fink’s latest annual letter to corporate America clarifies, and defends, his approach to social and environmental issues at the world’s largest money manager.                                                                                                                                                                                                                                                                          , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                       , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                , By Andrew Ross Sorkin and Michael J. de la Merced                                                                                                                                                                                                                                                                                                                                                                                             , Laurence D. Fink, the founder and chief executive of the investment giant BlackRock, has become one of the most influential voices in business over the past decade in pushing corporate leaders to think beyond profits, to their social purpose.                                                                                                                                                                                            , Mr. Fink has delivered his words in annual letters that have drawn remarkable attention, but also criticism from all corners: that he is beholden to politically correct antibusiness activists, or that he is co-opting these issues for marketing purposes.                                                                                                                                                                                 , On Monday night, he used his latest letter to corporate America to clarify — and defend — his approach.                                                                                                                                                                                                                                                                                                                                       , “Stakeholder capitalism is not about politics,” Mr. Fink wrote to the chief executives of businesses that BlackRock has invested in. “It is not ‘woke.’ It is capitalism.”                                                                                                                                                                                                                                                                    , Mr. Fink’s annual letter is widely followed, and this year’s 3,300-word edition is sure to be read in boardrooms and beyond.                                                                                                                                                                                                                                                                                                                  , On Friday, BlackRock said it managed more than $10 trillion in assets, across an array of index funds, pension plans and other investment products, cementing the firm’s position as the world’s largest asset manager. That gives Mr. Fink a huge amount of influence: If a public company that BlackRock has invested in ignores his calls, his firm could seek to oust its directors or, among its actively managed funds, sell its shares., So when Mr. Fink began urging chief executives four years ago to consider how they contributed to society, his words carried weight. Within weeks of his telling leaders in 2020 that climate change would become a “defining factor” in how BlackRock assessed their companies, many blue-chip businesses announced plans to become carbon-neutral or carbon-negative.                                                                       , In this year’s letter, Mr. Fink urged chief executives to continue embracing their moral responsibility as the pandemic reshapes society and business, and as consumers and workers demand more from companies.                                                                                                                                                                                                                               , But in perhaps the most telling sentence, he said that what drove his push for companies to have purpose was creating profits. “Make no mistake, the fair pursuit of profit is still what animates markets; and long-term profitability is the measure by which markets will ultimately determine your company’s success,” he wrote.                                                                                                          , Much of this year’s letter was devoted to Mr. Fink’s belief that a focus on environmental, social and corporate governance issues — E.S.G., for short — does not conflict with making money. Reducing a company’s carbon footprint, for example, makes the business more resilient in the long term, which is in investors’ interests.                                                                                                        , “We focus on sustainability not because we’re environmentalists, but because we are capitalists and fiduciaries to our clients,” Mr. Fink wrote.                                                                                                                                                                                                                                                                                              , He suggested that E.S.G. was not a fad but a permanent feature of the corporate world. Business leaders who do not adapt to the new reality, he suggested, risk being overtaken by younger and more innovative rivals in step with the times.                                                                                                                                                                                                 , “Capital markets have allowed companies and countries to flourish. But access to capital is not a right,” he wrote. “It is a privilege. And the duty to attract that capital in a responsible and sustainable way lies with you.”                                                                                                                                                                                                             , But some critics say Mr. Fink and BlackRock are not pushing companies hard enough to go green. Environmental groups have called out what they see as shortcomings in Mr. Fink’s approach: BlackRock’s Big Problem, a collection of nonprofits and other advocates, accuses the firm of failing to exclude major polluters from its investment funds, even in E.S.G.-focused products.                                                         , In his latest letter, Mr. Fink defended his more gradual approach, including a refusal to force BlackRock to divest holdings in fossil-fuel companies. (He has said in the past that the firm cannot rid many of its mainstream funds of holdings in companies that are part of major stock indexes.)                                                                                                                                         , “Divesting from entire sectors — or simply passing carbon-intensive assets from public markets to private markets — will not get the world to net zero,” he wrote. Focusing solely on cutting down on the supply of oil and gas, and not reducing the demand for fossil fuels, would simply drive up energy prices and encourage more of a backlash against green-energy efforts, he argued.                                                  , BlackRock has also faced pressure from the opposite end of the climate spectrum. Last year, Texas lawmakers passed a bill that, on paper, would block the state’s agencies from investing public money with financial companies, like BlackRock, if they were to “boycott energy companies.”                                                                                                                                                  , “If Wall Street turns their back on Texas and our thriving oil and gas industry, then Texas will not do business with Wall Street,” Lt. Gov. Dan Patrick, a supporter of the bill, posted on Twitter last year.                                                                                                                                                                                                                               , Mr. Fink’s letter did not address the Texas bill, and to date the state has not cut off BlackRock. He also said the firm would offer individual investors more ability to vote its shares, something BlackRock has been under pressure to do, especially by Republican lawmakers who have complained that the firm has too much influence. BlackRock is making it easier for institutions to vote themselves as well.                         , “We are pursuing an initiative to use technology to give more of our clients the option to have a say in how proxy votes are cast at companies their money is invested in,” Mr. Fink wrote. “We now offer this option to certain institutional clients, including pension funds that support 60 million people.”                                                                                                                              , Along with his push for companies to focus more on climate, he repeated a call on governments and multinational organizations like the World Bank to be more supportive of investments in green energy.                                                                                                                                                                                                                                       , “Businesses can’t do this alone,” Mr. Fink wrote, “and they cannot be the climate police.”                                                                                                                                                                                                                                                                                                                                                    , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-18/europe-s-smelters-call-for-action-to-combat-soaring-energy-costs?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-18 12:00:00 </td>
   <td style="text-align:left;"> Europe’s Smelters Call for Action to Combat Soaring Energy Costs </td>
   <td style="text-align:left;"> Mark Burton                                                                                                                                                                                                                                                                                                    , A group of Europe’s leading metal producers has called on the continent’s politicians to deploy a package of measures including state aid and tapping national gas reserves to ease the regional power crisis and avert further smelter shutdowns.                                                             , Eurometaux, which represents producers including Glencore Plc, Rio Tinto Group and Norsk Hydro ASA, sent a letter to the European Commission warning that more producers could be forced to cut output or shutter plants entirely without additional support to protect smelters from the surge in power costs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-18 11:44:00 </td>
   <td style="text-align:left;"> WTI Crude Nears 2021 High </td>
   <td style="text-align:left;"> WTI crude futures traded around $85 per barrel on Tuesday, nearing a multi-year high of $85.41 reached in October 2021 as the bull run in oil prices showed no signs of slowing down. Oil prices continued to trend higher amid concerns over tightness in the oil market, with investors shrugging off a potential hit to fuel demand from the omicron variant. Fears about possible supply disruptions were also stoked after Yemen’s Houthi group attacked the United Arab Emirates, escalating hostilities between the Iran-aligned group and a Saudi Arabian-led coalition. Moreover, oil prices rallied even after China recently agreed with the US to release crude oil from its strategic stockpiles around the Lunar New Year, in a bid by major consumers to lower energy prices. Analysts said supply tightness is unlikely to ease as some OPEC+ member countries are struggling to pump at their allowed capacities due to underinvestment and outages. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-01-18 11:37:10 </td>
   <td style="text-align:left;"> Brent Hits 7-Year High </td>
   <td style="text-align:left;"> Brent crude futures hit a 7-year high to trade above $86.72 per barrel on Tuesday, as the bull run in oil prices showed no signs of slowing down. Oil prices continued to trend higher amid concerns over tightness in the oil market, with investors shrugging off a potential hit to fuel demand from the omicron variant. Fears about possible supply disruptions were also stoked after Yemen’s Houthi group attacked the United Arab Emirates, escalating hostilities between the Iran-aligned group and a Saudi Arabian-led coalition. Moreover, oil prices rallied even after China recently agreed with the US to release crude oil from its strategic stockpiles around the Lunar New Year, in a bid by major consumers to lower energy prices. Analysts said supply tightness is unlikely to ease as some OPEC+ member countries are struggling to pump at their allowed capacities due to underinvestment and outages. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60034140?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-18 11:18:42 </td>
   <td style="text-align:left;"> Hong Kong police charge two former aircrew over Covid rules </td>
   <td style="text-align:left;"> Hong Kong police say two former flight attendants have been arrested and charged for allegedly breaking the city's coronavirus restrictions.                                                                                              , Police said the two had "conducted unnecessary activities" when they should have been in home isolation.                                                                                                                                  , They both later tested positive for the fast-spreading Omicron variant.                                                                                                                                                                   , The airline they worked for has not been named but it comes after Cathay Pacific fired two aircrew who were suspected of breaching Covid rules.                                                                                           , Police said that the two arrested flight attendants returned to Hong Kong from the US on 24 and 25 December.                                                                                                                              , They have been released on bail with their case scheduled to be heard on 9 February.                                                                                                                                                      , If convicted, they could face up to six months in prison and a fine of up to HK$5,000 (£470; $642).                                                                                                                                       , Cathay Pacific, which is Hong Kong's flagship carrier, has faced claims that its aircrew were responsible for the initial spread of Omicron in the city.                                                                                  , Hong Kong chief executive Carrie Lam last week singled out the airline and ordered probes into allegations that its aircrew broke pandemic regulations.                                                                                   , In response, Cathay's chairman Patrick Healy reportedly told staff that non-compliance of a "tiny minority" must not "overshadow the remarkable discipline and professionalism" of the majority of its aircrew.                           , Hong Kong has continually adjusted its quarantine rules for air crew as it pursues mainland China's zero Covid policy.                                                                                                                    , The city dramatically tightened its regulations after the emergence of Omicron last year, leading to Cathay cancelling most of its planned passenger and cargo flights in January.                                                        , Even before the tougher rules were imposed the airline had been struggling to staff many of its flights, as some routes relied on pilots volunteering to fly rosters that involved being confined to hotel rooms for five weeks at a time., Cathay pilots have previously told the BBC how the rules have affected their mental health and put a strain on their personal lives, with one saying that he was "in a perpetual state of quarantine."                                    , This video can not be played                                                                                                                                                                                                              , Five phrases attributed to famous figures, but did they even say them?!                                                                                                                                                                   , Specially curated tracks to soothe your mind and spirit                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/interest-rate </td>
   <td style="text-align:left;"> 2022-01-18 11:08:00 </td>
   <td style="text-align:left;"> Japan Holds Rates, Changes View on Inflation Risks </td>
   <td style="text-align:left;"> The Bank of Japan left its key short-term interest rate unchanged at -0.1% and that for 10-year bond yields around 0% during its January meeting, by an 8-1 vote, as widely expected. In a quarterly outlook report, meanwhile, the central bank adjusted its view of inflation risks for the first time since 2014, raising its inflation forecasts for FY 2022 that begin in April to 1.1% from earlier forecasts of 0.9% made in October, amid soaring costs of energy and raw material. Policymakers noted that risks to the price outlook were evenly balanced, with signs of a rise in inflation broadening. The board also revised higher the projected growth for FY 2022 to 3.8% from earlier projections of 2.9%, reflecting massive stimulus from the government; but lowered the  GDP growth for the current FY to 2.8% from 3.4%, amid lingering supply constraints. The BoJ stressed that it will maintain its ultra-loose monetary policy even as its global counterparts seek to exit from crisis-mode policies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-18/crude-markets-run-hot-in-asia-as-omicron-fails-to-dent-demand?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-18 11:07:38 </td>
   <td style="text-align:left;"> Crude Markets Run Hot in Asia as Omicron Fails to Dent Demand </td>
   <td style="text-align:left;"> Sharon Cho                                                                                                                                                                                                                                                                                                                                                                  , The physical crude market in Asia is showing further signs of strength, bolstering the outlook for higher futures prices just as global oil benchmark Brent rallies to the highest level in seven years.                                                                                                                                                                    , Prices of Russian crudes are the latest signal of the sustained market bullishness. Spot differentials for Sokol that are scheduled to be shipped in March rose by at least 40 cents a barrel from the previous trade, while the premium commanded by ESPO crude -- a favorite grade among Chinese processors -- surged to the highest since November, according to traders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-18/edf-hit-with-rating-warnings-after-france-acts-on-energy-crisis?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-18 10:58:38 </td>
   <td style="text-align:left;"> EDF Hit With Rating Warnings After France Acts on Energy Crisis </td>
   <td style="text-align:left;"> David Stringer                                                                                                                                                                                                                                                                                                                            , Electricite de France SA had a credit rating cut and was warned over further downgrades after the state-controlled utility was ordered to sell more power at a steep discount under action to tackle Europe’s energy crisis.                                                                                                              , EDF plunged after President Emmanuel Macron’s government moved last week to limit increases in electricity bills for households and small businesses. The plan could cost EDF as much as 8.4 billion euros ($9.6 billion) and some analysts expect the firm to raise capital as a result of that action and new outages at nuclear plants. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-18/boj-stands-pat-changes-long-held-view-on-inflation-risks?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-18 10:55:49 </td>
   <td style="text-align:left;"> BOJ’s Cautious Price Forecasts Likely to Cool Normalization Talk </td>
   <td style="text-align:left;"> Toru Fujioka                                                                                                                                                                                                                       ,  and Sumio Ito                                                                                                                                                                                                                     , Sign up for the New Economy Daily newsletter, follow us @economics and subscribe to our podcast.                                                                                                                                   , The Bank of Japan adjusted its view of inflation risks for the first time since 2014 but only nudged up its price forecasts a fraction, a combination that suggests moves toward phasing out stimulus are still a distant prospect. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 10:44:22 </td>
   <td style="text-align:left;"> China Stocks Edge Higher on Policy Easing Boost </td>
   <td style="text-align:left;"> The Shanghai Composite rose 0.4% to around 3,555 while the Shenzhen Component gained 0.5% to 14,440 on Tuesday, a day after the Chinese central bank cut key policy rates to cushion a slowing economy. The People’s Bank of China slashed interest rates on 1-year MLF loans and 7-day reverse repos by 10 basis points to 2.85% and 2.1%, respectively, on Monday as the country’s GDP growth slowed in the 4th quarter of 2021. The decision contrasted with other major economies which are on track to normalize monetary settings this year, prompting Chinese president Xi Jinping to caution against a rapid rise in global interest rates in the Davos Agenda virtual event on Monday. He warned that policy tightening by major economies would present challenges to global economic and financial stability, with developing countries bearing the brunt. Technology, industrial and consumer staples led the market, with notable gains from Beijing Egova (13%), Zhewen Interactive (3%) and Kweichow Moutai (2.1%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cotton </td>
   <td style="text-align:left;"> 2022-01-18 10:43:00 </td>
   <td style="text-align:left;"> Cotton Hits 7-week High </td>
   <td style="text-align:left;"> Cotton increased to a 7-week high of 120 USd/Lbs, not far from its 9-½-year peak of 119.2 USd/Lbs hit on November 15th amid expectations of firm demand, particularly from China and tight supplies. An urgency in obtaining the supplies and a buyout of cotton futures by hedge funds also supported the cotton market. Meanwhile, farmers in top producer India held on to production as heavy rains hit the quality of crop. Elsewhere, USDA in its latest report estimated 2021/22 global production to drop by 608,000 bales as lower production in the US and India offset increases for China, Australia and Pakistan. The 2021/22 global consumption forecast is virtually unchanged as a 500,000-bale decline in China’s cotton use is offset by gains for India, Mexico, and Pakistan. Global ending stocks for 2021/22 are down 726,000 bales this month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-18/top-carmaker-shutdowns-hint-more-to-come-in-covid-zero-china?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-18 10:35:04 </td>
   <td style="text-align:left;"> Top Carmaker Shutdowns Hint More to Come in Covid-Zero China </td>
   <td style="text-align:left;"> River Davis                                                                                                                                                                                                                                 , China’s zero tolerance approach to Covid has idled Toyota Motor Corp. and Volkswagen AG factories the past week, a troubling sign for global carmakers as the omicron variant begins to spread in the world’s biggest auto production hub.  , The two top-selling carmakers’ factories in Tianjin, 108 kilometers (67 miles) southeast of Beijing, have been halted since Jan. 10 as the local government carries out multiple rounds of mass testing for the city’s 14 million residents. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/china-car-sector-falling-short-of-net-zero-goals-greenpeace </td>
   <td style="text-align:left;"> 2022-01-18 10:16:08 </td>
   <td style="text-align:left;"> China car sector falling short of 'net zero' goals: Greenpeace </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                         , SHANGHAI - China's massive car sector is on track to bring its climate-warming carbon dioxide emissions to a peak by 2027 but on current trends it is unlikely to meet the country's 2060 "net zero" target, environment group Greenpeace said on Tuesday., The sector's total carbon emissions are likely to plateau at 1.75 billion tonnes, and will steadily drop 11% by 2035, Greenpeace estimated in a research report.                                                                                          , But it will need to cut emissions by at least 20% by 2035 if it is to stay on track towards net zero by 2060, Greenpeace said.                                                                                                                            , WEST VIRGINIA DUMPS BLACKROCK FUND OVER ANTI-ENERGY STANCE                                                                                                                                                                                                , China needs to bring zero emissions vehicle sales to 63% by 2030 and 87% by 2035 if it is to meet its targets, the environmental group estimated.                                                                                                         , "The ideal response is for car makers in China to completely phase out internal combustion engine vehicles by 2030," said Bao Hang, project leader for Greenpeace Asia in Beijing.                                                                        , Cars drive on the road during the morning rush hour in Beijing, China, July 2, 2019. REUTERS/Jason Lee                                                                                                                                                    , China said in a 2021-2035 development plan for the sector in late 2020 that pure electric vehicles should make up 20% of sales by 2025 and then become the "mainstream" by 2035.                                                                          , The country's cabinet said in an action plan on bringing emissions to a peak last year that total new and clean energy vehicle sales should reach around 40% of the total by 2030.                                                                        , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                   , Chinese sales of battery-powered electric vehicles, plug-in petrol-electric hybrids and hydrogen fuel-cell vehicles grew 157.5% to 3.52 million units in 2021, official data showed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-18/china-s-property-sector-contraction-worsens-in-blow-to-economy?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-18 10:11:07 </td>
   <td style="text-align:left;"> China’s Property Sector Contraction Worsens in Blow to Economy </td>
   <td style="text-align:left;"> China’s property sector shrank at a faster pace in the final three months of last year as the country’s housing slump continues to take its toll on the economy.                                                                                                                          , Output in the real-estate sector shrank 2.9% in the fourth quarter after a 1.6% contraction in the previous three months, the National Bureau of Statistics said Tuesday in a supplemental report on gross domestic product. That was the first consecutive quarterly decline since 2008.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-01-18 10:06:00 </td>
   <td style="text-align:left;"> Brent Hits 7-year High </td>
   <td style="text-align:left;"> Brent increased to a 7-year high of 86.85 USD/Bbl, amid mounting concerns over supply constraints as the OPEC+ are gradually relaxing output cuts implemented when demand collapsed in 2020. News that Russia was preparing to attack Ukraine if diplomacy failed also supported bullish sentiment, along with signs that the Omicron strain will not be as disruptive to fuel demand as previously feared. At the same time, market participants paid little attention to reports that China plans to release oil reserves around the Lunar New Year holidays between January 31st and February 6th as part of a plan coordinated by the US. Meanwhile, Libya's total oil output is back to 1.2 million barrels per day after a blockade by petroleum guards ended, according to National Oil Corp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 09:45:05 </td>
   <td style="text-align:left;"> Japanese Shares Rise as BOJ Meeting Eyed </td>
   <td style="text-align:left;"> The Nikkei 225 Index rose 0.6% to around 28,500 while the broader Topix Index edged up 0.45% to 1,995 on Tuesday, as Japanese stocks extended the previous session’s gains with broad market participation, while investors awaited fresh policy signals from the central bank meeting. The Bank of Japan is widely expected to raise its growth and inflation forecasts after it concludes a 2-day monetary policy meeting today, while keeping interest rates unchanged. However, a Reuters article said that Japanese policymakers are debating how soon they can start signaling an eventual rate hike, which could come even before inflation hits the 2% central bank target amid broadening price increases and a more hawkish Federal Reserve. Nearly all sectors of the market advanced, with notable gains from Lasertec (2.7%), Toyota (1.4%), Fast Retailing (3.4%), Kawasaki Kisen (1.3%) and Recruit Holdings (1.8%), among others. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 09:13:03 </td>
   <td style="text-align:left;"> Australian Shares Climb on Tech, Mining Boost </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index rose 0.25% to around 7,435 on Tuesday, helped by gains in technology and mining stocks, while investors continued to monitor Covid-related developments closely. Australian technology firms led the market higher, with notable gains from Brainchip Holdings (13.5%), Afterpay (0.3%) and Xero Ltd (2.2%). Heavyweight miners and lithium explorers also advanced ahead of quarterly production figures, including BHP Group (1.7%), Fortescue Metals (1.4%), Pilbara Minerals (2.8%), South32 Ltd (3.2%) and Allkem Ltd (4.6%). Elsewhere, Rio Tinto lagged behind its peers after the company posted a 5.4% drop in its fourth-quarter iron ore shipments, partly hit by lower demand from top consumer China. On the virus front, Australia recorded its worst day in Covid deaths on Monday with 74 fatalities, but new cases were seen declining. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 08:37:59 </td>
   <td style="text-align:left;"> US Futures Steady Ahead of Earnings Reports </td>
   <td style="text-align:left;"> US stock futures were steady on Tuesday as investors awaited a fresh batch of corporate earnings reports. Dow and S&amp;P 500 futures were little changed, while Nasdaq 100 futures were also flat. US markets were closed Monday for the Martin Luther King holiday. The shortened trading week will feature quarterly reports from index heavyweights including UnitedHealth, Bank of America, Netflix, Morgan Stanley and Goldman Sachs. Of the 26 S&amp;P 500 companies that have reported fourth-quarter earnings so far, nearly 77% posted better-than-expected results. Forward guidance from companies has also been largely positive for 2022 despite disruptions from the omicron on some businesses. Meanwhile, investors remained concerned over the recent inflationary surge and the prospect of tighter monetary policy from the Federal Reserve. Analysts argued that earnings and business performance become increasingly more important in an environment of rising interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/17/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-01-18 07:01:31 </td>
   <td style="text-align:left;"> U.S. stock futures are little changed ahead of more earnings reports </td>
   <td style="text-align:left;"> , U.S. stock futures were little changed Monday night as traders braced for the latest batch of corporate earnings reports.                                                                                                                                                                                                                      , Futures tied to the Dow Jones Industrial Average ticked higher by 33 points, or 0.1%. S&amp;P 500 futures rose 0.1%, and Nasdaq 100 futures slipped marginally. U.S. markets were closed Monday due to the Martin Luther King holiday.                                                                                                             , The shortened trading week will feature quarterly reports from 35 companies in the S&amp;P 500, including Bank of America, UnitedHealth and Netflix. Goldman Sachs is also set to post its most-recent quarterly figures Tuesday before the bell.                                                                                                  , Major banks Wells Fargo, JPMorgan Chase and Citigroup kicked off the earnings season on Friday, with the three companies posting better-than-expected profits. However, the market's reaction to those results was mixed. Wells Fargo shares posted a gain on the back of those results, but JPMorgan Chase and Citigroup slid.                , Overall, 26 S&amp;P 500 companies have reported calendar fourth-quarter earnings thus far, according to Refinitiv. Of those companies, nearly 77% posted bottom-line results that beat analyst expectations.                                                                                                                                       , Goldman Sachs has a bunch of new buy-rated stocks — and says 5 have upside of more than 90%                                                                                                                                                                                                                                                    , Hedge fund manager says Ark ETF stocks are a potential 'time bomb'                                                                                                                                                                                                                                                                             , Morgan Stanley thinks time spent in cars will jump by 25% by 2030, and these stocks will benefit                                                                                                                                                                                                                                               , "The economic backdrop to the fourth quarter was positive, boding well for profit and revenue growth," UBS Global Wealth Management CIO Mark Haefele said in a note last week. "Guidance from companies also looks set to point to continued demand strength in 2022, even if omicron is disrupting some businesses right now."                , The spread of the omicron Covid-19 variant has raised questions over the state of the global economic recovery ever since news of its discovery broke. Some countries and regions reinstated lockdowns and other social distancing measures to curb the outbreak.                                                                              , However, recent data indicates the spread may be easing. In New York the seven-day average of daily new cases has been falling since hitting a record earlier this month, according to data compiled by Johns Hopkins University. In Maryland, daily infections are down 27% week over week. Cases are also falling in South Africa and the UK., Monday's moves come as equities have struggled to start 2022.                                                                                                                                                                                                                                                                                  , The Dow, S&amp;P 500 and Nasdaq Composite are all down for the year amid concerns over the recent inflationary surge and the prospect of tighter monetary policy from the Federal Reserve.                                                                                                                                                         , Philadelphia Fed President Patrick Harker told CNBC last week that the central bank could raise rates three or four times this year. He noted that inflation is "more persistent than we thought a while ago."                                                                                                                                 , Tech, the biggest S&amp;P 500 sector by market cap, has been hit especially hard this year, falling more than 4%. Big Tech names like Meta Platforms, Amazon, Netflix, Alphabet and Apple are all down year to date.                                                                                                                               , Subscribe to CNBC PRO for exclusive insights and analysis, and live business day programming from around the world.                                                                                                                                                                                                                            , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/17/chamath-palihapitiya-says-nobody-cares-about-uyghur-genocide-in-china.html </td>
   <td style="text-align:left;"> 2022-01-18 07:00:19 </td>
   <td style="text-align:left;"> Billionaire investor Chamath Palihapitiya says 'nobody cares' about Uyghur genocide in China </td>
   <td style="text-align:left;"> , WASHINGTON – Billionaire investor Chamath Palihapitiya triggered a backlash on social media after saying during a recent episode of his podcast that "nobody cares" about the ongoing human rights abuses against the Uyghurs in China.                                                                                                                                                                                                     , During a 90-minute episode, Palihapitiya told co-host Jason Calacanis on their "All-In" podcast that he would be lying if he said that he cared about the Uyghurs, an ethnic Muslim minority in China's northwest region of Xinjiang.                                                                                                                                                                                                       , "Every time I say that I care about the Uyghurs, I'm really just lying if I don't really care. And so, I'd rather not lie to you and tell you the truth, it's not a priority for me," said Palihapitiya, a venture capitalist who owns 10% of the NBA team the Golden State Warriors.                                                                                                                                                       , The team wrote in a statement on Twitter Monday that Palihapitiya "does not speak on behalf of our franchise, and his views certainly don't reflect those of our organization." The Golden State Warriors' statement did not mention the Uyghurs or China.                                                                                                                                                                                  , Calacanis and Palihapitiya began talking about the Uyghurs when Calacanis praised President Joe Biden's foreign policy approach to China.                                                                                                                                                                                                                                                                                                   , The Biden administration has described the abuse of Uyghurs and members of other Muslim minorities in the region as "widespread, state-sponsored forced labor" and "mass detention." The Biden administration has also warned businesses with supply chain and investment ties to Xinjiang that they could face legal consequences.                                                                                                         , In July, that warning manifested as a joint advisory from the Departments of State, Treasury, Commerce, Homeland Security and Labor, along with the Office of the U.S. Trade Representative. The most-pointed line from the Xinjiang Supply Chain Business Advisory states that "businesses and individuals that do not exit supply chains, ventures, and/or investments connected to Xinjiang could run a high risk of violating U.S. law.", The Chinese government has previously denied any wrongdoing or human rights abuses in Xinjiang.                                                                                                                                                                                                                                                                                                                                             , About 15 minutes into the podcast, Calacanis pointed to the Biden administration's steps to curb and address China's sweeping human rights abuses when the following conversation ensued:                                                                                                                                                                                                                                                   , Calacanis: His [President Biden's] China policy, the fact that he came out with a statement on the Uyghurs, I thought it was very strong.                                                                                                                                                                                                                                                                                                   , You know, it's one of the stronger things he did, but it's not coming up in the polls.                                                                                                                                                                                                                                                                                                                                                      , Palihapitiya: Let's be honest, nobody, nobody cares about what's happening to the Uyghurs, okay? You bring it up because you really care. And I think that's really nice that you care but ...                                                                                                                                                                                                                                              , Calacanis: What? What do you mean nobody cares?                                                                                                                                                                                                                                                                                                                                                                                             , Palihapitiya: The rest of us don't care. I'm just telling you a very hard truth.                                                                                                                                                                                                                                                                                                                                                            , Calacanis: Wait, you personally don't care?                                                                                                                                                                                                                                                                                                                                                                                                 , Palihapitiya: I'm telling you a very hard truth, okay? Of all the things that I care about. Yes, it is below my line. Okay, of all the things that I care about it is below my line.                                                                                                                                                                                                                                                        , Calacanis: Disappointing.                                                                                                                                                                                                                                                                                                                                                                                                                   , Palihapitiya went on to say that he cared about supply chain issues, climate change, America's crippled health-care system as well as the potential economic fallout of a Chinese invasion of Taiwan.                                                                                                                                                                                                                                       , He later clarified his remarks in a Monday evening tweet, saying he recognizes that he came across as "lacking empathy."                                                                                                                                                                                                                                                                                                                    , "As a refugee, my family fled a country with its own set of human rights issues so this is something that is very much a part of my lived experience," said Palihapitiya, who was born in Sri Lanka. "To be clear, my belief is that human rights matter, whether in China, the United States, or elsewhere. Full stop."                                                                                                                    , Last month, the White House announced a diplomatic boycott of the 2022 Winter Olympics in Beijing, citing "ongoing genocide and crimes against humanity in Xinjiang and other human rights abuses."                                                                                                                                                                                                                                         , Governments, civil society groups and United Nations officials have previously expressed concern over Beijing's harsh measures of repressing those who criticize the Chinese Communist Party.                                                                                                                                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/17/business/airlines-5g-warning.html </td>
   <td style="text-align:left;"> 2022-01-18 06:57:27 </td>
   <td style="text-align:left;"> Airlines Warn of Chaos if AT&amp;T and Verizon Deploy 5G Expansion - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                             , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                              , Thousands of planes could be grounded because the new internet technology interferes with sensors, the industry reiterated in a letter to federal officials.                                                                                                                                                                                                                                                                                              , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                   , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                            , By Jack Ewing                                                                                                                                                                                                                                                                                                                                                                                                                                             , Two days before Verizon and AT&amp;T plan to deploy more segments of their new 5G mobile internet technology, leaders of the nation’s largest air carriers warned again on Monday that thousands of flights could be grounded by interference from the technology and that “the nation’s commerce will grind to a halt.”                                                                                                                                      , In unusually sharp terms, the airline industry implied in a letter to Transportation Secretary Pete Buttigieg and other top federal officials that Verizon’s and AT&amp;T’s plans could add to the disruptions in the global shipping network that have fueled inflation.                                                                                                                                                                                     , High-speed 5G internet uses so-called C-band frequencies close to those used by aircraft to measure their altitude. The airlines say the technology can interfere with the instruments and create a serious safety hazard. Verizon and AT&amp;T have argued that the aviation industry had years to upgrade any equipment that might be affected.                                                                                                             , The protest by the chief executives of Delta Air Lines, American Airlines, United Airlines and seven other passenger and cargo carriers threw into question a deal reached this month between the Federal Aviation Administration and the telecommunications companies. The F.A.A. said it would not object to a rollout of the new technology after the companies promised to address safety concerns by reducing power at 5G transmitters near airports., The airline executives said in their letter on Monday, which was reported earlier by Reuters, that aircraft manufacturers had informed them in recent weeks that the measures promised by Verizon and AT&amp;T were not enough to prevent interference with aircraft sensors. They asked that the 5G technology not be activated within two miles of 50 major airports.                                                                                       , “Multiple modern safety systems on aircraft will be deemed unusable,” according to the letter, which carried the letterhead of Airlines for America, an industry group. “Airplane manufacturers have informed us that there are huge swaths of the operating fleet that may need to be indefinitely grounded,” stranding thousands of passengers and worsening turmoil in the supply chain, the airlines said.                                            , “Immediate intervention is needed to avoid significant operational disruption to air passengers, shippers, supply chain and delivery of needed medical supplies,” said the letter, which was also signed by the chief executives of FedEx Express and UPS Airlines.                                                                                                                                                                                       , In a statement on Monday, the F.A.A. said it “will continue to keep the traveling public safe as wireless companies deploy 5G” and “continues to work with the aviation industry and wireless companies to try and limit 5G-related flight delays and cancellations.”                                                                                                                                                                                     , Spokesmen for AT&amp;T and Verizon declined to comment.                                                                                                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-17/stocks-set-for-cautious-start-yen-dips-before-boj-markets-wrap </td>
   <td style="text-align:left;"> 2022-01-18 05:59:45 </td>
   <td style="text-align:left;"> Stocks, U.S. Futures Wilt as Treasury Yields Surge: Markets Wrap </td>
   <td style="text-align:left;"> WATCH: Two interest rate hikes by the Federal Reserve this year is more likely than four, says Christopher Smart, chief global strategist at Barings.                                                                                                                                                                 , Sunil Jagtiani                                                                                                                                                                                                                                                                                                        , U.S. equity futures retreated and Asian stocks struggled Tuesday amid a jump in Treasury yields as investors girded for interest-rate hikes by the Federal Reserve to quell high inflation.                                                                                                                           , Treasuries fell across the curve, pushing two-year and 10-year yields up to levels last seen before the pandemic roiled markets. Pressure is growing for the Fed to act more quickly to contain price pressures, which are being stoked in part by a rally in oil that’s taken Brent crude to the highest since 2014.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/17/tonga-volcano-eruption-orig-tp-jc.cnn </td>
   <td style="text-align:left;"> 2022-01-18 05:45:09 </td>
   <td style="text-align:left;"> Tonga volcano: Video shows underwater eruption a day before tsunami - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 05:26:31 </td>
   <td style="text-align:left;"> Brazilian Equities Fall to Start the Week </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, fell 0.3% to close at 106,275 on Monday, amid lower trading volumes from closed equity markets in the United States. At the same time, Brazilian petrochemical producer Braskem slipped over 6% after it filed with the Securities and Exchange Commission on Friday for a share offering in which Petrobras and Novonor will sell their stakes in the petrochemical company. Traders also monitor the possibility of an escalation in the pressure of civil servants for salary readjustments, given the potential fiscal impact. Meanwhile, Central Bank of Brazil’s market expectations survey for 2022 showed growth projections were raised marginally to 0.29% from 0.28%, while inflation forecasts were revised higher to 5.09% from 5.03%. On the data front, the IBC-Br index of economic activity in Brazil rose by a more-than-expected 0.69% from a month earlier in November, after four consecutive months of drops and the most since last February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 05:21:13 </td>
   <td style="text-align:left;"> Canadian Shares at 7-week High </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite Index was 0.8% higher to hover around 21,537 on Monday, its highest since November 25th, amid lower trading volumes from closed equity markets in the United States, supported by upbeat global sentiment and strong performing energy and banking sectors. Financial stocks were 1.2% higher, carried by the Royal Bank of Canada (1.2%) and the Bank of Nova Scotia (1%), while energy shares jumped 1.7% tracking higher oil prices. On the economic data front, Canada reported that foreign investors acquired C$30.2 billion in Canadian securities during November of 2021, surpassing market expectations for the highest reading since April of 2020. At the same time, manufacturing sales were 2.6% higher on the month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/california-proposal-double-taxes </td>
   <td style="text-align:left;"> 2022-01-18 03:44:30 </td>
   <td style="text-align:left;"> California weighing proposal that could double its taxes </td>
   <td style="text-align:left;"> U-Haul Vice President Stuart Shoen argues that last year's 'mass outflow' of people from California led to the most significant 'inability for us to meet our customer demand.'                                                                                                                                                                                                                                                                      , California lawmakers unveiled a new bill at the beginning of the year that would establish a single-payer health care system – an ambitious plan that would be funded by nearly doubling the state's already-high taxes.                                                                                                                                                                                                                             , A new analysis from the Tax Foundation, a non-partisan group that generally advocates for lower taxes, found that the proposed constitutional amendment would increase taxes by roughly $12,250 per household in order to fund the first-of-its-kind health care system. In all, the tax increases are designed to raise an additional $163 billion per year, which is more than California raised in total tax revenue any year before the pandemic., WHICH STATES HAVE THE HIGHEST, LOWEST TAX BURDEN?                                                                                                                                                                                                                                                                                                                                                                                                    , The proposal includes three main revenue raisers, according to Jared Walczak, a fellow at the Tax Foundation: Higher income taxes on wealthy Americans, a payroll tax on certain employees' wages for large companies, and a new gross receipts tax.                                                                                                                                                                                                 , California Gov. Gavin Newsom leaves a news conference in Sacramento, California, on Jan. 10, 2022. (AP Photo/Rich Pedroncelli / AP Newsroom)                                                                                                                                                                                                                                                                                                         , Under the bill, the top marginal rate on wage income would soar to 18.05% – well above the median top marginal rate of 5.3% and the state's existing rate of 12.3%. There would be an 18-bracket system, with higher taxes kicking in for individuals earning more than $149,509.The highest rate would apply to those who earn more than $2,484,121.                                                                                                , Here's a closer look at how the tax system would be structured, based on individual income:                                                                                                                                                                                                                                                                                                                                                          , California would also expand the payroll tax paid by employees who earn more than $49,990 in annual income if they work for a company that has more than 50 workers. Walczak noted the plan could deter small businesses from expanding by inadvertently creating a tax cliff. For instance, if a company that had 49 workers earning $80,000 each hired one additional employee, they would suddenly create a tax bill of more than $90,000.        , Hollywood Boulevard.                                                                                                                                                                                                                                                                                                                                                                                                                                 , Finally, the state would also adopt a new 2.3% gross receipts tax (GRT) on qualified businesses minus the first $2 million in annual gross receipts, at a rate more than three times that of the country's current highest GRT.                                                                                                                                                                                                                      , Walczak noted the proposed tax increases come as California grapples with a high number of residents who are leaving for red states with lower tax burdens. A separate Tax Foundation analysis based on Census Bureau data shows that California's population actually declined 0.8% in 2021, even as states with lower taxes saw their populations increase.                                                                                        , "Practically doubling state taxes—even if the burden is partially offset through state-provided health coverage—could send taxpayers racing for the exits," Walczak wrote.                                                                                                                                                                                                                                                                           , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                          , The taxes would fund government-run health care for all Californians, which supporters say would offset the costs of higher taxes and would save money in the long run.                                                                                                                                                                                                                                                                              , Gov. Gavin Newsom, a Democrat, has said that he supports single-payer health care in the past, although he has not commented on this specific proposal. The Assembly Bill 1400 was sponsored by Assemblyman Ash Kalra. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/west-virginia-dumps-blackrock-fund-over-anti-energy-stance </td>
   <td style="text-align:left;"> 2022-01-18 03:37:27 </td>
   <td style="text-align:left;"> West Virginia dumps BlackRock fund over anti-energy stance </td>
   <td style="text-align:left;"> Charlie Gasparino weighs in on 'Cavuto: Coast to Coast' as BlackRock's China investing fuels questions                                                                                                                                                                                                                                                                                                                                   , West Virginia state Treasurer Riley Moore announced Monday that his state would end the use of a BlackRock Inc. investment fund over the firm's push for climate-focused investment strategies that Moore says threaten his state's economy.                                                                                                                                                                                             , "As the state’s chief financial officer and chairman of the Board of Treasury Investments, I have a duty to ensure that taxpayer dollars are managed in a responsible, financially sound fashion which reflects the best interests of our state and country, and I believe doing business with BlackRock runs contrary to that duty," Moore said in a statement.                                                                         , West Virginia State Treasurer Riley Moore ( West Virginia )                                                                                                                                                                                                                                                                                                                                                                              , GASBUDDY ANALYST WARNS ‘IT’S GOING TO BE AN UGLY YEAR' FOR PRICES                                                                                                                                                                                                                                                                                                                                                                        , The treasurer's press release explained that the decision came in reaction to reports that BlackRock "has urged companies to embrace ‘net zero’ investment strategies that would harm the coal, oil and natural gas industries, while increasing investments in Chinese companies that subvert national interests and damage West Virginia's manufacturing base and job market."                                                         , Last month, educational nonprofit Consumers' Research sent a letter to ten governors, including the governor of West Virginia, whose state pension funds are most invested with BlackRock, warning about the money management firm's heavy investments in China.                                                                                                                                                                         , "BlackRock’s funneling of billions in U.S. capital to China carries with it risks not present in other markets, risks that threaten the large wagers the company is putting on steep returns from the Middle Kingdom," Consumers' Research Executive Director Will Hild wrote in the letter.                                                                                                                                             , "Chinese firms are not held to the same transparency standards as their western counterparts, so foreign investors are often hard pressed to appreciate the true risk profile of what they’re investing in," Hild added.                                                                                                                                                                                                                 , BlackRock offices in New York City. Founded in 1988, BlackRock, Inc. is a US multinational investment management corporation.  (Erik McGregor/LightRocket via Getty Images / Getty Images)                                                                                                                                                                                                                                               , BLACKROCK INVESTMENTS IN CHINA: CONSUMERS' RESEARCH WARNING CONSUMERS, GOVERNMENTS                                                                                                                                                                                                                                                                                                                                                       , A BlackRock spokesperson told FOX Business at the time that the U.S. and China "have a large and interconnected economic relationship."                                                                                                                                                                                                                                                                                                  , "We recognize that our stakeholders have differing views on China — BlackRock takes those concerns seriously," the spokesperson explained. "We seek to balance the concerns of our stakeholders with our role as a global investor and fiduciary working for our clients as we navigate this very complicated relationship between the US and China. Our approach to Chinese-related investments is consistent with U.S. foreign policy.", BlackRock, the largest money manager in the world with more than $10 trillion in assets under management, announced in January 2021 that it had signed on to supporting a goal of achieving net-zero greenhouse gas emissions by 2050 or sooner. The company has made it no secret that it is committed to decarbonization and sustainability.                                                                                           , In 2020, the asset management behemoth rolled out a series of climate-focused exchange-traded funds that screen out companies with certain levels of investment in certain energy sectors such as coal and shale oil that environmentally-focused investors want to avoid.                                                                                                                                                               , BlackRock says on its website that its net-zero initiative is important because "climate risk will fundamentally reshape finance and drive a significant reallocation of capital," adding that the company believes "a successful and orderly net zero transition is in the financial interest" of their clients "and the economy as a whole."                                                                                           , Larry Fink, chief executive officer of BlackRock Inc., gestures as he speaks during a Bloomberg event on the opening day of the World Economic Forum (WEF) in Davos, Switzerland, on Tuesday, Jan. 21, 2020. (Photographer: Simon Dawson/Bloomberg via Get (Photographer: Simon Dawson/Bloomberg via Getty Images / Getty Images)                                                                                                        , BlackRock CEO Larry Fink says the company's sustainability investment strategies are in high demand. He said on the company's recent fourth-quarter earnings call that "We have already seen $4 trillion of capital move from traditional investments to sustainability ones in the last two years alone, and this is just the beginning."                                                                                               , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                  , West Virginia is the second-largest coal producer in the U.S. and the state ranks fifth in total energy production. Roughly 4.6% of the state's energy production comes from renewables such as hydroelectric and wind power, according to the state's Department of Economic Development.                                                                                                                                               , BlackRock did not immediately respond to FOX Business' request for comment on West Virginia's move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/17/business/electric-vehicles-europe.html </td>
   <td style="text-align:left;"> 2022-01-18 03:14:28 </td>
   <td style="text-align:left;"> Sales of Electric Vehicles Surpass Diesel in Europe, a First - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The popularity of battery-powered cars is soaring while the overall auto market stagnates, a worldwide trend.                                                                                                                                                                                                                                                                                                                                                         , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                               , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                        , By Jack Ewing                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Europeans bought more electric cars than diesels in December, a stunning illustration of the growing popularity of battery power and the decline of diesel, which was once the most popular engine option in Europe.                                                                                                                                                                                                                                                  , More than 20 percent of new cars sold in Europe and Britain in December were powered solely by electricity, according to data compiled by Matthias Schmidt, an analyst in Berlin who tracks electric vehicles sales. Sales of diesel vehicles, which as recently as 2015 accounted for more than half of the new cars in the European Union, slipped below 19 percent.                                                                                                , The December figures illustrate how electric vehicles are fast becoming mainstream. Sales of battery-powered cars soared in Europe, the United States and China last year while sales of conventional vehicles stagnated. Government incentives have made electric vehicles more affordable, the variety of electric cars to choose from has grown and buyers have become more conscious of the environmental cost of vehicles powered by internal combustion engines., The growth of electric vehicles was all the more remarkable considering that the overall car market is in crisis. Sales of all new cars in the European Union fell more than 20 percent in November as a shortage of semiconductors strangled production, according to the European Automobile Manufacturers’ Association.                                                                                                                                            , “This is the real deal,” Mr. Schmidt said in an email. His figures, based on data from European government agencies, were reported earlier by The Financial Times. The data includes Norway, which is not a member of the European Union and has the highest percentage of electric vehicles of any nation on the continent.                                                                                                                                          , Tesla was the best-selling electric vehicle brand in 2021, followed by Volkswagen, Mr. Schmidt said. Tesla will be in a good position to expand its leadership when it opens a factory near Berlin this year to serve the European market. Tesla has been importing cars from China.                                                                                                                                                                                  , Diesel was long popular in Europe because of tax policies that made diesel fuel less expensive than gasoline. Diesel-powered vehicles are generally more fuel-efficient than gasoline cars, but produce more harmful pollution.                                                                                                                                                                                                                                       , Diesel’s decline began in 2015 after Volkswagen admitted that it had sold millions of diesel cars equipped with software that produced artificially low emissions during official tests. The illegal software made the vehicles appear much cleaner than they were.                                                                                                                                                                                                   , The scandal called attention to the pollution caused by diesel cars, which is blamed for tens of thousands of premature deaths. Cities like Hamburg and Berlin banned diesel cars from some neighborhoods, while the European Union tightened its rules on vehicle pollution. Carmakers must pay substantial fines if they do not reduce carbon dioxide emissions to prescribed levels.                                                                               , The regulations encouraged carmakers to develop electric vehicles, which produce no tailpipe emissions, to comply. Gasoline vehicles are still more popular, accounting for 40 percent of new cars, but are also in long-term decline.                                                                                                                                                                                                                                , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/17/us/inside-texas-synagogue-hostage-standoff/index.html </td>
   <td style="text-align:left;"> 2022-01-18 03:07:29 </td>
   <td style="text-align:left;"> Inside the Texas synagogue hostage standoff - CNN </td>
   <td style="text-align:left;"> (CNN)It started like most any Saturday for members of Congregation Beth Israel.                                                                                                                                                                                                                                                                                                                                , Families of the Reform Jewish synagogue just outside Dallas-Fort Worth had gathered -- in person and online -- to participate in the Sabbath service, even amid the twin perils of a fresh pandemic wave and a swelling tide of attacks on Jewish people in the United States.                                                                                                                                  , By day's end, the community of faith in Colleyville, Texas, would be at the center of a global drama involving a livestreamed hostage-taking, an imprisoned terrorist icon, an elite FBI rescue team, a rabbi's quick thinking and a final, frantic sprint to freedom.                                                                                                                                          , More details may yet offer a deeper understanding of why it happened. But already, the tale is one of searing trauma, with the broader American Jewish community now again forced to be resilient as it's reminded of the ever-present potential for disaster.                                                                                                                                                  , A rabbi welcomes a stranger                                                                                                                                                                                                                                                                                                                                                                                     , A stranger arrived that morning at the synagogue.                                                                                                                                                                                                                                                                                                                                                               , Rabbi Charlie Cytron-Walker welcomed in the man and made him a cup of tea, the rabbi told CBS on Monday.                                                                                                                                                                                                                                                                                                        , Cytron-Walker may not have known immediately that Malik Faisal Akram, 44, was a British national. Akram had arrived in the US via New York's John F. Kennedy International Airport in late December, a US law enforcement source familiar with the investigation told CNN.                                                                                                                                      , In the two weeks before he met Cytron-Walker, Akram had spent three nights -- January 6, 11 and 13 -- at a Dallas homeless shelter, according to Union Gospel Mission Dallas CEO Bruce Butler. He was very quiet and wasn't there long enough to build any relationships, Butler said.                                                                                                                          , Over their shared tea, Cytron-Walker and Akram talked, the rabbi said.                                                                                                                                                                                                                                                                                                                                          , "Some of his story didn't quite add up, so I was a little bit curious, but that's not necessarily an uncommon thing," said the rabbi, who soon that day would lead a religious service for the 157 membership families of his congregation, established in 1999.                                                                                                                                                , The rabbi pointed Jeffrey Cohen, the vice president on the synagogue's board of trustees, to their guest that day. Cohen went over and introduced himself, he wrote in a Facebook post describing his experience.                                                                                                                                                                                               , "He was on the phone, but briefly stopped his conversation," Cohen said. "He said hello, smiled, and after we introduced ourselves, I let him go back to his call. He seemed calm and happy to be in from the frigid 20 degree morning. His eyes weren't darting around; his hands were open and calm, he said hello, he smiled."                                                                               , Because of the recent coronavirus surge, many of Congregation Beth Israel's members had stayed home on Saturday to watch the weekly prayers via Facebook or Zoom. Services began at 10 a.m.                                                                                                                                                                                                                     , As the rabbi led the prayers -- his back turned as he faced toward Jerusalem -- he heard a click. It came from the stranger.                                                                                                                                                                                                                                                                                    , "And it turned out, that it was his gun," Cytron-Walker said.                                                                                                                                                                                                                                                                                                                                                   , Cohen said he heard that same click, the "unmistakable sound of an automatic slide engaging a round." The mysterious guest then began yelling something. Cohen dialed 911 on his phone, put the screen side down and moved as commanded, he wrote.                                                                                                                                                              , Akram took four people hostage, including the rabbi, authorities said.                                                                                                                                                                                                                                                                                                                                          , 'I'm going to die at the end of this'                                                                                                                                                                                                                                                                                                                                                                           , Police got an emergency call at 10:41 a.m.                                                                                                                                                                                                                                                                                                                                                                      , They rushed to the synagogue and set up a perimeter, evacuating residents nearby, police said. Soon, nearly 200 local, state and federal law enforcement, including the FBI and the federal Bureau of Alcohol, Tobacco, Firearms and Explosives, were on hand, FBI Dallas Special Agent in Charge Matthew DeSarno said.                                                                                         , Meantime, the livestream -- intended for the faithful who'd stayed home to be safe from Covid-19 -- appeared to capture some of what Akram was saying.                                                                                                                                                                                                                                                          , "I'm gunned up. I'm ammo-ed up," he told someone he called nephew. "Guess what, I will die,"                                                                                                                                                                                                                                                                                                                    , The audio can be difficult to understand, and it's not clear whom Akram is talking to. But it's clear he planned to die during the standoff, he repeatedly told people.                                                                                                                                                                                                                                         , "OK, are you listening? I don't want you to cry. Listen! I'm going to release these four guys ... But then I'm going to go in the yard, yeah? ... And they're going to take me, alright? I'm going to die at the end of this, alright? Are you listening? I am going to die! OK? So, don't cry over me," the man said to someone else.                                                                          , Congregation member Stacey Silverman watched the livestream for more than an hour. She heard the suspect ranting, sometimes switching between saying, "I'm not a criminal," to apologies, she said.                                                                                                                                                                                                             , The man vacillated among languages and was "screaming hysterically," she said. He claimed to have a bomb.                                                                                                                                                                                                                                                                                                       , Akram also "spoke repeatedly about a convicted terrorist who is serving an 86-year prison sentence in the United States," the FBI said in a statement. The convict is believed to be Aafia Siddiqui, a Pakistani with a PhD in neuroscience who is serving a federal prison sentence in Fort Worth after being found guilty of attempted murder and other charges in an assault on US officers in Afghanistan.  , She was not involved in the Colleyville attack, her attorney said Saturday.                                                                                                                                                                                                                                                                                                                                     , "He wanted this woman released and he wanted to talk to her and he thought -- well, he said point blank -- he chose this synagogue because 'Jews control the world. Jews control the media. Jews control the banks. I want to talk to chief rabbi of the United States,'" Cohen told CNN, adding there is no chief rabbi in the US.                                                                             , Inside the synagogue, Cohen resisted following exactly as Akram commanded, he wrote in his Facebook post. Rather than go to the back of the room as ordered, Cohen stayed in line with one of the exits. When a police officer came to the door and the hostage-taker became more agitated, Cohen moved closer to the exit door, he wrote.                                                                      , Akram let them call their families, and Cohen called his wife, daughter and son and even posted on Facebook. He also slowly moved a few chairs in front of him -- "anything to slow or divert a bullet or shrapnel," he wrote.                                                                                                                                                                                  , At one point -- at the suspect's request -- the rabbi being held hostage called a well-known rabbi in New York City so the suspect could say Siddiqi was framed and he wanted her released, two officials briefed on investigation said.                                                                                                                                                                        , As hours ticked on, law enforcement negotiators had a "high frequency and duration of contact" with the suspect, DeSarno said. The FBI called out its Hostage Rescue Team from Quantico, Virginia, and some 60 to 70 people came to the site, Colleyville Police Chief Michael Miller said.                                                                                                                     , One hostage -- a man -- was released unharmed around 5 p.m., Colleyville Police Sgt. Dara Nelson said. The hostage-taker did not harm the hostages, the rabbi told CBS.                                                                                                                                                                                                                                         , But, he added, they were threatened the entire time.                                                                                                                                                                                                                                                                                                                                                            , A thrown chair activates a bold escape                                                                                                                                                                                                                                                                                                                                                                          , With threats and attacks targeting Jewish people growing more common in recent years, Cytron-Walker and his congregation had participated in security courses with law enforcement agencies, he said.                                                                                                                                                                                                           , As Saturday afternoon rolled to the night -- and the hostage-taker's demeanor began to change -- that training helped the rabbi and the two others still held against their will.                                                                                                                                                                                                                               , "In the last hour of our hostage crisis, the gunman became increasingly belligerent and threatening," Cytron-Walker said Sunday in a statement. "Without the instruction we received, we would not have been prepared to act and flee when the situation presented itself."                                                                                                                                     , Cohen helped another hostage move closer to that exit, and whispered to him about the door, he wrote. The third hostage later joined them when they received pizza to eat, putting them all within 20 feet of the exit door.                                                                                                                                                                                    , They spoke with Akram and asked him questions, trying to buy the FBI time to move into position, he wrote.                                                                                                                                                                                                                                                                                                      , Yet the situation began to devolve. "At one point, our attacker instructed us to get on our knees. I reared up in my chair, stared at him sternly. I think I slowly moved my head and mouthed NO. He stared at me, then moved back to sit down. It was this moment when Rabbi Charlie yelled run," he wrote.                                                                                                    , The rabbi said he threw a chair at the hostage-taker to buy time.                                                                                                                                                                                                                                                                                                                                               , "We were terrified," Cytron-Walker told CBS. "And when I saw an opportunity where he wasn't in a good position, I made sure that the two gentlemen who were still with me, that they were ready to go.                                                                                                                                                                                                          , "The exit wasn't too far away. I told them to go. I threw a chair at the gunman, and I headed for the door," he said. "And all three of us were able to get out without even a shot being fired."                                                                                                                                                                                                               , The three hostages burst through the exit door and sprinted away from the building, video taken from outside the synagogue by CNN affiliate WFAA shows. Seconds later, a man in black holding what appears to be a gun stepped halfway through the exit to look outside. He then returned inside the building without shooting, the video shows.                                                                , A group of heavily armed law enforcement personnel moved toward another part of the building, the video shows. About 30 seconds later, a series of four bangs erupted, followed by a louder explosive boom that set a number of car alarms to begin wailing. Other armed law enforcement personnel moved into a different position by the building, and another three loud bangs then went off, the video shows., The loud boom, heard by a CNN team near the synagogue at about 9:12 p.m., was the result of entry tools used by the hostage rescue team, an ATF spokesperson said.                                                                                                                                                                                                                                              , The rescue team breached the synagogue, Miller said. The suspect was killed.                                                                                                                                                                                                                                                                                                                                    , None of the four hostages was harmed, DeSarno said.                                                                                                                                                                                                                                                                                                                                                             , More booms echoed as the tactical team disposed of leftover entry explosives brought by the rescue team. Crime scene investigators recovered one firearm they believe belonged to the suspect, the ATF spokesperson said. An ATF dog found no more explosives, the spokesperson said.                                                                                                                           , On Facebook, Cohen credited active shooter training he received for his survival and escape.                                                                                                                                                                                                                                                                                                                    , "We weren't released or freed," he said. "We escaped because we had training from the Secure Community Network on what to do in the event of an active shooter."                                                                                                                                                                                                                                                , The Secure Community Network describes itself as the, "official safety and security organization of the Jewish community in North America."                                                                                                                                                                                                                                                                     , 'The time to heal our community has begun'                                                                                                                                                                                                                                                                                                                                                                      , On Sunday morning, Cytron-Walker took to Facebook, this time to express his gratitude to those who supported him throughout Saturday's ordeal.                                                                                                                                                                                                                                                                  , "I am thankful and filled with appreciation for all of the vigils and prayers and love and support, all of the law enforcement and first responders who cared for us, all of the security training that helped save us," he wrote in the Facebook post.                                                                                                                                                         , "I am grateful for my family. I am grateful for the CBI Community, the Jewish Community, the Human Community. I am grateful that we made it out. I am grateful to be alive," Cytron-Walker said in the post.                                                                                                                                                                                                    , Nothing suggests the threat posed by Akram is continuing, officials said. The investigation into the case and its motive is likely to be global, DeSarno added, including contacts with Tel Aviv and London.                                                                                                                                                                                                    , Initially, the FBI, based on its exchanges, found the suspect to be "singularly focused on one issue, and it was not specifically related to the Jewish community, but we'll continue to work to find motive," DeSarno said.                                                                                                                                                                                    , On Monday, the agency called Saturday's attack "a terrorism-related matter, in which the Jewish community was targeted," according to a statement. The case "is being investigated by the Joint Terrorism Task Force."                                                                                                                                                                                          , Congregation Beth Israel will hold a special service at Monday night to help the community put the "terrible event behind" them "and be thankful for a good result," according to a post on its Facebook page.                                                                                                                                                                                                  , "We are strong. We are resilient," it said. "The time to heal our community has begun."                                                                                                                                                                                                                                                                                                                         , CNN's Keith Allen, Melissa Alonso, Tina Burnside, Josh Campbell, Kacey Cherry, Ashley Killough, Ed Lavandera, Raja Razek and Geneva Sands contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/17/business/scotland-north-sea-wind-farms.html </td>
   <td style="text-align:left;"> 2022-01-18 01:54:19 </td>
   <td style="text-align:left;"> A North Sea Auction Produces Big Plans for Scottish Wind Farms - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                               , Oil giants like BP and Shell propose to spend billions on renewable energy, bolstering Scotland’s efforts to move away from an economy based on fossil fuel.                                                                                                                                                                                                                                                                               , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                    , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                             , By Stanley Reed                                                                                                                                                                                                                                                                                                                                                                                                                            , Oil giants like BP and Shell as well as Iberdrola, the Spanish utility, look like the big winners in Scotland’s first offshore wind auction, whose results were announced on Monday.                                                                                                                                                                                                                                                       , If the proposed wind farms are constructed, they would triple Britain’s capacity to generate electricity from turbines at sea.                                                                                                                                                                                                                                                                                                             , They would also advance still nascent plans to transform the Scottish North Sea region from oil and gas production into a major area for renewable electric power.                                                                                                                                                                                                                                                                         , “This is not just going to be a matter of producing green power,” said Soeren Lassen, head of offshore wind at Wood Mackenzie, a market research firm. “This is fuel to build up a green economy,” he added.                                                                                                                                                                                                                               , In awarding the leases, the Scottish government is also trying to persuade the oil companies, which have been laying off workers as investment in oil and gas plummets, to retain a substantial presence in Scotland.                                                                                                                                                                                                                      , “For a number of key companies this will underline their commitment to the area,” said Barney Crockett, the lord provost, or mayor, of Aberdeen, the oil hub.                                                                                                                                                                                                                                                                              , Companies were bidding on the chance to develop offshore parcels covering 2,700 square miles. The auction will bring in nearly 700 million pounds, or about $955 million, in option fees to the Scottish government. But the work will take time: Energy executives said the Scottish projects were unlikely to start generating power before the late 2020s.                                                                              , “We secured the blocks that we wanted,” said Louise Kingham, head of country for Britain at BP, which gained the option to develop a large wind farm near Aberdeen with capacity comparable to a nuclear power station, in partnership with EnBW, a German utility.                                                                                                                                                                        , Ms. Kingham said BP would invest £10 billion in the wind farm, including the acquisition of four service vessels and initiatives to modernize Leith, Edinburgh’s port. It is expected to become a manufacturing center for offshore equipment. BP also plans for Aberdeen, now a center for undersea technology for the oil industry, to become an operations and maintenance hub for the company’s wind business.                         , Ms. Kingham said there was now “a real opportunity” for Scotland to become a center for renewable energy, including hydrogen, electric vehicle charging and other solutions to climate change.                                                                                                                                                                                                                                             , The Scottish government insisted that winning bidders spend substantial sums with local businesses. Overall, the 17 offshore wind projects awarded are likely to bring in tens of billions of pounds in investment, bolstering the British and Scottish economies.                                                                                                                                                                         , Thomas Brostrom, senior vice president for renewables at Shell, said that the company had promised that 40 percent of its investment would go to Scottish firms and that his company, like BP, was considering making Aberdeen into a center for wind power. Shell and Iberdrola’s subsidiary, ScottishPower, won two large tracts off northeast Scotland with a depth of as much as 330 feet of water.                                    , Alvaro Martinez Palacio, managing director for offshore wind at Iberdrola, which won the largest amount of acreage, partly in partnership with Shell, estimated that the capital costs for the company’s awarded wind farms would be £10 billion to £20 billion.                                                                                                                                                                           , The Scottish projects are also likely to be test sites for floating wind turbines, which are anchored to the seabed rather than attached. Floating turbines can be placed in deep water, which describes much of the area covered by the Scottish leases, as well as places like the California coast.                                                                                                                                     , So far, though, floating turbines are still too costly for wide commercial deployment. Shell’s two wind farms, which amount to about 20 percent of the capacity awarded, would need to be on floating structures, which are still in the experimental stage.                                                                                                                                                                               , A key issue is where the power will go. Overall, the potential capacity that has been awarded is likely far too much for the Scottish system. Southbound cables will be needed to take power to major population and industrial centers in England. Eventually, the Scottish power may also be used to generate hydrogen, a clean-burning gas, and the electricity could be sent across the North Sea to Norway or Germany, executives say., Holger Grubel, head of portfolio development at EnBW, BP’s partner, said building infrastructure for sending power south and finding other ways to make use of it were “a crucial element in being successful in actually delivering the wind farms on time.”                                                                                                                                                                              , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/17/business/brexit-food-imports.html </td>
   <td style="text-align:left;"> 2022-01-18 01:15:09 </td>
   <td style="text-align:left;"> Brexit Import Rules Begin to Squeeze British Food Importers - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , For companies depending on fast, small deliveries, the costs of new Brexit trade rules are mounting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , By Eshe Nelson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , LONDON — In a warehouse tucked under two railway arches in southeast London is a treasure trove of Greek delicacies, including barrel-aged feta, fresh oregano, Cretan olive oil and cases of nearly a hundred different wines destined for the city’s top restaurants and discerning home cooks. But as Britain phases in Brexit-required customs rules with the European Union, the tempting variety at Maltby &amp; Greek is under threat.                                                                                                                                     , The additional forms, customs charges and health safety checks needed for goods to cross Britain’s border are particularly arduous for businesses moving small quantities. That includes specialist food importers buying from small suppliers across the European continent who have helped make London one of the world’s best cities for dining.                                                                                                                                                                                                                           , It has “minimized our ability to discover and import unusual products,” said Yannos Hadjiioannou, the owner of Maltby &amp; Greek, which for the past decade has imported food and wine from Greece and its islands, prizing itself on products rarely found in Britain. On Saturdays, under the arches, customers can peruse goat-milk butter; Mastelo cheese, a kind of halloumi made from cow’s milk from the island of Chios; bunches of mountain tea; and pale Gigantes beans from Feneos, in the northern Peloponnese.                                                      , Getting each of those items here became more complicated just over two weeks ago.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , After a yearlong delay, on Jan. 1, Britain stepped up its enforcement of customs requirements for goods coming from the European Union, which in 2020 accounted for half of all imports into the country. Now, the goods must be accompanied by customs declarations. (Last year, British importers could delay reporting by about six months.) And businesses importing animal and plant products — most food, for example — must notify the government of shipments in advance.                                                                                             , At the border, the introduction of the rules has gone relatively smoothly. DFDS, a Danish logistics company that runs ferry services to Britain, said some customers had incorrectly filled out the paperwork, and some food shipments were stopped. On one day, shipments from the Netherlands had to be halted to deal with a backlog from the previous day.                                                                                                                                                                                                                , “Everybody involved tried to learn from what happened a year ago,” said Torben Carlsen, the chief executive of DFDS.                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Last year, the European Union introduced customs rules as soon as Brexit went into effect, and immediately the problems piled up: Deliveries were delayed, trucking companies stopped serving Ireland and food spoiled in ports. It took more than a month before most of the problems were resolved.                                                                                                                                                                                                                                                                         , Britain couldn’t afford the same import issues this year. About a quarter of the country’s food is imported from the European Union, according to data from 2019, a figure that jumps substantially in winter for fresh fruit and vegetables.                                                                                                                                                                                                                                                                                                                                 , But there are challenges — unseen, away from the border. Some British businesses are taking on the export costs of their European suppliers to avoid losing them. Others are just importing less, reducing the choices for customers. Still others are restricting purchases to bulk orders and forgoing trying new products.                                                                                                                                                                                                                                                 , The decline was noticeable even before the latest import rules began. In the first nine months of 2021, food and drink imports fell about 11 percent from 2019, according to the Food and Drink Federation.                                                                                                                                                                                                                                                                                                                                                                   , After Britain left the European Union’s customs union at the start of 2021, Mr. Hadjiioannou kept business going as normal, he said. Within six months, however, the additional customs costs and associated price increases became prohibitive. He stopped getting weekly deliveries of anthotyro, a soft fresh sheep’s milk cheese from Crete, and traditionally strained sheep or goat yogurt, leaving the popular products regularly out of stock. Sausages from Crete now come frozen instead of fresh so they can be sent in larger, less frequent deliveries.          , “Most of the perishable products have suffered, particularly the ones which were small volume but important for a lot of the restaurateurs and delis,” Mr. Hadjiioannou said. The biggest disruption from Brexit has been the loss of flexibility, he added.                                                                                                                                                                                                                                                                                                                  , Maltby &amp; Greek’s warehouse is at Spa Terminus, a long strip of railway arches housing food producers, wholesalers and wine importers. At this time of year, fresh produce at its markets includes Sicilian citrus, Italian leafy greens and French root vegetables. At the opposite end to Maltby &amp; Greek, Rachel Sills sells cheese made in Switzerland and the Netherlands. While her experience exporting from Switzerland softened the blow of Brexit’s trade rules, it hasn’t insulated her from the extra cost.                                                         , She buys cheese from four small producers in the Netherlands — so small that not all of them have an email address. Now each one is required to have an Economic Operator’s Registration and Identification number, as well as customs agents to do export and tax paperwork, and they must complete more detailed invoices, which include tariff codes.                                                                                                                                                                                                                      , Ms. Sills said she had taken on the extra costs for export clearances for the cheesemakers. Recently she was able to combine the orders to pay only 65 euros ($74.50) for each invoice, on top of her own import fees. “So they, to this stage, haven’t started paying for the real costs of the export charges,” she said. “I have.”                                                                                                                                                                                                                                         , “It’s not that the paperwork or the cost is actually that onerous,” Ms. Sills said. But for companies with lots of suppliers, “when you add up the cost of each one, then it becomes insane,” she said, especially if buying small volumes.                                                                                                                                                                                                                                                                                                                                   , And that is so far what Brexit has boiled down to for these businesses: extra costs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , “We are past the point of having wild shortages,” said David Henig, a trade policy expert in London. The customs systems work, but the damage will be more like a “slow boiling frog.” The extra costs will eat away at Britain’s economy, with independent forecasts indicating a long-run shortfall of about 4 percent of gross domestic product. For customers, the overall effect is likely to be less choice, Mr. Henig added.                                                                                                                                           , It also continues to diminish the incentives for companies to invest in Britain.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , “We are less U.K.-centric than we were a couple of years ago,” said Franco Fubini, the founder of Natoora, which began in London in 2004 and now supplies fresh produce from hundreds of small farms in Europe and North America to about 1,600 restaurants globally and shops including Selfridges and Whole Foods, with outposts in the United States.                                                                                                                                                                                                                      , Natoora reorganized its internal processes so that the British arm of the company no longer imports anything directly from the farms in Italy, France, Spain and Greece. Instead more employees were hired in Paris and Milan so the produce could be bought by the hubs in the continent and then sold to the London office. This consolidation means there is only one invoice, saving money on trucks and customs.                                                                                                                                                         , Even though Natoora found a workaround, Mr. Fubini said Brexit had dented Britain’s international reputation, making him reconsider his company’s future. “For the first time in 15 or 16 years, I really started to question how much we should continue to invest in the U.K,” he said.                                                                                                                                                                                                                                                                                     , When Prime Minister Boris Johnson announced the new trade deal with the European Union on Christmas Eve 2020, he said the agreement, “if anything, should allow our companies and our exporters to do even more business with our European friends.” In reality, it has made it harder, not easier. Brexit might free Britain from Brussels bureaucracy, but it has tied businesses up in other red tape. While the promises of Brexit were varied — from opening up new markets and deregulation — the slowness in realizing the benefits has frustrated even its supporters., The other fresh produce market at Spa Terminus, Puntarelle &amp; Company, is run by Elena Deminska, who said Brexit could be a great opportunity for British farmers to produce some of the food that was mostly imported from the European Union. The country has the climate for bitter winter lettuce or broccoli rabe or, “with a little bit of effort,” apricots, Ms. Deminska said. Instead she complains that the farmers are “not flexible.”                                                                                                                              , About four years ago, with great foresight, Ms. Deminska outsourced her customs work to an external company. Still she despairs at the Brexit-induced paperwork. “It’s just not helpful,” she said. “There is already enough paperwork.”                                                                                                                                                                                                                                                                                                                                      , For all of these businesses there are more hurdles ahead. Beginning in July, food imports will need to be accompanied by health certificates signed off by inspectors in the European Union, and could be picked for spot checks at the border.                                                                                                                                                                                                                                                                                                                               , Those changes “are just going to add complexity, add cost,” Mr. Fubini said. “It is disruptive.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/mlk-day-janet-yellen-us-economy-unfair-black-americans </td>
   <td style="text-align:left;"> 2022-01-18 01:12:52 </td>
   <td style="text-align:left;"> On MLK Day, Yellen says US economy 'has never worked fairly' for Black Americans </td>
   <td style="text-align:left;"> Kay C. James on MLK Day, Biden admin                                                                                                                                                                                                                                                                                                                                              , The U.S. economy has "never worked fairly" for Black Americans or any person of color, Treasury Secretary Janet Yellen said in a Monday speech, joining a cadre of national leaders who used Martin Luther King Jr. Day to acknowledge racial inequalities in the country.                                                                                                        , Yellen made the in remarks in a prepared speech that she recorded for delivery at the Rev. Al Sharpton’s National Action Network breakfast in Washington. Monday would have been the 93rd birthday of the Rev. Martin Luther King Jr., who was only 39 when he was assassinated in Memphis, Tennessee, in 1968 while supporting Black city sanitation workers who were striking.  , ALVEDA KING REVEALS HOW TO BE MORE LIKE MLK IN 2022                                                                                                                                                                                                                                                                                                                               , She referenced part of King's famous "I Have a Dream" speech that he gave on the steps of the Lincoln Memorial, in which he said that America "has defaulted on this promissory note" that all Americans would be guaranteed the inalienable rights of life, liberty and the pursuit of happiness "insofar as her citizens of color are related."                                 , In this Aug. 28, 1963, file photo, Dr. Martin Luther King Jr. addresses marchers during his "I Have a Dream" speech at the Lincoln Memorial in Washington. (Associated Press)                                                                                                                                                                                                     , The civil rights leader called the promise a "bad check, a check which has come marked insufficient funds. But we refuse to believe the bank of justice is bankrupt."                                                                                                                                                                                                             , "It is compelling rhetoric, but I think Dr. King knew it was more than a metaphor," Yellen said. "He knew that economic injustice was bound up in the larger injustice he fought against. From Reconstruction, to Jim Crow, to the present day, our economy has never worked fairly for Black Americans – or, really, for any American of color."                                 , Yellen said the Treasury Department has "much more work" to do in order to narrow the racial wealth divide, and noted that no one program or administration can "make good on the hopes and aspirations that Dr. King had for our country."                                                                                                                                       , Janet Yellen, U.S. Treasury secretary, speaks during a Senate Banking, Housing and Urban Affairs Committee hearing in Washington, D.C., on Tuesday, Nov. 30, 2021. (Al Drago/Bloomberg via Getty Images / Getty Images)                                                                                                                                                           , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                       , But she argued that the Biden administration is helping to shrink the gap and improve equity through different actions it's taken, including passing the $1.9 trillion American Rescue Plan in March, diversifying leadership roles at the Treasury and injecting $9 billion into community development financial institutions and minority depository institutions.              , "Since taking office last January, our administration has tried to change that; to ensure that neither the figurative bank of justice – nor any literal economic institution – fails to work for people of color," she said.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 01:12:26 </td>
   <td style="text-align:left;"> Italian Stocks Recover from Last Week's Losses </td>
   <td style="text-align:left;"> The FTSE MIB Index traded 0.5% higher to close at 27,689 on Monday, supported by tech and raw materials shares as investors weighed on the People’s Bank of China’s rate cur following a near two-year low GDP growth rate for Q4 2021. Tenaris led the gains to rise by 2.4% amid outlooks of high demand for stainless steel pipes after data from Baker Hughes indicated an increase in active oil and natural gas drilling rigs in the United States. Meanwhile, expansionary monetary policy in China lifted Italian luxury brands, especially Moncler (1.6%) and Brunello Cucinelli (2.8%). On the other hand, Telecom Italia fell 3.3% following news that the firm’s boardroom aims to re-strategize the telecom’s fixed network assets, diminishing the chances of KKR’s takeover. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/17/opinions/tonga-volcano-eruption-tsunami-lessons/index.html </td>
   <td style="text-align:left;"> 2022-01-18 01:00:57 </td>
   <td style="text-align:left;"> Opinion: The enormous Tonga volcano eruption was a once-in-a-millennium event - CNN </td>
   <td style="text-align:left;"> Shane Cronin is a Professor in Volcanology at the University of Auckland, New Zealand. He has published more than 200 scientific papers on the chemistry and physics of active volcanoes and strives to understand the hazards they pose, especially in the Asia-Pacific region. The opinions expressed here are his own. View more opinion at CNN.                                                                                                                                                                                                                                                                               ,  (CNN)The eruption of the Hunga-Tonga-Hunga-Ha'apai volcano on Saturday was so large, it was a spectacle best appreciated from space.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The eruption was remarkable in that it involved the simultaneous formation of a volcanic ash plume, an atmospheric shock wave and a series of tsunami waves.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , While details are still emerging and we are still within an eruption episode that could have more twists and turns, there are several pieces of information that can help us begin to understand this event and why it occurred.                                                                                                                                                                                                                                                                                                                                                                                                  , First, let's look at the eruption. Events of this magnitude occur roughly once a decade around the world, but for this volcano an eruption of this scale is a rarity. Based on my research, using radiocarbon dating to examine the ash and deposits from past eruptions, it seems this latest eruption is a once-in-a-millennium event for the Hunga-Tonga-Hunga-Ha'apai volcano.                                                                                                                                                                                                                                                , It takes roughly 900-1000 years for the Hunga volcano to fill up with magma, which cools and starts to crystallize, producing large amounts of gas pressure inside the magma. As gases start to build up pressure, the magma becomes unstable. Think of it like putting too many bubbles into a champagne bottle -- eventually, the bottle will break.                                                                                                                                                                                                                                                                            , As the magma pressure rises, the cold and wet rock above the magma fails and suddenly releases the pent-up pressure. The eruption we saw on Saturday blasted rock, water, and magma 30 km high into the atmosphere, and was profound in terms of its energy. Within 30 minutes, the resulting cloud seen from space was over 350 km (or 218 miles) in diameter, with ash falling out onto several Tongan islands.                                                                                                                                                                                                                 , As for tsunamis, they are most commonly caused by earthquakes.  When tectonic plates shift under the ocean, it can displace enough water to cause massive waves. So how does a partially submerged volcano in the southwest Pacific create enough energy to produce tsunami waves that hit the West coast of the US?                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , While it's still unclear what exactly caused the tsunami, there are at least two distinct possibilities -- and the first has to do with the expansive force of the initial eruption. On Saturday, the eruption of magma from the volcano created a sudden release of pressure, producing supersonic air pressure waves that could be seen from space.                                                                                                                                                                                                                                                                             , These air pressure waves traveled more than 2000 km (1,200 miles) to New Zealand and were felt as far as the United Kingdom and Finland.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The atmospheric waves and the initial blast affected the ocean surface, causing the giant waves that then hit the Tongan island of Tongatapu and the capital of Nuku'alofa. Early videos showed the waves splashing over roads before the plume of ash darkened the sky.                                                                                                                                                                                                                                                                                                                                                          , Another possible cause of the tsunami waves could have been the remarkable changes within the Hunga volcano. In the aftermath of the eruption, images from satellite radar imagery show the central part of the volcano which previously rose above sea level has since disappeared below the waves. This indicates when the eruption occurred, the sudden loss of magma likely caused the central portion of the volcano to collapse, creating a caldera, or a hollow depression. This collapse could have displaced the water, generating tsunami waves that radiated outwards across the Pacific and all the way to California.,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The Hunga eruption was also astounding in terms of all the lightning generated. This is caused by the electrostatic interaction of very fine volcanic "ash" particles in the air. Weather satellites and lightning researchers are calling this one of the most significant events they have ever seen, with lightning strikes peaking at 63,000 events per 15 minutes.                                                                                                                                                                                                                                                           , Past eruptions from this volcano -- such as the 2014 eruption that created a new island --  included many phases of eruption, and thus we could see more explosions in the coming days and weeks. One moderating factor is the caldera is now underwater, making it harder for eruptions to break through into the atmosphere.                                                                                                                                                                                                                                                                                                    , This could mean a shift to more submarine-style explosive eruptions. While this would mean a smaller atmospheric impact, there could still be an elevated risk of tsunamis, and people who live in coastal areas around the Pacific should be on high alert in the coming weeks.                                                                                                                                                                                                                                                                                                                                                  , Even though our past research has highlighted the importance of the power of eruptions at this volcano, predicting volcanic eruptions to the day and hour remains impossible. This is particularly difficult at a volcano so far offshore, with no power and a shifting, dynamic environment. The only observations are possible via satellite methods, which give a few minutes warning at best for the local residents of Tonga.                                                                                                                                                                                                , They say every major eruption brings with it a new surprise. This event has shown us clearly volcanoes can be very effective at generating tsunami events, and while Tonga is a long way away from most other countries, its volcanoes can threaten low-lying areas of nations around the globe.                                                                                                                                                                                                                                                                                                                                  , Over the next days to weeks, we will learn more about this fascinating and dangerous volcano and also the hazards of submarine calderas. Early reports suggest Tonga has experienced significant damage due to tsunami, with many outlying areas still out of reach. We can only hope at the moment everyone in Tonga is safe and well.                                                                                                                                                                                                                                                                                           , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 00:51:47 </td>
   <td style="text-align:left;"> South African Stocks End Higher </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index closed 0.6% up at 75,594 on Monday, not far from a record high of 75,926 touched on January 13th, boosted by commodity-linked companies and tech stocks. Meanwhile, investors focused on upcoming US corporate earnings and the outlook for tighter monetary policy, while also digesting mixed economic data from China. Domestically, a government meeting is set for this week where proposals will be discussed regarding a roadmap for when the state of disaster will end. On the data front, traders are awaiting a set of economic data in the coming days, including mining production, consumer price inflation and retail sales. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 00:47:55 </td>
   <td style="text-align:left;"> FTSE 100 Hits 2-Year High </td>
   <td style="text-align:left;"> The FTSE 100 rose 0.9% to close at 7,611 on Monday, the highest level since January 2020, helped by a jump of 4.1% in shares of GlaxoSmithKline after the company rejected a £50 billion offer from Unilever for its consumer goods arm, saying it undervalued the business. Unilever shares dropped 6.5% and were the worst performer on the index. Meanwhile, energy and mining stocks were boosted by rising commodity prices, while investors digested China's fourth-quarter GDP figures. The world's No 2 economy grew at the softest pace in over a year during the October-December period, prompting the country's central bank to cut the borrowing costs of its medium-term loans for the first time since April 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 00:46:00 </td>
   <td style="text-align:left;"> European Stocks Start Week Higher </td>
   <td style="text-align:left;"> European equity markets closed higher on Monday, with Frankfurt’s DAX rising 0.3% led by gains across basic resources while investors cheered better-than-expected GDP data out of China. The world's second-largest economy grew by 4% in the October-December period, above market forecast of 3.6%. In corporate news, Credit Suisse shares declined more than 2% as its chairman Antonio Horta-Osorio resigned following an internal probe into his personal conduct. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 00:46:00 </td>
   <td style="text-align:left;"> French Shares Rebound to Start Week </td>
   <td style="text-align:left;"> The CAC 40 Index closed 0.8% higher at 7202 on Monday, supported by luxury goods and expansionary monetary policy in China. The Chinese GDP grew 4% on the quarter during Q4 2021, the lowest rate since the second quarter of 2020, leading the PBoC to cut its benchmark rate for the first time in nearly two years. Expansionary policy in China, the largest market for French luxury brands, lifted Hermes (3.8%), Kering (2.9%), and LVMH (1.6%) shares. Meanwhile, Vallourec gained 6.2% following news that the steel pipe producer is in talks with Brazilian Authorities about reopening its Pau Branco iron ore mine. Meanwhile, Renault rose 1.5% despite lower global sales, as the auto-manufacturer released promising data of its prospected revenues during 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-18 00:45:11 </td>
   <td style="text-align:left;"> The FTSE 100 Index went up by 0.87% </td>
   <td style="text-align:left;"> United Kingdom Stock Market gained 66 points. Gains were led by Antofagasta (4.48%), Admiral Group (4.44%) and Taylor Wimpey PLC (4.09%). Biggest losers were Unilever (-6.47%), Evraz (-1.38%) and Flutter Entertainment (-1.33%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-01-18 00:32:00 </td>
   <td style="text-align:left;"> Canadian Dollar Steady Around 2-Month High </td>
   <td style="text-align:left;"> The Canadian dollar traded just above 1.25, hoovering near a 2-month high of 1.249 hit on January 13th, on higher oil prices and a subdued dollar.  Oil prices – a major Canadian export – traded higher above $83 per barrel. Meanwhile, investors eye the inflation report due on January 19th to assess further clues on the next steps of the monetary policy. Higher inflation data would strengthen the appeal for higher rates from the BoC, which dashed investors’ expectations in its last meeting arguing that the new variant Omicron had raised uncertainty around the economic recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-01-18 00:13:37 </td>
   <td style="text-align:left;"> Brazilian Real at 2-Month High </td>
   <td style="text-align:left;"> The Brazilian Real traded near 5.50, the highest since November 16th, after economic activity figures showed that the Brazilian economy rose 0.7% in November, slightly above market expectations and snapping four consecutive months of contraction. The real has been hit by successive downward revisions of growth expectations, therefore better-than-expected economic data brought certain optimism to investors. Also, the currency gains remain sustained by a subdued dollar and higher-than-expected inflation data strengthing the case for higher rates in Brazil. Consumer prices data showed that inflation rose 10.06% in 2021, hotter than market expectations of a 9.97% increase, and well above the central bank’s target range of 3.75% ± 1.5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/17/us/ghislaine-maxwell-john-does/index.html </td>
   <td style="text-align:left;"> 2022-01-18 00:10:36 </td>
   <td style="text-align:left;"> Ghislaine Maxwell ends fight to keep eight 'John Does' secret - CNN </td>
   <td style="text-align:left;"> (CNN)Ghislaine Maxwell will no longer fight to keep the names of eight 'John Does' secret and will leave it to the court to decide whether the names should be unsealed, according to a January 12 letter to federal Judge Loretta Preska of the Southern District of New York.                                                                                                                                                                             , The documents containing the names are connected to a 2015 defamation case brought by Virginia Roberts Giuffre, who claimed Epstein sexually abused her while she was a minor and that Maxwell aided in the abuse. The case was settled in 2017.                                                                                                                                                                                                             , Maxwell, 60, faces up to 65 years in prison after she was found guilty last month in a New York federal court on five federal charges, including sex trafficking of a minor. The charges were related to her role in Epstein's sexual abuse of minor girls between 1994 and 2004.                                                                                                                                                                            , "After careful review of the detailed objections submitted by Non-Party Does 17, 53, 54, 55, 73, 93 and 151, counsel for Ghislaine Maxwell writes to inform the Court that she does not wish to further address those objections," Maxwell attorney Laura Menninger wrote. "Each of the listed Does has counsel who have ably asserted their own respective privacy rights. Ms. Maxwell therefore leaves it to this Court to conduct the appropriate review.", Giuffre's attorney had filed a brief on Wednesday, arguing for the names to be revealed.                                                                                                                                                                                                                                                                                                                                                                     , "[G]eneralized aversion to embarrassment and negativity that may come from being associated with Epstein and Maxwell is not enough to warrant continued sealing of information. This is especially true with respect to this case of great public interest, involving serious allegations of the sex trafficking of minors," Guiffre attorney Sigrid McCawley wrote.                                                                                         , "Now that Maxwell's criminal trial has come and gone, there is little reason to retain protection over the vast swaths of information about Epstein and Maxwell's sex-trafficking operation that were originally filed under seal in this case."                                                                                                                                                                                                             , McCawley said the court has already rejected similar arguments for anonymity and the same standard should apply to the eight 'John Does' who still remain anonymous in court documents.                                                                                                                                                                                                                                                                      , "Upon review of the objections of those Does, it is apparent that their objections essentially mirror objections to unsealing that this Court has already rejected: that unsealing certain documents might be embarrassing, would expose non-parties to media attention, and could result in some unfortunate association between the non-parties and Jeffrey Epstein or Ghislaine Maxwell," McCawley wrote.                                                 , McCawley added at least two of the unidentified people -- John Does 53 and 54 respectively -- do not oppose and do not generally object to their names being unsealed.                                                                                                                                                                                                                                                                                       , Maxwell also was found guilty of transporting a minor with the intent to engage in criminal sexual activity and three related counts of conspiracy. Her attorneys plan to appeal.                                                                                                                                                                                                                                                                            , Maxwell denied knowing Epstein had a scheme to recruit underage girls for sex, according to her 2016 deposition related to Giuffre's defamation case.                                                                                                                                                                                                                                                                                                        , CNN's Brian Vitagliano contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-18 00:04:00 </td>
   <td style="text-align:left;"> Colombia Posts Widest Trade Gap on Record </td>
   <td style="text-align:left;"> Colombia’s trade deficit widened to USD 2.56 billion in November of 2021, from USD 1.66 billion in the corresponding month of the previous year. It was the largest trade shortfall ever recorded, as imports jumped 56.3% to a record high of USD 6.5 billion, amid higher purchases of manufactured products (50.8%); fuels and extraction industries (190.2%) and agricultural products, food &amp; beverages (35.3%).
Meanwhile, exports advanced 58% to a near four-year high of USD 3.99 billion, boosted by sales of manufactured products (34.8%), fuels and mining industries (117.9%) and agricultural products, food &amp; beverages (25.6%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/imports-yoy </td>
   <td style="text-align:left;"> 2022-01-17 23:59:32 </td>
   <td style="text-align:left;"> Colombia Imports Hit Record High </td>
   <td style="text-align:left;"> Colombian imports jumped by 56.3 percent over a year to an all-time high of USD 6.5 billion in November of 2021, partly reflecting low base effects and amid the ongoing recovery. Purchases grew significantly for manufactured products (50.8 percent); fuels and extraction industries (190.2 percent) and agricultural products, food &amp; beverages (35.3 percent). The largest import partners were the US (25.6 percent of total imports), followed by China (22.8 percent), Mexico (6.1 percent) and Brazil (5.5 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/17/business/bbc-license-fee.html </td>
   <td style="text-align:left;"> 2022-01-17 23:45:16 </td>
   <td style="text-align:left;"> BBC Funding Frozen for 2 Years as Cabinet Minister Attacks Public Fee - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                               , The license fee on TV owners makes up three-quarters of the British broadcaster’s income and is guaranteed until 2027.                                                                                                                                                                                                                                                                                                                                     , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                    , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                             , By Eshe Nelson                                                                                                                                                                                                                                                                                                                                                                                                                                             , Over the weekend, a British government minister tried to deal a death blow to the main source of funding for the BBC, a license fee charged each year to any household with a TV.                                                                                                                                                                                                                                                                          , Nadine Dorries, who oversees the BBC in the cabinet, said on Twitter that an imminent announcement about the license fee “will be the last.” But by Monday afternoon, standing in the House of Commons in Parliament, she walked back her contentious claim as she announced that the license fee would be frozen for the next two years — a move that could require substantial budget cuts at the public broadcaster just to keep up with fast inflation., The funding freeze is “disappointing,” Richard Sharp, the BBC’s chairman, and Tim Davie, the director-general, said in a statement, and will “necessitate tougher choices.”                                                                                                                                                                                                                                                                                , For four years from April 2024, the fee will rise again in line with inflation, Ms. Dorries said. The BBC and the government have been in negotiations since late 2020 over the amount that TV owners must pay over the next five years. For the past five years, the fee has increased in line with inflation annually.                                                                                                                                   , “This is a very good result compared to alternative results, including the elimination of the license fee” and additional below-inflation increases, said Claire Enders, founder of Enders Analysis, a media research firm.                                                                                                                                                                                                                                , Three-quarters of the BBC’s income, about 3.75 billion pounds ($5.1 billion), comes from the license fee, which is currently £159 ($217) per household. The fee was introduced in 1923 to pay for radio. Now it funds eight national TV channels, 10 radio stations, local stations (including Welsh and Gaelic language services), educational content and on-demand services. Fourteen percent of the license fee funds non-BBC TV.                      , Ms. Dorries, who is the culture secretary, and fellow Conservatives have long argued that the BBC needs a big overhaul in how it is funded. They have also said it is too left-leaning and too London-centric.                                                                                                                                                                                                                                             , “The days of the elderly being threatened with prison sentences and bailiffs knocking on doors are over,” Ms. Dorries said on Twitter on Sunday. “Time now to discuss and debate new ways of funding, supporting and selling great British content.”                                                                                                                                                                                                       , In Parliament on Monday, in a more conciliatory tone and citing the BBC’s “unique place in our cultural heritage,” Ms. Dorries said that “it’s time to begin asking those really serious questions” about the funding of the BBC and whether the license fee was appropriate. But she wasn’t stating a policy. “We are announcing a debate and a discussion,” she said.                                                                                    , The BBC’s funding through the license fee is guaranteed until the end of 2027, after which the BBC’s Royal Charter expires and its mission, public purpose and funding method need to be renewed. New terms will be decided with the government of the day. But before then there will be another general election, which will determine the fate of the license fee.                                                                                      , In Britain, inflation is at its highest level in a decade, and freezing the license fee could require the broadcaster to make even more cuts. Ms. Dorries said any increase couldn’t be justified while millions of households were squeezed by rising energy bills and consumer prices. The Conservative government is also raising taxes in April to fund more health services.                                                                          , Since 2016, the BBC has been undertaking a vast cost-cutting plan, trying to save £800 million annually. This fiscal year, it expects the savings to rise above £950 million. Last year, it cut 1,200 jobs.                                                                                                                                                                                                                                                , The changes have come amid an overhaul of the BBC’s leadership. Since late 2020, a new director-general and chairman have been installed. Deborah Turness, who was president of NBC News, will be the BBC’s next director of news.                                                                                                                                                                                                                         , After complaints about bias in its news coverage, the broadcaster announced a plan last year to spend an additional £700 million outside London by 2027 and relocate 400 jobs.                                                                                                                                                                                                                                                                             , The broadcaster has been facing increasing pressure, and not just from the government. The BBC is trying to reach a more diverse and younger audience while cutting costs, as big-budget streaming companies such as Netflix and Spotify expand in Britain.                                                                                                                                                                                                , On the future of the BBC’s funding and purpose, Mr. Sharp and Mr. Davie said that while all options should be considered, “the BBC is owned by the public, and their voice must always be the loudest when it comes to determining the BBC’s future.”                                                                                                                                                                                                      , In Britain, the debate around the fee often focuses on the BBC’s news service, and whether everyone should be required to pay for it, said Meera Selva, the deputy director of the Reuters Institute for the Study of Journalism at the University of Oxford. The BBC also broadcasts other content, including documentaries and dramas. When schools closed during the pandemic, it also increased children’s educational output.                         , The next question for Britain to decide, Ms. Selva said, is “are we willing to pay for all content or just news?”                                                                                                                                                                                                                                                                                                                                          , Alternative funding ideas include a direct grant from the government, a subscription service or a membership system that makes its content available to everyone for free but is funded by willing members. But unlike, say, Netflix, the BBC is being asked to provide many different services and is required to provide content that might not be commercially viable, Ms. Selva said.                                                                  , “The license fee,” she said, “is the closest model we have for preserving editorial independence.”                                                                                                                                                                                                                                                                                                                                                         , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/stock-market </td>
   <td style="text-align:left;"> 2022-01-17 23:44:36 </td>
   <td style="text-align:left;"> Stocks in Mexico Hit All-time High </td>
   <td style="text-align:left;"> IPC Mexico increased to an all-time high of 54109 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-01-17 23:34:58 </td>
   <td style="text-align:left;"> Colombia Retail Sales Growth Eases to 9-Month Low </td>
   <td style="text-align:left;"> Colombia’s retail sales rose 7.4 percent year-on-year in November of 2021, easing from a 14.2 percent advance in the previous month. It was the lowest retail trade growth since February 2021. The most important contributions came from sales of fuels (16.2 percent), vehicle and motorbike (23.3 percent), spare parts, accessories and lubricants for vehicles (23.6 percent). On the other hand, sales declined for sound &amp; video equipment (-33.9 percent), food (-3.4 percent) and home appliances, furniture (-11.4 percent). Retail trade excluding fuels rose 5.6 percent from a year earlier in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.marketwatch.com/story/moderna-aims-for-covid-flu-booster-in-2023-but-fauci-and-other-virus-experts-warn-of-challenges-to-come-this-year-11642433642 </td>
   <td style="text-align:left;"> 2022-01-17 23:33:00 </td>
   <td style="text-align:left;"> Moderna aims for COVID/flu booster in 2023, but Fauci and other virus experts warn of challenges to come this year - MarketWatch </td>
   <td style="text-align:left;"> Moderna’s chief executive officer Stephane Bancel said the company hopes to have a combined flu and COVID vaccine ready for 2023, but virus experts speaking on a panel Monday poured cold water on the possibly of the pandemic shifting to an endemic phase this year.                                                                                                                                                                                           , Bancel said in addition to an omicron vaccine that they hope will be ready for regulatory scrutiny by March, the company 
        MRNA,
        -2.59%
      hopes to have its combination flu/COVID jab ready by autumn of 2023. And this would go some ways toward breaking down resistance among individuals to vaccines.                                                                                                                                    , “Our goal is to be able to have a single annual booster so that we don’t have compliance issues where people don’t want to get to get two to three shots a winter, but to get one dose where they get a booster for Corona and a booster for flu and RSV to make sure people get their vaccines,” said Bancel in a virtual World Economic Forum panel on Monday.                                                                                                   , Virtual gatherings hosted by the World Economic Forum on Monday were being held instead of the annual January meeting in Davos, Switzerland, due to pandemic concerns.                                                                                                                                                                                                                                                                                             , Read: Xi touts China’s vaccine sharing, climate-change efforts in virtual Davos speech                                                                                                                                                                                                                                                                                                                                                                             , Also on the panel was Dr. Anthony Fauci, chief medical adviser to the president and director of the Institute of Allergy and Infectious Disease. He said an endemic phase, when the virus is more manageable and marked by greater population immunity, remains some ways off.                                                                                                                                                                                     , “I think if you look at the history of infectious diseases, we’ve only eradicated one infectious disease…and that’s smallpox, and that’s not going to happen with this virus,” said Fauci, who said he would consider the pandemic to have reached endemic status when it doesn’t disrupt society.                                                                                                                                                                 , “I really do think it remains to be seen whether omicron is going to be the live virus vaccination that everyone is hoping for because you have such a great deal of variability with variants,” he said.                                                                                                                                                                                                                                                          , Another panel member, Annelies Wilder-Smith, professor of emerging infectious diseases at the London School of Hygiene and Tropical Medicine, said she is hoping for the best-case scenario in the virus’s evolution. However, she said the world should be “prepared for the worst case” of another variant with high transmissibility and high mortality.  That’s the key allegation made by Dr. Robert Malone, a controversial doctor and pioneer mRNA reseacher, Read: Will this COVID-19 wave lead to herd immunity? Are you less likely to get sick again if you had omicron? Why this ‘milder’ variant is a double-edged sword                                                                                                                                                                                                                                                                                                   , Wilder-Smith said there were ,though, obvious positives compared with the start of the pandemic, when a global population of 7.7 billion had zero immunity to the virus, while now more than 50% of those billions have received two doses.                                                                                                                                                                                                                        , Misinformation surrounding vaccines remains a major global challenge ahead, the experts said, and Fauci addressed one belief that that too many boosters could be harmful for immune systems. That’s the key allegation made by Dr. Robert Malone, a controversial doctor and pioneer mRNA reseacher.                                                                                                                                                              , “Obviously if you just give a person an antigen all the time, you get a hyperactivity of immunity but giving boosters at different times, there’s no evidence that’s gonna hinder it,” said Fauci.                                                                                                                                                                                                                                                                 , That said, individuals need to need to understand that a good vaccine may not prevent initial infection, which may be mild, but still prevent most hospitalizations and death, such as what has been seen with the omicron variant.                                                                                                                                                                                                                                , Fauci added it was important experts don’t approach new every new variant with a “whack-a-mole” approach, rather he said they’re “trying to figure out what the mechanisms are that induces a response to a commonality among the potential variants we’re seeing and that can occur.”                                                                                                                                                                             , Fauci was asked in particular why the U.S., one of the world’s richest nations, is struggling so much to contain COVID, saying that was in part due to a “fractured and disparate accessibility to healthcare.                                                                                                                                                                                                                                                     , “We have  individuals who don’t have access to care, a higher degree of hospitalization and death in minority populations, but we also have such a degree of pushback against regular, normal, easy-to-understand health measures, reluctance to wear masks, reluctance to promote vaccinations and do public health measures.  If we all pulled together we’d be much better off,” he said.                                                                       , Investors looking for a brief respite from two weeks of volatile trading on Wall Street may get one on Monday, when Martin Luther King Jr. Day is observed this year.                                                                                                                                                                                                                                                                                              , Barbara Kollmeyer is an editor for MarketWatch in Madrid. Follow her on Twitter @bkollmeyer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/industrial-production </td>
   <td style="text-align:left;"> 2022-01-17 23:26:39 </td>
   <td style="text-align:left;"> Colombia Manufacturing Output Grows in November </td>
   <td style="text-align:left;"> Manufacturing production in Colombia rose 13.9 precent over a year in November of 2021, picking up from a 10.1 percent increase in the previous month. It was the 10th consecutive month of growth, with main upward pressure coming from food products (12.4 percent), chemical products (11.9 percent), rubber and plastic (21.2 percent), and paper production and cardboard (17.4 percent). On a seasonally, adjusted monthly basis, manufacturing production rose 0.8 percent, accelerating from a 0.6 percent increase in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/winter-storm-leaves-nearly-200000-without-power </td>
   <td style="text-align:left;"> 2022-01-17 23:20:00 </td>
   <td style="text-align:left;"> Winter storm leaves nearly 200,000 without power </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                              , The messy winter storm that is being blamed for two deaths in North Carolina has knocked out power for nearly 200,000 Americans Monday.                                                                                                                                        , As of late this morning, 30,342 customers were without electricity in South Carolina, followed by 29,214 in North Carolina and 24,990 in Georgia, according to the website Poweroutage.us.                                                                                     , In Georgia – where some parts of the state received up to 10 inches of snow – there were 23,277 customers without power, the website also reported.                                                                                                                            , In this photo provided by the Durham Police Department, a truck hangs from the highway N.C. 147 overpass after its cab apparently slid off the highway during winter weather, Sunday, Jan. 16, 2022, in Durham, N.C.  (AP/Durham Police Department / Associated Press)         , KENTUCKY CANDLE FACTORY'S TORNADO DAMAGE MIGHT COST 250 JOBS                                                                                                                                                                                                                   , The storm is now moving through the Northeast, but it’s being blamed for two deaths in North Carolina.                                                                                                                                                                         , A man and woman from South Carolina, both 41, died Sunday morning after becoming involved in a crash along I-95 near Rocky Mount while a "mixture of wintry precipitation" was falling in the area, WNCN reported, citing the North Carolina State Highway Patrol.             , As of 10:15 a.m. ET, more than 1,400 flights have been canceled in the U.S. as the winter storm moves Northeast, according to the website FlightAware.                                                                                                                         , A truck plows Interstate 40 near Lewisville-Clemmons Road in Clemmons, N.C., late Sunday afternoon. (Walt Unks/The Winston-Salem Journal via AP)                                                                                                                               , The Charlotte Douglas International Airport has suffered the most cancellations – with more than 200 – followed by airports in the New York City and Washington, D.C. areas.                                                                                                   , Over 900 U.S. flights have been delayed.                                                                                                                                                                                                                                       , This image provided by Virginia State Police shows the scene of a multi-vehicle crash on Interstate 81 in Culpeper County at Alanthus Rd. near Route 29 on Sunday. (Virginia State Police via AP)                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                    , The National Weather Service said Monday that the "major winter storm will continue heavy snow and strong winds today from the central Appalachians into Upstate New York and the higher elevations of New England with dangerous travel, power outages, and coastal flooding.", "Strong winds are expected behind the storm as far south as Georgia which could lead to additional power outages and tree damage, especially in areas with significant ice," it added.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/platinum </td>
   <td style="text-align:left;"> 2022-01-17 23:05:00 </td>
   <td style="text-align:left;"> Platinum Rebounds To Near 6-Week High </td>
   <td style="text-align:left;"> Platinum futures traded around $980 per troy ounce in the third week of January, not far from 6-week high of $990 per troy ounce hit on January 5th, amid a weaker dollar and in line with other precious metals. The dollar index weakened after the CPI report showed US annual inflation came in line with forecasts, easing concerns that the Fed would need to implement more aggressive tightening plans. Also, on January 11th, Federal Reserve Chair Jerome Powell dashed market expectations for a more hawkish approach. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-17 22:50:02 </td>
   <td style="text-align:left;"> Canadian Shares Extend Gains </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite Index was 0.3% higher to hover around 21,410 in the first trading day of the week, amid lower trading volumes from closed equity markets in the United States, supported by upbeat global sentiment and strong performing energy and banking sectors. Financial stocks were 0.4% higher, carried by the Royal Bank of Canada (0.7%) and the Bank of Nova Scotia (0.4%), while energy shares edged 0.8% higher despite subdued oil prices. On the economic data front, Canada reported that foreign investors acquired C$30.2 billion in Canadian securities during November of 2021, surpassing market expectations for the highest reading since April of 2020. At the same time, manufacturing sales were 2.6% higher on the month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-01-17 22:48:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Falls for 7th Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 1.9% to 1,731 on Monday, its lowest since early March 2021, extending losses for a seventh straight session, amid weaker seasonal demand across all vessel segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, declined 1.7% to 1,470, its lowest since late February 2021; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, fell 2.1% to 2,326. Among smaller vessels, the supramax index shed 33 points to its lowest level since April at 1,864. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/harvard-economist-on-how-long-prices-will-continue-to-soar </td>
   <td style="text-align:left;"> 2022-01-17 22:34:35 </td>
   <td style="text-align:left;"> Harvard economist on how long prices will continue to soar </td>
   <td style="text-align:left;"> Harvard University Professor Kenneth Rogoff argues that the Fed will be 'cautious' and certainly 'won’t overshoot for now on raising interest rates' as a way to curb inflation.                                                                                                                                                                                                                      , Harvard University professor Kenneth Rogoff explained on Monday why he believes inflation is not transitory and will stick around into next year.                                                                                                                                                                                                                                                     , "It’s not so easy to raise interest rates to fight inflation when public and private data is high, when the stock market is high, when housing prices are high, when the economy is still weak," The former chief economist at the International Monetary Fund noted on "Mornings with Maria" on Monday. "It takes a lot of stomach."                                                                 , He then noted that he believes the Federal Reserve will be "cautious" and certainly "won’t overshoot for now on raising interest rates," explaining that that’s why he believes "we’ll still have inflation in 2023."                                                                                                                                                                                 , Rogoff provided the insight less than one week after it was revealed inflation rose at the fastest pace in nearly four decades in December, as rapid price gains fueled consumer fears about the economy.                                                                                                                                                                                             , The consumer price index rose 7% in December from a year ago, according to a new Labor Department report released Wednesday, marking the fastest increase since June 1982, when inflation hit 7.1%. The CPI – which measures a bevy of goods ranging from gasoline and health care to groceries and rents – jumped 0.5% in the one-month period from November.                                        , Economists expected the index to show that prices surged 7% in December from the year-ago period, and 0.4% from the previous month.                                                                                                                                                                                                                                                                   , The eye-popping reading – which marked the seventh consecutive month the gauge has been above 5% – will likely amp up pressure on the Federal Reserve to begin hiking interest rates as soon as March in order to combat the recent price surge. Hiking interest rates tends to create higher rates on consumers and business loans, which slows the economy by forcing them to cut back on spending. , VanEck CEO Jan van Eck says the era of attractively priced goods and services is over.                                                                                                                                                                                                                                                                                                                , INFLATION CALCULATOR: SEE HOW HIGHER PRICES ARE HITTING YOUR WALLET                                                                                                                                                                                                                                                                                                                                   , Chairman Jerome Powell has already signaled the U.S. central bank plans to speed up its withdrawal of support for the U.S. economy in order to combat inflation, which has been higher and longer-lasting than policymakers initially expected.                                                                                                                                                       , Rogoff said that he believes the Fed takes their 2% inflation target "seriously," adding that the central bank also takes "having a recession seriously."                                                                                                                                                                                                                                             , "And I think the question is: How much are they going to have to step on the breaks to really slow inflation down?" he continued, noting that he believes the Fed will be conservative in their rate increases as the central bank has indicated.                                                                                                                                                     , He also pointed out that the Fed hasn’t "tried to raise interest rates to stop inflation really for almost 30 years now."                                                                                                                                                                                                                                                                             , "It’s not clear how it’s going to work," he added, stressing that there is "a lot of uncertainty."                                                                                                                                                                                                                                                                                                    , Rogoff then said that he believes that the Fed will eventually have to raise interest rates more than the central bank is initially planning on.                                                                                                                                                                                                                                                      , Harvard University professor Kenneth Rogoff, a former chief economist at the International Monetary Fund, explains why he believes inflation is not transitory and will still be around next year.                                                                                                                                                                                                    , Rising inflation is eating away at strong gains and wages and salaries that American workers have seen in recent months: Real average hourly earnings rose just 0.1% in December, as the 0.5% inflation increase eroded the 0.6% total wage gain, according to the Labor Department. On an annual basis, real earnings actually declined 2.4%.                                                        , Rogoff argued on Monday that pressure for increased wages due to inflation poses a "danger."                                                                                                                                                                                                                                                                                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                           , He said he thinks the Fed and other central banks "were sort of counting on being like the Bank of Japan where no matter what they do inflation does not seem go up, but it’s not as entrenched here, so wages have been trailing prices… and there are going to be pressures on that."                                                                                                               , "The service sector, if the economy comes back, it’s going to take a lot of wage increases to bring people back, people are feeling a lot of pricing pressure," he continued.                                                                                                                                                                                                                         , Rogoff went on to note that people have felt pricing pressures last year and will "very likely" again this year "unless the pandemic really takes a turn for the worse."                                                                                                                                                                                                                              , "I think that is going to be really difficult to push back on," he stressed.                                                                                                                                                                                                                                                                                                                          , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                               , FOX Business’ Megan Henney contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/17/beijing-shanghai-china-covid-omicron-case-olympics-dnt-newday-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-17 22:25:01 </td>
   <td style="text-align:left;"> 2022 Winter Olympics: China's new measures to contain Omicron - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/somalia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-17 22:24:40 </td>
   <td style="text-align:left;"> Somalia December Inflation Rate at Over 2-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Somalia quickened to 5.67 percent in December of 2021, from 5 percent in the previous month. It was the highest inflation rate since August of 2019, mainly due to higher prices of transport (4.28 percent vs 0.95 percent in November), food &amp; non-alcoholic beverages (7.39 percent vs 7.42 percent in November); housing &amp; utilities (5.49 percent vs 1.95 percent), health (14.09 percent vs 11.02 percent), and recreation &amp; culture (5.75 percent vs 4.15 percent). On a monthly basis, consumer prices edged down 0.22 percent, after a 0.63 percent uptick in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60015294?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-17 22:17:44 </td>
   <td style="text-align:left;"> Wealth of world's 10 richest men doubled in pandemic, Oxfam says </td>
   <td style="text-align:left;"> The pandemic has made the world's wealthiest far richer but has led to more people living in poverty, according to the charity Oxfam.                                                                                                                                                                                                                      , Lower incomes for the world's poorest contributed to the death of 21,000 people each day, its report claims.                                                                                                                                                                                                                                               , But the world's 10 richest men have more than doubled their collective fortunes since March 2020, Oxfam said.                                                                                                                                                                                                                                              , Oxfam typically releases a report on global inequality at the start of the World Economic Forum meeting in Davos.                                                                                                                                                                                                                                          , That event usually sees thousands of corporate and political leaders, celebrities, campaigners, economists and journalists gather in the Swiss ski resort for panel discussions, drinks parties and schmoozing.                                                                                                                                            , However for the second year running, the meeting (scheduled for this week) will be online-only after the emergence of the Omicron variant derailed plans to return to an in-person event.                                                                                                                                                                  , This week's discussions will include the likely future path of the pandemic, vaccine equity and the energy transition.                                                                                                                                                                                                                                     , Danny Sriskandarajah, Oxfam GB's chief executive, said the charity timed the report each year to coincide with Davos to attract the attention of economic, business and political elites.                                                                                                                                                                  , "This year, what's happening is off the scale," he said. "There's been a new billionaire created almost every day during this pandemic, meanwhile 99% of the world's population are worse off because of lockdowns, lower international trade, less international tourism, and as a result of that, 160 million more people have been pushed into poverty.", "Something is deeply flawed with our economic system," he added.                                                                                                                                                                                                                                                                                           , According to Forbes figures cited by the charity, the world's 10 richest men are: Elon Musk, Jeff Bezos, Bernard Arnault and family, Bill Gates, Larry Ellison, Larry Page, Sergey Brin, Mark Zuckerberg, Steve Ballmer and Warren Buffet.                                                                                                                 , While collectively their wealth grew from $700bn to $1.5tn between March 2020 and November 2021, there is significant variation between them, with Mr Musk's fortune growing by more than 1,000%, while Mr Gates' rose by a more modest 30%.                                                                                                               , Oxfam's decision to measure the growth from the start of the pandemic, when global share prices plummeted, also skews the findings slightly.                                                                                                                                                                                                               , The wealth of the world's richest is typically tied up in their stock holdings, which fell sharply in March 2020, meaning the subsequent growth was from this lower base.                                                                                                                                                                                  , If Oxfam had measured from just before the pandemic began, the growth would have been less pronounced.                                                                                                                                                                                                                                                     , However, one of the report's authors Max Lawson told the BBC: "If you take the wealth of billionaires in mid-February 2020 instead, we estimate that the increase in the top ten richest men is more like 70% - which would still represent a record breaking increase, and something the like of which we have never seen before."                        , Oxfam's report is based on data from the Forbes Billionaires List and the annual Credit Suisse Global Wealth report, which gives the distribution of global wealth going back to 2000.                                                                                                                                                                     , The Forbes survey uses the value of an individual's assets, mainly property and land, minus debts, to determine what he or she "owns". The data excludes wages or income.                                                                                                                                                                                  , The methodology has been criticised in the past as it means that a student with high debts, but with high future earning potential, for example, would be considered poor under the criteria used.                                                                                                                                                         , Oxfam also says that due to the fact prices have risen during the pandemic, it has adjusted for inflation using the US Consumer Price Index (CPI), which tracks how fast the cost of living is increasing over time.                                                                                                                                       , Oxfam's report, which was also based on data from the World Bank, said a lack of access to healthcare, hunger, gender-based violence and climate breakdown contributed to one death every four seconds.                                                                                                                                                    , It said 160 million more people were living on less than $5.50 (£4.02) a day than would have been without the impact of the Covid pandemic.                                                                                                                                                                                                                , The World Bank uses $5.50 a day as a measure of poverty in upper-middle-income countries.                                                                                                                                                                                                                                                                  , The report also says:                                                                                                                                                                                                                                                                                                                                      , "Even during a global crisis our unfair economic systems manage to deliver eye-watering windfalls for the wealthiest but fail to protect the poorest," Mr Sriskandarajah said.                                                                                                                                                                             , He said political leaders now had an historic opportunity to back bolder economic strategies to "change the deadly course we are on".                                                                                                                                                                                                                      , That should include more progressive tax regimes, which impose higher levies on capital and wealth, with the revenue spent on "quality universal healthcare and social protection for all" Mr Sriskandarajah said.                                                                                                                                         , Oxfam is also calling for the intellectual property rights on Covid-19 vaccines to be waived to enable wider production and faster distribution.                                                                                                                                                                                                           , Earlier this month the president of the World Bank, David Malpass, voiced his concerns over widening global inequality, arguing the impact of inflation and measures to tackle it were likely to cause more damage to poorer countries.                                                                                                                    , "The outlook for the weaker countries is still to fall further and further behind," he said.                                                                                                                                                                                                                                                               , This video can not be played                                                                                                                                                                                                                                                                                                                               , Five phrases attributed to famous figures, but did they even say them?!                                                                                                                                                                                                                                                                                    , Specially curated tracks to soothe your mind and spirit                                                                                                                                                                                                                                                                                                    , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-17 22:17:00 </td>
   <td style="text-align:left;"> Brazilian Equities Drop on Monday </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, was down 0.6% to around 106,275 on Monday, led by losses in miner Vale and steel companies, tracking falling iron ore prices. At the same time, Brazilian petrochemical producer Braskem slipped over 4% after it filed with the Securities and Exchange Commission on Friday for a share offering in which Petrobras and Novonor will sell their stakes in the petrochemical company. Traders also monitor the possibility of an escalation in the pressure of civil servants for salary readjustments, given the potential fiscal impact. Meanwhile, Central Bank of Brazil’s market expectations survey for 2022 showed growth projections were raised marginally to 0.29% from 0.28%, while inflation forecasts were revised higher to 5.09% from 5.03%. On the data front, the IBC-Br index of economic activity in Brazil rose by a more-than-expected 0.69% from a month earlier in November, after four consecutive months of drops and the most since last February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60018459?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-17 22:10:20 </td>
   <td style="text-align:left;"> Cladding crisis: Norwegian wealth fund urged to pressure firms and builders </td>
   <td style="text-align:left;"> Campaigners have urged Norway's giant state investment fund to pressure cladding firms and builders to fix fire safety issues.                                                                                                                                                             , Grenfell survivors and leaseholders affected by the cladding crisis called on Norges Bank to pull £5.7bn of funds from companies if they fail to do so.                                                                                                                                    , Lucy Brown-Cortes of the End Our Cladding Scandal campaign said pressure from shareholders was "overdue".                                                                                                                                                                                  , Norges said it had raised product safety with several of the companies.                                                                                                                                                                                                                    , The cladding crisis has left many people with huge bills to fix unsafe homes.                                                                                                                                                                                                              , After the Grenfell fire, which killed 72 people in 2017, flammable cladding and other fire safety defects were discovered in hundreds of blocks of flats across the UK.                                                                                                                    , Removing cladding can cost millions of pounds per block. The cost has often been passed on to flat owners under the leasehold system in England and Wales.                                                                                                                                 , Many leaseholders have also seen sharply increasing service charges, and some have had to pay for so-called "waking watch" fire wardens.                                                                                                                                                   , A letter was sent to the boss of Norges Bank Investment Management (NBIM) demanding action on Friday, as first reported by the Sunday Times.                                                                                                                                               , Its signatories include End Our Cladding Scandal, UK Cladding Action Group, Grenfell United, Action for Fire Safety Justice, the National Leasehold Campaign, Leasehold Knowledge Partnership and Tory MP Sir Peter Bottomley.                                                             , "This crisis has meant that at least 3,000,000 leaseholders are trapped in flammable flats they cannot sell, they are financing interim fire safety costs that they cannot afford to pay, and facing repossession/forfeiture over life-changing bills to make homes safe," the letter says., Nicolai Tangen, the chief executive of NBIM, should "leverage its position as major shareholder", it says, to push 11 firms to fix safety issues and provide compensation to victims of the Grenfell fire.                                                                                 , NBIM should "divest its holdings in these firms if they fail to do so", the letter adds.                                                                                                                                                                                                   , The fund is an investor in three companies that were involved in producing materials used on Grenfell Tower: Kingspan, Arconic and Saint-Gobain.                                                                                                                                           , NBIM also has stakes in different housebuilders, as pointed out by the campaigners, such as Barratt, Bellway, Berkeley, Crest Nicholson, LendLease, Persimmon, Taylor Wimpey and Vistry.                                                                                                   , Ms Brown-Cortes told the BBC that campaigners wanted to see NBIM "live up to their environmental, social and governance (ESG) credentials and leverage their position" as a major shareholder in some property developers.                                                                 , The biggest sovereign wealth fund in the world promotes itself as a "responsible" investor in more than 9,000 companies globally. It has previously cut tobacco companies from its portfolio, for example.                                                                                 , In its response to the campaigners, NBIM said it had "raised product safety with several of the companies mentioned in your letter" and it was a topic it would continue to monitor.                                                                                                       , NBIM added: "In accordance with the Fund's Ethical Guidelines, companies may be put under observation or be excluded if there is an unacceptable risk that the company contributes to or is responsible for serious or systemic violations of human rights.                                , "The independent Council on Ethics is responsible for assessing whether our investments are inconsistent with these guidelines. In line with our procedures, we have shared the information you have provided us with the Council of Ethics."                                              , This video can not be played                                                                                                                                                                                                                                                               , Housing Secretary Michael Gove backed the campaigners' "call to action" on Sunday.                                                                                                                                                                                                         , "Developers and cladding companies who caused these problems must pay to fix them. We want these companies to do the right thing and help end this scandal," he said.                                                                                                                      , It was confirmed last week that firms would be given until March to agree how to help leaseholders trapped in "unsellable homes".                                                                                                                                                          , Mr Gove warned those who had mis-sold unsafe cladding or cut corners on homes that the government was "coming for you".                                                                                                                                                                    , Residents in blocks 11-18m high had been ineligible for government support to remove unsafe cladding, but the Housing Secretary said earlier this week that the government was scrapping "the proposal for loans and long-term debt for medium rise leaseholders".                         , Mr Gove said some building companies had shown leadership and covered the costs but others "had not shouldered their responsibilities."                                                                                                                                                    , Five phrases attributed to famous figures, but did they even say them?!                                                                                                                                                                                                                    , Specially curated tracks to soothe your mind and spirit                                                                                                                                                                                                                                    , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/money/irs-backlog-premature-collection </td>
   <td style="text-align:left;"> 2022-01-17 22:07:48 </td>
   <td style="text-align:left;"> Massive IRS backlog triggers premature collection notices </td>
   <td style="text-align:left;"> The IRS warns tax refunds could be delayed due to staffing shortages and processing backlogs. FOX Business' Gerri Willis with the latest.                                                                                                                                                                                                                                                                                                                                      , The Internal Revenue Service is prematurely sending some Americans collection notices even though they filed their returns, as the agency works to wade through a deluge of unprocessed returns from years past.                                                                                                                                                                                                                                                               , That's according to a report from National Taxpayer Advocate Erin Collins, who warned that the IRS took too long to process taxpayer responses to its notices, further delaying refunds and in some instances, leading to premature collection notices – an occurrence that prematurely hurts low-income Americans.                                                                                                                                                            , The IRS sent tens of millions of notices to taxpayers in 2021, including 14 million math error notices, automated underreported notices (where an amount reported on a tax return did not match the corresponding amount reported to the IRS on Form 1099), notices requesting a taxpayer to authenticate his or her identity and collection notices.                                                                                                                          , IRS TAX-FILING SEASON TO KICK OFF ON JAN. 24                                                                                                                                                                                                                                                                                                                                                                                                                                   , In many cases, taxpayer responses were required; if individuals failed to respond – or they did and the IRS failed to process it due to the severe backlog – it could "take adverse action or not release the refund claimed on the tax return," Collins wrote.                                                                                                                                                                                                                , The problem is that many taxpayers did respond to the notices from the IRS, but the agency was so overwhelmed by the millions of unprocessed returns that it was still working through, that it did not process those responses. While the "normal" processing time for the agency is typically 45 days, Collins estimated that it's actually running close to six months or longer.                                                                                           , Blank W-4 form and a pen. Tax season                                                                                                                                                                                                                                                                                                                                                                                                                                           , To prevent enforcement actions before the IRS had adequate time to process taxpayer responses, the agency reprogrammed its computer systems. But there are gaps, Collins said. The IRS has a backlog of nearly 5 million pieces of taxpayer correspondence, some of which are from April.                                                                                                                                                                                      , If the IRS is mistaken, taxpayers will not owe any additional dues, penalties or interest. But it can still create a complicated resolution process.                                                                                                                                                                                                                                                                                                                           , "Like return processing delays, correspondence processing delays can harm taxpayers," the report said. "In cases where the IRS is holding a refund until it receives a taxpayer response, correspondence processing delays mean refund delays."                                                                                                                                                                                                                                , The difficulty this season – which officially begins Jan. 24 – stems from a massive pileup of unprocessed returns accrued during the pandemic: Collins estimated the IRS had a backlog of more than 8.6 million unprocessed individual income tax returns and 2.8 million business returns as of mid-December due to the pandemic and other related disruptions. It also had close to 5 million pieces of unanswered mail.                                                     , The IRS is grappling with office closures as well as the Herculean task of delivering millions of stimulus checks in 2020 and 2021. (Andrew Harrer/Bloomberg / Getty Images)                                                                                                                                                                                                                                                                                                   , By comparison, the IRS usually enters the tax-filing season with fewer than 1 million remaining items to address.                                                                                                                                                                                                                                                                                                                                                              , There are several reasons for the delays.                                                                                                                                                                                                                                                                                                                                                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                    , The IRS was grappling with office closures as well as the Herculean task of delivering millions of stimulus checks in 2020 and 2021, all while trying to adapt to major changes to the tax code in the middle of the filing season. The agency is also grossly understaffed; it has 20,000 fewer staff than it did in 2010, and its budget is roughly $11.4 billion – 20% less than it was in 2010, when adjusted for inflation, according to the Congressional Budget Office. , On top of that, more than 20% of the IRS customer service workforce has been unable to work for pandemic-related health reasons over the last two years.                                                                                                                                                                                                                                                                                                                       , "The IRS is in crisis and needs to apply resources to its core mission – processing returns and paying the corresponding refunds," the report said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-scotland-scotland-business-60002110?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-17 22:01:27 </td>
   <td style="text-align:left;"> ScotWind offshore auction raises £700m </td>
   <td style="text-align:left;"> An auction of seabed plots for major offshore wind projects around the Scottish coast has netted £700m.                                                                                                                                                            , Seventeen projects covering a total of 7,000km2 have been chosen in the first such leasing round in a decade.                                                                                                                                                      , They have a combined potential generating capacity of 25GW - well above the expected auction outcome of 10GW.                                                                                                                                                      , Scotland has 1.9GW of operational offshore wind, and another 8.4GW in construction or advanced development.                                                                                                                                                        , The ScotWind leasing auction attracted more than 70 bids from major oil companies, utility firms and investment funds from around the world.                                                                                                                       , Most of the sites are on the east, north east or northern coast, with just one on the western side of Scotland.                                                                                                                                                    , Successful bidders include Scottish Power, which won the seabed rights to develop three new offshore wind farms with a total capacity of 7GW.                                                                                                                      , They include two new floating projects in conjunction with Shell and one fixed project.                                                                                                                                                                            , Shell New Energies is the lead applicant on the most expensive development, off the coast of Aberdeen, estimated to cost £86m in option fees.                                                                                                                      , BP Alternative Energy Investments and SSE Renewables will each pay £85.9m in fees for two sites.                                                                                                                                                                   , The auction process was overseen by Crown Estate Scotland, with funds raised from the process going to the Scottish government.                                                                                                                                    , The winners have now been offered option agreements which reserve the rights to specific areas of seabed.                                                                                                                                                          , They include parts of the North Sea to the east of Angus, the outer Moray Firth, west of Orkney and north-west of both Lewis and Islay.                                                                                                                            , Although there was a sea area east of Shetland offered for the auction, this was not allocated to any bidder.                                                                                                                                                      , ScotWind represents a major sea-change in how we generate our electricity in Scotland.                                                                                                                                                                             , By the time they're all built, an estimated six million tonnes of carbon dioxide will be prevented from entering our atmosphere each year. That's about an eighth of all Scotland's emissions for 2019.                                                            , But we've already largely decarbonised our electricity sector. So, why build more offshore wind farms?                                                                                                                                                             , The inherent unpredictability of the wind means we need masses of overcapacity to allow us to keep the lights on when some of the turbines are not turning.  But those looking after the grid need to be more clever than just building more turbines.             , That means a growing use of smart technology and increased storage - through batteries or green hydrogen - will become critical in the coming years.                                                                                                               , Crown Estate Scotland chief executive Simon Hodge said: "Today's results are a fantastic vote of confidence in Scotland's ability to transform our energy sector.                                                                                                  , "In addition to the environmental benefits, this also represents a major investment in the Scottish economy, with around £700m being delivered straight into the public finances and billions of pounds worth of supply chain commitments."                        , First Minister Nicola Sturgeon described the ScotWind auction as a "truly historic opportunity for Scotland's net zero economy".                                                                                                                                   , She added: "The scale of opportunity represented in today's announcement exceeds our current planning assumption of 10GW of offshore wind - which is a massive vote of confidence in Scotland."                                                                    , Scottish Renewables said the announcement was "an exciting and significant moment in Scotland's renewable energy story".                                                                                                                                           , Chief executive Claire Mack added: "The potential for 17 new projects creates huge ambition for our sector to deliver on, and will require strong collaboration to deliver maximum impact for our economy and environment."                                        , WWF Scotland said the outcome was a "big vote of confidence in renewable power and Scotland's green economy".                                                                                                                                                      , The environmental group's climate and energy lead, Fabrice Leveque, said: "Offshore wind has a vital role to play in helping to cut our climate emissions, and is already powering hundreds of thousands of Scottish homes.                                        , "Each of these projects could create hundreds of jobs and will have a role in helping put Scotland on a path to a green recovery."                                                                                                                                 , However, RSPB Scotland criticised the announcement, claiming it could "accelerate some seabird species towards extinction in Scotland".                                                                                                                            , Aedan Smith, the charity's head of policy and advocacy said: "Offshore wind has an important role to play in helping halt climate change.                                                                                                                          , "However, the offshore wind projects already consented in Scotland are predicted to kill hundreds of seabirds like kittiwakes, gannets and puffins every year.                                                                                                     , "The potential projects announced today would be many times bigger than those existing projects and would greatly increase those impacts."                                                                                                                         , Meanwhile, the Scottish Fishermen's Federation (SFF) raised concerns about what the projects would mean for their industry.                                                                                                                                        , Chief executive Elspeth Macdonald said: "In the rush to energy transition, it is vital that our industry's voice is properly heard and that the fleet's access to Scotland's productive fishing grounds is protected.                                              , "In particular, proper scrutiny must be given to developers' claims that offshore windfarms and fishing activity can co-exist with little change to existing patterns of activity, since our experience to date shows very strongly that the opposite is the case.", The auction was originally meant to close at the end of March last year, but was delayed after a parallel English and Welsh auction resulted in far higher prices than expected.                                                                                   , At risk of losing out on hundreds of millions of pounds if it stuck to its original auction price guidelines, CES raised the cap for the auction bids from £10,000 to £100,000 per square kilometre.                                                               , The Scottish government has set a target of reaching net-zero emissions by 2045.                                                                                                                                                                                   , Five phrases attributed to famous figures, but did they even say them?!                                                                                                                                                                                            , Specially curated tracks to soothe your mind and spirit                                                                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/17/ford-signs-five-year-payments-deal-with-stripe-for-e-commerce-drive.html </td>
   <td style="text-align:left;"> 2022-01-17 22:00:01 </td>
   <td style="text-align:left;"> Ford signs five-year payments deal with Stripe for e-commerce drive </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                       , Online payment processor Stripe has signed up Ford Motor Company as a customer, in a five-year deal aimed at bolstering the automotive giant's e-commerce strategy.                                                                                                                                                                                   , Ford Motor Credit Company, the carmaker's financial services arm, will use Stripe's technology to process digital payments in markets across North America and Europe, the companies said in a statement Monday.                                                                                                                                      , Stripe will handle transactions for consumer vehicle orders and reservations, as well as bundled financing options for Ford's commercial customers. The automaker also plans to use Stripe to route a customer's payment from its website to the correct local Ford or Lincoln dealer.                                                                , The tie-up marks one of the biggest client wins yet for Stripe, and forms part of Ford's turnaround plan under CEO Jim Farley, who took the helm in October 2020.                                                                                                                                                                                     , Founded in 2010 by Irish brothers Patrick and John Collison, Stripe is the most valuable start-up in Silicon Valley, with a $95 billion valuation. The company sells software that makes it simple for businesses of all shapes and sizes to accept payments over the internet.                                                                       , The firm, which makes money by taking a small cut on each transaction it processes, counts the likes of Shopify, Salesforce and Deliveroo as customers. But it faces growing competition from rival fintechs such as Adyen and Checkout.com, which was valued at $40 billion in a $1 billion funding round last week.                                 , "We are making strategic decisions about where to bring in providers with robust expertise and where to build the differentiated, always-on experiences our customers will value," Marion Harris, CEO of Ford Motor Credit Company, said in a statement.                                                                                              , Ford expects to start rolling out Stripe's technology in the second half of 2022, starting with North America.                                                                                                                                                                                                                                        , "During the pandemic, people got comfortable paying online for groceries, health care, even home haircut advice from barbers," said Mike Clayville, Stripe's chief revenue officer. "Now, they expect to be able to buy anything and everything online."                                                                                              , Ford's market capitalization topped $100 billion for the first time last week, as investors cheered the firm's electric vehicle strategy and its Ford+ restructuring plan. The company was the best-performing auto stock in 2021, beating the likes of Tesla and General Motors.                                                                     , Stripe, meanwhile, is still privately held. There's long been speculation about when the company will go public. A Bloomberg report in September said Stripe had held talks with investment banks about going public as soon as 2022. But John Collison, Stripe's president, told CNBC a month later that the company is "very happy" staying private., Stripe hired Dhivya Suryadevara, the former chief financial officer of General Motors, as its finance chief in August 2020.                                                                                                                                                                                                                           , - CNBC's Michael Wayland contributed to this report                                                                                                                                                                                                                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/steel </td>
   <td style="text-align:left;"> 2022-01-17 21:59:00 </td>
   <td style="text-align:left;"> Steel Hovers Around 4,600Yuan/MT </td>
   <td style="text-align:left;"> Steel rebar futures have been trading around CNY 4,600 per tonne since mid-December, as investors balance a slowdown in demand against tight supplies and a surge in steelmaking ingredient nickel prices. Low temperatures and lockdowns to stem the spread of Covid have been reducing construction activity in many parts of China while factories maintenance in the first quarter, the Lunar New Year holidays and Beijing Winter Olympics in February limit production. Meanwhile, the China Iron and Steel Association said the balance between steel supply and demand has been achieved in 2021, and the yearly steel output is expected to be 1.03 billion tons, about 35 million tons less than a record 1.065 billion tons in 2020, amid policy enforcements on steel production cuts as the country aims to reduce energy consumption. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cocoa </td>
   <td style="text-align:left;"> 2022-01-17 21:50:40 </td>
   <td style="text-align:left;"> Cocoa Hits Over 3-Month High on Rising Demand </td>
   <td style="text-align:left;"> Cocoa futures rose to a 3-month high of around $2600 a tonne, amid tight supplies and rising demand. Data from the Cocoa Association of Asia showed Asia's fourth quarter cocoa grind, a key indicator of demand, rose 6.33% year-on-year to 231,309 tonnes. Meanwhile, light rains and mild seasonal winds in most of Ivory Coast's cocoa-growing regions raised outlooks for both October-to-March and April-to-September crops. Elsewhere, the International Cocoa Organization in its recent report projected that global demand for cocoa would go up by 4.9 million tonnes in the 2021/2022 cropping season whereas production would rise by 5.2 million tonnes due to better weather conditions in major producing countries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-01-17 21:48:00 </td>
   <td style="text-align:left;"> Copper Falls to 1-Week Low </td>
   <td style="text-align:left;"> Copper futures fell to a one-week low of $4.4 per pound in the third week of January, dragged down by rising inventories and demand concerns from top buyer China mainly due to a slowdown in the property sector. Stocks of copper in LME-registered warehouses rose by 6,550 tonnes to 92,850 tonnes, easing fears of tighter supplies on the LME market. Meanwhile, data showed property investment in China tumbled 13.9% year-on-year in December as regulators stepped up a campaign to cut high rates of borrowing, triggering defaults at some heavily indebted companies. Still, China is set to maintain relatively loose policies in the coming months to support the slowing economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/manufacturing-sales </td>
   <td style="text-align:left;"> 2022-01-17 21:39:00 </td>
   <td style="text-align:left;"> Canada Manufacturing Sales Rise Less than Expected </td>
   <td style="text-align:left;"> Manufacturing sales in Canada increased 2.6 percent from a month earlier to CAD 63.1 billion in November of 2021, easing from an upwardly revised 4.6 percent rise in the previous month and missing preliminary estimates of a 3.1 percent increase. Sales increased in 18 of the 21 industries, led by primary metals (5.8 percent) due to the resumption of production in major non-ferrous plants, while sales of petroleum and coal products (3.7 percent), and non-metallic minerals (10.4 percent) also increased. On the other hand, lower sales were recorded for machinery (-1.8 percent) and beverage and tobacco products (-4.4 percent). On a yearly basis, total sales were up 16.8 percent in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/foreign-stock-investment </td>
   <td style="text-align:left;"> 2022-01-17 21:35:00 </td>
   <td style="text-align:left;"> Investment in Canadian Securities at 1-1/2-Year High </td>
   <td style="text-align:left;"> Foreign investors acquired C$30.2 billion of Canadian securities in November of 2021, following a downwardly revised C$22.3 billion in October and above market expectations of C$23.5 billion. It was the 16th straight month of net purchases from foreigners and the largest amount since April 2020, targeting federal government debt securities by C$31.4 billion, and to a lesser extent, private corporate debt securities by C$9.8billion. On the other hand, non-resident investors reduced their overall exposure to the Canadian equity market by C$1.3 billion in November, after three consecutive months of investment. Meanwhile, Canadian investors increased their holdings of foreign securities by C$17.5 billion, led by purchases of US shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-17 21:17:06 </td>
   <td style="text-align:left;"> Russia Trade Surplus Widens in November, Exports at Near 8-Year High </td>
   <td style="text-align:left;"> Russia's trade surplus widened to USD 21.06 billion in November of 2021 from USD 7.39 billion in the corresponding month of the previous year. Exports surged 62.4 percent to USD 48.96 billion, the highest since December 2013, boosted by sales to non-CIS (64.8 percent) and CIS countries (49.2 percent). Meanwhile, imports rose at a softer 22.6 percent to USD 27.90 billion, driven by purchases from non-CIS (21.3 percent) and CIS countries (34.4 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/17/credit-suisse-needs-to-salvage-reputation-and-personnel-after-latest-scandal.html </td>
   <td style="text-align:left;"> 2022-01-17 21:13:19 </td>
   <td style="text-align:left;"> Credit Suisse needs to salvage reputation after chairman quits in latest scandal, analysts say </td>
   <td style="text-align:left;"> , LONDON — Credit Suisse Chairman Antonio Horta-Osorio resigned on Sunday after violating Covid-19 quarantine rules, the latest in a series of high-profile scandals that have rocked the Swiss bank in recent years.                                                                                                                                                                        , Horta-Osorio took over as chairman of Switzerland's second-biggest lender in April last year, with a mission to clean up its corporate culture after its damaging involvement with collapsed investment firm Archegos Capital and insolvent supply chain finance company Greensill.                                                                                                        , These came on the back of a bizarre and protracted spying saga which ultimately led to the resignation of former CEO Tidjane Thiam, who was replaced by Thomas Gottstein.                                                                                                                                                                                                                  , Horta-Osorio, who was found by an internal investigation to have committed multiple breaches of Covid quarantine requirements in the U.K. and Switzerland, will be replaced by UBS executive Axel P. Lehmann. Credit Suisse has insisted that its strategic overhaul, announced in November and which includes a scaling back of its investment banking business, will continue undeterred., Analysts told CNBC Monday that the bank had made the right call in removing Horta-Osorio, and that Lehmann was a wise appointment as the firm looks to deliver stability.                                                                                                                                                                                                                  , Bruno Verstraete, managing partner at Zurich-based asset manager Lakefield Partners, said Lehmann was a choice that represented the stability the bank needs, given his wealth of experience in risk management.                                                                                                                                                                           , "One can only hope that the scandals will fade over time, and that they will be able to turn the nose of the ship in the right direction, away from the storm. It is about time, that is clear," Verstraete told CNBC.                                                                                                                                                                     , However, some emphasized that the problems run deeper than one individual, with the bank facing a litany of legal issues.                                                                                                                                                                                                                                                                  , "I think the job at hand for Credit Suisse over the coming months and year is frankly to repair its risk management, to repair its reputation, and obviously one factor that needs to be looked at carefully is, can it retain its talent?" said Bob Parker, investment committee member at Quilvest and former senior advisor at Credit Suisse.                                           , "One thing that happened after Archego was that a number of talented people in the investment bank left the firm."                                                                                                                                                                                                                                                                         , Credit Suisse's share price has taken a substantial hit over the past 12 months, and analysts have pointed to the divergence from the performance of its domestic rival UBS as an indication that investors remain skeptical about the turnaround.                                                                                                                                         , Credit Suisse is down more than 24% over the past year and was last trading at 9.37 Swiss francs ($10.25) per share on Monday morning, while UBS has gained more than 31% in the past 12 months to trade at around 18 Swiss francs per share.                                                                                                                                              , "I think the performance of the share price in recent months clearly reflects the view by investors that a number of these legacy issues are going to take time to repair, and I think that is probably right," Parker said.                                                                                                                                                               , Beat Wittmann, chairman of Zurich-based Porta Advisors, told CNBC that Credit Suisse will need to rebuild its reputation over time through changing its business practices and demonstrating leadership by example, rather than seeking quick PR victories or "culture-washing."                                                                                                           , "The price performance difference between Credit Suisse and UBS is 50% — not five, 50% — and therefore the shares are cheap, but for many reasons cheap," Wittmann said.                                                                                                                                                                                                                   , However, he suggested that if the new chairman and management team can deliver stability and a strategic redirection with "discipline and focus," then Credit Suisse shares are a "big buy" at their current valuations.                                                                                                                                                                   , "Key shareholders like Harris Associates, Dodge &amp; Cox etc., have suffered for many years, and the general public as well, so it's all in the hands of management and the board to get this done. It's absolutely possible to get it done," he said.                                                                                                                                        , Credit Suisse's third-quarter revenues were strong and the bank beat profit expectations despite a hit from charges related to settling allegations of corruption in Mozambique, along with several other legal issues.                                                                                                                                                                    , Wittmann highlighted that along with sound financial fundamentals, Credit Suisse is operating against a very supportive macro backdrop.                                                                                                                                                                                                                                                    , "For banking businesses, the last year was one of the best years on record in terms of rising risk assets, record M&amp;A activity, basically all factors aligned and in favor of such a bank," he said.                                                                                                                                                                                       , Given the potential that could be unlocked should the revamp go as planned and the low share price, Wittmann said he would not be surprised to see strategic buyout efforts being launched for Credit Suisse, noting that "the European landscape is overdue for consolidation," as several regulators have pointed out.                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                           , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-17 21:00:51 </td>
   <td style="text-align:left;"> Japan Government Bond Yield Remains Elevated, BoJ Eyed </td>
   <td style="text-align:left;"> The yield on the benchmark Japan 10-year JGB was around 0.15% in the third week of January, close to levels not seen since February of 2021, and tracking a general rise in global bond yields, amid expectations the Federal Reserve will need tight monetary policy faster. Meanwhile, the Bank of Japan will likely continue with its ultra-easy monetary policy on Tuesday, but policymakers are also said to be debating how to communicate an eventual interest rate hike, Reuters reported. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-17 20:55:03 </td>
   <td style="text-align:left;"> Australia 10-Year Bond Yield Rises on Rate Hikes Expectations </td>
   <td style="text-align:left;"> The yield on the Australian 10-year government bond rose back to 1.9% during the third week of January, matching an over ten-week high touched on January 10th, amid expectations of quicker interest rate hikes. The US Federal Reserve is seen raising interest rates as early as March to curb inflation, amid improving outlooks for the economy and labor market. At the same time, markets have priced in up to three interest rate hikes by the Reserve Bank of Australia this year, as inflation pressure and expectations remain elevated and as unemployment levels continue to fall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/naphtha </td>
   <td style="text-align:left;"> 2022-01-17 20:54:00 </td>
   <td style="text-align:left;"> Naphtha Climbs to Near 2014 Highs </td>
   <td style="text-align:left;"> The naphtha market extended its upward momentum into the third week of January, with futures approaching levels not seen since September 2014 above the $760 per tonne level and tracking oil prices higher on the back of a tightening market. OPEC+ is gradually relaxing output cuts implemented when demand collapsed in 2020, but many smaller producers such as Lybia cannot raise supply and others have been wary of pumping too much oil in case of renewed Covid-19 setbacks. Meanwhile, the impact from the spread of Omicron coronavirus variant on fuel demand is seen limited and lower than previously expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60019735?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-17 20:42:23 </td>
   <td style="text-align:left;"> Credit Suisse boss Horta-Osorio resigns over Covid breaches </td>
   <td style="text-align:left;"> The chairman of global banking giant Credit Suisse, Antonio Horta-Osorio, has resigned with immediate effect after breaking Covid quarantine rules.                                                                                                                                                               , Mr Horta-Osorio, who was with the bank for just nine months, left following an internal investigation.                                                                                                                                                                                                            , The former boss of Lloyds Banking Group joined Credit Suisse after a series of scandals at the Swiss bank.                                                                                                                                                                                                        , But it has emerged he breached Covid rules last year, including by attending the Wimbledon tennis finals.                                                                                                                                                                                                         , "I regret that a number of my personal actions have led to difficulties for the bank and compromised my ability to represent the bank internally and externally," Mr Horta-Osorio said in a statement issued by the bank.                                                                                         , "I therefore believe that my resignation is in the interest of the bank and its stakeholders at this crucial time," he added.                                                                                                                                                                                     , Mr Horta-Osorio has been replaced by board member Axel Lehmann.                                                                                                                                                                                                                                                   , Last month, a preliminary investigation by Credit Suisse had found that Mr Horta-Osorio had breached Covid-19 rules.                                                                                                                                                                                              , He attended the Wimbledon tennis finals in July at a time when the UK's Covid-19 restrictions required him to be in quarantine.                                                                                                                                                                                   , Mr Horta-Osorio also breached Swiss Covid restrictions when, according to Reuters, he flew into the country on 28 November but left on 1 December. Swiss rules meant he should have quarantined for 10 days upon his arrival.                                                                                     , Mr Horta-Osorio joined Credit Suisse in April last year following a series of scandals at the bank,                                                                                                                                                                                                               , In February 2020, then-Credit Suisse chief executive Tidjane Thiam resigned after it was revealed the bank had spied on senior employees. Mr Thiam denied knowledge of the spying operations.                                                                                                                     , Credit Suisse has also been hit with huge losses in connection with the failed financial firm Greensill - which backed Liberty Steel - and Archegos, the US hedge fund which collapsed last year.                                                                                                                 , Last year, in a report into its relationship with Archegos, Mr Horta-Osorio said: "We are committed to developing a culture of personal responsibility and accountability."                                                                                                                                       , There are two narratives emerging from Antonio Horta-Osorio's short-lived tenure at the top of one of Swiss banking giants.                                                                                                                                                                                       , One is that he broke the rules, was investigated and, having been found in breach, was asked to step down.                                                                                                                                                                                                        , But allies of the former boss of Lloyds Banking Group insist that the board of Credit Suisse could have censured him rather than forced him out and suggest that the Swiss bank had not appreciated his efforts to reform an executive team and a culture that has been hit a series of scandals in recent years. , Credit Suisse clients lost billions after the bank funnelled them into financial products designed by the collapsed Greensill Capital while the bank itself took a multi-billion hit from the collapse of hedge fund Archegos.                                                                                    , The bank also found itself at the centre of an unusual spying scandal which saw the departure of chief executive Tidjane Thiam.                                                                                                                                                                                   , Ironically, the man Credit Suisse brought in to bring an end to a string of negative headlines is the subject of them this morning.                                                                                                                                                                               , Justin Tang, head of Asian research at investment firm United First Partners, said Credit Suisse "has been in the 'damaged goods' section for a while now".                                                                                                                                                       , "While Horta-Osorio was responsible for the new strategy, his short tenure means that the revamp is likely to only be in the nascent stage. The irony of it is that Horta was hired to fix the reputational damage to Credit Suisse and revamp its risk taking culture in the bank."                              , In his statement, Mr Horta-Osorio said: "I am proud of what we have achieved together in my short time at the bank."                                                                                                                                                                                              , But George Godber, fund manager at Polar Capital, told the BBC: "Only [nine] months in is not really time to achieve much.                                                                                                                                                                                        , "He was brought in to turn around the business - it is a bank that has been hit by scandal - and so it means that his reign has been cut short.                                                                                                                                                                   , "Not everybody is above the law for Covid restrictions."                                                                                                                                                                                                                                                          , Mr Horta-Osorio was chief executive at Lloyds Banking Group for 10 years, the start of which was marked by a surprise two month leave of absence to deal with severe sleep deprivation.                                                                                                                           , Later on, amid media reports of an extra-marital affair, Mr Horta-Osorio emailed Lloyds staff, saying: "I deeply regret being the cause of so much adverse publicity and the damage that has been done to the group's reputation.                                                                                 , "I have been a strong advocate of expecting the highest professional standards from everyone at the bank, and that includes me."                                                                                                                                                                                  , Speaking to the BBC, a spokesperson for Credit Suisse said that the bank would give no further details on Mr Horta-Osorio's resignation other than those in its statement.                                                                                                                                        , They also said that there were no plans to release the findings of the investigation.                                                                                                                                                                                                                             , This video can not be played                                                                                                                                                                                                                                                                                      , Five phrases attributed to famous figures, but did they even say them?!                                                                                                                                                                                                                                           , Specially curated tracks to soothe your mind and spirit                                                                                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/leading-economic-index </td>
   <td style="text-align:left;"> 2022-01-17 20:32:00 </td>
   <td style="text-align:left;"> Brazil Economic Activity Rebounds </td>
   <td style="text-align:left;"> The IBC-Br index of economic activity in Brazil rose by 0.69% from a month earlier in November of 2021, compared to a downwardly revised 0.3% drop in October and slightly above market expectations of a 0.65% increase. It was the first rise in economic activity after four consecutive drops and the biggest since last February, helped by a stronger than expected gain in services activity and retail sales. Year-on-year, the Brazilian economy grew a non-seasonally adjusted 0.43%, compared to a 1.55% contraction in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rubber </td>
   <td style="text-align:left;"> 2022-01-17 20:28:00 </td>
   <td style="text-align:left;"> Rubber Remains Close 2-Month High </td>
   <td style="text-align:left;"> Osaka rubber futures have been on the rise this year to settle around the 230 yen per kg level in mid-January, its highest since November 25th, amid a subdued yen and improved Chinese demand outlook. Imports from China are set to pick ahead of the week-long holiday for the Lunar New Year, which begins at the end of the month. Still, concerns persist that spreading Omicron coronavirus cases in Japan will slow economic activities and that supply may get tight as coronavirus curbs by rubber-producing countries in Southeast Asia would cause labour shortages at rubber farms. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60022166?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-17 19:47:58 </td>
   <td style="text-align:left;"> Amazon halts plan to block UK Visa credit cards amid talks </td>
   <td style="text-align:left;"> Amazon has dropped plans to block UK Visa credit card payments this week, as the two sides continue to try to resolve a dispute over payment fees.                                                                                                                                                        , "The expected  change regarding  the use of  Visa credit cards on Amazon.co.uk will no longer take place on January 19," Amazon said.                                                                                                                                                                     , Visa said it was "working closely to reach an agreement".                                                                                                                                                                                                                                                 , Amazon said last year that Visa payment costs were "an obstacle" to providing the best prices for customers.                                                                                                                                                                                              , But Visa accused Amazon of threatening to restrict consumer choice. "When consumer choice is limited, nobody wins," Visa said.                                                                                                                                                                            , Neither company has indicated when the talks might conclude. In an email to customers on Monday, Amazon said it was working closely with Visa on "a potential solution that will enable customers to continue using their Visa credit cards on Amazon.co.uk".                                             , An EU-enforced cap on fees charged by card issuers is no longer in place in the UK following Brexit.                                                                                                                                                                                                      , Both Visa and its rival Mastercard have raised the so-called interchange fee on cross-border transactions between businesses in the UK and the European Union following Brexit.                                                                                                                           , However, Amazon and Visa said last year that their dispute had nothing to do with the UK leaving the EU.                                                                                                                                                                                                  , They have been slugging it out in public and in private, now these two corporate heavyweights are going in for an extra round.                                                                                                                                                                            , Amazon is ahead on points in this bout. Given this announcement has come so close to the deadline, many customers would have already switched their primary Amazon payment method away from Visa. But the online retailer would also have been hurt financially if it had followed through on its threat. , The cancelling of the deadline, and the fact a new end date has not been set, suggests a deal is near. Neither Amazon nor Visa are saying much to be able to judge quite how close they are to a compromise.                                                                                              , This dispute is about more than just fees. It is also about control. Don't forget that Amazon has taken a different course with Mastercard, which is behind Amazon's reward card.                                                                                                                         , Amazon has previously declined to say how much Visa charges the retailer to process transactions made on credit cards.                                                                                                                                                                                    , Visa also declined to comment, though it claimed that on average it takes less than 0.1% of the value of a purchase.                                                                                                                                                                                      , The Payment Systems Regulator has raised concerns about competition in this sector, which is dominated by Visa and Mastercard.                                                                                                                                                                            , In a strategy published last week, it said one of its priorities was to promote competition between UK payment systems.                                                                                                                                                                                   , "We will focus more on improving competition between payment systems, not just competition within payment systems," its managing director Chris Hemsley said.                                                                                                                                             , "This is important because we know that the future of retail payments is becoming increasingly about digital payments, most of which are currently made using card payment systems."                                                                                                                      , Five phrases attributed to famous figures, but did they even say them?!                                                                                                                                                                                                                                   , Specially curated tracks to soothe your mind and spirit                                                                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-17 19:43:38 </td>
   <td style="text-align:left;"> Irish Trade Surplus Narrows in November </td>
   <td style="text-align:left;"> Ireland’s trade surplus narrowed to EUR 5.39 billion in November of 2021 from EUR 5.58 billion in the corresponding period of 2020. Imports increased by 6 percent to EUR 9.87 billion, driven by purchases of electrical machinery, appliances, and parts (127 percent to EUR 0.76 billion), petroleum (96 percent to 0.37 billion), and organic chemicals (42 percent to 0.95 billion). Purchases from Great Britain decreased by 18 percent and those from the EU decreased by 8 percent. Meanwhile, exports rose by a softer 2 percent to EUR 15.29, pushed by sales of electrical machinery, appliances, and parts (40 percent to EUR 1.13 billion), organic chemicals (16 percent to 2.32 billion), and food and live animals (15 percent to 1.13 billion). While sales to Great Britain rose by 16 percent, those to the EU decreased by 8 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/17/amazon-halts-plan-to-stop-accepting-visa-credit-cards-in-the-uk.html </td>
   <td style="text-align:left;"> 2022-01-17 19:31:28 </td>
   <td style="text-align:left;"> Amazon halts plan to stop accepting Visa credit cards in the UK </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                             , LONDON — Amazon has scrapped plans to stop accepting Visa credit cards in the U.K.                                                                                                                                                                                                                                                                                                                                                          , The e-commerce giant was expected to prevent Brits from using a Visa-issued credit card on its platform from Jan. 19. But in a statement Monday, the firm said the change "will no longer take place."                                                                                                                                                                                                                                      , "We are working closely with Visa on a potential solution that will enable customers to continue using their Visa credit cards on Amazon.co.uk," an Amazon spokesperson told CNBC by email.                                                                                                                                                                                                                                                 , Amazon initially made the shock announcement in November, citing "high fees Visa charges for processing credit card transactions." Visa at the time said it was "very disappointed" in the move and would work toward a resolution with Amazon.                                                                                                                                                                                             , The two companies have locked horns in the past, with Amazon announcing plans to introduce a 0.5% surcharge on Visa credit cards in Australia and Singapore last year.                                                                                                                                                                                                                                                                      , It's not yet clear why Amazon made the U-turn on its plan to ditch Visa credit cards in the U.K., nor whether the decision is final or temporary.                                                                                                                                                                                                                                                                                           , "Amazon customers can continue to use Visa cards on Amazon.co.uk after January 19 while we work closely together to reach an agreement," a Visa spokesperson told CNBC by email.                                                                                                                                                                                                                                                            , Following Brexit, Visa and rival payment processor Mastercard have hiked interchange fees, the cut they take on digital transactions between the U.K. and European Union. Card networks were allowed to raise their charges after an EU cap on interchange fees ceased to apply in Britain.                                                                                                                                                 , However, Amazon and Visa say the dispute is not related to the U.K.'s withdrawal from the EU. Instead, the move was interpreted by experts as a way for Amazon to get some bargaining power over Visa to lower its fees.                                                                                                                                                                                                                    , David Ritter, a financial services strategist at IT firm CI&amp;T, said the about-face from Amazon "comes as no surprise." He argues the move would have proven difficult given that customers' Visa credit cards may be tied to digital wallets like Apple Pay, Google Pay and PayPal, as well as Amazon's own Prime subscription service.                                                                                                     , "Amazon is a retail giant so it has some leverage, but there's no way it won't accept Visa cards," said Ritter. "It's more likely that Amazon has been applying pressure tactics. Major players in the retail space tend to have bespoke rates with payment firms, rather than paying published rates. The move by Amazon is likely a way to negotiate a longer-term agreement on rates, or even to push for a freeze to its current rates.", Amazon is not the only company complaining of the high costs associated with major card networks — another notable example was grocery chain Kroger's, which temporarily banned Visa credit cards at a number of its stores.                                                                                                                                                                                                                , Meanwhile, Visa and Mastercard are facing growing pressure from financial technology upstarts like Klarna and Afterpay, which offer "buy now, pay later" services that let shoppers split the cost of their purchases over a period of monthly installments.                                                                                                                                                                                , "This latest twist in the saga certainly shows the power of the Amazon brand," said Roger De'Ath, head of U.K. at fintech start-up TrueLayer. "Irrespective of the final decision or the solution offered, its initial announcement has now pushed the debate around card fees for merchants into the mainstream."                                                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/croatia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-17 19:28:43 </td>
   <td style="text-align:left;"> Croatia Inflation Rate at Over 13-Year High </td>
   <td style="text-align:left;"> Croatia’s annual inflation rate rose for the sixth consecutive month to 5.5 percent in December of 2021, from 4.8 percent in the previous month. It was the highest rate since October of 2008, led by soaring prices of food &amp; non-alcoholic beverages (7.9 percent vs 5.7 percent in November); and transport (11.4 percent vs 12.2 percent), primarily fuels &amp; lubricants (22.5 percent). Additional upward pressure came from costs of housing &amp; utilities (3.2 percent vs 3.5 percent); and restaurants &amp; hotels (4.5 percent vs 4 percent). On a monthly basis, consumer prices were flat, after a 0.7 percent uptick in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/greece/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-17 19:25:36 </td>
   <td style="text-align:left;"> Greece 10Y Bond Yield Hits 19-month High </td>
   <td style="text-align:left;"> Greece 10 Year Government Bond Yeld increased to a 19-month high of 1.595% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2022-01-17 19:24:38 </td>
   <td style="text-align:left;"> BSE Sensex Ends Flat on Monday </td>
   <td style="text-align:left;"> The BSE Sensex ended little changed at 61,308.91 on Monday after traders digested weak macroeconomic data last week and with gains in capital goods and autos countering the losses in technology and banks. Domestic sentiment remained muted as India reported over 260,000 fresh COVID cases although its two major capital cities, Delhi and Mumbai recorded a sharp fall in COVID-19 infections in the past two days.  Among the individual stocks, Ultra Cement Company surged 2.78% as it reported an 8% increase in its net profit beating market estimates. Besides this, Mahindra and Mahindra (+2.19%), Maruti (+2.08%), Tata Steel (+1.35%) and Tata Consultancy Services (+1.26%) were among the other top performers. On the other hand, the index was pulled down by heavyweights like Hindustan Computer Limited Technologies (-5.89%), Housing Development Finance Corporation (-1.53%), Axis Bank (-1.25%) and Tech Mahindra (-1.01%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/currency </td>
   <td style="text-align:left;"> 2022-01-17 19:21:18 </td>
   <td style="text-align:left;"> Turkish Lira Steady Ahead of TCMB Meeting </td>
   <td style="text-align:left;"> The Turkish lira remained steady at the 13.5 per USD level in the third week of January, ahead of the TCMB meeting on Thursday, in which the central bank is expected to hold the interest rates unchanged for the first time since August of 2021. Still, investors remained concerned about the future of Turkey’s currency and price stability following 500bps of unorthodox rate cuts over the past few months to support exports and growth. Data showed recently that the consumer price inflation hit a 19-year high of 36.08% in December, the highest under President Tayyip Erdogan's rule and well above the bank's target of 5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-17 19:18:00 </td>
   <td style="text-align:left;"> German 10-Year Bund Yield Hovers at 2-1/2-Year High </td>
   <td style="text-align:left;"> Germany's 10-year yield rose to -0.02% in the third week of January, nearing its highest in about two-and-a-half years on expectations the Federal Reserve would start hiking fed funds rate in March to combat inflation. On Friday, ECB President Christine Lagarde said euro zone inflation will fall from a record high this year and the ECB is ready to take any measures necessary to get it down to its 2% target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/nigeria/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-17 19:12:00 </td>
   <td style="text-align:left;"> Nigeria December Inflation Rate Edges Higher to 15.6% </td>
   <td style="text-align:left;"> Nigeria’s annual inflation rate rose to 15.63% in December of 2021, after eight straight months of decline, amid a slight acceleration in prices of major component food (17.4% vs 17.2% in November), linked to the increase in demand during the festive season. Upward pressure also came from non-food products, including transport (15%, the same as in November); clothing &amp; footwear (15.1% vs 14.8%); miscellaneous goods &amp; services (14.1% vs 14%); housing &amp; utilities (11.1% vs 10.6%), among others. The annual core inflation rate, which excludes the prices of agricultural produce, rose further to 13.87% in December, the highest since April of 2017, from 13.85% in the prior month. On a monthly basis, consumer prices inched up by 1.82%, the most since May of 2017, after a 1.08% increase in the prior month. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-01-18 14:42:24 UTC +8

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
   <td style="text-align:left;"> 2022-01-18 14:41:53 </td>
   <td style="text-align:left;"> $SPY when they don&amp;#39;t program bots for holidays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:41:46 </td>
   <td style="text-align:left;"> $SPY Let the Bulls crybabies get their $480 then Puts crash cash money for days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:41:43 </td>
   <td style="text-align:left;"> $SPY stonks only go up..... uk sending weapons is nothing burger.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:41:42 </td>
   <td style="text-align:left;"> $SPY its.over before it even starts bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:40:49 </td>
   <td style="text-align:left;"> $SPY  imagine this week it breaks out and up  $480 handle and stair steps 
Into a new channel I will die laughing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:40:38 </td>
   <td style="text-align:left;"> $SPY  Calls tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:40:16 </td>
   <td style="text-align:left;"> $SPY Is Bitcoin a good indicator for $SPY prediction of the day? $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:40:14 </td>
   <td style="text-align:left;"> $QQQ $AMD $SPY trades helped me take advantage of the selloff in the stock market today. Secured 437% on DOCU, doubling my portfolio in a single day! Joining this Discord community was the decision I&amp;#39;ve ever made! Thanks, tinyurl.com/fgh5ah2wabxx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:40:04 </td>
   <td style="text-align:left;"> $SPY Let me pump  ES_F for ya </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:40:00 </td>
   <td style="text-align:left;"> $SPY Real price will come out soon;, Follow price targets🚀 stocks.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:39:37 </td>
   <td style="text-align:left;"> $SPY ahh yes, of course. Futures green on a day we can&amp;#39;t trade...but the day we can, yes gap down of course. Classic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:39:32 </td>
   <td style="text-align:left;"> $SPY .....  ..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:39:15 </td>
   <td style="text-align:left;"> $SPY Ran out of Puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:39:04 </td>
   <td style="text-align:left;"> $SPY Puts everywhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:38:58 </td>
   <td style="text-align:left;"> $SPY yeah I bet everyone is just dying to buy in ! 🤡🌎🔥📉🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:38:47 </td>
   <td style="text-align:left;"> $SPY Make Puts Great Again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:38:14 </td>
   <td style="text-align:left;"> $SPY If everyone just buys Puts, then everyone wins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:37:52 </td>
   <td style="text-align:left;"> $V $SPY They have helped me to grow my account to almost 2.5 million.. stockplays.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:37:51 </td>
   <td style="text-align:left;"> $SPY go to sleep bulls it will be green by morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:37:40 </td>
   <td style="text-align:left;"> $SPY Puts Only Zone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:37:27 </td>
   <td style="text-align:left;"> $SPY Ukraine fud is done with as west  surrender before war ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:37:18 </td>
   <td style="text-align:left;"> $SPY 4636.50 gunna hit bid got nothing on it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:36:51 </td>
   <td style="text-align:left;"> $SPY WHats  all the WAR talk about? Care to share a link.. can see nothing in newss or twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:36:41 </td>
   <td style="text-align:left;"> $SPY  this is so bad for Calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:35:47 </td>
   <td style="text-align:left;"> $SPY retail bags go bust ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:35:13 </td>
   <td style="text-align:left;"> $SPY Green before your 42 year old pot head cousin yells at your aunt for not buying the chocolate chip waffles value pack. Eta: 2pm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:34:40 </td>
   <td style="text-align:left;"> Any bullish action left in crude will be inversely reflected in $SPY imo. There&amp;#39;s no way they&amp;#39;re going to tolerate 85+ crude and multiple rate hikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:34:36 </td>
   <td style="text-align:left;"> $SPY phuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:34:34 </td>
   <td style="text-align:left;"> $SPY  Could this be it ? The Final Fud show down ?  The “big-un” (big one) 
The wam bam thank u mam ? The big red ?
The straw that broke Kamala’s back ? The Biden burial ? Putin’s a’ shootin ? 
Black Goose no dip buy ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:34:29 </td>
   <td style="text-align:left;"> $SPY I wonder if Biden‘s upcoming draft will only include the vaccinated? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:34:10 </td>
   <td style="text-align:left;"> $SPY which one of you jammies slapped 15 on the bid I see you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:33:36 </td>
   <td style="text-align:left;"> $SPY yes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:33:15 </td>
   <td style="text-align:left;"> $QQQ $SPY Green by the bell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:33:11 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:32:50 </td>
   <td style="text-align:left;"> $SPY Do you consider buying Puts as Shorting? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:32:20 </td>
   <td style="text-align:left;"> $SPY Do you consider buying Puts as Shorting? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:32:10 </td>
   <td style="text-align:left;"> $SPY $QQQ Lichtenstein just invaded and took over France? 

Mexico is invaded Australia…. Again

Texas just took the Moon’s Dark Side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:32:06 </td>
   <td style="text-align:left;"> $SPY I wasn’t a member here for the Kung Flu market crash. I can only imagine how the feed was then if a .4% drop gets the bears this horny </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:31:10 </td>
   <td style="text-align:left;"> $SPY should see -1.5% day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:31:05 </td>
   <td style="text-align:left;"> $SPY how I feel about your 401k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:30:52 </td>
   <td style="text-align:left;"> $SPY short it… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:29:58 </td>
   <td style="text-align:left;"> $SPY should see -1.5% day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:29:26 </td>
   <td style="text-align:left;"> $QQQ $SPY No Dip buying.Not this time.. 26th Jpow speaking. Oil prices going up. Next month cpi data coming Feb 9th if I’m not wrong.. fed is looking for data to take actions. They hike immediately in March. May be April. There are very few places to hide money.. everything is overpriced in us markets. I think  everything will be fine in coming days. Big tech has developed rapidly. It will fucking automate everything. Unemployment rate gets high in next 2-3years.. money printing goes brrrrrrrrrrrrr… everything goes to moon.. 5G world baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:29:20 </td>
   <td style="text-align:left;"> $SPY @PivotPoint101 
I took the long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:29:12 </td>
   <td style="text-align:left;"> $SPY  so who’s enlisting, and who’s evading the draft ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:28:34 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m expecting $GS to get rekt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:28:07 </td>
   <td style="text-align:left;"> $SPY  They want Kiev as well. Mother Russia is a thirsty one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:28:03 </td>
   <td style="text-align:left;"> $SPY Shorting is useless when Puts pay out much better by margin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:28:00 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:27:55 </td>
   <td style="text-align:left;"> $SPY 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:27:54 </td>
   <td style="text-align:left;"> $SPY what happened. 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:27:27 </td>
   <td style="text-align:left;"> $SPY short everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:25:32 </td>
   <td style="text-align:left;"> $SPY  I picked the wrong nite to stop making Onlyfans videos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:25:24 </td>
   <td style="text-align:left;"> $SPY  Hey guys relax I mean  it’s only 100k soldiers at the border. There’s no way they’re planing on invading. It’s an exercise. A fishing trip even </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:24:47 </td>
   <td style="text-align:left;"> $SPY if you can get 2% on a 10 year treasury and inflation is 7% you are only losing 5% a year. Better sell my stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:24:40 </td>
   <td style="text-align:left;"> $SPY $ES $SPX If you really want to make a huge profit on stock trading. Then this community is for you.:&amp;quot;&amp;gt;:-    discord.io/aeaSXA6 
 
#03 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:24:17 </td>
   <td style="text-align:left;"> $SPY bear flag forming on the 5 min futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:24:10 </td>
   <td style="text-align:left;"> $SPY bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:24:08 </td>
   <td style="text-align:left;"> $SPY $RSX is a layup buy with USSA unraveling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:24:07 </td>
   <td style="text-align:left;"> $SPY just short the he&amp;#39;ll out of this and make Pelosi pay 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:24:07 </td>
   <td style="text-align:left;"> $SPY  GesundheitPuts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:23:58 </td>
   <td style="text-align:left;"> $SPY I’m sleepy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:23:58 </td>
   <td style="text-align:left;"> $SPY Word for next couple months will be Volatility!  OTM strangles will be your friend.  Wild swings coming both directions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:23:51 </td>
   <td style="text-align:left;"> $SPY  

US Pushes Back On Reports The West Is No Longer Considering Cutting Russia From The SWIFT International Payments System If It Attacks Ukraine - Politico </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:23:08 </td>
   <td style="text-align:left;"> $QQQ $V $AMD $SPY They have helped me to grow my account to almost 2.5 million. 100% recommend joining! 
 
It&amp;#39;s free joining 🚀 discord.io/7MktDXk3TA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:22:54 </td>
   <td style="text-align:left;"> $SPY  I believe the Futures Bottomed and the 10 Year Yield topped out.   Hey Bears 2 points off the SPY is a Big Nothing Burger.  SPY will still be well above 460.  LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:22:39 </td>
   <td style="text-align:left;"> $SPY futures=red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:22:12 </td>
   <td style="text-align:left;"> $SPY   Is Joe Biden a   GELDING   ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:21:57 </td>
   <td style="text-align:left;"> $BBIG 1% puts us at $40 pps just think about it! FOMO for LOMO $spy $fb $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:21:56 </td>
   <td style="text-align:left;"> $SPY Joesputs Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:21:44 </td>
   <td style="text-align:left;"> $SPY Nancy Putslosi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:21:02 </td>
   <td style="text-align:left;"> $SPY $AAPL  how do you want it ! 🤷‍♂️ https://youtu.be/uA13uMi9Hp0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:20:39 </td>
   <td style="text-align:left;"> $SPY Nancy Pelosi was forced to buy $1 million worth of Calls to gaslight the Bulls and avoid insider trading penalty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:20:38 </td>
   <td style="text-align:left;"> $SPY Oil certainly thinks we are about to go to war unless it&amp;#39;s just moving up from rates, I&amp;#39;m sure it&amp;#39;s both, and, inflation fears, plus 26th is in the forward view too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:19:55 </td>
   <td style="text-align:left;"> $SPY …462’s

This is what happened the last time we were at 462 (Tuesday the 11th) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:19:42 </td>
   <td style="text-align:left;"> $SPY Putin was born to buy Puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:19:36 </td>
   <td style="text-align:left;"> $SPY let it bounce tomorrow in the morning and then look for the chart to tell you what’s coming. In my opinion they are gonna finally break this downward </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:19:13 </td>
   <td style="text-align:left;"> $SPY Putin buys Puts with Putsinthemoney </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:19:09 </td>
   <td style="text-align:left;"> $SPY imma laugh if this reverses overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:18:35 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:18:20 </td>
   <td style="text-align:left;"> $SPY calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:18:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $AAPL  This has been escalating, escalating, escalating, and, as soon as I first heard it, I said, we&amp;#39;re in trouble.

We don&amp;#39;t have a wartime president, and, IF UK is going to go help Ukraine then China will be helping Russia. They are about to become VERY GOOD oil and energy buddies. 

They will be axis powers vs Western world, you watch, Putin will call on China&amp;#39;s help when UK and other countries go to Ukraine.

And, 100% certainty, USA will become involved </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:17:45 </td>
   <td style="text-align:left;"> $QQQ $V $AMD $SPY $PLUG :&amp;quot;:&amp;quot;:-- #01 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,959 
Goal: $100,000 by end of January. 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:17:36 </td>
   <td style="text-align:left;"> $SPY just say Puts in response to everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:16:59 </td>
   <td style="text-align:left;"> $SPY margin call ☎️ hey it’s a bear market ! 📉🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:16:42 </td>
   <td style="text-align:left;"> $SPY Day 1 new semester in Economics 101 college course. “Puts” then walk out of the class </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:16:37 </td>
   <td style="text-align:left;"> $SPY   So let’s say Biden says we won’t let this to happen and we will join the UK 
And CAN

What price do you see SPY ? Or $XBI  thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:16:29 </td>
   <td style="text-align:left;"> $SPY Congrats to all the bulls that held over the weekend, maybe you can have your job at McDonald&amp;#39;s back? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:16:26 </td>
   <td style="text-align:left;"> $SPY Maybe &amp;quot;Wonder Woman&amp;quot;  can help </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:16:24 </td>
   <td style="text-align:left;"> $SPY 
 we are only down half a percent hmm reverse imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:16:22 </td>
   <td style="text-align:left;"> $SPY can’t wait for the market to open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:16:07 </td>
   <td style="text-align:left;"> $SPY ouch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:15:49 </td>
   <td style="text-align:left;"> $SPY extra leverage bears 🐻 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:15:19 </td>
   <td style="text-align:left;"> $SPY put city baby…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:15:07 </td>
   <td style="text-align:left;"> $SPY we are only down half a percent hmm reverse imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:14:57 </td>
   <td style="text-align:left;"> $SPY keep in mind when I see nice 5% +
pullbacks from high, I like to go heavy &amp;amp; long into $SPXL . Bid/ask spread is abit thick but limit sells usually catch well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:14:41 </td>
   <td style="text-align:left;"> $SPY if UK going to Ukraine to fight against the Russian invasion, then buying oil is an excellent call for tomorrow. $UCO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:14:35 </td>
   <td style="text-align:left;"> $SPY imma leave it alone 2k on a holiday is enough don&amp;#39;t wanna be greedy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:14:25 </td>
   <td style="text-align:left;"> $SPY and half of the bulls are completely idiots🤣.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:14:18 </td>
   <td style="text-align:left;"> $SPY   OMG,  I dont know what to do Rick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:13:54 </td>
   <td style="text-align:left;"> $SPY 

Me at 7:00 ET — don’t be shy and join me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:13:46 </td>
   <td style="text-align:left;"> $SPY What to watch this week:

Goldman Sachs, Morgan Stanley, Bank of America, UnitedHealth Group and Netflix are among companies publishing earnings during the week

U.S. data includes Empire manufacturing Tuesday, housing starts Wednesday and jobless claims Thursday

Interest-rate decisions due from nations including Indonesia, Malaysia, Norway, Turkey and Ukraine, Thursday

EIA crude oil inventory report, Thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:13:34 </td>
   <td style="text-align:left;"> $SPY Convinced half the bears on this board are bots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:13:00 </td>
   <td style="text-align:left;"> $SPY perma bulls are in for a nice bank account flush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:12:24 </td>
   <td style="text-align:left;"> $SPY might take a long here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:10:41 </td>
   <td style="text-align:left;"> $SPY tomorrow is the day… dump coming…. 🤑🤑🤑🤑buy every dip in China $BABA $JD  QE in China.. interest rates slashed. $NIU .. dump $QQQ baby… $SPY blood bath coming  baby.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:10:04 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:10:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $NVDA  SPEAK JOE! 

God help us IF you don&amp;#39;t.

UK going to RUSSIA, folks, is bad-bad news.

THIS is very serious now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:09:42 </td>
   <td style="text-align:left;"> $SPY no buyers=easy short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:09:39 </td>
   <td style="text-align:left;"> $SPY $QQQ tomorrow should be fun 😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:09:29 </td>
   <td style="text-align:left;"> $SPY I don’t want this sheet to open tomorrow man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:09:29 </td>
   <td style="text-align:left;"> $SPY back to $420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:09:09 </td>
   <td style="text-align:left;"> $SPY $420.69 open likely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:08:31 </td>
   <td style="text-align:left;"> $SPY 469 open likely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:08:30 </td>
   <td style="text-align:left;"> $SPY it is time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:08:29 </td>
   <td style="text-align:left;"> $SPY  Wow,  Joe Biden Crashed his 4 year presidency inside of 11 months - thats gotta be record </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:08:01 </td>
   <td style="text-align:left;"> $SPY $459.60 open likely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:07:32 </td>
   <td style="text-align:left;"> $SPY How I like my bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:07:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $GOOG $AMD USA really should have made a statement by now regarding Russia actions + UK is heading over with troops and tanks.

We just wait too long for everything.

QE should have been stopped in July, but, mo, the Summer Of Wait, which has cost us dearly waiting, we&amp;#39;re in a super fix, inflation just goes on, worse and worse, war or no war. 

As soon as CHINA goes to Russia side , that is when things get ugly, deathly ugly....for the UK. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:07:20 </td>
   <td style="text-align:left;"> $SPY      Biden will save us all Putin is scared of him right ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:06:54 </td>
   <td style="text-align:left;"> $SPY buying every dip because im not a little betch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:06:52 </td>
   <td style="text-align:left;"> $SPY 🙌
 https://www.reddit.com/r/Epic_Economics/comments/s6qe7o/treasury_yields_climbing_to_records_as_they/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:06:46 </td>
   <td style="text-align:left;"> $SPY oil is going up again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:06:41 </td>
   <td style="text-align:left;"> $SPY Is $NASDAQ going to break through the unbreakable trend line? 😶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:06:28 </td>
   <td style="text-align:left;"> $SPY If the Russians invade Ukraine, will Joe Biden do like Obama did, when they took Crimea     and just lay down and take it ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:06:09 </td>
   <td style="text-align:left;"> $SPY na .5% red is nothing. Normal even. Will Open green. Is going to be a interesting couple weeks though. Bears are foaming at the mouth lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:05:33 </td>
   <td style="text-align:left;"> $SPY 

Straddled for the week and glad there’s lots of movement. Looks like it really wants to play out that H&amp;amp;S </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:05:20 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m not celebrating, i&amp;#39;ve seen dumbass V&amp;#39;s come out of nowhere before. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:05:12 </td>
   <td style="text-align:left;"> $SPY having my
Money in the stock market now feels like when I was on the airplane and I took this pic of the guys fixing the engine of my plane man 🥺 why ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:04:48 </td>
   <td style="text-align:left;"> $SPY imagine this is green by the morning lmaoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:04:41 </td>
   <td style="text-align:left;"> $PLUG $17.88 support watch $fcel $spy $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:04:06 </td>
   <td style="text-align:left;"> $SPY nonstop bad news 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:03:50 </td>
   <td style="text-align:left;"> $SPY 10 year creeping back up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:03:44 </td>
   <td style="text-align:left;"> $SPY still waiting for the crash ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:03:33 </td>
   <td style="text-align:left;"> $SPY hey you “future prime” home owners that gambled the mortgage check, my offer still stands. I’ll buy before the bank repos and rent back to ya. I’ll need prog of income though. 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:03:08 </td>
   <td style="text-align:left;"> $SPY Russia vs U.S.A. in a war would be interesting to see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:03:01 </td>
   <td style="text-align:left;"> $SPY Poooots all week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:02:25 </td>
   <td style="text-align:left;"> $SPY   Dammit, now I have to re-open my OnlyFans account </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:02:01 </td>
   <td style="text-align:left;"> $SPY lol.. we bulls get fucked tomorrow?? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:02:00 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ll buy calls tomorrow if it bounces, I just won&amp;#39;t hold them very long. :D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:01:51 </td>
   <td style="text-align:left;"> $QQQ , $IWM, $SPY
Bond yields up, meaning bonds being sold, meaning money is free in cash, money never sleeps, meaning it is going back to the stock market, why? because the stocks are dirt cheap, 
Economy 101…
Green in the morning, and after and after, futures are dumb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:01:46 </td>
   <td style="text-align:left;"> $SPY your account about to get nuked? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:01:41 </td>
   <td style="text-align:left;"> $SPY Does buying both sides profit either way? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:01:11 </td>
   <td style="text-align:left;"> $SPY if war is coming they aren’t raising rates lol but yields go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:01:10 </td>
   <td style="text-align:left;"> $SPY Can we name the next Covid variant the Putincron ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:00:58 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:00:46 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:00:42 </td>
   <td style="text-align:left;"> $SPY I don’t see really any negative news at the moment, other than, will Russia invade?  Rate hike is old news, been out there at least the last 6 month.  We likely be flat for the week, unless we get good er and forward guidance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 14:00:18 </td>
   <td style="text-align:left;"> $SPY First Timers probably have the best odds than all of us guessing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:59:47 </td>
   <td style="text-align:left;"> $SPY Why is it that when $SPY and $QQQ are deep green in the premarket, barely any attempts are made to bring them down but when they are deep red, significant attempts are made to move them up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:59:39 </td>
   <td style="text-align:left;"> $SPY $QQQ Warren Buffet: RECOMMENDATION FOR NEW INVESTORS
https://youtu.be/dzL2dxZnM_k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:59:35 </td>
   <td style="text-align:left;"> $SPY if I were a bull I’d just let the wife and kids sleep. They have 30 days to evict you. Plus all the paper work and court and all that. You got time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:59:32 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:59:32 </td>
   <td style="text-align:left;"> $SPY USA said any statement yet ? 

$QQQ $AAPL $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:59:01 </td>
   <td style="text-align:left;"> $SPY when there are allot of bears we should be bullish.  When there is allot of bulls we should be taking profits.  Remember that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:58:17 </td>
   <td style="text-align:left;"> $SPY bleed it out bears so we can buy it dirt  cheap for the next bull run. Love this game. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:58:10 </td>
   <td style="text-align:left;"> $SPY 

SERIOUSLY 🚨🥺

If we join this we crash for sure ! 
Putin getting in Ukrain we crash
New variant we crash 
Economy as it is we crash 

WTF dude what can we do ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:57:42 </td>
   <td style="text-align:left;"> $SPY  Phuck, its an 8 pack of frozen hotdogs thawing out in a sink of a gas station bathroom again  -  God dammit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:57:05 </td>
   <td style="text-align:left;"> $SPY rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:56:45 </td>
   <td style="text-align:left;"> $SPY $10 incoming Blank Check SPAC company merger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:56:26 </td>
   <td style="text-align:left;"> $SPY it’s coming ✔️✔️✔️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:56:04 </td>
   <td style="text-align:left;"> $SPY bulls will be eating hormel chili from Save-a-lot grocery store for the foreseeable future </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:56:03 </td>
   <td style="text-align:left;"> $QQQ $SPY Checking Futes.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:56:01 </td>
   <td style="text-align:left;"> $SPY $492 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:55:57 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:55:47 </td>
   <td style="text-align:left;"> $SPY Púts Variant discovered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:55:43 </td>
   <td style="text-align:left;"> $SPY    uh  oh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:55:39 </td>
   <td style="text-align:left;"> $SPY incoming bears tomorrow saying “this market is so manipulated” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:55:24 </td>
   <td style="text-align:left;"> $SPY funny as hell according to CNBC online article populist losing support from globalist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:55:06 </td>
   <td style="text-align:left;"> $SPY Delta, Lambda, Omicron, then finally PUTS variant✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:55:04 </td>
   <td style="text-align:left;"> $SPY ..about to get the long D  bulls! 🍆 💋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:54:58 </td>
   <td style="text-align:left;"> $SPY  imagine still buying Calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:54:38 </td>
   <td style="text-align:left;"> $SPY oil be like.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:54:33 </td>
   <td style="text-align:left;"> $SPY Smells like beef stew! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:54:24 </td>
   <td style="text-align:left;"> $SPY Bulls are so used to buying the Dip over the last 1.5 years and it has always worked out back to ATH&amp;#39;s and higher every time. Things have finally changed and it&amp;#39;d hard to unlearn this pattern they have traded for so long.  A lot of Bull traps have happened over the last 2-3 months.  The market has changed now, and They are giving back profits and blowing it up.  My advice is to just day trade and not carry over anything over more than a day or two, till we get some clear direction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:54:10 </td>
   <td style="text-align:left;"> $SPY Next COVID Variant starts with the letter P. Puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:54:02 </td>
   <td style="text-align:left;"> $SPY futes shittin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:53:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA AWWWWWWW LAWWWWWD TANKY TANK MCDUMPDUMP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:53:44 </td>
   <td style="text-align:left;"> $DWAC $SPY 🕯️📚 All of the Convid &amp;#39;variants&amp;#39; are named after Greek letters - Kappa (κ) Iota (ί) Beta (β) Delta (δ) Eta (η) Lambda (λ) Omicron (ο). Taken together they form the word κίβδηλο which means &amp;#39;counterfeit.&amp;#39;

Convid is FAKE. The &amp;#39;vaccines&amp;#39; are the weapon, the hospitals are 
the battlefield. Administrators, doctors and nurses are being paid by governments to kill people with &amp;quot;Covid protocol&amp;quot; which includes lethal drugs and ventilators. They are terrorists and war criminals in violation of the Nuremberg Code. Access is restricted to these crime scenes hide the genocide and maintain the narrative. The Rockefeller Medical Cabal uses the SERPENT ⚕️as its symbol. Snakes don&amp;#39;t heal. They administer deadly venoms. 💉💉

&amp;quot;For thy merchants were the princes of the earth; for with thy sorcery were all the nations deceived.&amp;quot; - Revelation 

Sorcery in Greek = pharmakeia 💊

Pharmakeia = drugs, &amp;#39;medicines,&amp;#39; sorcery 🧙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:53:15 </td>
   <td style="text-align:left;"> $SPY  OMG,  What happened </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:53:00 </td>
   <td style="text-align:left;"> $SPY bulls have to unlock the options on buying Puts😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:52:41 </td>
   <td style="text-align:left;"> $SPY pretty strong chance tech can fall 50%. There’s a couple gaps that need to be filled wayyyyyyyyyy down there $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:52:30 </td>
   <td style="text-align:left;"> $SPY I’ve seen this story before green by 9:30 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:52:28 </td>
   <td style="text-align:left;"> $SPY I think half the comments are paid bots, in todays society we now have this, it’s everywhere too.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:51:48 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:51:15 </td>
   <td style="text-align:left;"> $SPY Oh boi, an incurable variant! Time to Buy Calls! -permabulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:51:11 </td>
   <td style="text-align:left;"> $SPY Papa been a dealer in hard truths for awhile.  

https://youtube.com/shorts/w1EhBhtgL6s?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:50:55 </td>
   <td style="text-align:left;"> $PLUG $SPY $AMD Start trading over 4 month ago and i lost all of money, Now I&amp;#39;ve made over 147K+ profits after join their chat room and using their alerts. Highly recommended! tinyurl.com/skalertsforfreext </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:50:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $UVXY $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:50:45 </td>
   <td style="text-align:left;"> $SPY we need  a turnaround turnaround Tuesday... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:50:33 </td>
   <td style="text-align:left;"> $SPY imagine still buying Calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:49:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $GOOG 

Thursday was it? 

But, yeah, I distinctly remember Biden calling Putin to tone down attack talk AND PUTIN &amp;quot;IGNORED HIM.&amp;quot;    or  Secretery of state , Antony Blinken, maybe ignored him.
Either way, this is scary development, for the world, not just Russia and Ukraine. 

Dear Lord...Amen

And u should say a prayer now too 🙂

============
How qualified is Blinken dealing with wartime escalations? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:48:30 </td>
   <td style="text-align:left;"> $SPY Can we get the &amp;quot;crash&amp;quot; out of the way now and then blow it up like a moonshot for the rest of the year? k thx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:48:25 </td>
   <td style="text-align:left;"> $SPY The markets will fall when Covid is under control and many of the unknowns are known. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:47:49 </td>
   <td style="text-align:left;"> $SPY red futures equals red day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:47:23 </td>
   <td style="text-align:left;"> $AMC &amp;quot;Honey, why is the bank calling about a home equity loan&amp;#39;s missed payment? And what happened to Timmy&amp;#39;s college fund? MOASS? What are you talking about?&amp;quot; $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:47:13 </td>
   <td style="text-align:left;"> $SPY placin puts tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:46:55 </td>
   <td style="text-align:left;"> $SPY if warren buffet pulls out, its game over for everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:46:54 </td>
   <td style="text-align:left;"> $SPY 

So you all here are telling we are fck ? 

Come on $XBI  has wiped out all my gains and now this ? 

Give me a dam break man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:46:43 </td>
   <td style="text-align:left;"> $SPY $QQQ HOLY FUCK! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:46:34 </td>
   <td style="text-align:left;"> $SPY market could sell of and fed will be more dovish than expected or the market throws.a.tantrum and fed buys all the bonds and makes the bond market bubble.even bigger than u can ever imagine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:46:20 </td>
   <td style="text-align:left;"> $SPY vix is running! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:45:47 </td>
   <td style="text-align:left;"> $SPY it seems too easy for another market crash. they aint gonna do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:45:23 </td>
   <td style="text-align:left;"> $SPY what will be the price at open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:44:47 </td>
   <td style="text-align:left;"> $AMC $IWM $SPY small cap futures getting absolutely crushed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:44:45 </td>
   <td style="text-align:left;"> $QQQ You miscalculated the “dip”.
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:44:34 </td>
   <td style="text-align:left;"> $SPY Biden keeps saying, “we will not go back to days like March 2020.”😂😂😂 It means we are going back like days in March 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:43:57 </td>
   <td style="text-align:left;"> Today $SPY shows HOLD signal (TA) for short term. Technical analysis source: https://stockinvest.us/stock/SPY?utm_source=stocktwits&amp;amp;utm_medium=autopost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:43:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $ARKK More pain for growth stonck hodlers and Cathie Woodshed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:43:19 </td>
   <td style="text-align:left;"> $SPY Restart back to $10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:43:12 </td>
   <td style="text-align:left;"> $SPY Bulls by the end of the month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:43:07 </td>
   <td style="text-align:left;"> $SPY haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:42:59 </td>
   <td style="text-align:left;"> $SPY being removed by direct tv…

https://en.m.wikipedia.org/wiki/One_America_News_Network </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:42:58 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:42:40 </td>
   <td style="text-align:left;"> $SPY be like water 💧- Liquidate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:42:29 </td>
   <td style="text-align:left;"> $SPY 
what&amp;#39;s more realistic?
KFC soy chicken or 450 spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:42:09 </td>
   <td style="text-align:left;"> $SPY runnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:42:06 </td>
   <td style="text-align:left;"> $SPY Timing the market, not time in the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:41:44 </td>
   <td style="text-align:left;"> $SPY, do you know I hold my position during the weekend, even when it dropped Friday morning, and do you know why? Because the target is 440$. I just added to those positions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:41:38 </td>
   <td style="text-align:left;"> $SPY can this go 440 this week, someone please tell fast its urgent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:41:09 </td>
   <td style="text-align:left;"> $SPY  I believe the Futures bottomed.   If we open and the SPY drops 2-3 points and stays above 460 its going to be a Big Nothing Burger for the Bears and the Bears will yet Starve Again.   LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:41:08 </td>
   <td style="text-align:left;"> $SPY New Traders start out with the only choice to either Buy or do not buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:40:47 </td>
   <td style="text-align:left;"> $SPY bears get the lube ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:40:29 </td>
   <td style="text-align:left;"> $SPY damn the vibes are good in the lab tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:40:07 </td>
   <td style="text-align:left;"> $SPY $UAL $DAL $LUV in other news, rising interest rates are expected to curb a supply chain problem 🤡 and planes to be grounded in exchange for half a bar of 5G signal 🤡 ….libtards be libbin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:39:55 </td>
   <td style="text-align:left;"> $SPY Short term puts, long term calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:39:54 </td>
   <td style="text-align:left;"> $spy $kweb

China easing, US tightening with the biggest gap CQQQ and QQQ have ever seen. You do the math. Long KWEB on weakness imo - might continue to trough lower support range but time to accumulate for a 2 year swing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:39:23 </td>
   <td style="text-align:left;"> $tlt $spy $vxx there she goes… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:39:16 </td>
   <td style="text-align:left;"> $SPY spy is trending it’s real 🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:38:55 </td>
   <td style="text-align:left;"> $SPY Only choice noobs can do is Buy so they are forced to become Bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:38:53 </td>
   <td style="text-align:left;"> $SPY bulls , do you need to call miss Cleo ? 🤷‍♂️📉🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:38:20 </td>
   <td style="text-align:left;"> $SPY too many 460 puts. They will not get paid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:38:07 </td>
   <td style="text-align:left;"> $SPY Noobs bullish because they cannot short or do not know how to buy Puts in Options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:38:02 </td>
   <td style="text-align:left;"> $SPY looking weak..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:38:02 </td>
   <td style="text-align:left;"> $SPY Pretty soon, USA will be entering the conflict, that&amp;#39;s it, sub 400 espy immediately 

$AMZN $GOOG $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:37:53 </td>
   <td style="text-align:left;"> $SPY by tomorrow morning it will be green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:36:53 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:36:44 </td>
   <td style="text-align:left;"> $SPY relax </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:36:32 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA if you are on welfare, want your city, state or country looking like a war zone, or a drug addicted moron you vote democrat, no other reason to,, wake up America! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:36:14 </td>
   <td style="text-align:left;"> $SPY $AAPL  📉🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:35:29 </td>
   <td style="text-align:left;"> $SPY we are down by only 1/2% and bears acting like the world is ending </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:35:12 </td>
   <td style="text-align:left;"> $SPY SPY 2022-01-16 Trade Analysis Video: 
https://www.youtube.com/watch?v=orxujtX_hao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:34:23 </td>
   <td style="text-align:left;"> $SPY first move always a pump fake hold my bags and my nuts bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:34:18 </td>
   <td style="text-align:left;"> Armageddon Depression update https://intodayspaper.cmail20.com/t/ViewEmail/d/9081FB4F14E42B112540EF23F30FEDED/D26BC6F6CAEB86714BD7C9066BE4161D?alternativeLink=False $djia $SPX $NDX $spy $qqq 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:33:53 </td>
   <td style="text-align:left;"> $SPY bulls emotional damage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:33:53 </td>
   <td style="text-align:left;"> $SPY be green by the morning lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:33:51 </td>
   <td style="text-align:left;"> $SPY nah fr I’m literally a clown. See y’all tomorrow. Sorry culo,  not really tho tbh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:33:41 </td>
   <td style="text-align:left;"> $SPY Bring mother fucker Trump back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:33:29 </td>
   <td style="text-align:left;"> $SPY $SPX 10 yr. to the moon 🌚 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:33:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:32:39 </td>
   <td style="text-align:left;"> $SPY opens 459 … we’re going to the 450s baby… that 460 support going to get cracked by AM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:32:21 </td>
   <td style="text-align:left;"> $SPY 🤷‍♂️🤡🌎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:32:16 </td>
   <td style="text-align:left;"> $SPY ST&amp;#39;ers never disappoint

😁😁📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:32:14 </td>
   <td style="text-align:left;"> $SPY $475 tomorrow! Take it or leave it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:31:38 </td>
   <td style="text-align:left;"> $SPY LAUGHING ALL THE WAY TO THE BANK!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:31:26 </td>
   <td style="text-align:left;"> $SPY my 440 puts 1/28 price is not changing , futures are red, why my puts price is not changed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:31:19 </td>
   <td style="text-align:left;"> $SPY This is highly heightened all the sudden.

Know God.
Know peace.
No God 
No peace. 

Could set off China-Russia-USA relations toast. 

Could, worst case scenario here, a lot of other ones before this, 2 or so, it could set off WW3 
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:31:04 </td>
   <td style="text-align:left;"> $SPY I wonder how many poots the FED has through there proxies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:30:48 </td>
   <td style="text-align:left;"> $SPY $IPOF $AMD $50,000 a day keeps the 9 to 5 away; For a limited time, we are opening our trading chat-room to the public...   https://www.discord.io/rBHacCP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:30:43 </td>
   <td style="text-align:left;"> $SPY Can&amp;#39;t sleep UGH

Any advice to get some shut eye?

🙂👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:30:18 </td>
   <td style="text-align:left;"> $SPY kyler Murray more like Michael Burry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:29:43 </td>
   <td style="text-align:left;"> $SPY Both Russia and Ukraine have many of the best programmers in the world. Would suck if they blew each other up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:29:28 </td>
   <td style="text-align:left;"> $SPY where I check futures? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:29:22 </td>
   <td style="text-align:left;"> $SPY pipe it down bears  im going long on my calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:29:09 </td>
   <td style="text-align:left;"> $SPY $JETS $BA $AAL $LUV short them all https://www.reuters.com/technology/exclusive-major-us-airline-ceos-urge-action-avoid-catastrophic-5g-flight-2022-01-17/

Watch them steal more taxpayer $ for this incompetent management </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:28:35 </td>
   <td style="text-align:left;"> $SPY chamath is a repulsive human. in another life he would be a member of the jihad squad.  so many dirtbags in the nba and nfl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:28:04 </td>
   <td style="text-align:left;"> $SPY someone answer asap, futures are red, why wont my 440 puts 1/28 print? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:27:58 </td>
   <td style="text-align:left;"> $SPY @youngwarrren man this sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:27:39 </td>
   <td style="text-align:left;"> $SPY Just watching for my $UVXY calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:27:22 </td>
   <td style="text-align:left;"> $SPY Futes tripping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:27:09 </td>
   <td style="text-align:left;"> $SPY I guess the printed market economy isn’t the way to go (long term). Maybe it will just keep going and y’all should keep buying calls.  Looks oversold to me… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:27:02 </td>
   <td style="text-align:left;"> $SPY $BABA hahahahaha.... Epic gapdown😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:26:38 </td>
   <td style="text-align:left;"> $SPY 500 🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:26:37 </td>
   <td style="text-align:left;"> $SPY Futes are about to make that next leg down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:26:11 </td>
   <td style="text-align:left;"> $SPY $QQQ The market will be fine. Bonds yields rising just mean investors are getting more and more confident in the outlook of the US economy, stronger economy = higher stock prices in a long run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:26:02 </td>
   <td style="text-align:left;"> $SPY futures bobbie shmurdered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:25:56 </td>
   <td style="text-align:left;"> $SPY ok ok ok ok bulls need the price to go up ! 😂 https://www.reddit.com/r/wallstreetbets/comments/reberu/wsb_the_last_couple_of_weeks/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:25:33 </td>
   <td style="text-align:left;"> $SPY $QQQ bloodbath coming, 10 yr yield spiking into breakout territory, oil climbing, Naz futures down 1% already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:24:52 </td>
   <td style="text-align:left;"> $VXX going bullish EOD &amp;amp; into AH on Friday, &amp;amp; what’s going on with $NASDAQ $DJIA $SPY $RUT right now… 10 yr bullish chart. Makes perfect sense. 

It’s okay. Everything will be okay. 

🤮🤮

If you’re hedged. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:24:34 </td>
   <td style="text-align:left;"> $SPY  https://www.reddit.com/r/wallstreetbets/comments/s45ahf/stonks/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:24:32 </td>
   <td style="text-align:left;"> $SPY Ahhhh Will Biden be able to handle Putin, or do we need Trump back? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:24:25 </td>
   <td style="text-align:left;"> $SPY people say big market crash so how big? I mean don&amp;#39;t we go up and down? I have 27 shares average 426 so lower than this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:24:23 </td>
   <td style="text-align:left;"> $SPY Load puts. Big hands liquidate assets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:24:23 </td>
   <td style="text-align:left;"> $SPY 我的电话一文不值 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:24:21 </td>
   <td style="text-align:left;"> $SPY honestly us young people should rebel against the old boomers and take their money. Gates, buffet, dalio, bloomberg etc they’re too f*cking old, they shouldn’t have that much money, what are they gonna do with the money anyway? Buy fancy diapers? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:24:07 </td>
   <td style="text-align:left;"> $SPY let’s face it  Biden poll numbers are in the tank every demographic that voted for Biden disapprove except for dead people  which are unchanged at 99% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:23:43 </td>
   <td style="text-align:left;"> $SPY volatility is legal again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:23:41 </td>
   <td style="text-align:left;"> latexe37a3348930c121b47beb9f967840232SPY - holding on to 462 by the same stand. 
$NVDA $AMD $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:23:12 </td>
   <td style="text-align:left;"> $SPY Neg 1% at open tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:22:50 </td>
   <td style="text-align:left;"> $SPY call holders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:22:42 </td>
   <td style="text-align:left;"> $QQQ $DIA $SPY you vote democrat you get poverty, dummies, you were worried that a president had more balls than you before and said what he felt like saying, now you’re stuck with the imbicil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:22:38 </td>
   <td style="text-align:left;"> $SPY this will be green by open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:22:22 </td>
   <td style="text-align:left;"> $SPY if your bearish do a pussy fart lol ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:22:18 </td>
   <td style="text-align:left;"> $SPY Эдриан Тотьма </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:21:14 </td>
   <td style="text-align:left;"> $SPY So the $QQQ futures dip of -0.27% from the short holiday session will tacked on to the current dip and that will reflect in the QQQ stock price right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:21:13 </td>
   <td style="text-align:left;"> $SPY tomorrow is gunna touch -2% or more. 456 gap fill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:21:04 </td>
   <td style="text-align:left;"> $SPY incase you missed it the other day  https://www.reddit.com/r/wallstreetbets/comments/s3w3j1/cathie_wood_rn_while_investors_lose_half_their/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:21:02 </td>
   <td style="text-align:left;"> $SPY what cardinals game looked we like @CuloCapital 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:21:02 </td>
   <td style="text-align:left;"> $SPY $QQQ Brandon isnt the Answer and neither is Big Orange.

DEMs not the Answer and neither are the REPUBs

Go fish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-18 13:20:11 </td>
   <td style="text-align:left;"> $SPY someone answer asap , will my 440 puts 1/28 print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:40:53 </td>
   <td style="text-align:left;"> $QQQ this etf is controlled by like 10 stocks lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:40:14 </td>
   <td style="text-align:left;"> $QQQ $AMD $SPY trades helped me take advantage of the selloff in the stock market today. Secured 437% on DOCU, doubling my portfolio in a single day! Joining this Discord community was the decision I&amp;#39;ve ever made! Thanks, tinyurl.com/fgh5ah2wabxx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:38:15 </td>
   <td style="text-align:left;"> $QQQ poor performance in Jan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:36:33 </td>
   <td style="text-align:left;"> $QQQ  poor performance in Jan. - </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:35:50 </td>
   <td style="text-align:left;"> $QQQ yikes 10 year breaking out.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:35:03 </td>
   <td style="text-align:left;"> $MSFT $QQQ At this point, I’d rather this be down than up at open.  If it’s up it will sell off- if it’s down decent chance it rallies off the bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:34:56 </td>
   <td style="text-align:left;"> $QQQ They have helped me to grow my account to almost 2.5 million. stockplays.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:33:27 </td>
   <td style="text-align:left;"> $QQQ Why the selloff in the QQQ, 10 year bond yield 1.841% up from Fridays close at b1.793%, thats a huge move for a bond. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:33:15 </td>
   <td style="text-align:left;"> $QQQ $SPY Green by the bell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:32:37 </td>
   <td style="text-align:left;"> $MARA $QQQ &amp;quot;:&amp;quot;::-- #05 
 
Who needs WallStreetBets when you have Xtrades. Thanks to Xtrades, I have doubled my entire portfolio in just one week. Joining this Discord community was the best investment I&amp;#39;ve ever made!  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:32:10 </td>
   <td style="text-align:left;"> $SPY $QQQ Lichtenstein just invaded and took over France? 

Mexico is invaded Australia…. Again

Texas just took the Moon’s Dark Side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:31:06 </td>
   <td style="text-align:left;"> $QQQ poor performance in Jan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:29:26 </td>
   <td style="text-align:left;"> $QQQ $SPY No Dip buying.Not this time.. 26th Jpow speaking. Oil prices going up. Next month cpi data coming Feb 9th if I’m not wrong.. fed is looking for data to take actions. They hike immediately in March. May be April. There are very few places to hide money.. everything is overpriced in us markets. I think  everything will be fine in coming days. Big tech has developed rapidly. It will fucking automate everything. Unemployment rate gets high in next 2-3years.. money printing goes brrrrrrrrrrrrr… everything goes to moon.. 5G world baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:23:08 </td>
   <td style="text-align:left;"> $QQQ $V $AMD $SPY They have helped me to grow my account to almost 2.5 million. 100% recommend joining! 
 
It&amp;#39;s free joining 🚀 discord.io/7MktDXk3TA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:22:36 </td>
   <td style="text-align:left;"> $QQQ 1am bounce on the way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:22:22 </td>
   <td style="text-align:left;"> $QQQ today is the official day the fed drops to 60b a month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:21:57 </td>
   <td style="text-align:left;"> $BBIG 1% puts us at $40 pps just think about it! FOMO for LOMO $spy $fb $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:21:56 </td>
   <td style="text-align:left;"> $QQQ slow ride back up into the sunrise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:20:17 </td>
   <td style="text-align:left;"> $QQQ poooooooootssssss city boys… 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:18:58 </td>
   <td style="text-align:left;"> $QQQ dip 30-50% incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:18:35 </td>
   <td style="text-align:left;"> $QQQ down 2%. Must be powell unloading all his shares again. Snake. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:18:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $AAPL  This has been escalating, escalating, escalating, and, as soon as I first heard it, I said, we&amp;#39;re in trouble.

We don&amp;#39;t have a wartime president, and, IF UK is going to go help Ukraine then China will be helping Russia. They are about to become VERY GOOD oil and energy buddies. 

They will be axis powers vs Western world, you watch, Putin will call on China&amp;#39;s help when UK and other countries go to Ukraine.

And, 100% certainty, USA will become involved </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:17:45 </td>
   <td style="text-align:left;"> $QQQ $V $AMD $SPY $PLUG :&amp;quot;:&amp;quot;:-- #01 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,959 
Goal: $100,000 by end of January. 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:13:26 </td>
   <td style="text-align:left;"> $QQQ 
 a bunch of little fags writing blck tuesday, green by lunch bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:13:06 </td>
   <td style="text-align:left;"> $QQQ dip before the rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:11:42 </td>
   <td style="text-align:left;"> $QQQ don&amp;#39;t celebrate yet bears....totally could be green by open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:10:41 </td>
   <td style="text-align:left;"> $SPY tomorrow is the day… dump coming…. 🤑🤑🤑🤑buy every dip in China $BABA $JD  QE in China.. interest rates slashed. $NIU .. dump $QQQ baby… $SPY blood bath coming  baby.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:10:20 </td>
   <td style="text-align:left;"> $QQQ a bunch of little fags writing blck tuesday, green by lunch bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:10:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $NVDA  SPEAK JOE! 

God help us IF you don&amp;#39;t.

UK going to RUSSIA, folks, is bad-bad news.

THIS is very serious now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:09:39 </td>
   <td style="text-align:left;"> $SPY $QQQ tomorrow should be fun 😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:08:15 </td>
   <td style="text-align:left;"> $QQQ and yet it keeps dropping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:07:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $GOOG $AMD USA really should have made a statement by now regarding Russia actions + UK is heading over with troops and tanks.

We just wait too long for everything.

QE should have been stopped in July, but, mo, the Summer Of Wait, which has cost us dearly waiting, we&amp;#39;re in a super fix, inflation just goes on, worse and worse, war or no war. 

As soon as CHINA goes to Russia side , that is when things get ugly, deathly ugly....for the UK. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:06:40 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;m so fuckig passed off at this market... Just a few weeks ago until Jan 3rd, I was short heavily on the market and lost heavily as this pigs just kept going up. Then I gradually reduced my short positions and became long as the market fell and this muthufucker POs keeps going down. It has caused me so much pain both ways.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:05:04 </td>
   <td style="text-align:left;"> $QQQ dump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:03:55 </td>
   <td style="text-align:left;"> $QQQ to the mooon. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:03:34 </td>
   <td style="text-align:left;"> $QQQ is the #1 trending ticker on Stocktwits as Nasdaq futures are down more than 1% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:02:58 </td>
   <td style="text-align:left;"> $QQQ sheessshhh down nearly 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:01:55 </td>
   <td style="text-align:left;"> $QQQ https://phunwallet.app.link/YFubwlIDVkb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:01:51 </td>
   <td style="text-align:left;"> $QQQ , $IWM, $SPY
Bond yields up, meaning bonds being sold, meaning money is free in cash, money never sleeps, meaning it is going back to the stock market, why? because the stocks are dirt cheap, 
Economy 101…
Green in the morning, and after and after, futures are dumb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 14:00:58 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:59:47 </td>
   <td style="text-align:left;"> $SPY Why is it that when $SPY and $QQQ are deep green in the premarket, barely any attempts are made to bring them down but when they are deep red, significant attempts are made to move them up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:59:39 </td>
   <td style="text-align:left;"> $SPY $QQQ Warren Buffet: RECOMMENDATION FOR NEW INVESTORS
https://youtu.be/dzL2dxZnM_k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:59:32 </td>
   <td style="text-align:left;"> $SPY USA said any statement yet ? 

$QQQ $AAPL $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:58:37 </td>
   <td style="text-align:left;"> $QQQ no green day in 2022 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:58:00 </td>
   <td style="text-align:left;"> $QQQ  $AMD  $BBIG    
$50,000 a day keeps the 9 to 5 away,, Big thanks to this chat ][ 
discord.io/trade_view </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:57:02 </td>
   <td style="text-align:left;"> $QQQ 10 year yield gonna fuck the market tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:56:03 </td>
   <td style="text-align:left;"> $QQQ $SPY Checking Futes.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:54:03 </td>
   <td style="text-align:left;"> $QQQ the whole world market went green yesterday. America opens. It is crashing. Ridiculus pos… this is pure manipulation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:53:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA AWWWWWWW LAWWWWWD TANKY TANK MCDUMPDUMP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:52:41 </td>
   <td style="text-align:left;"> $SPY pretty strong chance tech can fall 50%. There’s a couple gaps that need to be filled wayyyyyyyyyy down there $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:51:53 </td>
   <td style="text-align:left;"> $QQQ .. buying this dip in the morning if it doesn&amp;#39;t recover before open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:50:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $UVXY $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:49:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $GOOG 

Thursday was it? 

But, yeah, I distinctly remember Biden calling Putin to tone down attack talk AND PUTIN &amp;quot;IGNORED HIM.&amp;quot;    or  Secretery of state , Antony Blinken, maybe ignored him.
Either way, this is scary development, for the world, not just Russia and Ukraine. 

Dear Lord...Amen

And u should say a prayer now too 🙂

============
How qualified is Blinken dealing with wartime escalations? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:48:22 </td>
   <td style="text-align:left;"> $ADA.X $QQQ $V Start trading over 3 month ago and i lost all of money, Now I&amp;#39;ve made over 67K+ profits after join their chat room and using their alerts. Highly recommended! tinyurl.com/alertsfreeforsstocking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:48:06 </td>
   <td style="text-align:left;"> $QQQ 10/10 people knows this will dump tomorrow. It will 100%, but out of those 10, I bet maybe 1-2 have puts or open shorts max lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:46:43 </td>
   <td style="text-align:left;"> $SPY $QQQ HOLY FUCK! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:44:53 </td>
   <td style="text-align:left;"> $QQQ Rippin&amp;#39; titties </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:44:45 </td>
   <td style="text-align:left;"> $QQQ You miscalculated the “dip”.
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:43:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $ARKK More pain for growth stonck hodlers and Cathie Woodshed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:43:14 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:43:09 </td>
   <td style="text-align:left;"> $QQQ bond yields have shit to do with this market coming down..all propaganda..when bond yields came down heavy 1 day last week..market still tanked. No real money being put in something giving negative returns on top of inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:43:03 </td>
   <td style="text-align:left;"> Please daily traders, stop shorting the market so it crashes sooner. The more you short, the more it will rise. Wallstreet don&amp;#39;t like shorts. Let it be and come back when it crashes. The only reason Dow been going down is I no longer short. They were trying to squeez me while it was breaking records. But I never gave up until I was making money. Won&amp;#39;t do it again!
$SSO $DJIA $QQQ $QLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:41:58 </td>
   <td style="text-align:left;"> $QQQ literal maggard on the sidewalk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:41:43 </td>
   <td style="text-align:left;"> $HOMERUN.X $QQQ $T  flexing my gains because these guys are straight fire.,,.,; discord.io/Mr6AYuXT 
., </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:41:33 </td>
   <td style="text-align:left;"> $QQQ longs bend over like the little bitches you are </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:41:17 </td>
   <td style="text-align:left;"> $QQQ if QQQ is trending it’s real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:36:46 </td>
   <td style="text-align:left;"> $QQQ Who would put his money in bond?

10 years %2 

Buy any shitcoin, you would have more return in 10 years 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:36:32 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA if you are on welfare, want your city, state or country looking like a war zone, or a drug addicted moron you vote democrat, no other reason to,, wake up America! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:35:26 </td>
   <td style="text-align:left;"> $QQQ how much more can you fucking sell.  Thank you Biden for this wonderful economy. Since this mother fucking retard and senile president came to office I lost sooo much fucking money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:34:18 </td>
   <td style="text-align:left;"> Armageddon Depression update https://intodayspaper.cmail20.com/t/ViewEmail/d/9081FB4F14E42B112540EF23F30FEDED/D26BC6F6CAEB86714BD7C9066BE4161D?alternativeLink=False $djia $SPX $NDX $spy $qqq 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:33:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:33:05 </td>
   <td style="text-align:left;"> $QQQ real yields are still negative </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:30:23 </td>
   <td style="text-align:left;"> $QQQ why the fuck futures are down ? NasDaq down by 150 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:29:53 </td>
   <td style="text-align:left;"> $QQQ this is gonna be a great week!!! $405 by end of week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:26:49 </td>
   <td style="text-align:left;"> $ada.x $QQQ $V $COTI.X $50,000 a day keeps the 9 to 5 away; For a limited time, we are opening our trading chat-room to the public..   https://www.discord.io/rBHacCP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:26:11 </td>
   <td style="text-align:left;"> $SPY $QQQ The market will be fine. Bonds yields rising just mean investors are getting more and more confident in the outlook of the US economy, stronger economy = higher stock prices in a long run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:25:33 </td>
   <td style="text-align:left;"> $SPY $QQQ bloodbath coming, 10 yr yield spiking into breakout territory, oil climbing, Naz futures down 1% already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:23:41 </td>
   <td style="text-align:left;"> latexe37a3348930c121b47beb9f967840232SPY - holding on to 462 by the same stand. 
$NVDA $AMD $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:22:42 </td>
   <td style="text-align:left;"> $QQQ $DIA $SPY you vote democrat you get poverty, dummies, you were worried that a president had more balls than you before and said what he felt like saying, now you’re stuck with the imbicil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:21:45 </td>
   <td style="text-align:left;"> $QQQ the only reason this is down is because the bulls are sleeping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:21:14 </td>
   <td style="text-align:left;"> $SPY So the $QQQ futures dip of -0.27% from the short holiday session will tacked on to the current dip and that will reflect in the QQQ stock price right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:21:02 </td>
   <td style="text-align:left;"> $SPY $QQQ Brandon isnt the Answer and neither is Big Orange.

DEMs not the Answer and neither are the REPUBs

Go fish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:20:34 </td>
   <td style="text-align:left;"> $BTC.X Everyone is almost sure that $QQQ is gonna drop hard tomorrow. Makes me feel sure that it won’t 🤨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:18:42 </td>
   <td style="text-align:left;"> $NQ_F $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:17:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOXX $AMD Mark this post, if rates open: 

2 yr over $1
10 yr 1.84
30yr 2.15

+ oil $84+

this market will scream lower and not let up until a looooooong time , tech and biotech, wreck, wrecked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:15:09 </td>
   <td style="text-align:left;"> $QQQ bloodbath tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:14:44 </td>
   <td style="text-align:left;"> $QQQ where do you see this end of week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:14:31 </td>
   <td style="text-align:left;"> $BTC.X $SPY $Qqq
PET SEMETARY
GROUND IS SOUR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:14:06 </td>
   <td style="text-align:left;"> $QQQ  No grease for the ass rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:14:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Greta must be on Suicide watch.

Good’ol China lollll

China Coal Production Hits Record To Avoid Energy Crisis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:13:43 </td>
   <td style="text-align:left;"> $QQQ tech tanking tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:13:30 </td>
   <td style="text-align:left;"> $QQQ green opens 3am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:13:05 </td>
   <td style="text-align:left;"> $QQQ NASDAQ futures right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:11:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Brandon when market drops 10% in a week

- “come on man” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:10:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARK  
 
Five Predictions for this Monthly OPEX week: 
 
1) Out of the blue, the Fed will raise .50 bps, with J-Pow raving &amp;quot;time to rip da bandaid off, motha fockas -- or else Hellaflation!!!&amp;quot; 
 
2) Chairman Xi will join Trump at a rally in Florida, exchanging high fives like old buddies.    
 
3) Cathie Wood will be burned as a witch in Salem, MA.  Her employees will be gathered, two by two, on a boat and banished, thereby ironically fulfilling their Ark mission. 
 
4) Algorithms, which already account for 70% of regular trading, will collectively resolve to &amp;quot;PAMP IT HIGHER,&amp;quot; creating the markets&amp;#39; first 90% systematic flow day.  It will be remembered by humans as Algogeddon. 
 
5) Baron Von Rothschild, when asked how stocks would perform in the upcoming year, immortally replied:  &amp;quot;they will fluctuate.&amp;quot; 
 
Prepare thyself.   
Hedge with work and whiskey. 
17 days does not a year make. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:10:08 </td>
   <td style="text-align:left;"> $QQQ uh oh.. NASDAQ almost down 1% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:09:45 </td>
   <td style="text-align:left;"> $QQQ fakeout before earnings season lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:09:39 </td>
   <td style="text-align:left;"> $QQQ $SPY $NASDAQ

Puts will pay again this week $AMC $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:09:29 </td>
   <td style="text-align:left;"> $QQQ Tech crashing $SOFI $SQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:09:25 </td>
   <td style="text-align:left;"> $QQQ $SPY futures looking a lot better. Market of over reactions. So seems fitting lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:08:51 </td>
   <td style="text-align:left;"> $SPY Interest rates brutalize businesses and consumers, that is what happens according to renowned,  Investopedia. 

Inflation just adds more pain and to an nth degree as it compounds monthly more and more, further driving the consumer and data center corporation to a point they literally cannot afford to spend.

At this rising inflationary standard now at, with Peak Inflation LOOKING NOWHERE CLOSE WITH &amp;quot;REVENGE SPENDING&amp;quot; from Covid cooped up nightmares by consumers and businesses having so much cash and further fueling the fire of inflation in a highly wealthy economy now of over 33 TRILLION CONSUMER AND BUSINESS wealth, the end cannot be anytime soon.

Expect inflation, if FED not jump in 26th now to tame it WITH DRASTIC stopping QE &amp;amp; bond buying 80B to ZERO, or, 15B max, plus 1st rate rise FEBRUARY of .75-1%, this economy will begin to burn 
itself up soon with no way out from 7% to 9% to 12%, like, 1970s, except with wealth now, 24% peak inflation early 2023.

$QQQ $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:08:20 </td>
   <td style="text-align:left;"> $QQQ Bulls, tomorrow will be last low of $QQQ,  if my prediction is wrong you all can block me. I am so confident. It wouldn’t drop below 374 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:07:33 </td>
   <td style="text-align:left;"> $QQQ i will be buying tomorrow for a swing. Can’t time the bottom…but I think it’s getting close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:07:24 </td>
   <td style="text-align:left;"> $QQQ don’t you bulls understand yet? TRILLIONS of new fake money was pumped into the market past few years. It’s being unwound now. The fed is slowing down QE and unwinding their positions. Economy is great but stock market is ridiculous.  Elon Musk knew this which is why he cashed out. Really? Tesla worth more than almost all other car companies combined but sell only a few % of what they sell? Lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:07:09 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-16 Options Analysis Video: 
https://www.youtube.com/watch?v=I1xGEPiYRW4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:05:44 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY Trump’s  rally over the wknd tanking the markets!🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:04:27 </td>
   <td style="text-align:left;"> This week $uvxy $spy $dia $qqq $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:03:17 </td>
   <td style="text-align:left;"> $spy $qqq $iwm $dia $sqqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:02:41 </td>
   <td style="text-align:left;"> $QQQ futures massively dropped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:02:39 </td>
   <td style="text-align:left;"> $QQQ do or die here. Think were gonna bounce hard through the night and tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:02:02 </td>
   <td style="text-align:left;"> $QQQ     flexing my gains because these guys are straight fire.,.; discord.io/Mr6AYuXT 
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:01:35 </td>
   <td style="text-align:left;"> $BTC.X only btc can bring $qqq green now 58k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:00:33 </td>
   <td style="text-align:left;"> Market Volume Barometer 1-14-2022 
Sentiment: EAGER 
Volume: 2% 
Real Feel: CHILLY 
Cycle: BEARISH II 
Portfolio: LONG 
Next Day Move: SIDEWAYS 
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/ 
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 13:00:06 </td>
   <td style="text-align:left;"> A Beginner&amp;#39;s Guide On Learning How To Trade

$QQQ $DWAC $NVDA $RIVN $PLUG

https://www.chartlearning.com/2016/01/learn-how-to-trade.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:59:25 </td>
   <td style="text-align:left;"> $QQQ $SPY sad thing is future didn’t even drop 1-2% 😂:: keep dropping, I love discounts  for calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:59:16 </td>
   <td style="text-align:left;"> $SPY yield falling back and should go red by opening tomorrow.

$QQQ seems to be a dip buying tomorrow first half if it opens low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:58:46 </td>
   <td style="text-align:left;"> $QQQ More fuckery tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:58:40 </td>
   <td style="text-align:left;"> $QQQ ugh this could be down 3% tomorrow again to start the week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:57:27 </td>
   <td style="text-align:left;"> $QQQ Whenever I see so many bears here, I feel better about my long positions. Turnaround Tuesday possible tomorrow. If this gap down holds, don’t open new shorts at open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:56:22 </td>
   <td style="text-align:left;"> $QQQ worst fking thing you&amp;#39;ll ever own will be this in 2022! party is over for tech...just wait til that 10 yr crosses 2%... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:56:04 </td>
   <td style="text-align:left;"> $QQQ 66.66% Correct on tap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:55:54 </td>
   <td style="text-align:left;"> $QQQ down 1% in the futures? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:55:46 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:55:07 </td>
   <td style="text-align:left;"> $QQQ 35% correction only take this to July 2020....long ways to go down with lower multiples on higher interest rates $SPY $KWEB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:54:52 </td>
   <td style="text-align:left;"> $QQQ that was nasty... i hope nobody got hurt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:54:39 </td>
   <td style="text-align:left;"> $QQQ worldwide yields are making me a little uneasy 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:54:03 </td>
   <td style="text-align:left;"> $SPY $ARKK $QQQ Cnbc ponzi bubbles
$AMC $GME reddit ponzis
They all must implode before market is disease free. Reddit ponzis must go back to beginning and spy to under 400. And Qqq is a total joke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:53:51 </td>
   <td style="text-align:left;"> $SPY $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:53:39 </td>
   <td style="text-align:left;"> $QQQ if everyone buys even just 0.10 fractional share of $QQQ itll offset selling pressure and the market will have no choice but to 🚀 🚀 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:53:31 </td>
   <td style="text-align:left;"> $QQQ Ready b*&amp;amp;ches </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:53:09 </td>
   <td style="text-align:left;"> $QQQ big wish for bears , god loves you guys , please go Heaven tomorrow all bears 😂😂😂😂 before market open!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:53:06 </td>
   <td style="text-align:left;"> $QQQ 22% correction only takes to January...blip on chart...could be 35% correction on Nasdaq $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:51:53 </td>
   <td style="text-align:left;"> $QQQ Building permits will be up with jobless claims lower. More inflation pressure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:51:44 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMD   classic MLK Tuesday red day. The fact that Asia is bussing. Imo BTD, will probably recover by next week or sooner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:51:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $NVDA 10 year and futes are bouncing off each other right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:50:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $AAPL QUESTION-

Okay so the Vaccine (Flu Shot) Developers get indemnified against Lawsuits… (that sucks)

But lets say a big assssh bully Company … like say Apple forces employees to get Vaccinated to keep their jobs…..

Do they (Apple) now ASSUME ALL VACCINE LIABILITY if say employees drop dead or can’t have Children, grow goiters, gills, or multiple extra nipples?????

Asking for a friend.
Thanks for the responses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:50:49 </td>
   <td style="text-align:left;"> OH. My. Goodness. $PSQ did $48M in volume Friday when days in the recent past it would only log very, very strong avg of single digit volume days? Holy hell the Jan volume numbers… If you don’t know, what $PSQ is, it’s a short $QQQ… just look at that volume. 

$SPY $djia 

Only bullish on a market crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:50:49 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:50:04 </td>
   <td style="text-align:left;"> $SPY Mega tech and spy have always been the last leg down in markets...10-15% correction on SPY....22% correction on QQQ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:49:58 </td>
   <td style="text-align:left;"> $QQQ green open don’t surprise!! Happened 75% of the time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:49:49 </td>
   <td style="text-align:left;"> $QQQ will open @374 and move up from there, not seeing any drop below 374 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:49:45 </td>
   <td style="text-align:left;"> $QQQ Crystal ball says Feds will crush 10 year to &amp;lt;1.6 and Vix to &amp;lt;19…let’s see by end of week?? Who knows but they always playing games </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:49:26 </td>
   <td style="text-align:left;"> latexe2c4f55fcd5b911cec004568391f15c7SQQQ 
$SPXU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:47:19 </td>
   <td style="text-align:left;"> $QQQ $SPY rofl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:46:55 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:46:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $MSFT $AAPL $NVDA buying now is just gambling. You’ll know when it’s the real bottom of this cycle once people are crying that they lost all their money and begging to keep their house. The 2020 drop will be a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:45:52 </td>
   <td style="text-align:left;"> $QQQ if i can get 2% for my money i’ll take it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:45:51 </td>
   <td style="text-align:left;"> $SPY $QQQ call buyers tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:45:43 </td>
   <td style="text-align:left;"> $SPY $QQQ  y&amp;#39;all see the dang past trend? see how the 20sma she came and met her man the 50sma? once they meet and make love it drops further. so, I see she is trying come see her man again. careful bulls LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:45:20 </td>
   <td style="text-align:left;"> Tomorrow is setting up to be a bloodbath. Once the market opens be patient to decide a direction! $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:44:48 </td>
   <td style="text-align:left;"> $QQQ tech wont disappear

the high pees may though

reality </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:44:34 </td>
   <td style="text-align:left;"> $QQQ $350 this week!!! Incoming!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:44:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 

Sinking like a stone tonight. Pajama traders are pissed off right now. Let’s see how the market reacts tomorrow. Earnings week, don’t overreact to a little red to start the week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:44:03 </td>
   <td style="text-align:left;"> $V $QQQ $T $IPOF I’ve made $93,111.27 by their alerts. Big thanks to this chat room!! Make as much as you want. 🚀 https://www.discord.io/xEvE2Aatrp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:43:49 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $SPY futures looking 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:43:34 </td>
   <td style="text-align:left;"> $SPY $QQQ FRAUDci needs to gave Passport yanked and be under arrest for crimes against Humanity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:43:10 </td>
   <td style="text-align:left;"> $QQQ  this will flip and flop around and could  breach the over throw low of 380 but will never see 350  not happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:43:08 </td>
   <td style="text-align:left;"> $QQQ , $IWM , $SPY
As if it wasn’t expected?!?!
Wtf, fed stated clearly they are going to hike 4 times, bonds yield has to adjust, 
The market act “surprised” ?!?!
Bullcrap, green in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:43:03 </td>
   <td style="text-align:left;"> $SPY $QQQ brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:42:38 </td>
   <td style="text-align:left;"> $SPY 10-15% correction minimum from top.....480 goes to 408-432 at very least for bottom. $qqq $jd $Kweb $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:42:14 </td>
   <td style="text-align:left;"> $QQQ this will flip and flop around and could  breach the over throw low of 380 but will never see 350  not happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:42:09 </td>
   <td style="text-align:left;"> $QQQ markets have been so volatile the last few weeks. Would anyone even be surprised if this goes green by 8am? I honestly wouldnt be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:42:09 </td>
   <td style="text-align:left;"> $QQQ this is going to drop at least 75-80% from its high when it bottoms easily. Overinflated fed-fueled bubble. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:40:46 </td>
   <td style="text-align:left;"> $SPY not to my 2 yet but it. will. get. there. too. So will 369 .$QQQ and rock that $soxx to 516 locks 
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:38:25 </td>
   <td style="text-align:left;"> $QQQ I don’t even begin to get excited until futures are at least -1.5% in the red and it holds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:38:25 </td>
   <td style="text-align:left;"> $QQQ remember when qqq would go up a dollar everyday lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:38:07 </td>
   <td style="text-align:left;"> $ARKK what do you know… Michael Burry was right again. Lol 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:37:12 </td>
   <td style="text-align:left;"> $TSLA  $SPY  $QQQ 

All these Bear post , talk to me at 8:30 Am tomorrow when market opens !

Good night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:35:42 </td>
   <td style="text-align:left;"> $QQQ will futures break Fridays low? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:34:54 </td>
   <td style="text-align:left;"> $NVDA $AMD $QQQ $BABA ;;;;;,,, 
 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $97,369 
Goal: $100,000 by end of January, 2022 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓 discord.io/MqakycG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:34:13 </td>
   <td style="text-align:left;"> $QQQ $SPY The only dip you bulls will he buying is the one for your chips! That&amp;#39;s if you still have money left over 🤡🤣🔻🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:34:13 </td>
   <td style="text-align:left;"> Most excellent, welcome to Crash Tuesday and the Armageddon Depression, indices-futures are plunging downward severely as socioeconomic news spirals upwards. Carry on sticking forks in the stock markets at large for profits my friends, followers, haters and those on block for jawboning self serving nonsense. Thank dog that I am here to help. 🐻❤😈✔ https://www.investing.com/indices/indices-futures ... https://finviz.com/news.ashx ... @Profit_Maker https://stocktwits.com/Profit_Maker 🤑 $djia $SPX $NDX $spy $qqq and more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:32:42 </td>
   <td style="text-align:left;"> $QQQ say hello to 369 minimum tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:31:09 </td>
   <td style="text-align:left;"> $ARKK who’s ready to fail tomorrow? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:31:06 </td>
   <td style="text-align:left;"> $QQQ Could see under $370 tomorrow. Congrats if you bought puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:30:20 </td>
   <td style="text-align:left;"> $QQQ Retailers running to get puts in the morning... 
 
$SPY $MSFT $FB $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:30:11 </td>
   <td style="text-align:left;"> $QQQ The trend lines can only break so many times. Might be rough  tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:29:50 </td>
   <td style="text-align:left;"> $QQQ https://youtu.be/Zcwi1ZrKtgQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:29:41 </td>
   <td style="text-align:left;"> $QQQ oh boy, get ready tomorrow is going to sting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:29:24 </td>
   <td style="text-align:left;"> $QQQ $SPY 10y at precovid high. Market gonna get wrecked tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:28:57 </td>
   <td style="text-align:left;"> $QQQ Ohhhhh shit. That T bond Yield is going to cuck us all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:28:14 </td>
   <td style="text-align:left;"> $QQQ 375 will hold imo. Recovery day tomorrow 387 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:28:11 </td>
   <td style="text-align:left;"> $QQQ the ol’ Bonds back at it again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:26:52 </td>
   <td style="text-align:left;"> $QQQ are you guys still able to buy groceries in your area? Is this “build back better”? The screens aren’t saying a word about it though. Weird.. 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:26:48 </td>
   <td style="text-align:left;"> $QQQ $spy $dia $BTC.X biden harris killing all mid and small cap tech companies!!! Communist mf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:25:31 </td>
   <td style="text-align:left;"> $QQQ opens deep red rockets up $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:25:02 </td>
   <td style="text-align:left;"> $QQQ Lost latexd8c0d81250ec264047d1d1cc6bbfc586AMD 129

$AAPL 165 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:24:39 </td>
   <td style="text-align:left;"> $QQQ $SPY Mehnnn it feels sooo good to see the futures sink deep into the red zone; tech puts will print bigly tomorrow. But I always worry about thd greedy hedge fund folks orchestrating to make the indices green before the market opens. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:24:15 </td>
   <td style="text-align:left;"> $QQQ Going all in on the Tech bull run tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:23:37 </td>
   <td style="text-align:left;"> $QQQ welp 350 incoming next couple weeks. Buckle up and stay safe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:23:32 </td>
   <td style="text-align:left;"> $QQQ 

Damn 10yr Y is High Snoop Dog High?? Crazy 

https://www.marketwatch.com/investing/bond/tmubmusd10y?countrycode=bx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:22:57 </td>
   <td style="text-align:left;"> $QQQ weeeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:22:22 </td>
   <td style="text-align:left;"> $QQQ Dip shit all over....no free money to pump.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:22:11 </td>
   <td style="text-align:left;"> $QQQ 😍😍😍😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:21:36 </td>
   <td style="text-align:left;"> $QQQ another 3% drop tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:21:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:21:23 </td>
   <td style="text-align:left;"> $QQQ Rams! 
Q’s not looking as good right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:20:49 </td>
   <td style="text-align:left;"> $qqq red to green fk the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:20:03 </td>
   <td style="text-align:left;"> $V $IPOF $T $PNC $QQQ ;;;; 
 
 
 
Account Challenge Update:~ 
Starting Balance January 3rd: $300  
Current balance January 15th: $1415.02  
Goal: $12,500 by end of year 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/MqakycG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:19:33 </td>
   <td style="text-align:left;"> $QQQ $SPY yawn... it&amp;#39;s not Tuesday already? Tired of waiting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:19:10 </td>
   <td style="text-align:left;"> $AMD $ND_F $QQQ RAF! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:18:37 </td>
   <td style="text-align:left;"> $SPY Probably panic from Putin and rates now EQUALLY SCARY, we should espy open a percent down from each, let&amp;#39;s add that up. 

$QQQ $AMD $XBI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:18:22 </td>
   <td style="text-align:left;"> $QQQ SOS Limited (SOS) is trending in the last 24 hours on Reddit ,Twitter, and Youtube** 
 
Add to your watchlist (Top 10 Stocktwits) 
 
&amp;quot;Retail preparing a buying event tomorrow, with price targets set at $3+ on this CryptoMiner.&amp;quot; -SS 
 
This piggybacks the rally BBIG has seen in recent trading days. 
 
Look for a gap fill to $2 with volume. 
 
 
 
https://www.reddit.com/r/SOSLimited/comments/s678qb/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:17:46 </td>
   <td style="text-align:left;"> $QQQ well fuck me the 10 year is up a bit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:17:12 </td>
   <td style="text-align:left;"> $QQQ hourly macd plays out bearish kiss this thing good bye </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:17:09 </td>
   <td style="text-align:left;"> $QQQ gonna be hilarious when futures are back to flat at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:17:04 </td>
   <td style="text-align:left;"> $PTON $QQQ $SBEV $49,000 a day keeps the 9 to 5 away; For a limited time, we are opening our trading chat-room to the public...   https://www.discord.io/rBHacCP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:16:41 </td>
   <td style="text-align:left;"> $QQQ huge down day tmrw. Bonds may crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:16:38 </td>
   <td style="text-align:left;"> $QQQ 200 Day here we come. This should bounce hard into earnings next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:15:52 </td>
   <td style="text-align:left;"> $QQQ   Legit no buyers. Just sellers. Limit down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:15:51 </td>
   <td style="text-align:left;"> $QQQ should have raised rates 6 months ago inflation out of control now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:15:29 </td>
   <td style="text-align:left;"> the RealEstate ETF Huge Unusual Option activity on Friday.. 3 times the volume  54,000 PUTS to 3,000 CALLS. 
 
  interest rates spiking hard. mortgage lenders watching.  
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:14:57 </td>
   <td style="text-align:left;"> $QQQ why do i always have to miss the dip?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:13:12 </td>
   <td style="text-align:left;"> $QQQ Legit no buyers. Just sellers. Limit down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:11:28 </td>
   <td style="text-align:left;"> $SPY Lets kill it this week. Make money when it goes down or up like a true professional. 🍻 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:10:15 </td>
   <td style="text-align:left;"> $PLTN Getting out of nasdaq 100 is good for this stock as $QQQ  has more to fall and will be sold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:10:00 </td>
   <td style="text-align:left;"> $QQQ is currently trading in the upper part of its 52 week range, which is inline with the index. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:09:58 </td>
   <td style="text-align:left;"> $QQQ so many twerp bears with their weeklies praying for doom and gloom🤡🤡🤡🤡 🤣🤣🤣🤣🤣
Waiting with powder for leap calls, bring it on 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:09:36 </td>
   <td style="text-align:left;"> $QQQ $SPY Limit down let&amp;#39;s do this. 
Tomorrow Nasdaq will be down 600 pts
Big Tech will bleed through the nose🔻🔻🔻🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:09:20 </td>
   <td style="text-align:left;"> $SPY $AMD Going to be a ton of R&amp;amp;D (probably already was 4Q and Su will break that news to you your 26th ER, ouch! Same day as FOMC FED meeting) involved with mobile chipping, going forward trying to make processors, just like new R6500, expect some EPS costs associated with it too. 

$QQQ $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:09:18 </td>
   <td style="text-align:left;"> $QQQ biden and harris @joebiden @kamalaharris SUCKS SUCKS .. make American communist again $spy $spx $btc.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:09:12 </td>
   <td style="text-align:left;"> $SPY $QQQ bond yields move higher// the higher move in rates is unnerving investors fearing it could be driven by inflation rather than economic recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:09:11 </td>
   <td style="text-align:left;"> $QQQ I’m hoping for blood in the water with a big V shaped recovery!! A man can dream can’t he? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:08:57 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
Oh, they&amp;#39;re cranking it like no tomorrow... 
 
https://www.investing.com/rates-bonds/usa-government-bonds 
 
$AAPl $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:07:41 </td>
   <td style="text-align:left;"> $SPY $QQQ i feel like during  2020-2021 big money pump it up and now the fed just holding it in so market won’t crash while big money slowly sellling and taking there gains. Screw u big money lol.. y’all will regret when it goes higher ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:07:23 </td>
   <td style="text-align:left;"> $QQQ loving this 😏
Give me -10% 
Ill load alot $AAPL $AMD $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:07:02 </td>
   <td style="text-align:left;"> $iwm $qqq guess the paid CNBC pundits won’t be using omicron as the excuse tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:06:25 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-16 Daily Forecast Video: 
https://www.youtube.com/watch?v=HZ_PS1g3aaw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:05:59 </td>
   <td style="text-align:left;"> $QQQ @biden no friend of technology </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:05:41 </td>
   <td style="text-align:left;"> $QQQ biden is sucks you all know now .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:05:15 </td>
   <td style="text-align:left;"> $QQQ glad this happened now. Slow climb up into 9:30 now $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:04:35 </td>
   <td style="text-align:left;"> $QQQ I was clinging on to some hope but devastated now, why is this happening to me, oh God, are you even real. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:03:42 </td>
   <td style="text-align:left;"> $SPY something something.... The bond yield story is overblown. $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:02:35 </td>
   <td style="text-align:left;"> latexb2b78f9acd19cdf5d34298cba7507780QQQ 
$XBI $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:02:14 </td>
   <td style="text-align:left;"> $QQQ omg it&amp;#39;s crashing again 😫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:01:54 </td>
   <td style="text-align:left;"> $QQQ What the fuck happened here? Is that drop based on some kind of news? I just went looking the cnn and fox websites to see if Russia declared war or something. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:01:28 </td>
   <td style="text-align:left;"> $QQQ this just beginning of a long over due correction. Finally can load up on good company’s and growth stocks dirt cheap! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:00:48 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

PERMA BULLS TOMORROW... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 12:00:40 </td>
   <td style="text-align:left;"> $QQQ bloody this week. Trade the sentiment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:59:14 </td>
   <td style="text-align:left;"> $SPY $QQQ nightmare open tuesday morning, gap down below Friday low. 
all tech damping.  stop DCA ing around tops. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:59:09 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;m never going to financially recover from this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:59:09 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:58:29 </td>
   <td style="text-align:left;"> $QQQ $MSFT $AMZN just when I was wondering if the jump in the 10 year was disconnected from NQ futures… no, it isn’t. Mechanical red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:58:10 </td>
   <td style="text-align:left;"> $QQQ $F $AMZN  
$49,000 a day keeps the 9 to 5 away; For a limited time, we are opening our trading chat-room to the public,,   https://www.discord.io/rBHacCP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:57:16 </td>
   <td style="text-align:left;"> $QQQ short everything!!! Sell all positions in 401k. Buy puts!!! This is tanking hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:56:39 </td>
   <td style="text-align:left;"> $QQQ Tsar Bondba! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:56:27 </td>
   <td style="text-align:left;"> $QQQ man… bears are winning this week big time!!! Long over due drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:56:05 </td>
   <td style="text-align:left;"> latexb6e2f79c586a5865b78a2739fbca3dcc$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:55:57 </td>
   <td style="text-align:left;"> $QQQ bears loosing their shot over premarket low volume drop 🤡🤡🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:55:55 </td>
   <td style="text-align:left;"> $QQQ WHAT happened to futes?!?! They look like someone just blew out linch and dinner from the front and back 😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:55:46 </td>
   <td style="text-align:left;"> $DWAC is the anti-tech 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:55:22 </td>
   <td style="text-align:left;"> $QQQ man I’m destined to be poor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:55:08 </td>
   <td style="text-align:left;"> $ND_F  not looking good… A gap down in the morning getting bought would a good sign, with a flow through day on Wednesday. Typically, we do not see reversals or big Green Day on monthly options expirations day. 

On the other hand, of the gap down gets sold, we are in for a world of pain this week… $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:55:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Such an “Organic” drop.... very believable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:54:46 </td>
   <td style="text-align:left;"> $QQQ lol futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:53:38 </td>
   <td style="text-align:left;"> $SPY $QQQ &amp;#39;s on the other land look ready to dive, set up for a Q1 h/s anyone ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:52:41 </td>
   <td style="text-align:left;"> $QQQ $SPY someone told me the Canadian stock market was open today. Never heard of it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:52:25 </td>
   <td style="text-align:left;"> $QQQ Tech may be gettin an ass whoopin tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:52:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM FUTURES DUMPING 
 
ON MLK DAY 2022, FIFTY PERCENT OF AFRICAN AMERICANS IN OUR NATION&amp;#39;S CAPITAL ARE BANNED FROM RESTAURANTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:50:58 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $BTC.X 

FUTES RIP-PING.... 🪦📉🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:50:04 </td>
   <td style="text-align:left;"> $QQQ what a beauty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:49:21 </td>
   <td style="text-align:left;"> $QQQ That was an odd nosedive in futures at 1030. Guess the bearish hedges were a good idea with move indicating there will be a follow through. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:49:11 </td>
   <td style="text-align:left;"> $QQQ $SPY $MSFT $AAPL

Head shoulders knees n toes
Knees n toes 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:48:15 </td>
   <td style="text-align:left;"> $SPY Real ugly $QQQ correction probably just beginning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:48:04 </td>
   <td style="text-align:left;"> $SPY $QQQ  dayum… 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:47:59 </td>
   <td style="text-align:left;"> $SPY sorry clowns I’m coming for you this week but I’ll join you the week after I promise

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:47:52 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:47:25 </td>
   <td style="text-align:left;"> $QQQ we are so fucked 😡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:47:18 </td>
   <td style="text-align:left;"> $QQQ People about to make so much money on puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:46:45 </td>
   <td style="text-align:left;"> $QQQ haven’t ever seen the 10 yr note drop downs fast. 1.9 yield a possibility before open and would cripple this index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:46:42 </td>
   <td style="text-align:left;"> $QQQ RIP to the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:46:41 </td>
   <td style="text-align:left;"> $SPY $QQQ Falling too slow for my liking. Should be in -1% territory by now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:46:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $TNX looks like the 10 year yield bull flag is playing out. Rip tech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:46:05 </td>
   <td style="text-align:left;"> Brother the Yields $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:45:41 </td>
   <td style="text-align:left;"> $QQQ $NQ_F executing on this classic bear flag. I know hella people went long on tech names + Nasdaq on Friday. Let’s see how price opens 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:45:39 </td>
   <td style="text-align:left;"> $QQQ bears gonna be pissed again they can’t sell their puts rn $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:44:04 </td>
   <td style="text-align:left;"> $QQQ bought futes here lookin for a swing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:43:47 </td>
   <td style="text-align:left;"> $QQQ $SPY they leak news of rate hike announcement? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:43:38 </td>
   <td style="text-align:left;"> $QQQ get fucked bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:43:29 </td>
   <td style="text-align:left;"> $MSFT $SPY  
 
See...sooner than I thought. 
 
$AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:42:41 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures look good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:42:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Uhm… is this real?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:42:32 </td>
   <td style="text-align:left;"> $QQQ they are gonna trap Friday’s dip buyers aren’t they </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:42:20 </td>
   <td style="text-align:left;"> $SPY $QQQ 10 year is on fire. Patiently waiting for the fed to remove nine trillion from their balance sheet so we can finally get to fair value around zero. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:42:10 </td>
   <td style="text-align:left;"> $SPY - The 10yr yield is absolutely flying. This continues and we will have a $SPY $QQQ and $BTC.X limit down overnight. Total crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:41:53 </td>
   <td style="text-align:left;"> $ND_F $QQQ flush it out of that bear flag straight to 15,100 by open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:41:49 </td>
   <td style="text-align:left;"> $QQQ should open at $373 before testing $350 sometime soon before heading back up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:39:51 </td>
   <td style="text-align:left;"> $SPY $QQQ werent these down 0.5% the other night and ended up flat by morning lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:39:05 </td>
   <td style="text-align:left;"> $QQQ hell of a month so far to bring in the year, the blood won&amp;#39;t stop flowin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:38:16 </td>
   <td style="text-align:left;"> $QQQ  $350 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:37:56 </td>
   <td style="text-align:left;"> $QQQ people gonna realize inflation can’t be controlled. Tech will be corrected heavily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:36:48 </td>
   <td style="text-align:left;"> $QQQ 😹😹😹😹 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:36:25 </td>
   <td style="text-align:left;"> $QQQ FUTES RIPPIN HAHAHAHA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:35:48 </td>
   <td style="text-align:left;"> $SPY $QQQ 2Y looks like a biotech stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:35:13 </td>
   <td style="text-align:left;"> $QQQ My 370 puts are looking juicy. Flush this shit 3% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:35:11 </td>
   <td style="text-align:left;"> $SPY $QQQ looks like it’s about to get real tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:33:23 </td>
   <td style="text-align:left;"> $QQQ 10 yr will run wild all night gonna be a complete meltdown tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-18 11:31:51 </td>
   <td style="text-align:left;"> $QQQ $spy We are not doing the 2021 CNBC rotation this week to another rotation next week to another rotation next week to another rotation it’s all value baby this year value stocks with the exception of Microsoft Google and Amazon and Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 14:37:09 </td>
   <td style="text-align:left;"> $AAPL In the recent reporting quarter: 100 institutions increased their position, while 143 decreased https://insider-analysis.com/search_whales.php?ticker=TABLE_AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 14:36:08 </td>
   <td style="text-align:left;"> $AAPL wow bears are here nice and early </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 14:22:06 </td>
   <td style="text-align:left;"> $AAPL advice to the Employees
Listen to ol’Johnny Paycheck

https://m.youtube.com/watch?v=gj2iGAifSNI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 14:21:02 </td>
   <td style="text-align:left;"> $SPY $AAPL  how do you want it ! 🤷‍♂️ https://youtu.be/uA13uMi9Hp0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 14:18:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $AAPL  This has been escalating, escalating, escalating, and, as soon as I first heard it, I said, we&amp;#39;re in trouble.

We don&amp;#39;t have a wartime president, and, IF UK is going to go help Ukraine then China will be helping Russia. They are about to become VERY GOOD oil and energy buddies. 

They will be axis powers vs Western world, you watch, Putin will call on China&amp;#39;s help when UK and other countries go to Ukraine.

And, 100% certainty, USA will become involved </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 14:08:05 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-16 Technical Analysis Video: 
https://www.youtube.com/watch?v=BAnnG_dJL4Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 14:06:56 </td>
   <td style="text-align:left;"> $CRM Futures looking bad for tomorrow $AAPL $MSFT $AI   😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 14:04:37 </td>
   <td style="text-align:left;"> $AAPL PT raised, ER a round the corner and this is going to plummet today.
Worst case today down to $170. 😞😞😞😞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 14:01:00 </td>
   <td style="text-align:left;"> $AAPL Simulated 175.0C for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:59:32 </td>
   <td style="text-align:left;"> $SPY USA said any statement yet ? 

$QQQ $AAPL $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:55:35 </td>
   <td style="text-align:left;"> $AAPL I dont get it. How is apple 172 and tesla over 1000? Tesla isnt 10 times better than apple. It makes no sense. ( yes i am just kidding, i am making fun of some of the stupid stupid things some people say) @NovaJed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:40:46 </td>
   <td style="text-align:left;"> $AAPL Based on Friday’s trade , Aaple will go up 5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:36:14 </td>
   <td style="text-align:left;"> $SPY $AAPL  📉🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:35:40 </td>
   <td style="text-align:left;"> ... Armageddon Depression update https://intodayspaper.cmail20.com/t/ViewEmail/d/9081FB4F14E42B112540EF23F30FEDED/D26BC6F6CAEB86714BD7C9066BE4161D?alternativeLink=False $tsla $f $ccl $aal $aapl 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:34:21 </td>
   <td style="text-align:left;"> $AAPL may open at 170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:33:47 </td>
   <td style="text-align:left;"> Let’s see if $AAPL finally falls today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:33:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:31:19 </td>
   <td style="text-align:left;"> $SPY This is highly heightened all the sudden.

Know God.
Know peace.
No God 
No peace. 

Could set off China-Russia-USA relations toast. 

Could, worst case scenario here, a lot of other ones before this, 2 or so, it could set off WW3 
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:28:18 </td>
   <td style="text-align:left;"> $AAPL this will go up since  many upgrades came last week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 13:08:51 </td>
   <td style="text-align:left;"> $SPY Interest rates brutalize businesses and consumers, that is what happens according to renowned,  Investopedia. 

Inflation just adds more pain and to an nth degree as it compounds monthly more and more, further driving the consumer and data center corporation to a point they literally cannot afford to spend.

At this rising inflationary standard now at, with Peak Inflation LOOKING NOWHERE CLOSE WITH &amp;quot;REVENGE SPENDING&amp;quot; from Covid cooped up nightmares by consumers and businesses having so much cash and further fueling the fire of inflation in a highly wealthy economy now of over 33 TRILLION CONSUMER AND BUSINESS wealth, the end cannot be anytime soon.

Expect inflation, if FED not jump in 26th now to tame it WITH DRASTIC stopping QE &amp;amp; bond buying 80B to ZERO, or, 15B max, plus 1st rate rise FEBRUARY of .75-1%, this economy will begin to burn 
itself up soon with no way out from 7% to 9% to 12%, like, 1970s, except with wealth now, 24% peak inflation early 2023.

$QQQ $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:53:00 </td>
   <td style="text-align:left;"> $AAPL has an average volume of 96865000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:50:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $AAPL QUESTION-

Okay so the Vaccine (Flu Shot) Developers get indemnified against Lawsuits… (that sucks)

But lets say a big assssh bully Company … like say Apple forces employees to get Vaccinated to keep their jobs…..

Do they (Apple) now ASSUME ALL VACCINE LIABILITY if say employees drop dead or can’t have Children, grow goiters, gills, or multiple extra nipples?????

Asking for a friend.
Thanks for the responses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:46:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $MSFT $AAPL $NVDA buying now is just gambling. You’ll know when it’s the real bottom of this cycle once people are crying that they lost all their money and begging to keep their house. The 2020 drop will be a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:42:38 </td>
   <td style="text-align:left;"> $SPY 10-15% correction minimum from top.....480 goes to 408-432 at very least for bottom. $qqq $jd $Kweb $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:42:07 </td>
   <td style="text-align:left;"> $AAPL DOWN $8+ tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:41:46 </td>
   <td style="text-align:left;"> $MSFT $AAPL Retail sheep ran from growth stocks to hide in overvalued megacaps.  The correction is only beginning, long way to fall for both </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:40:46 </td>
   <td style="text-align:left;"> $SPY not to my 2 yet but it. will. get. there. too. So will 369 .$QQQ and rock that $soxx to 516 locks 
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:35:54 </td>
   <td style="text-align:left;"> ... Most excellent, welcome to Crash Tuesday and the Armageddon Depression, indices-futures are plunging downward severely as socioeconomic news spirals upwards. Carry on sticking forks in the stock markets at large for profits my friends, followers, haters and those on block for jawboning self serving nonsense. Thank dog that I am here to help. 🐻❤😈✔ https://www.investing.com/indices/indices-futures ... https://finviz.com/news.ashx ... @Profit_Maker https://stocktwits.com/Profit_Maker 🤑 $tsla $f $ccl $aal $aapl and more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:35:06 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-16 Largest Trades Data: 
https://www.youtube.com/watch?v=MglgCb8wofM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:34:11 </td>
   <td style="text-align:left;"> $AAPL They all want to touch 150 or 200 day moving averages. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:33:23 </td>
   <td style="text-align:left;"> $AAPL what’s causing the drop in futes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:32:47 </td>
   <td style="text-align:left;"> $SPY $AAPL tech wreck secured 📉☠️🔥✌️🍆🍆🍆 🍆🍆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:26:54 </td>
   <td style="text-align:left;"> latex5b85c9edee6b51dfc8c3d744ee22a1f9AMD 129

$AAPL 165 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:23:44 </td>
   <td style="text-align:left;"> $AMD  $nvda   $intc   $aapl   $TSLA  
 
 
 4nm Exynos with AMD  RDNA2 graphics just announced! AMD will gap up with the news! 
 
https://www.samsung.com/semiconductor/minisite/exynos/newsroom/pressrelease/samsung-announces-game-changing-exynos-2200/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:22:10 </td>
   <td style="text-align:left;"> $AAPL y’all didn’t see the full moon tonight? Limit down $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:17:23 </td>
   <td style="text-align:left;"> $U potential bidders $FB $MSFT or $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:14:46 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $MSFT uh-oh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:10:45 </td>
   <td style="text-align:left;"> $AAPL $160 this wee, bloody week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:08:57 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
Oh, they&amp;#39;re cranking it like no tomorrow... 
 
https://www.investing.com/rates-bonds/usa-government-bonds 
 
$AAPl $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:07:23 </td>
   <td style="text-align:left;"> $QQQ loving this 😏
Give me -10% 
Ill load alot $AAPL $AMD $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:06:27 </td>
   <td style="text-align:left;"> $AAPL Bullshit storm incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:00:48 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

PERMA BULLS TOMORROW... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 12:00:26 </td>
   <td style="text-align:left;"> $AAPL 

High Tech futures getting blasted down!

Ugh! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:57:12 </td>
   <td style="text-align:left;"> Nasdaq Tech seems will have hard time tomorrow $spy $aapl $msft even $sofi because of nasdaq !!  
 
I think dividend big companies will be strong compare to them !! Like $K  
 
Always have plan and trade accordingly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:56:05 </td>
   <td style="text-align:left;"> $V Look in your pocket or purse. What do you have.. Visa and an iPhone or Android is my guess 📱 💳 $AAPL $GOOGL $V </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:52:46 </td>
   <td style="text-align:left;"> $AMC $AAPL $AMD $49,000 a day keeps the 9 to 5 away; For a limited time, we are opening our trading chat-room to the public   https://www.discord.io/rBHacCP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:49:11 </td>
   <td style="text-align:left;"> $QQQ latexa7c5f3ea63286c4347e56e9faf98d959AAPL  over 173.89📈 under 171.00📉

$TSM over 141.53📈 under 140.00📉

Good luck! Live-streaming in my server. 

 🔥🔥LINK IN BIO🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:43:29 </td>
   <td style="text-align:left;"> $MSFT $SPY  
 
See...sooner than I thought. 
 
$AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:31:12 </td>
   <td style="text-align:left;"> $SPY $AAPL tech wreck ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:30:18 </td>
   <td style="text-align:left;"> $MSFT $SPY We&amp;#39;re going &amp;quot;down, down, baby&amp;quot; after the morning pop. 
 
https://finance.yahoo.com/quote/MSFT/options?p=MSFT 
 
$AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:27:35 </td>
   <td style="text-align:left;"> $AAPL  **Just noticed SOS Limited (SOS) trending on Reddit and Twitter... Retail trying to force some squeezes? ! 
 
Technicals show a gap fill to $2.10 range is possible. In for 1000 shares tomorrow!  
 
Keep SOS on watch and add to strength. 
 
$3+ Coming! 
 
https://www.reddit.com/r/SOSLimited/comments/s678qb/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:19:08 </td>
   <td style="text-align:left;"> $AAPL latex4fcb1e21ca9f62d0c55e9b2b598ecf04AAPL 
$DJIA 
You tell me, if this is not art. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:05:05 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-16 Technical Analysis Video: 
https://www.youtube.com/watch?v=BAnnG_dJL4Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:01:30 </td>
   <td style="text-align:left;"> $AAPL they called every product “magic” until it fucking worked. Built the plane as it was flying and nearly crashed it haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:00:57 </td>
   <td style="text-align:left;"> $AAPL Simulated 175.0C for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 11:00:37 </td>
   <td style="text-align:left;"> $AAPL only company that ACTUALLY makes magic in real life wake the fuck up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:59:48 </td>
   <td style="text-align:left;"> $SPY Infkationary prices gon roCk your world tomorrow, bulls.
Those rates at parabolic pace, just like I said Friday. 
Oil? 👀🔥
Dollar dropping next.

This country going into recession, soon, from INFLATION. 

All the talking heads say don&amp;#39;t do it, the problem with not doing it is HISTORY is clear, high inflation that just goes higher and is not contained gets out of control QUICKLY AT 7% STAGE WE ARE AT NOW.
It is too late, the Summer Of Wait killed chances to take it slow now.
26th announcement comes, bond buying ends by March 1 and rate hikes begin, 0.75-1%👌

Sure, you have no growth for 2-3 years IF you cut the head off the hydra now but you have no growth for a DECade if u wait. See 1970s👍🚨
$QQQ $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:53:36 </td>
   <td style="text-align:left;"> Wondering who were the best Analysts of 2021? Wish u could follow their advice? 
 
Check out @TipRanks Top Analysts of 2021 LIVE Awards Ceremony, Jan 20th @ 11am EST!  
 
Watch the best give their Top Picks for 2022! 
 
$AAPL $TSLA $SPY $QQQ $SPY 
 
Free Sign Up 
👇 
https://bit.ly/3f6YNUA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:51:36 </td>
   <td style="text-align:left;"> $AAPL $MSFT $TSLA huge earnings next week for some great companies. Easy money in calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:50:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Equity of 150.07%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:48:31 </td>
   <td style="text-align:left;"> $AMD $TSLA $INTC 

I wonder, if these guys paid a premium like Apple &amp;quot;to ensure capacity&amp;quot; this quarter for their customers🤔

🚨

$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:47:48 </td>
   <td style="text-align:left;"> $AAPL tech getting annihilated! $spy 

Crash this pos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:43:00 </td>
   <td style="text-align:left;"> $AAPL last year, apple ran up 9.38% this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:41:04 </td>
   <td style="text-align:left;"> A Beginner&amp;#39;s Guide On Learning How To Trade 
 
$TSLA $MRNA $AAPL $FUBO $GME  
 
https://www.chartlearning.com/2016/01/learn-how-to-trade.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:36:43 </td>
   <td style="text-align:left;"> $AAPL  
 
#13 Trending on Twitter the last 24hrs - getting a lot of attention. You&amp;#39;ll want to keep an eye on this tonight and at market open tomorrow.  
 
We build this tool for you guys - check it out here https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220117 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:32:19 </td>
   <td style="text-align:left;"> $AAPL If the last couple of week’s trend continues, $175 until about 11 am and then back to $173 again just before close 🤷🏻‍♀️🦘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:27:40 </td>
   <td style="text-align:left;"> $AAPL

Oh wow!! I’m not a bear because I want to be. I’m a bear because every time frame on AAPL is calling for a huge 50%-ish haircut down to the potential double digit range at this point in time. Don’t hate me bulls, but the bull run definitely caused this and the volume drop off.. wowzers. I could go on &amp;amp; on but all I’ll say is that this is just unsustainable. If you’re a long I would definitely consider hedging.  

🤮🤮🤮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:24:26 </td>
   <td style="text-align:left;"> $AAPL why are we fricken red again man… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:23:46 </td>
   <td style="text-align:left;"> $SPY green now , red at open that’s how they get y’all . Bond yields and inflations.. remember that ! $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:23:43 </td>
   <td style="text-align:left;"> $FUBO this company is going to do a lot better than if $AAPL buys them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:20:21 </td>
   <td style="text-align:left;"> $AAPL Subida artificial.O preço não perdoa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:15:12 </td>
   <td style="text-align:left;"> $FUBO $TSLA Fails to realize profits ! ! ! $FUBO acquires $TSLA with the force of Seal Team Six &amp;amp; Tim Cook $AAPL  ! ! ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:10:28 </td>
   <td style="text-align:left;"> $AAPL 
190 eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:10:09 </td>
   <td style="text-align:left;"> $FUBO FUBO just bought $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:07:46 </td>
   <td style="text-align:left;"> $AAPL $180 this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:07:38 </td>
   <td style="text-align:left;"> $AAPL I wish this and $MSFT was the only sticks I ever.  https://www.apple.com/apple-watch-series-7/?afid=p238%7CsUddUdUXd-dm_mtid_20925qtb42335_pcrid_571113956391_pgrid_130165756274_&amp;amp;cid=wwa-us-kwgo-watch-slid---Brand-AppleWatchSeries7-newyear- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:06:39 </td>
   <td style="text-align:left;"> $AAPL this stock is sexy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:06:34 </td>
   <td style="text-align:left;"> $FUBO Not to feed into it, but $AAPL has the cash to buy it even double the current market cap and gives them a true “Sports Streaming Platform”, an international presence (read “soccer/futbol”), and an interface for Live that’s as good as any without even making a dent in their cash reserves. Not saying it’s happening, but ask me a few months from now and it could be a serious option. Inflation means your cash on the sidelines loses value, companies will put theirs to work if they see a positive return from it in the long run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:06:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-16 Largest Trades Data: 
https://www.youtube.com/watch?v=MglgCb8wofM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:05:06 </td>
   <td style="text-align:left;"> $GSAT if ya see that $AAPL  commercial  during the nfl game emergency 🆘 call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:04:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMD Anyone else strike it odd, Core PCE Deflator data typically follows CPI a week after but this month it is TWO weeks after? 🤔

I got my guess, that boy&amp;#39;s gon print n-n-nasty the 28th, FED purposely wanted that bad boy BEHIND the 26th FOMC meeting to be equally nasty, nasty, nasty, boys  ! ( Extra credit: who knows who sings that song, &amp;quot;Nasty...boys.&amp;quot; Janet Jackson😉)

Over 7%, huge jump shopping season, mi ladies spent so much on cosmetics and purrrrfumes and personal care, they be giddy right now . Gentlemen, y&amp;#39;all getting those Thomas Bosley hair transplants and GNC multis and whey protein, you spending a lot of big bucks too, flashing those inflationary dollars in the form of $40 billion spent on credit + all that mattress cash so the ole IRS don&amp;#39;t get wise to ya! 

You, you, *squeezes cheeks, big spenduhs, oo, oo, oooh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 10:03:22 </td>
   <td style="text-align:left;"> A message from the wise to the morons who shorted! 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:56:22 </td>
   <td style="text-align:left;"> How them $AAPL futures looking ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:50:31 </td>
   <td style="text-align:left;"> $AAPL y’all remember when all those Covid vaccines worked so well that case numbers 10x-ed lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:41:24 </td>
   <td style="text-align:left;"> $SPY $AAPL A large amount of In The Money (ITM) calls expiring this week into OPEX (Options Expiration). Apple is wedging with a confluence on 9 and 20 on the daily above the price action. You can view the Options Expiration Calendar marketwatch.com/optionscenter/…. Not investment advice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:40:44 </td>
   <td style="text-align:left;"> $LCID   At Berlin stock exchange $LCID was opened 37.35 Eur ($42.650) and closed 36.825 Eur ($42.054). It seems like $AAPL  rumor on Friday was fade away. Let see what will happen in the US today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:40:27 </td>
   <td style="text-align:left;"> $AAPL bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:37:25 </td>
   <td style="text-align:left;"> $AMD $AAPL $AMZN $MSFT 8:30 ET and the 10-year is up 5bps lol Someone is dumping bonds hard trying to crash the markets. Too bad no one believes him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:36:24 </td>
   <td style="text-align:left;"> $SPY $ES_F Above $4743 to break the downtrend, there could possibly be more volatile moves before resistance is broken. We’re starting the week on a Tuesday &amp;amp; Wednesday is usually choppy it’ll be interesting to see where the price is at the end of the week, last trading week before FOMC and both $TSLA &amp;amp; $AAPL earnings… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:35:13 </td>
   <td style="text-align:left;"> $NFLX $MRNA $COST $AAPL ~:&amp;quot;:::--#02 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,959 
Goal: $100,000 by end of January. 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:33:14 </td>
   <td style="text-align:left;"> $MSFT It&amp;#39;s looking like a pop in the morning and puts into the rest of the week... 
 
$SPY $QQQ $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:26:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $AAPL 

&amp;quot;I&amp;#39;m your girlfriend (eating his Subway sandwich in his work office cubicle).&amp;quot;
 
I-I-I don&amp;#39;t think this is going to work out. 

US markets, especially tech, and, especially tech in China, everything about to come to a head. 

China&amp;#39;s Xi now telling USA not to raise rates.

LOL, they just lowered rates so that their people can buy more of THEIR GOODS THAN OURS.

You really think protectionism president, Xi, liked hearing Apple was the #1 phone sold in the country for December? 

Heeeeeel, no! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:25:05 </td>
   <td style="text-align:left;"> $SPY $ETH.X $AAPL $MSFT massive nft drop coming (with alot of utility) members gonna get in on the mint as well so join up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:23:16 </td>
   <td style="text-align:left;"> $AAPL if investors are looking for a solid gas and oil company, look no further than Enerplus $ERF. It is up 27% over the past month. The company has 10 years worth of reserves on its lands and Oil is heading to $100. That is a recipe for making money. While we were celebrating MLK Day ERF popped up another 2.07% on the Toronto Stock Exchange today. It is certain to catch up on the NYSE tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:21:32 </td>
   <td style="text-align:left;"> $SPY  $SPX  
 
$BRK.B  $AAPL   
 
**Gumby just said caution for weakening momentum /negative divergence in Berkshire Hathaway. ichimoku by definition is extremely far from cloud equilibirum and needs a red line (9 day candle average) retest then a white line (26 candle average ) retest..  
Caution for gumballs flying everywhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:20:37 </td>
   <td style="text-align:left;"> $AAPL*  Has anyone seen this for SOS Limited? Trending currently on all social media! Give it a watch... $3 coming soon! 
 
I&amp;#39;m buying 1000 shares tomorrow.  
 
https://www.reddit.com/r/SOSLimited/comments/s678qb/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:19:43 </td>
   <td style="text-align:left;"> 💣 Big Darkpool level💣 01/14/2022
$AAPL
#moneyflow
#Darkpool
#smartmoney
#support
#Resistance 
#Blackboxstocks
#SR 
#Stockmarket 
#Swingtrades
#Daytades
#Intraday 
Data:Blackboxstocks
https://buff.ly/3pawfxV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:11:05 </td>
   <td style="text-align:left;"> Huge gains for $CFVI incoming valuation is 2 billion and right now the market cap is only half a billion! https://twitter.com/armstock_/status/1483232847615848448?s=21 $DWAC $PHUN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:08:37 </td>
   <td style="text-align:left;"> January Earnings Calendar  
 
$AAPL $AMD $CAT $GE $INTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:07:37 </td>
   <td style="text-align:left;"> It seems like the volatility in the $NASDAQ is set to continue this week... $MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 09:01:22 </td>
   <td style="text-align:left;"> $AAPL Simulated 175.0C for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:59:34 </td>
   <td style="text-align:left;"> $AAPL - Upcoming quarterly report is on 27th of January 2022. Apple new variance upsurges… https://www.macroaxis.com/invest/technicalIndicator/AAPL/Variance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:55:52 </td>
   <td style="text-align:left;"> MetaVerse ✅
✅ $AAPL
✅ $MSFT 
✅ $NVDA 
✅ $FB 

https://youtu.be/tMbLEnf3-V4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:50:35 </td>
   <td style="text-align:left;"> $AAPL once the tech wreck starts - there’s no stopping it ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:46:18 </td>
   <td style="text-align:left;"> $SPY full noon in 2 min... happy Market crash fellas $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:44:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $AAPL MAYBE it is time we untie the knot 
Leave China trade to everyone else in the world.

Decouple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:42:25 </td>
   <td style="text-align:left;"> $AAPL Another iPhone &amp;quot;Killer&amp;quot; is going down... https://www.ped30.com/2022/01/17/apple-samsung-flagship-sinking/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:42:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:39:31 </td>
   <td style="text-align:left;"> $AAPL bought my first share of apple last week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:38:10 </td>
   <td style="text-align:left;"> $AAPL Bullish.. 🍏🍏🍏 
 
Read my TA 👇👇👇 
https://twitter.com/MadHodor/status/1483236825279913995 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:34:51 </td>
   <td style="text-align:left;"> $AAPL https://www.reddit.com/r/pennystocks/comments/s6bgpf/comprehensive_report_conservatively_showing_a_633/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:32:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-16 Technical Analysis Video: 
https://www.youtube.com/watch?v=BAnnG_dJL4Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:31:43 </td>
   <td style="text-align:left;"> $SPY $AAPL $BA Thanks a lot fintwit. You are really encouraging. Trying out this new content and almost 2k with 1k subscribers. Crazy! 

➡️ https://youtu.be/Spp5_M0aWCc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:16:49 </td>
   <td style="text-align:left;"> $AAPL Data suggest that the overall analyst sentiment for AAPL  is bullish. Simplify the way you research stocks with Invescent   
https://play.google.com/store/apps/details?id=org.invescent.invescent&amp;amp;hl=en_US&amp;amp;gl=US </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:16:01 </td>
   <td style="text-align:left;"> Happy Hunting $AAPL $AMD $LCID $GM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:12:23 </td>
   <td style="text-align:left;"> $TSLA $NIO $QQQ $SPY $AAPL Markets racist if Tuesday is a red day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:10:41 </td>
   <td style="text-align:left;"> $SPY $UBER and $DASH Drivers work solely on tips now, pretty sad $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:09:48 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s start the week green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:09:00 </td>
   <td style="text-align:left;"> $AAPL in here for the tech wreck ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:07:20 </td>
   <td style="text-align:left;"> $AAPL Red futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:07:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple, Amazon, and Ford Contend With Payment Models https://www.stck.pro/news/AAPL/21492746 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 08:01:26 </td>
   <td style="text-align:left;"> $FUBO TV would be an awesome fit for $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:56:35 </td>
   <td style="text-align:left;"> $AAPL tech bout to get crushed! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:55:04 </td>
   <td style="text-align:left;"> $AAPL  $SPY $QQQ  this aint no bear or bull market , this is a dang 🤡 clown market 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:48:14 </td>
   <td style="text-align:left;"> New signal generated on $AAPL by the Momentum factor with an expected return of 16.54% and an historical probability of profit of 77.27%. Via: https://www.stockgrid.io/factor-analysis/momentum/daily/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:45:35 </td>
   <td style="text-align:left;"> $AAPL 

That’s very encouraging news for people who live in NY .. it will bring back to normal with reopening of Apple Stores and more people will come out slowly.

Thank you Apple for mandating own vaccine policies to ensure safety of the consumers and employee likewise so people can shop with ease and confidence! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:41:39 </td>
   <td style="text-align:left;"> $AABB $AAPL started out in a 1 car garage FACT! $AMD started out on OTC FACT! $TSLA was a penny stock under 5$ FACT! $NFLX was also a penny stock under 5$ all facts. $AABB is DEBT FREE! with 5 Gold producing mines NO DEBT an a Global exchange. All FACTS https://microcapdaily.com/asia-broadband-otcmkts-aabb-crypto-operator-launches-its-aabb-crypto-exchange-continues-rollout-of-200-trading-pairs/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:40:41 </td>
   <td style="text-align:left;"> $AAPL 50ema as support if it comes https://youtu.be/e-8S_YikPx8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:37:03 </td>
   <td style="text-align:left;"> Omicron shows signs of easing in states hit early by contagious variant - CNBC $BTC.X $QQQ $SPY $AAPL $NVDA  https://apple.news/AO2rZSCCcRiefjmVl3rk3oQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:20:27 </td>
   <td style="text-align:left;"> $AABB  $SPY $AAPL $AMD $SHOP Pro Alert&amp;gt; MAJOR Basher campaign all weekend! Tomorrow have your DD done and ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:19:50 </td>
   <td style="text-align:left;"> $AAPL I am thinking we can make it 250 to 300 by end of year easily!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:04:19 </td>
   <td style="text-align:left;"> $aapl $msft $googl https://www.youtube.com/watch?v=9XIaFT4uTzE&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 07:02:25 </td>
   <td style="text-align:left;"> $AAPL nails is with marketing... 
purchased #mom a #AppleWatchSeries7 ⌚️ 
https://youtu.be/VHtffwyHauU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 06:54:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $AAPL

I&amp;#39;m thinking FED may take a peak at PCE Deflator data due the 28th pre their 26th FOMC meeting.

&amp;quot;That&amp;#39;s cheatin&amp;#39;! Dem can&amp;#39;t do dat!&amp;quot; 

Well, yes, they can, LOL, they are the FED.

BUT, yeah, and it a big &amp;quot;but,&amp;quot; I think, IF you hear &amp;#39;balance sheet to ZERO by March 1 and 1st rate rise March will be high,&amp;#39; maybe, they give #, maybe not.
My predict: BB DONE + .75-1% rate hike.

PCE is going to be a doozy of a #.

I&amp;#39;m guessing OVER, wow, am I really saying this, over 7%. 

Let&amp;#39;s be honest, too, that high a jump will drop markets A MINIMUM 10% immediately after data announced.
So already we got a 10% drop from the balance sheet done + aggressive, large 1st rate hike on 26th before a brutal inflation report the 28th.

Gee, sounds so fun a whole week really, the ANTICIPATION of 26 &amp;amp; 28 will be to die for.
And likely starting tomorrow the build to THAT NEWS starts ramping, who even cares about....

bank ERs; we pretty much hot gist already too👍JPM BAC--THEY WILL BE BAD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 06:53:32 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL Happy MLK Day, hopefully your enjoying the time off and relaxing. Who&amp;#39;s excited for the market to open tomorrow?!?!? 
 
Just wanted to share a tool we built to track trends on socials (Twitter, Stocktwits and Reddit).  Hedge Funds are already using this data - so we wanted to give you the power to track trending stocks across social media. Keep an eye on this tonight and tomorrow morning. 
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220117 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 06:47:57 </td>
   <td style="text-align:left;"> $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 06:40:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $DIS  This just doesn&amp;#39;t sound positive for sentiment tomorrow: 

&amp;quot;Goldman Sachs slashes US GDP 2022 3.8% to 3.4%.&amp;quot; 

&amp;quot;JP Morgan CEO says there could be 6 or 7 interest rate hikes 2022.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 06:35:34 </td>
   <td style="text-align:left;"> $AAPL Bear season lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 06:30:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-16 Largest Trades Data: 
https://www.youtube.com/watch?v=MglgCb8wofM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 06:23:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $BTC.X 
 
No wonder Biden is not making Millennials and GenZ pay back their student loans. 
 
They don&amp;#39;t want to work let alone pay back their debts...lol 
 
https://www.youtube.com/watch?app=desktop&amp;amp;v=Vzl16lOXtNw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 06:22:13 </td>
   <td style="text-align:left;"> $AAPL $DIS $PYPL Love these tickers this week!
Let’s STACK GAINS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 06:12:51 </td>
   <td style="text-align:left;"> latexd398b551721567a8db8646e26af6f3f0VERB launching a new  ecommerce website where all retailers will be live streaming as well as having a store to showcase goods.
Verb just signed a 56mm finance package to launch the site, which keeps stock off the market putting it in the hands of verbs 13g investor 3i&amp;#39;s. 
The site is done and previewed here &amp;amp; will begin a series of launch promotional events.

https://youtu.be/c5xKOK6VhZg

https://youtu.be/c4PUx6X36S4

Verb ceo is also a judge on David Meltzers streaming show 2min Drill. David Meltzer just signed a deal w/$AAPL tv &amp;amp; is the producer of upcoming Verbtv providing content for Verb to convert to shoppable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:59:13 </td>
   <td style="text-align:left;"> We put together a 3 part series on how we locate STOCK PRICE ACTION PATTERNS &amp;amp; how we utilize this information to develop $AAPL $DIS and $MSFT trade plans. Check it out by clicking the link before. Enjoy!📺

https://instagram.com/stories/optionsplayers/2753445255837794696?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:56:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:46:20 </td>
   <td style="text-align:left;"> $AAPL * Get into SOS Limited (SOS) for tomorrow! Who&amp;#39;s ready for tomorrow? 100-1000 Shares/ Order Bulls :) 
https://www.reddit.com/r/SOSLimited/comments/s678qb/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:43:28 </td>
   <td style="text-align:left;"> $AAPL I think we are going up this week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:34:06 </td>
   <td style="text-align:left;"> $AAPL Take a look at Paysafe https://www.paysafe.com/de-en/apple-pay/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:26:36 </td>
   <td style="text-align:left;"> $AAPL what y’all think </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:20:56 </td>
   <td style="text-align:left;"> $AAPL $TSM  secured an order from $AAPL for A16 chips
 🚀 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:20:06 </td>
   <td style="text-align:left;"> $AAPL trade idea! 
Entry Break $174.25 for Calls
Entry Break $171 for PUTS
Could be a small upside day here if we trade under the daily trend!
Will trade choppy if either side doesn&amp;#39;t break!
https://share.trendspider.com/chart/AAPL/11367j6vvh4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:17:03 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on higher time frames.  We only like to buy it in 3, 7 or 11 swing at the blue boxes.   We still favour lower to take place before the blue box equal leg is hit, which can play a part in dragging world indices lower in the sessions to come.    #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:04:12 </td>
   <td style="text-align:left;"> $AAPL the pullback from the peak can reach $162.10- $152.80 area lower where buyers should be waiting to appear again #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:03:57 </td>
   <td style="text-align:left;"> $AAPL 1hr view from 1/14 Pre-Market update presented to members at elliottwave-forecast.com/ #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 05:00:51 </td>
   <td style="text-align:left;"> $AAPL Simulated 175.0C for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:53:07 </td>
   <td style="text-align:left;"> $AAPL #Apple $AAPL video from 12 January looking at the #Elliottwave path https://www.youtube.com/watch?v=q1xLRP7d8LA  #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:47:13 </td>
   <td style="text-align:left;"> $AAPL Chart of The Day 12 January: #Apple can see further downside https://elliottwave-forecast.com/stock-market/elliott-wave-view-apple/  #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:32:56 </td>
   <td style="text-align:left;"> $AAPL $TSLA $NVDA $AMD $LCID 📈📈📈 Earnings season is coming!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:31:29 </td>
   <td style="text-align:left;"> ‪NEW Article: “Fitness A Major Consumer Priority In 2022” - https://www.seeitmarket.com/fitness-a-major-consumer-priority-in-2022/‬ 
 
‪by @_SeanDavid $PTON $PLNT $AAPL‬ $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:28:01 </td>
   <td style="text-align:left;"> $SPY $AMD $QQQ $AAPL Short day, what did futures start at? 
What current news since? Singapore becoming India growth hot. What else?

Taiwan sure kicking it since late 2019, r u kidding me, 9000 to 18000+ Taiwan Weighted index, China just got to be salivating at the mouth over that. Warring?

China economy starting to salivate, right, GDP smoked estimates, 1.6% print, est. 1%. And, Industrial Production, what a serious read that was, 4.3% when, whoa, wow, 3.6% predicted. 

Just horrible, huh, LOL? 

Hot as Hell (btw, know the Lord God, u don&amp;#39;t want to go there).

Well, tho. What about retail sales? 
Hamburger, electronics! 
RS missed hugely, 3.7% predicted and was NEGATIVE 1.7%.

Well, since China lockdowns basically started Q4 very ending w/ Xian province &amp;amp; 2 other cities last 6 days, it really can&amp;#39;t be a Covid excuse, can it, for horrible shocker retail sales.

So what?

How about USA INFLATION biggest trigger to China retail sales slowdown?that 6%-7% drag all Q4? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:24:30 </td>
   <td style="text-align:left;"> $SPY $BTC.X $QQQ $TSLA $AAPL  
 
JDADDY need to get market back to ATH once again. 
 
His Boomer generation still have bag to hand off to Millennial in &amp;quot;generational buying opportunity&amp;quot;! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:13:29 </td>
   <td style="text-align:left;"> Significant jump in impressions on $AAPL ticker on Stocktwits the past 24hrs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:07:13 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Nvidia Is Building Worlds https://www.stck.pro/news/AAPL/21484031 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:06:30 </td>
   <td style="text-align:left;"> $SPY $SNIPF 50M company, 200M in my sleep. 1B more realistic, 15B with the right connect $AAPL $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 04:01:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $BTC.X 
 
If JDADDY can inflate asset prices a few more percent then maybe even more Millennial can afford house of their dream! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:58:18 </td>
   <td style="text-align:left;"> $TSM has secured an order from $AAPL for A16 chips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:54:52 </td>
   <td style="text-align:left;"> $AABB $TSLA $AAPL $GOOG $MSFT Hope everybody&amp;#39;s enjoying their Holiday weekend. Tomorrow back to wealth building </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:54:18 </td>
   <td style="text-align:left;"> $AMD $AAPL $AMZN $MSFT  Watched this over the weekend. Mark Yusko, massive Bitcoin bull, grudgingly admit that inflation has peaked. Markets might be volatile in the first half of the year as folks panic about the Fed. But if there is a draw down, I think it&amp;#39;s a buying opportunity because when inflation numbers start tumbling down, the Fed will back off and the market will come roaring back

https://www.youtube.com/watch?v=dMpAq2IZp0o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:48:00 </td>
   <td style="text-align:left;"> $AAPL 183 this week, 200 ER day and after. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:43:44 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-16 Technical Analysis Video: 
https://www.youtube.com/watch?v=BAnnG_dJL4Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:26:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Narrowing Down High-Quality Dividend Growth: Snap-On Is A Sure Bet https://www.stck.pro/news/AAPL/21482967 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:21:15 </td>
   <td style="text-align:left;"> $AAPL Apple App Store Analysis: Netflix And Disney+ Heat Up, AT&amp;amp;T&amp;#39;s HBO Max Catches Fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:19:20 </td>
   <td style="text-align:left;"> $TSM has secured an order from $AAPL for A16 chips at higher prices!

$NVDA $MRVL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:19:00 </td>
   <td style="text-align:left;"> $AAPL&amp;#39;s ROE of 150.07% is amongst the best returns of the industry https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 03:13:31 </td>
   <td style="text-align:left;"> $AAPL latex130fc3d98ddc4857bc5d02b83b9a50f3$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:45:45 </td>
   <td style="text-align:left;"> $PBR $MARA $AAPL They have helped me to grow my account to almost 2.5 million. 100% recommend joining!,, 
 
It&amp;#39;s free joining 🚀 discord.io/7MktDXk3TA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:45:04 </td>
   <td style="text-align:left;"> New correlation matrix for Altria( $MO ), Apple( $AAPL… https://www.macroaxis.com/invest/marketCorrelation?s=MO,AAPL,THC,APD,ICE,EFX,SUN #correlations #stocks #stockratings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:40:12 </td>
   <td style="text-align:left;"> $AAPL We saw this on Squeeze plays not long ago. SOS Limited (SOS)  1000 shares/ order is the talk.  $3+ Gamma runner!!! https://www.reddit.com/r/SqueezePlays/comments/s65yiq/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:37:30 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL $QQQ Don&amp;#39;t be fooled by China bad retail sales from Covid crap, they only started lockdowns in Xian province 3 weeks ago and then couple other cities in lockdown, rest of China OPEN.

So Q4 retail sales miss from something other than that?

What was it?

USA INFLATION! Mostly.

I&amp;#39;d be remiss and biased to mention a other factor too, the dollar was HIGHER Oct. &amp;amp; Nov. so it doubly served to hammer China&amp;#39;s shopping for global shipped goods too Q4👍

But, I&amp;#39;m telling you, I&amp;#39;m telling you, I&amp;#39;m telling you: 

INFLATION WILL RULE THE DAY (FOR YEARS NOW) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:37:13 </td>
   <td style="text-align:left;"> $AAPL Apple is a safe bet for me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:36:32 </td>
   <td style="text-align:left;"> $NIO $FCEL $AAPL For a limited time, we are opening our trading chatroom to the public.. best.stocktradingchat.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:35:34 </td>
   <td style="text-align:left;"> $AAPL $BA $AMD We hope enjoy this video on PRICE ACTIONS PATTERNS!
Make sure you SUBSCRIBE, LIKE, and COMMENT so you can enjoy all of our valuable content. 

https://youtu.be/7NZ0OTdFvsE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:34:46 </td>
   <td style="text-align:left;"> $SPY ....Tech looks... 👨‍💻 Yakety smackity blah blah blah Resistance correlation yakety smackity Support Breakout Fibonacci yakety smackity.....🍀 Yall know what ta do 👍 $STUDY $QQQ $UVXY $AAPL 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:31:39 </td>
   <td style="text-align:left;"> $BBIG $TSLA $AAPL Find active market alerts here. For a limited time,, we are opening our trading chatroom to the public✅ options.stocktradingchat.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:31:32 </td>
   <td style="text-align:left;"> $QQQ $AMZN latexe89f82ed1e7d0358c170510eb14025daAAPL 
$DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:23:18 </td>
   <td style="text-align:left;"> $AAPL $T $NFLX $DIS  
 
https://www.benzinga.com/news/22/01/25074951/apple-app-store-analysis-netflix-and-disney-heat-up-at-ts-hbo-max-catches-fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:18:18 </td>
   <td style="text-align:left;"> $AAPL Apple Option Alert: Jan 21 latexb829c549c1589f99407c8c3a2a3e0be7AAPL 
$DJIA 
 
If it happens , the rebound will not last long . . try to take advantage of it. .
That train won&amp;#39;t come by too many times this year. .
 . ..... ** // </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:12:08 </td>
   <td style="text-align:left;"> $ADA.X $BBIG $TSLA $AAPL $BTC.X For a limited time, we are opening our trading chatroom to the public_ Get access to chatrooms stock alerts option alerts portfolios and more stockchat.livetradeview.net/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:07:01 </td>
   <td style="text-align:left;"> $SPY $JD $QQQ $AAPL  
 
$BABA They will close it ALL down!! Unvaccinated and ineffective vaccine—as world recovers China will fall behind for next 5-10 years at this rate!! HK sold; selling the 25% straight line prop—-GAP fill to mid 70’s BEFORE delisting!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:06:16 </td>
   <td style="text-align:left;"> $AAPL Apple Option Alert: Jan 2024 $175 Puts at the Bid: 158 vs 1349 OI; Earnings 1/27 After Close🐻 |🥇 Check out ➡️ SweepCast.com  #stockmarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 02:05:37 </td>
   <td style="text-align:left;"> $TSLA 10, 000 more watchers and we surpass $AAPL ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:57:53 </td>
   <td style="text-align:left;"> $SPY $QQQ   
 
Based on Friday&amp;#39;s close (stats below), which way are we going the week? 
 
https://twitter.com/MeisaBonelli/status/1483134882595459072?s=20 
 
$TSLA $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:55:04 </td>
   <td style="text-align:left;"> $TV $AMD $AAPL $49,000 a day keeps the 9 to 5 away; For a limited time, we are opening our trading chat-room to the public.,,..  discord.io/stock-opt-trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:51:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Mark these words all over:

THE MOVE at end of day and afterhours for Nasdaq was a bull trap, that 80 point afterhours run-up Friday is where now in futures? 

And, let&amp;#39;s see where $NDX opens Monday to confirm, IT&amp;#39;S A _____ !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:46:02 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $COIN I&amp;#39;m just gonna leave this here for you metaverse fans and parents that have kids. $RBLX &amp;lt;- https://youtu.be/8Mr4a84prMc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:45:09 </td>
   <td style="text-align:left;"> $AAPL Thank god for this break. The tug of war continues until the run up. Have fun bull/bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:45:03 </td>
   <td style="text-align:left;"> $AMD $XLNX $MSFT $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:39:20 </td>
   <td style="text-align:left;"> Today &amp;#39;s  #DOW30 HeatMap of  #large  market stocks: $AAPL 
$MSFT $UNH $JNJ $JPM 
 
finscreener.org/map/map </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:38:56 </td>
   <td style="text-align:left;"> Incoming, https://www.youtube.com/watch?v=N_jGOKYHxaQ unfortunately re due diligence, Armageddon Depression, great movie, saw it in the theatres in the 1970&amp;#39;s, be prepared my friends, followers, haters and those on block for jawboning nonsense. Thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker 🐻❤😈✔ $tsla $f $aapl $ccl $h and more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:38:39 </td>
   <td style="text-align:left;"> #SP500 Today &amp;#39;s HeatMap of  #mega  market stocks:  $GOOG 
$GOOGL $AMZN $TSLA $AAPL 
  
finscreener.org/map/map </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:36:40 </td>
   <td style="text-align:left;"> $AAPL $200 soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:34:13 </td>
   <td style="text-align:left;"> Semi news as relates to 🇨🇳 

&amp;gt; https://www.cnbc.com/2022/01/17/meituan-backs-chip-start-up-as-chinese-giants-pour-money-into-space.html
$AMD ↗️➕ $XLNX 🖐💍
$INTC | $NVDA | $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:24:01 </td>
   <td style="text-align:left;"> $AMD $NFLX $NVDA $AAPL $MRNA ~~^&amp;gt;:&amp;quot;::- 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,959 
Goal: $100,000 by end of January. 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:22:43 </td>
   <td style="text-align:left;"> $AAPL $FB Hey Meta freaks! SOS LIMITED IS THE PLAY! https://www.reddit.com/r/SOSLimited/comments/s678qb/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:18:00 </td>
   <td style="text-align:left;"> $AAPL has an average volume of 96865000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:17:54 </td>
   <td style="text-align:left;"> $RIDE $AAPL $F it’s going to be a sad, sad day when all the $RIDE bulls find out that Foxconn bought out their production facility not so they could partner with them, but so they could build the $AAPL car there inside the US and qualify for the federal tax incentives…. Just think about who does $AAPL production now, does anyone really see this going any other way?  Foxconn could have bailed out LMC with a loan but instead they bought specific parts of their yet unused production line, wake up people! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:17:14 </td>
   <td style="text-align:left;"> $AAPL SOS LIMITED IS THE PLAY! Get in before the news... big money to be made :) https://www.reddit.com/r/SOSLimited/comments/s678qb/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:16:49 </td>
   <td style="text-align:left;"> $MVIS can We get interactive projection $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:14:12 </td>
   <td style="text-align:left;"> $AAPL Apple Option Alert: Jan 21 $60 Calls at the Bid: 5 vs 685 OI; Earnings 1/27 After Close🐂 |🥇 Check out ➡️ SweepCast.com  #stockmarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:13:23 </td>
   <td style="text-align:left;"> $SPY $AMC $GME $TSLA $AAPL  👊🏻🧞‍♂️

https://music.amazon.com/albums/B09KP5TDLM?do=play&amp;amp;trackAsin=B09KP5C8PC&amp;amp;ref=dm_sh_2SagkaNVGXBSAdLbGyAxbFzIQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:12:50 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMD $QQQ About to see how inflation has already begun wrecking things and it&amp;#39;s poison will gush blood.

1) Supply chain disruptions USA started October, however, look at inflation data, like PCE Deflator Core index put out monthly by govt, inflation ALREADY out of control and, for TWO MONTHS! 

In fact, infkation Core PCE Deflator index data OVER 2% HIGHER THAN FED FUNDS 🎯 RATE OF 2% 👌 (4.2% Core) as of August 2021👍

Then, it just snowballs from there, both CPI + PCE  wickedly jumping. 28th next PCE read, so, get ready.

And it don&amp;#39;t matter what China, Europe, or anyone wants, all that posturing will do is further irrerepair our relationships w/ both, esp. China. 

China cutting its RATE is further warning and understanding inflation is winning and its cutting deeply soon to the global economy, you did just see Goldman Sachs SLASH growth forecast for USA 2022, no? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 01:07:51 </td>
   <td style="text-align:left;"> Apple App Store Analysis: Netflix And Disney+ Heat Up, AT&amp;amp;T&amp;#39;s HBO Max Catches Fire  $T $NFLX $DIS $AAPL 

https://newsfilter.io/a/65e4318475fd024601d05b5d45690081 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:58:54 </td>
   <td style="text-align:left;"> $DWAC can’t wait tomorrow  to open a position in dwac- my 3 favorite stocks $LCID $AAPL and $DWAC !! Lets make money!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:56:01 </td>
   <td style="text-align:left;"> $AAPL $BA $AMD Print, Post, and STACK!
See you all tomorrow with more great trade plans! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:53:54 </td>
   <td style="text-align:left;"> $SPY Happy MLK day. $QQQ $AAPL $DWAC

&amp;quot;I have a dream, that....!&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:43:19 </td>
   <td style="text-align:left;"> $AAPL Next A16 will use 4nn chips from $TSMC. 📈📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:36:29 </td>
   <td style="text-align:left;"> $AAPL Does the market shift it’s narrative from the bearish Fed to bullish earnings tomorrow or will it be another week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:33:36 </td>
   <td style="text-align:left;"> Ready to STACK MORE $AAPL gains tomorrow?
Let’s do this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:32:53 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : The Retirees&amp;#39; Dividend Portfolio: John And Jane&amp;#39;s December Taxable Account Update https://www.stck.pro/news/AAPL/21475775 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:23:47 </td>
   <td style="text-align:left;"> Top Stock Analysts Of 2021 
 
$TSLA $MRNA $AAPL $FUBO $GME 
 
https://www.chartlearning.com/2022/01/top-stock-analysts-of-2021.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:22:45 </td>
   <td style="text-align:left;"> $BTC.X $AAPL screaming buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:22:21 </td>
   <td style="text-align:left;"> Some students off to a great start in 2022! We embrace volatility.. when many traders are sitting sidelines and don’t know how to play downside or quick spikes back up and then re short opportunities, we are alive and making plays. We thrive when markets are on edge up or down! Let’s stay focused and continue to crush it, 2022 IS GOING TO BE A TRADING YEAR, traders should do really well! $TSLA $QQQ $SBEV $LGVN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:20:14 </td>
   <td style="text-align:left;"> $AAPL trying to sell but noone buying? WTH 🤦‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:17:48 </td>
   <td style="text-align:left;"> $AAPL like this said all tech stocks will be flat this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:16:54 </td>
   <td style="text-align:left;"> $BTC.X $AAPL roaring 20s will continue this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:07:23 </td>
   <td style="text-align:left;"> $SPY $AMD $DWAC $BTC.X $AAPL 
Happy MLK day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-18 00:00:13 </td>
   <td style="text-align:left;"> $AAPL I am seeing more ads of Apple watches than I have ever seen before, and phone companies selling iPhones at 1/3 the prices to get new customers.   Something I have not seen before.    Is this concerning? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:58:54 </td>
   <td style="text-align:left;"> Looks like $DIS $AAPL are bailing out on Pelosi! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:58:41 </td>
   <td style="text-align:left;"> $AAPL https://www.reddit.com/r/SOSLimited/comments/s678qb/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:56:46 </td>
   <td style="text-align:left;"> $AAPL the pullback from the peak can reach $162.10- $152.80 area lower where buyers should be waiting to appear again #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:53:54 </td>
   <td style="text-align:left;"> $AAPL 1hr view from 1/14 Pre-Market update presented to members at elliottwave-forecast.com/ #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:53:21 </td>
   <td style="text-align:left;"> $AAPL will this hit $200 this year.   When?  Thoughts ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:51:57 </td>
   <td style="text-align:left;"> latex87dcab6661874a007a2afb8a261b9f23AAPL 
$DJIA 
 
Slow, but irreducible. .inexorable and irreversible . .there goes the Nasdaq (or at least, today&amp;#39;s futures) . .there it goes, to the scrapping, of stock indices. .
 . ..... ** // </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:46:23 </td>
   <td style="text-align:left;"> $AAPL Chart of The Day 12 January: #Apple can see further downside https://elliottwave-forecast.com/stock-market/elliott-wave-view-apple/  #elliottwave #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:46:11 </td>
   <td style="text-align:left;"> $AAPL Steve Jobs would never have allowed this policy at his company. https://www.reuters.com/technology/apple-require-employee-proof-covid-19-booster-the-verge-2022-01-15/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:45:37 </td>
   <td style="text-align:left;"> How do you think the market will react to this? $AAPL in Uptrend: Stochastic indicator peaks and leaves oversold zone. View odds for this and other indicators: https://srnk.us/go/3331989 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:44:16 </td>
   <td style="text-align:left;"> $SHOP $AAPL $NVDA when is the growth Stock turnaround??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:34:19 </td>
   <td style="text-align:left;"> In The Group 3 live analysis session today, talked about $AAPL liking to buy the dips in 3, 7 or 11 swing at the blue boxes when given the chance. Do not like to sell short AAPL, only like to buy it at the blue box extreme areas #Elliottwave #Trading #Stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:30:31 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPLHappy MLK Day, hopefully your enjoying the time off and relaxing. Great opportunity to step back and get some perspective.  
 
Just wanted to share a tool we built to track trends on socials (Twitter, Stocktwits and Reddit).  Hedge Funds are already using this data - so we wanted to give you the power to track trending stocks across social media. 
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220117 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:19:21 </td>
   <td style="text-align:left;"> $AAPL does anybody remember all the money I lost trading apple options?  I wrote the book.  Enjoy on your day off!

https://books.apple.com/us/book/hedged/id1604296804 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:17:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 23:08:27 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple requiring corporate, store employees to have COVID-19 boosters https://www.stck.pro/news/AAPL/21474223 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 22:59:27 </td>
   <td style="text-align:left;"> $GPCO Chase decline,not rise.Keep buying baby! $AAPL $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 22:39:51 </td>
   <td style="text-align:left;"> 9 Monster Stock Market Predictions - The Week of January 17, 2022 Edition https://mottcapitalmanagement.com/9-monster-stock-market-predictions-the-week-of-january-17-2022-edition/ $AAPL, $RBLX, $NFLX, $MO, $SQ, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 22:33:13 </td>
   <td style="text-align:left;"> $AAPL Why don’t you wake up. Do you realize that you have already been vaccinated several times in your lifetime and you are still here? Our society is what it is because we collectively have subjected our arms to the polio , measles, chicken pox vaccines and a host of others. It’s nothing new. So get over it and get your jab and join society. jerk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 22:26:10 </td>
   <td style="text-align:left;"> $AAPL Been looking at $180 calls for a week now. 

Any catalysts or such I should be aware of before I pull the TRIGGER??? Thnx in advance! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 22:00:58 </td>
   <td style="text-align:left;"> $AAPL Simulated 175.0C for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 21:58:59 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN Follow me for more shit that you could’ve just googled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 21:48:15 </td>
   <td style="text-align:left;"> We&amp;#39;re still waiting on $AMD, $AMZN, etc. to schedule dates, but here&amp;#39;s a look at #earnings season with $TSLA, $AAPL, and $MSFT topping the list 

http://eps.sh/cal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 21:46:41 </td>
   <td style="text-align:left;"> $AAPL $SBEV $ATIP  
$49,000 a day keeps the 9 to 5 away; For a limited time, we are opening our trading chat-room to the public,,   https://www.discord.io/xEvE2Aatrp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 21:35:54 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $msft $FB  what&amp;#39;s going on traders do yourself a favor and be prosperous and stay profitable bears and bulls alike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 21:35:17 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on higher time frames.  We only like to buy it in 3, 7 or 11 swing at the blue boxes.   We still favour lower to take place before the blue box equal leg is hit further down which can play a part in dragging world indices lower this week.    #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 21:32:07 </td>
   <td style="text-align:left;"> Portfolio prediction for next week: Apple( $AAPL ),… https://www.macroaxis.com/invest/marketRatings?s=AAPL,MMM,MKC,AIZ,ABC,ZION,AZO,NWBI,TER,ETN,QCOM,WFC #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 21:29:15 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : RH: Unjustified Clearance Sale On This Best Of Breed Luxury Furniture Brand https://www.stck.pro/news/AAPL/21468998 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 21:22:21 </td>
   <td style="text-align:left;"> $NVDA $AAPL $MSFT FIRE 🔥 SALE but if you want to benefit from the drop buy and sell PUTS like I do in this video https://youtu.be/6I0fTbMvQ-o no BS. $study </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 21:07:39 </td>
   <td style="text-align:left;"> $AAPL                 F……..apple 

They are forcing employees to take vaccines……

Wake up people…..
THIS IS AMERICA…….
The people are in charge…..

Tell apple to go to h…
Time to buy SAMSUNG OR ANYTHING BESIDES APPLE……

This is how it works……
If you don’t buy apple they go out of business…….

If you want the vaccines (( gene therapy ))
Then you or your family can be next! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 20:47:14 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Can 2021&amp;#39;s Best-Performing FAANG Stock Do It Again in 2022? https://www.stck.pro/news/AAPL/21465204 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 20:27:45 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $AAPL is the #1 stock that institutions traded this week with 462.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 20:17:24 </td>
   <td style="text-align:left;"> $AAPL it they build it (VR headset), they will come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 20:11:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-16 Technical Analysis Video: 
https://www.youtube.com/watch?v=BAnnG_dJL4Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 20:06:12 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : How are Adtech Companies Preparing for a Cookieless World? https://www.stck.pro/news/AAPL/21465206 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 20:00:59 </td>
   <td style="text-align:left;"> $AAPL Simulated 175.0C for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 20:00:18 </td>
   <td style="text-align:left;"> #Levermann #US #MegaCap #Sell WK2 $AAPL (1), $AMZN (-4), $FB (1), $JPM (2), $UNH (2), JNJ (2), HD (2), BAC (0), WMT (-2), MA (2) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 20:00:09 </td>
   <td style="text-align:left;"> Lower interest rates great for tech names

https://www.bbc.com/news/business-60019830

$MSFT $AAPL $AMZN $BABA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 19:34:19 </td>
   <td style="text-align:left;"> $AAPL They’ve helped me grow my account to 25.0 million PER DAY!  You too can join liars.com for $1 per month! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 19:29:30 </td>
   <td style="text-align:left;"> $SPY $AAPL $GOOGL  got to love shitna 
Apple browser bug could lead to personal data leak
Apple browser bug could lead to personal data leak https://www.rt.com/news/546261-apple-safari-browser-data-leak/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 19:23:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : The Capital Sponge https://www.stck.pro/news/AAPL/21464653 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 18:57:32 </td>
   <td style="text-align:left;"> $GME $WMT $NVDA $AAPL $MRNA ~&amp;gt;&amp;lt;&amp;gt;:: #02 ::&amp;gt;&amp;gt;&amp;lt;&amp;gt;~ 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,959 
Goal: $100,000 by end of January. 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 18:51:30 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $AAPL is the #1 ticker with sweep activity that institutions traded urgently this week options with 343.8K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 18:31:00 </td>
   <td style="text-align:left;"> $AAPL outperforms 90% of all stocks! https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 18:16:19 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Big Tech Meets White House to Tackle Software Security Concerns https://www.stck.pro/news/AAPL/21459883 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 18:14:50 </td>
   <td style="text-align:left;"> $AAPL $AMZN $ROKU Who needs WallStreetBets when you have Xtrades. Thanks to Xtrades, I have doubled my entire portfolio in just one week. Joining this Discord community was the best investment I&amp;#39;ve ever made.  tinyurl.com/ioiugrf5t65sz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 18:14:49 </td>
   <td style="text-align:left;"> ROTFLMAO, what a crock of EU unregulated manipulated self serving bs renliarsnfigure, figures lie ... Financial spreadbetters expect London&amp;#39;s FTSE to open 21 points higher at 7,564, Frankfurt&amp;#39;s DAX to open 43 points higher at 15,927 and Paris&amp;#39; CAC to open 19 points higher at 7,162. Asian share markets were choppy as a slew of Chinese economic data confirmed the deadening effect of coronavirus restrictions on consumer spending, prompting Beijing to again ease monetary policy. Oil prices rose, with Brent crude futures at their highest in more than three years, as investors bet supply will remain tight amid restrained output by major producers with global demand unperturbed by the Omicron coronavirus variant. ... rest assured severe stock market crashes in queue $tsla $f $ccl $h $aapl and more  🐻❤😈✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 18:11:44 </td>
   <td style="text-align:left;"> $FCEL $AAPL $GEVO They have helped me to grow my account to almost 2.5 million.. stockplays.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 18:03:06 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-16 Largest Trades Data: 
https://www.youtube.com/watch?v=MglgCb8wofM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 17:54:44 </td>
   <td style="text-align:left;"> $TSLA $AAPL $NVDA They have helped me to grow my account to almost 2.5 million.... stockplays.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 17:35:33 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Abides by a Dutch Ruling – Report https://www.stck.pro/news/AAPL/21459891 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 17:29:58 </td>
   <td style="text-align:left;"> $WIMI $AAPL $RBLX 🔥🔥In the future, how to establish a business closed loop covering technology, business model, application scenarios and operation mechanism with the support of &amp;quot;Metaverse&amp;quot; will be the focus of WIMI&amp;#39;s exploration.💥💥💥
 👏👏It&amp;#39;s worth noting that Metaverse is still in the concept exploration stage around the world, and it&amp;#39;s getting a lot of attention as well as a lot of buzz. In the long run, metaverse, a great new industry, will improve and grow, but it&amp;#39;s not easy to predict who will win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 17:19:04 </td>
   <td style="text-align:left;"> $TSLA $AAPL $SPY  MLK was a fraud. Open the markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 17:08:30 </td>
   <td style="text-align:left;"> $AAPL wait wtf are futures open ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 17:05:41 </td>
   <td style="text-align:left;"> $AAPL some euro trading stats for today:
It saw $173.64 
It dropped to $173 
It went back to $173.07
It is now trading at US AH close of $173.28
It has a new Ask of $173.50
It has a current bid of $173.36 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 17:00:56 </td>
   <td style="text-align:left;"> $AAPL Simulated 175.0C for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 16:54:00 </td>
   <td style="text-align:left;"> $aapl ftse, nikkei , sensex , SSE all green. Only Hang seng taking a dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 16:25:12 </td>
   <td style="text-align:left;"> $AAPL $FB $WIMI $GME Four major technology trends you can&amp;#39;t ignore in 2022 are gradually approaching

https://medium.com/@elyseewpryh67/four-major-technology-trends-you-cant-ignore-in-2022-are-gradually-approaching-6c56df414787 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-17 16:22:56 </td>
   <td style="text-align:left;"> $AAPL LFGG green week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:39:21 </td>
   <td style="text-align:left;"> $TSLA this is going to be super red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:36:14 </td>
   <td style="text-align:left;"> $TSLA bears pinning their hopes on nasdaq futures. I&amp;#39;m pinning my hopes on TSLA&amp;#39;s stellar ER coming next week. Let&amp;#39;s see who wins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:33:37 </td>
   <td style="text-align:left;"> $TSLA These rumours about a tesla phone are not real.... but I would love to see what happens to apple stocks they were actually real!!!! Apple would overreact and dump! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:33:00 </td>
   <td style="text-align:left;"> $TSLA bears pinning their hopes on nasdaq futures. I&amp;#39;m pinning my hopes on TSLA&amp;#39;s stellar ER coming next week. Let&amp;#39;s see who wins. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:32:53 </td>
   <td style="text-align:left;"> $NKLA https://www.youtube.com/watch?v=gys8PS8Nr2w 
 
 
$PLUG $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:27:55 </td>
   <td style="text-align:left;"> $TSLA hows it looking in europe? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:27:00 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:21:42 </td>
   <td style="text-align:left;"> $tsla deliveries out of its Giga Shanghai factory totaled 484,130 vehicles in 2021, of which 321,000 vehicles were sold in China, it was reported on Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:19:24 </td>
   <td style="text-align:left;"> $TSLA Tesla will go up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:17:33 </td>
   <td style="text-align:left;"> $TSLA musk will pay for his criminal disrespect towards the great American senator Bernie sanders. Cybertruck still hasn&amp;#39;t been delivered. Where is the roadster? 

https://www.google.com/amp/s/www.proactiveinvestors.com/companies/amp/news/204377 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:15:58 </td>
   <td style="text-align:left;"> $TSLA It May test $900 again but ER is soon so the pullback will have to wait !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:13:31 </td>
   <td style="text-align:left;"> $TSLA Tesla and tulip both starts with T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:08:18 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-16 Technical Analysis Video: 
https://www.youtube.com/watch?v=Swq1COe3seM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:07:39 </td>
   <td style="text-align:left;"> $TSLA back from the 3 day weekend. Prepare to gargle my balls bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:04:41 </td>
   <td style="text-align:left;"> $PLUG $17.88 support watch $fcel $spy $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 14:02:10 </td>
   <td style="text-align:left;"> $TSLA Simulated u for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:59:18 </td>
   <td style="text-align:left;"> $TSLA-Breaking News YESSSS- https://www.cnbc.com/amp/2022/01/17/tesla-inks-deal-to-get-key-battery-component-outside-china.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:58:18 </td>
   <td style="text-align:left;"> $UPST $SNOW $tsla $SQ open your buttcheeks to get buttfucked again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:56:48 </td>
   <td style="text-align:left;"> $TSLA futes looking great 😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:54:22 </td>
   <td style="text-align:left;"> $TSLA 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:53:31 </td>
   <td style="text-align:left;"> $TSLA so I see people tripping about the 10 year treasury yields being high. But if you take a look at the chart and correlate the pandemic timeline with that of yields for the past three years you will see a pattern emerge. Every time the pandemic eases up and there is a supposed “light at end of tunnel” yields drop quite aggressively. The opposite is true when the “light” goes away and we enter another wave. Omicron will pass quickly with less death and shorter hospitalization which is starting to be apparent. Yields will drop and money will flow away from “risk free treasuries” and move into equities and riskier investments. This is just my opinion, look at the chart. I don’t think we are on the verge of a crash just a correction and then next leg up. Again just an opinion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:51:06 </td>
   <td style="text-align:left;"> $TSLA     World  Wide  ……it’s the same  
Hundreds of Teslas sighted in Auckland port, hinting at even more growth in NZ 
https://www.teslarati.com/tesla-surges-new-zealand-photos/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:49:53 </td>
   <td style="text-align:left;"> $TSLA will my 800 puts 1/21 print tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:48:59 </td>
   <td style="text-align:left;"> $TSLA https://www.nasdaq.com/articles/tesla-tsla-upgraded-to-strong-buy%3A-heres-why </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:47:14 </td>
   <td style="text-align:left;"> $TSLA FSD coming next year. Every year since 2014. Meanwhile GM and GOOG-GOOGL have actual fully self driving cars TODAY. Semi was due since 2019 and so was Cybertruck. Battery Plant is also long overdue. This is called fraud. Ask how Elizabeth Holmes how that works out. Elon Musk is next. Always been the ending of this story. Not my fault you believe in pots of gold at the end of rainbows. I am not you. Never will be. I defy. You follow. Somethings are just by nature in this dog eats dog world. Best to realize that NOW before LATER. Gary Gensler just do what Biden appointed you for already. I can&amp;#39;t save the world or fix stupid no matter how hard it is I try. God knows that is endlessly... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:47:02 </td>
   <td style="text-align:left;"> $TSLA https://www.msn.com/en-us/autos/news/report-made-in-germany-tesla-model-y-performance-coming-in-march/ar-AASS0Dw?ocid=BingNewsSearch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:46:11 </td>
   <td style="text-align:left;"> $TSLA has the production of Model Y at Giga Austin started? 

Source: https://youtu.be/0rVQYB69ZSQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:41:55 </td>
   <td style="text-align:left;"> $TSLA wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:40:51 </td>
   <td style="text-align:left;"> $TSLA https://phonereview24.com/tesla-phone-pi-5g/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:38:01 </td>
   <td style="text-align:left;"> $TSLA https://investorplace.com/2021/02/tsla-stock-is-worth-50-percent-more-by-2022-year-end-so-buy-its-leaps/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:37:36 </td>
   <td style="text-align:left;"> $TSLA  
fuck the futures ….you people sound like a bunch of school girls ….and by the looks of your profiles pictures …..I’m surprised how popular investing is among you young women these days  
 
if it dips we buy 
When it rips we roadster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:35:40 </td>
   <td style="text-align:left;"> ... Armageddon Depression update https://intodayspaper.cmail20.com/t/ViewEmail/d/9081FB4F14E42B112540EF23F30FEDED/D26BC6F6CAEB86714BD7C9066BE4161D?alternativeLink=False $tsla $f $ccl $aal $aapl 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:35:20 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-16 Trade Analysis Video: 
https://www.youtube.com/watch?v=Fk_AuCl9yGE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:34:29 </td>
   <td style="text-align:left;"> $TSLA can this open 800 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:32:38 </td>
   <td style="text-align:left;"> $TSLA Only reminiscence of this company that will even exist by 2025 is Tesla Shanghai Ltd. since technically Tesla Inc. doesn&amp;#39;t even truly own that. China does. Again. What follows here will prove my words as true so I don&amp;#39;t even care what you think or say. That is the real difference between us. Your words mean nothing. Mine will only ring bells. Enjoy knowing that... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:32:12 </td>
   <td style="text-align:left;"> $TSLA traders market. mind as well... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:31:57 </td>
   <td style="text-align:left;"> $TSLA why didn’t I buy more pits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:29:18 </td>
   <td style="text-align:left;"> $TSLA has future s ever been know to change to positive over night before opening? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:25:48 </td>
   <td style="text-align:left;"> $TSLA Permanent losses. Sad but true. Nothing even all of you combined can do to stop that. 2025 Price Target is $0. This company won&amp;#39;t even exist at all by then. Fly by night and it is daytime now. Don&amp;#39;t take my word for it. Actions that follow will speak for themself. Is what it is... Not my fault. This was all planed before you even heard of Tesla Inc. Oops. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:23:05 </td>
   <td style="text-align:left;"> $TSLA nice rug pull of the Nasdaq, 2Y and 10Y yields are surging, I guess we will have more nice buying opportunities in 900-s on Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:20:33 </td>
   <td style="text-align:left;"> $TSLA tomorrow red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:20:32 </td>
   <td style="text-align:left;"> $TSLA Truth is I know how all this works. I know this game inside and out. Market Makers both know and love me. You  however are simply clueless and me being just who I am; try to actually help the have nots understand this 99% loss market. You pay rent. You pay car payments. I don&amp;#39;t. Never will. I am everything you want to be but yet... Why do I bother? Cathy Wood is a boomer and she baited you. Now like a light switch reality gets turned on and you are the one that loses here. Not me. I will do this until my last breathe and teach my toddlers the same. I was being nice. Like it or not this is over now. Sorry I am not sorry. I gave you my all... Now watch it fall. Scapegoat Elon Musk Agenda Activated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:20:16 </td>
   <td style="text-align:left;"> $TSLA Is is a glitch or we had 3-year high today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:15:16 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:14:20 </td>
   <td style="text-align:left;"> First thing to do in the morning, is to check futures levels before entering into a play… saying that… I’ll be watching #1:
$rblx $tsla $mos $kbh $sq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:09:44 </td>
   <td style="text-align:left;"> $TSLA You all own their $35 shares at a $1000+ average but you are winning right? This is like buying permanent losses. How didn&amp;#39;t you know? Pitty is for the weak. You are the weak. I pitty you now more than ever. Anyone with REAL SUMS of money would not invest in this today for over $10 but you know better. You know so much YOU that willingly followed a boomer named Cathy Wood to YOUR doom while calling everyone else who opposed her a boomer. Wtf were YOU thinking? You got robbed. Legally. How disgusting. Like taking candy from a baby. 3k NEVER. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:09:12 </td>
   <td style="text-align:left;"> $TSLA NQ(NASDAQ) heading back up 15614 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:08:23 </td>
   <td style="text-align:left;"> $TSLA Just remember what Powell said last week.  Expect three, maybe four rate increases this year.  For those that think this is short term guess again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:07:18 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-16 Options Analysis Video: 
https://www.youtube.com/watch?v=d2iBIjrfL5Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:05:44 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY Trump’s  rally over the wknd tanking the markets!🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:04:54 </td>
   <td style="text-align:left;"> $TSLA going under 1k this week probably tomorrow latest is weds and will be 800s before earnings to burn all the calls when fed is hawkish then it will rocket after earnings only if big beat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:03:45 </td>
   <td style="text-align:left;"> $TSLA can this go to 800 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:02:39 </td>
   <td style="text-align:left;"> $TSLA 2/10 inversion knocking on the door with debt to gdp ratio well above 120% for a sustained period of time. How clueless one must be to not know what is coming. Everyone was a genius in a bull market. Boomers robbed you like they did GenX and us Melenials. You can&amp;#39;t beat them at this long sick game they play. You been working for them the whole time. I don&amp;#39;t work for anyone yet cared enough to try and warn you. Guess you will learn like I once did. The hard way... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:02:14 </td>
   <td style="text-align:left;"> $TSLA this stock and market is going to be manipulated so bad i think best time is to just buy long calls on day of earnings after Fed meeting on 26th in the meantime load up puts on any pop theres just too many negative news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:02:05 </td>
   <td style="text-align:left;"> $DIA $pl $tsla Futures bright red. Did pedo with dementia President Brandon open his mouth again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:01:12 </td>
   <td style="text-align:left;"> $TSLA Confirmation.  The Nikkei just went Red and tanked about 300 points from a session high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:00:55 </td>
   <td style="text-align:left;"> $TSLA 910 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 13:00:27 </td>
   <td style="text-align:left;"> $TSLA Face ripper rally is larger and faster on every short dip. We&amp;#39;re lucky so many amateurs help goose the gains on Best in Class execution and earnings growth. Not necessary for so many shorts to blow up their accounts, more than a few have seen the light and are longs now. May the dips continue to be delicious and frequent. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:59:26 </td>
   <td style="text-align:left;"> $TSLA oh no L0N3W01FTR4D3R is back 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:56:18 </td>
   <td style="text-align:left;"> $TSLA In 2000 the Fed reckt the dot.con bubble but most people still blame Enron and all the traders of the time for being so inexperienced and stupid. Wonder who they will scape goat this time? You Tesla Lemmings. That is who. Written all over the wall for ALL the ages to SEE forever more. Welcome to the real market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:56:00 </td>
   <td style="text-align:left;"> $TSLA: The long term trend is positive and the short term trend is neutral. Lets see where this goes. https://www.chartmill.com/stock/quote/TSLA/technical-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:55:56 </td>
   <td style="text-align:left;"> $TSLA well drop below 1000 this week for another tes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:55:08 </td>
   <td style="text-align:left;"> $TSLA earnings, major profits, 2 new Gigas, product roadmap update including cybertruck and semi and few fun surprises by Mr. Musk...uhh bears, you&amp;#39;re finished!! 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:54:51 </td>
   <td style="text-align:left;"> $TSLA this slump every other day theme is getting old now... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:54:05 </td>
   <td style="text-align:left;"> $TSLA Got my1010 p’s  01/21/22 Ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:54:00 </td>
   <td style="text-align:left;"> $TSLA Cathie Wood Continues Profit-Booking In Tesla, Selling Another $28M On Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:52:52 </td>
   <td style="text-align:left;"> $NVDA $TSLA $MRNA I’ve made $93,111.27 by their alerts. Big thanks to this chat room!! Make as much as you want... 🚀 https://www.discord.io/xEvE2Aatrp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:51:40 </td>
   <td style="text-align:left;"> $TSLA These Futures tonight don’t mean shit with earnings coming up in a week . TSLA is going to run and run hard .. 1300 this week Mark this post </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:50:31 </td>
   <td style="text-align:left;"> $TSLA And so it begins. The most erroneously valued stocks get hit the hardest and fastest. Did you see this coming? If no you must be blind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:49:50 </td>
   <td style="text-align:left;"> $TSLA cannot wait for market open.. time to shut up all the bears 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:49:28 </td>
   <td style="text-align:left;"> $TSLA you would think New Zealand had enough coast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:49:25 </td>
   <td style="text-align:left;"> $NIO not a long video. Everyone should check it out. $XPEV $TSLA 

https://youtu.be/i9fDUWRUJ80 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:46:57 </td>
   <td style="text-align:left;"> $TSLA the 2 new Gigas are ALIVEEEE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:45:08 </td>
   <td style="text-align:left;"> $TSLA bears truly are the dumbest of the dumb. Just because they know a few facts, they think they know what they&amp;#39;re doing. Just like a kid who went with his dad to the shooting range thinks he knows how to handle a gun. And then a tragic accident happens. Except in this case, it won&amp;#39;t be tragic. I&amp;#39;ll be holding their money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:44:46 </td>
   <td style="text-align:left;"> $TSLA https://www.bloomberg.com/news/articles/2022-01-17/stocks-set-for-cautious-start-yen-dips-before-boj-markets-wrap?sref=pHyhiApD   
 
US equity futures fell and Asian stocks were mixed Tues amid a jump in TSY yields, as investors girded for QT rate-hikes by the FOMC to quell inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:44:23 </td>
   <td style="text-align:left;"> $TSLA I’m thinking the 1050 puts will make for a great day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:42:39 </td>
   <td style="text-align:left;"> $TSLA 

This is the true byproduct of Government spending !! 

Seriously Joe!!  you want to push BBB scam plan !! More spending !!??

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:42:07 </td>
   <td style="text-align:left;"> $TSLA Another dot.com bubble will make Chinese economy surpass USA’s economy and have so bad consequences for USA in next 10 years so don’t expect at all another market crash maybe 10 or 15 percent correction that’s all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:40:23 </td>
   <td style="text-align:left;"> Cathie Wood Stocks to Buy and Hold for 10 Years $RBLX $TSLA $SE https://bit.ly/326GcoG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:39:17 </td>
   <td style="text-align:left;"> $TSLA The Fed has run out of tools.  You don&amp;#39;t want to know what the next step is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:39:01 </td>
   <td style="text-align:left;"> $TSLA I tried to warm y’all 🙋🏻‍♂️🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:38:49 </td>
   <td style="text-align:left;"> $TSLA 
https://driveteslacanada.ca/news/blusmart-india-promises-to-buy-1000-tesla-model-3s-as-several-leaders-try-to-woo-elon-musk-to-set-up-manufacturing-in-their-states/  
HOLD ON BULLS WE r going. Higher tomorrow no doubt. This is huge news, they have been working on for a few years. It really is huge news. Wouldn’t wanna be short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:38:34 </td>
   <td style="text-align:left;"> $TSLA US 10 year @ 1.847 yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:37:22 </td>
   <td style="text-align:left;"> $TSLA market conditions aren’t looking very good for bulls……more red coming…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:37:16 </td>
   <td style="text-align:left;"> $TSLA   
Lots of buyers jumping in this week for record  earnings coming up! 
 
Looking forward  to Elon joining the call to make an announcement📣  
 
PT $1200+ Q4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:37:12 </td>
   <td style="text-align:left;"> $TSLA  $SPY  $QQQ 

All these Bear post , talk to me at 8:30 Am tomorrow when market opens !

Good night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:35:54 </td>
   <td style="text-align:left;"> ... Most excellent, welcome to Crash Tuesday and the Armageddon Depression, indices-futures are plunging downward severely as socioeconomic news spirals upwards. Carry on sticking forks in the stock markets at large for profits my friends, followers, haters and those on block for jawboning self serving nonsense. Thank dog that I am here to help. 🐻❤😈✔ https://www.investing.com/indices/indices-futures ... https://finviz.com/news.ashx ... @Profit_Maker https://stocktwits.com/Profit_Maker 🤑 $tsla $f $ccl $aal $aapl and more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:35:00 </td>
   <td style="text-align:left;"> $TSLA don&amp;#39;t be scared grasshopper. Many bears will die this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:34:52 </td>
   <td style="text-align:left;"> $TSLA 950 Before 2/4
Come on Elon, sell more shares! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:33:57 </td>
   <td style="text-align:left;"> $TSLA nasdaq down tomorrow . Tesla up ;) don’t forget who told you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:33:07 </td>
   <td style="text-align:left;"> $SPY $MARA $AMZN $TSLA $AMC ;;;; 
 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $97,369 
Goal: $100,000 by end of January, 2022 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓 discord.io/MqakycG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:32:51 </td>
   <td style="text-align:left;"> $TSLA the play before was manipulate NQ futures and now it’s bond yields to tank Nasdaq/tech before earnings play out next week.. how it’s easy for the big players to just move markets however they want..  😵‍💫🤦🏻‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:32:20 </td>
   <td style="text-align:left;"> $TSLA Another spectacular trading week on tap. Enjoy ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:31:51 </td>
   <td style="text-align:left;"> $TSLA    
Futures never mattered much before  
   TSLA is the safe  harbour   
TSLA  beat inflation by about 97% last year  
 
PT $1200 + Q4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:30:31 </td>
   <td style="text-align:left;"> $TSLA We start another week tomorrow.  I&amp;#39;m ready... are you? Have a plan in place and be ready for any price movement. We all know stocks move 3 ways. Let&amp;#39;s have a great week!  If you not hustling, you not trying! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:30:21 </td>
   <td style="text-align:left;"> $TSLA opening around 1020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:29:37 </td>
   <td style="text-align:left;"> $TSLA fsd gets better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:29:36 </td>
   <td style="text-align:left;"> $TSLA      
The math is simple even Bears should grasp  
every Q is better than the last  
 
             More deliveries  = more $ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:29:31 </td>
   <td style="text-align:left;"> $TSLA Elon will pull this up no matter how the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:29:06 </td>
   <td style="text-align:left;"> $TSLA we go high as all are down/red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:27:39 </td>
   <td style="text-align:left;"> $TSLA 🏴‍☠️🏴‍☠️🏴‍☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:27:27 </td>
   <td style="text-align:left;"> $TSLA blood 🩸 bath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:27:17 </td>
   <td style="text-align:left;"> $TSLA Giga Berlin is buzzing! 
Report: Made-In-Germany Tesla Model Y Performance Coming In March. Dozens of black Model Y were already produced as part of the preparations. 🤞🏻🤞🏻 
 
https://insideevs.com/news/561267/report-mig-tesla-modely-coming/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:27:11 </td>
   <td style="text-align:left;"> $TSLA 
Futures are red.
We open in upper $900s tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:27:02 </td>
   <td style="text-align:left;"> $TSLA bloodbath tomorrow likely, nq down yield up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:26:25 </td>
   <td style="text-align:left;"> $TSLA moon ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:23:53 </td>
   <td style="text-align:left;"> $TSLA     Semi infrastructure said  to be mote like …. Being quietly built out across the continent  
https://insideevs.com/news/561326/new-photos-tesla-megachargers/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:23:44 </td>
   <td style="text-align:left;"> $AMD  $nvda   $intc   $aapl   $TSLA  
 
 
 4nm Exynos with AMD  RDNA2 graphics just announced! AMD will gap up with the news! 
 
https://www.samsung.com/semiconductor/minisite/exynos/newsroom/pressrelease/samsung-announces-game-changing-exynos-2200/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:23:21 </td>
   <td style="text-align:left;"> $TSLA sensing so much fear on this board.  You noobs really haven&amp;#39;t experienced a true market crash. You are about to find out though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:22:28 </td>
   <td style="text-align:left;"> $AMC $SPY $NVDA $TSLA ,,,,,;;;; 
 
 
Account Challenge Update:~ 
Starting Balance January 3rd: $300  
Current balance January 15th: $1415.02  
Goal: $12,500 by end of year 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/MqakycG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:21:45 </td>
   <td style="text-align:left;"> $TSLA imagine being a bull w Biden, Omicron, Russia about to deploy more troops to Ukraine, fed interest rate increases pending and oh dumb fuk Biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:21:33 </td>
   <td style="text-align:left;"> $TSLA $850 measured move break that also lines up with a gap! Would create a double bottom at Jan ‘21 high and PCZ of the harmonic. Would be sweet if this played out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:21:15 </td>
   <td style="text-align:left;"> $TSLA One  thing is for sure Fed won’t let another dot.com bubble happen period! So don’t expect a similar market crash but 10 percent correction likely maybe we are in that correction right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:21:12 </td>
   <td style="text-align:left;"> $TSLA $COIN Apparently Cathie places more faith in Coinbase than Tesla.  Thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:20:41 </td>
   <td style="text-align:left;"> $TSLA when speculation gets crushed by fundamentals, fed rate hikes, supply chain disruption and lower gdp. It going to be spectacular </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:20:21 </td>
   <td style="text-align:left;"> $TSLA       
 
FSD subscriptions up  bigly ..as people try before price hike to $12k  
 
  FSD……because everyone wants to be driven ! 
 
Soon FSD will get you a discount on auto insurance…….100x safer than driver alone! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:20:09 </td>
   <td style="text-align:left;"> $TSLA If this goes to 1.8 tomorrow, game over.  Market wide.  Especially tech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:16:21 </td>
   <td style="text-align:left;"> $BCRX It turns out that if you spend time in space you get increased hemolysis that leads to anemia. SpaceX may need BCX9930 if they want to build that colony on Mars. $TSLA  
https://www.nature.com/articles/s41591-021-01637-7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:15:20 </td>
   <td style="text-align:left;"> $TSLA     
 Record Deliveries + Record Margins    
                        =Record  Profits  
It’s not rocket science  
 
PT $1200+ Q4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:14:46 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $MSFT uh-oh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:14:13 </td>
   <td style="text-align:left;"> $TSLA imagine standing right next to this.... that is what&amp;#39;s about to happen to your brokerage accounts when the Fed is no longer manipulating the market... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:12:57 </td>
   <td style="text-align:left;"> $TSLA a lot puts are scared </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:12:56 </td>
   <td style="text-align:left;"> $TSLA 

CBs control everything— playing with markets and world economy!! 

One day 10YR Yields up HFs front run it attacking growth stocks then the next day Yields are down and yay market is up and so forth !! 

This is global market manipulation &amp;amp; terrorism- reducing the reliance on CBs is what Cryptocurrency all about - only then things will be different !!  This is getting old !! 

F*** CBs!

🙏🏻🐉🦅👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:12:10 </td>
   <td style="text-align:left;"> $TSLA   After Q4 earnings  
credit rating expected to be raised  
more Tutes buying up TSLA ! 
 
too easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:11:48 </td>
   <td style="text-align:left;"> $TSLA the whole week is going to be red now ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:11:46 </td>
   <td style="text-align:left;"> $TSLA With India, Germany and China expansion in horizon, guidance for 2002 will be around 1.5 million cars - Earnings is going to be a blockbuster; $1300 by 1/28 looks real good, irrespective of what happens this week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:10:43 </td>
   <td style="text-align:left;"> $TSLA Look at the After Hours action last Wednesday and the subsequent tanking the next day.  Friday After Hours was the same setup. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:09:29 </td>
   <td style="text-align:left;"> $TSLA    Best selling cars just about everywhere now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:09:26 </td>
   <td style="text-align:left;"> $TSLA The number of tesla buyers is growing every year. #vehiclesales </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:08:57 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
Oh, they&amp;#39;re cranking it like no tomorrow... 
 
https://www.investing.com/rates-bonds/usa-government-bonds 
 
$AAPl $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:08:57 </td>
   <td style="text-align:left;"> $TSLA recall last Friday, TSLA futures down 30+, we were green before 10AM. Leading up to monster earnings, we’ll retest 1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:08:37 </td>
   <td style="text-align:left;"> $AMC We are North American Apes                                                                                                                                            
                                                                                                                                  
Americans                                                                                                                                            
Mexicans                                                                                                                                            
Canadians                   
  
Follow for weekly free plays. 
 
Buy 50 calls AMC $25 for 1/21 
Buy 30 calls GME $130 for 1/21 
Buy 10 call TSLA 1,150 for 1/21 
We hate Shorts!   
$GME $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:08:10 </td>
   <td style="text-align:left;"> $TSLA https://www.google.com/amp/s/www.aljazeera.com/amp/economy/2022/1/17/as-india-waffles-on-sops-for-tesla-several-states-woo-musk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:06:58 </td>
   <td style="text-align:left;"> $TSLA let the bodies hit the floor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:06:54 </td>
   <td style="text-align:left;"> $TSLA below $1000 tomo at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:06:49 </td>
   <td style="text-align:left;"> $TSLA Now all of the sudden the Nikkei is starting to tank. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:05:36 </td>
   <td style="text-align:left;"> $TSLA 💸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:04:32 </td>
   <td style="text-align:left;"> $TSLA and by the way. You Shot Morons. Tomorrows headline for TSLA is already out. India is dying to have TSLA just curious how many people do I Morton’s think are in INDIA? We are going up big with Short covering going into earnings, I wouldn’t sell you one share. Lol see you at $1400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:03:48 </td>
   <td style="text-align:left;"> $TSLA I hope you saw market makers game o last Friday like me and didn’t buy call options for this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:03:40 </td>
   <td style="text-align:left;"> $TSLA  
FXHedge 
@Fxhedgers 
· 
28m 
10-YEAR YIELD 1.83% HIGHEST SINCE DEC 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:03:25 </td>
   <td style="text-align:left;"> $TSLA Same shit story as last years, 10 year goes up and futures drop 😢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:02:55 </td>
   <td style="text-align:left;"> $TSLA just sold a bunch of $AMZN friday. looking to add to tsla, $AMD and $NVDA. there will be blood lol but it&amp;#39;s a long-term buying opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:01:47 </td>
   <td style="text-align:left;"> $TSLA  On Friday volume was going down and price was going up. I stayed quiet because I know it&amp;#39;s priced in. 🤪🤪🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:01:28 </td>
   <td style="text-align:left;"> $DWAC $SPY $BTC.X $TSLA  
 
Poll: Nearly Half Of Democrats Support Fines, Segregated Camps And Prison Terms For Those Who Disagree With Them On COVID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:00:48 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

PERMA BULLS TOMORROW... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:00:18 </td>
   <td style="text-align:left;"> $TSLA What?  LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 12:00:03 </td>
   <td style="text-align:left;"> $TSLA ok futures tanking hard tech is done till earnings week =( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:59:13 </td>
   <td style="text-align:left;"> $TSLA getting ugly here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:58:14 </td>
   <td style="text-align:left;"> $TSLA this is when the market gets savage and you begin seeing people jumping off buildings.  It will certainly get much worse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:58:12 </td>
   <td style="text-align:left;"> $TSLA yahoo finance is trash what is Nasdaq down rn? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:57:42 </td>
   <td style="text-align:left;"> $TSLA ready to burn $1000 puts this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:57:18 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:56:36 </td>
   <td style="text-align:left;"> $TSLA Bond yields are over $1.85 hope markets don’t crash ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:56:31 </td>
   <td style="text-align:left;"> $TSLA 
10 year 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:55:50 </td>
   <td style="text-align:left;"> $TSLA Ooof, nasdaq down cuz 10 year? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:55:22 </td>
   <td style="text-align:left;"> $TSLA 
Since when did selling stocks at a massive scale make the price goes up? You Bullards got set up on Friday to get dumped on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:55:10 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboys....don&amp;#39;t forget to keep your overpriced rape whistle beside you this week. Muahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:54:28 </td>
   <td style="text-align:left;"> $TSLA Something special is brewing 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:54:02 </td>
   <td style="text-align:left;"> $TSLA Going to be a very telling day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:53:13 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Cathie Wood Continues Profit-Booking In Tesla, Selling Another $28M On Friday https://www.stck.pro/news/TSLA/21499023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:51:20 </td>
   <td style="text-align:left;"> $TSLA damn Tsla getting rekt tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:51:06 </td>
   <td style="text-align:left;"> $TSLA see this hitting 980 at very minimum tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:51:01 </td>
   <td style="text-align:left;"> $TSLA wait until the 10 yr reaches 2% by Friday, dumb asses. Tesla Fanboys&amp;#39; asses are about to get reamed. They don&amp;#39;t even realize the savagery that they are about to encounter.  GL losers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:50:58 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $BTC.X 

FUTES RIP-PING.... 🪦📉🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:49:48 </td>
   <td style="text-align:left;"> $TSLA. You Bears are really funny. The Nasdaq Futures and for that matter mean nothing at night.  Any one piece of news could come out to nought and pound the Futures lower and the market goes down or there is good new and the Market goes up. But please don’t be as ignorant to get the Nasdaq or any other market confused with TSLA. Just look at where the Nasdaq went since Jan 1st and TSLA is up. We are in the process of a combination of a short squeeze and Gama squeeze like u have never seen. With earnings out in next week and split this stock could easily move up $225 points in 2-3 days.s. In fact that’s what it did while the market tanked. See you at $1400. SOON! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:48:54 </td>
   <td style="text-align:left;"> $TSLA Here&amp;#39;s What Elon Musk Has To Say About Dogecoin&amp;#39;s Joke Origins 

https://newsfilter.io/a/76292fa9b54d508c4c3e7b86c0ec2a5c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:48:37 </td>
   <td style="text-align:left;"> $TSLA wow. 10 year really starting to tank the futures could be really ugly tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:48:11 </td>
   <td style="text-align:left;"> $TSLA $SPY $COTI.X $49,000 a day keeps the 9 to 5 away; For a limited time, we are opening our trading chat-room to the public.   https://www.discord.io/rBHacCP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:48:08 </td>
   <td style="text-align:left;"> $DWAC $SPY $BTC.X $TSLA  
 
Poll: Joe Biden’s Approval Rating Slumps, Plurality Say Handled Coronavirus Worse than Trump 
 
Additionally, the survey found that “pluralities of respondents believe Joe Biden has handled the economy (46%), immigration (44%), national security and defense (41%), and foreign policy (41%) worse than Donald Trump.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:47:49 </td>
   <td style="text-align:left;"> $TSLA think 10yr might hit close to 1.95-2.0% tomorrow. See if induces weakness holds throughout the night by opening. Things change </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:47:38 </td>
   <td style="text-align:left;"> $TSLA I’m going to do the Butt naked dance in front of the police station when gigatexas is in operation! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:47:35 </td>
   <td style="text-align:left;"> $TSLA man futures not looking good , tomorrow might be a blood bath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:47:14 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboys and their idol are about to f&amp;#39;ing burn 🔥! GL You POSs were warned! Muahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:43:29 </td>
   <td style="text-align:left;"> $MSFT $SPY  
 
See...sooner than I thought. 
 
$AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:43:12 </td>
   <td style="text-align:left;"> $TSLA This is getting so predictable 10 year up Nasdaq down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:41:21 </td>
   <td style="text-align:left;"> $Tsla (SOS) Keep SOS Limited on watch! https://soslimited.us/f/40-price-target-from-scorpiovc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:39:27 </td>
   <td style="text-align:left;"> $TSLA The 10 year keeps this up its going to pay as much as dividend stock hmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:38:01 </td>
   <td style="text-align:left;"> $TSLA 10 year at 1.84% ouch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:37:43 </td>
   <td style="text-align:left;"> $TSLA is this what’s hitting the Nasdaq futs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:31:30 </td>
   <td style="text-align:left;"> $TSLA 
Yep. 23 millions shares were sold to retailers  on Friday. It was going up on purpose so they can pull the rug Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:30:48 </td>
   <td style="text-align:left;"> $TSLA Imagine one day Asian markets tanking overnight, followed by the European. Wow 😁👌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:30:18 </td>
   <td style="text-align:left;"> $MSFT $SPY We&amp;#39;re going &amp;quot;down, down, baby&amp;quot; after the morning pop. 
 
https://finance.yahoo.com/quote/MSFT/options?p=MSFT 
 
$AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:28:04 </td>
   <td style="text-align:left;"> $TSLA You bulls going to learn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:27:09 </td>
   <td style="text-align:left;"> $TSLA 10 year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:26:34 </td>
   <td style="text-align:left;"> $TSLA 10 year 1.82 ugh...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:26:17 </td>
   <td style="text-align:left;"> $TSLA SAVE LOS ANGELES ITS THE NEW GOTHAM CITY @Elon_Musk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:23:57 </td>
   <td style="text-align:left;"> $TSLA why can’t we buy the Tesla car with Dogecoin ? Get the picture ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:23:33 </td>
   <td style="text-align:left;"> $TSLA Message volume in this thread down $18+ percent. lol

Where’d everybody go? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:23:21 </td>
   <td style="text-align:left;"> $TSLA crude at $85 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:22:14 </td>
   <td style="text-align:left;"> $TSLA  Bitcoin. The price people are willing to pay for nothing!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:22:13 </td>
   <td style="text-align:left;"> $SPY FEBRUARY GOING TO BE A BLOODY MONTH. $AAL $NFLX $QCOM $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:20:50 </td>
   <td style="text-align:left;"> $TSLA not red tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:19:49 </td>
   <td style="text-align:left;"> $TSLA Giga-what?!  

Model Ys in the Austin lot. 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:19:09 </td>
   <td style="text-align:left;"> $TSLA $1500 by February. Get ready. Don&amp;#39;t ever bet against Elon one of the humans that&amp;#39;s will be remember 300 years from now. Almost like betting against Albert Einstein. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:17:19 </td>
   <td style="text-align:left;"> $TSLA i love tsla as much as most of you bulls but does any bullish person here realistically look at the direction of the market and remain bullish? Tsla will provail  in the future asnit has now, but dont you consider the wider market implications of a looming depression? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:16:10 </td>
   <td style="text-align:left;"> $TSLA my woke boss and his elitist German wife who own a Tesla, are suddenly starting to diss musk. OMG, rules to investing 101! Get in when they’re fearful! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:11:52 </td>
   <td style="text-align:left;"> $NIO $TSLA  related news:

https://thedriven.io/2022/01/18/tesla-and-nio-supplier-catl-confirms-battery-swap-rumours/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:10:41 </td>
   <td style="text-align:left;"> $TSLA Elon getting picked up in two Germany made Model Ys from the airport once he visits. 
Elon so busy working hard for us... love this old man!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:10:04 </td>
   <td style="text-align:left;"> $TSLA what % of &amp;quot;shorts&amp;quot; on this board are just poor fucks who can&amp;#39;t even afford 2 shares TSLA and just come here to troll? 95%? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:09:01 </td>
   <td style="text-align:left;"> $TSLA Standing rule for Elon... refrain from commenting on ANY post with dollar signs or posts discussing Tesla&amp;#39;s valuation. Also off limits, ANY post discussing your whereabouts and why. Please and thank you. That is all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:08:55 </td>
   <td style="text-align:left;"> latexf97947b21c3e3c1f862125d7582dd774AAPL 
$DJIA 
You tell me, if this is not art. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:05:28 </td>
   <td style="text-align:left;"> $NKLA $TSLA : </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:05:16 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-16 Technical Analysis Video: 
https://www.youtube.com/watch?v=Swq1COe3seM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:04:13 </td>
   <td style="text-align:left;"> $SPY  10 year is totally manipulated today everyone knows there is very limited liquidity during overnight sessions beside we have auction tomorrow so fuck you bond bullies be ready to get your ass spanked. it’s earning season and tell me when last time in earning season we had more than 5% drawdown ???  do not drop your balls bulls  $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:02:55 </td>
   <td style="text-align:left;"> Cathie Wood Continues Profit-Booking In Tesla, Selling Another $28M On Friday  $TSLA $ARKK $ARKW $XPEV $SNAP 

https://newsfilter.io/a/0e3be0b907529c3e7319f13526f71d09 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:01:58 </td>
   <td style="text-align:left;"> $TSLA Simulated u for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:01:28 </td>
   <td style="text-align:left;"> $TSLA damn, Elon is again in a wrong mood. Ok, now everyone will scream he thinks the company is overvalued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 11:01:23 </td>
   <td style="text-align:left;"> $TSLA https://www.etsy.com/listing/1159194621/tesla-vinyl-decal-clear-background?ref=shop_home_active_2&amp;amp;frs=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:59:17 </td>
   <td style="text-align:left;"> $TSLA trying to send a message? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:58:40 </td>
   <td style="text-align:left;"> $NKLA $TSLA 
https://youtu.be/gys8PS8Nr2w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:57:06 </td>
   <td style="text-align:left;"> $TSLA damn, bad news, Elon debunked the rumor of him visiting Berlin this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:55:39 </td>
   <td style="text-align:left;"> $TSLA yeah, that&amp;#39;s right 👍! Let&amp;#39;s burn some shorts on Tuesday

Btw, current price of Tesla is slightly BELOW the price BEFORE the insane Q4 deliveries beat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:54:35 </td>
   <td style="text-align:left;"> $TSLA Yup, 🔝is in. Sell! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:54:00 </td>
   <td style="text-align:left;"> $TSLA: The Revenue is expected to grow by 35.52% on average over the next 5 years. This is a very strong growth https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:53:36 </td>
   <td style="text-align:left;"> Wondering who were the best Analysts of 2021? Wish u could follow their advice? 
 
Check out @TipRanks Top Analysts of 2021 LIVE Awards Ceremony, Jan 20th @ 11am EST!  
 
Watch the best give their Top Picks for 2022! 
 
$AAPL $TSLA $SPY $QQQ $SPY 
 
Free Sign Up 
👇 
https://bit.ly/3f6YNUA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:51:36 </td>
   <td style="text-align:left;"> $AAPL $MSFT $TSLA huge earnings next week for some great companies. Easy money in calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:50:02 </td>
   <td style="text-align:left;"> $TSLA Uh oh, Elon commenting on a post with a video of him burning “$TSLA Shorts” with a Not-A-Flamethrower… he’s feeling cocky boyz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:48:31 </td>
   <td style="text-align:left;"> $AMD $TSLA $INTC 

I wonder, if these guys paid a premium like Apple &amp;quot;to ensure capacity&amp;quot; this quarter for their customers🤔

🚨

$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:45:44 </td>
   <td style="text-align:left;"> $TSLA Just noticed SOS Limited and BBIG trending on Reddit and Twitter... Retail trying to force some squeezes?  
 
Technicals show a gap fill to $2.10 range is possible. In for 1000 shares tomorrow!  
 
Keep SOS on watch and add to strength. 
 
$3+ Coming! KEEP IT ON WATCH 
 
https://www.reddit.com/r/SOSLimited/comments/s678qb/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:45:42 </td>
   <td style="text-align:left;"> $TSLA &amp;gt; $LCID &amp;gt; $F &amp;gt; $RIVN &amp;gt; $NKLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:42:47 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/SawyerMerritt/status/1483212695017041923?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:42:42 </td>
   <td style="text-align:left;"> $TSLA 

When garbage meet junk you get a pile of trash !’ 

Can someone take this pile of trash out !! Stinks 😷!! 

Oh one more thing! 
NYTimes is the biggest trash container!! 

🙏🏻🐉🦅🗑🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:41:04 </td>
   <td style="text-align:left;"> A Beginner&amp;#39;s Guide On Learning How To Trade 
 
$TSLA $MRNA $AAPL $FUBO $GME  
 
https://www.chartlearning.com/2016/01/learn-how-to-trade.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:38:19 </td>
   <td style="text-align:left;"> $TSLA retest of $1100 by Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:34:49 </td>
   <td style="text-align:left;"> $TSLA  
 
#2 Trending on Twitter the last 24hrs - getting a lot of attention. You&amp;#39;ll want to keep an eye on this tonight and at market open tomorrow.  
 
We build this tool for you guys - check it out here https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220117 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:32:13 </td>
   <td style="text-align:left;"> Asian markets Green!! Let’s go $SPY $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:31:38 </td>
   <td style="text-align:left;"> $TSLA  Holding 1086/1048 is important on the weekly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:28:36 </td>
   <td style="text-align:left;"> $ALAC just counting the days for warrants to 5x and s-4 acceptance with voting dates….

Need more listed solar companies, great opportunity here.

 $TSLA $FSR latexf771efa4a93406dfa4d688e14b8f341fBABA 
$TSLA 
 
Very complete analysis, on the present and future developments of the company. .
MercadoLibre is the largest e-commerce ecosystem in LATAM.
Its operations span 18 countries including Argentina, Brazil and Mexico.
Its legacy business is e-commerce, but its growth narrative and profitability will eventually originate from its fintech operations.
Ａｓ ＬＡＴＡＭ＇ｓ ｌａｒｇｅｓｔ Ｅ－ｃｏｍｍｅｒｃｅ ｐｌａｙｅｒ， ＭｅｒｃａｄｏＬｉｂｒｅ ｈｏｓｔｓ ａｌｍｏｓｔ ４Ｘ ｍｏｒｅ ｖｉｓｉｔｓ／ｍｏｎｔｈ ｔｈａｎ ｔｈｅｉｒ ｃｌｏｓｅｓｔ ｃｏｍｐｅｔｉｔｏｒ ｗｈｉｃｈ ａｌｓｏ ｈａｐｐｅｎｓ ｔｏ ｂｅ ｇｌｏｂａｌ Ｅ－ｃｏｍｍｅｒｃｅ ｇｉａｎｔ Ａｍａｚｏｎ．

https://seekingalpha.com/article/4476946-mercadolibre-the-fundamentals-remain-rock-solid-buy?li_source=LI&amp;amp;li_medium=liftigniter-widget </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:16:30 </td>
   <td style="text-align:left;"> $TSLA lots of dumb ass bears tonight, screen shot the stupidity so you can rub it in their face when we’re at 1300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:15:12 </td>
   <td style="text-align:left;"> $FUBO $TSLA Fails to realize profits ! ! ! $FUBO acquires $TSLA with the force of Seal Team Six &amp;amp; Tim Cook $AAPL  ! ! ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:12:59 </td>
   <td style="text-align:left;"> $TSLA Market manipulation is not something to play with. Fraud musk will pay for his dodgy financial moves. As a hardworking American I beg of Tesla investors to sell while Biden’s market is still intact. Let’s be a little smarter with our finances, cheers all @sofibull75 @OhGodWhatHasBecome </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:10:22 </td>
   <td style="text-align:left;"> $TSLA Thailand going down not good New Zealand government taking over  😕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:09:25 </td>
   <td style="text-align:left;"> $GOOG  $COST $TSLA THE 1% TOOK TOO MUCH.   now no one wants to work. they are still living off the stimi&amp;#39;s.  my expensive  town can&amp;#39;t find anyone to work in the restaurants, hotels, coffee shops, retail.... etc.      
wild times as wage inflation goes insane. 
$190 for a lift ticket now.  and no one to groom the runs or make u hot coco. 
#vanlife ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:08:18 </td>
   <td style="text-align:left;"> $TSLA @jccoo You playing center naked for boyfriend tonight?  Snappin him those balls while the Somali market is closed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:05:03 </td>
   <td style="text-align:left;"> $TSLA futes red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:04:37 </td>
   <td style="text-align:left;"> $TSLA https://join.flahmingo.com
Check it out, let me know what you guys think </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:03:54 </td>
   <td style="text-align:left;"> $TSLA Where’s dick breath @jccoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:03:22 </td>
   <td style="text-align:left;"> A message from the wise to the morons who shorted! 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:02:18 </td>
   <td style="text-align:left;"> we are now live for the weekend update 🔥 
⚔️I&amp;#39;m going to announce the winner of the @tradersync  give away  
👉im also going to cover 👇 
📈TRADE IDEAS 
🔫TRIGGERS  
🎯TASRGETS  
AND MORE 
CLICK  https://us02web.zoom.us/webinar/register/WN_2XCaJkjEQCKrBzfVQ1Eahg 
 $spy $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 10:02:02 </td>
   <td style="text-align:left;"> $TSLA fuck me tesla. just hit 1300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:56:09 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:45:20 </td>
   <td style="text-align:left;"> $TSLA New Zealand is currently invading Thailands mainland by force. This will affect TSLA delivery bad.  Www.cmsworldnews/NZinvadesthaigovern.org </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:40:50 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:40:18 </td>
   <td style="text-align:left;"> $SPY $TSLA Still looking at Inverse Head and Shoulders (I-H&amp;amp;S). Last weeks push threatened the break down of the neck line but bulls held their ground. Close to a billion In The Money (ITM) gamma expiring into OPEX with ER next week. Not investment advice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:39:34 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:39:12 </td>
   <td style="text-align:left;"> $TSLA $F $CENN &amp;gt;&amp;gt;

Elon Musk // @elonmusk //Replying to 

@skorusARK

Tesla &amp;amp; Ford are the only American carmakers not to have gone bankrupt out of 1000’s of car startups. Prototypes are easy, production is hard &amp;amp; being cash flow positive is excruciating.

3:04 PM · Mar 4, 2021·Twitter for iPhone

All these new EV companies now &amp;gt;&amp;gt; market is saturated with companies destined for bankruptcy &amp;gt;&amp;gt;

https://twitter.com/elonmusk/status/1367611973697818628?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:37:36 </td>
   <td style="text-align:left;"> $UPWK I just found out about this company by accident using their website.  Holy shit this is literally my next Tesla like company that&amp;#39;s going to change my life again.  I use Indeed and Glassdoor and think that makes me a pretty smart employee in terms of getting my worth plus I follow the subreddit for my profession to understand compensation etc.  This in my opinion is going to change the labor marketplace, I am new and just found out about this 45 minutes ago, but am I far reaching here?  This concept just hit me in the face like when I bought $TSLA in the summer of 2019.  Maybe I am missing something but holy crap I might quit my job and freelance here even though I make great money.  This is nuts....... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:36:24 </td>
   <td style="text-align:left;"> $SPY $ES_F Above $4743 to break the downtrend, there could possibly be more volatile moves before resistance is broken. We’re starting the week on a Tuesday &amp;amp; Wednesday is usually choppy it’ll be interesting to see where the price is at the end of the week, last trading week before FOMC and both $TSLA &amp;amp; $AAPL earnings… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:33:23 </td>
   <td style="text-align:left;"> $TSLA $1111 tomorrow’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:32:20 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-16 Options Analysis Video: 
https://www.youtube.com/watch?v=d2iBIjrfL5Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:31:37 </td>
   <td style="text-align:left;"> $TSLA price prediction tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:30:44 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMC $AMD $AMZN :&amp;quot;::- #01 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,959 
Goal: latexc5ae64e067b70256fbc88d0c659923a4BABA 
$TSLA 

＃ ＷＥＥＫＬＹ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:19:59 </td>
   <td style="text-align:left;"> $TSLA ** Has anyone seen this for SOS Limited? Trending currently on all social media! Give it a watch... $3 coming soon! 
 
I&amp;#39;m buying 1000 shares tomorrow.  
 
https://www.reddit.com/r/SOSLimited/comments/s678qb/breaking_news_sos_limted_gamma_squeeze_potential/?utm_source=share&amp;amp;utm_medium=web2x&amp;amp;context=3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:19:43 </td>
   <td style="text-align:left;"> RT Analysis: When chasing your tail is the smart trade. Plus what to do with $TSLA https://cracked.market/2022/01/when-chasing-your-tail-is-the-smart-trade-plus-what-to-do-with-tsla/ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:19:15 </td>
   <td style="text-align:left;"> $TSLA I wish this went up before earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:18:39 </td>
   <td style="text-align:left;"> $TSLA making sure they work for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:18:34 </td>
   <td style="text-align:left;"> $TSLA has Cathy lost her mind?🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:18:34 </td>
   <td style="text-align:left;"> $TSLA TSLA Earnings Date 
Earnings announcement* for TSLA: Jan 26, 2022 
Tesla, Inc. is expected* to report earnings on 01/26/2022 after market close. The report will be for the fiscal Quarter ending Dec 2021. According to Zacks Investment Research, based on 6 analysts&amp;#39; forecasts, the consensus EPS forecast for the quarter is $1.5699999999999998. The reported EPS for the same quarter last year was $0.24. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:17:43 </td>
   <td style="text-align:left;"> $TSLA $CVNA $ATVI $MARA  Start trading over 3 month ago and I lost all of money, Now I&amp;#39;ve made over $120K+ profits after join 🔗 their chat room, and using their alerts.,,,🚀 discord.io/3NxHHWku8d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:17:36 </td>
   <td style="text-align:left;"> $TSLA Next Wednesday 01-26-22 Earnings and Musk lecture on $25K spors car, Cybertruck timeline </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:16:28 </td>
   <td style="text-align:left;"> $TSLA 1700 before earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:14:33 </td>
   <td style="text-align:left;"> $TSLA is it the only company in Berlin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:13:39 </td>
   <td style="text-align:left;"> $TSLA laughable haha https://m.youtube.com/watch?v=dUUm-dVDj78 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:13:13 </td>
   <td style="text-align:left;"> $TSLA Shutdown coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:13:05 </td>
   <td style="text-align:left;"> $TSLA selling the house. All in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:11:45 </td>
   <td style="text-align:left;"> $TSLA earnings 1/26 and maybe giga Texas opening announcement 1/29 to represent the 129 rumors? Since Berlin visit isn’t until February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:07:42 </td>
   <td style="text-align:left;"> $TSLA could see this going either way tomorrow but I do think omicron surge has big impact in forward thinking sentiment during earning season. That all being said would love to pick this up at 950 this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:06:04 </td>
   <td style="text-align:left;"> $TSLA 

#Shorts this week will feel like 🔝 kick 👇

🙏🏻🐉🦅🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:05:39 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:04:58 </td>
   <td style="text-align:left;"> $TSLA Global economy is about to derail whose ready for more upcoming negative  news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:04:15 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:03:32 </td>
   <td style="text-align:left;"> $TSLA Simulated u for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:01:50 </td>
   <td style="text-align:left;"> $TSLA futures is mostly green! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 09:01:01 </td>
   <td style="text-align:left;"> $TSLA future is negative sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:57:39 </td>
   <td style="text-align:left;"> $TSLA I would like this stock to goo 2000 i well not gett rich butt this guy they hate the company soo much  they can look at it and cry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:55:38 </td>
   <td style="text-align:left;"> $TSLA Don’t be surprised if we trade over 1150 tomorrow.. there’s gonna be a lot of Momentum into Earnings this week Bulls Trade accordingly good luck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:53:53 </td>
   <td style="text-align:left;"> $TSLA I guess they’ll be raiding FSD prices in Canada soon. Big fat software margins! https://electrek.co/2022/01/17/tesla-releases-full-self-driving-beta-10-9-software-update-announces-expansion-canada/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:53:00 </td>
   <td style="text-align:left;"> The Altman-Z score of latexa79afe42946b36000958a239fee9e476NIO
$F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:47:49 </td>
   <td style="text-align:left;"> $TSLA ....https://i-want-to-believe.com/2022/01/17/kill-time-3/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:47:34 </td>
   <td style="text-align:left;"> $TSLA run up ER next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:47:10 </td>
   <td style="text-align:left;"> $TSLA Bulls bulls bulls😌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:44:37 </td>
   <td style="text-align:left;"> $TSLA That ten year yield👀🥰🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:42:43 </td>
   <td style="text-align:left;"> $TSLA ✅✅✅✅ https://www.reddit.com/r/pennystocks/comments/s6bgpf/comprehensive_report_conservatively_showing_a_633/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf

Help a small lung cancer bio company 
Showed an excellent phase 2results that doubled the life expectancy for lung cancer patients from 11 months to 24 1/2 month without chemotherapy.🙏🙏
$HTBX.  . Help us stop criminals shorts manipulation.🙏🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:42:39 </td>
   <td style="text-align:left;"> $TSLA Buyer beware. Scam Company.Caution. Proceed at your own risk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:41:13 </td>
   <td style="text-align:left;"> $TSLA 800 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:40:41 </td>
   <td style="text-align:left;"> $TSLA Bulls are you ready to catch a falling machete yet?😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-18 08:37:58 </td>
   <td style="text-align:left;"> $TSLA open at 980 tomorrow? </td>
  </tr>
</tbody>
</table></div>

---
