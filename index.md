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



Last Updated: 2022-01-10 16:05:51 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/romania/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-10 15:57:45 </td>
   <td style="text-align:left;"> Romania Trade Gap Widens in November </td>
   <td style="text-align:left;"> Romania's trade deficit widened to EUR 2.16 billion in November 2021 from EUR 1.58 billion gap in the same month the previous year. Exports grew 17.5 percent year-on-year to EUR 7.09 billion, while imports rose at a faster 21.5 percent to a new record high of EUR 9.25 billion. Considering the first eleven months of the year, the trade gap increased sharply to EUR 21.37 billion from EUR 16.44 billion in the same period of 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-10 15:54:05 </td>
   <td style="text-align:left;"> Switzerland 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Switzerland 10 Year Government Bond Yeld increased to a 3-year high of 0.016% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 15:50:26 </td>
   <td style="text-align:left;"> UK Stocks Set to Open Higher </td>
   <td style="text-align:left;"> The FTSE 100 headed for a positive session on Monday, extending a third week of gains, as investors across the globe await another US inflation print later this week that could provide further guidance on the Federal Reserve's monetary policy path. US policymakers are now expected to start raising interest rates four times this year as the CPI is seen hitting a near four-decade high of 7% year-on-year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/austria/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-10 15:49:35 </td>
   <td style="text-align:left;"> Austria 10Y Bond Yield Hits 21-month High </td>
   <td style="text-align:left;"> Austria 10 Year Government Bond Yeld increased to a 21-month high of 0.201% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-10 15:48:12 </td>
   <td style="text-align:left;"> Danish Inflation Rate Eases in December </td>
   <td style="text-align:left;"> Denmark's annual inflation declined to 3.1% in December of 2021 from 3.4% a month earlier, due to softer rises in prices of food and non-alcoholic beverages (1.6% vs 2.1% in November),  housing, water, electricity, gas and other fuels (5.2% vs 5.3%), transport (6.6% vs 9.5%), and restaurants &amp; hotels (3.6% vs 3.7%). Meanwhile, prices continued to increase for clothing &amp; footwear (2.4% vs 1.3%), miscellaneous goods and services (1.6% vs 1.5%), while rebounded for furnishing, household maintenance (0.1% vs -1.3%), health (0.3% vs -0.3%), and furnishing, household maintenance (0.1% vs -1.3%). On the other hand, inflation was steady for recreation &amp; culture (at 1.5%), education (at 2.1%). By contrast, prices fell for: communication (-1.1% vs 0.1%), alcoholic beverages, tobacco (-0.2% vs -0.3%). On a monthly basis, consumer prices fell by 0.5%, reversing from a 0.3 percent gain in November. The harmonized index of consumer prices rose 3.4%, easing from a 3.8% growth in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 15:45:24 </td>
   <td style="text-align:left;"> China Stocks Rise on Reform Expectations </td>
   <td style="text-align:left;"> The Shanghai Composite rose 0.39% to close at 3,594 while the Shenzhen Component gained 0.44% to 14,407 on Monday, as mainland stocks erased early losses and staged a broad market rebound, led by Shanghai’s tech-focused STAR Market amid reform expectations. The China Securities Regulatory Commission said late on Friday it will pilot market-making on Shanghai’s Nasdaq-style STAR Market in a bid to deepen reforms and improve liquidity. The announcement followed pledges by the agency’s head to adopt various measures to stabilize the market, as an ugly start to 2022 prompted him to ease investors’ nerves. Nearly all sectors of the market rebounded following sharp declines last week, with notable gains from Kweichow Moutai (1.24%), China Mobile (2.05%), Tianqi Lithium (3.59%), Andon Health (1.82%) and Muyuan Foods (5.35%), among others. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/romania/unemployment-rate </td>
   <td style="text-align:left;"> 2022-01-10 15:39:59 </td>
   <td style="text-align:left;"> Romania Jobless Rate Unchanged at 5.2% </td>
   <td style="text-align:left;"> Romania's seasonally adjusted unemployment was at 5.2 percent in November, unchanged from a downwardly revised figure in October, with the number of unemployed rising 8 thousand from the previous month to 432 thousand. Meanwhile, the jobless rate for men was stable (at 5.5 percent) while that for women increased (4.9 percent vs 4.7 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 15:39:00 </td>
   <td style="text-align:left;"> European Shares Set to Start Week Higher </td>
   <td style="text-align:left;"> European shares look set to open up slightly on Monday following losses last week, as investors remain cautious ahead of the release of a batch of economic data including the US inflation rate due Wednesday. The CPI is seen climbing to a near four-decade high of 7% year-on-year, which could prompt the Federal Reserve to deliver in March its first interest-rate hike since the pre-pandemic era. Last Friday, inflation in the Eurozone hit 5% in December, a new record high. Elsewhere, rising COVID-19 infections added to traders' concerns. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-10 15:32:17 </td>
   <td style="text-align:left;"> Ireland 10Y Bond Yield Hits 21-month High </td>
   <td style="text-align:left;"> Ireland 10 Year Government Bond Yeld increased to a 21-month high of 0.372% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/currency </td>
   <td style="text-align:left;"> 2022-01-10 15:27:41 </td>
   <td style="text-align:left;"> Chinese Yuan Gains on Corporate Demand </td>
   <td style="text-align:left;"> The offshore yuan edged higher toward 6.375 per dollar on Monday, as corporate demand ahead of the Lunar New Year offset expectations of a more aggressive monetary tightening by the US Federal Reserve. The People’s Bank of China also set the midpoint rate at a near 3-week high of 6.3653 per dollar, 89 pips firmer than the previous fix of 6.3742. The moves came after the yuan depreciated last week as strong hawkish signals from the Fed sent US Treasury yields higher, squeezing the yield spread between Chinese and US 10-year government bonds and raising the risk of capital outflows. Meanwhile, the Chinese central bank is widely expected to ease monetary policy further  to cushion an economic slowdown. Investors also grew concerned over China’s zero-tolerance approach to Covid as the first cases of the omicron variant was reported in the city of Tianjin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-10 15:19:00 </td>
   <td style="text-align:left;"> DanishTrade Surplus Widens in November </td>
   <td style="text-align:left;"> Denmark's goods and services trade surplus increased to a seasonally adjusted DKK 17.6 billion in November 2021 from an upwardly revised DKK 16.6 billion in the previous month. Exports rose 3.7 percent month-on-month to DKK 135.8 billion. Meanwhile, imports grew at a softer 3.3 percent from a month earlier to DKK 118.1 billion. Considering the first eleven months of the year, the trade surplus widened to DKK 153.6 billion from DKK 151.1 billion a year earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/unemployment-rate </td>
   <td style="text-align:left;"> 2022-01-10 15:18:25 </td>
   <td style="text-align:left;"> Turkish Jobless Rate Holds Steady at 11.2% </td>
   <td style="text-align:left;"> The unemployment rate in Turkey stood at 11.2 percent in November 2021, unchanged from October's four-month low. The number of unemployed increased by 39 thousand from the previous month to 3.777 million and employment levels rose by 228 thousand to 29.855 million. Job gains occurred in all sectors: services (up 95 thousand); industry (up 73 thousand); agriculture (up 49 thousand); and construction (up 10 thousand). Meanwhile, the labor underutilization dropped to 22.1 percent from 22.8 percent a month earlier; while the youth jobless rate for those aged between 15-24 years was up 1.7 percentage points at 22.3 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/current-account </td>
   <td style="text-align:left;"> 2022-01-10 15:18:00 </td>
   <td style="text-align:left;"> Denmark Current Account Surplus Widens </td>
   <td style="text-align:left;"> Denmark's current account surplus rose to a seasonally adjusted DKK 21.4 billion in November 2021 from an upwardly revised DKK 20.8 billion in the previous month. It was the largest current account surplus since June 2020, as the surplus of goods account increased to DKK 7.3 billion from DKK 6.5 billion in October and that of services account edged up to DKK 10.3 billion from DKK 10 billion. Meantime, the surplus of primary income fell slightly to DKK 7.8 billion from DKK 8.1 billion in October; while the gap of secondary income was at DKK 4.0 billion, compared with a deficit of DKK 3.9 billion in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/10/tennis/djokovic-australia-covid-hearing-intl-hnk/index.html </td>
   <td style="text-align:left;"> 2022-01-10 15:14:43 </td>
   <td style="text-align:left;"> Novak Djokovic:Judge orders tennis star be freed from immigration detention in Australia - CNN </td>
   <td style="text-align:left;"> (CNN)World tennis No. 1 Novak Djokovic will be allowed to defend his men's singles title at the Australian Open in Melbourne this month, after a judge quashed the government's decision to cancel his visa and ordered him to be freed.                                                                                                                               , Following hours of deliberations, technical glitches and arguments from both sides, Justice Anthony Kelly ordered Djokovic to be released from a temporary hotel detention facility and his possessions returned within 30 minutes of the Monday ruling.                                                                                                                , Justice Kelly also ordered the respondent in the case -- the Australian Ministry of Home Affairs -- to pay Djokovic's legal costs.                                                                                                                                                                                                                                      , Following the decision, a lawyer for the government said Australia's Minister for Immigration reserves the right to personally intervene in the case. Christopher Tran, acting for the government, said Minister Alex Hawke retains ministerial power to remove Djokovic from the country, despite the ruling.                                                          , The ruling, held via video link at the Australian Federal Circuit Court in Melbourne, comes after days of speculation and public anger about whether the tennis star would be able to play in the Australian Open, despite being unvaccinated for Covid-19.                                                                                                             , The 34-year-old Serb flew to Australia on January 5, only to have his visa canceled after Australian Border Force deemed his medical exemption from requirements that all arrivals be fully vaccinated against Covid-19 was invalid.                                                                                                                                    , Faced with deportation and his hopes of winning a record 21st Grand Slam in jeopardy, Djokovic launched a legal challenge.                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                         , During the hearing, Djokovic's legal team argued he had obtained the required medical exemption to travel to Australia and bypass vaccination restrictions for Covid-19. That exemption had been granted on the grounds that Djokovic had natural immunity after being infected with Covid-19 in December, his defense argued.                                          , Djokovic, who has previously voiced opposition to Covid-19 vaccines and vaccine mandates, was unvaccinated when he arrived in Australia. In his ruling, the judge noted that if Djokovic had been deported, he would have been banned from Australia for three years.                                                                                                   , The case has attracted worldwide attention and sparked anger from both his supporters and critics, with some saying his case shows celebrities are getting special treatment when it comes to Australia's tough Covid-19 rules, which have seen families separated for years, and others who believe coronavirus restrictions are encroaching on their civil liberties. , Djokovic's situation has also highlighted the plight of asylum seekers in Australia -- with dozens of refugees inside the same hotel as Djokovic who have been locked up for years, and who face indefinite detention under Australia's tough immigration rules.                                                                                                        , The arguments                                                                                                                                                                                                                                                                                                                                                           , The arguments for both the defense and the government essentially centered around guidelines issued from an advisory group for the federal government called the Australian Technical Advisory Group on Immunization (ATAGI).                                                                                                                                           , Nick Wood, Senior Counsel representing Djokovic, argued ATAGI advice states that past Covid infection provides at least six months of natural protection -- "and therefore may be regarded as a temporary exemption to vaccination."                                                                                                                                    , He said Djokovic understood he'd been given approval to come to Australia by the government, and had made repeated appeals to federal officers in Melbourne that "he had done absolutely everything that he understood was required for him to enter Australia."                                                                                                        , "Any reasonable person would understand, and he did understand, that he had ticked absolutely every box," Wood added.                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                         , Lawyers for Australian Minister for Home Affairs, Karen Andrews, defended the Australian Border Force decision to deport Djokovic, arguing the tennis star did not provide any medical reason why he could not be vaccinated against Covid-19.                                                                                                                          , The government said Djokovic was mistaken to think he was guaranteed entry, and that a previous Covid infection does not equate to a valid medical reason why he could not be vaccinated.                                                                                                                                                                               , They pointed to the same ATAGI guidelines, which say despite acknowledgment of natural protection, past infection "is not a contraindication to vaccination" -- meaning it is not a valid reason for somebody not to get the vaccine.                                                                                                                                   , The government also argued that while those guidelines suggest people can temporarily put off their vaccination after acute illness, "there was no suggestion Djokovic was seriously ill."                                                                                                                                                                              , "All he has said is that he tested positive for Covid-19. That is not the same," the government said in its court submission.                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                         , Tran, the government's barrister, said authorities have a low bar to canceling visas and that even the possibility of a risk to Australians' health was reason enough.                                                                                                                                                                                                  , Justice Anthony Kelly, however, appeared to acknowledge Djokovic's position, saying he was "agitated" by the burden placed on the tennis star to provide officials with evidence.                                                                                                                                                                                       , Djokovic had recorded a Covid-19 infection in December -- which two independent panels agreed to be a good enough reason to delay Djokovic's need to be vaccinated.                                                                                                                                                                                                     , "What more could this man have done?" Judge Kelly said.                                                                                                                                                                                                                                                                                                                 , What Djokovic is playing for at the Australian Open                                                                                                                                                                                                                                                                                                                     , The visa debacle had threatened Djokovic's chances of winning a record 21st Grand Slam at the Australian Open, which kicks off in Melbourne on January 17.                                                                                                                                                                                                              , Djokovic currently holds 20 Grand Slam victories, equaling the all-time record with tennis greats Spain's Rafael Nadal and Switzerland's Roger Federer.                                                                                                                                                                                                                 , A victory in Melbourne would mean Djokovic breaks the record for the most career grand slams ever held by a man.                                                                                                                                                                                                                                                        , That is a very real possibility -- Djokovic has won the Australian Open nine times before.                                                                                                                                                                                                                                                                              , Federer, 40, is not playing in Melbourne and while Nadal, 35, is set to play, he has been beset with injury.                                                                                                                                                                                                                                                            , The pair have faced each other 58 times, with Djokovic leading with 30 wins to 28. Nadal, who has won one Australian Open in 2009, is ranked world No. 6.                                                                                                                                                                                                               , CNN's Hilary Whiteman, Hannah Ritchie and Angus Watson contributed reporting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/finland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-10 15:00:05 </td>
   <td style="text-align:left;"> Finland 10Y Bond Yield Hits 21-month High </td>
   <td style="text-align:left;"> Finland 10 Year Government Bond Yeld increased to a 21-month high of 0.192% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/currency </td>
   <td style="text-align:left;"> 2022-01-10 14:59:44 </td>
   <td style="text-align:left;"> Japanese Yen Steadies Amid Calls for Stability </td>
   <td style="text-align:left;"> The Japanese yen steadied around 115.8 per US dollar on Monday, gaining some ground after dipping to 116.35 last week, as the Japanese finance minister stressed the need for currency stability and said he was watching market moves closely and their impact on the economy. Analysts have warned of negative implications from a weak yen, which pushes up import prices and households’ cost of living at a time when the economy is recovering from the pandemic. However, the yen remained close to 5-year lows as monetary policy between Japan and other countries continued to diverge. While other central banks signaled readiness to normalize monetary settings, the Bank of Japan is widely expected to maintain its ultra-loose policy as Japanese inflation remained well below the 2% central bank target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2022-01-10 14:51:42 </td>
   <td style="text-align:left;"> Aussie Dollar Pressured as Fed, Virus Weigh </td>
   <td style="text-align:left;"> The Australian dollar hovered below $0.72 on Monday, remaining under pressure amid a steady rise in US Treasury yields as traders braced for a more aggressive monetary tightening by the Federal Reserve. The latest Fed minutes revealed US policymakers considered quicker interest rate hikes and discussed quantitative tightening this year to tame persistently high inflation. The firm hawkish stance pushed US bond yields higher, hurting stocks and risk-sensitive currencies. Meanwhile, the Reserve Bank of Australia has repeatedly insisted that a hike in domestic rates is not likely until 2023, or until inflation pushes sustainably within its 2-3% target range. The latest omicron wave in the country also complicated the outlook for the economy and interest rates. Moreover, the RBA lagged behind other major central banks in dialing back pandemic-era stimulus, but is set to decide whether to end its bond-buying early this year at its Feb. 1 meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/egypt/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-10 14:39:00 </td>
   <td style="text-align:left;"> Egypt Inflation Rate Below Estimes </td>
   <td style="text-align:left;"> The annual inflation rate in Egypt increased to 5.9% in December of 2021 from 5.6% in November, but below market expectations of 6.1%. On a monthly basis, consumer prices edged down 0.1%, the first monthly decline in 11 months, reversing from a 0.1% rise in the previous </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/currency </td>
   <td style="text-align:left;"> 2022-01-10 14:34:57 </td>
   <td style="text-align:left;"> New Zealand Dollar Struggles for Momentum </td>
   <td style="text-align:left;"> The New Zealand dollar hovered below $0.679 on Monday, struggling to gain momentum amid a steady rise in US Treasury yields as traders braced for a more aggressive monetary tightening by the Federal Reserve. The latest Fed minutes revealed US policymakers considered quicker interest rate hikes and discussed quantitative tightening this year to tame persistently high inflation. The firm hawkish stance pushed US bond yields higher, hurting stocks and risk-sensitive currencies. Meanwhile, the Reserve Bank of New Zealand has already hiked interest rates twice to 0.75% this year and is widely expected to move to 1.0% at its Feb. 23 policy meeting amid persistent inflation and record low unemployment. A milder than expected third quarter economic contraction in New Zealand also solidified expectations of further central bank monetary tightening, but moves in the currency remained subdued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/steel </td>
   <td style="text-align:left;"> 2022-01-10 14:28:00 </td>
   <td style="text-align:left;"> Steel is down by 2.07% </td>
   <td style="text-align:left;"> Steel Rebar decreased 2.07% to 4551 CNY/T but not far from CNY 4,600 a tonne, amid restocking demand and renewed steel production controls in Tangshan city as industrial companies in China's steel hub were ordered to cut their production after an orange alert for heavy pollution was issued on January 3rd. Top steel producer China is expected to keep output restrictions in place to ensure smog-free skies as it hosts the 2022 Winter Olympic Games in February. On the demand side, low temperatures have been reducing construction activity in many parts of China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 14:25:40 </td>
   <td style="text-align:left;"> Australian Shares Fall as Tech Stocks Weigh </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index shed 0.08% to close at 7,447 on Monday, as Australian tech names remained under pressure from prospects of higher interest rates, while investors continued to monitor the Covid situation closely. High-growth technology stocks sold off globally at the start of the year amid strong hawkish signals from the US Federal Reserve, which indicated that it could tighten monetary policy more aggressively than anticipated. The biggest decliners in local tech names include Xero Ltd (-2.75%), Afterpay (-2.31%), Wisetech Global (-2.72%), Nextdc Ltd (-1.63%) and Seek Ltd (-0.68%). Healthcare, consumer and financial stocks also fell, while energy and mining firms mostly gained. Meanwhile, authorities in the country reinstated some restrictions to battle a record spike in Covid cases, with an official modeling indicating that the omicron outbreak in New South Wales could peak by the end of January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kazakhstan/services-pmi </td>
   <td style="text-align:left;"> 2022-01-10 14:23:03 </td>
   <td style="text-align:left;"> Kazakhstan Services Sector Returns to Growth </td>
   <td style="text-align:left;"> The Tengri Partners Kazakhstan Services PMI increased to 52.7.in December of 2021 from 48.7 in the previous month, signalling a rebound in the sector, as business activity rose strongly due to a fresh uplift in new work, amid reports of stronger client demand. Meanwhile, the rate of the job shedding eased to the softest since the current sequence of decline began in September and only marginal. On the price front, input prices increased due to a rise in prices of raw material and transport costs. Nonetheless, the rate of increase eased noticeably from November's peak, though it remained marked overall. Meanwhile, output cost inflation was largely unchanged. Looking ahead, business sentiment strengthened to a 6-month high on hopes that demand conditions would improve, and COVID-19 related issues subside in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 14:20:58 </td>
   <td style="text-align:left;"> New Zealand Stocks Fall on Broad Decline </td>
   <td style="text-align:left;"> The NZX 50 Index lost 0.6% to close at 12,893 on Monday, falling for a third straight session as stocks in New Zealand came under pressure from rising bond yields. The benchmark 10-year bond yield in New Zealand jumped to 2.54% on Monday, tracking a steady rise in US Treasury yields as traders braced for a more aggressive monetary tightening by the US Federal Reserve. Nearly all sectors of the market declined, with notable losses from Tourism Holdings (-4.55%), EBOS (-3.98%), Sky Network (-3.53%), Mercury NZ (-3.14%) and Serko (-2.99%), among others. Meanwhile, stocks that were able to resist the selloff include Sanford (2.67%), Restaurant Brands NZ (1.79%) and A2 Milk (1.56%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kazakhstan/composite-pmi </td>
   <td style="text-align:left;"> 2022-01-10 14:20:00 </td>
   <td style="text-align:left;"> Kazakhstan Private Sector Bounces Back </td>
   <td style="text-align:left;"> The Tengri Partners Kazakhstan Composite PMI increased to 51.6 in December 2021 from 49.1 in the prior month, signaling a fresh upturn in private sector activity that was moderate overall. At the sector level, the first fall in factory production since August was counteracted by a return to growth in services. New orders expanded marginally following a slight dip in November, while employment fell at the softest rate in four months. Turning to prices, inflationary pressures remained severe by historical standards. Input prices rose further, but the rate of inflation eased significantly from November's peak. As a result, average charges went up the least since September. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/saudi-arabia/industrial-production </td>
   <td style="text-align:left;"> 2022-01-10 14:08:37 </td>
   <td style="text-align:left;"> Saudi Industrial Output Growth Strongest in 5 Months </td>
   <td style="text-align:left;"> Industrial production in Saudi Arabia expanded by 10.3 percent year-on-year in November 2021, accelerating sharply from a 7.7 percent rise in the previous month. It was the fastest rate in industrial production since June, as production grew faster for mining and quarrying (10.4 percent vs 9.1 percent in October), manufacturing (9.7 percent vs 4.0 percent), and electricity and gas supply (11.9 percent vs 4.7 percent). On a seasonally adjusted monthly basis, industrial output rose by 2.0 percent in November, following a 1.7 percent gain in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 14:02:00 </td>
   <td style="text-align:left;"> Indian Shares Climb on Auto, Banking Boost </td>
   <td style="text-align:left;"> The BSE Sensex and Nifty 50 indices each rose about 0.8% on Monday, extending gains to a second session as auto and bank stocks provided a boost, while investors remained on edge amid rising Covid cases. The market moves came after three weeks of strong gains from both averages as investors in Indian equities shrugged off prospects of higher global interest rates. Early market leaders include Tata Motors (2.3%), Maruti Suzuki (3.4%), Icici Bank (1.2%), State Bank of India (1.1%) and Kotak Mahindra Bank (1.6%). Technology firms also advanced, with sharp gains from Infosys (2.6%), KPIT Technologies (4.3%) and Tech Mahindra (1%). Meanwhile, India recorded 179,723 fresh Covid cases, with the fast-spreading omicron variant fuelling an almost eight-fold rise in daily infections since the start of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-01-10 13:44:46 </td>
   <td style="text-align:left;"> Dollar Steadies as Traders Eye Inflation Data </td>
   <td style="text-align:left;"> The dollar index steadied near the 96 level on Monday, as traders await December US inflation data due later this week to guide the outlook for monetary policy. Markets also expect further hawkish commentary from Federal Reserve chair Jerome Powell as he testifies before the Senate this week, along with governor Lael Brainard, regarding their nominations. Meanwhile, the index dropped half a percent in the previous session as the December jobs report missed expectations. However, the case for monetary tightening remained intact following hawkish minutes from the Fed’s December meeting, which indicated the central bank could reduce its balance sheet in addition to hiking interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/netherlands/manufacturing-production </td>
   <td style="text-align:left;"> 2022-01-10 13:39:00 </td>
   <td style="text-align:left;"> Dutch Manufacturing Output Growth Accelerates in November </td>
   <td style="text-align:left;"> The average daily output generated by the Dutch manufacturing industry grew by 10.6 percent year-on-year in November 2021, accelerating from a 9.9 percent rise in October. It was the ninth straight month of expansion in manufacturing output, as production expanded faster for machinery (58.7 percent vs 57.2 percent in October), metal products (7.9 percent vs 5.6 percent), rubber and plastic (3.8 percent vs 0.3 percent), food (3.2 percent vs 0.9 percent), and electrical industry (11.3 percent vs 10.5 percent). Meanwhile, output contracted further for transport equipment (-4.6 percent vs -15.7 percent) and repair and installation of machinery (-13.6 percent vs -0.5 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-01-10 13:08:16 </td>
   <td style="text-align:left;"> Gold Hovers Near 3-Week Low </td>
   <td style="text-align:left;"> Gold hovered near 3-week lows below $1,800 on Monday, weighed down by firmer bond yields as traders braced for a more aggressive monetary tightening by the Federal Reserve in a bid to tame high inflation. US Treasury yields topped 1.8% last week following hawkish minutes from the Fed’s December meeting. It revealed the central bank discussed reducing its balance sheet in another move to aggressively dial back pandemic-era stimulus, after previously signaling three interest rate hikes this year.  Although investors view gold as a hedge against inflation, higher interest rates raise the opportunity cost of holding non-yielding bullion. Meanwhile, traders await December US inflation data that could reinforce the Fed’s hawkish stance after weaker jobs data. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/10/politics/joe-biden-voting-rights-democracy-russia-diplomacy/index.html </td>
   <td style="text-align:left;"> 2022-01-10 13:00:59 </td>
   <td style="text-align:left;"> Analysis: Joe Biden confronts challenges to democracy at home and abroad this week - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)President Joe Biden's fresh vow to save democracy faces an immediate test at home and abroad this week, with a long-shot voting rights push and the most critical US diplomacy with Russia since the Cold War.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , With his forceful speech on the anniversary of the January 6 insurrection last week, Biden appeared to engineer a political pivot, putting his credibility on the line to pass new laws rolling back Republican state voter suppression bills and restoring minority voting rights. He will travel to Atlanta, a city synonymous with the civil rights movement, on Tuesday, to try to dislodge the "dagger" he suggested ex-President Donald Trump and his Republican Party are holding "at the throat of our democracy." But to be successful, Biden must find a way to overcome the roadblock that has so far also derailed his social spending and climate agenda -- opposition to amending Senate filibuster rules among moderate Democrats including Sens. Joe Manchin and Kyrsten Sinema.                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Biden's administration is also locked in consequential work overseas, with a flurry of talks with Russia amid US warnings that President Vladimir Putin may be poised to invade a young democracy -- Ukraine. The Kremlin is using its former satellite state as a pawn in a gambit aimed at driving NATO out of Eastern European democracies that were once within its Cold War orbit. US efforts to convince Russia to stand down will have huge implications for the geopolitical situation in Europe. And Biden's tussle for influence with Putin is all the more ironic since the Russian leader is not only threatening democracy across the Atlantic. He is accused by US intelligence of interfering in US elections to help Trump, the ex-President who eventually sought to deny the will of voters in 2020 by attempting a coup and who often genuflected toward the Russian leader.                                                                                                                                                             , The talks in Europe, and Biden's capacity to unlock the voting rights puzzle in Washington, will be a marker of his presidential clout as he tries to bounce back after a rough political patch. The stakes of the voting rights initiative is huge, testing Democrats' ability to protect access to the franchise, especially for minority voters, which is under threat from GOP-led legislatures inspired by Trump's lies. And the two-front administration push will go a long way toward deciding the outcome in the US and internationally of a presidency Biden has dedicated to safeguarding the global democracy that he says is under mortal threat.                                                                                                                                                                                                                                                                                                                                                                                              , A full bore push for voting rights                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Voting rights has often seemed less of a priority than other Biden agenda items in a first year in power dominated by the pandemic and ambitious spending proposals, including the bipartisan infrastructure law that passed and the stalled social safety net bill.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , But both Biden and Vice President Kamala Harris will travel to Atlanta to build support for the Freedom to Vote Act and the John Lewis Voting Rights Advancement Act. The first bill would make Election Day a public holiday, mandate same-day voter registration and allow all voters to request mail-in ballots, among other provisions. It would also reverse partisan takeovers of election administration contained in some recent GOP legislation in the states. The latter bill would restore federal government oversight of state voting laws gutted by the Supreme Court in a 2013 decision. Since Republicans universally oppose the Freedom to Vote Act and only one of their senators, Alaska's Lisa Murkowski, backs the measure named for civil rights hero and late Democratic Rep. John Lewis, Democrats must get around Republican use of the filibuster that requires a supermajority of 60 votes to pass most major legislation. But Manchin of West Virginia and Sinema of Arizona have been reluctant to water down filibuster rules., Many Democrats are pleading with them to relent, arguing that a cascade of voter suppression laws passed by Republican-run states represents an existential threat to free and fair elections that can only be reversed by federal action in what may be the waning months of Democratic power before midterm elections in November.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Senate Majority Leader Chuck Schumer, a New York Democrat, has vowed to hold a vote by Martin Luther King Jr. Day -- a week from Monday -- if Republicans do not yield. Supporters of the legislation are pushing for a limited filibuster opt-out for a voting rights overhaul and are trying to get Manchin on board -- especially given that he wrote the Freedom to Vote Act himself, after Republicans balked at an earlier bill that contained more sweeping reforms.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , "He pulled it together and they're still refusing to support it, so he has all the cover he needs to now step away and do what we need done, and that is provide the 49th vote and I hope that the 50th vote will come along," House Majority Whip James Clyburn said on CNN's "Newsroom" on Saturday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Speaking to Fox's Bret Baier on Sunday, the South Carolina Democrat increased the pressure on Manchin. He said he agreed with Massachusetts Democratic Sen. Elizabeth Warren that the Senate filibuster had "deep roots in racism" and should not be allowed to cement a veto for the minority.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Manchin last week dealt a blow to the hopes of voting reform advocates like Clyburn, a key figure in rescuing Biden's then-languishing presidential campaign in early 2020 and an important ambassador to Black voters.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , "I've always been for rules being done the way we've always done, two-thirds of the members voting," Manchin indicated to CNN's Jake Tapper. He warned that getting rid of the filibuster would hurt Democrats if Republicans win back control of the Senate. "The reason I say it's a heavy lift is once you change a rule or you have a carve out -- I've always said this -- anytime there's a carve out, you eat the whole turkey. There's nothing left because it comes back and forth," he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , But House Speaker Nancy Pelosi on Sunday poured more pressure on recalcitrant senators from her party, describing Republican state voting laws, which in many cases make it harder to cast ballots and easier for politicians to interfere in elections, as a "very major threat on our democracy."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , "They are not only suppressing the vote ... they are nullifying elections," the California Democrat said on CBS's "Face the Nation."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Republicans like Senate Minority Leader Mitch McConnell accuse Democrats of threatening the right of states to run their own elections. Many of the new state laws, however, are justified on the grounds of "election integrity" -- a code word rooted in Trump's lies about voter fraud in the 2020 presidential vote that have been disproved multiple times.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Russia and China think 'democracy's days are numbered'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , During his January 6 anniversary speech in Statuary Hall in the Capitol on Thursday, Biden warned that foreign enemies were watching to see whether the United States safeguarded its own democracy under an unprecedented threat in modern times.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , "From China to Russia and beyond, they're betting that democracy's days are numbered," Biden said. "They're betting America's a place for the autocrat, the dictator, the strongman."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Two of the most dangerous US foreign policy challenges involve two democracies -- Taiwan and Ukraine -- pinning their hopes of survival on American support as they exist under threat from much more powerful and proprietorial autocracies, China and Russia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Biden has personally warned Putin at several virtual summits of devastating sanctions if he orders tens of thousands of Russia troops into Ukraine to follow up on the Russian annexation of Crimea in 2014. US officials will give the same message this week in talks that began on Sunday with a working dinner between Deputy Secretary of State Wendy Sherman and Russian Deputy Foreign Minister Sergei Ryabkov in Geneva. The talks will resume on Monday. Two days later, the NATO-Russia Council will convene in Brussels. The Vienna-based Organization for Security and Cooperation in Europe, which includes both Russia and the United States, meets on Thursday.                                                                                                                                                                                                                                                                                                                                                                              , But there is little hope of progress. The United States argues that Russia is demanding concessions that would permanently weaken NATO in Europe with its calls for the withdrawal of troops and weapons from ex-Warsaw Pact nations. Moscow also wants assurances that Ukraine -- a former Soviet state -- will never be allowed to join the alliance.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , "It's hard to see making actual progress, as opposed to talking, in an atmosphere of escalation with a gun to Ukraine's head," US Secretary of State Antony Blinken told Tapper on "State of the Union" on Sunday. Ryabkov was equally downbeat, saying he was "disappointed" by signals from Washington and Brussels. "In short, they reflect a lack of understanding of what we need," he said before laying out a wish list the West will never accept. "We need legal guarantees, legal guarantees that NATO will not expand further, eliminate everything that the alliance has created, driven by anti-Russian phobias and all sorts of false ideas about what is the essence of Russian policy for the period since 1997."                                                                                                                                                                                                                                                                                                                           , His warning was chillingly resonant of late 20th century clashes between two ideologically opposed superpowers. While talk of a second Cold War now often refers to a building American clash with China rather than Russia, there is one big difference between the period between the end of World War II and the fall of the Berlin Wall.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Back then, the challenge to America democracy came mostly from abroad. Now, it is under siege at home.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-10 12:31:00 </td>
   <td style="text-align:left;"> India 10Y Bond Yield Hits 23-month High </td>
   <td style="text-align:left;"> India 10 Year Government Bond Yield increased to a 23-month high of 6.551%, tracking a rally in US treasury yields after FOMC minutes showed the Fed might hike interest rates sooner than anticipated to cool inflation. Meanwhile, the Reserve Bank of India kept the interest rate at a record low of 4% and pledged to maintain an accommodative stance to support economic recovery from the pandemic-induced slump, which further weighed on the domestic bond market. At the same time, the Omicron strain of the coronavirus continues to spread rapidly in the country, prompting several state governments to impose fresh restrictions. Last year, the yield rose by 0.56% amid pandemic after falling by 0.66% in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malaysia/industrial-production </td>
   <td style="text-align:left;"> 2022-01-10 12:11:00 </td>
   <td style="text-align:left;"> Malaysia Industrial Output Growth Strongest in 6 Months </td>
   <td style="text-align:left;"> Industrial production in Malaysia jumped by 9.4 percent year-on-year in November 2021, accelerating sharply from a 5.5 percent rise in the previous month and easily beating market forecasts of 7.3 percent. This was the third straight month of increase in industrial output and the strongest pace since May, amid a further relaxation in COVID-19 restrictions and an upturn in the vaccination rate. Manufacturing output growth accelerated (11.3 percent vs 8.0 percent in October), buoyed by electrical &amp; electronics products (17.8 percent), food, beverages and tobacco (12.9 percent), and petroleum, chemical, rubber &amp; plastics (8.5 percent). Also, electricity production grew faster (5.1 percent vs 4.1 percent). In addition, mining activity rebounded strongly (3.7 percent vs -3.5 percent), due to a 10.2 percent increase in the natural gas index. On a monthly basis, industrial output expanded 0.9 percent, rising for the fourth month running. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malaysia/unemployment-rate </td>
   <td style="text-align:left;"> 2022-01-10 12:05:00 </td>
   <td style="text-align:left;"> Malaysia Jobless Rate Down to 4.3% in November </td>
   <td style="text-align:left;"> The unemployment rate in Malaysia declined to 4.3 percent in November 2021 from 4.8 percent in the same month a year earlier, as the economy recovered from the coronavirus disruptions. The number of unemployed dropped 9.2 percent from a year earlier to 694.4 thousand, while employment increased 2.7 percent to 15.61 million. Meantime, the labor force gained 2.2 percent to 16.30 million. In October 2021, the jobless rate was also at 4.3 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-01-10 11:12:29 </td>
   <td style="text-align:left;"> Brent Stabilizes as Supply Returns </td>
   <td style="text-align:left;"> Brent crude futures steadied near $82 per barrel on Monday after a strong rally last week, as supplies returned in Libya and Kazakhstan. Libyan production rose to 900,000 barrels a day after maintenance in a major pipeline was completed, while some output was restored in Kazakhstan following unrest that interrupted supplies last week. Elsewhere, China began a city-wide testing campaign in the port city of Tianjin after 20 people tested positive, raising demand concerns in the world’s biggest oil importer as the country maintains its zero-tolerance approach to Covid. Meanwhile, oil prices have pushed higher at the start of 2022 amid optimism about global demand coupled with supply constraints. While OPEC+ agreed to boost output further, analysts suggest the group may not be able to deliver the planned amount in full. Declining US crude inventories also buoyed oil prices, with EIA reporting six straight weekly draws. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/indonesia/consumer-confidence </td>
   <td style="text-align:left;"> 2022-01-10 11:12:00 </td>
   <td style="text-align:left;"> Indonesia Consumer Morale Little-Changed </td>
   <td style="text-align:left;"> Indonesia's consumer confidence index inched down 0.2 points to 118.3 in December from 118.5 in the previous month, as three of out the six main sub-indices weakened: economic outlook (down 1.0 points to 136.8); income expectations for the next six months (down 0.4 points to 137.5); and job availability expectations (down 1.2 points to 133.7). Meanwhile, sub-indices improved for current economic conditions (up 0.7 points to 99.9); the assessment of current income (up 1.3 points to 109.6); job availability compared to six months ago (up 1.8 points to 98.1). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-10 11:09:00 </td>
   <td style="text-align:left;"> Oil Steadies as Supply Concerns Ease </td>
   <td style="text-align:left;"> WTI crude futures steadied near $79 per barrel on Monday after a strong rally last week, as supplies returned in Libya and Kazakhstan. Libyan production rose to 900,000 barrels a day after maintenance in a major pipeline was completed, while some output was restored in Kazakhstan following unrest that interrupted supplies last week. Elsewhere, China began a city-wide testing campaign in the port city of Tianjin after 20 people tested positive, raising demand concerns in the world’s biggest oil importer as the country maintains its zero-tolerance approach to Covid. Meanwhile, oil prices have pushed higher at the start of 2022 amid optimism about global demand coupled with supply constraints. While OPEC+ agreed to boost output further, analysts suggest the group may not be able to deliver the planned amount in full. Declining US crude inventories also buoyed oil prices, with EIA reporting six straight weekly draws. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/dollar-firm-as-inflation-test-looms </td>
   <td style="text-align:left;"> 2022-01-10 10:34:03 </td>
   <td style="text-align:left;"> Dollar firm as inflation test looms </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                  , SYDNEY - The dollar started the week with support as traders bet U.S. inflation data and appearances from several Federal Reserve officials would bolster the case for higher interest rates.                                                      , After dipping on Friday, the greenback stood around its 200-day moving average against the euro at $1.1357 in early Asia trade on Monday. It firmed slightly on the yen to 115.65, fairly close to last week's five-year high of 116.35 per dollar., Trade in the Asia session was thinned by a holiday in Japan.                                                                                                                                                                                       , HOW INFLATION WILL IMPACT YOUR 2022 TAXES                                                                                                                                                                                                          , Federal Reserve chair Jerome Powell and governor Lael Brainard testify before Senate committees this week regarding their nominations as chair and deputy chair at the Fed.                                                                        , U.S. inflation figures are due on Wednesday, with headline CPI seen climbing to a red-hot 7% year-on-year.                                                                                                                                         , The dollar started the week with support as traders bet U.S. inflation data and appearances from several Federal Reserve officials would bolster the case for higher interest rates. (iStock)                                                      , "The dollar index is likely to recoup some of its Friday losses this week on Powell's likely hawkish commentary and rising U.S. inflation," said Scotiabank FX strategist Qi Gao.                                                                  , Cryptocurrencies have faced pressure from broad selling in risk assets at the start of this year, but were steady in Asia after bitcoin managed to hold support at $40,000 through weekend trade.                                                  , Bitcoin last bought $41,784 and ether $3,145.                                                                                                                                                                                                      , Eventually, though, he added that the greenback would probably run out of steam, and the index head towards 94 once money markets fully price in a Fed hike in March.                                                                              , The dollar index last sat at 95.800.                                                                                                                                                                                                               , U.S.-Russia talks over rising tension in Ukraine also have traders on edge as the two sides seem far apart and failure risks an armed confrontation on Europe's doorstep.                                                                          , CLICK HERE TO GET FOX BUSINESS ON THE GO                                                                                                                                                                                                           , The Australian dollar was marginally weaker at $0.7179 early in the Asia session and has been held below resistance around $0.7190.                                                                                                                , The kiwi was steady at $0.6750.                                                                                                                                                                                                                    , The dollar had met with some selling late last week after a weaker-than-expected headline U.S. job-creation figure squeezed traders out of long dollar positions.                                                                                  , But analysts said better-than-expected unemployment numbers still made a good case for hikes sooner rather than later.                                                                                                                             , Fed funds futures have priced an almost 90% chance of a rate hike in March and a more than 90% chance of another one by June and U.S. yields have been surging higher.                                                                             , Sterling was also marginally weaker on the dollar but has been rallying with bets that the Bank of England (BOE) is likely to be hiking in tandem with the Fed.                                                                                    , It was last at $1.3590, near a two-month high, and close to last week's two-year peak on the euro . Strategists at MUFG reckon traders are too hawkish on their rates expectations in Britain but still think sterling will hold its own.          , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                            , "We still expect two rate hikes by the BOE which should keep EUR/GBP under modest downward pressure, which will result in GBP/USD advancing to around the 1.4000 level," they said in an outlook note published over the weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59932551?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-10 10:33:12 </td>
   <td style="text-align:left;"> Crisis-hit Sri Lanka asks China to restructure its debt </td>
   <td style="text-align:left;"> The president of crisis-hit Sri Lanka has asked China to restructure its debt repayments as part of efforts to help the South Asian country navigate its worsening financial situation.                                                                          , Gotabaya Rajapaksa made the request during a meeting with Chinese foreign minister Wang Yi on Sunday.                                                                                                                                                            , In the last decade China has lent Sri Lanka over $5bn (£3.7bn) for projects including roads, an airport and ports.                                                                                                                                               , But critics say the money was used for unnecessary schemes with low returns.                                                                                                                                                                                     , "The president pointed out that it would be a great relief to the country if attention could be paid on restructuring the debt repayments as a solution to the economic crisis that has arisen in the face of the Covid-19 pandemic," Mr Rajapaksa's office said., The statement also said China was asked to provide "concessional" terms for its exports to Sri Lanka, which amounted to around $3.5bn last year, without providing further details.                                                                              , Mr Rajapaksa also offered to allow Chinese tourists to return to Sri Lanka provided they adhere to strict coronavirus regulations.                                                                                                                               , Before the pandemic China was Sri Lanka's main source of tourists and it imports more goods from China than from any other country.                                                                                                                              , In recent months, Sri Lanka has been experiencing a severe debt and foreign exchange crisis, which has been made worse by the loss of tourist income during the pandemic.                                                                                        , China is Sri Lanka's fourth biggest lender, behind international financial markets, the Asian Development Bank and Japan.                                                                                                                                        , The country has received billions of dollars of soft loans from China but the island nation has been engulfed in a foreign exchange crisis which some analysts have said has pushed it to the verge of default.                                                  , Sri Lanka has to repay about $4.5bn in debt this year starting with a $500m international sovereign bond, which matures on 18 January.                                                                                                                           , The country's central bank has repeatedly assured investors that all of its debt repayments will be met and said funds for this month's bond repayment has already been allocated.                                                                               , Sri Lanka is a key part of China's Belt and Road Initiative, a long-term plan to fund and build infrastructure linking China to the rest of the world.                                                                                                           , However, some countries, including the US, have labelled the project a "debt trap" for smaller and poorer nations.                                                                                                                                               , Beijing has always rejected those accusations, and in response has accused some in the West of promoting this narrative to tarnish its image.                                                                                                                    , Last month a Sri Lankan government minister said the country planned to settle a debt for past oil imports from Iran by paying it off in tea.                                                                                                                    , It plans to send $5m worth of tea to Iran each month to clear a $251m debt.                                                                                                                                                                                      , In September, Sri Lanka declared an economic emergency, after a steep fall in the value of its currency, the rupee, caused a spike in food prices.                                                                                                               , Authorities said they would take control of the supply of basic food items, including rice and sugar, and set prices in an attempt to control rising inflation.                                                                                                  , This video can not be played                                                                                                                                                                                                                                     , Russell Kane and guests consider the life of the iconic musician                                                                                                                                                                                                 , Featuring music from The Wild Bunch and more                                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 10:24:58 </td>
   <td style="text-align:left;"> China Stocks Pressured by Zero-Covid Approach </td>
   <td style="text-align:left;"> The Shanghai Composite fell 0.1% while the Shenzhen Component rose 0.15% early on Monday, with losses in consumer, transportation and industrial stocks offsetting gains in technology and healthcare firms, as mainland stocks remained under pressure from the country’s zero-tolerance Covid strategy in the run-up to the Lunar New Year and WInter Olympics. Authorities in the Chinese port city of TIanjin said they began a city-wide testing campaign of its 14 million residents after a cluster of 20 children and adults tested positive for Covid, including two with the omicron variant. China’s approach of responding to small numbers of cases with mass testing and tight lockdowns contrasted with other countries, which have opened up following vaccination campaigns. The market laggards include Cosco Shipping (-4%), Power Construction (-3.9%) and China Tourism (-4.1%), while some gainers were Andon Health (3.9%), Shijiazhuang Yilin (4.5%) and China Greatwall (8.5%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/09/opinions/canadians-fear-us-democracy-collapse-obeidallah/index.html </td>
   <td style="text-align:left;"> 2022-01-10 09:48:44 </td>
   <td style="text-align:left;"> Opinion: Even Canadians fear US democracy could end soon - CNN </td>
   <td style="text-align:left;"> Dean Obeidallah, a former attorney, is the host of SiriusXM radio's daily program "The Dean Obeidallah Show" and a columnist for The Daily Beast. Follow him @DeanObeidallah. The opinions expressed in this commentary are his own. View more opinion articles on CNN. This piece has been updated to reflect the latest news.                                                                                                                                                                                                                                                                                                                                                                                                             ,  (CNN)"The United States is coming to an end. The question is how." Those are the jarring opening lines of Canadian author Stephen Marche's new book, "The Next Civil War: Dispatches from the American Future." Released the same week as the anniversary of the January 6 attack on our Capitol that signaled how dangerous our political polarization has become, Marche's book shares different scenarios of how the United States could collapse.                                                                                                                                                                                                                                                                                      , Marche isn't the only Canadian worried about their southern neighbor's future. Just days before Marche's book released, political scientist Thomas Homer-Dixon -- the executive director of the Cascade Institute, which focuses on ways to address threats to society -- penned a powerful op-ed in Canada's "Globe and Mail" that begins with a similar warning. "By 2025, American democracy could collapse, causing extreme domestic political instability, including widespread civil violence," Homer-Dixon writes. "By 2030, if not sooner," he adds, "the country could be governed by a right-wing dictatorship."                                                                                                                  , As Americans, our first instinct when a person from outside of the US says something critical of our nation is often to dismiss the comment (or mock their country; be honest!). In this case, though, neither Marche nor Homer-Dixon wrote their words to belittle America or to make Canadians feel better about their country.                                                                                                                                                                                                                                                                                                                                                                                                           , In fact, as Marche explained on my SiriusXM radio show last week, it's the opposite: Marche wrote his book because he "loves" the US after working and living within its borders off and on for years. His hope, he says, is to warn Americans of where the nation is going before it's too late.                                                                                                                                                                                                                                                                                                                                                                                                                                           , In the case of Homer-Dixon, the warning is even more unnerving because the column is addressed not to Americans but to his fellow Canadians, to prepare them for what may be heading their way if America's democracy does collapse. Homer-Dixon bluntly cautions his compatriots: "A terrible storm is coming from the south, and Canada is woefully unprepared."                                                                                                                                                                                                                                                                                                                                                                          , When Canadians start to counsel one another on the threat posed to American democracy, you know we're in a dire position. This is not about scoring political points; rather, it emanates from a place of sincere concern for their own nation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , It's a sobering reminder that if our democratic republic ends it will have repercussions not just for our nation but the world -- from bolstering autocratic leaders, such as the type that former President Donald Trump had praised, to undermining Western democracies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Homer-Dixon's words carry real weight: As he says, for more than 40 years he's studied the causes of war, revolution and social breakdown. "Today," he wrote to his countrymen and women, "as I watch the unfolding crisis in the United States, I see a political and social landscape flashing with warning signals."                                                                                                                                                                                                                                                                                                                                                                                                                     , To those who might view his premonitions as over the top, Homer-Dixon adds, "We mustn't dismiss these possibilities just because they seem ludicrous or too horrible to imagine. In 2014, the suggestion that Donald Trump would become president would also have struck nearly everyone as absurd." (Point taken with that one!)                                                                                                                                                                                                                                                                                                                                                                                                           , This scholar of violent conflict highlights the range of factors currently plaguing the US and contributing to our institutions' vulnerability, from growing income inequality to demographic change that has caused some "right-wing ideologues" to inflame "fears that traditional US culture is being erased and Whites are being 'replaced." (Fox News' Tucker Carlson has long been peddling this "replacement theory" -- although he's denied that's what he's doing -- and he's been rightfully denounced. And at least one other GOP elected official, Rep. Matt Gaetz, has joined him, claiming Democrats are "importing new voters" from other countries. As with Carlson, Gaetz insisted his views had nothing to do with race.) , Homer-Dixon even believes that using the "F word" -- fascism -- to describe the state of the GOP is accurate, citing the perspective of Canadian-American conservative David Frum: "Trumpism increasingly resembles European fascism in its contempt for the rule of law and glorification of violence." I couldn't agree more.                                                                                                                                                                                                                                                                                                                                                                                                             , But what truly resonates with me is Homer-Dixon's assessment that the "underpinning" of our politics "is a vital set of beliefs and values," and "if a substantial enough fraction of a population no longer holds those beliefs and values, then democracy can't survive."                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Alarmingly, a recent NPR/Ipsos poll found that two-thirds of Republicans agree with the demonstrably false statement that "voter fraud helped Joe Biden win the 2020 election." Fewer than half of Republicans, the poll found, agree that they are willing to accept the election's proven results.                                                                                                                                                                                                                                                                                                                                                                                                                                        , How can we have a functioning democratic republic when one side apparently believes that only elections they win are "legitimate"? The fact so many Republicans reject the results of the 2020 election was likely part of the motivation behind this memorable line in President Joe Biden's speech one year following the January 6 attack: "You can't love your country only when you win."                                                                                                                                                                                                                                                                                                                                              , For Homer-Dixon, all of this adds up to a crucial question for his country: How can Canadians prepare for the worst? For one, he says, "We need to start by fully recognizing the magnitude of the danger." He continues, "If Mr. Trump is re-elected" and ushers in a right-wing authoritarian regime, "The risks to our country in their cumulative effect could easily be existential, far greater than any in our federation's history."                                                                                                                                                                                                                                                                                                , For example, he theorizes, "What happens ... if high-profile political refugees fleeing persecution arrive in our country, and the U.S. regime demands them back. Do we comply?"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , To prepare for that kind of possible scenario, he implores Canada's prime minister, Justin Trudeau, to "immediately convene" a committee with representatives from the various political parties in government who "should receive regular intelligence analyses and briefings by Canadian experts on political and social developments in the United States and their implications for democratic failure there."                                                                                                                                                                                                                                                                                                                          , There's been a lot of talk lately by American leaders on the threat posed to our democracy by today's GOP. Former President Jimmy Carter wrote an op-ed for the New York Times titled, "I fear for our democracy," raising concerns that since the January 6 attack, "promoters of the lie that the election was stolen have taken over one political party and stoked distrust in our electoral systems."                                                                                                                                                                                                                                                                                                                                  , But there's something deeply compelling about reading the words of Canadians who have no skin in the game of American politics to offer such blunt words and warnings about the red flags they are seeing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , As Marche details in his book, there are Americans who hold a "desperate faith in their country's institutions that amounts nearly to delusion." These Canadians are warning us to break free of those delusions and instead understand that "it" can happen here -- with "it" being anything from fascism to a civil war that would collapse our democracy -- and to get a grasp on this reality before it's too late.                                                                                                                                                                                                                                                                                                                     , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/private-house-approvals- </td>
   <td style="text-align:left;"> 2022-01-10 09:04:00 </td>
   <td style="text-align:left;"> Australia Private House Approvals Ease </td>
   <td style="text-align:left;"> Private house approvals in Australia increased by 1.4 percent month-over-month to 10,892 units in November 2021, slowing from a 3.5 percent gain a month earlier, a preliminary figure showed.  The series has been at historically elevated levels over the past year, largely driven by government stimulus and record low-interest rates. "While private house approvals are no longer at record highs, the November result remains 25.8 percent higher than the pre-pandemic level in November 2019, indicating ongoing strength in the detached housing market," said Daniel Rossi, ABS Director of Construction Statistics.  Approvals rose in Queensland (7.4 percent), South Australia (6.4 percent), and New South Wales (5.4 percent), while falls were recorded in both Western Australia (-12.1 percent) and Victoria (-0.8 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/building-permits </td>
   <td style="text-align:left;"> 2022-01-10 08:53:04 </td>
   <td style="text-align:left;"> Australia Building Permits Rebound </td>
   <td style="text-align:left;"> The seasonally adjusted estimate for total dwellings approved in Australia rose by 3.6 percent month-over-month to 16,448 units in November 2021, swinging from a revised 13.6 percent slump a month earlier, flash data showed. This marked the first rise in building permits since August, driven by an increase in approvals for private sector dwellings excluding houses, which rose 9.7 percent following a 37.9 percent slump in October. Meanwhile, private sector houses continued to level off (1.4 percent vs 3.5 percent) after being at historically elevated levels over the past year due to government stimulus and record low-interest rates. Across Australia, dwelling approvals rose in Tasmania (40.8 percent), Queensland (20 percent), South Australia (14.5 percent), and Victoria (8.9 percent). In contrast, building permits fell in both New South Wales (-18.4 percent) and Western Australia (-1.1 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 08:45:00 </td>
   <td style="text-align:left;"> US Futures Mixed After a Losing Week </td>
   <td style="text-align:left;"> US stock futures were mixed on Monday after a losing week for the three major averages, as investors grappled with prospects of higher interest rates. Dow futures fell 0.1%, while S&amp;P 500 and Nasdaq 100 futures rose 0.1% and 0.3%, respectively. The Nasdaq led the declines last week after falling 4.53%, as investors rotated out of high-growth names into value and cyclical stocks. The S&amp;P 500 followed with a 1.87% weekly loss and the Dow shed 0.29%. Technology, healthcare and communication services stocks dropped the most, while energy and financial names gained. Equities came under pressure last week as the 10-year Treasury yield topped 1.8% following the release of the Fed’s December meeting minutes which indicated that the central bank could tighten monetary policy more aggressively than anticipated. The central bank is planning to reduce its balance sheet  in addition to hiking rates. Meanwhile, investors await key inflation and a slew of Q4 earnings reports in the week ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/media/2022/01/09/tucker-carlson-coronavirus-treatment-fox-reiner-acostanr-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-10 08:12:08 </td>
   <td style="text-align:left;"> Hear doctor's challenge for Tucker Carlson - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59930934?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-10 08:02:33 </td>
   <td style="text-align:left;"> Virgin and O2 users will not face EU roaming charges </td>
   <td style="text-align:left;"> Virgin Media O2 phone users will not face roaming charges following announcements by other networks to reintroduce extra fees after Brexit.                                                                                                     , It means customers travelling to Europe will be able to use their mobile data and make calls and texts on the same deal as they have in the UK.                                                                                                 , Vodafone, EE and Three are set to reintroduce roaming fees this year for customers travelling to Europe.                                                                                                                                        , Consumer champion Which? urged the UK and EU to "strike a deal" on charges.                                                                                                                                                                     , Before the UK left the EU, users were able to use their calls, texts, and data allowance in their mobile plans in any EU country after the bloc removed roaming charges in 2017.                                                                , However, the EU trade deal of December 2020 gave mobile operators the option of reintroducing charges.                                                                                                                                          , Virgin Media O2 said a family of four going abroad for two weeks could see an extra £100 on their bill, based on analysis of rates from other providers.                                                                                        , "We're starting the year by giving our customers some certainty: we will not be reintroducing roaming fees in Europe for customers on O2 or Virgin Mobile," said Gareth Turpin, chief commercial officer.                                       , "With many Brits now looking to plan a trip abroad, we've got our customers covered and extra roaming charges will be one less thing to worry about."                                                                                           , Vodafone plans to bring back roaming charges at the end of January, while EE is set to in March. Both networks delayed reintroducing the charges earlier due to testing and technical issues respectively.                                      , Meanwhile, Three is to introduce fees in May.                                                                                                                                                                                                   , Customers who joined or upgraded with EE after 7 July 7 2021 face a £2 daily roaming charge in EU countries, while Vodafone will charge the same fee for people who joined the network after 11 August 11 or upgraded or renewed their contract., However, both companies will offer deals to avoid the fee, with EE customers able to buy a 30-day roaming pass for £10 and Vodafone users able to pay £1 a day for an eight or 15-day pass.                                                     , Three will bring in the £2 daily charge for people who joined or upgraded after 1 October 2021.                                                                                                                                                 , Sue Davies, head of consumer protection policy at Which?, said it was "reassuring" that Virgin Media O2 had offered some certainty to customers.                                                                                                , "As the UK continues to negotiate trade deals, it should take the opportunity to lower the cost of roaming for consumers travelling around the world," she added.                                                                               , "The UK and EU should also work to strike a deal on roaming charges to stop companies chipping away at the roaming benefits customers have become used to and to ensure the high charges people used to face do not return."                    , In April last year, a £31bn merger between Virgin Media and O2 was approved, making it one of the the UK's largest entertainment and telecoms firms.                                                                                            , Russell Kane and guests consider the life of the iconic musician                                                                                                                                                                                , Featuring music from The Wild Bunch and more                                                                                                                                                                                                    , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59917640?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-10 08:00:32 </td>
   <td style="text-align:left;"> Energy bills: Fix insulation to tackle cost of heating, PM told </td>
   <td style="text-align:left;"> Better insulation could save UK households more than £500 a year on energy bills, according to a group of business organisations and charities.                                                                                                                                                      , The Energy Efficiency Infrastructure Group is calling on the prime minister to prioritise energy saving through home improvements.                                                                                                                                                                   , It could save the UK £7.8bn a year, the group says.                                                                                                                                                                                                                                                  , The government is under political pressure to take action over rocketing gas bills.                                                                                                                                                                                                                  , Households have seen energy bills rise in recent months and further increases will take effect in April, when the energy price cap will be raised to take higher wholesale gas prices into account.                                                                                                  , The government is exploring ways to support those on low incomes who will struggle to afford higher heating costs.                                                                                                                                                                                   , But the EEIG, which includes the CBI, Kingfisher, Energy Savings Trust and the green group WWF, says this and previous administrations are partly to blame for higher bills because they failed to ensure Britain's homes are adequately insulated.                                                  , "The cost-of-living crisis is being driven by soaring gas prices," said EEIG chairwoman Sarah Kostense-Winterton. "A permanent solution to lower bills is by reducing demand through energy efficiency measures.                                                                                     , "Emergency short-term measures for the most vulnerable households are crucial, but it's fundamental for the government to simultaneously focus on the long term to avoid futures crises.                                                                                                             , "Green home retrofits have significant social, environmental and economic co-benefits, and stand out as a 'no regrets' solution to the energy crisis, climate crisis, and levelling up agenda."                                                                                                      , Britain has the coldest and leakiest housing stock in western Europe, leaving residents particularly exposed to spikes in gas prices.                                                                                                                                                                , Successive governments have failed to implement policies to tackle the problem. The most recent insulation scheme, the Green Homes Grant, was scrapped after just six months.                                                                                                                        , The chancellor was urged by backbench MPs to use last autumn's Budget to introduce a multi-year energy efficiency programme, but he declined.                                                                                                                                                        , In the short term the EEIG wants the government to provide additional support for vulnerable households to prevent a fuel poverty emergency.                                                                                                                                                         , This would include expanding the Warm Homes Discount, an option the government is discussing.                                                                                                                                                                                                        , But the EEIG insists that ministers must also bolster the Energy Company Obligation (ECO) which requires energy suppliers to help low-income households to fit energy-saving measures.                                                                                                               , The group fears that the chancellor may suspend the long-term ECO funding and shift the cash to tackle the immediate bills problem instead.                                                                                                                                                          , The EEIG is warning that cutting ECO would be damaging for households and industry, and would stall progress in making fuel-poor homes more energy efficient, risking green jobs and keeping households hooked on expensive gas.                                                                     , In his manifesto Boris Johnson promised £9bn for energy efficiency up to 2030.                                                                                                                                                                                                                       , About £6bn was allocated to be spent this parliament but the EEIG says money not allocated amounts to a broken promise.                                                                                                                                                                              , The EEIG is also calling for a new £3.6bn grant or subsidy scheme to help all households, including private owners, to insulate their homes.                                                                                                                                                         , At the moment, the EEIG maintains, two-thirds of households have no financial support for insulation, even though insulation is a vital part of the strategy to cut carbon emissions.                                                                                                                , The insulation call was backed at the weekend by MPs on the Conservative Environment Network.                                                                                                                                                                                                        , A government spokesman said it had already made huge progress in upgrading the energy efficiency of England's homes - from 9% rated grade C in 2008, to 40% today.                                                                                                                                   , He said all new heating systems installed in UK homes from 2035 will be low-carbon technologies, like heat pumps or hydrogen-ready boilers. This will be a gradual, 14-year transition, and to cut the cost of heat pump, we're offering grants to households worth £5,000.                          , He added: "Improving energy efficiency is the best long term solution to tackling fuel poverty, which is why we are supporting households across the UK to improve their energy performance and reduce bills, having already invested £1.3bn this year alone to upgrade up to 50,000 homes.          , "The Energy Price Cap will remain in place, shielding millions of customers from rising global gas prices, and we are continuing to support lower-income households through £4.2bn in support, including the Home Upgrade Grant, Energy Company Obligation and the new £500m Household Support Fund.", Follow Roger on Twitter @rharrabin                                                                                                                                                                                                                                                                   , Russell Kane and guests consider the life of the iconic musician                                                                                                                                                                                                                                     , Featuring music from The Wild Bunch and more                                                                                                                                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-01-10 08:00:04 </td>
   <td style="text-align:left;"> Natural gas Hits 5-week High </td>
   <td style="text-align:left;"> Natural gas increased to a 5-week high of 4.135 USD/MMBtu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/09/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-01-10 07:02:39 </td>
   <td style="text-align:left;"> Stock futures reverse losses after S&amp;P 500 posts 4-day losing streak </td>
   <td style="text-align:left;"> , Stock futures were mostly higher in overnight trading Sunday after a rocky start to 2022 for equity markets as interest rates rise.                                                                                                                                                            , Futures on the Dow Jones Industrial Average retraced most of their earlier losses and were down about 15 points, or 0.04%. S&amp;P 500 futures erased losses and rose 0.1% and Nasdaq 100 futures added 0.32%.                                                                                     , The three major stock averages all fell in the first week of the year. The S&amp;P 500 slid 0.4% on Friday for its first four-day losing streak since September. The Nasdaq Composite dropped 0.9%, also posting four straight losing days. The Dow Jones Industrial Average lost 4.81 points.     , Stocks, particularly high-growth names, have struggled as interest rates tick higher. The 10-year Treasury yield topped 1.8% on Friday, on a run after closing 2021 at the 1.51% level.                                                                                                        , "As we kick-started 2022 this week, trading attention fell on a definitive rotation into value and pro-cyclical stocks and out of growth as investors digested a sharply higher rate environment," Goldman Sachs' Chris Hussey said in a Friday note.                                          , The rising rates come as the Federal Reserve signaled it could dial back its easy monetary policy more aggressively than some expected. Minutes from the Fed's December meeting released Wednesday showed the central bank is planning to shrink its balance sheet in addition to hiking rates., Investors are awaiting key inflation reports in the week ahead. The consumer price index is set for release Wednesday and the producer price index is slated for Thursday.                                                                                                                     , Federal Chair Jerome Powell is scheduled to testify Tuesday at his nomination hearing before a Senate panel, while the hearing on Fed Governor Lael Brainard's nomination to the post of vice chair is set for Thursday.                                                                       , Delta Air Lines reports earnings Thursday and financial heavyweights JPMorgan Chase, Citigroup and Wells Fargo release quarterly results Friday.                                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/09/entertainment/golden-globes-winners-2022/index.html </td>
   <td style="text-align:left;"> 2022-01-10 06:20:23 </td>
   <td style="text-align:left;"> Golden Globe winners list 2022 - CNN </td>
   <td style="text-align:left;"> (CNN)On a typical year, the Golden Globe Awards serve as the gold standard for tipsy fun. But this is not a typical year for Hollywood's quirkiest award show.                                                , Still, even as the Globes serve a time out as The Hollywood Foreign Press Association works to repair its reputation, there is no break being taken from recognizing the best films and television of the year., In a toned down, untelevised presentation, the winners of the Golden Globes were announced Sunday night.                                                                                                       , A full list of nominees follows below with winners indicated in bold.                                                                                                                                          , Television                                                                                                                                                                                                     , Best Performance by an Actor in a Television Series -- Musical or Comedy                                                                                                                                       , Anthony Anderson, "Black-ish"                                                                                                                                                                                  , Nicholas Hoult, "The Great"                                                                                                                                                                                    , Steve Martin, "Only Murders in the Building"                                                                                                                                                                   , Martin Short, "Only Murders in the Building"                                                                                                                                                                   , Jason Sudeikis, "Ted Lasso" *WINNER                                                                                                                                                                            ,                                                                                                                                                                                                                , Best Performance by an Actress in a Television Series -- Musical or Comedy                                                                                                                                     , Hannah Einbender, "Hacks"                                                                                                                                                                                      , Elle Fanning, "The Great"                                                                                                                                                                                      , Issa Rae, "Insecure"                                                                                                                                                                                           , Tracee Ellis Ross, "black-ish"                                                                                                                                                                                 , Jean Smart, "Hacks" *WINNER                                                                                                                                                                                    ,                                                                                                                                                                                                                , Best Performance by an Actor in a Television Series -- Drama                                                                                                                                                   , Brian Cox, "Succession"                                                                                                                                                                                        , Lee Jung-jae, "Squid Game"                                                                                                                                                                                     , Billy Porter, "Pose"                                                                                                                                                                                           , Jeremy Strong, "Succession" *WINNER                                                                                                                                                                            , Omar Sy, "Lupin"                                                                                                                                                                                               ,                                                                                                                                                                                                                , Best Performance by an Actress in a Television Series -- Drama                                                                                                                                                 , Uzo Aduba, "In Treatment"                                                                                                                                                                                      , Jennifer Aniston, "The Morning Show"                                                                                                                                                                           , Christine Baranski, "The Good Fight"                                                                                                                                                                           , Elisabeth Moss, "The Handmaid's Tale"                                                                                                                                                                          , Mj Rodriguez, "Pose" *WINNER                                                                                                                                                                                   ,                                                                                                                                                                                                                , Best Performance by an Actor in a Limited Series or Motion Picture Made for Television                                                                                                                         , Paul Bettany, "WandaVision"                                                                                                                                                                                    , Oscar Isaac, "Scenes From a Marriage"                                                                                                                                                                          , Michael Keaton, "Dopesick" *WINNER                                                                                                                                                                             , Ewan McGregor, "Halston"                                                                                                                                                                                       , Tahar Rahim, "The Serpent"                                                                                                                                                                                     ,                                                                                                                                                                                                                , Best Performance by an Actress in a Limited Series or Motion Picture Made for Television                                                                                                                       , Jessica Chastain, "Scenes From a Marriage"                                                                                                                                                                     , Cynthia Erivo, "Genius: Aretha"                                                                                                                                                                                , Elizabeth Olsen, "WandaVision"                                                                                                                                                                                 , Margaret Qualley, "Maid"                                                                                                                                                                                       , Kate Winslet, "Mare of Easttown" *WINNER                                                                                                                                                                       ,                                                                                                                                                                                                                , Best Television Series Drama                                                                                                                                                                                   , "Lupin"                                                                                                                                                                                                        , "The Morning Show"                                                                                                                                                                                             , "Pose"                                                                                                                                                                                                         , "Squid Game"                                                                                                                                                                                                   , "Succession" *WINNER                                                                                                                                                                                           ,                                                                                                                                                                                                                , Best Television Limited Series or Motion Picture Made for Television                                                                                                                                           , "Dopesick"                                                                                                                                                                                                     , "Impeachment: American Crime Story"                                                                                                                                                                            , "Maid"                                                                                                                                                                                                         , "Mare of Easttown"                                                                                                                                                                                             , "The Underground Railroad" *WINNER                                                                                                                                                                             ,                                                                                                                                                                                                                , Best Performance by an Actress in a Supporting Role in a Series, Limited Series or Motion Picture Made for Television                                                                                          , Jennifer Coolidge, "White Lotus"                                                                                                                                                                               , Kaitlyn Dever, "Dopesick"                                                                                                                                                                                      , Andie MacDowell, "Maid"                                                                                                                                                                                        , Sarah Snook, "Succession" *WINNER                                                                                                                                                                              , Hannah Waddingham, "Ted Lasso"                                                                                                                                                                                 ,                                                                                                                                                                                                                , Best Performance by an Actor in a Supporting Role in a Series, Limited Series or Motion Picture Made for Television                                                                                            , Billy Crudup, "The Morning Show"                                                                                                                                                                               , Kieran Culkin, "Succession"                                                                                                                                                                                    , Mark Duplass, "The Morning Show"                                                                                                                                                                               , Brett Goldstein, "Ted Lasso"                                                                                                                                                                                   , Oh Yeong-su, "Squid Game" *WINNER                                                                                                                                                                              ,                                                                                                                                                                                                                , Best Television Series -- Musical or Comedy                                                                                                                                                                    , "The Great"                                                                                                                                                                                                    , "Hacks" *WINNER                                                                                                                                                                                                , "Only Murders in the Building"                                                                                                                                                                                 , "Reservation Dogs"                                                                                                                                                                                             , "Ted Lasso"                                                                                                                                                                                                    ,                                                                                                                                                                                                                , FILM                                                                                                                                                                                                           , Best Motion Picture -- Musical or Comedy                                                                                                                                                                       , "Cyrano"                                                                                                                                                                                                       , "Don't Look Up"                                                                                                                                                                                                , "Licorice Pizza"                                                                                                                                                                                               , "Tick, Tick ... Boom!"                                                                                                                                                                                         , "West Side Story" *WINNER                                                                                                                                                                                      ,                                                                                                                                                                                                                , Best Motion Picture -- Drama                                                                                                                                                                                   , "Belfast,"                                                                                                                                                                                                     , "CODA"                                                                                                                                                                                                         , "Dune"                                                                                                                                                                                                         , "King Richard"                                                                                                                                                                                                 , "The Power of the Dog" *WINNER                                                                                                                                                                                 ,                                                                                                                                                                                                                , Best Motion Picture -- Foreign Language                                                                                                                                                                        , "Compartment No. 6"                                                                                                                                                                                            , "Drive My Car" *WINNER                                                                                                                                                                                         , "The Hand of God"                                                                                                                                                                                              , "A Hero"                                                                                                                                                                                                       , "Parallel Mothers"                                                                                                                                                                                             ,                                                                                                                                                                                                                , Best Screenplay -- Motion Picture                                                                                                                                                                              , Paul Thomas Anderson, "Licorice Pizza"                                                                                                                                                                         , Kenneth Branagh, "Belfast" *WINNER                                                                                                                                                                             , Jane Campion, "The Power of the Dog"                                                                                                                                                                           , Adam McKay, "Don't Look Up"                                                                                                                                                                                    , Aaron Sorkin , "Being the Ricardos"                                                                                                                                                                            ,                                                                                                                                                                                                                , Best Original Song -- Motion Picture                                                                                                                                                                           , "Be Alive" from "King Richard" - Beyoncé Knowles-Carter, Dixson                                                                                                                                                , "Dos Orugitas" from "Encanto" - Lin-Manuel Miranda                                                                                                                                                             , "Down to Joy" from "Belfast" - Van Morrison                                                                                                                                                                    , "Here I Am (Singing My Way Home)" from "Respect" - Jamie Alexander Hartman, Jennifer Hudson, Carole King                                                                                                       , "No Time to Die" from "No Time to Die" - Billie Eilish, Finneas O'Connell *WINNER                                                                                                                              ,                                                                                                                                                                                                                , Best Actor in a Supporting Role in Any Motion Picture                                                                                                                                                          , Ben Affleck, "The Tender Bar"                                                                                                                                                                                  , Jamie Dornan, "Belfast"                                                                                                                                                                                        , Ciarán Hinds, "Belfast"                                                                                                                                                                                        , Troy Kotsur, "CODA"                                                                                                                                                                                            , Kodi Smit-McPhee, "The Power of the Dog" *WINNER                                                                                                                                                               ,                                                                                                                                                                                                                , Best Actress in a Supporting Role in Any Motion Picture                                                                                                                                                        , Caitríona Balfe, "Belfast"                                                                                                                                                                                     , Ariana DeBose, "West Side Story" *WINNER                                                                                                                                                                       , Kirsten Dunst, "The Power of the Dog"                                                                                                                                                                          , Aunjanue Ellis, "King Richard"                                                                                                                                                                                 , Ruth Negga, "Passing                                                                                                                                                                                           ,                                                                                                                                                                                                                , Best Actor in a Motion Picture -- Musical or Comedy                                                                                                                                                            , Leonardo DiCaprio, "Don't Look Up"                                                                                                                                                                             , Peter Dinklage, "Cyrano"                                                                                                                                                                                       , Andrew Garfield, "Tick, Tick ... Boom!" *WINNER                                                                                                                                                                , Cooper Hoffman, "Licorice Pizza"                                                                                                                                                                               , Anthony Ramos, "In the Heights"                                                                                                                                                                                ,                                                                                                                                                                                                                , Best Motion Picture -- Animated                                                                                                                                                                                , "Encanto" *WINNER                                                                                                                                                                                              , "Flee"                                                                                                                                                                                                         , "Luca"                                                                                                                                                                                                         , "My Sunny Maad"                                                                                                                                                                                                , "Raya and the Last Dragon"                                                                                                                                                                                     ,                                                                                                                                                                                                                , Best Actor in a Motion Picture -- Drama                                                                                                                                                                        , Mahershala Ali, "Swan Song"                                                                                                                                                                                    , Javier Bardem, "Being the Ricardos"                                                                                                                                                                            , Benedict Cumberbatch, "The Power of the Dog"                                                                                                                                                                   , Will Smith, "King Richard" *WINNER                                                                                                                                                                             , Denzel Washington, "The Tragedy of Macbeth"                                                                                                                                                                    ,                                                                                                                                                                                                                , Best Actress in a Motion Picture -- Drama                                                                                                                                                                      , Jessica Chastain, "The Eyes of Tammy Faye"                                                                                                                                                                     , Olivia Colman, "The Lost Daughter"                                                                                                                                                                             , Nicole Kidman, "Being the Ricardos" *WINNER                                                                                                                                                                    , Lady Gaga, "House of Gucci"                                                                                                                                                                                    , Kristen Stewart, "Spencer"                                                                                                                                                                                     ,                                                                                                                                                                                                                , Best Actress in a Motion Picture -- Musical or Comedy                                                                                                                                                          , Marion Cotillard, "Annette"                                                                                                                                                                                    , Alana Haim, "Licorice Pizza"                                                                                                                                                                                   , Jennifer Lawrence, "Don't Look Up"                                                                                                                                                                             , Emma Stone, "Cruella"                                                                                                                                                                                          , Rachel Zegler, "West Side Story" *WINNER                                                                                                                                                                       ,                                                                                                                                                                                                                , Best Director -- Motion Picture                                                                                                                                                                                , Kenneth Branagh, "Belfast"                                                                                                                                                                                     , Jane Campion, "The Power of the Dog" *WINNER                                                                                                                                                                   , Maggie Gyllenhaal, "The Lost Daughter"                                                                                                                                                                         , Steven Spielberg, "West Side Story"                                                                                                                                                                            , Denis Villeneuve, "Dune"                                                                                                                                                                                       ,                                                                                                                                                                                                                , Best Original Score                                                                                                                                                                                            , "The French Dispatch"                                                                                                                                                                                          , "Encanto"                                                                                                                                                                                                      , "The Power of the Dog"                                                                                                                                                                                         , "Parallel Mothers"                                                                                                                                                                                             , "Dune" *WINNER                                                                                                                                                                                                 ,                                                                                                                                                                                                                , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/china-fines-japanese-7-eleven-taiwan-country </td>
   <td style="text-align:left;"> 2022-01-10 04:48:06 </td>
   <td style="text-align:left;"> China fines Japanese-owned 7-Eleven for calling Taiwan a country </td>
   <td style="text-align:left;"> Independent Women's Forum foreign policy fellow Claudia Rosett reacts to growing tensions between China and Taiwan and applauds NBA’s Enes Kanter for standing up to China.                                                                                                                   , The Chinese government has fined the Japanese-owned 7-Eleven convenience store chain in Beijing for featuring a map on its website that labeled the island of Taiwan a country.                                                                                                               , The company was fined 150,000 yuan ($23,519) by Chinese market regulators for displaying an "incorrect" and "incomplete" Chinese map that labeled Taiwan "an independent country," the Global Times, a Communist Party tabloid, reported Friday.                                              , CHINA ACCUSES WALMART OF 'STUPIDITY AND SHORTSIGHTEDNESS' AMID CLAIMS IT PULLED XIANJIANG PRODUCTS                                                                                                                                                                                            , A 7-Eleven location in Madison Heights, Michigan. It is the world's largest chain of convenience stores. Headquartered in Japan, there are currently a total of 39,000 locations worldwide.                                                                                                   , "Taiwan is an inalienable part of China’s territory and the one-China principle is a widely-recognized norm governing international relations and the broad consensus of the international community," Wang Wenbin, spokesperson for the Chinese Foreign Ministry, said at a press conference., Beijing also complained that the 7-Eleven website didn’t use its official names for some disputed islands in the South China Sea, The Guardian reported.                                                                                                                                      , The Beijing stores are owned by a subsidiary of Japanese firm 7 &amp; i Holdings, which said it would "do our best to prevent a recurrence," The Guardian reported.                                                                                                                               , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                       , China claims Taiwan is part of its own territory and has rejected its claims of independence after the two countries split in 1949. The U.S. does not formally recognize Taiwan but maintains an unofficial relationship and is supportive of its democratic government.                      , Beijing has been increasing its presence near Taiwan and has been sending dozens of warplanes towards its defense zone, coinciding with calls by President Xi Jinping for Taiwan to be brought into China as part of a "peaceful reunification."                                              , Fox News' Adam Shaw contributed to this article. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/features/race-for-batteries-scientist-seen-all </td>
   <td style="text-align:left;"> 2022-01-10 02:24:54 </td>
   <td style="text-align:left;"> In the race for batteries, one scientist has seen it all </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Much of the technology behind the batteries that power electric vehicles and smartphones came from the U.S. Most batteries are made by Asian companies using materials produced in China.                                                                                                                                                                                                                                                                                                                               , Susan Babinec is trying to put the U.S. in front again on batteries. She has been among the leading U.S. battery scientists for more than 20 years and believes cutting-edge science will make that happen.                                                                                                                                                                                                                                                                                                             , "Everyone knows what the stakes are," Ms. Babinec said. As batteries become more sophisticated, "we’re playing to the United States’ strength. We are bad-ass scientists."                                                                                                                                                                                                                                                                                                                                              , TOYOTA TO BUILD $1.29B BATTERY MANUFACTURING PLANT IN NORTH CAROLINA                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Ms. Babinec has played key roles in the rise, fall and rise again of the U.S. battery industry. Currently a leader of battery research and development at Argonne National Laboratory outside Chicago, Ms. Babinec holds more than 50 patents. She has done stints with the federal government, the most famous failed battery startup and chemical giant Dow Chemical.                                                                                                                                                 , The transition away from fossil fuels has sparked a global arms race to improve battery technology. Better batteries would extend the range and quicken the charging of electric cars. They would allow solar and wind power to run the electric grid even after the wind stops and the sun sets.                                                                                                                                                                                                                       , United Auto Workers President Rory Gamble told Reuters the union is in talks with General Motors about representing workers at joint venture battery plants, and voiced opposition to proposals for Washington to impose a firm deadline to end use of gas (Ford)                                                                                                                                                                                                                                                       , The U.S. has fallen far behind in batteries. China accounts for 79% of the production of lithium-ion cells, compared with 7% in the U.S. and 7% in Europe, according to Wood Mackenzie. China produces about 80% of the chemicals used in lithium-ion batteries, according to Benchmark Mineral Intelligence, which tracks the battery supply chain.                                                                                                                                                                    , The Biden administration and private investors are trying to reverse that. They are funding battery startups, developing lithium mines in the U.S. and aiming to cut the cost of batteries for the electric grid by 90% within the decade.                                                                                                                                                                                                                                                                              , Ms. Babinec’s first close encounter with electricity occurred when she stuck a scissors in a light socket when she was a child. She was briefly knocked unconscious and awoke on the other side of the room. She blacked out her house but was uninjured.                                                                                                                                                                                                                                                               , EV TRUCK MAKER RIVIAN PLANS IN-HOUSE BATTERY CELL MANUFACTURING                                                                                                                                                                                                                                                                                                                                                                                                                                                         , She joined Dow Chemical in 1979 after earning a degree in chemistry at the University of Wisconsin and became the chemical giant’s first female corporate fellow, the highest level scientist at the company, in 1998. She also worked for Dow’s venture capital group, where she gained experience developing new businesses.                                                                                                                                                                                          , Dow management asked her to put together a strategy in energy. She quickly landed on batteries, which she thought was a good fit for a big chemicals and materials producer. "I saw that it was going to be a huge materials play, and Dow was a materials company," she said.                                                                                                                                                                                                                                          , Demand was rising from laptops and cellphones. Soon after, researchers at Argonne applied for a patent for what would become one of the dominant types of lithium ion-batteries. Money began flowing to battery startups.                                                                                                                                                                                                                                                                                               , British manufacturers and those in other parts of Europe want to move more of the supply chain for batteries used in electric cars and renewable energy away from China and closer to their plants, a survey showed. (Mikael Sjoberg/Bloomberg via Getty I                                                                                                                                                                                                                                                              , Ms. Babinec wanted Dow to acquire an alternative-energy company called T/J Technologies that specialized in nanomaterials. Dow passed on the deal and a hot battery startup named A123 Systems snapped it up.                                                                                                                                                                                                                                                                                                           , Frustrated with the slow pace of change at Dow, she joined A123 in 2007. Working at the company’s Ann Arbor, Mich., research facility, Ms. Babinec reveled in the freewheeling culture of a startup. Her second day on the job, a pipe broke and she helped fix it. "If I was at Dow, I would have to call the union and it would have taken weeks to fix," she said.                                                                                                                                                   , A123 suffered a string of setbacks. Electric vehicles failed to take off in the U.S. despite the rise of Tesla Inc., and battery technology advanced more slowly than expected. A defect was found in one of the company’s batteries, leading to a recall and millions of dollars in losses. Ms. Babinec’s group figured out what the problem was. "I’ll never forget that day," she said.                                                                                                                              , LITHIUM PRICES SOAR, TURBOCHARGED BY ELECTRIC-VEHICLE DEMAND AND SCANT SUPPLY                                                                                                                                                                                                                                                                                                                                                                                                                                           , The company declared bankruptcy in 2012, and Ms. Babinec was briefly out of a job. It marked the beginning of a years-long drought in funding for clean-energy projects in the U.S. The high-profile collapse of solar startup Solyndra in 2011 and dirt-cheap natural-gas prices that undercut the urgency to transition away from fossil fuels drained investor enthusiasm for clean energy. The Chinese government, meanwhile, pushed into batteries and the materials that go into them, such as cobalt and lithium., Tesla automobile plugged in and charging at a Supercharger rapid battery charging station for the electric vehicle company Tesla Motors in the Silicon Valley town of Mountain View, Calif., in August 2016. (Smith Collection/Gado/Getty Images / Getty Images)                                                                                                                                                                                                                                                        , About a month after A123 failed, Ms. Babinec joined the Energy Department’s Advanced Research Projects Agency-Energy, or ARPA-E. Modeled on the Defense Department’s research arm, ARPA-E funds early-stage innovation projects. With private funding tight, Ms. Babinec helped direct $120 million to a range of battery companies during a six-year stint.                                                                                                                                                            , Among the battery companies Ms. Babinec helped fund were: Natron Energy, which is developing a rechargeable battery that uses abundant sodium instead of lithium, which is harder to get; Sila Nanotechnologies Inc., a Silicon Valley startup that raised $590 million in new funding in January 2021; and Ion Storage Systems, a developer of so-called solid-state batteries that can last longer than today’s standard technology.                                                                                  , Ms. Babinec’s business background proved valuable to scientists with little experience outside of the lab. Eric Wachsman, a chemistry professor at the University of Maryland and founder of Ion Storage Systems, said that when he performed an experiment on his battery materials, she made him do it two more times with increasing precision before she was satisfied. "She’s a taskmaster," he said.                                                                                                              , TESLA ACTIVISTS CALL FOR CHINA SHOWROOM CLOSURE                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Ion Storage plans to produce more than one million cellphone-size batteries annually from its Maryland facility beginning in 2023. The company has a contract to develop batteries for the U.S. Army and foresees producing an electric-vehicle battery in several years.                                                                                                                                                                                                                                               , Ms. Babinec left ARPA-E in 2018 and joined Argonne, taking the lead of its stationary energy storage program, including a focus on long-duration batteries. Argonne is a descendant of the Chicago lab where Enrico Fermi worked on nuclear reactions for the Manhattan Project.                                                                                                                                                                                                                                        , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Long-duration batteries, often massive in scale, capture the intermittent power generated by windmills and solar. They can distribute energy over extended periods of time, such as several days, as customers need it. Lithium-ion batteries, by contrast, can only discharge for four or five hours. Much of the technology remains expensive and unproven on a large scale, but an electric grid powered by renewable energy is impossible without it.                                                               , A secret weapon for researchers at Argonne is the Advanced Photon Source, a massive high-energy X-ray device that gives scientists the ability to peer inside batteries as they operate. The device can help discover new chemical combinations to maximize battery performance. An upgrade currently under way that will be completed in the next few years will make it 500 times brighter, Argonne scientists said.                                                                                                  , Last summer, inside a hermetically sealed room deep within Argonne’s sprawling laboratory complex, Ms. Babinec pointed to a machine slowly coating a copper plate with a thin slurry of graphite, a key lithium-ion battery material.                                                                                                                                                                                                                                                                                   , Thinking back to the failure of A123, Ms. Babinec said the process had to be perfect. Otherwise, she said, "You can destroy a company."                                                                                                                                                                                                                                                                                                                                                                                 , This article was originally published in The Wall Street Journal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/09/business/ruth-shalit-barrett-atlantic-lawsuit.html </td>
   <td style="text-align:left;"> 2022-01-10 02:22:17 </td>
   <td style="text-align:left;"> Freelance Writer Ruth Shalit Barrett Accuses Atlantic of Defamation - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , A lawsuit by Ruth Shalit Barrett centers on the magazine’s retraction of her article in 2020 about wealthy parents seeking Ivy League admissions for their children through sports.                                                                                                                                                                                                                                                                                                                                                                                                , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , By Katie Robertson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , A freelance writer, Ruth Shalit Barrett, accused The Atlantic of defamation in a lawsuit that centers on the rare retraction of a magazine article.                                                                                                                                                                                                                                                                                                                                                                                                                                , Ms. Barrett was the author of “The Mad, Mad World of Niche Sports,” an investigative article about wealthy Connecticut parents pursuing Ivy League admissions for their children through various athletic endeavors. The Atlantic published the article online in October 2020 and in its November 2020 print issue.                                                                                                                                                                                                                                                               , After questions were raised by The Washington Post’s media critic, Erik Wemple, The Atlantic took the highly unusual step of retracting the entire article. In a lengthy editor’s note, the outlet said that “new information” had emerged that cast doubt on the accuracy of the article and the “trustworthiness” of Ms. Barrett. The Atlantic also said Ms. Barrett had encouraged a source to lie to its fact checkers and noted details about Ms. Barrett’s background, including plagiarism accusations against her in the 1990s when she was a reporter at The New Republic., In a lawsuit filed on Saturday in the U.S. District Court in Washington, D.C., that asks for $1 million in damages, Ms. Barrett accused The Atlantic and Donald Peck, its top print editor at the time, of smearing her reputation.                                                                                                                                                                                                                                                                                                                                                , The Atlantic had caved to pressure from Mr. Wemple, she said, who, in a series of columns, had questioned both the veracity of some of the details in the article, including the description of a fencing injury, and whether The Atlantic had deceived readers by not including Ms. Barrett’s maiden name, which she used at The New Republic.                                                                                                                                                                                                                                    , Ms. Barrett stated in the lawsuit that the only “falsehood” The Atlantic had uncovered was the addition of a nonexistent son to the family of “Sloane,” a central character in the article. Ms. Barrett said she had added the son at the request of the anonymous source to help disguise her identity.                                                                                                                                                                                                                                                                           , Ms. Barrett also said in the suit that The Atlantic’s editors had employed a similar tactic by changing a quote in her article to shield the identity of someone, which a fact-checker said in a text message was because of “a legal request.” A spokeswoman for The Atlantic, Anna Bross, said in an email: “Our lawyers have never, in this case or any other, advised editors to alter direct quotes. This is a basic journalistic principle; of course, we do not alter quotes.”                                                                                              , Ms. Barrett argued that the inclusion of the son was necessary to protect her source and that she was “acting in accordance with the law and ethical precepts of the profession of journalism.” She also said in the suit the two factual inaccuracies regarding the town one person was from and the size of backyard hockey rinks were “so trivial and insignificant as to hardly warrant correction — let alone the full retraction of a serious and meaningful piece of journalism.”                                                                                           , The Atlantic, in a nearly 1,000-word editor’s note, said that its fact-checking department had gone through the piece and spoken with more than 40 sources, but that Ms. Barrett had misled the fact checkers and lied to the editors.                                                                                                                                                                                                                                                                                                                                             , “It is impossible for us to vouch for the accuracy of this article,” the note said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , In the lawsuit, Ms. Barrett also accused The Atlantic of misrepresenting her background and destroying her journalistic career through what it publicly said about her.                                                                                                                                                                                                                                                                                                                                                                                                            , Ms. Barrett was a rising star in political journalism in the 1990s, when she was in her 20s and wrote under her maiden name Ruth Shalit. She was accused of plagiarism in 1994 and 1995 over several passages and sentences in some of her work that resembled the work of other journalists. She left her job at The New Republic in 1999, and has had few articles published in the last 20 years.                                                                                                                                                                               , The Atlantic said in the editor’s note that it had originally used the byline “Ruth S. Barrett” at Ms. Barrett’s request “but in the interest of transparency, we should have included the name that she used as her byline in the 1990s.” The note said that Ms. Barrett had been assigned the story because “more than two decades separated her from her journalistic malpractice at The New Republic” but that editors regretted the decision.                                                                                                                                 , In the lawsuit, Ms. Barrett accused The Atlantic of folding to pressure from Mr. Wemple and misrepresenting her background. She said that she had an “antagonistic relationship” with the Post journalist leading back to the 1990s when he worked at the Washington City Paper.                                                                                                                                                                                                                                                                                                   , Mr. Wemple said in an email that he did not recall meeting or interacting with Ms. Barrett before 2020, when he wrote his columns about her Atlantic story.                                                                                                                                                                                                                                                                                                                                                                                                                        , “I was doing my job as a media critic,” Mr. Wemple said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Ms. Bross, The Atlantic’s spokeswoman, said the publication stood by its retraction and editor’s note.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , “We completely reject the allegations and believe the suit is meritless, will be filing a motion to dismiss, and are confident we will ultimately prevail,” she said in a statement.                                                                                                                                                                                                                                                                                                                                                                                               , Ms. Barrett’s lawyers offered in early December to settle the case before they filed the lawsuit. In a letter sent to The Atlantic that was obtained by The New York Times, Ms. Barrett’s lawyers said they would not sue if The Atlantic agreed to make corrections to its editor’s note, surrender intellectual property rights to the article and pay Ms. Barrett’s legal fees, which at the time were nearly $120,000.                                                                                                                                                         , “Any post-suit settlement would require monetary compensation, which Ms. Barrett is willing to forego at this point in order to attain some minimal repair of her journalistic reputation,” the letter said.                                                                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/09/us/bronx-fire-injuries/index.html </td>
   <td style="text-align:left;"> 2022-01-10 02:20:57 </td>
   <td style="text-align:left;"> Bronx apartment building fire leaves 19 people dead, including 9 children - CNN </td>
   <td style="text-align:left;"> (CNN)A major fire in a residential apartment building in the Bronx in New York City on Sunday left 19 people dead, including 9 children, in what Mayor Eric Adams described as one of the worst fires the city has experienced in modern times.                                                                                                                                                                       , The blaze sent 32 people to hospitals with life-threatening conditions, Daniel Nigro, commissioner of the New York City Fire Department, said earlier Sunday. A total of 63 people were injured.                                                                                                                                                                                                                       , A "malfunctioning electric space heater" was the source of the fire, Nigro said during a press conference. The heater was in the bedroom of an apartment, and the fire consumed the room and then the entire apartment, he said.                                                                                                                                                                                       , The apartment door was left open and smoke spread throughout the building when the residents left their unit, Nigro said.                                                                                                                                                                                                                                                                                              , "This is a horrific, horrific, painful moment for the city of New York, and the impact of this fire is going to really bring a level of just pain and despair in our city," Adams said.                                                                                                                                                                                                                                , About 200 members of the New York City Fire Department responded to the fire at the 19-story building at 333 East 181st Street. The fire began a little before 11 a.m. in a duplex apartment on the 2nd and 3rd floors of the building, the FDNY said.                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                        , Firefighters were met by "very heavy smoke, very heavy fire" in the hallways.                                                                                                                                                                                                                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                                                                                        , Victims were found in stairways on every floor of the building, many in cardiac arrest, in what Nigro said could be an unprecedented loss of life. The injuries were predominantly from smoke inhalation, he said.                                                                                                                                                                                                     , Firefighters kept attempting to save people from the building despite running out of air tank, Nigro said. Some of the residents who were trying to leave the building could not "escape because of the volume of smoke."                                                                                                                                                                                              , The FDNY posted several images of the scene showing ladders extending into apartment windows as well as a number of broken windows.                                                                                                                                                                                                                                                                                    , "This is going to be one of the worst fires that we have witnessed during modern times here in the city of New York," Adams said.                                                                                                                                                                                                                                                                                      , "I am horrified by the devastating fire in the Bronx today," New York Gov. Kathy Hochul said on Twitter. "My heart is with the loved ones of all those we've tragically lost, all of those impacted and with our heroic FDNY firefighters. The entire State of New York stands with New York City."                                                                                                                    , The residential apartment where the fire occurred is 50 years old and has 120 units, according to building records.                                                                                                                                                                                                                                                                                                    , There have not been any major building violations or complaints listed against the building, according to city building records. Past minor violations were rectified by the property and there were no structural violations listed.                                                                                                                                                                                  , Apartment fire impacts Muslim and immigrant community                                                                                                                                                                                                                                                                                                                                                                  , The building where the fire occurred housed a largely Muslim population, Adams said, with many immigrants from Gambia, a small nation on the west coast of Africa.                                                                                                                                                                                                                                                     , The mayor said that one priority will be to make sure that Islamic funeral and burial rites are respected. Another will be to seek Muslim leaders to connect with residents.                                                                                                                                                                                                                                           , The names of people who request government assistance will not be turned over to Immigration and Customs Enforcement, Adams added.                                                                                                                                                                                                                                                                                     , "We want people to be comfortable in coming forward, and it's imperative that we connect with those on the ground to make sure they get that message and that word out," Adams said.                                                                                                                                                                                                                                   , Christina Farrell, first deputy commissioner of NYC emergency management, told CNN's Phil Mattingly Sunday that residents who lived in the apartment building are now being housed at a middle school next door.                                                                                                                                                                                                       , "We have all the residents here. We've been able to give them food, a warm space, water, any short-term needs that they had. People brought their pets and so we are in the process of finding people shelter this evening," Farrell said. "We work with the Red Cross, we have hotel rooms and have other resources available. And so we will be making sure every family has a safe, warm space to sleep in tonight.", A service center will be set up Monday, Farrell said.                                                                                                                                                                                                                                                                                                                                                                  , "We'll be hopeful that many of them will be able to go back into their apartment in the coming days," she said. "But for the people that are out long-term, we will work with them and the state to get them appropriate housing."                                                                                                                                                                                     , Hochul, appearing at a press conference Sunday, said she met with survivors of the fire, including a mother who was her family's sole survivor.                                                                                                                                                                                                                                                                        , "It's impossible to go into that room, where scores of families who are in such grief, who are in pain, and to see it in the mother's eyes as I held her, who lost her entire family," she said.                                                                                                                                                                                                                       , As she prepares her new budget this week, Hochul said she will establish a compensation fund to help provide the victims of the fire with money for housing, burial costs and other necessities.                                                                                                                                                                                                                       , "Tonight is a night of tragedy and pain, and tomorrow we begin to rebuild," Hochul said. "We rebuild their lives and give them hope, especially those who came all the way from Africa [from] Gambia in search of a better life right here in this great borough of the Bronx."                                                                                                                                        , Senate Majority Leader Chuck Schumer also spoke at the conference and said numerous forms of assistance are being examined on the federal level and will include housing and tax assistance as well as and immigration assistance, "so families can be reunited."                                                                                                                                                      , Correction: An earlier version of this story misstated the region where Gambia is located. It is in West Africa.                                                                                                                                                                                                                                                                                                       , CNN's Brynn Gingras contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/media/2022/01/09/politico-sotomayor-error-rs-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-10 01:13:29 </td>
   <td style="text-align:left;"> Politico apologizes for false story about photo of Sonia Sotomayor and Chuck Schumer - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/09/business/us-flight-cancellations.html </td>
   <td style="text-align:left;"> 2022-01-10 01:09:04 </td>
   <td style="text-align:left;"> U.S. Flight Cancellations Continue Into the Weekend - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                      , By Niraj Chokshi                                                                                                                                                                                                                                                                                                                                                                                                                                   , Airlines canceled thousands more flights in recent days as the industry tried to move past its holiday hangover.                                                                                                                                                                                                                                                                                                                                   , Bad weather and coronavirus outbreaks among workers continued to disrupt schedules across the United States, but airlines have also called off many recent flights, in advance, so they can correct course at a traditionally slow time for travel without surprising customers with last-minute cancellations.                                                                                                                                    , About 5,000 flights were canceled from Friday through Sunday, according to FlightAware, a data tracking service, with the daily number of cuts declining steadily over that period. Southwest Airlines suspended over 1,000 flights, more than any other carrier. SkyWest Airlines, which operates flights for several major carriers, and United Airlines each canceled more than 500 flights.                                                    , The turmoil began before Christmas, caused by bad weather in the West and staff shortages because of virus outbreaks among employees. Snowfall in the Northeast continued to wreak havoc at major airport hubs across the country into the first weekend of this month.                                                                                                                                                                            , “Given the ongoing surge in Covid cases and related sick calls, we’ve been working with each of our major partners to proactively reduce our January schedules,” SkyWest said in a statement. The airline operates flights for United, Delta Air Lines, American Airlines and Alaska Airlines and said the pullback is intended to “ensure we’re able to adequately staff our remaining flying as we work to recover in the coming weeks.”         , After canceling flights at high rates over the holidays, JetBlue Airways said it would preemptively cut about 1,300 flights in the first half of January. Alaska said in a statement last week that it would slash about one in 10 flights planned for the month to gain “the flexibility and capacity needed to reset.”                                                                                                                           , As in many other industries, airlines are also contending with workers calling in sick at high rates as the Omicron virus variant spreads at astonishing speed.                                                                                                                                                                                                                                                                                    , “It has been one of the most difficult operational environments we’ve ever faced,” Allison Ausband, Delta’s chief customer experience officer, said in a statement last week apologizing to customers for the disorder.                                                                                                                                                                                                                            , To deal with staffing shortages, many carriers have started offering extra pay to those who were otherwise not scheduled to work. Southwest, for example, said last week that it was offering double pay for most of the month to employees who picked up extra shifts, incentives available to workers across its operation, including ground staff, flight attendants, customer service employees, flight schedulers and maintenance technicians., The chaos comes at a frustrating time for the industry, which is preparing for a significant rebound this summer. That recovery rests largely on the hope that the pandemic will be mostly under control by then and that people will be more willing to travel internationally and for work.                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/09/health/sleep-history-wellness-scn/index.html </td>
   <td style="text-align:left;"> 2022-01-09 21:54:46 </td>
   <td style="text-align:left;"> How our ancestors used to sleep can help the sleep-deprived today - CNN </td>
   <td style="text-align:left;"> Sign up for the Sleep, But Better newsletter series. Our seven-part guide has helpful hints to achieve better sleep.                                                                                                                                                                                                                                                                                                                                                                                     ,  (CNN)Like many people, historian A. Roger Ekirch thought that sleep was a biological constant -- that eight hours of rest a night never really varied over time and place.                                                                                                                                                                                                                                                                                                                              , But while researching nocturnal life in preindustrial Europe and America, he discovered the first evidence that many humans used to sleep in segments -- a first sleep and second sleep with a break of a few hours in between to have sex, pray, eat, chat and take medicine.                                                                                                                                                                                                                           , "Here was a pattern of sleep unknown to the modern world," said Ekirch, a university distinguished professor in the department of history at Virginia Tech.                                                                                                                                                                                                                                                                                                                                              , Ekirch's subsequent book, "At Day's Close: Night in Times Past," unearthed more than 500 references to what's since been termed biphasic sleep.  Ekirch has now found more than 2,000 references in a dozen languages and going back in time as far as ancient Greece. His 2004 book will be republished in April.                                                                                                                                                                                       , The practice of sleeping through the whole night didn't really take hold until just a few hundred years ago, his work suggested. It only evolved thanks to the spread of electric lighting and the Industrial Revolution, with its capitalist belief that sleep was a waste of time that could be better spent working.                                                                                                                                                                                  , The history of sleep not only reveals fascinating details about everyday life in the past, but the work of Ekirch, and other historians and anthropologists, is helping sleep scientists gain fresh perspective on what constitutes a good night's sleep. It also offers new ways to cope with and think about sleep problems.                                                                                                                                                                           , There is value in knowing about this prior pattern of sleep in the Western world. "A large number of people who today suffer from middle-of-the-night insomnia, the primary sleep disorder in the United States -- and I dare say in most industrialized countries -- rather than experiencing a quote unquote, disorder, are in fact, experiencing a very powerful remnant, or echo of this earlier pattern of sleep," Ekirch said.                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Myth of 8-hour sleep?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The first reference to biphasic sleep Ekirch found was in a 1697 legal document from a traveling "Assizes" court buried in a London record office. The deposition of a 9-year-old girl called Jane Rowth mentioned that her mother awoke after her "first sleep" to go out. The mother was later found dead.                                                                                                                                                                                             , "I had never heard the expression, and it was expressed in such a way that it seemed perfectly normal," he said. "I then began to come across subsequent references in these legal depositions but also in other sources."                                                                                                                                                                                                                                                                               , Ekirch subsequently found multiple references to a "first" and "second" sleep in diaries, medical texts, works of literature and prayer books. A doctor's manual from 16th century France advised couples that the best time to conceive was not at the end of a long day but "after the first sleep," when "they have more enjoyment" and "do it better."                                                                                                                                               , By the early 19th century, however, the first sleep had begun to expand at the expense of the second sleep, Ekirch found, and the intervening period of wakefulness. By the end of the century, the second sleep was little more than turning over in one's bed for an extra 10 minutes of snoozing.                                                                                                                                                                                                     , Ben Reiss, author of "Wild Nights: How Taming Sleep Created Our Restless World" and professor and chair of the English department at Emory University in Atlanta, blames the Industrial Revolution and the "sleep is for wimps" attitude it engendered.                                                                                                                                                                                                                                                  , "The answer is really to follow the money. Changes in economic organization, when it became more efficient to routinize work and have large numbers of people showing up on factory floors, at the same time and doing as much work in as concentrated fashion as possible," Reiss said.                                                                                                                                                                                                                 , Our sleep schedule got squeezed and consolidated as a result, Reiss said.                                                                                                                                                                                                                                                                                                                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , No golden age                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , However, preindustrial life was no halcyon era when our ancestors went about their day well rested and rejuvenated, untroubled by insomnia or other sleep problems, effortlessly in sync with the cycle of night and day, weather patterns and seasons, according to Sasha Handley, a professor of history at The University of Manchester in the United Kingdom. She studies how families optimized their sleep in Britain, Ireland and England's American colonies between 1500 and 1750.              , "Every discussion of sleep history seemed to center around the sort of watershed moment of industrialization, the coming of electricity ruining everybody's sleep lives. The corollary of that is that anything preindustrial was imagined as this golden age of sleep."                                                                                                                                                                                                                                 , Handley said her research suggested, just like today, sleep was linked to physical and mental health and was a topic that people worried about and obsessed over.                                                                                                                                                                                                                                                                                                                                        , Doctor's manuals from the time are full of advice on how many hours to sleep and in what kind of posture, she said. The reference guides also list hundreds of sleep recipes to aid a good night's sleep, she said. These include the bizarre -- cutting a pigeon in half and sticking each half to each side of your head and the more familiar -- bathing in camomile-infused water and using lavender. People also burned specific types of wood in their bed chambers that were thought to aid sleep., "For our period, sleep is very strongly linked to digestion, emotion, stomach, and therefore to people's diets," Handley said.                                                                                                                                                                                                                                                                                                                                                                           , Doctors advised sleepers to rest first on the right side of their body before turning to the left side during the second half of the night. Resting on the right, perhaps during the first sleep, was thought to allow food to reach the pit of the stomach, where it was digested. Turning to the left, cooler side, released vapors and spread the heat evenly through the body.                                                                                                                       , It's thought this habit could be the origin of the phrase about getting out of bed on the wrong side.                                                                                                                                                                                                                                                                                                                                                                                                    , Not all scholars believe that sleeping in two shifts, while perhaps common in some communities, was once a universal habit. Far from it, said Brigitte Steger, a senior lecturer in Japanese studies at the University of Cambridge in the UK, who didn't uncover any references to segmented sleep in her work on sleep habits in Japan.                                                                                                                                                                , "There is no such thing as natural sleep. Sleep has always been cultural, social and ideological," said Steger, who is working on a series of six books about the cultural history of sleep.                                                                                                                                                                                                                                                                                                             , "There is not such a clear-cut difference between premodern (or pre-industrial) and modern sleep habits," she said via email. "And sleep habits throughout pre-industrial times and throughout the world have always changed. And, of course, there has always been social diversity, and sleep habits have been very different at court than for peasants, for instance."                                                                                                                               , Similarly, Gerrit Verhoeven, an assistant professor in cultural heritage and history at the University of Antwerp in Belgium, said his study of criminal court records from 18th century Antwerp suggested that sleep habits weren't so different to our own today. Seven hours of sleep was the norm and there was no mention of first or second sleep.                                                                                                                                                 , "As a historian I'm concerned that arguments about alleged sleeping patterns in the past -- prolonged, by-phasic and with napping during the day -- are sometimes presented as a possible remedy for our modern sleeping disorders. Before drawing such conclusions, we have to do much more research about these early modern sleeping patterns," he said.                                                                                                                                              , Rethinking insomnia                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Russell Foster, a professor of circadian neuroscience at the University of Oxford, said Ekirch's findings on biphasic sleep, while not without controversy, had informed his work as a sleep scientist.                                                                                                                                                                                                                                                                                                  , Experiments in sleep labs had shown that when humans are given the opportunity to sleep longer, he said, their sleep can become biphasic or even polyphasic, replicating what Ekirch found in historical records. However, Foster, who is also the director of the Sir Jules Thorn Sleep and Circadian Neuroscience Institute at Oxford, doubted that it was a sleep pattern that would happen for everybody.                                                                                            , Nobody should impose a regime of segmented sleep on themselves, particularly if it resulted in a reduction of total sleep time, he added.                                                                                                                                                                                                                                                                                                                                                                , What was clear, Foster said, was that interrupted sleep was perceived as less of a problem in the past and that modern expectations about what constitutes a good night's sleep -- sleeping through the night for eight hours -- weren't always helpful.                                                                                                                                                                                                                                                 , He said a key point was waking at night need not mean the end of sleep. One example he cited was more people waking up at night during lockdowns during the Covid-19 pandemic.                                                                                                                                                                                                                                                                                                                           , "They'll get terribly anxious and worried about waking up in the middle of night, because that's not what they normally experience," said Foster, who is also the author of "Life Time: The New Science of the Body Clock, and How It Can Revolutionize Your Sleep and Health," which will be published in May 2022. More likely, what had happened was that people's sleep episode -- how much time they have available for sleep -- had expanded and wasn't constricted by an alarm clock going off.   , "It's a throwback to a time when we genuinely got more sleep," he said.                                                                                                                                                                                                                                                                                                                                                                                                                                  , If we wake up at night, sleep is likely to return, if sleep is not sacrificed to social media or other behavior that makes you more alert or activates a stress response, Foster's research has suggested. Like most sleep experts, he recommended getting out of bed if you're getting frustrated by the failure to fall back to sleep and engaging in a relaxing activity while keeping the lights low.                                                                                                , "Individual sleep across humans is so variable. One size doesn't fit all. You shouldn't worry about the sort of sleep that you get," he said.                                                                                                                                                                                                                                                                                                                                                            , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/09/business/the-week-in-business-vaccine-mandates.html </td>
   <td style="text-align:left;"> 2022-01-09 20:00:08 </td>
   <td style="text-align:left;"> The Week in Business: Vaccine Mandates - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , with interest                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , By Sarah Kessler                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Businesses were grappling with increased staff shortages while workers called in sick or tested positive for Covid-19 as well as shifting guidance on what they are required to do to keep their workers safe. On Tuesday, the Centers for Disease Control and Prevention stood by its guidance that Americans who test positive for the coronavirus could end isolation after five days without obtaining a negative test. The omission of a testing requirement has been criticized by some public health experts, and the agency had been widely expected to add testing to its guidelines. Walmart told workers on Tuesday that it would cut its paid time off for workers who contract the virus to one week, down from two. On Friday, the Supreme Court heard arguments on the legality of two rules from the Biden administration: One requires large private businesses to ensure workers are vaccinated or undergo weekly tests and the other requires some health care workers to be vaccinated. Macy’s requested the vaccination status of its employees last week, while Starbucks set a Feb. 9 deadline for its U.S. workers to be fully vaccinated and Citigroup said it would dismiss unvaccinated employees by the end of the month., Employers are still having trouble finding workers. The U.S. economy added 199,000 jobs in December, down from 249,000 in November, the Labor Department said on Friday. It was the weakest job growth of the year, even before the Omicron variant of the coronavirus presented a new threat to the economy. The problem appears to be that demand for workers is outpacing available candidates. The unemployment rate in December fell to 3.9 percent from 4.2 percent, while average hourly earnings rose 4.7 percent over the year — a sign that companies are struggling to attract and retain workers. Data released Tuesday showed that more Americans quit their jobs in November than in any other month on record.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , After a trial that lasted more than three months and seven days of deliberations, the jury in the Elizabeth Holmes case reached a verdict on Monday, finding the Theranos founder guilty on four of 11 charges of fraud. Each count carries a maximum sentence of 20 years in prison, terms that are likely to be served concurrently. The case raised questions about Silicon Valley’s “fake it until you make it” culture and set off a debate about whether Ms. Holmes’s behavior reflects anything other than one entrepreneur’s false and misleading actions. Ms. Holmes is likely to appeal, and a sentencing date is expected to be set this week.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The entertainment industry heads into a diminished 2022 awards season this week. The Critics Choice Awards, initially scheduled for Sunday, have been postponed indefinitely because of coronavirus concerns. The Golden Globes, also scheduled for Sunday, will take place without an audience or a red carpet after questions were raised about possible financial missteps and a lack of diversity within the group that hands out the awards. The Grammy Awards, originally scheduled for Jan. 31, have been postponed; the Palm Springs International Film Festival, scheduled to run through this week, has been canceled; and the Sundance Film Festival will take place online only at the end of January. Plans for an in-person Academy Awards on March 27 remain unchanged, but relatively few people have seen the movies that are most likely to win Oscars.                                                                                                                                                                                                                                                                                                                                                                            , On Wednesday, the Department of Labor will report how much prices rose in December. In November, the Consumer Price Index, an important measure of inflation, rose at its fastest rate in nearly 40 years, and central banks around the world have begun efforts to cool off the economy. Minutes from the Federal Reserve’s December meeting released last week suggested that it may withdraw support for the economy more quickly than previously expected.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , The Senate will hold separate confirmation hearings this week for both Jerome H. Powell, who was nominated by President Biden for a second term as Federal Reserve chairman, and Lael Brainard, Mr. Biden’s nominee for deputy chair. Though some progressive Democrats, including Senator Elizabeth Warren, have said they will oppose Mr. Biden’s renomination of Mr. Powell, both Democrats and Republicans have expressed support for the appointment, which was widely seen as a signal of consistency. Mr. Powell will probably be asked about the controversy surrounding a financial transaction made by the departing vice chair of the Fed, Richard H. Clarida. Mr. Clarida bought shares in an investment fund that holds stocks one day before the Fed announced that it would rescue markets that were plunging at the start of the pandemic.                                                                                                                                                                                                                                                                                                                                                                                           , BlackBerry models that use the company’s operating systems stopped working on Tuesday, ending an era for the once-ubiquitous device. Apple’s market capitalization briefly hit $3 trillion for the first time. Cruises kept cruising despite warnings from the C.D.C. And airlines continued to cancel thousands of flights a day.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/sports/2022/01/09/australia-novak-djokovic-refugee-crisis-coren-pkg-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-09 19:49:37 </td>
   <td style="text-align:left;"> Djokovic's detention in Australia sheds light on refugee crisis - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/09/business/media/hollywood-golden-globes-oscars.html </td>
   <td style="text-align:left;"> 2022-01-09 18:00:10 </td>
   <td style="text-align:left;"> Quiet Awards Season Has Hollywood Uneasy - The New York Times </td>
   <td style="text-align:left;"> , Audiences remain reluctant to return to theaters. And the kinds of movies that used to rely on the sheen of awards to attract moviegoers now find themselves in peril.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Credit...Illustration by Delcan &amp; Co.; Photograph by Peter Dazeley/Getty Images                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , By Nicole Sperling                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , LOS ANGELES — Steven Spielberg directing a dance-filled musical through the streets of New York. Lady Gaga channeling her Italian roots. Will Smith back on the big screen. This year’s award season was supposed to celebrate Hollywood’s return to glitz and glamour. No more masks, no more socially distanced award shows or Zoom acceptance speeches, no more rewarding films that very few people had seen.                                                                                                                                                                                                                                                                                                                                                                                    , Now, between the Omicron spike and NBC’s decision not to televise the Golden Globes on Sunday because of the ethical issues surrounding the group that hands out the awards, Hollywood’s traditionally frenetic — and hype-filled — first week of the calendar year has been reduced to a whisper. The AFI Awards were postponed. The Critics’ Choice Awards — scheduled to be televised Sunday night in hopes of filling the void left by the Globes’ absence — were pushed back. The Palm Springs Film Festival, an annual stop along the awards campaign trail, was canceled. And most of those star-driven award favorites bombed at the box office.                                                                                                                                             , The Academy Awards remain scheduled for March 27, with nominations on Feb. 8, but there has been no indication what the event will be like. (The organization already postponed its annual Governors Awards, which for the past 11 years have bestowed honorary Oscars during a nontelevised ceremony.) Will there be a host? How about a crowd? Perhaps most important, will anyone watch? The Academy hired a producer of the film “Girls Trip” in October to oversee the show but has been mum on any additional details, and declined to comment for this article.                                                                                                                                                                                                                               , Suddenly, 2022 is looking eerily similar to 2021. Hollywood is again largely losing its annual season of superficial self-congratulation, but it is also seeing the movie business’s best form of advertisement undercut in a year when films desperately need it. And that could have far-reaching effects on the types of movies that get made.                                                                                                                                                                                                                                                                                                                                                                                                                                                    , “For the box office — when there was a fully functioning box office — those award shows were everything,” said Nancy Utley, a former co-chairman of Fox Searchlight who helped turn smaller prestige films like “12 Years a Slave” and “The Shape of Water” into best-picture Oscar winners during her 21-year tenure. “The recognition there became the reason to go see a smaller movie. How do you do that in the current climate? It’s hard.”                                                                                                                                                                                                                                                                                                                                                    , Many prestige films are released each year with the expectation that most of their box office receipts will be earned in the crucial weeks between the Golden Globes and the Academy Awards. The diminishing of the Globes — which collapsed after revelations involving possible financial impropriety, questionable journalistic ethics and a significant lack of diversity in the Hollywood Foreign Press Association, which administers the awards — had already hobbled that equation. If the Hollywood hype machine loses its awards season engine, it could prove devastating to the already injured box office. The huge audience shift fueled by streaming may be here to stay, with only blockbuster spectacles like “Spider-Man: No Way Home” drawing theatergoers in significant numbers., “The movie business is this gigantic rock, and we’re close to seeing that rock crumble,” said Stephen Galloway, the dean of Chapman University’s Dodge College of Film and Media Arts and a former executive editor of The Hollywood Reporter. “People have gotten out of the habit of seeing movies on a big screen. Award season is the best single tub-thumping phenomenon for anything in the world. How many years can you go without that?”                                                                                                                                                                                                                                                                                                                                                    , The Academy Awards were created in 1929 to promote Hollywood’s achievements to the outside world. At its pinnacle, the telecast drew 55 million viewers. That number has been dropping for years, and last year it hit an all-time low — 10.4 million viewers for a show without a host, no musical numbers and a little-seen best picture winner in “Nomadland.” (The film, which was released simultaneously in theaters and on Hulu, grossed just $3.7 million.)                                                                                                                                                                                                                                                                                                                                  , Hollywood was planning to answer with an all-out blitz over the past year, even before the awards season. It deployed its biggest stars and most famous directors to remind consumers that despite myriad streaming options, theatergoing held an important place in the broader culture.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , It hasn’t worked. The public, in large part, remains reluctant to return to theaters with any regularity. “No Time to Die,” Daniel Craig’s final turn as James Bond, was delayed for over a year because of the pandemic, and when it was finally released, it made only $160.7 million in the United States and Canada. That was $40 million less than the 2015 Bond film, “Spectre,” and $144 million below 2012’s “Skyfall,” the highest-grossing film in the franchise.                                                                                                                                                                                                                                                                                                                          , Well-reviewed, auteur-driven films that traditionally have a large presence on the awards circuit, like “Last Night in Soho” ($10.1 million), “Nightmare Alley” ($8 million) and “Belfast” ($6.9 million), barely made a ripple at the box office.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , And even though Mr. Spielberg’s adaptation of “West Side Story” has a 93 percent positive rating on Rotten Tomatoes, it has earned only $30 million at the domestic box office. (The original grossed $44 million back in 1961, the equivalent of $409 million in today.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , According to a recent study, 49 percent of prepandemic moviegoers are no longer buying tickets. Eight percent say they will never return. Those numbers are a death knell for the midbudget movies that rely on positive word of mouth and well-publicized accolades to get patrons into seats.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Some believe the middle part of the movie business — the beleaguered category of films that cost $20 million to $60 million (like “Licorice Pizza” and “Nightmare Alley”) and aren’t based on a comic book or other well-known intellectual property — may be changed forever. If viewing habits have been permanently altered, and award nominations and wins no longer prove to be a significant draw, those films will find it much more difficult to break even. If audiences are willing to go to the movies only to see the latest “Spider-Man” film, it becomes hard to convince them that they also need see a movie like “Belfast,” Kenneth Branagh’s black-and-white meditation on his childhood, in a crowded theater rather than in their living rooms.                                  , “All of this doesn’t just affect individual films and filmmakers’ careers,” Mr. Galloway said. “Its effect is not even just on a business. It affects an entire art form. And art is fragile.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Of the other likely best-picture contenders given a significant theatrical release, only “Dune,” a sci-fi spectacle based on a known property, crossed the $100 million mark at the box office. “King Richard” earned $14.7 million, and “Licorice Pizza” grossed $7 million.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , “The number of non-genre adult dramas that have cracked $50M is ZERO,” the film journalist and historian Mark Harris wrote on Twitter on Thursday. “The world of 2019, in which ‘1917’ made $160M, ‘Ford v. Ferrari’ made $120M, and ‘Parasite’ made $52M, is gone.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Still, studios are adjusting. MGM is slowing down its theatrical rollout of “Licorice Pizza” after watching other prestige pictures stumble when they entered more than 1,000 theaters. It is also pushing its release in Britain of “Cyrano,” starring Peter Dinklage, to February to follow the American release with the hope that older female moviegoers will return to the cinema by then. Sony Pictures Classics is redeploying the playbook it used in 2021: more virtual screenings and virtual Q.&amp;A.s to entice academy voters while also shifting distribution to the home faster. Its documentary “Julia,” about Julia Child, hit premium video-on-demand over the holidays.                                                                                                             , Many studios got out in front of the latest pandemic wave with flashy premieres and holiday parties in early December that required proof of vaccination and on-site testing. But so far in January, many of the usual awards campaigning events like screenings and cocktail parties are being canceled or moved to the virtual world. “For your consideration” billboards are still a familiar sight around Los Angeles, but in-person meet-and-greets are largely on hold.                                                                                                                                                                                                                                                                                                                        , Netflix, which only releases films theatrically on a limited basis and doesn’t report box office results, is likely to have a huge presence on the award circuit this year with films like “Tick, Tick … Boom,” “The Power of the Dog” and “The Lost Daughter” vying for prizes. Like most other studios, it, too, has moved all in-person events for the month of January to virtual.                                                                                                                                                                                                                                                                                                                                                                                                               , “Last year was a tough adaptation, and it’s turning out that this year is also going to be about adapting to what’s going on in the moment,” Michael Barker, a co-president of Sony Pictures Classics, said in a telephone interview last week. He spoke while walking the frigid streets of Manhattan instead of basking in the sunshine of Palm Springs, where he was supposed to be honoring Penélope Cruz, his leading lady in the Oscar contender “Parallel Mothers.”                                                                                                                                                                                                                                                                                                                           , “You just compensate by doing what you can,” he said, “and once this passes, then you have to look at what the new world order will be.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/09/business/human-resources-pandemic-vaccines.html </td>
   <td style="text-align:left;"> 2022-01-09 18:00:08 </td>
   <td style="text-align:left;"> How the Pandemic Changed H.R. Jobs - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Vaccine mandates. Boosters. Exemptions. Testing protocol. Just a handful of public health questions that human resources departments now have to answer.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , By Emma Goldberg                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Gia Ganesh is a people person, so she loved running people operations — what many companies now call human resources — at Florence Healthcare. She led the health care technology company’s recruitment efforts, met with expecting moms planning for maternity leave and helped staff decide whether to spend their wellness benefits on therapy or a massage.                                                                                                                                                                                                                                                                                                                     , But like many working people, she found that the pandemic broke open her job description and filled it with new responsibilities. And like many human resources professionals, she found that she sometimes had to play a role akin to company nurse.                                                                                                                                                                                                                                                                                                                                                                                                                               , As Covid first started to spread, Ms. Ganesh made sure employees had stipends to set up work spaces at home and planned virtual activities, like a magic show and a cooking competition, to keep people connected. By last fall, she was in the meeting with the chief executive writing up her company’s vaccine mandate, which requires that all employees, even those working remotely, be fully vaccinated against the coronavirus. She reviews every request for a vaccine rule exemption from people who would rather submit to regular coronavirus testing.                                                                                                                  , “What happens if employees test positive for Covid? How do we take care of them, and the role, if they’re out for a significant period of time? There’s a lot of new complexity that Covid has brought to the world of H.R.,” said Ms. Ganesh, whose company has about 150 employees globally.                                                                                                                                                                                                                                                                                                                                                                                      , Just as the Covid-19 crisis made amateur epidemiologists of people trying to go about their daily lives, it also forced H.R. professionals, especially those at small and midsize businesses, into a new focus on public health. As companies weighed when to return to the office, whether to require coronavirus vaccines and what sort of exemptions from those rules to allow, it was often H.R. directors who were asked to lead those efforts. It was no longer sufficient for these professionals to manage the job satisfaction and career development of their colleagues. Suddenly, they were also charged with monitoring their health, safety and views on immunization., The added dimensions of H.R. jobs are coming into sharper focus now, as more organizations put vaccine mandates into effect. About 17 percent of American employers were requiring vaccinations or negative Covid tests for employees returning to the office, according to a Gallagher survey of more than 500 employers conducted between August and October.                                                                                                                                                                                                                                                                                                                     , Hovering over company conversations about vaccines is the additional consideration of whether to mandate booster shots. The Centers for Disease Control and Prevention has not updated its definition of “fully vaccinated” but said that being “up to date” on vaccination includes a booster. And some state and local leaders like Gov. Kathy Hochul of New York have indicated that they plan to include a booster requirement as well.                                                                                                                                                                                                                                         , Then there’s the tug of war over return to office plans, with the pull of executives eager to see workers in person meeting the push of soaring Covid case counts. On top of that has come the challenge of retaining talent when workers are walking off the job, with 4.5 million leaving their roles voluntarily in November. The sources of stress, for some H.R. directors, seem to multiply by the month.                                                                                                                                                                                                                                                                     , For George Boué, who ran H.R. at Stiles, a commercial real estate company based in Fort Lauderdale, Fla., the anxieties of his job began to increase this fall. He kept jerking awake at 3 a.m., his mind racing with questions. How was he going to roll out a vaccine mandate to his colleagues who viewed it as an intrusion? More important, how was he going to keep everybody in his office safe?                                                                                                                                                                                                                                                                             , Mr. Boué, who is fully vaccinated, was surrounded by friends in South Florida who were citing misinformation about the vaccine. He estimated that one-third of his 300-person staff is most likely not fully vaccinated. When the Labor Department rolled out its vaccine rule in November, requiring large businesses to get their workers vaccinated or tested weekly, Mr. Boué started drafting the terms for his company’s vaccine policy; then he put it on hold because of legal battles over the mandates, especially in Florida. Mr. Boué decided that among teammates he wouldn’t refer to the policy as a mandate, because he wanted to temper tensions whenever he could., “There’s those that are feeling the world is coming to an end, and this is horrible, and those on the other side of the spectrum that feel this is all a bunch of baloney,” he said. “The toughest part of my role has been trying to address all sides.”                                                                                                                                                                                                                                                                                                                                                                                                                           , His responsibilities continued to grow thornier since the start of the pandemic: In the early months, his team had to order gallons of disinfectant and hundreds of masks. Last summer, they had to start enforcing mask requirements in the office for unvaccinated employees, though his team did not ask for proof of vaccination for that rule and instead went by “the trust factor.”                                                                                                                                                                                                                                                                                          , Some executives are outsourcing Covid safety work to companies that set up turnkey vaccine and testing systems. DocGo, for example, a health care and technology company, creates testing programs for businesses and monitors the maintenance of employee confidentiality, data privacy and compliance with federal government standards.                                                                                                                                                                                                                                                                                                                                          , Still, Anthony Capone, DocGo’s president, said he hears regularly from H.R. directors, especially those worried that their unvaccinated workers will struggle to obtain Covid tests, which could mean employers are in violation of government guidelines.                                                                                                                                                                                                                                                                                                                                                                                                                          , H.R. professionals said they’re trying, wherever possible, to point toward government rules and to emphasize to employees that they’re simply following advice from public health authorities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , “I try not to be a doctor or a scientist,” said Amy Zimmerman, the chief people officer of Relay Payments, a software company based in Atlanta with just over 100 employees. “We’ve got institutions like the World Health Organization and the C.D.C. and really smart people who are making decisions that if you’re reasonable, you trust.”                                                                                                                                                                                                                                                                                                                                      , Still, there are plenty of scientific decisions — especially those on vaccine rule exemptions — that have to be made on a case-by-case basis, and they tend to fall to an H.R. team that doesn’t have scientific training.                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Ms. Zimmerman’s company currently allows its staff to work from home, but those coming into the office have to show proof of full vaccination. The requests for exemptions from that rule go straight to H.R. One involved concerns about fertility treatments, but the employee could not get a supporting doctor’s note and now cannot come into the office. Another was from an employee who had been previously infected with coronavirus, who Ms. Zimmerman’s team determined would have to show proof of antibodies every 90 days.                                                                                                                                            , Relay Payments also had two large in-person gatherings last year, where it required both proof of vaccination and a negative test 72 hours before arrival. Right before its December gathering, an employee who was fully vaccinated tested positive and skipped the event. Ms. Zimmerman was relieved that he caught the case before his flight from home, which she viewed as validation of the company’s move to require both vaccines and testing.                                                                                                                                                                                                                              , Now her team is weighing whether to mandate boosters. She said they might hold off on for now, though they would continue to follow C.D.C. recommendations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Making these kinds of decisions demands constant consumption of news by business leaders, with many seeking out online expertise about Covid: “The C.D.C. is my main source, but there’s multiple channels and mediums I’m plugged into,” said Ms. Ganesh, at Florence Healthcare.                                                                                                                                                                                                                                                                                                                                                                                                  , Mr. Boué, in South Florida, has finally hit his limit on H.R. angst. He retired at the end of last year. His wife works at a hospital, and with the anxieties she carries — about freezer trucks and overflowing beds — he feels he can’t take home his own set of work worries.                                                                                                                                                                                                                                                                                                                                                                                                    , Mr. Boué used to wake up raring to get to the office: “Even though I’m antisocial, I do enjoy working and helping people out,” he said. But the last two years have undercut that sense of enthusiasm: “There wasn’t a particular ‘Aha!’ moment,” he added. “I just realized the stress wasn’t good for me.”                                                                                                                                                                                                                                                                                                                                                                        , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/calendar?article=29128&amp;g=top&amp;importance=2&amp;startdate=2022-01-07 </td>
   <td style="text-align:left;"> 2022-01-08 21:21:54 </td>
   <td style="text-align:left;"> Week Ahead </td>
   <td style="text-align:left;"> The US, China, India and Brazil will be publishing inflation updates for December in the coming week, while GDP data from the UK and Germany and factory production numbers from the US, Eurozone, India and Mexico will also be keenly watched. Other important data to follow include US retail sales and consumer confidence, Japan current account and producer prices, and Australia trade balance and retail sales. The Bank of Korea will be deciding on monetary policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/08/business/teslas-computer-chips-supply-chain.html </td>
   <td style="text-align:left;"> 2022-01-08 18:00:12 </td>
   <td style="text-align:left;"> Why Tesla Soared as Other Automakers Struggled to Make Cars - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The yawning disparity between the performance of the electric car company and established automakers last year reflects the technological change roiling the industry.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , By Jack Ewing                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , For much of last year, established automakers like General Motors and Ford Motor operated in a different reality from Tesla, the electric car company.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , G.M. and Ford closed one factory after another — sometimes for months on end — because of a shortage of computer chips, leaving dealer lots bare and sending car prices zooming. Yet Tesla racked up record sales quarter after quarter and ended the year having sold nearly twice as many vehicles as it did in 2020 unhindered by an industrywide crisis.                                                                                                                                                                                                                                                                                                             , Tesla’s ability to conjure up critical components has a greater significance than one year’s car sales. It suggests that the company, and possibly other young electric car businesses, could threaten the dominance of giants like Volkswagen and G.M. sooner and more forcefully than most industry executives and policymakers realize. That would help the effort to reduce the emissions that are causing climate change by displacing more gasoline-powered cars sooner. But it could hurt the millions of workers, thousands of suppliers and numerous local and national governments that rely on traditional auto production for jobs, business and tax revenue., Tesla and its enigmatic chief executive, Elon Musk, have said little about how the carmaker ran circles around the rest of the auto industry. Now it’s becoming clear that the company simply had a superior command of technology and its own supply chain. Tesla appeared to better forecast demand than businesses that produce many more cars than it does. Other automakers were surprised by how quickly the car market recovered from a steep drop early in the pandemic and had simply not ordered enough chips and parts fast enough.                                                                                                                           , When Tesla couldn’t get the chips it had counted on, it took the ones that were available and rewrote the software that operated them to suit its needs. Larger auto companies couldn’t do that because they relied on outside suppliers for much of their software and computing expertise. In many cases, automakers also relied on these suppliers to deal with chip manufacturers. When the crisis hit, the automakers lacked bargaining clout.                                                                                                                                                                                                                      , Just a few years ago, analysts saw Mr. Musk’s insistence on having Tesla do more things on its own as one of the main reasons the company was struggling to increase production. Now, his strategy appears to have been vindicated.                                                                                                                                                                                                                                                                                                                                                                                                                                      , Cars are becoming increasingly digital, defined by their software as much as their engines and transmissions. It’s a reality that some old-line car companies increasingly acknowledge. Many, including Ford and Mercedes-Benz, have said in recent months that they are hiring engineers and programmers to design their own chips and write their own software.                                                                                                                                                                                                                                                                                                        , “Tesla, born in Silicon Valley, never outsourced their software — they write their own code,” said Morris Cohen, a professor emeritus at the Wharton School of the University of Pennsylvania who specializes in manufacturing and logistics. “They rewrote the software so they could replace chips in short supply with chips not in short supply. The other carmakers were not able to do that.”                                                                                                                                                                                                                                                                      , “Tesla controlled its destiny,” Professor Cohen added.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Tesla sold 936,000 cars globally in 2021, an 87 percent increase for the year. Ford, G.M. and Stellantis, the company formed from the merger of Fiat Chrysler and Peugeot, all sold fewer cars in 2021 than they did in 2020.                                                                                                                                                                                                                                                                                                                                                                                                                                            , Measured by vehicles delivered globally, Tesla vaulted past Volvo and Subaru in 2021, and some analysts predicted that it could sell two million cars this year, as factories in Berlin and Austin, Texas, come online and a plant in Shanghai ramps up production. That would put Tesla in the same league as BMW and Mercedes — something few in the industry thought possible just a couple of years ago.                                                                                                                                                                                                                                                             , G.M. and Ford, of course, sell many more cars and trucks. Both companies said last week that they sold around two million vehicles last year just in the United States.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Tesla, which rarely answers questions from reporters, did not respond to a request for comment for this article. It has said little publicly about how it managed to soar in a down market.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , “We have used alternative parts and programmed software to mitigate the challenges caused by these shortages,” the company said in its third-quarter earnings report.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The performance is a stark turnaround from 2018, when Tesla’s production and supply problems made it an industry laughingstock. Many of the manufacturing snafus stemmed from Mr. Musk’s insistence that the company make many parts itself.                                                                                                                                                                                                                                                                                                                                                                                                                             , Other car companies have realized that they need to do some of what Mr. Musk and Tesla have been doing all along and are in the process of taking control of their onboard computer systems.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Mercedes, for example, plans to use fewer specialized chips in coming models and more standardized semiconductors, and to write its own software, said Markus Schäfer, a member of the German carmaker’s management board who oversees procurement.                                                                                                                                                                                                                                                                                                                                                                                                                      , In the future, Mercedes will “make sure we have customized, standardized chips in the car,” Mr. Schäfer said in an interview on Wednesday. “Not one thousand different chips.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Mercedes will also design its own vehicle hardware, he said. Without mentioning Tesla, Mr. Schäfer added, “Probably some others were earlier going down this road.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Doing more on its own also helps explain why Tesla avoided shortages of batteries, which have limited companies like Ford and G.M. from selling lots of electric cars. In 2014, when most carmakers were still debating whether electric vehicles would ever amount to anything, Tesla broke ground on what it called a gigafactory outside Reno, Nev., to produce batteries with its partner, Panasonic. Now, that factory helps ensure a reliable supply.                                                                                                                                                                                                              , “It was a big risk,” said Ryan Melsert, a former Tesla executive who was involved in construction of the Nevada plant. “But because they have made decisions early on to bring things in house, they have much more control over their own fate.”                                                                                                                                                                                                                                                                                                                                                                                                                        , As Professor Cohen of Wharton pointed out, Tesla’s approach is in many ways a throwback to the early days of the automobile, when Ford owned its own steel plants and rubber plantations. In recent decades, the conventional auto wisdom had it that manufacturers should concentrate on design and final assembly and farm out the rest to suppliers. That strategy helped reduce how much money big players tied up in factories, but left them vulnerable to supply chain turmoil.                                                                                                                                                                                   , The pandemic sparked the problem. The highly intricate and interconnected global supply chain is in upheaval. Much of the crisis can be traced to the outbreak of Covid-19, which triggered an economic slowdown, mass layoffs and a halt to production. Here’s what happened next:                                                                                                                                                                                                                                                                                                                                                                                      , A reduction in shipping. With fewer goods being made and fewer people with paychecks to spend at the start of the pandemic, manufacturers and shipping companies assumed that demand would drop sharply. But that proved to be a mistake, as demand for some items would surge.                                                                                                                                                                                                                                                                                                                                                                                          , Demand for protective gear spiked. In early 2020, the entire planet suddenly needed surgical masks and gowns. Most of these goods were made in China. As Chinese factories ramped up production, cargo vessels began delivering gear around the globe.                                                                                                                                                                                                                                                                                                                                                                                                                   , Then, a shipping container shortage. Shipping containers piled up in many parts of the world after they were emptied. The result was a shortage of containers in the one country that needed them the most: China, where factories would begin pumping out goods in record volumes                                                                                                                                                                                                                                                                                                                                                                                       , Demand for durable goods increased. The pandemic shifted Americans’ spending from eating out and attending events to office furniture, electronics and kitchen appliances – mostly purchased online. The spending was also encouraged by government stimulus programs.                                                                                                                                                                                                                                                                                                                                                                                                   , Strained supply chains. Factory goods swiftly overwhelmed U.S. ports. Swelling orders further outstripped the availability of shipping containers, and the cost of shipping a container from Shanghai to Los Angeles skyrocketed tenfold.                                                                                                                                                                                                                                                                                                                                                                                                                                , Labor shortages. Businesses across the economy, meanwhile, struggled to hire workers, including the truck drivers needed to haul cargo to warehouses. Even as employers resorted to lifting wages, labor shortages persisted, worsening the scarcity of goods.                                                                                                                                                                                                                                                                                                                                                                                                           , Component shortages. Shortages of one thing turned into shortages of others. A dearth of computer chips, for example, forced major automakers to slash production, while even delaying the manufacture of medical devices.                                                                                                                                                                                                                                                                                                                                                                                                                                               , A lasting problem. Businesses and consumers reacted to shortages by ordering earlier and extra, especially ahead of the holidays, but that has placed more strain on the system. These issues are a key factor in rising inflation and are likely to last for months — if not longer.                                                                                                                                                                                                                                                                                                                                                                                    , It also helps that Tesla is a much smaller company than Volkswagen and Toyota, which in a good year produce more than 10 million vehicles each. “It’s just a smaller supply chain to begin with,” said Mr. Melsert, who is now chief executive of American Battery Technology Company, a recycling and mining firm.                                                                                                                                                                                                                                                                                                                                                      , The Tesla lineup is also more modest and easier to supply. The Model 3 sedan and Model Y sport utility vehicle accounted for almost all of the company’s sales in 2021. Tesla also offers fewer options than many of the traditional carmakers, which simplifies manufacturing.                                                                                                                                                                                                                                                                                                                                                                                          , “It’s a more streamlined approach,” said Phil Amsrud, a senior principal analyst who specializes in automotive semiconductors at IHS Markit, a research firm. “They are not trying to manage all these different configurations.”                                                                                                                                                                                                                                                                                                                                                                                                                                        , Tesla software, which can be updated remotely, is considered the most sophisticated in the auto business. Even so, the company’s cars likely use fewer chips, analysts said, because the company controls functions like battery cooling and autonomous driving from a smaller number of centralized, onboard computers.                                                                                                                                                                                                                                                                                                                                                 , “Tesla has fewer boxes,” Mr. Amsrud said. “The fewer the components you need right now, the better.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Of course, Tesla could still run into problems as it tries to replicate the growth it achieved in 2021 — it is aiming to increase sales about 50 percent a year for the next several years. The company acknowledged in its third-quarter report that its creative maneuvering around supply chain chaos might not work so well as it increased production and needed more chips and other parts.                                                                                                                                                                                                                                                                        , The electric vehicle market is also becoming much more competitive as the traditional carmakers belatedly respond with models that people want to buy rather than the small electric vehicles typically made to appease regulators. Ford said this past week that it would nearly double production of the Lightning, an electric version of its popular F-150 pickup truck, because of strong demand. Tesla’s pickup truck won’t go on sale for at least another year.                                                                                                                                                                                                  , The outlook for the traditional carmakers is likely to improve this year as shortages of semiconductors and other components ease, and as manufacturers get better at coping.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Tesla vehicles still suffer from quality problems. The company told regulators in December that it planned to recall more than 475,000 cars for two separate defects. One could cause the rearview camera to fail, and the other could cause the front hood to open unexpectedly. And federal regulators are investigating the safety of Tesla’s Autopilot system, which can accelerate, brake and steer a car on its own.                                                                                                                                                                                                                                               , “Tesla will continue to grow,” said Stephen Beck, managing partner at cg42, a management consulting firm in New York. “But they are facing more competition than they ever have, and the competition is getting stronger.”                                                                                                                                                                                                                                                                                                                                                                                                                                               , The carmaker’s fundamental advantage, which allowed it to sail through the chip crisis, will remain, however. Tesla builds nothing but electric vehicles and is unencumbered by habits and procedures that have been rendered obsolete by new technology. “Tesla started from a clean sheet of paper,” Mr. Amsrud said.                                                                                                                                                                                                                                                                                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/08/business/management-jerks.html </td>
   <td style="text-align:left;"> 2022-01-08 18:00:09 </td>
   <td style="text-align:left;"> No More Working for Jerks! - The New York Times </td>
   <td style="text-align:left;"> , For almost two years, couches have been cubicles. Colleagues are instant message avatars. And people are reconsidering how much they should have to put up with from a boss.                                                                                                                                                                                                                                                                                          , Credit...Nicolas Ortega                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                          , By Emma Goldberg                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The honeymoon phase at Better.com opened with freebies galore. The employees did Zoom scavenger hunts. They did Zoom cooking classes. They were sent tequila and chocolate milk powder and pine boxes branded with the company’s name. They competed for giveaways, including a Peloton. This was the land of corporate-meets-summer-camp, where lunches were covered and training sessions featured funny hats.                                                      , Christian Chapman, 41, compared his feelings during Better.com’s orientation to the head rush of a new relationship. The perks were bountiful, the mission was sound and Mr. Chapman, a mortgage underwriting trainer, fell fast and hard. “LGTM!” he and his teammates cheered, which stood for “Let’s Get That Money.”                                                                                                                                              , Soon, though, there were red flags. Most notable was a video call last summer when Vishal Garg, the company’s chief executive, unleashed an expletive-laden monologue about beating the competition, prompting Mr. Chapman to hit mute and usher his young daughter out of the room.                                                                                                                                                                                  , Then, last month, Mr. Garg summoned 900 Better.com employees, including Mr. Chapman, roughly 9 percent of his staff, and fired them in a Zoom call that was recorded and shared online. Mr. Garg later apologized, but just over one week afterward, the company’s board announced that the founder and chief executive was “taking time off” from his role.                                                                                                          , For almost two years, couches have been offices. Colleagues are instant message avatars. And a work force that had shocking changes imposed on it has reconsidered its basic assumptions about how people treat each other in corporate life.                                                                                                                                                                                                                         , “The tolerance for dealing with jerky bosses has decreased,” observed Angelina Darrisaw, chief executive of the firm C-Suite Coach, who saw a spike of interest in her executive coaching services last year. “You can’t just wake up and lead people,” she added. “Companies are thinking about how do we make sure our managers are actually equipped to manage.”                                                                                                   , The scrutiny of workplace behavior comes after several years of high-profile conversation about appropriate office conduct. The #MeToo movement propelled dozens of executives to step down after accusations of sexual assault. The Black Lives Matter protests after the killing of George Floyd prompted corporate leaders to issue apologies for past discriminatory behaviors and the lack of racial diversity in their work forces and to pledge to make amends., And increasingly, as people’s work routines have been upended by the pandemic, they’ve begun to question the thrum of unpleasantness and accumulation of indignities they used to shrug off as part of the office deal. Some are saying: no more working for jerks.                                                                                                                                                                                                   , But it is not illegal to be a jerk, which introduces a hiccup into that mean-colleague reckoning. The definition of a bully is often in the eye of the coffee-fetcher.                                                                                                                                                                                                                                                                                                , The pop culture archetype of recent years is the ice queen with standards higher than her stiletto heels, Meryl Streep as Miranda Priestly (a thinly veiled Anna Wintour) in “The Devil Wears Prada.” The sort of boss who might ask, of an assistant: “Is there some reason that my coffee isn’t here? Has she died or something?”                                                                                                                                   , In real life, jerk behavior exists on a spectrum of cringe. There is the founder, whose vision and ambition can make it difficult for staff to question his temper — like Mr. Garg, who accused the employees he fired of “stealing” from the company by putting in too few hours. (In response to requests for comment, Better.com pointed to Mr. Garg’s early December apology for the way he had executed the layoffs.)                                            , There’s the example of the Hollywood mogul Scott Rudin, who made critically acclaimed art, and also threw staplers at underlings. (He later apologized.)                                                                                                                                                                                                                                                                                                              , There’s millennial hustle culture unhinged: Away’s former chief executive, Steph Korey, who demanded loyalty and Slack activity at all hours of the day and night. “I hope everyone in this group appreciates the thoughtfulness I’ve put into creating this career development opportunity,” she wrote in a message telling her staff to stop requesting time off. (Ms. Korey apologized, too.)                                                                      , And then there’s the self-determined type, like Oracle’s Larry Ellison, who referred to his own leadership style as MBR, for “management by ridicule.”                                                                                                                                                                                                                                                                                                                , “You’ve got to be good at intellectual intimidation and rhetorical bullying,” Mr. Ellison once said.                                                                                                                                                                                                                                                                                                                                                                  , (He later disavowed this as the strategy of an “inexperienced and insecure” C.E.O.)                                                                                                                                                                                                                                                                                                                                                                                   , Tessa West, a social psychologist at New York University, wrote a field guide to bad personalities, called “Jerks at Work,” that sketches out a handful — the bulldozer, the free rider, the gaslighter and the kiss up/kick downer. Many of her examples are of bosses, who tend to be harder to report.                                                                                                                                                             , For Ms. West, the quest is personal. Her own encounter with a workplace jerk came during graduate school at the University of Connecticut, when a peer resorted to creative forms of sabotage: giving Ms. West the wrong time for a meeting so that she would arrive late, calling her clothing overly sexualized. (“I dressed like a California girl,” Ms. West said.)                                                                                               , Because the comments did not seem clearly in violation of any code of conduct aside from basic manners, Ms. West hesitated to escalate the issue.                                                                                                                                                                                                                                                                                                                     , “The climate has changed,” Ms. West reflected. “I think we now recognize these behaviors are really inappropriate.”                                                                                                                                                                                                                                                                                                                                                   , Reporting to work has always meant accepting a variety of unpleasantries: commutes, precoffee chitchat, people who would like you to do what they tell you to do even if it’s not yet 10 a.m.                                                                                                                                                                                                                                                                         , But for some, the last year has rebalanced the power seesaw between worker and boss. Maybe it was the surge of people quitting: A record high 4.5 million Americans voluntarily left their jobs in November. Maybe it was the ebbing will-they-won’t-they tides of return to office plans. Whatever the change, more workers are feeling empowered to call out their managers.                                                                                        , “For the entirety of my career, I would hear this phrase, ‘Be your full self at work,’ and that meant wearing a pop of color,” Ms. Darrisaw said. “Now it means making time for meditation with your team, making time for conversations about how the company is showing up to support your community.”                                                                                                                                                              , Jacquelyn Carter, 26, did not think she was going to quit her job at the start of the pandemic. She was working at a nonprofit in Houston, and she had been taught by her mother, who had worked at the same place for 30 years, that it was important to stick with a team for as long as possible.                                                                                                                                                                  , But the slights started to add up. Some colleagues regularly forgot her name. Others talked over her in meetings. A manager at the organization called an idea of hers “stupid.”                                                                                                                                                                                                                                                                                      , And, as a Black woman, she found herself fielding insensitive remarks from white colleagues.                                                                                                                                                                                                                                                                                                                                                                          , “When you get to be home in your own space, you realize, ‘I don’t have to deal with someone passing me in the hallway and commenting on my hair,’” she said.                                                                                                                                                                                                                                                                                                          , She watched TikToks of other people celebrating their decisions to leave jobs they didn’t like — QuitTok — with its posts featuring Destiny’s Child’s “Bills, Bills, Bills” and Cardi B’s “Money.” One prime example of the genre: A trio of women dance their way offscreen to text that reads: “the company would rather lose 3 reliable hard working employees than fix their toxic management.”                                                                   , Ms. Carter decided that a mean colleague was as good a reason as any to leave her employer, so she started looking for new opportunities, and then joined Ms. Darrisaw’s firm.                                                                                                                                                                                                                                                                                        , The bad-boss-goodbye posts also inspired some to jump from retail to office jobs, including Kristofer Flatt, 23, who used to work at a big-box store in Arkansas. He said his managers ignored his pleas for more protective gear, gave him time-consuming tasks with no explanations — “change the item in that aisle to charcoal, not birdseed” — and questioned his request to take time off for a funeral. In spring 2020, he quit and moved to a corporate job.  , “If you’re a business leader and you want to recruit the best talent you can, you need to start prioritizing and doing the work of creating conscious culture,” said Janine Yancey, who runs Emtrain, which provides workplace trainings.                                                                                                                                                                                                                             , “Over the last couple decades, companies have not invested as much time and resources in developing leadership and management skills,” she said. “Everyone’s focused on the technical skills, the what, but not necessarily the how.”                                                                                                                                                                                                                                 , Ms. Yancey used to work as an employment lawyer. But she came to feel that the workplace changes she wanted to see wouldn’t be brought about solely by legal reform, something reaffirmed in 2015 when she watched Ellen Pao lose her gender discrimination lawsuit against the venture capital firm Kleiner Perkins Caufield &amp; Byers: “The laws are the bare minimum,” Ms. Yancey said. “Society has to change.”                                                     , Shani Ospina’s work is trying to accelerate that change. She is a professional jerk patroller. An executive coach who works with Strategyzer, a software and consulting company, she conducts 90-minute screenings during the interview process to assess the personality fit of job candidates, helping to enforce the company’s emphasis on being a team player.                                                                                                    , “What aspect of yourself are you most proud of?” Ms. Ospina starts out by asking. Then she gets deeper: “What aspect about yourself would you most like to change?” (She braces for the wince-inducing “I got promoted a year later than I’d hoped.”)                                                                                                                                                                                                                 , Ms. Ospina’s process is guided by the idea that most people are petty sometimes, but what separates the average person from the hard-core jerk is the capacity to recognize failures and try to improve.                                                                                                                                                                                                                                                              , One of Strategyzer’s founders, Alex Osterwalder, says common jerk qualities are blaming colleagues, refusing feedback and talking about people behind their backs. He believes that screening for nonjerkiness is just as important as looking for technical skills.                                                                                                                                                                                                  , Jerkiness, like incompetency, takes a toll on productivity. And competent jerks who rise through the ranks can have wide-reaching effects, especially in a corporate culture that puts more emphasis on output than on how the work gets done. People get gold stars for performance, not collegiality.                                                                                                                                                               , Baird, the financial services firm, took the principle a step further by codifying it in policy. Employees are informed during their orientation of the company’s “no asshole rule” — it’s even written into training material. Leslie Dixon, the head of human resources, has fired people for violating it.                                                                                                                                                         , “By putting it out there in print and talking about it when they’re onboarded and throughout their career, it fosters a very open conversation about behavior that’s not illegal but that can be uncomfortable,” Ms. Dixon said.                                                                                                                                                                                                                                      , Like the team at Strategyzer, the enforcers of Baird’s policy realize rudeness isn’t an immutable trait. People aren’t fired for slip-ups. Even Beth Kavelaris, director of culture and integration at the company, said she got feedback years ago that helped her rethink her own conduct.                                                                                                                                                                          , “It was from my boss, who said, ‘You’ve got to learn to listen better, Beth,’ and I think I interrupted her while she was telling me that,” Ms. Kavelaris recalled. “I’ve gotten better. I haven’t been told that in a long while.”                                                                                                                                                                                                                                   , Last month, Mr. Garg, who had fired 900 people over Zoom, posted an apology to his Better.com team. “I failed to show the appropriate amount of respect and appreciation for the individuals who were affected,” he wrote, and he pledged to do better. The note concluded with a promise to be transparent and share 2022 goals.                                                                                                                                     , His reckoning came at a moment when nearly every company shares the same goal: keeping talent. Nobody can hit metrics if they don’t have a staff.                                                                                                                                                                                                                                                                                                                     , And many are realizing that there’s nothing that thins out a work force like misbehavior. Ms. Darrisaw, for example, of C-Suite Coach, helps companies assess how they can improve their culture. “Are more people trying to leave certain teams?” she asks clients. “That often tells you what the management style is like.”                                                                                                                                        , Sometimes workers can name and shame their meaner colleagues — but in other cases, that job falls to those resigning instead. Which means quitting season might spell trouble for the jerks.                                                                                                                                                                                                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/john-legend-sells-music-catalog-kkr-bmg </td>
   <td style="text-align:left;"> 2022-01-08 17:33:37 </td>
   <td style="text-align:left;"> John Legend sells his music catalog to KKR, BMG </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , KKR &amp; Co. Inc. and BMG have acquired the songwriting catalog of John Legend.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The deal, disclosed in a regulatory filing, closed last fall and illustrates how red-hot the market for music investments has become. Mr. Legend, at 47 years old—still an active songwriter, recording artist, and performer—is younger and earlier in his career than many of his peers who have been inking deals to help set up their legacies and cash in on their life’s work.                                                                                                                                                                                                                                            , The R&amp;B crooner sold his publishing copyrights and the rights to receive royalties from music he penned from 2004 through early 2021. BMG Rights Management and KKR each purchased a 50% stake in the catalog. BMG, which has been administering Mr. Legend’s work since it bought Cherry Lane Music Publishing in 2010, also struck a deal to administer his future compositions, according to a person familiar with the matter. BMG, both a record label and publisher, is a subsidiary of Germany’s Bertelsmann SE.                                                                                                         , JOHN LEGEND GETS INVOLVED IN THE BOOK-PUBLISHING BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , One upshot of KKR and BMG’s investment in Mr. Legend’s work thus far is that his future releases and tours are likely to generate continued attention and streaming of his catalog. The deal encompasses Mr. Legend’s acclaimed 2004 debut album "Get Lifted" as well as hits like "All of Me" and "Love Me Now."                                                                                                                                                                                                                                                                                                               , John Legend appears at the Vanity Fair Oscar Party in Beverly Hills, California, on Feb. 9, 2020.  ( Associated Press / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , KKR last March teamed up with BMG to spend at least $1 billion on music copyrights. That commitment came amid a broader move into music last year for KKR, which last January struck a $200 million deal for a majority stake in Ryan Tedder’s catalog of hits including songs from Beyoncé, Adele, Stevie Wonder and Mr. Tedder’s band, OneRepublic. (Mr. Tedder, now 42 years old, was another relatively young entrant to the market.) In October, KKR spent $1.1 billion on investment advisory firm Kobalt Capital Ltd.’s KMR Music Royalties II portfolio, which includes more than 62,000 copyrights across music genres., CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Together, KKR and BMG last month invested in Texas blues-rock trio ZZ Top’s publishing catalog and recording music royalties in a deal valued around $50 million, according to people familiar with the deal.                                                                                                                                                                                                                                                                                                                                                                                                                   , Fueled by strong demand from legacy publishing outfits and financial players alike, as well as low interest rates and tax incentives, an onslaught of artists have been striking deals for their music rights, including Stevie Nicks, Bob Dylan, Neil Young and Bruce Springsteen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/starbucks-workers-at-arizona-store-to-hold-union-vote </td>
   <td style="text-align:left;"> 2022-01-08 17:04:58 </td>
   <td style="text-align:left;"> Starbucks workers at Arizona store to hold union vote </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                           , A Starbucks location in Arizona could be the next to have workers unionize after being granted a request to hold an election.                                                                                                                                                                                               , A U.S. labor official granted the request, rejecting the company’s arguments against holding store-by-store votes.                                                                                                                                                                                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                 , In a Friday ruling, the National Labor Relations Board's regional director ordered that ballots be mailed out Jan. 14 to employees at a store in Mesa, Arizona, according to Bloomberg.                                                                                                                                     , The regional director ruled that the employees of a single worksite constitute an appropriate voter pool for a union election.                                                                                                                                                                                              , Employees at the store have until Jan. 28 to return their ballots.                                                                                                                                                                                                                                                          , STARBUCKS SAYS IT WILL NEGOTIATE IN GOOD FAITH WITH FIRST UNIONIZED STORE                                                                                                                                                                                                                                                   , The ruling follows a labor victory last month in which Starbucks employees in New York voted to establish the first unionized restaurant among the coffee chain’s thousands of corporate-run U.S. sites.                                                                                                                    , Starbucks employee Brian Murray, center, and other employees and supporters react as votes are read during a viewing party for their union election on Thursday, Dec. 9, 2021, in Buffalo, New York. (Associated Press / AP Newsroom)                                                                                       , The movement to unionize has gained momentum since as workers in cities including Boston; Chicago; Knoxville, Tennessee; and Starbucks’ hometown of Seattle all have petitioned to unionize.                                                                                                                                , The labor group representing the New York and Arizona workers is the Service Employees International Union affiliate Workers United.                                                                                                                                                                                        , STARBUCKS TO REQUIRE COVID-19 VACCINE OR WEEKLY TESTING FOR EMPLOYEES                                                                                                                                                                                                                                                       , In response to the Friday ruling, a Starbucks spokesperson referenced a December letter to employees at the New York store in which the company’s North America president Rossann Williams said, "We do not want a union between us as partners," but that "we respect the legal process," and "will bargain in good faith.", CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                     , Employees at the newly unionized New York store have staged a walkout since Wednesday over what they say are insufficient COVID-19 safeguards and staffing.                                                                                                                                                                 , Starbucks has said it exceeds guidelines from experts and the Centers for Disease Control and Prevention </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/chinese-man-pleads-guilty-to-stealing-monsanto-trade-secret </td>
   <td style="text-align:left;"> 2022-01-08 14:42:40 </td>
   <td style="text-align:left;"> Chinese man pleads guilty to stealing Monsanto trade secret </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                   , A Chinese national admitted in federal court Thursday that he stole a trade secret when he worked for Monsanto and one of its subsidiaries in Missouri, federal prosecutors said.                                                   , Haitao Xiang, 44, formerly of Chesterfield, Missouri, pleaded guilty to conspiracy to commit economic espionage. He was indicted by a grand jury on eight charges in 2019.                                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                         , Prosecutors said in a news release that Xiang transferred a trade secret to a memory card and then attempted to take it to China for the benefit of the Chinese government.                                                         , FILE PHOTO: Monsanto's research farm is pictured near Carman, Manitoba, Canada REUTERS/Zachary Prong/File Photo ( REUTERS/Zachary Prong/File Photo / Reuters Photos)                                                                , Xiang worked as an imaging scientist for Monsanto and one of its subsidiaries, The Climate Corporation, from 2008 to 2017.                                                                                                          , COUPLE'S $86M AWARD IN MONSANTO PESTICIDE CASE STANDS                                                                                                                                                                               , Court records say Monsanto and The Climate Corporation developed a digital online farming software platform to help farmers collect field data to increase productivity.                                                            , Part of the platform was an algorithm called the Nutrient Optimizer, which the companies considered a trade secret and their intellectual property, prosecutors said.                                                               , In June 2017, the day after leaving employment with the companies, Xiang tried to fly to China. During a search, investigators found one of Xiang’s electronic devices contained copies of the Nutrient Optimizer, prosecutors said., CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                             , Xiang flew to China, where he worked for the Chinese Academy of Science’s Institute of Soil Science. He was arrested when he returned to the United States.                                                                         , He will be sentenced April 7. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/kudlow-bidens-2-trillion-boondoggle-spending-bill-last-winter-caused-inflation </td>
   <td style="text-align:left;"> 2022-01-08 06:12:25 </td>
   <td style="text-align:left;"> Kudlow: Biden's $2 trillion boondoggle spending bill last winter caused inflation </td>
   <td style="text-align:left;"> ‘Kudlow’ discusses Biden’s 'socialist' agenda as inflation continues to soar across the nation.                                                                                                                                                                                                                                                                                                                                                                                                                                        , We begin with a rare economic declaration from our President Joe Biden, which we will now record for posterity. Take a listen:                                                                                                                                                                                                                                                                                                                                                                                                         , Biden: "For too long Republicans have thrown around terms like pro-growth and supply-side economics to drive an economic agenda that didn't deliver enough growth and supplied more wealth to those who already were very well-off. From day one, my economic agenda has been different. It's been about taking a fundamentally new approach to our economy                                                                                                                                                                            , That's right, Joe. We have a brand-new approach to our economy. You have generated the first serious bout of inflation in 40 decades. Nice going! This could not have been easy! The Fed has been trying to get inflation above their 2% target for years and years. You just did it in 9 months!                                                                                                                                                                                                                                      , BIDEN TOUTS UNEMPLOYMENT DECLINE, IGNORES DISAPPOINTING JOB REPORT                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Nice going, sir. It's called way too much government spending to boost demand and way too many taxes and regulations to choke-off supply. What you should do in the new year is dump your advisers and make Senator Joe Manchin the chair of your Council of Economic Advisers. Why? Because he was completely right about his high inflation forecast. He's been right all year, and that's why we're saving America, and killing the bill – your $2 trillion boondoggle spending bill last winter contributing mightily to inflation., The Federal Reserve enabled it and distinguished Democratic economists like Larry Summers and Jason Furman told you so, along with Joe Manchin.                                                                                                                                                                                                                                                                                                                                                                                        , Now, if you slap on another $5 trillion of spending – which you have tried awfully hard to do but have failed, and will continue to fail – we'll hit double-digit inflation.                                                                                                                                                                                                                                                                                                                                                           , NatWest Markets global economics co-head Michelle Girard analyzes the December jobs report on 'Making Money.'                                                                                                                                                                                                                                                                                                                                                                                                                          , You're right, sir. You have triggered a fundamentally new approach to our economy, a big inflation which inevitably will lead to a big recession in a couple of years. So, thank you for that.                                                                                                                                                                                                                                                                                                                                         , Maybe you can haul out Vice President Kamala Harris, who will put your new economic thinking in the same historical pantheon as Pearl Harbor and 9/11.                                                                                                                                                                                                                                                                                                                                                                                 , STEVE MOORE BLAMES POOR JOB REPORT ON EXPANSION OF WELFARE PROGRAMS                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Now, as for your attack on supply-side growth economics, I invite your attention to some actual factoids in a recent piece by Trump economic advisers Kevin Hassett and Tyler Goodspeed. Using government factoids, they note that in 2019 alone real median household income rose by $4,400 - a bigger increase in one year than even the combined totals during the Bush and Obama administrations. Real wages for the bottom 10% of the distribution rose 8.4% while real wages for the top 10% rose only 5.2%.                     , VARNEY: KAMALA HARRIS IS A PROBLEM FOR THE DEMOCRATIC PARTY                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Real wealth for the bottom half of income earners rose an incredible 28.4% while that of the top 1% rose only 8.9%.                                                                                                                                                                                                                                                                                                                                                                                                                    , Business investment surged as did labor productivity growth, which is why real wages for the middle class increased far more than for the upper-end folks.                                                                                                                                                                                                                                                                                                                                                                             , By the way, Trump tax policy imposed a severely lower cap for the rich blue state deductions for state and local taxes. You want to subsidize the blue state rich. President Trump's supply-side policies led to a middle-class, blue-collar boom throughout the country.                                                                                                                                                                                                                                                              , The Melting Pot CEO Bob Johnston discusses how the pandemic and COVID protocols have impacted the service industry.                                                                                                                                                                                                                                                                                                                                                                                                                    , Unemployment among minority groups – African Americans, Hispanic Americans, Asian Americans – [and] women, dropped to 50-year lows and in some cases, even more. Poverty fell substantially. So did inequality.                                                                                                                                                                                                                                                                                                                        , But Uncle Joe, your big government socialism plan to spend, tax and regulate the entire economy is losing ground on almost every one of these fronts.                                                                                                                                                                                                                                                                                                                                                                                  , Your single achievement with your so-called fundamentally new approach to the economy is a massive inflation tax on middle-class working folks, and even more on the lowest income folks.                                                                                                                                                                                                                                                                                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , And Uncle Joe, as you were reading across your teleprompter this morning, attacking supply-side economics, let the record show that as a senator you voted for Ronald Reagan’s hugely successful supply-side tax cut packages in both 1981 and 1986.                                                                                                                                                                                                                                                                                   , So either you were smarter back then, or you've become a hypocrite right now. May I remind you that Democrat John F. Kennedy was the first post-World War II supply-side tax cutter, and it led to massive across-the-board prosperity. Then came Reagan, and then came Trump.                                                                                                                                                                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Lower taxes, with their incentives to work and invest, boost prosperity and reduce inflation. As Art Laffer reminds us, tax something more, and you get less of it. Tax something less, and you get more of it.                                                                                                                                                                                                                                                                                                                        , Somebody should add that to your teleprompter, Mr. President. It was Kennedy who first said a rising tide lifts all boats. Somebody should add that to your teleprompter. Come to think of it, sir, just throw the whole teleprompter out and get yourself a new one, this time backed up by some common sense economic thinkers.                                                                                                                                                                                                      , And that's my Riff.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , This article is adapted from Larry Kudlow's opening commentary on Jan. 7, 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/reddit-chooses-bankers-ahead-potential/story.aspx?guid={28768F38-AA8E-4713-B3CA-ECFFA4963A94}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-08 05:56:16 </td>
   <td style="text-align:left;"> Reddit chooses bankers ahead of potential March IPO: report - MarketWatch </td>
   <td style="text-align:left;"> San Francisco-based social-media company Reddit Inc. has picked Morgan Stanley and Goldman Sachs to help it go public as soon as March, according to a Bloomberg report late Friday that cited people with knowledge of the matter. The people said the company, home of meme-stock message board WallStreetBets and countless others, could be valued at as much as $15 billion in an initial public offering. Reddit announced in December it had confidentially filed for an IPO. The company was valued at around $10 billion after a funding round in August. , Found dead in hotel room at the Ritz-Carlton in Orlando, according to the sheriff's department. No cause of death had been determined. Saget had performed Saturday in Jacksonville, Fla.                                                                                                                                                                                                                                                                                                                                                                          , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-08 05:21:31 </td>
   <td style="text-align:left;"> Canadian Stocks Extend Gains </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite Index edged 0.1% higher to close at the 21,084 level on Friday, as investors balanced fresh domestic and US labor market data. The Canadian economy added 54.7 thousand jobs during December, nearly twice as much as markets expected. On the other hand, the latest US payroll data indicated 199 thousand jobs were added statewide, less than half of market forecasts, even though the jobless rate fell to a pandemic low. On the corporate front, energy stocks traded 0.9% higher to extend last session’s gains. Cameco Corp gained after announcing it could resume yearly production of 24 million pounds of uranium in North America if Kazatomprom’s supply chains were to be interrupted due to Kazakhstan’s political turmoil. On the week, the index extended losses and fell 0.7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-08 05:15:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Extend Gains On Friday </td>
   <td style="text-align:left;"> The Ibovespa stock index rose 1% to close at 102,523 on Friday, founding some support in rising iron ore prices, while investors digest the latest US jobs report which is unlikely to change the direction of the Fed's monetary policy towards a reduction of economic stimulus much faster. On corporate news, Brazilian state-run oil company Petrobras said it expects to sell 100% of its preferred stake in petrochemical producer Braskem by February. Still, the index extended the losses for the third consecutive week and fell 2.3%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-08 05:02:00 </td>
   <td style="text-align:left;"> Wall Street Wavers after Payrolls Report </td>
   <td style="text-align:left;"> US stocks traded mixed on Friday, as investors digested the latest payrolls report which reinforced the view that Fed may accelerate its timeline for rate hikes. Although only 199K jobs were created in December, less than half of the market forecasts, the jobless rate fell to 3.9% and hourly wages surged 4.7% from a year ago. The Dow Jones was little changed after falling 0.3% earlier in the session as gains in bank stocks amid expectations of higher yields were offset by tech losses. Meanwhile, the S&amp;P slipped 0.4% and the tech-heavy Nasdaq Composite dropped 1% to book its worst week since February 2021, down more than 4%. Among single stocks, chipmakers such as Nvidia and Microchip more than 4%. Also, Tesla erased 3.5% and Netflix lost 2%. Still, on the week, the S&amp;P traded 1.9% lower and the Dow Jones slipped 0.3%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/consumer-credit </td>
   <td style="text-align:left;"> 2022-01-08 04:03:43 </td>
   <td style="text-align:left;"> US Consumer Credit Tops Forecasts </td>
   <td style="text-align:left;"> Consumer credit in the United States increased by USD 39.991 billion in November of 2021, following a downwardly revised USD 16 billion gain in the previous month and above market expectations of a USD 19.5 billion rise. Revolving credit increased by USD 19.838 billion while non-revolving credit went up by USD 20.15 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dr-horton-stock-sinks-lead/story.aspx?guid={CCB252D5-0323-4F23-8268-9263AC8DFCED}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-08 03:59:06 </td>
   <td style="text-align:left;"> D.R. Horton stock sinks to lead the S&amp;P 500's losers as rising Treasury yields weigh on home builders - MarketWatch </td>
   <td style="text-align:left;"> Shares of D.R. Horton Inc. 
        DHI,
        -6.17%
       sank 5.8% in afternoon trading Friday, enough to pace the S&amp;P 500's 
        SPX,
        -0.41%
       decliners, as the continued rise in Treasury yields and mortgage rates weighs heavily on the home-builders sector. D.R. Horton's stock has now tumbled 11.9% this week, which would make it the biggest weekly drop since it slid 12.9% during the week ended April 3, 2020. Elsewhere, shares of Lennar Corp. 
        LEN,
        -4.74%
       dropped 3.9% and Toll Brothers Inc. 
        TOL,
        -4.42%
       slid 3.6%, while the iShares U.S. Home Construction ETF 
        ITB,
        -4.53%
       gave up 3.8%. Also getting hit was home-improvement retailer Home Depot Inc.'s stock 
        HD,
        -2.99%,
       which fell 2.5% to pace the Dow Jones Industrial Average's 
        DJIA,
        -0.01%
       decliners. The yield on the 10-year Treasury note
        TMUBMUSD10Y,
        1.767%,
       which is used to calculate mortgage rates, rose 4.0 basis points to a 2-year high of 1.773%. The fear is that higher rates could make homes less affordable., We looked for the S&amp;P 500 companies that managed to expand their profit margins—both net and gross—in the latest reported fiscal quarter, as compared with the same periods in 2020 and 2019.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-prices-end-lower-day/story.aspx?guid={35C48606-74BF-4CA7-A183-08073AA18C77}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-08 03:55:53 </td>
   <td style="text-align:left;"> Oil prices end lower for the day, but gain for the week as traders eye unrest in Kazakhstan - MarketWatch </td>
   <td style="text-align:left;"> Oil prices ended lower on Friday, but finished the week higher as traders kept an eye on unrest in Kazakhstan. Should any significant amount of production from the country be lost, "the bull market in oil will be extended," said Michael Lynch, president at Strategic Energy &amp; Economic Research. However, "OPEC+ is unlikely to react to such a loss unless it is clear that it will be lengthy and global inventories would thus continue to decline." February West Texas Intermediate crude 
        CLG22,
        +0.49%
       edged down by 56 cents, or 0.7%, to settle at $78.90 a barrel on the New York Mercantile Exchange. Prices based on the front-month contract rose 4.9% for the week, according to Dow Jones Market Data., A family in Florida says it got a surprise post-Christmas delivery in the form of two packages left at its doorstep by a U.S. Postal Service carrier.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/currency </td>
   <td style="text-align:left;"> 2022-01-08 03:38:54 </td>
   <td style="text-align:left;"> Swiss Franc Rebounds from 2-Week Low </td>
   <td style="text-align:left;"> The Swiss franc traded at 0.918 per USD, appreciating from the 2-week low of 0.923 touched on January 7th, amid a weaker dollar after release of US labor market data. Non-farm payrolls increased by 199 thousand in December, largely missing expectations of around 400 thousand added jobs. Still, the franc started the year subdued against both the euro and the dollar, as the Fed and the ECB point to outlooks of tighter monetary policy. During the FOMC’s meeting, Federal Reserve policymakers indicated that stimulus could be cut back faster than previously thought, with potential rate hikes coming in March followed by a possible balance sheet rundown. Meanwhile, the ECB slowed the pace of the pandemic emergency purchase programme in January and confirmed its conclusion in the end of March. On the other hand, the SNB has yet not signaled any policy tightening, as domestic inflation is still well below those of its main trading partners. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/stocks-fall-bond-yields-rise-as-investors-get-taste-of-2022 </td>
   <td style="text-align:left;"> 2022-01-08 03:38:04 </td>
   <td style="text-align:left;"> Stocks fall, bond yields rise as investors get taste of 2022 </td>
   <td style="text-align:left;"> Former treasury secretary Steven Mnuchin joins ‘Kudlow’ to discuss the current state of economy under the Biden administration.                                                                                                                                                                , Investors got a taste of what higher interest rates may mean for financial markets, including stocks, sectors and bonds.                                                                                                                                                                       , The S&amp;P fell 1.8% this week, the worst start to a calendar year since 2016, as tracked by Dow Jones Market Data Group.                                                                                                                                                                         , The 10-Year Treasury yield settled at 1.76%, a 12-month high, as the Federal Reserve disclosed that policymakers may accelerate the pace of interest rate hikes due to hot inflation.                                                                                                          , 1.769%                                                                                                                                                                                                                                                                                         , Largest 1 week yield gain since September 2019                                                                                                                                                                                                                                                 , Highest Since January 2020                                                                                                                                                                                                                                                                     , Source: Dow Jones Market Data Group                                                                                                                                                                                                                                                            , Steven Mnuchin, former treasury secretary under President Trump, gave his forecast for rates after the release of the Fed’s meeting minutes from the December meeting Wednesday.                                                                                                               , WHERE INFLATION IS HITTING AMERICANS THE HARDEST                                                                                                                                                                                                                                               , "Clearly, the Fed is gonna raise rates, the Fed is going to normalize the portfolio. It’s just how quick or how fast they do it. Eighteen months from now we will be sitting with 3% 10-year treasuries," Mnuchin told FOX Business’ Larry Kudlow, who served as Trump’s top economic advisor. , U.S. EMPLOYERS ADD 199,000 JOBS, UNEMPLOYMENT DIPS TO 3.9%                                                                                                                                                                                                                                     , The December jobs report, while mixed, is likely strong enough to keep the Fed on its mission, economists said. Employers added 199,000 positions, below the 400,000 expected. Still, unemployment fell to 3.9%, and average hourly earnings rose 4.7% over a 12-month period.                 , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                        , Higher yields historically benefit banks that can earn more as a result. So investors snapped up financial stocks driving the SPDR Financial exchange-traded fund to a record on Friday.                                                                                                       , Higher growth names, including the tech-heavy Nasdaq Composite, tanked 4.5% this week.                                                                                                                                                                                                         , Tech behemoths, including Microsoft, fell over 6% for the week, while Apple and Tesla slipped around 3%.                                                                                                                                                                                       , Fresh inflation data will come next week with the release of the Consumer Price Index on Wednesday followed by Producer Prices the following day.                                                                                                                                              , On Tuesday, Federal Reserve Chair Jerome Powell will be on Capitol Hill for his renomination hearing.                                                                                                                                                                                          , He will likely be grilled by lawmakers on the central bank’s wrong-way inflation call and the uber tight job market after a record 4.5 million people quit their jobs in November in what continues to be dubbed the ‘Great Resignation’ in the American workforce.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/07/your-money/college-early-decision-northeastern-merit-aid.html </td>
   <td style="text-align:left;"> 2022-01-08 03:03:33 </td>
   <td style="text-align:left;"> College Merit Aid (or Lack Thereof) Makes Early Decision Ever Murkier - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , your money                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Northeastern University won’t estimate how much merit aid it might offer if you get in. Can schools make you enroll if they don’t give you enough?                                                                                                                                                                                                                                                                                                                                , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                           , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                    , By Ron Lieber                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , When you agree to buy an in-demand product or service if it becomes available, it helps to know what the price will be before you commit.                                                                                                                                                                                                                                                                                                                                         , But in the world of college admissions and early decision, where you pledge to attend if a school offers you a spot, you don’t always get to know ahead of time the differing discounts — if any — many schools offer to each individual student.                                                                                                                                                                                                                                 , This is a big problem if you’re not sure you can afford the school. If you can’t get a price quote and you don’t want to make the early decision pledge, you don’t get to avail yourself of the better admissions odds that often exist when you apply that way.                                                                                                                                                                                                                  , Enter Northeastern University in Boston, a prime example of a popular school that does not always predict how much aid many applicants will get — an amount that could swing the final price by $100,000 or more during the undergraduate years. While examining its website in recent weeks, I also noticed that a key statistic that college shoppers need when assessing their odds of aid seemed off by at least 20 percentage points.                                        , Northeastern, which has transformed itself from a commuter school into a highly rejective one in just a few decades, is not alone. Connecticut College’s and New York University’s mechanisms for predicting prices have similar shortcomings. Last month, at my urging, N.Y.U. took down an admissions office blog post that was filled with incorrect early decision information.                                                                                               , All of this muck highlights a persistent problem in too many of the upper echelons of the undergraduate education industry: When it comes time to make this enormous, emotional purchase, all too often you don’t get to know before you apply and get in what the price will actually be.                                                                                                                                                                                        , So what are we talking about when we talk about the price discounts that come from “aid” and college shoppers’ ability to predict it? Schools don’t always make it clear.                                                                                                                                                                                                                                                                                                         , First, there is aid that schools base on the financial need that a student or family demonstrates. In this category, families get a fair bit of assistance in determining what might come their way. The federal government requires schools to offer something called a net price calculator, and it predicts what kind of assistance a college might offer people who can’t afford to pay the full price.                                                                       , The other big type of aid that institutions offer has come to be known as merit aid. It is murkier.                                                                                                                                                                                                                                                                                                                                                                               , Plenty of affluent families that don’t qualify for need-based aid get merit aid anyhow. Many of them believe that they can’t afford the retail price without some merit aid. Cry them a river, but if you earn $300,000 a year and live in an expensive area, writing a $75,000 tuition check, after taxes, may not be easy. Schools know this, which is part of the reason most of them offer merit aid.                                                                         , Some colleges will predict what merit aid you might get — which they determine by figuring out if they like your grades and test scores or other things about your application — before you sign an early decision agreement. Others, like Northeastern, will not do that in their net price calculators.                                                                                                                                                                         , Why not? One big reason, according to Sundar Kumarasamy, Northeastern’s vice president of enrollment management, is that these calculators are able to put test scores and grades through some rubric or another to define and predict merit aid — but they have qualitative limitations.                                                                                                                                                                                         , “How would a student who has an art portfolio compete with a person who knows how math and science work and tests well?” Mr. Kumarasamy said.                                                                                                                                                                                                                                                                                                                                     , This is reasonable, but it’s also pretty frustrating for families that just want to know — within six figures, at least! — what they might end up paying over four or five years. Whitman College in Washington and the College of Wooster in Ohio make a virtue — and a marketing strategy, really — of counseling individual families that want an early read on what kind of merit aid their applications might get.                                                           , Oberlin College in Ohio estimates merit aid via its net price calculator. Schools like Wabash College and the University of Alabama display their merit-aid-awarding grids for all to see.                                                                                                                                                                                                                                                                                        , It’s not a great look for Northeastern when it tells the world on its merit aid page that “students who are in the top 10-15% of our applicant pool are considered for competitive merit aid awards.” When I first read that figure a few weeks ago, I could tell from the school’s own published data that the percentage of undergraduates who do receive merit aid was higher than that figure might suggest.                                                                  , I asked, just to be sure, and 36 percent of first-year students who have not demonstrated financial need still get merit aid. In the wake of my inquiry, Northeastern updated the website to reflect these odds.                                                                                                                                                                                                                                                                  , Northeastern’s use of the term “binding” when it comes to early decision doesn’t strike me as quite right, either. In italics on its website, it instructs people: “​​Please note, Early Decision is binding — if you are admitted, you are committed to attending.”                                                                                                                                                                                                                , But you aren’t. This isn’t a contract that schools try to enforce through some kind of legal mechanism, and each year, 2 to 3 percent of the people who get into Northeastern via early decision decline the offer, mostly for financial reasons.                                                                                                                                                                                                                                 , Early decision isn’t binding, and Northeastern should say so on its website, using those same italics that are already there. (It is indeed as plain as day on one of the actual early decision agreements the school eventually asks students, high school counselors and parents to sign.)                                                                                                                                                                                      , And just to be crystal clear, if you don’t get the merit aid that you feel you need to make the numbers work, some schools will let you walk away from an early decision admittance.                                                                                                                                                                                                                                                                                              , “Any student who applies, is admitted ED and finds the financial aid award (need-based or merit-based aid or a combination of both) to be unreasonable has every right to withdraw their application at Conn and pursue higher education options elsewhere,” Andrew Strickler, the dean of admission and financial aid at Connecticut College, said via email. “I fervently support a student’s ability to discontinue their candidacy at Conn under these circumstances.”        , If you’re a student or parent stumbling through the college shopping process, you should take that fervent support as a kind of cue. You are not a supplicant here; you are a consumer.                                                                                                                                                                                                                                                                                           , So how would Northeastern feel if you walked away from an early decision acceptance if you didn’t get any merit aid — and thus felt that you couldn’t afford the school?                                                                                                                                                                                                                                                                                                          , When I first posed this question to Mr. Kumarasamy, he suggested that it was a kind of gamesmanship. I objected to that, given that plenty of people don’t feel they can afford his $75,000 or so list price but can make it work at $50,000 with that merit aid discount. How can this be gaming the system, I asked, when he doesn’t give them any sense ahead of time of whether they might get that $25,000 off?                                                              , Eventually, he came around. “What is not good for the student is not good for any of us,” he said. But he was also quick to point out the zero-sum nature of early decision; if you bail out on an acceptance, you took the spot of someone else — perhaps someone even needier than you — who would have liked a shot at getting in early in the senior year of high school and actually accepting the school’s financial aid offer.                                             , “There’s a difference between behavior that occurs in rare instances and behavior we want to encourage,” a Northeastern spokesman, Michael Armini, said via email.                                                                                                                                                                                                                                                                                                                , I would like to encourage that behavior a bit more than Northeastern does, and I wish college counselors in high schools would, too.                                                                                                                                                                                                                                                                                                                                              , It would be so much easier if none of this parsing was necessary, but early decision is going to be with us for a while because colleges like it so much. When enrollment managers (as they now often refer to themselves) admit a large fraction of a class at a point in the process where students feel obliged to go if they get in, it gives the schools great control over precisely what sorts of students are in any given class — and how much revenue they will deliver., So as long as we’re stuck with a highly imperfect system, schools should say what percentage of students get merit aid in the early decision round, if they have one and also offer merit aid. All schools should also say what percentage of the overall class gets merit aid and explain how they’re defining the term.                                                                                                                                                         , They should say that early decision is not binding, and they should pledge not to punish future applicants from high schools where former applicants walked away from an early decision acceptance. They should also clarify whether they have a problem with people who decline an early decision offer because they didn’t get enough merit aid.                                                                                                                                , Finally, if they won’t predict merit aid in their net price calculators, they should explain why, and give people more information about why some people get that aid and others don’t.                                                                                                                                                                                                                                                                                           , I shouldn’t have to say all of this, or any of it, really. I shouldn’t have to revise their websites for them in successive columns. And you shouldn’t have to go into this process — and come out of it, in many instances — having no idea how the system actually works.                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-08 03:01:39 </td>
   <td style="text-align:left;"> Switzerland 10Y Bond Yield at 2-Month Highs </td>
   <td style="text-align:left;"> The yield on the Swiss 10-year government bond rose to around 0%, the highest in over two months and tracking a global bond sell-off amid anticipation of tighter monetary policy in the US and rising inflation in Europe. On January 5th, the Federal Reserve indicated that it intends to speed up its stimulus cutback, while a higher federal funds rate could arrive earlier than expected in March. Domestically, the Swiss National Bank remains committed to its ultra-loose monetary policy, as December labor data indicated a slight increase in the unemployment rate to 2.6%. While the Swiss inflation rate is at its highest since 2008 at 1.5%, the SNB indicated it does not have plans to tighten policy before other major central banks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-mark-worst-weekly/story.aspx?guid={D3D0599B-CBFF-4074-9FE8-F478D65975FC}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-08 02:42:50 </td>
   <td style="text-align:left;"> Gold futures mark worst weekly performance since Thanksgiving week - MarketWatch </td>
   <td style="text-align:left;"> Gold futures settled higher on Friday after a disappointing rise in December U.S. nonfarm payrolls. Prices, however, still marked their worst weekly loss since the period ending Nov. 26, FactSet data show. The U.S. created a much smaller-than-expected 199,000 jobs in December, but the U.S. jobless rate slipped to 3.9% from 4.2%. "It seems traders are still expecting a March interest rate hike," said Chintan Karnani, director of research at Insignia Consultants. Investors will look to next week's inflation numbers and trends in the U.S. stock market to help guide the next move for gold prices, he said. February gold 
        GCG22,
        -0.16%
       rose $8.20, or 0.5%, to settle at $1,797.40 an ounce, with the most-active contract ending the week with a loss of about 1.7%., Found dead in hotel room at the Ritz-Carlton in Orlando, according to the sheriff's department. No cause of death had been determined. Saget had performed Saturday in Jacksonville, Fla.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-08 02:15:00 </td>
   <td style="text-align:left;"> Wall Street Wavers after Payrolls Report </td>
   <td style="text-align:left;"> US stocks traded mixed on Friday, as investors digested the latest payrolls report which reinforced the view that Fed may accelerate its timeline for rate hikes. Although only 199K jobs were created in December, less than half of the market forecasts, the jobless rate fell to 3.9% and hourly wages surged 4.7% from a year ago. The Dow Jones added more than 50 points supported by gains in bank stocks amid expectations of higher yields. Meanwhile, the S&amp;P slipped 0.3% and the tech-heavy Nasdaq Composite dropped 0.8% and is on the way to book its worst week since February 2021. Also, chipmakers such as Nvidia and Microchip fell more than 2% and Tesla and Netflix were down 2%. Still, on the week, the S&amp;P traded 1.6% lower and the Dow was little changed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-invited-give-state-union/story.aspx?guid={41A7F49E-8AF8-42B4-9CA3-76E015981555}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-08 01:55:22 </td>
   <td style="text-align:left;"> Biden invited to give State of the Union address on March 1 - MarketWatch </td>
   <td style="text-align:left;"> House Speaker Nancy Pelosi has invited President Joe Biden to give his first State of the Union address on March 1, the California Democrat said Friday. In a letter to Biden, Pelosi called the past year "historic" and said she is inviting the president to "share your vision of the State of the Union." Biden spoke before a joint session of Congress in April 2021, but the March 1 speech will be his first formal State of the Union address.   

, As President Joe Biden's 'Build Back Better' bill stalls on Capitol Hill, here's what's expected to happen with the hot-button issue of student-debt forgiveness.                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/costa-rica/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-08 01:54:38 </td>
   <td style="text-align:left;"> Costa Rica Inflation Rate Slips From Near 7-Year High </td>
   <td style="text-align:left;"> Costa Rica’s annual inflation rate increased to 3.30 percent in December of 2021 from 3.35 percent in the previous month. Prices accelerated for transports (14.26 percent vs 12.64 percent in November), furniture (4.79 percent vs 3.99 percent), and alcoholic beverages &amp; tobacco (2.23 percent vs 1.82 percent). On a monthly basis, consumer prices rose 0.48 percent in December, compared to a 0.82 increase percent in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/07/citigroup-is-the-first-major-wall-street-bank-to-terminate-unvaccinated-workers.html </td>
   <td style="text-align:left;"> 2022-01-08 01:54:35 </td>
   <td style="text-align:left;"> Citigroup will terminate unvaccinated workers by Jan. 31, a first among Wall Street banks </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                         , Citigroup will be the first major Wall Street institution to enforce a vaccine mandate by terminating noncompliant workers by the end of this month.                                                                                                                                                                    , The bank reminded employees in a memo sent Friday about its policy, first disclosed in October, that they must be "fully vaccinated as a condition of employment." At the time, the bank said that employees had to submit proof of vaccination by Jan. 14.                                                             , Those who haven't complied by next week will be put on unpaid leave, with their last day of employment being Jan. 31, according to the memo, which was first reported by Bloomberg. A spokeswoman for the New York-based bank declined to comment.                                                                      , Citigroup, the third biggest U.S. bank by assets and a major player in fixed income markets, has had the most aggressive vaccine policy among Wall Street firms. Rival banks including JPMorgan Chase and Goldman Sachs have so far stopped short of terminating unvaccinated employees.                                , Citigroup, led by CEO Jane Fraser since March of last year, said it made the decision because as a government contractor, it needed to comply with President Joe Biden's executive order on vaccines. The bank also said that enforcing the mandate would help ensure the safety of employees who return to office work., More than 90% of employees are compliant with the vaccine mandate, and that figure is rising as the deadline nears, according to a person with knowledge of the matter. The bank had 220,000 employees as of late last year, although the policy applies only to U.S. based staff.                                      , While some technology companies have embraced remote work as a permanent model, Wall Street CEOs including JPMorgan's Jamie Dimon and Morgan Stanley's James Gorman have been vocal about needing to pull workers back.                                                                                                 , But the spread of the omicron variant of Covid-19 has forced companies to suspend back-to-work plans yet again, making it the latest disruption caused by the pandemic.                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/07/stocks-making-the-biggest-moves-midday-discovery-gamestop-t-mobile-and-more.html </td>
   <td style="text-align:left;"> 2022-01-08 01:42:57 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Discovery, GameStop, T-Mobile and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                               , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                                   , GameStop – Shares of the video game retailer jumped 7.3% after news that the company is planning to create a marketplace for nonfungible tokens, or NFTs. At its session high, the speculative name jumped more than 20% on the day.                                                                                                                                                                                          , T-Mobile – The company saw its stock fall 5% after it reported postpaid net customer additions of 844,000 in the fourth quarter and about 2.9 million total in 2021. That came in lower than the StreetAccount consensus expectations of 867,900 in the fourth quarter.                                                                                                                                                       , DraftKings – Shares of the sports betting company added 5.6% ahead of the launch of legal mobile sports betting in New York state on Saturday.                                                                                                                                                                                                                                                                                , Discovery – The media stock soared 16.9% after Bank of America upgraded Discovery to buy. The pending merger with Warner Media could create a true rival to Netflix and Disney+ in the streaming space, Bank of America said.                                                                                                                                                                                                 , The New York Times – Shares tumbled 10.7% after the newspaper publisher announced a deal to buy sports news site The Athletic for $550 million. The transaction is expected to close in the first quarter of 2022.                                                                                                                                                                                                            , Delta Air Lines – Shares gained 3.5% after Bank of America upgraded Delta to a buy rating. The firm cited a recovery in business travel as underlying its bull thesis on the stock. "We expect each successive variant to have less of an impact on consumers' willingness to travel and return to office plans, which could result in a faster recovery in corporate demand than initially expected in 1H22," the firm said. , Texas Instruments – The stock fell 3.9% after Citi downgraded the company to a buy rating from neutral. "We believe its margins will decline due to increasing depreciation and the acquisition of a fab," Citi said.                                                                                                                                                                                                         , Kohl's – Shares of the retailer fell 1.7% after UBS downgraded Kohl's to sell from neutral. The bank said that inflation and less government stimulus could cause Kohl's to miss earnings expectations in 2022.                                                                                                                                                                                                               , Abercrombie &amp; Fitch – Abercrombie shares dropped 3.3% after UBS downgraded the retail stock to a neutral rating from buy. "We think macro forces result in slowing growth, making it hard for the stock to re-rate," the firm said.                                                                                                                                                                                           , Chewy — Shares of the pet supply retailer dropped 8.3% after Piper Sandler downgraded Chewy to neutral from overweight. The Wall Street firm said in its downgrade that it sees sales and margin headwinds for Chewy.                                                                                                                                                                                                         , Clover Health — Shares fell 5.7% after Credit Suisse downgraded the stock to underperform from neutral. "Our view is predicated on the company continuing to need to raise capital moving forward, a lack of clarity on significantly improving their medical loss ratio (MLR) to reduce cash burn, and an overall re-rating across the tech-enabled MCO sector," the firm said.                                              , Starbucks — The worldwide coffee chain ticked 3.2% lower following a downgrade to sector perform from outperform at RBC Capital Markets. The Wall Street firm said in its downgrade of Starbucks that it sees more compelling risk/reward.                                                                                                                                                                                    , — CNBC's Yun Li, Maggie Fitzgerald, Pippa Stevens and Jesse Pound contributed reporting                                                                                                                                                                                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59912190?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-08 01:18:26 </td>
   <td style="text-align:left;"> Hiring slows in US after record year of job gains </td>
   <td style="text-align:left;"> Hiring in the US slowed last month, as firms struggled to hire workers and continued to grapple with the effects of coronavirus.                                                                                                                      , Employers hired just 199,000 people in December, a second month of weaker than expected gains.                                                                                                                                                        , But the jobless rate dropped sharply to 3.9% and wages rose, the Labor Department said.                                                                                                                                                               , The mixed data, which was collected before Omicron's full force was felt, follows a record year of jobs growth.                                                                                                                                       , "For a second straight month, we have conflicting pictures emerging," said Mark Hamrick, senior economic analyst at Bankrate.com. "This report appears to reflect the state of play before the worst impacts of the Omicron variant hit the economy." , "We will have to wait until the following report, covering the job market picture in January, to get a clearer picture," he added.                                                                                                                    , The US added more than 6.4 million jobs in 2021, regaining many of the positions lost at the height of the pandemic in 2020.                                                                                                                          , Though total employment remains about 3.6 million lower than its pre-pandemic level - and far lower than it would have been if Covid had not struck - many signs point to a strong economy.                                                           , A record 4.5 million Americans quit jobs in November - a sign of confidence in the labour market - and more than 10 million positions stand open, the government reported this week. Jobless claims have dropped to a near 50-year low.               , "I could hire three full-timers and one part-timer on the spot," said Konstantinos Tsoulos, owner of Brothers Bagels in Brooklyn, New York.                                                                                                           , In September, he decided to close the shop on Mondays due to the staff shortage. He said he has not had a single person inquire about a job.                                                                                                          , "I've been in business almost 35 years and I've never seen anything like it," he said.                                                                                                                                                                , December's job gains were felt across most industries, led by leisure and hospitality. The unemployment rate fell to 3.9% from 4.2%, while average hourly earnings were up 4.7% year-on-year.                                                         , US President Joe Biden called the figures "historic", saying they reflected an economy back on its feet thanks to a flood of government spending championed by his administration.                                                                    , Wells Fargo economist Sarah House said future growth would be determined by worker availability.                                                                                                                                                      , "December's report underscored that workers are only likely to trickle back into the jobs market as reasons for sitting out, like financial cushions, health concerns and childcare issues do not unwind all at once," she said.                      , The labour shortages have helped to push inflation in the US to its highest rate in almost 40 years.                                                                                                                                                  , In response, America's central bank has signalled it plans to start removing support for the economy, raising interest rates potentially as soon as March.                                                                                            , But the emergence of the Omicron variant has complicated the outlook for the economy.                                                                                                                                                                 , The virus has been blamed for widespread worker absences in recent weeks, prompting the cancellation of thousands of flights, the closure of major school districts and strains on hospitals, transport systems and other businesses.                 , Mr Tsoulos said his business has been holding on thanks to patronage from neighbourhood families. But he is worried by the shift to remote working, which has cut into his commuter business and the catering orders he used to receive from offices. , "Everybody was touting that the downtown office buildings would open after Labor Day and nothing happened. Then they said January and it's almost mid-January," he said. "Now they're talking June."                                                  , Russell Kane and guests consider the life of the iconic musician                                                                                                                                                                                      , Featuring music from The Wild Bunch and more                                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-08 01:13:35 </td>
   <td style="text-align:left;"> South African Stocks End Slightly Lower </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index closed 0.3% down at 73,940 on Friday, as investors continued to expect faster interest rates increases by the Federal Reserve even after latest economic data pointed to a slowdown in US jobs growth in December. On the domestic economic front, South Africa Absa Manufacturing PMI dropped in December, pointing to a slower expansion in manufacturing activity, as a surge in Covid-19 infections driven by the Omicron variant and tighter global restrictions weighed on the country's exports. On a brighter note, Mauritius reopened to travellers from South Africa, and eight other previously restricted countries, three weeks ahead of schedule. Mauritius follows France, Germany, and the US in announcing eased travel restrictions on South Africa. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-08 01:11:33 </td>
   <td style="text-align:left;"> Italian Stocks Close Lower </td>
   <td style="text-align:left;"> The FTSE MIB erased early gains to close 0.1% lower at 27,618 on Friday, slightly extending last session’s 1.8% loss, as investors digested consumer price data from the Eurozone and labor market data from the United States. Consumer inflation in the euro area rose to 5% in December according to preliminary data, the highest ever recorded. At the same time, 199 thousand jobs were added to the US economy, less than half of market expectations. On the corporate front, industrial stocks led the losses, driven by recently demerged Cnh Industrial (-1.6%) and Iveco Group (-2.9%). Luxury clothing also traded on the red, led by Brunello Cucinelli (-3.2%) and Moncler (-2.8%). On the other hand, STMicroelectronics jumped 3.7% after publishing preliminary expectations of USD 3.56 billion in net revenue, 11.2% higher than the corresponding period in the previous year and 140bps above the upper limit of the firm’s reported range. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ecuador/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-08 01:07:25 </td>
   <td style="text-align:left;"> Ecuador December Inflation Rate at Over 5-1/2-Year High </td>
   <td style="text-align:left;"> Consumer prices in Ecuador rose1.94 percent over a year in December of 2021, accelerating from a 1.84 percent rise in the previous month. It was the highest inflation rate since March of 2016 as prices accelerated for food and non-alcoholic beverages (1.08 percent vs 0.59 percent); transport (9.77 percent vs 9.52 percent); housing and utilities (0.57 percent vs 0.17 percent); furnishings (2.24 percent vs 1.70 percent); and education ( 2.76 percent vs 2.71 percent). Also, prices fell less for clothing and footwear (-3.20 percent vs -3.73 percent). Meanwhile inflation slowed for healthcare (1.62 percent vs 2.09 percent); and restaurants and hotels (0.65 percent vs 0.78 percent). On a monthly basis, consumer prices rose 0.07 percent, slowing from a 0.36 percent rise in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/07/business/st-viateur-ess-a-bagel-business.html </td>
   <td style="text-align:left;"> 2022-01-08 01:00:17 </td>
   <td style="text-align:left;"> How Many Bagels Does It Take to Keep a Place in Business? - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                     , Supported by                                                                                      , scratch                                                                                           , Send any friend a story                                                                           , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.    , By Julia Rothman and Shaina Feinberg                                                              , Julia Rothman is an illustrator. Shaina Feinberg is a writer and filmmaker. Both live in Brooklyn., Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rubber </td>
   <td style="text-align:left;"> 2022-01-08 00:49:00 </td>
   <td style="text-align:left;"> Rubber Close to 1-Month High </td>
   <td style="text-align:left;"> Osaka rubber futures traded around 226 yen per kg level at the start of 2022, not far from an over one-month high of 229 touched on January 5th, amid a softer yen and on worries that transportation constraints from Southeast Asia were affecting near-term supply to consumer countries such as Japan and China, encouraging buying. At the same time, concerns mounted that the spread of the pandemic could cause labour shortage in rubber farms. Meanwhile, the imports from China are set to pick ahead of the week-long holiday for the Lunar New Year as factories are building up inventories to address seasonal supply shortage coinciding with the annual wintering of rubber trees in major producing countries. Rubber lost nearly 18% in 2021 as demand from the auto sector declined due to chip shortages and COVID-19 restrictions imposed especially across Europe and top buyer China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-01-08 00:46:00 </td>
   <td style="text-align:left;"> French Shares Extend Losses </td>
   <td style="text-align:left;"> The CAC 40 Index closed 0.4% lower at 7,219 on Friday, as investors digested fresh macroeconomic data from both the Eurozone and the US. Consumer inflation in the euro area rose to an all-time high of 5% on the year in December, according to preliminary estimates. In the meantime, US job growth in the last month of 2021 came at less than half of the market’s expectations. On the corporate front, luxury goods were among the hardest hit, with Hermes (-4%), LVMH (-2%), and Christian Dior (-3.1%) trading on the red. Tech stocks also continued to slide, led by Capgemini (-2.2%) and Dassault Systemes (-1.8%). On the other hand, STMicroelectronics jumped 3.2% after preliminary corporate results were better than expected. The semiconductor manufacturer’s revenue rose to USD 3.56 billion in Q4 2021, compared to USD 3.24 billion in the same period of the previous year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-08 00:45:47 </td>
   <td style="text-align:left;"> UK Stocks Recoup Some Losses </td>
   <td style="text-align:left;"> The FTSE 100 rose 0.4% to close at 7,479 on Friday, trying to recover from a 0.9% loss in the previous session, as mining stocks were supported by firmer copper prices and as investors digested a batch of economic data released during the session. UK house prices in December were 9.8% higher than a year earlier, the sharpest annual increase since July 2007, while a PMI survey suggested the country's construction sector growth eased to a three-month low as the rapid spread of Omicron had an impact on the economic recovery. Elsewhere, a mixed US jobs report, coupled with hawkish minutes from the Federal Reserve's December meeting, raised expectations of faster-than-expected US rate hikes. On the week, the index added 1.3%, extending gains for a third consecutive week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-08 00:44:08 </td>
   <td style="text-align:left;"> European Stocks Close Mostly Lower </td>
   <td style="text-align:left;"> European equity markets closed mostly lower on Friday as investors digested a batch of economic data from the Eurozone and the US. The bloc's inflation rate likely jumped to a record high of 5% in December, beating market expectations of 4.7% and remaining above the ECB's target for a sixth straight month. At the same time, economic sentiment in the Eurozone weakened to a seven-month low, while industrial production in Germany and France unexpectedly contracted in November. Elsewhere, the US jobs report showed a decline in the unemployment rate and an acceleration in wage growth, making the case for faster interest rate hikes by the Fed this year. On the corporate front, Deutsche Bank climbed to a more than six-month high, after the company's finance chief said it was confident it will reach a key profitability target this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-08 00:23:08 </td>
   <td style="text-align:left;"> Germany 10Y Bond Yield Hits 31-month High </td>
   <td style="text-align:left;"> Germany 10 Year Government Bond Yeld increased to a 31-month high of -0.03% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-08 00:21:41 </td>
   <td style="text-align:left;"> Italy 10Y Bond Yield Hits 17-month High </td>
   <td style="text-align:left;"> Italy 10 Year Government Bond Yeld increased to a 17-month high of 1.32% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/cincor-pharmas-stock-opens-well/story.aspx?guid={E244C422-0BA5-4272-A89D-E6B48362088E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-08 00:21:02 </td>
   <td style="text-align:left;"> CinCor Pharma's stock opens well above IPO price, then sells off sharply - MarketWatch </td>
   <td style="text-align:left;"> CinCor Pharma Inc.'s stock 
        CINC,
        
       shot out of the gate in morning trading Friday, but then pulled back sharply, to trade briefly below in negative territory. The Massachusetts-based biopharmaceutical company's stock's first trade was at $21.00 at 11:05 a.m. Eastern, or 31.3% above the $16 IPO price. The stock then rose to an intraday high of $22.67, before selling off to trade as low as $15.69, or 1.9% below its IPO price, before bouncing slightly to trade flat. At current prices, the company is valued at about $567 million. The company's debut comes on a day that the Renaissance IPO ETF 
        IPO,
        -0.43%
       dropped 1.4% while the S&amp;P 500 
        SPX,
        -0.41%
       lost 0.7%., Shares of Humana Inc. continued their plunge toward a near two-year low Friday, as some Wall Street analysts expressed concern that there isn't a fast fix to the health insurance services company's Medicare Advantage woes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/soybeans </td>
   <td style="text-align:left;"> 2022-01-08 00:19:00 </td>
   <td style="text-align:left;"> Soybeans Rise to 5-Month High </td>
   <td style="text-align:left;"> Soybean futures surged to $14 per bushel, the highest since August 2021 amid supply worries due to forecasts of hot and dry weather in Argentina and southern Brazil. Meanwhile in northern Brazil precipitation slowed down early harvest. Consultancy StoneX forecast Brazil's soybean crop at 134.0 million tonnes, below 145.1 million in December. Elsewhere, investors await a batch of US Department of Agriculture reports due on January 12th, including updated US 2021 crop production figures, as well as December 1st quarterly stocks and updated South American crop estimates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-08 00:14:00 </td>
   <td style="text-align:left;"> US 10Y Bond Yield Hits Near 2-Year High </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Treasury note rose to 1.78% on Friday, hovering around the highest level since January 2020 on a closing basis, after mixed economic data showed the US unemployment rate dropped more than expected in December and wage growth accelerated, while non-farm payrolls missed forecasts. Still, the jobs report is unlikely to change market expectations for a rate hike this quarter as the Fed set a more hawkish tone last meeting and viewed the labor market as “very tight". </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/cruise-stocks-surge-after-stifel/story.aspx?guid={A815F7E2-D6F0-40C4-B1C1-CB2CF6AD8373}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-08 00:12:36 </td>
   <td style="text-align:left;"> Cruise stocks surge, after Stifel analyst says 2022 will be the 'Year of the Cruise!' - MarketWatch </td>
   <td style="text-align:left;"> Shares of cruise operators rallied Friday, to buck the broad-market selloff, after Stifel Nicolaus analyst Steven Wieczynski pounded the table on the group, saying 2022 was going to be known as the "Year of the Cruise!" Shares of Royal Caribbean Group 
        RCL,
        +3.98%,
       which Wieczynski said was his "top idea for 2022," climbed 3.6%; Carnival Corp. 
        CCL,
        +3.94%
       rallied 2.9%, Norwegian Cruise Line Holdings Ltd. 
        NCLH,
        +4.03%
       rose 3.6%; Lindblad Expeditions Holdings Inc. 
        LIND,
        +2.47%
       tacked on 1.9%; while the S&amp;P 500 
        SPX,
        -0.41%
       dropped 0.6%. Wieczynski said for investors searching for recovery names that "massively underperformed" last year, he believes cruise-related names will stick out as compelling ideas. "[W]e are believers that cruise demand should remain strong throughout the majority of 2022," Wieczynski wrote in a note to clients. "While there certainly will be cancellations and itinerary adjustments in 1H22 due to COVID noise, we still believe that cruise operators are on a clear path (although might be delayed) to the all-important cash flow breakeven/positive level.", John Pinette had overseen Facebook's external communications since 2019.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-01-08 00:01:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Snaps 3-Day Winning Run </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index dropped 0.3% to 2,289 on Friday, after three consecutive sessions of gains, amid weakness across its smaller vessel segments. The panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, fell 1.9% to 2,957; and the supramax index declined 50 points to its weakest level since April of 2021 at 2,074. Meanwhile, the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, rose 3.2% to 2,432. The Baltic Dry Index rose more than 3% this week, after posting two straight weeks of losses. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-01-10 16:06:33 UTC +8

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
   <td style="text-align:left;"> 2022-01-10 16:04:30 </td>
   <td style="text-align:left;"> $SPY $QQQ bonds selling off, dollar strengthening... Expect blood 💉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 16:01:54 </td>
   <td style="text-align:left;"> $SPY Wisdom tooth pain is some of the worst pain you’ll ever experience, can’t even sleep lol. Now I have to stay up and see people scream “future ripping” when it’s only up 12 points….people be acting like we opened 200 points higher or something lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 16:00:53 </td>
   <td style="text-align:left;"> $SPY …Good morning,

Next Monday (a week from now is a trading holiday.

This week, Monday &amp;amp; Tuesday will be weak declines with Wednesday &amp;amp; Thursday having stronger declines.  Strong increases Friday will be followed after the extended weekend by continuing increases Tuesday and perhaps Wednesday &amp;amp; Thursday.

For Long Term Buy the Dip holders the best day to buy will be 1/11-1/12 (Wed-Thur) at $459.71

Strong rebounding should occur Friday, Tuesday &amp;amp; Wednesday back up near current levels mid next week.

GLTATraders LT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 16:00:08 </td>
   <td style="text-align:left;"> $SPY this whole market reminds me of the little Dutch boy story, trying to plug all the holes in the dyke with his fingers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:58:09 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:57:23 </td>
   <td style="text-align:left;"> $SPY $BTC.X https://youtu.be/S9IB3aWt3Ww </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:56:48 </td>
   <td style="text-align:left;"> $SPY Crash comin… keep tellin ppl, gunna make 2008 look like tea party. GL

https://twitter.com/reuters/status/1480404074663194625?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:55:29 </td>
   <td style="text-align:left;"> $UVXY  $IWM $SPY $SPX Taking into account the volume, the FED has printed, they are going to de-valuate the USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:53:21 </td>
   <td style="text-align:left;"> $SPY  Pretty straight forward either $450 or $475
 (465 pivot/trigger ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:53:18 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:52:31 </td>
   <td style="text-align:left;"> $SPY looks good I’m going to sleep see y’all at 480 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:51:57 </td>
   <td style="text-align:left;"> $SPY People are bullish on the virus spreading because they think it will send the market higher……..the logic of human beings never ceases to amaze me! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:49:54 </td>
   <td style="text-align:left;"> $SPY if fut can keep the momentum, even when theres a dip at the open, i believe all fang tech will push it higher. $TSLA $AAPL $AMZN $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:48:33 </td>
   <td style="text-align:left;"> $SPY  and don’t worry I bought the big box of granola bars this time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:47:53 </td>
   <td style="text-align:left;"> $SPY $PYPL the low T wankers and simps on here must be sweating the $600 irs transaction reporting requirement. you wouldn&amp;#39;t dream of dodging your own elected leadership&amp;#39;s requirement and marking it as &amp;#39;friends and family&amp;#39;, now would you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:47:50 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:46:43 </td>
   <td style="text-align:left;"> $SPY HAHAHAH BEARS ALL NIGHT 👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:44:19 </td>
   <td style="text-align:left;"> $SPY I recommend waiting for this dead cat to bounce tomorrow before loading up on puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:43:44 </td>
   <td style="text-align:left;"> $SPY $OCGN is ready to blow. Incredible results of COVAXIN for kids and adults. Time to blow this to 50+. Next 500% runner in my honest opinion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:43:37 </td>
   <td style="text-align:left;"> $SPY  anybody catch that Coronelta variant yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:41:29 </td>
   <td style="text-align:left;"> $SPY 🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:40:37 </td>
   <td style="text-align:left;"> $SPY deltacron </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:40:36 </td>
   <td style="text-align:left;"> $SPY bears, gL tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:39:27 </td>
   <td style="text-align:left;"> $SPY 500 open please 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:37:59 </td>
   <td style="text-align:left;"> $SPY /NQ +50bps /ES +25bps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:37:52 </td>
   <td style="text-align:left;"> $SPY $AMC I’ll leave you with this. When the government tells people who already had the virus to get an experimental vaccine when of course that individual has all the sufficient antibodies they need, then you know something is wrong. Even as a kid I remember the doctor saying that once you get the illness your body will have strong immunity to it. Unfortunately the brainwashing is strong and people have lost the ability to think for themselves! Fear is a powerful tool. Best wishes! ✌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:37:44 </td>
   <td style="text-align:left;"> $SPY $480 today 🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:37:26 </td>
   <td style="text-align:left;"> $SPY anybody live in Chicago? I need stock market friends </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:37:15 </td>
   <td style="text-align:left;"> $SPY last time this happened with fUtURes it pumped until 9:25, then dropped hard. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:36:06 </td>
   <td style="text-align:left;"> $SPY buy at 6:30/9:30 if you didn’t get in on Friday. Trust me this can rip 5%+ this week alone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:35:24 </td>
   <td style="text-align:left;"> $SPY FUTURES FLYING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:35:24 </td>
   <td style="text-align:left;"> $SPY LMFAOO THE BEARS STUCK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:34:56 </td>
   <td style="text-align:left;"> $SPY  BEARS ALL NIGHT 👇👇🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:34:54 </td>
   <td style="text-align:left;"> $SPY gonna inflate 🆙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:34:26 </td>
   <td style="text-align:left;"> $SPY oh yea futes RIPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:34:24 </td>
   <td style="text-align:left;"> $SPY haha bears trapped .. puts to go down.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:31:56 </td>
   <td style="text-align:left;"> $SPY bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:31:28 </td>
   <td style="text-align:left;"> $SPY 10yr about to break 2% LOL watch tech timber in 30 mins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:28:05 </td>
   <td style="text-align:left;"> $SPY start strong then dip? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:27:37 </td>
   <td style="text-align:left;"> $SPY alright bears I’m going to sleep this is going to pump itself 

BEARS, Keep your eyes glued to the futures and I’ll be back in the morning 

🪦🪦🪦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:27:21 </td>
   <td style="text-align:left;"> $SPY when germany opens in 33 minutes u bulls will be looking like this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:27:12 </td>
   <td style="text-align:left;"> $SPY Technical Analysis with Washboardjim,, Sneaky Snake trading strategy SPY  https://www.youtube.com/watch?v=8csAHZ8AWBI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:25:57 </td>
   <td style="text-align:left;"> $SPY   $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:25:11 </td>
   <td style="text-align:left;"> $SPY bears why so quiet ??!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:24:29 </td>
   <td style="text-align:left;"> $SPY California in shambles $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:24:13 </td>
   <td style="text-align:left;"> $SPY now the bond market ahead of the fed 😰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:23:47 </td>
   <td style="text-align:left;"> $SPY bonds still creeping up with green futes. My god u bulls r dumb if you keep buying calls. Literally gonna send urself into a financial suicide </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:23:45 </td>
   <td style="text-align:left;"> $SPY I’m feeling a bull trap and I have calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:19:04 </td>
   <td style="text-align:left;"> $SPY dang what a comeback , now I can sleep in peace </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:18:42 </td>
   <td style="text-align:left;"> The whole 
world rallying tonight  
virus worse enough to stop the hikes 
 
so bad it’s good 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:18:27 </td>
   <td style="text-align:left;"> $SPY LOL - realizing the bears on here are mostly butthurt deplorable Trumpsuckers. Probably should be called MAGATs instead of bears, they don&amp;#39;t look up much either and just dwell in a grubby larval stage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:17:10 </td>
   <td style="text-align:left;"> $SPY $AMC you have to ask yourself, if more people died this year while having the vaccines available, then why continue to push the vaccines when there are so many proven alternative therapies that will not only save your life, but keep you from going to the hospital. If the Biden administration is arguing that the vaccines will help lighten the load on the hospitals then why not use the alternative forms of care? I think everyone here is smart enough to know that there is a hidden agenda. What that hidden agenda is? Only time will tell. We can only hope the only reason why they are pushing the vaccines is because the politicians have made a deal with the vaccine manufactures and they are getting a monstrous kick back. These should be up tomorrow. Best wishes!✌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:17:02 </td>
   <td style="text-align:left;"> $SPY notice how all these old rich elites are just dying off now. Its obvious they getting merked. Economy propped up for their greed but since they dying off we dont need to pump for dead people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:16:32 </td>
   <td style="text-align:left;"> $SPY My bull friends, be calm and relaxed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:16:31 </td>
   <td style="text-align:left;"> $SPY $BTC.X $ETH.X so what you guys think? Will CPI on 12th cause a crash in crypto? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:16:25 </td>
   <td style="text-align:left;"> $SPY  The back of my mind tells me last week suggested  signs of dark cloud cover on trend. It needs a convincing V reversal otherwise worse case scenario for bulls is 
4 fitty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:15:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $TELL  
 
$PRTS  
CEO  
https://twitter.com/LevPeker/status/1476975716348563457 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:15:44 </td>
   <td style="text-align:left;"> $SPY Based on that pretty extreme GEX Fri I expect some upward movement this week. See if it holds. I have cheap protection for SPY long if we head lower but positioned more for upside. When I hedge is it not so much a position as insurance that pays to add to my long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:15:44 </td>
   <td style="text-align:left;"> $SPY lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:15:36 </td>
   <td style="text-align:left;"> $SPY pumpy pumpy they’re trying it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:14:51 </td>
   <td style="text-align:left;"> $SPY will crash if JPOW starts talking about the rushed taper. No positions but im biased for the bears atm 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:14:12 </td>
   <td style="text-align:left;"> $SPY haha it can’t get no lower because it’s 2022 numbers now Btch’s   

$nasdaq $ndx $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:14:08 </td>
   <td style="text-align:left;"> $SPY so looks green tommorow, only question is how green.... 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:13:03 </td>
   <td style="text-align:left;"> $SPY equity index futures bounced back but yields are lower... Red flag IMO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:12:53 </td>
   <td style="text-align:left;"> $SPY HAHAHAHAH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:12:25 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ 

FUTURES UPDATE FOR THE SHORTS 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:12:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA THE DEATH OF BOB SAGET WILL SET OFF A 2000 2008 LEVEL CRISIS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:12:13 </td>
   <td style="text-align:left;"> $SPY last two scalps screwed me over let’s see how this one goes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:11:26 </td>
   <td style="text-align:left;"> $SPY About to be exactly howI like my steak…bloody red🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:11:22 </td>
   <td style="text-align:left;"> $SPY wtf rigged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:10:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $TELL  
 
$PRTS  
CFO &amp;quot; Going from 2 distribution centers to 6 in the 3 years  
is a perfect demonstration of our success!&amp;quot;  
https://twitter.com/davidmeniane/status/1478435310056853506 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:10:13 </td>
   <td style="text-align:left;"> $SPY I expect a dip when we open! Least my puts do lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:06:42 </td>
   <td style="text-align:left;"> $SPY I want to learn about land sales this year.. I don’t think I want to flip houses, but I’ve always liked the idea of selling land property </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:05:25 </td>
   <td style="text-align:left;"> $SPY someone explain to me how McDonald&amp;#39;s is going up and up. 

Is their a mad rush for quarter pounders and nobody told me? 

$MCD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:04:54 </td>
   <td style="text-align:left;"> $SPY ye slow ramp up of 35 points… watch the flush happen at 4 AM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:04:04 </td>
   <td style="text-align:left;"> $SPY The futures ripping comment has no meaning anymore, unless it means it&amp;#39;s less than the previous day and still in the same channel of downtrend of last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:03:37 </td>
   <td style="text-align:left;"> $SPY in fairness, last week futes went deep red and opened the day at 9:30 in green. 

It&amp;#39;s all random. I don&amp;#39;t care anymore about them. I just check to see if the assholes who always say &amp;quot;futes are ripping&amp;quot; are correct, or if it&amp;#39;s just some bulljive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:03:36 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:03:31 </td>
   <td style="text-align:left;"> $SPY why must God take Bob Saget before..... Never mind I can&amp;#39;t name names but you know what I&amp;#39;m talking about </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:03:26 </td>
   <td style="text-align:left;"> $SPY $msft look it’s the moo pattern </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:03:14 </td>
   <td style="text-align:left;"> $SPY Futes Rippin&amp;#39; 🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:03:10 </td>
   <td style="text-align:left;"> $SPY $qqq nq calls dirt cheap.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:02:02 </td>
   <td style="text-align:left;"> $SPY ripping ferociously </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:02:01 </td>
   <td style="text-align:left;"> $SPY I’m collllld </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:01:36 </td>
   <td style="text-align:left;"> $SPY from Steelers Locker Room ⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️
Let’s Go Brandon (Staley)
🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 15:00:01 </td>
   <td style="text-align:left;"> $SPY futures rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:59:43 </td>
   <td style="text-align:left;"> $SPY

He protests too much. What a terrible and divisive leader. Put him on an island with people like Trudeau, Morrison, Arden and Biden. It’s the perfect company where they can build back worse.

https://www.lifesitenews.com/blogs/macron-insults-anti-covid-vaccine-french-says-they-are-no-longer-citizens/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:59:34 </td>
   <td style="text-align:left;"> $SPY you seeing anything?
You?
You?
You? 
You.....

&amp;quot;Nope&amp;quot;
&amp;quot;Nope....&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:58:43 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/ezM95_Y9ABk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:58:17 </td>
   <td style="text-align:left;"> $SPY are the rest of my calls gonna get destroyed tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:58:11 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:57:44 </td>
   <td style="text-align:left;"> $SPY aye y’all make some money at night too, I know surveys suck but this one actually pays decently well 

https://send.cloutzap.com/Ali786 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:56:52 </td>
   <td style="text-align:left;"> $SPY is there a hospital crisis because of cases ? Or because they TERMINATED all the hospital  staffs who refused the jabs 

https://m.theepochtimes.com/ontario-halts-non-urgent-surgeries-amid-hospital-capacity-concerns_4197257.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:54:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA BOB SAGET DIED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:52:27 </td>
   <td style="text-align:left;"> $SPY 3rd time is a charm.. tomorrow lets break this 15800 curse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:52:00 </td>
   <td style="text-align:left;"> $SPY 

Joseph Stalin said that “it’s not the people who vote that count, it’s the people who count the votes.”
Welcome to the future to be created by the DemocRATS.

https://www.breitbart.com/politics/2022/01/06/joe-biden-and-kamala-harris-use-january-6-demand-federal-takeover-elections/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:51:45 </td>
   <td style="text-align:left;"> $SPY to all: recommend to listen to this podcast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:51:15 </td>
   <td style="text-align:left;"> $ES_F areas of interest, 4646-4653 support area 1, 4639 support area 2, 4622 and 4615 below targets. Opposite end 4682-4689 resistance area 1, 4696 resistance area 2, 4713 and 4719 above targets 
$ES_F #ES_F $SPY #SPY $SPX #SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:51:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA 2000 2008 level crash incoming hide yo canoes 🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:47:56 </td>
   <td style="text-align:left;"> $SPY The market tell will be when Jerome Powell liquidates his $40 million portfolio, just like he did in February 2020.
PT184 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:47:46 </td>
   <td style="text-align:left;"> $SPY futures looking like they are being forced a jab and taxed harder. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:47:16 </td>
   <td style="text-align:left;"> $SPY  
 
You&amp;#39;re not buying enough calls again, lol.   
 
You need to buy more calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:46:38 </td>
   <td style="text-align:left;"> $SPY yea....2022 is going to be wild. Better off buying an index fund and chilling this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:46:24 </td>
   <td style="text-align:left;"> $SPY Go to bed, wake up red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:45:30 </td>
   <td style="text-align:left;"> $SPY $BTC.X  Monday🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:45:23 </td>
   <td style="text-align:left;"> $SPY how is the futures are looking? Is it boolish? I don’t think so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:45:06 </td>
   <td style="text-align:left;"> $SPY $MRNA $PFE 

Serious question… why do idiots like Whoopi keep saying that if everyone was vaccinated covid would no longer spread?  

So they won’t prevent getting it but they’ll prevent spreading it? Is this just like wearing a Scooby doo mask will help protect others? 🤡

In other news, inflation, taxes, unemployment &amp;amp; interest rates on the rise. 👍🤡 SPY $350 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:44:56 </td>
   <td style="text-align:left;"> $SPY made my third and final brokerage account for defensive positions.. time to load up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:44:43 </td>
   <td style="text-align:left;"> $UVXY $SPY $SPX $NASDAQ  The end of an era could very well be upon us. Black swan? 20% I’d like to see . 40% even better. Waiting on equities to plunge shortly after. But… firearms and ammunition will continue to hedge against inflation as a physical asset. I still love my decision months ago, but damn I miss range time as much as I used to go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:44:02 </td>
   <td style="text-align:left;"> $SPY Nasdaq board is 🔥 right now lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:43:58 </td>
   <td style="text-align:left;"> $SPY 700,000 illegals are not happy with the candidate they voted for.
PT184 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:43:42 </td>
   <td style="text-align:left;"> $SPY contagion hits everything. Don’t blink. 
 https://www.reddit.com/r/Epic_Economics/comments/s0dh48/crypto_death_crossed/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:43:37 </td>
   <td style="text-align:left;"> $SPY battle between da bears n bulls.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:43:12 </td>
   <td style="text-align:left;"> $SPY are we ripping tomorrow or another day of blood bath? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:41:48 </td>
   <td style="text-align:left;"> $SPY when the folks you follow are fighting eachother in your People Stream </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:41:14 </td>
   <td style="text-align:left;"> $SPY the real criminals … won’t even allow alternative treatments 

https://www.lifesitenews.com/news/twitter-suppresses-massive-study-showing-ivermectin-reducing-covid-mortality-by-68/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:39:35 </td>
   <td style="text-align:left;"> $SPY I’d make my wife cook me dinner in her uniform when my beloved Raiders would beat the Chargers! THAT’S how badass life was before kids 😂 that pad was on the water too! I’m drunk and going to bed now! Go Raiders! Bulls are done for this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:37:30 </td>
   <td style="text-align:left;"> $SPY My biggest question right now is how do you bottle a fart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:35:59 </td>
   <td style="text-align:left;"> $SPY It’s AntiJab Federal Firing day. No forced Jab, your out of a job. So much for my body my choice. Guess that’s only politically convenient?
PT184 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:35:35 </td>
   <td style="text-align:left;"> $SPY Well, bears, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:35:31 </td>
   <td style="text-align:left;"> $SPY futures flipping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:34:24 </td>
   <td style="text-align:left;"> $SPY bulls will be in shambles in 26 minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:33:16 </td>
   <td style="text-align:left;"> $SPY Bouncing today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:31:30 </td>
   <td style="text-align:left;"> $SPY don’t call it a comeback I’ve been here for years (they just keep deleting my accounts) 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:30:37 </td>
   <td style="text-align:left;"> $SPY herd immunity incoming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:29:03 </td>
   <td style="text-align:left;"> $SPY Someone tell me this works. I&amp;#39;m just seeing clockwise 🤔.

https://youtube.com/shorts/PwUo5TTjO00?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:28:13 </td>
   <td style="text-align:left;"> $SPY remove faang from any and all indices and the world is right again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:27:31 </td>
   <td style="text-align:left;"> $MSFT $SPY $AMD 

Wow, 1 day with this software and I already paid for a full year subscription ..

Really like the custom alerts . Went in yesterday trying to build my own and found most of them were already consistent with what I want to scan for 📈🥳

🎯  tinyurl.com/sothhjfsdv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:26:17 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:26:05 </td>
   <td style="text-align:left;"> $SPY Trey Gowdy is a RINO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:24:31 </td>
   <td style="text-align:left;"> $SPY this is getting really interesting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:24:01 </td>
   <td style="text-align:left;"> $SPY $qqq no one tightens when COVID is in high gear 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:23:36 </td>
   <td style="text-align:left;"> $SPY $qqq last week was biggest bear trap ever 🔥🔥🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:22:54 </td>
   <td style="text-align:left;"> $SPY $qqq this rally is nothing. Come Tuesday we have </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:22:24 </td>
   <td style="text-align:left;"> $SPY bull trap on futures right now. Has a long way to drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:22:02 </td>
   <td style="text-align:left;"> $SPY $qqq calls printin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:20:22 </td>
   <td style="text-align:left;"> $SPY good night bulls and bears …. See you next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:18:27 </td>
   <td style="text-align:left;"> $SPY it’s coming. 🌱✌️
 https://www.reddit.com/r/Epic_Economics/comments/s0d2ix/cannabis_religion/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:18:14 </td>
   <td style="text-align:left;"> $SPY futes ripping deep green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:17:20 </td>
   <td style="text-align:left;"> $SPY being a bear is feeling a little too crowded right now. Expecting a bounce for earnings season before the real correction begins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:17:16 </td>
   <td style="text-align:left;"> $SPY all I know they using the virus to do something else . Doesnt take a vascular surgeon to figure this out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:15:34 </td>
   <td style="text-align:left;"> $SPY only fans babes going to pay for the build back better bullshit.  Oh wait, that got shit canned… oh well, they’ll pay anyway 😂🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:13:59 </td>
   <td style="text-align:left;"> $SPY shouldn&amp;#39;t have called time out. Coach panicked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:13:39 </td>
   <td style="text-align:left;"> $SPY Missed Tesla ?

Don’t miss Tesla of Aviation- Joby

Watch Joby  - 10x stock 

https://youtu.be/iRlmfFIiHbU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:12:44 </td>
   <td style="text-align:left;"> $SPY rising interest rates, taxes &amp;amp; inflation bullish af. 

Lets Go BRANDON! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:12:44 </td>
   <td style="text-align:left;"> $SPY $DWAC I miss when we had a true Businessman, Patriot, and Fighter in the White House who didnt shit his pants while visiting world leaders. 

#TRUMP2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:12:36 </td>
   <td style="text-align:left;"> $SPY you should see the pictures I have of the chargers girls in San Diego omfg I live the best life. Even the chiefs and cardinals girls. We’re connected goooooooood </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:12:21 </td>
   <td style="text-align:left;"> $SPY but weekend wallstreet was red all weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:11:17 </td>
   <td style="text-align:left;"> $SPY ATHs are more fun. Probably flattish till the economic data is released </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:10:08 </td>
   <td style="text-align:left;"> $SPY $SPX 
end it now 
https://www.npr.org/2022/01/09/1071669980/michael-lang-a-co-creator-of-the-woodstock-festival-has-died-at-77?utm_medium=social&amp;amp;utm_term=nprnews&amp;amp;utm_campaign=npr&amp;amp;utm_source=facebook.com&amp;amp;fbclid=IwAR06HiwNNc-nZ9Rjcy0oV0XVpNRLytunJWCTMYk4KXLr0B80_DNAeezriPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:10:07 </td>
   <td style="text-align:left;"> $SPY 500 next joe biden is traitor worst president of all time braindeads voted for him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:09:09 </td>
   <td style="text-align:left;"> $SPY interest rates coming up soon (as they should), hawkish fed, and SPY punched through 50 day moving average on Friday. 100 day on deck next. This market is toast! Even my buddy on the mountain slopes today has $2m in his account and wants to move to Puerto Rico so he can cash out without gains. The rich are leaving the market, it’s over this year. 🌷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:09:00 </td>
   <td style="text-align:left;"> $SPY I’m going to wet my pants at Starbucks tomorrow if we end the day green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:07:37 </td>
   <td style="text-align:left;"> $SPY $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:07:09 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:06:25 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $MSFT ..,, 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $95,959 
Goal: $100,000 by end of January. 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:05:25 </td>
   <td style="text-align:left;"> $AMC $GME $SPY   dam rip bob saget I just heard 😮‍💨 dude was one of the idgaf comics 😢 in real life. 20-22 has been brutal  for icons 😩 rip Syd Poitier as well 😞  can we get a break 😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:05:06 </td>
   <td style="text-align:left;"> $SPY omg omg omg omg omg futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:04:34 </td>
   <td style="text-align:left;"> $SPY A slide in bond prices has pushed the 10-year Treasury yield to 1.769%, its highest since early 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:02:53 </td>
   <td style="text-align:left;"> $SPY Last week was different. On every pullback since covid, the market either ripped or dipped further, a flat week after a pullback maybe indicates to me this is longer term. Definitely market&amp;#39;s BEEN overpriced and everyone has known it for a long time. But at the end of the day, it&amp;#39;s all about liquidity, which there&amp;#39;s still plenty of, but when interest rates do rise and the FED unloads their assets, the selloffs will be major, maybe SPY will be as low as $380 in 2023. I think the smart money is selling now, but if you&amp;#39;re long-term, no problem, SPY will be $10,000 in 10-40 years. This is just boom and bust cycles which ironically have become inverse to the actual economy with the FED being the sole catalyst. It&amp;#39;s been an amazing 2 years, but cycles do end, and then they start again. My $0.02. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 14:01:01 </td>
   <td style="text-align:left;"> ⏳📈💰 $SPY - Trade of the week by I.S.T. 😎
Y&amp;#39;ALL MAKE SURE TO FALL-O THEM &amp;amp; LYNX IN BAYU 🤝 THANK ME LATER 🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:59:49 </td>
   <td style="text-align:left;"> $SPY this in case you forgot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:59:31 </td>
   <td style="text-align:left;"> $SPY $DIA $VALE $GLNCY $MT 

Not good at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:59:27 </td>
   <td style="text-align:left;"> $SPY no rate hikes anytime soon. Omicron has everyone and their dogs sick. That of course, really concerns J Powell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:59:26 </td>
   <td style="text-align:left;"> $SPY  They’ll be saying buy anything under $500 before you know it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:59:25 </td>
   <td style="text-align:left;"> $SPY $QQQ 
https://youtu.be/GD272oUleIM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:58:57 </td>
   <td style="text-align:left;"> $SPY don’t forget the greatest raider and greatest athlete to ever play any game.  Bo knows trading and he is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:58:47 </td>
   <td style="text-align:left;"> $SPY stop teasing you going green or not bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:58:30 </td>
   <td style="text-align:left;"> $SPY will be $538 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:58:07 </td>
   <td style="text-align:left;"> $SPY 
If you want to be in a stock market, the most important thing is to keep learning and educating yourselves about the economy and how things work. Regardless of your trading style and types of stocks you trade; let it be penny stocks, big caps, small caps, or anything, you must be aware of what is happening around the world. Because believe it or not, everything is connected to each others. Especially now with the Feds planning to raise interest rates soon, this will have a big impact on economy. Look at how high the inflation is. Therefore, I ask you guys to do more reading and learning about what happens when Feds raise interest rates, learn what a monetary policy is, how is it going to affect the stock market, etc. And that is why I am very careful with taking long, bullish trades. Because the market will turn bearish (SP500 and big caps), and it will continue being bear market. It is very important nowadays to be up to date with everything.  

https://www.forbes.com/advisor/investing/fed-raises-interest-rates/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:57:39 </td>
   <td style="text-align:left;"> $SPY FED news Wednesday buying Puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:57:02 </td>
   <td style="text-align:left;"> $SPY get ready for a rug pull at open 10 year yield keeps rising </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:54:04 </td>
   <td style="text-align:left;"> $SPY as a Raiders fan married to a former Charger Girl, that was pretty badass! All my wife’s hot NFL friends are pissed at me 😂☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:53:58 </td>
   <td style="text-align:left;"> $SPY Has nothing to do with markets , so just block me, but I&amp;#39;ll make the call, IF the Chargers coach was not hired this past off season them HE WOUKD BE FIRED.
25% chance he CPULD be fired now too, since Chargers miss playoffs, likely, because of blunder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:53:15 </td>
   <td style="text-align:left;"> $SPY  Did anyone grab tickets to the show ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:52:32 </td>
   <td style="text-align:left;"> $SPY Steelers Fan’s wife badgering... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:51:32 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:50:55 </td>
   <td style="text-align:left;"> $SPY Don’t trust futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:50:13 </td>
   <td style="text-align:left;"> $SPY My take on the game , 38 seconds left, Raiders at 39 yard line. Chargers and Raiders could have let clock go and Raiders kick 56 yards but Chargers coach took timeout. 

It allowed Raiders to set up another play, of which they ran ball on ground to 32. And kicked a 47 yard field goal to win it. 

At very least, Raiders think twice about kicking from 54 because of farther away and greater block attempt plus it&amp;#39;s just a lot harder to kick a 54 than a 47. Raiders kicker squeaked kicks thru uprights all night too, almost all 5 really

Sounds like a bull, doesn&amp;#39;t it, or a Biden follower or, let&amp;#39;s cut the chase, JPow or B0iden

😂😂😅😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:50:10 </td>
   <td style="text-align:left;"> $SPY unpopular opinion, the bullish momentum that has dominated the 4h chart since October could be failing. We will see. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:49:55 </td>
   <td style="text-align:left;"> $SPY the only way life has any meaning is to live it eternally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:49:23 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:49:10 </td>
   <td style="text-align:left;"> $SPY bearish this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:49:07 </td>
   <td style="text-align:left;"> $SPY $NVDA $QQQ I have been able to grow my account to over 1.7 million!  100% recommend joining!.. 
 
🚀 discord.io/stk-opt-trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:48:47 </td>
   <td style="text-align:left;"> $SPY $QQQ
Interesting that the Raiders did the Steelers a favor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:48:30 </td>
   <td style="text-align:left;"> $SPY what did I miss today? Was snowboarding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:48:30 </td>
   <td style="text-align:left;"> $SPY Covid is coming to an end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:48:23 </td>
   <td style="text-align:left;"> $SPY $TSLA 

https://www.businessinsider.com/big-short-michael-burry-elon-musk-tesla-gamestop-crypto-crash-2022-1?amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:48:20 </td>
   <td style="text-align:left;"> $SPY rippin’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:48:19 </td>
   <td style="text-align:left;"> $SPY pump it Pittsburgh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:48:17 </td>
   <td style="text-align:left;"> $SPY tech goes boom tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:47:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT CANCEL THE RISING YIELDS:  DESPITE &amp;quot;MILD&amp;quot; OMNICRON VARIANT, US COVID HOSPITALIZATIONS HIT RECORD HIGH

time to rotate back into tech and bonds and out of that other stuff you just rotated into sorry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:46:49 </td>
   <td style="text-align:left;"> $SPY  SPY going to Rip tomorrow .  Just win baby! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:45:58 </td>
   <td style="text-align:left;"> $SPY $470 today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:45:31 </td>
   <td style="text-align:left;"> $BOIL $NG_F $UNG $SPY WOOOOOOOOOOOOOOOOOOOOOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:44:58 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears are pretty quiet now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:44:45 </td>
   <td style="text-align:left;"> $SPY futes tricking you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:44:38 </td>
   <td style="text-align:left;"> $SPY BEARS WHAT HAPPENED TO THE CRASH ??!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:44:12 </td>
   <td style="text-align:left;"> $SPY Live look at me finding out some of my followers political and Covid views </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:44:05 </td>
   <td style="text-align:left;"> $SPY $500 after Powell speaks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:43:53 </td>
   <td style="text-align:left;"> $ETH.X $BTC.X $SPY $QQQ Lets not be headasses like the Chargers and agree to pump the crypto market and end in a tie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:43:53 </td>
   <td style="text-align:left;"> $SPY Red Day tomorrow  https://www.youtube.com/watch?v=to_sacDcSJk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:43:20 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
God Thomas Jefferson’s inaugural address is one of if not thee best speeches ever written. 

I repair, then, fellow-citizens, to the post you have assigned me. With experience enough in subordinate offices to have seen the difficulties of this the greatest of all, I have learnt to expect that it will rarely fall to the lot of imperfect man to retire from this station with the reputation and the favor which bring him into it. Without pretensions to that high confidence you reposed in our first and greatest revolutionary character, whose preeminent services had entitled him to the first place in his country&amp;#39;s love and destined for him the fairest page in the volume of faithful history, I ask so much confidence only as may give firmness and effect to the legal administration of your affairs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:42:39 </td>
   <td style="text-align:left;"> $SPY Wen Lambo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:42:29 </td>
   <td style="text-align:left;"> $SPY 

Will bet any Steeler fan $100, straight up for next game. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:41:43 </td>
   <td style="text-align:left;"> $SPY Chargers fans tomorrow arriving at work tomorrow ⬇️⬇️⬇️ 
But it’s all good, market will be down also </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:41:28 </td>
   <td style="text-align:left;"> $SPY bears thought it was black Monday 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:41:07 </td>
   <td style="text-align:left;"> $SPY if we do end up with a bear market I hope that we still have volume and range for trading once the dust settles. 

&amp;quot;Goldman Now Expects Four Fed Hikes, Sees Faster Runoff in 2022&amp;quot;

https://ca.investing.com/news/economy/goldman-now-expects-four-fed-hikes-sees-faster-runoff-in-2022-2616608

We could go through a period of really shitty trading conditions. Position trading will likely reign again. Swing trading is so much more fun though. Day trading even more so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:40:37 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m not gonna trade spy this week. It&amp;#39;s guess work. 

Just find me individual stocks and look for a good dump or pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:39:58 </td>
   <td style="text-align:left;"> $SPY this shit bout to ejaculate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:39:16 </td>
   <td style="text-align:left;"> $SPY feel like might be green tomorrow then back to red Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:39:04 </td>
   <td style="text-align:left;"> $ARKK $SPY $QQQ $TSLA beautiful bullish flag im going to start a long position ~70/60 
 
i think arkk goes to 180 by eoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:39:03 </td>
   <td style="text-align:left;"> $SPY is currently trading in the upper part of its 52 week range, which is inline with the index. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:38:29 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:38:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $SQQQ $TSLA just your market maker doing a mini pump pre market so they can exit in the morning or tuesday,  dont be the donkeys that buying the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:38:11 </td>
   <td style="text-align:left;"> $SPY https://www.msn.com/en-us/news/us/alexandria-ocasio-cortez-tests-positive-for-covid-19/ar-AASBqsp?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:37:13 </td>
   <td style="text-align:left;"> $SPY FUTES RIPPN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:36:57 </td>
   <td style="text-align:left;"> $SPY LAC coach is a dumbass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:35:51 </td>
   <td style="text-align:left;"> $SPY Raiders Earned the Win !!! Chargers are Lucky REFs and NFL tried to help them win but NOPE.   
GO STEELERS, Never a doubt !!!!     
(Market ⬇️⬇️⬇️) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:35:28 </td>
   <td style="text-align:left;"> $SPY how fucking stupid do COVID policies and regulations look now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:33:14 </td>
   <td style="text-align:left;"> $QQQ The Nasdaq could continue higher tomorrow without big tech if all things are normal. $SPY and $DIA never made it to the 125-day average during the last pull back they could continue lower. The market could seek out safety in the over sold Healthcare Sector which would still be bullish for the Qs. Also news of the delta-omicron combined variant could make this even more possible. 

Key Levels:
QQQ - $379.86
DIA - $326.31
SPY - $465.09

Look for the indexes to close above or below these levels in the first 30-minutes of trading. This should give some sort of insight on direction. 

After a close above mark your first point of resistance to test the strength of the move higher. After a close below mark your first point of support. 

Good luck to everybody tomorrow. 🙏🏽

###
I post key levels during the trading day for specific stocks and indexes. Follow my page for more insights. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:32:35 </td>
   <td style="text-align:left;"> $SPY When the correction has been masquerading as bearish but it’s really bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:32:26 </td>
   <td style="text-align:left;"> $SPY the real question is can we learn anything new from the press conference Tuesday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:32:19 </td>
   <td style="text-align:left;"> $SPY $QQQ Anyone get a look at who was running from the BioLab building?????

Kazakhstan Denies US-Funded &amp;#39;Military Biological Lab&amp;#39; Seized By Rioters After Russia Claims Potential Pathogen Leak

MONDAY, JAN 10, 2022 - 12:00 AM
Kazakh officials have denied that a US-funded &amp;#39;military biological laboratory&amp;#39; was seized by rioters in the recent unrest, which has seen at least 160 dead since the violence broke out just one week ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:32:18 </td>
   <td style="text-align:left;"> $SPY I am here to save you all. Keep your chin up high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:31:34 </td>
   <td style="text-align:left;"> $SPY yall heard of omicron X delta album 💿 🔥🔥🔥🔥😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:31:30 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA Wild week, ready for the next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:29:38 </td>
   <td style="text-align:left;"> $SPY Rick Rule, CEO of Sprott Holdings &amp;quot;So the fact that you are able to skate through today and tomorrow and the day after on other people’s money means that ultimately, when society itself has to pay the bill, the bill is much, much, much larger.”

https://www.google.com/amp/s/finance.yahoo.com/amphtml/news/rick-rule-cash-savings-crucial-140000290.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:29:36 </td>
   <td style="text-align:left;"> $SPY $QQQ 5 red days in a row last week and people are shocked futures are going very green? If you held puts this weekend you are a greedy clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:28:42 </td>
   <td style="text-align:left;"> $SPY I believe that for tomorrow the day goes to a day or tomorrow or Friday for the fed and taper with many other factors and the stock for market rotation/tech/also other things as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:28:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:26:15 </td>
   <td style="text-align:left;"> $SPY Live look at bears now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:26:10 </td>
   <td style="text-align:left;"> $SPY The Raaaiiidddeeerrrsss 👌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:25:35 </td>
   <td style="text-align:left;"> $SPY that was out of control lol just glad Steelers are going </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:25:33 </td>
   <td style="text-align:left;"> $SPY try hard for tendie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:25:25 </td>
   <td style="text-align:left;"> $SPY goodnight guys I have work tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:25:21 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:24:06 </td>
   <td style="text-align:left;"> $SPY Better team won for the markets.
Vegas loses and they gamble millions. 

Chargers lose and they just mope on the beach </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:23:42 </td>
   <td style="text-align:left;"> $SPY $NVDA $MSFT $AMZN &amp;quot;&amp;quot;&amp;quot;&amp;quot; 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $95,959 
Goal: $100,000 by end of January. 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:23:24 </td>
   <td style="text-align:left;"> $SPY stairway to 7 and spy to 700 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:23:16 </td>
   <td style="text-align:left;"> $BTC.X  but dont short its not worth the risk  doing HTF with btc its manipulated $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:22:43 </td>
   <td style="text-align:left;"> $SPY $DWAC Everyone is fleeing away from California, even the playoffs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:22:27 </td>
   <td style="text-align:left;"> $SPY so sad I was gonna cheer them all the way they have so much heart . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:22:10 </td>
   <td style="text-align:left;"> $SPY that 1 Steelers fan they showed doe... Meme him up America </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:22:03 </td>
   <td style="text-align:left;"> $SPY 2021 was the craziest NFL season in recent memory, change my mind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:21:42 </td>
   <td style="text-align:left;"> $SPY 465 for a starter. Wed dump for sure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:21:16 </td>
   <td style="text-align:left;"> $SPY oi oi oi the futures rippiing ye $sshole mate ya bears! $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:20:55 </td>
   <td style="text-align:left;"> $SPY fuck the raiders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:20:40 </td>
   <td style="text-align:left;"> $SPY Carr isn&amp;#39;t the best QB but he is underrated for sure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:20:39 </td>
   <td style="text-align:left;"> $SPY 6 conversions on 4 and 6 , not since 30 years, Chargers end up losing tho, all for naught. 

Comeback not secured </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:20:25 </td>
   <td style="text-align:left;"> $SPY now we have to see the Steelers get shit pumped by the chiefs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:20:03 </td>
   <td style="text-align:left;"> $SPY damn crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:19:59 </td>
   <td style="text-align:left;"> $SPY me the damn spy won’t rally because the $dia is so over bought. MM’s 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:19:59 </td>
   <td style="text-align:left;"> $SPY mike Tomlin’s job saved by a hair. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:19:48 </td>
   <td style="text-align:left;"> $SPY market is SEVERELY OVERSOLD. 

Generational buying opportunity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:19:32 </td>
   <td style="text-align:left;"> $SPY Steelers Fans! Yassss 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:19:20 </td>
   <td style="text-align:left;"> $SPY pay attention to that Wednesday CPI read! SOFI CHARTER DENIED? FUD!
https://youtu.be/ucQSD9ayiv8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:19:20 </td>
   <td style="text-align:left;"> $SPY chargers fans right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:18:57 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:18:43 </td>
   <td style="text-align:left;"> $SPY raiders win = Bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:18:09 </td>
   <td style="text-align:left;"> $SPY should have called a truce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:17:58 </td>
   <td style="text-align:left;"> $SPY they should&amp;#39;ve tied </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:17:23 </td>
   <td style="text-align:left;"> $SPY where do you think the worlds money is going? Bonds? Lol. Bitcoin? Lol. Back to the Fed? Lol. 

Spy can only go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:17:13 </td>
   <td style="text-align:left;"> $SPY If Ben Rapistberger is in the playoffs, everything is possible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:16:56 </td>
   <td style="text-align:left;"> $SPY LAC coach fucked up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:16:37 </td>
   <td style="text-align:left;"> $SPY Steelers fans counting their blessings rn lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:16:25 </td>
   <td style="text-align:left;"> $SPY spy isn’t going down it’s taking the long way up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:16:21 </td>
   <td style="text-align:left;"> $SPY LAS VEGAS WON! - that is bullish very </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:15:25 </td>
   <td style="text-align:left;"> $SPY if he misses, truce negotiated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:15:23 </td>
   <td style="text-align:left;"> $SPY Steelers fans </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:14:52 </td>
   <td style="text-align:left;"> $SPY large size 4680 prolly gunna fill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:14:20 </td>
   <td style="text-align:left;"> $SPY take the tie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:14:09 </td>
   <td style="text-align:left;"> $SPY raiders bolts tie is priced in. Spy 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:13:36 </td>
   <td style="text-align:left;"> $SPY call it truce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:13:33 </td>
   <td style="text-align:left;"> $SPY Not going to end well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:13:17 </td>
   <td style="text-align:left;"> $SPY ⬆️⬆️⬆️⬆️⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:12:51 </td>
   <td style="text-align:left;"> $SPY futes are rippin - like now.
I’m watching the Sugar Daddy and Sugar Babies movie marathon in lifetime; waiting for 4:00 for PM.
Confess, I know once you tune in to lifetime you can’t change the channel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:12:42 </td>
   <td style="text-align:left;"> $SPY best NFL game in history. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:12:35 </td>
   <td style="text-align:left;"> $SPY lol steelers in trouble rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:12:03 </td>
   <td style="text-align:left;"> $SPY Still in the same channel down trend even though its up a little tonight.  The morning is a better indicator.  Sunday nights are pretty much a waste unless it moves a lot in one direction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:11:37 </td>
   <td style="text-align:left;"> $SPY soooo much doom and gloom is priced in... SPY 500s...to 550s EOY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:11:29 </td>
   <td style="text-align:left;"> $SPY the surprise that crypto kids and spy call slappers disregard, not covid, not rate hikes, BALANCE SHEET RUN OFF. 🔥☠️
Finally. That $9T everyone likes to balk at. Bye bye. ❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:11:15 </td>
   <td style="text-align:left;"> $SPY steeler watching the raiders vs chargers game right now…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:11:06 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC.X Raiders vs Chargers is nuts!!! Instant Classic 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:10:53 </td>
   <td style="text-align:left;"> $SPY thinking we gonna get a nice 2am pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:10:08 </td>
   <td style="text-align:left;"> $SPY This guy has pretty good track record! 
I trust his calls! 👍 
https://youtu.be/1gAoQ7LD-nI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:09:52 </td>
   <td style="text-align:left;"> $TSLA alright, let’s see what you are made of. 
 
55 pt (+.33%) move on the nq1! (nasdaq mini’s) in the last hour. I like the conservative but notable rise on the $SPY  minis, at about +.12% in the past Hour and some change. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:09:45 </td>
   <td style="text-align:left;"> $SPY  very </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:09:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Nas futures are zoomin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:08:22 </td>
   <td style="text-align:left;"> $SPY about to MOASS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:08:01 </td>
   <td style="text-align:left;"> $SPY they should just negotiate a tie like US and China negotiated the trade agreement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:07:01 </td>
   <td style="text-align:left;"> $SPY you all watching this game?  Holy shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:06:39 </td>
   <td style="text-align:left;"> $SPY oh bears get your buttocks ready 😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:06:08 </td>
   <td style="text-align:left;"> Market Volume Barometer 1-07-2022
Sentiment: EAGER
Volume: -6%
Real Feel: CHILLY
Cycle: BEARISH I
Portfolio: LONG
Next Day Move: SIDEWAYS
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:04:58 </td>
   <td style="text-align:left;"> $SPY This Raider Charger game is unreal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:04:48 </td>
   <td style="text-align:left;"> $SPY chargers are king of 4th downs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:04:43 </td>
   <td style="text-align:left;"> $SPY Back to red in 30 minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:04:24 </td>
   <td style="text-align:left;"> $SPY BEARS 👇👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:04:01 </td>
   <td style="text-align:left;"> $SPY futures=rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-10 13:03:15 </td>
   <td style="text-align:left;"> $SPY bro im done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 16:04:30 </td>
   <td style="text-align:left;"> $SPY $QQQ bonds selling off, dollar strengthening... Expect blood 💉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 16:01:12 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:52:18 </td>
   <td style="text-align:left;"> $QQQ can we start a GoFundMe for the dogshit bears here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:39:18 </td>
   <td style="text-align:left;"> $QQQ Im seeing bullish divergences all over the place. Bears are not looking good right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:18:42 </td>
   <td style="text-align:left;"> The whole 
world rallying tonight  
virus worse enough to stop the hikes 
 
so bad it’s good 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:15:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $TELL  
 
$PRTS  
CEO  
https://twitter.com/LevPeker/status/1476975716348563457 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:14:12 </td>
   <td style="text-align:left;"> $SPY haha it can’t get no lower because it’s 2022 numbers now Btch’s   

$nasdaq $ndx $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:12:25 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ 

FUTURES UPDATE FOR THE SHORTS 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:12:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA THE DEATH OF BOB SAGET WILL SET OFF A 2000 2008 LEVEL CRISIS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:10:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $TELL  
 
$PRTS  
CFO &amp;quot; Going from 2 distribution centers to 6 in the 3 years  
is a perfect demonstration of our success!&amp;quot;  
https://twitter.com/davidmeniane/status/1478435310056853506 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:09:03 </td>
   <td style="text-align:left;"> $QQQ &amp;gt;&amp;gt; Fast STO @ 8.82 on the daily chart &amp;gt;&amp;gt;
Bounces followed the last 4 dips below 20 &amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:08:04 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:06:31 </td>
   <td style="text-align:left;"> $QQQ 390 lotto calls for tomorrow are gonna print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 15:03:10 </td>
   <td style="text-align:left;"> $SPY $qqq nq calls dirt cheap.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:55:36 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:54:39 </td>
   <td style="text-align:left;"> $QQQ &amp;gt;&amp;gt; Daily Chart &amp;gt;&amp;gt;

If 372.50 support breaks there could be a drop to the 200 day simple moving average at 362.59 &amp;gt;&amp;gt;

 The October 13 Gap down at 360 could fill &amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:54:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA BOB SAGET DIED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:51:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA 2000 2008 level crash incoming hide yo canoes 🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:48:50 </td>
   <td style="text-align:left;"> $QQQ We really need a relief rally so I can get the hell out of my long positions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:43:02 </td>
   <td style="text-align:left;"> $QQQ strong overnight action! Have we bottomed? $DKNG $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:36:53 </td>
   <td style="text-align:left;"> $QQQ nasdaq open interest up but it’s down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:34:10 </td>
   <td style="text-align:left;"> $QQQ lets goo to the moon calls tomorrow will print!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:30:14 </td>
   <td style="text-align:left;"> $QQQ Russia has just moved into Ukraine with 300k troops tonight blood market tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:29:51 </td>
   <td style="text-align:left;"> Ticker: $QQQ 
Buy: January 12, 2022 $380.00 Calls 
Entry Price: $3.66 - $3.71 
Exit Price: $4.83 
Stop Loss: $3.22 
Potential ROI: 32% 
Estimated Hold Time: 66 Minutes 
Alert Courtesy Of: https://www.fastscalp.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:26:55 </td>
   <td style="text-align:left;"> $QQQ futures up, but weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:26:48 </td>
   <td style="text-align:left;"> $QQQ Not trusting these futures. May be  a repeat of last week - rip at open and slow bleed. Hope I&amp;#39;m wrong because I&amp;#39;m out of ammo.  Trying to stay positive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:24:01 </td>
   <td style="text-align:left;"> $SPY $qqq no one tightens when COVID is in high gear 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:23:36 </td>
   <td style="text-align:left;"> $SPY $qqq last week was biggest bear trap ever 🔥🔥🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:22:54 </td>
   <td style="text-align:left;"> $SPY $qqq this rally is nothing. Come Tuesday we have </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:22:02 </td>
   <td style="text-align:left;"> $SPY $qqq calls printin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:21:35 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:06:48 </td>
   <td style="text-align:left;"> $QQQ guys buy buy buy buy OML if you don’t buy you will miss out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:06:15 </td>
   <td style="text-align:left;"> $QQQ omg omg oh my god the futes are ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:05:39 </td>
   <td style="text-align:left;"> $INTC $QQQ $NOK 

It works ! Very quick response, even in  office hours . Thanks a lot!!

🤑  tinyurl.com/yuouffvk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 14:02:07 </td>
   <td style="text-align:left;"> $EXAS $NVNXF $QQQ $AMC &amp;quot;&amp;quot;&amp;quot; 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $95,959 
Goal: $100,000 by end of January. 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:59:25 </td>
   <td style="text-align:left;"> $SPY $QQQ 
https://youtu.be/GD272oUleIM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:58:17 </td>
   <td style="text-align:left;"> New article published today:
4 Best Long-Term Performance U.S. Large Cap Growth ETFs
https://deepvalueetfaccumulator.com/blog/4-best-long-term-performance-u-s-large-cap-growth-etfs-1-5/ 
$QQQ $IWY $ONEQ $MGK $VONG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:51:19 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;m bagholding $5k in QQQ calls. waiting for a quick double in 2 weeks when this come back to $400.
give me that and I&amp;#39;ll start to buy puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:49:07 </td>
   <td style="text-align:left;"> $SPY $NVDA $QQQ I have been able to grow my account to over 1.7 million!  100% recommend joining!.. 
 
🚀 discord.io/stk-opt-trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:48:47 </td>
   <td style="text-align:left;"> $SPY $QQQ
Interesting that the Raiders did the Steelers a favor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:48:29 </td>
   <td style="text-align:left;"> $NASDAQ $QQQ can we finally start to see some green? Long term portfolio is getting killed 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:47:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT CANCEL THE RISING YIELDS:  DESPITE &amp;quot;MILD&amp;quot; OMNICRON VARIANT, US COVID HOSPITALIZATIONS HIT RECORD HIGH

time to rotate back into tech and bonds and out of that other stuff you just rotated into sorry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:44:58 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears are pretty quiet now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:44:34 </td>
   <td style="text-align:left;"> $QQQ wow this was in the gutter red now bright green, what happened?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:43:53 </td>
   <td style="text-align:left;"> $ETH.X $BTC.X $SPY $QQQ Lets not be headasses like the Chargers and agree to pump the crypto market and end in a tie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:43:20 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
God Thomas Jefferson’s inaugural address is one of if not thee best speeches ever written. 

I repair, then, fellow-citizens, to the post you have assigned me. With experience enough in subordinate offices to have seen the difficulties of this the greatest of all, I have learnt to expect that it will rarely fall to the lot of imperfect man to retire from this station with the reputation and the favor which bring him into it. Without pretensions to that high confidence you reposed in our first and greatest revolutionary character, whose preeminent services had entitled him to the first place in his country&amp;#39;s love and destined for him the fairest page in the volume of faithful history, I ask so much confidence only as may give firmness and effect to the legal administration of your affairs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:40:02 </td>
   <td style="text-align:left;"> $QQQ is currently trading in the upper part of its 52 week range, which is inline with the index. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:39:04 </td>
   <td style="text-align:left;"> $ARKK $SPY $QQQ $TSLA beautiful bullish flag im going to start a long position ~70/60 
 
i think arkk goes to 180 by eoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:38:55 </td>
   <td style="text-align:left;"> $QQQ Nasdaq headed to 14500. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:38:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $SQQQ $TSLA just your market maker doing a mini pump pre market so they can exit in the morning or tuesday,  dont be the donkeys that buying the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:35:30 </td>
   <td style="text-align:left;"> $QQQ We’re going to be burning money in the fireplace to stay warm soon. Nothing to be worried about right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:35:23 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-09 Trade Analysis Video: 
https://www.youtube.com/watch?v=ac8lEf8SbHU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:33:14 </td>
   <td style="text-align:left;"> $QQQ The Nasdaq could continue higher tomorrow without big tech if all things are normal. $SPY and $DIA never made it to the 125-day average during the last pull back they could continue lower. The market could seek out safety in the over sold Healthcare Sector which would still be bullish for the Qs. Also news of the delta-omicron combined variant could make this even more possible. 

Key Levels:
QQQ - $379.86
DIA - $326.31
SPY - $465.09

Look for the indexes to close above or below these levels in the first 30-minutes of trading. This should give some sort of insight on direction. 

After a close above mark your first point of resistance to test the strength of the move higher. After a close below mark your first point of support. 

Good luck to everybody tomorrow. 🙏🏽

###
I post key levels during the trading day for specific stocks and indexes. Follow my page for more insights. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:32:19 </td>
   <td style="text-align:left;"> $SPY $QQQ Anyone get a look at who was running from the BioLab building?????

Kazakhstan Denies US-Funded &amp;#39;Military Biological Lab&amp;#39; Seized By Rioters After Russia Claims Potential Pathogen Leak

MONDAY, JAN 10, 2022 - 12:00 AM
Kazakh officials have denied that a US-funded &amp;#39;military biological laboratory&amp;#39; was seized by rioters in the recent unrest, which has seen at least 160 dead since the violence broke out just one week ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:31:30 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA Wild week, ready for the next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:29:36 </td>
   <td style="text-align:left;"> $SPY $QQQ 5 red days in a row last week and people are shocked futures are going very green? If you held puts this weekend you are a greedy clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:28:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:28:09 </td>
   <td style="text-align:left;"> $NASDAQ $QQQ Does this mean $VIX going fall to $13 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:25:21 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:21:58 </td>
   <td style="text-align:left;"> $AMC $QQQ $AMD ,,, 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $95,959 
Goal: $100,000 by end of January. 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:18:20 </td>
   <td style="text-align:left;"> $QQQ gonna be a fun week. Wednesday cpi read holds the fate of this market. SOFI CHARTER DENIED? FUD!
https://youtu.be/ucQSD9ayiv8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:17:03 </td>
   <td style="text-align:left;"> $QQQ Next week is basically a tug of war between bears and bulls. Whether tech breaks key support level or bounces off, I believe in the latter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:15:54 </td>
   <td style="text-align:left;"> $QQQ finally
 https://www.reddit.com/r/Epic_Economics/comments/s0bxch/balance_sheet_runoff_stock_market_crypto_killer/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:11:17 </td>
   <td style="text-align:left;"> $QQQ 16,000 or 14,000? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:11:13 </td>
   <td style="text-align:left;"> $QQQ brr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:11:06 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC.X Raiders vs Chargers is nuts!!! Instant Classic 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:09:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Nas futures are zoomin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:07:47 </td>
   <td style="text-align:left;"> $QQQ although futures seem to be bouncing off of 15600 level, we are going down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:06:08 </td>
   <td style="text-align:left;"> Market Volume Barometer 1-07-2022
Sentiment: EAGER
Volume: -6%
Real Feel: CHILLY
Cycle: BEARISH I
Portfolio: LONG
Next Day Move: SIDEWAYS
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:03:24 </td>
   <td style="text-align:left;"> How To Tell If A Stock Has Bottomed Out

$QQQ $DWAC $NVDA $RIVN $PLUG

https://www.chartlearning.com/2021/12/how-to-tell-of-stock-has-bottomed-out.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:02:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA next goal is to break out of this channel and1 hour 21 ema, if we can do that.. we are set </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 13:00:42 </td>
   <td style="text-align:left;"> This market is set to go absolutrly INSANE higher - $qqq is bouncing off the bottom 
of its range as it has every last time, $spy cant even sustain 3% off all 
time highs - Powell probably scared shirtless to be hawkish - everyone is scared and short even though $vxx says otherwise OH MY  
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:59:50 </td>
   <td style="text-align:left;"> $QQQ gonna use money from these dogshit bears to treat folks tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:58:59 </td>
   <td style="text-align:left;"> $QQQ yes . dump all fart bucks into cumcoin immediately </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:53:43 </td>
   <td style="text-align:left;"> $QQQ $NASDAQ $TQQQ $AMZN Thou shall not celebrate futures moves less than +/- 1%. Easily disappear by open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:53:39 </td>
   <td style="text-align:left;"> $NASDAQ does anyone see the social pump going on here $IWM $ZOM $AMC $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:49:59 </td>
   <td style="text-align:left;"> $QQQ pretty nice! This guy has a good track record https://youtu.be/1gAoQ7LD-nI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:48:15 </td>
   <td style="text-align:left;"> $QQQ $SPY my only regret is not buying enough calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:47:16 </td>
   <td style="text-align:left;"> $QQQ Futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:46:12 </td>
   <td style="text-align:left;"> $QQQ Futes are green but it needs to get back above Friday’s highs and stay above it all through tomorrow for a green market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:45:17 </td>
   <td style="text-align:left;"> $QQQ 15 mins till bigger moves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:41:20 </td>
   <td style="text-align:left;"> $QQQ I am Da Charly Flow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:38:12 </td>
   <td style="text-align:left;"> I don&amp;#39;t understand how we get so excited about companies that loan money to literally anyone. After 2008 Shouldn&amp;#39;t it be lesson learned? Talking $AFRM $UPST  ETC! Trade it but do you have to own it? $spy $qqq $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:38:10 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ interesting week coming. Going to be volatile. Let’s make lots of money from both sides. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:37:14 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:36:56 </td>
   <td style="text-align:left;"> $NASDAQ wtf is this ticker and why is it trending

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:36:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $DXY 

Weekend Market Recap for Saturday 1/8/2022 for trending #Stocks #Bitcoin #Gold #Silver
https://youtu.be/IjgZcjBmh-0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:36:41 </td>
   <td style="text-align:left;"> $QQQ Break the fookin 15650 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:36:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 
BEARS WHAT HAPPENED TO THE CRASH ???!
Five hours ago when futures opened and were down .4  percent, u said limit down circuit breakers ??!! Now futures ALL GREEN and nasdaq getting a pump and let me guess your response “FUTures don’t MATtter, red by morning?!” 😂😂😂
FUTURES UPDATE FOR THE SHORTS  👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:35:24 </td>
   <td style="text-align:left;"> $SPY wallstreet does not want to help you they function only to make money so what makes you think the analysts from any investing firm have your interests in mind ! $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:34:56 </td>
   <td style="text-align:left;"> $AAPL $CRM  $MSFT $GOOG $QQQ Here’s something to ponder, what if inflationary forces ease soon as the supply chain bottle necks improve?  Would that become a big head fake for papa J?  He would then calm down his easing stance and techs would fly again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:34:22 </td>
   <td style="text-align:left;"> $QQQ guys let’s not let green Futes at this hour get you too amped. There’s been too many times Futes ripped overnight and crashed on market open. Be cautious. I hope it does rip Tom AM tho. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:33:22 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:30:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures green, the bears are in big time trouble tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:30:36 </td>
   <td style="text-align:left;"> $QQQ futures green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:28:07 </td>
   <td style="text-align:left;"> ‪NEW Article: “Nasdaq 100 Testing Key Support… Will It Hold?” - https://www.seeitmarket.com/nasdaq-100-etf-qqq-testing-key-support-will-it-hold/‬ 
 
‪by @marketminute $QQQ $SPY $IWM $SMH $IYT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:25:28 </td>
   <td style="text-align:left;"> $DJIA  $SPY $QQQ $TLT  WHO ARE YOU LISTENING TO?https://www.youtube.com/watch?v=feFREg4A1oI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:25:21 </td>
   <td style="text-align:left;"> $QQQ $SPY 420 coming in soon 
wave 3 up baby 
if we can break this channel tonight, tomorrow we are going to the fucking moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:21:48 </td>
   <td style="text-align:left;"> $QQQ y mooning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:20:38 </td>
   <td style="text-align:left;"> $AMC $SPY $QQQ $GME Futures are green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:18:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:18:09 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ 

LETS US BULLS JOIN TOGETHER AND SQUEEZE ALL THE SHORTS AND BEARS AWAY FROM TECH STOCKS. BULLS TAKE OVER AGAIN TOMORROW MONDAY JANUARY 10th!!! SPREAD THE WORD!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:17:45 </td>
   <td style="text-align:left;"> $QQQ Massive bear trap. Big green day incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:11:45 </td>
   <td style="text-align:left;"> $QQQ Enough is enough......you fcuking QQQ go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:09:14 </td>
   <td style="text-align:left;"> $QQQ 
Naz rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:09:08 </td>
   <td style="text-align:left;"> $SPY  $QQQ 😉💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:05:39 </td>
   <td style="text-align:left;"> $spy $qqq 🧃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:05:30 </td>
   <td style="text-align:left;"> $QQQ Three bond auctions this week starting Tuesday should keep a lid on yields. https://www.cnbc.com/2022/01/07/inflation-rising-rates-and-the-federal-reserve-could-whip-stocks-around-in-the-week-ahead.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:04:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:03:17 </td>
   <td style="text-align:left;"> $QQQ Politicians can no longer stand by and allow waves of covid hysteria to affect markets. We must have a secret national security order to nationalize all exchanges and set prices directly higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:02:37 </td>
   <td style="text-align:left;"> $SPY $QQQ I love it when old timers try calling out bear markets and corrections lol..everytime they turn from bull to bear only means one thing...BTMFD AND WE SAIL TO ATHs. LFG PUSH TOMORROW! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:00:36 </td>
   <td style="text-align:left;"> $QQQ Working hard to take market up! up! up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 12:00:17 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Still working...lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:58:16 </td>
   <td style="text-align:left;"> $QQQ 390 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:57:31 </td>
   <td style="text-align:left;"> $QQQ people are saying futures are crashing or like deep red.  Are we looking at the same futes???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:57:03 </td>
   <td style="text-align:left;"> $QQQ $SPY qqq above the 1 hour 9 ema 
3 minutes till candle close, as long as we stay above it, tomorrow will be very green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:55:46 </td>
   <td style="text-align:left;"> Stock futures fall after S&amp;amp;P 500 posts 4-day losing streak

$SPY $QQQ
 https://www.cnbc.com/2022/01/09/stock-market-futures-open-to-close-news.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:50:34 </td>
   <td style="text-align:left;"> $QQQ it will either go up or go down😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:50:02 </td>
   <td style="text-align:left;"> $QQQ JP Tuesday again then the 26th🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:48:20 </td>
   <td style="text-align:left;"> $SPY If FURUS really make money in the market, why do they sell courses for money? 
$qqq $afrm $amd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:43:17 </td>
   <td style="text-align:left;"> $IWM $spy $qqq main question u have to ask is does wall street want to be short or squeeze every ounce of gain out Q1 so the bonuses pays for 2021 taxes… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:40:53 </td>
   <td style="text-align:left;"> $QQQ powel to crush market this week. He will use some strong new words </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:38:18 </td>
   <td style="text-align:left;"> $QQQ if everyone had just gotten their vaccine we’d still be green and $spy would be $600 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:37:56 </td>
   <td style="text-align:left;"> $QQQ tomorrow I think the price of this will change </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:37:16 </td>
   <td style="text-align:left;"> $QQQ Sorry millennials and Gen z, the transfer of wealth is done. You get to hold the bags </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:36:53 </td>
   <td style="text-align:left;"> $QQQ I am buying  Beat down stock $WW. we all buying $WW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:36:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Those are COVID SHOTS NOT a Vaccine. 
They Changed the definition of a Vaccine to support their Agenda. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:36:06 </td>
   <td style="text-align:left;"> $SPY $QQQ 2030 FOMC Meeting Minutes… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:36:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 50999000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:34:11 </td>
   <td style="text-align:left;"> $QQQ $SPY  $TNX .... 10yr futes ..... a break of the 200wk would be most constructive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:32:33 </td>
   <td style="text-align:left;"> $QQQ need this to open at 375 plz lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:25:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Pelosi bought the dip.  

They will keep printing money until they literally they can’t.  

https://twitter.com/fxhedgers/status/1480366953248083968?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:18:00 </td>
   <td style="text-align:left;"> $QQQ all you bulls and bears better believe this will go up or down tomorrow.  
 
Because it will. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:17:48 </td>
   <td style="text-align:left;"> $AABB Lets go baabby !! AABB to $7 Q1 2023 on $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:17:30 </td>
   <td style="text-align:left;"> $MCO2.X 

$NASDAQ $QQQ $AMC $GME

Crypto that saves trees when making coins… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:16:07 </td>
   <td style="text-align:left;"> $QQQ will this see $400 before the FANGMANT report earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:13:31 </td>
   <td style="text-align:left;"> https://youtube.com/watch?v=IBBANiV8LBE&amp;amp;feature=share
$qqq $iwm $spy
Weekly update, hope it helps! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:12:53 </td>
   <td style="text-align:left;"> $BABA china indexes deep green again as US futures look shakey. Only a matter of time before the $TSLA degenerates start to chase gains and pile into Chinese tickets. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:12:02 </td>
   <td style="text-align:left;"> $AMC $NASDAQ $QQQ 

GUYS $MCO2.X 

GREEN CRYPTO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:11:02 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $BA black 🦢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:10:33 </td>
   <td style="text-align:left;"> $SPY um I thought nasdaq was tech. So why people saying small caps are gonna run because nasdaq is trending (btw I put 0 importance into &amp;quot;trending&amp;quot;). 

But small caps is Russell $IWM. 

nasdaq is $QQQ , yes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:06:38 </td>
   <td style="text-align:left;"> $SPY $QQQ so will the Media hide the VAX truth again and say the sorta funny man died jacking-off until he went blind and fell over a railing and landed on a Dis Dwarf? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:05:14 </td>
   <td style="text-align:left;"> $QQQ market exploding to upside 👆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:01:04 </td>
   <td style="text-align:left;"> $SPY $QQQ Riding you all the way!!! https://youtu.be/h-dsLyGGjlY?t=137 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 11:00:55 </td>
   <td style="text-align:left;"> $AMC $GME Me and my tin foil hat don’t believe that the 5g rollout on Jan 22 is a coincidence with the Jan 22 options. Massive 5g rollout this month so don’t be surprised if many get sick. New variants etc... $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:50:21 </td>
   <td style="text-align:left;"> $QQQ $SPY photo was when nasdaq was down -.5% on futes, now up .25%. Someone tell retail bears like @FeelsBearish @iTradeBetter to STFU lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:47:12 </td>
   <td style="text-align:left;"> $QQQ all this sell-off just means good buying opportunity for long term investors like me. Thank you for dropping lower. Can&amp;#39;t wait to see my account in 20+ years after buying many shares of this for a huge discount this year. (if we have more selloff) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:44:41 </td>
   <td style="text-align:left;"> Futures RIPPIN off low $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:43:57 </td>
   <td style="text-align:left;"> $AMD $QQQ  bears sounding dumb as ever, sky is falling, sky is falling, meanwhile bulls buyin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:43:50 </td>
   <td style="text-align:left;"> $spy $QQQ  
PELOSI OPENS THE DOOR TO VIRUS AID IN SPENDING PLAN AS OMICRON RAGES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:43:04 </td>
   <td style="text-align:left;"> $QQQ $SPY Two big days this week:
• Powell speaks on Tuesday
• CPI at 8:30am on Wednesday 
Any hawkish comment or high CPI means growth selloff to get worse IMO. I expect good buying opportunities this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:42:56 </td>
   <td style="text-align:left;"> $QQQ who here thinks jp will like to tank mkts on his confirmation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:41:53 </td>
   <td style="text-align:left;"> 🚨 WEEKLY MARKET CALENDAR 🚨 :

$SPY - $QQQ - $NDAQ - $IWM - $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:41:30 </td>
   <td style="text-align:left;"> $QQQ fuse it lit 🔥 what an easy chart moon is the only option from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:40:09 </td>
   <td style="text-align:left;"> $SPY $QQQ - Futures so far, what are we expecting for tomorrow?
💚 - FOLLOW 
❤ - LIKE 

LET&amp;#39;S GO.! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:39:31 </td>
   <td style="text-align:left;"> $DKNG oh snap and $QQQ  is heating up? Bears are cooked! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:38:32 </td>
   <td style="text-align:left;"> $QQQ bear meat on the menu!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:37:15 </td>
   <td style="text-align:left;"> $spy $qqq S&amp;amp;P about to flip green too ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:36:52 </td>
   <td style="text-align:left;"> $QQQ 1 contract NQ bot already up over $800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:35:58 </td>
   <td style="text-align:left;"> $SPY $QQQ bought these at the close ............ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:34:26 </td>
   <td style="text-align:left;"> $QQQ sell everything it’s over !!!! You will lose everything ahhhhhhhhh. We will crash to 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:33:34 </td>
   <td style="text-align:left;"> $QQQ 
Rotation back to tech for the bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:33:24 </td>
   <td style="text-align:left;"> $QQQ hmmmmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:32:26 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA  
Tuesday confirmation 
🚀🇺🇲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:31:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK Future are up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:30:56 </td>
   <td style="text-align:left;"> $QQQ big boys back to scoop all bargains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:29:43 </td>
   <td style="text-align:left;"> Trade alert on $SQQQ delivered today at 9:01AM CDT on 1/7/2022 🎯

Server link in the bio for winning alerts and for those eager to learn. $TQQQ $QQQ $NG_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:28:52 </td>
   <td style="text-align:left;"> $QQQ the shorts are thinking they going to get rich. They going to get fcked so hard next few months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:27:00 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:26:49 </td>
   <td style="text-align:left;"> $SPY $QQQ From red to green. THE SHOW MUST GO ON!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:26:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Futes are looking bullish! Is everybody ready for a green Monday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:26:25 </td>
   <td style="text-align:left;"> $QQQ wen moon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:26:18 </td>
   <td style="text-align:left;"> $QQQ what&amp;#39;s your favorite play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:25:48 </td>
   <td style="text-align:left;"> $SPY $QQQ This is what you call Classic manipulation by wallstreet. They want you to believe the dump is over...It&amp;#39;s far from done. We&amp;#39;ve only just begun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:25:32 </td>
   <td style="text-align:left;"> $QQQ Lets go boys prrr prrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:23:35 </td>
   <td style="text-align:left;"> $QQQ $SPY FUTES RIPPIN

(i didn&amp;#39;t even check yet tbh) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:22:55 </td>
   <td style="text-align:left;"> $QQQ bears getting destroyed tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:21:43 </td>
   <td style="text-align:left;"> $QQQ hahah. Bulls getting excited </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:21:26 </td>
   <td style="text-align:left;"> $SPY $QQQ We will continue to hold to our long term inflationary outlook based on Pokémon card valuations until the climate changes… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:19:05 </td>
   <td style="text-align:left;"> $QQQ implied open +23 

Let’s roll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:18:27 </td>
   <td style="text-align:left;"> $QQQ - They pop it, then drop it hard Monday. Sell into any upward momentum 

Powell will be spitting out dove feathers during Tuesday’s testimony.

Then the peanut gallery gets to tell their tales. Wait until one of the fed boneheads mentions besides quicker tapering, additional interest rate hikes, selling assets, they bring up the issue of requiring banks to increase their reserves💩

What happened to transitory inflation 🤣🤣🤣🤣

Clueless Fed in crisis management mode. Prepare for more pain, unless you’re buying puts at the open tomorrow 💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:15:57 </td>
   <td style="text-align:left;"> $QQQ 
All them puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:15:31 </td>
   <td style="text-align:left;"> $QQQ futures green. Shorts screwed！ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:12:30 </td>
   <td style="text-align:left;"> $SPY $qqq NQ 100 point reversal 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:11:32 </td>
   <td style="text-align:left;"> $QQQ is always a winners </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:11:09 </td>
   <td style="text-align:left;"> $QQQ Trading the futures like a champion. What a Beautiful day so far. 🙂🙃🥰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:11:01 </td>
   <td style="text-align:left;"> The general belief is once interest rates go up the market will crash. As if we didn&amp;#39;t know this from the beginning interest rates at some point would go up. I&amp;#39;m not one to try and call bottoms, but I feel fairly confident interest rates hike solidifies the bottom for growth stocks. If not, many will be trading below cash on hand, that would be equal to if not worse than dot com bubble. 71% stocks on Nasdaq are down 20%+.  
 
Assuming this is true, $WISH will organically go up along with many other growth stocks because its &amp;quot;priced in&amp;quot;. Back in 2009 markets bottomed in the worst economic conditions. Market is also forward looking which would make sense that the last 11 months were leading towards this event. Just my opinion. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:10:31 </td>
   <td style="text-align:left;"> $QQQ Does anyone think Kimye will get back with Kanye? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:10:25 </td>
   <td style="text-align:left;"> $QQQ tech futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:08:53 </td>
   <td style="text-align:left;"> $SPY $QQQ… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:08:46 </td>
   <td style="text-align:left;"> Economy Week Ahead: the Fed, Inflation, Consumers

https://www.google.com/amp/s/www.wsj.com/amp/articles/economy-week-ahead-the-fed-inflation-consumers-11641758401

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:08:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
NEVER DOUBT THE BROCCOLI MAN!!🥦

Few understand this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:07:04 </td>
   <td style="text-align:left;"> $QQQ $SPY we all should have bought the dip more on Friday.  I was to tentative…dumb.     We going higher this week.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:07:00 </td>
   <td style="text-align:left;"> $QQQ fk the QQQs... should only drop another 1k pts to bury these complacent bulls altogether.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:05:19 </td>
   <td style="text-align:left;"> $PINS overweight rating issued and a $53 PT today! $SNAP $TWTR $FB $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:05:01 </td>
   <td style="text-align:left;"> $SPY $QQQ Even the Chinese market is green and it is the weakest market in the world, our market should do very well tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:03:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures almost green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:03:29 </td>
   <td style="text-align:left;"> $QQQ 3% would be nice to start with </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:01:05 </td>
   <td style="text-align:left;"> $QQQ bears say it’s dropping when futes up and down.  Guess from here on out bears can’t quote futures as a bear signal.  (But I’m sure they will in the next five minutes) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:01:01 </td>
   <td style="text-align:left;"> NEW VIDEO JUST POSTED ON TEH Y-TUBE CHANEL PLS TUNE IN.. ARE YOU PLAYING PUTS OR CALLS ON $SPY $QQQ $BTC.X latex726cd6bd4fb79371c0a82af389a74c00$ 2 GAMER HIT JAGS ML- 49ERS ML... 55X ENTEY BOOOOM!! CONGRATS FAM #LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:00:45 </td>
   <td style="text-align:left;"> $NASDAQ $SPY $QQQ bulls and bears cheering a .01% change to either side is hilarious... i can&amp;#39;t beleive this app is free 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:00:44 </td>
   <td style="text-align:left;"> $QQQ Seems like this will pump big tomorrow. My biggest worry is a dump on Tuesday because of the CPI report the following morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:00:26 </td>
   <td style="text-align:left;"> $QQQ just like that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 10:00:16 </td>
   <td style="text-align:left;"> $SPY $QQQ 

So the Santa Claus rally didn&amp;#39;t really materialize.
Betty White&amp;#39;s 100th birthday would have been January 17th.
How &amp;#39;bout a Betty White rally?
I&amp;#39;m in.  
Will kick it off by adding more $TTD, $ISRG, or $SOFI tomorrow.
White wedding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:58:26 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:58:20 </td>
   <td style="text-align:left;"> $QQQ there she goes .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:58:13 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:58:10 </td>
   <td style="text-align:left;"> $SPY $VXX $QQQ The Vix futures just GOT CRUSHED. FEAR IS FADING THAT QUICK ALREADY 🤣😂🤣😂🤣😂 

Wen Crash??? 🤔🤣😂🤣😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:57:57 </td>
   <td style="text-align:left;"> $SPY $qqq 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:56:27 </td>
   <td style="text-align:left;"> $SPY $QQQ 😂😂🤣😂🤣😂 let’s gooooooo baby!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:53:04 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $SOXL $TQQQ 

Tech is oversold! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:52:45 </td>
   <td style="text-align:left;"> $SPY $QQQ NQ $15500 is the immovable object.  💪

This market just to strong to rollover. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:51:16 </td>
   <td style="text-align:left;"> $NQ_F: Expecting a bounce in tech tomo, but obviously if this support doesn&amp;#39;t hold, look out below. 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:48:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM MegaCap Tech is the Achilles heel for markets this year along with anything that Cathie Wood owns. 
 
She is the New smaller brassier wearing Gartman/Cramer/etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:48:19 </td>
   <td style="text-align:left;"> $WIMI WIMI Hologram Cloud Becomes the New Force of Technological Innovation, Helps the Ecological Development of 3D Holographic Projection $QQQ 
https://www.digitaljournal.com/pr/wimi-hologram-leads-the-new-trend-of-5g-hologram-the-nobelists-holographic-appearance-presented-on-idf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:48:07 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:46:02 </td>
   <td style="text-align:left;"> $SPY $QQQ if Crude drops anchor it&amp;#39;ll all follow. 
 
If Banks rollover Monday it could be Ugly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:44:51 </td>
   <td style="text-align:left;"> $QQQ , $SPY , $IWM , $IWO , $RUT :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:44:40 </td>
   <td style="text-align:left;"> $SPY $QQQ Monday morning field trip… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:43:59 </td>
   <td style="text-align:left;"> ETF Sentiment Weekly Recap: $QQQ is the #2 ETF that institutions traded this week with 802.5K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:43:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA this market could tank 10% or more!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:43:26 </td>
   <td style="text-align:left;"> $SPY, $QQQ, $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:42:18 </td>
   <td style="text-align:left;"> $SPY $QQQ 

More fun ahead. It looks like there is no real need to protect ourselves from the COVID 19 virus anymore. 

 Skip the masks, skip those vaccination mandates, feel free to embrace strangers with full upper body hugs because the sooner we can get COVID, the sooner we can put an end to this global dilemma. Now wouldn&amp;#39;t that be worth it? Time will tell.

Meanwhile back at the Ranch, the fight for this and that continues from both sides in attempts to somewhat stem the spread.

I get a kick of the in- your- face anti-vaxxers who died from COVID 19 in the last year. Yeah, that didn&amp;#39;t work out too well for them and actually thousands who followed their flawed well spoken directives. Yeah, losing loved ones at the hands of others spitting in your face is just not cool. Even the possibility of death is not a deterrent!  

I would love to see this nasty virus come to a global end by July 4th but if it doesn&amp;#39;t, we may be going South at a much quicker rate than most thought.

Stay safe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:39:29 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $BTC.X   
 
This has been my wallpaper for a while now. 
 
They&amp;#39;re distracted, in shock and awe, at this new benign virus marketed brilliantly as the doomsday disease. 
 
While in the background, is the permanent destruction of reason, truth, and the future prosperity/growth of anglophone countries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:38:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Who’s ready to get strange tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:35:59 </td>
   <td style="text-align:left;"> Weekly Watch-List comin at you.  
 
You excited? I am!!!!!!! 
 
$SPY $XBI $UVXY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:35:00 </td>
   <td style="text-align:left;"> $QQQ outperforms 72% of all stocks! https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:33:39 </td>
   <td style="text-align:left;"> Beautiful,  🐻❤ https://www.investing.com/indices/indices-futures  $tsla $spy $qqq $ccl $f and more ✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:32:30 </td>
   <td style="text-align:left;"> $QQQ someone better put their foot in...incoming cumluative nasty spooks...and dot come it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:31:53 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM $DIA   
 
I find it really intriguing  
that 50 years ago 
 
everyone believed in eugenics, and was praised for their support 
(all the ivy league university professors, capitalists, presidents, politicians.  heck, even that blind girl Helen Keller, as well as Margaret Sanger, founder of Planned Parenthood) 
 
that today 
 
no one believes in eugenics, and is ruthlessly shamed if they do. 
 
It&amp;#39;s hilarious how quickly the definition of &amp;quot;bad&amp;quot; or &amp;quot;evil&amp;quot; ideology can change.  Silly humans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:30:53 </td>
   <td style="text-align:left;"> $NASDAQ it&amp;#39;s time for the small caps to get some attention too - the top has been getting frothy for far too long.

Rotation starts this week 👀

$SPY $QQQ $IVW $RUA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:29:29 </td>
   <td style="text-align:left;"> $SPY $QQQ earnings will take the market higher and $TSLA and others will recover ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:27:08 </td>
   <td style="text-align:left;"> $SPY $QQQ See you in the morning bear whale short you dead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:25:47 </td>
   <td style="text-align:left;"> GS Sentiment Indicator 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:23:46 </td>
   <td style="text-align:left;"> $QQQ $SPY Ya right. The $VIX is up 1.4% and both SPY and QQQ are flat? Ya right, I call bullshit!
Scum bags MM&amp;#39;S are the best in trying to make you believe the bleeding is over 🤣🤣🤣🤣📖📖📖🔻🔻🔻🚽🚽🚽
More pain coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:19:43 </td>
   <td style="text-align:left;"> $QQQ time to slaughter the dogshit bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:16:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA HEY BULLS HOW ARE THINGS 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:15:50 </td>
   <td style="text-align:left;"> $QQQ, $AAPL  , $LCID - my favorite stocks In my portfolio !! A true winner! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:15:14 </td>
   <td style="text-align:left;"> $QQQ Too much beating, time to rise phoenix </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:14:31 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK 

Wow, this is such a shocker who would’ve ever guessed that this would happen.😱 Since when does the muskrat not met deadlines that he sets, look at some of his “finest” examples of timelines that he’s managed to meet (robotaxis, cybertruck, giga~shit and so on) oh... wait.....😱🤣 looks like once again the fanboys got musked with another failed promise by the muskrat... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:14:27 </td>
   <td style="text-align:left;"> $QQQ Tough one.  I&amp;#39;m legit 50/50 on this one   maybe we&amp;#39;ll be range bound for a couolemof week before any meaningful move.  Here are some short term elevating factors imho:
1. Sitting at support
2. Trip bottom
3. RSI (5)  oversold and near long term support 
4. Earnings season 

Deprecating factors:
1. Declining momentum
2. Double top
3. Usually bounces off lower BBands which in this case would break triple bottom support and trigger Algo selling. 

Will be an interesting week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:14:19 </td>
   <td style="text-align:left;"> $SPY $QQQ damn futes starting to rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:13:24 </td>
   <td style="text-align:left;"> $SPY $QQQ As Quick as a New York Liar

Between CA, NY, &amp;amp; DC these ASSHClowns give the USSA a bad name………..

Nearly half of the patients currently in New York hospitals with COVID-19 are not in the hospital because of COVID-19, the state said Friday.

Forty-three percent of the 11,548 hospitalized patients did not have COVID-19 listed as one of the reasons for admission, Gov. Kathy Hochul’s office said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:12:28 </td>
   <td style="text-align:left;"> $SPY $QQQ latex23ec1b0e2889a058649c579d9d22df6c$es and get back to work or our country is done! 😡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:12:04 </td>
   <td style="text-align:left;"> $QQQ green tomorrow for a fake breakout </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:10:18 </td>
   <td style="text-align:left;"> $QQQ is this really the end of free fed money? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:06:18 </td>
   <td style="text-align:left;"> $NVDA Gap to fill. If it breaks down could revisit support at 230. If market gets weak. This is a fat pig to short.
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:04:07 </td>
   <td style="text-align:left;"> $QQQ $SPY Can&amp;#39;t believe Bob Seger died 😣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:03:54 </td>
   <td style="text-align:left;"> $QQQ 365 low for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:03:08 </td>
   <td style="text-align:left;"> Momentum Monday – Rising Inflation Expectations https://ivanhoff.com/2022/01/09/momentum-monday-rising-inflation-expectations/ @howardlindzon @MarketSmith $QQQ $XLE $XLF $SMH $TLT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:02:21 </td>
   <td style="text-align:left;"> $QQQ bears be perplexed that futes aren’t down 10% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 09:02:02 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:59:23 </td>
   <td style="text-align:left;"> https://youtube.com/watch?v=IBBANiV8LBE&amp;amp;feature=share
Are we bouncing soon? Tech? 
$qqq $spy $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:58:58 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Putin &amp;amp; Xi bought puts!!!!😱📉🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:58:42 </td>
   <td style="text-align:left;"> $QQQ Futes a be teetering at this suppor. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:56:41 </td>
   <td style="text-align:left;"> $QQQ futes looking good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:55:28 </td>
   <td style="text-align:left;"> $QQQ fear mongers go buy gold to lessen your anxietis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:51:41 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM $DIA  
 
Science that cannot be questioned  
is not science. 
 
It is (the very definition of) a religion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:51:21 </td>
   <td style="text-align:left;"> $QQQ $SPY Nasdaq futures trading like CPI data isn’t around the corner. Fighting for its life at key support zones while Jpow turns hawkIsh due to insane levels of money printing. Do not fight thy Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:51:03 </td>
   <td style="text-align:left;"> $QQQ 385+ tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:49:06 </td>
   <td style="text-align:left;"> $QQQ they fall of their own weight...if there&amp;#39;s nothing good to say.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:48:28 </td>
   <td style="text-align:left;"> $QQQ fuck u bears u can suck it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:48:18 </td>
   <td style="text-align:left;"> $QQQ lots of delusion on here, welcome to the precovid market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:47:07 </td>
   <td style="text-align:left;"> $QQQ so green tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:44:15 </td>
   <td style="text-align:left;"> $SPY $QQQ 🤣🤣🤣🤣
Bunch of morons who actually believe this will reverse. SUCKERS!!!
PAIN AHEAD...You had your bull run now for almost 2 years with no Real correction!
Now it&amp;#39;s payback. Brrrrrrr POWELL will hurt 🔻🔻🚽🚽🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:43:59 </td>
   <td style="text-align:left;"> $SPY  $qqq so nasdaq already green while spy flat 😂  
Told you bears 🐻 spoke too early …  Green open push monday … but you might get lucky Tuesday and Wednesday … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:43:44 </td>
   <td style="text-align:left;"> $QQQ we green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:41:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X RIP Bob :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:41:04 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA fuck. your. puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:40:56 </td>
   <td style="text-align:left;"> $QQQ 
As you can see QQQ can potentially bounce if breaks $382.76.
Bellow QQQ $377.97 we can go lower.
Previous history has shown this is a key level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:40:33 </td>
   <td style="text-align:left;"> $SPY $QQQ Rot Eel is calling for an “everything dump” 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:39:23 </td>
   <td style="text-align:left;"> $QQQ $SPY the redskins are so ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:38:18 </td>
   <td style="text-align:left;"> $SPY $QQQ Lets go Raiders! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:34:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA There are just way to many selling days last week plus many people were still on vacay. I think markets are up nicely tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:34:06 </td>
   <td style="text-align:left;"> $QQQ shit’s green y’all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:32:56 </td>
   <td style="text-align:left;"> $QQQ futes been doing this red to green shit and then open always red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:32:48 </td>
   <td style="text-align:left;"> $SPY $QQQ is gonna rip to 416 the upper trendline top right in time for Apples ER april 27th, thats when you open shorts not now bros </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:31:06 </td>
   <td style="text-align:left;"> $QQQ stock analysis 

https://youtu.be/wcvezslxKYY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:31:02 </td>
   <td style="text-align:left;"> $AMD Could break down here, if Tech continues weak.
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:26:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $TGT $AMD $UVXY  
 
-On Sept. 30 FY2022 EPS estimated growth was 8.9% 
-On Dec. 31 FY2022 estimated EPS growth was 9.3% 
-Today FY2022 estimated EPS growth is 9.4% 
-By end of Feb. FY2022 estimated EPS growth ~10% 
-Projected base case FY2022 EPS growth 15%-18% 
 (Finom Group) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:26:45 </td>
   <td style="text-align:left;"> $QQQ ❤️ gotta defend these levels or it’s over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:26:44 </td>
   <td style="text-align:left;"> $QQQ Futes are not ripping.  It’s early, but CPI and PPI prolly not gunna be pleasant.  Oh, and JPow taking his spiked punch bowl home.  Oh, and 
JPow said he gunna introduce cover charge and removing ladies night and wet T-shirt contest.  Said we gunna have to earn our Munay now.  Prostitution is like church, no taxes but more fun.  Please fill out application. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:26:37 </td>
   <td style="text-align:left;"> $QQQ zone is holding. Still bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:26:23 </td>
   <td style="text-align:left;"> $ZOM a lot to be bullish on $XBI $QQQ $RYLD $IWM
https://www.griproom.com/fun/10-reasons-why-biotech-could-be-the-hottest-sector-in-2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:23:59 </td>
   <td style="text-align:left;"> $AFRM Still some gap left to fill. Still on a downtrend. I will go short under 74.50.
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:23:10 </td>
   <td style="text-align:left;"> $QQQ 

Hey fellas, check out these 5 stocks targets for this week along with market analysis!😊

https://youtu.be/YOS2NRGss9g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:20:49 </td>
   <td style="text-align:left;"> $QQQ $SPY 
🤖 Trap has been set 🤖 
🤖 Commence with STFR mode🤖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:16:35 </td>
   <td style="text-align:left;"> $UVXY the hourly vix closed as an almost engulfing bullish candle, its also starting to not give back its points gained and small caps are starting to get pummeled thats usually a sign of worse things to come for the broader market in the short term or in the short short term.  $IWM $SPY $DIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:15:52 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ Be stupid and rebalance your portfolio when stocks are said to only go up 🎭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:14:46 </td>
   <td style="text-align:left;"> $SPY $QQQ This needs to stop!! The fuds is just comical now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:14:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK $BRK.A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:13:27 </td>
   <td style="text-align:left;"> $QQQ Down 4 days in a row. 401.68 | 396.47 | 384.29 | 384.02 | 379.86 |  https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:09:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X Heading off of social media, YouTube, TV, News, etc., for 21 days starting at midnight tonight.  Prayers for the next 3 weeks.  God loves you folks, and so do I, don&amp;#39;t waste the free offer of grace He&amp;#39;s giving you! ♥️✝️♥️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:09:08 </td>
   <td style="text-align:left;"> The January Barometer: Buy the Dip or Stock Market Crash $SPY $QQQ $IWM  
https://www.youtube.com/watch?v=2t-OXlRcptc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:06:59 </td>
   <td style="text-align:left;"> $QQQ as long as we hold above 15492.5 im happy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:06:04 </td>
   <td style="text-align:left;"> $SPY $QQQ Couldn’t have happened to a nicer girl 😏 

https://www.foxnews.com/politics/aoc-tests-positive-for-covid-19-after-partying-in-miami-maskless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:05:00 </td>
   <td style="text-align:left;"> $SPY $QQQ This week will be worse week since pandemic hit
Tech,energy, banks all to the shit house 🔻🔻🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:04:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $ARKK 

Small cap tech now trading at or below cash across the board while S&amp;amp;P 500 is trading at a ludicrous P/E of 37.

These kind of unrealistic valuation disparities cannot last. Soon the gap will close.  Either the S&amp;amp;P will crash back down to more reisric valuations or small caps  will rally to catch up.

Interest rates be damned. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:03:55 </td>
   <td style="text-align:left;"> $SPY Here&amp;#39;s two guys that actually know what they are talking about!! Better Listen!https://www.youtube.com/watch?v=PdA_bOcDOiQ&amp;amp;t=2123s $QQQ $UVXY $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-10 08:03:48 </td>
   <td style="text-align:left;"> $QQQ thinking calls for the week if it opens deep red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 15:49:54 </td>
   <td style="text-align:left;"> $SPY if fut can keep the momentum, even when theres a dip at the open, i believe all fang tech will push it higher. $TSLA $AAPL $AMZN $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 15:42:01 </td>
   <td style="text-align:left;"> $AAPL Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 15:37:49 </td>
   <td style="text-align:left;"> $AAPL What’s the EOY prediction for this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 15:33:59 </td>
   <td style="text-align:left;"> $TSLA $GOOGL $PYPL $AMZN $AAPL Hope it stays green the whole Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 15:04:03 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-09 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=79nffRORSzY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 14:37:46 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/L37svHi_riM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 14:34:35 </td>
   <td style="text-align:left;"> $AAPL outperformer on red days. Lets see what happens on a potential green day! 
Note:- yields can still ruin the party but ER run is strong too. Gl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 14:30:27 </td>
   <td style="text-align:left;"> $AMZN $TSLA $AAPL 

Niiiiiice! Great scanners! 

Just banked from your scanners ...

Love it... thankful to the whole team 😇

🙌  tinyurl.com/vudipvxdc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 14:21:06 </td>
   <td style="text-align:left;"> $AAPL seems like the 1 am bear is up and done. 3 point difference lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 14:20:07 </td>
   <td style="text-align:left;"> $AAPL p3nis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 14:08:20 </td>
   <td style="text-align:left;"> $AAPL fomo about to happen with aapl tomorrow and futures are green!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 14:02:59 </td>
   <td style="text-align:left;"> Apple Rivals Microsoft, Blackberry, Nokia Laughed At iPhone, Shrugged It Off And Flung It To The Ground As Steve Jobs Lifted The Curtains — 15 Years Later, Here We Are  $AAPL $BB $NOK $TSLA 

https://newsfilter.io/a/20927dc03ceafdc4e56bdb5868809fe6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 14:01:40 </td>
   <td style="text-align:left;"> $AAPL told yall it put in a double bottom. Nothing but net. 1 am bear action pending tho. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 13:53:35 </td>
   <td style="text-align:left;"> 😎😎 $AAPL - Apple Rivals Microsoft, Blackberry, Nokia Laughed At iPhone, Shrugged It Off And Flung It To The Ground As Steve Jobs Lifted The Curtains — 15 Years Later, Here We Are </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 13:53:23 </td>
   <td style="text-align:left;"> $IIVI $TSLA $AAPL $AMZN https://www.fool.com/investing/2021/01/18/how-to-invest-in-5g-cloud-computing-autonomous-ele/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 13:49:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about latex992ffb356343e9c5227a7a7c16db093fRKT -Rocket Companies Experiencing Massive Growth, Expanding New Business Platforms Ahead Of Fed Interest Rate 

$PYPL - PayPal Explores Launch of Own Stablecoin in Crypto Push&amp;#39; - Bloomberg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 13:18:07 </td>
   <td style="text-align:left;"> $AAPL This thing is going to explode to $190. Watch for Apple Car PR’s. $4T market cap easy. I would also load up on $GOEV as Apple could take them over as prior noise has been there, and Apple gets the whole skateboard/undercarriage and patents and gets caught up to other players in one acquisition.

Carey on! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 13:12:28 </td>
   <td style="text-align:left;"> $AAPL GREEN FUTURES = GREEN CANDLES TOMORROW!! 🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 13:09:15 </td>
   <td style="text-align:left;"> $AAPL Apple manufacturing facility in southern India will reopen on Wednesday. Let&amp;#39;s see this thing go back to 180 EOW ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 12:58:20 </td>
   <td style="text-align:left;"> $AAPL ohh fck move coming for bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 12:53:55 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY MARKETS WILL BE PUMPED AROUND BIDEN ANNIVERSARY and ER for one last time before … the inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 12:44:34 </td>
   <td style="text-align:left;"> $AAPL futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 12:38:51 </td>
   <td style="text-align:left;"> $AAPL I know many technical analysts are anticipating a sell-off after another new ATH, but this company has SO much going for it. #ownitdonttradeit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 12:38:10 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ interesting week coming. Going to be volatile. Let’s make lots of money from both sides. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 12:36:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 
BEARS WHAT HAPPENED TO THE CRASH ???!
Five hours ago when futures opened and were down .4  percent, u said limit down circuit breakers ??!! Now futures ALL GREEN and nasdaq getting a pump and let me guess your response “FUTures don’t MATtter, red by morning?!” 😂😂😂
FUTURES UPDATE FOR THE SHORTS  👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 12:34:56 </td>
   <td style="text-align:left;"> $AAPL $CRM  $MSFT $GOOG $QQQ Here’s something to ponder, what if inflationary forces ease soon as the supply chain bottle necks improve?  Would that become a big head fake for papa J?  He would then calm down his easing stance and techs would fly again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 12:25:16 </td>
   <td style="text-align:left;"> $AAPL Foxconn India iPhone plant to reopen on Jan 12 -govt officials. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 12:14:02 </td>
   <td style="text-align:left;"> $AAPL To the moon 🍏🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 11:46:49 </td>
   <td style="text-align:left;"> $AAPL
Target $200 
 https://pulse2.com/apple-stock-nasdaq-aapl-200-price-target-reiterated-from-evercore/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 11:46:01 </td>
   <td style="text-align:left;"> $AAPL ***Remember- just over 2 weeks until knockout earnings numbers… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 11:15:19 </td>
   <td style="text-align:left;"> $AMC everyone one is concerned about AMC dedt...have you seen the debt $AAPL has? 136b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 11:09:08 </td>
   <td style="text-align:left;"> $SPY $AAPL 🤣🤣🤣 this is about ten years late. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 11:01:24 </td>
   <td style="text-align:left;"> $AAPL | Foxconn iPhone Manufacturing Plant In Southern India To Reopen On January 12 - RTRS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 10:56:59 </td>
   <td style="text-align:left;"> How To Tell If A Stock Has Bottomed Out

$TSLA $MRNA $AAPL $FUBO latex0ecf37aa00126df48cba6a4afd6f8374LCID Over latex77cc6f31beb7c11a878ed68de9eeaaacAAPL Over 173.10📈 

$BABA Over 130.21📈

Good Luck, Follow the link for alerts and livestream’s💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 10:48:35 </td>
   <td style="text-align:left;"> $amzn 3200
$googl $2700
$tsla $980
$msft $300
$aapl $170

Puts in case of possible pullback. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 10:47:43 </td>
   <td style="text-align:left;"> $AAPL dovewoodcapital.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 10:45:21 </td>
   <td style="text-align:left;"> $AAPL 175-177 please and thank you kindly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 10:42:07 </td>
   <td style="text-align:left;"> $amzn $3200
$googl $2700
$tsla $975
$aapl $169
$msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 10:34:06 </td>
   <td style="text-align:left;"> $AAPL $NVDA $SPY $DKNG $TSLA Hey everyone! So I wanted to just update everyone that moving in this year I will start posting my plays (exact entries and exits) on this app called tradeexchange! I am going to be posting exact entries and exits on Madria Stock Swings. Essentially you will be able to get the exact entries and exits on there (basically me trading for you legally haha)! I am doing a New Year special of $5 a month. Shortly I will be increasing the price  :-)  
 
If you want to support me, please follow me on there. Any questions and such - feel free to message me on here!  
 
I hope to see you guys there! Thanks again for supporting me for the last year and a half as we continue to grow! Getting more and more clutch each time! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 10:20:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.97%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 10:09:45 </td>
   <td style="text-align:left;"> https://youtube.com/watch?v=IBBANiV8LBE&amp;amp;feature=share
Holding $googl and $fb hopefully big tech carry a bit next week $aapl $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 10:08:26 </td>
   <td style="text-align:left;"> $AAPL Tech 100 futures are popping. Should be a big day for $AAPL tomorrow. Calls will be printing $$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:38:57 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy: January 14, 2022 $172.50 Calls 
Entry Price: $2.37 - $2.50 
Exit Price: $3.15 
Stop Loss: latex072eebf199921fe1378131b9cd2348f7AAPL/$FB  Am I glad am holding 875k in Cash? you bet you, have only 4 open positions with great fundamentals American  companies, No chines crap period.  
ready to load on 20% correction its coming mark it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:35:10 </td>
   <td style="text-align:left;"> $AAPL let it dump  they keep diluting shareholders with splits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:33:38 </td>
   <td style="text-align:left;"> $amzn $3350
$googl $2850
$tsla $1100
$msft $325
$aapl $177

Bullish calls if no more pullback. Puts if so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:33:31 </td>
   <td style="text-align:left;"> $AAPL trade idea
Looking at a continued decline to $168 area target next!
Entry break $171 ill play the $170 PUTS 1/14/22
Entry break $174.29, ill jump in calls! 
Targets and entry&amp;#39;s marked on chart! 

https://share.trendspider.com/chart/AAPL/1136780ef5z </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:32:51 </td>
   <td style="text-align:left;"> $AAPL ugh looking red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:18:27 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL is trending on Twitter the last 24hrs - seeing an increase in number of tweets, re-tweets, and impressions. Keep an eye on this Monday morning to see what&amp;#39;s happening. Real-time dashboard is here https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220109 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:15:50 </td>
   <td style="text-align:left;"> $QQQ, $AAPL  , $LCID - my favorite stocks In my portfolio !! A true winner! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:14:29 </td>
   <td style="text-align:left;"> $AAPL     🍏😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:06:32 </td>
   <td style="text-align:left;"> Episode 17 is out 🔥

Tracking unusual options order flow:

We are seeing the financial sector is starting to heat up! Let&amp;#39;s check the flow data and break down some technical analysis on $MS, $LCID, and $AAPL

Video: youtu.be/oXqAP_PvGY0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:03:18 </td>
   <td style="text-align:left;"> $AAPL 
AAPL above $173.72 for a potential run up.
AAPL below $170.6 for a potential drop.
History has shown this is a key level for AAPL.
#scalp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 09:02:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-09 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=79nffRORSzY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:58:58 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Putin &amp;amp; Xi bought puts!!!!😱📉🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:57:55 </td>
   <td style="text-align:left;"> $AAPL 

Next Record $192 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:53:56 </td>
   <td style="text-align:left;"> $AAPL PT90 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:52:30 </td>
   <td style="text-align:left;"> $AAPL $161, 140, 123 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:41:37 </td>
   <td style="text-align:left;"> $AAPL nas futes put in a double bottom. Ofc this could go to shit when the 1 am bear wakes up but who knows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:41:23 </td>
   <td style="text-align:left;"> $AAPL please open down so I can load up on some calls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:39:19 </td>
   <td style="text-align:left;"> $AAPL calls at open babyyyyy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:38:48 </td>
   <td style="text-align:left;"> $AAPL Last time it crossed down the 10 SMA we had a quick reversal, the depth of this second time crossing that same SMA could behave differently. Long term bullish but cautious with puts short term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:28:40 </td>
   <td style="text-align:left;"> $AAPL we hungry fomo from Friday tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:28:07 </td>
   <td style="text-align:left;"> $AAPL what’s going on with the futures? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:26:44 </td>
   <td style="text-align:left;"> $AAPL fucking $mcd has a PE OF 27 lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:18:59 </td>
   <td style="text-align:left;"> $AAPL 

Hey fellas, check out these 5 stocks targets for this week along with market analysis! Apple being a key one discussed. 

https://youtu.be/YOS2NRGss9g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:18:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 7.00. This indicates good health for $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:15:05 </td>
   <td style="text-align:left;"> $AAPL - can’t wait until earning report !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:15:01 </td>
   <td style="text-align:left;"> $brk.a $aapl called it! $spy $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:12:08 </td>
   <td style="text-align:left;"> $AAPL I need this to be green in the morning so I can get out of my options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 08:01:21 </td>
   <td style="text-align:left;"> $aapl so $nyt has a FUCKING 44x evaluation, even after the 10% dickslap it got. Smh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:57:46 </td>
   <td style="text-align:left;"> $AAPL Odds of 175-180 eow vs continual decline? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:54:07 </td>
   <td style="text-align:left;"> $AAPL $PYPL $HOOD https://www.bloomberg.com/news/newsletters/2022-01-09/apple-should-develop-checking-accounts-debit-card-stock-trading-tools-ky7mf6sf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:52:37 </td>
   <td style="text-align:left;"> $QQQ tech should start to implode soon $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:48:05 </td>
   <td style="text-align:left;"> Invest with an outcome based approach on $AAPL. Accelerate gains by 3.3x and make up to 13.7% (42.4% annualized) on $AAPL through 05/20/2022.

Buy 2 $170 calls
Sell 1 $175 call
Sell 1 $180 call
Sell 1 $180 put
 5/20/22 expiration
https://o.oliveinvest.com/uoaakh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:37:22 </td>
   <td style="text-align:left;"> $QQQ $AAPL LoL.  Why does apple care if the 10y is at 1.5 or 2?  They are printing money every quarter.  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:15:40 </td>
   <td style="text-align:left;"> $SPY $AAPL 

First block tomorrow

(I’ve been trading this for a while, now I want to own it) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:14:57 </td>
   <td style="text-align:left;"> $AAPL Puts Printing tom and Wed on CPI # like 7.5 lets go Brandon wiping us out lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:14:55 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $AAPL is the #1 stock that institutions traded this week with 507.7K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:12:36 </td>
   <td style="text-align:left;"> $AAPL I’m blocking Jamminsalmon because he lies on here and he seems generally full of 💩. Thought I’d share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:09:13 </td>
   <td style="text-align:left;"> $AAPL  record breaking earnings should bring the price to 190 a share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 07:08:35 </td>
   <td style="text-align:left;"> $AAPL Deep red Futes sorry! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 06:59:10 </td>
   <td style="text-align:left;"> $AAPL $MSFT load up!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 06:58:22 </td>
   <td style="text-align:left;"> $SPY $FB $AAPL $LAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 06:47:49 </td>
   <td style="text-align:left;"> $AAPL just dropped a 100k into TD account … when should I get into this don’t wanna miss dip or buy to soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 06:47:30 </td>
   <td style="text-align:left;"> $LCID $BNGO $AAPL it got very real today. I am trying to enjoy the day but got some news that my grandmother passed today. Love each other and don’t forget to say I love you to your loved ones. Money is temporary and so is life. Enjoy it and always stay happy. I’ll strive to be as caring and loving as she was. Always selfless with a kitchen full of food for us. She had no money and somehow enjoyed life in her very unique way. laugh and enjoy life. Will miss you Nana May your memory be eternal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 06:40:53 </td>
   <td style="text-align:left;"> $AAPL who’s catching the dips before earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 06:40:30 </td>
   <td style="text-align:left;"> $AAPL curious how earnings will play out! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 06:23:15 </td>
   <td style="text-align:left;"> $NVDA $TSLA $AAPL $AMD 
 Free discord link in bio!🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 06:10:14 </td>
   <td style="text-align:left;"> SweepCast alerted: $AAPL with Unusual Options Activity Alerted on $175 CALL Expiring: 01-14-2022 worth 33K🐂 |🥇  The trade has a sentiment of BEARISH | SweepCast.com or Premium Room ➡️  #daytradingtips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 06:00:39 </td>
   <td style="text-align:left;"> $AAPL $UPS Has a PE of 29.6, like what? How is Apple expensive at 30.66 then 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:58:26 </td>
   <td style="text-align:left;"> $AAPL Apple US Patents, Patent Applications and Patent Search - Justia Patents Search https://patents.justia.com/company/apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:56:14 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Evercore ISI Believes Apple (AAPL) Still Has Room to Grow https://www.stck.pro/news/AAPL/21049931 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:48:00 </td>
   <td style="text-align:left;"> $AAPL Puts print tomorrow sorry my peeps is what it is! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:40:44 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on multiple timeframes.  We only like to buy it in 3, 7 or 11 swing at the blue boxes.   Like to watch the $NQ_F at equal leg which can give some sense of timing for larger cap tech for buy areas. We don’t like to trade it in the middle area right now.   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:38:12 </td>
   <td style="text-align:left;"> Next week’s episode of market drama🍿
• Monday- #Deltacron headlines
• Tuesday- Powell speaking at 10AM
• Wednesday- CPI data at 8.30AM 
• Thursday- PPI data at 8.30AM
• Friday- Theta burn activities 👀

$spy $aapl $tsla $qqq $arkk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:37:57 </td>
   <td style="text-align:left;"> $AAPL The iPhone Turns 15: How The Breakthrough Product Changed Apple&amp;#39;s Fortunes 

https://newsfilter.io/a/1d25529db4afedb361529fef3e870123 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:21:19 </td>
   <td style="text-align:left;"> It&amp;#39;s The Smartphone Owned By Almost 90% Of US Teens: Study $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:20:56 </td>
   <td style="text-align:left;"> TODAY IN HISTORY, via @Investopedia
January 9, 2007
 
On this day in 2007, the first iPhone was announced by Steve Jobs. The new phone combined “three products—a revolutionary mobile phone, a widescreen iPod with touch controls, and a breakthrough Internet communications device,” in one. Just 12 years later, the iPhone’s enormous success allowed Apple to become the first publicly-traded company with a market value of $1 trillion. And on Jan. 3, 2022, it became the world&amp;#39;s first $3 trillion company. 
 
Source: Apple; David Paul Morris / Stringer $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:15:46 </td>
   <td style="text-align:left;"> $AAPL Apple is way oversold right now. Perfect time to buy calls and shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:15:28 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Intel: An Assessment For Long-Term Investors https://www.stck.pro/news/AAPL/21050020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:12:19 </td>
   <td style="text-align:left;"> $AAPL I took a beating last week but gonna triple down for earnings run up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:04:53 </td>
   <td style="text-align:left;"> $AAPL $TSLA $XOM CES, OIL, and more on this episode of Whats Next Wallstreet!
Like and Subscribe to get all of our show alerts and videos

https://youtu.be/0AW-EzMDy70 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:01:19 </td>
   <td style="text-align:left;"> $SPY WE ARE STILL not in trouble. Lets see what this week brings. Looks like Distribution all week last week. $qqq $AAPL

Follow me on twitter for more https://twitter.com/ApesBullsBears/status/1480283317836693506?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 05:01:00 </td>
   <td style="text-align:left;"> $AAPL - Do not take any jabs!!, the sooner y&amp;#39;all wake up the better.. 
https://rumble.com/vrun2b-gene-decode-one-of-the-most-important-videos-of-2021-mirrored.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:57:50 </td>
   <td style="text-align:left;"> $AAPL  Missed Auto Industry Disruption ? Don’t miss aviation 

Joby is 100x company - Watch Joby ticker !!

https://youtu.be/iRlmfFIiHbU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:57:33 </td>
   <td style="text-align:left;"> $AAPL tim cook finally becomes a billionaire congrats tim </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:54:35 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA 

Market participants are bracing for another historically hot reading on inflation in the latest CPI data, due out on Wednesday. On a year-over-year basis, consumer prices likely surged by 7.1% in December, based on Bloomberg consensus data, accelerating even further from November&amp;#39;s 6.8% year-over-year clip. This would mark the fastest rate since 1982, when CPI rose as much as 8.4% on a year-over-year basis.  - Yahoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:52:37 </td>
   <td style="text-align:left;"> $AAPL you’d be foolish to not grab shares at these prices. 200 is imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:48:07 </td>
   <td style="text-align:left;"> $AAPL puts printed last week thanks to @RiskVsReward💰💰🤝🤝 one of many 1000% plays. A regular thing when it comes to this guy 🙏🏻🙏🏻 looking forward to the next one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:45:22 </td>
   <td style="text-align:left;"> #Levermann #Global #MegaCap #Sell WK1 $AAPL (2), $AMZN (-4), $0700.HK (-1), $BAC (0), $BABA (-4) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:36:00 </td>
   <td style="text-align:left;"> $AAPL&amp;#39;s ROE of 150.07% is amongst the best returns of the industry https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:33:46 </td>
   <td style="text-align:left;"> $AAPL this looks like the floor is here! Don’t see this going any lower! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:28:46 </td>
   <td style="text-align:left;"> $AAPL is  it  true  Apple TV has  AMC ON DEMAND like the Meme stocks, so they  are  working  together now tat  is  great news. 
 
Apple  should  invest  more in movie  theaters, like get a commercial  in before  a big  movie  that  promotes the  I  phone could work 
 
We  love Movies I recommend everyone take  a  break  from this  stock  and  tv and go to the movies with the FAMILY I had  a great  time 
watching 
Spider-MAN  amazing movie 
go watch spiderman, All the  OLD Villains  CAME BACK AND MORE! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:27:28 </td>
   <td style="text-align:left;"> $AAPL https://www.facebook.com/100059283082154/posts/351513090168124/?d=n </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:18:40 </td>
   <td style="text-align:left;"> ⏳📈💰 $AAPL - It&amp;#39;s The Smartphone Owned By Almost 90% Of US Teens: Study </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:16:21 </td>
   <td style="text-align:left;"> $AAPL Why would anyone want to sell this stock?

https://uspto.report/company/Apple-Inc/patents </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:15:50 </td>
   <td style="text-align:left;"> Rumored iPhone SE with 5G expected to debut at March Apple event 
 
$AAPL 
 
https://appleinsider.com/articles/22/01/09/updated-iphone-with-se-expected-for-march-virtual-apple-event </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:13:52 </td>
   <td style="text-align:left;"> $SPY no long term speculation from me. all I’m saying is I expect a bounce Monday. I grabbed a few $AAPL calls on Friday near the bottom 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:12:23 </td>
   <td style="text-align:left;"> $TSLA Less people are getting trade jobs. Inflation is out of control. Buy companies with pricing power. $AAPL https://youtu.be/iix6tWuJkxo $SPY $USO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:03:19 </td>
   <td style="text-align:left;"> Dark pool after hours activity from Friday in:

$IWM - $124M print
$AAPL - $248M print
$MSFT - $467M print
$ATVI - $188M print

#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 04:00:37 </td>
   <td style="text-align:left;"> $AAPL stock analysis 

https://youtu.be/2XxGKpah9zc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:47:08 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ END OF BULL MARKET I THINK! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:41:47 </td>
   <td style="text-align:left;"> $aapl lookie here.
$btc.x is ripping 👀 
So good stocks will benefit. Money printer Apple! 👍🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:40:43 </td>
   <td style="text-align:left;"> $AAPL  Breakdown alert! Next level of support around 167. If that breaks  more downside to come. Distribution in place.  $spy $QQQ 
https://twitter.com/ApesBullsBears/status/1480228995358724104?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:35:56 </td>
   <td style="text-align:left;"> $AAPL What To Expect From Apple&amp;#39;s 2022 Spring Event: New iPhone SE, iMac And More 

https://newsfilter.io/a/b853ae66b4b41d805ca1be6e2268f64e </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:31:21 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
Never forget what keeps these markets moving higher. 
 
Take away free money liquidity and down they go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:13:01 </td>
   <td style="text-align:left;"> $AAPL https://www.macrumors.com/2022/01/09/apple-event-march-or-april-2022-gurman/ 
Iphone SE is going to be big seller and will make Apple eco system and service business much much bigger in 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:12:15 </td>
   <td style="text-align:left;"> $DARE BILL GATES will save us like he did to $AAPL…🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:11:08 </td>
   <td style="text-align:left;"> $AAPL this ain’t going to run into ER, in fact it will dump hard, these problems can’t be ignored and when your trading at a 3T market cap, everything better be perfect which is obviously not the case 
https://www.thestreet.com/investing/apple-has-a-6-billion-supply-chain-problem-that-may-get-worse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:10:36 </td>
   <td style="text-align:left;"> $AAPL coming to rest, then price bounce https://youtu.be/3tCPrTr3dSg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:01:14 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $GME 

It’s a war I tell you. A straight out slugfest to the death in this game. You throw a punch you keep punching until your opponent drops, because if you take a punch, they will keep punching until you drop and they don’t want you getting up again after they take all your money…stay on your toes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 03:00:38 </td>
   <td style="text-align:left;"> $AAPL bought this at $116 when dumb bears were calling for a gap fill at $80 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:56:51 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $AMZN 
This is how these players celebrate now a Goal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:41:50 </td>
   <td style="text-align:left;"> $AAPL Quarterly chart. It has been a nice run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:33:32 </td>
   <td style="text-align:left;"> $AAPL 

Just left one of the apple stores after buying a new iPad.  Store was a busy with a line outside.   

My guess is Apple will be on a strong trend up for quit some time!  

Let’s go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:30:10 </td>
   <td style="text-align:left;"> Tarnished Silvergate $SI Also $AAPL https://talkmarkets.com/content/stocks--equities/tarnished-silvergate?post=340578 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:27:01 </td>
   <td style="text-align:left;"> $PTON I noticed that Costco is now selling a poor man&amp;#39;s PTON called ProForm. It&amp;#39;s $400.

A PTON bike is what? $3,000?

Definitely the start of the slow, agonizing death spiral here. 

I don&amp;#39;t think PTON will go out of business. No way. They have a small group of hardcore fans. The same fans that probably love $AAPL and $TSLA . 

I think either Apple, Google, Amazon, or possibly Netflix will buy them out within 12-24 months. 

The stock will probably drop to $20-$25, management will know it&amp;#39;s done, and sell to Apple, Google, Amazon, or Netflix for $25-$40 per share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:26:43 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $AAPL is the #1 ticker with sweep activity that institutions traded urgently this week options with 455.5K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:19:26 </td>
   <td style="text-align:left;"> $AAPL is China. 
 https://www.reddit.com/r/Epic_Economics/comments/rzxpfr/fastest_inflation_in_four_decades_us10y/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:16:46 </td>
   <td style="text-align:left;"> $AAPL, $TSLA, #DNA, @elonmusk, @spacex, @deadstevejobs2 https://micabear.com/2022/01/09/one-thing-tesla-learned-from-apple-%f0%9f%a4%a3%f0%9f%a4%a3%f0%9f%a4%a3/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:14:38 </td>
   <td style="text-align:left;"> $AAPL 

Didn’t you know that when the stock is oversold already .. 

You will noticed that puts has shifted already to become more expensive and more discouraging for people to buy puts and will focus on buying calls.

You see why calls premiums are already very cheap already.

It’s not just theta ..

The pattern is already shown big consolidation with big up and down swing to make options very cheap.

Now with oversold territory has been touched for all levels.

You know what that means .. it has reset to October bottom trend and is on the upward trend to 200 to 210 oversold territory trend.

This is very bullish indication! Let’s go!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 02:04:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-09 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=79nffRORSzY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:51:28 </td>
   <td style="text-align:left;"> $AAPL is going 2022 biggest stock of the year! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:48:56 </td>
   <td style="text-align:left;"> $AAPL It&amp;#39;s The Smartphone Owned By Almost 90% Of US Teens: Study 

https://newsfilter.io/a/f98a3898f24586d8e8b3a882a79ac104 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:38:06 </td>
   <td style="text-align:left;"> $AAPL I don’t understand how anyone is bullish rn .. long term sure but short term the weekly is looking ugly .. $164 might be seen this week if Apple doesn’t shoot up and stay up on Monday .. imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:32:57 </td>
   <td style="text-align:left;"> $qqq $PLTR $tsla $amzn $aapl So many clowns 🤡 get through Seeking Alpha article submission. People need to realize that they are not ANALYSTS. They do not show positions. Nor do they should clarity and transparency by showing their real names in the articles. Do your own due diligence! 

You to can write a BS article for them. 

https://seekingalpha.com/page/article-submission-guidelines </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:28:40 </td>
   <td style="text-align:left;"> $AAPL sold 170 calls at the bell. It’s either a good hedge, or I’m trimming my position by 300 shares this week. Either way is good for me, profits in pocket are a beautiful thing in this environment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:27:19 </td>
   <td style="text-align:left;"> $AAPL bitty up above 3% Now it means that Apple ER run will resume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:25:29 </td>
   <td style="text-align:left;"> $AAPL always a run up before earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:25:28 </td>
   <td style="text-align:left;"> $NVDA $PATH $DKNG $AAPL am going to be doing market analysis and looking at current and scanning for new positions this afternoon. Lmk if you guys want charts for anything (followers have priority :) ) also exciting news coming later today!! Stay tuned $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:19:46 </td>
   <td style="text-align:left;"> $AAPL  https://micabear.com/2022/01/09/mark-gurman-silly-aapl-analyst-dude-gets-paid-stacks-for-this-research/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:13:42 </td>
   <td style="text-align:left;"> $AAPL are you bullish on pushing all time highs by earning or not? What’s your justification? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:13:05 </td>
   <td style="text-align:left;"> $AAPL https://www.binoidcbd.com/?ref=u2gwbey9cb  GLTA!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:12:42 </td>
   <td style="text-align:left;"> $VERB 
Bears can say what they want. Bottom line is Verb is using Rockwater, small powerful team that $GOOG , $VIAC , $SHOP &amp;amp; multiple fortune 50 companies, &amp;amp; film houses use for their growth expansions, launches &amp;amp; strategic planning. 

Verb has David Meltzer as their Producer of shoppable content same guy who just signed a deal with $AAPL Tv.
The future that is being pitched around big tech, &amp;amp; film studios is shoppable original content/ programming. Everything bought with a click, whether it be live stream original programming,  prerecorded streaming or pop up commercials. All shoppable.

In 1 year Verb launched
Verblive
https://youtu.be/lpvFxCdvSjk

Lauched a closed beta site only for ui/ux testing w/final product being developed parallel in private, to prevent copying

https://www.shoppopup.tv

Released a preview of final product 

https://youtu.be/c5xKOK6VhZg

Verbmail, for Microsoft Outlook &amp;amp; Gmail will likely be released immediately following financing.
Financing is the key unlocking many doors for Verb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:05:35 </td>
   <td style="text-align:left;"> $AAPL https://www.cbsnews.com/news/apple-airtag-brooks-nader-tracking-safety-instagram/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:04:01 </td>
   <td style="text-align:left;"> $AAPL 

Happy Birthday to iPhone !!

One of the world greatest inventions ever invented that revolutionized the whole world! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 01:02:57 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Diamond hands&amp;quot; is an interesting term. 
It&amp;#39;s thought to be for a long term investor but if you read about it, it says &amp;quot;to ignore dips and volatility and hold your position.&amp;quot; 

Now to me a long term investor is already doing this,  but a DAY TRADER , or, yeah, swing too, of course, maybe, more so, is not just holding a stock for YEARS.
For DTs and STs, it&amp;#39;s seconds, minutes, day, or, days, or, week, or, two, maybe, up to 3, on a swing, but that&amp;#39;s cut-off, IMO, let&amp;#39;s debate theclatter later please $QQQ $SOXX $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:52:19 </td>
   <td style="text-align:left;"> $AAPL try this all free mine free bitcoin easy money !!! https://www.chainmine.io/?ref=56Y7UCYa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:49:07 </td>
   <td style="text-align:left;"> $BTC.X People have a lot to say about crypto but one things for sure it’s not the stock market, these corrections/crashes are normal in my opinion because cryptocurrency will always be more volatile than the stock market. $AAPL MC almost $3T the entire MC of cryptocurrency is less than $3T…BTC still outpacing the S&amp;amp;P since inception….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:47:58 </td>
   <td style="text-align:left;"> $AAPL The iPhone and Mac maker has seen its business grow by a third over the past 12 months

https://www.thestreet.com/investing/apple-has-a-6-billion-supply-chain-problem-that-may-get-worse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:45:36 </td>
   <td style="text-align:left;"> $SPY $PENN $DKNG $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:36:55 </td>
   <td style="text-align:left;"> Link here $AAPL 

https://www.instagram.com/p/CYg6LkUsRXS/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:35:00 </td>
   <td style="text-align:left;"> On this day $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:34:18 </td>
   <td style="text-align:left;"> When SJ $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:31:08 </td>
   <td style="text-align:left;"> Fact here $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:27:05 </td>
   <td style="text-align:left;"> $AAPL 
MCAP. 🍏⬆️3.125T Soon. 
3.125/16.04 SO=$194,82. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:25:51 </td>
   <td style="text-align:left;"> $amzn $tsla $aapl what is the correction percentage from the hikes? 10%? 20%? More than 25%? What exactly is will the interest rate be? When? As soon as March?  The big question for the newbies and day traders, has the correction began already? $preparation $Bigtrap-$infochangesconvo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-10 00:15:02 </td>
   <td style="text-align:left;"> $AAPL https://seekingalpha.com/article/4478539-this-is-historically-a-bad-time-to-buy-apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 23:49:42 </td>
   <td style="text-align:left;"> $AAPL PyraWeb monthly.  Careful here, long outlook still good to end of 2020s, but price at tip top of pyramid make s me think it’s gonna retrace a bit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 23:41:47 </td>
   <td style="text-align:left;"> $SPY buying $AAPL in tranches as well

15k now 

15k March </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 23:35:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.97%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 23:14:56 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $MSFT $AAPL q1, q2 2022 you’re really going to start seeing the effects of biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 23:11:00 </td>
   <td style="text-align:left;"> PC Slowdown Sets a New Battleground for Chip Makers3 min read  $AMD $JEF $AAPL $QCOM 

https://newsfilter.io/a/e56a314295440fe622c2533f4d4d3dd4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 23:10:02 </td>
   <td style="text-align:left;"> $AAPL worth more than the Russell 2000 at 3 trillion market cap lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 23:04:55 </td>
   <td style="text-align:left;"> PC Slowdown Sets a New Battleground for Chip Makers  $AMD $JEF $AAPL $QCOM 

https://newsfilter.io/a/f1a7d292e3ce0cf045c5ea0bca097db8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 22:59:04 </td>
   <td style="text-align:left;"> $AAPL 
🍏
Apple is a $3 Trillion Stock – Week in Review
January 9, 2022. 

Apple (AAPL) was briefly a $3 trillion stock on January 4th, the first day the stock market opened in 2022. The stock price climbed over $182.86 per share on optimism about an electric vehicle, augmented-reality glasses, and other products. Alas, Apple’s stock price dropped the remainder of the week as a negative sentiment about rising interest rates impacted tech stocks and the NASDAQ. Apple’s market capitalization finished the week at $2.824 trillion.

https://www.dividendpower.org/2022/01/09/apple-is-a-3-trillion-stock-week-in-review/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 22:44:59 </td>
   <td style="text-align:left;"> Ticker: $AAPL
Buy: January 14, 2022 $172.50 Calls
Entry Price: $2.37 - $2.50
Exit Price: $2.99
Stop Loss: $2.09
Potential ROI: 26%
Estimated Hold Time: 63 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 22:36:12 </td>
   <td style="text-align:left;"> $AAPL i have a 180c for this week. Should I hold till wendsday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 22:31:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $SBUX $SBUX   
 
From within this weekend&amp;#39;s Research Report by Finom Group:  
 
-Cyclical bull markets since 1942 vs. 2020 to-date 
-minimum 26 months 
-maximum 132 months 
-average 63 months 
-current bull market 21 months 
-just a baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 22:20:00 </td>
   <td style="text-align:left;"> Does this make you nervous? $AAPL in Downtrend: RSI indicator exits overbought zone. View odds for this and other indicators: https://srnk.us/go/3310203 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 21:42:32 </td>
   <td style="text-align:left;"> $AAPL 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 21:41:38 </td>
   <td style="text-align:left;"> $AAPL I’m worried this is going to keep going down.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 21:41:38 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 21:35:38 </td>
   <td style="text-align:left;"> Why Apple’s iMessage Is Winning: Teens Dread the Green Text BubbleLong read  $AAPL $GOOG $PIPR $SBUX 

https://newsfilter.io/a/dd6792e18a4213ab17b2ca8ec469250f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 21:18:21 </td>
   <td style="text-align:left;"> Ready to stack more gains in $AAPL this week. See you all tomorrow with the premarket plan! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 21:15:53 </td>
   <td style="text-align:left;"> $BB $AAPL 

 https://www.rt.com/russia/545483-us-sanctions-plan-russia/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 21:05:52 </td>
   <td style="text-align:left;"> $AAPL  Check HRAA

Q10 in Sept shows Ameriguard Security bought 91% voting rights 
HRAA mc is only 18.5m
Ameriguard Security Services has many government contracts worth more than the mc of HRAA alone.
Along with that, they service residential and commercial companies.
A FB response in Nov 2021 said news was coming soon 👍
Could be a huge RM 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 20:50:11 </td>
   <td style="text-align:left;"> Apple is a $3 Trillion Stock – Week in Review $AAPL  
 
https://www.dividendpower.org/2022/01/09/apple-is-a-3-trillion-stock-week-in-review/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 20:47:05 </td>
   <td style="text-align:left;"> $AAPL Hello Everybody. Who doesn&amp;#39;t like extra $$$  Anyone ever heard of UPLAND yet? It&amp;#39;s based on nfts and it&amp;#39;s a crypto market. Upland will award you with a bonus for your first purchase, please use my link.  https://r.upland.me/jrSP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 20:42:54 </td>
   <td style="text-align:left;"> $AAPL yo dumb administration ppl learn from your mistakes last week and don’t loose too much this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 20:27:29 </td>
   <td style="text-align:left;"> The End of Car Keys, Passwords and Fumbling With Your Phone at Checkout9 min read  $AAPL $GOOG $QRVO 

https://newsfilter.io/a/bd2c852af7c49ee226693af608800315 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 19:36:16 </td>
   <td style="text-align:left;"> $AAPL 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 17:43:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $IWM If you paid attention to the market close last Friday, you’d have noticed the market is at risk. I’m longer term bullish but short term cautious. CPI comes out this Wednesday and we’ll probably have more bad news. $AAPL should be watched closely as it’s a good indicator for the S&amp;amp;P and we all know it can correct fast and hard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 17:31:13 </td>
   <td style="text-align:left;"> $WISH lolll $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 17:18:01 </td>
   <td style="text-align:left;"> $AAPL $NVDA $MSFT $AMZN $TSLA 

Keep compounding 💪🏽💪🏽💪🏽💪🏽💪🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 17:15:10 </td>
   <td style="text-align:left;"> 12 Ways to Tame Your Family’s Screen Time in 2022  $AAPL $ADC $NFLX 

https://newsfilter.io/a/79f222e130bf809d18b9e9c4a06edf2c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 17:10:24 </td>
   <td style="text-align:left;"> #Gold Reamed, #Silver Creamed, Now Lower Still, &amp;#39;Twould Seem $AAPL $GLD $SLV $SPX https://talkmarkets.com/content/commodities/gold-reamed-silver-creamed-now-lower-still-twould-seem?post=340553 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 16:29:36 </td>
   <td style="text-align:left;"> $AAPL 
Need to be very careful ..............
https://www.cnbc.com/2022/01/08/cyprus-reportedly-discovers-a-covid-variant-that-combines-omicron-and-delta.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 15:47:00 </td>
   <td style="text-align:left;"> $AAPL could see a reversal this week for some nice day trade action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 15:37:00 </td>
   <td style="text-align:left;"> $AAPL: The short term is neutral, but the long term trend is still positive. Not much to worry about for now. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 15:18:03 </td>
   <td style="text-align:left;"> latex1ab0dab20da13171243e9c6e5308963f$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 14:52:43 </td>
   <td style="text-align:left;"> $AAPL $MSFT Which one better in the long run? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 14:42:42 </td>
   <td style="text-align:left;"> $AAPL rotate here ;) https://youtu.be/ucQSD9ayiv8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 14:15:26 </td>
   <td style="text-align:left;"> $AAPL $QQQ Apple’s conference call to discuss first fiscal 
quarter results is scheduled for Thursday, January 27, 2022 
at 2:00 p.m. PT / 5:00 p.m. ET. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 13:13:02 </td>
   <td style="text-align:left;"> Bullish portfolio: Apple( $AAPL ), Allstate Corp( $ALL… https://www.macroaxis.com/invest/marketRiskAndReturn?s=AAPL,ALL,MRO,CTAS,CINF,KIM,PRU,BBY #correlations #stocks #stockratings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 12:26:22 </td>
   <td style="text-align:left;"> $AAPL the current level of price support is where? thank you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 12:24:13 </td>
   <td style="text-align:left;"> $AAPL  
is going after andriod users its company Humane putting together interface for its AR smart glasses it makes sense to do when Apple wants to attract new users from both android and apps eco systems. This will be huge, Apple brand Android simplicity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 12:20:49 </td>
   <td style="text-align:left;"> $AAPL $MSFT load up nothing else you need in your portfolio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 12:09:48 </td>
   <td style="text-align:left;"> $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 11:45:10 </td>
   <td style="text-align:left;"> $AAPL $DIS $MSFT Print out and post by your monitor so you don’t miss the next opportunity!
Have a great Sunday! See you Monday for MORE STACKS!👊🏼😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 11:42:05 </td>
   <td style="text-align:left;"> Consider investing in February 2022: Apple( $AAPL ),… https://www.macroaxis.com/invest/marketCorrelation?s=AAPL,XYL,IVZ,BAX,KMX,ROST,XLNX,VTR,PBCT,OKE,HUM #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 11:38:34 </td>
   <td style="text-align:left;"> $AAPL Long Term 🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 11:08:29 </td>
   <td style="text-align:left;"> $FSR during the recent fireside chat with Morgan Stanley Henrik (and Dan) seemed very confident, more than ever,  that the PEAR car with Foxconn will be a hit.  It’s as if there will be a connection with $AAPL but he just can’t say it outright yet.  He also keeps mentioning the shape of it and how you load it will be very unique which it hard to imaging but then again so was the iPhone before it came out…remember early renderings of the iPhone with a rotary dial etc. no one knew but Henrik seems to know that Fisker is in on something big. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 10:32:26 </td>
   <td style="text-align:left;"> $FB $AAPL $GOOG $AMZN $MSFT  will be 3-4 rate hikes this year, each a .25% increase.  So why the hell would these tech giants give a shit about borrowing money at 1% higher? I think the market would be severely overreacting if a sell off occurs within these names too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 10:25:49 </td>
   <td style="text-align:left;"> $ATOM While the clown shorts will tell you it is impossible Atomera is working with Tesla, I rely on facts not fake BS posted by anonymous clowns on stocktwits.  

Fact:  We are working with ST Micro 

Fact: ST Micro is a direct supplier to $TSLA and $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 10:14:04 </td>
   <td style="text-align:left;"> $AAPL I’m here to say I strongly believe Apple will make or popularize the Blockchain phone ✍🏿💎🤌🏿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 10:10:48 </td>
   <td style="text-align:left;"> $AAPL Perfect time to buy calls for earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 10:09:33 </td>
   <td style="text-align:left;"> Risk-adjusted landscape for Apple( $AAPL ), Keycorp( $KEY ),… https://www.macroaxis.com/invest/marketRiskAndReturn?s=AAPL,KEY,ADP,SYK,DHR,PEG,CME,PNW,EQR,FFIN,FCX,CVBF #canada #canadian_equities #CA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 10:08:17 </td>
   <td style="text-align:left;"> $AAPL The main takeaway from the daily chart is to recognize the blow off top that formed when it broke through the top of the channel on December 7. Wave 4 bounced off the top of the channel and now it bounced off it again on Friday. It&amp;#39;s about to break back into the channel, at which point, expect it to get crushed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 10:01:15 </td>
   <td style="text-align:left;"> $NVDA $TSLA, $AAPL time to test the real fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 09:40:40 </td>
   <td style="text-align:left;"> $AAPL In addition to sanctions on energy and consumer goods, the U.S. and its allies are considering bans on the export to Russia of advanced electronic components, software and related technology that uses American equipment. 
 
That would mean that Russia’s ability to obtain integrated circuits, and products containing integrated circuits, would be severely restricted, because of the global dominance of U.S. software, technology and equipment in this sector. The impact could extend to aircraft avionics, machine tools, smartphones, game consoles, tablets and televisions. https://www.marketwatch.com/story/biden-offers-carrots-threatens-sticks-with-russia-over-ukraine-01641676844?mod=mw_latestnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 09:40:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 6.11%. $AAPL outperforms 94% of its industry peers. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 09:23:30 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $AMZN 
Look at this Shit. This is how football players celebrate now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 09:22:37 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $BTC.X  sooooo now we got OMNIDELTA, …..puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 09:09:55 </td>
   <td style="text-align:left;"> $MRNA $PFE $AAPL $TSLA man…fking when is this Covid devil going to be over? Alpha, delta, Gama, omi erc. Now omidelta is on way. Then omialpha , alphadelta and so on…. Humanity is doomed. Fk to whoever invested this monster 😡😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 09:03:36 </td>
   <td style="text-align:left;"> $AAPL Oops </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 09:02:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-07 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=ZjorM95WyuM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 08:59:19 </td>
   <td style="text-align:left;"> $AMD $nvda  $tsla  $aapl   $FB  
 
 
THE POWER OF HEADLINES 
 
Headlines usually lead the way in changing market sentiment. But oftentimes these headlines also serve as indicators for contrarian investing. A study conducted by Paul Montgomery in the early ’80s found that if an investor followed the direction of the headlines in the stock market, he would usually be right for 30 days after the announcement. However, the direction would be wrong for the subsequent 11 months after the announcement in 80% of cases. As an investor, you would have been right 80% of the time by investing contradictory to the headlines 30 days after the publication for a period of 11 months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 08:39:31 </td>
   <td style="text-align:left;"> $AAPL God help Apple next week. Viewer discretion is advised! 👊🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 08:38:08 </td>
   <td style="text-align:left;"> $AAPL 64 of 100 charts in 60 minutes and in no particular order.  No notes this week because my goal is not to lead people to any conclusions.  In the end the market will always do what it wants despite our best efforts.  Our job as traders is to place our bets at optimal times, control our risk, and leave the rest up to the trading gods.

Remember to comment and/or like any charts that you want to see again next week.  The charts that get little to no love I&amp;#39;ll have to assume nobody cares about and those tickers will run the risk of being left off of the 100 charts in 60 minutes next week.  So, let&amp;#39;s get the conversation started and have some fun!

Side Note:  Last week I was unable to complete the 100 charts in 60 minutes.  It actually took me 90 minutes.  This week I actually 107 charts to post.  What are the odds I can complete it in 60 minutes???  Place your bets.  LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 08:08:41 </td>
   <td style="text-align:left;"> $SPY $DJIA $IWM $AAPL $TSLA all these &amp;quot;insider&amp;quot; politicians should be imprisoned and all gains should be used to build hospitals and parks, as it was intended, when the Federal Government started printing money for themselves. SMH. 
You are killing generations when you lie, steal and hide the prompt of your own interests at nation&amp;#39;s expense.

https://nypost.com/2022/01/07/nancy-pelosi-makes-30-million-from-tech-stocks-scoffs-at-push-to-ban-congressional-trades/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:47:55 </td>
   <td style="text-align:left;"> $AAPL someone bought 230K shares. 
 
Tech is in show mode. 

It will rise. No one makes a move like that without extra info. 

Crypto already is rising. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:43:43 </td>
   <td style="text-align:left;"> $AAPL Let us not forget. The best is yet to come🍏🚙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:42:49 </td>
   <td style="text-align:left;"> $AAPL 🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:41:21 </td>
   <td style="text-align:left;"> $AAPL looking to get back in under 170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:35:32 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:34:54 </td>
   <td style="text-align:left;"> Warren Buffett Moves Up The Top 10 Billionaires List As Berkshire Hathaway Hits All-Time Highs  $TSLA $BRK $MSFT $AMZN $AAPL 

https://newsfilter.io/a/d95f462bc57acb1afc4df138646e851a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:29:42 </td>
   <td style="text-align:left;"> $AAPL what does this company even do? Easy short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:27:01 </td>
   <td style="text-align:left;"> $ATOM Does anyone think that it is even slightly odd that the video suggesting an Atomera and $TSLA connection was taken down, no longer available to be viewed? Why would it have been pulled down?

Take that in conjunction with what a long time industry insider, with ties to UofA and formerly $AMAT said to his almost 5k LinkedIn followers. It really does make you wonder. 

STMicro is supplying Telsa and $AAPL   as we know for a fact, and we also know for a fact that Atomera has been working with ST Micro for many years now. I have said said epiphany here is likely going to be spectacular and transformational. Sure continues to be a lot of smoke for no  🔥. 

https://www.moroccoworldnews.com/2021/07/343433/stmicroelectronics-to-inaugurate-new-tesla-production-line-in-morocco </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:15:28 </td>
   <td style="text-align:left;"> $AAPL $MSFT buddy load up!! 50-50!!! Nothing else needed!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:14:24 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $AAPL is the #1 stock that institutions traded this week with 507.7K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:08:37 </td>
   <td style="text-align:left;"> $AAPL Can Apple Stock Reclaim $3 Trillion And Thrive In 2022?

https://www.thestreet.com/apple/stock/can-apple-stock-reclaim-3-trillion-and-thrive-in-2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 07:04:32 </td>
   <td style="text-align:left;"> $AMZN  People still haven’t digest how big this news is yet. Watch after the Fed tantrum is over we will all see. $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 06:54:53 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 06:51:54 </td>
   <td style="text-align:left;"> $QQQ $AAPL Are Funds really going to sell Apple now with ER and new product introductions coming up?  This could get interesting this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 06:45:59 </td>
   <td style="text-align:left;"> $SPY Hanging with papa Powell this weekend.

$aapl $msft $amd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 06:42:54 </td>
   <td style="text-align:left;"> $AAPL I don&amp;#39;t care what the naysayer gurus say , 130 pm today northern nj Apple store peeps waiting outside online to get in, the products and services are terrific!!! Don&amp;#39;t listen to them ,  this company is great !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 06:38:48 </td>
   <td style="text-align:left;"> $AAPL stock analysis 

https://youtu.be/2XxGKpah9zc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 06:38:15 </td>
   <td style="text-align:left;"> $NVDA $AMD $MSFT $FB $AAPL isn&amp;#39;t er that dictates the price of stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 06:06:30 </td>
   <td style="text-align:left;"> $NIO $TSLA $AAPL 

Feel free to follow me on Stocktwits for any updates and analysis.  Can also check out my YouTube channel. The link is in my profile. 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 05:59:37 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $AMZN  
 
$BABA Domed, hot articles plenty over weekend—$90’s next…25% up on GAPS—will fill all and some… 
 
https://www.cnbc.com/2022/01/07/chinas-property-problems-spread-to-once-healthy-developers-like-shimao.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 05:54:31 </td>
   <td style="text-align:left;"> $SPY $AAPL  reverse split then to the Moon ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 05:53:14 </td>
   <td style="text-align:left;"> $AAPL anyone think that there will be a period of time I’ll be able to sell these for profit? Or am I just screwed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 05:46:57 </td>
   <td style="text-align:left;"> latex5d1c1a873f311ffba603d22e52272f59 to 171$ and before ER this will fill the gap up and shoot up watch!! Second week of the New year makers always are  green..big bounce next week!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 05:17:44 </td>
   <td style="text-align:left;"> $AAPL depending on the overall market would be looking for  it to go above 173.80 in order to enter a bullish position, else around 168 would be a good entry point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 05:00:29 </td>
   <td style="text-align:left;"> $AAPL Let&amp;#39;s keep it up 🤑💸📉💸🤑💸📉💸🤑💸
if you love yourself invest in Pre-IPos.  I am placing a link for who I always use.Send them a message they are a good group.
Investors.be4ipo.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 04:52:06 </td>
   <td style="text-align:left;"> $AAPL Can’t wait to smash Apple again next week!
You ready?

https://vimeo.com/663767500/1d06f8aea4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 04:46:05 </td>
   <td style="text-align:left;"> $VERB 
Verb will have every tool under 1 roof for retail &amp;amp; any business that wishes to utilize Shoppable Live Stream for ecommerce &amp;amp;  Brand Awareness

Products
CRM &amp;amp; CMS w/Features
Verblive:1to1,1tofew strmin 
Verbmail: Shop vid/email
Attribution: Promotion tool
Market:Centralized Pltform
VerbTv:Shoppable content

Verbtv is scheduled to go live as centerpiece inside &amp;quot;Market&amp;quot; their ecommerce site. Producer David Meltzer who recently signed a deal w/$AAPL Tv will be providing content

Last year 
Verb 1st released Verblive
https://youtu.be/lpvFxCdvSjk

Then Verb&amp;#39;s Beta site went up for ui/ux functionality testing
https://www.shoppopup.tv

Verb then signed major dls w/Shop.com &amp;amp; NewAge, exposing Verb to 100&amp;#39;s of 1000&amp;#39;s of new subs

Then released free version of Verbmail
https://youtu.be/wZgoTt605Z0

The Attribution a promo tool &amp;amp; a way for camera shy promoters to earn commission w/o going on camera
https://youtu.be/bPOAjDbjeQE

Then released demo of the final product &amp;amp; how it will look

https://youtu.be/c5xKOK6VhZg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 04:42:33 </td>
   <td style="text-align:left;"> $AMD latexc90932ed187fec2b97a6c702e7c95625LCID - 62% call flow
$BAC - 91% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 04:19:07 </td>
   <td style="text-align:left;"> $AAPL $DIS $BABA 🤷🏼‍♂️🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 04:03:05 </td>
   <td style="text-align:left;"> $AAPL daily looking sick af🤢🤮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:55:26 </td>
   <td style="text-align:left;"> $SPY  Gonna go ahead here &amp;amp; bet every $ I’ve made my followers that neither bitcoins, or shitcoins, or Witcoins will affect the S&amp;amp;P500 into $JPM &amp;amp; $AAPL earnings mid to end of month. $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:51:41 </td>
   <td style="text-align:left;"> $AAPL Smart toilet paper, turns a color when you test positive for covid. Thank me later Tim Cook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:42:55 </td>
   <td style="text-align:left;"> $AAPL Looking for 160 area. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:41:30 </td>
   <td style="text-align:left;"> &amp;gt; https://www.tomshardware.com/news/amd-ryzen-7000-zen-4-16-core-8-core-cpus
$AMD ↗️ + $XLNX | $AAPL 
$MSFT | $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:40:04 </td>
   <td style="text-align:left;"> $AAPL $BA $DIS Make STACKING your goal for 2022… last weeks plays PAID
YOU ready for next weeks?💰👊🏼🤑

https://www.instagram.com/reel/CYew4mYJSXA/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:38:24 </td>
   <td style="text-align:left;"> $AAPL Apple CEO Earns $98.7 million in 2021, Five Times More than 2020 https://www.robinhoodnews.com/apple-ceo-earns-98-7-million-in-2021-five-times-more-than-2020/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:30:27 </td>
   <td style="text-align:left;"> $SPY $FB $TWTR $GOOG $AAPL  
 
It&amp;#39;s both a tragedy and travesty 
one&amp;#39;s Constitutional right of the freedom of speech 
does not extend to &amp;quot;social&amp;quot; media platforms 
due to their status as private corporations 
while basically having replaced the public forum from the past. 
 
The government knows this.   
Touting freedom while giving none. 
 
Let the day of reckoning be harsh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:29:53 </td>
   <td style="text-align:left;"> What Is Carry Trading? $SVXY $AAPL $SPY $VIX https://talkmarkets.com/content/stocks--equities/what-is-carry-trading?post=340517 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:21:18 </td>
   <td style="text-align:left;"> $AAPL https://www.youtube.com/watch?v=CJh59vZ8ccc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:13:24 </td>
   <td style="text-align:left;"> $AAPL hey do you like U2? I can give you their latest album for free! You want it don’t you? Right? SAY SOMETHING! Ohhh playing hard to get? Tehehe check your iTunes and thank me later 😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:08:42 </td>
   <td style="text-align:left;"> How To Create An Edge To Make Money Trading

$TSLA $MRNA $AAPL $FUBO $GME 

https://www.chartlearning.com/2021/07/how-to-measure-your-trading-edge.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 03:05:35 </td>
   <td style="text-align:left;"> $NVDA if valuations will start to matter than Nvidia should get cut in half. $AAPL and AMD have a P/Sales around 10, Nvidia&amp;#39;s is 28!! Apple P/E is around 10, Nvidia 84! How and why did Nvidia get up here? I have no clue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:57:40 </td>
   <td style="text-align:left;"> $AAPL just stay safe $BHP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:55:17 </td>
   <td style="text-align:left;"> $SPY $AAPL $BAC Just keep buying and holding.  The big drops just mean we get more shares at cheaper prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:44:52 </td>
   <td style="text-align:left;"> “Novice traders &amp;amp; investors seem to buy more into the future growth stories than most of the market. 80% of large cap trading is done by institutions, (60% passive 20%+ trend following algos), retail is a much smaller mix. One of many reasons why markets don&amp;#39;t do what most expect.”
$AMD + $XLNX | $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:39:09 </td>
   <td style="text-align:left;"> $BTC.X if you aren’t bullish you are probably bearish on $AAPL too 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:32:51 </td>
   <td style="text-align:left;"> $AAPL enters bullish trend https://srnk.us/go/3308271 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:26:12 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $AAPL is the #1 ticker with sweep activity that institutions traded urgently this week options with 455.5K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:13:52 </td>
   <td style="text-align:left;"> $AAPL when you guys think we hit 180 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:05:41 </td>
   <td style="text-align:left;"> $SHOP $AAPL $TSLA  any bounce before earnings  could be last bounce before 👇👎👇👎👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:04:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-07 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=ZjorM95WyuM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 02:00:23 </td>
   <td style="text-align:left;"> $AAPL curious to hear any bear argument on why is this overvalued.    Warren Buffett once said he didn&amp;#39;t invest in tech because he didn&amp;#39;t understand how computers work but this is now 40% of his personal portfolio.  And he&amp;#39;s not one to just hurl money around blindly (he&amp;#39;s not Cathy Woods lol).   
 
I only own it through $QQQ and $SPY  
 
TIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 01:58:09 </td>
   <td style="text-align:left;"> Finished the week with 22 Wins &amp;amp; 0 Losses. That is a Win Rate of 100% for the week. $SPY $MSFT $AAPL

Play of the week:

$SPX- 4760 Puts at $3.30 went to $55 - 1,000%+

Having a flawless week is a great way to start off the new year. Looking forward to keeping the streak alive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 01:57:11 </td>
   <td style="text-align:left;"> $AAPL enters bullish trend https://srnk.us/go/3308175 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 01:39:20 </td>
   <td style="text-align:left;"> $AAPL Buy 100 of these </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 01:27:42 </td>
   <td style="text-align:left;"> Oh wow this is big! $AAPL in Downtrend: RSI indicator exits overbought zone. View odds for this and other indicators: https://srnk.us/go/3308096 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 01:20:51 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s go....................,...
Do not save what is left after spending but spend what is left after saving.
if you love yourself invest in Pre-IPos.  I am placing a link for who I always use.Send them a message they are a good group.
Investors.be4ipo.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 01:16:15 </td>
   <td style="text-align:left;"> $AAPL as well with the 50% retracement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 01:14:11 </td>
   <td style="text-align:left;"> $AAPL $3 Trillion reasons to invest in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 00:57:13 </td>
   <td style="text-align:left;"> 1 of 11 $AAPL $AMGN $AXP Daily and 30 min charts of the DJIA Components with the SSI indicator, a proprietary indicator based exclusively on the eSignal platform, are posted here weekends … see 2/11 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 00:51:54 </td>
   <td style="text-align:left;"> $DIDI $BABA $TENCENT $AAPL $UBER 
how can it trade 1/3r or 1/4th valuation when transaction volume only dipped 3%(Q2-&amp;gt;Q3)  with worst showdown with china authorities like no app/ no new user registration etc...softbank/apple/uber/tencent/alibaba/CIC owns closer to 50% of the company and they have not sold anything and valuation is lower than october 2016 round... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-09 00:49:09 </td>
   <td style="text-align:left;"> Why Apple’s iMessage Is Winning: Teens Dread the Green Text Bubble - WSJ … genius $aapl 

Time will tell if it’s still fragile  https://www.wsj.com/articles/why-apples-imessage-is-winning-teens-dread-the-green-text-bubble-11641618009 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 16:00:28 </td>
   <td style="text-align:left;"> $TSLA The bears must be hibernating. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:51:41 </td>
   <td style="text-align:left;"> $TSLA look exactly like last Monday. I just hope we don’t have the same Tuesday - Friday same as last week. 
Looking good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:49:54 </td>
   <td style="text-align:left;"> $SPY if fut can keep the momentum, even when theres a dip at the open, i believe all fang tech will push it higher. $TSLA $AAPL $AMZN $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:47:37 </td>
   <td style="text-align:left;"> Asus&amp;#39; $1,650 all-AMD #gaming laptop delivers excellent performance and battery life, with a top-of-the-line Ryzen 9 5900HX CPU and Radeon RX 6800M GPU -- and that&amp;#39;s before you realize that the performance and components are way above its price class.
&amp;gt; https://www.cnet.com/tech/computing/gaming-monitors-from-ces-2022-to-get-hyped-for/ 
$AMD ↗️ + $XLNX 
$MSFT | $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:42:51 </td>
   <td style="text-align:left;"> $TSLA  
 
The future belongs to us!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:42:07 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:41:44 </td>
   <td style="text-align:left;"> $TSLA bears better get your lube on now cause I ain&amp;#39;t stopping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:40:32 </td>
   <td style="text-align:left;"> $TSLA due for a green day, 4 days of absolute shit..

the negative catalysts aren&amp;#39;t until Tuesday/Wednesday and maybe the market likes the news who knows!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:39:49 </td>
   <td style="text-align:left;"> $TSLA 1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:39:11 </td>
   <td style="text-align:left;"> $TSLA 

$1,052.82 in Germany </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:39:00 </td>
   <td style="text-align:left;"> $TSLA woke up to 370% profit on my tesla contracts last monday opening, i wonder what i will see this monday 🤑 tesla is too easy to read </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:36:58 </td>
   <td style="text-align:left;"> $TSLA there is no better feeling than waking up and see bears getting wreked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:36:04 </td>
   <td style="text-align:left;"> $TSLA ba ha ha .. bears.. this will run back up.. loads of catalysts ahead .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:34:44 </td>
   <td style="text-align:left;"> $TSLA $1052.74 in Frankfurt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:34:10 </td>
   <td style="text-align:left;"> $TSLA 5% day right at open to start it off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:33:59 </td>
   <td style="text-align:left;"> $TSLA $GOOGL $PYPL $AMZN $AAPL Hope it stays green the whole Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:33:43 </td>
   <td style="text-align:left;"> $TSLA sorry bears, but you&amp;#39;re f*k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:31:35 </td>
   <td style="text-align:left;"> $TSLA   You didnt hold PUTS over the week-end, did you ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:30:05 </td>
   <td style="text-align:left;"> $TSLA $1100 open 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:26:56 </td>
   <td style="text-align:left;"> $TSLA breakout in germany +2,36% 1047 on the ask. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:25:57 </td>
   <td style="text-align:left;"> $SPY   $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:24:47 </td>
   <td style="text-align:left;"> $TSLA futures ripping 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:24:12 </td>
   <td style="text-align:left;"> $TSLA $1200+ ✅🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:23:54 </td>
   <td style="text-align:left;"> $TSLA $1044 in Germany </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:23:02 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:18:59 </td>
   <td style="text-align:left;"> $TSLA Tesla Owner Says He Makes $800 A Month Using His Model 3 To Mine Bitcoin, Ethereum 

https://newsfilter.io/a/5083fa3a16ac0dae640f4ecfd0c5b7c3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:12:25 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ 

FUTURES UPDATE FOR THE SHORTS 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:10:55 </td>
   <td style="text-align:left;"> How NASA Plans To Use The Orion Space Launch System &amp;amp; SpaceX Starship To Land The Next Astronauts On The Moon 
 
$TSLA 
 
https://www.tesmanian.com/blogs/tesmanian-blog/sls-hls-2025 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:10:10 </td>
   <td style="text-align:left;"> $TSLA Roaring Nasdaq futures 😆Green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:08:50 </td>
   <td style="text-align:left;"> $TSLA $1,037.99 Frankfurt premarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:07:43 </td>
   <td style="text-align:left;"> $TSLA $AMD $NVDA futures not looking strong , might be red at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:07:30 </td>
   <td style="text-align:left;"> $TSLA $1041 USD in Germany </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:07:02 </td>
   <td style="text-align:left;"> North Judson PD in Indiana Goes Electric, Adds Tesla Model Y to Police Fleet 
 
$TSLA 
 
https://www.tesmanian.com/blogs/tesmanian-blog/the-north-judson-pd-in-indiana-goes-electric-with-tesla-model-y-in-police-fleet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:04:43 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-09 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=uO_DgRipZfw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:03:29 </td>
   <td style="text-align:left;"> $TSLA Germany $1040 asking price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:02:38 </td>
   <td style="text-align:left;"> $TSLA I know it says nothing. But opened green +1,23% in germany. Probably just the AM buys. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:01:19 </td>
   <td style="text-align:left;"> $TSLA all futures are green now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 15:00:47 </td>
   <td style="text-align:left;"> $PLUG Partner Gaussin For the first time, a 100% hydrogen-powered truck is taking part into the Dakar.
As the official partner for clean technologies and as part of #DakarFuture, the H2 RACING TRUCK® from 
@GaussinGroup
 pushes its limits in the though conditions of the race.
#Dakar2022 https://twitter.com/dakar/status/1479750977825611779?s=20

$NKLA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:57:11 </td>
   <td style="text-align:left;"> $TSLA pump master doge daddy. Fook dat guy
 https://www.reddit.com/r/Epic_Economics/comments/s0dpcz/the_binance_ceo_his_mega_fortune_frauds_abundant/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:55:15 </td>
   <td style="text-align:left;"> $TSLA 
Bitcoin to zero , soon!

Blackout in Berlin: Heating power plant offline. 370,000 households reportedly without electricity and heating. Hot water supply is also interrupted (Focus) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:54:14 </td>
   <td style="text-align:left;"> $TSLA Ayeee boys some extra fun money to be made at night, and you can search up reviews, it’s legit and pays much better lol https://send.cloutzap.com/Ali786 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:49:00 </td>
   <td style="text-align:left;"> $TSLA $1,300 this week MINIMUM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:48:25 </td>
   <td style="text-align:left;"> $TSLA $1167 in Fuckshitstan open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:43:55 </td>
   <td style="text-align:left;"> $TSLA doge daddy really did u dirty
 https://www.reddit.com/r/Epic_Economics/comments/s0dh48/crypto_death_crossed/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:41:45 </td>
   <td style="text-align:left;"> WATCHLIST  1/10/21 - 1/14/21 MON - FRI
PT-4
OPTIONS

$UPS - Stock forming inverse head and shoulders on charts. Close to breaking all time highs. Calls above $220

$QCOM -. GM To Use Qualcomm&amp;#39; Snapdragon Ride Platform For Advanced Driver Assistance Technology. Calls above $182.25

$MU - stock is looking strong on charts. Possible triple digits incoming. Calls above $95

$TSLA -  Stock breaking key support level on friday. Calls above $1035. Puts below $1000

$SNOW - Stock ending the week with two small green candles indicating a possible reversal. Calls above $305

https://rooms.stocktwits.com/checkout/4451239/prod_KEH7byRXcPlJ63 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:33:52 </td>
   <td style="text-align:left;"> $TSLA I honestly believe this is going to 950 this week. 

But I&amp;#39;m not going to get puts. I already banked profit shorting it from 1100 to 1026. 

400% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:33:38 </td>
   <td style="text-align:left;"> $TSLA  A 1% rate increase corresponds to a 1% correction. $TSLA crash 20% on a 0.25 % rate increase which is total BS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:33:37 </td>
   <td style="text-align:left;"> $TSLA $1226 today with GS upgrade. Bears will be learning some lessons here undoubtedly. 😇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:30:27 </td>
   <td style="text-align:left;"> $AMZN $TSLA $AAPL 

Niiiiiice! Great scanners! 

Just banked from your scanners ...

Love it... thankful to the whole team 😇

🙌  tinyurl.com/vudipvxdc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:27:43 </td>
   <td style="text-align:left;"> $CEI you guys ready $TSLA to be coworkers? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:27:15 </td>
   <td style="text-align:left;"> $TSLA Tech and Dow futures are in equilibrium :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:27:13 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/k-4fySgpPvU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:25:37 </td>
   <td style="text-align:left;"> $TSLA red day forming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:21:41 </td>
   <td style="text-align:left;"> $TSLA “futures are ripping” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:19:28 </td>
   <td style="text-align:left;"> $TSLA it will open 1045-1055 range </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:17:37 </td>
   <td style="text-align:left;"> $TSLA really 12k in Jan 17? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:15:18 </td>
   <td style="text-align:left;"> $TSLA fuck your calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:10:29 </td>
   <td style="text-align:left;"> $TSLA ohhhhh shit $970 looking good for tomorrow....puts are going to print. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:08:58 </td>
   <td style="text-align:left;"> $TSLA bought a few 1090$ calls before close. News this weekend is promising. Lets pump again like last Monday 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:08:13 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-09 Technical Analysis Video: 
https://www.youtube.com/watch?v=zN0Oh_3bq8k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:06:57 </td>
   <td style="text-align:left;"> $TSLA when are the China delivery numbers released? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:06:54 </td>
   <td style="text-align:left;"> $TSLA  can it pull off another 10% day 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:04:16 </td>
   <td style="text-align:left;"> $TSLA buyin innovation https://youtu.be/ucQSD9ayiv8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:02:59 </td>
   <td style="text-align:left;"> Apple Rivals Microsoft, Blackberry, Nokia Laughed At iPhone, Shrugged It Off And Flung It To The Ground As Steve Jobs Lifted The Curtains — 15 Years Later, Here We Are  $AAPL $BB $NOK $TSLA 

https://newsfilter.io/a/20927dc03ceafdc4e56bdb5868809fe6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 14:02:53 </td>
   <td style="text-align:left;"> $TSLA will spend 2022 under $1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:59:54 </td>
   <td style="text-align:left;"> $TSLA https://www.streetinsider.com/dr/news.php?id=19438015&amp;amp;gfv=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:59:17 </td>
   <td style="text-align:left;"> $SAITAMA-X $TSLA #wolfpack #saitamask we running </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:58:24 </td>
   <td style="text-align:left;"> $TSLA Tesla S prototype at the Petersen Auto Museum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:57:34 </td>
   <td style="text-align:left;"> $TSLA Big Day coming ip. Leta go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:56:53 </td>
   <td style="text-align:left;"> $TSLA get ready bears, don&amp;#39;t clench your buttholes tomorrow, it will only hurt more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:56:31 </td>
   <td style="text-align:left;"> $TSLA This is cathys piggy bank, just keep cashing them gains on tsla.. that fucking gilf.. smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:54:23 </td>
   <td style="text-align:left;"> ⏳📈💰 $TSLA - Cathie Wood Sells Another $12M Shares In Tesla On Friday — Buys These Stocks On The Dip - Roku, Square &amp;amp; Coinbase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:54:14 </td>
   <td style="text-align:left;"> $TSLA Big short these 🥜… tomorrow y’all will pay back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:53:23 </td>
   <td style="text-align:left;"> $IIVI $TSLA $AAPL $AMZN https://www.fool.com/investing/2021/01/18/how-to-invest-in-5g-cloud-computing-autonomous-ele/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:48:23 </td>
   <td style="text-align:left;"> $SPY $TSLA 

https://www.businessinsider.com/big-short-michael-burry-elon-musk-tesla-gamestop-crypto-crash-2022-1?amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:46:04 </td>
   <td style="text-align:left;"> $TSLA $SOFI $LCID 
So funny! 😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:44:16 </td>
   <td style="text-align:left;"> $TSLA   NASDAQ FUTURES RIPPIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:42:51 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:42:10 </td>
   <td style="text-align:left;"> $TSLA drops and pops. Load up on the drop.  BTW My guess is good as anyone on stocktwist 😄 🤣 😂  but the risk is all your, don&amp;#39;t blame anyone for losing. Casino opens in few hours. Gl fellas. &amp;quot;#BWBB&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:39:22 </td>
   <td style="text-align:left;"> $TSLA Garbage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:39:04 </td>
   <td style="text-align:left;"> $ARKK $SPY $QQQ $TSLA beautiful bullish flag im going to start a long position ~70/60 
 
i think arkk goes to 180 by eoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:38:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $SQQQ $TSLA just your market maker doing a mini pump pre market so they can exit in the morning or tuesday,  dont be the donkeys that buying the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:33:56 </td>
   <td style="text-align:left;"> $TSLA we test 1000 early </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:24:09 </td>
   <td style="text-align:left;"> $TSLA I purchased a few shares at $1050 Am I fucked? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:17:58 </td>
   <td style="text-align:left;"> $TSLA Elon the doge daddy has no way out. Pumped for personal gain. Pay the consequences. 🙌💣🔥☠️
 https://www.reddit.com/r/Epic_Economics/comments/s0bxch/balance_sheet_runoff_stock_market_crypto_killer/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:15:32 </td>
   <td style="text-align:left;"> $TSLA why is this not all over Twitter? LETS GO!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:12:42 </td>
   <td style="text-align:left;"> $TSLA Stocks which are highly valued will come down this year !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:11:28 </td>
   <td style="text-align:left;"> $TSLA pop up tomm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:10:45 </td>
   <td style="text-align:left;"> $TSLA damn futures are still red.....do you remember once upon a time when stocks were a good investment? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:09:52 </td>
   <td style="text-align:left;"> $TSLA alright, let’s see what you are made of. 
 
55 pt (+.33%) move on the nq1! (nasdaq mini’s) in the last hour. I like the conservative but notable rise on the $SPY  minis, at about +.12% in the past Hour and some change. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:09:36 </td>
   <td style="text-align:left;"> $TSLA NASDAQ AND SPY GREEN.. LFG MF&amp;#39;RS 🔥🔥✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:09:28 </td>
   <td style="text-align:left;"> $TSLA This guy has a good track record! Watch this! https://youtu.be/1gAoQ7LD-nI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:08:36 </td>
   <td style="text-align:left;"> $TSLA Inflation is way too serious. Fed should increase interest rates and do QT as soon as possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:07:11 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-09 Options Analysis Video: 
https://www.youtube.com/watch?v=Z5EFxUStxMY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:05:05 </td>
   <td style="text-align:left;"> Tesla $TSLA BidaskScore is #Reiterated to Held https://bidaskclub.com/news/company/2022-01-06/TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:04:10 </td>
   <td style="text-align:left;"> $TSLA if there is any meaningful pop should just sell into it market is jittery with fed and cpi data coming this week care </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:02:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA next goal is to break out of this channel and1 hour 21 ema, if we can do that.. we are set </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 13:01:59 </td>
   <td style="text-align:left;"> $TSLA This Coin Named After Elon Musk&amp;#39;s Pet &amp;#39;Floki&amp;#39; Is Up Over 740% Even As Dogecoin And Shiba Inu Trade Muted 

https://newsfilter.io/a/84cc8d4e87b61275d1030e2b263a35e6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:57:53 </td>
   <td style="text-align:left;"> $TSLA $SOFI $LCID 
In one one and a half year all these will be 3X!!! 
So just forget about them for a year and pretend you dont have them! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:57:41 </td>
   <td style="text-align:left;"> $TSLA insanely cheap 

https://youtu.be/k-4fySgpPvU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:56:21 </td>
   <td style="text-align:left;"> $TSLA https://media.discordapp.net/attachments/458459657015525378/929946627232374794/IMG_4016.png </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:56:10 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:56:06 </td>
   <td style="text-align:left;"> $TSLA do far everything suggests a small recovery during pre mkt, probably to the high 1030-s:
- Nasdaq futures green, +0.33%
- Bitcoin is up, reclaimed 42k and is holding
- opinion of Dan Ives that Texas opens soon (pay attention, it&amp;#39;s just a speculation)
- new note from GS with PT 1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:53:55 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY MARKETS WILL BE PUMPED AROUND BIDEN ANNIVERSARY and ER for one last time before … the inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:49:12 </td>
   <td style="text-align:left;"> $TSLA It&amp;#39;s happening! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:48:14 </td>
   <td style="text-align:left;"> $TSLA Reddit on your knees! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:48:13 </td>
   <td style="text-align:left;"> $TSLA Even though it don&amp;#39;t mean anything futu&amp;#39;s are green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:47:51 </td>
   <td style="text-align:left;"> $TSLA Giga Texas production will start with Tesla Model Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:47:18 </td>
   <td style="text-align:left;"> $TSLA Could be nothing, could be something. https://twitter.com/SawyerMerritt/status/1480383632867049483?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:46:50 </td>
   <td style="text-align:left;"> $TSLA Dow futures red and nasdaq green… makes complete sense with rotation back into tech, let’s hope it holds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:45:42 </td>
   <td style="text-align:left;"> $TSLA The Tesla Analyst: Wedbush analyst Daniel Ives has an Outperform rating and a $1,400 price target for Tesla shares, with the bull case price target at $1,800. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:44:18 </td>
   <td style="text-align:left;"> $TSLA futures are red as shit... tha fuk? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:41:14 </td>
   <td style="text-align:left;"> $TSLA  futures green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:39:10 </td>
   <td style="text-align:left;"> Algos and Trading: Conversation with Money Moves Investment&amp;#39;s Creator https://youtu.be/3edLz1rs9KA with @dallionking 

$SPY $TSLA $BTC $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:38:12 </td>
   <td style="text-align:left;"> $TSLA it funny when bears say please 🤣 😂 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:38:06 </td>
   <td style="text-align:left;"> $TSLA run it the f up im hungry again for that sub 1k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:37:59 </td>
   <td style="text-align:left;"> $TSLA Going all in tommorow for a swing trade. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:37:00 </td>
   <td style="text-align:left;"> $TSLA love how the noobs are excited about being up slightly on futes. Check it out DOW about to go red. Why would nasdaq be green tomorrow. So far Jan has sucked and how Jan goes so goes the year. We need a big ass pullback in order to stop market from toppling completely over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:36:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 
BEARS WHAT HAPPENED TO THE CRASH ???!
Five hours ago when futures opened and were down .4  percent, u said limit down circuit breakers ??!! Now futures ALL GREEN and nasdaq getting a pump and let me guess your response “FUTures don’t MATtter, red by morning?!” 😂😂😂
FUTURES UPDATE FOR THE SHORTS  👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:35:20 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-09 Largest Trades Data: 
https://www.youtube.com/watch?v=Gtq03JHi3IA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:34:55 </td>
   <td style="text-align:left;"> $TSLA 1200 eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:32:16 </td>
   <td style="text-align:left;"> $TSLA there some &amp;quot;news&amp;quot; about the drop of 10y note futures

Pay attention to two things
- it&amp;#39;s about the note, not Yield. Note price action is the inverse of yield

- the drop over weekend is very very small, insignificant. The news is about the fact that the absolute value hit the very low level. But it didn&amp;#39;t happen over weekend, it&amp;#39;s the results of the drop during last months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:31:56 </td>
   <td style="text-align:left;"> $TSLA we got good news, why are a lot of people saying it’s bearish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:31:30 </td>
   <td style="text-align:left;"> $SPY we already experienced halted down pre-covid. Can we experience halt up by fed pump? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:30:07 </td>
   <td style="text-align:left;"> $TSLA Probably up tomorrow and then down before Jerome Powell’s confirmation hearing on Tuesday with possible positive remarks from him then all the way up nonstop until their next meeting on January 24th </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:29:02 </td>
   <td style="text-align:left;"> $TSLA 1200$ this week 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:26:09 </td>
   <td style="text-align:left;"> $TSLA I don’t think that Fed will move in a way that will crash markets which will hurt millions of retail investors and  their families financially and it’s huge impact on Economy. Even markets don’t know how quickly they will move on reducing their balance sheet. These are just possibilities that markets makers react on. When we hear some positive news about their certain plans on reducing balance sheet. The markets will skyrocket from this level by burning all short sellers alive😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:24:06 </td>
   <td style="text-align:left;"> $TSLA 

GS price target $1200 check
Giga Austin revving this week check 
Elon having fun on Twitter check 
Earnings going to be bananas check 

Which way is price headed this week?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:23:30 </td>
   <td style="text-align:left;"> $TSLA $AMD $NVDA $SPY 

Who’s ready to trade tomorrow!!

Join the free discord to get free alerts!

Link in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:22:53 </td>
   <td style="text-align:left;"> $TSLA Goldman Sach $1200+ ✅🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:19:09 </td>
   <td style="text-align:left;"> $TSLA Goldman the most prestigious bank in the world. 20% 1 yr target is 5 X the expected 1 yr return of the major equity indices Pegged at4% 1 yr.  GMO says down 7%. Going higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:17:42 </td>
   <td style="text-align:left;"> $TSLA Buying $900 put around open. If it dips buying 15 shares. Let’s go 😆✊🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:14:09 </td>
   <td style="text-align:left;"> $TSLA futures looking green we trap good amounts of bears before Q4 earnings.

Follow by inflation data this Wednesday we  looking good boys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:11:51 </td>
   <td style="text-align:left;"> $TSLA let the upgrades begin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:11:45 </td>
   <td style="text-align:left;"> $TSLA tomorrow we ride </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:08:36 </td>
   <td style="text-align:left;"> $TSLA $850 please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:06:38 </td>
   <td style="text-align:left;"> $TSLA @sambal This is one of the biggest pumpers on this board along with @Borggss .  Don&amp;#39;t follow his advice.  If you do you will go broke.  Look at all the money he has lost as of late writing these crazy put options. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:06:29 </td>
   <td style="text-align:left;"> $TSLA is a $67 stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:06:23 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-09 Daily Forecast Video: 
https://www.youtube.com/watch?v=7vdS9w9q2j8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:06:12 </td>
   <td style="text-align:left;"> $TSLA futes rippin or trippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:05:37 </td>
   <td style="text-align:left;"> $TSLA My puts will make some money tomorrow hopefully. I see 950$ coming this week. Sell or hold for long term. These week markets will resemble last week again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:04:42 </td>
   <td style="text-align:left;"> $SPCE $TSLA $RIVN How To BEAT The Options Market With Greeks Explained &amp;amp; MORE on this episode of WNW
Be sure to like, comment, and subscribe!📺

https://youtu.be/0AW-EzMDy70 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:03:57 </td>
   <td style="text-align:left;"> $TSLA how you drive home to tell your wife Tesla hit $3000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:03:24 </td>
   <td style="text-align:left;"> $TSLA puts at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:03:02 </td>
   <td style="text-align:left;"> $TSLA is one of the better performing stocks in the Automobiles industry. https://www.chartmill.com/stock/quote/TSLA/technical-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:02:37 </td>
   <td style="text-align:left;"> $TSLA be ready for a Nasdaq snap back rip your face rally ……only short term, long term markets have to figure out fed fucking everyone by unwinding balance sheet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 12:02:07 </td>
   <td style="text-align:left;"> $TSLA If this dips more tomorrow buying more.  I really hope it does. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:59:17 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!!

TREASURY 10-YEAR FUTURES DROP TO LOWEST SINCE DECEMBER 2019

🙏🏻🦅🐉👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:56:19 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:56:11 </td>
   <td style="text-align:left;"> $TSLA goldman Sachs raised price target...$1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:54:47 </td>
   <td style="text-align:left;"> $MRNA 2021 $JPM Health Care conference presentation was impressive, and impressively they followed through on promises and targeted progress. 2021 Presentations will be HUGE! This is $TSLA of biotech 
 
https://s29.q4cdn.com/745959723/files/doc_presentations/events-presentations/2021/01/JPM-Master-Final-Presentation-(01.11.21).pdf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:53:51 </td>
   <td style="text-align:left;"> $TSLA When I saw they used a callin iOS only app I knew they were idiots. God bless Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:53:07 </td>
   <td style="text-align:left;"> $TSLA not safe stock to be in at this time!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:50:20 </td>
   <td style="text-align:left;"> $TSLA I hope those idiots on the Texas owner conference won&amp;#39;t tank the stock tomorrow. I am so tired of the endless supply of idiots in the world. God bless Tesla! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:49:23 </td>
   <td style="text-align:left;"> $TSLA Mary&amp;#39;s gonna run that company into the ground. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:49:01 </td>
   <td style="text-align:left;"> $TSLA  I am looking for position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:47:49 </td>
   <td style="text-align:left;"> $TSLA Texas in production within 10 days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:44:01 </td>
   <td style="text-align:left;"> $GME $AMC $TSLA https://www.reddit.com/r/Superstonk/comments/s09j6m/keep_it_alive_charles_gradante_deep_dive_into_gme/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:42:54 </td>
   <td style="text-align:left;"> $TSLA 

🙏🏻🐉🦅🤥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:41:36 </td>
   <td style="text-align:left;"> $TSLA not inflation; not “deltacron”;  nothing can stop this stock market.  Nothing!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:40:52 </td>
   <td style="text-align:left;"> $TSLA 886 🥶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:39:09 </td>
   <td style="text-align:left;"> $TSLA The announcement is a bunch of Tesla nerds wants to have a Giga Austin party but don’t know anything about throwing a party!
😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:38:07 </td>
   <td style="text-align:left;"> $TSLA buy  Beat down stock $WW. to the moon WW this is the time to shine $WW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:38:04 </td>
   <td style="text-align:left;"> $TSLA you see how Tesla isn’t crashing?  It’s trying to shake out weak hands.  Go all in on this ticker!  It will continue to rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:37:35 </td>
   <td style="text-align:left;"> $TSLA What happened to the $2500 and $5000 predictions? LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:37:13 </td>
   <td style="text-align:left;"> $TSLA $NKLA Now that&amp;#39;s what I call karma is a bitch.. Cathie Woods prediction for $NKLA was 0... she lost 48% with her ARK fund last week.. $NKLA beat the market last week with 7% .... https://www.google.com/amp/s/www.cnbc.com/amp/2022/01/06/sell-off-in-cathie-woods-ark-innovation-fund-reached-48percent-at-low-point-thursday.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:36:48 </td>
   <td style="text-align:left;"> $ETH.X is now classified as stocks like $TSLA $NVDA on dips. Everyone have to at least have some in their portfolio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:36:38 </td>
   <td style="text-align:left;"> $TSLA Apple partnership ? Now thats interesting ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:35:07 </td>
   <td style="text-align:left;"> $TSLA 
More fresh selling and lower lows tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:34:48 </td>
   <td style="text-align:left;"> $TSLA Can we 1500s? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:33:53 </td>
   <td style="text-align:left;"> $TSLA $1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:33:42 </td>
   <td style="text-align:left;"> $TSLA Just poured a cold beer and grabbed a bucket of popcorn.  This is truly comical reading these.
“3 for 1 split”
“Down 300 tomorrow”
“4 for 1 split”
“Up 300 tomorrow”
“To the Moon”
“Partnership with Apple”
“Going bankrupt”
Good luck tomorrow whichever side you are on.
Thanks for all of the laughs! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:33:36 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-09 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=uO_DgRipZfw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:33:07 </td>
   <td style="text-align:left;"> $CYDVF Nice https://aheadoftheherd.com/cypress-development-a-potential-low-cost-lithium-producer-in-nevada-to-look-out-for-in-2022/. $ALB $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:32:43 </td>
   <td style="text-align:left;"> $TSLA who’s watching futures to? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:31:19 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:30:59 </td>
   <td style="text-align:left;"> $TSLA when the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:30:59 </td>
   <td style="text-align:left;"> $TSLA Cathie Wood Sells Another $12M Shares In Tesla On Friday — Buys These Stocks On The Dip 

https://newsfilter.io/a/ef5a297eafc9fe2b54adafacaebdb027 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:30:22 </td>
   <td style="text-align:left;"> $TSLA fuck me sideways. LETS GO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:30:21 </td>
   <td style="text-align:left;"> $TSLA these owner conferences are the biggest pointless circle jerks ever. Dunno why anyone would think it’ll have any impact in the stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:30:19 </td>
   <td style="text-align:left;"> $TSLA 900 before 1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:29:27 </td>
   <td style="text-align:left;"> $TSLA  F U bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:28:52 </td>
   <td style="text-align:left;"> $AMC We are North American Apes                                                                                                                                         
                                                                                                                               
Americans                                                                                                                                         
Mexicans                                                                                                                                         
Canadians                
     
We hate Shorts!  
Buy 100 calls 28$ AMC 1/14 
Buy 30 calls $150 $GME 1/14 
Buy 10 calls $1150 $TSLA 1/14 
 
Follow for free plays 
OptionDonkeys.EveryMonday.com 
                                             
 Let’s Go. We rise as One! Worldwide </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:28:20 </td>
   <td style="text-align:left;"> $TSLA 
So this call seems to be a big NOTHING BURGER.

Just a bunch of swinging Dick tsla owners </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:27:22 </td>
   <td style="text-align:left;"> $TSLA 

Any serious announcement will come only from Tesla officially ! 

🙏🏻🦅🐉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:26:50 </td>
   <td style="text-align:left;"> $TSLA flat till next ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:26:47 </td>
   <td style="text-align:left;"> $TSLA 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:26:21 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:25:58 </td>
   <td style="text-align:left;"> $TSLA been waiting for hours then…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:24:32 </td>
   <td style="text-align:left;"> $TSLA Whoever called that 4th and 1 go for it yolo on your own 18 yard line  .....  gets fired tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:23:59 </td>
   <td style="text-align:left;"> $TSLA new PT 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:23:59 </td>
   <td style="text-align:left;"> $TSLA JUST ANNOUNCED PARTNERSHIP WITH APPLE! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:23:23 </td>
   <td style="text-align:left;"> $TSLA I will be thrilled if we see $1100 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:23:18 </td>
   <td style="text-align:left;"> $TSLA very dissapointed ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:23:11 </td>
   <td style="text-align:left;"> $TSLA 4:1 split!!!! Fuck ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:22:58 </td>
   <td style="text-align:left;"> $TSLA Tesla Con in Austin around the giga party.. final dates to be announced 🥳 see you there 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:22:40 </td>
   <td style="text-align:left;"> $TSLA The announcement is Tesla community Texas! Tesla club gathering </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:22:21 </td>
   <td style="text-align:left;"> $TSLA doesn’t look good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:22:16 </td>
   <td style="text-align:left;"> $TSLA no good news on call ! Just listened to it lame </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:22:10 </td>
   <td style="text-align:left;"> $TSLA teslacon in austin- biggest rodeo of all times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:21:54 </td>
   <td style="text-align:left;"> $TSLA 😮 sell sell sell. Tomorrow dark red I guess. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:19:50 </td>
   <td style="text-align:left;"> $TSLA 990 🎯 remains .. not buying there though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:19:33 </td>
   <td style="text-align:left;"> $TSLA 1125 YOLO weekly calls beetchiiisss owww </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:18:47 </td>
   <td style="text-align:left;"> $TSLA call details please ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:16:40 </td>
   <td style="text-align:left;"> $TSLA moon boots 3:1 forward split ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:14:49 </td>
   <td style="text-align:left;"> $TSLA whats being said at the annoucment !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:14:43 </td>
   <td style="text-align:left;"> $TSLA do they not know there’s a problem with the callin app? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:12:53 </td>
   <td style="text-align:left;"> $BABA china indexes deep green again as US futures look shakey. Only a matter of time before the $TSLA degenerates start to chase gains and pile into Chinese tickets. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:12:42 </td>
   <td style="text-align:left;"> $TSLA what are they ssying is it good ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:12:01 </td>
   <td style="text-align:left;"> $TSLA futures 💩😭☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:11:47 </td>
   <td style="text-align:left;"> $TSLA nasdaq will go up 200-300 tomorrow…. Big money will jumping back into tech stocks! Not giving a PT for Tesla, but would love to be back above $1100! Also, still waiting on China delivery numbers for December 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:11:29 </td>
   <td style="text-align:left;"> $TSLA y’all best post what they’re saying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:08:36 </td>
   <td style="text-align:left;"> $TSLA Tera Texas ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:08:03 </td>
   <td style="text-align:left;"> $TSLA callin app not working? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:07:05 </td>
   <td style="text-align:left;"> $TSLA stupid ass Callin app requirement and wannabe users. Morons. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:06:54 </td>
   <td style="text-align:left;"> $TSLA bull patterns in larger bull patterns usually result in bullish price action. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:06:03 </td>
   <td style="text-align:left;"> $TSLA up or down tmw? Comment with explanation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:05:56 </td>
   <td style="text-align:left;"> $TSLA I smell a lot of fear... from the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:05:11 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-09 Technical Analysis Video: 
https://www.youtube.com/watch?v=zN0Oh_3bq8k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:04:42 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/q06WYYSUsdU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:03:56 </td>
   <td style="text-align:left;"> $TSLA - 950 February 4th puts 💵
Fed Powell, will crush tech this week as he and his suicidal suppositories run their pie holes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:03:27 </td>
   <td style="text-align:left;"> $TSLA  ... public service announcement for self serving TESLA jawboners  ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:00:41 </td>
   <td style="text-align:left;"> $TSLA 🤯🤯🤯🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:00:29 </td>
   <td style="text-align:left;"> $TSLA Shorts just adding fuel to the rocket lol thank you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 11:00:13 </td>
   <td style="text-align:left;"> $TSLA  
https://www.teslarati.com/tesla-giga-texas-model-y-production-start-date-tentative/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:59:57 </td>
   <td style="text-align:left;"> $TSLA the more this gets shorted the more it’s gonna go up eventually. 1200c are going to print this week fasho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:56:59 </td>
   <td style="text-align:left;"> How To Tell If A Stock Has Bottomed Out

$TSLA $MRNA $AAPL $FUBO $GME 

https://www.chartlearning.com/2021/12/how-to-tell-of-stock-has-bottomed-out.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:56:07 </td>
   <td style="text-align:left;"> $TSLA I have a feeling Giga Austin launches tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:52:55 </td>
   <td style="text-align:left;"> $TSLA yo are we hitting 1300 this week?🥺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:51:21 </td>
   <td style="text-align:left;"> $GME $BTC.X $ETH.X $TSLA $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:50:02 </td>
   <td style="text-align:left;"> $TSLA Trade idea
Entry break $1014 for PUTS to $950 area
Ill play the $1000 PUTS 1/14/22
Ill dabble calls over $1045
https://share.trendspider.com/chart/TSLA/11367835o49 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:48:44 </td>
   <td style="text-align:left;"> @SCALPINGSTOCKS4RICHES predicitons for $TSLA tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:48:35 </td>
   <td style="text-align:left;"> $amzn 3200
$googl $2700
$tsla $980
$msft $300
$aapl $170

Puts in case of possible pullback. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:46:30 </td>
   <td style="text-align:left;"> $TSLA I am sure many of us join in this call and post the update. that meeting is going to happen in 15 minutes (10 PM EST) Here is the link          https://www.callin.com/room/big-announcement-from-tesla-owners-austin-SKExhcfnrx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:46:17 </td>
   <td style="text-align:left;"> $TSLA So, news in 14 minutes apparently? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:45:29 </td>
   <td style="text-align:left;"> $TSLA What’s a good call option to buy long term? Something like 1,400 a year from now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:42:20 </td>
   <td style="text-align:left;"> $TSLA 
Serious question:

Why/how is an announcement from a few tesla owners so catalytic to its stock?

Ty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:42:07 </td>
   <td style="text-align:left;"> $amzn $3200
$googl $2700
$tsla $975
$aapl $169
$msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:41:28 </td>
   <td style="text-align:left;"> $TSLA it may go sideways tomorrow if not down. Good luck both bulls and bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:40:04 </td>
   <td style="text-align:left;"> $TSLA Goldman Sachs $1200 price point let’s goooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:39:04 </td>
   <td style="text-align:left;"> $BYDDY is the only Chinese EV company that can compete with $TSLA&amp;#39;s global limited amount with Chinese market sales in 2022. 2022 battery sales are likely to catch up with CATL&amp;#39;s 2021 battery sales. New cars are likely to be bursting, but production capacity is still not enough. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:37:39 </td>
   <td style="text-align:left;"> $TSLA I am joining in Tesla owners call which is happening at 10 PM PST. I will post that exciting news.... stay tune. https://www.callin.com/room/big-announcement-from-tesla-owners-austin-SKExhcfnrx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:36:28 </td>
   <td style="text-align:left;"> $TSLA LETS FUCKIN RIP BOYS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:36:27 </td>
   <td style="text-align:left;"> $TSLA no bears must mean this thing is about to open with a gap up and fly early 🚀🚀🚀🚀🚀🚀🚀 beautiful descending wedge showing very bullish movements!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:36:24 </td>
   <td style="text-align:left;"> $TSLA https://www.carscoops.com/2022/01/2023-tesla-model-2-everything-we-know-25000-compact/#Echobox=1641446420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:34:29 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-09 Daily Forecast Video: 
https://www.youtube.com/watch?v=7vdS9w9q2j8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:34:06 </td>
   <td style="text-align:left;"> $AAPL $NVDA $SPY $DKNG $TSLA Hey everyone! So I wanted to just update everyone that moving in this year I will start posting my plays (exact entries and exits) on this app called tradeexchange! I am going to be posting exact entries and exits on Madria Stock Swings. Essentially you will be able to get the exact entries and exits on there (basically me trading for you legally haha)! I am doing a New Year special of $5 a month. Shortly I will be increasing the price  :-)  
 
If you want to support me, please follow me on there. Any questions and such - feel free to message me on here!  
 
I hope to see you guys there! Thanks again for supporting me for the last year and a half as we continue to grow! Getting more and more clutch each time! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:33:47 </td>
   <td style="text-align:left;"> $NASDAQ best stock out there. Forget $TSLA, $AMC , and $DOGE.X   better stock than all those stonks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:33:03 </td>
   <td style="text-align:left;"> $TSLA  Chances of Nasdaq going to red is more than remaining green... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:29:44 </td>
   <td style="text-align:left;"> $TSLA  
Cathy wood exposed issues with GM and Ford. 
1. ICE car sales decline. 
2. Struggle to generate funds to ramp up EV production 
3. Credit ratings down 
4. Verge of bankruptcy. 
 
I am helpless if you don&amp;#39;t understand this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:26:03 </td>
   <td style="text-align:left;"> $TSLA Big put whale buyers! https://vm.tiktok.com/TTPdMxJwDw/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:23:49 </td>
   <td style="text-align:left;"> $TSLA You can thank me later 
https://www.callin.com/room/big-announcement-from-tesla-owners-austin-SKExhcfnrx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:23:07 </td>
   <td style="text-align:left;"> 👑Watchlist for Monday #5:
1) $TSLA (TL resistance reject)
2) $MRIN (Flagging)
3) $SPY (Ma50 key level)
4) $CELZ (Fixing for 4 break)
5) $HOUR (Dips ww for next run)

Gave multiple runners last week💰💰🧲 More coming… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:21:55 </td>
   <td style="text-align:left;"> $TSLA Encourage you to join in Tesla owners calls which is happening at 10 PM PST. They are going to talk about Giga Texas opening festival. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:20:41 </td>
   <td style="text-align:left;"> $TSLA Cathy puzzled about how GM EV sales decline in stunning way. But no one worry about that. Instead of they talk about Cathy selling 1 Million dollar worth of Tesla shares. When they buy Tesla stock at $200, obviously they take profit for various reasons. It is not a big deal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:16:14 </td>
   <td style="text-align:left;"> $TSLA  950$ coming week. CPI seems to be rising. Be prepared to sell now or hold for long time and long calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:16:04 </td>
   <td style="text-align:left;"> $TSLA buy it all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:11:11 </td>
   <td style="text-align:left;"> $TSLA oooo green one for a fail in the the open. Or a straight rip your tittties off to 110O </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:09:56 </td>
   <td style="text-align:left;"> $TSLA Futures looking good so far! Hope it keeps going 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:09:05 </td>
   <td style="text-align:left;"> $TSLA no way. The nasdaq isn&amp;#39;t red. Am I dreaming? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:07:29 </td>
   <td style="text-align:left;"> $TSLA futures are up let’s go 🦾🦾🦾🦾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:07:09 </td>
   <td style="text-align:left;"> $TSLA 1100 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:06:30 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-09 Largest Trades Data: 
https://www.youtube.com/watch?v=Gtq03JHi3IA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:04:54 </td>
   <td style="text-align:left;"> $TSLA cummon man! Going to bed with this push up. Inshallah gonna wake to flashing green futures and premarket. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:03:30 </td>
   <td style="text-align:left;"> $TSLA Up Up we go.. Bye bye small $ drama kids posting nonsense 

TSLA long! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:03:02 </td>
   <td style="text-align:left;"> $SLDP bagholders for days.   Ssb isn&amp;#39;t even in production yet, and has been crushed by $TSLA and $IVAN /Ses AI energy density and cost. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:02:37 </td>
   <td style="text-align:left;"> $TSLA https://www.youtube.com/watch?v=IQwc8pV90Mo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:01:58 </td>
   <td style="text-align:left;"> $TSLA bears are fucked. Futures are green bitches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:01:36 </td>
   <td style="text-align:left;"> $TSLA Tesla 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:01:00 </td>
   <td style="text-align:left;"> $TSLA is one of the better performing stocks in the Automobiles industry. https://www.chartmill.com/stock/analyzer/stock/TSLA?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:00:05 </td>
   <td style="text-align:left;"> $TSLA | Tesla  Inc. $TSLA Trading Advice (TSLA) https://tinyurl.com/y5uavu2q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 10:00:04 </td>
   <td style="text-align:left;"> $TSLA LOS BEARS FuTUs Are green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:59:07 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:58:11 </td>
   <td style="text-align:left;"> $TSLA Elon is a master pumper but he sold his shares, made bank and has no reason to piss off SEC. He&amp;#39;s gonna play it cool from here on out. Unless the stock drops to $600 Elon won&amp;#39;t pump. He&amp;#39;s got to much to worry about with SpaceX. If Star Ship doesn&amp;#39;t happen this year Star Link business model is bankrupt. They need increased pay load to orbit to make Star Link be cash flow positive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:57:48 </td>
   <td style="text-align:left;"> $TSLA ok let’s cut thru the bullshit. The bet is your net wort.  TSLA made its all time high last week on 300,000 unit run.  It will never go higher. Go ahead bears. Bet on that.  Tesla will be a 20,000 stock no split adjustment in 10 years. Anything other than this says you’re a trader thinking your bullshit assinine posts will actually affect your 5 share short position which causes you to to not be able to order Dominos tonight. Go away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:56:24 </td>
   <td style="text-align:left;"> $TSLA futs green! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:55:31 </td>
   <td style="text-align:left;"> $TSLA oh snap https://twitter.com/marketrebels/status/1480343285797425163?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:55:17 </td>
   <td style="text-align:left;"> $NASDAQ can u get $TSLA and $GME to pump for just a day please? 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:54:29 </td>
   <td style="text-align:left;"> $TSLA $1,200 next week MINIMUM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:53:56 </td>
   <td style="text-align:left;"> $SPY usually market sell off in unexpected time, the red candle need to close first before it&amp;#39;s ready for the 2nd one. Bullish only for 1-2 days. Not expecting any big movement. $TQQQ $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:53:29 </td>
   <td style="text-align:left;"> $TSLA come over to $BYND and help us squeeze to $300 you can invest it all back into Tesla and then some. Until 4680 cell ramps I don&amp;#39;t see anything that isn&amp;#39;t already figured into price. Tesla needs 4680 and 1000 km range before I see this stock pushing higher. BYND is where Tesla was 3 years ago before it sky rocketed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:52:52 </td>
   <td style="text-align:left;"> $TSLA don&amp;#39;t be a fool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:51:41 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE 🔥
COME JOIN US FOR 
📈 TRADE IDEAS 
🔫TRIGGERS 
⚔️PRICE TARGETS 
🔥SHERE TO GET IN AND OUT 
CLICK 👇https://us02web.zoom.us/webinar/register/WN_72riwIo3S42QgOGqjIvxbA  #spy $SPY  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:51:08 </td>
   <td style="text-align:left;"> $TSLA what if SPY gap up tomrr? Lets go tesla u can do it...new ATH before earning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:50:48 </td>
   <td style="text-align:left;"> $TSLA solid buy at $50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:50:30 </td>
   <td style="text-align:left;"> $MELI $TSLA $GOOG 

Will load these up Incase market falls tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:49:11 </td>
   <td style="text-align:left;"> $TSLA Down 4 days in a row. 1199.78 | 1149.59 | 1088.12 | 1064.7 | 1026.96 |  https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:48:54 </td>
   <td style="text-align:left;"> Ticker: $TSLA 
Buy: January 14, 2022 $1030.00 Calls 
Entry Price: $33.70 - $34.25 
Exit Price: $46.84 
Stop Loss: $29.66 
Potential ROI: 39% 
Estimated Hold Time: 50 Minutes 
Alert Courtesy Of: https://www.fastscalp.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:46:41 </td>
   <td style="text-align:left;"> $TSLA   The shorts here are betting stupid face ripping high risk.  Much easier tickers to short, like  HOOD (down 80% since the AUG 4th fake high)  btw, Cathy Wood is buying HOOD, lol (I  have no idea why)

Also, easy to short the vaccine stocks, just look at MRNA, and its crashing for obvious reasons </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:44:56 </td>
   <td style="text-align:left;"> $TSLA this stock will come down. Bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:44:24 </td>
   <td style="text-align:left;"> $TSLA  $1200 incoming 🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:44:00 </td>
   <td style="text-align:left;"> $TSLA Up or down day tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:43:57 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:43:48 </td>
   <td style="text-align:left;"> $TSLA haha $1200+ tomorrow 🙈🔥✅🤤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:43:41 </td>
   <td style="text-align:left;"> $TSLA US Tech 100 futures holding up well. Nearly green. Hopefully tech can lead Nasdaq to the promised land tomorrow. Dragged it down last week, this week the opposite? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:42:50 </td>
   <td style="text-align:left;"> $TSLA 

Bob Saget died today.  Booster shot? 💉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:38:09 </td>
   <td style="text-align:left;"> $TSLA Nice, lol🤪 ... Why nice is a bad word?  Well, we recently found out nice used to be a negative—derived from the Latin word nescius meaning “ignorant.” And, in the 14th century, it was used to refer to a stupid, ignorant, or foolish person. Ok, so you really didn&amp;#39;t want to be the nice guy back then. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:33:39 </td>
   <td style="text-align:left;"> Beautiful,  🐻❤ https://www.investing.com/indices/indices-futures  $tsla $spy $qqq $ccl $f and more ✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:33:38 </td>
   <td style="text-align:left;"> $amzn $3350
$googl $2850
$tsla $1100
$msft $325
$aapl $177

Bullish calls if no more pullback. Puts if so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-10 09:32:52 </td>
   <td style="text-align:left;"> $TSLA nice to see Elon saying GOOD things about his company lol </td>
  </tr>
</tbody>
</table></div>

---
