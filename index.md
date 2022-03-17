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



Last Updated: 2022-03-17 08:50:29 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/singapore/domestic-exports-of-non-oil-nodx-pctyoy </td>
   <td style="text-align:left;"> 2022-03-17 08:44:48 </td>
   <td style="text-align:left;"> Singapore Exports Growth Weakest in 6 Months </td>
   <td style="text-align:left;"> Singapore's non-oil domestic exports (NODX) grew by 9.5 percent year-on-year in February of 2022, easing sharply from a 17.6 percent rise in the previous month, and below market consensus of a 15.7 percent growth. It was the lowest growth in NODX since last August. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/unemployment-rate </td>
   <td style="text-align:left;"> 2022-03-17 08:44:47 </td>
   <td style="text-align:left;"> Australia Jobless Rate Falls to 13-1/2-Year Low </td>
   <td style="text-align:left;"> Australia's seasonally adjusted unemployment was at 4.0% in February 2022, compared with market consensus of 4.1% and January's figure of 4.2%. This was the lowest jobless rate since August 2008, amid further easing of COVID-19 restrictions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-17 08:35:21 </td>
   <td style="text-align:left;"> Brazil 10Y Bond Yield Eases from 2-Year High </td>
   <td style="text-align:left;"> Brazil’s 10-year government bond yield eased to 12.2% from the two year high of 12.6% touched on March 14th as ceasefire talks between Ukrainian and Russian delegations and lower commodity prices lowered demand for government debt. On the monetary policy front, the Central Bank of Brazil increased the Selic rate by 100bps on its March meeting, as expected, and signaled another 100bps for its next meeting. Meanwhile, investors monitor state-backed oil company Petrobras and its gasoline pricing strategy amid high volatility in crude oil markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-03-17 07:48:13 </td>
   <td style="text-align:left;"> Brazilian Real Strengthens Following Interest Rate Decision </td>
   <td style="text-align:left;"> The Brazilian real strengthened to 5.07 per USD from the two-week low of 5.17 per USD after investors digested rate hikes from both the Central Bank of Brazil and the US Federal Reserve. The Brazilian central bank increased its main rate by 100bps for its 9th consecutive hike, while signaling another 100bps increase in its next meeting in an effort to curb secondary impacts of commodity supply shocks. At the same time, the Fed increased the funds rate by 25bps and signaled 6 additional hikes this year. Meanwhile, developments in talks between Russia and Ukraine also eased demand for haven currencies, as investors continue to monitor commodity prices and the terms of trade with Brazilian agricultural goods and metals to gauge the demand for the real. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/gdp-growth </td>
   <td style="text-align:left;"> 2022-03-17 07:13:27 </td>
   <td style="text-align:left;"> New Zealand GDP Expands Less than Expected </td>
   <td style="text-align:left;"> New Zealand’s economy expanded by 3 percent on the quarter in the three months leading to December of 2021, following a downwardly revised 3.6 percent contraction in the previous period and missing estimates of a 3.2 percent growth rate. Growth was underpinned by services which were able to operate better in the fourth quarter of 2021 due to lower Covid-19 restrictions, reflected in a 6.7 percent rise in retail trade and accommodation output. Meanwhile, goods-production industries expanded by 6.5 percent while primary industries contracted 2.2 percent. Considering the full 2021, the Kiwi economy contracted 1.4 percent, compared to the 2.2 percent increase in 2020, despite the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/16/europe/ukraine-railways-eu-kyiv-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-17 06:26:13 </td>
   <td style="text-align:left;"> Ukraine's rail chief reveals how EU leaders got in and out of Kyiv: 'Everyone should understand that it's war' - CNN </td>
   <td style="text-align:left;"> (CNN)The chairman of Ukrainian Railways has said that the Polish, Czech and Slovenian Prime Ministers, who traveled by train for a Tuesday meeting with Ukrainian President Volodymyr Zelensky in Kyiv, took a "strong step" to show support for his war-torn country, albeit a "naïve" one.                   , "That was really important for us, even if it was naïve," Oleksandr Kamyshin told CNN Wednesday.                                                                                                                                                                                                                , Kamyshin, the national rail system's top executive, called the move naïve because the delegation of EU leaders announced their travel plans while they were still en route to the capital.                                                                                                                      , Kyiv has been terrorized by a campaign of Russian airstrikes that have hit residential areas in recent days, including several apartment blocks -- prompting a 35-hour curfew that began Tuesday evening.                                                                                                       , Ukraine's rail system is not immune to those strikes. But Tuesday morning, Polish Prime Minister Mateusz Morawiecki announced that he, along with Slovenian Prime Minister Janez Janša and Czech Prime Minister Petr Fiala, were heading toward Kyiv.                                                           , "I was keeping their secret, but when I saw something was published online, it surprised me. I didn't understand that," Kamyshin told CNN.                                                                                                                                                                      , While en route, Morawiecki wrote in a Facebook post: "It is our duty to be where history is being made. Because it's not about us, it's about the future of our children who deserve to live in a world free from tyranny."                                                                                     , Fiala also tweeted that the "purpose of the visit is to confirm the unequivocal support of the entire European Union for the sovereignty and independence of Ukraine."                                                                                                                                          , Security concerns have been at the top of the 37-year-old rail executive's mind ever since the war began.                                                                                                                                                                                                       , Kamyshin and his top deputies have spent the last three weeks criss-crossing the country, managing the railway's 321,000 employees and roughly 1,450 stations on the move. He believes that railway management is a target for Russian bombs, so staying in near-constant motion is a matter of personal safety., "Even to my kids I don't tell them, 'Hey don't reveal your location,' because everyone should understand that it's war. I can't instruct prime ministers," he said.                                                                                                                                             , According to Kamyshin, it was the Prime Ministers' idea to travel to Kyiv by train, believing it was the safest mode of transport.                                                                                                                                                                              , He agreed, despite a train station in Zaporizhzhia being hit Wednesday morning by a Russian bomb, shortly after their visit, which left a crater-sized hole on the railway tracks, and damaged the rail station.                                                                                                , "Any smart person would choose the train over a car these days," he said. "Even with bombing everywhere, stations and trains are the safest places in the country right now."                                                                                                                                   , Kamyshin said the delegation traveled on a special train with four of the railway's newest sleeper cars. The only other passengers were part of the delegation or security.                                                                                                                                     , "It was a regular, normal train, with normal rail cars," he said. "So [the delegation's route] was not more special than the others. ... It was the same track that normal passengers take as well."                                                                                                            , The journey took around eight or nine hours, he said. The leaders spent a few hours with Zelensky and his team before taking an overnight train back to Poland.                                                                                                                                                 , "For me, it's the best assessment of the railways if foreign prime ministers chose railways instead of a car or a helicopter, or any other option," he said.                                                                                                                                                    , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/interest-rate </td>
   <td style="text-align:left;"> 2022-03-17 06:26:00 </td>
   <td style="text-align:left;"> Brazil Hikes Interest Rate to 11.75% as Expected </td>
   <td style="text-align:left;"> The Central Bank of Brazil unanimously decided to raise the Selic rate by 100 basis points to 11.75% on March 16th, as expected, while signaling another 100bps rate hike at its next meeting. It was the ninth consecutive interest rate hike since it has started tightening. The committee noted that the tighter monetary conditions are aimed to combat secondary impacts of surging commodity prices due to the current supply shock and maintained that it will continue evaluating the situation and alter its guidance as necessary. The Copom also noted that inflation continues to surprise negatively, while fourth quarter growth expectations rose above previous expectations. The last consumer inflation reading pointed to 10.5% on the year, well above the central bank’s target of upper bound of the central bank target of 5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/16/business/media/chris-cuomo-cnn-filing.html </td>
   <td style="text-align:left;"> 2022-03-17 06:13:27 </td>
   <td style="text-align:left;"> Chris Cuomo Seeks $125 Million From CNN - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Mr. Cuomo’s lawyers claim the money is owed to him for wrongful termination.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , By John Koblin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The former cable news anchor Chris Cuomo is seeking $125 million from CNN for what his lawyers claim was wrongful termination when the cable news network fired him in December.                                                                                                                                                                                                                                                                                                                                                                                                            , In a legal filing on Wednesday with JAMS, an arbitration organization, Mr. Cuomo’s lawyer, Bryan Freedman, said he was seeking the $15 million that Mr. Cuomo was owed under his contract as well as “future wages lost as a result of CNN’s efforts to destroy his reputation.”                                                                                                                                                                                                                                                                                                            , Mr. Cuomo was fired days after the New York attorney general released a trove of emails and text messages that indicated he had been intimately involved with providing strategic advice to his brother, Andrew M. Cuomo, who was confronting a mounting sexual harassment scandal while serving as governor of New York.                                                                                                                                                                                                                                                                   , Mr. Cuomo was fired by Jeff Zucker, CNN’s president at the time. Mr. Cuomo has maintained that Mr. Zucker was aware of his dealings with his brother, an accusation that Mr. Zucker has denied.                                                                                                                                                                                                                                                                                                                                                                                             , An internal investigation into Mr. Cuomo commissioned by WarnerMedia, CNN’s parent company, soon imperiled Mr. Zucker as well. Mr. Zucker resigned under pressure in early February after the investigation revealed that he had failed to disclose a romantic relationship with the network’s head of marketing and communications, Allison Gollust. WarnerMedia would later say that “the investigation found violations of company policies, including CNN’s news standards and practices, by Jeff Zucker, Allison Gollust and Chris Cuomo.” Mr. Zucker and Ms. Gollust have denied that., Mr. Freedman, Mr. Cuomo’s lawyer, said on Wednesday that it “should by now be obvious that Chris Cuomo did not lie to CNN about helping his brother.”                                                                                                                                                                                                                                                                                                                                                                                                                                       , “In fact, as the limited information released from WarnerMedia’s investigation makes clear, CNN’s highest-level executives not only knew about Chris’s involvement in helping his brother but also actively assisted the governor, both through Chris and directly themselves,” Mr. Freedman continued.                                                                                                                                                                                                                                                                                     , A CNN spokesman declined to comment. Deadline reported Mr. Cuomo’s legal filing earlier on Wednesday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-03-17 06:11:33 </td>
   <td style="text-align:left;"> New Zealand GDP Growth Picks Up in Q4 </td>
   <td style="text-align:left;"> New Zealand’s economy expanded 3% from a year earlier in the fourth quarter of 2021, from a downwardly revised 0.2% contraction in the prior period and below market expectations of a 3.3% increase. The economy expanded amid looser Covid-19 restrictions throughout the country, in sharp contrast with the previous quarter. On a quarterly basis, the economy grew 3 percent in the three months leading to December, after contracting 3.6 percent in the prior quarter. Considering the full 2021, the Kiwi economy contracted 1.4 percent, compared to the 2.2 percent increase in 2020, despite the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/saudi-arabia/interest-rate </td>
   <td style="text-align:left;"> 2022-03-17 05:43:39 </td>
   <td style="text-align:left;"> Saudi Arabia Hikes Repo Rate in Line with Fed </td>
   <td style="text-align:left;"> The Saudi Central Bank (SAMA) increased both its repo rate and its reverse repo rate by 25 basis points to 1.25% and 0.75%, respectively, on March 16th 2022. The increases tracked the hike in the US Federal Reserve benchmark rate on the same day. The central bank said that the adjustments are consistent with objectives of monetary policy stability and stability of the financial sector amid evolving international monetary conditions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-arab-emirates/interest-rate </td>
   <td style="text-align:left;"> 2022-03-17 05:18:37 </td>
   <td style="text-align:left;"> UAE Raises Interest Rate in Line with Fed </td>
   <td style="text-align:left;"> The Central Bank of the United Arab Emirates increased the base rate of its overnight deposit facility by 25bps on March 16th 2022, tracking the increase in the federal funds rate. At the same time, the central bank maintained the rate on borrowing short-term liquidity from all standing credit facilities as 50bps above the base rate at 2%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/nordstrom-resumes-dividend/story.aspx?guid={5777F236-A284-4057-A7B0-BC6B645294A4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 05:03:17 </td>
   <td style="text-align:left;"> Nordstrom resumes dividend - MarketWatch </td>
   <td style="text-align:left;"> Nordstrom Inc. 
        JWN,
        +3.32%
       said late Wednesday it is reinstating a quarterly dividend, with the company's board of directors approving a quarterly dividend of 19 cents a share payable April 13 to shareholders of record at the close of business on March 28. Nordstrom shares rose 1.2% in the extended session after ending the regular trading day up 3.3%. 
, Starbucks announced that CEO Kevin Johnson will retire in April, with Howard Schultz stepping in on an interim basis and helping with the search for a successor.                                                                                                                                                                                                                              , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/lennar-stock-rises-more-2/story.aspx?guid={8D202C7B-45B8-4CC8-BC15-657CE1E15579}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 04:55:10 </td>
   <td style="text-align:left;"> Lennar stock rises more than 2% after Q1 profit tops views - MarketWatch </td>
   <td style="text-align:left;"> Lennar Corp. 
        LEN,
        +2.60%
       shares rose more than 2% in the extended session Wednesday after the home builder reported first-quarter profit that topped Wall Street expectations and said its "strong sales" reflected ongoing strength in the housing market. Lennar said it earned $503.6 million, or $1.69 a share, in the first quarter, compared with $1 billion, or $3.20 a share, in the year-ago quarter. Adjusted for one-time items, Lennar earned $2.70 a share. Revenue rose 16% to $6.2 billion. Analysts polled by FactSet expected Lennar to report adjusted EPS of $2.60 on revenue of $2.6 billion. "Our sales pace remained strong and consistent throughout the quarter, while strong traffic to our welcome home centers and website suggests that demand remains strong for the foreseeable future," Chairman Steve Miller said in a statement. Margins were strong even as materials costs and wages have increased, he said. Deliveries were "constrained" by supply-chain disruptions but were in line with the guidance given at the beginning of the quarter, he said. Lennar increased its guidance on full-year deliveries and gross margins, saying it expects to deliver about 68,000 homes, up from guidance of 67,000 homes. , "As towering skyscrapers rose in Moscow atop a pile of oil cash, Putin’s government became more backward-looking and more isolated," Lukas I. Alpert writes in a commentary piece.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 04:54:00 </td>
   <td style="text-align:left;"> Brazilian Equities Snap 4-Day Losing Run </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Ibovespa, closed 2% higher at 111,112 on Wednesday after four consecutive sessions of declines, tracking North American bourses amid the 25bps rate hike by the Federal Reserve, as expected, while investors awaited the monetary policy decision by the Copom due after the session’s close. An apparent advance in negotiations between Russia and Ukraine also improved market sentiment along with China’s pledge to roll out stimulus measures and policies in favor capital markets. On the corporate front, Banco Inter(8.9%) and EcoRodovias (8.2%) were among the top performers. At the same time, shares in the country's biggest tourism agency CVC Brasil Operadora e Agencia de Viagens jumped 16% after reporting upbeat Q4 earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2022-03-17 04:52:59 </td>
   <td style="text-align:left;"> Australian Dollar Appreciates </td>
   <td style="text-align:left;"> The Australian dollar regained ground to around $0.73, moving further away from a 2-week low of 0.718 hit on Monday as the US dollar edged lower after Fed Chair Powell assured investors the Fed hikes won't derail the economic recovery. The FOMC raised the interest rates for the first time since 2018 and signaled room for six rate hikes this year but during the press conference, the Chair emphasized that the US economy can withstand tighter monetary conditions and that the likelihood of a recession is “not particularly elevated”. Still, the Aussie remains pressured by easing commodity prices on ongoing peace talks between Russia and Ukraine and fears of a Covid-induced demand slowdown in China. The Reserve Bank of Australia kept the cash rate unchanged at a record low of 0.1% in its last meeting, as widely expected. However, Governor Philip Lowe adopted a more hawkish tone recently, saying a rate hike is plausible this year as the Russia-Ukraine war threatened to fuel further inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/williams-sonoma-q4-profit-beats-expectations/story.aspx?guid={8C9B81D2-5283-4E49-AC2D-4A028BFF6697}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 04:33:31 </td>
   <td style="text-align:left;"> Williams-Sonoma Q4 profit beats expectations, retailer raises dividend by 10% - MarketWatch </td>
   <td style="text-align:left;"> Shares of Williams-Sonoma Inc. 
        WSM,
        +2.65%
       rallied more than 10% in the extended session Wednesday after the retailer reported quarterly profit above expectations and raised its dividend. Williams-Sonoma said it earned $403 million, or $5.41 a share, in the fourth quarter, compared with $309 million, or $3.92 a share, in the year-ago quarter. Revenue rose to $2.5 billion, from $2.3 billion a year ago. Adjusted for one-time items, the company earned $5.42 a share. FactSet consensus called for adjusted earnings of $4.82 a share on sales of $2.6 billion. "These results reflect the resilience in our business model, as we successfully navigated unprecedented challenges within the supply chain, material and labor shortages, and capacity limitations from our incredible consumer demand," Chief Executive Laura Alber said in a statement. The company said it expects a fiscal 2022 financial performance "in line with our long-term financial guidance of mid-to-high single digit annual net revenue growth, increasing revenues to $10 billion by fiscal year 2024," as well as operating margins "relatively in-line with our fiscal year 2021 operating margin." Separately, the retailer said its board has authorized a 10% dividend increase to 78 cents a share, payable on May 27, and also has approved a new $1.5 billion stock buyback program, superseding the about $750 million that remains outstanding under the company's current stock repurchase authorization. The moves were thanks to an "impressive finish to fiscal 2021, our strong liquidity position, and our operating cash flows," the company said. Williams-Sonoma stock ended the regular trading day up 2.7%., Fully vaccinated people will need a fourth shot later in 2022, according to the head of Pfizer Inc., who said that COVID-19 is not going to just go away in the coming years.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/bidens-oil-blame-game-backfire </td>
   <td style="text-align:left;"> 2022-03-17 04:32:53 </td>
   <td style="text-align:left;"> Biden's oil blame game backfires </td>
   <td style="text-align:left;"> Red Apple Group Chairman and CEO John Catsimatidis argues if Biden declared energy independence and changes his policies price of oil and gas will decrease.                                                                                                                                                                                                                                                                        , President Biden blamed Russia for the big recent jump in gasoline prices, but it isn’t flying on Main Street, so now he’s placing blame with big U.S. energy companies.                                                                                                                                                                                                                                                             , "Oil prices are decreasing, gas prices should too," the president tweeted. "Last time oil was $96 a barrel, gas was $3.62 a gallon. Now it's $4.31.  Oil and gas companies shouldn't pad their profits at the expense of hardworking Americans."                                                                                                                                                                                    , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                                                , A wonky red and blue trading chart using Bloomberg data was also included, but it may have backfired. Javier Blas, who works for the financial data and news company, tweeted a chart that actually seemed to dispute the president's contention that somehow oil companies are padding their profits at the expense of the American people.                                                                                        , EXXON MOBIL CEO SAYS OIL COMPANIES WERE IN TOUGH POSITION BEFORE UKRAINE-RUSSIA WAR                                                                                                                                                                                                                                                                                                                                                 , "I see the White House chart is sourced to Bloomberg LP data. As a public service, I'm going to suggest a different chart. Mine has some of the same elements (WTI oil and retail US gasoline price), but instead, I normalized it, and use Dec 1, 2021, = 100," Blas tweeted.                                                                                                                                                      , OIL PRICES VOLATILE ON MIXED SUPPLY DATA                                                                                                                                                                                                                                                                                                                                                                                            , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                             , Mr. Blas's chart shows the opposite, that oil companies failed to pass on the cost of the crude price increase to customers at the gas pump.                                                                                                                                                                                                                                                                                        , According to most recent data from the Energy Information Administration (EIA), 56% of the cost of gasoline is the hard cost of crude oil that the refiners have to pay. The chart shows that the price increase at the pump failed to keep up with the incredible jump in crude oil prices. It also shows that oil companies were making less money, not more on the way up.                                                       , That is why it seems to some that prices go up much faster than they fall because, after a big price spike in crude, most oil companies get squeezed on the revenue side on the way up. In other words, based upon that chart, it's very clear that energy companies did not pass on the entire price increase in the cost of crude oil and may have to keep prices higher to make back revenue they lost on the way up.            , They better make money because, under President's Biden new regulations and tax proposals on oil companies, it will make it much more expensive to replace spent supplies of both oil and gasoline.                                                                                                                                                                                                                                 , President Biden and the White House COVID-19 Response Team participate in a virtual call with the National Governors Association from the South Court Auditorium of the Eisenhower Executive Office Building of the White House Complex Dec. 27, 2021. (Kent Nishimura/Los Angeles Times via Getty Images / Getty Images)                                                                                                           , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                         , Biden has to understand that U.S. oil companies and oil workers are not our enemies or the enemies of freedom. Iran is an enemy of freedom. Maduro in Venezuela is an enemy of freedom. Let's face it: When we think of freedom, we don't think of Saudi Arabia. So why is President Biden so quick to blame the oil companies with misleading facts instead of working with them to produce more oil to keep gasoline prices down? , The White House would not need any scapegoats if we began to value our domestic energy producers.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 04:29:00 </td>
   <td style="text-align:left;"> Toronto Shares Book Gains on Wednesday </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite index closed 1.3% higher at 21,468 on Wednesday, tracking US stocks as traders digested domestic price data and the rate hike by the US Fed, while continuing to monitor talks between Moscow and Kyiv. Equities momentarily fell to the flatline after the FOMC signaled room for six rate hikes this year but rebounded to close amid intra-day highs after Chair Powell said the US economy is well positioned to handle a tighter monetary environment. At the same time, Canada’s inflation rate quickened to an over three-decade high of 5.7%, surpassing market expectations of 5.5% in February and marking the eleventh straight month above the central bank’s target of 1-3%. Tech stocks led the gains to jump 5.8%, while financial shares closed 1.5% higher. On the other hand, miners fell 0.8%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/article/federal-reserve-rate-increase.html </td>
   <td style="text-align:left;"> 2022-03-17 04:25:00 </td>
   <td style="text-align:left;"> What a Federal Reserve Rate Increase Means for You - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Rates on credit cards, savings accounts and different kinds of loans move when the Fed changes its benchmark rate. Here’s what you need to know.                                                                                                                                                                                                                                                                                                                                         , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                           , By Tara Siegel Bernard                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Consumers are already feeling squeezed by higher prices on daily necessities, whether it’s at the gas pump or in the supermarket. And now that interest rates are ticking higher, the cost of borrowing — from credit cards and car financing to private student loans — will increase, too.                                                                                                                                                                                             , By increasing its benchmark rate a quarter of a point on Wednesday, the Federal Reserve is trying to rein in inflation, which is at a 40-year high. The mechanics are relatively straightforward: By raising its federal funds rate — the rate banks charge one another for overnight loans — the Fed sets off a domino effect. Whether directly or indirectly, a number of borrowing costs for consumers go up. In theory, this slows demand for goods and taps the brakes on inflation., The rate increase was the first bump in the benchmark rate since the pandemic gripped the world in March 2020 and pushed the rate to near zero. But the global economic situation is only slightly less complicated today than it was when the coronavirus closed down large swaths of the global economy. Supply-chain problems have persisted, and Russia’s war in Ukraine has roiled the markets for oil and natural gas.                                                             , The Fed is anticipating more rate increases as the year goes on. For now, consumers may feel the sting of higher prices more acutely than the pain of a quarter-point bump. But the effects of the Fed’s moves will be more pronounced the further the central bank goes.                                                                                                                                                                                                                , Mortgage rates don’t move in lock step with the federal funds rate, but instead track the yield on 10-year Treasury bonds, which is influenced by a variety of factors — including how investors expect the Fed to react to inflation.                                                                                                                                                                                                                                                   , Mortgage rates have already been ticking higher as a result of inflation, even though they remain historically low: Rates on 30-year fixed-rate mortgages averaged 3.85 percent with 0.8 points as of Thursday, according to Freddie Mac, up from 3.76 a week earlier and 3.05 a year ago. (A point is a one-time fee, equal to 1 percent of the mortgage amount, paid to the lender to buy down the mortgage rate.)                                                                     , “The pain to the consumer from accumulated hikes probably doesn’t start to bite until several rate increases are in place,” said Keith Gumbinger, vice president at HSH.com, which tracks the mortgage market. “But at the same time, rates could rise considerably from present levels and still be considered low by historical standards.”                                                                                                                                            , Mr. Gumbinger said he expected the 30-year fixed rate mortgage to “crest over the 4 percent mark this week,” pressured upward by inflation, which is pushing long-term Treasury rates higher (and pulling mortgage rates along).                                                                                                                                                                                                                                                         , Other home loans are more closely linked to the Fed’s move — including home equity lines of credit and adjustable-rate mortgages — and will generally move higher the next time an individual loan resets its rate.                                                                                                                                                                                                                                                                      , Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Changes in credit card rates will hew closely to the Fed’s moves, so consumers can expect to pay more on any revolving debt. The average interest rate was 16.44 percent for cardholders who did not pay off their balance each month at the end of last year, according to the Federal Reserve.                                                                                                                                                                                         , Higher rates tend to be passed along within one or two statement cycles, said Greg McBride, chief financial analyst at Bankrate.com. For people carrying debt, he suggests considering a zero percent balance transfer, some of which last as long as 21 months.                                                                                                                                                                                                                         , “This will insulate you from the rate hikes we expect over the next 18 months or so,” he said, “but also give you a clear runway to get that debt paid off for good without facing the headwind of interest charges.”                                                                                                                                                                                                                                                                    , Student Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Current federal student loan borrowers aren’t affected because those loans carry a fixed rate set by the government. (Loan payments and interest accruals remain paused until May.) New batches of federal loans are priced each July, based on the 10-year Treasury bond auction in May.                                                                                                                                                                                                , Private student loan borrowers, however, should expect to pay more — both fixed and variable rate loans are linked to benchmarks that track the federal funds rate.                                                                                                                                                                                                                                                                                                                      , Variable loans will generally move higher first. But private lenders will begin to price additional expected increases into their new fixed-rate loans, said Mark Kantrowitz, a student loan expert and author of “How to Appeal for More College Financial Aid.”                                                                                                                                                                                                                        , The Fed is widely expected to raise the funds rate several times over the next couple of years, and private lenders could soon start baking those expectations into their interest rates — meaning borrowers could end up paying anywhere from 1.5 to 1.9 percentage points more, depending on the length of the loan term.                                                                                                                                                              , Car Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Prices for new and used vehicles have skyrocketed so much in the past year that interest rates may seem like an afterthought. But these rates are expected to rise, too.                                                                                                                                                                                                                                                                                                                 , The average interest rate on new car loans was 4.39 percent in February, relatively flat from a year ago, according to Dealertrack, which provides business software to dealerships. The average for used vehicles was 7.83 percent in February, down from 8.25 percent.                                                                                                                                                                                                                 , Car loans tend to track the five-year Treasury, which is influenced by the federal fund rate — but that’s hardly the biggest factor in determining the rate you’ll pay.                                                                                                                                                                                                                                                                                                                  , The rate a borrower qualifies for depends on credit history, the type of vehicle, the loan term, down payment and other factors. Borrowers with poor credit scores may pay 20 percent or more, while those with pristine credit might qualify for rates near zero, said Jonathan Smoke, chief economist at Cox Automotive, an industry consulting firm.                                                                                                                                  , “There is far more variation in auto lending than in, say, the mortgage market because there are more credit types,” he added. “Anyone can get an auto loan.”                                                                                                                                                                                                                                                                                                                            , Though the typical car payment has reached its highest levels since 2012, the latest increase isn’t expected to make a meaningful difference — at least not yet.                                                                                                                                                                                                                                                                                                                         , “Car loan rates will move up as the Fed hikes interest rates, but it will be a nonissue for car buyers because it has such a limited impact on monthly payments,” said Mr. McBride, adding that the difference of a quarter percentage point on a $25,000 loan is $3 a month. “Nobody will need to downsize from the S.U.V. to the compact because of rising rates,” he said.                                                                                                            , Many people stashed extra money in their bank accounts over the past couple of years, but whether rate increases translate into a more attractive yield depends on the type of account you have and the institution you’re doing business with.                                                                                                                                                                                                                                          , An increase in the Fed benchmark often means banks will pay more interest on deposits — but not necessarily right away. Banks tend to raise rates when they want to bring more money in, but the largest banks already have plenty of deposits. That gives them little incentive to pay depositors more.                                                                                                                                                                                 , Smaller banks and online banks tend to pay better rates more quickly than larger institutions, according to Ken Tumin, founder of DepositAccounts.com, part of LendingTree. And some of them, particularly the savings arms of credit-card banks including Capital One and American Express, have already begun increasing their rates a bit, he added.                                                                                                                                  , But overall, rates remain quite low. The average online savings account was paying just 0.49 percent in March, according to DepositAccounts.com; the average was 0.48 a year ago. At brick-and-mortar banks, the average savings account paid 0.12 percent in March, down slightly from 0.15 the year prior.                                                                                                                                                                             , Certificates of deposit, which tend to track similarly dated Treasury securities, have already begun to move a bit higher, particularly among online banks: The average one-year C.D. at online banks is 0.67 percent in March, up from 0.51 percent in January, while the average five-year C.D. is 1.08 percent, up from 0.86 percent in January.                                                                                                                                      , Most money market mutual funds, which tend to hold lower-risk investments like short-term government securities, are also expected to rise, albeit from a rock-bottom rate. Most money market fund yields are below 0.02 percent. “They usually respond fairly quickly to changes in the federal funds rate,” Mr. Tumin said.                                                                                                                                                            , The world remains an uncertain place, and the stock and bond markets will continue to react to all of it — Russia’s war on Ukraine, the ebbs and flows of the pandemic, inflation, energy prices, or what the Fed does next.                                                                                                                                                                                                                                                             , If you’re a long-term investor, you’re reaching for a goal at some date in the future — and your portfolio should include just enough riskier investments (stocks) offset by some more stabilizing ones (bonds) to get there. In other words, it should be built for rocky periods like these — and if that’s the case, it’s better to look away and focus on what you can control.                                                                                                      , The stock market has already priced in expectations for multiple increases this year, so any market reaction on Wednesday is just a short-term blip. But investors will be closely watching for any hints the Fed is going to slow down or speed up the next increase.                                                                                                                                                                                                                   , Bond investors often worry at moments like these because when rates rise, the price of existing bonds fall. That’s because older (lower-yielding) bonds aren’t as attractive as those shiny new bonds offering a higher rate. But people who own bonds in vehicles like mutual funds will eventually benefit as the funds reinvest money in higher-yielding bonds.                                                                                                                       , Given the price declines, that idea is sometimes lost on investors. “Higher yields are a positive thing for long-term investors,” said Andrew Patterson, senior international economist at Vanguard. “You have to absorb those price losses in the near term, but over the long run you could end up with higher returns.”                                                                                                                                                               , Most people with bond investments hold them through some type of mutual fund. To get a sense of how your fund may react to rising rates, take a look at its duration, a number that you can look up on your fund provider’s website. It’s a complex calculation that combines interest payments and the bond’s maturity date to measure the investment’s sensitivity to rate changes. The longer the duration, the more sensitive the bond.                                              , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/wd-40-ceo-garry-ridge-retire/story.aspx?guid={59627964-1EA2-447C-98BC-4E6BEB3B739F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 04:15:55 </td>
   <td style="text-align:left;"> WD-40 CEO Garry Ridge to retire, COO Steve Brass to become CEO - MarketWatch </td>
   <td style="text-align:left;"> WD-40 Co. 
        WDFC,
        +2.55%
       said late Wednesday that Chief Executive Garry Ridge will retire from his post on Aug. 31 as part of a "planned leadership transition." Steve Brass, the company's chief operating officer, has been appointed CEO, effective Sept. 1. Brass will also serve on the company's board of directors, WD-40, the maker of the eponymous spray, said. Shares of WD-40 were flat in the extended session after ending the regular trading day up 2.6%. , A flood of U.S. companies have announced plans to suspend, close or curtail activities in Russia following its invasion of neighboring Ukraine, but one prominent conglomerate seems to be operating on a business-as-usual basis.                                                                                                                                                                                                                                                                 , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/16/berkshire-hathaway-closes-at-a-record-above-500000-a-share-as-buffetts-conglomerate-roars-back.html </td>
   <td style="text-align:left;"> 2022-03-17 04:05:18 </td>
   <td style="text-align:left;"> Berkshire Hathaway closes at a record above $500,000 a share as Buffett's conglomerate roars back </td>
   <td style="text-align:left;"> , Berkshire Hathaway class A shares achieved a key milestone Wednesday, hitting an all-time closing high of half a million dollars as Warren Buffett's multifaceted conglomerate fires on all cylinders during the economic recovery.                                                                                                                            , The class A shares gained 1.3% Wednesday, rising for a fourth straight day to close at $504,400 — its first-ever close above the half-million dollar threshold. Shares of the Omaha-based company have rallied more than 11% this year, significantly outperforming the broader market.                                                                        ,                                                                                                                                                                                                                                                                                                                                                                , "I think a rotation into value names, coupled with Berkshire's exposure to the energy and utility space ... and investors' enthusiasm for Berkshire's aggressive share buybacks drove the shares' performance," said Cathy Seifert, a Berkshire analyst at CFRA Research.                                                                                      , The rally in the stock pushed Berkshire's market cap above $730 billion, surpassing tech pioneer Meta Platforms in market value and becoming only non-tech companies on the list of 10 most valuable U.S. public companies.                                                                                                                                    , Berkshire's Class A shares are the conglomerate's original offering, which rapidly ballooned over time in price to eventually become one of the most expensive single stocks on Wall Street. Buffett has said he will never split the Class A shares because he believes the high share price will keep and attract more long-term, quality-oriented investors., Still, in response to demand for a cheaper option among small investors, Berkshire issued convertible Class B shares in 1996 for one thirtieth of Class A share price initially. The affordable share class allows investors to purchase a piece of the company directly instead of buying a fraction of a share through unit trusts or mutual funds.          , Berkshire's Class B shares closed at $336.11 apiece on Wednesday, rising a similar 12% this year.                                                                                                                                                                                                                                                              , JPMorgan says these are the stocks to buy on the pullback, including some set to gain 50% or more                                                                                                                                                                                                                                                              , Jeffrey Gundlach says he would buy bitcoin over gold in the short term                                                                                                                                                                                                                                                                                         , S&amp;P 500 chart forms the ominous-sounding ‘death cross.’ What it really means for the market                                                                                                                                                                                                                                                                    , The company's operating earnings — which encompass profits made from the myriad of businesses owned by the conglomerate like insurance, railroads and utilities — jumped 45% from a year ago in the fourth quarter as businesses continued to roar back to life from the pandemic economic slowdown.                                                           , A slew of Buffett's stock holdings are also paying off handsomely, from Apple to big banks and Japanese trading houses. The 91-year-old investing legend's massive bet on Apple, which makes up 40% of Berkshire's equity portfolio, has made more than $120 billion on paper.                                                                                 , Meanwhile, Berkshire has further supported the stock by repurchasing a record $27 billion of its own shares in 2021 as the "Oracle of Omaha" found few opportunities externally. The conglomerate hasn't pulled off any big acquisitions in recent years so has consistently bought back its own shares with its massive cash pile.                            , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-ends-more-500-points/story.aspx?guid={28385504-39E7-4F93-9EBC-228C2735A300}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 04:04:40 </td>
   <td style="text-align:left;"> Dow ends more than 500 points higher after Fed delivers rate hike - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended sharply higher Wednesday in a session marked by big swings after the Federal Reserve delivered a widely expected quarter-point rate hike and penciled in a series of increases over the rest of the year. The Dow Jones Industrial Average 
        DJIA,
        +1.55%
       dipped into negative territory after the Fed announcement, but roared back by the closing bell to end the session up around 519 points,  or 1.5%, near 34,063. The S&amp;P 500 
        SPX,
        +2.24%
       jumped 2.2% to close near 4,358, while the Nasdaq Composite 
        COMP,
        +3.77%
       advanced 3.8% to close near 13,437., Investors need to remember where the path of the global economy was before the Russian invasion of Ukraine. They are staying bullish on stocks.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60768818?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-17 03:56:23 </td>
   <td style="text-align:left;"> US central bank raises interest rates for first time since 2018 </td>
   <td style="text-align:left;"> The US Federal Reserve is raising interest rates for the first time since 2018 in an attempt to bring fast-rising prices under control.                                                                                                                                                                                                 , The US central bank said it was lifting its benchmark rate by 0.25 percentage points and signalled plans for further rate rises in the months head.                                                                                                                                                                                     , The moves come as the economy faces new uncertainty caused by the Ukraine war and coronavirus outbreaks in China.                                                                                                                                                                                                                       , They are expected to have widespread global repercussions.                                                                                                                                                                                                                                                                              , By raising rates, the Fed will make it more expensive for households, businesses and governments to borrow.                                                                                                                                                                                                                             , It is hoping that will cool demand for goods and services, helping to ease price inflation in the US, which hit a new 40-year high of 7.9% last month.                                                                                                                                                                                  , "The plan is to restore price stability while also maintaining a strong labour market," Federal Reserve Chairman Jerome Powell said. "That is our intention and we believe we can do that but we have to restore price stability."                                                                                                      , "We're not going to let high inflation become entrenched," he said. "The costs of that would be too high."                                                                                                                                                                                                                              , The bank is trying to pull off a "high-wire act" says Diane Swonk, chief economist at accounting firm Grant Thornton.                                                                                                                                                                                                                   , Move too slowly and inflation could become entrenched, eroding living standards over time. Move too fast and the Fed risks knocking growth in the US and abroad.                                                                                                                                                                        , "They want to dampen down the pressures of inflation without derailing the global economy," she says.                                                                                                                                                                                                                                   , The plans represent a seismic shift in policy from the bank overseeing the world's largest economy. The Fed moved cautiously to raise interest rates after the financial crisis of 2008 and slashed them again when the coronavirus pandemic hit.                                                                                       , The rate increase announced on Wednesday was expected and will push the target range for the bank's key rates to 0.25% to 0.5%.                                                                                                                                                                                                         , Projections released after the Fed's meeting show officials also expect the interest rate to rise to almost 2% by the end of the year - a full percentage point higher than they predicted in December.                                                                                                                                 , In addition to rate rises, the Fed will also be winding down other stimulus, including massive purchases of Treasury securities and other assets that it started to stabilize markets at the beginning of the coronavirus crisis.                                                                                                       , And while the bank has certainly raised rates before, it has not faced this kind of inflation in decades.                                                                                                                                                                                                                               , "It's no longer just raising rates to accommodate stronger growth," Ms Swonk says. "Actually chasing inflation as opposed to pre-empting inflation is a very different concept."                                                                                                                                                        , Fed Chairman Jerome Powell said the US economy was well positioned to handle the increases, dismissing fears that it might tip into recession.                                                                                                                                                                                          , "The probability of a recession in the next year or so is not particularly elevated," he said at a press conference following the Fed meeting. "All signs are that this is a strong economy, one that will be able to flourish, not to say withstand, but certainly flourish as well in the face of less accommodative monetary policy.", Bank officials expect the US economy to grow 2.8% this year, and inflation to subside to around 4.3% by the end of the year.                                                                                                                                                                                                            , That is still well above the bank's 2% target, raising fears the Fed is moving too cautiously.                                                                                                                                                                                                                                          , In the UK - where inflation hit 5.5% in January - the Bank of England has already raised rates twice and is expected to do so again on Thursday.                                                                                                                                                                                        , Officials in many other countries, including South Africa, Brazil and South Korea, have also acted.                                                                                                                                                                                                                                     , By holding off, the Fed created a situation with more uncertainty about how far the it will have to raise rates and how quickly to get inflation under control, says Maurice Obstfeld, professor of economics at the University of California, Berkeley.                                                                                , That's a problem - and not just in the US, he says.                                                                                                                                                                                                                                                                                     , "If you're in the UK or a wealthy continental European country, it's not a terribly big deal," he says.                                                                                                                                                                                                                                 , "But if you're in a small emerging market where there have been inflationary prices - which is sort of everywhere outside of Asia - then I think you do have to worry about the repercussions, because you are entering a situation of greater fragility on international capital markets and you're on the front line of that."        , When the US raises interest rates, investors often redirect money from riskier economies, deflating the value of local currencies.                                                                                                                                                                                                      , That also puts pressure on governments - especially those with large amounts of debt in dollars - at a time when budgets were already under strain from the Covid crisis.                                                                                                                                                               , Russia's invasion of Ukraine - which has disrupted global oil and food markets - has made the situation even more delicate.                                                                                                                                                                                                             , It's not the Fed's job to focus on spill-over effects, says Professor Obstfeld, who is also a fellow at the Peterson Institute for International Economics.                                                                                                                                                                             , "The ultimate factor that is destabilizing or potentially destabilizing for global markets is out-of-control US inflation," he says.                                                                                                                                                                                                    , Companies have attributed the price increases to higher costs from supply shortages, logistics disruptions and wage increases as they compete for workers in a competitive job market.                                                                                                                                                  , Despite the gains, US demand has remained strong, boosted in part by increased government assistance to households during the pandemic.                                                                                                                                                                                                 , But the rising cost of basics like food and petrol has still put pressure on President Joe Biden, as inflation outpaces wage gains.                                                                                                                                                                                                     , Sheilla Thompson, a manager at a social services organisation in Brooklyn, says she has put off going to the doctor, worried about how the extra bill will fit in amid rapidly rising costs of groceries and other essentials.                                                                                                          , "I have to cut back," the 45-year-old says. "All kinds of stuff has gone up."                                                                                                                                                                                                                                                           , "The way all these prices are shooting up, can't the government put a stop to it?" she adds.                                                                                                                                                                                                                                            , The origins of a notorious street gang that arose in Birmingham                                                                                                                                                                                                                                                                         , Stock car racing is raw and unfiltered - who will finish the season on a high?                                                                                                                                                                                                                                                          , 'The Boss' Sasha Banks on her love for wrestling and what it means to her                                                                                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/16/europe/ukraine-mykolaiv-fighting-russian-intl-cmd/index.html </td>
   <td style="text-align:left;"> 2022-03-17 03:49:03 </td>
   <td style="text-align:left;"> Mykolaiv's fate hangs in the balance, as Ukrainian troops dig in to defend the city - CNN </td>
   <td style="text-align:left;"> Mykolaiv, Ukraine (CNN)The road between Kherson and Mykolaiv is sparse and ghostly. Civilians flee at high speed in one direction, as vans of grimacing troops head the other way.                                                                                                                                                                                          , The fate of the key port of Mykolaiv will likely be decided along this stretch of concrete in southern Ukraine. Russian forces are moving from the occupied city of Kherson to pound villages along its once peaceful plains and Ukraine claims a counter-attack is pushing them back.                                                                                      , One minibus fleeing the village of Luch carries five adults, who describe how only 10 of the 18 homes there remained standing. "No electricity, gas, water or heat," one woman says, adding that a school had been demolished. In the rear seat, another Luch resident adds: "The only ones left are those who can't leave."                                                , In the back sits 75-year-old Halyna, who was originally born in Tambov, Russia. She smiles wistfully as she remembers her late Ukrainian husband whom she left Russia to live with. She trembles and weeps onto the seat in front of her. "It was never before like this. It's cold inside me, I'm shaking. So scary."                                                      , Ukrainian troops on the road are edgy, and three young soldiers briefly point their guns at a CNN crew -- despite the journalists wearing "press" on their protective vests -- before they apologize.                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                             , Ukrainian anxiety on the road is likely enhanced by fears of Russian saboteurs, but also a recent warning from the regional governor Vitali Kim that separatist militants from Donbas were attacking locals suspected of having links to the armed forces.                                                                                                                  , Within minutes, troops on the same highway have fortified their positions at a checkpoint with cut-down trees and tires, the fluid environment on the road reflected in their constantly changing presence.                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                             , On Tuesday, the Ukrainian military destroyed a number of Russian military helicopters at the Kherson International Airport, new satellite images from Planet Labs show. A large black plume of smoke is seen rising from the airport in the images, with a number of helicopters on fire.                                                                                   , But Ukrainian positions nearby are crude: trenches dug in the farmland along a highway pock-marked with shell impacts. Some of the soldiers are local -- one pointing to his neighborhood in the city -- and others are from the nearby city of Odesa, which is Russia's eventual target along the Black Sea coast.                                                         , The conditions they endure are startling: this is not a trench network of Javelin missiles or sophisticated NATO arms deliveries. Crude stoves boil water, and trees and soil form the roofs of shelters. Every night the Russian Grad rocket systems target them; the intense bombardment has left at least one of the troops shell-shocked, a soldier said.               , Still, their morale appears higher than that of the Russian troops they captured over a week ago when a Tigr armored vehicle launched a failed assault on a nearby roundabout.                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                             , One Ukrainian soldier said of the captured Russians: "They said they can't understand what's going on. They can't go back, because back there they're being shot for retreating. So they advance or surrender."                                                                                                                                                             , Across the farmland around the highway, rocket tips protrude gruesomely from the arable land -- a hazard for years to come and indication of how random the bombardment can be.                                                                                                                                                                                             , In Mykolaiv, a large line of women and children has formed, as a number of buses snakes around them. A soldier, Oleksandr, waves goodbye to his son through the bus window, before returning to the city's southern defenses.                                                                                                                                               , Another man, a former sailor, helps push his wife and daughter through the crowds onto the transport. "This my wife Zheniya, and daughter Varvara. She go Poland. After come back. I go to the ..." he said, indicating with his head towards the front lines. "What I must do? I go to Poland? No, this is my country, I will stay here."                                  ,                                                                                                                                                                                                                                                                                                                                                                             , Dusk comes with sirens, and the distant rumble of shelling that sometimes hits residential compounds in the city. A curfew has been established for weeks, enforced by police who patrol the eerily empty streets. Their blue lights often flag down stray, drunk locals. It is slow work. Every phone must be checked for suspicious photographs of military installations., Suddenly, a call comes in for help with an urgent blood delivery, from surgeons at a key hospital. The police blue lights starkly illuminate the four-story building -- in the blackout the hospital appears almost invisible in the gloom to protect it from Russian airstrikes.                                                                                           , The bombing of Mykolaiv has grown in ferocity and its indiscriminate nature. Sunday saw the worst example yet when a rocket hit outside a store, killing nine people outright. One was Svetlana's husband. She sits alone in a room in hospital, her arm bandaged, her fragile form shaking. "Such grief," she weeps. "In a moment, everyone gone."                         , Svetlana's loss is compounded by the death of her daughter, in the Czech Republic, away from the war, earlier in the week. She and her husband were buying candies for the funeral wake when the bomb hit, robbing her of the only person she had left.                                                                                                                     , "We went to buy sweets to remember her," she said. "Then the rockets landed and my husband just exploded and the blood came from his head. And he is still lying there in the blood and they took me here. And I am here and he is there. In pieces."                                                                                                                       , The hospital staff have done what they can to patch up her wounded arm, but they are too overloaded to care for her well-being in the months ahead. Blood still on her coat, she totters slowly out of the hospital doors, and across its cold, barren courtyard, back into the city.                                                                                       , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/white-house-calls-gasoline-stations/story.aspx?guid={62D47550-2495-426C-98B0-2F905D5A915F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 03:48:37 </td>
   <td style="text-align:left;"> White House calls for gasoline stations to lower prices after oil's drop - MarketWatch </td>
   <td style="text-align:left;"> White House press secretary Jen Psaki on Wednesday urged operators of gasoline 
        RB00,
        -0.09%
       stations to pass on the recent retreat in oil prices 
        CL00,
        +0.43%
       to Americans. "Retail gasoline prices are updated at least daily, and if gas retailers' costs are going down, they need to immediately pass those savings on to consumers," she told reporters during a briefing. President Joe Biden made the same point on gasoline earlier Wednesday, tweeting that oil prices are decreasing, so "gas prices should too.", What to expect when you're expecting a hit to housing, stocks and other 'sure' things.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/16/business/media/justin-smith-ben-smith-media.html </td>
   <td style="text-align:left;"> 2022-03-17 03:48:28 </td>
   <td style="text-align:left;"> Justin Smith, Former Bloomberg C.E.O., Offers New Details on Media Start-up - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The former Bloomberg Media C.E.O. offered new details on the venture he is starting with the journalist Ben Smith.                                                                                                                                                                                                                                                                                                                                                          , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                     , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                              , By Michael M. Grynbaum                                                                                                                                                                                                                                                                                                                                                                                                                                                      , It will be named for a word that is the same in dozens of languages. It will recruit English-speaking journalists from countries like India and Singapore to cover the news. And according to its co-founder, “The era of the foreign correspondent is over.”                                                                                                                                                                                                               , These are among the ideas in store for the new media venture led by Justin Smith, the former chief executive of Bloomberg Media, and Ben Smith, the former editor of BuzzFeed and media columnist for The New York Times, according to remarks by Justin Smith during an online seminar on Tuesday.                                                                                                                                                                         , The Smiths, who are not related, have been tight-lipped about plans for their new company, which has captured the fascination of the media industry because of its high-profile founders and their ambitious pledge to compete with international outlets like Reuters, The Associated Press and The Times.                                                                                                                                                                 , The Smiths are seeking tens of millions of dollars in funding from prominent investors. This week, they announced the hiring of Gina Chua, a top editor at Reuters who will serve as executive editor.                                                                                                                                                                                                                                                                      , On Tuesday, Justin Smith offered some new details during an hourlong Zoom interview sponsored by the Harvard Business School Club of New York.                                                                                                                                                                                                                                                                                                                              , “We’ve chosen a brand that we’re going to be unveiling in a couple of months that is the same word in 25 or 35 different languages,” Mr. Smith told the moderator. “It is very intentionally going to be able to live in Asia or Europe or the Middle East or America.”                                                                                                                                                                                                     , Mr. Smith did not reveal the name that he had selected. English words that are the same or similar in many other languages include taxi, tea, coffee, chai, sugar, pajama, radio and soup.                                                                                                                                                                                                                                                                                  , Mr. Smith also shared his thoughts about what he called the end of an era when news outlets based in London, New York or Washington dispatched journalists to foreign countries to report on the goings-on there. He asked why foreign readers would not prefer a homegrown English-speaking native to report the news in their region.                                                                                                                                     , “The idea that you send some well-educated young graduate from the Ivy League to Mumbai to tell us about what’s going on in Mumbai in 2022 is sort of insane,” Mr. Smith said.                                                                                                                                                                                                                                                                                              , Instead, he said, he will pursue “very educated, English-language-educated journalists all around the world,” describing an opportunity “for scaling local and regional newsrooms at a lower cost.”                                                                                                                                                                                                                                                                         , He also argued that many foreign news readers were ill served.                                                                                                                                                                                                                                                                                                                                                                                                              , “You maybe went to school in the U.S., you’re pretty well educated, you’re connected to your network and your family all around the world — and the quality of your local media is not amazing,” Mr. Smith said. “It’s either state-censored or, it’s just, the journalism’s not great.”                                                                                                                                                                                    , “So what do you do?” he continued. “You say, OK, well, let me let me pick up The New York Times, or let me pick up The Wall Street Journal, or let me pick up The Washington Post. And what do you get? You get exactly what you’d expect if you read something that had the word New York in it, or something that has the word Washington in it. Or you go to CNN and you get a feed from Atlanta, some regional story from the Midwest, and you’re sitting in Singapore.”, (The Post and The Times, among other American outlets, have expanded their reporting presence in Europe in recent years. CNN broadcasts an international feed outside the United States.)                                                                                                                                                                                                                                                                                   , Mr. Smith told his audience that he was reluctant to share too many plans. (“There’s not a huge advantage when you’re starting a new company to be giving away all the specifics.”) But he allowed that he hoped to launch in the United States and “at least one other major international market,” and that a live events business would be integrated. The co-founders are aiming to launch in the second half of this year.                                             , Mr. Smith also said he was intrigued by automated translation of non-English-language news articles. “The quality of translation software for journalism is really quite amazing; it captures subtlety and nuance in a way it did not in previous years,” he said.                                                                                                                                                                                                          , At one point, the moderator cited a quote from Ben Smith that the company’s potential market included 200 million educated English speakers “who no one is really treating like an audience.”                                                                                                                                                                                                                                                                               , “That vague platitude,” Justin Smith joked. He added, “The end-stage vision is that we will serve many, many portions of this audience all across the world.”                                                                                                                                                                                                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-17 03:28:00 </td>
   <td style="text-align:left;"> US 10-Year Treasury Yield Falls Below 2019-Highs </td>
   <td style="text-align:left;"> The yield on the benchmark US 10-year Treasury note fell back to 2.19% on Wednesday after briefly rising to near 2-year highs of 2.24%, as investors digest the latest FOMC statement. The Fed hiked the federal funds rate by 25bps as expected but signaled six more rate hikes this year and projected slower growth and higher inflation. But during the press conference following the decision, Fed Chair Powell said the American economy is very strong and well positioned to handle tighter monetary policy while the probability of a recession is “not particularly elevated.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 03:27:00 </td>
   <td style="text-align:left;"> US Stocks Close Higher on Fed Decision Day </td>
   <td style="text-align:left;"> US stocks closed higher on Wednesday, rebounding from muted levels after Fed Chair Jerome Powell assured investors the Fed hikes won't derail the economic recovery. During the press conference, the Chair emphasized that the US economy can withstand tighter monetary conditions and that the likelihood of a recession is “not particularly elevated”. The Dow Jones closed over 500 points higher at 34,064, while the S&amp;P 500 gained 2.2% and the Nasdaq jumped 3.8%. Earlier, the Dow fully erased a 500 point gain after the Fed hiked the federal funds rate by 25bps as expected but signaled six additional rate hikes this year and projected slower growth and higher inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/16/politics/biden-calls-putin-a-war-criminal/index.html </td>
   <td style="text-align:left;"> 2022-03-17 03:22:37 </td>
   <td style="text-align:left;"> Biden on Putin: 'I think he is a war criminal' - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)President Joe Biden called Russian President Vladimir Putin a "war criminal" Wednesday, a rhetorical leap that came as civilian deaths mount in Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , It was the harshest condemnation of Putin's actions from any US official since the war in Ukraine began three weeks ago. Previously, Biden had stopped short of labeling atrocities being documented on the ground in Ukraine as "war crimes," citing ongoing international and US investigations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , But on Wednesday, speaking with reporters at an unrelated event, Biden affixed the designation on the Russian leader.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , "I think he is a war criminal," the President said after remarks at the White House.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The shift from the administration's previous stance came after an emotional address to Congress from Ukrainian President Volodymyr Zelensky, who aired a video showing Ukrainians suffering amid Russia's onslaught. Zelensky asked American lawmakers and Biden for more help defending itself, including a no-fly zone and fighter jets.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Biden responded in his own address a few hours later, laying out new American military assistance to Ukraine -- including anti-aircraft and anti-armor systems, weapons and drones -- but stopping short of acceding to Zelensky's requests.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Still, Biden acknowledged the horrors transpiring on the ground.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , "We saw reports that Russian forces were holding hundreds of doctors and patients hostage in the largest hospital in Mariupol," Biden said. "These are atrocities. They're an outrage to the world. And the world is united in our support for Ukraine and our determination to make Putin pay a very heavy price."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , It wasn't until a few hours after that that Biden responded to a question about Putin being a war criminal. Biden initially said "no," but immediately returned to a group of reporters to clarify what had been asked. When asked again whether Putin was a war criminal, he answered in the affirmative.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Officials, including Biden, had previously avoided saying war crimes were being committed in Ukraine, citing ongoing investigations into whether that term could be used. Other world leaders have not been as circumspect, including British Prime Minister Boris Johnson, who said last week war crimes were being committed. The International Criminal Court at the Hague has also opened an investigation into war crimes. And the US Senate unanimously asked for an international investigation into war crimes on Tuesday. US Ambassador to the United Nations Linda Thomas-Greenfield said last week that actions committed by Russia against the Ukrainian people "constitute war crimes," marking the first time a senior US official directly accused Moscow of war crimes since last month's attack on Ukraine began., In Poland last week, Vice President Kamala Harris called for international investigations into war crimes, and made clear she believed atrocities were underway. She said the intentional targeting of civilians would constitute war crimes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , After Biden delivered his assessment, the White House said the administration's investigation into war crimes would continue.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , "The President's remarks speak for themselves," press secretary Jen Psaki said. She said Biden was "speaking from the heart."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , State Department spokesman Ned Price echoed Psaki later Wednesday, telling CNN's Erin Burnett on "OutFront" that "when you are speaking from the heart, speaking as a human and you're seeing what we've all seen, these searing images on TV, a Russian strike on a maternity hospital in Mariupol, strikes against residential buildings, against schools, against civilian neighborhoods, it's hard not to walk away with that conclusion."                                                                                                                                                                                                                                                                                                                                                                                    , "What we are doing here at the State Department, we are collecting every single piece of information, we're evaluating it, we're documenting it and sharing it with our partners. There is a process that is involved in this and there are people working almost around the clock to document, evaluate, share as we all watch what is happening with some horror."                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Pressed as to how Putin's actions don't currently amount to war crimes, Price reiterated that "there is a formal process here at the department under international humanitarian law to document war crimes. We're involved in that."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , While the term "war crimes" is often used colloquially -- as Biden appeared to be doing Wednesday -- they do have a legal definition that could be used in potential prosecution. That includes in the Geneva Convention, which specifies intentional targeting of civilians as a war crime.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Yet in order to prosecute a war crime, solid evidence is required. And for Russian officials to be held accountable, they would need to travel outside of the country.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Still, an official designation of war crimes -- backed up with evidence -- would still present the West with a symbolic tool in framing Putin's actions in Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Biden has come under increasing pressure to do more to help besieged Ukrainians as Russia's campaign intensifies. On Wednesday, a theater in Mariupol where civilians were sheltering was bombed, the latest example of Russia's indiscriminate shelling.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The pressure was only likely to increase after Zelensky's dramatic appeal to lawmakers for more help. He compared what is happening in Ukraine to Pearl Harbor and September 11, and said "we need you right now" to offer more support.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Biden watched the address from the library of his private residence, and later called it a "convincing" and "significant" speech.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , "Putin is inflicting appalling, appalling devastation and horror on Ukraine, bombing apartment buildings, maternity wards, hospitals," he said afterward. "I mean, it's godawful."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Next week, Biden plans to travel to Brussels for an extraordinary session of NATO leaders, where he hopes to demonstrate western unity amid Russia's aggression.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , This story has been updated with additional reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bahrain/interest-rate </td>
   <td style="text-align:left;"> 2022-03-17 03:16:03 </td>
   <td style="text-align:left;"> Bahrain Lifts Borrowing Costs in Line with Fed </td>
   <td style="text-align:left;"> The central bank of Bahrain increased its key one-week deposit facility to 1.25% from 1% on March 16th 2022, tracking a hike in the fed funds rate. The central bank also increased the overnight deposit, four-week deposit and lending rates by 25 bps each to 1%, 1.75% and 2.5%, respectively. Bahrain usually follow the Fed's lead on interest rates as it maintains an exchange rate peg at 0.376 Bahraini dinars to the US dollar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/personal-finance/federal-reserve-raises-interest-rates </td>
   <td style="text-align:left;"> 2022-03-17 03:07:28 </td>
   <td style="text-align:left;"> Federal Reserve raises interest rates: What to do now </td>
   <td style="text-align:left;"> The Federal Reserve on Wednesday announced its first interest rate hike since 2018 in order to combat inflation.  (iStock)                                                                                                                                                                                                                                                      , The Federal Reserve ended its Federal Open Market Committee (FOMC) meeting Wednesday with the announcement that it is raising rates for the first time since 2018.                                                                                                                                                                                                              , The Fed raised the federal funds rate by 25 basis points moving it from 0% to a targeted range of 0.25% to 0.5%. This decision came as no surprise after Fed Chair Jerome Powell said he backed the move earlier this month. The Fed also indicated that it anticipates more rate hikes will soon come.                                                                         , Federal Reserve bank member James Bullard was the only member to vote against the action, instead voting for a more drastic measure of a 50 basis point rate hike.                                                                                                                                                                                                              , The federal funds rate helps determine the direction of other interest rates including those on mortgages, credit cards, personal loans, student loans, car loans and more.                                                                                                                                                                                                     , "Indicators of economic activity and employment have continued to strengthen," the FOMC said in its post-meeting statement. "Job gains have been strong in recent months, and the unemployment rate has declined substantially. Inflation remains elevated, reflecting supply and demand imbalances related to the pandemic, higher energy prices, and broader price pressures.", One way that borrowers can take advantage of interest rates now before they increase further is by taking out a personal loan to pay off high-interest debt. You can visit Credible to find your personalized interest rate without affecting your credit score.                                                                                                                , INFLATION RISES TO YET ANOTHER NEW 40-YEAR HIGH IN FEBRUARY                                                                                                                                                                                                                                                                                                                     , When announcing its decision to raise rates, the Federal Reserve also reiterated its goal to achieve a long-term inflation average of 2%, which is significantly lower than the 7.9% annual inflation rate reported in February. The central bank also said that it "anticipates that ongoing increases in the target range will be appropriate."                               , "The Federal Reserve raised its short-term rate target for the first time since 2018 at its March meeting," Mike Fratantoni, Mortgage Bankers Association (MBA) chief economist, said. "More importantly, it clearly signaled that additional hikes are coming, with the median FOMC member expecting to raise rates at each of the remaining six meetings in 2022.             , "With the unemployment rate below 4%, inflation nearing 8%, and the war in Ukraine likely to put even more upward pressure on prices, this is what the Fed needs to do to bring inflation under control," Fratantoni continued. "The FOMC economic projections indicate slower growth and higher inflation than had been the expectation at their December meeting."            , If you want to take advantage of interest rates now before the Fed’s next rate hike, you could consider refinancing your private student loan to save money on your monthly payment. Visit Credible to compare multiple lenders at once and choose the one with the best interest rate for you.                                                                                 , YELLEN SAYS INFLATION IS ‘LIKELY’ TO BE 'VERY UNCOMFORTABLY HIGH' FOR ANOTHER YEAR                                                                                                                                                                                                                                                                                              , While the Federal Reserve is now adjusting its monetary policy to fight inflation, it predicts that a 2% inflation rate will not be achieved until after 2024. The FOMC attributed this, in part, to the escalating Russia-Ukraine conflict.                                                                                                                                    , "The invasion of Ukraine by Russia is causing tremendous human and economic hardship," the FOMC said in its statement. "The implications for the U.S. economy are highly uncertain, but in the near term the invasion and related events are likely to create additional upward pressure on inflation and weigh on economic activity."                                          , In a recent interview, current Treasury Secretary and former Fed Chair Janet Yellen said the U.S. was "likely to see another year" of "uncomfortably high" inflation numbers. This is due to "a lot of uncertainty" caused by Russia’s invasion of Ukraine, she said.                                                                                                           , "We have seen a very meaningful increase in gas prices, and my guess is that next month we’ll see further evidence of an impact on U.S. inflation of Putin’s war on Ukraine," Yellen said.                                                                                                                                                                                      , If you need to lower your monthly expenses amid rising inflation and interest rates, you could consider refinancing your mortgage to lower your monthly payments. Contact Credible to speak to a home loan expert and see if this is the right option for you.                                                                                                                  , Have a finance-related question, but don't know who to ask? Email The Credible Money Expert at moneyexpert@credible.com and your question might be answered by Credible in our Money Expert column. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2022-03-17 03:05:00 </td>
   <td style="text-align:left;"> Russian Ruble Regains Ground </td>
   <td style="text-align:left;"> The Russian ruble appreciated to below 100 per dollar on Wednesday, moving further away from a record low of 150 hit last week as diplomatic efforts between Russia and Ukraine showed every intention of continuing, while Moscow was due to make interest payments to investors holding two bonds denominated in USD. Ukrainian President Volodymyr Zelensky said in a video address early on Wednesday that the positions of both sides at the peace talks were sounding more realistic but more time was needed. Meanwhile, Russia finance minister, Anton Siluanov, said Russia had sent an order on Monday to a correspondent bank for the payment of $117m in coupons, and that authorities in the US should clarify whether it could be processed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/silver </td>
   <td style="text-align:left;"> 2022-03-17 03:00:00 </td>
   <td style="text-align:left;"> Spot Silver Extends Decline </td>
   <td style="text-align:left;"> Spot silver remained below $25 an ounce, the lowest in two two-week low, as the tighter monetary guidance by the Federal Reserve eased demand for precious metals. The Fed raised its benchmark rate by 25bps as expected on its March meeting but signaled six more hikes this year, more aggressive than previously expected. Still, Chair Powell said that the US economy can withstand tighter monetary conditions and it is unlikely to fall to a recession. Further, the Bank of England is also expected to increase borrowing costs, while investors continue to monitor the developments of ceasefire talks between Moscow and Kyiv. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kuwait/interest-rate </td>
   <td style="text-align:left;"> 2022-03-17 03:00:00 </td>
   <td style="text-align:left;"> Kuwait Hikes Rates after Fed </td>
   <td style="text-align:left;"> The central bank of Kuwait raised its key discount rate by 25bps to 1.75% on March 16th 2022, tracking a rise in the Federal Reserve funds rate. The bank also decided to change the rates of monetary policy instruments by varying percentages, including repurchases (Repo), CBK bonds and tawarruq, term deposits, direct intervention instruments, as well as public debt instruments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-futures-settle-lower-third/story.aspx?guid={507953AE-75EF-468B-B43E-75D841A60C7D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 02:46:17 </td>
   <td style="text-align:left;"> Oil futures settle lower for a third straight session - MarketWatch </td>
   <td style="text-align:left;"> Oil futures finished Wednesday with a loss for a third consecutive session, with the U.S. oil benchmark at its lowest settlement since Feb. 25. Data from the Energy Information Administration released Wednesday revealed the first rise in U.S. crude supplies in three weeks, and traders showed concern that high fuel prices may lead to less demand. In a monthly report, however, the International Energy Agency warned that Russia's invasion of Ukraine and resulting sanctions threaten a supply shock that may push the oil market into a deficit unless major producers increase output. West Texas Intermediate crude for April delivery 
        CLJ22,
        +0.42%
       fell $1.40, or nearly 1.5%, to settle at $95.04 a barrel on the New York Mercantile Exchange after losing 6.4% on Tuesday. , A flood of U.S. companies have announced plans to suspend, close or curtail activities in Russia following its invasion of neighboring Ukraine, but one prominent conglomerate seems to be operating on a business-as-usual basis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-03-17 02:45:00 </td>
   <td style="text-align:left;"> Euro Little Changed after Fed </td>
   <td style="text-align:left;"> The euro changed hands at $1.10, above a 2-year low of $1.08 as diplomatic efforts to end the war in Ukraine continued and traders digested the recent Fed move. The US central bank started its rate hiking cycle in March with a 0.25 bps hike and is set to increase borrowing costs six more times this year. Last week, the ECB said it may end asset purchases in Q3 as surging inflation more than offset concerns about Russia's shock invasion of Ukraine. The bloc’s inflation is already running at record highs and is now likely to be more persistent on the back of higher commodity prices and a tight labor market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-17 02:39:00 </td>
   <td style="text-align:left;"> 10-Year Treasury Yield Hits Highest Since May 2019 </td>
   <td style="text-align:left;"> The benchmark 10-year Treasury yield rose above 2.2%, the highest since May of 2019 after the Fed hiked the federal funds rate by 25bps as expected but signaled six more rate hikes this year, more than initially expected. It was the first increase in the interest rate since 2018, after the latest CPI data showed that the annual inflation rate accelerated to 7.9% in February. Price data is yet to account for the recent surge in commodity prices due to the Russian invasion in Ukraine, while the central bank said the economy faces strong uncertainty amid consequences of the war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-17 02:33:26 </td>
   <td style="text-align:left;"> Crude Oil is down by 2.04% </td>
   <td style="text-align:left;"> Crude Oil WTI decreased 2.04% to 94.46 USD/Bbl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/powell-three-more-biden-fed/story.aspx?guid={83925B52-3CAA-4071-BD6B-DB07466E11BB}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 02:28:59 </td>
   <td style="text-align:left;"> Powell and three more Biden Fed nominees to get Senate committee vote Wednesday - MarketWatch </td>
   <td style="text-align:left;"> The Senate Banking Committee on Wednesday will vote to advance the re-nomination of Federal Reserve Chairman Jerome Powell, as well as three other individuals nominated by President Joe Biden to serve in top roles at the central bank. The vote will come a day after Sarah Bloom Raskin, Biden's nominee as vice chair for supervision, withdrew her name from consideration. In addition to Powell, committee members will vote on the nominations of Lael Brainard for Fed vice chair, and Lisa Cook and Philip Jefferson for governors of the Fed. The Fed said Wednesday it would raise its benchmark interest rate by a a quarter percentage point and laid out plans for "ongoing increases in its policy rate."  

, The bipartisan bill, named the Sunshine Protection Act, would ensure Americans would no longer have to change their clocks twice a year. But the bill still needs approval from the House, and the signature of President Joe Biden, to become law.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-03-17 02:21:00 </td>
   <td style="text-align:left;"> Gold Pares Losses </td>
   <td style="text-align:left;"> Gold prices pared some losses to around $1910 an ounce on Wednesday, as investors digest the recent FOMC statement. The Fed raised the fed funds rate for the first time since 2018 as expected but pointed to a gloomier outlook with slower growth, higher inflation, and interest rates. Still, Fed Chair Powell said the US economy can handle Fed tightening and the probability of a recession is “not particularly elevated.” The Bank of England is also expected to hike borrowing costs on Thursday. Meanwhile, an apparent progress in ceasefire talks between Russia and Ukraine also weighed on haven demand for gold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-03-17 02:18:00 </td>
   <td style="text-align:left;"> DXY Remains Near 21-Month High </td>
   <td style="text-align:left;"> The dollar index touched briefly the 99 levels after the Federal Reserve hiked the fund's rate by 25bps as expected and pointed to six more hikes this year to tame surging inflation but retreated again as Fed Chair Powell was giving a press conference. “The American economy is very strong and well positioned to handle tighter monetary policy,” and the probability of a recession is “not particularly elevated.” Powell said. The latest data showed the US annual inflation rate accelerated to 7.9% in February, matching expectations but rising to a fresh 40-year high. The data came amid growing concerns over a commodity-driven rise in inflation spurred by the Russia-Ukraine war, leaving central banks with a balancing act between curbing inflation and supporting growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 02:15:00 </td>
   <td style="text-align:left;"> US Stocks Pare Gains </td>
   <td style="text-align:left;"> US stocks pared early gains on Wednesday, after the Federal Reserve hiked the federal funds rate by 25bps to 0.5%, as widely expected while pointing to six additional rate hikes this year, more than investors were expecting. The Dow Jones erased its 500 point gain to trade at the flatline, while the S&amp;P 500 added roughly 0.2%, and the tech-heavy Nasdaq was up 0.9%. The equities rallied earlier in the session after FT reported that Ukraine and Russia have made “significant progress” on a peace plan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-turns-negative-treasury-yield/story.aspx?guid={3F3D47B4-1177-472E-9C63-C4FAAC52E51C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 02:14:09 </td>
   <td style="text-align:left;"> Dow turns negative, Treasury yield curve flattens after Fed delivers quarter-point rate hike - MarketWatch </td>
   <td style="text-align:left;"> Stocks erased or trimmed gains in afternoon trade Wednesday after the Federal Reserve, as expected, delivered a quarter-point rate increase. The Dow Jones Industrial Average 
        DJIA,
        +1.55%
       was down 27 points, or 0.1%, near 33,519. The blue-chip gauge was up around 200 points just ahead of the announcement. The S&amp;P 500 
        SPX,
        +2.24%
       was up 0.2% at 4,272, while the Nasdaq Composite 
        COMP,
        +3.77%
       remained higher by 0.9%. The yield curve flattened significantly, with the 2-year Treasury yield jumping around 13 basis points on the day to 1.983%, while the 10-year yield rose more than 5 basis points to top 2.21%. Yields were already trading at their highest since 2019., U.S. and global benchmark crude oil entered a bear market on Tuesday, just five trading days after they settled at their highest prices since 2008.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-settles-lower-then-moves/story.aspx?guid={BBC3F34B-DD85-4F81-A9CC-F6553C182DA6}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-17 02:12:30 </td>
   <td style="text-align:left;"> Gold settles lower, then moves up after Fed announces first interest-rate hike since 2018 - MarketWatch </td>
   <td style="text-align:left;"> Gold futures settled lower on Wednesday, then headed higher in electronic trading after the Federal Reserve announced the first interest-rate increase since 2018. Fed officials lifted the fed funds rate by one-quarter point to the 0.25% to 0.5% range and noted that the Russia-Ukraine war put upward pressure on inflation. April gold 
        GCJ22,
        +0.95%
       was at $1,913.30 an ounce in electronic trading shortly after the announcement. That follows a settlement of $1,909.20, down $20.50, or 1.1%, for Wednesday's session, the lowest finish for a most-active contract since Feb. 28, FactSet data show. , The central bank made its long-awaited move on Wednesday. The quarter-point increase was the first since 2018.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/16/heres-what-changed-in-the-new-fed-statement.html </td>
   <td style="text-align:left;"> 2022-03-17 02:04:02 </td>
   <td style="text-align:left;"> Here's what changed in the new Fed statement </td>
   <td style="text-align:left;"> , This is a comparison of Wednesday's Federal Open Market Committee statement with the one issued after the Fed's previous policymaking meeting on Jan. 26., Text removed from the January statement is in red with a horizontal line through the middle.                                                             , Text appearing for the first time in the new statement is in red and underlined.                                                                         , Black text appears in both statements.                                                                                                                   , Watch Fed Chair Jerome Powell's press conference here.                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/interest-rate </td>
   <td style="text-align:left;"> 2022-03-17 02:03:00 </td>
   <td style="text-align:left;"> Fed Delivers First Rate Hike since 2018 </td>
   <td style="text-align:left;"> The Fed raised the target for the fed funds rate by a quarter-point to 0.25%-0.5% during its March 2022 meeting, in line with market expectations. It is the first increase in borrowing costs since 2018. In addition, policymakers expect to begin reducing its holdings of Treasury securities and agency debt and agency mortgage-backed securities at a coming meeting. The Fed now sees rate hikes at each of the six remaining meetings this year, with the fed funds rate reaching 1.9% by year’s end. PCE inflation is seen sharply higher at 4.3% in 2022 (2.6% in the December projection) and the economy is seen growing 2.8% this year, well below 4% seen in December. Regarding the war in Ukraine, the central bank noted the implications for the US economy are highly uncertain, but it is likely to create additional upward pressure on inflation and weigh on economic activity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/16/federal-reserve-meeting.html </td>
   <td style="text-align:left;"> 2022-03-17 02:00:15 </td>
   <td style="text-align:left;"> Federal Reserve approves first interest rate hike in more than three years, sees six more ahead </td>
   <td style="text-align:left;"> , The Federal Reserve on Wednesday approved its first interest rate increase in more than three years, an incremental salvo to address spiraling inflation without torpedoing economic growth.                                                                                                                                                                                                                                                                                   , After keeping its benchmark interest rate anchored near zero since the beginning of the Covid pandemic, the policymaking Federal Open Market Committee said it will raise rates by a quarter percentage point, or 25 basis points.                                                                                                                                                                                                                                             , That will bring the rate now into a range of 0.25%-0.5%. The move will correspond with a hike in the prime rate and immediately send financing costs higher for many forms of consumer borrowing and credit. Fed officials indicated the rate increases will come with slower economic growth this year.                                                                                                                                                                       , Along with the rate hikes, the committee also penciled in increases at each of the six remaining meetings this year, pointing to a consensus funds rate of 1.9% by year's end. That is a full percentage point higher than indicated in December. The committee sees three more hikes in 2023 then none the following year.                                                                                                                                                    , The rate rise was approved with only one dissent. St. Louis Fed President James Bullard wanted a 50 basis point increase.                                                                                                                                                                                                                                                                                                                                                      , The committee last raised rates in December 2018, then had to backtrack the following July and begin cutting.                                                                                                                                                                                                                                                                                                                                                                  , In its post-meeting statement, the FOMC said it also "anticipates that ongoing increases in the target range will be appropriate." Addressing the Fed's nearly $9 trillion balance sheet, made up mainly of Treasurys and mortgage-backed securities it has purchased over the years, the statement said, "In addition, the Committee expects to begin reducing its holdings of Treasury securities and agency debt and agency mortgage-backed securities at a coming meeting.", Fed Chairman Jerome Powell at his post-meeting news conference hinted that the balance sheet reduction could start in May, and said the process could be the equivalent of another rate hike this year.                                                                                                                                                                                                                                                                        , The indication of about 175 basis points in rate increases this year was a close call: The "dot plot" of individual members' projections showed eight members expecting more than the seven hikes, while 10 thought that seven total in 2022 would be sufficient.                                                                                                                                                                                                              , "We are attentive to the risks of further upward pressure on inflation and inflation expectations," Powell said at the news conference. "The committee is determined to take the measures necessary to restore price stability. The U.S. economy is very strong and well-positioned to handle tighter monetary policy."                                                                                                                                                        , Officials also adjusted their economic outlook on multiple fronts, seeing much higher inflation than they expected in December and considerably slower GDP growth.                                                                                                                                                                                                                                                                                                             , JPMorgan says these are the stocks to buy on the pullback, including some set to gain 50% or more                                                                                                                                                                                                                                                                                                                                                                              , Jeffrey Gundlach says he would buy bitcoin over gold in the short term                                                                                                                                                                                                                                                                                                                                                                                                         , S&amp;P 500 chart forms the ominous-sounding ‘death cross.’ What it really means for the market                                                                                                                                                                                                                                                                                                                                                                                    , Committee members bumped up their inflation estimates, expecting the personal consumption expenditures price index excluding food and energy to reflect 4.1% growth this year, compared with the 2.7% projection in December 2021. Core PCE is expected to be 2.7% and 2.3%, respectively, in the next two years before settling to 2% over the longer term.                                                                                                                   , "Inflation remains elevated, reflecting supply and demand imbalances related to the pandemic, higher energy prices, and broader price pressures," the statement said.                                                                                                                                                                                                                                                                                                          , On GDP, December's 4% was sliced to 2.8%, as the committee particularly noted the potential implications of the Ukraine war. Subsequent years were unchanged. The committee still expects the unemployment rate to end this year at 3.5%.                                                                                                                                                                                                                                      , "The invasion of Ukraine by Russia is causing tremendous human and economic hardship," the statement said. "The implications for the U.S. economy are highly uncertain, but in the near term the invasion and related events are likely to create additional upward pressure on inflation and weigh on economic activity."                                                                                                                                                     , Stocks initially reacted negative to the announcement but then bounced back. Bond yields momentarily moved higher, with the benchmark 10-year Treasury note rising to 2.22% before receding.                                                                                                                                                                                                                                                                                   , "Ultimately, they've come through with a clear message, that the Fed has a path forward to continue to tighten in response to this overwhelming concern around inflation," said Jim Baird, chief investment officer at Plante Moran Financial Advisors. "The question is, will it be enough and are they even recognizing that they've ... perhaps fallen behind the curve?"                                                                                                   , The central bank had slashed its federal funds rate in the early days of the pandemic to combat a shutdown that crippled the U.S. economy and financial markets while sending 22 million Americans to the unemployment line.                                                                                                                                                                                                                                                   , But myriad factors have combined to force the Fed's hand on inflation, a condition that policymakers last year dismissed as "transitory" before capitulating. Officials over the past two months have strongly indicated that interest rate hikes are coming, with the main question left for investors being how many increases and how quickly they would come.                                                                                                              , The current trend of price increases, at their fastest 12-month pace in 40 years, has been fed by demand that has far outstripped supply chains that remain clogged if less so than their pandemic-era peaks. Unprecedented levels of fiscal and monetary stimulus — more than $10 trillion worth – have coincided with the inflation surge. And the Ukraine war has coincided with a major spike in oil prices, though that has abated in recent days.                        , Heading into this week's FOMC meeting, markets had been pricing in the equivalent of about seven 0.25% hikes this year, according to CME Group data. However, traders were split about 50-50 over whether the Fed might hike 50 basis points in May, as some officials have indicated could happen if inflation pressures persist.                                                                                                                                             , Prices are up 7.9% year over year, according to the consumer price index, which measures a wide-ranging basket of goods and services. Energy has been the biggest burden, as gasoline prices have risen 38% in the 12-month period.                                                                                                                                                                                                                                            , However, price pressures have broadened out from simply gas and groceries.                                                                                                                                                                                                                                                                                                                                                                                                     , For instance, clothing prices, after plummeting in the early days of the pandemic, have risen 6.6% over the past year. Motor vehicle repair costs are up 6.3% and airline fares have jumped 12.7%. Rent of shelter costs, which make up nearly one-third of the CPI, have been moving up sharply in recent months and are up 4.8% year over year.                                                                                                                              , All of those cost increases have left the Fed's 2% inflation target in the dust.                                                                                                                                                                                                                                                                                                                                                                                               , The Fed in September 2020 approved a new approach to inflation, in which it would let it run hotter in the interest of a full and, most notably, inclusive employment goal that spans across race, gender and wealth. However, the change in approach was followed almost immediately by more pernicious inflation than the U.S. economy had seen since the days of the Arab oil embargo and inflation that peaked in the early 1980s at nearly 15%.                           , In those days, the Paul Volcker-led Fed had to jack up interest rates to a point where they tipped the economy into recession, something central bankers now want to avoid. Back then, the funds rate eclipsed 19%.                                                                                                                                                                                                                                                            , Baird said the Fed will need to live up to its promise to be "nimble" if it is to continue to assuage market fears about runaway inflation.                                                                                                                                                                                                                                                                                                                                    , "Will the path that they've laid out be enough to bring inflation back down to more comfortable levels in some reasonable time frame? The possibility certainly exists that they could get more aggressive," he said.                                                                                                                                                                                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/federal-reserve-interest-rate-hike-march-2022-inflation </td>
   <td style="text-align:left;"> 2022-03-17 01:34:34 </td>
   <td style="text-align:left;"> Fed raises interest rates for first time in 3 years, projects 6 more hikes as inflation soars </td>
   <td style="text-align:left;">  Nicole Webb, Gary Kaltbaum and Phil Blancato react to the Federal Reserve raising the fund rate by 25 basis points on 'Making Money.'                                                                                                                                                                                                                                                                                                                                              , The Federal Reserve said on Wednesday that it would raise interest rates for the first time in three years as policymakers look to cool red-hot inflation, a move that comes at a precarious time for the U.S. economy as it confronts a continuing pandemic and a war in Europe.                                                                                                                                                                                                   , The widely anticipated move – that the Fed would raise rates by 25-basis points – brings to an end the ultra-easy monetary policy put in place two years ago to prop up the economy through the COVID-19 pandemic.                                                                                                                                                                                                                                                                  , The rate liftoff, which puts the benchmark federal funds rate at a range between 0.25% and 0.5%, is likely just the start of a series of increases intended to curb runaway inflation.                                                                                                                                                                                                                                                                                              , New economic projections released after the meeting show that policymakers expected six more, similarly sized increases over the course of 2022 after consumer prices hit a 40-year-high. It marks a considerable shift from just six months ago, when half of the central bankers believed interest rate increases were not warranted until at least 2023. Fed officials also expect inflation to remain elevated, ending 2022 at 4.3% – far above the Fed's annual target of 2.3%., "With appropriate firming in the stance of monetary policy, the committee expects inflation to return to its 2 percent objective and the labor market to remain strong," the Fed said in its post-meeting statement. It noted the committee anticipates "that ongoing increases in the target range will be appropriate."                                                                                                                                                           , Just one voting member of the Federal Open Market Committee dissented: St. Louis Fed President James Bullard, who wanted a 50-basis point increase.                                                                                                                                                                                                                                                                                                                                 , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                                                                                                , The meeting comes one week after the Labor Department said the consumer price index rose 7.9% in February from the previous year, marking the fastest increase since January 1982, when inflation hit 8.4%. The CPI – which measures a bevy of goods ranging from gasoline to health care – rose 0.8% from January.                                                                                                                                                                 , But the Fed must walk an economic tightrope this week as it juggles sky-inflation with the COVID-19 health crisis, including new health restrictions in major Chinese cities, and the Russia-Ukraine war. Officials downgraded their forecast this year, penciling in much slower economic growth of 2.8%, down from a 4% estimate in December.                                                                                                                                     , Jerome Powell, chairman of the U.S. Federal Reserve, during a Senate Banking, Housing and Urban Affairs Committee hearing in Washington, D.C., U.S., on Tuesday, Sept. 28, 2021.  (Kevin Dietsch/Getty Images/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                            , Although Fed officials carefully telegraphed to the public their rate-hike plans, the Russian invasion of Ukraine, which has triggered a massive humanitarian crisis, has upended those plans. Some analysts have warned that because the conflict exacerbated already sky-high inflation, it could force the central bank to take a more nimble approach or risk inducing a recession.                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                         , During his post-meeting press conference, however, Chair Jerome Powell downplayed broader economic concerns from the war.                                                                                                                                                                                                                                                                                                                                                           , "The probability of a recession in the next year is not particularly elevated," Powell told reporters, citing the strong labor market, solid payroll growth and strong business and household balance sheets. "All signs that are this is a strong economy, and one that will be able to flourish in the face of less accommodative monetary policy."  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-17 01:14:27 </td>
   <td style="text-align:left;"> Italian 10-Year Yield Falls from 4-Week High </td>
   <td style="text-align:left;"> The yield on the Italian 10-year BTP fell below 1.9% from the one-month high of 1.97% touched on March 14th, as bond prices over-performed its European peers amid short-covering after the recent BTP selloff, while expectations of joint debt issuances from the EU also reduced the risk premium in Italian debt. Last week, the ECB said purchases during the third quarter under the conventional Asset Purchase Programme would be smaller than previously planned and could end in the third quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/16/ukraine-bread-line-bombed-chernihiv-sot-nr-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-17 01:13:46 </td>
   <td style="text-align:left;"> Video: People in line for bread killed by Russian shelling, Ukrainian regional official says - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 01:08:00 </td>
   <td style="text-align:left;"> South African Stocks Rebound Sharply </td>
   <td style="text-align:left;"> The JSE FTSE All Share index extended gains to close 4% firmer at 73,484 on Wednesday, following three consecutive sessions of losses, mainly supported by a sharp rebound in heavyweights tech Naspers and Prosus, tracking the spike in the shares of its biggest investment Tencent Holdings in Asian trading after China vowed policies to boost strained financial markets. Also, bank stocks advanced solidly. Meanwhile, investors awaited the outcome from the US Federal Reserve's policy meeting and monitored potential peace talks between Russia and Ukraine. On the economic front, South Africa's retail sales surged 7.7% year-on-year in January, the fifth straight month of gains and the most since last June, above market expectations of a 4.9% rise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/16/stocks-making-the-biggest-moves-midday-aerovironment-alibaba-boeing-and-more.html </td>
   <td style="text-align:left;"> 2022-03-17 01:00:28 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Alibaba, AeroVironment, Boeing and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                         , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                             , Alibaba, JD.com, Pinduoduo — Shares of Chinese companies listed publicly in the U.S. surged as Beijing signaled support for the stocks. The Chinese government said it supports the listing of businesses overseas and that its crackdown on technology companies should end soon, according to Chinese state media. Alibaba jumped 36.7%, JD.com added 39.4% and Pinduoduo rallied 56%., AeroVironment — The defense stock jumped 9.8% after NBC News reported that the White House was considering supplying drones made by AeroVironment to the Ukrainian government to help fend off Russian forces.                                                                                                                                                                          , Lockheed Martin — Shares of the defense contractor dropped 6.1% after Bloomberg News reported that the Pentagon would cut its request for F-35 fighter jets in the new fiscal budget proposal.                                                                                                                                                                                          , Boeing — Boeing shares rallied 5.1% after Baird added the aerospace company to its bullish fresh picks list. While the company's stock is down year-to-date, investors should buy the dip as deliveries of the 737-Max are expected to resume in China even amid the recent surge in Covid-19 cases, analysts wrote.                                                                    , Micron Technology — The semiconductor stock surged 9%. Bernstein analysts upgraded Micron to outperform, saying the firm will see huge gains after supply issues are resolved later this year.                                                                                                                                                                                          , Spotify — The streaming company's stock price jumped more than 6% in midday trading. Spotify signed a stadium and shirt sponsorship deal on Tuesday with Spanish soccer team FC Barcelona. The team members will wear the Spotify logo on their uniform shirts for the next four years.                                                                                                 , Starbucks — Shares of Starbucks climbed 7.9% after the coffee giant announced CEO Kevin Johnson's retirement following five years on the job and said that Howard Schultz will return as interim CEO. JPMorgan analysts also upgraded Starbucks to overweight and said its shares could rally 22% despite recent China restrictions.                                                    , Nvidia — The chipmaker's stock price surged 6.6%. Analysts at Wells Fargo added Nvidia to their "signature picks" list, saying the stock's recent tumble has created an attractive risk/reward profile. Wells Fargo also expects upbeat announcements at Nvidia's upcoming investor day.                                                                                                , Nike — The sportswear company's stock price spiked 4.9%. Bernstein said Tuesday that supply chain issues have created a buying opportunity in Nike, which analysts expect will maintain its top position in China.                                                                                                                                                                      , NortonLifeLock — Shares for NortonLifeLock tumbled 13.3% after Britain signaled that the cybersecurity company's $8.6 billion deal to acquire competitor Avast may get an "in-depth" probe by antitrust regulators.                                                                                                                                                                     , — CNBC's Hannah Miao, Jesse Pound and Samantha Subin contributed reporting.                                                                                                                                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 00:59:55 </td>
   <td style="text-align:left;"> Madrid Stocks End at Over 2-Week High </td>
   <td style="text-align:left;"> The Ibex 35 index rose 1.75% to close at 8,380 on Wednesday, its highest since February 28th, extending gains for a fourth straight session, mainly driven by banks ahead of an expected interest rate increase from the Federal Reserve. Market sentiment was also supported by renewed optimism of progress in talks between Russia and Ukraine along with China's stimulus pledge. Meanwhile, Spain has raised concerns with the European Commission about the impact of surging inflation on its 70-billion-euro EU-funded recovery plan and expects "guidance" on limiting its effects on projects. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Close at 2-Week High </td>
   <td style="text-align:left;"> The FTSE MIB index closed 3.3% higher at 24,285 on Wednesday, the highest in two-weeks, as negotiations between the Russian and Ukrainian delegations progressed while investors weighed on reports that China will take measures to support financial markets. Financial shares led the gains on the corporate front, driven by Banco Bpm (8.7%) and Bper Banca (7.3%) amid expectations of rate hikes by the Federal Reserve and the Bank of England after the session’s close. At the same time, Intesa Sanpaolo (7%), and Unicredit (6.2%), both booked significant gains as Italy's larger banks continue to assess its exposure to Russian and Ukrainian capital, with the former announcing that loans to Russian and Ukrainian clients totaled EUR 5.1 billion, or 1% of its total assets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 00:47:00 </td>
   <td style="text-align:left;"> European Shares Rally, DAX ends at Over 2-Week High </td>
   <td style="text-align:left;"> European equity markets rose sharply on Wednesday, with Germany’s DAX up almost 4% to an over 2-week high above 14,450 as global sentiment was boosted by signs of progress in Russia-Ukraine talks. Negotiators have been discussing a proposal for Ukraine to become a neutral country and accept limits on its armed forces in exchange of a ceasefire and Russian withdrawal. Gains also came on the back of reports that China will step in to support markets and the economy. Among single stocks, BMW gained about 4% despite the German auto lowered its 2022 operating profit forecasts due to geopolitical uncertainty. Germany’s largest energy firm E.ON also rose after saying it expects 2022 core earnings to fall up to €7.6 billion from €7.9 billion in 2021, on concerns over the Nord Stream 1 pipeline. Meanwhile, investors weighed an expected interest-rate increase from the Federal Reserve after the closing bell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Rebound, Ends 3.68% Higher </td>
   <td style="text-align:left;"> The CAC 40 ended 233.64 points or 3.68% higher to close at 6,588.64 on Wednesday, amid renewed optimism of progress in talks between Russia and Ukraine, and as investors await the monetary policy decision and economic forecasts from the US Fed later today. Capital goods, banks and luxury stocks led the gains with 36 out of 40 stocks ending in the green. Among the individual stocks, top gainers included Societe Generale (+9.13%); Renault (7.72%); Hermes International (+7.54%); STMicroelectronics (+7.48%); and Alstom (+7.47%). On the other hand, Total Energies slumped by 0.47% amid lower oil prices and Thales dragged by 1.17% on prospects of reduced military spending. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-17 00:45:00 </td>
   <td style="text-align:left;"> UK Stocks Close at 2-Week High </td>
   <td style="text-align:left;"> The FTSE 100 closed 1.8% higher at a two-week high of 7,295 on Wednesday, tracking European equity markets upwards as talks between Kyiv and Moscow progressed and Chinese officials eased concerns over the regulation of overseas listing while pledging to support domestic financial markets. Base metal miners booked significant gains in London, led by Polyemetal international (12%) as the Anglo-Russian firm continued to rebound after losing over 90% of its share value after Russia’s invasion of Ukraine. Financial shares also edged higher, driven by Prudential (4.3%) and Lloyds (2.4%), as investors awaited interest rate decisions by the Bank of England and the Federal Reserve, which are both expected to increase borrowing costs. Also, the UK’s competition watchdog said the takeover bid of cybersecurity firm Avast by its American rival NortonLifeLock for $8.6 billion could be subject to an in-depth investigation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60750642?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-17 00:26:50 </td>
   <td style="text-align:left;"> Fears Russia will not be able to pay its debts mount </td>
   <td style="text-align:left;"> Russia may be about to default on its debts after Western sanctions were imposed in the wake of its invasion of Ukraine.                                                                                                                                                                 , It is due to make $117m in interest payments to investors on two dollar-denominated bonds today.                                                                                                                                                                                         , And credit ratings agencies have warned that a debt default is "imminent".                                                                                                                                                                                                               , However Russia's finance minister said the interest owed had now been paid and was waiting clearance in the US banking system.                                                                                                                                                           , Anton Siluanov said: "We have the money, we have made the payment, now the ball is in the court, primarily, of the American authorities."                                                                                                                                                , So, for now, it remains unclear whether today's deadline for making the interest payments has been met or not.                                                                                                                                                                           , The Russian government - and firms such as Gazprom, Lukoil and Sberbank - owe about $150bn to overseas investors.                                                                                                                                                                        , Most of this is in either dollars or euros, and interest and repayments must be made in those currencies.                                                                                                                                                                                , But sanctions imposed after the invasion of Ukraine mean Russia has lost access to a large proportion of its $630bn (£470bn) in foreign currency reserves. However, it still receives dollars for the oil, gas and other things it sells abroad, and that foreign currency is accessible., If Russia does default, it will be the country's first debt default since 1998.                                                                                                                                                                                                          , It would also be its first default on a foreign-currency debt since the 1917 revolution when the new Bolshevik government refused to recognize the debts of the last tsar.                                                                                                               , If Russia pays using dollars held domestically then default worries would go away for now.                                                                                                                                                                                               , Another possibility is that Russia does not pay today - even though the $117m is due today, technically there is a 30-day grace period to finally settle the bill by 15 April. So Russia would not be deemed officially in default until then, ratings agencies suggest.                 , A third option is where Russia pays in roubles. Its foreign ministry has said it would make payments to international investors in roubles if it were stopped from paying them in dollars or euros.                                                                                      , However, neither of the two dollar-denominated bonds which need to be paid today allow for any other currency to be used, so this would likely to trigger a default.                                                                                                                     , Some of Russia's other debt agreements do allow for different currencies to be used - in which case paying in roubles could be acceptable.                                                                                                                                               , This would depend on whether the rouble payment was judged to be the same value as the original dollar or euro payment that investors were expecting.                                                                                                                                    , Investors in Russia have seen the value of their investments slump in recent days.                                                                                                                                                                                                       , The problem for many will have been the swiftness of Russia's fall from financial grace, which has left them with little time to react by selling-off their holdings.                                                                                                                    , Credit ratings agency Moody's says that in its 21-point ratings scale, which indicates how reliable a country is as a place to invest, Russia's rating is now at its second-lowest, and could fall still further.                                                                        , Moody's says this rating means both that it expects Russia to default, and that it is warning investors in Russia that they could lose between 35% and 65% of their money.                                                                                                               , The last time that Russia defaulted - in 1998 - it sent shocks through the financial markets. A default now would be hugely symbolic, but is "unlikely to have significant ramifications", according to Capital Economics chief economist William Jackson.                               , The IMF has said it will downgrade its forecast of 4.4% global economic growth in 2022 as a result of the war. However, IMF head Kristalina Georgieva has also discounted the idea of a wider shock to the global financial system from a Russian default.                               , But she warned that the sanctions imposed on Russia would lead to a "deep recession" there, and that the war would drive up global food and energy prices.                                                                                                                               , The unknown factor, as yet, is what debt defaults there may be by Russian firms - and what impact these may have on overseas investors who have heavily invested in Russia.                                                                                                              , Any debt default is likely to exacerbate the financial and economic problems Russia is now facing.                                                                                                                                                                                       , Before it invaded Ukraine, Russia was considered one of the most creditworthy countries in the world, with low debt levels. But things have now dramatically changed.                                                                                                                    , Foreign firms have left in droves, and Moscow has already imposed strict credit controls to limit the outflow of money in order to protect the economy and the rouble. Despite this, Russia's economy is set to shrink 7% this year as a result of sanctions.                            , Inflation in February was already 9.15% before the invasion of Ukraine. It is now forecast to surge significantly this year - despite Russia's central bank raising interest rates from 9.5% to 20%.                                                                                     , The origins of a notorious street gang that arose in Birmingham                                                                                                                                                                                                                          , Stock car racing is raw and unfiltered - who will finish the season on a high?                                                                                                                                                                                                           , 'The Boss' Sasha Banks on her love for wrestling and what it means to her                                                                                                                                                                                                                , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/uganda/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-17 00:20:42 </td>
   <td style="text-align:left;"> Uganda Inflation Rate at Over 1-1/2-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Uganda rose to 3.2 percent in February of 2022 from 2.7 percent in the prior month, reaching its highest point since July of 2020. Upward pressure came mostly from prices of furnishings (9.6 percent vs 5.8 percent in January); education (9 percent vs 0.6 percent); personal care, social protection &amp; miscellaneous goods (4.6 percent vs 4 percent) and food &amp; non-alcoholic beverages (4.5 percent vs 5.3 percent). On a monthly basis, consumer prices went up 1 percent, after decreasing 0.3 percent in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/senate-committee-vote-biden-fed-nominees-after-raskin-bows-out </td>
   <td style="text-align:left;"> 2022-03-17 00:16:43 </td>
   <td style="text-align:left;"> Senate committee to vote Wednesday on Biden's Fed nominees after Raskin bows out </td>
   <td style="text-align:left;"> Sen. Joe Manchin, D-WV, answers Fox News Digital's questions at CERAWeek.                                                                                                                                                                               , WASHINGTON - The U.S. Senate Banking Committee plans to hold a meeting Wednesday to vote on advancing four nominees for the Federal Reserve, including the renomination of Chairman Jerome Powell, according to the committee's website.                , BIDEN FED NOMINEE SARAH BLOOM RASKIN WITHDRAWS BOARD CANDIDACY                                                                                                                                                                                          , The panel will meet at an unspecified time to also vote on whether to advance the nomination of Fed Governor Lael Brainard to become the central bank's vice chair, and the nomination of Lisa Cook and Philip Jefferson to join the board as governors., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                             , (Reporting by Pete Schroeder) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/apple-supplier-foxconn-resumes-work-shenzhen-covid-lockdown </td>
   <td style="text-align:left;"> 2022-03-16 23:38:36 </td>
   <td style="text-align:left;"> Apple supplier Foxconn resumes some work in Shenzhen, China, after COVID lockdown </td>
   <td style="text-align:left;"> Ronald Reagan Institute director Roger Zakheim discusses the Russia-Ukraine war and the Iran deal.                                                                                                                                                                                                                                                                                                                     , Foxconn, one of Apple's biggest suppliers, announced Wednesday that it had partially resumed production in a key Chinese city after new COVID-19 restrictions forced the company to temporarily suspend operations.                                                                                                                                                                                                    , Beijing imposed a seven-day lockdown of Shenzhen, a key port city sometimes referred to as the "Silicon Valley of China," as it pursues a zero-COVID strategy. Shenzhen is home to Foxconn as well as Tencent and Huawei.                                                                                                                                                                                              , A Foxconn spokesperson told FOX Business on Wednesday that the company has started applying a "closed-loop management process" at its campus in Shenzen in order to restart some halted operations.                                                                                                                                                                                                                    , SAUDI ARABIA CONSIDERS ACCEPTING YUAN INSTEAD OF DOLLARS FOR CHINESE OIL SALES                                                                                                                                                                                                                                                                                                                                         , "In applying this closed-loop management process within the Shenzhen campus and in implementing the required health measures for the employees who live on campus, some operations have been able to restart and some production is being carried out at those campuses," the spokesperson said. "The company will continue to work closely with the relevant authorities in monitoring these operations very closely.", In this May 26, 2010, file photo, staff members work on the production line at the Foxconn complex in the southern Chinese city of Shenzhen, southern China.  (Associated Press)                                                                                                                                                                                                                                       , Foxconn earlier this week said that it had suspended factory lines in Shenzhen because of the ban on nonessential work, but that it shifted production to a different location in China that has not been affected by the latest restrictions in order to minimize the potential impact.                                                                                                                               , Chinese authorities reported 3,507 locally transmitted cases of coronavirus across dozens of mainland cities on Tuesday, an outbreak driven by the fast-spreading "stealth variant" of BA.2, a subvariant of omicron. Shenzhen reported 86 new cases; the lockdown affects roughly 17.5 million people who live in the city, which neighbors Hong Kong.                                                                , WHERE ARE SURGING CONSUMER PRICES HITTING AMERICANS THE HARDEST?                                                                                                                                                                                                                                                                                                                                                       , The move threatened to further inflame an already snarled global supply chain, which has contributed to the highest inflation in the U.S. since 1982. The Labor Department reported last week that consumer prices surged 7.9% in February from the previous year – driven in part by a shortage of electronics.                                                                                                       , Foxconn's factory in Shenzhen produces iPhones, Macs and iPads. But more than half of iPhones are produced at a separate factory in the Henan province, according to a Bank of America research note published on Monday.                                                                                                                                                                                              , A janitor checks his phone outside closed shops in Huaqiangbei area, the world's biggest electronics market, in Shenzhen in south China's Guangdong province Monday, March 14, 2022.  ((Feature China/Future Publishing via Getty Images) / Getty Images)                                                                                                                                                              , "Apple/Foxconn have the ability to relocate production to other areas in the short term provided that there is not a significantly higher duration of lockdown," the Bank of America economists wrote. "An increased period of shutdowns can cause ripple effects at other components that can create a shortfall in production."                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                            , Another manufacturing hub hit by new lockdown measures is Changchun, located in the northeast part of the country. The restrictions have affected Volkswagen AG, which halted production at its vehicle and component plants in the city from Monday through Wednesday, as well as Toyota, which halted production at its plant on Monday and will resume once the government gives the green light. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-03-16 23:14:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index at 1-Week Low </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 3.6% to 2,591 on Wednesday, its lowest since March 9th, extending losses for a second straight session, amid weakness across all its vessels segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes fell 191 points to 2,632 points; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, declined 99 points to 2,847 points. Among smaller vessels, the supramax index shed 25 points to 2,876 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-16 22:58:00 </td>
   <td style="text-align:left;"> Toronto Stocks Rise on Upbeat Global Mood </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, followed global equities higher, climbing as much as 1.2% on Wednesday, as traders digested positive cues from Russia-Ukraine talks and awaited a highly anticipated US Fed interest rate decision later in the session. Leading the gains, information technology stocks rose 1.8%, followed by a 1.4% gain in consumer stocks and a 1.2% climb in health-care. On the data front, Canada’s inflation rate quickened to an over three-decade high of 5.7%, beating market expectations of 5.5% in February, marking the eleventh straight month above the central bank’s target of 1-3%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/crude-oil-stocks-change </td>
   <td style="text-align:left;"> 2022-03-16 22:39:00 </td>
   <td style="text-align:left;"> US Crude Inventories Unexpectedly Rise: EIA </td>
   <td style="text-align:left;"> US crude oil inventories rose by 4.345 million barrels to 415.9 million barrels in the week ended March 11th, recovering from a 1.863 million fall in the previous period and compared with market expectations of a 1.375-million-barrel fall, data from the EIA Petroleum Status Report showed. Also, crude stocks at the Cushing, Oklahoma, delivery hub increased by 1.786 million to 24 million barrels, the first increase this year; and distillate stockpiles which include diesel and heating oil went up by 0.322 million barrels, against the consensus of a 1.826-million-barrel drop. Meanwhile, gasoline inventories declined by 3.616 million barrels, the sixth consecutive week of falls and above market forecasts of a 1.579 million drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/etfs-to-match-rising-interest-rates </td>
   <td style="text-align:left;"> 2022-03-16 22:37:05 </td>
   <td style="text-align:left;"> ETFs that can benefit from rising interest rates </td>
   <td style="text-align:left;"> CFRA head of ETF and mutual fund research Todd Rosenbluth analyzes the energy sector on 'The Claman Countdown.'                                                                                                                                                                                                                                                                                                                                                                                                                                   , The Federal Reserve has announced a hike to the federal funds rate by a quarter of a percentage point in a move that was widely expected by Wall Street. Policymakers also signaled there will likely be six more increases this year.                                                                                                                                                                                                                                                                                                            , The pivot, led by Chairman Jerome Powell, is the first since 2018 and comes in an effort to combat rising inflation. In February, the consumer price index climbed 7.9% on an annual basis, the fastest increase since January 1982.                                                                                                                                                                                                                                                                                                              , Federal Reserve Chairman Jerome Powell testifies before the Senate Banking Committee hearing on Capitol Hill on Dec. 1, 2020.  (Susan Walsh/Pool via Reuters/File)                                                                                                                                                                                                                                                                                                                                                                                , FOX Business provides a roundup of ETF opportunities where investors can benefit from rising interest rates.                                                                                                                                                                                                                                                                                                                                                                                                                                      , WHAT DOES A FEDERAL RESERVE INTEREST RATE HIKE MEAN FOR MAIN STREET?                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , One opportunity that ETFTrends.com CEO Tom Lydon recommends is the SPDR S&amp;P Regional Banking ETF.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , "Regional banks are better positioned than the larger banks to benefit from rising rates as the rates they charge their client lenders rise too," Lydon tells FOX Business. "Most of regional bank revenue comes mostly from lending where larger banks have revenue more diversified into other areas like equity trading and other financial services."                                                                                                                                                                                         , Lydon also recommends the iShares iBoxx High Yield Corporate Bond ETF.                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , "With the threat of aggressive rate hikes waning, high yield bonds are instantly more attractive. Many have anticipated multiple rate hikes for 2022 and beyond in an effort to stave off inflation, but Wall Street is less concerned considering recent events," he explains. "There is over $7 trillion in money market accounts and over $15 trillion in bank accounts receiving next to nothing in yield. Smaller and less frequent rate hikes may give these investors confidence to shift some of those funds to higher yielding vehicles.", Torn dollar with ETF message, Exchange Traded Fund stock market concept (iStock)                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , In addition, Lydon suggests investors consider the Invesco Optimum Yield Diversified Commodity Strategy No K-1 ETF (PDBC), which invests in 14 of the world's most heavily traded commodities, including precious metals, energy and agriculture. PDBC is up about 17% year-to-date.                                                                                                                                                                                                                                                              , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Another ETF option for investors is the FolioBeyond Rising Rates ETF, which invests primarily in interest-only mortgage-backed securities and U.S. Treasury bonds.                                                                                                                                                                                                                                                                                                                                                                                , "While there can be no guarantee of performance, RISR is engineered to have a duration of negative 10 years," FolioBeyond chief strategist Dean Smith tells FOX Business. "This means that for each 1% increase in rates, RISR is designed to experience an increase in [net asset value] by approximately 10%. To our knowledge, no other ETF has such a direct, measurable exposure to medium-term and long-term rates."                                                                                                                        , Smith also suggests the Quadratic Interest Rate Volatility and Inflation Hedge ETF, which invests primarily in Treasury Inflation Protected notes (TIPs).                                                                                                                                                                                                                                                                                                                                                                                         , "IVOL benefits from higher market volatility, but its correlation to interest rate movements is uncertain," Smith says. "Over time, TIPs have had mixed performance as an actual inflation hedge, and they still have positive durations, i.e. they tend to fall in value as interest rates increase. Moreover, IVOL purchases options, for which the fund pays premiums. This tends to reduce the available yield generated by the TIPs holdings."                                                                                               , In addition, Smith likes the Horizon Kinetics Inflation Beneficiaries ETF, which invests in companies involved in energy, commodities and financial services.                                                                                                                                                                                                                                                                                                                                                                                     , "It invests in stocks rather than bonds or interest rate hedges, has a meaningful beta exposure to the stock market generally, and may decline in value if higher interest rates contribute to a worsening economic environment that adversely affects the stock market," Smith notes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lumber </td>
   <td style="text-align:left;"> 2022-03-16 22:29:00 </td>
   <td style="text-align:left;"> Lumber Prices Down to 5-Week Low </td>
   <td style="text-align:left;"> Chicago lumber futures tumbled to $1,200 per thousand board feet, the lowest in near five weeks as the National Association of Home Builders urged the US to increase domestic production and to work with Canada on a new softwood lumber agreement that will eliminate tariffs. The cost of lumber hit a 10-month high of near $1,480 earlier in the month and remains historically high despite the output volumes at sawmills recovered from the constraints of mid-2020 to end-2021. Meanwhile, demand is set to stay strong as the large US home builders make their purchases necessary for the looming spring construction season. Still, the latest data showed builders' expectations of future home buyers in the US fell to the lowest since June 2020 due to the impact of elevated inflation and expected higher interest rates. Markets have been facing shortages as Canada, a leading lumber supplier to the US, was hit by fire, flood and infestations of wood-boring beetles last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/nahb-housing-market-index </td>
   <td style="text-align:left;"> 2022-03-16 22:07:00 </td>
   <td style="text-align:left;"> NAHB Homebuilder Sentiment at 6-Month Low </td>
   <td style="text-align:left;"> The NAHB housing market index in the US fell to a 6-month low of 79 in March of 2022 from 81 in February and below market forecasts of 81. The home sales over the next six months sub-index sank to 70 from 80 and the current single-family sub-index dropped to 86 from 89 while the gauge for prospective buyers increased to 67 from 65. "Builders are more concerned that increasing construction costs and higher interest rates will price prospective home buyers out of the market. While low existing inventory and favorable demographics are supporting demand, the impact of elevated inflation and expected higher interest rates suggests caution for the second half of 2022", NAHB Chief Economist Robert Dietz said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/business-inventories </td>
   <td style="text-align:left;"> 2022-03-16 22:03:01 </td>
   <td style="text-align:left;"> US Business Inventories Rise as Expected </td>
   <td style="text-align:left;"> Manufacturers’ and trade inventories in the US rose 1.1 percent from a month earlier in January of 2022, as expected, after an upwardly revised record-setting 2.4 percent increase in the prior month. Stocks rose the most among retailers (2.0 percent vs 4.7 percent in December), followed by merchant wholesalers (0.8 percent vs 2.6 percent) and manufacturers (0.7 percent vs 0.4 percent). Year-on-year, business inventories climbed 11.4 percent in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/russia-debt-default-economic-sanctions-ukraine </td>
   <td style="text-align:left;"> 2022-03-16 21:57:37 </td>
   <td style="text-align:left;"> Russia on verge of $150B debt default as sanctions cripple economy </td>
   <td style="text-align:left;"> Middlebury Institute Nonproliferation and Terrorism Studies professor Dr. Philipp Bleek discusses the possibility of Russia using chemical weapons.                                                                                                                                                                                                                                                            , Russia is spiraling closer to a historic debt default that could ripple throughout the global economy after the U.S. and its European allies hit the Kremlin with a slew of crippling financial sanctions.                                                                                                                                                                                                     , Moscow's invasion of Ukraine nearly one month ago – the biggest attack on a European state in decades – elicited a raft of economic penalties from Western nations, including cutting off a key part of the Central Bank of Russia by preventing it from selling dollars, euros and other foreign currencies in its roughly $630 billion reserve stockpile.                                                    , The financial fallout has prompted credit rating agencies to downgrade their long-term debt rating for the Russian government to "junk" status, with Fitch warning that international sanctions have brought a "huge shock to Russia's credit fundamentals." It noted additional sanctions remain a distinct possibility.                                                                                      , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                           , Russia has grasped for a way to soften the blow: the central bank more than doubled its key interest rate to 20% in early March after some banks were removed from the Swift financial system and the West froze a significant portion of its currency reserves.                                                                                                                                               , But the Kremlin is now due to pay $117 million in interest on two dollar-denominated bonds on Wednesday; if it fails to make those payments, it will be Russia's first default on foreign debt since the 1917 Bolshevik Revolution, according to JPMorgan Chase.                                                                                                                                               , A man looks to a screen displaying the Russian ruble exchange rates at a shopping mall bank on March 15, 2022, in Moscow, Russia.  (Konstantin Zavrazhin/Getty Images / Getty Images)                                                                                                                                                                                                                          , The Bank of Canada and Bank of England, which track global sovereign defaults, estimate the total value of government debt in default around the world was about $443.2 billion in 2020, or roughly 0.5% of world public debt.                                                                                                                                                                                 , Russian Finance Minister Anton Siluanov said Monday that Moscow will repay creditors from "countries that are unfriendly" in rubles and possibly the Chinese yuan until the sanctions are lifted, with the sanctions preventing the nation from accessing its reserve of dollars and euros. The ruble has depreciated sharply since Russia attacked Ukraine. As of Wednesday morning, 107 rubles were worth $1., FED EXPECTED TO HIKE RATES THIS WEEK, DESPITE UKRAINE VOLATILITY                                                                                                                                                                                                                                                                                                                                               , He said Russia has to pay coupons on its eurobonds and has already asked Western banks to proceed with the transactions.                                                                                                                                                                                                                                                                                       , "Is that a default?" Siluanov asked during an interview with Russian state news. "From Russia's point of view, we are fulfilling our obligations."                                                                                                                                                                                                                                                             , Russian Finance Minister Anton Siluanov attends an international conference dedicated to the 175th anniversary of Sberbank in Moscow on Nov. 10, 2016. ( Reuters/Sergei Karpukhin)                                                                                                                                                                                                                             , Others, however, argue that paying dollar-denominated bonds in rubles constitutes a default. It is unclear whether Russia will be viewed as defaulting on its debt if it pays in rubles. Siluanov accused Western nations of orchestrating the sanctions with the intention of creating a default that "has no real economic grounds."                                                                         , Kristalina Georgieva, the head of the Washington-based International Monetary Fund, said on Sunday a Russian default is no longer "improbable."                                                                                                                                                                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                    , "Russia has the money to service its debt, but cannot access it," she said during an interview on CBS News.                                                                                                                                                                                                                                                                                                    , If Russia fails to meet its obligation, there is a 30-day grace period that provides cover until April 15. But if Moscow indicates that it does not intend to pay its debt, credit rating agencies may declare Russia to be in default before the final deadline.                                                                                                                                              , Russia's central bank is poised to meet again on Friday as it attempts to stave off a full-blown financial crisis.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/wheat </td>
   <td style="text-align:left;"> 2022-03-16 21:45:00 </td>
   <td style="text-align:left;"> Wheat Falls 5% </td>
   <td style="text-align:left;"> Chicago wheat futures fell to below $11 per bushel in mid-March, as apparent progress in ceasefire talks between Russia and Ukraine helped to ease some concerns over supply disruptions. Russia and Ukraine are jointly responsible for over 30% of world wheat exports but commercial activity in Ukraine’s ports has stopped since Russia’s invasion began on February 24th. At the same time, weather forecasts point to rain for the next days in key US crop states, also offering some relief about US crop conditions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/vulnerable-democrats-lowering-gas-prices-policies-raise </td>
   <td style="text-align:left;"> 2022-03-16 21:33:18 </td>
   <td style="text-align:left;"> Vulnerable House Democrats now support lowering gas prices after backing policies to raise them </td>
   <td style="text-align:left;"> Rep. Dan Crenshaw, R-Texas, discusses the green agenda as the GOP questions environmentalists over ties to Russia, as well as the Biden administration's energy policies.                                                                                                                                                                                                                                                      , Politically vulnerable Democrats who once supported policies that would have raised gas prices are now singing a different tune ahead of the November midterm elections.                                                                                                                                                                                                                                                       , Democratic Reps. Elissa Slotkin and Dan Kildee of Michigan, Dina Titus of Nevada, and Kim Schrier of Washington state, who all face tough re-election battles in their districts, have cosponsored the Gas Prices Relief Act of 2022, which would suspend the 18.4 cents-per-gallon federal tax through the midterms and the rest of 2022.                                                                                     , GAS PRICES DIP AS OIL FALLS BELOW $100                                                                                                                                                                                                                                                                                                                                                                                         , Those same lawmakers, however, previously supported policies that would have raised gas prices.                                                                                                                                                                                                                                                                                                                                , Gas Prices (AAA)                                                                                                                                                                                                                                                                                                                                                                                                               , In 2018, Slotkin said she would "immediately" shut down the Enbridge Line 5 pipeline in Michigan, which moves crude oil and other petroleum products from western Canada. Shutting down the pipeline, an effort led by Democratic Michigan Gov. Gretchen Whitmer, would cost Midwest families and businesses an extra $23.7 billion for gasoline and diesel in the first five years, according to Consumer Energy Alliance.    , Notably, Whitmer, who is up for re-election this year, also supports the proposed federal gas tax holiday.                                                                                                                                                                                                                                                                                                                     , In 2021, Kildee cosponsored the Energy Innovation and Carbon Dividend Act, which would impose a fee on the carbon content of fossil fuels. According to the environmental group behind the legislation, Citizens' Climate Lobby, each $10 per metric ton carbon fee would add about 11 cents to a gallon of gasoline, about 6 cents to a therm of natural gas, and 0.9 cents to a kilowatt-hour of coal-generated electricity. , Rep. Elissa Slotkin speaks during a news conference to announce the Shutdown to End All Shutdowns Act in the Capitol on Jan. 29, 2018. (Bill Clark/CQ Roll Call)                                                                                                                                                                                                                                                               , In 1997, Titus, as a state lawmaker, voted for legislation that automatically raises Nevada’s fuel tax by the exact amount of any reduction at the federal level, The Nevada Independent reported. So the 18.4 cents per gallon that would be suspended through the proposed federal gas tax holiday would then be tacked on at the state level.                                                                               , Titus explained to The Nevada Independent earlier this month that the 1997 bill applies to permanent reductions in federal gas taxes, while the 2022 bill she is cosponsoring is a temporary measure.                                                                                                                                                                                                                          , Gas prices are advertised at almost $7 a gallon on March 7, 2022, in Los Angeles. (AP Photo/Marcio Jose Sanchez / AP Newsroom)                                                                                                                                                                                                                                                                                                 , In 2018, Schrier supported a failed ballot measure to impose a carbon fee in the state of Washington that would have increased every year until emissions targets were met. According to The Seattle Times, the measure would have raised gas prices 14 cents per gallon in the first year.                                                                                                                                    , Meanwhile, Rep. Angie Craig, D-Minn., who is a top target for Republicans trying to take back the House in the midterms, asked President Biden to tap the strategic petroleum reserve to lower gas prices in November 2021. Along with Kildee, she, too, cosponsored the Energy Innovation and Carbon Dividend Act of 2021 that would raise gas prices.                                                                        , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                        , Gas prices have been on a steady rise due to strained supply and increased demand, but Russia’s invasion of Ukraine on Feb. 24 accelerated the pace, sending gas prices soaring past levels last seen during the Great Recession.                                                                                                                                                                                              , The national average for a gallon of regular gasoline fell to $4.305 as of Wednesday morning, as oil prices retreated, according to AAA. On Friday, prices hit a record high of $4.33 per gallon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-16 21:33:00 </td>
   <td style="text-align:left;"> US Stocks Rise for 2nd Day, FOMC Eyed </td>
   <td style="text-align:left;"> US stocks were higher on Wednesday, extending the previous session rally, as traders await the FOMC decision later in the day and a highly-anticipated 25bps increase in the fed funds rate. The Dow Jones was up more than 300 points, the S&amp;P 500 added roughly 1.6% and the tech-heavy Nasdaq soared more than 2.5%. Market sentiment was also supported by apparent progress in ceasefire talks between Russia and Ukraine and China's pledge to roll out policies favourable for capital markets. Investors will also keep an eye on Ukrainian President address to Congress on Wednesday. On the data front, retail sales rose less than expected last month as inflation continues to pressure purchasing power. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/poland/current-account </td>
   <td style="text-align:left;"> 2022-03-16 21:18:00 </td>
   <td style="text-align:left;"> Polish Current Account Switches to Deficit </td>
   <td style="text-align:left;"> Poland’s current account shifted to a EUR 64 million deficit in January of 2022, from a EUR 2034 million surplus in the same month of the previous year and compared with market expectations of a EUR 943 million shortfall. It was the smallest current gap since May of 2021. Goods account swung to a deficit of EUR 64 million compared to a surplus of EUR 1286 million a year ago while the services surplus expanded to EUR 1851 million from EUR 1669 million. At the same time, the primary income gap narrowed to EUR 320 million from EUR 377 million and the secondary income deficit decreased to EUR 409 million from EUR 544 million a year earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/wholesale-sales </td>
   <td style="text-align:left;"> 2022-03-16 20:38:00 </td>
   <td style="text-align:left;"> Canada Wholesale Sales Rise More than Initially Thought </td>
   <td style="text-align:left;"> Wholesale sales in Canada grew by 4.2% month-over-month to CAD 79.8 billion in January of 2022, compared to preliminary estimates of a 3.8% rise. It marks the sixth consecutive month of growth in the sector, and was the largest since June 2020. Gains were widespread in the sector, with five of seven subsectors that represent 72% of total wholesale sales reporting higher sales, notably building material and supplies (14%), personal and household goods (10.6%), and machinery, equipment and supplies (6.6%). By contrast, the largest decline in sales was observed for motor vehicle and motor vehicle parts and accessories (-5.8%), reflecting lower exports and imports of motor vehicles in the month as supply chain issues continue to plague the subsector. Year-on-year, wholesale sales advanced 14.6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/retail-sales </td>
   <td style="text-align:left;"> 2022-03-16 20:36:00 </td>
   <td style="text-align:left;"> US Retail Sales Rise Only 0.3% in February </td>
   <td style="text-align:left;"> Retail sales in the US edged up 0.3% mom in February of 2022, easing from an upwardly revised 4.9% jump in January and below market forecasts of a 0.4% gain, as rising inflation limited purchasing power. Sales at gasoline stations recorded the biggest increase (5.3%) as gasolines prices soared nearly 7% last month, but excluding gas stations, retail sales fell 0.2%. Other increases were also seen in sales at food services and drinking places (2.5%) as omicron infections eased; miscellaneous store retailers (1.9%); sporting goods, hobby, musical and book stores (1.7%); clothing (1.1%); building materials and garden equipment (0.9%); and auto dealers (0.8%). On the other hand, retail sales fell at nonstore retailers (-3.7%); health and personal care stores (-1.8%); furniture stores (-1%); and food and beverages stores (-0.5%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/export-prices </td>
   <td style="text-align:left;"> 2022-03-16 20:34:00 </td>
   <td style="text-align:left;"> US Export Prices Rise the Most on Record </td>
   <td style="text-align:left;"> US export prices rose 3.0 percent from a month earlier in February of 2022, accelerating from a downwardly revised 2.8 percent advance in January. It was the largest monthly rise since 1-month percent changes were first published in January 1989. Prices for agricultural exports increased 3.0 percent, following a 2.8 percent increase in the prior month, as higher prices for soybeans, corn, and cotton more than offset lower nut prices. The cost of nonagricultural exports rose 3.0 percent, the most on record, due to higher prices for nonagricultural industrial supplies and materials; capital goods; consumer goods; automotive vehicles; and nonagricultural foods. On a yearly basis, US exports advanced 16.6 percent in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-16 20:33:00 </td>
   <td style="text-align:left;"> Canada Inflation Rate Climbs to Over 30-Year High </td>
   <td style="text-align:left;"> Canada’s annual inflation rate quickened to 5.7% in February of 2022, the highest since August of 1991, slightly above market expectations of 5.5%, as geopolitical risks and tight OPEC+ supplies fueled a rally in oil prices to over 13-year highs and logistical issues continued to underpin raw material and transportation costs. Prices rose faster in six of the eight major components, notably for shelter (6.6% vs 6.2% in January), which rose at the steepest pace since August 1983. Sharp price increases were also seen in transportation (8.7% vs 8.3%), bolstered by a 32.3% surge in gasoline charges at the pump; costs of food (6.7% vs 5.7%), as prices of food in grocery stores rose at the fastest rate in 13 years. Excluding gasoline, the CPI rose at a fresh record pace of 4.7%. On a monthly basis, consumer prices rose 1.0%, beating market forecasts of a 0.9% gain and marginally quicker than a 0.9% increase in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/import-prices </td>
   <td style="text-align:left;"> 2022-03-16 20:32:00 </td>
   <td style="text-align:left;"> US Import Prices Rise Less than Forecast </td>
   <td style="text-align:left;"> The price index for US imports increased 1.4 percent from a month earlier in February of 2022, easing from a downwardly revised 1.9 percent rise in January, which was the biggest advance since 2011 and below market expectations of 1.5 percent. Import fuel prices advanced 6.9 percent in February, after increasing 7.7 percent the previous month, with higher petroleum prices more than offsetting a decrease in natural gas prices. Cost for nonfuel imports increased 0.8 percent in February, following a 1.3 percent rise the previous month on the back of higher prices for nonfuel industrial supplies and materials; foods, feeds, and beverages; capital goods; consumer goods; and automotive vehicles. Nonfuel import prices have not recorded a monthly decline since November 2020. On a yearly basis, US import prices advanced 10.9 percent in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/16/business/starbucks-kevin-johnson-howard-schultz.html </td>
   <td style="text-align:left;"> 2022-03-16 20:28:05 </td>
   <td style="text-align:left;"> Starbucks C.E.O. Retires, and Howard Schultz Steps In as Interim - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Kevin Johnson, who was named chief executive in 2017, will leave his post on April 4.                                                                                                                                                                                                                                                                                                                                                                                                                     , By Julie Creswell and Noam Scheiber                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , For the past two years, even as the pandemic shut down key markets and created supply shortages, Kevin Johnson, the chief executive of Starbucks, managed to lead the company to robust revenue and profit growth.                                                                                                                                                                                                                                                                                        , But in recent months, those operational and financial successes have been overshadowed by a wave of employees — “partners” in Starbucks parlance — who have taken to social media to criticize work conditions and raise other issues at the chain. As a result, more than 100 Starbucks stores in more than 25 states have filed for union elections. Many either have begun to vote or are likely to vote in the coming months. At least six have voted to unionize.                                    , On Wednesday, in an abrupt move, Starbucks said Mr. Johnson, who has held the job since 2017, will retire on April 4 after 13 years with the company.                                                                                                                                                                                                                                                                                                                                                     , His interim replacement until the board of directors names a permanent one is a familiar name: Howard Schultz.                                                                                                                                                                                                                                                                                                                                                                                            , Mr. Schultz, 68, joined Starbucks in the 1980s and built it into a global coffee giant. And this isn’t the first time he has come back to oversee the company. After stepping down as chief executive in 2000, he returned as C.E.O. from 2008 to 2017, when Mr. Johnson took over and Mr. Schultz became executive chairman. Mr. Schultz will also rejoin the company’s board. Shares of Starbucks rose 4.8 percent to $87.10 on Wednesday.                                                              , The unexpected leadership change followed weeks of mounting pressure from investors as more stores filed for union elections. “We believe that Starbucks’s reputation may be jeopardized due to reporting of aggressive union-busting tactics,” a large group of investors, representing more than $1 billion in Starbucks stock, said in a letter sent to Mr. Johnson on Tuesday. Starbucks has denied engaging in anti-union activity.                                                                  , This week, the National Labor Relations Board filed a complaint accusing the company of illegally penalizing two workers involved in a union drive at a Starbucks in Phoenix, the latest in the chain’s labor struggles.                                                                                                                                                                                                                                                                                  , It is unclear whether the return of Mr. Schultz signals a softening of the company’s battles against unions or a deeper entrenchment. Mr. Schultz, who stepped down as executive chairman in 2018 and was, at the time, one of the largest Starbucks stockholders with 33 million shares, has played a significant role in the company’s response to stores that have sought to unionize.                                                                                                                 , In September, Mr. Schultz visited Buffalo to address local managers, telling them that the company had let them down by failing to help them address operational issues at their stores, and that he was not anti-union but “pro-Starbucks,” said one person who attended but was not authorized to speak publicly. Other Starbucks executives, like John Culver, the chief operating officer, and Rossann Williams, president of retail for North America, attended the meeting, but Mr. Johnson did not., Starbucks declined to make Mr. Schultz and Mr. Johnson available for interviews.                                                                                                                                                                                                                                                                                                                                                                                                                          , After the leadership change was announced on Wednesday, Mellody Hobson, Starbucks’s chairwoman, acknowledged to CNBC that the company had “made some mistakes” in addressing workers’ concerns. Ms. Hobson is co-chief executive of Ariel Investments, a firm that considers itself an early adopter of environmental, social and governance investing.                                                                                                                                                   , Jonas Kron, the chief advocacy officer for Trillium Asset Management, one of the investment firms that has written to and met with Starbucks executives urging them to take a neutral posture, said he believed the comment could be “the first signal of a pivot” on the union issue.                                                                                                                                                                                                                    , But a few hours later, during the question-and-answer session of Starbucks’s annual shareholder meeting, Ms. Hobson said the issue of neutrality was “nuanced” and would limit “our ability to speak to our partners in certain ways.”                                                                                                                                                                                                                                                                    , Mr. Kron later said he considered the comments at the meeting “disappointing.”                                                                                                                                                                                                                                                                                                                                                                                                                            , Various Starbucks executives mentioned during the shareholder meeting how successfully the company had worked with its employees during the pandemic, with pay and other benefits improving over the past year.                                                                                                                                                                                                                                                                                           , Starbucks is one of many companies where employees, many of whom worked long hours and under arduous conditions during the pandemic, are now trying to organize through TikTok and Twitter accounts, seeking better wages, steady hours and increased benefits.                                                                                                                                                                                                                                           , Two weeks ago, employees at a Manhattan location of REI, the outdoor equipment and apparel retailer, voted to create the first union at that company. Voting in union elections at two Amazon warehouses will end this month.                                                                                                                                                                                                                                                                             , Mr. Johnson, a former senior executive at Microsoft who was Starbucks’s president when he was named chief executive, raised the prospect of stepping down with the board of directors last year, he said in a company statement on Wednesday.                                                                                                                                                                                                                                                             , “A year ago, I signaled to the board that as the global pandemic neared an end, I would be considering retirement from Starbucks,” Mr. Johnson said. Starbucks said he would continue to serve on the board and as a consultant through September. The company said it had been planning for the succession since last year and anticipated it would have a new chief executive by fall.                                                                                                                  , The first time Mr. Schultz returned to Starbucks, he abruptly replaced Jim Donald as chief executive when the company was struggling with a downturn in the economy, an influx of coffee competition and missteps.                                                                                                                                                                                                                                                                                        , This time, while Starbucks is on stronger financial footing, Mr. Schultz will have to deal with the rising union issue, a concern he has faced before.                                                                                                                                                                                                                                                                                                                                                    , When he acquired Starbucks in 1987, several of the company’s Seattle stores were unionized, as was its local coffee roasting plant. Mr. Schultz made clear to union officials that he did not welcome the relationship.                                                                                                                                                                                                                                                                                   , “He went ballistic screaming at me, telling me to get out of the plant,” said Pam Blauman-Schmitz, the local union rep for the United Food and Commercial Workers, of her first visit to the plant under Mr. Schultz’s ownership. “He followed me all the way out.”                                                                                                                                                                                                                                       , In the late 1980s, workers at the stores voted to decertify the union, and the roasting plant followed in the early 1990s. In a subsequent book, Mr. Schultz said a single worker “did some research on his own and began an effort to decertify the union.” But he acknowledged that he did not want the company to be unionized. ﻿                                                                                                                                                                       , “I was convinced that under my leadership, employees would come to realize that I would listen to their concerns,” Mr. Schultz wrote. “If they had faith in me and my motives, they wouldn’t need a union.”                                                                                                                                                                                                                                                                                               , Union officials believed that Mr. Schultz had played a role in the decertification. “We thought it was initiated by a worker that Howard had handpicked to run the decertification campaign,” Ms. Blauman-Schmitz said.                                                                                                                                                                                                                                                                                   , Marie Solis contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/16/chinese-stocks-trading-in-the-us-rocket-higher-after-china-signals-support-for-the-shares.html </td>
   <td style="text-align:left;"> 2022-03-16 20:24:45 </td>
   <td style="text-align:left;"> Chinese stocks trading in the U.S. rocket higher after China signals support for the shares </td>
   <td style="text-align:left;"> , Shares of Chinese companies listed publicly in the U.S. surged Wednesday as China signaled support for the stocks.                                                                                                                                 , Regulators from both countries are progressing toward a cooperation plan on U.S.-listed Chinese stocks, according to Chinese state media. The report cited a meeting Wednesday chaired by Vice Premier Liu He, who heads China's finance committee., The Chinese government supports the listing of companies overseas and said its crackdown on technology companies should end soon, the state media report said.                                                                                     , Alibaba jumped 36.7%, JD.com added 39.4% and Pinduoduo rallied 56% Wednesday.                                                                                                                                                                      , The move comes as American depositary receipts of Chinese companies have been beaten down recently amid regulatory and delisting fears. ADRs are shares of non-U.S. firms traded on U.S. exchanges.                                                , The Nasdaq Golden Dragon China index, which tracks the performance of U.S.-listed Chinese stocks, before Wednesday's trading session was down 38.8% in 2022 and 69.2% in the past 12 months.                                                       , The Securities and Exchange Commission last week named five U.S.-listed ADRs of Chinese companies that failed to comply with the Holding Foreign Companies Accountable Act.                                                                        , The act allows the SEC to delist and even ban companies from listing on U.S. exchanges if American regulators cannot review company audits for three consecutive years.                                                                            , Last summer, Chinese regulators stepped up their oversight on U.S.-listed Chinese stocks. Regulators reportedly asked Chinese ride-hailing giant Didi to delist from the U.S. months after the company's IPO.                                      , — CNBC's Evelyn Cheng contributed to this report.                                                                                                                                                                                                  , Xpeng and more: Morgan Stanley says these stocks will benefit from rising oil prices                                                                                                                                                               , Morgan Stanley upgrades Chinese TikTok rival and predicts over 60% in share price gains                                                                                                                                                            , Global investor Mark Mobius expects Chinese stocks to rebound, aided by Russia invading Ukraine                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                   , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2022-03-16 19:56:00 </td>
   <td style="text-align:left;"> EU Natural Gas Down 5% </td>
   <td style="text-align:left;"> EU natural gas front-month futures eased to €109 per megawatt-hour on Wednesday afternoon, close to 2-week lows touched in the prior session and remaining more than 65% below a record high of €345 hit last week. Traders digested developments in the Russia-Ukraine ceasefire talks, with Ukraine’s President Zelensky saying Kremlin’s demands are becoming more realistic, while Russian officials confirmed that the idea of a Swedish or Austrian-style neutrality was under discussion. Gazprom said it continues shipping gas to Europe via Ukraine, with daily volumes set at 95 million cubic meters, in line with customers' requests but down 13% from 109.6 million cubic meters on Tuesday, Reuters reported. Meanwhile, Norway’s Equinor has postponed maintenance work to boost supplies to the EU and the UK, which import 25% of their natural gas from the Nordic country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/16/opinions/putin-foreign-fighters-syria-africa-ukraine-fink/index.html </td>
   <td style="text-align:left;"> 2022-03-16 19:55:04 </td>
   <td style="text-align:left;"> Opinion: Putin is calling in favors from Syria and Africa. It's a dangerous move - CNN </td>
   <td style="text-align:left;"> Naureen Chowdhury Fink is the executive director of The Soufan Center. She previously served senior policy adviser on counterterrorism and sanctions at the United Kingdom's Mission to the United Nations.                                                                                                                                                                                                                                                    ,  (CNN)A quick glance of the military capabilities of Ukraine and Russia shows a David versus Goliath battle. On paper, Russia's armed forced forces have thousands more troops, weapons and vehicles -- with a staggering military budget to boot.                                                                                                                                                                                                             , On the ground it's a different story, where Russia has met fierce resistance from Ukraine's vastly outnumbered military. In the first two weeks of the invasion, Ukraine's President Volodymyr Zelensky's call for foreign volunteers to bolster his country's defense saw more than 20,000 people from 52 countries put their hands up, according to government officials.​                                                                                    , The influx of foreign fighters into Ukraine has been met with sympathy in many Western states, where citizens and even political leaders, have expressed support for those fighting Russia's invasion. Some leaders, such as United Kingdom Foreign Secretary Liz Truss, or Danish Prime Minister Mette Frederiksen, even encouraged civilians to travel.                                                                                                      , Not to be outdone, President Vladimir Putin last week also called for foreign reinforcements -- many of the applicants reportedly coming from the Middle East and Africa, where Russia has invested in bolstering governments and military actors, who are now in position to repay.                                                                                                                                                                           , Russia has called in favors from ally Syria -- where Putin's troops backed government forces in the country's long civil war -- claiming nearly 16,000 volunteers are ready to fight on their side.                                                                                                                                                                                                                                                            , And in Africa, Russia has sought to cultivate support in places like the Central African Republic, where Russian advisers and private military contractors have bolstered the authority of the government in Bangui.                                                                                                                                                                                                                                           , Add in widespread reports of the increased presence in Ukraine of the Wagner Group, a Russian private military company whose owner is reportedly close to Putin, and which is apparently offering starting salaries of $2,000 per month for all nationals (except Georgia), and the picture of foreign fighters in the war is going to get more complicated. And dangerous.                                                                                    , African states have been divided over Russia's invasion. During a historic vote earlier this month on Ukraine in the United Nations General Assembly, 24 African countries refrained from condemning Russia's invasion; 16 abstained, seven didn't vote at all and one voted against. For many states, longstanding relationships with Russia or historical commitments to the Non-Aligned Movement shape their response.                                      , Others see in Russia an anti-Western ally and in the case of Central African Republic for example, one that prevented a rebel onslaught. In Uganda, the President's son, Lt. Gen. Muhoozi Kainerugaba, widely rumored to be his successor, said: "The majority of mankind (that are non-white) support Russia's stand in Ukraine." For good measure, he added, "Putin is absolutely right!"                                                                    , It is notable that countries where the Wagner Group has been active -- including Mozambique, Central African Republic, Mali -- all abstained from voting against Russia at the UN. For some, fighting in Russia will provide an opportunity to challenge the post-colonial era dominated by the West; for others it will provide a valuable income and combat opportunities.                                                                                   , The experience of Libya however, has shown that the return of fighters with military experience has prompted instability and violence in the region.                                                                                                                                                                                                                                                                                                           , For over a decade, Russia has shielded Syria in the Security Council and flooded it with weapons, personnel, and operational support. Russia's longstanding support to Syrian President Bashar al-Assad allowed him a brutal testing ground for weapons, tactics and recruitment.                                                                                                                                                                              , In return, on the first day of the invasion, Putin reportedly called Assad who told him that, "Western nations bear responsibility for the chaos and bloodshed." It is unsurprising that Syrian volunteers are now being recruited, with US assessments indicating their experience in urban combat will be of particular value to Russia as it regroups for more assaults on Ukraine's cities.                                                                , Over the past decade, the term foreign fighters has conjured up images of another war in the Middle East, where nearly 40,000 people traveled to Syria and Iraq. The adversary for many was a brutal dictator; yet the ally was a UN-designated transnational terrorist group.                                                                                                                                                                                 , This is not that war. Russia's invasion of Ukraine has prompted the establishment of a Ukrainian Foreign Legion, under government control. Western interest is likely to remain high in supporting Ukrainian forces in fending off invasion and occupation. Statements from volunteers have overwhelmingly indicated interest in bolstering a sovereign democratic government in the face of unprovoked aggression.                                            , But should the current war morph into a longer-term insurgency, the scene for foreign fighters and supporters can change, with some sharpening ideological or political views or favoring extremist narratives.                                                                                                                                                                                                                                                , Moreover, in order to meet their obligations under Security Council counterterrorism resolutions, states have adopted measures, such as criminalizing travel to conflict zones or material support to terrorism -- without actually defining terrorism --  that can complicate the picture. It means there could be tensions between actions deemed permissible in conflict zones and what can be characterized as terrorism.                                  , As states confronted the challenges of travelers bound for Islamic State in Syria and Iraq, they unified around a set of sweeping and binding UN Security Council resolutions in order to address the phenomenon of what they termed foreign terrorist fighters -- those traveling with the intent to support a designated terrorist group.                                                                                                                    , In 2014 and 2017, the Security Council adopted two binding resolutions as states grappled with the prospect of foreigners traveling to conflict zones and returnees. These highlighted the need for a package of responses that included prosecution, rehabilitation, and reintegration. That terminology could further complicate the outlook for volunteer fighters in Ukraine.                                                                              , These measures were adopted when there was unparalleled international consensus about the status of ISIS and when terrorism was one topic where all five permanent members of the Council could agree, in large part. But now that these measures are on the books, there are risks individuals traveling to Ukraine could run afoul of them, or that the lack of clarity about some counterterrorism laws could endanger them in situations of armed conflict., While initial intentions from many traveling from the West have been overwhelmingly humanitarian and in support of a beleaguered sovereign, democratic government under attack, motivations can change over time. The influx of more diverse actors, could also cloud the legal minefield and prompt potential tensions between counterterrorism and humanitarian law.                                                                                         , Already Russia has indicated they would consider foreigners traveling to fight in Ukraine as mercenaries, and that they would not be considered combatants protected by international humanitarian law.                                                                                                                                                                                                                                                        , As long as volunteers are traveling to join the officially established foreign legion, and remain under responsible military command while in Ukraine, there may be some measures of legal protection. But individuals may be affected by exposure to atrocities, or recruited by groups with diverse ideological goals, particularly if they are not accepted into the foreign legion.                                                                        , Sympathizers abroad may grow increasingly frustrated with their own countries' responses and opt for more violent forms of political expression at home. During previous flows, returnees have not perpetrated harm in large numbers. But many will return battle-hardened with combat experience and new transnational networks that may be activated for other causes, and those that wish to do harm may be more capable of doing so.                       , But there are two things we can do now. States need to review their counterterrorism legislation and clarify when and where these do -- or don't -- apply with regard to Ukraine. With the fragmentation of consensus in the Security Council and the end of a post-9/11 era agreement on countering terrorism together, the Council may no longer be the place to determine what a collective international response looks like.                              , In the geopolitical fallout of the war in Ukraine, there will be an urgent need to reassess the roles and contributions of multilateral counterterrorism efforts -- like the vast bureaucratic architectures at the United Nations, Global Counterterrorism Forum and other intergovernmental bodies developed in the wake of the 9/11 era.                                                                                                                    , Nonetheless, the flow of volunteers to Ukraine and Russia, increases the need for international cooperation among all states to ensure the safety of their citizens -- and plan for their safe return.                                                                                                                                                                                                                                                         , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-03-16 19:51:00 </td>
   <td style="text-align:left;"> UK Gas Continues Rout, Hits 2-Week Low </td>
   <td style="text-align:left;"> UK natural gas prices slipped 5% to 260 pence a therm, a level not seen in two weeks, after holding to the flatline earlier in the session, as investors assessed positive cues from Russia-Ukraine talks. Ukraine’s President Zelensky said that the Kremlin’s demands are becoming more realistic, while Russian officials confirmed that the idea of a Swedish or Austrian-style neutrality was under discussion. Natural gas flows through the Yamal-Europe pipeline moved eastwards after earlier reports indicated flows were moving to Germany, while imports passing through Ukraine remained steady. Meanwhile, Prime Minister Boris Johnson is visiting oil and gas producing nations in the Arabian peninsula to discuss energy security. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/16/stocks-making-the-biggest-moves-premarket-nvidia-boeing-micron-and-others.html </td>
   <td style="text-align:left;"> 2022-03-16 19:50:21 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Nvidia, Boeing, Micron and others </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                                                                                                                                                                              , DiDi Global (DIDI), Alibaba (BABA), JD.com (JD), Pinduoduo (PDD) – China-based stocks listed in the U.S. are staging strong rallies in premarket trading, helped by state media reports that the Chinese government will take steps to support the markets and the economy, and that the U.S. and China are progressing toward an agreement on regulatory requirements for those companies. Didi surged 36.7% in the premarket, with Alibaba up 19.2%, JD.com rallying 21% and Pinduoduo soaring 32.5%., Nvidia (NVDA) – The graphics chipmaker's stock added 2.3% in the premarket after Wells Fargo added it to its "signature picks" list. The firm anticipates upbeat announcements from Nvidia at its upcoming investor day, and also said the recent market downdraft has helped create a favorable risk/reward profile.                                                                                                                                                                                  , Boeing (BA) – Boeing gained 2% in premarket trading after Baird declared the stock a "bullish fresh pick" following a recent sell-off and noted that 737 MAX deliveries to China are close to resuming.                                                                                                                                                                                                                                                                                                , Pfizer (PFE), BioNTech (BNTX) - Pfizer and partner BioNTech have asked the FDA to approve a second booster dose of their Covid-19 vaccine. A decision could come in time for an autumn vaccination campaign. BioNTech jumped 4.4% in premarket trading, while Pfizer rose 0.6%.                                                                                                                                                                                                                        , Micron Technology (MU) – Micron rallied 4.7% in the premarket following a Bernstein double upgrade to "outperform" from "underperform". Bernstein said the Ukraine conflict won't result in any significant memory chip supply or demand destruction, while also noting the recent sell-off in Micron and other semiconductor stocks.                                                                                                                                                                  , Spotify (SPOT) – The streaming services company signed a stadium and shirt sponsorship deal with Spanish soccer team FC Barcelona, with the Spotify brand on uniform shirts for the next four seasons. Spotify rose 2.6% in premarket action.                                                                                                                                                                                                                                                          , NortonLifeLock (NLOK) – NortonLifeLock's $8.6 billion deal to buy British cybersecurity rival Avast may get an in-depth probe by UK regulators, who say the deal raises competitive concerns. NortonLifeLock said it does not intend to submit any potential remedies for those concerns. Its stock slid 5.5% in the premarket.                                                                                                                                                                        , Lands' End (LE) – The apparel retailer missed estimates by 10 cents with quarterly earnings of 21 cents per share, while revenue also fell short of Street forecasts. Lands' End also gave a weaker-than-expected forecast as it faces increasing costs and continued supply chain challenges. Lands' End tumbled 9.5% in premarket trading.                                                                                                                                                           , Shoe Carnival (SCVL) – Shoe Carnival shares slid 3.3% in the premarket despite an upbeat quarterly report which saw it beat estimates on both the top and bottom lines. The shoe retailer issued a full-year revenue and profit forecast range that was largely – but not completely – above current Street forecasts. Shoe Carnival also announced a 29% dividend increase.                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kyrgyzstan/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-16 19:49:00 </td>
   <td style="text-align:left;"> Kyrgyzstan Inflation Rate at 10-Month Low </td>
   <td style="text-align:left;"> Kyrgyzstan’s annual inflation rate eased to 10.8 percent in February of 2022, from 11.2 percent in the previous month. It was the smallest increase in consumer prices since last April amid a slight slowdown in cost of food &amp; non-alcoholic beverages (12.1 percent vs 12.5 percent in January); in transportation costs (24.4 percent vs 24.7 percent); alcoholic beverages &amp; tobacco (12.4 percent vs 14.7 percent); and in health services (11.1 percent vs 13.0 percent). Meanwhile, prices rose faster in housing &amp; utilities (6.4 percent vs 6.2 percent); domestic utensils &amp; appliances (11.4 percent vs 10.2 percent); and clothing &amp; footwear (7.2 percent vs 6.8 percent). On a monthly basis, consumer prices edged up 0.7 percent, slowing from a 1.0 percent rise in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/house-price-index-yoy </td>
   <td style="text-align:left;"> 2022-03-16 19:44:19 </td>
   <td style="text-align:left;"> Irish Home Prices Rise the Most since 2015 </td>
   <td style="text-align:left;"> Residential property prices in Ireland surged 14.8 percent year-on-year in January of 2022, the largest increase since April of 2015 and following a downwardly revised 14.3 percent rise in the previous month. In Dublin, residential property prices advanced 13.3 percent in the year to January, while property prices outside Dublin were 16 percent higher. Overall, the national index is 3.3 percent lower than its highest level in 2007. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/croatia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-16 19:30:00 </td>
   <td style="text-align:left;"> Croatia Inflation Rate at 13-1/2-Year High </td>
   <td style="text-align:left;"> Croatia’s annual inflation rate rose for the eighth consecutive month to 6.3 percent in February of 2022, from 5.7 percent in the previous month. It was the highest rate since September of 2008, led by soaring prices of food &amp; non-alcoholic beverages (10 percent vs 9.4 percent in January); housing &amp; utilities (3.3 percent vs 2.7 percent); restaurants &amp; hotels (6.2 percent vs 4.7 percent); and alcoholic beverages and tobacco (6.4 percent vs 6.2 percent). On a monthly basis, consumer prices rose 0.9 percent, the most in 4 months, and advancing from a 0.3 percent uptick in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hungary/construction-output </td>
   <td style="text-align:left;"> 2022-03-16 19:30:00 </td>
   <td style="text-align:left;"> Hungary Construction Output Expands for 9th Straight Month </td>
   <td style="text-align:left;"> Hungary’s construction output rose 3.3 percent year-on-year in January of 2021, slowing sharply from a revised 29 percent jump in the previous month. It was the ninth consecutive month of growth in construction activity, although the softest in the sequence as base year effects faded. Output increased for civil engineering works (12.9 percent vs 24.8 percent in December) but contracted in building construction (-0.4 percent vs 32.7 percent). On a monthly basis, construction output fell by 6.3 percent, following a 5.4 percent increase in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/somalia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-16 19:29:00 </td>
   <td style="text-align:left;"> Somalia February Inflation Rate Slows to 6.45% </td>
   <td style="text-align:left;"> The annual inflation rate in Somalia eased to 6.45% in February of 2022, from a 2-1/2-year high of 6.84% in January, helped by another slump in prices of tobacco &amp; narcotics (-32.67% vs -27.61% in January), amid the normal volatility in prices for khat; and miscellaneous goods &amp; services (-9.10% vs -8.41%). At the same time, inflation slowed for clothing &amp; footwear (1.53% vs 2.91%); housing &amp; utilities (3.39% vs 4.50%); health (9.23% vs 13.45%) and transport (1.86% vs 2.08%). On the other hand, food prices continued to climb (12.65% vs 11.63%). On a monthly basis, consumer prices went up 0.55 percent, after decreasing 0.06 percent in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uranium </td>
   <td style="text-align:left;"> 2022-03-16 19:22:29 </td>
   <td style="text-align:left;"> Uranium Futures Slip from 11-Year High </td>
   <td style="text-align:left;"> Uranium futures slipped towards $55 a pound, easing from an 11-year high of $60.4 reached on March 10th, as signs of positive developments in Russia-Ukraine talks poured cold water on concerns over supplies. Kremlin officials said a neutral Ukraine with its own military could be compromised, while Ukraine’s President Zelensky said demands from Moscow were becoming more realistic, as talks resumed. Still, reports that the White House was mulling sanctioning Russian nuclear power supplier Rosatom, which is a major global supplier of fuel and technology, limited losses. The US nuclear energy sector produces 20% of the country's electricity, and relies on Russia for 16% of its imports. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/portugal/producer-prices-change </td>
   <td style="text-align:left;"> 2022-03-16 19:18:17 </td>
   <td style="text-align:left;"> Portugal February Producer Inflation Hits Record High </td>
   <td style="text-align:left;"> Producer prices in Portugal jumped 20.7 percent on year in February of 2022, accelerating from a downwardly revised 17.8 percent rise in the previous month. It was the highest inflation rate since available records began in January of 1991. Energy prices continued to soar at double-digit rates (60.9 percent vs 60.9 percent in the previous month). Also, prices accelerated for intermediate goods (19.2 percent vs 18.8 percent); capital goods (3.3 percent vs 2.9 percent) and consumer goods (6.8 percent vs 6.2 percent), particularly non-durable goods (7.1 percent vs 6.4 percent). On a monthly basis, producer prices rose by a record high of 2.7 percent, quickening from a downwardly revised 0.2 percent uptick in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-16 19:15:00 </td>
   <td style="text-align:left;"> Brent Crude Holds Below $100 </td>
   <td style="text-align:left;"> Brent crude futures steadied below $100 per barrel on Wednesday, the lowest since late February and after falling more than 11 in the previous two sessions, as diplomatic efforts between Russia and Ukraine showed every intention of continuing. Ukrainian President Volodymyr Zelensky said in a video address on Wednesday that the positions of both sides at the peace talks were sounding more realistic but more time was needed. Oil prices were also pressured recently by concerns of a slowing China demand, after a new wave of Covid infections triggered fresh lockdowns in the world’s second-largest oil consumer. Meanwhile, EIA data showed US crude inventories rose by 4.345 million barrels to 415.9 million barrels last week, while gasoline stocks declined by 3.616 million barrels. Brent futures now trade about 27% below a recent 14-year high of $139.13 reached last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-16 19:12:00 </td>
   <td style="text-align:left;"> Oil Prices Steady after 2-Day Selloff </td>
   <td style="text-align:left;"> WTI crude futures stabilized around $96 per barrel on Wednesday, the lowest since late February and after falling more than 11.5% in the previous two sessions, as diplomatic efforts between Russia and Ukraine showed every intention of continuing. Ukrainian President Volodymyr Zelensky said in a video address on Wednesday that the positions of both sides at the peace talks were sounding more realistic but more time was needed. Oil prices were also pressured recently by concerns of a slowing China demand, after a new wave of Covid infections triggered fresh lockdowns in the world’s second-largest oil consumer. Meanwhile, EIA data showed US crude inventories rose by 4.345 million barrels to 415.9 million barrels last week, while gasoline stocks declined by 3.616 million barrels. WTI crude futures now trade about 25% below a recent 14-year high of $130.5 reached last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/itx:sm </td>
   <td style="text-align:left;"> 2022-03-16 19:09:40 </td>
   <td style="text-align:left;"> Inditex earnings meet market expectations at 0.38 EUR </td>
   <td style="text-align:left;"> Inditex (ITX) released earnings per share at 0.38 EUR, in line with market expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/mortgage-applications </td>
   <td style="text-align:left;"> 2022-03-16 19:09:00 </td>
   <td style="text-align:left;"> US Mortgage Applications Fall Again: MBA </td>
   <td style="text-align:left;"> Mortgage applications in the US fell 1.2% in the week ended March 11th, following an 8.5% jump in the previous period which was the first increase in five weeks, as mortgage rates surged to the highest in 3 years. Applications to refinance a home loan declined 2.8% while those to purchase a home edged up 0.7%. Meanwhile, the average fixed 30-year mortgage rate increased to 4.27%, the highest since May of 2019, after falling for the first time this year to 4.09% in the previous week. “Mortgage rates continue to be volatile due to the significant uncertainty regarding Federal Reserve policy and the situation in Ukraine. Investors are weighing the impacts of rapidly increasing inflation in the U.S. and many other parts of the world against the potential for a slowdown in economic growth due to a renewed bout of supply-chain constraints” said Joel Kan, an MBA economist. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-03-16 19:08:00 </td>
   <td style="text-align:left;"> South Africa Retail Sales Growth Tops Forecasts </td>
   <td style="text-align:left;"> South Africa’s retail trade surged by 7.7 percent from a year earlier in January of 2022, up from an upwardly revised 3.2 percent rise in the previous month and above market estimates of a 4.9 percent gain. It was the fifth straight month of increases in retail activity and at the fastest pace since last June. Strong growth was recorded in sales of food, beverages &amp; tobacco (70.9 percent vs 1.9 percent in December) and textiles, clothing, footwear and leather goods (17.4 percent vs 16.4 percent). On a monthly basis, retail trade increased 1.5 percent, after an upwardly revised 1.7 percent rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/current-account </td>
   <td style="text-align:left;"> 2022-03-16 18:56:44 </td>
   <td style="text-align:left;"> German Current Account Surplus Shrinks in January </td>
   <td style="text-align:left;"> Germany's current account surplus narrowed to EUR 11 billion in January of 2022 from EUR 20.4 billion in the corresponding month of the previous year. The goods surplus shrank to EUR 4.54 billion from EUR 14.73 billion and the services account switched to a EUR 0.31 billion gap from a EUR 0.90 billion surplus. Meanwhile, the primary income surplus winded to EUR 12.82 billion from EUR 11 billion and secondary income deficit fell to EUR 6.06 billion from EUR 6.24 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-16 18:50:00 </td>
   <td style="text-align:left;"> South Africa Government Bond 10Y at Near 2-Week Low </td>
   <td style="text-align:left;"> South Africa 10 Year Government Bond Yield was at 9.6%, its lowest since March 3rd, as investors remained concerned about the adverse impact of the war in Ukraine on global growth despite China's promise to roll out more economic stimulus, while also assessing looming interest rate hikes. The Federal Reserve is expected to kick off a tightening cycle on Wednesday after US inflation hit a fresh 40-year high of 7.9% in February. Locally, investors are betting the South African Reserve Bank could have to respond to price pressures fueled by the rising oil price with another 25-basis-point hike at the next monetary policy meeting on March 24th. This is also a major threat to South Africa's fragile economic recovery along with domestic structural issues, in particular recurrent load-shedding across the country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/montenegro/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-16 18:48:00 </td>
   <td style="text-align:left;"> Montenegro Inflation Rate at Over 13-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Montenegro accelerated for the fifth straight month to 6.7% in February of 2022, from 5.7% in the previous month. It was the highest reading since December of 2008, mainly on account of prices of food &amp; non-alcoholic beverages (13.1% vs 11.3%) and transport (12.7% vs 10.5%). On a monthly basis, consumer prices were up 1.5%, after rising 1.3% in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60751080?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-16 18:46:13 </td>
   <td style="text-align:left;"> Lithuania threatens to stop using Russian oil and gas </td>
   <td style="text-align:left;"> Lithuania's president said the country was willing to stop Russian oil and gas imports, in the latest sign of how some EU nations plan to step up penalties on Moscow for invading Ukraine.                                            , "It would create some problems, but those problems would not be critical," President Gitanas Nauseda said.                                                                                                                             , Lithuania got about 63% of its oil imports from Russia in 2019.                                                                                                                                                                        , President Nauseda said that figure had now shrunk after its oil refinery stopped buying Russian crude oil.                                                                                                                             , Western countries hit Moscow with sanctions late last month over Russia's invasion of Ukraine, and the US has banned imports of Russian energy, while the UK is phasing out Russian oil imports.                                       , The EU, which gets roughly 40% of its gas from Russia, has said it will cut reliance on this fuel source by two thirds within a year.                                                                                                  , When it comes to Lithuania, President Nauseda told the BBC: "Of course, it depends on time: How long we would need to adjust [to cutting Russian imports].                                                                             , "But I would say it in other words: We are better prepared for such a cut from Russian energy resources than many other countries in the EU."                                                                                          , On 3 March, the owner of Lithuania's Mazeikiai refinery, Orlen Lietuva, said it had agreed a deal with Saudi Aramco for five additional tankers of the commodity taken out of the North Sea.                                           , That, it said, would ensure alternative supplies for Lithuania, Poland and the Czech Republic.                                                                                                                                         , Four days later, the company said that given the situation in Ukraine, it was "prepared for any scenario, including the complete suspension of supplies from the eastern direction."                                                   , The warning from Lithuania's president shows how some countries are willing to put further pressure on Russia's economy.                                                                                                               , Aside from oil, Lithuania has worked, over the last decade, to reduce its dependence on Russia for natural gas - including by opening its own LNG terminal called Independence.                                                        , Electricity independence, though, is still a work in progress, President Nauseda said.                                                                                                                                                 , "We still are connected with the so-called Brell system of the former Soviet Union and this connection does not allow a switch to different [European] systems [at present].                                                           , However, he said the process switching Lithuania away from Brell "will be completed in 2025".                                                                                                                                          , "Now we will try to speed up this process to disconnect faster," he added.                                                                                                                                                             , President Nauseda also acknowledged ongoing concern, including from Ukraine's president, Volodymyr Zelensky, about whether Baltic nations - including Lithuania - could be the next target for Russian President Vladimir Putin.       , "Unfortunately this is true. Since Putin declared that the largest tragedy of the 20th Century was the collapse of the Soviet Union, he had in mind the Baltic countries, because they are a consistent part of the Soviet Union, too. , "So, this is a threat. We never had illusions that we will be forgotten," he said.                                                                                                                                                     , But he said the country had increased defence spending including on military equipment. And he believes in the Nato military alliance.                                                                                                 , "I really believe in the ability of Nato to work effectively as a collective defence organisation," he said. "I see also, this solidarity in action, with additional deployment and military capabilities on the ground.               , "And this is probably the best proof for me that Nato is working," he said.                                                                                                                                                            , The origins of a notorious street gang that arose in Birmingham                                                                                                                                                                        , Stock car racing is raw and unfiltered - who will finish the season on a high?                                                                                                                                                         , 'The Boss' Sasha Banks on her love for wrestling and what it means to her                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-03-17 08:50:45 UTC +8

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
   <td style="text-align:left;"> 2022-03-17 08:50:25 </td>
   <td style="text-align:left;"> $SPY Clearly, I&amp;#39;ve been wrong since December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:50:19 </td>
   <td style="text-align:left;"> $SPY I have three baby mommas.  Every day is triple witching day up in this house mfers.  No cap.  💯🙊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:50:11 </td>
   <td style="text-align:left;"> $SPY $KWEB up big, $Yang down big today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:49:56 </td>
   <td style="text-align:left;"> $SPY just came across my desk… st pattys day apparently not priced in, more pain for bears ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:49:53 </td>
   <td style="text-align:left;"> $SPY cramer says when Market reaches all time highs again then you can buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:49:45 </td>
   <td style="text-align:left;"> $SPY our lord is very handsome... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:49:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX  Technical Analysis from one of my favorite follows 

https://youtu.be/Xqrp1Dcv4tE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:49:35 </td>
   <td style="text-align:left;"> $SPY Stonks only go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:49:20 </td>
   <td style="text-align:left;"> $SPY futes ripping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:49:05 </td>
   <td style="text-align:left;"> $SPY Can you imagine not ignoring the horrific macro issues and not buying into what is clearly not a trap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:48:57 </td>
   <td style="text-align:left;"> $SPY you know we heading south when the wife deletes the Amazon app </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:48:18 </td>
   <td style="text-align:left;"> $spy 
 
Decent market growth conditions, Biden&amp;#39;s doing an amazing job slamdunking crude oil prices. China is helping out Ukraine.  
 
This 👏 is 👏not👏a 👏dead 👏cat👏bounce. IT&amp;#39;S A BULL RUN!!! 
 
Also please report any bears for spreading disinformation misinformation about market manipulation of any kind. Call pumping is an ultra-right white nationalist conspiracy theory. VIX is a Russian 5th columnist and Apple is helping brave soldiers/volunteers fight back the Russians. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:48:13 </td>
   <td style="text-align:left;"> $SPY fed going for .5 next and 6.. yes SIX more interest rate hikes this year… GDP 2.8% 2022 and expected 2.2% in beginning of 2023. Bulls; they’re literally telling you this is bad if you’re smart, but to the dummies they’re saying “yeah economy is strong”.. you’ve been handed red flags.. either you’re delusional or you’re getting out before EOW. 🚩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:48:06 </td>
   <td style="text-align:left;"> $SPY too much on sale in the world for the SPY to get bid up much further. Big money looking for greaner pastures. Pray for flat. Once the 2Y crosses the 10Y run for your lives. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:59 </td>
   <td style="text-align:left;"> $SPY good night 💤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:58 </td>
   <td style="text-align:left;"> $SPY can’t wait for 2am when the mysterious mfs come and spread rumors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:53 </td>
   <td style="text-align:left;"> $SPY cramer said not to buy yet..wait till it goes much higher then buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:45 </td>
   <td style="text-align:left;"> $SPY Dark Pool Levels from today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:45 </td>
   <td style="text-align:left;"> $SPY just look how equal weight spy is never allowed to break under 6000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:39 </td>
   <td style="text-align:left;"> $SPY I can’t touch this knowing it’s falling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:14 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ll be convinced when all the moving averages are reclaimed and defended </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:13 </td>
   <td style="text-align:left;"> $SPY Bears are mad at charts so let me just show you cry baby bears something fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:10 </td>
   <td style="text-align:left;"> $SPY 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:47:09 </td>
   <td style="text-align:left;"> $SPY  
 
&amp;quot;We have tools&amp;quot; really means, &amp;quot;Look at the inflation rate.  We&amp;#39;ve used up all of our tools now.  That&amp;#39;s why we&amp;#39;re telling you that we have them in the first place.  Because we don&amp;#39;t.  Otherwise, we&amp;#39;d be using them.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:46:54 </td>
   <td style="text-align:left;"> $SPY stocktwit lagging, isit just me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:46:47 </td>
   <td style="text-align:left;"> The buy signals when matched up with my demand zones never fail! Today as price dropped into 4 hour demand, $SPY was SCREAMING buy! The 3/18 430C I alerted at 2.04 closed near 7.00! Unreal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:46:39 </td>
   <td style="text-align:left;"> $SPY Russia is about 8 days from losing ground they have won from Ukraine. With what has been approved by US now the next logical answer is for Russia to deploy a battlefield Nuke. Likely dead center Kyiv. God protect these people it’s coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:46:34 </td>
   <td style="text-align:left;"> $SPY I was building a portfolio in March 2020 and I got sick of it losing so I traded it all for puts on March 20, 2020.  True story.  I was doing the right thing and got impatient.  I come here to cope with my pain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:46:17 </td>
   <td style="text-align:left;"> $SPY I feel sorry for people in those damn target date 401k funds or in other funds they can&amp;#39;t buy $SARK in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:46:08 </td>
   <td style="text-align:left;"> $SPY quad witching priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:46:03 </td>
   <td style="text-align:left;"> $SPY $UVXY $AAPL $QQQ $TSLA 

The only thing worse than war is complacency. Investors &amp;amp; civilians seem to already be desensitized to the horrors that are going on in Ukraine. Stubborn bulls become low quality steak, remember that… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:45:38 </td>
   <td style="text-align:left;"> $SPY 
Today order flow. Bull trap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:45:37 </td>
   <td style="text-align:left;"> $SPY cough bagholder of puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:45:16 </td>
   <td style="text-align:left;"> $SPY Data driven. We have tools. Soft landing. 

Idk, J. Seems like the data is in and you haven’t used those tools, yet. And nothing about any of this has been soft. 

How long can the can get kicked down the road? 

You want me to trust this institution? I think not. 

Might as well have kept the rate at zero. .25 is a joke that isn’t even funny, anymore. 

Bernanke 2.0 and it disgusts me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:53 </td>
   <td style="text-align:left;"> $SPY cramer called the bottom at 425 remember? Then it hit 410.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:49 </td>
   <td style="text-align:left;"> $SPY this isn&amp;#39;t going to end well. 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:46 </td>
   <td style="text-align:left;"> $SPY drop to $432 for a cool off then we rip. This could get violent if we break and hold $440 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:40 </td>
   <td style="text-align:left;"> $UPST big movements today, quick trigger. 

$SPY is more volatile than ever….

Yet again, I buy my own alerts…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:34 </td>
   <td style="text-align:left;"> $SPY Look at every previous quad witching day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:32 </td>
   <td style="text-align:left;"> $XLE $USO $QQQ $SPY Gas stimmies for the EV driving Californians...😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:24 </td>
   <td style="text-align:left;"> $SPY Cramer was bullish and is never wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:12 </td>
   <td style="text-align:left;"> $SPY Wait is Cramer calling the BOTTOM here. Oh fck! Lol Even more validation for our thesis that this is simply a BEAR RALLY due to extreme OVERSOLD conditions. Wow!!!!!

Which tag do we use because we’re bullish for the next few days - short term, but bearish over the next several weeks out. I guess to keep it uniform we’ll use the bullish tag since that’s the NOW. :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:10 </td>
   <td style="text-align:left;"> $SPY One thing I&amp;#39;ve learned is the market likes certainty when it can obtain it.  Not trying to predict the next move, but I&amp;#39;ll be surprised if an end-of-the-day rally will be enough to call a bottom.  Especially when the price had already gapped up early.  The timing of the action is suspect as well.  Probably 99% of the market had already guessed the rate hike would be 25 bps weeks ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:03 </td>
   <td style="text-align:left;"> $SPY Big green candle for St. Patrick&amp;#39;s Day tomorrow? Slainte! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:44:03 </td>
   <td style="text-align:left;"> $SPY damnnnn those bears got rekt hard today. i was about to drop 30k in puts too lmaoooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:52 </td>
   <td style="text-align:left;"> $SPY  
 
🍦 I got into Biden&amp;#39;s ice cream cabinet... said do not touch 🥴🥴🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:48 </td>
   <td style="text-align:left;"> $SPY someone tell me what inflow/outflow was for today and I give you something good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:48 </td>
   <td style="text-align:left;"> $SPY I think I&amp;#39;m going to genuinely write an algo to query and natural language process StockTwits activity and buy the exact opposite of what everything is saying.

A good portion of the people here are:
- Scurred bears
- Overhyped bulls
- People on margin

I have the feeling if I just aggregated and inversed the live sentiment, it would make money.

What do ya&amp;#39;ll think. Should I give it a whirl and huck 10k at it and see what happens? Lol.

(Been writing software over 20 years and already have API keys for ST) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:41 </td>
   <td style="text-align:left;"> $SPY spam this chat with bullish tags to the fvcker finally goes red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:39 </td>
   <td style="text-align:left;"> $SPY It’s difficult to switch sides when you know you are right with actual data but things aren’t going your way. 

But it is more difficult waiting to be right rather than following the side that’s going pay you today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:38 </td>
   <td style="text-align:left;"> $SPY the day after fed meeting is always fucked ⏩ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:29 </td>
   <td style="text-align:left;"> $SPY All technical indicators still not showing bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:28 </td>
   <td style="text-align:left;"> $SPY basically if you bought when they knifed oil that was the play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:24 </td>
   <td style="text-align:left;"> $SPY talk radio was pumping the market while it was falling after the rate hike was announced. Went red and they were talking about how up it was. Then 30 minutes later it magically made a new high. Rigged market no doubt. Just ride the wave. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:21 </td>
   <td style="text-align:left;"> $SPY I mean I hate to bring him up; but he is still the oracle of the markets... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:43:13 </td>
   <td style="text-align:left;"> $SPY Chris Cuomo just spotted at NY tattoo parlor…Naked….having tattoo of Don Lemon removed from his ass….NO MASK…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:42:50 </td>
   <td style="text-align:left;"> $SPY Posting bullish to jinx it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:42:20 </td>
   <td style="text-align:left;"> $SPY cute how all the fang stocks chart are almost identical today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:42:13 </td>
   <td style="text-align:left;"> $SPY $ES_F Long $SPY $ES_F from 4,351 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:42:08 </td>
   <td style="text-align:left;"> $SPY wait for the show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:41:41 </td>
   <td style="text-align:left;"> $UVXY $SPY $SQQQ $VXX $SPXS  
 
Saudi tries to skip USD in Oil sales. This isn&amp;#39;t a good sign for US economy. 
 
https://www.wsj.com/articles/saudi-arabia-considers-accepting-yuan-instead-of-dollars-for-chinese-oil-sales-11647351541 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:41:39 </td>
   <td style="text-align:left;"> $SPY  bearish tags are passe now but give it a few weeks, they&amp;#39;ll be back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:41:38 </td>
   <td style="text-align:left;"> $SPY Bonds are talking if anyone is listening. The bears are still hungry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:41:37 </td>
   <td style="text-align:left;"> $SPY Still up trending </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:41:30 </td>
   <td style="text-align:left;"> $SPY we have to break $440 tomorrow, if that happens, bears better look out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:41:27 </td>
   <td style="text-align:left;"> $SPY Keep buying the dip junk biden market gonna have vix up at these levels on the regular </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:41:24 </td>
   <td style="text-align:left;"> $SPY still see a downtrend this year but let’s at least let this go up till the end of April 💢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:41:17 </td>
   <td style="text-align:left;"> $SPY 3% rip because the Fed only raised interest rates by.25%.
OK 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:41:00 </td>
   <td style="text-align:left;"> $SPY join the bull side,

Are you still looking to even on your bear side or praying for market crash, lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:40:43 </td>
   <td style="text-align:left;"> $SPY crude oil volatility also getting crushed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:40:40 </td>
   <td style="text-align:left;"> $SPY putin keeps escalating. Killing people in a bread lines bombing a theatre with children inside. He keeps it up theres gotta be a red line somewhere- then—-BOOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:40:18 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m bullish. 94% of the posts here are bullish.

99.6% chance of going down tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:40:17 </td>
   <td style="text-align:left;"> $SPY spoiler alert: there are no negotiations happening. Stop sending Zelinsky mofo money Biden you dumbfuk. Keep the money in America if you’re robbing US taxpayers so I can feel good about it.

https://twitter.com/zerohedge/status/1504227189151178756?s=20&amp;amp;t=UG3XClPoYMHw_iw0c2LsrQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:40:12 </td>
   <td style="text-align:left;"> $SPY 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:40:11 </td>
   <td style="text-align:left;"> $SPY I was so close to getting the house back for me and my wife and her new boyfriend…but I took a short position here at $410 and Diamond handed it and now Margin is calling me.

I threw my phone away and deleted my portfolio, good luck getting your money back ETrade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:40:10 </td>
   <td style="text-align:left;"> $SPY vix futures are up and vix close above 50 dma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:40:10 </td>
   <td style="text-align:left;"> $BTC.X $SPY @StockLorded this guy is still here? Every post he makes he&amp;#39;s wrong.. then he will justify his idiotic posts by saying next week... 🤔🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:39:44 </td>
   <td style="text-align:left;"> $SPY lots of puts at fridays 440 😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:39:27 </td>
   <td style="text-align:left;"> $SPY Vix still not dead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:39:23 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA $SQQQ  https://www.bloomberg.com/news/articles/2022-03-16/tesla-halts-bond-sale-backed-by-auto-leases-amid-market-turmoil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:39:16 </td>
   <td style="text-align:left;"> $SPY 

If you are wondering about the strength of the consumer you really have to listen closely to the CEOs of the homebuilders and airlines.  It speaks volumes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:39:01 </td>
   <td style="text-align:left;"> $SPY hard to believe this was at 411 at open yesterday...the FED is truly amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:38:55 </td>
   <td style="text-align:left;"> $SPY The “Death Cross” doesn’t even matter lol. All about the FED. Powell was hawkish but a lot was “priced in”. Now, we’re in a touchy area now because we still have potential for WW3 which isn’t going away anytime soon, very little growth, and inflation running rampant. Very fine line the FED is walking by hiking aggressively in a very low growth environment and inflation running hot. 

Don’t take off the table a surprise hike greater then 0.25+ basis points to initiate the “Waterfall” leg below @ 400 or WW3. Still not convinced this is the BOTTOM. So far we are going to consider this move up over the coming days an extended BEAR RALLY until we can BREAK @ 458. That’s our line in the sand because it was the same line in the sand during FED liftoff in 2018. 

So that said bullish for the next few days and will be watching for REJECTION @ 446 and @ 458. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:38:52 </td>
   <td style="text-align:left;"> The #Fed Is Looking For Tighter Financial Conditions; Good Luck Stocks $QQQ $SPY $SPX https://talkmarkets.com/content/bonds/the-fed-is-looking-for-tighter-financial-conditions-good-luck-stocks?post=348234 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:38:46 </td>
   <td style="text-align:left;"> $SPY Cramer justify his word that “Market has bottom” and this is the time to buy 🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:38:44 </td>
   <td style="text-align:left;"> $SPY im putting long money in the glory hole and forgetting about it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:38:35 </td>
   <td style="text-align:left;"> $SPY face rip to 445 and then the big finale. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:38:05 </td>
   <td style="text-align:left;"> $SPY is trading Forex this crazy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:38:01 </td>
   <td style="text-align:left;"> $SPY Let them pump it further. The bigger the rise the harder it will fall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:38:00 </td>
   <td style="text-align:left;"> Although the technical rating is bad, $SPY does present a nice setup opportunity. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:37:54 </td>
   <td style="text-align:left;"> $SPY if this is end of bear market then too bad man I didn&amp;#39;t collect enough discounts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:37:38 </td>
   <td style="text-align:left;"> $SPY now we know why dark pools have not sold off. In fact the opposite. Lots of sidelined cash getting less valuable with inflation dying to jump in at the first sign of recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:37:23 </td>
   <td style="text-align:left;"> $HSI-HKG (Hang-Seng) The Index should be providing a very nice timing to buy World Indices again. Here is the Weekly chart from 3/06 to member&amp;#39;s at elliottwave-forecast.com, showing the future path, and buying area. #elliottwave #trading $SPX $SPY $ES_F $DAX $FTSE $HSI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:37:18 </td>
   <td style="text-align:left;"> $SPY $QQQ 

A bit of trivia: in both 2000 and 2008 crashes, the actual real bottom was not realized until the next year, 2001 and 2009. Of course, during the courses, there were many days of -3% to +3% and vice versa. Look them up. 
The knowledge may save your portfolio. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:37:16 </td>
   <td style="text-align:left;"> $SPY the bears here disgust me, it&amp;#39;s like loser giving fairwell speech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:37:16 </td>
   <td style="text-align:left;"> $SPY 🔥 https://youtu.be/zykZDiH_i78 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:37:03 </td>
   <td style="text-align:left;"> $SPY i ever see a mf from Bloomberg in the street they getting hit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:37:03 </td>
   <td style="text-align:left;"> $SPY ok b ok. Need my 500k back though last 3 months. @torrotrader </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:36:48 </td>
   <td style="text-align:left;"> $SPY The one thing that no one on Stocktwits has the balls to say is “this is financial advice”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:36:43 </td>
   <td style="text-align:left;"> $SPY  it takes over 3 weeks of unprovoked invasion shelling &amp;amp; war crimes by Paranoid Putin for the United Nations to issue cease-and-desist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:36:30 </td>
   <td style="text-align:left;"> $SPY I’m gonna do sit-ups till I poop myself! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:36:19 </td>
   <td style="text-align:left;"> $SPY CNBC was in full pump mode today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:49 </td>
   <td style="text-align:left;"> $SPY inflation is transitory only when perceived from the notion that we are expected to get MOAR of it... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:46 </td>
   <td style="text-align:left;"> $SPY Still bearish until it clears 441.20.  Gut telling me they are going to take that out though.  No position after playing today wrong.  Waiting to see what happens. 400 and even 385 are still very possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:30 </td>
   <td style="text-align:left;"> $SPY bought puts at the close today. Gonna pay big by Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA  this hands down has to be dumbest rally I&amp;#39;ve seen in along time. Hawkish AF, Powell  says economy is strong, if that&amp;#39;s the case why are they raising rates? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:28 </td>
   <td style="text-align:left;"> $QQQ $SPY It&amp;#39;s just so funny when the market is up we only see bulls posts or vice versa. I think this forum is just being used as a place for pissing contest. Nothing more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:20 </td>
   <td style="text-align:left;"> $SPY Nothing feals better then a daily Wedgie break. Luv dem Wedgies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:18 </td>
   <td style="text-align:left;"> $SPY 

At this point, if you are being biased to one side then you are going leave lots of money on the table like some of you did today. 

Are you going leave / lose money on the table for your pride and ego or are you going to follow the money and get paid both ways?

I remember someone making 100k-500k a day because he wasn’t biased to either side — he was only biased to what paid him well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:16 </td>
   <td style="text-align:left;"> $SPY holding my /es futures puts into next week.  Closed 2 outs on the big dip today because they were in the green. Still holding 2 more. Will trade a futes contract if I need to hedge. But staying outta the market tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:11 </td>
   <td style="text-align:left;"> $SPY sniper entry the other night oh what’s next!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:05 </td>
   <td style="text-align:left;"> $SOFI RIP Sofia. Hashtag will be trending by the AM. 📉📉📉🩸 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:05 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ does anyone have any ideas what happens next? Dash crash then dash before the closing bell. It seems a little too rosy after rates went up war looming and quad witching day around the corner. I don’t feel confident this is the end of the bear market, call me a pessimist 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:35:02 </td>
   <td style="text-align:left;"> $SPY Yup, @OldFngGuy is @sonicmerlin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:34:52 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:34:45 </td>
   <td style="text-align:left;"> $SPY 🔥😏 take advantage of volatility dump. It always pays. We will see VIX spike above 30, maybe into 40s, 50s faster than you think - geopolitical fun just started. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:34:32 </td>
   <td style="text-align:left;"> $SPY Wherez @MikeTython yaz? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:34:28 </td>
   <td style="text-align:left;"> $UPST New bagholders emerged today here. Bears would $SPY at the market tomorrow after digesting the long lasting effect of rate hikes 👇🏽👇🏽👇🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:34:23 </td>
   <td style="text-align:left;"> $SPY +4.68 in 3 trading days totally normal :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:34:08 </td>
   <td style="text-align:left;"> $SPY Run to @ 446 then @ 458. Watch for REJECTION at both levels. “Weekly Chart” confirms a move higher over the next 1-2 weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:34:00 </td>
   <td style="text-align:left;"> $SPY I bought one put option for every time Powell mentioned tools in his presser today. Forgot to post about that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:33:36 </td>
   <td style="text-align:left;"> $SPY according to McDonald&amp;#39;s arching chart, china is the next British power $baba

Get ready to learn English, kids </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:33:32 </td>
   <td style="text-align:left;"> $SPY when all this begun. 5% up and going. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:33:16 </td>
   <td style="text-align:left;"> $SPY Lol &amp;#39;traderunlimited pro&amp;#39; &amp;#39;nailed it today&amp;#39;

Everyone a genius today eh.  Where were you timid mutts Monday?

dErP i cAuGhT 1% of the gigantic two day rip i&amp;#39;M a TrDeR nOw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:33:14 </td>
   <td style="text-align:left;"> $SPY whether it’s Powell talking..CPI..the market always reacts a day later like a idiot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:33:14 </td>
   <td style="text-align:left;"> $SPY Cramer called the bottom lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:33:12 </td>
   <td style="text-align:left;"> $spy can’t even short futures when there’s an unfilled gap at 13999 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:33:06 </td>
   <td style="text-align:left;"> $SPY relax guys. Powell has a lot of tools. Don&amp;#39;t know what that means, but he does. Maybe he is going into construction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:33:05 </td>
   <td style="text-align:left;"> $SPY the 2Y almost hit 2 today, the 10Y is at 2.1. How about that death Cross. It&amp;#39;s so fake and everyone knows it. Just get it over with already. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:33:00 </td>
   <td style="text-align:left;"> $SPY Cramer told me to buy, buy, BUY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:32:58 </td>
   <td style="text-align:left;"> $SPY So let’s get this straight, we are now supplying Ukraine with weapons to be used against Russia, we are raising rates aggressively, we are lowering earnings estimates, admitting inflation is way ahead of the Fed, have massive PE ratios and you want me to buy stocks because you unwound a shitload of puts on a witching week?….no thanks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:32:16 </td>
   <td style="text-align:left;"> $SPY fighting with inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:32:12 </td>
   <td style="text-align:left;"> $SPY SPY 2022-03-16 Options Analysis Video: 
https://www.youtube.com/watch?v=Bh158btkqk8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:32:12 </td>
   <td style="text-align:left;"> $SPY Bulls, so McDonalds does not offer a work from home option.  Bull &amp;quot;investors&amp;quot; who will breaking even in a decade or so should take note. Don&amp;#39;t shoot the messenger, I heard it from Bull who heard it from Ron aka&amp;quot;Ronnie&amp;quot; aka &amp;quot;Ron Daddy&amp;quot; aka &amp;quot;as$ clown&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:32:04 </td>
   <td style="text-align:left;"> $NASDAQ $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:32:02 </td>
   <td style="text-align:left;"> $SPY You have seen just how quickly the bulls can take back control. In less than two days we are back to breakthrough levels and on to all time highs with just a few more bullish trading days. The Fed is neutral right now. I would not count their position to be on either side. They rather have inflation over a recession. Trade wisely 🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:31:43 </td>
   <td style="text-align:left;"> Reducing my short position. Weekly charts are indicating a potential bull run 🐂📈. I’m going to have to accept I may be wrong that the correction will continue.  By the market close of Friday we’ll have a more concrete picture. Be ready for bull trap 🪤 regardless. $SPY $DJIA $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:31:42 </td>
   <td style="text-align:left;"> $SPY JPOW has such a gentle, placid touch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:31:39 </td>
   <td style="text-align:left;"> $SPY you guys think Putin will be cool with us getting back to aths with his country heavily sanctioned and shut down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:31:36 </td>
   <td style="text-align:left;"> $SPY a bag of chicken tenders from the grocery store for $14 or 20 piece McNuggets for $5 is the daily struggle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:31:25 </td>
   <td style="text-align:left;"> Make time for people who actually put an effort in being in your life not people who tell you one thing and do another actions speak louder than words $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:31:23 </td>
   <td style="text-align:left;"> $SPY After the Russia loses to Ukraine and parts of it will be partitioned, I hope Germany won&amp;#39;t be a pain in the ass and will let Poland keep Kaliningrad. In my opinion, Poland deserves it more but I do understand Germany has more heritage there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:31:15 </td>
   <td style="text-align:left;"> $SPY STRONG DOLLAR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:31:13 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:31:06 </td>
   <td style="text-align:left;"> $SPY $ASTS SPY will be higher tomorrow, so should $ASTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:30:45 </td>
   <td style="text-align:left;"> $SPY Idiot bears like me and many of the “smart people” here calling for a crash until to see this rip to $435 EOD. 

All it shows that no matter what — you can be severely wrong even if your facts are there. 

It also indicates it can be awhile until reality hits people that things are bad. Don’t lose money waiting for people to realize the truth that things are bad. 

In fact, Biden and Jpow laughed at bear’s faces like this today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:30:40 </td>
   <td style="text-align:left;"> $LEN $SPY

No position.  What a surprise that Home Builders are rocking and rolling when there are probably four or five buyers for every home actually for sale. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:30:17 </td>
   <td style="text-align:left;"> $SPY quad witching ?? friday ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:30:15 </td>
   <td style="text-align:left;"> $SPY  
 
I don&amp;#39;t know which is more insane: 
 
Ten dollars, in a single day, or 
Bulls here really expecting that to hold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:30:07 </td>
   <td style="text-align:left;"> $SPY @sonicmerlin China rally part 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:29:48 </td>
   <td style="text-align:left;"> $SPY bullshiit Chinese stocks will make you go broke $BABA $DIDI remember never invest only trade chinese </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:29:26 </td>
   <td style="text-align:left;"> $SPY Gonna be a fun time bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:29:24 </td>
   <td style="text-align:left;"> $SPY $QQQ that bear trap after the FOMC was one of the most brutal I’ve seen, made my hedges run wild, so can only imagine net bears… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:29:19 </td>
   <td style="text-align:left;"> $SPY $TSLA I tried warning Elon worshippers that Musk was a deep state puppet and all that space crap was just CGI animation to build his persona to be bigger then life.But I&amp;#39;m just a conspiracy theory hack. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:29:07 </td>
   <td style="text-align:left;"> $SPY soon McDonald’s will be the only affordable food </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:28:47 </td>
   <td style="text-align:left;"> $SPY damn congrats to whoever played  chinese stocks today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:28:24 </td>
   <td style="text-align:left;"> $SPY Every analyst knows this is crashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:28:09 </td>
   <td style="text-align:left;"> $SPY $QQQ what happened today is simple too much cash on the sidelines and no sellers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:28:06 </td>
   <td style="text-align:left;"> $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:28:01 </td>
   <td style="text-align:left;"> $SPY go up more it’ll just crash harder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:27:42 </td>
   <td style="text-align:left;"> $SPY you have permission to be long now. News will get better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:27:42 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Once futes turn red, the tune will change again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:27:39 </td>
   <td style="text-align:left;"> $SPY $415 Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:27:37 </td>
   <td style="text-align:left;"> $SPY If @OldFngGuy is wrong tomorrow I will laugh so hard!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:27:24 </td>
   <td style="text-align:left;"> $SPY got almost 2k in puts for march22 down 17% for today… my puts dead or nah ? Lol we’ll see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:27:13 </td>
   <td style="text-align:left;"> I’m thankful $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:27:07 </td>
   <td style="text-align:left;"> $SPY everything priced in until it isn’t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:26:56 </td>
   <td style="text-align:left;"> $SPY This is a good one.  In my city off a main drag there&amp;#39;s a gigantic digital billboard declaring, in blue and yellow letters &amp;#39;WE STAND WITH UKRAINE&amp;#39;

Mfer I don&amp;#39;t.  Nope.  When someone you know who is a CNN eater posts some thing on Fbook of whatever virtue-signalling their love for Ukraine, hit em w this and be like, &amp;#39;Oh these guys?  You&amp;#39;re with them?  Tell me MORE!!&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:26:47 </td>
   <td style="text-align:left;"> $SPY still see a downtrend this year but let’s at least let this go up till the end of April </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:26:45 </td>
   <td style="text-align:left;"> $SPY Russia will take over Ukraine soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:26:22 </td>
   <td style="text-align:left;"> $SPY as long as nothing crazy happens in Ukraine tonight this will rip hard tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:26:20 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:26:16 </td>
   <td style="text-align:left;"> $SPY Cramer thinks we have further to fall. That&amp;#39;s all you need to know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:26:03 </td>
   <td style="text-align:left;"> $TSLA 

not only is Tesla fucked. 3rd company in 1 week. 

My god

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:26:02 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m gonna go ahead and say it...... This simulation sucks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:25:58 </td>
   <td style="text-align:left;"> $SPY Hedged puts with calls, a key move on a turbulent day. 
Tomorrow I’m going straight puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:25:45 </td>
   <td style="text-align:left;"> $SPY 
MM’s won’t be wanting to pay out all those calls on Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:25:44 </td>
   <td style="text-align:left;"> $SPY I understand now. All we need is Powell to keep saying the economy is strong while they raising interest rates? Got it. Next Fed meeting I&amp;#39;m all in! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:25:20 </td>
   <td style="text-align:left;"> $SPY 🔥😏 hello bulls... I guess bottom is in. Buy everything. Hoard it. You shall be paid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:25:19 </td>
   <td style="text-align:left;"> $SPY  bearish tags are passe now but give it a few weeks, they&amp;#39;ll be back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:25:07 </td>
   <td style="text-align:left;"> $SPY i was reading some bear post yesterday and some of them indicated that they liquidated their entire portfolio....i sure hope they are doing ok...uncle Powell, Kaplan, and Nancy Pelosi&amp;#39;s husband are praying for them.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:25:06 </td>
   <td style="text-align:left;"> $SPY I bought the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:25:05 </td>
   <td style="text-align:left;"> $SPY the fed will not stop inflation by rising rates 25 basis points. The market is going way higher. Where do you think we are gonna get the money to support Ukraine? Were gonna print it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:24:57 </td>
   <td style="text-align:left;"> $SPY everyone though 460 unlocked OFG but we found out today OFG unlocked 435 in actuality </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:24:54 </td>
   <td style="text-align:left;"> $AMD $SPY  tinyurl.com/ynmdf7ev </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:24:51 </td>
   <td style="text-align:left;"> We NAILED IT again...  CONGRADGULATIONS on joining us! $SPY $QQQ $DYD $RYLD  HAPPY ST PATRICKS&amp;#39;s DAY!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:24:51 </td>
   <td style="text-align:left;"> $SPY Aflac will pay you cash while you’re injured </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:24:50 </td>
   <td style="text-align:left;"> $SPY the day after fed meeting is always fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:24:49 </td>
   <td style="text-align:left;"> $SPY $QQQ why are houses so expensive? Do you all think it’s coming back to reality? Why?Thanks for your answers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:24:17 </td>
   <td style="text-align:left;"> $SPY gonna fuck puts all week long and thats a fact </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:23:52 </td>
   <td style="text-align:left;"> $SPY I cant find a reason to be bullish till after week. Cant dip toe in water with war still on table. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:23:44 </td>
   <td style="text-align:left;"> $SPY Keep in mind though, March 18th is when Crimea &amp;quot;joined&amp;quot; Russia and there will massive gatherings all around Russia. Quite certain they will kill hundreds of their own just to blame Ukraine on it. Belarus already began bombing villages and towns near the Ukrainian border with their fighter jets which will of course be blamed on Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:23:43 </td>
   <td style="text-align:left;"> $SPY C-E-R-T-A-I-N-T-Y we have a plan, hopefully it works. Inflation sucks for everyone including these companies were investing in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:23:37 </td>
   <td style="text-align:left;"> $SPY bulls think we are going to ATHs 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:23:36 </td>
   <td style="text-align:left;"> $SPY calls gonna be vegga UP Af tmroo may have to hold out on all stocks see what happens mhm decisions (: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:23:24 </td>
   <td style="text-align:left;"> $SPY one more face rip to put the bears down for good tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:23:11 </td>
   <td style="text-align:left;"> $SPY 🎃 it&amp;#39;s Halloween Friday ladies 

BACK to reality..inflation isn&amp;#39;t cured 🧸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:23:01 </td>
   <td style="text-align:left;"> $SPY what ever happened to Fauci? mf a ghost now 👻 narrative change, now it’s putins fault LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:22:59 </td>
   <td style="text-align:left;"> $SPY pick one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:22:53 </td>
   <td style="text-align:left;"> $SPY As a fellow bear ,plz calm down, let this happen, we resume the down trend at noon....don&amp;#39;t lose ur asses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:22:41 </td>
   <td style="text-align:left;"> $SPY fuggit guess I’m buying a buttfuckton of 0dte calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:22:36 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:22:36 </td>
   <td style="text-align:left;"> $SPY 

Zelensky is doing everything he can to draw the entire world into the Ukraine conflict; it&amp;#39;s his last ditch effort.... The way he begs for assistance, despite of the hardware provided by the WEST, demonstrates that his troops are losing the battle and are on the verge of collapsing.... And he&amp;#39;s afraid that, in the end, he&amp;#39;ll have to agree to Russia&amp;#39;s conditions and accept them. 

This whole nonsense about Russia wanting to deploy chemical weapons is a farce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:22:09 </td>
   <td style="text-align:left;"> $SPY a close above $446.18 would create a completely new channel and head to $454.15 in a 7 rate hike in 1 year environment when the 10 year bond is at 2.2 lol 

That goes against basic economics. Only catalyst left is quad watching day Friday. After that... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:22:08 </td>
   <td style="text-align:left;"> $SPY $440.00 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:22:04 </td>
   <td style="text-align:left;"> $SPY Don’t fight the Fed.  🤫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:59 </td>
   <td style="text-align:left;"> $SPY bulls been waiting so long to claim victory enjoy it cause youre getting rugged by friday close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:51 </td>
   <td style="text-align:left;"> $SPY the loudest people in the room were dead fucking wrong today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:50 </td>
   <td style="text-align:left;"> $SPY it’s good that I spent my first ~2.5 years of trading/investing in penny stocks because now everything trades like them $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:47 </td>
   <td style="text-align:left;"> $SPY 9 out of 10 people do not enjoy diarrhea </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:39 </td>
   <td style="text-align:left;"> What’s the most important bone for moving markets?  The jawbone, of course.  $spy $qqq $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:31 </td>
   <td style="text-align:left;"> $MSFT let’s goooooo $SPY $MELI $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:29 </td>
   <td style="text-align:left;"> $SPY I mean it looks bullish 
Could be a trap 
Guess we’ll see what news they release once they decide which way they want it to go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:26 </td>
   <td style="text-align:left;"> $SPY so I fked up today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:21 </td>
   <td style="text-align:left;"> $spy $dwac This guy is hilarious and correct. 😂

https://youtube.com/watch?v=5RUu1F800lE&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:20 </td>
   <td style="text-align:left;"> $SPY remember that Q1 closes out in about 2 weeks. I don’t expect us to get back to ATHs but the market makers tend to pump at the end of each qtr for mass america so they are decent 401k statements. Nobody wants to see their retirement savings down 13% in 3 months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:20 </td>
   <td style="text-align:left;"> $SPY that was like a Tom Brady comeback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:05 </td>
   <td style="text-align:left;"> $SPY Your family eats at Golden Corral. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:02 </td>
   <td style="text-align:left;"> $SPY 🔥😏 the rug pull will be sudden and almost illegal. It&amp;#39;s going to be glorious for bears. Bears - build your hedge and enjoy the daily daily PA trade(s). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:21:00 </td>
   <td style="text-align:left;"> $SPY Short term uncertain, medium term bearish, long term uncertain. If you enter puts near these levels they will pay at least once in the next 7 trading days given the overbought nature of SPY right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:56 </td>
   <td style="text-align:left;"> $SPY $NET $CRWD $FTNT Started my taxes today.  Is it just me or is everyone thinking that mid-April would be an exceptionally obvious time for the mother of all Russian hack-jobs?  Sure hope the IRS gets their sh*t locked down.  Fookin&amp;#39; Putin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:47 </td>
   <td style="text-align:left;"> $AMC $SPY Futures are still green. 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:45 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:32 </td>
   <td style="text-align:left;"> $SPY I am going feel very bad for people if they don&amp;#39;t manage risk and understand that this market could rip higher in days to come. 
 
Just look at the VIX. 
 
There is no uncertainty anymore besides Russia. What else is there to worry about? 
 
Everything else is certain and clear. There is no reason to be feared in this market as you have all the answers now: 
 
Inflation is increasing 
Rates are coming 
House prices going up. 
 
Not sure why any individual would be scared knowing what they now know. This doesn&amp;#39;t imply that things can go down, but it does say that people could be continuing to buy equities this year during this slow period. 
 
All it takes is WSJ to keep pumping and informing people to buy equities since everything is cleared up. 
 
For the downside, all it takes is for more war FUD. 
 
Play smart... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:27 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Uh, oh…. 
A major warning for all of us tonight. 

OFG returned, claiming inflation cured his impotence again! 

We all know what happens next! 

Hide your women and children. 

🤣🤣🤣🙄🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:23 </td>
   <td style="text-align:left;"> $SPY Bulls wouldn&amp;#39;t know a bear market if it slapped them in the ass. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:23 </td>
   <td style="text-align:left;"> $SPY 
Congrats &amp;amp; all the BEST 
https://www.reuters.com/world/us/senate-panel-approves-powell-renomination-fed-chair-2022-03-16/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:09 </td>
   <td style="text-align:left;"> $SPY we could easily take another 15 points by Friday, maybe more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:08 </td>
   <td style="text-align:left;"> $SPY is this considered the “return to normal stage”? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:03 </td>
   <td style="text-align:left;"> $SPY there is too much speculation n gaming going on. They reduced the limit to 5% on nickel today at LSE and not even 250 contracts traded. It was 45k+ last day of trading. No one wants to gamble for 5%. They need to contain this NDF bs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:20:02 </td>
   <td style="text-align:left;"> $SPY UVXY SPXL SPXS its becoming obvious to expect the unexpected bought 200 shares of SPXL at close because my 1000 shares of uvxy where dropping - thoughts ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:19:59 </td>
   <td style="text-align:left;"> $SPX $SPY held white resiliently and bears running out of time. possible we are at the arrow shown in 2018 fractal, but if bears don&amp;#39;t pull the rug in the next few weeks likely have to wait until Q3 until further downside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:19:49 </td>
   <td style="text-align:left;"> $SPY everyone’s bullish 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:19:40 </td>
   <td style="text-align:left;"> $SPY So fed has hike rates, so what’s the next catalysts for ATH? Anyway, welcome to stagflation and recession. Remember during stagflation and recession, your charts wouldn’t work. It is going to get really nasty 🔜 

Big money left the bags for Stocktwits/Twitter bulls ⬇️⬇️⬇️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:19:16 </td>
   <td style="text-align:left;"> $SPY j pow a bitch.. 0.25 rate hike..bitch i coulda did that myself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:19:13 </td>
   <td style="text-align:left;"> $SPY Hong Kong going up 20%. 😂🤣. These are penny stocks now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:19:11 </td>
   <td style="text-align:left;"> $SPY guys OFG is an algo which is triggered @ 450+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:19:07 </td>
   <td style="text-align:left;"> $SPY Jussie Smollet spent “5 minutes alone” behind the judge’s bench and got released. Jurors claim it sounded like he was slurping a Slurpie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:58 </td>
   <td style="text-align:left;"> $SPY bears want last cent, or assume market care about your entry, no, it will never come back to fetch you to school </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:53 </td>
   <td style="text-align:left;"> $ARKK in the Money 🔥🤣🏦 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:50 </td>
   <td style="text-align:left;"> $SPY you know when old fing guy is here it’s a bull market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:48 </td>
   <td style="text-align:left;"> $SPY full moon tonight I don&amp;#39;t fuck with that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:45 </td>
   <td style="text-align:left;"> $SPY time to go nuclear!!! War </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:37 </td>
   <td style="text-align:left;"> $SPY Long live daytrading. The Fed screwed long term investors and volatility will be king until it&amp;#39;s fixed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:35 </td>
   <td style="text-align:left;"> $SPY JPow with addressing inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:20 </td>
   <td style="text-align:left;"> $SPY if Nancy still in, I&amp;#39;m still in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:12 </td>
   <td style="text-align:left;"> $SPY Only begging bears tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:11 </td>
   <td style="text-align:left;"> $SPY Elon Musk vs Putin.  Hand to hand combat til the death.  Who would win? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:18:04 </td>
   <td style="text-align:left;"> $SPY unless you are margincalled already no reason to panic cover. Fed money = green, No Fed money = red eventually. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:17:54 </td>
   <td style="text-align:left;"> $SPY close above bear trend line tomorrow means calls for the ride to the blow off top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:17:53 </td>
   <td style="text-align:left;"> $SPY yes! More ball kicking meme!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:17:49 </td>
   <td style="text-align:left;"> $SPY hongkong reaches 1mil covid cases </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:17:47 </td>
   <td style="text-align:left;"> $SPY high inflation and higher rates.....brilliant....daddy Powell knows how to press the bears buttons </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:17:40 </td>
   <td style="text-align:left;"> $SPY Smart ? Lol.
JUST IN 🚨 Russian ship carrying 8,000 tons of petroleum product turned away from US port - AP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:17:29 </td>
   <td style="text-align:left;"> $SPY I can’t wait for tomorrow to send @OldFngGuy back into lockdown. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:17:21 </td>
   <td style="text-align:left;"> $SPY rates probably don’t matter much anymore. Smart money is focused on QE and tightening. Lots of talk but not much action on that front. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:17:12 </td>
   <td style="text-align:left;"> $SPY say no to war we love China, Russia and America except Europe. We need each other to raise our standard of living! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:17:00 </td>
   <td style="text-align:left;"> $SPY 🐻 in training bring it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:16:58 </td>
   <td style="text-align:left;"> $SPY mm won&amp;#39;t pay your puts, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:16:46 </td>
   <td style="text-align:left;"> $SPY $QQQ The futures are looking better and better here, looks like we can go for 3 up days in a row tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:16:42 </td>
   <td style="text-align:left;"> $SPY the default market direction is up 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:16:41 </td>
   <td style="text-align:left;"> $SPY I’m just saying..remember March 11th? The fed was hawkish, things got worst since last fed meeting… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:16:38 </td>
   <td style="text-align:left;"> $SPY Putin will be in a “hunting accident” very soon and markets will reach ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:16:29 </td>
   <td style="text-align:left;"> $SPY Higher tomorrow EOD, guaranteed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:16:16 </td>
   <td style="text-align:left;"> Market wants to fly parabolic here people freaked out on Another level no it’s not all great out there but when Wall Street smells offsides it punishes everyone who is on the wrong side of the trade short term $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:16:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:16:03 </td>
   <td style="text-align:left;"> $SPY a trillion in puts got smoked by BlackRocks Algo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:58 </td>
   <td style="text-align:left;"> $SPY we have to forget bad days.all red. look forward to fresh new ass whopping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:57 </td>
   <td style="text-align:left;"> $SPY i can see it now ofg and soc calling every newb a worthless piece of trash as we project our wealth as internet moguls DCA to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:56 </td>
   <td style="text-align:left;"> $SPY now I know why they keep talking about $3900 $QQQ $DIA $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:54 </td>
   <td style="text-align:left;"> $SPY test pilot for sending out more money right in front of the midterm elections </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:50 </td>
   <td style="text-align:left;"> $SPY okay let’s be serious.
What can crash this market? Like all the shit that happened within 1 month didn’t cause a black swan effect, what could possibly take this monstrosity down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:45 </td>
   <td style="text-align:left;"> $SPY 
Why is this turd skyrocketing? I thought we were selling the news. Fundamentals and technicals demand it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:44 </td>
   <td style="text-align:left;"> $SPY nuke Russia!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:42 </td>
   <td style="text-align:left;"> $SPY oil looks bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:42 </td>
   <td style="text-align:left;"> $CLOV I wish upon a star for clov to have a fucking huge volume peak meme st patty’s day run $SPY $MSFT 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:39 </td>
   <td style="text-align:left;"> $BABA grab your popcorn for hk open and watch bear scream or get squeeze $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:22 </td>
   <td style="text-align:left;"> $SPY Hold the door with 0.25 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:17 </td>
   <td style="text-align:left;"> $SPY wat was the trigger for Chinese equities today... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:09 </td>
   <td style="text-align:left;"> $SPY  
 
Bears, save this image to your meme folder. We&amp;#39;re petty af and want the saltiest tears possible to drink. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:05 </td>
   <td style="text-align:left;"> $SPY dump coming tomorrow! Remember Jan 27th? Day after Fed meeting? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:15:02 </td>
   <td style="text-align:left;"> $QQQ , $SPY , $VIX  
$IWM , $RUT  : Only Few Get This ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:14:46 </td>
   <td style="text-align:left;"> $SPY I think the craziest thing is how many bears they suckered in along with them not exiting there position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:14:44 </td>
   <td style="text-align:left;"> $SPY I’ve won some poker tourneys though maybe I should play a little </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:14:38 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:14:34 </td>
   <td style="text-align:left;"> $SPY Why is the monthly chart bearish? This ran all the way to 437 today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:13:58 </td>
   <td style="text-align:left;"> $SPY just so many chips on the table and more still being added. It’s gross </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:13:48 </td>
   <td style="text-align:left;"> $SPY basically everything that caused this to crash in the previous days has escalated but somehow this keeps on pumping. Someone help me understand and dont say its priced in lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:13:47 </td>
   <td style="text-align:left;"> $SPY I think 💭 ver pumping it to crash it hard Imo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:13:47 </td>
   <td style="text-align:left;"> $SPY awesome! We are all back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:13:40 </td>
   <td style="text-align:left;"> $SPY I’m just glad we got off the Russia thing moving markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:13:22 </td>
   <td style="text-align:left;"> $SPY I see an NFT I kinda know you have nothing to offer me.  Blockarino.  Blockinated.  Blocktowne. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:13:20 </td>
   <td style="text-align:left;"> $UBER $SPY printing start </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:13:14 </td>
   <td style="text-align:left;"> $SPY wouldnt mind a 2-3% sell off so i can sell some vertical put debit spreads </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:12:57 </td>
   <td style="text-align:left;"> $SPY $4150 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:12:45 </td>
   <td style="text-align:left;"> $SPY me and ofg at the moment, though he blocked me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:12:20 </td>
   <td style="text-align:left;"> $SPY My favorite part of making money both ways… Is making money both ways. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:12:15 </td>
   <td style="text-align:left;"> $SPY if Chinese stock didn&amp;#39;t rallied, we&amp;#39;d get fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:12:11 </td>
   <td style="text-align:left;"> $QQQ $SPY ngl definitely doesn’t feel like a bear market. Bulls keep getting 7% swings their way lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-17 08:11:50 </td>
   <td style="text-align:left;"> $SPY Back to BTD🤷‍♂️ I don’t make the rules folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:49:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX  Technical Analysis from one of my favorite follows 

https://youtu.be/Xqrp1Dcv4tE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:49:26 </td>
   <td style="text-align:left;"> $QQQ look up Jan 28-29 and Feb 24-25 in the markets. look at what happened after those days in the markets.  
 
Then you will see why some people are bearish here on what seems to be a super bullish rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:49:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 85684600. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:46:40 </td>
   <td style="text-align:left;"> $QQQ $DJIA $SQQQ $DJIA https://talkmarkets.com/content/bonds/the-fed-is-looking-for-tighter-financial-conditions-good-luck-stocks?post=348234 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:46:10 </td>
   <td style="text-align:left;"> $QQQ There are too many unpredictable variables these days to make an accurate prediction about next week, let alone the coming months. It&amp;#39;s kinda funny, in a sad way, seeing bulls/bears make their claims and then the next day it moves against them. Seems we should only be day trading now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:46:03 </td>
   <td style="text-align:left;"> $SPY $UVXY $AAPL $QQQ $TSLA 

The only thing worse than war is complacency. Investors &amp;amp; civilians seem to already be desensitized to the horrors that are going on in Ukraine. Stubborn bulls become low quality steak, remember that… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:44:32 </td>
   <td style="text-align:left;"> $XLE $USO $QQQ $SPY Gas stimmies for the EV driving Californians...😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:42:58 </td>
   <td style="text-align:left;"> $QQQ bubble stocks bubbling again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:42:16 </td>
   <td style="text-align:left;"> $QQQ this is a gamblers market not base on fundamentals...up to MM to say whether the news are positive or negative...haha...you think it&amp;#39;s negative but they will give you a tight slap and tell you are wrong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:40:14 </td>
   <td style="text-align:left;"> $SQQQ, $QQQ  Why did the markets drop and then pop huge on the hawkish words and plans of the feds and J.Powell?   J.Powell, calmed the markets with a very clear plan, with some milestones folks can track - so he removed uncertainty, which markets hate.  I think that the computer algos also kicked in, and squeezed shorts out today.  This is a rare time I&amp;#39;m with the confused suits of CNBC, because there was little common sense to the market&amp;#39;s over-done, emotional  bullish reaction to what was a clearly hawkish fed plan.  We will see on Thurs/Fri how things go.   
https://www.youtube.com/watch?v=VYex_Nk4FKI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:39:23 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA $SQQQ  https://www.bloomberg.com/news/articles/2022-03-16/tesla-halts-bond-sale-backed-by-auto-leases-amid-market-turmoil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:38:52 </td>
   <td style="text-align:left;"> The #Fed Is Looking For Tighter Financial Conditions; Good Luck Stocks $QQQ $SPY $SPX https://talkmarkets.com/content/bonds/the-fed-is-looking-for-tighter-financial-conditions-good-luck-stocks?post=348234 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:37:18 </td>
   <td style="text-align:left;"> $SPY $QQQ 

A bit of trivia: in both 2000 and 2008 crashes, the actual real bottom was not realized until the next year, 2001 and 2009. Of course, during the courses, there were many days of -3% to +3% and vice versa. Look them up. 
The knowledge may save your portfolio. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:35:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA  this hands down has to be dumbest rally I&amp;#39;ve seen in along time. Hawkish AF, Powell  says economy is strong, if that&amp;#39;s the case why are they raising rates? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:35:28 </td>
   <td style="text-align:left;"> $QQQ $SPY It&amp;#39;s just so funny when the market is up we only see bulls posts or vice versa. I think this forum is just being used as a place for pissing contest. Nothing more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:35:05 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ does anyone have any ideas what happens next? Dash crash then dash before the closing bell. It seems a little too rosy after rates went up war looming and quad witching day around the corner. I don’t feel confident this is the end of the bear market, call me a pessimist 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:34:17 </td>
   <td style="text-align:left;"> $QQQ it will take time but market will realize the Feds aren&amp;#39;t on their side anymore. QT will be introduced in May and liquidity will be drained from the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:32:57 </td>
   <td style="text-align:left;"> $QQQ well this is the first of the interest rates ...many more to come...market will almost eventually realise that the party is over...hard times ahead... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:32:17 </td>
   <td style="text-align:left;"> latex86c0553daa4593eb9e56c2c7066fb7c6NIO 400%
@MommasOptions 
$YINN 240%

 Live Streaming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:29:40 </td>
   <td style="text-align:left;"> $QQQ histogram turn green today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:29:24 </td>
   <td style="text-align:left;"> $SPY $QQQ that bear trap after the FOMC was one of the most brutal I’ve seen, made my hedges run wild, so can only imagine net bears… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:28:09 </td>
   <td style="text-align:left;"> $SPY $QQQ what happened today is simple too much cash on the sidelines and no sellers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:27:42 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Once futes turn red, the tune will change again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:27:19 </td>
   <td style="text-align:left;"> $QQQ do you know how mad bears would be if have reached the bottom? So many bears out there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:26:03 </td>
   <td style="text-align:left;"> $TSLA 

not only is Tesla fucked. 3rd company in 1 week. 

My god

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:25:38 </td>
   <td style="text-align:left;"> $QQQ the next level on Feb-ret is at 349 once it’s taken then it  will run to next level at new ATH and beyond </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:24:51 </td>
   <td style="text-align:left;"> We NAILED IT again...  CONGRADGULATIONS on joining us! $SPY $QQQ $DYD $RYLD  HAPPY ST PATRICKS&amp;#39;s DAY!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:24:49 </td>
   <td style="text-align:left;"> $SPY $QQQ why are houses so expensive? Do you all think it’s coming back to reality? Why?Thanks for your answers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:24:23 </td>
   <td style="text-align:left;"> $QQQ With all the MMs fuckin shenanigans, is anyone even making any money in this market?  😀😆🤑💲💰💲💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:22:49 </td>
   <td style="text-align:left;"> $QQQ the crazy thing is this went up 3% down 3% and back up to 3.7%… 9% in large swing. People got robbed today. Especially those who can’t say trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:22:07 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : We&amp;#39;re With Warren - Buy SPY And Go Play Some Golf https://www.stck.pro/news/QQQ/24511747 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:21:39 </td>
   <td style="text-align:left;"> What’s the most important bone for moving markets?  The jawbone, of course.  $spy $qqq $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:21:29 </td>
   <td style="text-align:left;"> $QQQ last weeks close below blue has me a bit hesitant, but so far a successful recapture. same story as spy, bears running out of time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:20:27 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Uh, oh…. 
A major warning for all of us tonight. 

OFG returned, claiming inflation cured his impotence again! 

We all know what happens next! 

Hide your women and children. 

🤣🤣🤣🙄🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:19:37 </td>
   <td style="text-align:left;"> $QQQ hey shorts you deserve everything you got ha ha ha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:17:52 </td>
   <td style="text-align:left;"> $QQQ 340 has been a resistance 

If we can stay above it this is a good first step

Watch tomorrow and Friday to see if level holds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:17:21 </td>
   <td style="text-align:left;"> $QQQ if you predict the earnings/EBITDA/revenue and predict the multiple of each stock then you will know where the market is going -- if you are doing something else then u r missing the point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:16:46 </td>
   <td style="text-align:left;"> $SPY $QQQ The futures are looking better and better here, looks like we can go for 3 up days in a row tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:16:16 </td>
   <td style="text-align:left;"> Market wants to fly parabolic here people freaked out on Another level no it’s not all great out there but when Wall Street smells offsides it punishes everyone who is on the wrong side of the trade short term $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:16:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:15:56 </td>
   <td style="text-align:left;"> $SPY now I know why they keep talking about $3900 $QQQ $DIA $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:15:02 </td>
   <td style="text-align:left;"> $QQQ , $SPY , $VIX  
$IWM , $RUT  : Only Few Get This ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:12:11 </td>
   <td style="text-align:left;"> $QQQ $SPY ngl definitely doesn’t feel like a bear market. Bulls keep getting 7% swings their way lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:11:28 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
Those bear market rallies are fierce..  9%, 7%, 5%, 3%... Lucky enough to catch one of those right, then you can change your fortune overnight.. like those Chinese stocks.. WOW. 
 
Overall, this is NOT healthy by any means. Carefulness preserves wealth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:11:26 </td>
   <td style="text-align:left;"> $SPY $QQQ I&amp;#39;d be surprised to see a single red week until about September </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:09:26 </td>
   <td style="text-align:left;"> $SPY $QQQ JUSSIE SMOLLET’S ATTACKER WAS JUST RELEASED FROM PRISON

RACIST USA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:09:24 </td>
   <td style="text-align:left;"> $SPY $QQQ inflation is going to get worse with these minuscule 0.25% interest rate &amp;quot;hikes&amp;quot; and corporate profits will go lower. it&amp;#39;s like digging a sand hole at the beach while having someone kick new sand back in again at the same time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:09:06 </td>
   <td style="text-align:left;"> $QQQ 💓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:07:11 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA BTW Powell said next meeting they&amp;#39;ll start reducing the balance sheet meaning their about to run the printers over-time till then 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:06:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Tsunami Alert Canceled After Big Quake Near Fukushima

https://www.google.com/amp/s/www.nytimes.com/live/2022/03/16/world/fukushima-japan-earthquake.amp.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:06:24 </td>
   <td style="text-align:left;"> $SONM and $QQQ have a 0.27 Pearson correlation coefficient for daily price percent changes. 
 
Values range from -1 to 1, where -1 is a total negative correlation, 0 has no correlation, and 1 has total positive correlation. 
 
https://twentyontwenty.com/symbol/SONM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:05:38 </td>
   <td style="text-align:left;"> $QQQ THERE SHALL NOT BE ANOTHER RED CANDLE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:04:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA strong earthquake hitting north-east Japan

https://www.google.com/amp/s/www.bbc.com/news/world-asia-60770100.amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:04:09 </td>
   <td style="text-align:left;"> $NDX $QQQ $ES_F $SPY $DIA 

Price it forward </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:03:03 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA 

Damn, Fed expects inflation to drop to 4% eoy 

Wow murderous </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:02:37 </td>
   <td style="text-align:left;"> S&amp;amp;P 500, Nasdaq 100, Dow Blast Higher as Market Bets Fed Will Engineer Soft Landing https://www.billionaireclubcollc.com/sp-500-nasdaq-100-dow-blast-higher-as-market-bets-fed-will-engineer-soft-landing/  $SPY $DJIA $VIX $QQQ $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:02:33 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-16 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=e7q_ZVgRhwU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:01:38 </td>
   <td style="text-align:left;"> $QQQ let’s go $350 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:00:44 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 08:00:22 </td>
   <td style="text-align:left;"> $QQQ Best two-day run for the NASDAQ since 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:59:23 </td>
   <td style="text-align:left;"> $QQQ Watch what happens now that extended hours is over 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:59:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $DFEN $USA $AMD 
My friend Bill just sent me this 🤣. The good people of the world are coming to get you Badimir Pukin! 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:58:07 </td>
   <td style="text-align:left;"> $AFRM $BABA $QQQ $TSLA $BTC.X 
Cramer is the devil. He mixes true with lies and confuse retail. 2 weeks ago he brought charts from some expert that bottom is in. Now tonight his saying this crap. He made retail miss 50% run on Chinese stocks. Some of the shit he says is true but 50% is also lie. Now what? Sell tomorrow and watch everything go up? Or believe this fool that bottom still not in…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:57:59 </td>
   <td style="text-align:left;"> $SPY $QQQ going up AH due to Jussie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:56:50 </td>
   <td style="text-align:left;"> $C It’s just business. 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:55:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA bull market is back on?  Great.  Back to bitching about my taxes and tapping my foot all weekend :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:55:03 </td>
   <td style="text-align:left;"> $QQQ futes rippin! 
 
lol 
 
had to say it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:54:05 </td>
   <td style="text-align:left;"> $QQQ pumping still last minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:54:01 </td>
   <td style="text-align:left;"> $QQQ $SPY powell is literally that phone ceo guy from don’t look up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:53:41 </td>
   <td style="text-align:left;"> Beyond first rate hike, the Fed signals that inflation fight is going to get harder

https://www.cnbc.com/amp/2022/03/16/why-feds-first-rate-hike-since-2018-isnt-the-key-to-economys-future.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:53:28 </td>
   <td style="text-align:left;"> $SPY $QQQ HOLY SHIT I LOVE UKRAINE AND HATE PUTIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:53:23 </td>
   <td style="text-align:left;"> $QQQ i was a little girl i got on a bus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:53:11 </td>
   <td style="text-align:left;"> $MOS https://www.cpr.ca/en/about-cp-site/Pages/-TCRC-2022-labour-negotiations.aspx
$SPY $SPX $VIX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:52:45 </td>
   <td style="text-align:left;"> $QQQ whats the bull case? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:52:26 </td>
   <td style="text-align:left;"> $QQQ $SPY biden offering Ukraine 800 million to help, how much $ do these fags print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:48:57 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
let&amp;#39;s get rates up higher so Millennial can finally afford to buy home! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:48:30 </td>
   <td style="text-align:left;"> $QQQ if Biden could stop signing trillion dollar checks to a fucking comedian, that would be great. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:48:22 </td>
   <td style="text-align:left;"> $QQQ $SPY

History repeats, but this time it&amp;#39;s spacs and some tech

https://youtu.be/25_WjiZnvQk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:46:31 </td>
   <td style="text-align:left;"> $QQQ since when does the &amp;quot;U.S.&amp;quot; sign multi-billion dollar FOREIGN aid bills during a &amp;quot;State of Emergency&amp;quot;.... but all of this is by chance of course! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:45:51 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
0.25% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:45:01 </td>
   <td style="text-align:left;"> $QQQ dont forget that fucking FEMA is still in charge everyone .. while billions are being signed away in &amp;quot;foreign aid&amp;quot; (which will NEVER be fully tracked) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:43:52 </td>
   <td style="text-align:left;"> $QQQ drop it 3 percent tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:42:28 </td>
   <td style="text-align:left;"> $SPY $QQQ I think @HollywoodWolf777 got his account suspended, I miss all the spam😥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:41:45 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX 

Breaking news 🗞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:40:15 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
0.25% is not a &amp;quot;rate hike&amp;quot; 
 
dumb motherfuckers everywhere! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:40:12 </td>
   <td style="text-align:left;"> $GLD $IWM $QQQ $SPY  
If Russia sell it&amp;#39;s gold to cover it&amp;#39;s debt ⤵️🔽⏬⬇️👇📩🔻↘️📉😨😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:39:57 </td>
   <td style="text-align:left;"> $SPY $QQQ no way did we hit bottom there&amp;#39;s at least another -25% downside to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:39:31 </td>
   <td style="text-align:left;"> $IBM Big blue is a sleeping monster; but sometimes he wakes up and roars high! $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:38:34 </td>
   <td style="text-align:left;"> $QQQ stock pattern pro guy posting 01 tech crash doom scenario chart may have been the actual bottom 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:38:10 </td>
   <td style="text-align:left;"> $SPY $QQQ The best time to buy is when the market is bottoming and has sold off a little bit, not at the ATH. Now it is a great time to add to your long term positions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:36:13 </td>
   <td style="text-align:left;"> $QQQ $SPY  really nice bounce for  growth name , &amp;quot; i&amp;#39;m still heavy value/blue chip name .
if $VIX  break 25 on weekly , i&amp;#39;ll rotate to more risky play . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:35:34 </td>
   <td style="text-align:left;"> $QQQ I wouldn’t short this in this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:34:42 </td>
   <td style="text-align:left;"> $QQQ $SPY 14bil for Ukraine, and im constantly having to feed homeless elderly my lunch because i cant bare too see someone my fathers age on the streets hungry. UNREAL. Im in shock Biden signed that bill. I hate Ukraine with a passion now.  
WE the US tax payers deserve that money, feed the homeless, school kids, provide shelter and homes. Wtf is this guy doing. This isnt Ukraine, nor are they allies. Wtf is going on? 🤯🤯🤯🤯🤯🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:33:32 </td>
   <td style="text-align:left;"> $UVXY $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:32:51 </td>
   <td style="text-align:left;"> $QQQ s300 means buy to russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:32:23 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $DIA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:31:53 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
8% inflation and RISING 
 
FED sets interest rate at 0.25% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:30:24 </td>
   <td style="text-align:left;"> $QQQ https://www.cnbc.com/2022/03/16/charts-suggest-the-nasdaq-100-and-sp-500-could-be-days-away-from-bottoming-jim-cramer-says.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:30:15 </td>
   <td style="text-align:left;"> $UVXY $QQQ $SPY https://www.wsj.com/articles/saudi-arabia-considers-accepting-yuan-instead-of-dollars-for-chinese-oil-sales-11647351541 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:29:44 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA $SQQQ  Powell said they&amp;#39;ll start reducing the balance sheet next meeting lol make sense now🤡 https://www.forbes.com/sites/jonathanponciano/2022/03/15/biden-signs-15-trillion-spending-bill-with-14-billion-for-ukraine-aid-heres-whats-in-it/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:29:29 </td>
   <td style="text-align:left;"> $QQQ if u know the markets are rigged and u know the direction in which it is rigged dont then in the next sentence say you lost money taking the wrong position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:26:06 </td>
   <td style="text-align:left;"> $BABA $NIO $KWEB $SPY $QQQ  
 
It&amp;#39;s amazing what stocks do when central banks and governments print money to &amp;quot;support the markets&amp;quot; 
 
What a sham world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:24:05 </td>
   <td style="text-align:left;"> $QQQ $SPY Watch for $BTC.X to plunge big time tonight. There&amp;#39;s reports out of Bloomberg Asia that Putin &amp;amp; Xi are cashing out on this pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:22:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  I know it isn&amp;#39;t the best but my entire portfolio is 90%. Appe. Approx. $900,000k Safest stock in entire market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:21:10 </td>
   <td style="text-align:left;"> $QQQ all the comments in the world dont change one thing which is that given the supposed mandate of full employment and price stability the current fed funds rate is now just 0.25 percent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:20:57 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
i see today&amp;#39;s 0.25% interest rate as a TOTAL FAILURE of the FED to do their job at this point 
  
JPOW is the most spineless, fearful, cuck FED chair of all time. 
 
total pussy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:20:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $NDX $DIA $SPX 

Everybody watch Apple that’s dumping now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:18:43 </td>
   <td style="text-align:left;"> $QQQ what if QQQ goes up 5 more tmrw? Will u be ok? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:18:37 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
&amp;quot;should have moved earlier&amp;quot; 
 
but FED only raising rates to 0.25% now because &amp;quot;economy is strong&amp;quot; 
 
brilliant! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:18:18 </td>
   <td style="text-align:left;"> Stock futures are little changed as market looks to build on rally following Fed rate hike

$SPX $DJIA $QQQ

https://www.cnbc.com/2022/03/16/stock-futures-rise-slightly-as-market-looks-to-build-on-rally-following-fed-rate-hike.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:17:44 </td>
   <td style="text-align:left;"> $QQQ To be very, very clear:  FED never ever admits to recession possibilities. They never telegraph it as a strong possibility. Never have. Never will. If they did, economy would immediately constrict as CEO’s would pull in the reigns. Self fulfilling prophecy. I would say recession is 50/50 right now. It is certainly not remote. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:17:29 </td>
   <td style="text-align:left;"> $QQQ $IWM tomorrow looks wicky... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:16:48 </td>
   <td style="text-align:left;"> $QQQ bought sqqq for an over night hold looks good 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:15:57 </td>
   <td style="text-align:left;"> $SPY $qqq $djia why is a anyone holding anything on a quad witch Friday with a war going on in the middle of an unexplained psycho rally? Y&amp;#39;all crazy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:13:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $SQQQ $DJIA Questions you ignorant bulls have to ask yourselves is lol if &amp;quot;economy is so strong&amp;quot; why did we raise interest rates 25 basis points &amp;amp; not 50 or 75 basis points ? &amp;quot;We&amp;#39;ll reduce balance sheet next meeting &amp;quot; Seriously what the fuck are they waiting for?- Oh wait I know they just passed 1.5 Trillion Bill.  -Fucking clown!🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:13:44 </td>
   <td style="text-align:left;"> $QQQ none of JPOW&amp;#39;s prediction worked out in the last 12 months so no reason to think his current guesses matter either, so be it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:13:16 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Highest inflation in 40 years and RISING. 
 
FED sets interest rate at 0.25% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:13:11 </td>
   <td style="text-align:left;"> Allright… I bet we’re down tomorrow. Both $QQQ and $SPY… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:13:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $MULN $SOXL $DJIA 

Nice to see some real command from the bulls today for a change. Sorry shorties! Maybe you will have your day tomorrow. 

A toast to those who made fat gains, took hard losses and everywhere in between! We’re all fortunate to be playing this wild game, Cheers! 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:12:38 </td>
   <td style="text-align:left;"> $QQQ 20k of calls. Little scared futes aren&amp;#39;t ripping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:12:27 </td>
   <td style="text-align:left;"> Elon vs. Putin coming near you... 🤣🤣🤣 
 
$TSLA $SPY $QQQ $VIX  
 
https://twitter.com/TicTocTick/status/1504233522071973888 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:12:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Im not an ivy league grad, so what do I know.  But it seems like all the trusted economists Ive listened to are scratching their heads on how all this FED math adds up.  What we do know is &amp;quot;He has powerful tools. And he will use them. Some time ….    In the future.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:11:06 </td>
   <td style="text-align:left;"> $QQQ Talking heads can’t explain the pop. Me neither. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:10:46 </td>
   <td style="text-align:left;"> $QQQ market is different from last year. Time to get some put now…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:08:18 </td>
   <td style="text-align:left;"> $QQQ inflation is here to stay. buy bitcoin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:07:59 </td>
   <td style="text-align:left;"> $QQQ It usually plunges a day after the meeting. See if it holds the pattern this time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:06:12 </td>
   <td style="text-align:left;"> $QQQ $SPY Gap down of 2% tonight (if not more) and next 2 days 7-10% to the shit house </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:05:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA 

Are you guys looking at this nickel trade right now 

Halted down $NDX $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:03:46 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures higher, looks like more pain to come for the bears tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:03:18 </td>
   <td style="text-align:left;"> $QQQ $DIA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 07:03:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $QQQ https://youtu.be/xRW_6IXUr5Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:59:58 </td>
   <td style="text-align:left;"> $QQQ $SPY Just plain idiots pumping and talking out of their asses...Smart investors know what&amp;#39;s coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:59:43 </td>
   <td style="text-align:left;"> $SPY $SQQQ $QQQ Its hard to see in this chart but I wanted to show the whole thing. Today we broke the blue resistance line that’s held ALL YEAR. I’ve been doing exceptionally well trading the blue channel but now all hats are off. If you guys thought it was volatile before just watch what happens now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:59:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
To be honest, that Fed meeting was nothing to be happy or to rally about at all…. But that was what you called a a short squeeze on an expired day…. If it rallies again tomorrow, that probably means we’d bottomed and the trend is back up until some bad war news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:58:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Anyone want to join my trading discord?

Beating most bulls on here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:58:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $RSX 

It will give you a good laugh 😂 

https://twitter.com/dallastexastv/status/1504157531450580997?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:58:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $NDX $DIA 

I bought puts already just waiting for the next red day nothing more to report here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:58:19 </td>
   <td style="text-align:left;"> $qqq ain’t 🥜 ing Willy can’t fix.  At least 🐑 term!   🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:56:50 </td>
   <td style="text-align:left;"> Live updates: US says Russian troops stalled outside Kyiv https://www.billionaireclubcollc.com/live-updates-us-says-russian-troops-stalled-outside-kyiv/ $SPY $DJIA $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:56:21 </td>
   <td style="text-align:left;"> $QQQ 
Get ready for an extremely volatile Thurs and Fri. It&amp;#39;s Quad witching time. When you think it&amp;#39;s great, it&amp;#39;ll go down, when you think we are going to tank, it goes up. So for me, it&amp;#39;s hedge week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:55:44 </td>
   <td style="text-align:left;"> $QQQ bitcoin leads the way📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:55:20 </td>
   <td style="text-align:left;"> $SPY omg if it tumbled over night like it did today look out below $AAPL $QQQ $SPX 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:54:55 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY $IWM ath by next Friday!? 🤔. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:54:39 </td>
   <td style="text-align:left;"> $QQQ Smart money sold into strength today... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:52:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Everyone on Stocktwits wears a suit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:52:22 </td>
   <td style="text-align:left;"> $SPY $QQQ weekly close &amp;gt;337 and probably goes on to retest 370 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:50:55 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM Just a friendly reminder, on polarizing days like today...if you&amp;#39;re happened to make a killing...just STFU..no need to troll or insult...because what goes around comes around. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:50:07 </td>
   <td style="text-align:left;"> $AAPL anyone know how far this is about to drop? $SPY $SPX $QQQ  ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:49:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Possibly the best chicken fried steak in the state of Texas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:49:14 </td>
   <td style="text-align:left;"> $QQQ Many will wake up with a different mood tomorrow. Forget piece talks after Biden called Putin a war criminal. Tutes will also take some off the table and/or rotate to value stocks. QQQ is still made of non value stocks mostly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:48:57 </td>
   <td style="text-align:left;"> $QQQ all those people that were like yeah lets go long energy and utilities and short tech and china as a paired trade lost like 30 percent today LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:48:41 </td>
   <td style="text-align:left;"> $QQQ this shit said it was down 3% wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:48:23 </td>
   <td style="text-align:left;"> $QQQ AYO?! 🤨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:47:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 85684600. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:46:51 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ Posted Spy and Q&amp;#39;s already.  Here&amp;#39;s SPX.  SAME thing:  no surprise, none, why it stopped where it did today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:46:39 </td>
   <td style="text-align:left;"> $QQQ if they drop it hard tomorrow, I am buying a fucking bot to do my trades for me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:46:13 </td>
   <td style="text-align:left;"> $SPY $QQQ Bulls making me angry today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:45:09 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
   
  
8% inflation  
  
0.25% interest rate  
  
Wall Street celebrates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:44:57 </td>
   <td style="text-align:left;"> $BCTX $SPY latexb47a08d4063fb21efed25a070c16e516INDO$UVXY $BTC.X 
What is the next leg up for this HIDDEN GEM: BCTX $25.00??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:44:45 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
If you had your $$ in growth you were up atleast 6-9% today, more if you juiced it with options. Still - growth has a lot of work to do to recover off big draw down levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:44:26 </td>
   <td style="text-align:left;"> $QQQ $SPY Same as the post I just left on SPY, there&amp;#39;s no surprise, none, why it stopped where it did today.  Still a lot of mess here, far more than SPY, which is downright eager to continue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:44:14 </td>
   <td style="text-align:left;"> $QQQ Rejected exactly at the 20sma tomorrow is make or break day for Nasdaq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:43:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $KWEB $BABA $NIO  
 
&amp;quot;Authorities will rely on monetary policy as well as new loans to achieve its goals &amp;quot; of stabilizing the markets 
 
So, even in China asset holders are once again bailed out by the government and central banks? 
 
It&amp;#39;s becoming blatantly obvious that the whole world is a fucking sham designed to protect the assets of the wealthy at the expense of the poor and lower classes. 
 
https://www.barrons.com/articles/alibaba-baba-jd-china-stocks-51647423648 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:40:27 </td>
   <td style="text-align:left;"> $QQQ $SPY https://youtu.be/l7v8DAbIOx0 🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:40:12 </td>
   <td style="text-align:left;"> $QQQ bulls still need to show up tomorrow and Friday which is a big ask especially after this pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:39:50 </td>
   <td style="text-align:left;"> $BIDU $BABA $SPY $QQQ 🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:38:12 </td>
   <td style="text-align:left;"> $SPY $QQQ Posting this for the benefit of all.  Shared it in a private convo earlier.  It&amp;#39;s the best piece out there on Russia&amp;#39;s unavoidable credit and capital collapse, within weeks.  I&amp;#39;ve posted stuff from Goldman Sachs about this previously.  Putin needs to wrap up this Ukraine bullsh*t soon or Russia will be a fully bankrupt state. 
 
https://www.bloomberg.com/opinion/articles/2022-02-28/russia-s-money-is-gone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:35:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM Looks like this might have more sustained momo. No position in the indices right now. But, shorting here looks less realistic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:34:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
  
 8% inflation  
  
Fed sets interest rates at 0.25% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:34:02 </td>
   <td style="text-align:left;"> $QQQ thinking we went from a bear market Monday into a bull market in the last 2 hours today is a mental illness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:33:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $CL_F  Decide for yourself and share https://youtu.be/Igq2fqa7RY4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:33:31 </td>
   <td style="text-align:left;"> $QQQ it’s like all of a sudden we forgot about possible Russian debt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:33:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AAPL remember… you saw it here first. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:32:55 </td>
   <td style="text-align:left;"> $SPY $QQQ Powell: The economy is strong.

Me: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:32:30 </td>
   <td style="text-align:left;"> $IWM $SPY $QQQ Is there a limit up circuit breaker? Like, impossible for tech index to go up 20% in a day for some absurd reason right? $KWEB today, absolutely unprecedented </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:32:16 </td>
   <td style="text-align:left;"> $QQQ JPOW says FUCK YOUR PUTS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:31:17 </td>
   <td style="text-align:left;"> $QQQ keep comparing us to the dotcom crash 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:31:09 </td>
   <td style="text-align:left;"> $QQQ A rally to 360 or even the 200 dma at 367 is possible and I&amp;#39;d still be skeptical.  
 
I&amp;#39;ve never been interested in the first 15 or 20%. If we are heading to new ATHs there will be plenty of time to make $$. Who remembers the first 20% off of the 2020 lows? I sure don&amp;#39;t and that was an epic year. $SPY $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:30:53 </td>
   <td style="text-align:left;"> $QQQ Green tomorrow for St Paddy&amp;#39;s day, anything else would be a travesty. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:29:56 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
   
  
well 0.25% is great &amp;#39;course correct&amp;#39;! 
  
what a cuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:29:26 </td>
   <td style="text-align:left;"> $QQQ that resistance at 14,000 though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:29:12 </td>
   <td style="text-align:left;"> $QQQ huge follow thru to the upside tomorrow.. if you have been watching qqq since Biden you know it struck that ~315 support with vengeance and came out of the hole hot with monetary policy input. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:25:29 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
well 0.25% is great &amp;#39;course correct&amp;#39; 
 
lmfao!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:24:21 </td>
   <td style="text-align:left;"> $QQQ $SPY and… 10 YR continues to climb… (the literal recession indicator) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:23:01 </td>
   <td style="text-align:left;"> $QQQ $SPY The first move is up on fed day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:22:00 </td>
   <td style="text-align:left;"> $QQQ https://www.nytimes.com/live/2022/03/16/world/ukraine-russia-war#jake-sullivan-moscow-chemical-weapons </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:21:45 </td>
   <td style="text-align:left;"> Nasdaq 100  
 
$NQ_F $QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:20:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $GOOGL $AMD $ABNB prepare for red tomorrow and possibly Friday but if we can flip back to green by Monday the bears have lost temporary control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:20:11 </td>
   <td style="text-align:left;"> $QQQ Can someone post that pic of JPOW laughing? Literally how I feel about bears today haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:19:45 </td>
   <td style="text-align:left;"> $SPY $QQQ 2of 2: Despite all the sanctions on Russia there are still buyers of Russian energy. So we may have peaked in $USO as the supply has yet to actually get disrupted materially. That can change. The government also adjusted how they calculate CPI which will be bearish for continued CPI growth and will mask further inflation growth due to base effects. So the narrative will rise that inflation is declining and that the economy is growing. Again this will not be true but due to how the government reports data it will be. Tough to be overly bearish markets when the ponzi scheme is setting up its next round of growth and prosperity. For the few. And more pain for the masses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:19:18 </td>
   <td style="text-align:left;"> $SPY $QQQ Fed in panic mode about inflation. A controlled recession being engineered. * ignored Covid risks.*De emphasized Eastern Europe. * said recession/reduced employment not a concern * wages deflation is acceptable. ONLY CONCERN IS INFLATION 🚨😝 💣   👉Blue chip will be ok. Meme will be slaughtered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:19:16 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM amazing last 2 days, but we&amp;#39;ve seen this 4 times before in 2022 (all lead to disappointment). 
1/11, 1/31, 2/9, 2/25 =&amp;gt; NO continuation 
Let&amp;#39;s hope the 5th time is the charm...but have a stop loss just in case. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:17:40 </td>
   <td style="text-align:left;"> $AVGO should spring to 640 super volatile though 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:16:04 </td>
   <td style="text-align:left;"> $QQQ man I had to actually work today and couldn’t trade. I fucking missed the fuck out. Man FUCK. fuck you bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:16:03 </td>
   <td style="text-align:left;"> $SPY $QQQ bearish asia tonight.  5% drop.  short 436.  asiamageddon.  they don&amp;#39;t like powell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:16:00 </td>
   <td style="text-align:left;"> $SPY $QQQ 

 Curve your enthusiasm… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:15:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA I am currently 23 and plan to build my Roth around the following:

Microsoft
Apple
Nvidia
Google
Amazon

-M.A.N.G.A.

Any thoughts or advice here? I will have a long-term growth account and a trading account to supplement the retirement one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:15:25 </td>
   <td style="text-align:left;"> $DIDI  $QQQ  $SPX    &amp;gt;&amp;gt;   go.trade-ideas.com/SHDf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:14:18 </td>
   <td style="text-align:left;"> $QQQ bears are fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:13:53 </td>
   <td style="text-align:left;"> $SPY  $QQQ So everyone super bullish now after big spikes … no more Russia or rate issue I guess :) lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:13:53 </td>
   <td style="text-align:left;"> $QQQ who knows tickers for ammunition? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:13:22 </td>
   <td style="text-align:left;"> $SPY $QQQ 1 of 2: just some general thoughts. If you factor in inflation we are in a recession. The key here is inflation is not part of Wall streets analysis when they look at earnings and &amp;quot;growth&amp;quot;. Wages are lagging inflation which should weigh on GDP but is unlikley to go negative because inflation is so high. So we can pretend that the economy is strong when the reality is the growth is 107% driven by inflation. GDP growth 7% CPI 7.5% . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:13:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $SQQQ  25 basis point was soft, Bullard the only one on committee that has half brain.. wait till the news sinks in over this bs pump.  https://www.reuters.com/business/dollar-near-5-year-peak-yen-before-fed-aussie-weak-amid-china-risks-2022-03-16/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:12:20 </td>
   <td style="text-align:left;"> Alert on $TQQQ delivered today at 10:03AM CDT on 3/16/2022 🎯 

Server link in the bio for winning alerts and for those eager to learn. 
$SQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:12:00 </td>
   <td style="text-align:left;"> $QQQ $SPY Let&amp;#39;s talk stocks! https://youtu.be/OjSLLP74A4c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:11:56 </td>
   <td style="text-align:left;"> $QQQ $SPY Qs have a date with the 50wema…💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:10:52 </td>
   <td style="text-align:left;"> $SPY $QQQ Wait so is the war over and we can go up now? If I just checked Stocktwits, it would appear so 🍿. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:10:04 </td>
   <td style="text-align:left;"> $SPY $QQQ I didn&amp;#39;t buy anything today, an opportunity to buy is when the market has a big red day. Keep buying on the dips and you will make money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:09:38 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ $IWM - 🤫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:07:39 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:06:58 </td>
   <td style="text-align:left;"> $QQQ at this point would need a solid reason for reversal and one does not exist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:06:52 </td>
   <td style="text-align:left;"> $fb bring me back to this day 😢😩😩 $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:05:55 </td>
   <td style="text-align:left;"> $SPY $QQQ Zelensky has been paid billions by Biden and his war hawk crew to push for a proxy war against Russia on their borders. The fodder will be Ukrainians who stand no chance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:05:44 </td>
   <td style="text-align:left;"> $QQQ The Titanic bobbed up and down a few times before it sank to the bottom of the Caribbean Ocean. Fake pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:05:44 </td>
   <td style="text-align:left;"> $QQQ similar chart to when the war was announced. I’m sure it retraced. Be interesting to see. You simply can’t constantly have 3% up and down days forever lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:04:40 </td>
   <td style="text-align:left;"> $QQQ short term reversal back to $333… overbought in the 4hr chart… this thing got overhype today… LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:04:37 </td>
   <td style="text-align:left;"> $SPY $QQQ According to my model it will be a green day tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:04:06 </td>
   <td style="text-align:left;"> $Qqq tomorrow is flat/down day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:03:17 </td>
   <td style="text-align:left;"> $QQQ bye bye usd reserve currency </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:03:11 </td>
   <td style="text-align:left;"> $QQQ it&amp;#39;s most likely a sell the rip instead of buying the the dip market. Buying stocks with this administration in office good luck. Been invest in an areas outside the market since December good luck to everybody I&amp;#39;ll be back when we get a real administration in office. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:02:23 </td>
   <td style="text-align:left;"> $SQQQ $TQQQ $SPY $QQQ  Contract spreads looking really good so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:01:57 </td>
   <td style="text-align:left;"> $QQQ brilliant fighting actually 15 pct inflation with a .25 pct rate hike and continuing to increase the Fed s balance sheet. Wrecking the US and the begining of the end of the dollar as the reserve currency </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:01:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Thursday rippage? 🤫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:00:36 </td>
   <td style="text-align:left;"> $QQQ two big Green Day’s. What will be tomorrow like. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 06:00:33 </td>
   <td style="text-align:left;"> $SPY $QQQ Why are the rich so cruel? They have everything in life and more than they can spend yet they still shank us peasants with this plunge then rocketship. Why cant the little guy enjoy a sliver of what they have 24/7? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:59:53 </td>
   <td style="text-align:left;"> $QQQ $SPY mission creep...the weapons keep getting bigger and bigger...Russia is gonna do something rash.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:59:53 </td>
   <td style="text-align:left;"> $SPY $QQQ Ruble oversold. Going to go trade forex instead of wasting my time here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:58:55 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:58:49 </td>
   <td style="text-align:left;"> $QQQ no more bond buying and interest rates going up. Seems bearish to me but you wouldn’t know it from the last hour today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:58:37 </td>
   <td style="text-align:left;"> $SPY $QQQ We shouldn’t be supplying weapons to Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:58:20 </td>
   <td style="text-align:left;"> $JD pure GEM. $SPY $QQQ latexfdd79073c63cfaac5ac346bac4415ad1TQQ to 52+ 
$SQQQ back down to 40 ? 
 
Maybe, 100% risk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:56:13 </td>
   <td style="text-align:left;"> $QQQ definite red day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:56:06 </td>
   <td style="text-align:left;"> $QQQ Powell just wrecked the United States and the working class. Do you work for your money? poor you.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:54:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 

All the chest puffing “BTFD” dipshits from 2021 have had their souls crushed and are now fervently bearish. ST has become an echo chamber for broke sourpusses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:54:06 </td>
   <td style="text-align:left;"> $QQQ my first car was a 1972 Matador.  Ugly AF… horrible brakes.   
 
I got laid in it. 
 
this weekend I will driving a 2022,  911. 
 
I don’t want to get laid in it…but I’m sure I could. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:52:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Nice rally you have going there. Would be a shame if something were to happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:52:23 </td>
   <td style="text-align:left;"> $QQQ https://youtu.be/HXTRMT1el8o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:51:37 </td>
   <td style="text-align:left;"> $QQQ Thursdays and Fridays have been brutal all year  
 
this week will be no exception </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:51:34 </td>
   <td style="text-align:left;"> $QQQ the 3x short china (ticker YANG) went from 25 to 16 in the last 80 minutes of trading today -- think about that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:50:59 </td>
   <td style="text-align:left;"> $SPY $QQQ It&amp;#39;s not very often that u see a $50B market cap stock and a $250B market cap stock move 40% in a day 
 
🔥 $BIDU 
🔥 $BABA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:50:52 </td>
   <td style="text-align:left;"> $QQQ i hope we could keep the gains tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:47:13 </td>
   <td style="text-align:left;"> $QQQ Bought more puts at close. No way this holds +7% from Monday’s low. Profit taking tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:46:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA ⛔️⛔️⛔️⛔️⛔️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⛔️⛔️⛔️☢️☢️☢️☣️☣️☣️ IS GOING TO GET UGLY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:46:46 </td>
   <td style="text-align:left;"> $QQQ Market was sheepish the Fed would hike half point.  Now that those fears are abated, looks like it&amp;#39;s on like Donkey Kong until the bears can take the ball back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:45:48 </td>
   <td style="text-align:left;"> $QQQ weekly timeframe bodes a bullish engulfing candle. 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:45:37 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ  After tons of T/A and a few calls to a hedge fund friend.  I got a great look at what’s happening tomm. I posted my predictions on my comment
Page about 15 or so posts below. You might have to scroll through to see the comment. Given the feed was moving fast. It’ll give you an in-depth look at whats hedge funds are blocking tomm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:45:25 </td>
   <td style="text-align:left;"> $QQQ is it just me or did the host on CNBC say they were raising interest rates to .50, and not even 5 minutes later Powell says they’re only raising it .25? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:44:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 

To everyone adamantly bearish: Stop being so stubborn and follow the fucking trend. I had some puts prior weeks, I have calls now. It’s about making money, not about staying wrong until you’re finally right 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:44:34 </td>
   <td style="text-align:left;"> $QQQ and on this day, we are reminded... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:43:33 </td>
   <td style="text-align:left;"> $QQQ back to 350 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:43:01 </td>
   <td style="text-align:left;"> $QQQ OMG WE are aSTILL running.

Bears shooK. On Life support HUAHAHA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:42:58 </td>
   <td style="text-align:left;"> Fed raises interest rates for first time in four years and plots series of hikes to fight inflation

$SPX $DJIA $QQQ

https://www.marketwatch.com/story/fed-raises-rates-and-plots-strategy-of-steady-further-increases-11647453994?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:40:40 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ So we are just going to leave that gap below on SPX right? Ok. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:40:31 </td>
   <td style="text-align:left;"> $SPY $QQQ After 2.5 months of a bearish downtrend , I sense a lot of bears are afraid they didn’t eat enough before going back into hibernation. Bear season is ending folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:39:51 </td>
   <td style="text-align:left;"> $QQQ I feel really bad for call sellers and put holders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:39:30 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:38:45 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ war is bad. it&amp;#39;s gonna crash the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:38:28 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 3/16/2022 $SPY $QQQ $FB $NIO $CCJ https://www.chartguys.com/daily-market-videos/4193/flow-state-and-market-lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:38:22 </td>
   <td style="text-align:left;"> $SPY Lower gdp.   Higher rates 4x’s what expected we going to have a trough sell next few days or weeks

$spx $dia $qqq $es_f  I’m buyer of puts at the open 

Bank Of America told you sell the top. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:37:52 </td>
   <td style="text-align:left;"> $QQQ $SPY everything is good and well taken care of. Earnings will go up, stocks will go up, bonds will pay more, crypto will go up, and Russia will weep. Life is good, BTMFD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:37:50 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
8% inflation 
 
0.25% interest rate 
 
yep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:37:33 </td>
   <td style="text-align:left;"> $QQQ $SPY Awesome recovery, however looking at the numbers afterwards, it&amp;#39;s not great. I think this is all based on investors feeling on track and knowing that the FED won&amp;#39;t rug pull. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:36:23 </td>
   <td style="text-align:left;"> $QQQ Let the fun times roll....I love a good bottoming indicator! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:36:17 </td>
   <td style="text-align:left;"> $QQQ $SPY $PYPL $TSLA $UVXY History Says Now Could Be A Great Time To Buy Stocks: Here’s Why

https://news.alertsandnews.com/history-says-now-could-be-a-great-time-to-buy-stocks-heres-why/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:36:05 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $BTC.X  can anyone tell me why we rallied so hard in the afternoon today? I was in class and couldn’t check the news or anything, or was is it just a random pump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:36:03 </td>
   <td style="text-align:left;"> $NQ_F $QQQ Once this starts printing blue bars and the weekly cycle turns up we will be forecasting another 10% higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:35:54 </td>
   <td style="text-align:left;"> $SPY $QQQ There’s a lot of globetards on this site </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:35:29 </td>
   <td style="text-align:left;"> $QQQ hey, was the NAZ really up 500?  And after a 250 up day  yesterday? 
 
those guys really set up the bears last week. 
 
vaporized those puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:34:36 </td>
   <td style="text-align:left;"> As per Markets-- The World Economy is fixed and the Bull Market will return thanks to a 0.25BPS $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:33:08 </td>
   <td style="text-align:left;"> $QQQ i cannot even count how much money i made today -- but it also doesn&amp;#39;t feel right to be honest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:33:06 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA $SQQQ  how does anyone believe a word this clown says? He&amp;#39;s lied to our faces countless times, who remembers &amp;quot;inflation is transitory&amp;quot;? 🤡🤣 -Today &amp;quot;Economy is strong &amp;quot; 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:32:47 </td>
   <td style="text-align:left;"> $SPY $qqq $djia at the end of the day, where is the world going to invest? With us. Nobody wants to go long in Europe, Africa, India or Asia. You can gamble there, but you can&amp;#39;t invest. Nobody wants to live in bonds forever. Metals and commodities are for hedging. But investible money will come to America&amp;#39;s equities market because it has NOWHERE else to go. Yeah, rates, I know. So what? We have always had rates except for the past two years.nthe economy is strong. There are jobs. It will take oil and gas to reopen. People can juggle inflation and spending for awhile. It&amp;#39;s a resilient market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:32:45 </td>
   <td style="text-align:left;"> $QQQ  Most important language in Powell!s  comments

“Sharp outlook for inflation” no more transitory or even just plain inflation, “sharp”

“Pared expectations” for economic growth.

Raising  lending rates required to slow inflation is always dangerous  when the economy is slowing

It will all sink in tomorrow and Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:30:59 </td>
   <td style="text-align:left;"> $QQQ Glad I didn’t short this and went long 😅 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:30:40 </td>
   <td style="text-align:left;"> $QQQ at some point we will gap up and NOT fill. It will takes years to fill - if at all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:30:30 </td>
   <td style="text-align:left;"> $SPY instead of 7 rate hikes, Fed should&amp;#39;ve done a full 1% hike today.  Then let the market settle before next hike.   JPOW saying inflation will be under control at the end of 2023 is basically saying &amp;quot;I&amp;#39;m playing politics to position for 2024 presidential election&amp;quot; $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:29:42 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA Incase you missed FMOC today the Fed was hawkish lol Powell repeated the same shyt about Economy is strong which we all know completely bs he&amp;#39;s been saying that all year...  Real Inflation Is around 15%, they haven&amp;#39;t even started reducing the balance sheet. Wait till Fed Mins will be released, reality will sink in.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:29:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
8% inflation 
 
0.25% interest rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:29:20 </td>
   <td style="text-align:left;"> Earningwhispers After Hours Watchlist Part 1 $QQQ $PD $GLG $SPY $YINN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:29:17 </td>
   <td style="text-align:left;"> $QQQ did anyone here make over $350k TODAY? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:29:07 </td>
   <td style="text-align:left;"> $QQQ Still more puts than calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:28:46 </td>
   <td style="text-align:left;"> $QQQ $AAPL $AMD God I hope from the deepest bottom of my heart that those fckin bears who behaved like the first humans lost their money the last days… idc if the market corrects the next days because im long… Just hope that does idiots lost everything. Good Night from Europe Bulls ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:28:24 </td>
   <td style="text-align:left;"> $SPY $QQQ Fantastic Day. More to come, congrats bulls. Locked in some profits and ready for futures $NQ_F $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:27:41 </td>
   <td style="text-align:left;"> $QQQ &amp;quot;Russia’s president said the country’s economy had taken a profound blow from Western sanctions imposed on Moscow for the invasion of Ukraine.&amp;quot; WSJ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:27:41 </td>
   <td style="text-align:left;"> $QQQ wow!!!   Thicc af! 
 
gooooo long! 
 
Bullish baby! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:27:03 </td>
   <td style="text-align:left;"> $SPY  
$QQQ futures ram right into trend line </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:25:31 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
8% inflation 
 
0.25% interest rate 
 
Wall Street celebrates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:24:53 </td>
   <td style="text-align:left;"> $qqq a bahhhtom is NOT a new bull market!   wUtch until YO $zi. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:24:38 </td>
   <td style="text-align:left;"> $QQQ $SPY to those who mistakenly bought puts during the falling knife. May your accounts fade away peacefully </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:24:30 </td>
   <td style="text-align:left;"> $MULN $IWM $QQQ 

https://news.mullenusa.com/financial-website-insider-monkey-names-mullen-automotive-a-top-penny-stock-to-buy-in-march </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:23:53 </td>
   <td style="text-align:left;"> $QQQ add puts tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:23:29 </td>
   <td style="text-align:left;"> $QQQ $SPY Powell convincing investors that the economy is booming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:22:30 </td>
   <td style="text-align:left;"> $QQQ Hahahahahahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:21:19 </td>
   <td style="text-align:left;"> $SPY ... I&amp;#39;m sorry but all is not forgiven... $QQQ $UVXY $IWM $ARKK 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:20:43 </td>
   <td style="text-align:left;"> $QQQ j pow still buying??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-17 05:20:37 </td>
   <td style="text-align:left;"> $QQQ i am going to illustrate how arbitrary prices are to the dear readers of this board: 
 
at the absolute low today MSFT traded at 30x forward PE 
at the absolute high today MSFT traded at 31.4x forward PE 
 
both of these numbers are essentially indistinguishable but losers read into this as being important when in reality it is rounding error </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:50:29 </td>
   <td style="text-align:left;"> $AAPL whooooaaaaa what is futures crashing. Holy shit down 4%. Something high must have just happened. 
💥💥💥💥💥💥💥💥🔥💥💥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:46:03 </td>
   <td style="text-align:left;"> $SPY $UVXY $AAPL $QQQ $TSLA 

The only thing worse than war is complacency. Investors &amp;amp; civilians seem to already be desensitized to the horrors that are going on in Ukraine. Stubborn bulls become low quality steak, remember that… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:43:32 </td>
   <td style="text-align:left;"> $AAPL back in production and buyback!!!!!!
175 tomorrow easy!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:42:58 </td>
   <td style="text-align:left;"> $AAPL 175 tomorrow baby!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:35:58 </td>
   <td style="text-align:left;"> $AAPL 🤝 $MULN 👨‍🚀 
    $AMC $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:34:57 </td>
   <td style="text-align:left;"> $MULN and $AAPl.  🧐🧐🧐🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:32:40 </td>
   <td style="text-align:left;"> $AAPL what is this mullen thing about? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:30:50 </td>
   <td style="text-align:left;"> $NFLX $AAPL  tinyurl.com/2p9e489k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:29:20 </td>
   <td style="text-align:left;"> $MULN Anyone else thinking they make the $AAPL Car ?  I’d so… does anyone think this could hit $100 by Friday regardless? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:26:47 </td>
   <td style="text-align:left;"> $AAPL &amp;amp; $MULN ❤️ 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:26:41 </td>
   <td style="text-align:left;"> $AAPL anything to appl and mullen? CEO.. &amp;quot;no comment&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:24:40 </td>
   <td style="text-align:left;"> $MULN  &amp;amp; $AAPL ❤️ 🇺🇸 

https://mobile.twitter.com/Relentless_8/status/1502199190352707586 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:22:20 </td>
   <td style="text-align:left;"> $MULN make sure to tag $AAPL I&amp;#39;m sure their investors have never heard of us until now! We welcome all new investors 🚀 make sure to keep hitting that bullish button </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:21:31 </td>
   <td style="text-align:left;"> $MSFT let’s goooooo $SPY $MELI $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:17:17 </td>
   <td style="text-align:left;"> $MULN $AAPL 🤝🚀👨‍🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:15:24 </td>
   <td style="text-align:left;"> $AAPL $MULN 🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:11:09 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $MSFT $AMZN being a bear in this market is like the boy who cried wolf. By the time you&amp;#39;re actually right you&amp;#39;ll have no capital left to short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:09:14 </td>
   <td style="text-align:left;"> $AAPL weird havn t seen one comment about futes tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:08:51 </td>
   <td style="text-align:left;"> $SPY $AAPL finally broke our, lets see what tomorrow brings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:08:41 </td>
   <td style="text-align:left;"> $MULN hearing rumors of $AAPL buyout 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:08:29 </td>
   <td style="text-align:left;"> $AAPL 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 08:00:44 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $160.0 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:58:37 </td>
   <td style="text-align:left;"> $MULN the beast is awakening……. $TSLA $SPY $AAPL  $AMC  check it out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:53:25 </td>
   <td style="text-align:left;"> $AAPL I said yesterday $160 EOD today.  Pretty close huh?  Well $165 EOD tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:51:58 </td>
   <td style="text-align:left;"> $AAPL nice 170 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:42:19 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $TQQQ $NVDA 
Hope everyone enjoyed the ride today before SPY hits $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:40:11 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $BTC.X $FB  

The destruction of the planet is priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:39:31 </td>
   <td style="text-align:left;"> $IBM Big blue is a sleeping monster; but sometimes he wakes up and roars high! $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:38:49 </td>
   <td style="text-align:left;"> $AAPL get this nagging feeling that some shitty news gonna pop up which will clean up all the gains in the last two day, hope I&amp;#39;m wrong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:32:23 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $DIA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:22:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  I know it isn&amp;#39;t the best but my entire portfolio is 90%. Appe. Approx. $900,000k Safest stock in entire market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:22:03 </td>
   <td style="text-align:left;"> $AAPL is it me or is Apple dumping now? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:06:55 </td>
   <td style="text-align:left;"> $AAPL  $BA  $AMZN    |  go.trade-ideas.com/SHDf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:05:58 </td>
   <td style="text-align:left;"> $AAPL markets unfortunately dump whenever Webull gives this stock away for free. Caution. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:04:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $MSFT 
As a foreigner, this is the big problem America
: &amp;#39;Sesquipedalian speech&amp;#39;

White men BSing with all the jargon words at work. 
WTH was the &amp;#39;Tool&amp;#39; and &amp;#39;Framework&amp;#39; that J. Pow kept referring?  
I am sure he can keep his job with that for  now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:03:49 </td>
   <td style="text-align:left;"> $AAPL Quadruple Witching Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:03:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:01:15 </td>
   <td style="text-align:left;"> $MULN $AAPL 🚗🍏🧑‍💻👩‍💻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:01:07 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA 

I just bought puts at the bell just in case what they talking. About really happens. Nothing else to report here that’s all. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:00:42 </td>
   <td style="text-align:left;"> $AAPL history says puts is the place to be heading into quad witching Friday. hedge funds are prob turning over, but I would watch for a rug pull with naz up 5% in 2days. bullish going into spring and summer though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 07:00:08 </td>
   <td style="text-align:left;"> $MULN $AAPL 

“Are you in talks with Apple for partnering with an EV?” 

“No comment” ⚡️🔋

I love rumors, especially when they seem possible 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:55:20 </td>
   <td style="text-align:left;"> $SPY omg if it tumbled over night like it did today look out below $AAPL $QQQ $SPX 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:53:58 </td>
   <td style="text-align:left;"> $AAPL tmrw puts will print hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:52:51 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. High Volume Options... 👀 👀  $160 Call for Friday, March 18. Roughly 18 Million dollars! 💰💰💰 BIG MONEY 💰💰💰 Learn more on StockOrbit at https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:51:00 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 72.1K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:50:27 </td>
   <td style="text-align:left;"> $AAPL strong resistance at 160…break by Friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:50:07 </td>
   <td style="text-align:left;"> $AAPL anyone know how far this is about to drop? $SPY $SPX $QQQ  ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:47:38 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Earnings catching up quick! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:47:33 </td>
   <td style="text-align:left;"> $AAPL like how far is this going to drop?

7 rate hikes 4x’s more than most expected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:40:54 </td>
   <td style="text-align:left;"> $SPY
$AAPL $TSLA $BABA 

WTF:  Win The Fund by setting up good trades!

💎💯🐅👐💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:39:41 </td>
   <td style="text-align:left;"> $AAPL tomorrow back to $165.00. Institutions are driving this up. Retail short fucks get humble pie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:38:12 </td>
   <td style="text-align:left;"> $MULN any mention of $AAPL  will send this over $10 ! 🚀🚀🚀🚀 even if they peak interest MOON ! make a deal MARS  ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:35:31 </td>
   <td style="text-align:left;"> $AAPL 

bears have ZERO fear bulls, your weak pumps don’t scare us.😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:34:19 </td>
   <td style="text-align:left;"> $AAPL still weak in my opinion... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:33:24 </td>
   <td style="text-align:left;"> $AAPL I don’t think things are gonna and well for Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:33:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AAPL remember… you saw it here first. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:32:48 </td>
   <td style="text-align:left;"> $AAPL just keep buying just keep buying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:30:56 </td>
   <td style="text-align:left;"> $AAPL A $200 stock trading for $160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:26:50 </td>
   <td style="text-align:left;"> $AAPL up or down tomorrow? Will latexdb284500d4b1c14a4d5856f996c542b7AAPL March latexc6f508bba014a7d5449a51c35f706453AAPL March latexa0fa1a5978832842ca51b250ae958791AAPL March latexeb902da81644cdd7088a581df4e0f745AAPL March latexfdc31424f6b2b87efafbf62d7cab90ffAAPL March latexd09c5213f9f7f98d141c6fdd9f38fb83TSLA March latex5869e243d45b2c6171ef5822ecc39709AMD March latex662f62d26eccd61056fe5b829b998cfcAAPL March latex5c10db6d0abf9c106a44cd495b0019ceBABA March latexc9108950f1ccf9c314481c08e3cbab49BAC March latexa255392fc20204a56bdd29d3a8e74da0BABA 1.131m (73% call/27% put)
$NVDA 852k (60% call/40% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:20:42 </td>
   <td style="text-align:left;"> $GOOGL  bears got obliterated today 🤣 told y’all rate hikes would be a buy the news event new all time highs before summer $SPY $AAPL $TSLA $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:15:13 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : 7 Tech Stocks Hitching Their Wagon to Web 3.0 https://www.stck.pro/news/AAPL/24507012 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:05:16 </td>
   <td style="text-align:left;"> $AAPL these will print tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:01:53 </td>
   <td style="text-align:left;"> $MULN $NVDA $AMD $AAPL $TSLA 

💸🚀💸 T I M E   F O R   T A K E O F F 💸🚀💸
 🛸🚀💰🚀💰🚀💰💎💰🚀💰🚀💰🚀🛸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 06:00:14 </td>
   <td style="text-align:left;"> $MULN So $AAPL might be involved? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:59:14 </td>
   <td style="text-align:left;"> $AAPL $160 and beyond. It will be $160 friday $165 next Week. Could revisit $170 next week before coming back down some imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:58:39 </td>
   <td style="text-align:left;"> $AAPL 155 open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:56:41 </td>
   <td style="text-align:left;"> $AAPL I am buying a new Green Iphone this week. Huge earning call boost! hope to not sold out soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:53:53 </td>
   <td style="text-align:left;"> $SPY $AAPL but for real, wanna know what I bought today? Bahahahah, I’m on my way to Wendy’s.  Lesson learned.  Meet me there. Cash only. Oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:53:31 </td>
   <td style="text-align:left;"> $BTC.X get on the train $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:51:44 </td>
   <td style="text-align:left;"> $SPY $AAPL me and my 7 followers did well today. We made a combined total of 12.00 dollars.  That’s right Bitches. Follow me and your guaranteed to make (lose) tons of money. Do the opposite of what I do. Jk…not really.  Word of the day oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:48:41 </td>
   <td style="text-align:left;"> $MULN It seems like the $AAPL question came out of the blue....has anyone else heard rumours about this...honestly there very well could be a connection here...low(er) market cap than them trying to partner/buy Rivian or Fisker etc....One would think that there still might be a connection between Dre and Michery and in turn with Apple.....who knows...wilder things have happened...admittedly the NO COMMENT response was striking and normally I dont fall for this bullcrap.  I would think the ambiguity with the question and answer HAS to have investors thinking.....$2.50 tomorrow (fingers crossed) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:46:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA ⛔️⛔️⛔️⛔️⛔️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⛔️⛔️⛔️☢️☢️☢️☣️☣️☣️ IS GOING TO GET UGLY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:46:22 </td>
   <td style="text-align:left;"> $AAPL Ends the day with a strong candle breaking the swing high VWAP outside channel resistance 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:45:37 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ  After tons of T/A and a few calls to a hedge fund friend.  I got a great look at what’s happening tomm. I posted my predictions on my comment
Page about 15 or so posts below. You might have to scroll through to see the comment. Given the feed was moving fast. It’ll give you an in-depth look at whats hedge funds are blocking tomm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:40:29 </td>
   <td style="text-align:left;"> $SPY $AAPL i officially changed the sentiment.  My job is done here boyz and ladies.  The dump tomm will be spectacular .  Oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:38:42 </td>
   <td style="text-align:left;"> $SPY $AAPL welp I’m headed to Wendy’s. (Not for food) right now.  20 is 20. I fucked up.  Still….oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:37:22 </td>
   <td style="text-align:left;"> $AAPL today Was a roller coaster ride. LFG! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:36:09 </td>
   <td style="text-align:left;"> $BABA $NIO $TSLA $AAPL too tech heavy? Tell me again in 10 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:35:36 </td>
   <td style="text-align:left;"> $AAPL crazy how sentiment can change so quickly. Everyone was expecting this to die just 2 days ago, and now everyone is bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:35:03 </td>
   <td style="text-align:left;"> 🔥RISK ON🔥 EP. 199 MARCH 16th 2022 .. 50:53 Time Mark .... You Tube podcast ...

 Mullen Technologies .. $MULN ..
🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸 $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:33:02 </td>
   <td style="text-align:left;"> $AAPL $SPY i dont even know why I’m doing this, I’m not in either spy or apple. I have calls on RSX for this week. 🚀🚀🚀🚀🚀🚀💥💥💥💥💥 oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:31:24 </td>
   <td style="text-align:left;"> $AAPL NOT ONLY DO I want my money back from u bears ai want an additional 5% for the emotional distress u caused me for the last month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:30:26 </td>
   <td style="text-align:left;"> $SPY $AAPL I went on a date last week. Told the girl I was an ape and had diamond hands.  She never called me back.  Oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:29:56 </td>
   <td style="text-align:left;"> $AAPL what is not to like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:29:41 </td>
   <td style="text-align:left;"> $AMZN $AAPL $MSFT $AAPL $FB $GOOG Congratulations to everyone who bought the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:28:46 </td>
   <td style="text-align:left;"> $QQQ $AAPL $AMD God I hope from the deepest bottom of my heart that those fckin bears who behaved like the first humans lost their money the last days… idc if the market corrects the next days because im long… Just hope that does idiots lost everything. Good Night from Europe Bulls ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:26:01 </td>
   <td style="text-align:left;"> $SPY $AAPL overbought/oversold, poootin says fuck your calls.  Oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:21:58 </td>
   <td style="text-align:left;"> $SPY $AAPL im super sad, I totally got fucked today. Not from stocks, my uncle.  Oversold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:18:21 </td>
   <td style="text-align:left;"> $MULN So there is a possibility of $AAPL being involved? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:17:56 </td>
   <td style="text-align:left;"> $SPY $AAPL what a day.  Oversold. Dumping, futs are dark red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:17:49 </td>
   <td style="text-align:left;"> $MULN  
 
If $AAPL is looking for an EV partner to place their screen system it will be $MULN, everything makes sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:16:09 </td>
   <td style="text-align:left;"> $NIO listen to this bear where does $tsla and $aapl sell their 
 merchandise (CHINA) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:16:07 </td>
   <td style="text-align:left;"> $SPY $AAPL you bought calls and didn’t close them out.?? Yikes…oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:15:15 </td>
   <td style="text-align:left;"> $SPY $AAPL Putin agrees , oversold and will make sure to dump it tomm. …oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:14:25 </td>
   <td style="text-align:left;"> $AAPL   🍏  “Remember”, the next FOMC Meeting, is May 3-4.  That’s right…no April Meeting.  Trade smart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:13:59 </td>
   <td style="text-align:left;"> $SPY $AAPL you just got diabetes and jungle foot . Oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:13:30 </td>
   <td style="text-align:left;"> $AAPL 170 tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:13:15 </td>
   <td style="text-align:left;"> $SPY $AAPL fat person custom oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:13:01 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $NIO $TSLA   🔴🔴🔴🔴REMEMBER HE JUST SENDING THE MESSAGE. The war is going to get worse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:12:34 </td>
   <td style="text-align:left;"> $SPY $AAPL  big and tall oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:12:28 </td>
   <td style="text-align:left;"> $AAPL 💪🏽💪🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:12:25 </td>
   <td style="text-align:left;"> $SPY Give it up for the greatest president in history of the world 😎bow and suck it....
$AAPL $QQQ $TSLA $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:12:10 </td>
   <td style="text-align:left;"> $SPY 515 $AAPL $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:12:10 </td>
   <td style="text-align:left;"> $AAPL $165 EOD tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:11:59 </td>
   <td style="text-align:left;"> $SPY $AAPL xxl oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:11:36 </td>
   <td style="text-align:left;"> $AAPL Soooo closeeee… Gimmeee gimmeee. 🤗🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:11:35 </td>
   <td style="text-align:left;"> $SPY $AAPL  xtra oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:10:54 </td>
   <td style="text-align:left;"> $AAPL 200$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:10:51 </td>
   <td style="text-align:left;"> $SPY $AAPL oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:09:07 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $160.0 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:07:41 </td>
   <td style="text-align:left;"> $AAPL Still got it. Target 🎯 🍏 Swinging calls/puts day in and day out over night. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:06:41 </td>
   <td style="text-align:left;"> $SPY Loading puts here, don&amp;#39;t buy the top $AAPL $AMZN $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:03:35 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Congrats: If you are reading this post, you made it through another market day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 05:02:27 </td>
   <td style="text-align:left;"> $aapl $googl $amzn the generals that will lead the mkts back to new highs https://youtu.be/0eQKLiIDugI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:59:46 </td>
   <td style="text-align:left;"> $AAPL Another day of gains if you
followed congratulations. Like I say
technicals always work. For 3 weeks I
have been posting here I didn&amp;#39;t post it
on Stocktwits before that.I post it in my
group But you can see how targets are
hit and most retailers lost because they
trade emotionally. Haters can keep
hating me for helping everyone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:58:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:55:25 </td>
   <td style="text-align:left;"> Not sure why we rallied after the #Fed? Check out the preview vid I shared last night on youtube 
 
So far has played out pretty on point. Hawkish tone from the fed (more than id thought w/ 7 hike potential) and relief rally from oversold bear sentiment  
 
https://youtu.be/vU6h0TCcmFc 
 
$TSLA $AMZN $AAPL $BABA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:53:14 </td>
   <td style="text-align:left;"> $AAPL New measures aimed at China could be included in the legislation https://www.marketwatch.com/story/nothing-is-off-limits-as-congress-prepares-sweeping-new-russia-sanctions-bill-analyst-says-11647463008?mod=mw_latestnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:51:44 </td>
   <td style="text-align:left;"> $BTC.X $TSLA $AAPL $SPY $DJIA  
everybody made lots of money in the market today 
lets all go buy some more bitcoin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:50:30 </td>
   <td style="text-align:left;"> latexd9d79174d4b218e467c739936fae0ac4QQQ$SQ $AAPL loving these leap plays compared to daytrades . You can breath more and allow the stock to do what its go do. Definitely suggest playing leaps 6mos out or even a year. If you can sustain the points where you are significantly down. 👍🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:49:06 </td>
   <td style="text-align:left;"> $AAPL u bers better of took good care of my money because Daddy wants it back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:48:11 </td>
   <td style="text-align:left;"> @crgars $AAPL is $ BRK-A biggest holding.

But as George Washington University professor Lawrence Cunningham points out in the article, &amp;quot;Concentration has never worried them. They’ve been happy to have big percentages in just a handful of stocks.&amp;quot;
 
And Edward Jones analyst James Shanahan notes that &amp;quot;they needed to get more exposed to tech and if you take a higher-level view, the Apple exposure isn’t particularly outsized relative to the (operating) businesses,&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:47:44 </td>
   <td style="text-align:left;"> $AAPL let’s see this back at $120! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:47:13 </td>
   <td style="text-align:left;"> $PLTR $AAPL $LTC.X Stonks are ripping!!! Same with crypto. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:46:50 </td>
   <td style="text-align:left;"> $SPY geez  took an hour nap and woke up to the moooon  $AMD $AAPL $MSFT 
🚀🚀🚀🚀
510 eoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:43:43 </td>
   <td style="text-align:left;"> $AAPL there is no bearish with Apple. 

It’s a life stock, add and hold, add and hold, until retirement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:41:49 </td>
   <td style="text-align:left;"> $HCMC this company WILL be worth more than both $MSFT and $AAPL combined, even if it means losing my virginity 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:41:06 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:40:33 </td>
   <td style="text-align:left;"> $AAPL mumbling idiot Carter Worth called for $138 last friday, show some doodle lines on his chart. remind me to do the opposite of every one of these shills on cnbc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:39:17 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $IWM &amp;quot;U.S. economy is strong&amp;quot; (induced long term economic recession on its way) - Powell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:38:23 </td>
   <td style="text-align:left;"> $AAPL I let this market fake me out too many times . Not this time . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:37:38 </td>
   <td style="text-align:left;"> $SPY yeah they all popped off at 2:39
Except for $AAPL 
Gotta gave the right tools in your tool box for the job right? Algorithms work my friends
I believe in data </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:36:11 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 352.1K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:33:30 </td>
   <td style="text-align:left;"> $TSLA $AAPL keep it coming 🚀🤙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:33:12 </td>
   <td style="text-align:left;"> $DG Soon entire Americans will be shopping here. Thanks to fcking Brandon pos. $AAPL $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:31:43 </td>
   <td style="text-align:left;"> $AAPL me RN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:31:07 </td>
   <td style="text-align:left;"> Here are the two leading indicators that signal a market bottom. 
 
WATCH; https://youtu.be/0RpAym2XJ_c 
 
$AMZN $AAPL $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:29:02 </td>
   <td style="text-align:left;"> $AAPL whats bullish though. Nothing is bearish either truth be told but whats so bullish? They said 7 rate hikes, they said they are open to 50 point hike if need be, Russia still isnt backing off. 
Here is whats different: 
- China QE ? If they follow through, sure but why are American markets a WHOLE ripping? Its still in lockdown. Oil is cheap only because of that. Russia can of worms suddenly closed?
- Leverage got costlier. Over leveraged firms, what will they do? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:27:21 </td>
   <td style="text-align:left;"> $MULN MJF likes Mullen EV 
 
$AAPL $OCGN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:26:33 </td>
   <td style="text-align:left;"> $AAPL they opened the factory in Shengen.  Gonna be a decent bounce tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:24:28 </td>
   <td style="text-align:left;"> $AAPL 1hr view from 3/06 weekend update presented to members at elliottwave-forecast.com/ #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:23:43 </td>
   <td style="text-align:left;"> $AAPL    🍏 Surge in Volume, into the Close:  94.3 Million AAPL Shares, traded on the Day.  In the “final second” of Close, 11.4 Million AAPL Shares traded to the “Buy Side”.  Very strong, Close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:23:40 </td>
   <td style="text-align:left;"> $AAPL last minute pump of over 60/70 points. Kinda insane isnt it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:21:58 </td>
   <td style="text-align:left;"> $SPY 
$AAPL blocks at 155 .. 1.3million shares
Boom .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:20:14 </td>
   <td style="text-align:left;"> $AAPL @BankofEngland Just checking in, which month will apple hit 100? Start of summer? Mid summer? Maybe when it splits again summer of 2024 🤡🤡🤡🤡🤡🤡🤡🤡🤡🤡🤡🤡🤡🤡🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:20:01 </td>
   <td style="text-align:left;"> $SPY 500% gains on puts and 170%+ on calls in our free #DayTrading chat. Follow @LordofOptions. See our previous tweets and results. https://t.co/BOUqQStb6n

$SPY $SPX $AAPL $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:19:31 </td>
   <td style="text-align:left;"> $SPY I made easy 6K on spy calls within 40 min, bought after gap filled. I definitely know how to trade spy! Follow me on Instagram (@itsatradingdiary), to wach how I trade every day. $AAPL $NVDA 

https://instagram.com/itsatradingdiary?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:18:27 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 3/06 weekend update presented to members at elliottwave-forecast.com/ #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:18:05 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL  wow, guess bears didn’t see that coming. “But what about rising interest rates”???  😂 
IMO tho, $QQQ should pull back alittle by Friday.  So get ready bears.
I am only BULLISH on AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:17:57 </td>
   <td style="text-align:left;"> $AAPL 

Not surprised .. what a crazy pumping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:14:42 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $AAPL ya’ll can thank me and the feds for this pump! You’re welcome! 🦍🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:14:29 </td>
   <td style="text-align:left;"> $aapl this is ridiculous really lmao. doesnt make sense at all. as ridiculous as the 2 day drop to 150 lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:11:49 </td>
   <td style="text-align:left;"> $AAPL 4hr view from the 2/27 weekend update. Calling for a move lower towards blue box area where buyers are expected to appear #elliottwave #trading #apple #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:11:44 </td>
   <td style="text-align:left;"> $MSFT $AAPL $NVDA $GOOGL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:11:16 </td>
   <td style="text-align:left;"> $SPY $AAPL  I lost like 1300 since the beginnings of the week on Apple.  But I got almost all of it back. Nothing against apple but I’ll never touch this stock again. It’s so heavily manipulated that it’s almost impossible to make a sound decision on it. It’s a day traders dream and treated like a penny stock. Plus I have decided not to invest in Chinese stocks anymore.  Apple is not Chinese but all of its manufacturing  is done there so it’s subject to world wide economics.  I’m going all American. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:09:33 </td>
   <td style="text-align:left;"> $TSLA $AMZN latex6eadf3119459793c657a95b82f659fb3TSLA Long@ 834.96  Target @920.50 Stop Loss 799.11 
Sold on 840.10 
$GOOG Long@ 2655.99 Target @2710.61 Stop Loss 2590.11 
Sold on 2675.55 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:09:05 </td>
   <td style="text-align:left;"> $AAPL how are these looking? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:08:48 </td>
   <td style="text-align:left;"> $AAPL still not enough for my calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:08:19 </td>
   <td style="text-align:left;"> $AAPL  
 
https://www.tradingview.com/chart/AAPL/LNigqdxH-APPLE/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:06:00 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:05:47 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 2/20 weekend update presented to members at elliottwave-forecast.com/ called for a double correction lower to take place #elliottwave #trading #apple #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:05:45 </td>
   <td style="text-align:left;"> Finished the day with 9 Wins &amp;amp; 1 Loss: 
 
$BABA - 85 puts at $1.99 went to  $2.50 - Win 
 
$AAPL - 155 puts at $1.38 - .80 - Loss 
 
$SPY - 432 puts at $2 went to 2.28 - Win 
 
$SPY - 432 puts at $2.04 went to $2.49 - Win 
 
$SPY - 432 puts at $2.40 went to $3.18 - Win 
 
FOMC $SPX Strangle - 4265 puts at $4.50 went to $15.20 - Win 250%+ 
                                              4355 calls at $4.70 went to $5.30  
 
$SPX 4240 puts at $4.05 went to $10.70 - Win 150%+ 
 
$SPX 4270 puts at $4.40 went to $6.20 - Win 
 
$SPX 4290 puts at $4 went to $8.20 - Win 100%+ 
 
$SPX 4320 puts at $2.60 went to $5.30 - Win 
 
Great day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:05:25 </td>
   <td style="text-align:left;"> $AAPL 200 in no time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:04:59 </td>
   <td style="text-align:left;"> $AAPL   🍏 Sweet Green AAPL Soldiers”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:04:14 </td>
   <td style="text-align:left;"> $AAPL stonks go up when I talk bearish. I&amp;#39;ll keep doing that until nasdaq reaches 20000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:04:06 </td>
   <td style="text-align:left;"> $AAPL Strong close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:03:57 </td>
   <td style="text-align:left;"> $AAPL lmaooo Fear is one hell of a drug. Long and secured 🍆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:02:01 </td>
   <td style="text-align:left;"> $AAPL  🍏😁! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:01:44 </td>
   <td style="text-align:left;"> $AAPL tomorrow she will fill that gap &amp;amp; end $163 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:01:33 </td>
   <td style="text-align:left;"> $AAPL now I need to wake up to $163 at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:01:09 </td>
   <td style="text-align:left;"> $AAPL Fake pump, sell it off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:01:04 </td>
   <td style="text-align:left;"> $AAPL we hit that $159 🎉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:01:02 </td>
   <td style="text-align:left;"> $UUP dear bear keep dollar on short watchlist Thx $SPY $TSLA $AAPL $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:00:35 </td>
   <td style="text-align:left;"> $AAPL jesus christ. Bears got raped in the last 5 minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 04:00:09 </td>
   <td style="text-align:left;"> $SPY fuck $AAPL  is going parabolic. !!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:58:04 </td>
   <td style="text-align:left;"> $BABA baba will hit 120 to 150 tomorrow, entire wall street and china are buying it! the most undervalued stock in the planet 
 
$SPY $AAPL $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:58:01 </td>
   <td style="text-align:left;"> $AAPL I hope it runs I really do need that short high af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:56:51 </td>
   <td style="text-align:left;"> $AAPL 230 by next earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:56:39 </td>
   <td style="text-align:left;"> $AAPL    🍏  😎👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:56:09 </td>
   <td style="text-align:left;"> $AAPL can we squeeze $159 for the close???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:55:57 </td>
   <td style="text-align:left;"> $AAPL 🐻 market is ova!!! BTMFDs in effect! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:55:42 </td>
   <td style="text-align:left;"> $AAPL I knew that this will run after the meeting, it happened again last week. After being down almost 70 percent of my calls, I sold all of them and came out making extra money for my losing puts 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:55:05 </td>
   <td style="text-align:left;"> $AAPL New Iphone, Air Mac are coming this Friday! with long line up in Asia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:54:10 </td>
   <td style="text-align:left;"> $SPY $AAPL we’ll see how it holds tomorrow. Usually everything dumps the day after any fed meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:53:39 </td>
   <td style="text-align:left;"> $AAPL I wish it crosses $164 next , but what do you guys think of the quad witching tomorrow ? Hope it doesn’t cause a spike down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:51:19 </td>
   <td style="text-align:left;"> $AAPL if we hit $167 tomorrow I’ll buy someone a iPhone lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:51:17 </td>
   <td style="text-align:left;"> $AAPL +2.49% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:49:39 </td>
   <td style="text-align:left;"> $AAPL 170 incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:49:14 </td>
   <td style="text-align:left;"> $SKLZ skillz cloud will get the big boys excited. $MSFT $FB $AAPL if I was @andrewparadise, I’d host the skillz cloud on all of them. Apple arcade makes a lot of sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:48:57 </td>
   <td style="text-align:left;"> $SPY avg down on puts complete - i am jacked to the tits now - please drop $AAPL $MSFT  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:48:52 </td>
   <td style="text-align:left;"> $MSFT $QQQ $AAPL $AMZN vix collapsed below 26.5… tomorrow its gonna be epic rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:48:09 </td>
   <td style="text-align:left;"> $AAPL we broke that $158.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:46:59 </td>
   <td style="text-align:left;"> $AAPL Bears will cry themselves into sleep today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:46:05 </td>
   <td style="text-align:left;"> $AAPL bears in denial. give em time, they will be bull. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:45:42 </td>
   <td style="text-align:left;"> $AAPL we see limit up!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:43:58 </td>
   <td style="text-align:left;"> $AAPL They seem to be missing in action on this board today 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:42:46 </td>
   <td style="text-align:left;"> $AAPL Biden calls Putin a war criminal. Reactionary sanctions by Putin will be imminent. How does a nation recover by severing ties this intensely? What happens if Ukraine agrees to a ceasefire? Will Putin still be called a war criminal ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:42:12 </td>
   <td style="text-align:left;"> $AAPL lottos in play https://twitter.com/StChixinc/status/1504180990394130434?s=20&amp;amp;t=PxbMuWA-A0Aje49pWjmrvQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:40:51 </td>
   <td style="text-align:left;"> $AAPL $TQQQ $SOXL $TSLA 
&amp;quot;Balance sheet reduction to be discussed 3 weeks after. April  6&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:40:49 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:40:39 </td>
   <td style="text-align:left;"> $AAPL close below 157.5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:39:32 </td>
   <td style="text-align:left;"> $AAPL let’s go my calls coming back to life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:37:54 </td>
   <td style="text-align:left;"> $AAPL $FB $GOOGL something is not right with the price action today. We will see tomorrow if the bottom is in or just a bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:37:46 </td>
   <td style="text-align:left;"> $AAPL wish we were leading FAANG not following it but I’ll take this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:37:30 </td>
   <td style="text-align:left;"> $FB $CRSR $AAPL What a wonderful day...!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:36:49 </td>
   <td style="text-align:left;"> $SPY $AAPL locked and loaded on puts expiring friday 🙇‍♂️🔥🤟🤮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:36:33 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $SOXL $TQQQ 
Fed said, &amp;quot;Aggresive tightening&amp;quot;
Why so bullish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:36:33 </td>
   <td style="text-align:left;"> $CHPT $SOFI $FUBO $SPY $AAPL 
Buy the ticket 🎫 take the ride 🎢 
This is bat 🦇 country </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:35:10 </td>
   <td style="text-align:left;"> $DJIA  $SPY $ND_F $AAPL  
10% inflation going to 30% 
everything to the moon 
Fed has lost control and will backstop market on any and all drops 
Dow 100k by end of Jun 
zimbabwe 2.0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:35:07 </td>
   <td style="text-align:left;"> $AAPL bears.    Fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:34:58 </td>
   <td style="text-align:left;"> $SPY $AAPL has to drop, no way this is organic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:34:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  So that&amp;#39;s it? Selling is over and we&amp;#39;re about to go to all time highs again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:34:17 </td>
   <td style="text-align:left;"> $AAPL 

Final massive marketwide pumping to the close of Day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:31:20 </td>
   <td style="text-align:left;"> $AAPL average size is a dollar of these 4 candles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:31:19 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AMZN $AAPL 
Who bought puts on that dip? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:30:47 </td>
   <td style="text-align:left;"> $AAPL  
 
Let&amp;#39;s end this day green for AAPL! 
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=pw_20220316 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:30:41 </td>
   <td style="text-align:left;"> $AAPL Clowns need to read the charts, and Stop believing in fairytales.Last weeks resistance was $167.00 . Dumb money  late as usual to the party .. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:30:25 </td>
   <td style="text-align:left;"> $AAPL this is going to dump … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:29:45 </td>
   <td style="text-align:left;"> $AMD $AAPL $MSFT $GOOG Now the question becomes, do we get follow through tomorrow? 
If we do, I&amp;#39;m adding more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:28:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

But yet nothing was able to break the high of day... interesting...🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:28:42 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. High Volume Options... 👀 👀  $160 Call for Friday, March 18. Roughly 6 Million dollars! 💰💰 WOAH 💰💰 Learn more on StockOrbit at https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:28:24 </td>
   <td style="text-align:left;"> $AAPL 🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:28:07 </td>
   <td style="text-align:left;"> $AAPL $159 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:27:50 </td>
   <td style="text-align:left;"> $AAPL haha y&amp;#39;all know ping pong right going down!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:27:47 </td>
   <td style="text-align:left;"> $AAPL bears watching the charts like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:27:46 </td>
   <td style="text-align:left;"> $BTC-X Btc hungry! $TSLA $AAPL $AMZN $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:27:39 </td>
   <td style="text-align:left;"> $AAPL phew!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:27:00 </td>
   <td style="text-align:left;"> $AAPL 170 by next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:26:55 </td>
   <td style="text-align:left;"> $AAPL when Russia Ukraine ends this will rocket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:26:55 </td>
   <td style="text-align:left;"> $AAPL only up 2% while $BABA 37% 😂😂😂😂garbage USA companies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:25:24 </td>
   <td style="text-align:left;"> $AAPL  seize fire on friday and this will rip your faces off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:25:05 </td>
   <td style="text-align:left;"> $AAPL🔥🔥🔥✈️ insane turn around shooting for 158.50 cross 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:25:05 </td>
   <td style="text-align:left;"> $AAPL $NVDA $AMD $TSLA $BABA 

    🚀🟢🚀J U S T    B E A U T I F U L 🚀🟢🚀
 💎💰💎💰💎💰💎👑💎💰💎💰💎💰💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:24:47 </td>
   <td style="text-align:left;"> $AAPL wish j got in at the 151.x on Monday I called the plant shutdown baloney </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:24:32 </td>
   <td style="text-align:left;"> $AAPL where all the bears at? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:24:29 </td>
   <td style="text-align:left;"> $AAPL nice!!! Flippers about to flip! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:24:07 </td>
   <td style="text-align:left;"> $AAPL 

💰📲💰📲💰📲💰📲💰📲💰📲💰

$165+ tomorrow and I’ll buy a new iPhone 

📲💰📲💰📲💰📲💰📲💰📲💰📲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:24:00 </td>
   <td style="text-align:left;"> $AAPL damn that drop really fucked calls. Glad that’s not my game! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:23:55 </td>
   <td style="text-align:left;"> $AAPL where’s those $155 puts at? And those $150 price targets?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:23:45 </td>
   <td style="text-align:left;"> $AAPL I like it but let’s rally to 180 again. I need it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:23:24 </td>
   <td style="text-align:left;"> $AAPL short at the close. This is very hawkish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:23:05 </td>
   <td style="text-align:left;"> @Dr_Stockenstein $AAPL You doing good bro? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:23:02 </td>
   <td style="text-align:left;"> $AAPL More minutes to go! not far from $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:23:01 </td>
   <td style="text-align:left;"> $AMD CEO Dr. @LisaSu recently spoke at the AMD Women&amp;#39;s Forum to discuss how we are #BreakingTheBias. 
We want to recruit, retain and promote women through impactful programming and advocacy. 
Learn more about our AMD Women&amp;#39;s Forum.

&amp;gt;https://www.amd.com/en/corporate-responsibility/diversity-belonging-inclusion

$AAPL $INTC $MSFT $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:22:43 </td>
   <td style="text-align:left;"> $AAPL no where near as hawkish as the open statement seemed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:22:20 </td>
   <td style="text-align:left;"> $AAPL 160+ plz 165 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:21:29 </td>
   <td style="text-align:left;"> $AAPL $160 close? $165 end of week Doable imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:21:15 </td>
   <td style="text-align:left;"> $AAPL if this closes near 160$ I will smoke crack for real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:20:29 </td>
   <td style="text-align:left;"> $AAPL brrrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:19:34 </td>
   <td style="text-align:left;"> $AAPL um nothing warrants a move this green tho lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:19:09 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $AMD America Will be fine! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:18:32 </td>
   <td style="text-align:left;"> $AAPL will close HOd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:17:41 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY $AAPL $AMZN surely y’all realize now that I’m not here to just hear myself talk.. I’m not some one sided spammer that just posts me I support their position. I makes my positions support my posts. Not many people like that on @Stocktwits. Follow along, most people charge for this shit. 🤜🏻💥🤛🏻 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:17:31 </td>
   <td style="text-align:left;"> $AAPL bought 30 calls at the bottom what a time to be alive already up 55% 
Next week this will hit 170 easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:17:19 </td>
   <td style="text-align:left;"> $AAPL brutal haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:16:07 </td>
   <td style="text-align:left;"> $AAPL $SPY $TSLA the ones who try to outsmart the market are my favs. Just trade the trend and cry on your personal time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:16:02 </td>
   <td style="text-align:left;"> $GOOGL dovish fed meeting, were going to fly the rest of the year $SPY  $AAPL  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:15:59 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:15:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $TQQQ $AAPL The market is scared over the same news every week lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:14:45 </td>
   <td style="text-align:left;"> $AAPL $SPY back to $5 up. A truly manipulated day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:12:48 </td>
   <td style="text-align:left;"> $NIO should be trading $25 / $30 range , will hold thru weekend! $MULN $TSLA $AAPL $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:12:47 </td>
   <td style="text-align:left;"> $AAPL 158 coming…? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:12:28 </td>
   <td style="text-align:left;"> $AAPL $200 a Share it’s my money &amp;amp; I want it now 
Signature Here  X___ J G Wentworth _______ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:11:02 </td>
   <td style="text-align:left;"> $AAPL guess bears forgot everything was priced in 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:10:55 </td>
   <td style="text-align:left;"> $FB $AAPL $TSLA $AMZN Over $500+ MILLION  in premium traded in the dark pools for each name </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:10:41 </td>
   <td style="text-align:left;"> $AAPL those with their portfolio bleeding to death, wondering what is safe  
 
Check out the article via @TipRanks below, makes a good bull case in 1 of the worst trading environments we&amp;#39;ve had in a while. 
 
$SPY $QQQ  
 
https://www.tipranks.com/news/article/apple-stock-safe-pick-amid-geopolitical-risks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:09:08 </td>
   <td style="text-align:left;"> $AMZN  $AAPL $JNK $LQD XLE C EEM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:08:16 </td>
   <td style="text-align:left;"> $AAPL 

The shorts are retreating due to improving situation ..  on many fronts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:07:34 </td>
   <td style="text-align:left;"> $AAPL Powell is a CUCK, a real tool for Brandon Bears 🐻 brigade ..betting against America would have triple your money 💰 😒 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:07:06 </td>
   <td style="text-align:left;"> $AAPL dumb retail bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:06:58 </td>
   <td style="text-align:left;"> $AAPL 🤦🏼🤦🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:05:32 </td>
   <td style="text-align:left;"> $AAPL bears are you ok? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:05:15 </td>
   <td style="text-align:left;"> $AAPL 🚀💵💵💰💰💰💵💵💵🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:04:33 </td>
   <td style="text-align:left;"> $SPY those of you not watching the FED meeting with J Powell. The summary is &amp;quot;we will use TOOLS&amp;quot; WHICH THEY HAVE BEEN SAYING SAME SHIT FOR 28284X TIMES. Nothing to see here. Just FUD. $BAC $TLT $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:02:42 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA 
J. Powell 
&amp;quot; we are doing out best, but I don&amp;#39;t know how exactly stop the inflation than monitoring monthly data&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 03:01:46 </td>
   <td style="text-align:left;"> $AAPL just using some play money, but apple calls printed in the morning, sold them and bought puts, sold those at the bottom and bought calls again and sold near 175.50. Good market volatility! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:59:48 </td>
   <td style="text-align:left;"> $SPY $AAPL block at 155 
1.3 million shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:59:43 </td>
   <td style="text-align:left;"> $AABB $MARA $RIOT $AABB all mentioned here and the $AABBG.X Exchange (mobile app) before March 22nd on the $AAPL Android will be a MASSIVE GAME CHANGER! https://www.financialnewsmedia.com/after-a-banner-year-for-cryptocurrencies-in-2021-many-are-asking-is-the-market-poised-for-a-bounce/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:59:24 </td>
   <td style="text-align:left;"> $AAPL incredible. Markets should be down yet slingshots down $3 to slingshot back up $3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:59:15 </td>
   <td style="text-align:left;"> $BTC.X $TSLA $AMZN $AAPL A nice real estate investment opportunity here if anyone is interested 

https://nada.co/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:59:15 </td>
   <td style="text-align:left;"> $AAPL remember!!!!  Dips buying works! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:57:41 </td>
   <td style="text-align:left;"> $AAPL High of the day...WTF, Where are we going? Push this pass $170.00 then have a freaking party.. Timmy got y&amp;#39;all fooled..$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:57:15 </td>
   <td style="text-align:left;"> Why is it okay 1 entity controls or markets?

Why do we not have fair free trade? What is point of company value if this is how it works anyways?

$SPY $NVDA $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:57:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Stock Gains as Foxconn Comes Back Online https://www.stck.pro/news/AAPL/24498293 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:57:05 </td>
   <td style="text-align:left;"> $SPY $AAPL 
 &amp;quot;Fed always late to the inflation curve&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:57:03 </td>
   <td style="text-align:left;"> $SPY my apple calls are gonna pay haha! lets see $170 baby!!! $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:57:03 </td>
   <td style="text-align:left;"> $SPY 515 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:57:00 </td>
   <td style="text-align:left;"> $AAPL has a Profit Margin of 26.58%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:56:53 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:56:21 </td>
   <td style="text-align:left;"> $aapl setting up for disappointment once again here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:56:12 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

CROOKS!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:54:56 </td>
   <td style="text-align:left;"> $SPY $AAPL Well confirmed that #FederalReserve is using #AAPL and WebEx lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:54:47 </td>
   <td style="text-align:left;"> $AAPL Premarket PUMPING keep taking out highs..What a shi!t show..$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:54:46 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMZN  tinyurl.com/3jsszym4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:54:38 </td>
   <td style="text-align:left;"> $SPY  $AAPL 
Dhit show lol. 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-17 02:54:11 </td>
   <td style="text-align:left;"> $SPY $AAPL $NVDA $QQQ  china lowers interest rate while USA inc. https://www.reuters.com/markets/europe/china-cuts-mortgage-reference-rate-first-time-nearly-two-years-2022-01-20/#:~:text=At%20a%20monthly%20fixing%20on,first%20cut%20since%20April%202020. lets go BABA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:47:17 </td>
   <td style="text-align:left;"> $TSLA will drop to 750? This is crazy I did not sell off today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:46:44 </td>
   <td style="text-align:left;"> $TSLA 🦧 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:46:03 </td>
   <td style="text-align:left;"> $SPY $UVXY $AAPL $QQQ $TSLA 

The only thing worse than war is complacency. Investors &amp;amp; civilians seem to already be desensitized to the horrors that are going on in Ukraine. Stubborn bulls become low quality steak, remember that… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:42:52 </td>
   <td style="text-align:left;"> $TSLA my fav time
To check Stocktwits is on a high volatility day lol which has been every day last month seems like …. But anyways I like it for the memes between bulls vs bears it’s hilarious lol I really appreciate the people who dig deep and come up with the funny memes lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:38:11 </td>
   <td style="text-align:left;"> $TSLA the bears looked so sad today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:34:15 </td>
   <td style="text-align:left;"> $TSLA $AMZN  tinyurl.com/26z4kt6a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:32:08 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-16 Options Analysis Video: 
https://www.youtube.com/watch?v=nMJsGnrDKIM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:31:30 </td>
   <td style="text-align:left;"> $TSLA 

How do you spot a lie and FUD - follow the redline !! 

Bloomberg is a pile of 🐕 💩 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:29:19 </td>
   <td style="text-align:left;"> $SPY $TSLA I tried warning Elon worshippers that Musk was a deep state puppet and all that space crap was just CGI animation to build his persona to be bigger then life.But I&amp;#39;m just a conspiracy theory hack. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:27:07 </td>
   <td style="text-align:left;"> $TSLA future green. Tomorrow 880$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:26:51 </td>
   <td style="text-align:left;"> $TSLA https://teslanorth.com/2022/03/16/tesla-fremont-factory-tour-and-test-drives-impress-morgan-stanley/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:26:11 </td>
   <td style="text-align:left;"> $TSLA Rug pull market wide coming soon.  Explain this to me.  The NASDAQ was up 400 points today but had a outflow of $1.15 Billion.  On Tuesday it was the same setup with another $1 Billion being withdrawn.  Hedgies and Tutes silently unloading and pumping the entire market with naked shares.  They are going to leave retail holding the bag.  Manipulation at it&amp;#39;s finest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:26:03 </td>
   <td style="text-align:left;"> $TSLA 

not only is Tesla fucked. 3rd company in 1 week. 

My god

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:24:38 </td>
   <td style="text-align:left;"> @FrogAlgo $TSLA is nice signal on morning - come to forgalgo.com for more information </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:21:05 </td>
   <td style="text-align:left;"> $TSLA down ~$1.50 ah, rippp bears were right 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:20:28 </td>
   <td style="text-align:left;"> $TSLA my favorite stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:14:53 </td>
   <td style="text-align:left;"> $F perfect dip $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:12:28 </td>
   <td style="text-align:left;"> $TSLA manipulation but green still </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:11:49 </td>
   <td style="text-align:left;"> $TSLA $860+ open tmrw these bears are absolutely clueless

If the bond deal would have had any affect it would have done so in the after market hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:11:09 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $MSFT $AMZN being a bear in this market is like the boy who cried wolf. By the time you&amp;#39;re actually right you&amp;#39;ll have no capital left to short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:08:23 </td>
   <td style="text-align:left;"> US senator $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:07:43 </td>
   <td style="text-align:left;"> $TSLA  LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:07:26 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:06:49 </td>
   <td style="text-align:left;"> $CLOV unless the entire market is crazy fucked tomorrow I bet we hit at least 3.27 for another retest- would be the 3rd? $SPY $TSLA 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:06:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Tsunami Alert Canceled After Big Quake Near Fukushima

https://www.google.com/amp/s/www.nytimes.com/live/2022/03/16/world/fukushima-japan-earthquake.amp.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:05:26 </td>
   <td style="text-align:left;"> $TSLA 
 
good enough  
 
it broke VWAP upper , had to go down 
 
-.- 
 
PM bear-b-q 🐻🔥🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:05:19 </td>
   <td style="text-align:left;"> $TSLA what is bond delay meant? Thanks for helping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:04:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA strong earthquake hitting north-east Japan

https://www.google.com/amp/s/www.bbc.com/news/world-asia-60770100.amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:03:36 </td>
   <td style="text-align:left;"> $TSLA wow! Delayed bond offering. That explains why it was bought up. Insiders bid it up to dump it in after hours and tomorrow. Sub 800 tomorrow morning is a lock now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:03:29 </td>
   <td style="text-align:left;"> $SPY $TSLA becareful out there boys and girls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:02:24 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-16 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=83E99AbOKcY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 08:02:05 </td>
   <td style="text-align:left;"> latexc5003364c3114358196fafafd33ce5feNIO
$LI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:58:37 </td>
   <td style="text-align:left;"> $MULN the beast is awakening……. $TSLA $SPY $AAPL  $AMC  check it out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:58:07 </td>
   <td style="text-align:left;"> $AFRM $BABA $QQQ $TSLA $BTC.X 
Cramer is the devil. He mixes true with lies and confuse retail. 2 weeks ago he brought charts from some expert that bottom is in. Now tonight his saying this crap. He made retail miss 50% run on Chinese stocks. Some of the shit he says is true but 50% is also lie. Now what? Sell tomorrow and watch everything go up? Or believe this fool that bottom still not in…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:57:09 </td>
   <td style="text-align:left;"> $TSLA https://www.bloomberg.com/news/articles/2022-03-16/tesla-halts-bond-sale-backed-by-auto-leases-amid-market-turmoil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:54:53 </td>
   <td style="text-align:left;"> $TSLA $LLKKF Best lithium in the world 99.97% purity lithium carbonate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:53:14 </td>
   <td style="text-align:left;"> $TSLA | Tesla Halts Bond Sale Backed by Auto Leases Amid Market Turmoil - BBG https://www.bloomberg.com/news/articles/2022-03-16/tesla-halts-bond-sale-backed-by-auto-leases-amid-market-turmoil?srnd=premium-europe&amp;amp;sref=dJOSAJZH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:50:34 </td>
   <td style="text-align:left;"> $TSLA 

Show me $1k already!
🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:50:17 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/T0ONafOpnao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:50:06 </td>
   <td style="text-align:left;"> $TSLA LEAPs and shares friends </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:49:50 </td>
   <td style="text-align:left;"> $TSLA giga Berlin drop on bears head 3/22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:47:07 </td>
   <td style="text-align:left;"> $TSLA Don&amp;#39;t worry guys hertz is buying 100,000 Tesla&amp;#39;s.. 

Why doesn&amp;#39;t the SEC every investigate this stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:45:54 </td>
   <td style="text-align:left;"> $TSLA catch the knife </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:44:32 </td>
   <td style="text-align:left;"> $TSLA would not be surprised to see 900 this week with the rate  we are going </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:43:57 </td>
   <td style="text-align:left;"> $TSLA hai bears  
 
840....futures opening up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:43:42 </td>
   <td style="text-align:left;"> $TSLA bear are loading up put in paper trading. Ahhahaha this is going up 💵🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:43:02 </td>
   <td style="text-align:left;"> $TSLA honestly im impressed w tesla, it went up and is quite bullish lately.. even during rough times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:42:25 </td>
   <td style="text-align:left;"> $TSLA 200 DMA test loading up puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:42:19 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $TQQQ $NVDA 
Hope everyone enjoyed the ride today before SPY hits $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:41:21 </td>
   <td style="text-align:left;"> $TSLA i have to scan on pre market 1 mins before market open tomorrow, if it dips around 800 ima get in for a qiut scalp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:41:20 </td>
   <td style="text-align:left;"> $TSLA 02:32: DUE TO MARKET VOLATILITY, TESLA IS REPORTEDLY TO BE HALTING A $1 BILLION BOND DEAL TIED TO LEASES., 17.03.22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:40:49 </td>
   <td style="text-align:left;"> $TSLA possible limit down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:40:30 </td>
   <td style="text-align:left;"> $TSLA  bear doesn&amp;#39;t understand the word undervalued </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:40:21 </td>
   <td style="text-align:left;"> $TSLA  
https://www.youtube.com/watch?v=jnUqZyHvwWg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:40:11 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $BTC.X $FB  

The destruction of the planet is priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:39:15 </td>
   <td style="text-align:left;"> $TSLA 

Seriously ! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:39:00 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:38:06 </td>
   <td style="text-align:left;"> $TSLA how do you unblock someone?? Help? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:37:29 </td>
   <td style="text-align:left;"> $TSLA I think it’s going back to 800 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:37:00 </td>
   <td style="text-align:left;"> $TSLA why is there so much FUD here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:35:49 </td>
   <td style="text-align:left;"> $MULN CEO talks about $TSLA a lot, may be tesla buy this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:35:02 </td>
   <td style="text-align:left;"> $TSLA Smart bears already covered as market is turning some kids are still waiting here😂😂🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:34:06 </td>
   <td style="text-align:left;"> $TSLA Bought Tesla puts at the bell if this dumps could be my lucky day tomorrow $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:34:00 </td>
   <td style="text-align:left;"> $TSLA Lmaooo trolls will come out ! Bears are here to stay. 800 at the opening! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:32:23 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $DIA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:32:02 </td>
   <td style="text-align:left;"> $FSR $TSLA what did Elon Musk ever talk about Fisker cars? Guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:30:15 </td>
   <td style="text-align:left;"> $BKKT bullish

$SPY $TSLA $SHIB.X $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:28:16 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #11 ticker with sweep activity where institutions are trading options urgently with 17.4K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:24:41 </td>
   <td style="text-align:left;"> $TSLA told u bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:21:36 </td>
   <td style="text-align:left;"> $TSLA up on the shut down news in China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:19:05 </td>
   <td style="text-align:left;"> $TSLA possible -6% dump tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:16:33 </td>
   <td style="text-align:left;"> $GM  latexe73f3779c21dbf1f65e27a64bc4d0387NVDA - 74% call flow 
$HYG - 73% put flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:13:35 </td>
   <td style="text-align:left;"> $TSLA $124k profit so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:12:27 </td>
   <td style="text-align:left;"> Elon vs. Putin coming near you... 🤣🤣🤣 
 
$TSLA $SPY $QQQ $VIX  
 
https://twitter.com/TicTocTick/status/1504233522071973888 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:10:57 </td>
   <td style="text-align:left;"> $TSLA lower low... it&amp;#39;s gonna dip again but I&amp;#39;m just holding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:08:32 </td>
   <td style="text-align:left;"> $NIO $TSLA 

Nio Cat Tesla Cat Stockmoe
😒 😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:07:30 </td>
   <td style="text-align:left;"> $TSLA Option Alert.. High Volume Options... 👀 👀  $850 Call for Friday, March 18. Roughly 55 Million dollars! 💰💰💰 MASSIVE MONEY 💰💰💰 Learn more on StockOrbit at https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:05:17 </td>
   <td style="text-align:left;"> $SOFI, $TSLA $BRK.B 
Hello, any colleague with access to Duff and Phelps / Kroll to obtain data on size premiums? I am trying to calculate a wacc. Please. Be my hero! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:04:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $MSFT 
As a foreigner, this is the big problem America
: &amp;#39;Sesquipedalian speech&amp;#39;

White men BSing with all the jargon words at work. 
WTH was the &amp;#39;Tool&amp;#39; and &amp;#39;Framework&amp;#39; that J. Pow kept referring?  
I am sure he can keep his job with that for  now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:03:15 </td>
   <td style="text-align:left;"> $TSLA TESLA Stock Price Prediction and Analysis for Tomorrow Thursday March 17th
https://youtu.be/xILZgFZyseE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:02:55 </td>
   <td style="text-align:left;"> $TSLA eow predictions? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:01:07 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA 

I just bought puts at the bell just in case what they talking. About really happens. Nothing else to report here that’s all. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 07:00:41 </td>
   <td style="text-align:left;"> $TSLA ELONA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:54:00 </td>
   <td style="text-align:left;"> $TSLA: The EPS has been growing by 473.69% on average over the past 5 years. This is a very strong growth. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:52:46 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:51:00 </td>
   <td style="text-align:left;"> $MULN  if you bought that day you are up 100% $TSLA  $RIVN  $LCID  $FSR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:48:48 </td>
   <td style="text-align:left;"> $TSLA What a hottie! 🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:47:38 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Earnings catching up quick! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:42:44 </td>
   <td style="text-align:left;"> $AMC $GME $BBBY $TSLA

$HYMC 

HYcroft Mining Co = SILVER &amp;amp; GOLD

AA is a real Silverback &amp;amp; now Goldenback ! 💛 🦍 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:40:54 </td>
   <td style="text-align:left;"> $SPY
$AAPL $TSLA $BABA 

WTF:  Win The Fund by setting up good trades!

💎💯🐅👐💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:39:36 </td>
   <td style="text-align:left;"> $TSLA PUTS going to print hard end of the weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:38:45 </td>
   <td style="text-align:left;"> $TSLA Elona, you look lovely today.  🙂 https://www.independent.co.uk/news/world/europe/elon-musk-elona-twitter-putin-chechen-b2036841.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:37:42 </td>
   <td style="text-align:left;"> $TSLA  senate buying stock and you are buying put.
Sureee y are right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:36:19 </td>
   <td style="text-align:left;"> $MULN never been so bullish on a stock! For long term, this might go back up to $15 or could be the next $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:33:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AAPL remember… you saw it here first. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:33:08 </td>
   <td style="text-align:left;"> $TSLA  this stock want 900$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:32:16 </td>
   <td style="text-align:left;"> $TSLA $NIO What do you think of Mullen Automotive from the US? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:29:57 </td>
   <td style="text-align:left;"> latexec292ad01468acf81514c2789334ae99BABA 1.131m (73% call/27% put)
$NVDA 852k (60% call/40% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:23:39 </td>
   <td style="text-align:left;"> $TSLA 2k by June 👉🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:23:01 </td>
   <td style="text-align:left;"> $TSLA we gonna run tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:20:42 </td>
   <td style="text-align:left;"> $GOOGL  bears got obliterated today 🤣 told y’all rate hikes would be a buy the news event new all time highs before summer $SPY $AAPL $TSLA $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:20:42 </td>
   <td style="text-align:left;"> $AMC $GME $BBBY $TSLA

$HYMC 

HYcroft Mining Co = GOLD

Just joining the dots here, maybe a future (gold backed) crypto coin as a dividend for all my favourite shorted stocks ? ! 💛 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:18:06 </td>
   <td style="text-align:left;"> $TSLA 🤣🤣🤣... told u </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:16:58 </td>
   <td style="text-align:left;"> $MULN $TSLA  CEO Gave Elon Musk  a shout out during the interview today for paving the way for the EV sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:16:34 </td>
   <td style="text-align:left;"> $TSLA remember it can go down as fast as it went up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:16:05 </td>
   <td style="text-align:left;"> $TSLA ELONA will save us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:14:54 </td>
   <td style="text-align:left;"> $TSLA did you follow the smart money dumb bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:14:43 </td>
   <td style="text-align:left;"> $TSLA to all the bears that just got destroyed and will continue to get killed all week, thank you for the Audi R8 ❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️

Couldn’t of done it without all of your free money, thank god for kids using daddy’s money with paper hands 🧑🏻‍🦯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:13:53 </td>
   <td style="text-align:left;"> $TSLA at least we wont be hearing bears and their $500 price for some time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:13:35 </td>
   <td style="text-align:left;"> $NIO $TSLA $LCID $VWAGY $XPEV THE WAR IS ON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:08:20 </td>
   <td style="text-align:left;"> $TSLA bulls y’all think MM will let you win? Think again end of week sell off coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:06:02 </td>
   <td style="text-align:left;"> Kudos to Tesla!! We are grateful, Elon!! $TSLA $$MULN ... 🖐😎🤗✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:05:38 </td>
   <td style="text-align:left;"> $TSLA account update. Lets see if this going to double or zero tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:04:34 </td>
   <td style="text-align:left;"> $TSLA Probably goes higher here. Reason being is I said so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:03:14 </td>
   <td style="text-align:left;"> $TSLA 4skintheGAME is hands down the biggest clown on here, everyone please add him to your prayer chain... might even start a go fund me his puts are getting fucked so hard, please spread the word </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:01:53 </td>
   <td style="text-align:left;"> $MULN $NVDA $AMD $AAPL $TSLA 

💸🚀💸 T I M E   F O R   T A K E O F F 💸🚀💸
 🛸🚀💰🚀💰🚀💰💎💰🚀💰🚀💰🚀🛸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 06:01:51 </td>
   <td style="text-align:left;"> $TSLA $GOOG $FB $AMZN $NVDA most profitable stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:59:12 </td>
   <td style="text-align:left;"> $TSLA lol wait til tomorrow bears. A close like that would cause any short to lose sleep. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:58:02 </td>
   <td style="text-align:left;"> $TSLA Watch &amp;quot;🔥RISK ON🔥 EP. 199 MARCH 16th 2022&amp;quot; on YouTube
https://youtu.be/N8kVl6ciVVU

CEO David Michery THE SECOND ELON TO EV MARKET! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:57:37 </td>
   <td style="text-align:left;"> $MULN Just finished watching David&amp;#39;s interview. I&amp;#39;m very impressed! Here&amp;#39;s some notes I took.
1. Very grateful to $TSLA and loves Elons story and thankful for him paving the way for EV&amp;#39;s. (Respect)
2. Wants to bring jobs back to America and put Americans to work(Love it!)
3. People want to buy cars from companies who specialize in EV&amp;#39;s(David&amp;#39;s a smart man!)
4. Loves cars/collects cars, helped save bay watch(👏😂)
5. Carbon Ceramic brakes!!! (He mentioned fast! Love it!)
6. Ground breaking battery tech!(Hes very proud of! Safe, reliable, long lasting, American)
🚘📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:54:31 </td>
   <td style="text-align:left;"> $TSLA hilarious and at the same time so true https://youtu.be/XSa673PC7a4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:54:23 </td>
   <td style="text-align:left;"> $TSLA see you at 200 🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:54:14 </td>
   <td style="text-align:left;"> $TSLA $SPY jerome said “nope bears, I’m still hodling so I’m not going to crash it” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:54:11 </td>
   <td style="text-align:left;"> $TSLA should open around 860 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:53:32 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m expecting a split again soon.  opinions? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:51:29 </td>
   <td style="text-align:left;"> $TSLA it’s been doing this for the past 3 months won’t get excited until we break 950. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:49:42 </td>
   <td style="text-align:left;"> $TSLA was on the sidelines, buying calls tomorrow! 🤑🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:49:10 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:49:10 </td>
   <td style="text-align:left;"> $TSLA post FOMC sell off tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:48:26 </td>
   <td style="text-align:left;"> $TSLA can you please split already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:47:46 </td>
   <td style="text-align:left;"> $TSLA $GOOGL $AMZN $FB $NVDA  and AAPL  tech heavy,tell me again in 10 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:46:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA ⛔️⛔️⛔️⛔️⛔️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⛔️⛔️⛔️☢️☢️☢️☣️☣️☣️ IS GOING TO GET UGLY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:46:44 </td>
   <td style="text-align:left;"> $TSLA how many 18 year old option traders accounts just got obliterated?????????????

I’ll make sure and donate my Tesla profits to a local hunger shelter in your area🤒🙃🧑🏻‍🦯🦧🤧 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:45:51 </td>
   <td style="text-align:left;"> $TSLA you think MMs really want this up? Free premium for them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:45:24 </td>
   <td style="text-align:left;"> $TSLA it breaks then go long, rejection then go short. No need to be one sided when it’s all there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:45:19 </td>
   <td style="text-align:left;"> $TSLA this is a sure thing... Right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:45:13 </td>
   <td style="text-align:left;"> 17:17 Time Mark ... Milton Todd Ault III interview with $MULN, Mullen Technologies .... You Tube. .... Thanks! $TSLA $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:44:38 </td>
   <td style="text-align:left;"> $TSLA 1/10 how broke do you have to be to trade options 🤡🤡🤡🤡🤡🤡

Asking for a friend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:43:48 </td>
   <td style="text-align:left;"> $TSLA 900 tomorrow???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:43:22 </td>
   <td style="text-align:left;"> $TSLA THANKS FOR THE FREE MONEY BEARS, ILL MAKE SURE AND SPEND IT WELL 🐒🐒🐒🐒🐒🐒🧑🏻‍🦯🧑🏻‍🦯🧑🏻‍🦯🧑🏻‍🦯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:40:16 </td>
   <td style="text-align:left;"> $TSLA TESLA Stock Price Prediction and Analysis for Tomorrow Thursday March 17th
https://youtu.be/xILZgFZyseE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:38:45 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ war is bad. it&amp;#39;s gonna crash the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:38:17 </td>
   <td style="text-align:left;"> $TSLA can anyone suggest any good stock subscription for options and long term portfolios </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:36:39 </td>
   <td style="text-align:left;"> $TSLA Tesla Motors, Inc. (NASDAQ:TSLA) – Raw Material Shortages May Not Be Hurting Tesla Right Now, But This Other Shortfall Might

https://news.alertsandnews.com/tesla-motors-inc-nasdaqtsla-raw-material-shortages-may-not-be-hurting-tesla-right-now-but-this-other-shortfall-might/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:36:17 </td>
   <td style="text-align:left;"> $QQQ $SPY $PYPL $TSLA $UVXY History Says Now Could Be A Great Time To Buy Stocks: Here’s Why

https://news.alertsandnews.com/history-says-now-could-be-a-great-time-to-buy-stocks-heres-why/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:36:09 </td>
   <td style="text-align:left;"> $BABA $NIO $TSLA $AAPL too tech heavy? Tell me again in 10 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:36:05 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $BTC.X  can anyone tell me why we rallied so hard in the afternoon today? I was in class and couldn’t check the news or anything, or was is it just a random pump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:35:03 </td>
   <td style="text-align:left;"> 🔥RISK ON🔥 EP. 199 MARCH 16th 2022 .. 50:53 Time Mark .... You Tube podcast ...

 Mullen Technologies .. $MULN ..
🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸 $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:34:31 </td>
   <td style="text-align:left;"> $TSLA Bears famous last words : I&amp;#39;m going to slaughter this pig! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:34:00 </td>
   <td style="text-align:left;"> 4 Sniper Shot trades today for a total of $500. 🎯🎯🎯🎯 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:33:44 </td>
   <td style="text-align:left;"> $TSLA where them bear 🤡 at ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:32:46 </td>
   <td style="text-align:left;"> $TSLA I’ll bet y’all , tsla make a big jump ova ma 200 tomorrow and stay above 850 -900🚀🚀🚀🚀🚀🚀🚀😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:31:58 </td>
   <td style="text-align:left;"> $TSLA gap down tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:31:38 </td>
   <td style="text-align:left;"> $TSLA Go Elona! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:26:10 </td>
   <td style="text-align:left;"> $TSLA buying puts is like playing the don&amp;#39;t pass line. Don&amp;#39;t be that guy. You might win, but is it really worth being a hated POS? Don&amp;#39;t answer that question.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:25:26 </td>
   <td style="text-align:left;"> $TSLA $GME $LABU look like a huge gap up for all 3 tomorrow 🚀🚀🚀🚀🚀🚀🚀💵💵💵😁👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:25:12 </td>
   <td style="text-align:left;"> $TSLA Beautiful day.  I&amp;#39;ll take another order of this again tomorrow, please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:25:05 </td>
   <td style="text-align:left;"> $TSLA $900 babydoll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:25:04 </td>
   <td style="text-align:left;"> $MULN The 10,000 pound gorilla in the room was $TSLA and they couldn&amp;#39;t talk about it. I don&amp;#39;t think the CEO was just showing his appreciation to Tesla for the sake of it. There&amp;#39;s a possibility there is a deal brewing.  
 
Check out the 17th minute in the interview. 
https://www.youtube.com/watch?v=N8kVl6ciVVU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:23:04 </td>
   <td style="text-align:left;"> $TSLA ez come ez go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:22:34 </td>
   <td style="text-align:left;"> $TSLA  Well the last 2 days were fun!  Right bears? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:22:19 </td>
   <td style="text-align:left;"> $TSLA 850 let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:21:45 </td>
   <td style="text-align:left;"> $TSLA smells like wet fur around here what’s going on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:21:21 </td>
   <td style="text-align:left;"> $TSLA Love to buy around 750-775 swing easy money 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:21:09 </td>
   <td style="text-align:left;"> $TSLA 840.23 tested many times,  848 high AH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:21:08 </td>
   <td style="text-align:left;"> $TSLA  bears think this is SHOP or something, it&amp;#39;s not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:20:00 </td>
   <td style="text-align:left;"> $QQQ quad witching crusher for all the crowded bear bets mañana $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:19:51 </td>
   <td style="text-align:left;"> $TSLA i expected a rally. I didnt expect this kinda rally. My CCs are toast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:19:11 </td>
   <td style="text-align:left;"> $MULN imagine buying a couple of thousand shares of $TSLA …  keep buying fellas!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:18:33 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:18:33 </td>
   <td style="text-align:left;"> $TSLA is too late to buy  “dont buy” 📉🔻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:18:04 </td>
   <td style="text-align:left;"> $TSLA 2 days green 3 days red? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:16:49 </td>
   <td style="text-align:left;"> $TSLA  amazing Bull Powell 📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:16:42 </td>
   <td style="text-align:left;"> $TSLA $SPY 

Had to change my profile picture to get ready for the insane rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:16:09 </td>
   <td style="text-align:left;"> $NIO listen to this bear where does $tsla and $aapl sell their 
 merchandise (CHINA) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:14:14 </td>
   <td style="text-align:left;"> $TSLA 700 low - that&amp;#39;s it?   Not bad at all and only lasted a few minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:13:22 </td>
   <td style="text-align:left;"> $TSLA it was a good thing to sell puts earlier,   TSLA likes these 40 dollar swings.. I think today was special because of the fed meeting or we might of had a smaller percentage in either direction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:13:01 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $NIO $TSLA   🔴🔴🔴🔴REMEMBER HE JUST SENDING THE MESSAGE. The war is going to get worse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:12:25 </td>
   <td style="text-align:left;"> $SPY Give it up for the greatest president in history of the world 😎bow and suck it....
$AAPL $QQQ $TSLA $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:10:51 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $845.0 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:07:03 </td>
   <td style="text-align:left;"> $TSLA Puts burn tomorrow!!! Better cover!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:06:38 </td>
   <td style="text-align:left;"> Forget the Fed; We&amp;#39;ve Got Oil and &amp;quot;Elona Musk&amp;quot; to Talk About $AVB $UMH $TSLA $OIL https://talkmarkets.com/content/commodities/forget-the-fed-weve-got-oil-and-elona-musk-to-talk-about?post=348218 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:06:02 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;ll be selling at next ath and not a dollar sooner. 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:04:20 </td>
   <td style="text-align:left;"> $TSLA  tomorrow another 4% up thanks for war peace! Mark it. 1000$ 💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:03:54 </td>
   <td style="text-align:left;"> $TSLA covid lockdown in China, russia war, and raised prices the perfect storm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:03:47 </td>
   <td style="text-align:left;"> $TSLA 

Got to share this with y’all as I share my trades ! 

Triple “Bs E 2/6” meaning BBB-E 2/6
Beef Butter Bacon Eggs 2meals only 6hrs apart !! 

I’m not a nutritionist but this diet I discovered finally over yrs of suffering I’m forever grateful - ZERO SUGAR ZERO PLANT BASED FOOD JUST 100% HUMAN DIET FROM GRASS FED ANIMALS !! 

Revered all my issues and I feel if I’m 18yrs again! 

🙏🏻🐉🦅😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:03:35 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Congrats: If you are reading this post, you made it through another market day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:02:50 </td>
   <td style="text-align:left;"> $TSLA $1,200 end of year bearish case </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:02:37 </td>
   <td style="text-align:left;"> $NIO let’s go $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:02:27 </td>
   <td style="text-align:left;"> $TSLA maybe I should have held… 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:02:20 </td>
   <td style="text-align:left;"> $TSLA 🔥🚀🏦💵😂💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:02:06 </td>
   <td style="text-align:left;"> ChargePoint.... $MULN ... $TSLA .. $AMZN  ... 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:01:37 </td>
   <td style="text-align:left;"> $TSLA Can still make more lows but price action is very choppy.  It remains in a longer time frame area where a bounce can take place, we don’t like to short sell it in the blue boxes.  We do not like to short sell it.  #Ellliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:01:28 </td>
   <td style="text-align:left;"> $TSLA $200 eoy, it’s overvalued, nobody can afford electric cars, climate change not real, Musk is clown… this is how smart you bears sound. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:00:35 </td>
   <td style="text-align:left;"> $TSLA Red day tomorrow. Continuation like this can’t happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:00:17 </td>
   <td style="text-align:left;"> $ADMP Glad I bought them $tsla options around 760 up almost a $100 already LMAO still got til the 25th </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 05:00:11 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-16 Options Analysis Video: 
https://www.youtube.com/watch?v=nMJsGnrDKIM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:59:43 </td>
   <td style="text-align:left;"> $TSLA hope u didnt fall for this bull trap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:58:45 </td>
   <td style="text-align:left;"> $TSLA $900 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:57:09 </td>
   <td style="text-align:left;"> $TSLA Red line went under </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:56:55 </td>
   <td style="text-align:left;"> $TSLA when is model Pi coming out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:55:55 </td>
   <td style="text-align:left;"> $BABA $BTC.X $SPY $TSLA bears dinner tonight after the wife leaves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:55:25 </td>
   <td style="text-align:left;"> Not sure why we rallied after the #Fed? Check out the preview vid I shared last night on youtube 
 
So far has played out pretty on point. Hawkish tone from the fed (more than id thought w/ 7 hike potential) and relief rally from oversold bear sentiment  
 
https://youtu.be/vU6h0TCcmFc 
 
$TSLA $AMZN $AAPL $BABA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:54:03 </td>
   <td style="text-align:left;"> $TSLA get high rates is good
Let people hardly to short it stock 
Then we go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:53:34 </td>
   <td style="text-align:left;"> $NVDA $TSLA comparing the charts! NVIDIA setup right now looks similar to Tesla before the massive run. $HYMC $MULN $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:53:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $TSLA is 7.00. This indicates good health for $TSLA. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:52:59 </td>
   <td style="text-align:left;"> $NIO yep ✅🔥🚀💵 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:52:34 </td>
   <td style="text-align:left;"> $TSLA Anyone listen to JP today? is 25bp raise confirmed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:52:27 </td>
   <td style="text-align:left;"> $TSLA green or red tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:51:44 </td>
   <td style="text-align:left;"> $BTC.X $TSLA $AAPL $SPY $DJIA  
everybody made lots of money in the market today 
lets all go buy some more bitcoin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:51:19 </td>
   <td style="text-align:left;"> $SPY crazy day $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:51:19 </td>
   <td style="text-align:left;"> $TSLA if $800 retest happens I go all in. 0 money in cash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:51:01 </td>
   <td style="text-align:left;"> $TSLA elon will move on and dump this like every other project </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:50:18 </td>
   <td style="text-align:left;"> $TSLA I thought everyone said this  was going to 600 😗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:49:53 </td>
   <td style="text-align:left;"> $TSLA $900, 950,1000 Calls are massive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:49:46 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING! 

Tesla Stock has recaptured 200SMA after dipping below for 5 trading days !! 

Visit my posts ! (Fun facts) 

🙏🏻🐉🦅

https://stocktwits.com/BigNews/message/444406446 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:48:53 </td>
   <td style="text-align:left;"> $TSLA Giga Berlin D-Day next Tuesday lol imagine bears!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:47:40 </td>
   <td style="text-align:left;"> $MULN i smell $TSLA  going to buy this soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:46:19 </td>
   <td style="text-align:left;"> $TSLA give me 848 and then we burst </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:45:59 </td>
   <td style="text-align:left;"> $TSLA once you let that tesla share go you gonna have a hell of time getting it back at a decent price. I speak of experience! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:45:57 </td>
   <td style="text-align:left;"> $TSLA in between 700 and 1,000 ⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:45:30 </td>
   <td style="text-align:left;"> $TSLA congrats bulls last few days was a long time coming after months of pain seems like bottom was in 2/24 lows of 700 and it held the 750s with some concrete news about the Fed rate hikes out of the way, next catalysts would be a peaceful resolution to the war &amp;amp; of course the monthly PPI &amp;amp; CPI numbers being under control then it’s to the moon boys back to ATHs 🚀🚀🚀😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:44:31 </td>
   <td style="text-align:left;"> $TSLA easy $900+ tomorrow!!🔥🔥🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:44:29 </td>
   <td style="text-align:left;"> $TSLA. She’s a smellin that $1000🤑🤑🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:43:59 </td>
   <td style="text-align:left;"> $HOOD $F $TSLA $TWTR $GBTC  😂🥲
🌐🇺🇸👋🎩💼💲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:43:27 </td>
   <td style="text-align:left;"> $TSLA Elon gave us a signal yesterday. Check his twitter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:43:26 </td>
   <td style="text-align:left;"> $NVDA this will run like $TSLA  looks very similar and price action is super strong last few days. I would recommend adding this to your watchlist…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:43:02 </td>
   <td style="text-align:left;"> $TSLA Shorts!! 
 
Tesla +up 4.4 Points i AH! 
 
Tesla can handle rate hikes!! Demand &amp;gt; Supply Tesla can easily bill-back higher costs into EV prices (Basic cost-accounting) 
 
Delivery 04-04 2 weeks 
BBQ         04-07 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:42:40 </td>
   <td style="text-align:left;"> Lot of 🐑 calling bottoms today. A lot saying crash coming too. Chop Chop trending upwards is best guess to deter both sides over next few months, before more down back half of year. Rate hike uncertainties calmed for the most part, but Europe is still a big unknown that can really throw a wrench in the mix. Short term bull on equities, medium/long term bear $SPY $QQQ $FB $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:42:35 </td>
   <td style="text-align:left;"> $TSLA @jccoo Short the lows, cover on the highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:41:36 </td>
   <td style="text-align:left;"> $TSLA lol america is a joke, people literally starving and prices at record highs yet the Nasdaq and dow &amp;#39;Yep up we go&amp;#39; +500 points. 

If this isn&amp;#39;t a bear trap I don&amp;#39;t know what is tbh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:40:49 </td>
   <td style="text-align:left;"> $TSLA 

For those clowns 🤡 who trolled last week on my Technical Patterns n my Vertical Trades in spite of my sincere comment “learn so you can earn “ and rubbing it over n over “Bullish Divergence” that vertical trade is still open (added more today - at $802 and it’s up as of this closing SP (690k⬆️ ) in my 3% swing account !! 

You’re welcome! 

I may no longer share my trades if  y’all don’t care or you don’t see benefits ! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:40:49 </td>
   <td style="text-align:left;"> $TSLA soon $1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:40:33 </td>
   <td style="text-align:left;"> $TSLA if you did not sell your calls today. RIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:40:22 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #3 stock that institutions are trading over rolling 5 day window with 121.6K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:40:20 </td>
   <td style="text-align:left;"> $TSLA tomorrow is gonna be very interesting. With fed meeting out of way for now the market looks primed to continue the rally. I kept a small weekly otm put position as hedge and picked up few calls before close. I normally wouldn’t be touch calls at this point but weeklies are still dirt cheap. On verge of confirming a break out of downtown channel. Volume will really dictate how tomorrow goes. Gonna need buying volume to keep MM from screwing everyone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:40:11 </td>
   <td style="text-align:left;"> $TSLA tomorrow $900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:40:05 </td>
   <td style="text-align:left;"> $TSLA Watch this go to $1000 by Friday afternoon. Rate hike fears way overblown. I thought this would drop more but I feel like the market is too protected from crashes compared to the old days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:39:17 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $IWM &amp;quot;U.S. economy is strong&amp;quot; (induced long term economic recession on its way) - Powell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:38:55 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:38:55 </td>
   <td style="text-align:left;"> $TSLA The RSI needs to cool off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:38:52 </td>
   <td style="text-align:left;"> $TSLA hope there&amp;#39;s some value on my 900 strike calls Friday. If they move it like a turtle it will be worthless. Anyone else have those? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:38:36 </td>
   <td style="text-align:left;"> $TSLA 900 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:38:30 </td>
   <td style="text-align:left;"> $TSLA % </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:37:40 </td>
   <td style="text-align:left;"> $TSLA UH OH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:37:39 </td>
   <td style="text-align:left;"> $TSLA  well i see this going cloaing 430s tomorrow whocares 1200+ pt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:37:39 </td>
   <td style="text-align:left;"> $TSLA oiiiii </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:37:30 </td>
   <td style="text-align:left;"> $TSLA 

Wow. She is mooning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:37:10 </td>
   <td style="text-align:left;"> Sucks to suck bears.🐻 
 
$SPY $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:37:05 </td>
   <td style="text-align:left;"> $TSLA when you bust and she keep on suckin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:36:23 </td>
   <td style="text-align:left;"> $TSLA shocked we aren’t trending….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:36:13 </td>
   <td style="text-align:left;"> $TSLA Jesus Christ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:35:33 </td>
   <td style="text-align:left;"> $TSLA Tesla don&amp;#39;t care </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:35:29 </td>
   <td style="text-align:left;"> $TSLA Control the narrative… https://m.youtube.com/watch?v=RFE1zqJNA1Y&amp;amp;t=195s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:35:11 </td>
   <td style="text-align:left;"> $BTC.X $SPY $TSLA $QQQ $AMC  
my wife all excited told me that she saved 2 dollars with a coupon today… 
little does she know i made over $10k today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:33:52 </td>
   <td style="text-align:left;"> $TSLA $NIO $SPY $QQQ $PLTR 

Was fun while it lasted bears. Our time now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:33:38 </td>
   <td style="text-align:left;"> $TSLA $10 short of $850 wonder what tomorrow will look like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:33:30 </td>
   <td style="text-align:left;"> $TSLA $AAPL keep it coming 🚀🤙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:33:28 </td>
   <td style="text-align:left;"> $TSLA seems like when the bears fill the room this runs and when the Bulls come in it drops. Bulls put on your bears hat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:33:05 </td>
   <td style="text-align:left;"> $TSLA no problem admitting defeat i bought 770 put im still holding it but got crushed, good job bullios </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:32:28 </td>
   <td style="text-align:left;"> $TSLA there is no good news out. Back to $800 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:32:28 </td>
   <td style="text-align:left;"> $SPY look at $TSLA even
same thing 2:39? Come on. Now!!!
See .. a pattern? 
I dont .. but my algorithms do for me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:32:26 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-16 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=83E99AbOKcY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:32:15 </td>
   <td style="text-align:left;"> $TSLA still no movement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:31:39 </td>
   <td style="text-align:left;"> $SPY LOL $DWAC  $TSLA  😭😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:30:42 </td>
   <td style="text-align:left;"> $TSLA  $1000🤑🤑🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:30:04 </td>
   <td style="text-align:left;"> $TSLA hope I get some money for puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:29:27 </td>
   <td style="text-align:left;"> $TSLA I hope many  are making money holding this and not selling 👊🏼💥💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:28:44 </td>
   <td style="text-align:left;"> $TSLA $SPY How many bears killed themselves buying puts when SPY was at 425. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:28:33 </td>
   <td style="text-align:left;"> $TSLA 200 MA = 848 let&amp;#39;s get it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:27:52 </td>
   <td style="text-align:left;"> $TSLA lol it&amp;#39;s still pumping AH. Bears are dead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:27:50 </td>
   <td style="text-align:left;"> @EskimoBrother just crushing it scalping $TSLA options these days - glory be to volatility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:27:37 </td>
   <td style="text-align:left;"> $TSLA 850 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:26:49 </td>
   <td style="text-align:left;"> $NIO $HOOD $SPY $PLTR $TSLA 

I’m going to make so much money this summer it’s gonna be disgusting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:26:28 </td>
   <td style="text-align:left;"> $NIO $FSR $LCID $TSLA 🕯 💥🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:26:21 </td>
   <td style="text-align:left;"> After 3 months of being out in the cold I let $NIO cat back in today to join $TSLA cat. Now let’s get out there and make some money!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:26:15 </td>
   <td style="text-align:left;"> $TSLA 900 EOW LFGGGGGG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:25:14 </td>
   <td style="text-align:left;"> $TSLA Another inverse head and shoulders pattern forming.  I&amp;#39;m finding these all over the growth stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:24:16 </td>
   <td style="text-align:left;"> $MULN we going hard core. CEO coming on soon for squeeze  
 
 
$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:23:46 </td>
   <td style="text-align:left;"> $TSLA  840 + 25% = 1051.25 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:22:28 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:22:07 </td>
   <td style="text-align:left;"> $AMC $TSLA $PLTR All 3 are short and distort scams. Buy, hold and patience. And you will win! 
 
https://www.investopedia.com/terms/s/shortanddistort.asp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:22:07 </td>
   <td style="text-align:left;"> $TSLA OMG guys I fogot to close my Apr 14 900 calls((((( OMG CRAP! Now I am scared that this might tank tomorrow!!!!! FUSK! Let&amp;#39;s praay this opens higher and ideally move into 860 tomorrow. Crossing my fingers! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:20:33 </td>
   <td style="text-align:left;"> $TSLA https://www.youtube.com/watch?v=N8kVl6ciVVU meeting with ceo at 1;30 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:20:29 </td>
   <td style="text-align:left;"> 3 Stocks Leading Recent Gains https://www.billionaireclubcollc.com/3-stocks-leading-recent-gains/ $AAL $NVDA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:19:51 </td>
   <td style="text-align:left;"> $TSLA 

Breakout of Falling Wedge into “W” formation ! Next target $926 

🙏🏻🐉🦅IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:19:42 </td>
   <td style="text-align:left;"> $TSLA announces 5 for 1 stock split coming up next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:18:08 </td>
   <td style="text-align:left;"> $AMC $TSLA $PLTR If you know one chart, you know them all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:17:20 </td>
   <td style="text-align:left;"> $TSLA $QQQ $DIA $SPY bear market my ass America is still the Boss even with this guy in office </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:17:16 </td>
   <td style="text-align:left;"> $TSLA when at Costco someone in line said to buy ev stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-17 04:15:42 </td>
   <td style="text-align:left;"> $TSLA looking at open interest at the 850 calls could be in for a huge squeeze unless market makers can keep it down. doesn&amp;#39;t seem likely. </td>
  </tr>
</tbody>
</table></div>

---
