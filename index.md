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



Last Updated: 2022-03-01 08:42:32 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/australia/current-account </td>
   <td style="text-align:left;"> 2022-03-01 08:36:00 </td>
   <td style="text-align:left;"> Australia Current Account Surplus Smallest in 5 Months </td>
   <td style="text-align:left;"> Australia's current account surplus narrowed to a five-month low of AUD 12.7 billion in the fourth quarter of 2021, from a downwardly revised AUD 22.0 billion in the previous period and below market expectations of AUD 14.9 billion, dragged by a fall of  AUD 6.4 billion in the balance on goods and services surplus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/28/business/ukraine-crypto-donations.html </td>
   <td style="text-align:left;"> 2022-03-01 08:31:13 </td>
   <td style="text-align:left;"> Ukraine Has Received Crypto Donations in More Than $15 million - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                       , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                        , Crypto has provided a way for investors to quickly move funds to Ukrainian fighters.                                                                                                                                                                                                                                                                                                                                                                , By David Yaffe-Bellany                                                                                                                                                                                                                                                                                                                                                                                                                              , As Russia’s invasion escalated over the weekend, Ukrainian officials made an unusual request on Twitter: Send us your crypto.                                                                                                                                                                                                                                                                                                                       , A series of tweets, sent from government accounts, listed online wallet addresses for Bitcoin, Ether and Tether, three of the most popular cryptocurrencies. Since then, cryptocurrency investors have donated more than $22 million worth of digital assets to the Ukrainian government and a nonprofit supporting the country’s military, according to data provided by the blockchain tracking firm Elliptic on Monday evening.                  , The conflict in Ukraine has put the growing cryptocurrency industry under new scrutiny, with politicians and regulators expressing concern that the digital tokens could become a tool for sanctions evasion by Russian businesses and government officials. But cryptocurrency has also provided a way for investors around the world to quickly move funds to Ukrainian fighters, as more traditional crowdfunding strategies encounter obstacles., Last week, the crowdfunding website Patreon took down a page operated by Come Back Alive, a Kyiv organization that has raised money to arm and train military personnel in Ukraine. Patreon said the page had violated its rules against funding military activity.                                                                                                                                                                                 , But Come Back Alive now has a new source of funding: a crypto collective called UkraineDAO, which was formed last week by crypto enthusiasts working with the Russian protest band Pussy Riot. A spokeswoman for UkraineDAO said it had raised more than $4 million in cryptocurrency for Come Back Alive.                                                                                                                                          , Nadya Tolokonnikova, a member of the band, said in an interview that Come Back Alive had agreed to spend the funds on medical support for victims of the war, rather than arming soldiers.                                                                                                                                                                                                                                                          , “Blockchain allows us to scale our efforts in a way that wasn’t possible for us before,” Ms. Tolokonnikova said, referring to the decentralized ledger system that underlies cryptocurrencies. “The old ways of raising money sometimes are really slow and just clumsy.”                                                                                                                                                                           , Come Back Alive did not immediately respond to a request for comment. According to Elliptic, the Ukrainian group had raised more than $7 million in cryptocurrency as of Monday evening. The government of Ukraine had received $15.4 million in cryptocurrency contributions, Elliptic said.                                                                                                                                                       , The donations are a drop in the bucket in the context of the conflict. Last year, Ukraine’s defense budget was about $4 billion; Russia spends more than 10 times that much on its military.                                                                                                                                                                                                                                                        , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/imports-yoy </td>
   <td style="text-align:left;"> 2022-03-01 08:23:00 </td>
   <td style="text-align:left;"> South Korea Imports Extend Double-Digit Growth </td>
   <td style="text-align:left;"> Imports to South Korea expanded 25.1% yoy in to USD 53.07 billion February 2022, roughly in line with market forecasts of 25.2% and after a 35.3% jump in the prior month, with domestic demand staying solid following an acceleration in COVID-19 vaccinations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/exports-yoy </td>
   <td style="text-align:left;"> 2022-03-01 08:18:00 </td>
   <td style="text-align:left;"> South Korea Exports Rise the Most in 3 Months </td>
   <td style="text-align:left;"> Exports from South Korea grew by 20.6% yoy to USD 53.91 billion in February 2022, above market forecasts of 18.2% and after a 15.2% rise a month earlier. This was the 16th straight month of increase in shipments and the steepest pace since last November, despite escalating geopolitical tensions in eastern Europe and supply bottlenecks. Demand for semiconductors, computers, flat screens, steel, petroleum products, and petrochemicals remained strong, with shipments to nearly all major markets including the US and China expanding solidly. Amid a string of unfavorable external factors, exports from South Korea will likely lose some growth momentum in early 2022, local media said. Last year, exports jumped 25.8% yoy to a record of USD 644.5 billion, the strongest growth since 2010 and reversing from a 5.5% fall in 2020 and a 10.4% drop in 2019. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 08:13:35 </td>
   <td style="text-align:left;"> Australia Shares Rise Ahead of RBA Decision </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index rose 1% to around 7,120 in a broad market rally on Tuesday, as investors await fresh policy signals from the conclusion of the central bank meeting. The Reserve Bank of Australia is widely expected to keep interest rates on hold, but markets will be watching for any clues regarding the expected timetable for policy tightening. Nearly all sectors of the Australian market participated in Tuesday’s rally, led by the technology and financial sectors. Notable gainers include Xero (4.1%), Brainchip Holdings (5%), Commonwealth Bank (2%) and National Australia Bank (2.3%). Energy firms also advanced on robust oil and coal prices, with gains from Woodside Petroleum (1.1%), Yancoal (18.4%) and Whitehaven Coal (4.4%). Meanwhile, investors continue to monitor developments surrounding the Russia-Ukraine conflict as the two countries wrapped up the first round of talks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/balance-of-trade </td>
   <td style="text-align:left;"> 2022-03-01 08:12:00 </td>
   <td style="text-align:left;"> South Korea Trade Surplus Narrows </td>
   <td style="text-align:left;"> South Korea's trade surplus decreased to USD 0.84 billion in February 2022 from USD 2.33 billion in the same month a year earlier, as imports grew faster than exports, a preliminary reading showed. Arrivals grew by 25.1 percent year-on-year to USD 53.07 billion, while shipments rose at a softer 20.6 percent to USD 53.91 billion. The government said recently that the trade conditions will face several challenges, including high raw material prices and supply chain instability due to geopolitical tensions; but it has planned to roll out active support measures for exporters. . In 2021, the country posted a trade surplus of USD 29.49 billion, down sharply from USD 44.76 billion in 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60561679?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-01 08:03:24 </td>
   <td style="text-align:left;"> The whistleblowing bankers who were sent to jail </td>
   <td style="text-align:left;"> Two traders jailed for rigging interest rates were the original whistleblowers of the scandal, the BBC has learned.                                                                                                                                                                             , Leaked audio recordings reveal Peter Johnson and Colin Bermingham alerted the US central bank to a fraud that the tapes suggest was directed from the top of the financial system.                                                                                                              , But no senior figure was prosecuted. The Serious Fraud Office concluded the test for prosecution was not met.                                                                                                                                                                                   , Instead the whistleblowers were themselves sent to jail.                                                                                                                                                                                                                                        , Audio recordings, obtained exclusively by BBC Radio 4, reveal Peter Johnson, known at work as "PJ", was repeatedly instructed by senior managers at Barclays to engage in the fraud, known as "lowballing".                                                                                     , It involved lying about the interest rates banks were paying during the financial crisis, pretending they could borrow cash much more cheaply than they really could.                                                                                                                           , The conversations, evidence of a criminal fraud in the midst of the worst financial crisis in eighty years, are part of a cache of secret audio recordings leaked to the BBC and revealed in The Lowball Tapes, a pioneering series investigating the secret history of interest rate "rigging"., They reveal that Johnson, convicted separately for manipulating rates on a much smaller scale, in fact tried to bring lowballing to the authorities’ attention, starting in 2007.                                                                                                               , He repeatedly alerted the US central bank, the Federal Reserve (the Fed) to the fact that banks were lying about the interest rates they were paying to borrow dollars.                                                                                                                         , The stakes were high. This was at the beginning of the "credit crunch" – the early days of the financial crisis when banks were becoming afraid to lend to each other, and charging higher rates to reflect their fears.                                                                        , In a few weeks, this would lead to the Northern Rock bank collapse, and develop into a financial crisis the following year.                                                                                                                                                                     , For months, his campaign fell on deaf ears. While his immediate bosses were sympathetic, they said they were passing on instructions from above.                                                                                                                                                , Against his vehement protests, Johnson joined in the same fraud he was seeking to expose, making dishonest statements about the cost of borrowing cash which did not reflect the real cost his bank was paying on the markets.                                                                  , The recordings suggest board directors were concerned that if Johnson told the truth, it might look to journalists like Barclays was paying higher interest rates because it was desperate for money.                                                                                           , To avoid giving that impression, Barclays and other banks engaged in lowballing, a serious form of misconduct for which banks have since paid hundreds of millions in fines.                                                                                                                    , In November 2007, after months of pressure from his bosses to lie, Johnson vented his frustration on the phone to a 25-year-old colleague at Barclays’ Wall Street office called Ryan.                                                                                                          , In an expletive-laden call, an extract of which is below, Johnson calls it “sick” and “wrong.”                                                                                                                                                                                                  , Ryan: "Should be higher?"                                                                                                                                                                                                                                                                       , Johnson: "Much, much higher... believe me, you’ve got no idea how much higher."                                                                                                                                                                                                                 , He tells Ryan: "I think it’s becoming a sort of ethical and legal thing now. I’m patently giving a false rate!"                                                                                                                                                                                 , Johnson also protested to his boss, Mark Dearlove, saying: "I think we should take a stand. I’m going to write you an email and you can do with it what you want."                                                                                                                              , Dearlove: "Ok, fair enough. You’re right 'cos I want to get something written down for the guys upstairs..."                                                                                                                                                                                    , Johnson: "So I’ll just write a thing.  I’ll just say I think its bringing the Libor market into disrepute, Barclays into disrepute, me into disrepute..."                                                                                                                                       , Johnson wrote an email for Dearlove to circulate to senior management saying the bank was being "dishonest by definition". But that didn’t stop him being ordered to lowball.                                                                                                                   , What the FTSE 100 is to share prices, Libor is to interest rates – an index that tracks the cost of borrowing cash. For most of the past 35 years, 16 banks have answered a question every morning at 11am: At what interest rate could you borrow money?                                       , They submit their answers (eg RBS estimates 3.14%, Lloyds 3.13% etc) and an average is taken to get Libor, short for "London Interbank Offered Rate". To set Euribor, the process is similar but with more banks involved.                                                                      , The evidence against the traders jailed for rate "rigging" consisted entirely of requests they had made to colleagues to tweak those estimated interest rates up or down, typically by one hundredth of a percentage point (known on the money markets as a ‘basis point’).                     , The hope was that it might shift the Libor average marginally in the right direction to benefit the bank’s trades which went up or down linked to Libor.                                                                                                                                        , Neither Johnson nor Bermingham has ever granted the media an interview. But the BBC has been able to piece together their extraordinary stories and hear the actual words they said because their phones lines, as is normal on banks’ trading floors, were recorded.                           , In the confidential tapes, we hear Johnson being told by his bosses that the need to fix interest rates came from above: first from senior managers at Barclays Bank, then from instructions from the Bank of England, then from the UK government, including Downing Street.                   , The tapes reveal that Johnson and Bermingham repeatedly blew the whistle to the US central bank about his and other banks publishing false estimates of the cost of borrowing cash, known as "Libor submissions".                                                                               , On 11 April 2008, Bermingham alerted the Fed to what he regarded as a broken market, frankly telling them that Barclays, like other banks, is not posting "honest" estimates of the cost of borrowing cash. The Fed official says she understands fully and does not report a crime.            , At the peak of the financial crisis, a few weeks after the collapse of the investment bank Lehman Brothers sent stock markets plunging, then Prime Minister Gordon Brown announced unprecedented emergency measures on 8 October 2008, including £50bn to recapitalise the banks.               , On the same day, seven central banks from the US to Japan to Europe announced a co-ordinated cut in their official interest rates.  Then RBS and Lloyds had to be rescued and nationalised.                                                                                                     , But the real cost of borrowing cash, as measured by Libor, wasn’t dropping fast enough to show the emergency measures were working.                                                                                                                                                             , On 24 October 2008, Johnson told an official at the Fed about false rates being posted, saying "Please don’t believe it, it’s absolute rubbish."                                                                                                                                                , On 29 October 2008,  the then deputy governor of the Bank of England (BoE) Paul Tucker called Barclays chief executive Bob Diamond and told him that "senior figures" in Whitehall were asking why Barclays’ Libor rates were always too high.                                                  , Mr Diamond was concerned the government would think it meant that Barclays was struggling to get the funds it needed and had to be nationalised.                                                                                                                                                , The same day, Johnson received a call from his boss Mr Dearlove, who told him: "PJ, you’re going to absolutely hate this... but we've had some very serious pressure from the UK Government and the Bank of England about pushing our Libors lower."                                            , Agreeing it’s "the wrong thing to do," Mr Dearlove says, “I am as reluctant as you are... These guys don’t see it, they’re bent out of shape. They’re calling everyone…”                                                                                                                        , Both the US Department of Justice and the Serious Fraud Office had access to all the recordings obtained by the BBC, handed to them by Barclays’ legal department.                                                                                                                              , But they didn’t rush to find out more about all the evidence pointing to the top. Much of the evidence revealed in the tapes has never been published                                                                                                                                           , Far from being thanked for their whistleblowing, Johnson and Bermingham were separately prosecuted by the UK's Serious Fraud Office (SFO) for taking part in a much smaller kind of interest rate "rigging" which in most countries of the world is not seen as criminal.                       , Both Johnson and Bermingham were convicted and jailed as part of what traders allegeis a whole series of miscarriages of justice involving nine criminal trials on both sides of the Atlantic.                                                                                                  , After initially defending himself, Johnson chose not to fight the charges and pleaded guilty in 2014 to conspiring to manipulate Libor.                                                                                                                                                         , Bermingham was found guilty in 2019 of conspiring to manipulate the sister rate of Libor, Euribor, and jailed for five years.                                                                                                                                                                   , In all, 38 traders and brokers have been prosecuted, 24 of them in the UK and 14 in the United States, for “rigging” two benchmark interest rates, Libor and Euribor. In nine trials, seven of them in the UK, more have been acquitted than convicted as juries doubted the case against them. , None of the senior Barclays figures contacted by the BBC wanted to comment, but former Barclays boss Diamond has maintained there was no government or Bank of England pressure to lowball and has denied knowledge of it at the time.                                                          , The Bank of England has also denied that it put pressure on banks to lowball and stated that Libor was not regulated at the time.                                                                                                                                                               , The SFO said it carried out a thorough investigation into lowballing but concluded that the test for prosecution was not met.                                                                                                                                                                   , The Federal Reserve declined to comment. But in a statement from 2012, it said it had received “occasional anecdotal reports from Barclays of problems with Libor” in 2007, and shared suggestions for reform with relevant UK authorities.                                                     , Libor is currently being replaced with a different method of setting market interest rates.                                                                                                                                                                                                     , Start watching series 6 of Peaky Blinders on BBC iPlayer                                                                                                                                                                                                                                        , Watch this ultimate recap to make sure you didn't miss anything from Peaky Blinders                                                                                                                                                                                                             , Cillian Murphy shared what the whole-decade experience on Peaky Blinders means to him                                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 07:38:00 </td>
   <td style="text-align:left;"> US Futures Steady Amid Ukraine Crisis </td>
   <td style="text-align:left;"> US stock futures were steady in early Asian trade on Tuesday after the major averages ended mixed in the previous session, as investors continue to monitor developments surrounding the Russia-Ukraine conflict. Contracts tied to the three major indexes swung between small gains and losses. In regular trading on Monday, the Nasdaq Composite advanced 0.41% for its third straight day of gains, while the Dow and S&amp;P 500 snapped a 2-day rally to end 0.49% and 0.24% lower, respectively. The moves came as Russian forces continued to advance into Ukraine, prompting Western nations to ramp up economic and financial sanctions. The Bank of Russia more than doubled its key interest rate in an emergency move on Monday to support a plummeting ruble and suspended equity trading at the Moscow Exchange. Meanwhile, investors look ahead to Federal Reserve chair Jerome Powell's appearance in Congress on Wednesday and the release of US manufacturing PMI data on Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-01 07:05:36 </td>
   <td style="text-align:left;"> Oil Prices Post Third Monthly Gain </td>
   <td style="text-align:left;"> WTI crude oil surged almost 5% to above $96 a barrel on Monday, recording its third consecutive monthly gain after Western nations imposed fresh sanctions on Russia, raising fears of supply disruptions from one of the world's largest oil and gas producers. This massive rally that saw the US benchmark top $100 for the first time since 2014 earlier this month already prompted discussions about a coordinated release of about 60 million barrels of oil from the US and its ally's emergency oil reserves to cool markets. Meanwhile, OPEC+ is likely to stick to a planned output rise at a meeting this week, while investors are also closely monitoring the Iran nuclear talks amid signs of progress. A potential deal could add more than 1 million barrels a day of supply and help ease a tight global market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/28/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-03-01 07:02:58 </td>
   <td style="text-align:left;"> Stock futures rise ahead of first trading day of March, Russia-Ukraine conflict in focus </td>
   <td style="text-align:left;"> , U.S. stock futures rose in overnight trading on Monday before the first trading day of March as investors continue to monitor the fighting between Russia and Ukraine.                                                                                                                                                                                                                                   , Dow futures rose about 70 points. S&amp;P 500 futures added 0.2% and Nasdaq 100 futures increased 0.2%.                                                                                                                                                                                                                                                                                                      , In a volatile session on Monday, the Dow Jones Industrial Average lost nearly 170 points. The S&amp;P 500 dropped 0.24% and the Nasdaq Composite rose 0.4%.                                                                                                                                                                                                                                                  , The moves come amid fighting between Russia and Ukraine, where Ukrainian forces have held key cities including the capital of Kyiv.                                                                                                                                                                                                                                                                      , Ukrainian and Russian officials wrapped up a critical round of talks Monday.                                                                                                                                                                                                                                                                                                                             , Meanwhile, the central bank of Russia more than doubled its key interest rate on Monday, as the ruble plummeted after heavy sanctions were imposed on Moscow by the West.                                                                                                                                                                                                                                , JPMorgan's Marko Kolanovic said Monday the worst of the Russia-Ukraine sell-off might be over.                                                                                                                                                                                                                                                                                                           , "The Russia/Ukraine crisis will continue to produce market volatility, but the direct impact on corporate earnings should be small. Indirect risks are more substantial, given effects of higher commodity prices on inflation, growth, and consumers," Kolanovic said in a Monday afternoon note. "However, one silver lining is that the crisis forced a dovish reassessment of the Fed by the market.", Investors are also gearing up to hear from Federal Reserve Chair Jerome Powell in his semiannual hearing at House Committee on Financial Services, which begins on Wednesday.                                                                                                                                                                                                                            , Monday also marked the final trading day of February. The Dow lost 3.5% in February. The S&amp;P 500 and Nasdaq fell 3.1% and 3.4%, respectively, this month.                                                                                                                                                                                                                                                , Looking to Tuesday, big box retailer Target reports earnings before the bell and cloud giant Salesforce reports after the close.                                                                                                                                                                                                                                                                         , On the economic front, February's Markit Manufacturing PMI will be released at 9:45 a.m. on Tuesday. ISM manufacturing PMI for February will be out at 10:00 a.m.                                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-03-01 07:01:26 </td>
   <td style="text-align:left;"> Australia Manufacturing PMI Rebounds in February </td>
   <td style="text-align:left;"> The Ai Group Manufacturing PMI Index rose by 4.8 points to 53.2 in February of 2022, rebounding from a sharp decline recorded in the December 2021-January 2022 period. The latest reading shows that Australian manufacturing is recovering from the disruptions in output, sales and activity during the summer holiday months due to widespread coronavirus infections, labour shortages and supply chain bottlenecks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/industrial-sentiment </td>
   <td style="text-align:left;"> 2022-03-01 06:52:44 </td>
   <td style="text-align:left;"> Australia Markit PMI Revised Lower </td>
   <td style="text-align:left;"> The IHS Markit Australia Manufacturing PMI was revised lower to 57.0 in February of 2022 from a preliminary of 57.6. Still, manufacturing output returned to expansion following a brief month of contraction at the start of 2022 while new order growth accelerated. Employment conditions improved while purchasing activity rose among firms. As a result, price pressures worsened with input costs and output prices rising faster. Finally, business confidence amongst manufacturers improved in hopes of recovery from the latest COVID-19 wave. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uranium </td>
   <td style="text-align:left;"> 2022-03-01 06:43:50 </td>
   <td style="text-align:left;"> Uranium Rally Gains Steam </td>
   <td style="text-align:left;"> Uranium futures were trading above $46 per pound, a mark not seen in over a month, and closing on its highest level since November 2021 amid an upbeat global outlook for nuclear energy following the Russian invasion of Ukraine. The outbreak of war in eastern Europe and the impact of sanctions could reshape the energy transition debate, particularly in Europe, given the region's high dependency on Russian energy commodities. President Emmanuel Macron said that France would construct as many as fourteen new nuclear power to reduce its energy consumption while increasing its carbon-free energy production capacity. Germany is set to follow the trend into alternative and renewable energies and has already signalled that it might consider keeping its nuclear plants online. On the supply side, Cameco has announced plans to restart uranium production at McArthur River/Key Lake, idled since 2018, as the market strengthens. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ev-startup-canoo-posts-wider/story.aspx?guid={FC1A8980-FB26-4E21-B6B6-D3D73F2B0A90}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 06:41:37 </td>
   <td style="text-align:left;"> EV startup Canoo posts wider quarterly loss  - MarketWatch </td>
   <td style="text-align:left;"> Shares of Canoo Inc. 
        GOEV,
        -0.17%
       fell more than 7% in the extended session Monday after the electric-vehicle startup reported a wider-than-expected quarterly loss. Canoo said it lost $138.1 million, or 60 cents a share, in the fourth quarter, compared with a loss of $9.2 million, or 6 cents a share,  in the year-ago quarter. FactSet consensus, drawn from four analyst estimates, called for a loss of 51 cents a share for the quarter. Canoo, which went public in December 2020 after a merger with a blank-check company, said it ended the quarter with cash and equivalents of $224.7 million. Canoo is a pre-revenue company, and its plans include an electric delivery van and a pickup truck. "We continue to make key progress and recently executed multiple agreements with the state of Oklahoma, including for the purchase of 1,000 vehicles," Chief Executive Tony Aquila said in a statement.                                                                                                                                                                                                                                                                                                                                                                                                                , Shares of EPAM Systems Inc. undefined tumbled 9.8% to pace all S&amp;P 500 undefined components in premarket losses, after the provider of digital platform engineering services said it was withdrawing its financial guidance as a result of "military actions" in Ukraine. The company had said in its fourth-quarter earnings report out Feb. 17 that it expected first-quarter revenue of $1.17 billion to $1.18 billion and 2022 revenue of at least $5.15 billion, which compared with the FactSet consensus at the end of January for first-quarter revenue of $1.11 billion and 2022 revenue of $4.87 billion. EPAM said in its 10-K annual report filing late Friday that its largest delivery centers were located in Ukraine, Belarus and Russia. As of Dec. 31, it had 12,389 delivery professionals in Ukraine, 9,416 in Belarus and 8,933 in Russia. "EPAM's highest priority is the safety and security of its employees and their families in Ukraine. The company is proactively working to relocate its employees to lower risk locations in Ukraine and neighboring countries." The company stated on Monday. The stock, which tumbled 13.7% last week, is on track to open at the lowest price seen during regular-session hours since March 9, 2021. It has plunged 37.2% over the past three months through Friday, while the S&amp;P 500 slipped 4.6%., Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/28/technology/ukraine-russia-social-media.html </td>
   <td style="text-align:left;"> 2022-03-01 06:39:17 </td>
   <td style="text-align:left;"> Ukraine War Tests the Power of Tech Giants - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Google, Meta, Twitter, Telegram and others are levers in the conflict, caught between demands from Ukraine, Russia, the European Union and the U.S.                                                                                                                                                                                                                                                                                                                                                       , By Adam Satariano and Sheera Frenkel                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Adam Satariano has covered tech in Silicon Valley and in Europe since 2010. Sheera Frenkel has covered cybersecurity, misinformation and social networks for a decade.                                                                                                                                                                                                                                                                                                                                    , Russia’s invasion of Ukraine has become a defining geopolitical moment for some of the world’s biggest tech companies, as their platforms have turned into major battlefields for a parallel information war and their data and services have become vital links in the conflict.                                                                                                                                                                                                                         , Over the last few days, Google, Meta, Twitter, Telegram and others have been forced to grapple with how to wield that power, caught between escalating demands by Ukrainian, Russian, European Union and U.S. officials.                                                                                                                                                                                                                                                                                  , On Friday, Ukrainian leaders pleaded with Apple, Meta and Google to restrict their services inside Russia. Then Google and Meta, which owns Facebook, barred Russian state-run media from selling ads on their platforms. Sundar Pichai, Google’s chief executive, also spoke with top European Union officials over how to counter Russian disinformation.                                                                                                                                               , At the same time, Telegram, a widely used messaging app in Russia and Ukraine, threatened to shut down channels related to the war because of rampant misinformation. And on Monday, Twitter said it would label all posts containing links to Russian state-affiliated media outlets, and Meta said it would restrict access to some of those outlets across the European Union to ward off war propaganda.                                                                                              , For many of the companies, including Facebook, Google, Twitter, the war is an opportunity to rehabilitate their reputations after facing questions in recent years over privacy, market dominance and how they spread toxic and divisive content. They have a chance to show they can use their technology for good in a way not seen since the Arab Spring in 2011, when social media connected activists and was cheered as an instrument for democracy.                                                , But the tech companies face tricky decisions. Any missteps could be costly, adding more momentum to efforts in Europe and the United States to regulate their businesses or leading Russia to ban them altogether.                                                                                                                                                                                                                                                                                        , Executives inside the companies are making judgment calls about what to do, employees said. If Google, Meta, Twitter and others take some steps and not others, they might be accused of doing too little and looking halfhearted. But curbing too many services and information might also cut off ordinary Russians from the digital conversations that can counteract state-run propaganda.                                                                                                            , “These companies want all the benefits of monopolizing the world’s communications with none of the responsibility of getting swept up in geopolitics and having to choose sides,” said Yael Eisenstat, a fellow at the Berggruen Institute, a Los Angeles think tank, who formerly led Facebook’s election integrity operations. In many ways, she said, tech companies are “in a no-win situation in the midst of an international crisis.”                                                              , Many of the companies have moved gingerly, said Marietje Schaake, a tech policy expert and former member of the European Parliament. While Google and Meta blocked Russian state media from selling ads on their sites last week, the companies did not bar the outlets, as many Western policymakers had urged.                                                                                                                                                                                          , As the conflict has ratcheted up, the companies have taken additional steps. On Sunday, Google’s Maps division stopped displaying traffic information inside Ukraine out of concerns that it could create safety risks by showing where people were gathering. Facebook announced that it had taken down a pro-Kremlin influence campaign and a separate hacking campaign targeting its users in Ukraine.                                                                                                 , On Monday, Twitter began labeling all tweets containing links to Russian state-affiliated media outlets so users would be aware of the information sources. Since the conflict in Ukraine began, users have tweeted links to state-affiliated media about 45,000 times a day, the company said.                                                                                                                                                                                                           , Ms. Schaake, now the international policy director at Stanford University’s Cyber Policy Center, said the measures were not enough. She said the companies must block Russian propaganda outlets and establish clearer policies about their beliefs in human rights and democracy that could be applied beyond Russia.                                                                                                                                                                                    , “The interventions under huge pressure also underline what has not been done for so long,” she said.                                                                                                                                                                                                                                                                                                                                                                                                      , Others warned that there would be negative consequences if the platforms were blocked in Russia. “It’s the most important place for public debate about what’s going on,” said Andrei Soldatov, a Russian journalist and censorship expert. “Nobody would take it as a good sign if Facebook blocked access for Russian citizens.”                                                                                                                                                                        ,  Google did not immediately have a comment. Twitter said it took its role in the conflict seriously. Facebook declined to comment.                                                                                                                                                                                                                                                                                                                                                                        , Telegram’s experience illustrates the competing pressures. The app is popular in Russia and Ukraine for sharing images, videos and information about the war. But it has also become a gathering ground for war misinformation, such as unverified images from battlefields.                                                                                                                                                                                                                              , On Sunday, Pavel Durov, Telegram’s founder, posted to his more than 600,000 followers on the platform that he was considering blocking some war-related channels inside Ukraine and Russia because they could aggravate the conflict and incite ethnic hatred.                                                                                                                                                                                                                                            , Users responded with alarm, saying they relied on Telegram for independent information. Less than an hour later, Mr. Durov reversed course.                                                                                                                                                                                                                                                                                                                                                               , What is at the root of this invasion? Russia considers Ukraine within its natural sphere of influence, and it has grown unnerved at Ukraine’s closeness with the West and the prospect that the country might join NATO or the European Union. While Ukraine is part of neither, it receives financial and military aid from the United States and Europe.                                                                                                                                                , Are these tensions just starting now? Antagonism between the two nations has been simmering since 2014, when the Russian military crossed into Ukrainian territory, after an uprising in Ukraine replaced their Russia-friendly president with a pro-Western government. Then, Russia annexed Crimea and inspired a separatist movement in the east. A cease-fire was negotiated in 2015, but fighting has continued.                                                                                     , How did this invasion unfold? After amassing a military presence near the Ukrainian border for months, on Feb. 21, President Vladimir V. Putin of Russia signed decrees recognizing two pro-Russian breakaway regions in eastern Ukraine. On Feb. 23, he declared the start of a “special military operation” in Ukraine. Several attacks on cities around the country have since unfolded.                                                                                                               , What has Mr. Putin said about the attacks? Mr. Putin said he was acting after receiving a plea for assistance from the leaders of the Russian-backed separatist territories of Donetsk and Luhansk, citing the false accusation that Ukrainian forces had been carrying out ethnic cleansing there and arguing that the very idea of Ukrainian statehood was a fiction.                                                                                                                                   , How has Ukraine responded? On Feb. 23, Ukraine declared a 30-day state of emergency as cyberattacks knocked out government institutions. Following the beginning of the attacks, Volodymyr Zelensky, Ukraine’s president, declared martial law. The foreign minister called the attacks “a full-scale invasion” and called on the world to “stop Putin.”                                                                                                                                                  , How has the rest of the world reacted? The United States, the European Union and others have condemned Russia’s aggression and begun issuing economic sanctions against Russia. Germany announced on Feb. 23 that it would halt certification of a gas pipeline linking it with Russia. China refused to call the attack an “invasion,” but did call for dialogue.                                                                                                                                        , How could this affect the economy? Russia controls vast global resources — natural gas, oil, wheat, palladium and nickel in particular — so the conflict could have far-reaching consequences, prompting spikes in energy and food prices and spooking investors. Global banks are also bracing for the effects of sanctions.                                                                                                                                                                             , “Many users asked us not to consider disabling Telegram channels for the period of the conflict, since we are the only source of information for them,” he wrote. Telegram did not respond to a request for comment.                                                                                                                                                                                                                                                                                      , Inside Meta, which also owns Instagram and WhatsApp, the situation has been “chaotic” because of the volume of Russian disinformation on its apps, said two employees, who were not authorized to speak publicly. Russian experts on Meta’s security team, which identifies and removes state-sponsored disinformation from Facebook and Instagram, have been working around the clock and communicating regularly with Twitter, YouTube and other companies about their findings, the two employees said., Meta’s security team has long debated whether to restrict Sputnik and Russia Today, two of Russia’s largest state-run media sites, on its platforms or label their posts so they clearly state their source. Russia Today and Sputnik are “critical elements in Russia’s disinformation and propaganda ecosystem,” according to a January report from the State Department.                                                                                                                               , Meta executives had resisted the moves, saying they would anger Russia, the employees said. But after war broke out, Nick Clegg, who heads global affairs for Meta, announced on Monday that the company would restrict access to Russia Today and Sputnik across the European Union.                                                                                                                                                                                                                     , Tech companies now face two main types of war-related demands from governments.                                                                                                                                                                                                                                                                                                                                                                                                                           , Russia is pressuring them to increasingly censor social media posts and other information flows inside the country. Moscow has already heavily restricted access to Facebook and Twitter, with YouTube potentially next. On Monday, Russia demanded that Google block ads carried on its platform related to the war. That followed an order on Sunday to lift restrictions on pro-Kremlin media outlets related to Ukraine, without saying how it would enforce the order.                               , At the same time, Western officials are pushing the companies to block Russian state media and propaganda. On Monday, the leaders of Estonia, Latvia, Lithuania and Poland wrote to Meta, Google, YouTube and Twitter to ask them to suspend pro-Kremlin and official government accounts, including Russia Today and Sputnik.                                                                                                                                                                            , “The online platform providers and tech companies need to take a stand as authoritarian regimes seek to weaponize the openness of our societies to undermine peace and democracy,” the letter said.                                                                                                                                                                                                                                                                                                       , In France, Cédric O, the country’s minister for digital policy, met on Monday with Susan Wojcicki, the head of YouTube. On a call a day earlier, Mr. Pichai, Google’s chief executive, and Vera Jourova and Thierry Breton, two top E.U. policymakers, discussed countering Russian state-sponsored disinformation.                                                                                                                                                                                       , Ukraine’s vice prime minister called on Meta, Apple, Netflix and Google on Friday to restrict access to their services inside Russia to isolate the country. “We need your support,” his letter to YouTube said. American policymakers have also made requests to clamp down on Russian propaganda.                                                                                                                                                                                                       , “What strikes me is the power of the platforms is just so unequivocally recognized,” Ms. Schaake said. “I don’t ever recall seeing such a high-level political push for the companies to do more.”                                                                                                                                                                                                                                                                                                        , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/vroom-stock-falls-after-online/story.aspx?guid={074B688F-F8FD-4A2A-80DD-F2A7E958F42B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 06:25:57 </td>
   <td style="text-align:left;"> Vroom stock falls after online used-car retailer faces headwinds amid higher demand - MarketWatch </td>
   <td style="text-align:left;"> Shares of Vroom Inc. 
        VRM,
        -1.94%
       fell more than 5% in the extended session Monday after the online used-car retailer reported mixed fourth-quarter results, posting a wider-than-expected loss and sales that were above expectations, and called for lower-than-expected sales in the current quarter. Vroom said it lost $130 million, or 95 cents a share, in the quarter, compared with a loss of $61 million, or 44 cents a share, in the year-ago quarter. Adjusted for one-time items, Vroom lost 94 cents a share. Revenue rose 130% to $934.5 million, Vroom said. FactSet consensus called for an adjusted loss of 77 cents a share on sales of $902 million for the company. Vroom sold more vehicles online on "strong" demand for used cars and said there was a "growing consumer acceptance" of its business model, but headwinds included lower margins and higher reconditioning costs due to labor shortages and higher demand for third-party reconditioning companies, Vroom said. Vroom guided for first-quarter revenue of about $875 million, and online sales between 18,000 vehicles and 19,000 vehicles. The analysts surveyed by FactSet are calling for first-quarter revenue of around $1.04 billion. , The Bank of Russia raises its key interest rate to 20% from 9.5%, the highest in almost two decades.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60564781?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-01 06:23:01 </td>
   <td style="text-align:left;"> Canada to ban imports of crude oil from Russia </td>
   <td style="text-align:left;"> Canadian Prime Minister Justin Trudeau has announced a ban on Russian oil imports following the country's invasion of Ukraine.                                                                                          , Mr Trudeau said oil revenues have helped to prop up President Vladimir Putin and Russian oligarchs.                                                                                                                     , Coordinated Western sanctions against Russia have targeted its banks but still accept its oil and gas exports.                                                                                                          , Unlike Europe, Canada is not heavily reliant on Russia's oil exports.                                                                                                                                                   , "While Canada has imported very little amounts in recent years, this measure sends a powerful message," Mr Trudeau told a news conference.                                                                              , Canada imported just C$289m (£170m) worth of energy products in 2021, according to Statistics Canada.                                                                                                                   , Canada is the world's fourth largest producer of oil.                                                                                                                                                                   , Europe, however, is far more reliant on Russia's supplies. A quarter of the European Union's petroleum oil imports come from Russia and about 40% of the EU's natural gas imports.                                      , Refusing to buy its oil and gas would be a very tough sanction from European countries, but policymakers have so far been reluctant to take that step, worried about the impact on energy prices in their own countries., The price of Brent crude rose by 4.6% to $102 barrel on Monday after Western nations imposed new sanctions on Russia - one of the world's largest energy producers.                                                     , While the UK gets most of its imports from Norway and the US, fuel prices in the UK still hit record highs on Monday as the impact of Russia's invasion affected global energy markets.                                 , Russian oil and gas exports make up a fifth of Russia's economy and half of its earnings from exports. The country is the European Union's biggest oil trading partner, according to the latest data from Eurostat.     , Western nations announced at the weekend that they would impose sanctions on Russia's central bank to prevent it from selling its vast reserves to prop up its own banks and companies.                                 , Russia's central bank has build up $630bn in reserves.                                                                                                                                                                  , The White House press secretary Jen Psaki also said that sanctions targeting Russia's energy sector remain on the table.                                                                                                , On Saturday, the EU, the US, the UK and other allies also announced that some Russian banks would be banned from Swift, an international payment system.                                                                , Swift is the global financial artery that allows the smooth and rapid transfer of money across borders.                                                                                                                 , Banning Russia from using Swift will, for example, hit payments for its key energy and agricultural products.                                                                                                           , Start watching series 6 of Peaky Blinders on BBC iPlayer                                                                                                                                                                , Watch this ultimate recap to make sure you didn't miss anything from Peaky Blinders                                                                                                                                     , Cillian Murphy shared what the whole-decade experience on Peaky Blinders means to him                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/zm:us </td>
   <td style="text-align:left;"> 2022-03-01 06:16:05 </td>
   <td style="text-align:left;"> Zoom Video Communications earnings above expectations at 1.29 USD </td>
   <td style="text-align:left;"> Zoom Video Communications (ZM) released earnings per share at 1.29 USD, compared to market expectations of 1.07 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/28/business/lucid-motors-supply-chain-shortage.html </td>
   <td style="text-align:left;"> 2022-03-01 06:15:48 </td>
   <td style="text-align:left;"> Lucid Motors Will Produce Fewer Cars Than Expected - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                               , The electric car start-up cited supply chain problems.                                                                                                                                                                                                                                                                                                                                                                                     , By Jack Ewing                                                                                                                                                                                                                                                                                                                                                                                                                              , Lucid Motors, a fledgling maker of electric cars, on Monday significantly scaled back its production goals for the year, citing supply chain problems.                                                                                                                                                                                                                                                                                     , The company disclosed the new targets as part of its 2021 earnings report and will most likely disappoint investors who had seen the company as a serious challenger to Tesla. Lucid shares fell in after-hours trading.                                                                                                                                                                                                                   , Lucid said it expected to produce 12,000 to 14,000 vehicles this year at its factory in Arizona, down from the 20,000 that its chief executive, Peter Rawlinson, a former Tesla engineer, set as a goal last November.                                                                                                                                                                                                                     , Lucid said that 25,000 customers had placed reservations for its cars, which would translate into $2.4 billion in sales. So far the company has delivered about 300 vehicles.                                                                                                                                                                                                                                                              , The company reported a loss of $1 billion for the three months through December, compared with a loss of $311 million a year earlier. Sales were $26.4 million, compared with $3.6 million in the fourth quarter of 2020. Lucid said it had $6.2 billion in cash at the end of 2021, and also announced plans to build a second factory, in Saudi Arabia. The oil kingdom’s sovereign wealth fund is one of the largest investors in Lucid., “We remain confident in our ability to capture the tremendous opportunities ahead given our technology leadership and strong demand for our cars,” Mr. Rawlinson said in a statement.                                                                                                                                                                                                                                                      , Lucid’s first car, the $169,000 Lucid Air Dream Edition sedan, won praise for its workmanship and the ability to travel a record 520 miles on a single charge. MotorTrend magazine declared it the car of the year. The company’s stock surged last fall as stock market investors became increasingly enthusiastic about the prospects for electric cars.                                                                                 , But the shares have slumped since peaking in November as investors waited to see if Lucid could make vehicles in large numbers and become a serious challenger to Tesla, which nearly doubled its global sales in 2021.                                                                                                                                                                                                                    , “It’s been our decision not to compromise quality for quantity,” Mr. Rawlinson said in an interview on Monday evening, adding that he was “more bullish than ever” about the company’s ability to offer more affordable vehicles and an S.U.V.                                                                                                                                                                                             , He said the supply problems were related to relatively low-tech products like exterior trim rather than the semiconductor shortages that have plagued other carmakers.                                                                                                                                                                                                                                                                     , The leap from prototype to mass production has been difficult for other start-ups, too. Shares of Rivian, a maker of electric pickup trucks that also received rave reviews, have plummeted after the company failed to to meet a modest goal of producing 1,200 vehicles for individual buyers in 2021.                                                                                                                                   , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60564265?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-01 06:15:05 </td>
   <td style="text-align:left;"> Shell to sell Russian investments due to Ukraine conflict </td>
   <td style="text-align:left;"> Shell is to end all of its joint ventures with the Russian energy company Gazprom following the invasion of Ukraine.                                                                                                                                                                                                                                      , The move will include the oil giant's 27.5% stake in a major liquefied natural gas plant.                                                                                                                                                                                                                                                                 , Shell's chief executive, Ben van Beurden, said the company is "shocked by the loss of life in Ukraine".                                                                                                                                                                                                                                                   , It follows similar moves by BP, which is to offload its share in Russian state-owned oil firm Rosneft.                                                                                                                                                                                                                                                    , Shell will quit the flagship Sakhalin II facility, which is 50% owned and operated by Gazprom.                                                                                                                                                                                                                                                            , It will also sell its 50% stake in two Siberian oilfield projects, as well as end its involvement in the Nord Stream 2 gas pipeline from Russia to Germany, which it helped finance among a mix of other companies. The 1,200km pipeline under the Baltic Sea had already been put on hold by German ministers.                                           , In a statement issued on Monday, Shell said that it expects the move, which will also apply to any "related entities" to Gazprom, will be worth about $3bn (£2.2bn).                                                                                                                                                                                      , The associated costs will be marked on its balance sheet later this year.                                                                                                                                                                                                                                                                                 , "Our decision to exit is one we take with conviction," van Beurden said in a statement on Monday.                                                                                                                                                                                                                                                         , "We cannot - and we will not - stand by", he added, describing Russia's actions as "a senseless act of military aggression which threatens European security".                                                                                                                                                                                            , Business Secretary Kwasi Kwarteng voiced his support for Shell's decision on social media.                                                                                                                                                                                                                                                                , Foreign Secretary Liz Truss had earlier named Gazprom as one of the many Russian companies who would be unable to access any funding from UK financial institutions as part of new sanctions.                                                                                                                                                             , As part of the new measures announced, the European Union (EU), US, UK and allies have agreed to remove selected Russian banks from the Swift messaging system, which enables the smooth transfer of money across borders. The move is intended to cut Russia off from the international financial system and to "harm their ability to operate globally"., Major Russian banks are also having their assets frozen and being excluded from the UK financial system. This stops them from accessing pound sterling and clearing payments through the UK.                                                                                                                                                              , And several governments have imposed sanctions on some individuals, including Russia's President Vladimir Putin, the Foreign Minister Sergei Lavrov and a number of members of Russia's oligarch elite.                                                                                                                                                   , Shell's decision follows that of BP, which announced that it would offload its stake in the Russian state-owned oil firm Rosneft, which it has held since 2013.                                                                                                                                                                                           , Its boss Bernard Looney also said he would resign from the board of Rosneft with "immediate effect", having played a part on it since 2000, alongside chairman Igor Sechin, who is a close friend of Russian President Vladimir Putin.                                                                                                                    , Shell didn't take long to follow BP to the exit from Russian oil and gas interests.                                                                                                                                                                                                                                                                       , While nowhere near the scale of BP's potential $25bn (£18.7bn) hit, Shell could see a charge of up to $3bn (£2.2bn) as it offloads any interests in which it is a partner with state-owned gas giant Gazprom.                                                                                                                                             , As with BP, it is unclear how or to whom these businesses will be offloaded and whether they are worth anything.                                                                                                                                                                                                                                          , This will not be the last global company to bring decades-long collaborations to a financially damaging end.                                                                                                                                                                                                                                              , Russia's rapidly-acquired pariah status is prompting a reckoning for company boardrooms around the world.                                                                                                                                                                                                                                                 , It has also prompted a major rethink for the UK government.                                                                                                                                                                                                                                                                                               , Business Secretary Kwasi Kwarteng applauded the decisions by BP and Shell to yield to pressure he helped apply personally. It seems clear the UK government thinks it can no longer afford to be seen - as successive UK governments in the past have been - as an accommodating, unquestioning friend to Russian capital.                                , BP said it is too early to say how or to whom its stake in Rosneft will be sold.                                                                                                                                                                                                                                                                          , The firm will pay an $11bn charge when it writes off foreign exchange losses that have accumulated over the last few years and another charge relating to the value of its stake.                                                                                                                                                                         , Norwegian oil and gas producer Equinor also announced its exit from Russia on Monday, as it said it would begin the process of divesting from its joint ventures in the country.                                                                                                                                                                          , It said the ongoing conflict meant its position was "untenable".                                                                                                                                                                                                                                                                                          , Canadian Prime Minister Justin Trudeau has also announced that Canada will ban crude oil imports from Russia.                                                                                                                                                                                                                                             , Start watching series 6 of Peaky Blinders on BBC iPlayer                                                                                                                                                                                                                                                                                                  , Watch this ultimate recap to make sure you didn't miss anything from Peaky Blinders                                                                                                                                                                                                                                                                       , Cillian Murphy shared what the whole-decade experience on Peaky Blinders means to him                                                                                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-03-01 06:10:28 </td>
   <td style="text-align:left;"> US Natural Gas Fails to Hold Momentum </td>
   <td style="text-align:left;"> US natural gas futures were trading around $4.40/MMBtu, easing from a three-week peak of $4.94 hit in the prior week as the latest weather forecasts backed off the amount of cold that would spill over into March, lowering gas demand for heating. Putting a floor under prices were expectations of solid overseas demand for gas following tighter sanctions against Russia as it continues to invade Ukraine. Meanwhile, domestic natural gas inventory levels declined by 129 billion cubic feet last week, less than market forecasts of a 134 bcf draw. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/goodrx-stock-tumbles-30-after/story.aspx?guid={6C9D62A5-3BC4-4F60-9AFC-FD6F4ED26893}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 06:07:21 </td>
   <td style="text-align:left;"> GoodRx stock tumbles 30% after Q4 miss - MarketWatch </td>
   <td style="text-align:left;"> Shares of GoodRx Holdings Inc. 
        GDRX,
        +4.22%
       fell more than 30% in the extended session Monday after the health care company reported adjusted quarterly earnings below Wall Street expectations and sales also disappointed. The company said it lost $39.9 million, or 10 cents a share, in the fourth quarter, compared with a loss of $298.3 million, or 74 cents a share, in the year-ago period. Adjusted for one-time items, GoodRx earned 9 cents a share. Revenue rose 39% to $213.3 million, the company said. Analysts polled by FactSet expected adjusted earnings of 10 cents a share on sales of $218 million. GoodRx guided for revenue growth of about 23% for 2022. "We see significant opportunities to build on our 2021 growth and success to deliver a very strong 2022, reaching more consumers and providers and bringing more value to each stage of the health care journey," GoodRx said in a letter to investors. Separately, the company said that its board approved a share buyback program of up to $250 million. As of Dec. 31, GoodRx had cash and equivalents of $941.1 million, it said. GoodRx stock ended the regular trading day up 4.2%. , Emmy season is upon us and streaming services are launching their biggest shows, from 'Bridgerton' to 'Pachinko' to 'Halo.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/28/business/russia-oil-companies.html </td>
   <td style="text-align:left;"> 2022-03-01 05:56:58 </td>
   <td style="text-align:left;"> Shell Quits Russia, Joining BP as Oil Giants Object to Attack on Ukraine - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Shell said it would exit its investments in Russia, a day after BP said it would do the same. Now companies like TotalEnergies and Exxon will face questions.                                                                                                                                                                                                                                                                                                                                                                                                     , By Stanley Reed                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Shell, Europe’s largest oil company, said on Monday that it would exit its joint ventures with Gazprom, the Russian natural gas giant. It is joining BP, which said on Sunday that it would sell its nearly 20 percent stake in Rosneft, the Russian state-controlled oil company.                                                                                                                                                                                                                                                                                , The twin declarations, each involving investments of billions of dollars, displayed a sudden revulsion in dealing with Moscow as the Russian army assaults Ukraine and forces hundreds of thousands of refugees to flee.                                                                                                                                                                                                                                                                                                                                          , They also highlighted a remarkable reversal of sentiment in an industry that has worked diligently for decades to land Russian projects.                                                                                                                                                                                                                                                                                                                                                                                                                          , Shell had been careful to cultivate a strategic relationship with Gazprom, even providing financing and guarantees for the controversial Nord Stream 2 pipeline from Russia to Germany, which is now blocked.                                                                                                                                                                                                                                                                                                                                                     , That’s all over now.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , “We are shocked by the loss of life in Ukraine, which we deplore, resulting from a senseless act of military aggression,” Ben van Beurden, Shell’s chief executive, said in a statement. The investment in Russia was worth about $3 billion.                                                                                                                                                                                                                                                                                                                     , The oil giants’ investments in Russia have become embarrassments and targets for politicians as anger grows over President Vladimir V. Putin’s invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                               , Shell’s decision will put pressure on TotalEnergies, the French giant, to sell its considerable Russian gas holdings. Exxon Mobil also has a sizable Russian project.                                                                                                                                                                                                                                                                                                                                                                                             , There is much at stake here for both Russia and the Western companies, including loss of profits, but not as much as there might have been had the crisis in Ukraine occurred a decade or two ago. Even before this invasion, foreign oil developments in Russia had slowed sharply, partly because of sanctions imposed after Mr. Putin’s annexation of Crimea in 2014. Growing climate change concerns also may increasingly make Russian investments look expendable.                                                                                          , In addition, Russian oil and gas companies have had years to study the technology that Western oil companies brought with them, including modern well-enhancing techniques like fracking and drilling horizontally from service companies like Schlumberger.                                                                                                                                                                                                                                                                                                      , Thane Gustafson, author of “Wheel of Fortune,” an account of the Russian oil industry after the fall of the Soviet Union, recalled that the oil executives who were instrumental in establishing their companies in Russia — John Browne of BP, Rex W. Tillerson of Exxon Mobil, and Christophe de Margerie of TotalEnergies — were “hailed at the time, and rightly, as models of Western entrepreneurship.”                                                                                                                                                     , Now, he said, “the participation of the three brand-name majors at this moment is not crucial for Russia, no.” And the momentum to leave Russia is building.                                                                                                                                                                                                                                                                                                                                                                                                      , On Monday, Equinor, the Norwegian energy company, said it would “stop new investments into Russia” and “start the process of exiting” joint ventures there. “In the current situation, we regard our position as untenable,” Anders Opedal, the company’s president and chief executive, said in a statement.                                                                                                                                                                                                                                                     , Equinor’s investments in Russia are small, producing about 30,000 barrels a day, around 1.5 percent of the company’s total output, but calls for others to leave are continuing.                                                                                                                                                                                                                                                                                                                                                                                  , All of the Western oil companies’ deals in Russia over the last three decades must now be considered at risk, although the extent of their activities there and their importance to their overall results varies. While even a complete write-off — a possibility for BP — would not threaten the existence of any of the companies in this group, analysts say, losing a foothold in a major petroleum producer will still hurt.                                                                                                                                 , In turn, Russia could lose the marketing power of these giant companies, making it more difficult to sell Russian oil while sanctions are already making buyers cautious.                                                                                                                                                                                                                                                                                                                                                                                         , After the fall of the Soviet Union in 1991, oil companies headed to Russia and its vast quantities of oil and gas, partly in hopes of replacing the resources they had lost to nationalizations in Saudi Arabia, Iran and other countries.                                                                                                                                                                                                                                                                                                                        , “If you look back 15 to 20 years ago, the assumption was that Russia would become a normal part of the European economic system,” said Stuart Joyner, an analyst at Redburn, a research firm.                                                                                                                                                                                                                                                                                                                                                                     , BP took the most difficult yet potentially rewarding approach, investing $8 billion in a joint venture called TNK-BP in 2003 with a group of Russian oligarchs and applying its technology and know-how to improve operations. The venture flourished in its early years, but disagreements among the partners flared, and BP sold its share to Rosneft, taking $12.5 billion in cash and a large stake in the Russian company.                                                                                                                                   , A rising concern. Russia’s attack on Ukraine could cause dizzying spikes in prices for energy and food and could spook investors. The economic damage from supply disruptions and economic sanctions would be severe in some countries and industries and unnoticed in others.                                                                                                                                                                                                                                                                                    , The cost of energy. Oil prices already are the highest since 2014, and they have risen as the conflict has escalated. Russia is the third-largest producer of oil, providing roughly one of every 10 barrels the global economy consumes.                                                                                                                                                                                                                                                                                                                         , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders have accused Russia’s president, Vladimir V. Putin, of reducing supplies to gain a political edge.                                                                                                                                                                                                                                                              , Food prices. Russia is the world’s largest supplier of wheat and, together with Ukraine, accounts for nearly a quarter of total global exports. In countries like Egypt and Turkey, that flow of grain makes up more than 70 percent of wheat imports.                                                                                                                                                                                                                                                                                                            , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                                                                                                                                                                                                     , Financial turmoil. Global banks are bracing for the effects of sanctions designed to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                                                                                                                                                                                                              , But BP’s connection to Russia became increasingly untenable under Mr. Putin and his aggressive approach to his neighbors. BP’s chief executive, Bernard Looney, and his predecessor, Bob Dudley, who earlier in his career ran TNK-BP, have also resigned from the Rosneft board.                                                                                                                                                                                                                                                                                 , It was not acceptable in Britain, which has taken a hard line against Moscow over Ukraine, for them to be participating on a board alongside the likes of Igor Sechin, a longtime associate of Mr. Putin, who is chief executive of Rosneft.                                                                                                                                                                                                                                                                                                                      , “BP finds itself caught for the best of reasons by the changing world,” said Mr. Gustafson, who is a professor at Georgetown University.                                                                                                                                                                                                                                                                                                                                                                                                                          , Even though some analysts applauded BP’s announcement, many investors were apparently rattled by the news that BP would lose about one-third of its reported oil and gas production and substantial profits that came to $2.4 billion last year. BP’s shares fell sharply in trading on Monday.                                                                                                                                                                                                                                                                   , Shell, which only recently moved its headquarters to London from the Netherlands, said it would exit four joint ventures that it has with Gazprom and its subsidiaries. The most important of these is a minority but valuable holding in a liquefied natural gas facility on Sakhalin, an island in Russia’s Far East. Shell also will be pulling out of an oil joint venture called Salym IV, as well as ending its involvement with Nord Stream 2.                                                                                                             , Shell said it would be taking an unspecified write-off. But, in an indication that management does not expect that leaving Russia will do major damage to earnings, the company said it planned to increase its dividend by 4 percent for the first quarter and continue with $8.5 billion in share buybacks.                                                                                                                                                                                                                                                     , After the departure of BP and Shell, the oil company with the most at risk in Russia is TotalEnergies. The Paris-based company owns about 19 percent of Novatek, a Russian gas company, and a minority stake in a $27 billion natural gas export facility called Yamal LNG in the Russian Arctic. Giacomo Romeo, an analyst at Jefferies, an investment bank, said that supplies from the Yamal venture are vital to Total’s liquefied gas business, which in turn is an important pillar in the company’s efforts to reduce the carbon emissions of its products., Total along with Shell has played a crucial role in bringing advanced liquefied natural gas technology to Russia. Total’s shares also plunged Monday as investors worried that the French company would follow BP out the Russian door.                                                                                                                                                                                                                                                                                                                           , Exxon Mobil has produced oil for a quarter-century from the same area as Shell, but the oil flow is only around 2 percent of the company’s global total.                                                                                                                                                                                                                                                                                                                                                                                                          , Exxon did not respond to a request for comment, and Total declined to comment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , In the current environment, all of these investments look like holdovers from a more promising past rather than bases that could be built on in the future.                                                                                                                                                                                                                                                                                                                                                                                                       , Clifford Krauss contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60550992?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-01 05:50:23 </td>
   <td style="text-align:left;"> Ukraine conflict: Russia doubles interest rate after rouble slumps </td>
   <td style="text-align:left;"> Russia has more than doubled its interest rate to 20% in a bid to halt a slump in the value of its currency.                                                                                                                                                                                                                                                                   , The Bank of Russia raised the rate from 9.5% after the rouble sank 30% after new Western sanctions. The currency then eased back to about 20% down.                                                                                                                                                                                                                            , The collapse in value erodes the currency's buying power and could wipe out the savings of ordinary Russians.                                                                                                                                                                                                                                                                  , Amid pictures at the weekend of queues at cash machines, Russia said it had the resources to ride out sanctions.                                                                                                                                                                                                                                                               , President Vladimir Putin on Monday responded to the sanctions with an order barring citizens from transferring money outside of Russia, including for debt payments. Moscow's stock market, which saw heavy losses last week as investors sold, is to be closed for a second day on Tuesday.                                                                                   , Ahead of an emergency meeting between President Vladimir Putin and his economic advisers on Monday, Kremlin spokesman Dmitry Peskov said: "These are heavy sanctions, they're problematic, but Russia has the necessary potential to compensate the damage from these sanctions."                                                                                              , The UK, along with the US and EU, cut off major Russian banks from financial markets in the West, prohibiting dealings with the central bank, state-owned investment funds and the finance ministry. The moves sent the rouble tumbling.                                                                                                                                       , Chancellor Rishi Sunak said the measures demonstrated the UK's "determination to apply severe economic sanctions in response to Russia's invasion of Ukraine".                                                                                                                                                                                                                 , Russia has about $630bn (£470bn) in reserves - a stockpile of savings - built up from soaring oil and gas prices.                                                                                                                                                                                                                                                              , But because a lot of this money is stored in foreign currencies like the dollar, the euro and sterling as well as gold, the Western ban on dealing with Russia's central bank restricts Moscow from accessing the cash.                                                                                                                                                        , Last week, Russia's central bank was forced to increase the amount of money it supplies to ATMs after demand for cash reached the highest level since March 2020.                                                                                                                                                                                                              , Videos on social media on Sunday appeared to show long queues forming at cash machines and money exchanges in Moscow, with people worried that their bank cards may stop working or that limits will be placed on the amount of cash they can withdraw.                                                                                                                        , Chris Weafer, chief executive at consultancy firm Micro-Advisory and based in Moscow, said on Monday he was seeing some queues in food stores.                                                                                                                                                                                                                                 , "You are beginning to see a little bit of queuing in some grocery stores, particularly people buying some goods that they think might come into short supply due to trade restrictions or maybe will be subject to big price increases because of the rouble devaluation.                                                                                                      , "This set of sanctions is hitting ordinary Russians to an extent that previous sanctions have not and people are now becoming aware of that.                                                                                                                                                                                                                                   , "People are a lot more fearful. There is already talk about some companies having to either go on reduced working hours, or even suspend production because they're not able to access maybe key parts from the West due to sanctions or due to trade limitations, so there's a great deal of concern on the street."                                                          , Moscow resident Anastasia told Reuters that she expected her economic situation to get worse.  "It's inevitable in these circumstances," she added. Whilst another Moscow resident Sergey said he was already seeing an impact. "Prices are rising, of course, savings are shrinking and stocks are falling."                                                                  , On Monday, the central bank said it had ordered brokers to suspend the execution of all orders by foreign legal entities and individuals to sell Russian investments.                                                                                                                                                                                                          , The sanctions that have been imposed by the EU, the US, the UK and others are unprecedented. It's one thing to block the foreign reserves of a country like Iran or Venezuela, quite another to act against Russia - a country with a major role in global trade and a very significant supplier of oil and gas.                                                               , The reaction on the currency markets has been dramatic - with the rouble plummeting, despite the central bank's efforts to prop it up using interest rates. There may already have been a rush to the foreign currency ATMs in Russian cities, but citizens there have yet to feel the full impact.                                                                            , At the very least prices will rise dramatically; banking collapses, hyperinflation and a deep recession are all potential consequences.                                                                                                                                                                                                                                        , But sanctions are a two-way street. Cutting the central bank off from its reserves and limiting Russian institutions' access to the Swift network will not only hurt Russia - western institutions also face losses from debts that cannot or will not be repaid, for example. And then there is the risk of countermeasures from Russia - potentially hitting energy exports. , Such sweeping sanctions being imposed in such a unified way is remarkable. It's also a very big gamble.                                                                                                                                                                                                                                                                        , Attempts to put a stranglehold around Russia's finances reverberated across the financial and corporate world:                                                                                                                                                                                                                                                                 , Will Walker-Arnott, senior investment manager at Charles Stanley, told the BBC's Today programme that "it looks like Russia is increasingly becoming an economic pariah, increasingly isolated from the global financial system".                                                                                                                                              , Cutting some Russian banks from international payments system Swift is among the harshest measure so far imposed to date on Moscow over the Ukraine conflict.                                                                                                                                                                                                                  , The assets of Russia's central bank will also be frozen, limiting the country's ability to access its overseas reserves.                                                                                                                                                                                                                                                       , Russia is heavily reliant on the Swift system for its key oil and gas exports. It was not clear whether those deals would be exempt from the bans.                                                                                                                                                                                                                             , The intention is to "further isolate Russia from the international financial system", a joint statement said.                                                                                                                                                                                                                                                                  , On Monday, the European Central Bank (ECB) said several European subsidiaries of Sberbank Russia, which is Russia's largest bank and majority owned by the Russian government, were failing or likely to fail due to reputational cost of the war in Ukraine.                                                                                                                  , Sberbank Europe AG, which had total assets of €13.64bn (£11.4bn) at the end of last year, along with its Croatian and Slovenian units, suffered a rapid deposit outflow in recent days and is likely to fail to pay its debts or other liabilities, said the ECB, which is the lenders' supervisor.                                                                            , What questions do you have about the Russian invasion of Ukraine?                                                                                                                                                                                                                                                                                                              , In some cases your question will be published, displaying your name, age and location as you provide it, unless you state otherwise. Your contact details will never be published. Please ensure you have read our terms &amp; conditions and privacy policy.                                                                                                                      , Use this form to ask your question:                                                                                                                                                                                                                                                                                                                                            , If you are reading this page and can't see the form you will need to visit the mobile version of the BBC website to submit your question or send them via email to YourQuestions@bbc.co.uk. Please include your name, age and location with any question you send in.                                                                                                          , Start watching series 6 of Peaky Blinders on BBC iPlayer                                                                                                                                                                                                                                                                                                                       , Watch this ultimate recap to make sure you didn't miss anything from Peaky Blinders                                                                                                                                                                                                                                                                                            , Cillian Murphy shared what the whole-decade experience on Peaky Blinders means to him                                                                                                                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/ethanol </td>
   <td style="text-align:left;"> 2022-03-01 05:48:30 </td>
   <td style="text-align:left;"> Ethanol Hits 8-week High </td>
   <td style="text-align:left;"> Ethanol increased to a 8-week high of 2.35 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/28/stocks-making-the-biggest-moves-after-hours-zoom-video-workday-lucid-group-and-more.html </td>
   <td style="text-align:left;"> 2022-03-01 05:46:44 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Zoom Video, Workday, Lucid Group and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                   , Check out the companies making headlines after the bell:                                                                                                                                                                                                                                                                                                                                                          , Workday — Shares of Workday rose more than 5% in after-hours trading on Monday after beating on the top and bottom lines of its quarterly results. The software stock reported EPS of 78 cents per share, topping estimates of 71 cents, according to Refinitiv. Revenue also topped estimates.                                                                                                                   , Zoom Video — Shares of the video conferencing company ticked 2% lower in extended trading on Monday after issuing full-year guidance below what analysts had predicted. Zoom, however, reported earnings of $1.29 per share on revenue of $1.017 billion. Analysts expected earnings of $1.06 on revenue of $1.046 billion, according to Refinitiv. Zoom shares fell as much as 13% in extended trading on Monday., Lucid Group — Shares of Lucid Group tanked more than 10% in after hours trading after its quarterly report. The company reported a wider-than-expected loss of 64 cents, while analysts expected a loss of 25 cents per share, according to Refinitiv. Revenue also missed estimates.                                                                                                                             , Novavax — Shares of Novavax fell 5% after the bell on Monday after missing on the top and bottom line of its quarterly report. The company posted a loss of $11.18 per share. Revenue came in at $222.2 million.                                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/28/world/europe/russia-economy-sanctions-ukraine.html </td>
   <td style="text-align:left;"> 2022-03-01 05:37:35 </td>
   <td style="text-align:left;"> Russians Face Sanctions and Anxieties of a Costly War - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The ruble plunged, the stock market was shuttered and foreign investors shed holdings in Russian companies, deepening the concern among citizens who had become accustomed to the perks of globalization.                                                                                                                                                                                                                                                                                                                                                                    , By Anton Troianovski and Ivan Nechepurenko                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Photographs by Sergey Ponomarev                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , MOSCOW — For two decades under President Vladimir V. Putin, Russians reaped the bounties of capitalism and globalization: cheap flights, affordable mortgages, a plethora of imported gadgets and cars.                                                                                                                                                                                                                                                                                                                                                                      , On Monday, those perks of modern life were abruptly disappearing, replaced by a crush of anxiety as sanctions imposed by the West in retaliation for Moscow’s invasion of Ukraine rattled the foundations of Russia’s financial system.                                                                                                                                                                                                                                                                                                                                      , The ruble cratered, losing a quarter of its value, and the central bank shuttered stock trading in Moscow through Tuesday. The public rushed to withdraw cash from A.T.M.’s, and Aeroflot, the national airline, canceled all its flights to Europe after countries banned Russian planes from using their air space. Concern about travel was so great that some people rushed to book seats on the few international flights still operating.                                                                                                                              , “I’ve become one concentrated ball of fear,” said the owner of a small advertising agency in Moscow, Azaliya Idrisova, 33. She said she planned to depart for Argentina in the coming days and was not sure whether her clients would still pay her.                                                                                                                                                                                                                                                                                                                         , Compounding the pain was the decision by Western countries to restrict the Russian Central Bank’s access to much of its $643 billion in foreign currency reserves, undoing some of the Kremlin’s careful efforts to soften the impact of potential sanctions and making it difficult for the bank to prop up the ruble.                                                                                                                                                                                                                                                      , Note: Scale is inverted to show the decline in the ruble’s value. Price as of 5:00 p.m. Eastern.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , By The New York Times                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Other moves struck at the heart of critical Russian industries. Shell, a company that for years helped Russia profit from its energy riches, said it was exiting all its joint ventures with Gazprom, Russia’s largest state-owned natural gas company — following BP’s announcement Sunday it would sell its stake in the Russian state-run oil giant Rosneft. Volvo said it would stop production at its truck factory in Russia, and Mercedes-Benz said it would drop its partnership with a Russian truck maker.                                                         , And in a sign of how the sanctions were hitting regular Russians in ways big and small, Apple Pay and Google Pay stopped working at many of Moscow’s subway turnstiles — the ones operated by a bank on the American sanctions list.                                                                                                                                                                                                                                                                                                                                         , For many Russians opposed to the war, those hardships paled in comparison to the moral cost of seeing their country launch an unprovoked invasion. Antiwar protests continued across Russia, with at least 411 people detained in 13 cities, according to OVD Info, a rights group that tallies arrests, for a total of at least 6,435 detentions since last Thursday.                                                                                                                                                                                                       , But the financial jolt offered tangible evidence of the West’s outrage, one that is now washing over Russia’s economy with unpredictable consequences.                                                                                                                                                                                                                                                                                                                                                                                                                       , The sanctions announced by the European Union and the United States over the weekend, J.P. Morgan analysts wrote to clients on Monday, “are more severe and wider than even the more extreme sanctions we had believed were in play just a month ago.” By Monday evening, the European Union had added more Russian business tycoons to its sanctions list, including two owners of Alfa Bank, Mikhail Fridman and Petr Aven, who had cut a relatively Western-friendly image.                                                                                               , Some analysts worried that the wide-ranging sanctions, combined with Ukraine’s ferocious resistance on the battlefield, could lead Mr. Putin to escalate the crisis. The Defense Ministry issued a statement saying that the bombers, submarines and land-based launchers that make up Russia’s nuclear “triad” had been put on “enhanced combat duty,” as Mr. Putin had ordered on Sunday. Rumors circulated that men could be called up if the military got bogged down in Ukraine.                                                                                        , “I realized that this government has gone utterly mad,” said Ivan Petrov, 28, a Moscow machine learning engineer who flew to the Egyptian resort of Hurghada over the weekend, fearing the war in Ukraine could escalate to the point that he might get drafted. His next goal: Find a job in the West.                                                                                                                                                                                                                                                                      , “Earning in rubles seems absolutely pointless,” Mr. Petrov said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , On Monday, the sanctions’ full force hit Russia’s already stagnant economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Russia’s Central Bank, its reserves largely frozen, more than doubled its key rate to 20 percent to try to stabilize the ruble. A dollar cost more than 110 rubles at kiosks in Moscow on Monday compared with about 80 a week earlier, potentially devaluing people’s savings given the likely increase in the price of imported goods. In trading in London, shares of Sberbank, Russia’s largest bank, lost three-quarters of their value. The vice president of the country’s real estate agents’ association declared that Russians could say “goodbye to the mortgage.”, To stem the flight of capital, Mr. Putin on Monday signed an order rolling back some of the free-market capitalism that had integrated post-Soviet Russia into the world economy. Russian exporters were required to convert 80 percent of their foreign-currency revenues since Jan. 1 into rubles; residents of Russia were banned from depositing money into accounts outside the country.                                                                                                                                                                                , Mr. Putin called an emergency meeting on the economy with senior officials, in which he repeated his reference last week to the West as an “empire of lies.”                                                                                                                                                                                                                                                                                                                                                                                                                 , “Our financial system and our economy have collided with a totally non-standard situation,” Elvira Nabiullina, the head of the Central Bank, said afterward.                                                                                                                                                                                                                                                                                                                                                                                                                 , What is at the root of this invasion? Russia considers Ukraine within its natural sphere of influence, and it has grown unnerved at Ukraine’s closeness with the West and the prospect that the country might join NATO or the European Union. While Ukraine is part of neither, it receives financial and military aid from the United States and Europe.                                                                                                                                                                                                                   , Are these tensions just starting now? Antagonism between the two nations has been simmering since 2014, when the Russian military crossed into Ukrainian territory, after an uprising in Ukraine replaced their Russia-friendly president with a pro-Western government. Then, Russia annexed Crimea and inspired a separatist movement in the east. A cease-fire was negotiated in 2015, but fighting has continued.                                                                                                                                                        , How did this invasion unfold? After amassing a military presence near the Ukrainian border for months, on Feb. 21, President Vladimir V. Putin of Russia signed decrees recognizing two pro-Russian breakaway regions in eastern Ukraine. On Feb. 23, he declared the start of a “special military operation” in Ukraine. Several attacks on cities around the country have since unfolded.                                                                                                                                                                                  , What has Mr. Putin said about the attacks? Mr. Putin said he was acting after receiving a plea for assistance from the leaders of the Russian-backed separatist territories of Donetsk and Luhansk, citing the false accusation that Ukrainian forces had been carrying out ethnic cleansing there and arguing that the very idea of Ukrainian statehood was a fiction.                                                                                                                                                                                                      , How has Ukraine responded? On Feb. 23, Ukraine declared a 30-day state of emergency as cyberattacks knocked out government institutions. Following the beginning of the attacks, Volodymyr Zelensky, Ukraine’s president, declared martial law. The foreign minister called the attacks “a full-scale invasion” and called on the world to “stop Putin.”                                                                                                                                                                                                                     , How has the rest of the world reacted? The United States, the European Union and others have condemned Russia’s aggression and begun issuing economic sanctions against Russia. Germany announced on Feb. 23 that it would halt certification of a gas pipeline linking it with Russia. China refused to call the attack an “invasion,” but did call for dialogue.                                                                                                                                                                                                           , How could this affect the economy? Russia controls vast global resources — natural gas, oil, wheat, palladium and nickel in particular — so the conflict could have far-reaching consequences, prompting spikes in energy and food prices and spooking investors. Global banks are also bracing for the effects of sanctions.                                                                                                                                                                                                                                                , In a stark sign of the fury in the West over Russia’s attack on Ukraine, even Switzerland — a favorite destination and banking hub of Russian oligarchs and senior Kremlin officials — ditched its traditional neutrality and joined in European sanctions, including personal ones against Mr. Putin and Foreign Minister Sergey V. Lavrov.                                                                                                                                                                                                                                 , There were signs of anger in the elite, though not among the security establishment closest to Mr. Putin. Ms. Nabiullina, who has said in the past that her outfit choices are meant to send messages, wore funereal black. Oleg Deripaska, a sanctioned metals tycoon close to the Kremlin, wrote on social media that he wanted to know “who’s really going to pay for this whole party.” Vyacheslav Markhayev, a lawmaker from Siberia, declared that the Kremlin “hid plans to start a full-scale war against our closest neighbor.”                                     , “Countries should spend money on treating people, on research to defeat cancer, and not on war,” Oleg Tinkov, the billionaire founder of one of Russia’s biggest consumer banks, wrote on Instagram.                                                                                                                                                                                                                                                                                                                                                                         , Stanislav Usaty, owner of a marketing agency in St. Petersburg, said he expected to lose many of his clients because of the higher exchange rate, especially companies selling imports; he said he would probably need to lay off staff. Aleksandra Gridina, the owner of a travel agency in the city, said she would need to raise prices for international tours that her clients had already booked.                                                                                                                                                                      , “It’s a catastrophe for our business,” she said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Still, while there was confusion at the subway turnstiles and lines formed at A.T.M.’s and banks, there was no full-fledged financial panic among the general public. And it was far from clear whether the sanctions would help turn more Russians against the war — or whether they would only increase their resentment of the West, confirming the Kremlin narrative that the United States and Europe were determined to dismantle their country.                                                                                                                       , “Times change, much has happened, but one thing has not changed,” a reporter on the state-run news channel Rossiya 24 said on Sunday. “When a united Europe tried to destroy Russia, this always ended up bringing about the opposite result.”                                                                                                                                                                                                                                                                                                                               , The backbone of Mr. Putin’s power is made up of security officials who rarely leave Russia and stand to gain from greater state control over the economy. In the broader public, he draws his core support from pensioners and state employees, who are less sensitive to economic volatility than those in the private sector.                                                                                                                                                                                                                                              , Shopping for groceries in Moscow on Monday, Valentina V. Petrova, 85, who said she used to work on Russia’s Proton space rockets, said the economic troubles did not faze her.                                                                                                                                                                                                                                                                                                                                                                                               , “I think the president did everything right,” she said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Mr. Petrov, the engineer who flew to Egypt, said his parents also supported the war. And older Russians, he noted, had seen their share of ups and downs.                                                                                                                                                                                                                                                                                                                                                                                                                    , “They survived many other Russian crises,” he said. “They’re calm about this.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Alina Lobzina and Oleg Matsnev contributed reporting from Moscow, and Jeanna Smialek from Washington.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/us-fast-food-brands-vulnerable-to-shutdowns-in-russia </td>
   <td style="text-align:left;"> 2022-03-01 05:36:00 </td>
   <td style="text-align:left;"> US fast food brands vulnerable to shutdowns in Russia amid Ukraine conflict </td>
   <td style="text-align:left;"> Jason Birchard, third-generation owner of Ukrainian restaurant Veselka in New York City, is donating a portion of his profits to Ukrainian relief efforts. He calls Putin a 'maniac' and a 'tyrant.'                                                                                       , American fast-food giants with hundreds of locations in Russia could take a hit if the country decides to shut down U.S.-based brands as a way to retaliate against sanctions from the West, as tensions escalate over Russian President Vladimir Putin's ongoing invasion of Ukraine.     , McDonald's, KFC, and Papa John's are particularly vulnerable, according to a new report.                                                                                                                                                                                                   , Close-up McDonalds outdoor sign against blue sky (iStock)                                                                                                                                                                                                                                  , The New York Post reported Monday that the McDonald's corporation – rather than franchisees – owns "the vast majority" of the 847 McDonald's locations in Russia, and another 108 in Ukraine.                                                                                              , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                       , Ukrainian stores have already been shuttered for safety during the attack, and if Russia forces McDonald's locations to shut down it could have a significant impact – altogether, the locations between the two countries account for $2.1 billion or 9% of the company's global revenues., WENDY'S WILL ADD BREAKFAST TO ITS MENUS THIS SPRING IN CANADA                                                                                                                                                                                                                              , Meanwhile, KFC, owned by Yum! Brands, has right at 1,000 restaurants in Russia, and Papa John's has roughly 185.                                                                                                                                                                           , The reason analysts are looking at Russian retaliation via fast food shutdowns as a possibility is because the country has done it before in the not-so-distant past.                                                                                                                      , Photo Credit: iStock (iStock / iStock)                                                                                                                                                                                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                , During Russia's last aggression toward Ukraine in 2014, Russian authorities shut down several McDonald's locations in Moscow after the American company closed its locations in Crimea following Putin's seizure of the Ukrainian territory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 05:36:00 </td>
   <td style="text-align:left;"> TSX Ends Volatile February Higher </td>
   <td style="text-align:left;"> Canadian shares rose for a third session on Monday, with the benchmark S&amp;P/TSX Composite hovering above the 21,100 level to finish February on a slightly high note. Gains in the heavyweight energy sector offset losses among cyclical and financials stocks as investors digested harsh Western sanctions against Russia as it continued to invade Ukraine. On the data front, Canada posted a current account deficit of CAD 0.8 billion in the fourth quarter of 2021, compared to market expectations of CAD 2.3 billion surpluses. Kinross Gold fell nearly 10%, the most on the TSX, and the second-biggest decliner was Maple Leaf Foods, down 5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hpq:us </td>
   <td style="text-align:left;"> 2022-03-01 05:33:51 </td>
   <td style="text-align:left;"> HP earnings above expectations at 1.10 USD </td>
   <td style="text-align:left;"> HP (HPQ) released earnings per share at 1.10 USD, compared to market expectations of 1.04 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/albertsons-unveils-review-assets-businesses/story.aspx?guid={3814DE13-23B5-494A-8D5B-ACA08CC741E3}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 05:17:08 </td>
   <td style="text-align:left;"> Albertsons unveils 'review' of assets, businesses, stock rallies 9% - MarketWatch </td>
   <td style="text-align:left;"> Albertsons Cos. Inc. 
        ACI,
        -1.92%
       said late Monday its board is looking at "potential strategic alternatives aimed at enhancing Albertsons' growth and maximizing shareholder value," including what the company described as "potential strategic or financial transactions" as well as "responding to inquiries." The grocery chain has hired Goldman Sachs and Credit Suisse to serve as financial advisers to assist in the review, it said. "The board believes the continuing strength of our business and the scale of our portfolio of assets warrants a deep and considered review of all possible paths towards maximizing value creation," board co-chair Chan Galbato said in a statement. Albertsons operates more than 2,270 stores in 34 states as well as "growing digital and omnichannel capabilities," the company said. No timetable has been set, and no decisions made, Albertsons said. The company said it won't comment further until further disclosure "is appropriate or necessary." Shares of Albertsons rallied more than 9% in the extended session after the news. The stock ended the regular trading day down 2%.  , Get ready for more 'Upload,' an animated spinoff of 'The Boys,' 'Lucy &amp; Desi' and Lizzo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/bill-browder-putin-could-do-something-really-terrible-to-exert-his-dominance-to-show-hes-not-weak </td>
   <td style="text-align:left;"> 2022-03-01 05:16:33 </td>
   <td style="text-align:left;"> Sanctions have given Putin 'a strong black eye' and has financially 'humiliated' him: Bill Browder </td>
   <td style="text-align:left;"> Hermitage Capital Management CEO discusses if Russia is about to plunge into a financial crisis.                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Hermitage Capital Management founder and CEO Bill Browder joined "The Claman Countdown" Monday to react to the historic sanctions that have sparked a financial meltdown in Russia.                                                                                                                                                                                                                                                                                                                                                                   , BILL BROWDER: Sberbank is down 68% the ruble has gone down by 30%, people are standing in line trying to get their money out of ATM's. It looks like we’ve hit him pretty hard. We’ve given Putin a real strong black eye for what he’s done. I don't think he anticipated this [sanctions]. I think he thought that we weren’t going to be serious about this, but we have been, and we’re seeing it right now.                                                                                                                                      , …                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Putin is a guy who absolutely hates to be humiliated. He’s been humiliated in the financial markets by the west, and he’s being humiliated in the military situation by Ukraine, and I’m sad to say that he’s a guy who doesn’t do humiliation well, and he’s the kind of guy when he gets in a situation like this he just escalates. So I pray for the people of Ukraine, because what’s going to happen next is he’s going to do something really terrible to try to exert his dominance and show that he’s not as weak as he’s looking right now. , WATCH THE FULL ‘CLAMAN COUNTDOWN’ INTERVIEW HERE:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Hermitage Capital Management CEO tells 'The Claman Countdown' Putin is being 'humiliated' on the world stage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/wday:us </td>
   <td style="text-align:left;"> 2022-03-01 05:10:49 </td>
   <td style="text-align:left;"> Workday earnings above expectations at 0.78 USD </td>
   <td style="text-align:left;"> Workday (WDAY) released earnings per share at 0.78 USD, compared to market expectations of 0.71 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-stocks-close-mostly-lower/story.aspx?guid={0B3AB5A7-FABD-4CB6-9C3C-5140E5704A2D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 05:04:09 </td>
   <td style="text-align:left;"> U.S. stocks close mostly lower Monday on heightened Ukraine worries - MarketWatch </td>
   <td style="text-align:left;"> U.S. stock closed mostly lower Monday as investors weighed the latest sanctions against Russia after it attacked Ukraine and Russian President Vladimir Putin raised its nuclear alert level. The S&amp;P 500 
        SPX,
        -0.24%
       ended about 0.3% lower, while the Dow Jones Industrial Average 
        DJIA,
        -0.49%
       fell 0.5% and the Nasdaq Composite 
        COMP,
        +0.41%
       gained 0.4%, according to preliminary FactSet data. The White House said over the weekend that the U.S. and its allies vowed to remove some Russian banks from the Society for Worldwide Interbank Financial Telecommunication, a messaging service that helps banks execute financial transactions.
, We screened for companies that are 30% to 50% off their highs and that now sport more reasonable price/earnings ratios.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 04:30:00 </td>
   <td style="text-align:left;"> US Stocks Close Mixed </td>
   <td style="text-align:left;"> The Dow Jones slipped 169 points, the S&amp;P 500 closed down 0.3%, while the Nasdaq rebounded 0.4 as investors continued to monitor the Russian invasion of Ukraine. G7 nations agreed to exclude Russian banks from SWIFT, and the Biden administration banned US people and companies from doing business with the Bank of Russia, the Russian National Wealth Fund, and the Ministry of Finance. Defense and cybersecurity stocks helped limit Nasdaq losses while the banks sunk drugging down the Dow Jones. Adding to the gloomy mood, the Federal Reserve warned last week that inflation could persist longer than expected unless a shortage of available workers begins to ease. Still, the three major US averages lost roughly 4% in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/28/business/europe-sanctions-russia-leased-planes.html </td>
   <td style="text-align:left;"> 2022-03-01 04:27:40 </td>
   <td style="text-align:left;"> European Sanctions Could Strand Leased Planes in Russia - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                , European companies that have leased hundreds of planes to Russian airlines must now find a way to fly them out.                                                                                                                                                                                                                                                              , By Melissa Eddy                                                                                                                                                                                                                                                                                                                                                              , BERLIN — Western sanctions meant to punish President Vladimir V. Putin of Russia for invading Ukraine may have also dealt a big blow to European companies that leased commercial aircraft to Russian airlines.                                                                                                                                                              , The majority of commercial aircraft flown by Russian companies are leased, more than half of them from companies abroad. Most of those companies are based in Ireland, a member of the European Union, which banned the sale or leasing of aircraft to companies in Russia as part of its sanctions package.                                                                 , At stake is the fate of hundreds of planes worth an estimated $12 billion, according to Ishka, a consulting firm that specializes in the aviation industry. Those based in Ireland are particularly exposed, with $4 billion to $5 billion worth of aircraft in Russia, it said.                                                                                             , The sanctions give companies leasing the planes until March 28 to terminate existing contracts, the Irish government confirmed on Monday.                                                                                                                                                                                                                                    , But getting the planes back won’t be easy. The repatriation of leased planes is normally planned years in advance. Airlines in Russia may not cooperate or may be ordered by Mr. Putin’s government to throw up obstacles. Another challenge is that Europe and Russia have closed their airspaces to each other’s planes.                                                   , “The logistics are immense. We are talking hundreds of planes that need to be flown out,” said Phil Seymour, an aviation specialist with IBA, a consulting firm. He listed off the questions that the companies that own the aircraft now face. “Where in the world can they go? Will they play ball? Will there be any edict from above, telling not to cooperate?” he said., AerCap, the world’s largest leasing company for commercial aircraft, said on Monday that it would fully comply with sanctions requiring it to cease leasing planes to Russian airlines.                                                                                                                                                                                      , Based in Dublin, AerCap is likely to be the company most heavily exposed to the sanctions, with 152 planes valued at nearly $2.5 billion in Russia and Ukraine, according to IBA. Nine other leasing companies based in Ireland also have planes in Russia.                                                                                                                  , In a filing to investors, AerCap said its contracts with Russian airlines, which according to its website include Aeroflot and Rossiya, accounted for roughly 5 percent of its fleet, by value at the end of December.                                                                                                                                                       , The company acknowledged at the end of the year that doing business in places like Russia was inherently risky. AerCap said at the time that recovering planes would be difficult if it was forced to cancel contracts because of government sanctions.                                                                                                                      , A rising concern. Russia’s attack on Ukraine could cause dizzying spikes in prices for energy and food and could spook investors. The economic damage from supply disruptions and economic sanctions would be severe in some countries and industries and unnoticed in others.                                                                                               , The cost of energy. Oil prices already are the highest since 2014, and they have risen as the conflict has escalated. Russia is the third-largest producer of oil, providing roughly one of every 10 barrels the global economy consumes.                                                                                                                                    , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders have accused Russia’s president, Vladimir V. Putin, of reducing supplies to gain a political edge.                                                                         , Food prices. Russia is the world’s largest supplier of wheat and, together with Ukraine, accounts for nearly a quarter of total global exports. In countries like Egypt and Turkey, that flow of grain makes up more than 70 percent of wheat imports.                                                                                                                       , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                , Financial turmoil. Global banks are bracing for the effects of sanctions designed to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                         , “We may encounter obstacles and are likely to incur significant costs and expenses conducting repossessions,” the company said in a securities filing.                                                                                                                                                                                                                       , For a company as large as AerCap — the company had assets of $75 billion at the end of 2021 — the losses could be bearable, aviation experts said. But the sanctions could devastate companies with much smaller fleets and those with greater exposure to Russia.                                                                                                           , Even when plane leasing companies are working with cooperative customers, they have sometimes faced problems. For example, the plane may no longer have the engines that were installed originally because airlines have swapped in others for maintenance or other reasons.                                                                                                 , “It could prove very costly for the lessors,” Mr. Seymour said. Normally before a plane is returned, he said, it has to be brought back into shape, it must have a spotless interior, and the paperwork documenting its maintenance history and any problems must be in order.                                                                                               , If leasing companies were unable to recover their planes, they would end up taking on all of the risk associated with the aircraft, said Paul O’Driscoll, a consultant with Ishka. Once contracts are canceled, Russian airlines no longer have to make payments for planes or maintain them.                                                                                , “The local airline is absolved of its responsibility,” Mr. O’Driscoll said. “You’re really stuck. You have to leave the metal there.”                                                                                                                                                                                                                                        , Niraj Chokshi contributed reporting from New York, and Liz Alderman from Paris.                                                                                                                                                                                                                                                                                              , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/state-of-the-union-biden-plan-lowering-prices-inflation </td>
   <td style="text-align:left;"> 2022-03-01 04:12:32 </td>
   <td style="text-align:left;"> State of the Union: Biden to unveil plan for lowering prices </td>
   <td style="text-align:left;"> West Virginia AG Patrick Morrisey argues 'the Biden administration is administrative state run amok.'
                                                                                                                                                                                                                   , As President Biden prepares to address the nation in his first State of the Union address on Tuesday, the White House has revealed details about the president's plans for lowering prices on everyday items as Americans struggle with inflation at highs not seen in decades.                                             , President Joe Biden is set to deliver his first State of the Union address on Tuesday. (AP Photo/Evan Vucci / AP Newsroom)                                                                                                                                                                                                  , Biden is expected to lay out a four-pronged vision focused on bolstering supply chains, reducing the cost of everyday expenses, enacting further antitrust measures and promoting union labor.                                                                                                                              , The president will tout the growth in the U.S. economy during his first year in office as the country emerged from the COVID-19 pandemic and make a renewed push for American-made products.                                                                                                                                , UKRAINE INVASION NOT AS BIG FOR MARKETS AS INFLATION: BILLIONAIRE INVESTOR CARL ICAHN                                                                                                                                                                                                                                       , Biden will also call on Congress to pass several of the administration's legislative priorities, including raising the minimum wage to $15 an hour, passing federal paid family and medical leave, and enacting laws making it easier for workers to organize.                                                              , President Joe Biden signs a series of executive orders on health care at the White House on Jan. 28, 2021. (AP Photo/Evan Vucci / AP Newsroom)                                                                                                                                                                              , PSAKI PUSHES RENEWABLE ENERGY TO STOP DEPENDENCE ON FOREIGN OIL INSTEAD OF INCREASING US PRODUCTION                                                                                                                                                                                                                         , He is also planning to call on lawmakers to send him legislation that would tackle the deficit by increasing taxes on corporations and on Americans making $400,000 a year or more.                                                                                                                                         , The administration has consistently blamed companies and consolidation in certain sectors for higher prices being paid in several industries, and shipping giants have now become a target.                                                                                                                                 , The sun rises past the cranes and a container ship at the Port of Oakland, California, on Nov. 3, 2021. (Reuters/Ann Saphir / Reuters Photos)                                                                                                                                                                               , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                 , The president is set to announce a new agreement between the Department of Justice and the Federal Maritime Commission aimed at cracking down on major ocean freight companies by hitting large international firms with greater regulations in an effort to promote competition and bring down soaring costs for consumers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/28/snake-island-survivors-ukraine-navy-russia-invasion-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-01 04:01:23 </td>
   <td style="text-align:left;"> Video: Soldiers who cursed out Russian warship are still alive, Ukrainian Navy says - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-futures-mark-highest-finish/story.aspx?guid={DBDB1790-A4B1-4AA2-B8BA-1A273B979B31}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 03:49:34 </td>
   <td style="text-align:left;"> Oil futures mark highest finish since August 2014, up nearly 9% for the month - MarketWatch </td>
   <td style="text-align:left;"> Oil futures finished at a more than seven-year high on Monday, with U.S. prices ending higher for a third straight month, on the back of tougher global sanctions on Russia in retaliation for its invasion of Ukraine. "Traders are reacting more to the risk of a disruption than an actual disruption" to oil supplies, said Colin Cieszynski, chief market strategist at SIA Wealth Management. The price spread between U.S. and global benchmark crude shows that the European energy supply system is at much higher risk of disruption than the North American distribution systems, he said. Still, Cieszynski expects that OPEC+, which meets on Wednesday to decide on April production levels, will want to maintain its "confidence and credibility," which could be "undermined if they are seen as hitting the panic button." West Texas Intermediate crude for April delivery 
        CLJ22,
        +0.32%
       rose $4.13, or 4.5%, to settle at $95.72 a barrel on the New York Mercantile Exchange. That was the highest front-month finish since late August 2014, according to Dow Jones Market Data. For the month, prices rose 8.6%. , We screened for companies that are 30% to 50% off their highs and that now sport more reasonable price/earnings ratios.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/28/politics/us-kyiv-fears/index.html </td>
   <td style="text-align:left;"> 2022-03-01 03:47:07 </td>
   <td style="text-align:left;"> US officials fear the worst is yet to come for Kyiv - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Ukrainian forces have so far managed to stave off Russian ground forces massed less than 20 miles north of the embattled capital Kyiv -- but though they've defied US intelligence predictions that the city would likely fall within one to four days of a full-scale Russian assault, US officials warn that Russian President Vladimir Putin could imminently increase the intensity of the attack.                                                                                                                                                , Stiffer than expected Ukrainian resistance and Russia's own logistical missteps have bogged down Russia's advance, US and western officials say, sparking a fragile optimism. The US has also continued sharing downgraded intelligence with the Ukrainians, including about Russian military moves, in an attempt to help Ukraine on the battlefield, two of the sources told CNN.                                                                                                                                                                         , But intelligence and defense officials closely tracking the Russian campaign say that Putin still holds a number of moves in reserve that could devastate the Ukrainian resistance.                                                                                                                                                                                                                                                                                                                                                                         , "From a purely military/tactical standpoint, Russia has the manpower and firepower to take Kyiv. No question," said an American source familiar with the intelligence. "And no matter how much resistance the Ukrainians put up."                                                                                                                                                                                                                                                                                                                           , Roughly a quarter of Russia's amassed troops have yet to enter Ukraine, a senior defense official told reporters on Monday -- a potential "second wave," according to two sources familiar with the intelligence -- and defense officials say Putin could yet order a far less restrained bombing campaign, including airstrikes, long-range missiles and artillery.                                                                                                                                                                                        , "They have been slowed and they have been frustrated by their lack of progress on Kyiv, and one of the things that could result is a reevaluation of their tactics and the potential for them to be more aggressive and more overt in both the size and the scale of their targeting of Kyiv," a senior defense official told reporters on Monday.                                                                                                                                                                                                          , And at the end of the day, officials tracking the campaign say, the ugly truth remains that Ukraine is massively outgunned and outmanned -- even as Russia has made what military strategists say are a number of obvious blunders.                                                                                                                                                                                                                                                                                                                         , Already, Russia appears to be ramping up its campaign in the east and the south. In the northeastern city of Kharkiv, Russian forces have launched rocket attacks on at least one residential neighborhood that have killed civilians, according to Ukrainian officials and multiple social media videos geolocated by CNN. Meanwhile, in the small southern city of Mykolaiv, located on an inlet that would be a useful access point for Russians to bring in troops and supplies, the fighting has been among the most intense in Ukraine in recent days., Concerns about Putin's state of mind                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Perhaps most ominously, western officials are also warily watching Putin, under pressure from crushing economic penalties that have tanked the ruble and caused the Russian stock market to close. They fear those sanctions, combined with the lack of progress in Kyiv, may cause the unpredictable Russian leader to lash out even more.                                                                                                                                                                                                                 , Senior US lawmakers familiar with the intelligence, western officials and former senior US officials with deep experience in Russia have begun to openly raise questions about the Russian leader's mental stability.                                                                                                                                                                                                                                                                                                                                       , "Putin has been completely isolated, partly because of Covid," said the American source familiar with the intelligence. "He's now basically just by himself, completely cut off from most of his advisers, isolated geographically ... the only people talking to him are sycophants who are just feeding his resentment." The source added that the intelligence suggested Putin has not even been listening to his oligarchs -- traditionally the people who have had a key influence on his decision making.                                             , Sen. Marco Rubio of Florida, the top Republican on the Senate Intelligence Committee, tweeted Friday that "it's pretty obvious to many that something is off with #Putin," hinting that his assessment was based on intelligence briefings. "He has always been a killer, but his problem now is different &amp; significant. It would be a mistake to assume this Putin would react the same way he would have 5 years ago."                                                                                                                                   , On Sunday, Putin ordered Russia's nuclear forces into "special combat readiness," a heightened alert status that the Biden administration has characterized as part of a pattern of unprovoked escalation and "manufactured threats."                                                                                                                                                                                                                                                                                                                       , Holding back?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Five days into its multipronged assault on Ukraine, Russia has suffered repeated logistical failures that defense officials and independent military analysts say are largely of its own making. Russian mechanized forces that have been the tip of the spear have often outpaced their own sustainment units carrying fuel and other supplies, leaving the support units open to ambush and stranding forward-advancing forces without fuel in the tank.                                                                                                  , "Whether they outran [sustainment capabilities] or whether they just didn't plan properly for it, or whether they just simply didn't execute their plan for it, I don't know," said the senior defense official. But, "on day 4, they're running out of gas and they've having logistics problems. Our assessment was that they did not believe they would be having those kinds of problems that early on."                                                                                                                                                , Meanwhile, western officials have cheered on a better-than-anticipated showing by Ukrainian forces, in particular how effective they have been using western-provided Stinger shoulder-fired missiles and anti-aircraft artillery to take down an unknown number of Russian helicopters and fixed-wing aircraft.                                                                                                                                                                                                                                            , "The Russians don't have complete control of the airspace of the entire country," said the senior western intelligence official. "In the areas in which the Russian military operations are the most intense on the ground, those are the areas where the Russians have the most control over the airspace in terms of air to air."                                                                                                                                                                                                                         , But Western officials still aren't entirely sure why Russia has held back some forces outside of Ukraine's borders, or why Russia has not yet carried out the kind of electronic warfare against Ukraine the west had been anticipating -- like massive hacking campaigns and attacks on critical infrastructure.                                                                                                                                                                                                                                           , One official said the US believes Russia has been holding back on severing communications on the ground -- a tactic the west had expected early but has yet to happen -- because the Russian military forces need that infrastructure to communicate amongst themselves.                                                                                                                                                                                                                                                                                    , As for the troops left on the border, it's possible that Russia has planned the attack in waves in an effort to exhaust the Ukrainians with the first wave and then demolish them with a second wave of fresh troops, according to two sources familiar with the intelligence. It's also possible, according to one of those sources, that Russia has simply moved cautiously after facing a tougher fight than expected.                                                                                                                                   , At this point, officials said, it's impossible to put a timeline on how long Ukrainian forces will be able to hold the Russians at the gates of Kyiv.                                                                                                                                                                                                                                                                                                                                                                                                       , "I can't put a number [on how long Kyiv lasts]," the senior western intelligence official said. "I can't tell you it's going to be hours or days.                                                                                                                                                                                                                                                                                                                                                                                                           , "While the Ukrainians are putting on a stiff defense, and a much better one than I think the Russians anticipated, there will be a time where they will run out of ammunition. There will come a time where they run out of fuel and they can't move," this person said. "We are mindful of that and they are mindful of that."                                                                                                                                                                                                                             , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/sp-downgrades-several-russia-banks/story.aspx?guid={C7372D61-2746-4851-856E-2F2011C71A1D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 03:36:03 </td>
   <td style="text-align:left;"> S&amp;P downgrades several Russia banks, places the ratings of another 19 on CreditWatch negative - MarketWatch </td>
   <td style="text-align:left;"> S&amp;P Global Ratings on Monday downgraded several Russian banks and placed the ratings of another 19 on CreditWatch negative, to reflect the heightened geopolitical risks facing them after Russia's invasion of Ukraine led to a wave of international sanctions. The agency downgraded long and short-term ratings of Raiffeisenbank AO, UniCredit Bank AO, and Gazprombank JSC, as well as Alfa-Bank JSC and its holding company ABH Financial Ltd. "We also placed our ratings on Russian financial institutions, their debt issues, subsidiaries, and related entities on CreditWatch with negative implications, since we believe these entities face increased geopolitical and  economic risks." S&amp;P said in a statement. "The CreditWatch placement on our rating on subsidiaries reflects the likelihood that a potential decline in the parent companies' creditworthiness would have a negative knock-on effect on those entities." The move comes after S&amp;P downgraded Russia's sovereign rating on Friday to BB+/B from 'BBB-minus/A-3, placing it in high-yield, or "junk" status. "In our view, the escalation of Russia-Ukraine tensions, Russian  operations in 
Ukraine, and widening of sanctions against Russia could lead to conditions 
that eventually destabilize Russia's economy and financial system," S&amp;P said. 
                      , Shares of EPAM Systems Inc. undefined tumbled 9.8% to pace all S&amp;P 500 undefined components in premarket losses, after the provider of digital platform engineering services said it was withdrawing its financial guidance as a result of "military actions" in Ukraine. The company had said in its fourth-quarter earnings report out Feb. 17 that it expected first-quarter revenue of $1.17 billion to $1.18 billion and 2022 revenue of at least $5.15 billion, which compared with the FactSet consensus at the end of January for first-quarter revenue of $1.11 billion and 2022 revenue of $4.87 billion. EPAM said in its 10-K annual report filing late Friday that its largest delivery centers were located in Ukraine, Belarus and Russia. As of Dec. 31, it had 12,389 delivery professionals in Ukraine, 9,416 in Belarus and 8,933 in Russia. "EPAM's highest priority is the safety and security of its employees and their families in Ukraine. The company is proactively working to relocate its employees to lower risk locations in Ukraine and neighboring countries." The company stated on Monday. The stock, which tumbled 13.7% last week, is on track to open at the lowest price seen during regular-session hours since March 9, 2021. It has plunged 37.2% over the past three months through Friday, while the S&amp;P 500 slipped 4.6%., Ciara Linnane is MarketWatch's investing- and corporate-news editor. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gm-names-kyle-vogt-ceo/story.aspx?guid={E49828C8-1771-4864-8281-0A85FC8CD516}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 03:34:35 </td>
   <td style="text-align:left;"> GM names Kyle Vogt the CEO of AV unit Cruise - MarketWatch </td>
   <td style="text-align:left;"> General Motors Co. 
        GM,
        -1.50%
       said Monday that Kyle Vogt has formally accepted the role of chief executive of Cruise, GM's autonomous-driving unit. Vogt, who co-founded Cruise in 2013, has served as interim CEO since December. Vogt also will serve as chief technology officer and president of Cruise, which GM bought in 2016 for $1 billion., Emmy season is upon us and streaming services are launching their biggest shows, from 'Bridgerton' to 'Pachinko' to 'Halo.'                                                                                                                                                                                                                                                    , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/shell-is-pulling-out-of-russia-dumping-gazprom-deal </td>
   <td style="text-align:left;"> 2022-03-01 03:27:48 </td>
   <td style="text-align:left;"> Shell is pulling out of Russia, dumping Gazprom deal </td>
   <td style="text-align:left;"> Alaska Governor Mike Dunleavy argues the U.S. should be pushing for increased production of oil and natural gas as well as renewable energy for the sake of national security and the country's economy.                                                                                                                                                                                                                                                , Shell is calling it quits in Russia and has announced plans to exit its relationship with Gazprom and related entities.                                                                                                                                                                                                                                                                                                                                 , On Monday, in a statement, CEO Ben van Beurden detailed the emotional decision.                                                                                                                                                                                                                                                                                                                                                                         , "Our decision to exit is one we take with conviction," said van Beurden. "We cannot – and we will not – stand by. Our immediate focus is the safety of our people in Ukraine and supporting our people in Russia. In discussion with governments around the world, we will also work through the detailed business implications, including the importance of secure energy supplies to Europe and other markets, in compliance with relevant sanctions.", Workers prepare equipment on the drilling tower of an exploratory well at Gazprom's Sarikamysh gas field in Shakhrinav district, some 31 miles west of Dushanbe. (Reuters/Nozim Kalandarov)                                                                                                                                                                                                                                                             , The unwinding of the joint venture includes a "27.5% stake in the Sakhalin-II liquefied natural gas facility, its 50% stake in the Salym Petroleum Development and the Gydan energy venture."                                                                                                                                                                                                                                                           , Shell also intends to end its involvement in the Nord Stream 2 pipeline project, as detailed in the announcement.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60549927?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-01 03:26:48 </td>
   <td style="text-align:left;"> UK fast-tracks law to tackle Russian 'dirty money' </td>
   <td style="text-align:left;"> The UK is fast-tracking legislation to target money-laundering by foreign oligarchs.                                                                                                                                                                                         , The government's move follows Russia's decision to invade Ukraine.                                                                                                                                                                                                           , As part of the measures, foreign property owners will have to declare their identities rather than using companies as a façade.                                                                                                                                              , It follows the economic sanctions announced by Prime Minister Boris Johnson on Tuesday which targeted major Russian banks and leaders.                                                                                                                                       , The government said the legislation will support the National Crime Agency work in targeting corruption.                                                                                                                                                                     , The Economic Crime Bill will include a new register that will mean foreign owners of UK property must declare and verify their identities with Companies House.                                                                                                              , The aim is to stop overseas criminals and oligarchs from using agents to create companies or buy property for them in the UK.                                                                                                                                                , Entities that refuse to declare their owners will face restrictions in selling property and those who break the rule could be imprisoned for up to five years.                                                                                                               , The register also applies to property bought by overseas owners up to 20 years ago in England and Wales and from December 2014 for property in Scotland.                                                                                                                     , Companies House will also have more information on firms to increase corporate transparency, the government said.                                                                                                                                                            , On Monday the business secretary Kwasi Kwarteng said that agents from overseas would no longer be able to create UK companies on "behalf of criminals". The process to register a new company in the UK can cost as little as £12.                                           , Mr Kwarteng told Parliament that oligarchs and kleptocrats have benefited from the "veneer of legitimacy" provided by UK-registered companies and partnerships, while using high-end property to help "launder proceeds of corruption".                                      , Mr Kwarteng said the new register will "shine a light" on who owns what in the UK so the government could "flush out the oligarchs, criminals and kleptocrats who think they can use UK property to hide their illicitly obtained wealth".                                   , The National Crime Agency's 'Kleptocracy' cell, announced last week, will also begin to investigate sanctions evasion and be able to seize crypto-assets used for money-laundering.                                                                                          , The legislation also strengthens Unexplained Wealth Orders (UWOs) which were powers brought into force in January 2018 in the fight against suspected criminal money invested in property.                                                                                   , However, UWOs have been used just four times since 2018 and only one has resulted in property being surrendered so far.                                                                                                                                                      , UWOs will be reformed to give law enforcement agencies more time to review case material and to protect them from substantial legal costs if they pursue reasonable cases which are ultimately unsuccessful.                                                                 , British officials trying to freeze individual accounts held by Russian billionaires face difficulties in part due to the systems of trusts and shell companies that hold their fortunes.                                                                                     , Thomas Mayne, visiting fellow from thinktank Chatham House's Russia and Eurasia Programme, said while revealing ownership was a "step forward", enforcement needed to be effective.                                                                                          , "If there are no penalties for submitting false or misleading information (and, like with Companies House, funding of UK authorities to properly investigate), then the bill will be useless," Mr Mayne said.                                                                , Around 87,000 properties are owned by offshore companies in the UK which Mr Mayne said means the authorities have "no idea who owns them".                                                                                                                                   , "Actually getting the owners on record, checking the information and penalising those who submit false information will likely take years," Mr Mayne added.                                                                                                                  , Shadow chancellor Rachel Reeves said that Labour supports the legislation and will "scrutinise the strength of these measures, which the government must enact in their strongest form to tackle dirty money once and for all."                                              , "The long overdue Register of Overseas Entities, originally promised in 2016, must now be implemented at speed. Any transition period must be completed by the end of March and be accompanied by tough enforcement measures," she continued.                                , Shadow home secretary Yvette Cooper said the measures were "welcome" but "don't yet go far and fast enough".                                                                                                                                                                 , "Alongside strong sanctions we need an urgent crackdown on illicit finance, corruption and organised crime linked to Russia. For too long the City of London and the UK economy has been used as a laundromat by corrupt elites linked to organised crime," Ms Cooper added. , The anti-corruption organisation Transparency International has identified at least £1.5bn of UK property owned by Russians accused of financial crime or with links to the Kremlin.                                                                                         , As part of the latest round of sanctions, Mr Johnson said the government will also limit the amount of money Russian nationals will be able to deposit in their UK bank account.                                                                                             , Start watching series 6 of Peaky Blinders on BBC iPlayer                                                                                                                                                                                                                     , Watch this ultimate recap to make sure you didn't miss anything from Peaky Blinders                                                                                                                                                                                          , Cillian Murphy shared what the whole-decade experience on Peaky Blinders means to him                                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/alaska-ready-to-increase-oil-gas-production-if-biden-admin-allows-gov-dunleavy </td>
   <td style="text-align:left;"> 2022-03-01 03:17:14 </td>
   <td style="text-align:left;"> Alaska ready to increase oil, gas production if Biden admin allows: Gov. Dunleavy </td>
   <td style="text-align:left;"> Alaska Governor Mike Dunleavy argues the U.S. should be pushing for increased production of oil and natural gas as well as renewable energy for the sake of national security and the country's economy.                                                                                                                                                    , Alaska Governor Mike Dunleavy said on Monday that his state is ready to increase oil and gas production amid escalating tension overseas if the Biden administration allows.                                                                                                                                                                                , Dunleavy made the comment on "Cavuto: Coast to Coast" on Monday as oil prices surged, with U.S. benchmark crude around $96 per barrel in electronic trading on the New York Mercantile Exchange. Brent crude hovered at $98 per barrel as Russia, a major oil producer, continued to invade Ukraine.                                                        , Last week, oil prices hit an eight-year high, briefly topping $105 a barrel for the first time since 2014 – and Russia's full-blown attack on Ukraine, which started last Thursday, could push prices even higher.                                                                                                                                          , "We have billions of barrels of oil still in the ground. We’ve got about 126 trillion cubic feet of gas that we can deliver to our friends in Asia as well as the West Coast," Dunleavy told host Neil Cavuto. "So we’re prepared and ready to do our part if this administration allows us to."                                                            , Dunleavy provided the insight one day after White House press secretary Jen Psaki said the U.S. needs to decrease its reliance on foreign oil by switching over to renewable energy, not increasing domestic production.                                                                                                                                    , "We need to reduce our dependence on foreign oil, on oil in general, and we need to look at other ways of having energy in our country and others," Psaki said during an interview with ABC This Week Sunday. "We've seen over the last week or so... a number of European countries are recognizing they need to reduce their own reliance on Russian oil.", Psaki's comments come as fears grow that energy prices could continue to rise amid Russia's ongoing war in Ukraine, with many NATO countries such as Germany dependent on Russian oil to fuel their countries.                                                                                                                                              , RUSSIA-UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                , Port of Corpus Christi CEO Sean Strawbridge outlines the challenges, which include the regulatory environment that he and his customers, oil and gas companies, have experienced.                                                                                                                                                                           , That dependence has also limited the international response to Russia's invasion, with sanctions being specifically designed not to target Russian fuel exports amid fears such a move could send energy prices soaring in Europe.                                                                                                                          , The comments also come after the Biden administration last week began delaying decisions on new oil and gas leases after a federal judge blocked the administration from using higher climate change cost estimates when regulating polluting industries.                                                                                                   , The ruling stems from President Biden's decision on his first day in office to restore the climate cost estimate to $51 per ton of carbon dioxide emissions, up from the $7 it was slashed to during the Trump administration.                                                                                                                              , Biden has come under increasing pressure to walk back resistance to domestic oil production in the wake of Russia's invasion of Ukraine, with Rep. August Pfluger, R-Texas, arguing such a move would help the U.S. "regain our dominance on the world stage."                                                                                              , On Monday, Dunleavy argued that the U.S. should be pushing for increased production of oil and natural gas as well as renewable energy for the sake of national security and the country's economy.                                                                                                                                                         , Sen. Tommy Tuberville says 'they want to shut it all down' as the Biden admin halts new oil, gas drilling permits.                                                                                                                                                                                                                                          , Dunleavy noted that "$100 a barrel oil is great for Alaska’s coffers, but it’s bad for the people in the state and for America because of the prices at the pump."                                                                                                                                                                                          , On Monday, the national average for a gallon of gas was $3.60, which is 78 cents higher than the week before and 89 cents higher than the year before, according to AAA.                                                                                                                                                                                    , "I think we should push renewables and I think we should push oil and gas," Dunleavy told Cavuto. "I think they both present great opportunities for this country."                                                                                                                                                                                         , "I don’t understand why we aren’t doing that, especially given what is happening over in Russia," he continued.                                                                                                                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                 , "We had the same issue with Iran and others that are not necessarily friendly with the United States. I’m all for opportunities. I think we should push it. Alaska could do its part."                                                                                                                                                                      , According to the Energy Information Administration, Alaska's proved crude oil reserves of 2.4 billion barrels are the fourth largest of any state and Alaska ranks third in the country in natural gas gross withdrawals.                                                                                                                                   , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                     , FOX Business’ Michael Lee contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/unemployment-rate </td>
   <td style="text-align:left;"> 2022-03-01 02:53:00 </td>
   <td style="text-align:left;"> Colombia Jobless Rate Rises 14.6% in January </td>
   <td style="text-align:left;"> The unemployment rate in Colombia rose 14.6 percent in January of 2022, easing from 17.5 percent in the corresponding month of the previous year, as the number of unemployed fell by 0.51 million to 3.55 million, while employment went up by 1.58 million to 20.70 million. Meantime, the employment rate increased to 53.4 percent from 50.1 percent, while the activity rate rose to 62.6 percent from 60.7percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60559513?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-01 02:50:17 </td>
   <td style="text-align:left;"> UK citizens are advised not to travel to Russia </td>
   <td style="text-align:left;"> UK citizens have been advised against travelling to Russia due to a lack of flights available and economic problems in the country.                                                                                                                                                                                                                                                                                                             , The Foreign Office warned Britons in Russia might not be able to fly directly to the UK or via EU countries.                                                                                                                                                                                                                                                                                                                                    , It said the value of the rouble had fallen and there were reports of lots of people "attempting to withdraw their savings from Russian banks".                                                                                                                                                                                                                                                                                                  , The advice comes after Russia banned airlines from 36 countries.                                                                                                                                                                                                                                                                                                                                                                                , In a tit-for-tat retaliation to sanctions, the country said it would stop flights from nations including Germany, Spain, Italy and Canada from using its airspace.                                                                                                                                                                                                                                                                              , On its website, the Foreign Office urged people in Russia to "amend any travel plans accordingly".                                                                                                                                                                                                                                                                                                                                              , It means UK or EU citizens wanting to leave Russia by air would have to travel to a country which has not issued any flight or travel sanctions to Russia to then get a flight directly home.                                                                                                                                                                                                                                                   , Russia had already barred UK airlines from flying to and across the region after Britain banned Russian airlines, including national airline Aeroflot and private jets, from landing in the UK.                                                                                                                                                                                                                                                 , The Foreign Office also warned the sharp fall in the Rouble's value meant any Russian currency people held "may reduce in value over the coming days" and that foreign nationals in Russia were reported to be having difficulty using ATM and banking services.                                                                                                                                                                                , It also said since Putin's invasion there had been several reports of anti-war protests with a "heavy police presence".                                                                                                                                                                                                                                                                                                                         , "There are reports of increased police presence and ID checks. You should keep your passport with you at all times," the Foreign Office said.                                                                                                                                                                                                                                                                                                   , On Sunday, Europe shut its skies to Russian owned or controlled planes in one of a number of sanctions imposed by Western nations on Russia following its invasion of Ukraine.                                                                                                                                                                                                                                                                  , The announcement means all planes, including the private jets of oligarchs, will now be unable to land in, take off from or fly over any EU nation.                                                                                                                                                                                                                                                                                             , Transport Secretary Grant Shapps also announced he had told all UK ports to not let any Russian "flagged, registered, owned, controlled, chartered or operated vessels" to have access.                                                                                                                                                                                                                                                         , "I've made clear these vessels are not welcome here," he said.                                                                                                                                                                                                                                                                                                                                                                                  , The UK Chamber of Shipping said the banning of ships with Russian interests from UK ports would "put further pressure on the Russian President's military objectives", but added it would be "complex" and would "require new legislation".                                                                                                                                                                                                     , On Monday, the Russian aviation regulator, Rosaviatsia, said: "A restriction has been imposed on flights for airlines of 36 countries in accordance with international law as a retaliatory measure for the ban imposed by the European states on the flights of commercial airliners operated by Russian airlines and/or registered in Russia."                                                                                                , The measures mean airlines will have to make long detours on some routes, potentially raising the cost of fuel and tickets.                                                                                                                                                                                                                                                                                                                     , The countries banned from Russia's airspace are: Albania, Anguilla, Austria, Belgium, British Virgin Islands, Bulgaria, Canada, Croatia, Cyprus, Czech Republic, Denmark (including Greenland, the Faroe Islands), Estonia, Finland, France, Germany, Gibraltar, Greece, Hungary, Iceland, Ireland, Italy, Jersey, Latvia, Lithuania, Luxembourg, Malta, Netherlands, Norway, Poland, Portugal, Romania, Slovakia, Slovenia, Spain, Sweden, UK. , Swiss International Airlines, which is owned by Germany's Lufthansa, said that it had cancelled flights from Zurich to Moscow despite Switzerland not appearing on Russia's list of banned countries.                                                                                                                                                                                                                                           , A spokesperson for the Swiss airline also said it was not flying through Russian airspace.                                                                                                                                                                                                                                                                                                                                                      , It said: "We continue to closely monitor the development of the situation and are in close exchange with the Swiss and international authorities as well as with the Lufthansa Group for our operational decisions."                                                                                                                                                                                                                            , Meanwhile, cruise firm Carnival, which owns P&amp;O Cruises as well as Cunard, said it was changing journeys on Baltic cruises.                                                                                                                                                                                                                                                                                                                     , The company said it would advise guests of the changes "as soon as possible".                                                                                                                                                                                                                                                                                                                                                                   , On Monday, Switzerland - traditionally a neutral country and whose banks are believed to hold billions of dollars in Russian funds- said that it would adopt EU financial sanctions against Moscow.                                                                                                                                                                                                                                             , The Swiss justice minister, Karin Keller-Sutter, also said it had banned five oligarchs with links to Russia's president Vladimir Putin from entering the country, though declined to name them.                                                                                                                                                                                                                                                , The BBC's correspondent in Geneva, Imogen Foulkes, said: "Make no mistake, this is a huge step for Switzerland, which has often agonised over what being neutral actually means.                                                                                                                                                                                                                                                                , "Today, Swiss president Ignazio Cassis made it clear: the attack on Ukraine was an unacceptable attack on freedom and democracy," she said.                                                                                                                                                                                                                                                                                                     , Rob Morris, head of consultancy at aviation data and analytics company Ascend by Cirium, said the restrictions would hinder the aviation industry's emerging recovery ahead of the critical summer booking period.                                                                                                                                                                                                                              , Mr Morris said the restrictions will hit long haul routes from Europe to Asia the most and cargo was likely to be affected more than passenger routes.                                                                                                                                                                                                                                                                                          , Are you a UK citizen trying to fly to the UK from Russia? You can get in touch by emailing haveyoursay@bbc.co.uk.                                                                                                                                                                                                                                                                                                                               , Please include a contact number if you are willing to speak to a BBC journalist. You can also get in touch in the following ways:                                                                                                                                                                                                                                                                                                               , If you are reading this page and can't see the form you will need to visit the mobile version of the BBC website to submit your question or comment or you can email us at HaveYourSay@bbc.co.uk. Please include your name, age and location with any submission.                                                                                                                                                                               , Start watching series 6 of Peaky Blinders on BBC iPlayer                                                                                                                                                                                                                                                                                                                                                                                        , Watch this ultimate recap to make sure you didn't miss anything from Peaky Blinders                                                                                                                                                                                                                                                                                                                                                             , Cillian Murphy shared what the whole-decade experience on Peaky Blinders means to him                                                                                                                                                                                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palladium </td>
   <td style="text-align:left;"> 2022-03-01 02:43:00 </td>
   <td style="text-align:left;"> Palladium Surges on Russia Air Travel Bans </td>
   <td style="text-align:left;"> Palladium futures rose toward $2,500 an ounce, remaining close to levels not seen since August, as the ongoing conflict in Ukraine is set to disrupt exports of the precious metal. Palladium is usually transported by passenger planes and Russia accounts for 40% of all mined production. Demand for the metal, used in pollution-controlled devices, has been outpacing supply for years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/28/retired-us-army-maj-gen-james-marks-first-five-days-of-invasion-sot-ip-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-01 02:42:43 </td>
   <td style="text-align:left;"> The first five days of Russia's Ukraine invasion have not gone well. Here's why - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/chile/industrial-production </td>
   <td style="text-align:left;"> 2022-03-01 02:40:30 </td>
   <td style="text-align:left;"> Chile Industrial Output Contracts in January </td>
   <td style="text-align:left;"> Industrial production in Chile fell 1.1 percent year-on-year in January of 2022, contracting from a 1.7 percent increase in the previous month. It was the first decrease since September 2021 and the steepest since February of the same year, underpinned by a significant shrinkage in mining and quarrying (-6.3 percent vs 0.6 percent in December 2021), largely due to lower copper production (-7.5 percent vs -0.6 percent). On the other hand, output advanced for manufacturing (2.6 percent vs 2.3 percent) and electricity, gas, and water (3.1 percent vs 3.7 percent). On a monthly basis, industrial production fell by 1.1 percent, shrinking from the 0.3 percent decline in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-settle-higher-up/story.aspx?guid={CA5EE404-2749-468E-8C48-EBEB383470B9}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 02:39:52 </td>
   <td style="text-align:left;"> Gold futures settle higher, up nearly 6% for the month - MarketWatch </td>
   <td style="text-align:left;"> Gold futures climbed on Monday, buoyed by Russia's ongoing invasion of Ukraine, with prices for the metal ending higher for the month. "If there is no de-escalation between the West and Russia, there will be a surge of physical investment demand into precious metals as a rush into precious safe havens explodes," said Peter Spina, president and chief executive officer at GoldSeek.com, noting that Russia is also among the world's biggest gold producers. Still, gold prices may see "some selling pressures from some liquidity needs, so you will see some volatility," said Spina. April gold 
        GCJ22,
        +0.41%
       rose $13.10, or 0.7%, to settle at $1,900.70 an ounce. Prices based on the most-active contract rose 5.8% for the month, according to FactSet data., The U.S. tally of daily cases of COVID-19 has returned to levels seen before the highly infectious omicron strain was discovered in November, helping to lower hospitalizations, the number of patients in intensive-care units and the daily death toll.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/28/energy-giant-shell-to-end-partnership-with-russias-gazprom-as-ukraine-conflict-intensifies.html </td>
   <td style="text-align:left;"> 2022-03-01 02:15:13 </td>
   <td style="text-align:left;"> Energy giant Shell to end partnership with Russia's Gazprom as Ukraine conflict intensifies </td>
   <td style="text-align:left;"> , Shell said Monday it is ending an "equity partnership" with Gazprom, a Russian state-owned energy company, as the Russia-Ukraine conflict continues.                                                                                                                                                                                                                                                                            , Shell said it's selling a 27.5% stake in Sakhalin-II, an integrated oil and gas project located on the Sakhalin island in Russia, as well as a 50% interest in Salym Petroleum Development N.V., "a joint venture with Gazprom Neft that is developing the Salym fields in the Khanty-Mansiysk Autonomous District of western Siberia." The company also said it's ending its involvement in the Nord Stream 2 pipeline project., "We are shocked by the loss of life in Ukraine, which we deplore, resulting from a senseless act of military aggression which threatens European security," Shell CEO Ben van Beurden said in a statement.                                                                                                                                                                                                                      , "Our immediate focus is the safety of our people in Ukraine and supporting our people in Russia," van Beurden added. "In discussion with governments around the world, we will also work through the detailed business implications, including the importance of secure energy supplies to Europe and other markets, in compliance with relevant sanctions."                                                                    , Shell's announcement comes a day after rival BP said it was offloading its 19.75% stake in Rosneft, another Russian-controlled oil company. Meanwhile, the U.S. — along with other countries — has ramped up sanctions against Russia following its invasion of Ukraine.                                                                                                                                                        , The company said that it had about $3 billion in "noncurrent assets" through its Gazprom ventures at the end of 2021, noting that exiting these investments will "impact the book value of Shell's Russia assets and lead to impairments."                                                                                                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                          , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                          , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                              , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/nyse-nasdaq-halt-trading-of-russia-based-companies </td>
   <td style="text-align:left;"> 2022-03-01 02:13:50 </td>
   <td style="text-align:left;"> NYSE, Nasdaq halt trading of Russia-based companies </td>
   <td style="text-align:left;"> UBS Managing Director and senior portfolio manager Jason Katz argues the situation overseas and the economic repercussions 'exacerbates what is already a very challenging position for the Fed.'                                                                      , The New York Stock Exchange and the Nasdaq MarketSite have temporarily halted trading in select Russian companies listed on their respective exchanges.                                                                                                                , Per a notice with the NYSE, the listed companies are Mechel PAO, American Depositary Shares – each representing two ordinary shares – and Mobile TeleSystems Public Joint Stock Company and Cian PLC American Depositary Shares, each representing one ordinary share. , RUSSIA-UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                           , Sources familiar with exchanges tell FOX Business the halts, which can be used for unusual trading in any security, will allow time for officials to review the fast-moving developments impacting the shares.                                                         , US EFFECTIVELY FREEZES RUSSIAN CENTRAL BANK ASSETS HELD BY                                                                                                                                                                                                             , At the Nasdaq, stocks included are Yandex, known as Russia's Google, and online retailer Ozon, as well as Nexters and QIWI and Head Hunter Group.                                                                                                                      ,  MOSCOW SUSPENDS STOCK TRADING FOR DAYS                                                                                                                                                                                                                                , A Nasdaq spokesperson tells FOX Business the companies have been contacted and asked for information material to the ongoing situation between Russia and Ukraine and how it may impact business.                                                                      , Officials at the NYSE, which is owned by Intercontinental Exchange, declined to comment.                                                                                                                                                                               , Russia's invasion of Ukraine has created extreme volatility across equities and other asset classes including oil and gold.                                                                                                                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/silver </td>
   <td style="text-align:left;"> 2022-03-01 02:12:48 </td>
   <td style="text-align:left;"> Silver Climbs Above $24 </td>
   <td style="text-align:left;"> Silver futures have been trading above $24 per troy ounce, and touched a near 7-month high at above $25.5/oz on February 24th, as demand for precious metals has been supported by fears of prolonged fighting in Ukraine and investors scale back aggressive rate hike bets across major developed economies. Russian and Ukrainian officials met on the Belarusian border on Monday but hopes of a breakthrough remain slim considering Russia’s state war aims. Putin has demanded the surrender of Ukraine’s army and the removal of the country’s government. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/shell-offload-stakes-russias-gazprom/story.aspx?guid={2A7C0CF0-0CEA-4498-A700-CDC41717FA2A}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-01 02:05:25 </td>
   <td style="text-align:left;"> Shell to offload stakes in Russia's Gazprom projects  - MarketWatch </td>
   <td style="text-align:left;"> Shell PLC 
        SHEL,
        +3.59%
       said Monday it would exit its joint ventures with Russia's state-owned natural-gas giant Gazprom and related entities, including stakes in a liquified natural gas facility and other oil and gas projects worth about $3 billion. "We are shocked by the loss of life in Ukraine, which we deplore, resulting from a senseless act of military aggression which threatens European security," Shell Chief Executive Officer Ben van Beurden said in a statement. "In discussion with governments around the world, we will also work through the detailed business implications, including the importance of secure energy supplies to Europe and other markets, in compliance with relevant sanctions." Shell valued its assets in the ventures with Gazprom at around $3 billion at the end of 2021. Exiting the joint ventures will lead to impairments, Shell said, without details. Shell reaffirmed its dividend and share buyback programs and said it expects to increase its dividend by 4% for the first quarter. Shell's decision follows BP PLC's 
        BP,
        -4.95%
       move to offload its nearly 20% stake in Russian government-controlled oil giant Rosneft as the world reacts the Russian invasion of Ukraine. , The U.S. tally of daily cases of COVID-19 has returned to levels seen before the highly infectious omicron strain was discovered in November, helping to lower hospitalizations, the number of patients in intensive-care units and the daily death toll.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/28/stocks-making-the-biggest-moves-midday-raytheon-block-tesla-foot-locker-and-more.html </td>
   <td style="text-align:left;"> 2022-03-01 01:51:01 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Raytheon, Block, Tesla, Foot Locker and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                    , Defense stocks — Defense stocks rose as the conflict between Russia and Ukraine continued on Monday and European countries pledged to spend more on defense. Northrop Grumman climbed 7.9%, while Raytheon Technologies gained 4.6%, and General Dynamics added 2.8%. Lockheed Martin, which was also upgraded to to outperform from peer perform by Wolfe Research, rose 6.6%., BP — Shares of the oil and gas giant fell 3.9% after the company said it would offload its nearly 20% stake in Russia's state-controlled oil producer Rosneft. BP CEO Bernard Looney and former exec Bob Dudley are also resigning from Rosneft's board, effective immediately.                                                                                                , Block — Shares of fintech company Block rose 6.4% after an upgrade to outperform from BMO Capital Markets. The company said investors have an opportunity to pick up shares of Block at a growth-at-a-reasonable-price level after the stock's pullback.                                                                                                                       , Tesla — Shares of Tesla rallied 7.4% after Bernstein hiked its price target on the EV stock. "One obvious justification for TSLA's valuation is its unique growth profile, which stands out, even among tech companies," analyst Toni Sacconaghi said. However, Sacconaghi kept an underperform rating on the stock and still forecasts significant downside from here.        , Renewable Energy Group — Shares of Renewable Energy Group surged 40.3% after Chevron said it would buy the biodiesel maker in an all-cash deal valued at $3.15 billion. Chevron gained 2.5%.                                                                                                                                                                                   , First Horizon — Shares of the Memphis-based bank surged 28.6% following news that the company will be acquired by TD in an all-cash deal worth $13.4 billion, or $25 per share, a move that will allow the Canadian banking giant to expand its footprint in the southeastern part of the U.S.                                                                                 , Healthcare Trust of America — Shares of the health-care-centered real estate investment trust fell 5.3% following news that it will merge with rival Healthcare Realty in a deal with an implied value of $35.08 per share. Healthcare Realty shares dropped 11.1%.                                                                                                            , Foot Locker — Shares of the shoe retailer rose 8.7% despite being downgraded to underweight from equal weight at Morgan Stanley. The Wall Street firm said it's concerned about revenue potential after the company said it would sell fewer Nike products.                                                                                                                    , Gilead Sciences — Shares of Gilead Sciences dipped 1.1% after BMO downgraded the stock to market perform from outperform. "We are not negative on the name, but view Gilead as a 'show me' story and look to management for further de-risking of assets before we are more constructive," the firm said.                                                                      , Lear Corp — The automotive-seating company saw its shares fall 5.7% following a downgrade by Morgan Stanley from overweight to equal eight. The firm said its concerned about Lear's decelerating growth.                                                                                                                                                                      ,  — CNBC's Hannah Miao and Maggie Fitzgerald contributed reporting.                                                                                                                                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/soybeans </td>
   <td style="text-align:left;"> 2022-03-01 01:46:20 </td>
   <td style="text-align:left;"> Soybean Futures Bounce Back to $16.5/BU </td>
   <td style="text-align:left;"> Chicago soybean futures rose again to $16.5 a bushel, remaining close to levels not seen since September 2012 amid ongoing supply disruptions as heavy fighting continues in Ukraine, threatening exports from the Black Sea region. Ukraine is a major global supplier of corn and sunflower oil and any disruption to the production is set to put additional pressure on other grains and vegetable oils. Adding to the bullish tone, Argentina and Brazil have been facing abnormally dry conditions linked to the La Niña pattern, hitting the quality and quantity of crops. Elsewhere, the USDA said exporters reported the sale of 136,000 tonnes of US soybeans to China for delivery in the 2022/23 marketing year and 120,000 tonnes for delivery to unknown destinations during 2021/22. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-60521983?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-01 01:41:06 </td>
   <td style="text-align:left;"> Toyota to close Japanese factories after suspected cyber-attack </td>
   <td style="text-align:left;"> Toyota will shut down all 14 of its factories in Japan on Tuesday after a possible cyber-attack.                                                                           , News site Nikkei, which first reported the shutdown, said supplier Kojima Industries Corporation suspected it had been hit by a cyber-attack, causing a halt in production., Japanese factories account for about a third of Toyota's production.                                                                                                       , It told the Wall Street Journal it did not know whether the factories would remain closed beyond Tuesday.                                                                  , Toyota is the world's best selling carmaker.                                                                                                                               , Its production target for this year is 8.5 million vehicles.                                                                                                               , And the closure will reportedly set this back by about 13,000 cars.                                                                                                        , "Due to a system failure at a supplier in Japan, we have decided to suspend the operation of 28 lines at all 14 domestic plants", Toyota told news agency AFP.             , Like other manufacturers, Toyota's production has been hit by the global semi-conductor shortage.                                                                          , The shutdown included some plants operated by Toyota-affiliated Hino Motors and Daihatsu Motor, Reuters reported.                                                          , Start watching series 6 of Peaky Blinders on BBC iPlayer                                                                                                                   , Watch this ultimate recap to make sure you didn't miss anything from Peaky Blinders                                                                                        , Cillian Murphy shared what the whole-decade experience on Peaky Blinders means to him                                                                                      , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/ukraine-invasion-not-as-big-a-problem-for-markets-as-inflation-billionaire-investor-carl-icahn </td>
   <td style="text-align:left;"> 2022-03-01 01:39:32 </td>
   <td style="text-align:left;"> Ukraine invasion not as big for markets as inflation: Billionaire investor Carl Icahn </td>
   <td style="text-align:left;"> Icahn Enterprises founder Carl Icahn warns markets are at a 'precipice' and argues 'nobody is sure when this is going to happen, but your building toward it.'                                                                                                                                                                                                          , Billionaire investor and Icahn Enterprises founder Carl Icahn argued on Monday that inflation is the biggest economic problem amid the geopolitical unrest.                                                                                                                                                                                                             , Icahn, who has decades of experience in the investment business, noted on "Varney &amp; Co." on Monday that he has lived through the late 1970s when the U.S. experienced double-digit inflation, which prompted drastic action from the Federal Reserve.                                                                                                                   , "I think inflation is a major problem for us and I think that is what we have to deal with," Icahn told host Stuart Varney.                                                                                                                                                                                                                                             , "I lived through it in the 70s, and it’s not easy to put that genie back in the bottle."                                                                                                                                                                                                                                                                                , Icahn made the comments as U.S. stocks curbed some of the losses midday as investors weigh the latest on Russia's invasion of Ukraine against the U.S. expanding sanctions against Russia's central bank by freezing all assets held by Americans.                                                                                                                      , The S&amp;P 500 fell 0.3% on Monday and the Dow Jones Industrial Average dropped by nearly 200 points, erasing a 400+ point drop from earlier.                                                                                                                                                                                                                              , Oil prices surged Monday, with U.S. benchmark crude nearing $96 per barrel in electronic trading on the New York Mercantile Exchange. Brent crude hovered at $98 per barrel.                                                                                                                                                                                            , Inflation surged more than expected in January, notching another four-decade high.                                                                                                                                                                                                                                                                                      , The consumer price index rose 7.5% in January from a year ago, according to a Labor Department report released earlier this month, marking the fastest increase since February 1982, when inflation hit 7.6%. The CPI – which measures a bevy of goods ranging from gasoline and health care to groceries and rents – jumped 0.6% in the one-month period from December., Price increases were widespread: Although energy prices rose just 0.9% in January from the previous month, they're still up 27% from last year. Gasoline, on average, costs 40% than it did last year. Food prices have also climbed 7% higher over the year.                                                                                                           , YELLEN: FEDERAL RESERVE WON'T ALLOW INFLATION TO REACH 1970S LEVELS                                                                                                                                                                                                                                                                                                     , Chief global strategist and managing director of B. Riley Securities Mark Grant argues the U.S. is 'helping to finance Russia's invasion of the Ukraine' through purchases of Russian oil and petrochemicals.                                                                                                                                                           , Icahn pointed to higher oil prices on Monday when discussing inflation.                                                                                                                                                                                                                                                                                                 , Last week, oil prices hit an eight-year high, briefly topping $105 a barrel for the first time since 2014 – and Russia's full-blown attack on Ukraine on Thursday could push prices even higher.                                                                                                                                                                        , "I think that this market possibly is overreacted to what’s going on in the Ukraine, but I don’t think that’s the problem we have. I think the problem we really have is there’s a much deeper one, which is inflation," Icahn stressed on Monday.                                                                                                                      , Icahn Enterprises founder Carl Icahn argues inflation is the biggest economic problem amid the geopolitical unrest.                                                                                                                                                                                                                                                     , The Federal Reserve late last month signaled it could "soon" raise interest rates for the first time in three years, paving the way for a March liftoff as policymakers seek to keep prices under control and combat the hottest inflation in nearly four decades.                                                                                                      , "I don’t think anybody can predict the exact timing of the market, and anybody trying to do it is just, I think, wasting time," Icahn told Varney.                                                                                                                                                                                                                      , "But I think, look at a macro picture and if you lived this before, you have to realize that at this point, we’re sort of in a precipice."                                                                                                                                                                                                                              , He then noted that in terms of timing, it is hard to tell.                                                                                                                                                                                                                                                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                             , "When it’s going to happen though, could be three years, five years, you don’t know, or three days," Icahn said. "I think that a catalyst was this Russian Ukrainian thing, but I think we should be able to get through that."                                                                                                                                         , He stressed that he doesn’t want to be an "alarmist because nobody is sure when this is going to happen," but stressed that markets are "building toward it."                                                                                                                                                                                                           , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                 , FOX Business’ Megan Henney contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 01:35:26 </td>
   <td style="text-align:left;"> Madrid Stocks Pare Losses on Monday </td>
   <td style="text-align:left;"> The Ibex 35 Index pared earlier losses to close just below the flatline at 8,479 on Monday, over performing its European counterparts as investors monitored talks in between the Russian and Ukrainian delegations in Belarus, while weighing on sanctions by the EU and US. Western allies agreed over the weekend to remove key Russian banks from the SWIFT interbank messaging system and freeze the assets of Russia’s central bank. Banks closed in the red in Madrid, led by Banco Sabadell (-5%) and Banco Santander (-4.3%). On the other hand, companies in the renewable energy sector booked significant gains, led by Siemens Gamesa (14.4%), Solaria (10.8%) and Iberdrola (2.6%) as investors bet that demand for newer forms of energy in Europe will grow as oil prices rise and states start to reduce their dependence on Russian gas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/td-bank-biggest-acquisition </td>
   <td style="text-align:left;"> 2022-03-01 01:34:24 </td>
   <td style="text-align:left;"> TD Bank just made its biggest acquisition ever </td>
   <td style="text-align:left;"> Bill Baruch, president of Blue Line Capital, discusses his outlook for inflation and the markets.                                                                                                                                                                                                                                                                                                                                                                                                                  , TD Bank just made its biggest acquisition ever, despite the volatility rocking U.S. markets.                                                                                                                                                                                                                                                                                                                                                                                                                       , The bank is paying $13.4 billion for Memphis-based First Horizon, in an all-cash deal valuing the shares at $25.00, to establish a presence in the Southeast.                                                                                                                                                                                                                                                                                                                                                      , First Horizon has leadership positions in Tennessee, Louisiana, Florida, the Carolinas and Virginia, and footholds in the attractive Atlanta, Georgia, and Dallas and Houston, Texas markets.                                                                                                                                                                                                                                                                                                                      , First Horizon shares soared on the deal.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , RUSSIA-UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , "The Southeastern U.S. represents a tremendous opportunity for TD and the addition of First Horizon's commercial and specialty banking capabilities will position us as a leading national player in commercial banking. We will combine our resources and capabilities and continue to invest in the region as we focus on delivering the most differentiated banking experience in our markets" said Leo Salom, Group Head, U.S. Retail, TD Bank Group, and President and CEO, TD Bank in the deal announcement. , Salom will lead the combined businesses.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The deal will make TD's U.S. arm the sixth-largest U.S. bank with $614 billion in assets and 1,550 branches across 22 states.                                                                                                                                                                                                                                                                                                                                                                                      , TD's U.S. franchise1 will be a top 6 U.S. bank                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Pending regulatory and shareholder approvals, the deal is expected to close in the first quarter of TD's 2023 fiscal year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/maersk-shipping-russia </td>
   <td style="text-align:left;"> 2022-03-01 01:34:10 </td>
   <td style="text-align:left;"> Maersk considers suspending shipping container deliveries to, from Russia </td>
   <td style="text-align:left;"> Icahn Enterprises founder Carl Icahn argues inflation is the biggest economic problem amid the geopolitical unrest.                                                                                                                                                                                                                                                                                                                                                                                                       , Danish shipping company Maersk announced Monday that it is considering suspending container deliveries to and from Russia in an effort to comply with widespread sanctions against the country for its invasion of Ukraine.                                                                                                                                                                                                                                                                                               , "In light of the current conflict between Russia and Ukraine, we at A.P. Moller - Maersk are closely monitoring and preparing to comply with the ever-evolving sanctions and restrictions imposed against Russia while we safeguard our operations and our people in consideration of the constant developing situation," the company said in a statement. "Our preparations include a possible suspension of Maersk bookings to and from Russia on ocean and inland."                                                    , MOSCOW SUSPENDS STOCK TRADING UNTIL MARCH 5                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The company said it would do its "utmost" to deliver cargo already on the water to its intended destination.                                                                                                                                                                                                                                                                                                                                                                                                              , "We have a sharp focus on safeguarding reefer containers and keeping cold chain operations as stable as possible, as the commodities include important goods such as groceries and pharmaceuticals," the statement continued. "We are doing everything possible to prevent risk to the above cargo and in turn risk to the end-users in need of these commodities."                                                                                                                                                       , In addition, the company noted that its air services would be affected due to growing airspace restrictions against Russia.                                                                                                                                                                                                                                                                                                                                                                                               , The move comes after Maersk announced on Friday that it would stop accepting shipping container bookings to and from Ukraine until further notice.                                                                                                                                                                                                                                                                                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Maersk emphasized that the security and well-being of its employees is a top priority and that it has put plans in place to ensure its impacted workers and their families get the support they need. As of Feb. 24, all Maersk employees have been instructed to work from home, away from any conflict areas.                                                                                                                                                                                                           , "We have global coverage for any customer requests coming to the Ukraine Customer Experience teams. Normal requests will be handled as usual, but we ask for patience as global teams handle country-specific requests," the statement concluded. "Giving you the best ability to manage your supply chain is of the utmost importance to us and we are working to give you everything you need to run your global logistics in these circumstances. We expect to be able to share more information with you later today.", --FILE--A truck transports a container of Maersk unloaded from a container ship on a quay at the Port of Qingdao in Qingdao city, east China's Shandong province, 12 April 2016. (Oriental Image via Reuters Connect / Reuters Photos)                                                                                                                                                                                                                                                                                    , Maersk has been active in Russia since 1992, connecting the country's ports of St. Petersburg, Novorossiysk, Vladivostok, Vostochny and Kaliningrad to key global markets.                                                                                                                                                                                                                                                                                                                                                , Maersk shares slipped over 3% on Monday following the latest announcement.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 01:17:00 </td>
   <td style="text-align:left;"> South African Stocks End Higher, Post Monthly Gain </td>
   <td style="text-align:left;"> The JSE FTSE All Share index advanced about 2.5% to close at 76,091 on Monday, its biggest daily rise since January 12th, supported by commodity-linked sectors amid supply concerns over the impact of a possible prolonged Russia-Ukraine conflict. Investors continued to assess the latest round of western sanctions aimed to further isolate Russia’s economy and financial system, hitting the central bank and excluding some Russian banks from the global payments system SWIFT. Locally, South Africa is attempting to patch up relations with Russia after International Relations and Cooperation Minister Naledi Pandor issued an unusually strong statement calling on Russia to withdraw from Ukraine, contradicting South Africa’s official stance, which is to remain neutral and call for mediation. On the data front, South Africa posted the smallest trade surplus in nearly two years. For the month, the JSE gained 2.4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 00:51:00 </td>
   <td style="text-align:left;"> FTSE 100 Ends Lower, Records Monthly Decline </td>
   <td style="text-align:left;"> The FTSE 100 ended lower on Monday, in line with its European peers, as investors digested the latest sanctions against Russia amid the Ukraine invasion. The UK, US, the EU, Canada and Japan agreed to ban Russian financial institutions from the global payments system SWIFT, while the EU and the UK banned Russian aeroplanes from entering their airspace. Additionally, the UK said it would also ban Russian firms from money markets and transferable securities and prohibited British entities from undertaking transactions with major Russian financial institutions. Polymetal International PLC fell almost 60%, the most on the FTSE 100, as annual losses shrank significantly to £1.9 million last year, compared with a £6.2 million loss in 2020. BP shares slumped 4% after the oil giant said it would exit its stake in Rosneft, a state-controlled Russian oil-and-gas company. The FTSE 100 snapped two consecutive months of gains to finish February slightly down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Drop 1.4% on Monday </td>
   <td style="text-align:left;"> The FTSE MIB closed 1.4% down at 25,416, tracking its European counterparts and pressured by the Russian invasion in Ukraine as investors assessed the economic effects that harsher sanctions from the West can bring to the global economy. Measures included excluding key Russian banks from the Swift interbank system and freezing CBR assets, while the US banned national individuals and firms from transacting with the Central Bank of Russia, Russian National Wealth Fund, and the Ministry of Finance. On the corporate front, UniCredit (-9.5%) led the losses, pressured by its exposure to the Russian market despite the lender saying its Russian subsidiary was “very liquid and self-funded”. War in Ukraine and harsher sanctions from the West led UniCredit shares to plunge 22% on the week. On the other hand, Leonardo shares jumped over 15% after Germany announced it will commit an extra EUR 100 billion in defence spending. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-01 00:47:00 </td>
   <td style="text-align:left;"> UK 10-Year Gilt Drops to 1-Week Low </td>
   <td style="text-align:left;"> The yield on Britain's 10-year gilt fell to 1.43%, the lowest in near a week as concerns over the economic impact of Russia’s invasion of Ukraine and Western sanctions more than offset prospects of interest rate hikes. Before the war in Ukraine, the BoE had forecast inflation will peak at a 30-year high of 7.25% in April, well above the 2% target, when energy bills and taxes are due to go up. Money markets still see five rate hikes by the Bank of England this year and are currently pricing in a 25 basis point rate increase in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 00:47:00 </td>
   <td style="text-align:left;"> European Shares Tumble </td>
   <td style="text-align:left;"> European stocks ended a roller-coaster February lower. The benchmark DAX 30 fell to around 14,420 to record a second straight monthly decline as investors digested the latest sanctions against Russia and its implications for European companies and banks. Western nations and Japan agreed to ban Russian financial institutions from the global payments system SWIFT closing Russia's capital account. Shares of European banks suffered the sharpest declines on the region's exchanges Monday, with Deutsche Bank falling 8%, the most on the DAX 30. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 00:46:00 </td>
   <td style="text-align:left;"> French Shares Closes Lower </td>
   <td style="text-align:left;"> The CAC 40 Index closed 1.4% lower at 6,659 on Monday, partially recovering from having been down 3.3% in the session as investors continued to monitor the Russian invasion of Ukraine and the harsher retaliatory sanctions from western states. Western allies announced that key Russian banks are to be excluded from the Swift interbank system while freezing the assets of the Central Bank of Russia, while Washington banned US individuals and firms from transacting with the Central Bank of Russia, Russian National Wealth Fund, and the Ministry of Finance. In Paris, financial shares (-4%) led the losses, driven by Societe Generale (-10.3%) due to the lender’s exposure to the Russian market through its subsidiary Rosbank. Russian exposure also pressured Renault (-6.3%) through its auto parts manufacturer subsidiary Avtovaz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cocoa </td>
   <td style="text-align:left;"> 2022-03-01 00:40:29 </td>
   <td style="text-align:left;"> Cocoa Hits 4-week Low </td>
   <td style="text-align:left;"> Cocoa decreased to a 4-week low of 2503 USD/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/28/middleeast/mideast-summary-02-28-2022-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-01 00:29:35 </td>
   <td style="text-align:left;"> Montreux Convention: How a 1936 treaty could force Turkey to take sides in the Ukraine war  - CNN </td>
   <td style="text-align:left;"> (CNN)Turkey has officially labeled Russia's invasion of Ukraine as a war and says it will restrict some warships from passing through key waterways, in a move that experts said could potentially hinder some of Moscow's military activities in the region.                                                                                                                , On Thursday, Russian forces launched a land, sea and air assault on Ukraine in the biggest attack by one state against another in Europe since World War Two.                                                                                                                                                                                                                 , Ukraine's ambassador to Turkey Vasyl Bodnar went on local television last week and appealed for the government in Ankara to close its key straits to Russian warships under provisions of the 1936 Montreux Convention. Turkey said it could only do so if it officially recognized the conflict as a war, and on Sunday, that's what it did.                                 , On Monday, Turkish President Recep Tayyip Erdogan said his government would "use the authority given to our country by the Montreux Convention on ship traffic in the straits in a way that will prevent the crisis from escalating."                                                                                                                                         , While Erdogan said he considered "Russia's attack on Ukraine unacceptable," he also said Turkey would not abandon its ties with Russia or Ukraine.                                                                                                                                                                                                                            , Here's what you need to know.                                                                                                                                                                                                                                                                                                                                                 , What is the Montreux Convention?                                                                                                                                                                                                                                                                                                                                              , The convention gives Turkey certain control over the passage of warships from the Dardanelles and Bosphorus Straits that connect the Aegean, Marmara, and Black Sea.                                                                                                                                                                                                          , In peace time, warships can pass the straits by prior diplomatic notification with certain limitations on the weight of the ships and arms they carry -- and depending on whether the ship belongs to a Black Sea nation or not. And at times of war, Turkey can bar the passage of the warships of belligerent parties from crossing.                                        , According to the convention, if Turkey is a party to the war or considers itself threatened with imminent danger, it can shut down the straits to the passage of warships.                                                                                                                                                                                                    , How does this affect Russia?                                                                                                                                                                                                                                                                                                                                                  , Both Russia and Ukraine lie on the Black Sea, along with Romania and NATO members Bulgaria and Georgia. Turkey can limit the transit of Russian warships from the Mediterranean to the Black Sea through its straits under the Montreux Convention, but the pact has a caveat: belligerent states' warships can cross if they are returning to their base of origin.          , "If the ship of the war country will return to its port, an exception is made. We will implement all the provisions of Montreux with transparency," said Turkish Foreign Minister Mevlut Cavusoglu, adding that the exception should not be abused.                                                                                                                           , The move would only be symbolic, said Mustafa Aydin, president of the International Relations Council of Turkey.                                                                                                                                                                                                                                                              , "Russia has enough firepower in the Black Sea that it doesn't make sense for NATO countries to [enter]," he said. "Russia has complete supremacy on the water."                                                                                                                                                                                                               , But if the war drags on, Moscow may feel the heat, since Russia had already completed its naval buildup in the Black Sea by shifting units from the Baltic Sea ahead of the start of hostilities, said Serhat Guvenc, professor of international relations at Istanbul's Kadir Has University.                                                                                , Earlier in February, six Russian warships and a submarine transited the Dardanelles and Bosphorus straits to the Black Sea for what Moscow called naval drills near Ukrainian waters.                                                                                                                                                                                         , "They [Russia] probably have enough resources to sustain their naval power in the Black Sea for about two to three months," he said. "But if conflict drags on, it'll be a different story."                                                                                                                                                                                  , Why did Turkey declare the conflict a war?                                                                                                                                                                                                                                                                                                                                    , Guvenc said he hadn't expected Turkey to take a decision so soon, but Ukrainian President Volodymyr Zelensky "put Ankara on the spot" by prematurely thanking Turkey on Twitter for its support.                                                                                                                                                                              , Turkey has said that it has historically respected the treaty and will continue to do so.                                                                                                                                                                                                                                                                                     , Guvenc said it's in Ankara's interest to do so because the treaty supports Turkey at times of war. Any exception made to please Russia could jeopardize the treaty's credibility in the long run.                                                                                                                                                                             , "The United States is very interested in the idea of unrestricted freedom of navigation through the Turkish straits, as is the case with other waterways like the Suez and Panama canals," he said. A deviation from the convention would give the US "a legitimate reason to question Turkey's status as the watchdog of Montreux."                                          , How could this affect Turkey's foreign relations?                                                                                                                                                                                                                                                                                                                             , Turkey has a maritime border with both Ukraine and Russia on the Black Sea and views both countries as friendly. Ankara relies on Russia for tourism and natural gas but also has close economic and defense ties to Ukraine and has, despite Russian objections, sold drones to the country.                                                                                 , The Soviet Union, the Russian state's predecessor, was one of the original signatories of the Montreux Convention.                                                                                                                                                                                                                                                            , "Russia knows the intricacies of the politics and the law and would have been prepared for such an eventuality," said Guvenc. Moscow, however, may not have expected Ankara to act on the treaty so soon, he added.                                                                                                                                                           , "Turkey can sell this move as purely observing an obligation under international law," he said, but the move may be an indication of where Turkey may lean if the conflict drags on. "Turkey has decided to align more with its traditional allies in NATO and the European Union, and a bit away from Russia."                                                               , Other top Middle East news                                                                                                                                                                                                                                                                                                                                                    , Iran rejects deadline, 'politically motivated' claims in nuclear talks                                                                                                                                                                                                                                                                                                        , Iran said on Sunday it will not accept any deadline set by the West to revive its 2015 nuclear deal with world powers, and wants what it described as "politically motivated" claims by UN watchdog IAEA about Tehran's nuclear work to be dropped, Iranian state TV reported.                                                                                                , Background: One of the sticking points in the indirect talks between Iran and the United States to revive the deal appears to be questions about uranium traces found by the IAEA at old but undeclared sites in Iran.                                                                                                                                                        , Why it matters: Media reports said that the US had set a deadline for the nuclear talks in the Austrian capital Vienna. Iran's chief nuclear negotiator was due to return to Vienna on Sunday evening for the talks.                                                                                                                                                          , UAE not taking sides in Ukraine war, senior official says                                                                                                                                                                                                                                                                                                                     , The United Arab Emirates wants to encourage a political solution for the Ukraine war and taking sides would only encourage violence, a senior UAE official said on Sunday.                                                                                                                                                                                                    , Background: The comment, posted by Anwar Gargash on Twitter, comes after the UAE abstained from a Friday vote  on a draft United Nations Security Council resolution condemning Moscow's invasion of Ukraine. It did not pass because of Russia's veto. Read full story                                                                                                       , Why it matters: Gulf Arab states have so far taken a neutral stance between Western allies and Russia, with which they are partners under an oil producers' alliance known as OPEC+. Saudi Arabia and the UAE also have investment and business ties with Moscow.                                                                                                             , UN Security Council to vote on Houthi arms embargo                                                                                                                                                                                                                                                                                                                            , The Security Council is due to vote Monday on a proposal by the United Arab Emirates to impose an arms embargo on Yemen's Houthis after the group claimed several drone and missile assaults on the country this year.                                                                                                                                                        , Background: A year ago, the US revoked a designation of the Houthis as a terrorist organization over concerns that it would worsen Yemen's humanitarian crisis. The UAE, Saudi Arabia and some US lawmakers are pressing the White House to return the Houthi movement to the US list of foreign terrorist groups over the recent Houthi attacks on the UAE and Saudi Arabia. , Why it matters: The measure would expand a targeted UN arms embargo on several Houthi leaders to the whole group. The measure needs nine votes in favor and no vetoes by any of the Security Council's permanent members -- Russia, the US, Britain, France or China.                                                                                                         , Around the region                                                                                                                                                                                                                                                                                                                                                             , Iraqi archaeological authorities reopened a site at the ancient city of Hatra last week following the partial completion of a renovation project of the site once destroyed by ISIS militants years ago, Reuters reports.                                                                                                                                                     , Officials say nearly 15% of the site was destroyed by ISIS militants, who took over large swathes of the country.                                                                                                                                                                                                                                                             , Images published online in 2015 allegedly showed what is described as ISIS militants destroying statues and artifacts at the site with sledgehammers and pickaxes.                                                                                                                                                                                                            , The renovation project is carried out in cooperation with the Italian International Association for Mediterranean and Oriental Studies (ISMEO). Only 5% of the destruction has been renovated and the rest of the project is underway, officials added.                                                                                                                       , Hatra, a UNESCO World Heritage site, was among many sites destroyed by ISIS militants in Iraq and Syria, including the 2,700-year-old city of Khorsabad famed for its colossal statues of human-headed winged bulls.                                                                                                                                                          , ISIS once ruled a self-declared caliphate in parts of Iraq and Syria which contain some of the richest archaeological treasures on earth, where ancient Assyrian empires built their capitals, Greco-Roman civilization flourished and Muslim and Christian sects co-existed for centuries.                                                                                   , Picture of the day                                                                                                                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                               , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-01 00:27:26 </td>
   <td style="text-align:left;"> TSX Struggles for Traction </td>
   <td style="text-align:left;"> Canada's main stock opened on a weak note, with the benchmark S&amp;P/TSX Composite bottoming around its 21,000 psychological level, driven by losses in financials and cyclicals stocks. Concerns about escalating tensions in eastern Europe continued to dominate market sentiment after western powers imposed fresh sanctions on Russian banks. On the data front, Canada posted a current account deficit of CAD 0.8 billion in the fourth quarter of 2021, compared to market expectations of CAD 2.3 billion surpluses. Kinross Gold fell almost 8%, the most on the TSX, and the second-biggest decliner was Maple Leaf Foods, down 5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/poland/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-03-01 00:24:00 </td>
   <td style="text-align:left;"> Poland Q4 GDP Growth Confirmed at 7.3% </td>
   <td style="text-align:left;"> Poland’s gross domestic product advanced 7.3 percent year-on-year in the fourth quarter of 2021, picking up from a 5.3 percent expansion in the previous three-month period and in line with preliminary estimates. Consumption expenditure in the households’ sector advanced by 7.9 percent (vs 4.7 percent in Q3) and the gross fixed capital formation rose by 11.7 percent (vs 9.3 percent). Also, there was a significant positive contribution from changes in inventories, amounting to 4.2 percentage points (vs 3.7 percentage points in Q3). On the other hand, a negative impact of the net exports on the economic growth was noted, amounting to -3.2 percentage points (vs -2.7 percentage points). On a seasonally adjusted quarterly basis, the GDP rose by 1.7 percent, also in line with previous estimates and easing from 2.3 percent in the prior period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-01 00:19:29 </td>
   <td style="text-align:left;"> German 10-Year Bund Yield Falls to Over 3-Week Low </td>
   <td style="text-align:left;"> The yield on the German 10-year Bund declined to below 0.16%, the lowest in more than three weeks, as investors assess how the European Central Bank will respond to the current Russia-Ukraine war. Concerns over the Eurozone’s economic growth mounted due to higher prices of commodities and energy as Western nations announced hash sanctions on Russia. The Biden administration said that it would ban US people and companies from doing business with the Bank of Russia, the Russian National Wealth Fund, and the Ministry of Finance; after G7 nations agreed to exclude Russian banks from SWIFT. Money markets now see the first ECB rate hike only in September, compared to earlier expectations of June; and price in a total of 30 basis points increases by year-end, from roughly 35 bps earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coal </td>
   <td style="text-align:left;"> 2022-03-01 00:07:00 </td>
   <td style="text-align:left;"> Coal Hits All-time High </td>
   <td style="text-align:left;"> Newcastle coal futures broke above $270 per tonne for the first time ever, boosted by soaring demand for electricity and power, particularly from European countries and tight supplies amidst the ongoing Russia-Ukraine war. Germany is set to create reserves of coal for electricity power plant operators; Italy announced it could reopen some shuttered coal plants and Berlin is also considering an incentive plan to revive some troubled liquid natural gas terminal projects. The European Union's coal imports rose by 55.8% in January from a year ago, to 10.8 million tonnes, of which Russia supplied 43%, the data based on ship tracking found. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kenya/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-01 00:06:00 </td>
   <td style="text-align:left;"> Kenya February Inflation Rate at 16-Month Low </td>
   <td style="text-align:left;"> The annual inflation rate in Kenya eased for the fifth straight month to 5.08% in February of 2022, from 5.39% in the previous month, remaining within the central bank’s target range of 2.5% to 7.5%. It was the lowest inflation rate since October of 2020, mainly due to a slowdown in prices of food &amp; non-alcoholic beverages (8.69 percent vs 8.89 percent in January) and housing &amp; utilities (4.79 percent vs 5.11 percent), helped by a 15% cut on electricity tariff effective January. On a monthly basis, consumer prices increased 0.40%, up from a 0.31% rise in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/28/technology/whole-foods-amazon-automation.html </td>
   <td style="text-align:left;"> 2022-03-01 00:04:49 </td>
   <td style="text-align:left;"> Amazon Opens a Whole Foods With the Next Step in Automation - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                             , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                              , A newly revamped store in Washington shows how thoroughly Amazon has woven itself into the grocery shopping experience.                                                                                                                                                                                                                                                                                                                   , By Cecilia Kang                                                                                                                                                                                                                                                                                                                                                                                                                           , Cecilia Kang, who has shopped at the Whole Foods Market in Washington’s Glover Park neighborhood for a decade, covers tech policy.                                                                                                                                                                                                                                                                                                        , “Would you like to sign in with your palm?”                                                                                                                                                                                                                                                                                                                                                                                               , That was the question a cheerful Amazon employee posed when greeting me last week at the opening of a Whole Foods Market in Washington’s Glover Park neighborhood. She blithely added, “You can also begin shopping by scanning the QR code in your Amazon app.”                                                                                                                                                                          , “Let’s go for the palm,” I said.                                                                                                                                                                                                                                                                                                                                                                                                          , In less than a minute, I scanned both hands on a kiosk and linked them to my Amazon account. Then I hovered my right palm over the turnstile reader to enter the nation’s most technologically sophisticated grocery store.                                                                                                                                                                                                               , For the next 30 minutes, I shopped. I picked up a bag of cauliflower florets, grapefruit sparkling water, a carton of strawberries and a package of organic chicken sausages. Cameras and sensors recorded each of my moves, creating a virtual shopping cart for me in real time. Then I simply walked out, no cashier necessary. Whole Foods — or rather Amazon — would bill my account later.                                          , More than four years ago, Amazon bought Whole Foods for $13 billion. Now the Amazon-ification of the grocery chain is physically complete, as showcased by the revamped Whole Foods store in Glover Park.                                                                                                                                                                                                                                 , For a long time, Amazon made only small steps toward putting its mark on the more than 500 Whole Foods stores in the United States and Britain. The main evidence of change were the discounts and free home delivery for Amazon Prime members.                                                                                                                                                                                           , But this 21,000-square-foot Whole Foods just north of Georgetown has catapulted Amazon’s involvement forward. Along with another prototype Whole Foods store, which will open in Los Angeles this year, Amazon designed my local grocer to be almost completely run by tracking and robotic tools for the first time.                                                                                                                     , The technology, known as Just Walk Out, consists of hundreds of cameras with a god’s-eye view of customers. Sensors are placed under each apple, carton of oatmeal and boule of multigrain bread. Behind the scenes, deep-learning software analyzes the shopping activity to detect patterns and increase the accuracy of its charges.                                                                                                   , The technology is comparable to what’s in driverless cars. It identifies when we lift a product from a shelf, freezer or produce bin; automatically itemizes the goods; and charges us when we leave the store. Anyone with an Amazon account, not just Prime members, can shop this way and skip a cash register since the bill shows up in our Amazon account.                                                                          , Amazon has tested such automation for more than four years, starting with 24 Amazon Go convenience stores and several Amazon Fresh grocery stores around the country. The palm-scanning technology, known as Amazon One, is also being licensed by others, such as a Hudson convenience store at Dallas Love Field Airport and Shaquille O’Neal’s Big Chicken restaurant at Climate Pledge Arena in Seattle.                              , Those stores were valuable experiments, said Dilip Kumar, Amazon’s vice president of physical retail and technology. The company is treating Whole Foods as another step in its tech expansion into retail stores, he said.                                                                                                                                                                                                               , “We observed areas that caused friction for customers, and we diligently worked backward to figure out ways to alleviate that friction,” Mr. Kumar said. “We’ve always noticed that customers didn’t like standing in checkout lines. It’s not the most productive use of their time, which is how we came up with the idea to build Just Walk Out.”                                                                                      , He declined to comment on whether Amazon planned to expand the technology to all Whole Foods stores.                                                                                                                                                                                                                                                                                                                                      , My New York Times colleague Karen Weise, who covers Amazon from Seattle, said the company operated on long time horizons, with the patience and money to execute slowly. That has allowed it to transform labor, retail and logistics over many years, she said. Groceries are just one piece of its ambitions.                                                                                                                           , The Whole Foods in Glover Park has operated for more than 20 years, a cornerstone of a neighborhood that is within walking distance of Embassy Row and the vice president’s Naval Observatory residence. Four years ago, the store closed over a dispute with the landlord and a rat infestation. Amazon announced last year that it would reopen the store as a Just Walk Out pilot project.                                             , The rats may be gone, but not the neighborhood angst. The renovated store has sparked a spirited local debate, with residents sparring on the Nextdoor community app and a neighborhood email listserve over the store’s “dystopian” feeling versus its “impressive technology.” Some neighbors reminisced about how the store used to invite people to just hang out, with free samples and fluffy blueberry pancakes sold on weekends.  , Alex Levin, 55, an 18-year resident of Glover Park, said people should not reject the store’s changes.                                                                                                                                                                                                                                                                                                                                    , “We need to understand the benefits and downsides of the technology and use it to our advantage,” he said. He added that he had tried tricking the cameras and sensors by placing a box of chicken nuggets in his shopping bag and then putting the item back in a freezer. Amazon wasn’t fooled, and he wasn’t charged for the nuggets, he said.                                                                                         , But others said they had found errors in their bills and complained about the end of produce by the pound. Everything is now offered per item, bundle or box. Some mourned the disappearance of the checkout line, where they perused magazines and last-minute grab bag items. Many were suspicious of the tracking tech.                                                                                                                , “It’s like George Orwell’s ‘1984,’” said Allen Hengst, 72, a retired librarian.                                                                                                                                                                                                                                                                                                                                                           , Amazon said it didn’t plan to use video and other Whole Foods customer information for advertising or its recommendation engine. Shoppers who don’t want to participate in the experimental technology can enter the store without signing in and pay at self-checkout kiosks with a credit card or cash.                                                                                                                                 , As a longtime customer of Glover Park’s Whole Foods, I had missed the dark, cramped and often chaotic store and was excited to explore the changes. But somewhere between the palm scan and the six-pack banana bundles, I began to feel ambivalent.                                                                                                                                                                                      , I noticed a sign near the entrance that forbade shoppers to take photos or videos inside. My eyes drifted toward the ceiling, where I noticed hundreds of small black plastic boxes hanging from the rafters.                                                                                                                                                                                                                             , An employee jumped in. “Those are the cameras that will follow you during your shopping experience,” she explained, with no hint of irony.                                                                                                                                                                                                                                                                                                , Several workers milled about the entrance to guide customers through check-in, while others stood behind the seafood counter, cheese station and produce areas. Mr. Kumar said the stores would always employ humans, but I wondered for how much longer. Amazon, under scrutiny for its labor practices, said employees’ roles might shift over time and become more focused on interacting with customers to answer questions.          , There were early signs of a more self-service future. At the bakery, I looked for someone to slice my $4.99 Harvest loaf and was directed to an industry-grade bread slicer for customers. A small label warned: Sharp blades. Keep hands clear of all moving parts.                                                                                                                                                                      , Mr. Kumar wouldn’t share data on the accuracy of Just Walk Out, so I tested the technology. I picked up an organic avocado and placed it on a pile of nonorganic avocados. After walking around the store, I went back and picked up the same organic avocado. If the cameras and sensors functioned properly, Amazon would be on top of my actions and charge me for the organic avocado that had been misplaced in the conventional bin., When I was ready to leave, I had the option of using a self-checkout kiosk or skipping the process. I decided on the latter and waved my palm again over an exit turnstile. The turnstile’s arms opened.                                                                                                                                                                                                                                  , “You should receive your receipt within two to three hours,” an employee at the exit said.                                                                                                                                                                                                                                                                                                                                                , I walked out. It felt discomfiting, like I might be mistaken for a shoplifter.                                                                                                                                                                                                                                                                                                                                                            , An email from Amazon landed in my inbox an hour later. A link sent me to my Amazon account for details. It said my shopping experience had lasted 32 minutes 26 seconds. My total bill was $34.35 — and I was correctly charged for the organic avocado.                                                                                                                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/moscow-suspends-stock-trading-until-march-5 </td>
   <td style="text-align:left;"> 2022-03-01 00:01:38 </td>
   <td style="text-align:left;"> Moscow suspends stock trading until March 5 </td>
   <td style="text-align:left;"> Ernst &amp; Young Global managing partner Andy Baldwin discusses the impact of Russia's invasion of Ukraine on the global economy and what to expect at the Mobile World Congress.                                                                                                                                                                          , Russia's central bank has shut down the country's stock exchange for the week as the ruble plummets amid mounting sanctions imposed by other nations over Russian President Vladmir Putin's invasion of Ukraine.                                                                                                                                        , RUSSIA-UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                            , The Moscow Exchange building in Moscow on Wednesday, Feb. 23, 2022. (Andrey Rudakov/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                          , The Bank of Russia announced early Monday that the Moscow Exchange would not open some sections of the market for the day in light of the "current situation," before sending a second alert saying trading would be entirely suspended until March 5.                                                                                                  , Russian-related exchange-traded funds took a hit on Monday.                                                                                                                                                                                                                                                                                             , The decision comes as the central bank scrambles to try and mitigate steep, coordinated economic sanctions imposed by several other countries, including the U.S., and as the ruble hit a new record low versus the dollar.                                                                                                                             , A Russian flag flies above the headquarters of Bank Rossii, Russia's central bank, in Moscow on Monday, Feb. 28, 2022. (Andrey Rudakov/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                       , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                    , The Bank of Russia also signaled it would resume buying gold on Monday, and raised its key interest rate to 20%, up from 9.5%, in an effort to fight the depreciation of the ruble and higher inflation.                                                                                                                                                , NATO allies and other nations have taken action to inflict economic pain on Russia as Putin continues his bloody assault on Ukraine. Select Russian banks are set to be removed from the SWIFT international banking network by the European Union, and the Bank of Russia has also been targeted directly with sanctions from the Biden administration., President Vladimir Putin speaks to the media at the Kremlin in Moscow on Feb. 22, 2022. (Mikhail Klimentyev/Russian Presidential Press and Information Office/TASS via Getty Images / Getty Images)                                                                                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                             , A senior White House official told FOX Business on Monday, "Our strategy is to make sure that the Russian economy goes backward as long as President Putin decides to go forward with his campaign."                                                                                                                                                    , FOX Business' Ronn Blitzer and Paul Conner contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/austria/producer-prices-change </td>
   <td style="text-align:left;"> 2022-02-28 23:54:36 </td>
   <td style="text-align:left;"> Austria Producer Inflation Hits Record High </td>
   <td style="text-align:left;"> The industrial producer price index in Austria climbed 18.4 percent year-on-year in January of 2022, accelerating from a 16.7 percent rise in the previous month. It was the largest increase in producer prices since records began in January 2000, mainly boosted by high prices in the energy sector (43.3 percent vs 39.3 percent) and intermediate goods (19 percent vs 17.2 percent). Also, prices went up for both consumer goods (3.5 percent vs 3.2 percent) and capital goods (2.9 percent vs 1.8 percent). On a monthly basis, producer prices went up 2.4 percent, after a 1.5 percent increase in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/dallas-fed-manufacturing-index </td>
   <td style="text-align:left;"> 2022-02-28 23:52:00 </td>
   <td style="text-align:left;"> Texas Manufacturing Activity Growth at 4-Month High </td>
   <td style="text-align:left;"> The Federal Reserve Bank of Dallas' general business activity index for manufacturing in Texas rose by 12 points to +14.0 in February of 2022, up from the previous month's 1-1/2-year low of +2.0. It was the highest reading since October of 2021, as new orders increased by 3 points to 23.1, while the growth rate of the orders index held steady at 12.6, with both readings significantly above average. The capacity utilization index was unchanged at 11.5, and the shipments index rallied 15 points to 23.5. Employment growth remained robust while wages and prices continued to increase in February, with the indexes near record highs. Finally, expectations regarding future manufacturing activity were higher in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-02-28 23:49:28 </td>
   <td style="text-align:left;"> Sweden Retail Sales Rise for 13th Month </td>
   <td style="text-align:left;"> Sweden retail sales advanced by 5.1 percent year-on-year in January of 2022, following a 4.1 percent increase in the previous month. It was the 13th consecutive month of expansion in retail activity. Retail sales of durable increased by 5 percent and retail sales in consumables rose by 4.5 percent. On a monthly basis, retail sales rebounded by 4.5 percent, after falling 4.4 percent in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2022-02-28 23:48:00 </td>
   <td style="text-align:left;"> Mexican Peso Weakens on Geopolitical Risk </td>
   <td style="text-align:left;"> The Mexican peso weakened to around 20.4 per USD, moving away from the four month high of 20.2 per USD touched on last week amid a stronger dollar as investors continue to seek safe-haven assets during a high volatility period for emerging market currencies. During the weekend, multiple western states agreed to exclude key Russian banks from the Swift system, while US President Biden’s administration banned US individuals and firms from transacting with the CBR, Russian National Wealth Fund, and Ministry of Finance. Still, expectations of further interest rate hikes by Banxico limited the peso’s decrease. The central bank said that the inflation risks remain biased to the upside, as inflation expectations for 2022 and 2023 increased again, while medium-term expectations decreased slightly and those for the long-term have remained stable at levels above the target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-02-28 23:44:00 </td>
   <td style="text-align:left;"> Euro Remains Under Pressure </td>
   <td style="text-align:left;"> The euro depreciated to $1.12, closing in on the weakest level since June 2020 amid heightened geopolitical risks to the bloc’s economy from higher prices of commodities and energy after Russia invaded Ukraine and the West ramped up sanctions. G7 nations agreed to exclude Russian banks from SWIFT, and Biden’s administration announced it would ban US people and companies from doing business with the Bank of Russia, the Russian National Wealth Fund, and the Ministry of Finance. Meanwhile, delegations from Kyiv and Moscow met on the Belarusian border on Monday, and the possibility of a full-scale assault on the capital is rising as heavy fighting is reported. Adding to the bearish tone, investors cut back their bets for European Central Bank rate hikes this year. Money markets now see the first ECB rate hike only in September, compared to earlier expectations of June; and price in a total of 30 basis points increases by year-end, from roughly 35 bps earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/portugal/gdp-growth </td>
   <td style="text-align:left;"> 2022-02-28 23:43:00 </td>
   <td style="text-align:left;"> Portugal GDP Growth Confirmed at 1.6% in Q4 </td>
   <td style="text-align:left;"> Portugal’s GDP expended 1.6 percent quarter-on-quarter in the last three months of 2021, in line with preliminary estimates and slowing from a downwardly revised 2.8 percent expansion in the previous quarter. Net external demand was positive but its contribution to GDP growth decreased, as imports (7.0 percent vs 4.6 percent in Q3) almost offset exports (8.9 percent vs 8.8 percent). Meanwhile, growth of domestic demand lost some momentum (0.9 percent vs 1.3 percent), reflecting a softer increase in household spending (1.0 percent vs 1.7 percent), amid stronger headwinds from spending in nondurable goods. Finally, gross fixed investment rebounded strongly (3.5 percent vs -1.8 percent). On an annual basis, GDP advanced 5.8 percent, quickening from a downwardly revised 4.4 percent expansion in the third quarter. Considering 2021 as a whole, the economy of Portugal expanded 4.9 percent, rebounding from an unprecedented, downwardly revised 8.4 percent contraction in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-28 23:34:49 </td>
   <td style="text-align:left;"> Oil Poised for Third Straight Monthly Gain </td>
   <td style="text-align:left;"> WTI crude oil surged more than 4% to above $95 a barrel on Monday, and it's on track for a third consecutive monthly gain after Western nations imposed fresh sanctions on Russia, raising fears of supply disruptions from one of the world's largest oil and gas producers. This massive rally that saw the US benchmark top $100 for the first time since 2014 earlier this month already prompted discussions about a coordinated release of about 60 million barrels of oil from the US and its ally's emergency oil reserves to cool markets. Meanwhile, OPEC+ is likely to stick to a planned output rise at a meeting this week, while investors are also closely monitoring the Iran nuclear talks amid signs of progress. A potential deal could add more than 1 million barrels a day of supply and help ease a tight global market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/28/business/toyota-stoppage-cyberattack.html </td>
   <td style="text-align:left;"> 2022-02-28 23:22:33 </td>
   <td style="text-align:left;"> Toyota Stops Production After Possible Cyberattack at a Supplier - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                               , A supplier to the automaker said it had shut down its computer network to respond to what might have been a hack or a virus.                                                                                                                                                                                                                                               , By Ben Dooley and Hisako Ueno                                                                                                                                                                                                                                                                                                                                              , TOKYO — Toyota, the world’s largest automaker, said on Monday that it had suspended all production in Japan after a possible cyberattack at a major supplier.                                                                                                                                                                                                              , The stoppage followed a problem with computer systems at Kojima Industries, a manufacturer of automotive components, that disrupted the company’s ordering systems. The problem first appeared Saturday night, and the company decided to shut down its computer network to prevent the issue from spreading to customers, a company spokesman said.                       , Kojima Industries has not yet been able to determine the cause of the problem, but it suspects a cyberattack or virus. The company’s website remained down Monday evening.                                                                                                                                                                                                 , In comments at a news conference on the situation in Ukraine, Prime Minister Fumio Kishida of Japan said the government was aware of the Toyota shutdown and was investigating the cause.                                                                                                                                                                                  , Cyberattacks have become increasingly common in Japan in recent years. Japanese companies have been slow to update their networks to account for the growing use of ransomware by criminals, as well as intrusions by state actors. Manufacturers have been the most common targets for the attacks, which can essentially hold computer systems and valuable data hostage., Like many other automakers, Toyota had to substantially cut production after the pandemic wreaked havoc on global supply chains and led to shortages of semiconductors and other components.                                                                                                                                                                               , Last year, after the initial waves of the virus passed and global demand for automobiles surged, Toyota announced optimistic plans to produce 9.3 million units worldwide by March 31, the end of its fiscal year.                                                                                                                                                         , But skyrocketing demand for semiconductors and recurring waves of infection forced the company to reduce those plans first to nine million and then, in February, to eight and a half million.                                                                                                                                                                             , Even before the problems at Kojima Industries, Toyota had planned temporary stoppages in March at several factories in Japan because of parts shortages.                                                                                                                                                                                                                   , The stoppage announced on Monday includes Toyota’s 14 domestic factories and will affect the production of 13,000 vehicles, a Toyota spokeswoman said, adding that the company could not yet say for certain how long the factories would remain idle.                                                                                                                     , Despite the setbacks, Toyota has managed to use lessons learned during a 2011 earthquake and tsunami that devastated northeastern Japan to adjust to the pandemic’s disruptions better than its competitors, topping the global auto sales charts for two consecutive years.                                                                                               , Hino, a subsidiary of Toyota that manufactures heavy trucks and buses, said in a statement Monday that it would also pause production at two factories because of problems at an unspecified supplier. Another subsidiary, Daihatsu, has also paused some production, according to local media reports.                                                                    , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-28 23:06:58 </td>
   <td style="text-align:left;"> Colombia 10Y Bond Yield Hits 12-1/2-year High </td>
   <td style="text-align:left;"> Colombia 10 Year Government Bond Yeld increased to a 12-1/2-year high of 9.556% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coffee </td>
   <td style="text-align:left;"> 2022-02-28 23:05:00 </td>
   <td style="text-align:left;"> Arabica Coffee Hits 4-Week Low </td>
   <td style="text-align:left;"> Arabica coffee futures on ICE were trading around $2.4, its lowest since January 31th, on expectations of lower demand. Worries are growing that Russia's invasion of Ukraine could derail the global growth, curbing consumer spending and reducing coffee consumption. Meanwhile, the outlook for crop production in top producer Brazil has improved on prospects of adequate rains this season. Brazilian farmers are expected to harvest 58.9 million 60-kg bags of coffee in the new season (2022/23), a bit more than the 53.7 million bags they produced in the previous cycle that was hit by drought and frosts. Still, global supplies of arabica coffee remain tight amid ongoing logistical issues due to the pandemic, along with the effects of climate change. Certified ICE arabica stocks continued to fall to 1.03 million bags, their lowest volume for the last 20 years and down sharply from 1.54 million bags at the end of 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/chicago-pmi </td>
   <td style="text-align:left;"> 2022-02-28 22:50:00 </td>
   <td style="text-align:left;"> Chicago Business Barometer at 1-1/2-Year Low </td>
   <td style="text-align:left;"> The Chicago PMI in the United States decreased to 56.3 points in February of 2022 from 65.2 points in January and missing market forecasts of 63. It was the lowest reading since August of 2020, suggesting a slowdown in economic activity. All five of the main five indicators fell, with new orders and supplier deliveries taking the largest hit. Only Inventories edged up over the month, as firms continued stocking up due to persistent supply chain disruptions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/28/jpmorgan-project-will-push-bank-further-into-market-serving-private-firms.html </td>
   <td style="text-align:left;"> 2022-02-28 22:43:29 </td>
   <td style="text-align:left;"> Secret JPMorgan project aims to push bank deeper into growing market serving private companies </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                           , JPMorgan Chase is preparing to go all-in on private companies.                                                                                                                                                                                                                                                                                                                                                                                            , For the past year, the bank has been quietly hiring programmers and creating products for a new fintech business that aims to provide an array of services to start-ups and investors around the world, according to people with knowledge of the matter.                                                                                                                                                                                                 , The business, known internally by the code name "Project Bloom" because of its goal of helping early-stage private firms grow, is run by Michael Elanjian, head of digital private markets, said the people, who declined to be identified speaking before its launch.                                                                                                                                                                                    , JPMorgan, the biggest U.S. bank by assets, raised eyebrows last month when it said that expenses would surge this year, in part because of an annual technology budget that has grown to at least $12 billion. CEO Jamie Dimon is aggressively investing to help his bank battle fintech firms, and executives see an opportunity to create a private-markets winner before start-ups can dominate the space.                                             , A key part of Project Bloom is a digital network for JPMorgan clients that will match start-ups with investors, helping them in fundraising rounds, said the people. Other planned-for services include helping companies sell shares in tender offers or providing loans on private stakes, offering a digital interface for secondary trading of private company stock, and helping venture capital firms raise new funds.                              , While elements of these offerings exist across parts of JPMorgan's sprawling operations, the new effort aims to create a one-stop digital portal for start-ups and venture capital firms, family offices and other institutional investors, said the people.                                                                                                                                                                                              , The business aims to tie in offerings from the firm's corporate and investment bank, commercial bank and private bank. For instance, the private markets trading desk first reported by CNBC in 2020 will feed into the new platform, according to the sources.                                                                                                                                                                                           , By creating a self-service platform, JPMorgan can target smaller, earlier-stage companies than its bankers traditionally engage with, helping them raise funds and offering automated recommendations, the people said.                                                                                                                                                                                                                                   , JPMorgan's move comes as the number of private companies being created continues to explode. Investors are funneling billions of dollars into the asset class in the hopes of catching companies before they mature and their growth prospects level off, and start-ups are staying private for far longer because of the near-limitless access to capital.                                                                                               , Since the start of the pandemic in 2020, the number of unicorns, or private companies valued at $1 billion or more, has more than doubled to 1,032, collectively valued at $3.4 trillion, according to data provider CB Insights.                                                                                                                                                                                                                         , That has lifted the fortunes of start-ups like Carta, Brex and Forge that cater to private companies in one way or another. Banks have historically geared their services to public companies and more established start-ups that are approaching public listings, leading to the rise of specialty providers.                                                                                                                                            , Now, JPMorgan appears to be betting that if it can create a fully-scaled private company network before the fintechs do, its place in a future in which private companies have even greater importance will be assured.                                                                                                                                                                                                                                   , The new JPMorgan business has grown to 80 or so employees operating in stealth mode, walled off from other JPMorgan employees in more than a half dozen cities around the world, including in New York and New Jersey; Plano, Texas; Chicago; Glasgow; London and Buenos Aires, said the people.                                                                                                                                                          , The bank is in the midst of a hiring spree, pushing for 200 employees for the private markets business by year-end and specifically looking for software engineers, data wranglers and artificial intelligence specialists, according to job listings.                                                                                                                                                                                                    , "We are building a high-profile and exciting new data-driven fintech business for the firm, with the goal of creating a market leading platform for private markets," the bank said in one job post. The team "building the product brings together data scientists, finance specialists, former entrepreneurs, product managers, designers, and engineers, who work together with the benefits of a startup culture that can leverage the scale of JPM." , Another job post, this one for a business development manager, said the bank was looking for "individuals with entrepreneurial experience" like founders and investors to help it acquire clients for the business, referred to as Digital Private Markets.                                                                                                                                                                                               , In response to queries, JPMorgan spokeswoman Jessica Francisco had this response: "We've been a leader in private capital markets for years, and we see opportunity to provide new digital capabilities to private companies and investors."                                                                                                                                                                                                              , Word about the project began circulating within JPMorgan and at competitors earlier this month after Elanjian gave a presentation to Dimon and 200 other executives at the bank's annual senior leadership conference in Miami, according to people familiar.                                                                                                                                                                                             , The firm is gearing up to release a suite of products this year and recently launched its inaugural piece of software to a small group of clients, these people said.                                                                                                                                                                                                                                                                                     , Elanjian, who joined JPMorgan from archrival Goldman Sachs in 2018, hopes to sign several hundred companies and hundreds of investors onto the platform before its official launch later this year, according to the people.                                                                                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/balance-of-trade </td>
   <td style="text-align:left;"> 2022-02-28 22:41:48 </td>
   <td style="text-align:left;"> Sweden Trade Surplus Narrows in January </td>
   <td style="text-align:left;"> Sweden’s trade surplus shrank to SEK 0.4 billion in January of 2022 from SEK 4.2 billion in the corresponding month of the previous year. Exports rose 25 percent from a year earlier to SEK 142.9 billion and imports advanced at a faster 30 percent to SEK 142.5 billion. The number of weekdays in January 2022 was one more compared with January 2021. Trade in goods with countries outside the EU resulted in a deficit of SEK 10.8 billion, while EU trade resulted in a deficit of SEK 10.8 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macau/unemployment-rate </td>
   <td style="text-align:left;"> 2022-02-28 22:40:03 </td>
   <td style="text-align:left;"> Macau Jobless Rate at Over 12-Year High </td>
   <td style="text-align:left;"> The unemployment rate in Macau inched up to 3.2 percent in the three-month period ending January of 2022, from 3.1 percent in the previous three-month period. It was the highest jobless rate since the three months to November of 2009, as the number of unemployed increased by 500 people to 12,400. Meanwhile the employed population rose by 1,900 to 379,000, mostly in restaurants &amp; similar activities, hotels &amp; similar activities, and wholesale &amp; retail trade. The labor force participation rate edged up to 69.9 percent from 69.0 percent in the previous period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-02-28 22:37:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Down for 3rd Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 1.7% to 2,040 on Monday, extending losses into a third consecutive session, amid lower rates for capesize and panamax vessels due to concerns over the impact of the Ukraine crisis. "Traders fear EU/US sanctions against Russian energy exports will disrupt supplies and tanker availability, and are looking outside the Black Sea region for alternative crude sources," analysts at Jefferies said. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, fell 74 points to 1,617; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, eased 59 points to 2,599. Among smaller vessels, the supramax index went up 11 points to 2,428. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-28 22:31:00 </td>
   <td style="text-align:left;"> Wall Street Resumes Slide </td>
   <td style="text-align:left;"> US equity markets were under renewed selling pressure on Monday, with the Dow shedding more than 400 points at the open and  S&amp;P 500 and Nasdaq declining more than 1% after new sanctions imposed on Russia deepened tensions across markets. During the weekend, G7 nations agreed to exclude Russian banks from SWIFT, while Biden’s administration announced Monday that it would ban US people and companies from doing business with the Bank of Russia, the Russian National Wealth Fund, and the Ministry of Finance. Despite the escalation, a Ukrainian delegation held talks with Russian officials near the Belarusian border. Adding to the gloomy mood, the Federal Reserve warned last week that inflation could persist longer than expected unless a shortage of available workers begins to ease. As a result, US stocks are on track for their second consecutive monthly drop, with the Dow Jones down more than 4% in February, the most since September 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/solar </td>
   <td style="text-align:left;"> 2022-02-28 22:30:18 </td>
   <td style="text-align:left;"> Solar Energy Index Hits 5-week High </td>
   <td style="text-align:left;"> Solar Energy Index increased to a 5-week high of 332.12 USD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-28 22:19:00 </td>
   <td style="text-align:left;"> Russian 10Y Bond Yield Rises on Harsher Sanctions </td>
   <td style="text-align:left;"> The 10-year OFZ treasury bond rose to nearly 13%, approaching the 7-year high of 14% touched on last week in a thin trading environment due to suspended activity in the Moscow Exchange, as investors weighed on fresh sanctions from western states amid Russia’s attack on various Ukrainian cities. Harsher measures from the West drove the Central Bank of Russia to hike its key interest rate to 20% from 9.5% in an emergency move, while telling export-led businesses to sell 80% of their foreign currency as the ruble depreciated to record lows. The US, EU and their allies agreed over the weekend to remove key Russian banks from the SWIFT interbank messaging system and freeze the assets of Russia’s central bank, limiting the country’s ability to access its overseas reserves. Sanctions from Washington have also banned US people and companies from doing business with the CBR, Russian Ministry of Finance and National Wealth Fund. Lastly, S&amp;P Global Ratings cut Russia’s credit to BB+ from BBB-. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/iceland/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-02-28 22:12:33 </td>
   <td style="text-align:left;"> Iceland Q4 GDP Annual Growth Moderates </td>
   <td style="text-align:left;"> Iceland’s GDP increased by 4.4 percent year-on-year in the last quarter of 2021, slowing from an upwardly revised 6.8 percent expansion in the previous three-month period, which was the fastest in almost five years. Main positive contributions came from private final consumption (12.9 percent vs 6.5 percent in Q3) and gross fixed capital formation (15.0 percent vs 32.2 percent). To a lesser extent, government spending also aided the economy (1.5 percent vs 1.4 percent), while net external demand fell sharply, as export growth halved (15.0 percent vs 32.2 percent) while imports rose sharply (34.7 percent vs 28.9 percent). On a seasonally adjusted quarterly basis, the economy rose 2.2 percent, rebounding from a downwardly revised 1.1 percent contraction in the previous quarter. Considering 2021 as a whole, GDP increased 4.3 percent, recovering from an upwardly revised 7.1 percent drop in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/norway/household-spending-mom </td>
   <td style="text-align:left;"> 2022-02-28 22:12:12 </td>
   <td style="text-align:left;"> Norway Personal Spending Falls the Most in 17 Months </td>
   <td style="text-align:left;"> Household consumption of goods in Norway decreased by 4.4 percent month-on-month in January of 2022, extending a 0.7 percent fall in the previous month. This was the steepest increase in personal spending since August 2020, dragged down by spending on vehicles &amp; petrol (-22.9 percent vs 4.4 percent in December); and electricity &amp; heating fuels (-7.4 percent vs 2.1 percent). On the other hand, spending rebounded for food, beverages, &amp; tobacco (0.8 percent vs flat reading in December) and for other goods (0.4 percent vs -3.8 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/28/bill-ackman-says-its-time-for-us-troops-to-defend-ukraine-and-set-a-real-red-line.html </td>
   <td style="text-align:left;"> 2022-02-28 22:05:16 </td>
   <td style="text-align:left;"> Bill Ackman says U.S. military intervention may be needed as Russia-Ukraine conflict unfolds </td>
   <td style="text-align:left;"> , Investor Bill Ackman said Monday the U.S. should consider military intervention in defense of Ukraine as Russian forces continue to advance into the country from multiple directions.                                                                                                                                                                                                                                                                                  , In a series of tweets to more than 400,000 followers, the founder and CEO of Pershing Square Capital Management urged President Joe Biden to start considering taking actions beyond economic sanctions if the conflict doesn't resolve.                                                                                                                                                                                                                                , "I hope Russia stops this onslaught, but I don't see how Putin saves face. We need to be prepared for what comes next which means we need to start thinking about intervening military," Ackman said in the Twitter thread. "Isn't it time we set a real red line?"                                                                                                                                                                                                     , "We can't sit back and allow hundreds of thousands of Ukrainians and perhaps millions to die. I don't want to live in that world and you don't either. @POTUS, it is in your hands. You can fix the errors of the past and protect our future. With all due respect Mr. President, the time is now," Ackman said.                                                                                                                                                       , The Biden administration has announced sanctions against Russia's central bank, the National Wealth Fund of the Russian Federation and Russia's Ministry of Finance, moves that effectively prohibit Americans from doing any business with the entities. The action will also freeze assets of the Russian central bank in the United States.                                                                                                                          , In the latest development, a Ukrainian delegation has arrived near the border with Belarus to hold talks with Russian officials. Ukraine's armed forces continue to hold off Russian troops, defending and retaining control of key cities, and slowing Russia's advance on Kyiv.                                                                                                                                                                                       , Ackman later moved to clarify his earlier remarks, saying he wasn't proposing U.S. troops on the ground as soon as possible.                                                                                                                                                                                                                                                                                                                                            , "I am not advocating U.S. boots on the ground today. Putin has threatened the nuclear option," Ackman wrote in a separate post. "We need to set a red line on the use of nuclear weapons to deter their use. If the unthinkable happens, I see no alternative to our entering the war."                                                                                                                                                                                 , The White House told CNBC the administration continues to provide Ukraine with security assistance to help it defend its country.                                                                                                                                                                                                                                                                                                                                       , "Deliveries of U.S. security assistance to help the Ukrainian military defend their country are ongoing and have been arriving regularly. And we are working with Allies to facilitate the transfer of U.S.-made military equipment from their inventories to Ukraine," a White House spokesperson said.Clarification: This article has been updated to clarify that the sanctions announced Monday will freeze assets of the Russian central bank in the United States., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-28 21:55:28 </td>
   <td style="text-align:left;"> US Futures Fall on Russian Sanctions </td>
   <td style="text-align:left;"> US stock futures fell on Monday, with the Dow set to open more than 300 points lower and both the S&amp;P 500 and the Nasdaq down about 1% as investors assess new sanctions on Russia while officials meet at the Belarus border. During the weekend, G7 nations agreed to exclude major Russian banks from the SWIFT and today Biden’s administration banned US people and companies from doing business with the Bank of Russia, the Russian National Wealth Fund and the Ministry of Finance. Last Friday, despite the volatility, the Dow added 835 points on its best day since November 2020, the S&amp;P 500 gained 2.2% and the Nasdaq rose 1.6%. The Dow ended lower for the third week while the S&amp;P gained 0.8% and the Nasdaq advanced 1.1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/wholesale-inventories </td>
   <td style="text-align:left;"> 2022-02-28 21:41:00 </td>
   <td style="text-align:left;"> US January Wholesale Inventories Expand Less </td>
   <td style="text-align:left;"> Wholesale inventories in the US rose 0.8 percent month-over-month to $798.2 billion in January of 2022, slowing from an upwardly revised 2.3 percent increase in December, a preliminary estimate showed. It was the 18th straight month of expansion, amid increases in inventories of both durable goods (1.0 percent vs 2.8 percent in December) and nondurable ones (0.5 percent vs 1.6 percent). On an annual basis, wholesale inventories advanced 17.8 percent in January. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-03-01 08:42:42 UTC +8

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
   <td style="text-align:left;"> 2022-03-01 08:42:29 </td>
   <td style="text-align:left;"> $SPY Closed the month down 3.17% bringing the decline to 8.23% on the year. This is the first time that the $SPY dropped in consecutive months since September-October of 2020. 
 
$QQQ $AAPL $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:41:58 </td>
   <td style="text-align:left;"> $SPY who made this? 💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:41:46 </td>
   <td style="text-align:left;"> $SPY the world stage is laughing at the incompetence of the Russian military. And they think they can carry their hand in a conflict with the US?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:41:24 </td>
   <td style="text-align:left;"> $DWAC $Spy  if you&amp;#39;re pressing these money buttons they&amp;#39;ve got you.. you&amp;#39;re hooked.. this is a business model to separate you from your hard-earned money.. this business model does not take any mortal ethics into consideration in fact they know statistically fear and Hate generate some of the best profits.. know that you have a problem and seek immediate help. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:41:12 </td>
   <td style="text-align:left;"> $SPY 40-mile convoy priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:40:54 </td>
   <td style="text-align:left;"> $SPY $DWAC $RTX  It&amp;#39;s clear Ukraine should give terms of surrender and end this bloodshed. Let Putin stay in power but require a full disarming of all WMDs and the deployment of Ukrainian peacekeeping forces to Moscow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:40:54 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:40:51 </td>
   <td style="text-align:left;"> $SPY Futures update 👇👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:40:34 </td>
   <td style="text-align:left;"> $SPY spy to 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:40:30 </td>
   <td style="text-align:left;"> $SPY IT&amp;#39;S EASY TO ROOT FROM THE SIDELINES. ANYONE CAN VIRTUE SIGNAL THOUSANDS OF MILES FROM THE ACTION. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:40:18 </td>
   <td style="text-align:left;"> $SPY Anyone need to be reminded of FED and March </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:40:02 </td>
   <td style="text-align:left;"> $SPY don’t worry bears, more downside and volatility coming until there is peace. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:40:01 </td>
   <td style="text-align:left;"> $SPY if zelensky dies tomorrow 😞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:39:54 </td>
   <td style="text-align:left;"> $SPY oopsy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:39:52 </td>
   <td style="text-align:left;"> $SPY he&amp;#39;s so strong and brave </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:39:41 </td>
   <td style="text-align:left;"> $SPY Ukraine military kills Chechen general. Ha get wrecked fascists. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:39:17 </td>
   <td style="text-align:left;"> $SPY $QQQ What the USA needs right now is a good spanking and to show them the world isn&amp;#39;t afraid of them anymore. 
You&amp;#39;ve got clowns running the show! 
A good war is what they need...Send theses young punks that don&amp;#39;t work and sit on their ass all the long playing video games and smoke weed. Let them know what it feels like to not be spoon fed by mom &amp;amp; dad. Degenerates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:39:06 </td>
   <td style="text-align:left;"> $SPY Exposed Globalist agenda… 

https://youtu.be/K3vRnPUD1ZI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:39:04 </td>
   <td style="text-align:left;"> $SPY Today Biden said not to worry about nuclear war 👀

Translation: Pelosi and friends need to adjust stock positions so keep calm and keep thinking bullish so we can properly and quietly positions for rugpull 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:38:53 </td>
   <td style="text-align:left;"> $SPY FLAT for the day.
$BTC.X +16% 📈

Bitcoin has decoupled. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:38:43 </td>
   <td style="text-align:left;"> $SPY near $351  would put us around a 50% pullback off of march 2020 lows and the Quantitative Counterfeiting induced 2021 highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:38:24 </td>
   <td style="text-align:left;"> $SPY massive 10 point pump coming tomorrow. Followed by another 10 point pump on Wednesday. FED needs to get Spy to $460 before mar 10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:38:21 </td>
   <td style="text-align:left;"> $SPY Zelenskyy is going to fight a 40-mile convoy. dude is a fkn tank. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:38:18 </td>
   <td style="text-align:left;"> $SPY Folks need to know the world is analog not digital.  It’s not marvel with good guy bad guy.  

Much more gray and complex. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:38:12 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:38:10 </td>
   <td style="text-align:left;"> Only Amazon and tesla are pumped like hell EVERY DAY since past week😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:38:07 </td>
   <td style="text-align:left;"> $SPY cnbc said better buy puts than calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:38:03 </td>
   <td style="text-align:left;"> Largest stocks $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:37:55 </td>
   <td style="text-align:left;"> $SPY Bitcoin finally decoupled from the stock market..not sure how I feel about that honestly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:37:27 </td>
   <td style="text-align:left;"> JPM $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:37:14 </td>
   <td style="text-align:left;"> $SPY bulls told me Ukraine was winning? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:37:02 </td>
   <td style="text-align:left;"> $SPY for tomorrow 👍🏼🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:36:56 </td>
   <td style="text-align:left;"> $SPY Your future depends on brandon giving a good speech.  Basically puts will be printing by Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:36:14 </td>
   <td style="text-align:left;"> $SPY quitting my job going Trading Full time, will I win sometimes, will I Learn ABSOLUTELY💪🏽📉📌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:36:02 </td>
   <td style="text-align:left;"> $SPY 🔥😵

I&amp;#39;m so upset. Board is dead. Bears evaporated after 3 days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:35:55 </td>
   <td style="text-align:left;"> $SPY Bulls buying the EOM pump... yup, priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:35:54 </td>
   <td style="text-align:left;"> $SPY pretty sure tmm will be green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:35:25 </td>
   <td style="text-align:left;"> $FB $NVDA $SPY  All that you need to know. Shorts haven&amp;#39;t covered a single share; Check it out below, highly recommend everyone to follow them:]]] profit.stocktradingchat.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:35:14 </td>
   <td style="text-align:left;"> $SPY Now for a bit of good news..

https://flipboard.com/video/newyorkpost/c563f5e175 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:33:57 </td>
   <td style="text-align:left;"> $SPY 15% inflation Putin better be smart with them bullets every magazine is thrilled prices. He didn’t think this thru all the way. Is there a male menopause? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:33:56 </td>
   <td style="text-align:left;"> $SPY top of the channel. Do we gap above resistance in the AM? My puts hope not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:33:27 </td>
   <td style="text-align:left;"> $SPY lol, the casino that is tracked with charts to give pseudo-intellectual satisfaction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:33:21 </td>
   <td style="text-align:left;"> $SPY I thought the market was crashing again!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:33:15 </td>
   <td style="text-align:left;"> $SPY can’t lose all your money in the stock market if you already lost all your money in the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:33:11 </td>
   <td style="text-align:left;"> $SPY $QQQ If nuclear war is the reason you bought puts, then you’re an idiot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:33:02 </td>
   <td style="text-align:left;"> $SPY Sanctions on @blancobull are not priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:32:55 </td>
   <td style="text-align:left;"> $SPY Who is going to ruin Joe&amp;#39;s STOU
XI or Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:32:41 </td>
   <td style="text-align:left;"> $SPY very bullish I see 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:32:22 </td>
   <td style="text-align:left;"> $SPY why is it headline news that Russia has 15 percent inflation now?  Thats current US inflation 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:32:14 </td>
   <td style="text-align:left;"> $SPY Jen psaki thanks Putin for unifying nato like thanking hitler for reducing world population. How woke people get away with this? Mind boggling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:32:11 </td>
   <td style="text-align:left;"> $SPY Putin going off-script </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:31:59 </td>
   <td style="text-align:left;"> $SPY This guy is in Ukraine and has a well explained video on what’s happening

https://www.youtube.com/watch?v=1vdiEABLFoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:31:52 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/pKcmNGvaDUs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:31:51 </td>
   <td style="text-align:left;"> $SPY  
 
&amp;quot;Mark this post&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:31:47 </td>
   <td style="text-align:left;"> $SPY  I’m convinced 99 percent of you lose money in here. The market is irrational. Adapt or get smoked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:31:41 </td>
   <td style="text-align:left;"> The large-cap benchmark has gained an average of 1.0% in the month of March with 60% of periods closing higher over the past two decades.  $STUDY $SPX $SPY $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:31:33 </td>
   <td style="text-align:left;"> $SPY stock analysis based on today&amp;#39;s closing price 

https://youtu.be/wQtjLPHZuyg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:31:11 </td>
   <td style="text-align:left;"> $SPY buy the genocide and world war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:31:02 </td>
   <td style="text-align:left;"> $SPY hmmmm fed money transfer thru bitty to Ukraine????? Maybe I&amp;#39;m hi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:31:01 </td>
   <td style="text-align:left;"> $SPY 

BREAKING: Pentagon Press Secretary says the US will not set up a no-fly zone in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:30:29 </td>
   <td style="text-align:left;"> $SPY so tou tell me
Russia didn’t think this thru all the way didn’t think ukraine would fight back now peace talk haha Putin is an imbecile he was mad at what exactly? If we joined we would have took over russia easily. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:30:22 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:30:10 </td>
   <td style="text-align:left;"> $SPY casino nuff said 😆 🤣 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:29:56 </td>
   <td style="text-align:left;"> $SPY me just eating corn priced in tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:29:51 </td>
   <td style="text-align:left;"> S&amp;amp;P 500 Index charts a rather indecisive doji candlestick just above support at 4280. http://www.equityclock.com/2022/02/28/stock-market-outlook-for-march-1-2022/ $SPX $SPY $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:29:40 </td>
   <td style="text-align:left;"> $SPY sleepy joe going to pump market tomorrow evening ... it’s all he has going for him if anything left that hasn’t been destroyed 😂... you can bet he will talk about spending !!!!   Oh yeah they don’t want to lose mid terms either.  So this is it !!!   Glt ☮️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:29:27 </td>
   <td style="text-align:left;"> $SPY my forehead is brighter than bulls future </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:29:22 </td>
   <td style="text-align:left;"> $SPY $QQQ is always bullish in the absence of bearish factors, more accurately according to the efficient market theory, in the absence of visible solutions for those bearish factors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:29:19 </td>
   <td style="text-align:left;"> $SPY 455-460 would complete Right Shoulder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:29:10 </td>
   <td style="text-align:left;"> $SPY tomorrow’s Econ events page 2 (and final page)

Ok, that’s it!  Good night all!

Hope ya made bank today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:29:05 </td>
   <td style="text-align:left;"> $SPY Biden said don’t fear nuclear war so he can buy his ticket to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:28:54 </td>
   <td style="text-align:left;"> $SPY just saw 3 red 1m candles on futures chart. Confident that was the fall of Kyiv being priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:28:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA if this happens which it WONT I’ll delete my account forever. j powell is not gonna say he wants to u wins the balance sheet lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:28:35 </td>
   <td style="text-align:left;"> $SPY 40 miles is priced in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:28:31 </td>
   <td style="text-align:left;"> $SPY Pence for Prez 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:28:19 </td>
   <td style="text-align:left;"> $SPY is nuclear war priced in? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:28:04 </td>
   <td style="text-align:left;"> $SPY 40miles is actually insane </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:27:42 </td>
   <td style="text-align:left;"> $SPY  Biden has come out to say that Americans should not fear a nuclear war in Ukraine. The very fact that he is making such a public statement is confirming that there is a risk. 
Remember the movie 2012  when the lead actor says :When they tell you not to panic, that&amp;#39;s when you run! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:27:24 </td>
   <td style="text-align:left;"> $SPY we are going to witness a genocide. 
They need help and fast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:27:07 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:27:03 </td>
   <td style="text-align:left;"> $QQQ $SPY ANY TWITTER HANDLERS THAT GIVE FREE TRADES THAT WIN? POST THEM HERE. TRYNA GAMBLE LETS GOOOOOOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:27:02 </td>
   <td style="text-align:left;"> $SPY looking at the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:26:35 </td>
   <td style="text-align:left;"> $SPY It’s crazy How trump was the “your fired” real estate mogul guy …Who ALMOST everyone somewhat admired or tolerated. 
        To a kraken in the political arena, shattering hopes and dreams of the blind/unwoke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:26:26 </td>
   <td style="text-align:left;"> $SPY $QQQ I WANT TO SEE 1929 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:26:20 </td>
   <td style="text-align:left;"> $SPY tomorrow’s Econ events page 1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:26:20 </td>
   <td style="text-align:left;"> $BTC.X $SPY this is based on very little, none the less, BTC to 200K+ in 12-14 months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:26:15 </td>
   <td style="text-align:left;"> $SPY I already swiped left on the Russian and ukraine war. Didn’t interest me tbh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:26:15 </td>
   <td style="text-align:left;"> $SPY Yo free my nog YoungWarren. @Stocktwits you a disgrace... AMEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:26:14 </td>
   <td style="text-align:left;"> $SPY   would you move to Montana bozeman in your 20s? Or adapt to changing times in the newly liberal poulated red states? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:25:39 </td>
   <td style="text-align:left;"> $SPY we all know exactly where this is going </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:25:32 </td>
   <td style="text-align:left;"> $QQQ $SPY Reports on Fox News on tv just now. Reports Russians used a vacuum bomb which is considered a war crime.  It’s the stronger bomb under nuclear. It vaporizes people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:25:26 </td>
   <td style="text-align:left;"> $SPY Mr Workman is rooting for the Ukraine people at this point.  He reads the Klitschko Brothers even join the fight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:25:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $NQ_F watch that downtrend. Another way to look at it. Short term inverse  head and shoulder. Like I said earlier, needs to break that 14475ish to get that move to the upside. Until then.. chop chop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:49 </td>
   <td style="text-align:left;"> $SPY. Tomorrow ... Hi midget, remember me? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:43 </td>
   <td style="text-align:left;"> $SPY Putin will be the main event at Nuremberg number 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:43 </td>
   <td style="text-align:left;"> $SPY did putin find wmd&amp;#39;s in Ukraine yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:41 </td>
   <td style="text-align:left;"> $SPY 

17 mile long Russian convoy en-route to the capitol… 

Sad to say - but Russia will own Ukraine in a week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:36 </td>
   <td style="text-align:left;"> $SPY looking at after hours movement and futures is honestly a top tier waste of time. You&amp;#39;ll never get these hours back, ladies and gents. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:33 </td>
   <td style="text-align:left;"> $SPY you fucking Bears are retarded , Jesus Christ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:22 </td>
   <td style="text-align:left;"> $SPY The next news to hit would be &amp;quot;talks fail&amp;quot; .... BTFD ... as next day it would read &amp;quot;Zelensky surrenders&amp;quot; $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:17 </td>
   <td style="text-align:left;"> $SPY Biden opens his mouth tomorrow night. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:17 </td>
   <td style="text-align:left;"> $SPY Pretty damn sad when 10y rates go down and we are red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:06 </td>
   <td style="text-align:left;"> $SPY No one asks, why are there 11 US biolabs on Russia’s doorstep?   

The US invaded and destroyed Iraq for no WMDs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:01 </td>
   <td style="text-align:left;"> $SPY may want to pay attention to this one.  I think they decided to hold, but not sure yet.  We’ll see tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:24:01 </td>
   <td style="text-align:left;"> $SPY https://youtube.com/shorts/plsFumUDfr4?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:45 </td>
   <td style="text-align:left;"> $SPY Down with globalist agenda in Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:45 </td>
   <td style="text-align:left;"> $ERUS $RSX $SPY US Satellite Image Company Maxar: Images Show Russian Military Convoy Near Kyiv Stretches Approximately 439 Miles with last truck just leaving Moscow Burger King now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:38 </td>
   <td style="text-align:left;"> $SPY 439 open is decent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:36 </td>
   <td style="text-align:left;"> $SPY I bet all these bears are noobs, I think all the bears of the past disappeared and stopped trading 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:29 </td>
   <td style="text-align:left;"> $SPY 
Bulls with so much hope </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:26 </td>
   <td style="text-align:left;"> $SPY make money not war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:24 </td>
   <td style="text-align:left;"> $SPY  we look primed for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:24 </td>
   <td style="text-align:left;"> $SPY we will price in the fall of Kyiv before the bears can even blink </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:10 </td>
   <td style="text-align:left;"> $SPY When the rally starts nobody will believe it. Then FOMO will commence when we’re close to all time highs. You could be smart and buy now or chase later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:06 </td>
   <td style="text-align:left;"> $SPY $QQQ welcome to the SCAM MARKET. Where we wallstreet love to screw bulls and bears of their hard earned money. 
We don&amp;#39;t care about you retail investors, we only care what&amp;#39;s good for us. GREED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:04 </td>
   <td style="text-align:left;"> $SPY why russia even attempt to have talks with ukraine while they march miles more troops in ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:23:02 </td>
   <td style="text-align:left;"> $SPY Weekly is looking less and less bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:22:56 </td>
   <td style="text-align:left;"> $SPY as bad as this sounds, Kyiv might be going down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:22:38 </td>
   <td style="text-align:left;"> $SPY Poland agrees to provide Ukraine weapons, peeps. Do you think peace is here ? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:22:28 </td>
   <td style="text-align:left;"> $SPY over under 930pm est March 2nd real full scale invasion, with city lvling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:22:22 </td>
   <td style="text-align:left;"> $SPY 40 mile long convoy to kyiv. Fuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:22:15 </td>
   <td style="text-align:left;"> $SPY https://www.scmp.com/news/china/military/article/3166690/chinese-navy-puts-fleets-through-combat-readiness-paces 
 
Bulls get ready for some kong fu style spanking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:22:12 </td>
   <td style="text-align:left;"> $SPY fk 40mile long Russian convoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:59 </td>
   <td style="text-align:left;"> $TSLA I like how when i got to $SPY mfs be arguing over if bears or bulls are gonna win but at $TSLA everyone is Bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:56 </td>
   <td style="text-align:left;"> $SPY futes be rippin like my fingernails growing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:54 </td>
   <td style="text-align:left;"> $SPY 

PMI tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA this is EXACTLY WHY we inverse Cramer another idiot take.
 https://stocktwits.com/Guntz/message/440086425 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:38 </td>
   <td style="text-align:left;"> $SPY China </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:32 </td>
   <td style="text-align:left;"> $SPY Russia is getting fucked by everybody. The old military ways of Putin just need to be left in the past with  his old Soviet Union days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:28 </td>
   <td style="text-align:left;"> $SPY DIE DIE YOU PIECE OF SHXT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:20 </td>
   <td style="text-align:left;"> Day Trading Watch List Video for March 1st: $SPY $ALF $OPAD $DWAC $SKYH   
 
Watch here: https://greatstockpix.com/march-1st-watch-list-video/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:18 </td>
   <td style="text-align:left;"> $SPY NO LEAD IS SAFE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:21:06 </td>
   <td style="text-align:left;"> $SPY so S&amp;amp;P 500 is at 436.63 at close, and the market now has completely forgot the whole thing we went through to price in rate hikes. So basically, jack squat is priced in. Meaning, we crash again here in 2 weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:20:59 </td>
   <td style="text-align:left;"> $SPY Futs be fuckn ripping like grass growing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:20:35 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:20:26 </td>
   <td style="text-align:left;"> $SPY if putin have a stocktwits account im curious what will it look like i wanna hang out with him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:20:18 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM today was a very good for the day bulls , I’m so happy . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:20:18 </td>
   <td style="text-align:left;"> $SPY China </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:20:11 </td>
   <td style="text-align:left;"> $SPY   
https://t.me/istorijaoruzija/37401 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:20:08 </td>
   <td style="text-align:left;"> $SPY MMs now hiring psychics to price in all future catalysts. Soon we’ll find the final value of the market and it will instantly correct there and never move again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:20:06 </td>
   <td style="text-align:left;"> $SPY chart - 1 month sneak peek </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:19:56 </td>
   <td style="text-align:left;"> $SPY $QQQ hope Putin doesn’t like Disney movies. Could be the last straw for that crazy asshole </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:19:48 </td>
   <td style="text-align:left;"> $SPY 🚨🚨BREAKING🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:19:46 </td>
   <td style="text-align:left;"> $SPY Hey rainbow bears, i recommend you guys cover and use whats left for lube lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:19:41 </td>
   <td style="text-align:left;"> $SPY Putin will not bow down and he&amp;#39;s not giving a chance to save face (not to justify) he will still surprise imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:19:40 </td>
   <td style="text-align:left;"> $SPY sheep gang wya </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:19:21 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:18:48 </td>
   <td style="text-align:left;"> $SPY Wtf is up with no foreign minorities allowed on the trains or busses Ukraine?  This really pisses me off huge if Putin was actually right about the Nazi crap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:18:39 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:18:26 </td>
   <td style="text-align:left;"> $SPY I want a limit up tonight 

Enough fkng around with these weak 2% rallies

I want ALL BEARS DEAD by SUNRISE !!!!

🐻😵🐻😵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:18:16 </td>
   <td style="text-align:left;"> $SPY another day of pain tomorrow or a pin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:18:15 </td>
   <td style="text-align:left;"> $SPY NWO is not a conspiracy theory. Pandemic was a catalyst to help make this happen. I believe WWIII is a deeper battle than what meets the eye.  Probably to see who will dominate and govern this new world. I don’t like where this is going🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:18:05 </td>
   <td style="text-align:left;"> $SPY hello stocktwit family. i know i mainly post memes and shitpost on here but seriously. it is about to occur. i just sold it all with what i know and pulled max from the bank. prepare yourself and your family. fill your gas tanks and get your water topped off, charge your batteries. too late for ammo. prepare yourself. god bless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:18:03 </td>
   <td style="text-align:left;"> $SPY NATO has clearly exposed who they truly are, and Putin has every cause to be suspicious of Europe.

https://youtu.be/flEM5TG-dZc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:49 </td>
   <td style="text-align:left;"> $SPY breaking down that $437.50 wall 💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:48 </td>
   <td style="text-align:left;"> $SPY WILL THE  FUEL PUMPS START TAKING BITCOIN 
HAVE SLOT WHERE YOU INSERT YOUR COIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:47 </td>
   <td style="text-align:left;"> $SPY China is gonna do it, be ready for pits really cheap once we sort of rally a bit more. Be on high alert. These are “event plays”, set yourself up for success!🏆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:46 </td>
   <td style="text-align:left;"> $SPY Been DCA all these 2% down days... Discounts are awesome </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:43 </td>
   <td style="text-align:left;"> Woa.. liquidation?!! !!! $RUSL 
$qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:29 </td>
   <td style="text-align:left;"> The U.S. is not setting up a no-fly zone in Ukraine - Kirby $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:22 </td>
   <td style="text-align:left;"> $SPY 

Yes war is inflationary event. 
Very much so. 
Just in case anyone did not know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:19 </td>
   <td style="text-align:left;"> $SPY Stop conjuring up a nuclear war. If this really takes place, and not with one but with hundreds of missiles at the same time, then we will all no longer have to worry about stocks... Negotiations must be put on the table on how Russia and NATO can live together in harmony. Of course, Putin should pay for the war, but even if it doesn&amp;#39;t end in a nuclear catastrophe, the conflict will continue to smolder and history will repeat itself over and over again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:06 </td>
   <td style="text-align:left;"> $SPY big booty bitches imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:17:02 </td>
   <td style="text-align:left;"> Russia is now a penny stock and Putin blew his account up boiiiiii 😆 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:16:57 </td>
   <td style="text-align:left;"> $SPY Futes rippin’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:16:39 </td>
   <td style="text-align:left;"> $SPY $Spdr S&amp;amp;P 500 Etf​  where in the usa to live with small town vibes but still sexy asf and not expensive?​ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:16:22 </td>
   <td style="text-align:left;"> $SPY going up Tmr up 3% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:16:15 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m wet ,but spy better not rally too hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:16:02 </td>
   <td style="text-align:left;"> $SPY $AMC $WKHS $TGT $NLST  
Traders&amp;#39; Guide For Tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:15:40 </td>
   <td style="text-align:left;"> $SPY petro -dollar about to be challenged. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:15:21 </td>
   <td style="text-align:left;"> $SPY $QQQ literally the first thing I agree with him on 
https://www.cnbc.com/2022/02/28/jim-cramer-says-russias-invasion-of-ukraine-could-put-more-pressure-on-fed-to-raise-interest-rates.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:15:15 </td>
   <td style="text-align:left;"> $SPY SURPRISE BTCH

😎😎📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:15:04 </td>
   <td style="text-align:left;"> $SPY Russian oligarchs should be thrown out, no oligarchy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:15:00 </td>
   <td style="text-align:left;"> $SPY let&amp;#39;s hold off on  this carpet bombing until tomorrow  night Est. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:14:55 </td>
   <td style="text-align:left;"> $SPY stuck up entitled Americans are so blinded by entertainment and fake news they can’t see the simple fact that Ukraine joining nato would = nukes on the Russian border. 

The closest US nukes are stationed in Germany, as the NATO countries closest to Russia are part of the NFT treaty. Ukraine is not. 

Just imagine the Russians trying to start a military alliance with Mexico or other countries in South America and putting nukes on our borders.

The hypocrisy is sickening. PUTIN is 100% in the right to take action, how and exactly what he’s doing may not be, but military action is justified. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:14:45 </td>
   <td style="text-align:left;"> Disney pauses theatrical releases in Russia, condemns invasion of Ukraine $DIS $DIA $SPY https://www.cnbc.com/2022/02/28/disney-pauses-theatrical-releases-in-russia-condemns-invasion-of-ukraine.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:14:36 </td>
   <td style="text-align:left;"> $SPY  where to move now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:14:34 </td>
   <td style="text-align:left;"> $SPY - futures must be green.  There aren’t 500 bears posting about stupid bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:14:26 </td>
   <td style="text-align:left;"> $SPY anything under 445 tmr is a shame to america empire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:14:15 </td>
   <td style="text-align:left;"> $MULN how is this technology not worth billions to $TSLA ?? $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:57 </td>
   <td style="text-align:left;"> $SPY all I want to see tomorrow is THIS !!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:51 </td>
   <td style="text-align:left;"> $SPY Nuclear war isn’t priced in lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:42 </td>
   <td style="text-align:left;"> $SPY 

Putin is not an idiot. 

He had to have known there would be repercussions. 

Something tells me this isn’t over. 

Don’t buy those calls yet, bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:40 </td>
   <td style="text-align:left;"> $SPY On a losing day I tell myself  
 
I have no faith in this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:39 </td>
   <td style="text-align:left;"> $SPY I rarely ever post political shit but I&amp;#39;ve been around a long time, and I can tell you with a straight face that if Canada or Mexico let another country bring in nukes on their land and pointed them at our country I would be very fucking pissed. Chew on that for a minute. Good night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:35 </td>
   <td style="text-align:left;"> $SPY Dude, you just know the Ghost of Kyiv and the Angel of Verdun are about to fuck face each other first chance they get. That should be the next movie, for sure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:30 </td>
   <td style="text-align:left;"> $SPY yeah SHOCKER that the S&amp;amp;P 500 goes UP !!!!

🤡🤡📈🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:24 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures higher, looks like investors are gaining confidence that Putin isn&amp;#39;t crazy enough to launch nuclear wars against the US and Europe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:19 </td>
   <td style="text-align:left;"> $SPY 438.20 that&amp;#39;s the magic AH number... not happening though.  🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:14 </td>
   <td style="text-align:left;"> $SPY 7:08pm diaperman (lost $5k 2022): shits about to tank hard fam 

7:08 pm retardobull (lost $7k 2022): lmao suck it bears 

7:08 pm optionsgod (lost $3.5k 2022): rising wedge pattern on the chart. act accordingly 

7:07pm thebearboi (lost $13k 2022): fucking fire powell

7:07pm guccitrades (lost $6k 2022): which one of you retards voted for this clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:12 </td>
   <td style="text-align:left;"> $SPY so sick of these bears

All low IQ plebs who dont know ANYTHING

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:11 </td>
   <td style="text-align:left;"> $SPY this is not over - Ukraine gonna get rekt tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:01 </td>
   <td style="text-align:left;"> $SPY …Buy American Joe…Ban Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:13:00 </td>
   <td style="text-align:left;"> $DWAC $spy  some people would look at this as a white supremacist movement.. others might say interesting they&amp;#39;re holding a historical reenactment and combining two ideologies.. since it&amp;#39;s only one picture I&amp;#39;m going to look for a little bit more information before I come to an absolute judgment even if my Spidey senses are going off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:12:54 </td>
   <td style="text-align:left;"> $SPY the call gods will be out tomorrow . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:12:48 </td>
   <td style="text-align:left;"> $SPY i guess youll be paying 6$ in btc for a gallon of gas come july 4th. Adults in the room have this under control. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:12:40 </td>
   <td style="text-align:left;"> $SPY Sucker bulls about to get smashed as VIX accumulates, but not before a fake-out to fool the bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:12:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA the bears should not be happy at ALL today, this was such a disappointing day for them and then tmr should be even worse as I see tmr being 2% up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:12:38 </td>
   <td style="text-align:left;"> $SPY FUTURES are going to be super boring tonight - TRUST ME for bulls and bears! By design of MM etc.. They&amp;#39;re trying to survive this prop into Wednesday earliest..  📊✍️  
 
... Take the night off,  we all had an  eventful weekend..😮‍💨🙃😁  
 
Go find 💦👀🤣🙋‍♂️ $ZM $SDC $KSS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:12:35 </td>
   <td style="text-align:left;"> $SPY short the ruble to the depths of earth. USSR should dissolve </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:12:33 </td>
   <td style="text-align:left;"> $SPY VERY VERY BULLISH

I THINK BEARS R DUMB

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:12:17 </td>
   <td style="text-align:left;"> $SPY 

These Ukrainian officials are clearly members of KLAUS SCHWAB; they started this conflict to impose a globalist agenda, which Russia refuses to accept... Zelensky is a snake.

https://mobile.twitter.com/thechrisbuskirk/status/1498329010878615555?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1498329010878615555%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2Fbreaking-news%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:12:02 </td>
   <td style="text-align:left;"> $SPY Bears are the type of people that drive under the speed limit in the left lane and then wonder why everyone is flipping them off and brandishing weapons. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:56 </td>
   <td style="text-align:left;"> $SPY lots of propaganda, I refuse to believe anything on the news or any of the people who brought the US into the middle east </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:54 </td>
   <td style="text-align:left;"> $SPY All that today to basically end up even. Classic!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:53 </td>
   <td style="text-align:left;"> $SPY 

Where is one of my favorite bulls, @Potato_sb ?

Where are you, Mr. Potato?
Why can’t I find you? 
Why have you gone away? 🥺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:53 </td>
   <td style="text-align:left;"> $ERUS $RSX $SPY US Satellite Image Company Maxar: Images Show Russian Military Convoy Near Kyiv Stretches Approximately 40 Miles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:50 </td>
   <td style="text-align:left;"> $SPY We are in a phase of sell every pump till Fed makes their intention known through rate hikes. Possibility of downward pressure still high 🎢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:32 </td>
   <td style="text-align:left;"> MAXAR: NEW IMAGES REVEAL A MILITARY CONVOY SEEN NORTH OF KYIV IS MUCH LONGER THAN THE 17 MILES PREVIOUSLY REPORTED $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:31 </td>
   <td style="text-align:left;"> $SPY rode snowmobiles to old faithful today…on my 40th…🤠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:13 </td>
   <td style="text-align:left;"> $SPY bears lol your puny war is no match for the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:07 </td>
   <td style="text-align:left;"> $SPY Today the market showed me I cant be correct 9 out of 10 times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:11:01 </td>
   <td style="text-align:left;"> $SPY 

If enough sanctions are put on Russia and over time all their people start suffering, they will be stronger than ever and rally against the corrupt Nato. 

Wouldn&amp;#39;t be surprised if they start launching nukes not even as last resort. Even if they were to surrender now, their stock market is down 73%, roubles devalued by 48%, sanctions still on, no banking or money transfer available due to banning of swift payments, no money, and possibly have to pay for restitution against Ukraine. Why would they surrender or stop now? It&amp;#39;s too late </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:51 </td>
   <td style="text-align:left;"> $SPY ….shame on Biden for not banning Russian oil and all Russian banks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:49 </td>
   <td style="text-align:left;"> $SPY $446 or $450 before the next reversal that’s the question… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:44 </td>
   <td style="text-align:left;"> $SPY Petroleum + Soap Jelly = Freedom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:43 </td>
   <td style="text-align:left;"> $SPY How likely is it that Powell won’t raise rates in march cause of Ukraine? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:37 </td>
   <td style="text-align:left;"> $SPY don’t worry bulls. Literally anything bad that can happen is either priced in or bullish as fuck 🚀 an asteroid could hit earth and the market would rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:33 </td>
   <td style="text-align:left;"> Wow Russia only worth 10 dollars 😆 $SPY  $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:31 </td>
   <td style="text-align:left;"> $SPY I knew there would be chop with Bidens last speech. Let&amp;#39;s wait a month guys 😭 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:26 </td>
   <td style="text-align:left;"> $SPY I lost all my money i had in bank account… can only withdraw 20 rubles out of my life savings. How will I buy dip ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:16 </td>
   <td style="text-align:left;"> $SPY Putin  does  something stupid tonight and we wake up under 400. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:10:04 </td>
   <td style="text-align:left;"> $SPY short the Russian Ruble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:09:57 </td>
   <td style="text-align:left;"> $SPY remember when futures were down -2.7% last night? Are people who trade futures just those so bad at normal hours they decided to be even more wrong after hours and lose even more money? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:09:37 </td>
   <td style="text-align:left;"> $SPY es trying to break the resistance early </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:09:08 </td>
   <td style="text-align:left;"> $SPY So QE over now or nah? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:53 </td>
   <td style="text-align:left;"> $SPY people are really bullish here. It&amp;#39;s sick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:53 </td>
   <td style="text-align:left;"> $SPY $BTC.X everyone getting greedy and Powell hasn’t even moved yet. 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:52 </td>
   <td style="text-align:left;"> $SPY reversal confirmed..$500 by next month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:49 </td>
   <td style="text-align:left;"> $SPY Members with gains!🤑🎉
Free discord in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:46 </td>
   <td style="text-align:left;"> $SPY it is staggering to me how  much of risk market is just shrugging off right now. Ukraine, inflation, nuke threat, russian currency, mega caps exiting out of Russia with billions in losses. who is going to service all the debt we already had plus all the new one.  
 
Every Western country and some east as well are pitching in for Ukraine with arms and $ support. which is great. but how long can you stay on sidelines just sending in help before NATO actually gets involved?  
 
Outbreak of covid mkt did same thing - refused to recognize the changes in underlying structure caused by macro events. Before all helx broke loose. This time I see same thing happening likely. Unprecedented times for sure. Stay safe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:32 </td>
   <td style="text-align:left;"> $SPY selling my calls at the 945 pump tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:29 </td>
   <td style="text-align:left;"> US . $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:28 </td>
   <td style="text-align:left;"> $SPY time for Russia to finish Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:23 </td>
   <td style="text-align:left;"> $BTC.X $SPY 

Who keep their money in bank in Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:20 </td>
   <td style="text-align:left;"> $SPY i thought u gonna help me buy very low what happened bears 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:10 </td>
   <td style="text-align:left;"> $SPY am i bullish or bearish or neither or both? i cant even tell anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:09 </td>
   <td style="text-align:left;"> $SPY spy 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:08:08 </td>
   <td style="text-align:left;"> $SPY #dramaqueens  :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:07:58 </td>
   <td style="text-align:left;"> $SPY If we hit $450 resistance tomorrow as expected that would be a 10% run from the low in just 4 sessions. And then the fed is expected to speak where everyone expects them to be dovish, after a 10% run in 4 sessions. And they will either hold back the first hike or go with a small increase of 0.25% because of the effect the invasion on our economy, which will likely be a 10% run in 4 sessions. I think the market just dropped too fast so we’re rallying back up to resistance where hopefully, for the sake of lowering inflation, the market will drop back down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:07:49 </td>
   <td style="text-align:left;"> $SPY Ukraine is the tipping point for the NEW WORLD ORDER out of the mouth of Ukrainian MP … 

https://mobile.twitter.com/thechrisbuskirk/status/1498329010878615555?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1498329010878615555%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2Fbreaking-news%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:07:47 </td>
   <td style="text-align:left;"> $SPY give me 10x tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:07:43 </td>
   <td style="text-align:left;"> $SPY I have been a bull all through last week, but now I am getting worried about this Russian war, Putin is  being pushed into corner - Zelensky refuses to surrender, World arming Ukraine more... This might bring out some deperate moves from Putin which is not good.... hope they resolve it through talks... $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:07:25 </td>
   <td style="text-align:left;"> $SPY imagine hearing kyiv for the first time a week ago and think it will have a global impact ,  by the way, russians are smart . You think they are stupid ? Lol they obviously know what theyre doing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:07:08 </td>
   <td style="text-align:left;"> $SPY There are many Bullish scenarios here. I think Putin overplayed his hand. His days could be numbered.  The world is getting tired of wars and destruction.  This could set China back too. If things played out quickly we could be looking at 70 buck oil. 5300 SPY
75k $BTC.X and .75 raise by the Federal reserve with a dovish tone. November 2022 will be a Republican landslide and that&amp;#39;s bullish too. $DIA $QQQ $GLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:06:45 </td>
   <td style="text-align:left;"> $SPY Putin Sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:06:38 </td>
   <td style="text-align:left;"> $SPY  
 
$JDST pretty swinger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:06:33 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $AMD 

Does anyone know the Ticker for the inverse ETF for Cramer? 

Can’t find it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:06:24 </td>
   <td style="text-align:left;"> $SPY follow my pain sofi calls and lcid puts and spy calls by the fucin busload </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:06:12 </td>
   <td style="text-align:left;"> $SPY Looks like the run into FOMC and dump after scenario is playing out. The indices haven’t held a 4 day run since October and still barely hold any gains intraday now. If any are made it’s in pre market or after hours or after a huge sell off and a short covering rally happens or a quick reversal that doesn’t end up lasting either, none of what I mentioned are signs of a “healthy uptrend”. At some point the market will reverse back into an uptrend, who knows when but until the price action confirms it I’d be cautious calling for ATH just because of a few green days… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:06:10 </td>
   <td style="text-align:left;"> $SPY my trading plan for the next 6 months: don’t be tempted to sell covered calls until the vix is below 18 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:06:03 </td>
   <td style="text-align:left;"> $SPY The ruble went to rubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:05:57 </td>
   <td style="text-align:left;"> $SPY What about the invasion on our southern border this past year ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:05:50 </td>
   <td style="text-align:left;"> $SPY I do find it a bit ironic that bulls say bears are the ones hoping for war and simultaneously saying to buy the invasion. I&amp;#39;m just sitting over here reading economic data in droves and biding my time.  Believe me, I&amp;#39;m going to BTFD, too.  I just don&amp;#39;t think it&amp;#39;s here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:05:48 </td>
   <td style="text-align:left;"> $SPY $BTC.X 

https://www.google.com/amp/s/nypost.com/2022/02/28/bitcoin-surges-9-3-over-demand-from-russians-and-ukrainians/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:05:13 </td>
   <td style="text-align:left;"> $SPY Downtrend is on hold for now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:05:10 </td>
   <td style="text-align:left;"> $SPY futes ripping bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:04:45 </td>
   <td style="text-align:left;"> $SPY $200 a barrel   are we there yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:04:43 </td>
   <td style="text-align:left;"> $SPY alien invasion imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:04:25 </td>
   <td style="text-align:left;"> $SPY Kiev is going to fall tomorrow a wall 15 miles wide if tanks moving forward tonight. Not good. But let’s buy stocks. Guess we forgot about inflation covid and the boarder. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:04:21 </td>
   <td style="text-align:left;"> $SPY Ukraine is a trap for new world order and Ukraine is in on it $DWAC 

https://mobile.twitter.com/LeilaniDowding/status/1498221108163719168?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1498221108163719168%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2Fbreaking-news%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:04:20 </td>
   <td style="text-align:left;"> $SPY this is what I’m thinking. 

Keep this diagram aMe be amazed in two weeks!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:04:08 </td>
   <td style="text-align:left;"> $SPY last year was &amp;quot;transitory&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:03:55 </td>
   <td style="text-align:left;"> $SPY 2022 word of the year: priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:03:50 </td>
   <td style="text-align:left;"> $SPY Doesn’t matter the pump at close, tomorrow Biden will bring it back down 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:03:42 </td>
   <td style="text-align:left;"> $SPY Church of the Flying Spaghetti Monster priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:03:39 </td>
   <td style="text-align:left;"> $SPY World leaders desperately want people to care about Ukraine…. Their country is irrelevant, not worth a world war over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:03:32 </td>
   <td style="text-align:left;"> $SPY Priced in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:03:31 </td>
   <td style="text-align:left;"> $SQQQ I didn&amp;#39;t realize how much was priced in -

We&amp;#39;ve got 7% inflation  - priced in
Reduction in corporate profits due to inflation - IN
War and occupation of Ukraine - priced in
FED balance sheet reduction - priced in
$120 oil - priced in
Average PE of 20% - priced in

It&amp;#39;s amazing how efficient this market has been, especially since Wednesday past week 🤷‍♂️🤦‍♂️

$QQQ $TQQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:03:02 </td>
   <td style="text-align:left;"> $SPY 20% bitty gains bet? By 3am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:02:49 </td>
   <td style="text-align:left;"> $SPY honestly, the Ghost of Kyiv is more real than this stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:02:40 </td>
   <td style="text-align:left;"> $SPY 2% green tmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:02:40 </td>
   <td style="text-align:left;"> $SPY Once Brandon&amp;#39;s state of the union address is over, maybe they will stop propping up this fake market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:02:28 </td>
   <td style="text-align:left;"> $SPY Bill Hwang did nothing wrong... change my mind </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:02:21 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/paulmcleary/status/1498437405610852353?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1498437405610852353%7Ctwgr%5E%7Ctwcon%5Es1_c10&amp;amp;ref_url=https%3A%2F%2Fwww.redditmedia.com%2Fmediaembed%2Fliveupdate%2F18hnzysb1elcs%2FLiveUpdate_19bdecfe-98f2-11ec-b40b-c6e85d6a3567%2F0  
 
Ukrainian pilots arrive in Poland to pick up used fighter aircraft. War is just going to get worse when Russia gets big mad after it finds out, SPY 420 blaze it soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:02:12 </td>
   <td style="text-align:left;"> $SPY btc up like 15%. Holds thru the night nasdaq may post a +3% day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:01:52 </td>
   <td style="text-align:left;"> $SPY people belong in a mental institution if they actually think a nuclear bomb will be used against an enemy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:01:45 </td>
   <td style="text-align:left;"> $SPY damn Putin margin called moo :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:01:37 </td>
   <td style="text-align:left;"> $SPY any rationale Republican when they realize the rally folk to their left and right are mentally ill, Putin-apologists. 

Still plenty of time to go unaffiliated before the next election! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:01:16 </td>
   <td style="text-align:left;"> $PLTR $SPY $NIO $TSLA 

Sheesh. Just check for the first time lol. My account is down 24% in the past 3 months. Been brutal. Hopefully we turn around soon cause I’ve been loading these dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:01:07 </td>
   <td style="text-align:left;"> $SPY  Ghost of Kyiv bought the D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:01:03 </td>
   <td style="text-align:left;"> $SPY can someone teach me how to stocks in this bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:00:58 </td>
   <td style="text-align:left;"> $SPY the beauty of the coin flip. You think bull or bear know where price going ? No , they dont otherwise theyd have unlimited money . You see the superbowl bets for coinflip both sides -115. That way you can still short term win, but long term the house always wins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:00:53 </td>
   <td style="text-align:left;"> $SPY nazdik wants to run on the futes dang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:00:26 </td>
   <td style="text-align:left;"> $SPY ….Stop being a sissy Biden any block russian oil and banking…Stop Putin Joe. Quit giving our lunch money to the bully Joe…stop US money to Russia Joe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:00:19 </td>
   <td style="text-align:left;"> $SPY Here&amp;#39;s what we have to look forward to in March.    
I can&amp;#39;t see how any reversal of the trend can change until the Russian War + Sanctions has been realized and all these FED meetings, reports and new data is released.  
  
🔴State of the Union by Joe Biden on March 1, 2022  
  
🔴Federal Reserve chief Jerome Powell will testify before Congress on March 2 and 3 in what are likely to be his final public remarks on monetary policy before the U.S. central bank begins raising interest rates to fight decades-high inflation.   
   
🔴The Consumer Price Index for February 2022 is scheduled to be released on Thursday, March 10, 2022 at 8:30 a.m.   
   
🔴 FOMC Meeting. Two-day meeting, March 15-16 
 
Highly Volatile and Unstable. 
FEDs going to stop spending and start raising interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:00:01 </td>
   <td style="text-align:left;"> $SPY  When u find a milf whos good at stocks and hits you up regularly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 08:00:00 </td>
   <td style="text-align:left;"> $SPY most likely we have one more Green Day coming followed by a dump on Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:59:59 </td>
   <td style="text-align:left;"> $SPY $ES_F if gold &amp;amp; oil turn red tonight we can see big rippy tonight in futures trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:59:57 </td>
   <td style="text-align:left;"> $SPY Can we send Trump to Russia permanently so he can live with his brother Vlad? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:59:53 </td>
   <td style="text-align:left;"> $SPY fake moral boosting stories to being instilled in poor peoples hearts to persuade  Kiev residents to volunteer  them selves as HUMAN SHIELDS  for ZELENSKY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:59:51 </td>
   <td style="text-align:left;"> $SPY $QQQ  
Russian bank Sberbank is raising mortgage rates on homes (both finished and under construction) from 7.5% to 18.6% 
 
Infilation  or war affect not sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:59:51 </td>
   <td style="text-align:left;"> $SPY $TSLA 
Russia&amp;#39;s nuclear forces put on &amp;#39;enhanced combat duty&amp;#39; - as peace talks end on Belarus border

https://news.sky.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:59:48 </td>
   <td style="text-align:left;"> $SPY Whats up with these two red monthly candles? Are we going back to 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:59:35 </td>
   <td style="text-align:left;"> $SPY Tom Lee never will give up on his Bullishness.  HE was right a lot last year when market was bullish, but these first few months of 2022 he has been wrong.  https://www.youtube.com/watch?v=pGTLjx3bYW4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:58:48 </td>
   <td style="text-align:left;"> $SPY I haven’t seen moo 
What happened to him 
Did he missed the Russian Ukraine rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:58:28 </td>
   <td style="text-align:left;"> $SPY 🔥😏

Futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:58:28 </td>
   <td style="text-align:left;"> $SPY $UPRO Fundstrat’s Tom Lee: Market may have reached a bottom for the first half of 2022 https://www.cnbc.com/2022/02/28/fundstrats-tom-lee-market-may-have-hit-bottom-for-first-half-of-2022.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:58:11 </td>
   <td style="text-align:left;"> $SPY tomorrow should be nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-01 07:57:51 </td>
   <td style="text-align:left;"> $SPY spy looks like its forming a triple top. is at a very important retrace level, hammer candle with long tail formed on 4 hr and everyone is buying the dip and selling the rip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:42:29 </td>
   <td style="text-align:left;"> $SPY Closed the month down 3.17% bringing the decline to 8.23% on the year. This is the first time that the $SPY dropped in consecutive months since September-October of 2020. 
 
$QQQ $AAPL $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:40:33 </td>
   <td style="text-align:left;"> $QQQ this volatility we are seeing is for pros. Newer traders don’t get your hands burnt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:40:27 </td>
   <td style="text-align:left;"> $QQQ bears rn… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:39:17 </td>
   <td style="text-align:left;"> $SPY $QQQ What the USA needs right now is a good spanking and to show them the world isn&amp;#39;t afraid of them anymore. 
You&amp;#39;ve got clowns running the show! 
A good war is what they need...Send theses young punks that don&amp;#39;t work and sit on their ass all the long playing video games and smoke weed. Let them know what it feels like to not be spoon fed by mom &amp;amp; dad. Degenerates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:38:19 </td>
   <td style="text-align:left;"> $QQQ you can&amp;#39;t just print money forever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:34:36 </td>
   <td style="text-align:left;"> $QQQ how frustrated will you be if this goes up something like 17 of the next 19 trading days?  will you be OK? 
 
not saying it will or it won&amp;#39;t (i honestly don&amp;#39;t care) but many of you might night be able to handle all the possible outcomes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:33:33 </td>
   <td style="text-align:left;"> $QQQ Cramer says it’s time to worry, so accordingly this is going to pump like a motherfucker tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:33:11 </td>
   <td style="text-align:left;"> $SPY $QQQ If nuclear war is the reason you bought puts, then you’re an idiot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:30:58 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on closing price 

https://youtu.be/Qhbfk6gGyeM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:29:22 </td>
   <td style="text-align:left;"> $SPY $QQQ is always bullish in the absence of bearish factors, more accurately according to the efficient market theory, in the absence of visible solutions for those bearish factors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:28:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA if this happens which it WONT I’ll delete my account forever. j powell is not gonna say he wants to u wins the balance sheet lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:27:03 </td>
   <td style="text-align:left;"> $QQQ $SPY ANY TWITTER HANDLERS THAT GIVE FREE TRADES THAT WIN? POST THEM HERE. TRYNA GAMBLE LETS GOOOOOOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:26:26 </td>
   <td style="text-align:left;"> $SPY $QQQ I WANT TO SEE 1929 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:26:23 </td>
   <td style="text-align:left;"> $GOOGL $QQQ $ROKU All that you need to know.... Shorts haven&amp;#39;t covered a single share:- Check it out below 
~~~~~~~~~ 🚀 discord.io/7GPFADBFK5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:25:32 </td>
   <td style="text-align:left;"> $QQQ $SPY Reports on Fox News on tv just now. Reports Russians used a vacuum bomb which is considered a war crime.  It’s the stronger bomb under nuclear. It vaporizes people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:25:17 </td>
   <td style="text-align:left;"> $AMC $QQQ $DOGE-X  All that you need to know. Shorts haven&amp;#39;t covered a single share; Check it out below, highly recommend everyone to follow them:]] profit.stocktradingchat.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:25:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $NQ_F watch that downtrend. Another way to look at it. Short term inverse  head and shoulder. Like I said earlier, needs to break that 14475ish to get that move to the upside. Until then.. chop chop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:24:13 </td>
   <td style="text-align:left;"> $WKHS $AMC $QQQ Real price will come out soon, Follow price targets,,....🚀 fastcash.totalh.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:23:17 </td>
   <td style="text-align:left;"> $QQQ think of it like this.  imagine you trade at 20x earnings.  then i tell you because of a war that there will be no profits whatsoever for an entire year but things will return to normal next year.  it doesn&amp;#39;t mean you go to zero.  it just means you trade at 20x next year&amp;#39;s earnings.  maybe you deserve to trade at 18x next year&amp;#39;s earnings due to war risk.  maybe you deserver to trade at 22x next year&amp;#39;s earnings because things will be better after the war. 
 
now you know why you are just straight gambling regardless of what you think happens in the short term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:23:06 </td>
   <td style="text-align:left;"> $SPY $QQQ welcome to the SCAM MARKET. Where we wallstreet love to screw bulls and bears of their hard earned money. 
We don&amp;#39;t care about you retail investors, we only care what&amp;#39;s good for us. GREED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:21:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA this is EXACTLY WHY we inverse Cramer another idiot take.
 https://stocktwits.com/Guntz/message/440086425 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:21:10 </td>
   <td style="text-align:left;"> $QQQ 
📈📚
Option trades, Monday recap 2/28 🎯📈

QQQ 340P +22%
QQQ 347C +82%
QQQ 345P +153%
QQQ 342P +13%
QQQ 344C -35%

Tweet speaks for itself 🤷🏾‍♂️ don’t miss out on the next free alert!!!
💰💸

https://twitter.com/q_alerts/status/1498431545513816069?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:20:58 </td>
   <td style="text-align:left;"> $QQQ You people think this is bad...  Imagine what it will be like when China invades Taiwan.  Then imagine how much worse it will be once we&amp;#39;re pulled into war on 2 or 3 fronts officially starting WWIII.  Then if you can imagine Russia and China pull out of the Petro dollar system.  Then as if all that isn&amp;#39;t bad enough.  Imagine the limited use of thermo nuclear weapons somewhere in the world.  And to top it off, we have 3 more years of Biden.  And right in line behind him is Kamala and Nancy Pelosi.  If you&amp;#39;re putting money into anything right now, ask yourself why. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:20:36 </td>
   <td style="text-align:left;"> Wall Street open sends Bitcoin to $40K as latest BTC price surge passes 6% $BTC.X $QQQ $DJIA $VIX $SQQQ https://www.billionaireclubcollc.com/wall-street-open-sends-bitcoin-to-40k-as-latest-btc-price-surge-passes-6/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:20:18 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM today was a very good for the day bulls , I’m so happy . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:19:56 </td>
   <td style="text-align:left;"> $SPY $QQQ hope Putin doesn’t like Disney movies. Could be the last straw for that crazy asshole </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:17:43 </td>
   <td style="text-align:left;"> Woa.. liquidation?!! !!! $RUSL 
$qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:17:29 </td>
   <td style="text-align:left;"> The U.S. is not setting up a no-fly zone in Ukraine - Kirby $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:15:21 </td>
   <td style="text-align:left;"> $SPY $QQQ literally the first thing I agree with him on 
https://www.cnbc.com/2022/02/28/jim-cramer-says-russias-invasion-of-ukraine-could-put-more-pressure-on-fed-to-raise-interest-rates.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:15:13 </td>
   <td style="text-align:left;"> $QQQ $NQ_F Still has some work to do but CCI and OBV are looking constructive. I expect a little more sideways block and tackle.  First neckline broken(14030) , needs to break the second neckline (14676). Plenty of resistances to work through. I continue to DCA in, but mind the Fed meeting in March. It will likely be a catalyst. For me, a really bad scenario is priced in. If they do less than 50 bips, we could see violent upside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:15:02 </td>
   <td style="text-align:left;"> $QQQ The entire market is fucked... and I have news for both all of you pontificating expert bulls, and all of you pontificating expert bears (myself included)... you are all fucked... because these corrupt, unpredictable markets, take no prisoners... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:14:42 </td>
   <td style="text-align:left;"> $QQQ crashes don’t happen happen all at once, they happen in slow motion. This could climb all the way back up and back down over the next few months… puts and calls destroyed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:14:32 </td>
   <td style="text-align:left;"> $QQQ futures are green early? Guaranteed to be red at open 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:13:24 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures higher, looks like investors are gaining confidence that Putin isn&amp;#39;t crazy enough to launch nuclear wars against the US and Europe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:12:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA the bears should not be happy at ALL today, this was such a disappointing day for them and then tmr should be even worse as I see tmr being 2% up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:11:32 </td>
   <td style="text-align:left;"> MAXAR: NEW IMAGES REVEAL A MILITARY CONVOY SEEN NORTH OF KYIV IS MUCH LONGER THAN THE 17 MILES PREVIOUSLY REPORTED $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:07:08 </td>
   <td style="text-align:left;"> $SPY There are many Bullish scenarios here. I think Putin overplayed his hand. His days could be numbered.  The world is getting tired of wars and destruction.  This could set China back too. If things played out quickly we could be looking at 70 buck oil. 5300 SPY
75k $BTC.X and .75 raise by the Federal reserve with a dovish tone. November 2022 will be a Republican landslide and that&amp;#39;s bullish too. $DIA $QQQ $GLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:06:33 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $AMD 

Does anyone know the Ticker for the inverse ETF for Cramer? 

Can’t find it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:03:44 </td>
   <td style="text-align:left;"> $QQQ If the AH shit keeps going, we bout to rocket tomorrow then dump wed once talks go... imo.. but who knows this shits been bipolar lately lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 08:03:31 </td>
   <td style="text-align:left;"> $SQQQ I didn&amp;#39;t realize how much was priced in -

We&amp;#39;ve got 7% inflation  - priced in
Reduction in corporate profits due to inflation - IN
War and occupation of Ukraine - priced in
FED balance sheet reduction - priced in
$120 oil - priced in
Average PE of 20% - priced in

It&amp;#39;s amazing how efficient this market has been, especially since Wednesday past week 🤷‍♂️🤦‍♂️

$QQQ $TQQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:59:51 </td>
   <td style="text-align:left;"> $SPY $QQQ  
Russian bank Sberbank is raising mortgage rates on homes (both finished and under construction) from 7.5% to 18.6% 
 
Infilation  or war affect not sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:58:16 </td>
   <td style="text-align:left;"> $QQQ bounce off that low 340 to shake some ppl out before filling that gap at 360+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:57:50 </td>
   <td style="text-align:left;"> Stocks Drop On February 28 But The Real Risk Doesn&amp;#39;t Come Until Wednesday $C $QQQ $TIP $RINF $SPX $SQ https://talkmarkets.com/content/etfs/stocks-drop-on-february-28-but-the-real-risk-doesnt-come-until-wednesday?post=346467 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:56:42 </td>
   <td style="text-align:left;"> $DJIA bullish!!! $NCLH yup!! Bull market switching soon. Fomo incoming. $SPY $QQQ let&amp;#39;s goooo!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:56:36 </td>
   <td style="text-align:left;"> $qqq Trying to ANALyze daily price action thru with daily 🐑 news!!  It’s For bums!   N they getting it eventually!   🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:56:32 </td>
   <td style="text-align:left;"> $QQQ if I wanted to go short on consumer price index and expect weak consumption, what type of trade strategy should I put on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:55:12 </td>
   <td style="text-align:left;"> $QQQ 
📆💸
Option trades, Monday recap 2/28 🎯📈

QQQ 340P +22%
QQQ 347C +82%
QQQ 345P +153%
QQQ 342P +13%
QQQ 344C -35%

Tweet speaks for itself 🤷🏾‍♂️ don’t miss out on the next free alert!!!
💰💸

https://twitter.com/q_alerts/status/1498431545513816069?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:54:54 </td>
   <td style="text-align:left;"> $SPY $QQQ anyone here supports Putin? Just curious. No judgment zone. Safe place. Just curious to know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:54:01 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Where’s my bear gang at? 😢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:53:52 </td>
   <td style="text-align:left;"> $SPY $QQQ 

How’s futes doing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:53:34 </td>
   <td style="text-align:left;"> $QQQ VIX down 10% = markets up. VIX UP 10%? Markets up Hahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:52:17 </td>
   <td style="text-align:left;"> $QQQ  probably will go to 370-380 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:51:07 </td>
   <td style="text-align:left;"> A free-for-all but no crippling cyberattacks in Ukraine war $SPY $QQQ $DJIA $VIX $SQQQ  https://www.billionaireclubcollc.com/a-free-for-all-but-no-crippling-cyberattacks-in-ukraine-war/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:49:06 </td>
   <td style="text-align:left;"> $QQQ Today wasnt a head and shoulders, it was an ABC Pattern that is about to boot fook bears for a few days...impulsive moves on the horizon bulls...360...PT. Ukraine government are Nazi lovers! Do your research! Putin wants to denazify them, wake up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:48:17 </td>
   <td style="text-align:left;"> $QQQ Any upside will give away to the downside. Forgetting the nutty Russian, J Powell is testifying Wednesday and Thursday

Talk of two 50 bp hikes, March and June will sink the markets. Look for Putin to have a coordinated attack on Ukraine on Thursday

Putin bought puts expiring 3/4 💵💵💵💵🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:46:34 </td>
   <td style="text-align:left;"> $QQQ 

Bulls trying ever so hard not to have death cross on daily chart!!! Lol 😂 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:46:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN BING BONG 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:44:47 </td>
   <td style="text-align:left;"> Market seems does opposite of overnight futures .. last night huge red to green close nasdaq ..  
so if you bullish you want red futures over night otherwise tomorrow would be red day :) 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:43:41 </td>
   <td style="text-align:left;"> Here is a snippet of the analysis #ICFAM got this morning. We have been buying these dips and getting paid very nicely. Love the volatility.  
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:43:20 </td>
   <td style="text-align:left;"> $QQQ FIAT PONZI MARKET STRONG! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:41:40 </td>
   <td style="text-align:left;"> $QQQ do you think the down overnight, up in market hours pattern will occur again tonight/tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:40:36 </td>
   <td style="text-align:left;"> $SPY $QQQ lol I feel like the big boys secured puts profit and now leaving the leftover puts again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:40:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN tmw breakout? 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:39:13 </td>
   <td style="text-align:left;"> Stock futures are steady ahead of first trading day of March, Russia-Ukraine conflict in focus

$SPX $DJIA $QQQ

https://www.cnbc.com/2022/02/28/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:37:08 </td>
   <td style="text-align:left;"> $QQQ lol vix isn’t even down but this is? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:36:34 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ

Where the Tesla/Elon haters at?

Thought it was a PR stunt or elon wouldnt deliver?

It took only a matter of days! 

Stop complaining when others are trying to do something good. Even if it takes longer than expected. 

I dont see yall doing shit but complain and hate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:35:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $BTC.x  
 
Sanction are the most ridiculous thing that should be internationally illegal. It hurts the good people, the common people, while the oligarchs barely flinch. Maybe the elites will even take advantage of the fear. 100 % will. Fook yo Sank Shuns. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:35:32 </td>
   <td style="text-align:left;"> $QQQ Time to face reality and stop losing money. 
 
This will NEVER CRASH in your lifetime. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:34:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLE $SQQQ $IWM  
 
Finishing the day with a silly meme. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:33:56 </td>
   <td style="text-align:left;"> $QQQ why is the markets going up?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:32:11 </td>
   <td style="text-align:left;"> $QQQ we’ve seen +700pt rallies in less than 24hrs on 3 separate occasions now this year alone. It’s only a matter of time until we get than -900pt day here in tech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:32:10 </td>
   <td style="text-align:left;"> $QQQ -Putin will not go away, he would look like a fool. The whole napoleon complex he has keeps him in Ukraine until he nukes them or gets nuked  

Hope everyone got into puts at the close 💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:29:43 </td>
   <td style="text-align:left;"> $QQQ $SPY pretty wild that VIX was still up 9 percent on the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:25:49 </td>
   <td style="text-align:left;"> THE BRITISH ARMY HAS ISSUED A WARNING TO ITS SOLDIERS NOT TO GO ROGUE AND TRAVEL TO UKRAINE - TELEGRAPH

They also allow Belarus to help Russia $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:24:11 </td>
   <td style="text-align:left;"> $QQQ $SPY so are we in a correction? Are we rallying? Are we crashing? Are we consolidating? Lol this market is random af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:24:09 </td>
   <td style="text-align:left;"> $SPY $QQQ PMI 10am tomorrow but im assuming the markets won&amp;#39;t care </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:21:53 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
https://www.youtube.com/watch?v=uJ-VOO5yUbM 
 
The traders on CNBC believe the bottom is in for the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:21:33 </td>
   <td style="text-align:left;"> $SPY $DASH $QQQ 

A DoorDash driver sprayed a convenience store manager with mace. 😲

This after an Amazon driver shot a motorist yesterday just miles from this incident. 

Will these tech companies start adding a paragraph to their 10Q stating that &amp;quot;Our drivers assaulting innocent civilians is an additional risk that may reduce future earnings&amp;quot;? 

Unbelievable. 🤦

@blancobull @TurtleSniffer @Prat_ 

https://6abc.com/chemicals-sprayed-at-wawa-lawndale-philadelphia-rising-sun-avnue-philly-attack/11607582/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:21:07 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $SPY $BTC.X $DIA 

Fyi cunts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:20:53 </td>
   <td style="text-align:left;"> $SPY $QQQ lots of puts for wednesday mhmm will they kill or let them win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:20:46 </td>
   <td style="text-align:left;"> $QQQ lol wtf. bitcoin up $5k from this morning.  
  
How do you you all stay sane in a market this crazy. One day it&amp;#39;s the end of the world, the next day there are rallies crazier than we&amp;#39;ve seen in 7 years . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:20:20 </td>
   <td style="text-align:left;"> $DOW $SPY $QQQ Wheat is set to move a lot higher with inflation and two of the largest exporters being bogged down in war $WEAT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:18:47 </td>
   <td style="text-align:left;"> Live updates: Ukraine says more Russia shelling during talks $DPY $QQQ $DJIA $VIX $SQQQ https://www.billionaireclubcollc.com/live-updates-ukraine-says-more-russia-shelling-during-talks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:18:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY It&amp;#39;s a sad day when someone u follow has their account suspended by ST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:17:08 </td>
   <td style="text-align:left;"> $QQQ COVID drop for reference. You are currently here as denoted by the arrow. That was a Monday. What happened Tuesday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:15:52 </td>
   <td style="text-align:left;"> $SPY $QQQ im sure market will be just fine just by looking at crypto $AMZN break $3100 will be huge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:15:12 </td>
   <td style="text-align:left;"> U.S. Positioned to Withstand Economic Shock From Ukraine Crisis

https://www.wsj.com/amp/articles/u-s-positioned-to-withstand-economic-shock-from-ukraine-crisis-11646083994

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:14:21 </td>
   <td style="text-align:left;"> Putin’s Invasion of Ukraine Throws Global Markets and Economy Into Uncharted Waters

https://www.usnews.com/news/economy/articles/2022-02-28/putins-invasion-of-ukraine-throws-global-markets-and-economy-into-uncharted-waters?context=amp

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:13:45 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $DJIA 

The real question is does dr. burry fear tom lee or does tom lee fear dr. burry?...

🧸 vs 🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:12:59 </td>
   <td style="text-align:left;"> $SPY $QQQ inverse h and s. Going to 14473 which is around 360 on qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:12:00 </td>
   <td style="text-align:left;"> Russia blocks media outlets, others hacked over Ukraine war $DJIA $QQQ $VIX $SQQQ $SPY https://www.billionaireclubcollc.com/russia-blocks-media-outlets-others-hacked-over-ukraine-war/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:11:39 </td>
   <td style="text-align:left;"> $ES_F $SPY $QQQ  
 
$ES_F Opening above the downtrend resistance. Support now around 4,300 on a re-test. Resistances at 4,500 and then 4,575-4,600 around February highs. 
 
Bullish for now but would be very cautious at those resistance levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:11:15 </td>
   <td style="text-align:left;"> $SPY $QQQ third possibility, flat open. I would bench myself on that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:11:11 </td>
   <td style="text-align:left;"> $QQQ IT WAS A GREAT PONZI FIAT $$$ DAY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:11:09 </td>
   <td style="text-align:left;"> $QQQ 360 PT like it or not....RIP Kobe, when you passed the world literally died with you...massive short after 360 though...back to low 300s... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:10:57 </td>
   <td style="text-align:left;"> Crypto going INSANE 
Stocks about to go INSANE 
The rally of THE AGES is coming 
 
Do you understand the definition of PARABOLIC 
 
you will soon… 
 
wconoky reopening COVID disappeared nobody even talks about it anymore and the same will go for RUSSIA  
 
CONGRATS TO ALL FOLLOWERS 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:10:36 </td>
   <td style="text-align:left;"> $QQQ $SPY secondary possibility is a nice gap down in which we would buy that heavy and continue to short volatility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:09:56 </td>
   <td style="text-align:left;"> $QQQ $SPY most likely scenario is these gap up and y’all wet yourselves but forget to sell your calls or are too greedy, whatever. Then, when you least expect it, will shit the bed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:09:21 </td>
   <td style="text-align:left;"> Stocks Drop On February 28 But The Real Risk Doesn&amp;#39;t Come Until Wednesday - The market appears to be pricing in a less aggressive Fed and that may be a massive mistake. https://mottcapitalmanagement.com/stocks-drop-on-february-28-but-the-real-risk-doesnt-come-until-wednesday/ $C, $SQ $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:08:56 </td>
   <td style="text-align:left;"> $QQQ Last Thursday, wall street said war priced in. So cease fire tonight means sell off, cause cease fire priced in. 
Point I making, can&amp;#39;t have it both ways.........But then again this is Fraud Street </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:08:52 </td>
   <td style="text-align:left;"> Live updates: Canada pledges more military aid to Ukraine $SPY $DJIA $QQQ $VIX $SQQQ https://www.billionaireclubcollc.com/live-updates-canada-pledges-more-military-aid-to-ukraine/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:08:08 </td>
   <td style="text-align:left;"> $QQQ 
📚➡️📈
Option trades, Monday recap 2/28 🎯📈

QQQ 340P +22%
QQQ 347C +82%
QQQ 345P +153%
QQQ 342P +13%
QQQ 344C -35%

Tweet speaks for itself 🤷🏾‍♂️ don’t miss out…
💰💸

https://twitter.com/q_alerts/status/1498431545513816069?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:05:27 </td>
   <td style="text-align:left;"> $QQQ it&amp;#39;s a trick I bet. Trying to trick people into thinking it broke through resistance only to go red tomorrow. Will buy more in a month or so. Or I will buy at $303 whichever happens first </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:05:15 </td>
   <td style="text-align:left;"> $QQQ will the real slim shady please stand </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:04:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 🗣🗣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:03:50 </td>
   <td style="text-align:left;"> $QQQ @LongBacon WILL SUMMON CANOES IF REQUESTED. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:03:03 </td>
   <td style="text-align:left;"> 520,000+ refugees have fled Ukraine since Russia waged war $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/520000-refugees-have-fled-ukraine-since-russia-waged-war/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:02:58 </td>
   <td style="text-align:left;"> $SPY $QQQ

USSR?

https://youtu.be/z77JFw2D6f8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 07:00:37 </td>
   <td style="text-align:left;"> $QQQ too much optimism with Rising interest rates and Russia not backing down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:59:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Are you bullish yet? 
https://www.msn.com/en-us/money/markets/the-kremlin-says-russia-s-economic-reality-has-considerably-changed-in-the-face-of-problematic-western-sanctions/ar-AAUpD14?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:58:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:57:58 </td>
   <td style="text-align:left;"> $QQQ Nasdaq McClellan Oscillator shows tech run continuation likely.   Watch for bullish MacD cross. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:57:11 </td>
   <td style="text-align:left;"> $QQQ Crypto markets signaling another bullish move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:54:55 </td>
   <td style="text-align:left;"> $QQQ bullish reversal looks like. Broke past the 345 mark with ease into close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:53:27 </td>
   <td style="text-align:left;"> $QQQ $BTC.x bear markets are simply a past phenomenon. Hard to accept it, but it&amp;#39;s true. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:52:01 </td>
   <td style="text-align:left;"> $QQQ crypto rally commencing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:51:50 </td>
   <td style="text-align:left;"> Live updates: Ukraine opens entry to foreign war volunteers $SPY $QQQ $DJIA $VIX $SQQQ https://www.billionaireclubcollc.com/live-updates-ukraine-opens-entry-to-foreign-war-volunteers/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:50:53 </td>
   <td style="text-align:left;"> $QQQ when’s the last time the 10yr fell 8% in one day? A very long time me thinks. Not good for equities! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:49:25 </td>
   <td style="text-align:left;"> $SPY $QQQ tom lee bullish on world not being nuked. I&amp;#39;m telling you a nuke could hit the u.s. right now and it would be bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:49:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 77445200. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:49:00 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Zoom isn’t down 30% after earnings. That’s a plus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:48:21 </td>
   <td style="text-align:left;"> $QQQ all aboard 📈📈🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:47:14 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ $UVXY - I like how they are normalizing the idea of nuclear war. Like hey, their rockets have MIRV warheads that can hit 250,000 square miles. But hey, markets should rally right? We live in lunatic world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:45:02 </td>
   <td style="text-align:left;"> $ZM amazing earnings. Don’t sleep on this $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:44:51 </td>
   <td style="text-align:left;"> $PTON $QQQ  
Uh oh...look for more uncertainly to enter the market. 
 
Looks like credible intelligence from multiple sources is suggesting that Belarus is preparing to join the Russian invasion. I guess the talks today didn&amp;#39;t go as hoped. Not surprised... Putin didn&amp;#39;t start this thing with the intention of just giving up after a couple of days.  
 
https://www.msn.com/en-us/news/world/ukrainian-intel-suggests-belarus-is-prepared-to-join-russian-invasion-and-us-suspends-operations-at-embassy/ar-AAUq1Tc?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:43:18 </td>
   <td style="text-align:left;"> $SPY $QQQ As soon as there&amp;#39;s a truce, that&amp;#39;s when we moon 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:42:54 </td>
   <td style="text-align:left;"> $LCID bulls complaining like bro it’s not that big of a deal 13% haircut is nothing compared to other complain (Netflix) which had 20%+ haircuts with bad earnings.
Stop gambling with calls thinking you’ll hit of the next Tesla $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:42:25 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F  FED.  $4700.   $QQQ $DIA 

🧞‍♂️👊🏻🤑🤑🤑🤑⭐️🤑🤑🤑🤑🤑🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:40:44 </td>
   <td style="text-align:left;"> $QQQ Bears today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:40:18 </td>
   <td style="text-align:left;"> $SPY $QQQ  it’s always about the close.  Held the hourly 50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:39:50 </td>
   <td style="text-align:left;"> $QQQ this is forced pension buying EOM.  I&amp;#39;ll long if vwap holds one more day, but i dont think it will.  But.... this flag cout get bought to retest 200.  Little anxeity on my gut short at noon.  Plus 2.7% open?  Thats about right after. Buying puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:39:27 </td>
   <td style="text-align:left;"> $SPY   $QQQ   $NASDAQ    $NDX     $DIA   . 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:32:24 </td>
   <td style="text-align:left;"> 1-Minute Market Recap &amp;amp; Trade Plan For Tomorrow: 
2.28.22-3.1.22 
 
$ES_F $NQ_F $SPY $QQQ $CL_F  
 
https://www.youtube.com/watch?v=abgXBiwpYms </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:30:46 </td>
   <td style="text-align:left;"> $AMC AMC is reporting earnings tomorrow 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:30:01 </td>
   <td style="text-align:left;"> $SPY oh man lol Tom lee is up next about why the sell off is over. Last two times were 477 when he said it was headed to 500 and 450 ish when he said February was for violent V up not Valentine’s Day lol then we hit 407 after. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:28:24 </td>
   <td style="text-align:left;"> Elon Musk Delivers Starlink Satellites To Ukraine For Maintaining Internet Amid Invasion  $TSLA $SPY $QQQ https://www.billionaireclubcollc.com/elon-musk-delivers-starlink-satellites-to-ukraine-for-maintaining-internet-amid-invasion/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:28:08 </td>
   <td style="text-align:left;"> Support Holds Despite Weekend Futures latexb8d151fcab8813329e10e5373365e87dIWM - 3 has yet to reach the target on the wyckoff distribution, but has double bottomed and is consolidating. 210 is the double bottom key level.   
  
$XLF - 3 Moving averages have clustered at the $40 level. That will serve as resistance. above there, we can target the highs again.   
  
Final Thoughts // 3 markets completed their wave 5 selloff last week. If the wave theory holds, we could see corrective waves throughout the market. I am looking to buy shallow pullbacks (wave 2) and prepared to short deeper ones (original wave count was wrong and we will go a lot lower). Trends are still down but indicators are showing divergences which could suggest a reversal. Lets see how this plays out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:25:55 </td>
   <td style="text-align:left;"> $QQQ Bulls = Team USA  
 
Bears = Team Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:24:50 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:24:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $UVXY If the Fed continues their Easy Money Policy, we will see stocks hit new ATHs, and then it&amp;#39;ll be over for the USD and stocks as the US hits hyper inflation. People keep talking that a fiat crisis will never hit the US, but the same people never look at history. Find ONE fiat currency that didn&amp;#39;t fail. The USD hasn&amp;#39;t failed yet, but the debt is unsustainable according to the Federal Reserve. It&amp;#39;s all by design though.. fiats will decline worldwide. The bigger the bubble is, the bigger the hurt its going to cause. So, perhaps the bubble it will be blown bigger so they know next time it collapses, its truly the stake in the heart. It&amp;#39;s one chaotic event after the other. Covid. Russia. Who knows what&amp;#39;s next. Let&amp;#39;s see what March brings. If tomorrow isn&amp;#39;t a completely different story, than it means QE is STILL being pumped for the month of March. They said tapering ends in March... so, end of march? Beginning? We should still see less rally power nonetheless. Lets see. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:24:21 </td>
   <td style="text-align:left;"> Dow falls 170 points, but Nasdaq rallies late for slight gain as investors monitor Ukraine invasion

$DJIA $QQQ

https://www.cnbc.com/2022/02/27/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:24:07 </td>
   <td style="text-align:left;"> $QQQ resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:24:00 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Long and waiting for futes to open... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:23:43 </td>
   <td style="text-align:left;"> $COIN $SPY $QQQ 1 on 1 Over the weekend swing was risky but paid off kinda big </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:23:26 </td>
   <td style="text-align:left;"> $QQQ yea three days in a row. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:23:20 </td>
   <td style="text-align:left;"> $QQQ we are experiencing short squeeze I guess. Not make any sense to go up. How far they can squeeze!  They don&amp;#39;t care about war. But interest hike comin... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:19:47 </td>
   <td style="text-align:left;"> $QQQ How many Rubles are the shorts getting paid? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:19:01 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 2/28/2022 $SPY $XLF $QQQ $TAN $CCJ https://www.chartguys.com/daily-market-videos/4148/are-trend-changes-inevitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:17:39 </td>
   <td style="text-align:left;"> $QQQ does anyone feel like this is going to be a pump and dump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:16:11 </td>
   <td style="text-align:left;"> $QQQ did we reverse the death cross? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:13:04 </td>
   <td style="text-align:left;"> $QQQ 1H 
back to $300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:12:36 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

GREED!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:12:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $TLT $UUP  
 
Daily market recap video. Enjoy! 
 
https://www.youtube.com/watch?v=RYVfNJNxIr8&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:10:28 </td>
   <td style="text-align:left;"> $SPY $QQQ Powell will wreck the market Wednesday. You have been warned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:10:14 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
 
7.5% inflation 
 
FED still increasing balance sheet 
FED still holding interest rates at 0% 
FED still printing BILLIONS 
 
BRILLIANT!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:10:14 </td>
   <td style="text-align:left;"> $SPY     $SPX    $QQQ   $DIA  🔥 $NASDAQ  🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:09:42 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA How do I short the Russian Ruble $USDOLLAR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:08:51 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:08:36 </td>
   <td style="text-align:left;"> $NVAX Q4 EPS miss of  over -$9… worst eps miss they’ve ever had. $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:07:56 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Anyone heard from Putin? Or did he pass away? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:07:48 </td>
   <td style="text-align:left;"> $QQQ bitcoin rally📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:07:09 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $QQQ $SPY it&amp;#39;s taking some people longer than others to realize that stocks aren&amp;#39;t in a good spot but crypto is in a very good spot. Macroeconomic Fundamentals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:06:34 </td>
   <td style="text-align:left;"> $QQQ Imagine living in the Western world and shorting the US stock market, the pillar of freedom, and indirectly helping Putin. Time to do your patriotic duty and join your fellow hero Bulls currently saving the day. You might even feel proud when you can finally tell your kids you&amp;#39;re now fighting with the good guys! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 06:00:54 </td>
   <td style="text-align:left;"> $SPY $QQQ Tom Lee: The low is locked in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:59:56 </td>
   <td style="text-align:left;"> $QQQ algos saving this shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:55:56 </td>
   <td style="text-align:left;"> $QQQ Greed is amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:54:27 </td>
   <td style="text-align:left;"> Fundstrat&amp;#39;s technical view via Market Newton CMT 
 
🔹Friday&amp;#39;s move back above 4,365, the 2/14 lows is  
      positive 
🔹 May back &amp;amp; fill first 
🔹Tradable bottom is here 
🔹Overweights highlighted 
 
$SPY $QQQ $AAPL $WMT $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:54:18 </td>
   <td style="text-align:left;"> $QQQ HUGE GAINS TODAY!🎉🤑😈
Free discord in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:53:20 </td>
   <td style="text-align:left;"> $LCID with bad guidance, miss on sales, and a few thousand cars produced in a year is next to nothing. 
 
I put out this FREE ALERT in my discord 12 min before close. Hope some of you guys got puts with me. Closely watching $SDC and $ZM. $SPY $QQQ 
 
Free to join 👇 
https://discord.io/MTrading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:53:09 </td>
   <td style="text-align:left;"> $SPY $QQQ Give Kyle his freedom stick and send him to  🇺🇦 as a mercenary, he already has proven he is effective at killing commies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:52:35 </td>
   <td style="text-align:left;"> $NASDAQ $DJIA $SPY $QQQ 

Anybody care to know when the last time 30 yr closed over 6% red? I’ll give you a hint. A LONG time. That is DEFINITELY worth noting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:51:19 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM last night&amp;#39;s futures looked horrible...market did well to recover today.  Where do we go from here?  Up (I hope) 
Anyone went long (add more) today?  Which stocks/ETFs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:50:55 </td>
   <td style="text-align:left;"> $QQQ  $SPY $DJIA   Never have gone bearish on anything before (only been investing ~2 years) however, I just can’t see how people are bullish on the broad market right now. I understand the logic of pushing for a big short squeeze to close out this massive bull run the past 18 months, but numbers are numbers and facts are facts. Things just don’t add up. I am bearish, and I do believe the market is on the brink of a collapse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:50:51 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 907.6K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:49:37 </td>
   <td style="text-align:left;"> $SPY $QQQ I stand by my Bear Stearns optimism </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:49:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

I will add more puts tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:49:20 </td>
   <td style="text-align:left;"> $QQQ 450 Eod tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:48:14 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $DJIA $QQQ --- 
 
You cannot trust the press releases from either side; most of it is just propaganda.  
 
Just see how the market performs to figure out which side is really winning:   
 
---- Bullish market = Putin is winning (NATO countries will abandon Ukraine to its fate;  less pressure on Putin;  less chance for war to escalate; things settle down) ; 
 
--- Bearish Market = Putin struggling /stagnating (NATO countries use the opportunity to intervene more in Ukraine;  more pressure on Putin;  bigger chance for war to escalate by threatening use of nuclear weapons; markets panic). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:47:55 </td>
   <td style="text-align:left;"> $QQQ has had an intraday range of more than 1% every day this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:47:04 </td>
   <td style="text-align:left;"> $QQQ The Bulls of USA have won the day again vs. Putin&amp;#39;s Communist Bears trying to take the US stock market down for their dear leader. USA! USA! USA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:45:09 </td>
   <td style="text-align:left;"> $QQQ From what I understand, same people who engineered the financial crises, are now working for the government. 
Wall street runs the government or, government runs wall street. 
Answer, when u have both, you can bet fraudulent practices. 
So when u call out corrupt governments, look at your own first. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:44:04 </td>
   <td style="text-align:left;"> Markets See Mixed Day Of Trading As Russia-Ukraine Drama Continues  $QQQ $SPY $DIA $CVX $V 

https://newsfilter.io/a/5a6cd44079d199836699f7df49f88896 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:43:11 </td>
   <td style="text-align:left;"> $CHWY Potential double bottom candidate. Great volume today. Above 50 and this can ride to heavy resistance of 60 rather quickly. On watch! $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:42:31 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Are my $650 05/20 puts screwed?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:42:29 </td>
   <td style="text-align:left;"> $ZM If you&amp;#39;re going to kitchen sink it now is the time  
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:42:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $YNDX $BTC.X  My great great grandpa knew a Ukranian person. Therefore, I will act upset now and fully condemn war and violence that is taking place for some clout. Especially since Ukraine has always been a peaceful place to live and definitely didn&amp;#39;t have any war in the eastern region since 2014 where the government was shelling and shooting russian born civilians. That is all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:41:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $ETH.x $IWM $RSX  Just wait it out....must keep reminding myself of this... https://youtu.be/rDrhI1GUnNg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:41:34 </td>
   <td style="text-align:left;"> $QQQ bulls gonna be very confused about where the HYPER V recovery went over the next couple days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:40:47 </td>
   <td style="text-align:left;"> Russia just fell victim to the whole movement. They have been outright canceled worldwide. 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:40:21 </td>
   <td style="text-align:left;"> $QQQ markets about to crash in near future , same pattern like dotcom -bubble had, every dip gets buyed even when there is a very good reason for a dip . Well, moonboys generation repeats boomer generation mistakes .live and learn . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:39:23 </td>
   <td style="text-align:left;"> $QQQ tomorrow they pamp again to liquidate bears, that&amp;#39;s when you short, patience makes you money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:38:32 </td>
   <td style="text-align:left;"> NEW POST: Stock Market Recap 02/28/22 {Video} https://marketchess.com/2022/02/28/stock-market-recap-02-28-22-video $IWM $QQQ $SPY $URA $USO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:38:30 </td>
   <td style="text-align:left;"> $QQQ hope ya’ll went short on that BS pop into close. Easy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:37:07 </td>
   <td style="text-align:left;"> $QQQ Bought puts at close on that pop. Hate being a bear but here we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:35:53 </td>
   <td style="text-align:left;"> $QQQ hey green is green, no complaints!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:35:50 </td>
   <td style="text-align:left;"> $QQQ Bears its not to late to be part of the biggest bull run in history... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:35:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $Btc.x Stay safe and cheers babes, GIVE ME YOUR WORST AND ILL SHOW YOU MY BEST. https://youtu.be/7xxgRUyzgs0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:35:14 </td>
   <td style="text-align:left;"> $SPY $qqq Going to call bottom here as long as this week&amp;#39;s candle can hold above the trend line. We need to get above the 9ma next week! It&amp;#39;s looking good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:35:11 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Here&amp;#39;s you nuclear bomb war mongers! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:34:52 </td>
   <td style="text-align:left;"> $SPY $QQQ bear markets pump on Mondays! All you gotta know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:34:46 </td>
   <td style="text-align:left;"> Russia saved US markets from the Fed $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:34:30 </td>
   <td style="text-align:left;"> $SPY $QQQ with Bidens speech Tuesday.. Got a feeling a feeling PUTins going to do slmething beforehand, they haven&amp;#39;t disclosed the sanctions PUTins going to do to the world either... Bearish for now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:34:19 </td>
   <td style="text-align:left;"> $SPY $QQQ A very strong close. Looks like we indeed have bottomed and investors now will look to buy the dips at every opportunity that they get. As long as Russia isn&amp;#39;t shooting nuclear to Europe and the US, I think this market will do fine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:34:00 </td>
   <td style="text-align:left;"> $QQQ Bitcoin&amp;gt; puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:33:56 </td>
   <td style="text-align:left;"> $QQQ all time highs..coming.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:33:38 </td>
   <td style="text-align:left;"> $QQQ MM saw all our puts and said fuck your puts... pump it +$4-6 EOD.... 
 
Idk why I continue to play in this super rigged market. Sports betting or the casino is less risky than this POS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:33:28 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Maybe we can keep hearing about how war matters to the markets again all night. 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:33:26 </td>
   <td style="text-align:left;"> $SPY $QQQ Putin dead is the only way this war will end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:32:13 </td>
   <td style="text-align:left;"> $QQQ crazy swings. All these red futures but positive closes. Nj bulls.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:31:10 </td>
   <td style="text-align:left;"> $TSLA $NKLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:30:44 </td>
   <td style="text-align:left;"> $SPY the end of the world is priced in...

$QQQ $DJIA $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:30:16 </td>
   <td style="text-align:left;"> $qqq bears have sub &amp;lt;$20k accounts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:29:21 </td>
   <td style="text-align:left;"> Huge 1st day #DayTrading w/ #HIRO  
Helped us establish Long &amp;amp; Short trades on $SPY $QQQ $IWM &amp;amp; aided with the Buy to cover. Both times following the info provided in this video about looking for divergence  
Full Disc. #SpotGamma does NOT compensate me in any way  
I share because I find it helpful https://www.youtube.com/watch?v=O3za3a8EO-o&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:28:16 </td>
   <td style="text-align:left;"> $HIMX I&amp;#39;m just waiting for the spike.  I&amp;#39;m sure it&amp;#39;s coming but bloody hell this is painful seeing this get thrashed around while trading under a PE of 4.  How can a semiconductor trade at such a wildly low PE FFS?  They haven&amp;#39;t missed an ER for over 3 yrs.  $SPY $QQQ $IWM  This needs bull traders to catch the cocky short int in a squeeze. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:28:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $TSLA bears counting on Putin for the market to tank bc they realized inflation doesn’t matter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:27:15 </td>
   <td style="text-align:left;"> $SPY $QQQ  $SPX $DJIA  hypothetically the United States falls into a civil war, but plot twist not between political groups or states its between perma bulls vs perma bears , who is coming out on top ? haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:25:47 </td>
   <td style="text-align:left;"> $MSFT  $QQQ $SPY $DIA $XLK  eom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:25:33 </td>
   <td style="text-align:left;"> $LCID This is why I know that the downturn is not over... $SPY $QQQ ... EV companies are still way overpriced without any profits.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:25:15 </td>
   <td style="text-align:left;"> $dia $spy $qqq u dumbasss bears going against American companies. Just short or buy puts with this garbage russian ETF $rsx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:25:04 </td>
   <td style="text-align:left;"> $QQQ the real question is... how could you not know it was coming? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:24:57 </td>
   <td style="text-align:left;"> $SPY $QQQ 100% cash overnight. I will sleep peacefully </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:24:31 </td>
   <td style="text-align:left;"> Wondering if we will get a $NVDA pop this week... With good holds on key levels with $SPY $QQQ $NASDAQ  
 
We think we can and we will also watch a play on them!  
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:24:10 </td>
   <td style="text-align:left;"> $SPY $QQQ 29.1% port growth for Feb 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:24:09 </td>
   <td style="text-align:left;"> $QQQ Potential back test of prior resistance turned support (Green support, red resistance). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:24:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $HPQ Of note for other companies in HP Earnings... 

*HP INC SAYS RUSSIAN SANCTIONS TO HIT QUARTERLY EPS BY 3 CENTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:23:56 </td>
   <td style="text-align:left;"> $SPY $QQQ 19.6% port growth for Feb 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:23:54 </td>
   <td style="text-align:left;"> Simple logic tells you into the end of each month is a massive ripper always save the monthly candles - did you listen? 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:23:17 </td>
   <td style="text-align:left;"> $QQQ A FINAL FLUSH WILL BE COMING SOON ... $RUT , $IWM , $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:23:16 </td>
   <td style="text-align:left;"> $QQQ 

Tomorrow RETESTS ⛔️⛔️340 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:22:23 </td>
   <td style="text-align:left;"> $SPY $AMZN $QQQ 

An Amazon delivery driver shot a guy after they got into a fender bender. This happened 10 minutes outside Philadelphia. 

Wow. 

How did he pass the background check? 🥴

https://6abc.com/amazon-driver-shooting-clifton-heights-delaware-county-delco/11608426/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:21:01 </td>
   <td style="text-align:left;"> $BABA Apparently some don&amp;#39;t know how Traders play EOM so to be clear. A HF has to show Investors they&amp;#39;re doing a great job, a PM showing he/she owns Chinese stocks or Banks at the end of Feb would catch some heat so they play the &amp;quot;move things around&amp;quot; game.  
Its part of the job :o) 
 
$jpm $jd $c $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:19:19 </td>
   <td style="text-align:left;"> $TSLA $QQQ $PLTR $BTC.X $SPY is 26% a lot for 1 day? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:19:10 </td>
   <td style="text-align:left;"> $DIA $SpY $qqq shorts and buy puts on this russian ETF $RSX for sure it will go to zero </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:19:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$1.2B to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:18:42 </td>
   <td style="text-align:left;"> $QQQ earnings all shocking today after hours as well lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:18:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:18:15 </td>
   <td style="text-align:left;"> $qqq 🐑 Monday in a 🐑 tape YO!   🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:17:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:17:24 </td>
   <td style="text-align:left;"> $QQQ 
I not sure what everyone is talking about, but the amounts of puts is insane. Not for tomorrow but they are stacking up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:17:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 2/28 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:17:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Vlad, if you can hear us! 
 
We... Want... a Ceasefire!!! 
We... Want... a Ceasefire!!! 
We... Want... a Ceasefire!!! 
 
C&amp;#39;mon everybody! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:17:00 </td>
   <td style="text-align:left;"> $QQQ Did not bought puts they gonna pump tomorrow again and THEN I will short this bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:15:43 </td>
   <td style="text-align:left;"> $SPY $QQQ can&amp;#39;t fight powell that son of a Bitch is to powerful. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:15:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $BA $UVXY $JPM   
 
Finom Group trade alerts updated. Still rocking a 90% YTD hit rate. You can trade with us. Building core positions, scalping and swing trading daily/weekly. https://1drv.ms/x/s!Aj3zbNeZWtzPZ4N6DtMsvnE7Ujs?e=Utooqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:14:45 </td>
   <td style="text-align:left;"> $SOXL I left around 2pm or so to hit up COST. Came back and see nothing much happened. Glad I got that knocked out instead of sitting around watching each 5 minute candle... $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:14:44 </td>
   <td style="text-align:left;"> $QQQ mentioned the bullish divergence on Friday- daily chart -- 
ichimoku system is bearish but indicator points on turn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:13:55 </td>
   <td style="text-align:left;"> $QQQ if you are confused as to why. Time then price. Market has to hit a set prices at set dates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:13:30 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Putin stopped to talk to see if Ukraine had enough and if their willing to give in. Putin want smoke this will continue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:13:21 </td>
   <td style="text-align:left;"> $QQQ iron curtain at play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:12:38 </td>
   <td style="text-align:left;"> https://youtube.com/watch?v=Tfp63bYqr_s&amp;amp;feature=share
$spy $qqq $iwm nice bounce late into close, hope everyone is doing alright! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:12:36 </td>
   <td style="text-align:left;"> $QQQ No VWAP pension buys tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:12:20 </td>
   <td style="text-align:left;"> did $AAPL report yet? 
 
stonks 
 
$QQQ $NDX $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:11:53 </td>
   <td style="text-align:left;"> $SPY $QQQ What moves the 10yr yield on a day to day basis as well as intraday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:11:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $UVXY $AAPL  
 
If price actions scares you, up your resources. Mechanical end of month rebalancing is nothing to fear and everything to take advantage. Can always see it the equity/bond ratio when it&amp;#39;s happening.  Pro Tip of the day ;-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:10:34 </td>
   <td style="text-align:left;"> $QQQ fed is making their pumps even more obvious now lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:10:17 </td>
   <td style="text-align:left;"> Pretty strong bounce back the last few days to finish out the month. As long as no gap down tomorrow below $433.50-$434 resistance it looks like $SPY will break through the monthly downtrend. Same for $QQQ ($338-$339 resistance). 
 
I&amp;#39;d look for a re-test of the Feb highs next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:09:37 </td>
   <td style="text-align:left;"> $QQQ that my freinds was f uped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:09:22 </td>
   <td style="text-align:left;"> The narrative remains, massive BTFD opportunity in US stocks, dip was way overdone. Rally of ages comes. 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:09:12 </td>
   <td style="text-align:left;"> $SPY vix up 10% but $QQQ saying nothing to see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:08:56 </td>
   <td style="text-align:left;"> $QQQ any bull thinks that this Is not manipulated? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:08:37 </td>
   <td style="text-align:left;"> $SPY $QQQ bears should be happy, they get a red day.  😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:08:19 </td>
   <td style="text-align:left;"> $QQQ $SPY Ok so technically market gives 0 fucks, nuclear war would probably bring these to ATHs, no doubt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:08:04 </td>
   <td style="text-align:left;"> $QQQ up on shit $ZM earnings. Nothing makes sense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:07:26 </td>
   <td style="text-align:left;"> $QQQ green today, continuation from Friday tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:06:15 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … will March be a green 🍀 candle month ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:06:14 </td>
   <td style="text-align:left;"> $SPY $QQQ Just came to see how those bears that shorted tech were doing .... holy sht lmfao 🤣 poor fcks.  Keep going against the system load moar poots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:06:09 </td>
   <td style="text-align:left;"> $SPY $QQQ White House: President Biden Will Discuss Inflation During State Of The Union Address Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:05:54 </td>
   <td style="text-align:left;"> 3 S&amp;amp;P Outperformers…That Aren’t Oil Companies $SPY $QQQ $DJIA $SQQQ $VIX https://www.billionaireclubcollc.com/3-sp-outperformersthat-arent-oil-companies/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:05:37 </td>
   <td style="text-align:left;"> $QQQ market seem like dopehead shooting speedball up his veins for past 2 month . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:05:08 </td>
   <td style="text-align:left;"> $QQQ what a finish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:04:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL

Looks like the only thing that crashed was bears portfolio’s... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:04:28 </td>
   <td style="text-align:left;"> $QQQ PLUNGE PROTECTION TEAM WORKING OVERTIME BABYYY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:04:04 </td>
   <td style="text-align:left;"> $QQQ I give up on trading. What a horrible experience this journey has been . 
 
Good luck everyone. Hope shit goes better for you all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:03:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
My total balance all accounts went up $58 today.  Calling the lambo dealership now. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:03:48 </td>
   <td style="text-align:left;"> $QQQ 

🤣🤣🤣🤣🤣clueless Market

Calls tonight FCKED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:03:28 </td>
   <td style="text-align:left;"> $QQQ I guess moving forward we should expect 5 to 7 dollar swings back-and-forth either direction and then back the other way five or seven dollars Jesus so hard to figure out which way to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:03:16 </td>
   <td style="text-align:left;"> WHITE HOUSE SAYS PRESIDENT BIDEN WILL DISCUSS INFLATION DURING STATE OF THE UNION ADDRESS TUESDAY 
 
No option but rate hikes  ... $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:03:00 </td>
   <td style="text-align:left;"> $QQQ everything priced in..including human extinction.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:02:45 </td>
   <td style="text-align:left;"> $QQQ What a close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:02:43 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Trading would be hard if it weren&amp;#39;t so damn easy! 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:02:40 </td>
   <td style="text-align:left;"> $QQQ fed will be at 11 trillion soon 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:02:32 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Wow, bears got obliterated... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:02:03 </td>
   <td style="text-align:left;"> $QQQ downtrend move out of consolidation expected 3-4th. Mark it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLE 

Where is the leader of the US?

He couldn&amp;#39;t give us a press conference over the weekend to reassure us and demonstrate his leadership capabilities because he was busy in Delaware. 

Now where is he? He&amp;#39;s got more important matters to address than the greatest geopolitical unrest in 75 years?

🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:52 </td>
   <td style="text-align:left;"> $QQQ it&amp;#39;s funny seeing bears and bulls hate each other when the prices fluctuate like some football game or something </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:48 </td>
   <td style="text-align:left;"> $QQQ something is fishy. These fuckers have been pumping into close... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:42 </td>
   <td style="text-align:left;"> It feels SO good to be long right here omg --- the rally of ages comes $spy $qqq optimism wins as the world unites against PUTIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:25 </td>
   <td style="text-align:left;"> $QQQ how is it that Robinhood can sell your calls at 3pm then hold them and then your calls are 20x what they sold them for #fraud. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:20 </td>
   <td style="text-align:left;"> $QQQ facist bears when will you learn?😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:14 </td>
   <td style="text-align:left;"> $QQQ any more pump the chart would&amp;#39;ve went like this 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:13 </td>
   <td style="text-align:left;"> $QQQ jpow yooo bro smd. With no hands tho.

I did switch to calls on some small caps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:04 </td>
   <td style="text-align:left;"> $QQQ $SPY $NVDA You have to laugh how every chart is exactly the same </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:01:03 </td>
   <td style="text-align:left;"> $QQQ that’s a big fuck you to bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:00:58 </td>
   <td style="text-align:left;"> $QQQ $SPY When Powell said they still have &amp;quot;TOOLS&amp;quot; LMFAO crazy fing price action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:00:45 </td>
   <td style="text-align:left;"> $SPY $QQQ Remember the fast pumps at EOD during covid drop? Yeah that looked identical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:00:21 </td>
   <td style="text-align:left;"> $QQQ step outside for a second and we rally back to green?? What news was released now hha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:00:08 </td>
   <td style="text-align:left;"> $QQQ frankly terrifying price movement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:00:08 </td>
   <td style="text-align:left;"> $QQQ $SPY the fed is doing everything possible to not let this crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-01 05:00:04 </td>
   <td style="text-align:left;"> $QQQ this ain’t for boys, it’s for men🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 08:42:29 </td>
   <td style="text-align:left;"> $SPY Closed the month down 3.17% bringing the decline to 8.23% on the year. This is the first time that the $SPY dropped in consecutive months since September-October of 2020. 
 
$QQQ $AAPL $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 08:33:52 </td>
   <td style="text-align:left;"> $LCID PIF not selling. If they do, that’s when $AAPL and/or $AMZN should jump in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 08:26:53 </td>
   <td style="text-align:left;"> Possible worst case scenario: $AAPL and $AMZN bid up $LCID sometime in the future for M&amp;amp;A like they are currently doing to try and acquire NFL Sunday Ticket . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 08:25:11 </td>
   <td style="text-align:left;"> $AAPL  If the Ruskies agree on a cease fire we could see 175 tomorrow….think it can’t happen? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 08:11:13 </td>
   <td style="text-align:left;"> $STRR ⬆️ 🚀 

$MULN $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:58:10 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #3 ticker with sweep activity where institutions are trading options urgently with 24.8K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:57:41 </td>
   <td style="text-align:left;"> $AAPL Gonna Rip tomorrow 👍👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:54:01 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Where’s my bear gang at? 😢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:52:15 </td>
   <td style="text-align:left;"> latex4d88f8f72cf86c93d8fc55d6acce6c2dAAPL 841k (56% call/44% put)
$AMD 628k (71% call/29% put)

Lynk in bayo for option trading ideas and alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:47:48 </td>
   <td style="text-align:left;"> $AAPL who all are holding calls, you guys have nerves of steel - I am holding 100 167.5 calls friday expiry 🤟💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:41:25 </td>
   <td style="text-align:left;"> $BKKT they announced they were in advanced talks w $aapl over 6 months ago.  They must be advanced advanced by now 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:41:21 </td>
   <td style="text-align:left;"> $RNDR.X Excited by Render? You should be…Some quick DD right here about why it’s used by $AAPL $DIS $NFLX and $FB 

https://youtu.be/r7D2CA8qPHY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:33:21 </td>
   <td style="text-align:left;"> Making a safer internet with Cloudflare: 10,515,843 SSL requests served in the last month! CONGRATULATIONS $GOOG &amp;amp; $AAPL APPS COMING SOON.. CONGRAULATIONS BILLIONAIRE CLUB CO LLC. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:33:15 </td>
   <td style="text-align:left;"> $XIACY 🐂🐂🐂 $AAPL $SSNLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:27:11 </td>
   <td style="text-align:left;"> $AAPL reversal has started. They got y’all listening to this Ukraine noise.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:25:59 </td>
   <td style="text-align:left;"> $AAPL what calls you guys have? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:25:06 </td>
   <td style="text-align:left;"> $AAPL just a casual trillion dollars in after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:22:48 </td>
   <td style="text-align:left;"> $AAPL I bet…APPLE will make its own component cars….too much market potential with the 🍏 stores carrying interchangeable components to change or update their cars…IMAGINE THE POTENTIAL…UNCIVILIZED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:16:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 8.00, indicating great health for $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:10:56 </td>
   <td style="text-align:left;"> $LCID open for discussion with $AAPL and potential partnership with anyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:09:39 </td>
   <td style="text-align:left;"> $LCID did he say $AAPL ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:09:32 </td>
   <td style="text-align:left;"> $RTX going to keep flying with war going on, calls printing daily! Could see $115+ in the next week or two $AAPL $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 07:07:14 </td>
   <td style="text-align:left;"> $FB $AAPL $TSLA  $MSFT $CCL 
…………………………………………Has anyone of you noticed that the Russian stock market is closed until the 5th of March?   
Think about why for a moment.  
That market would have completely collapsed if it was open.  
But” if one thing could change, or a event were to happen before then of great significance” then that market could stabilize. 
  It seems Vladimir Putin is betting on something….  
Before it’s opened so it doesn’t collapse.   Thoughts anyone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:58:03 </td>
   <td style="text-align:left;"> $AAPL $168 possible tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:55:28 </td>
   <td style="text-align:left;"> $AAPL double bottom is in and working the right side of the base.     BO is coming at 176.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:38:18 </td>
   <td style="text-align:left;"> $AAPL Can’t wait till this starts delivering massive misses and reverts to the mean…That is at 75 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:32:55 </td>
   <td style="text-align:left;"> $SPY 🏆🎖🙌🏻🙌🏻 $AAPL $TSLA $MSFT $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:32:17 </td>
   <td style="text-align:left;"> $SPY I sometimes wonder if Tom Lee ever gets angry &amp;amp; raises his voice, what would that sound like? 
 
$aapl $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:28:33 </td>
   <td style="text-align:left;"> $LCID $TSLA $NVDA $AAPL $GGPI 

Updating 2022 production outlook for Lucid Air to a range of 12,000 to 14,000 vehicles.

&amp;quot;We remain on track to grow our Casa Grande facility to nearly quadruple its size as the first greenfield dedicated EV factory in North America; and today we announced plans to build a brand new manufacturing facility in the Kingdom of Saudi Arabia; we estimate that the location of our first international manufacturing plant in the Kingdom of Saudi Arabia may result in up to $3.4 billion of value to Lucid over 15 years.&amp;quot;

https://finance.yahoo.com/news/lucid-announces-fourth-quarter-full-210500201.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:18:23 </td>
   <td style="text-align:left;"> $AMD $AAPL $TSLA $MSTR  
Tech could get going if bonds get bought? 
 
https://www.youtube.com/watch?v=RYVfNJNxIr8&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:10:54 </td>
   <td style="text-align:left;"> $DWAC Ouch, like I said, from #1 6 days ago to under #20 in the $aapl app store. 
Its all happening 
 
https://www.newsweek.com/truth-social-users-losing-interest-trumps-social-media-app-1683375 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:05:37 </td>
   <td style="text-align:left;"> $AAPL     🍏 Unusual, “JPM AAPL Note”, out today:  Multiple “Buy Side” Analysts “Reiterating”:  AAPL PT of $210.  Rating:  Overweight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:03:20 </td>
   <td style="text-align:left;"> $AAPL Once again I&amp;#39;m humbled by my arrogance of being able to predict where this stock or market will go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:01:33 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-28 Options Analysis Video: 
https://www.youtube.com/watch?v=n7eb3XvXxwU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 06:01:09 </td>
   <td style="text-align:left;"> $ZM THIS JUST IN $AAPL TO TAKE FACETIME PUBLIC A $1b EVAL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:57:52 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:54:27 </td>
   <td style="text-align:left;"> Fundstrat&amp;#39;s technical view via Market Newton CMT 
 
🔹Friday&amp;#39;s move back above 4,365, the 2/14 lows is  
      positive 
🔹 May back &amp;amp; fill first 
🔹Tradable bottom is here 
🔹Overweights highlighted 
 
$SPY $QQQ $AAPL $WMT $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:50:12 </td>
   <td style="text-align:left;"> $AAPL  🍏 Massive surge in Volume, into the Close.  In the “final second” of the Close, 15.4 Million AAPL Shares traded to the “Buy Side”.  Are you, trading smart?  I hope so.  Trade wheat, not chaff.  Own the best.  Own, AAPL.  Now:  On watch, for the Apple “Spring Product Event” Announcement tonight/tomorrow:  Developers, receive their “Invitations” hours ahead of the public Announcement.  So, stay tuned…to see if the rumored “Event Date” is true, or delayed due to “Conflict”.  Pray for peace, in Ukraine 🇺🇦. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:49:16 </td>
   <td style="text-align:left;"> $AAPL  
One of the best value stock... 
Wanna know why? 
Because they have $200 Billion in CASH ON HAND! ahaha 
 
Unstoppable. 
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:48:42 </td>
   <td style="text-align:left;"> $GOOGL where all the $1500 price targets ? 🤣🦍🚀 $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:42:01 </td>
   <td style="text-align:left;"> $AAPL https://www.theblaze.com/news/ukrainian-government-official-shreds-biden-democrats
 Who voted for this Clown . Most hated president world wide </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:41:30 </td>
   <td style="text-align:left;"> $AAPL $FSR Fisker a Lifestyle Brand in the Making https://fiskerati.com/lifestyle/fisker-is-a-lifestyle-brand-in-the-making-just-like-apple/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:41:20 </td>
   <td style="text-align:left;"> $AAPL 170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:40:58 </td>
   <td style="text-align:left;"> $AAPL just sharing... @Meghantay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:40:57 </td>
   <td style="text-align:left;"> $AAPL 168$ tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:40:48 </td>
   <td style="text-align:left;"> $AAPL if big players are loading, then we may see 150-155 again. Big weekly demand zone. 

Closed all long positions. Was sized too large in them. 

Good luck to short term longs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:39:58 </td>
   <td style="text-align:left;"> Nothing is stopping this freight train of a stock $AAPL  
 
Whole market gets killed... NOT $AAPL haha 
 
$AMZN $TSLA $NVDA  
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:38:46 </td>
   <td style="text-align:left;"> $FSR $AAPL Fisker is a Lifestyle Brand in the Making https://fiskerati.com/lifestyle/fisker-is-a-lifestyle-brand-in-the-making-just-like-apple/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:36:10 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 333.8K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:35:41 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Invest in Rubles they said.  Can&amp;#39;t miss in 2022 they said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:34:00 </td>
   <td style="text-align:left;"> $AAPL Took the Jan 24 low last week.  We like looking for a decline further down still where buyers can enter at the blue box for a bounce.  We don’t like to sell it short this close to the blue box though, but we do like to buy it lower at the extreme 100% area.  #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:33:14 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Worried About Geopolitical Risk? Be Like Buffett and Hold Apple. https://www.stck.pro/news/AAPL/23615424 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:32:42 </td>
   <td style="text-align:left;"> $AAPL eod update on my poopy “phone” chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:31:50 </td>
   <td style="text-align:left;"> $AAPL theta burn basically </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:29:01 </td>
   <td style="text-align:left;"> $AAPL It’s trying for Those fools to buy some call option </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:28:57 </td>
   <td style="text-align:left;"> $AAPL do you guys watch apple TV?

How would you feel if it&amp;#39;s shoppable? 

https://www.prnewswire.com/news-releases/season-three-of-david-meltzers-2-minute-drill-premieres-on-apple-tv-301487896.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:28:46 </td>
   <td style="text-align:left;"> $AAPL Sup 160.00 Dunk Apple Stock to lower Lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:26:53 </td>
   <td style="text-align:left;"> $AAPL honestly should not have ended green today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:21:38 </td>
   <td style="text-align:left;"> March 1st money coming into market tomorrow. 
Enjoy the reversal $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:21:10 </td>
   <td style="text-align:left;"> $AAPL always bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:20:27 </td>
   <td style="text-align:left;"> Watching to see how the market reacts overnight! We think a nice bounce and push this week could set-up nicely for the following weeks!  
 
$SPY $NASDAQ $TSLA $AAPL  
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:18:59 </td>
   <td style="text-align:left;"> $AMZN $AAPL $PYPL Hope y’all STACKED 
Ready for the big Green Day ahead? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:17:27 </td>
   <td style="text-align:left;"> $AAPL TECH INVESTORS CNBC INTERVIEW MARK MAHANEY https://www.youtube.com/watch?v=yjVhoS6HYQM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:14:46 </td>
   <td style="text-align:left;"> $AAPL fleecing of the sheep complete, silence thhe lambs.  https://www.youtube.com/watch?v=m61UeElmVZ8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:13:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:12:20 </td>
   <td style="text-align:left;"> did $AAPL report yet? 
 
stonks 
 
$QQQ $NDX $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:11:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $UVXY $AAPL  
 
If price actions scares you, up your resources. Mechanical end of month rebalancing is nothing to fear and everything to take advantage. Can always see it the equity/bond ratio when it&amp;#39;s happening.  Pro Tip of the day ;-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:11:03 </td>
   <td style="text-align:left;"> $AAPL that 12.4 million sell order right before close, someone wanted to get out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:10:53 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m hoping we can see 166.50 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:10:04 </td>
   <td style="text-align:left;"> $AAPL anyone hear of an attack hero with high intelligence called PeaceMaker, can say not  more then 12 can say they do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:10:02 </td>
   <td style="text-align:left;"> $AAPL Million times a day CNBC&amp;#39;s talking heads and their &amp;quot;expert guest&amp;#39; repeat parrot like ON EVERY SHOW, EVERY MINUTE, regurgitate   about FED or Inflation, Fed inflation, Rate hike, rate hike </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:08:14 </td>
   <td style="text-align:left;"> $AAPL was super strong today, its heavily weighted on all main indices. Spx, djia,compx. lets call spx the weighted mean, and Apple outperformed $spy&amp;#39;s 24 points down with 16 points up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:07:31 </td>
   <td style="text-align:left;"> If $AAPL holds this 165 level they could be back at ATH this month! 
 
We are definitely WATCHING them!!! 
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:05:47 </td>
   <td style="text-align:left;"> $AAPL after hours lurch up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:04:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL

Looks like the only thing that crashed was bears portfolio’s... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:00:49 </td>
   <td style="text-align:left;"> $AAPL 

What a comeback !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:00:40 </td>
   <td style="text-align:left;"> $AAPL Aright 🍏🍏🍏! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 05:00:28 </td>
   <td style="text-align:left;"> $AAPL  
 
Still a growth stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:58:24 </td>
   <td style="text-align:left;"> $AAPL This is all a trap cell off and run away Putin Is going to Nuke the world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:58:11 </td>
   <td style="text-align:left;"> $AAPL Closing  0.10 cents in the green🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:57:59 </td>
   <td style="text-align:left;"> $AAPL $210 soon ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:57:24 </td>
   <td style="text-align:left;"> $aapl Opened 11 Put credit spreads today at local minimas. Not bad. Looking to open about 24 more. Dont know if i should do it tomorrow or wait for a mid week dump ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:57:22 </td>
   <td style="text-align:left;"> $AAPL go green mf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:56:48 </td>
   <td style="text-align:left;"> Buy for tomorrow I&amp;#39;m going with $NCLH $NIO printed as stated. heck yeah. Well played. $DJIA $TSLA let&amp;#39;s gooo green!!! $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:56:46 </td>
   <td style="text-align:left;"> $AAPL bounce bounce off that 100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:56:06 </td>
   <td style="text-align:left;"> $AAPL Come on 166 before close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:55:58 </td>
   <td style="text-align:left;"> $AAPL haha. Just can’t get positive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:55:57 </td>
   <td style="text-align:left;"> $BAND $TWLO $TQQQ $AAPL $ROKU 

Have you heard of this company called Bandwidth LLC, anybody have thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:53:48 </td>
   <td style="text-align:left;"> $AAPL buyer at $90 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:52:50 </td>
   <td style="text-align:left;"> How AI is Shaping the Cybersecurity Arms Race 
 
Read: https://www.channelchek.com/news-channel/Two_Ways_Artificial_Intelligence_is_Helping_Cybersecurity  
 
$MSFT $GOOGL $AAPL $NVDA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:52:07 </td>
   <td style="text-align:left;"> $AAPL this is just crap they way ot has been flipping back and forth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:51:05 </td>
   <td style="text-align:left;"> $AAPL this is so stupid. Just stay down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:50:25 </td>
   <td style="text-align:left;"> $AAPL let’s go positive! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:50:17 </td>
   <td style="text-align:left;"> $PLG Platinum group metals the rarest of metals will rock markets with new high coming fast in this economic warfare. $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:49:53 </td>
   <td style="text-align:left;"> When the Cult starts to get upset that you&amp;#39;re talking about Trump on a board thats about a stock he&amp;#39;s the main reason for you know they&amp;#39;re not happy. 
 
Whats next @yodone? You going to get upset w/ me talking talking about Tim Apple on the $aapl board? :o) 
 
#Triggred :o) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:48:41 </td>
   <td style="text-align:left;"> $AAPL 

Market very boring!!!

Tk’s Putin. MF. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:47:38 </td>
   <td style="text-align:left;"> $AAPL NICE! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:46:37 </td>
   <td style="text-align:left;"> $AAPL 4 minutes. FOUR MINUTES. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:46:23 </td>
   <td style="text-align:left;"> $AAPL 🖖🏽👹🐳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:46:17 </td>
   <td style="text-align:left;"> $AAPL woah☺️🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:43:44 </td>
   <td style="text-align:left;"> $aapl when is apple going to stop selling in Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:43:02 </td>
   <td style="text-align:left;"> $AAPL buffet hodling. if he starts to sell… shit show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:41:28 </td>
   <td style="text-align:left;"> $aapl &amp;gt;$164.07 close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:40:55 </td>
   <td style="text-align:left;"> $QQQ $AAPL ramp into close please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:40:53 </td>
   <td style="text-align:left;"> $MULN ok .. I bought a lot of calls on this even before doing any dd or anything. 
Their press release says first gen car will be Lithium ion and 2024 production ?? Second gen car will be solid state and 2025 ?? 

Earlier today I was wondering if it&amp;#39;s just a battery research company considering their tiny  market cap and tony float.  

But the above answered my question on why this was dropping to atl while entire bev / h2ev sectors were on a tear. 

I still think it has trading scope for few days  and if they are not lying, then some big co like $aapl should swoop them just for the tech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:40:45 </td>
   <td style="text-align:left;"> $AMZN $AAPL $NVDA $GOOG  
U.S. Oil Imports From Russia 
 
Whoopsies... 
 
Question heard on Capitol Hill: Who is willing to pay higher gas prices if we shut off the Russian oil spigot? 
 
Higher prices either way ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:39:51 </td>
   <td style="text-align:left;"> $AAPL  PE RATIO STILL HIGH REALTIVILY CNBC INTERVIEW   https://www.youtube.com/watch?v=IIczWj7BkS0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:37:36 </td>
   <td style="text-align:left;"> $KASHF 10% for Savings Account and up to 16% if you are active user and spend your cash with your card, this company and SP will get huuuuuge 🥳🔥🤪 $AMZN $AAPL $V </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:36:31 </td>
   <td style="text-align:left;"> Top Bullish Flow Today : 

$TSLA $DOCU $AAPL $VIX $SQ

🤖📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:35:55 </td>
   <td style="text-align:left;"> $AAPL sub 162 with the way this free falls without halt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:34:59 </td>
   <td style="text-align:left;"> $AAPL Under 160.00 Coming 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:34:45 </td>
   <td style="text-align:left;"> $AAPL went from positive 480 to negative 200 in calls in a matter of 2 minutes on this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:34:27 </td>
   <td style="text-align:left;"> $AAPL bloated little piggy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:34:19 </td>
   <td style="text-align:left;"> $AAPL pull coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:33:33 </td>
   <td style="text-align:left;"> $SPY $RSX $AAPL $GOOG $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:32:11 </td>
   <td style="text-align:left;"> $LCID what would be groundbreaking news for me: Lucid announces partnership with $AAPL to out-license its best-in-class EV battery tech. So they can get Project Titan off the ground while $LCID in-licenses Apple’s chip technology for better end-user customer experience. 
I can dream…
But More likely we’ll get updates on higher lucid Air reservations #s &amp;amp; plans for increased manufacturing capacity in AZ (decision on plant in SA or EU?)☘️💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:30:49 </td>
   <td style="text-align:left;"> $AAPL pumps and dumps and dumps again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:30:09 </td>
   <td style="text-align:left;"> $AAPL huge bad karma  coming for voters, media and others who put the retard Biden In office. Think of Ukraine people . That karma will come back to everyone who supported pos Biden . This never happens under trump . The world was safer. All this blood is on liberals hands . Remember this when your life goes to hell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:29:25 </td>
   <td style="text-align:left;"> Sanctions will continue~ 

Russia 🇷🇺 and Belarus 🇧🇾 banned from playing in the International Ice Hockey Federation.

#LGP 🏒🐧 🇺🇸 @CupCapsUP! 

$AAPL $AMD ↗️ $AMZN $BTC.x $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:28:29 </td>
   <td style="text-align:left;"> $AAPL  trigger the runtime buy bots quick little devils. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:26:38 </td>
   <td style="text-align:left;"> $AAPL  $muln Apple should just check it&amp;#39;s laundry basket , find some loose change and pay $5 per share for this company and buy it  before $tsla or $lcid even consider. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:25:03 </td>
   <td style="text-align:left;"> $awk $VTI $FIW $AAPL me donkey want wata </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:24:22 </td>
   <td style="text-align:left;"> $AAPL looking to add more on weakness 
 
give us 150 again! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:23:48 </td>
   <td style="text-align:left;"> $AAPL Chart Wars: Between Apple And Microsoft, Which Tech Stock Offers Better Risk-Reward? https://t.co/yRHfOVkXH8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:23:27 </td>
   <td style="text-align:left;"> $AAPL Run already past 165 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:20:00 </td>
   <td style="text-align:left;"> $AAPL Max pain last week = $165 , This week = $167.5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:19:05 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT I want my rally! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:18:17 </td>
   <td style="text-align:left;"> $AAPL this makes sense; Russia invades Ukraine so fewer people will buy iPhones.  sell!  Sell!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:16:31 </td>
   <td style="text-align:left;"> $QQQ best way to trade in this type of market is not to trade at all lol unless you’re crazy gifted $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:14:11 </td>
   <td style="text-align:left;"> $AAPL iPhone growth steadies in Europe as Samsung sales shrink - 9to5Mac https://9to5mac.com/2022/02/28/iphone-growth-steadies-in-europe-as-samsung-sales-shrink/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:13:43 </td>
   <td style="text-align:left;"> $MULN interesting “if” $AAPL 🙈😅👇🏼🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:13:25 </td>
   <td style="text-align:left;"> Chart Wars: Between #Apple And #Microsoft, Which Tech Stock Offers Better Risk-Reward? $AAPL $MSFT https://talkmarkets.com/content/stocks--equities/chart-wars-between-apple-and-microsoft-which-tech-stock-offers-better-risk-reward?post=346453 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:12:07 </td>
   <td style="text-align:left;"> $SPY So the people who panic sell to get cash because they are afraid of a nuclear war are thinking what? &amp;quot;when no one is left I&amp;#39;ll buy me a few drinks at the bar?&amp;quot; :o) 
 
If there was a nuclear war you wont be needing any cash so,.. BTD! :o) 
 
$aapl $bb $amzn $jpm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:09:54 </td>
   <td style="text-align:left;"> $AAPL dragonfly on 5m possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:06:48 </td>
   <td style="text-align:left;"> $AAPL a close sub 162 seems increasingly possible at this rate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:06:20 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:05:41 </td>
   <td style="text-align:left;"> $AAPL  nice support formed $163.06 watch open bell tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:04:28 </td>
   <td style="text-align:left;"> $VERB i think $AAPL is going to have Verb&amp;#39;s shoppable technology?  The pr is reading like that no? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:01:14 </td>
   <td style="text-align:left;"> $VERB omg is $VERB teaming up with $AAPL did that just come out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 04:00:42 </td>
   <td style="text-align:left;"> $AAPL break out watch lower now at </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:59:14 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:59:03 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:57:37 </td>
   <td style="text-align:left;"> $QQQ $SPY there is one company that could single-handedly end this war and that company is $AAPL no more iPhones for Russia and watch the people rise up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:55:52 </td>
   <td style="text-align:left;"> $AAPL if buyers aren’t rewarded soon then this is going back to the 155 range. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:52:05 </td>
   <td style="text-align:left;"> Chart Wars: Between Apple And Microsoft, Which Tech Stock Offers Better Risk-Reward? $AAPL $MSFT https://www.benzinga.com/trading-ideas/technicals/22/02/25881778/chart-wars-between-apple-and-microsoft-which-tech-stock-offers-better-risk-reward#.Yh0n2VNobUE.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:48:52 </td>
   <td style="text-align:left;"> May the beatings continue until 🇷🇺‘morale’ improves~ 

Russian oligarchs move super🛳 yachts as U.S. looks to &amp;#39;hunt down&amp;#39; and freeze assets!

$AAPL $AMD ↗️ $AMZN $BTC.x $ETH.x  https://www.cnbc.com/2022/02/28/russian-oligarchs-move-yachts-as-us-moves-to-hunt-down-and-freeze-assets.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:47:15 </td>
   <td style="text-align:left;"> $AAPL 

Putin’s last scare tactic is this convoy.

He knows he can’t win and the Russian military knows it’s defeated. 

Ceasefire in talks, then with sanctions lifted after Putin gets a Moscow cold from oligarchs.

Latest sanctions crippled entire country.

Putin is also like military, KAPUT! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:46:26 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Day 39: Rumor is OFG used his high education big $$$ intellect and realized a nuke might get launched so he headed underground into his bomb shelter almost 40 days ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:45:52 </td>
   <td style="text-align:left;"> $AAPL now that you bought the dip watch stops so you can lick your gains if this pulls back again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:43:09 </td>
   <td style="text-align:left;"> $SPY $DIA $AAPL $FB Can the Russian bots and trolls just have a massive nuclear war in the metaverse instead? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:43:05 </td>
   <td style="text-align:left;"> $AAPL keep buying dips a sell rips. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:41:27 </td>
   <td style="text-align:left;"> $SPY ...$msft and $aapl are making some massive downtrends right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:40:22 </td>
   <td style="text-align:left;"> $AAPL 162.25 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:40:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Electric Car Stocks: How To Use Finance Theory To Profit https://www.stck.pro/news/AAPL/23610221 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:39:18 </td>
   <td style="text-align:left;"> Most Traded Contracts

$AAPL 04 March $165 Call
$HTA March $32.50 Call
$TSLA 04 March $900 Call
$AAPL 04 March $167.50 Call
$AMD 04 March $125 Call
$AAPL 04 March $170 Call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:38:39 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY ....Down 1.4%.... The market doesn&amp;#39;t just go up anymore..... The chart matters more than it has over the past year and a half or so at this point... Simple lines over simple minds $STUDY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:37:36 </td>
   <td style="text-align:left;"> Ukrainian TB2 drone strike on the Russian military fuel train

https://www.cnn.com/europe/live-news/ukraine-russia-news-02-28-22/h_68c032cfbfafa2620426d90e9929cd62

$AAPL $QQQ $SPY $AMD latex946ade31f6f71f031d9cd2499c8af9a2AAPL 529k (59% call/41% put)
$AMD 445k (72% call/28% put)

Lynk in bayo for option trading ideas and alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:36:35 </td>
   <td style="text-align:left;"> $AAPL why the fuck does this keep happening to me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:36:11 </td>
   <td style="text-align:left;"> $AAPL confirmed below PMH, now we need to confirm below  ORL for more downside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:33:49 </td>
   <td style="text-align:left;"> $AAPL almost there, go down about 30 more cents and we will see what happens. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:33:18 </td>
   <td style="text-align:left;"> $SPY Just wait for those China/Taiwan headlines to roll in as the excuse for the 1-2 trillion unwinding in $aapl   that has to take place   &amp;gt;=) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:31:47 </td>
   <td style="text-align:left;"> $AAPL oh this is going to get bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:31:02 </td>
   <td style="text-align:left;"> $AAPL How does Russian crypto card MIR affect $AAPL if it is supposedly connected to Apple pay? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:30:56 </td>
   <td style="text-align:left;"> $AAPL I’m in love with Apple 🍏! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:29:57 </td>
   <td style="text-align:left;"> $AAPL update. We win. 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:28:42 </td>
   <td style="text-align:left;"> $AAPL why the drop all of a sudden?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:28:16 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMZN $FB $NFLX One of the best winning traders chat room, Join from here tinyurl.com/sktradingfreewinmop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:25:25 </td>
   <td style="text-align:left;"> $AAPL someones sweeping puts damn. They are taking my put credit spreads at ask.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:24:59 </td>
   <td style="text-align:left;"> $AAPL $140 next ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:24:29 </td>
   <td style="text-align:left;"> $AAPL what happened in the last 30 min?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:23:02 </td>
   <td style="text-align:left;"> $AAPL  - Upgraded today and down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:18:26 </td>
   <td style="text-align:left;"> $SPY When the entire Market moves in tandem you know its just  Algo &amp;amp; some PMs who sold to get cash &amp;amp; play safe 
 
Again EOM, lots of redemptions in Jan so cash is needed. Long Holders &amp;amp; Retail should be using this 
 
$baba $aapl $amzn $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:18:21 </td>
   <td style="text-align:left;"> Sanctions: 
Russia 🇷🇺 suspended from international soccer over Ukraine 🇺🇦 invasion 
&amp;gt;https://www.cnbc.com/2022/02/28/russia-suspended-from-international-soccer-over-ukraine-invasion.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard
$AAPL $AMD ↗️ $AMZN $BTC.x $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:16:10 </td>
   <td style="text-align:left;"> Calls: $AAPL $DIS 
Puts (short term): $SNAP $TSLA 

Usually bullish but Tesla went up too fast and Snap (recently) loves going sub 40 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:14:50 </td>
   <td style="text-align:left;"> $AAPL trend is starting to rotate down, not good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:14:21 </td>
   <td style="text-align:left;"> $AAPL dip bought!  Now let’s go back up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:12:32 </td>
   <td style="text-align:left;"> $AAPL the rejection came at a lower level than I expected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:12:30 </td>
   <td style="text-align:left;"> $AAPL bringing the whole market down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:12:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 8.00, indicating great health for $AAPL. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:12:00 </td>
   <td style="text-align:left;"> $AAPL $SPY tanking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:11:32 </td>
   <td style="text-align:left;"> $MULN Wonder what small elect auto company $AAPL could pair with that has the best battery system on the planet?  Just brainstorming. 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:11:30 </td>
   <td style="text-align:left;"> $AAPL reason nasdaq dropped 100 points in 10 mins?.? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:11:23 </td>
   <td style="text-align:left;"> $AAPL what’s happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:11:05 </td>
   <td style="text-align:left;"> Last week&amp;#39;s rally and today got the FOMO going. But did it suck in the max amount of participants?  
$QQQ $IWM $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:10:52 </td>
   <td style="text-align:left;"> $AAPL volitility , the new support will step in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:10:36 </td>
   <td style="text-align:left;"> $AAPL fucking bullshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:10:23 </td>
   <td style="text-align:left;"> $AAPL I hope y’all listened . PUTS ARE PRINTING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:10:01 </td>
   <td style="text-align:left;"> $AAPL $LAC Nothing to be done when they have the algo’s coordinated to market sweep dump…free market? 🤣😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:09:39 </td>
   <td style="text-align:left;"> $AAPL What a joke, if you watch FOX BUSINESS and monitor the charts,  you can see what direction this stonk is going.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:09:39 </td>
   <td style="text-align:left;"> $SPY this is so dumb...... flip out of puts into calls and this .... $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:09:25 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #4 stock that institutions are trading with 20.2K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:08:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $DJIA  
Do you want to understand why this leg down.   
Look at the calendar. Be prepared! 
Economic Events Calendar This Week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:08:17 </td>
   <td style="text-align:left;"> $AAPL seeking a bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:07:38 </td>
   <td style="text-align:left;"> $SPY We said &amp;quot;Watch the price action from 1:30-2:30 in the Market&amp;quot; 
This is why, its just the same Algo pattern w/ less Buy programs tight now 
 
$baba $jpm $aapl $bb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:06:11 </td>
   <td style="text-align:left;"> $AAPL Don’t you just love it when your right ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:04:42 </td>
   <td style="text-align:left;"> $AAPL &amp;quot;Apple Could Benefit From a New Dividend and Buyback Increase&amp;quot; - My latest article on Apple stock - Mark R. Hake, CFA, InvestorPlace - https://investorplace.com/2022/02/aapl-stock-could-benefit-from-a-potential-dividend-and-share-buyback-increase-announcement/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:04:21 </td>
   <td style="text-align:left;"> $AAPL incredible resilience at 163.80 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:04:12 </td>
   <td style="text-align:left;"> $AAPL 🌶️🌶️🌶️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:04:12 </td>
   <td style="text-align:left;"> $AAPL Need 165.5-166. Come on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:03:50 </td>
   <td style="text-align:left;"> Putin uses negotiations to buy time to have his nukes in place. Wake up Wall street. $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:03:44 </td>
   <td style="text-align:left;"> $AAPL fighting for its life, be careful if you are in a position. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:01:47 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Russia readying cyber attacks on new sanctions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:00:34 </td>
   <td style="text-align:left;"> $AAPL should set 52w lows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 03:00:05 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Market rolling over in the next 30 minutes. Nasdaq will close down 400-500 points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:59:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $GOOG that designated survivor tomorrow night with Russia having an axe to grind like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:57:10 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:57:08 </td>
   <td style="text-align:left;"> $AAPL 

Ceasefire in next 24 hours.

Russia is kaput. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:56:16 </td>
   <td style="text-align:left;"> $AAPL *phone posting beware* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:55:46 </td>
   <td style="text-align:left;"> $AAPL $FB $GOOG  Nancy conveniently lifted the congressional mask mandate in time for tomorrow nights SOTU. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:53:29 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL have been keeping track of the latest insights and alerts. This is one of the main positions in my portfolio. How are you guys feeling about it given current market conditions? 
 
I&amp;#39;m tracking all the news/alerts and other AI driven insights through my custom feed. Just add your tickers the watchlist and start receiving real-time customized investment insights. One of the best ways to stay on top of your portfolio and find new investment opportunities.  https://utradea.com/feed?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220228 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:51:28 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY  Goldman raises inflation outlook, sees 11 rate hikes through 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:50:29 </td>
   <td style="text-align:left;"> EOM Book dressing so look to see whats down for the Month &amp;amp; whats up, PMs will want to add what makes them look good &amp;amp; take off what doesn&amp;#39;t 
 
$aapl $dwac $jpm $lyv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:50:26 </td>
   <td style="text-align:left;"> $aapl Still contained within secular trend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:50:19 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

IM GONNA TAKE BULLS FOR A RIDE 

THEY WON’T FORGE!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:50:11 </td>
   <td style="text-align:left;"> $AAPL this has been dragging my portfolio down for months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:48:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 🐻🐻🐻🐻
Call J.G. Wentworth 🎵🎵
Call J.G. Wentworth 🎵🎵
Call J.G. Wentworth 🎵🎵
Call J.G. Wentworth 🎵🎵
877-CASH-NOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:48:44 </td>
   <td style="text-align:left;"> $AAPL watch for divergence here, otherwise… looking bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:47:10 </td>
   <td style="text-align:left;"> $AAPL Here it comes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:46:22 </td>
   <td style="text-align:left;"> $AAPL  getting ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:44:45 </td>
   <td style="text-align:left;"> $TSLA I now own so much Tesla $AAPL $AMZN and $GOOG as well as $ARKK that I will never need to work again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:42:02 </td>
   <td style="text-align:left;"> What&amp;#39;s On With Yandex Shares  $GOOG $GOOGL $AAPL $UBER $YNDX 

https://newsfilter.io/a/702c6d41471933f5cbc966366480ac78 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:42:02 </td>
   <td style="text-align:left;"> $AAPL $PLG   russia will begin to hoard PLATINUM GROUP METALS  key metal products </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:41:58 </td>
   <td style="text-align:left;"> $AAPL update on my poopy “phone” chart that has no value. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:40:53 </td>
   <td style="text-align:left;"> Google Inc. (NASDAQ: $GOOG), Google Inc. (NASDAQ: $GOOGL) – What’s On With Yandex Shares Today $AAPL $YNDX $UDER https://www.billionaireclubcollc.com/google-inc-nasdaqgoog-google-inc-nasdaqgoogl-whats-on-with-yandex-shares-today/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:39:09 </td>
   <td style="text-align:left;"> $AAPL real investors know what Apple does.  It’s ALL IN THE CHART. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:38:14 </td>
   <td style="text-align:left;"> $AAPL  time and price location 147pm $163.98 see some positron energy after the trigger event. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:37:54 </td>
   <td style="text-align:left;"> $AAPL watching for LL on price, but higher high on rsi here on 5m. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:36:20 </td>
   <td style="text-align:left;"> $AAPL harderrrrrr 👊🏼👊🏼👊🏼👊🏼👊🏼🙏🏻🙏🏻❤️❤️❤️‼️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:34:58 </td>
   <td style="text-align:left;"> $AAPL  bidens weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:34:51 </td>
   <td style="text-align:left;"> $AAPL watching for divergence here for buy opp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:34:37 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:30:01 </td>
   <td style="text-align:left;"> $PLG $TSLA  $AAPL PLG battery TECH LIONS BATTERY.  no more margin call raids in TSLA  so begin 2 week buy program. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:30:01 </td>
   <td style="text-align:left;"> $MULN APPLE JUST BUY THIS COMPANY THEY ALREADY HAVE THE CAR AND YOU HAVE THE TECH. They also have the next generation battery for the EV market $AAPL https://www.macrumors.com/roundup/apple-car/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:29:41 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:29:36 </td>
   <td style="text-align:left;"> My latest blog, “Take Profits In Berkshire Hathaway”, is available:

https://www.topgunfp.com/take-profits-in-berkshire-hathaway/

$BRK.A $BRK.B $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:29:10 </td>
   <td style="text-align:left;"> $AAPL large volume today when price went under the range it’s been playing. Sideways until supply/demand is worked out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:26:07 </td>
   <td style="text-align:left;"> $AAPL needs to get confirmation below PMH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:24:13 </td>
   <td style="text-align:left;"> $AAPL wtf is going on here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:23:56 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Dutch Antitrust Body Hits Apple With Sixth Fine of $5.7M https://www.stck.pro/news/AAPL/23607081 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:23:06 </td>
   <td style="text-align:left;"> This is amazing! What do you think? $AAPL in Uptrend: RSI indicator exits oversold zone. View odds for this and other indicators: https://srnk.us/go/3454321 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:22:14 </td>
   <td style="text-align:left;"> $AAPL  good chart . Im buying with $impl  for my best gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:17:33 </td>
   <td style="text-align:left;"> $AAPL just don’t see much higher here. Gonna retest at least that 155 level, but I think this weekly and monthly soon as well needs to reset back down 140 first then 115. Just like everything else, looking for resets to go higher, or sit for a long time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:17:11 </td>
   <td style="text-align:left;"> $AAPL Apple won&amp;#39;t see a short term reversal, until it breeches $166.20 .  Restrict the Algorithm BOTS and it would gap up to be a 3 trillion dollar company over night...this  to obvious.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:10:27 </td>
   <td style="text-align:left;"> $AAPL look how it rapidly fell outside of the upward trend and snapped back!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:10:25 </td>
   <td style="text-align:left;"> $AAPL little dip don’t last long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:10:06 </td>
   <td style="text-align:left;"> $AAPL $TSLA $FB $NVDA Bulls, be careful where you put your money in these hours. War is not over at all and NOBODY can predict Putin&amp;#39;s next move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:08:38 </td>
   <td style="text-align:left;"> $AAPL 

Forget the Noice....Extremely Bullish as you see via Option Contracts / Technicals / Sweeps !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:07:57 </td>
   <td style="text-align:left;"> $AAPL I believe the bottom is in and could go parabolic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:06:51 </td>
   <td style="text-align:left;"> $AAPL support moving up,  now the plan is to trigger shorts buy to cover ATM orders, apple buy back money and  create emoitional FOMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:03:39 </td>
   <td style="text-align:left;"> $AAPL time for a big break to the upside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:02:35 </td>
   <td style="text-align:left;"> $AAPL I wonder if $AAPL is helping NATO and hacking into iphones held by key Russian officials?  Getting audio and video? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:01:29 </td>
   <td style="text-align:left;"> $AAPL zoomed out more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:00:32 </td>
   <td style="text-align:left;"> $AAPL This is Apple, a company with 2.8 trillion Market cap ,struggling like a Penny stock, they say never bet against America, but is America ALGO BOTS betting against US. $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 02:00:27 </td>
   <td style="text-align:left;"> $AAPL hmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:59:00 </td>
   <td style="text-align:left;"> $AAPL they refuse to drop low enough to fill my spreads lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:57:59 </td>
   <td style="text-align:left;"> $AAPL I feel like Apple needs to join its friends below the 200 dma... $GOOGL $MSFT $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:55:55 </td>
   <td style="text-align:left;"> $AAPL gonna test 163.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:54:39 </td>
   <td style="text-align:left;"> $AAPL holding nice! 
#KSCP security company!  
#AABB next run 🍋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:54:35 </td>
   <td style="text-align:left;"> $AAPL Use Honeygain to share your unused broadband DATA for BTC, proven payments below   
  
r.honeygain.me/DJYUJ4BA01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:54:26 </td>
   <td style="text-align:left;"> $AAPL look at $TSLA  no more margin calls, apple will be same way with apple car news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:53:09 </td>
   <td style="text-align:left;"> $AAPL $ABNB This is obviously not humans buying and selling stocks at these rates,  the Algorithm BOTS are suppressing the market,  Enjoy the PUTS ,while they are printing.. The FAANG effect.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:51:54 </td>
   <td style="text-align:left;"> $AAPL pump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:51:40 </td>
   <td style="text-align:left;"> $AAPL https://www.businessinsider.com/ukraine-minister-tim-cook-block-apple-app-store-russia-2022-2?amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:50:29 </td>
   <td style="text-align:left;"> $AAPL  Inverse H&amp;amp;S &amp;amp; C&amp;amp;H on the 90d off of a double bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:48:24 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:46:52 </td>
   <td style="text-align:left;"> $AAPL Was 166 too much to ask for?!?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:46:44 </td>
   <td style="text-align:left;"> $AAPL market capitulation coming. Got all you bulls in at market high today. Now you’re toast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:46:27 </td>
   <td style="text-align:left;"> Market rejection incoming? Bull trap? What do you think??? 
 
$SPY $NASDAQ $TSLA $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:46:26 </td>
   <td style="text-align:left;"> $SPY Bullish right? Don&amp;#39;t mention the bond program ending today, and subsequently the fed selling starting in May $AAPL $IWM $AMZN $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:45:55 </td>
   <td style="text-align:left;"> $AAPL It has already tested $150. So you all know what is coming!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:45:18 </td>
   <td style="text-align:left;"> $AAPL  Reversal &amp;amp; bounce at the bottom of the over extended linear regression channel where reversals always &amp;amp; imminently occur &amp;amp; now in an Elliott wave 1 up with a buy signal on the mesa sine wave &amp;amp; all indicators a go &amp;amp; the ADX showing trend strength. Looks like this goes to 178 on the wave 1.  Launch time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:44:53 </td>
   <td style="text-align:left;"> $AAPL Wait for it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:44:14 </td>
   <td style="text-align:left;"> $AAPL 180+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:43:48 </td>
   <td style="text-align:left;"> $TSLA $AAPL tech crash imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:41:58 </td>
   <td style="text-align:left;"> $SPY This whole market is a scam, banks trying to get you to buying 25% higher than where you should, so they can boost their short term calls $AAPL $AMC $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:41:13 </td>
   <td style="text-align:left;"> $AAPL No American has done more to boost Putin&amp;#39;s personal image and brand in the United States than ____________. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:40:58 </td>
   <td style="text-align:left;"> $AAPL this stock just refuses to go down. What gives </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:38:27 </td>
   <td style="text-align:left;"> Netflix, Inc. (NASDAQ: $NFLX), Apple Inc. (NASDAQ: $AAPL) – ‘Ozark’ Joins Rare Company With 4 Billion Minutes Streamed In A Week As Netflix Continues To Dominate https://www.billionaireclubcollc.com/netflix-inc-nasdaqnflx-apple-inc-nasdaqaapl-ozark-joins-rare-company-with-4-billion-minutes-streamed-in-a-week-as-netflix-continues-to-dominate/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:36:22 </td>
   <td style="text-align:left;"> $TDOC can we get Siri $AAPL deal too? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:36:21 </td>
   <td style="text-align:left;"> $AAPL no results </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:36:16 </td>
   <td style="text-align:left;"> $AAPL get in guys bitcoin is leading the way.  https://www.coindesk.com/price/bitcoin/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:34:54 </td>
   <td style="text-align:left;"> $AAPL Watching to see how this resolves...My bias is to the downside...$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:34:39 </td>
   <td style="text-align:left;"> $AAPL talks ended </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:33:05 </td>
   <td style="text-align:left;"> It looks like it is going to get worse before there is sunshine and rainbows 👎

Goldman raises inflation outlook, sees 11 rate hikes through 2023

$AAPL $AMD $NVDA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:32:02 </td>
   <td style="text-align:left;"> $SPY ⚡️ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:31:10 </td>
   <td style="text-align:left;"> $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:31:08 </td>
   <td style="text-align:left;"> $AAPL Worst stock of the day 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:30:30 </td>
   <td style="text-align:left;"> $AAPL 

Brace Yourself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:26:14 </td>
   <td style="text-align:left;"> $AAPL if you know when all the stop loss orders have been triggered and know remain you know when the bottom will be. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:25:29 </td>
   <td style="text-align:left;"> $spy Every Quant &amp;amp; Momo Trader has to work the 12-1 time zone. They need to shake hard &amp;amp; are def trying because they can see the Market is being bought so,.. just a little test during the weakest time of the day. 
 
1:30 into 2pm should be interesting since we had so many Put Buyers last 2 weeks, that can also move Markets higher, lets see 
 
$aapl $amzn $b $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:25:01 </td>
   <td style="text-align:left;"> &amp;#39;Ozark&amp;#39; Joins Rare Company With 4 Billion Minutes Streamed In A Week As Netflix Continues To Dominate  $NFLX $NLSN $DIS $AMZN $AAPL 

https://newsfilter.io/a/4059c98785a5ca2ff4baee700b104bd4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:24:48 </td>
   <td style="text-align:left;"> Today&amp;#39;s Most Traded Contracts: 
 
- $HTA 3/18 32.5 call 
- $AAPL 3/04 165 call 
- $TSLA 3/04 900 call 
- $AMD 3/04 125 call 
- $AAPL 3/04 167.5 call 
- $AAPL 3/04 170 call 
- $BAC 4/14 47 call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:24:16 </td>
   <td style="text-align:left;"> Top Bullish Flow (a/o12:23pmEST): $AAPL $DIS $GOOGL $MSFT $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:23:40 </td>
   <td style="text-align:left;"> $XCUR $TSLA $AAPL come join the XCUR party! Just about to get good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:22:41 </td>
   <td style="text-align:left;"> $AAPL harderrrrrr up👊🏼👊🏼👊🏼🙏🏻🙏🏻🙏🏻🙏🏻🙏🏻❤️❤️❤️❤️🍏🍏🍏🍏🍏‼️‼️‼️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:21:49 </td>
   <td style="text-align:left;"> $AAPL fight it you whore! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-01 01:19:28 </td>
   <td style="text-align:left;"> 💎🕰🕰

In life nothing happens by chance.  It may appear so but there is always something at play somewhere.   Much of it cannot be seen.  

While many investors may not see the connection between the location of this plant and $TSLA, that’s ok — many others can and will benefit by such a move.  

There are many, many people who can’t  make the connection between people, connections are there and in fact they make the biggest moves.    Many, many people can’t draw conclusions for situations and the impact there of.  

When you start to make small connections between your equities such as $AMZN $AAPL $NIO and you keep them, you will begin to figure out a winning structure for you portfolio — you just need to learn to have patience.    

If you then add global problems to your investments you begin to form a picture, and if you begin to understand what you are looking at, you will see success.  

If you start to accumulate here and hold, then everything is unchanged.  

Good luck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:42:29 </td>
   <td style="text-align:left;"> $SPY Closed the month down 3.17% bringing the decline to 8.23% on the year. This is the first time that the $SPY dropped in consecutive months since September-October of 2020. 
 
$QQQ $AAPL $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:39:48 </td>
   <td style="text-align:left;"> $NIO $TSLA 

For call and put option analysis follow @ https://t.me/tigerprofit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:35:50 </td>
   <td style="text-align:left;"> $TSLA shoulda bought more on Putin Day 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:35:17 </td>
   <td style="text-align:left;"> $TSLA 1000 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:35:13 </td>
   <td style="text-align:left;"> $TSLA Over 900 tomorrow 🙏😀 let’s do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:34:16 </td>
   <td style="text-align:left;"> $TSLA 35K ON X 3 LEVERAGED TSLA 2DAY after 25 k on x 3 lev last week. tsla gonna eradicate need 4 russia oil and power.  its gonna blow upwards big time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:33:36 </td>
   <td style="text-align:left;"> $TSLA took a last minute scalp bought at 3:55 sold 3:58 EST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:32:49 </td>
   <td style="text-align:left;"> Load O&amp;#39; clock. $DJIA futes printing. $NCLH is way overdue. Let&amp;#39;s goooo!!! Good news ahead. $MSFT investment seems always a good idea. $TSLA calls printed fat wow!!! $SNDL a dog always has it&amp;#39;s day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:31:12 </td>
   <td style="text-align:left;"> $TSLA 900 open?😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:29:50 </td>
   <td style="text-align:left;"> SpaceX has been awarded a $3.5 billion contract from NASA for 9 flights through 2028

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:29:28 </td>
   <td style="text-align:left;"> $TSLA sorry guys its dumping tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:27:36 </td>
   <td style="text-align:left;"> $TSLA with gas prices this high people everywhere will be buying Tesla. Buy a Tesla and get a free FJB sticker </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:26:23 </td>
   <td style="text-align:left;"> $TSLA https://schrts.co/hKTxPETD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:25:30 </td>
   <td style="text-align:left;"> $NCLH fair value 35 to 40 range ceo just said covid is beyond them basically and that they are able to move forward very soon in full operation. This was 54 range pre covid. $TSLA  $SNDL $NIO top 3 picks moving forward let&amp;#39;s go!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:25:00 </td>
   <td style="text-align:left;"> $TSLA When there’s blood” literally on the streets” you hammer down and the living#%#€ 🥂😎🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:24:28 </td>
   <td style="text-align:left;"> $TSLA I hope whoever was short or always with their bearish shit that y’all call them out 😂. Screen shoot their crap and tags them 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:24:25 </td>
   <td style="text-align:left;"> $TSLA obviously </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:24:22 </td>
   <td style="text-align:left;"> $SPY The next news to hit would be &amp;quot;talks fail&amp;quot; .... BTFD ... as next day it would read &amp;quot;Zelensky surrenders&amp;quot; $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:24:18 </td>
   <td style="text-align:left;"> $TSLA This Bitch below Might wake up a little mad tomorrow at Elon for help in the Ukraine…Short it lol I’m kidding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:21:59 </td>
   <td style="text-align:left;"> $TSLA I like how when i got to $SPY mfs be arguing over if bears or bulls are gonna win but at $TSLA everyone is Bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:20:56 </td>
   <td style="text-align:left;"> $TSLA is Elon going to have an announcement tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:19:00 </td>
   <td style="text-align:left;"> $DE, $TSLA and $ETSY are the top gainers in the S&amp;amp;P500 for the day. https://www.chartmill.com/stock/stock-screener?v=3&amp;amp;f=ind_22&amp;amp;s=pt&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_top_S&amp;amp;P500_gainers&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:18:52 </td>
   <td style="text-align:left;"> $TSLA movin higher afterhours 🤑🤑🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:18:32 </td>
   <td style="text-align:left;"> $ICLN $TSLA http://WolverineVentureCapitalLLC.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:17:39 </td>
   <td style="text-align:left;"> $PLUG $tsla $arkk $f $NVDA  
 
If Putin will kill his own brothers, then what will he do to Americans? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:17:39 </td>
   <td style="text-align:left;"> $TSLA  $900 🤑🤑🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:17:37 </td>
   <td style="text-align:left;"> $AMC $EVGO $AABB $GME $TSLA DO WHY GARY? #enforcement #fairmarkets  https://www.reddit.com/r/amcstock/comments/sjwt85/im_sorry_what_happens_when_i_place_a_market_order/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:17:36 </td>
   <td style="text-align:left;"> Seems like $TSLA is the only car company w even a slight clue as to how to manage the supply chain. $LCID $F $GM looking clueless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:16:21 </td>
   <td style="text-align:left;"> Team Bullish Alerts for 02/28/2022
Days Realized Gain: +$8235.00

$MULN
Alert/Entry: $1.05
Closed: $1.75
Realized Gain: +$2550 
Scaled entry at the bell, hit my price target 4 of $1.75 in the afternoon.

$TSLA $900C 03/04/2022
Entry: $3
Closed: $6.35
Realized Gain: +$5400
Made entry at the bell for our small account options challenge. Premium ran to a $15.65 high, making another play tomorrow. 

$DSS
Entry: $0.44
Closed: $0.52
Realized Gain: +$285
Identified the double top at the $0.44 before it broke out to its days high of $0.684.

https://linktr.ee/TeamBullishTrading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:14:44 </td>
   <td style="text-align:left;"> $TSLA A lot of bad EV earnings after the bell, that&amp;#39;s why investors should stick with the traditional car names like Ford and GM rather than the overvalued one like Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:14:15 </td>
   <td style="text-align:left;"> $MULN how is this technology not worth billions to $TSLA ?? $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:13:42 </td>
   <td style="text-align:left;"> $TSLA stock is gonna run like crazy from here on out not going to stop much, factories, 4680, margins, fsd, then cyber, then bot, rinse &amp;amp; repeat many thousands coming sooner than people think </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:13:30 </td>
   <td style="text-align:left;"> $TSLA papa Elon take me to financial freedom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:12:49 </td>
   <td style="text-align:left;"> $TSLA Shorts!! 
 
+4 Points after Bell (Berlin gigafactory opening soon!) 
Then Austin, Texas US  opens +up this year!! 
 
We will beat every earnings after that (Shanghai factory to produce 1 million EV cars every year!) 
 
Missing an earnings will be a thing of the past! 
 
Have a good evening Shorts!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:12:48 </td>
   <td style="text-align:left;"> $TSLA what normally happens after a 3Sd move? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:11:49 </td>
   <td style="text-align:left;"> $MULN just hope $TSLA doesn’t buy this out at $3.00.   This is the Microsoft of batteries, EV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:11:44 </td>
   <td style="text-align:left;"> $TSLA 

Bears are in for extreme pain tomorrow. 

Tesla will announce openings of Berlin and Austin in March. The run up has started. 

Tesla is immune to staggering oil prices. In fact Tesla is the answer. 

Bears had their moment. It’s over. 
Spend your winnings wisely. 

Thanks to Elon for providing Internet services to Ukraine. He is a godsend to those people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:11:35 </td>
   <td style="text-align:left;"> $TSLA Tesla is killing it. Something told me to buy more calls. No lie, thought the Russia garbage wasn’t gonna let’s us fly and just keep bouncing low to high until it was over. My $810 call up 200%. Insane </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:11:13 </td>
   <td style="text-align:left;"> $STRR ⬆️ 🚀 

$MULN $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:08:34 </td>
   <td style="text-align:left;"> $TSLA   Dishy McFlatface to the rescue !   Nicely done. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:07:53 </td>
   <td style="text-align:left;"> $TSLA if Futures open green tomorrow 📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:07:47 </td>
   <td style="text-align:left;"> $TSLA damn congrats bulls !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:07:43 </td>
   <td style="text-align:left;"> $SPY I have been a bull all through last week, but now I am getting worried about this Russian war, Putin is  being pushed into corner - Zelensky refuses to surrender, World arming Ukraine more... This might bring out some deperate moves from Putin which is not good.... hope they resolve it through talks... $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:07:27 </td>
   <td style="text-align:left;"> $TSLA When the leaders of other countries call Elon to fix internet trouble during war??? Fuck off haters u have no idea!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:07:04 </td>
   <td style="text-align:left;"> $LCID hey dummies..the next Tesla is $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:06:41 </td>
   <td style="text-align:left;"> $TSLA supply chain issues will plague this in the S/T, not sure when that will be factored in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:06:33 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $AMD 

Does anyone know the Ticker for the inverse ETF for Cramer? 

Can’t find it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:06:04 </td>
   <td style="text-align:left;"> $TSLA 
📆📈📚💵
Option trades, Monday recap 2/28 🎯📈

QQQ 340P +22%
QQQ 347C +82%
QQQ 345P +153%
QQQ 342P +13%
QQQ 344C -35%

Tweet speaks for itself 🤷🏾‍♂️ don’t miss out on the next free alert!!!
💰💸

https://twitter.com/q_alerts/status/1498431545513816069?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:05:54 </td>
   <td style="text-align:left;"> $TSLA thanks papa Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:04:48 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:03:41 </td>
   <td style="text-align:left;"> $TSLA up almost 25% in 3 trading sessions, LCID earnings revealed supply chain issues incoming for auto industry. $750 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:01:16 </td>
   <td style="text-align:left;"> $PLTR $SPY $NIO $TSLA 

Sheesh. Just check for the first time lol. My account is down 24% in the past 3 months. Been brutal. Hopefully we turn around soon cause I’ve been loading these dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:01:00 </td>
   <td style="text-align:left;"> Amazingly, @Stocktwits censors deleted this message, supposedly because &amp;quot;Please do not include a TICKER in your message unless you&amp;#39;re sharing an idea specific to that name&amp;quot;. First of all, most of the messages on $TSLA $AMC etc are devoid of contents that could even remotely be considered an &amp;quot;idea&amp;quot;. Second of all, I made my idea clear. Short the stock. How&amp;#39;s that not an idea specific to $TSLA? 
I find it puzzling that Stocktwits is engaging in this kind of censorship just because $TSLA teslemmings are upset and have been reporting messages that are negative on the stonk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 08:00:55 </td>
   <td style="text-align:left;"> $TSLA sub $800 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:59:51 </td>
   <td style="text-align:left;"> $SPY $TSLA 
Russia&amp;#39;s nuclear forces put on &amp;#39;enhanced combat duty&amp;#39; - as peace talks end on Belarus border

https://news.sky.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:59:10 </td>
   <td style="text-align:left;"> $TSLA Russia Suspended Stock Trading. Expect Big Losses When Markets Reopen. https://www.marketwatch.com/articles/expect-big-losses-when-russian-markets-reopen-51646090918?reflink=share_barrons_twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:57:59 </td>
   <td style="text-align:left;"> $MULN this is kind of like a baby $TSLA - heck, those guys might want to take this over just because of the batteries... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:57:04 </td>
   <td style="text-align:left;"> $TSLA ✅✅✅✅✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:56:17 </td>
   <td style="text-align:left;"> $LCID Ya&amp;#39;ll said the same shit 10 years ago about $TSLA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:56:15 </td>
   <td style="text-align:left;"> $AMZN $TSLA 
WELL AS LONG AS POWELL IS ALIVE, THE SELL BUTTON MAKES NO SENSE.  PH.D in Pumping. 

COVID, INFLATION, WAR, Supply Chain/Labor Shortage, Housing does not matter. If Wednesday testimony tone is dovish, we shall see another madness BTMFD for short term.. UNTIL NEXT ER reporting big tech. 
FORD, LUCID, GM all suspended/lowered guidance except Tesla. This news is no news now. 

https://www.cnbc.com/2022/02/28/russia-ukraine-latest-updates.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:55:24 </td>
   <td style="text-align:left;"> $TSLA 
💨🅿️➡️💰📈
Option trades, Monday recap 2/28 🎯📈

QQQ 340P +22%
QQQ 347C +82%
QQQ 345P +153%
QQQ 342P +13%
QQQ 344C -35%

Tweet speaks for itself 🤷🏾‍♂️ don’t miss out on the next free alert!!!
💰💸

https://twitter.com/q_alerts/status/1498431545513816069?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:54:26 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #2 ticker with sweep activity where institutions are trading options urgently with 31.9K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:54:01 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Where’s my bear gang at? 😢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:53:56 </td>
   <td style="text-align:left;"> latexd5ff3708cc68d41a15abb33b7ecd9857AAPL 841k (56% call/44% put)
$AMD 628k (71% call/29% put)

Lynk in bayo for option trading ideas and alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:51:27 </td>
   <td style="text-align:left;"> $tsla rally it just above 50d before 🐑 slayer mode activated?   🐑 emotions running high in da Turing test????  It’s bahhhhcoining!!!!   🍿

❤️👑🌈🦄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:49:56 </td>
   <td style="text-align:left;"> biggest moves was mentioned pre market before it happened, u name it we trade it $SPY $TSLA $FB $MRNA  Link in bio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:49:51 </td>
   <td style="text-align:left;"> $TSLA bears, here&amp;#39;s your ammo. Go get em. https://www.kmbc.com/article/independence-missouri-tesla-crash-mechanical-issue-i-70-man-killed/39262712?utm_campaign=snd-autopilot# </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:49:01 </td>
   <td style="text-align:left;"> $TSLA pit buyers are so happy 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:48:44 </td>
   <td style="text-align:left;"> $TSLA i do expect a dip tomorrow, but I do expect a run after prolly dip at open then run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:47:55 </td>
   <td style="text-align:left;"> $TSLA bull flag up to 900 tomorrow 🤷🏼‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:45:58 </td>
   <td style="text-align:left;"> $TSLA BREAKING NEWS: &amp;quot;Every other EV company is a joke. Shit, every other auto company is a joke. Oh wait... this isn&amp;#39;t news.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:45:34 </td>
   <td style="text-align:left;"> $TSLA sounds crazy but hear me out… $1000 by friday next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:45:26 </td>
   <td style="text-align:left;"> $TSLA TSLA Stock Price  Prediction and Analysis for Tomorrow March 1st
https://youtu.be/XJCUrGat7pw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:44:20 </td>
   <td style="text-align:left;"> $TSLA bitcoin going and if this goes over $900 tomorrow ill be hypeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:43:45 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMZN 

A huge convoy of Russian armour, nearly 17 miles long, is advancing on Ukraine&amp;#39;s capital Kyiv, satellite images show

https://www.bbc.com/news/live/world-europe-60542877 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:43:17 </td>
   <td style="text-align:left;"> $TSLA NEWS - TSLA Expands Shanghai Production: 
https://www.youtube.com/watch?v=Dnm3uAGtCU4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:43:08 </td>
   <td style="text-align:left;"> $TSLA Tesla helping Ukraine will drive the stock higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:42:48 </td>
   <td style="text-align:left;"> $LCID welp atleast im holding $tsla calls lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:40:01 </td>
   <td style="text-align:left;"> $TSLA 

Please hit $900… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:39:17 </td>
   <td style="text-align:left;"> $TSLA where are the bears? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:38:50 </td>
   <td style="text-align:left;"> $TSLA 

No EV manufacturer can do what Tesla can do. 

Berlin
Austin

Gigafactories are going to pump out cars and trucks and Robots. 

Get ready. 

Elon has never let anyone down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:38:29 </td>
   <td style="text-align:left;"> $TSLA 

@elonmusk dropping off Starlinks for Ukraine!!

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:37:29 </td>
   <td style="text-align:left;"> $TSLA huh bears you told itnwas going to 250 dollar? Haha retardsss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:36:40 </td>
   <td style="text-align:left;"> $LCID $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:36:34 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ

Where the Tesla/Elon haters at?

Thought it was a PR stunt or elon wouldnt deliver?

It took only a matter of days! 

Stop complaining when others are trying to do something good. Even if it takes longer than expected. 

I dont see yall doing shit but complain and hate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:33:06 </td>
   <td style="text-align:left;"> $TSLA good to know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:32:05 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #25 ticker with unusual activity from institutional traders with an average of 16% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:29:32 </td>
   <td style="text-align:left;"> $TSLA Collected 14K today selling puts.  Honest day&amp;#39;s work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:29:00 </td>
   <td style="text-align:left;"> $LCID  is $25.00  which is on sale at this point.  Consider this as,  a new IPO and own the stock asap.  Accumulating this stock will enable us  good returns in coming years. Recall same time frame Feb last week 2021 people paid around $60 to $65  without any product. Now production started and got orders in hand, every thing is aligned for deliveries. I don&amp;#39;t see the issue in owning the stock at this point.  This is an alternate choice for $TSLA in my opinion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:28:19 </td>
   <td style="text-align:left;"> $TSLA big day tomorrow. big week ahead. 

back to ATH in no time. 

don’t fuck with elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:25:20 </td>
   <td style="text-align:left;"> $TSLA are my puts good or no </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:23:48 </td>
   <td style="text-align:left;"> $TSLA come a little closer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:22:59 </td>
   <td style="text-align:left;"> $TSLA tomm gonna be huge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:22:39 </td>
   <td style="text-align:left;"> $TSLA BRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:22:34 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/Uct-3MZQlAk
$Lcid $ride $F 

Very interesting Review </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:21:25 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TSLA yall ever look at TSLA yearly chart lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:21:10 </td>
   <td style="text-align:left;"> $LCID compare this call with $RIDE ,$NIO, $TSLA .. and you will see why your money is worth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:20:02 </td>
   <td style="text-align:left;"> $TSLA nice close! Rock&amp;amp;roll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:19:29 </td>
   <td style="text-align:left;"> $TSLA This guy is a hero forcing admiration. Hats Off to Elon on certain aspects!  
https://www.cnbc.com/2022/02/28/ukraine-updates-starlink-satellite-dishes.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:17:26 </td>
   <td style="text-align:left;"> $TSLA some entity is shorting this everytime it hits the 20 ema </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:17:22 </td>
   <td style="text-align:left;"> $TSLA fyre festival 🎎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:17:06 </td>
   <td style="text-align:left;"> $TSLA been in Dubai for 10 days. Seen many so Teslas, especially Model x. Didnt see any other electric cars but Teslas. I did see many advertising  about Lucid and their factory. Also many ubers in dubai drive Tesla model x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:16:51 </td>
   <td style="text-align:left;"> $SPY $TSLA $PLTR $BTC.X 

Up a rack today thank you shorts for piling on and adding more fuel to the fire. All time highs for market coming soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:16:50 </td>
   <td style="text-align:left;"> $TSLA It was a good day. Made money, held the fucking line, and best of all, bear put holders got RAILED💪🏽📈Cheers!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:16:19 </td>
   <td style="text-align:left;"> $TSLA you gotta love how we stopped at the 20 day again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:14:40 </td>
   <td style="text-align:left;"> $TSLA and heeerrrrre we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:13:49 </td>
   <td style="text-align:left;"> $TSLA this will drop tmw while amazon climbs you can screenshot this for accuracy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:13:45 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $DJIA 

The real question is does dr. burry fear tom lee or does tom lee fear dr. burry?...

🧸 vs 🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:12:03 </td>
   <td style="text-align:left;"> $TSLA shorting Tesla is truly un-American </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:11:26 </td>
   <td style="text-align:left;"> $TSLA saudi invested in $lcid! lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:09:47 </td>
   <td style="text-align:left;"> $TSLA steam gaming on tesla👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:09:32 </td>
   <td style="text-align:left;"> $RTX going to keep flying with war going on, calls printing daily! Could see $115+ in the next week or two $AAPL $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:09:11 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-28 Daily Forecast Video: 
https://www.youtube.com/watch?v=usN4K006AYY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:09:06 </td>
   <td style="text-align:left;"> $TSLA 2/24 🩸discount
Prices 📉🛒🧘‍♂️💥🔁💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:08:00 </td>
   <td style="text-align:left;"> $TSLA dang bears today salty 😆 Well seeing how 880 area works out tomorrow! That would be huge if we break above and hold imo!!! Let’s go!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:07:14 </td>
   <td style="text-align:left;"> $FB $AAPL $TSLA  $MSFT $CCL 
…………………………………………Has anyone of you noticed that the Russian stock market is closed until the 5th of March?   
Think about why for a moment.  
That market would have completely collapsed if it was open.  
But” if one thing could change, or a event were to happen before then of great significance” then that market could stabilize. 
  It seems Vladimir Putin is betting on something….  
Before it’s opened so it doesn’t collapse.   Thoughts anyone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:06:37 </td>
   <td style="text-align:left;"> $TSLA Short Squeeze tomorrow looking forward on updates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:05:08 </td>
   <td style="text-align:left;"> $MULN better then $tsla not even joking , wow why this stock was hiding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:03:57 </td>
   <td style="text-align:left;"> $DOGE.X $COIN $HOOD $TSLA 
eBay eBay eBay

https://www.benzinga.com/markets/cryptocurrency/22/02/25871566/ebay-could-soon-accept-bitcoin-ethereum-and-dogecoin-for-payments-report?utm_campaign=partner_feed&amp;amp;utm_source=robinhood.com&amp;amp;utm_medium=partner_feed&amp;amp;utm_content=ticker_page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:03:41 </td>
   <td style="text-align:left;"> $TSLA looks like it’s going to fall again due to the 3and 6 month pattern but only time will tell, I’ll keep loadin the boat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:03:12 </td>
   <td style="text-align:left;"> $TSLA New York - can&amp;#39;t outrun a Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 07:01:36 </td>
   <td style="text-align:left;"> Ooooooooo $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:58:18 </td>
   <td style="text-align:left;"> If $TSLA can hold over today&amp;#39;s high, it was room to run to $887.5 -&amp;gt; $904.6 -&amp;gt; $918 next.. 🟢 
 
Under $853 leaves room to $836 -&amp;gt; $822 -&amp;gt; $804 is market decides to give it all back. 🔴 
 
Plan shared last night worked SOOOO GOOD!!!  
 
https://discord.com/invite/Ur4e5Vc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:57:26 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:57:25 </td>
   <td style="text-align:left;"> $TSLA $LCID investors make your money back.  Buy $TESLA.  It is starting to get its grove back! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:56:55 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/SawyerMerritt/status/1498431775546265601 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:56:51 </td>
   <td style="text-align:left;"> $TSLA some people really thought lucid would be the next Tesla. Those Saudi’s gona pull out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:55:53 </td>
   <td style="text-align:left;"> Top UOA of the day 🔮
$UPST $6.9 Million buyer of the 5/20 135 puts  
$TSLA $4.2 Million buyer of the 1/19/24 1500 calls 
$COIN $1.7 Million buyer of the 4/14 175 calls 
$V Two orders totaling $2.6 Million of the 5/20 220 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:54:25 </td>
   <td style="text-align:left;"> $TSLA took profit on puts written on dip to 700 , moved to nearterm lotto calls today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:53:38 </td>
   <td style="text-align:left;"> $TSLA pump time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:53:19 </td>
   <td style="text-align:left;"> $TSLA  is MORE than EV.  We have have a creative leader that is also hell of a person.  Thanks for what you did for Ukrain!  Happy to be an investor of this stock and part of this board!  Go $TESLA and here is to peace! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:52:54 </td>
   <td style="text-align:left;"> $LCID lets appreciate that $TSLA can pump more car on a 15 minutes break than  lucid in a year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:50:54 </td>
   <td style="text-align:left;"> $TSLA Elon will save Ukrain‘s communication. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:50:12 </td>
   <td style="text-align:left;"> $FSR $LCID $TSLA $RIVN $NIO 
Have you met the Fisker Pear model with a base proof $22,500 after EV tax incentive? Proudly built in Lordstown, Ohio.🙋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:49:30 </td>
   <td style="text-align:left;"> $TSLA YOU KNOW WHERE THE MONEY IS $RTX !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:47:11 </td>
   <td style="text-align:left;"> Wasn’t $LCID supposed to be the $TSLA killer? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:47:00 </td>
   <td style="text-align:left;"> $TSLA Hot garbage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:46:40 </td>
   <td style="text-align:left;"> $TSLA Undisputed Champ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:46:17 </td>
   <td style="text-align:left;"> $LCID $TSLA Wouldn’t rather drive this EV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:45:49 </td>
   <td style="text-align:left;"> $TSLA Can we get $900 tomorrow?  Settle is the $900-$950 range? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:45:37 </td>
   <td style="text-align:left;"> $TSLA Made back 224 million just by holding bitcoin today, you know what means! Hope you degenerates rolled calls for the week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:45:14 </td>
   <td style="text-align:left;"> $ENPH $PLUG $SEDG $TSLA &amp;quot;BERLIN, Feb 28 (Reuters) - Germany aims to fulfil all its electricity needs with supplies from renewable sources by 2035, compared to its previous target to abandon fossil fuels &amp;quot;well before 2040,&amp;quot; according to a government draft paper obtained by Reuters on Monday.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:44:58 </td>
   <td style="text-align:left;"> $spy $tsla $NIO playing options is like doing time trials in video games they are challenging af and time is constantly working against you. Put ur self in high beta quality stocks that offer comparable returns if you can see the long term potential of how these companies are scaling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:44:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $TSLA is 7.00. This indicates good health for $TSLA. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:43:49 </td>
   <td style="text-align:left;"> $TSLA  900 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:43:41 </td>
   <td style="text-align:left;"> $TSLA needs to hold 800 if on the dip we hold that we headed for 1k soon enough ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:42:54 </td>
   <td style="text-align:left;"> $LCID bulls complaining like bro it’s not that big of a deal 13% haircut is nothing compared to other complain (Netflix) which had 20%+ haircuts with bad earnings.
Stop gambling with calls thinking you’ll hit of the next Tesla $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:38:27 </td>
   <td style="text-align:left;"> $TSLA hey wait, doesn’t TSLA have bitcoin on their balance sheet?🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:37:51 </td>
   <td style="text-align:left;"> $TSLA filthy bears praying for WWIII so they make money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:35:55 </td>
   <td style="text-align:left;"> $SHOP &amp;gt; $TSLA Fight me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:35:53 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:34:54 </td>
   <td style="text-align:left;"> $TSLA Breakthrough watch this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:34:44 </td>
   <td style="text-align:left;"> $LCID $TSLA $FSR $NIO $FERI 
Lovin this....keep the sp low for a wee bit longer so I fill my boots....millionaire stock opp but only if u have 5/10yr patience 

Customer reservations now exceed 25,000, reflecting potential sales of more than $2.4B

Selected to the Nasdaq-100 Index in December, issued $2B in green convertible bonds, and bolstered balance sheet to over $6.2B cash on hand at year-end

- 2.85 million square foot expansion of Casa Grande, Arizona manufacturing facility on track; announced plans for new manufacturing facility in the Kingdom of Saudi Arabia

Updating 2022 production outlook for Lucid Air to a range of 12,000 to 14,000 vehicles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:33:57 </td>
   <td style="text-align:left;"> Tesla Motors, Inc. (NASDAQ: $TSLA) – Tesla Roadster Makes History With $250K Sale: Here’s The World’s Most Expensive Tesla https://www.billionaireclubcollc.com/tesla-motors-inc-nasdaqtsla-tesla-roadster-makes-history-with-250k-sale-heres-the-worlds-most-expensive-tesla/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:33:17 </td>
   <td style="text-align:left;"> $TSLA we will be fulfilling more demand than ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:33:03 </td>
   <td style="text-align:left;"> $TSLA Giga factory FOMO will commence shortly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:32:55 </td>
   <td style="text-align:left;"> $SPY 🏆🎖🙌🏻🙌🏻 $AAPL $TSLA $MSFT $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:29:06 </td>
   <td style="text-align:left;"> $TSLA Elon Musk Delivers Starlink Satellites To Ukraine For Maintaining Internet Amid Invasion 

https://newsfilter.io/a/c5b0b086d1902dd42d45987e9ffaee0a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:28:33 </td>
   <td style="text-align:left;"> $LCID $TSLA $NVDA $AAPL $GGPI 

Updating 2022 production outlook for Lucid Air to a range of 12,000 to 14,000 vehicles.

&amp;quot;We remain on track to grow our Casa Grande facility to nearly quadruple its size as the first greenfield dedicated EV factory in North America; and today we announced plans to build a brand new manufacturing facility in the Kingdom of Saudi Arabia; we estimate that the location of our first international manufacturing plant in the Kingdom of Saudi Arabia may result in up to $3.4 billion of value to Lucid over 15 years.&amp;quot;

https://finance.yahoo.com/news/lucid-announces-fourth-quarter-full-210500201.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:28:24 </td>
   <td style="text-align:left;"> Elon Musk Delivers Starlink Satellites To Ukraine For Maintaining Internet Amid Invasion  $TSLA $SPY $QQQ https://www.billionaireclubcollc.com/elon-musk-delivers-starlink-satellites-to-ukraine-for-maintaining-internet-amid-invasion/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:25:08 </td>
   <td style="text-align:left;"> $TSLA Tesla shares rally on expectations that German factory will open in March

https://www.cnbc.com/2022/02/28/tesla-shares-rally-on-expectations-german-factory-will-open-in-march.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:23:59 </td>
   <td style="text-align:left;"> $ARKK fuck meet Kevin for not asking any questions besides $TSLA  
 
little weasel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:23:43 </td>
   <td style="text-align:left;"> $TSLA back to $1200 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:23:36 </td>
   <td style="text-align:left;"> $LCID added the dip long investor like $TSLA millionaires </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:23:31 </td>
   <td style="text-align:left;"> $TSLA yes tell your bosss Elon Musk about AMC rockettttsss.

 https://youtu.be/jRdySnHrWnM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:23:06 </td>
   <td style="text-align:left;"> $LCID  
  
Well-deserved crash! Just regretted that I didn&amp;#39;t grab enough $28.5 puts. Hopefully, I can close the puts for 200+% by Friday.  
  
$TSLA is the only EV I&amp;#39;m long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:22:10 </td>
   <td style="text-align:left;"> $TSLA 450$, yep, we&amp;#39;ll see it soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:21:16 </td>
   <td style="text-align:left;"> $TSLA $NIO Beautiful let&amp;#39;s gooooooo! 
 
https://www.interactivebrokers.com/mkt/?src=xiaowangY1&amp;amp;url=%2Fcn%2Findex.php%3Ff%3D2359 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:20:54 </td>
   <td style="text-align:left;"> $TSLA pull back tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:20:11 </td>
   <td style="text-align:left;"> $TSLA and honestly every single car manufacturer has a shortage in parts chips etc. Except Tesla, just a thought. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:20:10 </td>
   <td style="text-align:left;"> $TSLA $701.00 average TY paper hands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:19:23 </td>
   <td style="text-align:left;"> $TSLA Tesla longs…Is Tesla gigabattery using redwood materials battery recycling? Straubles company? Rumor of ipo. Thanks to whoever can answer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:19:12 </td>
   <td style="text-align:left;"> $LCID just like Lucid, $PLUG is going to get a massive PLUG pulled tomorrow boys and girls... MINUS $2 shortly after open and will continue downward.. earnings will close tomorrow AH around $18.78. Watch it happen. 
  EXTREME caution to be long in the EV sector.... Russian nuclear threats are going to send all the markets plummeting through mid-March easy guys. $NIO $LI $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:18:23 </td>
   <td style="text-align:left;"> $AMD $AAPL $TSLA $MSTR  
Tech could get going if bonds get bought? 
 
https://www.youtube.com/watch?v=RYVfNJNxIr8&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:16:38 </td>
   <td style="text-align:left;"> $TSLA this baby is going back to $1,200 ….. patiently waiting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:16:21 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;If they can&amp;#39;t afford it they can shake their fists at the sky&amp;quot; -Elon Musk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:15:00 </td>
   <td style="text-align:left;"> Most gaining stocks in the Nasdaq 100 today: $TSLA and $HON https://www.chartmill.com/stock/stock-screener?v=3&amp;amp;f=ind_20&amp;amp;s=pt&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_top_Nasdaq_100_gainers&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:14:15 </td>
   <td style="text-align:left;"> $TSLA This is why yah dont listen to the bears b.s. Hold long! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:14:06 </td>
   <td style="text-align:left;"> $TSLA Tesla Roadster Makes History With $250K Sale: Here&amp;#39;s The World&amp;#39;s Most Expensive Tesla 

https://newsfilter.io/a/782e1aaf1badf406904a0ed39c159375 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:12:53 </td>
   <td style="text-align:left;"> $TSLA  let’s run it over $900 tonight 🤑🤑🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:12:36 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

GREED!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:12:19 </td>
   <td style="text-align:left;"> $TSLA sending electric tanks to Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:10:56 </td>
   <td style="text-align:left;"> $TSLA 

$955.7 next ! 

🙏🏻🐉🦅imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:09:18 </td>
   <td style="text-align:left;"> $LCID just buy $TSLA already profitable and already has a huge fanbase worldwide. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:06:34 </td>
   <td style="text-align:left;"> $TSLA Russia going to shoot down SpaceX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:04:06 </td>
   <td style="text-align:left;"> $TSLA 
Watch out tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:03:46 </td>
   <td style="text-align:left;"> $SE I can guess $TSLA has had a very good couple days partly because Musk activated his Starlink satellite system for the Ukraine, but there&amp;#39;s more going on than that as other tech growth stocks like $SE and $SHOP seem to be surging since Russia&amp;#39;s invasion.  It can&amp;#39;t be a sudden random interest in growth stocks--the Ukraine madness has to be a factor I would think.  But why?  Any wisdom from you all? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:02:10 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:01:11 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-28 Options Analysis Video: 
https://www.youtube.com/watch?v=JEac5IJq7Zc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:01:09 </td>
   <td style="text-align:left;"> $TSLA I won’t say it again!!!!  

….until I do 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 06:00:05 </td>
   <td style="text-align:left;"> $TSLA no oil no problem Elon will provide all Europeans Tesla cars so that they don&amp;#39;t have to worry about oil and gas from Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:59:45 </td>
   <td style="text-align:left;"> $TSLA $1199 01/03/2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:59:15 </td>
   <td style="text-align:left;"> $PLUG $tsla $f $gm $NVDA  
 
Putin just started Viet Nam with his Slavic cousin’s in Ukraine!!! 
 
When are the Oligarchs going to have their coup de ta??!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:58:36 </td>
   <td style="text-align:left;"> $TSLA https://m.youtube.com/watch?v=RSFbWObcT4A&amp;amp;feature=emb_logo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:58:22 </td>
   <td style="text-align:left;"> $TSLA 3 days straight green, probably red tomorrow. maybe around 837. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:57:35 </td>
   <td style="text-align:left;"> $TSLA fly moe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:55:55 </td>
   <td style="text-align:left;"> $TSLA back to820 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:55:53 </td>
   <td style="text-align:left;"> $TSLA Martyrdom for Mars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:54:18 </td>
   <td style="text-align:left;"> $TSLA $900 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:54:14 </td>
   <td style="text-align:left;"> $TSLA lol Lucid delivered 125 cars :D in entire 2022 they will delivered 12k ( at least thats what they claim) this aint no God damn Tesla killer, yes nice cars, but far far away from Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:53:52 </td>
   <td style="text-align:left;"> $TSLA HUGE GAINS FOR OUR MEMBERS!🤑
Free discord in bio!🤑🎉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:53:39 </td>
   <td style="text-align:left;"> $TSLA I will start to short again if this gets to mid 900s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:53:22 </td>
   <td style="text-align:left;"> $TSLA bears, I&amp;#39;ve been waiting to f* you up. I think it&amp;#39;s time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:51:34 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:51:16 </td>
   <td style="text-align:left;"> $TSLA what kind of alien shit is this oh my </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:50:43 </td>
   <td style="text-align:left;"> Running up our best friend $TSLA with 900c tomorrow!  
 
Just sit back and collect. 
 
We&amp;#39;ll signal our entries to everyone who FOLLOWS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:50:41 </td>
   <td style="text-align:left;"> $TSLA how we feeling about this week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:49:55 </td>
   <td style="text-align:left;"> $LCID lowers guidance down to 12-14K for the entire 2022. 2021 they had 20K guidance and achieved 300. LMAO. So much for another &amp;quot; $TSLA killer. &amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:49:50 </td>
   <td style="text-align:left;"> $TSLA thank you OIL🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:49:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

I will add more puts tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:48:50 </td>
   <td style="text-align:left;"> $TSLA anyone see $1K by Friday then pullback below $800 next two weeks? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:48:42 </td>
   <td style="text-align:left;"> $GOOGL where all the $1500 price targets ? 🤣🦍🚀 $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:48:29 </td>
   <td style="text-align:left;"> $TSLA feels like the market is discounting this Russia conflict </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:47:55 </td>
   <td style="text-align:left;"> $LCID Stop comparing anything to $TSLA. Elon is more connected/woven into the fabric of the United States than most companies. This will never be Tesla. Ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:47:06 </td>
   <td style="text-align:left;"> We have to watch $TSLA next KEY levels! 
 
Possibility looking at signaling to you all when we play rejection... 
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:46:29 </td>
   <td style="text-align:left;"> $TSLA  - why up big today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:43:59 </td>
   <td style="text-align:left;"> $TSLA Be very careful bulls today was a good day but with Vladimir anything could happen tonight that’ll tank everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:43:41 </td>
   <td style="text-align:left;"> $TSLA Ok, which one of you showed him Lucid&amp;#39;s deliveries? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:42:39 </td>
   <td style="text-align:left;"> $TSLA Cathie realized she&amp;#39;s a one trick pony, came back to the stock that made her be. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:42:31 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Are my $650 05/20 puts screwed?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:41:49 </td>
   <td style="text-align:left;"> $TSLA why you so much today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:41:10 </td>
   <td style="text-align:left;"> $TSLA  Next

Giga Austin ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:41:07 </td>
   <td style="text-align:left;"> $TSLA  let&amp;#39;s keep pumping all week🚀🚀🚀 💪 💪💪💪💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:40:22 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #3 stock that institutions are trading over rolling 5 day window with 162.2K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:39:58 </td>
   <td style="text-align:left;"> Nothing is stopping this freight train of a stock $AAPL  
 
Whole market gets killed... NOT $AAPL haha 
 
$AMZN $TSLA $NVDA  
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:39:34 </td>
   <td style="text-align:left;"> $TSLA 1400$ by EOY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:39:08 </td>
   <td style="text-align:left;"> Looking for that strong push out of $TSLA  
 
We will signal a trade FOR SURE on them TOMORROW! 
 
FOLLOW🚨 
Lets catch this!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:37:33 </td>
   <td style="text-align:left;"> $TSLA $SPY https://twitter.com/FedorovMykhailo/status/1498392515262746630?s=20&amp;amp;t=1skA1gjLCNDX1lPsuQmlHQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:37:16 </td>
   <td style="text-align:left;"> $TSLA anyone else here bought Tesla at $50 and still holding? Well back then it was $250 :) pre split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:35:41 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Invest in Rubles they said.  Can&amp;#39;t miss in 2022 they said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:34:14 </td>
   <td style="text-align:left;"> $TSLA 700s 600s all gifts lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:33:55 </td>
   <td style="text-align:left;"> $TSLA Just had to buy more shares today on the basis of this - Thanks Elon for all your efforts to help mankind - Yeah I am a fanboy better than being a mommy&amp;#39;s boy living in a basement full of hate.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:33:32 </td>
   <td style="text-align:left;"> $TSLA from $699.00 to $850 and bears are still bearish😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:33:09 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-28 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=zdF8t2hyIM4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:32:48 </td>
   <td style="text-align:left;"> ✅3-0 so far this week on signals❌
(CLOSED TODAY) 
🟢 $SPY PUTS 91% (trade floor) announced eod on Friday as only play I was swinging + liked 
🟢 $AMD PUTS 32% (risky)
🟢 SPY CALLS 13% (risky) paid crazy eod but I was all out on a scalp
🟢 $TSLA PUTS 10% (trade floor) not counting as a win although I did mention I was taking these but they were very pricey. Made $148 per con
(RECAP) 
Another interesting day in the market. Been weathering the storm of volatility very well (knocks on wood). Feels good to have a good start to the week! Other than that keep watching Ukraine news about this cease fire as that’s the main headline as of lately. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:31:59 </td>
   <td style="text-align:left;"> $LCID lol wtf 125 cars and want to be as big as $TSLA ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:31:10 </td>
   <td style="text-align:left;"> $TSLA $NKLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:31:02 </td>
   <td style="text-align:left;"> $SPY If you like space and not into this stock $RKLB, you are missing  out. Another flawless lauch today, 70% yoy growth ... $TSLA $SPCE https://www.youtube.com/watch?v=Rafa_WBFIyE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:30:14 </td>
   <td style="text-align:left;"> We are just going to get GREAT trade opportunities on $TSLA all week.  
 
Just sit and play them to 900 
Then play the 900 rejection! 
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:30:11 </td>
   <td style="text-align:left;"> $TSLA bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:29:53 </td>
   <td style="text-align:left;"> $TSLA 

Berlin - PUMP
texas - PUMP
Elon Tweeted- PUMP

Elon said something about CyberTruck in 2025 ( I am on the waitlist and I like my 3 more than my 2018 X) 
- PUMP
ELON flight over China , Germany - he must be doing something - PUMP It 

Elon Farted 😀 and smoked on Radio- PUMP it

Tesla is for history books. When there is a dip under $700 any time this year, going all IN.  Even the war can’t do shit. Only thing could move below $750 is US involvement in war and FED news or something unexpected happened due to Russian war.  Starting a small put for 3/25 with a stop loss, of course. Worst thing could happen now is FED goes on dovish side. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:29:10 </td>
   <td style="text-align:left;"> Solid way to start the week, some great movers out the gate, very selective this afternoon payed off. Main tickers: $TSLA $LMT $CVX $FB $QS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:28:10 </td>
   <td style="text-align:left;"> $TSLA Some of these bears are hilarious. They think it&amp;#39;s cheesy easy to make 💰 buying puts whenever terrible world news comes out🙈...if it were so easy then why aren&amp;#39;t all traders  living in the Hamptons? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:28:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $TSLA bears counting on Putin for the market to tank bc they realized inflation doesn’t matter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:27:54 </td>
   <td style="text-align:left;"> $TSLA oil price going up, Testa going up 🔋 still going for the 1400$ mark by the end of the year. Nothing can stop them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:27:39 </td>
   <td style="text-align:left;"> $TSLA I think this today&amp;#39;s rally was more Bitcoin related than anything else imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:23:26 </td>
   <td style="text-align:left;"> We were ready for $TSLA 
 
Lets see if we can get them to rally hard tomorrow and push for 900 and into their chop zone around 900-1000... 
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:23:10 </td>
   <td style="text-align:left;"> $TSLA push! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:23:06 </td>
   <td style="text-align:left;"> $LCID I tried to tell people execution risk is not priced in. I do want them to succeed and I&amp;#39;m not a stock twits troll. $TSLA barely got through &amp;quot;production hell.&amp;quot; Lucid (and others) will have a bumpy path and only a handful (if that) will survive or be acquired. If you&amp;#39;re buying start-up EVs make sure you&amp;#39;re getting a nice discount. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:21:39 </td>
   <td style="text-align:left;"> $TSLA 

Berlin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:21:37 </td>
   <td style="text-align:left;"> $TSLA 800p </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:21:23 </td>
   <td style="text-align:left;"> $TSLA still holding 10 $825 puts, down -50% ($10,000) but still confident we see $800 again by Thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:21:15 </td>
   <td style="text-align:left;"> $TSLA amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:20:28 </td>
   <td style="text-align:left;"> $LCID Stop trying to look for next Tesla and just buy $TSLA lol. Even Nio is a better buy than this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:20:27 </td>
   <td style="text-align:left;"> Watching to see how the market reacts overnight! We think a nice bounce and push this week could set-up nicely for the following weeks!  
 
$SPY $NASDAQ $TSLA $AAPL  
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:19:19 </td>
   <td style="text-align:left;"> $TSLA $QQQ $PLTR $BTC.X $SPY is 26% a lot for 1 day? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:19:11 </td>
   <td style="text-align:left;"> WATCHLIST for tomorrow coming out later!  
 
With our plays listed... FOLLOW to see 
$TSLA $NVDA $AMZN  
 
We post daily! 
FOLLOW🚨, 
LIKE✅, 
&amp;amp; LETS MAKE MONEY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:18:49 </td>
   <td style="text-align:left;"> $TSLA will always eat everyone else’s lunch $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:18:36 </td>
   <td style="text-align:left;"> $TSLA 

Great work Biden &amp;amp; NATO you’re getting 1 inch closer to push the world into and inevitable demise !! 

More SANCTIONS plz!! 👍

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:18:18 </td>
   <td style="text-align:left;"> $TSLA  checking phone every 5 minute to see if it has pop another $50

Packed with news .

🎆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:17:33 </td>
   <td style="text-align:left;"> $TSLA God Bless ya. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:17:10 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla shares rally on expectations that German factory will open in March https://www.stck.pro/news/TSLA/23614579 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:14:51 </td>
   <td style="text-align:left;"> $TSLA shorting x500  on 7 diffrent accounts. Total with margin 120mil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:14:49 </td>
   <td style="text-align:left;"> $TSLA +7.48% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:13:49 </td>
   <td style="text-align:left;"> $TSLA don&amp;#39;t make my mistakes please and buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:13:39 </td>
   <td style="text-align:left;"> $TSLA resistance at 900 so buy dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:13:19 </td>
   <td style="text-align:left;"> $TSLA remember this stock is for the long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:13:08 </td>
   <td style="text-align:left;"> $TSLA there will be resistance towards 90p so please please buy the dips, this will get to 1.5k eventually </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:13:06 </td>
   <td style="text-align:left;"> Tesla Motors, Inc. (NASDAQ: $TSLA), General Motors Company (NYSE: $GM) – Lidar Vs. Cameras In EVs: Tesla’s Musk And His Followers Weigh In https://www.billionaireclubcollc.com/tesla-motors-inc-nasdaqtsla-general-motors-company-nysegm-lidar-vs-cameras-in-evs-teslas-musk-and-his-followers-weigh-in/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:13:04 </td>
   <td style="text-align:left;"> Why Tesla, Nio And Rivian Shares Surged  $TSLA $NIO $RIVN 

https://newsfilter.io/a/f6bfbc260e90d4b4f4986bc574bfee88 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:11:57 </td>
   <td style="text-align:left;"> We have identified an unusual $TSLA sweep that expires on March 18, 2022 with a strike price of $985.00.

600 CALL contracts with a price of $11.10 (Ask) were purchased at a $666,020 premium. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:11:47 </td>
   <td style="text-align:left;"> $TSLA swinging this overnight. We shall see what we have in store tmmr! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:11:14 </td>
   <td style="text-align:left;"> $TSLA seems like it wants to go tap 900 and then might get rejected. RSI and MACD looking healthy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:10:52 </td>
   <td style="text-align:left;"> $TSLA lucid getting wrecked AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:10:29 </td>
   <td style="text-align:left;"> $TSLA 🐻 wanted 600-700s we got there at 690ish last week now move along  there’s nothing to see here 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:10:27 </td>
   <td style="text-align:left;"> $TSLA Could touch 900 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:10:06 </td>
   <td style="text-align:left;"> $TSLA 780$ on Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:10:02 </td>
   <td style="text-align:left;"> $TSLA to the teslemmings saying &amp;quot;lol bro ur shorting $TSLA before 2 gigacraptories open&amp;quot;, have you never seen buy the rumor / sell the news type moves? Have you forgotten the stonk was under $700 just 3 sessions ago? Do you know how much I made shorting this bubble stonk YTD? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:09:50 </td>
   <td style="text-align:left;"> $TSLA why is this up 7 percent today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:09:49 </td>
   <td style="text-align:left;"> $TSLA LMAO shitty alternative EV stocks 
 
Lucid Group (NASDAQ: $LCID) reported Q4 EPS of ($0.64), $0.29 worse than the analyst estimate of ($0.35). Revenue for the quarter came in at $26.4 million versus the consensus estimate of $36.74 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:09:41 </td>
   <td style="text-align:left;"> $TSLA this will get to 1.5k then the fun will begin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:09:33 </td>
   <td style="text-align:left;"> $LCID Why get shitty alternatives when you can get $TSLA  
 
Lucid Group (NASDAQ: $LCID) reported Q4 EPS of ($0.64), $0.29 worse than the analyst estimate of ($0.35). Revenue for the quarter came in at $26.4 million versus the consensus estimate of $36.74 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:09:32 </td>
   <td style="text-align:left;"> $TSLA LMAOOOO LUCID delivered 300 cars...yes 300 :D :D What a Tesla killer. Lowered guidance Stock down 10% AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:09:19 </td>
   <td style="text-align:left;"> $TSLA I wish I had bought more at 730! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:09:13 </td>
   <td style="text-align:left;"> $TSLA cant wait to hear the lies this fucktard assclown tells at the &amp;quot;state of the destruction of the union &amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:09:09 </td>
   <td style="text-align:left;"> $TSLA I am long bull but  it is a really risky market at the moment - If Russia attacks any EU/Nato country (by purpose or by error) This will go way down. Also don&amp;#39;t forget recession, increasing energy prices and post Corona effect. Afraid it is too early for this to go up. What do you think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:08:59 </td>
   <td style="text-align:left;"> $TSLA buy all the dips people if you can </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:08:58 </td>
   <td style="text-align:left;"> $TSLA what if Biden mentions tsla in his speech tmr… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:08:57 </td>
   <td style="text-align:left;"> $TSLA Bought the dip. Up 12.58% since 2/23. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:08:56 </td>
   <td style="text-align:left;"> @Bullseye23 $TSLA must visit 820 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:08:46 </td>
   <td style="text-align:left;"> $TSLA when we get to 1.5k please don&amp;#39;t sell like bitches as stick split will make it good for you long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:08:16 </td>
   <td style="text-align:left;"> $MMAT $TSLA $MULN incredible day of gains… can’t wait for the rest of the week. Let’s get paid bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:08:13 </td>
   <td style="text-align:left;"> $TSLA as we go up to 1.5k buy the dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:08:01 </td>
   <td style="text-align:left;"> $TSLA 

How can one not like this stock❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:07:59 </td>
   <td style="text-align:left;"> $ARKK $DKNG $TDOC $TSLA $SQ Looks as thou Cathy knows what she is doing after all. Probably the best ETF to ride the rest of the year. 

Happy to be on the team, man. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:07:16 </td>
   <td style="text-align:left;"> $TSLA bought some calls for 1000 and puts for 700.. hopefully either way i win.. don’t bash me. Its just business in an uncertain time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:06:46 </td>
   <td style="text-align:left;"> $TSLA bulls there will be resistance so buy the dips if you can </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-01 05:06:09 </td>
   <td style="text-align:left;"> $TSLA --Sold partial for $871--A good day for TSLA (for now)--Let the rest ride with Cathie Wood!-- </td>
  </tr>
</tbody>
</table></div>

---
