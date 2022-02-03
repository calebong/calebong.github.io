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



Last Updated: 2022-02-03 09:04:06 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 08:54:12 </td>
   <td style="text-align:left;"> Nasdaq Futures Drop as Facebook Disappoints </td>
   <td style="text-align:left;"> US stock futures fell on Thursday as investors mulled a fresh batch of earnings results, including disappointing numbers from tech giant Meta Platforms. Nasdaq futures declined 2%, S&amp;P 500 futures fell 0.9% and Dow futures were flat. Shares of Facebook-parent Meta Platforms dropped nearly 23% in extended trading on lower-than-expected quarterly profits and on a weak revenue guidance for the current quarter. Other social media names declined including Snap (-17%) and Twitter (-8%) after the bell. Spotify also fell 10% on slowing premium subscriber growth. In regular trading on Wednesday, the major averages gained for a fourth straight session, with the S&amp;P 500 rising 0.94%, while the Dow climbed 0.63% and the Nasdaq edged up 0.5%. A 7.37% rally in Alphabet shares helped the indices, along with strong finishes from semiconductor names. Meanwhile, investors await the highly-anticipated nonfarm payroll due Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/building-permits </td>
   <td style="text-align:left;"> 2022-02-03 08:48:20 </td>
   <td style="text-align:left;"> Australia Building Permits Rise the Most in 9 Months </td>
   <td style="text-align:left;"> The seasonally adjusted estimate for total dwellings approved in Australia surged 8.2 percent month-over-month to 17,698 units in December 2021, quickening sharply from a 2.6 percent gain a month earlier, flash data showed. This was the second straight month of increase in building permits and the strongest pace since March, largely driven by a jump in approvals for private sector dwellings excluding houses, which rose 27.5 percent following a 13.4 percent rise in November. Meanwhile, private sector houses remained subdued, falling 1.8 percent following a 1.6 percent decline in November. Across Australia, dwelling approvals rose in New South Wales (32.1 percent), led by dwellings excluding houses and Victoria (2.5 percent); while fell in Queensland (-14.8 percent), Western Australia (-7.7 percent), Tasmania (-7.4 percent), and South Australia (-0.3 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/exports </td>
   <td style="text-align:left;"> 2022-02-03 08:48:08 </td>
   <td style="text-align:left;"> Australia Exports Rise to 4-Month High </td>
   <td style="text-align:left;"> Exports of goods and services from Australia grew 1 percent month-over-month to a four-month high of AUD 45.32 billion in December 2021, amid further solid global demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/balance-of-trade </td>
   <td style="text-align:left;"> 2022-02-03 08:40:00 </td>
   <td style="text-align:left;"> Australia Trade Surplus Smallest in 9 Months </td>
   <td style="text-align:left;"> Australia's trade surplus dropped to AUD 8.36 billion in December 2021 from an upwardly revised AUD 9.76 billion in the previous month. It was the smallest trade surplus since March, as imports rose more than imports, amid solid domestic demand ahead of year-end holidays. Exports grew 1 percent month-over-month to a 3-month high of AUD 45.32 billion and imports increased at a faster 5 percent to a record high of AUD 36.96 billion. Considering 2021 full year, the trade surplus surged to AUD 123.16 billion from AUD 72.10 billion in the same period of 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/imports </td>
   <td style="text-align:left;"> 2022-02-03 08:36:04 </td>
   <td style="text-align:left;"> Australia Imports Notch Fresh Record High </td>
   <td style="text-align:left;"> Imports of goods and services to Australia jumped 5% mom to a fresh peak of AUD 36.96 billion in December 2021, buoyed by solid domestic demand ahead of year-end holidays as strict lockdown measures in several key states eased following an acceleration in vaccinations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/02/middleeast/uae-drone-interception-intl/index.html </td>
   <td style="text-align:left;"> 2022-02-03 07:53:25 </td>
   <td style="text-align:left;"> UAE intercepts and destroys 3 'hostile' drones - CNN </td>
   <td style="text-align:left;"> Abu Dhabi, UAE (CNN)Three hostile drones were intercepted over the United Arab Emirates at dawn on Wednesday, the country's defense ministry said.                                                                                                                                                                                                                                                                 , The drones managed to penetrate Emirati airspace but were destroyed away from populated areas, the ministry said on Twitter.                                                                                                                                                                                                                                                                                       , It's unclear to whom the drones belonged. Yemen's Iranian-backed Houthi rebels, a possible culprit, have not claimed responsibility.                                                                                                                                                                                                                                                                               , The UAE is a member of the Saudi-led coalition that has been at war with the Houthis since 2015. The coalition has been fighting to restore Yemen's internationally recognized government after it was ousted by Houthi forces, who now control much of the country.                                                                                                                                               , In 2019, the UAE pulled most of its troops from Yemen, after privately deeming the war unwinnable. The campaign failed to crush the rebels and exacted a huge humanitarian toll.                                                                                                                                                                                                                                   , The UAE had largely avoided the firing line, with Houthis opting instead to strike Saudi Arabia until recently. The Houthis have launched a series of attacks on the Emiratis, beginning with a January 17 drone strike that killed three foreign workers in the capital, Abu Dhabi. The Saudi-led coalition responded with a weeklong offensive in Yemen, killing scores of people and knocking out the internet. , In recent days, Houthi forces have launched several ballistic missiles aimed at US and UAE forces deployed in the country -- including one attack that came during Israeli President Isaac Herzog's historic visit to the country. The missiles launched in those attacks were intercepted by US-deployed Patriot missile defense systems, and there were no casualties.                                           , On Tuesday, US Defense Secretary Lloyd Austin told Abu Dhabi's Crown Prince Sheikh Mohammed Bin Zayed that the US would be deploying fifth-generation fighters to assist against the Houthi threat. The move was welcomed by the UAE.                                                                                                                                                                              , The UAE has also been lobbying the US to redesignate the Houthis as a foreign terror organization, which US President Joe Biden said is "under consideration."                                                                                                                                                                                                                                                     , January's attacks have surprised residents of the UAE. Abu Dhabi has repeatedly been ranked one of the safest cities in the world. For decades, the UAE staved off turbulence in a crisis-ridden region, attracting millions of expatriates and large volumes of foreign investment.                                                                                                                               , CNN's Becky Anderson contributed reporting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60238565?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-03 07:34:19 </td>
   <td style="text-align:left;"> Facebook owner Meta warns advertising is slowing </td>
   <td style="text-align:left;"> Facebook-owner Meta has warned of slowing growth, as audiences flock to competitors like TikTok and the businesses that advertise on its platforms cut marketing budgets.                                                                                                                                                                                                         , The firm said sales growth could be just 3% in the first three months of 2022, far below its historic pace.                                                                                                                                                                                                                                                                       , Profits have already been hit as the firm ploughs money into projects focused on virtual reality.                                                                                                                                                                                                                                                                                 , The update sent shares down 20% in after-hours trade.                                                                                                                                                                                                                                                                                                                             , The sell-off spread to similar companies, like Snap, which also saw its shares plunge.                                                                                                                                                                                                                                                                                            , Analysts had been expecting Meta to report strong numbers, after Google-owner Alphabet shared its results yesterday.                                                                                                                                                                                                                                                              , The search giant, which also relies on advertising, reported revenues and profits that rose more than 30%.                                                                                                                                                                                                                                                                        , But Meta - the parent company of Facebook, Instagram and WhatsApp - has seen its dominance of social media challenged by companies like TikTok, known for its 30-second videos.                                                                                                                                                                                                   , Meta boss Mark Zuckerberg said the firm's sales growth had been hurt as audiences - especially younger users - left for rivals.                                                                                                                                                                                                                                                   , More than 2.8 billion people used one of its apps daily in December, but growth has slowed.                                                                                                                                                                                                                                                                                       , While the company has been making its own investments in video to compete with TikTok, it makes less money from those offerings than its traditional Facebook and Instagram feeds.                                                                                                                                                                                                , Mr Zuckerberg said he was confident the investments in video and virtual reality would pay off, as previous bets on mobile advertising and Instagram stories have.                                                                                                                                                                                                                , But, he noted, the firm didn't have to contend with a major rival during previous shifts in strategy.                                                                                                                                                                                                                                                                             , "The teams are executing quite well and the product is growing very quickly," he said. "The thing that is somewhat unique here is that TikTok is so big a competitor already and also continues to grow at quite a fast rate."                                                                                                                                                    , In its forecast for investors on Wednesday, Meta said it expected revenue growth of between 3% and 11% in the first three months of 2022.                                                                                                                                                                                                                                         , As well as the threat from TikTok, that slowdown at least partly reflects bigger economic issues, executives said.                                                                                                                                                                                                                                                                , "We're hearing from advertisers that macroeconomic challenges like cost inflation and supply chain disruptions are impacting advertiser budgets," the firm added.                                                                                                                                                                                                                 , The update added to questions facing Mr Zuckerberg over his bet on the so-called "Metaverse" - an online world where people can game, work and communicate in a virtual environment, often using virtual reality headsets.                                                                                                                                                        , The firm's Reality Labs unit, which focuses on virtual reality, lost more than $10bn last year.                                                                                                                                                                                                                                                                                   , "It's clear that there are many big roadblocks ahead as Meta faces tough new competition for ad revenue such as TikTok, and as it contends with ongoing ad targeting and measurement challenges from Apple's iOS changes," said Insider Intelligence analyst Debra Aho Williamson, referring to changes made by Apple that make it harder to target ads on Facebook and Instagram., "In addition, there's a lot of uncertainty about Meta's investments in the metaverse and if or when they will have a positive impact on the company's bottom line."                                                                                                                                                                                                               , Meta revenues in the last three months of 2021 topped $33.6bn (£24.8bn), up 20% year-on-year. But expenses rose almost twice as fast, to $21bn.                                                                                                                                                                                                                                   , Some of those costs were due to increased legal expenses, as the firm fights lawsuits, including from regulators that it runs a social media monopoly.                                                                                                                                                                                                                            , Profits in the quarter dropped 8% compared to the year before, falling to $10.3bn.                                                                                                                                                                                                                                                                                                , How one ship triggered a global crisis...                                                                                                                                                                                                                                                                                                                                         , An extraordinary family and their passion for climbing                                                                                                                                                                                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/oil-edges-lower-as-traders-digest-opec-decision-to-add-barrels?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-03 07:33:42 </td>
   <td style="text-align:left;"> Oil Edges Lower as Traders Digest OPEC+ Decision to Add Barrels </td>
   <td style="text-align:left;"> Jake Lloyd-Smith                                                                                                                                                                                                                                                                              , Oil eased from a seven-year high as traders waited to see whether OPEC+ can deliver on a promised increase in supply.                                                                                                                                                                         , West Texas Intermediate edged lower in early Asian trading after almost striking $90 a barrel on Wednesday. While the Organization of Petroleum Exporting Countries and its allies agreed midweek to lift output, traders are doubtful that all its members will be able to meet their quotas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/policy-normalization-bets-reach-japan-s-shore-as-rates-turn-zero?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-03 07:32:46 </td>
   <td style="text-align:left;"> Policy Normalization Bets Reach Japan’s Shore as Rates Turn Zero </td>
   <td style="text-align:left;"> Masahiro Hidaka                                                                                                                                                                                                                                                                   ,  and Masaki Kondo                                                                                                                                                                                                                                                                 , Speculation of monetary policy normalization has reached Japan.                                                                                                                                                                                                                   , Two-year overnight-indexed yen swaps this week breached zero for the first time since 2016 -- the year the Bank of Japan introduced its negative interest rate policy. The sometime proxy for investor expectations of future policy rates has risen three basis points this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/02/europe/frozen-migrants-turkey-greece-intl/index.html </td>
   <td style="text-align:left;"> 2022-02-03 07:02:33 </td>
   <td style="text-align:left;"> 12 people found frozen to death, sparking diplomatic row between Turkey and Greece - CNN </td>
   <td style="text-align:left;"> Istanbul (CNN)Twelve migrants were found dead in a small Turkish town near the border with Greece, officials said Wednesday, a week after a rare winter storm blanketed both countries in snow.                                                                                                             , Turkish Interior Minister Suleyman Soylu said the dozen migrants froze to death in Ipsala, a border town often used by migrants seeking to enter the European Union.                                                                                                                                        , Where the migrants came from and why they were stranded in frigid conditions remains unclear, but Greece and Turkey have blamed each other for the tragedy.                                                                                                                                                 , Soylu alleged on Twitter that the group was turned away by Greek border officials and stripped of their shoes and clothing. He tweeted blurred images that appeared to show the dead bodies of at least eight individuals, partially clothed and lying in the mud.                                          , Soylu called the Greek border patrol and units thugs, and said the European Union was "remediless, weak and void of humane feelings."                                                                                                                                                                       , Greek Immigration Minister Notis Mitarachi, however, denied Soylu's allegations of wrongdoing.                                                                                                                                                                                                              , "The death of 12 migrants on the Turkish border near Ipsala is a tragedy," he said in a statement. "But the truth behind this incident bears no resemblance to the false propaganda pushed out by my counterpart."                                                                                          , Mitarachi said that the migrants "never made it to the border."                                                                                                                                                                                                                                             , "Any suggestion they did, or indeed were pushed back into Turkey is utter nonsense," he said. "Rather than pushing out unfounded claims Turkey needs to live up to its obligations and work to prevent these dangerous journeys."                                                                           , The Greek foreign ministry did not immediately respond to CNN's request for comment about Turkey's allegations.                                                                                                                                                                                             , The 12 migrants were part of a group of 22. Regional authorities said in a statement that they are still searching for the remaining 10 and that they have opened an investigation into the incident,                                                                                                       , The Council of Europe and migrants themselves have for years alleged that the Greek Coast Guard and border patrols push back migrants, sometimes at sea. Though the United Nations Human Rights Agency has documented "credible reports" of such incidents, the Greek government has repeatedly denied them., CNN's Sugam Pokharel contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/02//stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-02-03 07:02:09 </td>
   <td style="text-align:left;"> Nasdaq futures drop as Facebook leads tech shares lower </td>
   <td style="text-align:left;"> , U.S. stock futures fell Wednesday night, as traders pored through the latest batch of corporate earnings, which included disappointing numbers from tech giant Meta Platforms.                                                               , Futures tied to the Nasdaq 100 dropped 2.3%, and S&amp;P 500 futures slid 1%. Dow Jones Industrial Average futures slid 35 points, or 0.1%.                                                                                                      , Shares of Facebook-parent Meta Platforms plunged more than 21% in after-hours trading after the company's quarterly profit fell short of expectations. The company also issued weaker-than-expected revenue guidance for the current quarter., "There was a lot to not like" from Meta's report, Metropolitan Capital Advisors CEO Karen Finerman told CNBC's "Fast Money." She noted that the company's revenue growth expectations were the "spookiest" part of the release.              , However, Finerman added that the move down seems a "little overdone."                                                                                                                                                                        , Other social media names, including Snap and Twitter, followed Facebook shares lower. Snap shares slid 16% after the bell, and Twitter dropped more than 8%.                                                                                 , Spotify Technology, meanwhile, fell 10.2% after the company's latest quarterly figures showed a slowdown in premium subscriber growth.                                                                                                       , Wednesday night's moves come after the major averages notched a four-day winning streak during the regular session.                                                                                                                          , The Dow jumped more than 200 points on the day, while the S&amp;P 500 and Nasdaq Composite advanced 0.9% and 0.5%, respectively. Those gains were driven by a jump in tech shares, which were led by a 7.3% rally in Alphabet shares.            , These tech stocks look cheap after the January rout, based on their growth prospects                                                                                                                                                         , Cathie Wood is buying Tesla again after steadily trimming position for months                                                                                                                                                                , These are JPMorgan's top stocks for February                                                                                                                                                                                                 , Fundstrat's Tom Lee says get ready for a 'violent rally' in February                                                                                                                                                                         , That four-day jump has helped the major averages trim some of their steep losses after a downbeat January. Last month's declines came as traders braced for potential rate hikes from the Federal Reserve.                                   , "It's been a crazy, volatile environment, which is what happens when you're in this transition period of monetary policy and economic growth," Canaccord's Tony Dwyer told CNBC's "Closing Bell."                                            , On the economic data front, investors will keep an eye out for the latest weekly U.S. jobless claims numbers. Economists polled by Dow Jones expect initial claims to have fallen to 245,000 from 260,000.                                   , Those numbers will follow the release of surprisingly downbeat private payrolls data. ADP said Wednesday that U.S. private payrolls dropped by 301,000 in January, while economists polled by Dow Jones had forecast a gain of 200,000.      , Subscribe to CNBC PRO for exclusive insights and analysis, and live business day programming from around the world.                                                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-02-03 06:57:21 </td>
   <td style="text-align:left;"> Brazilian Real Steady Around 4-1/2-Month High </td>
   <td style="text-align:left;"> The Brazilian Real traded below $5.30, the strongest since the mid-September, amid a weaker dollar and higher iron ore prices. Iron ore, a major Brazil’s export, rose to above $140 a tonne, the highest since the beginning of September 2021. Meanwhile, domestically, the Central Bank of Brazil has raised the borrowing costs by 150 bps to 10.75%, as expected, while pointed out that the tightening cycle will continue in the next meeting, although at a slower pace. Since April last year, COPOM has raised the main Selic rate by 875 bps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/02/arts/design/gold-cube-niclas-castello.html </td>
   <td style="text-align:left;"> 2022-02-03 06:55:49 </td>
   <td style="text-align:left;"> It’s Gold, Baby. But Niclas Castello’s Cube Is Nothing New in Art. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Art Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The artist’s solid gold cube, which appeared for one day in Central Park, was Instagram bait, an NFT promotion and even kind of pretty.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , By Will Heinrich                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Videos by Sam Youkilis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The fun thing about conceptual art is that it’s totally easy to create. You can say something about the increasingly virtual way many of us experience the world, and the explosive popularity of NFTs (nonfungible tokens) — or seem to say something profound, anyway — just by staging a Central Park happening around a knee-high cube of solid gold.                                                                                                                                                                                                                                                                                                                                                                                                                   , At least, that’s what the German pop artist Niclas Castello has done. His “Castello Cube,” cast from more than $10 million worth of 24-karat Nevadan gold, appeared in a patch of icy slush opposite the Naumburg Bandshell on Wednesday, preceded by an over-the-top marketing campaign that included a wraparound ad in that morning’s edition of The New York Times. Related NFTs from the artist and even a new digital currency, Castello Coin, will drop later in the month. The artist did privately presell enough of the coins to finance this project, according to Marina Dertnig, a member of the production team. But Castello, 43, underlined the rarity of the actual cube by displaying it for only a single day, and by promising that it wouldn’t be sold., When I visited, the cube was surrounded by a steady trickle of gawkers, some of whom had come to see the art and others drawn by the crowd itself. “I love a group of people staring at a box,” said Isabel Robin, an actor and tour guide.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , After all, the last time New Yorkers got to see a sizable chunk of solid gold in public was in 2016-2017, when Maurizio Cattelan installed his 18-karat gold toilet, “America,” at the Guggenheim Museum.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Some visitors in Central Park were swayed by the beauty of the material. “The reflections are incredible,” said Brigitte Bentele, a watercolorist and retired educator, “and putting it there in the snow seems really inspired.” Others, like a private security guard, Jamel Rabel, were dismayed by the gap between the hyperbolic advertisements for the piece — “Never before in the history of humanity has such an enormous amount of gold been cast into a single, pure object” — and its rather more modest presence. “It’s pretty plain,” he said.                                                                                                                                                                                                                , I’d say they’re both right. From a few feet away, the top face of the cube looked as slippery and delicate as a sheen of rainwater, reflecting the tree line. Stepping in close, I found a few little black marks left in the soft metal by the compressed sand in which the cube had been molded in Aarau, Switzerland. When the artist’s crew set up pink lights for their camera, the cube seemed to change color from dusky copper to bright yellow. The edges looked sharp but also, somehow, giving. There’s a reason people like gold.                                                                                                                                                                                                                               , Castello, who hung out at the site, was chic in black, with long hair and bright blue glasses. In the past, he created what he called “cube paintings” with canvases crumbled inside acrylic, and was involved in the European street art movement.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , But does his current public work add anything to what the Romanian-born sculptor Constantin Brancusi already said about shiny surfaces in the 1920s-30s with his gorgeous abstracted bronze birds? Or to Donald Judd’s exhaustive exploration of cubes in the 1960s? Does a one-day-only pop-up display really update 1960s happenings in the Sheep Meadow, or the release of a limited-edition Supreme T-shirt, in any meaningful sense? Can it compete with the majestic lines of the saffron-orange gates Christo erected in Central Park in 2005? Does it elucidate the tension between aesthetic and commodity value, or offer a fresh insight on the gold standard 50 years after Nixon junked it?                                                                    , What the “Castello Cube” really speaks to is the self-sustaining power of capital. If you have the resources to get hold of $10 or $11 million dollars’ worth of gold from a UBS Bank in Switzerland — as Castello did — and then pay a centuries-old bell foundry there to shape it into a cube, and finally to ship this cube to the most visible park in the finance capital of the Western world, you can get people to look at it, talk about it and review it — and then, in what is shaping up to be the new gold standard, sell the whole experience as an NFT.                                                                                                                                                                                                     , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/stock-rally-may-falter-on-toll-from-mixed-earnings-markets-wrap </td>
   <td style="text-align:left;"> 2022-02-03 06:29:21 </td>
   <td style="text-align:left;"> Nasdaq Futures Drop 2% on Dim Earnings; Yields Dip: Markets Wrap </td>
   <td style="text-align:left;"> Sunil Jagtiani                                                                                                                                                                                                                 , The rally in global stocks faltered Thursday following disappointing earnings from technology bellwethers and as traders await more clues on how quickly key central banks will tighten monetary policy.                       , U.S. equity futures dropped, with contracts on the technology-heavy Nasdaq 100 down some 2%, after Facebook parent Meta Platforms Inc. and streaming service Spotify Technology SA plunged in late trading on soggy forecasts.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/services-sentiment </td>
   <td style="text-align:left;"> 2022-02-03 06:14:11 </td>
   <td style="text-align:left;"> Australia Services Sector Plunges into Contraction </td>
   <td style="text-align:left;"> The IHS Markit Australia Services PMI was upwardly revised to 46.6 in January of 2022, after a flash estimate pointed to a read of 45, pointing to the first contraction in the services sector in four months with both services demand and activity declining amid the surge in COVID-19 infections. Still, service providers continued to expand their workforce, while, lingering supply issues caused backlogged work to continue accumulating, at the same time that prices rose. Overall optimism eased amid COVID-19 uncertainties. The deterioration of COVID-19 conditions in Australia led to demand falling at the start of the year. Fear surrounding the resurgence in COVID-19 cases contributed to lower services consumption. As a result, services output eased sharply with sub-sector data showing Real Estate &amp; Business Services leading the drop. Foreign demand was similarly affected, falling at a faster rate in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/composite-pmi </td>
   <td style="text-align:left;"> 2022-02-03 06:08:53 </td>
   <td style="text-align:left;"> Australia Markit Composite PMI Sinks On January </td>
   <td style="text-align:left;"> The IHS Markit Australia Composite PMI was upwardly revised to 46.7 in January of 2022, after a flash estimate pointed to a read of 45.3, still, the private sector output shrank sharply, pointing to the first contraction in four months due to the latest surge in COVID-19 infections as operations were disrupted. Both manufacturing and service sectors output declined in January amid the surge in COVID-19 infections. Meanwhile, expansion of workforce numbers nevertheless continued across both the manufacturing and service sectors, albeit at slower rates with firms facing difficulties in hiring. Price pressures meanwhile worsened, particularly in the service sector. Overall sentiment remained positive across both the manufacturing and service sectors in January, though the level of optimism eased across both sectors with concerns of the negative COVID-19 impacts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/american-dream-mall-drains-reserves-to-pay-muni-sales-tax-bonds?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-03 06:07:02 </td>
   <td style="text-align:left;"> American Dream Mall Drains Reserves to Pay Muni Bonds </td>
   <td style="text-align:left;"> Martin Z Braun                                                                                                                                                                                                                                                                                                                                                                                                                                                           , American Dream, the $5 billion super mall in New Jersey’s Meadowlands, drained a reserve fund to make a bond payment as it struggles to attract shoppers and tenants with the pandemic set to begin its third year.                                                                                                                                                                                                                                                      , The 3.5-million-square-foot shopping and entertainment complex, which features an indoor ski slope, amusement park and water park, nearly emptied a reserve account to make a $9.3 million payment due Tuesday on about $290 million of debt supported by sales tax receipts, according to a securities filing. About $820 is left in the reserve fund, the filing said. It’s not clear whether American Dream will make its next payment on the securities, due Aug. 1.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/02/stocks-making-the-biggest-moves-after-the-bell-facebook-qorvo-more.html </td>
   <td style="text-align:left;"> 2022-02-03 06:06:37 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after the bell: Facebook, Spotify, Qorvo &amp; more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                     , Check out the companies making headlines after the bell Wednesday:                                                                                                                                                                                                                                                  , Meta Platforms — Shares of the Facebook parent plunged more than 22% on the back of disappointing quarterly earnings. Meta reported earnings per share of $3.67, while analysts polled by Refinitiv expected a profit of 3.84 per share. The company's current-quarter revenue guidance was also below expectations., Qualcomm — Qualcomm shares whipsawed after the semiconductor maker posted better-than-expected results for the previous quarter. The company posted earnings of $3.23 per share on revenue of $10.7 billion. Analysts expected earnings of $3.01 per share on revenue of $10.42 billion, according to Refinitiv.    , Align Technology — Align Technology reported a fourth-quarter profit that was above expectations. The company earned an adjusted $2.83 per share, topping a StreetAccount estimate of $2.74 per share. Still, shares fell about 5% after hours.                                                                     , Spotify Technology — Shares of the audio streaming company dropped more than 11%, after the company's quarterly numbers showed a slowdown in subscriber growth. Spotify said premium subscribers grew by 16% year over year in the fourth quarter. That growth rate is down from 19% in the third quarter.          , Qorvo — Qorvo shares dropped about 4% on the back of mixed quarterly results. The chipmaker earned $2.98 per share in the previous quarter, topping a Refinitiv estimate of $2.76 per share. However, the company's revenue of $1.11 billion was in line with expectations.                                         , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/meta-s-earnings-flop-threatens-to-derail-nasdaq-100-rebound?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-03 05:58:58 </td>
   <td style="text-align:left;"> Meta’s Earnings Flop Threatens to Derail Nasdaq 100 Rebound </td>
   <td style="text-align:left;"> Jeran Wittenstein                                                                                                                                                                                                                                                                                                                                                                            , An ugly forecast from Facebook parent Meta Platforms Inc. is threatening a rebound in the Nasdaq 100 Stock Index that’s been fueled by strong earnings reports from its megacap peers. It would also set a grim historical milestone.                                                                                                                                                        , The social media giant’s warning on Wednesday afternoon that it’s facing numerous challenges to growth sent its stock tumbling about 22% as of 5:30 p.m. in New York, and rippled through other technology stocks. An exchange-traded fund tracking the Nasdaq 100 fell about 1.8% in postmarket trading. The tech-heavy index has gained 8.1% after closing at a seven-month low on Jan. 27. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/t-mobile-rallies-after-q4-profit/story.aspx?guid={3BCAB658-84E7-4564-BDA0-3B97586B5AE8}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-03 05:58:34 </td>
   <td style="text-align:left;"> T-Mobile rallies after Q4 profit beat - MarketWatch </td>
   <td style="text-align:left;"> Shares of T-Mobile US Inc. 
        TMUS,
        +0.03%
       rallied more than 7% late Wednesday after the telecommunications company reported fourth-quarter per-share profit well above expectations and sales that fell slightly short. T-Mobile said it earned $422 million, or 34 cents a share, in the quarter, compared with $750 million, or 60 cents a share, in the year-ago quarter. The company pinned the earnings drop mostly on an expected increase in costs related to its merger with Sprint. Revenue rose to $20.8 billion, from $20.3 billion a year ago. Analysts polled by FactSet expected T-Mobile to report earnings of 15 cents a share on sales of $21 billion. "We didn't just meet the bold goals we set for 2021 ... we crushed all of them," Chief Executive Mike Sievert said in a statement. "With plenty of room to run, we're in the best-ever position to continue delivering." The company guided for net customer additions of postpaid customers between 5 million and 5.5 million for 2022. T-Mobile stock ended the regular trading day up 0.1%. , The Google parent reported fourth-quarter sales of $75.3 billion, up 32% year over year. The company also announced a 20-for-1 stock split.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/facebook-stock-inflation-zuckerberg-meta </td>
   <td style="text-align:left;"> 2022-02-03 05:52:24 </td>
   <td style="text-align:left;"> Inflation hits Facebook, stock tanks </td>
   <td style="text-align:left;">  I/O Fund Official technology analyst Beth Kindig provides insight on the stock market on 'Making Money.'                                                                                                                                                                                   , Meta Platforms, formerly Facebook, is the latest casualty tied to inflation, and shares plummeted in the extended session.                                                                                                                                                                  , "We're hearing from advertisers that macroeconomic challenges like cost inflation and supply chain disruptions are impacting advertiser budgets," the company disclosed in its fourth-quarter earnings release.                                                                             , INFLATION SURGES 7% IN DECEMBER, HIGHEST IN 40 YEARS                                                                                                                                                                                                                                        , The stock traded as low as $257.65 as of 4:40 p.m. ET on Wednesday, off over 20%, after closing at $323 per share.                                                                                                                                                                          , WHERE PRICES ARE HITTING AMERICANS THE HARDEST                                                                                                                                                                                                                                              , In the fourth quarter, net income fell to $10.2 billion from $11.2 billion during the same period a year ago, or $3.67 versus $3.88 per share. Revenue rose to $33.6 billion from $28 billion a year ago.                                                                                   , Daily active users rose 5%, or 1.93 billion.                                                                                                                                                                                                                                                , Revenue for the first quarter will range between $27 billion and $29 billion, below the $30 billion or so analysts were expecting.                                                                                                                                                          , Other social media stocks fell in sympathy including Twitter, Snapchat and Pinterest.                                                                                                                                                                                                       ,   (DREW ANGERER/POOL/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                                   , CEO Mark Zuckerberg described the quarter as "solid" and highlighted key priorities for 2022.                                                                                                                                                                                               , "I'm encouraged by the progress we made this past year in a number of important growth areas like Reels, commerce, and virtual reality, and we'll continue investing in these and other key priorities in 2022 as we work towards building the metaverse," he said in the earnings release. , Facebook ended the 2021-year dealing with a public relations crisis after whistle-blower Francis Haugen went public with allegations that the tech giant ignored questionable and harmful content to focus on profits, among other things. Facebook disputed many of her claims.            , Haugen released a trove of documents related to her claims to multiple news organizations at the same time, including FOX Business.                                                                                                                                                         , Additionally, the company's ticker FB will change to META in the first half of the year while continuing its listing on the Nasdaq.   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/interest-rate </td>
   <td style="text-align:left;"> 2022-02-03 05:52:00 </td>
   <td style="text-align:left;"> Brazil Hikes Interest Rate to 10.75% as Expected </td>
   <td style="text-align:left;"> The Central Bank of Brazil unanimously decided to raise the Selic rate by 150 basis points to 10.75% on February 2nd, as expected. It was the eighth consecutive interest rate hike since it has started tightening, while the policymakers see another interest rate increase but by at a lower amount at the next meeting. The committee kept mentioning that accordingly to the balance of risk it is appropriate for the tightening cycle to advance significantly into the restrictive scenario, in order to consolidate a disinflation process and anchor the expectations. Both the forecasts from the monetary authority and the market participants show that inflation in 2022 could come at 5.4%, above the upper bound of the central bank target (5%). Meanwhile, recent growth indicators released for the last quarter of 2021 showed a slightly better than expected performance for the economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/02/technology/meta-facebook-earnings-metaverse.html </td>
   <td style="text-align:left;"> 2022-02-03 05:33:21 </td>
   <td style="text-align:left;"> Meta Spent $10 billion on the Metaverse in 2021, Dragging Down Profit - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Quarterly profits decreased 8 percent, to $10.3 billion, from a year earlier. Shares of Meta’s stock plunged about 22 percent in after-hours trading.                                                                                                                                                                                                                                                                                                                                                                                                , By Mike Isaac                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Mark Zuckerberg said his company was going all in on the metaverse last year. On Wednesday, he showed the costs of making that transition.                                                                                                                                                                                                                                                                                                                                                                                                           , Meta, the company that Mr. Zuckerberg founded as Facebook, said that its Reality Labs division, which makes virtual-reality goggles, smart glasses and other yet-to-be-released products, lost more than $10 billion in 2021 as it built the business. Those products are key to Mr. Zuckerberg’s vision of the metaverse, a next generation of the internet where people would share virtual worlds and experiences across different software and hardware platforms.                                                                               , It was the first time that Meta revealed the results of its hardware division. In the past, the company had not broken out those numbers because products like virtual-reality headsets were a small part of its overall business, which is dependent on social networking and digital advertising. Investing $10 billion in the metaverse is more than five times the amount of money Facebook paid to purchase the Oculus VR business in 2014 and 10 times what it paid to buy Instagram in 2012.                                                  , The spending dragged down Meta’s quarterly profits, which fell 8 percent, to $10.3 billion, in the three months ending in December from a year earlier, even as revenue rose 20 percent, to $33.7 billion, over the same period. Wall Street analysts had predicted profit of $10.9 billion on revenue of $33.4 billion.                                                                                                                                                                                                                             , At the same time, Meta said its social networking businesses — such as Facebook and Instagram — were being buffeted by another shift made by a rival tech giant. Meta said it expected its financial performance to be hurt by Apple’s changes to its mobile operating system, in which the iPhone maker made it more difficult last year for apps to track iPhone users’ digital habits. The move has affected social networking companies because it has given them less data to use for serving people targeted ads.                              , The higher spending on the metaverse and the effect of Apple’s changes have combined to create a difficult transition period for Facebook as it transforms into Meta. The results were highly unusual for a company that for years has churned out stellar financial performances like clockwork, powering through scandals about privacy and misinformation and other toxic content. On Wednesday, in response to the earnings report, Meta’s shares plunged about 22 percent in after-hours trading.                                               , “It is time for a reality check on Meta’s position for the metaverse,” said Raj Shah, a technology analyst for Publicis Sapient, a digital consultancy firm. “The metaverse is a long way from being profitable or filling the gap in ad revenue after Apple’s policy change.”                                                                                                                                                                                                                                                                       , In a call with investors after disclosing Meta’s results, Mr. Zuckerberg, Meta’s chief executive, appeared to acknowledge the difficulties. “Although our direction is clear, it seems that our path ahead is not quite perfectly defined,” he said.                                                                                                                                                                                                                                                                                                 , But he also defended the shift toward the metaverse and said his company had weathered challenges before. “Ultimately, our continued success relies on building products that people find valuable and that people want to use,” Mr. Zuckerberg said.                                                                                                                                                                                                                                                                                                , For years, Meta has tried to become less dependent on Apple, which holds the key to iPhone users, and to shift away from social networking controversies involving misinformation and hate speech. So in October, Mr. Zuckerberg announced that he planned for his company to take a new path toward the metaverse. He renamed Facebook as Meta. Since then, the company has embarked on a sweeping internal transformation, restructuring itself and pushing employees to join teams working on augmented reality and virtual reality.              , Meta’s spending is unlikely to subside anytime soon, especially as it is in a full-throttled race against other technology giants to claim ground in the theoretical metaverse. Last month, when Microsoft said it was buying the video game maker Activision Blizzard for nearly $70 billion, the software maker cited the deal as a building block for the metaverse, even though Activision does not produce virtual reality games. Google has been working on metaverse-related technology for years, and Apple has its own devices in the works., At the same time, Meta’s wildly profitable businesses are in a period of change. Sheryl Sandberg, Meta’s chief operating officer, said on the call with investors Wednesday that Instagram was heavily promoting a video product called Reels, which competes with TikTok. While Reels is the biggest contributor to Instagram’s growth, it does not make as much money from ads as other Instagram products like Stories and the main photo feed.                                                                                                   , In the call, Mr. Zuckerberg also pointed to the difficulties of competing with TikTok, which has grown increasingly popular with younger audiences. David Wehner, Meta’s chief financial officer, added that Apple’s iOS changes buoyed the ad business of Google, which is not dependent on Apple for advertising data.                                                                                                                                                                                                                             , The origins. The word “metaverse” describes a fully realized digital world that exists beyond the one in which we live. It was coined by Neal Stephenson in his 1992 novel “Snow Crash,” and the concept was further explored by Ernest Cline in his novel “Ready Player One.”                                                                                                                                                                                                                                                                       , An expanding universe. The metaverse appears to have gained momentum during the online-everything shift of the pandemic. The term today refers to a variety of experiences, environments and assets that exist in the virtual space.                                                                                                                                                                                                                                                                                                                 , Some examples. Video games in which players can build their own worlds have metaverse tendencies, as does most social media. If you own a non-fungible token, virtual-reality headset or some cryptocurrency, you’re also part of the metaversal experience.                                                                                                                                                                                                                                                                                         , How big Tech is shifting. Facebook staked its claim to the metaverse last year, after shipping 10 million of its virtual-reality headsets and announcing it had renamed itself Meta. Google, Microsoft and Apple have all been working on metaverse-related technology.                                                                                                                                                                                                                                                                              , The future. Many people in tech believe the metaverse will herald an era in which our virtual lives will play as important a role as our physical realities. Some experts warn that it could still turn out to be a fad or even dangerous.                                                                                                                                                                                                                                                                                                           , Alphabet, Google’s parent company, on Tuesday reported a 36 percent increase in profit and a 32 percent jump in revenue in the last three months of 2021 from a year earlier.                                                                                                                                                                                                                                                                                                                                                                        , Still, the number of users for Meta’s social networking apps continued to rise. The monthly active users of Facebook, Instagram, WhatsApp and other apps increased 9 percent, to 3.59 billion, in the quarter from a year earlier, the company said. The company added that more than one billion users interact with business accounts using services such as WhatsApp and Messenger every week.                                                                                                                                                    , Yet the main Facebook app appeared to hit a ceiling in at least some markets; the app lost one million users globally for the first time in the quarter, down from the prior quarter.                                                                                                                                                                                                                                                                                                                                                                , Meta also announced plans to change its stock ticker so that its shares would trade under the symbol META on the Nasdaq exchange instead of FB.                                                                                                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/costco-january-sales-gets-boost/story.aspx?guid={8D26573A-60F2-48D4-A7B9-E2A400FB7B6F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-03 05:31:25 </td>
   <td style="text-align:left;"> Costco January sales gets boost from early Lunar New Year holiday - MarketWatch </td>
   <td style="text-align:left;"> Costco Wholesale Corp. 
        COST,
        +2.68%
       said late Wednesday its January sales rose 15.5% to $15.76 billion, from $13.64 billion in January 2021. January sales got a boost from an earlier Lunar New Year in 2022. The holiday, celebrated Feb. 1, fell 11 days earlier this year, a shift that "favorably impacted" January sales outside of the U.S. and Canada by about 4% and total sales by about 0.5%, Costco said. Same-store sales rose 14.2% in January and e-commerce comparable sales rose 9%, the retailer said. Shares of Costco were up a fraction in the extended session after ending the regular trading day up 2.7%. , Alphabet's stock price will drop to around $148 based on the current stock price when the split becomes effective in July.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/qcom:us </td>
   <td style="text-align:left;"> 2022-02-03 05:29:45 </td>
   <td style="text-align:left;"> Qualcomm earnings above expectations at 3.23 USD </td>
   <td style="text-align:left;"> Qualcomm (QCOM) released earnings per share at 3.23 USD, compared to market expectations of 3.00 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/met:us </td>
   <td style="text-align:left;"> 2022-02-03 05:28:03 </td>
   <td style="text-align:left;"> MetLife earnings above expectations at 2.17 USD </td>
   <td style="text-align:left;"> MetLife (MET) released earnings per share at 2.17 USD, compared to market expectations of 1.47 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/tmus:us </td>
   <td style="text-align:left;"> 2022-02-03 05:25:27 </td>
   <td style="text-align:left;"> T-Mobile Us earnings above expectations at 0.34 USD </td>
   <td style="text-align:left;"> T-Mobile Us (TMUS) released earnings per share at 0.34 USD, compared to market expectations of 0.13 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mck:us </td>
   <td style="text-align:left;"> 2022-02-03 05:24:48 </td>
   <td style="text-align:left;"> McKesson earnings above expectations at 6.15 USD </td>
   <td style="text-align:left;"> McKesson (MCK) released earnings per share at 6.15 USD, compared to market expectations of 5.42 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 05:24:42 </td>
   <td style="text-align:left;"> Stocks in Canada Extend 4-Day Rally </td>
   <td style="text-align:left;"> The S&amp;P/TSX rose 0.2% to close at 21,362 on Wednesday, tracking US stocks higher and extending gains for the 4th consecutive session as consumer staples, industrials, financials, and energy stocks boosted the gains, while tech and healthcare stocks plunged more than 2% capping additional gains. Meanwhile, protests against the anti-vaccine mandate and other COVID-19 restrictions continue in Ottawa are causing outrages and business closures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/algn:us </td>
   <td style="text-align:left;"> 2022-02-03 05:24:23 </td>
   <td style="text-align:left;"> Align Technology earnings above expectations at 2.83 USD </td>
   <td style="text-align:left;"> Align Technology (ALGN) released earnings per share at 2.83 USD, compared to market expectations of 2.75 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/afl:us </td>
   <td style="text-align:left;"> 2022-02-03 05:24:05 </td>
   <td style="text-align:left;"> Aflac earnings above expectations at 1.28 USD </td>
   <td style="text-align:left;"> Aflac (AFL) released earnings per share at 1.28 USD, compared to market expectations of 1.26 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/fb:us </td>
   <td style="text-align:left;"> 2022-02-03 05:23:30 </td>
   <td style="text-align:left;"> Meta earnings below expectations at 3.67 USD </td>
   <td style="text-align:left;"> Meta (FB) released earnings per share at 3.67 USD, compared to market expectations of 3.85 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/elf-beauty-beats-q4-estimates/story.aspx?guid={93F33529-FF94-4905-B68D-74E6BF9AA82E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-03 05:20:59 </td>
   <td style="text-align:left;"> Elf Beauty beats Q4 estimates, raises guidance on 'momentum'  - MarketWatch </td>
   <td style="text-align:left;"> Shares of Elf Beauty Inc. 
        ELF,
        -0.71%
       rose more than 1% in the extended session Wednesday after the beauty products retailer reported fiscal third-quarter profit and sales above expectations and tweaked guidance for the year higher. Elf said it earned $6.2 million, or 12 cents a share, in the quarter, compared with $4.3 million, or 8 cents a share, in the year-ago period. Adjusted for one-time items, the company earned 24 cents a share. Elf said sales increased 11% to $98.1 million, mostly thanks to sales through national and international retailers. Analysts polled by FactSet expected the company to report adjusted earnings of 15 cents a share on sales of $95 million. Elf said it expects net sales between $372 million and $379 million for the year, compared with a previous expectations of sales between $364 million and $370 million. It updated the fiscal 2022 guidance for earnings to between $40 million and $42 million, from between $36 million and $37.5 million previously. The company "remains the only Top 5 color cosmetics brand with sales growth and market share above pre-pandemic levels," Chief Executive Tarang Amin said in a statement. "Given our momentum, we are raising our Fiscal 2022 guidance." Shares of Elf ended the regular trading day down 0.7%. , Alphabet's stock price will drop to around $148 based on the current stock price when the split becomes effective in July.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/pemex-holds-back-barrels-in-bid-to-ramp-up-domestic-fuelmaking?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-03 05:19:28 </td>
   <td style="text-align:left;"> Pemex Holds Back Barrels in Bid to Ramp Up Domestic Fuelmaking </td>
   <td style="text-align:left;"> Lucia Kassai                                                                                                                                                                                                                                                                                                                                                                                                                , Mexico’s crude oil exports, which slumped to a 32-year low in January, are expected to pick up again this month after its state-owned refiner realized it can’t process nearly as much at home as it was targeting.                                                                                                                                                                                                         , Daily oil exports plummeted 19% month on month to 849,000 barrels, the lowest in data going back to January 1990. The barrels kept in Mexico instead of going abroad were intended for processing at Petroleos Mexicanos’s domestic refineries, which have been trying to crank up fuelmaking at the expense of overseas sales. But Pemex didn’t refine nearly as much crude as expected in January, a person familiar said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ctsh:us </td>
   <td style="text-align:left;"> 2022-02-03 05:18:33 </td>
   <td style="text-align:left;"> Cognizant Technology Solutions earnings above expectations at 1.10 USD </td>
   <td style="text-align:left;"> Cognizant Technology Solutions (CTSH) released earnings per share at 1.10 USD, compared to market expectations of 1.04 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/australia-braces-for-tough-earnings-season-as-risks-pile-up?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-03 05:15:00 </td>
   <td style="text-align:left;"> Australia Braces for Tough Earnings Season as Risks Pile Up </td>
   <td style="text-align:left;"> Jackie Edwards                                                                                                                                                                                                                  , Australian shares are set for a rocky reporting season as threats to corporate profits pile up at home and overseas.                                                                                                            , The S&amp;P/ASX 200 Index is down almost 5% this year -- even as earnings estimates rise -- amid intense concern about the impact of tighter monetary policy, the spread of omicron, supply-chain snarls and geopolitical tensions.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/spotify-earnings-call-joe-rogan-controversy </td>
   <td style="text-align:left;"> 2022-02-03 05:14:14 </td>
   <td style="text-align:left;"> Spotify CEO on Joe Rogan controversy: 'We don't change our policies based on one creator' </td>
   <td style="text-align:left;"> 'Kennedy' panel weighs in on demands for Joe Rogan to be removed from Spotify                                                                                                                                                                                                                                                                                   , Spotify founder and CEO Daniel Ek addressed the ongoing controversy surrounding his platform's relationship with podcast titan Joe Rogan during the company's earnings call on Wednesday, as investors weigh the listening service's balancing act between allowing freedom of expression from creators and outside pressures to crack down on "misinformation.", Rogan has been accused of peddling "misinformation" about COVID-19 during conversations in some of his episodes, sparking protest from progressives.                                                                                                                                                                                                            , Longtime artist and far-left activist Neil Young pulled his music from Spotify after giving the company an ultimatum to drop Rogan – who has an enormous following exclusive to the platform – and a handful of other musicians followed suit in solidarity with Young.                                                                                         , Spotify then announced it would "add a content advisory to any podcast episode that includes a discussion about COVID-19."                                                                                                                                                                                                                                      , Neil Young poses for a portrait in Santa Monica, Calif. on Sept. 9, 2019. (Photo by Rebecca Cabage/Invision/AP, File) (Rebecca Cabage/Invision/AP / AP Newsroom)                                                                                                                                                                                                , NEIL YOUNG'S FEUD WITH SPOTIFY ‘WILL NOT HURT’ STREAMER, ‘NEGATIVE IMPACT’ WILL FALL ON SINGER: BRAND EXPERT                                                                                                                                                                                                                                                    , During Wednesday's call, the first question was about the situation with Rogan and how the company was dealing with it.                                                                                                                                                                                                                                         , "You've clearly changed your public stance given artist pushback to [Joe Rogan's] content," the individual told Ek, asking, "Is it a slippery slope censoring content on the platform, and have any advertisers left Spotify?"                                                                                                                                  , Ek acknowledged that the issue was "top of mind this week" but called it "very complicated."                                                                                                                                                                                                                                                                    , Daniel Ek, chief executive officer of Spotify. (Photo by Drew Angerer/Getty Images / Getty Images)                                                                                                                                                                                                                                                              , "I think the important part here is that we don't change our policies based on one creator, nor do we change it based on any media cycle," the chief executive said. "Our policies have been carefully written with the input from numbers of internal and external experts in this space – and I do believe they're right for our platform."                   , He added, "While Joe has a massive audience and is actually the number one podcast in more than 90 markets, he also has to abide by those policies."                                                                                                                                                                                                            , Ek said that "of course" Spotify has heard from its partners on the situation, but dodged on whether any advertisers had left.                                                                                                                                                                                                                                  , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                     , For the fourth quarter of 2021, Spotify reported an 18% increase in monthly active users from the year before to 406 million, and saw paying subscribers jump by 16% to 180 million. Both those numbers were on the high end of the company's expectations for Q4, which Ek said was the largest quarter of growth in the company's history. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 05:10:10 </td>
   <td style="text-align:left;"> Brazilian Stocks Snap 2-Day Rally </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, dropped 1.1% to close at 111,993 on Wednesday, snapping two straight sessions of gains, led by losses in shares of food processor BRF on discounted follow-on offering and IRB Brasil shares after Citi’s analysts pointed to the necessity of a follow on as the company after experiencing accounting fraud now faces a lack of profitability and its capital structure is still impaired. Meanwhile, traders cautiously await the central bank monetary policy decision later in the day, anticipating a 150bps hike in the key Selic rate to 10.75% amid persistent inflationary pressures. The monetary statement is also expected to shed some light on the bank's strategy ahead. On the data front, Brazil's industrial activity rose 2.9% from a month earlier in December, above market estimates, leading to a 3.9% increase in 2021 that is yet to restore it to pre-pandemic levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/02/entertainment/michael-k-williams-overdose-death-arrests/index.html </td>
   <td style="text-align:left;"> 2022-02-03 05:00:12 </td>
   <td style="text-align:left;"> Four arrested in connection to overdose death of actor Michael K. Williams - CNN </td>
   <td style="text-align:left;"> (CNN)Four men have been arrested for allegedly being part of a drug trafficking organization that sold deadly fentanyl-laced heroin to actor and producer Michael K. Williams, according to a press release from the United States Attorney's Office of the Southern District of New York.                                                                                                                                                         , Williams, best known for his role as Omar Little on HBO's "The Wire," was found dead in September 2021 at his New York City apartment.                                                                                                                                                                                                                                                                                                              , The New York City Medical Examiner's Office later determined Williams died from an accidental overdose.                                                                                                                                                                                                                                                                                                                                             , Irvin Cartagena, 39, Hector Robles, 57, Luis Cruz, 56, and Carlos Macci, 70, were arrested on Tuesday and were each charged with "conspiracy to distribute and possess with intent to distribute fentanyl analogue, fentanyl, and heroin," according court filings. The charge carries a mandatory minimum sentence of five years in prison and a maximum sentence of 40 years.                                                                     , The four men allegedly continued selling fentanyl-laced heroin in Manhattan and Brooklyn even after learning of Williams' death, according to prosecutors                                                                                                                                                                                                                                                                                           , "Deadly opioids like fentanyl and heroin don't care about who you are or what you've accomplished," said US Attorney Damian Williams in a statement. "They just feed addiction and lead to tragedy. The Southern District of New York and our law enforcement partners will not give up. We will bring every tool to bear. And we will continue to hold accountable the dealers who push this poison, exploit addiction, and cause senseless death.", Cartagena, who allegedly personally gave Michael K. Williams heroin laced with fentanyl and a fentanyl analogue, is also charged with causing the actor's death and faces a minimum sentence of 20 years in prison and a maximum sentence of life in prison, according to court filings.                                                                                                                                                            , Cartagena will be arraigned in federal court in Puerto Rico, where he was arrested, on Thursday, while Robles, Cruz, and Macci will be arraigned on Wednesday in Manhattan federal court before United States Magistrate Judge Stewart D. Aaron, according to the press release.                                                                                                                                                                    , CNN's Mark Morales contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 04:42:00 </td>
   <td style="text-align:left;"> Wall Street Extends 4-Day Winning Streak </td>
   <td style="text-align:left;"> US stocks extended gains for the fourth straight session on Wednesday, as the tech rally continued after upbeat earnings reports from big companies. The Dow Jones added as much as 225 points, the S&amp;P jumped 0.9%, and the tech-heavy Nasdaq Composite rose 0.5%. On the corporate front, shares of Alphabet jumped more than 7% after its quarterly results topped forecasts and the company also announced a 20-for-1 stock split. Earnings from Advanced Micro Devices and GM also beat expectations but reports from Paypal and Starbucks were disappointing. Meta, Qualcomm, and T-Mobile are also due to report earnings today after markets close. On the data front, investors shrug off the ADP report after it showed an unexpected 301K job loss last month, while expectations were around 200K new jobs. Yesterday, JOLTS figures showed that job openings rose and the quit rate remained high in December. The highly-anticipated nonfarm payrolls are due Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/sizzling-fuel-demand-sends-winter-time-margins-to-five-year-high?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-03 04:36:43 </td>
   <td style="text-align:left;"> Sizzling Fuel Demand Sends Winter-Time Margins to Five-Year High </td>
   <td style="text-align:left;"> Chunzi Xu                                                                                                                                                                                                                                                                                                                      ,  and Barbara J Powell                                                                                                                                                                                                                                                                                                          , Fuel profit margins are soaring as demand continues to recover faster than supply, sparking a bonanza for U.S. refiners that just two years ago were struggling to break even on a barrel of oil.                                                                                                                              , The profit a refiner earns on turning crude into gasoline and diesel stands at the highest for this time of year since 2017. The Gulf Coast refining margin, or crackspread, is over $20 a barrel after dropping to a low of just $2.31 a barrel in May of 2020 as the global economy ground to a halt due to the coronavirus.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/gas-price-near-year-high-biden-policies </td>
   <td style="text-align:left;"> 2022-02-03 04:36:27 </td>
   <td style="text-align:left;"> Gas price rises to $3.39 per gallon, just shy of seven-year high </td>
   <td style="text-align:left;"> FOX Business host gives his take on the rising tensions between Russia and Ukraine, tax cuts and Biden's energy policies on 'Kudlow.'                                                                                                                                                                                                                                                               , The average price for regular gasoline continues to rise and is only three cents away from a new seven-year-high.                                                                                                                                                                                                                                                                                   , According to AAA, the average price for regular gasoline now stands at $3.39, which is only 3 cents per gallon from a new seven-year high that was reached in 2014 when gas hit $3.42.                                                                                                                                                                                                              , High gas prices are posted at a full service gas station in Beverly Hills, Calif., Sunday, Nov. 7, 2021.AP Photo/Damian Dovarganes) (AP Photo/Damian Dovarganes / AP Newsroom)                                                                                                                                                                                                                      , GAS PRICES IN CALIFORNIA WILL SOAR FOLLOWING LA BAN ON NEW OIL AND GAS WELLS, INDUSTRY REP WARNS                                                                                                                                                                                                                                                                                                    , Additionally, $3.39 per gallon is almost a dollar more than the cost of gas was when President Biden took office in January of last year.                                                                                                                                                                                                                                                           , Earlier this week, Fox Business reported that the price for a gallon of gas has risen for the fifth week in a row.                                                                                                                                                                                                                                                                                  , AAA explains that the rise in gas prices is partially pushed by the developing tensions between Russia and Ukraine and fears that further sanctions on Russia would cause the country to withhold crude from the global market.                                                                                                                                                                     , "At the moment, only one person knows why Russia is threatening Ukraine, and that’s Russian President Vladimir Putin," said Andrew Gross, AAA spokesperson. "And the tensions along the Ukrainian border have helped push crude oil prices higher almost daily."                                                                                                                                    , Gas pump filling nozzles. Fuel at gas station close up (iStock / iStock)                                                                                                                                                                                                                                                                                                                            , GAS PRICES CLIMB FOR FIFTH STRAIGHT WEEK AS OIL SURGES                                                                                                                                                                                                                                                                                                                                              , AAA’s gas price tracker shows that a gallon of regular gasoline, on average, cost $2.42 per gallon one year ago and $3.28 per gallon one month ago.                                                                                                                                                                                                                                                 , For months, the prices of all kinds of energy – gasoline, diesel fuel, natural gas, oil, and more – have been a major driver behind inflation, which surged 7% in December, the highest level since 1982. Energy costs have climbed more than 29% over the past year, in part due to lopsided supply and demand. Consumers are traveling more, but the supply side has not kept up with the demand. , New analysis published Wednesday by the Joint Economic Committee Republicans suggests the Biden administration is exacerbating soaring energy prices by cracking down on the oil and gas industry with new regulations that limit production and discourage investments in traditional energy infrastructure.                                                                                       , Russian President Vladimir Putin (AP Newsroom)                                                                                                                                                                                                                                                                                                                                                      , The JEC study, shared exclusively with FOX Business, shows how President Biden's policies have stoked higher energy prices by "imposing new barriers to accessing American oil and gas reserves, and by discouraging investment in these historically reliable and inexpensive sources of energy." Rep. Mike Lee, R-Utah, is the ranking member of the Joint Economic Committee.                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                         , "Washington is sending conflicting messages," the report, authored by economist Hugo Dante and data analyst Kole Nichols, said. "Policymakers seem simultaneously concerned about high prices reflecting the weak supply of oil and gas, while aggressively pursuing an agenda designed to entirely phase-out oil and gas from domestic energy production."                                         , Fox Business’ Megan Henney and Jeff Flock contributed to this report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/tiger-global-melvin-swooned-last-month-with-rate-hikes-looming?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-03 04:34:11 </td>
   <td style="text-align:left;"> Hedge Funds Tiger Global and Melvin Swooned Last Month With Rate Hikes Looming </td>
   <td style="text-align:left;"> Chase Coleman                                                                                                                                                                                                                                                 , Katherine Burton                                                                                                                                                                                                                                              ,  and Hema Parmar                                                                                                                                                                                                                                              , Tiger Global Management and Melvin Capital Management underperformed the broader equity markets in January as rising inflation and the specter of Federal Reserve rate hikes battered growth stocks.                                                          , Chase Coleman’s Tiger Global, which managed $100 billion across public and private markets at year-end, logged a 14.8% decline for its hedge fund, and Gabe Plotkin’s $11.7 billion Melvin Capital slumped 15%, according to people familiar with the matter.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/02/politics/havana-syndrome-report/index.html </td>
   <td style="text-align:left;"> 2022-02-03 04:32:32 </td>
   <td style="text-align:left;"> US intelligence community report says 'pulsed electromagnetic energy' could cause Havana Syndrome - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)An intelligence panel investigating the cause of a spate of mysterious incidents that have struck dozens of US officials across the globe has said that some of the episodes could "plausibly" have been caused by "pulsed electromagnetic energy" emitted by an external source, according to an executive summary of the panel's findings released Wednesday.                                                                                                                    , But the panel stopped short of making a definitive determination, saying only that both electromagnetic energy and, in limited circumstances, ultrasound could explain the key symptoms -- highlighting the degree to which the murky illness known colloquially as "Havana Syndrome" has remained one of the intelligence community's most stubborn mysteries.                                                                                                                          , "We've learned a lot," an intelligence official familiar with the panel's work told reporters, speaking on anonymity under terms set by the Office of the Director of National Intelligence. "While we don't have the specific mechanism for each case, what we do know is if you report quickly and promptly get medical care, most people are getting well."                                                                                                                           , The finding largely confirms a National Academies of Science report from late 2020 that found "directed, pulsed radio frequency energy" to be "the most plausible mechanism in explaining these cases" -- but also stopped short of making a firm determination.                                                                                                                                                                                                                         , The so-called experts panel is made up of medical, scientific and engineering specialists who have access to classified information about the incidents. Officials emphasized that its work was focused only on uncovering the potential mechanism behind what the government calls "anomalous health incidents" and did not examine who, if anyone, might be responsible.                                                                                                               , An interim report issued last month by a separate CIA task force examining who might be behind the episodes found that it was unlikely Russia or any other foreign adversary is conducting a widespread global campaign designed to harm US officials. But the agency also did not rule out that a nation state -- including Russia -- might be responsible for roughly two dozen cases that investigators have been unable to explain by any other known cause.                         , Cases 'genuine and compelling'                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The scientific panel emphasized that the cases it studied were "genuine and compelling," noting that some incidents have affected multiple people in the same space and clinical samples from a few victims have shown signs of "cellular injury to the nervous system."                                                                                                                                                                                                                 , An executive summary of the panel's work provided new details about how the government is categorizing cases as possible Havana Syndrome, a clinically vague illness that has long frustrated firm diagnosis because victims have suffered from such a diverse array of symptoms.                                                                                                                                                                                                        , Although officials declined to say how many cases the panel examined as part of its inquiry, they said they studied cases that met four "core characteristics": the acute onset of sounds or pressure, sometimes in only one ear or on one side of the head; simultaneous symptoms of vertigo, loss of balance and ear pain; "a strong sense of locality or directionality"; and the absence of any known environmental or medical conditions that could have caused the other symptoms. , Victims have reported being struck by this confluence of symptoms in embassies and personal residences around the globe, and in at least one instance, at open-air stoplight in a foreign country.                                                                                                                                                                                                                                                                                       , Both pulsed electromagnetic energy, "particularly in the radiofrequency range," and ultrasonic arrays could feasibly cause the four core symptoms, the panel found. Both could originate from "a concealable source." But ultrasound can't travel through walls, the panel found, "restricting its applicability to scenarios in which the source is near the target."                                                                                                                   , Sources of radiofrequency energy, on the other hand, are known to exist, "could generate the required stimulus, are concealable, and have moderate power requirements," the panel said. "Using nonstandard antennas and techniques, the signals could be propagated with low loss through air for tens to hundreds of meters, and with some loss, through most building materials."                                                                                                      , But intelligence officials familiar with the panel's work emphasized that important information gaps remained, forestalling them from reaching firmer conclusions.                                                                                                                                                                                                                                                                                                                       , "It's frustrating but we're just as persistent to help understand and elucidate what's happening," one official said.                                                                                                                                                                                                                                                                                                                                                                    , Part of the challenge, this person said, is that the cases not only vary, but the combination of the four core characteristics is unique in medical literature.                                                                                                                                                                                                                                                                                                                          , "When we focus on the core characteristics, it's just a unique combination that we don't have a lot of experience with in the medical and clinical fields," the official said.                                                                                                                                                                                                                                                                                                           , And for ethical reasons, there is limited study of the impact of radiofrequency energy or ultrasound on the human body. The experts panel was limited to the accounts of people who had been exposed to either "inadvertently" and were willing to describe their symptoms.                                                                                                                                                                                                              , "There is a dearth of systematic research on the effects of the relevant electromagnetic signals on humans," the executive summary of the report stated.                                                                                                                                                                                                                                                                                                                                 , Victory for victim's advocates                                                                                                                                                                                                                                                                                                                                                                                                                                                           , In a victory for victims' advocates, the experts panel also ruled out one cause for those four characteristics: so-called psycho-social factors. Some victims have long complained that the CIA in the past had failed to take their reported symptoms seriously, brushing the cases aside as a psychosomatic episode or mass hysteria.                                                                                                                                                  , Those four core characteristics could not by explained by psycho-social factors "alone," the report found -- although an intelligence official explained that in some cases, a victim's symptoms might be "compounded" by a stress reaction or other psycho-social response.                                                                                                                                                                                                             , The panel also ruled out "ionizing radiation, chemical and biological agents, infrasound, audible sound, ultrasound propagated over large distances, and bulk heating from electromagnetic energy."                                                                                                                                                                                                                                                                                      , The panel made seven recommendations, including developing better biomarkers that are "more specific and more sensitive for diagnosis and triage" of cases. It also recommended utilizing "detectors" and obtaining "devices to aid research." Details on those recommendations were heavily redacted in the panel's executive summary.                                                                                                                                                  , Finally, officials urged swift action by medical officials whenever a case is reported, emphasizing that individuals who have been treated immediately after an event have improved.                                                                                                                                                                                                                                                                                                     , "I think something the employee can do to help themselves is promptly report and get medical care," the intelligence official said.                                                                                                                                                                                                                                                                                                                                                      , Officials stressed that the intelligence community will continue to investigate.                                                                                                                                                                                                                                                                                                                                                                                                         , "We continue to pursue complementary efforts to get to the bottom of Anomalous Health Incidents — and to deliver access to world-class care for those affected," Director for National Intelligence Avril Haines and CIA Director Bill Burns said in a joint statement. "We are making progress in both areas."                                                                                                                                                                          , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 04:30:07 </td>
   <td style="text-align:left;"> The Dow Jones Index rising 0.60% </td>
   <td style="text-align:left;"> United States Stock Market is gaining 213 points. Leading the gains are Travelers Companies (2.79%), UnitedHealth (2.74%) and P&amp;G (1.77%). Top losers are Salesforce.com (-3.31%), Walt Disney (-1.16%) and JPMorgan (-0.77%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/02/health/cancer-t-cell-therapy-remission-study/index.html </td>
   <td style="text-align:left;"> 2022-02-03 04:23:12 </td>
   <td style="text-align:left;"> T-cell therapy tied to 10-year remission in two leukemia patients - CNN </td>
   <td style="text-align:left;"> (CNN)Two people with leukemia achieved remission over a decade after being infused with CAR-T cells, immune cells that had been modified in a lab, according to a new study. The findings suggest that this approach could be a long-term therapy for leukemia -- and some researchers describe it as a possible cure.                                                                                                               , Chimeric antigen receptor or CAR-T cell therapy may be a "curative regimen" for chronic lymphocytic leukemia, according to the researchers, who announced their findings in a news briefing this week. Chronic lymphocytic leukemia accounts for about a quarter of new cases of leukemia.                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                       , The new paper describes "a 10-year follow up of the first patients we treated with CAR-T cells, chimeric antigen receptor modified T cells," which is the "first cell therapy made from the patient's own immune system," Dr. Carl June, a cancer immunologist at the University of Pennsylvania and one of the study's authors, said at the briefing.                                                                                , Based on the study results, "we can now conclude that CAR-T cells can actually cure patients with leukemia," June said.                                                                                                                                                                                                                                                                                                               , The CAR-T cells are an immunotherapy treatment designed to treat leukemia by harnessing the body's own immune system to target the cancer. The therapy sends a patient's immune cells to a lab to be genetically modified using a virus and gives the cells the ability to recognize and kill the source of the cancer.                                                                                                               , 'Sustained remission'                                                                                                                                                                                                                                                                                                                                                                                                                 , The new study, published Wednesday in the journal Nature, describes two distinct phases that the patients went through. They had an initial phase represented by CD8+ or CD4−CD8 CAR-T cells expressing a marker called Helios and then a shift into a long-term phase of remission dominated by the CD4+ CAR-T cell population.                                                                                                      , "CAR T cells remained detectable more than ten years after infusion, with sustained remission in both patients," the researchers wrote.                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                       , The researchers -- from the University of Pennsylvania and the Novartis Institute for Biomedical Research in Cambridge, Mass. -- studied the long-lasting T cells in the two people with leukemia who were in complete remission in 2010 after they had been infused with the cells as part of a Phase 1 clinical trial. The two remain in remission more than 10 years after the infusion, the researchers noted.                    , Oncologist Dr. David Porter, an author of the study, said this type of immunotherapy can come with serious side effects, though he said these therapies have become safer over the years and are given to hundreds or thousands of people a year.                                                                                                                                                                                     , One side effect is tumor lysis syndrome, "a phenomenon where you kill large numbers of cancer cells all at the same time and they spill their contents into the blood, and that can make people quite sick," he said. Tumor lysis syndrome can cause electrolyte abnormalities and damage to the kidneys.                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                                                                                       , Another side effect is cytokine release syndrome, which gives people a severe flu-like syndrome, with very high fevers, nausea, vomiting, and muscle and joint pain.                                                                                                                                                                                                                                                                  , "It can evolve to very dangerously low blood pressure, trouble breathing with fluid leaking into the lungs," Porter said.                                                                                                                                                                                                                                                                                                             , The third major side effect is a neurologic toxicity, leading to difficulty speaking or thinking clearly. In some situations, people can become comatose or develop seizures, according to Porter, but the majority of cases resolve on their own.                                                                                                                                                                                    , A 'deeper understanding'                                                                                                                                                                                                                                                                                                                                                                                                              , For the new research, June recruited Dr. Joseph Melenhorst to establish a laboratory that studied people who had been treated with CAR-T cells.                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                       , "We have actually built a pipeline and deeper understanding of the biology of the cells that were infused," Melenhorst, of the University of Pennsylvania, who was an author of the new paper, said in Tuesday's briefing. "We were able to isolate and analyze cells with new technologies, and it's given a very good insight into some of the mechanisms of persistence and tumor response in both subjects."                      , Doug Olson was one of the patients studied over the course of a decade. He was diagnosed with chronic lymphocytic leukemia when he was 49.                                                                                                                                                                                                                                                                                            , "Even though it was terrifying to hear that I had cancer, I really didn't need a lot of treatment for about six years," Olson said at the briefing.                                                                                                                                                                                                                                                                                   , Then "chemo got me in remission for another five years, and then things started to go downhill pretty quickly after that, and by 2010, about 50% of my bone marrow was CLL," Olson said, referring to chronic lymphocytic leukemia, a type of cancer that starts from white blood cells in the bone marrow.                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                       , Olson said he was given his first infusion of CAR-T cells in September 2010 and shortly after was very sick and hospitalized for about three days -- and the next week, his oncologist told him that no cancer cells were detected in his body.                                                                                                                                                                                       , "We did not think that this would be a curative therapy at all back in 2010," June said.                                                                                                                                                                                                                                                                                                                                              , "But the reason now I think we can say this is a cure for Doug -- from a scientific point of view -- is, I mean, these are the most mature, the oldest results available reported in the scientific literature, since they were the first treated," he said. "So at this point, 10 years on, we can't find any leukemia cells, and again, we still have the CAR-T cells that are on patrol and on surveillance for residual leukemia.", </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hdfc:in </td>
   <td style="text-align:left;"> 2022-02-03 03:56:07 </td>
   <td style="text-align:left;"> Housing Development earnings above expectations at 17.75 IR </td>
   <td style="text-align:left;"> Housing Development (HDFC) released earnings per share at 17.75 IR , compared to market expectations of 16.96 IR . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-end-slightly/story.aspx?guid={DC49232F-4CAA-4DFD-8B4F-821264C7575A}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-03 03:43:08 </td>
   <td style="text-align:left;"> U.S. oil futures end slightly higher after OPEC+ stands pat on plans to boost output - MarketWatch </td>
   <td style="text-align:left;"> U.S. oil futures saw a slight gain on Wednesday, enough to eke out another settlement at the highest since October 2014. Prices had spent much of the session trading lower after Organization of the Petroleum Exporting Countries and their allies agreed to a 400,000 barrel-per-day production increase for March. OPEC+ still "believes the global demand recovery is underway," said Rohan Reddy, research analyst at Global X, noting that OPEC forecasts "robust growth in world oil demand this year, despite expected interest rate hikes and the omicron variant." Still, OPEC+ has not further increased output as some of its members failed to meet their production targets last month, and given uncertainties surrounding geopolitical tensions involving Russia and Ukraine, said Reddy. Traders also weighed data from the Energy Information Administration, which showed a weekly decline in U.S. crude supplies and a rise in gasoline stockpiles. West Texas Intermediate crude for March delivery 
        CLH22,
        -0.66%
       rose 6 cents, or nearly 0.1%, to settle at $88.26 a barrel on the New York Mercantile Exchange. , Shares of Facebook parent Meta Platforms Inc. plummeted 22% in extended trading Wednesday on an earnings miss, weak guidance and intensifying competition.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/metaverse-etf-punk-launches-excludes-investments-in-mark-zuckerbergs-meta </td>
   <td style="text-align:left;"> 2022-02-03 03:25:35 </td>
   <td style="text-align:left;"> Metaverse ETF ‘PUNK’ launches, excludes investments in Mark Zuckerberg’s Meta </td>
   <td style="text-align:left;"> Gerber Kawasaki CEO Ross Gerber and CNET managing editor Russell Holly discuss Big Tech earnings expectations on 'The Claman Countdown.'                                                                                                                                                                                                                                        , A new exchange-traded fund is investing in all things having to do with the metaverse, with one glaring exception: Mark Zuckerberg’s "Meta."                                                                                                                                                                                                                                    , The "Subversive Metaverse ETF," from Subversive Capital Advisor, launched Thursday on the Cboe BZX Exchange.                                                                                                                                                                                                                                                                    , A 3D printed Facebook's new rebrand logo Meta is placed on laptop keyboard. (Reuters/Dado Ruvic/Illustration)                                                                                                                                                                                                                                                                   , Listed as "PUNK," this new ETF aims to achieve long-term capital appreciation by investing in globally-listed equity securities of companies that provide the services and infrastructure within the emerging Metaverse, according to a press release.                                                                                                                          , Christian H. Cooper, the ETFs portfolio manager, said discussions around the metaverse are overshadowed by larger companies like Zuckerberg’s "Meta."                                                                                                                                                                                                                           , WHAT IS METAVERSE AND WHY NFTS ARE KEY TO ITS MASSIVE EXPLOSION                                                                                                                                                                                                                                                                                                                 , "Our mission here at Subversive is to question the integrity of the status quo—which is why the PUNK Fund is short META—and build a foundation for people to appreciate these emerging sectors just as much as we do," Cooper said in a statement. "We want to make sure this industry develops, without getting ‘Zucked-up’, from those who see true potential of this space." , Mr. Zuckerberg spoke to an avatar of himself in the metaverse during a live-streamed virtual and augmented reality conference to announce the rebranding of Facebook as Meta. (Facebook via Reuters)                                                                                                                                                                            , Subversive Capital Advisor founder Michael Auerbach told Bloomberg last week, that "Facebook seems to be the antithesis of what actual consumers want their digital futures to look like."                                                                                                                                                                                      , "Mark and his team are not the best custodians of the digital futures," he said.                                                                                                                                                                                                                                                                                                , Facebook rebranded itself last October as "Meta," saying it would devote more resources and attention to becoming a Metaverse platform.                                                                                                                                                                                                                                         , FACEBOOK'S CRYPTOCURRENCY VENTURE TO WIND DOWN AFTER ASSET SALE TO SILVERGATE                                                                                                                                                                                                                                                                                                   , "From now on, we’re going to be metaverse first, not Facebook first," Zuckerberg said at a Connect 2021 event. "That means that over time, you won’t need to use Facebook to use our other services as our new brand starts showing up in our products. I hope people come to know the Meta brand and the future that we stand for."                                            , Facebook whistleblower, Frances Haugen appears before the Senate Commerce, Science, and Transportation Subcommittee during a hearing. (Matt McClain-Pool/Getty Images)                                                                                                                                                                                                          , The rebranding came at a time of upheaval for the company after former product manager-turned whistleblower Frances Haugen delivered scathing testimony to U.S. and U.K. lawmakers.                                                                                                                                                                                             , CLICK HERE TO READ FOX BUSINESS ON THE GO                                                                                                                                                                                                                                                                                                                                       , FOX Business has reached out to Meta for comment.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/economic-satisfaction-biden-first-year-gallup </td>
   <td style="text-align:left;"> 2022-02-03 03:21:43 </td>
   <td style="text-align:left;"> Americans' economic satisfaction plunged during Biden's first year in office: Gallup poll </td>
   <td style="text-align:left;"> Former Reagan economist Art Laffer argues inflation is 'not under control yet' and says he is 'quite concerned about the next 12 months for the U.S. economy.'                                                                                                                                                                                                                                                                                                   , Economic satisfaction plummeted during President Biden's first year in office as American consumers grappled with the hottest inflation in nearly four decades and the continuation of the COVID-19 pandemic.                                                                                                                                                                                                                                                    , A new Gallup poll found that just one-third of Americans are satisfied with the current state of the economy, despite the improvements in employment, economic growth and the stock market last year. It marks a significant drop from one year ago, before Biden was sworn in as president, when 43% of survey respondents said they were satisfied. By comparison, before the pandemic began, about 68% of Americans said they were satisfied with the economy., SURGING INFLATION TAKES HOLD IN MOUNTAIN STATES, WITH RATES NEAR 9%                                                                                                                                                                                                                                                                                                                                                                                              , In all, 64% of the people surveyed between Jan. 3 and Jan. 16 said they were dissatisfied with the economy, including about one in three who said they were "very dissatisfied" with the economy. It's the worst reading since January 2014.                                                                                                                                                                                                                     , Inflation has accelerated as the economy rebounds from the brief, but extremely severe, pandemic-induced recession, surging 7% in December from the previous year – the fastest pace since 1982, according to the Labor Department.                                                                                                                                                                                                                              , Customers wait in line to checkout during a Black Friday sale at Macy's, Nov. 26, 2021, in Indianapolis.  (AP Photo/Darron Cummings, File / AP Newsroom)                                                                                                                                                                                                                                                                                                         , The prices of all kinds of energy – gasoline, diesel fuel, natural gas, oil and more – have been a major driver behind inflation, with costs climbing more than 29% over the past year, in part due to lopsided supply and demand. Consumers are traveling more, but the supply side has not kept up with the demand.                                                                                                                                            , DECEMBER INFLATION BREAKDOWN: WHERE ARE PRICES RISING THE FASTEST?                                                                                                                                                                                                                                                                                                                                                                                               , One of the biggest satisfaction declines in the survey was with energy policies: Just 27% of respondents said they were satisfied with energy policies, a steep drop from one year ago, when 42% said they were satisfied.                                                                                                                                                                                                                                       , Rising gas prices are likely the reason. The Labor Department reported in January that gasoline prices have skyrocketed 49.6% over the past year, while natural gas has surged 24.1% and electricity is up 6.3%. A gallon of gas, on average, was $3.37 nationwide on Monday, according to AAA – up from $2.42 a year ago. In California, gas prices are well over $4 per gallon.                                                                                , People shop for groceries in a Manhattan store on Jan. 12, 2022 in New York City. (Spencer Platt/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                    , The rising prices are eating away at the strong wage gains Americans saw last year and are hitting the lowest-income households the hardest. An analysis from the University of Pennsylvania's Penn Wharton Budget Model shows that higher energy prices cost the average American an additional $1,200 last year. The lowest-income households spent about 11% of total expenditures on energy in 2021, up from 8% in 2020.                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                      , The rising prices are eating away at the strong wage gains Americans saw last year and are hitting the lowest-income households the hardest. An analysis from the University of Pennsylvania's Penn Wharton Budget Model shows that higher energy prices cost the average American an additional $1,200 last year. The lowest-income households spent about 11% of total expenditures on energy in 2021, up from 8% in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-us-canada-60236190?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-03 03:07:20 </td>
   <td style="text-align:left;"> CNN's Jeff Zucker resigns over undisclosed relationship </td>
   <td style="text-align:left;"> CNN president Jeff Zucker has resigned from the network after failing to disclose a romantic relationship with a senior executive.                                                                                                                           , The 56-year-old Mr Zucker said in a memo to colleagues that he was "wrong" to not report the relationship as required.                                                                                                                                       , The relationship was discovered during an investigation into the conduct of fired CNN anchor Chris Cuomo.                                                                                                                                                    , Mr Zucker is considered one of the most powerful media executives in the US.                                                                                                                                                                                 , In the message sent on Wednesday to the network's staff and shared online by CNN media correspondent Brian Stelter, Mr Zucker said that he was asked about his consensual relationship with a colleague during an investigation into Mr Cuomo's time at CNN. , Mr Cuomo was being investigated over efforts to help his politician brother, former New York governor Andrew Cuomo, fight allegations of sexual harassment.                                                                                                  , Mr Zucker said that he had worked with the colleague for two decades and that the relationship had "evolved in recent years".                                                                                                                                , "I was required to disclose it when it began but I didn't," he said. "I was wrong. As a result, I am resigning today."                                                                                                                                       , Mr Zucker's memo did not identify the colleague with whom he had a relationship but CNN named her as Allison Gollust, the network's executive vice president and chief marketing officer.                                                                    , "Jeff and I have been close friends and professional partners for over 20 years," she said in a statement quoted by Mr Stelter on air. "Recently, our relationship changed during Covid. I regret that we didn't disclose it at the right time."             , Ms Gollust was an executive at NBC Universal during Mr Zucker's time at that network as CEO.                                                                                                                                                                 , In 2012, Ms Gollust was named as communicators director for Andrew Cuomo. She joined CNN the following year after only four months in that role.                                                                                                             , In her statement, Ms Gollust added that she intends to stay at the network. Both she and Mr Zucker are divorced, the New York Times reported.                                                                                                                , Mr Zucker joined CNN in 2013. Under his leadership, it broke viewership records in 2020 and saw the most viewers in its history during January 2021 - partly as a result of the US Capitol riot on 6 January.                                                , Since then viewership has gone down, falling nearly 90% this January compared to the same time last year, according to Nielsen ratings.                                                                                                                      , At CNN, Mr Zucker faced criticism from those who believed the network gave too much coverage to the former president, especially during the Republican presidential primary. Mr Trump has also criticised what he saw as unfair coverage.                    , During his time at NBC, he approved Donald Trump's reality TV show "The Apprentice".                                                                                                                                                                         , How one ship triggered a global crisis...                                                                                                                                                                                                                    , An extraordinary family and their passion for climbing                                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-england-tyne-60234941?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-03 03:02:27 </td>
   <td style="text-align:left;"> Fawdon Nestle factory to close with loss of 474 jobs </td>
   <td style="text-align:left;"> Nestle has announced its confectionery factory in Newcastle is to shut with the loss of 474 jobs.                                                                                                                        , The global food manufacturer said it was holding talks with employees at the Fawdon plant but the focus was now on closing it in 2023.                                                                                   , A spokeswoman said the majority of production currently in the North East would move to Halifax, West Yorkshire.                                                                                                         , The GMB and Unite unions condemned the move and said closing "a profit-making factory" was "unacceptable".                                                                                                               , The future of the former Rowntree plant had been in doubt since Nestle announced in April that it wanted to end production at the site.                                                                                  , Fawdon has been producing confectionery since 1958 but, according to unions, the manufacture of Fruit Pastilles will switch to the Czech Republic and Toffee Crisps will be made in Poland.                              , In recent years the factory has made other popular brands like Rolos, Munchies and Matchmakers.                                                                                                                          , In a statement, Nestle said: "From the outset we wanted to provide adequate time and space for these discussions and it is only right that they are held directly with our employees and trade unions and not in public. , "It remains a priority to support our people and their families through this process and we thank everybody for their patience."                                                                                         , Ross Murdoch, GMB national officer, said: "Closing this profit-making site and shifting production to Europe is completely unacceptable.                                                                                 , "This will have a devastating impact on workers and their families."                                                                                                                                                     , The union claimed moving production to mainland Europe "will result in significant additional road and sea miles, increasing pollution and environmental damage" when transporting goods to the UK for consumption.      , "GMB and Unite will now speak to members in Fawdon and find out what they want to do next. We will give them whatever support and resources they need to fight this," Mr Murdoch added.                                  , Joe Clarke, national officer for Unite, said: "Our membership is bitterly disappointed that alternative proposals to keep the site within Nestle Fawdon open have been rejected.                                         , "We are currently seeking further information in relation to the proposal and we will enter into dialogue on next steps imminently."                                                                                     , Nestle employs more than 8,000 people in the UK and Ireland across 18 sites, including 14 factories.                                                                                                                     , Follow BBC North East &amp; Cumbria on Twitter, Facebook and Instagram. Send your story ideas to northeastandcumbria@bbc.co.uk.                                                                                              , Information about BBC links to other news sites                                                                                                                                                                          , How one ship triggered a global crisis...                                                                                                                                                                                , An extraordinary family and their passion for climbing                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/wendys-putting-chicken-breakfast-menu/story.aspx?guid={60F86237-9061-4DA4-A640-8DF6903D35BA}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-03 03:01:38 </td>
   <td style="text-align:left;"> Wendy's is putting chicken on the breakfast menu with the new Hot Honey Chicken Biscuit - MarketWatch </td>
   <td style="text-align:left;"> Wendy's Co. 
        WEN,
        -1.25%
       has added a couple of chicken options to its menu: the Hot Honey Chicken Biscuit, which marks the first breakfast addition since that menu was introduced in 2020, and the Hot Honey Chicken Sandwich, which is available for the rest of the day. The launches tap into the hot honey and spicy trends, according to John Li, Wendy's vice president of culinary innovation, who hosted a call with reporters about the launch. Both are made with white-meat chicken breast. The Hot Honey Chicken Sandwich also includes Pepper Jack cheese, Applewood smoked bacon and pickle chips that have been dusted with seasonings and fried. Wendy's launched a fresh take on French fries in August 2020. Wendy's is scheduled to report fourth-quarter earnings on March 1, according to a FactSet calendar. Wendy's stock has run up 11.3% over the last year while the S&amp;P 500 index 
        SPX,
        +0.94%
       is up 19.6%., Alphabet Inc. followed in the footsteps of Apple Inc. and Tesla Inc. on Tuesday, by making its stock seem more affordable through a 20-to-1 stock split, the first split in eight years for the internet ad and search giant.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-settle-highest-price/story.aspx?guid={E985179C-76D9-4D6B-A155-5E13AABF52B2}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-03 02:35:11 </td>
   <td style="text-align:left;"> Gold futures settle at highest price in a week - MarketWatch </td>
   <td style="text-align:left;"> Gold futures on Wednesday tallied a third straight session climb, extending their rise past $1,800 to mark their highest settlement in a week. "While gold is likely to exploit the dollar's weakness to push higher, its near-term outlook remains influenced by the U.S. jobs report on Friday," said Lukman Otunuga, manager, market analysis at FXTM. "A strong jobs report that shows robust job and wage growth may reinforce expectations of a hawkish [Federal Reserve], dragging gold prices lower as the dollar regains its mojo," he said. However, "if the jobs report disappoints, this could offer some relief to gold bugs, resulting in an incline back towards $1,831." April gold 
        GCJ22,
        -0.12%
       rose $8.80, or 0.5%, to settle at $1,810.30 an ounce. That was the highest most-active contract finish since Jan. 26, FactSet data show. , Alphabet's stock price will drop to around $148 based on the current stock price when the split becomes effective in July.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/02/victims-of-unemployment-fraud-may-find-out-this-tax-season.html </td>
   <td style="text-align:left;"> 2022-02-03 02:18:29 </td>
   <td style="text-align:left;"> Is a scammer getting unemployment benefits in your name? Victims will find out this tax season </td>
   <td style="text-align:left;"> , Many victims of identity theft linked to unemployment fraud will learn of the crime this tax season.                                                                                                                                                                                 , Such fraud — whereby organized crime rings and other thieves use stolen personal data to claim unemployment benefits in others' names — has surged during the Covid-19 pandemic.                                                                                                     , Victims unaware of an identity breach may get an unwelcome surprise: a 1099-G tax form.                                                                                                                                                                                              , The form, issued by a state unemployment agency, lists the total unemployment compensation collected over the year. The IRS treats benefits as taxable income; recipients generally report the 1099-G data on their federal income tax return.                                       , Fraud victims will get a 1099-G form for benefits they didn't receive, or for a larger sum than they collected. Identity thieves got those funds instead, leaving victims to deal with the fallout.                                                                                  , (Some victims may be notified of the fraud by their employer. A state unemployment agency may contact the employer to verify a layoff before issuing benefits.)                                                                                                                      , Here's the good news: Victims won't owe tax on those funds. But there are steps victims should take quickly to protect their identity; not doing so could have severe financial repercussions like damaged credit or having bank accounts opened in their name.                      , "By the time the fraudster has applied for unemployment insurance, who knows what else they used your identity for," according to Michele Evermore, a senior policy advisor for unemployment insurance at the U.S. Department of Labor.                                              , Identity theft was especially acute in 2020, when millions of people were likely victims, Evermore said.                                                                                                                                                                             , Criminals were lured by new federal programs that offered larger-than-usual sums of weekly aid and had relatively lax claiming requirements, which helped expedite funds to the jobless at a time of ballooning unemployment.                                                        , In most cases, thieves didn't hack the unemployment system for personal data, Evermore said — they got it from past data breaches, like the one that impacted the crediting reporting company Equifax in 2017.                                                                       , Federal officials and state agencies have clamped down since early 2020, instituting identity verification and other fraud-prevention measures, Evermore said.                                                                                                                       , However, criminals are still successful in some cases. About $1 billion of benefits issued between July 2020 and June 2021 was due to confirmed fraud, much of it likely due to identity theft, Evermore said.                                                                       , "We haven't completely shut down the fraud," she said. "[But] it's been such a huge priority for states. If there's not a significant reduction in 2021 I'd be shocked."                                                                                                             , Federal officials recommend victims take several steps after becoming aware of an unemployment-related identity theft.                                                                                                                                                               , Relative to taxes, victims shouldn't delay filing their tax returns. But they should report only the income they received in 2021, not the inaccurate number from the 1099-G.                                                                                                        , More from Personal Finance:How to prepare for student loan payments to restart in 3 monthsDon't make these IRA deduction mistakesWhat to do if you got an incorrect child tax credit letter from the IRS                                                                             , Report the theft to the state unemployment agency that issued the 1099-G. (Use this Labor Department state directory to find the appropriate contact.) The state will issue an amended tax form and update the record with the IRS on your behalf, according to the Labor Department., If possible, report the theft online, which will save time and be easier for the agency to process, according to the Federal Trade Commission.                                                                                                                                       , Further, check your credit report for suspicious activity or unauthorized lines of credit. You can request a free credit report every week through AnnualCreditReport.com or call 1- 877-322-8228, according to the Labor Department.                                                , Also, consider freezing your credit to protect against new accounts being opened in your name.                                                                                                                                                                                       , The Labor Department also recommends reporting the incident to the U.S. Department of Justice's National Center for Disaster Fraud, to help law enforcement stop future theft.                                                                                                       , Victims can consult dol.gov/fraud or the IRS website for more information.                                                                                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                               , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                               , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                     , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                     , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                   , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/are-we-bracing-for-a-recession-in-the-coming-years-as-economists-have-been-predicting </td>
   <td style="text-align:left;"> 2022-02-03 02:17:10 </td>
   <td style="text-align:left;"> Probability of recession predicted by former Fed official </td>
   <td style="text-align:left;"> Former Federal Reserve Bank of Atlanta President Dennis Lockhart argues the odds of a recession in 2023 are 'low' as 'the economy remains 'quite strong.'                                                                                                                                                                                                                                                                                                      , Former Federal Reserve Bank of Atlanta President Dennis Lockhart noted that he isn’t ruling anything out regarding a potential recession in the coming years, but argued the odds are "low."                                                                                                                                                                                                                                                                   , Lockhart offered the insight on "Mornings with Maria" on Wednesday responding to economist Nancy Lazar’s argument that a "significant global slowdown" and "a risk of a global recession" is plausible in 2023.                                                                                                                                                                                                                                                , "We are a global economy, many companies are globally based, and the tightening cycle was already set to slow the economy here in 2023 and the Fed would obviously make it worse, but so would Russia, big time, and that’s why we raised the specter from the first time of a global recession possibly in 2023," The co-founder and chief economist of Cornerstone Macro argued on "Mornings with Maria" late last month. "I hope not, but it is what it is.", Lockhart noted on Wednesday that "all kinds of things can happen" given the U.S. is in a "sensitive geopolitical situation" and "there could be a shock in that regard."                                                                                                                                                                                                                                                                                       , He also pointed out that "the Fed is trying to navigate between keeping a long expansion going and dealing with inflation" and that can impact the economy.                                                                                                                                                                                                                                                                                                    , Still, Lockhart believes the odds of a recession in 2023 are "low."                                                                                                                                                                                                                                                                                                                                                                                            , Markets have been volatile in anticipation of rate hikes. Last month, all three of the major averages were down with the Nasdaq fairing the worst.                                                                                                                                                                                                                                                                                                             , Global tensions with Russia inching closer to Ukraine contributed to selling last week as well as investor jitters over the possibility of faster rising interest rates to combat inflation.                                                                                                                                                                                                                                                                   , As for this year, Lockhart predicted that economic growth "will slow," which he stressed "is somewhat natural."                                                                                                                                                                                                                                                                                                                                                , LAFFER'S DIRE WARNING ON INFLATION, US ECONOMY: ‘TIPPING INTO A SLOWDOWN’                                                                                                                                                                                                                                                                                                                                                                                      , He noted that "2021 was a bounce back from the depths of the early stages of the COVID crisis in 2020 so all the numbers are going to show very, very strong growth."                                                                                                                                                                                                                                                                                          , "I think it’s natural as this whole situation matures that the economy slows down," he continued, stressing that he believes "the economy remains really quite strong" this year.                                                                                                                                                                                                                                                                              , "The Fed, the FOMC [The Federal Open Market Committee], is unquestionably going to raise interest rates, try to take the edge off the demand so policy is going to be set in a way to try to deal with the inflation question and slow things a little bit or take a little bit of the froth out of the economy," Lockhart went on to say, stressing that he believes "we are going to continue to see solid growth."                                          , George Cipolloni, portfolio manager at Penn Mutual Asset Management, discusses what he believes the Fed will do this year to try and curb inflation.                                                                                                                                                                                                                                                                                                           , Last week, The Federal Reserve signaled it could "soon" raise interest rates for the first time in three years, paving the way for a March liftoff as policymakers seek to keep prices under control and combat the hottest inflation in nearly four decades.                                                                                                                                                                                                  , Although central bank officials have left rates unchanged since March 2020, they indicated broad support last week during a two-day, policy-setting meeting to begin aggressively normalizing policy, including raising rates amid growing concern over the rapid increase in consumer prices.                                                                                                                                                                 , A rate increase would mark the first since December 2018.                                                                                                                                                                                                                                                                                                                                                                                                      , Last week, it was revealed that a key measure of annual inflation that is closely watched by the Federal Reserve is running at the hottest pace in nearly four decades as widespread supply disruptions, extraordinarily high consumer demand and worker shortages fuel rapidly rising prices.                                                                                                                                                                 , WHERE ARE SURGING CONSUMER PRICES HITTING AMERICANS THE HARDEST?                                                                                                                                                                                                                                                                                                                                                                                               , Prices soared by 5.8% in the year through December, according to the personal consumption expenditures price index data released Friday morning, beating out the previous month's increase of 5.7% to become the fastest inflation pace since 1982.                                                                                                                                                                                                            , Former Federal Reserve Bank of Atlanta President Dennis Lockhart argues 'we are not going to see the gains we saw in 2021.'                                                                                                                                                                                                                                                                                                                                    , In the one-month period between November and December, prices jumped 0.4% (0.5% when excluding food and energy costs).                                                                                                                                                                                                                                                                                                                                         , Excluding the more-volatile measurements of food and energy, prices rose 4.9% in December from the previous year – the highest since September 1983. That measurement is the Fed's preferred gauge to track inflation; it marks the ninth consecutive month the measure has been above the central bank's target range of 2%.                                                                                                                                  , The inflation spike largely reflected surging energy costs, which rose 29.9% from a year ago, and food costs, which were up 5.7% over that same time period. Services inflation rose by 4.2% in December, and goods inflation increased 8.8% – up from the 8.5% pace a month prior, the data shows.                                                                                                                                                            , George Cipolloni, portfolio manager at Penn Mutual Asset Management, discusses what he believes the Fed will do this year to try and curb inflation.                                                                                                                                                                                                                                                                                                           , Lockhart said he believes the "likely near scenario" will present two to three rate increases in an attempt to tame inflation.                                                                                                                                                                                                                                                                                                                                 , "I think the Fed will take a look at the situation and decide whether they want to go further, that will depend very much on the conditions at that time plus the outlook at that time in the future," he told host Maria Bartiromo.                                                                                                                                                                                                                           , He then stressed, that as a result, no one really knows exactly how many rate increases will take place at this stage. He did, however, say that he does believe the first rate increase will happen in March as the Fed had signaled.                                                                                                                                                                                                                         , "I tend to think they [the Fed] will do consecutive meetings, get two or three [rate hikes] under their belt and then pause and evaluate whether they want to go further or not or have to go further or not," Lockhart added.                                                                                                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                    , He also predicted that the Fed will "do quarter-point moves," especially because "that has been the pattern for a long, long time."                                                                                                                                                                                                                                                                                                                            , "When you start shifting to 50 basis point moves, a lot of misinterpretation can come into play," Lockhart stressed. "I think just sort of out of inertia they will stick with quarter-point moves."                                                                                                                                                                                                                                                           , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                        , FOX Business’ Suzanne O’ Halloran and Megan Henney contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/texas-tesla-oracle-california-texas </td>
   <td style="text-align:left;"> 2022-02-03 01:50:45 </td>
   <td style="text-align:left;"> Why Tesla, Oracle fled California for Texas </td>
   <td style="text-align:left;"> FOX Business’ Connell McShane reports just outside Austin, Texas, where business owners say outsider are ‘coming in troves.’                                                                                                                                                                               , The state of the Texas economy is growing and thriving, and a new study suggests it could be linked to the Lonestar State’s less restrictive COVID policies.                                                                                                                                               , "People and businesses know that if they come to Texas, they're going to stay open," Texas Association of Business President Glenn Hamer told FOX Business’ Connell McShane Wednesday.                                                                                                                     , "They know that there's always that threat, if it's a pandemic or God knows what. If they're in another state, they could be closed down or regulated out of existence," Hamer continued.                                                                                                                  , A recent Johns Hopkins study found that pandemic lockdowns and closures had "little to no" effect on reducing COVID deaths, and Texas is just one of four states surpassing pre-pandemic job levels after touting no-mask, no-lockdown measures last year.                                                 , TEXAS' ECONOMY ‘SURGING’ DURING OMICRON AS SOME CALIFORNIA BUSINESSES VOLUNTARILY SHUT DOWN                                                                                                                                                                                                                , Cities around the Austin area have seen an especially high outsider exodus which local business owners contribute to the open-for-business protocols, which have attracted larger companies like Tesla and Oracle to settle in Texas.                                                                      , "People are coming in droves," one Bastrop restaurant owner told McShane. "It's just been with the Tesla factory coming in and all of the ancillary stuff that's come along with that, and we were already on a pretty good growth trajectory anyway."                                                     , Texas Gov. Greg Abbott on supply chain issues, immigration under President Biden and Americans moving from other states to Texas.                                                                                                                                                                          , Another local business had to increase its staff by 36% in order to meet increased consumer demand.                                                                                                                                                                                                        , "We've been hiring as we can and trying to hire more and more right now as they're available," Pyrology owner Kemper Morrow said.                                                                                                                                                                          , In December, Texas brought in more sales tax than ever before, hitting $3.6 billion. Texas recorded only four months before the pandemic when sales taxes collected $3 billion or more. Now, the state has recorded nine consecutive months, from April to December, of hitting or exceeding the benchmark., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                , Gov. Greg Abbott praised the state’s strong economy, tweeting earlier this month that "Texas is #1 state for business."                                                                                                                                                                                    , The governor continued: "Companies of all sizes thrive in Texas due to our low taxes, superior business climate &amp; world-class workforce."                                                                                                                                                                  , READ MORE FROM FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/02/stocks-making-the-biggest-moves-midday-alphabet-paypal-general-motors-amd-more.html </td>
   <td style="text-align:left;"> 2022-02-03 01:48:25 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Alphabet, PayPal, General Motors, AMD &amp; more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                    , Check out the companies making headlines in midday trading Wednesday.                                                                                                                                                                                                                                                                                                              , Alphabet – Shares of Alphabet popped 7.5% after the Google parent posted blowout quarterly results and announced a 20-for-1 stock split. Alphabet beat analyst estimates for every major metric, except for YouTube advertising revenue; the company reported a profit of $30.69 per share in the fourth quarter, compared with the Refinitiv consensus estimate of $27.34.        , PayPal – PayPal plunged 24.6% after issuing disappointing guidance for the current quarter — which it blamed on inflation — and missing bottom-line forecasts by a penny per share. The payments giant also pointed to challenges with the transition of former owner eBay to its own payments platform.                                                                           , General Motors – GM shares fell 1.1% after a mixed quarterly report. The automaker posted adjusted quarterly earnings of $1.35 per share, 16 cents higher than the Refinitiv consensus estimate. However, GM's revenue fell short of Wall Street expectations.                                                                                                                     , Advanced Micro Devices – AMD shares added 5.1% after the chipmaker beat earnings expectations. The company posted an adjusted quarterly profit of 92 cents per share, topping the Refinitiv consensus estimate by 16 cents. AMD also forecast better-than-expected full-year revenue, as demand remains strong for its data center chips.                                          , Capri Holdings – Shares of the company behind Michael Kors and other luxury brands jumped 7.8% after a stronger-than-expected earnings report. Capri reported adjusted earnings of $2.22 per share for the last quarter, beating the Refinitiv consensus estimate of $1.69 per share. The company also hiked its profit forecast as demand for handbags and apparel remains strong., Boston Scientific – Shares of the medical device manufacturer ticked 4.7% lower after reporting a disappointing outlook. Boston Scientific did, however, report quarterly earnings of 45 cents per share, 1 cent over expectations. The company's revenue also beat a Refinitiv estimate.                                                                                          , Match Group – Match Group shares rose 5.3% even after the Tinder-parent company issued a weaker-than-expected full-year revenue forecast, as it projects pandemic will continue to hinder dating activity.                                                                                                                                                                         , Under Armour – Shares of the apparel company rose 2.7% after Morgan Stanley upgraded the stock to overweight. The investment firm said that Under Armour looked like a buying opportunity after a weak January and that the company should be able to better manage supply chain issues than some of its peers.                                                                    , — CNBC's Yun Li, Maggie Fitzgerald, Jesse Pound and Tanaya Macheel contributed reporting.                                                                                                                                                                                                                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                   , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 01:28:00 </td>
   <td style="text-align:left;"> Madrid Stocks Erase Gains </td>
   <td style="text-align:left;"> The IBEX 35 Index trimmed early gains to close 0.2% lower at 8,713 on Wednesday, underperforming its European counterparts, as investors weighed on a batch of fresh economic data while monitoring geopolitical developments in between Russia and NATO member states. Inflation in the Eurozone for January rose to a record high of 5.1%, according to preliminary estimates, significantly higher than expectations of 4.4%. At the same time, the number of people registered as unemployed in Spain unexpectedly increased by 17 thousand in January, after ten months of consecutive declines. On the corporate front, Inditex (-2.3%) took the biggest losses. On the other hand, Banco Santander shares rose 0.3% after posting EUR 8,124 million in profits during 2021, nearly recovering from EUR 8,771 million in losses during 2020. Given the results, the bank aims to increase shareholder renumeration by 40% in the long term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 01:10:23 </td>
   <td style="text-align:left;"> South African Stocks End at Near 2-Week High </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index rose 0.4% to close at 75,191 on Wednesday, its highest since January 20th, extending gains for a third straight session, as upbeat earnings reports from US companies helped to ease concerns over the pace of the potential increases in US interest rates and ongoing tensions in Eastern Europe. On a negative note, South African utility Eskom announced scheduled power cuts from Wednesday until Monday, after "numerous" generating unit breakdowns since the weekend at several power stations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 00:53:50 </td>
   <td style="text-align:left;"> European Shares End Mostly Higher </td>
   <td style="text-align:left;"> The DAX ended little changed at 15617 but other major bourses in Europe managed to finish higher on Wednesday, with the Stoxx 600 adding 0.5%, mainly boosted by tech shares amid spill over effects from upbeat quarterly results from Alphabet. In Europe, TeamViewer announced a share buyback program of up to €300M and confirmed its 2022 guidance, as revenues rose 9% in 4Q and 10% considering the whole FY21, despite a narrower operating profits margin. Spain’s largest bank, Santander, posted upbeat Q4 earnings and pledged to increase profitability further on expectations of higher interest rates. Meanwhile, traders continue to follow the standoff between Russia and the West over Ukraine, with the US sending more 2000 troops to Europe. On the data front, the Eurozone's annual inflation hit a fresh record of 5.1% in January and all eyes now turn to the ECB monetary policy decision tomorrow for any updates on the central bank inflation outlook and tightening plans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 00:50:58 </td>
   <td style="text-align:left;"> French Stocks Extend Gains </td>
   <td style="text-align:left;"> The CAC 40 Index closed 0.2% higher at 7,115 on Wednesday, supported by the technology and commodity-backed sectors as investors digested the latest Eurozone inflation data and US labor market data, while monitoring corporate earnings and geopolitical tensions in between Russia and NATO members. Consumer prices in the euro area jumped by a record-high 5.1% on the year during January, compared to market expectations of 4.4%, adding pressure to ECB policymakers ahead of their meeting tomorrow. Tech stocks rose 1.5%, led by Dassault Systemes (2.2%). Solvay gained 3% after announcing it would invest EUR 300 million to increase the production capacity of polyvinylidene fluoride, an essential chemical compound for lithium-ion batteries. In the meantime, Atos jumped 8.2% amid rumors that Thales wishes to acquire the cyber-security branch of the French IT service provider. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/albania/interest-rate </td>
   <td style="text-align:left;"> 2022-02-03 00:50:28 </td>
   <td style="text-align:left;"> Albania Interest Rate Steady at 0.5% </td>
   <td style="text-align:left;"> The Bank of Albania held its policy rate unchanged at 0.5% during its February 2022 meeting, noting that economic activity in Albania continues to recover, labour market indicators are improving, but inflation has risen sharply in the last two months. The inflation is expected to rise above the target of 3 percent in 2022 but to return sustainably to the target level starting from 2023. At the same time, the overnight deposit rate remained at 0.1% and the overnight loan rate was left steady at 0.9%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/02/the-spac-market-starts-2022-with-abysmal-losses-abandoned-deals.html </td>
   <td style="text-align:left;"> 2022-02-03 00:50:21 </td>
   <td style="text-align:left;"> The SPAC market starts 2022 with abysmal losses, abandoned deals </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                    , (Click here to subscribe to the new Delivering Alpha newsletter.)                                                                                                                                                                                                                                                  , The oversaturated SPAC market is continuing to get crushed in the new year as speculative stocks with little earnings fall further out of favor in the face of rising rates, while a growing number of deals were abandoned in the tough environment.                                                              , Companies that went public via blank-check deals have been among those worst affected by January's tech-driven sell-off. Meanwhile, faced with unfavorable market conditions, many sponsors have been forced to scrap their proposed deals, sometimes even before the SPACs got listed.                            , "The SPAC bubble is bursting," said Chris Senyek, senior equity research analyst at Wolfe Research. "SPAC shares are extremely volatile due to their speculative nature."                                                                                                                                          , The proprietary CNBC SPAC Post Deal Index, which is comprised of SPACs that have completed their mergers and taken their target companies public, tumbled 23% in January, even more abysmal than the tech-heavy Nasdaq Composite's 9% loss when it suffered the worst month since March 2020.                      , Some of the biggest losers last month included clean energy player Heliogen, self-driving related companies Aurora Innovation and Embark and 3D technology company Matterport, which all tumbled more than 50% in a single month.                                                                                  , SPACs stand for special purpose acquisition companies, which raise capital in an initial public offering and use the cash to merge with a private company and take it public, usually within two years.                                                                                                            , The market enjoyed a record year with more than $160 billion raised on U.S. exchanges in 2021, nearly double the prior year's level, according to data from SPAC Research. Investors once piled into shares of these empty corporate shells hoping they would hit a home run.                                      , After a year of issuance explosion, there are now almost 600 SPACs searching for an acquisition target, according to SPAC Research. As the market gets increasingly competitive, some announced deals failed to make it to fruition.                                                                               , The planned merger of Fertitta Entertainment and the blank-check firm Fast Acquisition Corp was called off at the end of last year. Recent deals that have been abandoned also included online grill retailer BBQGuys, fintech firm Acorns and cloud software platform ServiceMax.                                 , Meanwhile, there has been a growing number of SPAC listing withdrawals, meaning the sponsors decided to pull the plug on their listing after filing the initial S-1. There were nearly 20 such cases in the month of January, a jump from only single digits in the prior two quarters, according to SPAC Research., — CNBC's Gina Francolla contributed reporting.Disclosure: NBCUniversal and Comcast Ventures are investors in Acorns, and CNBC has a content partnership with it.                                                                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                   , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Extend Rally After Inflation Increase </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 0.6% higher at 27,389 on Wednesday, aided by the banking sector as investors digested the latest inflation data while anticipating the ECB's forward guidance ahead of the bank's policy meeting tomorrow. Consumer prices in the euro area jumped to a record-high 5.1% on the year during January, compared to market expectations of 4.4 percent. At the same time, domestic prices surged to a near 26-year high of 4.8%, significantly higher than market expectations of 3.8%. Banks traded in the green, led by UniCredit (3.2%) after Berenberg released data indicating the Italian bank can beat its profit targets by 12.5% this year and 14% by the end of 2024. Banco Bpm (2.4%) and Intesa Sanpaolo (1%) also booked gains. Also, Ferrari gained 1.6% after posting net profits of EUR 833 million for 2021, 37% higher than last years and beating market expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 00:46:00 </td>
   <td style="text-align:left;"> UK Stocks Extend Gain To Near 2-Week High </td>
   <td style="text-align:left;"> The FTSE 100 rose 0.8% to close at 7,592 on Wednesday, in line with mostly its European peers, and extending gains for a second session to near a two-week high, on strong earnings reports and as traders awaited the second rate hike from the Bank of England. Online supermarket Ocado climbed almost 6% after Credit Suisse double upgraded the stock to “outperform” and raised its price target and Auto Trader gained more than 4% after Jefferies bumped up its price target. Also, Vodafone rose as much as 3% after the company said it was on track to meet its full-year guidance and posted a 2.7% rise in Q3 group service revenue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 00:45:17 </td>
   <td style="text-align:left;"> The FTSE 100 Index rose 0.78% </td>
   <td style="text-align:left;"> United Kingdom Stock Market rose 59 points. Leading the gains are Ocado Group (4.86%), Auto Trader Group (4.23%) and Vodafone (3.20%). Top losers were Antofagasta (-4.88%), Rolls-Royce (-1.52%) and Fresnillo (-1.51%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/cnn-president-jeff-zucker-resigns/story.aspx?guid={6A716604-D068-4C59-88C4-E0F4F65C7D8F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-03 00:37:09 </td>
   <td style="text-align:left;"> CNN President Jeff Zucker resigns after failing to disclose relationship with coworker - MarketWatch </td>
   <td style="text-align:left;"> CNN President Jeff Zucker has resigned from his post after failing to disclose a romantic relationship with a co-worker, Zucker himself announced in a message to employees. Zucker said he was asked about a consensual relationship with his closest colleague as part of the network's investigation of anchor Chris Cuomo's tenure at CNN, a person he said he had worked with for more than 20 years. "I acknowledged the relationship evolved in recent years. I was required to disclose it when it began but I didn't. I was wrong," he wrote. He expressed regret that his tenure was ending in such a way. Zucker joined CNN in January 2013. CNN parent AT&amp;T Inc.'s stock  
        T,
        +0.49%
       was down 0.5% Wednesday.
, Here's what the chief executive of ARK Invest had to say.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Ciara Linnane is MarketWatch's investing- and corporate-news editor. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-60231055?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-03 00:35:50 </td>
   <td style="text-align:left;"> Wordle code could be copied to play for seven years </td>
   <td style="text-align:left;"> The code that powers the website of the viral puzzle game Wordle can be copied and saved to continue playing it for the next seven years, it has been revealed.                                                                             , The finding comes amid concerns that the game's sale to the New York Times may mean it stops being free to play.                                                                                                                            , The code, written in Javascript, appears as plain text for those who know how to access it.                                                                                                                                                 , Some publications have even printed a step by step guide of how to do it.                                                                                                                                                                   , "Effectively you can keep a version of the game as it exists today with enough data to keep you going for a long time," said Prof Alan Woodward, a computer scientist from University of Surrey.                                            , But, he added: "As you have the words stored locally it might be tempting to cheat, and where's the fun in that?"                                                                                                                           , He added it would not be "too difficult" to split the question grid from the answers.                                                                                                                                                       , "You'd need to hold the data in a file that was inaccessible other than to the game. In essence split the data file of words from the functionality you see when playing."                                                                  , That may sound like a lot of effort for a daily word game that challenges users to find a five-letter word in six guesses, with clues along the way.                                                                                        , But having risen from a handful of players to millions in just a few months, some may be willing to try.`                                                                                                                                   , This video can not be played                                                                                                                                                                                                                , The creator Josh Wardle recently sold his game to the New York Times for a seven-figure sum. He had originally said he did not want to make any money from the game he created as a distraction for himself and his partner during lockdown., And copying the code may carry legal risk.                                                                                                                                                                                                  , Nick Allan, legal director at law firm Lewis Silkin, told the BBC: "The particular expression of the software code underlying a game like Wordle will be protected as a literary copyright work under UK copyright law," he said.           , "It is not possible to waive UK copyright, and the copyright provided on the Wordle website is not obviously licensed to the general public on a free, perpetual open-source basis.                                                         , "Unless Mr Wardle has provided this type of general licence to the public, he or the New York Times are likely to still retain the right to enforce the copyright as they see fit."                                                         , That means that anyone replicating it or creating a clone game could be liable for copyright infringement, at least in the UK courts.                                                                                                       , It might be possible, added Mr Allan, to create a game using different lines of code that achieve the same result.                                                                                                                          , "Either way this is a complex area, fraught with legal risk for anyone thinking of using this code to release their own Wordle."                                                                                                            , And it is likely that the website will be completely re-engineered when the New York Times takes charge.                                                                                                                                    , How one ship triggered a global crisis...                                                                                                                                                                                                   , An extraordinary family and their passion for climbing                                                                                                                                                                                      , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/02/lux-capitals-josh-wolfe-on-why-the-buy-the-dip-mantra-will-no-longer-work.html </td>
   <td style="text-align:left;"> 2022-02-03 00:33:56 </td>
   <td style="text-align:left;"> Lux Capital's Josh Wolfe on why the buy-the-dip mantra will no longer work </td>
   <td style="text-align:left;"> , (Click here to subscribe to the new Delivering Alpha newsletter.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Lux Capital invests in emerging science and technology companies, making long-term bets on contrarians in the space. Over two decades, the firm has grown to manage $4 billion in assets.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Josh Wolfe is the futurist fund manager leading the charge at Lux Capital. He has an acute read on scientific innovation and technological breakthroughs to which investors should be paying close attention. Wolfe sat down with CNBC's Delivering Alpha newsletter to discuss his investing outlook, along with where he sees the most promising opportunities right now.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , (The below has been edited for length and clarity. See above for full video.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Leslie Picker: I just wanted to start first with your broader read on the markets right now. Do you think that especially in some of the key pockets of tech, and growth, is this just some air coming out of the tires a bit or a full revaluation of the sector?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Josh Wolfe: I think in some sectors, it's a mix. I think you've got a flat tire in some sectors. We're looking at probably, in my estimation, a greater than 60% chance that we are in March of 2000 for a broad segment of the market that has been very overvalued. And that means that we're probably going to, for an 18 month period till, say October 2001, where you saw about an 80% decline in some of the most popular names. And that 80% decline happened by 50 basis points, 1% drops over a long period of time, which was a measure of people's belief, clinging, that this was going to continue. You've had five, six years where buy the dip has been the mantra and it has worked. And I think it's no longer going to work and you're going to see revaluation across specifically some segments of the market, but largely across high-growth tech and speculation and the stuff that we specialize in.                                                                                                                                                                                                                                                                                                                                                                                        , Picker: What are you telling your portfolio companies to do in light of this?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Wolfe: Three words: husband your cash. Hold on to the cash that you've raised. We've had companies that have gone public through SPACs, we've had companies that have done direct listings, companies that have gone public through traditional IPOs – the amount of cash that was delivered to balance sheets of Lux portfolio companies, and many companies around the world, is unprecedented. You've got hundreds of millions of dollars for companies that are burning, maybe $10 million a quarter, something like that. So you've got maybe a decade of cash. What you do with that cash now is the most important capital allocation decision that a management team and a board can make. And in our judgment, the most important thing you can do is husband that cash. Investing now, if we're going into any kind of recessionary times, is going to be like spitting against the wind, where that cash is going to be ill served going after growth. Instead, make sure you have a fortress balance sheet, look at your weaker competitors, consolidate customers, technologies, positions, I think you're going to see a huge M&amp;A boom over the next year.                                                                                                                                            , Picker: One of the big aspects of valuation growth in Silicon Valley has just been the amount of capital that's been circulating over the last, five, six, seven years. Do you see that slowing down anytime soon, given what we're seeing in the public markets? And will that impact the valuations that companies are able to get as well as the capital that they're able to get moving forward?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Wolfe: And emphatic yes, yes and yes. Now the way that I think about this, there's going to be some segments of the market, again, that are flush with cash. A lot of funds have been raised. We closed a billion and a half just six months ago, with a lot of dry powder to deploy. Now the speed with which we're doing that is going to be much slower than it was say, a year ago or two years ago…So I think that the next year you're going to see LP indigestion, GPs slowing their pace, companies in the private markets seeing valuations come down, akin to what you are seeing predictably in the public markets.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Picker: Because typically, there is a lag. Only recently have we started seeing reports come out that companies are willing to take lower valuations as a result of what's going on right now. But at least over the last few years, and especially during - surprisingly - during COVID, many private companies still were able to maintain pretty decent valuations and a lot of them were able to double or triple their valuation. So you think this time is actually different and we will see sort of that 2002 period where startups really have to kind of bootstrap it for a while.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Wolfe: In the private markets, the latest valuation is set by the marginal price setter. And in many cases, historically, that might have been SoftBank. That might be some of the large crossover hedge funds that are doing private deals. And they were basically saying relatively indiscriminately, "We're gonna' buy the winner in the company. Does it really matter what price we pay? No, particularly if we have great terms." ... If you're senior preferred in the capital structure of these companies, you're in a great position. So I do think that you're going to see a situation where private companies are going to go through a discriminating narrowing, meaning the crossover hedge funds, the late-stage growth investors and even the early stage investors are going to be way more discriminating. And [it's] going to be dominated by, I'll give you an acronym, instead of FOMO, Fear Of Missing Out, It's what I call SOBS, the shame of being suckered. People do not want to be suckered in this current moment.                                                                                                                                                                                                                                                                   , Picker: I do like that acronym. I wonder if it will ultimately take hold, because I think a lot of investors have been waiting, especially those that have been in Silicon Valley for a while, I've heard the term tourist investors for some of the public-private investors that do both sides, crossover investors, that they don't expect them to be around for a while. Do you agree with that? Do you think that ultimately we do see people kind of just exit this part of the market entirely?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Wolfe: I think it's true of every industry through time, right? You see a huge number of entrants then a precipitous pruning as the numbers decline over time. What the wise person does in the beginning, the fool does in the end. This happens within sectors, it happens within investment sub sectors. So you saw this, you know, 2002 to 2007, with the rise of activist hedge funds or active long short hedge funds, then there was a pruning post-crisis…There will be survivors. There will be great investors that come out of this market, there will be great new firms that form, and there will be a significant culling of the herd. I would predict that between 50% and 75% of the active investors in private markets today will disappear within the next few years.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Picker: Are you putting capital to work right now? Are you kind of hunkered down to see how this all shakes out? Or are you really just looking to sit this out for the long term?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Wolfe: Well, for our existing companies, we've got fortress balance sheets and we're telling them, "Consolidate your position, do it as quietly as you can, do it as loudly as you can, but just do it." For new investments, we're becoming more discriminating on price. We're not participating in any auctions. We're not doing deals that are closing because of this FOMO in a day or two, because you got 40 competing term sheets. We're playing the long game. Now the beautiful thing about the long game is you can invest in deep science and deep technology in these cutting edge areas where there are few investors and few companies. We're not investing in areas where there's 500 or even 50 competitors. In many cases, we're investing in a sector where there might be only one, two, or three companies. You capitalize that company, you bet on the right management team and you can withstand whatever's happening in the macro for five, six, seven years and make sure these companies are well capitalized. At the end of the day, we're not buying indexes. We're not passive investors, we're active investors, we're sitting on boards. We're helping grow these companies from inception, providing them talent and competitive intelligence and future financing, risk reduction., I always say that it's sort of like in our business, trying to pick the best meal on a menu after you've selected the best menu in the best restaurant in the best city in the best state in the best country and you're about to eat a morsel of that delicious bite that you've selected, and all of a sudden Godzilla comes and steps on the on the restaurant. Ignorance of the macro is no virtue. You have to pay attention to what is going on in the context of capital markets, inflows, price setting where money is flowing, what the Fed is doing. A lot of people are not focused on that kind of stuff. We historically always pair a little bit of macro understanding and the global situation into our micro investments and security selection on the entrepreneurs we're betting and the companies that we're building.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Picker: Do you see any specific opportunities right now that you're excited about?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Wolfe: You know, there are two big themes that we're really capitalizing on. And we broadly say we're prepared to pounce. So one of them is in hard power and one of them is in soft power. Both of these relate to geopolitical instability. In the geopolitical stage, you've got a revanchist Russia, you've got a rising China, you have a cold war really between these two powers, a bifurcation of financial systems, surveillance systems, internet technology. And so on the hard power side, every facet of aerospace and defense is something that we think the U.S. and its allies needs cutting edge technology. You've had 20 years of Zeitgeist where people have really been loath in this military industrial complex to want to provide cutting edge technology to the women and men that are on the frontlines of war, whether that's Special Operations, Air Force, Space, Force, Army, etc. And so we are very focused on providing technology through many of our investments, to the defense industry.                                                                                                                                                                                                                                                                                       , And I think you're going to see a resurgence and reemergence of some of the next gen primes and people that are going to compete with Lockheed and Raytheon and General Atomics, et al. in air, space, land and sea – autonomous systems, artificial intelligence, machine learning, cutting edge tools and technologies that are very expensive, very risky and in many cases, people have been loath to only focus on a government customer like the Department of Defense or the Pentagon, or allies. We're entirely comfortable doing it and we think it's geopolitically important…You've got north of 14 sovereigns that are now racing to get to space...and so there's a lot of competition to launch things into space, have satellites, antennas, communication, lots of technologies that were invested in across [those] platforms from literally launch all the way up through space.                                                                                                                                                                                                                                                                                                                                                                                                                  , On the soft power piece….we're convinced, and people have not really picked up on the steam yet, but what we call the tech of science, there's going to be a huge boom and demand globally, but particularly for the U.S. pharma companies, biotech companies, academics, U.S. government labs, for the technologies that improve science and give us a competitive advantage to win on the global stage, what is really prestige, globally.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-02-03 00:24:04 </td>
   <td style="text-align:left;"> Brent Extends Losses For 2nd Day </td>
   <td style="text-align:left;"> Brent crude futures traded below $89 per barrel on Wednesday, after trading above $90 per barrel early in the session, and extending the last session 0.1% losses as OPEC+ stuck with its target of a monthly increase of 400Kbps per day, in line with market forecasts, but traders start to bet the group will be unable to meet its production targets once again. Meanwhile, on the data front, US crude oil inventory figures showed that stocks unexpectedly fell for the first time in 3 weeks, while also an industry report yesterday indicated an unexpected 1.6 million barrel draw from domestic storage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/industrial-production </td>
   <td style="text-align:left;"> 2022-02-03 00:10:52 </td>
   <td style="text-align:left;"> Russia Industrial Output Grows Well Above Expectations </td>
   <td style="text-align:left;"> Industrial production in Russia rose 6.1 percent year-on-year in December of 2021, easing from an upwardly revised 7.6 percent increase in the previous month and beating market expectations of a 3.9 percent gain. It was the tenth straight month of growth in industrial activity, boosted by; mining production (10 percent), manufacturing (4.3 percent), and utilities (1.9 percent). On a monthly basis, industrial output jumped 12.5 percent, accelerating from a 1.3 percent growth in the previous period. For the whole year of 2021, the industrial output grew 5.9 percent when compared to 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/02/business/media/jeff-zucker-cnn.html </td>
   <td style="text-align:left;"> 2022-02-03 00:04:49 </td>
   <td style="text-align:left;"> Jeff Zucker Resigns From CNN After Relationship With Top Executive - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The relationship came up during the network’s investigation into the former anchor Chris Cuomo. “I was required to disclose it when it began but I didn’t,” Mr. Zucker wrote in a memo to colleagues.                                                                                                                                                                                                                                                                                                      , By Michael M. Grynbaum and John Koblin                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Jeff Zucker resigned on Wednesday as the president of CNN, departing one of the most powerful positions in American media after acknowledging that he had failed to disclose a romantic relationship with another senior executive at the network.                                                                                                                                                                                                                                                         , The sudden end of Mr. Zucker’s nine-year tenure stunned his newsroom and threw CNN’s future into flux at a crucial moment: The network is about to introduce a high-stakes streaming service, and its parent company, WarnerMedia, is on the verge of being acquired by Discovery Inc.                                                                                                                                                                                                                     , Mr. Zucker, 56, wrote in a memo on Wednesday that his relationship had come up during an internal investigation into the conduct of Chris Cuomo, the CNN anchor who was fired in December over his involvement in the political affairs of his brother, former Gov. Andrew M. Cuomo of New York.                                                                                                                                                                                                           , “I was asked about a consensual relationship with my closest colleague, someone I have worked with for more than 20 years,” Mr. Zucker wrote. “I acknowledged the relationship evolved in recent years. I was required to disclose it when it began but I didn’t. I was wrong.”                                                                                                                                                                                                                            , He was referring to Allison Gollust, CNN’s executive vice president and one of the network’s highest-ranking leaders, who said on Wednesday that she would remain at CNN.                                                                                                                                                                                                                                                                                                                                  , “Jeff and I have been close friends and professional partners for over 20 years,” Ms. Gollust wrote. “Recently, our relationship changed during Covid. I regret that we didn’t disclose it at the right time.”                                                                                                                                                                                                                                                                                             , Both Mr. Zucker and Ms. Gollust are divorced. Mr. Zucker is also leaving his role as WarnerMedia’s chairman of news and sports.                                                                                                                                                                                                                                                                                                                                                                            , A leader in the television industry for 30 years, Mr. Zucker is the rare behind-the-scenes executive whose name recognition rivaled that of the anchors he oversees. He is perhaps best known for hiring Donald J. Trump to star in “The Apprentice” on NBC — and then clashing with his onetime employee after Mr. Trump became a media-bashing politician who castigated CNN.                                                                                                                            , In keeping with a career at the center of the news industry, Mr. Zucker’s exit on Wednesday was entwined with another dramatic story line: the downfall of the once-powerful Cuomo brothers.                                                                                                                                                                                                                                                                                                               , Chris Cuomo has fiercely contested the terms of his departure from CNN, which has refused to pay the anchor’s severance or honor the remainder of his current contract, saying he engaged in unethical conduct. Mr. Cuomo has retained the powerful Hollywood litigator Bryan Freedman.                                                                                                                                                                                                                    , In discussions with WarnerMedia lawyers, Mr. Cuomo’s legal team raised the subject of Mr. Zucker’s relationship with Ms. Gollust, according to two people briefed on the matter, who spoke on the condition of anonymity to discuss private conversations.                                                                                                                                                                                                                                                 , Early last week, both Mr. Zucker and Ms. Gollust were asked about their relationship by lawyers from Cravath, Swaine &amp; Moore, a law firm that WarnerMedia had retained to investigate Mr. Cuomo’s tenure at the network, according to two people briefed on internal deliberations.                                                                                                                                                                                                                        , Lawyers from Cravath were interviewing CNN officials broadly about Mr. Cuomo’s tenure and the events that led to his termination, in part because CNN executives believed the dispute could eventually lead to litigation, according to the two people, who spoke on the condition of anonymity to discuss company business. Mr. Cuomo’s lawyers sent a letter asking CNN to preserve messages between Mr. Zucker, Ms. Gollust, Andrew Cuomo and Andrew Cuomo’s staff.                                     , Among other matters, days before Mr. Cuomo’s firing, CNN had been informed of an accusation of sexual misconduct against the anchor by a former junior colleague at another network. Mr. Cuomo has denied the accusation.                                                                                                                                                                                                                                                                                  , WarnerMedia’s chief executive, Jason Kilar, spoke with Mr. Zucker after the interviews and informed the CNN president that he could not remain at the company, two people briefed on their discussion said. Mr. Zucker offered to stay on for a transition period as the network found a new leader, but Mr. Kilar rejected that suggestion, one of the people said.                                                                                                                                       , A hands-on manager who whispers in anchors’ earpieces and calls into the control room at odd hours, Mr. Zucker had been absent from his usual editorial calls in recent days. But even some of his closest confidants had no idea that he was on the verge of an exit. In the CNN newsroom, where Mr. Zucker commands fierce loyalty, journalists and producers were left stunned.                                                                                                                         , “This is an incredible loss,” the anchor Alisyn Camerota said on a broadcast on Wednesday. “These are two consenting adults who are both executives. That they can’t have a private relationship feels wrong.”                                                                                                                                                                                                                                                                                             , Mr. Zucker and Mr. Cuomo were once close. Mr. Zucker recruited the anchor to CNN from ABC News, and he stood by Mr. Cuomo for months even after revelations that he had advised aides to Andrew Cuomo on how the governor could fend off a sexual harassment scandal.                                                                                                                                                                                                                                      , Ms. Gollust also has a connection to the Cuomo family: She served as communications director to Andrew Cuomo, then the governor, for four months in 2012 and 2013.                                                                                                                                                                                                                                                                                                                                         , But Mr. Zucker’s support dwindled in December after more details emerged about Chris Cuomo’s involvement, including efforts to uncover the status of articles at other news outlets.                                                                                                                                                                                                                                                                                                                       , Mr. Kilar, who is based in Los Angeles, visited New York and Washington on Wednesday to address CNN executives, saying he had accepted Mr. Zucker’s resignation. He announced that three executives — Michael Bass, Amy Entelis and Ken Jautz — would jointly lead CNN on an interim basis through what he anticipated would be “the close of the pending transaction with Discovery.”                                                                                                                     , Mr. Kilar, a former head of Hulu, had been perceived as losing power to Mr. Zucker after the Discovery deal was announced. AT&amp;T, the parent company of WarnerMedia, neglected to inform Mr. Kilar about the pending merger until shortly before it was announced and he had been widely expected to leave once it was completed. And Mr. Zucker is close friends with David Zaslav, the Discovery chief executive who is poised to be the leader of the newly combined company.                            , AT&amp;T is run by John Stankey, who was Mr. Zucker’s boss and the head of WarnerMedia from June 2018 through April 2020. Representatives for both AT&amp;T and Discovery declined to comment.                                                                                                                                                                                                                                                                                                                     , Mr. Zucker rose to prominence in the early 1990s when he became the wunderkind executive producer of NBC’s “Today” show and made stars of Matt Lauer and Katie Couric. He became chief executive of NBCUniversal in 2007 before he was ousted from the company in 2010. Battling a series of medical ailments throughout his career, he began a comeback by joining CNN in January 2013, eventually becoming a public face of the network in large part because of his complex relationship with Mr. Trump., CNN was criticized during the 2016 presidential campaign for granting enormous amounts of airtime to speeches by Mr. Trump. But as Mr. Trump hardened against CNN, he publicly vilified Mr. Zucker and often joined his supporters in chants of “CNN sucks,” making the network a symbol of what he called a biased press. CNN itself brought on anti-Trump commentators, and its programming tilted toward more opinionated territory under Mr. Zucker’s reign.                                           , Mr. Trump celebrated Mr. Zucker’s resignation on Wednesday, claiming in a statement that Mr. Zucker had been “terminated for numerous reasons, but predominantly because CNN has lost its way with viewers and everybody else.”                                                                                                                                                                                                                                                                            , Fox News, whose coverage is often criticized by CNN commentators, also featured Mr. Zucker’s exit on Wednesday, running a headline at the top of its website saying he “resigns in disgrace.” An accompanying article said Mr. Zucker had “personally allowed” CNN to “drift from a just-the-facts news operation to a hyperpartisan opinion platform.”                                                                                                                                                    , In recent months, Mr. Zucker had been focused on the shaping of CNN+, a subscription streaming service that is set to begin this spring and a major financial bet for WarnerMedia. Mr. Zucker was involved in enticing big names like Eva Longoria, the NPR star Audie Cornish and the former Fox News anchor Chris Wallace to join the fledgling streaming network. CNN will now proceed into an uncertain digital future without its longtime leader at the helm.                                        , “Together, we had nine great years,” Mr. Zucker wrote in his memo on Wednesday. “I certainly wish my tenure here had ended differently. But it was an amazing run. And I loved every minute.”                                                                                                                                                                                                                                                                                                              , Katie Robertson contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-02 23:56:00 </td>
   <td style="text-align:left;"> Oil Futures Fall after OPEC </td>
   <td style="text-align:left;"> WTI crude futures fell below $88 per barrel on Wednesday after rising more than 1% to $89.6 early in the session, but remaining close to 2014 levels, as investors digest the supply outlook. OPEC+ agreed to increase oil production by 4000,000 bps in March, in line with market forecasts, but traders wonder if the group will be able to meet its own production targets. In January, crude output was raised by 210,000 additional barrels per day only instead of the 400,000 bpd that the group agreed to. Meanwhile, Iran is ready to return to the oil market as quickly as possible, the Iranian Oil Minister Javad Owji said. In the US, EIA data showed US crude stocks fell for the first time in 3 weeks in late January, with stocks at Cushing Oklahoma also falling while gasoline inventories were up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-02 23:52:54 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield Eases From Near 1-Week High </td>
   <td style="text-align:left;"> The yield on the Canadian 10-year government bond traded around 1.75%, after hitting a near one-week high of 1.792% on February 2nd, and tracking US treasury yields lower as investors remain cautious ahead of the payrolls report on Friday and wonder what the tightening path from the Fed will be. In the US, fresh ADP data showed private companies unexpectedly cut 301K jobs in January, a sign the impact of the omicron coronavirus variant may be bigger than initially anticipated. Meanwhile, domestically, the BoC during its last monetary policy decision dashed some investors' expectations after leaving the interest rate steady. The central bank, however, signaled a rise in interest rates will happen soon, money markets expect the first hike in March and at least five in total this year. Also, Canada’s jobs report for January, on February 4th, could provide further clues on the domestic economic recovery and, consequently, for the next steps of BoC. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/race:im </td>
   <td style="text-align:left;"> 2022-02-02 23:46:04 </td>
   <td style="text-align:left;"> Ferrari NV earnings above expectations at 1.16 EUR </td>
   <td style="text-align:left;"> Ferrari NV (RACE) released earnings per share at 1.16 EUR, compared to market expectations of 1.07 EUR. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/02/crypto-exchange-ftx-to-buy-japanese-rival-liquid.html </td>
   <td style="text-align:left;"> 2022-02-02 23:45:49 </td>
   <td style="text-align:left;"> Crypto exchange FTX to buy Japanese rival Liquid for Asia expansion </td>
   <td style="text-align:left;"> , FTX, the cryptocurrency exchange owned by billionaire Sam Bankman-Fried, is buying Japanese rival Liquid for an undisclosed sum.                                                                                                                                                                                                                                        , The company said Wednesday it had entered into an agreement to acquire Liquid and all its operating subsidiaries, including Quoine Corporation and its Singapore-based unit. Quoine was one of the first crypto exchanges to obtain registration with Japan's Financial Services Agency in 2017.                                                                        , FTX said it expects the acquisition of Liquid to close by March 2022. The deal is subject to regulatory and shareholder approval.                                                                                                                                                                                                                                       , "Following FTX's acquisition of Liquid, Quoine will gradually integrate FTX's products and services into its own offering, and FTX's existing Japanese customers will be migrated to Quoine's platform," Liquid said in a statement Wednesday.                                                                                                                          , "In connection with this acquisition, FTX has also entered into an agreement with Liquid to provide its existing Japanese users with services in compliance with Japanese laws, and will transfer its existing Japanese users to Quoine."                                                                                                                               , FTX, which earlier this week announced it had raised $400 million at a $32 billion valuation, is expanding aggressively in the Asian crypto market at a time when competition in the space is heating up.                                                                                                                                                               , Bankman-Fried told CNBC a large focus for the firm was acquiring licenses in several countries.                                                                                                                                                                                                                                                                         , Traditional lenders like Japan's SBI and Singapore's DBS have been making moves in the space to capitalize on crypto's wild growth. SBI is a minority shareholder in a number of crypto start-ups, including the $15 billion company Ripple, while DBS has set up its own digital asset exchange.                                                                       , Founded in 2014, Liquid is one of the world's largest crypto exchanges by volume, with nearly $72 million in daily trading volumes, according to CoinMarketCap data. It offers both spot trading in digital currencies such as bitcoin, ether and XRP, and financial derivatives which allow investors to speculate on price movements.                                 , The company suffered a major hack last year which saw the cybercriminals make off with more than $90 million worth of funds. Not long after the attack, FTX lent Liquid $120 million in debt financing. Liquid at the time said the funds would be used to "strengthen its capital position," and that the two firms would pursue "further collaborative opportunities.", Bahamas-based FTX offers crypto spot trading and derivatives products in a number of territories around the world — with the exception of the U.S., where its services are provided by an affiliate called FTX U.S.                                                                                                                                                     , FTX U.S. last week said it had raised $400 million in its first external fundraise, in a deal valuing the company at $8 billion.                                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/eia-data-show-decline-weekly/story.aspx?guid={286AF79D-9A29-4FDE-ABAB-F79E4615F001}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 23:41:34 </td>
   <td style="text-align:left;"> EIA data show a decline in weekly U.S. crude supplies, but gasoline stockpiles edge higher - MarketWatch </td>
   <td style="text-align:left;"> The Energy Information Administration reported on Wednesday that U.S. crude inventories fell by 1 million barrels for the week ended Jan. 28. On average, analysts had forecast an increase of 1.1 million barrels, according to a poll conducted by S&amp;P Global Platts. The American Petroleum Institute on Tuesday reported a 1.6 million-barrel decrease, according to sources. The EIA also reported a weekly inventory climb of 2.1 million barrels for gasoline, while distillate stockpiles fell by 2.4 million barrels. The S&amp;P Global Platts survey expected a supply climb of 1.7 million barrels for gasoline, but an inventory decline of 1 million barrels for distillates. The EIA data showed crude stocks at the Cushing, Okla., Nymex delivery hub edged down by 1.2 million barrels for the week. Oil futures continued to trade lower in the wake of the OPEC+ decision to boost output by 400,000 barrels per day in March, as expected. The March West Texas Intermediate crude contract 
        CLH22,
        -0.66%
       was down 83 cents, or 0.9%, at $87.37 a barrel on the New York Mercantile Exchange. It traded at $87.85 before the supply data., Here's what the chief executive of ARK Invest had to say.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/crude-oil-stocks-change </td>
   <td style="text-align:left;"> 2022-02-02 23:37:00 </td>
   <td style="text-align:left;"> US Crude Stocks Unexpectedly Fall </td>
   <td style="text-align:left;"> Stocks of crude oil in the United States fell by 1.046 million barrels in the week ended January 28th, the first decline in three weeks, and compared to forecasts of a 1.525 million rise, data from the EIA Petroleum Status Report showed. Crude stocks at the Cushing, Oklahoma, delivery hub were down by 1.2 million barrels and distillate stockpiles which include diesel and heating oil, fell by 2.4 million barrels. Meanwhile, gasoline inventories increased by 2.119 million, above forecasts of 1.645 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/02/politics/dean-heller-nevada-2020-election/index.html </td>
   <td style="text-align:left;"> 2022-02-02 23:35:38 </td>
   <td style="text-align:left;"> Dean Heller: This former Republican senator has a ridiculous reason for believing the Big Lie - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)When Dean Heller served in the Senate, he was known, primarily, as a pragmatic moderate -- a fitting political profile for someone representing a swing state like Nevada.                                                                                                                                                                                                                                                                                                                                                                                               , Now, however, Heller is running for governor -- and he has decided to bow at the altar of Donald Trump.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , On Tuesday, Heller told a reporter for the Las Vegas Review Journal that "he thinks Joe Biden is an illegitimate president." The Nevada independent followed up on that pronouncement; "Dean said that 71% of Republicans in Nevada believe Biden is an illegitimate President and that he is part of that 71%," explained a spokesman for the campaign.                                                                                                                                                                                                                       , So, Heller, who wants to be the chief executive of one of our 50 states, believes that Joe Biden didn't win because, um, a lot of other Republicans in the state think that? (A spokesman later told the Review Journal that "he meant to say most Republicans in the state think Biden is an illegitimate president.")                                                                                                                                                                                                                                                        , I did some digging on the Interwebs and -- surprise surprise! -- couldn't find the poll that Heller's campaign referenced in which 7 in 10 Republicans say Biden didn't beat Donald Trump fair and square in 2020.                                                                                                                                                                                                                                                                                                                                                             , When I asked the campaign, they offered some conspiracy theories about the 2020 election but didn't produce the so-called poll.                                                                                                                                                                                                                                                                                                                                                                                                                                                , Regardless of whether the poll actually exists, we know for certain that there was not, in fact, widespread vote fraud in the 2020 election in Nevada -- a state that Biden won 50% to 48%.                                                                                                                                                                                                                                                                                                                                                                                    , Last April, following a review of a complaint by the Nevada Republican Party, Republican Secretary of State Barbara Cegavske announced that "our investigation revealed that these allegations and others are based largely upon an incomplete assessment of voter registration records and lack of information concerning the processes by which these records are compiled and maintained." She added that the claims made by the state party "do not amount to evidentiary support for the contention that the 2020 general election was plagued by widespread voter fraud.", Why, then, is Heller repeating the Big Lie? Simple -- he is hoping for a Trump endorsement and knows that the only way that will happen is to parrot the former president's false claim that the 2020 election was plagued by fraud.                                                                                                                                                                                                                                                                                                                                           , Heller has a lot of ground to make up with the Trumpian base of the party, as evidenced by the fact that he was booed at a recent Republican debate as he tried to position himself as the candidate closest to Trump in the crowded Republican primary.                                                                                                                                                                                                                                                                                                                       , The boos are likely a reflection of the rocky relationship the two men had when Heller was in the Senate. "What happened with Dean Heller is I tried for him, but my base did not believe him," Trump told The Nevada Independent in 2019. "They wouldn't go for him because Dean Heller was really hostile in my race." (In the wake of the release of the "Access Hollywood" tape in October 2016, Heller had said he was "99 percent certain" that he won't vote for Trump.)                                                                                                , Heller, then, knows he starts in a not-great place with Trump (and the party base). And that the only way to give himself a chance at a Trump endorsements is to insist -- contra facts -- that the election was somehow stolen from Trump. His campaign, however, should probably find a better explanation for Heller's position than citing polls.                                                                                                                                                                                                                          , It's not at all clear whether Heller can convince Trump that he has been transformed from a doubter to a true believer. What is clear is that Heller has flip-flopped mightily on Trump -- and done so for utterly transparent political reasons.                                                                                                                                                                                                                                                                                                                              , This story has been updated with additional comment from the Heller campaign.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/sugar </td>
   <td style="text-align:left;"> 2022-02-02 23:21:08 </td>
   <td style="text-align:left;"> Sugar Futures Ease on Higher Supply Outlooks </td>
   <td style="text-align:left;"> Raw sugar futures on ICE fell to the $18.1 level in the beginning of February, amid prospects of higher supply in the world’s major producers. Heavy rainfall in the center-south region of Brazil improved the outlook for cane production in the country's largest sugar growing area. Meanwhile, the Brazilian Economy Minister Paulo Guedes said the government is considering tax cuts on diesel in the near future to combat higher fuel costs, decreasing the outlook for ethanol prices and thus increasing sugarcane mills’ propensity to produce raw sugar instead. At the same time, the Indian Sugar Mill Association (ISMA) upwardly revised the country’s sugar production estimate by 3.1% to 31.45 million tonnes for the 2021/22 marketing year ending in October, mainly due to higher production from the western state of Maharashtra. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/oat </td>
   <td style="text-align:left;"> 2022-02-02 23:15:00 </td>
   <td style="text-align:left;"> Oat Prices Rose above 700 USD </td>
   <td style="text-align:left;"> Oat futures soared above 700 USd/Bu in the first week of February, moving closer towards an all time high of 779.5 USd/Bu hit in November. In 2021, oat prices increased around 90%, making it one of the fastest-growing commodities, on supply disruptions and higher demand. Also, the global demand for oats, which is mainly used for feeding livestock, is also high. It is expected that the oat future prices will increase as a result of a 40% reduction in planting oats in 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 23:09:11 </td>
   <td style="text-align:left;"> Stocks in Canada Rise on Wednesday </td>
   <td style="text-align:left;"> The S&amp;P/TSX was up for a 4th day to trade around the 21400 level on Wednesday, tracking most US stocks higher, and boosted by tech shares and energy stocks. The financials and industrials sectors were also in the green. Meanwhile, protests against anti-vaccine mandate and other COVID-19 restrictions continue in Ottawa are causing outrages and business closures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lumber </td>
   <td style="text-align:left;"> 2022-02-02 22:44:00 </td>
   <td style="text-align:left;"> Lumber Prices Lowest in 2 Months </td>
   <td style="text-align:left;"> Chicago lumber futures traded below $1,000 per thousand board feet, the lowest in almost 2 months, as the US market is set to cool down on rising interest rates and as the government is considering reducing the tariffs on Canadian wood. The average fixed 30-year mortgage rate in the US increased to 3.78% in the last week of January 2022 from 3.72%, hitting a new high since March 2020. Meanwhile, it was reported that the U.S. Department of Commerce plans to reduce tariffs for most Canadian softwood producers from almost 18 percent to 11.64 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 22:42:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Edge Lower </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, was down 0.6% to around 112,600 on Wednesday, following two straight sessions of gains, led by losses in shares of food processor BRF on discounted follow-on offering and Santander Brasil after the bank posted a lower-than-expected profit in the fourth quarter. Meanwhile, traders cautiously await the central bank monetary policy decision later in the day, anticipating a 150bps hike in the key Selic rate to 10.75% amid persistent inflationary pressures. The monetary statement is also expected to shed some light on the bank's strategy ahead. On the data front, Brazil's industrial activity rose 2.9% from a month earlier in December, above market estimates, leading to a 3.9% increase in 2021 that is yet to restore it to pre-pandemic levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/brinker-stock-soars-after-chilis/story.aspx?guid={350A7146-ADDC-4322-AC3A-0CB85F8AAD9A}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 22:41:03 </td>
   <td style="text-align:left;"> Brinker stock soars after Chili's parent reports earnings that blow past expectations - MarketWatch </td>
   <td style="text-align:left;"> Brinker International Inc. 
        EAT,
        +8.35%
       shares soared 11.8% in early Wednesday trading after the restaurant company reported fiscal second-quarter profit that far exceeded expectations. Net income totaled $27.6 million, or 60 cents per share, up from $12.0 million, or 26 cents per share, last year. Adjusted EPS of 71 cents blew past the FactSet consensus of 51 cents. Revenue of $925.8 million was up from $760.7 million and roughly in line with the FactSet consensus of $925.9 million. Comparable sales grew 17.7% with Chili's up 12.1% and Maggiano's soaring 78.1%.  Chili's sales totaled $791.9 million and Maggiano's sales reached $112.6 million. The FactSet consensus was for 20% growth. Both restaurant chain saw sales grow alongside higher dining room business. Chili's growth was offset by a decline in off-premise business. Brinker stock is down 36.4% over the past year while the S&amp;P 500 index 
        SPX,
        +0.94%
       has gained 19.6%., The average number of daily deaths from COVID-19 in the U.S. has climbed above 2,600, according to a New York Times tracker, now higher than the peak surge in the fall when delta was the dominant variant and close to the peak last winter, before vaccines were available.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 22:33:00 </td>
   <td style="text-align:left;"> Nasdaq and S&amp;P Extend 4-Day Winning Streak </td>
   <td style="text-align:left;"> The Nasdaq was up almost 1% and the S&amp;P 500 around 0.5% on Wednesday, extending gains for a 4th straight session, as the tech rally continued after upbeat earnings reports from big companies. The Dow Jones, however, traded around the flatline. Shares of Alphabet jumped almost 9% after its quarterly results topped forecasts and the company also announced a 20-for-1 stock split. Earnings from Advanced Micro Devices and GM also beat expectations but reports from Paypal and Starbucks were disappointing. Meta, Qualcomm and T-Mobile are also due to report earnings today after markets close. Meanwhile, investors appear to shrug off an unexpected 301K job loss last month reported by ADP. On Tuesday, JOLTS figures showed that job openings rose and the quit rate remained high in December. The highly-anticipated nonfarm payrolls are due Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rice </td>
   <td style="text-align:left;"> 2022-02-02 22:30:15 </td>
   <td style="text-align:left;"> Rice Hits 18-month High </td>
   <td style="text-align:left;"> Rice increased to a 18-month high of 15.26 USD/cwt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/nasdaq-bell-ringing-ceremony-featured-chinese-official-genocide-uyghur-muslims-lies </td>
   <td style="text-align:left;"> 2022-02-02 22:21:17 </td>
   <td style="text-align:left;"> Nasdaq bell-ringing ceremony featured Chinese official who called genocide of Uyghur Muslims 'lies' </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , A Chinese government official who claimed reports of human rights violations in China were "lies" and praised the Communist Party of China (CPC) as a "great party" was featured at two high-profile events earlier this week in New York City, where he used his platform to promote the upcoming Beijing Winter Olympics and a "shared future" between China and the United States.                                                                                                                                                                                                            , Huang Ping, who has been the consul general of China’s New York Consulate since 2018, posted two videos of himself on Twitter participating in Nasdaq's virtual bell-ringing ceremony and the lighting of the Empire State Building for the start of the Lunar New Year.                                                                                                                                                                                                                                                                                                                         , "It is my great pleasure to attend Nasdaq's bell ringing ceremony for the fourth time to celebrate the Chinese Lunar New Year of the tiger," Huang said. "2021 was a year full of challenges. Despite the protracted and resilient pandemic, we have seen the positive trend of economic recovery. Nasdaq Composite index hit record high, China's GDP grow by 8.1 percent, the largest jump since 2011."                                                                                                                                                                                        , After hyping up China's economy and calling for China and the United States to work together, Huang promoted the Beijing Winter Olympics, saying, "The Beijing Winter Olympics are open in just five days. China is ready to deliver a streamlined, safe, and splendid Olympic Games to the world."                                                                                                                                                                                                                                                                                              , Nasdaq, which lists many of America’s largest tech companies, has come under scrutiny from U.S. officials, along with other major exchanges, for its continued listing of Chinese companies over concerns about transparency and threats to U.S. national security.                                                                                                                                                                                                                                                                                                                              , The Nasdaq building in Times Square in New York July 8, 2017.  (Avalon/Universal Images Group via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Nasdaq's Twitter account, which has over 700,000 followers, posted a few photos of the digital billboards in New York City, which included one with Huang and another billboard that said, "Nasdaq welcomes Chinese Consulate in New York."                                                                                                                                                                                                                                                                                                                                                      , Bob McCooey, who serves as a vice chairman at Nasdaq, quote tweeted Huang and said, "It is always such a great honor for me to be able to host [Huang Ping] each year at the beginning of the #LunarNewYear."                                                                                                                                                                                                                                                                                                                                                                                    , Chinese state-run media outlets were quick to exploit Huang's invitation to speak at the Nasdaq bell-ringing ceremony and promoted it to millions of followers on Twitter. China Daily, a CPC-controlled media outlet tweeted three photos of the digital billboards and said, "Chinese Consul General in New York Huang Ping said #China will continue to be the opportunity for #US investors in the Year of the Tiger." The Global Times, another CPC-controlled English language newspaper, promoted Huang's remarks about the upcoming Beijing Winter Olympics, which start later this week., Fox News Digital reported last month that Huang appeared on a podcast in August 2021, during which he made several controversial remarks, including praise of the CPC as a "great party" and repeatedly denying the existence of a genocide of Uyghur Muslims in Xinjiang, despite the State Department and Holocaust Museum saying China is committing genocide.                                                                                                                                                                                                                                , "There are lots of lies here fabricated by some people with their own political agenda," Huang said, denying the existence of genocide and internment camps. "As I said, there’s no genocide, not single evidence to prove that there’s a genocide or something there. It’s just a slandering."                                                                                                                                                                                                                                                                                                  , The sun sets on the Empire State Building, One Vanderbilt and the Chrysler Building in New York City March 14, 2021, as seen from Jersey City, N.J. (Gary Hershorn/Getty Images)                                                                                                                                                                                                                                                                                                                                                                                                                 , In addition to attending the bell-ringing ceremony Monday, Huang was invited to a virtual lighting of the Empire State Building over the weekend, where he was introduced by Tony Malkin, the chairman, president and chief executive officer of Empire State Realty Trust.                                                                                                                                                                                                                                                                                                                      , Malkin said the trust partners with Huang "each year" to light up the Empire State Building for the start of the Lunar New Year and that he was "honored" to welcome Huang to the lighting. He also promoted the upcoming Olympics in Beijing.                                                                                                                                                                                                                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , After Malkin's introduction, Huang spoke and called Malkin his "old friend" and used similar talking points from his remarks for the Nasdaq bell-ringing ceremony. He then promoted the Beijing Olympics and told viewers to "stay tuned and work together for a shared future."                                                                                                                                                                                                                                                                                                                 , Fox News Digital previously reached out to the Chinese consulate about Huang's denial of a genocide and concentration camps in Xinjiang, but the consulate echoed Huang's talking points and said the "Xinjiang-related issue is not about human rights" and that a "lie told a thousand times is nothing but still a lie."                                                                                                                                                                                                                                                                      , FOX Business reached out to Malkin and Nasdaq, but did not receive a response.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-02-02 22:21:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Snaps 4-Day Winning Streak </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 1.5% to 1,419 on Wednesday, ending a streak of 4 consecutive increases, weighed down by lower demand across all its vessel segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, went down 1.3% to 1,280 and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, declined  2.5% to 1,765, its lowest since April. Among smaller vessels, the supramax index fell 8 points to its lowest since February 2021 at 1,570. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/milk </td>
   <td style="text-align:left;"> 2022-02-02 22:14:17 </td>
   <td style="text-align:left;"> Milk Hits 4-week Low </td>
   <td style="text-align:left;"> Milk decreased to a 4-week low of 20.2 USD/CWT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://edition.cnn.com/2022/02/02/world/coronavirus-newsletter-intl-02-02-22/index.html </td>
   <td style="text-align:left;"> 2022-02-02 21:54:21 </td>
   <td style="text-align:left;"> In Europe, leaders are starting to turn the page on the pandemic. It's a different story in the US - CNN </td>
   <td style="text-align:left;"> This is the weekly edition of CNN's coronavirus newsletter. Look out for your roundup every Wednesday. If you haven't subscribed yet, sign up here.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ,  (CNN)Austria will introduce the European Union's strictest Covid-19 vaccine mandate this week, making it compulsory for anyone over the age of 18 to get the shot. While Italy, Greece and other EU countries have introduced mandates for certain groups, like the elderly, health care staff and workers, Austria is the first in the bloc to roll out such sweeping measures.                                                                                                                                                                                                                                                                                                                                                                           , Political consensus around the Austrian plan had shown signs of unraveling in recent weeks as experts waited for data to see whether available vaccines would be as effective against the new, highly transmissible Omicron variant. Recent studies, including a report published Tuesday by the US Centers for Disease Control and Prevention, have confirmed that vaccines help to prevent severe disease, hospitalization and death, while booster shots increase those protections.                                                                                                                                                                                                                                                                     , Austria's government has said that while the mandate is a tough step, it is necessary to combat severe disease and get out of the pandemic. "We know that vaccination is the only way to get out of it and to get back to a normal life," Austria's federal minister, Karoline Edtstadler, recently told the BBC.                                                                                                                                                                                                                                                                                                                                                                                                                                           , A return to normal life -- or something approaching it -- is starting across Europe. From the reopening of restaurants and nightlife to the loosening of quarantine measures and removal of mask mandates, some of the bloc's biggest economies are relaxing their Covid-19 rules in spite of record case numbers, fueled largely by the spread of Omicron. Officials say that they're able to do so because the variant is causing less severe illness and hospitalizations among their highly vaccinated populations.                                                                                                                                                                                                                                     , Britain's Health Secretary Sajid Javid on Monday scrapped an order forcing all frontline medical workers in England to get vaccinated, saying that while vaccination remained "our best line of defense" it was no longer "proportionate" to require it. The U-turn followed England's decision to drop its so-called "Plan B" restrictions, introduced to combat the Omicron variant, as cases plateau.                                                                                                                                                                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Norway, Denmark and the Netherlands are lifting their remaining Covid rules in spite of surging cases -- Denmark has the second-highest infection rate, or seven-day average of new infections, of any nation in the world, according to Our World in Data. Officials in the countries said that the recent spikes hadn't translated to a rise in hospitalizations, with Norway's Prime Minister Gahr Stoere noting: "We're well protected by vaccines." France on Wednesday said it would begin rolling back restrictions as the situation appears to stabilize.                                                                                                                                                                                           , The picture looks very different in America, where mounting hospitalizations and deaths have dashed hopes that Omicron would be kinder to the country than previous waves. Unlike in Western Europe, where leaders are beginning to turn the page on the pandemic, the Covid death rate in the United States is soaring, according to the latest estimates from Our World in Data. Experts are blaming the toll on the country's failure to vaccinate as many people as other rich nations. The US now ranks fourth globally for per capita Covid-19 deaths, according to Johns Hopkins University. The only large European country to exceed the US toll is Poland.                                                                                        , The World Health Organization (WHO) has warned that it is starting to see a worrying increase in deaths in most regions of the world, and that it was premature for any country to give up attempts to halt transmission. "We're concerned that a narrative has taken hold in some countries that because of vaccines, and because of Omicron's high transmissibility and lower severity, preventing transmission is no longer possible, and no longer necessary. Nothing could be further from the truth," WHO chief Tedros Adhanom Ghebreyesus told reporters on Tuesday.                                                                                                                                                                                 , "More transmission means more deaths. We are not calling for any country to return to so-called lockdown. But we are calling on all countries to protect their people using every tool in the toolkit, not vaccines alone. It's premature for any country either to surrender, or to declare victory," he added.                                                                                                                                                                                                                                                                                                                                                                                                                                            , YOU ASKED. WE ANSWERED                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Q: Should you wait for an Omicron specific booster?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , A: "No," says CNN's Medical Analyst Dr. Leana Wen, adding: "Everyone eligible to receive a booster should do so now."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here are two key reasons why:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , First, there is growing evidence that a third shot of Pfizer or Moderna or a second vaccine following Johnson &amp; Johnson is needed to sustain strong protection against Covid-19. Last month, three large new studies from the CDC found that boosters protect against severe illness and reduce the likelihood of contracting coronavirus.Second, Omicron-specific vaccines are still in clinical trials. Pfizer and BioNTech announced Tuesday that they're beginning trials for an Omicron-specific Covid-19 vaccine, and Moderna revealed Wednesday that it has entered Phase 2 of its own trial of a vaccine that targets the variant. These trials will take months to complete, and with Omicron still surging, people shouldn't delay their boosters., READS OF THE WEEK                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Pfizer applies to the FDA for a two-dose vaccine for children under 5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Pfizer and its partner, BioNTech, have asked the US Food and Drug Administration to authorize their two-dose Covid-19 vaccine for children aged 6 months to 5 years old, the companies said Tuesday, adding that the move came in response to "the urgent public health need in this population."                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The request for emergency authorization comes as the Omicron variant fuels a record rise in pediatric infections. Since the start of the pandemic, at least 11.4 million children have tested positive for Covid-19, the American Academy of Pediatrics reported Monday, with over 3.5 million cases reported in January alone. Children made up 22.8% of the total reported cases for the week ending January 27.                                                                                                                                                                                                                                                                                                                                          , Federal regulators pushed the companies to submit the request even though two child-sized doses of the vaccine did not produce the expected immunity in children aged between 2 and 5 in a clinical trial. Children between 6 months and 2 years old produced an immune response that was comparable to that of teenagers and young adults.                                                                                                                                                                                                                                                                                                                                                                                                                 , Parents, are you ready to get your young kids vaccinated? Have you been avoiding activities out of fear your children would get Covid-19? What will the vaccine mean for your family? Share your story with us.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A universal vaccine could be the future of the coronavirus fight                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Scientists are working to develop a "pan-coronavirus" vaccine -- one that offers protection against multiple variants of the coronavirus that causes Covid-19.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The hope is that such a vaccine could pave the way for the development of a universal coronavirus vaccine, which could head off any coronavirus -- not only emerging variants that cause Covid-19, but also some common colds and even the menacing threat of novel coronaviruses we haven't identified yet, Jacqueline Howard reports.                                                                                                                                                                                                                                                                                                                                                                                                                     , But such vaccines are "going to take years to develop," Dr. Anthony Fauci, director of the National Institute of Allergy and Infectious Diseases, said during a White House briefing on Wednesday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , What it's like to fly into Beijing's Olympic "bubble"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , The Beijing Winter Olympics is being hosted inside a veritable fortress -- known informally as the "bubble" -- that takes weeks of careful planning to penetrate. Designed to prevent the spread of Covid, the bubble is the most ambitious quarantine attempted anywhere since the start of the pandemic.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Across China, entire communities have been forced into lockdown over a single Covid case. Any failure to contain cases at the Winter Games could undermine the country's zero-Covid strategy and put the entire nation's health and reputation at risk.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , By the time she departed for Beijing, CNN correspondent Selina Wang was fully vaccinated, had tested negative for Covid twice, and had stocked her suitcase with face masks and snacks to eat if she failed a test and was forced to isolate alone for the entire Olympics. Read more about her journey.                                                                                                                                                                                                                                                                                                                                                                                                                                                    , TOP TIP                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , You're ready to swap your old cloth masks for N95s as some experts recommend, but the higher price tag and two little words -- "single use" -- are giving you pause. How long can you really wear an N95 and still protect yourself and others from Covid-19 risk?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Linsey Marr, a professor of civil and environmental engineering at Virginia Tech, has these tips:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Avoid touching the front outer part of the mask when putting it on. Instead, try to handle it by the edges or straps.These masks are designed to handle a lot of particles and will continue to work even after they are worn in crowded settings. But if you know you were exposed to someone with Covid, Marr recommends throwing away the mask. If the mask becomes damp, visibly dirty, bent, creased or otherwise damaged -- including from wearing makeup -- you need to replace it since these conditions could decrease the mask's effectiveness.                                                                                                                                                                                                   , LISTEN TO OUR PODCAST                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Our memories may be precious but they aren't necessarily accurate. This week on the Chasing Life podcast, CNN's Chief Medical Correspondent Dr. Sanjay Gupta explores why we forget and what we can do to keep our memories sharp at any age. Listen here.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-02 21:42:32 </td>
   <td style="text-align:left;"> Treasury Yields Steady, Payrolls Awaited </td>
   <td style="text-align:left;"> The yield on the benchmark US 10-year Treasury note was little changed at 1.8% on Wednesday as investors remain cautious ahead of the payrolls report on Friday and wonder what the tightening path from the Fed will be. Fresh ADP data showed US private companies unexpectedly cut 301K jobs in January, a sign the impact of the omicron coronavirus variant may be bigger than initially anticipated. At the same time, St. Louis Fed president James Bullard, a noted hawk, said on Tuesday he would argue for rate rises in March, May and June, but did not favor a half-point move. The US central bank indicated last week that it would likely hike interest rates in March, but markets started to price in five quarter-point rate hikes this year and some investors even pointed to a half-point rate hike next month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-02-02 21:34:00 </td>
   <td style="text-align:left;"> Dollar Extends Losses after ADP </td>
   <td style="text-align:left;"> The dollar index extended losses to 96 on Wednesday after the ADP report showed an unexpected loss in the job market in January due to the spread of the omicron coronavirus variant. New figures helped to ease some concerns of a very fast tightening by the Fed this year. Early in the session, the greenback was already falling as St. Louis Fed president James Bullard, a noted hawk, said on Tuesday he would argue for rate rises in March, May and June, but did not favor a half-point move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/building-permits </td>
   <td style="text-align:left;"> 2022-02-02 21:32:00 </td>
   <td style="text-align:left;"> Canada December Building Permits Fall More than Expected </td>
   <td style="text-align:left;"> The value of building permits in Canada fell 1.9 percent month-over-month to CAD 11.2 billion in December of 2021, after jumping an upwardly revised 7.6 percent to a record CAD 11.4 billion in November and compared with market estimates of a 1.5 percent decrease. Construction intentions in the residential sector declined 2.7 percent to CAD 7.7 billion, solely led by a 6.0 percent drop in multiple-family units to CAD 4.1 billion, while a 1.3 percent rise in single-family units to CAD 3.6 billion limited the downturn. Meanwhile, permits in the non-residential sector were roughly unchanged at CAD 3.4 billion, as a 17.2 percent jump in institutional units to CAD 0.7 billion and an 8.4 percent rise in industrial units to CAD 0.8 billion offset a 7.9 percent contraction in commercial building intentions to CAD 1.9 billion. Among major provinces, losses were led by British Columbia (-2.7 percent to CAD 1.9 billion) and Quebec (-0.5 percent to CAD 2.5 billion). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/energy/potential-russia-ukraine-war-could-impact-oil-prices-for-decades-analyst-warns </td>
   <td style="text-align:left;"> 2022-02-02 21:22:08 </td>
   <td style="text-align:left;"> Potential Russia, Ukraine war could impact oil prices for decades, analyst warns </td>
   <td style="text-align:left;"> Price Futures Group senior analyst Phil Flynn stresses that 'Russia really controls energy' in Europe and a prolonged war could lead to a 'difficult time' replacing supplies.                                                                                                                                                                                     , Price Futures Group senior analyst Phil Flynn warned on Wednesday that a potential war between Russia and Ukraine could impact oil prices for decades.                                                                                                                                                                                                             , The energy market analyst made the argument on "Mornings with Maria" on Wednesday as U.S. oil has been hovering just below $90 per barrel and Brent crude, the global benchmark, oil is even higher.                                                                                                                                                               , Flynn noted that the market is eyeing unrest in Ukraine as Russian forces inch closer.                                                                                                                                                                                                                                                                             , "This could be a major event that we will feel not just for weeks, but perhaps for decades," Flynn told host Maria Bartiromo.                                                                                                                                                                                                                                      , "A war between Ukraine and Russia is going to have ramifications across Europe and across the world and part of the reason is the energy policies in Europe have left them more dependent on Russia for supply so Russia really controls energy in that part of the world."                                                                                        , "So if they get into a protracted war, they decide to cut off supplies to Europe, Europe is going to have a very difficult time replacing those supplies," he went on to warn.                                                                                                                                                                                     , The White House revealed this week that it has reached out to suppliers of liquid natural gas both foreign and domestic seeking ways to redirect shipments of LNG to Europe in the instance that Russia cuts off the critical energy source to Europe.                                                                                                             , Republicans argue President Vladimir Putin is trying to get the region more hooked on Russian fuel. FOX Business' Hillary Vaughn with more.                                                                                                                                                                                                                        , Critics argue such a scramble would not be necessary if the Biden administration had better energy policies.                                                                                                                                                                                                                                                       , BIDEN'S WAR ON AMERICAN ENERGY MADE US DEPENDENT, AGAIN                                                                                                                                                                                                                                                                                                            , Russia supplies roughly 40% of Europe's natural gas, and concerns are growing that Moscow might use that as leverage if the conflict escalates with NATO allies over Russia's ongoing aggression toward Ukraine.                                                                                                                                                   , The White House noted that they do think it is unlikely that Russian President Vladimir Putin would cut off supplies to Europe entirely, given that it would hurt Russia economically. A spokesman for Putin said Monday that the idea Moscow would shut off energy exports was "yet another brilliant example of fake hysteria," The Wall Street Journal reported., A Biden administration official said during a press call on Tuesday that Russia has already cut the supplies it sends to Europe through Ukraine by half, and that officials are working to ensure Europe has enough energy sources through the winter and spring in case Russia cuts further from other routes.                                                    , Those efforts include "engaging with major buyers and suppliers of LNG to ensure flexibility in their existing contracts and storage — and how they manage their storage to enable the diversion to Europe if necessary," the White House official said.                                                                                                           , Price Futures Group senior analyst Phil Flynn argues 'this could be a major event' that could be felt for decades.                                                                                                                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                        , Flynn argued on Wednesday that it "isn’t that easy" to find other sources of liquid natural gas in the event Russia cuts off the energy source to Europe, as the Biden administration had suggested.                                                                                                                                                               , He also stressed that "Russia is still a major oil producer" and "if they decide to cut off oil supplies, those supplies really can’t be made up."                                                                                                                                                                                                                 , READ MORE ON FOX BUSINESS BY CLICKING HERE                                                                                                                                                                                                                                                                                                                         , FOX Business’ Phil Flynn and Breck Dumas contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/adp-employment-change </td>
   <td style="text-align:left;"> 2022-02-02 21:22:00 </td>
   <td style="text-align:left;"> US Companies Unexpectedly Cut 301K Jobs in January: ADP </td>
   <td style="text-align:left;"> Private businesses in the United States unexpectedly cut 301K workers in January of 2022, the first job loss since December of 2020 and the biggest since April 2020, as the spread of the omicron coronavirus variant hurt the job market. Investors were expecting a job gain of 207K. Biggest job losses occurred in the services sector (-274K), namely leisure and hospitality (-154K); trade, transportation and utilities (-62K); education and health (-15K); financial activities (-9K); and information (-8K). The goods-producing sector lost 27K jobs, due to manufacturing (-21K) and construction (-10K) while the natural resources and mining sector added 4K jobs. Small companies cut 144K payrolls, large 98K and midsized 59K. Figures for December were revised lower to show a 776K job gain instead of 807K previously reported. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-02 21:21:00 </td>
   <td style="text-align:left;"> Italian 10Y Bond Yield Rises Ahead of ECB Meeting </td>
   <td style="text-align:left;"> The yield on the Italian 10-year BTP rose to 1.42%, not far from the 18-month highs of 1.47% touched on January 27th, after surging inflation figures strengthened the case for tighter monetary policy ahead of the ECB policy meeting. Preliminary estimates showed consumer prices in the Eurozone rose by a record high of 5.1%, surpassing expectations of a 4.4% increase, while domestic inflation surged to a 26-year high of 4.8%. High inflation figures led market participants to bet on a 10bps hike on the ECB’s benchmark rate by July and 30bps by the end of 2022. In the meantime, investors digested the re-election of Sergio Mattarella as Italy’s head of state after seven stalemate rounds, leaving Mario Draghi as Prime Minister and increasing the likelihood of short-term continuity to the current administrations’ implementation of the EUR 191.5 billion in EU recovery funds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hungary/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-02 21:14:48 </td>
   <td style="text-align:left;"> Hungary 10Y Bond Yield Hits 7-1/2-year High </td>
   <td style="text-align:left;"> Hungary 10 Year Government Bond Yeld increased to a 7-1/2-year high of 4.99% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/abbv:us </td>
   <td style="text-align:left;"> 2022-02-02 21:09:35 </td>
   <td style="text-align:left;"> AbbVie earnings above expectations at 3.31 USD </td>
   <td style="text-align:left;"> AbbVie (ABBV) released earnings per share at 3.31 USD, compared to market expectations of 3.29 USD. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-03 09:04:20 UTC +8

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
   <td style="text-align:left;"> 2022-02-03 09:04:01 </td>
   <td style="text-align:left;"> $SPY breaking: NASDAQ GOES BLOOD RED ON THE WEEK. Don’t buy the cats. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:03:55 </td>
   <td style="text-align:left;"> $SPY I am done with the market. This manipulation is bullshit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:03:45 </td>
   <td style="text-align:left;"> $SPY remember that time you held spy options overnight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:03:42 </td>
   <td style="text-align:left;"> $SPY This what happens when you buy otm poots 3 days too early.. your dadi get sooo mad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:03:31 </td>
   <td style="text-align:left;"> $SPY I made a post yesterday, and said if spy breaks 460 resistance, so it didn’t today. Very important to know where is the resistance. Good to be prepared </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:03:31 </td>
   <td style="text-align:left;"> $SPY Crap, I think I tanked the entire market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:03:29 </td>
   <td style="text-align:left;"> $SPY Double digits down tomorrow…it is very unfortunate that some are pouring money into “back to normal phase” when outflow of billions is leaving market ✍🏼✍🏼

🤦🏽🤦🏽🤦🏽🤦🏽🤦🏽🤦🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:03:28 </td>
   <td style="text-align:left;"> $SPY stocks are too high... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:03:04 </td>
   <td style="text-align:left;"> $SPY $462 @ Open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:03:02 </td>
   <td style="text-align:left;"> Well, what a swing on $NVDA and $AMD ! $FB may have just caused a few days of Bearish runs.. thanks.

- had some great $SPY scalps today in the team chat!

- glad we bet against $SPOT , I had posted that more than likely history would repeat itself. These are going to look amazing at open!!!

Also looks like the AMD swing on puts will pay! Gotta play both sides! Working on a watch list with my team!

Message me for details if you’re interested in joining! 

Appreciate you all and anyone following should have made some serious cash today!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:02:35 </td>
   <td style="text-align:left;"> $SPY shorted Dow for the rest of this week atleast - might open spy puts in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:02:33 </td>
   <td style="text-align:left;"> $SPY can we get ta outlook to 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:02:22 </td>
   <td style="text-align:left;"> $SPY https://music.youtube.com/watch?v=xYqovSobZTc&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:02:20 </td>
   <td style="text-align:left;"> $SPY surely this goes to 440s tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:02:14 </td>
   <td style="text-align:left;"> $SPY 

Please stop buying the dip and pay attention to what’s going on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:02:13 </td>
   <td style="text-align:left;"> $SPY Remember when someone asked J Pow last meeting if there would be any “circuit breaker” that would change the feds stance? He quickly replied no, there isn’t. Some Volcker in his blood after all perhaps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:02:08 </td>
   <td style="text-align:left;"> $SPY this is a market where 1 bad earnings will drop your stock 20-50% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:01:47 </td>
   <td style="text-align:left;"> $SPY $AMZN 2500 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:01:43 </td>
   <td style="text-align:left;"> $SPY Poo Poo hits the fan? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:01:42 </td>
   <td style="text-align:left;"> $SPY When does p*rnhub release earnings? That&amp;#39;s gonna go up like a black c*ck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:01:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUT Wow everything is dying after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:01:28 </td>
   <td style="text-align:left;"> $SPY what time is amzn earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:01:17 </td>
   <td style="text-align:left;"> $SPY capital is about to leave the US markets in extraordinary fashion. Doge cat is scared </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:01:05 </td>
   <td style="text-align:left;"> $SPY  
 
I see downward movement.  But I don&amp;#39;t trust it.  Yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:01:01 </td>
   <td style="text-align:left;"> $SPY $AMZN earnings I’ll be looking for signs in supply chain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:00:51 </td>
   <td style="text-align:left;"> $SPY And the right shoulder is nearing completion 😆 head and shoulders  down goes Facebook… spy’s like an nice car and now investors are seeing the true value of the companies under the hood… little bloated aye? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:00:50 </td>
   <td style="text-align:left;"> $SPY well this does not look good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:00:35 </td>
   <td style="text-align:left;"> $SPY  If you&amp;#39;re a billionaire like me then you know you&amp;#39;re just looking for somewhere to stash your cash. Somewhere safe that&amp;#39;s reasonably liquid, cheap and maybe over time will give you a bit of return. At the moment, equity markets aren&amp;#39;t it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:00:32 </td>
   <td style="text-align:left;"> $SPY  
 
It takes God given skill to see  
SPY $500  
Tina has it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:00:09 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 09:00:04 </td>
   <td style="text-align:left;"> $SPY $QQQ Does not mean all out collapse. Just repricing of overpriced stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:59:45 </td>
   <td style="text-align:left;"> $SPY pls daddy powell show mercy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:59:35 </td>
   <td style="text-align:left;"> $XLF $SPY $QQQ $IWM $DIA This is an excellent example of the Feds medaling in the market.2017, 2018,2019 it just trends normally and then along comes the Fed. Now I&amp;#39;m not saying they shouldn&amp;#39;t have done anything, but geez!! Protect your capital, the volatility is not going away any tine soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:59:24 </td>
   <td style="text-align:left;"> $SPY Tbis shoukd ne an interesting after hours.  Can the nasdaw drop 1000 points ovnernight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:59:18 </td>
   <td style="text-align:left;"> $SPY BYE BILLY. CA CA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:59:16 </td>
   <td style="text-align:left;"> $CFVI $DWAC The Salty Cracker is LIVE! REEEEeeEEEeee  https://rumble.com/vtwyea-honk-apocalypse-reeeeee-stream-02-02-22.html $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:59:12 </td>
   <td style="text-align:left;"> $SPY lucky guess lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:57 </td>
   <td style="text-align:left;"> $SPY futes green by morning like usual? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:53 </td>
   <td style="text-align:left;"> $SPY another -60 handles by open will be lovely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:51 </td>
   <td style="text-align:left;"> $SPY would love to see /ES break 4530 in the next minute or so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:49 </td>
   <td style="text-align:left;"> $SPY Puts in place, come on $AMZN its like a dream </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:47 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:42 </td>
   <td style="text-align:left;"> $SPY We drop all day tommorow and Bulls get their bounce at $448 when Amazon reports earnings at close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:37 </td>
   <td style="text-align:left;"> $SPY Wish I could add more puts... LOOK AT ALL THOSE BAD EARNINGS. This will open closer to -2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:32 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:31 </td>
   <td style="text-align:left;"> $SPY blender </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:30 </td>
   <td style="text-align:left;"> $SPY since when did fb carry so much weight on spy? Smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:30 </td>
   <td style="text-align:left;"> $SPY  Dreaming, can’t even wait </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:19 </td>
   <td style="text-align:left;"> $SPY told you it was a bulltrap days ago. Just a technical relief rally to suck in more retail while the instituonals sell calls and offload inventory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:58:11 </td>
   <td style="text-align:left;"> $SPY total capital destruction and they are laying it off on retail..sad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:57:57 </td>
   <td style="text-align:left;"> $SPY 420 on 024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:57:38 </td>
   <td style="text-align:left;"> $SPY what time Amazon ER tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:57:32 </td>
   <td style="text-align:left;"> $SPY the fed, jobs report, biden, ukraine, covid, supply chain, china, tensions, protests. Anything will take this down 🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:57:24 </td>
   <td style="text-align:left;"> $SPY That&amp;#39;s when you know [communism] is over, when the nice Canadians turn on you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:57:23 </td>
   <td style="text-align:left;"> $SPY There’s a strong SmELL in the air. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:57:18 </td>
   <td style="text-align:left;"> $SPY tendies
 dry or saucey? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:57:14 </td>
   <td style="text-align:left;"> $SPY The $FB chart doesn’t even look real😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:57:11 </td>
   <td style="text-align:left;"> $SPY I got caught with only a few puts... I was loading these things. Didn&amp;#39;t expect so many bad earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:57:04 </td>
   <td style="text-align:left;"> $SPY $QQQ one amazon miss away from this ship really sinking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:56:37 </td>
   <td style="text-align:left;"> $SPY I play both sides of the market. There is still a gap fill to $407 here. This market is garbage so I continue to buy $UVXY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:56:28 </td>
   <td style="text-align:left;"> $SPY wow nasty market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:56:14 </td>
   <td style="text-align:left;"> $SPY I wanna live in a world 🌎 where everyone has to pluck their own chickens 🐔 no more easy drive thru fake (lab grown) chicken tendies ! 
KFC 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:56:05 </td>
   <td style="text-align:left;"> $SHOP $AMZN word on the street Amazon gonna got it out of the park with earnings $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:56:03 </td>
   <td style="text-align:left;"> $SPY $AMZN earnings!!!
To short or not to short🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:55:40 </td>
   <td style="text-align:left;"> $SPY traders market, short, scalp, watch, in and out, make money but mostly cash. Then we love the big moves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:55:39 </td>
   <td style="text-align:left;"> $SPY Friday&amp;#39;s job report is supposed to be tremendously bad.  Prepare. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:55:33 </td>
   <td style="text-align:left;"> $SPY 

Just remember, Biden and liberals fucked up the bull run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:55:28 </td>
   <td style="text-align:left;"> $SPY green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:55:28 </td>
   <td style="text-align:left;"> $SPY any1 happen to see the Family feud just a second ago? What brings men closer ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:55:19 </td>
   <td style="text-align:left;"> $BA Boeing will be like $fb $spy
They both have b in their name

Expecting deep red for Boeing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:55:13 </td>
   <td style="text-align:left;"> $SPY Gap up or down tomm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:55:11 </td>
   <td style="text-align:left;"> $SPY  Im soooo happy that cov is over and time to hit some live events and concerts!!!  adjust ur port. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:55:04 </td>
   <td style="text-align:left;"> $SPY 🤷🏾‍♂️ I wish Theta didn’t have to destroy my puts going into close but I saw this coming. Like I’ve said allllll day $445 before $460 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:54:57 </td>
   <td style="text-align:left;"> $SPY will amazon save the market ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:54:28 </td>
   <td style="text-align:left;"> $SPY Watch futures after close in six minutes!!! $ARKK $QQQ Will be very telling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:54:19 </td>
   <td style="text-align:left;"> $SPY The cool thing is stocks like Roku and Roblox still have at least 125 and 60 dollars to go down respectively. Gonna be a fantastic year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:54:10 </td>
   <td style="text-align:left;"> $SPY Last night, I dreamed that at 7:59 pm exactly, there was huge crash of all the indexes and nobody could do anything about it. The next morning was a comple, complete disaster, like it was the end of the world. There&amp;#39;s still 5 minutes left. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:54:03 </td>
   <td style="text-align:left;"> $SPY bulls tomorrow morning 😂 🤡 ‘s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:53:50 </td>
   <td style="text-align:left;"> As already mentioned a few weeks ago: 
 
Name change to META proved unlucky for $FB 
 Name change to BLOCK proved unlucky for $SQ  
 
Any other company wants to change their name? 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:53:19 </td>
   <td style="text-align:left;"> @ohnikanika $SPY $DJIA what do you think guys? 😌🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:53:19 </td>
   <td style="text-align:left;"> $SPY i came here for investment advice , i ended up re-apply for my wendys mopping job </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:53:06 </td>
   <td style="text-align:left;"> $SPY who got bulltrap at 458 today 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:52:54 </td>
   <td style="text-align:left;"> $SPY this just in: you’ve been hustled by the elite tweets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:52:53 </td>
   <td style="text-align:left;"> $SPY  
 
This is fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:52:47 </td>
   <td style="text-align:left;"> $SPY i think bulls and bears can agree. We just need a big flush. Get some cheap shares start a new trend. And live in piece. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:52:45 </td>
   <td style="text-align:left;"> $SPY RED RUM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:52:31 </td>
   <td style="text-align:left;"> $SPY MMs seem to be offloading 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:52:28 </td>
   <td style="text-align:left;"> $SPY I wonder how many people who started trading during the pandemic were completely blown up in the last two weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:52:01 </td>
   <td style="text-align:left;"> $SPY what good news is left to pump up the market?  more QE?  nope.  lower rates?  nope.  world peace?  nope.  Biden?  nope.   Amazon earnings?  not likely.  market is screwed.  $qqq $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:51:50 </td>
   <td style="text-align:left;"> $SPY shit load of tutes off sides. Tomorrow will be a beauty. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:51:46 </td>
   <td style="text-align:left;"> $SPY cupformed now 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:51:16 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s a buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:51:11 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

THIS POS BETTER BE BALLS DEEP RED 

TOMORROW, I WANNA SEE AN 

INSTITUTIONAL DUMP OF A LIFETIME... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:51:07 </td>
   <td style="text-align:left;"> $SPY I just looked through some history of some of the most respected posters on here. Almost all their predictions were wrong. 

Never forget that no one knows shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:51:05 </td>
   <td style="text-align:left;"> $SPY lolz bulls freaking out about “one stick should control the market” but we’re fine with google pump yesterday. Humble yourself simp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:50:55 </td>
   <td style="text-align:left;"> Facebook - before and after 
$FB $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:50:42 </td>
   <td style="text-align:left;"> $SPY https://music.youtube.com/watch?v=4a0cmyOL9s8&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:50:42 </td>
   <td style="text-align:left;"> $SPY  Zuckerberg Zucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:50:27 </td>
   <td style="text-align:left;"> $FB $SPY Facebook is only used by boomers now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:50:13 </td>
   <td style="text-align:left;"> $SPY its worth about 380 fair value right now. Ur paying to much. You should all be selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:49:50 </td>
   <td style="text-align:left;"> $SPY Can anyone tell me how much this will be up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:49:33 </td>
   <td style="text-align:left;"> $SPY any frens here shorting the stock market? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:49:30 </td>
   <td style="text-align:left;"> Daily Market Update for 2/2 
$NASDAQ $COMPQ $IXIC $SPY $DJIA $RUT 
https://www.drewby.com/2022/02/02/daily-market-update-for-2-2-2/ 
The rally in the Nasdaq slowed on Wednesday as investors took profits in some sectors while chasing a more select set of companies turning in great earnings this past two weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:49:17 </td>
   <td style="text-align:left;"> $SPY Huge Gap to fill to the upside! I would not even try going short here! Go long till we get a rejection! Till then this is going $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:49:05 </td>
   <td style="text-align:left;"> $SPY I’m sick of this shit!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:48:54 </td>
   <td style="text-align:left;"> $SPY the entire market right now…. 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:48:45 </td>
   <td style="text-align:left;"> $FB Well there goes the bounce! $SPY $F $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:48:39 </td>
   <td style="text-align:left;"> $SPY  healthy manufactured pullback on shit we knew was baked in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:48:35 </td>
   <td style="text-align:left;"> $SPY will go back to $456 by the first hour of trading tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:48:28 </td>
   <td style="text-align:left;"> $SPY saw this coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:48:13 </td>
   <td style="text-align:left;"> $SPY one stock should not be able to control the market like this!!!!!!!!! Fuck you facebook !!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:48:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA BULLS DUMB WATER WET 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:47:49 </td>
   <td style="text-align:left;"> $SPY $PYPL Called well before the move. 🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:47:42 </td>
   <td style="text-align:left;"> $SPY we are about 30 trillion in debt and our politicians keep recklessly spending.   Not good.  

I like this video of Neil degrasse Tyson explaining big numbers https://youtu.be/YPenDUY68rM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:47:42 </td>
   <td style="text-align:left;"> $SPY futes drippin 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:47:10 </td>
   <td style="text-align:left;"> $SPY free and fair markets is repugnant in a world 🌎 full of algos - my Patience is wearing thin and I haven’t even lost money 💰 the only stock I’m bag holding (-$2)  is T but I get paid to hold it 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:46:57 </td>
   <td style="text-align:left;"> Jim Cramer really out here huh $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:46:49 </td>
   <td style="text-align:left;"> $SPY War is fought with Boeing, long Boeing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:46:46 </td>
   <td style="text-align:left;"> $SPY oof that was def an exit pump.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:46:40 </td>
   <td style="text-align:left;"> $SPY damn. i&amp;#39;ve had my cheeks clapped before but never like this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:46:04 </td>
   <td style="text-align:left;"> $SPY War is bullish because we will draft all BLM thugs and Trump supporters with itchy fingers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:45:53 </td>
   <td style="text-align:left;"> $SPY $QQQ those who bought the ol’ Tom Lee pump scheme </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:45:47 </td>
   <td style="text-align:left;"> $SPY futures are going fast, should we event call them futures? At this point 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:45:43 </td>
   <td style="text-align:left;"> $SPY Imagine being a liberal little cuck yoloing it all on Zuck tonight $FB bankrupt as fck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:45:38 </td>
   <td style="text-align:left;"> $SPY  
 
Live look at the SPY $500 Party </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:45:11 </td>
   <td style="text-align:left;"> $SPY $FB Zuck out here decimating portfolios 🤖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:44:56 </td>
   <td style="text-align:left;"> $SPY is this just nightmare??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:44:39 </td>
   <td style="text-align:left;"> $SPY  After hours melt down. 
Fake upside breakout today. 457 resistance zone has been defended which keeps 452ish target in play. 452 support needs to hold or melt down begins to 445ish = strong support/buy zone.
Type of reaction we saw this afternoon (hit 457s target/ resistance, revisted, tried to pop above then failed is *typically* good for a short term reversal at least) 452-25 remains target. Likely initial morning pop then fail triggers to 445s. $QQQ $IWM $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:44:37 </td>
   <td style="text-align:left;"> $SPY there’s literally zero hope for calls or anything bullish tonight or tomorrow just turn off you’re computer and come back Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:44:17 </td>
   <td style="text-align:left;"> $SPY My Wifes Boyfriends ex wife called me said im ok to move back in . Wanted those BEAR hugs of love. 🥰🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:44:12 </td>
   <td style="text-align:left;"> $FB 42 “expert” analysts had buy ratings on this. More proof that analysts are fucking clueless/useless $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:44:10 </td>
   <td style="text-align:left;"> $SPY crossing my fingers rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:44:07 </td>
   <td style="text-align:left;"> $QQQ I missed the news, why is everything down after hours? $SPY $TSLA $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:43:58 </td>
   <td style="text-align:left;"> $SPY thinking S&amp;amp;P futures might go down 100 pts by open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:43:51 </td>
   <td style="text-align:left;"> $SPY 20 mins to close out positions and ride any puts i used to hedge. Decisions decisions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:43:28 </td>
   <td style="text-align:left;"> $SPY didn’t pay to be a clown today I almost bet my life on calls again after selling my NVDA calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:43:22 </td>
   <td style="text-align:left;"> $SPY I am le tired </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:43:19 </td>
   <td style="text-align:left;"> $SPY this market is racist. I’m suing. I want my money back.
Said all the libtards. ✊🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:43:10 </td>
   <td style="text-align:left;"> $FB $spy call me names etc. But that doesn&amp;#39;t change the fact that you&amp;#39;re using hate speech against a person of Jewish descent. Just saying. 

Just checked-- CNN agrees. And so does NY times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:42:44 </td>
   <td style="text-align:left;"> $SPY Loving the swings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:42:40 </td>
   <td style="text-align:left;"> $SPY were the last three days delusion. Are we entering despair??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:42:29 </td>
   <td style="text-align:left;"> $SPY any guess where this would open tomm?? 450 or mid 440? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:42:16 </td>
   <td style="text-align:left;"> $FB Buy sheeple ...  
this is a SCAM Shorting ... the truth is Facebook makes tonnes of money All over the world ...  
 
just WOKISM killed it  
$dwac $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:42:14 </td>
   <td style="text-align:left;"> $SPY market going from 1 step down to 4 steps forward after covid crash. Now it’s doing the opposite 1 step up 4 steps down. All the stims did was postpone a big market correction IMO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:42:09 </td>
   <td style="text-align:left;"> $SPY shoulda held my puts😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:42:05 </td>
   <td style="text-align:left;"> $SPY just waiting for the media to pull out Evergrande from their doodoo hole. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:42:00 </td>
   <td style="text-align:left;"> $SPY stock analysis based on today&amp;#39;s closing price 

https://youtu.be/Eb7Ap5Vp6vg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:41:58 </td>
   <td style="text-align:left;"> $SPY finally back to this. Relief bounce over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:41:51 </td>
   <td style="text-align:left;"> $SPY Gonna try to use the wheel strategy on this on like I do for TSLA.  Do like that you can do it 3x a week unlike most others. 
 
https://youtu.be/tz_rBZ0bYVQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:41:49 </td>
   <td style="text-align:left;"> $SPY make it stop bleeding 🛑 someone call the parademics </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:41:49 </td>
   <td style="text-align:left;"> $SPY  
 
SPY Key Levels Grid For Feb 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:41:33 </td>
   <td style="text-align:left;"> $SPY Love my spy clown bros.. but to y&amp;#39;all whack ass mm&amp;#39;s who be reporting me.. i see you kenny with ya bitch azz... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:41:31 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMZN Bezos tomorrow to all bears: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:41:28 </td>
   <td style="text-align:left;"> $SPY this market is trash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:41:17 </td>
   <td style="text-align:left;"> $SPY what to sell short tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:41:13 </td>
   <td style="text-align:left;"> $ES_F today broke down long before poor $FB earnings right over the 61.8 fib retrace. The key to trade ES_F is levels, NOT PATTERNS like stocks! $SPY $QQQ Note: I still think markets will head lower  but just play directional. Look for shorts if market breaking down, look for longs if levels hold - simple. Don&amp;#39;t make too many trades in opposite directions! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:40:57 </td>
   <td style="text-align:left;"> $SPY follow my special trading channel that I run out of your moms bedroom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:40:56 </td>
   <td style="text-align:left;"> $SPY HOLY COWWWWWW futures are dumping hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:40:41 </td>
   <td style="text-align:left;"> $SPY margin calls tomorrow on robinhood </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:40:23 </td>
   <td style="text-align:left;"> $SPY Feeling cute, going to yolo in some $425 puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:40:21 </td>
   <td style="text-align:left;"> Nasdaq futures drop as Facebook leads tech shares lower

$QQQ $FB $SPY

https://www.cnbc.com/2022/02/02/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:40:00 </td>
   <td style="text-align:left;"> $SPY is currently trading in the upper part of its 52 week range, which is inline with the index. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:39:52 </td>
   <td style="text-align:left;"> $SPY 🚀☺️ tomorrow AH . That’s all I’m going to say !!!  Big earnings for Amazon Buying big tomorrow if this opens red! And getting myself some $AMZN  as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:39:46 </td>
   <td style="text-align:left;"> $SPY saw this coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:39:35 </td>
   <td style="text-align:left;"> $AMZN 2500-2600$ tomorrow $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:39:32 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F Wow… talk about calling a bluff. 👀😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:39:07 </td>
   <td style="text-align:left;"> $SPY still green day  lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:39:00 </td>
   <td style="text-align:left;"> $SPY we gave back all the gains from today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:38:59 </td>
   <td style="text-align:left;"> $SPY Daily: Take Me Home, Bumpy Roads https://www.billionaireclubcollc.com/spy-daily-take-me-home-bumpy-roads/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:38:55 </td>
   <td style="text-align:left;"> $SPY $QQQ tomorrow is guna be a fun one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:38:45 </td>
   <td style="text-align:left;"> $SPY rejecting off previous channel is no good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:38:37 </td>
   <td style="text-align:left;"> $SPY ST is better on red days. Thats a fact bulls can never argue with. 
Bears are better people in general. We actualy care about our country and family. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:38:34 </td>
   <td style="text-align:left;"> $SPY $AMZN will drag spy below 400$ in 3-4 weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:38:13 </td>
   <td style="text-align:left;"> $SPY to $QQQ we&amp;#39;ve been disconnected.  
http://vixcentral.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:38:11 </td>
   <td style="text-align:left;"> $SPY $QQQ  this market is like my girlfriends vagina it will take anything good you have and make it disappear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:37:44 </td>
   <td style="text-align:left;"> $SPY will be fun to watch meltdowns on this board when we go higher tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:37:31 </td>
   <td style="text-align:left;"> $SPY BREAKING!! the Nasdaq 🤣🤣☠️
 https://www.tradingview.com/chart/NAS100/p0QW0Xkm-NAS100-Fallout-Buyer-BEWARE-Growth-at-all-Costs-is-No-More/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:37:31 </td>
   <td style="text-align:left;"> $SPY wow bro that’s so fucked up thank god I didn’t trade today $FB has a 900b$ market cap and combined wit $PYPL 155b was able to
Bring the market down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:37:21 </td>
   <td style="text-align:left;"> $SPY In my dream world we would open at 460 so i could print my calls and then close around 450 after selling off throughout day so i could print my puts. But probably won&amp;#39;t happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:37:20 </td>
   <td style="text-align:left;"> $SPY $FB all the thots moved from insta to tiktok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:37:13 </td>
   <td style="text-align:left;"> $SPY Facebook n Netflix never deserved to be crown jewels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:37:04 </td>
   <td style="text-align:left;"> $SPY Me shoving PUTS ITM Fed 4 exp into my brokerage accounts today above $457! 😂 $fb $spot - True Story! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:36:56 </td>
   <td style="text-align:left;"> $SPY Really?  Come on we need to pamp haaaaaaaaard!!!!!  Put everything I got on cheap calls!!! For a homerun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:36:51 </td>
   <td style="text-align:left;"> $SPY how good would an intraday $15 drop be tomorrow… show all these spamming bulls talking about their $470 calls and shit that valuation matters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:36:44 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:36:38 </td>
   <td style="text-align:left;"> $SPY this opens green doesn’t it?  We’re just going to ignore the end of the world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:36:33 </td>
   <td style="text-align:left;"> $SPY This markets volatility is worse than my girlfriend, you don’t know when she’s in a good mood or a bad mood. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:36:11 </td>
   <td style="text-align:left;"> $SPY 109.8pt Confirmed. EX girlfriend just called. Told me im fcked. 😍🥰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:35:53 </td>
   <td style="text-align:left;"> $SPY tempting 😅 no I said I wouldn’t do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:35:51 </td>
   <td style="text-align:left;"> $SPY The fact that NQ and ES are selling while the DOW holds is weirdly arousing, not gonna lie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:35:41 </td>
   <td style="text-align:left;"> $BNGO $XBI $LABU $SPY $TRIB About damn time to show some love to our bio companies out there. Host a White House Cancer Moonshot summit involving research and healthcare communities, patient organizations, agency leadership, biopharmaceutical companies and other stakeholders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:35:34 </td>
   <td style="text-align:left;"> $SPY The Dark pools from today are gonna tell it all the rest of the month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:35:14 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:34:44 </td>
   <td style="text-align:left;"> $SPY so much emotions...this market is going higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:34:32 </td>
   <td style="text-align:left;"> $SPY wen 410 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:34:29 </td>
   <td style="text-align:left;"> $SPY calm down bulls...just some pajama traders pumping it up for a better short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:56 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:43 </td>
   <td style="text-align:left;"> $SPY Facebook is growth priced as value. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:39 </td>
   <td style="text-align:left;"> $SPY $FB $TWTR $DWAC $QQQ 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:33 </td>
   <td style="text-align:left;"> $SPY After doing some trimming in $ARKK and $LSPD yesterday and the exit from $PYPL  I&amp;#39;m at 17% cash. I&amp;#39;ll likely put some of that to work tomorrow as Faceturd destroys the Qs. Will try to bring myself down to 15% and be prepared for a retest of the previous lows sometime over the next month at which point I&amp;#39;ll be down to 10% if that happens. 

I still feel like I should take some of my gains in Canadian banks but their dividends are beyond solid. Doesn&amp;#39;t seem worth the hassle in the long term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:32 </td>
   <td style="text-align:left;"> $QQQ $SPY it is possible that the removal of fed stimulus combined with slowing economic growth could result in the market returning to Feb 2020 levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:32 </td>
   <td style="text-align:left;"> $SPY In this stock market gains won’t stay at-least for 1 weeks after every retrace. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:26 </td>
   <td style="text-align:left;"> $SPY If the 200 DMA doesn&amp;#39;t hold then the market is doomed.  
 
If it holds we will see a bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:12 </td>
   <td style="text-align:left;"> $SPY don’t freak out 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:11 </td>
   <td style="text-align:left;"> $SPY those who blame poor zucky for their losses are anti-Semitic. 
The libtards taught me to bring race into everything . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:33:00 </td>
   <td style="text-align:left;"> $SPY $FB SO THATS WHAT HAPPENED
Makes sense now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:32:57 </td>
   <td style="text-align:left;"> $SPY $PYPL $HOOD $SOFI $FB I was taking a dump on the toilet and when I went to wipe I was thinking about these stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:32:53 </td>
   <td style="text-align:left;"> $SPY Mark fuckinberg how was that 32 billion loss today you ok? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:32:22 </td>
   <td style="text-align:left;"> $FB .....The weighting system....☠ It is absolutely terrible when a handful of stock can affect an entire Market...😪 Anyway here&amp;#39;s a line for you $AAPL $TSLA $MSFT $SPY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:32:07 </td>
   <td style="text-align:left;"> $SPY bears getting exited for nothing lol, they’ll say it’s manipulation in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:32:07 </td>
   <td style="text-align:left;"> $FB 
Whole market will bleed tomorrow. $SPY 390$ on the way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:31:48 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:31:33 </td>
   <td style="text-align:left;"> $SPY Yes, not good thanks to $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:31:28 </td>
   <td style="text-align:left;"> $NFLX and $FB bulls fighting over which dip is the best to buy. Lmao if you’re buying dips in this market y’all need JESUS. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:31:20 </td>
   <td style="text-align:left;"> $SPY they’ve been manipulating this market from the jump - the entire reason $BTCX WAS EVEN CREATED was so wallstreet &amp;amp; fake news could direct out flowing money 💰 away from precious metals because that would cause them to lose control of the price and would really be an accurate gauge for inflation $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:31:18 </td>
   <td style="text-align:left;"> $SPY VIX 🚀. PUTS will print 3 days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:31:12 </td>
   <td style="text-align:left;"> $SPY 445 tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:31:11 </td>
   <td style="text-align:left;"> $SPY will be green by premarket… just watch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:30:53 </td>
   <td style="text-align:left;"> $SPY ⚡️ ⛈ someone HALLLLLLP  at least Im hedged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:30:53 </td>
   <td style="text-align:left;"> $SPY $NFLX and $FB has disappointed their fellow FAANGs. $AMZN can you redeem? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:30:47 </td>
   <td style="text-align:left;"> $SPY is meet Kelvin still holding? He panic sold then fomo the green candle, thats a rookie mistake. 

Never fomo the green candle! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:30:25 </td>
   <td style="text-align:left;"> $SPY 

What’s the F in FANG, you dofuses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:30:23 </td>
   <td style="text-align:left;"> $MTCH &amp;quot;ROMANTICUS ATTICUS&amp;quot; CIRCA IIVX MAtch Group/Bumble/Tinder ancestor $spy will bring it all down tomorrow! 😂 
 
&amp;quot;SHORTTHETOPBRO&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:30:07 </td>
   <td style="text-align:left;"> $SPY 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:29:56 </td>
   <td style="text-align:left;"> $SPY bump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:29:10 </td>
   <td style="text-align:left;"> $SPY it’s dead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:29:10 </td>
   <td style="text-align:left;"> $SPY yes it&amp;#39;s Zuckerberg&amp;#39;s fault. Not Biden. Not Jpow. Not your moronic actions. 
Keep on blaming a &amp;quot;poor Jewish man&amp;quot; for your stupidity.   
Bulls are anti-Semitic. 
Where are the Jewish leagues???  🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:29:08 </td>
   <td style="text-align:left;"> $SPY tech is dead, value back in style $UNH $BRK.B $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:45 </td>
   <td style="text-align:left;"> $SPY $QQQ Do you still love stocks? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:38 </td>
   <td style="text-align:left;"> $SPY the pandemic isn&amp;#39;t good for the economy who would have thought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:28 </td>
   <td style="text-align:left;"> $SPY telling you…460 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:24 </td>
   <td style="text-align:left;"> $SPY is the V still on? Should i swap puts for calls tomorrow? Bhahahahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:23 </td>
   <td style="text-align:left;"> $SPY the most entertaining thing about this is…1 stock had all this power to drop everything….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:22 </td>
   <td style="text-align:left;"> $SPY it’ll Bounce tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:20 </td>
   <td style="text-align:left;"> $SPY  $IWM $QQQ $DIA all daily Macd has crossed UP. Ignore the noise. Never seen so much scared newbies in my life before. If you can’t handle the markets go work at a regular 9-5 job. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:18 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:18 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWN jesus wait until the Fed actually raises rates in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:16 </td>
   <td style="text-align:left;"> $SPY So, risk off? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:14 </td>
   <td style="text-align:left;"> $SPY Hey stock twats, the DOW isn’t selling off. 

Hint, hint, hint. Buy value, not growth. 

Also, SPY isn’t crashing 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:09 </td>
   <td style="text-align:left;"> $SPY 400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:06 </td>
   <td style="text-align:left;"> $SPY if we open below 452, we WILL see 443 by eod fri </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:28:05 </td>
   <td style="text-align:left;"> $PLTR $QQQ $SPY $TSLA $FB 

As much as it sucks with Facebook dropping all of my stocks, I would love for Facebook to keep bleeding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:59 </td>
   <td style="text-align:left;"> $SPY futures look extremely bullish I&amp;#39;m going all in 

-The Village Idiot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:58 </td>
   <td style="text-align:left;"> $SPY $QQQ I&amp;#39;m actually relieved we cooled off the RSI for the next leg down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:57 </td>
   <td style="text-align:left;"> $SPY futes reimbursing ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:55 </td>
   <td style="text-align:left;"> $SPY down LMAO 4k ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:48 </td>
   <td style="text-align:left;"> $SPY tm these puts baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:44 </td>
   <td style="text-align:left;"> $SPY can I get uhhhhh ☝️ limit down please 🥺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:43 </td>
   <td style="text-align:left;"> $SPY seriously recommend reading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:31 </td>
   <td style="text-align:left;"> $SPY why when traders post bearish analysis they are railed and made to feel less than? “You moron wait til we hit ATH” Prices go up and down. Maybe this can be a lesson on being open and worrying about your own trades. Sharing information doesn’t make people bearish 100% or bullish 100%. And doesn’t reflect on them being a shit person or not. Just saying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:09 </td>
   <td style="text-align:left;"> $SPY to close out positions or not…. That is the question???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:27:02 </td>
   <td style="text-align:left;"> $QQQ The crash this year will be epic. This is just the beginning $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:26:45 </td>
   <td style="text-align:left;"> $SPY Next leg down will take us below  400 to fill open gaps….probably overshoot ….always does… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:26:43 </td>
   <td style="text-align:left;"> $SPY Thanks Zuck.. $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:26:27 </td>
   <td style="text-align:left;"> $SPY futures are gone 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:26:04 </td>
   <td style="text-align:left;"> $SPY To all the degenerate gamblers that made a fortune on  $FB and $pypl today Congratz! ang fu%k you! haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:25:49 </td>
   <td style="text-align:left;"> $SPY Maybe he should cure delusions  of grandeur  first. Then work on this one.
https://www.google.com/amp/s/www.nytimes.com/2022/02/02/us/politics/biden-cancer-moonshot.amp.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:25:49 </td>
   <td style="text-align:left;"> $SPY futes kinda not rippin ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:25:49 </td>
   <td style="text-align:left;"> $SPY It begins!
Clownshow!
Compelling evidence is showing downside with velocity ah although who am I to call such events? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:25:42 </td>
   <td style="text-align:left;"> $SPY 500,000 jobs lost in a single month with nothing to show for it besides corona being used as a justification for just about everything.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:25:34 </td>
   <td style="text-align:left;"> $SPY if 452 dont hodl we gonna see 451.99 , yeah i just go ahead and block a few of those dog shit mfs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:25:25 </td>
   <td style="text-align:left;"> $AMC  Everybody knows in Financial  Circles .. $GS Goldman Sachs  
Pins the S&amp;amp;P $SPY  Since 3 + yrs ..  
So are they dumb to buy on 1//28 Jan on that Great meme Short Squeeze day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:25:19 </td>
   <td style="text-align:left;"> $SPY my 445p gonna be nice I want 1000% once amzn flushed down the toilet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:25:05 </td>
   <td style="text-align:left;"> We all $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:24:57 </td>
   <td style="text-align:left;"> AH $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:24:55 </td>
   <td style="text-align:left;"> $SPY fb really going to take there whole market down with it 😣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:24:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $FB 🥤🐻🍿 https://m.youtube.com/watch?v=stuHt7ZRYrQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:24:48 </td>
   <td style="text-align:left;"> Tomorrow $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:24:38 </td>
   <td style="text-align:left;"> $SPY 

2022 = the year liberals got REKT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:24:29 </td>
   <td style="text-align:left;"> $SPY all I see is bright red after hours, is this the end???? 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:52 </td>
   <td style="text-align:left;"> $SPY  even Bloomberg analysts already told you don’t turn your back on this volatility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:52 </td>
   <td style="text-align:left;"> $SPY damn, I hate FB. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:52 </td>
   <td style="text-align:left;"> $SPY $451 needs to hold for you bulls if not we’re seeing $448 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:37 </td>
   <td style="text-align:left;"> $SPY I’ll be shocked if there’s not at least some dip buying tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:36 </td>
   <td style="text-align:left;"> $SPY $QQQ I love how they&amp;#39;re holding it here till 8pm...then the shit show starts...This idiotic bounce of 8%+ in 3 days is ludicrous in this enviroment...this only means we see much more pain coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:30 </td>
   <td style="text-align:left;"> $SPY dark pools have been buying the crap out of the fear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:13 </td>
   <td style="text-align:left;"> $SPY Dramatic bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:13 </td>
   <td style="text-align:left;"> $SPY wtf is going on??? Is this bc Biden ordered the 3000 troops??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:10 </td>
   <td style="text-align:left;"> $SPY Let’s go to $445 by market open tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:23:03 </td>
   <td style="text-align:left;"> $SPY something tells me that 463 gap is gonna be talked about by bulls like bears talked about the 401 gap last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:22:47 </td>
   <td style="text-align:left;"> $SPY 5% drop day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:22:45 </td>
   <td style="text-align:left;"> $SPY they’re rigging markets like Precious metals $DJIA 🤦‍♂️  🤖 Mr.Algo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:22:44 </td>
   <td style="text-align:left;"> $SPY It wanted to fall today but the dip buyers just kept piling on as if a move hadn&amp;#39;t happened yet lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:22:37 </td>
   <td style="text-align:left;"> $SPY feels like the past few days were the &amp;quot;return to normal&amp;quot; phase before the actual dump, the trends show it as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:22:29 </td>
   <td style="text-align:left;"> $SPY Reload 254s TMR? Round 2? Thanks bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:22:08 </td>
   <td style="text-align:left;"> $SPY everything was a lie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:22:05 </td>
   <td style="text-align:left;"> $SPY 2 months ago,  market would have shrugged this FB er off. 

This is a clear sign of what&amp;#39;s to come, finally er and economic news mean something 🤔 👏 👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:22:04 </td>
   <td style="text-align:left;"> $SPY this is what I wanted to show you. From yesterday near the bell. We win again Mr. Market now Do your worst </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:22:01 </td>
   <td style="text-align:left;"> $SPY stocktwits update so now i can see people argue in HD! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:21:47 </td>
   <td style="text-align:left;"> $SPY dark pools - no big selloff (&amp;gt;45% still).   Similar to March 2020 action where buy every dip worked 🤔.   Meanwhile, DOW futures are almost green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:21:31 </td>
   <td style="text-align:left;"> $SPX $SPY $VIX 

https://c1b3a0cd-e4de-46b2-b44f-e72cd6dcbae1.filesusr.com/ugd/ea4f38_de8ffd55e995458e8b17e9d78671f720.pdf

Attached is a copy of yesterday’s $SPX Performance Report.  Today, we added more content. 

Not financial advice. Please read disclaimer link below. Thank you. 

Disclaimer: www.dovewoodcapital.com/general-3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:21:30 </td>
   <td style="text-align:left;"> I found Moo $SPY 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:21:25 </td>
   <td style="text-align:left;"> $SPY 

This is all I hear every time it violently changes direction

https://youtu.be/U1UtRnGn5hc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:21:22 </td>
   <td style="text-align:left;"> $SPY Wow, Valuations actually matter now? What a world! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:21:16 </td>
   <td style="text-align:left;"> $SPY &amp;quot;is it not the rich who oppress you?&amp;quot; &amp;quot;Is it not they who drag you into court?&amp;quot;
Remember what is said in the epistle of James when the Fed turns your money into Zimbabwe dollars to appease the rich. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:21:08 </td>
   <td style="text-align:left;"> $SPY Is there any hope for my friday 458C&amp;#39;s or am i a loser for not taking profit? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:21:05 </td>
   <td style="text-align:left;"> $SPY earnings driven .. don’t really care… drop a bomb or something .. otherwise this is nothing .. growth wins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:21:03 </td>
   <td style="text-align:left;"> $SPY murder on the dance floor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:20:59 </td>
   <td style="text-align:left;"> $SPY It begins! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-03 08:20:52 </td>
   <td style="text-align:left;"> $SPY Early innings of a nasty Bear market….Fed is the only thing propping this bubble ….Fed is fucked… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 09:03:35 </td>
   <td style="text-align:left;"> $QQQ yolo 370 EOW 
https://www.cnbc.com/2022/02/02/januarys-payrolls-report-on-friday-could-be-rough-with-as-many-as-400000-jobs-lost-by-one-estimate.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 09:03:28 </td>
   <td style="text-align:left;"> $QQQ Where are the bulls................ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 09:02:32 </td>
   <td style="text-align:left;"> $PINS $LSPD $QQQ Account Challenge Update:  
Start January 13,2022  
Starting: $5,000  
Current: $45,212  
Goal: $100,000 by end of February  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next pay👀, tinyurl.com/fg7YnbzWea2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 09:01:37 </td>
   <td style="text-align:left;"> $QQQ cmom china pump it up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 09:01:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUT Wow everything is dying after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 09:00:55 </td>
   <td style="text-align:left;"> $QQQ imagine if Google&amp;#39;s eps was not good... Amazon will tank this further...but we&amp;#39;d have seen a full blown 1929 had Google not been positive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 09:00:35 </td>
   <td style="text-align:left;"> $QQQ oh my lordie 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 09:00:29 </td>
   <td style="text-align:left;"> $QQQ LET THE BLOOD SPILL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 09:00:04 </td>
   <td style="text-align:left;"> $SPY $QQQ Does not mean all out collapse. Just repricing of overpriced stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:59:35 </td>
   <td style="text-align:left;"> $XLF $SPY $QQQ $IWM $DIA This is an excellent example of the Feds medaling in the market.2017, 2018,2019 it just trends normally and then along comes the Fed. Now I&amp;#39;m not saying they shouldn&amp;#39;t have done anything, but geez!! Protect your capital, the volatility is not going away any tine soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:58:31 </td>
   <td style="text-align:left;"> $QQQ Sell sell sell, grab your profits before they become losses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:58:30 </td>
   <td style="text-align:left;"> $FB $QQQ Investors wipe almost $200 billion from Meta -FT 🐳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:57:47 </td>
   <td style="text-align:left;"> $QQQ $TQQQ Holding through the storm ☔️ hope to see y’all on the other side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:57:22 </td>
   <td style="text-align:left;"> $QQQ does $amzn save the market tomorrow?🤔 seemed like they had their busiest season yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:57:04 </td>
   <td style="text-align:left;"> $SPY $QQQ one amazon miss away from this ship really sinking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:56:05 </td>
   <td style="text-align:left;"> $SHOP $AMZN word on the street Amazon gonna got it out of the park with earnings $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:55:06 </td>
   <td style="text-align:left;"> $QQQ minimum -3.5% tomorrow easily, could also be the worst day in 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:54:53 </td>
   <td style="text-align:left;"> $QQQ fall tomorrow will be felt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:54:48 </td>
   <td style="text-align:left;"> $QQQ if the WAR start the MARKET be AWESOME 😎……!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:54:28 </td>
   <td style="text-align:left;"> $SPY Watch futures after close in six minutes!!! $ARKK $QQQ Will be very telling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:53:50 </td>
   <td style="text-align:left;"> As already mentioned a few weeks ago: 
 
Name change to META proved unlucky for $FB 
 Name change to BLOCK proved unlucky for $SQ  
 
Any other company wants to change their name? 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:52:15 </td>
   <td style="text-align:left;"> $QQQ crushed by Facebook,,, the most ignominious way to die.  
 
SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:52:01 </td>
   <td style="text-align:left;"> $SPY what good news is left to pump up the market?  more QE?  nope.  lower rates?  nope.  world peace?  nope.  Biden?  nope.   Amazon earnings?  not likely.  market is screwed.  $qqq $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:51:38 </td>
   <td style="text-align:left;"> $QQQ looking at chart, tommorow gonna be bloody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:51:13 </td>
   <td style="text-align:left;"> $QQQ Dropping it’s nuts like a bag of groceries </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:51:11 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

THIS POS BETTER BE BALLS DEEP RED 

TOMORROW, I WANNA SEE AN 

INSTITUTIONAL DUMP OF A LIFETIME... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:50:55 </td>
   <td style="text-align:left;"> Facebook - before and after 
$FB $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:50:40 </td>
   <td style="text-align:left;"> $QQQ and we got fakebook ER gift </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:50:03 </td>
   <td style="text-align:left;"> $QQQ Plot twist : Gap up tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:50:01 </td>
   <td style="text-align:left;"> $QQQ people shorting the bottom are very similar to people buying the top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:50:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 71996400. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:49:52 </td>
   <td style="text-align:left;"> $QQQ POP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:49:17 </td>
   <td style="text-align:left;"> $SPY Huge Gap to fill to the upside! I would not even try going short here! Go long till we get a rejection! Till then this is going $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:49:11 </td>
   <td style="text-align:left;"> $QQQ 359.00 by morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:48:34 </td>
   <td style="text-align:left;"> $QQQ futures so bright (red!!) I gotta wear shades. Jobs report coming out soon too. Oh man y’all bulls in trouble tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:48:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA BULLS DUMB WATER WET 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:48:01 </td>
   <td style="text-align:left;"> $QQQ Zuckerberg just fucked us over, shame on hiiim👊🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:46:31 </td>
   <td style="text-align:left;"> $FB $AMZN $QQQ all we need now is Russia war announcement after amazon earnings for a total market collapse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:45:53 </td>
   <td style="text-align:left;"> $SPY $QQQ those who bought the ol’ Tom Lee pump scheme </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:45:47 </td>
   <td style="text-align:left;"> $QQQ why is this even down? Lol. Troop deployment news came out at lunch. Green tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:45:14 </td>
   <td style="text-align:left;"> $QQQ why the crash? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:44:39 </td>
   <td style="text-align:left;"> $SPY  After hours melt down. 
Fake upside breakout today. 457 resistance zone has been defended which keeps 452ish target in play. 452 support needs to hold or melt down begins to 445ish = strong support/buy zone.
Type of reaction we saw this afternoon (hit 457s target/ resistance, revisted, tried to pop above then failed is *typically* good for a short term reversal at least) 452-25 remains target. Likely initial morning pop then fail triggers to 445s. $QQQ $IWM $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:44:12 </td>
   <td style="text-align:left;"> $FB 42 “expert” analysts had buy ratings on this. More proof that analysts are fucking clueless/useless $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:44:07 </td>
   <td style="text-align:left;"> $QQQ I missed the news, why is everything down after hours? $SPY $TSLA $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:43:14 </td>
   <td style="text-align:left;"> $QQQ green tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:43:03 </td>
   <td style="text-align:left;"> $QQQ They are keeping the Q’s shored up until the extended hours trading is closed

Then they will sink it another 140 -160 points  

NASDAQ down at least 380-420 points tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:42:08 </td>
   <td style="text-align:left;"> $QQQ  
 
QQQ Key Levels Grid For Feb 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:41:47 </td>
   <td style="text-align:left;"> $QQQ amzn announce split?&amp;gt;&amp;gt;&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:41:31 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMZN Bezos tomorrow to all bears: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:41:13 </td>
   <td style="text-align:left;"> $ES_F today broke down long before poor $FB earnings right over the 61.8 fib retrace. The key to trade ES_F is levels, NOT PATTERNS like stocks! $SPY $QQQ Note: I still think markets will head lower  but just play directional. Look for shorts if market breaking down, look for longs if levels hold - simple. Don&amp;#39;t make too many trades in opposite directions! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:40:59 </td>
   <td style="text-align:left;"> $QQQ Tom Lee from strat fund said this would be face ripper rally, guess he forgot to mention which direction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:40:59 </td>
   <td style="text-align:left;"> $QQQ futures so bright (red!!) I gotta wear shades. Jobs report coming out soon too. Oh man y’all bulls in trouble tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:40:41 </td>
   <td style="text-align:left;"> $QQQ yolo 370 eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:40:23 </td>
   <td style="text-align:left;"> $QQQ 🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:40:21 </td>
   <td style="text-align:left;"> Nasdaq futures drop as Facebook leads tech shares lower

$QQQ $FB $SPY

https://www.cnbc.com/2022/02/02/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:39:57 </td>
   <td style="text-align:left;"> $QQQ only old ppl use $FB, should’ve seen that coming, everyone is now on Twitter or TikTok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:39:15 </td>
   <td style="text-align:left;"> $QQQ let&amp;#39;s V </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:39:03 </td>
   <td style="text-align:left;"> $QQQ Bull Flag Face Ripper inbound 

“Violent Recovery” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:38:55 </td>
   <td style="text-align:left;"> $SPY $QQQ tomorrow is guna be a fun one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:38:21 </td>
   <td style="text-align:left;"> $QQQ What the hell is happening with FB, 20% down on a big cap is huge. I just bought some 370 puts 2 minutes before the market close and saw them doubled in less than 5 minutes. Crazy 100% profit in 5 minutes, this market is crazy too much volatility. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:38:13 </td>
   <td style="text-align:left;"> $SPY to $QQQ we&amp;#39;ve been disconnected.  
http://vixcentral.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:38:11 </td>
   <td style="text-align:left;"> $SPY $QQQ  this market is like my girlfriends vagina it will take anything good you have and make it disappear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:36:44 </td>
   <td style="text-align:left;"> $QQQ hey where are the bulls that said we would be at $390 by end of the week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:36:21 </td>
   <td style="text-align:left;"> $QQQ bulls deserve it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:35:49 </td>
   <td style="text-align:left;"> $QQQ Even though everyone else is losing a ton, thanks to the overpaid analysts who are were all in love with with FB,   Zuck sure ain&amp;#39;t hurting...he&amp;#39;s been selling gobs of stock well above 300 bucks a share everyday from April to November....he&amp;#39;s got more cash in the bank from selling FB over that 2021 six month period then GOD... 
 
Just take a looksie: 
 
https://finviz.com/insidertrading.ashx?oc=1548760&amp;amp;tc=7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:35:16 </td>
   <td style="text-align:left;"> $QQQ it’s so hard to trade these markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:33:39 </td>
   <td style="text-align:left;"> $SPY $FB $TWTR $DWAC $QQQ 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:33:32 </td>
   <td style="text-align:left;"> $QQQ $SPY it is possible that the removal of fed stimulus combined with slowing economic growth could result in the market returning to Feb 2020 levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:33:13 </td>
   <td style="text-align:left;"> $QQQ what do we open at tomorrow 358? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:33:05 </td>
   <td style="text-align:left;"> $QQQ where did the bulls go? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:31:07 </td>
   <td style="text-align:left;"> $BTC.X have fun go broke $QQQ $FB  or make a tonne shorting in kucoin.com ( i researcehd they are best short trading app) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:30:40 </td>
   <td style="text-align:left;"> $QQQ This represents 100% retracement of 2021, Is it likely to do a total retracement, well it already went past 50% so very possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:30:37 </td>
   <td style="text-align:left;"> $QQQ just setting the limit orders of the lower fib retracements on my highest conviction plays. Probably going to be dip the ladle in my fav plays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:30:04 </td>
   <td style="text-align:left;"> $QQQ rejected 50 DEMA. RIP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:28:45 </td>
   <td style="text-align:left;"> $SPY $QQQ Do you still love stocks? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:28:27 </td>
   <td style="text-align:left;"> $QQQ As people spent more time on Youtube and google time spent on facebook gone down as a result. As Prime members increased netflix had lower users. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:28:20 </td>
   <td style="text-align:left;"> $SPY  $IWM $QQQ $DIA all daily Macd has crossed UP. Ignore the noise. Never seen so much scared newbies in my life before. If you can’t handle the markets go work at a regular 9-5 job. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:28:18 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWN jesus wait until the Fed actually raises rates in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:28:09 </td>
   <td style="text-align:left;"> $QQQ I won’t believe this will open down 2%+, I’m guessing more like 1.3-1.4% down then bleed more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:28:05 </td>
   <td style="text-align:left;"> $PLTR $QQQ $SPY $TSLA $FB 

As much as it sucks with Facebook dropping all of my stocks, I would love for Facebook to keep bleeding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:27:58 </td>
   <td style="text-align:left;"> $SPY $QQQ I&amp;#39;m actually relieved we cooled off the RSI for the next leg down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:27:26 </td>
   <td style="text-align:left;"> $QQQ THOSE ARE SOME WILD CANDLES ON THE 1 DAY 5MIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:27:18 </td>
   <td style="text-align:left;"> $QQQ $400 inbound </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:27:02 </td>
   <td style="text-align:left;"> $QQQ The crash this year will be epic. This is just the beginning $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:26:53 </td>
   <td style="text-align:left;"> $QQQ AMZN will miss too. Yikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:26:09 </td>
   <td style="text-align:left;"> $QQQ So when is the $QQQ reversal? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:25:49 </td>
   <td style="text-align:left;"> $QQQ You&amp;#39;ve got to find some humor in the fact that all day shorts were getting squeezed on many charts, and in the last minute of the day many stocks have a giant green volume bar from retail shorts covering, and then after hours they the rug was finally pulled only after they covered. LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:24:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $FB 🥤🐻🍿 https://m.youtube.com/watch?v=stuHt7ZRYrQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:24:33 </td>
   <td style="text-align:left;"> $GOOGL #inthecrosshairs  Resistance strikes again.  #stocks #stockmarket #stocktrading #options #optionstrading  #money  $QQQ $NASDAQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:24:10 </td>
   <td style="text-align:left;"> $QQQ is one of the highly manipulative index among 4 indexes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:23:36 </td>
   <td style="text-align:left;"> $SPY latexe147d27ef34b14bb87b114920528c867 
It&amp;#39;s more fun to stay with cash and look at the stock crash than make money from long 
I profit that i am not losing money when it&amp;#39;s crashing 
And profit all the way up after my buy order  filled
Big money 🤑💰
Ttd is perfectly match to aggressive swing movements
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:21:55 </td>
   <td style="text-align:left;"> $QQQ It has  came back inside trend once already, my thought is it will visit this area throughout the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:20:25 </td>
   <td style="text-align:left;"> $SPY $QQQ i wonder if oil will be the new tech..? oil keeps the economy going. whats more important oil or tech?
$xle $oih buy buy buy lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:19:49 </td>
   <td style="text-align:left;"> $FB PEM. Price to Earnings Matters!  Value coming back into style baby!  $SPY $QQQ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:19:13 </td>
   <td style="text-align:left;"> All Social Medias are down horribly After Hours, holy... $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:17:20 </td>
   <td style="text-align:left;"> $QQQ bot futures trading is taking over. Good luck trading raw stock to make money. Buy and hold or selling premium is the only way to go now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:16:04 </td>
   <td style="text-align:left;"> $QQQ $SPY was last week an epic bear trap or was this week a big pump fake. 🤷‍♂️

As long as $350 holds.  😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:15:40 </td>
   <td style="text-align:left;"> $QQQ why the crash? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:15:21 </td>
   <td style="text-align:left;"> $FB $GOOG $QQQ 
Now we know why Google earnings report was so good lol 😂 
Ad dollars has to go somewhere, at least they are staying in QQQ 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:15:21 </td>
   <td style="text-align:left;"> $spy $qqq $fb $qcom $spot https://www.youtube.com/watch?v=yi-BWuR0Vww </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:14:32 </td>
   <td style="text-align:left;"> $SPY $QQQ many investors are getting a rude awakening to their overvalued holdings. Valuation eventually matters and when growth slows everyone races for the exit at the same time. Stocks trading at 30 to 50 times forward earnings or 50 to 100 times sales is not normal and as the newbies learned its never different this time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:14:06 </td>
   <td style="text-align:left;"> Would not be surprised if $GOOG carried market up, $FB takes it down and $AMZN brings it right back up w blowout earnings after the bell tomorrow. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:14:00 </td>
   <td style="text-align:left;"> $QQQ This has already started rolling over on the monthly chart.  Monthly 10 day moving average is $370.  At some point it&amp;#39;s going back in the channel...  Stay hedged my friends. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:13:21 </td>
   <td style="text-align:left;"> $DJIA $DIA Breadth Thrust signal triggered today as  % of stocks above 5 DMA switched from below 10% to over 90% in less than 10 days. This has bullish implications for the $NDX $QQQ which during last 10 years has posted an 85% win rate in 3 months when this signal triggers. More details here:  https://marketcharts.com/page/09ea3486 @MarketCharts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:11:38 </td>
   <td style="text-align:left;"> $QQQ rally time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:11:27 </td>
   <td style="text-align:left;"> $QQQ mother of all clowns 🤡 @Dr_Stoxx  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:11:24 </td>
   <td style="text-align:left;"> $QQQ sigh why do I do this to myself...if we don&amp;#39;t see a small bounce to 363-364 tmr I just lost everything fuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:11:15 </td>
   <td style="text-align:left;"> $QQQ This morning QQQ early premarket was trading at $370.  People couldn&amp;#39;t get enough of it and drove it up to $372.  12 hours later QQQ was trading at $362 (almost 3% lower) and suddenly almost no one wanted to buy it and it dropped another $2.00. One thing that has helped in my trading career was to stop thinking the markets (and people) act rationally.  They don&amp;#39;t.  You will probably trade better and sleep better at night when you realize at times the market is just crazy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:11:04 </td>
   <td style="text-align:left;"> $QQQ Textbook 50% reversal on Fibonacci to $370. Now we have a measured move coming all the way down $299. Buckle up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:10:42 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $SQQQ  
 
For old times sake, just going to drop this beauty again for a kind reminder.  Turn off your log scale, and view the market in all it&amp;#39;s REAL and exaggerated perversion.  Apples to apples, oranges to oranges.    Looks like a profitable future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:10:32 </td>
   <td style="text-align:left;"> $qqq $spy $spx $ndx $tsla https://www.youtube.com/watch?v=JZ63GccJBAY&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:10:18 </td>
   <td style="text-align:left;"> $SPY $QQQ this is really not cool! I sell my puts, this fucking trash goes down! Ugh so stupid!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:10:07 </td>
   <td style="text-align:left;"> $QQQ Load the boat. Going to be a volatile sob but these sell offs are insane and we are getting into some real valuation now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:09:45 </td>
   <td style="text-align:left;"> $tsla $qqq $aapl $btc.x https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:09:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Kinda feels good sitting on 50% cash right now. 🐳

https://youtu.be/1iyIf8AJgWU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:09:13 </td>
   <td style="text-align:left;"> $QQQ this turd dumped right after I loaded on calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:09:01 </td>
   <td style="text-align:left;"> $QQQ 📈🖍 bear trap “violent rebound” incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:08:36 </td>
   <td style="text-align:left;"> $SPY Looks like the $QQQ will catch up with the $IWN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:08:21 </td>
   <td style="text-align:left;"> $SPY $QQQ Limit down futures baby...by 10pm we should see much more pain lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:07:56 </td>
   <td style="text-align:left;"> $QQQ $AMD $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:07:41 </td>
   <td style="text-align:left;"> $QQQ $250 by close tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:07:11 </td>
   <td style="text-align:left;"> $QQQ F this pos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:06:55 </td>
   <td style="text-align:left;"> $QQQ how much down is this gonna be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:06:24 </td>
   <td style="text-align:left;"> $SPY $QQQ how did it age? not only did i buy at the close i have been adding on every ridiculous pump this week...most of you have never even lived thru much less traded an inflationary bear market but I have ...tomorrow is pay day...this chump @FreakingClownBrohwas on his 2 day old ST account was getting lippy earlier feel free to come by and laugh at him...😂😂😂 $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:05:56 </td>
   <td style="text-align:left;"> $SPY $QQQ there might be a lot more air left to come out of the bubble stocks if $FB is getting punished like this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:05:23 </td>
   <td style="text-align:left;"> Stocks Rally On February 2, But Look Who May Have Crashed The Party $QQQ $AMZN $FB $SPX $PYPL https://talkmarkets.com/content/stocks--equities/stocks-rally-on-february-2-but-look-who-may-have-crashed-the-party?post=343389 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:05:12 </td>
   <td style="text-align:left;"> $SPY $QQQ The bears might have the upper hand right now and probably tomorrow morning but the bulls might be the ones laughing by the closing bell. The last few days showed that many people were still looking to buy the dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:04:12 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM Bears to perma bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:03:32 </td>
   <td style="text-align:left;"> $QQQ $AMD $FB I will see you all bright and early tomorrow for new bag holder orientation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:03:20 </td>
   <td style="text-align:left;"> $QQQ the more the market does these dumps the more it scares away investors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:02:15 </td>
   <td style="text-align:left;"> $QQQ Totally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:02:06 </td>
   <td style="text-align:left;"> $SPY $QQQ don’t be surprised with a massive futures buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:02:05 </td>
   <td style="text-align:left;"> $QQQ bears have these boards now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:01:37 </td>
   <td style="text-align:left;"> $FB Facebook has made some of the poorest business decisions imaginable including alienating a huge portion of society through censorship as well as (in my view) the nonsense METAverse pivot.  But rather than look in the mirror it’s easy to blame iOS privacy change headwinds, ad cutbacks, and similar secondary issues.  $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:00:57 </td>
   <td style="text-align:left;"> $QQQ $SPY https://www.youtube.com/watch?v=zo-x4PU8S6g 
 
to my moon bois who got yolo calls for today and friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:00:42 </td>
   <td style="text-align:left;"> so $FB is down to 2020 levels and the $QQQ has dipped...already down hard from January...and you guys don&amp;#39;t expect another rally?....by the time FB recovers...$qqq will be at another ATH...bear trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 08:00:31 </td>
   <td style="text-align:left;"> $QQQ $SPY lots of delusional bulls thinking these will go back to ath with the amount of companies that have dumped. If they do it’ll be carried by the top mega caps leading to a super bubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:59:58 </td>
   <td style="text-align:left;"> $QQQ 🔥🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:59:40 </td>
   <td style="text-align:left;"> $QQQ let’s go bitches!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:59:35 </td>
   <td style="text-align:left;"> $SPY everyone’s a genius in a bull market. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:59:28 </td>
   <td style="text-align:left;"> $QQQ $FB mark suckerberg dropped the ball </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:59:24 </td>
   <td style="text-align:left;"> $QQQ $SPY market dumps more often on earnings misses more often than rewarding good earnings. Tomorrow will be an absolute massacre. And if jobs numbers are bad…oh my </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:59:08 </td>
   <td style="text-align:left;"> $QQQ Hedges are edging hard tn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:58:38 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:58:23 </td>
   <td style="text-align:left;"> $QQQ 500 point free fall cause of the ZUCC smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:58:08 </td>
   <td style="text-align:left;"> $QQQ this isn&amp;#39;t the dip to buy... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:57:44 </td>
   <td style="text-align:left;"> $SPY a lot of support on the Nasdaq at 14400. $QQQ
See how this plays out. We&amp;#39;re in a bubble so literally everything is on the table. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:57:02 </td>
   <td style="text-align:left;"> I&amp;#39;m live on audio and chat with $ES_F live charting, select trades, commentary, etc.. It&amp;#39;s on discord which is free, but does require email sign up (I beleive). Click on broadcast under the &amp;quot;voice channel&amp;quot; on the left to hear audio. $SPY $QQQ #StockMarket #Futures #ESMinis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:56:59 </td>
   <td style="text-align:left;"> $QQQ have a good evening bag holders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:56:12 </td>
   <td style="text-align:left;"> $QQQ if it drops below 353 tomorrow it’s back on it’s way down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:56:01 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:55:58 </td>
   <td style="text-align:left;"> $QQQ my god… can we have a bounce to 364 tmr so I can break even lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:55:40 </td>
   <td style="text-align:left;"> $QQQ Everybody was making fun of Warren Buffett in 2021 ...In 2022 Warren be like...Fk Tech... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:55:20 </td>
   <td style="text-align:left;"> $QQQ wow futes absolutely shitter dumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:54:46 </td>
   <td style="text-align:left;"> $QQQ watch spy
Drop 6% tomorrow just to one up All the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:54:23 </td>
   <td style="text-align:left;"> $QQQ can we fast forward to tmr open, the anticipation to see what this will open at is killing me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:54:18 </td>
   <td style="text-align:left;"> @MonsterScalp load up ⬆️ $FB $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:54:05 </td>
   <td style="text-align:left;"> $QQQ $SPY the market tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:54:03 </td>
   <td style="text-align:left;"> $SPY $QQQ not sure what people thought. Most of the companies that ran up from covid low (excluding heavy weight tech) hit extreme pe ratios. With QE done by march the market has been pricing in proper valuations and normal pe ratios..look at zoom, etsy wayfair, roku, paypal, block. Spacs with crazy valuations. These things were not sustainable. It was just inevitable to come  back to earth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:53:50 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears are celebrating too early, one stock $FB is not gonna take the entire market down, there are many other companies posting very strong earnings 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:53:43 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:53:43 </td>
   <td style="text-align:left;"> @MonsterScalp $QQQ load the 🚤! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:53:39 </td>
   <td style="text-align:left;"> $SPY we need circuit breaker for old time sake. A nice 5%-6% on $QQQ tomorrow. The  bubble needs to pop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:53:24 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ Pump it up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:53:03 </td>
   <td style="text-align:left;"> $QQQ $FB still bleeding wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:52:47 </td>
   <td style="text-align:left;"> $SQQQ $TQQQ $QQQ  
 
Overnight dump is going to shake a lot of people.  Reverse FOMO come morning.  Everyone rushing to the exits. 
 
How low is Q going to go... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:52:04 </td>
   <td style="text-align:left;"> $GOOG sold or the -2% AH is all of what they will get tomorrow 

Honestly , got stopped at 360$ in my $QQQ with a small gains , instead of selling this morning near 370$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:51:43 </td>
   <td style="text-align:left;"> $QQQ tech bubble popped??? Holy **** </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:51:33 </td>
   <td style="text-align:left;"> $TTD how is buying now?!?!
The nasdaq going to halt collapse tomorrow
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:51:00 </td>
   <td style="text-align:left;"> $ABBV $IBM holding strong with this market meltdown. ✊🏼 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:50:29 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $ARKK $XLK  😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:49:52 </td>
   <td style="text-align:left;"> $QQQ Facebook is a small company in comparison to tech giants who already reported record earnings. NOOBs are selling another BTFD when market opens. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:49:20 </td>
   <td style="text-align:left;"> $spy $qqq $iwm if you have only been buying the dip for 2.5 years with weekly calls, your account is about to go zero </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:49:13 </td>
   <td style="text-align:left;"> $AABB $SPY $SPX $QQQ $NASDAQ When a OTC company comes out with GREAT NEWS and in the PR states they intend to up list to a MAJOR EXCHANGE is it coincidence that bashers appear and try to warn investors,especially when the company has NO DEBT/Recrd Profits/Record Gold/Global Exchange/First to market Global Gold currency system! https://finance.yahoo.com/news/asia-broadband-corporate-173900628.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:47:57 </td>
   <td style="text-align:left;"> $spy $qqq smells like crash again .. but I am waiting for a twit which will fix everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:47:55 </td>
   <td style="text-align:left;"> $FB $QQQ Buy Buy Buy Bitches! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:47:37 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;m bullish and own shares of QQQ, but happy I hedged a while back with puts right now... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:47:15 </td>
   <td style="text-align:left;"> $DBRG at least we haven&amp;#39;t followed $QQQ yet. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:46:47 </td>
   <td style="text-align:left;"> $SPY $QQQ MM waited to fuck you. Meta miss is an over reaction, but also a reason to trap those calls on SPY and Qs top ten weighted stonks. You&amp;#39;re fucked. $fb $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:46:39 </td>
   <td style="text-align:left;"> $QQQ 166k OI on june 325 puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:46:29 </td>
   <td style="text-align:left;"> $QQQ 370 end of week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:46:27 </td>
   <td style="text-align:left;"> $QQQ Those QQQ puts = 🤑.   Gheez 
 
My only regret is not holding more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:46:26 </td>
   <td style="text-align:left;"> $SPY $QQQ Time to ban TikTok in the US, we can’t allow a Chinese company to steal market share away from US company like $FB. Some younger kids don’t realize that TikTok is a Chinese company, they think it is a US company lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:46:23 </td>
   <td style="text-align:left;"> $LCID target met. Heres to it staying under at open tomorrow to collect premium. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:46:15 </td>
   <td style="text-align:left;"> $QQQ Jim Cramer did tell everyone to buy yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:44:37 </td>
   <td style="text-align:left;"> $QQQ Welp! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:44:29 </td>
   <td style="text-align:left;"> $QQQ $FB $SHOP $PLTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:43:39 </td>
   <td style="text-align:left;"> $QQQ $SPY markets hanging by a thread ($AMZN) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:43:25 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:42:59 </td>
   <td style="text-align:left;"> $QQQ tech is getting it&amp;#39;s balls blown off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:41:49 </td>
   <td style="text-align:left;"> $AMD Commercial Hedgers are short $ND_F. They are short and hitting the index. Just got to get thru it. $AMD gave you guidance. Stick with Su imo. https://finviz.com/futures_charts.ashx?t=NQ&amp;amp;p=d1  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:41:27 </td>
   <td style="text-align:left;"> $AAPL $FB $QQQ How many billions did Zuckerberg lose today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:41:03 </td>
   <td style="text-align:left;"> $SPY $QQQ holyshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:40:31 </td>
   <td style="text-align:left;"> P/E getting crushed in every direction $SPY $SPX $UVXY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:40:12 </td>
   <td style="text-align:left;"> $QQQ market might be down 10% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:40:07 </td>
   <td style="text-align:left;"> $QQQ literally one bad apple ruins the party </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:39:47 </td>
   <td style="text-align:left;"> $SPY $QQQ  $FB  literally crashed the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:39:17 </td>
   <td style="text-align:left;"> $QQQ we might see that double digit drop tomorrow!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:39:06 </td>
   <td style="text-align:left;"> $QQQ we down 5% tomorrow or what my calls toast? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:38:48 </td>
   <td style="text-align:left;"> $QQQ $SPY Genuinely think there needs to be a category above mega cap for Google, Microsoft and Apple now.... the giga cap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:38:43 </td>
   <td style="text-align:left;"> $SPY holding great over 200ma but $QQQ not so much. Wtf is this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:38:17 </td>
   <td style="text-align:left;"> $QQQ nonnoonnonononno </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:38:06 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : The Charts Continue To Improve (Technically Speaking For 2/2) https://www.stck.pro/news/QQQ/22414675 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:37:29 </td>
   <td style="text-align:left;"> $QQQ cup and handle on the q’s or we heading low low low low </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:37:11 </td>
   <td style="text-align:left;"> $QQQ Now all we need is for the bad winter storms coming across the state to wipe out Texas again and we really will have a supply chain issue on steroids </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:37:01 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Imagine you’re trying to sleep tonight while holding calls you bought at the close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:36:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB Mad respects for @Tradytics CANT DISAGREE HERE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:36:13 </td>
   <td style="text-align:left;"> $SPY $QQQ The trend has changed, January was all about STFR but this month is all about BTFD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:35:41 </td>
   <td style="text-align:left;"> $QQQ Well….elections have consequences, you Libs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:35:13 </td>
   <td style="text-align:left;"> $QQQ ,$SPY , $RUT , $IWM . In this environment,  where there are no more rocket emojis and YOLO playing out and you feel nothing is working out , it&amp;#39;s time to to reflect and build rules . NEVR FKING GIVE UP ! NEVER ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:34:21 </td>
   <td style="text-align:left;"> $SPY $QQQ Engaging STFR mode </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:33:13 </td>
   <td style="text-align:left;"> $ATVI $SPY $QQQ $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:32:48 </td>
   <td style="text-align:left;"> $SPY $QQQ 4 days of gains wiped out by the ZuckMeister 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:32:23 </td>
   <td style="text-align:left;"> $QQQ Work on your aim before you run out of ammunition. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:32:16 </td>
   <td style="text-align:left;"> $QQQ where’s 360 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:31:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $QCOM 

It’s to the slaughterhouse for these bloated piggies... 🐖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:31:00 </td>
   <td style="text-align:left;"> $FB this isnt $PYPL . There will be sizable bounces. A real chance trying to BTFD now can possibly be a real trap. Be careful.  We are in no man&amp;#39;s land. $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:29:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWN tomorrow will be one of those days where you just shouldn&amp;#39;t look at your account </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:29:00 </td>
   <td style="text-align:left;"> $SPY $qqq futes will be so dirty that you may want to open your skull and wash your brain with luke warm water to regain function. Tom Lee fucked you as noted on previous post. Violent February V rally my ass. Feb and Mar will be sucking volatility fat cock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:28:00 </td>
   <td style="text-align:left;"> $SPY $QQQ every noob trader out there right now with tech calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:27:44 </td>
   <td style="text-align:left;"> $QQQ -And never forget, Biden can implode at anytime🤣🤣🤣💵💵💵💵 Puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:27:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA $FB free speech is dead. I will
Most likely get banned tonight so consider this my last post. 

Big tech is coming for you. Soon we will
Be like a third world country. Hyperinflation will loom over the heads of everyone, we won’t be able to say things, books will be burned bc they’re not “woke”, the economic system will be so messed up it we will see millionaires starve. 

Prepare people! Get right with your maker! That is all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:26:36 </td>
   <td style="text-align:left;"> $PYPL $SPY $QQQ $CRSR $FB 

Me checking Nasdaq futes holding a port full of tech calls: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:24:35 </td>
   <td style="text-align:left;"> $QQQ $AMZN only thing that saves Amazon is if they pull a stock split
Like Google </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:24:00 </td>
   <td style="text-align:left;"> $FB $SPY $QQQ MARK ISN&amp;#39;T WELL! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:23:55 </td>
   <td style="text-align:left;"> $AMZN - A. Jassy no pressure. $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:23:51 </td>
   <td style="text-align:left;"> $SPY $QQQ How the Markets was so dry today you knew this was coming, got out quick. This is going down tomorrow guaranteed. The focus of the market is now on $AMZN if earnings turn out bad its going to be a bad Friday including Job reports going into next week. We&amp;#39;ll see how it plays out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:23:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

Love my cheap PUT. Will pay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:23:39 </td>
   <td style="text-align:left;"> $SPY $AMZN missing earnings with lowered guidance will seal the deal for SPY retreating to 400.   Add to that $GOOG profit taking, upcoming RATE HIKE, and WAR... leading to March going to be brutal.  $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:23:25 </td>
   <td style="text-align:left;"> $SQQQ $QQQ $NASDAQ  100 

“PEPPERSTONE NAS100 240 
Four hour confirmed 236 HODL”
(per Mike Khani) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:23:15 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $QQQ Crypto already had it’s correction and is bouncing off the bottom. Stocks have a long way down in go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:23:05 </td>
   <td style="text-align:left;"> How well do your systems work in a 🐻 regime? Something work looking into. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:22:43 </td>
   <td style="text-align:left;"> $QQQ now all we need is $NVDA to pull a fb paypal 20% drop and things will be all gravy $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:22:31 </td>
   <td style="text-align:left;"> $SPY $QQQ

Warned you last week, volatility dump. Accumulate put. Last impression is stronger than first impression. FB flopped, and Amazon is next. World is not normal. It&amp;#39;s done. 350 SPY and 290 QQQ. 50 point basis rate hike in March. 7 rate hikes at minimum in 2022. Oh, and don&amp;#39;t buy cyrpto, shit is pile of garbage. Pay your rent. LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:22:00 </td>
   <td style="text-align:left;"> $QQQ I hope they murder this bitch tomm... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:21:36 </td>
   <td style="text-align:left;"> $spy $qqq man, market exposure is deadly this year, day traders win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:21:07 </td>
   <td style="text-align:left;"> $QQQ 1 trick pony </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:20:19 </td>
   <td style="text-align:left;"> $QQQ what&amp;#39;s funny is that without knowing what earnings would be you could see the chart was setting up for a crash. Any time you see this pattern, run, it&amp;#39;s a cliff. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:20:15 </td>
   <td style="text-align:left;"> $SPY Be afraid.  Be VERY afraid.  $FB gap down below $235 overnight will gap $SPY down below 251. AGAIN.  $UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:20:12 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $QQQ $FB stocks are not an investable asset class at these levels. Digital assets will soar. Blow everyone’s mind </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:19:55 </td>
   <td style="text-align:left;"> $QQQ 

⚠️⚠️⚠️⚠️245 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:19:35 </td>
   <td style="text-align:left;"> $AMZN if delivers soft guidance and no stock split news, we can see $QQQ hitting $300. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:19:26 </td>
   <td style="text-align:left;"> $QQQ It&amp;#39;s like Mark Zuckerberg pulled the plug on the bathtub drain.  Glug, glug, glug... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:18:38 </td>
   <td style="text-align:left;"> $QQQ Who is next to Pop..? Keep the music playing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:18:01 </td>
   <td style="text-align:left;"> $SPY $QQQ #DIX prints is telling a different story. That&amp;#39;s a lot of consecutive bullish DIX prints. 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:17:41 </td>
   <td style="text-align:left;"> $SPY invest into where everyone hates and despises jan-march each year $QQQ $FB $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:17:24 </td>
   <td style="text-align:left;"> $QQQ y’all see $NQ_F rn 😭😭😭 ty $FB if $AMZN misses tomorrow this market will reverse down so hard everybody who was balls to the ball bullish needs to get clowned </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:17:13 </td>
   <td style="text-align:left;"> $QQQ shouldn’t check the futures now I am sick to my stomach. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:16:51 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM Russia invades ukraine, fed surprises with the 1st rate rise.

Gap fills $403 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:16:05 </td>
   <td style="text-align:left;"> $QQQ targets for end of week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:15:44 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ This is why.  
 
https://www.nytimes.com/2022/02/02/world/europe/us-nato-response-russia-demands.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:15:33 </td>
   <td style="text-align:left;"> $QQQ  CALL or PUT ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:14:51 </td>
   <td style="text-align:left;"> $SPY $QQQ need to reweigh indices. These mega caps need to be smaller size of weight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:14:48 </td>
   <td style="text-align:left;"> $SPY $QQQ I might get my chance to finally deploy some of this damn cash 💰 BIGLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:14:10 </td>
   <td style="text-align:left;"> $QQQ the who tech is dead because of $FB .  Crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:13:44 </td>
   <td style="text-align:left;"> $QQQ Got to love this market. Great growth companies at Major discounts nobody wants them. The same overvalued crap, they are buying it all time highs.with all the hopes of v shape recoveries </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:13:42 </td>
   <td style="text-align:left;"> $SPY $QQQ we cvs to revisit that $334 mark on the /$QQQ. So many of these stocks are still in bubble valuations.... So many can easily lose 60%-70% and still be overvalued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:13:06 </td>
   <td style="text-align:left;"> $QQQ I believe Bio sector will sign this year. This sector got hammered last year $XBI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:13:04 </td>
   <td style="text-align:left;"> $QQQ fites ripin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:12:57 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 2/2/2022 $SPY $XLF $QQQ $FB $MSOS https://www.chartguys.com/daily-market-videos/4124/strong-day-into-weak-afterhours-trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:12:56 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ U.S. Troops deployed in Europe and you&amp;#39;re all wondering wtf is going on? lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:12:35 </td>
   <td style="text-align:left;"> $soy $qqq someone chart for me please go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:12:13 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla $fb $PYPL 8th account. 7 perma ban via posting bearish on AMC, and 1 ban from fang stonk or indices tagged above. Stop being so sensitive. Bears on ST do DD and release info faster than your media heads on cnbc, YouTube, and Twitter. Fuck off. I had to unban this new account today for being RIGHT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:12:11 </td>
   <td style="text-align:left;"> $QQQ good days are over now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:12:04 </td>
   <td style="text-align:left;"> $QQQ talk about hitting the nail on the head. If you think this is bad wait until tomorrow and Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:11:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM Perma bulls are quite the species 😂

Make a call, be wrong, just become a long investor and claim stocks only go up long term

So no perma bull can ever make a wrong call

I like it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:11:43 </td>
   <td style="text-align:left;"> $QQQ incoming 52 week lows this week. Then comes the real crash.  what you morons get for buying these overpriced turds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:11:28 </td>
   <td style="text-align:left;"> $QQQ What stocks are good hedges to a tech bust ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:11:20 </td>
   <td style="text-align:left;"> $SPY $FB its the MARKET CLOSE that counts DONT FORGET THE GREEN WE LOCKED TODAY - this is AFTER HOURS FAKE NOISE on low volume, and UNREALIZED $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:10:56 </td>
   <td style="text-align:left;"> $SPY If you’re not aware that there’s bubble in most $QQQ companies valuations, then wait when our casino chair raise interest rates 👌🏽👌🏽👌🏽👌🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:10:45 </td>
   <td style="text-align:left;"> Great question $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:10:41 </td>
   <td style="text-align:left;"> $SHOP right now someone with a lot of money behind a laptop or Ipad is saying look at these pussies sell and buying up the shares afterhours $QQQ $ARKK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:10:13 </td>
   <td style="text-align:left;"> $QQQ $SPY  Now already looking for strong value stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:10:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA because people didn’t want to put up with a couple of tweets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:09:51 </td>
   <td style="text-align:left;"> $SPY $QQQ The DOW futures are actually up right now, value stocks are gonna shine over growth stocks tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:08:27 </td>
   <td style="text-align:left;"> Tech Wreak 2022! $FB $PYPL $TSLA $QQQ $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:08:06 </td>
   <td style="text-align:left;"> $QQQ $FB $SPY I’m sure the market won’t overreact tomorrow 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:06:04 </td>
   <td style="text-align:left;"> $FB $SPY $QQQ 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:05:24 </td>
   <td style="text-align:left;"> An update to the $QQQ trade suggestion: https://stocktwits.com/r/invest4success/t2syIwhsEP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:05:17 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $UVXY  
 
Market is forming the 2nd leg, but I don&amp;#39;t think the 2nd leg is lower than the 1st leg.  
 
$QQQ needs to retest $357--$360, another chance to get on bus if you missed the previous one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:04:45 </td>
   <td style="text-align:left;"> $SPY Futes zittin&amp;#39;. Ready to pop $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:04:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:04:17 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY think about it this way.... im an exceptional stock trader making over 150K on annual avg and im down 3K this week thus far and its not over. Youll all be fine its just bearish rn, hang in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:03:43 </td>
   <td style="text-align:left;"> $QQQ And here come the futures dip buyers. Lucky bastards. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:03:19 </td>
   <td style="text-align:left;"> $QQQ super market prices so high 
Fed f-ed everything and everyone 
Now their fake growth stocks crushed 
A big welcome to biden. He is finally effective </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:03:14 </td>
   <td style="text-align:left;"> $QQQ We guna give up that entire price drop in an hour like a few days ago?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:01:53 </td>
   <td style="text-align:left;"> $QQQ We&amp;#39;re Short viz $SQQQ and a few other names  
 
#SMAPro AI Powered Crystal Ball doing it&amp;#39;s damn job. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:01:29 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $QQQ The only logical thing you can do is hedge inflation with everything you have </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 07:00:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Why is anyone scared about social media companies’ stocks going down?  We all knew… $FB and $SNAP are getting rocked by TikTok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:59:46 </td>
   <td style="text-align:left;"> $QQQ $SPY when is a limit down coming? Tonight? After Amazon er? Or Monday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:59:07 </td>
   <td style="text-align:left;"> $QQQ $SPY how fast the narrative can change.  Reminds me of the Covid crash.  No one believed it and Wack. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:58:59 </td>
   <td style="text-align:left;"> $SPY $QQQ 6pm more downside,8pm continues,11pm down almost 5% 
boom bye bye </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:56:55 </td>
   <td style="text-align:left;"> $QQQ Short squeeze cometh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:56:20 </td>
   <td style="text-align:left;"> Ooooof $FB And to the $DWAC cult gloating this isn’t an either or. Everyone can lose $QQQ $TECS Mark “Zuckerberg&amp;#39;s &amp;#39;metaverse&amp;#39; business lost more than $10 billion last year” https://www.cnbc.com/2022/02/02/meta-reality-labs-reports-10-billion-loss.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:55:57 </td>
   <td style="text-align:left;"> $AMD $NVDA $QQQ $GOOGL My man Market Wizard is an absolute printer. Join the discord link in my bio to see these profits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:55:44 </td>
   <td style="text-align:left;"> $SPY Could see a -400 $ndx before close 

$QQQ $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:55:43 </td>
   <td style="text-align:left;"> $QQQ Good book , will share with you guys 
Its free on amazon 
you should read it 
https://www.amazon.com/gp/product/1734030917/ref=as_li_tl?ie=UTF8&amp;amp;camp=1789&amp;amp;creative=9325&amp;amp;creativeASIN=1734030917&amp;amp;linkCode=as2&amp;amp;tag=slavasrecipes-20&amp;amp;linkId=5ad4fa2cef4b379610657f6f1ff98f6a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:54:47 </td>
   <td style="text-align:left;"> $QQQ Looks like our old friend volatility is bouncing back for a bit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-03 06:54:41 </td>
   <td style="text-align:left;"> $QQQ R&amp;#39;uh R&amp;#39;oh. 
 
Short term pain inbound. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 09:02:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-02 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=H0zuPqhBSBc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 09:00:40 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $177.5 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:54:30 </td>
   <td style="text-align:left;"> $AAPL $GOOG $FB $NFLX $AMZN  
 
Now imagine AMZN misses ER tmr and AAPL as well as GOOG&amp;#39;s temporary ER gains begin to fade with overall sentiment...look out below for the 2nd leg down which could be worse than the one we just had in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:51:11 </td>
   <td style="text-align:left;"> $AAPL are futes ripping yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:51:11 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

THIS POS BETTER BE BALLS DEEP RED 

TOMORROW, I WANNA SEE AN 

INSTITUTIONAL DUMP OF A LIFETIME... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:49:30 </td>
   <td style="text-align:left;"> $FB Everyone should have seen this coming. Billions spent on name change. $AAPL privacy changes cost billions in ad revenue. Has no effect on $AMZN, however, so the movement there is just hedges trying to get cheapies in for tomorrow&amp;#39;s beat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:46:46 </td>
   <td style="text-align:left;"> $AAPL 
Apple: What’s not to admire?
From AppleInsider’s “Apple tops ‘most admired companies’ list for 15th year in a row”.
https://www.ped30.com/2022/02/02/apple-fortune-most-admired/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:46:13 </td>
   <td style="text-align:left;"> $AAPL where to bring the money to safety… why wouldn’t you want to run here from Fb etc here and goog you know your safe.. let’s see what $AMZN has in store next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:45:00 </td>
   <td style="text-align:left;"> $AAPL 

FB needs to learn to step up .. blaming AAPL do nothing to solve the problem.

It’s either Mark Z has to go or step up the game.

I believe changing FB name to Meta Is a bad move - it’s like putting a small bandaid on the wound after dismal report too. Now the problem grew much worse. 

Anyways, AAPL current price action shows how busy MM are dealing with exodus of investors wanting to park their money into safe place so they can make money without worries.

FB does not give out dividends nor stock splits..  just FB did buybacks That’s why FB failed to get investors confidence .. 

AAPL has done stock splits and pay dividends plus buyback. It’s very attractive to shareholders who want to park money long term.

So .. tmw .. I am not worried cause it’s going to be massive accumulation and busy day for MM dealing with money coming in from FB! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:44:13 </td>
   <td style="text-align:left;"> $AAPL 🍏❗️  Microsoft StockTwits, laughing at AAPL’s “Bear Games”.  Microsoft Twits, enjoying a peaceful evening.  AAPL Bear Twits…going full gangster.  This isn’t Motel 6.  It’s time to turn the lights out.  Sleep well, Bulls.  Leave the nightmares, to the Bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:43:58 </td>
   <td style="text-align:left;"> Apple (NASDAQ: $AAPL) Knocks It Out Of The Park https://www.billionaireclubcollc.com/apple-nasdaq-aapl-knocks-it-out-of-the-park/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:42:54 </td>
   <td style="text-align:left;"> I got to give $fb and $pypl the credit man. They are the only companies that honestly admit consumer pain and stop the madness of corporate profit over consumers pain, they honest company. Unlike $aapl evasive, no guidance. Honest guys admit problems, dishonest retards deny or evade problems.

https://www.cnn.com/2022/02/02/investing/paypal-consumer-spending-stock-earnings/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:41:01 </td>
   <td style="text-align:left;"> $FB So who is lying, $pypl and $fb that admit about pressure of inflation on consumers, or $aapl $googl and big techs saying party forever? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:39:57 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price 

https://youtu.be/XbtnBrBRxY0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:39:14 </td>
   <td style="text-align:left;"> $AAPL tech getting clobbered, but apple 🍏 is ur safest tech play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:35:04 </td>
   <td style="text-align:left;"> $FB - is at July 2020 pricing…. Wow 😮 

🚨 $AAPL $GOOG $TSLA $SNAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:32:25 </td>
   <td style="text-align:left;"> $FB - is at Sept 2020 pricing…. Wow 😮 

🚨 $AAPL $GOOG $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:32:22 </td>
   <td style="text-align:left;"> $FB .....The weighting system....☠ It is absolutely terrible when a handful of stock can affect an entire Market...😪 Anyway here&amp;#39;s a line for you $AAPL $TSLA $MSFT $SPY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:31:51 </td>
   <td style="text-align:left;"> $AAPL why going down? Any
News.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:31:17 </td>
   <td style="text-align:left;"> $AAPL There will be nowhere to hide except in Apple after Meta stocks decline. Long live apple!
They make $$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:30:30 </td>
   <td style="text-align:left;"> $AAPL gave us a false sense of security. They used that to justify buying the dip. $FB brought us back to the real universe lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:28:10 </td>
   <td style="text-align:left;"> $AAPL Love AAPL.  Is it worth doing CSP and Covered Calls on it?  
Trying to find another stock like TSLA to trade those types of options. 
 
https://youtu.be/tz_rBZ0bYVQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:28:08 </td>
   <td style="text-align:left;"> $AAPL pumping in the am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:27:07 </td>
   <td style="text-align:left;"> $AAPL   🍏 Free Thought Bubble:  If you think “Meta’s” Earnings are going to cause WallSt, Tutes, &amp;amp; Sovereigns to “Sell Apple” tomorrow,  you are a novice trading lamb, waiting to be shorn.  Old trading axiom, “never be fleeced by thine own self”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:26:11 </td>
   <td style="text-align:left;"> last 4 weeks or so runners: 

10,000% (Moonrock alt coin) 
5,200% (BankersDream alt coin) 
2,400% $PYPL puts 
1,300% $BSFC 
250%~ $AAPL calls 
120% $ONE.X (harmony)
$bbig 85% rinse swings 
mdia tapped 75% so far, but still holding for another 50%+ on top of current price
And ofc NINE holding full bc I believe still will pull a move like my CEI/GBR play, although I know some people who got the lucky chance to enter in the .80s and ride it to 1.40s already

Not too bad for someone who runs a completely free platform and shows full transparency and blueprint to every ticker chart set up

 (post my alerts first on discord *free link in bio* where I also post DAILY updates on my plays each night so you’re always up to date)

Paying for paid programs to follow someone’s tickers is NOT going to help you become successful. Trust me. These fuckers don’t care about you except for bringing more cash to their pockets

Commons, options, crypto, alt coins.. nobody else does it like this for free </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:25:49 </td>
   <td style="text-align:left;"> $AAPL https://stocks.apple.com/AcvrZBjqyQxS9mlPC_hrMNw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:25:04 </td>
   <td style="text-align:left;"> $AAPL another buying opportunity or put selling time.  May sell the $175 Feb 11 puts at $4/ contract. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:24:18 </td>
   <td style="text-align:left;"> $AAPL I’m gonna need this 165 by Friday can u sellers make it happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:23:58 </td>
   <td style="text-align:left;"> $FB  CFO Dave Wehner said $AAPL iOS privacy changes will cost Facebook about $10 billion in ad revenue this year. Wow. 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:23:46 </td>
   <td style="text-align:left;"> $AAPL 2$2$22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:22:15 </td>
   <td style="text-align:left;"> $AAPL Who buying Apple near the 52 week high during a major pullback 💋💋💋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:21:05 </td>
   <td style="text-align:left;"> Apple (NASDAQ:  $AAPL) Knocks It Out Of The Park https://www.billionaireclubcollc.com/apple-nasdaq-aapl-knocks-it-out-of-the-park/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:19:39 </td>
   <td style="text-align:left;"> $AAPL buying calls after 8am tomorrow I think see how bad damage is from fuck book </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:17:49 </td>
   <td style="text-align:left;"> Facebook&amp;#39;s Dismal Outlook—and What It Means for Social Media&amp;#39;s Future  $FB $AAPL $SNAP $TTD 

https://newsfilter.io/a/afbb9cbc95c6f1d68693f85a8ff52f69 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:17:11 </td>
   <td style="text-align:left;"> $AAPL $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:17:07 </td>
   <td style="text-align:left;"> $AAPL Bears right now with puts ending Friday lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:17:01 </td>
   <td style="text-align:left;"> #Apple Stock Could Push Higher $AAPL https://talkmarkets.com/content/stocks--equities/apple-stock-could-push-higher?post=342571 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:15:53 </td>
   <td style="text-align:left;"> $AAPL 🤣🤣🤣you brain dead idiots please explain how your dumb logic said let’s sell apple because fb missed 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤑🤑🤑🤑🤑🤑🤑🤑🍎🍎🍎🍎IDIOTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:13:45 </td>
   <td style="text-align:left;"> $AAPL 166 in a jiffy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:11:07 </td>
   <td style="text-align:left;"> $AAPL 

Aww - bears you better not to get overexcited ..

This is a bear trap too …

I won’t tell you why and how .. you will be surprised how it turns out tomorrow EOD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:10:50 </td>
   <td style="text-align:left;"> $AAPL This Friday is ex-div? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:09:45 </td>
   <td style="text-align:left;"> $tsla $qqq $aapl $btc.x https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:09:15 </td>
   <td style="text-align:left;"> $AAPL $167.5p for Friday gunna print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:09:12 </td>
   <td style="text-align:left;"> $AAPL warning big dip ahead, $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:07:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Judge dismisses lawsuit over Apple iPhone water resistance claims https://www.stck.pro/news/AAPL/22415846 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:06:50 </td>
   <td style="text-align:left;"> $AAPL so meta officially crashed all mkt? Is that even legal? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:06:15 </td>
   <td style="text-align:left;"> $AAPL People have short memory, less than a week ago this stock was $158.00 ,Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:06:00 </td>
   <td style="text-align:left;"> $AAPL what we looking at Friday? 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:04:13 </td>
   <td style="text-align:left;"> $SAND.X $RNDR.X $FB $WMG 
Shake out the weak stomachs....

Good enough for the big brands like Warner Music &amp;amp; Adidas and they dnt come any bigger than $AAPL  investing in the Metaverse. Its good enough for me 

https://www.fool.com/investing/2022/02/02/apple-ceo-tim-cook-metaverse-interested/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:04:03 </td>
   <td style="text-align:left;"> $AAPL WILL DROP TO 150! SO MAR PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:03:52 </td>
   <td style="text-align:left;"> $AAPL let this shit company drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:03:09 </td>
   <td style="text-align:left;"> $AAPL I see AH volume as 20, 000. Can anyone confirm that. If so that is way too low </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:01:59 </td>
   <td style="text-align:left;"> $AAPL it always happens AH, when you cant do anything about it. Cant swing weekly options in this market. We&amp;#39;ll see what tomorrow brings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:01:48 </td>
   <td style="text-align:left;"> $AAPL byebye </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:01:15 </td>
   <td style="text-align:left;"> $AAPL should we erase the ER move? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:01:15 </td>
   <td style="text-align:left;"> $AAPL the 🍏 will become 🍎 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:00:53 </td>
   <td style="text-align:left;"> $AAPL fb is playing on our price for sure, I believe we will go down the next few days, but will recover next week.  For now I’m out and neutral and just watching. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:00:46 </td>
   <td style="text-align:left;"> $FB $AAPL $GOOG $AMZN $NFLX  
 
FB may have just triggered the next leg down in the overall markets... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:00:22 </td>
   <td style="text-align:left;"> $AAPL Bears bringing out all their predictable moves tonight…for a 1% AH drop 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 08:00:21 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOGL $FB Futures are going crazy Ruby Red. Down 360. Oh Boy definitely taking the elevator on the way down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:59:56 </td>
   <td style="text-align:left;"> $AAPL 🤔🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:59:05 </td>
   <td style="text-align:left;"> $AAPL wow tomorrow going to be blood bath! I’m getting killed after hours in all my stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:59:00 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #3 ticker with sweep activity where institutions are trading options urgently with 47.1K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:58:21 </td>
   <td style="text-align:left;"> $AAPL it’s bearish now by association </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:56:08 </td>
   <td style="text-align:left;"> $AAPL  🍏  AH’s Volume is crazy, ~13 Million.  Don’t trade scared, trade smart!  Trade Pro, not novice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:55:32 </td>
   <td style="text-align:left;"> $FB apple is next. Wait for it  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:54:07 </td>
   <td style="text-align:left;"> $FB earning clearly shows how shitty zuck is comparing to $AAPL and $GOOGL . Don’t buy $FB ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:52:49 </td>
   <td style="text-align:left;"> $AAPL no reason why this is down. The king is the reason why FB is down so they can’t be tracking and running algorithms on us all day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:52:31 </td>
   <td style="text-align:left;"> $AAPL $MSFT $AMD these are the only trusted stocks in this market. They print big time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:52:17 </td>
   <td style="text-align:left;"> $AAPL WTF does FB got to do with 🍏. We making huge money here. We shouldn&amp;#39;t be suffering AHrs because of that shit! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:51:50 </td>
   <td style="text-align:left;"> $AAPL Tomorrow J.Daddy Bank Bucks need  to face the nation.🇺🇲0.0005% .. $FB $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:50:50 </td>
   <td style="text-align:left;"> $AAPL   🍏👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:50:32 </td>
   <td style="text-align:left;"> $AAPL NEWS - AAPL Reports First Quarter Results: 
https://www.youtube.com/watch?v=B2e7yheNg_E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:49:22 </td>
   <td style="text-align:left;"> $COST We can prove a lot tomorrow on where capital goes to first when the $FB ER market selloff bottoms out, no one has any idea what will happen at the open, my guess is a TON of $FB put profit taking will make it super volatile in the morning, and the entire tech sector although it will have a nasty open, will not be discounted based on $FB and there ridiculous 2022 spend plans.  

I’m buying some $AMD when the hysteria is peaked this week to get a nice discount on quality that had great earnings.  

Same goes for $AAPL if we really get knocked—I love them both, have traded them, but was looking at good fresh entries.  

With fear and volatility comes true value.  Bring it 🤘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:48:52 </td>
   <td style="text-align:left;"> $AAPL 172.50 held all day yesterday, going get interesting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:46:04 </td>
   <td style="text-align:left;"> $AAPL what did I say…? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:45:00 </td>
   <td style="text-align:left;"> $AAPL: Both the short term and long term trends are positive. This is a very positive sign. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:44:30 </td>
   <td style="text-align:left;"> $AAPL thank you $FB for a dip to buy 🤩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:43:24 </td>
   <td style="text-align:left;"> $AAPL LOAD UP! $$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:41:27 </td>
   <td style="text-align:left;"> $AAPL $FB $QQQ How many billions did Zuckerberg lose today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:40:26 </td>
   <td style="text-align:left;"> $SPY In Florida, Gynecologists have the highest average paying salary. $FB $SNAP $AAPL $SPOT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:39:43 </td>
   <td style="text-align:left;"> $AAPL How many Clown brought into the hype? BUY HIGH the Sell LOWER $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:38:51 </td>
   <td style="text-align:left;"> $AAPL  the good old days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:37:01 </td>
   <td style="text-align:left;"> Is $BEZOGE.X going to be #Shiba2.0 ??? I think so. So does Sir Swifty!!  Let’s dive into it right here: https://youtu.be/tY5jQS6VCjY $AXS.X $SHIB.X $BTC.X $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:36:59 </td>
   <td style="text-align:left;"> $SPY $AAPL saved us and $FB killed us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:33:08 </td>
   <td style="text-align:left;"> $AAPL only apple maintains the market atm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:29:11 </td>
   <td style="text-align:left;"> $AAPL How in the Heil did The METAVERSE $FB  fail..this will wreak havoc in the S&amp;amp;P </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:28:52 </td>
   <td style="text-align:left;"> $FB holy shit. How many people do you think went all in on calls after $MSFT, $AAPL, and $GOOGL beats. Absolutely wild couple weeks around here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:28:38 </td>
   <td style="text-align:left;"> $AAPL how many times do y’all have to get bitch slapped off 175 before you give up 😂 market is going down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:28:22 </td>
   <td style="text-align:left;"> $AAPL This is great ah buying opp here! $$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:27:44 </td>
   <td style="text-align:left;"> $FB $AMZN $AAPL top 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:27:03 </td>
   <td style="text-align:left;"> $AMZN adding calls as only $FB out of the big 5 is not doing good  $MSFT $AAPL $GOOGL are up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:25:08 </td>
   <td style="text-align:left;"> $AAPL I want this at 80.

Am I hoping for too much or smoking too much WEED? 💨🚬🌿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:23:25 </td>
   <td style="text-align:left;"> $FB Seems Mark has no place to go $AAPL is going to eat it away... Mark is trying to rush for Metaverse Ultimate Failure !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:22:10 </td>
   <td style="text-align:left;"> $AAPL aapl will come in clutch tomorrow 🍏🔥 fb gonna learn what real gains are </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:22:04 </td>
   <td style="text-align:left;"> $XELA , The BEST PENNY STOCK loves $SPOT $AAPL $AMZN $TSLA  Join us to squeeze shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:19:37 </td>
   <td style="text-align:left;"> $GOOG $aapl $msft not expecting the market leaders who already reported blowout earnings to be strongly affected by a declining social media stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:19:10 </td>
   <td style="text-align:left;"> $FB $AMD $NVDA $SPY $AAPL 
Mr. wonderful bought facebook ahead of ER report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:15:57 </td>
   <td style="text-align:left;"> $AAPL   Swine

https://www.businessinsider.com/apple-china-suppliers-uyghur-muslims-forced-labor-report-2021-5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:15:37 </td>
   <td style="text-align:left;"> $AAPL This is the alternate count if we sell harder tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:12:51 </td>
   <td style="text-align:left;"> $AAPL Tonight $FB is sleepless in the NASDAQ, tomorrow Apple may bleed OUT  the ASK.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:12:10 </td>
   <td style="text-align:left;"> Top Flow for the Week 🔥: $AAPL with a single CALL Trade for total premium worth $393.2K Ranking #106 the Week | This was a SWEEP trade.  | Visit SweepCast.com or Join our Premium Room For Access! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:12:03 </td>
   <td style="text-align:left;"> $GOOG $AAPL $MSFT $NVDA are the money makers $$$ buy and hold for future wealth 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:09:06 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-02 Daily Forecast Video: 
https://www.youtube.com/watch?v=0Wx1zWnY54U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:08:29 </td>
   <td style="text-align:left;"> $FB $AAPL This little nugget from the facedud release is why AAPL is going to truck well into the 200s this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:05:22 </td>
   <td style="text-align:left;"> latex4888c242f5aea47a4766fc00d85ec676AMZN earning Tomrorow and important  
$FB  ? who cares  
What a overreaction sell off with Market Nasdaq !! If it was AAPL I would say maybe !! but FB ? No </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:03:27 </td>
   <td style="text-align:left;"> $FB Facebook had this coming and they deserve it. Data will not be free in the future as crypto becomes more decentralized. P.S Meta was dead on arrival! Crypto/Metaverse community was never going hand it over to Facebook🖕. Hats off to $AAPL - They don’t owe Facebook anything - Protecting the users data is blessing - What you do online is your business! $MANA.X $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:03:10 </td>
   <td style="text-align:left;"> is it better to be under the government&amp;#39;s thumb like BABA or under god&amp;#39;s thumb like $FB  $AAPL $BABA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:02:44 </td>
   <td style="text-align:left;"> $AAPL my only hope for tomorrow is $f .. I hope they blow the earnings to the moon and take the stock back to $25.00.. i hope $baba majes a reversal back to $125.00.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 07:01:39 </td>
   <td style="text-align:left;"> $AAPL Higher highs and higher lows. Still near term bullish. Looking for higher after a quick pullback tomorrow AM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:59:07 </td>
   <td style="text-align:left;"> $amd $spy $tqqq $aapl $uvxy   
 
Highly recommended! It&amp;#39;s free joining. 👇https://unlimitedtraderscomm.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:58:57 </td>
   <td style="text-align:left;"> $FB $AAPL $AMZN $NFLX $GOOG 
Ever wonders why they actually are called the FAANG? 
Because their leaders are part of a group of elite human-alien hybrids that’s feed off the blood of newborns to enrich themselves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:58:52 </td>
   <td style="text-align:left;"> $AAPL looks like a blood bath already .. $aapl $baba .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:58:51 </td>
   <td style="text-align:left;"> $AAPL  🍏 Zuckerberg’s MetaVerse:  Zuckerberg, dressed up Models as “Avatars”, placed them in a greenfield backdrop, and changed Facebook’s name to Meta.  It was pure theater.  It was “dress-up &amp;amp; pretend”.  Apple, doesn’t play dress- up.  And, AAPL doesn’t play pretend.  AAPL, brings real Products to Mkt and dominates the “space”.  AAPL, will SOON release it’s AR/VR/AI Computerized IoT fully Connected Goggles/Glasses/&amp;amp; a “Secret Product”.  These Products, will change the World…how we work, play, &amp;amp; live.  The Products, will be “Pure Apple”…and they will dominate.  Apple, doesn’t play pretend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:58:50 </td>
   <td style="text-align:left;"> $AAPL nothing to see here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:58:28 </td>
   <td style="text-align:left;"> $AAPL $FB  This was a perfect setup, Buy the BIGGEST dippers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:56:24 </td>
   <td style="text-align:left;"> $AAPL $FB $AMZN $GOOG $NFLX  
 
FB&amp;#39;s slowing growth should come as no surprise because at some point, these multitrillion dollar market cap tech behemoths will experience slower growth simply due to the effect of large numbers. Over the past 20 years, these tech companies have enjoyed double and even triple percentage growth rates because their user bases are still unsaturated and not fully penetrated. This is no longer the case.  
 
Now, most of FB&amp;#39;s potential user base are already using FB, most people who can buy iphones already have one or several, most people who will sign up for Prime already have done so . In the coming decade, unless these tech giants can come up with new revenue streams/levers to pull, they will inevitably experience slower growth and combined with rising interest rates, slowing economies, chickens are coming home to roost.  
 
Be careful out there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:55:55 </td>
   <td style="text-align:left;"> $FB probably getting wiped out once more when $AAPL releases the AR glasses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:55:19 </td>
   <td style="text-align:left;"> $SPY Relax, it’s just 1 meta fkd company!. Not the whole Tech. $MSFT $AAPL $GOOG .. etc did just fine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:55:02 </td>
   <td style="text-align:left;"> $AAPL I need 179 by the end of the week plz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:53:19 </td>
   <td style="text-align:left;"> $AAPL red apple tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:53:15 </td>
   <td style="text-align:left;"> $AAPL Interesting idea! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:53:10 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $177.5 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:53:03 </td>
   <td style="text-align:left;"> $AAPL Facebook $FB  and Apple are birds of A  feather..  $TSLA $$TWLO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:53:03 </td>
   <td style="text-align:left;"> $AAPL Apple is not immune to this sell off …. Hope they don’t ever miss …… cos Wallstreet is very ruthless . That show no mercy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:52:46 </td>
   <td style="text-align:left;"> $AAPL $GOOG $AMZN $FB $QQQ   The market is F’ed tomorrow. Hope you sold today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:51:22 </td>
   <td style="text-align:left;"> $AAPL deep red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:49:59 </td>
   <td style="text-align:left;"> $MSFT - $AAPL 

Red to green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:49:16 </td>
   <td style="text-align:left;"> $FB Meta CFO Dave Wehner basically confirms to $AAPL iOS changes hammering Facebook&amp;#39;s ads revenue in commerce while buoying $GOOGL search ads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:49:06 </td>
   <td style="text-align:left;"> $AAPL 
So not providing guidance has allowed the 🍎 to bypass the destruction and maintain lofty levels while the ones that speak to the future outlook get nut kicked… 
I like the 🍏 for the premium selling and the beast it is, but hovering under and tickling 175 is not a very good place to buying shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:47:49 </td>
   <td style="text-align:left;"> Is Social Media Fading? Meta&amp;#39;s Weak Outlook Raises Tough Questions  $FB $AAPL $SNAP $TTD 

https://newsfilter.io/a/5bf9bcd84b2f912987d4f582d5231cb0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:44:48 </td>
   <td style="text-align:left;"> $AAPL stop loss triggers will happen tomorrow. That’s what happens when PC ratio is so low. So many stop loss orders just ready to be triggered. Thanks Facebook </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:44:32 </td>
   <td style="text-align:left;"> $AMZN - of FAANGM stocks,  $AAPL $GOOG $MSFT had great ERs, $FB and NFLX had bad ERs, so the final batter is AMZN tomorrow. Naz needs an AMZN ER grand slam. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:43:54 </td>
   <td style="text-align:left;"> $AAPL allllll those stop losses set for the call options and stock purchases are gonna trigger tomorrow and drop apple a couple dollars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:42:14 </td>
   <td style="text-align:left;"> $FB got fked hard by $AAPL thats end of story. But the good thing is they have started looking for other growth engine, also going forward as business come online and operate at optimal lvl&amp;#39;s the ad&amp;#39;s spend $$ will inc too so this drop is major over reaction and will be short lived as inst will gobble up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:41:10 </td>
   <td style="text-align:left;"> $AAPL  Looking for sub 170 soon. Maybe we get that tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:40:46 </td>
   <td style="text-align:left;"> $AAPL Thank for FB move Apple will be still get cheaper buyback price for its daily buyback. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:39:53 </td>
   <td style="text-align:left;"> $tsla $aapl $btc.x https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:38:57 </td>
   <td style="text-align:left;"> $qqq $spy $fb $aapl $amzn https://www.youtube.com/watch?v=JZ63GccJBAY&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:38:06 </td>
   <td style="text-align:left;"> $AAPL What a difference between company that cares about people and privacy VS $FB that cares about how to get free information from unsuspecting people and sell it to best bidder including Russia! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:36:59 </td>
   <td style="text-align:left;"> $pins $penn $aapl    
Highly recommended! It&amp;#39;s free joining. https://unlimitedtraderscomm.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:36:54 </td>
   <td style="text-align:left;"> $AAPL we’re down AH because of Facebook? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:35:17 </td>
   <td style="text-align:left;"> $AAPL $170...? Maybe? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:33:18 </td>
   <td style="text-align:left;"> $AAPL Facebook earnings...

Oh yes, another great reason for those tossers on Wall St to drag your shares down by 5 - 10% again tomorrow...!!!

Don&amp;#39;t they just love it... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:33:16 </td>
   <td style="text-align:left;"> Unusual Options Activity: $AAPL is the #9 ticker with unusual activity from institutional traders with an average of 20% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:30:55 </td>
   <td style="text-align:left;"> $aapl is so impressive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:28:26 </td>
   <td style="text-align:left;"> $AAPL $FB $MSFT - It&amp;#39;s all fine. The Fed will make up the losses with that good ol&amp;#39; reliable QE heroine. Look at stocks at 2:42, look at that injection. Insane how the Fed is fighting sellers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:25:31 </td>
   <td style="text-align:left;"> $AAPL how can you dis Apple, after there terrific results and outlook !! An after these other companies results .. hey peeps don&amp;#39;t forget we make and sell stuff!! Great products and services , this is tough to go against ,buy what you know and USE!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:22:43 </td>
   <td style="text-align:left;"> $AAPL I need to get off STs cuz I&amp;#39;m really tired of these FB bag holders tagging apple. Does anyone even USE FB anymore?!? 🤷🏽  
 
I totally agree with bearkiller5308. Good luck tomorrow and prepare for the flies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:21:40 </td>
   <td style="text-align:left;"> $AAPL you can say and do whatever makes you feel better but still a bit more pain til skies are clear. Longs are fine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:21:31 </td>
   <td style="text-align:left;"> $PLTR those who are fear mongering &amp;amp; feel so certain let them buy big straddle or even outright PUT, why not make big money on certainty ..lol $PLTR has its own crash course when others misses ($FB) or beat ( $AAPL ). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:21:07 </td>
   <td style="text-align:left;"> $AAPL selling your shares to apple and Buffett 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:19:30 </td>
   <td style="text-align:left;"> $AAPL $fb is case in point why &amp;quot;Just buy and Hold&amp;quot; is absolute BS. Traders stay winning. Holders taking Ls from July &amp;#39;20 to Feb &amp;#39;22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:18:39 </td>
   <td style="text-align:left;"> $AAPL had bounced strong within our blue box - seems like Apple is completing an impulse wave within the near-term future. #elliottwave #forex #trading #FXsignals #pips #forexsignals #tradingsignals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:17:32 </td>
   <td style="text-align:left;"> $MSFT - $AAPL - $NVDA 

Red to green move tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:16:14 </td>
   <td style="text-align:left;"> $AAPL I can’t figure out why this is down at all. Based on FB results . It should be up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:16:01 </td>
   <td style="text-align:left;"> $AAPL fuck Facebook! This is Apple 🍎! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:15:47 </td>
   <td style="text-align:left;"> $AAPL $$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:14:51 </td>
   <td style="text-align:left;"> Whole market gonna be crashing soon. $FB $AAPL $TSLA $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:14:35 </td>
   <td style="text-align:left;"> $AAPL Let it sink in that the market has been a dumpster fire, and yet clowns come in here to short/put buy/bash the greatest company on the planet, which is barely 1% down from its ATH. I will buy every fucking $AAPL dip like my portfolio depends on it and I&amp;#39;ll sleep so well at night doing it 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:13:40 </td>
   <td style="text-align:left;"> $FB the problem is everyone hates Facebook but so many of those people are hypocrites and use it or Instagram.

Young millenials and Gen Z are the biggest hypocritical generations I’ve ever seen.

All this fake wokeness yet their lives revolve around their $AAPL phone and social media.

If FB didn’t have so much hate Metaverse would be a windfall. But everyone is against them and I don’t want a metaverse world either. SAD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:13:23 </td>
   <td style="text-align:left;"> $CFVI $FB $GOOG $AAPL DAMN pt 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:13:00 </td>
   <td style="text-align:left;"> $AAPL meta money coming in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:12:49 </td>
   <td style="text-align:left;"> $CFVI $GOOG $AAPL $FB DAMN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:11:07 </td>
   <td style="text-align:left;"> $AAPL we seeing $160 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:10:47 </td>
   <td style="text-align:left;"> $AAPL y’all saw that big buy 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:10:23 </td>
   <td style="text-align:left;"> $AAPL when dumb are selling lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:07:55 </td>
   <td style="text-align:left;"> Remember how $fb &amp;#39;s Zuck wanted to make $aapl hurt ? Most of you wont because you are new to the beef and have forgotten, but turns out all the suckerburg had to do was tank his own stock by 20% xD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:07:07 </td>
   <td style="text-align:left;"> $AAPL wake up it’s back up and on it’s way to 180 Apple finna carry the market to catch up the slack fb dropped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:06:31 </td>
   <td style="text-align:left;"> $FB Thanks Zuck for giving me a chance to buy more $AAPL and $GOOGL tomorrow on the weakness. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:05:38 </td>
   <td style="text-align:left;"> $AAPL really starting to think sells are being delayed to fall all at once.  Manipulation at its finest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:04:55 </td>
   <td style="text-align:left;"> $UTME can be next $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:04:44 </td>
   <td style="text-align:left;"> $AAPL It&amp;#39;s on the tape, still confused as to the price difference though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:04:38 </td>
   <td style="text-align:left;"> $AAPL if I were in FB I’d dump it and be piling into Apple now. It’s in its own league. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:04:22 </td>
   <td style="text-align:left;"> $UTME is my next $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:03:37 </td>
   <td style="text-align:left;"> $AAPL everyone is waiting for dividends to hit their account and then we’ll see what it’s really made of. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:03:14 </td>
   <td style="text-align:left;"> $UTME is like $AAPL at 1980 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:02:17 </td>
   <td style="text-align:left;"> $AAPL 
WTF Facebook earnings have to do with Apple? Only idiots are selling Apple on this base 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:01:39 </td>
   <td style="text-align:left;"> $FB $AAPL needs to be split up, it is the most corrupt company in the History if the world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 06:00:15 </td>
   <td style="text-align:left;"> $AAPL will be green in the morning looks strong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:59:37 </td>
   <td style="text-align:left;"> $SPY $QQQ Well in my opinion $GOOGL and $AAPL are much better indicators on how the US economy is doing than $FB does, $AAPL is especially a good one to judge how well the US consumers are doing. Whether people are spending less time on Facebook or Instagram isn&amp;#39;t that good of an indicator of how well the US economy is doing, maybe people are just spending more time outdoor now with COVID fading away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:58:55 </td>
   <td style="text-align:left;"> $AAPL Apple didn&amp;#39;t give guidance for a reason, everyone knows why now. Good luck bulls, chip shortages are going to kick everyone&amp;#39;s asses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:58:08 </td>
   <td style="text-align:left;"> $AAPL prob between 170-180 for months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:57:13 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $msft $AAPL   Stick with ATM.  - Apple, tesla and Microsoft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:55:59 </td>
   <td style="text-align:left;"> $MSFT 
Initial reaction from $FB is usually the wrong one. Money pouring into Microsoft $AMD $GOOGL $AAPL . Watch and learn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:53:24 </td>
   <td style="text-align:left;"> $AAPL   🍏 Wayyyy too many “Shills” &amp;amp; “Meme Equivalent Traders”, posting misinformation and novice positioning.  No need to offer Pro Advice, these Posters posting Bearish, don’t “read other Trader’s Posts”.  Deep Think, continue to trade smarter.  AAPL, is it’s own Asset Class.  AAPL, is Alpha.  Breathe, through the noise.   🧘🧘‍♀️ Om. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:51:05 </td>
   <td style="text-align:left;"> $AAPL FB going put a hurt on the whole mkt... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:50:44 </td>
   <td style="text-align:left;"> $AAPL aapl is cash rich 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:49:13 </td>
   <td style="text-align:left;"> $FB 10 MILLION DOWN THE DRAIN! 👎

All these people are going to lose a lot of money, they probably thought the tech ERs would continue to be excellent after $AAPL. Just another case of staying away from ER being a good idea. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:47:39 </td>
   <td style="text-align:left;"> $AAPL This is why you invest in Apple! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:47:39 </td>
   <td style="text-align:left;"> $AAPL strength of a monster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:46:42 </td>
   <td style="text-align:left;"> $AAPL bears I will show you fear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:45:44 </td>
   <td style="text-align:left;"> $AAPL creepin’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:45:34 </td>
   <td style="text-align:left;"> $AAPL  Have a great night everyone!!!!!! Proverbs 21:2 ….Every way of a man is right in his own eyes, but the LORD weighs the heart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:44:22 </td>
   <td style="text-align:left;"> $AAPL it’s gonna pump they had to give bears some hopium lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:44:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $AAPL is 7.00. This indicates good health for $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:43:30 </td>
   <td style="text-align:left;"> $F $sofi  they have nothing to do with $fb so great buy opportunity AH !!! 
$goog $aapl already beat earning ; Fb always worst one ; also under 250 is great swing Fb anyway .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:43:15 </td>
   <td style="text-align:left;"> $aapl watchlist of 38 names.. all fucked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:42:52 </td>
   <td style="text-align:left;"> $AAPL Stocks were ripping today. Simulated Weekly $177.5 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:42:03 </td>
   <td style="text-align:left;"> $QQQ $AAPL and $MSFT only things holding this up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:42:02 </td>
   <td style="text-align:left;"> $AMZN  ER tomorrow
Problem: 👉 Higher Labor costs

We saw this with retailers like McDonald&amp;#39;s (MCD) and Starbucks (SBUX) and even in banks like Goldman Sachs (GS). Amazon is one of the largest private employers in the world - employing over a million people. There&amp;#39;s been plenty of ink spilled over Amazon workers&amp;#39; attempts to form labor unions, but even companies that don&amp;#39;t have to deal with unions are facing labor cost pressure. Amazon is vulnerable to these sorts of pressures 

$AAPL $SPY $TSLA $TQQQ 
https://www.google.com/amp/s/seekingalpha.com/amp/article/4483568-amazon-earnings-preview-key-drivers-to-watch-for </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:41:09 </td>
   <td style="text-align:left;"> $PLTR tech is not all fallen guys, $NFLX $FB vs $AAPL! Recent correction has ensured $PLTR ER will be no action (if miss) and little upside &amp;amp; slow uptrend if beat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:40:24 </td>
   <td style="text-align:left;"> $AAPL tim cook is a liar. everyone admits supply chain issues, except for apple. their supply all comes from china. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:39:29 </td>
   <td style="text-align:left;"> $AAPL glad I have puts for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:38:35 </td>
   <td style="text-align:left;"> $AAPL $GOOG $AMD had great earnings ; $FB is mean-less to me !! .. $amzn is bigger deal for tomorrow  AH earning .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:38:27 </td>
   <td style="text-align:left;"> $AAPL Look like TIM was waiting for $FB earning release to set the price of apple stock..IMHO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:37:11 </td>
   <td style="text-align:left;"> $AAPL beautiful defensive stock y’all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:36:48 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 545.7K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:36:21 </td>
   <td style="text-align:left;"> $AAPL Tim Apple is god. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:35:52 </td>
   <td style="text-align:left;"> $AMZN  what is the point of posting this if the real earnings is tomorrow.  Hedge funds are scaring y’all to buy cheaper. I am holding mines. $FB $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:35:18 </td>
   <td style="text-align:left;"> $SNAP $FB Apple is fucking us over with these changes $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:35:12 </td>
   <td style="text-align:left;"> $AAPL  🍏 AAPL…”The Equity”, that is the “must own Stock” in every WallSt, Tute &amp;amp; Sovereign’s Portfolio.  AAPL is pure Alpha.  March Qtr Guidance is “Outstanding”.  Analysts not only raised their Price Targets…but, also “immediately” upon the Earnings Release, raised EPS for the upcoming Mar Qtr based on “Tip off “ from Company Guide. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:35:10 </td>
   <td style="text-align:left;"> $AAPL why. They just set an earnings record. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:35:08 </td>
   <td style="text-align:left;"> $FB Fuck it I&amp;#39;m dumping all my bezos bags for $CLOV prolly rotate over some of my $AAPL they are next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:34:52 </td>
   <td style="text-align:left;"> $FB $AMZN $AAPL $SPY Hope Amazon drops 20% tomorrow so I can add little of that to the retirement account as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:34:39 </td>
   <td style="text-align:left;"> $AAPL FB’s drop will not affect apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:34:30 </td>
   <td style="text-align:left;"> $AAPL definitely this is going under $$160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:34:16 </td>
   <td style="text-align:left;"> $AAPL tech futures took a heavy shit just now. 190+ points lost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:33:58 </td>
   <td style="text-align:left;"> $AAPL nighty night! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:33:45 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB Apple giveth and Facebook taketh away 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:33:09 </td>
   <td style="text-align:left;"> $AMZN = Definitely no beat &amp;amp; lower guidance for increase warehouse workers pays due to inflation

FYI: $TQQQ $SPY $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:32:53 </td>
   <td style="text-align:left;"> $AAPL it was a nice day
👁❤️🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:32:41 </td>
   <td style="text-align:left;"> $FB There&amp;#39;s a certain pride in owning Apple stock, just like their phones and MacBooks. Just park your money in $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:32:38 </td>
   <td style="text-align:left;"> $FB $AAPL  F***** them with their add opt in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:32:08 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-02 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=H0zuPqhBSBc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:32:03 </td>
   <td style="text-align:left;"> $AAPL 

Oh I see FB made a huge misses .. blaming on AAPL..

Actually, FB doesn’t have any new strategies to prevent any losses. 

The drop in AH is to allow FB stockholders to roll over and rotate to AAPL.. further more accumulation warranted !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:31:13 </td>
   <td style="text-align:left;"> $AAPL in reality I don’t care if $fb goes belly up and shuts down for good, only problem is tomorrow it’s going to drag the market down with it.. $baba abd $aapl were already struggling today., </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:31:07 </td>
   <td style="text-align:left;"> $AAPL $FB  Missed opportunity..SMFH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:30:54 </td>
   <td style="text-align:left;"> $AAPL &amp;amp; $GOOGL save the markets then $FB does a rug pull, reminds me of Ruth of Ozark 😂😂😂

This is why I stick with day trading during these times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:29:27 </td>
   <td style="text-align:left;"> $QQQ $SPY 
$AAPL $MSFT 

How long the algos pull the plug on apple and Msft 
Only matter of time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:29:15 </td>
   <td style="text-align:left;"> $AAPL $tsla below 900 is a bear bell for the entire market smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:28:45 </td>
   <td style="text-align:left;"> $Aapl $GOOG saved mkt to go below 
SPY $400
now FB gone
If $AMZN pukes tomorrow then $SPY 400 is back on the table now
Not Feeling Good about AMZN ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:28:36 </td>
   <td style="text-align:left;"> $AAPL FAANG is not in trouble. FB and Netflix are in trouble. APPLE just had record earnings and investors should flock to Apple from FB. Zuckerberg is a little boy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:28:27 </td>
   <td style="text-align:left;"> $SPY $AMZN $AAPL $FB $TSLA 
Jan: 14% SPY drop for rate hike
Mar: 25-30% drop fo Recession

A curve inversion, particularly the one determined by comparing two-year and 10-year Treasury bonds, has in the past presaged recessions, as the market priced in expected rate cuts based on possible monetary policy actions that could damage the economy.

https://wsau.com/2022/02/02/u-s-yield-curve-inversion-may-be-false-positive-recession-signal-credit-suisse/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:28:22 </td>
   <td style="text-align:left;"> $SNAP yup $AAPL royally F***** them 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:28:02 </td>
   <td style="text-align:left;"> $AAPL tmr morning is buy buy buy time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:28:02 </td>
   <td style="text-align:left;"> $FB miss is due to $AAPL privacy policies. It’s not related to the Metaverse. In fact, it’s probably why they are spending billions to grow the Metaverse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:27:06 </td>
   <td style="text-align:left;"> $AAPL first timer here with Apple. Is this AH volume higher than usual? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:26:39 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:26:34 </td>
   <td style="text-align:left;"> $FB $AMZN $AAPL $NFLX $GOOG
FAANG is in trouble… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:26:22 </td>
   <td style="text-align:left;"> $FB That metaverse stuff was to help investors forget about the $aapl headwind </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:26:12 </td>
   <td style="text-align:left;"> $AAPL broke tracking for everyone. Huge ramifications. $FB $SHOP $SNAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:25:27 </td>
   <td style="text-align:left;"> $AAPL  &amp;quot;Oh SPY fell?  K&amp;quot;  - AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:25:07 </td>
   <td style="text-align:left;"> $AAPL $160 eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:24:57 </td>
   <td style="text-align:left;"> $SPY $QQQ the only thing that is bullish and is holding is $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:24:44 </td>
   <td style="text-align:left;"> $SPOT $SPY $QQQ  $AAPL 
Spotify (like)
or
Apple Music (comment) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:23:54 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/UU_4xfd0Xh0 .05 on the day is better than 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:23:02 </td>
   <td style="text-align:left;"> $AAPL 162.50 short term , short every rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:22:21 </td>
   <td style="text-align:left;"> $AAPL We have been forecasting AAPL to decline into the blue box and bounce higher in mid January.  The bounce now is strong enough where either a new cycle higher has started, or the instrument will decide to do the double.  We are looking for further extension higher as the preferred scenario at this point.  Members who bought the blue box have already taken partial profits..   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:22:18 </td>
   <td style="text-align:left;"> $AAPL supply chain issues are a huge factor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:22:06 </td>
   <td style="text-align:left;"> $AAPL I feel like anyone who has good earnings is going to be good for us.  If the major players on the S&amp;amp;P have good earnings it will break the bubble thesis and pull more money into the whole market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:22:05 </td>
   <td style="text-align:left;"> $AAPL $150 is where I’d consider covering / going long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:21:53 </td>
   <td style="text-align:left;"> $AAPL $135 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:21:34 </td>
   <td style="text-align:left;"> $AAPL FB shit performance will boost Apple. Apple is a real company with seasoned, competent management. Facebook is run by a boy who grew up playing video games in Mom’s basement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:21:16 </td>
   <td style="text-align:left;"> $SPY  Was riding the $AAPL earnings wave like everything is fine. Everything is fine with $AAPL but not much else. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:21:07 </td>
   <td style="text-align:left;"> $AAPL and to think everyone feared the Apple ER miss will crash the markets.. $spy $dji $fb $msft  
Which it would have lol. But Apple is bae. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:20:54 </td>
   <td style="text-align:left;"> $AAPL killing $FB quite easily actually. Those new ad controls must make zuccc upset </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:20:27 </td>
   <td style="text-align:left;"> $AAPL will be up in the am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:20:02 </td>
   <td style="text-align:left;"> Man when Chamath said go long $MSFT and $GOOGL and short $FB and $AAPL  ....he was at least half correct. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:19:55 </td>
   <td style="text-align:left;"> $SPY will be back up, over reaction to $FB er, it was expected, with AD tracking gone on $AAPL and lower engagement on facebook. They know this too warned ahead too with Metaverse play. $FB needs a sideways action before metaverse growth engine shows someprogress or find new ways to fingerprint users. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:19:46 </td>
   <td style="text-align:left;"> $AAPL $GOOGL these are the names to own next few months, let&amp;#39;s see what $AMZN does tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:19:28 </td>
   <td style="text-align:left;"> $SPY Golden Ratio Baby!  All down from here! $FB $AAPL $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:19:05 </td>
   <td style="text-align:left;"> $AAPL fb bad earnings = good news for apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:19:01 </td>
   <td style="text-align:left;"> $AAPL afraid for these now x( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:18:54 </td>
   <td style="text-align:left;"> $AAPL omg Apple 200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:18:52 </td>
   <td style="text-align:left;"> $AAPL  
 
Market has not bottomed out yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:18:23 </td>
   <td style="text-align:left;"> $AAPL 🍏’s altos killing that meta. $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:18:06 </td>
   <td style="text-align:left;"> $FB remember when $AAPL dropped like a rock before earnings hmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:17:26 </td>
   <td style="text-align:left;"> $AAPL This market is fu**ed maybe apple is the last man standing but most likely will get wacked tomorrow to </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:16:46 </td>
   <td style="text-align:left;"> $aapl all Nasdaq and spy heavy weights being battered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:16:43 </td>
   <td style="text-align:left;"> $AAPL Meta just fucked the market! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:16:40 </td>
   <td style="text-align:left;"> $AAPL thank god I got $190 puts at close for August😂😂😂aight imma head out and check back on this in June. $150 incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:15:37 </td>
   <td style="text-align:left;"> $AAPL fb didnt fuck apple. Yall get a life its retail betting on apple to go down because of fb horrible earnings. Smart money will actually rotate out into apple. This doesnt budge apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:15:19 </td>
   <td style="text-align:left;"> $AAPL 162.59 short term , will buy dip from there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:15:12 </td>
   <td style="text-align:left;"> $AAPL $baba already fucked the calls but now $fb and $spot are going to fuck the whole market tomorrow.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:15:00 </td>
   <td style="text-align:left;"> $FB $AMZN $GOOGL $AAPL $NVDA 
Angry Bulls tomorrow 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:14:37 </td>
   <td style="text-align:left;"> $AAPL lmao the bulls saying Fb fked u guys, what about google that kept your ass green today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:14:35 </td>
   <td style="text-align:left;"> $AAPL $GOOGL $FB why overpay for $MSFT ?? Never buy after 2:30 pm on a rip - sell the rips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:14:33 </td>
   <td style="text-align:left;"> $AAPL plz🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:14:31 </td>
   <td style="text-align:left;"> Wedbush&amp;#39;s Bryson Talks Semiconductor Trends With PreMarket Prep: AMD Earnings, Metaverse, 5G And More $AAPL $AMD $SONY https://www.benzinga.com/node/25379267#.Yfr0KN28xd4.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:14:26 </td>
   <td style="text-align:left;"> $AAPL mm using this opportunity to scare .. loving it.. its going to be back up soon when things settle down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:13:47 </td>
   <td style="text-align:left;"> $AAPL fuck $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:13:40 </td>
   <td style="text-align:left;"> $AAPL pulled a paypal lmao. down 30% tomorrow minimum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:13:40 </td>
   <td style="text-align:left;"> $AAPL Don&amp;#39;t bet against America.  If you bet against the American economy then you&amp;#39;re a terrorist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:13:32 </td>
   <td style="text-align:left;"> $AAPL fucking BS if meta tanks isn’t it apples gain. Zuck is a scumbag and can’t compete with Tim apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:13:11 </td>
   <td style="text-align:left;"> $AAPL fb officially ruined tomorrow party, let’s see what $AMZN does tmr, we will have a great Friday or a miserable one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:13:00 </td>
   <td style="text-align:left;"> $AAPL the only thing preventing a complete meltdown in this market is this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:12:42 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

RED!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:12:34 </td>
   <td style="text-align:left;"> $AAPL Apple will Carry tmr . L Facebook </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:12:33 </td>
   <td style="text-align:left;"> $FB  come on over to $AAPL  the waters fine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:12:20 </td>
   <td style="text-align:left;"> $AAPL   🍏 FB:  Meta reported.  Disaster Guidance.  Blaming AAPL…. Down 18% AHs.  AAPL is the Stock to own! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:11:47 </td>
   <td style="text-align:left;"> i can&amp;#39;t believe i&amp;#39;m not short $FB. that $AAPL IOS update is a complete fiasco for them...plus it always feels good to be short FB! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:11:39 </td>
   <td style="text-align:left;"> $AAPL lol hate commie fb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:11:26 </td>
   <td style="text-align:left;"> $SPY $QQQ Wow $FB really disappointed, still don&amp;#39;t think the market will be too concerned since we just got great earnings from $GOOGL and $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:11:18 </td>
   <td style="text-align:left;"> $AAPL where is that dumbass bull, 162 inc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:11:00 </td>
   <td style="text-align:left;"> $AAPL $FB just fucked us. I really hate that fucking company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:10:40 </td>
   <td style="text-align:left;"> $AAPL me feels a lot of money will move to $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:10:13 </td>
   <td style="text-align:left;"> $FB $AMZN $AAPL $GOOGL $SPY 
Tomorrow Amazon ⤵️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-03 05:09:41 </td>
   <td style="text-align:left;"> $FB apple really hurt the mobile ad business for Facebook. $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:03:42 </td>
   <td style="text-align:left;"> $NIO $TSLA $FB NASDQ is 300 points down now. Stupid facebook. Bloodbath tomorrow. Good night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:03:34 </td>
   <td style="text-align:left;"> $DOGE.X $TSLA yep 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:02:48 </td>
   <td style="text-align:left;"> $TSLA BULLS please explain all the Peanut Holding jockeying for $1000 by Friday? CALLS DECIMATED! 😂😂😂 
 
EPIC FAIL ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:02:37 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-02 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=KczpWpqoBQ8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:02:08 </td>
   <td style="text-align:left;"> $TSLA Facebook parent Meta Platforms said user additions stalled in the fourth quarter and gave a disappointing forecast for the current quarter  
 
https://www.bloomberg.com/news/articles/2022- 
02-02/facebook-shares-plunge-as-users-stall-forecast-falls-short?sref=pHyhiApD via @technology  
 
Company reports heavy losses from virtual reality effort </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:01:52 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $910.0 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:01:19 </td>
   <td style="text-align:left;"> $TSLA 880 nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:00:59 </td>
   <td style="text-align:left;"> $TSLA bulls waking up tomorrow 🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:00:58 </td>
   <td style="text-align:left;"> $TSLA 600 by March </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:00:55 </td>
   <td style="text-align:left;"> $TSLA $930 max pain this week, $950 next. Let it drop to mid 800s tomorrow and let&amp;#39;s see the buying that pours in 🎉 FB will have little effect on this monster long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 09:00:28 </td>
   <td style="text-align:left;"> $TSLA breaking 880 🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:59:08 </td>
   <td style="text-align:left;"> $TSLA 600 by March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:58:56 </td>
   <td style="text-align:left;"> $TSLA just say it 💤 Joe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:58:05 </td>
   <td style="text-align:left;"> $TSLA 

You’re doing round 2 donation but you don’t  know yet!! 

Thank you in advance … Shorts don’t like money I do !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:56:37 </td>
   <td style="text-align:left;"> $TSLA How much can we drop tomorrow?

-10% would be cool with me.  A drop to $800 would be cooler though.  

Idk what it will do tomorrow - but I stand by my recent statement that this will trade at $600 by March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:56:17 </td>
   <td style="text-align:left;"> $TWTR never use this, only thing I open for is  Elon twit $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:55:51 </td>
   <td style="text-align:left;"> $TSLA I bought FB years ago and made money on it but who would be holding that cancer now? It has zero going for it should just start paying a dividend and be done with it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:55:16 </td>
   <td style="text-align:left;"> $TSLA lets go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:55:12 </td>
   <td style="text-align:left;"> $FORD Fun fact. Last earnings Ford brought in 35 billion dollars revenue with profits of 1.8 billion
 $TSLA  brought in 2.3 billion in profit off 17 billion in revenue Tesla makes more profits of less then half the revenue ..Tesla can sell less then half the cars Ford does and make more money then them. 

🤷🏼‍♀️🤷🏼‍♀️🤷🏼‍♀️🤷🏼‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:55:12 </td>
   <td style="text-align:left;"> $TSLA Biden Mentioning TSLA is now a catalyst 😐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:53:16 </td>
   <td style="text-align:left;"> $TSLA this would be at $500 now if not for google and apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:53:14 </td>
   <td style="text-align:left;"> $TSLA Everyone is waiting to buy at $850 AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:52:15 </td>
   <td style="text-align:left;"> $TSLA bulls were being so mean on Tuesday, I honestly didn’t get it :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:51:11 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

THIS POS BETTER BE BALLS DEEP RED 

TOMORROW, I WANNA SEE AN 

INSTITUTIONAL DUMP OF A LIFETIME... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:50:35 </td>
   <td style="text-align:left;"> $TSLA Trashla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:50:26 </td>
   <td style="text-align:left;"> $BTC.X $TSLA $FB $PLTR 

 New South Park tonight.

You’re welcome. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:50:20 </td>
   <td style="text-align:left;"> $TSLA Facebook lower than 52 week low! Not looking good tomorrow for the whole market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:49:55 </td>
   <td style="text-align:left;"> $TSLA no so strong without all that freshly printed Fed money! Congrats to the congress clowns for creating this 10 trillion dollar bubble with spiraling inflation 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:49:27 </td>
   <td style="text-align:left;"> $TSLA The gift that keeps giving. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:49:00 </td>
   <td style="text-align:left;"> $TSLA has a good Piotroski-F score of 7.00. This indicates a good health and profitability. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:48:45 </td>
   <td style="text-align:left;"> $FB Well there goes the bounce! $SPY $F $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:48:15 </td>
   <td style="text-align:left;"> $TSLA and now we can All call Elon the douche that he is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:47:50 </td>
   <td style="text-align:left;"> In 1 year we will have a worldwide reaching major media network with tv stations - social media - apps - and dozens of other things... but the best part will be the new Trump approved MAGA seal of approval on every single website or product or company or store or city or night club or restaurant or bank or well you get the picture sooo much revenue flowing thru MAGA soon $dwac $tsla $twtr $fb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:47:50 </td>
   <td style="text-align:left;"> $TSLA FSD is a façade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:47:21 </td>
   <td style="text-align:left;"> $TSLA to all my bear friends here,  it might still be 950 tomorrow. Hogue dump AM and rally into close. Just saying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:46:56 </td>
   <td style="text-align:left;"> $TSLA 4hr view from 1/09 weekend update. Can see another blue box area where buyers should be waiting to appear again #elliottwave #tading #tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:46:24 </td>
   <td style="text-align:left;"> $TSLA Tesla Blue Box Area Provided The Minimum Reaction Higher. How we see the stock last November #elliottwave #tading #tesla #ondaselliott </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:45:38 </td>
   <td style="text-align:left;"> $TSLA i will load fuckin calls if this hits $850 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:45:30 </td>
   <td style="text-align:left;"> $TSLA under $800 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:44:59 </td>
   <td style="text-align:left;"> $TSLA so please explain me where did $225B of FB market cap disappeared ?
We’re approaching 2T$ in lost money on big tech where is it going ?
If this is not a bubble what is ?
If this is not the beginning of a bear market what is ?
If this does not resemble 1929 what is ?
Depression hurts.
I think we just start to see the real fear !
Good luck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:44:13 </td>
   <td style="text-align:left;"> $TSLA were Semis delivered to Pepsi Co. by end of January as previously announced or was that only mentioned to pump the stock up so Musk can sell his shares? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:44:07 </td>
   <td style="text-align:left;"> $QQQ I missed the news, why is everything down after hours? $SPY $TSLA $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:42:43 </td>
   <td style="text-align:left;"> $TSLA 850 tomorrow unfortunately </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:42:41 </td>
   <td style="text-align:left;"> $TSLA 882 now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:42:24 </td>
   <td style="text-align:left;"> $TSLA by 7: 00 AM tomorrow , if Telsa drops 3% ima get in and get that 2% up then sit on the side line and watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:42:07 </td>
   <td style="text-align:left;"> $TSLA 

I would like to see Elon do another 5:1 Split to a share price of $177 per share.

Then take the share price back to $1,224.

Winner winner for everyone! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:41:43 </td>
   <td style="text-align:left;"> $TSLA They’re dropping like flies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:41:33 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA Key Levels Grid For Feb 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:40:16 </td>
   <td style="text-align:left;"> $TSLA Facebook has a P/E of 22 and is still getting drilled AH. 
 
Tesla has a P/E of 190?   
 
Oh man... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:39:56 </td>
   <td style="text-align:left;"> $TSLA when does the company report the fake China numbers? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:39:43 </td>
   <td style="text-align:left;"> $TSLA could see 400 next two weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:39:38 </td>
   <td style="text-align:left;"> $TSLA  Biden Must Recognize That TSLA Stock Is America’s Best EV Bet

https://investorplace.com/2022/02/biden-must-recognize-that-tsla-stock-is-americas-best-ev-bet/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:39:00 </td>
   <td style="text-align:left;"> $FSR $GM $F $TSLA https://www.fleetforward.com/10159530/crossing-the-thresholdelectric-crossovers-suvs-2022-beyond </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:38:49 </td>
   <td style="text-align:left;"> $TSLA big downgrade. Next $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:38:25 </td>
   <td style="text-align:left;"> $TSLA break 790 tommorow follow $SHOP like a good girl! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:37:26 </td>
   <td style="text-align:left;"> $TSLA $770 can trade tomorrow or Friday.  Droolers will buy the dip all the way down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:36:51 </td>
   <td style="text-align:left;"> $TSLA this is fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:36:03 </td>
   <td style="text-align:left;"> $TSLA can&amp;#39;t wait for this bubble to pop. Fair price $100/share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:35:53 </td>
   <td style="text-align:left;"> $TSLA 

Great News

Did a little searching and found this.

Tesla chief executive Elon Musk says he will no longer be taking the electric car maker private, just two weeks after saying he was considering a deal. The plan was cancelled after a board meeting on Thursday, he wrote in a post published on the company&amp;#39;s site.

Aug 25, 2018 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:35:49 </td>
   <td style="text-align:left;"> $TSLA puts printing  🤑🤑🤑🤑 bulltards are ⤵️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:35:04 </td>
   <td style="text-align:left;"> $FB - is at July 2020 pricing…. Wow 😮 

🚨 $AAPL $GOOG $TSLA $SNAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:34:31 </td>
   <td style="text-align:left;"> $TSLA worst stock to keep in your folio. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:33:09 </td>
   <td style="text-align:left;"> $TSLA with downgrades this will fall additional 25%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:32:54 </td>
   <td style="text-align:left;"> $TSLA Go to 700 I sell my Fam to load up jk lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:32:51 </td>
   <td style="text-align:left;"> $SHOP $NVDA $TSLA market leader for years to come yes or no? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:32:26 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-02 Technical Analysis Video: 
https://www.youtube.com/watch?v=l9EEskAGzOQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:32:25 </td>
   <td style="text-align:left;"> $FB - is at Sept 2020 pricing…. Wow 😮 

🚨 $AAPL $GOOG $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:32:22 </td>
   <td style="text-align:left;"> $FB .....The weighting system....☠ It is absolutely terrible when a handful of stock can affect an entire Market...😪 Anyway here&amp;#39;s a line for you $AAPL $TSLA $MSFT $SPY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:31:31 </td>
   <td style="text-align:left;"> $TSLA 880 support 902 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:30:48 </td>
   <td style="text-align:left;"> $TSLA Come on make a new lod 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:30:36 </td>
   <td style="text-align:left;"> $TSLA Margin Calls tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:30:19 </td>
   <td style="text-align:left;"> $TSLA $883 now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:30:16 </td>
   <td style="text-align:left;"> $TSLA shorts are winning big. Never bet against Elon - is a statement of the past. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:29:08 </td>
   <td style="text-align:left;"> $TSLA so ugly … WTF 👺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:28:05 </td>
   <td style="text-align:left;"> $PLTR $QQQ $SPY $TSLA $FB 

As much as it sucks with Facebook dropping all of my stocks, I would love for Facebook to keep bleeding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:27:56 </td>
   <td style="text-align:left;"> $TSLA market’s reaction didn’t really make sense🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:26:17 </td>
   <td style="text-align:left;"> $TSLA if Amazon misses and I was still holding shares on this after hours tomorrow, I don&amp;#39;t think i would be able to sleep. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:25:59 </td>
   <td style="text-align:left;"> $TSLA sorry for being so negative. Just hit 502 and I&amp;#39;ll be satisfied </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:23:59 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:23:04 </td>
   <td style="text-align:left;"> $TSLA In my research today I find the following two things a bit odd;

1. Option activity 59% bearish 
2. Barclays and a few others have PT for Tesla still sitting at $300 range. 

My conclusion: Nobody knows and everybody is guessing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:22:44 </td>
   <td style="text-align:left;"> $TSLA please tank more to offset losses in Facebook </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:22:30 </td>
   <td style="text-align:left;"> $TSLA $700&amp;#39;s tommorow. See futures..? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:22:01 </td>
   <td style="text-align:left;"> $TSLA these swings are a traders wet dreams, fuck this market.. going balls deep in  trades.. ain&amp;#39;t holding nothing long or mid term. My 401k can do that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:21:36 </td>
   <td style="text-align:left;"> $TSLA You bulls ready to skydive back to reality? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:20:28 </td>
   <td style="text-align:left;"> $DWAC wen elon tweet $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:20:24 </td>
   <td style="text-align:left;"> $TSLA this is ridiculous </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:19:38 </td>
   <td style="text-align:left;"> latexf874c125149a152ea6dd179da307dca1$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:16:25 </td>
   <td style="text-align:left;"> $TSLA 777k watchers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:15:31 </td>
   <td style="text-align:left;"> $TSLA deliveries will 2x this year folks.  All else is merely noise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:15:11 </td>
   <td style="text-align:left;"> $FB $TSLA $MSFT $amd  i have 50k cash that will use to buy the dips,  waiting for prices to go back to pre pandemic level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:14:00 </td>
   <td style="text-align:left;"> $TSLA my tiny dick can&amp;#39;t take this much longer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:13:30 </td>
   <td style="text-align:left;"> $TSLA when $800 breaks it’s hello $550.  🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:12:55 </td>
   <td style="text-align:left;"> $TSLA well it broke 900.  no bueno </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:12:48 </td>
   <td style="text-align:left;"> $tsla $lcid $rivn $fsr https://www.youtube.com/watch?v=utVr6bkZmIA&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:12:03 </td>
   <td style="text-align:left;"> $TSLA $780 by Friday am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:11:54 </td>
   <td style="text-align:left;"> $TSLA massive rebound </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:11:49 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:11:27 </td>
   <td style="text-align:left;"> $QQQ mother of all clowns 🤡 @Dr_Stoxx  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:11:22 </td>
   <td style="text-align:left;"> $TSLA just a start would like to see -20% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:10:56 </td>
   <td style="text-align:left;"> $TSLA who’s gonna tell bulls… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:10:32 </td>
   <td style="text-align:left;"> $qqq $spy $spx $ndx $tsla https://www.youtube.com/watch?v=JZ63GccJBAY&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:10:22 </td>
   <td style="text-align:left;"> $TSLA 
&amp;quot;Tesla is not a member of our association because it&amp;#39;s not an autonomous vehicle, it&amp;#39;s a driver assistance technology&amp;quot; - Ariel Wolf, general counsel for
Autonomous Vehicle Industry Association </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:09:45 </td>
   <td style="text-align:left;"> $tsla $qqq $aapl $btc.x https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:09:42 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:08:59 </td>
   <td style="text-align:left;"> $TSLA tomorrow Tesla will have its single day biggest drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:08:58 </td>
   <td style="text-align:left;"> $TSLA $800 again i’m in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:07:16 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:07:10 </td>
   <td style="text-align:left;"> $F not going to change much in next 5 yrs. May Tesla could be 55 to 60%. Worst case it can capture more. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:07:02 </td>
   <td style="text-align:left;"> $ISR anyone else think this could run big in PM? $GME $TSLA $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:06:23 </td>
   <td style="text-align:left;"> $TSLA 
Facebook tanked AH market cause people are to dumb to realize the truth.
Facebook blamed inflation and supply chains on their ER miss when in fact it was due to Apples privacy changes many months ago… finally catching up in ER numbers.
Markets tank cause dumb dumbs believe the world is ending when in fact Mark Zuckerdick is full o shi$ blaming his business failures on false narratives. 
Guess what .?
Buy the dip … cause it’s an opportunity..nothing has changed .
The bears are morons … 
Buy the dip . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:05:40 </td>
   <td style="text-align:left;"> $TSLA  
 
techies 👨‍💻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:03:57 </td>
   <td style="text-align:left;"> $TSLA 

Last two hours:

Spotify down 20%
Pinterest down 20%
Snap down 20%
Facebook down 20%

Tech crash here we come! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:02:52 </td>
   <td style="text-align:left;"> $TSLA The day finally people realize what car they can afford, and Tesla-stonk is a penny-stonk☑️🔮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:02:46 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #4 ticker with sweep activity where institutions are trading options urgently with 29.5K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:02:31 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-02 Trade Analysis Video: 
https://www.youtube.com/watch?v=ZI8PmBaLW3Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 08:00:17 </td>
   <td style="text-align:left;"> $TSLA it is down because Facebook lost $10B on meta research program? 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:59:09 </td>
   <td style="text-align:left;"> $FB $AMZN $IWM $TSLA  
Winter is coming! This might help.  
 
https://www.financegreater.com/post/managing-a-bearish-market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:58:58 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:57:28 </td>
   <td style="text-align:left;"> $TSLA https://www.change.org/p/president-biden-please-acknowledge-tesla-s-ev-leadership
Tesla long 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:57:26 </td>
   <td style="text-align:left;"> $TSLA $800 open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:56:41 </td>
   <td style="text-align:left;"> $FB $TSLA 2021 performances :
Rev $TSLA  - $53.8 $FB - $117.9 B
Income $TSLA - $5.8 B $FB - $39.4B
= $TSLA market cap 25% more than $FB
Makes total sense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:56:39 </td>
   <td style="text-align:left;"> $FB $AMZN $TSLA $SPY $SPX   
In case you were worried you might have missed the dip, relax, you didn&amp;#39;t. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:55:34 </td>
   <td style="text-align:left;"> $TSLA 
Guided to 50% Increase in deliveries in 2022. Stated that FSD will be reality in 2022. Berlin and Texas up and humming in 2022. Acknowledging there may be supply constraints and factoring this into their guidance.  All these facts plus the fact that they can’t keep up with demand and all models are president. Any dip should be looked at as a gift and taken advantage of. This is not Pay Pal, or Facebook. Jump on it and HODL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:55:32 </td>
   <td style="text-align:left;"> $TSLA earth to elon? We want the stock back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:55:29 </td>
   <td style="text-align:left;"> $TSLA we’ll, atleast the gap will get filled lol. So glad I dumped my short term options 😅😅😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:54:44 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:54:19 </td>
   <td style="text-align:left;"> $TSLA Hold.  This can only move with fluidity. Hold to the core. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:53:46 </td>
   <td style="text-align:left;"> $TSLA going down because of a social media network app😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:52:03 </td>
   <td style="text-align:left;"> $TSLA $AMZN going to miss earnings and customer spending  tomorrow its gonna crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:51:50 </td>
   <td style="text-align:left;"> $AAPL Tomorrow J.Daddy Bank Bucks need  to face the nation.🇺🇲0.0005% .. $FB $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:50:56 </td>
   <td style="text-align:left;"> $TSLA Dr Burry come back! We&amp;#39;re having so much fun finally popping this bubble 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:46:47 </td>
   <td style="text-align:left;"> $SPY $QQQ MM waited to fuck you. Meta miss is an over reaction, but also a reason to trap those calls on SPY and Qs top ten weighted stonks. You&amp;#39;re fucked. $fb $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:46:27 </td>
   <td style="text-align:left;"> $TSLA JUNK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:46:16 </td>
   <td style="text-align:left;"> $TSLA they’ll probably bring it back up premarket to kill put value. They seemed to be out to kill premiums both ways today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:45:32 </td>
   <td style="text-align:left;"> $CLF this market is going to become more and more bifurcated over the next 3-6 months. The winners and losers are being defined during this earnings season. I’m  down to $TSLA and $CLF and I’m quite content with my positions! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:45:26 </td>
   <td style="text-align:left;"> $DWAC $twtr $fb $tsla Mr Zuckerberg, What do you have to say for yourself about censoring the Hunter Biden Laptop and the 10% to the &amp;quot;big guy&amp;quot;? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:44:45 </td>
   <td style="text-align:left;"> $NIO be careful guys $NIO and $TSLA are selling ads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:44:13 </td>
   <td style="text-align:left;"> $FB $TSLA $AMD $SPY $AMZN only one person exists who enlarged his $$$ from beginning of the year.. Guess who? Warren Buffet my man is only person who actually made money in Jan while others lost 25+ billions. My man Warren always do well, can&amp;#39;t believe it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:43:58 </td>
   <td style="text-align:left;"> $TSLA $847 on deck for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:42:38 </td>
   <td style="text-align:left;"> $TSLA reverse head &amp;amp; shoulders pattern forming on the 30 day chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:42:07 </td>
   <td style="text-align:left;"> $TSLA I didn’t know Facebook made evs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:41:55 </td>
   <td style="text-align:left;"> $FB $SPY $PYPL $TSLA $QCOM 

BREAKING: Meta announces new Indian CEO to make the stock price go up and immediately changes name to Beta. 

😆🤣😆 I love the interwebs 😆🤣😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:41:53 </td>
   <td style="text-align:left;"> $XPEV $NIO $TSLA  
 
The sky will fall tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:41:01 </td>
   <td style="text-align:left;"> $TSLA possible some FB investors rotate into Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:39:59 </td>
   <td style="text-align:left;"> $TSLA $SPY FANG mini bull run is done. Back to downtrend looks like. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:38:28 </td>
   <td style="text-align:left;"> $TSLA I will buy at 800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:38:16 </td>
   <td style="text-align:left;"> $TSLA so Tesla is in the same business of Facebook? 🤔🤔 interesting reaction after hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:38:03 </td>
   <td style="text-align:left;"> $TSLA 6uild 6ack 6etter club hates Elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:37:41 </td>
   <td style="text-align:left;"> $TSLA WEEEEEEEE short lived bull.  Back to market crash? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:37:10 </td>
   <td style="text-align:left;"> Last $TIME IICZECH THERE IS NO ROAD So $DRIV $ON   in $AI   2 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:37:00 </td>
   <td style="text-align:left;"> $TSLA SAY IT WIT ME. WE WILL GAP DOWN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:35:55 </td>
   <td style="text-align:left;"> We need Battery Storage and NeoGrids from  $OZSC  and  $TSLA  asap!!!

A deep freeze is coming to Texas, and no one knows if the power grid is ready | Ars Technica https://arstechnica.com/science/2022/02/a-deep-freeze-is-coming-to-texas-and-no-one-knows-if-the-power-grid-is-ready/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:35:05 </td>
   <td style="text-align:left;"> $TSLA Jeff Zucker (CNN CEO) resigned under credible allegations of sexual misconduct.

👏🏼👏🏼👏🏼

Al these lying perverts going down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:35:00 </td>
   <td style="text-align:left;"> $GOOGL god this market is so fucked we need Biden out of office anyone but him I’ll even take crooked Hillary smh also fuck Jerome Powell  that backstabber $TSLA $SPY $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:33:27 </td>
   <td style="text-align:left;"> $FB $TSLA after earnings, $TSLA market cap is 25% more than $FB... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:33:13 </td>
   <td style="text-align:left;"> $TSLA would be nice if Musk tweets that he&amp;#39;s gonna retire from Tesla just focus on spaceX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:33:04 </td>
   <td style="text-align:left;"> $TSLA owners will be like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:33:00 </td>
   <td style="text-align:left;"> $TSLA so tomo it’ll go up again .. what’s this 2 days up than down than up .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:32:21 </td>
   <td style="text-align:left;"> $TSLA lmao FB down 23% and it can only pull this down 2% 😂 keep selling those puts, bears and see where it gets u </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:32:04 </td>
   <td style="text-align:left;"> $DWAC $twtr $fb $tsla only a matter of hours or minutes until Elon tweets a comment on Meta and Twitter!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:31:59 </td>
   <td style="text-align:left;"> $TSLA this has a lot of room to go down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:31:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $QCOM 

It’s to the slaughterhouse for these bloated piggies... 🐖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:30:07 </td>
   <td style="text-align:left;"> $TSLA 🥱 the past 3 days in the market is what’s called a “dead cat bounce” $700 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:29:33 </td>
   <td style="text-align:left;"> $TSLA EVIL 666 COMING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:29:31 </td>
   <td style="text-align:left;"> $TSLA Gunna be getting an even better dip. Nice! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:29:23 </td>
   <td style="text-align:left;"> $TSLA so wait tesla is down today $45 just because of what??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:29:13 </td>
   <td style="text-align:left;"> $TSLA  Probably the most heavily produced TSLA video ever on option trading.   
 
https://youtu.be/tz_rBZ0bYVQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:28:47 </td>
   <td style="text-align:left;"> $TSLA OMG. On Tomorrow IS the day. 200B market cap drop from Facebook. I can&amp;#39;t see the moment this collapses to 500$ in a single trading session. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:28:03 </td>
   <td style="text-align:left;"> $TSLA  smh 
 
https://asiatimes.com/2022/02/whos-to-blame-when-your-autonomous-car-kills-someone/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:27:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA $FB free speech is dead. I will
Most likely get banned tonight so consider this my last post. 

Big tech is coming for you. Soon we will
Be like a third world country. Hyperinflation will loom over the heads of everyone, we won’t be able to say things, books will be burned bc they’re not “woke”, the economic system will be so messed up it we will see millionaires starve. 

Prepare people! Get right with your maker! That is all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:26:39 </td>
   <td style="text-align:left;"> latex22de77b65ff532626bbae8b32b44596f$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:25:38 </td>
   <td style="text-align:left;"> $TSLA Stupid $FB. Are you kidding me … down 23% AH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:25:31 </td>
   <td style="text-align:left;"> $TSLA I said it  yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:25:27 </td>
   <td style="text-align:left;"> $TSLA I hedged this time, wasn’t getting caught with my pants down again. Drop it all you want!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:24:04 </td>
   <td style="text-align:left;"> $TSLA tomorrow green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:23:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

Love my cheap PUT. Will pay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:23:35 </td>
   <td style="text-align:left;"> $TSLA 900K cars delivered, recalled 500K, that alone should&amp;#39;ve put Tesla out of its misery. But Musk is going to leave Tesal &amp;amp; meme status will be gone too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:22:37 </td>
   <td style="text-align:left;"> $TSLA unnecessary selling . That would mean that all deliveries and new factories don’t matter at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:22:04 </td>
   <td style="text-align:left;"> $XELA , The BEST PENNY STOCK loves $SPOT $AAPL $AMZN $TSLA  Join us to squeeze shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:21:48 </td>
   <td style="text-align:left;"> $TSLA hedges are fuding retail investors. f-ck them. we are way better investors now. and know this, HEDGES KNOW TESLA WILL BE A REVOLUIONARY CO &amp;amp; THEY WANT TO STEAL OUR SHARES. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:21:00 </td>
   <td style="text-align:left;"> $TSLA bad feeling about tomorrow 😪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:20:31 </td>
   <td style="text-align:left;"> $TSLA was up nice AH yesterday and crashed today hopefully it does the reverse tomorrow either way this market is crazy right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:20:07 </td>
   <td style="text-align:left;"> $TSLA If panic selling tmrw and lose major supports, it can drop like 🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:19:56 </td>
   <td style="text-align:left;"> $TSLA reduced to manufacturing these, till further notice .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:18:46 </td>
   <td style="text-align:left;"> $TSLA tesla will drop $100 tomorrow. confirmed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:18:45 </td>
   <td style="text-align:left;"> $TSLA could lose support and see 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:18:14 </td>
   <td style="text-align:left;"> $TSLA I told you these cars are ugly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:17:59 </td>
   <td style="text-align:left;"> $TSLA Big push to electric cars not stopping anytime soon. Buy the dips. Smart money will be. Hedge funds that missed the initial push accumulating. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:16:56 </td>
   <td style="text-align:left;"> $TSLA no clue where we stand or what direction we are going over the next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:16:47 </td>
   <td style="text-align:left;"> $TSLA just wait until the Fed raises rates! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:16:36 </td>
   <td style="text-align:left;"> $TSLA back in November this had a -$149 day. Let’s see it again 👊🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:16:25 </td>
   <td style="text-align:left;"> $TSLA wouldn&amp;#39;t be awesome to see Tesla under $400! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:16:17 </td>
   <td style="text-align:left;"> $TSLA https://insideevs.com.ar/news/564230/como-sera-tesla-model-2/
Tesla long 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:15:26 </td>
   <td style="text-align:left;"> $TSLA after cashing out my FB puts tomorrow morning, I will be buying more puts on this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:15:08 </td>
   <td style="text-align:left;"> $TSLA has to fill the gap at $198 gaps always get filled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:14:35 </td>
   <td style="text-align:left;"> $TSLA it’s alright taking a bullet for Jim Jones. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:13:59 </td>
   <td style="text-align:left;"> $TSLA The Nash Crash? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:13:46 </td>
   <td style="text-align:left;"> $TSLA Tomorrow is going to be ugly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:13:42 </td>
   <td style="text-align:left;"> $FB $spy $tsla $xbi $btc.x wow Biden is doing such a great job. The markets are super stable, tons of food on grocery shelves, everyone is employed, and his approval ratings are super high.

Lmaohahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:13:38 </td>
   <td style="text-align:left;"> $TSLA I really hope tesla does the opposite of what people expect because of the bad Facebook earnings.  But the naz will get hit hard because of Facebook. Bummer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:13:12 </td>
   <td style="text-align:left;"> $FB $tsla $dwav $cfvi Not a good day for anyone whose last name starts with Zuck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:13:00 </td>
   <td style="text-align:left;"> $TSLA when this Man talks. 
 
Fossil and clean Energy heads listen 🎧  
 
https://www.reuters.com/business/energy/aramco-ceo-says-energy-transition-not-going-smoothly-2022-01-27/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:12:45 </td>
   <td style="text-align:left;"> $TSLA only a matter time this stock collapses... tic-toc tic-toc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:12:13 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla $fb $PYPL 8th account. 7 perma ban via posting bearish on AMC, and 1 ban from fang stonk or indices tagged above. Stop being so sensitive. Bears on ST do DD and release info faster than your media heads on cnbc, YouTube, and Twitter. Fuck off. I had to unban this new account today for being RIGHT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:11:35 </td>
   <td style="text-align:left;"> Why would anyone leave Global Gigafactory Supply Chain at $tsla and $cat for $plug Power??? 
 
https://www.plugpower.com/plug-power-hires-former-tesla-and-caterpillar-execs-as-vice-presidents/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:11:33 </td>
   <td style="text-align:left;"> $TSLA  Today I took it easy on bulls. Tomorrow got to put some work 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:11:32 </td>
   <td style="text-align:left;"> $NFLX my trading group bought 2/4 exp 437.5 NFLX puts when this was at 452. We also bought $TSLA 900 puts 2/4 exp., when TSLA was trading about 935. Combined with the great earnings calls we had on FB AND PYPL, I&amp;#39;m clearing $250k this week, with no positions larger than 6k each... All trades are trade verified with Trade Hub. Join us, or don&amp;#39;t, we are happy this week either way! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:11:25 </td>
   <td style="text-align:left;"> $TSLA wait, seriously though, how is this spy satellite that just launched and landed back not in any news?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:11:23 </td>
   <td style="text-align:left;"> $TSLA this gonna hit the 1000 P/E Ratio like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:09:35 </td>
   <td style="text-align:left;"> $TSLA  1 trillion market cap under a Biden Administartion 🤣😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:08:27 </td>
   <td style="text-align:left;"> Tech Wreak 2022! $FB $PYPL $TSLA $QQQ $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:07:26 </td>
   <td style="text-align:left;"> $TSLA Bulls and Bears.  Required Viewing for tonight: 
 
https://www.youtube.com/watch?v=Hhy7JUinlu0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:07:17 </td>
   <td style="text-align:left;"> $TSLA lots of buys earlier </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:07:04 </td>
   <td style="text-align:left;"> $TSLA what going happen is tech will tank tomorrow and amzn will save the day AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:06:37 </td>
   <td style="text-align:left;"> $TSLA you’ve all been duped  
 
https://oilprice.com/Energy/Energy-General/The-Lack-of-Fossil-Fuel-Investment-Is-Hindering-The-Energy-Transition.amp.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:06:32 </td>
   <td style="text-align:left;"> $TSLA Only up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:06:04 </td>
   <td style="text-align:left;"> $TSLA you bears are pathetic , Tsla is not going to $300 get lost.  It’s been low since earnings. won’t go back to 796 like last week, it will be sideways up n down or fly up havre the shoulder is done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:05:51 </td>
   <td style="text-align:left;"> $SPY $FB $AMD $SNAP $TSLA 
Robot man fucked our Thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:05:15 </td>
   <td style="text-align:left;"> Absolutely amazing. This picture was from March 2021 when Cathie Wood was at the hight of her popularity before her historical downfall. How many people got suckered in. $ARKK $FB $SPOT $PYPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:05:14 </td>
   <td style="text-align:left;"> $TSLA shits going right back to 558.32 respectively 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:05:09 </td>
   <td style="text-align:left;"> $TSLA we may see $800 tomorrow unfortunately </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:05:00 </td>
   <td style="text-align:left;"> $SPY $NVDA $FB $AMZN $TSLA 
FYI. SPY is still there 👇 in the beginning of highest inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:04:35 </td>
   <td style="text-align:left;"> $TSLA the share price of this company will get slaughtered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:04:31 </td>
   <td style="text-align:left;"> $TSLA Alright robinhooders, let&amp;#39;s see how they are going to treat you from now until 9 am tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:03:49 </td>
   <td style="text-align:left;"> $SPY $TSLA These old tech companies need to move their money into cash or they moving their money to the future of tech. Tesla is the play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:03:39 </td>
   <td style="text-align:left;"> $TSLA 2000 by 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:03:15 </td>
   <td style="text-align:left;"> $TSLA $AMD -- both smashed their earnings results.   Both are down because FB (graph below) missed their earnings estimates.   You know what to do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:03:14 </td>
   <td style="text-align:left;"> $TSLA Just know that hedgies and corrupt elites will keep attacking Tesla and Elon Musk.  No reason to scream hold or hang in there.  We know the truth and even trillions of dollars or any power can change the truth. Tesla will revolutionalize humanity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:03:08 </td>
   <td style="text-align:left;"> $TSLA Bulls look up Stagflation. it will be here before summer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:02:56 </td>
   <td style="text-align:left;"> $TSLA bye bye tech futures tomorrow should be see off Am for sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:02:30 </td>
   <td style="text-align:left;"> $TSLA well I guess my 930 call is screwed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:02:02 </td>
   <td style="text-align:left;"> $TSLA the “first” and not last lol 
 
 “Kevin George Aziz Riad, 27, is likely the first motorist to be accused of a felony in the United States after a fatal accident while using a partially automated driving system” 
 
https://www.nbcnews.com/news/amp/rcna12724 
 
 
Elon be like .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:01:22 </td>
   <td style="text-align:left;"> $TSLA this sucks the big one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:01:16 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboys looking at Facebook after hours! Facebook wasn&amp;#39;t even considered overvalued!  People think the middle class are going to buy expensive, shitty EVs from this company when there is inflation and rates have substantially increased. Good luck! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:01:12 </td>
   <td style="text-align:left;"> $TSLA buy the dippers got dipped again. This dip taste so nice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:00:45 </td>
   <td style="text-align:left;"> $TSLA Wall Street is screwing almost everybody after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:00:37 </td>
   <td style="text-align:left;"> $TSLA wait...how is the rocket launching a classified satellite into space not news... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:00:35 </td>
   <td style="text-align:left;"> $TSLA Does anybody really listen to these people on Stockwitts? Hope not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 07:00:02 </td>
   <td style="text-align:left;"> $SHOP,  $TSLA , no logic if $FB  didn&amp;#39;t meet the expectation , why others stock should go down..all stocks are down 6% ..so weird. cant trust this market and manipulator </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:56:55 </td>
   <td style="text-align:left;"> $TSLA i think elon will call the saudis back and take this private before the bears get their wish…

-FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:56:42 </td>
   <td style="text-align:left;"> $TSLA looking forward to when this dumps. 30% after hours! It will be glorious! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:55:44 </td>
   <td style="text-align:left;"> $TSLA slow bleed to 720 before the next technical bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:55:07 </td>
   <td style="text-align:left;"> $TSLA  back down ya go 
 
https://www.vox.com/recode/22914487/clean-energy-fossil-fuels-salaries-unions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:53:53 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $910.0 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:53:03 </td>
   <td style="text-align:left;"> $AAPL Facebook $FB  and Apple are birds of A  feather..  $TSLA $$TWLO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:51:35 </td>
   <td style="text-align:left;"> $TSLA recallED. 
 
Software is bonkers.  
 
 Man charged with manslaughter due to Tesla. 
 
Lol Tesla drivers are guinea pigs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:51:18 </td>
   <td style="text-align:left;"> ***NEW VIDEO*** 
$TSLA Analysis that has turned out to be correct for the bull case 
Youtube- https://www.youtube.com/watch?v=1j3-fRIs-5Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:50:37 </td>
   <td style="text-align:left;"> $TSLA today: wtf was that about? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:50:31 </td>
   <td style="text-align:left;"> $TSLA last week I couldn&amp;#39;t lose.  This week, I zigged while market zagged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:49:49 </td>
   <td style="text-align:left;"> Elon Musk about to tweet $TSLA about to buy $FB Facebook aka #META haha 
https://qr.ae/pGBmwP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:49:34 </td>
   <td style="text-align:left;"> $TSLA  if EM can capture a fraction of the utility mkt this stock flies look the f… outThe cat is out of the bag you r dumber than a 2x4 to short this guy 
Do not listen to the BS! Good luck! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:49:34 </td>
   <td style="text-align:left;"> $TSLA Let&amp;#39;s see what the last hour of trading brings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:48:53 </td>
   <td style="text-align:left;"> $FB  humanoid robot is the opposite of metaverse.  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:48:49 </td>
   <td style="text-align:left;"> $SPY $qqq I trade so neutral at all time. If you didn&amp;#39;t take advantage of volatility dump to buy affordable put for March, April, and June... learn for next time. First impression Apple, Microsoft, and Google got you the rally during uncertainty period, but last impression will dictate how indices operate - Facebook and Amazon. 

Bonus:
1. Job number sucks, and will suck again Friday.
2. CPI data next week will suck
3. Large tech earnings is finished. No more catalyst.

$tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:48:45 </td>
   <td style="text-align:left;"> $SPY $TSLA $GM

Wait, so...wait...

You&amp;#39;re telling me EVs aren&amp;#39;t environmentally friendly? 🤔

But, wait, I uh...I&amp;#39;m confused. 🧐

https://twitter.com/ecomaeve/status/1488545711625052162?t=N4yTxZ26Obz_kMfijjM3Dw&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:47:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is -4.65%. $TSLA outperforms 88% of its industry peers. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:45:57 </td>
   <td style="text-align:left;"> $TSLA Attention Tesla Bulls:  
 
It&amp;#39;s 2019 calling.   
 
They want their P/E back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:45:47 </td>
   <td style="text-align:left;"> $TSLA sorry guys I bought today so ofcourse this starts to tank...my apologies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:45:03 </td>
   <td style="text-align:left;"> $TSLA bears… you’re given a chart for free… why don’t u read it properly 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:44:32 </td>
   <td style="text-align:left;"> $TSLA y’all ready for $800 or less tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:44:29 </td>
   <td style="text-align:left;"> $TSLA any way this gaps up tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:43:06 </td>
   <td style="text-align:left;"> $TSLA Gonna wake up one day and this mofo gonna be at $600 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:41:11 </td>
   <td style="text-align:left;"> $TSLA dont worry broskis $5000 end of week keep buying those  calls

 💎 🙌 

🚀 🚀 🚀 

🤣
We the best </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:41:01 </td>
   <td style="text-align:left;"> $TSLA silly me for buying calls I should’ve known!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:41:00 </td>
   <td style="text-align:left;"> $TSLA Weird to see this fall with the indexes going up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:40:19 </td>
   <td style="text-align:left;"> $TSLA u can&amp;#39;t call someone a damp sock puppet TWICE and still expect that this person reconsiders his behavior

It&amp;#39;s OVER, Biden will never say &amp;quot;Tesla&amp;quot;, will never invite Elon etc
Stop complaining, Elon made a decision and already burned all bridges
Probably he knew, that there was nothing to expect from WH anyway.

Would YOU  do a favor to someone, who calls u a damp sock puppet? Of course not, especially not of u were aware, that u  r really just a damp sock puppet .... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:39:53 </td>
   <td style="text-align:left;"> $tsla $aapl $btc.x https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:39:49 </td>
   <td style="text-align:left;"> $TSLA Largest companies in the world with revenue is gas/oil. Tesla will take over this arena. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:39:39 </td>
   <td style="text-align:left;"> $TSLA Hedge funds who missed the run are bashing tonight. And will be buying in the morning. Love this game. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:38:49 </td>
   <td style="text-align:left;"> $TSLA alright I’m going calls for Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:38:45 </td>
   <td style="text-align:left;"> $TSLA atrocious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:37:03 </td>
   <td style="text-align:left;"> $TSLA looks like no matter what, more pullback is coming. Puts are looking attractive 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:37:02 </td>
   <td style="text-align:left;"> $TSLA what is this company has anything to do with fuckin  Facebook 
Gtfo here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:36:44 </td>
   <td style="text-align:left;"> $TSLA I have yuge FSD in my pants and it doesn’t need hands on the wheel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:35:25 </td>
   <td style="text-align:left;"> $TSLA brutal… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:35:07 </td>
   <td style="text-align:left;"> $TSLA GREAT PRODUCTS, OVERPRICED COMPANY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:34:02 </td>
   <td style="text-align:left;"> $TSLA Thoughts on tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:33:33 </td>
   <td style="text-align:left;"> Don’t buy anything til trump is back $FB $AMZN $TSLA $SHOP $FUBO etc 
Only down now   Recession time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:33:09 </td>
   <td style="text-align:left;"> $TSLA does Tesla actually meet expectations or is it accounting trick or wallstreet just have low expectations to keep it up for a little while! I read in .com Era, lots of companies had nice earnings &amp;amp; beating expectations, the minute company was sold to another firm, bankrupted... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:32:14 </td>
   <td style="text-align:left;"> Top Flow for the Week 🏎️: $TSLA with a single CALL Trade for total premium worth $2465.1K Ranking #11 the Week | This was a SWEEP trade.  | Visit SweepCast.com or Join our Premium Room For Access! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:31:29 </td>
   <td style="text-align:left;"> $TSLA pretty soon this will be next! Just made a killing on my FB puts!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:31:24 </td>
   <td style="text-align:left;"> $TSLA ;-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:31:07 </td>
   <td style="text-align:left;"> $TSLA Elon Musk Says He Was Truthful About Taking Tesla Private

https://www.thestreet.com/technology/elon-musk-says-he-was-truthful-about-taking-tesla-private </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:30:46 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-02 Largest Trades Data: 
https://www.youtube.com/watch?v=w6xulQny2jw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:30:45 </td>
   <td style="text-align:left;"> $TSLA  
 
Facebook P/E was 22 when it got demolished today. 
 
Tesla P/E at 190. 
 
Are you guys seeing the risk profile here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:30:25 </td>
   <td style="text-align:left;"> @soulcopy  Do or daunte $RIDE $ON $A $TSLA ROCK $ON  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:30:23 </td>
   <td style="text-align:left;"> $FB boy the day $TSLA ever misses their numbers.   40% down no problem </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:29:47 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:29:40 </td>
   <td style="text-align:left;"> $TSLA $SAVA $FB Looks like Facefuck took a dump after hours and took the whole $QQQ ship with it... Glad I got some $UVXY to turn the day positive. Yep trading is like that.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:29:25 </td>
   <td style="text-align:left;"> $TSLA panic selling has to be the number one reason investors loose money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:29:08 </td>
   <td style="text-align:left;"> $TSLA Keep listening  to the punch drunk bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:29:05 </td>
   <td style="text-align:left;"> $TSLA Elon crashing his old rocket into the moon.  Hope he doesn&amp;#39;t F it up too bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-03 06:28:56 </td>
   <td style="text-align:left;"> $TSLA 

Whole market going to tank the next few days! </td>
  </tr>
</tbody>
</table></div>

---
