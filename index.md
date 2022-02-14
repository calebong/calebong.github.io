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



Last Updated: 2022-02-14 09:42:31 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-02-14 09:31:04 </td>
   <td style="text-align:left;"> Australia Shares Rise on Energy, Gold Boost </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index rose 0.2% to around 7,230 on Monday, as stronger oil and gold prices drove energy and gold stocks higher, outweighing losses in technology firms. Rising tensions between Russia and Ukraine spurred fears of disruptions in energy flows and demand for safe-haven bullion, driving gains in Australian commodity stocks including Northern Star (8%), Newcrest Mining (5%), Evolution Mining (8.7%), Woodside Petroleum (3.6%) and Santos Ltd (4.2%). The “Big Four” banks also jumped between 0.7% to 3.6% as top central banker Philip Lowe said last week it was plausible interest rates could rise later this year. Meanwhile, Australian tech firms tracked US peers lower, with losses from Brainchip (-6.5%), Carsales.com (-1.6%) and Appen Ltd (-3.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/construction-pmi </td>
   <td style="text-align:left;"> 2022-02-14 09:16:00 </td>
   <td style="text-align:left;"> Irish Construction Output Growth Picks Up </td>
   <td style="text-align:left;"> The Ulster Bank Construction PMI in Ireland jumped to 56.1 in January 2022 from an 8-month low of 53.7 in the prior month. The latest reading marked the ninth straight month of growth in construction activity, with all three categories rising.  Commercial posted the fastest expansion as the rate of growth hit a 3-month high. New orders grew for the 10th month running and at a faster pace, while buying activity rose the most since July last year. In addition, employment gained for the 19th straight month and at a marked rate. Meantime, input costs continued to increase substantially amid severe disruption to supply. The usage of sub-contractors by Irish construction firms increased, but there was again a sharp fall in their availability, contributing to a further steep rise in the rates they charged. Finally, sentiment strengthened to a near 3-1/2-year high, on improving demand conditions and optimism that the pandemic will not prove disruptive to operations during 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-14 09:15:19 </td>
   <td style="text-align:left;"> US Futures Inch Up After a Volatile Week </td>
   <td style="text-align:left;"> US stock futures inched higher on Monday as investors continued to assess brewing tensions between Ukraine and Russia and the outlook for monetary policy. Dow and S&amp;P 500 futures gained about 0.2%, while Nasdaq 100 futures rose 0.1%. The moves came after a volatile week for stocks, which were pressured by a hot inflation report and fears of a Russian invasion on Ukraine. The tech-heavy Nasdaq slumped 2.18% last week, the S&amp;P 500 fell 1.82% and the Dow lost 1%. US inflation accelerated to a 40-year high of 7.5% in January, driving the benchmark 10-year yield above 2% for the first time since 2019 and prompting St. Louis Fed president James Bullard to call for a bigger rate hike, expecting a full percentage point increase by July. Investors also assessed geopolitical risks after the White House warned that war in Ukraine could begin “any day now” and urged Americans there to leave “immediately.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/total-vehicle-sales </td>
   <td style="text-align:left;"> 2022-02-14 09:09:59 </td>
   <td style="text-align:left;"> India Passenger Vehicles Sales Jump 15.9% MoM in January </td>
   <td style="text-align:left;"> Total passenger vehicles sales in India surged 15.9 percent from the previous month to 254,287 units in January 2022, accelerating sharply from a 1.8 percent rise in the previous month, despite a global shortage of semiconductors that continued to hurt the auto sector. On a yearly basis, car sales fell 8.1 percent. "Sales in the month of January 2022 again declined compared to January 2021, due to both Omicron related concerns and semi-conductor shortages. On the other hand, passenger vehicle segment is unable meet the market demand due to supply side challenges resulting sales in January 2022 being even lower than January 2021." said Rajesh Menon, Director General, Society of Indian Automobile Manufactures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/13/business/media/coinbase-crypto-super-bowl-commercials.html </td>
   <td style="text-align:left;"> 2022-02-14 08:57:42 </td>
   <td style="text-align:left;"> Crypto companies weren’t the only advertising first-timers. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                         ,  Tiffany Hsu                                                                                                                                                                                                                                                                                                                                                                                          , Virtual currency companies have drawn much of the attention with their debut in the Super Bowl this year (that floating Coinbase QR code!), but several other categories had fresh entrants, too.                                                                                                                                                                                                     , As states and sports leagues embrace sports betting, a surge of ads for betting apps has followed. The Super Bowl will showcase several commercials, including one from DraftKings involving a daredevil Lady Luck. Caesar’s Sportsbook filled its ad with the actor JB Smoove as Julius Caesar, the actress Halle Berry as Cleopatra and the Manning family of football stars as their dinner guests., “The category is starting to play on a national level, whereas historically, based on the rollout of legalization, it was more of a local play,” said Jeremy Carey, the managing director of the sports marketing agency Optimum Sports. “Now they’ve gotten to a threshold where there’s efficiencies to be had on a national level.”                                                                , Commercials also pushed viewers to care for their bodies.                                                                                                                                                                                                                                                                                                                                             , Cue Health, which makes an at-home Covid-19 test, tapped the actress Gal Gadot to voice part of its upcoming inaugural Super Bowl spot. Hologic, in its first game-time ad in its 36-year history, asked the singer Mary J. Blige to stress the importance of women keeping up with their health screenings.                                                                                          , “In the moment we’re in in time, health and wellness is absolutely more at the forefront of everybody’s mind-share,” said Jane Mazur, Hologic’s vice president of communications. “We’re not a car, we’re not a chip, we’re not a beer, but we are bringing information to the audience that I think will resonate.”                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-14 08:35:00 </td>
   <td style="text-align:left;"> China 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> China 10 Year Government Bond Yield increased to a 4-week high of 2.857%, amid prospects of aggressive tightening by the US Fed and other major central banks. That said, the People’s Bank of China went in the opposite direction as growth momentum in the world's second-largest economy has been slowing since early 2021, due to COVID-19 flare-ups and the regulatory tightening effects. The central bank recently cut several key short- and medium-term interest rates, with analysts expecting more easing measures in the coming months including a 50 bps cut in the reserve requirement ratio. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rubber </td>
   <td style="text-align:left;"> 2022-02-14 08:30:00 </td>
   <td style="text-align:left;"> Rubber Hits 33-week High </td>
   <td style="text-align:left;"> Rubber increased to a 33-week high of 239 JPY/Kg, amid a weaker yen and higher oil prices along with expectations of stronger demand. The factories in China are restarting production after the Lunar Year Long Weekend while there are signs that the automotive chips shortage is easing. Automakers, including General Motors, Ford Motor, and Hyundai Motor, predict a near two-year chip constraint will ease in the second half of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-14 08:26:12 </td>
   <td style="text-align:left;"> Ireland 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Ireland 10 Year Government Bond Yeld increased to a 3-year high of 0.893% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-14/hong-kong-in-crisis-survival-rates-improving-virus-update?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-14 08:22:51 </td>
   <td style="text-align:left;"> Hong Kong in ‘Crisis’; Survival Rates Improving: Virus Update </td>
   <td style="text-align:left;"> Residents queue at a Covid-19 testing facility in the Tin Shui Wai area of Hong Kong, on Feb. 10.                                                                                                                                                                     , Hong Kong health officials warned of a “crisis” as a record 2,000 preliminary positive cases threatened to overwhelm hospitals and upend the government’s Covid Zero strategy.                                                                                        , The gap is widening between Covid infections and deaths, with effective vaccines and milder variants helping improve survival rates dramatically. Bloomberg’s new analysis shows that, in country after country, the link between infections and deaths is uncoupling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-02-14 08:10:01 </td>
   <td style="text-align:left;"> Heating Oil Hits 7-1/2-year High </td>
   <td style="text-align:left;"> Heating Oil increased to a 7-1/2-year high of 2.9515 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-02-14 08:04:15 </td>
   <td style="text-align:left;"> Nikkei 225 is down by 2.01% </td>
   <td style="text-align:left;"> Nikkei 225 decreased 2.01% to 27140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-02-14 08:04:00 </td>
   <td style="text-align:left;"> Gasoline Hits 7-1/2-year High </td>
   <td style="text-align:left;"> Gasoline increased to a 7-1/2-year high of 2.7648 USD/Gal, as traders continued to monitor Iran's nuclear talks against an increasingly tight global oil market. The resumption of the negotiations with Iran could mean the return of Iranian oil to international markets, which is easing some of the momentum in oil and gasoline futures. Meanwhile, demand is running hotter than models had forecasted and the previously expected market surplus in the first quarter of the year now seems more distant. Crude oil stockpiles have stayed on a downward trend, as oil producing countries failed to meet OPEC+ output targets and despite President Biden’s Strategic Petroleum Reserve release. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-14 08:04:00 </td>
   <td style="text-align:left;"> Crude Oil Hits 7-year High </td>
   <td style="text-align:left;"> Crude Oil increased to a 7-year high of 94.69 USD/Bbl, following comments from the US about an imminent attack by Russia on Ukraine as National Security Adviser Jake Sullivan said an invasion could begin "any day now". Last week, the International Energy Agency said that if the persistent gap between OPEC+ output and its target levels continues, supply tensions will rise. Meantime, Saudi Arabia and the United Arab Emirates were pointed as the OPEC members with spare capacity able to pump more crude. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-02-14 08:04:00 </td>
   <td style="text-align:left;"> Brent Hits 7-year High </td>
   <td style="text-align:left;"> Brent increased to a 7-year high of 95.67 USD/Bbl, amid elevating fears that a possible invasion of Ukraine by Russia could trigger sanctions from US and Europe and disrupt energy exports from the world's top producer. The upward pressure on prices was already present earlier after the IEA said supply tensions will rise if the persistent gap between OPEC+ output and its target levels continues. The IEA also pointed out that Saudi Arabia and the United Arab Emirates could pump more oil as they still have spare capacity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60366054?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-14 08:01:54 </td>
   <td style="text-align:left;"> Big banks fund new oil and gas despite net zero pledges </td>
   <td style="text-align:left;"> Big banks are pumping billions into new oil and gas production despite net zero pledges, campaigners have said.                                                                                                                                                                                   , Banks including HSBC, Barclays and Deutsche Bank are still backing new oil and gas despite being part of a green banking group, ShareAction said.                                                                                                                                                 , Investors should force banks to demand green plans from fossil fuel firms before funding them, it said.                                                                                                                                                                                           , HSBC and Barclays said they were focused on achieving environmental goals.                                                                                                                                                                                                                        , "Net zero" means not adding to greenhouse gases already in the atmosphere by cutting and trying to balance out emissions.                                                                                                                                                                         , If the Earth is to avoid damaging environmental effects, including more extreme weather, it needs to limit average global warming to below 1.5 degrees centigrade.                                                                                                                                , To achieve this, we need to get to net zero by 2050, experts have said.                                                                                                                                                                                                                           , As part of getting to net zero, the International Energy Agency has said there should be no new oil and natural gas fields.                                                                                                                                                                       , But big banks are continuing to fund oil and gas expansion with billions of dollars, ShareAction said, despite being part of a UN-led group called the Net Zero Banking Alliance.                                                                                                                 , HSBC put an estimated $8.7bn (£6.4bn) into new oil and gas in 2021, while Barclays put in $4.5bn, and Deutsche Bank loaned $5.7bn, the campaign group estimated.                                                                                                                                  , The fossil fuel giants receiving the funding included Exxon Mobil, Shell, BP, and Saudi Aramco.                                                                                                                                                                                                   , This is a big drop from 2020, when HSBC alone pumped more than $18bn into new oil and gas, and there were big drops in funding across the board between 2020 and 2021, according to figures from consultancy Profundo.                                                                            , ShareAction said this was due to banks focussing on providing pandemic-related loans to keep fossil fuel firms afloat during the pandemic, and that in 2021 funding returned to pre-pandemic levels.                                                                                              , Since joining the Net Zero Banking Alliance last year, 24 big banks have provided $33bn for new oil and gas projects, with more than half of that amount ($19bn) coming from four of the founding members - HSBC, Barclays, BNP Paribas and Deutsche Bank, the campaigners said.                  , ShareAction urged big investors to demand that banks restrict finance for oil and gas expansion, saying funding new oil and gas is a lose-lose for banks and investors.                                                                                                                           , Xavier Lerin, ShareAction senior research manager, said: "If oil and gas demand decreases in line with 1.5C scenarios, prices will fall and assets will become stranded.                                                                                                                          , "On the other hand, if demand does not fall enough to limit global warming to 1.5C, the economy will suffer from severe physical climate impacts.                                                                                                                                                 , "Either way, value will be destroyed for energy companies, banks and their investors."                                                                                                                                                                                                            , The campaign group added: "Banks say that they want to help their clients to transition away from fossil fuels, but there is little evidence for this claim."                                                                                                                                     , "Most banks - HSBC included - are not demanding transition plans from clients, raising doubts about their commitment to this transition," it added.                                                                                                                                               , But an HSBC spokesman said the bank was "committed to working with our customers to achieve a transition towards a thriving low carbon economy".                                                                                                                                                  , The bank published its policy to phase out funding coal for energy production in December, and said its oil and gas net zero financing plans would be published on 22 February in its annual report.                                                                                              , Barclays said it "continues to engage with a broad range of stakeholders on climate and sustainability topics".                                                                                                                                                                                   , "We continue to focus on our ambition to become a net zero bank by 2050, and our commitment to align our financing with the goals and timelines of the Paris Agreement," a spokeswoman said.                                                                                                      , Barclays has a target of a 15% reduction in financed emissions from energy, including coal, oil and gas, by 2025.                                                                                                                                                                                 , "We also have restrictions around the direct financing of new oil and gas exploration projects in the Arctic or financing for companies primarily engaged in oil and gas exploration and production in this region," the spokeswoman added.                                                       , A Deutsche Bank spokesman said: "Carbon intensive sectors account for only a small share of our loan book and based on publicly available data our lending and underwriting activity in fossil fuels is significantly smaller than global peers'.                                                 , "Moreover, our aim is to support all of our customers as we transition to a net zero world."                                                                                                                                                                                                      , Deutsche Bank said it was "well under way" to hitting green and social targets of €200bn (£170bn) by 2023, including "an intense dialogue with clients to move from high-carbon business models towards low and no-carbon ones".                                                                  , The spokesman added: "We have committed to align the operational and attributable emissions from our portfolio with pathways to net-zero by 2050 or sooner.                                                                                                                                       , "This includes measuring and subsequently disclosing the carbon intensity of our loan portfolio and developing and disclosing plans to adjust its footprint in accordance with national and international climate targets by end of this year."                                                   , BNP Paribas, which was also named in the ShareAction report, said: "As the leading bank in continental Europe, BNP Paribas is a major financier of European energy companies that are largely committed to transitioning their model through strong investments in developing renewable energies.", The bank said it is "convinced that these players, due to their technical and financial capacities, have the levers necessary to accelerate transition by developing renewable energy and other transformative solutions".                                                                        , Meanwhile, oil giant Exxon Mobil said that the International Energy Agency and the UN's Intergovernmental Panel on Climate Change "agree that significant investment in oil and gas is still needed in Paris-aligned scenarios".                                                                  , It said that even in the IEA net zero scenario, "additional investment of approximately $11tn through 2050 would be required in both oil and natural gas development to meet the world's energy demand".                                                                                          , BP said it "has a net zero ambition and we have set out a strategy to deliver it".                                                                                                                                                                                                                , "Resilient hydrocarbons are a core part of our strategy, but we are not aiming to grow our oil and gas production - we expect to see production fall 40% from 2019 to 2030.                                                                                                                       , "We expect to hold investment in oil and gas flat over this decade as output falls, while at the same time expanding our spending in transition growth businesses - including EV charging, convenience, renewables, hydrogen and bioenergy -  to around 50% of the total by 2030," BP added.      , Shell declined to comment, and Saudi Aramco was approached for comment.                                                                                                                                                                                                                           , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                                                                            , The trial of the most notorious Nazi war criminals                                                                                                                                                                                                                                                , Classics Walking in Memphis, A Thousand Miles, Bad Day and more...                                                                                                                                                                                                                                , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/food-inflation </td>
   <td style="text-align:left;"> 2022-02-14 07:46:56 </td>
   <td style="text-align:left;"> New Zealand Food Inflation at 10-Year High </td>
   <td style="text-align:left;"> Food prices in New Zealand increased 5.9 percent year-on-year in January of 2022, accelerating from 4.5 percent in the previous month and the highest since August of 2011. Costs rose for the most for fruit and vegetable prices (15 percent) and meat, poultry, and fish (5.7 percent). Prices also increased for restaurant meals and ready-to-eat food prices (5.1 percent) and grocery food prices (4.3 percent). On a seasonally adjusted monthly basis, food costs rose 1.1 percent, largely due to fruit and vegetables (6 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60369879?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-14 07:42:19 </td>
   <td style="text-align:left;"> HMRC seizes NFT for first time in £1.4m fraud case </td>
   <td style="text-align:left;"> The UK tax authority has seized three Non-Fungible Tokens (NFT) as part of a probe into a suspected a VAT fraud involving 250 alleged fake companies.                                                                                                                                                                              , HM Revenue and Customs (HMRC) said three people had been arrested on suspicion of attempting to defraud it of £1.4m.                                                                                                                                                                                                               , The authority said it was the first UK law enforcement to seize an NFT.                                                                                                                                                                                                                                                            , NFTs are assets in the digital world that can be bought and sold, but which have no tangible form of their own.                                                                                                                                                                                                                    , The digital tokens, which emerged in 2014, can be thought of as certificates of ownership for virtual or physical assets. NFTs have a unique digital signature so they can be bought and sold using traditional currency or crypto currency, such as Bitcoin.                                                                      , Where Bitcoin has been hailed as a digital answer to currency, NFTs have been touted as the digital answer to collectables, but plenty of sceptics fear they're a bubble waiting to burst.                                                                                                                                         , Traditional works of art such as paintings are valuable precisely because they are one of a kind, but digital files can be easily and endlessly duplicated.                                                                                                                                                                        , With NFTs, artwork can be "tokenised" to create a digital certificate of ownership that can be bought and sold. The tokens can represent a range of real-world objects such as artwork, music and videos.                                                                                                                          , As with crypto-currency, a record of who owns what is stored on a shared ledger known as the blockchain.                                                                                                                                                                                                                           , The records cannot be forged because the ledger is maintained by thousands of computers around the world. NFTs can also contain smart contracts that may give the artist, for example, a cut of any future sale of the token.                                                                                                      , In theory, anybody can tokenise their work to sell as an NFT but interest has been fuelled by recent headlines of multi-million-dollar sales.                                                                                                                                                                                      , An image of a popular internet meme, featuring a two-year-old girl, was sold as a NFT for about $74,000 (£54,000) in September last year.                                                                                                                                                                                          , The picture, dubbed Side Eyeing Chloe, shows young Chloe Clem giving a disapproving look after her mother reveals a surprise trip to Disneyland.                                                                                                                                                                                   , Twitter's founder Jack Dorsey has also promoted an NFT of the first-ever tweet, with bids hitting $2.5m.                                                                                                                                                                                                                           , HMRC said the suspects in its fraud case were alleged to have used "sophisticated methods" to try to hide their identities including false and stolen identities, false addresses, pre-paid unregistered mobile phones, Virtual Private Networks (VPNs), false invoices and pretending to engage in legitimate business activities., Nick Sharp, deputy director economic crime, said the first seizure of an NFT "serves as a warning to anyone who thinks they can use crypto assets to hide money from HMRC".                                                                                                                                                        , "We constantly adapt to new technology to ensure we keep pace with how criminals and evaders look to conceal their assets."                                                                                                                                                                                                        , HMRC said it had secured a court order to detain the seized crypto assets worth about £5,000 and three digital artwork NFTs, which have not been valued, while its investigation continues.                                                                                                                                        , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                                                                                                             , The trial of the most notorious Nazi war criminals                                                                                                                                                                                                                                                                                 , Classics Walking in Memphis, A Thousand Miles, Bad Day and more...                                                                                                                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-14 07:30:00 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield Hits 6-year High </td>
   <td style="text-align:left;"> Japan 10 Year Government Bond Yield increased to a 6-year high of 0.231%, as demand for domestic government debt securities declined amid prospects of higher interest rates in the US. The liquidity auction received bids 2.01 times higher than the offer, falling from 2.07 in the previous auction. Surging yields prompted the Bank of Japan to state it would buy an unlimited amount of 10-year JGBs at 0.25% in an attempt to keep yields below the bank's ceiling of the yield curve-control. Meanwhile, higher than expected inflation from the United States strengthened the case for accelerated policy tightening by the Federal Reserve.
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/services-pmi </td>
   <td style="text-align:left;"> 2022-02-14 07:28:30 </td>
   <td style="text-align:left;"> New Zealand Services Sector Continues to Contract </td>
   <td style="text-align:left;"> The BusinessNZ Performance of Services Index in New Zealand fell to 45.9 in January of 2022 from an upwardly revised 49.8 in the prior month, the sixth straight contraction in the Kiwi services sector. Lower output was seen in all sub-indices, as new orders/business (41.8 vs 52 in December 2021) dropped to its lowest level since May 2020 and activity/sales swung to contraction territory (44.1 vs 50.7). At the same time, employment (48.1 vs 49.1) shrank at the steepest rate since August, while supplier deliveries (43.5 vs 49.8) and inventory levels (47.6 vs 51) also fell back. However, BNZ Senior Economist Craig Ebert said that "the PSI can jag around quite a lot from month to month – upwards and downwards. However, it’s also worth pointing out that the long-term average of the PSI is 53.6, which is starting to feel some distance away. So much for the new traffic light system releasing the brakes on activity." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-13/blackstone-wins-crown-resorts-as-board-accepts-6-4-billion-bid?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-14 07:05:05 </td>
   <td style="text-align:left;"> Blackstone Wins Crown Resorts With $6.4 Billion Takeover Bid </td>
   <td style="text-align:left;"> The Crown casino and entertainment complex in Melbourne. Blackstone made its first approach for Crown in March last year, with an initial offer of A$11.85. That and a subsequent offer in May were rejected as two low.                                   , Harry Brumpton                                                                                                                                                                                                                                             ,  and Peter Vercoe                                                                                                                                                                                                                                          , U.S. private equity giant Blackstone Inc. has won its almost yearlong pursuit of Crown Resorts Ltd. after the troubled Australian casino operator on Monday accepted its A$8.9 billion ($6.4 billion) takeover offer.                                      , Under the offer, Crown shareholders will receive A$13.10 cash per share. The stock rose 2.8% to A$12.74 in early Sydney trading Monday. A meeting to vote on the offer is expected to be held in the second quarter of the year, Crown said in a statement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/13/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-02-14 07:03:14 </td>
   <td style="text-align:left;"> Stock futures are slightly higher as Wall Street weighs Russia-Ukraine tensions, potential Fed rate hikes </td>
   <td style="text-align:left;"> , Stock futures were slightly higher Sunday evening as investors continued to monitor the developing tension between Ukraine and Russia and potential Fed rate hikes.                                                                                                                                                                               , Futures tied to the Dow Jones Industrial Average climbed 83 points, or 0.2%. S&amp;P 500 futures rose 0.1% and Nasdaq 100 futures added 0.05%.                                                                                                                                                                                                        , The moves follow a rocky week for stocks, which were pressured by a hot inflation report and fears of a Russian attack on Ukraine. The Dow and S&amp;P 500 fell 1% and 1.8%, respectively, for the week. The tech-heavy Nasdaq Composite slid more than 2%.                                                                                           , On Friday, the Dow tumbled 503.53 points, or 1.43%. The S&amp;P 500 dropped 1.9% and the Nasdaq Composite shed 2.8%. The declines came as the White House warned that a war in Ukraine could begin "any day now" and urged Americans there to leave "immediately." Oil prices jumped Friday, along with traditional safe havens like Treasurys.       , "The real fear is that China backs Russia and the relationship between China and the U.S. continues to deteriorate," said Robert Cantwell, chief investment officer at Upholdings. "How it changes the U.S. relationships with the other economic superpowers – that's what's really scary and would affect economic outcome."                    , A phone call over the weekend between U.S. President Joe Biden and Russian President Vladimir Putin, in which Biden attempted to dissuade Putin from attacking Ukraine, failed to achieve a breakthrough.                                                                                                                                         , Some airlines have also halted or redirected flights to Ukraine amid the brewing crisis, while the Pentagon ordered the departure of U.S. troops in Ukraine.                                                                                                                                                                                      , Goldman lowers official S&amp;P 500 forecast and also evaluates what a recession would do to stocks                                                                                                                                                                                                                                                   , Conflict playbook: How investors can protect their portfolios if Russia were to invade Ukraine                                                                                                                                                                                                                                                    , Keep these stocks out of your portfolio if inflation continues to rage                                                                                                                                                                                                                                                                            , Traders are also weighing the potential impact of surging inflation on the U.S. economy, as well as the potential measures the Federal Reserve could take to quell the jump in prices.                                                                                                                                                            , The Labor Department reported last week that inflation in January surged 7.5%, its biggest gain since 1982. Rate-sensitive tech stocks were hit hard by the report, which briefly sent the 10-year Treasury yield above 2% — the first time since 2019 that the 10-year traded above that level.                                                  , After the report's release, St. Louis Fed President James Bullard said that he was open to a 50-basis point rate hike next month, adding that he wanted to see a full percentage point of hikes by July. To be sure, San Francisco Fed President Mary Daly said Sunday that the central bank should take a "measured" approach when raising rates., "This past week, the primary story was all about inflation," Cantwell said. "Every single time the inflation number comes out, it keeps surpassing expectations and the while the Fed has signaled that it's going to raise rates, they haven't actually raised them. The longer they wait, the faster they're going to have to raise them."      , Economists at Goldman Sachs also raised their Fed forecast to seven hikes for 2022, and said it sees the 10-year hitting 2.25% this year.                                                                                                                                                                                                         , The firm also lowered its 2022 S&amp;P 500 price target to 4,900 from 5,100. That would represent just a 2.8% return from where the benchmark ended 2021. Goldman said that higher rates will crimp valuations.                                                                                                                                       , Earnings are expected to ramp up again this week, with Nvidia, Walmart, Shopify, AMC and more scheduled to report.                                                                                                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-13/indonesia-skips-early-dollar-bond-sale-to-seek-issuance-window?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-14 07:00:00 </td>
   <td style="text-align:left;"> Indonesia Skips Early Dollar Bond Sale to Seek Issuance Window </td>
   <td style="text-align:left;"> The central business district in Jakarta, Indonesia.                                                                                                                                                                                                                                           , Grace Sihombing                                                                                                                                                                                                                                                                                , Indonesia isn’t in a rush to tap global bond markets this year after skipping its usual January issuance, instead it seeks a window of opportunity amid expected Federal Reserve tightening.                                                                                                   , The government is moving away from its previous strategy of selling early and late in the year and will be “extra careful” in issuing bonds offshore to avoid locking in a high financing burden, said Luky Alfirman, the finance ministry’s director general of financing and risk management. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-13/dbs-profit-tops-estimates-on-higher-loan-growth-fee-income-lift?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-14 06:36:56 </td>
   <td style="text-align:left;"> DBS Profit Tops Estimates on Higher Loan Growth, Fee Income </td>
   <td style="text-align:left;"> A customer uses an ATM at a DBS bank branch in Singapore.                                                                                                                                                                                                   , Faris Mokhtar                                                                                                                                                                                                                                               , DBS Group Holdings Ltd., Southeast Asia’s largest lender, posted a 37% jump in fourth-quarter profit, boosted by its highest loan growth in seven years and increased fee income.                                                                           , Net income climbed to S$1.39 billion ($1.03 billion) in the three months ended Dec. 31, from S$1.01 billion a year earlier, Singapore-based DBS said Monday. That compares with the S$1.36 billion average estimate of three analysts surveyed by Bloomberg. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-13/tokyo-s-bond-traders-brace-for-boj-intervention-amid-haven-bid?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-14 06:21:49 </td>
   <td style="text-align:left;"> BOJ Intervention, Haven Bid Boosts JGBs as Tokyo Traders Return </td>
   <td style="text-align:left;"> The Bank of Japan headquarters at dusk in Tokyo, Japan.                                                                                                                                                                                                                                             , Chikako Mogi                                                                                                                                                                                                                                                                                        , , Masaki Kondo                                                                                                                                                                                                                                                                                      , , and Toru Fujioka                                                                                                                                                                                                                                                                                  , Japanese bonds got a double boost Monday as the central bank undertook unlimited purchases and traders returned from a long weekend to a risk-off mood in global markets.                                                                                                                           , The Bank of Japan offered to buy an unlimited amount of five to 10-year bonds at fixed rates in a bid to cap the recent rise in yields. The plan was announced on Thursday, when most Japanese investors were already well on their way home, and is the first of its type in more than three years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-13/stocks-face-choppy-start-amid-tension-over-ukraine-markets-wrap </td>
   <td style="text-align:left;"> 2022-02-14 06:20:03 </td>
   <td style="text-align:left;"> Stocks Decline, Crude Rallies Amid Ukraine Tension: Markets Wrap </td>
   <td style="text-align:left;"> European Union and Ukrainian flags fly in Kyiv, Ukraine, on Feb. 13.                                                                                                   , Andreea Papuc                                                                                                                                                          , Stocks slid Monday and crude oil extended a rally as geopolitical risks over Ukraine rippled through global markets, spurring demand for havens such as sovereign debt., Japanese equities led declines, South Korea slid and Australia wavered. S&amp;P 500 and Nasdaq 100 futures were stable after sharp Wall Street losses Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-13/hedge-funds-supercharge-aussie-shorts-as-rba-splits-with-fed?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-14 06:04:32 </td>
   <td style="text-align:left;"> Hedge Funds Supercharge Aussie Shorts as RBA Splits With Fed </td>
   <td style="text-align:left;"> Photographer: Sergio Dionisio/Bloomberg                                                                                                                                                                                                                                                                                                                                                                                                       , Ruth Carson                                                                                                                                                                                                                                                                                                                                                                                                                                   , A dovish Reserve Bank of Australia is driving hedge funds to ramp up bets against the nation’s currency as the policy stance increasingly diverges from a hawkish Federal Reserve.                                                                                                                                                                                                                                                            , Leveraged funds have boosted net Australian dollar shorts to the most since November, according to the latest data from the Commodity Futures Trading Commission to Feb. 8. Futures and options speculators piled into positions to benefit from a weaker Aussie after RBA Governor Philip Lowe pledged to remain patient in assessing inflation even as peers in the U.S. and Europe made it clear they will respond to heated price growth.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-13/-100-oil-threatens-to-compound-world-economy-s-inflation-shock?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-14 05:17:50 </td>
   <td style="text-align:left;"> $100 Oil Threatens to Compound World Economy’s Inflation Shock </td>
   <td style="text-align:left;"> Enda Curran                                                                                                                                                                                                                                                                                                                    ,  and Rich Miller                                                                                                                                                                                                                                                                                                               , Oil’s surge toward $100 a barrel for the first time since 2014 is threatening to deal a double-blow to the world economy by further denting growth prospects and driving up inflation.                                                                                                                                         , That’s a worrying combination for the U.S. Federal Reserve and fellow central banks as they seek to contain the strongest price pressures in decades without derailing recoveries from the pandemic. Group of 20 finance chiefs meet virtually this week for the first time this year with inflation among their top concerns.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-13/pboc-s-rate-decision-sparks-debate-as-economy-comes-under-strain?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-14 05:00:00 </td>
   <td style="text-align:left;"> PBOC’s Rate Decision Sparks Debate as Economy Comes Under Strain </td>
   <td style="text-align:left;"> A majority of economists argue that the PBOC can afford to wait and see whether earlier easing measures are taking effect.                                                                                                                                                                                                   , The People’s Bank of China is leaving economists divided over whether it needs to cut interest rates for a second month to boost a faltering economy.                                                                                                                                                                        , Sixteen of the 27 economists polled by Bloomberg forecast the central bank will keep the interest rate on its one-year policy loans unchanged on Tuesday, when it’s scheduled to conduct a monthly medium-term lending facility operation. Six of them expect a 10-basis point cut and another five see a 5-point reduction.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/13/politics/us-economy-pandemic-politics/index.html </td>
   <td style="text-align:left;"> 2022-02-14 04:57:14 </td>
   <td style="text-align:left;"> Most Americans have come out ahead economically in the pandemic, despite inflation - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Public discontent with America's pandemic-battered economy obscures the good news: Even after inflation, most of the country has been coming out ahead.                                                                                                                                                                                                                                                                                  , Red-hot demand for labor means lower-income workers can command wage increases that outpace rising prices. So can middle-income workers who switch jobs.                                                                                                                                                                                                                                                                                       , Relief checks approved by lawmakers of both parties and sent out by Presidents Donald Trump and Joe Biden have given the majority of households a cushion. Those higher up the income scale have seen handsome increases in the values of their homes and investment assets.                                                                                                                                                                   , Even those who fault Biden's policies for exacerbating inflation risks acknowledge that, right now, the pandemic economy continues to offer large, underappreciated rewards.                                                                                                                                                                                                                                                                   , "For most people," concludes Michael Strain, who directs economic policy studies at the right-leaning American Enterprise Institute, "the current economic situation is good."                                                                                                                                                                                                                                                                 , You couldn't tell that from public opinion, though. A CNN poll last week showed that just 37% of Americans approve of President Joe Biden's handling of the economy -- fewer than approve of his handling of crime, relations with Russia or protecting democracy.                                                                                                                                                                             , The highest rate of inflation in four decades -- 7.5% on an annual basis in last week's government data -- explains part of the sour mood. Yet that worrisome milestone is directly related to another, more reassuring one: the highest annual economic growth in four decades, with an unemployment rate of just 4%.                                                                                                                         , Different economists use different measures of economic gains. Inflation looks more threatening when considering 2021 alone, but less so when also incorporating 2020, when initial Covid-19 shutdowns pushed prices down for high-profile expenses such as gasoline.                                                                                                                                                                          , At realtimeinequality.org, economists at the University of California-Berkeley estimate that disposable income for Americans overall increased by 5.3% after inflation from December 2019 to December 2021. Using that measure, which includes the effects of both labor income and Covid relief payments, the bottom 50% of earners saw their disposable income rise by 10.9%, compared with 3.8% for the middle 40% and 4.4% for the top 10%., Examining changes in wages alone, Arin Dube of the University of Massachusetts-Amherst estimates that two-thirds of American workers have seen their wages go up after accounting for inflation over the last two years. Over just the last year -- when inflation accelerated substantially -- roughly one-third of workers have come out ahead, Dube says.                                                                                   , Outsized gains at the bottom of the income scale chip away at inequality and create opportunity for younger workers who fill many lower-skill, lower-paying jobs. The labor market is running hot enough that millions of Americans keep quitting their jobs for higher-paying new ones in what White House economist Bharat Ramamurti calls "The Great Upgrade."                                                                              , More affluent older Americans have benefited from booming real estate and financial markets. Since February 2020, the Dow Jones Industrial Average has risen roughly 19%.                                                                                                                                                                                                                                                                      , To be sure, overall averages conceal the significant chunk of Americans, neither rich nor poor, who have lost ground to inflation in recent months. "There is a missing middle," Dube says.                                                                                                                                                                                                                                                    , It includes small business owners squeezed by higher labor costs, if they can find workers at all. It includes workers who have not switched jobs, settling for the modest pay increases they'd long been accustomed to. It includes renters whose landlords want more when leases expire.                                                                                                                                                     , A recent Wells Fargo analysis showed middle-income consumers were hit the hardest by rising gas and used-car prices. It's most painful for those, without benefit of work-from-home options, who have continued commuting to their jobs.                                                                                                                                                                                                       , The middle 40% of earners, according to the Cal-Berkeley economists, have seen their disposable income erode by 1.1% after inflation over the past year. That group looms especially large in American politics.                                                                                                                                                                                                                               , Public unhappiness incorporates anxiety over the pandemic's continued ability to disrupt economic activity. The fact that most Americans have gained financially doesn't mean they will continue to.                                                                                                                                                                                                                                           , "I'd drive a distinction between 'have benefited' and 'will benefit,' " observes Strain. He fears that the Federal Reserve's attempts to temper inflation through higher interest rates could trigger a recession.                                                                                                                                                                                                                             , Strain was among the relatively few economists who warned a year ago that Biden's $1.9 trillion American Rescue Plan was too big and risked sparking excessive inflation by overstimulating demand. Many others have belatedly accepted the prescience of those warnings.                                                                                                                                                                      , "It was bigger than would've been ideal," says liberal economist Dean Baker of the Center for Economic and Policy Research.                                                                                                                                                                                                                                                                                                                    , Of course, the part of Biden's rescue plan that economists most lament for unnecessarily fueling inflation was also the most politically irresistible. That was the $1,400 Covid-relief checks for single taxpayers earning $75,000 or less and couples earning $150,000 or less.                                                                                                                                                              , The Biden administration has worked for months to ease choke points in the supply chain for scarce goods such as automobiles. But the principal inflation-fighting power lies with the Fed, and Americans unhappy about inflation today may not like tomorrow's higher borrowing costs much better.                                                                                                                                            , "The people screaming for Biden to do something do not want the Fed to raise interest rates," says Betsey Stevenson, a former Obama administration economist now at the University of Michigan. "They want more damn cars."                                                                                                                                                                                                                    , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/13/business/1mdb-trial-roger-ng.html </td>
   <td style="text-align:left;"> 2022-02-14 01:30:07 </td>
   <td style="text-align:left;"> 1MDB Trial Set to Begin for Ex-Goldman Banker Roger Ng - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Roger Ng was indicted in 2018 for his role in the looting of Malaysia’s government fund. His trial starts Monday.                                                                                                                                                                                                                                                                                                                                                                                           , By Matthew Goldstein                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The global scandal over the looting of a big Malaysian infrastructure fund nearly a decade ago — a crime that tarnished the reputation of one of Wall Street’s premier banks — is about to play out once again in a federal courthouse in Brooklyn.                                                                                                                                                                                                                                                         , The criminal money laundering and bribery trial of Roger Ng, a former Goldman Sachs banker, will begin Monday, with opening arguments and federal prosecutors calling their first witnesses.                                                                                                                                                                                                                                                                                                                , The trial comes nearly four years after Mr. Ng, 49, a Malaysian resident, was indicted by federal prosecutors in Brooklyn. And it comes 16 months after Goldman pleaded guilty to a criminal charge and paid $5 billion in fines for its role in the far-reaching foreign corruption bribery scheme.                                                                                                                                                                                                        , Jho Low, the accused mastermind of the scheme to loot more than $4 billion from the big Malaysian fund known as 1MDB, remains a fugitive and is believed to be living in China. Tim Leissner, the former Goldman partner who pleaded guilty in the summer of 2018 and has been cooperating with the government, is expected to be the prosecution’s star witness. He could begin testifying as soon as this week.                                                                                           , Mr. Ng and Mr. Leissner worked together at Goldman in Asia. Mr. Ng is said to have introduced his former partner and others at the bank to Mr. Low in 2009. At the time, Mr. Low was a young and flamboyant businessman who had befriended many Hollywood celebrities. He was known for throwing lavish Las Vegas parties and buying up expensive properties in Los Angeles and New York.                                                                                                                   , Prosecutors have charged that the three men and others plotted to pay $1 billion in bribes to top officials in Malaysia and other countries so that Goldman could arrange $6.5 billion in bond offerings for 1MDB, a government fund that was supposed to pay for projects to benefit the Malaysian people. But instead, prosecutors contend, much of that money was diverted to pay for the bribes and to line the pockets of Mr. Low, Mr. Leissner, Mr. Ng and even the former prime minister of Malaysia., Money looted from 1MDB went to buy a boutique hotel in Beverly Hills, apartment buildings, artwork, a mega-yacht, a grand piano made of clear acrylic that was given to a supermodel as a gift and a share of the EMI Music Publishing portfolio. Some of the money even financed the Hollywood movie “The Wolf of Wall Street.” Most of the purchases were made by Mr. Low.                                                                                                                                , Mr. Leissner, who is married to the fashion designer and model Kimora Lee Simmons, agreed to forfeit up to $43.7 million as part of his guilty plea. One of Goldman’s most powerful deal makers in Asia before the scandal erupted in 2016, Mr. Leissner is expected to appear on the stand for several days once he begins testifying. Given his ties to Mr. Ng and Mr. Low, his testimony is seen as crucial to the government’s case.                                                                    , But Mr. Leissner is likely to face a fierce cross-examination from Mr. Ng’s legal defense team. Lawyers could draw from a dossier that Goldman had put together, presenting Mr. Leissner as a master con artist who had a doctorate from a mail-order diploma mill and had affairs with powerful women in Asia, including a client of the firm’s. The bank gathered the material when it was negotiating its plea deal with prosecutors and bank regulators.                                                , In court filings, prosecutors have acknowledged that Mr. Leissner was deceptive and frequently misled some at Goldman as to whether he was dealing with Mr. Low after being told not to. But authorities have faulted Goldman for accepting those denials at “face value.”                                                                                                                                                                                                                                  , Prosecutors have claimed that Mr. Ng and his family, including his wife, got up to $35 million in illicit proceeds from the 1MDB bond offerings. But Mr. Ng’s defense team intends to present evidence that Mr. Ng was not a critical player in putting together the bond deals and the money came from legitimate unrelated transactions, according to court filings.                                                                                                                                      , His lawyers are expected to argue that Mr. Ng and his family were owed money by Mr. Leissner’s former wife, who owns a large vineyard in China. Mr. Ng, they will contend, was unaware that the money they received came from proceeds that had been diverted from the 1MDB bond offering.                                                                                                                                                                                                                  , It is not known if Mr. Ng will testify on his own behalf.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Goldman Sachs is expected to have lawyers monitoring the proceedings. The bank’s Malaysian subsidiary pleaded guilty to one count of conspiring to violate the federal Foreign Corrupt Practices Act, and the parent company of the bank entered into a three-year deferred prosecution agreement on a similar charge. A number of Goldman employees, mainly from its compliance division, are expected to be called as witnesses.                                                                          , In reaching a deal with prosecutors and regulators, Goldman also took steps to recoup or withhold more than $100 million in executive compensation, including to Lloyd Blankfein, the former chief executive.                                                                                                                                                                                                                                                                                               , The bank also slashed $10 million from the 2020 pay package for David Solomon, who replaced Mr. Blankfein as chief executive officer, in the wake of the guilty plea. But Goldman made up for most of that lost ground by recently approving $35 million in compensation for Mr. Solomon for 2021 — roughly $8 million higher than the $27.5 million he was supposed to have gotten in 2021.                                                                                                                , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/pelosi-inflation-low-unemployment-manchin-not-right-bbb </td>
   <td style="text-align:left;"> 2022-02-13 23:36:41 </td>
   <td style="text-align:left;"> Pelosi blames inflation on low unemployment, says Manchin ‘not right’ on BBB criticism </td>
   <td style="text-align:left;"> Pennsylvania Republican discusses the bipartisan push to ban stock trading in Congress on ‘The Evening Edit.’                                                                                                                                                                                                                                                                                                , House Speaker Nancy Pelosi, D-Calif., said Sunday that skyrocketing inflation is due to more people entering the workforce, and that Sen. Joe Manchin, D-W.Va., is wrong to claim that President Biden’s $1.75 trillion Build Back Better Act would worsen inflation.                                                                                                                                        , During an appearance on ABC’s "This Week," Pelosi was asked by anchor George Stephanopoulos to explain what Democrats in Congress are doing to address rising inflation, which is up 7.5% in the past year, marking the steepest increase in 40 years.                                                                                                                                                       , ELON MUSK WARNS OF SKYROCKETING NATIONAL DEBT: 'SOMETHING HAS TO GIVE'                                                                                                                                                                                                                                                                                                                                       , House Speaker Nancy Pelosi (Chip Somodevilla/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                    , "The fact that people have jobs always contributes to an increase in inflation, and that’s a good thing," Pelosi said. "But inflation is not a good, you know, we have to contain it."                                                                                                                                                                                                                       , "Wages are not keeping up with prices," Stephanopoulos interjected.                                                                                                                                                                                                                                                                                                                                          , "That’s right, and let me just say what Congress has been doing," the congresswoman replied.                                                                                                                                                                                                                                                                                                                 , Pelosi touted the COMPETES Act, which passed the House earlier this month by a 222-210 largely partisan vote and addressed supply chain disruptions exacerbated by the coronavirus pandemic. The bill includes a $52 billion "chips" fund to bring semiconductor fabrication back to the U.S. and a $45 billion investment to ensure critical goods are made in the U.S. rather than relying on China.       , "What contributes to inflation? More people having jobs, scarcity of product, which makes prices go up, and the rest," Pelosi said. "So we passed the Competes Act last Friday – this was a giant step for it."                                                                                                                                                                                              , Pelosi also promoted Biden’s Build Back Better Act, a $1.75 trillion economic and climate package that is all but dead due to Manchin’s opposition in the evenly divided Senate. Manchin said passing BBB would only add fuel to the already burning economy, but Pelosi pushed back Sunday, claiming it is a "deficit reduction bill."                                                                      , Sen. Joe Manchin speaks with reporters outside the Senate Chamber on Capitol Hill on Jan. 20, 2022.  (Kent Nishimura/Los Angeles Times via Getty Images / Getty Images)                                                                                                                                                                                                                                      , "Clearly, he has—," she said, stopping herself. "Look, Joe Manchin, as you said, is the senator that counts, every senator counts, and we have legislation that is so transformative for our country. When you say what President Biden has done and in this year, whether it's the Rescue package that has put money in people's pockets, taken people off of poverty, vaccines in their arms and the rest—", "Yes, but people aren’t feeling it right now," Stephanopoulos interjected. "They’re upset."                                                                                                                                                                                                                                                                                                                  , "I understand that, but there has to be a cumulative effect, a cumulative effect," Pelosi said. "And part of the consequences of all of that investment and the infrastructure bill and the rest is that more people have jobs and therefore inflation goes up."                                                                                                                                             , "Yes, we have inflation," she continued. "It's very important for us to address it, we must bring it down, but it’s not right, with all due respect in the world for my friend Joe Manchin, it's not right to say that what we're doing is contributing to inflation, because it’s exactly the opposite."                                                                                                    , House Speaker Nancy Pelosi gestures during a news conference on Capitol Hill on Feb. 3, 2022. (AP Photo/Evan Vucci / AP Newsroom)                                                                                                                                                                                                                                                                            , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                      , Pelosi also addressed rising crime in her interview, declaring that the stance taken by Rep. Cori Bush, D-Mo., who wants to defund the police, "is not the position of the Democratic Party."                                                                                                                                                                                                                , "Community safety, to protect and defend in every way, is our oath of office," Pelosi said. "Public safety is our responsibility."                                                                                                                                                                                                                                                                           , Fox News' Marisa Schultz contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/13/politics/biden-zelensky-call/index.html </td>
   <td style="text-align:left;"> 2022-02-13 22:55:16 </td>
   <td style="text-align:left;"> Biden and Ukrainian President Zelensky will speak today
 - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)President Joe Biden told Ukrainian President Volodymyr Zelensky in a roughly hour-long call Sunday that the US would respond "swiftly and decisively" if Russia takes further steps toward invasion, according to a White House readout of the call.                                                                                                                                                             , The call came amid US warnings that a Russian invasion of Ukraine could happen as soon as this week.                                                                                                                                                                                                                                                                                                                   , "President Biden made clear that the United States would respond swiftly and decisively, together with its Allies and partners, to any further Russian aggression against Ukraine. The two leaders agreed on the importance of continuing to pursue diplomacy and deterrence in response to Russia's military build-up on Ukraine's borders," according to the White House readout.                                    , A senior Ukrainian official said Zelensky renewed calls for Washington to provide greater military and financial support to Ukraine and asked for Biden to visit Ukraine as soon as possible. US officials said a trip by Biden to Ukraine is extremely unlikely.                                                                                                                                                      , The official, who had been briefed on the conversation, told CNN that Zelensky used the call to suggest what the official described as "concrete ideas to diminish the Russian threat to Ukraine" such as providing Ukraine greater military support, including more advanced weaponry.                                                                                                                                , Zelensky also emphasized to Biden the need for a significant financial package for Ukraine, according to the official. The official told CNN the Ukrainian leader stressed to his US counterpart that strong economic support would -- in the words of the official -- "show Putin that the West stands with Ukraine, and that the impact of Putin's escalation would bear no fruit."                                  , According to the Ukrainian official, Zelensky asked Biden to visit Ukraine as soon as possible, but that there had been no positive response from Biden. US officials said a trip by Biden to Ukraine is extremely unlikely.                                                                                                                                                                                           , When reached for comment by CNN, a White House official noted security assistance to Ukraine is ongoing, highlighted shipments in recent weeks and said the administration is exploring "additional macroeconomic support to help Ukraine's economy" amid the Russian military buildup.                                                                                                                                , Biden and Zelensky last spoke in January and it "did not go well," a senior Ukrainian official told CNN at the time, amid disagreements over the "risk levels" of a Russian attack.                                                                                                                                                                                                                                    , Their latest call Sunday came a day after Biden warned Russian President Vladimir Putin during a call that the US and its allies will respond "decisively and impose swift and severe costs" on Russia should Putin decide to invade Ukraine.                                                                                                                                                                          , Biden's national security adviser Jake Sullivan on Sunday issued a stark warning that the US believes Russia could launch an invasion of Ukraine this week, but is still holding out hope diplomacy can prevail. Sullivan told CNN's Jake Tapper on "State of the Union" that Russian forces are in a place where an invasion could take place before the end of the Beijing Winter Olympics, which end on February 20., The US has estimated that Russia has more than 100,000 troops near the Ukraine border, with thousands added just this week, according to an administration official. As of Saturday, the US had moved some of its forces out of Ukraine and ordered the evacuation of most of its embassy staff on Saturday as fears mount over a possible Russian invasion.                                                           , Sullivan said the US Embassy in Ukraine is "ready to complete the drawdown ... should that become necessary."                                                                                                                                                                                                                                                                                                          , This story has been updated with additional information.                                                                                                                                                                                                                                                                                                                                                               , CNN's Kaitlan Collins contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/13/politics/cnn-poll-biden-trump-2024/index.html </td>
   <td style="text-align:left;"> 2022-02-13 21:01:12 </td>
   <td style="text-align:left;"> CNN Poll: Neither Biden nor Trump has their party's full support for a 2024 run - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)A significant number of both Democrats and Republicans currently hope to see their parties find alternatives to President Joe Biden and former President Donald Trump in the next presidential election, according to a new CNN poll conducted by SSRS. But very few have specific candidates in mind, underscoring how distant -- and potentially mutable -- the 2024 race remains.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The survey, conducted in January and February, found that 45% of Democratic and Democratic-leaning voters wanted to see the party renominate Biden in 2024, while 51% preferred a different candidate. There's more support in the party for Biden among voters 45 and older (52% of whom want to see him as the nominee again), voters of color (55%) and voters without a college degree (51%). There's also a gap between the 48% of self-identified Democrats who want to see Biden renominated and the third of Democratic-leaning independents who felt the same. The 2024 support for Biden is concentrated among his most ardent backers in the party. While 70% of Democratic voters who strongly approve of the way he's handling the job said they'd like to see him renominated, that drops to just 35% among Democrats who said they approve moderately., Across the aisle, Republican and Republican-leaning voters are about evenly split between wanting their party to nominate Trump again (50%) or wanting a different candidate (49%). A majority of Republicans (54%) favored Trump, compared with 38% of Republican-leaning independents. Continued support for the former president within the GOP is also particularly strong among White voters without a college degree (60%) and those who falsely claim Biden's 2020 victory was illegitimate (64%).                                                                                                                                                                                                                                                                                                                                                            , The next presidential primaries are, of course, almost two years away, and these poll findings are no prediction of what the nomination process will look like then. What they do provide is a glimpse of the current state of the parties: Both are divided over whether to rally behind their current flagbearers, but neither has anointed an alternative as yet.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The numbers for both Biden and Trump look tepid compared with past poll results on a similar question. In March 2010, nearly 8 in 10 Democratic and Democratic-leaning voters said they wanted the party to renominate Barack Obama (79%). And in March 2018, Republican and Republican-leaning voters were solidly behind Trump's renomination (77%).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , But the new poll also suggests that the hesitance over both Biden and Trump stems more from electability and other concerns than because their partisans don't want them to be president.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Of those Democratic-aligned voters hoping to see Biden replaced on the ticket, 31% said it was because they didn't want him to be reelected. Thirty-five percent said it was mostly because they doubted Biden's ability to win against a Republican candidate, and the rest offered up other reasons for wanting to switch up the ticket -- the most common (19%) being concerns about Biden's age. (Biden will turn 82 in November 2024.)                                                                                                                                                                                                                                                                                                                                                                                                                          , Democratic-aligned voters also aren't yet gravitating en masse toward any specific alternatives: Only 12% of all Democratic and Democratic-leaning voters wanted to see a nominee who isn't Biden and had a specific alternative in mind. No individual candidate was named by more than 5% of those who didn't want Biden atop the ticket.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , On the Republican side, only 39% of those hoping Trump isn't on the ticket said it's specifically because they don't want to see him as president again. Twenty-two percent said they doubted Trump could win against the Democrats, while 38% had other reasons, including wanting a fresher candidate (9%) or someone less polarizing (7%), or due to concerns over Trump's personality (6%).                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Just 19% of all Republican-aligned voters had a preferred alternative to Trump in mind, the CNN Poll found, while 29% picked "just someone besides Trump." But among those looking for alternatives to Trump, one name stood out: 21% of those voters mentioned Florida Gov. Ron DeSantis, with no other potential candidate getting more than 1%.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Even this early, Americans were more likely to say they were looking forward to the next presidential election (58%) than dreading it (41%). But there's a notable partisan divide: 81% of GOP-aligned respondents, but just 44% of Democrats and Democratic-leaning independents, said they were looking forward to 2024.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The CNN Poll was conducted by SSRS January 10 through February 6 among a random national sample of 1,527 adults initially reached by mail, and is the second survey CNN has conducted using this methodology. Surveys were either conducted online or by telephone with a live interviewer. Results for the full sample have a margin of sampling error of plus or minus 3.3 percentage points.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , CNN's Jennifer Agiesta contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/13/politics/trump-telephone-records-capitol-riot-investigation/index.html </td>
   <td style="text-align:left;"> 2022-02-13 19:00:44 </td>
   <td style="text-align:left;"> Trump's unorthodox phone habits complicate January 6 investigation - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)In Donald Trump's White House, telephones were a valued commodity. The then-President loved to talk to everyone, said a former White House aide.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , "He took everybody's calls," the aide said, even interrupting national security briefings to make and receive calls.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The phone was his lifeline, according to former Trump administration officials.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , And the ex-President's telephone habits have become a problem for January 6 investigators.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , That's because the House select committee looking into the US Capitol riot has discovered an unusual gap in Trump's official White House phone log for multiple hours, according to sources familiar with the House investigation -- from after he returned to the White House from speaking to his supporters at the Ellipse on January 6, 2021, until he spoke via video to the nation from the Rose Garden. And it has got investigators looking elsewhere -- to other people's cell phones and perhaps even to Trump's own cell phones, although the committee has declined to take that uncomfortable step so far. , The difficulty for the committee in tracking down just whom Trump spoke with -- and when -- is dealing with his unorthodox phone habits while in office: According to multiple sources formerly in the administration, the ex-President often used other people's telephones (or multiple phones of his own, sometimes rotated in and out of use) to communicate with his supporters -- and even family.                                                                                                                                                                                                                , One former staffer blamed the former President's habit on an aversion to anyone listening to his calls (which, in the White House, is hard for a president to avoid if he calls from a desk phone). So he would, frequently, grab the cell phone of a nearby aide or even a Secret Service agent to make calls.                                                                                                                                                                                                                                                                                                         , One case in point: After the Stormy Daniels story broke in 2018, Trump was on the golf course trying to reach his wife, Melania Trump, from his phone, and she did not pick up, according to a source with knowledge. So he turned to a Secret Service agent and used the agent's phone to try to reach her instead. The first lady then picked up. According to this source, the agent was not pleased his phone had been used this way.                                                                                                                                                                               , As CNN has reported, sources familiar with the investigation have not drawn any conclusions about the large gap in the phone records at this point. Trump may have decided not to make or receive calls, committee sources allow. There's also a chance that the National Archives will find more records -- on other people's phones -- to explain the gaps.                                                                                                                                                                                                                                                           , Multiple sources have told CNN that former White House deputy chief of staff Dan Scavino was a common conduit for Trump's conversations, having an office in the outer Oval "within shouting distance" of the president. One source witnessed Scavino routinely handing his phone to Trump to take calls. The source describes Scavino as the "key to pretty much everything," given how much time he spent with the then-President. An attorney for Scavino declined to comment.                                                                                                                                       , Scavino, according to this source, had an official phone and a personal phone.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , He has been subpoenaed by the January 6 committee and is suing Verizon because of the committee's subpoena of his phone records. The lawsuit -- still in its earliest stage -- has temporarily stopped the phone company from giving logs of his calls and subscriber information to the House.                                                                                                                                                                                                                                                                                                                         , The way former aides tell it, people would often get through to Trump by calling staff around him. Some callers, the aides say, found it easiest to communicate through chief of staff Mark Meadows or even daughter Ivanka Trump. They would offer Trump a call from an ally who was on hold, and he would either take it or wave them off with the back of his hand.                                                                                                                                                                                                                                                  , "He liked to talk to people he agreed with," said another aide.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , In addition, Trump typically would not take his own personal cell phone into the Oval Office, according to former New Jersey Gov. Chris Christie, who tried multiple times to reach him as the riot raged.                                                                                                                                                                                                                                                                                                                                                                                                              , "First, I called his secretary. She didn't pick up the phone. Went right to her voicemail. Then I called his body person and he didn't answer his phone. Then I called the White House switchboard and asked to be put through. And they said he was not available. And then I called his personal cell phone," Christie told CNN's Dana Bash in an interview last year. "I didn't know where he was. I tried his cell phone and it went to voicemail."                                                                                                                                                                 , Trump never called Christie back that day, the former governor told Bash.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Trump did speak with House Minority Leader Kevin McCarthy during the insurrection -- although it was not noted in the official call logs. A call earlier that morning with GOP Rep. Jim Jordan of Ohio, first reported by CNN, was noted in the official log.                                                                                                                                                                                                                                                                                                                                                           , As a way to gauge how unprecedented Trump's presidential behavior on the phone was -- and how he ran the White House generally -- a former senior White House official describes an early chaotic process with "almost no records of anything."                                                                                                                                                                                                                                                                                                                                                                         , "In fact," this former official says, "no one ever thought to ever keep track of people going in and out of the Oval."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , According to another former White House official, "for large chunks, at least, and most likely for the entirety of the Trump presidency, there aren't Oval Office visitor logs." Keeping such logs is not mandated, but it had become the norm under previous administrations.                                                                                                                                                                                                                                                                                                                                          , When Gen. John Kelly became Trump's chief of staff in July 2017, he tried to clean up the messy phone process inside the White House -- and his boss hated it, according to a former White House official. Kelly tried to keep call logs and screen Trump's calls, but the President bristled at the restrictions, because he didn't want Kelly to know with whom he was speaking, the former official said.                                                                                                                                                                                                            , By comparison, a source with knowledge says that in the previous administration, all calls were run through official White House channels -- through the residence, the switchboard, the Situation Room and the signal operator. There was no way to get around the tight strictures.                                                                                                                                                                                                                                                                                                                                   , "It just didn't happen," the source said. There was no circumventing that." And most calls were by appointment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , In addition, the source said, then-President Barack Obama Obama would never have been allowed to use the phone of an aide or Secret Service agent to make calls. "Heavens, no," the source said.                                                                                                                                                                                                                                                                                                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/13/technology/divorce-bitcoin-crypto.html </td>
   <td style="text-align:left;"> 2022-02-13 18:00:12 </td>
   <td style="text-align:left;"> Divorcing Couples Fight Over the Kids, the House and Now the Crypto - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Dividing the family’s Bitcoin stash has become a major source of contention in divorce cases.                                                                                                                                                                                                                                                                                                                                                                                                                                    , By David Yaffe-Bellany                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , David Yaffe-Bellany, who covers crypto and fintech, combed through more than 600 pages of legal filings for this article.                                                                                                                                                                                                                                                                                                                                                                                                        , The divorce dragged on for eight years, almost as long as the marriage. The wealthy San Francisco couple sparred over child support, the profits from the sale of the husband’s software company and the fate of their $3.6 million home.                                                                                                                                                                                                                                                                                        , But the most consequential court battle between Erica and Francis deSouza concerned a bitter dispute over millions of dollars in missing Bitcoin.                                                                                                                                                                                                                                                                                                                                                                                , Mr. deSouza, a tech executive, had bought a little over 1,000 Bitcoins before he separated from his wife in 2013, and then lost nearly half the funds when a prominent cryptocurrency exchange collapsed. After three years of litigation, a San Francisco appeals court ruled in 2020 that Mr. deSouza had failed to properly disclose some elements of his cryptocurrency investments, which had exploded in value. The court ordered him to give Ms. deSouza more than $6 million of his remaining Bitcoin.                   , In legal circles, the deSouzas’ case has become known as perhaps the first major Bitcoin divorce. Such marital disputes are increasingly common. As cryptocurrencies gain wider acceptance, the division of the family stash has turned into a major source of contention, with estranged couples trading accusations of deception and financial mismanagement.                                                                                                                                                                  , An ugly divorce tends to generate arguments about virtually everything. But the difficulty of tracking and valuing cryptocurrency, a digital asset traded on a decentralized network, is creating new headaches. In many cases, divorce lawyers said, spouses underreport their holdings, or try to hide funds in online wallets that can be difficult to get into.                                                                                                                                                              , “Originally, it was under the mattress, and then it was the bank account in the Caymans,” said Jacqueline Newman, a divorce lawyer in New York who works with high-net-worth clients. “Now it’s crypto.”                                                                                                                                                                                                                                                                                                                         , The rise of cryptocurrencies has provided a useful medium of exchange for criminals, creating new opportunities for fraud. But digital assets are not untraceable. Transactions are recorded on public ledgers called blockchains, enabling savvy analysts to follow the money.                                                                                                                                                                                                                                                  , Some divorce lawyers have come to rely on a growing industry of forensic investigators, who charge tens of thousands of dollars to track the movement of cryptocurrencies like Bitcoin and Ether from online exchanges to digital wallets. The investigative firm CipherBlade has worked on about 100 crypto-related divorces over the last few years, said Paul Sibenik, a forensic analyst for the company. In multiple cases, he said, he has traced more than $10 million in cryptocurrency that a husband hid from his wife., “We’re trying to make it a cleaner space,” Mr. Sibenik said. “There needs to be some degree of accountability.”                                                                                                                                                                                                                                                                                                                                                                                                                  , In interviews, nearly a dozen lawyers and forensic investigators described divorce cases in which a spouse — usually the husband — was accused of lying about cryptocurrency transactions or hiding digital assets. None of the couples agreed to be interviewed. But some of the divorces have created paper trails that shed light on how these disputes unfold.                                                                                                                                                               , The deSouzas married in September 2001. That same year, Mr. deSouza founded an instant-messaging company, IMlogic, that he eventually sold in a deal netting him more than $10 million, according to court records.                                                                                                                                                                                                                                                                                                              , Mr. deSouza’s cryptocurrency investments date to April 2013, when he spent time in Los Angeles with Wences Casares, an early crypto entrepreneur, who pitched him on digital assets. That month, Mr. deSouza bought about $150,000 of Bitcoin.                                                                                                                                                                                                                                                                                   , The deSouzas separated later that year, and Mr. deSouza soon disclosed that he owned the Bitcoin. By the time the couple were ready to divide their assets in 2017, the value of that investment had ballooned to more than $21 million.                                                                                                                                                                                                                                                                                         , But there was a catch. That December, Mr. deSouza revealed that he had left a little under half the funds in a cryptocurrency exchange, Mt. Gox, that went bankrupt in 2014, putting the money out of reach.                                                                                                                                                                                                                                                                                                                     , In court filings, Ms. deSouza’s lawyers said it was “egregious” that her husband had failed to mention earlier that so much of the Bitcoin was gone, and argued that his secretive management of the investment had cost the couple millions of dollars. The lawyers also speculated that Mr. deSouza might be hoarding additional funds.                                                                                                                                                                                        , “Francis has been less than forthright with his ever-changing stories,” Ms. deSouza’s lawyers claimed in one filing.                                                                                                                                                                                                                                                                                                                                                                                                             , No secret stash ever materialized. A spokeswoman for Mr. deSouza said he had disclosed the entirety of his cryptocurrency holdings at the beginning of the divorce. “As soon as Francis knew that the Bitcoin was caught up in the Mt. Gox bankruptcy, he told his ex-wife,” the spokeswoman said. “Had the Mt. Gox bankruptcy not occurred, the division of the BTC would have been entirely uncontroversial.”                                                                                                                  , Ms. deSouza declined to comment through her lawyer.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , But the appeals court found that Mr. deSouza, 51, who is now the chief executive of the biotech company Illumina, had violated rules of the divorce process by failing to keep his wife fully apprised of his cryptocurrency investments.                                                                                                                                                                                                                                                                                        , He was ordered to give Ms. deSouza about half the total number of Bitcoins he had owned before the Mt. Gox bankruptcy, leaving him with 57 Bitcoins, worth roughly $2.5 million at today’s prices. Ms. deSouza’s Bitcoins are now worth more than $23 million.                                                                                                                                                                                                                                                                   , Not all crypto divorces involve such large sums. A few years ago, Nick Himonidis, a forensic investigator in New York, worked on a divorce case in which a woman accused her husband of underreporting his cryptocurrency holdings. With the court’s authorization, Mr. Himonidis showed up at the husband’s house and searched his laptop. He found a digital wallet, which contained roughly $700,000 of the cryptocurrency Monero.                                                                                            , “He was like: ‘Oh, that wallet? I didn’t think I even had that,’” Mr. Himonidis recalled. “I was like, ‘Seriously, dude?’”                                                                                                                                                                                                                                                                                                                                                                                                       , A glossary. Cryptocurrencies have gone from a curiosity to a viable investment, making them almost impossible to ignore. If you are struggling with the terminology, let us help:                                                                                                                                                                                                                                                                                                                                                , Bitcoin. A Bitcoin is a digital token that can be sent electronically from one user to another, anywhere in the world. Bitcoin is also the name of the payment network on which this form of digital currency is stored and moved.                                                                                                                                                                                                                                                                                               , Blockchain. A blockchain is a database maintained communally, that reliably stores digital information. The original blockchain was the database on which all Bitcoin transactions were stored, but non-currency-based companies and governments are also trying to use blockchain technology to store their data.                                                                                                                                                                                                               , Cryptocurrencies. Since Bitcoin was first conceived in 2008, thousands of other virtual currencies, known as cryptocurrencies, have been developed. Among them are Ether, Dogecoin and Tether.                                                                                                                                                                                                                                                                                                                                   , Coinbase. The first major cryptocurrency company to list its shares on a U.S. stock exchange, Coinbase is a platform that allows people and companies to buy and sell various digital currencies, including Bitcoin, for a transaction fee.                                                                                                                                                                                                                                                                                      , Crypto finance. The development of cryptocurrencies spawned a parallel universe of alternative financial services, known as Decentralized Finance, or DeFi, allowing crypto businesses to move into traditional banking territory, including lending and borrowing.                                                                                                                                                                                                                                                              , NFTs. A “nonfungible token,” or NFT, is an asset verified using blockchain technology, in which a network of computers records transactions and gives buyers proof of authenticity and ownership. NFTs make digital artworks unique, and therefore sellable.                                                                                                                                                                                                                                                                     , In another case, Mr. Himonidis said, he discovered that a husband had moved $2 million in cryptocurrency out of his account on the Coinbase exchange, a platform where people buy, sell and store digital currencies. A week after his wife filed for divorce, the man transferred the funds to digital wallets, and then left the United States.                                                                                                                                                                                , A court can order a cryptocurrency exchange to turn over funds. But the online wallets in which many investors store cryptocurrency are not subject to any centralized control; access requires a unique password created by the wallet’s owner. Without that digital key, the husband’s funds were effectively out of the soon-to-be-ex-wife’s reach.                                                                                                                                                                           , An exchange can still be a valuable source of information. In 2020, Gregory Salant, a divorce lawyer in White Plains, N.Y., worked with a client who believed her husband owned cryptocurrency he hadn’t disclosed. Mr. Salant sent a subpoena to Coinbase, which responded with a spreadsheet that he found impossible to understand. He hired a forensic investigator, Mark DiMichael, to translate the spreadsheet and track down the assets.                                                                                 , Mr. DiMichael produced a 42-page report that said the husband had made a series of payments to wallet addresses associated with the dark web, an online marketplace for drugs and other illicit goods. The husband had also transferred nearly $225,000 in cryptocurrency to other anonymous addresses. A review of his tax returns showed he hadn’t reported spending the cryptocurrency or converting it into dollars.                                                                                                         , “Plaintiff either neglected to report the sale or sending of the Missing Cryptocurrency on his income tax returns,” the report concluded, “or Plaintiff still retained control of the Missing Cryptocurrency.”                                                                                                                                                                                                                                                                                                                   , The case was eventually settled. Under the final agreement, some of the husband’s other assets were allocated to the wife to resolve the cryptocurrency dispute.                                                                                                                                                                                                                                                                                                                                                                 , “It was a package deal,” Mr. Salant said. “‘I won’t touch your retirement account, you won’t touch my retirement account, we give a $25,000 swing for the crypto.’”                                                                                                                                                                                                                                                                                                                                                              , In some divorces, the cryptocurrency stash turns out to be tiny or even nonexistent. Several lawyers described cases in which a wife’s suspicions were unfounded. But over and over, said Kelly Burris, a divorce lawyer in Austin, Texas, who primarily represents husbands, men have come into her office and detailed their plans to hide cryptocurrency.                                                                                                                                                                     , “They can be weirdly not creative,” Ms. Burris said. “They’ll be like, ‘I’ll give it to my brother for a dollar’ or whatever, and I’m like, ‘You can’t do that.’”                                                                                                                                                                                                                                                                                                                                                                , Ms. Burris is a fixture on the divorce industry lecture circuit, where she talks about the challenges of tracking digital assets. In some cases, she said, her male clients have proposed slightly more sophisticated frauds, like using a crypto A.T.M. to buy Bitcoin with cash.                                                                                                                                                                                                                                               , “They’re thinking, ‘There’s no way she can track it,'” Ms. Burris said. “‘There’s no way she can get access.’”                                                                                                                                                                                                                                                                                                                                                                                                                   , Kirsten Noyes and Sheelagh McNeill contributed research.                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/saudi-arabia-transfers-aramco-shares-worth-80-billion-to-wealth-fund </td>
   <td style="text-align:left;"> 2022-02-13 17:52:12 </td>
   <td style="text-align:left;"> Saudi Arabia transfers Aramco shares worth $80 billion to wealth fund </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                  , Saudi Arabia transferred shares worth about $80 billion in oil giant Aramco to its wealth fund as part of efforts to diversify the kingdom's hydrocarbon-dependent economy.                                                                                                                                                                                                                                        , The transfer of a 4% stake in state-owned Saudi Arabian Oil Co., known as Aramco, will support the Public Investment Fund's plan to grow its assets under management to over $1 trillion by 2025, from about $480 billion currently, the Saudi government said Sunday.                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                        , The Saudi government, which will remain the largest shareholder in Aramco with a stake of more than 94%, has sought to monetize the country's massive oil assets and use the proceeds to invest in industries outside of oil as part of Crown Prince Mohammed bin Salman's plan to restructure the economy by 2030.                                                                                                , An oil tank is seen at the Saudi Aramco headquarters during a media tour at Damam city REUTERS/ Ali Jarekji ( REUTERS/ Ali Jarekji / Reuters Photos)                                                                                                                                                                                                                                                               , To help meet that goal, Prince Mohammed, the kingdom's day-to-day ruler, has tasked the PIF to invest in companies and industries untethered to hydrocarbons. The government had also transferred the $29.4 billion it raised from Aramco's initial public offering in 2019 on the Saudi stock exchange to the PIF to deploy.                                                                                      , A RUSSIA-UKRAINE WAR WOULD MEAN GLOBAL ENERGY SHOCK                                                                                                                                                                                                                                                                                                                                                                , Earlier this month, people familiar with Aramco's strategy said the kingdom has restarted plans to list more shares of Aramco, the world's most valuable oil company, with an ambition to sell as much as a $50 billion stake, which at current valuations would be 2.5% of the company. The listing of shares would be by far the largest in the history of capital markets and could prove difficult to pull off., The stake-sale effort is still in the planning stage, and could still be delayed or changed, the people said. Riyadh has floated several different plans over the years aimed at raising funds via Aramco, some of which have ultimately faltered or been abandoned.                                                                                                                                               , The share transfer to PIF will help bolster the fund's strong financial position and its high credit rating in the medium term, according to the government.                                                                                                                                                                                                                                                       , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                            , In a separate statement, Aramco said the deal is a private transfer between the kingdom and the PIF, and Aramco isn't a party to the transfer and didn't enter into any agreements or pay or receive any proceeds from the transfer.                                                                                                                                                                               , The transfer doesn't have an impact on Aramco's operations, strategy or dividends-distribution policy, it added.                                                                                                                                                                                                                                                                                                   , Write to Summer Said at summer.said@wsj.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/stellantis-recalling-nearly-20000-plug-in-minivans-for-fire-risks </td>
   <td style="text-align:left;"> 2022-02-13 16:00:44 </td>
   <td style="text-align:left;"> Stellantis recalling nearly 20,000 plug-in minivans for fire risks </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                             , Chrysler parent Stellantis is recalling 19,808 plug-in hybrid minivans and urged owners to stop recharging them, after reports of 12 fires in parked vehicles.                                                                , The automaker said the recall covers 2017-2018 Chrysler Pacifica Hybrid vehicles. All were parked and turned off, while eight were connected to chargers. Stellantis said it was unaware of any related injuries or accidents., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                   , Stellantis is advising owners to refrain from recharging the vehicles and to park them away from structures and other vehicles. The automaker said it is working to confirm the cause of the fires.                           , Chrysler 2017 Pacifica hybrid minivan is unveiled during the press preview of the 2016 North American International Auto Show in Detroit, Michigan. (Photo credit should read JEWEL SAMAD/AFP via Getty Images)               , Owners can keep operating the vehicles using the internal combustion engine.                                                                                                                                                  , STELLANTIS AND FOXCONN PARTNERING ON AUTOMOTIVE SEMICONDUCTOR BUSINESS                                                                                                                                                        , The National Highway Traffic Safety Administration declined to comment.                                                                                                                                                       , The recall comprises 16,741 vehicles in the United States, 2,317 in Canada and another 750 outside North America.                                                                                                             , Other automakers have faced fire issues with plug-in hybrid or full electric vehicles.                                                                                                                                        , General Motors Co halted production of its Chevrolet Bolt electric vehicle in August and has extended that halt through the end of this month.                                                                                , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                       , The largest U.S. automaker in August widened its recall of the Bolt to more than 140,000 vehicles to replace battery modules after a series of fires. GM has also indefinitely halted retail sales of new Bolt vehicles.      , (Reporting by David Shepardson; Editing by Leslie Adler and David Gregorio) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/13/business/how-did-squarespace-know-podcasts-would-get-this-big.html </td>
   <td style="text-align:left;"> 2022-02-13 16:00:09 </td>
   <td style="text-align:left;"> How Did Squarespace Know Podcasts Would Get This Big? - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                         , From “This Week in Tech” to Zendaya at the Super Bowl.                                                                                                                                                                                                                                                                                                                                                                               , By Joel Stein                                                                                                                                                                                                                                                                                                                                                                                                                        , In 2009, Anthony Casalena was listening to a lot of podcasts, especially one called “This Week in Tech,” a round table where tech reporters gathered to talk about things like Farmville, Foursquare and the iFart app.                                                                                                                                                                                                              , Though the website building business he started in his dorm room six years before had yet to make a profit, he decided to make a big bet. He spent around $20,000 for an ad on the show to tell listeners about Squarespace.                                                                                                                                                                                                         , “It was so expensive compared to anything else I had done,” he said over Zoom from his vacation house in Montauk, N.Y., in September. By this fall, he was working on an ad campaign on a somewhat larger scale — including the Sunday Super Bowl ad starring Zendaya.                                                                                                                                                               , How Squarespace went from podcast spots to Super Bowl ads shows that his 2009 bet was right. Podcasts could sell.                                                                                                                                                                                                                                                                                                                    , To find out if that gamble on his first podcast ad on This Week in Tech worked, Squarespace built one of the earliest post-purchase surveys, the ones companies now pepper customers with. When he looked at the results, Mr. Casalena was shocked. A third of the company’s new subscribers had heard of its product from the ad on This Week in Tech.                                                                              , “So we became pioneers in trying to find every emerging show host we could before they’re super popular,” Mr. Casalena said. Everyone at Squarespace started hunting for podcasts to advertise on.                                                                                                                                                                                                                                   , When a podcast host ad-libbed their promotional copy — and particularly if they stressed that using the Squarespace promo code supported their show — the return on the ad spending was enormous. And, according to a former Squarespace employee, when that host was Joe Rogan, the return was almost unbelievable.                                                                                                                 , Other people later discovered the same about Mr. Rogan, who started podcasting the same year Squarespace started advertising. In 2020 Spotify offered him a reported $100 million for his show.                                                                                                                                                                                                                                      , It has also, in recent days, apologized for him. After several artists pulled their music from Spotify because they believed Mr. Rogan promoted Covid-19 misinformation, and his past use of racial slurs drew new attention, Spotify’s chief executive sent his staff an email saying “there are no words I can say to adequately convey how deeply sorry I am.” (Mr. Rogan also apologized for what he called “shameful” language.), The controversy erupted several months after Mr. Casalena and I spoke and, through a spokesman, he declined to comment on Mr. Rogan.                                                                                                                                                                                                                                                                                                 , The success with podcast ads made Mr. Casalena such a believer in advertising that in 2015, he decided to buy a 30-second Super Bowl ad that he figures cost him $10 million. “It’s a good deal,” he said. “What other ad do we do that gets picked up in the media over like a hundred different sources and played for free?” It is very hard to argue with that point here.                                                       , Mr. Casalena’s commitment to podcast advertising was so singular even in 2015 that when President Barack Obama — years from being a podcaster himself — went on Marc Maron’s show, Squarespace was the only company approached about ads.                                                                                                                                                                                            , Ilyas Frenkel, Squarespace’s growth marketing manager at the time, received that call from Midroll Media, the company that sold Mr. Maron’s ads. Mr. Frenkel asked the salesperson who Mr. Maron was interviewing that put the ad rate at $100,000. “He couldn’t tell me but he said, ‘You have to do it.’ We said, ‘OK,’” Mr. Frenkel said.                                                                                         , That year, FiveThirtyEight tracked the biggest podcast advertisers, and it found that Squarespace was taking out two-and-half as many ads as its nearest competitor, Stamps.com.                                                                                                                                                                                                                                                     , The company was advertising on more than 400 podcasts a month. According to a former Midroll employee, the company had an internal meeting because the executives were concerned that one account, Squarespace, accounted for a third of the revenue.                                                                                                                                                                                , Squarespace’s team purchasing ads on Facebook and Google would get grilled in meetings, because their return on what they spent on ads couldn’t compete with the team placing ads on podcasts and YouTube videos.                                                                                                                                                                                                                    , The podcast ad budget grew so large that the team of four young people couldn’t spend it all. According to the former employee, at one point, Squarespace discussed taking out ads that didn’t even talk about Squarespace and just promoted Podcast Awareness month, something they were going to make up. Squarespace employees were the only group of people in the world who have ever thought there weren’t enough podcasts.    , Squarespace ad buyers were agnostic about audience size. If they spent $500 on a podcast with a tiny audience and scored 20 subscribers, it was worth it — because people who pay an annual fee to host their website aren’t likely to leave and redesign their site somewhere else.                                                                                                                                                 , Squarespace gets mocked for being the podcast-ad company, but Mr. Casalena revels in the attention, rattling off mentions on “Saturday Night Live,” the Netflix show “Only Murders in the Building” and J. Cole’s song “My Life.” (“I think he just really needed something that rhymes with ‘airspace,” Mr. Casalena said.)                                                                                                         , Dax Shepard said he heard Squarespace ads so much on his favorite podcasts that he believed their ads helped legitimize his show when he started reading them. “It one of the few ads I know by heart,” Mr. Shepard explained in an email. “It’s a party trick.”                                                                                                                                                                     , Mr. Casalena said that since he founded the company, he has spent over $1 billion promoting his brand across all platforms. The revenue from those ads, plus all that attention, helped the company go public in May, landing Mr. Casalena himself $2.4 billion in stock in the $6.6 billion company.                                                                                                                                , Long before anyone came up with the idea of Web3 (the name for a decentralized internet run on crypto tokens), Mr. Casalena understood that people were looking to monetize every interaction in their lives.                                                                                                                                                                                                                        , He saw that Squarespace’s small business owners were selling services along with goods. Online classes. Tattoo appointments. Tutoring. Tarot card reading. The internet rule “information wants to be free” was starting to deteriorate.                                                                                                                                                                                             , “People were able to get audiences in ways they couldn’t get them before via the social networks. But they don’t want to be beholden to the social networks,” Mr. Casalena said.                                                                                                                                                                                                                                                     , He is now betting on a world in which people’s social media accounts reviewing wine or dispensing makeup tips become their main businesses. “We see this larger opportunity now around selling time,” Mr. Casalena said.                                                                                                                                                                                                             , In 2019, Squarespace made its first acquisition, buying Acuity Scheduling, which helps businesses with online appointments. In March 2021, it bought Tock, which helps restaurants and wineries manage reservations and takeout orders, for more than $400 million.                                                                                                                                                                  , After a 2021 Super Bowl ad in which Dolly Parton extolled the side hustle angered people who felt exploited by the gig economy (“5 to 9,” she sang), Squarespace refined its service-economy-forward message with a campaign featuring John McEnroe.                                                                                                                                                                                 , The former tennis great had stumbled into a new line of work — doing voice overs — and in the ad (and the seven-minute mockumentary accompanying the campaign), Mr. McEnroe uses Squarespace to promote his voice-over career.                                                                                                                                                                                                       , To help everyone on the journey from person to brand, Squarespace created its new Video Studio app, which provides a library of images as well as voices you can access simply by typing. A company that started advertising on podcasts essentially changed its business to help people make podcasts.                                                                                                                              , The decentralized economy, Squarespace predicts, will be all side hustle, all the time. “The part of the economy that will be less commoditized is our individual experiences,” said Nick Kokonas, the derivatives trader turned Chicago restaurateur who founded Tock.                                                                                                                                                              , If 10 different merchants on Amazon are selling the same product, he can buy the cheapest one. “But food isn’t like that. And personal training isn’t like that. Those people whose marketplace used to be hyperlocal, this gives them global reach,” he said.                                                                                                                                                                       , Mr. Kokonas believes that most businesses selling goods will add a service component, a trend called multimodal spending that the pandemic sped up.                                                                                                                                                                                                                                                                                  , In this year’s Super Bowl ad, Zendaya plays a woman selling seashells who uses Squarespace to offer seashell meditation sessions and a seashell travel, becoming a “seashell celebrity.” Which is a not a completely improbable job description in 2022. No doubt, she’ll also have a podcast.                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/enb:cn </td>
   <td style="text-align:left;"> 2022-02-13 15:19:22 </td>
   <td style="text-align:left;"> Enbridge earnings below expectations at 0.68 CAD </td>
   <td style="text-align:left;"> Enbridge (ENB) released earnings per share at 0.68 CAD, compared to market expectations of 0.76 CAD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bats:ln </td>
   <td style="text-align:left;"> 2022-02-13 15:19:09 </td>
   <td style="text-align:left;"> British American Tobacco earnings below expectations at 1.51 GBp </td>
   <td style="text-align:left;"> British American Tobacco (BATS) released earnings per share at 1.51 GBp, compared to market expectations of 173.81 GBp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/rosn:rm </td>
   <td style="text-align:left;"> 2022-02-13 15:16:40 </td>
   <td style="text-align:left;"> Rosneft earnings below expectations at 39.09 RUB </td>
   <td style="text-align:left;"> Rosneft (ROSN) released earnings per share at 39.09 RUB, compared to market expectations of 42.89 RUB. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/rel:ln </td>
   <td style="text-align:left;"> 2022-02-13 13:51:01 </td>
   <td style="text-align:left;"> Relx earnings below expectations at 0.42 GBp </td>
   <td style="text-align:left;"> Relx (REL) released earnings per share at 0.42 GBp, compared to market expectations of 78.00 GBp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/politics/2022/02/12/arizona-senate-candidate-ad-guttenberg-intv-sot-acostanr-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-13 08:17:59 </td>
   <td style="text-align:left;"> GOP Senate candidate runs ad featuring armed 'showdown' with Dems - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/china-stiffed-trump-trade-agreement-exports </td>
   <td style="text-align:left;"> 2022-02-13 05:08:58 </td>
   <td style="text-align:left;"> China stiffed US on Trump Phase 1 trade agreement, failed to buy extra $200B in exports </td>
   <td style="text-align:left;"> Michelle Steel, R-Calif., argues the U.S. Olympic corporate sponsors are ‘hypocritical’ for not being concerned about athletes in poor condition during the Beijing Winter Games.                                                                                                                                                                                                                                                                                                            , China failed to increase its purchase U.S. goods despite an agreement with President Trump to grab an additional $200 billion of U.S. exports, a new study found.                                                                                                                                                                                                                                                                                                                            , Trump signed a "historic" deal with China in January 2020 which would see Beijing increase its imports by Dec. 31, 2021. A study from the Peterson Institute for International Economics examined the "Phase 1" agreement, which dictated that China would buy at least $227.9 billion of U.S. goods in 2020 and $274.5 billion in 2021, but the company hit only $288.8 billion over the two-year period instead.                                                                           , CONSUMERS' RESEARCH BLASTS BLACKROCK'S LARRY FINK FOR GOING ‘ALL-IN ON CHINA’                                                                                                                                                                                                                                                                                                                                                                                                                , China only achieved 57% of its promised purchases, which left it short of even its pre-pandemic levels and means China did not increase its imports from the U.S. at all. U.S. officials promised to continue pressing China to show "serious intent" to reach their purchase commitments but admitted the deal offered little leverage for enforcement, Reuters reported.                                                                                                                   , Custom officials check documents with a man at a container port in Yantai in eastern China's Shandong province on Tuesday.   | Associated Press                                                                                                                                                                                                                                                                                                                                              , The study pointed to the COVID-19 pandemic as a significant stumbling block for China to hit the target sum, but also highlighted that the trade war Trump instigated prior to the deal left U.S. exporters to play catch up in the first place. The crash of two Boeing planes also dampened the ability to ship out new planes, and tariffs from China pushed automakers to move production out of the U.S. in order to maintain access to consumers, wrote the study’s author Chad Brown. , Walter Lohman, Director of the Asian Studies Center at the Heritage Foundation, told FOX Business that the deal was doomed to failure from the start, but not for the reasons that Brown cited.                                                                                                                                                                                                                                                                                              , TIKTOK SHARES MORE OF YOUR DATA THAN ANY OTHER APP, AND A STUDY SAYS IT'S NOT CLEAR WHERE IT GOES                                                                                                                                                                                                                                                                                                                                                                                            , "The idea of locking China into certain quotas … I think it was a flawed concept to begin with," Lohman said. "It just wasn’t the way to go about things."                                                                                                                                                                                                                                                                                                                                   , Lohman explained that the trade relationship between the two countries, despite some noise made by leaders, has remained "pretty strong." China remains among America’s top three trading partners with roughly equal shares to Mexico and Canada, and sales from American companies with subsidiaries in China sell almost twice as much as America generally exports to the country.                                                                                                       , KUDLOW: COMPETES ACT IS NOTHING TO DO WITH COMPETING WITH CHINA                                                                                                                                                                                                                                                                                                                                                                                                                              , Lohman argued that the deal set out to fix Chinese theft of American intellectual property (IP), but it was a poor way to handle the situation. China initially agreed to the deal because they were trying "wait the Trump administration out," but it was "never likely" to meet the agreed upon targets.                                                                                                                                                                                  , "The companies have often given away their property as the cost of doing business," he said. "It’s basically illegal in international trade law to demand someone gives you their intellectual property as a cost of business, but the Chinese do it, and the companies do it."                                                                                                                                                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                  , "Some of the companies even offer it up to favor the Chinese, and then the market doesn’t work out for them, and then years later they complain about their technology being coerced away from them," he added, noting that as long as it doesn’t impact U.S. national security, that’s a problem for the companies to deal with. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/12/business/economy/ibm-age-discrimination.html </td>
   <td style="text-align:left;"> 2022-02-13 04:52:56 </td>
   <td style="text-align:left;"> Making ‘Dinobabies’ Extinct: IBM’s Push for a Younger Work Force - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Documents released in an age-discrimination case appear to show high-level discussion about paring the ranks of older employees.                                                                                                                                                                                                                                                                                                                                                                                                                                            , By Noam Scheiber                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , In recent years, former IBM employees have accused the company of age discrimination in a variety of legal filings and press accounts, arguing that IBM sought to replace thousands of older workers with younger ones to keep pace with corporate rivals.                                                                                                                                                                                                                                                                                                                  , Now it appears that top IBM executives were directly involved in discussions about the need to reduce the portion of older employees at the company, sometimes disparaging them with terms of art like “dinobabies.”                                                                                                                                                                                                                                                                                                                                                        , A trove of previously sealed documents made public by a Federal District Court on Friday show executives discussing plans to phase out older employees and bemoaning the company’s relatively low percentage of millennials.                                                                                                                                                                                                                                                                                                                                                , The documents, which emerged from a lawsuit contending that IBM engaged in a yearslong effort to shift the age composition of its work force, appear to provide the first public piece of direct evidence about the role of the company’s leadership in the effort.                                                                                                                                                                                                                                                                                                         , “These filings reveal that top IBM executives were explicitly plotting with one another to oust older workers from IBM’s work force in order to make room for millennial employees,” said Shannon Liss-Riordan, a lawyer for the plaintiff in the case.                                                                                                                                                                                                                                                                                                                     , Ms. Liss-Riordan represents hundreds of former IBM employees in similar claims. She is seeking class-action status for some of the claims, though courts have yet to certify the class.                                                                                                                                                                                                                                                                                                                                                                                     , Adam Pratt, an IBM spokesman, defended the company’s employment practices. “IBM never engaged in systemic age discrimination,” he said. “Employees were separated because of shifts in business conditions and demand for certain skills, not because of their age.”                                                                                                                                                                                                                                                                                                        , Mr. Pratt said that IBM hired more than 10,000 people over 50 in the United States from 2010 to 2020, and that the median age of IBM’s U.S. work force was the same in each of those years: 48. The company would not disclose how many U.S. workers it had during that period.                                                                                                                                                                                                                                                                                             , A 2018 article by the nonprofit investigative website ProPublica documented the company’s apparent strategy of replacing older workers with younger ones and argued that it followed from the determination of Ginni Rometty, then IBM’s chief executive, to seize market share in such cutting-edge fields as cloud services, big data analytics, mobile, security and social media. According to the ProPublica article, based in part on internal planning documents, IBM believed that it needed a larger proportion of younger workers to gain traction in these areas., In 2020, the Equal Employment Opportunity Commission released a summary of an investigation into these practices at IBM, which found that there was “top-down messaging from IBM’s highest ranks directing managers to engage in an aggressive approach to significantly reduce the head count of older workers.” But the agency did not publicly release evidence supporting its claims.                                                                                                                                                                                   , The newly unsealed documents — which quote from internal company emails, and which were filed in a “statement of material facts” in the lawsuit brought by Ms. Liss-Riordan — appear to affirm those conclusions and show top IBM executives specifically emphasizing the need to thin the ranks of older workers and hire more younger ones.                                                                                                                                                                                                                               , “We discussed the fact that our millennial population trails competitors,” says one email from a top executive at the time. “The data below is very sensitive — not to be shared — but wanted to make sure you have it. You will see that while Accenture is 72% millennial we are at 42% with a wide range and many units falling well below that average. Speaks to the need to hire early professionals.”                                                                                                                                                                , “Early professionals” was the company’s term for a role that required little prior experience.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Another email by a top executive, appearing to refer to older workers, mentions a plan to “accelerate change by inviting the ‘dinobabies’ (new species) to leave” and make them an “extinct species.”                                                                                                                                                                                                                                                                                                                                                                       , A third email refers to IBM’s “dated maternal workforce,” an apparent allusion to older women, and says: “This is what must change. They really don’t understand social or engagement. Not digital natives. A real threat for us.”                                                                                                                                                                                                                                                                                                                                          , Mr. Pratt, the spokesman, said that some of the language in the emails “is not consistent with the respect IBM has for its employees” and “does not reflect company practices or policies.” The statement of material facts redacts the names of the emails’ authors but indicates that they left the company in 2020.                                                                                                                                                                                                                                                      , Both earlier legal filings and the newly unsealed documents contend that IBM sought to hire about 25,000 workers who typically had little experience during the 2010s.  At the same time, “a comparable number of older, non-Millennial workers needed to be let go,” concluded a passage in one of the newly unsealed documents, a ruling in a private arbitration initiated by a former IBM employee.                                                                                                                                                                     , Similarly, the E.E.O.C.’s letter summarizing its investigation of IBM found that older workers made up over 85 percent of the group whom the company viewed as candidates for layoffs, though the agency did not specify what it considered “older.”                                                                                                                                                                                                                                                                                                                        , The newly unsealed documents suggest that IBM sought to carry out its strategy in a variety of ways, including a policy that no “early professional hire” can be included in a mass layoff in the employee’s first 12 months at the company. “We are not making the progress we need to make demographically, and we are squandering our investment in talent acquisition and training,” an internal email states.                                                                                                                                                          , The lawsuit also argues that IBM sought to eliminate older workers by requiring them to move to a different part of the country to keep their jobs, assuming that most would decline to move. One internal email stated that the “typical relo accept rate is 8-10%,” while another said that the company would need to find work for those who accepted, suggesting that there was not a business rationale for asking employees to relocate.                                                                                                                              , And while IBM employees designated for layoffs were officially allowed to apply for open jobs within the company, other evidence included in the new disclosure suggests that the company discouraged managers from actually hiring them. For example, according to the statement of material facts, managers had to request approval from corporate headquarters if they wanted to move ahead with a hire.                                                                                                                                                                 , Several of the plaintiffs in a separate lawsuit brought by Ms. Liss-Riordan appeared to have been on the receiving end of these practices. One of them, Edvin Rusis, joined IBM in 2003 and had worked as a “solution manager.” He was informed by the company in March 2018 that he would be laid off within a few months. According to his legal complaint, Mr. Rusis applied for five internal positions after learning of his forthcoming layoff but heard nothing in response to any of his applications.                                                              , Mr. Pratt, the spokesman, said that the company’s efforts to shield recent hires from layoffs, as well as its approach to relocating workers, were blind to age, and that many workers designated for layoffs did secure new jobs with IBM.                                                                                                                                                                                                                                                                                                                                 , The ProPublica story from 2018 identified employees in similar situations, and others who were asked to relocate out of state and decided to leave the company instead.                                                                                                                                                                                                                                                                                                                                                                                                     , The company has faced other age discrimination claims, including a lawsuit filed in federal court in which plaintiffs accused the company of laying off large numbers of baby boomers because they were “less innovative and generally out of touch with IBM’s brand, customers and objectives.” The case was settled in 2017, according to ProPublica.                                                                                                                                                                                                                     , In 2004, the company agreed to pay more than $300 million to settle with employees who argued that its decision in the 1990s to replace its traditional pension plan with a plan that included some features of a 401(k) constituted age discrimination.                                                                                                                                                                                                                                                                                                                    , The federal Age Discrimination in Employment Act prohibits discrimination against people 40 or over in hiring and employment on the basis of their age, with limited exceptions.                                                                                                                                                                                                                                                                                                                                                                                            , The act also requires companies to disclose the age and positions of all people within a group or department being laid off, as well as those being kept on, before a worker waives the right to sue for age discrimination. Companies typically require such waivers before granting workers’ severance packages.                                                                                                                                                                                                                                                          , But IBM stopped asking workers who received severance packages to waive their right to sue beginning in 2014, which allowed it to cease providing information about the age and positions of workers affected by a mass layoff.                                                                                                                                                                                                                                                                                                                                             , Instead, IBM required workers receiving a severance package to bring any discrimination claims individually in arbitration — a private justice system often preferred by corporations and other powerful defendants. Mr. Pratt said the change was made to better protect workers’ privacy.                                                                                                                                                                                                                                                                                 , While some former employees preserved their ability to sue IBM in court by declining the severance package, many former employees accepted the package, requiring them to bring claims in arbitration. Ms. Liss-Riordan, who is running for attorney general of Massachusetts, represents employees in both situations.                                                                                                                                                                                                                                                     , The particular legal matter that prompted the release of the documents in federal court was a motion by one of the plaintiffs whose late husband had signed an agreement requiring arbitration, and whose arbitration proceeding IBM then sought to block.                                                                                                                                                                                                                                                                                                                  , IBM argued that the plaintiff sought to pursue the claim in arbitration after the window for doing so had passed, and that some of the evidence the plaintiff sought to introduce was confidential under the arbitration agreement. The plaintiff argued that those provisions of the arbitration agreement were unenforceable.                                                                                                                                                                                                                                             , The judge in the case, Lewis J. Liman, has yet to rule on the merits of that argument. But in January, Judge Liman ruled that documents in the case, including the statement of material facts, should be available to the public.                                                                                                                                                                                                                                                                                                                                          , IBM asked a federal appellate court to stay Judge Liman’s disclosure decision, but a three-judge panel of the U.S. Court of Appeals for the Second Circuit rejected the company’s argument, and the full circuit court also declined to grant a stay. The New York Times filed an amicus brief to the circuit court arguing that the First Amendment applied to the documents in question.                                                                                                                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/12/politics/hillary-clinton-emails-trump-records/index.html </td>
   <td style="text-align:left;"> 2022-02-13 02:26:20 </td>
   <td style="text-align:left;"> Clinton jabs at Trump over allegedly flushing documents: "But her emails"  - CNNPolitics </td>
   <td style="text-align:left;"> Washington (CNN)Hillary Clinton jokingly jabbed at former President Donald Trump in a tweet amid reports that he periodically flushed papers down the toilet in the White House residence.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , "Just in time for Galentine's Day, and the news that Trump was flushing documents down White House toilets...," Clinton, the 2016 Democratic presidential candidate and former secretary of state, tweeted promoting a new hat that reads "but her emails." Her nonprofit organization Onward Together is selling the hat as part of its fundraising efforts. Her mention of "Galentine's Day" in the tweet is a nod to the NBC television series "Parks and Recreation," which popularized the term.                                                                                                                                                                              , Clinton's tweet comes after reports this week that then-President Trump would often tear up documents, drafts and memos after reading them. The revelation of Trump's toilet-flushing habit was first revealed Thursday by Maggie Haberman, a New York Times journalist and author of the forthcoming book "Confidence Man" about Trump.                                                                                                                                                                                                                                                                                                                                           , Trump has denied the toilet-flushing allegations as categorically untrue.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The hat Clinton promoted in the tweet references her use of a personal email account on a private server during her tenure as secretary of state under the Obama administration. The FBI investigated the matter, and then-FBI Director James Comey said in 2016 that Clinton was "extremely careless" but ultimately determined she should not be charged. The email controversy prompted also prompted an internal State Department investigation that found Clinton didn't deliberately mishandle classified information.                                                                                                                                                       , Clinton established her nonprofit organization after losing the 2016 presidential election with a mission to support progressive leaders and organizations. As a part of the fundraising efforts, the organization sells merchandise using Clinton's likeness and name.                                                                                                                                                                                                                                                                                                                                                                                                            , The National Archives has asked the Department of Justice to investigate Trump's handling of White House records and is seeking a review of whether Trump violated the Presidential Records Act, which requires that all records created by presidents be turned over to the National Archives at the end of their administrations, and other possible violations, including the handling of classified information. The request came after recent revelations that the National Archives last month had to retrieve 15 boxes of records that had ended up with Trump in Mar-a-Lago and that other documents given to the Archives were torn up and had to be pieced back together., Trump frequently referenced the Clinton email probe on the campaign trail in 2016, referring to it as "the biggest political scandal since Watergate."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The "but her emails" hat has already sold out.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/d:us </td>
   <td style="text-align:left;"> 2022-02-13 00:18:44 </td>
   <td style="text-align:left;"> Dominion Resources earnings below expectations at 0.90 USD </td>
   <td style="text-align:left;"> Dominion Resources (D) released earnings per share at 0.90 USD, compared to market expectations of 0.91 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/apo:us </td>
   <td style="text-align:left;"> 2022-02-13 00:18:25 </td>
   <td style="text-align:left;"> Apollo Global Management earnings below expectations at 1.05 USD </td>
   <td style="text-align:left;"> Apollo Global Management (APO) released earnings per share at 1.05 USD, compared to market expectations of 1.09 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/enb:us </td>
   <td style="text-align:left;"> 2022-02-13 00:17:50 </td>
   <td style="text-align:left;"> Enbridge USA earnings below expectations at 0.54 USD </td>
   <td style="text-align:left;"> Enbridge USA (ENB) released earnings per share at 0.54 USD, compared to market expectations of 0.60 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/calendar?article=29133&amp;g=top&amp;importance=2&amp;startdate=2022-02-12 </td>
   <td style="text-align:left;"> 2022-02-12 20:56:00 </td>
   <td style="text-align:left;"> Markets are Braced for More Volatility Next Week </td>
   <td style="text-align:left;"> Worries over a hawkish Federal Reserve and growing fears of the Russian invasion on Ukraine will dominate markets next week. In the US, all eyes will be on the FOMC meeting minutes, retail sales, producer inflation and housing data. Other important releases include inflation rates for China, Canada and Japan; UK unemployment rate, and Japan GDP growth rate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/emerging-deal-split-83m-surfside-condo-collapse </td>
   <td style="text-align:left;"> 2022-02-12 20:08:51 </td>
   <td style="text-align:left;"> Emerging deal would split $83M for Surfside condo collapse losses </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                             , A tentative deal announced Friday would pay $83 million to people who suffered economic losses such as condominium units and personal property in the collapse of a Florida building that killed 98 people.                                                                                                                   , The emerging agreement, yet to be formally reduced to writing, would set aside whatever amount above the property settlement figure for those who lost loved ones in the collapse of the 12-story Champlain Towers South condominium in Surfside, Florida.                                                                    , The proposal was unveiled at a hearing Friday before Miami-Dade Circuit Judge Michael Hanzman, who is presiding over lawsuits stemming from the June 24 collapse.                                                                                                                                                             , "That is promising news. We’ll see how it plays out," said Hanzman, who must approve a deal and said he would hear any objections before deciding. "There’s a strong possibility we’re going to avoid any drawn-out legal battle."                                                                                            , This aerial image shows an oceanfront condo building that partially collapsed three days earlier, resulting in fatalities and many people still unaccounted for, in Surfside, Fla., June 27, 2021.  (AP Photo/Gerald Herbert / AP Newsroom)                                                                                   , NYC CRIME A BOON TO FLORIDA BUSINESS: REAL DEVELOPER                                                                                                                                                                                                                                                                          , A written agreement will be ready to file in court by next Thursday, said attorneys involved in the negotiations overseen by mediator Bruce Greer.                                                                                                                                                                            , The main lawsuit, filed on behalf of Champlain Towers South victims and family members, contends that work on the adjacent Eighty Seven Park tower damaged and destabilized a building in dire need of major structural repair.                                                                                               , Champlain Towers was in the midst of its 40-year structural review when it collapsed without warning, burying victims under tons of rubble and almost instantly destroying dozens of condo homes. That has triggered multiple federal and state investigations and a flurry of lawsuits by victims, families and condo owners., A key question from the beginning was how to allocate money from the property’s sale, insurance proceeds and damages from lawsuits between wrongful death cases and those with only property claims.                                                                                                                          , Gonzalo Dorta, who represents the property owners group, said the agreement means those who accept part of the $83 million will be finished with the case and won’t be subjected to a possible assessment that state law allows for condo associations to cover legal and other costs.                                        , "They will be free from that exposure," Dorta said.                                                                                                                                                                                                                                                                           , People embrace at a makeshift memorial outside St. Joseph Catholic Church, in Surfside, Fla., June 28, 2021, near the collapsed building. (AP Photo/Gerald Herbert / AP Newsroom)                                                                                                                                             , LA MANSION HEADED TO AUCTION BLOCK IS AMERICA'S MOST EXPENSIVE HOME                                                                                                                                                                                                                                                           , It wasn’t immediately clear how many people are in each camp. There were 136 units in Champlain Towers South and 98 deaths. Some units were rented from out-of-town owners. Some owners also are part of the wrongful death aspect of the case.                                                                               , "We believe this resolution takes into account interests for all sides," said attorney Judd Rosen, who represents the wrongful death plaintiffs.                                                                                                                                                                              , Still, this tentative agreement would represent only part of the case. The lawsuit claiming damages for wrongful death will move forward, with potential collections including $120 million or more from the property sale and perhaps $30 million in estimated insurance proceeds.                                           , This aerial photo shows part of the 12-story oceanfront Champlain Towers South Condo that collapsed June 24, 2021, in Surfside, Fla.  (Amy Beth Bennett /South Florida Sun-Sentinel via AP)                                                                                                                                   , An auction sale of the property is planned for late April, court-appointed receiver Michael Goldberg said.                                                                                                                                                                                                                    , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                       , The lead investigating agency is the National Institute for Standards and Technology, which recently estimated its probe could take as long as two years.                                                                                                                                                                     , Much of the recent work has involved preparing the beach side site to collect evidence through soil borings and other methods about what caused the collapse. There is also a Feb. 21 walk-through planned for experts to examine evidence stored in warehouses.                                                              , "We’re really just pleased with how that’s going," Goldberg said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/rating </td>
   <td style="text-align:left;"> 2022-02-12 19:05:06 </td>
   <td style="text-align:left;"> Fitch Downgrades Turkish Debt Deeper into Junk </td>
   <td style="text-align:left;"> The Fitch rating agency lowered Turkey's long-term debt rating to B+ from BB-, pushing it deeper into the junk territory. The agency also issued a negative outlook  bringing the possibility of further downgrades. Policy-driven financial stress episodes of higher frequency and intensity have increased Turkey's vulnerabilities in terms of high inflation, low external liquidity and weak policy credibility, the agency said. Fitch does not expect the authorities' policy response to reduce inflation, including FX-protected deposits, targeted credit and capital flow measures, will sustainably ease macroeconomic and financial stability risks. Standard &amp; Poor's credit rating for Turkey stands at B+ with negative outlook. Moody's credit rating for Turkey was last set at B2 with negative outlook. DBRS's credit rating for Turkey is BB (high) with negative outlook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/12/weather/rogue-wave-record-vancouver-island/index.html </td>
   <td style="text-align:left;"> 2022-02-12 19:02:21 </td>
   <td style="text-align:left;"> Four-story high rogue wave breaks records off the coast of Vancouver Island - CNN </td>
   <td style="text-align:left;"> (CNN)A rogue wave measuring 58 feet (17.6 meters) tall was recorded off the coast of Vancouver Island, breaking the record for proportionality at three times the size of surrounding waves.                                                                                                                                                                                                                                , "Only a few rogue waves in high sea states have been observed directly, and nothing of this magnitude. The probability of such an event occurring is one in 1,300 years," said Johannes Gemmrich, one of the lead researchers on rogue waves at the University of Victoria.                                                                                                                                                  , The wave made a splash in the scientific community for being proportionally the most extreme rogue wave ever recorded. Although it occurred in November 2020, the study confirming it was just released February 2 of this year.                                                                                                                                                                                             , A rogue wave is exactly how it sounds: unexpected and terrifying.                                                                                                                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                              , "They look like a large four-story lump sticking out of the water with a large peak and big troughs before it," Scott Beatty, CEO of MarineLabs, the company operating the buoy which measured the wave, told CNN.                                                                                                                                                                                                           , In the past few decades, what was once known as marine folklore has now  been accepted as real by scientists.                                                                                                                                                                                                                                                                                                                , "Rogues, called 'extreme storm waves' by scientists, are those waves which are greater than twice the size of surrounding waves, are very unpredictable, and often come unexpectedly from directions other than prevailing wind and waves," The National Oceanic and Atmospheric Association (NOAA) explained.                                                                                                               , In simplified terms, "A rogue wave is actually just a wave that is large compared to the surrounding wave field," Gemmrich clarified.                                                                                                                                                                                                                                                                                        , Overall size doesn't matter, but the comparison in size to other waves does.                                                                                                                                                                                                                                                                                                                                                 , Thus, while a wave achieving a four-story height equivalent is impressive, its magnitude being three times that of its surrounding waves is what landed it in the record books.                                                                                                                                                                                                                                              , The first rogue wave recorded, known as "The Draupner Wave," was measured in 1995 off the coast of Norway at 84 feet (25.6 meters) with surrounding waves of approximately 40 feet (12 meters), making the original rogue wave about twice the size of those around it.                                                                                                                                                      , The record-breaking rogue wave recorded in November 2020 measured at almost 58 feet (17.6 meters) in comparison to surrounding waves of around 20 feet (6 meters), blowing the original proportions out of the water.                                                                                                                                                                                                        , Recording these "killer waves" is no easy feat                                                                                                                                                                                                                                                                                                                                                                               , The rogue wave in the study was measured via a MarineLabs buoy approximately 4.3 miles (7 kilometers) off of the coast of Ucluelet, British Columbia.                                                                                                                                                                                                                                                                        , "We're a real-time intelligence company, and we provide real-time updates on what is going on along the coastline, including wind, waves, and other data," Beatty explained.                                                                                                                                                                                                                                                 , The company produced a video simulation of the buoy around the time the rogue wave came through, showing the swell in comparison to the smaller surrounding waves.                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                              , The problem lies in how to continuously track rogue waves once identified by a sensor.                                                                                                                                                                                                                                                                                                                                       , "Most observations are at a single buoy, a single location, and so the wave passes through, and we know at this moment it was this high, but we don't know how long. That is the big science question," Gemmrich noted.                                                                                                                                                                                                      , One thing is known for sure: Rogue waves are not afraid to rock the boat.                                                                                                                                                                                                                                                                                                                                                    , Such waves can pose a significant threat to marine operations as well as the public due to their immense power and lack of predictability, Beatty stressed.                                                                                                                                                                                                                                                                  , "They are unexpected, so the vessel operator has little warning. If it is high enough that it can cause some damage to the vessel, the operator has no time to change course or react to it." Gemmrich added.                                                                                                                                                                                                                , One common misconception Gemmrich wanted to emphasize is rogue waves are not to be mistaken for tsunamis. Although both are known for being large waves, the way they come about is completely different.                                                                                                                                                                                                                    , "Rogue waves are generated by wind, so they are just a rare occurrence of wind generated waves. Whereas a tsunami is generated most commonly by an earthquake, underwater earthquake, or as we've seen recently a volcano eruption," Gemmrich stated.                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                              , Coastal communities everywhere are vulnerable to rogue waves. According to Gemmrich, anywhere exposed to water could experience a rogue wave, though places with strong currents may be more likely to see them.                                                                                                                                                                                                             , As for Vancouver Island, there was no reported damage from the rogue wave, as it occurred too far offshore. However, they can present onshore danger if they originate closer to the coast.                                                                                                                                                                                                                                  , To ensure better safety in the future, the scientific community is pushing for better research and forecasting to help prevent any damage to maritime operations or the public.                                                                                                                                                                                                                                              , Jennie Lyons at NOAA pointed out there are specialized distinctions for rogue waves.                                                                                                                                                                                                                                                                                                                                         ,  A "sneaker wave" typically describes a rogue wave condition along the beach because it sneaks up on you. Rogue waves out over open water much larger than those around it, are often called "freak" waves. And rogue waves large enough to damage a ship or cause a ship to roll more than normal are called "killer waves," because if they are severe enough, the damage could capsize a ship, potentially killing people., MarineLabs has a system of 26 buoys placed strategically in the oceans surrounding North America with hopes to more than double their number by the end of 2022.                                                                                                                                                                                                                                                             , "We are aiming to improve safety and decision-making for marine operations and coastal communities through widespread measurement of the world's coastlines," Beatty stated.                                                                                                                                                                                                                                                 , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/12/business/ukraine-business-economy.html </td>
   <td style="text-align:left;"> 2022-02-12 18:00:23 </td>
   <td style="text-align:left;"> Running a Business Under the Shadow of War - The New York Times </td>
   <td style="text-align:left;"> , “When you’re constantly thinking about invading Russians you’re not going to go buy a new phone, or a car, or a house.”                                                                                                                                                                                                                                                                                                                                                                    , The offices of Roosh, a digital venture company that invests in artificial intelligence start-ups, in Kyiv, Ukraine.Credit...Sasha Maslov for The New York Times                                                                                                                                                                                                                                                                                                                           , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Photographs and Text by Sasha Maslov                                                                                                                                                                                                                                                                                                                                                                                                                                                       , When I was flying to Kyiv from Odesa last month, I arrived at the airport to find a policewoman blocking an entrance to the terminal. A considerable crowd was gathered across the road. Apparently someone had called in a bomb threat.                                                                                                                                                                                                                                                   , Shocked at first, I looked around to see how the other passengers were reacting. Some people were on the phone, trying to rearrange their evening plans; some were just chatting among themselves or tapping away on their phones.                                                                                                                                                                                                                                                         , At that time, the Russian military presence on the border was growing, and the possibility of conflict was on people’s minds. But bomb threats like these have become routine.                                                                                                                                                                                                                                                                                                             , I made my way to a Georgian restaurant, the only place within walking distance to find warmth. The restaurant was buzzing — with airport workers, stranded passengers, overwhelmed waiters carrying trays with tea and snacks. At the next table over, a group of strangers were sharing a meal and discussing how frequently these minings — a term Ukrainians use for anonymous bomb threats — take place.                                                                               , Before long, I heard walkie-talkies murmur under the green jackets of the airport workers, and people began gathering their things. When I was leaving, I saw a handwritten note on the bathroom door that read: “Airport is unmined. Have a good flight.”                                                                                                                                                                                                                                 , Everyone was free to get on with their journey, and I continued on to do my work.                                                                                                                                                                                                                                                                                                                                                                                                          , I was in Kyiv in late January, a city that felt both unsettling and familiar, to capture people who were doing their jobs and hoping that everything they had built since the last conflict would not disappear in another round of fighting.                                                                                                                                                                                                                                              , Ukraine has never been a beacon of stability. Since the fall of the Soviet Union, an event that turned everything people knew in their life upside down, it has become a nation with “crisis” tattooed on its forehead.                                                                                                                                                                                                                                                                    , I was born in Kharkiv, a city just 50 kilometers away from the Russian border, in 1984. In my lifetime I have seen: the financial meltdown following the ruble crash of 1998; the Orange Revolution in 2004; the global financial crisis of 2008; and the Maidan revolution of 2014. The annexation of Crimea and the war with Russian-backed separatists in the East had followed, and now the coronavirus pandemic was being pushed aside by the new wave of Russian aggression.         , For the past several years in the business world, Ukraine has provided entrepreneurs with wild opportunities with high risks.                                                                                                                                                                                                                                                                                                                                                              , Andriy Fedoriv, 43, runs Fedoriv Agency, one of the leading ad and marketing agencies of Ukraine, with more than a hundred employees and several offices around the world. Ukrainians, he noted, had been living with some sort of a Russian troop presence for years and had gotten used to it.  “So we got used to it.”                                                                                                                                                                  , “We feel angry because we don’t want to start over again,” he said. “We have done so much with so little resources. We would like to continue creating value and not fighting. But if needed, we will.”                                                                                                                                                                                                                                                                                    , Ievgen Lavreniuk, 34, is one of the founders of the Dream House Hostel network. A backpacker and an avid traveler, Mr. Lavreniuk saw a gap in the market in Kyiv and opened a 24-bed hostel in 2011. Business took off, and the hostel moved to a larger space on St. Andrew’s descent, a picturesque old street that connects two parts of old Kyiv. Mr. Lavreniuk still operates this location, which has over a 100 beds, a little cafe and a bar. By 2019, he had hostels in 12 cities., More than 60 percent of hostel visitors in Kyiv come from abroad, Mr. Lavreniuk said, most from Germany, the United Kingdom and the United States. At the end of 2021, there was a wave of cancellations, which Mr. Lavreniuk initially blamed on the Omicron variant. But as coronavirus cases declined, the cancellations continued.                                                                                                                                                     , On feedback forms he started noticing that people were expressing fear of traveling to Ukraine.                                                                                                                                                                                                                                                                                                                                                                                            , “We might have these tensions with Russia for another month or two, but people will continue to think that Ukraine is a dangerous place for two or three years,” he said.                                                                                                                                                                                                                                                                                                                  , ZigZag is the kind of hip eatery that Dream House guests might want to try on their trip to Kyiv.                                                                                                                                                                                                                                                                                                                                                                                          , Its owner, Liubov Tsybulska, 36, used to work as a digital communications adviser with the Ukrainian Armed Forces, with a focus on Russian disinformation. She still does some work in that field, too. Last year, she helped start an organization dedicated to countering Russian disinformation, a joint venture between the government and civil organizations.                                                                                                                        , She tries to prepare her staff at the restaurant for the worst-case scenario. “We distributed brochures on what to do in case of war,” she said. “Interestingly, it was a brochure I helped develop when I was working in the government.”                                                                                                                                                                                                                                                 , At work one day, she and her employees decided to take a field trip: “We researched the nearest bomb shelter on the internet and went to take a look where it is,” she said.                                                                                                                                                                                                                                                                                                               , Denis Dmitrenko, 30, said he was trying to remain in “don’t panic mode.” Mr. Dmitrenko is a Kyiv native and managing partner of Roosh, a company that invests in artificial intelligence start-ups. (One hit for Roosh was the face-swapping video app Reface, which had viral moments in 2020.)                                                                                                                                                                                           , “We believe in Ukraine, and we want to build a global center for artificial intelligence here,” he said. At that point, nothing had altered those ambitions. “If things get worse, then we will react, but for now there is no plan B,” he said.                                                                                                                                                                                                                                           , Igor Mazepa, 45, was expecting an economic boom as the country emerged from the grips of the pandemic. Now Mr. Mazepa, the director general of Concorde Capital, an investment bank, is looking at things differently.                                                                                                                                                                                                                                                                     , “When you’re constantly thinking about invading Russians you’re not going to go buy a new phone, or a car, or a house,” he said.                                                                                                                                                                                                                                                                                                                                                           , Consumer spending was down, and he said that several deals had fallen through because one of the companies involved was too worried about the risks of sustained conflict.                                                                                                                                                                                                                                                                                                                 , But as of late January, one group wasn’t retreating from the market: “Ukrainian investors are more resistant to these waves of external pressure,” he said. He didn’t want to wager a bet on the future though.                                                                                                                                                                                                                                                                            , “Of course I can’t predict anything, especially when the fate of the world depends on the decision making process of one person,” he said.                                                                                                                                                                                                                                                                                                                                                 , Alik Mamedov, 53, is a fruit seller at Zhitnii Rynok — a Soviet modernist structure built on the site of the oldest market in town, dating back to 15th century. Mr. Mamedov had seen war arrive at his doorstep in Azerbaijan before he moved his family to Ukraine. “I’ve experienced it and wouldn’t want this to happen here,” he said. “This is my second home; I eat Ukrainian bread and walk on Ukrainian soil. My kids go to school here.”                                         , He still grows his pomegranates in Azerbaijan on land he owns and brings them to Kyiv to sell. But as tensions with Russia mount, business has been slow. “Before, people would buy a few kilos,” he said. “Now I sell just a couple of fruits to a customer.”                                                                                                                                                                                                                             , Elsewhere at Zhitnii Rynok, Valentyna Poberezhec, 63, a meat seller, said she had also seen a decline in sales — she blamed politicians. But she also was more optimistic than most. “Putin loves Ukrainian people; he won’t attack us,” she said late last month.                                                                                                                                                                                                                         , Iryna Chechotkina, 42, felt that her experience operating her business during past conflicts might prepare her for another one.                                                                                                                                                                                                                                                                                                                                                            , She is the co-founder and co-chief executive of Rozetka, an online retailer that she and her husband started 17 years ago. Home delivery for parcels is not as common in Ukraine as it is in the United States, and most often people ship their packages to a local Rozetka shop, which also serves as a retail store. Now, there are about 300 stores across Ukraine, and the company employs more than 8,000 people.                                                                    , She and her husband began the business amid an earlier crisis, Ms. Chechotkina said, and it has helped them build up resilience.                                                                                                                                                                                                                                                                                                                                                           , A brewing conflict. Antagonism between Ukraine and Russia has been simmering since 2014, when the Russian military crossed into Ukrainian territory, annexing Crimea and whipping up a rebellion in the east. A tenuous cease-fire was reached in 2015, but peace has been elusive.                                                                                                                                                                                                        , A spike in hostilities. Russia has been gradually building up forces near its border with Ukraine, and the Kremlin’s messaging toward its neighbor has hardened. Concern grew in late October, when Ukraine used an armed drone to attack a howitzer operated by Russian-backed separatists.                                                                                                                                                                                               , Preventing an invasion. Russia called the strike a destabilizing act that violated the cease-fire agreement, raising fears of a new intervention in Ukraine. Since then, the United States, NATO and Russia have been engaged in a whirlwind of diplomacy aimed at averting that outcome.                                                                                                                                                                                                  , The Kremlin’s position. President Vladimir V. Putin of Russia, who has increasingly portrayed NATO’s eastward expansion as an existential threat to his country, said that Moscow’s growing military presence on the Ukrainian border was a response to Ukraine’s deepening partnership with the alliance.                                                                                                                                                                                 , Rising tension. Western countries have tried to maintain a dialogue with Moscow. But the Biden administration warned that the U.S. could throw its weight behind Ukraine in case of an invasion. France, Germany and Poland also warned Russia of consequences if it launched incursions into Ukraine.                                                                                                                                                                                     , “We just became parents for the first time, the country was living in the aftermath of the Orange Revolution and the future felt rather uncertain,” she said. “Born during a time of change, our business was baptized from the start to be fast and flexible.”                                                                                                                                                                                                                            , She is not worried about the business adapting to ongoing tensions with Russia.                                                                                                                                                                                                                                                                                                                                                                                                            , “Perhaps, it is because we have all developed some immunity to this war,” she said.                                                                                                                                                                                                                                                                                                                                                                                                        , But looking back, she does see Ukraine at the time of the Crimea annexation and Ukraine today as two different countries.                                                                                                                                                                                                                                                                                                                                                                  , That divide is particularly stark for Emil Dervish, 30, a Crimean Tatar from a village near Simferopol. He opened his small architectural bureau in Kyiv in 2018. Even though his own home was occupied by Russians a few years prior — and he has traveled there only once since the occupation, when his father had a heart attack — he  refused to believe that Russia would advance further.                                                                                           , “It’s hard for me to imagine that here in the heart of Europe in the 21st century there will be a full-on invasion,” he said. “I think what’s going on is a way to psychologically oppress people and make them doubt if they want to live here.”                                                                                                                                                                                                                                          , Eno Enyieokpon, 34, a native of Nigeria, moved to Ukraine in 2017 after finishing college in Belarus and started his fashion brand, Iron Thread, the following year. “I feel like I’m meant to be here,” he said.                                                                                                                                                                                                                                                                          , For Mr. Enyieokpon, things in Ukraine have been working out well. His brand gained some popularity, and he now employs three people — though he still makes most of his clothing himself, selling it primarily to local artists.                                                                                                                                                                                                                                                           , “Right now, all my energy is concentrated on my show in six days,” he said late last month, in advance of Ukrainian fashion week. “After that, I’ll think about Russia.”                                                                                                                                                                                                                                                                                                                   , Darko Skulsky, 48, was born to Ukrainian American parents and grew up in Philadelphia. After getting a degree from George Washington University, he came to Ukraine in 1995.                                                                                                                                                                                                                                                                                                               , In 1998, he and his partner started Radioaktive Film, a production company that has done work on Samsung and Apple ads and “Chernobyl,” the HBO mini-series.                                                                                                                                                                                                                                                                                                                               , “You have to have a certain frame of mind to do business in this country,” Mr. Skulsky said. “It’s more turbulent, and there are more ebbs and flows. ”                                                                                                                                                                                                                                                                                                                                    , In December, Mr. Skulsky started hearing concern from clients about shooting in Ukraine. After that, one verbal agreement after another failed to materialize into a signed contract, and work was being canceled or postponed.                                                                                                                                                                                                                                                            , Radioaktive Film lost some contracts, and Mr. Skulsky and his partner transferred some work to their offices in Poland and Georgia. But Mr. Skulsky’s life is in Ukraine.                                                                                                                                                                                                                                                                                                                  , “I still wake up here every day, have my coffee and take my kids to school,” he said.                                                                                                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/technology/cisco-made-20-billion-plus-takeover-offer-for-splunk </td>
   <td style="text-align:left;"> 2022-02-12 17:08:01 </td>
   <td style="text-align:left;"> Cisco made $20 billion-plus takeover offer for Splunk </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                         , Cisco Systems Inc. has made a takeover offer worth more than $20 billion for software maker Splunk Inc., according to people familiar with the matter, in what would be the networking giant's biggest acquisition ever.                                                                                                                                                                                                  , The offer was made recently and the companies aren't currently in active talks, some of the people said.                                                                                                                                                                                                                                                                                                                  , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                               , Should there be a deal, it would be Cisco's biggest ever, eclipsing the roughly $7 billion acquisition of Scientific Atlanta in 2005. Its most recent deal of size was its nearly $5 billion purchase of Acacia Communications Inc. in 2021.                                                                                                                                                                              , FILE PHOTO - The logo of Dow Jones Industrial Average stock market index listed company Cisco is seen in San Diego, California REUTERS/Mike Blake/File Photo                                                                                                                                                                                                                                                              , Splunk is currently searching for a chief executive after Doug Merritt stepped down from the role in November after roughly six years following a series of disappointing earnings reports. The company named Chairman Graham Smith as interim CEO, a position he still holds.                                                                                                                                            , Splunk shares rose sharply early in the pandemic as did those of a number of other technology companies with strong growth potential, but have almost fallen in half since then.                                                                                                                                                                                                                                          , It isn't clear whether other potential suitors are circling Splunk.                                                                                                                                                                                                                                                                                                                                                       , CISCO FORECAST KNOCKED BY SUPPLY CHAIN SNAGS, SHARES FALL                                                                                                                                                                                                                                                                                                                                                                 , Splunk, founded in 2003, makes software used by companies' information-technology and security operations to monitor and analyze data.                                                                                                                                                                                                                                                                                    , San Jose, Calif.-based Cisco, run by Chief Executive Chuck Robbins, sells routers, switches and security services as well as software products such as its Webex meeting application. It already has a data-security partnership with Splunk.                                                                                                                                                                             , In a sign of the increasing importance it places on software, Cisco in September said it would introduce new financial metrics and overhaul its reporting segments to showcase the growth of its software business.                                                                                                                                                                                                       , The idea was to illustrate the company's shift toward software and recurring revenue, Chief Financial Officer Scott Herren said at the time.                                                                                                                                                                                                                                                                              , VERIZON EXEC SAYS GAME CHANGING 5G THE 'FUTURE OF GROWTH'                                                                                                                                                                                                                                                                                                                                                                 , Software sales accounted for 30% of Cisco's total revenue in fiscal 2021. The company said it wanted subscriptions to generate 50% of annual revenue in fiscal 2025, up from 44%. Cisco reported revenue of $49.8 billion for the year, up 1%. Net income was $10.6 billion, down 6%.                                                                                                                                     , Cisco's interest shows that the networking giant -- a serial acquirer, but usually of smaller companies -- has an appetite for big deals.                                                                                                                                                                                                                                                                                 , And it has the wherewithal, with a market value of around $230 billion and more than $20 billion in cash and short-term investments.                                                                                                                                                                                                                                                                                      , Software has been a hot corner of the M&amp;A market lately, with a number of companies in the sector being snapped up by private-equity firms or other industry players. In one of the latest examples, Citrix Systems Inc. agreed to be taken private by a pair of private-equity firms in an acquisition valued at $16.5 billion, including debt.                                                                          , Splunk said in June that technology-focused private-equity firm Silver Lake was making a $1 billion investment in the company to help support the transformation of the business. Splunk has been shifting from a traditional software-licensing arrangement to a cloud-based subscription model. An increase in the shares on news of that investment had evaporated by the close of trading Friday.                     , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                   , Cisco wouldn't be the only legacy technology company making a big bet on future growth through a flashy acquisition. Microsoft Corp. in January agreed to buy videogame maker Activision Blizzard Inc. for about $75 billion in what would be its largest acquisition by far. In December, Oracle Corp. agreed to buy electronic-medical-records company Cerner Corp. for more than $28 billion, in its biggest deal ever., Cisco is set to report its fiscal second-quarter earnings Feb. 16, while Splunk reports March 2.                                                                                                                                                                                                                                                                                                                          , Nina Trentmann contributed to this article.                                                                                                                                                                                                                                                                                                                                                                               , Write to Dana Cimilluca at dana.cimilluca@wsj.com and Cara Lombardo at cara.lombardo@wsj.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/12/business/economy/small-town-living-standard.html </td>
   <td style="text-align:left;"> 2022-02-12 16:00:16 </td>
   <td style="text-align:left;"> Why Small Towns Are Attracting More Newcomers - The New York Times </td>
   <td style="text-align:left;"> , Incomes are low in small-town Tennessee, but so is the cost of living. That attraction could be a key to reviving many rural areas.                                                                                                                                                                                                                                                                                                                                      , The town of Granville in Jackson County, Tenn., is filled with museums and shops celebrating small-town life. Credit...                                                                                                                                                                                                                                                                                                                                                  , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                             , By Eduardo Porter                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Photographs by Stacy Kranitz                                                                                                                                                                                                                                                                                                                                                                                                                                             , GAINESBORO, Tenn. — There is not much to suggest prosperity in Gainesboro, a hamlet of 920 in Tennessee’s Upper Cumberland region. Almost one in seven homes are vacant. One-quarter of the population lives in poverty.                                                                                                                                                                                                                                                 , Yet from his office in the Jackson County Courthouse, County Mayor Randy Heady outlines a picture of plenty: Revenue from sales and occupancy taxes almost doubled in the last fiscal year, and he expects another 20 percent increase this year. “Sales tax is up, occupancy tax is up, liquor tax is up,” he said.                                                                                                                                                     , And outsiders are flocking into the county. “They are coming from other states, trying to get away from the high taxes,” Mr. Heady said. “People are moving from Arizona and California, New York and New Jersey.”                                                                                                                                                                                                                                                       , Economists have long voiced fear that rural places like this are being left behind. The last of the textile businesses, once an economic mainstay, departed in the 1990s. Jackson County and several other counties in the Upper Cumberland are considered “distressed” or “at risk” by the Appalachian Regional Commission.                                                                                                                                             , Celina                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Tennessee                                                                                                                                                                                                                                                                                                                                                                                                                                                                , JACKSON                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , County                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Gainesboro                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Overton                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , County                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Cookeville                                                                                                                                                                                                                                                                                                                                                                                                                                                               , PUTNAM County                                                                                                                                                                                                                                                                                                                                                                                                                                                            , 10 miles                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , VA.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , KEN.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Nashville                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Knoxville                                                                                                                                                                                                                                                                                                                                                                                                                                                                , TENNESSEE                                                                                                                                                                                                                                                                                                                                                                                                                                                                , N.C.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , MISS.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , S.C.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , GA.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , ALA.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , 100 miles                                                                                                                                                                                                                                                                                                                                                                                                                                                                , By The New York Times                                                                                                                                                                                                                                                                                                                                                                                                                                                    , But the newcomers are fueling a boomlet in the area, based on a simple economic proposition: It is pretty, and it is cheap. While Jackson County’s typical household makes $35,207 a year, just over half the national average, the low cost of living allows residents to punch far above their weight in economic terms.                                                                                                                                               , Some local businesses are busier than ever. Carol Abney has 250 clients for an internet-based accounting practice she runs from her husband’s auto-repair shop in Celina, about half an hour north of Gainesboro in Clay County. “I’m booming,” she said.                                                                                                                                                                                                                , While the good times are still fragile, the turnaround could suggest a path for other rural areas to shake off their persistent story of decline.                                                                                                                                                                                                                                                                                                                        , “Our county has been growing pretty steadily over the last five years, but really growing in the last couple,” said Randy Porter, the mayor of Putnam County, the most populous in the region.                                                                                                                                                                                                                                                                           , The region has a couple of things in its favor. It has long drawn summer tourists for hunting and fishing, as well as retirees who come from as far away as Ohio to settle among the rivers, lakes and hollers.                                                                                                                                                                                                                                                          , Cookeville, the region’s largest city, is home to the Tennessee Technological University, which has about 10,000 students. The university estimates that in the 2019-20 academic year it contributed $860 million to the economy of the Upper Cumberland region and added 7,356 jobs.                                                                                                                                                                                    , While manufacturing jobs in the commuting zone centered in Cookeville were nearly halved between 1990 and 2010, it has staged a bit of a rebound since then. Before the coronavirus pandemic, jobs reached over 14,000, about one-fifth of the region’s total employment, compared with 8.5 percent nationwide. The unemployment rate is 3.5 percent, considerably below the national average.                                                                           , But there is another dynamic that Mayor Heady and others are hoping will stick: an exodus of workers fleeing the cost of living in big cities. The area is about an hour-and-a-half drive from Nashville, allowing for a not-unreasonable commute. Many of the new residents are coming from farther away.                                                                                                                                                               , The eight counties in the commuting zone are home to about 220,000. From 2010 to 2020, migration from the rest of the country bumped the population by almost 15,000. In 2020 alone, it grew by 2,692, making up almost all of the region’s population gain.                                                                                                                                                                                                             , And the pandemic has only added to the trend, Mr. Heady and Mr. Porter say, by encouraging workers to leave congested and expensive urban hubs and work remotely from the Upper Cumberland. If remote work remains widespread, their counties could benefit from a decisive price advantage.                                                                                                                                                                             , Research by Rebecca Diamond, an economist at Stanford University, and Enrico Moretti, an economist at the University of California, Berkeley, explains the attraction. They worked out how costs affect living standards in various parts of the country.                                                                                                                                                                                                                , Workers without a four-year college degree earn little in the Cookeville commuting zone — their income puts them among the poorest 10 percent of households in hundreds of commuting zones across the country. After adjusting for the local cost of living, however, their purchasing power rises to the top 10 percent.                                                                                                                                                , They can live more comfortable lives than if they moved to a bigger city, like Nashville or Knoxville. According to Ms. Diamond and Mr. Moretti’s work, which is based on data from 2014, the household income of a typical worker who never finished high school in Cookeville is about $43,000. In New York it is $58,000; in San Francisco, $62,000.                                                                                                                  , Still, adjusting for the local cost of living, the workers in San Francisco and New York could afford much less — roughly what someone with an income of $37,000 could buy in a city like Cleveland, which ranks in the middle of the national income distribution. The Cookeville workers, by contrast, live as if they were making $46,000 in Cleveland.                                                                                                               , Big cities are not that good a deal for even highly educated workers. They do earn much higher wages in New York than in Cookeville — indeed, the college educated reap a bigger pay premium if they work in bigger cities than their less-educated peers. But according to the researchers, all the extra wages are eaten up by higher costs.                                                                                                                           , It’s mostly about housing. Last November, the typical home in Cookeville cost $217,303, according to Zillow. That’s one-fourth of the median price of a home in Los Angeles and one-sixth of the price in San Francisco. Median rent in Jackson County is $548 per month.                                                                                                                                                                                                , Housing costs are putting a big dent in the case for urban America. “If you are trying to raise people’s standard of living you want to move them away from big cities not towards them,” said Jesse Rothstein, an economist at the University of California, Berkeley. He wrote a research paper with David Card, his colleague at Berkeley, and Moises Yi of the Census Bureau that pours more cold water on the supposed advantages of America’s megalopolises.       , David Autor, an economist at the Massachusetts Institute of Technology who has studied how jobs vary across urban and rural areas, agreed: “The notion of ‘go to the city, young man or woman,’ is simply not true.”                                                                                                                                                                                                                                                     , People are catching on. In 2020, 110,000 more people left Los Angeles than arrived from other parts of the country; New York City lost 150,000 people. “California is the main source of people, also New York and Oregon for some reason,” Mr. Porter said of Jackson County. “Folks sell their home, move here and can buy a house that’s twice the size for half the price.”                                                                                          , Cassie and Pete Kessler offer a glimpse into the Upper Cumberland’s improved fortunes. They arrived from Clearwater, Fla., where she tended bar and he cooked for restaurants on the beachfront. Following the hint of a regular who hailed from Tennessee, they gave the region a shot. In July 2020, they opened the Stolen Coin Oyster Bar &amp; Bistro in Gainesboro, across the street from the courthouse.                                                             , They offer a Louisiana-inflected menu, with fresh, grilled or fried oysters, a shrimp-and-andouille starter in a Cajun Creole sauce and entrees like pecan-crusted salmon. Not quite standard fare for these parts. “They said people here won’t eat that,” Ms. Kessler said. But they did very good business. Sales hit $685,000 in 2021, she said — and not for lack of competition.                                                                                   , The fancier Bull and Thistle opened on the same block a few months before the Stolen Coin. The 12 Degrees Tavern came a few months before that. There is a new Mexican place by the Marathon gas station. One block over, the Roaring River Distillery opened in November.                                                                                                                                                                                               , “In 2018, the only restaurant we had was Faye’s Cafe,” Mr. Heady said. “A country breakfast joint.”                                                                                                                                                                                                                                                                                                                                                                      , The Kesslers are so optimistic that they sunk much of their first-year profit into a “speakeasy” upstairs. They have a deal to buy the building in which the Stolen Coin sits — which they rent for $800 a month — for $54,000.                                                                                                                                                                                                                                          , But whether the area’s budding prosperity will continue remains an open question. The explosion in sales filling the coffers in Jackson and Putnam Counties was propelled in part by the multitrillion-dollar economic rescue packages passed by Congress in 2020 and 2021. That stimulus is largely over.                                                                                                                                                               , It is also unclear how big and permanent a change remote work will bring about in the Upper Cumberland. Some early research suggested that the workers who were leaving cities during the pandemic mainly moved to nearby suburbs and exurbs.                                                                                                                                                                                                                            , Others have bet on the area before. In the 1990s, a man who owned a construction company in the Florida Keys bought a lot of buildings in Gainesboro, hoping the region would bounce back from the doldrums and he would mint a fortune. “He didn’t want to sell, waiting for it to appreciate,” Mr. Heady said. “But the appreciation didn’t happen.” Or at least not fast enough. The man died in January.                                                             , The other question is what will happen if the comeback endures. Mr. Porter, the mayor of Putnam County, says his biggest concern is how to keep up with population growth. “We never thought we would be growing at the pace we’re growing,” he said. This summer, the county will start building the third new school since he took office in 2014.                                                                                                                     , There is a downside to out-of-towners' snapping up cheap real estate. The median home price in Cookeville has risen over 60 percent since the end of 2016, according to Zillow, outpacing a nationwide increase of 50 percent and vastly outstripping price increases in New York, Los Angeles and Chicago. Mr. Porter told of a newly married local couple who bid on 16 homes in Cookeville, without success, even when they offered the full asking price.            , And an influx of new residents is likely to bring other changes to a rural community that is considerably whiter and more conservative than urban America. More than 80 percent of Putnam County’s population is white and not Hispanic. Donald Trump won 71 percent of the county vote in the presidential election of 2020. Jackson County skews even more in this direction.                                                                                          , Skyler Beason, Mr. Kessler’s right-hand man in the kitchen of the Stolen Coin, and his girlfriend, Hailey Allen, a photographer, welcome the changes they see. They are young: 25 and 27. Both grew up in the region. They live in Cookeville, and neither wants to leave. “It’s gotten very progressive,” Mr. Beason said.                                                                                                                                              , Brie Flora, 30, a jeweler and metalsmith who came from Boston, is the face of such progressivity. She and her partner moved to a farm in nearby Overton County in 2016 and bought a home in Cookeville two years later. A few months ago, she and a friend opened an art gallery, The Silver Fern. “This is definitely home,” she said. Still, the “red-state feel” unnerves her. And she roots for a new nonprofit group that aims to help L.G.B.T.Q. youth in the area., Not everybody will embrace the change the out-of-towners may bring. Local residents “don’t want people to come with the intent to change the community,” Mr. Porter said. The question, perhaps, is whether that is the price of prosperity.                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/12/business/kroger-grocery-stores-workers-pay.html </td>
   <td style="text-align:left;"> 2022-02-12 16:00:10 </td>
   <td style="text-align:left;"> Business Booms at Kroger-Owned Grocery Stores, but Workers Are Left Behind - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , A number of the stores’ nearly 500,000 employees have reported being homeless, receiving government food stamps or relying on food banks.                                                                                                                                                                                                                                                                                                                                                                                                                                                      , By Sapna Maheshwari and Michael Corkery                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , When Enrique Romero Jr. finishes his shift fulfilling online orders at a Fred Meyer grocery store in Bellingham, Wash., he often walks to a nearby plasma donation center. There, he has his blood drained, and a hydrating solution is pumped into his veins, a process that leaves him tired and cold.                                                                                                                                                                                                                                                                                       , Mr. Romero, 30, said selling his plasma made him feel “like cattle.” But the income he earns from it — roughly $500 a month — is more reliable than his wages at Fred Meyer, which is owned by the grocery giant Kroger. His part-time hours often fluctuate, and he struggles to find enough money to cover his rent, his groceries and the regular repairs required to keep his 2007 Chevy Aveo on the road.                                                                                                                                                                                 , “The economy we have is grueling,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Business has boomed during the pandemic for Kroger, the biggest supermarket chain in the United States and the fourth-largest employer in the Fortune 500. It owns more than 2,700 locations, and its brands include Harris Teeter, Fred Meyer, Ralphs, Smith’s, Pick ’n Save and even Murray’s Cheese in New York City. The company, which is based in Cincinnati, said in December that it was expecting sales growth of at least 13.7 percent over two years. The company’s stock has risen about 36 percent over the past year.                                                            , But that success has not trickled down to its vast work force of nearly 500,000 employees, a number of whom have reported being homeless, receiving government food stamps or relying on food banks to feed their families. A brief strike in Colorado last month by workers, represented by the United Food and Commercial Workers Union, at dozens of Kroger-owned King Soopers locations brought renewed scrutiny to the issues of pay and working conditions for grocery workers, who have been on the front lines throughout the pandemic.                                                , The Economic Roundtable, a nonprofit research group that surveyed more than 10,000 Kroger workers in Washington, Colorado and Southern California about their working conditions for a report commissioned by four units of the food workers union, found that about 75 percent of Kroger workers said they were food insecure, meaning they lacked consistent access to enough food for an active, healthy life. About 14 percent said they were homeless or had been homeless in the previous year, and 63 percent said they did not earn enough money to pay for basic expenses every month., “There is a race to the bottom that’s been going on for a while with Walmart and other large retail stores, and also restaurants, and to reverse that trend is not easy,” said Daniel Flaming, president of the Economic Roundtable.                                                                                                                                                                                                                                                                                                                                                           , Kroger was the sole employer for 86 percent of those surveyed, partly because more than half had schedules that changed at least every week, making it difficult to commit to another employer. About two-thirds said they were part-time workers, even though they wanted more hours. Keeping workers part time is a strategy employers use to encourage turnover and reduce costs.                                                                                                                                                                                                           , Kristal Howard, a spokeswoman for Kroger, said the report was “one-dimensional and does not tell the complete story.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , “Kroger has provided an incredible number of people with their first job, second chances and lifelong careers, and we’re proud to play this role in our communities,” she said. Ms. Howard added that the company had raised its national average hourly rate of pay to $16.68 from $13.66 in 2017, a 22 percent increase, and that its benefits package included health care, retirement savings, tuition assistance and on-demand access to mental health assistance.                                                                                                                        , Some of the workers said that even though other retailers and fast food restaurants had started offering higher starting wages than Kroger, the company’s health insurance and retirement benefits, which the union negotiated, were more generous than what other employers offered. Other part-time Kroger workers say they stay on the job because they don’t want to lose their seniority and the chance for a full-time role.                                                                                                                                                             , Despite some of the wage increases and benefits, working at a grocery store no longer provides the stable income and middle-class lifestyle that it did 30 years ago, workers say. The Economic Roundtable report studied contracts dating back to 1990 and said the most experienced clerks — known as journeymen — in Southern California made roughly $28 per hour in today’s dollars while working full-time schedules. Wages for top-paid clerks today are 22 percent lower, and those workers are far more likely to be working part-time hours.                                         , Ashley Manning, a 32-year-old floral manager at a Ralphs in San Pedro, Calif., works full time but is regularly strapped for cash. Ms. Manning, the single mother of a 12-year-old, said she had worked at Ralphs for nine years and earned $18.25 an hour. It took her four years to reach full-time status, which guarantees 40 hours per week and comes with an annual bonus ranging from $500 to $3,000.                                                                                                                                                                                   , She said she struggled to pay rent and moved into her grandmother’s house after being evicted last spring. She has needed help from her family to help pay for a car. She has tried to make extra money through a party planning and decorating business, but demand for those services dried up in the pandemic.                                                                                                                                                                                                                                                                              , “I would think, ‘I have a good job and make decent money,’ and I don’t,” Ms. Manning said. “I’m still on the poverty level.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , During the pandemic, grocery store workers have been recognized as essential to keeping society going, but they have also faced health risks. At least 50,600 grocery workers around the country have been infected with or exposed to the coronavirus, and at least 213 have died from the virus, according to the United Food and Commercial Workers International Union.                                                                                                                                                                                                                    , Ms. Manning was hospitalized for Covid-19 last summer. She blames herself for her grandmother’s subsequent death from the virus in August.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , “She was one of the people that would help me the most, if I was short on a bill or needed help, to pick my daughter up from school,” she said. But when her grandmother was in critical condition, Ms. Manning said, she was told that she couldn’t take more time off after being sick with Covid-19.                                                                                                                                                                                                                                                                                        , The illness and the company’s response were jarring, given that corporate workers had the flexibility to work from home, she said, adding that she ultimately took disability leave for a stretch.                                                                                                                                                                                                                                                                                                                                                                                             , Kroger has one of the country’s starkest gaps between a chief executive’s compensation and that of the median employee. Rodney McMullen, Kroger’s chief executive since 2014, earned $22.4 million in 2020, while the median employee earned $24,617 — a ratio of 909 to 1. The average C.E.O.-to-worker pay ratio in the S&amp;P 500 is 299 to 1, with grocery chains like Costco (193 to 1) and Publix (153 to 1) lower than that.                                                                                                                                                               , These disparities have fomented outrage among employees, who are also dealing with issues like fights over masks and theft and violence in stores.                                                                                                                                                                                                                                                                                                                                                                                                                                             , In Colorado, more than 8,000 workers at the Kroger-owned King Soopers chain walked off the job last month when union contract negotiations broke down over wages, employee safety issues and scheduling.                                                                                                                                                                                                                                                                                                                                                                                       , Around the time of the strike, a nonprofit publication, A More Perfect Union, published an internal Kroger document in which the company acknowledged that one in five of its employees received government assistance in 2017. The document also included research showing that employee turnover was lower in places where it raised wages.                                                                                                                                                                                                                                                  , In response, Kroger said it had developed an improvement plan after the analysis, which included the wage increase and steps to improve tuition assistance and retirement benefits. The company commissioned its own study that stated last month that Kroger’s average pay and benefits in Colorado and three other Western states were higher than those of other retailers.                                                                                                                                                                                                                 , After more than a week of picketing, the union — Local 7 of the U.F.C.W. — won large concessions, including wage increases and a plan to move at least 500 part-time workers into full-time roles within a few months.                                                                                                                                                                                                                                                                                                                                                                         , As successful as the strike was for workers in Colorado, Larry Cohen, former president of the Communications Workers of America, said the contracts covered only employees at specific Kroger chains, making it difficult for unions to gain broader leverage.                                                                                                                                                                                                                                                                                                                                 , “When all contracts are local, how do you deal with a giant national company?” Mr. Cohen said. “Not very well.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Kroger has tightly controlled labor expenses during the pandemic. The company offered hero pay and thank-you bonuses to workers in the early months of the pandemic but ended those well before vaccinations were available. (Grocery workers were also not given priority for vaccinations in many states.) While some municipalities like Los Angeles and Seattle sought to institute hazard pay mandates, Kroger and grocery lobbying associations fought such efforts.                                                                                                                     , Kroger’s resistance to wage increases peaked last year when the Los Angeles City Council approved a hazard pay mandate requiring large grocers and pharmacies to pay employees an additional $5 an hour for four months. In response, Kroger said it would close three stores in the area in May — two Ralphs locations and a Food 4 Less — blaming increased costs. The company pointed to a release at the time that said the stores were underperforming. But City Council members were left with the sense that the closures were retaliatory.                                             , Paul Koretz, a member of the Council, said he had dealt with backlash from some constituents about the impending closing of a Ralphs in his district, a go-to for the local Orthodox Jewish community. He said Ralphs representatives had warned him that they would close the store if the mandate was instituted.                                                                                                                                                                                                                                                                            , “I’m not sure I really believed that Ralphs would do it,” he said. “It just seemed so counterintuitive that you would mess with your very loyal customers.”                                                                                                                                                                                                                                                                                                                                                                                                                                    , Shoppers in his district have adapted since the store closed. But he said he believed that the impact of the closings on employees and Council members’ fear of angering constituents probably had a chilling effect on other municipalities that were considering similar measures.                                                                                                                                                                                                                                                                                                           , The mandated hazard pay gave many Kroger workers a glimpse of how their day-to-day lives could improve with more money. Areli Rivas, a part-time cashier at a Ralphs in Van Nuys, Calif., who is married to a full-time worker at the store, said the extra pay gave her “peace of mind.”                                                                                                                                                                                                                                                                                                      , The mother of two said it was hard to justify purchases like a new backpack for her son, even though his current one is fraying. More pay would also allow her to get her daughter a new glasses prescription.                                                                                                                                                                                                                                                                                                                                                                                 , Some workers like Ms. Manning said that they couldn’t afford to shop at their store and that the employee discount of 10 percent applied only to Kroger-branded goods and did not always include produce and other essentials.                                                                                                                                                                                                                                                                                                                                                                 , Kroger said that the discount covered 19,000 private-label food products and that it did include dairy, proteins and produce.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Pio Figueroa, 25, who has been working at a Ralphs in Laguna Beach, Calif., for about six years, said he was able to manage his monthly expenses now that he was among the highest earners in his store, making about $22.50 an hour. But at one point, he was making $15 or $16 per hour at the chain and struggled mightily.                                                                                                                                                                                                                                                                 , “There were times I could only budget to spend $100 on food and everything a week,” he said. “So there were times I would go without a meal or definitely think, ‘What am I going to eat tonight?’”                                                                                                                                                                                                                                                                                                                                                                                            , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gsci </td>
   <td style="text-align:left;"> 2022-02-12 11:00:30 </td>
   <td style="text-align:left;"> S&amp;P GSCI Hits 6-1/2-year High </td>
   <td style="text-align:left;"> S&amp;P GSCI increased to a 6-1/2-year high of 3219 Index Points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/manganese </td>
   <td style="text-align:left;"> 2022-02-12 09:00:19 </td>
   <td style="text-align:left;"> Manganese Hits 12-week High </td>
   <td style="text-align:left;"> Manganese increased to a 12-week high of 34.5 CNY/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/neodymium </td>
   <td style="text-align:left;"> 2022-02-12 09:00:16 </td>
   <td style="text-align:left;"> Neodymium Hits All-time High </td>
   <td style="text-align:left;"> Neodymium increased to an all-time high of 1410000 CNY/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coal </td>
   <td style="text-align:left;"> 2022-02-12 07:45:57 </td>
   <td style="text-align:left;"> Coal Hits 17-week High </td>
   <td style="text-align:left;"> Coal increased to a 17-week high of 245 USD/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/cryptocurrency-investors-face-tax-season-challenges </td>
   <td style="text-align:left;"> 2022-02-12 06:32:03 </td>
   <td style="text-align:left;"> Cryptocurrency investors face tax season challenges </td>
   <td style="text-align:left;"> Gem Mining CEO John Warren and Rosecliff founder Mike Murphy give their take on the benefits of mining Bitcoin and if stock picking should be allowed for everyone on 'Making Money.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Now that tax season is in full swing, taxpayers who participated in last year’s boom in cryptocurrency and other digital assets like non-fungible tokens (NFTs) are figuring out what it all means for their taxes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , For investors without tax savvy, navigating surprise tax bills or complex crypto tax situations could be a challenge during the filing season, so it is important to be well-prepared. Even if cryptocurrency aims to be an alternative to the U.S. dollar, it does not change Americans' tax obligations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , REAL-TIME CRYPTOCURRENCY PRICING DATA: CLICK HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The Internal Revenue Service (IRS) treats cryptocurrency and other digital assets like property, meaning a taxpayer may owe tax when they exchange or sell assets for a profit. Tax may be due even if a taxpayer exchanges assets for a good or service, such as buying a vehicle with cryptocurrency from e-commerce sites like eBay.                                                                                                                                                                                                                                                                                                                                                                                                                                                        , THREE CHANGES TO KNOW THIS TAX SEASON                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , While the policy discussion in Washington, D.C. has focused on tax reporting rules for crypto transactions, the rules are not scheduled to kick in for several years. Taxpayers are not, however, released from reporting their transactions to the IRS. This year’s individual income tax return asks up front: "did you receive, sell, exchange, or otherwise dispose of any financial interest in any virtual currency?" The question is meant to remind taxpayers about their crypto transactions while making it harder for people to ignore their tax obligations.                                                                                                                                                                                                                       , VENMO, PAYPAL AND CASH APP TO REPORT PAYMENTS OF $600 OR MORE TO IRS THIS YEAR: WHAT TO KNOW                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , THE IRS STARTS SATURDAY WALK-IN SERVICE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The tax filing season may also be tricky for crypto investors because of an overwhelmed IRS. The nation’s tax collector is still catching up on last tax season and issued a public service announcement earlier in the year telling taxpayers to be patient for their returns. Because of the backlog, it will be difficult to contact someone at the IRS if a taxpayer has questions about how they should approach their crypto transactions. Even professional preparers may run into difficulty, particularly when helping taxpayers who did not record their crypto tax basis and engaged in a high number of transactions.                                                                                                                                                              , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , It’s not all bad news, though, as crypto investors may see some upsides this year. The volatility of digital assets resulted in many taxpayers selling at a loss, which can in turn be used to offset crypto gains, or even gains from other sources. In fact, taxpayers may even buy back digital assets within 30 days of selling at a loss without losing the value of the loss deduction. The process, known as a wash sale, is banned for most other assets – investors must wait at least 31 days to repurchase a stock, for example, and still be eligible for a loss deduction. As with many evolving tax issues, don’t expect wash sales to be fair game forever – Congress is considering rules to treat crypto like other financial assets, including barring the use of wash sales., Policymakers have a few options to help taxpayers who are new to trading digital assets and dealing with complicated tax situations. Among them, providing a small exemption for realized gains because the compliance costs associated with paying taxes on small gains outweigh what little revenue would be raised.                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Taxpayers can help themselves by following general best practices when it comes to filling taxes: start the process early in the tax season, ensure proper documentation of transactions, and know when to get extra help by contacting a professional tax service. Taxpayers have until April 18th in most states to file their returns, and it’s better to get it right the first time than to get it wrong and be in a prolonged back-and-forth with the IRS.                                                                                                                                                                                                                                                                                                                               , By following best practices, taxpayers with crypto-related income are much more likely to have a smoother tax filing process amid all the challenges they will face this year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Watson and Muresianu are federal policy analysts at the Tax Foundation, a nonpartisan think tank in Washington, D.C.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-02-12 05:41:00 </td>
   <td style="text-align:left;"> Brent Crude Surges to $95 </td>
   <td style="text-align:left;"> Brent crude futures climbed 4% to hit $95, its highest since 2014 after the White House said that Russia could invade Ukraine at any time. The upward pressure on prices was already present earlier after the IEA said supply tensions will rise if the persistent gap between OPEC+ output and its target levels continues. The IEA also pointed out that Saudi Arabia and the United Arab Emirates could pump more oil as they still have spare capacity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/lillys-covid-19-treatment-gets-fdas/story.aspx?guid={AEFF7CC6-A5F6-40EA-98B7-11A1D9A2A31F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-12 05:40:58 </td>
   <td style="text-align:left;"> Lilly's COVID-19 treatment gets FDA's emergency-use approval - MarketWatch </td>
   <td style="text-align:left;"> Eli Lilly &amp; Co. 
        LLY,
        -1.63%
       said late Friday that the U.S. Food and Drug Administration has issued an emergency-use authorization for bebtelovimab, the pharma company's antibody treatment for COVID-19. Bebtelovimab now can be used for the treatment of mild-to-moderate COVID-19 in adults as well as children older than 12 years of age and over a certain weight who are at high risk of severe COVID-19 and for whom treatment options may be limited. Lilly announced late Thursday that the U.S. government had agreed to buy about 600,000 doses of bebtelovimab pending the EUA. Shares of Lilly were flat in the extended session after ending the regular trading day down 1.6%.  , Mexico has acknowledged that the U.S. government has suspended all imports of Mexican avocados after a U.S. plant safety inspector in Mexico received a threat.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2022-02-12 05:39:36 </td>
   <td style="text-align:left;"> Indian Rupee Hits 7-week Low </td>
   <td style="text-align:left;"> USDINR increased to a 7-week high of 75.596 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-12 05:33:00 </td>
   <td style="text-align:left;"> Crude Oil Hits $94 </td>
   <td style="text-align:left;"> WTI crude futures surged more than 4.5% to almost hit $94 per barrel on Friday afternoon, its highest since 2014 after the White House said that Russia could invade Ukraine at any time. The upward pressure on prices was already present earlier after the IEA said supply tensions will rise if the persistent gap between OPEC+ output and its target levels continues. The IEA also pointed out that Saudi Arabia and the United Arab Emirates could pump more oil as they still have spare capacity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 05:31:00 </td>
   <td style="text-align:left;"> Brazilian Equities Rise for 4th Day </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, closed 0.2% up at 113,572 on Friday, extending gains for a fourth straight session, driven by banks, after Brazil's biggest lender Itaú beat fourth-quarter profit estimates and gave an upbeat 2022 outlook. Also, oil company Petrobras advanced tracking rising oil prices. Meanwhile, investors digested concerns over a more hawkish Federal Reserve, escalating geopolitical tensions and domestic fiscal worries. On the data front, the IBC-Br index of economic activity in Brazil pointed to the second consecutive month of rising economic activity in December, although at a weaker pace. The Bovespa rose 1.2%, extending gains for a fifth straight week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 05:21:00 </td>
   <td style="text-align:left;"> US Stocks End Friday's Session Sharply Lower </td>
   <td style="text-align:left;"> Three main US stock market indexes finished sharply lower as investors turned to safe assets on growing tensions between Russia and Ukraine and tried to weigh the Fed's response to persistent inflation. The Dow ended 504 points down, the S&amp;P 500 declined 1.9% and the Nasdaq shed 2.8%. The White House has warned Russia could invade Ukraine at any time, as more Russian troops were moved towards the border, urging Americans to leave. Yesterday, St. Louis Fed President Bullard called for two 50 bps hikes by the start of July after the data showed inflation hit 7.5% in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-ends-down-500-points/story.aspx?guid={2C227F88-0F77-4D67-AEA3-F6ECE29F7A4B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-12 05:04:26 </td>
   <td style="text-align:left;"> Dow ends down 500 points as U.S. says Russia invasion of Ukraine could happen 'any day now' - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended sharply lower Friday after White House National Security Adviser Jake Sullivan warned that a Russian invasion of Ukraine could happen "any day now." The Dow Jones Industrial Average 
        DJIA,
        -1.43%
       fell 504 points, or 1.4%, to close near 34,737, according to preliminary figures, while the S&amp;P 500 
        SPX,
        -1.90%
       dropped around 86 points, or 1.9%, ending near 4,418. The Nasdaq Composite 
        COMP,
        -2.78%
       shed around 394 points, or 2.8%, to finish near 13,791. The warning on Ukraine lifted oil futures and provided support for traditional safe havens, including gold and Treasurys. The fall left major benchmarks lower on the week, with the Dow suffering a 1% weekly decline, the S&amp;P 500 down 1.8% and the Nasdaq off 2.2%. The Ukraine jitters come as investors were wrangling with concerns about how aggressive the Federal Reserve will be in moving to rein in inflation after data on Thursday showed U.S. consumer prices rose at a hotter-than-expected 7.5% year-over-year pace in January., The stock market shrugged off the Fed and inflation this week. It couldn’t shrug off warnings from the U.S. and U.K. that Russia could soon invade Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 05:04:00 </td>
   <td style="text-align:left;"> Canada Stocks Edge Up, Book Weekly Gain </td>
   <td style="text-align:left;"> The S&amp;P/TSX composite index ended marginally higher at 21,549 on Friday, tracking stronger crude and gold prices, despite concerns over a faster monetary policy tightening and escalating geopolitical tensions. On the corporate front, Magna International reported a 13.7% fall in quarterly revenues and RBC raised the target price for both Constellation Software and Definity Financial. Meanwhile, a state of emergency has been declared in Ontario after the Biden administration urged Prime Minister Justin Trudeau's government to use its federal powers to end a border blockade by truckers opposed to coronavirus mandates. The benchmark index gained 1.3% on the week, its third straight week in positive territory, and remaining close to 2-1/2-month highs levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60290236?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-12 05:01:07 </td>
   <td style="text-align:left;"> Cost of pasta and tinned tomatoes jumps as shop prices rise </td>
   <td style="text-align:left;"> The price of pasta, tinned tomatoes and strawberry jam jumped last year as the cost of supermarket staples rose, new figures for the BBC suggest.                                                                                                                           , Overall, the price of a basket filled with 15 standard food items rose by £1.32, or 8%, in just one year.                                                                                                                                                                   , Changes in the average cost of the food items at Asda, Morrisons, Sainsbury's and Tesco were tracked by retail research firm Assosia.                                                                                                                                       , Some items fell in price, with carrots and mild cheddar seeing small declines.                                                                                                                                                                                              , The same basket of food made up of items from the cheaper "value" ranges at the supermarkets recorded an overall fall in price, down 45p, or 4%. But within that, items such as pasta and vanilla ice cream saw rises of more than 6%.                                      , Other items the firm tracked in the new research for BBC News included tortilla chips, fish fingers, honey, blueberries, carrots and lemons.                                                                                                                                , Although official figures suggest that the overall cost of living increased by 5.4% in the year to December, this number - known as the inflation rate - can mask some steep rises seen at the tills, especially on everyday items.                                         , There are many factors that can make it difficult to track how prices are changing for households, such as promotions at supermarkets or a lack of availability of certain products.                                                                                        , Asda, for example, recently pledged to stock its budget ranges in all of its 581 supermarkets and online after complaints from anti-poverty campaigner Jack Monroe.                                                                                                         , "Looking at food prices is a bit of a minefield", says Kay Staniland, director at Assosia.  Her company selected a snapshot of popular products that were comparable across the value and standard ranges.                                                                  , "I think the figures show that retailers are trying to avoid the biggest increases to value lines as much as possible. But these value lines do make up a small part of total ranges. The standard mid-tier range is where the largest volume of sales come from," she says., Adam Leyland, editor of The Grocer magazine, also tracks a weekly basket of goods and how prices differ across the supermarket aisles.  He says "we're now in a 'once in a generation' moment for food inflation in the UK".                                                , "We've not seen anything like this since the financial crash in 2008. And this is just the start. It's going to go on for two or two and a half years, probably as various costs and problems filter through into the system."                                              , Inflation is everywhere in the food supply chain, he says, from rising energy and labour costs to raw materials and packaging.                                                                                                                                              , The supermarkets are now grappling with how much of these costs to pass on.                                                                                                                                                                                                 , "The food market is incredibly competitive and if you put your prices up ahead of the competition, the shopper will notice.  Right now, more than ever, price is the major focus for the shopper. And they will vote with their feet," he says.                             , Shoppers such as Fernanda Almeida have already been feeling the pinch, though.                                                                                                                                                                                              , She lives with her partner in Worcester and the pair used to purchase ready-meals, or pots of instant porridge, which he could take along to his military barracks where cooking space is limited.                                                                          , But after the shopping bill went up by about £20 a week, they introduced some changes.                                                                                                                                                                                      , "Our shopping has changed completely... we're definitely cooking from scratch a lot more now because it just works out cheaper," Fernanda says.                                                                                                                             , She says she feels "worried". "I've gone from someone who has a budget per month but goes to the shop without a list, picks up things that I fancy eating, to planning each meal, checking items off against the list."                                                     , She's noticed that tinned items in particular have gone up in price and it can often be cheaper to buy individual items for recipes in larger supermarkets, even in comparison with discount stores like Aldi or Lidl.                                                      , Vimbai Gwata-St John in Bexley has seen her food shop go up by about £20 a week, too.                                                                                                                                                                                       , As a mum to an 18-week-old baby with food intolerances she has had to chop and change what they are buying from week to week.                                                                                                                                               , She says she used to follow a budget strictly until she became ill during her pregnancy.                                                                                                                                                                                    , "Because of that, we didn't have time or ability to track our expenses, we just bought what we needed out of desperation because of the other problems at that point in our lives."                                                                                         , Now she is trying to get the budget back on track and is looking at couponing or starting to buy items such as toilet paper or nappies in bulk.                                                                                                                             , Although prices are going up across the board, she says: "The one thing you can't compromise on is food."                                                                                                                                                                   , How supermarkets manage their own inflationary pressures will have consequences for millions of households. And the least well-off, which spend a bigger share of income on essentials such as food and energy, are less able to absorb soaring prices in the aisles.       , The big four supermarket chains have learned from the mistakes they made in 2008, when they put prices up. Aldi and Lidl swooped, stealing customers and market share. Their businesses have since doubled in size and are still opening new stores.                        , "It's a real dog-eat-dog situation," says Adam Leyland.                                                                                                                                                                                                                     , "The battleground is value. And they are determined to stop them (the discounters) making further grounds. For instance, Tesco and Sainsbury's are price-matching Aldi.                                                                                                     , Cost cutting, shrinkflation - reducing the size of a product but not the price - and cutting back on expensive ingredients are just some of the tactics that retailers are using to mitigate the rising cost of groceries. But the trend is clear.                          , Assosia recorded more than 17,000 price increases across the main supermarkets last month, more than double the number in the same month last year, and across every category.                                                                                              , "Inflation is everywhere" says Mr Leyland. And he agrees with the recent warning from John Allan, the chairman of Tesco, that the worst is yet to come.                                                                                                                     , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                                                      , The trial of the most notorious Nazi war criminals                                                                                                                                                                                                                          , Classics Walking in Memphis, A Thousand Miles, Bad Day and more...                                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60261804?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-12 05:00:54 </td>
   <td style="text-align:left;"> The challenges of running a business in Ukraine's second city </td>
   <td style="text-align:left;"> What happens when your country faces invasion, and you just want to get on with running your business?                                                                                                                                                                                                                                                                                                                                                                                           , In Ukraine, there is a distinct sense of déjà vu for people running small and medium-sized businesses over the situation they now find themselves in.                                                                                                                                                                                                                                                                                                                                            , Particularly in Ukraine's second city, Kharkiv, located just 26 miles (46km) from the border. Over 100,000 Russian troops are gathered at several strategic points along the border but Russia denies it is planning an attack.                                                                                                                                                                                                                                                                  , Most Kharkiv entrepreneurs clearly remember the huge task they faced to reinvent themselves after the armed conflict in eastern Ukraine began back in 2014.                                                                                                                                                                                                                                                                                                                                      , "Our clients are very concerned," says Roman Shekin, chief operating officer of the software company Zfort, in Kharkiv.                                                                                                                                                                                                                                                                                                                                                                          , "What we're trying to tell them is, we're ready for any unexpected stuff, because we've been at war for a few years already."                                                                                                                                                                                                                                                                                                                                                                    , In 2014, Russia seized then annexed Crimea, and fighting broke out in the Donbas region of eastern Ukraine, parts of which are now controlled by Russian-backed separatists.                                                                                                                                                                                                                                                                                                                     , Over the space of a few months, businesses in Ukraine lost the vast majority of their customers and suppliers in Russia. Overnight, the conflict cut off old, established cross-border ties. Many companies collapsed and many more had to start again from scratch.                                                                                                                                                                                                                             , For many it feels like their hard work to rebuild is about to be undone.                                                                                                                                                                                                                                                                                                                                                                                                                         , Zfort is one of thousands of Ukrainian IT companies that have flourished since 2014, creating apps and websites for clients in the US and Western Europe. Mr Shekin is trying to reassure his worried clients but some, he says, have put contracts on hold, waiting for more clarity.                                                                                                                                                                                                           , He hopes to put their minds at ease by explaining Zfort's contingency plans. "All our infrastructure is cloud-based and hosted on European server. We can continue operations even if something happens to our offices here… our employees would just move to a safe place and connect remotely."                                                                                                                                                                                                , But for Kharkiv's traditional heavy industry, setting up remotely on a laptop is not an option.                                                                                                                                                                                                                                                                                                                                                                                                  , Right in the centre of the city is the Kharkiv State Aircraft Manufacturer, where the flagship Antonov aircraft, was produced.                                                                                                                                                                                                                                                                                                                                                                   , But no aircraft have been built here for eight years, because 70% of the components needed came from Russia. The firm is now $170m in debt, and has been trying to attract foreign investors to save it from bankruptcy.                                                                                                                                                                                                                                                                         , Managing director, Oleksandr Kryvokon says any interest he has had from Western countries has dried-up. But since this latest ramping up of pressure from Russia at the border, he sees a potential opportunity.                                                                                                                                                                                                                                                                                 , Mr Kryvokon wants Ukrainian companies to collaborate with him on producing aircraft to defend their homeland. "Many factories started thinking, if there's a conflict what are we going to do to help Ukraine?" he says.                                                                                                                                                                                                                                                                         , Across town is the huge market of Barabashovo. Pitching-in to shore up Ukraine's defence is a big theme for entrepreneurs here too.                                                                                                                                                                                                                                                                                                                                                              , It is the biggest market in eastern Europe, with 15,000 shops and 60,000 employees. One of them is Viktor Kuzmenko, who sells heating systems to the building trade.                                                                                                                                                                                                                                                                                                                             , When the conflict with Russia began in 2014, Mr Kuzmenko lost 70% of his business in a few short months - including almost all his loyal customers in Russia.                                                                                                                                                                                                                                                                                                                                    , He just about managed to keep his business going, mostly through online sales.                                                                                                                                                                                                                                                                                                                                                                                                                   , January is usually pretty slow, but this past month he has made a loss. "I depend on people with big money, who are ready to invest in construction, and nobody's going to invest in building in a place where there's even the tiniest threat to it," he says.                                                                                                                                                                                                                                  , Like many of his fellow entrepreneurs, Mr Kuzmenko has dug into his savings to support Ukrainian troops on the frontline. "My country's going through a particularly tense time, I couldn't stand on the sidelines," he says. With the money they raise, they buy tinned food, socks, and soap which are sent to the troops.                                                                                                                                                                     , Mr Kuzmenko and many other business owners are mostly resigned to the threat their country faces and there's a sense of business as usual, according to Peter Dickinson, the publisher of Business Ukraine magazine.                                                                                                                                                                                                                                                                             , "One of the key [Russian] narratives is that Ukraine is a failure - a chaotic, lawless, dysfunctional place - so, obviously damaging the economy is a big part of that [strategy]," he explains.                                                                                                                                                                                                                                                                                                 , The knock-on effect of that is withdrawal of Western investment. "It makes Ukraine toxic," he adds, "because Ukraine becomes high risk all of a sudden."                                                                                                                                                                                                                                                                                                                                         , Orysia Lutsevych, Head of the Ukraine Forum at Chatham House agrees there is a deliberate strategy to undermine Ukraine's modernisation …. "Russia will do everything to have Ukraine be this grey, buffer zone, where Russia will take over while the West will be too risk averse to engage with Ukraine."                                                                                                                                                                                     , Ms Lutsevych, says Ukraine needs external economic support to sustain its economy, and particularly to help small and medium sized business. This could come, she says, from places like the International Monetary Fund, the European Investment Bank, or the European Bank for Reconstruction and Development. She wants to see the creation of "new [financial] instruments to support small and medium businesses because they are taking the highest toll of the suffering, on top of Covid", "Ukrainians have done remarkably well over the last eight years to rebuild the economy from the shocks of 2014, when the war began. This is a blow to them and quite deliberately so," says Mr Dickinson.                                                                                                                                                                                                                                                                                        , Others are hopeful that there will be a period of regeneration eventually, particularly for industries like design and engineering - mirroring the years that followed 2014. "After periods of crisis it's creative and new industries that flourish," says Dr Olga Onuch, associate professor in Politics, University of Manchester.                                                                                                                                                            , But for now, back at Zfort, Roman Shekin is hopeful the situation can be resolved soon. For now, he's telling his clients to hold their nerve.                                                                                                                                                                                                                                                                                                                                                   , He is also looking to the future: "We'll probably set up offices outside Ukraine in countries like Poland or Slovakia. We have to show our clients we can keep their projects safe and secure, no matter what."                                                                                                                                                                                                                                                                                  , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                                                                                                                                                                                                                                                                           , The trial of the most notorious Nazi war criminals                                                                                                                                                                                                                                                                                                                                                                                                                                               , Classics Walking in Memphis, A Thousand Miles, Bad Day and more...                                                                                                                                                                                                                                                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 04:30:04 </td>
   <td style="text-align:left;"> The Dow Jones Index falling 0.98% </td>
   <td style="text-align:left;"> United States Stock Market is dropping 345 points. Leading the losses are Salesforce.com (-4.84%), Boeing (-3.06%) and Nike (-2.95%). Top gainers were Chevron (1.65%), Walgreens Boots Alliance (1.04%) and Merck &amp; Co (0.72%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-12 04:25:05 </td>
   <td style="text-align:left;"> Gold traded above 1865 USD/t.oz </td>
   <td style="text-align:left;"> Gold rose above 1865, according to trading on a contract for difference (CFD). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/11/business/inflation-federal-reserve-economy.html </td>
   <td style="text-align:left;"> 2022-02-12 04:11:30 </td>
   <td style="text-align:left;"> Inflation May Have Peaked. The Fed Needs to Step Gingerly. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Strategies                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Part of the surge in prices stems from the pandemic’s effects and the money poured into the economy to ease that harm.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , By Jeff Sommer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , The headlines have been alarming.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , They are based on a report on Thursday from the Bureau of Labor Statistics that the Consumer Price Index had increased 7.5 percent over the year through January.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , With their own eyes, millions of people are seeing data that is at least as troubling: the soaring price of gasoline, which approached a national average of $3.50 on Thursday, and was more than a dollar higher in California, according to AAA.                                                                                                                                                                                                                                                                                                                                                                                   , On Long Island, I shelled out almost $50 to fill up the family Subaru. That got my attention. The bill reminded me of the gas prices during the oil shocks and inflationary spiral of the 1970s, when I first started to drive.                                                                                                                                                                                                                                                                                                                                                                                                      , Gas prices have always been a notoriously imperfect inflation indicator and that’s especially true today, as automakers shift away from fossil fuels. Even so, they remain perhaps the single greatest influence on American attitudes toward inflation — what economists call inflation expectations.                                                                                                                                                                                                                                                                                                                               , “Many people see gas prices several times a day,” said Yuriy Gorodnichenko, an economist at the University of California, Berkeley. “They are salient. They affect inflation expectations in a big way.”                                                                                                                                                                                                                                                                                                                                                                                                                             , But they are contributing to a sense of panic that, I think, is unwarranted, because inflation may have already peaked, as I will explain.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , When inflation expectations become “unanchored” — when they far exceed the 2 to 3 percent range that the Federal Reserve deems an appropriate inflation target — an economy is often seen to have entered dangerous territory. That may be happening among the general public.                                                                                                                                                                                                                                                                                                                                                       , People who run businesses are especially important because they set prices. They expect inflation to rise 5.6 percent over the next 12 months, a survey posted on Professor Gorodnichenko’s website found. “This is a very difficult problem for policymakers,” he said.                                                                                                                                                                                                                                                                                                                                                             , The Federal Reserve has little choice under these circumstances, given its mandate to keep inflation under control: It must tighten financial conditions, and expectations are high that it will do so at its March 15-16 meeting. Jerome Powell, the Fed chair, said in a news conference last month that the Fed would proceed with “humility,” and respond nimbly to the data before it. Financial markets project that the benchmark Fed funds rate will rise above 1.50 percent by December, from its current near-zero level.                                                                                                  , The Fed has an enormous immediate impact on financial markets: Anticipation of Fed tightening has already unnerved many stock and bond investors, and further bouts of higher volatility can be expected.                                                                                                                                                                                                                                                                                                                                                                                                                            , But the Fed’s ability to constrain inflation over the short term is limited, at best. Nothing it can do is likely to have an immediate effect on the cost of gasoline or the thousands of items whose prices have risen largely because of supply-chain bottlenecks.                                                                                                                                                                                                                                                                                                                                                                 , Alberto Cavallo, a Harvard economist who has studied inflation using vast quantities of high-frequency online price data, told me that he expected the inflationary impact of the pandemic to linger for months.                                                                                                                                                                                                                                                                                                                                                                                                                     , Initially, he said, the C.P.I. understated the pandemic’s inflationary impact when people could not easily find substitutes for products that became scarce or disappeared. Many retailers at first refrained from raising prices out of a sense of fairness and propriety but as the pandemic continued, they did so for those items that they could still obtain and sell.                                                                                                                                                                                                                                                         , As a category, for example, transportation — including cars whose prices have jumped because of shortages of semiconductors and other critical parts — has increased sharply. And, he said, the C.P.I. may now be overstating overall inflation, much as it understated it earlier.                                                                                                                                                                                                                                                                                                                                                  , But, he said, he is finding that even when supply issues ease, retailers still raise prices for several months. Furthermore, thanks in part to fiscal and monetary stimulus, and to recovery from the pandemic, demand is increasing, also leading to higher prices.                                                                                                                                                                                                                                                                                                                                                                 , “We’re not seeing much of a slowdown in inflation yet,” he said. “The Fed definitely has to act.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , No matter how you measure it, the rate of inflation today is much higher than it was before the start of the pandemic. And inflation has been elevated too long for policymakers to be able to continue to describe the problem as “transitory,” as they did last year.                                                                                                                                                                                                                                                                                                                                                              , Words are important. Transitory was the wrong word.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , But if you simply say the effects of the pandemic are continuing and many of them will abate on their own, I think you will be absolutely correct.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Exactly how much of the inflation surge is attributable to the pandemic and will be alleviated without intervention is impossible to say with accuracy. “Forecasting the future of inflation right now is hazardous,” said Michael Weber, an economist at the University of Chicago. “It’s just too complex.”                                                                                                                                                                                                                                                                                                                        , There are reasons to be more optimistic than most of the headlines would suggest, however.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Most basically, if you look at the monthly C.P.I. numbers — as well as those of other inflation measures — you will find that although inflation is high, it is not spiking.                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Mark Zandi, chief economist at Moody’s Analytics, which conducts economic research and risk analysis, put it clearly in a conversation on Wednesday. “Inflation has already peaked,” he said. “It peaked in October.”                                                                                                                                                                                                                                                                                                                                                                                                                , How is this possible?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , A close look at the numbers shows that the annual C.P.I. inflation rate reflects the very low base levels of one year ago, when the pandemic had suppressed demand and prices were low. The month-to-month numbers support a different narrative.                                                                                                                                                                                                                                                                                                                                                                                    , What is inflation? Inflation is a loss of purchasing power over time, meaning your dollar will not go as far tomorrow as it did today. It is typically expressed as the annual change in prices for everyday goods and services such as food, furniture, apparel, transportation and toys.                                                                                                                                                                                                                                                                                                                                           , What causes inflation? It can be the result of rising consumer demand. But inflation can also rise and fall based on developments that have little to do with economic conditions, such as limited oil production and supply chain problems.                                                                                                                                                                                                                                                                                                                                                                                         , Where is inflation headed? Officials say they do not yet see evidence that rapid inflation is turning into a permanent feature of the economic landscape, even as prices rise very quickly. There are plenty of reasons to believe that the inflationary burst will fade, but some concerning signs suggest it may last.                                                                                                                                                                                                                                                                                                             , Is inflation bad? It depends on the circumstances. Fast price increases spell trouble, but moderate price gains can lead to higher wages and job growth.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , How does inflation affect the poor? Inflation can be especially hard to shoulder for poor households because they spend a bigger chunk of their budgets on necessities like food, housing and gas.                                                                                                                                                                                                                                                                                                                                                                                                                                   , Can inflation affect the stock market? Rapid inflation typically spells trouble for stocks. Financial assets in general have historically fared badly during inflation booms, while tangible assets like houses have held their value better.                                                                                                                                                                                                                                                                                                                                                                                        , Consider that monthly C.P.I. rose:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , .09 percent in October.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , 0.7 percent in November.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , 0.6 percent in December.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , 0.6 percent in January.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , It’s true that this has been the worst year for inflation in more than 40 years, but we’ve known that for months. What these numbers show is that although inflation is high, it has also been fairly stable on a month-to-month basis. Mr. Zandi, who says he takes “a sanguine view,” expects that the annual C.P.I. numbers will start to decline in several months, whatever the Fed does. And much as annual corporate earnings look better when compared with low numbers a year earlier, the decline in the annual C.P.I. rate will look even better in comparison with the steep readings of the past year. That’s just math., The Fed does need to raise rates considerably over a few years and reduce its swollen balance sheet, he said, but that can be good news because it means extraordinary measures are no longer needed and it’s time to “normalize.”                                                                                                                                                                                                                                                                                                                                                                                                   , In short, it might be helpful to reframe the C.P.I. news.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Newspapers could quite accurately have run this much duller headline: Inflation Remained Stable, Well Below Its October Peak.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , When inflation becomes deeply worrisome, it is typically because a “wage-price spiral” has set in, with workers responding to price increases with demands for even greater wage increases, and so on.                                                                                                                                                                                                                                                                                                                                                                                                                               , But that hasn’t happened so far.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Yes, after years of rising corporate profits and meager raises, many workers have greater leverage these days, and are demanding more pay. Why shouldn’t they?                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Labor shortages induced by the pandemic appear to have accelerated corporate investment in capital equipment like computers and software that are increasing productivity, Ian Shepherdson, chief economist of Pantheon Macroeconomics, a research firm, said Wednesday in an online talk.                                                                                                                                                                                                                                                                                                                                           , That could produce a happy confluence of events: rising wages, offset by rising productivity, while inflation ebbs, thanks to the Fed and to the easing of pandemic effects.                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Let’s hope so.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , The alternative, a true wage-price spiral fueling runaway inflation, is something the United States hasn’t seen since Paul A. Volcker was Fed chairman from 1979 until 1987. It took brutally high interest rates, soaring unemployment and two recessions to wring high inflation out of the national psyche.                                                                                                                                                                                                                                                                                                                       , In a new paper, Ray Fair, the Yale economist, used his longstanding econometric model to test the effects of Fed rate increases. In a telephone interview, he said his conclusion was this: “If the Fed had to take down, say, 5 percentage points of inflation and try do it all in one year, it would be far more disruptive than most people understand.”                                                                                                                                                                                                                                                                         , That’s all the more reason for the Fed to rein in inflation expectations through clear communications about its intentions, while ever so gently raising interest rates. Mr. Zandi said he believed it was possible to have a soft landing, preserving the economic recovery while the inflation narrative shifts.                                                                                                                                                                                                                                                                                                                   , “Inflation is high but it’s going down.” With a little bit of luck, that mantra can prevail a few months from now.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The alternatives are too bleak to contemplate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , .                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-ends-higher-extending-gains/story.aspx?guid={244E1C7D-7AB1-45C4-B2C2-2FEBF00CC8F5}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-12 03:38:24 </td>
   <td style="text-align:left;"> Oil ends higher, extending gains as Ukraine fears rise - MarketWatch </td>
   <td style="text-align:left;"> Oil futures ended solidly higher Friday, extending gains after White House National Security Adviser Jake Sullivan warned that a Russian invasion of Ukraine could happen "any day now." West Texas Intermediate crude for March delivery rose $3.22, or 3.6%, to close at $93.10 a barrel on the New York Mercantile Exchange., A White House warning that Russia could invade Ukraine “any day now” shook up financial markets Friday. Here's what investors need to know about military action and markets.                                                                                                                                                  , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stocks-extend-slump-ukraine-fears/story.aspx?guid={F2C70C9B-8147-4C9B-800A-5B2C83A0B9E7}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-12 03:26:18 </td>
   <td style="text-align:left;"> Stocks extend slump as Ukraine fears rise; yields edge lower, gold and oil extend gains - MarketWatch </td>
   <td style="text-align:left;"> U.S. stocks extended losses Friday afternoon, while Treasury yields pulled back and gold and oil prices rose as White House National Security Advisor Jake Sullivan warned that Russia was in position to mount an invasion of Ukraine "any day now." He said the U.S. wasn't saying that Russian President Vladimir Putin had made a final decision on Ukraine. The Dow Jones Industrial Average 
        DJIA,
        -1.43%
       was down 287 points, or 0.8%, at 34,945 after falling as low as 34,709. The S&amp;P 500 
        SPX,
        -1.90%
       was down 1.4% at 4,442 and the Nasdaq 
        COMP,
        -2.78%
       dropped 2.2% to 13,879. Traditional haven assets appeared to find some buying interest, with the yield on the 10-year Treasury note falling around 5 basis points to 1.977% --- yields move opposite to price. Gold futures 
        GC00,
        +0.98%
       extended gains. Oil futures also added to gains, with the U.S. benchmark up 3.5% at $93.04 a barrel after trading as high as $94.66., Dutch pension PGGM cut investments in Apple, Intel, and Qualcomm in the fourth quarter, and started a position in Nvidia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/russian-invasion-ukraine-could-begin/story.aspx?guid={14F99D12-E495-4EBC-A218-57765F8F9519}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-12 03:20:17 </td>
   <td style="text-align:left;"> Russian invasion of Ukraine could begin 'any day now,' White House's Sullivan says  - MarketWatch </td>
   <td style="text-align:left;"> A Russian invasion of Ukraine could begin "any day now," White House national-security adviser Jake Sullivan said Friday, telling reporters that Moscow is in position to mount a "major military action." Sullivan said the U.S. isn't saying Putin has made a final decision but still urged Americans in Ukraine to leave the country within 48 hours. Sullivan added a Russian invasion could happen during the Olympics, which are being held in Beijing. Stocks extended an afternoon decline, with the Dow 
        DJIA,
        -1.43%
       falling more than 300 points at its session low. Traditional haven assets saw some buying interest, with Treasury yields pulling back and gold extending gains. Oil futures also extended a Friday rise., Republicans are lining up to oppose further action to relieve borrowers of federal student debt, but they may be powerless to stop forgiveness in the courts.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/pfizer-biontech-delay-seeking-authorization/story.aspx?guid={6358049E-7179-4E65-BBB2-2A0E65577CE4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-12 02:56:37 </td>
   <td style="text-align:left;"> Pfizer, BioNTech to delay seeking authorization of their COVID-19 shot in young children  - MarketWatch </td>
   <td style="text-align:left;"> Pfizer Inc. 
        PFE,
        +0.36%
       and BioNTech SE 
        BNTX,
        +2.04%
       said Friday they are continuing to test their COVID-19 vaccine in children between the ages of 6 months old and 4 years old and will now wait until April when they believe they will have clinical data evaluating three doses to seek emergency authorization in the U.S. This announcement comes less than two weeks after the companies submitted an application for emergency authorization to the Food and Drug Administration for this age group based on data using the first two out of three doses. At that time, Pfizer CEO Albert Bourla said in a news release: "If two doses are authorized, parents will have the opportunity to begin a COVID-19 vaccination series for their children while awaiting potential authorization of a third dose." An FDA advisory committee was then scheduled to meet on Tuesday to discuss whether the benefits of the vaccine outweigh the risks among young children. (The FDA said Friday that the meeting has been postponed.) Over the past year, Pfizer's stock has gained 46.3%, while BioNTech's shares are up 44.0%. The S&amp;P 500 
        SPX,
        -1.90%
       is up 15.2%., Steep losses caused by heavy spending on marketing and ads worry investors, but the growth opportunity is huge. We handicap six of the biggest companies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dennys-offering-free-weddings-its/story.aspx?guid={D89E8C26-3384-4824-8A72-457BC5F02735}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-12 02:55:23 </td>
   <td style="text-align:left;"> Denny's offering free weddings at its Las Vegas chapel on Valentine's Day - MarketWatch </td>
   <td style="text-align:left;"> Diner chain Denny's Corp. 
        DENN,
        -0.30%
       is offering free weddings at its Las Vegas chapel on Valentine's Day. Denny's will also livestream the nuptials for friends and family on its YouTube channel. The package includes the ceremony with an officiant, music and Denny's shirts for the bride and groom; a reception with champagne toast; and vouchers for two Grand Slam meals on the couple's next visit. The Denny's chapel is available all year long as well. Denny's stock has edged down 0.4% over the last year while the S&amp;P 500 index 
        SPX,
        -1.90%
       has gained 13.3%., The Super Bowl is expected to reach a record $1 billion in legal bets, which include widely popular prop bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-12 02:47:00 </td>
   <td style="text-align:left;"> Gold Hits 12-week High </td>
   <td style="text-align:left;"> Gold increased to a 12-week high of 1856 USD/t.oz as metal's safe-haven appeal was boosted by growing geopolitical tensions. White House has warned Russia could invade Ukraine during the Olympics, as more Russian troops were moved towards the border, urging Americans to leave. Also, inflation concerns added to the bullish trend after data showed US inflation rate hit 7.5% in January, the highest in 40 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/svb-leerink-analyst-doesnt-expect/story.aspx?guid={CA624841-BB3F-4132-AA69-08E0275F07E8}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-12 02:35:35 </td>
   <td style="text-align:left;"> SVB Leerink analyst doesn't expect cancer drug developed by Innovent and Lilly to be approved - MarketWatch </td>
   <td style="text-align:left;"> Investors should expect to see fewer Food and Drug Administration approvals of copycat PD-L1 therapies after an advisory committee recommended against approving an experimental cancer drug, according to SVB Leerink analysts. The drug in question, sintilimab, is being developed by Innovent Biologics Inc. 
        1801,
        -2.85%,
       a Chinese drug maker, and Eli Lilly &amp; Co. 
        LLY,
        -1.63%.
       The FDA's Oncologic Drugs Advisory Committee on Thursday voted against approving the drug as a frontline non-small cell lung cancer treatment; the main trial for the drug was conducted in China, and the committee said it wants additional studies assessing the therapy in the U.S. population. More broadly, the vote may be an indicator for how other copycat PD-L1 therapies will be viewed by U.S. regulators, the analysts said. "Were [the trial] a one-off case, we sense that the FDA may be more willing to grant approval, but given its status as a leading example, we believe the FDA will draw a line in the sand to discourage this single-country trial approach," SVB Leerink analyst Daina Graybosch told investors on Friday. She also wrote that she does not expect sintilimab to receive FDA approval. Lilly's stock was down 1.0% in trading on Friday and is up 17.0% over the past year. The S&amp;P 500 
        SPX,
        -1.90%
       has gained 15.2% over the past year. , The Super Bowl is expected to reach a record $1 billion in legal bets, which include widely popular prop bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-02-12 02:32:26 </td>
   <td style="text-align:left;"> Gasoline Hits 7-year High </td>
   <td style="text-align:left;"> Gasoline increased to a 7-year high of 2.7232 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/uruguay/industrial-production </td>
   <td style="text-align:left;"> 2022-02-12 02:08:00 </td>
   <td style="text-align:left;"> Uruguay Industrial Output Grows for 10th Month </td>
   <td style="text-align:left;"> Manufacturing production in Uruguay rose by 11.3 percent year-on-year in December of 2021, following a 21.1 percent surge in the previous month. It was the tenth consecutive month of growth in factory activity but at a slower pace. Considering the full year of 2021, manufacturing output advanced 12.3 percent over a year ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/11/stocks-making-the-biggest-moves-midday-under-armour-zillow-affirm-and-more.html </td>
   <td style="text-align:left;"> 2022-02-12 01:53:27 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Under Armour, Zillow, Affirm and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                               , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                   , Under Armour — The sports equipment company's shares dropped 12.5% as lingering supply chain constraints clouded the firm's outlook and overshadowed its recent performance. The company also warned that heightened freight expenses will weigh on profits in the coming months. The sell-off in the stock came even as the retailer reported fourth-quarter earnings and sales ahead of analysts' estimates., Newell Brands — Shares of the household products maker jumped 11% after the company reported better-than-expected earnings and revenue for its most recent quarter and issued an upbeat earnings forecast. Newell brought in an adjusted 42 cents per share for its latest quarter, beating analysts' estimates by 10 cents.                                                                                  , Affirm — Shares of Affirm plunged 20.6% after Jefferies downgraded the "buy now, pay later" stock. The firm said credit normalization is will lead to increased losses and rising interest rates will pressure margins.                                                                                                                                                                                       , Monolithic Power Systems — The semiconductor company's shares rose 4.1% after Needham upgraded the stock to a buy, saying it sees a more favorable risk/reward profile following a recent decline in share price. Needham's $530 price target on the stock implies about 30% upside.                                                                                                                          , Zillow Group — Shares of the digital real estate platform soared 12.6% after reporting a smaller-than-expected loss for the fourth quarter. Zillow also beat revenue expectations. Those results came despite an $881 million loss on its now-shuttered home-flipping business.                                                                                                                               , Expedia — The travel services company's shares added about 1% before turning lower after quarterly earnings beat analysts' estimates, while revenue for the period missed forecasts slightly. Expedia said it saw a big impact in travel bookings from Covid-related challenges, but they weren't as long or as severe as in previous waves of the pandemic.                                                  , GoDaddy — Web hosting company GoDaddy saw shares jump 8.6% after it reported quarterly earnings and revenue that beat Wall Street forecasts and announced a $3 billion share repurchase program. For the quarter, GoDaddy earned an adjusted 52 cents per share, beating estimates by 11 cents.                                                                                                               , Yelp — The company behind the online review site gained 4.1% after it reported quarterly earnings of 30 cents per share, which more than doubled analysts' expectations of 14 cents per share. Yelp also recorded better-than-expected revenue driven by strength in its advertising business.                                                                                                                , Regeneron — The pharmaceutical company saw its shares rise 3.2% after announcing an eye-injection treatment for patients with wet age-related macular degeneration has completed the second phase of a trial. Regeneron released the results from the trial.                                                                                                                                                  , Energy stocks — Oil and energy stocks gained on Friday as oil prices rose, after the International Energy Agency said oil markets were tight. Coterra Energy, Hess and Phillips 66 rose more than 4%. Occidental rose 5.6% and Halliburton added 3.4%.                                                                                                                                                        ,  — CNBC's Maggie Fitzgerald, Yun Li and Hannah Miao contributed reporting                                                                                                                                                                                                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 01:52:00 </td>
   <td style="text-align:left;"> South African Stocks Close in the Red </td>
   <td style="text-align:left;"> The JSE FTSE all Share index ended 0.3% down at 76,383 on Friday, after setting a record high of 76,690 earlier in the week, as investors mulled how the hotter-than-expected US inflation print will impact Fed's monetary policy. Meanwhile, the local focus was on the state of the nation address on Thursday, at which President Ramaphosa reaffirmed pledges for fundamental reforms including a massive rollout of infrastructure throughout the country and increased industrialization. He also promised to intensify the fight against corruption and indicated as other top priority tackling “unreliable electricity supply” by Eskom. The JSE gained 1.6% in the second week of February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/11/jeffrey-gundlach-says-the-fed-is-obviously-behind-the-curve-will-raise-rates-more-than-expected.html </td>
   <td style="text-align:left;"> 2022-02-12 01:43:10 </td>
   <td style="text-align:left;"> Jeffrey Gundlach says the Fed is 'obviously behind the curve,' will raise rates more than expected </td>
   <td style="text-align:left;"> , DoubleLine Capital CEO Jeffrey Gundlach said Friday the Federal Reserve is failing in its battle against a spike of inflation, and the central bank is likely to accelerate its rate hikes this year.                                                                                                                                                                          , "One thing we can all agree on is inflation just continues to surprise on the upside. The Fed is obviously behind the curve. ... It's going to have to raise rates more than the market still thinks," Gundlach said Friday on CNBC's "Halftime Report." "My suspicion is they are going to keep raising rates until something breaks, which always happens."                  , His comments came as inflation surged to a fresh four-decade high with the consumer price index rising 7.5% year over year. In 2020, the Fed adopted a new monetary policy framework where it seeks to achieve inflation that averages 2% over time and tolerate price rises above that level for a while.                                                                     , Gundlach said he's doubtful that the red-hot inflation will decelerate as much as the central bankers are expecting due in part to extended supply chain challenges.                                                                                                                                                                                                           , "I do expect [inflation] to come down, but I think it's going to be disappointing, the pace and the degree to which it's going to come down," Gundlach said. "We think inflation is very likely to print at least 5% for 2022."                                                                                                                                                , The so-called bond king forecast five interest rate hikes this year, adding there's a 1 in 3 chance the Fed will increase rates by a larger-than-usual 50 basis points in March.                                                                                                                                                                                               , On Thursday after the release of inflation data, St. Louis Fed President James Bullard said he was open to a 50 basis point hike in March, or an increase of 0.5%. He also said he wanted to see a full percentage point of rate rises by July. Still, the presidents of the Atlanta, Richmond, Virginia, and San Francisco Feds pushed back against the idea of a double hike., Gundlach said it's going to be a "tough environment" for risk assets as the Fed embarks on its tightening cycle.                                                                                                                                                                                                                                                               , "Interest rates are going higher. Every risk asset has to reprice based upon these higher interest rates," he said.                                                                                                                                                                                                                                                            , Gundlach sees the 10-year Treasury yield to exceed 2.5% this year. He also said, "It's possible the 10-year takes a peek at 3%."                                                                                                                                                                                                                                               , The benchmark Treasury yield has spiked a great amount in 2022, rising almost 50 basis points from 1.51% at the end of last year. The rate topped 2% for the first time since 2019 on Thursday.Correction: In 2020, the Fed adopted a new monetary policy framework. An earlier version misstated the year.                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 01:41:35 </td>
   <td style="text-align:left;"> Spanish Stocks Fall from 13-Week High </td>
   <td style="text-align:left;"> The IBEX 35 Index closed 0.9% lower at 8,798 on Friday amid increasing concerns of tighter monetary policy by the Federal Reserve in response to surging inflation. On the corporate front, Naturgy led the losses to plunge 11.9% after the utility announced it would split into two separately listed entities. One will focus on the infrastructure of energy distribution, while the other will be in charge of power generation and marketing. The spin-off led to divided opinions from analysts and investors. JPMorgan cut its recommendation on the utility and Credit Suisse left it at "underweight", while Barclays stated the operation is strategically sound. On the other hand, Morgan Stanley said its long-term valuation is not clear, since Naturgy has not yet described the division of funds in between both future entities. At the same time, BBVA fell 1.5% and Bankinter lost 1.2% after BofA downgraded its recommendation on the European banking sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-02-12 01:15:50 </td>
   <td style="text-align:left;"> Brent Crude Climbs to Near $92 </td>
   <td style="text-align:left;"> Brent crude futures climbed more than 1.5% to almost $92 per barrel on Friday, after the International Energy Agency said if the persistent gap between OPEC+ output and its target levels continues, supply tensions will rise, increasing the likelihood of more volatility and upward pressure on prices. Saudi Arabia and the United Arab Emirates were pointed as the OPEC members with spare capacity able to pump more crude. The Paris-based agency also said that demand for oil would rise by 3.2 million barrels a day this year, roughly 100,000 barrels a day less than it said it was expecting last month. Still, the benchmark Brent crude is heading for its first weekly drop after rallying for seven straight weeks as diplomatic efforts raised the chance of reviving the Iran nuclear deal, paving the way for a resumption in official flows from the nation. Analysts suggested that Iran could add as much as 1.5 million barrels a day if an agreement is reached that allows sanctions to be lifted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-12 01:12:00 </td>
   <td style="text-align:left;"> Oil Rises as IEA Sees Tight Market </td>
   <td style="text-align:left;"> WTI crude futures rose more than 1% to around $91.5 per barrel on Friday, after the IEA said if the persistent gap between OPEC+ output and its target levels continues, supply tensions will rise, increasing the likelihood of more volatility and upward pressure on prices. The IEA also pointed out that Saudi Arabia and the United Arab Emirates could pump more oil as they still have spare capacity. The Paris-based agency also said that demand for oil would rise by 3.2 million barrels a day this year, roughly 100,000 barrels less than it said it was expecting last month. Still, the oil is heading for its first weekly drop after rallying for seven straight weeks on market jitters connected with more hawkish Fed monetary policy stance and as diplomatic efforts raised the chance of reviving the Iran nuclear deal, paving the way for resumption in official flows from the nation. Analysts suggested that Iran could add as much as 1.5 million barrels a day if an agreement is reached. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 01:09:00 </td>
   <td style="text-align:left;"> UK Stocks Drop, But Enjoy Best Week This Year </td>
   <td style="text-align:left;"> The FTSE 100 closed 0.2% down at 7,661 on Friday, but remained close to a 2-year high hit in the previous session, amid ongoing concerns over inflationary pressures and a global monetary policy tightening. Meanwhile, Britain's economy shrank by a less-than-expected 0.2% in December and expanded 1% on quarter in the last three months of 2021, suggesting it was not so severely hit by Omicron as previously thought. On the earnings front, British American Tobacco reported a 7% jump in full-year adjusted revenue along with a dividend increase and a share repurchase programme worth 2 billion pounds ($2.71 billion) for 2022. The FTSE 100 gained 1.9% in the second week of February, the biggest weekly gain so far this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 01:04:00 </td>
   <td style="text-align:left;"> European Stocks Maintain Downward Trend </td>
   <td style="text-align:left;"> European equities remained under pressure on Friday, with the regional STOXX 600 index finishing on a negative note amid mounting fears over the current surge of inflation that is likely to prompt central banks to move more quickly to raise rates. Investors are now pricing in a 50-basis-point increase in the ECB's interest rate by December. However, Lagarde cautioned that a hike would not address rising oil prices and disrupted supply chains. Falls were most pronounced in high-growth tech-related stocks, with the prospect of higher interest rates threatening to undermine the valuations of those companies. On the economic data, the latest GDP figures showed Britain's economy saw a minor hit from the Omicron variant, contracting less than expected in December and expanding 1% for the full Q4.  Domestically, the benchmark DAX 30 closed down around 15,400 but recorded an over 2% weekly gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 00:50:00 </td>
   <td style="text-align:left;"> US Stocks Fall for 2nd Session </td>
   <td style="text-align:left;"> Three main US stock market indexes turned sharply lower in the afternoon trade as investors continued to digest the latest batch of earnings and economic data and tried to weigh the Fed response to persistent inflation. The Dow was down more than 400 points, the S&amp;P 500 declined more than 1.5% and the Nasdaq more than 2.5%. St. Louis Fed President Bullard called for two 50 bps hikes by the start of July after the data showed inflation hit 7.5% in January. On the corporate front, Zillow jumped almost 12% after the real estate website operator posted a surprise profit of $1.07 per share while Expedia rose 4% after the company beat earnings expectations and said that bookings were improving. Meanwhile, preliminary data showed the US's University of Michigan consumer sentiment fell sharply for a second straight month to 61.7 in February of 2022, the lowest since October of 2011 and well below market forecasts of 67.5. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Take Losses on Friday </td>
   <td style="text-align:left;"> The FTSE MIB Index fell 0.8% to close at 26,966 on Friday, in line with global equity markets, amid fears of tightening monetary policy by the Federal Reserve. Following the release of higher than expected inflation figures in the US, St. Louis Fed President James Bullard commented he stands dramatically more hawkish, calling for 100bps in interest rate hikes by the Fed’s July meeting. On the corporate front, financial shares were among the biggest underperformers, led by Banca Mediolanum (-3.4%) after the communication of its quarterly results. On the other hand, Banco BPM shares jumped 9.8%, after being halted from trading during in the first half of the session amid renewed speculation that UniCredit (-1%) would launch a takeover bid on the bank. While no formal bids were made, since conditions for a merger in line with UniCredit’s CEO Andrea Orcel could not be met, investors speculate the bank could evaluate further strategies and make a bid over the weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-12 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Extend Losses </td>
   <td style="text-align:left;"> The CAC 40 Index closed 1.4% lower at 7,012 on Friday, extending yesterday’s 0.4% loss, as investors digested a batch of corporate earnings while still weighing on higher than expected inflation figures from the US and the entailed projections of accelerated policy tightening by the Federal Reserve. Prospects of higher borrowing costs pressured the luxury goods sector the most, as LVMH (-2.7%), Hermes (-3.5%), and Kering (-1.4%) traded in the red. At the same time, BNP Paribas (-2.5%) and Societe Generale (-2.2%) shares both dropped after Bank of America Global Research downgraded the European banking sector. Meanwhile, EDF fell 2.4% after further corrosion and safety issues in their nuclear reactors led the utility to decrease its nuclear production estimate for 2023 to 300-330 terawatt hours from 340-370. Despite the session’s loss, the CAC 40 ended the week 0.9% higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/currency </td>
   <td style="text-align:left;"> 2022-02-12 00:43:00 </td>
   <td style="text-align:left;"> South African Rand Remains Strong </td>
   <td style="text-align:left;"> The South African rand was trading around 15.1 against USD, its highest since January 21st, after President Cyril Ramaphosa delivered its pro-business State of the Nation Address. The President announced plans for green energy projects worth USD 17.8 billion over the next decade, including the industrialization of the production of cannabis, with strong potential to create 130,000 jobs. Ramaphosa also said that a social grant put in place to cushion the impact of the COVID-19 pandemic will be extended for a year and promised new intensity for the fight against corruption. Tackling “unreliable electricity supply” by Eskom was also listed as a top priority. Meanwhile, the IMF said South Africa faces lacklustre growth in the medium-term, despite a faster-than-anticipated recovery from the Covid-19 pandemic due to unsolved structural issues, including deteriorating state-owned enterprises and inconsistent electricity supply. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/tajikistan/interest-rate </td>
   <td style="text-align:left;"> 2022-02-12 00:41:00 </td>
   <td style="text-align:left;"> Tajikistan Holds Key Policy Rate at 13.25% </td>
   <td style="text-align:left;"> The National Bank of Tajikistan kept its benchmark interest rate unchanged at 13.25% during an unscheduled meeting on February 11th 2022, aiming to support the domestic recovery from the Covid-19 crisis as inflationary pressure eased. The country's annual inflation rate stood at an over one-year low of 8% in December of 2021, within the central bank's target range of 4-8%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kyrgyzstan/monthly-gdp-yoy </td>
   <td style="text-align:left;"> 2022-02-12 00:19:18 </td>
   <td style="text-align:left;"> Kyrgyzstan’s GDP Expands 1% YoY in January </td>
   <td style="text-align:left;"> Kyrgyzstan's economy advanced by 1 percent year-on-year in January of 2022, recovering from a 7.8 percent pandemic-induced contraction a year ago. The expansion was supported mainly by service sector (+4 percent), particularly wholesale and retail trade, car and motorcycle repair activities (+7.6 percent); and transportation and storage (+3.5 percent). Meanwhile, economic activity remained subdued within goods-producing industries (-3 percent vs -10 in January 2020), amid poor performances in manufacturing (-5.4 percent); mining (-6.6 percent); agriculture (-4 percent); electricity, gas, steam and air conditional supply (-16.6 percent); and water supply (-4.3 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-02-12 00:11:19 </td>
   <td style="text-align:left;"> UK Gas is up by 5.09% </td>
   <td style="text-align:left;"> Natural Gas UK GBP increased 5.09% to 187.22 GBp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/itub:us </td>
   <td style="text-align:left;"> 2022-02-12 00:09:43 </td>
   <td style="text-align:left;"> Itau Unibanco earnings meet market expectations at 0.12 USD </td>
   <td style="text-align:left;"> Itau Unibanco (ITUB) released earnings per share at 0.12 USD, in line with market expectations. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-14 09:42:49 UTC +8

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
   <td style="text-align:left;"> 2022-02-14 09:42:24 </td>
   <td style="text-align:left;"> Natty moving $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:42:22 </td>
   <td style="text-align:left;"> $SPY if Bengals win, market is red for the month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:42:12 </td>
   <td style="text-align:left;"> $SPY &amp;#39;s next move may depend on Dr. Trump&amp;#39;s intervention with his old buddy Putin. Imagine! 
 
If Donny had any sense, he could create a positive outcome on a global scale by whispering to Putinmeister. The only problem with that idea is that there is little for Trumpy to gain as the Scales of Justice begin to toss more weights around his tanned neck.  The weight for Donny, Donny Jr. and Ivanka are increasing but who cares?  No one. 
 
Trillions moving lately and there was a massive amount of $$$ funneled into equities in the last week.  Insane $latex7a5a4675b7cd0a965356c031a53b0614SPY Key Levels: 
- Key Level of 440 (200ema) 
- If key level can hold support next resistance targets are 445, 450 then 455 areas 
- If key level cannot hold support our next bounce zones are 434, 427, 420. 
- First i&amp;#39;ll be watching the 440 at the 200ema to hold support for a potential bounce back up to retest highs 
- Second i&amp;#39;m watching the 420 level as that can be a retest of support for a potential reversal. 
 
https://fourhorsementrading.substack.com/p/fht-weekly-watch-list-9bd 
^^^ 
Subscribe to the FHT Newsletter to receive the entire FHT Weekly Watch-List charting, catalysts and news included! 
 
For the active trader join the FHT Discord for alerts and live action trading (Link in Bio). 
 
$SPY Chart: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:41:39 </td>
   <td style="text-align:left;"> $SPY all these black people these days think they can take over our country.  Let&amp;#39;s Go Brandon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:41:36 </td>
   <td style="text-align:left;"> Lots of big earnings reports coming again this week. Earnings season isn&amp;#39;t over yet. $ABNB $NVDA $POOL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:41:08 </td>
   <td style="text-align:left;"> $SPY $QQQ halftime was garbage. Joe shiesty in control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:36 </td>
   <td style="text-align:left;"> $QQQ $SPY $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:35 </td>
   <td style="text-align:left;"> $SPY Rams or Bengals which one us the strong team..? I mean expectations on which team the most?? Are they performing according to the expectations? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:33 </td>
   <td style="text-align:left;"> $SPY remember tomorows red or green doest matter... eod when fed minutes come out and if its not 0.5% rate increase immediately * which is extremely unlikely) , tuesday is going to be major rjp green $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:25 </td>
   <td style="text-align:left;"> $SPY $QQQ The Rams should still be able to survive without OBJ since they still have the best receiver in the league in Kupp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:16 </td>
   <td style="text-align:left;"> $SPY That Donald dirty as fuk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:14 </td>
   <td style="text-align:left;"> $SPY bears gotta chill bro </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:07 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:07 </td>
   <td style="text-align:left;"> $SPY Bengals are crushing it. Rams are a gone case. One side show. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:07 </td>
   <td style="text-align:left;"> $SPY This is the type of shit OBJ is gonna tell his son about for years until he grows up and has to redeem his family name. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:04 </td>
   <td style="text-align:left;"> $SPY futures dripping ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:40:02 </td>
   <td style="text-align:left;"> $SPY OBJ got drake his half mil and dipped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:39:48 </td>
   <td style="text-align:left;"> $SPY wow Fute is so green . Let’s Enjoy this moment now Bc you will never see this anymore start from tmr morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:39:45 </td>
   <td style="text-align:left;"> $SPY I fell asleep did the commercials passed already? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:39:40 </td>
   <td style="text-align:left;"> $SPY what tomorrow&amp;#39;s bullish action will feel like to the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:39:34 </td>
   <td style="text-align:left;"> $SPY Donald.. watch out for those lineman.. they will eat you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:39:28 </td>
   <td style="text-align:left;"> ETF Sentiment Weekly Recap: $SPY is the #1 ETF that institutions traded this week with 3.7M options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:39:26 </td>
   <td style="text-align:left;"> $SPY futes ripping how? lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:39:06 </td>
   <td style="text-align:left;"> $SPY Bengals are gonna win on this black swan event </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:57 </td>
   <td style="text-align:left;"> $SPY 95% of the bears here do not even know were Ukraine is on the map 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:44 </td>
   <td style="text-align:left;"> $SPY WHO DEY?!🐅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:41 </td>
   <td style="text-align:left;"> $SPY Futes very weak. Big drop soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:39 </td>
   <td style="text-align:left;"> $SPY who is your pick for MVP? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:37 </td>
   <td style="text-align:left;"> $SPY asia deep red, but we green... fck...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:32 </td>
   <td style="text-align:left;"> $SPY don’t get swindled tomorrow morning buying in morning because of FOMO and then we close red… $aapl $googl $tsla $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:28 </td>
   <td style="text-align:left;"> $SPY $QQQ all of us posting about the super bowl on stocktwits are the single people 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:17 </td>
   <td style="text-align:left;"> $SPY Fuuuuuuck OBJ come back Drake gonna check the weather and find out its oppy outside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:16 </td>
   <td style="text-align:left;"> $SPY no OBJ gonna hurt the Rams. Burrow taking this home. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:06 </td>
   <td style="text-align:left;"> $SPY yup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:38:01 </td>
   <td style="text-align:left;"> $SPY BRO! Stafford choke on full display TN. Send him back to Detroit! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:59 </td>
   <td style="text-align:left;"> $SPY BLACK SWAN 🏈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:48 </td>
   <td style="text-align:left;"> $SPY UVXY gonna payyyyyy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:38 </td>
   <td style="text-align:left;"> $SOFI Bengals baby $SPY $DKNG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:27 </td>
   <td style="text-align:left;"> $SPY bengals bengals bengals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:21 </td>
   <td style="text-align:left;"> $SPY interception. Bears in control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:16 </td>
   <td style="text-align:left;"> $SPY bengals win = SPY 400 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM His balls are sweaty, knees weak, calls are heavy
There&amp;#39;s diarrhea on his sweater already, mom&amp;#39;s beefaroni
He&amp;#39;s nervous, but on the surface he looks balmy and shitty
To drop worthless calls, but he keeps on forgettin&amp;#39;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:14 </td>
   <td style="text-align:left;"> $SPY 

You are watching the Super Bowl.

I am watching the Super Bowl.

We are not the same. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:12 </td>
   <td style="text-align:left;"> $SPY rams will blame the loss on that face mask </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:07 </td>
   <td style="text-align:left;"> $SPY 2 tos by stafford 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:05 </td>
   <td style="text-align:left;"> $SPY 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:37:00 </td>
   <td style="text-align:left;"> $SPY futes showing momentum downward right now while BTC just cracked under 42k lets gooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:59 </td>
   <td style="text-align:left;"> $SPY money in the bank market is for the bulls  aka underdog </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:55 </td>
   <td style="text-align:left;"> $SPY 🔥 if futes end up green we will have an early morning well-off as prescribed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:53 </td>
   <td style="text-align:left;"> $BTC.X whales unloading lol. This pump is over $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:51 </td>
   <td style="text-align:left;"> $SPY fuck I’m so fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:34 </td>
   <td style="text-align:left;"> $SPY annnnd Bengals gonna run away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:31 </td>
   <td style="text-align:left;"> Oil keeps flying high-- Futures reversing, Crypto falling and Bonds are green on possible Catalysts that Ukraine might abandon NATO or moving on the news that Russia has now 130K soldiers at border $SPY $QQQ $XLE $BTC.X $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:31 </td>
   <td style="text-align:left;"> What a turn of events $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:28 </td>
   <td style="text-align:left;"> $SPY $SOFI Market crashes if Bengals win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:21 </td>
   <td style="text-align:left;"> $SPY I hope it opens green. More upside on puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:20 </td>
   <td style="text-align:left;"> $SPY wtf was that shit I love corruption refs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:19 </td>
   <td style="text-align:left;"> $SPY LMAOOOO SCREW LA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:18 </td>
   <td style="text-align:left;"> Wow Bengals $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:36:16 </td>
   <td style="text-align:left;"> $SPY Bengals literally score and futes go down, is this a coincidence? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:35:59 </td>
   <td style="text-align:left;"> $SPY Huge Facemask, market tanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:35:56 </td>
   <td style="text-align:left;"> $SPY Bidens old ass and commander Kameltoe is Bullish in a modern warfare scenario?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:35:56 </td>
   <td style="text-align:left;"> $SPY neither bearish or bullish rn. Flat as can be. Enjoy super bowl Sunday everyone and we will evaluate tmmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:35:51 </td>
   <td style="text-align:left;"> $SPY DOES ANYBODY KNOW 
 
ARE WE BULL FLAGGING OR BEAR FLAGGING 
 
PLEASE MAKE UP YOUR MIND </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:35:49 </td>
   <td style="text-align:left;"> $SPY WHAT DID I TELL YOU THIS IS THE QUARTERBACK FOR PUTS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:35:38 </td>
   <td style="text-align:left;"> $SPY if the Cowboys were playing, that would’ve been a flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:35:26 </td>
   <td style="text-align:left;"> $SPY slick move by higgins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:35:13 </td>
   <td style="text-align:left;"> $SPY 
Weak market - Tuesday PPI numbers coming out !! Nothing to be bullish about </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:35:08 </td>
   <td style="text-align:left;"> $SPY FUCK DA RAMS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:34:47 </td>
   <td style="text-align:left;"> $SPY hate to say it but it’s an outright short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:34:38 </td>
   <td style="text-align:left;"> $SPY Bengals for a bearish market. Lets go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:34:35 </td>
   <td style="text-align:left;"> $SPY 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:34:29 </td>
   <td style="text-align:left;"> $SPY if we count for inflation then we say this should be at like 750 by now so lots of room for sure 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:34:18 </td>
   <td style="text-align:left;"> $SPY just like that. All it took was 2 hours for the bulls to shut up, thank god. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:34:13 </td>
   <td style="text-align:left;"> $SPY Goodnight rams </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:34:04 </td>
   <td style="text-align:left;"> $SPY LIKELY NOT NOOOOOOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:33:54 </td>
   <td style="text-align:left;"> $SPY lets go bengals! Joey B! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:33:52 </td>
   <td style="text-align:left;"> $SPY 🔥🔥🔥🔥🔥75ytd. Fuck yeah!!!!  FIRE BOYS!!!  Damnnnnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:33:40 </td>
   <td style="text-align:left;"> $SPY 

LOL… holy crap, Cincinnati! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:33:40 </td>
   <td style="text-align:left;"> $BTC.X what the hell are you people doing $SPY what a joke of an asset ——————- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:33:35 </td>
   <td style="text-align:left;"> $SPY futes remain flat as Fck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:33:34 </td>
   <td style="text-align:left;"> $SPY Bring back the good ol American super bowl commercials with beer and hot women. Wtf is all this bs? Bearish on political correctness and being “ woke” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:33:29 </td>
   <td style="text-align:left;"> $SPY murder was the case </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:33:13 </td>
   <td style="text-align:left;"> $SPY Go pull up the 5 day on btc, then tell me again how it correlates to the spy.  😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:33:00 </td>
   <td style="text-align:left;"> Although the technical rating is bad, $SPY does present a nice setup opportunity. https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:53 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s amazing Dre and Snoop still performing together. They really are OG&amp;#39;s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:52 </td>
   <td style="text-align:left;"> $SPY Matthew Stafford gonna have to earn it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:48 </td>
   <td style="text-align:left;"> $SPY guys I think odell tore his acl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:41 </td>
   <td style="text-align:left;"> $SPY 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:34 </td>
   <td style="text-align:left;"> $SPY Amanda and Hannah chose wrong. They make little money. One has a refrigerator technician fat boyfriend and one dates small time sugar daddies with little money. One is stuck working retail and swamped with student loan debt and the other has a crap bartender job. I grind hard and got promoted multiple times in a year. Be excellent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:30 </td>
   <td style="text-align:left;"> $SPY Well that was a 💩 show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:26 </td>
   <td style="text-align:left;"> $SPY  went short 10 contracts NQ on that beta boy low T halftime show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:23 </td>
   <td style="text-align:left;"> $SPY More than enough time for OBJ to come back? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:22 </td>
   <td style="text-align:left;"> $SPY futures looking lame. might turn red during open ngl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:21 </td>
   <td style="text-align:left;"> $SPY futures look weak. Even if we go up some tommarow likely selloff before the eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:18 </td>
   <td style="text-align:left;"> $SPY meanwhile ukraine is getting fucked in the ass while the u.s celebrates the half time show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:16 </td>
   <td style="text-align:left;"> $SPY SPY 2022-02-13 Options Analysis Video: 
https://www.youtube.com/watch?v=MamPqMZvgCo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:12 </td>
   <td style="text-align:left;"> $SPY Puts margin calls incoming in 3... 2... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:07 </td>
   <td style="text-align:left;"> $SPY darling nikkei </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:32:04 </td>
   <td style="text-align:left;"> $AFRM so is there a fed meeting tomorrow that can tank/surge the overall market? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:31:58 </td>
   <td style="text-align:left;"> $SPY the pain is yet to come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:31:30 </td>
   <td style="text-align:left;"> $SPY 🤦🏻‍♂️ halftime </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:31:18 </td>
   <td style="text-align:left;"> $SPY you know money is in low supply look at that half time show. The budget might be under $1 million lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:31:18 </td>
   <td style="text-align:left;"> $SPY it can’t keep it up 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:31:17 </td>
   <td style="text-align:left;"> $SPY $QQQ If you are hoping to make money on your shorts/puts on rate hikes then I don’t really have a problem with it, I have a problem with the bears hoping for WW3 though and so they can make some money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:31:14 </td>
   <td style="text-align:left;"> $SPY Yo... w/e happens with your finance tomo - appreciate the fact you witnessed OG Em, Dre, and Snoop perform fire in 2022. Man, I grew up listening to them with my boys (and Backstreet boys at home thinking about my crush). 🔥🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:31:14 </td>
   <td style="text-align:left;"> $SPY sucks for OBJ.  Hope wasn&amp;#39;t another tear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:55 </td>
   <td style="text-align:left;"> $SPY green today and whole week. All bears lose their saving and die </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:48 </td>
   <td style="text-align:left;"> $SPY Can&amp;#39;t decide.  I mean, that was better than Kenny Chesney or whatever they had last time idk.  But it just wasn&amp;#39;t the right venue.  Gotta remember plenty of other acts have been lewd and crass and not the classiest through the years and people over 40 w a brain are supposed to start turning on popular culture if not completely eschewing it.   i&amp;#39;m not supposed to like what&amp;#39;s going on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:48 </td>
   <td style="text-align:left;"> $SPY no war yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:44 </td>
   <td style="text-align:left;"> $SPY garbage half time. glorified hood rats. Two turn tables and microphone. Where it’s at.  Natcisists. The decay of American society. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:43 </td>
   <td style="text-align:left;"> $SPY Clown Putin with his billion dollar palace only cares about one thing: $$$. Can’t wait for that corrupt POS and his palace to be reduced to rubble.
Karma’s a bitch as he shall soon learn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:33 </td>
   <td style="text-align:left;"> $SPY the only thing that kills the market is uncertainty!! Remember that!! Uncertainty !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:30 </td>
   <td style="text-align:left;"> $SPY the uncultured here tonight 

“Worst half time ever. Maroon five was the best. The good ol days” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:28 </td>
   <td style="text-align:left;"> $SPY I wonder… is the US Intelligence community trying so hard to convince the world that Putin is going to invade Ukraine to spur a rally in the price of oil so that American producers can recover from 2020… this whole Ukraine thing is starting to feel a little like a sham. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:24 </td>
   <td style="text-align:left;"> $SPY 50 cent looked like 85 cent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:24 </td>
   <td style="text-align:left;"> $SPY they be fucken up the fresh prince. Comedy not no damn drama!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:30:10 </td>
   <td style="text-align:left;"> $SPY RUSSIA’S 1ST GUARDS TANK ARMY IS MOVING CLOSE TO UKRAINE BORDER, 130,000 RUSSIAN TROOPS NOW AT UKRAINE BORDER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:59 </td>
   <td style="text-align:left;"> $SPY I want Adam Sandler headlining next year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:59 </td>
   <td style="text-align:left;"> $SPY 

Who else was crip walking in their living room at half time??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:58 </td>
   <td style="text-align:left;"> $SPY Crude up, futures flat, crypto down, 10 yr treasury up..... big red by open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:48 </td>
   <td style="text-align:left;"> $SPY 50 cent is now 75 cent due to inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:47 </td>
   <td style="text-align:left;"> $SPY the amount of classic albums Dre and Snoop were apart of is just insane. Eminem is just one of those dudes who had an insane flow and a crazy-in-a-good-way charisma. Had all the right influences, too. Kendrick is one of the few woke rappers who holds credibility across the underground and pop culture

Are Eminem and Snoop still beefing or nah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:42 </td>
   <td style="text-align:left;"> $spy $dia $QQQ puts on that halftime show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:31 </td>
   <td style="text-align:left;"> $SPY how futes lookin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:31 </td>
   <td style="text-align:left;"> $QQQ $SPY just since 1989 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:24 </td>
   <td style="text-align:left;"> $SPY Bearish af on this Fresh Prince remake 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:22 </td>
   <td style="text-align:left;"> $SPY promoting drugs, violence, and self glorification in front of all of America in the name of “social justice” lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:20 </td>
   <td style="text-align:left;"> $SPY Dark Pool inflow at ATH, wonder who’s accumulating while you retailers dump and panic 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:19 </td>
   <td style="text-align:left;"> $SPY $QQQ  when you bought a bunch of puts for ww3 but only war happening is between you and your margin calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:13 </td>
   <td style="text-align:left;"> $SPY so many of u mad because of the showtime. Talking about our country is fucked… you mean it ain’t as white anymore. Y’all are so ignorant now. It’s disgusting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:11 </td>
   <td style="text-align:left;"> $SPY  awesome half time show 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:08 </td>
   <td style="text-align:left;"> $SPY for the  military generals here on stock twits wen invasion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:06 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:05 </td>
   <td style="text-align:left;"> $SPY wtf is bel air </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:03 </td>
   <td style="text-align:left;"> $SPY Looks like inflation hit 50 Cent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:29:01 </td>
   <td style="text-align:left;"> $SPY pretty cool half time show, took me back to my high school days doggystyle was big, was mainly into nirvana soundgarden radiohead, and metal but was still pretty cool. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:58 </td>
   <td style="text-align:left;"> $SPY ho forgot to invite cube?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:58 </td>
   <td style="text-align:left;"> $SPY 🎶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:53 </td>
   <td style="text-align:left;"> $SPY wait til board meeting… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:50 </td>
   <td style="text-align:left;"> $SPY crypto is down and china is down 2%.. oil is up 1% but the US future are ripping? Haha they are just getting the run outta the way cuz it’s down hill at open.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:48 </td>
   <td style="text-align:left;"> $SPY $QQQ The Super Bowl = the best show on the planet, nothing can compare with the Super Bowl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:44 </td>
   <td style="text-align:left;"> $SPY you know how I know you have no friends? You post on spy board your thoughts about the Super Bowl halftime show. Yeeeesh some of y’all need some real companionship </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:41 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:28 </td>
   <td style="text-align:left;"> $SPY RUSSIA’S 1ST GUARDS TANK ARMY IS MOVING CLOSE TO UKRAINE BORDER, 130,000 RUSSIAN TROOPS NOW AT UKRAINE BORDER.  They ain&amp;#39;t fooling around.  Wonder if it happens during the Super Bowl or while everyone is hungover in the morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:28 </td>
   <td style="text-align:left;"> $SPY we gon be alrighttt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:24 </td>
   <td style="text-align:left;"> $SPY Great show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:23 </td>
   <td style="text-align:left;"> $SPY wen invasions 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:22 </td>
   <td style="text-align:left;"> $SPY dog water half time show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:20 </td>
   <td style="text-align:left;"> $SPY why are we green? What changed since friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:20 </td>
   <td style="text-align:left;"> $SPY If Chris Brown didnt beat the shit out of Rihanna he&amp;#39;d be up there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:18 </td>
   <td style="text-align:left;"> $SPY def best halftime show in quite some time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:17 </td>
   <td style="text-align:left;"> $SPY $QQQ is it me or 50 looking like a Dolla coin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:16 </td>
   <td style="text-align:left;"> $SPY member gaga, modina a d Coldplay and U2.... Yea that was better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:15 </td>
   <td style="text-align:left;"> $SOFI I’m going all in after that Halftime Show. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:06 </td>
   <td style="text-align:left;"> $SPY no boob this year...ah well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:02 </td>
   <td style="text-align:left;"> $SPY 🔥🔥🔥🔥🔥🔥 Bro - Em, Dre, Snoop, and Kendrick were fire... wish it was a lot longer.

P.s. I threw up watching Mary J Blige. Glad that cellulite went first. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:28:01 </td>
   <td style="text-align:left;"> $SPY still looks weak as.s fuck.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:56 </td>
   <td style="text-align:left;"> $SPY $QQQ Best halftime show in years.  Not as good as Prince though that’s still the best.  They should have done the explicit version of “Nuthin but a G Thang” though.  😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:54 </td>
   <td style="text-align:left;"> $SPY nice how there’s not a ton of some BS this year. No commercials about how you’ll die without big pharma etc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:53 </td>
   <td style="text-align:left;"> $SPY this country is turning ghetto... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:52 </td>
   <td style="text-align:left;"> $SPY Halftime show was 🔥🔥🔥 haven’t c-walked in many years but was giving it a shot 👌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:52 </td>
   <td style="text-align:left;"> $SPY ok shows over. Back to invading Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:49 </td>
   <td style="text-align:left;"> $SPY Shoulda had Wu Tang, ODB would have stole the show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:46 </td>
   <td style="text-align:left;"> $SPY  Best half time time show was last year with The Weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:43 </td>
   <td style="text-align:left;"> $SPY circuit breaker at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:34 </td>
   <td style="text-align:left;"> $SPY half time show budget need to be increased lol. Very weak show 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:30 </td>
   <td style="text-align:left;"> $SPY 

Atleast halftime show wasnt woke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:24 </td>
   <td style="text-align:left;"> $SPY Back to stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:19 </td>
   <td style="text-align:left;"> $SPY Not as good as Janet Jackson super bowl halftime show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:18 </td>
   <td style="text-align:left;"> $SPY i have a plan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:15 </td>
   <td style="text-align:left;"> $SPY No lame ass lip syncing. That’s how you do a halftime show. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:14 </td>
   <td style="text-align:left;"> $SPY That was literally the symbolic end of the country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:13 </td>
   <td style="text-align:left;"> $SPY im probably the only dipshit on the planet not watching Superbowl right now 🤣😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:13 </td>
   <td style="text-align:left;"> $SPY 50 cent seemed like he had a hard time performing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:13 </td>
   <td style="text-align:left;"> $SPY damn Jim is really struggling for that next paycheck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:13 </td>
   <td style="text-align:left;"> $SPY  the gang is all here 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:08 </td>
   <td style="text-align:left;"> $SPY I wanted Nickleback at Halftime. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:02 </td>
   <td style="text-align:left;"> $SPY  That half time show sucked.. It’s  like they were trying to hard.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:27:00 </td>
   <td style="text-align:left;"> $SPY j lo still hottest woman alive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:59 </td>
   <td style="text-align:left;"> $SPY It’s almost as if they weren’t actual people but primitive vessels for demonic entities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:59 </td>
   <td style="text-align:left;"> $SPY why you clown bulls saying futes ripping lmao. Futes aren&amp;#39;t doing a damn thing still down 1.7% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:58 </td>
   <td style="text-align:left;"> $SPY go long now and you’ll be living on pork and beans for the rest of your life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:57 </td>
   <td style="text-align:left;"> $SPY This all music we grew up with in the 90&amp;#39;s. These kids dont even know these rappers lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:56 </td>
   <td style="text-align:left;"> $SPY j lo that’s a show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:55 </td>
   <td style="text-align:left;"> $SPY Damn J Lo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:53 </td>
   <td style="text-align:left;"> $SPY good showing .... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:48 </td>
   <td style="text-align:left;"> $SPY nice half time 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:48 </td>
   <td style="text-align:left;"> $SPY halftime show better than the commercials </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:46 </td>
   <td style="text-align:left;"> $SPY Bring OBJ back he needs to make me and drake money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:46 </td>
   <td style="text-align:left;"> $SPY shout out to my 90s babies lfg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:43 </td>
   <td style="text-align:left;"> $SPY bulls wanted nickelback at halftime </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:39 </td>
   <td style="text-align:left;"> $SPY omg that was amazing 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:37 </td>
   <td style="text-align:left;"> $SPY Trading bots right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:35 </td>
   <td style="text-align:left;"> $SPY 

Dre got me fucked up rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:35 </td>
   <td style="text-align:left;"> $SPY “This half time show sucks!”… congrats, you’re a certified boomer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:30 </td>
   <td style="text-align:left;"> $SPY Futes flat as  a pita bread. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:27 </td>
   <td style="text-align:left;"> $SPY half time was ok, nothing impressive .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:17 </td>
   <td style="text-align:left;"> $SPY Best halftime in at least 10 years. Minus Kendrick Lamar no talent compared to Snoop and Dre. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:17 </td>
   <td style="text-align:left;"> $SPY J J J JEEEEYUHHHH

okay wow yeah great is this still a football game or am I watching BET.  

convict dressed dancers crip walking for the kiddos.  

mixed feelings.  that would have been cooler if snoop would have yelled &amp;#39;biotch&amp;#39; at the beginning or end.  also that&amp;#39;s just never really gonna be family entertainment w the asses hanging out and twerking going on idk.  stay classy america. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:02 </td>
   <td style="text-align:left;"> $SPY That’s how you do a Half Time show.  Roll out the OG’s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:26:01 </td>
   <td style="text-align:left;"> $SPY I can tell who AINT from the WESTCOAST by the comments 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:57 </td>
   <td style="text-align:left;"> $SPY I give the haft time show a B- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:53 </td>
   <td style="text-align:left;"> $SPY it was not a garbage show but one of the lowest energy show I have ever watched. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:53 </td>
   <td style="text-align:left;"> $SPY That was a weak half time show. Snoop took the show, unlike Em who lip synced. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:44 </td>
   <td style="text-align:left;"> $SPY The worst SB half time ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:41 </td>
   <td style="text-align:left;"> $SPY Lebron commercial more entertaining than half-time show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:37 </td>
   <td style="text-align:left;"> $SPY Lmaoo Jim Carey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:33 </td>
   <td style="text-align:left;"> $SPY damn that shit was fire 🔥 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:29 </td>
   <td style="text-align:left;"> $SPY bulls are celebrating for +.11%? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:26 </td>
   <td style="text-align:left;"> $SHIB.X LA baby! Let’s fucking go!!!🚀🚀 $BTC.X $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:25 </td>
   <td style="text-align:left;"> $SPY now we been youngboy next year.🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:18 </td>
   <td style="text-align:left;"> $SPY $QQQ This halftime show is the best ever in the Super Bowl. Now the Rams should have enough time to come up with a game plan for the second half without OBJ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:16 </td>
   <td style="text-align:left;"> $SPY did you guys like the Pepsi half time show?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:15 </td>
   <td style="text-align:left;"> $SPY tame show for the conservative nfl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:10 </td>
   <td style="text-align:left;"> $SPY so basically cut off half the stadium? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:09 </td>
   <td style="text-align:left;"> $SPY too short half time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:08 </td>
   <td style="text-align:left;"> Market Volume Barometer 2-11-2022 
Sentiment: LIMBO 
Volume: 0% 
Real Feel: SWELTERING 
Cycle: BEARISH I 
Portfolio: LONG 
Next Day Move: SIDEWAYS DOWN 
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/ 
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:05 </td>
   <td style="text-align:left;"> $SPY weak sauce half time, expected much more from that line up. Futes tank on bad half time show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:25:04 </td>
   <td style="text-align:left;"> $SPY Worst Half Time Super Bowl Ever! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:59 </td>
   <td style="text-align:left;"> $SPY that was great except for Orpah in the white costume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:56 </td>
   <td style="text-align:left;"> $SPY In honor of Snoop’s halftime performance, Blackrock has a special treat in store for the bears tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:50 </td>
   <td style="text-align:left;"> $SPY No Jay Z? I couldn&amp;#39;t brush dirt off my shoulders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:49 </td>
   <td style="text-align:left;"> $SOFI $SPY $LC 

HALF TIME SHOW WAS GOOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:48 </td>
   <td style="text-align:left;"> $SPY, is this another BET hoodball? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:42 </td>
   <td style="text-align:left;"> $SPY BEST HALFTIME SHOW HANDS DOWN

DETROITTTTTT in the house </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:41 </td>
   <td style="text-align:left;"> $SPY that was nice performance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:41 </td>
   <td style="text-align:left;"> $SPY  Do you guys ever wonder what else they are lying to you about or pretending that there is “no evidence to come to that conclusion” about? Think about it.
https://youtu.be/FmwBY-gJwkM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:39 </td>
   <td style="text-align:left;"> $SPY halftime show was 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:35 </td>
   <td style="text-align:left;"> $SPY shakira and jlow was better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:33 </td>
   <td style="text-align:left;"> $SPY best halftime show ever hands down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:29 </td>
   <td style="text-align:left;"> $SPY garbage halftime show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:23 </td>
   <td style="text-align:left;"> $SPY HOLY shit... Dre and Snoop... FUCKING OG fire🔥🔥🔥🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:23 </td>
   <td style="text-align:left;"> $SPY  all righty than </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:20 </td>
   <td style="text-align:left;"> $SPY 

Don’t tell me Beyonce got so old and fat. She still got her sausage thighs though… oh, that is not her? Sorry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:16 </td>
   <td style="text-align:left;"> $SPY only thing more bullish than the Super Bowl is a July 4th with some baseball hot dogs and fireworks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:14 </td>
   <td style="text-align:left;"> $SPY $463 open 🚀🚀🚀🚀 lmfao poor bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:08 </td>
   <td style="text-align:left;"> $SPY I read in a biology textbook that black people are closer in lineage to the chimpanzee than white people.  Is this true? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:05 </td>
   <td style="text-align:left;"> $SPY this music brought me flash backs of when I was a poor kid 

Now I’m making and losing wads of cash in this game 

f* got love for the (wall)streets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:24:03 </td>
   <td style="text-align:left;"> $SPY Dre by far the best part </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:23:50 </td>
   <td style="text-align:left;"> $SPY i need more titties on that show wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:23:41 </td>
   <td style="text-align:left;"> $QQQ $SPY $DKNG good performance by Brooks Koepka at the half time show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:23:41 </td>
   <td style="text-align:left;"> $SPY  Bloods disrespected big time lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:23:30 </td>
   <td style="text-align:left;"> $SPY needs Easy E to save this... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:23:26 </td>
   <td style="text-align:left;"> $SPY 

I&amp;#39;ve been warning folks since 2020, and I&amp;#39;ve been removed on this platform for who knows how many times. 

I knew this drug was a bioweapon as soon as I learned they were using MRNA to infiltrate cells and transform your body into an SPIKE protein manufacturer... MRNA should never be allowed to come close to being a VACCINATION because the potential for abuse is unimaginable.

NO PHARMACEUTICAL COMPANY ON EARTH SHOULD BE ALLOWED TO BE NEAR YOUR CELLS OR GENETIC INFORMATION. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:23:25 </td>
   <td style="text-align:left;"> $SPY Well looks like Russia is going into Ukraine based on troop movement and oil prices.  This may see some really low levels this week even if it does not happen.  $330 test is almost imminent at this point watching if we touch $318 this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:23:21 </td>
   <td style="text-align:left;"> $SPY This halftime show is fucking fire. Screw Kendrick, we got Dre, snoop and Em. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:23:06 </td>
   <td style="text-align:left;"> $SPY If only the past is glorified it must mean the future isn&amp;#39;t too good . . . 
 
all imo of course 
no super positive upcoming catalysts . . . 
 
Just a thought: BTS should&amp;#39;ve done the half-time, would&amp;#39;ve placed more int&amp;#39;l attention on the Super Bowl? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:50 </td>
   <td style="text-align:left;"> $SPY i am bearish on the market but not because of this russo ukranian bullcrap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:46 </td>
   <td style="text-align:left;"> $SPY best show up in a while yall. Dint forget America is enigmatic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:44 </td>
   <td style="text-align:left;"> $SPY Mary j was the star here. Otherwise it kinda ducked. I appreciate the 50 cent cameo though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:36 </td>
   <td style="text-align:left;"> $SPY seriously. Futures is meaningless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:33 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:28 </td>
   <td style="text-align:left;"> $SPY This half time show was funded with Jerome Powell QE. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:23 </td>
   <td style="text-align:left;"> $SPY  Bloods triggered rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:23 </td>
   <td style="text-align:left;"> $SPY futes looking fucking awful, decent game and halftime show. Great night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:20 </td>
   <td style="text-align:left;"> $SPY Lmao literally sent to the 2000&amp;#39;s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:18 </td>
   <td style="text-align:left;"> $SPY slim shady killing it, means green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:22:04 </td>
   <td style="text-align:left;"> $SPY white and rap is hard to pull off. MM is as close as you get though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:51 </td>
   <td style="text-align:left;"> $SPY when bengals win everyone head explodes and most of the work done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:40 </td>
   <td style="text-align:left;"> $SPY only white person in the whole halftime show is Eminem lol wouldn’t even matter if they didn’t try so hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:38 </td>
   <td style="text-align:left;"> $SPY  we need more white people everywhere.  Black people are starting to fancy themselves superior to the master race </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:35 </td>
   <td style="text-align:left;"> $SPY super bowl halftime show bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:35 </td>
   <td style="text-align:left;"> $SPY Everyone who hates this halftime show right now… $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:29 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:23 </td>
   <td style="text-align:left;"> $SPY 

Lol
You’re watching television. 

Dumbasses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:22 </td>
   <td style="text-align:left;"> $SPY E is liberals bitch just like the rest of them ! You were so talk to you take orders from the Democrat party you fake fucking entertainers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:19 </td>
   <td style="text-align:left;"> $SPY only good song from Eminem 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:13 </td>
   <td style="text-align:left;"> $SPY Everyone worried about the Russia/Ukraine tension never lived through the east coast/west coast rap wars of the late 90s 😭😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:12 </td>
   <td style="text-align:left;"> $SPY Eminem hyping bitches, niggas and white niggas all at the same time, fuking legend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:04 </td>
   <td style="text-align:left;"> $SPY ah the trash one was Kendrick.  makes sense now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:21:01 </td>
   <td style="text-align:left;"> $SPY 

Gangsta half time….nice. First time for everything! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:53 </td>
   <td style="text-align:left;"> $SPY Unless war has confirmed to begin this market will probably bounce. Its not just going to continue to selloff waiting for Russia to move. Keep in mind the Russia news isn&amp;#39;t new. This is a huge buy the dip opportunity until significant news comes out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:49 </td>
   <td style="text-align:left;"> $SPY Shady BOY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:47 </td>
   <td style="text-align:left;"> $SPY It was covid, WW3, now the half time show... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:44 </td>
   <td style="text-align:left;"> $SPY I feel so old 😭 watching this half time show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:42 </td>
   <td style="text-align:left;"> $SPY KING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:34 </td>
   <td style="text-align:left;"> $SPY whats Dre Day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:25 </td>
   <td style="text-align:left;"> $SPY omg it’s moms spaghetti guy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:23 </td>
   <td style="text-align:left;"> $SPY 😭😭😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:20 </td>
   <td style="text-align:left;"> $SPY scare half time show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:17 </td>
   <td style="text-align:left;"> $SPY Chain wallets wack. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:17 </td>
   <td style="text-align:left;"> $SPY Kendrick is fire brahhhhh🔥🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:16 </td>
   <td style="text-align:left;"> $SPY half time show really mid 🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:20:11 </td>
   <td style="text-align:left;"> $SPY Oh fuck they got Em lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:59 </td>
   <td style="text-align:left;"> $SPY Oh fuck Slim Shady go Lions bitch!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:58 </td>
   <td style="text-align:left;"> $SPY mom’s spaghetti!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:57 </td>
   <td style="text-align:left;"> $SPY It’s over bears and Russian trolls.
Tomorrow massive gap up as fear mongering fcktards get squeezed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:55 </td>
   <td style="text-align:left;"> $SPY $AAPL $ARKK $TSLA ya all ready for slim shady </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:47 </td>
   <td style="text-align:left;"> $SPY squares and boomers just losing their shit right now 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:46 </td>
   <td style="text-align:left;"> $SPY now the racist comments stop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:32 </td>
   <td style="text-align:left;"> $SPY macd crossover extremely bullish to 360 days futes open over 4440 we fly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:32 </td>
   <td style="text-align:left;"> $SPY If you&amp;#39;re mad you&amp;#39;re a boomer lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:30 </td>
   <td style="text-align:left;"> $SOFI $SPY Best halftime show. Bears are screwed after Bullard tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:19 </td>
   <td style="text-align:left;"> $SPY It was WW3, now it&amp;#39;s the half time show... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:14 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:19:09 </td>
   <td style="text-align:left;"> $SPY Eminem coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:18:57 </td>
   <td style="text-align:left;"> $SPY need more Dre </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-14 09:18:54 </td>
   <td style="text-align:left;"> $SPY Kendrick is nice too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:42:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 74643200. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:41:19 </td>
   <td style="text-align:left;"> $QQQ  
 
RUSSIA:  &amp;quot;We aren&amp;#39;t going to invade Ukraine&amp;quot; 
 
UKRAINE:  &amp;quot;Russia isn&amp;#39;t going to invade.&amp;quot; 
 
MEDIA:  &amp;quot;WAR IS IMMINENT arm Ukraine and get them fighting.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:41:13 </td>
   <td style="text-align:left;"> $MMAT $SENS $QQQ bout to be a dirty game from here like the market lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:41:08 </td>
   <td style="text-align:left;"> $SPY $QQQ halftime was garbage. Joe shiesty in control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:40:36 </td>
   <td style="text-align:left;"> $QQQ $SPY $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:40:25 </td>
   <td style="text-align:left;"> $SPY $QQQ The Rams should still be able to survive without OBJ since they still have the best receiver in the league in Kupp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:38:28 </td>
   <td style="text-align:left;"> $SPY $QQQ all of us posting about the super bowl on stocktwits are the single people 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:37:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM His balls are sweaty, knees weak, calls are heavy
There&amp;#39;s diarrhea on his sweater already, mom&amp;#39;s beefaroni
He&amp;#39;s nervous, but on the surface he looks balmy and shitty
To drop worthless calls, but he keeps on forgettin&amp;#39;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:36:31 </td>
   <td style="text-align:left;"> Oil keeps flying high-- Futures reversing, Crypto falling and Bonds are green on possible Catalysts that Ukraine might abandon NATO or moving on the news that Russia has now 130K soldiers at border $SPY $QQQ $XLE $BTC.X $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:32:12 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-13 Options Analysis Video: 
https://www.youtube.com/watch?v=OD__4ijo6Ew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:31:17 </td>
   <td style="text-align:left;"> $SPY $QQQ If you are hoping to make money on your shorts/puts on rate hikes then I don’t really have a problem with it, I have a problem with the bears hoping for WW3 though and so they can make some money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:29:42 </td>
   <td style="text-align:left;"> $spy $dia $QQQ puts on that halftime show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:29:31 </td>
   <td style="text-align:left;"> $QQQ $SPY just since 1989 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:29:19 </td>
   <td style="text-align:left;"> $SPY $QQQ  when you bought a bunch of puts for ww3 but only war happening is between you and your margin calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:28:48 </td>
   <td style="text-align:left;"> $SPY $QQQ The Super Bowl = the best show on the planet, nothing can compare with the Super Bowl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:28:17 </td>
   <td style="text-align:left;"> $SPY $QQQ is it me or 50 looking like a Dolla coin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:27:56 </td>
   <td style="text-align:left;"> $SPY $QQQ Best halftime show in years.  Not as good as Prince though that’s still the best.  They should have done the explicit version of “Nuthin but a G Thang” though.  😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:26:28 </td>
   <td style="text-align:left;"> $QQQ Market is going to be on fire this week! 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:25:18 </td>
   <td style="text-align:left;"> $SPY $QQQ This halftime show is the best ever in the Super Bowl. Now the Rams should have enough time to come up with a game plan for the second half without OBJ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:25:08 </td>
   <td style="text-align:left;"> Market Volume Barometer 2-11-2022 
Sentiment: LIMBO 
Volume: 0% 
Real Feel: SWELTERING 
Cycle: BEARISH I 
Portfolio: LONG 
Next Day Move: SIDEWAYS DOWN 
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/ 
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:24:42 </td>
   <td style="text-align:left;"> $QQQ put pucked..calls pucked..wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:24:04 </td>
   <td style="text-align:left;"> $QQQ futes ripping war adverted📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:23:41 </td>
   <td style="text-align:left;"> $QQQ $SPY $DKNG good performance by Brooks Koepka at the half time show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:22:33 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:18:25 </td>
   <td style="text-align:left;"> $QQQ NASDAQ bounced off the white indicators </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:18:16 </td>
   <td style="text-align:left;"> $SPY $QQQ What a good wholesome family event for wack history month. Thanks NFL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:17:01 </td>
   <td style="text-align:left;"> $QQQ anyone looking at futures at 5pm pst and taking them seriously is retarded 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:16:51 </td>
   <td style="text-align:left;"> $SOFI $SPY $QQQ slim shady will save us </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:16:37 </td>
   <td style="text-align:left;"> $QQQ  
 
The bars and restaurants in Kiev, are full.   
People are shopping and living normal lives. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:16:09 </td>
   <td style="text-align:left;"> $QQQ $SPY RUSSIA’S 1ST GUARDS TANK ARMY IS MOVING CLOSE TO UKRAINE BORDER, 130,000 RUSSIAN TROOPS NOW AT UKRAINE BORDER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:06:58 </td>
   <td style="text-align:left;"> $SPY $NASDAQ $QQQ So did the sky fall and WWIII break out yet? Maybe I missed it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:05:10 </td>
   <td style="text-align:left;"> $SPY  and $QQQ gave us millions last Friday on the Thursday setup. 
 
Biden did a great job with the early clues on Thursday morning which allowed the Boyz ample time to get loaded with cheap puts while the markets were very slow to respond but eventually saw the bright lights! 
 
These opps are rare but lately, it&amp;#39;s been wonderful and so lucrative.  Millions invested on the sly provides multi billions to a select few who keep smiling! ;-))))) 
 
Now we have another great setup this week.  Enjoy the opps and the manip.  Make banque! 
 
// </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:04:41 </td>
   <td style="text-align:left;"> $SPY $QQQ Super Bowl priced in, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:04:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA block all bears.  Imagine being so fucked up to take joy in the suffering of others.  I&amp;#39;d like to attend the funeral of their loved ones in a clown suit, running around screaming THEY DIED LOLOLOLOLOL and slapping everyone and laughing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:03:25 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Market will be Up 2-3% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 09:02:51 </td>
   <td style="text-align:left;"> $QQQ $SPY Buy the dip and sell the rally!
Welcome to this new market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:58:54 </td>
   <td style="text-align:left;"> $QQQ gap upnon amzn split announcement and Tom Lee comes out that he like gladiator movies🚀🦬🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:55:03 </td>
   <td style="text-align:left;"> $SPY Gold up, oil up, vix up, futures up, treasuries up, my dick up, what the actual fuck $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:49:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $INTC $TSLA organic seltzer?  Sounds like something Intel investors would drink…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:48:24 </td>
   <td style="text-align:left;"> $UVXY $QQQ https://www.youtube.com/watch?v=JlEGU2ypr1Q

Best interview hands on ever. It&amp;#39;s not about Russia or the occasional daily crisis... it&amp;#39;s about a systemic bubble. Remember indexes are the best of the best... if an index drops 30-50% then 90% of the stocks go down 50-80%... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:47:02 </td>
   <td style="text-align:left;"> $QQQ Hello Darkness my ole friend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:47:01 </td>
   <td style="text-align:left;"> $QQQ Nikki down 2%. Japan is always spooked with potential wars especially one that involves a country on their border ever since the last time they got two cities nuked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:46:55 </td>
   <td style="text-align:left;"> $QQQ $SPY  I got $24520 on bengals and I will lose it all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:46:49 </td>
   <td style="text-align:left;"> $QQQ Nasdaq Futures dropped 900 points in two days. We might get a small bounce in the morning then flush out again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:46:26 </td>
   <td style="text-align:left;"> $SPY breaking:  RUSSIA’S 1ST GUARDS TANK ARMY IS MOVING CLOSE TO UKRAINE BORDER, 130,000 RUSSIAN TROOPS NOW AT UKRAINE BORDER
$qqq $dia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:45:58 </td>
   <td style="text-align:left;"> $QQQ nato and USA will not send a single soldier into Ukraine even Russia invades… so buy on any dip…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:44:41 </td>
   <td style="text-align:left;"> $SPY $QQQ Futes update… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:42:26 </td>
   <td style="text-align:left;"> $SPY  $QQQ Even I am bearish side in short term ; damn after I saw clueless bulls annoying ; you guys deserve to lose call premium … only reason I wanna be bull today because of super bowl and pity on long holders …otherwise FED will screw the market with rate hikes plus .. bond buying end in March … so I ll buy my long term stocks so cheap soon 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:41:21 </td>
   <td style="text-align:left;"> $SPY $QQQ joe brrrrr @Prat_ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:40:26 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:38:59 </td>
   <td style="text-align:left;"> $QQQ green. 
 
no war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:38:42 </td>
   <td style="text-align:left;"> $SPY futures green. No war? Lol $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:38:38 </td>
   <td style="text-align:left;"> $QQQ look at that limit down!!! Dumbass bears spewing garbage all weekend lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:35:59 </td>
   <td style="text-align:left;"> $QQQ futures dropped quick... gonna be back and forth all day. Won’t know for sure until tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:34:38 </td>
   <td style="text-align:left;"> $QQQ those futes are really rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:31:46 </td>
   <td style="text-align:left;"> $SPY $QQQ No emergency rate hike tomorrow and still no war on Friday, I expect a pretty green week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:30:11 </td>
   <td style="text-align:left;"> $SPY $QQQ  friendly reminder - double digit PPI will be released 8:30 am on Tuesday,  huge market drop is expected after the release </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:30:02 </td>
   <td style="text-align:left;"> $QQQ https://www.marketwatch.com/investing/future/gc00/charts?mod=mw_quote_advanced 
gold and oil went up 1% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:28:08 </td>
   <td style="text-align:left;"> $SPY $QQQ If Mahomes didn’t choke then we would be seeing a competitive Super Bowl rather than a blowout 😨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:27:32 </td>
   <td style="text-align:left;"> $QQQ $SOFI $DOGE.X 

https://twitter.com/anthonynoto/status/1492940535337656321?t=rgWqPPP3RzIuhFqwNwRu6w&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:27:08 </td>
   <td style="text-align:left;"> $QQQ Qq momma qq momma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:22:45 </td>
   <td style="text-align:left;"> $QQQ Enjoy PM BULLS LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:22:09 </td>
   <td style="text-align:left;"> $QQQ , $IWM, $SPY
Need not say more…

https://www.zerohedge.com/markets/money-flowing-stocks-record-pace-goldman-does-not-see-larger-correction-taking-place </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:21:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $PFE $JNJ $MRNA if somebody can give me a legitimate answer as to why this is not a conflict of interest I will venmo you $10. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:21:27 </td>
   <td style="text-align:left;"> $QQQ oil and gold price is still going up, which it is a best data to prove that tomorrow trend. if the gold and oil keep going up. tomorrow will be 100% bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:20:59 </td>
   <td style="text-align:left;"> $QQQ I shoulda covered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:20:47 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:19:38 </td>
   <td style="text-align:left;"> $QQQ 

Check out these 3 stock targets for next week along with market analysis. 

https://youtu.be/VbMCRZdFvwY

// </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:19:29 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:18:45 </td>
   <td style="text-align:left;"> $QQQ futes tripping likebobjs hair </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:17:35 </td>
   <td style="text-align:left;"> $SPY  $QQQ Futures being red with Super Bowl night is unti American :)  even I think market will pull more ; I am happy to see green futures while super bowl game 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:14:55 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ 

😎😎😎😎😎😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:11:03 </td>
   <td style="text-align:left;"> $QQQ let&amp;#39;s see whos laughing after fed emergency meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:09:52 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:07:43 </td>
   <td style="text-align:left;"> $SPY $QQQ how is this not a conflict of interest? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:06:59 </td>
   <td style="text-align:left;"> $QQQ $SPY $TQQQ $BTC.X $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:05:41 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:04:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $UVXY just watched two dudes at Whole Foods remove about 500 avocados from the produce display. Calls on guacamole </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:03:53 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DJIA $IWM  
 
MMs and hedgies robbed the scared retail idiots once again. What else is new LOLOLOLOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:02:28 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-13 Trade Analysis Video: 
https://www.youtube.com/watch?v=iaa1HzPuaIE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:02:01 </td>
   <td style="text-align:left;"> $QQQ how the hell are the futures green? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:01:19 </td>
   <td style="text-align:left;"> $SPY $QQQ recon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 08:00:37 </td>
   <td style="text-align:left;"> $QQQ Futes are pumping like me in my gf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:59:49 </td>
   <td style="text-align:left;"> $QQQ lmfao idiot fear mongering bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:59:06 </td>
   <td style="text-align:left;"> $QQQ thank God for the dumb retail bulls buying the dip .  Hahaha suckers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:58:57 </td>
   <td style="text-align:left;"> latex94897ca0bc16774e90796034cf9811aaSpy futes

$qqq futes

Semi conductors rally! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:58:50 </td>
   <td style="text-align:left;"> $QQQ Boom 💥 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:58:04 </td>
   <td style="text-align:left;"> $QQQ E*Trade pump incoming tomorrow quick cover your shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:57:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK Falling sentiment = good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:57:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA $FUBO The market is always green after the Super Bowl.  And with no war, green dildos everywhere tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:55:34 </td>
   <td style="text-align:left;"> $SPY $QQQ  This should up at least 1% by the open, Asia and Europe were turbo short this on Fri because it was the only market open at the time, it was the only way to hedge against a war over the weekend, that didnt happen so they got to cover. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:55:15 </td>
   <td style="text-align:left;"> Goldman reiterates that global equities have logged $152.50B worth of YTD inflows so far in 2022, on pace to exceed 2021 inflows of 4913B  
 
$GS $SPY $QQQ $EEM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:55:07 </td>
   <td style="text-align:left;"> $QQQ any LEGIT justification as to which direction this opens tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:54:57 </td>
   <td style="text-align:left;"> $SPY $QQQ No point looking at futures now that fed meeting is announced the day will be flat until meeting lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:54:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

Odell making it look easy 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:53:52 </td>
   <td style="text-align:left;"> $QQQ Ummm why the celebration? QQQ is still red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:50:05 </td>
   <td style="text-align:left;"> $SPY $QQQ oil 95 a barrel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:49:44 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DJIA $IWM  
 
OH!!!!!!!!!!!!!! Look at that &amp;#39;Ukraine Invasion&amp;#39; crash that the bears predicted  LOLOLOLOLOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:49:21 </td>
   <td style="text-align:left;"> $QQQ I have started hating $BTC.X , it just follows the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:48:56 </td>
   <td style="text-align:left;"> $SOFI $QQQ $BTC.X 

https://twitter.com/SoFi/status/1492966862388449288?t=rI46CuNGRC8zzDwhudsAzQ&amp;amp;s=19

$SOFI 

Get your money right and free money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:48:37 </td>
   <td style="text-align:left;"> $QQQ greeeeeeeeeeeen!!! How you like that doom and gloom world gonna end bears??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:45:27 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
no rate hike tomorrow such fud bs  
 
definitely some Russian bot farms on here  
 
look at SF fed pres Daly’s response from today and multiple ppl from Friday. bullard is a fraud  
 
0.25bps raise in March max or no hike at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:43:58 </td>
   <td style="text-align:left;"> $QQQ omg would be so cool if there was a NASDAQ superbowl commercial. Then it would grow instantly like $CRO.X is totally gonna do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:43:25 </td>
   <td style="text-align:left;"> $QQQ $SPY $TQQQ $UVXY 

You guys crack me up for falling for this bs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:41:50 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ Anyone not hedging long positions with puts or uvxy clearly isnt paying attention. For the record, Ukraine isnt a nato country, people. It will never be. Russia will not likely attack during the Olympics. Think about it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:41:50 </td>
   <td style="text-align:left;"> $SPY when they reclaim the 200 MA only to lose it again, bad things tend to happen shortly after $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:40:16 </td>
   <td style="text-align:left;"> $QQQ got a question russel is more like nasdaq or Dow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:39:41 </td>
   <td style="text-align:left;"> $SPY  $QQQ  if the Rams lose, then Ukraine 100% gets invaded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:39:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 74643200. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:34:05 </td>
   <td style="text-align:left;"> $QQQ u&amp;#39;d have to be suicidal to PUT nas at 14000$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:33:31 </td>
   <td style="text-align:left;"> $QQQ Watch for the POP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:33:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA barring some miracle breakthrough, things are going to get real hairy once the European markets open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:33:01 </td>
   <td style="text-align:left;"> $SPY $QQQ Gold and oil look stable, it means the fears about war are easing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:32:51 </td>
   <td style="text-align:left;"> $F Excellent , welcome to Crash Monday  djia $SPX $NDX $spy $qqq https://www.investing.com/indices/indices-futures ... thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker  🐻❤ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:32:13 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
 
BULLS FOR THE BENGALS  
 
🐯🐯🐯🐯🐯🐯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:31:45 </td>
   <td style="text-align:left;"> $QQQ macd/ theezenutz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:31:22 </td>
   <td style="text-align:left;"> $qqq funny how most of you watching futures .. I bet you also wear diapers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:30:45 </td>
   <td style="text-align:left;"> $QQQ 
Relax: Dow Futes turned green ! Hah 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:30:02 </td>
   <td style="text-align:left;"> $SPY $QQQ No need to watch the futures now, nobody really trading until after the Super Bowl anyway 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:29:30 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY $SPX ,, More Bearish then Bullish , Sneaky Snake Trading Strategy  https://www.youtube.com/watch?v=Nmcv0LJXlgI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:29:01 </td>
   <td style="text-align:left;"> $SPY $QQQ red again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:28:37 </td>
   <td style="text-align:left;"> $QQQ whats a good link for futures? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:26:08 </td>
   <td style="text-align:left;"> $QQQ 60% cash waiting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:25:59 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:25:41 </td>
   <td style="text-align:left;"> $SPY a story as old as time... 
$qqq $dia @mbellizz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:25:32 </td>
   <td style="text-align:left;"> $QQQ stop falling all bs!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:25:23 </td>
   <td style="text-align:left;"> $SPY $QQQ No action from Russia over the weekend. Putin knows that we have a much strong military than they do and we would have easily destroy them if we decide to help Ukraine. Putin also know that President Biden is much smarter than Trump, Trump was a dumb clown who had no prior political experience </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:24:55 </td>
   <td style="text-align:left;"> $SPY $QQQ futues rrrripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:22:41 </td>
   <td style="text-align:left;"> $QQQ 
There is nothing intelligent to say about the near term direction of the equity, futures, fixed, commodity, or currency markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:21:18 </td>
   <td style="text-align:left;"> $SPY $QQQ  so is there some important FED meeting tomorrow? if so, what time? thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:20:17 </td>
   <td style="text-align:left;"> $QQQ I sold some more calls just now but I am pacing myself. Hoping some morons would buy nq and pump this for a better shorting opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:19:17 </td>
   <td style="text-align:left;"> $QQQ blood bath tomorrow. Futures dipping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:17:17 </td>
   <td style="text-align:left;"> $SPY go Bengals 
$DIA $NASDAQ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:16:49 </td>
   <td style="text-align:left;"> $QQQ future ripping !? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:16:31 </td>
   <td style="text-align:left;"> $QQQ bulls calls destroyed at open from time lost, and even slight decline at open 

I know because I am still short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:16:11 </td>
   <td style="text-align:left;"> The Bounce Trails Off As Sellers Re-Emerge $QQQ $IWM $SPX https://talkmarkets.com/content/stocks--equities/the-bounce-trails-off-as-sellers-re-emerge?post=344594 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:15:46 </td>
   <td style="text-align:left;"> $QQQ bulls got tech on their side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:15:06 </td>
   <td style="text-align:left;"> $SPY intersting futes slightly red but the $VIX.  Steady red as well. 🧐
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:14:41 </td>
   <td style="text-align:left;"> $QQQ $SPY wow this is escalating quickly. Nice! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:14:05 </td>
   <td style="text-align:left;"> $QQQ $SPY down &amp;gt;1% by morning? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:13:58 </td>
   <td style="text-align:left;"> $SPY $QQQ The inflation is driven by the supply chain issues indeed. COVID cases are now going down and we should be able to resolve the supply chain issue soon to push inflation down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:12:55 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TLT $GLD 
   
7.5% inflation  
  
0% interest rates  
9 trillion dollar balance sheet  
Still printing billions... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:11:59 </td>
   <td style="text-align:left;"> $BTC.X $UDN $IYR $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:11:04 </td>
   <td style="text-align:left;"> $SPY $QQQ Poor bulls may not be able to enjoy the Super Bowl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:10:20 </td>
   <td style="text-align:left;"> $QQQ well, if this breaks below $341 this will be a bloodbath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:08:17 </td>
   <td style="text-align:left;"> $QQQ when was the last 3% gap down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:06:15 </td>
   <td style="text-align:left;"> $QQQ When will the Russian troops finish the drills? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:05:41 </td>
   <td style="text-align:left;"> $QQQ $SPY no gap down ✅ now small runup overnight to make the chart look nice.. and dump tomorrow... Yes Please.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:05:16 </td>
   <td style="text-align:left;"> $QQQ good earnings  = selling 2022 logic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:04:43 </td>
   <td style="text-align:left;"> $QQQ $SPY desperate lol gap down again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:04:26 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures flat, not sure if too many people will watch the futures tonight since the whole world will be watching the biggest sporting event in the world. Guessing the Rams will win but I guess I will check the futures again after the game </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:04:18 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM $DJIA    
 
OHHHH MY! The bears were right! Look at that massive &amp;quot;invasion&amp;quot; crash!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:03:54 </td>
   <td style="text-align:left;"> $spy $qqq  
 
Russia this, Powell that, nobody fucking cares. always buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:03:33 </td>
   <td style="text-align:left;"> $QQQ I love the bulls. They just spam futures ripping... they deserve these upcoming losses 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:03:15 </td>
   <td style="text-align:left;"> $SPY $QQQ SORRY BEARS - RECESSION AVERTED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:02:20 </td>
   <td style="text-align:left;"> $QQQ futes ripping 🚀🚀🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:01:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $DWAC $LCID-  Should be very interesting tomorrow.   
 
Learn how to grow your small account in just a few weeks or apply our strategies to your main.  
https://www.wallstreetsttatrading.com/learn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:01:45 </td>
   <td style="text-align:left;"> $QQQ DOWN again!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:01:21 </td>
   <td style="text-align:left;"> $spy $QQQ  
 
IT&amp;#39;S FUCKING GREEN! AHHAHAHAA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 07:00:00 </td>
   <td style="text-align:left;"> $QQQ $spy $tsla Colonel Peteuaki at the Kremlin tells me the war is postponed until wednesday since the Generals were drunk and it’s raining… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:57:20 </td>
   <td style="text-align:left;"> $QQQ green wow huge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:56:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN AIRCRAFT CARRIER SOON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:56:09 </td>
   <td style="text-align:left;"> Senior CatAlyst’s new PT for $SPY is 3,500, buckle up lol. Photo courtesy of StockCats. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:55:29 </td>
   <td style="text-align:left;"> $SPY $QQQ  lol futes already ripping and pipping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:54:11 </td>
   <td style="text-align:left;"> $SPY $QQQ let the casino open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:52:57 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA remember people…
futures don’t mean shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:49:21 </td>
   <td style="text-align:left;"> $SPY $QQQ FUTES RIPPING PEOPLE SIPPING KIDS SINGING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:48:45 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY $SVXY $VXX  
12 minutes until go time 👍👍👍🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:46:45 </td>
   <td style="text-align:left;"> $SPY $QQQ  https://twitter.com/RussianEmbassy/status/1492485832753795074 
Cheap political points for Biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:46:24 </td>
   <td style="text-align:left;"> Buy $UPST buy $AFRM buy $BKKT.......BUY $QQQ  ......lol 
 
NOT!!!!!! Retail will buy and PRO is short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:42:29 </td>
   <td style="text-align:left;"> $QQQ load uppp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:42:26 </td>
   <td style="text-align:left;"> $SPY $QQQ There are two scenarios with high chance of happening tomorrow, IMO. I lean towards the first.  
1- We open positive and keep going up, the FED guy as a catalyst to suck in sheep. What would appear as a string rally to arund 4480-4500. If it&amp;#39;s the case very likely to selloff in the afternoon, in all cases less likely to go above Friday&amp;#39;s high and the selling would restart Tuesday. This would indicate January low will be held, $SPX will go to 4300 and reverse. This would be a good short opportunity with tight stop (short term) 
2- We gap down, or open negative and continu to selloff;  chances we will break January lows during the week and go as low as 4100 before turning around.  
$XBI As long as it is above 88.4, we are in business. If we rally to $SPX 4480-4500, I would sell some of my XBI calls to buy them lower if/when it pulls back to 90-91. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:42:08 </td>
   <td style="text-align:left;"> $QQQ down down and down. It&amp;#39;s clear to me this is very bearish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:41:58 </td>
   <td style="text-align:left;"> $QQQ wow futes green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:41:46 </td>
   <td style="text-align:left;"> $QQQ if no war next week. Get ready for Big pump. Fed will have measured interest rates, no doubt. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:39:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:38:36 </td>
   <td style="text-align:left;"> $GOOG $GOOGL $SPY $QQQ

GOOG/GOOGL retesting support lvls once again in conjunction with 200EMA expecting an imminent reversal on this once especially with its latest earnings performance and announcements </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:38:12 </td>
   <td style="text-align:left;"> $SPY $QQQ I feel bad for all the retail in is &amp;quot;bull&amp;quot; market now.. Too many warning signs for a big pullback.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:37:53 </td>
   <td style="text-align:left;"> $QQQ $SPI Do you think Ukraine is dying to join NATO if it knows that will mean it will be powdered to the ground? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:36:38 </td>
   <td style="text-align:left;"> $QQQ $SPY what they gonna do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:33:55 </td>
   <td style="text-align:left;"> $SPY $QQQ no war over the weekend.  Could be a Green Day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:33:20 </td>
   <td style="text-align:left;"> $QQQ war tmrw or bears are in trouble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:33:10 </td>
   <td style="text-align:left;"> $QQQ This will fall. I&amp;#39;m not saying all in one day but this 200ema will take us downhill... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:32:46 </td>
   <td style="text-align:left;"> $SPY $QQQ lets relax futes could be down 10% tn and be green by tm morning so nothing matters right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:30:37 </td>
   <td style="text-align:left;"> $QQQ 30mins till BULLS are saying Futures don&amp;#39;t matter... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:27:42 </td>
   <td style="text-align:left;"> The Fed will end the Bond buying on March 10  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:23:19 </td>
   <td style="text-align:left;"> $QQQ Russian Drills with tanks and more than 140,000 troops. Believe Russia Govt at your own risk ⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:21:59 </td>
   <td style="text-align:left;"> $QQQ the QQQ futs will open up 150.. Put buyers take it in the rear again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:21:14 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA good to see the president spending time today addressing the lack of black coaches in the NFL, meanwhile in the real world that doesn&amp;#39;t seem to matter for the guy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:19:04 </td>
   <td style="text-align:left;"> This weeks promises to be exciting 
$SPX $QQQ $TQQQ $IWM $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:18:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $BTC.X $DWAC  
 
Children bet on sports, real men bet on bitcoin using 125x leverage at futures market open at 6pm Sunday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:18:18 </td>
   <td style="text-align:left;"> $QQQ war tmrw says the bears. guess we shall see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:15:11 </td>
   <td style="text-align:left;"> $SPY $QQQ averaged almost 20% in the past 10 years…
The ones that missed most of that are the ones that are bashing the most right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:12:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUT tomorrow we could see BLOOD BATH repeatedly 🐻🐻🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:10:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN AIRCRAFT CARRIER SOON 😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:10:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA S&amp;amp;P 500 (SPY) Technical Analysis, Forecast, and Trade Ideas:  
https://www.youtube.com/watch?v=byNe02vPR_o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:08:09 </td>
   <td style="text-align:left;"> $QQQ $SPY Interesting tweet by Russian Embassy UK https://twitter.com/russianembassy/status/1492485832753795074?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:06:45 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:02:44 </td>
   <td style="text-align:left;"> The Federal Reserve’s rate debate and Ukraine tensions could jolt markets in the week ahead

$SPX $QQQ $VIX

https://www.cnbc.com/2022/02/11/fed-rate-debate-ukraine-tensions-could-jolt-markets-in-the-week-ahead.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:02:40 </td>
   <td style="text-align:left;"> $PYPL $QQQ $IPAY $SQ

PYPL is obeying the descending channel expecting a relief bounce soon as it approaching the bottom of the channel
SQ earnings approach can also act as an imminent reversal opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 06:00:56 </td>
   <td style="text-align:left;"> $QQQ puts into the hole is piggish, can work briefly, but poor r/r.  The mrkt is painting a huge range, while working sideways to slight down, while scarring the crap out of many with plunglettes.  
 
Every month it does not go up is roughly a 1% correction. That adds up over five or so months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:57:22 </td>
   <td style="text-align:left;"> $QQQ chart looks bad. death cross imminent.
lots of uncertainty 
343 price target this week, if that breaks 334 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:50:13 </td>
   <td style="text-align:left;"> $QQQ $GRIMACEBSC.X going parabolic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:49:54 </td>
   <td style="text-align:left;"> $QQQ no war please… no more useless wars. 
 
thank you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:48:52 </td>
   <td style="text-align:left;"> @alealcpa $QQQ monthly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:48:46 </td>
   <td style="text-align:left;"> $QQQ 
When do red futures open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:47:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Hey who&amp;#39;s ready to get hit over the head with not very subtle leftist dreck for three hours in the greatest subconscious reinforcement of the party line ever devised?  

Gambling, aggression, circus, spectacle, arrogance, gluttony, gross consumption, misogyny will all be on full display.  And that&amp;#39;s just the ads. 

Anachronistic, stupid, dull, and all just to sell you shit.  A giant commercial.  

Rams win 24-10. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:46:08 </td>
   <td style="text-align:left;"> $QQQ Oil is at $93.00 per barrel. Putin’s plan is working just fine. He will just sit on the boarder and inflate oil prices as long as he can $$$$. Facts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:41:58 </td>
   <td style="text-align:left;"> Inflation’s Impact on Stock Returns $SPY $QQQ $DJIA $DIA $AAPL https://www.billionaireclubcollc.com/inflations-impact-on-stock-returns/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:41:05 </td>
   <td style="text-align:left;"> $QQQ wait, I thought all this world turmoil was suppose happen under trump??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:40:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA So, who is ready for a rigged football game, Satanic halftime show, and brainwashing commercials? 🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:38:16 </td>
   <td style="text-align:left;"> $QQQ puts feels like a big sucker play here.. 
 
the bounce higher could be 5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:37:53 </td>
   <td style="text-align:left;"> $SPY $QQQ in joe shiesty we trust. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:37:12 </td>
   <td style="text-align:left;"> $AAPL $QQQ  this drama happens everytime only during a dems run govt... anywhere in the world.. dont understand the logic.. 😇😇😇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:33:07 </td>
   <td style="text-align:left;"> $SPY Everyone is so bearish, This will gonna fly coming Monday! $QQQ $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:30:45 </td>
   <td style="text-align:left;"> $QQQ If the bears need anything else to spread more fear...a sack of rice just fell over here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:29:54 </td>
   <td style="text-align:left;"> $QQQ  
 
&amp;quot;MOSCOW (AP) — Ukraine’s president played down intensified warnings of a possible Russian invasion within days, saying he had yet to see convincing evidence&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:25:25 </td>
   <td style="text-align:left;"> $QQQ Bigly gap up tomorrow! $355+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:23:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK  16% average sound good to everyone?  Or does everyone want to go to all cash? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:23:56 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears scared everything is priced in now🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:23:30 </td>
   <td style="text-align:left;"> Iranian official said nuclear talks becoming “more difficult” as West powers “pretends” $SPY $QQQ $DJIA $EURUSD  https://www.billionaireclubcollc.com/iranian-official-said-nuclear-talks-becoming-more-difficult-as-west-powers-pretends/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:23:05 </td>
   <td style="text-align:left;"> $QQQ geo-powerwise, an immed plunge from here makes US look surprising vulnerable to Russia, so I wld be surprised and in fact expect a small gain.  US is always, forever confident in the face of challenges and does not shrink. Does not mean a bear is not starting, but the timing won&amp;#39;t look like fear of russia actions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:19:27 </td>
   <td style="text-align:left;"> $QQQ $TQQQ 

I looked up the P/E ratio for the QQQ. I’m getting different numbers from the internet. Can someone please tell me the actual P/E? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:14:28 </td>
   <td style="text-align:left;"> $SPY can you imagine to know exactly when a war and market crash was coming
🤡🤡🤡

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:09:52 </td>
   <td style="text-align:left;"> $QQQ Daly just said will take a measured approach to interest rate hikes (Opposite of Bullard).   Nothing happened with Russia over the weekend so far.  I expect a green market on Monday especially after dropping 5%+ the last 2 trading sessions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:09:21 </td>
   <td style="text-align:left;"> $QQQ so what else did just google tell you geopol geniuses? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:08:00 </td>
   <td style="text-align:left;"> Stock Market Crash Update: Ukraine, Oil &amp;amp; Inflation $SPY $QQQ $IWM $VIX https://www.youtube.com/watch?v=dw4ccqkTN6U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:06:14 </td>
   <td style="text-align:left;"> Invest with an outcome based approach on $QQQ. Make up to 9.0% (9.6% annualized) and start to lose only if $QQQ drops by more than 19.3% through 01/20/2023.

Buy 1 $345 call
Sell 1 $370 call
Sell 1 $280 put
 1/20/23 expiration
https://o.oliveinvest.com/25thuz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:06:03 </td>
   <td style="text-align:left;"> $QQQ does this drop below 340 this week or next? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:05:47 </td>
   <td style="text-align:left;"> $QQQ $SPY I can’t wait to find out if stocks are going down this week because bond yields are going up because of inflation or if stocks are going down because bond yields are going down because of war lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:05:16 </td>
   <td style="text-align:left;"> $QQQ -200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:03:38 </td>
   <td style="text-align:left;"> Tax Strategies for Your Retirement Income $SPY $QQQ $DJIA $DXY $TSLA  https://www.billionaireclubcollc.com/tax-strategies-for-your-retirement-income/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 05:00:09 </td>
   <td style="text-align:left;"> $QQQ Europe is defcon 2... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:58:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA BENGALS 🐅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:53:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  
 
$NKE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:51:09 </td>
   <td style="text-align:left;"> Ambassador Bridge still closed ... love it ... welcome to crash Monday and beyond and the Autogeddon Depression ... check out the live 24/7 webcam inbound, outbound 🇨🇦🇺🇸 https://www.ambassadorbridge.com/into-canada/ F  GM  TM  TSLA 
 STLA  and more re LINAMAR, MAGNA, et al  $DJIA $SPX $NDX $spy $QQQ 🤑😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:49:27 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:49:22 </td>
   <td style="text-align:left;"> $QQQ Seriously what is the BULL case for tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:46:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 74643200. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:41:19 </td>
   <td style="text-align:left;"> $QQQ no one knows up or down yet so stf up please . You bought puts so you hope it&amp;#39;s down you bought calls so you hope it&amp;#39;s up . Thays all this board is . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:41:13 </td>
   <td style="text-align:left;"> $QQQ 
QQQ above $347.84 for a potential run up.
QQQ below $345.53 for a potential drop.
#scalp
Watchlist 2/14/22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:35:33 </td>
   <td style="text-align:left;"> $SPY if war is real then big loss for Russia and China . USA will become much stronger $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:33:12 </td>
   <td style="text-align:left;"> ROTFLMAO  .. the fools can&amp;#39;t make money during the Armageddon Depression so why not?  https://finance.yahoo.com/news/super-bowl-lvi-sports-betting-200931747.html ... loving my 🇺🇸 stocks active short trading for profits  🤑🐻❤😈  $djia $SPX $NDX $spy $qqq  ... enjoy Crash Monday and beyond starting at 6 PM EST today 👍😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:25:42 </td>
   <td style="text-align:left;"> $SPY $QQQ ITS TIME FOR ROCKET BLAST TIME HOPE AND PROGRESS FOR US WE PRAY 🤲 LAUNCH IT HIGH PRICES??!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:23:37 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DJIA $IWM    
 
OHHHHHHHHHHHHH the mkt looks soooooo terrified ...off 48pts   LOLOLOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:17:32 </td>
   <td style="text-align:left;"> $QQQ 310 soon. Fed is going to pop some bubbles. Real inflation is 15%. Get ready. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:17:02 </td>
   <td style="text-align:left;"> February 7th - February 11th Trade Log 📝    
   
$SPX $TSLA $QQQ  
  
Follow us on Twitter for more Trade Ideas: twitter.com/eliteoptions2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:16:30 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:16:21 </td>
   <td style="text-align:left;"> $BTC.X 50k looking good $SPY $QQQ $MSTR https://www.bloomberg.com/news/articles/2022-02-11/rapper-drake-turns-to-bitcoin-for-million-dollar-super-bowl-bet?sref=xuVirdpv&amp;amp;utm_content=business&amp;amp;utm_source=twitter&amp;amp;cmpid=socialflow-twitter-business&amp;amp;utm_medium=social&amp;amp;utm_campaign=socialflow-organic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:16:10 </td>
   <td style="text-align:left;"> $QQQ $SPY more fear mongering :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:14:01 </td>
   <td style="text-align:left;"> $QQQ $IWM $SPY $HOOD $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:13:04 </td>
   <td style="text-align:left;"> $SPY $QQQ there have never been so many reasons to be cautious.

Inflation, interest rates, war, and the fed pulling back their pandemic pump to name a few.

Plus there’s this 14 year parabolic bull run that is unprecedented and needs a healthy pullback.

2022 is the year we reset. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:12:19 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:12:19 </td>
   <td style="text-align:left;"> $QQQ het ready people. We are in a stage 4 correction from a technical standpoint. The days of easy money are over. Blood is coming to the markets, will be down over 30% in the next 4 months. Dont go full retard.🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:10:41 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA Do we have any big market catalysts planned this coming week? That could change market direction up or down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:08:30 </td>
   <td style="text-align:left;"> $SPY $QQQ i live in Ukraine here to answer any questions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:04:26 </td>
   <td style="text-align:left;"> $QQQ $SPY NFL is rigged Rams will win at home </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:03:13 </td>
   <td style="text-align:left;"> $QQQ markets right as rain

https://media0.giphy.com/media/WxDZ77xhPXf3i/giphy.gif </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:00:58 </td>
   <td style="text-align:left;"> $QQQ bullflag thrown.... Intern is working hard in putins office to calm him down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 04:00:13 </td>
   <td style="text-align:left;"> Stock Market Health Update For Swing Trading - Week Of Feb. 14 $TSXV $QQQ $IWM $SPX https://talkmarkets.com/content/global-markets/stock-market-health-update-for-swing-trading-week-of-feb-14?post=344580 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:59:27 </td>
   <td style="text-align:left;"> $QQQ another monster earnings week

https://invescohood.com/top-10-most-anticipated-earnings-this-week-2/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:55:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM $SOX If you think you can time the market, great! I won’t waste my resources trying. I’m looking for bargains at every significant dip. Don’t let fear mongering paralyze you just as you shouldn’t buy an equity with exuberant valuation or FOMO. Be mindful of the ST “gurus” who spend hours posting macro analysis scaring you to death of the impending “crash”. When was the last time a crash happened as people were hedged to the hilt waiting for it to happen??? Also, the issue I see staying in cash is that suddenly the market will reverse, as it always does, and you will miss out on that nice 5% jump, which you’ll chase and buy high just to regret sooner than later. I use EW to see the big picture, and it’s telling me the market might revisit January 24 lows, then it’ll melt up before BIG bear arrives. It’ll all happen this year! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:51:39 </td>
   <td style="text-align:left;"> Weekly Futures Market Outlook: 2.14.22 - 2.18.22 
Discussing the main fundamental themes and technical levels to pay attention to  
$ES_F $SPY $NQ_F $QQQ  
   
https://www.youtube.com/watch?v=zWtTRkWvpwQ&amp;amp;ab_channel=LandsharkCapital </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:50:58 </td>
   <td style="text-align:left;"> $QQQ - Green Market for sure tomorrow!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:48:13 </td>
   <td style="text-align:left;"> $AABB Which exchange will $AABB be on in 2023 $NASDAQ is my guess? $SPY $SPX $QQQ https://finance.yahoo.com/news/asia-broadband-corporate-173900628.html Stay ahead of the news/curve. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:45:36 </td>
   <td style="text-align:left;"> $QQQ https://www.channelchek.com/news-channel/How_Reliable_is_the_Super_Bowl_Indicator </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:43:57 </td>
   <td style="text-align:left;"> $QQQ - Go Rams! 
We may get an interim low reading on the PPI number on Tuesday , only due to the dip in oil and auto dealers that  over ordered allocations in anticipation of more chip shortages

Higher loan rates, market tanking  issues  are starting to slow down purchases by free money spenders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:37:50 </td>
   <td style="text-align:left;"> $QQQ i say we hit 343 then have a little bounce then if shit hits the fan test support level of 334 this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:37:34 </td>
   <td style="text-align:left;"> $SPY $SPX $IWM $QQQ    
 
Retail is sooooo scared   thats so BULLISH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:35:56 </td>
   <td style="text-align:left;"> $INMD last year guide was also 18-20% and the grew 73% and you gonna tell me that they guided 18-20% again amd they will only grow that much? I&amp;#39;m not stupid but someone wants cheap shares $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:32:58 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ At that point in my life where I’m more excited about futures than the Super Bowl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:28:12 </td>
   <td style="text-align:left;"> $SPY $qqq don’t worry everyone, the war is coming. just delayed a couple of days while the Generals sober up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:26:15 </td>
   <td style="text-align:left;"> $QQQ $SPY go bengals! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:24:01 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:20:32 </td>
   <td style="text-align:left;"> Forecasters project steady jobs growth as Fed moves to tame inflation

https://www.reuters.com/business/us-economy-could-be-weaker-q1-than-previously-thought-forecasters-say-2022-02-11/

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:19:49 </td>
   <td style="text-align:left;"> @mregory_gannorino the market is goin up Monday. $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:19:36 </td>
   <td style="text-align:left;"> Fed&amp;#39;s Daly advocates for a &amp;#39;measured&amp;#39; approach as rate hike expectations rise

https://www.google.com/amp/s/www.cnbc.com/amp/2022/02/13/feds-daly-advocates-for-a-measured-approach-as-rate-hike-expectations-rise.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:16:22 </td>
   <td style="text-align:left;"> $QQQ Am I reading this correctly? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:16:03 </td>
   <td style="text-align:left;"> $QQQ Too big to fail. Where my PPT from 2008?!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:14:26 </td>
   <td style="text-align:left;"> $QQQ Bulltards get ready!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:13:20 </td>
   <td style="text-align:left;"> $QQQ People, the Russian-Ukrainian border has been militarily guarded since 2015.... I travel casually to Russia regularly.... Putin feels threatened because the NATO East expansion is to be expanded against the promises of the criminal German government.... What would you do what you do when all your neighbors are reporting badly about you, handing out weapons in front of your house... I would also get ready.... don&amp;#39;t let the media blind you.... Russia is huge and has no interest in more Country. $DYD $PYPL $PLTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:11:49 </td>
   <td style="text-align:left;"> $QQQ way too many bears 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:10:51 </td>
   <td style="text-align:left;"> $SPY The reason Jake Sullivan keeps  yelling war is because he is part of Clinton illegal activities.  Just trying to keep control of headlines.  Can&amp;#39;t blame the guy.   https://www.google.com/amp/s/nypost.com/2021/09/23/did-jake-sullivan-commit-perjury-e-mails-reveal-lie-on-trump/amp/  $BTC.X $QQQ $TSLA Wag the Dog and puppets fall for it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:09:13 </td>
   <td style="text-align:left;"> $SPY $DIA $NASDAQ $QQQ W.H: Ukrainian President Volodymyr Zelenskiy and U.S. President Joe Biden stressed the importance of pursuing “diplomacy and deterrence in response to Russia’s military buildup on Ukraine’s borders&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:07:39 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ Inflation Calculator

https://www.in2013dollars.com/us/inflation/1955?amount=10000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:05:33 </td>
   <td style="text-align:left;"> $SPY $QQQ Russian invasion DD on Wall Street Bets is higher quality than what you are being given on the news, sad timeline.  Fact is that White House is spreading worst case scenario FUD so they don’t look like they got blindsided like they did in Afghanistan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:05:14 </td>
   <td style="text-align:left;"> $SPY $FB $QQQ one of the few times Cramer was right about something 

https://youtu.be/EWtMFnjN1Tg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:04:25 </td>
   <td style="text-align:left;"> $SPY $QQQ 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 03:02:16 </td>
   <td style="text-align:left;"> $QQQ limit up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:59:54 </td>
   <td style="text-align:left;"> $SPY $QQQ seeing bulls and bears going back and forth makes me sleep good at night as I went cash on the weekend. I just play the trend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:57:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA WHO NEEDS FUTES WHEN YOU HAVE $BTC.X LOL MARKETS WILL POOP THE BED BIGLY TOMORROW OH WELL GO BENGALS 🐅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:55:02 </td>
   <td style="text-align:left;"> $SPY $QQQ just remember, 10% for the big guy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:52:17 </td>
   <td style="text-align:left;"> $QQQ wish I had the balls to buy calls end of day Friday lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:51:05 </td>
   <td style="text-align:left;"> $QQQ BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:49:00 </td>
   <td style="text-align:left;"> $QQQ all three circuit breakers will be hit tomorrow and the market will be closed by 10:30. Same thing will happen Tuesday and this will be below 250 by end of month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:44:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA BENGALS 🐅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:42:59 </td>
   <td style="text-align:left;"> $QQQ stop spreading fear. USA is great. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:42:45 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TLT $GLD  
 
7.5% inflation 
 
0% interest rates 
9 trillion dollar balance sheet 
Still printing billions... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:34:39 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $NASDAQ $DAX German leader will visit Moscow so I guess nothing happens the next 24 hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-14 02:29:12 </td>
   <td style="text-align:left;"> $QQQ no war! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 09:38:32 </td>
   <td style="text-align:left;"> $SPY don’t get swindled tomorrow morning buying in morning because of FOMO and then we close red… $aapl $googl $tsla $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 09:33:56 </td>
   <td style="text-align:left;"> $AAPL bye bye rams </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 09:19:55 </td>
   <td style="text-align:left;"> $SPY $AAPL $ARKK $TSLA ya all ready for slim shady </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 09:16:54 </td>
   <td style="text-align:left;"> $SPY $AAPL $ARKK halftime </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 09:11:27 </td>
   <td style="text-align:left;"> $COIN $AAPL $NVDA 

Nas 200 points up
Dow 500 points
Shorts get their asses handed over
Futures are up big time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 09:09:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 09:03:25 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Market will be Up 2-3% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 09:00:20 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:55:41 </td>
   <td style="text-align:left;"> $AAPL futes is ripping now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:53:28 </td>
   <td style="text-align:left;"> $GOOGL futes ripping  $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:51:41 </td>
   <td style="text-align:left;"> $AAPL     🍏 IPhone SE 5G:  Release:  AppleEvent March 8?  😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:47:54 </td>
   <td style="text-align:left;"> $AAPL 
🔝
Apple Stock: Upgraded PT On Stronger Revenue Growth (NASDAQ:AAPL) | Seeking Alpha. 

https://seekingalpha.com/article/4486671-apple-stock-price-target-upgraded-stronger-revenue-growth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:37:00 </td>
   <td style="text-align:left;"> $AAPL japan do not fuck us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:33:22 </td>
   <td style="text-align:left;"> $AAPL no Touch ID? Fuck apple! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:32:49 </td>
   <td style="text-align:left;"> $AAPL Tomorrow UPGRADE. $210🍏🔜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:32:24 </td>
   <td style="text-align:left;"> $AMD  $nvda  $tsla  $AAPL  
 
 https://www.investopedia.com/ask/answers/043015/what-difference-between-accretive-and-dilutive-merger.asp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:16:27 </td>
   <td style="text-align:left;"> $AAPL 

Check out these 3 stock targets for next week along with market analysis. 

https://youtu.be/VbMCRZdFvwY

———— </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:15:34 </td>
   <td style="text-align:left;"> $AAPL missed the superbowl $coin giveaway because it took almost 10 seconds for my camera to start working thanks fir the planned obselecence </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:12:05 </td>
   <td style="text-align:left;"> $AAPL Green Day! 

https://youtu.be/51CxtNl7AEI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:03:35 </td>
   <td style="text-align:left;"> $AAPL there goes futes.  Called it!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 08:02:05 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-13 Trade Analysis Video: 
https://www.youtube.com/watch?v=AS8F5hrWtr4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:53:44 </td>
   <td style="text-align:left;"> $AAPL futes is ripping now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:52:38 </td>
   <td style="text-align:left;"> $AAPL $SPY nasdaq barely moving due to 10 yr spike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:51:44 </td>
   <td style="text-align:left;"> $NIO $AAPL $TSLA A NEW, SIMPLE AND EASY METHOD TO UNDERSTAND TECHNICALS, TO CALL TOP AND BOTTOM. FREE VIDEO AND FREE TUTORIAL  https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:46:40 </td>
   <td style="text-align:left;"> $AAPL green Monday and the market all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:35:58 </td>
   <td style="text-align:left;"> $SPY Anyone else surprised crypto hasnt dropped to a penny $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:28:15 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG green after RAMS win tonight money going to be flying into the market with them gains!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:26:17 </td>
   <td style="text-align:left;"> $SPY $TQQQ $AAPL $GOOGL 
Go Go Rams  ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:25:29 </td>
   <td style="text-align:left;"> $SPY $TQQQ $GOOGL $AAPL $UBER 
Best Anthem ever  🎊😍
Thanks Mickey Guyton </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:25:08 </td>
   <td style="text-align:left;"> $AAPL $150  🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:24:48 </td>
   <td style="text-align:left;"> $AAPL futes abt to turn around big time overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:15:22 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $AAPL is the #1 stock that institutions traded this week with 288.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:08:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:05:44 </td>
   <td style="text-align:left;"> $AAPL got my bid in GTC .0001 should get filled by next Tuesday LOSEday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 07:00:31 </td>
   <td style="text-align:left;"> $AAPL go futes go!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:58:52 </td>
   <td style="text-align:left;"> $AAPL futures gonna be up 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:58:14 </td>
   <td style="text-align:left;"> $SPY $AAPL #DIA  the Dow 30  in n out pattern..   retested old flat cloud equilibirum levels.. icimoku cloud forms 26 days ahead of current price from past 26 candle avergaes and plotted for future support and resistance.  *old levels price reacts also.  
 
**i post charts for myself for future levels to watch of support and resistance levels.  most dont look at ichimoku indicator so please ignore my posts.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:54:48 </td>
   <td style="text-align:left;"> $SPY  $AAPL $VIX  tested old long strong flat cloud ichimoku green line level. that is where price average spent a lot of time.  9 and 26  red/white candle average line get tested alot in choppy  zone before trend. accumulation zone between blue lines.  
 
the Pillsbury Doughboy thinks the VIX put sweepers were fluffy and interesting .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:53:48 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:50:11 </td>
   <td style="text-align:left;"> $SPY move along bulls... LIMIT DOWN MONDAY! 🚨  
 
Any attempted POPS - &amp;quot;SHORTTHETOPBRO&amp;quot; $TSLA $AFRM $PTON $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:45:01 </td>
   <td style="text-align:left;"> Wholly Owned Subsidiary Definition $TSLA $AAPL https://www.billionaireclubcollc.com/wholly-owned-subsidiary-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:36:12 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG load uppp the media is scaring everyone over nothing “war” “rate hikes” “inflation” all bs!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:34:59 </td>
   <td style="text-align:left;"> $AAPL 💀✝️ $160 by months end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:08:46 </td>
   <td style="text-align:left;"> $NIO $TSLA $AAPL A SIMPLEST WAY TO BUY BOTTOM SELL TOP. FREE VIDEO FREE TUTORIAL. ENJOY https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:08:26 </td>
   <td style="text-align:left;"> $AAPL this should see 162 to 164 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 06:08:19 </td>
   <td style="text-align:left;"> $AAPL daily -
Has held up well, but starting to break down. One of the last standing in QQQ/SPY
Should see some good down moves over next couple weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:58:39 </td>
   <td style="text-align:left;"> Taking Social Security Early: Pros and Cons  $AMZN $TSLA $AAPL $MA $V https://www.billionaireclubcollc.com/taking-social-security-early-pros-and-cons/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:56:51 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA thank u POTUS for making awareness about climate change , taking leadership and making the right moves , we r with u and will be with u come 2024 , thank u sir 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:49:55 </td>
   <td style="text-align:left;"> How to Set Up a Trust Fund $BAC $JPM $WFC $C $AAPL https://www.billionaireclubcollc.com/how-to-set-up-a-trust-fund/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:47:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Hey who&amp;#39;s ready to get hit over the head with not very subtle leftist dreck for three hours in the greatest subconscious reinforcement of the party line ever devised?  

Gambling, aggression, circus, spectacle, arrogance, gluttony, gross consumption, misogyny will all be on full display.  And that&amp;#39;s just the ads. 

Anachronistic, stupid, dull, and all just to sell you shit.  A giant commercial.  

Rams win 24-10. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:44:57 </td>
   <td style="text-align:left;"> $AAPL inflation is so temporary that these dip are all gifts to buy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:41:58 </td>
   <td style="text-align:left;"> Inflation’s Impact on Stock Returns $SPY $QQQ $DJIA $DIA $AAPL https://www.billionaireclubcollc.com/inflations-impact-on-stock-returns/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:39:33 </td>
   <td style="text-align:left;"> $AAPL we need more bulls to buy the dip on AAPL … I need to reload cheap puts please. Thank you 🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:37:12 </td>
   <td style="text-align:left;"> $AAPL $QQQ  this drama happens everytime only during a dems run govt... anywhere in the world.. dont understand the logic.. 😇😇😇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:35:52 </td>
   <td style="text-align:left;"> 🔥We are now live 🔥 
📈 THE WEEKEND UPDATE 📈 
IM GOING TO BREAK DOWN  👇 
📈TRADE IDEAS  
🔫TRIGGERS  
🎯TARGETS  
🚨SECTORS CLICK  
👉 https://us02web.zoom.us/j/82883233300  $SPY  $AAPL   $TSLA    $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:34:44 </td>
   <td style="text-align:left;"> $AAPL $MSFT easy money. Putin will provide </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:34:18 </td>
   <td style="text-align:left;"> $AAPL green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:33:07 </td>
   <td style="text-align:left;"> $SPY Everyone is so bearish, This will gonna fly coming Monday! $QQQ $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:30:06 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOGL $NVDA Constructing my Roth account around these big players. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:29:16 </td>
   <td style="text-align:left;"> $AAPL $NIO $TSLA WILL HAIKIN ASHI CANDLES STAND TEST OF TIME WITH APPLE? YES THEY WILL AND YOU CAN USE THEM FOR FINDING THE TOP AND BOTTOM https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:15:06 </td>
   <td style="text-align:left;"> What to Know About Restricted Stock Units  $AAPL $TSLA $AMZN $LCID $SNAP https://www.billionaireclubcollc.com/what-to-know-about-restricted-stock-units/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 05:06:34 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL), Peloton Interactive, Inc. (NASDAQ: $PTON) – Why Apple’s Business Model Won’t Work For Peloton And How The Fitness Company Can Turnaround Its Business https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-peloton-interactive-inc-nasdaqpton-why-apples-business-model-wont-work-for-peloton-and-how-the-fitness-company-can-turnaround-its-business/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 04:55:05 </td>
   <td style="text-align:left;"> $AMD $ABNB $GOOGL $AAPL $DIS Monday we Rally
https://www.cnbc.com/2022/02/13/feds-daly-advocates-for-a-measured-approach-as-rate-hike-expectations-rise.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 04:53:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  
 
$NKE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 04:46:46 </td>
   <td style="text-align:left;"> $AAPL My special needs chil is onto something. 
https://youtube.com/shorts/ag21AzrqbHE?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 04:45:21 </td>
   <td style="text-align:left;"> #Levermann #Global #MegaCap #Sell WK6 $AAPL (1), $MSFT (2), $AMZN (-1), latex2ca6f4a70372256fe4d39fd8fca26d19aapl
$tsla

Forget superbowl .... futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 04:39:08 </td>
   <td style="text-align:left;"> $TSLA $NIO $AAPL price action through lens of Haikin Ashi candles !!! MUST WATCH https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 04:12:19 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 04:09:40 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 03:50:11 </td>
   <td style="text-align:left;"> $AAPL Haikin Ashi can be used to call the top and bottom trends. WATCH THIS TO FIND OUT. https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 03:48:59 </td>
   <td style="text-align:left;"> $IDEX $LI $QS $AAPL  
 
https://www.youtube.com/watch?v=bSMJqNXmm80 
 
$ABML It&amp;#39;s only a matter of time. 
 
You will all need us sooner than you think. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 03:47:56 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 03:35:10 </td>
   <td style="text-align:left;"> $AAPL torn about whether to buy this here for long term. Arguments from both sides are welcomed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 03:32:59 </td>
   <td style="text-align:left;"> $FB $GOOG $AAPL the world is shifting to apps for information, not websites. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 03:28:28 </td>
   <td style="text-align:left;"> $AAPL I cannot figure out from this chart, is it cheap to buy now? iI think it is. Going all in tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 03:28:04 </td>
   <td style="text-align:left;"> $SPY Tits Up Monday!  BULLS are a dying breed☠️ in 2022, any analyst upgrade in BIG TECH will be Sold into -$TSLA $AAPL $AMZN $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 03:06:43 </td>
   <td style="text-align:left;"> $AABB $AMZN $AAPL $TSLA $MSFT Are all Massive Growth stocks 2 of which started in small garages. The Vision/Execution made these Blue Chips what they are today. If you are looking for the Next one look into $AABB Gold miner/Global Exchange/100M+ in assets/No Debt/First to market Global Gold currency system. Corporate up date last week ststed their intentions of up listing on a MAJOR EXCHANGE. Oversold,Undervalued,BOOM TOWN!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 02:47:01 </td>
   <td style="text-align:left;"> $AAPL $SPY Remember to always keep drafting portion of your gains to your bank account regularly. especially option players. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 02:41:47 </td>
   <td style="text-align:left;"> $AAPL $SPY $TSLA weekend chart studying . Post your ticker below and I&amp;#39;ll do a quick analysis on it...Thanks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 02:39:56 </td>
   <td style="text-align:left;"> $AMD $AAPL $MSFT $NET The Fed committee probably pulled Jim Bullard into an ally this weekend and taught him a lesson. He&amp;#39;ll probably show up to his CNBC interview tomorrow with a few stitches and a black eye 
 
https://www.cnbc.com/2022/02/13/feds-daly-advocates-for-a-measured-approach-as-rate-hike-expectations-rise.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 02:36:08 </td>
   <td style="text-align:left;"> $AAPL we printed 7trillion $s do we not see some mass correction lmao 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 02:27:09 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $AAPL is the #1 ticker with sweep activity that institutions traded urgently this week options with 234.0K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 02:21:29 </td>
   <td style="text-align:left;"> Why Apple&amp;#39;s Business Model Won&amp;#39;t Work For Peloton And How The Fitness Company Can Turnaround Its Business  $PTON $AAPL $AMZN $NKE 

https://newsfilter.io/a/3e3fe534edf595e73bf42723c1f83fd3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 02:02:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.38%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 01:52:49 </td>
   <td style="text-align:left;"> $FB Taking more bread off the table?   $AAPL $AMZN $GOOG $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 01:47:29 </td>
   <td style="text-align:left;"> $SPY Russia - Ukraine is another bullshit story to steal your shares for cheap. Don’t be fool the market has seen worse than this before. Don’t forget the recessions we had in the past. Good companies always survive and go up. Look at $AAPL $MSFT $GOOGL and  so on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 01:41:43 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 01:38:51 </td>
   <td style="text-align:left;"> $SPY Low IQ 🥴slobber drip bulls are scrambling to convince themselves the cheap money thrill party of the Feds isn&amp;#39;t coming to an end! The nerve of Wall Street pansies contempt to reality that they&amp;#39;ll be protected ABOVE ALL OTHER PEOPLE on the planet during WAR,  COVID,  INFLATION,  INSIDE FED TRADING,  LACK OF GOVERNMENT STIMULUS,  CHINA DECOUPLING etc etc etc..  FEDS HAVE NO CREDIBILITY LEFT! America hasbigger problemsthan Putin alone!  
 
&amp;quot;SHORTTHETOPBRO&amp;quot; - $aapl $tsla $qqq $afrm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 01:03:33 </td>
   <td style="text-align:left;"> $AAPL  Out of the 372 other times AAPL was down 2.3% during a trading day, 53% of the time it traded higher by the next day&amp;#39;s market close. #CoinFlip link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 00:51:47 </td>
   <td style="text-align:left;"> $RIDE $GGPI $TSLA $AAPL  make sure your looking out for joe in the endurance today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 00:49:35 </td>
   <td style="text-align:left;"> $AAPL : Apple Inc.&amp;#39;s (NASDAQ:AAPL) retail store workers are in for a windfall, as Cupertino is reportedly raising pay for them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 00:33:29 </td>
   <td style="text-align:left;"> $AAPL Has been very technical off the Jan 24 low.  Momentum  is suggesting that a pullback against the Jan 24 low may be underway in this instrument.   we do not like to sell short $AAPL only like buying blue boxes. #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 00:16:25 </td>
   <td style="text-align:left;"> $SPY $DIA $MSFT $AAPL $IWM  Found a great app for anyone under the TSP retirement, it’s called daily tsp and tracks your portfolio just like a brokerage account, curbs my day trading addiction and keeps me wanting to add more and more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 00:13:02 </td>
   <td style="text-align:left;"> Who’s got who winning the super bowl? $SPY $QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-14 00:02:28 </td>
   <td style="text-align:left;"> $MCD So ya&amp;#39;ll following $AAPL into the crypto game today? I see a letter that I didn&amp;#39;t notice in the drivers seat. It&amp;#39;s either an E, or a C... 👀 #Conspiracy $BTC.X $DOGE.X $SHIB.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 23:56:32 </td>
   <td style="text-align:left;"> $AAPL  apple 4% tomorrow at one point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 23:26:55 </td>
   <td style="text-align:left;"> $SPY $AMZN $AAPL historically the US markets are ‘Patriotic’ during War… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 23:22:46 </td>
   <td style="text-align:left;"> $SPY Market in Bear Market 
$AAPL $QQQ $AMD 
Here are some clues that we are in a 
Bear Market :
Lower highs and lower lows
Negative divergence on oscillators 
RSI 14 and CCI 
Russell 2000 $IWM has underperformed the Market and is Negative compared to Mkt  Russell 2000 should be higher than the market during a healthy Bull market👀
Metals and also Energy are running hot that usually happens at Market 🔝 
and financials usually should be weaker 
 Currently Financials are being manipulated just to make some noise 👀😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 23:21:33 </td>
   <td style="text-align:left;"> NEW POST: Weekend Overview and Analysis 02/13/22 {Video} https://marketchess.com/2022/02/13/weekend-overview-analysis-02-13-22-video $AAPL $IWM $NVDA $QQQ $SPY #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 22:41:22 </td>
   <td style="text-align:left;"> Wars/conflicts generally don&amp;#39;t impact markets for very long and to any significant degree. 

Recent conflicts between Russia/Ukrain/Crimea/Turkey have found almost no market impact on average. 

$SPY $VIX $$AAPL $SBUX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 22:39:17 </td>
   <td style="text-align:left;"> $AAPL Wave 5 + eSIX  ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 22:39:15 </td>
   <td style="text-align:left;"> They keep telling me the consumer is tapped and with sour sentiment, but...

My C&amp;amp;C Stock Market Factory says otherwise.

Costco sales accelerating and Cass Freight at record levels. Lots of stuff getting shipped, lots of stuff getting bought off the shelves.  1/2

$SPY $QQQ $UVXY $AAPL $COST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 22:36:00 </td>
   <td style="text-align:left;"> Do you agree with the A.I. prediction? $AAPL in Uptrend: price may ascend as a result of having broken its lower Bollinger Band on January 19, 2022. View odds for this and other indicators: https://srnk.us/go/3410511 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 22:24:20 </td>
   <td style="text-align:left;"> $AAPL Apple Boosts Retail Worker Pay to Cope With Tighter Labor Market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 22:22:56 </td>
   <td style="text-align:left;"> $AAPL Apple is expanding its retail operations, betting that a combination of strategies developed before and during COVID-19 will make its stores more popular than ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 22:09:05 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-13 Trade Analysis Video: 
https://www.youtube.com/watch?v=AS8F5hrWtr4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 22:07:38 </td>
   <td style="text-align:left;"> $LCID it’s time for $AAPL to pull the trigger. Too cheap at this level </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 22:03:44 </td>
   <td style="text-align:left;"> $AAPL  $QQQ $DJIA 

This will prove to be an excellent buying opportunity. 

https://www.rferl.org/amp/ukraine-olympic-athlete-no-war/31699461.html

Peace on earth will prevail, these are just exercises but there will not be war this year  that’s my prediction. Stocks rip higher next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 21:10:58 </td>
   <td style="text-align:left;"> $AAPL 177 pt gap up on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 21:08:33 </td>
   <td style="text-align:left;"> SoftBank May Take Its Big British Tech Stock to Nasdaq. It Might Be Better to Stay Local.  $AAPL $UBER $NVDA 

https://newsfilter.io/a/d07e834a9fc216a8777bda9a03c8bbe3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 21:04:33 </td>
   <td style="text-align:left;"> $AAPL Your Remote Work Setup Needs a Portable Monitor 

https://newsfilter.io/a/7bf563cd9b051f211e4b396bf7af6e49 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 21:04:32 </td>
   <td style="text-align:left;"> $AAPL How One of the World’s Biggest Carbon Emitters Got a Factory to Zero Emissions6 min read 

https://newsfilter.io/a/fba32a98b810e50f5c62f3fe358f02cc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 20:51:41 </td>
   <td style="text-align:left;"> $SPY $AAPL FANG death cross inbound. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 20:45:28 </td>
   <td style="text-align:left;"> $BTC.X $SPY $AAPL $TSLA $NVDA 
BULLARD who called for 100 basis- points hike should be sent on vacation for couple of weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 20:40:03 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 6.11%. $AAPL outperforms 94% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 20:00:11 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 19:40:06 </td>
   <td style="text-align:left;"> $SPY $FB $AAPL $TSLA $AMZN Folks a small question, what do they mean ? to buy PUT options, or PUT in ? And thanks ahead for the answers... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 19:23:30 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL $AMZN $LMT 
Say NO to the war and drop a news saying “ Diplomatic path achieved and no war” ; LMT GOLD OIL down and tech goes up. 
And we gonna have to sell the belongings soon to pump Fuel soon if oil doesn’t come down soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 19:18:47 </td>
   <td style="text-align:left;"> $AAPL https://9to5mac.com/2022/02/11/airtag-safety-vs-tile/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 19:04:08 </td>
   <td style="text-align:left;"> $AAPL $btc.x is above 42.. should be fine for equities going in? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 19:00:22 </td>
   <td style="text-align:left;"> $AAPL Stunning Concept Imagines a Foldable iPhone With a Clamshell Design and Chrome Hinges – Video
Sat Feb 12 10:18:09 EST 2022
https://youtu.be/RazwXWq7V6w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 18:56:00 </td>
   <td style="text-align:left;"> $BTC.X $AAPL $SAND.X $FB $MANA.X 

         Go JOE! Superbowl 56 🏟 🇺🇸 🏈

And the SNOOP! Rock the Meta House💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 18:49:05 </td>
   <td style="text-align:left;"> $BTC.X $MSFT $VLX.X $BRISE.X $AAPL 
ACCUMULATE during the lean times or finally get on board. Crypto has to be a serious component to your portfolio. Adoption is undeniably growing globally. This revolutionary innovative crypto &amp;amp; blockchain Industry is thriving and investment is arriving daily. 

Or simply pull up a chair and live with regret </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 18:48:19 </td>
   <td style="text-align:left;"> $SPY so looks like this step up Wag the Dog  https://www.google.com/amp/s/www.reviewjournal.com/opinion/letters/letter-joe-bidens-wag-the-dog-2521677/amp/  is to keep news headlines from showing Clinton hiring tech people to get into Trump tower.  https://www.google.com/amp/s/nypost.com/2022/02/13/hillary-clinton-campaign-paid-tech-workers-to-dig-up-donald-trump-russia-connections/amp/  maybe. Might be something else. $TWTR $SNAP $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 18:37:28 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $TSLA 
Russia TV live says its all “Western Hysteria” and fake news/Propaganda campaign by the west. 
White house said It starts Wednesday with Aerial Bombing. I grew up in war and Rarely the Enemy gives appointments and bomb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 18:29:03 </td>
   <td style="text-align:left;"> Bullish portfolio proposal: Apple( $AAPL ), Citrix… https://www.macroaxis.com/invest/stock-volatility?s=AAPL,CTXS,S,CHK,MDLZ,JCI,GD,CMCSA,SLB #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:55:51 </td>
   <td style="text-align:left;"> $SPY $NVDA $AAPL $AMZN $TSLA ..

 

https://www.rt.com/russia/549149-anglo-saxon-propaganda-brigade/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:54:40 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $TSLA 

https://www.rt.com/russia/549175-putin-biden-phone-talks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:50:12 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 2/10 update presented to members at  http://elliottwave-forecast.com #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:47:46 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 2/01 update. Showing further reaction higher taking place from the blue box area #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:34:30 </td>
   <td style="text-align:left;"> $AAPL How One of the World’s Biggest Carbon Emitters Got a Factory to Zero Emissions 

https://newsfilter.io/a/90ecda350252d8d4daa580d528264654 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:32:27 </td>
   <td style="text-align:left;"> Roomba Maker Needs to Suck Up More Chips3 min read  $AAPL $SONO $GPRO 

https://newsfilter.io/a/095d50b2e455c78062e25b493d5a79d9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:29:03 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 1/30 weekend update. Found buyers at the blue box area &amp;amp; showing reaction higher taking place from the blue box area. Longs should be risk free by now #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:23:39 </td>
   <td style="text-align:left;"> $AAPL then managed to reach the blue box area from where buyers were expected to appear  #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:18:59 </td>
   <td style="text-align:left;"> $AAPL 1hr view from 1/23 Weekend update. Calling for more downside to take place #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:13:15 </td>
   <td style="text-align:left;"> $AAPL 1hr view from 1/14 Pre-Market update presented to members at http://elliottwave-forecast.com #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 17:09:05 </td>
   <td style="text-align:left;"> $AAPL Chart of The Day 1/12/2022 update. #Apple can see further downside https://elliottwave-forecast.com/stock-market/elliott-wave-view-apple/…  #Elliottwave #Trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 15:33:04 </td>
   <td style="text-align:left;"> $AAPL fell below 171 I’m short here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 15:14:26 </td>
   <td style="text-align:left;"> $AAPL $AMZN $M WHOZ READY FOR FOURTH VACCINE. This time it’s a cocktail vaccine. Pfizer and Moderna together. Yummy. 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 15:09:50 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT  $QQQ happy heart’s day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 14:00:18 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 13:55:00 </td>
   <td style="text-align:left;"> $AAPL has only a medium technical rating, but it does show a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 13:53:44 </td>
   <td style="text-align:left;"> TRADE IDEA ⚔️ #PRESSIT 
TICKER 📈 $AAPL  
🚨SHORT SIDE ONLY NO TRIGGER NO TRADE  
SHORT TRIGGER 🔫 168.05 
SHORT PT🎯 162.84 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 13:48:42 </td>
   <td style="text-align:left;"> $UVXY $SPY $IWM $AAPL $MSFT - 2008 Chart (Red) vs 2022 Chart (Blue). Movements are so close. Looks like it’s a huge fall down next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 13:10:10 </td>
   <td style="text-align:left;"> $UVXY $AAPL $MSFT $AMZN $SPY - Even Goldman comes to reality. Get ready for Black Monday or at least a bloody red week next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 13:03:46 </td>
   <td style="text-align:left;"> $AAPL the 3 crucial informations he gave us : 
 
1) Covid-19 is a man made virus ; 
 
2) The current treatments are not vaccines, They Are Poisons ; 
 
3) Variants are a production and result from the vaccination. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 12:47:56 </td>
   <td style="text-align:left;"> $SPY Bloody Valentines Day likely 2/14
My Bloody Valentine for Red Market may occur Monday because of What Happened on Friday 2/11/2022
Technically Market is breaking down and from negative fundamentals from 10 year over 2% to lower Economic Growth Bad Consumer Sentiment Number 

And possibly Russia invasion of Ukraine 
$AMD $QQQ $AAPL 

https://m.imdb.com/title/tt1179891/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 11:32:06 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-13 Trade Analysis Video: 
https://www.youtube.com/watch?v=AS8F5hrWtr4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 11:29:43 </td>
   <td style="text-align:left;"> $SPY  &amp;amp; again, Mr B sticks w/ the facts &amp;amp; breaks it down. 
Not sure who sold their Tech ($amzn $aapl $msft $baba) stocks on Friday but why? 
 
Take away the emotional reactions &amp;amp; listen to the GOAT, money has to go somewhere it will make more money so,.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 11:28:23 </td>
   <td style="text-align:left;"> $RIDE 
Remember when $AAPL  did this during the Super Bowl?
https://youtu.be/VtvjbmoDx-I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 11:24:02 </td>
   <td style="text-align:left;"> $SPY Anyone going? 
I think  you take the cash &amp;amp; buy $aapl $baba $amzn stock &amp;amp; watch the game at home 
 
A few ETF&amp;#39;s too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 11:01:27 </td>
   <td style="text-align:left;"> $AAPL 
So, the moderator over at $AMC is a sore loser liberal... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 11:00:18 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:40:21 </td>
   <td style="text-align:left;"> $UPST $AAPL $AFRM $MARA 

IM GONNA FLUSH THIS TURD JUST LIKE 
🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸
HOW TRUMP FLUSHED CLASSIFIED 
🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸
DOCUMENTS....🚽💩🚽💩🚽💩🚽💩 
🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:33:33 </td>
   <td style="text-align:left;"> Balance Sheet vs. Cash Flow Statement: What’s the Difference? $AAPL $TSLA $AMZN $PYPL https://www.billionaireclubcollc.com/balance-sheet-vs-cash-flow-statement-whats-the-difference/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:31:17 </td>
   <td style="text-align:left;"> Its Business Model and Competition $SQ $PYPL $AFRM $AAPL https://www.billionaireclubcollc.com/its-business-model-and-competition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:23:46 </td>
   <td style="text-align:left;"> What Is the Weighted Average of Outstanding Shares? How Is It Calculated?  $AFRM $GOOGLE $AMZN $AAPL $TSLA https://www.billionaireclubcollc.com/what-is-the-weighted-average-of-outstanding-shares-how-is-it-calculated/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:20:04 </td>
   <td style="text-align:left;"> 5 Tips for Diversifying Your Portfolio $SPY $QQQ $DJIA $TSLA $AAPL https://www.billionaireclubcollc.com/5-tips-for-diversifying-your-portfolio/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:18:52 </td>
   <td style="text-align:left;"> $NFLX $AAPL   tinyurl.com/43f4ncvr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:14:57 </td>
   <td style="text-align:left;"> $WIMI  $AAPL ✊The Tickeron SMR rating for WIMI is 7 (best 1 - 100 worst), indicating very strong sales and a profitable business model. 💥💥💥SMR (Sales, Margin, Return on Equity) rating is based on comparative analysis of weighted Sales, Income Margin and Return on Equity values compared against S&amp;amp;P 500 index constituents.🔥🔥 The weighted SMR value is a proprietary formula developed by Tickeron and represents an overall profitability measure for a stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:10:33 </td>
   <td style="text-align:left;"> $PSTH $AAPL  $SQ  Sounds like Apple is ready to take on Stripe and Square. 
 
https://www.inc.com/jason-aten/apple-just-quietly-introduced-a-feature-to-your-iphone-that-is-going-to-upend-this-17-trillion-industry.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:08:09 </td>
   <td style="text-align:left;"> $AABB $BRK.A $AAPL $MSFT $TSLA The overall market will have some pull backs and many investors will jump in some OTC stocks if they know what their doing. $AABB at .10 cents has 100M+ in assets/Record Profits/Record Gold/ No Debt/Gold producing mines/Brand New Global Exchange/213 trading pairs/Featuring AABBG.X Gold backed cryptocurrency coin (mine to token) The FIRST TO MARKET Global Gold currency system/Recent corporate PR stated plans on UP LISTING on a MAJOR EXCHANGE!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 10:03:12 </td>
   <td style="text-align:left;"> What Is Stock Volume? How to Improve Your Trading $AMZN $AAPL $AFRM $SPY $VIX https://www.billionaireclubcollc.com/what-is-stock-volume-how-to-improve-your-trading/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:58:15 </td>
   <td style="text-align:left;"> 5 Tax Breaks Overlooked By Small Business $LCID $AAPL $AMZN $TSLA $Owners https://www.billionaireclubcollc.com/5-tax-breaks-overlooked-by-small-business-owners/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:51:02 </td>
   <td style="text-align:left;"> $AAPL where is the bottom? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:42:24 </td>
   <td style="text-align:left;"> $BKKT   You may or may not play a lot of chess, but I do, and it&amp;#39;s checkmate now. 
 
1. Price held strong after 80%+ run up (new buyers in for long haul) 
2. 14m shares sold short &amp;amp; must buy eventually (they are so fucked!)  
3. 7.5%+ inflation encourages $ billions to try bitcoin &amp;amp; crypto   
4. Putin war = temporary downs then big moves into bitcoin/crypto 
5. So few startups with AMAZING growth trajectories (go Bakkt!) 
6. I haven&amp;#39;t even touched upon a possible $AAPL announcement, ICE possibly increasing stake, skyrocketing revenues, etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:41:08 </td>
   <td style="text-align:left;"> $AAPL $DWAC 
If your a Fox News watcher or a Republican don’t complain about high gas prices or inflation. Both of those outlets have one and only policy: supporting anarchism all over the world. 
They don’t care about you. Actually you are behind the last thing they care on their list. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:40:08 </td>
   <td style="text-align:left;"> Understanding Different Mortgage Rates $AAPL $LC $RCKT $AMZN $TSLA https://www.billionaireclubcollc.com/understanding-different-mortgage-rates/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:37:42 </td>
   <td style="text-align:left;"> Top 3 Stocks for Novice Swing Traders $FB $MSFT $AAPL https://www.billionaireclubcollc.com/top-3-stocks-for-novice-swing-traders/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:28:31 </td>
   <td style="text-align:left;"> $AAPL  $175.00 Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:28:09 </td>
   <td style="text-align:left;"> $AAPL putin is clear he won’t go offensive
Expect surge on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:22:22 </td>
   <td style="text-align:left;"> How Much Do I Need to Retire? $TSLA $AAPL $AMZN $LCID https://www.billionaireclubcollc.com/how-much-do-i-need-to-retire/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:21:12 </td>
   <td style="text-align:left;"> $AMD $nvda  $intc  $TSLA  $aapl 
 
Yahoo spreads FUD news   https://finance.yahoo.com/video/russia-ukraine-conflict-could-affect-210757760.html 
 
 
80% Platinum is mined in Africa!! Google it!! So, calm down!! 
For the record = The majority (about 80 percent) of platinum is mined in South Africa. Approximately 10 percent is mined in Russia, and the rest is found in North and South America, according to the U.S. Geological Survey. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:17:17 </td>
   <td style="text-align:left;"> $AAPL TA Stats Today&amp;#39;s Change 29% + 🚀 https://t8sk.com/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:16:57 </td>
   <td style="text-align:left;"> SweepCast observed: $AAPL with Unusual Options Activity Alerted on $230 PUT Expiring: 01-20-2023 worth 60K🐻  Check out Premium Room or SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:13:38 </td>
   <td style="text-align:left;"> $XLE / $AAPL This should get interesting 🍿 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:06:59 </td>
   <td style="text-align:left;"> $SPY  What a fraud! 😆 Violent and treacherous rally in February he said 🤡 - TSLA $AFRM $AAPL $PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:05:48 </td>
   <td style="text-align:left;"> Chatbot Definition $AAPL $TWTR $SNAP https://www.billionaireclubcollc.com/chatbot-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:03:10 </td>
   <td style="text-align:left;"> Building An Effective Watchlist $AAPL $AMZN $TSLA https://www.billionaireclubcollc.com/building-an-effective-watchlist/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:02:43 </td>
   <td style="text-align:left;"> $ME Anyone have thoughts on the CEO&amp;#39;s comment in regards to integrating their data with wearables? Given $AAPL sig push towards targeted individual health metrics in past years, seems like a natural fit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 09:00:25 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 08:51:00 </td>
   <td style="text-align:left;"> The industry average ROE is 22.20%. $AAPL outperforms 94% of its industry peers. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 08:44:19 </td>
   <td style="text-align:left;"> $psy So lets talk about timing &amp;amp; why when people say you should jump out of things like $aapl &amp;amp; get back in its a losing game 
 
Take @BullBearPig, hes a great example. He trolls people who Buy &amp;amp; Hold, he did it to the $tsla Longs when he sold at the lows &amp;amp; it went to $1300 but what has to be the single best trade on ST is his BTC play 
 
He sold &amp;amp; went short in 2017 when it  dropped from $1800 &amp;amp; went to  $1300 because why would anyone want to hold for longer than a year? that would be stupid, right? 
 
Now whatever you do do not clip &amp;amp; post his post, for some reason he hates when people see this &amp;amp; gets triggered. I never understand why trolls get mad when they get a taste of their own medicine, must be hard  
 
$coin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 08:43:11 </td>
   <td style="text-align:left;"> $AAPL $160 by Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 08:43:03 </td>
   <td style="text-align:left;"> $AAPL - Volatility alert: Apple options pin risk is increasing https://www.macroaxis.com/stock-options/AAPL/Apple-Inc?utm_source=dlvr.it&amp;amp;utm_medium=stocktwits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 08:24:49 </td>
   <td style="text-align:left;"> $AAPL Howie Felthersnatch! Coming for ya </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 08:16:31 </td>
   <td style="text-align:left;"> $SPY $AAPL emergency meeting on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 08:14:22 </td>
   <td style="text-align:left;"> Buy-Side vs. Sell-Side Analysts: What’s the Difference? $SPY $TSLA $AAPL $AMZN $BTC.X https://www.billionaireclubcollc.com/buy-side-vs-sell-side-analysts-whats-the-difference/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 08:08:14 </td>
   <td style="text-align:left;"> $AAPL imagine Apple has a commercial on either headset or possible EV vehicle type TV Ad tomorrow, slim chance , but a wish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 08:04:21 </td>
   <td style="text-align:left;"> How To Get the Most Money Back on Your Tax Return $AAPL latexfba4c4d55816750d657800a04863c41aAMD - 71% call flow 
$NVDA - 51% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 07:55:41 </td>
   <td style="text-align:left;"> $AAPL IF Ukraine invasion happens this going to 80 

KNOW THIS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 07:42:52 </td>
   <td style="text-align:left;"> $AAPL is about to give $PYPL and $SQ a run for their bottom line. $$200++++++++ https://www.inc.com/jason-aten/apple-just-quietly-introduced-a-feature-to-your-iphone-that-is-going-to-upend-this-17-trillion-industry.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 07:18:01 </td>
   <td style="text-align:left;"> $AAPL 200 by July 100% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 07:14:51 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $AAPL is the #1 stock that institutions traded this week with 288.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 07:02:08 </td>
   <td style="text-align:left;"> $AAPL Does anyone noticed that after the 7.5 CPI the 10y bonds yield dropped 13 points?
All the inflationary talk and this result. The expectations of some market participants were probably for 8% 😃 
In other words, imo the inflationary pressures are going to subside soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 07:01:46 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 06:35:59 </td>
   <td style="text-align:left;"> $AAPL $TSLA $NVDA https://www.yankodesign.com/2022/02/11/not-another-apple-car-concept-this-norwegian-ev-comes-with-a-620-mile-range-rivaling-your-tesla/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 06:31:13 </td>
   <td style="text-align:left;"> $AAPL…they just keep knocking it out of the park..$200++ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 06:22:45 </td>
   <td style="text-align:left;"> $AAPL $NVDA $FB $COST Pentagon orders departure of U.S. troops in Ukraine as Russia crisis escalates https://www.cnbc.com/2022/02/12/pentagon-orders-departure-of-us-troops-in-ukraine.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 06:13:04 </td>
   <td style="text-align:left;"> $SPY from the other side.  Not wag the dog.  $AAPL $FB $GOOGL  https://www.themoscowtimes.com/2022/02/12/klm-suspends-flights-to-ukraine-airline-2-a76361 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 06:11:01 </td>
   <td style="text-align:left;"> $AAPL https://appleinsider.com/articles/22/02/12/apple-watch-detects-symptom-of-thyroid-issue-months-ahead-of-diagnosis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 06:07:58 </td>
   <td style="text-align:left;"> $AAPL now need to fight tis 50ema spot https://youtu.be/EhOlbT0Kz8A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 06:07:28 </td>
   <td style="text-align:left;"> Growth Stocks vs Value Stocks  $TSLA $AMZN $AAPL https://www.billionaireclubcollc.com/growth-stocks-vs-value-stocks-2/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:56:03 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $AMZN oh man now they give Putin a deadline..16 february...if you dont invade your a pussy😂😂Biden is the real BadGuy...is playing dirty...its all about selling guns to ukraine.Stay calm and buy the dip...probably on wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:54:04 </td>
   <td style="text-align:left;"> $AAPL will likely be the last to fall here - has been strong relative to peers but now big risk as has yet to fill in the air gap down to the 50/100wk MA cluster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:45:51 </td>
   <td style="text-align:left;"> $AAPL Biden is tail wagging the dog with Russia. Takes people’s mind off inflation, Southern boarder, mask and vaccine mandates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:44:19 </td>
   <td style="text-align:left;"> $AAPL $AMZN $XOM $TSLA I bet Putin is shitting in his pants 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣
Hope Biden doesn’t flinch and hit the “LAUNCH NUKE “ button lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:19:04 </td>
   <td style="text-align:left;"> $AAPL will there be a war? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:15:30 </td>
   <td style="text-align:left;"> $XOM $AAPL $TSLA $AMZN 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣 and 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣can’t stop 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣😜🤣😜😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:14:36 </td>
   <td style="text-align:left;"> $AAPL Look at this!  8 Trades executed, trade Profitability of  87% and Profit Factor of  6.  15 minute chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:11:33 </td>
   <td style="text-align:left;"> 7 ways small-business owners can save on taxes in 2022 $TSLA $AAPL $AMZN https://www.billionaireclubcollc.com/7-ways-small-business-owners-can-save-on-taxes-in-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:05:12 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

PIGS GET SLAUGHTERED 🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 05:03:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

BULLS SPREAD THE MOST SHIT OUT OF 

ANYONE THAT’S WHY IT’S CALLED 

BULL~SH*T.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:52:35 </td>
   <td style="text-align:left;"> $AAPL one of the best campaign ads they did back in the days

https://youtu.be/5sMBhDv4sik </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:51:11 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

rawr 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:50:43 </td>
   <td style="text-align:left;"> $SPY Jeremy Grantham warns ‘super bubble’ will soon pop, tanking stocks 50 percent 
Yes his opinion and we shall see....
$AMD $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:49:19 </td>
   <td style="text-align:left;"> What is a Stock Split? – Everything You Need to Know $GOOGLE $NVDA $TTD $AAPL $TSLA https://www.billionaireclubcollc.com/what-is-a-stock-split-everything-you-need-to-know/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:31:30 </td>
   <td style="text-align:left;"> $SPY Jeremy Grantham-Bloomberg 
Front-Row MKt Super Bubble 👀

$QQQ $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:30:14 </td>
   <td style="text-align:left;"> $AAPL sold at 173.00 maybe we will see $159 again that seems to be the support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:22:43 </td>
   <td style="text-align:left;"> How do you think the market will react to this? $AAPL in Uptrend: price expected to rise as it breaks its lower Bollinger Band on January 19, 2022. View odds for this and other indicators: https://srnk.us/go/3408549 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:21:45 </td>
   <td style="text-align:left;"> $AABB $AMZN $MSFT $AAPL $GOOGL $AABB Gold mines/Global Exchange/First to market global gold currency system. LOAD the undervalued,oversold,mega visionary stock looking to up list to a Major Exchange. Accumulate NOW!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:18:38 </td>
   <td style="text-align:left;"> $AAPL  Out of the 372 other times AAPL was down 2.3% during a trading day, 53% of the time it traded higher by the next day&amp;#39;s market close. #CoinFlip link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:06:19 </td>
   <td style="text-align:left;"> $MSFT If u look at the year opens MSFT outperforms $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 04:03:24 </td>
   <td style="text-align:left;"> $AAPL $SPY sound like this Russian bull crap is just western propaganda , fake war, fake tension, all for political agenda. My Russian friends saying it’s not bad as what USA claim. So stop it, but it’s working , it’s making idiots selling 🤣.. sell sell.. we buy lower ..  love the dip. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:58:00 </td>
   <td style="text-align:left;"> $SPY See you BULLS MONDAY! YIKES 😬  
 
(RUSSIAN BEAR PATTERN) - $TSLA $AAPL $AFRM $FB = Tech not a safe haven either!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:49:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:45:19 </td>
   <td style="text-align:left;"> $AAPL 

How can one not like this chart❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:44:04 </td>
   <td style="text-align:left;"> The biggest single day market cap gains in US stock market history

1 Amazon $AMZN
2 Apple $AAPL
3 Microsoft $MSFT
4 Tesla $TSLA
5 Google $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:43:40 </td>
   <td style="text-align:left;"> $AAPL $MSFT $NVDA $AMD I’d welcome a good old-fashioned nuclear war. Humanity needs a wake up call—it seems we get stupider by the year. Right now we are focused on transgender men competing in women’s sports, speculating on stupid-looking NFT ape jpegs, morons on Facebook spreading conspiracy theories, social media and the culture of shilling products…endless list of ills </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:39:18 </td>
   <td style="text-align:left;"> $AMC $SPX $AAPL All that you need to know... Shorts haven&amp;#39;t covered a single share;------------ Check it out below 👇 
 
highly recommend everyone to follow them 🚀 livetrading99.a0001.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:38:09 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $AMZN 
On BBC news; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:37:32 </td>
   <td style="text-align:left;"> $AAPL need a good nuclear war to get humanity back on the right path. Right now we are focused on transgenders competing in women’s sports, stupid-looking NFT jpegs going for hundreds of thousands or millions, the masked vs. maskless, giving criminals more rights than victims, retards on Facebook spreading conspiracy theories…we need a good cleansing anyway </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:33:34 </td>
   <td style="text-align:left;"> $AMD $TSLA $NVDA $AAPL  if bullsh1t is gonna happen it wont last long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:30:27 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY  fake ass war . 😂 .. let see some nukes and laser , I wanna see see who can display military technology, we have invisible soldier yet? How  about robot doggy ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:27:30 </td>
   <td style="text-align:left;"> $AAPL anyone have any dealings with @Hiwojima very angry little elf. It’s kind of funny. Just swears at you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:21:44 </td>
   <td style="text-align:left;"> $UVXY $AAPL $IWM $SPY $MSFT - Goodness... looks like the idiots are going through with it. Look at Gold, huge jump. It looks like we will have a black Monday at this rate, specially if gold is jumping this high. $2000 by March and drop 10% in equities? Easy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:15:36 </td>
   <td style="text-align:left;"> $AAPL A serious threat to payment processing companies. Money maker feature with high dominance. Love apple!
https://www.inc.com/jason-aten/apple-just-quietly-introduced-a-feature-to-your-iphone-that-is-going-to-upend-this-17-trillion-industry.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:14:59 </td>
   <td style="text-align:left;"> $SPY Over Under SPY 430 for Friday 4/18/2022
Yes or No  Bets 🐻🐂
$AMD $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:07:33 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:03:07 </td>
   <td style="text-align:left;"> $AAPL - BTDhttps://share.trendspider.com/chart/AAPL/7123k7hcbw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 03:02:12 </td>
   <td style="text-align:left;"> $spy I wonder if $twtr should have to put back up Trumps tweets as they are a matter of public record, its just so much fun to look back at them now &amp;amp; laugh. Remember all the things he said to Boycott &amp;amp; how he threatened to take down so many things like $aapl &amp;amp; nke? 
 
$aapl was $27 (price adj) &amp;amp; nke was $40 &amp;amp; lets not get started on $amzn, Bezo&amp;#39;s laughed in his face then 😊 
 
Trump has always been bad at Markets so I guess we know where $dwac will be in a few months since hes behind it, same place as his casino </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 02:49:06 </td>
   <td style="text-align:left;"> $XOM $AAPL $TSLA $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 02:42:37 </td>
   <td style="text-align:left;"> $XOM I bet Putin pissed his pants after Biden warned him of severe consequences.

He pissed his pants from laughing so hard 🤣🤣🤣🤣
$AAPL $TSLA $AMZN $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 02:26:39 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $AAPL is the #1 ticker with sweep activity that institutions traded urgently this week options with 234.0K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 02:22:29 </td>
   <td style="text-align:left;"> $AC-CA $UAL $AAPL 
Take air Canada and come smoke some good legal weed here :) we also have a trucker party and if you feel alone , it’s easy to meet someone at the hospital ...they are all full ! . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 02:19:49 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT Hello friends, I am a super pro chart expert and after studying this chart for nights and days I can 100% confirm we have reached the bottom and from this point onward we will enter a bull market which will end at the year 3567. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 02:18:06 </td>
   <td style="text-align:left;"> $QQQ $AAPL Democrats when no war happens be like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 02:16:53 </td>
   <td style="text-align:left;"> $SPY $qqq $aapl not a fan of Putin .. he is criminal
But what if Russia sets ups bases in Mexico what USA would do .. USA should focus on economy , inflation and assure Ukraine won’t be part of NATO .. Biden is moron </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 02:02:52 </td>
   <td style="text-align:left;"> $SPY $TQQQ $AAPL $UBER $SOXL 
😴 Sleepy Joe just bluffing to get media attention. 
90% chance there will be no war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 02:01:05 </td>
   <td style="text-align:left;"> $AAPL ima buy me a pound of that master P and ima roll me a lil Romeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:59:46 </td>
   <td style="text-align:left;"> $GOOG $AAPL $NVDA  
 
Google&amp;#39;s stock split is perfect for investors 
 
https://utradea.com/blog/Googles-stock-split-is-perfect-for-investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:59:02 </td>
   <td style="text-align:left;"> $SPY If you&amp;#39;re a Trader you use the Headlines to make moves but you know its all BS, if you&amp;#39;re an Investor you look for Market drops based on Headlines to BTD, but who would believe what these people say? Its not even a question 
 
The US is just playing w/ Putin to get a reaction. If the news reports that &amp;quot;Sources say Tim Cook is leaving $aapl on Sat&amp;quot; the stocks moves &amp;amp; then he doesn&amp;#39;t it moves back up, If on a Sunday Bloomberg reports &amp;quot;Sources say $SFTBY may sell their $baba shares&amp;quot; the stock drops 6% becuase people react &amp;amp; then a day later  Softbank says its bs then what? If you didn&amp;#39;t buy you missed a great sale. 
 
Stop thinking what you hear from the media is real, its all a game we play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:49:18 </td>
   <td style="text-align:left;"> $DIS $AAPL $MSFT Mr market continues to do his best to pretend he didn’t see blowout earnings and pretend like these companies have no pricing power in inflation. Annoying but what can you do - you are presented with an excellent opportunity to accumulate these companies at highway robbery prices. I’ll be continuing to shovel money into these positions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:47:06 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/Wo5rroMoquE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:46:34 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL Happy Saturday everyone! hopefully you&amp;#39;re taking some time off to enjoy the weekend. I like to use this time to step back, reset, and prepare for the week ahead (DD, news, rumors, etc.) 
 
One of the most important things to track is social momentum and social sentiment. When a ticker starts to gain traction, more people see it , and it can start to take off. When this happens it usually leads to increased price action and volume. Remember, at the end of the day the market is set by whatever price some is will to buy and sell at.  
 
This is why we build this social sentiment dashboard, so you can stay ahead of the trends an movements. It is one of the most useful indicators for investing and trading. Check it out - happy to answer any questions. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_202202012 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:43:13 </td>
   <td style="text-align:left;"> $SPY Mr B is wealthy because he knows how to play the game. 
The Market did not sell off because of the Russia news or even the Bullard news, Markets always go up or down based on how most people are feeling, they will then use the news for an excuse why. 
 
Why you been around long enough you see how things play, w/ a Market that goes up over 87% of the time is it really that hard? 
 
So yes $aapl $amzn &amp;amp; $msft will be bought again so,.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:37:26 </td>
   <td style="text-align:left;"> $AAPL  If war breakout Europe goes back to the dark ages. People in Europe won’t even afford to charge an iphone anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:36:41 </td>
   <td style="text-align:left;"> $tsla $googl $amzn $aapl https://www.youtube.com/watch?v=CI93IWCx9XQ&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:32:17 </td>
   <td style="text-align:left;"> $AAPL Bieden admin creating fearmongering to divert attention from inflation driven policies. What better way than to promote war where u lose nothing and gain everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:27:05 </td>
   <td style="text-align:left;"> $spy The most important thing for any Trader is to never make rash decisions, always do your homework the night before &amp;amp; have your plan set &amp;amp; ready to go so you are prepared. 
 
Create &amp;amp; follow rules that will help you in this fast paced Algo driven world. I put in bids for the Tech I wanted the night before &amp;amp; when we Opened &amp;amp; the Market was running I thought about if I needed to up the Bids, I stuck to my rules &amp;amp; didn&amp;#39;t, let the bids stand &amp;amp; left the office. 
They all were hit. 
 
Markets can fool you fast so again, do the work when you&amp;#39;re not in the middle of the storm 
 
$aapl $baba $bb $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:21:49 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:16:57 </td>
   <td style="text-align:left;"> $AAPL How much we&amp;#39;re down since January 2, 2022. 
 
https://twitter.com/MeisaBonelli/status/1492546795968286723?s=20&amp;amp;t=Jd5NM60068k0Xt1aVCwWjw 
 
$PYPL $NVDA $F $GM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 01:15:26 </td>
   <td style="text-align:left;"> $LCID stupid us,uk… politicians… they are fuc** this World..
$RIVN  $NIO $TSLA $AAPL 

https://twitter.com/carlaglow1/status/1492547298466971651?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 00:59:04 </td>
   <td style="text-align:left;"> $TSLA $spy $aapl $btc.x Do not give Nobel peace price based on Russia Ukraine fake war.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 00:58:52 </td>
   <td style="text-align:left;"> $AAPL  When Putin decides to kiss and make up we’ll be back. Maybe not an ATH… but back. Keep the faith. Monday might be a game changer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 00:49:40 </td>
   <td style="text-align:left;"> $AAPL how low will it go? Red? White? Blue? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 00:33:27 </td>
   <td style="text-align:left;"> $TSLA $AAPL It Won&amp;#39;t Be The Same Tesla In The Future: Elon Musk And Others Weigh In 

https://newsfilter.io/a/fc7bb3b820ca137bb6dc5773d3ecc0be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-13 00:25:13 </td>
   <td style="text-align:left;"> latexa40885bc381003fa96095d696f203d25AMZN 
$QCOM 
DoD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 23:50:31 </td>
   <td style="text-align:left;"> $AAPL  with all the bad things going on during the Sleepy Joe administration, just remember , Follow the money.   Sleepy is possibly a member of a drug cartel, he and son maybe part of the Russian mafia, he and son could be members of the Chinese Communist party,  trying to be butt buddies with the leader of Iran, and last but not least , is pissed off at the American military for not telling him they were pulling out of Afganistan, so he said to Lester Holt the other night On TV.  
Supposedly, his ratings are 38.9 % as of last week.  WHO in their right mind would still back this idiot  ?   
Let’s go Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 23:39:48 </td>
   <td style="text-align:left;"> $AAPL I will love you until China doesn&amp;#39;t love you anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 23:35:47 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 23:31:39 </td>
   <td style="text-align:left;"> $AAPL 
BONDS YIELDS 10 YEARS 
1.918% FROM 2.05%. Yesterday’s. 
Going DOWN. 
BIG GREEN NEXT TRADING.-🍏🆙🔜🔝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 23:25:21 </td>
   <td style="text-align:left;"> $AAPL 

BIG GREEN NEXT TRADING. 
Fed officials push back on Bullard’s rate-hike warnings. 

https://www.cnbc.com/video/2022/02/11/fed-officials-push-back-on-bullards-rate-hike-warnings.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 23:17:26 </td>
   <td style="text-align:left;"> $AAPL Why Is Apple Hiking Pay For Its Retail Store Employees? 

https://newsfilter.io/a/32268621d21e44dc739e5aff00318612 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 23:06:18 </td>
   <td style="text-align:left;"> $AAPL can you all said $145 with me 😭😭😭 it’s 🔥 🥵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:55:41 </td>
   <td style="text-align:left;"> $AAPL looking for 157-159 by EOM. May bounce early next week but then down.  
 
#AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:53:58 </td>
   <td style="text-align:left;"> $GME I posted a few charts and commentary... 
 
https://twitter.com/MeisaBonelli 
 
$AMC $PTON $DWAC $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:47:22 </td>
   <td style="text-align:left;"> $AAPL a whole 1.42 in dividend holy moly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:46:00 </td>
   <td style="text-align:left;"> $AAPL: The Revenue has grown by 28.62% in the past year. This is a very strong growth!. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:44:10 </td>
   <td style="text-align:left;"> $SPX $BTC.X $AAPL  $DWAC  think Biden is wagging the dog due to disastrous Presidency. https://www.rt.com/russia/549149-anglo-saxon-propaganda-brigade/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:31:26 </td>
   <td style="text-align:left;"> EV Week In Review: Musk Finally Gets Biden&amp;#39;s Mention, XPeng Zooms Into More European Markets Ahead Of Nio, Ford Ropes In Another Tesla Executive And More  $TSLA $F $AAPL $LI $XPEV 

https://newsfilter.io/a/60e8d846bd071fac0463e1792dd6e326 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:29:47 </td>
   <td style="text-align:left;"> $AAPL - If Apple didn’t release guidance, this should serve as it:

https://news.yahoo.com/u-consumer-sentiment-falls-fresh-151419313.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:27:03 </td>
   <td style="text-align:left;"> $AAPL can it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:19:07 </td>
   <td style="text-align:left;"> $BKKT $AAPL  Gave bakkt a follow on twitter/ instagram and liked their facebook page to see what company&amp;#39;s they follow, from the 18 accounts they follow on instagram most are already partners.. but one really caught my eye.. partnership announcement on earnings perhaps? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:15:26 </td>
   <td style="text-align:left;"> $SPY  PUTIN : you guys are waiting on me.... Not going to reveal my hand and or let LET&amp;#39;S GO BRANDON frontrun my moves as to take credit for them to save his OVERBOUGHT STOCK MARKET...   - STAY THIRSTY MY FRIEND 🍻😆💀 Dos Equis  
 
&amp;quot;SHORTTHETOPBRO&amp;quot; - $tsla $afrm $pton $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:09:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-11 Trade Analysis Video: 
https://www.youtube.com/watch?v=5zYQlzchdqQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 22:00:08 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 21:55:11 </td>
   <td style="text-align:left;"> Apple Stock ( $AAPL ) Buying The Dips At The Blue Box Area. Read the article: https://elliottwave-forecast.com/trading/apple-stock-aapl-buying-dips-blue-box/ #elliottwave #ondaselliott #AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 21:54:32 </td>
   <td style="text-align:left;"> ICYMI: Wolf&amp;#39;s Weekly Trade Ideas: $AAPL $LVS $VIX http://dlvr.it/SJs55P </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 21:17:47 </td>
   <td style="text-align:left;"> 1 of 11 $AAPL $AMGN $AXP Daily and 30 min charts of the DJIA Components with the SSI indicator, a proprietary indicator based exclusively on the eSignal platform, are posted here weekends … see 2/11 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 21:14:37 </td>
   <td style="text-align:left;"> $PTON $AAPL $AMZN $SPOT $NFLX 
Some possible buyers of Peloton:
Apple, Amazon, Spotify and Netflix. 
Get in bulls before we suddenly go over $100/share in seconds after buyout news. Bulls you’ve seen it before. It’s one of the nicest news for bulls ever.
🚴🚴🚴🚴🚴🚴🚴🚴🚴🚴🚴🚴🚴🚴🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🐂🐂🐂🐂🐂🐂🐂🐂🐂🐂🐂🐂🐂🐂🦍🦍🦍🦍🦍🦍🦍🦍🦍🦍🦍🦍🦍🦍❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 20:51:43 </td>
   <td style="text-align:left;"> Samsung Might Finally Have an Apple Killer on Its Hands

$SSNLF $AAPL

https://www.thestreet.com/investing/samsung-might-finally-have-an-apple-killer-on-its-hands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 20:31:03 </td>
   <td style="text-align:left;"> $AAPL Biden and this liberals pushing for a war 🤣
How fast can you destroy this country </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 20:27:42 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #1 stock that institutions are trading with 73.9K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 20:25:40 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG Monday should be green and all this garbage war talk should blow over america can’t do crap and will not go to war! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 20:24:46 </td>
   <td style="text-align:left;"> ✅Bull’s Week 2/11/22❌
🟢 $SPY CALLS 100% (watchlist)
🟢 SPY PUTS 65% (dt, scale)
🟢 $BA CALLS 56% (dt)
🟢 SPY PUTS 50% (lotto) 
🟢 $QQQ PUTS 38% (lotto)
🟢 SPY CALLS 38% (dt) 
🟢 SPY PUTS 24% (dt)
🟢 SPY PUTS 21% (dt)
🟢 $UBER CALLS 18% (swing)
🟢 SPY PUTS 17% (dt)
🟢 QQQ PUTS 17% (lotto)
🟢 SPY PUTS 15% (watchlist)
🟢 SPY PUTS 16% (dt) 
🟢 APPS 13% ( lotto) 
🟢🟡 $AAPL CALLS 10% (swing)
🔴 APPS - iv crush. Expired.  

(DISCORD LINK IN BIO) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-12 20:23:24 </td>
   <td style="text-align:left;"> $SPY this BS for 3 months of non stop Russia is going to invade Ukraine is this administration WMD (weapons of mass destruction) they show same photos of vehicle in parking lots and say troop movements. It would be nice if USA media reported other side of story by talking to Russian officials https://medium.com/@InstituteSecTech/fake-news-and-wmds-in-the-age-of-the-internet-fc6a2f80e997   $FB $AAPL $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:40:33 </td>
   <td style="text-align:left;"> $SPY remember tomorows red or green doest matter... eod when fed minutes come out and if its not 0.5% rate increase immediately * which is extremely unlikely) , tuesday is going to be major rjp green $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:38:32 </td>
   <td style="text-align:left;"> $SPY don’t get swindled tomorrow morning buying in morning because of FOMO and then we close red… $aapl $googl $tsla $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:37:10 </td>
   <td style="text-align:left;"> $GOOG $Tsla market playing squid game with us? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:36:19 </td>
   <td style="text-align:left;"> $TSLA wont goof until all the bad issues gone. Buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:35:27 </td>
   <td style="text-align:left;"> $GGPI to $TSLA FUTURE Will Always Be Here. NOT Mars! 
U OLD MUSK! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:32:33 </td>
   <td style="text-align:left;"> $TSLA 

Tesla sued by California over civil rights. American automaker Tesla is being sued by the California state civil rights agency on behalf of “thousands of Black workers” after a decade of complaints and a 32-month investigation. The state charges that Tesla enabled a culture of racism and divisiveness at its California plant, where Black employees regularly endured object of racial slurs. Tesla denied the claims. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:32:21 </td>
   <td style="text-align:left;"> $TSLA lol Silverado with 75 miles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:32:21 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-13 Options Analysis Video: 
https://www.youtube.com/watch?v=ESuaGmOsPBU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:32:05 </td>
   <td style="text-align:left;"> $TSLA every time I see an EV commercial on super bowl. I think.  TESLA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:31:13 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:30:27 </td>
   <td style="text-align:left;"> $F $TSLA $GM funny how Tesla doesn’t have to use money on marketing. Fuck your commercials, we know people LOVE TESLA!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:27:20 </td>
   <td style="text-align:left;"> $TSLA futures are green so haha shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:27:13 </td>
   <td style="text-align:left;"> $TSLA Future is green. All those people who got spooked about the war now gona buy back in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:25:17 </td>
   <td style="text-align:left;"> $TSLA  Real price come out soon.. Hit the target price... 
Join now: livetradingchat.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:23:34 </td>
   <td style="text-align:left;"> $DWAC $tsla $twtr $fb this is the coolest halftime show i have ever seen and im old lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:19:55 </td>
   <td style="text-align:left;"> $SPY $AAPL $ARKK $TSLA ya all ready for slim shady </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:19:37 </td>
   <td style="text-align:left;"> Looks like we&amp;#39;re not only buying more shares of $GGPI tomorrow, but also buying a Polestar 2. 

$TSLA and $LCID have some real competition 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:18:00 </td>
   <td style="text-align:left;"> $TSLA  ask yourself why ferrari doesn&amp;#39;t make commercial

Because they don&amp;#39;t have competition.

Same as tesla in The EV market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:17:41 </td>
   <td style="text-align:left;"> $TSLA worst company to do option trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:16:03 </td>
   <td style="text-align:left;"> $TSLA what is this half time show? It feels like I&amp;#39;m 20 years in the past. It&amp;#39;s surreal lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:14:00 </td>
   <td style="text-align:left;"> $TSLA + $DWAC

BOOM 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:11:37 </td>
   <td style="text-align:left;"> $TSLA Fake morning pop and quickly sold off, same as every other day. No reason to expect different, company incapable of producing any positive news surprises at this stage of the game. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:10:20 </td>
   <td style="text-align:left;"> $GGPI doesn&amp;#39;t even know which company is going to Mars. Only wants to be what $TSLA was at 5 years ago. What a low bar. At least they&amp;#39;re being realistic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:09:51 </td>
   <td style="text-align:left;"> $SPY $TSLA weow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:08:36 </td>
   <td style="text-align:left;"> $TSLA  1350$ PT by  piper sandler </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:08:18 </td>
   <td style="text-align:left;"> $TSLA No conquering Mars… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:07:54 </td>
   <td style="text-align:left;"> Video Replay Sunday Night LIVE! $ARKK $LW $SJT $NEE $TSLA https://thecontrariantrader.com/sunday-night-futures-live-9/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:07:42 </td>
   <td style="text-align:left;"> $TSLA Tesla futures down $16.78 now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:06:12 </td>
   <td style="text-align:left;"> $TSLA Nikkei on a free fall currently </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:06:07 </td>
   <td style="text-align:left;"> $TSLA Not part of the Trump Cult but I am a Conservative Republican. Every real Yankee is. For the republic for which I stand. This garbage got to get canned. No clue what the liberal agenda is and honestly I don&amp;#39;t care. However let&amp;#39;s just all get together and cancel Tesla Inc. Not even a choice about it. Call yourself whatever you ever want but don&amp;#39;t call yourself an American if you don&amp;#39;t agree. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:04:04 </td>
   <td style="text-align:left;"> $SPY $TSLA $GME $TWLO $BA  while you watch the halftime show join my room to see the best alerts anywhere tmrw. 

375$---&amp;gt; $16,435 😱 in 1 day. 😱

🏈🍺🏈😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:03:42 </td>
   <td style="text-align:left;"> $GGPI  great commercial. now we will be amongst discussion with competition like $TSLA  $FSR  $RIVN and $LCID  well majority have no car yet so Polestar is clear choice, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:03:31 </td>
   <td style="text-align:left;"> $TSLA 
$GGPI no conquering Mars 

https://youtu.be/nRUA5UGI7hs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:03:25 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Market will be Up 2-3% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:03:13 </td>
   <td style="text-align:left;"> $TSLA Watchlist going as planned!🤑💰
Discord link in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:02:33 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $865.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:02:27 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-13 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=ygIXKsS41PE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:01:25 </td>
   <td style="text-align:left;"> $TSLA  Reviews from our members!⭐️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 09:01:02 </td>
   <td style="text-align:left;"> $GGPI Nice add on the super bowl, really ! Love how they played on the $TSLA  weak point 👍 
- Not dirty secret
- No conquering Mars 😂

https://youtu.be/nRUA5UGI7hs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:59:22 </td>
   <td style="text-align:left;"> $TSLA ouch lot of commercials targeted against tesla/spacex tonight. too bad tesla doesnt need to spend millions on advertising to get noticed oh wait </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:59:06 </td>
   <td style="text-align:left;"> $DWAC they had to announce an emergency fed meeting right after the John Durham news? really?? is $tsla and trump stocks gonna dive or spike at he bell?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:58:31 </td>
   <td style="text-align:left;"> $TSLA TSLA Stock Price Prediction and Analysis for Next Coming Monday February 14th
https://youtu.be/Lcrx7HCai64 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:58:11 </td>
   <td style="text-align:left;"> $GGPI $TSLA No conquering Mars, bitch! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:57:58 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:56:20 </td>
   <td style="text-align:left;"> latex88e9e0fb5564f36e0629ef3f4480231f$ will soon be served 0.02 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:55:39 </td>
   <td style="text-align:left;"> $TSLA NO CONQUERING MARS.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:55:36 </td>
   <td style="text-align:left;"> $SPX $TSLA most mentioned today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:54:51 </td>
   <td style="text-align:left;"> Episode 23 is out! 🎉 
 
This week is a pivotal moment for the market. $TSLA, $VIX and $FB all have unique setups that could provide insight on where $SPY goes 
 
Watch Video: http://youtu.be/IiGfC7auCNM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:54:42 </td>
   <td style="text-align:left;"> $TSLA no commercial bro </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:53:28 </td>
   <td style="text-align:left;"> $GOOGL futes ripping  $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:52:56 </td>
   <td style="text-align:left;"> $TSLA So Elon didn&amp;#39;t believe the super bowl was worth advertising but evry other commercial is electric car and trucks(Silverado). Better cars/trucks with better dealer/service options now available. RIP you turd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:52:41 </td>
   <td style="text-align:left;"> $GGPI Might have to buy some of this. Even if its not as good as $TSLA i dont think it needs to be to generate good sales if its a solid car and little less expensive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:52:08 </td>
   <td style="text-align:left;"> $TSLA May be it&amp;#39;s because I am a true blooded Yankee but I really cannot stand racist. They seem so dumb to everyone but themselves. Can you tell? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:52:05 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:51:46 </td>
   <td style="text-align:left;"> $TSLA NO CONQUERING MARS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:51:37 </td>
   <td style="text-align:left;"> $TSLA “NO CONQUERING MARS” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:51:32 </td>
   <td style="text-align:left;"> $TSLA No Mars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:49:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $INTC $TSLA organic seltzer?  Sounds like something Intel investors would drink…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:49:25 </td>
   <td style="text-align:left;"> $TSLA NO CONQUERING MARS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:48:32 </td>
   <td style="text-align:left;"> $TSLA McDonald&amp;#39;s Knows. Uhhhhhh something coming. Cancel this pos racist company. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:46:56 </td>
   <td style="text-align:left;"> $TSLA maximum pain tommorow.🔝🔝🔝🏃‍♂️🏃‍♂️🏃‍♂️🏃‍♂️🩸🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:46:54 </td>
   <td style="text-align:left;"> $GGPI $TSLA 
https://www.cnbc.com/2022/02/13/ev-start-up-polestar-takes-shots-at-teslas-elon-musk-in-super-bowl-ad.html?utm_term=Autofeed&amp;amp;utm_medium=Social&amp;amp;utm_content=Main&amp;amp;utm_source=Twitter#Echobox=1644796922 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:46:42 </td>
   <td style="text-align:left;"> $TSLA No one even cares if you are a fraud once you become a certified racist. What could possibly be worse than being a fraud company? Elon Musk proved what that can be. One that is racist and violated basic rights of humans in America. So whitey. I can say that because I am all white right? Time to wake up. You are no better than anyone. Pathetic excuses for human beings. Cancel this garbage. Show over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:45:57 </td>
   <td style="text-align:left;"> $TSLA Elon won’t spend $6 million for super bowl ad ? wtf 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:41:39 </td>
   <td style="text-align:left;"> $TSLA Chevy spends record money on super bowl ad …..and everyones talking    
about whens the the Cyber truck Coming? 
 
Musk for the win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:36:22 </td>
   <td style="text-align:left;"> $TSLA Elon has to bring an affordable car to market. A 25k car. That will be the differentiator. I’d love to buy a model 3, but I just don’t make enough to justify it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:32:26 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-13 Technical Analysis Video: 
https://www.youtube.com/watch?v=l1MVCNllnHk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:32:24 </td>
   <td style="text-align:left;"> $AMD  $nvda  $tsla  $AAPL  
 
 https://www.investopedia.com/ask/answers/043015/what-difference-between-accretive-and-dilutive-merger.asp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:29:10 </td>
   <td style="text-align:left;"> $GGPI $TSLA $LCID $F Invest LOW =or= Chase HIGH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:28:45 </td>
   <td style="text-align:left;"> $SAVA $GME $TSLA $AMC Arrest Joe Kenny Gary Janet and Jerome anyone else? Market corruption is hitting all new lows.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:28:07 </td>
   <td style="text-align:left;"> $TSLA I thought I couldn&amp;#39;t like this company any less until I read that lawsuit. This is a disgrace of a company. No longer welcome in America. Let China keep Tesla Shanghai Ltd. We don&amp;#39;t care. You KKK Tesla Cult Members. We don&amp;#39;t care about YOU either. Enjoy your permanent losses. Gary Gensler do your job so I don&amp;#39;t even need to think about this despicable company ever again. Saint Valentine&amp;#39;s Day Massacre! Al Capone Style. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:25:30 </td>
   <td style="text-align:left;"> $TSLA This week Musk is supposed to go to Berlin and possible start of production/delivery of vehicles may be announced </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:25:19 </td>
   <td style="text-align:left;"> $TSLA CHEVY TRUCK.   LOOKS AWESOME!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:25:02 </td>
   <td style="text-align:left;"> $TSLA Every car manufacturer going electric, Chevy Silverado commercial, pole-star, BMW electric, but Tesla never had a commercial yet. Can’t wait to see TESLA‘s commercial in the future!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:25:02 </td>
   <td style="text-align:left;"> $TSLA electric vehicle commercial going to pump Tesla up tomorrow buy and sell the Super Bowl hype  . Easy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:24:53 </td>
   <td style="text-align:left;"> $TSLA 
So puts on Monday after that bad ass Silverado commercial? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:24:41 </td>
   <td style="text-align:left;"> $TSLA is gonna drop tomorrow on all these electric car commercials 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:24:18 </td>
   <td style="text-align:left;"> $TSLA SpaceX will become Tesla&amp;#39;s biggest customer: hundreds of thousands of robots to prep mars for human consumption. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:23:22 </td>
   <td style="text-align:left;"> $TSLA I have all kinds of mixed kids. Would you racist scum like to hate my children for not being all white while you are at it? Subject my kids to anything racism and I will gladly show you what real is. Same applies to this pos company. We all the same. This company is done. DONE. Cancel Tesla Inc. Gary do your Job. Saint Valentine&amp;#39;s Day Massacre. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:21:54 </td>
   <td style="text-align:left;"> $TSLA how many recalls will this pos announce. The fog is becoming clearer as the circus emerges. This overbloated pos stock will burn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:19:24 </td>
   <td style="text-align:left;"> $GGPI $TSLA No conquering Mars 😆😆😆😆😆

Shots fired!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:17:50 </td>
   <td style="text-align:left;"> $TSLA 

When someone calls innovation #Tesla non sense in a direct insult @elonmusk —- know that’ll be the first who goes belly up !!  #Volvo $F

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:16:53 </td>
   <td style="text-align:left;"> $TSLA Cancel Tesla Inc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:16:46 </td>
   <td style="text-align:left;"> $TSLA 

Check out these 3 stock targets for next week along with market analysis. 

https://youtu.be/VbMCRZdFvwY

—————- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:16:04 </td>
   <td style="text-align:left;"> $TSLA 1250$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:15:59 </td>
   <td style="text-align:left;"> $GGPI YOU HEAR THAT ELON $TSLA NO CONQUERING MARS OR EMPTY PROMISES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:15:01 </td>
   <td style="text-align:left;"> $TSLA I could have swore my ancestors taught America what happens to racist. I guess I was wrong. We don&amp;#39;t play this game. Time to relearn History. Know who&amp;#39;s market belongs to? Us Yankees. Oops. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:13:58 </td>
   <td style="text-align:left;"> $GGPI $tsla $gm $f will someone tell these clowns Tesla spends zero money advertising, let alone stupid ass Super Bowl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:11:14 </td>
   <td style="text-align:left;"> $TSLA I am a white yankee and after reading that lawsuit that the State of California filed. I am furious. Don&amp;#39;t read it unless you want to be beyond mad. The fraud is one thing but to racially segregate OUR people and belittle them and demoralize them like this is 1950. You are DONE. I am sorry for what he did to people but this company WILL NOT be in MY COUNTRY anymore. China can keep what will be left of it. I can&amp;#39;t even imagine how African Americans feel about this pos. Flush it all down the toilet. Burn it to the ground. This company got to go. This is America. Not South Africa where whites are permitted to be racist SCUM. I am not alone. Anything but. Nati Time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:10:27 </td>
   <td style="text-align:left;"> $TSLA doge gonna moon tonight! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:05:48 </td>
   <td style="text-align:left;"> $TSLA Musk you are the father….It’s true </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:05:08 </td>
   <td style="text-align:left;"> $TSLA Supper bowl ad? i don’t think so. But love to see one for Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:04:00 </td>
   <td style="text-align:left;"> $TSLA that polestar 1 looked like a 2018 Lincoln Navigator. $RIVN is garb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:02:49 </td>
   <td style="text-align:left;"> $TSLA lol polestar&amp;#39;s ad is a shot a Tesla i suppose, &amp;#39;no conquering Mars&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:02:43 </td>
   <td style="text-align:left;"> $SPY Polestar just made a powerful enemy.  Yeesh.  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:02:33 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-13 Trade Analysis Video: 
https://www.youtube.com/watch?v=Q_qJ5gKlVaQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:02:01 </td>
   <td style="text-align:left;"> $TSLA New EV ads all over super bowl. iX looks amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:01:35 </td>
   <td style="text-align:left;"> $GGPI Soon as I seen it in the screen!!!!!! FUCK $LCID $TSLA and $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:01:25 </td>
   <td style="text-align:left;"> $SPY $TSLA $GGPI SHOTS FIRED MFERS GET DOWN GRAB YOUR STICKS.  BLAH BLAH BLAY GOING TO MARS OOF.  ELON SCRAMBLIN FOR THE KEYBOARD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:01:20 </td>
   <td style="text-align:left;"> $GGPI jabbing hard at the recall monster $TSLA 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:01:19 </td>
   <td style="text-align:left;"> $TSLA 

SP is now $1000 below where it should be by EOY !! 0.02

This will squeeze the life out of shorts accounts  — 

ZERO SYMPATHY!! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:01:10 </td>
   <td style="text-align:left;"> $TSLA Soon driving these garbage EVs will have your dumb self labeled as a racist. Tesla might as well just sell some bed sheets and pillow cases so you can dress up and hide in your car. Racist ass pos. Burn this stock to the ground. Cancel Tesla Inc. Garbage! Yankee Time Up in Here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:01:09 </td>
   <td style="text-align:left;"> $TSLA even if the market does rebound tomorrow, this won&amp;#39;t follow it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:00:55 </td>
   <td style="text-align:left;"> $SPY $TSLA who is that polar car? Trashing Tesla in the ad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:00:54 </td>
   <td style="text-align:left;"> $TSLA POLESTAR??? SHOTS FIRED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:00:37 </td>
   <td style="text-align:left;"> $TSLA i hope elon comes at their neck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:00:36 </td>
   <td style="text-align:left;"> $TSLA rather have a mustang Mache E. This is a trillion $ car company? Lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:00:27 </td>
   <td style="text-align:left;"> $GGPI no blah blah blah heard that $TSLA ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:00:22 </td>
   <td style="text-align:left;"> $TSLA polestar can suck my dick 

rams by 100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 08:00:09 </td>
   <td style="text-align:left;"> $TSLA wow fuck polestar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:59:51 </td>
   <td style="text-align:left;"> $TSLA polestar threw shade at Tesla in that ad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:59:51 </td>
   <td style="text-align:left;"> $TSLA fuck polestar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:59:49 </td>
   <td style="text-align:left;"> $TSLA Tesla is not just a car company! Tesla is years ahead of the competition! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:59:42 </td>
   <td style="text-align:left;"> $TSLA rather have the beemer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:56:31 </td>
   <td style="text-align:left;"> $TSLA All Electric BMW! Looks bad ass more competition coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:56:19 </td>
   <td style="text-align:left;"> $TSLA Cancel Tesla Inc. You guys thought McDonald&amp;#39;s was going to accept DOGE. Do you even know what this contraption is and why it was made? You shareholders better call your CEO and ask how many Americans canceled their orders since Friday. Lmfao. Cancel Tesla Inc. Just do it already Gary. Tesla Inc. is a certified racist fraud company. No room in America for this company. Canceled. Bye Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:55:43 </td>
   <td style="text-align:left;"> $TSLA No reason this should have this valuation. Not the only EV. Don’t even advertise. Get out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:55:35 </td>
   <td style="text-align:left;"> $TSLA electric BMW looks 10x better than any Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:55:07 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $TSLA is the #9 stock that institutions traded this week with 127.3K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:55:07 </td>
   <td style="text-align:left;"> $SPY UGH O $TSLA CULT

BMW COMIN FOR DAT ASS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:54:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

Odell making it look easy 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:52:38 </td>
   <td style="text-align:left;"> $MCD disclaimer:  I am long this stock but also hold $DOGE.X and made decent money off $TSLA on the way up. 
 
That being said, MCD has been successful since Elon&amp;#39;s grandparents were in diapers.  They&amp;#39;re not stupid.   
 
Elon Musk became the richest man in the world by fucking over everyone he could get his hands on.  He made a big list of everyone he could think of, called fellow scumbags like Chamath and Bill Ackman and asked if they could add anyone to the list, and then just fucked everyone: 
 
His own stock&amp;#39;s bulls with many &amp;quot;our stock is too high&amp;quot; tweets 
$BTC.X bulls by no longer taking it for his cars, under the pretext of environmental concern but in reality to suck China&amp;#39;s cock for model 3 sales;  his recent bashing of bitcoin suggests he&amp;#39;ll never accept it again 
DOGE.X bulls  
China themselves with a bunch of recall-riddled shitboxes 
 
In much the same way as Warren Buffett laughs at the idea of investing in TSLA, MCD laughs at the idea of trusting some slimeball shill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:52:30 </td>
   <td style="text-align:left;"> $TSLA I restarted my FSD Beta Score. Will be driving like a grandma 👵 for at least 100 miles over 5 consecutive days to be what happens in March </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:51:44 </td>
   <td style="text-align:left;"> $NIO $AAPL $TSLA A NEW, SIMPLE AND EASY METHOD TO UNDERSTAND TECHNICALS, TO CALL TOP AND BOTTOM. FREE VIDEO AND FREE TUTORIAL  https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:51:20 </td>
   <td style="text-align:left;"> $TSLA Adjust your portfolio for a second quarter recession. Elon predicted it and the Fed is paving the way for an economic slow down. Higher energy prices coupled with the highest inflation since 82 will definitely lead to consumer crushing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:49:50 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:47:28 </td>
   <td style="text-align:left;"> $TSLA According to his LinkedIn profile, Clarke worked in a number of roles at Tesla for more than 12 years. Most recently, he served as director of new programs engineering. He worked on numerous Tesla products, including the Model Y, the Roadster and Model 3, among other projects, according to LinkedIn.

He joins the company as Ford aims to boost its annual EV production capacity to 600,000 units by the end of next year, and as it prepares to launch the all-electric F-150 Lightning pickup truck this spring. The automaker has committed to investing $30 billion in electrification through 2025 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:42:15 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMD 

Future is ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:42:00 </td>
   <td style="text-align:left;"> $TSLA has a Return On Assets of 8.89%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:36:50 </td>
   <td style="text-align:left;"> $TSLA Piper Sandler wants to save bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:35:40 </td>
   <td style="text-align:left;"> $TSLA updated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:31:46 </td>
   <td style="text-align:left;"> $TSLA 
Okay made it here 30 minutes late. Futes reports coming soon lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:29:30 </td>
   <td style="text-align:left;"> $TSLA and down it goes tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:27:45 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/squawksquare/status/1492986015434346503?s=20&amp;amp;t=DsAkPl3ZXk47JDzo84LI4Q $F $GM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:27:19 </td>
   <td style="text-align:left;"> $TSLA 915 / 925 tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:25:57 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:23:45 </td>
   <td style="text-align:left;"> Shittin on the toilet $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:21:11 </td>
   <td style="text-align:left;"> $TSLA Piper Sandler’s Alex Potter increased his $TSLA PT fo $1,350 from $1,300, based on 10-K disclosure of $5-7B/year CapEx through 2024. Alex also raised his discount rate to 11.5% (from 11.2%) to reflect higher 10yr TY.

Source: Gary Black </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:20:40 </td>
   <td style="text-align:left;"> $TSLA company is not innovating. Musk has only stole others ideas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:20:07 </td>
   <td style="text-align:left;"> $dwac $cfvi $phun $tsla call holders tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:18:11 </td>
   <td style="text-align:left;"> $TSLA Fed finally gave clarity today on ending the bond but-backs on March 10th. Also pretty clear they may only do 1 rate hike in March 16th. Russia is not invading the Ukraine. We have reached peak fear and should see a rally this week on more certainty. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:16:55 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:15:16 </td>
   <td style="text-align:left;"> $TSLA Today, Piper Sandler raised target to $1,350.  This analyst is ranked #315 out of 7,789 Analysts on TipRanks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:06:25 </td>
   <td style="text-align:left;"> $SPY Bulls who bought SWING CALLS = ANNIHILATED 🚨😆 
 
told you guys - &amp;quot;SHORTTHETOPBRO&amp;quot; 
 
$PTON $AFRM $TSLA $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:05:20 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:01:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $DWAC $LCID-  Should be very interesting tomorrow.   
 
Learn how to grow your small account in just a few weeks or apply our strategies to your main.  
https://www.wallstreetsttatrading.com/learn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:01:21 </td>
   <td style="text-align:left;"> $TSLA  let&amp;#39;s see how the short will close hahahha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 07:00:00 </td>
   <td style="text-align:left;"> $QQQ $spy $tsla Colonel Peteuaki at the Kremlin tells me the war is postponed until wednesday since the Generals were drunk and it’s raining… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:59:52 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!!

New $TSLA price target: 

Alex Potter of Piper Sandler has increased his price target to $1,350 from $1,300 following a review of Tesla’s 10-K annual filing.

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:55:50 </td>
   <td style="text-align:left;"> $TSLA A drop to 580 is in the cards. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:54:28 </td>
   <td style="text-align:left;"> $TSLA $MCD imagine if McDonald’s actually pulls it off and has Elon eating a Big Mac  on Super Bowl Sunday as a commercial to announce they are accepting $DOGE.X i could careless about dogecoin but that would be fucking insane 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:54:19 </td>
   <td style="text-align:left;"> Earnings Yield Definition  $TSLA https://www.billionaireclubcollc.com/earnings-yield-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:54:10 </td>
   <td style="text-align:left;"> $TSLA During their Sunday phone call Ukraine&amp;#39;s President Zelensky asked Biden to visit Kiev in person amid continuing White House claims that a Russian invasion is set to happen &amp;quot;any day&amp;quot; now.  
 
Saying that major Ukrainian cities are &amp;quot;under safe protection,&amp;quot; Zelensky suggested that a visit of the US president in person would stop the spread of panic and prevent escalation. &amp;quot;I am convinced that your visit to Kyiv in the coming days... would be a powerful signal and help stabilize the situation,&amp;quot; Zelensky was quoted as saying in the call. 
 
&amp;quot;We will stop any escalation. The Ukrainian capital, Kiev, other cities in our country - Kharkov and Lvov, Dnepr and Odessa - are under safe protection,&amp;quot; Zelensky told the US president.  (Zero Hedge) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:53:55 </td>
   <td style="text-align:left;"> $TSLA time to fuk those ho&amp;#39;s bears in the asssss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:53:48 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:52:48 </td>
   <td style="text-align:left;"> $TSLA $1000? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:51:50 </td>
   <td style="text-align:left;"> $TSLA           New Giga plans leak    
              here a Giga ……there  a Giga                                          
                      everywhere a Giga!  
                                🚀 🌝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:50:11 </td>
   <td style="text-align:left;"> $SPY move along bulls... LIMIT DOWN MONDAY! 🚨  
 
Any attempted POPS - &amp;quot;SHORTTHETOPBRO&amp;quot; $TSLA $AFRM $PTON $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:48:05 </td>
   <td style="text-align:left;"> $TSLA https://www.zerohedge.com/geopolitical/surreal-plot-twist-ukraines-president-demands-proof-us-over-russian-invasion-claims  
 
Zelensky Invites Biden To Visit Ukraine In &amp;quot;Coming Days&amp;quot; In Pushback Against &amp;#39;Imminent&amp;#39; Invasion Fears (Zero Hedge)  
 
During their Sunday phone call Ukraine&amp;#39;s President Zelensky asked Biden to visit Kiev in person amid continuing White House claims that a Russian invasion is set to happen &amp;quot;any day&amp;quot; now.  
 
Saying that major Ukrainian cities are &amp;quot;under safe protection,&amp;quot; Zelensky suggested that a visit of the US president in person would stop the spread of panic and prevent escalation. 
 
 &amp;quot;I am convinced that your visit to Kyiv in the coming days... would be a powerful signal and help stabilize the situation,&amp;quot; Zelensky was quoted as saying in the call. 
 
&amp;quot;We will stop any escalation. The Ukrainian capital, Kiev, other cities in our country - Kharkov and Lvov, Dnepr and Odessa - are under safe protection,&amp;quot; Zelensky told the US president. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:46:45 </td>
   <td style="text-align:left;"> $TSLA LOOK OUT 780 next stop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:45:01 </td>
   <td style="text-align:left;"> Wholly Owned Subsidiary Definition $TSLA $AAPL https://www.billionaireclubcollc.com/wholly-owned-subsidiary-definition/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:38:17 </td>
   <td style="text-align:left;"> $TSLA I ordered a car with hands-on manual autopilot and half full self driving. if it’s not delivered by end of this year, I am going to short this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:38:17 </td>
   <td style="text-align:left;"> $DWAC i bought $tsla calls kiss me for good luck please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:38:02 </td>
   <td style="text-align:left;"> $TSLA 🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🏃‍♂️🏃‍♂️🏃‍♂️🏃‍♂️🏃‍♂️🏃‍♂️🏃‍♂️🏃‍♂️🏃‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:35:40 </td>
   <td style="text-align:left;"> $TSLA  this week we gonna experience the biggest short squeeze. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:34:01 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:27:07 </td>
   <td style="text-align:left;"> $tsla sold some puts +300% I have 4 more strikes to sell. 👁🍝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:26:15 </td>
   <td style="text-align:left;"> $TSLA to da moon now  
https://carnewschina.com/2022/02/13/breaking-teslas-second-chinese-gigafactory-in-works-local-government-leaks/?fbclid=IwAR2pZlhHCOGbtcUelyZBIk_TiYZuutcpUeZ6tX9SUJcXmyfPt7HHav3Zlzk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:21:09 </td>
   <td style="text-align:left;"> $TSLA So there is no war. White House and sleepy Joe bought bunch of puts then announced there would be a war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:13:55 </td>
   <td style="text-align:left;"> $TSLA I remember one of my friends telling me that Leo lost over $10 million when he invested into Tesla several years back prior to the pandemic.  Since then, DiCaprio can&amp;#39;t stand the fooker. He thinks very low of Musk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:13:40 </td>
   <td style="text-align:left;"> $TSLA if market is green tomorrow, Tesla green. If market is red, Tesla red. Best investment advice you’ll get on Stocktwits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:09:55 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:08:46 </td>
   <td style="text-align:left;"> $NIO $TSLA $AAPL A SIMPLEST WAY TO BUY BOTTOM SELL TOP. FREE VIDEO FREE TUTORIAL. ENJOY https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:08:19 </td>
   <td style="text-align:left;"> $TSLA Musk is about pure greed. He doesn&amp;#39;t give a shit about anyone.  

https://www.teslarati.com/elon-musk-dont-look-up-peter-isherwell-inspiration-confirmed/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:05:33 </td>
   <td style="text-align:left;"> Ford Has A Surprise Feature to One-Up GM and Tesla

$F $GM $TSLA

https://www.thestreet.com/investing/ford-has-a-surprise-for-gm-and-tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:05:17 </td>
   <td style="text-align:left;"> $TSLA prepare for take off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:04:57 </td>
   <td style="text-align:left;"> $DOGE.X $TSLA Maybe this commercial has nothing to do with Dogecoin maybe Elon will be sitting in a Tesla at a McDonald&amp;#39;s drive thru but right before he can order his Saweetie combo he shits his pants </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:03:06 </td>
   <td style="text-align:left;"> $TSLA ready to drop into the 700s tomorrow, Fanboys?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:02:40 </td>
   <td style="text-align:left;"> $TSLA explosion imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:00:58 </td>
   <td style="text-align:left;"> $TSLA Lots of sabre rattling and disinformation and propaganda but there will be NO war. Putin is enjoying the show and getting  high oil prices by this manufactured tensions on Ukraine border. If no tension oil will immediately drop by 10-15 dollars per barrel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:00:47 </td>
   <td style="text-align:left;"> $TSLA the posts on this board by Tesla Fanboys sound completely delusional.  They are so far-fetched that the comments reek of desperation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 06:00:12 </td>
   <td style="text-align:left;"> $TSLA should just build another factory in China. It’s clearly working. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:58:39 </td>
   <td style="text-align:left;"> Taking Social Security Early: Pros and Cons  $AMZN $TSLA $AAPL $MA $V https://www.billionaireclubcollc.com/taking-social-security-early-pros-and-cons/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:58:27 </td>
   <td style="text-align:left;"> $NIO great video on PS ratios of $TSLA $XPEV $LI
https://youtu.be/OIzmHhE8s3k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:58:01 </td>
   <td style="text-align:left;"> $TSLA this is where the opening of Austin with 4680 Model Y’s, China numbers (in next 10 hours), and possible news on the range of the new model Y out of Texas will all protect Tesla share price on any macro uncertainties. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:57:01 </td>
   <td style="text-align:left;"> $TSLA Russian Ukraine war will make Tesla price goes up, $GM and $F will go down  
The reason is gas prices will go up, makes more customers prefer to buy EV  than regular CE cars   
Tesla is dominating the EV market at this point, Ford and GM EV sales are only 3% of their total sales, and it will them a lot of money and a lot of time to compete with Tesla  
This is why very likely Tesla will be a buy next week, Ford and GM will be a sell 
I expect with the Russian/Ukraine war and the expected spike in gas price to trigger a huge shift in the auto industry, we may find more than 50% of new cars sales are EV, and 70% of that will o to Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:56:51 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA thank u POTUS for making awareness about climate change , taking leadership and making the right moves , we r with u and will be with u come 2024 , thank u sir 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:56:38 </td>
   <td style="text-align:left;"> $TSLA I see the Ukrainian President’s outreach to Putin for transparency as hugely bullish.  There will be no invasion. Would have happened already. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:56:25 </td>
   <td style="text-align:left;"> $DOGE.X $MCD $TSLA $HOOD $,COIN 
89 minutes away 

https://youtu.be/hv5CzJdx6NE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:55:46 </td>
   <td style="text-align:left;"> $TSLA rumor of a 2nd China factory in Liaoning, in the north east would make sense given China is a massive market for Tesla. The choice of locating the design center in Beijing rather than Shanghai would also support this.  A future announcement of a 2nd Chinese Giga would be massive for the share price.  Tesla must be considering it given all the regulatory hurdles with Berlin and insane production in China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:55:45 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA Happy Sunday everyone! Hopefully you&amp;#39;re taking some time off to enjoy the weekend.  Also, enjoy the Super Bowl - if you&amp;#39;re watching tonight. 
 
I like to use this time to step back, reset, and prepare for the week ahead (DD, news, rumors, etc.)  
 
One of the most important things to track is social momentum and social sentiment. When a ticker starts to gain traction, more people see it , and it can start to take off.  
 
This is why we build this social sentiment dashboard, so you can stay ahead of the trends an movements. It is one of the most useful indicators for investing and trading. Check it out - happy to answer any questions. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_202202013 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:54:58 </td>
   <td style="text-align:left;"> $tsla $dwac sleep tight libtards $twtr $fb $cmcsa https://youtu.be/4u5KnVRv914?t=116 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:50:48 </td>
   <td style="text-align:left;"> $TSLA $SPY What company do you know that did 54 billion in revenue in 2021 that expects 50% growth in 2022? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:48:28 </td>
   <td style="text-align:left;"> $TSLA 1000 incoming, tesla is a great company and its stock is on sale </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:43:54 </td>
   <td style="text-align:left;"> $TSLA $700 is coming. Tesla is a great company but its stock is POS. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:42:20 </td>
   <td style="text-align:left;"> $TSLA China remains the key for Tesla. January numbers posting within the next 10 hours could be huge. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:40:42 </td>
   <td style="text-align:left;"> $TSLA FYI:  Stocks charts are non-regressive correlation-based predictive instruments without causality (Latter tools may or may not be &amp;quot;totally&amp;quot; accurate) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:35:52 </td>
   <td style="text-align:left;"> 🔥We are now live 🔥 
📈 THE WEEKEND UPDATE 📈 
IM GOING TO BREAK DOWN  👇 
📈TRADE IDEAS  
🔫TRIGGERS  
🎯TARGETS  
🚨SECTORS CLICK  
👉 https://us02web.zoom.us/j/82883233300  $SPY  $AAPL   $TSLA    $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:35:14 </td>
   <td style="text-align:left;"> Now we have to see what the market does with the new I formation 

$TSLA $FB $VMEO $PRQR $CEI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:29:16 </td>
   <td style="text-align:left;"> $AAPL $NIO $TSLA WILL HAIKIN ASHI CANDLES STAND TEST OF TIME WITH APPLE? YES THEY WILL AND YOU CAN USE THEM FOR FINDING THE TOP AND BOTTOM https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:26:57 </td>
   <td style="text-align:left;"> $TSLA I am such a Terrible FSD Beta Scorer: 0 pts for 18 miles driven 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:25:20 </td>
   <td style="text-align:left;"> $TSLA The average clueless analyst target is 100 dollars higher than the current price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:24:59 </td>
   <td style="text-align:left;"> $TSLA I’ll take some off the table at $5,000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:24:22 </td>
   <td style="text-align:left;"> $TSLA ready for the morning bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:23:09 </td>
   <td style="text-align:left;"> $TSLA 

Tesla Begins Delivering Cars to Leasing Companies in Israel 🇮🇱 

🙏🏻🐉🦅

https://www.tesmanian.com/blogs/tesmanian-blog/tesla-began-delivering-cars-to-leasing-companies-in-israel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:21:47 </td>
   <td style="text-align:left;"> $TSLA 
Or down first then up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:21:44 </td>
   <td style="text-align:left;"> $TSLA There you have it.  https://metro.co.uk/2022/02/11/mark-rylance-based-dont-look-up-villain-on-dangerous-elon-musk-16093921/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:21:34 </td>
   <td style="text-align:left;"> $TSLA 
We are going to be up ? Then down 🤣😂🤦🏼‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:21:00 </td>
   <td style="text-align:left;"> $GGPI the more I watch the Polestar commercial, the more I like it. No bullshit, NO CONQUERING MARS!!! Lmao!!!  Ooofff shots fired at $TSLA  !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:19:14 </td>
   <td style="text-align:left;"> $DWAC $tsla $twtr $cmcsa holy moly #lockherup #trumpwasright </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:19:03 </td>
   <td style="text-align:left;"> $TSLA love the company, do not like the P/E.  Having said that yes i agree this opens tomorrow north of $900. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:16:59 </td>
   <td style="text-align:left;"> $BMTX $AMC $PLUG $SKLZ $TSLA https://lomotif.app.link/SPZUrZtICnb yee babe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:15:06 </td>
   <td style="text-align:left;"> What to Know About Restricted Stock Units  $AAPL $TSLA $AMZN $LCID $SNAP https://www.billionaireclubcollc.com/what-to-know-about-restricted-stock-units/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:14:57 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:10:58 </td>
   <td style="text-align:left;"> $TSLA take a dump on this racist company! This isn&amp;#39;t apartheid South Africa. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:06:26 </td>
   <td style="text-align:left;"> $TSLA 3-7k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:04:23 </td>
   <td style="text-align:left;"> $TSLA smart woman

https://www.cnbc.com/2022/02/13/feds-daly-advocates-for-a-measured-approach-as-rate-hike-expectations-rise.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:03:38 </td>
   <td style="text-align:left;"> Tax Strategies for Your Retirement Income $SPY $QQQ $DJIA $DXY $TSLA  https://www.billionaireclubcollc.com/tax-strategies-for-your-retirement-income/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:01:16 </td>
   <td style="text-align:left;"> $GME $AMC $BBIG $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 05:01:04 </td>
   <td style="text-align:left;"> $TSLA when market realizes war is fake and fed is on path to 0.25 in march, this may touch 1000 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:59:40 </td>
   <td style="text-align:left;"> $TSLA 450 500  by March 10th mark it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:58:21 </td>
   <td style="text-align:left;"> $TSLA open 900 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:57:18 </td>
   <td style="text-align:left;"> $TSLA Invasion is all power talk  
https://www.voanews.com/a/biden-speaks-with-ukraine-s-zelenskiy-as-threat-of-russian-invasion-looms/6439904.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:57:11 </td>
   <td style="text-align:left;"> $TSLA where is the war, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:56:32 </td>
   <td style="text-align:left;"> $TSLA coming off a multi year support level. Good luck bears. I’m long here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:55:20 </td>
   <td style="text-align:left;"> $TSLA The call I grabbed before Friday close looks like it will print at open🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:52:41 </td>
   <td style="text-align:left;"> #Levermann #Global #MegaCap #Buy WK6 $TSLA (5), $NVDA (5), $PG (5) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:52:33 </td>
   <td style="text-align:left;"> $TSLA open at 890 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:51:53 </td>
   <td style="text-align:left;"> $TSLA most stocks will be up Monday and Tuesday that’s for sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:51:45 </td>
   <td style="text-align:left;"> $TSLA ignore the salty bears.... all in on tsla ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:51:41 </td>
   <td style="text-align:left;"> $TSLA do NOT invest this is a failing company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:51:24 </td>
   <td style="text-align:left;"> $TSLA sell it. 🩸🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:51:03 </td>
   <td style="text-align:left;"> $TSLA who else could sell an unfinished product to consumers for testing, even increasing the price? I am bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:50:55 </td>
   <td style="text-align:left;"> $TSLA Average pump 125% for Tesla. We bulls know what&amp;#39;s going to happen later this year! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:49:58 </td>
   <td style="text-align:left;"> $TSLA markets will die this week. Stage 4 correction is here. Get to cash and hedge with puts otherwise youll be eating ice soup. 🔝🔝🔝🔝🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🔝🩸🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:48:16 </td>
   <td style="text-align:left;"> $TSLA zerohedge@zerohedge·3m* (Ukrainian President) ZELENSKIY INVITES BIDEN TO VISIT UKRAINE IN `COMING DAYS&amp;#39; 
*ZELENSKIY PLEDGES TO `STOP ANY ESCALATION TOWARDS UKRAINE&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:46:30 </td>
   <td style="text-align:left;"> $TSLA that MACD crossing on 6M/4H is not nice signal,as these are quite relaible for some week forecasts. Sh1t if this goes to 800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:46:12 </td>
   <td style="text-align:left;"> $TSLA Huge call options being bought by hedge funds! 
https://youtu.be/gPuB2W4Vj7A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:44:51 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $TSLA $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:44:03 </td>
   <td style="text-align:left;"> Ambassador Bridge still closed ... love it ... welcome to crash Monday and beyond and the Autogeddon Depression  ... check out the live 24/7 webcam inbound, outbound 🇨🇦🇺🇸 https://www.ambassadorbridge.com/into-canada/ $F $GM $TM $TSLA $STLA $STLA and more re LINAMAR, MAGNA, et al </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:43:38 </td>
   <td style="text-align:left;"> latexc68227421afaad02ce6bd4cf436ad98daapl
$tsla

Forget superbowl .... futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:40:06 </td>
   <td style="text-align:left;"> $TSLA  so much competition where exactly? Ahhahaha no EV will compare to tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:39:36 </td>
   <td style="text-align:left;"> $TSLA 1 trillion valuation get real party is over so much competition really surprised this isn&amp;#39;t under 5 billion valuation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:39:18 </td>
   <td style="text-align:left;"> $TSLA coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:39:08 </td>
   <td style="text-align:left;"> $TSLA $NIO $AAPL price action through lens of Haikin Ashi candles !!! MUST WATCH https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:38:12 </td>
   <td style="text-align:left;"> $TSLA self driving!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:37:13 </td>
   <td style="text-align:left;"> $TSLA $550 will be a tough line in the sand that may have to prove twice that it can hold in order for this to continue higher. Don’t be caught off guard!! If $550 can hold both times then bulls may be the winners! Should be a nail biter when we get to those levels! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:37:03 </td>
   <td style="text-align:left;"> $TSLA so many retards in here bought into Tesla over the $1000 range. They are hoping they will have a chance to break even. When in reality we all know the market is headed way down, and Tesla will be cut in half along the way. Get out now or bury your head in the sand.🔝🔝🔝🔝🩸🩸🩸🩸🩸🔝🔝🔝🩸🩸🩸🩸🔝🔝🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:35:51 </td>
   <td style="text-align:left;"> ROTFLMAO .. the fools can&amp;#39;t make money during the Autogeddon Depression so why not? https://finance.yahoo.com/news/super-bowl-lvi-sports-betting-200931747.html ... loving my 🇺🇸 stocks active short trading for profits 🤑🐻❤😈 $f $gm $TM  $tsla $stla and more ... enjoy Crash Monday and beyond starting at 6 PM EST today 👍😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:34:45 </td>
   <td style="text-align:left;"> $SPY $TSLA  all in tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:33:25 </td>
   <td style="text-align:left;"> $TSLA big up day tomorrow Russia and Ukraine sorting things out over this storm in tea cup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:32:37 </td>
   <td style="text-align:left;"> $TSLA rob-a -taxis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:32:16 </td>
   <td style="text-align:left;"> $TSLA I wonder if they were using the autonomous driving feature...
https://abc7.com/woodland-hills-deadly-crash-woman-killed-car-slams-into-tree/11560146/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:32:08 </td>
   <td style="text-align:left;"> $TSLA   

Good time to be in oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:30:26 </td>
   <td style="text-align:left;"> $TSLA be prepared for the reaming this week..gonna be ugly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:30:11 </td>
   <td style="text-align:left;"> $TSLA 200MA is still working like heavy support and bouncing place. Hope that these FED and Ukraine bullsh1t go away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:30:00 </td>
   <td style="text-align:left;"> $TSLA sounds like elon could have a doge/ McDonald’s commercial tonight . Time to make some $ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:28:15 </td>
   <td style="text-align:left;"> $TSLA This is going to get absolutely hammered this week..I feel bad for anyone who still owns this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:26:59 </td>
   <td style="text-align:left;"> $TSLA This isn&amp;#39;t even a joke anymore. If you are ok with racism it is only because you too are a racist. I might be white but what does that matter? It don&amp;#39;t. Let me however use white privilege card to tell you something though. Tesla is already a certified racist and fraud company. We don&amp;#39;t care what you say or think or do anymore. It just got real. Yankee Style. Just wipe it out. About to look like Gettysburg up in here. You bulls stepped onto the wrong battlefield. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:23:36 </td>
   <td style="text-align:left;"> $TSLA  fear money doesn&amp;#39;t not make money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:23:29 </td>
   <td style="text-align:left;"> Cathie Wood&amp;#39;s ARK Investment Betting Big On Innovation, Largely On Unprofitable Companies  $RBLX $SQ $HOOD $TSLA $ROKU 

https://newsfilter.io/a/6098c9a28452b7c2875861cea6163c75 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:22:31 </td>
   <td style="text-align:left;"> $TSLA down by 80% on the Cairo Exchange!!! Tesla Fanboys about to be broken in half. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:22:01 </td>
   <td style="text-align:left;"> Elite Options #Watchlist 💡 
 
📉 $TSLA 800P under 851 | 🎯: 800 | SL: 865 
📉 $AMZN 2900P under 3054 | 🎯: 2955 | SL: 3088 
 
Earnings Trade Ideas 🎲 
📈 $NVDA 2/18 265C 
📈 $RBLX 2/18 77C 
 
Follow us on twitter for more trade ideas twitter.com/EliteOptions2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:19:02 </td>
   <td style="text-align:left;"> $TSLA - Under 851 - Trade Idea 💡 -  Feb 18 800P 
 
Closed at 860.00 
 
Failed at 945 resistance and started to break down on Friday 
 
Under 851 can drop to 819, 800  
 
Calls can work above 945   
 
Follow us on Twitter for more Trade Ideas: twitter.com/eliteoptions2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:17:02 </td>
   <td style="text-align:left;"> February 7th - February 11th Trade Log 📝    
   
$SPX $TSLA $QQQ  
  
Follow us on Twitter for more Trade Ideas: twitter.com/eliteoptions2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:15:24 </td>
   <td style="text-align:left;"> $TSLA We didn&amp;#39;t even need another reason to go all out American on Elon Musk but like this is 2022. Racial Segregation? You got to be kidding. Take this Chinese Company off my Market. Elon Musk is some White South African with a green card. We will pull that card too by the time this is all said and done. Yankee Doodle Dandy. Last one out turn off the lights. Blood of first Americans in my veins and this guy makes it boil. Believe me I am anything but alone. Dog this Dog. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:13:21 </td>
   <td style="text-align:left;"> $TSLA 7 - 8% drop  6.31am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:11:28 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $865.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:10:01 </td>
   <td style="text-align:left;"> $TSLA 🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:09:06 </td>
   <td style="text-align:left;"> $TSLA Did someone say fear? lol No big deal. Just biggot drop it. Cancel Tesla. Bye Tesla. Have you guys not seen that the State of California is suing Tesla Inc. for being certified racist? That isn&amp;#39;t fear. That is death. I am a Yankee. Know what we do to racist that treat humans like animals? Guess you will find out. Ask the south. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:07:00 </td>
   <td style="text-align:left;"> $TSLA shows a strong growth in Revenue. Over the last 5 years it has been growing by 50.37% yearly. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:05:48 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-13 Largest Trades Data: 
https://www.youtube.com/watch?v=7ESIAl3CDEI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:02:29 </td>
   <td style="text-align:left;"> $TSLA need 50 point drop tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 04:02:10 </td>
   <td style="text-align:left;"> latexe7a37ea49239c6001d07868797447374, after Ukraine and inflation Fud we flying back to 1500$ 🐮🐮🐮🐮🐮🐮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:59:21 </td>
   <td style="text-align:left;"> $DCFC no brainer with this one. $CHPT $BLNK $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:57:29 </td>
   <td style="text-align:left;"> $REQ.X partnered with $TSLA to the moon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:57:11 </td>
   <td style="text-align:left;"> $SPY $TSLA Sunday night for so may couples.... $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:56:28 </td>
   <td style="text-align:left;"> $DWAC $tsla $twtr $fb Be afraid, be very afraid  https://twitter.com/ReformLewis/status/1492949863906086914 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:52:35 </td>
   <td style="text-align:left;"> $SNDL $BTC.X $TSLA $IDEX $WISH The FEAR INDEX will crash the market - Retail, doesn’t stand a chance because we don’t have access to the dark pool state of the art tech AND WE BELIEVE ANYTHING. I had Tesla shares at $400 and knew they would surpass $1k, I was sitting on them for months confident with my PT - What did I do I sold them when they were in the red for 2 months and let the FUD news and Chamath selling his shares finally get in my head, making a measly 15% profit, a month later it rose and continued to $1065+ which would of been life changing money for me SMDH. Back in now, but imagine if I stayed in at $400. FEAR destroys - remember that. 🔔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:52:02 </td>
   <td style="text-align:left;"> $GME $AMC $TSLA $SPY $SNDL

Powell’s gotta go to.  https://www.reddit.com/r/GME/comments/srqgm1/meet_the_american_angel_of_death_jerome_powell/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:51:20 </td>
   <td style="text-align:left;"> $TSLA How to know when to DCA in and When to DCA out ? WATCH THIS TO FIND OUT https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:50:38 </td>
   <td style="text-align:left;"> $TSLA  the war of bluff,  is gonna be bullish for tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:47:57 </td>
   <td style="text-align:left;"> $TSLA https://nypost.com/2022/02/13/ambassador-says-moscow-doesnt-give-a-s-t-about-sanctions/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:44:37 </td>
   <td style="text-align:left;"> $TSLA Reviews from our members!!⭐️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:42:18 </td>
   <td style="text-align:left;"> $TSLA Reviews on our discord!⭐️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:41:34 </td>
   <td style="text-align:left;"> $TSLA Reviews from our members⭐️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:40:41 </td>
   <td style="text-align:left;"> $TSLA any option traders / quants here?  IV looks a bit high in the near term but 850p / 900p  looked like a decent bet going out to 5/20... assuming you are bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:37:30 </td>
   <td style="text-align:left;"> $TSLA shots fired </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:37:07 </td>
   <td style="text-align:left;"> $TSLA bulls and bears just say random numbers based on nothing and it never pans out correctly. Gamblers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:34:42 </td>
   <td style="text-align:left;"> $RIVN

George Soros possibly taking $800 million loss on Rivian stock bought in Q4.

$AMZN $F $TSLA

https://www.reuters.com/business/autos-transportation/billionaire-soros-buys-stake-ev-startup-rivian-2022-02-11/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:31:49 </td>
   <td style="text-align:left;"> $TSLA $F $GM $RIVN  
 
https://www.youtube.com/watch?v=bSMJqNXmm80 
 
$ABML   It&amp;#39;s only a matter of time. 
 
You will all need us sooner than you think. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:31:15 </td>
   <td style="text-align:left;"> $TSLA Maybe I should shorting this into the ground ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:30:34 </td>
   <td style="text-align:left;"> $TSLA 1250$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:28:04 </td>
   <td style="text-align:left;"> $SPY Tits Up Monday!  BULLS are a dying breed☠️ in 2022, any analyst upgrade in BIG TECH will be Sold into -$TSLA $AAPL $AMZN $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:25:24 </td>
   <td style="text-align:left;"> $VUZI Seems like $AMZN &amp;amp; $WMT are taking action to make workers &amp;amp; their environments more efficient and safer.
VUZIX AR Smart Glasses will spread across the entire enterprise space like green on a golf course.
VUZI the $TSLA of AR

https://www.businessinsider.com/injury-rates-at-amazon-most-dangerous-warehouse-dupont-washington-2022-2

Very </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:22:28 </td>
   <td style="text-align:left;"> $TSLA Biden is a war monger.  He’s dumb and mean. He sucks. RUSSIAN s are nice fun people. They don’t want war. This whole thing is just a negotiator tool. For Russia to be able to sell fuel at higher prices.  Chill out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:15:51 </td>
   <td style="text-align:left;"> $dwac $tsla Trust The Rabbi!!!   https://twitter.com/BenRabizadeh/status/1492938507236618243 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-14 03:14:12 </td>
   <td style="text-align:left;"> $DWAC $TSLA $TWTR $FB  whoever this is, wow just wow.   
 
&amp;quot;Get out of my community pool with your unvaccinated tomfoolery&amp;quot;    
 
https://twitter.com/seriouspoolman/status/1492939175905083395 </td>
  </tr>
</tbody>
</table></div>

---
