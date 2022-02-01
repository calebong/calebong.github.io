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



Last Updated: 2022-02-01 09:29:28 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 09:09:32 </td>
   <td style="text-align:left;"> Japanese Shares Climb on Tech Boost </td>
   <td style="text-align:left;"> The Nikkei 225 Index jumped 1.3% to around 27,360 while the broader Topix Index gained 1% to 1,915 on Tuesday as Japanese stocks tracked sharp overnight gains on Wall Street, with technology firms leading the charge. Notable gainers include Lasertec (3.3%), SoftBank (2.3%), Tokyo Electron (3.6%), Keyence (4.4%) and TDK Corp (12.4%). Japanese shippers, healthcare, manufacturing and consumer-related firms also participated in the rally. Meanwhile, Sony Group jumped 2.2% after its subsidiary, Sony Interactive Entertainment, announced Monday it has agreed to acquire privately held video game developer Bungie for $3.6 billion. The benchmark indices booked their worst month since March 2020 at the previous session’s close, as investors grappled throughout January with prospects of tighter monetary policy from the US Federal Reserve. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/myanmar/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-01 09:08:33 </td>
   <td style="text-align:left;"> Myanmar Manufacturing Shrinks for 17th Month </td>
   <td style="text-align:left;"> The IHS Markit Myanmar Manufacturing PMI fell to 48.5 in January 2022 from a 16-month high of 49.0 a month earlier. The latest reading was the 17th straight month of contraction in factory activity, amid uncertainties due to political situations and rising cases of the Omicron strain. Output shrank faster, and new orders dropped for the 17th month running, and at the quickest rate since October while buying levels were down for 23 consecutive months. Meantime,  power outages and raw material shortages led to a record rate of backlog accumulation, while severe delivery delays persisted. More positively, employment grew for the 2nd straight month as firms tried to boost output. On prices, input cost inflation accelerated on higher transport cost and the depreciation of the kyat against the dollar. Selling prices rose for the 14th consecutive month, as the rate of inflation was the steepest since last October and among the fastest in history. Finally, sentiment eased to a 3-month low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uranium </td>
   <td style="text-align:left;"> 2022-02-01 09:00:19 </td>
   <td style="text-align:left;"> Uranium Hits 4-week Low </td>
   <td style="text-align:left;"> Uranium decreased to a 4-week low of 44 USD/Lbs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 08:55:07 </td>
   <td style="text-align:left;"> Australian Shares Edge Up Ahead of RBA Decision </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index edged up 0.2% to around 6,987 on Tuesday as Australian technology firms tracked overnight gains on Wall Street peers, while investors cautiously awaited the Reserve Bank of Australia’s monetary policy decision. The RBA is widely expected to end its bond-buying program in its meeting today, but a rate hike in response to inflationary risks may be further out. Policymakers will have to contend with persistent inflation, which surged at its fastest annual pace since 2014 at 2.6% in the December quarter. Technology stocks led the market higher, with gains from Brainchip Holdings (9.8%), Xero Ltd (2%), Wisetech Global (1.3%), Aristocrat Leisure (1.2%) and Carsales.com (2.3%). Meanwhile, heavyweight miners declined including BHP Group (-2.5%), Rio Tinto (-2%) and Fortescue Metals (-1.1%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/balance-of-trade </td>
   <td style="text-align:left;"> 2022-02-01 08:42:51 </td>
   <td style="text-align:left;"> New Zealand Trade Balance Swings to Deficit </td>
   <td style="text-align:left;"> New Zealand posted a trade deficit of NZD 477 million in December 2021, compared with a surplus of NZD 74.95 million in the same month last year, as global demand continued to recover and commodity prices rose. Imports jumped 23 percent to NZ 6.5 billion, led by vehicles, parts, accessories, mechanical machinery &amp; equipment. Exports rose at a softer 13 percent to a record high of  NZD 6.1 billion, boosted by sales of dairy products. Considering the year 2021, the annual trade deficit was NZD 6.8 billion, compared with a surplus of NZD 3 billion in the same period of 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/jobs-to-applications-ratio </td>
   <td style="text-align:left;"> 2022-02-01 08:41:01 </td>
   <td style="text-align:left;"> Japan’s Job Availability Rises to 1.16 in December </td>
   <td style="text-align:left;"> The jobs-to-applications ratio in Japan increased to 1.16 in December 2021, meaning that there were 116 job openings for every 100 job seekers. The figure was up 0.01 point from the previous month’s reading and matched the consensus forecast. Meanwhile, job availability was still far from pre-pandemic levels, when the data posted at 1.55 two years ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-01 08:35:00 </td>
   <td style="text-align:left;"> Japan Manufacturing PMI Rises to Near 8-Year High </td>
   <td style="text-align:left;"> The au Jibun Bank Japan Manufacturing PMI was revised higher to 55.4 in January 2022 from a preliminary reading of 54.6, and after a final 54.3 a month earlier. This was the strongest growth in factory activity since February 2014, amid surging vaccinations and despite pressure from a persistent chip shortage. Output grew at the fastest rate since February 2014, while new order rose solidly, with the latter rising at the fastest pace for nine months. Also, both domestic demand and new export order growth accelerated. In addition, the rate of job creation accelerated to the fastest since April 2018, with backlogs of work accumulation increasing at the fastest pace in nine months. On the price front, input prices inflation rose amid higher raw material prices, while output cost inflation accelerated to the highest level since July 2008. Finally, business confidence strengthened, due to hopes that an end to the pandemic would induce a broad recovery in demand and supply chains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/unemployment-rate </td>
   <td style="text-align:left;"> 2022-02-01 08:33:10 </td>
   <td style="text-align:left;"> Japan Jobless Rate Falls to 2.7% in December </td>
   <td style="text-align:left;"> Japan’s unemployment rate decreased to 2.7% in December 2021, compared with 2.8% in November and better than market expectation of no change. The data reflected the continued recovery of the labor market before the onslaught of the fast-spreading omicron variant. Meanwhile, the jobs-to applications ratio posted at 1.16 in December, meaning that there were 116 job openings for every 100 job seekers. The figure was up 0.01 point from the previous month’s reading and matched the consensus forecast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/imports-yoy </td>
   <td style="text-align:left;"> 2022-02-01 08:19:00 </td>
   <td style="text-align:left;"> South Korea Imports Rise More than Expected </td>
   <td style="text-align:left;"> Imports to South Korea expanded 35.5 percent year-on-year to USD 60.21 billion in January 2022, above market expectations of 32.8 percent and after a 37.1 percent jump a month earlier, a preliminary release showed. This marked the twelfth straight month of double-digit growth in purchases, lifted by solid domestic demand ahead of the Lunar New Year and following an acceleration in COVID-19 vaccinations. In 2021, inbound shipments climbed 31.5 percent to a record US$615.1 billion, recovering from a 7.1 percent fall in 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60208463?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-01 08:16:05 </td>
   <td style="text-align:left;"> Wordle: New York Times buys popular word game </td>
   <td style="text-align:left;"> The New York Times has purchased the popular word game Wordle for an undisclosed seven-figure sum.                                                                                                                                                                                     , The free and simple game was created by software engineer Josh Wardle. It was released last October and now boasts millions of players.                                                                                                                                                , Mr Wardle said the game's success had been "a little overwhelming", and that he was "incredibly pleased" to announce the deal with the New York Times.                                                                                                                                 , The newspaper publisher said the game would initially remain free to play.                                                                                                                                                                                                             , The game challenges players to find a five-letter word in six guesses.                                                                                                                                                                                                                 , A new puzzle is published every day and players can post how quickly they solved the colourful grid on social media - but in a way that does not spoil the answer for those still playing - which is why, Mr Wardle said, it managed to capture the imagination of so many users.      , Mr Wardle announced the deal in a statement posted on Twitter, saying he had "long admired the NYT's approach to their games and the respect with which they treat their players".                                                                                                     , The New York Times said it bought the hit word game from its creator for a price "in the low seven figures".                                                                                                                                                                           , "The Times remains focused on becoming the essential subscription for every English-speaking person seeking to understand and engage with the world. New York Times Games are a key part of that strategy," a statement said.                                                          , "Our games already provide original, high-quality content and experiences every single day. Wordle will now play a part in that daily experience, giving millions more people around the world another reason to turn to The Times to meet their daily news and life needs," it added. , The game can be played in just a few minutes. Players begin by guessing any five-letter word.                                                                                                                                                                                          , Mr Wardle said he had "really got into" the New York Times crossword and spelling games during the pandemic.                                                                                                                                                                           , The New York Times Games, Mr Wardle said, played a "big part" in Wordle's origins, "so this step feels very natural".                                                                                                                                                                  , In January, Mr Wardle, who engineered games for social-media platform Reddit, told the BBC's Today programme he had come up with a prototype for the game in 2013 but his friends had not been keen on it.                                                                             , "Last year, my partner and I got really into crosswords and word games and I wanted a game for us to play each morning as part of our routine," he said.                                                                                                                               , He then shared it with his family on WhatsApp before opening it up to the public.                                                                                                                                                                                                      , Asked whether he planned to make money from it, he said: "I don't understand why something can't just be fun. I don't have to charge people money for this and ideally would like to keep it that way."                                                                                , Amanda Owen reveals what life is like living and working as a shepherdess                                                                                                                                                                                                              , Can they keep their progress hidden from their loved ones?                                                                                                                                                                                                                             , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/exports-yoy </td>
   <td style="text-align:left;"> 2022-02-01 08:14:00 </td>
   <td style="text-align:left;"> South Korea Export Growth Slows to 11-Month Low </td>
   <td style="text-align:left;"> Exports from South Korea grew by 15.2% yoy to USD 55.32 billion in January 2022, compared with market consensus of 15.5% and after a 18.3% gain a month earlier, a flash figure showed. This was the weakest rise in shipments since February 2021, as foreign demand moderated on the back of growing cases of the Omicron strain while supply chain issues persisted. In 2021, sales jumped 25.8% yoy to a record of USD 644.5 billion, the strongest growth since 2010 and reversing from a 5.5% fall in 2020 and a 10.4% drop in 2019. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-01/korea-export-gains-slow-as-demand-stabilizes-amid-omicron-wave?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-01 08:12:16 </td>
   <td style="text-align:left;"> Korea Export Gains Slow as Demand Stabilizes Amid Omicron Wave </td>
   <td style="text-align:left;"> A gantry crane loads a shipping container onto a cargo ship in Busan, South Korea.                                                                                                                , Hooyeon Kim                                                                                                                                                                                       ,  and Kyungji Cho                                                                                                                                                                                  , South Korea’s export growth slowed in January as a renewed outbreak of Covid-19 weighed on demand for manufactured goods and as gains stabilized from the large increases of the previous year.   , Exports rose 15.2% last month from a year earlier, the trade ministry said Tuesday, narrowing from an 18.3% gain in December. Economists had expected an increase of 15.8%. Imports were up 35.5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/balance-of-trade </td>
   <td style="text-align:left;"> 2022-02-01 08:09:53 </td>
   <td style="text-align:left;"> South Korea Trade Balance Swings to Deficit in January </td>
   <td style="text-align:left;"> South Korea posted a trade deficit of USD 4.89 billion in January 2022, shifting from a surplus of 3.76 billion in the same month a year earlier, a preliminary reading showed. This was the second straight month of trade gap, amid disruptions in global supply chains as many countries reintroduced COVID-19 restrictions following the rapid spread of the Omicron variant. Exports rose by 15.2 percent year-on-year to USD 55.32 billion, while imports expanded at a faster 35.5 percent to USD 60.21 billion. In 2021, the country posted a trade surplus of USD 29.49 billion, down sharply from USD 44.76 billion in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60208461?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-01 07:59:58 </td>
   <td style="text-align:left;"> Is this the summer that travel gets back to normal? </td>
   <td style="text-align:left;"> Airlines and tour operators are racing to boost staff numbers in the hope receding travel rules will trigger a summer holiday boom.                                                                                                                                                                                        , The UK will remove all travel testing requirements for fully-vaccinated people next Friday.                                                                                                                                                                                                                                , However, travel agents say destinations' Covid rules are still putting some Brits off, and many continue to book last minute.                                                                                                                                                                                              , There are also warnings of recruitment struggles as the industry ramps up.                                                                                                                                                                                                                                                 , On Monday, Ryanair's Michael O'Leary was the latest travel boss to predict a strong bounce-back, as people return to going on holiday.                                                                                                                                                                                     , He said that for summer 2022, airline expected to put on 115% of the capacity it had done in 2019.                                                                                                                                                                                                                         , Ryanair is recruiting and training 1,000 new pilots and 2,000 cabin crew.                                                                                                                                                                                                                                                  , However, he warned that much depended on Covid developments and said: "I think being cautious is the sensible way forward."                                                                                                                                                                                                , Some other travel businesses have also said they expect to put on a summer offering at least as big as before Covid.                                                                                                                                                                                                       , The airline and a tour operator Jet2 told the BBC earlier this month it was planning a larger summer holiday package this year than in 2019.                                                                                                                                                                               , It is selling more seats on an expanded fleet of planes in the expectation of high demand, and recruiting for more than 1,700 roles. These include roles in ground operations in the UK and overseas, cabin crew, and office staff.                                                                                        , The chief executive of Easyjet, Johan Lundgren, said pent-up demand should push summer capacity near to 2019 levels.                                                                                                                                                                                                       , Easyjet is recruiting 1500 seasonal cabin crew, and plans to recruit 1,000 pilots over the next five years.                                                                                                                                                                                                                , British Airways, which has cut about a quarter of its staff - 10,00 roles -  since the pandemic began, has recently been looking to hire thousands of cabin crew with a view to ramping up services. This includes inviting back some staff who previously left but expressed an interest in returning.                    , The carrier is looking for hundreds more for its new Gatwick short-haul subsidiary, which is due to launch at the end of March.                                                                                                                                                                                            , The UK's biggest tour operator TUI is also recruiting cabin crew for what it expects to be a busy summer.                                                                                                                                                                                                                  , Julia Lo Bue-Said, chief executive of the independent travel agent network Advantage Travel Partnership, said consumer confidence still needed to improve for a bumper summer to materialise.                                                                                                                              , She said many people were nervous about booking trips far in advance in case rules changed again, and complicated Covid regulations for entering popular destinations such as Spain were still putting families off.                                                                                                       , "A third of everything being sold [by our members] is currently classed as late departures, so travelling before the end of March. That's unusual," she continued.                                                                                                                                                         , "40% of what you'd normally be selling now would be in school holidays - at the moment it's more like 15%."                                                                                                                                                                                                                , She also believes a significant proportion of those travelling this summer will have postponed from last year - or even 2020.                                                                                                                                                                                              , However, Dame Irene Hays, chair of Hays Travel, said a lot of customers were booking last minute, but the summer season was "by far the number one".                                                                                                                                                                       , Since the second week of January, Dame Hays said Hays Travel has seen increases week on week, the biggest of which came after last Monday's announcement that the UK would scrap travel tests for the fully-vaccinated.                                                                                                    , Dame Irene said this was the same as the equivalent weekend in 2020, which she described as remarkable.                                                                                                                                                                                                                    , "The majority of short-haul holiday bookings are for Spain, Turkey and Greece, but there's also been a phenomenal increase in long-haul holidays for a longer duration," she added.                                                                                                                                        , "People are now ready for the holidays many are taking the opportunity to spend more on a holiday that's been worth waiting for."                                                                                                                                                                                          , ABTA, a trade association for travel agents and tour operators, said its members had reported an increase in activity following the relaxation of the UK's travel restrictions.                                                                                                                                            , However, the group feels it's still too early to say for certain what the summer will look like.                                                                                                                                                                                                                           , ABTA spokesperson Emma Brennan said that, like many other sectors, the travel industry was experiencing challenges with recruitment.                                                                                                                                                                                       , "The pandemic led to hundreds of thousands of jobs being lost, with many people making a move to other sectors. As a sector we now need to face the challenge of enticing them back and attracting new talent."                                                                                                            , Aviation is among the industries to have suffered most during the pandemic, shedding thousands of jobs.  The recruitment site Indeed.com said vacancies in the industry only returned to pre-pandemic levels in December 2021, before nose-diving again, as a result of Omicron. It said there were now signs of a rebound., James Reed, the Chairman of recruiter Reed.co.uk, said the scramble to hire more workers to cope with the British public's pent-up demand for travel had created a jobs boom. However, like other industries, he said the aviation sector faced labour shortages.                                                          , "The current labour market is a sellers' market, not a buyers' market, meaning jobseekers hold all the cards and it is down to the employers to make themselves as attractive as possible to new talent."                                                                                                                  , Ryanair's Michael O'Leary said he did not generally see staffing issues affecting the ramping up of operations, although "there are pockets".                                                                                                                                                                              , Other modes of travel have also expressed optimism about the coming months. Saga said last week cruise bookings were strong for 2022 and 2023.                                                                                                                                                                             , Amanda Owen reveals what life is like living and working as a shepherdess                                                                                                                                                                                                                                                  , Can they keep their progress hidden from their loved ones?                                                                                                                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60199024?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-01 07:57:58 </td>
   <td style="text-align:left;"> How people may get help to pay high energy bills </td>
   <td style="text-align:left;"> With rising energy costs set to push gas and electricity bills even higher, the government is looking at ways to soften the blow. But what route, if any, will it take?                                                                                                                                                    , It's my understanding that Chancellor Rishi Sunak is considering a multi-billion pound intervention of a temporary and targeted nature, aimed at mitigating the coming record rises for the most vulnerable households.                                                                                                    , It would be an "energy price-based" intervention, not a tax or benefit-based one. So that rules out the cut to VAT on energy bills called for by the Labour party.                                                                                                                                                         , A temporary intervention can be justified on the basis that most of the factors pushing up energy prices are freakish one-offs - from the mismatches in supply that followed the lifting of pandemic restrictions, to the geopolitical tensions with Russia.                                                               , The open question is just how targeted this intervention will be.                                                                                                                                                                                                                                                          , On its current trajectory, the energy price cap, which limits what providers can charge consumers, is likely to rise to close to £2,000 a year for dual fuel customers. That will treble the number of households under "fuel stress", in other words spending more than a tenth of their income on energy, to 6.3 million., One way to help this group would be to widen the Warm Homes Discount (WHD) scheme, which sees £140 automatically taken off the annual energy bills of anyone receiving pension credit. It is currently funded by increasing everyone else's bills.                                                                         , There is talk of doubling the WHD and then extending it to working-age households receiving Universal Credit. If the taxpayer met that £2-3bn cost for a year, then the policy could have an impact, but it would require big changes to the WHD system.                                                                   , Another option for the government would be to look at green levies.                                                                                                                                                                                                                                                        , Everyone's energy bills contain about £200 of levies annually to support green energy and social support schemes. If the taxpayer stepped in for a year to fund these commitments, it could turn the heat down on those rising energy prices, but this policy is much harder to target.                                    , Yet another option would be some sort of smoothing mechanism to support energy companies with loans, known as a "Cost Deferral Mechanism".                                                                                                                                                                                 , It could operate with or without help from the Treasury or the Bank of England, but British Gas-owner Centrica is not a fan, having described it as a "bailout". It is unclear, however, why it does not think asking the taxpayer to shoulder renewable and social levy obligations is not also a bailout.                , The Treasury is likely to announce any decision on support before the regulator Ofgem unveils the new price cap next Monday, so the chancellor and the Prime Minister will have to come to an agreement imminently.                                                                                                        , Amanda Owen reveals what life is like living and working as a shepherdess                                                                                                                                                                                                                                                  , Can they keep their progress hidden from their loved ones?                                                                                                                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-31/trucker-protest-strands-beef-shipments-at-u-s-canada-border?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-01 07:40:15 </td>
   <td style="text-align:left;"> Trucker Protest Strands Beef Shipments at U.S.-Canada Border </td>
   <td style="text-align:left;"> Jen Skerritt                                                                                                                                                                                                                                                                                                             , Protesters who are rallying against vaccine mandates are holding up shipments of Canadian beef to the U.S.                                                                                                                                                                                                               , More than 150 loads of beef are stuck at the border at Coutts, Alberta, the Canadian Meat Council said Monday. A blockade of vehicles has been slowing traffic at the crossing between Alberta and Montana since the weekend in a protest against rules that require truckers crossing the border to be fully vaccinated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/31/white-house-ukraine-mess-pkg-lead-mattingly-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-01 07:37:57 </td>
   <td style="text-align:left;"> 'The provocation's from Russia': US has tough words on Ukraine crisis at UN Security Council meeting - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-31/australia-s-wealth-fund-trims-stocks-warns-on-inflation-uptick?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-01 07:30:00 </td>
   <td style="text-align:left;"> Australia’s Wealth Fund Trims Stocks, Warns on Inflation Uptick </td>
   <td style="text-align:left;"> Matthew Burgess                                                                                                                                                                                                                                     , Australia’s sovereign wealth fund has trimmed its stock exposure in anticipation the removal of stimulus by central banks will cause more volatility and warned rising inflation could mean returns are tougher to generate.                        , Stock holdings fell to 31% from 33% in three months to Dec. 31 as it increased cash, according to a statement Tuesday. The fund returned 19.1% in 2021, its best calendar year performance, lifting assets to about A$204 billion ($144.2 billion).  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/31/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-02-01 07:02:42 </td>
   <td style="text-align:left;"> Stock futures dip after S&amp;P 500 wraps up worst month since March 2020 </td>
   <td style="text-align:left;"> , Stock futures declined in overnight trading Monday after Wall Street wrapped up a tumultuous month with steep losses as investors grappled with the Federal Reserve's policy shift.                                                                                                                                                                                                                             , Futures on the Dow Jones Industrial Average dipped 80 points. S&amp;P 500 futures and Nasdaq 100 futures both traded 0.3% lower.                                                                                                                                                                                                                                                                                    , While stocks pulled off a tech-driven rally Monday, major averages still suffered a brutal month marked by wild price swings. The S&amp;P 500 and the Nasdaq Composite posted their worst months since March 2020 at the depth of the pandemic, down 5.3% and 8.9%, respectively. It was also the S&amp;P 500's biggest January decline since 2009. The blue-chip Dow declined 3.3% for the month.                      , January's sell-off came as the central bank signaled its readiness to tighten monetary policy, including raising interest rates multiple times this year, to tame inflation that has shot up to the highest level in nearly four decades. Investors flocked out of growth-oriented technology shares, which are particularly sensitive to rising rates.                                                         , Volatility exploded during the month as investors deciphered the Fed's messaging on its policy pivot. At one point last week, the S&amp;P 500 dipped into correction territory on an intraday basis, briefly down 10% from its record high. The recent comeback pushed the large-cap benchmark 6.3% below its peak. Meanwhile, the tech-heavy Nasdaq is still in a correction, last down 12% from its all-time high., Still, many Wall Street strategists are reminding investors that corrections are normal in bull markets. Since 1950, there have been 33 S&amp;P 500 corrections of 10% or more since 1950, and the median episode has lasted about five months, according to Goldman Sachs.                                                                                                                                         , "The latest decline is a normal market correction that does not signal a recession or the end of this bull market," said Chris Haverland, global equity strategist at Wells Fargo. "We continue to believe that economic growth and corporate earnings will be solid this year, and that the Fed will not be overly aggressive in dialing back monetary policy."                                                , Fundstrat's Tom Lee says get ready for a 'violent rally' in February                                                                                                                                                                                                                                                                                                                                            , Stocks look ready for a February rally, but chart strategists warn it could be short-lived                                                                                                                                                                                                                                                                                                                      , The sell-off is nearly over and history says these stocks bounce back first: Trivariate Research                                                                                                                                                                                                                                                                                                                , Goldman Sachs says these 5 stocks could rally over 80% this year                                                                                                                                                                                                                                                                                                                                                , This week a flurry of key companies are expected to report earnings, which could set the tone for the month of February. Exxon Mobil is slated to post numbers before the bell on Tuesday, while Alphabet, General Motors, Starbucks, AMD and PayPal will report after the bell.                                                                                                                                , So far, of the 172 companies in the S&amp;P 500 that have reported earnings to date, 78.5% topped analysts' estimates, according to Refinitiv.                                                                                                                                                                                                                                                                      , "We still anticipate solid, albeit more modest, gains for markets this year, alongside more normal pullbacks, especially given the transition in monetary policy," Keith Lerner, chief market strategist at Truist, said in a note.                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                          , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                          , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                              , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-31/australia-home-prices-edge-up-in-further-sign-of-cooling-boom?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-01 07:00:00 </td>
   <td style="text-align:left;"> Australia Home Prices Edge Up, Further Sign of Cooling Boom </td>
   <td style="text-align:left;"> Homes in the Bella Vista suburb of Sydney, Australia.                                                                                                                                                                              , Nabila Ahmed                                                                                                                                                                                                                       ,  and Harry Brumpton                                                                                                                                                                                                                , Australian home prices rose slightly during the first month of this year amid a historically sluggish mid-summer period, as overall growth continues to show the booming market is cooling.                                        , House prices were up 1.1% in January, compared with 1% a month earlier, as the most-populous cities, Sydney and Melbourne, were outpaced by smaller rivals and regional markets, according to a report from CoreLogic Inc. Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/ethanol </td>
   <td style="text-align:left;"> 2022-02-01 06:47:25 </td>
   <td style="text-align:left;"> Ethanol Hits 17-week Low </td>
   <td style="text-align:left;"> Ethanol decreased to a 17-week low of 2.115 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/31/business/economy/fed-pandemic-policy.html </td>
   <td style="text-align:left;"> 2022-02-01 06:36:00 </td>
   <td style="text-align:left;"> Fed Officials Make It Clear: This Time Is Different - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Central bankers on Monday emphasized that conditions are better than they were the last time they backed off their efforts to prop up the U.S. economy.                                                                                                                                                                                                                                                                                                                                                                     , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Federal Reserve officials are preparing to pull back their economic help as inflation remains stubbornly high and the labor market swiftly heals, and they are signaling clearly that the last business cycle is a poor template for what comes next.                                                                                                                                                                                                                                                                       , During the economic expansion that stretched from the global financial crisis to the start of the pandemic, the Fed acted very gradually — it slowly dialed back bond buying meant to help the economy, then only ploddingly shrank its balance sheet of asset holdings. Central bankers increased borrowing costs sporadically between 2015 and the end of 2018, raising them at every other meeting at the very fastest.                                                                                                  , But inflation was muted, the labor market was slowly crawling out of an abyss, and business conditions needed the Fed’s support. This time is different, a series of Fed presidents emphasized on Monday — suggesting that the pullback in policy support is likely to be quicker and more decisive.                                                                                                                                                                                                                        , Four of the central bank’s 12 regional presidents spoke on Monday, and all suggested that the Fed could soon begin to cool off the economy. Central bankers are widely expected to make a series of interest rate increases starting in March, and could soon thereafter begin to fairly rapidly shrink their balance sheet holdings. The pace of policy retreat is still up for debate and officials reiterated that it will hinge on incoming data — but several also noted that economic conditions are unusually strong., “The economy is far stronger than it has been, during any of my time in this role, and certainly, during any of the recoveries that we’ve been trying to navigate our policy through in recent memory,” Raphael Bostic, president of the Federal Reserve Bank of Atlanta, said in an interview with Yahoo Finance. Any risks “that our policies are going to lead to a contraction in the economy, I think they’re relatively far off.”                                                                                     , While it took the Fed a long time to begin shrinking its balance sheet last time, the central bank will probably move more promptly in 2022, Esther George, president of the Federal Reserve Bank of Kansas City, suggested during a speech.                                                                                                                                                                                                                                                                                , “With inflation running at close to a 40-year high, considerable momentum in demand growth, and abundant signs and reports of labor market tightness, the current very accommodative stance of monetary policy is out of sync with the economic outlook,” said Ms. George, who votes on monetary policy this year.                                                                                                                                                                                                          , Tricky questions lie ahead about how big the balance sheet should be, she noted. The Fed’s holdings have swollen to nearly $9 trillion, more than twice its size before the pandemic.                                                                                                                                                                                                                                                                                                                                       , Ms. George estimated that the Fed’s big bond holdings were weighing down longer-term interest rates by roughly 1.5 percentage points — nearly cutting the interest rate on 10-year government debt in half. While shrinking the balance sheet risks roiling markets, she warned that if the Fed remains a big presence in the Treasury market, it could distort financial conditions and imperil the central bank’s prized independence from elected government.                                                            , “While it might be tempting to err on the side of caution, the potential costs associated with an excessively large balance sheet should not be ignored,” she said. She suggested that shrinking the balance sheet could allow policymakers to raise rates, which are currently set near-zero, by less.                                                                                                                                                                                                                     , Mary C. Daly, the president of the Federal Reserve Bank of San Francisco, also argued for an active — albeit still gradual — path toward removing policy help.                                                                                                                                                                                                                                                                                                                                                              , The Fed is not behind the curve, she said on a Reuters webcast, but it needs to react to the reality that the labor market appears at least temporarily short on workers and inflation is running hot. Prices picked up by 5.8 percent in the year through December, nearly three times the 2 percent the Fed aims for on average and over time.                                                                                                                                                                            , “We’re not trying to combat some vicious wage-price spiral,” Ms. Daly said. Still, she said she could support a rate increase as soon as March, and hinted that four rate increases could be reasonable, a path that would slow things down while “not pulling away the punch bowl completely and causing disruptions.”                                                                                                                                                                                                     , What is inflation? Inflation is a loss of purchasing power over time, meaning your dollar will not go as far tomorrow as it did today. It is typically expressed as the annual change in prices for everyday goods and services such as food, furniture, apparel, transportation and toys.                                                                                                                                                                                                                                  , What causes inflation? It can be the result of rising consumer demand. But inflation can also rise and fall based on developments that have little to do with economic conditions, such as limited oil production and supply chain problems.                                                                                                                                                                                                                                                                                , Where is inflation headed? Officials say they do not yet see evidence that rapid inflation is turning into a permanent feature of the economic landscape, even as prices rise very quickly. There are plenty of reasons to believe that the inflationary burst will fade, but some concerning signs suggest it may last.                                                                                                                                                                                                    , Is inflation bad? It depends on the circumstances. Fast price increases spell trouble, but moderate price gains can lead to higher wages and job growth.                                                                                                                                                                                                                                                                                                                                                                    , How does inflation affect the poor? Inflation can be especially hard to shoulder for poor households because they spend a bigger chunk of their budgets on necessities like food, housing and gas.                                                                                                                                                                                                                                                                                                                          , Can inflation affect the stock market? Rapid inflation typically spells trouble for stocks. Financial assets in general have historically fared badly during inflation booms, while tangible assets like houses have held their value better.                                                                                                                                                                                                                                                                               , Even so, she said it would be “misinformation” to suggest that officials are coalescing around a clear path forward — the Fed will have to figure out how rapidly rates will increase as it learns more about the economy.                                                                                                                                                                                                                                                                                                  , Wall Street economists increasingly expect a rapid pace for rate increases this year: Goldman Sachs and J.P. Morgan both expect five rate moves in 2022, and some Fed watchers have suggested as many as seven are possible. Markets are pricing in a small but meaningful chance that the Fed is going to raise rates by a half-point in March, instead of a more typical quarter-percentage-point increase.                                                                                                               , Officials have been careful to emphasize that they do not know what is going to happen next with policy because the economy is so uncertain — rents are rising and supply chains remain messy, which could keep inflation elevated, but government support programs are waning, which could weigh down demand.                                                                                                                                                                                                              , “We’re not set on any particular trajectory,” Mr. Bostic said.                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Mr. Bostic had suggested in an interview with The Financial Times over the weekend that a half-point rate increase could be appropriate this year, a rapid approach to withdrawing policy help that was never used in the last expansion.                                                                                                                                                                                                                                                                                   , He said on Yahoo on Monday that he does not prefer a supersize increase in March at this point, though he has “increasingly” seen that meeting as the right time for the Fed to begin raising rates. Like Ms. George, Mr. Bostic also emphasized that this time was different when it comes to the Fed’s balance sheet.                                                                                                                                                                                                     , “The economy is stronger,” he said. “And we have that previous experience that gives us some guidance as to how markets are likely to respond as that balance sheet shrinks. So I think we can be more robust in terms of how we do that.”                                                                                                                                                                                                                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-31/asian-stocks-set-for-tailwind-from-rally-in-u-s-markets-wrap </td>
   <td style="text-align:left;"> 2022-02-01 06:35:46 </td>
   <td style="text-align:left;"> Asian Stocks Climb After Tech-Led Rally in U.S.: Markets Wrap </td>
   <td style="text-align:left;"> Sunil Jagtiani                                                                                                                                                                                                                                                 , Asian stocks on Tuesday harnessed the tailwind from a technology-led rally in the U.S. that was spurred by dip buyers betting this year’s equity rout is going to ebb.                                                                                         , Shares rose in Japan and Australia, which are among the few markets open due to Lunar New Year holiday closures. U.S. futures edged down following the best two-day jump in the S&amp;P 500 and tech-heavy Nasdaq 100 since April and November 2020, respectively.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/industrial-sentiment </td>
   <td style="text-align:left;"> 2022-02-01 06:15:45 </td>
   <td style="text-align:left;"> Australia Markit PMI Revised Lower </td>
   <td style="text-align:left;"> The IHS Markit Australia Manufacturing PMI was revised lower to 55.1 in January of 2022 from a preliminary of 55.3, the lowest reading in five months,  as the COVID-19 Omicron wave weighed on operations. New orders continued to grow but output contracted. Stronger demand nevertheless kept manufacturers hiring and increasing their buying activity. Meanwhile lead times worsened though price pressures eased. Overall sentiment remained positive amongst firms. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-01 06:09:00 </td>
   <td style="text-align:left;"> Australia Factory Activity Falls During Summer Holiday </td>
   <td style="text-align:left;"> The Australian Industry Group Australian Performance of Manufacturing Index fell by 6.4 points to 48.4 points over the summer holiday period (December 2021 and January 2022) from 54.8 in November, pointing to a contraction in the factory sector, amid lower demand over a normally quiet period. Production, new orders, sales and stocks remained mildly positive following stronger results in November. The very large food &amp; beverage sector fell into contraction after a temporary rebound in November while manufacturers in the building materials and machinery &amp; equipment sectors posted strong results. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-01 06:00:13 </td>
   <td style="text-align:left;"> Gold Loses Almost 2% in January </td>
   <td style="text-align:left;"> Gold prices edged higher to around the $1780 an ounce level on Monday but booked a nearly 1.7% fall for the January month as bets of a faster Fed tigthening sent the US dollar higher. The US central bank indicated last week that it would likely hike interest rates in March and begin reducing its balance sheet soon after to combat inflation, with markets pricing in five quarter-point rate hikes for this year. Although gold is considered a hedge against inflation, interest rate hikes would raise the opportunity cost of holding non-yielding bullion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 05:50:42 </td>
   <td style="text-align:left;"> Brazilian Shares Rebound </td>
   <td style="text-align:left;"> The Ibovespa rebounded to end 0.2% higher at 112144 on Monday, tracking positive cues from its American peers, and led by gains in airlines and technology shares. On the month, the main stock index of Brazil jumped 7%. Traders now await the central bank monetary policy decision on Wednesday, anticipating a 150bps hike in the key Selic rate and earnings from Santander Brasil and Cielo. Meanwhile, Brazil's central bank financial markets' weekly survey for 2022 showed inflation forecasts were revised higher for a third consecutive week to 5.38% from 5.15%, while growth projections were revised slightly higher to 0.30% from 0.29%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-31/herky-jerky-stocks-lashed-by-gamma-hedging-in-thinning-liquidity?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-01 05:39:57 </td>
   <td style="text-align:left;"> Stock Market Chaos Revved Up by Options Dealers Rushing to Hedge </td>
   <td style="text-align:left;"> Lu Wang                                                                                                                                                                                                                                                                                                            ,  and Cristin Flanagan                                                                                                                                                                                                                                                                                              , Two days of big stock rallies have investors wondering: Is the new year’s selloff over? Maybe, but a couple researchers are pointing to below-the-surface dynamics that may be exaggerating moves and leaving investors exposed to more volatility.                                                                , At Goldman Sachs Group Inc., strategists including Rocky Fishman found that the market’s ability to absorb orders worsened rapidly during last week’s turmoil. Liquidity evaporated so much that a measure based on the bid-ask spread of S&amp;P 500 futures widened to levels not seen since the 2020 pandemic crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/31/business/media/new-york-times-wordle.html </td>
   <td style="text-align:left;"> 2022-02-01 05:30:58 </td>
   <td style="text-align:left;"> The New York Times Buys Wordle - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The word game, released in October, has millions of daily users.                                                                                                                                                                                                                                                                                                                                                                                                                                                      , By Marc Tracy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The sudden hit Wordle, in which once a day players get six chances to guess a five-letter word, has been acquired by The New York Times Company.                                                                                                                                                                                                                                                                                                                                                                      , The purchase, announced by The Times on Monday, reflects the growing importance of games, like crosswords and Spelling Bee, in the company’s quest to increase digital subscriptions to 10 million by 2025.                                                                                                                                                                                                                                                                                                           , Wordle was acquired from its creator, Josh Wardle, a software engineer in Brooklyn, for a price “in the low seven figures,” The Times said. The company said the game would initially remain free to new and existing players.                                                                                                                                                                                                                                                                                        , Wordle — the name is a cheeky pun on its creator’s name — has had a striking rise. It first appeared on a no-frills, ad-free website in October, and had 90 users on Nov. 1. That number grew to 300,000 by the middle of this month, and now millions play the game daily, according to the Times announcement.                                                                                                                                                                                                      , A feature enables users to share their performance, with rows of five bricks indicating how close they were to guessing the correct word. For the uninitiated: A green brick indicates that the letter is correct and in the exact location; a yellow brick indicates that the letter appears in the word but in a different place; and a gray or black brick indicates that the letter does not appear anywhere in the word. These analog brick layouts have been endlessly memed and have driven millions of tweets., “The Times remains focused on becoming the essential subscription for every English-speaking person seeking to understand and engage with the world,” a company statement said. “New York Times Games are a key part of that strategy.”                                                                                                                                                                                                                                                                               , Since The Times put up a paywall in 2011, its business strategy has revolved around persuading readers and users, the overwhelming majority of whom get Times content digitally, to buy subscriptions. The traditional newspaper business model is centered on advertising.                                                                                                                                                                                                                                           , The Times sells subscriptions to its print newspaper and core digital news app. For lower prices, it also offers subscriptions to a games app (Games), a recipe app (Cooking) and, as of last year, Wirecutter, a product-recommendation site The Times bought in 2016. This month, The Times spent $550 million to buy the sports news website The Athletic, hailing the 1.2 million subscribers the site brings with it.                                                                                            , The business strategy has been vindicated to the tune of millions of new subscribers. In November, The Times said in an earnings report that it had nearly 8.4 million. (Its next earning report is scheduled to be released Wednesday.) In December, The Times reported that Games and Cooking each had more than one million subscribers.                                                                                                                                                                           , The Times’s games — along with the crossword and Spelling Bee, they include Letter Boxed, Tiles and Vertex — were played more than 500 million times last year, the company said.                                                                                                                                                                                                                                                                                                                                     , Mr. Wardle told a Times reporter this month that he had started Wordle after he and his partner “got really into” The Times’s crosswords and Spelling Bee games during the pandemic.                                                                                                                                                                                                                                                                                                                                  , “New York Times Games play a big part in its origins,” Mr. Wardle said in the company’s statement, “and so this step feels very natural to me.”                                                                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 05:30:17 </td>
   <td style="text-align:left;"> Canadian Shares End Higher on Monday </td>
   <td style="text-align:left;"> The S&amp;P/TSX closed 1.7% higher at 21098 on Monday, tracking strong gains on Wall Street, and led by gains in tech and healthcare shares. Considering January as a whole, the index is set to shed 1.9%, after climbing 2.7% in the previous month. On the corporate front, shares of Ballard Power Systems jumped 13% and were among the top performers, after falling to over 52-week lows in the previous week. Considering full January,  the benchmark stock index in Canada went down 0.6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/cirrus-logic-stock-jumps-10/story.aspx?guid={07E0F03C-1DAE-4861-94B4-627B229700BA}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-01 05:30:12 </td>
   <td style="text-align:left;"> Cirrus Logic stock jumps 10% after quarterly results top views - MarketWatch </td>
   <td style="text-align:left;"> Shares of Cirrus Logic Inc. 
        CRUS,
        +4.91%
       jumped more than 10% in the extended session Monday after the chip supplier reported fiscal third-quarter earnings and sales well above Wall Street expectations. Cirrus Logic said it earned $128 million, or $2.16 a share, in the quarter, compared with $114 million, or $1.91 a share, in the year-ago period. Adjusted for one-time items, the company earned $2.54 a share. Sales rose to $548.3 million from $294 million a year ago. Analysts polled by FactSet expected Cirrus Logic to report adjusted earnings of $2.14 a share on sales of $510 million. The company guided for fiscal fourth-quarter revenue between $400 million and $440 million, and GAAP gross margin between 51% and 53% in the period. Cirrus Logic shares ended the regular trading day up 4.9%. , Netflix hurt by price hike and programming slump, while rivals offer Winter Olympics and a stronger slate of new shows                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/nxpi:us </td>
   <td style="text-align:left;"> 2022-02-01 05:28:13 </td>
   <td style="text-align:left;"> NXP Semiconductors earnings below expectations at 2.24 USD </td>
   <td style="text-align:left;"> NXP Semiconductors (NXPI) released earnings per share at 2.24 USD, compared to market expectations of 3.01 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/white-house-omicron-spike-january-jobs </td>
   <td style="text-align:left;"> 2022-02-01 05:09:54 </td>
   <td style="text-align:left;"> White House warns omicron spike could skew January jobs report </td>
   <td style="text-align:left;"> FOX Business’ Madison Alworth discusses red states like Texas, Arizona, Idaho, and Utah recovering all jobs lost during the COVID-19 pandemic.                                                                                                                                                                                                                                                                                          , The Biden administration is laying the groundwork for disappointing job growth in January, warning that an omicron-fueled surge in COVID-19 cases earlier this month likely distorted hiring as the virus sidelined millions of workers.                                                                                                                                                                                                , White House press secretary Jen Psaki told reporters on Monday that because the Labor Department report only includes data from the first half of a month, it could have a disproportionate impact on the headline jobs figure – including the possibility of negative growth. The economy has not shed jobs since December 2020, when employers cut 306,000 jobs before the vaccine was available.                                     , FED SIGNALS INTEREST RATE HIKE COULD COME 'SOON' AS INFLATION RAGES                                                                                                                                                                                                                                                                                                                                                                     , "Because omicron was so highly transmissible, nearly 9 million people called out sick in early January when the jobs data was being collected," Psaki told reporters. "The week the survey was taken was at the height of the omicron spike… As a result, the jobs report may show job losses, in large part because workers were out sick from omicron at a point when it was peaking."                                                , White House press secretary Jennifer Psaki speaks during the daily briefing on Jan. 21, 2022. (SAUL LOEB/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                           , The "survey reference week" this month was taken between Jan. 9 to Jan. 15 – precisely when COVID-19 cases peaked, with the highest seven-day average count coming on Jan. 15, according to the CDC. Hourly employees who were sick and had to stay home that week without paid sick leave will not be counted as employed, even if they have not been laid off.                                                                        , A Census Survey shows that an estimated 8.75 million Americans said they were not working in early January, either because they were infected with COVID-19 or taking care of someone else who had contracted the virus. That's a huge jump from December, when 2.96 million people reported they could not work due to the coronavirus.                                                                                                , Economists surveyed by Refinitiv expect the U.S. economy to have added 153,000 jobs in January, which would still be the weakest since December 2020. But there is a possibility the number will be far worse.                                                                                                                                                                                                                          , The effects of the fast-spreading omicron variant on daily life continue to be felt. (AP Photo/Marta Lavandier / AP Newsroom)                                                                                                                                                                                                                                                                                                           , "If you think about omicron in early January, and the impact it was having in terms of the number of people who were out sick, we do expect there to be some real variation in the data," National Economic Council Director Brian Deese told CNBC on Sunday.                                                                                                                                                                           , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                             , For weeks, there has been growing unease on Capitol Hill over a stunning rise in cases driven by the highly transmissible omicron variant.                                                                                                                                                                                                                                                                                              , While it's still unclear what the fast-spreading variant will ultimately mean for the health of the economy, its effects on daily life have already been felt. Thousands of flights have been canceled, Broadway shows are shuttering their doors and a growing number of schools have postponed reopenings. The White House has maintained that it has the resources needed to respond to any disruptions caused by the omicron spread. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/31/feds-barkin-says-businesses-would-welcome-higher-interest-rates.html </td>
   <td style="text-align:left;"> 2022-02-01 05:06:05 </td>
   <td style="text-align:left;"> Federal Reserve's Barkin says businesses would welcome higher interest rates </td>
   <td style="text-align:left;"> , The U.S. economy is ready for interest rate increases to control rampant inflation, Richmond Federal Reserve President Thomas Barkin said Monday.                                                                                                                                                                                                                           , With the Fed poised to start hiking rates in March and beyond, Barkin told CNBC in a live interview that tighter monetary policy is appropriate. However, he didn't commit to how aggressive the central bank might be.                                                                                                                                                     , "I'd like the Fed to get better positioned. I think we've got a good part of the year to get there," he said on "Closing Bell." "I think how fast we go just depends on how the economy develops."                                                                                                                                                                          , Financial markets, however, are expecting the Fed to move quickly.                                                                                                                                                                                                                                                                                                          , Current futures pricing indicates a strong possibility of five 0.25% increases in the benchmark short-term borrowing rate. There's even about a one-in-three chance that the Fed could hike six times, according to CME calculations through its FedWatch Tool. Bank of America economists said Friday they forecast seven increases this year.                             , Those expectations come with inflation running at its highest level in nearly 40 years. The Fed uses interest rates to raise the cost of money and slow the pace of the economy, which had its fastest single-year growth spurt since 1984 a year ago.                                                                                                                      , Barkin said it's been his experience that at least for those in the business community, the rate increases will be welcomed.                                                                                                                                                                                                                                                , "As I talk to participants in the economy, what I hear is they actually want us to do something now about inflation. They'd like us to get back to at least a normal interest-rate posture and not be simulating more demand on top of normal levels," he said. "So, I don't hear much resistance to that."                                                                 , He spoke the same day as two of his fellow regional presidents, Mary Daly of San Francisco and Esther George of Kansas City, also voiced support for tighter policy. Part of that tightening is interest rates. The other part deals with the Fed's monthly bond purchases, which are set to end in March, and the holdings of those bonds, which have eclipsed $8 trillion., Following their meeting last week, Fed officials said they expect to run down the assets on their balance sheet aggressively.                                                                                                                                                                                                                                               , In a speech she delivered earlier in the day to The Economic Club of Indiana, George said running off the balance sheet more quickly might allow the Fed to enact fewer rate hikes.                                                                                                                                                                                         , "What we do on the balance sheet will likely affect the path of policy rates and vice versa," George said. "For example, more aggressive action on the balance sheet could allow for a shallower path for the policy rate."                                                                                                                                                 , Daly said during a Reuters forum that the Fed is "not behind the curve at all" when it comes to fighting inflation. However, she also said it's time to start easing the throttle on the most accommodative monetary policy in the central bank's history.                                                                                                                  , "If the economy progresses like I see it progressing, then it is clear that it can stand on its own two feet, that we do not need to be providing the same level of extraordinary … accommodation that we provided during the pandemic and have provided for the last two years," she said.                                                                                 , None of the Fed officials would commit to a schedule, though many on Wall Street think each of the Fed's seven remaining meetings this year will be "live," or subject to policy moves.                                                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-31/omicron-dashes-china-s-hopes-of-winter-olympics-boosting-economy?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-01 05:00:00 </td>
   <td style="text-align:left;"> Omicron Dashes China’s Hopes of Winter Olympics Boosting Economy </td>
   <td style="text-align:left;"> Sign up for the New Economy Daily newsletter, follow us @economics and subscribe to our podcast.                                                                           , China’s Winter Olympics may be more of a drag on Beijing’s regional economy than a boost, as virus flare-ups and pollution curbs weigh on consumer and industrial activity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 04:30:00 </td>
   <td style="text-align:left;"> US Stocks Rally to End January but Book Big Monthly Loss </td>
   <td style="text-align:left;"> US stocks closed sharply higher on the last trading day of January, led by gains in consumer discretionary, communication services, and tech shares. The Dow Jones ended 406 points higher at 35131, the S&amp;P 500 rallied 1.9% to 4515 and the Nasdaq jumped 3.4% to 14240. On the corporate front, Tesla stocks rallied almost 11% after Credit Suisse upgraded the company to “outperform". In the month, however, the S&amp;P 500 lost almost 6% and the Nasdaq nearly 4%, their worst month since March 2020 while the Dow Jones fell 3.3% as the Fed moved to a more hawkish monetary policy with investors increasingly betting on five rate hikes in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/unemployment-rate </td>
   <td style="text-align:left;"> 2022-02-01 04:23:49 </td>
   <td style="text-align:left;"> Colombia Jobless Rate at 11 percent in December </td>
   <td style="text-align:left;"> The unemployment rate in Colombia fell to 11 percent in December of 2021 from 13.4 percent in the corresponding month of 2020. The number of unemployed persons dropped by 634 thousand to 2.670, while employed persons rose by 185 thousand to 21.593 million. Meanwhile, the employment rate declined to 53.2 and the activity rate went down to 59.8 percent from 61.6 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/exxonmobil-corporate-headquarters-houston-restructuring </td>
   <td style="text-align:left;"> 2022-02-01 04:09:20 </td>
   <td style="text-align:left;"> ExxonMobil moving corporate HQ to Houston </td>
   <td style="text-align:left;"> Chevron CEO Mike Wirth discusses the statistics surrounding Chevron and the oil industry’s strong growth since the pandemic on ‘The Claman Countdown.’                                                                                                                                                                                                                                     , ExxonMobil is slated to move its corporate headquarters about 250 miles from Irving, Texas to its campus north of Houston in mid-2023.                                                                                                                                                                                                                                                     , About 250 people currently work at the Irving location, including CEO Darren Woods and the company's management committee.                                                                                                                                                                                                                                                                 ,   (REUTERS/Brendan McDermid/File Photo / Reuters Photos)                                                                                                                                                                                                                                                                                                                                   , "We greatly value our long history in Irving and appreciate the strong ties we have developed in the North Texas community," Woods said in a statement. "Closer collaboration and the new streamlined business model will enable the company to grow shareholder value and position ExxonMobil for success through the energy transition."                                                 , GAS PRICES CLIMB FOR FIFTH STRAIGHT WEEK AS OIL SURGES                                                                                                                                                                                                                                                                                                                                     , The move is part of an organizational restructuring that will put the company on track to exceed $6 billion in structural cost savings by 2023.                                                                                                                                                                                                                                            ,   (AP Photo/Reed Saxon, File / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                , Effective April 1, the company will establish three business lines: upstream, which produces oil and gas, product solutions, which makes fuel and chemicals, and low carbon solutions. Its technology operations will also be combined under a single organization known as ExxonMobil Technology and Engineering.                                                                         , Former ExxonMobil Chemical Company president Karen McKee will lead the production solutions business, while former ExxonMobil Upstream Oil and Gas Company president Liam Mallon will lead the upstream business. ExxonMobil Technology and Engineering Company will be led by former ExxonMobil Upstream Integrated Solutions and Upstream Business Development president Linda DuCharme. ,  CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                   , An ExxonMobil spokesperson told FOX Business that the company is offering a relocation package to eligible employees to help enable their move to Houston and retain as many employees as possible.                                                                                                                                                                                        , "Relocation is not expected to result in significant job reductions," the spokesperson added.                                                                                                                                                                                                                                                                                              , The announcement comes ahead of ExxonMobil's fourth-quarter earnings results, which will be released on Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/31/business/sony-bungie-destiny-halo.html </td>
   <td style="text-align:left;"> 2022-02-01 04:07:08 </td>
   <td style="text-align:left;"> Sony to Buy Bungie, Creator of Destiny and Halo Games, for $3.6 Billion - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                   , The deal follows two other major acquisitions in the game market by Microsoft and Take-Two Interactive.                                                                                                                                                                                                                                                         , By Cade Metz                                                                                                                                                                                                                                                                                                                                                    , Sony Interactive Entertainment said on Monday that it had agreed to acquire the video game maker Bungie in a deal valued at $3.6 billion, as the game market further consolidates around some of its biggest companies.                                                                                                                                         , This month, Microsoft announced a $69 billion acquisition of Activision Blizzard, and Take Two Interactive reached an agreement on an $11 billion purchase of Zynga.                                                                                                                                                                                            , Sony Interactive Entertainment, maker of the PlayStation game console and a major game developer in its own right, said Bungie, the original developer of the multiplayer shooter games Destiny and Halo, would operate independently and have free rein to publish games for other consoles and platforms. But the move could help Sony reach new game players., “This is an important step in our strategy to expand the reach of PlayStation to a much wider audience,” Jim Ryan, Sony Interactive Entertainment’s president and chief executive, said in a statement.                                                                                                                                                         , Sony and Bungie did not immediately respond to requests for comment.                                                                                                                                                                                                                                                                                            , Microsoft acquired Bungie in 2000, and its signature title, Halo, helped turn Microsoft’s Xbox console into a major game platform. But the developer split from Microsoft in 2007 and stopped making Halo three years later. Since 2011, Halo has been developed by 343 Industries, a company owned by Microsoft.                                               , Now, Bungie will be acquired by Microsoft’s biggest rival in the game console market: Sony. Bungie’s most popular current game is Destiny 2, which is available on multiple platforms, including the Xbox and Sony’s PlayStation.                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-31/u-s-treasury-lifts-quarterly-borrowing-estimate-to-729-billion?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-01 04:00:00 </td>
   <td style="text-align:left;"> U.S. Treasury Lifts Quarterly Borrowing Estimate to $729 Billion </td>
   <td style="text-align:left;"> Liz McCormick                                                                                                                                                                                                                     , The U.S. Treasury boosted its estimate of federal borrowing needs for the three months through March after entering the quarter with a cash pile that was run down by congressional delays in lifting the government’s debt limit., The Treasury’s new projections, released in Washington Monday, incorporate last month’s move by lawmakers to increase the debt ceiling by an amount intended to last until early next year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-up-over/story.aspx?guid={F298849A-61C2-4B64-94F2-971FA6F5287C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-01 03:59:35 </td>
   <td style="text-align:left;"> U.S. oil futures up over 17% for the month - MarketWatch </td>
   <td style="text-align:left;"> This corrects the reference date for the strongest monthly percentage rise.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Oil futures climbed Monday, with U.S. prices up over 17% for the month -- the largest such rise since February 2021, according to Dow Jones Market Data. Traders remained focused on the potential threat to oil supplies from Russia, which on Monday said the United States was "provoking an escalation" of the situation with Ukraine by falsely charging Moscow with preparing to invade Ukraine, according to a report from The Washington Post. West Texas Intermediate crude for March delivery 
        CLH22,
        +0.35%
       rose $1.33, or 1.5%, to settle at $88.15 a barrel on the New York Mercantile Exchange. For the month, the front-month contract gained 17.2%. Prices also marked their highest settlement since early October 2014., Advanced Micro Devices Inc. earnings will serve as an important indicator on whether the semiconductor outlook is truly weak for the March-ending quarter or whether it's just weak for certain companies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-31/s-p-500-rallies-for-second-day-with-tech-stocks-driving-surge?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-01 03:40:58 </td>
   <td style="text-align:left;"> S&amp;P 500 Rallies for Second Day, With Tech Stocks Driving Surge </td>
   <td style="text-align:left;"> Matt Turner                                                                                                                                                                                                                                                                                                                                                                                                                              , The S&amp;P 500 is trying to cap a month of mostly losses with a victory as tech stocks lead the market higher for a second straight session, despite lingering uncertainty on the number and swiftness of Federal Reserve rate hikes this year.                                                                                                                                                                                             , The benchmark gauge was up 1.4% as of 2:10 p.m. in New York, but is still on track for its worst start to a year since 2009. All of the 11 major industry groups rose, with the consumer discretionary and consumer staples sectors leading gains. The tech-heavy Nasdaq 100 Index rose 2.5%, extending its two-day rally to 5.8%, the largest since November 2020. Elsewhere, the blue-chip Dow Jones Industrial Average increased 0.8%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/31/business/texas-florida-vaccine-mandate.html </td>
   <td style="text-align:left;"> 2022-02-01 03:33:59 </td>
   <td style="text-align:left;"> How Businesses in Texas and Florida Wrestle With States’ Vaccine Backlash - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , With the Biden administration’s attempt to impose a national standard blocked, companies must navigate a thicket of local rules as they try to return employees to the workplace.                                                                                                                                                                                                                                                                                                                                                                                                                                                             , By Emma Goldberg and Lauren Hirsch                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Emma Goldberg and Lauren Hirsch write frequently about how the pandemic has affected the workplace.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The Biden administration’s attempt to impose a sweeping vaccine rule for private employers last year was met with a wave of state laws limiting company vaccine mandates. Texas and Florida were on the vanguard of that backlash.                                                                                                                                                                                                                                                                                                                                                                                                            , Now that the Supreme Court has blocked the federal vaccine standard, which would have compelled large companies nationwide to mandate Covid-19 vaccines or weekly testing for a total of 80 million workers, businesses in Texas and Florida have been left to navigate complex local laws and muddled public health guidelines as they weigh how to protect their workers.                                                                                                                                                                                                                                                                   , As the coronavirus increasingly makes clear that it is here to stay, businesses are feeling the pressure to reopen and re-establish some semblance of normalcy. That means figuring out what their safety precautions should look like, especially if their operations span states with drastically different pandemic rules.                                                                                                                                                                                                                                                                                                                 , The Walt Disney Company suspended its national vaccine mandate for Florida employees because of state regulations, even as it is working to keep the requirement in place for workers in its home state of California. A restaurant owner in Austin said he requested vaccines of his customers, but couldn’t check their proof of vaccination under state law. Hewlett Packard Enterprise has set up a crisis management team that meets twice weekly to evaluate Covid conditions and local laws in the 17 states where it operates, including Texas, and to assess the company’s ability to reopen offices and mandate vaccines or testing., “Of course it’s challenging to keep track of shifting guidance at the national level or the local level,” said Adam Bauer, a spokesman for Hewlett Packard Enterprise. “Nothing about this pandemic has been uncomplicated.”                                                                                                                                                                                                                                                                                                                                                                                                                  , In the fall, with the economy picking up, a number of large national companies instituted vaccine mandates in the hopes of keeping workers healthy and on the job. A November poll of 543 companies from Willis Towers Watson found that 57 percent required or planned to require vaccines, though one-third said they would do so only if the Biden administration’s rule took effect. The Omicron surge mobilized more companies to consider such precautions.                                                                                                                                                                             , In Texas and Florida, state officials maintained they wanted to protect the freedoms of workers by limiting the types of safety protocols employers could put in place. Many employers, though, have found that the regulations can be a barrier to keeping their workers safe and businesses open.                                                                                                                                                                                                                                                                                                                                           , “It’s a bizarro world in Texas,” said Austin Kaplan, an employment lawyer who has consulted with many companies in Austin struggling with Texas’ vaccine rules. “In other states, you have to show proof of vaccination to dine. In Texas, you’re not allowed to ask.”                                                                                                                                                                                                                                                                                                                                                                        , In Florida, where 65 percent of people are fully vaccinated, Gov. Ron DeSantis signed into law restrictions on vaccine mandates in November, arguing that “nobody should lose their job due to heavy-handed Covid mandates.”                                                                                                                                                                                                                                                                                                                                                                                                                  , Florida requires businesses to allow for an extensive list of exemptions that workers can cite to avoid a vaccine mandate, effectively making workplace requirements moot. Workers can avoid a company vaccine mandate if they are pregnant, say they are trying to get pregnant or use employer-provided personal protective equipment. Large companies that run afoul of Florida’s standard can be penalized as much as $50,000 per violation.                                                                                                                                                                                              , In Texas, where 59 percent of people are fully vaccinated, Gov. Greg Abbott issued an executive order in October declaring that no employer could compel vaccination from someone who conscientiously objects to it. This exemption effectively guarantees that no workers can be subject to broad vaccine mandates, according to labor lawyers.                                                                                                                                                                                                                                                                                              , The Texas Legislature passed a law in May saying institutions subject to any kind of government licensing — meaning all restaurants and bars — cannot require their customers to show proof of vaccination. Businesses that ask for proof of vaccination can face stiff penalties, including the loss of a liquor license.                                                                                                                                                                                                                                                                                                                    , “Making a vaccine passport illegal seems purely political,” said Adam Orman, who with Fiore Tedesco owns L’Oca d’Oro, a restaurant in Austin with 25 workers. He is also a co-founder of the hospitality association Good Work Austin. “It doesn’t give freedom to business, which is what most of the behavior from the state toward businesses during the pandemic has been.”                                                                                                                                                                                                                                                               , Mr. Orman requests that his customers be vaccinated for indoor dining — and will let them know when they call for reservations — but he stops short of asking for proof because of state law. Mr. Orman instructed members of his staff last spring that they had to be fully vaccinated, with booster shots, unless they had a medical or religious exemption. He said he was frustrated that he couldn’t promise them that the people they served would be held to the same standard.                                                                                                                                                       , “Our employees are working too hard to keep themselves safe and healthy so they can show up to work to serve people,” he said. “To have that one piece where we can’t require guests who are coming into the restaurant, to the safe place we’ve created, to be vaccinated — that hurts.”                                                                                                                                                                                                                                                                                                                                                     , The Texas and Florida laws have forced national companies that operate in the states to carve out exceptions to corporate policies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Disney paused its vaccine mandate for employees of its Florida theme park in November, after the state made broad vaccine rules illegal. More than 95 percent of cast members at the park are vaccinated, a spokeswoman said. The Related Companies, a real estate firm that mandated vaccines for all of its employees in April, is no longer requiring them of its staff in Florida or any states where broad vaccine mandates are prohibited.                                                                                                                                                                                              , Other businesses have pushed back on Florida’s red tape. Norwegian Cruise Line Holdings sued Florida’s surgeon general in July, accusing the state of preventing it from “safely and soundly” resuming trips by barring it from requiring customers to be vaccinated. A judge ruled in the company’s favor a month later.                                                                                                                                                                                                                                                                                                                     , Omicron in retreat. Though the U.S. is still facing overwhelmed hospitals and more than 2,500 deaths a day, new cases are falling rapidly across the country, and some governors are saying it’s time to try to restore a sense of normalcy and learn to live with the virus.                                                                                                                                                                                                                                                                                                                                                                 , Around the world. A report on British Prime Minister Boris Johnson's lockdown parties found leadership failures and “excessive” drinking at Downing Street, but did not directly implicate him in wrongdoing. In Italy, with its high vaccination rate, a new social schism revolves around the risk takers and the risk averse.                                                                                                                                                                                                                                                                                                              , Covid shots. New C.D.C. data on Covid outcomes among people who have received booster shots shows their effectiveness. The F.D.A. granted full approval to Moderna’s vaccine, the second-most widely used in the U.S. and the second to receive full regulatory approval.                                                                                                                                                                                                                                                                                                                                                                     , Spotify. After Neil Young and Joni Mitchell removed their music from Spotify to protest the platform’s support of Joe Rogan, the star podcaster who has been accused of spreading Covid misinformation, the company said it would not take on the position of “content censor.”                                                                                                                                                                                                                                                                                                                                                               , Staying safe. Worried about spreading Covid? Keep yourself and others safe by following some basic guidance on when to test, which mask to pick and how to use at-home virus tests. Here is what to do if you test positive for the coronavirus, and if you lose your vaccination card.                                                                                                                                                                                                                                                                                                                                                       , Meanwhile, some companies run by managers who support the vaccines but question the idea of making them a condition of employment have welcomed Texas’ and Florida’s policies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                , “I understand that every state has to make their policies of what their leadership feels like is right for the state, and it’s my job as a C.E.O. to adhere to it,” said Harold Westervelt, chief executive of the Texas-based tech company FileTrail, which has about 70 employees.                                                                                                                                                                                                                                                                                                                                                          , It is a tumultuous moment in the world of work. With Covid cases soaring, companies are postponing return-to-office plans or putting in place new safety policies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , We looked at five questions workers are struggling with →                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , How can you stay safe if you’re starting to go back into the office?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , It starts with a high-quality mask because the Omicron variant is so infectious. Don’t hesitate to be explicit about your safety preferences with colleagues: Let them know, for example, if you want to stay away from others when eating. Companies can do a lot too, like investing in ventilation and setting up work environments that allow for social distancing.                                                                                                                                                                                                                                                                      , If you have been going into the office, what should you do if you feel sick?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , If you start to experience symptoms — a scratchy throat or congestion — you should go get a test. Lab tests, known as P.C.R.s, will offer a more accurate assessment of whether you are infected, while rapid antigen tests give a good sense of whether you are contagious.                                                                                                                                                                                                                                                                                                                                                                  , If you have Covid, how long before you can go back to work?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The Centers for Disease Control and Prevention recommends you isolate for at least five days. After that, if you are asymptomatic or your symptoms are improving, you can mingle with others if you wear a mask for the next five days. Many public health experts say it is best to wait for at least one negative antigen test before leaving isolation.                                                                                                                                                                                                                                                                                    , If you’re still stuck working from home, how can you get your best work done?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Create an office-like setup at home. A desk or comfortable chair can help you stay focused and productive. We like to add other touches, like candles and snacks. Don’t be shy if you are craving guidance on your work -- reach out to your manager and colleagues. And be compassionate with yourself when circumstances are outside your control.                                                                                                                                                                                                                                                                                          , How can you connect with your colleagues while working remotely?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Don’t write off Zoom or Google Hangouts to stay connected. Schedule virtual coffee chats with colleagues you want to get to know. Or try an old-fashioned phone call if you’re Zoomed out, like us! Send notes to co-workers who have done work that you appreciate. And when it’s safe, meet up with colleagues outside. We’re both big fans of a walk in the park.                                                                                                                                                                                                                                                                          , Read more about return-to-office plans upended by Omicron.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Some large national employers are maintaining their vaccine mandates in Texas and Florida by applying them only to people entering their offices. Whether that approach keeps companies out of the cross hairs of state officials could be tested when more workers are required to return to the office.                                                                                                                                                                                                                                                                                                                                     , For example, the money management company Vanguard, which requires its U.S. workers to be vaccinated to enter its offices, will extend that same requirement to the Dallas office it plans to open this year. The private equity firm Blackstone, which is requiring vaccines and boosters for U.S. workers to enter its offices, is maintaining that policy in Florida.                                                                                                                                                                                                                                                                      , The oil giant BP, whose 3,500 Houston office employees are working remotely, is requiring employees to be vaccinated or tested twice weekly and wear masks once they start going back in person.                                                                                                                                                                                                                                                                                                                                                                                                                                              , Checkr, a human resources technology company that is opening a new office in Orlando, Fla., this spring, created a task force that monitors state regulations to set Covid safety policies for each of the company’s five U.S. locations and 845 employees. Employees in the San Francisco office have to wear masks, while those in the Denver office do not — though in both locations everyone going into the office has to be vaccinated.                                                                                                                                                                                                 , The company says it has yet to make a decision about vaccination or masking policies for the Florida office, citing uncertainty about the state’s regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , “We’ve had to be really flexible, recognizing the virus is shifting and our understanding of what’s a safe work environment has changed,” said Linda Shaffer, Checkr’s chief people and operations officer. “Do I wish it wasn’t that way? Of course. Everyone wishes that.”                                                                                                                                                                                                                                                                                                                                                                  , Brooks Barnes contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/31/investing/george-soros-china-real-estate/index.html </td>
   <td style="text-align:left;"> 2022-02-01 03:13:35 </td>
   <td style="text-align:left;"> George Soros warns China is facing an economic crisis - CNN </td>
   <td style="text-align:left;"> London (CNN Business)China is facing an economic crisis after a real estate boom ended with a bang last year, according to investor George Soros.                                                                                                                                                                                                                                          , The billionaire said in a speech at Stanford University's Hoover Institution Monday that President Xi Jinping may not be able to restore confidence in the troubled industry, which has been hit by a series of defaults by developers and falling prices for land and apartments.                                                                                                         , China's real estate boom was based on an "unsustainable" model that benefited local governments and encouraged people to invest the bulk of their savings in property, Soros said.                                                                                                                                                                                                         , Government policies designed to curb the boom made it difficult for indebted real estate behemoth Evergrande to pay its debts, he added.                                                                                                                                                                                                                                                   , The developer is reeling under more than $300 billion of total liabilities, including about $19 billion in offshore bonds held by international asset managers and private banks on behalf of their clients. Evergrande has been scrambling for months to raise cash to repay lenders.                                                                                                     , Government officials have been sent into the company to oversee a restructuring, but there's little clarity about what comes next. Evergrande has appealed for more time, but some lenders appear unwilling to wait. On Sunday, the company said that receivers had been appointed over a plot of land in Hong Kong, which it pledged as collateral against a $520 million loan last year. , "It remains to be seen how the authorities will handle the crisis," Soros said, during a panel discussion about developments in China and how the United States should respond. "They may have postponed dealing with it for too long, because people's confidence has now been shaken."                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                            , Soros has in recent years emerged as a prominent critic of Xi and China's ruling Communist Party. The legendary investor and chair of the Open Society Foundations said in September that asset manager BlackRock was making a "tragic mistake" by doing more business in China. He has criticized Beijing over its surveillance policies and a crackdown on private business.             ,                                                                                                                                                                                                                                                                                                                                                                                            , The Chinese president now faces risks from the property market, according to Soros, who was speaking just days before the start of the Winter Olympics in Beijing.                                                                                                                                                                                                                         , Falling prices will "turn many of those who invested the bulk of their savings in real estate against Xi Jinping," Soros said, adding that the current situation "doesn't look promising."                                                                                                                                                                                                 , "Xi Jinping has many tools available to reestablish confidence — the question is whether he will use them properly," said Soros.                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                            , Analysts have been long been concerned that Evergrande's collapse could trigger wider risks for China's property market, hurting homeowners and the broader financial system. Real estate and related industries account for as much as 30% of the country's GDP.                                                                                                                          , China's economy expanded 8.1% last year, far exceeding the government's own targets. But weakening growth in the closing months of 2021 suggests the real estate crisis, renewed Covid outbreaks and Beijing's strict approach to controlling the virus are taking a toll.                                                                                                                 , The International Monetary Fund expects economic growth to slow dramatically to 4.8% in 2022.                                                                                                                                                                                                                                                                                              , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/novavax-asks-fda-authorize-its/story.aspx?guid={D35282EB-4B64-436A-ABDA-026F994AECA0}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-01 03:06:02 </td>
   <td style="text-align:left;"> Novavax asks the FDA to authorize its COVID-19 vaccine candidate - MarketWatch </td>
   <td style="text-align:left;"> Shares of Novavax Inc. 
        NVAX,
        +13.00%
       rallied 10.0% in trading on Monday after the company said it filed for authorization of its experimental COVID-19 shot in the U.S. Novavax's COVID-19 vaccine candidate is protein-based, meaning it's a different type of vaccine than the mRNA shots developed by BioNTech SE 
        BNTX,
        +6.08%
      /Pfizer Inc. 
        PFE,
        -3.02%
       and Moderna Inc. 
        MRNA,
        +6.18%
       or the Johnson &amp; Johnson 
        JNJ,
        +0.29%
       viral vector vaccine. Novavax said it is seeking authorization for its two-dose vaccine in adults, based on two clinical studies. One Phase 3 trial assessing the vaccine in about 15,000 adults in the U.K. reported an 89.7% efficacy rate against infection with the virus, according to research published in the New England Journal of Medicine in September. A second trial that enrolled about 30,000 adults in the U.S. and Mexico found that shots produced an efficacy rate of 92.6% against any variants of concern or interest. That study was also published in the New England Journal of Medicine, in December. Some of the vaccine's side effects include headache, pain at the injection site, and fatigue. The vaccine requires two shots, spaced 21 days apart. Novavax's stock has tumbled 59.2% over the past year, while the broader S&amp;P 500 
        SPX,
        +1.89%
       is up 17.0%., After a bruising week, Spotify Technology SA on Sunday said it would add content advisories to certain podcasts and improve transparency about its misinformation policy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-climb-session-fall/story.aspx?guid={5F846FF6-D99C-4896-AFB4-8503C3316010}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-01 03:05:52 </td>
   <td style="text-align:left;"> Gold futures climb for the session, fall for the month - MarketWatch </td>
   <td style="text-align:left;"> Gold prices settled higher on Monday, but posted a loss for the month pressured, in part, by a rise in Treasury yields over the past few months, said Michael Hewson, chief market analyst at CMC Markets UK. Still, prices rebounded after falling to a roughly six-week low at the end of last week. April gold 
        GCJ22,
        +0.13%
       rose $9.80, or nearly 0.6%, to settle at $1,796.40 an ounce. Prices based on the most-active contracts ended the month down 1.8%, according to Dow Jones Market Data., Here's what you need to know.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ges-stock-rallies-after-aviation/story.aspx?guid={E7905DA2-B014-4DC8-A883-064BF7E90887}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-01 03:04:03 </td>
   <td style="text-align:left;"> GE's stock rallies after Aviation unit announces $6.8 billion order from Qatar Airways - MarketWatch </td>
   <td style="text-align:left;"> Shares of General Electric Co. 
        GE,
        +2.58%
       rallied 1.9% in afternoon trading Monday, after the industrial conglomerate said it received an order valued at more than $6.8 billion from Qatar Airways for its GE9X engines. GE Aviation said the order was part of Qatar Airways' global launch order of 50 of Boeing Co.'s 
        BA,
        +5.07%
       777-8 Freighters. "We are proud to continue building our relationship with Qatar Airways and play a significant role in their growth with this order of Boeing 777-8 Freighter and 777 Freighter aircraft," said GE Aviation Chief Executive John Slattery. GE's stock has lost 10.5% over the past three months, while Boeing's stock has shed 4.0% and the Dow Jones Industrial Average 
        DJIA,
        +1.17%
       has slipped 2.4%. , Netflix hurt by price hike and programming slump, while rivals offer Winter Olympics and a stronger slate of new shows                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/illinois-pizzeria-owner-begs-for-help-as-future-of-workforce-hangs-in-the-balance </td>
   <td style="text-align:left;"> 2022-02-01 03:01:24 </td>
   <td style="text-align:left;"> Illinois pizzeria owner begs for help as future of workforce hangs in the balance </td>
   <td style="text-align:left;"> Joanie's Pizzeria owner Michael Okun argues people are 'still getting government funded money' and even though he is doing everything he can to incentivize workers, he is still having trouble recruiting employees.                                                                                                                                                                            , An Illinois pizzeria owner said on Monday that he is begging for help as the future of the workforce hangs in the balance while business owners deal with labor shortages and government funding comes to an end.                                                                                                                                                                                , Joanie's Pizzeria owner Michael Okun argued on Monday that people are "still getting government funded money" and noted that even though he is doing everything he can to incentivize workers, he is still having trouble recruiting employees.                                                                                                                                                  , Okun told FOX Business’ Grady Trimble that he has been shuffling workers around all his different businesses to stay open, stressing that the situation is "so tough right now."                                                                                                                                                                                                                 , "What we’ve done is cross-trained,"Okun told Trimble during a live interview on "Varney &amp; Co." on Monday.                                                                                                                                                                                                                                                                                        , DICKEY'S BBQ GETS CREATIVE TO SOLVE WORKER SHORTAGE ISSUE                                                                                                                                                                                                                                                                                                                                        , "My head chef over at Chatter Box [restaurant] comes over here and helps us and we have the bartenders moving back and forth."                                                                                                                                                                                                                                                                   , Earlier this month it was revealed that the latest JOLTS report on job openings sat at 10.6 million by the end of November after hitting a record 11.03 million the month before. The data comes before the highly contagious omicron variant of the coronavirus began disrupting the economy. Data for December job openings will be released on Tuesday.                                       , It was also revealed earlier this month that a record number of Americans quit their jobs in November 2021, underscoring how persistent turmoil in the labor market has made it difficult for employers to fill open positions.                                                                                                                                                                  , Dickey's Barbecue Restaurants CEO Laura Rea Dickey describes the innovative approach her company is taking to alleviate the situation.                                                                                                                                                                                                                                                           , The Labor Department said earlier this month that an unprecedented 4.5 million Americans, or about 3% of the workforce, quit their jobs November, matching the high from September. That's up from 4.2 million in October and tops the previous record of 4.4 million in September. The pre-pandemic level was about 3.6 million.                                                                , Resignations in November were concentrated – one of the industries hit hardest by the pandemic – accommodation and food services, as well as health care and social assistance, transportation, housing and utilities. A majority of people quit for a new job.                                                                                                                                  , Okun said he has been offering workers more money, a 401k and health insurance and he is still "not getting anybody."                                                                                                                                                                                                                                                                            , He stressed that he believes money from the government during the pandemic has "absolutely" contributed to the problem.                                                                                                                                                                                                                                                                          , "I think they are still getting government-funded money," Okun stressed, referencing the fact that many people had more to spend because of the stimulus checks issued during the pandemic.                                                                                                                                                                                                      , As more people got vaccinated this past spring and demand for dining and shopping rebounded, businesses were faced with the challenge of trying to meet the soaring demand. Also contributing to the worker shortage, many of the hourly employees found new jobs as they redefined their priorities.                                                                                            , The issued forced employers, like Okun, to look for ways to make their jobs seem more attractive while some were also forced to cut back on hours of operation.                                                                                                                                                                                                                                  , Former McDonald's USA CEO Ed Rensi explains the 'confluence of events' leading to the labor shortages as data revealed a record number of Americans quit their jobs in November 2021.                                                                                                                                                                                                            , According to a September survey from the National Restaurant Association, the vast majority of restaurant owners polled said their restaurants reduced hours of operation on days it was open for business from June through August. The survey also found that nearly half of those polled said they closed their restaurant on the days that it would normally be open during that time frame. , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                      , When asked what he thinks is in store for 2022, Okun said he hopes that the situation will improve now that government funding is expiring.                                                                                                                                                                                                                                                      , "We do see a little blip where some people are starting to come out and want to work," he said, adding that, still, he recently had to beg a friend who had retired to help him with his businesses amid the current labor shortage and now that friend is managing the pizzeria.                                                                                                                , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                          , FOX Business’ Megan Henney and The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/tv/2022/01/31/amanpour-rory-stewart-boris-johnson-partygate-sue-gray-report.cnn </td>
   <td style="text-align:left;"> 2022-02-01 02:55:54 </td>
   <td style="text-align:left;"> Fmr. UK Conservative MP: 'The fish rots from its head' - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/chicago-pmi </td>
   <td style="text-align:left;"> 2022-02-01 02:55:22 </td>
   <td style="text-align:left;"> Chicago Business Barometer at 3-Month High </td>
   <td style="text-align:left;"> The Chicago PMI in the United States increased to 65.20 points in January from 64.30 points in December of 2021. It is the highest reading in 3 months, beating forecasts of 61.7. Order backlogs, employment and supplier deliveries all increased and prices slowed while production and orders fell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/greece/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-02-01 02:54:38 </td>
   <td style="text-align:left;"> Greek Retail Trade Growth Picks Up in November </td>
   <td style="text-align:left;"> Greece’s retail trade growth jumped 14.7 percent year-on-year in November of 2021 from a downwardly revised 7.9 percent rise in the previous month. It was the steepest increase since May, mainly boosted by sales of clothing and footwear (54.4 percent) and books and stationery (47.2 percent). Additional increases took place for furniture, electrical equipment, and household equipment (44.3 percent) and pharmaceutical products and cosmetics (17.6 percent). On a seasonally adjusted monthly basis, retail trade decreased by 2.6 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/sony-buying-bungie-in-3-6b-video-game-deal </td>
   <td style="text-align:left;"> 2022-02-01 02:52:49 </td>
   <td style="text-align:left;"> Sony buying Halo, Destiny video game maker Bungie in $3.6B deal </td>
   <td style="text-align:left;"> UBS Managing Director and senior portfolio manager Jason Katz on the state of markets and predicts more volatility.                                                                                                                                                           , Deal-making continues in the video game industry as Sony Interactive buys Bungie, the maker of the Halo and Destiny titles.                                                                                                                                                   , MICROSOFT BUYING ACTIVISION IN $68.7B DEAL                                                                                                                                                                                                                                    , "Bungie’s successful track record in multi-format publishing and live game services will assist us in realizing our ambitions to take PlayStation beyond the console and increase our potential audience," said Jim Ryan, president of Sony Interactive, in a deal blog post. , MICROSOFT DEAL MAKES ACTIVISION CEO EVEN RICHER                                                                                                                                                                                                                               ,   (AP Photo/Eugene Hoshiko, File)                                                                                                                                                                                                                                             , The $3.6 billion deal comes after Microsoft shelled out $69 billion for Activision earlier this month.                                                                                                                                                                        , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                       , Other game makers traded higher following the deal news.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ukraine/current-account </td>
   <td style="text-align:left;"> 2022-02-01 02:49:50 </td>
   <td style="text-align:left;"> Ukraine Current Account Widens in December </td>
   <td style="text-align:left;"> Ukraine’s current account  deficit widened to USD 547 million in December 2021, from a USD 317 million gap in the corresponding month of the previous year. The goods account gap widened to USD 1,312 million from USD 1,099 million, while the service account surplus expanded to USD 651 million from USD 508 million. Also, the primary income account widened to USD 340 million from USD 157 million. Meanwhile, the secondary income surplus slightly increased to USD 454 million from USD 431 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-01 02:30:00 </td>
   <td style="text-align:left;"> India 10Y Bond Yield Falls on Debt Switch Operation </td>
   <td style="text-align:left;"> Indian 10 year Government Bond Yield fell to 6.68%, down 8.4 basis points from yesterday amid easing of government’s borrowing concerns from the market following the debt switch operation with Central bank of India (RBI). RBI data showed the government switched bonds worth USD 15.96 billion with RBI last Friday. However, the bond yield remained close to 25-month high, tracking a general rise in global bond yields after the Federal Reserve set a more hawkish tone in its last meeting in contrast to an accommodative stance by the central bank of India </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/31/wage-growth-may-be-slowing-from-breakneck-pace.html </td>
   <td style="text-align:left;"> 2022-02-01 02:28:12 </td>
   <td style="text-align:left;"> Wage growth may be slowing from 'breakneck' pace </td>
   <td style="text-align:left;"> , The rapid pace of pay increases that characterized the labor market for much of last year is showing signs of slowing down.                                                                                                                                                                                                                                                                                                                  , Wage growth among private-sector jobs slowed to 1.2% in the fourth quarter of 2021 from 1.4% in the previous quarter, according to U.S. Department of Labor data issued Friday.                                                                                                                                                                                                                                                              , That pace is still above normal; it translates to a roughly 5% annual raise for workers compared to the pre-pandemic trend of around 3%, according to Nick Bunker, economic research director for North America at the Indeed Hiring Lab.                                                                                                                                                                                                    , More from Personal Finance:5 steps to protect your money from inflation65% of women would buy a home without being married firstInflation at its worst: Some ticket prices up as much as 100%                                                                                                                                                                                                                                                , The deceleration suggests businesses are starting to have an easier time finding workers — and therefore may not feel the need to bid up wages as rapidly to attract talent in 2022.                                                                                                                                                                                                                                                         , "The Q4 data hints at a slowdown," Bunker said. "In combination with other data, it suggests the breakneck speed of wage growth we saw in summer and early fall may not be the pace we see moving forward."                                                                                                                                                                                                                                  , "Slowing down from 120 miles per hour to 90 miles per hour is slowing down," he added. "But you're still hitting 90, which is pretty quick."                                                                                                                                                                                                                                                                                                 , A further slowdown would be unwelcome news for workers. Inflation has been running at its fastest pace in decades, eroding the large raises workers have gotten over the past year.                                                                                                                                                                                                                                                          , If wage growth continues to decelerate while the cost of living fails to ebb, the combination would eat into paychecks even more. However, if inflation moderates in 2022 and wage growth plateaus at current levels, workers may ultimately experience a net raise, Bunker said.                                                                                                                                                            , Demand for workers surged last year as the U.S. economy emerged from its pandemic hibernation.                                                                                                                                                                                                                                                                                                                                               , Job openings soared to record levels as employers' need for  workers outstripped the ready supply of labor. Millions of Americans have stayed on the sidelines of the job market, largely due to persistent pandemic health fears, care responsibilities at home and early retirements among older workers, according to economists. Other factors like elevated household savings and employee burnout also likely played a role, they said., Employees also began quitting in record numbers — a trend that came to be known as the Great Resignation — as Americans re-evaluated their work lives and many grew confident that they could find better, higher-paying jobs elsewhere.                                                                                                                                                                                                     , The recent Labor Department wage data suggests those hiring challenges for employers have somewhat eased.                                                                                                                                                                                                                                                                                                                                    , "Relatively, it's not as hard to hire as it was, say, back in September or August for some sectors," Bunker said.                                                                                                                                                                                                                                                                                                                            , Wages have jumped the most for low-paying, in-person jobs in  leisure and hospitality (hotels, restaurants, bars), and for those workers at bricks-and-mortar retail stores. Both sectors had  extended pandemic-related shutdowns, Bunker said.                                                                                                                                                                                             , Pay growth among leisure and hospitality jobs slowed to 1.4% in the fourth quarter of 2021, down from 2.5% in both the third and second quarters, according to the Labor Department data.                                                                                                                                                                                                                                                    , A separate agency report, the Job Openings and Labor Turnover survey, suggests that the rate of hiring among leisure and hospitality businesses improved in November after falling for three consecutive months.                                                                                                                                                                                                                             , Meanwhile, pay growth may still be accelerating in some industries. Retail wage growth, for example, jumped to 2.6% in the fourth quarter from 1.6% and 0.9% in the third and second quarters, respectively, according to the new data.                                                                                                                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/31/stocks-making-the-biggest-moves-midday-tesla-spotify-netflix-beyond-meat-and-more.html </td>
   <td style="text-align:left;"> 2022-02-01 01:54:08 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Tesla, Spotify, Netflix, Beyond Meat and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                       , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                                                           , Tesla — Tesla shares surged 10.7% after Credit Suisse upgraded the stock to outperform from neutral. The firm said the pullback in technology stocks this month has created a buying opportunity. "With robust fundamentals ahead and with the stock having been caught in the market decline, we believe the stock should recover," Credit Suisse said.                                                                                              , Spotify — Shares of the streaming platform are on watch after influential podcaster Joe Rogan apologized to Spotify amid a boycott over his content. Neil Young and Joni Mitchell pulled their music from Spotify after the company continued to host "The Joe Rogan Experience," which medical professionals have called out for spreading Covid misinformation. The stock also received an upgrade from Citi. Spotify shares surged more than 13.5%., Netflix – Shares of Netflix jumped 11.1% after Citi upgraded the stock to buy from neutral, saying that the streaming service has ample pricing power to weather high inflation, and that prevailing equity values don't reflect material subscriber growth prospects beyond 2023.                                                                                                                                                                    , Beyond Meat – The alternative meat stock surged 15.2% on Monday following a double upgrade from Barclays. The investment firm said that Beyond Meat's partnership with restaurant chains should help it stand out in a competitive industry.                                                                                                                                                                                                          , Boeing – Shares of Boeing popped 5.1% after the aircraft maker won an order from Qatar Airways on Monday. The airline signed a provisional order for 25 737 Max 10 jets.                                                                                                                                                                                                                                                                              , Goldman says corrections are buying opportunities and rarely turn into bear markets                                                                                                                                                                                                                                                                                                                                                                   , Wharton's Jeremy Siegel says don't panic if the stock market goes down another 10%                                                                                                                                                                                                                                                                                                                                                                    , Earnings playbook: An investor's guide to reports from Alphabet, Amazon, Meta and more                                                                                                                                                                                                                                                                                                                                                                , Intuitive Surgical – Shares of Intuitive Surgical rose 4.6% after Piper Sandler on Monday upgraded the medical stock to overweight from neutral. The firm said the "recent pullback offers investors an attractive entry point into a premier medtech name."                                                                                                                                                                                          , Align Technology — Shares of the dental company popped 6.7% in trading after Morgan Stanley initiated coverage of Align Technology as overweight. "ALGN is well positioned in the fastest-growing segment of the Dental market with its leading position in clear aligners," the firm said. The bank gave the stock a $575 per share price target.                                                                                                    , Kellogg — Shares of the food company ticked 3.5% lower after BMO downgraded Kellogg to market perform from outperform. The Wall Street firm said that it sees cereal "challenges" ahead.                                                                                                                                                                                                                                                              , Enphase Energy — Enphase Energy shares surged 13.4% after the company, which makes microinverters and backup energy storage for solar systems, announced an expansion of battery storage in Massachusetts.                                                                                                                                                                                                                                            , Citrix Systems — Citrix shares fell 3.4% after reports that the cloud-computing company will be taken private in an all-cash deal worth $16.5 billion, including debt. Vista Equity Partners and an affiliate of Elliott Management are acquiring Citrix for $104 per share, according to The Wall Street Journal.                                                                                                                                    , BlackBerry – BlackBerry shares added 4.4% after the communications software company announced a deal to sell its legacy patents for $600 million. The noncore patent assets include mobile devices, messaging and wireless networking. Catapult, a special purpose vehicle, was formed to acquire the BlackBerry patents.                                                                                                                             , Otis Worldwide – Shares of the elevator company rose 3.2% after Otis reported 72 cents in earnings per share for the fourth quarter, four cents ahead of estimates, according to Refinitiv. The company missed on revenue estimates but said it expected sales and operating margins to grow in 2022.                                                                                                                                                 , Walgreens – Walgreens shares dipped about 1.4% after Bloomberg reported the company has started the sales process for its Boots international drugstore unit. Additional buyout firms, such as Sycamore Partners, are reportedly considering bids.                                                                                                                                                                                                    , — CNBC's Leslie Joseph, Yun Li, Tanaya Macheel, Margaret Fitzgerald and Jesse Pound contributed reporting                                                                                                                                                                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-02-01 01:49:06 </td>
   <td style="text-align:left;"> Gasoline at Over 7-Year Highs </td>
   <td style="text-align:left;"> US gasoline futures extended a rally beyond $2.5 per gallon at the end of January, following crude oil futures higher and touching the highest level since September 2014, on supply concerns. US President Joe Biden said he would consider imposing sanctions on his counterpart Vladimir Putin if Russia invades Ukraine, while Yemen's Houthi movement launched Monday a missile attack on a United Arab Emirates base. Meanwhile, the weekly US inventory reports from both the Energy Information Administration and the American Petroleum Institute showed gasoline inventories rose for a fourth consecutive period last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/chile/industrial-production </td>
   <td style="text-align:left;"> 2022-02-01 01:45:00 </td>
   <td style="text-align:left;"> Chile Industrial Output Growth Slows in December </td>
   <td style="text-align:left;"> Industrial production in Chile rose 1.7 percent year-on-year in December of 2021, slowing from an upwardly revised 2.7 percent increase in the previous month. It was the third straight month of increases in industrial output, underpinned by manufacturing activities (2.3 percent vs 5.5 percent in November), and utilities (3.7 percent vs 4.7 percent). Meanwhile, mining &amp; quarrying output rebounded marginally (0.6 percent vs -0.6 percent), despite a slight drop in copper production (-0.6 percent vs -1.6 percent). On a monthly basis, industrial production inched down 0.3 percent after declining 0.6 percent in November. Considering the whole year, industrial output rose 2.2 percent, rebounding from a 1.0 percent drop in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 01:41:00 </td>
   <td style="text-align:left;"> Madrid Stocks Close Muted </td>
   <td style="text-align:left;"> The IBEX 35 Index recovered from intra-day losses to close at the flatline at 8,613 on Monday, as investors digested a batch of economic data ahead of the UN Security Council’s meeting regarding the Ukraine crisis after the session’s close and the ECB’s meeting on Thursday. On the corporate front, losses in the banking sector, led by Banco Santander (-1.7%) and Bankinter (-1.6%) offset gains in the industrial sector driven by ArcelorMittal (2.7%) and Ferrovial (1.6%). Meanwhile, preliminary data indicated the Eurozone's economy grew by 0.3% on the quarter during the three months leading to December, in line with market estimates. At the same time, Spain’s inflation rate eased to 6 percent in January, the first decrease since February of 2021, amid lower prices for electricity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/lithuania/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-01 01:28:51 </td>
   <td style="text-align:left;"> Lithuania 10Y Bond Yield Hits 31-month High </td>
   <td style="text-align:left;"> Lithuania 10 Year Government Bond Yeld increased to a 31-month high of 0.675% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/31/technology/joe-rogan-spotify-controversy.html </td>
   <td style="text-align:left;"> 2022-02-01 01:25:43 </td>
   <td style="text-align:left;"> Spotify’s Joe Rogan Problem Isn’t Going Away - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The Shift                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The controversy is different, in many ways, from the other conflicts between online stars and the companies that give them a platform.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , By Kevin Roose                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , To hear more audio stories from publications like The New York Times, download Audm for iPhone or Android.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Stop me if you’ve heard this one before:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , A popular internet personality, beloved by millions for his irreverent, anti-establishment commentary, becomes the subject of a heated backlash after critics accuse him of promoting dangerous misinformation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The controversy engulfs the creator’s biggest platform, which has rules prohibiting dangerous misinformation and now faces pressure to enforce them against one of its highest-profile users.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Hoping to ride out the storm, the platform’s chief executive publishes a blog post about the importance of free speech, declining to punish the rule-breaker but promising to introduce new features that will promote higher-quality information.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Still, the backlash intensifies. Civil rights groups organize a boycott. Advertisers pull their campaigns. A hashtag trends. The platform’s employees threaten to walk out. Days later, the chief executive is forced to choose between barring a popular creator — and face the fury of his fans — or being seen as a hypocrite and an enabler of dangerous behavior.                                                                                                                                                                                                                                                                                                                                                                     , If this scenario sounds familiar, it’s because a version of it has occurred on every major internet media platform over the last half decade. Facebook and Alex Jones, Twitter and Donald Trump, YouTube and PewDiePie, Netflix and Dave Chappelle: Every major platform has found itself trapped, at some point, between this particular rock and a hard place.                                                                                                                                                                                                                                                                                                                                                                           , Now, it’s Spotify’s turn. The audio giant has faced calls for weeks to take action against Joe Rogan, the mega-popular podcast host, after Mr. Rogan was accused of promoting Covid-19 misinformation on his show, including hosting a guest who had been barred by Twitter for spreading false information about Covid-19 vaccines. This month, a group of hundreds of medical experts urged Spotify to crack down on Covid-19 misinformation, saying Mr. Rogan had a “concerning history” of promoting falsehoods about the virus.                                                                                                                                                                                                       , So far, the backlash cycle is hitting most of the usual notes. Critics have compared snippets of Mr. Rogan’s interviews with Spotify’s stated rules, which prohibit material “that promotes dangerous false or dangerous deceptive content about Covid-19.” Two folk-rock legends, Neil Young and Joni Mitchell, led the boycott, pulling their catalogs from Spotify last week in protest of the platform’s decision to support Mr. Rogan. Brené Brown, another popular host, soon followed, saying she would not release new episodes of her Spotify-exclusive podcast “until further notice.”                                                                                                                                           , Daniel Ek, Spotify’s chief executive, published the requisite blog post on Sunday, defending the company’s commitment to free expression and saying that “it is important to me that we don’t take on the position of being content censor.” And while Spotify declined to take action against Mr. Rogan, it committed to putting advisory warnings on podcast episodes about Covid-19, and directing listeners to a hub filled with authoritative health information.                                                                                                                                                                                                                                                                     , Despite its surface similarities, Mr. Rogan’s Spotify standoff is different from most other clashes between creators and tech platforms in a few key ways.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , For one, Spotify isn’t merely one of many apps that distribute Mr. Rogan’s podcast. The streaming service paid more than $100 million for exclusive rights to “The Joe Rogan Experience” in 2020, making him the headline act for its growing podcast division. Critics say that deal, along with the aggressive way Spotify has promoted Mr. Rogan’s show inside its app, gives the company more responsibility for his show than others it carries.                                                                                                                                                                                                                                                                                      , Another difference is who wields the leverage in this conflict. YouTube, Twitter and Facebook are ad-supported businesses; if advertisers disagree with moderation decisions, they can threaten to inflict financial damage by pulling their campaigns. (Whether these boycotts actually accomplish anything is another question.)                                                                                                                                                                                                                                                                                                                                                                                                         , Spotify, by contrast, makes most of its money from subscriptions, so it’s unlikely to suffer financially from its handling of Mr. Rogan unless there’s a wave of account cancellations. And given how few Netflix subscribers appear to have canceled their subscriptions during last year’s dust-up with Mr. Chappelle, Spotify can probably breathe easy on this front for now.                                                                                                                                                                                                                                                                                                                                                          , But Spotify has a different constituency to worry about: stars. A leading music streaming service like Spotify needs to have popular hits in its library, which means that, in theory, musicians with enough firepower could force change simply by threatening to remove their albums. (As a viral tweet last week put it: “Taylor Swift could end Joe Rogan with a single tweet at Spotify.”) In practice, it’s a bit more complicated than that, in part because record labels, not musicians, generally control streaming rights. But it’s still possible that if Mr. Young’s and Ms. Mitchell’s moves inspire more top musicians and/or labels to pull their songs from Spotify, it could become a real business risk for the company., A third difference is Mr. Rogan himself. Unlike Mr. Jones and other firebrands, he is primarily an interviewer, and most of the uproar has been in response to things his guests have said. That gives him a more plausible excuse for entertaining fringe views, although critics have pointed out that Mr. Rogan’s own statements about Covid-19 have also been full of dubious information.                                                                                                                                                                                                                                                                                                                                             , So, how will Mr. Rogan’s backlash cycle end? It’s hard to say.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , One possibility is that it will end like those of Mr. Jones and Mr. Trump, whose behavior was so outrageous (and who continued to flagrantly violate the rule even after being called out) that Twitter and Facebook had no real choice but to shut them down permanently.                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , A different kind of controversy. Spotify is facing calls to take action against Joe Rogan after the popular podcast host was accused of promoting Covid-19 misinformation on his show, but the standoff is different from other similar controversies in a few key ways. Here’s a closer look:                                                                                                                                                                                                                                                                                                                                                                                                                                             , How it started. In an open letter, medical experts urged Spotify to crack down on Covid misinformation, singling out a recent episode of Mr. Rogan’s show that featured an interview with an outspoken vaccine skeptic.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Boycotts begin. The folk-rock legends Neil Young and Joni Mitchell pulled their catalogs from the streaming service ​​in protest of the platform’s decision to support Mr. Rogan. Brené Brown, another popular podcast host, also suspended her Spotify-exclusive show “until further notice.”                                                                                                                                                                                                                                                                                                                                                                                                                                               , The response. Spotify’s chief executive said that the company would add a “content advisory” to any podcast episode that includes a discussion of the coronavirus, but that it would not take on the position of “content censor.” Mr. Rogan has apologized for his “out of control” show and pledged to invite more mainstream experts.                                                                                                                                                                                                                                                                                                                                                                                                   , Big-picture impact. Unlike other platforms that have banned high-profile accounts for spreading Covid misinformation — such as Twitter’s permanent suspension of Representative Marjorie Taylor Greene — Spotify owns the exclusive rights to Mr. Rogan’s show. However, critics say that gives the company even more responsibility for the content.                                                                                                                                                                                                                                                                                                                                                                                      , Mr. Rogan could double down on Covid-19 misinformation, daring Spotify to de-platform him and casting himself as a “victim of the woke mob,” censored for speaking too many uncomfortable truths. He could wriggle out of his Spotify deal and head back to YouTube and to the other platforms that used to carry his show. (He could even go to a right-wing social network like Gettr or Parler, but I’m guessing he’d prefer an audience.)                                                                                                                                                                                                                                                                                              , Or he could do what PewDiePie, the popular YouTube creator whose real name is Felix Kjellberg, did after he was accused of making antisemitic comments. After briefly becoming a hero to right-wing reactionaries, Mr. Kjellberg apologized for his behavior, cleaned up his channel and eventually worked his way back into the platform’s good graces.                                                                                                                                                                                                                                                                                                                                                                                   , Mr. Rogan could quietly capitulate, protecting his Spotify deal and backing away from the Covid-skeptical fringe in a way that doesn’t cost him his reputation as an anti-establishment contrarian. (This outcome looked like the likeliest one on Sunday night, when Mr. Rogan posted a 10-minute Instagram video apologizing for his “out of control” show and pledging to invite more mainstream experts on to discuss the pandemic.)                                                                                                                                                                                                                                                                                                   , A third option is that the whole controversy could simply fizzle out, like last year’s imbroglio with Mr. Chappelle and Netflix, which began after the comedian was accused of making transphobic remarks during a special and ended, days later, with no real consequences for anyone. But this outcome doesn’t seem likely, given that boycotts have already begun and appear to be snowballing.                                                                                                                                                                                                                                                                                                                                         , The relationship between media personalities and the networks that air their work has always been fraught. But it has gotten messier in recent years, as growth-hungry tech companies have begun to pay top stars directly for their content. These deals have made them more like the radio and TV stations of old — picking popular acts, paying handsomely for their work, assuming greater responsibility for their output — and less like the neutral platforms they once claimed to be.                                                                                                                                                                                                                                              , The relationships between the companies and their users is changing, too. Users of these services have learned, by observing dozens of backlash cycles over the past several years, that a sufficient amount of pressure can get a tech company to do almost anything. They understand that the companies’ rules are fuzzy and improvisational, and that what chief executives mostly want — no matter what high-minded principles they profess to hold — is for people to stop yelling at them. They also know that if a company won’t take action based on listener complaints alone, there are other ways to turn up the heat.                                                                                                          , Spotify may think it’s gotten past the worst of the Rogan backlash. But we know from recent history that what looks like the end of a content moderation controversy is often just the warm-up act.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Audio produced by Parin Behrooz.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 01:23:47 </td>
   <td style="text-align:left;"> South African Stocks End at Over 1-Week High </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index rose 1.2% to close at an over one-week high of 74,305 on Monday, following a 1.8% loss the week before, supported by mobile operator MTN Group, tech stocks and a rise in commodity prices. Meanwhile, investors continued to digest the prospect of sharper interest rate hikes by the Federal Reserve, while also monitoring developments between Russia and Ukraine with the UN Security Council set to meet today to discuss ongoing tensions. Domestically, traders wait for news about adjustments to South Africa’s lockdown restrictions. On the data front, South Africa's trade surplus narrowed slightly in December. The JSE booked a 0.8% gain in January, its fourth consecutive monthly gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/congressman-ed-perlmutter-reintroduces-safe/story.aspx?guid={8BB43156-3E88-40F9-AE0C-AF674B451212}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-01 01:05:46 </td>
   <td style="text-align:left;"> Congressman Ed Perlmutter reintroduces SAFE Banking measure for cannabis companies - MarketWatch </td>
   <td style="text-align:left;"> Congressman Ed Perlmutter, D., Colo., said Friday he has attached the Secure and Fair Enforcement (SAFE) Banking Act for cannabis companies to an existing bill called the America Competes Act. The America Competes Act addresses research and innovation efforts as a non-cannabis specific bill. "Cannabis-related businesses - big and small - are in desperate need of access to capital &amp; the banking system in order to operate in an efficient, safe manner &amp; compete in the growing global cannabis marketplace," Perlmutter said on his Twitter feed late Friday. Late last year, SAFE Banking was included in the House version of the annual U.S. defense spending bill, but it was removed in the Senate. , Here's what you need to know.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 01:01:00 </td>
   <td style="text-align:left;"> UK Stocks End Almost Flat </td>
   <td style="text-align:left;"> The FTSE 100 erased early gains to close virtually unchanged at 7,464 on Monday, following an 88-point drop on Friday, as advances in financials offset losses in healthcare and commodity-linked stocks. On the corporate front, Vodafone was among the top performers (1.9%) after the company said it will work with Intel on designing its own chip architecture to drive innovation. Ryanair took a cautious note on travel rebound while posting a bigger-than-expected loss of €96 million in Q4. Meanwhile, investors brace for a busy week with the BoE monetary policy decision and earnings from Shell, Virgin Money and Glencore while the UN Security Council will meet today to discuss the Ukraine crisis at a time the US is close to approve big sanctions on Russia. The FTSE 100 rose 1.1% in January, its second consecutive monthly gain, outperforming its European peers, helped by a robust performance in higher weighted banking and energy shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 01:00:11 </td>
   <td style="text-align:left;"> French Shares Rebound on Monday </td>
   <td style="text-align:left;"> The CAC 40 Index recovered from mid-session losses to close 0.5% higher at 6,999 on Monday, supported by tech and luxury goods, while investors await the UN’s security council meeting regarding Russian military tensions with Ukraine and digest economic data from the Eurozone. Shares in the technology sector jumped 2.6%, tracking the Nasdaq composite and led by STMicroelectronics (3%), while Hermes (1.8%) and Kering (1.3%) lifted the luxury goods. On the other hand, Casino Guichard shares plunged 13.8% after the group lowered its gross operating surplus forecasts for French retail brands during 2021. Consequently, other retail shares traded in the red, driven by Carrefour (-5.8%). On the data front, the Eurozone economy expanded 5.2% during 2021 and 0.3% quarterly during Q4, while forecasts expect the euro area to grow by 4.2% in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/federal-reserve-fight-inflation-interest-rate-hikes </td>
   <td style="text-align:left;"> 2022-02-01 00:48:39 </td>
   <td style="text-align:left;"> Fed expected to raise rates 7 times this year to fight inflation, BofA says </td>
   <td style="text-align:left;"> FOX Business' Ashley Webster reports from the the Port of Savannah.                                                                                                                                                                                                                                                                                                                                                                                                  , Bank of America economists expect the Federal Reserve to hike interest rates at every meeting for the remainder of the year as central bank policymakers look to tackle the hottest inflation in nearly four decades.                                                                                                                                                                                                                                                , In a Friday analyst note to clients, the Bank of America economists – led by Ethan Harris – projected seven, quarter percentage point rate increases in 2022, putting the target range between 2.75% and 3% at year's end.                                                                                                                                                                                                                                           , "The Fed has all but admitted that it is seriously behind the curve," they wrote. "This should affect the economy with a lag, weighing on 2023 growth."                                                                                                                                                                                                                                                                                                              , FED SIGNALS INTEREST RATE HIKE COULD COME 'SOON' AS INFLATION RAGES                                                                                                                                                                                                                                                                                                                                                                                                  , Economists scrambled to update their outlook after the Fed said during its two-day, policy-setting meeting last week that it could "soon" raise rates for the first time in three years, paving the way for a March liftoff as policymakers seek to keep prices under control. A rate increase would mark the first since December 2018.                                                                                                                             , A woman walks past the Federal Reserve headquarters in Washington Sept. 16, 2015. (Reuters/Kevin Lamarque / Reuters Photos)                                                                                                                                                                                                                                                                                                                                          , "With inflation well above 2% and a strong labor market, the committee expects it will soon be appropriate to raise the target range for the federal funds rate," the Fed said in its post-meeting statement. The central bank's next meeting is scheduled for March 15-16; it has six more meetings in May, June, July, September, November and December.                                                                                                           , Other Wall Street banks have also increased their expectations on rate hikes this year: Goldman Sachs, for instance, is penciling in five increases, while Deutsche Bank also expects five and TD Securities sees four. Most traders are pricing in at least five rate hikes this year, with more than three-quarters projecting four rate hikes by September, according to the CME Group, which tracks trading.                                                     , For months, the Fed has been wrestling with its dual mandate of stable prices and full employment. But the nation's jobless rate plunged to 3.9% in December, down from a pandemic high of 14.7%, while consumer prices surged 7.1% from a year ago, marking the fastest pace for inflation since 1982 as consumer demand confronts a shortage of goods caused by congested ports and other pandemic-induced disruptions in the supply chain.                        , Federal Reserve Chair Jerome Powell pauses during a news conference in Washington on Jan. 29, 2020. (AP Photo/Manuel Balce Ceneta, File / AP Newsroom)                                                                                                                                                                                                                                                                                                               , "I would say, and this view is widely held on the committee, both sides of the mandate are calling for us to move steadily away from the very highly accommodative policies we put in place during the challenging conditions that the economy faced earlier in the pandemic," Fed Chairman Jerome Powell told reporters during a post-meeting press conference. "Most FOMC participants agree that labor market conditions are consistent with maximum employment." , Some economists believe the Fed waited too long to confront the burst in inflation, while others have expressed concerns that moving too quickly to stabilize prices risks slowing hiring and potentially leaving many workers, particularly lower-income Americans, without a job. Hiking interest rates tends to create higher rates on consumers and business loans, which slows the economy by forcing employers to cut back on spending.                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                          , Powell has left open the possibility of a rate hike at every meeting this year and has refused to rule out a more aggressive, half-percentage point rate hike, but said it's important to be "humble and nimble."                                                                                                                                                                                                                                                    , "We’re going to be led by the incoming data and the evolving outlook," he said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 00:48:00 </td>
   <td style="text-align:left;"> Italian Stocks Outperform European Counterparts </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 0.9% higher at 26,814 on Monday, supported by tech and banking shares, while investors digested fresh economic data and awaited the UN Security Council meeting regarding Russia’s military tension with Ukraine. STMicroelectronics (3.1%) led the gains among the technology sector, while UniCredit (1.8%) rose the most among the banks. On the other hand, Saipem lost 30.2% before trading was halted mid-session, as the oilfield services provider warned it will take a heavy loss for 2021. On the data front, the Italian economy expanded 0.6% during the fourth quarter, beating market expectations, while the euro area expanded 0.3%. On the political front, Sergio Mattarella was re-elected as the Italian president on the eighth voting round after six days of stalemate, keeping Mario Draghi as the Prime Minister. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 00:47:00 </td>
   <td style="text-align:left;"> European Stocks End Flat to Higher </td>
   <td style="text-align:left;"> European stocks closed marginally higher on Monday, with both the DAX and the Stoxx 600 up 0.6%, and the FTSE 100, CAC 40, and IBEX 35 ending almost flat, while the FTSE MIB outperformed and gained roughly 0.7%. Investors digested fresh economic data and earnings while awaiting the UN Security Council meeting today to discuss the Ukraine crisis at a time when the US is close to approving big sanctions on Russia. The Eurozone economy expanded 0.3% in Q4 as expected but the Italian economy advanced at a faster-than-anticipated 0.6%, while Germany’s inflation rate eased less than expected to 4.9% in January. On the corporate front, Ryanair took a cautious note on travel rebound while posting a bigger-than-expected loss of €96 million in Q4. Quarterly results from UBS and Roche this week and the ECB monetary policy decision on Thursday will also be in the spotlight. On a monthly basis, the Stoxx 600 shed 4% in its worst month since October 2020, while the DAX erased 3.4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/31/media/joe-rogan-misinformation-instagram-response/index.html </td>
   <td style="text-align:left;"> 2022-02-01 00:41:48 </td>
   <td style="text-align:left;"> Joe Rogan responds to the backlash from Spotify artists - CNN </td>
   <td style="text-align:left;"> New York (CNN)Joe Rogan has responded to the backlash he's received from Spotify artists surrounding Covid-19 misinformation on his popular podcast.                                                                                                                                                                                                                              , "I'm not trying to promote misinformation, I'm not trying to be controversial. I've never tried to do anything with this podcast other than just talk to people and have interesting conversations," Rogan said in a 9-minute video posted to Instagram on Sunday.                                                                                                                , On Sunday, Spotify said it will add a content advisory to any podcast episode about Covid-19 — and Rogan said he agrees with that move. The advisory will direct listeners to a Covid-19 information hub that will include links to trusted sources, the company said.                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                   , "I want to thank Spotify for being so supportive during this time. And I'm very sorry that this is happening to them, and that they're taking so much heat from it," Rogan said.                                                                                                                                                                                                  , Spotify will also for the first time publicly post its long-standing Platform Rules. A growing list of musicians and personalities are pressuring Spotify to take action on misinformation after Neil Young and then Joni Mitchell requested that their music be removed from the platform.                                                                                       , In his video, Rogan said he would try to balance controversial guests by having the mainstream perspective on right after them. He also said he will research contentious topics and "have all the pertinent facts at hand."                                                                                                                                                      , "I want to show all kinds of opinions so that we can all figure out what's going on and not just about Covid, about everything about health, about fitness, wellness, the state of the world," Rogan said.                                                                                                                                                                        , Rogan portrayed himself as a figure who is just having interesting conversations, but at the same time he disputed the basic concept of misinformation. He claimed that changes in scientific opinion — for example about the effectiveness of cloth masks or the origins of the virus — have previously been viewed as misinformation and could have been banned on social media.,                                                                                                                                                                                                                                                                                                                                                                                   , "Many of the things that we thought of as misinformation just a short while ago are now accepted as fact," Rogan claimed.                                                                                                                                                                                                                                                         , "The Joe Rogan Experience" is currently the top podcast in the United States and the United Kingdom on Spotify, according to the platform.                                                                                                                                                                                                                                        , Rogan defended two of his most controversial guests — cardiologist Dr. Peter McCullough, who claimed Covid-19 vaccines are "experimental," and virologist Dr. Robert Malone, who has been banned from Twitter for Covid-19 misinformation.                                                                                                                                        , "Both these people are very highly credentialed, very intelligent, very accomplished people. And they have an opinion that's different from the mainstream narrative," Rogan said, adding that he has also hosted CNN's Dr. Sanjay Gupta. "I wanted to hear what their opinion is."                                                                                               , Rogan also said he is "not mad" at Neil Young and that he is a "huge" fan of the musician.                                                                                                                                                                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macau/balance-of-trade </td>
   <td style="text-align:left;"> 2022-02-01 00:36:00 </td>
   <td style="text-align:left;"> Macau Trade Gap Widens in December </td>
   <td style="text-align:left;"> Macau’s trade deficit widened to MOP 13.65 billion in December of 2021 from MOP 10.8 billion a year earlier. Imports jumped 22.2 percent year-on-year to MOP 14.68 billion, mainly boosted by purchases of electronic components (127.2 percent); gold &amp; jewelry (81.3 percent); and mobile phones (34.9 percent). Meanwhile, exports fell 15.0 percent to MOP 1.03 billion, weighed down by a 19 percent drop in re-exports, while an 8 percent rise in domestic exports limited further losses. Re-exports fell mostly for cosmetics &amp; skincare products (-69.4 percent) and casino (-56.0 percent), while domestic exports rose on the back of pharmaceutical products &amp; organic chemicals (44.4 percent). Considering 2021 as a whole, Macau’s trade deficit widened to MOP 140.91 billion from MOP 81.75 billion in the previous year, as imports soared 66.2 percent to MOP 153.88 billion and exports rose a slower 19.9 percent to MOP 12.96 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/gas-prices-climb-fifth-straight-week-oil-prices </td>
   <td style="text-align:left;"> 2022-02-01 00:19:33 </td>
   <td style="text-align:left;"> Gas prices climb for fifth straight week as oil surges </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                  , The average price for a gallon of gasoline in the United States rose slightly for the fifth week in a row, climbing 2.9 cents from a week ago, according to an industry expert.                                    , Currently, the national average is sitting at $3.34 per gallon, according to GasBuddy, which compiled price reports covering over 150,000 gas stations across the country.                                         , The current figure reflects a nearly 76-cent increase per gallon compared to a month ago and a nearly 93-cent increase per gallon compared to a year ago, according to the data.                                   ,  CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                           , Petrol prices are seen displayed at a Conoco gas station, a brand owned by Phillips 66, in Brooklyn, New York, Nov. 11, 2021.  (REUTERS/Andrew Kelly / Reuters Photos)                                             , Patrick De Haan, the head of petroleum analysis for GasBuddy, said in a blog post Monday that the continued uptick at the pump is because oil prices are being "pushed into territory unseen in over seven years." , GAS PRICES RISING: DRIVERS COULD FEEL 'REAL PAIN' AT THE PUMP BY SPRINGTIME, EXPERT WARNS                                                                                                                          , The price of West Texas Intermediate crude oil hit $88 per barrel in overnight trading Sunday, the highest level since 2014, before dipping to $87.50 per barrel on Monday.                                        , Although the increases at the pump have been small, they will "likely" continue, De Haan said.                                                                                                                     , "With continued concerns over geopolitical tensions and crude oil supply, the small yet noticeable increases are likely to continue," De Haan said in the blog post.                                               , Gas prices grow along with inflation as this sign at a gas station shows in San Diego, California, Nov. 9, 2021.  (Reuters/Mike Blake / Reuters Photos)                                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                        , The key that's been keeping "prices from rising more substantially is that gasoline demand remains low as winter storms keep motorists closer to home," De Haan added.                                             , However, as the weather begins to get warmer, "we’ll lose the only restraint to larger price increases."                                                                                                           , Previously, De Haan projected that there may be an increase of 10 to 20 cents per gallon every month starting in March through Memorial Day.                                                                       , By June, GasBuddy estimated that the national average price for a gallon of gasoline could climb to a high of $4.13. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/fda-grants-full-approval-modernas/story.aspx?guid={4883F8AD-671F-4C2D-A8D4-543E86CB9D41}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-01 00:16:27 </td>
   <td style="text-align:left;"> FDA grants full approval to Moderna's COVID-19 vaccine - MarketWatch </td>
   <td style="text-align:left;"> Shares of Moderna Inc. 
        MRNA,
        +6.18%
       gained 3.4% in trading on Monday after the company said it received full approval from the Food and Drug Administration for its COVID-19 vaccine, which is now called Spikevax. The FDA has granted full approval to one other COVID-19 shot: BioNTech SE 
        BNTX,
        +6.08%
       and Pfizer Inc.'s 
        PFE,
        -3.02%
       Comirnaty. The Spikevax approval is for adults, though the vaccine still has emergency authorization for use in teens and as a booster dose. Moderna's stock is down 4.5% over the past year, while the broader S&amp;P 500 
        SPX,
        +1.89%
       is up 17.0%. , Will the Fed tighten the economy into a recession? That’s what some on Wall Street fear. Watch the yield curve for clues to the next downturn.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-01 00:10:00 </td>
   <td style="text-align:left;"> Italy 10Y Bond Yields Stable Ahead of ECB Decision </td>
   <td style="text-align:left;"> The yield on the Italian 10-year BTP remained near 1.4% amid inflation worries ahead of the ECB meeting on Thursday, although presidential election results capped lower bond prices relative to its European peers. The Eurozone's benchmark rate is widely expected to remain unchanged, as investors await the ECB's inflation expectations and timing of policy tightening, since money markets currently price two 10bps rate hikes by the end of the year. The bloc's latest inflation rate came at a record 5% for December. In the meantime, investors digested the re-election of Sergio Mattarella as Italy’s head of state after seven stalemate rounds, leaving Mario Draghi as Prime Minister and increasing the likelihood of short-term continuity to the current administrations’ implementation of the EUR 191.5 billion in EU recovery funds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-02-01 00:05:00 </td>
   <td style="text-align:left;"> Hong Kong Retail Sales Wane in December </td>
   <td style="text-align:left;"> Retail sales in Hong Kong rose 3.4 percent year-on-year in December of 2021, slowing from an upwardly revised 4.3 percent advance in the previous month. It was the eleventh straight month of expansion in the sector but the slowest since July of the same year. Retail sales rose the most for jewelry, watches, clocks &amp; valuable gifts (18.7 percent vs 9.7 percent in November); followed by fuels (13.4 percent vs 2.3 percent); other consumer goods (8.9 percent vs 17.4 percent); consumer durable goods (4.3 percent vs 0.2 percent); and clothing, footwear &amp; allied products (4.0 percent vs 9.8 percent). Looking ahead, a government spokesman said the sector faced added risks now that authorities reimposed public health restrictions amid the latest wave of the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/portugal/gdp-growth </td>
   <td style="text-align:left;"> 2022-01-31 23:39:52 </td>
   <td style="text-align:left;"> Portugal GDP Growth Wanes in Q4 </td>
   <td style="text-align:left;"> Portugal’s GDP rose 1.6 percent quarter-on-quarter in the last three months of 2021, slowing from a 2.9 percent expansion in the previous quarter, a preliminary estimate showed. With one of the highest vaccination rates in Europe, economic activities in Portugal resumed almost unrestricted, such that domestic demand contributed more significantly to growth than in the previous period. Net external demand was positive but the stronger weight of the import deflator dampened its contribution to GDP growth, namely due to increasing energy and raw materials prices. Year-on-year, the economy advanced 5.8 percent, following an upwardly revised 4.5 percent expansion in the third quarter. Considering 2021 as a whole, the Portuguese GDP rose at a three-decade high of 4.9 percent, rebounding from an unprecedented 8.9 percent slump in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macedonia/retail-sales-yoy </td>
   <td style="text-align:left;"> 2022-01-31 23:39:03 </td>
   <td style="text-align:left;"> Macedonia Retail Sales Growth Slows to 10-Month Low </td>
   <td style="text-align:left;"> Retail sales in Macedonia rose 1.4 percent year-on-year in December of 2021, slowing from a 9 percent increase in the previous month. It was the smallest annual gain in retail trade since February, as sales slowed for both non-food products (5.2 percent vs 12.8 percent in November); and automotive fuel (9.5 percent vs 9.9 percent). Also, sales declined for food, beverages &amp; tobacco (-2.8 percent vs 8.9 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/ex-reagan-economist-issues-dire-warning-on-us-economy-tipping-into-a-slowdown </td>
   <td style="text-align:left;"> 2022-01-31 23:38:58 </td>
   <td style="text-align:left;"> Laffer's dire warning on inflation, US economy: 'Tipping into a slowdown' </td>
   <td style="text-align:left;"> Former Reagan economist Art Laffer argues that inflation is 'not under control yet' and that 'the Fed is doing everything wrong.'                                                                                                                                                                                                                                 , Former Reagan economist Art Laffer issued a dire warning for the U.S. economy, arguing on Monday that it is "tipping into a slowdown" and that a recession in 2023 is plausible.                                                                                                                                                                                  , Laffer also argued that inflation is "not under control yet" and noted that he is "quite concerned about the next 12 months for the U.S. economy."                                                                                                                                                                                                                , Laffer made the comments on "Mornings with Maria" on Monday, three days after it was revealed that a key measure of annual inflation that is closely watched by the Federal Reserve is running at the hottest pace in nearly four decades as widespread supply disruptions, extraordinarily high consumer demand and worker shortages fuel rapidly rising prices. , Prices soared by 5.8% in the year through December, according to the personal consumption expenditures price index data released Friday morning, beating out the previous month's increase of 5.7% to become the fastest inflation pace since 1982                                                                                                                , WHERE ARE SURGING CONSUMER PRICES HITTING AMERICANS THE HARDEST?.                                                                                                                                                                                                                                                                                                 , In the one-month period between November and December, prices jumped 0.4% (0.5% when excluding food and energy costs).                                                                                                                                                                                                                                            , Excluding the more-volatile measurements of food and energy, prices rose 4.9% in December from the previous year – the highest since September 1983. That measurement is the Fed's preferred gauge to track inflation; it marks the ninth consecutive month the measure has been above the central bank's target range of 2%.                                     , The inflation spike largely reflected surging energy costs, which rose 29.9% from a year ago, and food costs, which were up 5.7% over that same time period. Services inflation rose by 4.2% in December, and goods inflation increased 8.8% – up from the 8.5% pace a month prior, the data shows.                                                               , "I think we are at a really precarious position," Laffer told host Maria Bartiromo on Monday.                                                                                                                                                                                                                                                                     , Former Reagan economist Art Laffer argues inflation is 'not under control yet' and says he is 'quite concerned about the next 12 months for the U.S. economy.'                                                                                                                                                                                                    , "I think we might be tipping into a slowdown and if that happens, that would be really bad for the economy."                                                                                                                                                                                                                                                      , When speaking about inflation, he pointed to oil prices, noting that there has been "a very sharp rise" last month, following "a very sharp fall" the month before, "but the two together don’t show any improvement in inflation to my way of looking at it."                                                                                                    , "And we don’t have any basics coming in that could really do a good job; tax cuts, spending restraint, sound money, all of that is missing, so I am quite concerned about the next 12 months for the U.S. economy," he continued.                                                                                                                                 , Last week, The Federal Reserve signaled it could "soon" raise interest rates for the first time in three years, paving the way for a March liftoff as policymakers seek to keep prices under control and combat the hottest inflation in nearly four decades.                                                                                                     , Although central bank officials have left rates unchanged since March 2020, they indicated broad support last week during a two-day, policy-setting meeting to begin aggressively normalizing policy, including raising rates amid growing concern over the rapid increase in consumer prices.                                                                    , A rate increase would mark the first since December 2018.                                                                                                                                                                                                                                                                                                         , Markets have been volatile in anticipation of the rate hikes. For the month, all three of the major averages are down with the Nasdaq fairing the worst off 12%.                                                                                                                                                                                                  , Last Monday, co-founder and chief economist of Cornerstone Macro Nancy Lazar argued that a "significant global slowdown" and "a risk of a global recession" is plausible in 2023.                                                                                                                                                                                 , "We are a global economy, many companies are globally based, and the tightening cycle was already set to slow the economy here in 2023 and the Fed would obviously make it worse, but so would Russia, big time, and that’s why we raised the specter from the first time of a global recession possibly in 2023," Lazar said. "I hope not, but it is what it is.", Cornerstone Macro Chief economist Nancy Lazar argues the Fed's anticipated rate hikes in addition to what has been a 'very clear global tightening cycle,' higher oil prices, and the potential for weaker company earnings are weighing on markets.                                                                                                              , Laffer agreed with Lazar on Monday, telling Bartiromo that the economist is "right on the money."                                                                                                                                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                       , Global tensions with Russia inching closer to Ukraine also contributed to the selling last week. A big catalyst came when President Biden announced he would hold a video call with European leaders over the escalating situation in the afternoon which sent stocks to the lows of the session.                                                                 , The end result: joint efforts to keep Russia and President Putin in check.                                                                                                                                                                                                                                                                                        , Last week’s market volatility was also a result of investor jitters over the possibility of faster rising interest rates to combat inflation.                                                                                                                                                                                                                     , "I think the Fed is doing everything wrong," Laffer argued. "I think the only hope we really have of a good thing would be the elections in November."                                                                                                                                                                                                            , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                           , FOX Business’ Suzanne O’ Halloran and Megan Henney contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kenya/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-31 23:38:05 </td>
   <td style="text-align:left;"> Kenya January Inflation Rate Lowest Since November 2020 </td>
   <td style="text-align:left;"> The annual inflation rate in Kenya eased to 5.4 percent in January of 2022 from 5.7 percent in the previous month. It was the lowest inflation rate since November of 2020, amid a slowdown in prices of food &amp; non-alcoholic beverages (8.9 percent vs 9.1 percent in December). Also, prices eased for housing and utilities (5.11 percent vs 6.2 percent); and transport (6.8 percent vs 8.1 percent). On a monthly basis, consumer prices inched up 0.3 percent, slowing from a 0.9 percent rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/dallas-fed-manufacturing-index </td>
   <td style="text-align:left;"> 2022-01-31 23:37:00 </td>
   <td style="text-align:left;"> Texas Manufacturing Activity Growth at 1-1/2-Year Low </td>
   <td style="text-align:left;"> The Federal Reserve Bank of Dallas' general business activity index for manufacturing in Texas eased 6 points to +2 in January of 2022, pointing to the smallest growth in factory activity since July of 2020. The production index, a key measure of state manufacturing conditions, came in at 16.6, an eight-month low but a reading still indicative of above-average output growth. The new orders and growth rate of orders indexes held steady at 20.0 and 12.6, respectively, suggesting a continuation of elevated demand growth. The capacity utilization index fell 13 points to 12.0, and the shipments index fell 12 points to 8.6. While still suggestive of growth, these lower readings indicate a deceleration from December. Labor market measures indicated robust employment growth and longer workweeks; while prices and wages continued to increase strongly in January, though price pressures eased slightly. Finally, expectations regarding future manufacturing activity remained highly positive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hungary/producer-prices-change </td>
   <td style="text-align:left;"> 2022-01-31 23:24:22 </td>
   <td style="text-align:left;"> Hungary Producer Inflation at New All-Time High </td>
   <td style="text-align:left;"> Producer prices in Hungary jumped 22.3 percent year-on-year in December of 2021, quickening from a 21.6 percent increase in the previous month. It was the fastest producer inflation rate since records began in January of 2001 amid soaring utility prices (93.5 percent vs 86.6 percent in November). To a lesser extent, prices also rose steeply in the mining &amp; quarrying sector (30.5 percent vs 31.9 percent), and at a much softer pace in manufacturing industries (14.1 percent vs 14.0 percent). At last, charges for water collection, treatment, and supply continued to decline (-1.2 percent vs -1.1 percent). On a monthly basis, producer prices went up by 1.6 percent, after increasing 2.7 percent in the previous month. For 2021 as a whole, prices climbed 13.5 percent, after rising 4.2 percent in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-31 23:14:00 </td>
   <td style="text-align:left;"> Toronto Stocks Extend Gains on Monday </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, extended gains past the 20,800 mark on Monday, with rising oil and bullion prices underpinning growth in energy and materials stocks. Still, caution over faster tightening of monetary policy from the US Fed and the Bank of Canada offset some of the upward momentum. On the data front, prices of raw materials fell more than expected in December, the second straight month of declines. Elsewhere, rising tensions in Eastern Europe have led the government to withdraw non-essential staff and dependents from its embassy in Ukraine. Considering January as a whole, the index is set to shed 1.9%, after climbing 2.7% in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-01-31 23:08:51 </td>
   <td style="text-align:left;"> Dollar on Track for 1% Monthly Gain </td>
   <td style="text-align:left;"> The dollar index declined to below 97 on the last trading day of January but is on track to book a 1% gain for the month, amid increasing bets the Fed will deliver 5 interest rate hikes this year while economic data for the US has pointed to a robust economic recovery. Investors now await the payrolls report on Friday for a more clear picture of the impact of the omicron coronavirus variant on the labour market while monetary policy decisions in Australia, Europe and the UK will give an update on tightening plans from other major central banks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-01-31 23:03:13 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index at Over 1-Week High </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index rose 2.7% to 1,418 on Monday, its highest since January 20th, extending gains for a third straight session, as the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, climbed 12.4% to 1,208, its highest level in more than a week. Meanwhile, the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, eased 12 points to 1,828, its lowest since April; and the supramax index fell 10 points to its lowest since February 2021 at 1,587. The Baltic Dry Index has fallen 36% in January, its biggest decline in two years, amid seasonal weakness and lower iron ore shipments from Australia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/israel/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-31 23:00:09 </td>
   <td style="text-align:left;"> Israel 10Y Bond Yield Hits 22-month High </td>
   <td style="text-align:left;"> Israel 10 Year Government Bond Yeld increased to a 22-month high of 1.422% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2022-01-31 23:00:00 </td>
   <td style="text-align:left;"> British Pound Strengthens Ahead of BoE Meeting </td>
   <td style="text-align:left;"> The British pound strengthened above $1.34 on Monday, after rebounding from an over one-month low of $1.339 reached on January 27th, as investors geared up for the Bank of England monetary policy meeting later in the week. Market participants are expecting policymakers to raise interest rates by 25 bps, following a 15 bps hike at its last meeting, while also beginning to taper its £875 billion government bond holdings. For the month of January as a whole, the British pound still weakened roughly 0.7% against the greenback, which benefited from the Federal Reserve’s signals of faster tightening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-31 22:59:56 </td>
   <td style="text-align:left;"> US 10Y traded above 1.8 percent </td>
   <td style="text-align:left;"> US 10 Year Note Bond Yield rose above 1.8, according to over-the-counter interbank yield quotes for this government bond maturity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macedonia/industrial-production </td>
   <td style="text-align:left;"> 2022-01-31 22:51:42 </td>
   <td style="text-align:left;"> Macedonia Industrial Output Shrinks in December </td>
   <td style="text-align:left;"> Industrial production in Macedonia fell 4.9 percent from a year earlier in December of 2021 compared to a 4.7 percent rise in the previous month as output declined in manufacturing (-9.1 percent) on lower production of beverages; textiles; wearing apparel; basic metals, pharmaceutical products; machinery and equipment n.e.c, motor vehicles, trailers and semi-trailers. Meanwhile, production rose for both electricity, gas, steam and air conditioning supply (20.5 percent) and mining &amp; quarrying (2.5 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-31 22:48:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Edge Lower </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, was down 0.3% to around 111,630 on the last trading day of January, mainly led by miner Vale. At the same time, investors remain cautious ahead of the central bank's meetings in Brazil and in other parts of the world, including the Eurozone and England. On the domestic economic front, Brazil shed a more-than-expected net 265.8 thousand formal jobs in December of 2021, traditionally a negative month for job creation; but added a net 2.731 million formal jobs in 2021, the best annual figure since the data series started in 2010, benefiting from an expansion in the services sector. Meanwhile, Brazil's central bank financial markets' weekly survey for 2022 showed inflation forecasts were revised higher for a third consecutive week to 5.38% from 5.15%, while growth projections were revised slightly higher to 0.30% from 0.29%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/31/health/moderna-mrna-hiv-vaccine/index.html </td>
   <td style="text-align:left;"> 2022-01-31 22:42:04 </td>
   <td style="text-align:left;"> Moderna mRNA HIV vaccine: First patients vaccinated in clinical trial - CNN </td>
   <td style="text-align:left;"> (CNN)The first participants have been vaccinated in a Phase 1 clinical trial of an experimental HIV vaccine that utilizes Moderna's mRNA technology, the company announced last week.                                                                                                                                                                                                                                 , The trial, titled IAVI G002, is being conducted in partnership with IAVI, a nonprofit scientific research organization. It is testing a vaccine that delivers HIV-specific antigens to the body with the goal of inducing an immune response. These antigens were initially developed by researchers at IAVI and Scripps Research, led by Dr. William Schief.                                                          , In a "proof-of-concept" trial last year, the research team found the HIV antigens produced the desired immune response in 97% of participants. The current trial builds on the previous one by testing the primary version of the vaccine and also a booster version, and by employing Moderna's mRNA technology, which was previously used to create a successful Covid-19 vaccine.                                   , "We are tremendously excited to be advancing this new direction in HIV vaccine design with Moderna's mRNA platform. The search for an HIV vaccine has been long and challenging, and having new tools in terms of immunogens and platforms could be the key to making rapid progress toward an urgently needed, effective HIV vaccine," Mark Feinberg, IAVI's president and CEO, said in a news release from Moderna.  ,                                                                                                                                                                                                                                                                                                                                                                                                                        , The new trial, funded in part by the Bill &amp; Melinda Gates Foundation, will follow 56 HIV-negative adult participants, with the goal of studying both the safety and efficacy of the vaccine. Forty-eight of the volunteers will receive at least one dose of the primary vaccine, 32 of which will also receive the booster. The remaining eight will receive the booster vaccine alone.                               , The trial includes participants from four locations: George Washington University School of Medicine, Hope Clinic of Emory Vaccine Center, Fred Hutchinson Cancer Research Center, and the University of Texas Health Science Center at San Antonio.                                                                                                                                                                   , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-31 22:42:00 </td>
   <td style="text-align:left;"> Oil Books 17% Monthly Gain </td>
   <td style="text-align:left;"> WTI crude futures traded above $88 a barrel on Monday, remaining close to levels not seen since 2014 and booking a 17% gain for the January month, the strongest since February 2021, amid robust demand, tight supply and falling inventories. Geopolitical tensions in Eastern Europe and the Middle East are raising worries of supply disruptions and commercial oil and fuel stocks in OECD countries are at their lowest levels in seven years, according to the IEA. Moreover,  OPEC+ is set to stick with a planned 400,000 bpd production increase for March when it meets this week but the group has failed to meet output targets as some members struggled with capacity constraints. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-31 22:35:00 </td>
   <td style="text-align:left;"> Wall Street Rebounds to End January </td>
   <td style="text-align:left;"> US stocks rebounded on the last trading day of January, with the Dow Jones gaining more than 200 points, the S&amp;P 500 adding more than 1% and the Nasdaq more than 2%. Still, January has been very bad for stocks on mixed earnings reports and as Fed moved to a more hawkish monetary policy with investors increasingly betting on five rate hikes in 2022. The Dow and the S&amp;P 500 are down 5% and 7%, respectively, and head for their worst month in over a year while the Nasdaq is off by 12% and is on track for its worst month since October 2008. Meanwhile, Advanced Micro, Exxon Mobil, GM, Alphabet, Meta, Amazon, Honeywell, Ford, PayPal, and Wynn Resorts are due to report this week. The payrolls report, JOLTS, and ADP figures will also be in the spotlight this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-01-31 22:32:00 </td>
   <td style="text-align:left;"> Brazilian Real Strongest in 4-Months </td>
   <td style="text-align:left;"> The Brazilian Real is approaching $5.35, the strongest since October, as hotter-than-expected inflation rate strengthened the case for a more hawkish policy stance by The Central Bank of Brazil. Mid-month consumer price data showed that the annual inflation rate remained above 10%, higher than market expectations and the central bank’s target of 3.5%. Since April last year, COPOM has raised the main Selic rate by 725 bps to 9.25% and is expected to deliver another 150 bps hike during its next monetary policy meeting on February 2nd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/government-budget-value </td>
   <td style="text-align:left;"> 2022-01-31 22:32:00 </td>
   <td style="text-align:left;"> Brazil Government Budget Narrows in December </td>
   <td style="text-align:left;"> Brazil's nominal budget deficit shrank to BRL 54.2 billion in December of 2021, from BRL 75.8 billion in the corresponding month of the previous year. The central government gap declined to BRL 37 billion from 64.9 billion in December of 2020 and the deficit of state-owned enterprises fell to BRL 1.4 billion from BRL 1.7 billion. By contrast, regional governments' shortfall rose to BRL 15.9 billion from BRL 9.1 billion in December of 2020. Meanwhile, Brazil's government posted a primary surplus of BRL 0.1 billion, compared to a deficit of BRL 58.1 billion a year ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/biden-federal-reserve-nominee-opposition-state-treasurers </td>
   <td style="text-align:left;"> 2022-01-31 22:30:07 </td>
   <td style="text-align:left;"> Biden's Fed nominee Raskin opposed by 24 state financial officers over 'radical' economic views </td>
   <td style="text-align:left;"> Mark Smith, Erin Gibbs and Jared Dillian analyze the state of the economy on 'Making Money.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , A coalition of Republican state financial officers is pushing back again Sarah Bloom Raskin, President Biden’s nominee to become the Federal Reserve's top Wall Street regulator, over concerns that her economic views on issues like climate change and the private banking sector are "radical."                                                                                                                                                                                                                                                                                 , In a Monday letter addressed to the White House, 24 state treasurers, auditors and financial officers urged Biden to withdraw his nomination of Raskin as the Fed's vice chair of supervision, warning that her past statements indicate she is "willing to place the growth and stability of the U.S. economy at risk to achieve her preferred social outcomes."                                                                                                                                                                                                                   , FED SIGNALS RATE HIKE COULD COME 'SOON' AS INFLATION RAGES                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , A major point of contention for the state financial officers is Raskin's stance on climate change and her view that it poses a systemic risk to the U.S. financial system. Raskin has previously argued that all financial institutions should re-evaluate their relationships with energy companies and has advocated for a push toward sustainable investments that do not depend on carbon and fossil fuels. If banks and other financial institutions do not take these steps to distance themselves from fossil-fuel companies, Raskin has said the Fed should penalize them.  , Sarah Bloom Raskin, governor of the U.S. Federal Reserve, on Tuesday, Dec. 10, 2013.  (Andrew Harrer/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                                                                                                     , "We oppose Ms. Raskin’s radical banking and economic views and are deeply concerned that she would use the supervisory authority as Vice-Chair for Supervision at the Federal Reserve Bank to disrupt the private banking sector, reliable energy supplies, and the U.S. economy," the state financial officers wrote.                                                                                                                                                                                                                                                              , Signatories included the financial officers from Nebraska, Arkansas, Missouri, Utah, Louisiana, Arizona, Florida, Georgia, Idaho, Indiana, Kentucky, Mississippi, North Carolina, North Dakota, Ohio, Oklahoma, Pennsylvania, South Carolina, South Dakota, West Virginia and Wyoming.                                                                                                                                                                                                                                                                                              , The letter comes just a few days before Raskin is scheduled to testify before the Senate Banking Committee on Thursday, along with two other academic economists that Biden tapped to join the central bank's board of governors: Lisa Cook and Philip Jefferson. The nominees need to be approved by a simple majority vote in the Senate.                                                                                                                                                                                                                                         , As vice chair for supervision, Raskin – a Duke University law professor who has held high-level jobs at both the Treasury Department and the Fed – would oversee annual stress tests that review bank safety and liquidity. Her nomination has been welcomed by progressive senators and advocacy groups, who think she will take a tougher stance against Wall Street than her predecessor, Randal Quarles, a Trump nominee who stepped down last month.                                                                                                                           , But Republicans are already gearing up to fight Raskin's nomination as the Fed's top regulatory czar: A senior GOP aide told FOX Business that the party has "serious concerns" about her push to develop financial regulatory policies for cryptocurrencies and fighting climate change. Raskin's husband, Rep. Jamie Raskin, D-Md., also led the second impeachment trial of former President Trump.                                                                                                                                                                              , A man wearing a mask walks past the U.S. Federal Reserve building in Washington D.C., on April 29, 2020. (Xinhua/Liu Jie via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                                                                                           , Raskin previously served on the Fed's board from 2010 to 2014 and was tapped by former President Obama to serve as assistant Treasury secretary.                                                                                                                                                                                                                                                                                                                                                                                                                                    , Sen. Pat Toomey, the ranking member of the Senate Banking Committee, is expected to press Raskin over her view that federal policymakers take "bold actions" in order to avoid an "economic catastrophe" brought on by climate change. He also plans to question her calls for the Fed to allocate credit to businesses and deny credit to disfavored ones, such as oil and gas companies.                                                                                                                                                                                          , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , "I have serious concerns that she would abuse the Fed’s narrow statutory mandates on monetary policy and banking supervision to have the central bank actively engaged in capital allocation. Such actions not only threaten both the Fed’s independence and effectiveness, but would also weaken economic growth," Toomey, R-Pa., said in a statement.                                                                                                                                                                                                                             , Late last year, Biden nominated Chairman Jerome Powell to a second four-year term at the helm of the central bank, and picked current Fed Governor Lael Brainard as the Fed's second-in-command.                                                                                                                                                                                                                                                                                                                                                                                    , The White House has defended the nomination, with press secretary Jen Psaki telling FOX Business' Edward Lawrence on Monday that Raskin brings "unprecedented experience and the support of economic experts across the spectrum" to this role.                                                                                                                                                                                                                                                                                                                                     , "She believes, and she has said she believes firmly in the independent role of the Federal Reserve and will work in concert with her colleagues to identify and mitigate a range of risks," Psaki said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-31 22:23:48 </td>
   <td style="text-align:left;"> South Africa Trade Surplus Narrows in December </td>
   <td style="text-align:left;"> South Africa's trade surplus narrowed to ZAR 30.1 billion in December of 2021, from ZAR 35.8 billion in the previous month. Exports declined by a faster 3 percent from a month earlier, on lower sales of prepared foodstuff (-20%), precious metals and stones (-12%); base metals (-12 %) and vehicles &amp; transport equipment (-9%). Main export partners were the US (11.4 % of total sales), China (8.8%), Germany (8.2%), the UK (5.8%) and Japan (5.5%). At the same time, imports edged down 0.6 percent, due to reduced purchases of prepared foodstuff (-19%); chemical products (-16%); and machinery and electronics (-3%). Top import partners included China (24% of total purchases), the US (7%), India (6%), Saudi Arabia (5.7) and Germany (5.6%). Considering the full 2021 year, trade surplus widened to ZAR 440.8 billion from ZAR 271.5 billion a year earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/citrix-systems-private-16b-deal </td>
   <td style="text-align:left;"> 2022-01-31 22:13:42 </td>
   <td style="text-align:left;"> Citrix Systems going private in $16B deal </td>
   <td style="text-align:left;"> Former Reagan economist Art Laffer argues inflation is 'not under control yet' and says he is 'quite concerned about the next 12 months for the U.S. economy.'                                                        , Citrix Systems Inc. will be taken private in an all-cash acquisition by Vista Equity Partners and Elliott Investment Management LP valued at $16.5 billion, including the assumption of debt.                         , CATHIE WOOD’S ARK FACES LOYALTY TEST AFTER TECH-STOCK ROUT                                                                                                                                                            , Under the deal’s terms, Citrix stockholders will receive $104 a share. Elliott is participating in the acquisition through its Evergreen Coast Capital affiliate.                                                     , Citrix shares closed Friday at $105.55. The Wall Street Journal reported on Sunday that the deal, which had also been the subject of earlier media reports, was nearing completion.                                   , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                               , Vista and Evergreen plan to combine Citrix with Tibco Software, a Vista portfolio company. The move would create a software company with 400,000 customers and 100 million users in 100 countries, the companies said., Citrix headquarters in Santa Clara, California, U.S., on Wednesday, Jan. 19, 2022. (Photographer: David Paul Morris/Bloomberg via Getty Images) ( David Paul Morris/Bloomberg via Getty Image / Getty Images)         , Citrix will keep its name and its Fort Lauderdale, Fla. headquarters, the companies said. The deal is expected to close near the middle of 2022.                                                                      , To read more from the Wall Street Journal, click here.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-01-31 22:04:37 </td>
   <td style="text-align:left;"> Madrid Stocks Erase Gains </td>
   <td style="text-align:left;"> The IBEX 35 Index erased earlier gains to trade 0.3% lower at 8,580 on Monday, extending the previous week’s 0.8% loss, as investors digested a batch of economic data ahead of the UN Security Council’s meeting regarding the Ukraine crisis amid sanction threats from US senators and UK officials. On the corporate front, banks booked the steepest losses and traded 0.7% lower, driven by Banco Santander (-1.3%) and Caixabank (-0.7%). On the data front, preliminary estimates indicated Spain’s inflation rate eased to 6 percent in January, amid lower prices for electricity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/corn </td>
   <td style="text-align:left;"> 2022-01-31 22:04:00 </td>
   <td style="text-align:left;"> Corn Close to 7-Month High on Supply Concerns </td>
   <td style="text-align:left;"> Corn futures traded close to a 7-month high of $6.4 a bushel at the end of January on expectations of lower supply. A drought in South American top producing regions, especially in Brazil and Argentina is set to impact the quality of the harvest. Meanwhile, continued geopolitical tensions between Russia and Ukraine brought fears of export disruption from Ukraine, which is a major global corn supplier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-31 21:41:21 </td>
   <td style="text-align:left;"> Germany's 10Y Bund Yield in Positive Territory </td>
   <td style="text-align:left;"> The yield on Germany’s benchmark Bund spiked to a near three-year high of 0.026%, as traders digested inflation data against a backdrop of expectations of monetary policy tightening towards the end of the year. A preliminary estimate showed the annual inflation rate in Germany eased to 4.9% in January, from a near three-decade high of 5.3% in December but was still faster than market expectations of 4.3%. Meanwhile, investors are betting on a 10 bps rate hike in October, with the Deutsche Bank forecasting a 25 bps hike in December, although the ECB has continuously dismissed rate hikes this year. Still, the Federal Reserve’s hawkish signaling last week added pressure to the ECB over its forward guidance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-31 21:36:01 </td>
   <td style="text-align:left;"> UK 10Y Bond Yield Hits 34-month High </td>
   <td style="text-align:left;"> UK 10 Year Government Bond Yeld increased to a 34-month high of 1.301% </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-01 09:29:44 UTC +8

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
   <td style="text-align:left;"> 2022-02-01 09:29:27 </td>
   <td style="text-align:left;"> $SPY OMG ITS GONNA MOON  !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:29:27 </td>
   <td style="text-align:left;"> $SPY I think the Fed is trying to create uncertainty 
They’ve realized the power of narrative when you are a church. 
FED&amp;#39;S BARKIN: I&amp;#39;M NOT SEEING A DECLINE IN CORE DEMAND; IT&amp;#39;S NOT OUR PRIORITY TO BE CONCERNED ABOUT A RECESSION WHEN DEMAND REMAINS STRONG. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:29:11 </td>
   <td style="text-align:left;"> $SPY $QQQ Despite the rally from the last 2 sessions, the market remains oversold for the year and there is not much reason for people to take profits yet when the market is still down YTD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:28:57 </td>
   <td style="text-align:left;"> $SPY my positions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:28:44 </td>
   <td style="text-align:left;"> $SPY I want a refund, Tom Lee sold me calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:28:37 </td>
   <td style="text-align:left;"> $SPY why would you want to hurt a majestic animal bulls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:28:32 </td>
   <td style="text-align:left;"> $SPY lol bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:28:31 </td>
   <td style="text-align:left;"> $SPY damn futes sneezing, wheezing and Chris Breezing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:28:23 </td>
   <td style="text-align:left;"> $SPY Alright... which one of you that had puts expiring today did this?  
 
https://www.msn.com/en-us/news/us/man-charged-with-threatening-to-bomb-white-house-in-order-to-kill-joe-biden/ar-AATldyn?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:28:03 </td>
   <td style="text-align:left;"> $SPY bears need time machine, then maybe stand a chance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:28:02 </td>
   <td style="text-align:left;"> $SPY save your kids </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:27:27 </td>
   <td style="text-align:left;"> $SPY 
Guess what ... Inflation hasn’t left ...
Powell fucked you all with the over excessive asset buying ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:26:44 </td>
   <td style="text-align:left;"> Dark pool after hours activity in: 
 
$SPY - $100M print 
$IWM - $130M print 
$PM - $226M print 
$QQQ - $163M print 
 
#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:26:31 </td>
   <td style="text-align:left;"> $SPY Futes tippin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:26:21 </td>
   <td style="text-align:left;"> $SPY possibly the play or we just keep going up from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:26:17 </td>
   <td style="text-align:left;"> $SPY wait a min... 449 is rekt?!? lol wasn&amp;#39;t this 420... 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:25:47 </td>
   <td style="text-align:left;"> $SPY $NASDAQ https://youtu.be/P3Xl0DS-TP4 misery loves company. Says never to go cash and keeps doubling down on unprofitable companies . Even bragging about gains on call options he bought today  🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:25:25 </td>
   <td style="text-align:left;"> $SPY Bulls - Who is getting in this sleeping bag ( that smells like cigs )  with this Bear tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:25:18 </td>
   <td style="text-align:left;"> $SPY futures getting whacked. Meaning back to $426? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:25:08 </td>
   <td style="text-align:left;"> $SPY Next year this time we’ll see 550 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:24:19 </td>
   <td style="text-align:left;"> $SPY Why is everybody so obsessed with with Biden.. as a kid I grew up without shampoo ..washed my hair with bar soap.. Lifebuoy if we were flush with money Lava if we weren&amp;#39;t.. I remember my first shampoo experience with Pert. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:24:18 </td>
   <td style="text-align:left;"> $SPY futes be like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:24:13 </td>
   <td style="text-align:left;"> $SPY I don’t think I have ever seen futes this red before.. my fellow bears tomorrow is our day. SPY 460 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:24:11 </td>
   <td style="text-align:left;"> $SPY uh oh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:23:16 </td>
   <td style="text-align:left;"> $spy $btc.x $twtr 

Can someone please explain to me the Liberal Logic of how the Canadian Trucker protest is “racist?” 

That’s a crazy stretch even for the “everything is racist” people… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:23:10 </td>
   <td style="text-align:left;"> $SPY, you have no clue what is coming. Unfortunately, like always, I&amp;#39;m ahead of the market few weeks. But it&amp;#39;s good to notify people. I feel better. Look at this; it&amp;#39;s not a joke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:23:06 </td>
   <td style="text-align:left;"> $SPY This will be a very interesting week. We retraced half the drop. There will be some major resistance test(s). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:22:53 </td>
   <td style="text-align:left;"> $SPY 20% growth in the last year is absolutely not sustainable. Get your head out your ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:22:44 </td>
   <td style="text-align:left;"> $SPY Buy ES calls here.. this will open flat to green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:21:55 </td>
   <td style="text-align:left;"> $SPY Futes ripping 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:21:54 </td>
   <td style="text-align:left;"> $SPY omg this tiramisu is deadly lol no you can&amp;#39;t have any yogi 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:21:50 </td>
   <td style="text-align:left;"> $SPY biggest bull trap in history 🔪🔪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:21:48 </td>
   <td style="text-align:left;"> $SPY it’s definitely going to go up or down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:21:37 </td>
   <td style="text-align:left;"> The S&amp;amp;P 500 Index has averaged an unchanged result in the month of February over the past 20 years with 60% of periods ending higher. http://www.equityclock.com/2022/01/31/stock-market-outlook-for-february-1-2022/ $STUDY $SPX $SPY $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:21:30 </td>
   <td style="text-align:left;"> $SPY 
Will Wallstreet laugh off a bulltrap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:20:58 </td>
   <td style="text-align:left;"> $SPY buy the earnings hype, sell before it gets released. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:20:50 </td>
   <td style="text-align:left;"> $SPY the suits are a little too anxious        calling for a mulligan..ERRRRR …pullback. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:20:44 </td>
   <td style="text-align:left;"> $SPY needs to retest the 200sma, most likely but ww here if 20ema rejects https://youtu.be/iZ1v89h_xP4 $IWM $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:20:44 </td>
   <td style="text-align:left;"> $SPY need NVDA to open up 3%+ and I’m set for the month of February god please hear my prayers 🙏 $NVDA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:20:04 </td>
   <td style="text-align:left;"> $SPY $NASDAQ all the bulls claiming bear market dead and we bottomed. True comedy! Fedora boy is a class act tho 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:19:49 </td>
   <td style="text-align:left;"> $SPY Is this max pain or is that 454. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:19:43 </td>
   <td style="text-align:left;"> $SPY 
He is on the rocket 🚀 token life of fighting death from an wealthy eyes 👀 trade with caution </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:19:42 </td>
   <td style="text-align:left;"> Great post $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:19:37 </td>
   <td style="text-align:left;"> $SPY chart looks like a crash up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:19:03 </td>
   <td style="text-align:left;"> $SPY $QQQ So the market in Singapore and South Korea are closed today too? I didn&amp;#39;t know these countries celebrate Chinese New Year too lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:18:21 </td>
   <td style="text-align:left;"> $SPY the financial media industry are leeches. Most of their stock recs over the past year are down over 50%.  
Palantir...the Amazon of X, Y, Z 
Why buy Palantir if you can just buy Microsoft. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:18:05 </td>
   <td style="text-align:left;"> $SPY could be the previous Santa Claus run 5 days (Friday was the first) into EOW.  I usually do the opposite but has the feel with earnings and kick start of Olympics.  Took some profits so worth a shot.  Insane 2 days.  May we all make money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:18:03 </td>
   <td style="text-align:left;"> $SPY Guess what I bought hedges cause I&amp;#39;m a loser. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:17:46 </td>
   <td style="text-align:left;"> $SPY 460 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:17:15 </td>
   <td style="text-align:left;"> $SPX $SPY S&amp;amp;P 500 managed to close above the Dec lows. More inflation data out tomorrow (PMI/ISM manufacturing, construction spending) and Jan NFP on Friday. See if we get some more follow-through this week. Very high Put/Call ratio last week (seems like everyone&amp;#39;s all hedged up for a crash) and we didn&amp;#39;t get that selloff in the final hour (outside of a Friday close) today for once. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:16:30 </td>
   <td style="text-align:left;"> Appreciate the people who were there for you while you was at your lows $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:16:11 </td>
   <td style="text-align:left;"> $SPY futures going to get ugly https://youtu.be/K1bK-8L54fU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:15:38 </td>
   <td style="text-align:left;"> $SPY to all illusionists: 
market was oversold, and this counterattack was because of technical reasons; the geometry of the chart should be correct. Any spike is just a short opportunity for smart money and a bull trap. My evidences are: 
1- market imbalance for the last two sessions was 5.6B buy-side, which means they dumped their expensive shares and dump-money bought it. 
2- check the PUT premiums on indices and specifically on SPX. 
more than 200m$ PUT for SPX opened between 3:30 and 4:15 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:15:30 </td>
   <td style="text-align:left;"> $SPY imma need tomorrow to reverse today&amp;#39;s gains completely. 

I&amp;#39;m still bearish on $dash $bidu &amp;amp; semiconductors. 

I am willing to change my semi conductor stance though for bullish $ups or $nke 

Nike price action is stronger than the chart. Even on deep red days with spy, Nike was green most of the day. This is something you notice only if you&amp;#39;re looking. 

Anyway, I also understand my own advice: the market is under no obligation to do what I want it to do; nor is it subject to my opinion. 

I will take the losses on bidu and dash and semis and spy shorts if I must. But I&amp;#39;m still trading my plan. 

Just damn my plan sucking right now. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:15:22 </td>
   <td style="text-align:left;"> Bear market rallies $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:15:12 </td>
   <td style="text-align:left;"> $SPY My sources tell me they&amp;#39;ll expire worthless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:15:05 </td>
   <td style="text-align:left;"> $SPY 
The 450 wall of death 💀💀💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:14:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Many of these bears must be new traders lol. 125 basis points is already priced in and the companies that have reported numbers particularly in tech are exceptional. The cash positions many of these companies have can eat up these shares for lunch. All these clown bears were telling me on Friday and the weekend that we would be down big today and even this past Friday and yet they were squeezed. There will be fluctuations of course but most of the bears on here are just plain dumb lol. You can try and time markets but for the most of you brainless bears you will never beat long term investor gains. Thats why 99 percent of traders fail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:13:50 </td>
   <td style="text-align:left;"> $SPY crash confirmed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:13:48 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/jmhansler/status/1488311341505036290?s=21

Evacuating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:13:47 </td>
   <td style="text-align:left;"> $SPY $AAPL $NVDA $AMZN $TSLA 

Daily reminder to keep investing, keep compounding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:13:45 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:13:16 </td>
   <td style="text-align:left;"> $SPY $TSLA  it takes a  diabolical mind to  outwardly support  the Canadian Truckers  protest while simultaneously building the very trucks intended to replace them..... 
 
https://nypost.com/2022/01/31/cops-investigating-after-protesters-allegedly-urinated-on-canadian-monuments/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:13:10 </td>
   <td style="text-align:left;"> $SPY this aged well 🥲 📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:13:00 </td>
   <td style="text-align:left;"> $SPY $QQQ At EOD today, bears were telling themselves... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:12:35 </td>
   <td style="text-align:left;"> $SPY What do you think of Trump&amp;#39;s offer to pardon 1/6 folk and a call for protests if he is criminally  charged? 
To me it sounds like he is desperate and scared. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:12:32 </td>
   <td style="text-align:left;"> $SPY lmao these people are so dumb it blows my mind, clown world 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:11:47 </td>
   <td style="text-align:left;"> $SPY honestly, you deserve to lose money if u are still holding calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:11:24 </td>
   <td style="text-align:left;"> $SPY how??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:11:21 </td>
   <td style="text-align:left;"> $SPY green or red tomorrow🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:10:43 </td>
   <td style="text-align:left;"> $SPY I know violent rally will take us to violent 410 or below. Buying the dip will lead to catching falling knife 🔪 soon. I can’t wait for some to start shouting Biden name and some 🤡 calling for emperor ruler Trump to be reinstated as president ✍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:10:42 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:10:38 </td>
   <td style="text-align:left;"> $SPY people on CNBC should be ashamed. All their talking heads either evoking fear or trying to time the market, meanwhile Warren Buffett and index holders literally do nothing except use their income to automatically buy their index and drastically outperform every &amp;quot;stock market specialist&amp;quot; and &amp;quot;financial advisor&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:09:59 </td>
   <td style="text-align:left;"> $SPY 

Yield curve and spy 

Will try to post everyday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:09:09 </td>
   <td style="text-align:left;"> $SPY Russian invasion imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:09:06 </td>
   <td style="text-align:left;"> $SPY https://open.spotify.com/episode/3OpBGuOSfKH6CkdUxBQWy1?si=SDh8UfhKQdyekW5YMQuBSQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:08:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA just watching Tom Lee’s bit on Fast Money. V is for Violent Rally in February? Who’s paying him to say this??? 🙄

F is for Flush. As in we’re going to Flush back down to 4200 by mid-February. 

Only thing bullish i see in February is the Olympics, which could cool off geo-political crises for a couple weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:07:44 </td>
   <td style="text-align:left;"> $SPY personally expect 452 to 455 tomrrow before a drop to 445 then uptrend continuation this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:07:23 </td>
   <td style="text-align:left;"> $SPY ultimately I just want biotechs to start running again. When $XBI  was cooking late 2020 and early 2021 was the most fun the markets ever been. Really fits my skill set way better. Ultimately don’t expect them to really heat up again for quite a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:06:52 </td>
   <td style="text-align:left;"> $SPY thought OFG would be out fighting bears after the last two sessions.  I&amp;#39;m kinda worried. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:06:19 </td>
   <td style="text-align:left;"> $SPY going to be so red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:06:09 </td>
   <td style="text-align:left;"> latexc7f9a19b8ca47e40a2389b805901057f 
405$ 
GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:05:49 </td>
   <td style="text-align:left;"> $SPY - Tom Lee says he expects a &amp;quot;violent rally&amp;quot; in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:05:34 </td>
   <td style="text-align:left;"> $SPY / $QQQ bears just got gaped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:05:32 </td>
   <td style="text-align:left;"> $SPY $PFE $BLK  See $SPOT run.  
Run Spot run! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:05:06 </td>
   <td style="text-align:left;"> $SPY    **updated Rkt jan 26  #MrsButtersworth chart. 
 
&amp;#39; if&amp;#39;    #Rocket Mortgage is next in the squeeze list, then a break over  white 26 candle average line  ( 13.75 ish) then $15&amp;#39;s by Friday /early next week very  very possible/likely..   short interest  still very very high.. 
$HOOD and other small names with high short interest had some CALL buying past few days/today in Hood..   someone looks interested in the  mid $12&amp;#39;s   on chart in $RKT 
 
#LeggoMyEggo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:04:58 </td>
   <td style="text-align:left;"> $SPY if FB tanks this week I wouldn’t expect lower than SPY 436 and it would rip absolute face from there IMO. Honestly 442 is going to be a son of a bitch to break below 444 which is the first bitch. In other words bears r fuk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:04:43 </td>
   <td style="text-align:left;"> $SPY futes seem to be futing can anyone confirm?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:04:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $UUP

Daily Market Recap for Monday 1/31/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/jJ2iFq_WIcM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:04:20 </td>
   <td style="text-align:left;"> $SPY stuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:03:59 </td>
   <td style="text-align:left;"> $SPY after buying 59 more 422. I&amp;#39;m feeling pretty good. I never thought we would see 430 again. I&amp;#39;ll buy more if we do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:03:55 </td>
   <td style="text-align:left;"> $QQQ $SPY bears are disheartened. Most had to cover. Shorting is rocket science. Most bears don’t understand that. 

When bears are rare it will collapse again. Markets may go up another 1% to 5%. Then the crash will be nasty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:03:25 </td>
   <td style="text-align:left;"> $SPY turbulent times are over. What was that? Like 2 weeks? Back to normal. Also $FB looks spicy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:03:13 </td>
   <td style="text-align:left;"> $SPY bears fooked.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:02:46 </td>
   <td style="text-align:left;"> . $SPY . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:02:38 </td>
   <td style="text-align:left;"> $SPY wow, futures are barely down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:02:31 </td>
   <td style="text-align:left;"> $SPY I know a good percentage of you guys despise Cramer for one reason or another. However, I’ve made money with his calls. 

Sharing some information for all long bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:02:19 </td>
   <td style="text-align:left;"> $SPY down tomorrow to test the 200 then bounce Wednesday &amp;amp; Thursday to 456 zone. Then back to downtrend Friday thru next week. Trust the science bro </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:02:14 </td>
   <td style="text-align:left;"> $SPY trash
 https://www.tradingview.com/chart/NAS100/p0QW0Xkm-NAS100-Fallout-Buyer-BEWARE-Growth-at-all-Costs-is-No-More/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:01:53 </td>
   <td style="text-align:left;"> $SPY Draft the children 13-18, we need the young adults for the economy and jobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:01:42 </td>
   <td style="text-align:left;"> $SPY let’s go higher! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:01:32 </td>
   <td style="text-align:left;"> $dwac $spy 😵‍💫🤘

https://youtube.com/watch?v=zsFXW01xfmg&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:01:25 </td>
   <td style="text-align:left;"> $BTC.X $SPY Pushing P </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:01:22 </td>
   <td style="text-align:left;"> $SPY  narrative flip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:01:07 </td>
   <td style="text-align:left;"> $SPY gonna stay up all night waiting for Nigeria to report GDP hoping my FD puts print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 09:00:16 </td>
   <td style="text-align:left;"> $SPY canadian truckers have now setup a blockade at the US Canada border. Canadian meat companies are already tweeting about disruptions. US truckers also preparing to strike. Supply chain is about to get wrecked. 

Prepare now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:59:45 </td>
   <td style="text-align:left;"> $SPY this is a scam market. 
Overall bearish. Who gives a fuck how it goes tomorrow. 
No one knows. Stop day trading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:59:09 </td>
   <td style="text-align:left;"> $SPY Biden likes ice cream 🍦 https://youtu.be/tt_04EYIM-c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:58:57 </td>
   <td style="text-align:left;"> $SPY fake news bears. Putin, Kim
Jung Un and Xi will declare world peace tonight and SPY will open at $460 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:58:56 </td>
   <td style="text-align:left;"> $SPY  
 
Returning nightmares, only shadows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:58:46 </td>
   <td style="text-align:left;"> $SPY too good. 🤣💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:58:44 </td>
   <td style="text-align:left;"> $SPY Farting in Okracoke... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:58:25 </td>
   <td style="text-align:left;"> $DWAC $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:57:27 </td>
   <td style="text-align:left;"> $SPY what if turnaround Tuesday means red now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:57:03 </td>
   <td style="text-align:left;"> $SPY There will be blood tomorrow. Green blood. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:56:30 </td>
   <td style="text-align:left;"> Best performing $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:56:19 </td>
   <td style="text-align:left;"> Assets $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:56:13 </td>
   <td style="text-align:left;"> $SPY squeezing a bit more green out the lemon tmrw before a bit of downtrend Wednesday/Thursday? What do y’all think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:56:11 </td>
   <td style="text-align:left;"> $QQQ $SPY  Everyone needs to chill. This totally looks like a drill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:56:09 </td>
   <td style="text-align:left;"> If your $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:55:56 </td>
   <td style="text-align:left;"> $SPY if this area doesn&amp;#39;t act like resistance we will know that the crash was an overreaction to the feds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:54:04 </td>
   <td style="text-align:left;"> $SPY 

The tyrant xi still sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:53:55 </td>
   <td style="text-align:left;"> $SPY I wanna see Biden pass a 5th grade spelling test right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:53:53 </td>
   <td style="text-align:left;"> $SPY 
454 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:53:08 </td>
   <td style="text-align:left;"> $SPY  I’m just fascinated by financial markets. Would I still be as fascinated if money wasn’t involved? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:52:51 </td>
   <td style="text-align:left;"> $SPY semi conductors ripped my face off today. Hopefully this is just a bull trap but I won&amp;#39;t try to hold Bearish past tomorrow if this keeps up. 

I knew I wouldn&amp;#39;t be able to watch the market this week so I withdrew over 80% of my account value last week. Keep that money safe in my wallet. Ain&amp;#39;t gonna let the market take it away from me. 

If Iose my play money, it&amp;#39;ll suck, but whatever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:52:23 </td>
   <td style="text-align:left;"> $SPY I made great money on this pump today. but this bounce will just lead to a fat bubble bursting.  SPY to 400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:52:13 </td>
   <td style="text-align:left;"> $SPY grilling some worthless puts lmaoo just Zelle me your money instead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:51:33 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/jus6LaMTZKM🪖🪖🪖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:51:22 </td>
   <td style="text-align:left;"> $SPY bullish on nba youngboy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:51:19 </td>
   <td style="text-align:left;"> $spx $spy historical framing exercises. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:51:14 </td>
   <td style="text-align:left;"> $SPY 

The ugly charts is for bears 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:51:02 </td>
   <td style="text-align:left;"> $SPY ES_F 4522 pump for you all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:50:53 </td>
   <td style="text-align:left;"> $SPY I can see a test of the 200Day Moving Average tomorrow for confirmation of today&amp;#39;s move..   To get ES to roll over tonight, they might pump the US2,10,20Y &amp;amp; DXY tonight..  If SPY retests the 200 day and fails to break down through it., then I can see $455-460 by Wednesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:50:41 </td>
   <td style="text-align:left;"> $SPY futes ripping in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:50:31 </td>
   <td style="text-align:left;"> $SPY 

Draw a dumb chart draw a line 

Get mad if the real price doesn’t fit 

That’s most bear cubs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:50:27 </td>
   <td style="text-align:left;"> $SPY Remember everyone, it is not a sin to be stupid. $WM needs employees too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:50:20 </td>
   <td style="text-align:left;"> $SPY there’s no selling pressure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:49:37 </td>
   <td style="text-align:left;"> $SPY gonna give selling to short at 462 a try </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:49:37 </td>
   <td style="text-align:left;"> $SPY uh oh bears I heard there’s a violent rally coming not good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:49:05 </td>
   <td style="text-align:left;"> $SPY sitting on the 50% ($450.37) Fibonacci retracement  level. 

Going over will signal to a lot of traders correction is done. 

Turning around here could prove that this is the top of the first wave on the way down further. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:48:50 </td>
   <td style="text-align:left;"> $SPY what are we waiting for let&amp;#39;s rip we all know its no going down the keep holding 4500 up so let&amp;#39;s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:48:34 </td>
   <td style="text-align:left;"> $SPY things are getting real interesting just remember when the market cools off in a few days stop buying options 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:47:55 </td>
   <td style="text-align:left;"> $SPY I see people bearish on this. I think thanks to $AAPL  $SPY has more to go. Profit from this was good today expecting more to come.  Follow me on Twitter and iG especially for alerts @mrscalikisses thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:47:22 </td>
   <td style="text-align:left;"> $SPY Cramer is really just a tool. I&amp;#39;m surprised people listen to him. I guess media glorifies idiots. 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:46:44 </td>
   <td style="text-align:left;"> $SPY $430 eow. 

Maybe even $429.99 idk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:46:43 </td>
   <td style="text-align:left;"> $SPY not saying it’ll happen, but bulls would you be mad if you saw 436 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:46:39 </td>
   <td style="text-align:left;"> $SPY Ath this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:46:07 </td>
   <td style="text-align:left;"> $SPY gap up tomorrow? Back to 4700 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:45:37 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:45:29 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Honestly... If I was in charge? 

Vaccinations would be mandatory and done by force if necessary. It would be door to door motherfucker. You’re bullshit “freeDUM” argument that you somehow have a right to not have a bare minimum level of buy in to participate in society gets shut down like Washington did when he inoculated the continental army in 1776. 

“I have determined that the troops shall be inoculated ... Necessity not only authorizes but seems to require the measure, for should the disorder infect the Army in the natural way and rage with its usual virulence we should have more to dread from it than from the Sword of the Enemy.” - George Washington </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:44:51 </td>
   <td style="text-align:left;"> $SPY r we goin to catwalk thru that 2yr broken trendline without even 1 rejection ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:44:37 </td>
   <td style="text-align:left;"> $SPY The selling pressure has dried up confirmed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:44:23 </td>
   <td style="text-align:left;"> $GM $SPY  GM coming up off the lows minimum upside target $60. 1-3 month exp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:44:21 </td>
   <td style="text-align:left;"> $SPY retest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:43:46 </td>
   <td style="text-align:left;"> $SPY  $QQQ Futures need to decline more overnight in order to red market tomorrow ; otherwise will be another green push tomorrow … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:43:12 </td>
   <td style="text-align:left;"> $SPY ok I was super bullish for the past 2 sessions but now we obviously due for a retest of support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:43:07 </td>
   <td style="text-align:left;"> $SPY $QQQ Its going to be a looong night for these silly bears. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:42:56 </td>
   <td style="text-align:left;"> $SPY my 89 year-old double vaxxed and boosted Republican father still thinks blacks are uppity.. I consider this to be anecdotal rather than ironic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:42:46 </td>
   <td style="text-align:left;"> $SPY cramer says do some selling on stuff that been hammered off the highs, rates gonna be front loaded $AAPL $AMZN $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:41:58 </td>
   <td style="text-align:left;"> $SPY bulls got tom lees 🍆 in their mouth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:41:49 </td>
   <td style="text-align:left;"> $SPY Remember Jim Cramer is bullish!

Time to buy now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:41:49 </td>
   <td style="text-align:left;"> $SPY looking like rest of this week gonna be bloody... strong likelihood its coming back to the bottom of this channel tomorrow.  Dont get upset its just my thesis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:40:50 </td>
   <td style="text-align:left;"> $SPY as someone with a lot riding on a drop tomo I’m very conceded that futures are red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:40:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $IPOF did anyone get homesick when they went to uni? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:40:28 </td>
   <td style="text-align:left;"> $SPY retarded bulls are fun, two session green because of technical and they think all the issues solved. Let me list for you what we have on the table:
1-inflation
2- over valued tech bubble
3- confirmed bear price action for 60% of the stocks(they are below 200MA and price declined more than 50%)
4- china slow down growth( US economy is defendant to their growth)
5- Real State issues in China
6- Russia and Ukraine conflict
7- China and Taiwan Conflict
8- FED interest rate uncertainty ( 3 to 7 )
9- Supply Chain Management issue
10- Biden 2.5T$ Priced in  market value that should be remove from indices,  it was added to price in Jan.

Good Luck all Bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:40:22 </td>
   <td style="text-align:left;"> $SPY things are looking up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:40:17 </td>
   <td style="text-align:left;"> $SPY what is your favorite futures trading mobile app? I will start. TOS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:40:12 </td>
   <td style="text-align:left;"> $SPY is Joe Flacco, elite? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:40:00 </td>
   <td style="text-align:left;"> $SPY has a poor technical rating and the quality of the setup is also not perfect at the moment. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:39:25 </td>
   <td style="text-align:left;"> $SPY Yall got me geeked tonight lmaooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:39:15 </td>
   <td style="text-align:left;"> $SPY 
AAAAWWWWW SSSHHHIIIIEEEETTTT

https://www.cnbc.com/2022/01/31/bank-of-england-expected-to-impose-back-to-back-rate-hikes-for-the-first-time-since-2004.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:39:10 </td>
   <td style="text-align:left;"> $SPY Thought I saw a Bear 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:38:53 </td>
   <td style="text-align:left;"> $SPY let me pump future for you all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:38:48 </td>
   <td style="text-align:left;"> $SPY Remember BULLS 🐂💰🐂💰💰🐂💰🐂🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:38:28 </td>
   <td style="text-align:left;"> $SPY who bought 0dte puts at open today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:37:55 </td>
   <td style="text-align:left;"> $SPY $HD $DE $UNP just had to invest in boomer stocks.. no up or down just.. boring quarterly dividowns? Dividuans? whatever theyre called. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:37:49 </td>
   <td style="text-align:left;"> $SPY Vix term structure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:37:46 </td>
   <td style="text-align:left;"> $SPY TOM LEE SAID BUY THE DIP..🤥🤥🤥🤓🤓🤓🤭🤭🤭🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:37:12 </td>
   <td style="text-align:left;"> $SPY I am seeing a lot of disguised butt hurt Bear posts right now without saying it lol  🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:37:02 </td>
   <td style="text-align:left;"> $SPY bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:37:01 </td>
   <td style="text-align:left;"> $SPY alerted in our free discord Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:36:36 </td>
   <td style="text-align:left;"> $SPY So what was Cramers “expert” analysis tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:36:23 </td>
   <td style="text-align:left;"> $SPY fake bounce, printer stopped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:36:12 </td>
   <td style="text-align:left;"> $SPY please lord +5% green futes so this opens -6% tomo 🙏🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:36:03 </td>
   <td style="text-align:left;"> $spy $btc.x 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:35:58 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:35:55 </td>
   <td style="text-align:left;"> $SPY Surprised Jim Cramer is not in jail already. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:35:34 </td>
   <td style="text-align:left;"> $SPY https://stocktwits.com/OptionRunners/message/432116203 
 
$ES_F did open below monthly uptrend support. Resistance at 4,525 on a re-test. 
 
I think we&amp;#39;re heading back for the January lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:35:08 </td>
   <td style="text-align:left;"> $SPY COPENHAGEN (Reuters) - The BA.2 subvariant of the Omicron coronavirus variant, which has quickly taken over in Denmark, is more transmissible than the more common BA.1 and more able to infect vaccinated people, a Danish study has found. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:35:03 </td>
   <td style="text-align:left;"> $SPY WTF.  Futres were good green.  then all of a sudden red.  :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:34:59 </td>
   <td style="text-align:left;"> $SPY bullish on my portfolio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:34:50 </td>
   <td style="text-align:left;"> $SPY will the fed commit to one rate hike in March at least? Jeez. Won&amp;#39;t even commit to that which is why my first baby mama left me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:34:31 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m bearish stock twits &amp;amp; Nancy.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:34:29 </td>
   <td style="text-align:left;"> $SPY 

Over 4% in 2 days……probably takes a break tomorrow and gives the bears something to nibble on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:33:52 </td>
   <td style="text-align:left;"> $SPY We all know it.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:33:50 </td>
   <td style="text-align:left;"> $spy $btc.x 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:33:09 </td>
   <td style="text-align:left;"> $SPY this board gives me anxiety </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:32:26 </td>
   <td style="text-align:left;"> $SPY VIX going to crater tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:32:19 </td>
   <td style="text-align:left;"> $SPY shorted 450. Holding 2/11 440 p 3.74 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:32:13 </td>
   <td style="text-align:left;"> $SPY futes are futin’ is it bear hunting season yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:31:59 </td>
   <td style="text-align:left;"> $SPY bunch of ironic know nothing know it alls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:31:45 </td>
   <td style="text-align:left;"> $SPY Tom Lee says it&amp;#39;s going to rip. It WILL fucking rip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:31:45 </td>
   <td style="text-align:left;"> $SPY 😂🐻😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:31:40 </td>
   <td style="text-align:left;"> $SPY tech rally tomorrow while Dow an SPY sell off……🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:31:31 </td>
   <td style="text-align:left;"> $SPY I got qqq puts… am I screwed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:30:51 </td>
   <td style="text-align:left;"> Who else got in some $SPY and $AAPL calls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:30:45 </td>
   <td style="text-align:left;"> $SPY dix moved higher today😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:30:32 </td>
   <td style="text-align:left;"> $SPY I will come out of disbelief at 515 until then this rally will fail like the others </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:30:26 </td>
   <td style="text-align:left;"> $ARVL $SPY $QQQ 

ARVL is Very active after hours. Good volume. 

People getting ready for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:29:14 </td>
   <td style="text-align:left;"> $SPY Remember, if you had to give up your job in capital markets for CNBC, then you have absolutely no idea what you’re doing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:28:42 </td>
   <td style="text-align:left;"> $SPY all of my btches got friends
Amd they bad they bad, so we’re good
Just enough for the clique </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:28:42 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ .    #zucchini </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:28:29 </td>
   <td style="text-align:left;"> Bill and Melinda Gates Foundation Pledges $5 Billion to Fight AIDS in Africa | National News | US News $IBRX $SPY $XBI $LABU. With this data news can we tap into this Bill Gates $$.  https://www.usnews.com/news/articles/2016-07-18/bill-and-melinda-gates-foundation-pledges-5-billion-to-fight-aids-in-africa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:28:28 </td>
   <td style="text-align:left;"> $SPY let’s get these ERs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:28:23 </td>
   <td style="text-align:left;"> $SPY Investing.com has some of the most trusted and experienced experts in economics on the forums </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:28:12 </td>
   <td style="text-align:left;"> $SPY bears today circle jerkin each other muh rate hikes derrrrrp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:27:58 </td>
   <td style="text-align:left;"> $SPY $QQQ This will go higher this week to test EMA&amp;#39;s on 4 hour and daily and resistance on weekly and they all point towards $4580 on futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:27:46 </td>
   <td style="text-align:left;"> $SPY calls definitely printed today. Bears are salty cause they wanna feel like they are Michael fuckin Burry shorting the housing market in 08. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:27:25 </td>
   <td style="text-align:left;"> $SPY if you fuck this bull rally up Cramer I’ll never say anything bad about you again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:27:07 </td>
   <td style="text-align:left;"> $FNGU $TQQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:27:07 </td>
   <td style="text-align:left;"> $SPY bears r fuk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:26:50 </td>
   <td style="text-align:left;"> $spy $qqq $iwm $btc.x https://www.youtube.com/watch?v=37aoAp8sALU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:26:44 </td>
   <td style="text-align:left;"> $SPY (if we can hold $448 tomorrow) there is not much supply until $456. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:25:59 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:25:58 </td>
   <td style="text-align:left;"> $SPY layup line, she was practice 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:25:57 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
https://www.youtube.com/watch?v=Ys5NlAoI2HA 
 
Tom Lee is bullish for February </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:25:52 </td>
   <td style="text-align:left;"> $SPY 

Yeehaw got my spy dividend today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:25:43 </td>
   <td style="text-align:left;"> $SPY more green coming tomorrow..get ready for max pain bears!! 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:25:35 </td>
   <td style="text-align:left;"> $SPY if you’re down on your luck maybe try the Costanza method https://youtu.be/rag0Z1nTJOc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:25:11 </td>
   <td style="text-align:left;"> $SPY It’s funny to realize that most bears yell bearish all day but hold calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:25:07 </td>
   <td style="text-align:left;"> $SPY bearsncan only hope tomorrow is better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:24:35 </td>
   <td style="text-align:left;"> $SPY bears are so bitter, how&amp;#39;s that 9-5 treating you? LOL. Just because you want the system to collapse so your boring life becomes a little more exciting doesn&amp;#39;t mean it&amp;#39;s actually gonna happen. Stop living in a fantasy world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:24:11 </td>
   <td style="text-align:left;"> $SPY 02/02/2022= 10

10 in Binary is yes.

Confirmation that ATH will be reaches by 02 feb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:24:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $NDX 
 
Fear Greed Index (CNN) is still in FEAR. we have much room to go up.  
 
AAII has never been so BEARISH. We have to much room to go up too. 
 
What is the reason to go down? I we have to go down, first we have to correct this bearish sentiment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:24:06 </td>
   <td style="text-align:left;"> $SPY cy·cli·cal 
&amp;quot;tough times create strong men 
strong men create easy times 
easy times create weak men 
weak men create tough times&amp;quot; Wojak. 
https://www.youtube.com/watch?v=83PtLd7QoD0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:24:06 </td>
   <td style="text-align:left;"> $SPY 
475 to 480 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:24:04 </td>
   <td style="text-align:left;"> $SPY Tom V SHAPED VIOLENT RALLY LEE!!  We did it!  Crushed the bear whale </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:24:04 </td>
   <td style="text-align:left;"> $SPY good luck holding this overnight.  Option hedges going to unwind hard if we simply pause. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:23:45 </td>
   <td style="text-align:left;"> $SPY  
 
Where did you get poked and does this refute the axiom? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:23:42 </td>
   <td style="text-align:left;"> $SPY bullish 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:23:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $AMZN 

35500 will be the top for the year for dow and all index tomorrow. Be prepared to short the crap out of the market tomorrow. For puts wait for some IV crush before loading. There might be some consolidation before the move down.  After tomorrow we will see the biggest correction since 2008. 
21700 is where the buck stops for dow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:23:25 </td>
   <td style="text-align:left;"> $SPY $QQQ f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:23:18 </td>
   <td style="text-align:left;"> $spy $dia $spx https://www.youtube.com/watch?v=4TqM0peojuk&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:23:07 </td>
   <td style="text-align:left;"> $SPY oversold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:22:59 </td>
   <td style="text-align:left;"> Stock Pick of the Month - February 2022  
$ALLY $SPY  
 
https://youtu.be/HKZORMcEyNU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:21:50 </td>
   <td style="text-align:left;"> $SPY Hourly RSI overbought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:21:46 </td>
   <td style="text-align:left;"> $SPY Bull are Boring Bots. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:21:41 </td>
   <td style="text-align:left;"> $SPY bears talking smack now, they same shit as last night. How’s that work out losers???😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:21:31 </td>
   <td style="text-align:left;"> $SPY 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:21:26 </td>
   <td style="text-align:left;"> $SPY  Reality check coming tomorrow bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:21:16 </td>
   <td style="text-align:left;"> $SPY Nice continuation after closing back above the 200 day average Friday 
https://share.trendspider.com/chart/SPY/66823diyjj </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:20:33 </td>
   <td style="text-align:left;"> $SPY It’s time to short dog walking businesses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:20:26 </td>
   <td style="text-align:left;"> $SPY Finished closing my last active position. Hoping for some bio P&amp;amp;D action tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:20:14 </td>
   <td style="text-align:left;"> $SPY 

Shepherd Smith is a sick lib… can’t I just turn on CNBC during dinner to watch Finance !?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:20:05 </td>
   <td style="text-align:left;"> $SPY can’t wait for tomorrow 🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:20:01 </td>
   <td style="text-align:left;"> $SPY 472 coming in couple of days. Watch and learn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:19:59 </td>
   <td style="text-align:left;"> $SPY CRAMER $BTC.X $FJIM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:19:50 </td>
   <td style="text-align:left;"> $SPY Red Futes … now I know for sure we’re going higher!😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:18:20 </td>
   <td style="text-align:left;"> $SPY reading this board is like reading a shitty horoscope. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:18:05 </td>
   <td style="text-align:left;"> $SPY @TraderLeibniz 
since you like mcclellan 
 exhaustion signal was a powerful indication on 1/27 for what came next on both 1/28 and today. 

But that doesn&amp;#39;t mean we have an all clear. It just means we&amp;#39;ve seen the oversold condition from exhaustion selling worked through. 

Be careful with volatility both ways. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:18:02 </td>
   <td style="text-align:left;"> $SPY Did you catch the bottom with me last week? Very complicated trade here. Absolutely amazing when you learn how to identify direction the Market will take after such negative sentiment.✅👏 #SPY #stockMatket #investing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:17:44 </td>
   <td style="text-align:left;"> $SPY Tuesday is generally a RED day. Just putting it out here! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:17:41 </td>
   <td style="text-align:left;"> $SPY Jim Cramer went bullish. LETS GOOOOOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:17:35 </td>
   <td style="text-align:left;"> $IBRX 1 min ago. $XBI $LABU $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:17:08 </td>
   <td style="text-align:left;"> $SPY Don&amp;#39;t get scared if this is dumped 3-4% tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:17:08 </td>
   <td style="text-align:left;"> $SPY  
 
TINA ignored the safe word today 
 
SPY $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:16:41 </td>
   <td style="text-align:left;"> $SPY $AAPL $TQQQ $SOXL  Whoever invented the squeeze momentum indicator is a genius </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:16:22 </td>
   <td style="text-align:left;"> $SPY not even moving on negative futes. Nobody give a fuck about them until open unless they&amp;#39;re really popping one way or another. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:16:14 </td>
   <td style="text-align:left;"> I hit over 1000 ES handles💰for January.  I&amp;#39;m taking a little break from LIVE trading.😎 
$ES_F $ES $SPY $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:15:51 </td>
   <td style="text-align:left;"> Worst performing $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:15:50 </td>
   <td style="text-align:left;"> $SPY Why is everyone kissing Tom Lee’s ass 
I swear 
🙄🙄🙄 watch the guy say 500 by march again and be wrong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:15:29 </td>
   <td style="text-align:left;"> $SPY I NEVER BET AGAINST AMERICA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:15:27 </td>
   <td style="text-align:left;"> $SPOT $NFLX $HOOD $SPY $TSLA  alerted premarket for free. With P/L and entries and exits. https://vm.tiktok.com/TTPdhTpmxg/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:15:25 </td>
   <td style="text-align:left;"> $SPY $QQQ — The question is, are we filling gaps, or making new ones this week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:15:24 </td>
   <td style="text-align:left;"> $ARKK $SPY $QQQ 

If everything went straight up or straight down, everyone will be rich. When everyone is rich, there’s no need for a market. Respect the charts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:15:22 </td>
   <td style="text-align:left;"> $SPY What a fuckn rip, I mean damn! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:15:10 </td>
   <td style="text-align:left;"> $SPY theta coming for your calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:14:33 </td>
   <td style="text-align:left;"> $SPY $DJIA $NASDAQ $QQQ Tomorrow Brent Price will pass $90, if something unexpected occurs. It will be one of the highest Monthly gains and likely to take January inflation into a double - Digit Zone. If this scenario actually occurs we will be facing the highest rate hike since 2000 ,50 Basis points in Match or before, most likely.

Inflation means some are getting big heating bills this winter. How to stay warm and keep costs down
https://www.cnbc.com/2022/01/31/how-to-keep-heating-costs-down-this-winter-amid-rising-inflation-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:14:20 </td>
   <td style="text-align:left;"> $SPY Market got legs! Going higher! I like first ladies who speak English and don&amp;#39;t pole dance, how &amp;#39;bout you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:14:12 </td>
   <td style="text-align:left;"> $SPY wow markets are fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:13:56 </td>
   <td style="text-align:left;"> $SPY ready for a bull crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:13:56 </td>
   <td style="text-align:left;"> $SPY bears accounts are dead. $500 here we come beep beep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:13:51 </td>
   <td style="text-align:left;"> $SPY looks like we lost some of those bears that were talking shhhhht. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:13:32 </td>
   <td style="text-align:left;"> $SPY Tom Lee (still favorite person to watch). Literally now calling a VSHAPE bounce right here. 
 
https://www.youtube.com/watch?v=Ys5NlAoI2HA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:13:30 </td>
   <td style="text-align:left;"> $SPY Man! This rallied like it was the last day of January or something. Smooth sailing ahead!!!! Woo woo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:13:00 </td>
   <td style="text-align:left;"> $SPY  
 
Maybe an incorrect assessment, but I feel like 20% of the SPY board has a goose on their currency 
 
SPY $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:12:26 </td>
   <td style="text-align:left;"> $QQQ $SPY the relief rally all about bonds.  The 5 yr fell 50 bps since Friday.  Unsustainable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:12:09 </td>
   <td style="text-align:left;"> $SPY There won&amp;#39;t be a crash, but we are in a downtrend and hitting major resistance levels after a bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:11:53 </td>
   <td style="text-align:left;"> $SPY $480 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:11:25 </td>
   <td style="text-align:left;"> $SPY $DIA $BTC.X $SMH HODL, FCK, and LFG! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:11:00 </td>
   <td style="text-align:left;"> $SPY 454 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:10:43 </td>
   <td style="text-align:left;"> $SPY Pull back overnight/ tomorrow morning or I&amp;#39;m not Ray Finkle... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:10:31 </td>
   <td style="text-align:left;"> $SPY calls in the morning during first dip and sell them at the first sign of rejection. I don&amp;#39;t expect this to rally like it did today. Will immediately switch to puts. Easy 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:10:06 </td>
   <td style="text-align:left;"> $SPY Fuck America Haters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:09:54 </td>
   <td style="text-align:left;"> $SPY $UPRO Fundstrat&amp;#39;s Tom Lee says get ready for a &amp;#39;violent rally&amp;#39; in February https://www.cnbc.com/2022/01/31/fundstrats-tom-lee-says-get-ready-for-a-violent-rally-in-february.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:09:14 </td>
   <td style="text-align:left;"> $SPY Nice bounce back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:09:05 </td>
   <td style="text-align:left;"> $SPY PT for tomorrow? What about eoy? I was thinking a bounce off  $452-455 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-01 08:08:32 </td>
   <td style="text-align:left;"> $SPY 472 is tomorrow stop. 5 percent tomorrow. Shorts ripped into face </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:29:21 </td>
   <td style="text-align:left;"> $QQQ up today on relatively low volume isn’t a good sign for you bulls. I wouldn’t get to excited. Algos bidding this up to sucker idiots into buying the bags before the big dump. Head and shoulders almost complete 😎🇨🇳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:29:11 </td>
   <td style="text-align:left;"> $SPY $QQQ Despite the rally from the last 2 sessions, the market remains oversold for the year and there is not much reason for people to take profits yet when the market is still down YTD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:26:44 </td>
   <td style="text-align:left;"> Dark pool after hours activity in: 
 
$SPY - $100M print 
$IWM - $130M print 
$PM - $226M print 
$QQQ - $163M print 
 
#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:23:56 </td>
   <td style="text-align:left;"> $QQQ 380 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:21:01 </td>
   <td style="text-align:left;"> $QQQ Cramer thinks that the selling will increase, so I am all in on calls now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:20:44 </td>
   <td style="text-align:left;"> $SPY needs to retest the 200sma, most likely but ww here if 20ema rejects https://youtu.be/iZ1v89h_xP4 $IWM $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:20:33 </td>
   <td style="text-align:left;"> $AMD $QQQ certainly no one expects the same volatility for QQQ tomorrow as it performed today. Maybe retest $377 EOD and then trickle down rest of week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:19:03 </td>
   <td style="text-align:left;"> $SPY $QQQ So the market in Singapore and South Korea are closed today too? I didn&amp;#39;t know these countries celebrate Chinese New Year too lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:15:54 </td>
   <td style="text-align:left;"> $WIMI The metaverse is a hot investing topic of late, partially driven by Mark Zuckerberg&amp;#39;s decision to rename Facebook as Meta Platforms. Zuckerberg&amp;#39;s move is a bet that the metaverse becomes a major force over the next decade, and he&amp;#39;s not alone in thinking this concept has a future.$QQQ $AAPL 
https://skinnerifffz85.medium.com/4-top-metaverse-stocks-ready-for-a-bull-run-63a8b13f1bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:14:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Many of these bears must be new traders lol. 125 basis points is already priced in and the companies that have reported numbers particularly in tech are exceptional. The cash positions many of these companies have can eat up these shares for lunch. All these clown bears were telling me on Friday and the weekend that we would be down big today and even this past Friday and yet they were squeezed. There will be fluctuations of course but most of the bears on here are just plain dumb lol. You can try and time markets but for the most of you brainless bears you will never beat long term investor gains. Thats why 99 percent of traders fail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:13:00 </td>
   <td style="text-align:left;"> $SPY $QQQ At EOD today, bears were telling themselves... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:12:47 </td>
   <td style="text-align:left;"> $QQQ 22 points in 2 days? No way, this has to pull back 5 points or 8 points before going up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:10:13 </td>
   <td style="text-align:left;"> $QQQ it&amp;#39;s a 50% retracement ... From here it&amp;#39;s either going to explode and retest the high. Or it will dump to last week level. 

Not the right time to be either long or short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:09:41 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:08:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA just watching Tom Lee’s bit on Fast Money. V is for Violent Rally in February? Who’s paying him to say this??? 🙄

F is for Flush. As in we’re going to Flush back down to 4200 by mid-February. 

Only thing bullish i see in February is the Olympics, which could cool off geo-political crises for a couple weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:05:35 </td>
   <td style="text-align:left;"> $QQQ I told her 16 inches was headed her way... She was like... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:05:34 </td>
   <td style="text-align:left;"> $SPY / $QQQ bears just got gaped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:05:30 </td>
   <td style="text-align:left;"> $QQQ they closed now what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:04:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $UUP

Daily Market Recap for Monday 1/31/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/jJ2iFq_WIcM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:03:55 </td>
   <td style="text-align:left;"> $QQQ $SPY bears are disheartened. Most had to cover. Shorting is rocket science. Most bears don’t understand that. 

When bears are rare it will collapse again. Markets may go up another 1% to 5%. Then the crash will be nasty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:02:36 </td>
   <td style="text-align:left;"> $QQQ free tip for moron retail bears: correction is behind us, and $AMD and $GOOG are going to utterly destroy ER.  
 
Try investing in real companies, short crap like $DKNG.  
 
Rip continues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:02:13 </td>
   <td style="text-align:left;"> $QQQ don’t want to fomo just yet. Still room for volatility. Going to keep scalping 15-20% swings where I can </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 09:01:59 </td>
   <td style="text-align:left;"> $SPX $QQQ $NDX $DIA $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:56:11 </td>
   <td style="text-align:left;"> $QQQ $SPY  Everyone needs to chill. This totally looks like a drill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:53:00 </td>
   <td style="text-align:left;"> $QQQ has a poor technical rating and the quality of the setup is also only medium at the moment. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:51:41 </td>
   <td style="text-align:left;"> $QQQ short and hurt really bad , need fresh air to breath. Covered with losses . Staying away from market . Peace </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:45:29 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Honestly... If I was in charge? 

Vaccinations would be mandatory and done by force if necessary. It would be door to door motherfucker. You’re bullshit “freeDUM” argument that you somehow have a right to not have a bare minimum level of buy in to participate in society gets shut down like Washington did when he inoculated the continental army in 1776. 

“I have determined that the troops shall be inoculated ... Necessity not only authorizes but seems to require the measure, for should the disorder infect the Army in the natural way and rage with its usual virulence we should have more to dread from it than from the Sword of the Enemy.” - George Washington </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:43:46 </td>
   <td style="text-align:left;"> $SPY  $QQQ Futures need to decline more overnight in order to red market tomorrow ; otherwise will be another green push tomorrow … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:43:07 </td>
   <td style="text-align:left;"> $SPY $QQQ Its going to be a looong night for these silly bears. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:40:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $IPOF did anyone get homesick when they went to uni? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:40:15 </td>
   <td style="text-align:left;"> $QQQ Fibb TA wants $371.43 bounce to confirm 50% retraction. From there anyone’s game. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:33:40 </td>
   <td style="text-align:left;"> $MSFT $AAPL $NVDA  $QQQ $TSLA time to get short again.  the candles look bullish on some timeframes, but its not :-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:31:52 </td>
   <td style="text-align:left;"> $QQQ there are lots of statistics people throw around.  the only 2 that matter is the price you buy and the price you sell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:30:26 </td>
   <td style="text-align:left;"> $ARVL $SPY $QQQ 

ARVL is Very active after hours. Good volume. 

People getting ready for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:28:42 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ .    #zucchini </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:28:09 </td>
   <td style="text-align:left;"> $QQQ interesting close testing the 200 ema?🤔 would you say we’re overbought or oversold in the last 200 days? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:27:58 </td>
   <td style="text-align:left;"> $SPY $QQQ This will go higher this week to test EMA&amp;#39;s on 4 hour and daily and resistance on weekly and they all point towards $4580 on futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:26:50 </td>
   <td style="text-align:left;"> $spy $qqq $iwm $btc.x https://www.youtube.com/watch?v=37aoAp8sALU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:25:59 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:25:57 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
https://www.youtube.com/watch?v=Ys5NlAoI2HA 
 
Tom Lee is bullish for February </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:25:43 </td>
   <td style="text-align:left;"> $SPY more green coming tomorrow..get ready for max pain bears!! 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:25:15 </td>
   <td style="text-align:left;"> $qqq $ndx $uso https://www.youtube.com/watch?v=dd8rXsnuMko&amp;amp;ab_channel=UnlimitedOptionsInvesting $xle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:24:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $NDX 
 
Fear Greed Index (CNN) is still in FEAR. we have much room to go up.  
 
AAII has never been so BEARISH. We have to much room to go up too. 
 
What is the reason to go down? I we have to go down, first we have to correct this bearish sentiment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:24:06 </td>
   <td style="text-align:left;"> $QQQ Market will be down tomorrow 2% For next 3 months will be painful ride </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:24:04 </td>
   <td style="text-align:left;"> $QQQ Another side note: The spread between the 2 year and 10 year was 1.38% last year, it is now down to around .63%. The last 8/10 times these have crossed it’s caused a recession. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:23:42 </td>
   <td style="text-align:left;"> $SPY bullish 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:23:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $AMZN 

35500 will be the top for the year for dow and all index tomorrow. Be prepared to short the crap out of the market tomorrow. For puts wait for some IV crush before loading. There might be some consolidation before the move down.  After tomorrow we will see the biggest correction since 2008. 
21700 is where the buck stops for dow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:23:25 </td>
   <td style="text-align:left;"> $SPY $QQQ f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:23:17 </td>
   <td style="text-align:left;"> $QQQ Putting in bids for 360 puts tomorrow if 370 hits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:22:25 </td>
   <td style="text-align:left;"> $fb $amzn $goog $qqq https://www.youtube.com/watch?v=b-ZYKVaEWYA&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:18:13 </td>
   <td style="text-align:left;"> $QQQ nothing more than short covering. This market down turn will be a long, drawn out process due to the people that think that “buying the dip” works every time. It’s when these people finally run out of money that the market has reached its bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:16:52 </td>
   <td style="text-align:left;"> $QQQ fake red. Always turns green next day!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:15:25 </td>
   <td style="text-align:left;"> $SPY $QQQ — The question is, are we filling gaps, or making new ones this week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:15:24 </td>
   <td style="text-align:left;"> $ARKK $SPY $QQQ 

If everything went straight up or straight down, everyone will be rich. When everyone is rich, there’s no need for a market. Respect the charts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:14:33 </td>
   <td style="text-align:left;"> $SPY $DJIA $NASDAQ $QQQ Tomorrow Brent Price will pass $90, if something unexpected occurs. It will be one of the highest Monthly gains and likely to take January inflation into a double - Digit Zone. If this scenario actually occurs we will be facing the highest rate hike since 2000 ,50 Basis points in Match or before, most likely.

Inflation means some are getting big heating bills this winter. How to stay warm and keep costs down
https://www.cnbc.com/2022/01/31/how-to-keep-heating-costs-down-this-winter-amid-rising-inflation-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:12:26 </td>
   <td style="text-align:left;"> latex2b79fb2ec5c034ec3a14521853115111NVDA possible to see 241,248 after AMD earnings on Tuesday, best to hold above 230

$AMZN to 3000 can come before earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:02:21 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-31 Trade Analysis Video: 
https://www.youtube.com/watch?v=Uw3WsM2nK90 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:02:18 </td>
   <td style="text-align:left;"> $SPY what a pump today. My puts fucked up today. Hope they will be paid tomorrow $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:02:04 </td>
   <td style="text-align:left;"> $QQQ looks like we bullish until they actually raise the interest rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:01:13 </td>
   <td style="text-align:left;"> $SPY yeah eat shit bears! $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:00:34 </td>
   <td style="text-align:left;"> Something I didn&amp;#39;t like today was the strongest industrial stocks barely moving $HD &amp;amp; $CAT. In a healthy market we want to see them advance like 2% but today they were flat. $QQQ $SPY I had fun today. But, very suspicious if you follow $DJT $QQQ rule. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 08:00:03 </td>
   <td style="text-align:left;"> And So It Begins, Markets Initiate A Rally $QQQ $IWM $SPX https://talkmarkets.com/content/stocks--equities/and-so-it-begins-markets-initiate-a-rally?post=343119 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:56:50 </td>
   <td style="text-align:left;"> $QQQ 
It’s gotten a little ahead of itself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:56:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

little $$$ is buying at this level 

BIG $$$ is selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:56:05 </td>
   <td style="text-align:left;"> $NASDAQ  $NDX $QQQ  

       ♠️  $SPY     $ES_F   ♠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:54:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Had some peeps over for bear steak today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:54:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Let’s do another red at night, green in the light. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:52:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL
 
OMG CRAMER IS BOOLISH!!!😱📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:50:07 </td>
   <td style="text-align:left;"> $QQQ always buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:49:09 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:49pm)

⦿ $QQQ is down 0.0% in the last 5 mins. 

⦿ There are 15 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 7.5% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:46:30 </td>
   <td style="text-align:left;"> NEW Article:  &amp;quot;Outlook For Remote Workers Remains Strong&amp;quot; - https://www.seeitmarket.com/outlook-for-remote-workers-remains-strong/ 
 
by @SeanDavid $QQQ $ZM $MSFT $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:46:14 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX   ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:45:43 </td>
   <td style="text-align:left;"> $SPY  $QQQ Futures were bull trading last a few weeks then started Bear trapping at night and open then ripped .. I am sure after people got used to this ; will be bull trap again…  
Let bull celebrate little more like bears did … then our dips will come again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:43:44 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:43:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $GLD $TLT  
 
CPI inflation                +7% (bullshit)      
Housing inflation    +20%      
Gas inflation             +50%      
Heating oil                 +40%      
Used car prices        +25%     
   
INTEREST RATES         0%   
      
JPOW still printing.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:43:26 </td>
   <td style="text-align:left;"> $QQQ hoping we open up big tomorrow. Would love to close out my calls and then buy puts for the rest of the day. Only to close my puts close to end of trading day to buy $GOOGL calls expiring on friday. Lots to ask for! Let’s see what happens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:39:10 </td>
   <td style="text-align:left;"> $QQQ $402 jun/17 calls. Rack up get as many as you can. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:38:41 </td>
   <td style="text-align:left;"> $QQQ i would just be racking up on calls at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:38:37 </td>
   <td style="text-align:left;"> $SPY $QQQ Lets hope this wasn’t the strongest day of the week. But, so far so good. Let’s see what Mr. M shows us tomorrow. Exciting isn’t it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:38:34 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:37:57 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Never ever listen to the losers here they’re always scared shitless…

Tom Lee has been spot on

https://www.cnbc.com/video/2022/01/31/treacherous-market-activity-paves-way-for-violent-rally-in-february-says-market-bull-tom-lee.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:37:22 </td>
   <td style="text-align:left;"> $QQQ google about to set a records high earning. buckle up 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:34:10 </td>
   <td style="text-align:left;"> $SPY  $QQQ when they ask what made you buy those calls last week ? It was 99 cents </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:33:24 </td>
   <td style="text-align:left;"> $QQQ Its not thrilling to see that even garbage rallied like crazy today.. relief rally imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:33:09 </td>
   <td style="text-align:left;"> $SPY $QQQ don&amp;#39;t be suckered in like fish on hook. Uncle Vladimir has big plans </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:32:44 </td>
   <td style="text-align:left;"> $spy $qqq $iwm today was the greatest opportunity to short since Feb 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:31:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $NDX $BTC.X $AMC 

 from the Fed:

The possibility the Federal Reserve will cause a recession is far-off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:31:07 </td>
   <td style="text-align:left;"> $QQQ biggest Green days always happen in bear markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:31:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $GOOG  
 
Hey Millennial and newbie trader! 
 
Boomers giving you guys one more chance to buy high before JDADDY takes away the free money! 
 
Do miss this chance!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:30:00 </td>
   <td style="text-align:left;"> $SPY $QQQ If SPX can clear $4500 then $4570 will come easily with $QQQ to hit $370 and $SPY to hit $460 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:28:41 </td>
   <td style="text-align:left;"> $AAPL 
Apple
Thanks for everything.  🥲

$PLTR $QQQ  $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:27:58 </td>
   <td style="text-align:left;"> $QQQ &amp;#39;Treacherous&amp;#39; market activity paves way for &amp;#39;violent rally&amp;#39; in February, says market bull Tom Lee https://www.cnbc.com/video/2022/01/31/treacherous-market-activity-paves-way-for-violent-rally-in-february-says-market-bull-tom-lee.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:25:55 </td>
   <td style="text-align:left;"> $QQQ gapping down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:24:26 </td>
   <td style="text-align:left;"> $BTC.X $QQQ 

https://www.cryptoglobe.com/latest/2022/01/btc-300-community-banks-in-u-s-preparing-to-start-offering-bitcoin-trading-in-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:23:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK Well we got our follow through day, which marks the start of a new uptrend. BUT not all FTD hold to new highs. Now we want to keep track of distribution days as they have a high correlation with failure rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:21:10 </td>
   <td style="text-align:left;"> $QQQ are you ready for the Crush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:17:56 </td>
   <td style="text-align:left;"> $QQQ More than 1000pts UP IN A WEEK 
 
Sheet ..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:17:41 </td>
   <td style="text-align:left;"> $QQQ Who knows, maybe this correction is over and we are going to enter a true parabolic market topping phase  this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:16:40 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Days like today remind my why FREE MONEY CAPITALISM is the best and work is for SUCKERS! 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:16:21 </td>
   <td style="text-align:left;"> $QQQ Yup, looking thru beartard bozo posts on here .... 
 
 
Whole new class of dum fux fof money losers or 2022. 
 
The roster of loser imbeciles changes every 3-4 months .... LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:15:28 </td>
   <td style="text-align:left;"> $QQQ - Hedgies let retail run it up one more day, then they pull the plug on Wednesday 

Should head back to the 354 zone by the close Thursday

343 …..Friday, if we crash through the 354 support on Thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:13:56 </td>
   <td style="text-align:left;"> $SPY remember all last week on CNBC and the media outlets?  &amp;quot;valuations, earnings, profits, increase cash, sell growth stocks&amp;quot;..   all magically disappeared today.  $UVXY $QQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:13:54 </td>
   <td style="text-align:left;"> $QQQ $SPY a big big crash is coming and it may be fantastic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:12:34 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 1/31/2022 $SPY $XLF $QQQ $NIO $CGC https://www.chartguys.com/daily-market-videos/4121/bulls-lead-the-charge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:12:13 </td>
   <td style="text-align:left;"> FUTURES ABOUT TO RIP 
 
Are you loaded. DID YOU GET CALLS 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:11:30 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
How JPOW help average American suffering from 7% inflation? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:09:21 </td>
   <td style="text-align:left;"> $SPY $QQQ we don&amp;#39;t bottom until @OldFngGuy returns. Second leg down coming if he doesn&amp;#39;t have the confidence to show himself yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:07:02 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
still printing... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:01:52 </td>
   <td style="text-align:left;"> $ATER $SPY $QQQ $IWM you can’t change the stock price … but what you can change is ur attitude and positivity.  Trust me, everything becomes easier when u have a positive attitude.  Even if u lose money.  There will always be more opportunities.  Positivity is key to maintaining sanity in an uncertain market and also key in maintaining ur emotional well-being.  Don’t let money take away ur health. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:01:07 </td>
   <td style="text-align:left;"> CUE FEBRUARY BUYING OF FUTURES PUMP 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:00:57 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Piggie sold shares and moved 10% back to cash at 50% retrace today. 
 
He now 65% cash and ready to go 100% cash on retest of ATH. 
 
Piggie ain&amp;#39;t buying shit above the ATH. 
 
gl! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 07:00:26 </td>
   <td style="text-align:left;"> $SPY $QQQ I think this is gonna be the theme this week, a snap back to the 50-day MA📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:59:29 </td>
   <td style="text-align:left;"> $QQQ $CRUS 

STEALING on dip 💵💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:58:08 </td>
   <td style="text-align:left;"> $SHOP $TSLA   $1000 + for THESE 2 FUCKERS TOMORROW.... MOM:  I&amp;#39;M FUCKING RICH!!!!  🔥🔥🔥🚀🚀🚀🚀🤑 
. 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:57:00 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla 440, 350, 900 respectively tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:55:59 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Say it with me. The market Crash doesn&amp;#39;t exist. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:55:04 </td>
   <td style="text-align:left;"> $AMD earnings tomorrow after close. $PYPL earnings tomorrow after close. Silvergate Capital ( $SI ) on Cramer tonight. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:54:07 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I guess you Trump supporters can&amp;#39;t blame Biden anymore. Market crash doesn&amp;#39;t seem to exist apparently. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:54:01 </td>
   <td style="text-align:left;"> $qqq whut 2022 is gonna do if YO ain’t got YO huckleberries.    🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:52:00 </td>
   <td style="text-align:left;"> $QQQ has a poor technical rating and the quality of the setup is also only medium at the moment. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:49:11 </td>
   <td style="text-align:left;"> Hi Traders! New market analysis video ( $SPY $QQQ $VIX )  has been uploaded. You can find it here - https://www.youtube.com/watch?v=wLW_M3R-hOw - Last week I spoke about a potential bounce. Now that we got it, I talk about where I see us going from here. Enjoy! - #stockmarket #options #trader #FOMC #FED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:47:39 </td>
   <td style="text-align:left;"> $QQQ Tom Lee says violent rally into February .. the man is almost never wrong.  BUY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:47:30 </td>
   <td style="text-align:left;"> $QQQ $375 coming up here, Tesla looks bearish a bit but Qqq looking beautiful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:43:50 </td>
   <td style="text-align:left;"> $QQQ technical analysis for tomorrow. 
 
https://youtu.be/3AxZAM79vj0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:43:38 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
If we manage a double top at 4800-4840 Piggie will go 100% cash in his retirement account. 
 
He let other degenerates gamble on SP 5000. 
 
Just a heads up how Piggie gonna play it :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:43:30 </td>
   <td style="text-align:left;"> $QQQ 6% in 2 days... 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:43:13 </td>
   <td style="text-align:left;"> Todays PnL GREEN $10,000. Today was a day playing SUPER small to the upside on names and premium contract calls in my day trade account.Today was ALSO a day where I was blessed to add puts and RE SHORT the tops for a lower move in the markets potentially on my IRA and long term swing accounts. Hope folks nailed plays. Have a great night team $KSCP $QQQ $COIN $AFRM $INDO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:42:35 </td>
   <td style="text-align:left;"> $QQQ Russia most likely to attack before start of Olympics on Friday. This week will get ugly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:41:42 </td>
   <td style="text-align:left;"> $SPY $QQQ If you missed the bottom last week, still no reason to think it is too late to get in. If the market will be up 12-15% by end of this year then still a lot of upside from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:40:33 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Listen to what big money is telling you .. 🤓 https://twitter.com/marketrebels/status/1488179464324407304?s=24 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:39:39 </td>
   <td style="text-align:left;"> $QQQ 04-Feb-22 ATM Implied Vol Drops -18.9% to 26.4. Straddle Implies a Move of ±2.7% https://tinyurl.com/y43nc2ef </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:39:19 </td>
   <td style="text-align:left;"> $QQQ promise me you’ll hit the bid and bend the bears over again tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:38:42 </td>
   <td style="text-align:left;"> $SPY $QQQ  $TSLA 

We trapping bears 🐻!!

Shussssssss! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:37:55 </td>
   <td style="text-align:left;"> Bear markets may rally hard, even 50%. Some words of wisdom from Charlie. 👇🏼👇🏼
$QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:34:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA BULLS DUMB WATER WET $420.69 #DESTINY 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:34:38 </td>
   <td style="text-align:left;"> $QQQ i am equal opportunity -- interesting turn lower in CRUS -- caught my attention though i don&amp;#39;t follow it closely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:32:39 </td>
   <td style="text-align:left;"> $SPY 9 million sold at 450.17..nothing to see here...right on the close. I&amp;#39;m sure it was a few retail traders! $UVXY $QQQ $TSLA $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:32:39 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:31:25 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM 2 consecutive days of closing at the daily highs...good! 
Hope you went long 3 trading days ago...as per my tweet on Jan. 27 
Where do we go from here? idk...I hope this continues, as I&amp;#39;m still long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:31:01 </td>
   <td style="text-align:left;"> $QQQ https://stockbet.io/home/QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:30:44 </td>
   <td style="text-align:left;"> $spy $qqq $labu $iwm 
Now $$$$
CNBC pump of bio xbi $$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:29:46 </td>
   <td style="text-align:left;"> Hedge funds enjoying last stages of massive liquidity before Fed tightening, GDP sliding, and earning decline. See how SP500 earnings for 2021 (% better than expected): 
• Q4  5%
• Q3  9%
• Q2  17%
• Q1  21% 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:29:28 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $QQQ Since Cramer said he was buying Bitcoin and ETH, and suggested his following do the same… Bitcoin is up over 15% and ETH even more.

Even if you aren’t a big Cramer fan, you’ve got to be aware of how these pronouncements affect things </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:26:59 </td>
   <td style="text-align:left;"> $QQQ $TQQQ — Spot on so far… which would mean red tomorrow 🧙‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:26:49 </td>
   <td style="text-align:left;"> $QQQ nasdaq resistance @ 15000, then ☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:23:47 </td>
   <td style="text-align:left;"> $QQQ if you want to look smart always sit at a mahogany desk that has leather chairs on the side and encyclopedias in the background on the shelf -- and then make up some stuff about forward PE ratios and dividend yields and supply chains or something like that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:22:30 </td>
   <td style="text-align:left;"> $QQQ Son of a bitch just keeps giving and giving. Congrats to those along for the ride today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:21:17 </td>
   <td style="text-align:left;"> $QQQ over extended to the upside? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:20:55 </td>
   <td style="text-align:left;"> $PLTR $QQQ $TSLA $AAPL They believe Palantir its way too discounted and extremely cheap data is the new oil expecting a hard pop up into Earnings in two weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:20:51 </td>
   <td style="text-align:left;"> $QQQ being a &amp;quot;wall street strategist&amp;quot; like tom lee is a GREAT job.  you just find any reason whatsoever to be bullish all the time in every asset.  simple! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:20:32 </td>
   <td style="text-align:left;"> $SPY $QQQ All that resistance around 365 makes this rally a little suspicious ..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:19:48 </td>
   <td style="text-align:left;"> $QQQ is this gonna keep moving like a penny stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:18:21 </td>
   <td style="text-align:left;"> $SPY $QQQ is it me or is Tom Lee’s drip highly improved </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:17:35 </td>
   <td style="text-align:left;"> $SPY $QQQ 

I aspire to achieve my dreams just like Powell accomplished his. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:16:24 </td>
   <td style="text-align:left;"> $QQQ if you think this is gonna go up by another 10 bucks then I don&amp;#39;t know what to say. Short morning spike Tbh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:16:04 </td>
   <td style="text-align:left;"> $QQQ $SPY  Rug Pulled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:15:14 </td>
   <td style="text-align:left;"> $QQQ 

Ah

CLOWN HOUR with TOM LEE 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:12:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK — Pretty fucking disgusting if you ask me… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:10:52 </td>
   <td style="text-align:left;"> $SPY tomorrow is soooo big for the health of the future of the markets... Let&amp;#39;s hope we stay green ... Covid is going down. Bottom line.

 Everything else is just speculation. $qqq $DWAC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:09:56 </td>
   <td style="text-align:left;"> $SQQQ does anyone actually believe that a 10% swing in the innovation/tech stocks is actually going to hold tomorrow?

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:09:13 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : William Blair- Outlook 2022: A Closer Look at the Big 5 https://www.stck.pro/news/QQQ/22291100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:08:24 </td>
   <td style="text-align:left;"> $QQQ people can try to analyze charts all they want. At the end of the day, good companies grow, bad ones don&amp;#39;t. Look at QQQ holdings. It&amp;#39;s a Nasdaq ETF. No point in analyzing trend lines, etc. The market is sporadic and common trend lines are purely coincidental. It might spark some minor correlation due to sentiment from these magic psychic line readers. At the end of the day, invest in growth. That&amp;#39;s it. Weed, 5G, AI, etc. Sell overbought, buy when oversold. That&amp;#39;s all. There&amp;#39;s no magic formula dictating the &amp;quot;trend.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:08:02 </td>
   <td style="text-align:left;"> $QQQ the problem with blaming Biden for the down days is you then would have to give him credit for the last 2 biggest up days of all time.  better to just ignore politicians altogether. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:07:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK $AAPL $TSLA 
 
If JPOW can keep pumping asset prices and keep inflation moving higher soon enough every Millennial will be able to afford a home! 
 
JPOW pumping asset prices for Millennial!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:07:01 </td>
   <td style="text-align:left;"> $RBLX This stock is in such a nice position. I might sell some of my other stonks and really get balls deep here. Really bullish consecutive +3% days for $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:06:41 </td>
   <td style="text-align:left;"> $QQQ cnbc is like an endless parade of clowns that are just guessing -- not a single one of these people have any edge whatsoever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:06:36 </td>
   <td style="text-align:left;"> $QQQ Tomorrow’s price action tells us a lot.. a whole lot… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:05:39 </td>
   <td style="text-align:left;"> $UPST $QQQ Upstart is currently profitable and is experiencing triple digit revenue and earnings growth 💎💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:05:11 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
How to get 7% inflation under control. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:04:43 </td>
   <td style="text-align:left;"> $QQQ wall streets attempt at saving there jobs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:02:32 </td>
   <td style="text-align:left;"> $SPX $QQQ $IWM $XBI Today is refreshing, it can spark the a frenzy &amp;quot;meltup&amp;quot; with short covering. Two scenarios, IMO, have more chances to happen:  
1) $SPX makes a higher high tomorrow and goes around 4535 and reverses. In this case, two three small range bound days drifting lower to get close to but not going below today&amp;#39;s low will follow, then Thursday or Friday the rally resumes even stronger. If this happens and we go below today&amp;#39;s low, then the pressure on the downside will be high for the market to handle.  
2) $SPX does not make a higher high tomorrow and we go lower, expect tomorrow or Turesday to be a big scary down day, the low of Friday should hold, otherwise trouble.  
 
If Scenario (1) plays out then, we are likely to make new ATH and probably reach my previous target of 5050-5100 in $SPX before the END.  
If Scenario (2) plays out then, even if we make new ATH it would be few points above, before the end. 
Next resistance 4750. Support still at 4260.  
GL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:01:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM BiDeN mArKeT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:01:19 </td>
   <td style="text-align:left;"> $QQQ 

Hoodies fooled 🤣AAAAAAGAIN 

Calls AH ☎️ margin calls resume tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:01:18 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $BTC.X https://twitter.com/elonmusk/status/1488269452588326913?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:00:50 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ Elon is singlehandedly trolling world governments over and over again… I love it.

https://twitter.com/elonmusk/status/1488269452588326913?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 06:00:19 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
I wonder who and how much futes markets are going to pay to hold risk overnight. 
 
Should be interesting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:57:53 </td>
   <td style="text-align:left;"> $QQQ the market fooled all bears into shorting the markets these past two trading days... sadly MM&amp;#39;s control that! lol trillions burned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:57:37 </td>
   <td style="text-align:left;"> $QQQ keep the fiat $$$$$ printing! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:57:16 </td>
   <td style="text-align:left;"> $QQQ $SPY Denmark Declares Covid No Longer Poses Threat to Society </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:56:47 </td>
   <td style="text-align:left;"> $AMD $QQQ Lisa, u got this!! 
 💎🦾💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:56:15 </td>
   <td style="text-align:left;"> $SPY On a avg week I would expect to see selling on the Tues after a Monday Pop like this but because it was EOM rebalancing &amp;amp; book dressing its hard to make that call. 
 
Will look at $aapl,$tsal  &amp;amp; $amzn price action tomorrow &amp;amp; see if the $qqq&amp;#39;s get more inflows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:56:08 </td>
   <td style="text-align:left;"> $SPY $DJIA $NASDAQ $QQQ January Inflation data is one of the most critical event past decade. 
Makes or breaks, 

4000 or 5000

50 Basis points rate hike ( First time since 2000) or Gradual Hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:55:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $ETH.X This new Stocktwits desktop ad unit that opens directly in the center of the screen is super annoying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:54:52 </td>
   <td style="text-align:left;"> $SPY $QQQ keep hearing chatter about a developing HnS pattern....🤔. 
 
I don&amp;#39;t think so...it&amp;#39;s a potential HnS pattern...until it isn&amp;#39;t.   New ATH&amp;#39;s coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:53:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA End of month rally, shit might hit the fan tomorrow, I don’t have much faith until March </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:53:19 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #3 ETF that institutions are trading over rolling 5 day window with 617.7K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:52:26 </td>
   <td style="text-align:left;"> $QQQ People are too bullish… we need 80uvol tomorrow to confirm anything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:52:00 </td>
   <td style="text-align:left;"> $QQQ Up 7% in two days, If tomorrow gaps up this is a conviction short for a trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:51:44 </td>
   <td style="text-align:left;"> Stocks rally to end a dismal January, but S&amp;amp;P 500 still posts worst month since March 2020

$SPY $QQQ $DJIA $IWM

https://www.cnbc.com/2022/01/30/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:51:35 </td>
   <td style="text-align:left;"> $QQQ $SPY These analysts that come on cnbc and say a lost decade of stocks should be held accountable when markets go higher. She&amp;#39;s discouraging people from investing.  It&amp;#39;s awful for people to watch this crap. I can sit at home and analyze better than this person.  Other countries buy and use American companies like Google and Facebook. They don&amp;#39;t use European google or Mexico Facebook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:50:30 </td>
   <td style="text-align:left;"> $SPY $QQQ Chinese New Years. Assume the position bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:50:19 </td>
   <td style="text-align:left;"> $QQQ don’t be surprised when you wake up everything down 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:50:18 </td>
   <td style="text-align:left;"> $QQQ now that we canceled mother of crash … can we please have mother of all squeeze! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:49:45 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
From last week. 
 
Today was a gimme for the bulls...lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:49:20 </td>
   <td style="text-align:left;"> $QQQ Futures pivot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:49:03 </td>
   <td style="text-align:left;"> $QQQ glad to be adding puts with IV finally coming down. I’ll keep slowly adding puts for March and April. I know Wall Street is about to FUD the market with Russia war propaganda to complete this flush. Money printer is stopping. Valuations will come to reality and multiples will be compressed. Looking for a 20% dump soon 🖕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:48:37 </td>
   <td style="text-align:left;"> $QQQ it will go up just as fast as went down. Perfect vshape recovery </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:48:37 </td>
   <td style="text-align:left;"> $QQQ  99/00 daily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:48:29 </td>
   <td style="text-align:left;"> $QQQ here comes the relief rally. fomo sets in everyone is going to  jump in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:47:54 </td>
   <td style="text-align:left;"> $QQQ b to b business model vs b to c business model. Is this lady on cnbc serious?  When does she come back to earth?. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:47:20 </td>
   <td style="text-align:left;"> $SAVE double bottom confirmed? 🤔💡 
 
$SPY $QQQ $DIA $JETS  
 
🎰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:46:22 </td>
   <td style="text-align:left;"> $qqq An IBD FTD?   pay $aten tion to whut has 🧠 “qualities”.  Their sure ain’t many $pdfs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:46:00 </td>
   <td style="text-align:left;"> $spy $qqq remember to never invest in EM/Europe unless you are prepared to underperform </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:45:30 </td>
   <td style="text-align:left;"> $QQQ heating up... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:45:20 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
No...but I do know instantly when someone has not checked my history 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:44:51 </td>
   <td style="text-align:left;"> $QQQ will my $NDX 15800 calls actually be in the money this week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:44:01 </td>
   <td style="text-align:left;"> $SPY $UVXY $QQQ $BTC.X $GOOG
I drew these trend lines a while back… the s&amp;amp;p closed exactly at $450 as anticipated and will dump this and next week.  I have a google ad account that did $856k in sales and was making $8k a day before my supplier stole enough money to leave me broke and have to shut down the business I turned down $21k for the ad account.  If anyone has $2,500 and wants a wildly successful ecom business I will work slave labor for you if you can get me the cash so I can place this options bet and get myself out of the hole I am in.  My number is (413) 977-2680 I am free all day to text </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:43:44 </td>
   <td style="text-align:left;"> $QQQ I actually feel bad for bulls and how they are about to get absolutely raped. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:43:35 </td>
   <td style="text-align:left;"> $QQQ they ripped that right before month close. 30 pts in two days gtfo hahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:43:35 </td>
   <td style="text-align:left;"> Looking at 6 month daily volume profile chart on $DIA $QQQ $SPY IWM $TSLA  Yer mom etc will need QE TNT to infinity to get though that great wall of China resistance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:42:58 </td>
   <td style="text-align:left;"> Prefer we open @ $445. 
 
The $SPY game is awesome!  $$$$$$$ 
 
The churn is in progress. 
 
 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:42:27 </td>
   <td style="text-align:left;"> $QQQ  
 
QQQ Key Levels Grid for Month of February </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:41:14 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:41:11 </td>
   <td style="text-align:left;"> $QQQ picking up March and April puts 30-40% off today 😍 hopefully tomorrow we open near 370 to complete the head and shoulders then the next leg down we will be around 300 📝📝📝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:39:56 </td>
   <td style="text-align:left;"> $QQQ stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:39:16 </td>
   <td style="text-align:left;"> $QQQ Craziest day I&amp;#39;ve ever seen. So many 10-20% runners. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:38:51 </td>
   <td style="text-align:left;"> $SPY $QQQ 

I love when it bounces </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:38:45 </td>
   <td style="text-align:left;"> $QQQ like watching a train wreck in slow motion…. There is no real catalyst to push this higher and MANY more cases for a long bear market.  You have to be on the spectrum to think otherwise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:38:27 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Absolutely NOTHING has changed. 
 
JPOW is still full of shit and still printing money... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:38:18 </td>
   <td style="text-align:left;"> $QQQ technical bounce on oversold levels. If you didn&amp;#39;t gtfo today. 😞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:37:57 </td>
   <td style="text-align:left;"> $QQQ a trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:37:56 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $NDAQ $NASDAQ $SPY it’s gonna get ugly for the bulls here get ready for the bottom to fall out of the NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:37:38 </td>
   <td style="text-align:left;"> NEW POST: Stock Market Recap 01/31/22 {Video} https://marketchess.com/2022/01/31/stock-market-recap-01-31-22-video $ARKK $FB $GOOGL $QQQ $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:37:20 </td>
   <td style="text-align:left;"> $QQQ This pump is fake I promise that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:35:59 </td>
   <td style="text-align:left;"> $QQQ I hope this opens down 2% so the bulls can shove it where the sun don’t shine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:35:20 </td>
   <td style="text-align:left;"> $SPY I am a profitable options trader but I won’t earn your respect if I don’t admit my mistakes. Not making excuses bcuz this is my first(so far) unprofitable trade in over 3 weeks but it looks like I screwed the pooch on my $QQQ puts. What can I say… I keeps it real. I should have listened to Economist 4401 or whatever. Our bull/bear flags are usually in line. He/she got it better than me this time.Yet I live to gamble another day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:35:13 </td>
   <td style="text-align:left;"> $QQQ To da MOOOOON  
remember March 2020 
if you don&amp;#39;t buy the dips 
it will leave you behind regretful  
buy the dips, be a man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:34:26 </td>
   <td style="text-align:left;"> @jbananas $SPY $QQQ $AMD posted this last Monday at the ultimate fear 😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:34:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Iguanas are falling from the trees in Florida. Is there anything Florida can’t do? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:33:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM  12 out of the last 15 years, the market has been bullish on the first day of February #Almanac </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:33:45 </td>
   <td style="text-align:left;"> $QQQ back to 350 we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:33:35 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ just after the close, model statuses: 
TA - Trend: SELL 
TA - Mean Reversion: SELL 
Vix Basic: BUY 
https://grizzlybulls.com 
 
2/3 FREE models have become bearish on this bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:32:23 </td>
   <td style="text-align:left;"> $QQQ I mean if this is a dead cat bounce, it’s a huge one. Not sure which way this is really going. What positive news is to come ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:31:39 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Congrats bulls you bought a dead cat bounce... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:30:31 </td>
   <td style="text-align:left;"> $QQQ , $NASDAQ : Good to see strong jump i beaten down growth name ! But be watchful and careful ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:29:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Comon Bull!...push back higher! 
 
PIGGIE want to short at 4510 50% retrace level. 
 
HELP A PIGGIE OUT!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:29:40 </td>
   <td style="text-align:left;"> $SPY $QQQ still extremely relevant DD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:29:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Time to change strategies bears or she’ll be “out with the girls” on Friday night. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:28:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL

Did World Peace just get announced?... No, I didn’t think so... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:26:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA JPow&amp;#39;s printing press is shutting down. Peak printing Dec 31st. It&amp;#39;s going to get real ugly when the plug gets pulled. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:25:40 </td>
   <td style="text-align:left;"> $AAPL Rally higher $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:25:33 </td>
   <td style="text-align:left;"> $SPY $QQQ  Best Bear Market ever 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:24:40 </td>
   <td style="text-align:left;"> $QQQ We are about to close the monthly candle right were we need it to be bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:23:54 </td>
   <td style="text-align:left;"> $SPY $QQQ everything’s too green to bet on puts right now especially with ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:22:56 </td>
   <td style="text-align:left;"> Uncle POWELL so happy since Friday :) on next FOMC, he does not have to worry/ watch  his words and rate hikes...  
Some know what i mean; some don&amp;#39;t  
 
Slow and steady to the TRAP... 
 
FYI: All tweeter GURU bullish today; ALL OF THEM... 
 
They created FOMO 
 
$spy $qqq $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:22:00 </td>
   <td style="text-align:left;"> $tsla $spy $qqq tesla will keep climbing, but can’t see SnP staying above 4500 until Amazon reports.  Google guidance is expected to be bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:21:23 </td>
   <td style="text-align:left;"> $QQQ thank you for the easiest short opportunity EVER! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:20:33 </td>
   <td style="text-align:left;"> $QQQ Stock Climbs 3.2%. The 02-Feb-22 Option Straddle is Implying a ±2.1% Move in the Next 2 days https://tinyurl.com/y43nc2ef </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:20:07 </td>
   <td style="text-align:left;"> $SPY $QQQ what a beautiful Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:19:22 </td>
   <td style="text-align:left;"> $QQQ Will it smash past the 200? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:19:15 </td>
   <td style="text-align:left;"> $SPY $QQQ oh my god it’s beautiful😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:18:38 </td>
   <td style="text-align:left;"> $QQQ $SPY
Never ever ever listen to the losers, they missed the boat then &amp;amp; they missed it again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:18:37 </td>
   <td style="text-align:left;"> $TSLA every BS stonk in my watch list is up more than Tesla or about as much as Tesla. So.. it is better we figure out why.  
Credit Suisse is nice, but they never move Tesla more than +2% during pre mkt and after that everything is always gone. 
So... yeah, why??? $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:18:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Wow Chinese New Year is good for the bulls I guess lol. Anyway looks like we have bottomed and the market is up from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:17:53 </td>
   <td style="text-align:left;"> $RIDE Recap. Made 30% on Ride puts. Easiest pump and dump stock out there next to $FCEL and $OCGN 😆 Now go home and get your fucking shine box . 😆 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:17:49 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

One of the weakest low volume pumps I’ve ever seen... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:17:27 </td>
   <td style="text-align:left;"> $SPY $QQQ 2018-19 playbook? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:17:27 </td>
   <td style="text-align:left;"> $QQQ lol stupid ass bulls and FOMO buying. Can’t wait to watch you lose all your money this week as it goes below 340. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:16:31 </td>
   <td style="text-align:left;"> $QQQ fuck I was gonna short $UVXY  at the open too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:16:06 </td>
   <td style="text-align:left;"> $QQQ alright who wants to open up at $369 tomo? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:15:41 </td>
   <td style="text-align:left;"> $QQQ 

Paper gains …..for a day or two 🤣🤣🤣🤣

Enjoy them until the AM 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:15:36 </td>
   <td style="text-align:left;"> $QQQ hoping to get another 2~3% boost tomorrow then I&amp;#39;ll flip to the shot side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:15:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$1.7B to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:15:31 </td>
   <td style="text-align:left;"> those of you in a worthless pay service or listening to a supposedly bearish  &amp;#39;stock market authority&amp;#39;, 
cancel you pay service and just follow my posts 
 
based on my free posted trading calls ,  my followers made oodles of money today. You can too .   
 
$SPY $QQQ $UDOW $LABU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:15:10 </td>
   <td style="text-align:left;"> $SPY $QQQ 

pelosi bought calls!!...😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:14:55 </td>
   <td style="text-align:left;"> $QQQ NXPI up another 10 after hours, sorry bears but u r definitely screwed with the news flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:14:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:14:30 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA  
Daily charts look eerily identical... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:14:23 </td>
   <td style="text-align:left;"> $QQQ 1/26 1400 and 1500 hourly candles both 31.7 and 31.9 mil in vol.  Crazy coordination in play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:14:10 </td>
   <td style="text-align:left;"> $QQQ did Feb 2020 feel like this? i wasn’t around, but i feel like so many bulls weren’t either.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:14:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:13:39 </td>
   <td style="text-align:left;"> $QQQ ok thanks for the gains 
Inf for me 
Lets see what happen tommrow from the side hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:13:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 2/1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:12:23 </td>
   <td style="text-align:left;"> $QQQ what time do daily options officially expire?? 415? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:11:51 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
JPOW is like used car salesman. 
 
BLAH, BLAH, BLAH...buy my shit! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:11:38 </td>
   <td style="text-align:left;"> $SPY The $QQQ s closed right at the 200ema. I expect a downward move tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:11:38 </td>
   <td style="text-align:left;"> $QQQ Poor bears. It must be frustrating to get bongo bongo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:11:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $NVDA today got me feelin like Jimmy wit da stimmy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:10:17 </td>
   <td style="text-align:left;"> $QQQ 

CALLS 

ALREADY FCKED ☎️AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:09:41 </td>
   <td style="text-align:left;"> MEGA RAMP INTO THE CLOSE; BEARS GOT THEIR LIVERS RIPPED OUT FOR THEM - Dr. Fly $QQQ $IWM https://ibankcoin.com/flyblog/2022/01/31/mega-ramp-close-bears-got-livers-ripped/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:09:36 </td>
   <td style="text-align:left;"> $QQQ $SPY seems to be a given Q’s hits $470 by Wednesday.   BTFD and BTFRip💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:09:00 </td>
   <td style="text-align:left;"> $QQQ $TSLA When I heard on the TV this morning that bank analyst were now calling for an estimated 7 rate hikes this year I knew they were going to be covering today. lol  How can they estimate 7 rate hikes and unwinding the balance sheet at the same time with a straight face. lol Seriously. That is just comical. I knew the media was 100% corrupt regarding politics but now they are going full overboard market crash happy as well. How much do the hedge funds give these guys? Next there going to be telling people that the Covid Vaccine did a great job of stopping the Virus. After everyone gets sick and gets natural immunity. lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:08:51 </td>
   <td style="text-align:left;"> Market wrap: 
🔷 US indices closed solidly higher on the day:  
$DJIA +1.2%, $SPX +1.9%, $QQQ +3.2% 
🔷 #Gold (+0.7%) and #WTI (+1.7%) both rose as well. 
🔷 #AUD was the day&amp;#39;s strongest major currency; #USD was the weakest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:08:44 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
NOTHING has changed. 
 
Still printing... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:08:39 </td>
   <td style="text-align:left;"> $QQQ  Looking for the Market to go up between now thru Wednesday. I am in some 2/2/22 $368 Calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:08:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA

The S&amp;amp;P just posted it’s largest two day gain since April of 2020. Bears getting flashbacks... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:08:17 </td>
   <td style="text-align:left;"> $QQQ Not very impressed with volume, but it was by no means bad $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:07:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMC already on the right side of each trade I made at the close... love it...btw max pain here got revised down to $15...enjoy.. http://maximum-pain.com/options/AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:07:38 </td>
   <td style="text-align:left;"> $QQQ 

Bulls awake  for two days 🤣🤣🤣

After weeks of margin calls ☎️☎️☎️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:07:36 </td>
   <td style="text-align:left;"> $SPY they literally dont have to do a thing other than tamp down the sell algos now $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:07:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $TSLA ”Gap down tomorrow morning” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:07:22 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Just incase you are newbie or don&amp;#39;t know &amp;quot;free money&amp;quot;! 
 
Wall Street simpletons do same thing over and over :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:07:21 </td>
   <td style="text-align:left;"> latexc54b2bf363e03cc173af03881898e0d7CHWY Calls 450% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:07:14 </td>
   <td style="text-align:left;"> FOR THE MONTH, THE S&amp;amp;P UNOFFICIALLY FELL 5.26%, THE DOW UNOFFICIALLY LOST 3.32%, THE NASDAQ UNOFFICIALLY SHED 8.98% 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:07:08 </td>
   <td style="text-align:left;"> $BTC.X $QQQ hey guys just need 30 more days of this penny stock rocket and will be in Mars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:07:04 </td>
   <td style="text-align:left;"> $QQQ Talk about a trap lol. This will drop below $360 after hours tonight and gap down tomorrow. GL everyone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:06:48 </td>
   <td style="text-align:left;"> $QQQ jut a tremendous amount of short covering in meme stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-01 05:06:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA “NASDAQ Composite records worst month since March 2020” 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:28:49 </td>
   <td style="text-align:left;"> $AAPL respect it… stop the hating. 
 
pull back on the chart and you can easily see where this is going! 
 
the March to 200 has begun. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:27:43 </td>
   <td style="text-align:left;"> $SONY $MSFT $AAPL $INMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:24:48 </td>
   <td style="text-align:left;"> $AAPL every fucking phone is out of stock and it’s been 3 months, $200 easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:22:57 </td>
   <td style="text-align:left;"> $MSFT it is quite normal that traders are chasing the growth stocks now for quick bucks

Not to worry about $googl $msft $aapl $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:22:54 </td>
   <td style="text-align:left;"> $AAPL Here is the unusual activity on sweepcast.com/ as I mentioned in my previous post. #options #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:20:44 </td>
   <td style="text-align:left;"> $AAPL Great long chart!! Looking at the daily chart, the stock is close above 20D and 50D SMA levels with huge volume. Nice time to buy at deep. Algo also indicates a buy signal. It&amp;#39;s might be bounced from this spot. Make sure you&amp;#39;re using an unusual scanner platform such as SweepCast #stockstobuy #stockti </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:16:38 </td>
   <td style="text-align:left;"> $AAPL $MSFT never bet against America!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:15:54 </td>
   <td style="text-align:left;"> $WIMI The metaverse is a hot investing topic of late, partially driven by Mark Zuckerberg&amp;#39;s decision to rename Facebook as Meta Platforms. Zuckerberg&amp;#39;s move is a bet that the metaverse becomes a major force over the next decade, and he&amp;#39;s not alone in thinking this concept has a future.$QQQ $AAPL 
https://skinnerifffz85.medium.com/4-top-metaverse-stocks-ready-for-a-bull-run-63a8b13f1bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:14:53 </td>
   <td style="text-align:left;"> $AAPL shorts are getting clobbered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:14:40 </td>
   <td style="text-align:left;"> $AAPL wheees the guy that was saying that it was going to fall below 174 postmarket? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:14:34 </td>
   <td style="text-align:left;"> $AAPL will use $SQ network; apple will not try to set up its own network due to monopoly concerns. Consider it a partnership with apple, may very well be a tailwind moving forward.. a break above the 20SMA at $132 and we could teleport to $165 aka the 50SMA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:13:47 </td>
   <td style="text-align:left;"> $SPY $AAPL $NVDA $AMZN $TSLA 

Daily reminder to keep investing, keep compounding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:11:23 </td>
   <td style="text-align:left;"> $AAPL it was window dressing day across the whole market, let’s see what February brings, my guess more red. $GM $DIS $MU $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:09:51 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price 

https://youtu.be/zeWEIZ9Bix0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:09:40 </td>
   <td style="text-align:left;"> So what now? 
 
It doesn&amp;#39;t feel like too long ago, markets were on a verge of further collapse.  And as predicted with timely precision, market enjoyed a rebound on Friday and Monday, wiping out 25% of losses, in some cases, up to 50% depending on what equity you were tracking. 
 
100% of the stocks I called out last week are up considerably with what looks like no sign of slowing down. $NVDA $TSLA But that&amp;#39;s the problem. 
 
Not a single fund manager looks at this as a fundamental rebound, but a &amp;quot;technical&amp;quot; rebound.  Which I was adamant of declaring last Thur. 
 
As we speak, on L3 and in the back channels, managers are issuing transparent orders to sell off $AAPL quietly in the 175-180 range.  Does this mean the market will sell off at that point?  Who knows. 
 
But what we do know is that investment strategy has now forever changed.  What used to be a buy and hold strategy for fund managers has now become buy and take.   
 
Stay cautiously optimistic and define your goals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:09:13 </td>
   <td style="text-align:left;"> $AAPL 3 trillion thingy coming quickly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:02:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-31 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=Fm6QXVGIoaI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:00:13 </td>
   <td style="text-align:left;"> $AAPL Stocks were ripping today. Simulated Weekly $175.0 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 09:00:09 </td>
   <td style="text-align:left;"> $AAPL this is still going up tomorrow might even touch 178$? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:59:51 </td>
   <td style="text-align:left;"> $AAPL AAPL going wild https://www.thefinanceheadline.com/apple-celebrates-heart-month-with-new-resources-across-services/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:58:05 </td>
   <td style="text-align:left;"> $AAPL I’m fine with it. Everything kinda just drifted AH. I think we tap 176-177$ tomorrow before we head a little lower to cool off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:57:00 </td>
   <td style="text-align:left;"> $AAPL is currently trading in the upper part of its 52 week range, outperforming the market. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:52:51 </td>
   <td style="text-align:left;"> $AAPL buying back shares.  No wonder we have a $200 price target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:50:28 </td>
   <td style="text-align:left;"> Its not likely Apple and Square will compete directly - if they do, Bloc has the open source advantage. 

$SQ will innovate from new technology that $AAPL will bring to the payments platform. 

Ultimately, Square will benefit. In-store and online shopping experiences are entering a new era with crypto playing a role.

More options, more opportunities, more people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:49:05 </td>
   <td style="text-align:left;"> $AAPL you can only have so many up days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:47:55 </td>
   <td style="text-align:left;"> $SPY I see people bearish on this. I think thanks to $AAPL  $SPY has more to go. Profit from this was good today expecting more to come.  Follow me on Twitter and iG especially for alerts @mrscalikisses thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:44:41 </td>
   <td style="text-align:left;"> $AAPL under $174 by 8pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:42:46 </td>
   <td style="text-align:left;"> $SPY cramer says do some selling on stuff that been hammered off the highs, rates gonna be front loaded $AAPL $AMZN $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:40:50 </td>
   <td style="text-align:left;"> $NXPI chip stocks are ripping. Failed $QCOM  merger but nxpi was always no joke, big earner, diversified revenue streams.

$CRUS  Its been a long time since i owned this. I used to own big when it was single digits up to about 40 under jason Rodes. The problem  that crus always faced was they were $AAPL  dependent, who was at 1 time 80% of revenue. Still a lot I&amp;#39;m sure but they have diversified revenue streams since than, by how much idk. That was a phenominal quarter though.

$VERB after a year in development verb is launching a  new ecommerce website.
Their url  just went live the other day so launch is in anyday  soon.
Market.live

They have been rounding up sports partnerships for maybe some big promotional event. Keep your eyes peeled for another sports team announcement it could be the break in the damn, market sell off caused disconnection, this dollar stock might be on its way to double digits.

https://youtu.be/xvJO93fTzlI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:39:29 </td>
   <td style="text-align:left;"> $AAPL these upgrades aren’t making my puts look happy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:33:40 </td>
   <td style="text-align:left;"> $MSFT $AAPL $NVDA  $QQQ $TSLA time to get short again.  the candles look bullish on some timeframes, but its not :-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:30:51 </td>
   <td style="text-align:left;"> Who else got in some $SPY and $AAPL calls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:30:51 </td>
   <td style="text-align:left;"> $AAPL look at this beauty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:28:55 </td>
   <td style="text-align:left;"> $AAPL $DIS $AMZN Yall ready for tonight’s live session on Green Goose &amp;amp; Bullocks?
Here is your link to access the 8:30pm Est live broadcast. A nice prize pkg will be given away too!

https://vimeo.com/event/1786197/1090a0a2b6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:28:42 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ .    #zucchini </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:26:30 </td>
   <td style="text-align:left;"> $aapl $bulz $xlk $tecl https://www.youtube.com/watch?v=KnhPvpaJEeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:26:16 </td>
   <td style="text-align:left;"> $AAPL This company can take their $400 air pods and their malfunctioning $30 adaptors and shove both right up their ass. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:25:59 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:16:41 </td>
   <td style="text-align:left;"> $SPY $AAPL $TQQQ $SOXL  Whoever invented the squeeze momentum indicator is a genius </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:15:36 </td>
   <td style="text-align:left;"> $SBUX nice. 30 minutes ago.  $AAPL. $BA. $WMT. https://www.benzinga.com/analyst-ratings/analyst-color/22/01/25309311/coffee-prices-hit-10-year-highs-what-it-means-for-starbucks-investors?utm_campaign=partner_feed&amp;amp;utm_source=robinhood.com&amp;amp;utm_medium=partner_feed&amp;amp;utm_content=ticker_page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:09:57 </td>
   <td style="text-align:left;"> $AAPL Fed talks dominant the evening news..Jerome Fed Daddy Powell  going to pull a rabbit out of his hat.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:07:47 </td>
   <td style="text-align:left;"> $AAPL dip to $170 in the morning? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:05:49 </td>
   <td style="text-align:left;"> $AAPL y’all really think apple will shoot from $154 to $180 in less than a week? You know how many billions of dollar needed to do that? Not gonna happen until there’s a retracement back to $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:04:50 </td>
   <td style="text-align:left;"> Someone knows something. Huge trade, 245,790 shares! At the midpoint, $16.06 . Hence AH candle spikes 👀 🚀 
Bullish $AMC $GME $HOOD $AAPL  $BBIG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:04:49 </td>
   <td style="text-align:left;"> $AAPL Open Interest and Volume for weekly CALLS contracts for AAPL  on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:02:32 </td>
   <td style="text-align:left;"> $AAPL 180 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:02:13 </td>
   <td style="text-align:left;"> $AAPL Another fine day, long af.  This time it&amp;#39;s the market boosting $AAPL? Whatever,  I feel for you if you are rooting and betting on doom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 08:00:04 </td>
   <td style="text-align:left;"> $AAPL  190+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:57:55 </td>
   <td style="text-align:left;"> $SPY $AAPL    ichimoku progress chart.. the cloud bottoms are formed from a long time price average over 26 day period.  
 
Jan 18 gave caution on bearish cross . Jan 19 caution breaking /entering cloud top support $160 level.. someone liked that level.. wow..  it bounced hard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:56:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

little $$$ is buying at this level 

BIG $$$ is selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:53:24 </td>
   <td style="text-align:left;"> $AAPL  When is this B going to hit the ATH again???????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:52:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL
 
OMG CRAMER IS BOOLISH!!!😱📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:51:21 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 102.0K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:49:00 </td>
   <td style="text-align:left;"> $AAPL chiannna doesnt have an Apple to buy from. So they come to USA Apple now and later. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:47:06 </td>
   <td style="text-align:left;"> $AAPL violent rally coming in February </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:46:30 </td>
   <td style="text-align:left;"> NEW Article:  &amp;quot;Outlook For Remote Workers Remains Strong&amp;quot; - https://www.seeitmarket.com/outlook-for-remote-workers-remains-strong/ 
 
by @SeanDavid $QQQ $ZM $MSFT $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:43:17 </td>
   <td style="text-align:left;"> $AAPL NEWS - AAPL Reports First Quarter Results: 
https://www.youtube.com/watch?v=B2e7yheNg_E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:40:25 </td>
   <td style="text-align:left;"> $AAPL Whoooaaaa $8.00 more dollars and we are at the 3T market Cap..Bears are Scared.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:38:04 </td>
   <td style="text-align:left;"> $AAPL $NVDA $MSFT sorry but all these and the rest will drop big time again soon. The correction is far from over. If you think it&amp;#39;s over you&amp;#39;re mad, c&amp;#39;mon. Run up far too much. Learn how to read charts. Will buy afterwards.  Please don&amp;#39;t lose like I did in the early days. Learn, research </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:36:44 </td>
   <td style="text-align:left;"> $SPY $AAPL  banana cream pie ichimoku cloud levels.. not many will understand ichimoku. . ( i do mostly draw for myself :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:36:14 </td>
   <td style="text-align:left;"> Top Flow for the Week 🔥: $AAPL with a single PUT Trade for total premium worth $5840.3K Ranking #2 the Week | This was a SWEEP trade.  | Visit SweepCast.com or Join our Premium Room For Access! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:35:46 </td>
   <td style="text-align:left;"> $AAPL top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:35:44 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:35pm)

⦿ $AAPL is down 0.0% in the last 5 mins. 

⦿ There are 16 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 9.5% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:31:12 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Fairholme Focused Income Fund Starts 5 New Positions in 4th Quarter https://www.stck.pro/news/AAPL/22293771 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:31:04 </td>
   <td style="text-align:left;"> $SPY latexb28ca95f69038095012cbd6ac22a4749NVDA - 93% call flow 
$AMD - 61% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:29:39 </td>
   <td style="text-align:left;"> $NVDA $AAPL $FCX $AFRM 

Tom Lee says he expects a &amp;quot;violent rally&amp;quot; in February </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:29:15 </td>
   <td style="text-align:left;"> $AAPL The  BEARS ate so much last week  ,you can find them  hibernating..👇😂😂👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:28:41 </td>
   <td style="text-align:left;"> $AAPL 
Apple
Thanks for everything.  🥲

$PLTR $QQQ  $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:27:08 </td>
   <td style="text-align:left;"> $AAPL Stocks were ripping today. Simulated Weekly $175.0 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:22:03 </td>
   <td style="text-align:left;"> $AAPL those 15M at the close was buy or sell ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:16:08 </td>
   <td style="text-align:left;"> $AAPL call me crazy but I’m holding these $170 weekly puts overnight. RSI is overextended and the two trading day sympathy rally will end in tears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:15:57 </td>
   <td style="text-align:left;"> $AAPL go 175 by 8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:12:11 </td>
   <td style="text-align:left;"> $AAPL $SNAP $AAL  Novice question for you experts, please.   If you buy a call and it expires ITM, do you have to then buy the shares to make profit?  Or could you just sell the option and make some money?  Again, sorry if this is incompetent.  I&amp;#39;m new at options.  Thank you in advance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:09:06 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-31 Daily Forecast Video: 
https://www.youtube.com/watch?v=CHpTKV_HkSA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:08:27 </td>
   <td style="text-align:left;"> $SPY $MSFT $AAPL $AMD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:06:30 </td>
   <td style="text-align:left;"> $AAPL 180 in the money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:06:10 </td>
   <td style="text-align:left;"> $XELA has not even started. Wait and see. 
Good opportunity for 
$AAPL $AMZN $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:03:48 </td>
   <td style="text-align:left;"> Why Peacock, Apple and HBO Max are streaming must-haves for February 2022 — but Netflix is not

$AAPL $CMCSA $NFLX

https://www.marketwatch.com/story/why-peacock-apple-and-hbo-max-are-streaming-must-haves-for-february-2022-but-netflix-is-not-11643582694?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:03:16 </td>
   <td style="text-align:left;"> $TSLA $SPY $MSFT $AAPL $AMD violent rally coming soon
🌙 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:01:35 </td>
   <td style="text-align:left;"> $PLUG $FCEL $ENPH $AAPL $AMZN  
Nice day, bulls. Have a nice, cool beverage tonight and ponder future riches. They&amp;#39;re coming. 💪🦬💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 07:01:15 </td>
   <td style="text-align:left;"> $AAPL rug pull by Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:55:51 </td>
   <td style="text-align:left;"> $MTCH 30% off Tomorrow ! $TSLA  $NFLX $AAPL $DOCU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:55:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:51:02 </td>
   <td style="text-align:left;"> $GOOGL about to join the $AAPL $MSFT earnings season winner pillars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:50:09 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple&amp;#39;s Blockbuster Report Holds US Tech Slump. Three Reasons Apple is still a Good Buy. https://www.stck.pro/news/AAPL/22292295 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:49:06 </td>
   <td style="text-align:left;"> $AAPL 💵💵💵💵💵💵💵💵💪🤙🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:48:29 </td>
   <td style="text-align:left;"> $AAPL just yolo’d my way into retirement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:46:40 </td>
   <td style="text-align:left;"> $AAPL 🍏🍏🍏😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:45:47 </td>
   <td style="text-align:left;"> $AAPL technical analysis for tomorrow. 
 
https://youtu.be/VTlh7JLZ_SA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:39:40 </td>
   <td style="text-align:left;"> $AAPL ❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:34:57 </td>
   <td style="text-align:left;"> $AAPL watching, she looks like she may do a bit of a retrace before rising again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:32:01 </td>
   <td style="text-align:left;"> $AAPL https://stockbet.io/home/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:31:25 </td>
   <td style="text-align:left;"> $AAPL “You&amp;#39;ve got to know when to hold &amp;#39;em
Know when to fold &amp;#39;em
Know when to walk away from yours stock investment 
And know when to take your gain
You never count your money until you sell. 
There&amp;#39;ll be time enough for countin&amp;#39;
When the gain is lock-in “
Edit from Kenny Rogers lyrics.    
Subject to my attorney approval </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:30:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-31 Largest Trades Data: 
https://www.youtube.com/watch?v=no3yotlx85s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:28:43 </td>
   <td style="text-align:left;"> $AAPL well if this day didn&amp;#39;t break the bears, they are a resilient group, albeit adumb one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:25:18 </td>
   <td style="text-align:left;"> $AAPL ◢ Follow The Movement https://bit.ly/3slupxs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:20:55 </td>
   <td style="text-align:left;"> $PLTR $QQQ $TSLA $AAPL They believe Palantir its way too discounted and extremely cheap data is the new oil expecting a hard pop up into Earnings in two weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:20:12 </td>
   <td style="text-align:left;"> $AAPL $GOOG $TSLA $AMD $SPY  
 
Tech stock moving higher into rising interest rate environment after refusing to issue future guidance. 
 
Short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:19:38 </td>
   <td style="text-align:left;"> Buy These Mega-Cap Stocks Now and Hold for Years? $AAPL $KO $NFLX $DIS https://www.zacks.com/stock/news/1860184/buy-these-mega-cap-stocks-now-and-hold-for-years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:19:32 </td>
   <td style="text-align:left;"> $AAPL 
The beast. Best company in the world 🌍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:18:00 </td>
   <td style="text-align:left;"> $AAPL Look what Apple did to my Roof! Not nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:16:19 </td>
   <td style="text-align:left;"> $TLRY More earnings this week.  Hard to say if $AAPL is enough to keep things pumping.  Volume is not driving these bumps in the tickers I’m following.  I think there is still more downside in tech.  Cannabis been beaten down a lot longer and a million times harder.    Maybe things turn around here first?  Hard to days. Still waiting.  Hope I don’t miss a good entry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:16:01 </td>
   <td style="text-align:left;"> $AAPL most likely gonna get close to $170 again before $180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:15:52 </td>
   <td style="text-align:left;"> $AAPL closed out my calls today still have open short from 3t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:10:08 </td>
   <td style="text-align:left;"> $AAPL $SPY  
 
BTW....Piggie short 200 shares of Apple at 174 today for fun! 
 
PIGGIE don&amp;#39;t believe in company with NO GUIDANCE!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:09:23 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Could BBY Stock Be the Next Big Metaverse Bet? One Analyst Thinks So. https://www.stck.pro/news/AAPL/22290755 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:08:15 </td>
   <td style="text-align:left;"> $AAPL we still moving. calls are doing well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:07:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK $AAPL $TSLA 
 
If JPOW can keep pumping asset prices and keep inflation moving higher soon enough every Millennial will be able to afford a home! 
 
JPOW pumping asset prices for Millennial!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:06:52 </td>
   <td style="text-align:left;"> $AAPL I will put this as most of my portfolio. Learned my lesson </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:06:40 </td>
   <td style="text-align:left;"> $AAPL Stocks were ripping today. Simulated Weekly $175.0 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:04:14 </td>
   <td style="text-align:left;"> $AAPL 180 EOW✅🍏✅🥂🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:02:51 </td>
   <td style="text-align:left;"> $AAPL Every bear who said LAST WEEK this would tank ....how u like us now??? EXTRA BULLISH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:02:30 </td>
   <td style="text-align:left;"> $AAPL $SPY   Can’t hide from reality forever this is what I’m concerned about. And I would think if we have a food crisis it will tank the market.  

I’m already prepared for the worst just to be safe and  recommend you get prepared too.   Msm covering this will lead to more panic buying and dry up what little supply we have left.  Vax mandates are making the problems worse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:02:00 </td>
   <td style="text-align:left;"> latexee1874b1f69a4055835d61d2616bd131TSLA 1.123m (60% call/40% put)
$NVDA 629k (73% call/27% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:00:12 </td>
   <td style="text-align:left;"> $AAPL 190C Exp:17-Jun-22 ↑  🚀🚀🚀 Total(Day): $153,467 
$AAPL 200C Exp:15-Sep-23 ↑↑  🚀 Total(Day): $186,500 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:00:08 </td>
   <td style="text-align:left;"> $AAPL 185C Exp:19-Jan-24 ↓  🚀 &amp;lt;R&amp;gt; Total(Day): $272,145 
$AAPL 185C Exp:11-Mar-22 ↑↑  🚀🚀🚀 Total(Day): $148,599 
$AAPL 190C Exp:14-Apr-22 --  🚀🚀 &amp;lt;R&amp;gt; Total(Day): $152,308 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 06:00:07 </td>
   <td style="text-align:left;"> $AAPL apple will tank the nasdaq and whole market this week. The whole market is held up by apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:58:20 </td>
   <td style="text-align:left;"> $AAPL game just began. Tomorrow $180.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:57:54 </td>
   <td style="text-align:left;"> Today&amp;#39;s &amp;quot;wrap sheet&amp;quot; mostly sales from purchases made in the previous weeks on the dip. $TQQQ sales all profits, $VXX covered short on the day, 1 scalp from today long $CAT, and sold some $AAPL that was purchased on the morning after earnings when it dipped into the $162s.  
 
You can trade with Finom Group and our pros! (1/2) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:56:15 </td>
   <td style="text-align:left;"> $SPY On a avg week I would expect to see selling on the Tues after a Monday Pop like this but because it was EOM rebalancing &amp;amp; book dressing its hard to make that call. 
 
Will look at $aapl,$tsal  &amp;amp; $amzn price action tomorrow &amp;amp; see if the $qqq&amp;#39;s get more inflows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:52:26 </td>
   <td style="text-align:left;"> $AAPL Losing steam, it&amp;#39;s game over tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:50:50 </td>
   <td style="text-align:left;"> $AAPL finding out AAPL has rallied 10% since their earnings after the Fed confirmed rate hike fears lol this is unbelievable. After these last two trading days, I&amp;#39;m fully expecting another bottom out like we had last Monday. This market is bonkers, man. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:50:07 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL Solid day in the markets. Strong volume and significant price action. Saw an increase in social sentiment and momentum in the morning and continue through the day. Will be keeping an eye on this tonight an first thing tomorrow. 
 
You can keep an eye on the real-time trend here https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220131 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:49:27 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m laughing while coughing smoke rn... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:47:50 </td>
   <td style="text-align:left;"> $OUST and then all our dreams will come true ........ where this company will be if we sign a contract with $AAPL ??? we are the only  lidar company who use same lidar technology in the iphones ....... 
 
https://markets.businessinsider.com/news/stocks/is-this-the-lidar-company-apple-will-use-for-apple-car-1030996297 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:47:48 </td>
   <td style="text-align:left;"> 🎥 RUSH:
&amp;gt;https://youtube.com/watch?v=6bvzVOZlXu4&amp;amp;feature=share

“A wiseman learns more from his enemies than FOOL from his friends” ~ 

#F1 sponsored 💰🥇🏎💨
$AMD ↗️➕ $XLNX 🤔💭🛎

$AAPL | $TSLA | $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:46:22 </td>
   <td style="text-align:left;"> $AAPL Fud Booster Media 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:44:38 </td>
   <td style="text-align:left;"> $SPY I got into trouble last week with my SPY puts dragging out too long. Premiums were killing me. I hedged with $AAPL calls. I made money on both but the hedge paid more. That’s the beauty of high volatility… you can get paid playing both sides. That’s all. Live. Learn. Prosper my friends. John Cougar CamelToe has a place in his heart for all people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:44:12 </td>
   <td style="text-align:left;"> $AAPL if you didn’t gtfo tofay, god bless you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:40:01 </td>
   <td style="text-align:left;"> $AAPL 300 pls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:38:44 </td>
   <td style="text-align:left;"> $AAPL can someone explain how to buy puts n calls to me please! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:38:13 </td>
   <td style="text-align:left;"> $AAPL 
DO YOU KNOW WHAT I MEAN…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:37:13 </td>
   <td style="text-align:left;"> A word of caution as the Nasdaq moves up 5%, 10%, 15%----do not short. Until we get to about 18-20% gains from todays close.  
 
$MSFT $AAPL $NIO $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:37:08 </td>
   <td style="text-align:left;"> $AAPL Just voted on proxy vote. Now how did I not know that Maggot Al Gore was on the board of Directors? I voted No for that POS. The biggest lying hypocrite on the planet... Well there are many but he ranks right up there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:37:07 </td>
   <td style="text-align:left;"> $AAPL Hoyasaxa1978 gets his feelings hurt lol whata pussy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:36:57 </td>
   <td style="text-align:left;"> $AMD The guidance will be great. Lisa will take a page out of Cools playbook…. If she even needs to $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:36:32 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 561.9K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:33:33 </td>
   <td style="text-align:left;"> $AAPL 🍏🍏🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:32:51 </td>
   <td style="text-align:left;"> $AAPL but but but Apple is suppose to crash!? 😭 Some of these bears don’t even know the difference between an income statement and a balance sheet. Forget about cash flow. Bears are temporary and believe in predicting the market and that the chart is “telling them something” 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:32:13 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-31 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=Fm6QXVGIoaI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:31:39 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Congrats bulls you bought a dead cat bounce... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:29:13 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : 7 Blue-Chip Stocks to Buy for February https://www.stck.pro/news/AAPL/22289207 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:28:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL

Did World Peace just get announced?... No, I didn’t think so... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:27:42 </td>
   <td style="text-align:left;"> $AAPL looks like most of the rest of the bears covered today. Time to get down to business and let’s keep Russia off our radar from here on out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:27:20 </td>
   <td style="text-align:left;"> $AAPL welcome all the millennial losers running to what they think is safety.  Chasing losses and Hopi g apple will be there savior.  Exactly what markets are designed to do, get every degenerate invested at near ATH all before the flush to $140-$150.  This is truly beautiful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:27:15 </td>
   <td style="text-align:left;"> $AAPL the market tanked for weeks, and got back up quick in 2 days. Two. With everything going on in the world, this is dangerous for those buying in at these prices. All it would take is some bad catalyst to get this going to the downside. The market is not stable right now, and could turn ugly quick. This is for short term option traders, day traders. If your long term, then the dip only offers opportunity to buy cheaper, but smart money is hedging their portfolios. Just as fast as it goes up, it can go down. Volatility can make or break you. And this market is yoo volatile to only be  a one sided trader </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:27:08 </td>
   <td style="text-align:left;"> $AAPL Mr PUTZ returning his Lambo from last week.......... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:26:35 </td>
   <td style="text-align:left;"> $AAPL bound to pull back a little bit before resumes upward momentum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:26:27 </td>
   <td style="text-align:left;"> $AAPL $172-$170 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:25:40 </td>
   <td style="text-align:left;"> $AAPL Rally higher $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:23:31 </td>
   <td style="text-align:left;"> $AAPL $178-$180 tomorrow 🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:23:24 </td>
   <td style="text-align:left;"> $AAPL jumped up above KUMO 🏇 🏌️‍♂️ 
( Using chart program Pro ☞ https://tinyurl.com/y32cywz4 ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:23:04 </td>
   <td style="text-align:left;"> $AAPL looks strong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:21:17 </td>
   <td style="text-align:left;"> $AAPL  just want to post this happy monday.  djxidnxbcjdbxbdjxnxbchdhdnxnxjdbxbxbxhdbchcjcbcbxjzjznxbzjdnxmckskabxbxiskxnchdjcncjzkzjcnxjskzncjsixncjsoxjxnxhcbxbvvvvvvvhxjkslzjajahakapapajzhxnzbajazxxdsewasdrtyopootjfncncnbbbnnnmmbbnbhhggxbxbcncncnxncmcmvmvmvmvmvmvmvmvmvmxbxvsiaoaoapapapapapapapapshfirudjvoxpslqnsgcudkslxbwhqsbxjcjcncjfjf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:20:31 </td>
   <td style="text-align:left;"> $AAPL Time to buy Pootz sorry Fan Boys its time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:20:21 </td>
   <td style="text-align:left;"> $AAPL my poor man’s covered call at 170 is getting cooked. Fuuuuuuuck🤦🏾‍♂️ Didn’t think it would be this strong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:20:11 </td>
   <td style="text-align:left;"> $AAPL Very bullish day... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:19:37 </td>
   <td style="text-align:left;"> $AAPL  🍏😁.   Om. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:18:04 </td>
   <td style="text-align:left;"> $AAPL View @ www.elliottwave-forecast.com We have been forecasting AAPL to decline into the blue box and bounce higher in mid January.  The bounce now is strong enough where either a new cycle higher has started, or the instrument will decide to do the double.  We are looking for further extension higher as the preferred scenario at this point.  Members who bought the blue box have already taken partial profits..   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:18:00 </td>
   <td style="text-align:left;"> No but kidding aside. Look for 17-20% on the Nasdaq in February.  
 
$AAPL $MSFT $NIO $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:17:49 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

One of the weakest low volume pumps I’ve ever seen... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:17:12 </td>
   <td style="text-align:left;"> $SPY nailed this range 
$420 to $450 swinging the $445 
$AAPL target was 175 as spy hit $450 
tomorrow $UPS and $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:16:36 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:15:18 </td>
   <td style="text-align:left;"> The only thing that can derail this MONSTER rally coming in February is a 1% FED rate hike. And we know that isn&amp;#39;t coming until 2030 or so. LOL.  
 
Think things are expensive now. We are going to buying loafs of bread with our monthly salary, but the good thing is we don&amp;#39;t have to worry cause a bailout is coming.  
 
$AAPL $MSFT $NIO $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:15:01 </td>
   <td style="text-align:left;"> $DJIA $NFLX $TSLA $AAPL Dead cat bounce or will market go on to make new highs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:14:09 </td>
   <td style="text-align:left;"> What if $AJRD and $RDW teamed up? It could be a good plan if $LMT can&amp;#39;t win the FTC suit. It would open up the opportunity for AJRD to enter the commercial space with an instant link to Blue Origin and other opportunities like  $AAPL and their sat inclusion for the iCar. The tweet has some good points. 
 
https://twitter.com/NakaStudiosLLC/status/1487977863915753476 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:14:01 </td>
   <td style="text-align:left;"> $AAPL 15m sell signal ouch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:13:49 </td>
   <td style="text-align:left;"> more 6 month puts around the close latex2458a60478a17a2dd7d422b46a2d2068$ is in the $182-183 range I believe. Gee I wonder if we will hit that.....AGAIN.......YA THINK. 
Funny thing about ATHs..........Don&amp;#39;t be THAT guy. 
&amp;quot;This will never break $50...75...100...125...150...175...182...???&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:13:05 </td>
   <td style="text-align:left;"> $AAPL added 250B MC over a minor earnings beat. You guys are delusional </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:12:39 </td>
   <td style="text-align:left;"> $AAPL To the moon right? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:11:42 </td>
   <td style="text-align:left;"> $AAPL Stopped out mid-day. I&amp;#39;ll give Elliottwave forcast their due. I didn&amp;#39;t another top was coming. Broke through all resistance so we are on our way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:11:33 </td>
   <td style="text-align:left;"> $BKKT Just your friendly reminder to hold for $100 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:10:50 </td>
   <td style="text-align:left;"> $AAPL 
AH $176
That’s all folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:09:45 </td>
   <td style="text-align:left;"> $SPY $AAPL   bears always  complaining ,  The dip wasn&amp;#39;t deep enough and they weren&amp;#39;t smart enough to buy the dip . I bought the dip and sold the rip .  
Tomorrow is another day - 440-455 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:08:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA

The S&amp;amp;P just posted it’s largest two day gain since April of 2020. Bears getting flashbacks... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:08:12 </td>
   <td style="text-align:left;"> $AAPL SHHHHHHHH just lay there.....SHHHHHHHH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:07:15 </td>
   <td style="text-align:left;"> $AAPL apple bulls since y2k: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:07:09 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:07:03 </td>
   <td style="text-align:left;"> $AAPL look at the freakin volume...this screams bull trap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:06:59 </td>
   <td style="text-align:left;"> $AAPL upgraded from Sell to Neutral at New Street Research. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:06:23 </td>
   <td style="text-align:left;"> $AAPL is a beast. All time high I say in a week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:06:19 </td>
   <td style="text-align:left;"> $SPY Bears doubling down on Puts are gonna get so REKTED this week. There&amp;#39;s so much sidelined cash ready to buy oversold stocks. $AAPL was the last dip in awhile. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:05:49 </td>
   <td style="text-align:left;"> $AAPL which 🏳️‍🌈🐻 said „tHe gAp WiLl bE FiLlEd, cRaSH toMOrRoW“🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:05:43 </td>
   <td style="text-align:left;"> $AMZN  Very Bullish.. PT $3500. $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:05:36 </td>
   <td style="text-align:left;"> ALL tailwind until March.  Beware! 
 
$AAPL $MSFT $NIO $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:05:07 </td>
   <td style="text-align:left;"> $AAPL I thought we would see $140-150. I’ll keep waiting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:04:49 </td>
   <td style="text-align:left;"> $AAPL what is the day for dividends? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:04:37 </td>
   <td style="text-align:left;"> $AAPL 
🍏🔝🆙🔜
NEXT MC 3.125B
SHARES OUTSTANDING 16.404

NEW PTlatexa394d93705de40d2d9ffaa1e43b61525AAPL latex7ab04a758aa22479de3c82616d662a04ABNB 165 
$NIO $28 
$MSFT 329 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:04:06 </td>
   <td style="text-align:left;"> $AAPL wow ...3T Coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:04:03 </td>
   <td style="text-align:left;"> $AAPL What&amp;#39;s that smell?............... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:04:00 </td>
   <td style="text-align:left;"> $SPY I LOST EVERYTHING THIS MORNING FROM SWINGING PUTS AND MADE IT ALL BACK UP 600 BUCKS NOW LFG $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:03:26 </td>
   <td style="text-align:left;"> $AAPL dropped to bottom and bounce. Nice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:03:24 </td>
   <td style="text-align:left;"> $AAPL Where are all the Bears and So Called Experts from last week that were claiming doom and gloom for $AAPL ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:03:21 </td>
   <td style="text-align:left;"> $AAPL I think this week will be a really good one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:03:19 </td>
   <td style="text-align:left;"> $AAPL epic hanging man on the monthly.  This shits doomed. 😂🤣😂🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:03:01 </td>
   <td style="text-align:left;"> $AAPL closing strong. The v shape recovery looks scary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:02:58 </td>
   <td style="text-align:left;"> $SPY Lol too easy to make the shorts cover, two days and they jump ship $AAPL $AMD latexc3669fe681f11ce8e3c6ef08799be631AMD (Vol: 95.96M) 
$QQQ (Vol: 89.70M) 
 
Alerts &amp;amp; Technical Analysis via tradethehalt.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:02:03 </td>
   <td style="text-align:left;"> $AAPL they’re going to crash it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:02:03 </td>
   <td style="text-align:left;"> Live shot of an Apple bear checking his $AAPL puts. 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:02:00 </td>
   <td style="text-align:left;"> $MSFT $AAPL $ABNB $NIO  
 
Not 600 on the nasdaq but close enough.  
 
Watch for another 400 tomorrow and every day this week. We are going to 18,000 maybe 20,000 before the end of February. We didn&amp;#39;t get the capitulation at the bottom but we will at the top. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:01:58 </td>
   <td style="text-align:left;"> $AAPL 

Anyone else see 13m shares trade, 1 tick 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:01:47 </td>
   <td style="text-align:left;"> $AAPL 
🍏🔝🆙🔜⬆️
$176 AH 
VOLUME 107.550M
+$4.45
+2.61% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:01:41 </td>
   <td style="text-align:left;"> $AAPL What a comeback! Holding for the long term! As I always said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:01:23 </td>
   <td style="text-align:left;"> $AAPL what a close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:01:22 </td>
   <td style="text-align:left;"> $AAPL Bull trap huh........yeah GTFO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:01:10 </td>
   <td style="text-align:left;"> $TSLA $AAPL super strong close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:00:55 </td>
   <td style="text-align:left;"> $AAPL she did it HOD $175.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:00:54 </td>
   <td style="text-align:left;"> $AAPL 

Another toast for EOM .. we have made a very stunning come back from worst nightmare! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:00:47 </td>
   <td style="text-align:left;"> $AAPL what a day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 05:00:24 </td>
   <td style="text-align:left;"> $AAPL read my earlier post -- I told you 175 today.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:59:46 </td>
   <td style="text-align:left;"> $AAPL panic buying apple like it won’t always be there lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:59:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $AAPL $SPX  
 
going to be a long time before bears financially and mentally recover form this one.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:59:31 </td>
   <td style="text-align:left;"> $AAPL every funds want to own this name.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:59:16 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:59:15 </td>
   <td style="text-align:left;"> $AAPL to my foreign people, putting your money in Apple is the safest place to be? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:59:09 </td>
   <td style="text-align:left;"> $AAPL this panic buying at $175 push is insane... many will be bull trap in it... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:59:01 </td>
   <td style="text-align:left;"> $AAPL Mr PUTZ checking his Robin Hood account in the morning..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:59:00 </td>
   <td style="text-align:left;"> $AAPL I forget how much I like using their products until I have to use a PC or an Android. It’s time to upgrade to a new Mac (still using my 2011 MacBook Pro which has performed valiantly) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:58:39 </td>
   <td style="text-align:left;"> The thing about HISTORY is that it always repeats itself. Especially in the equities markets.  
 
See you all tomorrow. GL  Hate to say I told you so but I did. I told you on Friday at the lows too.  
 
$AAPL $MSFT $NIO $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:58:35 </td>
   <td style="text-align:left;"> $AAPL own it, don&amp;#39;t trade it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:58:14 </td>
   <td style="text-align:left;"> $SPY wow 😳 $AAPL $TSLA $AMZN $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:57:31 </td>
   <td style="text-align:left;"> $AAPL for you bears ..  Umm,  this is Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:57:19 </td>
   <td style="text-align:left;"> $AAPL 175.00 bring it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:57:10 </td>
   <td style="text-align:left;"> $AAPL 180 end of week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:57:07 </td>
   <td style="text-align:left;"> $AAPL 10% in 2 days lmaoooooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:56:46 </td>
   <td style="text-align:left;"> $AAPL Wall Street’s biggest weapon is FEAR. Fear in the face of an uncertain future. 
 
If you sell, THEY win. .........If you hold, YOU win......CATCH UP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:56:35 </td>
   <td style="text-align:left;"> $AAPL strong. Almost back to ATH. Can’t say that for many tech stonks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:56:32 </td>
   <td style="text-align:left;"> Days not over. 100 more points on nasdaq in last 4 minutes.  
 
$AAPL $MSFT $NIO $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:56:18 </td>
   <td style="text-align:left;"> $AAPL holding it down 🫡🫡🫡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:56:15 </td>
   <td style="text-align:left;"> $AAPL where did all the numb nuts bears go? Some of their arguments were pretty dumb and enjoyed listening to them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:55:56 </td>
   <td style="text-align:left;"> $AAPL dem puts still printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:55:15 </td>
   <td style="text-align:left;"> $AAPL 

Now shorts have left .. they can’t take anymore as MM throw them out!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:55:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA  

$1 TRILLION DOLLARS WORTH OF PUTS PURCHASED EACH DAY BEARS, DON’T BECOME A STATISTIC... THEY AREN’T GONNA PAY THOSE OUT... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:54:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:53:49 </td>
   <td style="text-align:left;"> $AAPL $200 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:53:38 </td>
   <td style="text-align:left;"> $AAPL going high in AH too... you&amp;#39;ll see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:52:40 </td>
   <td style="text-align:left;"> $ETSY Told you SHORTIES to cover. We are going to rally now. Lube up bc it&amp;#39;s coming fast and hard. Get on the long train $spy $qqq $msft $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:52:24 </td>
   <td style="text-align:left;"> $AAPL analyst the other day saying $210.00 right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:52:22 </td>
   <td style="text-align:left;"> $AAPL grabbed some $170 puts for $1. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:51:49 </td>
   <td style="text-align:left;"> $AAPL whole market pumping retail buying on hopium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:50:45 </td>
   <td style="text-align:left;"> $BKKT $5AH. Bring the $AAPL and $GME news on. Opens at $20… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:50:36 </td>
   <td style="text-align:left;"> $AAPL The 5% Apple stake Berkshire Hathaway acquired in 2018 for $36 billion  stake now makes up more than 40% of its equity portfolio. 
 
Warren Buffett?... WhyTF would you follow him when you&amp;#39;ve got all these anonymous basher trolls to listen to?.......GTFO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:50:18 </td>
   <td style="text-align:left;"> $AAPL I SMELL $3T 2.0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:49:52 </td>
   <td style="text-align:left;"> $AAPL i panic sold everything including $140 strike 2024 calls at the low last week. Wtf was I thinking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:49:46 </td>
   <td style="text-align:left;"> $AAPL licking chops --- 175 AH better cover ladies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:49:35 </td>
   <td style="text-align:left;"> $AAPL let’s close $4.00 Green! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:49:06 </td>
   <td style="text-align:left;"> Watch for 200 more on the nasdaq last 10 minutes.  
 
$AAPL $MSFT $NIO $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:48:49 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:48:44 </td>
   <td style="text-align:left;"> $SPY $AAPL Market out to give bears max pain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:48:19 </td>
   <td style="text-align:left;"> $AAPL run it up to new ath until Jerome kicks everyone out the party in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:47:40 </td>
   <td style="text-align:left;"> $AAPL nice, cheers 🍸🍸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:47:27 </td>
   <td style="text-align:left;"> $AAPL Boy that correction was some scary shit huh.........GTFO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:47:06 </td>
   <td style="text-align:left;"> $AAPL Good job bulls when I’m wrong I say I’m wrong nice play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:46:45 </td>
   <td style="text-align:left;"> $AAPL what a load of bullshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:45:29 </td>
   <td style="text-align:left;"> $AAPL $SPY well Can’t win them all. Time to invade the beer distributor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:45:23 </td>
   <td style="text-align:left;"> $AAPL gett ready to 158.80 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:45:16 </td>
   <td style="text-align:left;"> $AAPL NEWS - AAPL Reports First Quarter Results: 
https://www.youtube.com/watch?v=B2e7yheNg_E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:44:29 </td>
   <td style="text-align:left;"> It was … huge. Hands down, best ever. Chip, schmip shortages couldn’t stop $AAPL from having its biggest quarter of sales ever in the three months leading up to Christmas.  
 
Read more here: https://www.toggle.global/post/daily-brief-apple-s-biggest-quarter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:43:37 </td>
   <td style="text-align:left;"> $AAPL Beast mode!!  Loving me my Apple!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:43:28 </td>
   <td style="text-align:left;"> $AAPL Mr PUTZ.............. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:43:26 </td>
   <td style="text-align:left;"> $AAPL this either gets huge rejection or breaks out I’m betting rejection $CHD still believe it will fall $XCUR bullish $HOOD leaning towards an uptrend $WDC probably the best chart for uptrend currently on my watchlist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:43:06 </td>
   <td style="text-align:left;"> $AAPL this pig is trying to go places... https://youtu.be/8t_PgKycnXw $study video collecting rent is helping the cost avg. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:43:05 </td>
   <td style="text-align:left;"> $AAPL this price action and stength provides me with a hardon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:42:51 </td>
   <td style="text-align:left;"> $AAPL 150 next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:42:44 </td>
   <td style="text-align:left;"> $AAPL Microsoft left in the dust with this nasty pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:42:38 </td>
   <td style="text-align:left;"> $SPY $AAPL 52 week high inbound </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:42:14 </td>
   <td style="text-align:left;"> On huge  #Sobering  GAP Up  watch  Mates.. .  Major China names Call buying.. Australia &amp;amp; Asia may be up huge. 
 
fresh 1st of month money watching market run up for a week without em..    
$SPY $AAPL  #Tool 
 
https://www.youtube.com/watch?v=PzbQIPcPkf4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:41:53 </td>
   <td style="text-align:left;"> $AAPL hold and wait for $180 :-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:41:29 </td>
   <td style="text-align:left;"> Accept our deepest condolences  :) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:41:27 </td>
   <td style="text-align:left;"> $AMZN  Let’s just read between the lines. And this Prime increase will have a lot of Analyst upgrade AMZN an extra $20 with over 200 Million Prime members. Please do the math. When this happen which I really believe they will do it or announce it at this earnings. Looking at the pattern every 4 years and $20 increase. Time will tell. Until then let’s enjoy our daily GREEN ✅🤑. $GOOGL needa to Beat tomorrow to keep us going.. let’s pray 🙏🏽. Great day today guys. See y’all tomorrow🙌💎. $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:41:22 </td>
   <td style="text-align:left;"> $AAPL $174 + BREAKOUT. 
CLOSE $175. 

Apple Can Do It. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:41:15 </td>
   <td style="text-align:left;"> $AAPL let’s close at $175.00 come on Apple you can do it!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:41:13 </td>
   <td style="text-align:left;"> $AAPL hello $174.00! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:41:00 </td>
   <td style="text-align:left;"> $AAPL  .....YOU BEARS WILL BE FINE....LOL  
 
“Apple’s prodigious cash flow is one reason why investors believe that Apple can continue to spend significant amounts on share buybacks while still growing its headcount and investing in research and development. Apple reported an industry-leading $104 billion in cash flow in its fiscal 2021..&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:40:35 </td>
   <td style="text-align:left;"> $aapl closing in on all time highs did you listen $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:40:30 </td>
   <td style="text-align:left;"> $AAPL in your dreams shorty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:40:24 </td>
   <td style="text-align:left;"> $AAPL will start loading here on up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:40:08 </td>
   <td style="text-align:left;"> $AAPL tank baby , tank :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:39:26 </td>
   <td style="text-align:left;"> $AAPL  .....SOUNDS LIKE A PLAN  
  
&amp;quot;Investors are beginning to see Apple as a “flight to safety” or quality trade thanks to the combination of its large cash flow and willingness to return that money to investors.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:38:47 </td>
   <td style="text-align:left;"> $AAPL &amp;quot;Apple is the “poster child” for share buybacks, spending more than $467 billion in the past 10 years.&amp;quot;  
  
If it ain&amp;#39;t broke............. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:38:44 </td>
   <td style="text-align:left;"> $AAPL constant pumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:38:19 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:37:02 </td>
   <td style="text-align:left;"> $AAPL 👽. Still waiting. I don’t mess with puts until they are super cheap, but I love eating up call premiums </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:36:49 </td>
   <td style="text-align:left;"> $AAPL ......“Our analysis suggests that Apple is likely to be able to CONTINUE REPURCHASING ~ 3-4% of its shares PER YEAR UNTIL THE END OF 2026 while GROWING IT&amp;#39;S DIVIDEND per share by 10% annually.... without taking on net debt on its balance sheet,” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:35:28 </td>
   <td style="text-align:left;"> $AAPL the stock goes up down or sideways- nobody knows-  just do coke and masturbate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:35:05 </td>
   <td style="text-align:left;"> $AAPL how bout those apples 🍎! Beast mode! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:34:37 </td>
   <td style="text-align:left;"> $TSLA $SPY $SPOT $AAPL 

5 minutes Bear trap and ready to go again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:34:18 </td>
   <td style="text-align:left;"> $AAPL new HOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:33:49 </td>
   <td style="text-align:left;"> $AAPL 176ish and new ATH tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:33:33 </td>
   <td style="text-align:left;"> $AAPL rising wedge will short it when it will breakdown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:31:41 </td>
   <td style="text-align:left;"> $AAPL is this going to hold to the close 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:30:45 </td>
   <td style="text-align:left;"> $AAPL 

Lol MM is tired of people trying to attack the tape ..

Soon they will throw out of the window again ..

Wink .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-01 04:29:31 </td>
   <td style="text-align:left;"> $AAPL 175 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:29:21 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:29:08 </td>
   <td style="text-align:left;"> $TSLA huge potential 
https://youtu.be/oTK8VGObKfY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:27:55 </td>
   <td style="text-align:left;"> $TSLA https://nypost.com/2022/01/28/elon-musk-calls-joe-biden-a-damp-sock-puppet-after-snub/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:27:52 </td>
   <td style="text-align:left;"> $TSLA it actually starts Feb 1 this year, let’s just forget about January </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:27:12 </td>
   <td style="text-align:left;"> $TSLA Allah came up to me and said 860$ tomorrow, even tho im atheist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:27:11 </td>
   <td style="text-align:left;"> $TSLA headed to $10 trillion market cap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:26:38 </td>
   <td style="text-align:left;"> $TSLA The headline reads « Tesla fans complain Biden ignores Tesla’s E.V. leadership « …Tesla fans?.. Every American and business leader should be totally outraged and turned off.. if Trump would of tried to pull a stunt like that. mainstream media would of been all over him and DEMANDED clear answers… sometimes omitting and ignoring is the worst form of public misinformation and bullshit… this guy Biden reminds me of manipulative antics I used to see in high school… and insults every American worker who worked so hard to make this country more efficient and greener… imagine you praise the top three that just finished a race but you ignore the gold medalist… cause he’s black.. extreme comparison you say?.. absolutely not… just as outrageous !..worst administration ever!.. oh and I’m sure Bernie and hypocritical auntie Elizabeth had their word to say..so to finish off politely… go fuck yourself Sleepy Joe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:25:38 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $TSLA $BTT.X 

Tiger 🐯 Power 2022

Tesla Tiger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:25:02 </td>
   <td style="text-align:left;"> $tsla Cathie back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:24:53 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $TSLA $BTT.X 

Tiger 🐯 Power 🐅 

Tesla Tiger 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:24:11 </td>
   <td style="text-align:left;"> Cathie Wood bought $TSLA today. A welcome change. Maybe she had a spiritual awakening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:24:00 </td>
   <td style="text-align:left;"> $TSLA last week was 987 .. 2 weeks ago 1070.. getting close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:23:28 </td>
   <td style="text-align:left;"> Cathie Wood buying more $TSLA today $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:23:26 </td>
   <td style="text-align:left;"> $TSLA does anyone else see that it&amp;#39;s still in the downward wedge? It is that just me? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:23:13 </td>
   <td style="text-align:left;"> $TSLA Cathie bought 42K shares today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:23:12 </td>
   <td style="text-align:left;"> $TSLA Tesla is working on the new electric Airliner plans. 2026! Shhhh... It&amp;#39;s a secret. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:22:38 </td>
   <td style="text-align:left;"> $TSLA wow bears got smoked. It’s funny because they swore we were collapsing 😂. Good night bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:22:38 </td>
   <td style="text-align:left;"> $TSLA hitting 960 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:21:48 </td>
   <td style="text-align:left;"> $TSLA 

I don’t know if anyone reads what I read between the lines @elonmusk  I see deep frustration and disappointment!! 

By the country?!  the world?!  His fight has gotten much harder over time when you’d think the opposite!! 

Not much help !! Thx Moe ..

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:19:25 </td>
   <td style="text-align:left;"> $TSLA more people are in buying mood, the previous dip accumulated too much buying force, this gravity along will accelerate price break 1000 very very soon, perhaps tomorrow.. 
 
Recommend put position wait for next better window, it might come sometime around 2nd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:17:52 </td>
   <td style="text-align:left;"> $TSLA I hope y’all got your $1000 call for tomorrow. It will definitely hit $1000 tomorrow. A little advice buy in regardless in the morning and you will still times 3 to 4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:17:32 </td>
   <td style="text-align:left;"> Tesla says it had 400,000 Storm Watch activations on Powerwalls last year alone 
 
The feature helps homeowners avoid power outages in extreme weather 
 
$TSLA 
 
https://electrek.co/2022/01/31/tesla-storm-watch-activations-powerwalls-2021/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:16:54 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:16:12 </td>
   <td style="text-align:left;"> $TSLA Bears swear “they’re winning” #sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:15:44 </td>
   <td style="text-align:left;"> $BA I don’t see how $TSLA is 1T company when Ba is only $117B!!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:14:42 </td>
   <td style="text-align:left;"> $tsla $spx $amzn $nvda listen  https://twitter.com/i/spaces/1MnxnkybbgjKO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:13:47 </td>
   <td style="text-align:left;"> $SPY $AAPL $NVDA $AMZN $TSLA 

Daily reminder to keep investing, keep compounding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:13:16 </td>
   <td style="text-align:left;"> $SPY $TSLA  it takes a  diabolical mind to  outwardly support  the Canadian Truckers  protest while simultaneously building the very trucks intended to replace them..... 
 
https://nypost.com/2022/01/31/cops-investigating-after-protesters-allegedly-urinated-on-canadian-monuments/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:11:24 </td>
   <td style="text-align:left;"> $TSLA you guys ready for the fomo buys tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:11:23 </td>
   <td style="text-align:left;"> $AAPL it was window dressing day across the whole market, let’s see what February brings, my guess more red. $GM $DIS $MU $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:11:01 </td>
   <td style="text-align:left;"> $TSLA positivity kills the up trend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:10:47 </td>
   <td style="text-align:left;"> $TSLA I made money bring short till 841. Flipped at 841 from short to long - profit till 901. Now I am short since 901

We are taking it down to 650. Nothing anyone can do to stop that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:10:46 </td>
   <td style="text-align:left;"> $TSLA 1000$+ tomorrow🥳🥳🥳🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:09:40 </td>
   <td style="text-align:left;"> So what now? 
 
It doesn&amp;#39;t feel like too long ago, markets were on a verge of further collapse.  And as predicted with timely precision, market enjoyed a rebound on Friday and Monday, wiping out 25% of losses, in some cases, up to 50% depending on what equity you were tracking. 
 
100% of the stocks I called out last week are up considerably with what looks like no sign of slowing down. $NVDA $TSLA But that&amp;#39;s the problem. 
 
Not a single fund manager looks at this as a fundamental rebound, but a &amp;quot;technical&amp;quot; rebound.  Which I was adamant of declaring last Thur. 
 
As we speak, on L3 and in the back channels, managers are issuing transparent orders to sell off $AAPL quietly in the 175-180 range.  Does this mean the market will sell off at that point?  Who knows. 
 
But what we do know is that investment strategy has now forever changed.  What used to be a buy and hold strategy for fund managers has now become buy and take.   
 
Stay cautiously optimistic and define your goals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:09:28 </td>
   <td style="text-align:left;"> $TSLA so like 950+? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:09:24 </td>
   <td style="text-align:left;"> $TSLA stupid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:09:15 </td>
   <td style="text-align:left;"> $TSLA Lol Brandon...ttt...es...gm!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:07:00 </td>
   <td style="text-align:left;"> $MANA.X $SAND.X 
+300%(?)  🚀🚀  when $TSLA opens up dealership in Metaverse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:06:34 </td>
   <td style="text-align:left;"> $TSLA $2,000 by Jan 2023. Yep, I said it! You got a problem with that? @Elon_Musk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:06:14 </td>
   <td style="text-align:left;"> $TSLA New ATH coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:06:03 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:05:56 </td>
   <td style="text-align:left;"> $TSLA super 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:05:18 </td>
   <td style="text-align:left;"> $tsla ok it touched 940; bears done Tom row </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:04:40 </td>
   <td style="text-align:left;"> $BTC.X  this pet rock doesn&amp;#39;t do anything so it&amp;#39;s not going to appreciate like $TSLA or $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:04:17 </td>
   <td style="text-align:left;"> $TSLA shorts just made a killing from $1200 to $792, and they want it to go down again. That’s why you bozos always get roasted. Go with the movement, and the movement is up until further notice! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:03:26 </td>
   <td style="text-align:left;"> $TSLA Tesla climbs more than 10% on Monday after Credit Suisse upgrade

https://www.cnbc.com/2022/01/31/tesla-climbs-nearly-10percent-on-monday-after-credit-suisse-upgrade.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:03:07 </td>
   <td style="text-align:left;"> $FSR this is easily a $TSLA killer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:02:40 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-31 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=eKyEE1-UMXI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:02:31 </td>
   <td style="text-align:left;"> $TSLA I’ll see ya at $800s soon retards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:02:20 </td>
   <td style="text-align:left;"> $TSLA my 1200 March call feels juicy :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:01:59 </td>
   <td style="text-align:left;"> $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:01:31 </td>
   <td style="text-align:left;"> Rumored that $GME is going to buy $TSLA to become the dumbest conglomerate of investors ever.

Let me know what you guys hear about it. Thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:00:31 </td>
   <td style="text-align:left;"> $TSLA Stocks were ripping today. Simulated Weekly $940.0 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:00:10 </td>
   <td style="text-align:left;"> $TSLA all you panic buyers are gonna be crying when we’re back below $800 idiots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 09:00:02 </td>
   <td style="text-align:left;"> $TSLA break $980 or fill the gap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:59:39 </td>
   <td style="text-align:left;"> $TSLA 

Its the most wonderful stock of the …..😍😍😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:59:09 </td>
   <td style="text-align:left;"> $TSLA just hit 940 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:57:56 </td>
   <td style="text-align:left;"> $TSLA $1400 PT by end of </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:57:51 </td>
   <td style="text-align:left;"> $TSLA I see some of you are smart covering </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:57:47 </td>
   <td style="text-align:left;"> $TSLA   lower highsss lower lowssss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:57:22 </td>
   <td style="text-align:left;"> $TSLA lol crayon eaters back at it again with this stock going up 10%.  

I guess this stock wants to go back to an 1300  P/E ratio again.  If so fair value is closer to 2000$ +++ to return to our P/E to where it was  those levels early last year.  

HODL.  Stonk is going up forever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:56:21 </td>
   <td style="text-align:left;"> $TSLA Tesla is a beast!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:55:38 </td>
   <td style="text-align:left;"> $TSLA Beautiful. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:53:26 </td>
   <td style="text-align:left;"> $TSLA green AH close 

shorts, y’all are going to get absolutely mangled by elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:51:15 </td>
   <td style="text-align:left;"> $TSLA shorts mad scramble tmr to cover you kick yard dogs are in trouble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:51:13 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:49:00 </td>
   <td style="text-align:left;"> $TSLA has a good Piotroski-F score of 7.00. This indicates a good health and profitability. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:45:08 </td>
   <td style="text-align:left;"> $TSLA should rally off this video and this alone 😂😂😂 LFGGGGGG

https://m.youtube.com/watch?v=iKytthXjylI

To all the Basement dwellers just know👉🏼👉🏼 $TSLA is first in class 🚀💎🌙💚 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:43:13 </td>
   <td style="text-align:left;"> $TSLA throw in the towel, Burry! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:43:00 </td>
   <td style="text-align:left;"> $NFLX, $TSLA and $AMD are the top gainers in the Nasdaq 100 for the day. https://www.chartmill.com/stock/stock-screener?v=3&amp;amp;f=ind_20&amp;amp;s=pt&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_top_Nasdaq_100_gainers&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:40:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $IPOF did anyone get homesick when they went to uni? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:40:27 </td>
   <td style="text-align:left;"> Tesla Motors&amp;#39;s SVP Powertrain and Energy Eng. just cashed-in 3,500 options  https://www.conferencecalltranscripts.com/summary/?id=10378338 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:39:38 </td>
   <td style="text-align:left;"> $TSLA InSiDeRs SelLiNG!!¡

There I did it before the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:39:38 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: SVP Powertrain and Energy Eng. Baglino Andrew D: 
Disposed 3,500 of Common Stock at price $933.56 a https://s.flashalert.me/uSkIFl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:38:48 </td>
   <td style="text-align:left;"> $TSLA Cup &amp;amp; handle.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:38:23 </td>
   <td style="text-align:left;"> $TSLA 📜 SEC Form 4: Baglino Andrew D exercised 3,500 shares at a strike of $62.72 and sold $3,267,460 worth of shares (3,500 units at $933.56) as part of a pre-agreed trading plan

https://quantisnow.com/insight/2329899?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:38:00 </td>
   <td style="text-align:left;"> Insider Andrew D Baglino reports selling 3,500 shares of $TSLA for a total cost of $3,267,460.00 https://fintel.io/n/us/tsla/baglino-andrew-d?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:37:47 </td>
   <td style="text-align:left;"> $HOOD $BTC.X $TSLA stay powerful stay strong stay as a winner and you have to stay with the winners and dont get tired of winning.. and that is stay patriotic stay maga stay capitalist 🇺🇸🇺🇸🇺🇸👇👇👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:37:34 </td>
   <td style="text-align:left;"> $TSLA $3,047,940.00 of shares sold by Baglino Andrew D (SVP Powertrain and Energy Eng.), reported in a new form 4 filed with the SEC  

https://newsfilter.io/a/d1c5cb3171c0ef570608879b3673e474 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:33:40 </td>
   <td style="text-align:left;"> $MSFT $AAPL $NVDA  $QQQ $TSLA time to get short again.  the candles look bullish on some timeframes, but its not :-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:33:16 </td>
   <td style="text-align:left;"> $TSLA it all now depends on breaking $940 wall to get back to $987, $1000, $1020 levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:32:32 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-31 Technical Analysis Video: 
https://www.youtube.com/watch?v=2DKFhUSnsKM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:31:58 </td>
   <td style="text-align:left;"> $TSLA would be opening $1000 or plus tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:30:47 </td>
   <td style="text-align:left;"> $TSLA these are the current gaps open. Look’s like we will be filling the ones up top, and leaving that one in the 800’s behind…✌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:30:23 </td>
   <td style="text-align:left;"> $STEM $ARVL $TSLA strong finish 📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:29:56 </td>
   <td style="text-align:left;"> $TSLA https://www.teslarati.com/tesla-non-tesla-supercharer-pilot-program-france-norway/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:29:19 </td>
   <td style="text-align:left;"> $TSLA  bear will leave in denial just admit you didn&amp;#39;t aspect 10% up today and probably will never accept another run tomorrow, I can see this touching 980 and consolidating till Friday in this 930(980 range then we will see a push up to 1000 wich will cause a major bottom.  March will probably take this stock again to 1200 with maybe a new high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:28:56 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:27:03 </td>
   <td style="text-align:left;"> $TSLA 1k tomorrow would be nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:26:18 </td>
   <td style="text-align:left;"> $TSLA let me buy 9 more of this before it gets aways from me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:25:59 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:25:15 </td>
   <td style="text-align:left;"> 1 thousand + EOW 

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:23:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $AMZN 

35500 will be the top for the year for dow and all index tomorrow. Be prepared to short the crap out of the market tomorrow. For puts wait for some IV crush before loading. There might be some consolidation before the move down.  After tomorrow we will see the biggest correction since 2008. 
21700 is where the buck stops for dow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:21:44 </td>
   <td style="text-align:left;"> $TSLA likes to leave the gap. 862 gap fill? That&amp;#39;s almost 70 bucks move down from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:21:12 </td>
   <td style="text-align:left;"> $TSLA do they release Jan delivery numbers tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:20:06 </td>
   <td style="text-align:left;"> $ARKK  
 
Nice Channel support 
TODAY gives BUY signal (oir system) 
MACD wants to break out 
Much room to go UP 
 
I am very bullish. I have LONG postion in $TSLA $MELI $UPST $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:18:58 </td>
   <td style="text-align:left;"> $TSLA 

That hourly bullish Wolfewave is still in play.

https://youtube.com/shorts/GckdWt0SLfU?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:18:43 </td>
   <td style="text-align:left;"> latex4f7f9aa9f10c28e2f5d977c5f2b2a703NFLX
 
$BBIG
 

 🚨 BREAKING NEWS🚨

FIRST OF ALL I WOULD LIKE TO SAY “ FUCK YOU JIM CRAMER “ 

I have released the Cramer Index.

It follows every Cramer Buy, and holds everything he holds, updating in real time.

Right now, he is -13%.

Inversing Cramer&amp;#39;s positions is up by comparison.

See it here: unusualwhales.com/etfs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:15:27 </td>
   <td style="text-align:left;"> $SPOT $NFLX $HOOD $SPY $TSLA  alerted premarket for free. With P/L and entries and exits. https://vm.tiktok.com/TTPdhTpmxg/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:14:59 </td>
   <td style="text-align:left;"> $TSLA violent February rally incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:12:05 </td>
   <td style="text-align:left;"> $TSLA bears got trapped again! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:11:33 </td>
   <td style="text-align:left;"> $TSLA shit load of buys today dang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:07:20 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/EvAidWCXDqk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:07:05 </td>
   <td style="text-align:left;"> $TSLA https://driveteslacanada.ca/supercharger/tesla-supercharger-electrify-america-study/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:07:03 </td>
   <td style="text-align:left;"> $TSLA 3k by summer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:06:06 </td>
   <td style="text-align:left;"> $RMO well RMO killed it today. $NIO $TSLA $TEVA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:04:35 </td>
   <td style="text-align:left;"> $TSLA most Stocktwits bag holders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:02:32 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #4 ticker with sweep activity where institutions are trading options urgently with 21.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:02:26 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-31 Trade Analysis Video: 
https://www.youtube.com/watch?v=IOtaQM5n6rg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:02:15 </td>
   <td style="text-align:left;"> $TSLA tomorrow 🚀🚀🚀🚀🚀💎💎💎💎💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:01:46 </td>
   <td style="text-align:left;"> $TSLA 
Futes green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:00:47 </td>
   <td style="text-align:left;"> These 3 Analyst Ratings insights were important today:

1. $AMRN 📡 SVB Leerink reiterated coverage on Amarin Corp with a new price target: https://quantisnow.com/insight/2325193?s=qnps
2. $BA 📡 Jefferies reiterated coverage on Boeing with a new price target: https://quantisnow.com/insight/2326921?s=qnps
3. $TSLA 📡 Tesla upgraded by Credit Suisse with a new price target: https://quantisnow.com/insight/2323019?s=qnps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 08:00:43 </td>
   <td style="text-align:left;"> $TSLA bought 8 shares at 900. Expect to add another 10-12 shares below 1000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:57:57 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:57:39 </td>
   <td style="text-align:left;"> $TSLA https://driveteslacanada.ca/energy/giga-texas-rooftop-solar-spell-tesla/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:56:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

little $$$ is buying at this level 

BIG $$$ is selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:55:49 </td>
   <td style="text-align:left;"> $TSLA Dave is a good Tesla Bill. $78.5k is nothing to him from YouTube. He donated it all &amp;amp; added more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:52:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL
 
OMG CRAMER IS BOOLISH!!!😱📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:50:06 </td>
   <td style="text-align:left;"> $TSLA 

Dave:

I&amp;#39;d love to ask @elonmusk about his insistence to &amp;quot;drive&amp;quot; almost all new programs at Tesla

@elonmusk 
Dave, I know you’re a fan, but this is a silly question. I don’t drive programs because I want to, but because I have to.

Hey Dave ! No more silly question or else 👇

🙏🏻🐉🦅👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:49:46 </td>
   <td style="text-align:left;"> $SI Meme of 2022, like $GME $AMC $TSLA $CAR in 2021 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:48:50 </td>
   <td style="text-align:left;"> $TSLA Has the Bidet admin heard of this company? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:48:46 </td>
   <td style="text-align:left;"> $COIN $MANA.X $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:48:13 </td>
   <td style="text-align:left;"> Top Flow for the Week 🎁: $TSLA with a single PUT Trade for total premium worth $1049.9K Ranking #32 the Week | This was a TRADE trade.  | Visit SweepCast.com or Join our Premium Room For Access! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:47:46 </td>
   <td style="text-align:left;"> $TSLA it was up 90 today? Tomorrow it will be down 40. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:47:13 </td>
   <td style="text-align:left;"> $TSLA $SQ $SHOP $SE 

Talk about powerful moves today glad I’m holding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:46:04 </td>
   <td style="text-align:left;"> $TSLA when stock split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:41:57 </td>
   <td style="text-align:left;"> $TSLA 
All green across the board.
Even Biden got it up today.🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:41:39 </td>
   <td style="text-align:left;"> $TSLA CPI numbers for January are released Feb 10th.. cautiously bullish until then, trade safe lads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:40:05 </td>
   <td style="text-align:left;"> $TSLA shorts are playing with 🔥
This will be settling back over $1050 at the least
Mark this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:39:42 </td>
   <td style="text-align:left;"> $TSLA should pull back tomorrow hopefully not too much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:39:01 </td>
   <td style="text-align:left;"> $TSLA 📈📈📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:38:29 </td>
   <td style="text-align:left;"> $TSLA does anyone look at Cathy Woods investment and wonder if a split is in the near future. At this point she bought the low last week. Does she know something...?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:37:46 </td>
   <td style="text-align:left;"> $TSLA why the sudden drop AH? Looked like it was gonna go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:37:38 </td>
   <td style="text-align:left;"> $TSLA every other car I see in CA on 101 is basically a Tesla now, it’s fucking eye opening the transition the last two years, soon the entire country will be this way I fucking promise you, I didn’t believe it until I saw it with my own eyes, it’s fucking everywhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:36:58 </td>
   <td style="text-align:left;"> $SOFI not sure how I missed this partnership with $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:36:39 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:36:21 </td>
   <td style="text-align:left;"> $TSLA if we open at 1k tomorrow. I&amp;#39;m cry because of my 1k calls I sold. But I&amp;#39;ll still be happy with my 950s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:35:53 </td>
   <td style="text-align:left;"> $TSLA https://www.change.org/p/president-biden-please-acknowledge-tesla-s-ev-leadership?recruiter=2741609&amp;amp;utm_source=share_petition&amp;amp;utm_medium=twitter&amp;amp;utm_campaign=psf_combo_share_initial&amp;amp;recruited_by_id=fc3041a0-72eb-0130-6c6c-3c764e04a19b&amp;amp;share_bandit_exp=initial-32188532-en-US </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:35:26 </td>
   <td style="text-align:left;"> $TSLA to 1k 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:34:44 </td>
   <td style="text-align:left;"> $TSLA Biden needs to whisper Tesla in the mic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:34:04 </td>
   <td style="text-align:left;"> $TSLA fuck Tesla this stock is so unpredictable. Now it’s going down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:32:41 </td>
   <td style="text-align:left;"> $TSLA yes, quick panic sell. I STILL need to get in... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:32:31 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!! 

More than 33,000 people have signed a petition on change.org, asking President Joe Biden to acknowledge Tesla’s electric vehicle leadership. The petitioners have accused the president of ignoring Tesla TSLA, a non-union company, in favor of the traditional Detroit automakers, which are unionized.

🙏🏻🐉🦅

https://apple.news/AtBjd7a9aS5uu9Et3AgOK_Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:32:23 </td>
   <td style="text-align:left;"> $TSLA should have taken my company public. These days you can say that you&amp;#39;re working on developing Optimus prime as opposed to developing or improving existing products, and your company&amp;#39;s shares will recover after a 12% drop. Pretty amazing when the Fed created so much liquidity in the markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:31:56 </td>
   <td style="text-align:left;"> $TSLA $900 came Much faster than expected 👊🏼💥💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:31:47 </td>
   <td style="text-align:left;"> $TSLA how can the Nasdaq go from positive 445 to -48 red 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:31:47 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:31pm)

⦿ $TSLA is down 0.3% in the last 5 mins. 

⦿ There are 11 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 9.5% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:31:04 </td>
   <td style="text-align:left;"> $SPY latex2fa6b16c2bc436e57b309795012caceeNVDA - 93% call flow 
$AMD - 61% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:29:51 </td>
   <td style="text-align:left;"> Nice pop, $TSLA. 22nd-best performance in five years, so no 5-year-top-20 changes to report, however. Carry on! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:28:26 </td>
   <td style="text-align:left;"> $TSLA Three Day Rule... Rules!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:27:45 </td>
   <td style="text-align:left;"> $TSLA congrats, i sold out at 960 completely so never felt my all in account feel the 790-800s kill my account. 
 
Watching from the side lines to see if this isn&amp;#39;t just a fake bull run so hedgies benefit. 
 
Entering when volatility stops.. if split announced going all in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:27:25 </td>
   <td style="text-align:left;"> $TSLA Stocks were ripping today. Simulated Weekly $940.0 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:27:14 </td>
   <td style="text-align:left;"> $TSLA $959 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:26:50 </td>
   <td style="text-align:left;"> $TSLA $1100 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:26:26 </td>
   <td style="text-align:left;"> $TSLA how high can it go $SPY market Trade  
https://www.stockbookie.com/tsla-technical-analysis-1-31-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:26:25 </td>
   <td style="text-align:left;"> $TSLA oh so we’re about to blow.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:25:58 </td>
   <td style="text-align:left;"> $TMC the next big squeeze play??

 $GME $AMC $TSLA $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:25:01 </td>
   <td style="text-align:left;"> $TSLA  good shit  💯💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:24:03 </td>
   <td style="text-align:left;"> $AMC Up 1000% since last year but mainstream media writes negative articles against $AMC whereas  $HOOD  down 80 % but media is excited about its prospects and say it has bottomed out $GME $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:23:13 </td>
   <td style="text-align:left;"> $TSLA free ticket to exit longs! (Short term) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:22:58 </td>
   <td style="text-align:left;"> $TSLA 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:22:32 </td>
   <td style="text-align:left;"> $TSLA may see some red tomorrow. GL to all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:22:07 </td>
   <td style="text-align:left;"> $TSLA watch everyone turn into a sellout when it starts dropping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:21:40 </td>
   <td style="text-align:left;"> $TSLA split is coming! Elon wants his equity affordable for everyone! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:21:14 </td>
   <td style="text-align:left;"> $TSLA THis is going thru the roof tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:20:44 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $NFX $BIG  The Yield curve is important , an inverted Yield curve is a very reliable signal for a recession , an inversion occurs when the Long Term rates fall below the Short Term , Banks borrow Short Term and loan out Long Term , with inverted Yield , no money for the Hedgies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:20:03 </td>
   <td style="text-align:left;"> $TSLA I bought 60 shares Friday at 820... I think this will re-test 1200 very soon but the question is do sell at 1000 knowing that there will likely be short term profit taking before the re-test?... hmmmm.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:20:01 </td>
   <td style="text-align:left;"> Stocks Rise For A Second Day on January 31, Ahead of Turnaround Tuesday https://mottcapitalmanagement.com/stocks-rise-for-a-second-day-on-january-31-ahead-of-turnaround-tuesday/ $SHOP, $SQ, $TSLA  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:19:10 </td>
   <td style="text-align:left;"> $TSLA how can you stop the bull? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:18:07 </td>
   <td style="text-align:left;"> $PYPL large Call volume at 180 strikes. $TSLA also large call volume today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:18:04 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:15:59 </td>
   <td style="text-align:left;"> $TSLA 

Wut?  

What a beautiful set up!! 🚀

🙏🏻🐉🦅 (D) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:15:06 </td>
   <td style="text-align:left;"> $TSLA SSr gets turned On when a stock loses 10% on a day, likewise buying puts should be turned off when a stock gains 10% a day to avoid Bears extinction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:15:01 </td>
   <td style="text-align:left;"> $TSLA Elon should sell anal beads for the bears 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:14:58 </td>
   <td style="text-align:left;"> $TSLA Space X Launching! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:14:29 </td>
   <td style="text-align:left;"> $TSLA  $1000 tomorrowwwww.. 😳😳😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:13:17 </td>
   <td style="text-align:left;"> $TSLA 
Longs hopes of 1,000 ever again: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:12:41 </td>
   <td style="text-align:left;"> $TSLA  939 buy 936 sell 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:12:29 </td>
   <td style="text-align:left;"> $TSLA I have 1010 weeklies chances? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:12:02 </td>
   <td style="text-align:left;"> $TSLA bear suit might be coming back out tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:11:58 </td>
   <td style="text-align:left;"> $TSLA tesla will have another 10% day. I see 1010 in the near future </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:11:30 </td>
   <td style="text-align:left;"> $TSLA 
Gap up tomorrow 😋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:10:33 </td>
   <td style="text-align:left;"> $TSLA Market Share Shift 
 
https://www.youtube.com/watch?v=KWZ0BhzZ7Sk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:09:39 </td>
   <td style="text-align:left;"> $TSLA Market Share Shift 
 
https://www.youtube.com/watch?v=mTHd4PZji9M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:09:03 </td>
   <td style="text-align:left;"> $TSLA what a day. That’s why you don’t sell nor set stop losses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:08:27 </td>
   <td style="text-align:left;"> $TSLA Audi is bringing it 
 
https://www.youtube.com/watch?v=1SaqSIvon_U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:08:27 </td>
   <td style="text-align:left;"> $SPY $MSFT $AAPL $AMD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:08:23 </td>
   <td style="text-align:left;"> latex11879ab4fb2b3a800b9570db36cfee91$ plate of GAP UP in the morning...&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:07:31 </td>
   <td style="text-align:left;"> General Motors Q4 2021 Earnings Preview $GM $F $TSLA https://bit.ly/3ubJgeZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:06:10 </td>
   <td style="text-align:left;"> $XELA has not even started. Wait and see. 
Good opportunity for 
$AAPL $AMZN $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:04:53 </td>
   <td style="text-align:left;"> $TSLA Bullish Three Inside Up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:04:36 </td>
   <td style="text-align:left;"> $TSLA Loaded calls Friday, didn’t sell a single one today, I bought more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:03:35 </td>
   <td style="text-align:left;"> $TSLA on the watch for 970. 👀 ✅ 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:03:16 </td>
   <td style="text-align:left;"> $TSLA $SPY $MSFT $AAPL $AMD violent rally coming soon
🌙 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 07:02:49 </td>
   <td style="text-align:left;"> $TSLA Tesla fans complain that Biden ignores company’s EV leadership

https://www.marketwatch.com/story/tesla-fans-complain-that-biden-ignores-companys-ev-leadership-01643668313?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:58:08 </td>
   <td style="text-align:left;"> $SHOP $TSLA   $1000 + for THESE 2 FUCKERS TOMORROW.... MOM:  I&amp;#39;M FUCKING RICH!!!!  🔥🔥🔥🚀🚀🚀🚀🤑 
. 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:57:00 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla 440, 350, 900 respectively tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:55:51 </td>
   <td style="text-align:left;"> $MTCH 30% off Tomorrow ! $TSLA  $NFLX $AAPL $DOCU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:55:47 </td>
   <td style="text-align:left;"> $TSLA yus!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:55:09 </td>
   <td style="text-align:left;"> $BA $35 billion dollars order, if the same order confirmed for $TSLA it would have added Boeing market cap of $110 billion in single day. This hardly struggled to add 5 percent. Don’t think logics in the market. Price action is the KING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:54:50 </td>
   <td style="text-align:left;"> $TSLA 

Monthly profit: $1378

Green is Good 😊. 

Whole month trades n positive hope stays like it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:53:11 </td>
   <td style="text-align:left;"> $AMC $BBIG $TSLA $XELA $KSCP Follow me and check out my discord (in profile) for quality alerts. We have over 20 analysts and we are winning every day regardless of market conditions. We also provide an educational course/materials, weekly live classes, account challenges, monthly raffles, chat/activity cash prizes, 1 on 1 support, and more!  
 
Free Alerts and Free Trial(for those interested in premium). Free section available for all, no purchase necessary!  
 
Start trading and investing smart with us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:53:09 </td>
   <td style="text-align:left;"> $TSLA       💎      🙌🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:50:54 </td>
   <td style="text-align:left;"> $TSLA 💰💰💰💰💰💰💰👏💪🤙🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:49:35 </td>
   <td style="text-align:left;"> $TSLA 
 
All these Hertz Tesla rentals will be their own app store where customers can choose to upgrade their cars.  Tesla Insurance? OK. Unlimited supercharging for the trip duration? Autopilot? OK. FSD? Sure. Heated steering wheel? OK for $100.  Tesla/Hertz split 70/30.  Software will be a cash cow. 
 
 https://twitter.com/WholeMarsBlog/status/1488241595447013378 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:46:20 </td>
   <td style="text-align:left;"> $TSLA proof that I absolutely threw away a SHITLOAD of profit because of my bearish outlook on Bitcoin and the market going into this past  weekend. I am the HOG who got slaughtered. Congrats bulls I’m still bearish because I don’t have a choice but acknowledge I’m fucked. I took that photo last night to show my buddy how much money I was set to make if today was a bearish day.... and then today happened. Again, congrats bulls. Fuck you Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:45:33 </td>
   <td style="text-align:left;"> NOTE: IF market recovers this week, TSLA should see a run back up to 900s at most, it will be a tough one to get to, but some small pop may occur, eventhough the trend is now bearish, if you want me to do an update video on this stock explaining it, let me know in the comments section of the video. 
Please consider subscribing so you don&amp;#39;t miss out on other analysis videos on stocks you may be interested in. 
$TSLA HUGE analysis on our man ELON MUSK and his stock price as well as realistic PT&amp;#39;s and levels to watch for going forward after a massive massive run since last year. 
Like and subscribe for more unbiased trades, be a bull or a bear, you make money both ways! 
Youtube- https://www.youtube.com/watch?v=qNHsRE_D8CI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:44:49 </td>
   <td style="text-align:left;"> Watching to see what the market wants to do tomorrow. Should be interesting after things decided to go on a run today... $TSLA $NVDA $AMZN $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:44:27 </td>
   <td style="text-align:left;"> Shares of U.S. based electric vehicle maker $TSLA surged +10.68% on Monday at $936.72, after Swiss investment bank $CRP upgraded the stock to outperform &amp;amp; the broader market rebounded. Tesla had previously declined nearly 20% in January, amid a sell-off that dragged the entire Nasdaq down. The rebound brings Tesla&amp;#39;s market cap back to $849.96B. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:43:08 </td>
   <td style="text-align:left;"> $tsla get it over 940 brothers and no stopping 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:43:07 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow. 
 
https://youtu.be/eTeIZ_NERHI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:42:05 </td>
   <td style="text-align:left;"> $TSLA just under 900 for re-entry? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:42:00 </td>
   <td style="text-align:left;"> $TSLA: The EPS has been growing by 473.69% on average over the past 5 years. This is a very strong growth. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:38:42 </td>
   <td style="text-align:left;"> $SPY $QQQ  $TSLA 

We trapping bears 🐻!!

Shussssssss! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:38:02 </td>
   <td style="text-align:left;"> $TSLA nice looks like it wants green AH. Either way tomorrow could dip then rip. Still believe this can push 1k by Friday. Especially with techs reporting this week. If they don&amp;#39;t blow it of course. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:37:03 </td>
   <td style="text-align:left;"> $TSLA split this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:36:00 </td>
   <td style="text-align:left;"> $TSLA Besides &amp;#39;pride&amp;#39; and &amp;#39;status&amp;#39;, what stops Apple from collaborating with Tesla for an Apple car? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:35:58 </td>
   <td style="text-align:left;"> $TSLA Aunt Cathy looking at her recent Tesla gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:34:38 </td>
   <td style="text-align:left;"> $TSLA Open your eyes bear!
Scalping for a penny?
What a joke ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:34:29 </td>
   <td style="text-align:left;"> $TSLA Gordon L Johnson secret footage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:32:49 </td>
   <td style="text-align:left;"> $TSLA dam, my puts got a little destroyed today, left with a coin toss tomorrow. Could see upper 997 area tomorrow or drop to around 890 hoping for the latter but gl to bulls as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:32:39 </td>
   <td style="text-align:left;"> $SPY 9 million sold at 450.17..nothing to see here...right on the close. I&amp;#39;m sure it was a few retail traders! $UVXY $QQQ $TSLA $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:32:15 </td>
   <td style="text-align:left;"> $TSLA 4680 Y’s out of Texas soon. No one understands how big this is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:31:43 </td>
   <td style="text-align:left;"> $TSLA https://stockbet.io/home/TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:30:47 </td>
   <td style="text-align:left;"> $TSLA 

KISS!!!

Just BUY and HOLD 10 Years Min.

4K in 2025 then BOT Revenue Model kicks in and WS will finally gets it! More than a Car Co.

Infinite Labor Replacement means TSLA gets to 50T eventually.

https://youtu.be/Ywri4bvs7Wo

Sit on your hands! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:30:36 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-31 Largest Trades Data: 
https://www.youtube.com/watch?v=pDfRwas8PJ4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:30:10 </td>
   <td style="text-align:left;"> $TSLA want 1400+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:28:40 </td>
   <td style="text-align:left;"> $TSLA the next major near-term catalyst could be Tesla getting upgraded to AAA credit.  Would send the stock over $1300. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:28:35 </td>
   <td style="text-align:left;"> $TSLA holy hell I refuse to look at my puts. I went from up 25000 percent this past Friday, to being scared to open up the portfolio.    I will say this I need 780.... preferably by tomorrow. FUCK U TESLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:27:27 </td>
   <td style="text-align:left;"> $TSLA what is bigger?  The potential for Tesla-bot?  Or your mom? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:25:37 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #7 ticker with unusual activity from institutional traders with an average of 26% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:23:35 </td>
   <td style="text-align:left;"> $TSLA https://electrek.co/2022/01/31/tesla-expands-program-open-supercharger-network-electric-cars-other-automakers-norway-france/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:21:13 </td>
   <td style="text-align:left;"> $TSLA volume is even worst in AH, just don’t think it bodes well for bulls…IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:20:55 </td>
   <td style="text-align:left;"> $PLTR $QQQ $TSLA $AAPL They believe Palantir its way too discounted and extremely cheap data is the new oil expecting a hard pop up into Earnings in two weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:20:40 </td>
   <td style="text-align:left;"> $TSLA 1.5 mill deliveries this year not including gigas. Gigas will be the gravy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:20:12 </td>
   <td style="text-align:left;"> $AAPL $GOOG $TSLA $AMD $SPY  
 
Tech stock moving higher into rising interest rate environment after refusing to issue future guidance. 
 
Short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:18:37 </td>
   <td style="text-align:left;"> $TSLA Credit Suisse must need to get out, upgrade on &amp;#39;fundamentals&amp;#39; 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:18:25 </td>
   <td style="text-align:left;"> $TSLA the riskiest stock I own </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:17:24 </td>
   <td style="text-align:left;"> $TSLA $tqqq puts and retail bears got destroyed in every stocks today lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:15:52 </td>
   <td style="text-align:left;"> $TSLA beautiful day for call buyers, including share holders. I bought puts late in the afternoon for a trade by Friday. I firmly believe supply chain constraints is real, especially semis. $AMD earnings will give a nice hint. Tagging bullish because I love tesla, but right now it is all about making trades. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:14:37 </td>
   <td style="text-align:left;"> $TSLA Trillion dollar MC company moving 10%. jeez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:14:18 </td>
   <td style="text-align:left;"> $NIO officialy the lowest valued EV stock. Less than 1/10 Tesla’s revenue, with Neo park the gross profit will rise significantly, and the ET5 and ET7 are soon(by far) the hottest EV’s on the market! Yet a valuation that’s 1/20 from $TSLA   1/2 of $LCID ,… 
—&amp;gt; Short term financial strength is very optimal (Current ratio: 2,61) and profitability is almost a FACT!
—&amp;gt; $68 EOY, screenshot it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:14:06 </td>
   <td style="text-align:left;"> $TSLA this will fall to $700 in two weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:13:59 </td>
   <td style="text-align:left;"> $TSLA lets run this 15% tomorrow 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:13:46 </td>
   <td style="text-align:left;"> $TSLA what price you see this in say 2 years or 5 years? If covid pandemic over and stable economy? Ballpark figures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:12:58 </td>
   <td style="text-align:left;"> $ARKK $TSLA $SQ $BTC.X  Live now with Cathie, Dorsey and Elon!  
 
https://www.youtube.com/watch?v=Sj8OggxYGnk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:12:41 </td>
   <td style="text-align:left;"> $TSLA 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:12:31 </td>
   <td style="text-align:left;"> $TSLA  my only lifetime stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:11:11 </td>
   <td style="text-align:left;"> $TSLA Elon is daddy  (no homo) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:10:52 </td>
   <td style="text-align:left;"> $SPY tomorrow is soooo big for the health of the future of the markets... Let&amp;#39;s hope we stay green ... Covid is going down. Bottom line.

 Everything else is just speculation. $qqq $DWAC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:10:46 </td>
   <td style="text-align:left;"> $TSLA entire market was green . And darkpool was strange today . Big guys didn’t buy anything which means the bottoms not here yet . Interesting day tho , congrats bulls 💰 . I’m still holding puts here tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:10:05 </td>
   <td style="text-align:left;"> $AMTX AEMETIS (NASDAQ:AMTX) USDA is giving $700 Mln as relief for biofuel producers, another clear sign of government support for CO2 reduction activities $CVX $XOM $TSLA 

Deadline to apply is 11 February

A few millions dollar can arrive soon to Aemetis 

http://biomassmagazine.com/articles/18678/usda-amends-program-offering-700m-in-covid-19-aid-for-biofuels </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:08:12 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla&amp;#39;s gross margins and profitability are ahead of everyone, says Mizuho analyst https://www.stck.pro/news/TSLA/22290370 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:07:26 </td>
   <td style="text-align:left;"> $TSLA you did good today boo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:07:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK $AAPL $TSLA 
 
If JPOW can keep pumping asset prices and keep inflation moving higher soon enough every Millennial will be able to afford a home! 
 
JPOW pumping asset prices for Millennial!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:07:06 </td>
   <td style="text-align:left;"> $TSLA OEMs paying Tesla for the privilege to use their chargers: 
 
https://www.teslarati.com/tesla-non-tesla-supercharer-pilot-program-france-norway/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:07:01 </td>
   <td style="text-align:left;"> $TSLA Stocks were ripping today. Simulated Weekly $940.0 CALLS for Tuesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:06:17 </td>
   <td style="text-align:left;"> $TSLA 1500C Exp:20-Jan-23 --  🚀 Total(Day): $30,300 
$TSLA 1725C Exp:17-Mar-23 ↑↑  🚀 &amp;lt;R&amp;gt; Total(Day): $236,805 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:06:15 </td>
   <td style="text-align:left;"> $TSLA 1200C Exp:17-Jun-22 --  🚀 Total(Day): $153,580 
$TSLA 1250C Exp:18-Feb-22 ↑  🚀 &amp;lt;R&amp;gt; Total(Day): $218,256 
$TSLA 1300C Exp:16-Sep-22 --  🚀 Total(Day): $271,600 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:06:12 </td>
   <td style="text-align:left;"> $TSLA 1050C Exp:18-Mar-22 ↑  🚀 Total(Day): $28,040 
$TSLA 1075C Exp:18-Mar-22 ↑  🚀 Total(Day): $27,090 
$TSLA 1100C Exp:04-Feb-22 --  🚀 Total(Day): $31,000 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:06:09 </td>
   <td style="text-align:left;"> $TSLA 1010C Exp:18-Feb-22 ↑  🚀 &amp;lt;R&amp;gt; Total(Day): $149,193 
$TSLA 1020C Exp:04-Feb-22 --  🚀 Total(Day): $33,500 
$TSLA 1020C Exp:18-Mar-22 ↑  🚀 Total(Day): $48,000 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:06:06 </td>
   <td style="text-align:left;"> $TSLA 1000C Exp:20-Jan-23 --  🚀 &amp;lt;R&amp;gt; Total(Day): $173,260 
$TSLA 1000C Exp:18-Mar-22 ↑  🚀 Total(Day): $530,490 
$TSLA 1010C Exp:18-Mar-22 ↑  🚀 Total(Day): $40,150 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:06:03 </td>
   <td style="text-align:left;"> $TSLA 950C Exp:04-Feb-22 --  🚀 &amp;lt;R&amp;gt; Total(Day): $1,696,328 
$TSLA 980C Exp:20-May-22 ↑↑  🚀 Total(Day): $34,820 
$TSLA 1000C Exp:04-Feb-22 --  🚀 &amp;lt;R&amp;gt; Total(Day): $965,169 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:05:26 </td>
   <td style="text-align:left;"> $TSLA Back to $1200 quickly and swiftly young lads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:05:25 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $NFLX $BBIG 

 🚨 BREAKING NEWS🚨

FIRST OF ALL I WOULD LIKE TO SAY “ FUCK YOU JIM CRAMER “ 

I have released the Cramer Index.

It follows every Cramer Buy, and holds everything he holds, updating in real time.

Right now, he is -13%.

Inversing Cramer&amp;#39;s positions is up by comparison.

See it here: unusualwhales.com/etfs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:05:15 </td>
   <td style="text-align:left;"> $TSLA green tomorrow as well! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:04:47 </td>
   <td style="text-align:left;"> $TSLA it is not sus, that Tesla is up 90 bucks, Tesla can run to 1300 in one day and it will be totally deserved.  
But when such BS as RIDE is up 22%, then it is VERY sus... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:03:59 </td>
   <td style="text-align:left;"> $TSLA RIP to all puts today lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:01:39 </td>
   <td style="text-align:left;"> $TSLA buying calls at the end of a 10% day isn’t exactly smart imo.. but hey I’ve seen crazier shit happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:01:37 </td>
   <td style="text-align:left;"> $TSLA expect a drop tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:01:22 </td>
   <td style="text-align:left;"> $TSLA can’t get away from all the good press. Just put your phones down and come back before Friday 🤷🏼‍♀️💁🏼‍♀️💎🙌🏼 💵 gains imminent!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:00:50 </td>
   <td style="text-align:left;"> $TSLA $SPY latex0c0a6dce6890c6148a4c8ba5bf8ac2dfTSLA 1.123m (60% call/40% put)
$NVDA 629k (73% call/27% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:00:26 </td>
   <td style="text-align:left;"> $TSLA great start this week if you looking to short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 06:00:22 </td>
   <td style="text-align:left;"> $TSLA sold waayyy to early. Paperhanded that shit. Still holding my 950s though 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:59:49 </td>
   <td style="text-align:left;"> $TSLA test $1000 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:59:36 </td>
   <td style="text-align:left;"> $TSLA Who’s diamond handling over here??????? 💎🚀🙌🏼🌙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:59:31 </td>
   <td style="text-align:left;"> $TSLA Exhibit A: prototype cars that will never reach meaningful production rates 
 
https://www.youtube.com/watch?v=4tujk8FDP8Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:58:28 </td>
   <td style="text-align:left;"> $TSLA $955 AH 🎈🎈🎈💎💎💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:58:11 </td>
   <td style="text-align:left;"> $TSLA 💎💎💎💎💎💎💎💎💎💎💎💎💎💎🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈🎈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:57:11 </td>
   <td style="text-align:left;"> $TSLA Jesus… watching Gordon talking about Tesla is like the Twilight Zone… why is he constantly yelling… and his head also keeps expanding while he’s at it… media is pure comedy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:57:06 </td>
   <td style="text-align:left;"> $TSLA bear be like, &amp;quot; tesla is red after hour&amp;quot; I&amp;#39;m in at 400$.

Ahhahahahahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:56:38 </td>
   <td style="text-align:left;"> $TSLA 

@elonmusk 

Denmark just ended Covid restrictions!!

🙏🏻🐉🦅👀

https://www.bloomberg.com/news/articles/2022-01-26/denmark-to-end-covid-curbs-as-premier-deems-critical-phase-over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:56:28 </td>
   <td style="text-align:left;"> $TSLA 

OK, This is no good.  It&amp;#39;s going down inch by inch. Now I know I went crazy chasing up.

Tomorrow&amp;#39;s prognosis, anybody!?

.
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:55:27 </td>
   <td style="text-align:left;"> $TSLA idiots. Actual idiots. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:53:44 </td>
   <td style="text-align:left;"> $TSLA tomorrow $1000 plus 🌙🌙🌙🌙🌙🌙🌙🌙🌙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:53:01 </td>
   <td style="text-align:left;"> $TSLA here we go 💐💐💐💐💐💐💐💎💎💎💎💎💎💎🚀🚀🚀🚀💎💎💎💎💎💎💎💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:51:47 </td>
   <td style="text-align:left;"> $TSLA Elon can make Tesla bigger than Amazon reports out!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:51:01 </td>
   <td style="text-align:left;"> $TSLA  Elon Musk Could Make TSLA Stock Even Bigger Than Amazon

https://investorplace.com/2022/01/elon-musk-could-make-tsla-stock-even-bigger-than-amazon/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:50:39 </td>
   <td style="text-align:left;"> $TSLA 

It Is NOT a car company !! 

You won’t get margins of 30+% if it’s.. don’t believe me ask $GM $F !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:49:04 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:48:50 </td>
   <td style="text-align:left;"> $TSLA such a crazy market where companies with a market cap like this can move 10% in a day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:48:45 </td>
   <td style="text-align:left;"> $TSLA too far too fast. Dump tomorow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:48:41 </td>
   <td style="text-align:left;"> $TSLA cross over 1000 by end of the week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:48:00 </td>
   <td style="text-align:left;"> $TSLA  
 
$TSLA Solid day in the markets. Strong volume and significant price action. Saw an increase in social sentiment and momentum in the morning and continue through the day. Will be keeping an eye on this tonight an first thing tomorrow. 
 
You can keep an eye on the real-time trend here https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220131 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-01 05:47:57 </td>
   <td style="text-align:left;"> $TSLA i bought calls ,hope they don&amp;#39;t tank the market tomorrow! </td>
  </tr>
</tbody>
</table></div>

---
