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
[View the latest Economic Forecasts](/Monthly-Market-Outlook--Jan-2022--html.md)

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



Last Updated: 2021-12-30 14:14:28 UTC +8

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
   <td style="text-align:left;"> 2021-12-30 14:12:48 </td>
   <td style="text-align:left;"> New Zealand Stocks End at 7-Week High </td>
   <td style="text-align:left;"> The NZX 50 Index jumped 0.78% to make a 7-week high close at 13,041 on Thursday, tracking gains from global peers as investors shrugged off reports of the first community exposure from omicron in New Zealand. Markets gained confidence after several studies suggested that the new variant is less severe than previously feared, with most governments holding off from imposing new restrictions on movement. The biggest index advancers were Vista (4.37%), Skellerup (3.22%), Mainfreight (2.88%), Heartland Group (2.86%) and Scales (2.71%). The benchmark equity index is set to finish the year unchanged in a largely sideways market, as New Zealand underwent one of the longest and strictest lockdowns, and the Reserve Bank of New Zealand was among the first major central banks to hike interest rates to fight inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 13:54:02 </td>
   <td style="text-align:left;"> Indian Shares Edge Higher on Tech Boost </td>
   <td style="text-align:left;"> The BSE Sensex Index gained 0.2% toward 57,920 and the Nifty 50 Index rose 0.1% to 17,230 on Thursday, as gains in technology stocks outweighed losses in financial firms. Early market leaders include Wipro Ltd (1.7%), Tata Consultancy (0.9%), Infosys (0.7%), HCL Technologies (1.4%) and Tech Mahindra (1.7%); while some of the laggards were RBL Bank (-8.7%), State Bank of India (-0.7%) and Bajaj Finserv (-1.3%). Indian equities have retreated about 7% from a record peak hit in October on worries over high valuations and the spread of the omicron variant across the globe. However, the major averages are on track to finish the year up more than 20% as Indian stocks outperformed regional peers on the back of accommodative monetary policies and market momentum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/samsung-biologics-says-report-on-biogen-deal-talks-untrue </td>
   <td style="text-align:left;"> 2021-12-30 13:51:48 </td>
   <td style="text-align:left;"> Samsung BioLogics says report on Biogen deal talks untrue </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                             , Samsung BioLogics on Thursday denied a media report that said the South Korean firm was in talks to buy U.S. drugmaker Biogen Inc.                                                                                                                                            , Korea Economic Daily reported on Wednesday, citing investment banking sources, that Biogen had approached Samsung to buy its shares, which could be valued at more than $42 billion. Biogen is valued at $34.67 billion, according to Refinitiv data.                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                   , Samsung BioLogics, the biotech unit of Samsung Group, said in a regulatory filing that the report was "not true," without giving any more details.                                                                                                                            , Biogen said it does not comment on market rumors or speculation. Its stock closed up 9.5% on Wednesday.                                                                                                                                                                       , Any such deal would be the biggest overseas acquisition ever by a South Korean company. The largest so far was in 2016, when Samsung Electronics bought auto electronics maker Harman International Industries in an $8 billion deal.                                         , BIOGEN CUTS PRICE FOR ALZHEIMER’S DRUG ADUHELM BY HALF                                                                                                                                                                                                                        , Samsung Group had said earlier this year it will invest 240 trillion won ($206 billion) in the next three years to expand its footprint in biopharmaceuticals, artificial intelligence, semiconductors and robotics in the post-pandemic era.                                 , This image provided by Biogen on Monday, June 7, 2021 shows a vial and packaging for the drug Aduhelm. (Biogen via AP / AP Newsroom)                                                                                                                                          , In June, Biogen's controversial Alzheimer's drug won U.S. regulatory approval, becoming the first new treatment for the memory-robbing disease in nearly 20 years, despite an outside advisory panel's view that the company had not proven the treatment's clinical benefits., Biogen has been betting on the drug, Aduhelm, to buffer a hit as its main revenue drivers such as multiple sclerosis treatment Tecfidera and muscle disease treatment Spinraza face rising competition.                                                                       , But U.S. sales from Aduhelm have been slower than expected as hospitals complained that the drug's high cost was not worth its benefits. The company cut its price by about half to $28,200 this month.                                                                       , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                       , Biogen, which makes drugs for neurological diseases, currently has more than 30 new drugs in its pipeline.                                                                                                                                                                    , (Reporting by Dania Nadeem in Bengaluru and Joyce Lee in Seoul; Editing by Shinjini Ganguli) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/netherlands/business-confidence </td>
   <td style="text-align:left;"> 2021-12-30 13:49:02 </td>
   <td style="text-align:left;"> Dutch Business Mood Falls in December from Record High </td>
   <td style="text-align:left;"> The Netherlands' business confidence indicator fell to 10.2 in December 2021 from a record high of 12.7 a month earlier. Manufacturers were less optimistic about both future production (8.5 vs 11.6 in November) and their order books (22.2 vs 23.0). At the same time, their assessments on stocks of finished products turned negative for the first time since August 2020 (-0.3 vs 3.6). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/30/asia/korean-war-armistice-peace-explained-intl-hnk-ml/index.html </td>
   <td style="text-align:left;"> 2021-12-30 13:48:51 </td>
   <td style="text-align:left;"> The Korean War never officially ended. That might soon change - CNN </td>
   <td style="text-align:left;"> Hong Kong (CNN)Is the Korean War about to come to an end?                                                                                                                                                                                                                                                                                                                             , Some people might answer: "Didn't that happen in 1953?"                                                                                                                                                                                                                                                                                                                               , Others may know that it was only an armistice that brought hostilities to a halt in 1953 -- but there's never been a treaty to end the conflict between North Korea (and its chief ally China) and South Korea and its allies, most notably the United States.                                                                                                                        , With the top South Korean diplomat on Wednesday saying Seoul and Washington have "effectively" agreed on a draft agreement to end the war, here's a primer on what that means.                                                                                                                                                                                                        , What was the Korean War?                                                                                                                                                                                                                                                                                                                                                              , The war broke out on June 25, 1950, when the first of what the US military estimated as 135,000 North Korean forces stormed across the 38th parallel dividing North and South Korea in an effort to take total control of the Korean Peninsula.                                                                                                                                       , The United States, under President Harry Truman, responded with what was called a "police action," assembling a group of international allies under the auspices of the "United Nations Command" to come to the aid of South Korea. Twenty-two nations contributed combat troops or medical support units to the US-led effort.                                                       , Communist-controlled North Korea had the support of both the Soviet Union and China, with Beijing actively intervening on the military front in October 1950, sending almost a quarter-million troops into the Korean Peninsula as the US-led forces were advancing toward China's border with North Korea.                                                                           , Chinese support of the North pushed the UN advance back down the peninsula and by 1951 stalemate emerged along the 38th parallel, where the border between the two Koreas sits today.                                                                                                                                                                                                 , How did the fighting stop?                                                                                                                                                                                                                                                                                                                                                            , Armistice talks began in 1951 and occurred intermittently until a final agreement to end combat was made at Panmunjom on the 38th parallel on July 27, 1953. Within three days, both sides withdrew their troops to be at least 2 kilometers (1.2 miles) from the cease-fire line.                                                                                                    , Why didn't the armistice end the war?                                                                                                                                                                                                                                                                                                                                                 , The signatories of the July 27, 1953 agreement to end hostilities were the heads of the UN Command, the North Korean army and of Chinese troops on the Korean Peninsula. South Korea is not a signee, and the agreement specifically says it is not a peace treaty.                                                                                                                   , According to the armistice preamble, it is made "in the interest of stopping the Korean conflict, with its great toil of suffering and bloodshed on both sides, and with the objective of establishing an armistice which will insure a complete cessation of hostilities and of all acts of armed force in Korea until a final peaceful settlement is achieved."                     , What has happened since 1953?                                                                                                                                                                                                                                                                                                                                                         , There was no official contact between the North and South Korean governments until 1971, according to the US State Department.                                                                                                                                                                                                                                                        , By 1991 though, tensions had eased enough that Pyongyang and Seoul signed on to the North-South Basic Agreement, which said reunification was the goal of both parties. But a State Department history says the North's budding weapons programs and the death of its longtime leader Kim Il-Sung in 1994, coupled with political turmoil in the South, led to new tensions.          , The first inter-Korean summit was held in June 2000, but the thaw it provided ended with North Korea's admission in 2002 that it was pursuing nuclear weapons.                                                                                                                                                                                                                        , That admission led to a series of negotiations about the North's nuclear program among North Korea, China, Russia, South Korea, the US and Japan, known as the six-party talks. North Korea pulled out of that effort in 2009 after restarting its Yongbon nuclear reactor and launching a series of missile tests.                                                                   , In 2007, South Korean President Roh Moo-hyun and North Korean leader Kim Jong Il met in Pyongyang and agreed to try to bring peace to and reunify the peninsula without the intervention of outside parties. But conservative Lee Myung-bak was elected South Korean President a few months later, and switched to a hard line on the North's weapons program, chilling peace efforts., Tensions thawed again in 2018 when North Korean leader Kim Jong Un met with South Korean President Moon Jae-in in Panmunjom. The two said they would work to turning the 1953 armistice into a peace treaty.                                                                                                                                                                          , Later that year the two met again in Pyongyang and signed a joint declaration to pursue denuclearization while working toward peace on the peninsula.                                                                                                                                                                                                                                 , Three meetings between US President Donald Trump and Kim -- the first between a sitting US President and a North Korean leader -- also failed to make any progress toward denuclearization of the North, despite their historic nature. Efforts have since stalled.                                                                                                                   , So what does the announcement of a possible peace treaty draft mean?                                                                                                                                                                                                                                                                                                                  , Essentially, not much -- for now. Whatever deal the US and South Korean diplomats make on draft language, it would still need approval within their respective governments. Of course, North Korea would have to agree and, as a party to the armistice, so would China.                                                                                                              , But there is some room for optimism.                                                                                                                                                                                                                                                                                                                                                  , South Korean Foreign Minister Chung Eui-yong said Wednesday that North Korea has been quickly and positively responding to South Korea's movement to declare the end of the Korean War.                                                                                                                                                                                               , And Kim Yo Jong, sister of the North Korean leader, in September termed the South Korean President's proposal to declare an end to the war "interesting" and "an admirable idea," but questioned the timing and demanded a hostile policy against the North must be withdrawn first.                                                                                                  , North Korea has yet to respond in detail about the declaration though, even through China, Chung said.                                                                                                                                                                                                                                                                                , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2021-12-30 13:26:00 </td>
   <td style="text-align:left;"> Gold Pressured by Rising Treasury Yields </td>
   <td style="text-align:left;"> Gold stabilized around the $1,800 per ounce level on Thursday, but remained under pressure as Treasury yields crept higher. The benchmark US 10-year yield broke above 1.5% on Wednesday as investors anticipate the direction of inflation next year. Higher bond yields raise the opportunity cost of holding the non-interest paying gold. However, a weaker dollar, which steadied near a one-month low, provided a floor to the yellow metal. Gold fluctuated wildly throughout the final week of 2021, and is on track for its biggest annual percentage decline since 2015.  The metal is set to fall about 5% for the year, marred by reduced stimulus and expectations of higher interest rates as major central banks tighten monetary policy to combat inflation. This year's lackluster performance followed a stellar period as it benefited from inflationary pressures and hit an all time high in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/gold-set-for-worst-performance-in-six-years-steadies-above-1800 </td>
   <td style="text-align:left;"> 2021-12-30 13:11:58 </td>
   <td style="text-align:left;"> Gold set for worst performance in six years, steadies above $1,800 </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                        , Gold was on course to record its worst performance in six years, though prices steadied above the key $1,800 per ounce level in thin trade on Thursday as a weak dollar countered pressure from firm Treasury yields.                                                    , Spot gold was down 0.1% at $1,801.40 per ounce by 0353 GMT. U.S. gold futures fell 0.2% to $1,802.30.                                                                                                                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                              , "The kind of back and forth seen over the last 48 hours is less indicative of any particular fundamental catalyst and much more of the market being very thin and volatility being amplified by that absence of liquidity," said DailyFX currency strategist Ilya Spivak., Gold prices hit a one-month high on Tuesday but slipped to a one-week low the very next session before closing unchanged, and were on track for their biggest annual percentage decline since 2015.                                                                      , American gold bars stand on display REUTERS/Mike Segar (UNITED STATES)                                                                                                                                                                                                   , The first week of January will provide directional clues because gold is seen caught between how fast and in what direction inflation is going and what, and how much, the U.S. Federal Reserve is doing to contain it, Spivak said.                                     , Benchmark 10-year U.S. Treasury yields firmed near a one-month peak, raising the opportunity cost of holding non-interest paying gold.                                                                                                                                   , However, buoying the metal's appeal, the dollar index steadied near a one-month low as investors looked beyond a surge in Omicron variant cases and favored riskier currencies.                                                                                          , Asian shares got off to a listless start as the spread of Omicron clouded the last trading day of the year for many exchanges around the globe.                                                                                                                          , U.S. weekly initial jobless claims data, a key metric of the country's economic health usually monitored by market participants, is due at 1330 GMT later in the day.                                                                                                    , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                  , Spot silver dipped 0.5% to $22.70 an ounce, platinum eased 0.3% to $964.96, and palladium fell 0.5% to $1,973.75. All set for their worst showing in several years.                                                                                                      ,  (Reporting by Bharat Govind Gautam and Seher Dareen in Bengaluru; Editing by Vinay Dwivedi) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59824407?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-30 12:54:46 </td>
   <td style="text-align:left;"> China ride-hailing giant Didi sees losses deepen after crackdown </td>
   <td style="text-align:left;"> Chinese ride-hailing giant Didi Chuxing has seen its losses deepen after Beijing ordered online stores not to offer the company's app.                                                                                                                                                                                       , The firm reported an operating loss of $6.3bn (£4.7bn) for the first nine months of year as revenues in China fell by 5% in the third quarter.                                                                                                                                                                               , The Chinese crackdown came just days after Didi made its New York stock market debut at the end of June.                                                                                                                                                                                                                     , This month, it said it will move its share listing to Hong Kong from the US.                                                                                                                                                                                                                                                 , In recent months, Didi has become one of the most high profile targets of Beijing's clampdown on the country's technology industry.                                                                                                                                                                                          , The restrictions placed on it by authorities in China have hit its share price in the US hard.                                                                                                                                                                                                                               , The company's value on the New York Stock Exchange has fallen by 65% since its debut less than six months ago.                                                                                                                                                                                                               , In its latest report to investors the firm also said that its board had authorised it to pursue a listing of its shares on the main board of the Hong Kong Stock Exchange.                                                                                                                                                   , "The company is executing above plans and will update investors in due course," Didi said.                                                                                                                                                                                                                                   , Didi's announcement early in December that it planned to leave the US stock market came on the same day that the US Securities and Exchange Commission said it had finalised rules that would mean US-listed foreign companies can be delisted if their auditors do not comply with requests for information from regulators., "Following careful research, the company will immediately start delisting on the New York stock exchange and start preparations for listing in Hong Kong," the company said at the time.                                                                                                                                     , Didi also said in Thursday's announcement that Daniel Zhang, the chief executive of Chinese e-commerce giant Alibaba, who had served as a director on its board since 2018, has resigned from the role.                                                                                                                      , As well as coming under intense scrutiny from Chinese regulators, Didi now faces tough competition in its home market from ride-hailing services launched by car makers Geely and SAIC Motor.                                                                                                                                , This video can not be played                                                                                                                                                                                                                                                                                                 , The man himself on ten key lyrics, including some of The Beatles' classics                                                                                                                                                                                                                                                   , Abbey Road's amazing history of making music for films and games                                                                                                                                                                                                                                                             , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/iran/inflation-cpi </td>
   <td style="text-align:left;"> 2021-12-30 12:34:00 </td>
   <td style="text-align:left;"> Iran Inflation Rate at 15-Month Low of 35.2% </td>
   <td style="text-align:left;"> The annual inflation rate in Iran decreased to 35.2 percent in December 2021 from 35.7 percent in the previous month. This was the lowest reading since September 2020, mainly due to a slowdown in prices of food &amp; non-alcoholic beverages (41.8% vs 47.0% in November); furniture &amp; household equipment (36.7% vs 39.6%); health (34.6% vs 35.2%); and recreation &amp; culture (32.7% vs 33.4%). Meanwhile, inflation accelerated for housing &amp; utilities (26.2% vs 25.6%); transport (33.3% vs 25.0%); communication (2.3% vs 1.2%); clothing &amp; footwear (48.8% vs 48.8%); tobacco (29.7% vs 28.1%; and miscellaneous goods &amp; services (36.5% vs 36.5%).  On a monthly basis, consumer prices went up 1.7 percent in December, the least in 7 months, easing from a 2.5 percent gain November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malaysia/producer-prices-change </td>
   <td style="text-align:left;"> 2021-12-30 12:16:00 </td>
   <td style="text-align:left;"> Malaysia Producer Price Inflation Slows </td>
   <td style="text-align:left;"> Producer prices in Malaysia rose by 12.6 percent year-on-year in November of 2021, slowing from a 13.2 percent gain a month earlier which was the highest figure since September 2011. Still, this was the eighth straight month of a double-digit rise in producer inflation, amid higher commodity prices and supply chain issues. Cost continued to rise for both mining (71.2 percent vs 82.9 percent in October) and agriculture, forestry &amp; fishing (19.1 percent vs 24.8 percent).  At the same time, prices of electricity &amp; gas supply fell 0.3 percent after gaining 0.7 percent in October. By contrast, cost of manufacturing accelerated (8.4 percent vs 7.9 percent), amid a rebound in prices of water supply (0.2 percent vs -0.7 percent). On a monthly basis, producer prices grew 1.4 percent in November, faster than from a 1.4 percent rise in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-30 12:04:00 </td>
   <td style="text-align:left;"> South Korea 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> South Korea 10 Year Government Bond touched a 4-week high, as bond markets have been stressed by the persistence of US inflation and a resulting hawkish turn by the Fed, with investors now pricing the first-rate hike as early as March or May. Locally, South Korea’s headline inflation accelerated to a decade high in November at 3.7%, remaining above the central bank’s 2% annual target for an eighth straight month. The latest inflation rate followed a 3.2% increase in October, driven by elevated costs from oil and other commodities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-30 11:48:00 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> Japan 10 Year Government Bond Yield increased to a 4-week high of 0.071% on the final trading day before the four-day New Year holiday, tracking US Treasury yields higher on expectations that the Omicron strain would not derail the economic recovery. On the data front,  consumer prices in Japan rose 0.6% yoy in November, the steepest increase since January 2020, underpinned by fuel costs. Earlier, the Japanese government upgraded its economic assessment for the first time in seventeen months, as authorities raised their views on private consumption and business conditions, despite downside risks from lingering supply issues and raw material price inflation. On December 17th, the Bank of Japan decided to begin tapering corporate debt purchases to pre-pandemic levels and partially unwind its emergency funding scheme from March 2022 onwards, adding that the economy was picking up, despite remaining in a severe situation due to the impact of COVID-19. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2021-12-30 11:46:23 </td>
   <td style="text-align:left;"> Brent Gains on Falling US Oil Inventories </td>
   <td style="text-align:left;"> Brent crude futures firmed up above $79 a barrel on Thursday, hovering close to levels last seen before news of the omicron variant first broke on Nov. 26, after EIA data showed US crude inventories fell more than expected last week. The EIA Petroleum Status Report showed US crude oil inventories fell by 3.576 million barrels last week, a 5th consecutive period of declines and compared with market forecasts of a 3.143 million drop. Also, investors grew confident there will be no need to impose more restrictions on movements amid more evidence omicron is less severe than previous strains. Oil is on track to book a more than 50% gain for 2021, its strongest performance in more than a decade, amid rising demand and supply constraints. Traders now await the next OPEC+ meeting on January 4th, as the group is set to decide whether to go ahead with a planned 400,000 barrels per day production increase in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2021-12-30 11:43:59 </td>
   <td style="text-align:left;"> Oil Firms as US Crude Inventories Fall </td>
   <td style="text-align:left;"> WTI crude futures firmed up above $76 a barrel on Thursday, hovering close to levels last seen before news of the omicron variant first broke on Nov. 26, after EIA data showed US crude inventories fell more than expected last week. The EIA Petroleum Status Report showed US crude oil inventories fell by 3.576 million barrels last week, a 5th consecutive period of declines and compared with market forecasts of a 3.143 million drop. Also, investors grew confident there will be no need to impose more restrictions on movements amid more evidence omicron is less severe than previous strains. Oil is on track to book a more than 50% gain for 2021, its strongest performance in more than a decade, amid rising demand and supply constraints. Traders now await the next OPEC+ meeting on January 4th, as the group is set to decide whether to go ahead with a planned 400,000 barrels per day production increase in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2021-12-30 11:11:00 </td>
   <td style="text-align:left;"> Indian Rupee Hits 5-week High </td>
   <td style="text-align:left;"> USDINR notched a 5-week high of 74.48, but not far from an 18-month low of $76.34 hit on December 15th and is set to end the quarter 1.8% lower amid relentless foreign fund outflows after rating agencies like Goldman Sachs and Nomura Holdings lowered the outlook for Indian equities, citing them as overpriced. Global funds pulled USD 4.2 billion from the domestic equity market and USD 587 million from the bond market this quarter. Also, RBI’s dovish monetary policy in contrast with the hawkish Fed decision, where it signaled as many as three rate hikes in 2022, reduced the INR appeal among investors. At the same time, India showed signs of slowing growth through its record-high trade deficit (USD 23 billion) and a higher-than-expected jump in retail prices (14.2 percent vs expected 11.9 percent) last month. This comes at a time when the country's Omicron cases have already reached over 300, casting further doubts on its slowing economic recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 10:54:53 </td>
   <td style="text-align:left;"> China Stocks Rise on Broad Market Rebound </td>
   <td style="text-align:left;"> The Shanghai Composite rose 0.8% toward 3,625 and the Shenzhen Component jumped 1% to 14,805 on Thursday, as mainland stocks attempted to rebound from sell offs driven by extended lockdowns in northern China. The country has followed a “zero Covid-19” strategy of tight border controls, lengthy quarantines and targeted lockdowns ahead of February’s Winter Olympics. Consumer-related and technology stocks led the market rebound, with gains from Kweichow Moutai (1.1%), East Money (2.7%), Longi Green Technology (1.5%), AECC Aviation (5.7%) and Gigadevice Semiconductor (5.6%), among others. The Shanghai Composite and Shenzhen Component indices are set to end the year up by 4% and 2%, respectively, in a largely sideways market, marred by debt crises in the property sector and regulatory crackdown in the technology sector. Meanwhile, new energy stocks outperformed throughout the year amid a global push toward cleaner energy, with government support from Beijing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59824404?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-30 10:38:54 </td>
   <td style="text-align:left;"> Elon Musk rejects claims that his satellites are hogging space </td>
   <td style="text-align:left;"> Elon Musk has rejected claims that his Starlink satellite internet project is taking up too much room in space.                                                                                                                    , "Tens of billions" of satellites can be accommodated in orbits close to Earth, he told the Financial Times.                                                                                                                        , His comments come after a claim by the head of the European Space Agency (ESA) that Mr Musk was "making the rules" for the emerging commercial space industry.                                                                     , This week, China complained that its space station was forced to avoid collisions with Starlink satellites.                                                                                                                        , "Space is just extremely enormous, and satellites are very tiny," Mr Musk said in the interview.                                                                                                                                   , Mr Musk pushed back at suggestions that his Starlink Internet Services project was effectively obstructing the entry of competitors to the satellite industry, saying that there is ample room in the Earth's orbit for satellites., "This is not some situation where we're effectively blocking others in any way. We've not blocked anyone from doing anything, nor do we expect to," he said.                                                                       , "A couple of thousand satellites is nothing. It's like, hey, here's a couple of thousand of cars on Earth, it's nothing," he added.                                                                                                , This month, Josef Aschbacher, the director general of ESA, warned that the thousands of communications satellites launched by Starlink would result in there being far less space for competitors.                                 , Other experts have said that much larger distances are needed between spacecraft to avoid collisions than Mr Musk has suggested.                                                                                                   , Scientists have also previously voiced concerns about the risks of collisions in space and called on world governments to share information about the estimated 30,000 satellites and other space debris that are orbiting Earth.  , Mr Musk made headlines this week as he faced a social media backlash after China complained that its space station was forced to avoid collisions with satellites launched by his Starlink project.                                , The country's space station had two "close encounters" with Starlink satellites this year, Beijing claimed.                                                                                                                        , The incidents occurred on 1 July and 21 October, according to a document submitted by China this month to the United Nations Office for Outer Space Affairs.                                                                       , "For safety reasons, the China Space Station implemented preventive collision avoidance control," Beijing said in the document published on the agency's website.                                                                  , The incidents behind the complaints, lodged with the UN's space agency, have not yet been independently verified.                                                                                                                  , China also accused the US of putting astronauts in danger by ignoring obligations under outer space treaties.                                                                                                                      , Foreign ministry spokesman Zhao Lijian said China was urging the US to act responsibly.                                                                                                                                            , SpaceX has already launched almost 1,900 satellites as part of the Starlink network, and plans to deploy thousands more.                                                                                                           , This video can not be played                                                                                                                                                                                                       , The man himself on ten key lyrics, including some of The Beatles' classics                                                                                                                                                         , Abbey Road's amazing history of making music for films and games                                                                                                                                                                   , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/canola </td>
   <td style="text-align:left;"> 2021-12-30 09:51:00 </td>
   <td style="text-align:left;"> Canola Hits All-time High </td>
   <td style="text-align:left;"> Canola increased to an all-time high of 1101 CAD/T, heading for an over 70% yearly gain in 2021, as Canada's canola harvest yielded its smallest crop in 14 years because of a severe drought. Canada is the world’s biggest canola producer and about 90% of its output is shipped to 50 countries, according to Canola Council of Canada. On the demand side, China and other nations like Japan, the UAE and France stepped up imports of the oilseed used for vegetable oil, processed foods, and animal feed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/30/2021-asia-ipos-that-have-faltered-since-a-strong-debut-day-performance.html </td>
   <td style="text-align:left;"> 2021-12-30 09:18:59 </td>
   <td style="text-align:left;"> These Asia stocks have fallen sharply since their 2021 IPOs, fading from their first day surges </td>
   <td style="text-align:left;"> , Some 2021 Asia-Pacific IPOs have seen a sharp reversal in their fortunes since their strong market debuts.                                                                                                                                                                                                                                 , At the top of the list is Chinese short video company and Tiktok-rival Kuaishou, which more than doubled from its issue price during its February debut. It was the only Asia listing among this year's top five largest IPOs globally by deal size, according to Morningstar.                                                             , As of Wednesday's market close in Hong Kong, however, the stock sat 77% below those first day gains.                                                                                                                                                                                                                                       , Elsewhere, shares of Indonesian e-commerce firm Bukalapak have also tumbled hard after rising almost 25% on day one of trading. The stock is now 57% below those levels, as of Wednesday's close.                                                                                                                                          , Another Chinese stock that has plunged from its debut gains is JD Logistics, which raised more than $3 billion in its IPO. The stock was 36% below its first day closing price, based on its Wednesday close.                                                                                                                              , These are the 4 stocks to play the EV 'arms race,' according to one investment firm                                                                                                                                                                                                                                                        , Market gains may be harder to come by in 2022, but it could still be a positive year                                                                                                                                                                                                                                                       , Here are the top internet stock picks for 2022 as selected by Evercore ISI                                                                                                                                                                                                                                                                 , Those losses follow a number of issues including Beijing's ongoing crackdown on China's tech sector, which led to giants like Alibaba and Meituan being slapped with massive fines.                                                                                                                                                        , U.S. Treasury yields have also risen as the Federal Reserve signals it will soon begin to normalize monetary policy. Under such conditions, investors tend to avoid stocks in sectors like tech. These stocks could be hurt by rising rates which affect a company's ability to fund growth and also makes future cash flows less valuable., The fast-spreading omicron Covid variant has also further weighed on investor sentiment in recent weeks and dampened risk appetite, with questions remaining over the new strain's potential economic impact.                                                                                                                              , To be sure, poor post-IPO performances are not unique to the region.                                                                                                                                                                                                                                                                       , In a December note, Pitchbook's James Thorne and Jordan Rubio highlighted blockbuster 2021 market debuts elsewhere in the world that have also fallen sharply since going public.                                                                                                                                                          , One of those examples was Chinese ride-hailing firm Didi, which announced early this month it will delist from the New York Stock Exchange less than six months after going public. It is also making plans for a Hong Kong debut instead amid reports of political pressure from Beijing.                                                 , Other U.S.-listed firms that saw mega IPOs such as Robinhood and South Korea's Coupang, have also "lost significant value," they said.                                                                                                                                                                                                     , "This lackluster performance has led to a cooling off in the IPO market that has caused some new issuers to delay or downsize their IPO plans. When all is said and done, 2021 could represent a high point of the IPO market that may not be matched for years to come," said Thorne and Rubio.                                           , New York University's Aswath Damodaran told CNBC earlier this month that the post-IPO slumps could be due to some investors buying into "the big market delusion."                                                                                                                                                                         , Such investors are "not doing their homework" like examining the business models of these companies, with reality usually setting in as the first earnings report is released, the professor of finance at NYU's Stern School of Business explained.                                                                                       , "It's a slightly troubling sign, but by itself I don't think … it's a red flag. I think it's more a sign of the kinds of companies you've seen going public, many with small revenues, big losses and lots of potential," Damodaran said.                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                           , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 09:18:11 </td>
   <td style="text-align:left;"> Australian Shares Hover Near 4-Month High </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index held above 7,500 on Thursday, hovering close to 4-month highs despite surging local Covid infections, as gains in Australian miners offset losses in technology stocks. Prime minister Scott Morrison said on Wednesday that Australia needed a “gear change” to manage overburdened laboratories and get people out of isolation, with a plan to prioritize clinically urgent cases as infections surged across the country. A business group also called on state governments to continue easing Covid restrictions and ramp up use of rapid antigen tests to enable staff to return quickly to work. Australian miners supported the market with gains from BHP Group (1.6%), Pilbara Minerals (2.5%), Rio Tinto (1.2%), Mineral Resources (1.7%), AVZ Minerals (1.9%) and Syrah Resources (6.8%). As 2021 draws to a close, the benchmark index is set to add nearly 14% this year and reverse losses from the pandemic-battered 2020, boosted by record-low interest rates and monetary stimulus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/currency </td>
   <td style="text-align:left;"> 2021-12-30 09:13:00 </td>
   <td style="text-align:left;"> Japanese Yen Hits 4-week Low </td>
   <td style="text-align:left;"> USDJPY touched a 4-week low of 115.03, as the safe-haven currency fell out of favor among investors amid an improving risk appetite and optimism that the omicron variant won’t derail the global recovery. Moreover, the Bank of Japan signaled that it would lag behind other central banks in scaling back monetary stimulus. Inflation also remained subdued despite higher input costs as firms were reluctant to pass on rising costs to consumers. Last week, prime minister Fumio Kishida said that he hoped the BOJ continues to make efforts to achieve its 2% inflation target, expressing a desire for supportive monetary and fiscal policies. The Japanese government also approved a record 107.6 trillion yen budget for the fiscal year 2022 last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 08:38:59 </td>
   <td style="text-align:left;"> US Futures Flat After Dow, S&amp;P Notch Records </td>
   <td style="text-align:left;"> US stock futures were little changed on Thursday after the Dow and S&amp;P 500 closed at new records in the previous session amid a thinly traded final week of 2021. Dow Jones and S&amp;P 500 futures were mostly unchanged, while Nasdaq 100 futures fell about 0.2%. During regular trading on Wednesday the S&amp;P 500 advanced 0.14% to its 70th record close of the year. The Dow also rose 0.25%, its first record close since November, while the Nasdaq Composite declined 0.1%. The real estate, consumer defensive and healthcare sectors led the charge, with Biogen taking the spotlight after jumping 9.46% following reports that Samsung is in talks to acquire the company. Meanwhile, growth-oriented areas of the market stalled as Treasury yields crept higher, with the benchmark 10-year yield breaking above 1.5% on Wednesday, seen by analysts as a major headwind for equities in 2022. So far in the year, the S&amp;P 500 is up 27.6%, the Nasdaq 22.3%, and the Dow Jones 19.2%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59741141?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-30 08:01:46 </td>
   <td style="text-align:left;"> New home and car insurance rules mean change in prices </td>
   <td style="text-align:left;"> Prices paid for home and motor insurance are changing due to new rules coming into effect on 1 January to protect loyal and vulnerable consumers.                                                                                                                           , Anyone renewing their policy will pay no more than they would as a new customer, under regulations set by the Financial Conduct Authority (FCA).                                                                                                                            , That means prices for those who switch regularly will go up, while long-standing customers will pay less.                                                                                                                                                                   , The FCA said the move would save loyal customers £4.2bn over 10 years.                                                                                                                                                                                                      , Brian Brown, consumer finance expert at market analysts Defaqto, said there was no sign of insurers leaving the market as a result, meaning customers still had plenty of choice of products.                                                                               , The policy is designed to end cases of "price walking", which is when a customer is charged more year after year, by staying with the same insurance company - even though their risk is no greater.                                                                        , When announcing its plans, the FCA pointed to an example in which a new customer for home insurance typically paid £130 for a year's cover.                                                                                                                                 , But for the same policy, having stayed with the same insurer for five years, that annual premium rose to £238.                                                                                                                                                              , For motor insurance, new customers paid £285 while people who have been with their provider for more than five years paid £370, according to the FCA's example.                                                                                                             , The new rules are being brought in by the FCA in the New Year following a super-complaint from Citizens Advice about the loyalty penalty.                                                                                                                                   , Those who switched have received the best deals as new customers. Those who stayed loyal were charged more.                                                                                                                                                                 , Around 10 million policies across home and motor insurance are held by people who have been with their provider for five years or more.                                                                                                                                     , Matthew Upton, director of policy at Citizens Advice, said: "Rip-off renewal prices have seen consumers paying over the odds for far too long. No longer can you be exploited just for staying loyal."                                                                      , He added that people tended to be at a disadvantage if they were older, on lower incomes, or unable to access the internet.                                                                                                                                                 , "We welcome the FCA's bold new rules on home and motor insurance. We now need to see urgent action to protect consumers in the other markets," he said.                                                                                                                     , People can still shop around for the best deals, and will need to consider whether the policy matches their requirements.                                                                                                                                                   , However, premiums charged to all renewing home and private motor insurance customers by their insurance provider cannot be greater than the price they would charge to an equivalent new customer for the equivalent policy.                                                , Individual premiums can still be set at different levels depending on factors such as a customer's age, type of vehicle, driving record and history of claims.                                                                                                              , James Dalton, from the Association of British Insurers, said: "While the FCA recognises that these changes could lead to price rises for some who shop around regularly, all customers should get fairer outcomes in the UK's competitive home and motor insurance markets.", In October, the FCA introduced new rules requiring insurers to look more closely at how they offer fair value for consumers.                                                                                                                                                , It should also be made easier for consumers to cancel automatic policy renewals, and home and motor insurance firms must report more data to the regulator.                                                                                                                 , The man himself on ten key lyrics, including some of The Beatles' classics                                                                                                                                                                                                  , Abbey Road's amazing history of making music for films and games                                                                                                                                                                                                            , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 07:21:40 </td>
   <td style="text-align:left;"> S&amp;P/ASX 200 Hits 16-week High </td>
   <td style="text-align:left;"> AU200 increased to a 16-week high of 7519 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/construction-output </td>
   <td style="text-align:left;"> 2021-12-30 07:16:00 </td>
   <td style="text-align:left;"> South Korea Construction Output Extends Contraction in November </td>
   <td style="text-align:left;"> Construction output in South Korea dropped 5.6 percent year-on-year in November of 2021, following an upwardly revised 0.1 percent drop in the previous month. It was the fourteenth consecutive month of falling construction activity as civil engineering output plunged 24.5 percent (from 8.1 percent), and the building activity growth eased to 1.8 percent (from 2.8 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/industrial-production </td>
   <td style="text-align:left;"> 2021-12-30 07:10:00 </td>
   <td style="text-align:left;"> South Korea Industrial Output Grows More Than Expected </td>
   <td style="text-align:left;"> Industrial production in South Korea increased 5.9 percent year-on-year in November of 2021, after a 4.5 percent increase in the previous month and above market expectations of a 3.2 percent increase. The industrial activity accelerated the rebound after falling for the first time in September since October 2020. Manufacturing activity rose 6.2 percent, up from a 4.6 percent increase in October. On a seasonally adjusted monthly basis, industrial production rose 2.9%, following an upwardly revised 2.9 percent drop in October and below market expectations of a 2.5 percent increase </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/29/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2021-12-30 07:07:46 </td>
   <td style="text-align:left;"> Stock futures are flat after Dow, S&amp;P 500 close at record </td>
   <td style="text-align:left;"> , U.S. stock index futures were little changed during overnight trading Wednesday after the S&amp;P 500 and Dow Jones Industrial Average closed at new records.                                                                                                                                                                                                                                                     , Futures contracts tied to the Dow Jones Industrial Average inched higher, while S&amp;P 500 futures were unchanged. Nasdaq 100 futures were slightly lower.                                                                                                                                                                                                                                                       , During regular trading on Wednesday the S&amp;P 500 advanced 0.14% to its 70th record close of the year. This is the second highest number of record closes for the benchmark index during a calendar year, trailing just 1995's 77 record closing highs.                                                                                                                                                         , The Dow rose 90 points, or 0.25%, to also close at a record — its first since November. The 30-stock benchmark saw its sixth straight positive session. The Nasdaq Composite, however, declined 0.1%. Chip stocks came under pressure, with AMD, Xilinx and Nvidia all declining at least 1%.                                                                                                                 , Travel-related stocks also slid amid ongoing Covid-19 concerns, with the NYSE Arca Airline Index dipping 2.5%.                                                                                                                                                                                                                                                                                                , On the flip side, a number of consumer stocks rose to new all-time highs during the session, including Domino's Pizza, McDonald's, Yum Brands, Costco and Procter &amp; Gamble.                                                                                                                                                                                                                                   , Credit Suisse and JPMorgan pick stocks to buy in a high-flying Asian market                                                                                                                                                                                                                                                                                                                                   , These are the 4 stocks to play the EV 'arms race,' according to one investment firm                                                                                                                                                                                                                                                                                                                           , Here are the top internet stock picks for 2022 as selected by Evercore ISI                                                                                                                                                                                                                                                                                                                                    , All three major averages are in the green for December. The S&amp;P and Dow are on pace for a second positive month in the last three, while the Nasdaq Composite is on track for a third straight month of gains.                                                                                                                                                                                                , Wednesday's upward action for the Dow and S&amp;P continued a historically strong period for stocks, which has been dubbed the "Santa Claus rally." The S&amp;P 500 has notched a gain during the period — the last five trading days of the year followed by the first two session in January — 78.5% of the time since 1928, according to Bank of America.                                                          , "Santa has been good to investors this holiday season, and we look for another year of positive returns in 2022," said Scott Wren, senior global market strategist at Wells Fargo Investment Institute.                                                                                                                                                                                                       , With just two trading days left in 2021, the major averages are also on track to end the year in the green. The S&amp;P and Dow are up 27.6% and 19.2%, respectively. The Nasdaq's gained 22.3%, while the Russell 2000 is up 13.9%.                                                                                                                                                                              , "2021 was a terrific year for the equity markets," said Anu Gaggar, global investment strategist for Commonwealth Financial Network. "Between federal stimulus keeping the economy going, easy monetary policy from the Fed keeping markets liquid and interest rates low, and the ongoing medical improvement leading to surprising growth, markets have been in the best of all possible worlds," she added., Looking forward, Gaggar said 2022's performance depends on earnings and stock valuations.                                                                                                                                                                                                                                                                                                                     , Treasury yields creeping higher could prove to be a headwind for 2022, especially among growth-oriented areas of the market. The yield on the U.S. 10-year Treasury broke above 1.5% on Wednesday.                                                                                                                                                                                                            , "We expect interest rates to move modestly higher in 2022 based on near-term inflation expectations above historical trends and improving growth expectations once the impact of COVID-19 variants recede," said Lawrence Gillum, fixed income strategist for LPL Financial. "Our year-end 2022 forecast for the 10-year Treasury yield is 1.75–2.00%."                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                              , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/retail-sales-annual </td>
   <td style="text-align:left;"> 2021-12-30 07:06:00 </td>
   <td style="text-align:left;"> South Korea Retail Sales Growth Eases from 3-Month High </td>
   <td style="text-align:left;"> Retail sales in South Korea increased 4.6 percent year-on-year in November of 2021, easing from a 7.4 percent rise in the prior month, and marking the tenth straight month of gains in retail trade. On a monthly basis, retail sales decreased 1.9 percent, after rising 0.2 percent in the previous period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/us/2021/12/29/jury-verdict-ghislaine-maxwell-trial-vpx.cnn </td>
   <td style="text-align:left;"> 2021-12-30 06:50:24 </td>
   <td style="text-align:left;"> Jury finds Ghislaine Maxwell guilty on five of six counts - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/media/2021/12/29/hong-kong-news-outlet-closes-police-raid-stand-news-pkg.cnnbusiness </td>
   <td style="text-align:left;"> 2021-12-30 06:45:55 </td>
   <td style="text-align:left;"> Hong Kong independent news outlet closes after police raid - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/29/politics/trump-supreme-court-washington-post-bennie-thompson/index.html </td>
   <td style="text-align:left;"> 2021-12-30 05:27:22 </td>
   <td style="text-align:left;"> Trump wants Supreme Court to read Washington Post interview with Bennie Thompson - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)As the Supreme Court considers whether to take up former President Donald Trump's January 6 White House records case, Trump's attorney submitted to the court a new filing Wednesday making the court aware of a Washington Post interview with Rep. Bennie Thompson, who chairs the House select committee seeking the records.                                   , In the interview, the Mississippi Democrat said that the committee's investigation into Trump's delay in calling for his supporters to end their rioting at the US Capitol could lead to a criminal referral to the Justice Department.                                                                                                                                  , "That dereliction of duty causes us real concern," Thompson told the Post. "And one of those concerns is that whether or not it was intentional, and whether or not that lack of attention for that longer period of time, would warrant a referral."                                                                                                                    , Thompson added: "I can assure you that if a criminal referral would be warranted, there would be no reluctance on the part of this committee to do that," according to the Post.                                                                                                                                                                                         , RELATED: The January 6 committee formed 6 months ago. Here's what it's uncovered.                                                                                                                                                                                                                                                                                        , Trump's lawyers told the justices Wednesday that the comments back one of his case's key allegations: that the effort to obtain his White House records lacks a legitimate legislative purpose and thus should be blocked.                                                                                                                                               , "The Committee cannot make a mockery of Congress's constitutional mandate that its requests and investigation be supported by a 'valid legislative purpose,'" Trump's lawyers wrote. "It cannot embark on what is essentially a law enforcement investigation with the excuse that it might legislate based on information it turns up in the course of the exploration.", When the case was before the DC US Circuit Court of Appeals, Trump raised similar comments from the committee members about the possibility their investigation would expose wrongdoing by Trump.                                                                                                                                                                        , "The mere prospect that misconduct might be exposed does not make the Committee's request prosecutorial," the appeals court said earlier this month, rejecting the former President. "Missteps and misbehavior are common fodder for legislation."                                                                                                                       , The Supreme Court has not indicated how it intends to move forward with Trump's request to take up his case. The Democratic-run House and the Biden administration are expected to submit filings on Trump's request on Thursday.                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 05:18:12 </td>
   <td style="text-align:left;"> Toronto Stocks Hit 5-Week High </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, rose 0.5% to close at 21,345 on Wednesday, extending gains for the 5th session to five-week highs on Wednesday, in line with US stock markets, as investors were optimistic that the Omicron variant would not derail the economic recovery. The gains were sustained by a rise of 2% in energy stocks amid higher oil prices. Still, in Canada, infections have skyrocketed to unprecedented levels, with more than 2x times the daily infections seen at the peak of the April wave on Monday. Quebecois authorities said infected essential workers would continue to work in order to prevent severe staff shortages, a week after bars, gyms, and casinos were shut and restaurants were slapped with capacity constraints to curb the contagion rate of the virus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 05:18:00 </td>
   <td style="text-align:left;"> Brazil Stocks at 4-Week Low </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, fell 0.8% to close at 104,080 on Wednesday, the lowest in four weeks and underperforming its international peers as travel stocks weighed down amid Omicron jitters. Among the top losers, CVC plunged 7.4%, Azul dropped 7.1%, and Gol erased 6.5%. On the data front, the inflation gauge known as IGP-M, used in the readjustment of housing rents, jumped 17.78 percent in 2021, the second steepest increase in prices since 2002 after last year. On corporate news, Vale confirmed preliminary talks with the UK’s Anglo-American regarding a potential partnership for logistics and processing infrastructures in Brazil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/29/entertainment/dwayne-the-rock-johnson-interview/index.html </td>
   <td style="text-align:left;"> 2021-12-30 05:16:36 </td>
   <td style="text-align:left;"> Dwayne Johnson reflects on his record-breaking year - CNN </td>
   <td style="text-align:left;"> (CNN)Dwayne "The Rock" Johnson has plenty of reasons to toast 2021 with some Teremana.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , He produced and starred in two hit films, "Jungle Cruise" and "Red Notice," debuted his biographical sitcom "Young Rock," saw unprecedented sales growth with his Teremana tequila, and became the most followed American man on Instagram with 285 million followers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , At 49, with grit, charisma and determination to "deliver the goods," Johnson has segued from professional wrestler to movie star, major entrepreneur and someone nearly half of America would like to see as the next president of the United States, according to one poll.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , CNN spoke with Johnson this week about his monumental year. He addressed hype around his possible return to the "Fast and Furious" franchise and his potential political ambitions. He also offered a glimpse at how he plans to top his blockbuster 2021.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Our conversation, which has been lightly edited for flow and clarity, follows below.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , You've seen some great successes, any highlights? Reflecting back, anything you wish you would have done differently?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , "I worked hard, had some luck on my side and was able to accomplish a few things in 2021. A few highlights that come to mind, one would be completing two massive Seven Bucks Productions films, 'Red Notice' and 'Black Adam.' (Set for release in 2022.) Both presented a lot of challenges during Covid, but like so many businesses out there, we adjust, get clarity, create our new Covid strategy and get to work. Seven Bucks also just completed -- two weeks ago -- our second season of NBC's 'Young Rock.' I'm quite proud of everyone's efforts and talents to get the job done and deliver quality. And the other businesses in my portfolio have shown tremendous growth and moved along nicely in 2021 -- Teremana Tequila, ZOA Energy, Project Rock and XFL. As for anything I would've done differently in 2021, sure, I would've listened to my gut when it was telling me to slow down a bit. Enjoy these moments even more with your family and friends, because at the end of the day these joyful moments are the s*** that really matters in life. Sorry to cuss but that's the truth. Good lesson to always listen to that voice in your gut.", "Red Notice" received an enormous amount of praise, from both those in the industry and with audiences worldwide by becoming Netflix's most watched movie in the world for 2021, and most watched of all time. What do you think made "Red Notice" so successful?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , "First thing, we made a great movie for families around the world to enjoy. That's the bottom line. Deliver the goods. I always say I can bring people to the dance and with the trust they have in me, they'll dance one song. But then it's up to the quality I'm offering that will make them dance all night.  We made a great movie and people are dancing to it. Rawson Thurber did a tremendous job of writing and directing 'Red Notice' that attracted two of the biggest stars in the world, in Gal Gadot and Ryan Reynolds, and a dude who's only famous for his tattoos, raised eyebrow and a fanny pack. But dumb jokes aside, it's a monumental achievement for our Seven Bucks Productions to produce the most watched Netflix film of all time. 'Red Notice' was my first film on a streaming platform so it was critically important for myself and our Seven Bucks Company to deliver and move the streaming needle. What a holy s*** achievement and congrats to everyone involved."                                                                                                                                                                , What are your thoughts on the streaming wars among platforms and its impact on theatrical releases, does this play a part when discussing releases for your projects as a producer?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , "I say this with great clarity, we are in a tremendous time in our Hollywood industry as we are in the eye of a massive opportunity to listen and learn what our audience and our consumers want and just as important, how they want it. I believe strongly in our theatrical business and want us to continue to work hard to maintain that theatrical experience for our consumers. When a movie is done right, man it's pure magic in the theaters. And I also feel strongly that it's our job as creators, producers and deliverers of entertainment to always take care of and go to the people. I try and approach streaming platforms versus theatrical with an entrepreneurial spirit and vision. The power of possibilities and the needs of the audience, consumers first, best practice will emerge. We just have to be smart, open and flexible to change and listen to what the people say they want."                                                                                                                                                                                                                                                   , There was a lot of buzz that you may rejoin the "Fast and the Furious" franchise. We saw that Vin Diesel recently posted he wants you back. We know you addressed potentially returning months ago, but were you surprised by Vin's post?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , "I was very surprised by Vin's recent post. This past June, when Vin and I actually connected not over social media, I told him directly - and privately - that I would not be returning to the franchise. I was firm yet cordial with my words and said that I would always be supportive of the cast and always root for the franchise to be successful, but that there was no chance I would return. I privately spoke with my partners at Universal as well, all of whom were very supportive as they understand the problem.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Vin's recent public post was an example of his manipulation. I didn't like that he brought up his children in the post, as well as Paul Walker's death. Leave them out of it. We had spoken months ago about this and came to a clear understanding. My goal all along was to end my amazing journey with this incredible 'Fast &amp; Furious' franchise with gratitude and grace. It's unfortunate that this public dialogue has muddied the waters. Regardless, I'm confident in the 'Fast' universe and its ability to consistently deliver for the audience, and I truly wish my former co-stars and crew members the best of luck and success in the next chapter."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , As the most followed American man on Instagram, do you think anything has changed with how you have approached your own social media this past year?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , "That answer is yes. I still have my anchoring guidelines I follow: Be authentic, be real and try to make sure every social post has a quality and meaning behind it, offering some takeaway for people and being aware about never wasting anyone's time with a bulls***post about nothing. But I'll tell you, as we navigate our way through Covid's harsh ebbs and flows, I've found myself trying to use a much lighter touch with my words since things on social media are so easily triggering these days, clickbait stuff.  Lighter touch and quality I try to use daily when connecting with people through social media. And if I can make you laugh and smile, I'll try and do that too."                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Was becoming a tequila mogul always part of the plan? What's next for Teremana in 2022 and beyond?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , "Tequila mogul was not part of the initial strategy, but I'll sure take it. Our numbers were disclosed earlier this week and our Teremana growth is truly unprecedented. Our sales have exceeded over 600,000 nine-liter cases and in our spirits industry, that's an all-time record for first year sales. For context, George Clooney sold his Casamigos tequila brand to Diageo for $1 billion dollars and they were selling approximately 170,000 cases.  Teremana is currently selling over 600,000 cases. So you can extrapolate the math and valuation, astounding growth and I think it reflects our 'highest in quality and best in taste' mantra. I'm happy but not satisfied with what we've been able to accomplish with Teremana tequila thus far. The work is just beginning. My goal for 2022 and beyond is to make Teremana a true international tequila brand. We have the organization and international distribution expertise with our Mast-Jäegermeister partners, our Teremana team and just as important, we have the ambition and work ethic. "                                                                                                , You've said in the past, I believe specifically in your interview for your recent Vanity Fair cover, that you would not run for President in 2024 because you "don't know a thing about politics." Yet, according to a poll this spring, almost half of Americans would vote in your favor. Could "The Rock" still be a potential presidential candidate in the future?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , "Well, I think that poll of almost half of Americans being in favor of me running for president is so humbling. It sits me down and I don't know any other way to describe it. To have a little ability to potentially galvanize our country is humbling, very humbling. Might be the Teremana talking here but I still don't know a damn thing about being a politician. I don't know if I have that politician gene in my DNA. Leader? Yes. Patriot? All day long. Politician? No.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , I feel the best position I can be in right now is to be a trusted, nonjudgmental place for people; regardless of what side of the street you live on, what color you are, what you do for a living, how you choose to live your life, what your bank account says, whether you drive a car or take the bus. I don't care. None of that matters to me. Just work hard, take care of your family, be good to people, be kind to people, be straight up, honor your word and always [have] some fun along the way. And don't be an a**hole. Like I said, I don't think I'd make a good politician."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Do you have a New Year's goal or resolution?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , "To be honest, I usually don't have New Year's resolutions. I know I sound like an a**hole here but I'm the guy who usually just does it throughout the year. Whatever change needs to happen, I'll get it done and move on. But this past year has been different. It's opened my eyes a bit more to real change that needs to my attention. Work flow, work stream, what and who in my life really need my attention, what truly should be getting me out of bed. I've reached a point in my life this past year where I realized just how vital the idea and essence of time is; who and what gets my time these days.  We don't get time back, so in 2022 and beyond, the people, the projects, the energy, the everything. Life. If it gets my time and gets me out of bed, then I'll go to sleep knowing it was worth it and it was all time wisely spent. Time is our greatest and most valuable currency."                                                                                                                                                                                                                                                     , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-closes-record-high-its/story.aspx?guid={591C05AA-ACB1-4CBD-865E-1F0A3E347039}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-30 05:04:04 </td>
   <td style="text-align:left;"> Dow closes at record high in its longest rally since March, S&amp;P 500 ends at fresh peak - MarketWatch </td>
   <td style="text-align:left;"> The Dow Jones Industrial Average closed at a record high Wednesday, as investors pushed the blue-chip-stocks index to a sixth straight day of gains for its longest winning streak since March. The Dow 
        DJIA,
        +0.25%
       closed around 0.3% higher in a day of mixed trade that saw the S&amp;P 500 index 
        SPX,
        +0.14%
       rise about 0.1% to an all-time closing high and the technology-laden Nasdaq Composite 
        COMP,
        -0.10%
       finish about 0.1% lower, according to preliminary data from FactSet. High-growth tech stocks tend to be sensitive to rising rates. The yield on the 10-year Treasury note 
        TMUBMUSD10Y,
        1.547%
       climbed to 1.542% Wednesday, the highest since Nov. 24 based on trading levels at 3 p.m. Eastern Time, according to Dow Jones Market Data. Investors traded amid omicron variant concerns and fresh economic data showing the U.S. trade deficit in goods surged to an all-time high in November, a trade gap that largely reflected faster improvement in the world's largest economy compared to most other countries in the pandemic., Here's what to know.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/real-estate/reits-romped-2021-property-values-soared </td>
   <td style="text-align:left;"> 2021-12-30 04:47:32 </td>
   <td style="text-align:left;"> REITs romped in 2021 as property values soared </td>
   <td style="text-align:left;"> State Street Realty president George Pino shares details on the Sunshine State's real estate market.                                                                                                                                                                                                                                                    , Investors who bet on real estate investment trusts at the beginning of 2021 are reaching for top-shelf champagne these days as they prepare to celebrate the new year.                                                                                                                                                                                  , They can afford to splurge. The FTSE NAREIT Equity REITs index was up 36% in 2021, compared with 26% for the S&amp;P 500 as of Dec. 23, according to real estate analytics firm Green Street. If that trend continues for the remainder of the year, 2021 will be the REIT index’s best year since 1976 in terms of absolute performance, Green Street said., But will the same strategy work again in 2022? Investors who are planning to double down on this year’s REIT strategy might want to hold off for now on buying Dom Pérignon by the case, some analysts warn.                                                                                                                                            , Signs advertise a business space for lease at a shopping plaza, Tuesday, Jan. 12, 2021, in Orlando, Fla.  (AP Photo/John Raoux / AP Newsroom)                                                                                                                                                                                                           , For starters, REIT strength this year was partly a rebound after a bad 2020. With office, retail, and other property types hammered by the pandemic, the sector fell 8% last year compared with an increase of 18.4% for the S&amp;P 500, Green Street said.                                                                                                , Next year it is doubtful this year’s momentum can be maintained. "It’s hard for us to see the group putting in a similar year in 2022," said Steve Sakwa, an analyst with Evercore ISI.                                                                                                                                                                 , WILL REAL ESTATE BOOM COOL OFF IN 2022?                                                                                                                                                                                                                                                                                                                 , Meanwhile, dangers are lurking in the REIT sector. Concerns about the omicron variant of the Covid-19 virus already are dampening hopes that millions of people who have been working from home throughout the pandemic will return to offices in January.                                                                                              , REIT shares, like those of numerous other companies, also could face a bumpy ride in 2022 from inflation and rising interest rates. "Headline risk around additional variants, inflation and interest rates will create significant volatility over the next 12 months," said a December report on REITs by Evercore ISI.                               , A few property types have continued to thrive throughout the pandemic. For example, total returns of industrial REITs have been over 40% since the pandemic hit because of the rise in online retail sales, according to analysts.                                                                                                                      , Self storage warehouse with open red doors outside Marshall, Texas Americana.  (Visions of America/Universal Images Group via Getty Images / Getty Images)                                                                                                                                                                                              , Total returns of self-storage landlords have increased more than 80% during that same time frame as people working from home have decluttered, analysts said. "Folks wanted the extra space," said Michael Mueller, an analyst with JPMorgan Chase &amp; Co. "They cleared out the back bedroom."                                                           , Meanwhile, REITS that own properties like office buildings, malls, senior housing, and hotels that depend on business travel have been tracking the ups and downs of the pandemic since early 2020. Their stocks have tumbled when new variants have appeared and soared with promising news about vaccines.                                            , "When you think of 2021, everything started with the vaccine news in November 2020," said Cedrik Lachance, Green Street’s head of research.                                                                                                                                                                                                             , PENDING HOME SALES FALL 2.2% IN NOVEMBER AS RISING PRICES MAKE BUYERS HESITANT                                                                                                                                                                                                                                                                          , Good news about vaccines as 2021 began boosted the performance and share prices of some REITs faster than expected. For example, demand soared in the first half of 2021 for rental apartments in cities like New York and San Francisco that had seen an exodus of renters in 2020.                                                                    , Shoppers also surprised some analysts by returning to malls so quickly. For example, strong sales helped push the share price of Simon Property Group Inc., the largest mall owner in the U.S. to above $150 a share, which is where it was trading before the pandemic hit.                                                                            , Shoppers browse the stores at the Brookfield Place indoor mall on December 27, 2021 in New York City.  (Photo by Scott Heins/Getty Images / Getty Images)                                                                                                                                                                                               , The rise in inflation, so far, has been good for REITs because it has helped drive up mergers and acquisitions volume, as well as sales volume and values of individual properties. Many investors consider real estate an inflation hedge because owners can raise rents to stay ahead or at least keep pace with rising prices.                       , "If the cost of building real estate goes up because of inflation, you don’t have the ability to build more supply until rents get to a certain level to justify it," said Tony Paolone, analyst with JPMorgan.                                                                                                                                         , But inflation may be painful for highly leveraged property owners next year if it sparks sharply higher interest rate costs. Inflation and higher rates also could lead to an economic downturn and drops in demand for a range of property types.                                                                                                      , READ MORE ON FOX BUSINESS BY CLICKING HERE                                                                                                                                                                                                                                                                                                              , Health news in 2022 will be even more of a wild card for REITs, analysts say. Bad news will likely hurt property types like office and senior housing while helping REITs that specialize in data centers which see strong demand when people are sitting at home streaming movies and TV shows.                                                        , Good news will boost malls and hotels. Mr. Lachance, of Green Street, predicted a possible repeat of the "revenge spending and revenge traveling" that has occurred when infection rates have fallen. To get back at the virus, people "hit the mall and buy things because it makes them feel good," he said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 04:42:00 </td>
   <td style="text-align:left;"> S&amp;P and Dow Extends Rally </td>
   <td style="text-align:left;"> US stocks traded mixed on Wednesday, the Dow Jones extended the recent rally for the 6th session and added almost 100 points to reach a new all-time high sustained by the gains of over 1% in P&amp;G, Home Depot, Nike, and Walgreens Boots Alliance. The S&amp;P rebounded from last session fall and rose 0.2% to a fresh record high buoyed by the surge of over 9% in Biogen stocks after a report showed that the company is in the process to be acquired by Samsung in a $40 billion deal. On the other hand, the tech-heavy Nasdaq Composite slipped 0.1% as the tech stocks were dragged down by expectations of higher interest rates after the 10-year government bond yield increased more than 5 bps. Still, investors keep an eye on the unfoldings of the spread of the covid strain after the number of covid cases almost doubled in December, wheres remained optimistic that the outbreak will not derail the economic growth. So far in the year, the S&amp;P 500 is up 29.5%, the Nasdaq 24.1%, and the Dow Jones 20.7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 04:34:04 </td>
   <td style="text-align:left;"> Dow Jones Hits All-time High </td>
   <td style="text-align:left;"> US30 increased to an all-time high of 36566 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/29/politics/melania-trump-steps-back-into-the-public-eye/index.html </td>
   <td style="text-align:left;"> 2021-12-30 04:22:25 </td>
   <td style="text-align:left;"> Melania Trump steps back into the public eye  - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)After months of relative public silence, former first lady Melania Trump before Christmas emerged from private life to announce a new project: A piece of artwork, a watercolor closeup of her eyes, in the form of a non-fungible token (NFT) was now available for purchase.                                                                                                                                                                                                                                                                                                                                                                               , It was an unusual move for any former first lady, to delve into the world of blockchain sales, but Trump has never been a predictable nor typical political spouse.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , "I am proud to announce my new NFT endeavor, which embodies my passion for the arts, and will support my ongoing commitment to children through my Be Best initiative," said Trump in a statement released via her social media platforms and on her website. Trump has since posted on her Twitter account 17 times about the endeavor.                                                                                                                                                                                                                                                                                                                           , Her NFT, entitled "Melania's Vision," and drawn by French artist Marc-Antoine Coulon, is available through December 31 through the cryptocurrency Solana, at a cost of approximately $175 -- depending on the market -- and has an authenticated identity via blockchain. The sales could be incredibly lucrative for Trump, one of several celebrities -- including Paris Hilton, Shawn Mendes, Tom Brady, Kate Moss and Grimes -- who have recently dipped into the NFT market and emerged hundreds of thousands, if not millions, of dollars richer. Fans are often enticed by the opportunity to own a unique digital piece of memorabilia or original artwork., Trump's NFT also comes with an audio clip of her saying: "My vision is: Look forward with inspiration, strength and courage."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , "Through this new technology-based initiative, we will provide children computer science skills, including programming and software development, to thrive after they age out of the foster care community," added Trump in Thursday's statement, noting not every dollar of profit is intended solely for her, yet neglecting to clarify how, when and to what extent the charitable component will be a part of the process.                                                                                                                                                                                                                                     , Coulon, the artist, had perhaps been filled in on details the public has not, writing on his Instagram page: "The project has been clearly defined and its objectives and the charities involved are very much in line with the spirit in which the project was motivated." A spokesperson for Coulon did not return a request for comment.                                                                                                                                                                                                                                                                                                                        , Trump's statement said "a portion of the proceeds" will go to children aging out of the foster care system, but no specifics on what that portion is were provided. Several attempts by CNN to reach Trump's spokesperson for clarity on these components of the NFT went unanswered.                                                                                                                                                                                                                                                                                                                                                                              , "I'm confused by it. It's very random as a project and seems tone deaf to release online artwork of yourself for $150," said a former White House official who worked with Melania Trump on several of her East Wing initiatives, and one of several acquaintances or former Trump staff who spoke with CNN on condition of anonymity to maintain personal relationships. "The timing seems odd too -- Covid and natural disasters are impacting the country, and many people are struggling financially."                                                                                                                                                         , Trump, who embraces a wealthy lifestyle, has not indicated publicly, or privately to those who spoke to CNN, that she is in any financial need. "With Melania's personal wealth, I certainly hope the 'portion of proceeds' going to help kids is significant," said another person who worked with her for several years.                                                                                                                                                                                                                                                                                                                                         , 'Why now?'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , When she left Washington in January, Trump re-embraced her fondness for a low-profile life, retreating to Palm Beach, where she now resides full-time at Mar-a-Lago. For several months after her departure from the White House, Trump did not appear publicly, nor did she establish a course of directives for her Be Best initiative.                                                                                                                                                                                                                                                                                                                          , Since last spring, she has tweeted sporadically, mostly images and memories from her time as first lady; in September she tweeted just twice, and nothing in October.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , However, in November, on the heels of her first public remarks at an event put on by the Log Cabin Republicans -- held downstairs from her private quarters at Mar-a-Lago in the club's ballroom -- Trump seemed to get a fresh yen for the spotlight.                                                                                                                                                                                                                                                                                                                                                                                                             , "It was like all of the sudden she remembered she liked when people were noticing her," said another Trump acquaintance.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , At the event, Trump was honored with the group's Spirit of Lincoln Award and made brief acceptance remarks at a black-tie dinner attended by invited guests and her husband, former President Donald Trump.                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Since then, the former first lady has ramped up her social media output, tweeting regularly on topics both national (a tribute to the anniversary of Pearl Harbor), and local (sending prayers to those in Kentucky following the deadly tornadoes). She tweeted photographs of a Thanksgiving visit to a Florida children's foster care center, and this month, photos of herself, dressed in nautical stripes, on a Coast Guard vessel wishing a special holiday message to service members.                                                                                                                                                                     , Then came the announcement of the NFT, and a barrage of retweets of subsequent press stories about her new moneymaking venture.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , "Why now?" asks the acquaintance, who suggests the lure of attention may be tied to Trump's desire to re-establish her brand. "To some degree she thinks she's an influencer. This is a way to stay relevant. If you think his fans love President Trump, they worship Melania. There is nothing she can do or say that they won't support."                                                                                                                                                                                                                                                                                                                       , More NFTs are coming                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , A second NFT piece will likely be on offer next month, a preview of which is scheduled for January 4, with a live date of January 11, according to information on Trump's website, MelaniaTrump.com. The website describes part of the impetus for releasing the first NFT was her "personal journey" from Slovenia to the White House.                                                                                                                                                                                                                                                                                                                            , "The beauty and hardships of individuals, majestic landscapes and profound architecture have entered her lens and remain in her heart," says the description.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , It is unclear who is advising Trump on her decision to enter the NFT market, but the former White House official suggests this is Trump's way of "trying to look busy," something the former first lady has not particularly portrayed to the public since leaving the White House.                                                                                                                                                                                                                                                                                                                                                                                , "This is not exactly using her platform for larger global or domestic impact," this person said. "This is ostensibly a quick moneymaker. It's a classic Trump move, using their brand and their supporters to cash in."                                                                                                                                                                                                                                                                                                                                                                                                                                            , Typically, most modern first ladies establish foundations or organizations -- generally not-for-profit -- that further the initiatives they began during their White House tenures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , For Laura Bush, that has come partly in the form of continuing her work helping Afghan women, as well as supporting America's libraries and educational reading programs. Michelle Obama has several official endeavors that push her work supporting girls and education, college attendance and voting rights.                                                                                                                                                                                                                                                                                                                                                   , Trump has said she is continuing her Be Best cause, but there has been no official output of events or dedicated objectives.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Donald Trump's crypto flip-flop                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , As first lady, Trump prided herself on not always aligning her East Wing messaging with that of the West Wing, which could at times publicly place her views in stark opposition to those of the President. Her former spokeswoman, Stephanie Grisham, told CNN several times that the former first lady did what she chose to do when she chose to do it and acted "independently" of her husband.                                                                                                                                                                                                                                                                , Trump's delving into the world of NFT appears another example of her inattention to the former President's public comments, flying in the face of his recent takes on cryptocurrency, which he publicly bashed during two separate interviews with Fox Business.                                                                                                                                                                                                                                                                                                                                                                                                   , Cryptocurrency, Donald Trump said in June, is a "scam against the dollar," and he questioned the veracity of the rising trend.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , "The currency of this world should be the dollar," said Trump, adding, "I think they should regulate them very, very high."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , In August he doubled down on that dislike, saying cryptocurrencies are "potentially a disaster waiting to happen," and that he has "not been a big fan."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , However, his wife's new website, from which people may click their way to a cyber-purchase of her water-colored eyeballs, includes an entire page dedicated to explaining the complex world of NFTs, blockchain and cryptocurrency. It even includes a link to a suggested "digital wallet" platform from which customers can use Solana cryptocurrency to purchase Trump's limited release NFT.                                                                                                                                                                                                                                                                   , A day after "Melania's Vision" was revealed, Donald Trump seemed to have fresh clarity on crypto.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , "Congratulations to my wife, Melania," he said via a statement released to the public from his office. "The launch of Melania's new NFT business epitomizes our American Spirit of ingenuity, creativity, and entrepreneurship. By leveraging blockchain technology, MelaniaTrump.com will provide Melania's fans, connoisseurs of the arts, and the public at large the ability to collect rare and limited edition pieces while benefiting children in the foster care community."                                                                                                                                                                               , CNN asked Trump's spokeswoman if the statement meant Trump has changed his mind about viewing cryptocurrency as a "scam" now that his wife is involved with NFTs, but did not receive a response.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/monthly-gdp-yoy </td>
   <td style="text-align:left;"> 2021-12-30 04:05:48 </td>
   <td style="text-align:left;"> Russia GDP Growth at 5-Month High in November </td>
   <td style="text-align:left;"> Russia's gross domestic product rose 5.2 percent year-on-year in October of 2021, accelerating easing from a downwardly revised 4.8 percent rise in the previous month. It was the highest GDP growth since July, as output grew at a higher pace for agriculture (12.9 percent vs 5.5 percent) and construction (6.9 percent vs 0.0 percent). Meanwhile, output eased for retail (3.1 percent vs 4.3 percent), services (14.9 percent vs 15.1 percent), and catering (10.6 percent vs 12.8 percent). Considering the first eleven months of the year, the economy advanced 4.7 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/elon-musks-spacex-raises-over-337m-in-fresh-funding </td>
   <td style="text-align:left;"> 2021-12-30 03:32:49 </td>
   <td style="text-align:left;"> Elon Musk's SpaceX raises over $337M in fresh funding </td>
   <td style="text-align:left;"> Blue Origin's third human spaceflight, the first with 6 on board.                                                                                                                                                                                                   , Billionaire Elon Musk's SpaceX has raised $337.4 million in equity financing, the rocket company disclosed in a regulatory filing on Wednesday.                                                                                                                     , FILE - In this Aug. 27, 2017 file photo, SpaceX CEO Elon Musk congratulates teams competing on the Hyperloop Pod Competition II at SpaceX's Hyperloop track in Hawthorne, Calif. (AP Photo/Damian Dovarganes, File) (AP Photo/Damian Dovarganes, File / AP Newsroom), SpaceX, which counts Alphabet Inc and Fidelity Investments among its investors, hit $100 billion in valuation following a secondary share sale in October, according to CNBC. It had raised about $1.16 billion in equity financing in April.                       , SpaceX did not immediately respond to Reuters' request for more details on the latest funding round.                                                                                                                                                                , SPACEX PUSHES BACK ON ‘UNSUBSTANTIATED’ COVID OUTBREAK REPORTS                                                                                                                                                                                                      , The company competes with former Amazon.com Chief Executive Jeff Bezos's space venture Blue Origin and billionaire Richard Branson's Virgin Galactic in the burgeoning constellation of commercial rocket ventures.                                                 , All three rocket companies have successfully launched civilians into space. According to Morgan Stanley, the space economy could be worth $1 trillion by 2040.                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                         , Musk, who also leads several futuristic companies including Tesla Inc, Neuralink and Boring Co, said earlier this year that SpaceX will be landing its Starship rockets on Mars well before 2030.                                                                   , SpaceX has already launched numerous cargo payloads and astronauts to the International Space Station for the National Aeronautics and Space Administration (NASA). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biogen-stock-surges-after-report/story.aspx?guid={3D3B23CB-19B7-4E86-99F2-AF3650A7EDF7}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-30 03:29:08 </td>
   <td style="text-align:left;"> Biogen stock surges after report of talks to be bought by Samsung in a deal that could be valued at more than $40 billion - MarketWatch </td>
   <td style="text-align:left;"> Shares of Biogen Inc. 
        BIIB,
        +9.46%
       shot up 8.9% in afternoon trading Wednesday, after the Korea Economic Daily reported that the U.S.-based drug maker is in talks to be acquired by South Korea-based conglomerate Samsung Group in a deal that could value Biogen at roughly $42 billion. That would represent an 11% premium to Biogen's current market capitalization of about $37.88 billion. Citing investment banking sources, the report said Biogen had approached Samsung about a deal to sell its shares, in a deal valued at more than 50 trillion won. Back in 2011, Samsung and Biogen had agreed to form a joint venture to develop bio-pharmaceuticals. Biogen's stock has gained 5.0% year to date, while the SPDR Health Care Select Sector ETF 
        XLV,
        +0.57%
       has rallied 24.5% and the S&amp;P 500 
        SPX,
        +0.14%
       has advanced 27.6%., The U.S. has started shipping some doses of the recently authorized COVID-19 antivirals developed by Pfizer and Merck.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-59818796?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-30 02:50:57 </td>
   <td style="text-align:left;"> Apple puts Indian iPhone factory 'on probation' </td>
   <td style="text-align:left;"> Apple has placed an iPhone factory in southern India "on probation" following protests over food poisoning and living conditions.                                                                                                                    , An audit by Apple found that remote dining rooms and dormitories used by workers did not meet requirements.                                                                                                                                          , Around 250 women who worked at the Foxconn plant were affected by food poisoning, with more than 150 ending up in hospital, local media reported.                                                                                                    , Foxconn apologised and said it was investigating the situation.                                                                                                                                                                                      , "We are very sorry for the issue our employees experienced and are taking immediate steps to enhance the facilities and services we provide," the Taiwanese firm said in a statement.                                                                , The factory has been closed since 18 December, when the protests began.                                                                                                                                                                              , Apple has not specified what being on probation means but in the past it has declined to award new business to facilities on probation until problems are resolved.                                                                                  , An Apple spokesman said: "Following recent concerns about food safety and accommodation conditions at Foxconn Sriperumbudur, we dispatched independent auditors.                                                                                     , "We found that some of the remote dormitory accommodations and dining rooms being used for employees do not meet our requirements, and we are working with the supplier to ensure a comprehensive set of corrective actions are rapidly implemented.", The iPhone factory, which is about 25 miles (40km) from Chennai, employs 17,000 people.                                                                                                                                                              , The food-poisoning cases and subsequent protests also led the Tamil Nadu state government to ask Foxconn to review its worker facilities.                                                                                                            , Last year, Apple had to place another iPhone manufacturing partner on probation after worker riots broke out over unpaid wages at the partner's factory near Bangalore.                                                                              , The man himself on ten key lyrics, including some of The Beatles' classics                                                                                                                                                                           , Abbey Road's amazing history of making music for films and games                                                                                                                                                                                     , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/2-year-note-yield </td>
   <td style="text-align:left;"> 2021-12-30 02:45:16 </td>
   <td style="text-align:left;"> Japan 2Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Japan 2 Year Government Bond Yeld increased to a 3-year high of -0.085% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/20-year-bond-yield </td>
   <td style="text-align:left;"> 2021-12-30 02:44:37 </td>
   <td style="text-align:left;"> Japan 20Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> Japan 20 Year Government Bond Yeld increased to a 4-week high of 0.477% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/5-year-note-yield </td>
   <td style="text-align:left;"> 2021-12-30 02:44:31 </td>
   <td style="text-align:left;"> France 5Y Bond Yield Hits 8-week High </td>
   <td style="text-align:left;"> France 5 Year Government Bond Yeld increased to a 8-week high of -0.349% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/52-week-bill-yield </td>
   <td style="text-align:left;"> 2021-12-30 02:44:16 </td>
   <td style="text-align:left;"> Japan 52W Bond Yield Hits Near 6-year High </td>
   <td style="text-align:left;"> Japan 52 Week Government Bond Yeld increased to a near 6-year high of -0.084% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/western-digitals-stock-surges-pace/story.aspx?guid={E3530A94-CFC1-4730-A31F-405E877CABAB}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-30 02:25:12 </td>
   <td style="text-align:left;"> Western Digital's stock surges to pace the S&amp;P 500's winners after rival Samsung has to 'adjust' operations due to COVID - MarketWatch </td>
   <td style="text-align:left;"> Shares of Western Digital Corp. 
        WDC,
        +5.24%
       shot up 5.6% in afternoon trading Wednesday toward a sixth-straight gain, enough to make the data storage company's stock the biggest gainer among S&amp;P 500 
        SPX,
        +0.14%
       components. Benchmark analyst Mark Miller said he believes the rally is being driven by South Korea-based rival Samsung Electronics Co. Ltd.'s 
        005930,
        -0.13%
       announcement that it had to "temporarily adjust operations" a its manufacturing facilities in Xi'an, China, had to put its plant Xian, China as a result of the "ongoing COVID-19 situation." Miller reiterated the buy rating he's had on Western Digital's stock since at least the past 2 1/2 years, and kept his stock price target at $92, which implies a TK% upside from current levels. The stock, which was headed for the highest close since Aug. 11, has soared 18.7% during its current win streak, which would be the longest since the six-day stretch ended Feb. 19. The stock's rally Wednesday comes as the SPDR Technology Select Sector 
        XLK,
        +0.09%
       slipped 0.1% while the S&amp;P 500 inched up 0.1%. , Elon Musk sold another $1 billion worth of Tesla Inc. stock Tuesday, as he closes in on his goal of divesting 10% of his stake in the electric-vehicle maker.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/champagne-shortage-ahead-of-new-years-eve-as-supply-chain-issues-hit-wine-industry </td>
   <td style="text-align:left;"> 2021-12-30 02:15:09 </td>
   <td style="text-align:left;"> Champagne shortage ahead of New Year's Eve as supply chain issues hit wine industry </td>
   <td style="text-align:left;"> Wine Spectator senior editor Alison Napjus explains how supply chain issues has impacted the industry.                                                                                                                                     , Wine Spectator senior editor Alison Napjus warned on Wednesday, two days before New Year’s Eve, that "it could be tough to find some of your favorite labels this year" as supply chain disruptions have been impacting the industry.      , Napjus noted on "Mornings with Maria" that the issues hit the wine industry in a "perfect storm" ahead of the holiday when champagne is in strong demand.                                                                                  , Several companies have noted higher logistics-related costs and disruptions to their normal operations. Vineyards are no exception as the backlog at ports and the truck driver shortage have left them short of products.                 , The issues have also impacted consumers in the form of empty shelves and higher prices.                                                                                                                                                    , Wine Enthusiast Magazine reported earlier this month that the U.S. is currently in the early stages of a champagne shortage that is expected to last several years.                                                                        , Earlier this month, Michael Bilello, senior vice president of communications and marketing of Wine &amp; Spirits Wholesalers of America, said increased costs could soon be passed to consumers.                                               , "As the cost of business and challenges of doing business impact the wine and spirits industry, consumers are going to see that on the shelves or their bars and restaurants," Bilello said.                                               , SUPPLY CHAIN BOTTLENECKS SOUR WINE INDUSTRY AMID BOTTLE SHORTAGE                                                                                                                                                                           , Dr. Kaan Kurtural, a viticulture specialist with the University of California in Davis, explains how the supply chain crisis is impacting the wine industry. FOX Business' Kelly O'Grady reports.                                          , He noted that in a recent survey conducted by SipSource, 43% of suppliers and distributors said they expect to see an increase in the price of wine.                                                                                       , Napjus stressed on Wednesday that shipping delays and the truck driver shortage has been a challenge for the wine industry.                                                                                                                , "It’s not even just that basic transportation issue. We’re also looking at things like shortages of the cage that goes on top of your bottle, labels, boxes to put wine in," she said.                                                     , "So you put that all together with the huge increase in demand we’ve seen for champagne this year [and] for other sparkling wines and of course, the holiday season, and it could be tough to find some of your favorite labels this year.", Dr. Kaan Kurtural, a viticulture specialist with the University of California Davis, told FOX Business in October that a shortage of bottles due to supply chain disruptions was an issue for the wine industry.                           , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                , Kurtural pointed out that the industry is currently facing even more issues, including seeds being "difficult to come by" and the price of fertilizer shooting "through the roof."                                                         , Demand for wine has increased during the coronavirus pandemic, as Americans sheltered in place to avoid potential infection.                                                                                                               , Market research and analysis firm Nielsen reported that wine has led as one of the strongest alcoholic categories last year.                                                                                                               , Wine Spectator senior editor Alison Napjus weighs in, explaining the issues the industry has been dealing with amid supply chain disruptions.                                                                                              , As the demand for wine increased, the industry has been dealing with a severe drought and now supply chain issues on top of that. The issues have been contributing to a decrease in wine production.                                      , READ MORE FROM FOX BUSINESS                                                                                                                                                                                                                , FOX Business’ Jiovanni Lieggi contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-59819664?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-30 02:07:23 </td>
   <td style="text-align:left;"> TikTok moderator sues over 'psychological trauma' </td>
   <td style="text-align:left;"> A former TikTok moderator is suing the company, claiming it failed to protect her mental health after "constant" exposure to traumatic video content.                                                                                                                   , Candie Frazier says she reviewed videos that featured "extreme and graphic violence" for up to 12 hours a day.                                                                                                                                                          , She says she suffers from "significant psychological trauma", including anxiety, depression, and post-traumatic stress disorder.                                                                                                                                        , TikTok says it strives to promote "a caring working environment".                                                                                                                                                                                                       , In September TikTok announced 1 billion people were using the app each month. It now has more hits than Google, according to Cloudflare, an IT security company.                                                                                                        , To protect its users, the video-sharing platform uses thousands of in-house and contract content moderators to filter out videos and accounts that break its rules.                                                                                                     , Ms Frazier is suing both TikTok and its parent company, Chinese tech-giant Bytedance.                                                                                                                                                                                   , She claims that in her role as a moderator she watched graphic content, including videos of sexual assault, cannibalism, genocide, mass shootings, child sexual abuse, and the mutilation of animals.                                                                   , Ms Frazier, who worked for a third-party contractor, Telus International, says she was required to review hundreds of videos a day.                                                                                                                                     , According to the lawsuit filed with a federal court in California last week, Ms Frazier suffered "significant psychological trauma, including anxiety, depression, and post-traumatic stress disorder" because of the material she was required to review.              , The lawsuit claims that while she was not a TikTok employee, the social-media giant "controlled the means and manner in which content moderation occurred".                                                                                                             , Ms Frazier alleges that in order to handle the volume of content, she was expected to review, she had to watch as many as 10 videos simultaneously.                                                                                                                     , In the lawsuit it is claimed that during a 12-hour shift moderators were permitted a 15-minute break after the first four hours of work, and then a 15-minute break every subsequent two hours. In addition there was a one-hour lunch break.                           , It alleges that TikTok failed to meet industry standards designed to reduce the impact of content moderation, and that the firm violated California labour law by not providing a safe work environment.                                                                , TikTok would not comment on the "on-going" case, but the firm did say it strived to "promote a caring working environment for our employees and contractors".                                                                                                           , The company added: "Our safety team partners with third-party firms on the critical work of helping to protect the TikTok platform and community, and we continue to expand on a range of wellness services so that moderators feel supported mentally and emotionally.", TikTok believes its measures to protect moderators are in line with industry best practice.                                                                                                                                                                             , Last year, TikTok was among a coalition of social-media giants that created guidelines to safeguard employees who have to filter out child sex-abuse imagery.                                                                                                           , Telus International, which is not a defendant in the case, said it had robust mental-health programmes in place and told the Washington Post, its employees could raise concerns through "several internal channels" -  something it claimed Ms Frazier had not done.   , The firm told the paper Ms Frazier's allegations were "entirely inconsistent with our policies and practices".                                                                                                                                                          , The BBC has approached Telus International for comment.                                                                                                                                                                                                                 , In 2020, another social-media goliath, Facebook, agreed to pay out $52m (£39m) in compensation to moderators who had developed PTSD as a result of their job.                                                                                                           , The man himself on ten key lyrics, including some of The Beatles' classics                                                                                                                                                                                              , Abbey Road's amazing history of making music for films and games                                                                                                                                                                                                        , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-30 02:02:17 </td>
   <td style="text-align:left;"> France 10Y Bond Yield Hits 8-week High </td>
   <td style="text-align:left;"> France 10 Year Government Bond Yeld increased to a 8-week high of 0.203% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-30 02:02:16 </td>
   <td style="text-align:left;"> Germany 10Y Bond Yield Hits 7-week High </td>
   <td style="text-align:left;"> Germany 10 Year Government Bond Yeld increased to a 7-week high of -0.175% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/industrials/south-africa-court-shell-halt-seismic-survey </td>
   <td style="text-align:left;"> 2021-12-30 02:01:12 </td>
   <td style="text-align:left;"> South Africa court rules against Shell, orders company halt seismic survey </td>
   <td style="text-align:left;"> Taylor Financial Services owner Eszylfie Taylor and Former Trump adviser Steve Moore discuss personal financial actions that can result in a happier financial life in the new year                                                                                                         , A South African court has blocked Shell’s seismic survey along the country’s eastern coastline, handing environmentalists a strong victory against the oil company.                                                                                                                         , The survey aimed to examine a 155-mile stretch of coastline in Eastern Cape Province. The seismic blasting process involves firing high-powered air guns every 10 seconds and measuring the echoes to detect cavities under the sea bed.                                                    , High Court Judge Gerald Bloem said Shell initially earned the right to explore the waters based on "a substantially flawed consultation process," the BBC reported.                                                                                                                         , APPLE SET TO BECOME FIRST $3T COMPANY THIS YEAR?                                                                                                                                                                                                                                            , "This case is really a culmination of the struggle of communities along the Wild Coast for the recognition of their customary rights to land and fishing, and to respect for their customary processes," Wilmien Wicomb, attorney at the Legal Resource Center, said.                       , Royal Dutch Shell said on Monday it would sell its Permian Basin assets to ConocoPhillips for $9.5 billion in cash, an exit from the largest U.S. oilfield for the energy major shifting its focus to the clean energy transition. (Associated Press)                                       , Wicomb hailed the verdict as one of "huge significance."                                                                                                                                                                                                                                    , PENDING HOME SALES FALL 2.2% IN NOVEMBER AS RISING PRICES MAKE BUYERS HESITANT                                                                                                                                                                                                              , Shell’s approval for the project may have resulted from an outdated legislation, since it derived from Shell receiving the green light in 2014 just months before the legislation changed, according to The Guardian.                                                                       , A different high court on Dec. 3 decided in Shell’s favor, but the new ruling contends that Shell did not have the necessary environmental approvals.                                                                                                                                       , BIDEN NOT A ‘LEADER’ ON CLIMATE CHANGE, GRETA THUNBERG SUGGESTS                                                                                                                                                                                                                             , Energy Minister Gwede Mantashe claimed that critics to Shell’s project wanted to deprive Africa of energy resources, but environmentalists worried that the project – which would involve blasting parts of the coast – would disturb sea life, which includes whales, dolphins and seals.  , "Could it be possible that this is an extreme pure love for the environment, or an unrelenting campaign to ensure Africa and South Africa do not see the investment inflows they need?"                                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                 , A Shell spokesperson told Reuters that the company will "respect the court’s decision and have paused the survey while we review the judgement."  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/medallion-financial-stock-plunges-toward/story.aspx?guid={62BDB328-160E-4027-A8B4-5A927FA46898}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-30 01:45:33 </td>
   <td style="text-align:left;"> Medallion Financial stock plunges toward 13-month low after SEC discloses fraud charges - MarketWatch </td>
   <td style="text-align:left;"> Shares of Medallion Financial Corp. 
        MFIN,
        -21.07%
       plummeted at much as 58.6% intraday Wednesday, before paring losses to be down 27.4% in midday trading, after the Securities and Exchange Commission charged the New York-based bank holding company and its Chief Operating Officer Andrew Murstein for engaging in "fraudulent schemes" to boost its stock price. The SEC's complaint alleges that from late 2014 through 2017, Medallion and Murstein engaged in "illegal touting" of its stock by paying media strategy company Ichabod's Cranium Inc. to place positive stories about the company on various websites, including Huffington Post, Seeking Alpha and TheStreet.com. Ichabod's Cranium and its owner Lawrence Meyers were also charged by the SEC. "With Murstein's knowledge, Meyers and others created fake identities so their opinion pieces would appear credible to potential investors," the SEC said in a statement. "The complaint further alleges that Medallion and Murstein fraudulently increased the carrying value of Medallion Bank (the Bank), a wholly owned subsidiary of Medallion, to offset losses relating to the taxicab medallion loans." Medallion's stock has still run up 25.2% this year, while the SPDR S&amp;P Reginal Banking ETF 
        KRE,
        +0.18%
       had rallied 37.1% and the S&amp;P 500 
        SPX,
        +0.14%
       had advanced 27.4%., Shares of FuelCell Energy Inc. undefined sank 5.1% toward 13-month low in premarket trading Wednesday, after the fuel cell technology company reported a wider-than-expected fiscal fourth-quarter loss as revenue surprisingly declined. The net loss for the quarter to Oct. 31 was $24.98 million, or 7 cents a share, after a loss of $19.66 million, or 8 cents a share, in the year-ago period. The number of shares outstanding increased to a weighted average of 366.67 million from 236.38 million. The FactSet consensus for per-share losses was 3 cents. Total revenue dropped 18.0% to $13.94 million, while the FactSet consensus called for 28% increase to $21.77 million. The decline in revenue was driven by a $5.6 million, or 102% decline, in service agreements and license revenue to negative $0.1 million, while the FactSet consensus was for a 22% increase to $6.6 million. The company said the backlog was largely unchanged. "Looking forward, we are focused on executing against our existing project backlog, while simultaneously increasing our annualized production rate, repositioning our brand for the future and building the next generation sales structure," said Chief Executive Jason Few. The stock has tumbled 47.5% this year, while the S&amp;P 500 undefined has climbed 27.4%.                                                                                                                , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/29/us/denver-shooting-spree-wednesday/index.html </td>
   <td style="text-align:left;"> 2021-12-30 01:39:27 </td>
   <td style="text-align:left;"> Denver shooting spree: Suspect wrote about a murderous rampage in a series of books under a pseudonym  - CNN </td>
   <td style="text-align:left;"> (CNN)The suspect in Monday's metro Denver shooting spree foreshadowed the rampage in a series of books he wrote under a pseudonym, and used the names of actual victims in his writings.                                                                                                                         , Five people were killed in the shooting and several were wounded -- including a female police officer. Investigators believe the gunman targeted some of his victims, but his motive remains unclear, Denver Police Chief Paul Pazen said.                                                                        , The gunman -- identified as Lyndon James McLeod, 47 -- was killed after a gunfight with a police officer.                                                                                                                                                                                                         , McLeod wrote under the pseudonym Roman McClay, according to a CNN review of his writings. The writings were first reported by The Denver Post.                                                                                                                                                                    , McLeod writes in chilling detail in one of his books about a character named "Lyndon Macleod" who dressed in police gear and kills another character by the name of "Michael Swinyard" at a building located at 1300 Williams St.                                                                                 , One of the victims in Monday's shooting was named Michael Swinyard, according to the Denver County Medical Examiner's office. Police say he was killed at that same address.                                                                                                                                      , In another book, McLeod writes about a character killing a woman named Alicia Cardenas. The Denver County Medical Examiner's office said a woman by the name of Alicia Cardenas was killed.                                                                                                                       , Cardenas, 44, was the owner of Sol Tribe Tattoo &amp; Body Piercing, according to her father, who spoke to CNN Denver affiliate KMGH.                                                                                                                                                                                 , The rampage is among more than 675 shootings that left four or more people dead or injured in the United States this year, according to Gun Violence Archive.                                                                                                                                                     , 3 of the shooting victims were killed at tattoo parlors, family and police say                                                                                                                                                                                                                                    , Authorities, friends and relatives identified three more victims Wednesday.                                                                                                                                                                                                                                       , Alfredo Cardenas, the father of Alicia Cardenas, told KMGH his daughter was gregarious, friendly and a "real leader in the community."                                                                                                                                                                            , Two other Sol Tribe employees were shot in the Monday night rampage, the father told the affiliate.                                                                                                                                                                                                               , A Sol Tribe assistant manager, Alyssa Gunn Maldonado, was killed, and her husband, James Maldonado, has been hospitalized after being injured in the shootings, a friend and a former colleague told CNN. James Maldonado was a piercer at the tattoo studio.                                                     , Swinyard, 67, was killed in Denver, according the city/county medical examiner. Police Cmdr. Matt Clark previously mentioned a victim who was killed at his home near the Cheesman Park area east of downtown Denver, and the address listed in the medical examiner's news release is a block north of the park. , Police also identified two other victims in the suburb of Lakewood: Danny Scofield, 38, who was fatally shot at Lucky 13 Tattoo, and Sarah Steck, 28, who was killed while working at the Hyatt House hotel.                                                                                                      , Motive behind the shooting still unclear                                                                                                                                                                                                                                                                          , Denver police investigated McLeod in 2020 and early 2021 but charges were never filed, Chief Pazen said Tuesday.                                                                                                                                                                                                  , "This individual was on the radar of law enforcement," he said without elaborating.                                                                                                                                                                                                                               , It appears McLeod had some connection to the local tattoo community, via his previous affiliation with a now-shuttered studio, though it's also unclear whether the shootings are related to McLeod's previous business relationships.                                                                            , A Denver tattoo parlor listing McLeod as its "registered agent," according to the Colorado Secretary of State's Office, was incorporated in 2005 and became "delinquent for failure to file Periodic Report" in 2017. CNN has reached out to the Denver Police Department for comment.                            , The site of the former business -- just south of the Denver Health Medical Center, where one of Monday night's shootings took place -- is now occupied by a tattoo parlor with a different name. Another incident was reported at that intersection, Pazen said.                                                  , "We believe a gun was fired. However, we do not have any injuries at that particular location," the chief said.                                                                                                                                                                                                   , Shooting spree included a car chase and gunfight                                                                                                                                                                                                                                                                  , McLeod allegedly opened fire at multiple locations around Denver before traveling to Lakewood, about 8 miles west of downtown Denver, Pazen said.                                                                                                                                                                 , The shootings began just after 5 p.m. when the gunman killed two women and wounded a man in Denver's busy South Broadway neighborhood, the chief said. Sol Tribe is located on Broadway.                                                                                                                          , The wounded man was taken to a hospital and was in critical condition Tuesday but is expected to survive, said Clark, the Denver police commander.                                                                                                                                                                , Authorities then received a call about a burglary where, Clark said, the suspect broke into a building and fired shots. People there escaped uninjured. Several blocks away, the gunman killed the man in his home near Cheesman Park, Clark said.                                                                ,                                                                                                                                                                                                                                                                                                                   , Denver police identified a black Ford linked to the incident and gave chase, leading to a gunfight, the chief said.                                                                                                                                                                                               , "We believe the individual, after disabling the police car, fled into Lakewood," he said.                                                                                                                                                                                                                         , Authorities received a report of shots fired at Lucky 13 Tattoo just before 6 p.m., Lakewood police spokesman John Romero said. Scofield was pronounced dead at the scene.                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                   , The gunman made his way to the Hyatt House Hotel in a shopping center a few miles away, where he allegedly shot Steck, who died later, police said Tuesday.                                                                                                                                                       , Lakewood Police Agent Ashley Ferris eventually confronted McLeod in a shopping area near the hotel and "ordered him to drop his weapon as he approached her," a news release from the Lakewood Police Department said.                                                                                            , The gunman ignored Ferris' commands and shot her, striking her abdomen, the release said. "Agent Ferris, shot and wounded on the ground, was able to return fire on the suspect. The suspect was shot by Agent Ferris and died on scene."                                                                         , Ferris remains in the hospital, according to the Wednesday news release.                                                                                                                                                                                                                                          , "The entire Lakewood Police family will be here to support Agent Ferris and her family as she embarks on this recovery process," said Lakewood Police Chief Dan McCasky.                                                                                                                                          , CNN's Ashley Killough, Omar Jimenez, Eric Levenson, Caroll Alvarado and Shawn Nottingham contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/29/stocks-making-the-biggest-moves-midday-victorias-secret-tesla-didi-and-more.html </td>
   <td style="text-align:left;"> 2021-12-30 01:14:49 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Victoria's Secret, Tesla, Didi and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                            , Check out the companies making headlines in midday trading Wednesday.                                                                                                                                                                                                                                                                      , Victoria's Secret — Shares of Victoria's Secret jumped 12.2% after the intimate apparel retailer announced a $250 million accelerated share repurchase program. The company also reaffirmed fourth-quarter guidance provided in November, including an up to 3% increase in sales versus last year's fourth-quarter sales of $2.10 billion., Didi Global — Shares of the Chinese ride-hailing firm fell 8.2%, continuing a brutal month for the stock. Reuters reported Wednesday that Didi is planning to list its stock in Hong Kong in mid-2022 without issuing more shares or raising additional capital.                                                                           , Tesla — Tesla shares dipped 0.2% after financial filings published late Tuesday showed CEO Elon Musk sold another 934,090 shares — or about $1.02 billion worth of his holdings — in the electric car company.                                                                                                                             , Alibaba — Alibaba shares fell 2.4% after Bloomberg reported the Chinese e-commerce giant is considering the sale of its 30% stake in social media company Weibo to state-owned Shanghai Media Group. Weibo shares retreated 4.3%.                                                                                                          , American Airlines — Travel-related stocks struggled after rebounding in the previous session, as the omicron Covid variant continued to influence market action. American Airlines slid 2.6%. United Airlines and Alaska Air each pulled back more than 1%.                                                                                , Cal-Maine Foods — Shares of Cal-Maine Foods fell 5.4% after the egg producer reported weaker-than-expected quarterly results. The company earned 2 cents per share for its latest quarter, well short of the 30-cent Refinitiv consensus estimate. Higher production costs and feed costs bit into profit, Cal-Maine Foods reported.       , — CNBC's Tanaya Macheel and Jesse Pound contributed reporting                                                                                                                                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                           , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 01:14:07 </td>
   <td style="text-align:left;"> Italian Shares Edge Lower </td>
   <td style="text-align:left;"> The FTSE MIB erased early gains to close 0.4% lower at 27,344.25 on Wednesday, as stronger pandemic related restriction measures dented investors’ sentiment on economic growth. Italy’s daily case count hit a fresh record of 78.3 thousand yesterday, as quarantine periods from close contacts with infections were reduced to five days for vaccinated individuals, but extended to ten days for the unvaccinated. Health experts criticized the long quarantine times, stating the country could risk paralysis when the highly infectious Omicron strain should be dominant by January. At the moment, over 2.5 million people are estimated to be in isolation from close contact with positive cases. On the corporate front, energy stocks took the most losses, driven by Eni (-1%) and Saipem (-0.6%). Still, the FTSE MIB is on course to close 2021 hovering around 13-year highs at a 25% yearly increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rice </td>
   <td style="text-align:left;"> 2021-12-30 01:11:00 </td>
   <td style="text-align:left;"> Rice Hits 17-Month High </td>
   <td style="text-align:left;"> Chicago rough rice futures extended gains to a 17-month high of $14.7 per hundredweight in the last week of December, underpinned by an ongoing fertilizer crisis, due to a spike in the cost of raw materials used to manufacture crop nutrients in many northern states of India. Also, a rise in transportation cost triggered by the recent fuel price hike is putting additional pressure on prices. Rice increased nearly 21% in 2021 amid a rise in demand as the global economy recovery continues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 01:02:00 </td>
   <td style="text-align:left;"> French Stocks Decline After Hitting Fresh Record </td>
   <td style="text-align:left;"> The CAC 40 Index erased early gains and closed 0.3% down at 7,161.52 on Wednesday, after hitting an intra-day record of 7,201.65 in the session, as surging coronavirus cases amid the spread of the Omicron variant dented traders’ sentiment. France registered over 200 thousand covid cases in the last 24 hours, a new European record. While the government signaled no lockdowns, Health Minister Olivier Veran told lawmakers that hospitals already feel overburdened. On the corporate front, travel and lodging stocks were hit the hardest, driven by Airbus (-1.3%) and Unibail-Rodamco-Westfield (-1.5%). Still, French equities are on course to finish 2021 on a strong note, pointing to 29% increase on the year, the steepest yearly increase for the CAC 40 since 1999. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/29/politics/biden-putin-call/index.html </td>
   <td style="text-align:left;"> 2021-12-30 00:54:37 </td>
   <td style="text-align:left;"> Biden to speak with Putin on Thursday at Russian leader's request - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)President Joe Biden will hold a call with Russian President Vladimir Putin on Thursday afternoon "to discuss a range of topics, including upcoming diplomatic engagements with Russia," National Security Council spokesperson Emily Horne told CNN.                                                                                                                                                                                                                                                                                                                                                                                                                                  , The call was requested by Putin, according to an administration official, and Biden accepted because "he believes when it comes to Russia there is no substitute for direct leader-leader dialogue."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Horne added that "the Biden Administration continues to engage in extensive diplomacy with our European Allies and partners, consulting and coordinating on a common approach in response to Russia's military build-up on the border with Ukraine. President Biden has spoken with leaders across Europe, and Biden Administration officials have engaged multilaterally with (the North Atlantic Treaty Organization), the (European Union), and the (Organization for Security and Cooperation in Europe). They have also held numerous consultations with counterparts, including those from eastern flank countries bilaterally and in the (Bucharest Nine) format as well as Ukraine.", The Bucharest Nine is a reference to nine European nations that form the eastern edge of NATO -- Poland, Romania, the Czech Republic, Estonia, Hungary, Bulgaria, Latvia, Lithuania and Slovakia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Biden plans to preview the upcoming bilateral talks between the US and Russia set to take place on January 10, the official said, and will also discuss the NATO-Russia and Organization for Security and Cooperation in Europe meetings slated for January 12 and 13. Close consultation with US allies and partners has been "a priority for the administration from the get-go," the official said, and Biden will underscore that to Putin as well.                                                                                                                                                                                                                                     , A senior administration official told reporters on Wednesday that while the US and its allies are committed to meaningful diplomacy with Russia, "we are also prepared to respond" with harsh, coordinated sanctions if Russia advances with a further invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                 , The US has also "made plans to reinforce NATO's force posture" in eastern Europe if Russia attacks Ukraine, the official said, and is prepared to provide Ukraine "with further assistance" to help the country defend itself if necessary.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The official noted that the US has not yet seen any effort by Russia to lower tensions.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , "We continue to see a significant Russian troop presence in and around the border of Ukraine, and we have continued to make clear to the Russian side that for there to be real progress in these talks, a context of de-escalation will be required."                                                                                                                                                                                                                                                                                                                                                                                                                                      , The US has also developed, "in some detail," a list of concerns it intends to share with Russia "at the appropriate point," the official said. "We are at a moment of crisis and have been for some weeks now, and it will take a high level of engagement to address this and try to find a path of de- escalation."                                                                                                                                                                                                                                                                                                                                                                       , Biden and Putin are not expected to participate in the talks on January 10 in Geneva, the official said. The talks will include representatives from the Pentagon and NSC and will be led by the State Department.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Secretary of State Antony Blinken spoke with Ukrainian President Volodymyr Zelensky on Wednesday about the ongoing tensions and previewed Biden's upcoming call with Putin, according to the State Department.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The Biden-Putin call, scheduled for 3:30 pm ET, will be the second direct contact between the two leaders this month as the US continues to pressure Russia to draw down its large military presence near Ukraine's borders. More than 100,000 Russian troops are still stationed there, and US intelligence officials have warned Ukraine and allies that Russia could be planning to launch an attack as soon as January.                                                                                                                                                                                                                                                                 , Biden warned Putin during a virtual meeting earlier this month that an invasion would result in serious consequences, such as harsh economic penalties and US military reinforcements on NATO's eastern flank.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Putin, in turn, has warned the US and NATO that Russia will be forced to act if its "red lines" are crossed, specifically if NATO expands its military capabilities further eastward and into Ukraine. Putin has demanded legally binding security guarantees from the US and NATO, some of which US officials have already called nonstarters but without detailing what exactly is off the table.                                                                                                                                                                                                                                                                                         , But US and Russian officials have agreed to sit down for security talks on January 10, where "Russia can put its concerns on the table, and we will put our concerns on the table with Russia's activities as well," an NSC spokesman said on Tuesday. The State Department will lead that delegation, the administration official said on Wednesday.                                                                                                                                                                                                                                                                                                                                       , The status of the talks is not contingent upon Russia first drawing down its forces, a White House official said on Tuesday, because the Biden administration still believes diplomacy is the most responsible path forward "even if we don't get everything we want."                                                                                                                                                                                                                                                                                                                                                                                                                      , US officials plan to consult with Ukraine regularly on the side as the negotiations with Russia take place next month, the White House official told CNN.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 00:54:26 </td>
   <td style="text-align:left;"> London Stocks at Fresh 22-Month High </td>
   <td style="text-align:left;"> The FTSE 100 rose 0.7% to close at 7,421 on Wednesday, hitting a fresh 22-month high, and outperforming its European peers, as trading activity returned to the London Stock Exchange after being closed for holidays since Friday afternoon. Traders were optimistic that the Omicron variant would not derail the economic recovery. On the pandemic front, UK’s health minister said the government would not impose new restrictions this week, as it waits to see if health services can manage high infection rates. On corporate news, Anglo-American commenced preliminary talks with Brazil’s Vale regarding a potential partnership for logistics and processing infrastructures in Brazil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 00:47:00 </td>
   <td style="text-align:left;"> European Stock Rally Pauses </td>
   <td style="text-align:left;"> European bourses closed mostly in the red on Wednesday, with trading volumes remaining thin towards the end of the year, as the Christmas rally showed signs of faltering after five consecutive sessions. Frankfurt's DAX 30 ended 0.7% lower at 15,852 and Paris' CAC 40 finished slightly below a recent record high, as investors remain cautious due to uncertainty surrounding the economic outlook amid a spike in coronavirus cases. Meanwhile, London's FTSE 100 climbed to a fresh 22-month high helped by slim prospects of lockdowns till the year-end. On corporate news, Daimler appointed a new chief executive to lead its battery projects, while France’s Teleperformance announced the acquisition of US process outsourcing firm Senture for $400 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2021-12-30 00:45:14 </td>
   <td style="text-align:left;"> The FTSE 100 Index increased 0.66% </td>
   <td style="text-align:left;"> United Kingdom Stock Market went up by 49 points. The rise was driven by Spirax-Sarco Engineering (3.50%), Royal Mail (2.84%) and Centrica (2.75%). Biggest losses came from TUI (-5.74%), Carnival (-4.13%) and Fresnillo (-2.11%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/29/investors-fear-inflation-most-in-2022-and-see-lower-stock-market-returns-cnbc-survey-shows.html </td>
   <td style="text-align:left;"> 2021-12-30 00:32:00 </td>
   <td style="text-align:left;"> Investors fear inflation most in 2022 and see lower stock market returns, CNBC survey shows </td>
   <td style="text-align:left;"> , (Click here to subscribe to the new Delivering Alpha newsletter.)                                                                                                                                                                                                                                                                                                 , Wall Street investors believe inflation will remain a major roadblock for markets in 2022 and stocks will only see muted returns, according to a new CNBC Delivering Alpha investor survey.                                                                                                                                                                       , We polled about 400 chief investment officers, equity strategists, portfolio managers and CNBC contributors who manage money about where they stood on the markets for the rest of 2021 and next year. The survey was conducted this week.                                                                                                                        , More than half of the respondents said inflation is their biggest worry for 2022. Thirty percent said the Federal Reserve raising rates at the wrong time is their top concern, while 17% said the economic impact of a lingering pandemic is their No. 1 worry.                                                                                                  , For months, investors have watched a variety of inflation data points show their highest levels in decades. The consumer price index, which measures the cost of a wide-ranging basket of goods and services, surged 6.8% on a year-over-year basis in November, the fastest rate since June 1982.                                                                , The Fed signaled it will make aggressive policy moves in response to rising inflation, including accelerating the reduction of its monthly bond purchases. Fed officials also see as many as three rate hikes coming next year.                                                                                                                                   , "There are serious headwinds to worry about," Brad McMillan, chief investment officer at Commonwealth Financial Network, said in a note. "Inflation is at the highest level in decades. Supply chain problems seem to be insoluble. If these issues keep getting worse, they could derail the recovery."                                                          , The S&amp;P 500 has rallied over 27% this year to a record high as the market climbed a wall of worry from surging inflation to the ongoing pandemic to the rollback of monetary stimulus. For 2022, investors think gains will be much lower.                                                                                                                        , More than 50% of the survey respondents expect the S&amp;P 500 to go up less than 10% in 2022. Nearly 18% think the market will produce another double-digit year, while 10% see a flatline for stocks.                                                                                                                                                               , Among different asset classes, equities are still investors' top choice, according to the survey result.                                                                                                                                                                                                                                                          , "While inflation is a concern and source of volatility, it also makes stocks the most compelling choice among the major asset classes," Tony DeSpirito, chief investment officer of U.S. fundamental active equity at BlackRock, said in a note. "Individual companies will manage through differently, highlighting the importance of a stock-by-stock approach.", In terms of stock preferences, 35% of the respondents said they favor financials and 27% like cyclical names benefiting from the economic recovery. Technology stocks in general became less favorable among investors.                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                  , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/retail-sales-annual </td>
   <td style="text-align:left;"> 2021-12-30 00:24:00 </td>
   <td style="text-align:left;"> Russia Retail Sales Rise Less than Expected </td>
   <td style="text-align:left;"> Retail sales in Russia advanced by 3.1 percent year-on-year in November of 2021, easing from a 4.3 percent surge in the prior month and below market expectations of a 3.9 percent raise, Still, it was the 8th consecutive month of growth in retail activity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/inflation-cpi </td>
   <td style="text-align:left;"> 2021-12-30 00:19:00 </td>
   <td style="text-align:left;"> Russia Inflation Rate Nears 6-Year High </td>
   <td style="text-align:left;"> Russia's consumer price inflation came in at 8.39 percent year-on-year in December 2021, little-changed from the previous month's rate of 8.40 percent, which was the highest since January 2016, a preliminary estimate showed. Inflation has risen sharply this year and is now running at a level that is more than twice the central bank's target of 4 percent, on the back of a rapid economic recovery from the initial phase of the coronavirus, reports of labor shortages across many industries and the ongoing supply issues. Upward pressure came from food (10.62 percent vs 10.81 percent in November), non-food products (8.58 percent vs 8.32 percent), and services (4.98 percent vs 5.15 percent). Policymakers have warned about the threat of an inflationary spiral as consumers bring forward purchases as they fear future price rises, and said food prices should increase further in 2022 due to a weaker-than-expected agricultural season in Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/7-year-note-yield </td>
   <td style="text-align:left;"> 2021-12-30 00:17:54 </td>
   <td style="text-align:left;"> Japan 7Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> Japan 7 Year Government Bond Yeld increased to a 4-week high of -0.069% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/unemployment-rate </td>
   <td style="text-align:left;"> 2021-12-30 00:15:50 </td>
   <td style="text-align:left;"> Russia Jobless Rate Steady at 2-Year Low in November </td>
   <td style="text-align:left;"> Russia's unemployment rate remained unchanged at 4.3 percent in November 2021, in line with market forecasts, and remained at the lowest rate since August 2019. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cotton </td>
   <td style="text-align:left;"> 2021-12-30 00:08:00 </td>
   <td style="text-align:left;"> Cotton Hits 4-week High </td>
   <td style="text-align:left;"> Cotton increased to a 4-week high of 112.9 USd/Lbs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-29 23:58:57 </td>
   <td style="text-align:left;"> UK 10Y Bond Yield Hits 5-week High </td>
   <td style="text-align:left;"> UK 10 Year Government Bond Yeld increased to a 5-week high of 1.008% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-29 23:58:51 </td>
   <td style="text-align:left;"> US 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> US 10 Year Government Bond Yeld increased to a 4-week high of 1.5375% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2021-12-29 23:44:42 </td>
   <td style="text-align:left;"> Euro Hits 4-week High </td>
   <td style="text-align:left;"> EURUSD increased to a 4-week high of 1.1361 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/crude-oil-stocks-change </td>
   <td style="text-align:left;"> 2021-12-29 23:44:22 </td>
   <td style="text-align:left;"> US Crude Stocks Fall for 5th Week </td>
   <td style="text-align:left;"> US crude oil inventories fell by 3.576 million barrels in the week ending December 24th, a fifth consecutive period of declines and compared with market forecasts of a 3.143 million drop, data from the EIA Petroleum Status Report showed. Meanwhile, gasoline inventories were down by 1.458 million barrels, defying expectations of a 0.487 million increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2021-12-29 23:43:20 </td>
   <td style="text-align:left;"> Heating Oil Hits 5-week High </td>
   <td style="text-align:left;"> Heating Oil increased to a 5-week high of 2.3979 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2021-12-29 23:43:00 </td>
   <td style="text-align:left;"> Brent Rebounds to 5-Week High </td>
   <td style="text-align:left;"> Brent crude futures rebounded toward $80 per barrel on Wednesday, the highest in five weeks after EIA showed US crude inventories fell more than expected last week and fewer worries the new Covid-19 variant will reduce fuel demand. The EIA Petroleum Status Report showed US crude oil inventories fell by 3.576 million barrels last week, a 5th consecutive period of declines and compared with market forecasts of a 3.143 million drop. Also, investors grew confident there will be no need to impose more restrictions on movements amid more evidence Omicron is less severe than previous strains. Oil prices gained more than 50% this year due to the return of demand and supply cuts by major oil-producing countries. Markets now await the next OPEC+ meeting on January 4th, as the group is set to decide whether to go ahead with a planned 400,000 barrels per day production increase in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2021-12-29 23:43:00 </td>
   <td style="text-align:left;"> Oil Bounces Back to 5-Week High after EIA Data </td>
   <td style="text-align:left;"> WTI crude futures rose more than 1% to above $77 a barrel on Wednesday, the highest in near five weeks and extending gains for the sixth session, after EIA data showed US crude inventories fell more than expected last week and as investors welcome signs the omicron variant is less severe than initially expected. The EIA Petroleum Status Report showed US crude oil inventories fell by 3.576 million barrels last week, a 5th consecutive period of declines and compared with market forecasts of a 3.143 million drop. Also, investors grew confident there will be no need to impose more restrictions on movements amid more evidence Omicron is less severe than previous strains. Oil is on track to book a more than 50% gain for 2021, its strongest performance in more than a decade, amid rising demand and supply constraints. Traders now await the next OPEC+ meeting on January 4th, as the group is set to decide whether to go ahead with a planned 400,000 barrels per day production increase in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2021-12-29 23:41:21 </td>
   <td style="text-align:left;"> Australian Dollar Hits 5-week High </td>
   <td style="text-align:left;"> AUDUSD increased to a 5-week high of 0.7263 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2021-12-29 23:37:19 </td>
   <td style="text-align:left;"> Gasoline Hits 4-week High </td>
   <td style="text-align:left;"> Gasoline increased to a 4-week high of 2.2682 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/facebooks-stock-reverses-lower-after/story.aspx?guid={1FEBC383-4B76-40F2-9D63-4202A459A072}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-29 23:32:57 </td>
   <td style="text-align:left;"> Facebook's stock reverses lower, after report that it looked to divide lawmakers to forestall tougher rules on social media - MarketWatch </td>
   <td style="text-align:left;"> Shares of Facebook parent Meta Platforms Inc. 
        FB,
        -0.95%
       dropped 0.8% in morning trading Wednesday, reversing earlier intraday gains of as much as 1%, after the Wall Street Journal reported that the social-media and metaverse company looked to divide lawmakers along party lines to forestall any bipartisan attempt to install tougher rules on social-media platforms. Citing people described as familiar with the conversations, the report said Facebook's Washington team called Republican lawmakers to push the narrative that former Facebook employee and whistleblower Frances Haugen was trying to help Democrats, while at the same time calling Democrats to warn them that Republicans were focused on Facebook's decision to ban expressions of support for Kyle Rittenhouse, who was charged with killing two people during civil unrest in Wisconsin, and later acquitted. The report said Chief Executive Mark Zuckerberg told employees not to apologize. Meta's stock has gained 1.2% over the past three months and has rallied 25.8% this year, while the S&amp;P 500 
        SPX,
        +0.14%
       has advanced 9.8% in the past three months and has run up 27.4% in 2021., Analysts at Wedbush point to three catalysts, including China demand, that could drive Tesla stock higher in 2022.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2021-12-29 23:21:00 </td>
   <td style="text-align:left;"> Dollar on Track for 7% Yearly Gain </td>
   <td style="text-align:left;"> The dollar index hovered around 96 at the end of December, close to the lowest level in 4 weeks, but it is still set for a 7% gain in 2021, the biggest since 2015 amid prospects the Fed would tighten monetary policy faster than other central banks and as investors believe the US economic recovery remains resilient and more robust than others. The Federal Reserve announced at its December meeting it would end its pandemic-era bond purchases in March, paving the way for three interest rate hikes by the end of 2022, as policymakers voiced concerns over persistently high inflation against a backdrop of a steady recovery in the labor market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/pending-home-sales-mom </td>
   <td style="text-align:left;"> 2021-12-29 23:08:48 </td>
   <td style="text-align:left;"> US Pending Home Sales Unexpectedly Drop </td>
   <td style="text-align:left;"> Contracts to buy US previously owned homes fell 2.2% mom in November of 2021, compared to market forecasts of a 0.5% rise, and following a 7.5% surge in October, amid limited supply and high home prices. Each of the four major regions witnessed contract transactions decline. Year-on-year, pending home sales were down 2.7%. "There was less pending home sales action this time around, which I would ascribe to low housing supply, but also to buyers being hesitant about home prices. While I expect neither a price reduction, nor another year of record-pace price gains, the market will see more inventory in 2022 and that will help some consumers with affordability", said Lawrence Yun, NAR's chief economist. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/real-estate/pending-home-sales-november-2021 </td>
   <td style="text-align:left;"> 2021-12-29 23:03:06 </td>
   <td style="text-align:left;"> Pending home sales fall 2.2% in November as rising prices make buyers hesitant </td>
   <td style="text-align:left;"> Brown Harris Stevens CEO Bess Freedman discusses rising home prices and the luxury real estate market.                                                                                                                                                                                                                                                                                       , Pending home sales unexpectedly fell in the month of November as homebuyers were hesitant to buy due to higher prices.                                                                                                                                                                                                                                                                       , The National Association of Realtors' pending home sales index, which tracks the number of homes that are under contract to be sold, slipped 2.2% to 122.4 in November on a monthly basis. The latest reading came in short of the 0.5% increase expected by economists surveyed by Refinitiv and well below October's 7.5% increase. On a year-over-year basis, contract signings slid 2.7%., HOME PRICES JUMP 18.4% IN OCTOBER                                                                                                                                                                                                                                                                                                                                                            , An index of 100 is equal to the level of contract activity in 2001.                                                                                                                                                                                                                                                                                                                          , All regions in the U.S. posted declines in pending home sales. The Midwest saw the biggest drop, falling 6.3% last month. Signings in the West fell 2.2%, while sales in the South and Northeast declined 0.7% and 0.1%, respectively.                                                                                                                                                       , A "sale pending" sign stands alongside a housing lot in Madison County, Mississippi, Tuesday, March 16, 2021. (AP Photo/Rogelio V. Solis)                                                                                                                                                                                                                                                    , NAR chief economist Lawrence Yun attributed the drop to low housing supply and buyers being hesitant about home prices.                                                                                                                                                                                                                                                                      , On Tuesday, S&amp;P CoreLogic Case-Shiller reported that its 20-city composite index surged 18.4% year over year in October, marking the fifth-largest annual gain on record for U.S. home prices, but down from the previous month's growth of 19.1% on an annual basis.                                                                                                                        , Total housing inventory at the end of November amounted to 1.11 million units, down 9.8% from October and down 13.3% from a year ago. Unsold inventory sits at a 2.1-month supply at the current sales pace, a decline from both the prior month and from a year ago.                                                                                                                        , "While I expect neither a price reduction, nor another year of record-pace price gains, the market will see more inventory in 2022 and that will help some consumers with affordability," Yun said.                                                                                                                                                                                          , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                      , Yun said housing demand continues to be high, with homes placed on the market for sale going from listed status to under contract in approximately 18 days.                                                                                                                                                                                                                                  , "Buyer competition alone is unrelenting, but home seekers have also had to contend with the negative impacts of supply chain disruptions and labor shortages this year," he explained. "These aspects, along with the exorbitant prices and a lack of available homes, have created a much tougher buying season."                                                                           , Looking ahead, Yun warns that a countrywide surge of the omicron COVID-19 variant poses a risk to the housing market's performance by sidelining buyers and sellers and delaying home construction.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2021-12-29 22:54:04 </td>
   <td style="text-align:left;"> Indian Rupee Hits 4-week High </td>
   <td style="text-align:left;"> USDINR decreased to a 4-week low of 74.579 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rice </td>
   <td style="text-align:left;"> 2021-12-29 22:35:24 </td>
   <td style="text-align:left;"> Rice Hits 17-month High </td>
   <td style="text-align:left;"> Rice increased to a 17-month high of 14.705 USD/cwt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-29 22:32:43 </td>
   <td style="text-align:left;"> US Stocks Steady </td>
   <td style="text-align:left;"> US stocks were little changed on Wednesday after the Dow Jones booked its 5th straight session of gains and the S&amp;P hit an intraday record the day before. Traders continue to wonder what will be the impact of omicron coronavirus variant on the global economy while expecting the Fed to continue to tighten next year amid persistent high inflation and a robust economic recovery. On the corporate front, Tesla shares rose 0.5%, following news that Elon Musk has exercised the last of his stock options for next year while stocks of BioNTech (-3%) and Moderna (-1.8%) were in the red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2021-12-29 21:52:59 </td>
   <td style="text-align:left;"> British Pound Hits 5-week High </td>
   <td style="text-align:left;"> GBPUSD increased to a 5-week high of 1.3462 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/wholesale-inventories </td>
   <td style="text-align:left;"> 2021-12-29 21:34:22 </td>
   <td style="text-align:left;"> US Wholesale Inventories Continue to Rise </td>
   <td style="text-align:left;"> Wholesale inventories in the US increased 1.2% mom to $769.9 billion in November of 2021, following a 2.5% rise in October, preliminary estimates showed. Stocks of durable goods surged 2%  while non-durable goods edged up 0.1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/goods-trade-balance </td>
   <td style="text-align:left;"> 2021-12-29 21:33:00 </td>
   <td style="text-align:left;"> US Posts Largest Goods Trade Deficit on Record </td>
   <td style="text-align:left;"> The US goods trade deficit widened to an all-time high of USD 97.78 billion in November 2021 from a revised USD 83.2 billion in the previous month, the advance estimate showed. Imports rose 4.7 percent to USD 252.43 billion, reflecting the ongoing recovery in domestic demand due to rising wages and a fast-recovering economy. Purchases rose for industrial supplies (10.0 percent), consumer goods (4.5 percent), vehicles (4.5 percent), and foods, feeds, &amp; beverages (3.4 percent). Meanwhile, exports were down 2.1 percent to USD 154.66 billion on the back of lower sales of industrial supplies (-2.3 percent), capital goods (-3.0 percent), consumer goods (-2.1 percent), and vehicles (-2.3 percent). So far this year, the US posted a goods gap of USD 984.6 billion, and is on track to book its biggest annual shortfall on record. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2021-12-29 21:28:59 </td>
   <td style="text-align:left;"> Stocks in South Africa Hit All-time High </td>
   <td style="text-align:left;"> SAALL increased to an all-time high of 73062 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/aluminum </td>
   <td style="text-align:left;"> 2021-12-29 21:27:00 </td>
   <td style="text-align:left;"> Aluminum Books 40% Gain for the Year </td>
   <td style="text-align:left;"> Aluminum futures were above $2,800 per tonne in the end of December, slightly below 2008-highs of $3,200 hit in October, but booking a nearly 40% gain for the 2021 year, amid supply chain constraints and lower production. The Chinese industry which accounts for nearly 60% of global aluminum output, was under heavy pressure this year due to severe power shortages, natural disasters and production accidents. In 2021, Chinese smelters have cut a total capacity of 3.8 million mt/year while new capacity only reached 450,000 mt/year, according to Antaike. Also, non-ferrous production in Europe is again under pressure as electricity prices roared back to record levels. Heading into 2022, high power prices, limited supply and rising demand are likely to continue to pressure the aluminum market. At the same time, Chinese authorities asked the aluminum sector to slash emissions 5% by 2025, according to a five-year plan to cut greenhouse-gas emissions and lower energy consumption. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-29 21:26:06 </td>
   <td style="text-align:left;"> US Futures Flat </td>
   <td style="text-align:left;"> US futures cut early gains to trade around the flatline on Wednesday after the Dow Jones booked its 5th straight session of gains and the S&amp;P hit an intraday record the day before. Traders continue to wonder what will be the impact of omicron coronavirus variant on the global economy while expecting the Fed to continue to tighten next year amid persistent high inflation and a robust economic recovery. On the corporate front, Tesla shares rose 1.4% in premarket trading, following news that Elon Musk has exercised the last of his stock options for next year while stocks of BioNTech (-3%) and Moderna (-1.6%) were in the red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cyprus/wage-growth </td>
   <td style="text-align:left;"> 2021-12-29 20:49:54 </td>
   <td style="text-align:left;"> Cyprus Wages Rise 1.3% YoY in Q3 </td>
   <td style="text-align:left;"> Average gross monthly earnings of employees in Cyprus grew by 1.3 percent year-on-year to EUR 1,934 in the third quarter of 2021, following an upwardly revised expansion of 2.5 percent in the previous period. Wages for male employees advanced 1.4 percent on the year to EUR 2,074, while those for female employees increased 1.3 percent to EUR 1,764. Compared to the previous quarter, seasonally adjusted wages rose by 0.5 percent to EUR 2,024. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/29/stocks-making-the-biggest-moves-premarket-cal-maine-tesla-alibaba-and-others.html </td>
   <td style="text-align:left;"> 2021-12-29 20:43:28 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Cal-Maine, Tesla, Alibaba and others </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                          , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                                , Cal-Maine Foods (CALM) – The nation's largest egg producer earned 2 cents per share for its latest quarter, well short of the 30-cent consensus estimate. Sales were better-than-expected, but the bottom line was hit by higher costs for packaging and labor. Cal-Maine shares tumbled 7.1% in the premarket.                                          , Tesla (TSLA) – Tesla rose 1.4% in premarket trading, following news that CEO Elon Musk completed the exercising of all his stock options for next year. That signals the end of recent stock sales by Musk to cover tax bills generated by the exercise of those options.                                                                                , Alibaba (BABA) – The China-based e-commerce giant is considering the sale of its 30% stake in social media advertising company Weibo (WB) to state-owned Shanghai Media Group, according to a Bloomberg report. Alibaba fell 1% in premarket action, while Weibo edged lower by 0.3%.                                                                    , Victoria's Secret (VSCO) – The intimate apparel retailer announced a $250 million accelerated share repurchase program.                                                                                                                                                                                                                                  , Akamai Technologies (AKAM) – Akamai rose 1.2% in the premarket after D.A. Davidson rated the internet content delivery company a "buy" in new coverage. The firm set a price target of $143 per share, compared with Tuesday's close of $118.45.                                                                                                         , Didi Global (DIDI) – Didi was down 2.4% in premarket trading after Reuters reported the Chinese ride-hailing company will use the "listing by introduction" method to list in Hong Kong, as it moves to delist in New York. That method would issue no new shares and raise no capital.                                                                  , BioNTech (BNTX) – The drug maker's shares fell 3% in the premarket, potentially extending the stock's losing streak to 7 days. BioNTech has fallen 16% over the past 6 sessions. Rival vaccine maker Moderna (MRNA) is in a similar slump, falling for the past six sessions and falling 18% over that stretch. Moderna dropped 1.6% in premarket action., FuelCell Energy (FCEL) – The fuel cell technology company lost 7 cents per share for its latest quarter, wider than the 4-cent loss predicted by analysts. Revenue also fell below analyst forecasts, and the stock slumped 4.6% in premarket trading.                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                         , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rubber </td>
   <td style="text-align:left;"> 2021-12-29 20:43:00 </td>
   <td style="text-align:left;"> Rubber Heads for 18% Loss in 2021 </td>
   <td style="text-align:left;"> After touching an almost four-year high of 338 yen in January, the Japanese rubber futures traded around the 220 yen per kg level at the end of 2021, heading for an 18% yearly loss in 2021 on concerns about global demand and despite a weaker yen. Continuing standoff in the auto sector due to chip shortages and restrictions imposed especially across Europe and top buyer China against the rapid spread of the Omicron coronavirus variant heavily weighted on the metal's appeal. Still, increasing demand from China ahead of the Lunar New Year should provide some support at the start of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovenia/retail-sales-annual </td>
   <td style="text-align:left;"> 2021-12-29 20:35:04 </td>
   <td style="text-align:left;"> Slovenia Retail Trade Growth at Record High </td>
   <td style="text-align:left;"> Retail sales in Slovenia advanced 41 percent year-on-year in November of 2021 from a 34.3 percent increase in the previous month. It was the largest growth rate since the series began in 2001, boosted by accelerated sales of non-food products (45.8 percent vs 13.1 percent in October). Although at a slower pace, sales also grew for automotive fuel (79.4 percent vs 97.2 percent) and food, beverages, and tobacco (6 percent vs 7.6 percent). On a seasonally adjusted monthly basis, retail trade slowed 0.4 percent, compared to the 13 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/zew-economic-sentiment-index </td>
   <td style="text-align:left;"> 2021-12-29 20:14:00 </td>
   <td style="text-align:left;"> Swiss Investor Morale Improves in December </td>
   <td style="text-align:left;"> The Swiss investor sentiment index jumped 10.8 points to a neutral 0 in December of 2021 from -10.8 in November. "Swiss financial analysts have so far shrugged off the new variant of coronavirus in their forecasts and are bringing the year to a close with a neutral outlook" Credit Suisse said. The investment bank added that analysts see an ongoing recovery boom amid moderate inflation in the long-run. Meanwhile, the current conditions index fell 19.9 points to 34.2 in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coal </td>
   <td style="text-align:left;"> 2021-12-29 20:08:00 </td>
   <td style="text-align:left;"> Coal on Track for 110% Gain in 2021 </td>
   <td style="text-align:left;"> Newcastle coal futures were trading slightly above $170 per metric ton in the end of December, well below a record high of $269.50 hit in October, but booking a nearly 110% gain for the 2021 year on strong demand and limited supplies. Higher than normal natural gas prices have been boosting coal appeal in Europe with stockpiles in plants hitting their lowest level since 1970's. Also, demand from India and China remains strong. Earlier this year, China introduced power curbs especially for energy-intensive businesses and restrictions on coal imports, aiming to reach its climate targets but such curbs led to a serious power crunch. The Chinese government then lifted some restrictions to balance the coal market and slow record prices. As a result, global coal power generation is on course to increase by 9% to an all-time high of 10,350 terawatt-hours in 2021, according to the latest IEA report. For 2022, the IEA forecasts both coal production and demand to rise to the highest ever levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/croatia/stock-market </td>
   <td style="text-align:left;"> 2021-12-29 20:00:22 </td>
   <td style="text-align:left;"> Stocks in Croatia Hit Near 5-year High </td>
   <td style="text-align:left;"> CROBEX increased to a near 5-year high of 2063 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2021-12-29 19:47:03 </td>
   <td style="text-align:left;"> South Africa Shares Hit New Record High </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index extended gains towards an all-time high of 73,000 on Wednesday, amid thin trading volumes and optimism about the economic recovery backed by recent studies about the omicron variant. On the pandemic front, South Africa’s government put the implementation of the latest quarantine rules, which discarded self-isolation for asymptomatic infected individuals, on hold and said it would release an amended version. In contrast, a top advisory council is set to meet this week to discuss the possibility of reintroducing tighter restrictions in the country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/greece/loan-growth </td>
   <td style="text-align:left;"> 2021-12-29 19:33:59 </td>
   <td style="text-align:left;"> Greece Total Credit Growth at 1-Year Low </td>
   <td style="text-align:left;"> The annual growth rate of total credit extended to the Greek economy eased to 12.2 percent in November of 2021 from a downwardly revised 12.4 percent in the previous month. It was the lowest growth rate since October of 2020 as credit rose at softer pace for the government (46.3 percent vs 43.3 percent in October). On the other hand, credit edged up for the private sector (1.1 percent vs 0.9 percent). </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2021-12-30 14:15:38 UTC +8

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
   <td style="text-align:left;"> 2021-12-30 14:14:21 </td>
   <td style="text-align:left;"> $SPY Ruh roh here bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:13:18 </td>
   <td style="text-align:left;"> $SPY woke lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:13:12 </td>
   <td style="text-align:left;"> $SPY $TSLA $RIOT silver to diamond with top lane even tho i havent played in so long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:12:47 </td>
   <td style="text-align:left;"> $SPY index at all time highs while growth stocks get slaughtered to all time lows. Moral of the story ? We don’t anymore more success stories , join the program and crawl on your knees to financial freedom. Well Fuck the system , bulls coming back 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:10:47 </td>
   <td style="text-align:left;"> $NILE $IWM $SPY $AYRO Facts!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:10:43 </td>
   <td style="text-align:left;"> Post here $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:10:19 </td>
   <td style="text-align:left;"> Keep compounding $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:09:00 </td>
   <td style="text-align:left;"> $SPY anyone see anything wrong in this pic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:07:54 </td>
   <td style="text-align:left;"> $SPY don’t care what direction this moves tomorrow. Just move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:06:27 </td>
   <td style="text-align:left;"> $SPY HSI sliced through multiyear support let&amp;#39;s see what chaos it brings to market world wide. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:05:51 </td>
   <td style="text-align:left;"> $spy rainbow bearz have the options edge into tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:05:34 </td>
   <td style="text-align:left;"> $SPY All I want in life is a 263ft $100M Yacht. Is that so much to ask? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:05:05 </td>
   <td style="text-align:left;"> $SPY $SPX GREAT READ AND WHY I LOVE @BookmapPro

https://www.onlyticks.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:01:58 </td>
   <td style="text-align:left;"> $SPY new work culture 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:00:41 </td>
   <td style="text-align:left;"> $SPY … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 14:00:18 </td>
   <td style="text-align:left;"> $SPY HSI hanging by thread on multi year support again. It&amp;#39;s likely to slice through it today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:59:45 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F the anatomy of a trade in 2 pics </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:59:27 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:59:23 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F the anatomy of a trade in two images </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:59:00 </td>
   <td style="text-align:left;"> Keep going $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:58:51 </td>
   <td style="text-align:left;"> $SPY 

 Why is bear so poor all the time ??

🤔🤔📈🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:57:28 </td>
   <td style="text-align:left;"> $SPY what the Hell is that all about ?! 👽👀 $UFO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:56:55 </td>
   <td style="text-align:left;"> https://www.investing.com/indices/indices-futures  $f $tsla $ccl  $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:55:35 </td>
   <td style="text-align:left;"> $SPY juice wrld bought this stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:55:11 </td>
   <td style="text-align:left;"> $SPY hmm so Putin wants to talk to Biden. I’m sure this will be completely improvised and they haven’t already spoken and made some sore of agreement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:55:06 </td>
   <td style="text-align:left;"> Some other interesting option trades...

$QQQ $SPY $EEM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:54:54 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/1szayJV505M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:53:39 </td>
   <td style="text-align:left;"> $SPY I need a gf lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:51:23 </td>
   <td style="text-align:left;"> $SPY Ima need you to do that 480 thingy by Friday ☺️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:46:52 </td>
   <td style="text-align:left;"> $SPY Mac Miller got me in my feelings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:45:03 </td>
   <td style="text-align:left;"> $SPY If you think the bull market is done get ready 2022 is going to be even larger. Globally rates are still frozen at 0% so all of the new money has to go somewhere. It’s not hard to see SPY hitting $600 end of next year https://www.cnbc.com/2021/12/16/big-wealth-investors-are-likely-to-put-money-to-work-in-stocks-after-amassing-record-levels-of-cash.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:44:14 </td>
   <td style="text-align:left;"> $spy I&amp;#39;m more burnt out on government control than I am of COVID. I think we need to take our governments back, peacefully. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:43:40 </td>
   <td style="text-align:left;"> $DWAC $SPY $QQQ 
Total psy-op false flag Lefty scam..

https://m.youtube.com/watch?v=qwYIWno8EJo&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:42:46 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

Anyone heard from Crossing Trends? Or did he go broke? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:42:25 </td>
   <td style="text-align:left;"> $SPY 🙏🏾 let’s close this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:41:26 </td>
   <td style="text-align:left;"> $SPY futus are rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:40:45 </td>
   <td style="text-align:left;"> $SPY $SPOT https://www.youtube.com/watch?v=4LSdLh7dsR0 fire song </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:40:20 </td>
   <td style="text-align:left;"> $SPY pretty clear that the worlds investors still thinks America is the place to put their money for the next decade. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:40:10 </td>
   <td style="text-align:left;"> $SPY chinese futures died quickly... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:39:52 </td>
   <td style="text-align:left;"> $SPY $TSLA$juicewrld $QQQ $NFLX $DIS alexa play all girls are the same </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:39:19 </td>
   <td style="text-align:left;"> $SPY tomorrow is going to be flat so Brandon can say how good the economy is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:39:19 </td>
   <td style="text-align:left;"> $SPY  HSI ready for waterfall. Let see if it&amp;#39;s going to break multi year support today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:39:05 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:38:35 </td>
   <td style="text-align:left;"> $SPY latexc9091331a933e41ffe06b14954714c36SPY 
$WISH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:36:50 </td>
   <td style="text-align:left;"> $SPY I have calls and puts. Fk you SPY. Only theta can hurt me now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:36:11 </td>
   <td style="text-align:left;"> $SPY 20 SMA on 60m. Still key level according to me. Goodnight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:35:59 </td>
   <td style="text-align:left;"> $SPY be advised </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:35:41 </td>
   <td style="text-align:left;"> $SPY bounced hard af off liquidity level and retest of breakout on /nq 16400 and they&amp;#39;re still buying puts. I&amp;#39;m going to enjoy this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:35:26 </td>
   <td style="text-align:left;"> $spy looks like every night Fauci comes with a statement to arouse the bear to fuck them hard by the first hour of market open.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:35:22 </td>
   <td style="text-align:left;"> $SPY I Am  bull again I am bull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:33:52 </td>
   <td style="text-align:left;"> $SPY what’s your 2022 5-10 bagger Tickers???  lot of brilliant people here. What say you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:32:49 </td>
   <td style="text-align:left;"> $SPY it’s just... I mean c’mon.  If tumbles through every support then magically V rallies straight up right back above every resistance and bounces off the highest support? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:32:38 </td>
   <td style="text-align:left;"> $SPY haha we are going higher bear meat again tomorrow.. consolidation done … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:32:24 </td>
   <td style="text-align:left;"> $SPY loaded puts all day 474s 477s &amp;amp; 470s Jan 22 … will I become rich or blow up my account. Stay tuned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:32:11 </td>
   <td style="text-align:left;"> $SPY hey guys just spoke to Dave portnoy on my T Mobile Sidekick. He loaded up calls and he’s ready to paper hand them at the smallest 0.8% drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:31:43 </td>
   <td style="text-align:left;"> $BTC.X $SPY “guilt is an illusion “ Ted Bundy 🤣👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:31:42 </td>
   <td style="text-align:left;"> $SPY they bounced the nasdaq off 16400 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:31:37 </td>
   <td style="text-align:left;"> $WMT $SPY If the china problem isn&amp;#39;t resolved may plummet

$UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:31:08 </td>
   <td style="text-align:left;"> $SPY How easy would it be for ST to make an algo that scans for posts who say - “I went broke then I made a 300k in a week when I joined scamyou discord server” and blocks them. That fucking easy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:30:35 </td>
   <td style="text-align:left;"> $SPY anyone know of magic spell to cause broad rally beyond the chosen five </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:29:52 </td>
   <td style="text-align:left;"> $SPY  How many lolita express passengers going to board runaway express?
https://www.dailymail.co.uk/news/article-10332169/Underage-orgies-possible-pregnancy-key-moments-Ghislaine-Maxwells-sensational-trial.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:29:46 </td>
   <td style="text-align:left;"> $SPY so a beautiful phone call tomorrow?  Yeah the trash news recycling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:29:39 </td>
   <td style="text-align:left;"> $SPY starting to look like they intend to prop until Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:29:06 </td>
   <td style="text-align:left;"> $SPY what’s your 2022 5-10 bagger Tickers??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:29:00 </td>
   <td style="text-align:left;"> $SPY can’t imagine how screwed some of these meme stock traders are in April. Hit gold a couple times and took the short term gain, then lost it on other trades that went bad. Why do you think wall st is crushing growth stocks? They want retail out of the market. They’re taking everything back. Hopefully traders are ready to cut one of the biggest checks they’ll ever have to write. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:28:17 </td>
   <td style="text-align:left;"> $SPY the prop is annoying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:27:48 </td>
   <td style="text-align:left;"> $SPY lmfaoooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:27:47 </td>
   <td style="text-align:left;"> $spy Hong Kong with the crash candle now =🌈 rainbow bear for the win again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:27:14 </td>
   <td style="text-align:left;"> $SPY And as mysteriously as he appeared, the duck had vanished </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:27:04 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA  I have a 2k/day quota that I have to meet day trading with the occasional 10k/day when the market is volatile enough. My daily driver is a Tesla, occasional driver Lamborghini, just moved into a massive new place in NY and I&amp;#39;m single. 
If I can do it, YOU can do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:25:32 </td>
   <td style="text-align:left;"> $SPY I don’t really hate anybody I’m just saying that cause I love u all ❤️👍 tough love 😜 micky d hiring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:24:37 </td>
   <td style="text-align:left;"> $SPY How the bears see the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:24:16 </td>
   <td style="text-align:left;"> $SPY you guys seeing these videos coming out of China? Supply chain issues may make an aggressive comeback. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:22:16 </td>
   <td style="text-align:left;"> $SPY We are gonna open at 476 right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:20:56 </td>
   <td style="text-align:left;"> $SPY so what? Is it crashing or going to The Moon tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:20:13 </td>
   <td style="text-align:left;"> $SPY $TKAT $CRO.X $ASTR this still working??
https://youtu.be/_W_BWkNl1pU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:19:12 </td>
   <td style="text-align:left;"> $SPY so sleepy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:19:01 </td>
   <td style="text-align:left;"> $SPY Golds irrelevant. I’m going all in on sand. Apparently we’re using it all up at a rapid rate. I’ll pass it onto my children and they’ll pass it onto their children. 1 tonne will be worth 27.5 BTC (today’s value $27,479,002,974,019,736,010 accounting for inflation) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:18:55 </td>
   <td style="text-align:left;"> $SPY Word of wise advice: Don&amp;#39;t be a Cathy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:17:53 </td>
   <td style="text-align:left;"> $SPY $SPX South Korea’s factory production jumped the most since mid-2020 last month, suggesting supply disruptions that hurt manufacturing in key industries are easing
https://www.bloomberg.com/news/articles/2021-12-30/korea-production-jumps-most-in-17-months-as-supply-woes-ease?utm_source=twitter&amp;amp;utm_campaign=socialflow-organic&amp;amp;utm_content=markets&amp;amp;cmpid%3D=socialflow-twitter-markets&amp;amp;utm_medium=social </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:16:34 </td>
   <td style="text-align:left;"> $SPY James Harden just might be the king of natural immunity. 💃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:16:08 </td>
   <td style="text-align:left;"> $SPY what’s up guys I’m gonna blow my account up on puts and then in 2022 I’m gonna turn the 5 dollars I have left into 5 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:15:47 </td>
   <td style="text-align:left;"> $SPY if futures are flat it means it either gonna go up or down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:15:24 </td>
   <td style="text-align:left;"> Day 118- $21400

$100 - $250k journey 

Have now turned 100 bucks into 21k 
Slow and steady has been key with heavy sizing. 

Today - $NAKD  $2600

$AMC $WISH $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:14:58 </td>
   <td style="text-align:left;"> ETF Sentiment: $SPY is the #1 ETF that institutions are trading with 306.5K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:14:58 </td>
   <td style="text-align:left;"> $SPY 🤣🤣 https://babylonbee.com/news/fda-assures-vaccine-is-almost-as-safe-for-kids-as-covid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:14:45 </td>
   <td style="text-align:left;"> $SNES The government better start investing in sustainable rodent control infrastructure before we get more spread between rodents and people. Vaccines are obviously not going to make this go away. We better start getting real and Learn to manage this. Especially keeping our farms and livestock safe by keeping rodent populations at bay by using Contrapest made by Senestech. $SPY $IWM $IWC 

https://www.nbcnewyork.com/news/coronavirus/omicron-variant-might-come-from-transmission-between-humans-and-mice-study-says/3451661/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:13:32 </td>
   <td style="text-align:left;"> $SPY $SPX yes crashing tomorrow 🌈🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:12:54 </td>
   <td style="text-align:left;"> $SPY these are some weird futures something up. Either face ripper rally tomorrow or big ass sell off. Leaning
Towards the latter so I can position
Myself into calls lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:12:17 </td>
   <td style="text-align:left;"> $SPY $SPX buy puts bears 
and pay me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:11:54 </td>
   <td style="text-align:left;"> $SPY oh these controlled red futes have been fun this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:11:52 </td>
   <td style="text-align:left;"> $SPY $SPX DIX GEX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:11:32 </td>
   <td style="text-align:left;"> $SPY JPM has a 5000 price target for s&amp;amp;p500 end of 2022

Standard ~10% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:11:05 </td>
   <td style="text-align:left;"> $SPY pretty interesting that this is an exactly perfect wave where the pullbacks are just… bullflags. 12345, we may very well see a small abc move up here before moving to and over $480. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:10:41 </td>
   <td style="text-align:left;"> $SPY $SPX YES BEARS WE CRASHING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:10:31 </td>
   <td style="text-align:left;"> $SPY flat activity. GEX and DIX at neutral levels. However SPY a bit toppy could experience a small pullback. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:10:19 </td>
   <td style="text-align:left;"> $VXX slip sliding into the depths of Hell while $SPY RSI resets thru time .... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:09:07 </td>
   <td style="text-align:left;"> $SPY going to buy contracts that allow me to buy this for more than it has ever cost tomorrow with a premium. Seems smart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:07:15 </td>
   <td style="text-align:left;"> $SPY futes bloody red.  not good for you bulls.  the bears have won this Santa Claus rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:07:09 </td>
   <td style="text-align:left;"> $SPY SPY 2021-12-29 Options Analysis Video: 
https://www.youtube.com/watch?v=ws1oYd0LMC8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:06:40 </td>
   <td style="text-align:left;"> $SPY squeeze or die </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:05:49 </td>
   <td style="text-align:left;"> $SPY start trimming profits once we get 480-485... we might see some volatility soon, and a corrective wave around there before we rally to 500 by mid/late January </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:05:47 </td>
   <td style="text-align:left;"> $SPY ? https://www.reddit.com/r/MillennialBets/comments/rro07z/ktta_the_shorts_are_actually_trapped_here/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:05:15 </td>
   <td style="text-align:left;"> $SPY I just watched a doc about Ghislane and her brother must be the biggest pos in the world. Omg this guy his accent and wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:03:27 </td>
   <td style="text-align:left;"> $SPY Just finished the Matrix…I am woke… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:03:27 </td>
   <td style="text-align:left;"> $SPY she wanna fuck me, she don’t love me
Lifestyle, lifestyle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:02:51 </td>
   <td style="text-align:left;"> $ES_F Opening 4650, Type: SHORT $SPY 20 point tolerance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:02:01 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:01:41 </td>
   <td style="text-align:left;"> $SPY im running for congress. Will easily turn 1 dollar into a million in 10 trading days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 13:00:51 </td>
   <td style="text-align:left;"> $SPY why did this drop 16% ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:59:52 </td>
   <td style="text-align:left;"> $SPY bears do u see a bull flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:59:11 </td>
   <td style="text-align:left;"> $SPY  Some professionals in this market are pitiful beings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:58:21 </td>
   <td style="text-align:left;"> $SPY  Cathie used Macro economic data as an excuse to sell off even more of her losing “investments” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:58:15 </td>
   <td style="text-align:left;"> $SPY New year, new trades and better improved strategies are on the way for me. Bullish for 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:57:34 </td>
   <td style="text-align:left;"> $TSLA , $SPY $49,000 a day keeps the 9 to 5 away; Stay patient and the let the trade play out.. stockplays.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:57:05 </td>
   <td style="text-align:left;"> $SPY yikes . X

https://dailysceptic.org/2021/12/22/triple-vaccinated-more-than-four-times-more-likely-to-test-positive-for-omicron-than-unvaccinated-data-shows/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:57:04 </td>
   <td style="text-align:left;"> $SPY this is just top of the golden bear porn by Cathy https://mobile.twitter.com/cathiedwood/status/1476377783580471297 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:55:58 </td>
   <td style="text-align:left;"> $SPY  Ever ride one of these ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:55:54 </td>
   <td style="text-align:left;"> $SPY new strategy for 2022

Short more uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:55:50 </td>
   <td style="text-align:left;"> $SPY for the bulls, i would start trimming calls at around 484 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:55:32 </td>
   <td style="text-align:left;"> $SPY the 460 days are gone like my puts 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:55:27 </td>
   <td style="text-align:left;"> $SPY THE RUG SALESMAN is coming for your MONEY 💰 let the PULL BEGIN ❗️❗️❗️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:55:19 </td>
   <td style="text-align:left;"> $SPY whats the word? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:55:10 </td>
   <td style="text-align:left;"> $SPY why do you 

Take a Ho

To a hotel?

Because a Ho tell er body. Even the Mayor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:55:01 </td>
   <td style="text-align:left;"> $SPY How are the Bears struggling to even have this retrace to the 4 EMA? 😂 At least create another dip to buy lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:54:38 </td>
   <td style="text-align:left;"> $SPY i get a follower here and there from time to time, and while not all, i get weird looks when i ask to be unfollowed.

Listen, i am no one. I am not deserving of your follow. If you really want to follow someone, follow Jesus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:53:31 </td>
   <td style="text-align:left;"> $SPY bears fuk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:53:23 </td>
   <td style="text-align:left;"> $SPY 
 
Danish study released on Pfizer and MODERNA yikes 

https://mobile.twitter.com/ezralevant/status/1474106318206255113?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1474106318206255113%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.naturalnews.com%2F2021-12-29-covid-vaccines-damage-your-immune-system.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:53:05 </td>
   <td style="text-align:left;"> $SPY we need a breather to 474 then back up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:52:54 </td>
   <td style="text-align:left;"> $SPY  Ok guys Duck said watch out for a $30 green pp candle 🕯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:52:40 </td>
   <td style="text-align:left;"> $SPY $QQQ corrupt govt..corrupt market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:52:25 </td>
   <td style="text-align:left;"> $SPY $AAPL im
Ready 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:52:13 </td>
   <td style="text-align:left;"> $SPY oh man lol those are incredibly bearish candles the last 2 days… here comes the drop you delusional bulls are in for a rude awakening now-Friday. 😂😂😂😂 enjoy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:52:11 </td>
   <td style="text-align:left;"> $SPY 

Cathy sold everything yesterday  bought nothing

curious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:52:06 </td>
   <td style="text-align:left;"> $SPY God Bless the bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:51:41 </td>
   <td style="text-align:left;"> $SPY wild year for cathie and ark. i&amp;#39;ll never forget that sht. at least shes transparent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:51:23 </td>
   <td style="text-align:left;"> $ARDX $NVDA $TSLA $SPY For a limited time,from Xtrades  we are opening our trading chatroom to the public. Get access to chatrooms, stock alerts, option alerts,, portfolios, and more...  https://www.discord.io/xEvE2Aatrp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:51:07 </td>
   <td style="text-align:left;"> $SPY send it duck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:50:57 </td>
   <td style="text-align:left;"> $SPY  historically the last trading day of the year we rally!! Get ur helmets on bulls 🚀!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:50:39 </td>
   <td style="text-align:left;"> $SPY futes flat af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:50:37 </td>
   <td style="text-align:left;"> $SPY coin flip test sell at all time highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:49:45 </td>
   <td style="text-align:left;"> $SPY ducks back. 500 eoy confirmed ?🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:49:25 </td>
   <td style="text-align:left;"> $SPY Update on our Biden winter of Death. Took in another movie at Cinemark then hit Costco. Wife wanted to go to Hobby Lobby.....nope. dropped me off and rode my new Nordic Track s22i through Costa Rica. It&amp;#39;s badass. Had some cocktails. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:49:11 </td>
   <td style="text-align:left;"> $SPY 480 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:48:38 </td>
   <td style="text-align:left;"> $SPY all in on angry pitbull club </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:48:25 </td>
   <td style="text-align:left;"> $SPY 🥰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:48:14 </td>
   <td style="text-align:left;"> $SPY road to 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:48:10 </td>
   <td style="text-align:left;"> $SPY  I’m on my duck isshh tonight @HOODuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:47:25 </td>
   <td style="text-align:left;"> $SPY The duck is back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:46:36 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ i just apply for cash account and option from help from holly , y’all get ready 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:46:28 </td>
   <td style="text-align:left;"> $SPY Covid is the new Logan’s Run. Change my mind. 😬🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:46:10 </td>
   <td style="text-align:left;"> $SPY I love when people try and compare todays market or economy to ones 40 years ago. We have daddy. Way different    Brrrrrrrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:43:35 </td>
   <td style="text-align:left;"> $SPY  They all want our Capital Markets. Forever. Data from Oct 28 2021 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:43:01 </td>
   <td style="text-align:left;"> $SPY wow, sleepy Joe’s first year stock market is off to a betters start than Trump’s.  29 vs 21%.  Trump must be fuming.  Who knew. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:42:00 </td>
   <td style="text-align:left;"> $SPY has an average volume of 72698700. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:41:56 </td>
   <td style="text-align:left;"> $SPY  Same shit different century </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:41:44 </td>
   <td style="text-align:left;"> $SPY so true 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:39:58 </td>
   <td style="text-align:left;"> $SPY 

Looks familiar? Just plot it over the DOW and S&amp;amp;P 500 since 2018. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:39:49 </td>
   <td style="text-align:left;"> $SPY It is all about the 2 second chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:38:51 </td>
   <td style="text-align:left;"> $SPY futes ripping - good night everybody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:38:49 </td>
   <td style="text-align:left;"> $SPY 2 points up tomorrow and  3 points dump Friday to 477. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:38:29 </td>
   <td style="text-align:left;"> $SPY lines of covid here are like a mile long?
WTF is going on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:37:31 </td>
   <td style="text-align:left;"> $SPY holy shite cathy woods taking a play from the SOC playbook 

https://twitter.com/cathiedwood/status/1476377783580471297?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:37:19 </td>
   <td style="text-align:left;"> $SPY Tomorrow seems like a green day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:36:34 </td>
   <td style="text-align:left;"> $SPY Message volume currently at support. Could get ugly the next few days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:35:10 </td>
   <td style="text-align:left;"> $SPY oh no even VIX is red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:34:48 </td>
   <td style="text-align:left;"> $SPY futures should be deciding a direction soon here. Wont stay camped put for much longer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:34:11 </td>
   <td style="text-align:left;"> $SPY Vaccination is the key to spreading the virus because people are asymptomatic.
And the  unvaccinated get all the ass kicks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:33:57 </td>
   <td style="text-align:left;"> $SPY  I’ll take the average yearly Spy return. But monthly with options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:33:04 </td>
   <td style="text-align:left;"> $SPY  Death is only the beginning for Options traders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:32:05 </td>
   <td style="text-align:left;"> $SPY This is an amazing country

Vaccination is the key to spreading the virus because people are asymptomatic.
There are at least 5 infected  people sitting mask less in our office making fun of the two unvaccinated who never tested positive as they are much careful than others.

And the  unvaccinated get all the ass kicks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:31:00 </td>
   <td style="text-align:left;"> $SPY holy shit futures are down so much.. bahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:30:54 </td>
   <td style="text-align:left;"> $SPY  Trading above 5 moving averages as we speak. That’s the bull thesis 🥂💨🏦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:29:14 </td>
   <td style="text-align:left;"> $SPY Just a little more to go before global economic collapse. Maybe 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:29:14 </td>
   <td style="text-align:left;"> $SPY the rippin and the tearin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:28:34 </td>
   <td style="text-align:left;"> $SPY gold should be at $2260 I’m sure that the fed factors in bank manipulation in gold price as lower inflation data 🤡s $GLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:28:06 </td>
   <td style="text-align:left;"> $SPY I like trading and suggesting trades that I can’t enter myself here. Helps people and makes me feel complete 🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:26:18 </td>
   <td style="text-align:left;"> $SPY Is anybody thinking of going all-in on crypto? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:25:54 </td>
   <td style="text-align:left;"> $SPY https://www.youtube.com/watch?v=n7hiDaN3NH8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:25:51 </td>
   <td style="text-align:left;"> $SPY bear extinction after year 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:23:50 </td>
   <td style="text-align:left;"> $SPY  I just wanna say I love 3 chi products 💨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:23:36 </td>
   <td style="text-align:left;"> $SPY ive been living fast fast fast fast
Feeling really bad bad bad bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:23:27 </td>
   <td style="text-align:left;"> $SPY futes are fuckin rippin amirite </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:23:15 </td>
   <td style="text-align:left;"> $SPY hi bear

how has this year been for you ??

🤡🤡📈🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:22:28 </td>
   <td style="text-align:left;"> $SPY It&amp;#39;s dumb ass Idiots like this that just Love the Pandemic Love wearing a mask and love the idea of endless booster shots 🤬
https://www.today.com/health/woman-tests-positive-covid-19-flight-isolates-5-hours-bathroom-rcna10303?cid=sm_npd_nn_fb_ma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:22:18 </td>
   <td style="text-align:left;"> $SPY Jeez, futures are flat enough to get pimped out by Maxwell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:21:39 </td>
   <td style="text-align:left;"> $SPY  Crown Me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:21:36 </td>
   <td style="text-align:left;"> $SPY any death pools on the next octogenarian celebrity to go? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:21:25 </td>
   <td style="text-align:left;"> $SPY @InternetQ1234 I live in a place that you dream of. Does that bother you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:21:19 </td>
   <td style="text-align:left;"> $SPY Posting non stop why brother..no one minds will change. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:20:52 </td>
   <td style="text-align:left;"> $SPY 
Futes are rippin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:20:02 </td>
   <td style="text-align:left;"> $SPY  and you thought I was pulling numbers out of my ass. Hehe 
TINA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:19:52 </td>
   <td style="text-align:left;"> $SPY $AAPL A Bogandoff twin has died. What effect will this have on stock and crypto markets? I predict wide scale uncertainty and bearish on crypto as 1/2 of its creator is no more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:18:12 </td>
   <td style="text-align:left;"> $SPY $CODX $CEMI $XBI $XHE
U.S. COVID update: New cases set world record, number in hospital rising

- New cases: 484,377
- Average: 302,132 (+34,394)
- States reporting: 50/50
- In hospital: 84,293 (+5,594)
- In ICU: 17,577 (+220)
- New deaths: 1,937
- Average: 1,232 (-17) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:17:30 </td>
   <td style="text-align:left;"> $SPY Covid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:16:27 </td>
   <td style="text-align:left;"> $SPY 450 and $490 PT with Vix being low???? Cmon people do better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:15:05 </td>
   <td style="text-align:left;"> $SPY The only path forward is open the economy up for more people to come internationally to the U.S... it will create a rising GDP and fill jobs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:14:59 </td>
   <td style="text-align:left;"> $BA  SP500 $SPY GOES TO 5600 in 2022.  And that’s a conservative estimate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:14:44 </td>
   <td style="text-align:left;"> $SPY #themoreyouknow #confirmed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:14:12 </td>
   <td style="text-align:left;"> $SPY  market always made a stop or back with theses news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:14:03 </td>
   <td style="text-align:left;"> $SPY I’m a few hours ahead located in China, futures are ripping! Green as fuck 45pts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:12:47 </td>
   <td style="text-align:left;"> $SPX $SPY $EZA  #SouthAfrica #Omicron cases are now crashing from the peak.  Click on the 7-day moving average on the &amp;quot;new cases&amp;quot; chart here... https://www.worldometers.info/coronavirus/country/south-africa/  

Should see a similar pattern in the US as #COVID19 Omicron burns through the unvaccinated older/sicker population in particular, and &amp;quot;naturally boosts&amp;quot; the vaccinated, even the boosted who don&amp;#39;t wear masks over the next few weeks.  

Unfortunately it will also kill some older/sicker vaxed and boosted patients who don&amp;#39;t realize they have poor immune responses, and the usual seemingly random group of healthy, younger patients who also did not realize their immune system was suppressed.  

The vaccine does not improve a patient&amp;#39;s immune response.   It gets it primed to variable degrees depending on the strength of a patient&amp;#39;s immune response to fight the virus from day one.  Masks and distancing are the only other things that will more completely protect the older/sicker. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:12:25 </td>
   <td style="text-align:left;"> $SPY futures bout to go deep green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:12:04 </td>
   <td style="text-align:left;"> $SPY Futures not bad at this time of night, as you know this will be the last buying opportunity of 2021, how bout some options 9n the SPY $483 for January 4th???  BABY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:11:29 </td>
   <td style="text-align:left;"> $SPY The game of using shrinkflation to keep reported inflation running softer is over. We now have shrinkflation with inflation running amock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:10:57 </td>
   <td style="text-align:left;"> $SPY history repeats 

https://rightsfreedoms.wordpress.com/2021/08/13/the-1918-spanish-flu-only-the-vaccinated-died/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:10:52 </td>
   <td style="text-align:left;"> $SPY 

The bear market will last over 30 years when it arrives - and it will arrive. 
Ask Japan how they did it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:10:19 </td>
   <td style="text-align:left;"> $BTC.X $SPY what would happen to btc and spx if China collapsed?  It’s already happening and no one is talking about it.  China catches a cold and the world catches Pneumonia. 30% of Chinese GDP is predicated on housing. 70% of Chinese wealth is in their homes.  90% of Chinese home buyers canceled the last 60 days. house value to income is 50/1. Japan at the peak in 1989 was at 17/1.  If deleveraging starts it’s going to get really ugly but no one knows when this will start. Evergrande and all Chinese  developers’ bonds are selling pennies on a dollar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:10:07 </td>
   <td style="text-align:left;"> $SPY hahahahahahahahahahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:10:06 </td>
   <td style="text-align:left;"> $SPY Love is patient, love is kind. It does not envy, it does not boast, it is not proud. It does not dishonor others, it is not self-seeking, it is not easily angered, it keeps no record of wrongs. Love does not delight in evil but rejoices with the truth. It always protects, always trusts, always hopes, always perseveres. True Love never ends. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:09:58 </td>
   <td style="text-align:left;"> $SPY tomorrow market hours?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:09:29 </td>
   <td style="text-align:left;"> $SPY Somebody said futures are crashing? You mean that red pixel? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:09:20 </td>
   <td style="text-align:left;"> $SPY $FB today I saw a video of Zuck shooting dice in the metaverse with meta gloves on so he can actually touch shit in there. Blew my mind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:09:02 </td>
   <td style="text-align:left;"> $SPY where do you guys see futures crashing lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:08:40 </td>
   <td style="text-align:left;"> $SPY man, what I wouldn’t do to see the future </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:08:23 </td>
   <td style="text-align:left;"> $SPX $spy $SSNLF $MU  Smooth one 🇨🇳 China! Lockdown the city where Samsung and Micron build memory chips.  Which is the only city the has the “only outbreak” in a Country with $1billion+ people.  Lol. If they don’t get Taiwan, then “no chips for you”

https://www.reuters.com/world/china/micron-warns-dram-chip-delays-due-chinas-xian-lockdown-2021-12-29/?utm_medium=Social&amp;amp;utm_source=twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:08:14 </td>
   <td style="text-align:left;"> $SPY dad? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:08:03 </td>
   <td style="text-align:left;"> $SPY futures crashing at this hour is actually very bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:07:41 </td>
   <td style="text-align:left;"> $SPY stop paying attention to the futures and start paying attention to these MM crooks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:07:40 </td>
   <td style="text-align:left;"> $SPY she fuck with me cause I got the vision! 👁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:07:21 </td>
   <td style="text-align:left;"> $SPY $FB all I know is Zuckerberg sold shares at ATH and conveniently right before the name change. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:07:09 </td>
   <td style="text-align:left;"> $SPY The market is struggling just above the upper daily BB. Model is still long, but waning strength. https://grizzlybulls.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:06:13 </td>
   <td style="text-align:left;"> $SPY SPY 2021-12-29 Daily Forecast Video: 
https://www.youtube.com/watch?v=Mwo1loGaMiE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:05:41 </td>
   <td style="text-align:left;"> $SPY futures Crashing. Bye bye bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:05:16 </td>
   <td style="text-align:left;"> $SPY You wanna see a real collapse? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:05:13 </td>
   <td style="text-align:left;"> $GME $AMC $SPY $XRT XRT which is riddled with FTDS had a major FTD cover today volume candle and it resulted in GME flying as well. Shorts have shorted this index into oblivion trying to facilitate naked short selling &amp;amp; death spiral algorithm. Fun times ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:04:12 </td>
   <td style="text-align:left;"> $SPY 

One day closer to sonic leAving forever and bernie sanders retirement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:03:04 </td>
   <td style="text-align:left;"> McClellan Oscillator: The Best Market Timing Indicator?

$NKLA $NIO $PLTR $LCID $SPY 

http://www.chartlearning.com/2021/11/what-is-the-mcclellan-oscillator-indicator.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:02:42 </td>
   <td style="text-align:left;"> $SPY market open on Friday or closed ? Thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:02:06 </td>
   <td style="text-align:left;"> $STUDY 2022 contribution💰 hits the Roth IRA on 3 January, how are you deploying it? Or what are you waiting to buy on a dip? 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:01:35 </td>
   <td style="text-align:left;"> $SPY 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 12:00:28 </td>
   <td style="text-align:left;"> $SPY maybe dips tomorrow finally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:58:53 </td>
   <td style="text-align:left;"> $SPY $RLFTF $NXRP

https://www.nrxpharma.com/wp-content/uploads/2021/12/NRX-Aviptadil-Breakthrough-Designation-Request-Dec-28.pdf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:58:50 </td>
   <td style="text-align:left;"> $SPY I see aunt Jemima is all upset and running ads now to make pearl milling company cool now lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:57:23 </td>
   <td style="text-align:left;"> $FTK We have a buyer in the house! An American company for sale. Who wouldn&amp;#39;t want to take part? $SPY $TSLA 

1.11$ so far 

(NYSE: FTK) has received an unsolicited indication of interest for a potential transaction for all or part of the Company. To assist in evaluating this unsolicited indication of interest, Flotek&amp;#39;s Board of Directors has engaged Piper Sandler &amp;amp; Co. (&amp;quot;Piper Sandler&amp;quot;) as a financial advisor to assist with the evaluation process. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:57:08 </td>
   <td style="text-align:left;"> $SPY 

https://www.cnbc.com/amp/2021/12/29/us-covid-cases-rise-to-pandemic-high-as-delta-and-omicron-circulate.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:56:19 </td>
   <td style="text-align:left;"> $SPY they said it was going to 450 so I bought puts they said they said. Bears! Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:56:15 </td>
   <td style="text-align:left;"> $SPY  SPY top stocks were red today and continued to drop AH, futes are all red.. Expect a lot volatility tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:55:01 </td>
   <td style="text-align:left;"> $SPY All I want is the truth. I just want the dam truth. Is that so much to ask?

https://www.youtube.com/watch?v=8MJio3s2wFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:54:37 </td>
   <td style="text-align:left;"> $SPY — CONSERVATIVELY — SPY goes to 5600 in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:54:00 </td>
   <td style="text-align:left;"> $SPY I can draw lines too! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:53:18 </td>
   <td style="text-align:left;"> $SPY should be a green day, no matter what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:51:36 </td>
   <td style="text-align:left;"> $SPY I hereby declare Covid-19 over. Run to the nearest public bathroom and lick the floor, it&amp;#39;s safe now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:50:32 </td>
   <td style="text-align:left;"> $SPY waiting for a VIX spike so I can short it’s products </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:49:59 </td>
   <td style="text-align:left;"> $SPY clot shots 

https://conejoguardian.org/2021/12/14/more-vc-nurses-blow-whistle-on-overwhelming-numbers-of-heart-attacks-clotting-strokes/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:49:47 </td>
   <td style="text-align:left;"> $SPY I think better outcome can come on trade by this method. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:48:17 </td>
   <td style="text-align:left;"> $SPY 
Biden’s winter of death is coming for you bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:46:59 </td>
   <td style="text-align:left;"> $SPY stock analysis.  What is next? 480 or something else 🤔 

Watch

https://youtu.be/gsCANGVrpi0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:45:47 </td>
   <td style="text-align:left;"> $SPY am I the only one that sees this, if it follows trend, this needs a $450-$455 pull back before it can go to $500, learn how to play both sides of the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:45:44 </td>
   <td style="text-align:left;"> $SPY thank goodness im hedged with some calls and short uvxy. Looks like Vix is headed to hell. 🥴... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:45:41 </td>
   <td style="text-align:left;"> $SPY I wonder how badly the corporate media will be damaged by their fear campaign when everyone knows Omicron is basically a cold next month.

https://youtu.be/OM2VgBm9pTI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:44:48 </td>
   <td style="text-align:left;"> $SPY y’all the market IMO for your money 💴 and then you get the same boat 🛥 buy a bunch and then we’ll find something different lol 😆 we will see you tomorrow if you’re interested or if you’d like 👍 can </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:44:00 </td>
   <td style="text-align:left;"> $SPY I see now.  Government sees Omicron as best chance for herd immunity so they are hoping for as many to catch it as possible.  Damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:43:46 </td>
   <td style="text-align:left;"> $SPY Never ever forget that it is good to be alive. Remember that.
https://www.youtube.com/watch?v=VqhCQZaH4Vs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:41:28 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:41:19 </td>
   <td style="text-align:left;"> $SPY C’mon man.. the lions too?ZOOKEEPER: 3 Unvaxxed Lions At New Orleans Zoo Test Positive For COVID-19, Can&amp;#39;t Stop Coughing and Sneezing - Breaking911  https://breaking911.com/3-unvaxxed-lions-at-new-orleans-zoo-test-positive-for-covid-19-cant-stop-coughing-and-sneezing/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:40:13 </td>
   <td style="text-align:left;"> $SPY yah definitely easier to play the up side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:39:50 </td>
   <td style="text-align:left;"> $SPY we all should wait for Pelosi to release her new set of trades </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:39:13 </td>
   <td style="text-align:left;"> $SPY So Omicron is milder, provides good immunity against the previous variants. AND, the vaccines work against it. 
 
A covid pill is approved so let&amp;#39;s now load up a fleet of C17s and drop this all over Africa, India and the middle East. 
 
Time to wrap this up for the history books! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:38:24 </td>
   <td style="text-align:left;"> $SPY 

The theme of 2021:  Progressives ran off the Indian, but kept the land. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:37:26 </td>
   <td style="text-align:left;"> $SPY tank it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:36:43 </td>
   <td style="text-align:left;"> $SPY miracle green on the AM, no worries </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:36:25 </td>
   <td style="text-align:left;"> $SPY $BTC.X 
When they all think it’s going to crash…. You know it’s actually time to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:35:52 </td>
   <td style="text-align:left;"> $SPY futes zzzzzzZZZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:35:21 </td>
   <td style="text-align:left;"> $SPY I like to post bannon on occasion cuz it gets the lefties to go apeshit. Never vote in my life. Natalie Winters is hot.

https://rumble.com/vrml9a-pfizer-partnered-with-chinas-vaccine-passport.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:34:52 </td>
   <td style="text-align:left;"> $SPY lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:34:47 </td>
   <td style="text-align:left;"> $SPY OMG!! I was trying to tell the Bears about this bull run but of course they didn’t listen and now they missed out on   thousands of dollars because they are persistent at being small minded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:34:11 </td>
   <td style="text-align:left;"> $SPY $QQQ
The Omicron cycle for me was eight days from first symptoms to no more signs of it, if anyone wants a data point.  Only the first day or so was like the flu.  Not sure why anyone would bother to get tested.  If you have symptoms just assume you have it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:34:04 </td>
   <td style="text-align:left;"> $SPY Still waiting for black swan and “the big one” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:32:25 </td>
   <td style="text-align:left;"> $SPY can we just drop so I can sell tons of puts again fcking ey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:32:17 </td>
   <td style="text-align:left;"> $BTC.X $SPY 
Tomorrow should be green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:31:47 </td>
   <td style="text-align:left;"> $SPY 3rd flat future night in a row. Will there be last chance tax selling tomorrow or friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:31:46 </td>
   <td style="text-align:left;"> $TSLA I just rode in a 2020 Model 3 Performance. Fastest car I ever have been in. Torque is mind blowing. New update is amazing. It&amp;#39;s Game Over. Buying more TSLA tomorrow. $GM and $F. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:30:49 </td>
   <td style="text-align:left;"> $SPY Apple PB ratio 2018 = 10
APPLE PB ratio 2021 = 46
hmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:30:39 </td>
   <td style="text-align:left;"> $SPY Actually volume was not too low today 55mm. We have had many 40mm days before at such low vix. Lets see if we make a move to 4800+ on futures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:30:34 </td>
   <td style="text-align:left;"> $SPY Futes looking like they are about to take a huge dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:30:02 </td>
   <td style="text-align:left;"> Always do your hw have friends that know carpentry, plumbing etc do your research check the neighborhood talk to the neighbors $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:29:21 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:29:07 </td>
   <td style="text-align:left;"> $SPY  Now every day matters as it is a battle of angels and demons (bulls vs. bears) for control of the very fate of the market.  This break out can become a bull trap very fast and if that happens now it results in a quick move down and as the first the 2 weeks of Jan go so does the year. Last 2 days are Dojis so that is good in that we may get few days of sideways action and calm some nerves.  If you are a bull you want as few Dojis as possible and want the SC rally to take effect and duh want price to move higher.  The MACD is encouraging also here as it is moving higher for the bulls.  Price is the number one indicator so that is mainly what it is all about as higher prices will fetch higher prices until Jan 14th if all goes right for the bulls best case senario, but I am looking at it hour by hour.  Look, a lot of people have one foot out the door or are out of the market.  The megacaps have to lead, but all caps matter and are connected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:28:53 </td>
   <td style="text-align:left;"> $SPY making 1 million dollars is easy, just ask 1 million people for a dollar ez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:27:52 </td>
   <td style="text-align:left;"> $SPY Trump mentioned dark winter during a group photo op before the virus hit, and when asked to explain, he just answered with &amp;quot;you&amp;#39;ll see&amp;quot; 

You do what you want with that info </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:27:49 </td>
   <td style="text-align:left;"> $SPY wow boring week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:27:12 </td>
   <td style="text-align:left;"> $SPY apple price to book = 46 .. yeah ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:26:57 </td>
   <td style="text-align:left;"> $MSFT $AAPL $SPY $BRK.B 

FINKLE IS EINHORN! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:26:20 </td>
   <td style="text-align:left;"> latex6ca81b859ec167504fb5a505f2aaaaafSMH)
mRNA technology ($PFE, $MRNA)
quantum computing ($IBM)
search engine (GOOGL)
etc.

Think of taxpayers as long-term investors (timescale of decades, even sometimes &amp;gt;50 years). It is the taxpayers who invested in these ideas via the means of government. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:25:35 </td>
   <td style="text-align:left;"> $SPY this whole *pandemic* was just to steal an election. And they played trump, he sold out too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:24:44 </td>
   <td style="text-align:left;"> $SPY You see the entire value is speculation beyond 1 price to book, even at 1 there is a chance for decline AKA EGO at 0.47 price to book. It is all speculation on the future earnings. What does this mean? It means there is a long way down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:24:30 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ll take a 20 percent correction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:23:57 </td>
   <td style="text-align:left;"> $SPY bloodbath next two days. Crash imminent. $470 friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:23:52 </td>
   <td style="text-align:left;"> $SPY 

https://rumble.com/vrmdjh-its-time-stop-the-vaccination-and-treat-the-vaccine-injured.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:23:23 </td>
   <td style="text-align:left;"> $SPY covid crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:23:05 </td>
   <td style="text-align:left;"> $SPY https://www.youtube.com/watch?v=LTseTg48568 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:22:50 </td>
   <td style="text-align:left;"> $SPY I disagree with those saying Omicron was dear mongering... 
 
The response was fully warranted until the variant was understood but now we know it is not the beast it could have been. Onwards to 500, LFG! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:22:31 </td>
   <td style="text-align:left;"> $SPY covid going to crash this again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:22:30 </td>
   <td style="text-align:left;"> $SPY  The S&amp;amp;P ytd is 28% with an average of 15% over 10 years... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:21:56 </td>
   <td style="text-align:left;"> $SPY hmmm where will it spike </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-30 11:21:46 </td>
   <td style="text-align:left;"> $SPY S&amp;amp;P limit down and it still wasn&amp;#39;t done .. lol.. who will be the last one out this time? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:58:10 </td>
   <td style="text-align:left;"> $QQQ well test 399.7 tomorrow, if that don’t hold, we’ll most likely try 392 support by Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:56:55 </td>
   <td style="text-align:left;"> https://www.investing.com/indices/indices-futures  $f $tsla $ccl  $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:55:06 </td>
   <td style="text-align:left;"> Some other interesting option trades...

$QQQ $SPY $EEM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:53:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 48426300. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:43:40 </td>
   <td style="text-align:left;"> $DWAC $SPY $QQQ 
Total psy-op false flag Lefty scam..

https://m.youtube.com/watch?v=qwYIWno8EJo&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:42:46 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

Anyone heard from Crossing Trends? Or did he go broke? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:40:20 </td>
   <td style="text-align:left;"> $QQQ Get ready! I might get in. And when I do it crashes. LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:39:52 </td>
   <td style="text-align:left;"> $SPY $TSLA$juicewrld $QQQ $NFLX $DIS alexa play all girls are the same </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:38:35 </td>
   <td style="text-align:left;"> $SPY $QQQ bull flag will break by 3 am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:18:42 </td>
   <td style="text-align:left;"> ETF Sentiment: $QQQ is the #2 ETF that institutions are trading with 55.3K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:05:17 </td>
   <td style="text-align:left;"> $QQQ https://www.reddit.com/r/MillennialBets/comments/rro07z/ktta_the_shorts_are_actually_trapped_here/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 13:01:07 </td>
   <td style="text-align:left;"> $QQQ 405.71 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 12:52:40 </td>
   <td style="text-align:left;"> $SPY $QQQ corrupt govt..corrupt market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 12:46:36 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ i just apply for cash account and option from help from holly , y’all get ready 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 12:35:15 </td>
   <td style="text-align:left;"> McClellan Oscillator: The Best Market Timing Indicator?

$QQQ $DWAC $NVDA $RIVN $PLUG

https://www.chartlearning.com/2021/11/what-is-the-mcclellan-oscillator-indicator.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 12:25:09 </td>
   <td style="text-align:left;"> $QQQ stonks only go up -🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 12:09:18 </td>
   <td style="text-align:left;"> $QQQ easy 100% on puts tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 12:02:06 </td>
   <td style="text-align:left;"> $STUDY 2022 contribution💰 hits the Roth IRA on 3 January, how are you deploying it? Or what are you waiting to buy on a dip? 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:49:37 </td>
   <td style="text-align:left;"> $QQQ stock analysis 

https://youtu.be/7ISQQLghTaw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:44:02 </td>
   <td style="text-align:left;"> $AMZN $QQQ not a lot of details, but Amazon posted on their blog their 3p sellers did  record sales this holiday season.

https://www.aboutamazon.com/news/small-business/independent-selling-partners-broke-amazon-records-this-holiday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:34:11 </td>
   <td style="text-align:left;"> $SPY $QQQ
The Omicron cycle for me was eight days from first symptoms to no more signs of it, if anyone wants a data point.  Only the first day or so was like the flu.  Not sure why anyone would bother to get tested.  If you have symptoms just assume you have it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:24:32 </td>
   <td style="text-align:left;"> $QQQ can someone tell me why VTIVX is down 13% it’s a fund </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:18:59 </td>
   <td style="text-align:left;"> $mrna $BNTX my predictions are coming true. many of you who know me knew I said there would be a winter surge and another variant in September. I said there would be increased hospitalizations and death with this latest variants weeks back. I said children’s cases would surge and fill ICUs  $nvax $spy $qqq how often is my broken clock right? This does not bring me satisfaction To say these things aside from laughing at those that deny me this much.  
https://deadline.com/2021/12/omicron-surge-slams-los-angeles-hospitals-1234902721/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:18:08 </td>
   <td style="text-align:left;"> $SPY $QQQ i guess both calls and puts are getting killed this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:14:19 </td>
   <td style="text-align:left;"> $QQQ puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:05:00 </td>
   <td style="text-align:left;"> In the last month $QQQ has a been trading in the 377.47 - 404.58 range, which is quite wide. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:03:59 </td>
   <td style="text-align:left;"> $PTON Hedge funds walk away from Peloton amid post-COVID decline and 52-week lows
Turn the lights out for Peloton💩 while Market $SPY $QQQ near ATHS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:03:49 </td>
   <td style="text-align:left;"> This is a great breakdown $VOO $VTI $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:03:08 </td>
   <td style="text-align:left;"> The most unusual job market in modern American history, explained

https://www.washingtonpost.com/business/2021/12/29/job-market-2021/

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 11:02:17 </td>
   <td style="text-align:left;"> Opinion: Which ‘gray swan’ risk could derail the U.S. economy and the stock market in 2022?

https://www.google.com/amp/s/www.marketwatch.com/amp/story/which-gray-swan-risk-could-derail-the-u-s-economy-and-the-stock-market-in-2022-11640799334

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:44:36 </td>
   <td style="text-align:left;"> $QQQ Been making lower highs and it didn’t break above previous high while $SPY did, interesting… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:42:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK Hope people finally realize that last year was just a lucky year for Cathie Wood, stop treating her like some kind of genius. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:28:38 </td>
   <td style="text-align:left;"> $SPY WHAT IF I TOLD U THAT FOR THE PAST 6 TRADING SESSIONS A CRIMINAL BID SPOOFING MANIPULATING CITADEL SCAM ALGORITHM IS MANIPULATING SHARE PRICE, STEALING BILLIONS IN OPTIONS PREMIUM, AND PROPPING MARKETS FOR A MASSIVE CRASH THAT WILL BANKRUPT THE MIDDLE CLASS, ONLY TO ENRICH THE 1%? $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:27:47 </td>
   <td style="text-align:left;"> $SPY $QQQ I see the internet still allows broke $$ ignorance and zero accountability.  Its like the last 150+ monster BTD winners in a row somehow are forgotten and the bearish idiots still want to fight $$. We can wipe you out without even trying.
 
The best part of all this BS drama is knowing bears have failed lives.

Market will always go to ATH and 90% of idiots posting fear mongering BS get wiped out, lets dance on their graves!!!

Non-stop Winning and making $$ because human ignorance never stops paying me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:27:16 </td>
   <td style="text-align:left;"> ($slv $gld $gold $gld) hedges and stores of value tore up. All hail tech $qqq it&amp;#39;s been this way for awhile now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:25:19 </td>
   <td style="text-align:left;"> $SPY $QQQ If you stay stubborn and keep shorting in 2022 then you are very likely to continue to lose money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:24:12 </td>
   <td style="text-align:left;"> $SPY $QQQ they pump the futures overnight everyday to green and then the market struggles to hold it. if you don&amp;#39;t see a problem then.... well I have nothing left to say just good luck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:23:09 </td>
   <td style="text-align:left;"> $QQQ https://youtu.be/TMYaE-1bTZM ❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:21:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Biggest difference between 2020 and 2021 is that in 2020 we had a reality show clown in the White House who had no idea how to deal with COVID and in 2021 we have a strong and smart leader who know exactly what to do to fight against COVID, that&amp;#39;s why this year is so much better than last year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:21:33 </td>
   <td style="text-align:left;"> latexfb138c22d24a7045dcb62e6e13a67e1a in graphic processing unit (GDU) maker NVIDIA Corporation (NVDA) one month before reports surfaced that the company&amp;#39;s chips would be used in a U.S. supercomputer&amp;#39;

$QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:21:01 </td>
   <td style="text-align:left;"> $DWAC $SPY $QQQ .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:17:50 </td>
   <td style="text-align:left;"> $qqq $spy $dia the unexpected shock could be a big decline in January. Most people are positioned for a rally. But January plunges have happened before. Few are prepared for it and valuations are stretched. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:16:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Looks like we are heading for a fairly flat day tomorrow then the market will open 2022 sharply higher next Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:14:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Can someone tell me why 81 million people voted for these Dem socialist parasites in DC? They just want to suck the life out of every hard worker, entrepreneur, business owner. Higher taxes, more restrictions, new mandates. They never created anything they just want take take take. Trillions of $$$s wasted &amp;amp; it’s never enough. Stop voting for them you idiots!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:14:08 </td>
   <td style="text-align:left;"> $SPY ASIA IS DEEP RED. DAX IS ABOUT TO GET SHORED. GOLDMAN IS ALERTING CLIENTS, JP MORGAN IS PAYING OFF CNBC TO HIDE PUMP UP MARKETS ITS NOT LOOKING GOOD FOR THE BULLS. $480 IS A TARGET THAT RIS NOT ATTAINABLE $QQQ $IWM $ES_f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:09:23 </td>
   <td style="text-align:left;"> $QQQ 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:03:52 </td>
   <td style="text-align:left;"> Another day of trading is behind us now! 
$SPY treated us well today as did $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:03:06 </td>
   <td style="text-align:left;"> $QQQ $spy massive deferred tax gain selling likely to slam the markets in the first week or two of January. By selling in Jan., investors and funds can defer cap. gains taxes until 2023. Also geopolitical events and pandemic news could hurt. I expect a decline of at least 15% next month, but a larger decline is possible once the selling starts and panic sets in. The markets are a game of musical chairs after all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:02:32 </td>
   <td style="text-align:left;"> $SPY $QQQ Goldman sees inflation normalizing lower, as it tends to do.  Worth a read if you&amp;#39;re the worrying or shit-posting type:  https://heisenbergreport.com/2021/12/29/why-goldman-expects-inflation-to-settle-down-in-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:02:28 </td>
   <td style="text-align:left;"> $SPY $QQQ I’ve been looking at my positions too closely lately.  Time to step back and look from a distance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 10:01:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA At this point I don’t even care anymore if futures are up, I’d rather have it down and have the markets run up during session…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:54:38 </td>
   <td style="text-align:left;"> $QQQ FUTES BOUT TO GO GREEN
BOOIIIII </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:54:30 </td>
   <td style="text-align:left;"> $BTC.X what&amp;#39;s with this hodler bruhs? $QQQ $ETH.X $SPY https://youtu.be/7ZBC3mJxZGk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:50:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA 

U.S. Covid cases rise to pandemic high as delta and omicron circulate https://www.cnbc.com/2021/12/29/us-covid-cases-rise-to-pandemic-high-as-delta-and-omicron-circulate.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard
Stocks set to drop . Expect a circuit breaker an $VIX to go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:46:01 </td>
   <td style="text-align:left;"> $SPX $SPY C&amp;amp;I loans fall. The last 2 times contractions like this occurred 2000 and 2007. Both periods had bear markets follow. Did COVID pull forward too much? Stagflation and rising rates not good for loan growth? $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:45:15 </td>
   <td style="text-align:left;"> $SPY Maaan, those Auburn Tigers play the D almost as good as Jpow vs shorts $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:38:47 </td>
   <td style="text-align:left;"> TP 65min: all 3 in strong RSI bull ranges above the rising MA bands. Bumping up agains some levels. just digesting for now $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:38:27 </td>
   <td style="text-align:left;"> $QQQ Glimpse of Putin and Biden going at it tomorrow. 😆 $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:37:15 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA $NVDA $SPY Rest in peace to the legend... may he continue to pomp eet from the grave :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:35:19 </td>
   <td style="text-align:left;"> TP Daily: Not a spot where we want $IWM to turn back. So far nothing more than a rest day after a few on the go... $SPY $QQQ don&amp;#39;t look too worried. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:35:01 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK

futes up bigly... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:34:08 </td>
   <td style="text-align:left;"> $QQQ $spy don&amp;#39;t bet what you can&amp;#39;t afford to lose of course. But my forecast is for a significant decline in January. I&amp;#39;m laddering weekly puts. Higher strikes for near term (Jan3,5,7) and lower strikes for the second and 3rd week of Jan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:32:03 </td>
   <td style="text-align:left;"> $QQQ But what us wrong with the nikkei future 🤡🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:26:47 </td>
   <td style="text-align:left;"> $PTON PTON 30.00 breaks then 28.00 then back to COVID-19 2020 Lows 17.70

While Market $SPY and $QQQ near ATHs however the Whole Market is likely to drop ( -10 % possibly) early next year in January 2022 sometime or shortly afterwards . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:21:53 </td>
   <td style="text-align:left;"> $QQQ $spy $dia markets down 15-25% early next year. Going to be a very bad two weeks into mid January. Especially in QQQ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:16:57 </td>
   <td style="text-align:left;"> $QQQ $SPY 📈✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:07:37 </td>
   <td style="text-align:left;"> $QQQ $FB $AAPL https://www.bloomberg.com/news/articles/2021-12-28/apple-pays-unusual-180-000-bonuses-to-retain-engineering-talent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:04:16 </td>
   <td style="text-align:left;"> $QQQ with Omicron overwhelming the world now and hospitals soon, most people will get it within two months and governments will have to declare pandemic is over as no one will be at work due to self isolation at home. 

This time pandemic stocks like $ZM or $ROKU will not be going up like last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:04:00 </td>
   <td style="text-align:left;"> Looking at the yearly performance, $QQQ did better than 79% of all other stocks. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:03:04 </td>
   <td style="text-align:left;"> $SPY $QQQ ….Thursday meeting with Putin goes….Come on man the Ukraine hasn’t paid Hunter in years now and that damn laptop and Rudy…have at it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 09:02:46 </td>
   <td style="text-align:left;"> $SPY Biden vs Putin $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:59:02 </td>
   <td style="text-align:left;"> $SPY 💡 Trade Idea 💡- extremely probable that this triggers tomorrow especially with the Q&amp;#39;s sitting on a fresh bounce off support. 1/18/22 485s should trigger in the 2.1 range with a profit margin between 60-100%. GL to you all. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:56:25 </td>
   <td style="text-align:left;"> $QQQ well fellow bears, the last week wiped me out on the Q’s…got no powder left to join the crusade.  Best of luck to you all, I’ll be watching from the sidelines rooting for the collapse of this overbloated pig! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:54:46 </td>
   <td style="text-align:left;"> $QQQ $SPY NY is going to lockdown tomorrow. Mark this. Not that it matters that much but it gives the push for these inflated assets to pop a little bit sooner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:50:56 </td>
   <td style="text-align:left;"> $QQQ 📉💲💸📉💲💸📉💲
if you love yourself invest in Pre-IPos.  I am placing a link for who I always use.  
Investors.be4ipo.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:47:48 </td>
   <td style="text-align:left;"> $QQQ Roflmao...goodbye easystreet $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:45:16 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ The market is open Friday everyone. Why does everyone think tomorrow is the last trading day? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:44:24 </td>
   <td style="text-align:left;"> $QQQ stock analysis 
https://youtu.be/7ISQQLghTaw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:43:21 </td>
   <td style="text-align:left;"> $ARKK $SPY $QQQ &amp;gt;&amp;gt; 497 Stocks made New 52 Week Lows Today &amp;gt;&amp;gt; 

Which stocks on that list are going to rebound in January?

https://stockcharts.com/def/servlet/SC.scan?s=TSAL[t.t_eq_s]![as0,20,tv_gt_40000]![tl0_lt_an1,253,tl]&amp;amp;report=predefall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:43:15 </td>
   <td style="text-align:left;"> $QQQ can see it go green tomorrow as it bounced off demand today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:41:49 </td>
   <td style="text-align:left;"> $SPY $QQQ futures aren’t even down bad chill lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:39:45 </td>
   <td style="text-align:left;"> Santa Rally nothing but a scam! Rich continue to get richer. Small caps continue to be bearish 

50% of the market declining. 53% reaching new lows 

Media continues to ignore!

$SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:39:30 </td>
   <td style="text-align:left;"> $QQQ $TQQQ   ‘bout right.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:38:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $XBI $CEMI $CODX 
BREAKING: U.S. reports 400,000 new coronavirus cases, the biggest one-day increase on record, with some states yet to report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:36:09 </td>
   <td style="text-align:left;"> $SPY DRAIN THE SWAMP!!!$IWM $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:35:47 </td>
   <td style="text-align:left;"> $QQQ Retesting the breakout... These usually turn out to be the best setups. 

https://share.trendspider.com/chart/QQQ/8130s8j6r5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:33:03 </td>
   <td style="text-align:left;"> January &amp;gt;&amp;gt; This is the Month where one person&amp;#39;s trash 🗑 becomes another person&amp;#39;s treasure 🤑 💰 

Make a list of the beaten down stocks that have the best chance of rebounding in January &amp;gt;&amp;gt;

$SPY $QQQ $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:27:16 </td>
   <td style="text-align:left;"> $SPY $QQQ …A Bear with no teeth is a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:23:54 </td>
   <td style="text-align:left;"> $QQQ We played calls off of the trendline support bounce and secured our last contracts two days ago for 3200% gains!!! For more plays like this join my discord, click the link in my bio. We give out free plays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:23:45 </td>
   <td style="text-align:left;"> $QQQ $350 please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:20:37 </td>
   <td style="text-align:left;"> $SPY futes dipping? BTFD $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:19:14 </td>
   <td style="text-align:left;"> $QQQ the next market correction is going to be absolutely brutal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:13:15 </td>
   <td style="text-align:left;"> I ❤ Dan ✔ Enjoy the Armageddon Depression my friends, followers, haters and those on block for jawboning stupid 😈 https://www.cnbc.com/video/2021/12/29/satori-fund-founder-dan-niles-on-why-hes-bullish-on-energy-and-financials-in-2022.html  ...   https://www.cnbc.com/video/2021/12/29/watch-cnbcs-full-interview-with-satori-funds-dan-niles-on-markets-and-inflation.html   $ccl $tsla $f  $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:11:44 </td>
   <td style="text-align:left;"> $QQQ -1.849 Million continuing jobless claims keep the faith that people are getting back to work without spooking the Fed  

Omicron getting under control, tomorrow we fly! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:10:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA San Francisco New York Chicago losing over a million residents in 2021.. You delusional braindead liberals leaving the sh*t piles you created to infect other parts of the country? These people are a spreading cancer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:07:39 </td>
   <td style="text-align:left;"> $QQQ $SPY …my gosh the massive tax selling coming before end of year is crazy crash levels…then they all buy back Monday you say?? Loading calls Friday i am game!! Party on!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 08:02:56 </td>
   <td style="text-align:left;"> Welcome to Crash Thursday https://www.investing.com/indices/indices-futures 😈
I covered my short $ccl at a loss Tuesday, no matter on that trade, made a lot of money on recent short CCL trades, unbelievable CCL has not sold of hard, what a scam it came sonclose to 19s only to rally higher.  Yesterday pist CCL I went short TESLA Wednesday and covered for profits, thereafter short FORD which is ridiculously overpriced in tandem with lots of negative news re driveshaft recalls, et al https://www.google.com/search?q=ford+motor+company+news+f&amp;amp;client=tablet-android-samsung-rev2&amp;amp;biw=1262&amp;amp;bih=652&amp;amp;tbs=qdr%3Ad&amp;amp;tbm=nws&amp;amp;ei=YPXMYdm3DsG3tQa9sJWACA&amp;amp;ved=0ahUKEwjZ547Zmor1AhXBW80KHT1YBYAQ4dUDCA0&amp;amp;uact=5&amp;amp;oq=ford+motor+company+news+f&amp;amp;gs_lcp=Cgxnd3Mtd2l6LW5ld3MQAzIICCEQFhAdEB4yCAghEBYQHRAeMggIIRAWEB0QHjIICCEQFhAdEB4yCAghEBYQHRAeMggIIRAWEB0QHjIICCEQFhAdEB4yCAghEBYQHRAeMggIIRAWEB0QHjIICCEQFhAdEB46BAgAEEM6BQgAEIAEUPEHWNMKYNETaABwAHgAgAFYiAH5AZIBATOYAQCgAQHAAQE&amp;amp;sclient=gws-wiz-news  Biden is a joke mandating EVs, get over it, Karen, mandate vaccines.  EVs represent a very small percentage of vehicle sales.  Furthermore we have an Armageddon Depression in queue in tandem with many other socioeconomic concerns including an income stock market crash. Carry on sticking forks in the stock markets and bitcoin at large for profits. Good health and trading to all.  Thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker 💀😈☠🐻✔ $f $tsla $ccl $spy $qqq and more 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:54:11 </td>
   <td style="text-align:left;"> $SPY Are we set up identically with Dec - January 2008?
runup to new highs, followed by profit taking into a new year to defer capital gains tax.
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:50:31 </td>
   <td style="text-align:left;"> $SPY Forget the duck, I actually tell you where this headed by mid $QQQ 1 .

DAMN I love the cryptic 

#TechWreckFeb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:45:49 </td>
   <td style="text-align:left;"> $QQQ bruh puts at open for sure zero support under 401.5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:43:23 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM $USO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:37:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA SCOTTIE PIPPEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:35:59 </td>
   <td style="text-align:left;"> $QQQ $390 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:35:42 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM $DIA    
 
Few people realize the very essence of (the study of) economics. 
 
&amp;quot;Econo&amp;quot; and &amp;quot;omia&amp;quot; is from the Greek, loosely meaning &amp;quot;household [financial] management&amp;quot;.    In other words, budgeting wants and needs, in an environment restrained by finite resources. 
 
Well, fast forward to the glorified p(l)andemic, and the nothing of finite resources is completely gone.  4,000 million / day of new money, every day, for 2 years continuously. 
 
Let&amp;#39;s just say, if the US was a household, it wouldn&amp;#39;t last another hour.  And a true pity that economics (as it as known pre-mid 2010s) is dead.  buried.  eviscerated.   
 
Better off studying theology to figure out the markets henceforth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:31:02 </td>
   <td style="text-align:left;"> $SPY CNBC IS ANOTHER CRIMINAL ORGANIZATION COLLUDING WITH WALL ST AND SCAM ALGORITHIMS, &amp;quot;STOCKS ARE FLAT AFTER RECORD CLOSE&amp;quot; WTF?? EQUITIES ARE SELLING THE FUCK OFF, CRYPTO IS FREE FALLING, CHINA IS GOING ON LOCKDOWN, NEVER TRUST CNBC AND NEVER TRUST CRAMER, THEY ARE PROFESSIONAL FRAUDSTERS THEIR &amp;#39;INVESTMENT ADVICE&amp;#39; IS DESIGNED TO ROB U OF UR MONEY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:27:51 </td>
   <td style="text-align:left;"> $SPY anyone currently doing a strategy to collect 3%/week on SPY, $QQQ , or any other indices? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:26:03 </td>
   <td style="text-align:left;"> $SE $PINS one of the worst years for me vs $SPY $QQQ. Never experienced this sort of dichotomy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:21:07 </td>
   <td style="text-align:left;"> $SPY $QQQ e1 is saying Friday for last day to tax loss harvest but shouldn&amp;#39;t it have been today what with T+2?  TIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:19:21 </td>
   <td style="text-align:left;"> $QQQ trash. Rates will kill it. 🙌☠️
 https://www.tradingview.com/chart/QQQ/KuhZpxqd-Invesco-QQQ-Ponzied-Valuation-Matters-Smallcaps-Win/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:18:35 </td>
   <td style="text-align:left;"> $MRNA $bntx last 5/5. $spy $qqq $nbi. Bastards even hit buzz feed lol.. why </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:17:42 </td>
   <td style="text-align:left;"> $MRNA $bntx page 4 ssr list. $spy $qqq $nbi only go long on these sectors iMo weeklies will get raped Until they lose interest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:16:34 </td>
   <td style="text-align:left;"> $MRNA $bntx page 3 ssr list. $spy $qqq $nbi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:16:06 </td>
   <td style="text-align:left;"> $UPH $QQQ today was the last day to sell for a 2021 loss.  Time to move back up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:15:53 </td>
   <td style="text-align:left;"> $mrna $bntx page 2 ssr list. Oh and SPACS still a big target. $spy $qqq $nbi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:14:49 </td>
   <td style="text-align:left;"> $MRNA $bntx 5 pages of short list ssr today. Again, whole biotech index is targeted. Stay long and no weeklies. They can bring down the index from below and need to move on. They’re also after SPACS but definitely moving into mining, crypto facility, and autonomous driving technology shorting. Page 1/5 $spy $qqq $NBI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:07:37 </td>
   <td style="text-align:left;"> Stocks Rise On December 29 But Trouble Lies Beneath https://mottcapitalmanagement.com/stocks-rise-on-december-29-but-trouble-lies-beneath/ $aapl $msft $dia $qqq $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:07:10 </td>
   <td style="text-align:left;"> $SPY $QQQ So many folks on Stocktwits seem unaware that the historical average of the markets is ~7%.  If you&amp;#39;re a newish investor, know you&amp;#39;ve been grotesquely spoiled.  Give thanks for recent market years.  70 ATH&amp;#39;s for SPY.  Sure, speculative tech and biotech got crushed this year, but that happens.  You shouldn&amp;#39;t be in those sectors if you aren&amp;#39;t surprised by years like 2021.  Bio, especially, seems primed for a glorious 2022.  At least three of my top five picks for 2022 will be smid bios.   Deal with it, don&amp;#39;t whine about it.  My largest position is SPY.  Don&amp;#39;t gamble on spec until you&amp;#39;re mentally prepared for the beat-downs.  The melt-ups are easy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:06:25 </td>
   <td style="text-align:left;"> $QQQ time to commit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:05:44 </td>
   <td style="text-align:left;"> $QQQ NASI update: MacD and TSI (true strength indicator) crossed bullish.  First cross since the bearish cross which occurred week of Nov. 20 (QQQ all time high). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:05:39 </td>
   <td style="text-align:left;"> $QQQ $MSFT @maxwell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:05:06 </td>
   <td style="text-align:left;"> $XBI reached our first target of $111-12. Today&amp;#39;s action is very encouraging, we may go tomorrow a little lower, then resume the uptrend while $SPY and $QQQ correct, it looks like a pattern now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 07:02:43 </td>
   <td style="text-align:left;"> $SPY I think tomorrow will probably be the last up day before a pullback starts. 
$QQQ There is definitely some selling going on, I expect $NQ_F to reach around 16630 and reverse. If it makes an ATH, then scratch all my analysis, I was a trapped and go with the flow and buy every tiny dip. 
$IWM will be surprised if it goes above 226.54 before a good pullback. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:55:20 </td>
   <td style="text-align:left;"> @Ethle_Mertz $dia $qqq $spy. EX Pfizer VP FILES CHARGES. https://www.riotimesonline.com/brazil-news/modern-day-censorship/covid-19-pharmaceutical-giants-gates-fauci-uk-officials-accused-of-crimes-against-hum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:53:00 </td>
   <td style="text-align:left;"> $QQQ: Both the short term and long term trends are positive. This is a very positive sign. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:51:48 </td>
   <td style="text-align:left;"> $SPY $QQQ  shirt term needs a pullback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:51:14 </td>
   <td style="text-align:left;"> $SPY ALL SECTORS HAVE ALREADY ENTERED BEAR MARKET TERRITORY. MM , CITADEL, FED, WALL ST ARE ALL PROPPING UP THE DOG SHITTER FAANG OVERBOUGHT, OVERVALUED FRAUD STOCKS $MSFT $TSLA $AAPL LIKE IN THE DOT COM BUBBLE MEANWHILE SMALL CAPS ARE GETTING OBLITERATED. WHEN THEY POP THIS PONZI BUBBLE JUST PRAY YOU AREN&amp;#39;T CAUGHT UNDER IT. CLOSE UR CALLS IMMEDIETELY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:50:03 </td>
   <td style="text-align:left;"> $QQQ impressed at how this is not at 390 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:48:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $BAC $BA $NCLH 

Last year, nobody dreamed the Fed would raise rates until 2023. Now market makers need to factor in the possibility of at least three rate hikes, which will degrade the future earnings of growth stocks. 

Personally, I don’t think the Fed will be as aggressive as everybody fears, but this is not enough to give market makers the warm and fuzzy to continue aping into tech, growth, and other conceptual companies. 

I expect these companies to remain under pressure for quite some time. The travel sector is about as much risk as I am willing to take because I think the grand reopening narrative will return in about a month or so.

I might consider megacap tech once the valuations come down a bit. Other than that, I think value is the safest place to put money to work to actually make money. Won’t be anything like 2020 or 2021, but the environment has changed and we need to adapt accordingly. 

The same ole plays aren’t going to work under these market conditions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:48:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $GLD $SLV 

Daily market recap.  Enjoy. 

https://youtu.be/Ig1oXe_NqA8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:47:39 </td>
   <td style="text-align:left;"> $QQQ bull flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:42:02 </td>
   <td style="text-align:left;"> $ASTR If $QQQ rips tomorrow + company speaks out. We rebounding heavy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:41:37 </td>
   <td style="text-align:left;"> $QQQ puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:40:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK Going live at 7pm Central to breakdown my watchlist for the rest of the week and take as many chart requests from you as possible! What stocks do you want to see?
https://youtu.be/NEDzxbFLsOQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:40:18 </td>
   <td style="text-align:left;"> Make a plan and let the market come to you, sometimes no trade is the best trade. #Elliottwave #Trading #Stocks #ETFs #Bitcoin #bourse #dax30 $QQQ $DIA #SPY #aktien #forex #tradingsignals #pips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:37:59 </td>
   <td style="text-align:left;"> $QQQ $SPY bull flag on nasdaq too  
we gonna go higher and higher :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:30:57 </td>
   <td style="text-align:left;"> latex31e8657acf92cf705781899021438d51$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:28:09 </td>
   <td style="text-align:left;"> $SPY $QQQ Trump lost the election and he also lost to Biden in stock market performance. Biden just beat Trump in everything 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:26:58 </td>
   <td style="text-align:left;"> $TSLA Wih-whu, whuh what happened tesla, I thought u was going to the moon today 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:26:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM “Tax Loss Selling” is when investors sell their losing investments to offset capital gains, investors don’t sell their winning investments….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:23:24 </td>
   <td style="text-align:left;"> $TSLA   Chill

Last day of tax selling was today .

$spy  $QQQ   was green where all major stock were red .

#buythedip !🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:23:16 </td>
   <td style="text-align:left;"> $SPY $QQQ 2022 should be another favorable year for the bulls. COVID likely will become less and less of a factor to the US economy from now on and we could see some remarkable strength of the US economy that we have never seen before </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:21:44 </td>
   <td style="text-align:left;"> $SPY $QQQ …I would like Bears to please explain where the hell is a crash going to come from
1. More money is being invested by all types of people (young and old) and globally more and more each year which is more demand for stocks. Do Bears see money exiting the market anytime soon and why?
2. Large Cap companies are the ones that are bringing in increased revenues driving value…do you honestly see sell offs in the Large Caps anytime soon?
3. Covid…in covid culture more and more money going into Tech, Amazon, most all SP500 top companies. Little guy getting kicked to curb. See this changing?
More money going to SP500 and QQQ or out of it this next year?
4. Pay rates and minimum wages going up due to covid so more money going into 401k and savings funds
5. Inflation…company estimates were lowered last quarter but everyone paid way higher prices for the same shit so revenues and sales figures will be thru the roof. Inflation always transitions to the buyer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:20:22 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $HOOD 

Wasn’t Jim Cramer pumping Robinhood during their IPO? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:18:09 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 12/29/2021 $SPY $XLF $QQQ $CCJ $MSOS https://www.chartguys.com/daily-market-videos/4092/bull-flags-everywhere-but-will-they-hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:17:37 </td>
   <td style="text-align:left;"> U.S. trade deficit in goods jumps 17.5% to record $97.8 billion as imports surge

https://www.google.com/amp/s/www.marketwatch.com/amp/story/u-s-trade-deficit-in-goods-jumps-17-5-to-record-97-8-billion-as-imports-surge-11640785256

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:16:54 </td>
   <td style="text-align:left;"> What Social Trends Told Us About the American Economy in 2021

https://www.google.com/amp/s/www.nytimes.com/2021/12/29/business/economy/us-economic-trends-2021.amp.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:10:36 </td>
   <td style="text-align:left;"> $QQQ Looks like Santa took a great big crap in the bulls stocking. best hope ot wasnt infected with coronacold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:08:54 </td>
   <td style="text-align:left;"> A thread on when AI/ML/Data Science have been or can be harmful. Why it might be relevant? It is a new research topic and currently confined in the realm of academia. It takes time until policymakers pick up on these developments and write policies around these ideas but certainly as the public become more educated we will see major changes in AI policies that will be developed around these research. 

If you are not looking for technical discussion, here there is a list of popular books and podcasts by experts on this topic: https://www.aiethicist.org/recommended-books-podcasts-journals

More in comments

$SPY, $QQQ, $GOOGL, $AI, $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:06:48 </td>
   <td style="text-align:left;"> $QQQ $SPY so wait bears was that the big sell off? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:04:22 </td>
   <td style="text-align:left;"> $SPY $DIA $IWM $QQQ
SEND IT TO MOON @POTUS 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:04:18 </td>
   <td style="text-align:left;"> $QQQ tomorrow will be a big test </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:04:16 </td>
   <td style="text-align:left;"> ‪Will Santa Claus Rally Bring New Highs For Nasdaq 100 (QQQ)? - https://www.seeitmarket.com/will-santa-claus-rally-bring-new-highs-for-nasdaq-100-qqq/‬ 
 
‪article by @andrewnyquist $QQQ $XLK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:04:03 </td>
   <td style="text-align:left;"> $SPY $QQQ
The charts are setting up for a major pop. But you have to wonder how much longer can this continue to go up without a significant pullback! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 06:02:34 </td>
   <td style="text-align:left;"> $QQQ closed long going short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:50:33 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 230.1K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:48:20 </td>
   <td style="text-align:left;"> $QQQ down trend started, buckle up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:48:16 </td>
   <td style="text-align:left;"> Indexes are at all an all high, but growth is bleeding?
The rise of cryptocurrency among retail traders is a huge reason why these stocks continue to bleed.

$SNAP $FUBO $SPCE $GLSI $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:47:02 </td>
   <td style="text-align:left;"> $QQQ So the SEC is going to look away while half the markets get shorted to death lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:46:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Preliminary option volume of 26.7M today is 32% below recent average. Calls led puts 16.21M to 10.47M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:46:07 </td>
   <td style="text-align:left;"> $QQQ  Trading on the 15 minute. 81.82% profitability with a Profit Factor of 3.94. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:45:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$374M to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:45:07 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : GMO&amp;#39;s Climate Change Strategy https://www.stck.pro/news/QQQ/20553099 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:45:02 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:44:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:43:57 </td>
   <td style="text-align:left;"> $QQQ % Stocks &amp;gt; 200MA still defending the important 50% zone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:43:56 </td>
   <td style="text-align:left;"> 12/29 $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:41:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 12/30 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:41:19 </td>
   <td style="text-align:left;"> $QQQ Bull flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:40:58 </td>
   <td style="text-align:left;"> Breadth Oscillator flipped long, more improvements here in my models $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:40:45 </td>
   <td style="text-align:left;"> $QQQ FOMO rips the Q’s higher Tomorrow and Friday, 350-400 points higher on the NASDAQ  by weeks end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:38:26 </td>
   <td style="text-align:left;"> $QQQ will never crash!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:35:05 </td>
   <td style="text-align:left;"> $QQQ bloody New Year’s Day is coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:34:47 </td>
   <td style="text-align:left;"> $QQQ 
To the ground!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:32:20 </td>
   <td style="text-align:left;"> $SPY $QQQ Looks like tomorrow will be another pretty flat day then we will open 2022 with a bang next year with investors getting more and more optimistic on the prospects of the US economy in the coming years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:31:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX 

Almost there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:30:59 </td>
   <td style="text-align:left;"> $QQQ right on support let’s see if it holds tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:28:32 </td>
   <td style="text-align:left;"> $SPY $QQQ ….tomorrow we will hit the 71 all time high of the year…buy puts you bears chart says so again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:25:54 </td>
   <td style="text-align:left;"> $QQQ There isn&amp;#39;t a whole lot more at the bottom of this barrel. I think it will take alot to move the entire index beyond this point. Seeing how QQQ is already trying to test its ATH. Hopefully we&amp;#39;ll see a rejection here.
Appl testing 3t market cap again, just a couple dollars shy, and is &amp;quot;technically&amp;quot; overvalued.

Shy of ATH
 Goog 3% 
NFLX 13%
FB 11%
TSLA 13%
MSFT 1% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:23:53 </td>
   <td style="text-align:left;"> $QQQ …lateral movement or flagging higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:23:46 </td>
   <td style="text-align:left;"> $QQQ wrote/sell CALLS that expired today.  Relatively easy day if you wrote CALLs or PUTs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:23:10 </td>
   <td style="text-align:left;"> $QQQ wild after hours, see prints 417ET </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:22:54 </td>
   <td style="text-align:left;"> $QQQ the markets could go sideways befor they fall of the cliff. Ath&amp;#39;s on extremly low volume...wow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:22:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $SMH … what a year has been ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:20:24 </td>
   <td style="text-align:left;"> $SPY $QQQ How are all the 2020/21 investors doing? 
I hope ya&amp;#39;ll made good money these past 2 years. 

Next year gonna be killers market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:19:36 </td>
   <td style="text-align:left;"> $QQQ CDC lowers isolation to 5 days after Delta CEO requested it. Lol the COVID fud is going to run dry soon bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:16:55 </td>
   <td style="text-align:left;"> $QQQ omicron is spreading like crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:16:36 </td>
   <td style="text-align:left;"> $SPY $QQQ the market right now is so weird. all time highs every week but like 90% of the stocks in the index are down lieke 20-80% from their highs. This entire rally is being led by like FAAG and 5 companies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:14:55 </td>
   <td style="text-align:left;"> $QQQ more of this lateral movement rest of the week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:14:22 </td>
   <td style="text-align:left;"> $QQQ NVDA FB AMZN down 1%, what was the counter that kept this unchanged? 🤔🧐 Asking for a friend 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:13:52 </td>
   <td style="text-align:left;"> $QQQ not a whole lot here today, nice bounce after 10 from the cloud/demand zone then just chopped around back into the neutral zone (yellow) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:13:39 </td>
   <td style="text-align:left;"> $HD So we know whats coming here, lots of chasing &amp;amp; window dressing in some of my Fav&amp;#39;s.,  not a big fan of that into EOY since it means we will see Selling in Jan/Feb but what a crazy run

$aapl $msft $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:13:34 </td>
   <td style="text-align:left;"> $RIOT The number one longest and biggest scam in human history just sucked more $ and is currently being wired to the cayman island accounts
$spy $amc $qqq $djia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:12:23 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:10:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $TWTR Twitter Suspends mRNA Inventor Dr. Robert Malone

WEDNESDAY, DEC 29, 2021 - 01:45 PM
After months of providing valuable Covid-19 information that runs counter to the official narrative, Twitter has finally banned Dr. Robert Malone, inventor of mRNA technology.

Malone, who will appear on the Joe Rogan show Thursday according to associate Ed Dowd (one of four contributors to the Malone doctrine), had more than 520,000 followers. He has been an outspoken critic of both mRNA vaccines, as well as the abysmal failures of policymakers worldwide in responding to the pandemic.

 
He was not warned or provided an opportunity to delete any offending tweets - instead he was &amp;quot;just suspended,&amp;quot; Dowd continued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:09:21 </td>
   <td style="text-align:left;"> $QQQ bloody week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:09:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $AAPL 

FOR THOSE THAT KEEP ASKIN, 
YES THE MARKET AKA THE CASINO IS OPEN ON FRIDAY

https://www.marketwatch.com/amp/story/merry-christmas-wall-street-but-theres-no-new-years-day-holiday-for-the-stock-market-this-yearheres-why-11640192753 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:09:16 </td>
   <td style="text-align:left;"> Market wrap:
🔷 US indices closed mixed on the day: 
$DJIA +0.3%, $SPX +0.1%, $QQQ -0.1%
🔷 #Gold (-0.3%) and #WTI (+0.7%) also finished mixed.
🔷 #GBP was the day&amp;#39;s strongest major currency; #JPY was the weakest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:09:06 </td>
   <td style="text-align:left;"> $QQQ: nice little battle going here at R. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:06:29 </td>
   <td style="text-align:left;"> $QQQ If you see those big red candles and think those are weak hands you are an idiot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:05:19 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

Let me guess. Jim Cramer is telling people to buy at ATHs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:04:45 </td>
   <td style="text-align:left;"> $QQQ kinda hilarious at this point lol greedy criminals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:04:28 </td>
   <td style="text-align:left;"> $QQQ y’all still bullish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:03:51 </td>
   <td style="text-align:left;"> $QQQ $SPY ….the crash is coming, the crash is coming…the Bears see the cliff…buy the Puts they say…😝😝😝sheep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:02:35 </td>
   <td style="text-align:left;"> $QQQ $SPY remove FANGs and both will be in sh*t territories. Markets hanging on a thin line, pull back in mega caps and game over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:02:09 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ Model Summary 12/29/2021:
TA - Mean Reversion: BUY
TA - Trend: BUY
Vix Basic: BUY
https://grizzlybulls.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:01:34 </td>
   <td style="text-align:left;"> $QQQ $398 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:01:28 </td>
   <td style="text-align:left;"> $QQQ  closed red!! Victory lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:00:42 </td>
   <td style="text-align:left;"> $QQQ such a pump and dump 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 05:00:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $TSLA $AAPL 

accurate depiction of bears celebrating a -0.25% &amp;quot;crash&amp;quot; after rallying +7.0% from 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:59:44 </td>
   <td style="text-align:left;"> $SPY  powers North as more FOX News contributors who are rabid anti-vaxxers develop a sudden shallow breath via COVID 19.  Who knew that oxygen was still needed to live in these tough times?  Don&amp;#39;t worry, the level of denial and ridicule for others is still alive and well on FOX News. They can&amp;#39;t help themselves. 

Will their overburdened Hospital Staff move them into the Waiting Room and say...

&amp;quot;You will need to wait for a room to open up as we are full and since you are not vaccinated, take a number...Oh well. &amp;quot;

Stay safe all.

Millions affected and millions made in our wonderful markets!  $$$$$

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:57:59 </td>
   <td style="text-align:left;"> $SPY $QQQ work harder bears but they’re doing this to kill both premiums and plus premiums are still expensive 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:57:48 </td>
   <td style="text-align:left;"> $QQQ looking fugly on the daily timeframe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:57:42 </td>
   <td style="text-align:left;"> $BB $SPY $QQQ $DIA 

IRS: we will tax all capital gains 

My portfolio: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:55:40 </td>
   <td style="text-align:left;"> $SPY lets close at $478 $QQQ $402 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:55:39 </td>
   <td style="text-align:left;"> $SPY Scary:

2022 will be the year of both the empta verse and hyperinflation . Oh, plus, growth cycle to bear side, don&amp;#39;t market out that fact.

What IN THE WORLD is espy af ATHs.

Yikes 

$QQQ is about to </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:55:31 </td>
   <td style="text-align:left;"> $DIA $BA $QQQ elevator back in service </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:55:13 </td>
   <td style="text-align:left;"> $QQQ shooting star on 1 month? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:55:06 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM the real santa rally starts NOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:54:37 </td>
   <td style="text-align:left;"> $QQQ sell everything but puts for Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:53:57 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:53:13 </td>
   <td style="text-align:left;"> $SPY $QQQ Lets gooooo markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:52:16 </td>
   <td style="text-align:left;"> $NVDA $305+ tomorrow. Easy.

$SPY $QQQ $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:52:00 </td>
   <td style="text-align:left;"> $QQQ outperforms 80% of all stocks! https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:51:53 </td>
   <td style="text-align:left;"> $NQ_F $QQQ $VXX #SP500 #stockmarket #markets #equitymarket #investing #equities #Futures #Trading #swingtrading #marketforecast Price compression at the highs within a bull trend, new all time highs in focus.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:51:30 </td>
   <td style="text-align:left;"> ICYMI, my latest:  &amp;quot;Will Santa Claus Rally Bring New Highs For Nasdaq 100?&amp;quot; --&amp;gt; https://www.seeitmarket.com/will-santa-claus-rally-bring-new-highs-for-nasdaq-100-qqq/

#IBDPartner  @InvestorsBusinessDaily @MarketSmith  $QQQ $XLK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:51:26 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA where do thots come from and I ain’t talkin bout the mind ya doinks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:50:59 </td>
   <td style="text-align:left;"> $QQQ $SPY hello bull flag.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:50:53 </td>
   <td style="text-align:left;"> $SPY $QQQ compete fumes on 1/10th volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:50:37 </td>
   <td style="text-align:left;"> $QQQ tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:49:54 </td>
   <td style="text-align:left;"> $SPY $QQQ buy more puts bears, right now! It&amp;#39;s coming down into close. Buy buy buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:48:55 </td>
   <td style="text-align:left;"> $SPY $QQQ a faker market we will.never see again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:48:53 </td>
   <td style="text-align:left;"> $SPY $QQQ witnessing the death of social security </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:48:33 </td>
   <td style="text-align:left;"> $SPY $QQQ stay mad bears lol we both got killed with premiums it’s ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:46:48 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

A green close today is a bearish sentiment in my opinion... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:46:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:46:02 </td>
   <td style="text-align:left;"> $QQQ wants to go lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:45:37 </td>
   <td style="text-align:left;"> $SPY $QQQ …only thing crashing is the Bears accounts…Bears are sheep just keep them dangling in the wind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:45:33 </td>
   <td style="text-align:left;"> $SPY $DIA $DJIA $QQQ  1 million cases/ day next week, most likely 

WHO chief worried about ‘tsunami’ of omicron, delta cases

https://www.wsav.com/news/coronavirus/who-covid-cases-up-11-globally-last-week-omicron-risk-high/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:45:27 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ so let’s just prop up the index to make everything look merry during the holidays, while underneath the surface everything is getting rocked again today. Seriously can’t make this stuff up if you tried </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:44:25 </td>
   <td style="text-align:left;"> $SPY $QQQ ofcourse calls will close here for profit booking but I&amp;#39;m super bullish for next 2 days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:43:51 </td>
   <td style="text-align:left;"> $QQQ 2 more minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:43:48 </td>
   <td style="text-align:left;"> $AMZN - $QQQ needs to up another 1% for us to just turn green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:43:35 </td>
   <td style="text-align:left;"> $SPY $QQQ …bears appear to be the true sheep…hey when is that crash coming again (the charts never wrong)…keep buying those Puts please…Lets go Bears!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:43:24 </td>
   <td style="text-align:left;"> $QQQ swing idea tgt 402.94 stop 401.86. 1.5 weeks out expiry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:43:03 </td>
   <td style="text-align:left;"> $QQQ how many bears committed suicide today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:41:41 </td>
   <td style="text-align:left;"> $SPY I licked my wounds on my short puts  after this broke the down trend , swapped to long &amp;amp; loaded up on calls across all 3 accounts on these $QQQ $SPY  $AAPL &amp;amp; $SBUX  I expect a strong close to week .. way up right now 👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:41:08 </td>
   <td style="text-align:left;"> $QQQ not saying it will go to $410 but anything is possible u know how qqq runs it can literally run 10 points in a day ;)  but Goodluck y’all trade safe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:40:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA S&amp;amp;P 500 (SPY) Technical Analysis, Forecast, and Trade Ideas: 
https://www.youtube.com/watch?v=u5M2GdO0ysM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:40:45 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY market crash coming... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:39:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AMZN $NVDA Christmas was four days ago guys, Santa ain&amp;#39;t making trip back from north pole to hand out more tendies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:39:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $AAPL $TSLA 

bears still spamming about omicron after institutionals stopped giving a shit almost 5 weeks ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:39:21 </td>
   <td style="text-align:left;"> $QQQ pushhhhhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:38:37 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM all options are literally fucking dead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:38:20 </td>
   <td style="text-align:left;"> $BTC.X $DIA $NASDAQ $QQQ Big S&amp;amp;P 500 Bear Market Case Sees Inflation Finally Eating Everything

https://www.bloomberg.com/news/articles/2021-12-29/big-s-p-500-bear-case-sees-inflation-finally-eating-everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:38:17 </td>
   <td style="text-align:left;"> $QQQ Final day trade absolutely fcukin rippin ... 

Hope you dum bear fux are enjoying yourselves ... Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:38:16 </td>
   <td style="text-align:left;"> $SHOP $qqq going off, this is about to join the party. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:37:40 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ We have already reached the moon 🌝
next stop, MARS!! ☄️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:37:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX oh noes, what happened, bears lose ramen money again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:36:36 </td>
   <td style="text-align:left;"> What a finish!!!!! $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:36:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX 

bears were so confident this morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:34:59 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ $TSLA $AMZN it’s coming… $SPY $QQQ $TSLA went red to green since my first message and spy has gone $2+ since. $QQQ same </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:34:04 </td>
   <td style="text-align:left;"> $QQQ 403? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:33:42 </td>
   <td style="text-align:left;"> $NVDA where are all the bulls from yesterday now? no more $QQQ rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:33:37 </td>
   <td style="text-align:left;"> $QQQ lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:28:08 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $NASDAQ NY Obliterates Single-Day Case Record With Nearly 70K New Positives; Hochul Warns Worst Yet to Come

https://www.nbcnewyork.com/news/coronavirus/ny-obliterates-single-day-covid-case-record-with-nearly-70000-new-positives/3471191/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:27:55 </td>
   <td style="text-align:left;"> $SPY lol pushing it above $478 before close perfect set up for $480-482 tmw and yes $QQQ held above $400 lol time to end the week $405-408 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:27:12 </td>
   <td style="text-align:left;"> $SPY At least this is up….
Don’t know what the fuck is wrong with these two $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:24:42 </td>
   <td style="text-align:left;"> The simple fact is that it&amp;#39;s very hard to make money being bearish. You get very few opportunities to actually make money in the market. 

Meanwhile, the easy money is made on the long side.

The market has been in an uptrend for yearssss. Very few down moves, and when they come, they are very quick.  

The market spends the vast majority of its time heading higher. That&amp;#39;s just a fact. You cannot argue that. And if you do, it&amp;#39;s because there&amp;#39;s something wrong with how you&amp;#39;re viewing the market. 

If you disagree, then maybe you&amp;#39;ve been looking at your charts upside down ;)

$SPX $SPY $QQQ $DIA $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:24:35 </td>
   <td style="text-align:left;"> $QQQ 420 before any selloff, just mortgage the house if u wanna retire for free </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:24:03 </td>
   <td style="text-align:left;"> $QQQ $SPY breaking news right before close.  Can&amp;#39;t say more. yes I could be a clown. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:23:14 </td>
   <td style="text-align:left;"> latex5f3e2285815833159fb40d1cd2a135e9Gdx easy buy
$BTC.X easy sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:22:56 </td>
   <td style="text-align:left;"> $NVDA LAGGING big time here behind $SPY and $QQQ. $303 is on the table! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:22:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA tomorrow&amp;#39;s gonna&amp;#39; be redder (more red? 🤔) than your mother&amp;#39;s toilet paper 27 hours after the egg falls out...

You&amp;#39;re welcome in advance...  

ps...  I&amp;#39;m probably right, but there&amp;#39;s an outside chance I&amp;#39;m wrong..  There&amp;#39;s also an outside chance that I&amp;#39;m your father, but who&amp;#39;s keeping trach eh&amp;#39;? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:22:45 </td>
   <td style="text-align:left;"> $SPY $QQQ we going for a stock market monopoly with only 10 or so stocks making up the market? That&amp;#39;ll be fun... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:22:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL $TWTR  
 
I dont know about you, but Im feeling the investment landscape for 2022, ooh ooh! Everything will be alright if I do me and you do youuuuuu!!! 
 
You dont know about me, but I bet you want toooo. Everything will be alright if, if we just keep investing iinn 2022! 
 
(Take his man card, please ;-) ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:21:26 </td>
   <td style="text-align:left;"> $SPY One last pump before the big drop. I&amp;#39;m bullish but this is ridiculous. Total manipulation to destroy retail traders. Tread lightly at these levels. I have call LEAPs but am buying short term puts for the drop. Should be nasty. $QQQ $NDAQ $DIA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:21:25 </td>
   <td style="text-align:left;"> $VIX Special coverage on the Vix Crashing 

Due to @HollywoodWolf777 our futures trader has accumulated more than 1000 puts on the Vix   $QQQ $DIA $NDX $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:18:26 </td>
   <td style="text-align:left;"> $QQQ $SPY …green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:17:09 </td>
   <td style="text-align:left;"> $FUBO full dump once $ROKU and $nflx roll over with $spy $qqq. puts to 14.58 then 14.13. Sorry if you listened to pumpers. They bottom feed cheap calls and leave you out to dry. At least the others in the sector have supports that actually hold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:14:05 </td>
   <td style="text-align:left;"> $IWM “rob the poor to feed the rich, rob the poor to feed the rich…” sing it with me! 🎶 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:13:28 </td>
   <td style="text-align:left;"> $QQQ short 401.44 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:10:51 </td>
   <td style="text-align:left;"> McClellan Oscillator: The Best Market Timing Indicator?

$SPY $QQQ $DIA $IWM $STUDY

https://www.chartlearning.com/2021/11/what-is-the-mcclellan-oscillator-indicator.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:09:35 </td>
   <td style="text-align:left;"> $SPY The Nasdaq must be afk or sum 🤦🏽‍♂️ $QQQ RALLY ALREADY STOP PLAYING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:09:34 </td>
   <td style="text-align:left;"> $QQQ breaking news right before market close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:09:18 </td>
   <td style="text-align:left;"> $KMX coming off bottom after a great ER last week and selloff. Car max.   $QQQ. $TSLA. $RIVN. $IBM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:09:10 </td>
   <td style="text-align:left;"> Remember this? Finom Group members do: 
 
&amp;quot;If you bought the open with just 7 trading days left in December over the last 23 years (using stop loss), you would have generated a profit the next day ~95% of the time.  
 
This year Dec 23rd marks TDLIM (7 trading days left). &amp;quot; 
 
Remember, while you&amp;#39;re searching for reasons why this time will be different, know that it is always different, but the market is an expression of human behavior, which is rather constant.  
 
$SPX $SPY $QQQ $UVXY $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:07:56 </td>
   <td style="text-align:left;"> $AAPL I wouldn’t be surprise if media/news come out about potential new year attack on USA soil $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:05:44 </td>
   <td style="text-align:left;"> ETF Sentiment: $QQQ is the #2 ETF that institutions are trading with 25.0K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:04:57 </td>
   <td style="text-align:left;"> $SPY $QQQ the push higher the remainder of this week could be intense. Many Biotech short coverings should ignite soon, $IBB $XBI $LABU nice volume candles to start the fun! Plenty more where that came from? Ofcourse! 🔥🔥 The M&amp;amp;A activity in the Biospace during Q1 will only add further fuel towards its reversal upward. January IS Biotech folks 😉😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:04:53 </td>
   <td style="text-align:left;"> $QQQ one word….Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:04:47 </td>
   <td style="text-align:left;"> $QQQ $SPY 
Y’all need to regain your leadership </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:02:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM theta burn day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 04:00:28 </td>
   <td style="text-align:left;"> $SPY $QQQ... Power Hour!!! 💰🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 03:53:14 </td>
   <td style="text-align:left;"> $NVDA every institution and retailers want to load this for 2022  and seeing $1Trillion in a month it seems $qqq $spy $tsla $GOOG  road is cleared </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 03:51:52 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 03:51:12 </td>
   <td style="text-align:left;"> $QQQ Me going over todays price action vs todays expiring calls and puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 03:50:25 </td>
   <td style="text-align:left;"> Peter Lynch Echoes Michael Burry’s Warning About Index Investments

Read: https://www.channelchek.com/news-channel/Peter_Lynch_Echoes_Michael_Burrys_Warning_About_Index_Investments

$SPY $QQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 03:50:05 </td>
   <td style="text-align:left;"> $QQQ 
EVERYONE I NEED HELP I WANT TO DAY TRADE THIS WITH OPTIONS. THOTS? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-30 03:48:45 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 14:14:10 </td>
   <td style="text-align:left;"> $AAPL $TSLA 

FUTES RIPPING 😆🖕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 14:03:29 </td>
   <td style="text-align:left;"> $AAPL Simulated 182.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 14:00:35 </td>
   <td style="text-align:left;"> $AAPL I hope it goes up 2% so I can get some puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 13:54:01 </td>
   <td style="text-align:left;"> @GoodieGood $tsla dip into earnings then rip $aapl rip into earnings then dip heard it here first 🥦💨😮‍💨😴✌🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 13:46:31 </td>
   <td style="text-align:left;"> Here&amp;#39;s some option&amp;#39;s overview for high volume trades. $AMD $AAPL $MSFT $MU $SNOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 13:27:04 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA  I have a 2k/day quota that I have to meet day trading with the occasional 10k/day when the market is volatile enough. My daily driver is a Tesla, occasional driver Lamborghini, just moved into a massive new place in NY and I&amp;#39;m single. 
If I can do it, YOU can do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 13:21:08 </td>
   <td style="text-align:left;"> $AAPL $200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 13:19:32 </td>
   <td style="text-align:left;"> $AAPL way oversold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 13:19:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 7.00. This indicates good health for $AAPL. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 13:12:19 </td>
   <td style="text-align:left;"> $PTON I mean $AAPL paid billions for a dogshit headphone company.  Might be some value here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 13:11:43 </td>
   <td style="text-align:left;"> $AAPL Still bullish on long Intraday 180 calls for Dec. 31st </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 13:10:51 </td>
   <td style="text-align:left;"> $AAPL ❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:52:25 </td>
   <td style="text-align:left;"> $SPY $AAPL im
Ready 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:50:11 </td>
   <td style="text-align:left;"> Apple trying to retain talent with unusual $180,000 bonuses. $AAPL.
https://bit.ly/3pD84tC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:50:07 </td>
   <td style="text-align:left;"> $AAPL I checked my local Costco every Apple product is oos! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:48:51 </td>
   <td style="text-align:left;"> Apple (AAPL) puts Foxconn Technology Group&amp;#39;s (HNHPF) India plant on probation. $AAPL.
https://bit.ly/3pD84tC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:46:36 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ i just apply for cash account and option from help from holly , y’all get ready 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:35:43 </td>
   <td style="text-align:left;"> $AAPL Bullish pattern forming today. Follow for more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:33:06 </td>
   <td style="text-align:left;"> $AAPL, easistet money ever 2024 120 puts….. they will print many times over imo… 
 
 wait for the rug pull on this market…. 25-50 companies have bloated themselves to larger bubble than 01…. during a near economic collapse of productivity with covid…. 👍 👌  
 
see you in 2024 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:30:59 </td>
   <td style="text-align:left;"> $AAPL gonna hit $200 on 14th Jan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:19:52 </td>
   <td style="text-align:left;"> $SPY $AAPL A Bogandoff twin has died. What effect will this have on stock and crypto markets? I predict wide scale uncertainty and bearish on crypto as 1/2 of its creator is no more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 12:03:02 </td>
   <td style="text-align:left;"> $UPST $TSLA $AAPL 
Short selling has become normalized but how much of it is legit/legal?  If you have major hedge funds and institutional investors shorting a stock they obviously have major pull and can pull the stock down.  This is what people mean when they say &amp;quot;market manipulation&amp;quot;.  And the ones doing this have so much power that it&amp;#39;s very unlikely for them to get caught.  I think this will be dealt with behind the scenes as not to affect the market because if the true nature of manipulation was made public it would scare away many retail investors.  Stocks will rise in 2022. Corruption eventually always gets exposed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:57:51 </td>
   <td style="text-align:left;"> $AAPL Bloomberg really has an axe to grind with Apple. Now they believe the market will fall each time the stock reaches a new Trillion market cap level, yea, so maybe tomorrow, or next week or eventually. Bloomberg nutjobs.
https://youtu.be/kLbiq0VIT9w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:57:36 </td>
   <td style="text-align:left;"> $AAPL $AMC $AMD Print and Post in your trading station so you have a constant reminder. Enjoy the Stacks!🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:55:48 </td>
   <td style="text-align:left;"> $AAPL $AMZN $NAKD Print and Post in your trading station as a reminder!
Happy Stacking! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:53:47 </td>
   <td style="text-align:left;"> $AAPL Apple To Release Special Beats Studio Buds To Celebrate The &amp;#39;Year Of The Tiger&amp;#39; 

https://newsfilter.io/a/431a278b7c3efe8ea75d775c1f8fe637 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:53:34 </td>
   <td style="text-align:left;"> $EMAN $AAPL 

&amp;quot;US firm eMagin is also working on MicroOLED FMM with Apple&amp;quot;

Going to go to blue sky territory soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:51:44 </td>
   <td style="text-align:left;"> McClellan Oscillator: The Best Market Timing Indicator?

$TSLA $MRNA $AAPL $FUBO $GME 

https://www.chartlearning.com/2021/11/what-is-the-mcclellan-oscillator-indicator.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:48:26 </td>
   <td style="text-align:left;"> $AAPL I guess we are looking at 3 trillion dollars mark next week and not this week. We have tomm for any movement going up and not Friday for the weekly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:41:15 </td>
   <td style="text-align:left;"> Apple (AAPL) puts Foxconn Technology Group&amp;#39;s (HNHPF) India plant on probation. $AAPL.
https://www.tiktok.com/@stockcryptotok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:34:23 </td>
   <td style="text-align:left;"> $AAPL surprised Apple hasn’t taken over $PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:33:03 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-29 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=LZ12BXDRLVc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:28:39 </td>
   <td style="text-align:left;"> $AAPL - TFC flow is not showing much weakness into the year end after back to back days of consolidation. 
https://thefinancial.cloud/join/?ref=haseebhack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:26:57 </td>
   <td style="text-align:left;"> $MSFT $AAPL $SPY $BRK.B 

FINKLE IS EINHORN! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:26:52 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #1 stock that institutions are trading with 63.8K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:21:28 </td>
   <td style="text-align:left;"> $AAPL 
🍏🎄
https://www.cnbc.com/amp/2021/12/29/apple-ditched-intel-and-it-paid-off.html?__source=instagram%7Cmain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:21:17 </td>
   <td style="text-align:left;"> $AABB $SPY $TSLA $AAPL $MSFT  What does this INDICATE? The Short% wen&amp;#39;t from 50% to 35% to 54% to 16% to 4% . No more shares available to short. Paid bashers flooding the board and the global exchange just launched. LOADING ZONE! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:21:16 </td>
   <td style="text-align:left;"> $RIDE $GOEV $WKHS will merge and create an EVJV funded by $AAPL. Manufacturing by Foxconn to take the Apple car and Apple truck public….

Licenses…tech…battery production and supply agreement….fully “moated” new EV entrant with zero legacy interference….

Watch!

Make your own decisions! Do your own DD! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:19:06 </td>
   <td style="text-align:left;"> $AAPL $NAKD $DIS Like and Follow if you will achieve this goal! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:15:31 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $FB Praying for a red day tomorrow as I&amp;#39;ve just gone in heavy. Fill or kill, or kill myself. 
 
Just the desperating millennials need now to get a house down payment. I already got screwed out of the 2021 season by Bill FKing Ackman, and now will have to pay 20% extra. 
 
😿🤞🏻🙏🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:15:05 </td>
   <td style="text-align:left;"> $AABB $SPY $TSLA $AAPL $MSFT New Exchange and massive paid bashing! You know what that means 1000% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:14:37 </td>
   <td style="text-align:left;"> $JASMY.X I’m cash out my $SOXL $AAPL  yesterday, market definitely in correction mode.. 
cash is king … I will add more $JASMY.X every other day or 2 …
No sweat about red… 
Just common sense that Japan legally accepting $JASMY.X , so no way this is fall , unless else where change… 
Stay strong ,, fuck the  clown 🤡/ FUD, cry babies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:13:21 </td>
   <td style="text-align:left;"> $AAPL next target is $181 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:05:42 </td>
   <td style="text-align:left;"> $AAPL i d love $182 on friday so the puts on my wishlist are cheaper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:04:26 </td>
   <td style="text-align:left;"> Top Sell Flow Money - 12.29.2021 - $AAPL $TSLA $IEF $FXI via Super Stocks App </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:03:00 </td>
   <td style="text-align:left;"> $AAPL is currently trading near its 52 week high, which is a good sign. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:02:26 </td>
   <td style="text-align:left;"> $AAPL Simulated 182.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:00:32 </td>
   <td style="text-align:left;"> $AAPL watching for the flag break to see ath by end of week.

Link in bio for free discord where i provide daily and pre mkt analysis with price targets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 11:00:20 </td>
   <td style="text-align:left;"> $AAPL  CnH? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:58:38 </td>
   <td style="text-align:left;"> $AAPL sorry to say this, but who ever have puts and shorted will be printing tomorrow big time..!!!  Unfortunately its going to be RED.  GL to all..!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:56:19 </td>
   <td style="text-align:left;"> $AAPL I am bullish on Apple long term, but I just don’t trust these cocksuckers on WallStreet. 3 trill hype so they can unload at the top before Friday’s dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:43:56 </td>
   <td style="text-align:left;"> $AAPL below 175 this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:39:35 </td>
   <td style="text-align:left;"> $AAPL 3 Trillion Market Cap Before 2022? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:33:54 </td>
   <td style="text-align:left;"> $AAPL $300 in 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:32:36 </td>
   <td style="text-align:left;"> $MVIS the only way they getting projection like that is $MVIS what do you say $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:29:12 </td>
   <td style="text-align:left;"> $AAPL why short a stock everyone knows that’s just dumb! Market always uptrending you can’t bet against the American economy!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:28:38 </td>
   <td style="text-align:left;"> $SPY WHAT IF I TOLD U THAT FOR THE PAST 6 TRADING SESSIONS A CRIMINAL BID SPOOFING MANIPULATING CITADEL SCAM ALGORITHM IS MANIPULATING SHARE PRICE, STEALING BILLIONS IN OPTIONS PREMIUM, AND PROPPING MARKETS FOR A MASSIVE CRASH THAT WILL BANKRUPT THE MIDDLE CLASS, ONLY TO ENRICH THE 1%? $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:27:36 </td>
   <td style="text-align:left;"> $AAPL https://rumble.com/vrk7op-trump-releases-devastating-new-video-exposing-bidens-total-failure-on-covid.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:22:08 </td>
   <td style="text-align:left;"> $AAPL 175 before 3 trill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:16:41 </td>
   <td style="text-align:left;"> $SPY shorts are hunting the market now, most tickers are cut down to size already, only few juggernauts left supporting indexes, GAME OVER $aapl  $msft $tsla $nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:14:48 </td>
   <td style="text-align:left;"> $AAPL 3 trillion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:12:42 </td>
   <td style="text-align:left;"> $AAPL ➡️LCLP 50% up in 2 days and just the beginning https://drive.google.com/file/d/1ZkjjuQMGsf5sU9LhicQR3rDl0iPK72En/view </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 10:06:07 </td>
   <td style="text-align:left;"> $AAPL buy more apple stock
https://shop.robindrip.com/collections/aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:59:38 </td>
   <td style="text-align:left;"> $AAPL look at the volume on the S&amp;amp;p, tiny </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:59:05 </td>
   <td style="text-align:left;"> $AAPL it’s over for this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:57:19 </td>
   <td style="text-align:left;"> $AAPL Apple will hit $183! Santa said sooooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:50:33 </td>
   <td style="text-align:left;"> $SNIPF Just imagine when there are screens everywhere with advertisements. Digital Marketing is not even 1% where it will be in 10yrs $SPY $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:48:48 </td>
   <td style="text-align:left;"> Stocks Rise On December 29 But Trouble Lies Beneath $AAPL $MSFT $IWM $NDX $SPX $DJI https://talkmarkets.com/content/stocks--equities/stocks-rise-on-december-29-but-trouble-lies-beneath?post=339525 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:44:46 </td>
   <td style="text-align:left;"> $AAPL desperate when you&amp;#39;re posting bullish adds about fridge deals 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:40:37 </td>
   <td style="text-align:left;"> $AAPL Apples got unfinished 3 trillion business to hit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:37:15 </td>
   <td style="text-align:left;"> $AAPL $QQQ latex5e211dbe608f5ed72e115abf8d236adfTSLA - PUT IDEAS ✅
$SE - PUT IDEAS ✅

CONGRATS TO OUR FOLLOWERS &amp;amp; SUBSCRIBERS 🥂
FOLLOW ME HERE FOR MORE TRADE IDEAS 👈🏻 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:33:10 </td>
   <td style="text-align:left;"> $AAPL load uppp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:29:39 </td>
   <td style="text-align:left;"> $AAPL oh no the world is ending . It’s down 50 cents after hours 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:23:22 </td>
   <td style="text-align:left;"> $AAPL Once AAPL corrects like the rest of the Market, you are looking at a 35 Dollar stock here within 4 months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:21:49 </td>
   <td style="text-align:left;"> $AAPL $SPY here&amp;#39;s your &amp;quot;futures rip&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:19:14 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA  You drank the new generation future just in two years cause you wanted your 401k grow up non-stop. Want to feel safe and comfy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:07:37 </td>
   <td style="text-align:left;"> $QQQ $FB $AAPL https://www.bloomberg.com/news/articles/2021-12-28/apple-pays-unusual-180-000-bonuses-to-retain-engineering-talent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:02:20 </td>
   <td style="text-align:left;"> $AAPL Simulated 182.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:02:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-29 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=LZ12BXDRLVc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 09:02:00 </td>
   <td style="text-align:left;"> $AAPL has a Profit Margin of 25.88%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:50:22 </td>
   <td style="text-align:left;"> $AAPL always pays to be a BULL 🐃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:49:56 </td>
   <td style="text-align:left;"> $AAPL if you bought calls today, tomorrow going to be a good day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:49:33 </td>
   <td style="text-align:left;"> $AAPL this is hitting 3 trillion tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:49:09 </td>
   <td style="text-align:left;"> $AAPL I’m blocking every negative bear on here. You’re anti Apple negativity is boring. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:47:04 </td>
   <td style="text-align:left;"> Risk-adjusted landscape for Apple( $AAPL ), Mosaic(… https://www.macroaxis.com/invest/marketRiskAndReturn?s=AAPL,MOS,FMC,THC,L,GOOG #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:46:04 </td>
   <td style="text-align:left;"> $AAPL $SPY I can&amp;#39;t wait for Russia sanctions to kick off. Specifically that part where they stop selling them  smartphones. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:41:42 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:39:41 </td>
   <td style="text-align:left;"> $AAPL 165 eow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:36:09 </td>
   <td style="text-align:left;"> $SPY DRAIN THE SWAMP!!!$IWM $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:34:00 </td>
   <td style="text-align:left;"> $AAPL dark pool is 105p 3/1/21 … GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:32:27 </td>
   <td style="text-align:left;"> $AAPL Below $179 and this pukes 🤮 up its lunch all over the place 🤬😆😆😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:30:50 </td>
   <td style="text-align:left;"> $AAPL Every single vocal bear you’ve seen on this board this year has ended up losing money and eventually stopped posting. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:28:05 </td>
   <td style="text-align:left;"> $AAPL so glad I stopped holding options theta can be a bish scalp your way to victory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:27:37 </td>
   <td style="text-align:left;"> $AAPL Tomorrow those calls are going to eat a dickup and hiccup 😳😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:18:27 </td>
   <td style="text-align:left;"> $AAPL noobs bought 179-180+ they got trap .. pros bought 150-160 and under . Feel the drop soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:15:10 </td>
   <td style="text-align:left;"> $AAPL Today was the last day (still is till 8 PM est) for the &amp;quot;wash sale&amp;quot; for the tax reasons. Mkt should reward few good tech names like this and $FB next 2 days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:12:19 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 08:07:21 </td>
   <td style="text-align:left;"> $AAPL $NAKD $AMZN Are YOU too? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:58:53 </td>
   <td style="text-align:left;"> The market is still in no competition with $TSLA $AAPL 🙏🏾. Stocks only go up and down 💪🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:55:02 </td>
   <td style="text-align:left;"> $AAPL when is the next offering? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:54:44 </td>
   <td style="text-align:left;"> $AAPL tomorrow I’m gonna go put a down payment on a new house bc you guys wanna pump apple over no news , the bears gonna pump yo ass tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:53:53 </td>
   <td style="text-align:left;"> $AAPL time to eat our hairy ass tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:53:46 </td>
   <td style="text-align:left;"> $AAPL resistance resistance resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:53:20 </td>
   <td style="text-align:left;"> $AAPL ➡️ Quantum Artificial Intelligence, The Breakthrough? Quantum Ai
◢ https://youtu.be/VFuElWbRuHM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:53:03 </td>
   <td style="text-align:left;"> $AAPL good luck losing money tomorrow, call me if you need a loan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:53:03 </td>
   <td style="text-align:left;"> $AAPL time to eat hairy azzz tomrrow get ready for poundage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:52:28 </td>
   <td style="text-align:left;"> $AAPL get ready for poundage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:52:27 </td>
   <td style="text-align:left;"> $AAPL tomorrow red bc u guys failed to pump it today sad world, hopefully it goes to $100 and then back to $200 in one day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:52:05 </td>
   <td style="text-align:left;"> $SPY latex4819668a70635159cc3660117d820ad9BABA - 72% call flow
$MU - 93% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:48:43 </td>
   <td style="text-align:left;"> $AAPL back above $180 she goes tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:48:42 </td>
   <td style="text-align:left;"> $BILI 3 year return is similar to $AAPL things are more normalized nowadays. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:47:24 </td>
   <td style="text-align:left;"> $AAPL down she blows! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:47:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : The Dow&amp;#39;s New High Is Hiding This Key Market Rotation https://www.stck.pro/news/AAPL/20558487 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:47:01 </td>
   <td style="text-align:left;"> $AAPL 

Damn too many trolls here talking different things .. not related to this stock.

Plus lots of trolls trying to use pointless talk about puts ..

I am going to block all of them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:46:51 </td>
   <td style="text-align:left;"> $AAPL All intelligent investing is value investing. Acquiring more that you are paying for. You must value the business in order to value the stock.” Here is the link for Pre-IPO acces.Good Luck.Investors.be4ipo.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:46:11 </td>
   <td style="text-align:left;"> $AAPL Bears have an actual medical problem. The medical term is “Self inflicted pain syndrome.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:43:08 </td>
   <td style="text-align:left;"> $AAPL NEWS - AAPL Warns Foxconn India After Protests: 
https://www.youtube.com/watch?v=036Nyfvm-Gc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:33:06 </td>
   <td style="text-align:left;"> $TSLA nothing can bring tesla down they’ve been shorting us since ipo And we overcame. 2T by eoy 2022 and we will overtake $AAPL by 2023 .  Fuck the haters 🦍 in elon mush we trust </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:28:36 </td>
   <td style="text-align:left;"> $AAPL $NAKD $DIS Its been one hell of a year of gains at OP. Time to start planning the next OP Event! Are y’all ready? 
Click the follow button if you want the invite!
Cheers to 2022 and the continued alert play success!

https://youtu.be/EcPAj7Ljxt8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:20:31 </td>
   <td style="text-align:left;"> $AAPL deep Red Market tomorrow I mean don&amp;#39;t need to b a rocket scientist 5 days in row green! Nas could b green thou? Who da fuck knows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:20:24 </td>
   <td style="text-align:left;"> Nvidia stands to benefit from the metaverse, says DCLA&amp;#39;s Sarat Sethi $nvda $amd $aapl $fb https://www.cnbc.com/video/2021/12/29/nvidia-stands-to-benefit-from-the-metaverse-says-dclas-sarat-sethi.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:08:10 </td>
   <td style="text-align:left;"> $AAPL Simulated 182.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:07:37 </td>
   <td style="text-align:left;"> Stocks Rise On December 29 But Trouble Lies Beneath https://mottcapitalmanagement.com/stocks-rise-on-december-29-but-trouble-lies-beneath/ $aapl $msft $dia $qqq $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 07:00:21 </td>
   <td style="text-align:left;"> latex088de7a3b4b9615155934392c5d642cbNIO 321k (75% call/25% put)
$AAPL 979k (71% call/29% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:57:21 </td>
   <td style="text-align:left;"> $ALPP hardly any investors are patient in the market sadly. Small cap stocks have been out of favour for 9 months and have been massively sold off lately because they have not risen. Even Alpine 4 which has a great future and now trades at 52 week lows despite nothing changing in the company.

People are instead buying $AAPL, $NVDA which have had good years and are having a run up. I never buy what&amp;#39;s going up. I hang around on companies I believe in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:55:15 </td>
   <td style="text-align:left;"> $AAPL Sinking after hours..

APPLE INC
Close
$179.38

Presently 
Bid  ARCX
179.16 x 1
Ask  XNMS
179.19 x 13

Volume
62,248,176 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:53:09 </td>
   <td style="text-align:left;"> $AAPL I see a double top. Looks bearish to me. PT around 173 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:51:14 </td>
   <td style="text-align:left;"> $SPY ALL SECTORS HAVE ALREADY ENTERED BEAR MARKET TERRITORY. MM , CITADEL, FED, WALL ST ARE ALL PROPPING UP THE DOG SHITTER FAANG OVERBOUGHT, OVERVALUED FRAUD STOCKS $MSFT $TSLA $AAPL LIKE IN THE DOT COM BUBBLE MEANWHILE SMALL CAPS ARE GETTING OBLITERATED. WHEN THEY POP THIS PONZI BUBBLE JUST PRAY YOU AREN&amp;#39;T CAUGHT UNDER IT. CLOSE UR CALLS IMMEDIETELY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:49:08 </td>
   <td style="text-align:left;"> $AAPL huge volume on calls
But man I can’t see this going 182+ by Friday lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:31:41 </td>
   <td style="text-align:left;"> $AAPL I just want to get out in front of this, as I&amp;#39;ll be travelling the next week.
Ghislaine Maxwell did not commit suicide.

&amp;quot;Ghislaine Maxwell Found Guilty In Sex Abuse Trial&amp;quot;

And I&amp;#39;m short AAPL @ 179.65 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:26:57 </td>
   <td style="text-align:left;"> $AAPL looking weak I’m looking to short tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:26:01 </td>
   <td style="text-align:left;"> $AAPL $NAKD $TSLA Make sure you check out this episode of WNW!

https://youtu.be/Bot0p2x1Eko </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:25:04 </td>
   <td style="text-align:left;"> $AAPL  🤤🧐🤓
Apple ditched Intel, and it paid off https://www.cnbc.com/2021/12/29/apple-ditched-intel-and-it-paid-off.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:24:30 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $1,679,398 call block traded with $60.0 strike expiring on 2024-01-19. Via: https://www.stockgrid.io/optionsflowcumulativestats/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:23:07 </td>
   <td style="text-align:left;"> $AAPL Tomorrow is the last day to settle tax losses 😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:23:02 </td>
   <td style="text-align:left;"> $AAPL $NVDA $MSFT $TSLA $FB 

No shit Ghislaine Macwell was guilty, but I want to know all of the other pedophiles she was guilty with. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:12:52 </td>
   <td style="text-align:left;"> $AAPL thank you AAPL for a nice year. 2022 should be great too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:09:28 </td>
   <td style="text-align:left;"> $AAPL fuuk this POS today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 06:07:01 </td>
   <td style="text-align:left;"> $AAPL back to </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:55:25 </td>
   <td style="text-align:left;"> $AAPL Simulated 182.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:54:51 </td>
   <td style="text-align:left;"> $AAPL 180 call for Jan 14th . Let’s ride this wave 🌊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:54:25 </td>
   <td style="text-align:left;"> $AAPL short puts, short calls...both expiring Friday. Made money on both today. Hopefully, they expire worthless Friday, but I can guarantee this. By Friday afternoon if I have to cover (buy back) either of them, the time premium will be close to nothing. Love selling options!!!! GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:49:04 </td>
   <td style="text-align:left;"> $AAPL  
Best company ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:48:26 </td>
   <td style="text-align:left;"> $AAPL made 3$ today fuck ya WTF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:48:22 </td>
   <td style="text-align:left;"> Most Active Options $AAPL $TSLA $NVDA $AMD $MU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:47:29 </td>
   <td style="text-align:left;"> $AAPL I love when people think their opinions on here have any relevance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:46:14 </td>
   <td style="text-align:left;"> $TQQQ this week tech bag holder will cry. $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:45:50 </td>
   <td style="text-align:left;"> $AAPL load up easy $185 soon end of January earnings we hitting $190!+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:44:06 </td>
   <td style="text-align:left;"> ProShares Wants to Launch a Metaverse ETF. Here’s What You Should Know.

$NVDA $AAPL $RBLX $MANA.X  

https://investorplace.com/2021/12/proshares-wants-to-launch-a-metaverse-etf-heres-what-you-should-know/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:41:52 </td>
   <td style="text-align:left;"> $AAPL I still see $200 by end of Jan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:39:01 </td>
   <td style="text-align:left;"> $AAPL I’m really liking those February puts somebody invested $6 million in. Using the search criteria I use on these order flow programs any order that fit my certain criteria has never lost the puts I just found the criteria. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:37:33 </td>
   <td style="text-align:left;"> $AMC my WHOLE watch list red! All BUT $AMC - now thát should tell ypu guys something. This is only the beginning! Just eait for the real shit to hit in January/February when the big players like $TSLA $AAPL amd $AMZN will be hit. Hedge funds will burn and #AMCAPES will still be holding. It will be carnage that’s what is going to happen. Mark it! 💎👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:35:53 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 299.3K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:34:50 </td>
   <td style="text-align:left;"> $GGPI Vs $TSLA reminds me of $AAPL Vs $NOK ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:32:17 </td>
   <td style="text-align:left;"> $AAPL      🍏 Nasdaq Close:  “off lows of Day”.  Not a bad set-up into overnight…especially, as AAPL’s Close was lowered to Fill “Two Preferential Large Block Orders”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:32:08 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-29 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=LZ12BXDRLVc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:29:26 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on multiple timeframes.  it can still rally for one more high before pulling back.  If it fails to make a new high, we like to buy it lower at the equal leg blue box where buyers can enter for a bounce in 3, 7 or 11   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:29:18 </td>
   <td style="text-align:left;"> $AAPL looks like a cup and handle to me hopefully we see $182 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:28:24 </td>
   <td style="text-align:left;"> $AAPL no 3 trill this yr FACT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:26:01 </td>
   <td style="text-align:left;"> $AAPL big sell last minute lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:24:07 </td>
   <td style="text-align:left;"> $AAPL with many believe it will hit 3T shortly, it is the perfect time to set up a bull trap. I am stupid, I  believe there are many smart people out there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:22:27 </td>
   <td style="text-align:left;"> $AAPL bulls got trapped after market lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:22:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : State Of The Markets At Year End https://www.stck.pro/news/AAPL/20552071 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:19:49 </td>
   <td style="text-align:left;"> $AAPL After Hours..

Bid  ARCX
179.34 x 6
Ask  ARCX
179.37 x 2
Volume
61,041,194 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:17:15 </td>
   <td style="text-align:left;"> $AAPL 177.50 is to far away but 180 seems just as far. Last week of the year gets freaky on ops huh 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:14:17 </td>
   <td style="text-align:left;"> $AAPL

Someone parked and bought 7 million shares already at 179.38 

That means no one can go below 179.

It will lead to easy ride up to 183 to 185 EOW

LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:13:39 </td>
   <td style="text-align:left;"> $HD So we know whats coming here, lots of chasing &amp;amp; window dressing in some of my Fav&amp;#39;s.,  not a big fan of that into EOY since it means we will see Selling in Jan/Feb but what a crazy run

$aapl $msft $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:13:33 </td>
   <td style="text-align:left;"> $AAPL 20-Jan-23 210 Calls Traded 1,100 times for $1.2 Million in premium. https://tinyurl.com/y9tgluzt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:12:20 </td>
   <td style="text-align:left;"> $AAPL nice little bounce off the cloud/demand zone around 10:15, then chopped the neutral zone (yellow). but look how well it stayed in our zone. kind of crazy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:09:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $AAPL 

FOR THOSE THAT KEEP ASKIN, 
YES THE MARKET AKA THE CASINO IS OPEN ON FRIDAY

https://www.marketwatch.com/amp/story/merry-christmas-wall-street-but-theres-no-new-years-day-holiday-for-the-stock-market-this-yearheres-why-11640192753 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:05:17 </td>
   <td style="text-align:left;"> $AAPL I have a feeling that the YoY is not going to yield us a push above $3T. I still feel like a pullback is coming. Just being realistic. Still very long this name but will trade all dips and rips. 

I hope I’m incorrect. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:04:35 </td>
   <td style="text-align:left;"> $AAPL Show is over let&amp;#39;s go home and come back tomorrow!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:03:26 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s see what happens tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:03:22 </td>
   <td style="text-align:left;"> $AAPL was given a bunch of trading opportunities today.  Shitty volume but nothing to worry about since unless you’re greedy like me you’re not working this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:02:04 </td>
   <td style="text-align:left;"> $AAPL my guess is many won&amp;#39;t sell before the new year for tax purposes. , making too much money. Next Monday maybe blooded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:01:56 </td>
   <td style="text-align:left;"> $AAPL the manipulation is crazy! Can tell from the $180 price action! They don’t want those calls itm friday! If it were a free market apple would’ve already hit $200.. artificially held down like a meme stock sheesh 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:01:05 </td>
   <td style="text-align:left;"> $AAPL battle not over bears we will meet again tomorrow! This time no escape </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 05:00:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $TSLA $AAPL 

accurate depiction of bears celebrating a -0.25% &amp;quot;crash&amp;quot; after rallying +7.0% from 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:59:16 </td>
   <td style="text-align:left;"> $AAPL  WTF dude.....&amp;quot;Vaccinated and boosted Joe Biden is wearing a mask outside, on the beach, alone with his wife,&amp;quot; .....&amp;quot;Mask theater is so absurd.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:59:07 </td>
   <td style="text-align:left;"> $AAPL   🍏 MM/Specialist, is handling this Close.  Fighting off Buyers…to “Walk a Preferential Buyer’s Trade Through”.  Bid keeps jumping ahead of Ask…then pulled back to a defined spread.  Not fun to watch…but, Bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:59:00 </td>
   <td style="text-align:left;"> Looking at the yearly performance, $AAPL did better than 88% of all other stocks. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:56:50 </td>
   <td style="text-align:left;"> $AAPL Status Filled at $179.65
Symbol AAPL
Description APPLE INC
Action Sell Short
Quantity xxx Shares
Route
FDLM
Order Type Limit at $179.65
Time in Force Day
Conditions None
Trade Type Short
Market Session Standard
Order Date 12/29/2021, 03:49:39 PM ET </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:56:49 </td>
   <td style="text-align:left;"> Top Bearish Flow Today : 

$AAPL $TSLA $FUTU $BABA $CGC

🤖📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:56:20 </td>
   <td style="text-align:left;"> Top Bullish Flow Today : 

$QCOM $AAPL $BABA $TSLA $MU 

🤖📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:55:48 </td>
   <td style="text-align:left;"> $AAPL bull power last 5 mins.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:55:30 </td>
   <td style="text-align:left;"> $AAPL fk u shorts trying to close at EOD .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:55:28 </td>
   <td style="text-align:left;"> $AAPL $WKEY ↗️ $fb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:55:23 </td>
   <td style="text-align:left;"> $AAPL resistance is at 179.79 if it cuts it through we will hold it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:53:16 </td>
   <td style="text-align:left;"> $AAPL 180 coming i see it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:53:11 </td>
   <td style="text-align:left;"> $AAPL volume is weak. Fake price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:52:10 </td>
   <td style="text-align:left;"> $AAPL got some 1/7 170 puts and started a short position.  My boss is finally happy with me but I&amp;#39;ll probably sell it early to piss him off.  Overbought imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:51:12 </td>
   <td style="text-align:left;"> $AAPL the kettle is getting hot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:50:59 </td>
   <td style="text-align:left;"> $AAPL 

 this is hilarious .. really , wait till  12:58 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:49:12 </td>
   <td style="text-align:left;"> $AAPL Mr PUTZ checking his RH account tomorrow morning...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:49:10 </td>
   <td style="text-align:left;"> $AAPL one push it all it takes possibility!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:48:59 </td>
   <td style="text-align:left;"> $AAPL $175 tomorrow before the top next year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:48:12 </td>
   <td style="text-align:left;"> $AAPL $AMZN Ready for melt up day tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:47:50 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:47:11 </td>
   <td style="text-align:left;"> $AAPL 3T and $GOOGL 2T Jan 3rd! Flat next two days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:47:10 </td>
   <td style="text-align:left;"> $AAPL  🍏 Shenanigans, into the Close.  Bid, keeps jumping ahead of Ask.  Looks like, MM has an Order to Fill…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:46:48 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

A green close today is a bearish sentiment in my opinion... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:46:47 </td>
   <td style="text-align:left;"> $AAPL Taking a stab at 2DTE 175p. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:46:25 </td>
   <td style="text-align:left;"> $AAPL &amp;gt;&amp;gt; Daily Chart &amp;gt;&amp;gt;

Double top &amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:45:46 </td>
   <td style="text-align:left;"> $AAPL ........SPOOF THIS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:44:56 </td>
   <td style="text-align:left;"> $AAPL that’s a huge ASK at the 180.00 ..

Robinhood shows 80k
Webull shows 29k …  watch it disappear after the market closes .. 

Market makers don’t want it to fly ,but high probability tomorrow or Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:44:48 </td>
   <td style="text-align:left;"> $AAPL one big push once it crosses 180 then sky is the limit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:44:08 </td>
   <td style="text-align:left;"> $AAPL NEWS - AAPL Warns Foxconn India After Protests: 
https://www.youtube.com/watch?v=036Nyfvm-Gc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:42:35 </td>
   <td style="text-align:left;"> $AAPL let’s close above $180 ;) push it boys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:41:41 </td>
   <td style="text-align:left;"> $SPY I licked my wounds on my short puts  after this broke the down trend , swapped to long &amp;amp; loaded up on calls across all 3 accounts on these $QQQ $SPY  $AAPL &amp;amp; $SBUX  I expect a strong close to week .. way up right now 👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:41:40 </td>
   <td style="text-align:left;"> $AAPL 

Bull flag detected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:41:06 </td>
   <td style="text-align:left;"> $AAPL 

Low volume .. that’s usual holiday volume ..

Very dangerous premium burning !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:41:02 </td>
   <td style="text-align:left;"> $AAPL party soon!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:40:45 </td>
   <td style="text-align:left;"> $AAPL institutional entities don’t want to mess with 🍏’s buy back monies… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:39:45 </td>
   <td style="text-align:left;"> $AAPL that volume also 188k on $180 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:39:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $AAPL $TSLA 

bears still spamming about omicron after institutionals stopped giving a shit almost 5 weeks ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:37:15 </td>
   <td style="text-align:left;"> $AAPL Crooked Bears deserve a good squeeeeeze! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:37:06 </td>
   <td style="text-align:left;"> $AAPL PT $200.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:35:14 </td>
   <td style="text-align:left;"> $AAPL 180 EOD!!✅✅🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:34:59 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ $TSLA $AMZN it’s coming… $SPY $QQQ $TSLA went red to green since my first message and spy has gone $2+ since. $QQQ same </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:34:43 </td>
   <td style="text-align:left;"> $AAPL it never dissapoints...200 by tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:32:30 </td>
   <td style="text-align:left;"> $AAPL As long as we are above the VWAP we are okay ...VWAP is at 179.45 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:27:54 </td>
   <td style="text-align:left;"> $AAPL 🌈 🐻 - STAP. Let it run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:25:40 </td>
   <td style="text-align:left;"> $AAPL look at symbol KMX. Car max. Great ER last week and sold off. Coming of bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:24:32 </td>
   <td style="text-align:left;"> $AAPL just waiting for PT 185 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:24:13 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m out at $179.60 (from my 12:30 pm buy in at $178.90; see earlier ST post).  
 
I still love the stock and am looking for an all-time high but had to take short-term profit @ $175.00. 
 
You can read my earlier posts from today to see how I got there. 
 
Done for today as I&amp;#39;ve learned never to push a good thing.  :  ) 
 
Be back tomorrow. GLTA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:22:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA tomorrow&amp;#39;s gonna&amp;#39; be redder (more red? 🤔) than your mother&amp;#39;s toilet paper 27 hours after the egg falls out...

You&amp;#39;re welcome in advance...  

ps...  I&amp;#39;m probably right, but there&amp;#39;s an outside chance I&amp;#39;m wrong..  There&amp;#39;s also an outside chance that I&amp;#39;m your father, but who&amp;#39;s keeping trach eh&amp;#39;? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:22:43 </td>
   <td style="text-align:left;"> $SPY pushing HOD ATH areas while retail accounts in big reds with small cap and growth stocks  
 
again $aapl $msft etc .. mega cap again being pump .. Insane </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:22:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL $TWTR  
 
I dont know about you, but Im feeling the investment landscape for 2022, ooh ooh! Everything will be alright if I do me and you do youuuuuu!!! 
 
You dont know about me, but I bet you want toooo. Everything will be alright if, if we just keep investing iinn 2022! 
 
(Take his man card, please ;-) ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:21:37 </td>
   <td style="text-align:left;"> $AAPL lmao bulls got fucked . I sold my outs at opening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:21:26 </td>
   <td style="text-align:left;"> $SPY One last pump before the big drop. I&amp;#39;m bullish but this is ridiculous. Total manipulation to destroy retail traders. Tread lightly at these levels. I have call LEAPs but am buying short term puts for the drop. Should be nasty. $QQQ $NDAQ $DIA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:21:03 </td>
   <td style="text-align:left;"> $AAPL So these MMs (crooks) can hold this and won&amp;#39;t let reach the milestone. Apparantly there are too many bets on the higher end that need to go worthless and they are doing their best to destroy them. This needs to see 182+ before the year ends.

Politics aside, Santa rally came fast and furious during Trump&amp;#39;s era. This new guy is... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:20:43 </td>
   <td style="text-align:left;"> $AAPL Recent sweeps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:20:28 </td>
   <td style="text-align:left;"> $AAPL gooooo!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:20:26 </td>
   <td style="text-align:left;"> $CPOP i dont respond to dms,

Still holding. Also this is far from over.🚀🤞😏

Adjusted PT to $5.

$MARA $AAPL $TSLA $GREE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:20:22 </td>
   <td style="text-align:left;"> Looks lie $AAPL gonna close the year at 179.99, $3T next year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:19:37 </td>
   <td style="text-align:left;"> $AAPL $FB https://www.bloomberg.com/news/articles/2021-12-28/apple-pays-unusual-180-000-bonuses-to-retain-engineering-talent

Jeez! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:16:19 </td>
   <td style="text-align:left;"> $AAPL I think my computer froze.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:12:50 </td>
   <td style="text-align:left;"> $AAPL I will close my puts if it goes red again today and buy calls instead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:12:42 </td>
   <td style="text-align:left;"> $AAPL up you bastard!! My calls expire Friday lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:11:11 </td>
   <td style="text-align:left;"> $AAPL testing resiliency, it seems Apple holding up pretty good, I expect a bounce tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:11:00 </td>
   <td style="text-align:left;"> $AAPL bears …taunting the Nasdaq… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:09:39 </td>
   <td style="text-align:left;"> $AAPL 190 coming in the power hour </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:08:50 </td>
   <td style="text-align:left;"> $AAPL when Bears post doom in rapid tweets, it’s time to buy.  SQUEEZE EM HARD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:07:56 </td>
   <td style="text-align:left;"> $AAPL I wouldn’t be surprise if media/news come out about potential new year attack on USA soil $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:07:30 </td>
   <td style="text-align:left;"> $SPY $AAPL market is telling you to get in now. Need new bag holders so they can get out before the huge drawdown🙊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:06:34 </td>
   <td style="text-align:left;"> $AAPL Sweeper Alert 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:05:23 </td>
   <td style="text-align:left;"> $AAPL 180 push!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:02:47 </td>
   <td style="text-align:left;"> $AAPL Lmao telling people to look at the past on why it went from 100 to 180. That does not explain on why it should go pass 180. Enough said. :) unless you’re a whale, no reason to buy at this price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:01:51 </td>
   <td style="text-align:left;"> $AAPL power hour, send her North and SQUEEZE SHORTS HARD!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:01:50 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s have a NICE close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:01:29 </td>
   <td style="text-align:left;"> $AAPL and the $HD are the market leaders like everyday. Holding these boys up! $DJIA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:01:16 </td>
   <td style="text-align:left;"> Some top tech sector flow coming in above ask

$NVDA - $354K call sweep
$AAPL - $243K call sweep
$MDB - $174K call sweep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:00:47 </td>
   <td style="text-align:left;"> $AAPL looks like UPS can use some armor Apple Electric Truck! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 04:00:28 </td>
   <td style="text-align:left;"> $SPY 500+, $AAPL 190+ incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:59:46 </td>
   <td style="text-align:left;"> $AAPL my new trading chair.. haters gonna hate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:59:03 </td>
   <td style="text-align:left;"> $SPY  
Samsung wanna buy $BIIB and $AAPL buy $PFE ? 
Nice deals!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:58:46 </td>
   <td style="text-align:left;"> $AAPL the only way spoke not happy about todays stock price are those who aren’t holding shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:56:44 </td>
   <td style="text-align:left;"> $AAPL bears gonna get roasted, there&amp;#39;s still time to flip bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:55:42 </td>
   <td style="text-align:left;"> $AAPL Higher lows on the daily. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:54:50 </td>
   <td style="text-align:left;"> What..what~?
Apple $AAPL gives some engineers a rare $180,000 bonus to prevent them from defecting to Meta $FB | Daily Mail Online

$AMD ↗️ + $XLNX ⏳? https://www.dailymail.co.uk/sciencetech/article-10350935/Apple-gives-engineers-rare-180-000-bonus-prevent-defecting-Meta.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:54:49 </td>
   <td style="text-align:left;"> $AAPL lower lows and lower highs form </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:54:42 </td>
   <td style="text-align:left;"> $AAPL 

Let her loose !!!! PH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:52:32 </td>
   <td style="text-align:left;"> $AAPL honestly who the fuck is buying at this level! The market doesn’t even feel the same anymore anyone who doesn’t agree this and everything else needs a break or a nice discount is delusional </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:50:58 </td>
   <td style="text-align:left;"> $AAPL my calls and puts both down massively , good job </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:50:51 </td>
   <td style="text-align:left;"> $AAPL Sure it has news at $140 doesnt mean it has anything to help it pass the $180 threshold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:49:49 </td>
   <td style="text-align:left;"> $AAPL 

No need to explain why it needs to go higher …

You are asking me same thing since 140, 150, 160, 170 and now 180 

I have answered back to you already …

My explanation to you - go read and GTFO

Thank you !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:49:14 </td>
   <td style="text-align:left;"> $AAPL there is no news to carry this to 190+ because it ran from 160s to 180 under 2 week! To high and to fast . Expect it to drop first $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:48:49 </td>
   <td style="text-align:left;"> $AAPL bearish flow detected... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:48:45 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:48:24 </td>
   <td style="text-align:left;"> $NVAX Go Green Stay Green and let&amp;#39;s get the Press Release!!! $IBB $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:48:02 </td>
   <td style="text-align:left;"> $AAPL why should Apple go higher than 180? Explains so I can be bullish. From what I can see, the only reason is that you want it to be 3T. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:46:36 </td>
   <td style="text-align:left;"> $AAPL $TSLA Y’all ready for the FLUSH???? Grab your dicks, it’s comin’ in hot… NO 3T for Apple until earnings, No run for Tesla because Elon is done selling. Big dogs have been waiting patiently to bring both down to load up for next year… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:46:07 </td>
   <td style="text-align:left;"> $AAPL covid is everywhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:45:44 </td>
   <td style="text-align:left;"> $MRK run in $MRK … $AAPL $TSLA $SPY  .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:45:10 </td>
   <td style="text-align:left;"> $AAPL 

🤣🤣🤣🤣calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:42:12 </td>
   <td style="text-align:left;"> $AMZN need the split playbook like $AAPL and $TSLA . Tesla wouldn&amp;#39;t have been able to reach 1T without splitting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:42:11 </td>
   <td style="text-align:left;"> $AAPL puts gonna print 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:41:41 </td>
   <td style="text-align:left;"> $AAPL Dump hour incoming? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:40:02 </td>
   <td style="text-align:left;"> $IIVI $AAPL https://www.gophotonics.com/news/details/2771-apple-collaborates-with-ii-vi-with-a-new-410-million-award-from-its-advanced-manufacturing-fund </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:39:30 </td>
   <td style="text-align:left;"> $aapl $msft $tsla https://www.youtube.com/watch?v=xD9Nu_487sQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:39:12 </td>
   <td style="text-align:left;"> $AAPL do testatrone boost man boob? Asking for a friend since he wanna work out $PLTN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:38:09 </td>
   <td style="text-align:left;"> $AAPL  🍏 See:  Hoya/ WSJ Article Post, below.  85% of Active WallSt Funds, failed to meet/beat AAPL’s 2021 Performance.  Were you an AAPL Shareholder this Year?  If so, congratulations!  Give yourself, a pat on your back:  You beat 85% of WallSt’s Active Money Managers.  A hearty, “Hoya Saxa” to all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:37:52 </td>
   <td style="text-align:left;"> $AAPL 

This action is similar to the session on 12/23 

Meaning we will see rise by the EOD

Pumping up at the close of day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:37:47 </td>
   <td style="text-align:left;"> $AAPL wish i didnt sell calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:36:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL calls and puts are getting killed but bears are having a hard time 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:36:27 </td>
   <td style="text-align:left;"> $AAPL next 2 days down or theta burn. Lock in those gains. Good year guys! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:35:42 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ lookkng weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:34:16 </td>
   <td style="text-align:left;"> $AAPL on fidelity, is it possible to buy back the 12/31 $187.50 covered calls I sold while simultaneously selling 12/31 $185 covered calls? Would bring in more premium. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:34:05 </td>
   <td style="text-align:left;"> $AAPL late day run? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:33:14 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-29 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=LZ12BXDRLVc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:32:10 </td>
   <td style="text-align:left;"> $AAPL first psychological mark 3 T and then second one for 200$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:31:17 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $SNIPF Snipp cutting costs big time, while growing revenues. And recently crossed over into positive cash flow, impressive for a new company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-30 03:30:17 </td>
   <td style="text-align:left;"> $AAPL the shorts are taking it today right up the ……. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 14:14:10 </td>
   <td style="text-align:left;"> $AAPL $TSLA 

FUTES RIPPING 😆🖕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 14:13:12 </td>
   <td style="text-align:left;"> $SPY $TSLA $RIOT silver to diamond with top lane even tho i havent played in so long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 14:11:45 </td>
   <td style="text-align:left;"> $TSLA     Bears are going to suffer.  That&amp;#39;s what I think.   Several back-to back catalysts will occur that will bump the price up several dollars each time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 14:08:17 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Technical Analysis Video: 
https://www.youtube.com/watch?v=GMQxgDrix7Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 14:06:31 </td>
   <td style="text-align:left;"> $TSLA She tweakin bro

https://m.theepochtimes.com/cathie-sells-another-22-million-worth-of-shares-in-tesla-on-tuesday_4182750.html/amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:57:50 </td>
   <td style="text-align:left;"> $TSLA   Lets do a poll....I say we make this a Yogi-free Post. I&amp;#39;m SO tired of hearing and blocking garbage from these fuzz balls.....not to mention having to endure the lamentations of their women.....WINTER IS COMING yogi....long,cold,and bleak.and I pity your sorry hides. Didn&amp;#39;t you get the memo? Elon is going to now skin your sorry hides once and for all....have a HAPPY NEW YEAR. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:56:55 </td>
   <td style="text-align:left;"> https://www.investing.com/indices/indices-futures  $f $tsla $ccl  $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:54:01 </td>
   <td style="text-align:left;"> @GoodieGood $tsla dip into earnings then rip $aapl rip into earnings then dip heard it here first 🥦💨😮‍💨😴✌🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:52:23 </td>
   <td style="text-align:left;"> $UWMC $FCEL $TSLA $AMC $49,000 a day keeps the 9 to 5 away; Stay patient and the let the trade play out...🚀 https://www.discord.io/rBHacCP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:50:07 </td>
   <td style="text-align:left;"> $tsla $f $gm $NKLA $tm https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwiD_6Kn6Yr1AhVbj4kEHTn-DIEQxfQBKAB6BAgREAI&amp;amp;url=https%3A%2F%2Fwww.fool.com%2Finvesting%2F2021%2F12%2F13%2Fwhy-ford-general-motors-nikola-and-other-auto-stoc%2F&amp;amp;usg=AOvVaw2MhG8qiUXB1vQCvL54duc8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:48:47 </td>
   <td style="text-align:left;"> https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwiD_6Kn6Yr1AhVbj4kEHTn-DIEQxfQBKAB6BAgPEAI&amp;amp;url=https%3A%2F%2Fwww.barrons.com%2Farticles%2Fstock-ford-gm-tesla-outlook-51639508218&amp;amp;usg=AOvVaw0yqVmLotxS6Par7SmU32hd $tsla $f $gm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:48:11 </td>
   <td style="text-align:left;"> Getting Paid Over $25,000 For My Used Honda! Carvana or Carmax? https://youtu.be/txYxrwQrkYQ $CVNA $KMX $HTZ $CAR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:43:11 </td>
   <td style="text-align:left;"> @GoodieGood $tsla I want $1020 retest and the Rip 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:40:01 </td>
   <td style="text-align:left;"> $JOBY We are close to 10000 watchers  !!

It’s going to be a great milestone for sure !! The power of retail when stayed together is under estimated 

$TSLA  meets $UBER is $JOBY 

Disruption is inevitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:38:07 </td>
   <td style="text-align:left;"> $TSLA ROTFLMAO at the graveyard shift of TESLA bulls and sheeples hard at work, or better yet,hardly working, jawboning long TESLA silliness. The folk that keep on giving  ... thanks 🐂&amp;#39;s for lending 🐻&amp;#39;s your shares to short for profits at your expense. 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:36:58 </td>
   <td style="text-align:left;"> $TSLA TSLA reallt fuvked me this week down 1.1k and maybe another 300 tomorrow. Holding my contract till 0 I suppose </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:34:30 </td>
   <td style="text-align:left;"> $TSLA wow, looks like elon and cathie are both in sink these days dumping their bags onto retail fomoing in at the top... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:29:55 </td>
   <td style="text-align:left;"> $TSLA Run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:28:39 </td>
   <td style="text-align:left;"> $DWAC $F $GM $TSLA does it really work??
https://youtu.be/_W_BWkNl1pU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:28:30 </td>
   <td style="text-align:left;"> $PTRA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:27:04 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA  I have a 2k/day quota that I have to meet day trading with the occasional 10k/day when the market is volatile enough. My daily driver is a Tesla, occasional driver Lamborghini, just moved into a massive new place in NY and I&amp;#39;m single. 
If I can do it, YOU can do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:23:33 </td>
   <td style="text-align:left;"> $TSLA Futes fucking ripping bears asses in half with these enormous green hulk dicks. Tesla to the fucking moon tomorrow, these WSB pumps never fail when we all get together and yolo money on a gamme squeeze. We can certainly afford it with tesla options. To the moon, to the moon 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:14:49 </td>
   <td style="text-align:left;"> $TSLA no catalyst. Flat day. We all lose money. Bear or bull lose money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:14:33 </td>
   <td style="text-align:left;"> $TSLA tomorrow 1050 below </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:14:00 </td>
   <td style="text-align:left;"> $TSLA is currently trading in the upper part of its 52 week range, slightly lagging the index. https://www.chartmill.com/stock/analyzer/stock/TSLA?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:11:56 </td>
   <td style="text-align:left;"> $TSLA FUTURES RUPPING LETS GO ALL IN ON SHORT TERM EXPIRY TESLA OPTIONS AGAIN 🚀 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:10:38 </td>
   <td style="text-align:left;"> $TSLA I guess it will be another flat day or close slightly lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:09:50 </td>
   <td style="text-align:left;"> $TSLA 
above 1098 it can see 1125-1140
below 1059 it can see 995-1005 intraday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:08:43 </td>
   <td style="text-align:left;"> $MVIS $DNAY $AMC $TSLA For a limited time,from Xtrades  we are opening our trading chatroom to the public. Get access to chatrooms, stock alerts, option alerts,, portfolios, and more...  https://www.discord.io/rBHacCP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:07:54 </td>
   <td style="text-align:left;"> $TSLA GIGA TEXAS🤯👉 https://youtu.be/B5tQ3ktVUOU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:07:14 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Options Analysis Video: 
https://www.youtube.com/watch?v=9i7Q9FtIDeA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 13:02:53 </td>
   <td style="text-align:left;"> latexed8d9ba3b9fcf689f915d2dab010d4e4 OTM options anyway between 1097 and 1100? NOTHING

I had 1400 calls for next week. 
You best believe i sold at 1097. 

3$ is the difference between a baggie and a profit maker. 

Remember it can be less, or more. But the point is SPTP , see profit take profit. Don&amp;#39;t wait for that nice round even number. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:59:46 </td>
   <td style="text-align:left;"> $TSLA $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:57:34 </td>
   <td style="text-align:left;"> $TSLA , $SPY $49,000 a day keeps the 9 to 5 away; Stay patient and the let the trade play out.. stockplays.livetradeview.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:56:12 </td>
   <td style="text-align:left;"> $TSLA halted? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:54:17 </td>
   <td style="text-align:left;"> $METX we will have our day ladies and gents $VISL $GME $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:51:23 </td>
   <td style="text-align:left;"> $ARDX $NVDA $TSLA $SPY For a limited time,from Xtrades  we are opening our trading chatroom to the public. Get access to chatrooms, stock alerts, option alerts,, portfolios, and more...  https://www.discord.io/xEvE2Aatrp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:51:12 </td>
   <td style="text-align:left;"> $TSLA  let’s have Elon give a tweet before the year is over and toast the shorts and large hedge funds! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:47:40 </td>
   <td style="text-align:left;"> $TSLA 
Everyone tomorrow 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:46:32 </td>
   <td style="text-align:left;"> $TSLA Elon has been selling off his shares and putting it all in Petco, incase y’all are wondering why $WOOF is trending rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:43:05 </td>
   <td style="text-align:left;"> $TSLA Tesla Group is made of

Tesla Auto
The Autopilot by Tesla Auto
The Boring Company
Neuralink
SpaceX

The Boring Company alone is valued $200B

Therefore, Tesla Group is currently undervalued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:43:02 </td>
   <td style="text-align:left;"> $TSLA $WKEY “WISeKey announced its IoT Picosatellites WISeSat-1 and WISeSat-2 are tested and ready to launch onboard of SpaceX Falcon 9 in January 2022”

“announced that they have completed the installation of the first ground station that will serve as the control base for the direction of IoT satellites. With this installation, marks the completion of the first phase of the MoU signed earlier this year between the municipality of La Línea and WISekey for the creation of a 4th Industrial Revolution Center of Excellence”

https://www.globenewswire.com/news-release/2021/11/12/2333564/0/en/WISeKey-announced-its-IoT-Picosatellites-WISeSat-1-and-WISeSat-2-are-tested-and-ready-to-launch-onboard-of-SpaceX-Falcon-9-in-January-2022.html

https://llg4ir.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:39:47 </td>
   <td style="text-align:left;"> $TSLA SpaceX&amp;#39;s Starship Orbital Debut Pushed To March As FAA Flooded With Public Comments 

https://newsfilter.io/a/8c104024f218a2d2ba735b0f563db3ee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:38:31 </td>
   <td style="text-align:left;"> $TSLA aftee last Friday tho daily movement looks like s huge beartrap bluff... Should have bought Mondays but instead today bought 10!11170c for Jan21 hopefully gain 50~75 % catching the delivery numbers and the er fomo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:35:21 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Largest Trades Data: 
https://www.youtube.com/watch?v=0Aho2hBtUf4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:34:08 </td>
   <td style="text-align:left;"> $SPCE sorry guys $WOOF is the future. 🚀 $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:34:04 </td>
   <td style="text-align:left;"> $AMD 96% bullish.  Chart is very similar to $TSLA , bull run. 

Free discord in bio for real time updates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:33:55 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-model-3-from-hertz-large-order-started-arriving-will-be-rolled-out-to-new-markets-next-year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:33:18 </td>
   <td style="text-align:left;"> $TSLA Still undervalued </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:30:54 </td>
   <td style="text-align:left;"> $TSLA i deposited 25,000$ today on TD but dont have that in my bank account but im day trading with it tmr before it bounces and if i make money do i keep the profits while ach bounces??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:30:17 </td>
   <td style="text-align:left;"> $TSLA fu bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:29:31 </td>
   <td style="text-align:left;"> $TSLA in last three days market makers scared shitt out of majority of options buyers and forced them to sell their positions so that they run with their losses also they made bears fall into their trap by giving them a false hope that it may go towards $1000 so far so good the plan of fuckking both side worked out so well. Even in Casino, You play against each other but Casino owner is the one who fuckk both sides </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:28:53 </td>
   <td style="text-align:left;"> $TSLA Price always does opposite of what I do. I buy Calls, immediately drops once the order fills and keeps going south. Have no worry bulls. If I load up on Puts tomorrow it&amp;#39;s bound to rocket north. 

Guess that&amp;#39;s the game plan tomorrow 🤣 I say this while out drinking captain tonight btw 😁 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:28:26 </td>
   <td style="text-align:left;"> $TSLA $$$$$$$$$$$$
https://www.reuters.com/markets/us/elon-musks-spacex-raises-over-337-mln-fresh-funding-2021-12-29/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:20:45 </td>
   <td style="text-align:left;"> $TSLA Quiet because I had Elon&amp;#39;s green monster cock in my mouth 🍆🤤🤤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:16:42 </td>
   <td style="text-align:left;"> $TSLA another half percent .
Bs. Lets rip today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:13:11 </td>
   <td style="text-align:left;"> $TSLA this thread is very quite tonight, l like it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:12:11 </td>
   <td style="text-align:left;"> $TSLA  I AM GOING TO PLAY THE SIDELINES  ON THIS TILL Q4 EARNINGS NEXT MONTH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:09:12 </td>
   <td style="text-align:left;"> $TSLA $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:09:05 </td>
   <td style="text-align:left;"> $TSLA Take it serious or not but my all instincts say that Tesla will hit $1160 by this Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:08:40 </td>
   <td style="text-align:left;"> $TSLA $TQQQ 
They are identical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:06:18 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Daily Forecast Video: 
https://www.youtube.com/watch?v=ikdiN8pX3C8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:05:02 </td>
   <td style="text-align:left;"> $TSLA market closed Friday ? For New Years ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:03:44 </td>
   <td style="text-align:left;"> $TSLA Is buying TSLA an IQ test? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:03:02 </td>
   <td style="text-align:left;"> $UPST $TSLA $AAPL 
Short selling has become normalized but how much of it is legit/legal?  If you have major hedge funds and institutional investors shorting a stock they obviously have major pull and can pull the stock down.  This is what people mean when they say &amp;quot;market manipulation&amp;quot;.  And the ones doing this have so much power that it&amp;#39;s very unlikely for them to get caught.  I think this will be dealt with behind the scenes as not to affect the market because if the true nature of manipulation was made public it would scare away many retail investors.  Stocks will rise in 2022. Corruption eventually always gets exposed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 12:02:56 </td>
   <td style="text-align:left;"> $ILUS IN TALKS WITH $TSLA !! AMAZING NEWS!

https://youtu.be/iw0LndRBZIM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:58:45 </td>
   <td style="text-align:left;"> $TSLA 

Elon Musk&amp;#39;s SpaceX raises over $337 mln in fresh funding

🙏🏻🐉🦅

https://www.reuters.com/markets/us/elon-musks-spacex-raises-over-337-mln-fresh-funding-2021-12-29/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:57:23 </td>
   <td style="text-align:left;"> $FTK We have a buyer in the house! An American company for sale. Who wouldn&amp;#39;t want to take part? $SPY $TSLA 

1.11$ so far 

(NYSE: FTK) has received an unsolicited indication of interest for a potential transaction for all or part of the Company. To assist in evaluating this unsolicited indication of interest, Flotek&amp;#39;s Board of Directors has engaged Piper Sandler &amp;amp; Co. (&amp;quot;Piper Sandler&amp;quot;) as a financial advisor to assist with the evaluation process. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:56:21 </td>
   <td style="text-align:left;"> $NKLA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:52:12 </td>
   <td style="text-align:left;"> $IPOF Chammy sold his entire $TSLA position to buy a jet…no very eco friendly. Why would Elon give him Starlink or SpaceX. Only shitty companies go SPAC and Elon’s companies are neither. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:51:44 </td>
   <td style="text-align:left;"> McClellan Oscillator: The Best Market Timing Indicator?

$TSLA $MRNA $AAPL $FUBO $GME 

https://www.chartlearning.com/2021/11/what-is-the-mcclellan-oscillator-indicator.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:51:16 </td>
   <td style="text-align:left;"> $TSLA honestly, I don’t blame it if it bleeds tmmr. However, I would like to see another run or a pp touch @1098.

If it can’t surpass it, buy them poooots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:50:27 </td>
   <td style="text-align:left;"> $TSLA moving sideways eating premium all week this will </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:48:58 </td>
   <td style="text-align:left;"> $TSLA good read! Let’s see what this window dressing does tomorrow and after tomorrow 😎 https://www.investopedia.com/terms/w/windowdressing.asp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:47:44 </td>
   <td style="text-align:left;"> $TSLA Red to Green move:  -2.24%  to +0.07% https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan&amp;amp;type=redtogreenDaily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:47:32 </td>
   <td style="text-align:left;"> $TSLA Are sales and profits up after 4th Quarter 2021 in comparison with 2020 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:46:31 </td>
   <td style="text-align:left;"> $TSLA aww down she goes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:46:19 </td>
   <td style="text-align:left;"> $TSLA rip grichka the legend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:46:07 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:44:54 </td>
   <td style="text-align:left;"> $TSLA best in the world!

https://www.freep.com/story/money/cars/mark-phelan/2021/12/29/2022-lucid-air-care-electric-vehicle-luxury-sedan-review-price/9016627002/?gnt-cfr=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:43:52 </td>
   <td style="text-align:left;"> $TSLA breaks out tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:42:23 </td>
   <td style="text-align:left;"> $TSLA 

Bulls are Mammals.

Bears are Fungus.

. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:40:21 </td>
   <td style="text-align:left;"> $TSLA too bullish in here. 

A good sign for my puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:39:16 </td>
   <td style="text-align:left;"> $TSLA 

Apples and Oranges
~~~~~~~~~~~~~~~~~

https://m.facebook.com/story.php?story_fbid=1667505413599561&amp;amp;id=395068240843291&amp;amp;fs=1&amp;amp;focus_composer=0&amp;amp;m_entstream_source=feed_mobile

.
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:38:48 </td>
   <td style="text-align:left;"> Tesla (TSLA) CEO Elon Musk sold another $1.02B in common stock. $TSLA.
https://www.tiktok.com/@stockcryptotok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:35:10 </td>
   <td style="text-align:left;"> $TSLA Damn.  Cathie in sync with Elon.  😅🤣😂😆🤪😁💲💰💲💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:34:48 </td>
   <td style="text-align:left;"> $TSLA the condition they deliver some cars in is funny as hell. 😂 doesn’t seem to stop anyone from buying them though, I suppose a cult can be a business. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:34:44 </td>
   <td style="text-align:left;"> $TSLA bottom catching </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:34:40 </td>
   <td style="text-align:left;"> Cathie Wood&amp;#39;s ARK Investment sold 27.9K shares of Tesla today. $TSLA.
https://www.tiktok.com/@stockcryptotok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:34:19 </td>
   <td style="text-align:left;"> Equity Sentiment: $TSLA is the #3 stock that institutions are trading with 26.0K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:33:49 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=uy2ic7uRIdA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:32:38 </td>
   <td style="text-align:left;"> $TSLA may crack level 4 autonomy this year. The best real-world functioning AI in the world. Long-term, the bot division  may surpass auto production. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:31:46 </td>
   <td style="text-align:left;"> $TSLA I just rode in a 2020 Model 3 Performance. Fastest car I ever have been in. Torque is mind blowing. New update is amazing. It&amp;#39;s Game Over. Buying more TSLA tomorrow. $GM and $F. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:31:42 </td>
   <td style="text-align:left;"> $TSLA uh oh..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:24:31 </td>
   <td style="text-align:left;"> $TSLA for Christmas, New Year and all there after🇺🇸😎🍾🍾

https://media0.giphy.com/media/QT4ecsgzl8s7ALZQsX/giphy.gif?cid=5e2148861a956387ca31b77bc3d88ecfacbc26b7a6751dd3&amp;amp;rid=giphy.gif&amp;amp;ct=g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:22:35 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:21:17 </td>
   <td style="text-align:left;"> $AABB latex0f9d564db5d008c4ad116a87af112b05BBIO
$BFRI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:17:22 </td>
   <td style="text-align:left;"> $TSLA love seeing it stay up all week, it’s going to the moon after the 1st </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:15:05 </td>
   <td style="text-align:left;"> $AABB $SPY $TSLA $AAPL $MSFT New Exchange and massive paid bashing! You know what that means 1000% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:13:00 </td>
   <td style="text-align:left;"> Looking at the yearly performance, $TSLA did better than 93% of all other stocks. https://www.chartmill.com/stock/quote/TSLA/technical-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:12:54 </td>
   <td style="text-align:left;"> $VLN $DDAIF $F $TSLA $RIVN $INDI 

Doing some DD on VLN . I know a couple months old .. any idea on truck they could be referencing? @ 

https://m.calcalistech.com/Article.aspx?guid=3913730

We are in Mercedes and we have another deal in trucks, we will soon announce a product that does not exist in any truck and it is a game changer for the driver.&amp;quot;

@_HCMC_MoneyTeam_GNCP_ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:11:20 </td>
   <td style="text-align:left;"> $TSLA $NIO $RIVN https://youtu.be/4KvroPV1zY8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:10:47 </td>
   <td style="text-align:left;"> $TSLA $NVDA amazing year for these two large cap. Expecting eoy performance rally. Holding calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:09:05 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:08:17 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀🚀😩😩🔥🔥🤪🤪✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:07:47 </td>
   <td style="text-align:left;"> $F $TSLA Ford Bags Large Mustang Mach-E Order From NYC, With Tesla Also In The Fray 

https://newsfilter.io/a/161946949cc1f0a3a5b6ec5a1558ab52 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:07:31 </td>
   <td style="text-align:left;"> $TSLA oh sheet! 40% down on the South African Exchange!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:05:56 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m honestly surprised by the amount of misinformation and flawed reasoning that the bears have on this board. Some bulls too. But mostly the bears. For example, they take one piece of information, that Elon sold shares, and conclude that he&amp;#39;s &amp;quot;dumping&amp;quot; because he doesn&amp;#39;t believe in TSLA anymore. Really? They don&amp;#39;t understand that he&amp;#39;s actually &amp;quot;cash poor&amp;quot; and had no choice to sell shares, because he needed to pay taxes on his options, which are expiring next year. That&amp;#39;s public information. But they don&amp;#39;t get it. Either they&amp;#39;re too stupid, or they actually do understand but are intentionally twisting the truth for their own gain. Not sure which is worse... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:05:47 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:05:19 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Technical Analysis Video: 
https://www.youtube.com/watch?v=GMQxgDrix7Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:05:16 </td>
   <td style="text-align:left;"> $TSLA next target is $1142 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:04:43 </td>
   <td style="text-align:left;"> $TSLA this stocktraderhub is an idiot what is cathie woods down for the year about 25 percent loss in 2021 for her ark fund, previous year up 180 percent did it with tesla stock, paired out of tesla in 2021 for various reasons now losing her ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:04:26 </td>
   <td style="text-align:left;"> Top Sell Flow Money - 12.29.2021 - $AAPL $TSLA $IEF $FXI via Super Stocks App </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:04:13 </td>
   <td style="text-align:left;"> $TSLA Wow the days before the first stock split &amp;amp; S&amp;amp;P inclusion were announced </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:03:05 </td>
   <td style="text-align:left;"> $TSLA  Anyone knows the source of this predective tsla chart? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 11:02:41 </td>
   <td style="text-align:left;"> $TSLA getting close to me weekly $1175 yolo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:59:10 </td>
   <td style="text-align:left;"> $TSLA watching for flag break to see 1131+

Link in bio for free discord where i provide daily and pre mkt analysis with price targets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:58:36 </td>
   <td style="text-align:left;"> $TSLA Tesla delivery Jan 3rd..get in before then!! Just saying! ;) It&amp;#39;s going to the moon! This is Tesla&amp;#39;s year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:54:31 </td>
   <td style="text-align:left;"> $TQQQ $TSLA $NVDA fut need to make up their mind.. and FeD need to stop pumping this 5#i7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:50:27 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow

https://youtu.be/l8y33AH7QTE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:49:49 </td>
   <td style="text-align:left;"> Thursday Watchlist Part 5: 🚀

1) $ISIG
2) $SPY
3) $TSLA
4) $SNDL
5) $ENSC 

There Will Be More Huge Runners Coming. 🤫💯🔥🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:49:42 </td>
   <td style="text-align:left;"> $DCRN spac target Tritium is the only $TSLA Supercharger competitor. $F EVs will rely on this international infrastructure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:44:54 </td>
   <td style="text-align:left;"> $BTC.X Since this and $TSLA are joined at the hip, is this bringing TSLA down or the other way around?  Hmmmm.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:42:12 </td>
   <td style="text-align:left;"> $TSLA I just saw hood raised the margin requirement from low to med and increased from 25% to 35% maintenance…when I see this it was Feb/March this year…I hope these mofos don’t take our share again…expecting pains ahead but am bullish AF..I ll sell my rollover IRA to fund my margin even </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:41:49 </td>
   <td style="text-align:left;"> $TSLA Literally all of smart money CEO included! Are dumping tesla and the bulls are eating it up, it&amp;#39;s wild really. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:40:45 </td>
   <td style="text-align:left;"> 🚨 ARK LATEST TRADES 🚨 :

$TDOC - $TSLA - $VRTX - $XPEV - $BLDE 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:40:31 </td>
   <td style="text-align:left;"> $TSLA strong hold on highs past 2 days , will buy risking 1080 , thinking $TSLA will close all time highs or around 1200 next 2 days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:40:22 </td>
   <td style="text-align:left;"> 🚀Watchlist for Thursday #4:
1) $EFOI (Gapper potential)
2) $TSLA (TL resistance rejection)
3) $SPY (Holding highs still)
4) $NRXP (Wedge forming)
5) $NEW (Vwap break can see next leg)

Congrats if you banked today on CPOP $2.86-3.50 (22% daytrade✅) I gave out bangers early everyday🧨🤑🔮More coming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:39:05 </td>
   <td style="text-align:left;"> $TSLA zzz. Cathie wood is still selling tesla. Didnt she say tesla is the best and she will only sell tesla when it reaches her goal of 7k? What a hypocrite. To make things worse. She is selling tesla and deploying the money to buy chinese ev xpeng 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:38:52 </td>
   <td style="text-align:left;"> $TSLA tomorrow we pop, just because last 2 days looked like it was going to rally and drop !! , tesla rarely make any sense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:38:36 </td>
   <td style="text-align:left;"> Tesla Motors&amp;#39;s SVP Powertrain and Energy Eng. just cashed-in 3,500 options  https://www.conferencecalltranscripts.com/summary/?id=10272968 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:37:26 </td>
   <td style="text-align:left;"> AMD Ryzen And 12V Li-Ion Battery Spotted In New Model 3/Y In US $amd $tsla $nvda $soxx $smh  https://insideevs.com/news/557722/amd-12v-liion-model3y-us/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:35:21 </td>
   <td style="text-align:left;"> $TSLA gonna be honest, this is going down tomorrow… long and strong though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:34:30 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Daily Forecast Video: 
https://www.youtube.com/watch?v=ikdiN8pX3C8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:33:50 </td>
   <td style="text-align:left;"> $TSLA 

Imagine treating every FLU 😷 case as a COVID case ?!! Or every COVID case as FLU 😷 case — what ?! !!! is there a difference  ! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:31:51 </td>
   <td style="text-align:left;"> $TSLA more insiders dumping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:29:49 </td>
   <td style="text-align:left;"> $TSLA 📜 SEC Form 4: Baglino Andrew D exercised 3,500 shares at a strike of $62.72 and sold $3,755,500 worth of shares (3,500 units at $1,073.00) as part of a pre-agreed trading plan

https://quantisnow.com/insight/2194064?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:29:20 </td>
   <td style="text-align:left;"> Insider Andrew D Baglino reports selling 3,500 shares of $TSLA for a total cost of $3,755,500.00 https://fintel.io/n/us/tsla/baglino-andrew-d?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:29:17 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: SVP Powertrain and Energy Eng. Baglino Andrew D: 
Disposed 3,500 of Common Stock at price $1,073 an https://s.flashalert.me/Al5zn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:28:44 </td>
   <td style="text-align:left;"> $TSLA $3,535,980.00 of shares sold by Baglino Andrew D (SVP Powertrain and Energy Eng.), reported in a new form 4 filed with the SEC  

https://newsfilter.io/a/3ef08100b572c526a4bc2bb1837d09d5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:24:50 </td>
   <td style="text-align:left;"> $TSLA tomorrow will break out, 3 days at top of bearish trend line on the daily. If the market is even decent I&amp;#39;m looking for a jump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:24:08 </td>
   <td style="text-align:left;"> $arkk $arkg $tsla — Samsung buying … Biogen?   
 https://news.yahoo.com/samsung-talks-buy-biogen-42-225844053.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:22:24 </td>
   <td style="text-align:left;"> $TSLA Asian Fomo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:21:41 </td>
   <td style="text-align:left;"> $TSLA how’s is looking tmr shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:20:53 </td>
   <td style="text-align:left;"> $TSLA 1020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:18:48 </td>
   <td style="text-align:left;"> $TSLA en always pull the trigger to early on calls need to wait till about 11 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:17:22 </td>
   <td style="text-align:left;"> $TSLA headed to $10T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:16:41 </td>
   <td style="text-align:left;"> $SPY shorts are hunting the market now, most tickers are cut down to size already, only few juggernauts left supporting indexes, GAME OVER $aapl  $msft $tsla $nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:15:52 </td>
   <td style="text-align:left;"> $TSLA ➡️LCLP 💎 up 50% 🚨in 2 days and just the beginning! Imagine just putting one Tesla share into LCLP and letting it sit 🚀! DD Package below https://drive.google.com/file/d/1ZkjjuQMGsf5sU9LhicQR3rDl0iPK72En/view </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:13:56 </td>
   <td style="text-align:left;"> $TSLA  😂 people on here are funny . Elon pays 8 billion in capital gain taxes from the sale of his Tesla shares. Hedge funds are dumping shares all of them 🤣 as they take your money . Who sales that much if they think it&amp;#39;s going higher ?  But ya buy more fan boys. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:13:42 </td>
   <td style="text-align:left;"> $TSLA Asian markets doing good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:12:22 </td>
   <td style="text-align:left;"> $TSLA TIMBER!!!! Another ominous sign for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:11:46 </td>
   <td style="text-align:left;"> $TSLA 1124.87 eod tomorrow 🥃🎆🎇🎆🎇🎉🎆🎆🎆🎆🎇🎇🎇🎉🎉🎉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:10:57 </td>
   <td style="text-align:left;"> $TSLA Likes to put in these 7-9 day consolidations at levels of resistance....But which way will it break?  Prior examples this year were during an overall larger period of consolidation and price suppression.  If we&amp;#39;re in the middle of an overall larger expansion, these smaller consolidations might tend towards breaking higher.  Just a though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:09:30 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:06:28 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Largest Trades Data: 
https://www.youtube.com/watch?v=0Aho2hBtUf4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:03:09 </td>
   <td style="text-align:left;"> $TSLA I know it does not matter but Futes went Green! Its a start </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:01:42 </td>
   <td style="text-align:left;"> $TSLA That User Interface update is absolutely trash. Hid a bunch of useful buttons and replaced them with stupid sh*t you don&amp;#39;t need while driving..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:01:39 </td>
   <td style="text-align:left;"> $TSLA Future&amp;#39;s Turning Green 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:01:23 </td>
   <td style="text-align:left;"> $TSLA when your account goes from $900 profit to $1500 loss in less than 5 minutes 🤦‍♂️ because you don’t sell but when you sell it jumps 10% that day 🙃🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 10:00:04 </td>
   <td style="text-align:left;"> $TSLA saying my prayerz to the most high , 📈. Goodnight everyone ❤️❤️🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:59:29 </td>
   <td style="text-align:left;"> $TSLA  lots of FUD about Elon still selling .... its all LIES  .....  if you want to know of or when Elon sold, all you have to do is go to the SEC Edgar Website and look for his FORM 4.     Here is the link  

https://www.sec.gov/edgar/browse/?CIK=0001318605 

Here is a screen shot:   Pull up the page, then select and Clink on  &amp;quot;Ownership Disclosures&amp;quot;  (see pic)  it pulls up the latest SEC filings.

Elon FINISHED his last batch of sales on 12/28/2021 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:58:08 </td>
   <td style="text-align:left;"> $TSLA 29 is last day for tax loss purposes so that is the reason it was a red day. I expect this to be volatile for next 2 days and start climbing high in January </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:57:44 </td>
   <td style="text-align:left;"> $TSLA Nobody cares that Cathy is selling Tesla shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:57:19 </td>
   <td style="text-align:left;"> $TSLA $1002 by Friday. Play it good fellas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:55:47 </td>
   <td style="text-align:left;"> $TSLA and still crazy cathie continues to sell tesla today while buying garbage with the cash... I think she&amp;#39;s in denial...and pls dont respond with the rebalancing reason...that excuse went out the window months ago.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:53:51 </td>
   <td style="text-align:left;"> $TSLA      lmao  NOBODY cares if Cathy sells 24k shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:53:21 </td>
   <td style="text-align:left;"> $TSLA 

A beautiful bird 🦅 just whispered in my ears and said :

Tesla Stock is going to $1500 🔜 !! 😎👀

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:52:53 </td>
   <td style="text-align:left;"> $TSLA cathie sells Tesla every day yet claims this is going to 4X in a few years. Riiiiiiight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:51:26 </td>
   <td style="text-align:left;"> $TSLA if it were a true breakout it wouldn’t have stopped here...but that’s my personal noob thesis that I’ve been ranting about since last Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:50:26 </td>
   <td style="text-align:left;"> $TSLA bloody pre market then we rip. Put holders gettin fried </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:47:15 </td>
   <td style="text-align:left;"> $TSLA Elon is cashing out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:46:39 </td>
   <td style="text-align:left;"> $TSLA very weird day.. VIX dropped. Volume low. Let’s see what tomorrow brings beating up that downward trend to continue on the long term upward trend. Otherwise a quiet Elon never fails
to bring the good news catalyst. Esp with delivery numbers right here. Yikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:45:16 </td>
   <td style="text-align:left;"> $TSLA it has opened green and dropped from the open and finished red.

Opens red tomorrow and??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:42:52 </td>
   <td style="text-align:left;"> $WOOF Hey @LetsFukinGo, you gonna paper hand $NIO like you did $TSLA  and $WOOF? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:41:46 </td>
   <td style="text-align:left;"> $TSLA it feels soooo good to drop the bag on someone else&amp;#39;s shoulders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:41:14 </td>
   <td style="text-align:left;"> $TSLA just need 1120-1130 tomorrow 😔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:39:54 </td>
   <td style="text-align:left;"> $TSLA I should of looked this up before but why did institutions start dumping shares in Q3.  As of 11/23/21: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:38:27 </td>
   <td style="text-align:left;"> $QQQ Glimpse of Putin and Biden going at it tomorrow. 😆 $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:37:49 </td>
   <td style="text-align:left;"> $TSLA 1200 Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:37:33 </td>
   <td style="text-align:left;"> $TSLA hopefully Tesla will run tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:37:16 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:37:15 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA $NVDA $SPY Rest in peace to the legend... may he continue to pomp eet from the grave :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:36:41 </td>
   <td style="text-align:left;"> $TSLA Resistance at the downtrend line. Pretty obvious spot that is heavily watched. I added today at the 50 day. Would love to see a few more days rest below the downtrend line before moving higher towards the standard double bottom pivot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:35:37 </td>
   <td style="text-align:left;"> $TSLA Newest negative trollbot, @miniscule_ball,  er, whatever they call themselves.  joined 8 days ago.  100% negative.

Also 100% bot. Only question? Rusha or chyna???

Bulls hold and are happy.
Bears troll, hoping  for misery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:35:01 </td>
   <td style="text-align:left;"> $TSLA latexce25cef7fec81ce2b6a9594d1b4580bcTSLA - PUT IDEAS ✅
$SE - PUT IDEAS ✅

CONGRATS TO OUR FOLLOWERS &amp;amp; SUBSCRIBERS 🥂
FOLLOW ME HERE FOR MORE TRADE IDEAS 👈🏻 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:32:18 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Options Analysis Video: 
https://www.youtube.com/watch?v=9i7Q9FtIDeA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:28:33 </td>
   <td style="text-align:left;"> $TSLA I think woods got a self lube problem 💃🏻💦🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:27:51 </td>
   <td style="text-align:left;"> $TSLA did Musk sell shares today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:26:02 </td>
   <td style="text-align:left;"> $TSLA Me Before Tesla Q4 Delivery report on Sunday or Monday 01-03-22 (280K VS 271K expectations) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:25:41 </td>
   <td style="text-align:left;"> $NVDA $AMD $TSLA $BTC.X risk assets about to get  hammered 🤢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:23:56 </td>
   <td style="text-align:left;"> $TSLA duckface woodpecker sold today… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:22:52 </td>
   <td style="text-align:left;"> $TSLA autopilot in rain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:21:30 </td>
   <td style="text-align:left;"> $TSLA when is delivery numbers ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:20:27 </td>
   <td style="text-align:left;"> $TSLA Jay Powell once again kills the market right before he has to come and say &amp;quot;sorry&amp;quot; I f&amp;#39;d up again (re:Fall of 2018)... Watch.  It&amp;#39;s like a scene out of Walking Dead in the ER&amp;#39;s, Urgent Cares and the lines for testing are hundreds of cars long everywhere.  We&amp;#39;re going into another lockdown.  Not because OMI is that bad (there is still Delta out there), but because the numbers justify the crazy psychotic health pros and their equally sadistic Pols to control business and people.  It&amp;#39;s their wet dream come true.  We are in a dystopian nightmare.  And Biden and Harris are MIA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:19:59 </td>
   <td style="text-align:left;"> latex28de6cafb0464b76e43bebf6f9055af3ARKK is a giant amalgamation of shit. 

$TSLA is a Ponzi fraud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:19:14 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA  You drank the new generation future just in two years cause you wanted your 401k grow up non-stop. Want to feel safe and comfy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:18:48 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:14:50 </td>
   <td style="text-align:left;"> $TSLA I am sure Santa will continue to push markets higher for this week. Remember Mar 2020? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:13:40 </td>
   <td style="text-align:left;"> $TSLA cathie sold Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:12:03 </td>
   <td style="text-align:left;"> $TSLA 1150 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:12:03 </td>
   <td style="text-align:left;"> The Piotroski-F score of $TSLA is 7.00. This indicates good health for $TSLA. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:10:43 </td>
   <td style="text-align:left;"> $TSLA The Shorts were out in force in after hours.  Usually they mask their after hours trading with neutral buys.  Tonight they straight up bought in.  Not one green fill in after hours.  The final fill price not included was $1078. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:10:38 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-model-3-from-hertz-large-order-started-arriving-will-be-rolled-out-to-new-markets-next-year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:09:32 </td>
   <td style="text-align:left;"> $TSLA 1150 premarket tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:08:38 </td>
   <td style="text-align:left;"> $TSLA 

CW continues to unload Tesla although her fund is way underweight!

🙏🏻🐉🦅👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:08:34 </td>
   <td style="text-align:left;"> $TSLA i ain’t worried bout nothin bitch I ain’t worried bout nothin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:07:46 </td>
   <td style="text-align:left;"> $TSLA china’s zero covid policy will soon or later force Elon to shut down its Shanghai factory and we have to prepare for a rough ride soon even though we are a Elon bull. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:07:25 </td>
   <td style="text-align:left;"> $TSLA  Elon Musk is currently in Shanghai China at the giga-factory where every 38 seconds a  tesla  Model Y  leaves the plant - He is also going to announce a 2nd Giga factory to double the 1 million cars sold this year ( China sales ) and will be using China as an export hub -   GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:03:06 </td>
   <td style="text-align:left;"> $AMC $GME $SAVA $TSLA thought I would share an interesting article... https://www.linkedin.com/pulse/dtcc-weaponize-chill-freeze-meme-stocks-tale-quid-pro-a-p- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:03:03 </td>
   <td style="text-align:left;"> $TSLA permabulls happy at a 1.7k short close out eod lmaooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:02:58 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=uy2ic7uRIdA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:02:56 </td>
   <td style="text-align:left;"> $TSLA lessons learnt never do PUTS on Tesla… this is a running machine only uptrend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:02:05 </td>
   <td style="text-align:left;"> $TSLA 
1200 now here in SoCal 

🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:02:02 </td>
   <td style="text-align:left;"> $TSLA 
So this cocksucker is still selling more stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:01:33 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:00:50 </td>
   <td style="text-align:left;"> $TSLA lol not so fast crack whores! I’ll sleep a lil easier now after that! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 09:00:50 </td>
   <td style="text-align:left;"> $TSLA 

That green candle in the last moment in after hours just now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:59:31 </td>
   <td style="text-align:left;"> $TSLA rather see red through premarket for a change. Up too much premarket has always made me nervous going into opening bell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:59:26 </td>
   <td style="text-align:left;"> $TSLA has had an epic run the last few years.

As 2022 approaches check out the article below,  where @Wedbush Analyst discusses y $TSLA will continue higher.

Do you agree? Will $LCID $RIVN $NIO put a dent in $TSLA?

via @TipRanks 

https://www.tipranks.com/news/article/tesla-outlining-the-2022-bull-case/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:58:48 </td>
   <td style="text-align:left;"> $TSLA we&amp;#39;ll play 10s, we&amp;#39;ll play 30s.. but the day is coming where nobody will be playing.😉🙃🌄 listen for the whistle we are in the train. eagle waits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:58:21 </td>
   <td style="text-align:left;"> $TSLA after ah i might eat ice cream in a long time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:57:50 </td>
   <td style="text-align:left;"> $TSLA now we see profit taking next week and ride it all the way down to $550 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:57:20 </td>
   <td style="text-align:left;"> $TSLA the 28th was the last day Elon sold, people just got caught up in the new saying he was selling more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:57:03 </td>
   <td style="text-align:left;"> $TSLA why the hell it keeps dropping. I shouldn&amp;#39;t have bought it at 1095 smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:56:33 </td>
   <td style="text-align:left;"> $SPCE Matter of time before Branson sells this to Bezos or Musk $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:56:32 </td>
   <td style="text-align:left;"> $TSLA   I believe Elon is done ... the math adds up, this chart (pic below) was made on 12/22 ...... and look in the purple box, 1.5m remaining

now look real time, he exercised those remaining  1.5m  on 12/28 - SEC Form 4 filed.   which means he should be done done, and done  

I  will be shocked to find another SEC Form 4 tonight after 8pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:56:08 </td>
   <td style="text-align:left;"> $TSLA ggpi polestar check it out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:55:56 </td>
   <td style="text-align:left;"> $TSLA its is now over $1890 in kabul🐐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:55:02 </td>
   <td style="text-align:left;"> $TSLA 1250 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:54:36 </td>
   <td style="text-align:left;"> $TSLA so might be a dumb question but what if Elon sold one more tranche today.  I don&amp;#39;t think he did just throwing that out there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:53:29 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:53:05 </td>
   <td style="text-align:left;"> Elon Musk: Tesla Bot could develop a unique personality and become a companion - Electrek $TSLA  https://apple.news/A45ZrSPgYQ5-G1C3d9vxfBA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:51:18 </td>
   <td style="text-align:left;"> $TSLA SMOKING ON THAT SPACE X FUCK ALL U BROKE BEARS WE GOING TO THE MOON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:50:04 </td>
   <td style="text-align:left;"> $TSLA moral of the story: Don&amp;#39;t take investing advice from stocktwits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:49:28 </td>
   <td style="text-align:left;"> $TSLA After hours sellers are stupid. Premarket gap up. Free money. 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:49:15 </td>
   <td style="text-align:left;"> $TSLA what a jerkoff day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:49:09 </td>
   <td style="text-align:left;"> $TSLA MY Calls Are Officially Worthless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:48:14 </td>
   <td style="text-align:left;"> $TSLA OMG Why Do I Always Buy Calls at Worst Time SMH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:47:55 </td>
   <td style="text-align:left;"> $TSLA  1078⬇️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:47:25 </td>
   <td style="text-align:left;"> $TSLA continues to amaze as it&amp;#39;s now over a trillion dollar company. Elon seems to be about done selling and the stock&amp;#39;s had a pretty decent rebound the past week with the MACD crossing. Hit some resistance on the trendline drawn though. Risky to go long up here imo until that trendline breaks. Over 1120 its upside targets are 1175, 1200, then ath around 1250+. On the weekly chart it looks like it&amp;#39;s in a bull flag that should send it up to 1500 area once it breaks out over the ath, but as it needs to break that resistance line first or it could consolidate for a long time like it did for the first 8 months of 2021 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:46:57 </td>
   <td style="text-align:left;"> $TSLA Jesus I shouldn’t have held those 1/7 1130s overnight.  That was fuckn stupid… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:46:28 </td>
   <td style="text-align:left;"> $TSLA I like the stock but looks to me like its the top of the right shoulder. Elon selling and a &amp;#39;leaked&amp;#39; mail from him recently suggests earnings will not be good. Took small number of OTM puts for post earnings but actually my main play close to earnings will be puts on the pretend car makers, LCID &amp;amp; RIVN, maybe FSR if they are over 18 at the time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:46:20 </td>
   <td style="text-align:left;"> $TSLA Elon going to Tweet the deats and then we will moon rocket because Elon is the leader. Rockets to the moon, apes holding with diamond hands. 🚀 Major bullshit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:45:16 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ The market is open Friday everyone. Why does everyone think tomorrow is the last trading day? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:44:53 </td>
   <td style="text-align:left;"> If you&amp;#39;ve been following me for a while, you know i don&amp;#39;t trade trendline breaks. 
$TSLA is trading right under a down trending trendline. It has been added to my watchlist to see if it can build a cheat area post trendline breakout (orange bars).
That will get me interested. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:43:09 </td>
   <td style="text-align:left;"> $TSLA $1500 here we come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:42:57 </td>
   <td style="text-align:left;"> $TSLA could gap down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:42:14 </td>
   <td style="text-align:left;"> $TSLA i for one will not be sleeping with options overnight but puts looks promising </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:39:37 </td>
   <td style="text-align:left;"> $TSLA so is the nasdaq just going to keep dumping while s&amp;amp;p and dow make ATH? dont get it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:38:50 </td>
   <td style="text-align:left;"> $TSLA What? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:38:00 </td>
   <td style="text-align:left;"> $TSLA Futes up bigly!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:36:54 </td>
   <td style="text-align:left;"> $TSLA Daily lookin&amp;#39; pretty clear... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:36:52 </td>
   <td style="text-align:left;"> $TSLA Elon has &amp;#39;Completed&amp;#39; ALL exercises in his 2012 options compensation awards  ....  AND he has Completed  ALL SALES  ...... 

You can stop looking for SEC FORM 4s  now.   The stock is Free from Elon, and it is now being controlled by MMs, shorts, longs, and all regular market forces .

Today was the 1st day, free from the Elon Overhang.   You will now see swings up, and swings down, in the same trading day.  (just like today)

Relax, plan your trades, and execute your plans.
Know the upcoming catalysts.

I personally remain,  BULLISH  AF, but recognize, there will be down and up days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:35:32 </td>
   <td style="text-align:left;"> $TSLA Dropping it seems because SPY is tanking ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:32:46 </td>
   <td style="text-align:left;"> $TSLA Waiting for the Elon’s tweet, “Selling is completely done”. Tomorrow $1150. 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:32:38 </td>
   <td style="text-align:left;"> Tesla&amp;#39;s PT raised by Argus to $1,313.00. buy rating. https://www.marketbeat.com/r/1692646 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:32:17 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-29 Technical Analysis Video: 
https://www.youtube.com/watch?v=GMQxgDrix7Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:31:31 </td>
   <td style="text-align:left;"> $TSLA bull analyst who has been correct over and over again on the stock raises PT: nobody gives a flying fuck. Bear analyst who has been wrong over and over again on the stock lowers PT: everyone gets fucking scared. 

What a fucking joke. Sick of this fucking trash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:31:31 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:30:24 </td>
   <td style="text-align:left;"> $TSLA looking forward to the last trading-day before sales numbers are out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:28:13 </td>
   <td style="text-align:left;"> $TSLA  Mega pumper Elon is silent on twitter not talking about share price
Or tesla. This could mean either
1) BEST ever quarter with close $1M annual delivery numbers with some surprises about new product/split
2) WORST quarter due to supply chain issues and 1st loss/even quarter

50:50.

Tesla means Elon. Nothing else. Actually its bad for tesla.  Will wait til EOW for buying calls for 1/22. Weeklies are horrible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:27:48 </td>
   <td style="text-align:left;"> Tesla given $830.00 PT by Credit Suisse Group AG. https://www.marketbeat.com/r/1692583 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:27:47 </td>
   <td style="text-align:left;"> Tesla given $950.00 PT by Royal Bank of Canada. https://www.marketbeat.com/r/1692586 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:27:28 </td>
   <td style="text-align:left;"> $TSLA wow looks like I am fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:26:22 </td>
   <td style="text-align:left;"> $TSLA high for the week 1119, low 1064. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:25:46 </td>
   <td style="text-align:left;"> $TSLA Look at some of these crazy people  as of today buying calls and puts for Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:25:18 </td>
   <td style="text-align:left;"> $TSLA that’s what gets me pissed off. Where did all the pumpers/bulls go??? I’m bullish, but know how to be realistic. It’s sad that they post so much BS, and then disappear when the stock goes down. Like I said before, Elon isn’t done selling yet. Hopefully he should be done by Friday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:23:51 </td>
   <td style="text-align:left;"> $TSLA has a 4 day rally after getting shit on for 6 weeks and it has to “cool off” the tesla of old is fucking dead. What a sad story… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:23:24 </td>
   <td style="text-align:left;"> $TSLA does this look good? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:23:04 </td>
   <td style="text-align:left;"> $TSLA #Tesla 4 hour update from 29 December at www.elliottwave-forecast.com shows the stock turning higher from blue box as expected. If long from the blue box, position is already risk free #elliottwave #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:22:43 </td>
   <td style="text-align:left;"> IF YOU ARE MISSING MY REAL TIME ALERTS SEE MY BIO. Another great day for 1000s of our members. My #1 rule is follow the liquidity UP OR DOWN! Tons of great alerts today: $NEW $PIXY $NVAX $MARA $TSLA. Losers on YGMZ and MFIT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:22:40 </td>
   <td style="text-align:left;"> $TSLA #Tesla 4 hour update from 29 December at http://bit.ly/1o97qwz shows the stock turning higher from blue box as expected. If long from the blue box, position is already risk free #elliottwave #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:21:47 </td>
   <td style="text-align:left;"> $TSLA when are they releasing the delivery numbers? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:21:28 </td>
   <td style="text-align:left;"> $TSLA #Tesla 4 Hour update from 28 November at www.elliottwave-forecast.com looking for the stock to drop into the 100% extension blue box area before finding support for 3 waves rally at least #elliottwave #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:21:20 </td>
   <td style="text-align:left;"> $TSLA The longer this crap drags on, the more of a (unlikely) parabolic spike this will have to make to save my 1/28/22 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:20:59 </td>
   <td style="text-align:left;"> $TSLA #Tesla 4 Hour update from 28 November at http://bit.ly/1o97qwz looking for the stock to drop into the 100% extension blue box area before finding support for 3 waves rally at least #elliottwave #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:20:47 </td>
   <td style="text-align:left;"> $TSLA 1160 breakeven for my call that expires Friday. Am I fucked? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:19:37 </td>
   <td style="text-align:left;"> $TSLA after this friday exp probably wont be trading tesla for a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:19:28 </td>
   <td style="text-align:left;"> $TSLA doesnt like to stay up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:19:03 </td>
   <td style="text-align:left;"> $TSLA so what will bidenstein do with elons $11b tax he paid?? Build back better?🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:18:21 </td>
   <td style="text-align:left;"> $TSLA Bigger the consolidation, bigger the move 😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:17:03 </td>
   <td style="text-align:left;"> $TSLA I will buy tomorrow 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:15:13 </td>
   <td style="text-align:left;"> $TSLA what a fucking joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:13:41 </td>
   <td style="text-align:left;"> $ENPH $PLUG $SPWR $TSLA 

If Democrats want to save Build Back Better, it must be paid for in full

Much of the attention since Manchin&amp;#39;s announcement has focused on what&amp;#39;s in and what&amp;#39;s out. Those decisions will be difficult, but regardless of the specific policy compromises that will be necessary to get the bill over the finish line, Manchin laid down one overall marker that should serve as the guiding principle for rebuilding the BBBA: ensure that its provisions are fully and transparently funded over the long-term. 

That is not the case with the version that passed in the House. In an effort to enact as many new or expanded programs as possible while keeping the official 10-year cost to about $2 trillion without increasing 10-year budget deficits, House Democrats chose to simply end (sunset) several key provisions after a few years while offsetting them with permanent revenue increases.

https://thehill.com/opinion/white-house/587499-if-democrats-want-to-save-build-back-better-it-must-be-paid-for-in-full </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:13:15 </td>
   <td style="text-align:left;"> I ❤ Dan ✔ Enjoy the Armageddon Depression my friends, followers, haters and those on block for jawboning stupid 😈 https://www.cnbc.com/video/2021/12/29/satori-fund-founder-dan-niles-on-why-hes-bullish-on-energy-and-financials-in-2022.html  ...   https://www.cnbc.com/video/2021/12/29/watch-cnbcs-full-interview-with-satori-funds-dan-niles-on-markets-and-inflation.html   $ccl $tsla $f  $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:11:53 </td>
   <td style="text-align:left;"> $TSLA This is looking nice. January is about to be crazy everybody.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:10:42 </td>
   <td style="text-align:left;"> $TSLA If you want to add emotions with your trading, just buy and uninstall your app and open it after 3-5 yrs, thank me later

Once again, THIS IS SHORT TERM

Do you guys HONESTLY think tesla will be less than here in 5 yrs with more than 5 catalysts coming?  These NUMEROUS bear posts are just ridiculous and have no basis, even the pros on mainstream media </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:09:02 </td>
   <td style="text-align:left;"> $TSLA still don’t understand why this pumps 20 dollars pre market the past 3 days and close lower we all got fucking played $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:08:30 </td>
   <td style="text-align:left;"> $TSLA 1060 break even for this Friday. how screwed and I? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:08:11 </td>
   <td style="text-align:left;"> $TSLA .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:07:55 </td>
   <td style="text-align:left;"> $TSLA Red to Green move:  -2.24%  to +0.07% https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan&amp;amp;type=redtogreenDaily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:06:06 </td>
   <td style="text-align:left;"> $TSLA 
Ummm Good news Bulls
For 2 days now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:05:41 </td>
   <td style="text-align:left;"> $TSLA  I I starting to doubt myself..... tesla and appl can&amp;#39;t make the breakthrough..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:05:38 </td>
   <td style="text-align:left;"> $TSLA market is painted red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-30 08:05:30 </td>
   <td style="text-align:left;"> $TSLA We need a green day tomorrow. </td>
  </tr>
</tbody>
</table></div>

---
