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

[View the latest Economic Forecasts](/pdf/Monthly-Market-Outlook--Apr-2022-.pdf)

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



Last Updated: 2022-04-26 06:45:32 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/bro:us </td>
   <td style="text-align:left;"> 2022-04-26 06:15:49 </td>
   <td style="text-align:left;"> Brown &amp; Brown earnings above expectations at 0.77 USD </td>
   <td style="text-align:left;"> Brown &amp; Brown (BRO) released earnings per share at 0.77 USD, compared to market expectations of 0.75 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/25/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-04-26 06:06:12 </td>
   <td style="text-align:left;"> Nasdaq futures are slightly lower ahead of Big Tech earnings </td>
   <td style="text-align:left;"> , Nasdaq 100 futures fell slightly Monday evening after stocks bounced in the afternoon and ahead of Big Tech earnings.                                                                                                                                                                                                                   , Futures tied to the tech focused index fell 0.1%. Dow Jones Industrial Average futures and S&amp;P 500 futures were little changed.                                                                                                                                                                                                         , In regular trading Monday, the Nasdaq Composite jumped 1.3%. The Dow advanced 0.7%, after cutting a 500-point loss from earlier in the day, and the S&amp;P 500 gained 0.6%.                                                                                                                                                                , The moves came as tech names like Microsoft, Alphabet and Meta Platforms rallied in the afternoon, amid falling interest rates and ahead of an intense week of earnings for mega cap tech stocks. Twitter also jumped after its board accepted Tesla CEO Elon Musk's offer to take it private.                                          , The bounce was welcomed by investors after stocks ended the previous week on a sour note, with the Dow falling to its fourth down week in a row and the S&amp;P and Nasdaq hitting three-week losing streaks Friday. The tech-heavy Nasdaq is attempting to break out of bear market territory, sitting 19.8% from its record.              , Whether this is a bottom remains to be seen. Edward Moya, senior market analyst at Oanda, told CNBC there's still a lot of optimism about the U.S. economy and said he anticipates a relief rally from here.                                                                                                                            , "A third of the S&amp;P is reporting [earnings] this week, and you're probably going to see much of the same:  lots of top and bottom line beats. Companies are going to talk about margin pressures and passing on price increases to the consumer, but they're still going to highlight there's still overall optimism about the economy.", Goldman says oil and gas investment is about to boom, and names the stocks to cash in                                                                                                                                                                                                                                                   , Almost none of the Berkshire Hathaway analysts recommend buying the conglomerate’s stock                                                                                                                                                                                                                                                , Warren Buffett is on a roll. Here is what's behind his big moves and what could come next                                                                                                                                                                                                                                               , Between the continuation of earnings beats and a quiet period from the Federal Reserve, there will likely be a relief rally in the market, Moya added.                                                                                                                                                                                  , "We're not going to be getting more nervousness about Fed tightening, because we won't be hearing much more about it until the May meeting," he said.                                                                                                                                                                                   , Market bull Tom Lee, head of research at Fundstrat Global Advisors, said even though he'd expected a "treacherous" first half to the year, the market has been worse than even he expected, with inflation worsening relative to market expectations. Nevertheless, he remains optimistic.                                              , "When the bond market is screaming for Fed to be a bit tighter, it's tough for stocks to hold up and I think that's what we're kind of going through now, but, I don't think that means that we should be selling equities here either," he said on CNBC's "Closing Bell: Overtime" Monday.                                             , "Markets just want to have some sense of when this could end," he added. "If inflation doesn't reach some sort of apex that's concerning for markets, but I also don't think it's set in stone that inflation is going to continue to be a problem even in the second half."                                                            , Tech earnings will kick off on Tuesday after the bell with Alphabet and Microsoft. Meta, Amazon and Apple will report later in the week. UPS and 3M are also scheduled to report in the morning.                                                                                                                                        , In economic data, investors are expecting fresh numbers for new home sales and consumer confidence on Tuesday morning.                                                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/04/25/volunteers-ukraine-russian-invasion-kiley-pkg-lead-vpx.cnn </td>
   <td style="text-align:left;"> 2022-04-26 06:02:10 </td>
   <td style="text-align:left;"> What it's like to volunteer on the front lines in Ukraine - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/25/stocks-making-the-biggest-moves-after-hours-cadence-design-packaging-corp-of-america-sba-communications-and-more-.html </td>
   <td style="text-align:left;"> 2022-04-26 05:46:39 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Cadence Design, Packaging Corp of America, SBA Communications and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines in extended trading.                                                                                                                                                                                                                                                               , Cadence Design Systems – Shares of computer software company gained 5% after hours following the company's quarterly earnings reports. Earnings and revenue for the first quarter both came in above consensus forecasts, according to FactSet. The company also issued upbeat full year earnings and revenue guidance.     , Heidrick &amp; Struggles – The executive search firm's shares fell more than 4% in extended trading, despite reporting an increase in profit and revenue for the first quarter. The company also recorded a slew of increased spending for consolidates salaries and benefits, cost of services and administrative expenses.    , SBA Communications Corporation – Shares of the wireless communications company saw its stock rise 1.5% after reporting quarterly results, which included adjusted EBITDA that beat FactSet estimates and better-than-expected full year financial guidance. The company also announced it's repurchasing 1.3 million shares., Packaging Corp of America – The packaging company's shares advanced 1.6% after company earnings. Adjusted EBITDA for the first quarter came in at $467.2 million, compared to FactSet estimates of $443.1 million.                                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61222470?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-26 05:43:10 </td>
   <td style="text-align:left;"> Elon Musk strikes deal to buy Twitter for $44bn </td>
   <td style="text-align:left;"> The board of Twitter has agreed to a $44bn (£34.5bn) takeover offer from the billionaire Elon Musk.                                                                                                                                  , Mr Musk, who made the shock bid less than two weeks ago, said Twitter had "tremendous potential" that he would unlock.                                                                                                               , He also called for a series of changes from relaxing its content restrictions to eradicating fake accounts.                                                                                                                          , The firm initially rebuffed Mr Musk's bid, but it will now ask shareholders to vote to approve the deal.                                                                                                                             , Mr Musk is the world's richest person, according to Forbes magazine, with an estimated net worth of $273.6bn mostly due to his shareholding in electric vehicle maker Tesla which he runs. He also leads the aerospace firm SpaceX.  , "Free speech is the bedrock of a functioning democracy, and Twitter is the digital town square where matters vital to the future of humanity are debated," Mr Musk said in a statement announcing the deal.                          , "I also want to make Twitter better than ever by enhancing the product with new features, making the algorithms open source to increase trust, defeating the spam bots, and authenticating all humans," he added.                    , "Twitter has tremendous potential - I look forward to working with the company and the community of users to unlock it."                                                                                                             , The move comes as Twitter faces growing pressure from politicians and regulators over the content that appears on its platform. It has drawn critics from left and right over its efforts to mediate misinformation on the platform. , In one of its most high-profile moves, last year it banned former US President Donald Trump, perhaps its most powerful user, citing the risk of "incitement of violence".                                                            , At the time Mr Musk observed: "A lot of people are going to be super unhappy with West Coast high tech as the de facto arbiter of free speech."                                                                                      , News of the takeover has been cheered by the right in the US, although Mr Trump on Monday told Fox News he had no plans to re-join the platform.                                                                                     , The White House declined to comment on the takeover but spokesperson Jen Psaki told reporters: "No matter who owns or runs Twitter, the president has long been concerned about the power of large social media platforms."          , On Twitter, MP Julian Knight, chairman of the UK's Digital, Culture, Media and Sport Committee, called the deal an "extraordinary development in the world of social media".                                                         , "It will be interesting to see how a privately owned Twitter (run by a man who is an absolutist over free speech) will react to global moves to regulate."                                                                           , Mr Musk, who has more than 80 million followers on Twitter, has a controversial history on the platform himself.                                                                                                                     , In 2018 US financial regulators accused him of misleading Tesla investors with his tweets, claims that were resolved in a $40bn settlement and that Mr Musk continues to deny.                                                       , And in 2019 he was hit with a defamation suit - which he successfully defeated - after calling a diver involved in rescuing schoolboys in Thailand "pedo guy" on the platform.                                                       , On Monday, Mr Musk, who has been known to clash with journalists and block critics, suggested that he saw Twitter as a forum for debate.                                                                                             , "I hope that even my worst critics remain on Twitter, because that is what free speech means," he wrote just hours before the deal was announced.                                                                                    , As part of the takeover, which is expected to close later this year, Twitter's shares will be delisted and it will be taken private.                                                                                                 , Mr Musk has suggested this will give him freedom to make the changes he wants to the business.                                                                                                                                       , Among other ideas, he has suggested allowing longer posts and introducing the ability to edit them after they have been published.                                                                                                   , Twitter shares on Monday closed more than 5% higher after the deal was announced.                                                                                                                                                    , But the price remained lower than Mr Musk's $54.20 per share offer, a sign that Wall Street believes he is overpaying for the firm.                                                                                                  , Mr Musk has said he doesn't "care about the economics" of the purchase. However, he will take on a company with a chequered record of financial performance.                                                                         , Despite its influence, Twitter has rarely turned a profit and user growth, particularly in the US, has slowed.                                                                                                                       , The company, founded in 2004, ended 2021 with $5bn in revenue and 217 million daily users globally - a fraction of the figures claimed by other platforms such as Facebook.                                                          , Bret Taylor, chair of Twitter's board, said it had fully assessed Mr Musk's offer and it was "the best path forward for Twitter's stockholders".                                                                                     , It is not clear who will lead the company moving forward. Twitter is currently led by Parag Agrawal, who took over from co-founder and former boss Jack Dorsey last November.                                                        , But in his offer document, Mr Musk told Twitter's board: "I don't have confidence in management."                                                                                                                                    , Mr Agrawal on Monday said: "Twitter has a purpose and relevance that impacts the entire world. Deeply proud of our teams and inspired by the work that has never been more important."                                               , Mr Musk's targeting of Twitter has moved at remarkable speed. It emerged at the beginning of April that he had become the largest shareholder in the firm with a 9.2% stake.                                                         , He was then invited to join Twitter's board but turned down the offer before launching a surprise bid for the company on 14 April, saying he wanted to "unlock" its potential as a bastion of freedom of speech.                     , Twitter tried to fend off his bid, threatening to dilute the shareholdings of anyone who bought more than a 15% stake in the firm. However, its stance shifted after Mr Musk revealed more financial details about his proposed bid. , He has secured $25.5bn of financing for the deal and will take a $21bn stake in the business.                                                                                                                                        , The board unanimously approved the bid, which will now be presented to shareholders for a vote.                                                                                                                                      , The speed this move has happened at had many heads in Silicon Valley spinning.                                                                                                                                                       , From nowhere, Elon Musk is the absolute monarch of Twitter.                                                                                                                                                                          , He himself has said it's not about the "economics", this is about power and influence.                                                                                                                                               , By taking the company private he will exercise total control over Twitter.                                                                                                                                                           , He has the power to do with the company as he pleases. In practice that will mean a much lighter moderation policy.                                                                                                                  , He also says that he will make its algorithm public - so that people can better understand how Twitter works.                                                                                                                        , The move leaves the door open to Donald Trump's return to the platform, though he apparently says he would rather use his own social media platform Truth Social for now.                                                            , For years conservatives have argued that Twitter is biased against them - and the news has left Republicans in the US delighted.                                                                                                     , Others have been left dismayed at what Twitter might look like without strong platform moderation.                                                                                                                                   , You only need to look at how much criticism Facebook has received for not taking down groups linked to the QAnon conspiracy theory, or the Stop the Steal movement to imagine how much criticism Elon Musk is in store for.          , The danger that Twitter now faces is that unfettered free speech on social media can become very ugly, very quickly.                                                                                                                 , How many miles do you need to drive before it pays off?                                                                                                                                                                              , Gary Lineker on football, politics and road rage                                                                                                                                                                                     , Searching for Vladislav Surkov, key architect of the 'post truth' world                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cocoa </td>
   <td style="text-align:left;"> 2022-04-26 05:23:00 </td>
   <td style="text-align:left;"> Cocoa Drops Toward 4-Month Low </td>
   <td style="text-align:left;"> Cocoa futures on ICE fell toward $2400 per tonne, the lowest in nearly four months on demand concerns and amid expectations of higher supplies. The North American Confectioners Association reported that North American cocoa grindings, a measure of demand, fell to 114,694 tonnes in the first quarter, down 2.77% from the same period a year earlier. Meanwhile, the world's top producer Ivory Coast exported a total of 1.99 tonnes of cocoa during the October 1st to April 24th season, 1% higher than the corresponding period of the previous year; and Nigeria’s February exports rose 148% on the year to 27.6 thousand tonnes. Further, US inventories rose to a 4-3/4-month high of 5.06 million bags. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cck:us </td>
   <td style="text-align:left;"> 2022-04-26 05:13:14 </td>
   <td style="text-align:left;"> Crown earnings above expectations at 2.01 USD </td>
   <td style="text-align:left;"> Crown (CCK) released earnings per share at 2.01 USD, compared to market expectations of 1.82 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/energy-hungry-europe-buys-up-supertanker-sized-u-s-oil-cargoes?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-26 05:02:31 </td>
   <td style="text-align:left;"> Energy-Hungry Europe Buys Up Supertanker-Sized U.S. Oil Cargoes </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                                                                                                             , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                         , Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                                                                                                         , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                                                                                                                        , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                                                                                                                        , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                                                                                                          , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                                                                                                                     , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                                                                                                                     , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                                                                                                                    , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                                                                                                                       , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                                                                                                                        , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                                                                                                               , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                                                                                                          , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                                                                                                                        , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                                                                                                                 , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                                                                                                               , Elon Closes In                                                                                                                                                                                                                                                                                                                     , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                                                                                                                  , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                                                                                                               , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                                                                                                               , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                                                                                                              , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                                                                                                                       , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                                                                                                                 , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                                                                                                                        , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                                                                                                                        , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                                                                                                                        , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                                                                                                                       , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                                                                                                                      , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                                                                                                                     , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                                                                                                                    , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                                                                                                                     , Sheela Tobben                                                                                                                                                                                                                                                                                                                      , A supertanker delivered U.S. crude oil to Spain for the first time in more than six years as Europe increasingly relies on American energy to replace supply disruptions from Russia’s war in Ukraine.                                                                                                                             , Vessel Solana delivered some of its 2 million barrels of crude into the Spanish port of Bilbao in mid-April before unloading additional oil in Wilhelmshaven, Germany, and Rotterdam, tracking data show. Solana had received its U.S. oil cargo from smaller vessels while in the U.S. Gulf of Mexico before departing for Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/chinese-developer-bonds-diverge-as-offshore-creditors-lose-most?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-26 05:00:00 </td>
   <td style="text-align:left;"> Chinese Developer Bonds Diverge as Offshore Creditors Lose Most </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                                                                                                                                                                                                                                                         , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                                                                                                                                                                     , Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                                                                                                                                                                                                                                                     , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                                                                                                                                                                                                                                                                    , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                                                                                                                                                                                                                                                                    , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                                                                                                                                                                                                                                                      , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                                                                                                                                                                                                                                                                 , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                                                                                                                                                                                                                                                                 , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                                                                                                                                                                                                                                                                , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                                                                                                                                                                                                                                                                   , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                                                                                                                                                                                                                                                                    , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                                                                                                                                                                                                                                                           , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                                                                                                                                                                                                                                                      , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                                                                                                                                                                                                                                                                    , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                                                                                                                                                                                                                                                             , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                                                                                                                                                                                                                                                           , Elon Closes In                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                                                                                                                                                                                                                                                              , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                                                                                                                                                                                                                                                           , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                                                                                                                                                                                                                                                           , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                                                                                                                                                                                                                                                          , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                                                                                                                                                                                                                                                                   , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                                                                                                                                                                                                                                                             , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                                                                                                                                                                                                                                                                    , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                                                                                                                                                                                                                                                                    , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                                                                                                                                                                                                                                                                    , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                                                                                                                                                                                                                                                                   , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                                                                                                                                                                                                                                                                  , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                                                                                                                                                                                                                                                                 , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                                                                                                                                                                                                                                                                , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                                                                                                                                                                                                                                                                 , Some of China’s distressed developers have seen their domestic and offshore bond prices diverge sharply this year, as firms focus debt efforts on local investors.                                                                                                                                                                                                                                                                                                             , While the dollar notes of beleaguered builders like Yuzhou Group Holdings Co. and Shimao Group Holdings Ltd. have plunged to deeply distressed levels, some yuan bonds have seen smaller declines or even gained in price this year. Onshore holders have received coupon payments or sweetened offers on extension proposals while offshore payments are missed. A case also recently emerged about whether money owed in a restructuring would be able to leave the country.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/centerbridge-backed-suntex-marinas-said-to-tap-bofa-for-u-s-ipo?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-26 04:52:51 </td>
   <td style="text-align:left;"> Centerbridge-Backed Suntex Marinas Taps BofA for U.S. IPO </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                                                                                                                          , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                                      , Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                                                                                                                      , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                                                                                                                                     , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                                                                                                                                     , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                                                                                                                       , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                                                                                                                                  , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                                                                                                                                  , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                                                                                                                                 , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                                                                                                                                    , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                                                                                                                                     , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                                                                                                                            , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                                                                                                                       , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                                                                                                                                     , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                                                                                                                              , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                                                                                                                            , Elon Closes In                                                                                                                                                                                                                                                                                                                                  , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                                                                                                                               , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                                                                                                                            , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                                                                                                                            , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                                                                                                                           , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                                                                                                                                    , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                                                                                                                              , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                                                                                                                                     , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                                                                                                                                     , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                                                                                                                                     , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                                                                                                                                    , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                                                                                                                                   , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                                                                                                                                  , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                                                                                                                                 , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                                                                                                                                  , Gillian Tan                                                                                                                                                                                                                                                                                                                                     , Suntex Marinas Investors LLC, an owner and operator of marinas across the U.S. backed by Centerbridge Partners LP, has hired a lead underwriter as it prepares for a U.S. initial public offering, according to people with knowledge of the matter.                                                                                            , The Dallas-based real estate investment trust tapped Bank of America Corp. to helm a listing that could occur as soon as the third quarter, said one of the people, all of whom requested anonymity discussing the plans. Any transaction may value the company at more than $3 billion and is dependent on market conditions, the person said.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-26 04:47:00 </td>
   <td style="text-align:left;"> Brazilian Equities End at Near 1-Month Low </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, closed 0.4% down at 110,685 on Monday, the lowest since March 15th, extending losses for the sixth straight session. Fresh worries that spreading Covid cases and more lockdowns in China will hurt the global economy added to concerns that Federal Reserve tightening could also weaken growth prospects. At the same time, the war in Ukraine entered the third month, with no end in sight. Among single stocks, heavyweights Petrobras and miner Vale were the main draggers, tracking lower commodities prices. By contrast, TIM shares advanced more than 1% after the Brazilian telecoms company detailed the potential gains from the acquisition of Oi's mobile operations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/jcpenney-owners-offer-buy-archrival-kohls-8-6b </td>
   <td style="text-align:left;"> 2022-04-26 04:42:55 </td>
   <td style="text-align:left;"> JCPenney owners offer to buy archrival Kohl’s for $8.6B </td>
   <td style="text-align:left;"> Strategic Resource Group managing director Burt Flickinger argues retail sales increase is due to inflation.                                                                                                                                                                                                                       , The owners of JCPenney have made an offer to acquire archrival Kohl’s in a deal that could value the department-store chain at upwards of $8.6 billion, The Post has learned.                                                                                                                                                      , Under the proposal, shopping-mall giant Simon Property and Canada-based Brookfield Asset Management — which together scooped JCPenney out of bankruptcy in December 2020 — have offered to acquire Kohl’s for $68 a share, according to sources close to the talks.                                                                , The owners of JCPenney have made an offer to acquire department-store chain Kohl’s Inc., a source told The New York Post. (iStock / iStock)                                                                                                                                                                                        , Kohl’s shares on Monday closed at $60.39, up 5.3 percent.                                                                                                                                                                                                                                                                          , One well-placed source told The Post that the plan is for JCPenney’s corporate parents to continue to maintain two separate brands while streamlining operations and cutting costs. The bidders’ plan for Kohl’s is to slash costs by $1 billion over the next three years, according to the source.                               , OLD NAVY TO AVOID PRICE INCREASES ON KIDS' APPAREL THROUGH BACK-TO-SCHOOL SEASON                                                                                                                                                                                                                                                   , The Post has reached out to Simon Property Group and Brookfield Asset Management seeking comment.                                                                                                                                                                                                                                  , Kohl’s, based in Wisconsin, put itself up for sale earlier this year at the urging of activist investors Macellum and Engine Capital, who were unhappy with the direction of the company.                                                                                                                                          , Kohl's put itself up for sale earlier this year. (Photographer: Daniel Acker/Bloomberg via Getty Images) ( Daniel Acker/Bloomberg via Getty Images) / Getty Images)                                                                                                                                                                , Private equity giants Sycamore Partners and Leonard Green &amp; Partners as well as Saks Fifth Avenue’s Canada-based parent company Hudson’s Bay are reportedly interested in acquiring Kohl’s.                                                                                                                                        , Goldman Sachs has been tapped to lead a potential sales process.                                                                                                                                                                                                                                                                   , Simon and Brookfield have proposed that a single management team would operate JCPenney and Kohl’s while merging the information technology systems so that one unit is in charge of the chains, according to a source. The companies would also have all private apparel manufactured by the same in-house label, the source said., SUPPLY CHAIN EXPERT WARNS OF RISING RATES GOING INTO PEAK SEASON: ‘I SEE A LOT OF TROUBLE’                                                                                                                                                                                                                                         , If the sale is complete, the new business would ditch plans to roll out Sephora concession stands inside Kohl’s locations, The Post has learned.                                                                                                                                                                                   , Simon Property Group is run by CEO David Simon, the son of the late company co-founder Melvin Simon. David Simon’s uncle, Herb Simon, who co-founded the company with his late brother, is the owner of the NBA’s Indiana Pacers — the team the Simon brothers bought in 1983.                                                     , A parking lot at a JC Penney store is empty in Roseville, Mich.  (AP Photo/Paul Sancya, File / AP Newsroom)                                                                                                                                                                                                                        , Simon Property Group and Brookfield Asset Management acquired JCPenney after the 118-year-old retailer filed for Chapter 11 bankruptcy in May 2020.                                                                                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                        , JCPenney was one of two dozen retail casualties of the coronavirus pandemic as lockdown measures barred in-person shopping while consumers turned to online options like Amazon.                                                                                                                                                   , The restructuring forced the closure of a third of its stores nationwide. As of now, there are just 689 JCPenney locations in operation — down from more than 1,110 in 2012. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/uhs:us </td>
   <td style="text-align:left;"> 2022-04-26 04:42:40 </td>
   <td style="text-align:left;"> Universal Health Services earnings below expectations at 2.15 USD </td>
   <td style="text-align:left;"> Universal Health Services (UHS) released earnings per share at 2.15 USD, compared to market expectations of 2.48 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/pkg:us </td>
   <td style="text-align:left;"> 2022-04-26 04:42:34 </td>
   <td style="text-align:left;"> Packaging Of America earnings above expectations at 2.72 USD </td>
   <td style="text-align:left;"> Packaging Of America (PKG) released earnings per share at 2.72 USD, compared to market expectations of 2.51 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/wrb:us </td>
   <td style="text-align:left;"> 2022-04-26 04:42:27 </td>
   <td style="text-align:left;"> W.R. Berkley earnings above expectations at 1.10 USD </td>
   <td style="text-align:left;"> W.R. Berkley (WRB) released earnings per share at 1.10 USD, compared to market expectations of 0.94 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/amp:us </td>
   <td style="text-align:left;"> 2022-04-26 04:42:21 </td>
   <td style="text-align:left;"> Ameriprise Financial earnings above expectations at 5.98 USD </td>
   <td style="text-align:left;"> Ameriprise Financial (AMP) released earnings per share at 5.98 USD, compared to market expectations of 5.88 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/are:us </td>
   <td style="text-align:left;"> 2022-04-26 04:42:14 </td>
   <td style="text-align:left;"> Alexandria Real Estate Equities earnings below expectations at -0.96 USD </td>
   <td style="text-align:left;"> Alexandria Real Estate Equities (ARE) released earnings per share at -0.96 USD, compared to market expectations of 0.75 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/whr:us </td>
   <td style="text-align:left;"> 2022-04-26 04:11:29 </td>
   <td style="text-align:left;"> Whirlpool earnings above expectations at 5.31 USD </td>
   <td style="text-align:left;"> Whirlpool (WHR) released earnings per share at 5.31 USD, compared to market expectations of 4.82 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sbac:us </td>
   <td style="text-align:left;"> 2022-04-26 04:11:08 </td>
   <td style="text-align:left;"> SBA Communications earnings above expectations at 1.72 USD </td>
   <td style="text-align:left;"> SBA Communications (SBAC) released earnings per share at 1.72 USD, compared to market expectations of 1.00 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cdns:us </td>
   <td style="text-align:left;"> 2022-04-26 04:11:02 </td>
   <td style="text-align:left;"> Cadence Design Systems earnings above expectations at 1.17 USD </td>
   <td style="text-align:left;"> Cadence Design Systems (CDNS) released earnings per share at 1.17 USD, compared to market expectations of 1.02 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/rumbling-in-options-market-is-sound-of-traders-rushing-to-hedge?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-26 04:08:43 </td>
   <td style="text-align:left;"> Rumbling in Options Market Is Sound of Traders Rushing to Hedge </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                                                                                                                              , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                                          , Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                                                                                                                          , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                                                                                                                                         , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                                                                                                                                         , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                                                                                                                           , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                                                                                                                                      , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                                                                                                                                      , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                                                                                                                                     , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                                                                                                                                        , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                                                                                                                                         , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                                                                                                                                , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                                                                                                                           , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                                                                                                                                         , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                                                                                                                                  , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                                                                                                                                , Elon Closes In                                                                                                                                                                                                                                                                                                                                      , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                                                                                                                                   , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                                                                                                                                , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                                                                                                                                , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                                                                                                                               , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                                                                                                                                        , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                                                                                                                                  , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                                                                                                                                         , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                                                                                                                                         , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                                                                                                                                         , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                                                                                                                                        , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                                                                                                                                       , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                                                                                                                                      , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                                                                                                                                     , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                                                                                                                                      , Lu Wang                                                                                                                                                                                                                                                                                                                                             , The only thing that isn’t falling in markets is the price of protection -- complicating the lives of harried traders rushing to hedge.                                                                                                                                                                                                              , The issue is particularly pronounced in equities, where the relative cost of loss-protecting put contracts is as high as its been any time in two years. The benchmark options index in the U.S., know as the VIX, on Monday briefly surged above longer-dated futures -- a relatively rare inversion that occurs when market volatility mushrooms.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/nasdaq-jumps-13-major-indexes/story.aspx?guid={04440D2E-E84C-4DC4-8655-3A2867009EFD}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 04:07:19 </td>
   <td style="text-align:left;"> Nasdaq jumps 1.3% as major indexes close higher after erasing steep losses - MarketWatch </td>
   <td style="text-align:left;"> All three major U.S. stock benchmarks closed higher Monday, recovering from losses earlier in the trading session, as Treasury yields fell and investors appeared to shrug off concerns over China's Covid-19 lockdown. The Nasdaq Composite 
        COMP,
        +1.29%
       led the way higher with a 1.3% gain, followed by the Dow Jones Industrial Average, which finished up 0.7%, according to preliminary FactSet data. The S&amp;P 500 closed with a modest gain of about 0.6%, with mixed results across its 11 sectors. Information technology and communication services booked the biggest gains in the S&amp;P 500 index, while energy was the worst-performing sector Monday, FactSet data show. Major stock benchmarks rose as the yield on the 10-year Treasury note 
        TMUBMUSD10Y,
        2.903%
        fell 8 basis points to 2.825%, the largest one-day decline since March 4 based on 3 p.m. Eastern Time levels, according to Dow Jones Market Data. , After sharp losses Friday, Wall Street is poised for more declines as stock-index futures slid Sunday night.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/elliott-seeks-over-2-billion-war-chest-for-private-equity-deals?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-26 04:05:01 </td>
   <td style="text-align:left;"> Elliott Seeks Over $2 Billion War Chest for Private Equity Deals </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                        , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.    , Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                    , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                                   , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                                   , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                     , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                                , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                                , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                               , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                                  , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                                   , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                          , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                     , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                                   , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                            , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                          , Elon Closes In                                                                                                                                                                                                                                , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                             , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                          , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                          , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                         , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                                  , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                            , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                                   , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                                   , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                                   , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                                  , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                                 , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                                , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                               , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                                , Paul Singer                                                                                                                                                                                                                                   , Photographer: Misha Friedman/Bloomberg                                                                                                                                                                                                        , Gillian Tan and                                                                                                                                                                                                                               , Scott Deveau                                                                                                                                                                                                                                  , Paul Singer’s Elliott Investment Management LP is in talks to raise more than $2 billion to boost its leveraged-buyout efforts, according to people with knowledge of the matter.                                                             , The firm is in talks with institutional backers regarding the vehicle, known as a co-investment commitment fund, which it can draw on for its private equity wagers, said the people, asking not to be identified discussing the fundraising.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-26 04:04:00 </td>
   <td style="text-align:left;"> Canada Stocks End at Near 2-Month Low </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, closed 0.8% down at 21,012 on Monday, the lowest since March 1st, extending losses for the fourth straight session, dragged by the energy and base metal sectors. Market sentiment was dented by renewed concerns about slowing global growth due to worsening pandemic trends in China, as well as the prospect of aggressive tightening of monetary policy by major central banks. Meanwhile, Bank of Canada governor Tiff Macklem signaled that Canada’s key interest rate could go up another half percentage point in June to help wrestle inflation under control. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/25/dining/haribo-gummy-bear.html </td>
   <td style="text-align:left;"> 2022-04-26 03:56:02 </td>
   <td style="text-align:left;"> Gummy Bears, 100 Years On, Are Still Bouncing - The New York Times </td>
   <td style="text-align:left;"> , On its 100th anniversary, the colorful candy has evolved from dancing bears to a booming industry — and for some, a bountiful obsession.                                                                                                                                                                                                                                                                                                                                                                                                             , A gummy “charcuterie” board of bears, butterflies and other creatures by Elizabeth Schmitt, who makes the boards for her Atlanta company, Ruby Bond. Credit...Melissa Golden for The New York Times                                                                                                                                                                                                                                                                                                                                                  , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                       , By Mahira Rivers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Matthew Beverley, an electrical engineer in Mount Pearl, Newfoundland, is known to keep a bag of Haribo gummy candy on his bedside table. There is usually a bag or two in his desk at work. Then there’s the filled plastic bin in his home office, not to mention the scattered loosies.                                                                                                                                                                                                                                                           , Some might say this is a problem. He calls it a collection.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , It took more than four months during the pandemic for Mr. Beverley, 40, to amass his Haribo hoard, which peaked at nearly 120 distinct varieties. Among his most prized are the eccentric Super Gurken gummy pickles and a special 100th-anniversary packet of Haribo’s Goldbears, which he calls “a stone-cold classic.”                                                                                                                                                                                                                            , A century after they were first invented by Haribo in Bonn, Germany, gummy bears remain a sweet, squishy source of joy. But the world of gummies has expanded far beyond that company, into countless corners of modern life.                                                                                                                                                                                                                                                                                                                        , There are gummy versions of sushi and of interlocking blocks that work like Legos. Gummies have wiggled their way into the wellness industry via gummy supplements, an extension of the gummy vitamins that became popular in the 1990s. These are not to be confused with the so-called “better-for-you” gummies that are marketed as candy, but made with added fiber, less sugar, or pectin instead of animal-based gelatin.                                                                                                                      , Others are delivery systems for CBD — or its more potent cousin, THC. Which brings us to boozy gummies, containing small shots of cocktails. Further enhancing the party mood are gummy-inspired kitsch like strings of bear-shaped lights and inflatable pool floats. Social media platforms are rife with taste tests, D.I.Y. recipes and even a catalog of catchy theme songs.                                                                                                                                                                    , “Gummies are the most popular kind of candy,” said Marcia Mogelonsky, a director of insight at the marketing analysis firm Mintel Food &amp; Drink. “It’s not surprising that they are turning up everywhere else. They have a certain resonance. It’s one of those nostalgic things.”                                                                                                                                                                                                                                                                   , It’s also probably a far cry from what the candy maker Hans Riegel had in mind in 1922, when he adapted a recipe for fruit-flavored pastilles to create the first gummy bear (or Gummibär, German for “rubber bear”) for his nascent sweets company, Haribo. The densely chewy, gelatin-based gummies were modeled after real-life dancing bears, a form of entertainment at the time, and later rebranded as Goldbears.                                                                                                                             , Like many German companies, Haribo has come under scrutiny for its operations during World War II. In 2000, Time magazine reported that the candy maker had been “named in the German parliament as having used forced labor,” after it declined to join other German companies in donating money to support surviving enslaved or forced laborers. In 2017, the company said it was investigating assertions that slave labor was being used at plantations in Brazil that supplied the carnauba wax it used to keep gummies from sticking together., In response, Haribo said last week that it had looked into all the allegations and found no evidence that it or its wax suppliers had ever used forced labor. The company said it had helped start an initiative to improve working conditions in production of carnauba wax, and now uses only beeswax.                                                                                                                                                                                                                                             , Gummy candy didn’t take off in the United States until the 1980s.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , In 1981, the Herman Goelitz Candy Company (later renamed Jelly Belly) introduced the first American-made gummy bear. A year later, Haribo set up its first distribution center in the United States. The Indiana-based company Albanese unleashed its famously soft bears in 1983 and soon, gummies abandoned the bear altogether — cue Trolli’s writhing worms and the Sour Patch Kids from Mondelez.                                                                                                                                               , In 1985, the medieval-themed adventures of the Gummi family in Disney’s animated series “Adventures of the Gummi Bears” solidified the candy in the American pop-culture canon — as the theme song put it, “bouncing here and there, and everywhere.”                                                                                                                                                                                                                                                                                                , The pandemic has been a boon for candy makers, as customers turn to the comfort of an inexpensive sugar rush. Sales of chewy candy in the United States, which includes gummies, hit $4.6 billion in 2021, a nearly 15 percent increase from the previous year, according to the market research company IRI. The nation also led the world in gummy sales, followed by China and Germany, according to data from Euromonitor.                                                                                                                       , Gummy fandom is decidedly cross-cultural. And even within the United States, there are an array of regional adaptations.                                                                                                                                                                                                                                                                                                                                                                                                                             , Ashley Garza recalls her teenage years in the Rio Grande Valley in Texas, when she ate commercial gummy bears in raspas, a shaved-ice dessert, and as dulces enchilados, a Mexican American snack of chamoy- and chile-coated candies. “When I was in high school, people were selling little Ziploc bags of gummy bears with chamoy,” she said.                                                                                                                                                                                                     , Ms. Garza, 30, was a grocery clerk at the start of the pandemic, but facing mounting bills, she started a candy company called Texas Chile Dulceria with her boyfriend, Adrian Martinez, 28. He hand-mixes the candy, which includes sweet bears and mouth-puckering sour belts. Each batch starts with a generous drizzle of chamoy, followed by a liberal shower of tart chile seasoning.                                                                                                                                                          , Elizabeth Schmitt, 37, a self-professed gummy fanatic, owns the candy company Ruby Bond, in Atlanta. “Gummy candy is so nostalgic,” she said. “It reminds me of simpler times.’                                                                                                                                                                                                                                                                                                                                                                      , She layers various shapes onto acrylic trays to make candy “charcuterie.” In one of her most popular arrangements, bears are squished alongside an ombré rainbow of stars, butterflies and other springy creatures.                                                                                                                                                                                                                                                                                                                                  , She has an abundance of choices: oozy jelly-filled shapes, super-sour chews and foamy, marshmallowy creations. She leans toward the softer varieties with vivid colors.                                                                                                                                                                                                                                                                                                                                                                              , “Not all gummy candies are created equal,” she said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Novelty candy shops across the country and online are treasure troves for more extreme takes, from one bear that weighs in at about five pounds to a scorchingly spicy counterpart that reaches nine million units on the Scoville scale.                                                                                                                                                                                                                                                                                                            , Jessica Stevenson, 34, owns a candy shop called Hello, Sweets with her husband, Tyler, in Tonawanda, N.Y. The couple sometimes post videos of their favorite candy to social media, spurring intense debates in the comments section over issues like the merits of a rigorous chew versus a supple one.                                                                                                                                                                                                                                             , “Everybody has very strong opinions about candy,” Ms. Stevenson said                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , TikTok is a rabbit hole of gummy candy ephemera. The platform’s subculture known as Candytok is full of videos in which gummies are poured into a container on an endless loop. One such video that Ms. Stevenson posted to her store’s account in 2021 shows a pile of brightly colored bears noisily tumbling into a metal bowl in a gleaming heap. As of Monday, it had more than 660,000 views.                                                                                                                                                  , TikTok’s audience skews young, a reminder that gummy bears were originally fashioned to appeal to children. Adults, Ms. Stevenson said, tend to be pickier and a little more obsessive about their candy.                                                                                                                                                                                                                                                                                                                                            , In her 2012 book, “Sweet Tooth: The Bittersweet History of Candy,” the historian Kate Hopkins elaborates on the deep connection adults have with candy: “Innocence lost rarely can return, and the years of joy that the ignorance of childhood brings is a luxury that we, as adults, cannot afford.”                                                                                                                                                                                                                                               , Sometimes the best we can do, Ms. Hopkins writes, is to have a piece of something sweet, and revel in a moment when “nothing else matters except the self and that joy that a sugar fix can bring.”                                                                                                                                                                                                                                                                                                                                                  , The physical qualities of gummy candies — their tenderness and the soothing sound as they’re chewed — might serve as a cushion for the hard-edge realities of adult life.                                                                                                                                                                                                                                                                                                                                                                            , Mr. Beverley, the collector in Newfoundland, has finally started to dip into his stash. Unlike sharing his music and movie collections with friends, he said, opening a bag of candy is more likely to elicit a smile. He likes to dole out bags of Goldbears or Sour Cherries to neighbors, co-workers — or anyone, really.                                                                                                                                                                                                                         , “There’s a joy in collecting it,” he said, “and there’s also a joy in sharing it.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Follow NYT Food on Twitter and NYT Cooking on Instagram, Facebook, YouTube and Pinterest. Get regular updates from NYT Cooking, with recipe suggestions, cooking tips and shopping advice.                                                                                                                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-concerned-about-social-medias/story.aspx?guid={57C73C95-3DE4-4B5B-A8E4-A6FFDFEE7C2F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 03:41:02 </td>
   <td style="text-align:left;"> Biden 'concerned' about social media's power, regardless of who owns Twitter, White House says  - MarketWatch </td>
   <td style="text-align:left;"> White House press secretary Jen Psaki on Monday said President Joe Biden has concerns about social-media companies' power after Twitter's 
        TWTR,
        +5.66%
       board agreed to a sale to billionaire Elon Musk. "No matter who owns or runs Twitter, the president has long been concerned about the power of large social-media platforms -- with the power they have over our everyday lives," Psaki told reporters during a briefing. "He has long argued that tech platforms must be held accountable for the harms they cause." She said she wouldn't comment on "what hypothetical policies might happen," such as Musk possibly reinstating former President Donald Trump's Twitter account. , Elon Musk’s move to buy Twitter has sparked chatter about former President Donald Trump getting reinstated on the platform, but Trump says he has no interest in returning.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-61222793?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-26 03:38:22 </td>
   <td style="text-align:left;"> Twitter: Why Elon Musk has been so keen on taking control </td>
   <td style="text-align:left;"> At first, the story of Twitter and Elon Musk feels a little like a tale of unrequited love.                                                                                                                                                                                                                                                                                                                  , Our unlikely couple starts out with an imbalance of power.                                                                                                                                                                                                                                                                                                                                                   , Elon Musk loves Twitter. He has an enormous audience of 83.8m followers. He tweets prolifically, sometimes controversially, occasionally catastrophically. The SEC banned him from tweeting about Tesla affairs after one tweet wiped $14bn off its share price, and he was sued for defamation following a tweet about a cave diver in which he called him "pedo guy" (the cave diver lost).                , But he has never strayed far from his keyboard.                                                                                                                                                                                                                                                                                                                                                              , Twitter on the other hand is far less effusive about Elon Musk.                                                                                                                                                                                                                                                                                                                                              , You might think, if someone offered you $44bn for a 16-year-old business that hadn't really enjoyed the exponential growth of its rivals, they were doing you a favour - and Twitter's shareholders seem inclined to agree.                                                                                                                                                                                  , He wants to see Twitter fulfil its "extraordinary potential", he says - and he's not even that interested in making money out of it. He has plenty of that already, and multi-billionaires can afford to have different priorities.                                                                                                                                                                          , Twitter responded by going straight on the defensive, deploying a "poison pill" strategy which prevented anybody from owning more than 15% of its shares while Musk circled, though a deal has now been agreed.                                                                                                                                                                                              , Why?                                                                                                                                                                                                                                                                                                                                                                                                         , Perhaps the board was unnerved by Musk's declaration that he wanted to see more "free speech" and less moderation. Many Republicans, who have long felt that Twitter's moderation policies favour the freedom of speech of left-leaning viewpoints, rejoiced.                                                                                                                                                , But regulators around the world are lining up to crack down on social networks and force them to take more responsibility for the content they carry, issuing steep fines for non-compliance on material that incites violence, or is abusive, or classifies as hate speech, among other things. You can hear the alarm bells start to ring.                                                                 , Let's not forget the finances. Twitter's main business model is ad-based - and Musk wants to change that. He's more interested in subscriptions, he claims, which could prove a hard sell in an environment where all the main social networks are free-to-use. Twitter users may decide they prefer for their data to not be used to monetise them and they're willing to pay for that - but it's a gamble. , He also likes crypto-currencies. Could he use the platform to incentivise payments in volatile, unprotected currencies such as Bitcoin?                                                                                                                                                                                                                                                                      , And then there's Musk himself. He's the richest man in the world, a serial entrepreneur whose successes include PayPal and Tesla. He's charismatic and unfiltered - which can make him a very loose cannon indeed. He likes to test boundaries and break rules.                                                                                                                                              , There's a reason why he declined to join Twitter's board after buying a 9.2% stake in January - he didn't want to be bound by the responsibility.                                                                                                                                                                                                                                                            , And he has an army of loyal fans who adore him - I once tweeted about the fact that, because of the way his finances are structured (his wealth is largely shares-based rather than cash income, and he doesn't own property) - he doesn't pay income tax.                                                                                                                                                   , How dare I suggest that he might, he's brilliant and we should simply be grateful for him, came the replies.                                                                                                                                                                                                                                                                                                 , He has not exactly wooed Twitter with flowers and chocolates, this has been an aggressive bid from an aggressive businessman - no negotiation, no compromise.                                                                                                                                                                                                                                                , It's a private sale, of a private company, and it's not a merger between two giants so there is unlikely to be much in the way of regulatory obstacles.                                                                                                                                                                                                                                                      , Musk's Twitter would be a very different landscape for the 300 million people who continue to use it, if indeed they do. More feisty, perhaps, and less liberal-leaning. He could reinstate Donald Trump, who currently has a permanent ban - and given that Mr Trump's own attempt at a social network, Truth Social, appears to be floundering, he would probably be delighted to return.                  , It's hard to summarise the collective view of Twitter's users. In my unscientific observation, for every tweet welcoming Musk, there seems to be another threatening to leave. But then - since when did Twitter users ever agree on anything?                                                                                                                                                               , How many miles do you need to drive before it pays off?                                                                                                                                                                                                                                                                                                                                                      , Gary Lineker on football, politics and road rage                                                                                                                                                                                                                                                                                                                                                             , Searching for Vladislav Surkov, key architect of the 'post truth' world                                                                                                                                                                                                                                                                                                                                      , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-04-26 03:24:01 </td>
   <td style="text-align:left;"> Natural gas is up by 5.04% </td>
   <td style="text-align:left;"> Natural gas increased 5.04% to 6.857 USD/MMBtu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/consumer-financial-protection-bureau-prepares/story.aspx?guid={75822D5A-0DDD-4722-BDF7-D54C93663B2B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 03:05:00 </td>
   <td style="text-align:left;"> Consumer Financial Protection Bureau prepares to study practices by non-bank lenders - MarketWatch </td>
   <td style="text-align:left;"> The Consumer Financial Protection Bureau (CFPB) said Monday it's tapping a mostly unused legal provision to examine nonbank financial companies that pose risks to consumers. "The CFPB believes that utilizing this dormant authority will help protect consumers and level the playing field between banks and nonbanks," it said in a prepared statement. The CFPB is also seeking public comments on a procedural rule to make the examination process more transparent.  CFPB director Rohit Chopra said the CFPB is tapping an authority it received under the Dodd-Frank legislation to use traditional law enforcement to prevent companies from posing risks to consumers. "This authority gives us critical agility to move as quickly as the market, allowing us to conduct examinations of financial companies posing risks to consumers and stop harm before it spreads," Chopra said. The Financial Select Sector SPDR ETF 
        XLF,
        +0.17%
       is down 7.8% in 2022, compared to drop of 10.6% by the S&amp;P 500 
        SPX,
        +0.57%.
      , The Fed clobbered stocks, with the S&amp;P 500 and Nasdaq Composite down for the third straight week, and the Dow Jones Industrial Average notching its fourth straight losing week.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/tesla-shares-dip-after-ceo/story.aspx?guid={E9A7E591-2CF4-44BF-AB38-BA2B81A0E1FD}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 03:00:50 </td>
   <td style="text-align:left;"> Tesla shares dip after CEO Elon Musk reaches deal to acquire Twitter - MarketWatch </td>
   <td style="text-align:left;"> Tesla Inc. shares 
        TSLA,
        -0.70%
       dipped slightly in afternoon trade, after Chief Executive Elon Musk reached an agreement to acquire Twitter Inc. 
        TWTR,
        +5.66%,
       raising concerns about how much he will be distracted in running the electric car company. The stock, which opened at $978.97 and touched an intraday high of $1,008.62, was last down 1.3% at $991.30. The news was expected after media reports said the Twitter board was close to agreeing a deal. Musk had made a bid for the company at $54.20 a share, which has now been accepted. He has secured $25.5 billion of debt and margin loan financing and is providing about $21 billion in equity himself. Musk said he wants to make Twitter better, "by enhancing the product with new features, making the algorithms open source to increase trust, defeating the spam bots, and authenticating all humans." Tesla shares are down 6% in the year to date, while the S&amp;P 500 
        SPX,
        +0.57%
       has fallen 10%., Musk claimed in tweets that Gates' short selling conflicts with his social goals.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Ciara Linnane is MarketWatch's investing- and corporate-news editor. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/elon-musk-clinches-deal-to-take-twitter-private-for-44-billion </td>
   <td style="text-align:left;"> 2022-04-26 02:53:58 </td>
   <td style="text-align:left;"> Elon Musk Lands Deal to Take Twitter Private for $44 Billion </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                                                                              , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                          , Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                                                                          , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                                                                                         , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                                                                                         , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                                                                           , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                                                                                      , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                                                                                      , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                                                                                     , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                                                                                        , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                                                                                         , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                                                                                , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                                                                           , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                                                                                         , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                                                                                  , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                                                                                , Elon Closes In                                                                                                                                                                                                                                                                                      , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                                                                                   , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                                                                                , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                                                                                , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                                                                               , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                                                                                        , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                                                                                  , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                                                                                         , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                                                                                         , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                                                                                         , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                                                                                        , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                                                                                       , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                                                                                      , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                                                                                     , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                                                                                      , Kurt Wagner                                                                                                                                                                                                                                                                                         , Billionaire entrepreneur Elon Musk agreed to buy Twitter Inc. for $44 billion, using one of the biggest leveraged buyout deals in history to take private a 16-year-old social networking platform that has become a hub of public discourse and a flashpoint in the debate over online free speech., Investors will receive $54.20 for each Twitter share they own, the company said in a statement Monday. The price is 38% more than the stock’s close on April 1, the last business day before Musk disclosed a significant stake in the company, sparking a share rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-track-biggest-intraday-bounce/story.aspx?guid={58FE6165-911C-4F7F-8AED-A7BD566D7D16}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 02:50:11 </td>
   <td style="text-align:left;"> Dow on track for biggest intraday bounce since February as it erases 488-point loss - MarketWatch </td>
   <td style="text-align:left;"> A stock-market selloff took a breather Monday afternoon, with the Dow Jones Industrial Average on track for its biggest intraday bounce-back from negative territory since February. The blue-chip gauge tumbled sharply in early trade, falling 487.7 points, or 1.44%, at its session low, before turning higher in afternoon action. The Dow 
        DJIA,
        +0.70%
       was up 40 points, or 0.1%, at 33,852 in midafternoon activity. The last time the Dow was down that much on an intraday basis and closed higher was on Feb. 24, when it fell as much as 2.59% but ended the day up 0.28%, according to Dow Jones Market Data. The move comes after the Dow ended nearly 1,000 points lower on Friday, leaving it with its biggest one-day percentage decline since October 2020. The S&amp;P 500 
        SPX,
        +0.57%
       was down 0.2% near 4,263, while the Nasdaq Composite 
        COMP,
        +1.29%
       rose 0.5% to 12,908., The social media company said on Monday it had accepted the Tesla chief executive’s takeover bid.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-26 02:39:00 </td>
   <td style="text-align:left;"> Wall Street Turns Positive </td>
   <td style="text-align:left;"> US stocks pared losses on Monday as a retreat in bond yields boosted the tech stocks. The Dow  The Dow gained as many as 238 points, after being down almost 490 points earlier in the session, the Nasdaq was up 1.3% while the S&amp;P 500 gained 0.6%. Stocks sunk at the open as investors remained concerned about Covid-19 lockdowns in China and inflation currently running at a 4-decades high, which has already prompted the Federal Reserve to signal big increases in the Fed funds rate this year. Among single stocks, Twitter shares climbed more than 6% after the board accepted Elon Musk’s offer to buy the social media company and take it private. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/cross-asset-volatility-spikes-all-over-the-world-on-growth-fears?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-26 02:36:31 </td>
   <td style="text-align:left;"> Cross-Asset Volatility Spikes All Over the World on Growth Fears </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                                                                                         , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                     , Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                                                                                     , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                                                                                                    , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                                                                                                    , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                                                                                      , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                                                                                                 , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                                                                                                 , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                                                                                                , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                                                                                                   , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                                                                                                    , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                                                                                           , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                                                                                      , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                                                                                                    , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                                                                                             , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                                                                                           , Elon Closes In                                                                                                                                                                                                                                                                                                 , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                                                                                              , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                                                                                           , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                                                                                           , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                                                                                          , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                                                                                                   , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                                                                                             , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                                                                                                    , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                                                                                                    , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                                                                                                    , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                                                                                                   , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                                                                                                  , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                                                                                                 , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                                                                                                , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                                                                                                 , Emily Graffeo                                                                                                                                                                                                                                                                                                  , Markets around the world are in the throes of volatility, as growth fears in China break out just as Wall Street grapples with ever-more hawkish monetary policy in the age of elevated inflation.                                                                                                             , U.S. stock fluctuations measured by the Cboe Volatility Index, or VIX, spiked to the highest level since mid-March in Monday trading. Yields on 10-year Treasuries broke a three-week slump to trade as much as 14 basis points lower. A broad measure of currency fluctuations is near its highest in a month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-futures-fall-sharply-us/story.aspx?guid={93AA7E05-EFD2-44E8-A5C8-4917003FA05C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 02:35:29 </td>
   <td style="text-align:left;"> Oil futures fall sharply, with U.S. prices ending at a 2-week low - MarketWatch </td>
   <td style="text-align:left;"> Oil futures finished sharply lower on Monday, with U.S. benchmark prices marking their lowest finish since two weeks. Oil sold off amid the ongoing lockdowns in Shanghai and other parts of China, "seriously denting petroleum demand there," said Marshall Steeves, energy markets analyst at S&amp;P Global Commodity Insights. "This really illustrates the supremacy of the demand fears related to China over concerns related to Russian oil exports." West Texas Intermediate crude for June delivery 
        CLM22,
        +0.11%
       fell $3.53, or 3.5%, to settle at $98.54 a barrel on the New York Mercantile Exchange, the lowest front-month finish since April 11, FactSet data show.                                                                                                                                                                                                                                                             , Twitter Inc. undefined shares rose 5% premarket Monday, after Reuters said the  social media site is set to accept Tesla Inc. undefined CEO Elon Musk's "best and final" offer to buy the company. Musk said last week he had lined up $46.5 billion in financing to back his bid for the company announced April 14, when he offered $54.20 a share. Musk has criticized the company for failing to live up to its potential as a platform for free speech. But Musk himself has used Twitter to start a spat with the Securities and Exchange Commission, with a famous tweet in which he claimed he had "funding secured" to take Tesla private. And Twitter enacted a poison pill that would make it expensive to take full control of the company. Reuters cited unnamed people who are familiar with the matter and said an announcement could come as early as today. Twitter shares are up 13% in the year to date, while the S&amp;P 500 undefined has fallen 10%. , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/business/2022/04/25/elon-musk-silicon-valley-interview-2001-vault-orig.cnn </td>
   <td style="text-align:left;"> 2022-04-26 02:29:14 </td>
   <td style="text-align:left;"> Elon Musk in 2001: I'm a little tired of the internet - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/fda-formally-approves-gileads-veklury/story.aspx?guid={E796F036-2576-4E03-936A-3FC009CD80EA}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 02:20:19 </td>
   <td style="text-align:left;"> FDA formally approves Gilead's Veklury for young children - MarketWatch </td>
   <td style="text-align:left;"> The Food and Drug Administration said Monday it expanded the approval of Gilead Sciences Inc.'s 
        GILD,
        +0.64%
       Veklury to include pediatric patients between the ages of four weeks and 12 years old. (Infants must also weigh at least seven pounds.) Veklury is a COVID-19 treatment for patients who have been hospitalized or who have mild or moderate infections but are at high risk of severe COVID-19. The drug previously received emergency authorization for this group of pediatric patients. "As COVID-19 can cause severe illness in children, some of whom do not currently have a vaccination option, there continues to be a need for safe and effective COVID-19 treatment options for this population," Patrizia Cavazzoni, director of the FDA's Center for Drug Evaluation and Research, said in a news release. Gilead's stock is down 14.7% this year, while the broader S&amp;P 500 
        SPX,
        +0.57%
       has declined 10.3%., Here's what to know.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/money/workers-changing-jobs-are-receiving-massive-pay-increases-analysis-shows </td>
   <td style="text-align:left;"> 2022-04-26 02:20:08 </td>
   <td style="text-align:left;"> Workers changing jobs are receiving massive pay increases, analysis shows </td>
   <td style="text-align:left;"> Labor Secretary Marty Walsh ackowledges there is 'work to do' on the jobs front, but argues overall the March employment report was 'strong.'                                                                                                                                                                                                                                                                                                 , Americans who switched jobs this year are often receiving double-digit pay increases, according to a new survey, underscoring how the tightest labor market in years has empowered workers – while also fueling inflation.                                                                                                                                                                                                                    , A new ZipRecruiter survey shows that 64.2% of recently hired Americans received a pay raise at their new jobs, compared with just 21% who actually saw a wage cut. Among those workers who received a wage hike, nearly half – about 47.9% – received a substantial raise of 11% or more.                                                                                                                                                     , S&amp;P 500 ABOUT TO FALL SHARPLY AS IT TEETERS ON BRINK OF BEAR MARKET, MORGAN STANLEY SAYS                                                                                                                                                                                                                                                                                                                                                      , On top of that, 22% of job switchers reported getting a signing bonus. Among first-time hires, the number is actually even higher at 33%.                                                                                                                                                                                                                                                                                                     , "This is really remarkable," said Julia Pollak, chief economist at ZipRecruiter. "Before the pandemic, these kinds of bonuses were rare."                                                                                                                                                                                                                                                                                                     , A large "Now Hiring" advertisement posted on the windows of the Advance Auto Parts store in Bay Shore, New York, on March 24, 2022.  (Steve Pfost/Newsday RM via Getty Images / Getty Images)                                                                                                                                                                                                                                                 , Bonuses were previously used infrequently to recruit top talent in the most senior roles, Pollak said; in 2000 for instance, just 4% of private-sector workers had received a signing incentive, according to Labor Department data. What's more, prior to February 2020, only 2% to 3% of jobs on ZipRecruiter explicitly offered signing bonuses in their job postings. That figure is now about 12%.                                       , The data emphasizes how newly empowered workers are quitting their jobs in favor of better wages, working conditions and hours as businesses lure new workers with higher salaries – a trend dubbed the "Great Resignation." As a result, Americans' incomes are rising across the board as employers have ramped up hiring to offset the losses or try to out-compete other businesses for workers.                                          , The Labor Department reported last month that 4.4 million Americans, or about 2.9% of the workforce, quit their jobs in February. Meanwhile, the number of job openings fell slightly to 11.3 million by the end of February – the third-highest level on record. In fact, the number of available jobs has topped 10 million for seven consecutive months; before the pandemic began in February 2020, the highest on record was 7.7 million., As a result, wages are rising across the board: Annual wage growth for the average worker hit 6% in March, according to the Federal Reserve Bank of Atlanta’s wage tracker. That's up from 3.4% in the year-ago period.                                                                                                                                                                                                                       , A hiring sign is displayed outside a retail store in Buffalo Grove, Illinois, on June 24, 2021. (AP Photo/Nam Y. Huh, File / AP Newsroom)                                                                                                                                                                                                                                                                                                     , The concern is that higher wages are exacerbating already sky-high inflation, which surged 8.5% in March from the previous year, according to the Labor Department. Some economists have warned that rising wages could fuel even higher inflation – a jarring possibility, given that consumer prices already surged 7.5% in January, the fastest pace since February 1982.                                                                  , The combination of high inflation and rising wages has fueled concern about the possibility of a wage-price spiral, a 1970s-style phenomenon where high inflation leads to pay hikes, which in turn lead to more spending and more expensive prices.                                                                                                                                                                                          , Federal Reserve Chairman Jerome Powell has warned of growing supply-and-demand imbalances in the labor market, with the unemployment rate tumbling from to 3.6% in March from 6% the previous year.                                                                                                                                                                                                                                           , "It’s too hot. It’s unsustainably hot," Powell said last week during an annual meeting between the International Monetary Fund and the World Bank. "It’s our job to get it to a better place where supply and demand are closer together."                                                                                                                                                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                   , As a result, the Fed is taking an increasingly hawkish approach to fighting inflation, which is at the highest level since December 1981. Policymakers raised rates by a quarter-percentage point in March, and have since signaled that sharper, half-point increases are likely in the coming months, beginning in May.                                                                                                                     , "It is appropriate to be moving a little more quickly," Powell said. "I also think there’s something in the idea of front end-loading whatever accommodation one thinks is appropriate. So that points in the direction of 50-basis points being on the table." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/breakfast-gets-pricier-as-u-s-agency-hikes-food-price-forecasts?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-26 02:12:59 </td>
   <td style="text-align:left;"> Breakfast Gets Costlier as U.S. Ratchets Up Food-Price Forecasts </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                    , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                               , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                               , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                 , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                            , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                            , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                           , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                              , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                               , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                      , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                 , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                               , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                        , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                      , Elon Closes In                                                                                                                                                                                                                            , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                         , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                      , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                      , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                     , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                              , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                        , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                               , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                               , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                               , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                              , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                             , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                            , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                           , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                            , Photographer: Alexander Spatari/Moment RF/Getty Images                                                                                                                                                                                    , Alexandre Tanzi                                                                                                                                                                                                                           , Diners may want to think twice about going for an American breakfast, which is poised to get pricier this year in the U.S. Department of Agriculture’s latest monthly projections.                                                        , Choosing a cereal option, or going for fresh fruits, won’t provide relief, either. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/real-estate/blackstone-buy-ps-business-parks-billions-take-private-deal </td>
   <td style="text-align:left;"> 2022-04-26 01:59:46 </td>
   <td style="text-align:left;"> Blackstone to buy PS Business Parks in $7.6B take-private deal </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.                                                                                                                                                                                                                  , Blackstone Inc on Monday agreed to buy real estate investment trust (REIT) PS Business Parks for $7.6 billion, including debt, as dealmaking activity in the real estate sector continues to thrive in the aftermath of the COVID-19 pandemic.                 , As part of the take-private deal, Blackstone said its real estate affiliates will pay $187.50 cash to shareholders of PS Business Parks, representing a 12% premium from the stock's closing price last week.                                                  , California-headquartered PS Business Parks operates a portfolio of industrial, business parks, office buildings, and multifamily properties located across California, Florida, Texas and northern Virginia.                                                   , SOARING INTEREST RATES CREATE 'BARRIER TO THE AMERICAN DREAM': FORMER INVESTMENT BANKER                                                                                                                                                                        , Mergers and acquisitions (M&amp;A) activity involving REITs reached a record high in 2021, driven by a robust U.S. housing market, availability of cheap capital from low interest rates, and strong economic recovery from the pandemic.                          , Blackstone, the world's largest real estate investor, has been a prolific acquirer of REITs, helping drive transaction volumes in the sector to $140 billion in 2021, up from $17 billion in the previous year, according to real estate services provider JLL., New York, June 27, 2016: Manhattan office location of Blackstone hedge fund.                                                                                                                                                                                   , Blackstone has already agreed to buy three REITs this year alone. Last week, it struck a deal to acquire student housing REIT American Campus Communities Inc in a $12.8 billion deal.                                                                         , RENTAL AND HOME PRICES EXPECTED TO RISE EVEN MORE THIS YEAR, FORCING SOME TO PACK UP AND MOVE                                                                                                                                                                  , It also agreed to pay $5.8 billion cash to buy multifamily housing REIT Preferred Apartment Communities in February, and in January, it announced a deal to purchase non-publicly traded Resource REIT Inc for $3.7 billion.                                   , Blackstone said its acquisition of PS Business Parks is expected to close in the third quarter of this year.                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                    , Simpson Thacher &amp; Bartlett LLP, Wachtell, Lipton, Rosen &amp; Katz, J.P. Morgan, and Eastdil Secured acted as advisers on the transaction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-mark-lowest-finish/story.aspx?guid={CA5A22FF-ADF0-4D2E-8B75-A12F6EF576A8}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 01:54:23 </td>
   <td style="text-align:left;"> Gold futures mark lowest finish in about 2 months - MarketWatch </td>
   <td style="text-align:left;"> Gold futures fell on Monday to mark their lowest settlement in roughly two months. Strength in the U.S. dollar pressured prices for the precious metal, with the ICE U.S. dollar index 
        DXY,
        +0.51%
       trading as high as 101.86, the highest since March 2020. June gold 
        GCM22,
        +0.28%
       fell $38.30, or 2%, to settle at $1,896 an ounce, the lowest most-active contract finish since Feb. 25, FactSet data show., Here's what to know.                                                                                                                                                                                                                                                                                                                                                                                                                                                , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-26 01:45:00 </td>
   <td style="text-align:left;"> Mexico 10Y Bond Yield Hits 3-Year High </td>
   <td style="text-align:left;"> Mexico’s 10-year government bond yield crossed 8.95% for the first time since December of 2018, as investors continued to ditch government debt amid lingering concerns that rising food prices could tip the country into recession. The central bank of Mexico has increased interest rates at its last seven meetings, aiming to curb inflationary pressures due to the war in Ukraine. Meanwhile, President Andres Manuel Lopez Obrador said that he will present a plan in a week that will make prices of Mexican staples less exposed to foreign markets, by helping farmers to boost local production. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-26 01:44:00 </td>
   <td style="text-align:left;"> Wall Street Trades Mostly Lower </td>
   <td style="text-align:left;"> US stocks pared some losses on Monday but mostly remained in the negative territory with Dow Jones down more than 200 points in the afternoon trade, S&amp;P declining almost 1%, and Nasdaq attempting to hold small gains. Investors remained concerned about Covid-19 lockdowns in China and inflation currently running at a 4-decades high, which has already prompted the Federal Reserve to signal big increases in the Fed funds rate this year. Among single stocks, Twitter shares climbed more than 6% on reports the company is in advance talks to sell itself to Elon Musk and a deal could be reached as soon as Monday. Meanwhile, financials and energy shares led the sell-off with crude oil prices retreating more than 6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/trump-held-contempt-court-ordered/story.aspx?guid={43396BAA-A14B-468A-B1B8-D1DA64A5322B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 01:04:07 </td>
   <td style="text-align:left;"> Trump held in contempt of court, ordered to pay $10,000 a day over failing to comply with subpoena - MarketWatch </td>
   <td style="text-align:left;"> Former President Donald Trump has been held in contempt of court by a New York judge for failing to comply with a subpoena related to a probe by the state attorney general's office, and must pay $10,000 a day as long as he doesn't comply, reports said Monday. Judge Arthur Engoron said Trump's attorneys failed to show how a search of materials held by Trump was conducted, according to CNN. Engoron said Trump would be fined $10,000 a day until he complies. New York Attorney General Letitia James has been investigating the Trump Organization for more than two years. , Trillions of dollars will be unavailable for schools, housing, healthcare, childcare and fighting the climate crisis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/25/-stocks-making-the-biggest-moves-midday-twitter-amd-deere-verizon-and-more.html </td>
   <td style="text-align:left;"> 2022-04-26 01:03:11 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Twitter, AMD, Deere, Verizon and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                             , Twitter — Shares of the social media rose 5.7% on news that Twitter would accept a buyout from Elon Musk to take the company private for $54.20 per share.                                                                                                                                                                                                                                              , Penn National Gaming — Shares of the casino and online betting company rose 4.9% after an upgrade from Morgan Stanley. The investment firm hiked its rating to overweight, saying that the recent slump for Penn National's stock made it an attractive valuation and that the company has a better strategy for gaining sports-betting customers than its competitors.                                 , Oil stocks — Energy stocks dipped amid renewed fears of a global slowdown as the country grapples with a Covid outbreak. Shares of Chevron and Exxon Mobil fell 2.2% and 3.4%, respectively.                                                                                                                                                                                                            , Advanced Micro Devices, Marvell — AMD's stock rallied 2.9% after Raymond James upgraded it to outperform and said its stock could surge 80%. Raymond James also upgraded Marvell to market perform, which sent shares up 3.9%                                                                                                                                                                           , Verizon — The stock fell nearly 3.1% after Goldman Sachs downgraded Verizon to neutral from buy on valuation, following a big subscriber loss for the telecom giant. Goldman said Verizon is positioned to remain a wireless leader in the 5G cycle but also anticipates a slowdown in revenue growth.                                                                                                  , Snowflake — Shares surged 7.6% after Wolfe Research initiated coverage of the cloud data company with an outperform rating. The stock, which is trading at "Black Friday prices," could get a boost at its upcoming analyst day, the analyst said. Wolfe expects new product reveals, as well as updated guidance on how Snow will reach $10 billion in annual product revenues by the 2029 fiscal year., ThredUp — Shares of the resale stock dipped 2.3% following a downgrade from a buy to neutral rating by Goldman Sachs, which cited near-term headwinds.                                                                                                                                                                                                                                                  , Activision Blizzard — The videogame publisher's stock moved 0.7% lower after missing analyst estimates in the first quarter. Activision Blizzard cited disappointing demand for its "Call of Duty: Warzone" among the contributors to the weak earnings.                                                                                                                                                , Deere — Shares tumbled 4.5% after Bank of America downgraded the stock to neutral from buy. Analysts said they see limited upside for the agricultural machinery stock, which could get hit by rising fertilizer prices amid the ongoing conflict in Ukraine.                                                                                                                                           , GoDaddy — The stock ticked 4.5% higher after Piper Sandler upgraded the company to overweight from neutral, calling it a top defensive idea. The firm also said the website domain company has strong free cash flow potential, and it likes GoDaddy's $3B capital return strategy for the next three years.                                                                                            , Formula One — Shares rose marginally higher after Citi downgraded the stock to neutral and said there is little upside left to gain.                                                                                                                                                                                                                                                                    , — CNBC's Sarah Min, Tanaya Macheel and Jesse Pound contributed reporting.                                                                                                                                                                                                                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/dip-buyers-bail-on-china-tech-etf-as-faith-in-rebound-wanes?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-26 00:58:33 </td>
   <td style="text-align:left;"> Dip Buyers Bail on China Tech ETF as Faith in Rebound Wanes </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                                                                                                                                                                                                                      , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                                                                                                                                  , Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                                                                                                                                                                                                                  , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                                                                                                                                                                                                                                 , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                                                                                                                                                                                                                                 , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                                                                                                                                                                                                                   , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                                                                                                                                                                                                                              , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                                                                                                                                                                                                                              , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                                                                                                                                                                                                                             , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                                                                                                                                                                                                                                , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                                                                                                                                                                                                                                 , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                                                                                                                                                                                                                        , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                                                                                                                                                                                                                   , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                                                                                                                                                                                                                                 , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                                                                                                                                                                                                                          , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                                                                                                                                                                                                                        , Elon Closes In                                                                                                                                                                                                                                                                                                                                                                                                                              , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                                                                                                                                                                                                                           , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                                                                                                                                                                                                                        , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                                                                                                                                                                                                                        , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                                                                                                                                                                                                                       , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                                                                                                                                                                                                                                , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                                                                                                                                                                                                                          , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                                                                                                                                                                                                                                 , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                                                                                                                                                                                                                                 , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                                                                                                                                                                                                                                 , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                                                                                                                                                                                                                                , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                                                                                                                                                                                                                               , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                                                                                                                                                                                                                              , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                                                                                                                                                                                                                             , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                                                                                                                                                                                                                              , Isabelle Lee                                                                                                                                                                                                                                                                                                                                                                                                                                , Dip buyers have gone AWOL during the latest slide in Chinese tech stocks.                                                                                                                                                                                                                                                                                                                                                                   , After months of seizing on virtually every decline to pile into the KraneShares CSI China Internet Fund (ticker KWEB) -- a $5.4 billion U.S. exchange-traded fund that buys Hong Kong and New York-listed shares -- investors have pulled $19 million so far in April. While that’s a tiny amount for the fund, it puts KWEB on course for its first monthly outflow of 2022 despite another double-digit monthly slide, its third straight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-25/treasury-tax-season-provides-preview-of-fed-balance-sheet-unwind?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-26 00:45:59 </td>
   <td style="text-align:left;"> Treasury Tax Season Provides Preview of Fed’s Balance Sheet Unwind </td>
   <td style="text-align:left;"> Bloomberg Daybreak Australia. Live from New York and Sydney. The latest news impacting markets, business and finance around the world.                                                                                                                                                                                                                                                                                                                      , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                                                                                                                                                  , Climate change is increasingly threatening cities with catastrophic flooding. Many are now looking to Rotterdam, and its long history of innovation when it comes to holding water at bay.                                                                                                                                                                                                                                                                  , Australia Briefing: Interest Rates in Focus                                                                                                                                                                                                                                                                                                                                                                                                                 , Trump Ex-Broker Ordered to Comply With N.Y. Probe Subpoenas                                                                                                                                                                                                                                                                                                                                                                                                 , Elon Musk and Twitter: What We Know, What We Don’t About $44 Billion Deal                                                                                                                                                                                                                                                                                                                                                                                   , Fisker CEO’s Twitter Account Disappears After Musk Acquisition                                                                                                                                                                                                                                                                                                                                                                                              , Twitter CEO Says It’s Business as Usual Until Musk Deal Closes                                                                                                                                                                                                                                                                                                                                                                                              , U.K.’s Johnson Demands ‘Innovative’ Solutions on Cost of Living                                                                                                                                                                                                                                                                                                                                                                                             , DeSantis Signals More Disney Action Ahead After ‘First Step’                                                                                                                                                                                                                                                                                                                                                                                                , Twitter Under Elon Musk Threatens to End Trump’s Truth Social Media Venture                                                                                                                                                                                                                                                                                                                                                                                 , Warren Buffett to Host Final Charity Lunch for San Francisco’s Glide                                                                                                                                                                                                                                                                                                                                                                                        , Mickelson Signs Up for 3 Events Without Saying He'll Play                                                                                                                                                                                                                                                                                                                                                                                                   , Biden Avoids Politics in Honoring Hockey Champion Lightning                                                                                                                                                                                                                                                                                                                                                                                                 , What Disney Can Teach Microsoft in the Gaming Wars                                                                                                                                                                                                                                                                                                                                                                                                          , Elon Musk and Twitter Are Not a Match Made in Heaven                                                                                                                                                                                                                                                                                                                                                                                                        , Elon Closes In                                                                                                                                                                                                                                                                                                                                                                                                                                              , This Earnings Season Will Be a Weird One for Industrial Companies                                                                                                                                                                                                                                                                                                                                                                                           , Why Nasal Sprays Are Poised to Be the Next Weapon for Fighting Covid                                                                                                                                                                                                                                                                                                                                                                                        , Everything You Need to Know About Netflix’s Big Miss                                                                                                                                                                                                                                                                                                                                                                                                        , Divided Supreme Court Allows Selective High School’s Diversity Policy                                                                                                                                                                                                                                                                                                                                                                                       , Amazon Union Election Kicks Off at Second New York Warehouse                                                                                                                                                                                                                                                                                                                                                                                                , Exxon Executive Is ‘Crushed’ at Hurt Caused by Pride Flag Decision                                                                                                                                                                                                                                                                                                                                                                                          , Climate Votes Fought by Major Oil Companies Get Key Backing                                                                                                                                                                                                                                                                                                                                                                                                 , John Kerry Touts Global Warming Cap He Once Called Too Weak                                                                                                                                                                                                                                                                                                                                                                                                 , Free Public Transit Is Not a Climate Policy                                                                                                                                                                                                                                                                                                                                                                                                                 , How Cities Became Accidental Wildlife Havens                                                                                                                                                                                                                                                                                                                                                                                                                , California Slow to Sell Housing Bonds as Homelessness Worsens                                                                                                                                                                                                                                                                                                                                                                                               , Doge Surges After Memecoin Advocate Musk Agrees to Buy Twitter                                                                                                                                                                                                                                                                                                                                                                                              , Crypto Conference in North Korea Leads to More Criminal Charges                                                                                                                                                                                                                                                                                                                                                                                             , Bitcoin ‘Stuck at the Moment’ as Record Cash Flees Crypto ETFs                                                                                                                                                                                                                                                                                                                                                                                              , Alex Harris                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Treasury’s latest tax collection may preview how the shrinking of the Federal Reserve’s $9 trillion balance sheet, or quantitative tightening, will unfold for the markets and global liquidity.                                                                                                                                                                                                                                                        , The influx of personal tax receipts pushed the amount of cash in the Treasury’s account at the central bank to $908 billion as of April 20, the most since May 2021, data show. The Treasury General Account, or TGA, operates like the government’s checking account at the Fed. When Treasury increases its cash balance, that’s on the liability side of the Fed’s balance sheet, so as that goes up, it drains reserves from the system, and vice versa. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/currency </td>
   <td style="text-align:left;"> 2022-04-26 00:43:00 </td>
   <td style="text-align:left;"> South African Rand at Over 3-Month Low </td>
   <td style="text-align:left;"> The South African rand continued its losing streak to touch 15.7 against USD, its lowest since January 6th, amid a stronger dollar as investors focused on growth risks and rapid US interest rate hikes. Domestically, rolling power cuts, flood damage and signs of a Covid-19 comeback added to worries about the country’s economic outlook. Still, expectations of continued monetary policy tightening by the South African Reserve Bank limited further losses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2022-04-26 00:31:05 </td>
   <td style="text-align:left;"> Russian Stocks at 2-Month Low </td>
   <td style="text-align:left;"> The MOEX Russia Index closed 2.1% lower at 2,186 on Monday, falling to its lowest in two months, as the prolonged invasion of Ukraine and risk of further sanctions against Moscow continued to weigh on Russian equities. Reports indicated that the EU is preparing “smart sanctions” for its sixth package against Russian oil imports that may be unveiled later this week, aimed at maximizing pressure on Russia with minimal collateral damage. Sanction threats and lower crude prices due to growth jitters in China pressured the energy sector to close in the red. Prospects of economic penalties also pressured the financial sector, with Sberbank ending 4.3% lower. The lender’s shares have lost 23% of their value since the start of the month, amid reports that it is also a primary target in the EU’s sixth sanction package. On the earnings front, Polyus fell 4.5% after it declined to publish its operating results while Polymetal plunged 8.6% after posting a 6% y-o-y decrease in production. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/25/politics/trump-contempt-hearing/index.html </td>
   <td style="text-align:left;"> 2022-04-26 00:25:47 </td>
   <td style="text-align:left;"> Donald Trump: Judge holds former President in civil contempt for withholding documents in NY AG investigation - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)A New York judge is holding Donald Trump in civil contempt after the state's attorney general's office said he did not comply with a subpoena for documents as part of its investigation into the former President's company.                                                                                                                                                                                                                                                                                       , Judge Arthur Engoron said Trump failed to abide by his order to comply with the subpoena, and that his attorneys failed to show how a search of materials held by Trump was conducted. Engoron said Trump would be fined $10,000 a day until he complies.                                                                                                                                                                                                                                                                 , "Mr. Trump, I know you take your business seriously and I take mine seriously. I hereby hold you in civil contempt and fine you $10,000 per day until you purge that contempt," Engoron said at a hearing Monday. A written decision with a start date for fines is expected Tuesday.                                                                                                                                                                                                                                     , Trump plans to appeal the decision, his attorney Alina Habba told reporters.                                                                                                                                                                                                                                                                                                                                                                                                                                              , "We respectfully disagree with the court's decision today," Habba said. "All documents, as I explained, responsive to the subpoena were already produced to the attorney general months ago."                                                                                                                                                                                                                                                                                                                             , New York Attorney General Letitia James' office has been investigating the Trump Organization for more than two years and previously said her office found multiple misleading or fraudulent misstatements and omissions in the Trump Organization's financial statements, which were provided to lenders and insurers, among others, as part of its investigation.                                                                                                                                                       , Andrew Amer, with the attorney general's office, said that Trump has failed to produce "even a single responsive document" for a subpoena that was issued to him in December.                                                                                                                                                                                                                                                                                                                                             , "We are being hampered in our efforts to have a complete understanding because we don't have evidence from the person who sits at the top of the organization," Amer said.                                                                                                                                                                                                                                                                                                                                                , Kevin Wallace, with the attorney general's office, said in some instances it's been "like pulling teeth" to get documents needed for the investigation, and describing the Trump Organization as a closely-held family company with 500 entities and millions of dollars moving around.                                                                                                                                                                                                                                   , In court, Habba said the former president does not believe he is above the law, but simply does not have the types of written communications that were sought by the subpoena, but that he produced hundreds of thousands of documents through his assistants. Habba said she herself searched Trump's hard copy calendars and physical file locations, and even interviewed her client in Florida.                                                                                                                       , "President Trump does not email. He does not text message. And he has no work computer at home or anywhere else," Habba said.                                                                                                                                                                                                                                                                                                                                                                                             , "I took it upon myself to get on a plane and flew down and asked him one by one if there was anything that he had on his person that he had not given me I would need that. And he did not," she said.                                                                                                                                                                                                                                                                                                                    , The judge asked why Trump didn't sign an affidavit swearing that he complied with the subpoena. Habba said that he would.                                                                                                                                                                                                                                                                                                                                                                                                 , "My client is an honest person, much to the dismay of certain people in this room," Habba said.                                                                                                                                                                                                                                                                                                                                                                                                                           , James' office has said in court filings that the Trump Organization is under investigation for engaging in fraudulent or misleading conduct in connection with appraisals and financial statements. The office has subpoenaed both the former president and his company for documents related to its investigation.                                                                                                                                                                                                       , Habba argued that the attorney general's investigation has "seemingly become aimless," saying that since it began three years ago, the Trump Organization has been given six separate subpoenas, produced more than 6 million pages of documents, and 13 Trump Organization witnesses have been deposed, among other things.                                                                                                                                                                                              , "The scope is continuously changing to fit the attorney general's needs," Habba said in court. "When it is not satisfied with the evidence it has obtained it pivots and looks for something new."                                                                                                                                                                                                                                                                                                                        , Judge orders Cushman and Wakefield to comply with NY AG subpoena                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Also Monday, Engoron allowed James' office to add real estate services firm Cushman and Wakefield as a respondent to its legal action against the Trump Organization, and ordered the company to comply with a subpoena for documents.                                                                                                                                                                                                                                                                                    , At the heart of the subpoenas are appraisals from Cushman and Wakefield appraisers who worked on valuations for Trump Organization properties, as well as documents showing relationships between the two companies and internal communications about Cushman's decision to ultimately sever ties with the Trump Organization in January.                                                                                                                                                                                 , Austin Thompson, an attorney with the New York attorney general's office, said his office has identified "misstatements" made by appraisers who made valuations at a Trump Organization property in Westchester County, New York, known as Seven Springs. And while the statute of limitations on some of the appraisals may have run out, the office still wants to investigate other reports that may be more recent and indicated that the real estate firm could become a party to future legal action by the office. , "We'd like to understand whether these folks are committing misconduct today," Thompson said. "Cushman has made repeated misstatements in the documents we've seen so far, so we're entitled to look at other documents, other appraisals they've written."                                                                                                                                                                                                                                                               , Sawnie McEntire, an attorney for Cushman and Wakefield, said the four subpoenas the company has received from the attorney general's office since 2019 are "overly broad." He said the company has dealt with a dozen subpoenas for documents and witness testimony, including depositions with appraisers who worked on Trump Organization property valuations.                                                                                                                                                          , "We cannot be faulted because we believe their requests have exceeded what is legally required," McEntire said.                                                                                                                                                                                                                                                                                                                                                                                                           , James' office is also seeking details on how much money Cushman and Wakefield has made from its relationship with the Trump Organization. McEntire said in court that the company made less than $200,000 doing business with the Trump Organization on the appraisal side of its business.                                                                                                                                                                                                                               , Engoron also granted the attorney general's office's request to file documents with the court only, because they contained information that could harm its ongoing investigation.                                                                                                                                                                                                                                                                                                                                         , This story has been updated with the ruling on Cushman and Wakefield.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-04-26 00:18:00 </td>
   <td style="text-align:left;"> South African Stocks End at 5-Month Low </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index slumped 3.4% to close at 69,822 on Monday, a low level not seen since last November, extending losses for a fourth straight session, led by commodity-linked sectors.  Risk aversion rippled across markets due to concerns over the worsening pandemic situation in China and faltering global growth, as well as the anticipation of an aggressive monetary policy tightening by major central banks. At the same time, investors have also been monitoring with caution a rise in virus infections in South Africa, which could translate to higher sickness-related absences and increase supply chain bottlenecks. On the earnings front, investment group PSG, which is mulling delisting from the JSE, reported a near two-fifth surge in its net asset value, on strong results from its financial and education services subsidiaries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/talis-biomedical-stock-bounces-off/story.aspx?guid={7B7291F7-CE0D-4F61-ABD5-1CC34393D689}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-26 00:08:35 </td>
   <td style="text-align:left;"> Talis Biomedical stock bounces off record low after largest shareholder pulls share-sale plans - MarketWatch </td>
   <td style="text-align:left;"> Shares of Talis Biomedical Corp. 
        TLIS,
        +5.61%
       bounced 1.9% in midday trading Monday, after the diagnostic testing company requested a withdrawal of a large share offering by a selling shareholder. After the March 15 closing bell, the company had registered 37.49 million common shares for sale, including 7.63 million common shares and 29.86 million shares issuable after the conversion of convertible preferred stock, by entities affiliated with Baker Bros. Advisors L.P., which is Talis' largest shareholder. Talis did not disclose the reason for the requested withdrawal of the offering, but the stock had plunged 57.9% since the stock-offering registration through Friday's record close of $1.07. The stock, which went public on Feb. 12, 2021, is now trading 93.2% below its initial public offering price of $16 a share., It's one of several generic drugs that's being tested as a way to treat the virus.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-04-26 00:07:05 </td>
   <td style="text-align:left;"> French Stocks Start Week with Decline </td>
   <td style="text-align:left;"> The CAC 40 index ended 2% down at 6,449 on Monday, the lowest close in six weeks, weighed down by the luxury goods sector amid expectations of monetary tightening by the ECB and growth jitters from China, while investors weighed on President Macron’s re-election. Prolonged Covid lockdowns in major Chinese lowered demand expectations for heavyweight French luxury good brands, with LVMH and Hermes dropping nearly 4%, while Kering fell 4.4%. On the earnings front, ArcelorMittal plunged 8.8% after publishing its Q1 corporate results, posting an EBITDA of $4.6 billion. Vivendi shares were 1.5% down as the media group did not announce earnings forecasts for the current fiscal year, despite recording a 13.4% turnover during Q1. Still, further losses were limited as President Macron was re-elected for 5 more years in office, beating far-right candidate Marine Le Pen in the second round run-off with 58% of the votes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-04-26 00:05:00 </td>
   <td style="text-align:left;"> Madrid Stocks Start Week on Weak Note </td>
   <td style="text-align:left;"> The IBEX 35 closed 0.9% down at 8,575 on Monday, extending a 1.8% drop in the previous session, in line with its European peers, as fears of a recession due to lockdowns in China and rate hikes overshadowed relief over Emmanuel Macron's re-election. On the economic data front, Spanish factory-gate inflation surged to an all-time high for the 6th straight month at 46.6% in March, led by surge in energy costs. The cyclical stocks, especially those most linked to commodities were the top losers, led by ArcelorMittal (-8.6%), Repsol (-4.5%) and Acerinox (-4.5%). Looking forward, focus will be on the results of Santander, Enagás, Ence, Iberdrola, Aena, Red Eléctrica, Naturgy, Repsol, Mapfre, Banco Sabadell, CIE Automotive, PharmaMar, BBVA, Cellnex, CaixaBank, Fluidra and Indra all reporting this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/inflation-will-severely-hurt-dems-in-2022-midterms-andy-puzder </td>
   <td style="text-align:left;"> 2022-04-26 00:03:10 </td>
   <td style="text-align:left;"> Inflation will 'severely' hurt Dems in 2022 midterms: Andy Puzder </td>
   <td style="text-align:left;"> Former CKE Restaurants CEO Andy Puzder blasts Sen. Elizabeth Warren, D-Mass., for her calls to lower inflation amid her push to increase government spending.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Andy Puzder, former chief executive officer of CKE Restaurants, warned on Monday that inflation will "severely" hurt Democrats in November.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Puzder made the comment on "Mornings with Maria" on Monday in response to Sen. Elizabeth Warren, D-Mass., warning that "Democrats are going to lose" in the midterm elections if they don’t help to bring down prices for families.                                                                                                                                                                                                                                                                                                                                                                                                                                   , Speaking on CNN’s "State of the Union," Sunday, Warren said, "It is the responsibility of Congress, of the president, to get out there, and make the changes we need to make to bring down those prices for families, and we can do that. We have the tools."                                                                                                                                                                                                                                                                                                                                                                                                         , "I think we’re going to be in real trouble if we don’t get up and deliver then I believe the Democrats are going to lose," she added.GET FOX BUSINESS ON THE GO BY CLICKING HEREPuzder told host Maria Bartiromo on Monday that "Elizabeth Warren is right" as inflation accelerated to a new four-decade high in March with supply chain constraints, the Russian war in Ukraine and strong consumer demand fueling rapid price gains that wiped out the benefits of rising wages for most Americans.                                                                                                                                                                , Rep. Nancy Mace, R-S.C., discusses inflation crippling the U.S., her Penny Plan and leaked audio of Rep. Kevin McCarthy's reaction to Jan. 6.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Labor Department said earlier this month that the consumer price index (CPI) – which measures a bevy of goods including gasoline, health care, groceries and rents – rose 8.5% in March from a year ago, the fastest pace since December 1981, when inflation hit 8.9%. Prices jumped 1.2% in the one-month period from February, the largest month-to-month jump since 2005.                                                                                                                                                                                                                                                                                         , Price increases were widespread: Energy prices rose a stunning 11% in March from the previous month, and are up 32% from last year. Gasoline, on average, costs 48% more than it did last year after rising 18.3% in March on a monthly basis as the Russian war in Ukraine fueled a rapid increase in oil prices. BIDEN ANNOUNCES STUDENT LOAN PAYMENT PAUSE EXTENSION: WHAT BORROWERS CAN DO NOWPuzder, however, slammed Warren on Monday for her calls to curb inflation amid her support for more government spending, arguing that "she is out there advocating not only for Build Back Better," but she also "wants the president to forgive the student debt." , The former CEO of CKE Restaurants weighs in on Sen. Elizabeth Warren, D-Mass., warning that ‘Democrats are going to lose’ in the midterm elections if they don’t help to bring down prices for families.
                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Senate Majority Leader Chuck Schumer reportedly said during a meeting by The Student Debt Crisis Center entitled "The State of Student Debt Summit," which also featured comments from Sen. Warren, that President Biden could be growing closer to canceling student debt and that the White House "seems more open to it than ever before."                                                                                                                                                                                                                                                                                                                         , "Democrats just have really no idea what to do to lower inflation," Puzder argued in response. "Everything they do would actually increase inflation."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Fox News’ Jessica Chasmar and FOX Business’ Megen Henney contributed to this report.   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nuclear </td>
   <td style="text-align:left;"> 2022-04-25 23:51:31 </td>
   <td style="text-align:left;"> Nuclear Energy Index Hits 4-week Low </td>
   <td style="text-align:left;"> Nuclear Energy Index decreased to a 4-week low of 1450 USD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-04-25 23:50:37 </td>
   <td style="text-align:left;"> UK Stocks End at Near 6-Week Low </td>
   <td style="text-align:left;"> The FTSE 100 plunged about 1.9% to close at 7,381 on Monday, its lowest level in nearly six weeks, as risk aversion weighed down on commodity-linked stocks amid a backdrop of fears over slowing growth and an aggressive tightening of monetary policy. Adding to concerns, the pandemic situation in China seemed to worsen over the weekend, with authorities suspecting that the virus has spread undetected for a week in the capital Beijing. Heavyweight miners and energy stocks fell sharply, with Anglo American down more than 6.5% and BP shedding almost 6%. In corporate news, supermarket chain ASDA said it planned to spend £73 million to help customers and staff weather the cost of living in 2023, cutting prices in more than 100 staples and raising the hourly pay of shop-floor workers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-04-25 23:46:04 </td>
   <td style="text-align:left;"> Italian Stocks Close at Near 6-Week Low </td>
   <td style="text-align:left;"> The FTSE MIB index ended 1.5% lower at 23,909 on Monday, the lowest close in six weeks amid jitters of monetary tightening by major central banks and economic slowdown in China. Energy stocks fell 3.6%, tracking lower crude prices as higher Covid cases in Beijing strengthened expectations of prolonged lockdowns in China. Tenaris shares plunged nearly 7%, while Saipem lost 6.1%. At the same time, Telecom Italia ended 2.4% lower after major shareholder Vivendi did not release earnings forecasts along with their quarterly results, despite recording an improved turnover. Utility stocks outperformed other sectors, with Enel gaining 1.5%, extending the sector’s recent momentum as Italy continues to attempt to reduce its Russian energy supply. Meanwhile, S&amp;P confirmed Italy’s sovereign rating at BBB with a positive outlook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/inflation-small-businesses-goldman-sachs </td>
   <td style="text-align:left;"> 2022-04-25 23:43:51 </td>
   <td style="text-align:left;"> Surging inflation squeezing small businesses, Goldman Sachs survey shows </td>
   <td style="text-align:left;"> Gradient Investments President Michael Binger argues valuations have become 'much more reasonable lately.' 
                                                                                                                                                                                                                                                                              , Soaring inflation and snarled supply chains are crushing small businesses owners, who are struggling to maintain their bottom line and retain workers, according to a new survey published by Goldman Sachs.                                                                                                                                                                                 , The survey of owners from Goldman Sachs' 10,000 Small Business Voices shows that 91% of respondents believe broader economic trends, including red-hot inflation, supply chain issues and a labor shortage, are having a negative effect on their business.                                                                                                                                  , FED RAISES INTEREST RATES FOR FIRST TIME IN 3 YEARS, PROJECTS 6 MORE HIKES AS INFLATION SURGES                                                                                                                                                                                                                                                                                               , "Small business owners are stuck between a rock and a hard place as inflation and an uneven economic recovery are impacting every part of our businesses with no end in sight," said Khari Parker, a member of the Goldman Sachs' 10,000 Small Businesses Voices National Leadership Council and the owner of a small business, Connie's Chicken and Waffles, in Baltimore.                  , A shopper walks through the aisles of the Dollar Tree store in Alhambra, California, on Dec. 10, 2021. (Frederic J. Brown/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                               , The hottest inflation in four decades has exacerbated workplace challenges, according to the survey, with the high costs of attracting and retaining talent hurting small businesses' profit margins and ability to do business. Eight in 10 respondents said their business' financial health has been hurt by rising consumer prices over the past six months.                             , "Small businesses are sending a clear signal that the economy and the challenges they face – like inflation, workforce, supply chain and energy costs – are going from bad to worse," said Joe Wall, national director of the 10,000 Small Businesses Voices.                                                                                                                                , A persistent labor shortage has also weighed on small businesses as owners are forced to hike wages in an increasingly competitive market to hire new workers. Some economists have warned that rising wages could fuel even higher inflation. Nearly two-thirds of small business owners said they have increased wages in order to attract new employees or retain their former employees. , A notice of closure is posted at The Great Frame Up in Grosse Pointe Woods, Michigan, on April 2, 2020. (AP Photo/Paul Sancya, File / AP Images)                                                                                                                                                                                                                                             , As a result of the higher wages, about 60% of small business owners said they are passing along the costs to consumers by raising the prices of goods or services, according to the survey, which is based on 1,107 respondents and was conducted between April 11-14.                                                                                                                       , The combination of high inflation and rising wages has fueled concern about the possibility of a wage-price spiral, a 1970s-style phenomenon where high inflation leads to pay hikes, which in turn lead to more spending and more expensive prices.                                                                                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                  , The inflation spike has been bad news for President Biden, who has seen his approval rating plunge as consumer prices rose. The White House has blamed the price spike on supply chain bottlenecks and other pandemic-induced disruptions in the economy, while Republicans have pinned it on the president's massive spending agenda.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lumber </td>
   <td style="text-align:left;"> 2022-04-25 23:42:34 </td>
   <td style="text-align:left;"> Lumber Prices Ease Below $1,000 </td>
   <td style="text-align:left;"> Chicago lumber futures eased to below $1000 per thousand board feet, hurt by demand concerns due to higher interest rates despite the looming summertime construction season. Lumber prices have been under pressure and are down more than 15% since the beginning of 2022, as transportation bottlenecks eased and output volumes at sawmills have recovered from such constraints amid better spring weather, easing supply concerns after months of tight inventories. On top of that, rising mortgage rates helped cool the red-hot US housing market. Meanwhile, lumber prices reached record highs in Japan due to sanctions imposed against Moscow. Russia accounts for more than 80% of Japan’s imports of wood veneer sheets and nearly 20% of its imports of rafters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-04-25 23:39:00 </td>
   <td style="text-align:left;"> Brazilian Real at 1-Month Low </td>
   <td style="text-align:left;"> The Brazilian real was changing hands around $4.9, hovering at a one-month low, after a wave of risk aversion swept global markets on fears that more lockdowns in China and aggressive monetary policy tightening by the Federal Reserve would hurt growth. Still, the Brazilian currency has been the world's best performing this year, up 13.6%, despite domestic economic and political crisis, helped by soaring commodity prices and double-digit interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-04-25 23:36:39 </td>
   <td style="text-align:left;"> European Stocks End Sharply Lower, DAX at 6-Week Low </td>
   <td style="text-align:left;"> European equity markets closed sharply lower on Monday, with Germany’s DAX down more than 1.5% to its lowest since mid-March as fears about faltering economic growth, a looming tightening cycle of monetary policy, and a deterioration in the pandemic situation in China more than offset relief from Macron's strong victory in the French presidential elections. China-exposed sectors were among the worst performers and oil and gas stocks tracked the decline in crude prices. On the earnings front, Dutch health technology firm Philips said Q1 core profits fell roughly 30% from the previous year, partly reflecting a recall of a large number of its ventilators, while Swiss pharma Roche posted a better-than-expected 10% increase in Q1 sales on strong demand for antigen COVID-19 tests. On the data front, German business morale unexpectedly improved in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/25/technology/twitter-employees-elon-musk.html </td>
   <td style="text-align:left;"> 2022-04-25 23:28:04 </td>
   <td style="text-align:left;"> Twitter Employees Search for Answers as Musk Takeover Becomes Reality - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Workers say they have been left largely in the dark about what a sale to the billionaire will mean for them and their shares in the company.                                                                                                                                                                                                                                                                                                                                                                                               , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                             , By Kate Conger                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , In January 2020, thousands of Twitter employees gathered in Houston for a corporate summit called #OneTeam. During the event, Jack Dorsey, Twitter’s chief executive at the time, revealed he had invited a surprise guest. Then, with a wave and a smile, Elon Musk appeared on giant screens above the stage. The crowd cheered, clapped and pumped fists. “We love you,” one employee shouted.                                                                                                                                          , Inside Twitter today, surprise announcements about Mr. Musk land differently. Employees said they had largely stopped celebrating the richest man in the world since he declared his intent this month to buy Twitter, scrap its content moderation policies and transform the publicly traded company into a private one. On Monday, Twitter announced it had accepted Mr. Musk’s offer to buy the company for about $44 billion.                                                                                                         , As the takeover fight played out over the last two weeks, Twitter employees said they were frustrated that they had heard little from management about what it meant for them, even as Twitter closed in on a deal with Mr. Musk on Monday morning. They asked their chief executive, Parag Agrawal. They asked Mr. Musk himself in questions sent on Twitter. Some even went to Charles Schwab, the financial firm that manages their stock options, for clarity about the impact a sale of the company would have on them.               , But they were not getting very many answers before Mr. Musk’s bid succeeded, said 11 Twitter employees who asked to not be named because they were not authorized to speak publicly, even as it became clear that they could soon find themselves reporting to Mr. Musk. On Monday afternoon, Mr. Agrawal told employees he would finally speak with them at a meeting later that day. “I know this is a significant change and you’re likely processing what this means for you and Twitter’s future,” he wrote in an email to employees. , This kind of silence that hovered over the week of negotiations is routine in takeover fights. As the board of directors confers with bankers, lawyers and expensive public relations firms, employees are often kept in the dark. But for employees at Twitter, a company that has billed itself as the world’s town square, finding out what is happening to their company primarily through Twitter, the service they built, has been particularly embittering.                                                                         , After years of leadership squabbles, demands for change from activist investors and the boundary-testing tweets of former President Donald J. Trump, Twitter’s more than 7,000 employees are accustomed to turmoil. But some of them say the takeover bid by the mercurial billionaire is hitting them in ways other company crises have not.                                                                                                                                                                                              , Employees said they worried that Mr. Musk would undo the years of work they had put into cleaning up the toxic corners of the platform, upend their stock compensation in the process of taking the company private and disrupt Twitter’s culture with his unpredictable management style and abrupt proclamations.                                                                                                                                                                                                                        , But Mr. Musk also has fans among Twitter’s rank-and-file, and some employees have welcomed his bid. In an internal Slack message seen by The New York Times that asked if employees were excited about Mr. Musk, about 10 people responded with a “Yes” emoji. A Twitter spokesman declined to comment.                                                                                                                                                                                                                                    , If Twitter is worth buying, much of its value is in the employees who build and manage the service, said David Larcker, a professor of accounting and corporate governance at Stanford University. “The wild card is, what if it becomes a very different company than they thought they were working for? It’s an uncomfortable working relationship,” he said.                                                                                                                                                                           , Mr. Musk has made some of his intentions clear in regulatory filings, tweets and public appearances: The company must scrap nearly all of its moderation policies, which ban content like violent threats, harassment and spam. It must provide more transparency about the algorithm it uses to boost tweets in users’ newsfeeds. And it must become a private company.                                                                                                                                                                   , Twitter has been expanding its content moderation policies since 2008, when its 25th employee was hired specifically to combat abuse on its platform. The teams overseeing moderation and safety have now grown to hundreds of employees.                                                                                                                                                                                                                                                                                                  , Many Twitter employees feel personally invested in the company’s effort to encourage healthy conversation — even if they do not directly work on content moderation — and have pressed executives to crack down further on hate speech and misinformation, six employees said. They see Mr. Musk’s proposal to revert to Twitter’s early, lax approach as a rebuke of their work.                                                                                                                                                          , But other employees have argued in internal messages seen by The Times that their co-workers have shifted too far to the left side of the political spectrum, making employees who support Mr. Musk’s plans too uncomfortable to speak up. In a worker-run survey of nearly 200 Twitter employees on Blind, an anonymous workplace review app, 44 percent said they were neutral on Mr. Musk. Twenty-seven percent said they loved Mr. Musk, while 27 percent said they hated him.                                                         , Although executives and employees at Twitter have agreed with Mr. Musk about changes to its algorithm, that work is in its earliest stages and could take years to complete. That could test something Mr. Musk is not particularly known for — patience.                                                                                                                                                                                                                                                                                  , One of the top concerns among Twitter workers is whether they will take a financial hit from Mr. Musk’s acquisition. Many Twitter employees make 50 percent or more of their total compensation from Twitter stock. Employees said they feared missing out on the long-term value of their stock at Mr. Musk’s price of $54.20 per share.                                                                                                                                                                                                  , In an attempt to quell financial worries, Sean Edgett, Twitter’s general counsel, told employees that any potential buyer would most likely be required to keep employee equity “as is” or provide equivalent compensation, like a cash award.                                                                                                                                                                                                                                                                                             , Mr. Edgett, who made his comments before the deal with Mr. Musk was announced, stressed that employees should not view his guidance as insight into the deal-making. “This is meant to provide some peace of mind and explain how these things typically work, not because we believe there will be one outcome versus another,” he wrote in messages to employees reviewed by The Times.                                                                                                                                                  , Twitter has been on a hiring spree, spending $630 million on stock-based compensation in 2021, a 33 percent increase from the previous year. Twitter predicted in a February earnings report that it would spend between $900 million and $925 million on stock-based compensation this year.                                                                                                                                                                                                                                              , But Mr. Musk’s campaign has also begun to undercut Twitter’s attempts to recruit new employees, according to internal documents outlining the company’s hiring efforts that were viewed by The Times. Prospective hires have expressed skepticism about Mr. Musk’s plans to transform Twitter and upend its content moderation, those documents said.                                                                                                                                                                                      , Recruits have also fretted that the shares included in their offer letters could quickly become devalued if Mr. Musk took Twitter private.                                                                                                                                                                                                                                                                                                                                                                                                 , Twitter’s recruiting problem could balloon further if current employees quit, as some have warned they would do if Mr. Musk took over. Other employees worried about layoffs or the loss of work visas under Mr. Musk, and raised questions about these issues with Mr. Agrawal.                                                                                                                                                                                                                                                           , Managers responsible for hiring have been asked to keep track of how many prospective employees turn down job offers because of fears about Mr. Musk, according to internal communications reviewed by The Times.                                                                                                                                                                                                                                                                                                                          , Employees have also wondered: Could he also move Twitter’s headquarters to Texas, as he did with Tesla? Could he end the company’s flexibility about returning to the office, which has become a selling point for employees and recruits? Mr. Musk, after all, fought with officials in California to keep his car factory open early in the pandemic.                                                                                                                                                                                    , Mr. Agrawal has tried to calm his work force. In a question-and-answer session with employees held the day Mr. Musk announced he intended to buy Twitter, Mr. Agrawal declined to share details about how the company would respond to Mr. Musk but urged employees to remain focused on the things they could control, like their day-to-day work, according to employees who attended the meeting.                                                                                                                                       , The stress at the mention of Mr. Musk is a stark contrast to the welcome he enjoyed from employees two years ago. Although some employees said they were skeptical of Mr. Musk at the 2020 event, many of them listened attentively as he gave his advice for Twitter: The company should step up its moderation, he said, by doing more to weed out bots and scammers from the actual humans using the platform.                                                                                                                          , “By the way, do you want to run Twitter?” Mr. Dorsey asked Mr. Musk.                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , The assembled Twitter employees laughed. Mr. Musk did not immediately answer.                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Ryan Mac and Mike Isaac contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/monthly-gdp-yoy </td>
   <td style="text-align:left;"> 2022-04-25 23:26:28 </td>
   <td style="text-align:left;"> Mexico Economic Activity Growth at 6-Month High </td>
   <td style="text-align:left;"> Economic activity in Mexico increased 2.5 percent year-on-year in February of 2022, quickening from a 1.8 percent expansion in the previous month and in line with market expectations. It was the fastest rise in national output since last August, due to a recovery in the momentum of the expansion in the service sector (2.7 percent vs 0.6 percent in January). Meanwhile, production in the secondary sector rose slightly slower (2.5 percent vs 4.3 percent), reflecting contractions in mining (-2.9 percent vs 10.6 percent) and construction activities (-4.3 percent vs 0.6 percent, while growth in manufacturing output limited losses (6.9 percent vs 3.7 percent). Finally, agriculture output also fell (-2.9 percent vs 0.5 percent). On a seasonally adjusted monthly basis, economic output remained unchanged in February, after rising 0.4 percent in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-04-25 23:21:03 </td>
   <td style="text-align:left;"> Gold Approaches 2-Month Low </td>
   <td style="text-align:left;"> Gold declined more than 1.5% to below $1,900 an ounce on Monday, closing in on its lowest level in two months, as the prospect of faster Federal Reserve policy tightening continued to support the dollar and US Treasury yields, while denting demand for bullion. Speaking at a panel hosted by the IMF last week, Fed Chair Jerome Powell said a 50-basis point interest rate increase was “on the table” for May and reiterated that Fed officials were committed to “front-end loading” inflation-fighting efforts. The dollar index hit fresh 2-year highs following the remarks, while the benchmark 10-year US yields held near 3-year highs. Meanwhile, investors remained cautious of geopolitical uncertainties and the risk of stagflation, which may drive safe-haven demand and support gold prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61215194?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-25 23:17:00 </td>
   <td style="text-align:left;"> Stock markets tumble over China lockdown fears </td>
   <td style="text-align:left;"> Stock markets across Europe have fallen after sharp declines in Asia on fears Covid restrictions in China could hit supply chains and the global economy.                                                                                                                                                         , Authorities in Beijing have implemented mass testing in one area of the city following a small outbreak of cases.                                                                                                                                                                                                 , But there are concerns the capital could follow Shanghai by enforcing a lockdown to contain the spread.                                                                                                                                                                                                           , London's leading FTSE 100 share index tumbled, led by commodities firms such as oil producers and miners.                                                                                                                                                                                                         , The FTSE clawed back from some losses from morning trade but the index closed the day 1.8% down. Germany and France recorded similar declines.                                                                                                                                                                    , In the US, both the Dow Jones Industrial Average and the S&amp;P 500 opened lower.                                                                                                                                                                                                                                    , Overnight China's Shanghai Composite Index fell by more than 5% while Hong Kong's Hang Seng closed 3.7% lower.                                                                                                                                                                                                    , "The scourge of Covid continues, with China unwavering in its zero tolerance policy," said Susannah Streeter, senior investment and markets analyst at Hargreaves Lansdown.                                                                                                                                       , "As cases erupt in Beijing, there is concern that prolonged lockdowns will hit employment and lead to a sharp slowdown in growth as well as sparking fresh shipping logjams and supply chain issues."                                                                                                             , Oil prices also fell on Monday, with Brent crude down 4.7% at $101.41 a barrel on the prospect of falling demand from China, the world's second largest economy after the US.                                                                                                                                     , Oil giants such as BP and Shell saw their share prices fall on Monday. Shares in mining giants such as Anglo American, Glencore and Rio Tinto were also among the biggest losers in early trading.                                                                                                                , Shanghai has been in lockdown for several weeks - but the daily death rate from Covid is rising and there are now thousands of known cases. In Beijing, there has been panic buying, as residents there fear they will soon face hefty restrictions of their own.                                                 , With China's "zero Covid" policy under pressure as never before, there are growing concerns about the impact all of this will have on the country's economy. Small wonder, then, that shares in Shanghai and Hong Kong have been tumbling.                                                                        , The ripple-effects are being felt more widely too. Shares in mining companies such as Glencore and Anglo-American have been suffering steep falls; if China's economy loses steam, demand for raw materials will decline - and that will hit their profits.                                                       , Then you have the wider background - of continued Covid-related disruption to supply chains; of shortages and rising prices linked to the war in Ukraine; and of speculation the US Federal Reserve and other central banks will hike interest rates faster than expected in an effort to keep a lid on inflation., All of this is creating a deeply queasy environment for investors - and weighing heavily on share prices around the world.                                                                                                                                                                                        , Beijing - which has a population of more than 21 million people - has reported a handful of new cases, but China has a strict zero-Covid policy in place. Over the weekend, some Beijing residents were told they needed to do Covid tests three times a week.                                                    , Pang Xinghuo, deputy director of the Beijing Center for Disease Prevention and Control, told that China Daily that the number of cases in Beijing is expected to increase in the following days.                                                                                                                  , In Shanghai, where there was a fresh outbreak a few weeks ago, much of the city is in lockdown or facing restrictions.                                                                                                                                                                                            , The latest outbreak in Shanghai, first detected in late March, has seen more than 400,000 cases recorded so far and 138 deaths.                                                                                                                                                                                   , Some factories in Shanghai have restarted production with companies such as electric car maker Tesla reportedly requiring employees to work on a "closed-loop" system which means they eat and sleep at the plant.                                                                                                , "The prospect of further restrictions in China could lead to a poisonous mix of further inflationary pressure, as supply chains in the so-called 'factory of the world' get disrupted and weaker economic growth," warned Russ Mould, investment director at AJ Bell.                                             , Analysts said stock markets in Europe and Asia were also affected by sharp falls on leading US indexes at the end of last week amid expectations of steep US interest rates rises to calm soaring inflation - currently at a 40-year high of 8.5%.                                                                , On Friday, the Dow Jones Industrial Average, the Nasdaq and the S&amp;P 500 indexes all fell by 2.5% or more.                                                                                                                                                                                                         , Last week, Jerome Powell, chairman of the US Federal Reserve, hinted that the central bank may increase the key interest rate by half a percentage point at the next meeting in May.                                                                                                                              , This would follow a quarter percentage point rise in March.                                                                                                                                                                                                                                                       , Mr Powell said: "It is appropriate in my view to be moving a little more quickly," adding that "50 basis points will be on the table".                                                                                                                                                                            , How many miles do you need to drive before it pays off?                                                                                                                                                                                                                                                           , Gary Lineker on football, politics and road rage                                                                                                                                                                                                                                                                  , Searching for Vladislav Surkov, key architect of the 'post truth' world                                                                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-04-25 23:11:57 </td>
   <td style="text-align:left;"> UK Gas Hits 9-week Low </td>
   <td style="text-align:left;"> UK Gas decreased to a 9-week low of 158.61 GBp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-25 23:11:00 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield Eases from 10-Year High </td>
   <td style="text-align:left;"> Canada’s 10-year government bond fell to 2.78%, down slightly from a 10-year high of 2.90% hit on April 21st, tracking a retreat in US Treasury yields, as concern grew that more COVID-19 lockdowns in China and potentially rising US interest rates would hurt global economic growth. Meanwhile, the Bank of Canada increased its target for the overnight rate by 50bps to 1% in its April meeting, a move not seen since May 2000 and pushing borrowing costs to the highest level since the coronavirus pandemic started. Policymakers added that interest rates would need to rise further as the economy moves into excess demand and inflation persists well above target. Canada's consumer prices jumped 6.7% over a year earlier in March, the quickest advance since January 1991. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-04-25 23:07:44 </td>
   <td style="text-align:left;"> Heating Oil Bucks Trend in Crude </td>
   <td style="text-align:left;"> Heating oil futures traded above $3.9 per barrel, holding on to gains of the previous week despite a rout in crude futures, as supply concerns offset downbeat demand growth forecasts. Industry figures showed inventory levels of distillates, which include heating oil, fell by 1.65 million barrels last week, following a larger 4.96 million barrel draw in the previous period. At the same time, daily oil output from OPEC nations and allies stood at 1.45 million barrels last month, as sanctions hit Russian production. On the demand side, concerns about the possibility of a lockdown in Beijing, after authorities closed down activities in Shanghai, dampened market sentiment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palladium </td>
   <td style="text-align:left;"> 2022-04-25 22:55:03 </td>
   <td style="text-align:left;"> Palladium Drops to 3-Month Low </td>
   <td style="text-align:left;"> Palladium futures tumbled to around $2,150 per tonne, closing in on its lowest level since January 21st, weighed down by demand concerns from the auto industry due to prolonged Covid-19 lockdowns in China while the US increases interest rates, further threatening global growth. The metal, used in vehicle exhausts to curb emissions, is down almost 40% since hitting an all-time high of $3,440 on March 7th due to concerns that the war in Ukraine could cut supply from key producer Russia. On April 8th, the London Platinum &amp; Palladium Market and the Chicago Metal Exchange trading hubs, suspended Krastsvetmet and Prioksky Plant of Non-Ferrous Metals from delivering palladium to the trading hubs, while the Japan Exchange Group’s Osaka Exchange was also mulling similar moves.
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-25 22:51:03 </td>
   <td style="text-align:left;"> Australia 10-Year Bond Yield Eases from 7-Year High </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Australian government bond eased to 3.04%, after hitting a  near 7-year high of 3.164% earlier in the session, moving in tandem with US Treasury yields with investors pricing a worsening global growth outlook against prospects of an increasingly hawkish Federal Reserve stance. Investors rushed to government bonds on Monday as reports of growing coronavirus infections in Beijing heightened concerns over another strict lockdown in a major city with more than 20 million people. Now, traders await key first-quarter inflation figures for Australia, which investors see hitting a near 14-year high of 4.6% on an annual basis, which should be enough for the Reserve Bank of Australia to shift to a more hawkish stance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/dallas-fed-manufacturing-index </td>
   <td style="text-align:left;"> 2022-04-25 22:38:00 </td>
   <td style="text-align:left;"> Texas Manufacturing Activity Growth at Near 2-Year Low </td>
   <td style="text-align:left;"> The Federal Reserve Bank of Dallas' general business activity index for manufacturing in Texas slipped further to 1.1 in April of 2022 from 8.7 in March. It was the lowest reading since October of 2020. The production index, a key measure of state manufacturing conditions, ticked down two points to 10.8, a reading in line with the index’s average. Meanwhile, the new orders index inched up to 12.1, while the growth rate of orders index held steady at 13.0. The capacity utilization index was unchanged at 14.3, and the shipments index pushed up five points to 11.8. Labor market measures indicated robust employment growth and longer workweeks Prices and wages continued to increase strongly in April, though the indexes eased off their historical highs. Expectations regarding future manufacturing activity generally eased but remained positive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/world-in-early-stages-of-very-significant-recession-economist-nancy-lazar </td>
   <td style="text-align:left;"> 2022-04-25 22:37:32 </td>
   <td style="text-align:left;"> World in early stages of ‘very significant’ recession: Economist Nancy Lazar </td>
   <td style="text-align:left;"> The Piper Sandler chief global economist warns the world is in the early stages of a 'very significant' recession.                                                                                                                                                                                                                                                               , Piper Sandler chief global economist Nancy Lazar warned on Monday that the world is in the early stages of a "very significant" and "synchronized" recession.                                                                                                                                                                                                                    , In an appearance on "Mornings with Maria" Monday, Lazar noted that a recession is expected outside of the United States.                                                                                                                                                                                                                                                         , "It’s going to be a global recession pulling down [the] Euro zone in particular," she told host Maria Bartiromo. "It looks like China GDP [Gross domestic product] in the second quarter could also be negative."                                                                                                                                                                , "Now we think the United States could not go into a recession. We have still plus 1% GDP for the U.S. this year, but that’s still a very significant slowdown from roughly 6% last year to one," she continued, noting that 1% GDP growth "will feel very, very weak."                                                                                                           , FED JAWBONING TO BLAME FOR MARKET SELLOFF: FITZ-GERALD                                                                                                                                                                                                                                                                                                                           , U.S. economic growth was revised slightly higher in the final months of 2021, helping the nation record its best year for growth in nearly four decades before the highly contagious omicron variant of the coronavirus dampened consumer spending and further strained the global supply chain.                                                                                 , Economist Nancy Lazar warns that the world is in the early stages of a "very significant" and "synchronized" recession. (iStock)                                                                                                                                                                                                                                                 , Gross domestic product, the broadest measure of goods and services produced across the economy, grew by 7% on an annualized basis in the fourth quarter, the Commerce Department said in its second reading of the data in February. The economy grew at an annual revised rate of 2.3% in the third quarter.                                                                    , Lazar noted that the U.S. faced "a similar situation back in 2015" and that there were "fears of a recession" in 2016.                                                                                                                                                                                                                                                           , "You didn’t get it, in part because the backbone of the United States is pretty healthy, which we still think is the case," she told Bartiromo.                                                                                                                                                                                                                                  , "But, nonetheless, outside of the United States, indeed you do get a recession, led by the Euro zone given what’s going on with oil prices and global interest rates."                                                                                                                                                                                                           , Oil prices fell on Monday, with U.S. crude slipping below the $100 per barrel level.                                                                                                                                                                                                                                                                                             , Oil prices have fallen back on expectations of weaker demand after peaking above $130 per barrel last month due to anxiety about the disruption of supplies from Russia, the world's No. 2 exporter.                                                                                                                                                                             , Meantimes, Wall Street is betting the Federal Reserve will raise interest rates at the steepest pace in over two decades as policymakers look to tame red-hot inflation.                                                                                                                                                                                                         , Traders are already pricing in a 100% chance of a half-point rate increase during the Fed's May meeting, in addition to at least three more 50-basis point hikes at the U.S. central bank's subsequent meetings in June, July and September, according to the CME Group, which tracks trading.                                                                                   , Sarge986 president Stephen Guilfoyle and Fitz-Gerald Group principal Keith Fitz-Gerald react to the Fed's hawkish inflation position on 'The Claman Countdown.'                                                                                                                                                                                                                  , By September, traders expect the federal funds target range to be at least 2.25% to 2.5%, well above the current range of 0.25% to 0.50%.                                                                                                                                                                                                                                        , In March, inflation accelerated to a new four-decade high as supply chain constraints, the Russian war in Ukraine and strong consumer demand fueled rapid price gains that wiped out the benefits of rising wages for most Americans.                                                                                                                                            , AS GAS PRICES SOAR, EVS OUT OF REACH                                                                                                                                                                                                                                                                                                                                             , The Labor Department said earlier this month that the consumer price index (CPI) – which measures a bevy of goods including gasoline, health care, groceries and rents – rose 8.5% in March from a year ago, the fastest pace since December 1981, when inflation hit 8.9%. Prices jumped 1.2% in the one-month period from February, the largest month-to-month jump since 2005., Price increases were widespread: Energy prices rose a stunning 11% in March from the previous month, and are up 32% from last year. Gasoline, on average, costs 48% more than it did last year after rising 18.3% in March on a monthly basis as the Russian war in Ukraine fueled a rapid increase in oil prices. Lazar predicted on Monday that "lower inflation is coming."   , Piper Sandler chief global economist Nancy Lazar argues 'we are at the early stages of a very significant, synchronized global recession.'                                                                                                                                                                                                                                       , "I think we are going to have significant goods deflation," she told Bartiromo, pointing to the price of used cars as an example.                                                                                                                                                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                      , "We’ve seen used cars decline 6% just in a few months," Lazar said, noting that she expects prices to drop even more and that the fall in prices will spread between industries.                                                                                                                                                                                                 , Lazar also pointed out the positive and negative impact of deflation.                                                                                                                                                                                                                                                                                                            , "On the one hand that’s positive in that you are going to send, obviously, the CPI significantly lower over the next year; but on the other hand, it’s not going to be pretty in that it’s going to affect company earnings, through lower earnings via weaker demand for products and also declining prices," she explained.                                                    , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                          , FOX Business’ Megan Henney contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/netflix-subscriber-losses-streaming-cancellations </td>
   <td style="text-align:left;"> 2022-04-25 22:27:14 </td>
   <td style="text-align:left;"> Netflix subscriber losses prompt animated project cancellations: Report </td>
   <td style="text-align:left;"> WSJ media and entertainment reporter Joe Flint discusses the carefree spending of Netflix as the streaming service faces challenges and CNN+ short-lived streaming network.                                                                                                                                                                                                   , Multiple projects in Netflix's animation department have reportedly been canceled as the streaming behemoth looks to cut costs following its first subscriber loss in over a decade.                                                                                                                                                                                          , NETFLIX'S COMPETITORS ‘GAINING ON THEM’ AS SUBSCRIBER GROWTH POSES CHALLENGES: JOE FLINT                                                                                                                                                                                                                                                                                      , According to The Wrap, animated projects that have been cut include an adaptation of Roald Dahl's "The Twits," an animated series based on Jeff Smith's "Bone" comic book series and Lauren Faust's "Toil and Trouble." Phil Rynda, Netflix's director of creative leadership and development for original animation, and many of his staff have also reportedly been let go. , In addition to the shake-up in the animation department, Netflix is also reportedly undergoing a restructuring of its engineering department, according to Bloomberg.                                                                                                                                                                                                         , A spokesperson for Netflix did not immediately return FOX Business' request for comment.                                                                                                                                                                                                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                   , Netflix reported 200,000 fewer subscribers in the first quarter of 2022.                                                                                                                                                                                                                                                                                                      , Though the company's own guidance projected it would add 2.5 million customers during the period, the company only added about 500,000 subscribers. Netflix said shutting down its service in Russia resulted in the loss of 700,000 subscribers. In total, the company has nearly 222 million subscribers worldwide.                                                         , In order to combat its subscriber losses, the company plans to crack down on more than 100 million households sharing passwords and introduce a cheaper, ad-supported subscription tier. Looking ahead, Netflix is expecting to lose another 2 million subscribers in the second quarter.                                                                                     , Shares of Netflix are down more than 65% year-to-date.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/603259:ch </td>
   <td style="text-align:left;"> 2022-04-25 22:26:21 </td>
   <td style="text-align:left;"> WuXi AppTec earnings above expectations at 0.53 USD </td>
   <td style="text-align:left;"> WuXi AppTec (603259) released earnings per share at 0.53 USD, compared to market expectations of 0.47 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/currency </td>
   <td style="text-align:left;"> 2022-04-25 22:20:14 </td>
   <td style="text-align:left;"> Swiss Franc Hovers at 22-Month Low </td>
   <td style="text-align:left;"> The Swiss franc was at 0.95 per USD in late April, hovering around 22-month lows as a hawkish fed lifted the dollar amid signals of a 50bps rate hike in the Funds rate at the bank’s next meeting. Meanwhile, the SNB has not shown plans to deviate from its ultra-loose monetary policy, as Chairman Jordan said current levels of inflation are temporary. In its last meeting, the SNB emphasized it would limit the franc’s appreciation after hitting a 7-year high against the euro following Russia’s invasion of Ukraine. Sight deposits at the SNB rose to CHF 742.6 billion in the week ending April 22, CHF 11.2 billion more than four weeks prior. The deposit increases are widely seen as a proxy for the central bank’s foreign currency interventions, dictating the amount of credit added on sight accounts of commercial banks with freshly created francs in exchange for foreign currency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-04-25 22:19:00 </td>
   <td style="text-align:left;"> Canadian Dollar Hits 6-Week Low </td>
   <td style="text-align:left;"> The Canadian dollar weakened to its lowest level in six weeks against the dollar, testing the $1.28 region, as investors sought safety amid concerns over the global growth outlook. China's worsening Covid-19 outbreak and uncertainty around the war in Ukraine added to fears sparked by faster Federal Reserve tightening. On the flip side, domestic inflation data cemented the narrative that the Bank of Canada will have to tighten more aggressively to tame broad price pressures. Canada's annual inflation rate accelerated faster than expected in March, hitting a 31-year high of 6.7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-25 22:18:51 </td>
   <td style="text-align:left;"> Canada Stocks Hit 2-Month Low </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, fell for the fourth session in a row on Monday, touching levels not seen since the Russian invasion of Ukraine, as the commodity-heavy index tracked oil and gold prices lower. Market sentiment was dominated by global growth woes, with downside risks gaining strength with the deterioration in China’s pandemic situation and the anticipation of a looming, aggressive tightening of monetary policy by major central banks. On corporate updates, National Bank of Canada analysts downgraded the price target of Precision Drilling by C$40 to C$180 per share. On the data front, wholesales sales in Canada fell 0.3% in March, after falling 0.4% in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/sp-500-fall-sharply-bear-market-morgan-stanley </td>
   <td style="text-align:left;"> 2022-04-25 22:17:06 </td>
   <td style="text-align:left;"> S&amp;P 500 about to fall sharply as it teeters on brink of bear market, Morgan Stanley says </td>
   <td style="text-align:left;"> FOX Business host provides insight on the stock market on 'Making Money.'                                                                                                                                                                                                                                                                                                                    , The S&amp;P 500 is poised to fall sharply as investors flee risks assets on fears over a recession, aggressive tightening by the Federal Reserve and the hottest inflation in four decades, according to Morgan Stanley analysts.                                                                                                                                                                , In a Monday note to investors, Morgan Stanley analysts, led by Michael Wilson, warned the S&amp;P 500 appears "ready to join the ongoing bear market." The index has plunged in recent weeks and extended a sharp selloff on Monday as worries over a potential COVID-19 lockdown in China rattled investors.                                                                                    , FED RAISES INTEREST RATES FOR FIRST TIME IN 3 YEARS, PROJECTS 6 MORE HIKES AS INFLATION SURGES                                                                                                                                                                                                                                                                                               , In the past month, the benchmark S&amp;P index has dropped about 6.6%. It is down about 11.1% so far this year.                                                                                                                                                                                                                                                                                  , "With defensives the latest big outperformer, they are now expensive, leaving very few places to hide," Morgan Stanley analysts wrote in a Monday note. "This suggests the S&amp;P 500 will finally catch up to the average stock and enter a bear market."                                                                                                                                      , In the past month, the benchmark S&amp;P index has dropped about 6.6%. It is down about 11.1% so far this year. (AP Photo/Mark Lennihan / AP Newsroom)                                                                                                                                                                                                                                           , They said the increasingly hawkish Fed is looking "right into the teeth of a slowdown," and that there is little upside for defensive positioning lately.                                                                                                                                                                                                                                    , "The market has been so picked over at this point, it’s not clear where the next rotation lies. In our experience, when that happens, it usually means the overall index is about to fall sharply with almost all stocks falling in unison," the analysts wrote.                                                                                                                             , The note comes amid growing fears that the Fed could inadvertently trigger an economic downturn as it takes a more hawkish approach to fighting inflation, which is at the highest level since December 1981. Policymakers raised rates by a quarter-percentage point in March, and have since signaled that sharper, half-point increases are likely in the coming months, beginning in May., "It is appropriate to be moving a little more quickly," Fed Chairman Jerome Powell said last week during a panel discussion at the International Monetary Fund and World Bank spring meetings. "I also think there’s something in the idea of front end-loading whatever accommodation one thinks is appropriate. So that points in the direction of 50-basis points being on the table."    , Traders are now pricing in a 100% chance of at least a half-point rate jump when policymakers meet on May 3-4. It would mark the first time since 2000 that the U.S. central bank raised the federal funds rate by 50 basis points.                                                                                                                                                          , People enter the Morgan Stanley headquarters building in New York on April 11, 2018. (Christopher Lee/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                             , Some economists believe the Fed waited too long to confront the burst in inflation, while others have expressed concerns that moving too quickly to stabilize prices risks triggering an economic recession. Hiking interest rates tends to create higher rates on consumer and business loans, which slows the economy by forcing employers to cut back on spending.                        , Powell has pushed back against concern that further tightening by the central bank will trigger a recession and has maintained optimism that the Fed can strike a delicate balance between taming inflation without crushing the economy.                                                                                                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                  , Still, he acknowledged the difficulty of the task ahead and said it is "absolutely essential" for central bankers to restore price stability.                                                                                                                                                                                                                                                , "Our goal is to use our tools to get demand and supply back in sync, so inflation moves back into place, without a slowdown that amounts to a recession," Powell said. "I don't think you'll hear anyone at the Fed say that's straightforward and easy. It's going to be challenging." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/live/2022/04/25/business/elon-musk-twitter </td>
   <td style="text-align:left;"> 2022-04-25 22:01:08 </td>
   <td style="text-align:left;"> Elon Musk and Twitter Reach $44 Billion Deal: Live Updates - The New York Times </td>
   <td style="text-align:left;"> Twitter agreed to be taken over at $54.20 a share, a 38 percent premium over the share price before it was revealed that Mr. Musk had been buying up the company’s stock.                                                                                                                                                                                                                                                                                                                                                      , RIGHT NOW                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Regulators are unlikely to block Musk’s purchase of Twitter, former officials say.                                                                                                                                                                                                                                                                                                                                                                                                                                             , Musk’s deal for Twitter is worth about $44 billion.                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , How Twitter’s staff reacted at a meeting after the announcement.                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Here’s what we know about how Musk will pay for Twitter.                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Twitter’s closing price on Monday suggests that traders think this deal is real.                                                                                                                                                                                                                                                                                                                                                                                                                                               , Musk’s takeover of Twitter gets the full Twitter treatment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , 4 ways Twitter could change under Elon Musk.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Elon Musk struck a deal on Monday to buy Twitter for roughly $44 billion, in a victory by the world’s richest man to take over the influential social network frequented by world leaders, celebrities and cultural trendsetters.                                                                                                                                                                                                                                                                                              , Twitter agreed to sell itself to Mr. Musk for $54.20 a share, a 38 percent premium over the company’s share price this month before he revealed he was the firm’s single largest shareholder. It would be the largest deal to take a company private — something Mr. Musk has said he will do with Twitter — in at least two decades, according to data compiled by Dealogic.                                                                                                                                                  , “Free speech is the bedrock of a functioning democracy, and Twitter is the digital town square where matters vital to the future of humanity are debated,” Mr. Musk said in a statement announcing the deal. “Twitter has tremendous potential — I look forward to working with the company and the community of users to unlock it.”                                                                                                                                                                                          , The deal, which has been unanimously approved by Twitter’s board, is expected to close this year, subject to a vote of Twitter shareholders and certain regulatory approvals.                                                                                                                                                                                                                                                                                                                                                  , The blockbuster agreement caps what had seemed an improbable attempt by the famously mercurial Mr. Musk, 50, to buy the social media company — and immediately raises questions about what he will do with the platform and how his actions will affect online speech globally.                                                                                                                                                                                                                                                , The billionaire, who has more than 83 million followers on Twitter and has romped across the service hurling gibes and memes, has repeatedly said he wants to “transform” the platform by promoting more free speech and giving users more control over what they see on it. By taking the company private, Mr. Musk could work on the service out of sight of the prying eyes of investors, regulators and others.                                                                                                            , Yet scrutiny will likely be intense. Twitter is not the biggest social platform — it has more than 217 million daily users, compared with billions for Facebook and Instagram — but it has had an outsized role in shaping narratives around the world. Political leaders have used it as a megaphone, while companies, celebrities and others have employed it for image-making and brand building.                                                                                                                           , In recent years, Twitter has also become a lightning rod for controversy, as some users spread misinformation and other toxic content on the service. Former President Donald J. Trump frequently turned to Twitter to insult and inflame, before getting barred from the platform after the Jan. 6 riot at the Capitol last year. The company has repeatedly been forced to create policies on the fly to deal with unexpected situations.                                                                                    , In a statement, Bret Taylor, Twitter’s chairman, said the board had “conducted a thoughtful and comprehensive process to assess Elon’s proposal with a deliberate focus on value, certainty, and financing. The proposed transaction will deliver a substantial cash premium, and we believe it is the best path forward for Twitter’s stockholders.”                                                                                                                                                                          , Mr. Musk himself has had a rocky relationship with online speech. This year, he tried to quash a Twitter account that tracked the movements of his private jet, citing personal and safety reasons. On Monday, he tweeted that he hoped his worst critics would remain on Twitter because “that is what free speech means.”                                                                                                                                                                                                    , “Without any conditions for Musk to purchase Twitter, the platform’s community standards and recourse to ban users who violate those standards, Twitter could set a dangerous precedent for other social media companies to follow,” said Bridget Todd, director at UltraViolet, a women’s rights organization. “This is a massively slippery slope.”                                                                                                                                                                          , Beyond speech issues, Twitter faces questions about its business. For years, the company has struggled to gain new users and to keep people coming back to the service. Its advertising business, which is the main way Twitter makes revenue, has been inconsistent. Twitter has not turned a profit for eight of the last 10 years.                                                                                                                                                                                          , — Mike Isaac and Lauren Hirsch                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Twitter’s chief executive, Parag Agrawal, met with employees on Monday afternoon to discuss the sale of the social media company to Elon Musk. Mr. Agrawal was joined by Bret Taylor, the chair of Twitter’s board, for the employee question-and-answer session.                                                                                                                                                                                                                                                              , In a nearly hourlong meeting, employees grilled Mr. Agrawal and Mr. Taylor about how the deal came to be, what would happen to their compensation and jobs, and how Mr. Musk might change Twitter.                                                                                                                                                                                                                                                                                                                             , “It’s important to acknowledge that all of you have many different feelings about what is happening,” Mr. Agrawal said, according to two people who attended the meeting and were not authorized to speak publicly. “Some of you are concerned, some are you are excited, and some of you are waiting to see how this goes. I know this affects all of you personally.”                                                                                                                                                        , “It is an emotional day,” Mr. Taylor added, “and I just want to acknowledge it.” A Twitter spokesman declined to comment on the meeting.                                                                                                                                                                                                                                                                                                                                                                                       , Employees had been frustrated that Twitter management was silent as it hashed out the terms of the agreement with Mr. Musk, who has said that he would change much about the way Twitter operates, including the policies it uses to moderate tweets. In a statement on Monday, Mr. Musk said he would focus on “new features, making the algorithms open source to increase trust, defeating the spam bots and authenticating all humans.”                                                                                    , Twitter workers have fretted about the impact on their stock compensation as Mr. Musk transformed Twitter into a private company, and about the cultural changes he would cause. But others have celebrated Mr. Musk’s bid for the company and said they believed his impact would be positive.                                                                                                                                                                                                                                , Mr. Agrawal told employees that their stock options would convert to cash when the deal with Mr. Musk closes, which he estimated would take three to six months, and that they would continue to receive bonuses according to Twitter’s vesting schedule. Employees would receive their same benefits packages for a year after the deal was finalized, Mr. Agrawal added, according to the two people familiar with the meeting.                                                                                              , In response to a question from an employee about whether former President Donald J. Trump would be allowed back on Twitter, Mr. Agrawal deferred, leaving the question for Mr. Musk to answer once he takes over the company. “We constantly evolve our policies,” Mr. Agrawal said. “Once the deal closes, we don’t know what direction this company will go in.”                                                                                                                                                             , Mr. Taylor addressed employees’ concerns about his silence. “I know there were a ton of twists and turns along the way, all of it in public, and I know we weren’t able to share all the info with you,” but he and Mr. Agrawal were bound by their fiduciary duty to shareholders to keep quiet and not share updates with employees, he said.                                                                                                                                                                                , Twitter’s board of directors will be disbanded when the company goes private, Mr. Taylor said. Although the board had enacted a defensive tactic known as a “poison pill” to block Mr. Musk from acquiring more Twitter shares, Mr. Taylor said the move was not intended to prevent Mr. Musk from buying the company but simply to put the negotiation process back in the board’s control.                                                                                                                                   , Mr. Agrawal told employees that they should continue to work on their current projects, and that he would try to arrange time for them to ask questions of Mr. Musk. He confirmed that he would keep working, too, remaining as chief executive at least until the deal with Mr. Musk closes.                                                                                                                                                                                                                                  , “He wants Twitter to be a powerful, positive force in the world, just like all of us,” Mr. Agrawal said of Mr. Musk, noting that he had spoken with the billionaire only a few times and was drawing assumptions from those conversations. “He believes Twitter matters.”                                                                                                                                                                                                                                                      , He urged employees to “operate Twitter as we always have,” adding that “how we run the company, the decisions we make and the positive changes we drive — that will be on us, and under our control.”                                                                                                                                                                                                                                                                                                                          , — Mike Isaac and Kate Conger                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Regulators may examine Elon Musk’s purchase of Twitter but are unlikely to sue to block it, former antitrust officials said on Monday.                                                                                                                                                                                                                                                                                                                                                                                         , Bill Baer, who led the Justice Department’s antitrust division during the Obama administration, said enforcers would “look hard to see whether there is a risk to competition and to consumers.” The big price tag, roughly $44 billion, will require Twitter and Mr. Musk to submit the deal for review by the Justice Department or the Federal Trade Commission, the two agencies that regulate acquisitions.                                                                                                               , Officials at both have pledged to take a closer look at how mergers and acquisitions fuel concentration in the technology industry. The F.T.C. has sued Facebook on the grounds that the company’s purchase of Instagram and WhatsApp stamped out possible future competitors.                                                                                                                                                                                                                                                 , But Mr. Musk’s acquisition of Twitter isn’t the kind of deal the government usually challenges. The government most commonly intervenes when a company is buying a competitor. It also sometimes challenges deals when the acquisition will unfairly benefit the purchaser in another part of its business. Mr. Musk’s two major holdings — the electric carmaker Tesla and the rocket company SpaceX — don’t compete with Twitter, and it is not clear that he will try to link them to the social network in any way.        , “It seems to me he has a major stake in two transportation companies at the moment,” said William Kovacic, a former chair of the F.T.C. “And it’s hard to see how Twitter has much to do with either one of them.”                                                                                                                                                                                                                                                                                                             , A spokeswoman for the Justice Department and a spokesman for the F.T.C. declined to comment.                                                                                                                                                                                                                                                                                                                                                                                                                                   , — David McCabe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The biggest question Wall Street has been asking since Elon Musk said he wanted to buy Twitter was: How would he fund such a deal? Mr. Musk is the richest person in the world, with a net worth well north of $200 billion. But his wealth is mostly tied up in Tesla stock.                                                                                                                                                                                                                                                  , According to securities filings, Mr. Musk is paying with $13 billion in bank loans, plus another $12.5 billion in loans against his stock in Tesla. He has pledged another $21 billion in cash to buy the rest of Twitter’s equity.                                                                                                                                                                                                                                                                                            , Mr. Musk did not answer one of the biggest remaining questions on Monday: the source of that $21 billion. One of the most obvious paths would be to sell shares in Tesla, which were trading at $978 a share on Monday afternoon. He also owns various other private companies, including the Boring Company, a tunnel development company recently valued at almost $6 billion, and SpaceX, which was valued at $100 billion last year. He could sell stakes in those companies to generate cash.                             , — Lauren Hirsch                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Twitter’s share price rose throughout the day on Monday as a deal with Elon Musk appeared increasingly likely. It gained more ground after the acquisition was announced, closing up 5.7 percent at $51.70 per share.                                                                                                                                                                                                                                                                                                          , Source: Sentieo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , By The New York Times                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , That’s not far below the $54.20 price agreed to in the deal with Mr. Musk, which shareholders will receive when the acquisition is made official and Twitter becomes a private company. The share price is also closer to Mr. Musk’s offer than it was at any other time during the takeover saga, a sign that investors ultimately expect the deal to be sealed with a vote from Twitter shareholders and subsequent regulatory checks.                                                                                       , When Mr. Musk announced his “best and final” offer at $54.20 on April 14, traders were more skeptical. For days after, Twitter’s shares traded in the mid-40s, far from Mr. Musk’s bid price, signaling that the markets weren’t sure the negotiations would yield an agreement on those terms. After all, Twitter’s board had announced a so-called poison pill defense maneuver, making it harder for Mr. Musk to get his way without approval from the board.                                                               , But then, Mr. Musk detailed the financial commitments from banks to help finance his offer, marking a turning point in the negotiations. A deal has now been agreed upon, and investors think that there is little to stop it from taking place.                                                                                                                                                                                                                                                                               , — Jason Karaian                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Twitter users voiced a mix of excitement, worry and skepticism on Monday about Elon Musk’s takeover of the site. And perhaps unsurprisingly, the reaction reflected the divided political and cultural nature of the running conversation on the platform.                                                                                                                                                                                                                                                                     , The news generated multiple trending topics on Twitter, including Mr. Musk’s name and the hashtags #RIPTwitter and #twittersold.                                                                                                                                                                                                                                                                                                                                                                                               , Many raised questions about Mr. Musk’s plans for the company.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , John Scott-Railton, a researcher at the University of Toronto’s Citizen Lab, wrote: “Does Musk plan to let Trump back on the platform? Will he look at the DMs of perceived enemies?” he asked, referring to Twitter’s private, direct messaging feature.                                                                                                                                                                                                                                                                      , Two questions:- Does Musk plan to put Trump back on Twitter?- Will he look at the DMs of perceived enemies?                                                                                                                                                                                                                                                                                                                                                                                                                    , Officials and policymakers, in the United States and beyond, shared their opinions, showing how the site had become a sort of political battleground.                                                                                                                                                                                                                                                                                                                                                                          , Senator Ted Cruz, Republican of Texas, posted a poll for Twitter followers, asking: “Is Elon Musk’s purchase of Twitter a good thing?” The two answer choices — “Yes” and “No, I hate free speech” — seemed to suggest his support for the move.                                                                                                                                                                                                                                                                               , Gov. Ron DeSantis, Republican of Florida, wrote that Elon Musk’s offer to buy Twitter was “a good deal for shareholders and raises the prospect that the platform will be a place where free speech can thrive, not a tool for narrative enforcement.”                                                                                                                                                                                                                                                                         , .@elonmusk’s offer to buy Twitter is a good deal for shareholders and raises the prospect that the platform will be a place where free speech can thrive, not a tool for narrative enforcement.                                                                                                                                                                                                                                                                                                                                , Nigel Farage, the British politician who pushed for a hard-line break with the European Union, wrote on Twitter: “Great news. Many congrats, Elon Musk. Let’s hope this marks a turning point.”                                                                                                                                                                                                                                                                                                                                , On the other side of the political spectrum, lawmakers were concerned about Mr. Musk’s motives and his wealth. “Tax the rich,” wrote Representative Pramila Jayapal, Democrat of Washington. “It’s absurd that one person can afford to buy Twitter for more than $40 billion while working families across this country have to choose every day between buying groceries or their prescription drugs.”                                                                                                                       , Senator Elizabeth Warren, Democrat of Massachusetts, shared a similar message: “This deal is dangerous for our democracy. Billionaires like Elon Musk play by a different set of rules than everyone else, accumulating power for their own gain. We need a wealth tax and strong rules to hold Big Tech accountable.”                                                                                                                                                                                                         , Robert Reich, a labor secretary under former President Bill Clinton, touched on many progressives’ fears when he wrote on the site: “When billionaires like Elon Musk justify their motives by using ‘freedom,’ beware. What they actually seek is freedom from accountability.”                                                                                                                                                                                                                                               , When billionaires like Elon Musk justify their motives by using “freedom,” beware. What they actually seek is freedom from accountability.                                                                                                                                                                                                                                                                                                                                                                                     , In the business world, allies of Mr. Musk were optimistic. Keith Rabois, a venture capitalist who worked at PayPal with Mr. Musk, earlier on Monday posted, “Ok, now I can finally start to Tweet.”                                                                                                                                                                                                                                                                                                                            , The entertainment world also took notice. Ice Cube, the rapper and actor, wrote on Twitter: “Free at last!” He tagged Mr. Musk and wrote, “Take off my shadow ban homie,” referring to a subtle form of limiting a user’s posts without letting them know.                                                                                                                                                                                                                                                                     , Others voiced fears about harassment on the platform, after Mr. Musk said he would change content moderation. Users of social media sites like Twitter, Instagram and TikTok have long complained that harassment is rampant, even with current content moderation efforts.                                                                                                                                                                                                                                                    , Dr. Peter Hotez, a vaccine researcher who has frequently spoken publicly about receiving threats online after speaking about pandemic safety measures, has said he is forced to block two to four people or groups most days “due to their menacing tweets or threats.” He said on Twitter that he would seek an alternative to the site if the hateful responses to him significantly increased.                                                                                                                              , My take on Twitter: Each day I block 2-4 individuals or groups on average due to their menacing tweets or threats. That increases X10-20 when FoxNews anchors send out an evening dog whistle/attack. If under Elon Musk things remain as is, I suppose I will probably tolerate it, but                                                                                                                                                                                                                                       , And some voiced concerns that people would leave the platform. “This is like a season finale of Twitter,” wrote Jane Manchun Wong, a technology blogger and researcher.                                                                                                                                                                                                                                                                                                                                                        , But others called quitting Twitter a dramatic response. “I doubt anyone’s really leaving Twitter,” read a post from the Twitter account for Spawn Wave, a YouTube platform mostly for tech reviews and video game content. “There’s just too much stuff for us to complain about nowadays.”                                                                                                                                                                                                                                    , — Melina Delkic                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Elon Musk can at times be inscrutable, and his politics are elusive, which has made it somewhat difficult to determine exactly what the billionaire would do if he successfully acquired Twitter. But over the past weeks and months, as he neared Monday’s deal with the company, Mr. Musk has given more hints about what he would change about Twitter — in interviews, regulatory filings and, of course, on his Twitter account.                                                                                          , Here are the main areas Mr. Musk could seek to address:                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Free speech and content moderators. Mr. Musk has frequently expressed concern that Twitter’s content moderators go too far and intervene too much on the platform, which he sees as the internet’s “de facto town square.”                                                                                                                                                                                                                                                                                                     , He brought up those concerns once again in the release announcing the agreement: “Free speech is the bedrock of a functioning democracy, and Twitter is the digital town square where matters vital to the future of humanity are debated,” Mr. Musk said.                                                                                                                                                                                                                                                                     , “I also want to make Twitter better than ever by enhancing the product with new features, making the algorithms open source to increase trust, defeating the spam bots, and authenticating all humans” he added. “Twitter has tremendous potential — I look forward to working with the company and the community of users to unlock it.”                                                                                                                                                                                      , 🚀💫♥️ Yesss!!! ♥️💫🚀 pic.twitter.com/0T9HzUHuh6                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , In a tweet on Monday, ahead of the announcement of his agreement with Twitter, Mr. Musk said he hoped even his “worst critics” continued to use the platform “because that is what free speech means.”                                                                                                                                                                                                                                                                                                                         , The Trump question. Mr. Musk has not commented publicly on how he would handle the former President Donald Trump’s banned Twitter account. But his free speech comments have stoked speculation that Twitter under his ownership might reinstate Mr. Trump, who was barred from the platform last year. After the Jan. 6 riot at the Capitol, Twitter said Mr. Trump had violated its policies by inciting violence among his supporters. Facebook also banned Mr. Trump for the same reason.                                  , The former president, who was known for tweets that criticized opponents and sometimes announced policy changes, is also trying to get his own social media site off the ground. His start-up, Truth Social, has struggled to attract users, and the problem could get worse now that Mr. Musk has suggested changing content moderation rules on Twitter. Mr. Trump said in a recent interview that he probably wouldn’t rejoin Twitter.                                                                                      , The algorithm. At a TED conference this month, he elaborated on his plans to make the company’s algorithm an open-source model, which would allow users to see the code showing how certain posts came up in their timelines.                                                                                                                                                                                                                                                                                                  , He said the open-source method would be better than “having tweets sort of be mysteriously promoted and demoted with no insight into what’s going on.”                                                                                                                                                                                                                                                                                                                                                                         , Mr. Musk has also pointed to the politicization of the platform before, and recently tweeted that any social media platform’s policies “are good if the most extreme 10 percent on left and right are equally unhappy.”                                                                                                                                                                                                                                                                                                        , A social media platform’s policies are good if the most extreme 10% on left and right are equally unhappy                                                                                                                                                                                                                                                                                                                                                                                                                      , Who uses the platform and how. Before Mr. Musk offered to buy Twitter this month, he expressed concern about the relevance of the platform.                                                                                                                                                                                                                                                                                                                                                                                    , When an account posted a list of the 10 most followed Twitter accounts, including former President Barack Obama and the pop stars Justin Bieber and Katy Perry, Mr. Musk responded and wrote: “Most of these ‘top’ accounts tweet rarely and post very little content. Is Twitter dying?”                                                                                                                                                                                                                                      , More recently, the Tesla chief executive promised in a tweet Thursday that he would “defeat the spam bots or die trying!”                                                                                                                                                                                                                                                                                                                                                                                                      , If our twitter bid succeeds, we will defeat the spam bots or die trying!                                                                                                                                                                                                                                                                                                                                                                                                                                                       , — Melina Delkic                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Elon Musk made a centerpiece of his bid for Twitter the need to restrain what he sees as overly aggressive content moderation policies that limit what people can say on the site. He may face a major challenge fulfilling such a dream in Europe.                                                                                                                                                                                                                                                                            , On Saturday, European policymakers reached an agreement on landmark new legislation, called the Digital Services Act, which requires social media platforms like Twitter to more aggressively police their services for hate speech, misinformation and illicit content.                                                                                                                                                                                                                                                       , Under the new law, Twitter and other social media companies with more than 45 million users in the E.U. will be required to conduct annual risk assessments about the spread of harmful content on their platforms and outline plans to combat the problem. If they are not seen as doing enough, the companies can be fined up to 6 percent of global revenue, or even be banned from the E.U. for repeat offenses.                                                                                                           , The shifting laws in Europe illustrate the broader legal challenges Mr. Musk would inherit if he closes a deal to buy Twitter. Rather than having a single unified approach to policing its platform, the company has had to adjust based on the different laws where it operates. In Germany, Twitter removes flagged hate speech, racism and references to Nazism. In countries like Turkey, the company faces pressure to remove content critical of the ruling government. In Russia, the service has been largely blocked., — Adam Satariano                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Over the weekend, as negotiations for his takeover of Twitter were approaching their final stages, Elon Musk took a shot at fellow billionaire Bill Gates in a series of high-profile tweets. The messages were a reflection of Mr. Musk’s freewheeling style on the social network, where he has more than 80 million followers, mixing serious messages and more sophomoric material.                                                                                                                                        , Mr. Musk said Mr. Gates had taken a short position in Tesla’s stock, betting that it would fall. Mr. Musk was responding to a tweet that included screenshots of texts he apparently exchanged with Mr. Gates about potential philanthropic projects. Minutes later, he mocked Mr. Gates’s physical appearance in a tweet that got 1.1 million “likes.”                                                                                                                                                                        , On Sunday, before a pivotal meeting between him and Twitter’s board, Mr. Musk tweeted that he was “moving on” from “making fun of Gates for shorting Tesla while claiming to support climate change action.”                                                                                                                                                                                                                                                                                                                   , (from making fun of Gates for shorting Tesla while claiming to support climate change action)                                                                                                                                                                                                                                                                                                                                                                                                                                  , The DealBook newsletter notes that the tweets may be a glimpse at how Twitter would run under Mr. Musk’s ownership. Critics say they were just the latest example of Mr. Musk using the platform, and his enormous following on it, as a bully pulpit, whether directed at billionaires or others.                                                                                                                                                                                                                             , Mr. Musk has said he wants Twitter to fulfill its “societal imperative” as a platform for free speech. But as DealBook has reported, that raises questions about what will happen to Twitter under his watch, given the tone he is setting and the problems that plagued the network’s previous chief executive, Jack Dorsey, before he embraced a more rules-based approach to content moderation.                                                                                                                            , Mr. Dorsey had said that he “didn’t fully predict or understand the real-world negative consequences” of a more unfettered service.                                                                                                                                                                                                                                                                                                                                                                                            , Truth Social is slow and clunky. Its audience participation remains low. Two top executives have left. And the merger that could bring $1.3 billion in desperately needed cash to former President Donald J. Trump’s social media project seems far from completion.                                                                                                                                                                                                                                                           , And that was before Elon Musk entered the picture, The Times’s Matthew Goldstein, Kenneth P. Vogel and Ryan Mac report.                                                                                                                                                                                                                                                                                                                                                                                                        , Mr. Musk’s acquisition of Twitter is the latest challenge for Trump Media &amp; Technology Group’s flagship Truth Social app, which Mr. Trump has positioned as Twitter’s freewheeling conservative counterpart. Truth Social, which is available only for Apple devices, has 1.3 million installs, Sensor Tower, an app insights company, estimated. By comparison, Twitter has more than 200 million active users.                                                                                                               , Mr. Musk announced a deal with Twitter Monday morning after announcing that he had lined up $46.5 billion in financing for his takeover bid. In recent weeks, Mr. Musk has said he would loosen the Twitter moderation policies that he has chafed under — and that famously led the service to bar Mr. Trump for inciting violence over the outcome of the 2020 presidential election.                                                                                                                                        , Although Mr. Musk has not said if he would allow Mr. Trump to return to the platform, his ideas for easing Twitter’s rules would further sap the appeal of Mr. Trump’s beleaguered start-up as it faces a regulatory investigation that could decide its future.                                                                                                                                                                                                                                                               , Trump Media declined to comment on Mr. Musk’s Twitter bid. Liz Harrington, a spokeswoman for Mr. Trump, pointed to a recent interview with Americano Media in which the former president said he “probably wouldn’t rejoin Twitter if he could.”                                                                                                                                                                                                                                                                               , READ THE FULL ARTICLE →                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Before Twitter and Elon Musk struck a deal on Monday for him to acquire the company, Twitter employees were searching for answers about how Mr. Musk’s takeover could affect them and the company.                                                                                                                                                                                                                                                                                                                             , They said they were frustrated because they weren’t hearing much from management about what was going on with the takeover fight and what it meant for them, even as Twitter closed in on a deal with Mr. Musk. They asked their chief executive, Parag Agrawal. They asked Mr. Musk himself in questions sent on Twitter. Some even went to Charles Schwab, the financial firm that manages their stock options, for clarity about the impact a sale of the company would have on them.                                       , But they were not getting very many answers, even as it became clear that they could soon find themselves reporting to Mr. Musk. This is according to 11 Twitter employees who asked to not be named in interviews with The Times’s Kate Conger because they were not authorized to speak publicly. Some employees vented their frustrations on Twitter on Monday, ahead of Twitter’s announcement of its deal with Mr. Musk, while others commiserated in private chats.                                                      , Employees said they worried that Mr. Musk would undo the years of work they have put into cleaning up the toxic corners of the platform, upend their stock compensation in the process of taking the company private, and disrupt Twitter’s culture with his unpredictable management style and abrupt proclamations.                                                                                                                                                                                                          , But Mr. Musk also has fans among Twitter’s rank-and-file, and some employees have welcomed his bid.                                                                                                                                                                                                                                                                                                                                                                                                                            , READ THE FULL ARTICLE →                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , On April 4, Elon Musk revealed that he had purchased a sizable stake in Twitter. Three weeks later, Mr. Musk and Twitter have reached a deal for the billionaire to acquire the social media company entirely and take it private.                                                                                                                                                                                                                                                                                             , Here are highlights of our coverage of the twists and turns in this saga:                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Elon Musk Becomes Twitter’s Largest Shareholder (April 4): The Tesla chief executive, who has been critical of Twitter’s content moderation policies, has bought 9.2 percent of the social media company.                                                                                                                                                                                                                                                                                                                      , Elon Musk Joins Twitter’s Board, Pitching Ideas Big and Small (April 5): Free speech, open-source algorithms — and an edit button: The world’s richest person will soon help steer the social media platform where he has a huge following.                                                                                                                                                                                                                                                                                    , Elon Musk Will Not Join Twitter’s Board, Company Says (April 10): The announcement reverses a decision made days earlier. By not joining Twitter’s board, Mr. Musk will also no longer be bound by a previous agreement he had signed with the company.                                                                                                                                                                                                                                                                        , Elon Musk, After Toying With Twitter, Now Wants It All (April 14): The billionaire executive recently became one of the company’s largest shareholders. Now he says he wants to buy the whole thing and change how it handles speech.                                                                                                                                                                                                                                                                                          , Twitter Counters a Musk Takeover With a Time-Tested Barrier (April 15): With a “poison pill” defense, Twitter seems intent on fending off the billionaire’s bid to buy it.                                                                                                                                                                                                                                                                                                                                                     , Elon Musk Races to Secure Financing for Twitter Bid (April 19): Mr. Musk is trying to shore up debt financing, including potentially taking out a loan against his shares of Tesla.                                                                                                                                                                                                                                                                                                                                            , Elon Musk Details Plan for $46.5 Billion Twitter Takeover (April 21): The financial commitments from a group of banks put pressure on the social media company’s board to take his advances seriously.                                                                                                                                                                                                                                                                                                                         , Twitter in Advanced Talks to Sell Itself to Elon Musk (April 24): The company’s 11-member board held negotiations with Mr. Musk over his offer to buy the social networking service.                                                                                                                                                                                                                                                                                                                                           , Elon Musk Buys Twitter (April 25): The Tesla chief executive struck a deal to buy the site for roughly $44 billion. Twitter agreed to sell itself for $54.20 a share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-04-25 22:01:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index at Over 3-Week High </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index rose about 2.1% to 2,356 on Monday, the highest since April 1st, extending gains for the third straight session. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, jumped 8.6% to its highest in over a month at 2,003 points; and the supramax index rose 21 points to 2,699 points. Meanwhile, the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, went down 1.2% to 2,967 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/business-confidence </td>
   <td style="text-align:left;"> 2022-04-25 21:55:14 </td>
   <td style="text-align:left;"> Belgium Business Morale Rebounds in April </td>
   <td style="text-align:left;"> The business confidence barometer in Belgium rose to 2.4 points in April of 2022, rebounding from the one-year low of 0.4 in the prior month. Sentiment significantly rebounded for trade (0.3 vs -6.5 in March), largely due to higher intentions of placing orders and demand expectations. Sentiment also rebounded for the manufacturing industry (0.5 vs -2.7) and improved in the building industry (2.1 vs 1.2). On the other hand, confidence eased for business-related services (11.7 vs 15.1). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-25 21:41:00 </td>
   <td style="text-align:left;"> Brazilian Equities Down for 6th Day </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, fell over 1% to below the 110,000 level on Monday, for the first time since March 15th, extending losses for the sixth straight session. Fresh worries that spreading Covid cases and more lockdowns in China will hurt the global economy added to concerns that Federal Reserve tightening could also weaken growth prospects. At the same time, the war in Ukraine entered the third month, with no end in sight. Among single stocks, heavyweights Petrobras and miner Vale were the main draggers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-25 21:33:00 </td>
   <td style="text-align:left;"> Wall Street Extends Losses </td>
   <td style="text-align:left;"> US stocks extended losses on Monday, amid concerns about Covid-19 lockdowns in China and subsequent supply chain disruptions that could further spur inflation currently running at a 4-decades high, that has already prompted the Federal Reserve to signal big increases in the fed funds rate this year. Among single stocks, Twitter shares climbed on reports the company is in advance talks to sell itself to Elon Musk and a deal could be reached as soon as Monday. Equities of Coca-Cola also gained after it reported stronger-than-expected Q1 results. The Dow Jones lost more than 350 points to a 6-week low below 33,400, the S&amp;P 500 was down over 1% and the Nasdaq 0.5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-04-25 21:32:25 </td>
   <td style="text-align:left;"> Gasoline is down by 5% </td>
   <td style="text-align:left;"> Gasoline decreased 5% to 3.1399 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ko:us </td>
   <td style="text-align:left;"> 2022-04-25 21:30:25 </td>
   <td style="text-align:left;"> Coca-Cola earnings above expectations at 0.64 USD </td>
   <td style="text-align:left;"> Coca-Cola (KO) released earnings per share at 0.64 USD, compared to market expectations of 0.58 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/crypto </td>
   <td style="text-align:left;"> 2022-04-25 21:22:19 </td>
   <td style="text-align:left;"> Bitcoin Falls to 6-Week Low </td>
   <td style="text-align:left;"> Bitcoin fell below $39,000 in late April, extending the month’s losses to a six-week low as hawkish outlooks from major central banks led investors to reallocate to the dollar and safer assets. Fed Chair Powell said a 50bps hike for the Funds rate is on the table for the next meeting, with policymakers previously stating the bank’s balance sheet could be run-off by $95 billion per month. Risk-off sentiment was also heightened after rising Covid cases in Beijing spurred concerns that the prolonged lockdowns in major Chinese cities may extend to the capital, furthering economic inactivity. Other cryptocurrencies also saw declines, with Ether falling to a five-week low of $2,860. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/morocco/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-25 21:20:49 </td>
   <td style="text-align:left;"> Morocco Consumer Prices Continue to Rise in March </td>
   <td style="text-align:left;"> The annual inflation rate in Morocco climbed to 5.3% in March of 2022 from 3.6% in the previous month, reaching its highest level since at least January of 2008. Main upward pressure came from price of food &amp; non-alcoholic beverages (9.4% vs 5.5% in February) and transportation (7.6% vs 6 percent). On a monthly basis, consumer prices inched up 1.8%, the most since at least January of 2007. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/elon-musk-buys-twitter </td>
   <td style="text-align:left;"> 2022-04-25 21:15:54 </td>
   <td style="text-align:left;"> Twitter accepts Musk's $44 billion deal </td>
   <td style="text-align:left;"> Domain Money founder and CEO Adam Dell argues Elon Musk has a ‘reasonable approach’ for the Twitter platform.                                                                                                                                                                                                                                                                                                                                                                                                      , Twitter shares popped over 5% on Monday after the company's board unanimously accepted Tesla CEO Elon Musk's $44 billion offer to take the social media giant private.                                                                                                                                                                                                                                                                                                                                             , ELON MUSK TAKES TO TWITTER TO EXPLAIN ‘WHAT FREE SPEECH’ MEANS                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Under the terms of the agreement, Twitter stockholders will receive $54.20 in cash for each share of common stock that they own upon closing of the proposed transaction. The purchase price represents a 38% premium to Twitter's closing stock price on April 1, the last trading day before Musk disclosed a 9.2% stake in the company.                                                                                                                                                                         , Musk has secured approximately $46.5 billion to finance the transaction, including $25.5 billion of fully committed debt and margin loan financing and $21 billion in equity financing. The transaction is expected to close in 2022, subject to the approval of Twitter stockholders, the receipt of applicable regulatory approvals and the satisfaction of other customary closing conditions.                                                                                                                  , Twitter independent board chairman Brett Taylor said the company "conducted a thoughtful and comprehensive process to assess Elon's proposal with a deliberate focus on value, certainty, and financing."                                                                                                                                                                                                                                                                                                          , TWITTER RE-EXAMINES MUSK'S BID AFTER TESLA CEO SECURES FINANCING: REPORT                                                                                                                                                                                                                                                                                                                                                                                                                                           , Musk, a self-described "free-speech absolutist," has been critical of the platform and its chief executive Parag Agrawal's approach to free speech.                                                                                                                                                                                                                                                                                                                                                                , "Free speech is the bedrock of a functioning democracy, and Twitter is the digital town square where matters vital to the future of humanity are debated," Musk said in a statement. "I also want to make Twitter better than ever by enhancing the product with new features, making the algorithms open source to increase trust, defeating the spam bots, and authenticating all humans. Twitter has tremendous potential – I look forward to working with the company and the community of users to unlock it.", Elon Musk and Parag Agrawal (Reuters | Twitter / Reuters Photos)                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Though Musk was initially invited to join Twitter's board, he later declined the offer. If he joined, Musk would have been unable to own more than 14.9% of Twitter's stock while serving on the board or for 90 days after. Musk's board term would have expired at Twitter’s 2024 annual meeting.                                                                                                                                                                                                                , Following Musk's offer, Twitter adopted a limited duration shareholder rights plan, commonly referred to as a poison pill, to prevent him or any other entity or group from acquiring beneficial ownership of 15% or more of Twitter's outstanding common stock in a transaction not approved by the board.                                                                                                                                                                                                        , Along with Musk's announcement that he lined up financing for a potential deal, he revealed that he was considering a tender offer to acquire all of Twitter's outstanding common stock.                                                                                                                                                                                                                                                                                                                           , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The agreement comes ahead of Twitter's first quarter earnings report on Thursday before the market open. In light of the pending transaction, Twitter will not hold a corresponding conference call.                                                                                                                                                                                                                                                                                                               , Musk told the TED2022 conference earlier this month that he intends to keep as many shareholders on board as possible through a private company. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/politics/2022/04/25/wall-street-journal-putin-rumored-girlfriend-reporting-newday-vpx.cnn </td>
   <td style="text-align:left;"> 2022-04-25 20:55:21 </td>
   <td style="text-align:left;"> WSJ: US government is holding off on sanctioning Putin's rumored girlfriend - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/currency </td>
   <td style="text-align:left;"> 2022-04-25 20:51:45 </td>
   <td style="text-align:left;"> Chinese Yuan Erases Some Losses </td>
   <td style="text-align:left;"> The offshore yuan was trading at 6.59 to the dollar, after the People’s Bank of China cut the reserve requirement ratio (RRR) for foreign currency deposits at banks to 8% from 9% starting May 15th aiming at increasing banks’ capabilities of forex fund use and to help liquidity management. The change would increase the supply of dollars and other currencies onshore and relieve the yuan’s weakness. Earlier the yuan weakened to a 17-month low at above $6.6 as fears grew that Beijing was on the verge of joining Shanghai in lockdowns, putting more downward pressure on China’s battered economy and raising the need for further policy easing. State media in China reported that residents were ordered not to leave Beijing’s Chaoyang district after a few dozen cases were detected over the weekend. Meanwhile, China's central bank set the yuan’s midpoint rate at an 8-month low on Monday, seen as an official nod to the currency’s recent slide. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/wholesale-sales </td>
   <td style="text-align:left;"> 2022-04-25 20:38:00 </td>
   <td style="text-align:left;"> Canada Wholesale Sales Seen Lower in March </td>
   <td style="text-align:left;"> Manufacturing sales in Canada likely fell by 0.3 percent form a month earlier in March of 2022, slightly slowing from the 0.4 percent decrease in the previous month, according to preliminary estimates. The decrease was underpinned by lower sales of machinery, equipment, and supplies (-4.2 percent), personal and household goods (-2.4 percent), and farm products (-1.6 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/chicago-fed-national-activity-index </td>
   <td style="text-align:left;"> 2022-04-25 20:37:27 </td>
   <td style="text-align:left;"> Chicago Fed National Activity Index at 3-Month Low </td>
   <td style="text-align:left;"> The Chicago Fed National Activity Index went down to 0.44 in March of 2022 from a downwardly revised 0.54 in February, the lowest in 3 months. Production-related indicators contributed +0.27, down slightly from +0.30 in February, and employment-related indicators contributed +0.16, down from +0.31. Meanwhile, the contribution of the personal consumption and housing category was unchanged at -0.04 while the contribution of the sales, orders, and inventories category moved up to +0.06 in March from -0.03. The index’s three-month moving average, CFNAI-MA3, increased to +0.57 in March from +0.43 in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/25/tech/elon-musk-twitter-sale-agreement/index.html </td>
   <td style="text-align:left;"> 2022-04-25 20:32:28 </td>
   <td style="text-align:left;"> Elon Musk to buy Twitter in $44 billion deal - CNN </td>
   <td style="text-align:left;"> New York (CNN)Twitter said Monday it has agreed to sell itself to Elon Musk in a roughly $44 billion deal that has the potential to expand the billionaire's business empire and put the world's richest man in charge of one of the world's most influential social networks.                                                                                                                                                                                                                                               , The deal, which will take the company private, caps off a whirlwind period in which the Tesla and SpaceX CEO became one of Twitter's largest shareholders, was offered and turned down a seat on its board and bid to buy the company — all in less than a month.                                                                                                                                                                                                                                                            , Under the terms of the deal, shareholders will receive $54.20 in cash for each share of Twitter stock they own, matching Musk's original offer and marking a 38% premium over the stock price the day before Musk revealed his stake in the company.                                                                                                                                                                                                                                                                         , "Free speech is the bedrock of a functioning democracy, and Twitter is the digital town square where matters vital to the future of humanity are debated," Musk said in a statement Monday. "Twitter has tremendous potential — I look forward to working with the company and the community of users to unlock it."                                                                                                                                                                                                         , The deal, which was unanimously approved by Twitter's board, is expected to close this year. It comes after Musk revealed last week he had lined up $46.5 billion in financing to acquire the company, an apparent turning point that forced Twitter's board to seriously consider the deal. The board met Sunday to evaluate Musk's offer.                                                                                                                                                                                  , "The Twitter Board conducted a thoughtful and comprehensive process to assess Elon's proposal with a deliberate focus on value, certainty, and financing," Twitter independent board chair Bret Taylor said in a statement, calling the deal " the best path forward for Twitter's stockholders."                                                                                                                                                                                                                            , Twitter stock was up nearly 6% following the announcement of the deal, hovering around $51.84, just shy of the offer price. The deal is pending approval from shareholders and regulators.                                                                                                                                                                                                                                                                                                                                   , In an internal message to employees obtained by CNN, Twitter CEO Parag Agrawal said he would hold an all-hands meeting with Taylor on Monday afternoon to answer questions about the deal. "I know this is a significant change and you're likely processing what this means for you and Twitter's future," he said.                                                                                                                                                                                                         , What Musk means for Twitter                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Musk is both a high-profile Twitter user and a controversial one. He has more than 83 million followers on the platform, which he has used over the years for everything from sharing memes and discussing his companies to insulting politicians, spreading misleading claims about Covid-19 and making offensive remarks about the transgender community.                                                                                                                                                                  , Musk has repeatedly stressed in recent days that his goal is to bolster free speech on the platform and work to "unlock" Twitter's "extraordinary potential."                                                                                                                                                                                                                                                                                                                                                                , In his statement Monday, Musk said he wants to "make Twitter better than ever by enhancing the product with new features, making the algorithms open source to increase trust, defeating the spam bots, and authenticating all humans." Separately, he said in a tweet Monday that he hopes "even my worst critics remain on Twitter, because that is what free speech means."                                                                                                                                               , Still, some industry experts worry that Musk's desire for free speech on Twitter could mean rolling back some of the platform's work to curb hate speech, misinformation, harassment and other harmful content. Others questioned whether Musk might restore former President Donald Trump's account, which was removed early last year for violating Twitter policies against inciting violence following the Capitol Riot. Such a move could have significant ramifications for the upcoming 2024 US presidential election., While Twitter is smaller than some social media rivals, it has an outsized influence in the online and offline worlds because it is used by many politicians, public figures and journalists, and has sometimes acted as a model for other platforms in how to handle harmful content.                                                                                                                                                                                                                                       , "Do not allow Twitter to become a petri dish for hate speech, or falsehoods that subvert our democracy," Derrick Johnson, president of the NAACP, said in a statement directed at Musk Monday following the deal.                                                                                                                                                                                                                                                                                                            , A new and uncertain era for Twitter                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , In the days since Musk's initial bid, many following the company wondered whether Twitter would try to find another buyer, especially after the company put in place a poison pill to make it more difficult for Musk to acquire the company without its approval.                                                                                                                                                                                                                                                           , But CFRA senior equity analyst Angelo Zino said Monday that Twitter's board more seriously considering Musk's offer may have come "from the Board's realization that an alternative bid from a 'white knight' may be difficult to come by, especially following the decline in asset prices from social media companies in recent weeks/months."                                                                                                                                                                             , It's not clear whether Agrawal — who took over the CEO role from founder Jack Dorsey in November — will remain in the top job following the takeover. Musk previously tweeted a meme comparing Agrawal to former Soviet leader Joseph Stalin. Musk also said in his offer letter to buy Twitter that he does not "have confidence in management."                                                                                                                                                                            , The deal could, however, put an end to nearly a decade of chaos at Twitter as a public company, during which it has cycled through CEOs, grappled with an activist investor and struggled to ignite growth and successfully monetize its influential user base.                                                                                                                                                                                                                                                              , Agrawal said in Monday's statement that "Twitter has a purpose and relevance that impacts the entire world," He added: "Deeply proud of our teams and inspired by the work that has never been more important."                                                                                                                                                                                                                                                                                                              , CNN Business tech reporter Clare Duffy can be reached at clare.duffy@cnn.com.                                                                                                                                                                                                                                                                                                                                                                                                                                                , CNN's Brian Stelter and Donie O'Sullivan contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-04-25 20:24:09 </td>
   <td style="text-align:left;"> US Natural Gas Recoups Earlier Losses </td>
   <td style="text-align:left;"> US natural gas futures bounced back to $6.6 per million British thermal units, after hitting a two-week low of $6.3 earlier in the session and pausing a rout that erased roughly 20% off a thirteen-year high of $8.065 hit in the previous week, as traders continued to assess the outlook for demand. Weather forecasts point to cooler-than-usual weather this week, which should keep demand above the 5-year average for longer. Still, EIA inventory data revealed a 53 billion cubic feet injection (bcf) last week, much more than a median estimate of 37bcf. For the year, the contract is up roughly 80%, as harsh wintry weather extended well into spring, causing domestic inventories to shrink well below the five-year average. At the same time, the US is exporting LNG cargoes at record levels, mainly to Europe, as the region scrambles to replace Russian gas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61209893?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-25 20:23:23 </td>
   <td style="text-align:left;"> Asda and Morrisons cut prices as supermarkets fight for customers </td>
   <td style="text-align:left;"> Morrisons and Asda are cutting prices as supermarkets face a fierce battle for customers with the soaring cost of living hitting households' finances.                                                                                                                         , Both supermarkets have been losing customers to discounters such as Aldi and Lidl as price pressures grow.                                                                                                                                                                     , Morrisons said it would offer an average 13% price cut on more than 500 goods including eggs, beef and rice.                                                                                                                                                                   , Meanwhile, Asda announced it had "dropped and locked in" prices on some products until the end of the year.                                                                                                                                                                    , The cost of living is rising at its fastest rate in 30 years in part due to soaring food prices.                                                                                                                                                                               , Morrisons, which is the UK's fourth-largest supermarket after Tesco, Sainsbury's and Asda, said the cuts would cover refrigerated, frozen and store cupboard food and affect around 6% of its total sales volume.                                                              , "We know that our customers are under real financial pressure at the moment and we want to play our part in helping them when it comes to the cost of grocery shopping," said boss David Potts.                                                                                , Items being discounted include cereal, cooking sauces, chicken and sausages as well as flour, bread and ham.                                                                                                                                                                   , Meanwhile, Asda said more than 100 products covered by its "dropped and locked" promise ranged from some fresh fruit and vegetables to fresh meat and frozen food.                                                                                                             , The supermarket said prices would drop by 12% on average.                                                                                                                                                                                                                      , "We know that household budgets are being squeezed by an increasing cost of living and we are committed to doing everything we can to support our customers, colleagues and communities in these exceptionally tough times," said Mohsin Issa, co-owner of Asda.               , The cost of living squeeze is starting to bite and shoppers are on the hunt for value in the supermarket aisles.                                                                                                                                                               , Recent industry data shows more people are ditching the big brands in favour of own-label products to save money.                                                                                                                                                              , They've also been turning to the discounters, Aldi and Lidl. After a tough pandemic, they've been growing market share.                                                                                                                                                        , Tesco and Sainsbury's have Aldi price-matching campaigns and have been performing better than Morrisons and Asda.                                                                                                                                                              , Now these two are fighting back. They need to. Morrisons and Asda have traditionally served budget conscious shoppers and can't afford to haemorrhage customers to the discounters.                                                                                            , Last month, Asda launched its Just Essentials range promising an expanded line of low-cost products in all its stores from May.                                                                                                                                                , In February, the grocer said it would offer a wider range of low-cost goods in its stores after being criticised by food poverty campaigner and chef Jack Monroe.                                                                                                              , Last week, the UK's largest supermarket chain, Tesco, said its profits last year more than trebled, but said its performance this year would be affected by the need to keep prices down.                                                                                      , Both Asda and Morrisons are losing out as customers turn to discounters Aldi and Lidl, to cut their costs, according to research firm Kantar.                                                                                                                                  , UK grocery price inflation hit 5.2% in the 12 weeks to 20 March, it said, its highest level since April 2012.                                                                                                                                                                  , In that time, Lidl and Aldi were the only big supermarkets to see their sales and market shares rise. By contrast, Morrisons and Asda saw the biggest drops in sales and market share.                                                                                         , Kantar's head of retail Fraser McKevitt said: "We're really starting to see the switch from the pandemic being the dominant factor driving our shopping behaviour towards the growing impact of inflation, as the cost of living becomes the bigger issue on consumers' minds.", In March, one food boss told the BBC food price inflation could rise as a high as 15% this year as a result of the war in Ukraine.                                                                                                                                             , Ronald Kers, the boss of food firm 2 Sisters, blamed the rising prices of wheat and natural gas, which is used to heat greenhouses and to make fertiliser.                                                                                                                     , How many miles do you need to drive before it pays off?                                                                                                                                                                                                                        , Gary Lineker on football, politics and road rage                                                                                                                                                                                                                               , Searching for Vladislav Surkov, key architect of the 'post truth' world                                                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/phg:us </td>
   <td style="text-align:left;"> 2022-04-25 20:21:47 </td>
   <td style="text-align:left;"> Koninklijke Philips earnings below expectations at 0.16 USD </td>
   <td style="text-align:left;"> Koninklijke Philips (PHG) released earnings per share at 0.16 USD, compared to market expectations of 0.26 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/atvi:us </td>
   <td style="text-align:left;"> 2022-04-25 20:21:32 </td>
   <td style="text-align:left;"> Activision Blizzard earnings below expectations at 0.64 USD </td>
   <td style="text-align:left;"> Activision Blizzard (ATVI) released earnings per share at 0.64 USD, compared to market expectations of 0.71 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/4519:jp </td>
   <td style="text-align:left;"> 2022-04-25 20:21:19 </td>
   <td style="text-align:left;"> Chugai Pharma earnings above expectations at 80.14 JPY </td>
   <td style="text-align:left;"> Chugai Pharma (4519) released earnings per share at 80.14 JPY, compared to market expectations of 53.41 JPY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/lithuania/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-25 20:14:27 </td>
   <td style="text-align:left;"> Lithuania 10Y Bond Yield Hits 7-year High </td>
   <td style="text-align:left;"> Lithuania 10 Year Government Bond Yeld increased to a 7-year high of 1.85% </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-04-26 06:45:46 UTC +8

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
   <td style="text-align:left;"> 2022-04-26 06:45:30 </td>
   <td style="text-align:left;"> $SPY $QQQ sorry to break it to you guys but this clearly was a dead cat bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:45:23 </td>
   <td style="text-align:left;"> $SPY go woke go broke $TWTR …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:45:20 </td>
   <td style="text-align:left;"> $SPY Can we just get to $450 so we can let @OldFngGuy out? 

He must be trolling VIX futures room today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:44:51 </td>
   <td style="text-align:left;"> $DNUT Just ate 2 dozen Krispy Kreme.

$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:44:48 </td>
   <td style="text-align:left;"> $SPY 460🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:44:35 </td>
   <td style="text-align:left;"> $SPX $ES_F $SPY     $4480.00 Wed.  🛰🧞‍♂️ 📡. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:43:29 </td>
   <td style="text-align:left;"> $SPY Next time Biden WH issues an order to block or remove someone, Elon would say.. EV summit. Free speech. Not gonna do it. 😇😇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:42:53 </td>
   <td style="text-align:left;"> $spy $TWTR  
 
Your days of anonymously posting on the internet are numbered folks! 
 
Get your last words in now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:42:00 </td>
   <td style="text-align:left;"> $SPY literally, only in Philly 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:41:30 </td>
   <td style="text-align:left;"> $SPY 437 calls and puts after amazon brings down this overpriced market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:41:17 </td>
   <td style="text-align:left;"> $SPY 

Twitter is for the same retards who weren’t accepted enough on every other lame ass social media platform. 

Who gives a fuck who owns it. 
The world has always been full of losers. 
Lmfao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:40:33 </td>
   <td style="text-align:left;"> $SPY I swear Fb gonna rip 20% after we </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:40:05 </td>
   <td style="text-align:left;"> $SPY We may have an Asian bounce and Euro bounce tonight, dollar dump and bounce to 4350+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:39:03 </td>
   <td style="text-align:left;"> $SPY man I’m feeling so bad for all the bears 😞 what the hell are they going to tell their families when spy giga ultra moons 😭 Jesus I’m feeling so sad. I can’t even imagine the look on their face as they tell their boyfriends that they can’t make rent this month (or any month for that matter) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:38:55 </td>
   <td style="text-align:left;"> $SPY of you want to know what libs will say about elon and twitter, tune into the media and find out tonight. Its like knowing the future </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:38:52 </td>
   <td style="text-align:left;"> $SPY when spy sub 419 today i almost say goodbye to the stonk market but the lord somehow hide the sell button in my robinhood account my fingers were numb and just like that i open my eyes at 3:50pm and see spy around 428 i know jesus r real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:38:01 </td>
   <td style="text-align:left;"> $SPY Good morning AMERICA 🇺🇸 🤦‍♂️ $DIS https://twitter.com/yasharcoins/status/1518684743377641473?s=21&amp;amp;t=vYz6qD98boLd5Bw8ivOv2w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:37:54 </td>
   <td style="text-align:left;"> $SPY it will take $twtr 100+ years to pay off Elon’s margin loan. Its not about money, now I get it, I was baffled for a minute there…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:37:18 </td>
   <td style="text-align:left;"> $NFLX 5x your money with my call outs 🙏😇❤️🌞👍🚀 $TSLA $SPY $NVDA $FB https://youtu.be/n7ovzGgjBus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:36:54 </td>
   <td style="text-align:left;"> $SPY we love you elon💙 # Virgil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:36:20 </td>
   <td style="text-align:left;"> $SPY I’m on the run, btch, I just took of on the cops 😂👉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:35:30 </td>
   <td style="text-align:left;"> $SPY 422-424 then back to 430.. idk maybe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:35:23 </td>
   <td style="text-align:left;"> $SPY 

If this economy depends on me to keep buying more plastic $hit from China to grow, it’s in for a rude awakening. I don’t buy anything! This is my TV, and it still works and I’m planning to keep it for another 12 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:34:41 </td>
   <td style="text-align:left;"> $SPY Remember when this traded at 479.98 on Jan 4th?.....LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:34:36 </td>
   <td style="text-align:left;"> $SPY Went short eod suckers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:33:54 </td>
   <td style="text-align:left;"> $SPY bears got fucked so hard GOD BLESS AMERICA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:33:15 </td>
   <td style="text-align:left;"> $SPY  I really can&amp;#39;t understand people who long contracts on spy If your green sell that f****** thing!!!!!!! And buy again... sheesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:33:12 </td>
   <td style="text-align:left;"> $SPY morons at Twitter lucky they got an offer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:32:59 </td>
   <td style="text-align:left;"> $TWTR $spy.   
Excited for Elon to bring sorely needed digital ID to the internet.  That&amp;#39;s what this is about.....Brilliant!!! 
 
This will be game changing!! 
 
No more broke $$ bears to clog the internet....you will all be classified as bots that will be run over by the machine. 
 
You don&amp;#39;t deserve an opinion and you won&amp;#39;t have one much longer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:32:54 </td>
   <td style="text-align:left;"> $SPY did explosions in Moldova get priced in yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:32:07 </td>
   <td style="text-align:left;"> $SPY  $UVXY $VXX  
   @KevDog1997 @@KEVDOG97   LOL ...... good luck on   &amp;quot;this will go down like 80 percent in the next 7 years&amp;quot;   learn basic math.......... history might help you too........ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:31:53 </td>
   <td style="text-align:left;"> $SPY  $UVXY $VXX  
   @KevDog1997 @@KEVDOG97   LOL ...... good luck on   &amp;quot;this will go down like 80 percent in the next 7 years&amp;quot;   learn basic math.......... history might help you too...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:31:18 </td>
   <td style="text-align:left;"> $spy If you&amp;#39;ve never seen the film Sexy Beast you should. One of my fav&amp;#39;s &amp;amp; Sir Ben Kingsley was just so great &amp;amp; crazy 
 
This scene is right after his Broker told him to Buy more $dwac after he had already added at $100 &amp;amp; then $80. 
 
https://www.youtube.com/watch?v=DDLpKrTVJKc 
 
$twtr $fb $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:31:08 </td>
   <td style="text-align:left;"> $SPY I was taught if Monday is bad bear Tuesday is suicide tbh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:30:56 </td>
   <td style="text-align:left;"> Since December heavy put interest centered around 3/18 for $QQQ. So far 3/15 has marked bottom for $NASDAQ. After Netflix, and other big tech declines put interest has soared, but my theory is smart money bet on the decline in December, bottomed March on fed rate decision and everybody else who has these doom &amp;amp; gloom scenarios are just those who came to the party late. Everything thus far backs up my thesis. 

Who is selling all these puts now, and who is buying them? Key point to reflect on is who is saying what at what time during sentiment at not seen lows since 1987. $SPY $SPXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:30:35 </td>
   <td style="text-align:left;"> $SPY why doesn’t the earnings calendar show up on my ST app anymore? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:30:25 </td>
   <td style="text-align:left;"> $SPY 485 calls going to fill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:29:43 </td>
   <td style="text-align:left;"> $QQQ the ole’ Monday bull trap $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:29:04 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:28:21 </td>
   <td style="text-align:left;"> $SPY     Low for OVN trading will be 4277 on $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:28:18 </td>
   <td style="text-align:left;"> $SPY  A good ol bear ass whooping today hee-haw ✋️🤠😎😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:27:52 </td>
   <td style="text-align:left;"> $SPY the guy could’ve dumped his money into treasuries, waited a year and probably bought Twitter for 75% off.  Instead his autistic ego has him throwing around more money than earth at trashy companies that I am 99.99999999% certain everyone in his circle told him not to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:27:38 </td>
   <td style="text-align:left;"> $SPY musk and Gates gonna help each other knock this down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:26:33 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX SUCH A WEAK FINISH!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:26:12 </td>
   <td style="text-align:left;"> $SPY futures are going to rip rip rip rippppp🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:25:57 </td>
   <td style="text-align:left;"> $SPY man did i have a great time laughing my ass off at all the bear comments at like 10pm last night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:25:55 </td>
   <td style="text-align:left;"> $SPY @PurpleReign8 nets filly mavs outright </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:25:45 </td>
   <td style="text-align:left;"> $SPY day 3 of  the $50 scrap account. Goal is 5k in 2 weeks 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:25:29 </td>
   <td style="text-align:left;"> $SPY bears be like Futes in free fall while it’s only down .06% 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:25:16 </td>
   <td style="text-align:left;"> $SPY some one post futes my spy puts goin to 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:24:56 </td>
   <td style="text-align:left;"> $SPY does anyone else has difficulty drinking wen getting older?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:24:29 </td>
   <td style="text-align:left;"> $SPY futures dripping hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:24:18 </td>
   <td style="text-align:left;"> $SPY fuck I shorted the spy today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:24:09 </td>
   <td style="text-align:left;"> $SPY who buys a social media company a couple weeks before Fed QT starts?  It really goes to show you how lucky these people are to have benefitted from Fed intervention.  How disproportional the benefits of Fed printing have been, mainly going to a select few and everyone else eating the table scraps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:23:42 </td>
   <td style="text-align:left;"> $QQQ held well since open trapping bears 🐻 for couple of hours dumping $SPY with non-tech selling, PCR ratio of 1 means most likely puts will go worthless . Check huge puts volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:23:34 </td>
   <td style="text-align:left;"> $SPY gap up 433 or 435+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:23:24 </td>
   <td style="text-align:left;"> $SPY democrats getting their ass beat  in November so that’s pretty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:22:47 </td>
   <td style="text-align:left;"> $SPY Bears dinner tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:22:27 </td>
   <td style="text-align:left;"> $SPY bear always asks if I get paid to &amp;quot;pump&amp;quot;

LOL

If you know anyone who will pay me for posting COMMON SENSE that the market goes UP, please let me know !!!

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:22:11 </td>
   <td style="text-align:left;"> $SPY sorry to rain on the parade. But, Europe is cancelling oil this  week or so. Earnings aren’t gonna be positive for Facebook or Amazon. And we are in a bubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:21:56 </td>
   <td style="text-align:left;"> $SPY similar to Jan 24th but with relatively less volume. Expecting a flat couple of days with high of 435 and low of 424. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:21:05 </td>
   <td style="text-align:left;"> $SPY could see a limit up tomorrow TBH....

Literally ZERO REASONS to see red

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:20:23 </td>
   <td style="text-align:left;"> $SPY I promise msg vol will be down tomorrow bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:20:08 </td>
   <td style="text-align:left;"> $TWTR $SPY $FB $TSLA $SNAP 
Most Famous Dona tweet 2.0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:20:07 </td>
   <td style="text-align:left;"> $IRNT this stock will make you rich. Buy and HODL $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:20:04 </td>
   <td style="text-align:left;"> $SPY bears tell their loved ones they invest 

Let me just put these kids in their place

Bulls invest and trade only to buy the dip, hedging perfect sceneries 

Whereas bears try and time my market. Lmao. This shit never gets old. I don’t think they’ll ever be able to figure this out as few can understand this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:19:27 </td>
   <td style="text-align:left;"> $SPY https://www.investopedia.com/terms/i/inverseheadandshoulders.asp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:19:27 </td>
   <td style="text-align:left;"> $SPY Market makers trapped bears 🐻 for first four hours and squeezed them out VIX 31+ was not sustainable 🤪 looks the volume of puts that closed worthless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:19:10 </td>
   <td style="text-align:left;"> $SPY 430 436 tomorrow with hammer candle today… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:19:08 </td>
   <td style="text-align:left;"> $SPY 

🧐😳

&amp;quot;WaPo, NY Times report Democrats forecast &amp;#39;increasingly dire&amp;#39; November elections: &amp;#39;Fatalism is settling in&amp;#39;
&amp;#39;There is as much a plan to win the midterms as there was to airlift Afghans out of Kabul,&amp;#39; one Democratic political adviser told WaPo&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:18:19 </td>
   <td style="text-align:left;"> $SPY Bags to Riches Ep 11 / AMC Squeeze AAPL Rip MULN FREQ ATER RBLX #SPY Rip METX / Stock Market Analysis 
 
https://youtu.be/UXfhFMg2m44 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:18:14 </td>
   <td style="text-align:left;"> $SPY Elon will get margin call soon, as he will join the club of $spy bull babies. Instead of selling stock at 200PE he borrows against it at the top of the biggest bubble ever known to man kind. Ah….no words </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:18:08 </td>
   <td style="text-align:left;"> $SPY $TOL $PHM

Inventory of homes for sale is about 9% less than this time last year.   The shortage of supply has grown to about Five Million units and will probably hit Six Million by 2024.  

If you look at new home construction rates it&amp;#39;s not even close to keeping up with population growth.  Prices and profits will go higher! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:18:06 </td>
   <td style="text-align:left;"> $SPY reloading calls tomorrow at 424 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:17:46 </td>
   <td style="text-align:left;"> $SPY poor bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:17:39 </td>
   <td style="text-align:left;"> $SPY what a day! What a swing!🔥👍👍👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:17:24 </td>
   <td style="text-align:left;"> $SPY Where did bears go lmao 

Tomorrow could be another fatty rally 

And Wednesday 
Shit maybe Thursday as well 
Fuck it Friday we POP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:17:20 </td>
   <td style="text-align:left;"> $DJIA $SPY $SPX  
MARKET SHOULD CLOSE HIGHER TOMORROW. 
RECOMMEND BUYING THE NADEX US 500(JUN) 4294.0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:17:04 </td>
   <td style="text-align:left;"> $SPY bloooood bath tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:16:03 </td>
   <td style="text-align:left;"> $SPY So what happens to investors shares if Elon goes private with Twitter? I thought once it was public it had to stay public legally because of shareholders? What am I missing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:15:46 </td>
   <td style="text-align:left;"> $SPY 

Still waiting to find my soulmate on StockTwinder...

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:15:36 </td>
   <td style="text-align:left;"> $SPY he’s gonna lose 90% of his money once Twitter stock price drops into an abyss.  Well this has happened to almost everyone at the top of these bubbles.  Insanely rich ppl who don’t have a clue what to do with their money and are terrible investors lose almost all of it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:15:09 </td>
   <td style="text-align:left;"> $SPY is moving very slowly into a bear market and then a recession a bit later but do NOT fret.  It will be ugly and then more ugly in time.  
 
So important for $$$ mgrs to get ready for the carnage before the next brutal news bite hits our screens.  Exit at best prices. 
 
We know all too well how markets can reverse in &amp;#39;news&amp;#39; that we all knew.  50 points and 75 points per month but who&amp;#39;s counting???  LOL 
 
We don&amp;#39;t want to bleed  but that is out life into 2023&amp;#39;+ 
 
 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:14:57 </td>
   <td style="text-align:left;"> $SPY had a feeling . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:14:50 </td>
   <td style="text-align:left;"> $SPY more calls tomorrow.  Eyeing dips to load 430/438 calls around 424 if I’m lucky and 426 if bulls control the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:14:15 </td>
   <td style="text-align:left;"> $SPY bills gate have only 1 prob job tmr afterhour better not let me down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:13:19 </td>
   <td style="text-align:left;"> $SPY fuck what a day to miss everything that happened. Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:13:10 </td>
   <td style="text-align:left;"> $SPY after all that chop today and the crazy 1$ moves up and down in 3 seconds all day makes me feel like they pumped it at the end and they gonna dump it tmrw cuz they are faqheads and don’t want anyone to know which direction it’s going to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:13:06 </td>
   <td style="text-align:left;"> $TWTR $SPY Talk about a golden parachute you run a company into the ground and get paid fuck you money if you get fired. https://www.reuters.com/technology/twitter-ceo-set-receive-42-million-if-terminated-after-musk-deal-2022-04-25/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:12:45 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ve seen this in movies and oscar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:12:18 </td>
   <td style="text-align:left;"> $TWTR $SPY $FB $SNAP $TSLA 
Most Famous tweets by Dona </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:12:10 </td>
   <td style="text-align:left;"> $SPY ez baby , bouncy bouncy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:11:54 </td>
   <td style="text-align:left;"> $SPY $QQQ we live to trade another day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:11:49 </td>
   <td style="text-align:left;"> $SPY btfd this is unprecedented </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:11:48 </td>
   <td style="text-align:left;"> $SPY 500 eom and I&amp;#39;ll love you forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:11:48 </td>
   <td style="text-align:left;"> My thoughts on the $NFLX earnings and how they may affect $FB or $MSFT. also an intraday discussion of the action in $ROKU $SPY (thank you @Tradytics  roku data helped me find the setup) https://youtu.be/zC8LhG3pCyg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:11:39 </td>
   <td style="text-align:left;"> $SPY 44 billion dollars vs world hunger? 
Nope. 
44 billion dollars for Twitter?  
Yes sir! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:11:28 </td>
   <td style="text-align:left;"> $SPY man, she pivoted at 11:45 and didn&amp;#39;t look back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:11:21 </td>
   <td style="text-align:left;"> $SPY 

The cost to buy one of the largest social media companies: $44B

Liberal tears: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:11:05 </td>
   <td style="text-align:left;"> $SPY Elon musk is richest man holding two massive bubbles . We know hot that ends ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:10:58 </td>
   <td style="text-align:left;"> $SPY $QQQ Per Charlie McElligott, extreme negative delta and negative gamma ... aka &amp;quot;kindling&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:10:51 </td>
   <td style="text-align:left;"> $SPY man I am praying to god they don’t make tmrw a red day 🤦🏻‍♂️ just feels too good to be true that we are going to go up tmrw. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:10:39 </td>
   <td style="text-align:left;"> $SPY All of the indexes hit their 200 EMA on the weekly. Headed back down soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:10:30 </td>
   <td style="text-align:left;"> $SPY BREAKING: Trump-Appointed Federal Judge Issues Temporary Restraining Order Barring Joe Biden From Lifting Title 42 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:10:14 </td>
   <td style="text-align:left;"> $SPY $QQQ Everyone should give this list a really hard look to understand what &amp;quot;big&amp;quot; days for the markets actually look like....  

https://en.wikipedia.org/wiki/List_of_largest_daily_changes_in_the_S%26P_500_Index

For example we&amp;#39;ve had 10 HUGE $10-$20+ single day gains on SPY since COVID.  Something to keep in the back of your mind after last week and todays rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:10:09 </td>
   <td style="text-align:left;"> $SPY NOT BAD GUISE🤠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:10:04 </td>
   <td style="text-align:left;"> $SPY Alright who else did some hypothetical math after the bell after they sold calls early today, just me? 😄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:09:58 </td>
   <td style="text-align:left;"> $SPY futes already looking EXTREMELY bullish !!!

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:09:47 </td>
   <td style="text-align:left;"> Our piggy had a great day. She got drowned @ $420 and revived to $428.  Is it manip?  Most likely to some degree. 
 
Think for a moment about what recent catalysts allowed the markets to fall rather quickly from the sweet $450 to $425 in a flash. Do not forget that the blood out there has yet to dry. 
 
When the $SPY trades normally in the $405 to $415 area in the near future, there may be some buy opps in some areas, in others not. The roller coaster rides will eventually force investors to lose millions in 22&amp;#39; and that reality is hard to accept. 
 
Will Retail realize the need to protect equity assets soon or will most just keep reaching for the Kool Aid?  I think we are getting more savvy about how to proceed. 
 
$SPY  $QQQ    We must avoid swallowing the poison pills. 
 
$420- 
 
$VXX on radar... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:09:26 </td>
   <td style="text-align:left;"> $SPY actually think it&amp;#39;ll be red tmr morning pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:09:25 </td>
   <td style="text-align:left;"> $SPY $QQQ Rally time, aka reversion to the mean. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:09:16 </td>
   <td style="text-align:left;"> $TWTR $SPY GOD BLESS ELON MUSK. THE DEMOCRATS AND THE “WOKE” WILL NEVER GET TO STEAL ANOTHER ELECTION AGAIN! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:09:15 </td>
   <td style="text-align:left;"> $SPY huge reversal!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:09:08 </td>
   <td style="text-align:left;"> $SPY SPY 2022-04-25 Daily Forecast Video: 
https://www.youtube.com/watch?v=dWrcFMlOcB4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:08:59 </td>
   <td style="text-align:left;"> $SPY whats you taught bout tomorrow &amp;amp; Rest of the week ? With @ Monday like this ? 🤯🤷🏾‍♂️😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:08:42 </td>
   <td style="text-align:left;"> $SPY futes trippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:08:36 </td>
   <td style="text-align:left;"> $SPY  follow thru tomorrow 🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:08:11 </td>
   <td style="text-align:left;"> $SPY 

Like I said, there’s one more relief rally left in this market before they close the door and turn off the lights. If your plan is to stay “invested” in this economy, please do so. We need hero’s like you! ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:07:45 </td>
   <td style="text-align:left;"> $SPY I couldn&amp;#39;t be a politician solely based off my stocktwit posts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:07:21 </td>
   <td style="text-align:left;"> $SPY elon should run for prez… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:07:15 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:07:08 </td>
   <td style="text-align:left;"> $SPY just LOVING all the bull posts !!!

GREAT WORK, bulls !

🙂👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:07:00 </td>
   <td style="text-align:left;"> $SPY has an average volume of 103630000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:06:59 </td>
   <td style="text-align:left;"> $SPY Elon buying Nasdaq &amp;amp; NYSE. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:06:44 </td>
   <td style="text-align:left;"> $SPY I hate bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:06:31 </td>
   <td style="text-align:left;"> $SPY oh my God LMAO PUTS GOT DESTROYED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:06:13 </td>
   <td style="text-align:left;"> $SPY 

Bear goes BROKE tonight !!!!

Selloff OVER !

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:05:22 </td>
   <td style="text-align:left;"> $SPY $DJIA YOU FIGURE OUT ISRAEL 🇮🇱 WOULD LOVE NOTHING MORE THAN TO SEE EU WITHOUT GAS / oil ! Who’s plan so you think this is anyway ? 🇮🇱😂😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:05:20 </td>
   <td style="text-align:left;"> $SPY HAPPY TRADING DUE TO THE WIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:05:03 </td>
   <td style="text-align:left;"> $NFLX $SPY $QQQ All bulls double up your Netflix position tomorrow and let’s short squeeze this beotch back above $300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:04:57 </td>
   <td style="text-align:left;"> $SPY UP Or Down Tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:04:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $GOOGL $NVDA 
Yellen says U.S. economy being &amp;#39;resilient&amp;#39;, no recession in sight

&amp;quot;I don&amp;#39;t expect a recession,&amp;quot; Yellen told CNBC.

https://www.reuters.com/business/finance/yellen-says-us-economy-being-resilient-no-recession-sight-2022-04-22/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:04:57 </td>
   <td style="text-align:left;"> $SPY will rip this week 435 before reversal.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:04:33 </td>
   <td style="text-align:left;"> $SPY tank it, again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:04:28 </td>
   <td style="text-align:left;"> $SPY 🌈🐻 desperate af right now.  We all know what that means </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:04:20 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:02:52 </td>
   <td style="text-align:left;"> $SPY did musk single-handedly lifted the msrket? Lol kudos if true </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:02:39 </td>
   <td style="text-align:left;"> $SPY YES, DOWN MORE BEFORE THE END OF THE DAY!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:02:22 </td>
   <td style="text-align:left;"> $SPY There is over 1 billion in puts for May! It has nothing to do with QT QE or whatever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:02:19 </td>
   <td style="text-align:left;"> $SPY Only thing to concern me about this week being green is Europe banning goddamn Russian oil… But maybe Germany will delay this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:02:12 </td>
   <td style="text-align:left;"> $SPY Cramer  also said Twitter would block Elon’s bid…

…there’s always a bull market somewhere, and he promises to help you find it 😵‍💫

 $TWTR $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:01:42 </td>
   <td style="text-align:left;"> $SPY hell to $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:01:26 </td>
   <td style="text-align:left;"> $QQQ $SPY seems like pump today could’ve been fake out ..what you guys think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:01:13 </td>
   <td style="text-align:left;"> $SPY 🤣😂🤣🙌🙌🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:00:59 </td>
   <td style="text-align:left;"> $SPY 434 then maybe shorting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 06:00:37 </td>
   <td style="text-align:left;"> $SPY NOW WS JEWS WILL CRASH THE MARKETS ! They’re pissed 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:59:15 </td>
   <td style="text-align:left;"> $NFLX $AAPL $QQQ $SPY  Aapl should buy NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:59:12 </td>
   <td style="text-align:left;"> US equity funds have seen outflows of $30 billion over the past two weeks. 
 
h/t @SoberLook  
 
$SPY $QQQ $DIA etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:59:00 </td>
   <td style="text-align:left;"> $QQQ $SPY  so tell me…who bought puts at 418🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:58:37 </td>
   <td style="text-align:left;"> $SPY worry about your paperwork </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:58:23 </td>
   <td style="text-align:left;"> $SPY Yahoo flashed -1.28% on this a few minutes ago, I had a small panic attack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:57:36 </td>
   <td style="text-align:left;"> $SPY Bears didn&amp;#39;t cover this LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:57:33 </td>
   <td style="text-align:left;"> $SPY did the bears get rekt today or what? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:57:21 </td>
   <td style="text-align:left;"> $SPY 

Sonic lost 250 million in paper puts today 

Yay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:57:15 </td>
   <td style="text-align:left;"> $SPY been on point lately. Called $450 top Thursday, $427 Friday, and $418 bottom today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:57:03 </td>
   <td style="text-align:left;"> $SPY futes drippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:57:00 </td>
   <td style="text-align:left;"> $SPY 4 hour time frame closed just under its 9 ema. This pop seems to be a retracement from overnight sell off. Something to take note of </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:56:45 </td>
   <td style="text-align:left;"> $DOGZ stock closed $ 4+   We loaded$  2.60 Nobody noticed but we killed this trade. These contracts almost doubled %%+ since Friday and the shares are green. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:56:43 </td>
   <td style="text-align:left;"> $SPY  
 
Has anyone ever bought/sold an option while riding a unicycle? 
 
I want to say no, but the world is filled with all types. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:56:32 </td>
   <td style="text-align:left;"> $SPY NVIDIA down 33.93% for the year yet SPY only down 10%! How!!!!!!!? This is so heavily manipulated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:56:11 </td>
   <td style="text-align:left;"> $SPY so is this the reversal? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:56:06 </td>
   <td style="text-align:left;"> $SPY FuTuReS aRe CrAsHiNg 
 
Where? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:55:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $TWTR https://www.instagram.com/tv/CcyVP9bDzJe/?igshid=MDJmNzVkMjY=

😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:55:54 </td>
   <td style="text-align:left;"> $SPY wheres OFG??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:55:52 </td>
   <td style="text-align:left;"> $SPY Liberals are mad today with selling of Twitter, good to see them suffer a little bit, they deserve it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:55:15 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX FUTURES ALREADY CRASHING!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:55:09 </td>
   <td style="text-align:left;"> $SPY $DJIA $TWTR check this out ! They’ve been using social media to fool and control us for too long ! https://twitter.com/deus_volk/status/1518688157839024130?s=21&amp;amp;t=vYz6qD98boLd5Bw8ivOv2w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:54:21 </td>
   <td style="text-align:left;"> $SPY  This place smells like bull shit...straight to unicorns.  Not happening without the QE folks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:54:16 </td>
   <td style="text-align:left;"> $SPY 30 second ads on netflix will cost 175k $NFLX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:54:07 </td>
   <td style="text-align:left;"> $SPY I told you you will never see 410 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:59 </td>
   <td style="text-align:left;"> $SPY Sounds like the general consensus is that the market hasn’t flushed down enough! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:52 </td>
   <td style="text-align:left;"> $SPY 🇺🇸 🇺🇸 🇺🇸 🚀  Calls Only Bears Are Done!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:50 </td>
   <td style="text-align:left;"> Today was just an oversold Bounce IMO. Those RSIs were cooked man. Then you had some FOMO buying into close. If ERs are trash this is going sub 400 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:46 </td>
   <td style="text-align:left;"> $spy $twtr $tsla 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:32 </td>
   <td style="text-align:left;"> $TWTR $TSLA $SPY $AAPL 
Literally 99% of the people on here. Broke worshiper lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:19 </td>
   <td style="text-align:left;"> $SPY Just eat ze bugs.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY How can Joe Biden and the Dems control inflation? It&amp;#39;s very simple; run a smaller, more efficient government and pay down the national debt🗽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:06 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:02 </td>
   <td style="text-align:left;"> $SPY gap up tomorrow and Erin for the rest of the week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:53:01 </td>
   <td style="text-align:left;"> $TWTR &amp;quot;Upon completion of the transaction, Twitter will become a privately held company. Under the terms of the agreement, Twitter stockholders will receive $54.20 in cash for each share of Twitter common stock that they own upon closing of the proposed transaction&amp;quot;. $SPY $TSLA $AAPL $FB https://www.sec.gov/Archives/edgar/data/1418091/000119312522117743/d319190ddefa14a.htm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:52:33 </td>
   <td style="text-align:left;"> $SPY I have a custom back tested algo that just triggered my RARE &amp;amp; BEST indicator, right now, after hours. It says we are going to see $422.08 tomorrow. Not scaring you. It’s no indication for the remainder of the week, only tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:52:22 </td>
   <td style="text-align:left;"> $SPY i’m eating a chocolate easter bunny right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:50:43 </td>
   <td style="text-align:left;"> $SPY if the snowflakes abandon Twitter, it will die. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:50:03 </td>
   <td style="text-align:left;"> $SPY y’all should short AMC https://nypost.com/2022/04/24/melvin-capitals-gabe-plotkin-apologizes-for-losses-to-investors-who-want-their-money-back/ 😢😢😢 your never getting your money back if you invest with hedge funds. Remember me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:49:23 </td>
   <td style="text-align:left;"> THE OSCILLATOR SETUP? 
 
S&amp;amp;P 500 $SPY Analysis 👉 https://www.youtube.com/watch?v=2CSckVl267k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:48:58 </td>
   <td style="text-align:left;"> $SPY VIX looking unhealthy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:48:29 </td>
   <td style="text-align:left;"> $SPY shitty economy huh and guy spends 50 billion musks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:48:19 </td>
   <td style="text-align:left;"> $SPY holy shit Elon just bid to buy my stocktwits account $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:48:03 </td>
   <td style="text-align:left;"> $SPY Easy mode. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:47:54 </td>
   <td style="text-align:left;"> $SPY  🧸👋🏼🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:47:45 </td>
   <td style="text-align:left;"> S&amp;amp;P 500 $SPY Top Gainers during today  $MRNA $MTCH $FTNT $TWTR 
    
Learn more: https://www.finscreener.org/screener/top-gainers/stocks/sp500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:47:39 </td>
   <td style="text-align:left;"> $SPY who held their puts after dancing on 420 all morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:47:34 </td>
   <td style="text-align:left;"> $SPY home prices should see a decline and CCI should beat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:46:55 </td>
   <td style="text-align:left;"> $SPY Nice! Coming back! Bought a shit ton on that dip and will on the others </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:46:53 </td>
   <td style="text-align:left;"> $SPY Elon Musk is buying Twitter.

CNN+ is shutting down.

Disney is being reined in. 

It&amp;#39;s a bad time to be woke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:46:13 </td>
   <td style="text-align:left;"> $SPY my mini golf course is coming to fruition, getting quoted for materials </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:46:06 </td>
   <td style="text-align:left;"> $SPY 500 June </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:45:57 </td>
   <td style="text-align:left;"> $SPY bears got slapped today 🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:45:52 </td>
   <td style="text-align:left;"> $SPY Just heard Elon is buying SPY out at $500 a share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:45:43 </td>
   <td style="text-align:left;"> $SPY will be happy to see spy at 435-438 tomorrow. Can’t wait </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:45:37 </td>
   <td style="text-align:left;"> $SPY terrorist bears betting against 🇺🇸 will burn in theta fire tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:45:35 </td>
   <td style="text-align:left;"> $SPY hey Elon… how about stocktwits? Tired of opening up all these accounts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:44:45 </td>
   <td style="text-align:left;"> $SPY 

love bruh 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:44:42 </td>
   <td style="text-align:left;"> $SPY CCI at 10 am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:43:19 </td>
   <td style="text-align:left;"> $SPY $SOXL $USD $CDNS $SNPS  
 
Cadence Design Systems: Q1 Non-GAAP EPS of $1.17. 
Revenue of $902M (+22.6% Y/Y). 
 
Sees FY22 EPS $3.89-$3.97 Vs. $3.80 Est., Sales $3.395B-$3.435B Vs. $3.36B Est. 
 
For the second quarter of 2022, the company expects total revenue in the range of $825 million to $845 million. Second quarter GAAP operating margin is expected to be in the range of 29 percent to 30 percent and GAAP net income per diluted share is expected to be in the range of $0.59 to $0.63. Using the non-GAAP measures defined below, operating margin is expected to be in the range of 39 percent to 40 percent and net income per diluted share is expected to be in the range of $0.95 to $0.99. 
 
For fiscal year 2022, the company expects total revenue in the range of $3.395 billion to $3.435 billion.  
 
https://seekingalpha.com/news/3826393-cadence-design-systems-non-gaap-eps-of-1_17-revenue-of-902m </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:43:16 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
so far so good 
 
psychology creates the shape, not the reverse 
 
no crash  
 
almost confirmed 🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:42:47 </td>
   <td style="text-align:left;"> $SPY no mercy tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:42:32 </td>
   <td style="text-align:left;"> $SPY The Ukraine/Russia WAR is some crazy delusional Mickey Mouse fantasy on Twitter - On Telegram, it&amp;#39;ll turn you into a pacifist pretty f&amp;#39;ing fast! 
 
Blinken &amp;amp; Austin &amp;amp; Biden &amp;amp; Congress &amp;amp; the Pentagon fighting Russia  to the last Ukrainian is insulting. A crazy evil that can&amp;#39;t even be quantified. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:42:01 </td>
   <td style="text-align:left;"> $SPY please be $440 by open. It’s hard out here man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:41:51 </td>
   <td style="text-align:left;"> $SPY so I made bears massive loss today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:39:43 </td>
   <td style="text-align:left;"> $TSLA  $TWTR  $DOGE.X  ====&amp;gt;  these FUCKERS ABOUT TO EXPLODE !!!! 👀🔥🔥🚀🚀🚀 
. 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:39:31 </td>
   <td style="text-align:left;"> $SPY so what has to happen for me to make profit 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:39:24 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC $FB $SNAP 
Hes back????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:39:20 </td>
   <td style="text-align:left;"> Market Summary Update: We got a short term oversold signal today intraday. Good bounce since then. $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:39:06 </td>
   <td style="text-align:left;"> $SPY fire up your sazeracs! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:38:45 </td>
   <td style="text-align:left;"> $SPY Look, failure is not an option, I gotta be at the top
Like I&amp;#39;m sorry, but I don&amp;#39;t really feel sorry for y&amp;#39;all
I&amp;#39;m sorry I got a new number that you can&amp;#39;t call
I&amp;#39;m sorry to everyone who still wants me to fall
Hold up, you know what, I ain&amp;#39;t sorry at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:38:43 </td>
   <td style="text-align:left;"> $SPY  
 
How do we think @FlappJacks did at the charity golf outing today?  I feel like he is a closest to the pin guy vs long drive guy... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:38:35 </td>
   <td style="text-align:left;"> $SPY Poor bears man. They took a V to the face today. Am not surprised 

When I say btd you BTMFD 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:38:27 </td>
   <td style="text-align:left;"> $SPY rookie mistake. Long and short Iron condors or any other 4 leg strategy with high extrinsic value must be avoided especially when IV is high. You won’t be able to get out trade early without realizing loss even if the price action is in your favor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:37:49 </td>
   <td style="text-align:left;"> $SPY shhhh dont tell the bears we gonna have a lil rally .. We need them to keep buying puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:37:35 </td>
   <td style="text-align:left;"> Market Recap: Monday - April 25, 2022 
 
If you like this newsletter, feel free to subscribe. It&amp;#39;s FREE, No Ads and you will only get one email per day after the market closes to make sense of what&amp;#39;s happening in markets 🙏 
 
$TWTR $SPY $DOGE.X  
https://marketcrier.com/markets/blog/market-digest/44744d8e-798b-4f97-a252-299a589959ce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:37:08 </td>
   <td style="text-align:left;"> $SPY NEW ARTICLE : The Markets Strike Back (At Least For Now) (Technically Speaking For 4/25) https://www.stck.pro/news/SPY/26753003 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:36:51 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:36:45 </td>
   <td style="text-align:left;"> $SPY Del Taco kids calling for 5750 eoy.....LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:36:42 </td>
   <td style="text-align:left;"> $SPY 445 tomorrow $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:36:41 </td>
   <td style="text-align:left;"> $SPY I see a big green dildo biting at least $432 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:35:28 </td>
   <td style="text-align:left;"> $SPY CNBC fast money always says we need another 10% drop 

Literally everyday for last 5 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:35:06 </td>
   <td style="text-align:left;"> $NFLX $SPY $TSLA BOUGHT PUTS, AND NO DOUBT WILL MAKE MILLIONS THIS WEEK!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:35:01 </td>
   <td style="text-align:left;"> $SPY We are at 668 members the sooner we get to 1000 the sooner I will start posting on https://stocktwits.com/r/ZcashIsKing/ make happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:34:59 </td>
   <td style="text-align:left;"> $SPY they been trying to stop the wave but the wave don’t stop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:34:56 </td>
   <td style="text-align:left;"> $SPY go Elon!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:34:14 </td>
   <td style="text-align:left;"> $SPY this guy on CNBC looks like he’s reporting the weather </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:33:55 </td>
   <td style="text-align:left;"> $SPY let me get $441 tomorrow?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:33:43 </td>
   <td style="text-align:left;"> $SPY Honestly I think the FED wants the market lower than this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:33:15 </td>
   <td style="text-align:left;"> $SPY This pump today was 100% technically driven, and we called it to the penny today. We sold our puts at exactly $4002 on $SPX. Knowing a temp pump might be among us. This pump will vanish faster than your stinkiest fart into thin air if big tech misses earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:33:04 </td>
   <td style="text-align:left;"> $SPY the cows 🐮 udders were squeezed today!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:32:06 </td>
   <td style="text-align:left;"> $SPY Nazis in this country will try to make every dumb thing that happens into a &amp;#39;libsgutowned&amp;#39; party. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:31:34 </td>
   <td style="text-align:left;"> $TWTR $SPY latex3645bd7aac87569cb581d4f4d23e3592 eventually. 0 doubt. Don’t forget the Tesla doubters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:31:22 </td>
   <td style="text-align:left;"> Today&amp;#39;s action made us feel like the Abyss is far away but oddly enough it&amp;#39;s right behind us covered with beautiful leaves.  The action is so deceiving but lucrative also for just a period of time which is getting shorter by the day. 
 
Amazing power on the call payouts as well as puts!  Thank you 
 
$SPY    $QQQ 
 
Now that the popper is over, how long before the Boyz figure out the timing for the next drop to the $420 area??? 
 
Tic tic tic.....   nasty moves for all kinds of catalysts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:31:17 </td>
   <td style="text-align:left;"> $SPY she fck with small town dudes
I got bigger dreams </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:31:08 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 4/25/2022 $SPY $TWTR $TSLA $QQQ $XBI https://www.chartguys.com/daily-market-videos/4219/bulls-stop-the-bleeding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:30:57 </td>
   <td style="text-align:left;"> $SPY If you think the war has helped $appl sell more services and iPhones and macs, then go all in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:30:43 </td>
   <td style="text-align:left;"> $SPY almost every single down move gets a bunch of stupid buyers I wonder how much money they have left without the Fed doing QE every day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:29:50 </td>
   <td style="text-align:left;"> $TWTR $SPY 
Twitter even filing with SEC the tweets they tweeted lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:29:10 </td>
   <td style="text-align:left;"> $SPY  never quitting Options. Ever! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:29:02 </td>
   <td style="text-align:left;"> $SPY definitely an exciting week setting up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:28:55 </td>
   <td style="text-align:left;"> $SPY Black Swans or temporary SPY pumpers. That is what $appl, $msft, $goog and $fb are currently. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:28:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $TWTR $DWAC so all cockroaches leaving twitter? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:28:53 </td>
   <td style="text-align:left;"> $SPY volume price analysis into intraday showed a bullish sentiment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:28:41 </td>
   <td style="text-align:left;"> $SPY Bags to Riches Ep 11 / AMC Squeeze BB AAPL Rip MULN FREQ ATER RBLX #SPY METX / Stock Market Analysis 
 
Lets go big wins 
https://youtu.be/UXfhFMg2m44 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:28:28 </td>
   <td style="text-align:left;"> $SPY need this at 435 tmr will it happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:28:17 </td>
   <td style="text-align:left;"> $SPY  
 
2 thick 
2 skinny 
 
Fight me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:28:11 </td>
   <td style="text-align:left;"> $SPY over $452 by Wednesday EOD. Take notes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:27:57 </td>
   <td style="text-align:left;"> $SPY 🔨 CANDLE 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:27:50 </td>
   <td style="text-align:left;"> $SPY looking for a 1.5% gain tomorrow, ok $QQQ looking for a 2% gain and then Wed at open expecting both to push to close to 3% at least by 10am reaching high of week and then collapsing for next leg down to end week much lower than open. I’m thinking peak will be near $450 for a triple top on the SPY and near $345-$348 for the Q’s for a triple top there as well. This hinges on $MSFT and $GOOG ER beat and forward guidance beat. I’m expecting Azure to beat growth estimates leading growth on both top and bottom lines as well as Google Cloud for $GOOG offsetting loss on search ad revenue due to Apple privacy and reduced ad spend headwinds. If tomorrow indeed does pump, will probably go into Wed just to be flat ready to get puts on everything after morning bell push. If and when spy passes $448 and the Q’s pass $343, will start scaling in puts for Friday. I cannot wait for Amazon to drop 20%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:27:35 </td>
   <td style="text-align:left;"> $VLO  one of my fav plays from today these contracts closed green 30%+ from shared entry $SPY $CVX  chats💬🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:27:26 </td>
   <td style="text-align:left;"> latex00e4f2c1aab0d9f335a6c098086cda4bFB 
 loses more users the crash will continue the following day. If  
$Aapl misses earnings, a market crash to $400 SPY will happen immediately and a correction to $340 will be the end result before we find out where we are going after that. I know it&amp;#39;s a tall order but just in case it happens that&amp;#39;s what will happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:26:31 </td>
   <td style="text-align:left;"> $QQQ $SPY More downside is expected. https://www.youtube.com/watch?v=7PO_uFxtU2U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:26:00 </td>
   <td style="text-align:left;"> $SPY the end of the day rally was unexpected. hopefully it&amp;#39;s good sign for the rest of the week. if the CPI is April less tham March, it will fly. Bullish as ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:25:35 </td>
   <td style="text-align:left;"> $SPY 

Remember! You don’t need me if your strategy is working for you &amp;amp; is consistently profitable in stock market! But if its not, you better believe it!🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:25:34 </td>
   <td style="text-align:left;"> $SPY my oat milk indicator says we’re going to get a dip tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:25:34 </td>
   <td style="text-align:left;"> $TWTR $SPY Once Elon gets those brain chips poppin off people gonna be tweeting their thoughts and looking at twitter through their own eyes with no phone/computer like this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:25:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA The market&amp;#39;s getting ready to torch the puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:24:23 </td>
   <td style="text-align:left;"> $SPY missed the most of this move down but nailed the bottom today. Tomorrow is another day only holding $BABA and $NVdA calls overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:24:20 </td>
   <td style="text-align:left;"> $SPY honestly I feel like we rally 2 days (up then flat) for earnings and retest lows after </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:24:09 </td>
   <td style="text-align:left;"> $SPY If $MSFT and $GOOG misses earnings tomorrow the market crash should start somewhat, If $FB loses more users the crash will continue the following day. If $appl misses earnings, a market crash to $400 SPY will happen immediately and a correction to $340 will be the end result before we find out where we are going after that. I know it&amp;#39;s a tall order but just in case it happens that&amp;#39;s what will happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:24:08 </td>
   <td style="text-align:left;"> $SPY 436 this week, then retest of 428-430 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:24:00 </td>
   <td style="text-align:left;"> $TWTR Hes coming to TWTR . $SPY $DWAC $SNAP $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:23:29 </td>
   <td style="text-align:left;"> $SPY bulls feel like winners 🏆  lol 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:23:09 </td>
   <td style="text-align:left;"> #DAYTRADING $SPY #OPTIONS 
Today&amp;#39;s ITM 422CALL/425PUT, despite four stop-losses each to start the day on each side of the SPY open, rack up a fourth plus 300% #daytrading gain. 
https://thegodoftrading.medium.com/daytrading-spy-options-april-2022-3c582d849ca8 
#1KdayTrade 
https://thegodoftrading.medium.com/membership 
https://thegodoftrading.medium.com/subscribe 
https://ko-fi.com/michaelpetryni </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:23:05 </td>
   <td style="text-align:left;"> $SPY For all the friends. Very nice bowl into cup / nas 100. But hey im hedged so it doesnt matter but I think we will kill some bottom shorters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:22:07 </td>
   <td style="text-align:left;"> $SPY like if you survived the “market crash” 🚀🚀🚀😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:21:51 </td>
   <td style="text-align:left;"> $SPY above 430 open tmr i should recover all my last week loss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:21:39 </td>
   <td style="text-align:left;"> $SPY The idiots in DC need to sit down &amp;amp; negotiate with Putin. The walls of corpses the Russians are lining up daily on Telegram is beyond comprehension. The AFU is losing nearly 1k bodies a day.  
 
Complete f&amp;#39;n insanity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:21:23 </td>
   <td style="text-align:left;"> $SPY Ramp and camp champion! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:21:11 </td>
   <td style="text-align:left;"> $SPY You welcome. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:20:48 </td>
   <td style="text-align:left;"> $SPY boo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:20:30 </td>
   <td style="text-align:left;"> $SPY twitter currently... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:20:18 </td>
   <td style="text-align:left;"> $SPY cute. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:20:09 </td>
   <td style="text-align:left;"> $SPY Anyone that listens to CNBC for stock news is greener than any green rookie. I mean this. I&amp;#39;m not joking. If you listen to CNBC for stock tips, you&amp;#39;re a lost cause and should not trade options or stocks. Just contribute to a 401k and never look at the market again till it&amp;#39;s time to retire. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:19:57 </td>
   <td style="text-align:left;"> $SPY It&amp;#39;s coming $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:19:57 </td>
   <td style="text-align:left;"> $SPY my dead body is healed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:19:05 </td>
   <td style="text-align:left;"> $IRNT 10s of millions of $$$ coming in soon. They have just been waiting for government funding which a bill was passed in mid March by government that’ll likely fund some of these projects. Also biden has mentioned an increase in cybersecurity spending for FY23. You can see in the December call the general mention the amount of money two of these deals will bring in for them https://seekingalpha.com/article/4475481-ironnet-inc-irnt-ceo-keith-alexander-on-q3-2021-results-earnings-call-transcript
 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:17:19 </td>
   <td style="text-align:left;"> $SPY Get ready for an action packed week starting Tuesday after hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:17:18 </td>
   <td style="text-align:left;"> $SPY $434 open 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:17:17 </td>
   <td style="text-align:left;"> $SPY every time I log in here I regret it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:17:09 </td>
   <td style="text-align:left;"> $AAPL $MSFT $SPY $QQQ I’ll leave you with this. So many have grown bearish which translates to we will see a pump. It’s seems as if no one learns their lesson. Rather than profit,  they simply want to be right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:17:02 </td>
   <td style="text-align:left;"> $SPY MASSIVE earnings coming which will set the course for the market the next few weeks or months.
 
If $MSFT  $GOOGL  can set the tone Tuesday with good quarters it can trigger a rally into $AAPL  $AMZN  on Thursday
 
If 3/4 of them can deliver on earnings... $SPY to 469 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:16:30 </td>
   <td style="text-align:left;"> ⭐️ ⭐️ Profits for today: $500.13 ⭐️ ⭐️ 

Took it very easy today. Didn’t force anything and wanted to get into ideally set up plays than risk more and possibly lose and be red for the day. Played small size and got bored a few times during the day. No big winners. Biggest winner was $NVDA with $175 in profits, followed up by $SPY and $KSS with around $90 each in profits. Goal for tomorrow and rest of this week will be $500 daily. Hope you all banked today. Have a good evening everyone 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:15:57 </td>
   <td style="text-align:left;"> $SPY We played it both ways today… Thanks to the UMG ALGO 💰💸💰💸  but our calls PRINTED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:15:50 </td>
   <td style="text-align:left;"> $SPY Would have rather seen it be a bit more bloody today since Pros wait for Tues to come back in. Have to think they Sell some of the pop tomorrow &amp;amp; wait for Earnings so,.. prepping for that 
 
$aapl $amzn $msft $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:15:43 </td>
   <td style="text-align:left;"> $SPY whats your EOY target here people? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:15:39 </td>
   <td style="text-align:left;"> $SPY if trump stays on truth social and refuses to go back to twitter... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:15:10 </td>
   <td style="text-align:left;"> $SPY if bitcoin hits 41300 we are going to $445 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:15:05 </td>
   <td style="text-align:left;"> New YouTube Video is LIVE! Discussing and giving an Update on the recent move on $SPY which I had mentioned was coming for the last few Weeks. If you are confused as to why we made the move that we did, check it out. $NKTX $RDBX $VERU $ATER https://youtu.be/lsc0LBiqqoU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:14:43 </td>
   <td style="text-align:left;"> $SPY time to load up on $TLRY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:14:27 </td>
   <td style="text-align:left;"> $SPY Here just buy and hold these if you aren&amp;#39;t doing well.  You&amp;#39;re probably trying to be too fancy and you&amp;#39;re also holding crypto or penny stocks or growth trash.  Stop that.  

AAPL
MSFT
NVDA
GOOGL
TSLA
ADBE
NET
DT
APPS
SMH

You&amp;#39;re welcome. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:14:03 </td>
   <td style="text-align:left;"> $TWTR $dwac 
$spy  $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-26 05:13:14 </td>
   <td style="text-align:left;"> $SPY I wouldn’t give 44 billions for a social media platform . Worse investment ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:45:30 </td>
   <td style="text-align:left;"> $SPY $QQQ sorry to break it to you guys but this clearly was a dead cat bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:42:48 </td>
   <td style="text-align:left;"> $QQQ Nasdaq McClellan Oscillator:  turning up again - still looking for bullish MacD cross </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:30:56 </td>
   <td style="text-align:left;"> Since December heavy put interest centered around 3/18 for $QQQ. So far 3/15 has marked bottom for $NASDAQ. After Netflix, and other big tech declines put interest has soared, but my theory is smart money bet on the decline in December, bottomed March on fed rate decision and everybody else who has these doom &amp;amp; gloom scenarios are just those who came to the party late. Everything thus far backs up my thesis. 

Who is selling all these puts now, and who is buying them? Key point to reflect on is who is saying what at what time during sentiment at not seen lows since 1987. $SPY $SPXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:29:43 </td>
   <td style="text-align:left;"> $QQQ the ole’ Monday bull trap $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:23:42 </td>
   <td style="text-align:left;"> $QQQ held well since open trapping bears 🐻 for couple of hours dumping $SPY with non-tech selling, PCR ratio of 1 means most likely puts will go worthless . Check huge puts volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:22:21 </td>
   <td style="text-align:left;"> $FB back at the 2 Yr Uptrend line... as $QQQ at a quasi-double bottom. Now its all about Nasdaq 100 $NDX earnings from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:21:35 </td>
   <td style="text-align:left;"> Today&amp;#39;s PnL GREEN $8,000, slower small day. Didn’t trade much at all. SEE MY BIO to join 1000s of members. Super busy with personal things and errands. Waiting for the volatility Wed-Thurs with mega cap tech ERs. Sniped $DWAC puts that was about it for 100%, swing puts for $35 strike running more then 400%+ though. Will be patient all week not forcing size if needed. $LGVN $SBFM $NKTX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:20:07 </td>
   <td style="text-align:left;"> $IRNT this stock will make you rich. Buy and HODL $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:18:00 </td>
   <td style="text-align:left;"> $QQQ Cramer is bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:15:09 </td>
   <td style="text-align:left;"> $SPY is moving very slowly into a bear market and then a recession a bit later but do NOT fret.  It will be ugly and then more ugly in time.  
 
So important for $$$ mgrs to get ready for the carnage before the next brutal news bite hits our screens.  Exit at best prices. 
 
We know all too well how markets can reverse in &amp;#39;news&amp;#39; that we all knew.  50 points and 75 points per month but who&amp;#39;s counting???  LOL 
 
We don&amp;#39;t want to bleed  but that is out life into 2023&amp;#39;+ 
 
 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:11:54 </td>
   <td style="text-align:left;"> $SPY $QQQ we live to trade another day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:10:58 </td>
   <td style="text-align:left;"> $SPY $QQQ Per Charlie McElligott, extreme negative delta and negative gamma ... aka &amp;quot;kindling&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:10:14 </td>
   <td style="text-align:left;"> $SPY $QQQ Everyone should give this list a really hard look to understand what &amp;quot;big&amp;quot; days for the markets actually look like....  

https://en.wikipedia.org/wiki/List_of_largest_daily_changes_in_the_S%26P_500_Index

For example we&amp;#39;ve had 10 HUGE $10-$20+ single day gains on SPY since COVID.  Something to keep in the back of your mind after last week and todays rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:10:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 73507200. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:09:47 </td>
   <td style="text-align:left;"> Our piggy had a great day. She got drowned @ $420 and revived to $428.  Is it manip?  Most likely to some degree. 
 
Think for a moment about what recent catalysts allowed the markets to fall rather quickly from the sweet $450 to $425 in a flash. Do not forget that the blood out there has yet to dry. 
 
When the $SPY trades normally in the $405 to $415 area in the near future, there may be some buy opps in some areas, in others not. The roller coaster rides will eventually force investors to lose millions in 22&amp;#39; and that reality is hard to accept. 
 
Will Retail realize the need to protect equity assets soon or will most just keep reaching for the Kool Aid?  I think we are getting more savvy about how to proceed. 
 
$SPY  $QQQ    We must avoid swallowing the poison pills. 
 
$420- 
 
$VXX on radar... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:09:25 </td>
   <td style="text-align:left;"> $SPY $QQQ Rally time, aka reversion to the mean. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:07:32 </td>
   <td style="text-align:left;"> $QQQ Is not going to crash below this level but will in the side channel for couple of months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:05:03 </td>
   <td style="text-align:left;"> $NFLX $SPY $QQQ All bulls double up your Netflix position tomorrow and let’s short squeeze this beotch back above $300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 06:01:26 </td>
   <td style="text-align:left;"> $QQQ $SPY seems like pump today could’ve been fake out ..what you guys think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:59:15 </td>
   <td style="text-align:left;"> $NFLX $AAPL $QQQ $SPY  Aapl should buy NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:59:12 </td>
   <td style="text-align:left;"> US equity funds have seen outflows of $30 billion over the past two weeks. 
 
h/t @SoberLook  
 
$SPY $QQQ $DIA etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:59:00 </td>
   <td style="text-align:left;"> $QQQ $SPY  so tell me…who bought puts at 418🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:55:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $TWTR https://www.instagram.com/tv/CcyVP9bDzJe/?igshid=MDJmNzVkMjY=

😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:54:16 </td>
   <td style="text-align:left;"> $SPY 30 second ads on netflix will cost 175k $NFLX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:53:09 </td>
   <td style="text-align:left;"> $QQQ sell before may and go away! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:53:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY How can Joe Biden and the Dems control inflation? It&amp;#39;s very simple; run a smaller, more efficient government and pay down the national debt🗽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:49:18 </td>
   <td style="text-align:left;"> NASDAQ $QQQ Top Gainers during today $MRNA $MTCH $MELI $FTNT 
  
Learn more: https://www.finscreener.org/screener/top-gainers/stocks/nq100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:48:10 </td>
   <td style="text-align:left;"> $QQQ *Michael burry mysteriously disappears*   /delete twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:47:26 </td>
   <td style="text-align:left;"> $QQQ  RIP to all the 401ks that will flow in on 29th. Black Friday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:45:21 </td>
   <td style="text-align:left;"> $QQQ MSFT, GOOG, and AAPL will definitely beat earnings IMO. I&amp;#39;m not very confident about AMZN or FB. I&amp;#39;m giving those two a miss or in-line with bad guidance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:43:59 </td>
   <td style="text-align:left;"> $DKNG $LVS  $PENN $FUBO $QQQ  Fade Paul Pierce😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:43:16 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
so far so good 
 
psychology creates the shape, not the reverse 
 
no crash  
 
almost confirmed 🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:39:20 </td>
   <td style="text-align:left;"> Market Summary Update: We got a short term oversold signal today intraday. Good bounce since then. $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:33:41 </td>
   <td style="text-align:left;"> $QQQ $AAPL Apple never really &amp;quot;misses&amp;quot; on earnings, the worst they do is maybe just not knocking it out of the park </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:32:20 </td>
   <td style="text-align:left;"> $QQQ puts going to .01 hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:31:22 </td>
   <td style="text-align:left;"> Today&amp;#39;s action made us feel like the Abyss is far away but oddly enough it&amp;#39;s right behind us covered with beautiful leaves.  The action is so deceiving but lucrative also for just a period of time which is getting shorter by the day. 
 
Amazing power on the call payouts as well as puts!  Thank you 
 
$SPY    $QQQ 
 
Now that the popper is over, how long before the Boyz figure out the timing for the next drop to the $420 area??? 
 
Tic tic tic.....   nasty moves for all kinds of catalysts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:31:08 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 4/25/2022 $SPY $TWTR $TSLA $QQQ $XBI https://www.chartguys.com/daily-market-videos/4219/bulls-stop-the-bleeding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:29:53 </td>
   <td style="text-align:left;"> $QQQ I would laugh of this thing fell again by Friday. People will never learn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:28:54 </td>
   <td style="text-align:left;"> Impeccable market reversal timing…On 4/5 Sam signaled that volume and breadth were starting to roll over…since then $SPX has dropped over 5% and $QQQ over 8% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:28:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $TWTR $DWAC so all cockroaches leaving twitter? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:27:50 </td>
   <td style="text-align:left;"> $SPY looking for a 1.5% gain tomorrow, ok $QQQ looking for a 2% gain and then Wed at open expecting both to push to close to 3% at least by 10am reaching high of week and then collapsing for next leg down to end week much lower than open. I’m thinking peak will be near $450 for a triple top on the SPY and near $345-$348 for the Q’s for a triple top there as well. This hinges on $MSFT and $GOOG ER beat and forward guidance beat. I’m expecting Azure to beat growth estimates leading growth on both top and bottom lines as well as Google Cloud for $GOOG offsetting loss on search ad revenue due to Apple privacy and reduced ad spend headwinds. If tomorrow indeed does pump, will probably go into Wed just to be flat ready to get puts on everything after morning bell push. If and when spy passes $448 and the Q’s pass $343, will start scaling in puts for Friday. I cannot wait for Amazon to drop 20%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:26:31 </td>
   <td style="text-align:left;"> $QQQ $SPY More downside is expected. https://www.youtube.com/watch?v=7PO_uFxtU2U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:25:19 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:25:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA The market&amp;#39;s getting ready to torch the puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:22:49 </td>
   <td style="text-align:left;"> $VERU how do you penny trading novices not understand that today’s oral presentation of Ph2 data is meaningless? We already saw Interim Ph3 and it SUCKED in trial design…you can’t be positive by going back in time. So many idiots. $5 PT. 😂😂😂😂🤦‍♂️🤦‍♂️🤦‍♂️🤦‍♂️ $XBI $XLV $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:22:38 </td>
   <td style="text-align:left;"> $QQQ  Went short after todays earnings and selling these puts first thing AM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:19:05 </td>
   <td style="text-align:left;"> $IRNT 10s of millions of $$$ coming in soon. They have just been waiting for government funding which a bill was passed in mid March by government that’ll likely fund some of these projects. Also biden has mentioned an increase in cybersecurity spending for FY23. You can see in the December call the general mention the amount of money two of these deals will bring in for them https://seekingalpha.com/article/4475481-ironnet-inc-irnt-ceo-keith-alexander-on-q3-2021-results-earnings-call-transcript
 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:18:35 </td>
   <td style="text-align:left;"> $QQQ I’m still holding $TQQQ gains but am afraid any poor guidance by one mega cap and Nasdaq slide down the drain, easy in high 11k. 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:17:09 </td>
   <td style="text-align:left;"> $AAPL $MSFT $SPY $QQQ I’ll leave you with this. So many have grown bearish which translates to we will see a pump. It’s seems as if no one learns their lesson. Rather than profit,  they simply want to be right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:16:54 </td>
   <td style="text-align:left;"> $QQQ earnings pump in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:16:14 </td>
   <td style="text-align:left;"> $QQQ i should have shorted this end of day today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:15:50 </td>
   <td style="text-align:left;"> $SPY Would have rather seen it be a bit more bloody today since Pros wait for Tues to come back in. Have to think they Sell some of the pop tomorrow &amp;amp; wait for Earnings so,.. prepping for that 
 
$aapl $amzn $msft $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:15:34 </td>
   <td style="text-align:left;"> $QQQ i am surprised this bounced up. This morning I panic sold for a tiny loss but sure enough it bounced up afterwards..... holding over weekends when the Vix futures shoots through the roof is not my forte........ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:15:27 </td>
   <td style="text-align:left;"> $QQQ crashing AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:11:43 </td>
   <td style="text-align:left;"> $QQQ it&amp;#39;s weird to me that a green or red day is enough to bring either side out in force.. market is obviously going to be volatile next couple of weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:11:11 </td>
   <td style="text-align:left;"> $IRNT government deals are coming soon. This is an amazing opportunity. Co founder/co CEO was the head of the NSA. Many other ex NSA employees also working for the company. This is literally a steal T these prices $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:10:28 </td>
   <td style="text-align:left;"> $QQQ going short here, already down in AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:07:01 </td>
   <td style="text-align:left;"> $SPY $QQQ needs to recapure major resistance before I turn bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:06:17 </td>
   <td style="text-align:left;"> $TWTR $SPY $QQQ You know what to do boys, time to give Karen a squeeze!!!! 🤣🚀🧨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:06:02 </td>
   <td style="text-align:left;"> $AAPL $MSFT $SPY $QQQ Nasdaq will get back to 14k. Dow 35k. It’s a simple game of back and forth! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:04:27 </td>
   <td style="text-align:left;"> $QQQ whose ready for that money printer this week the idiots have spoken </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 05:02:00 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-04-25 Chart Analysis Video: 
https://www.youtube.com/watch?v=_yC_hgpAiSA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:59:52 </td>
   <td style="text-align:left;"> $QQQ $BTC.X $ETH.X $DOGE.X I think crypto&amp;#39;s going to rally from here with Elon&amp;#39;s buyout of Twitter!🐤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:59:34 </td>
   <td style="text-align:left;"> $ARVL $SPY $QQQ 

If anyone here is scared to see 24% short interest, I would recommend them to see $LCID short interest. It is over 20% despite of having LCID ahead of ARVL in all aspects. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:59:22 </td>
   <td style="text-align:left;"> $CRM heading down 138.00 to 130.00 ‘s 
Aging Garbage 
$QQQ $SPY $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:57:42 </td>
   <td style="text-align:left;"> $QQQ started a 15k short position at the end. Easily down 1% tomorrow no biggie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:57:35 </td>
   <td style="text-align:left;"> $QQQ OVERSOLD TODAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:56:56 </td>
   <td style="text-align:left;"> $QQQ Wow the manipulation is insane,  that run into close and the second the market closes and algos turns of the market stops? what happened to the hype and momentum? How anybody can thay invested in this corrupt market is beyond me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:56:16 </td>
   <td style="text-align:left;"> $QQQ I think this would be too easy. MM&amp;#39;s not gonna let you win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:55:35 </td>
   <td style="text-align:left;"> latex48df55ca281c0cb9c9cad04923868830SPY  
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:52:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:51:34 </td>
   <td style="text-align:left;"> $SPY $QQQ WILL ELON MUSK BRING BACK THE FAIL WHALE? 🐋🤔 $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:50:58 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 988.2K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:49:36 </td>
   <td style="text-align:left;"> $QQQ Haha 
 
Bozo knuckleheads are pathetic....LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:48:10 </td>
   <td style="text-align:left;"> $QQQ 7% down 1% Up haha nothing has changed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:47:25 </td>
   <td style="text-align:left;"> $QQQ W variation after all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:47:23 </td>
   <td style="text-align:left;"> $ARVL $SPY $QQQ 

Wall Street is not less than a prostitution business. They play all kind of dirty games. If there is something wrong with ARVL products &amp;amp; process to make their products, Wall Street pimps would creat some kind of hype to sell their holdings to retail fools. But, they are doing opposite. They are scaring the retail investors &amp;amp; buying their stocks at low price. They are still not done scaring small guys. Wait for some time &amp;amp; see these pimps singing completely different song. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:44:30 </td>
   <td style="text-align:left;"> $QQQ tech going to hold up the rest of the week or was this just Monday funday before it collapses again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:42:36 </td>
   <td style="text-align:left;"> $QQQ a Green Day ? wtf this pump n dump scam of a stock doing, wen rug pull ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:40:02 </td>
   <td style="text-align:left;"> $SPY $QQQ

I was correct </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:38:36 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMD $MU $TQQQ Hey Bears, how are things? Did that go the way you expected? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:38:28 </td>
   <td style="text-align:left;"> $QQQ Made big money Both ways if you followed my trade plan that I post on twitter everyday for free. It makes money every single day. Follow me on twitter at optionboys. I post detailed market analysis and free trade plans there everyday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:38:00 </td>
   <td style="text-align:left;"> $QQQ $SPY feels like a shake out today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:37:25 </td>
   <td style="text-align:left;"> $QQQ Day trade!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:37:10 </td>
   <td style="text-align:left;"> $QQQ cal1928 gives me the laughs I tell you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:36:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Elon Musk proves that he is a GOP person rather than a Dems person, President Biden did the right thing by preferring great companies like GM and Ford over Tesla $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:35:23 </td>
   <td style="text-align:left;"> $TWTR $qqq $spy everyone to report Justin Trudeaus account </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:35:14 </td>
   <td style="text-align:left;"> $QQQ Big boys report tomorrow: GOOGL MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:35:12 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM 100% long (see my 4/22 tweet) 
 
Got back in around where I exited on Friday...smh 
Now, let&amp;#39;s get some continuation so we can make mula  
 
Anyone went long/short today?  Which stocks/ETFs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:32:23 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-04-25 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=ipC2DJu1pps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:31:39 </td>
   <td style="text-align:left;"> Closed at the pivot.  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:30:56 </td>
   <td style="text-align:left;"> $QQQ bear market rally begins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:30:09 </td>
   <td style="text-align:left;"> $SPY $QQQ Now I am getting worried that Musk will allow Trump to post on Twitter again, Trump is an extremely dangerous guy to this country and he shouldn&amp;#39;t be allowed to post on social media ever again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:28:12 </td>
   <td style="text-align:left;"> $QQQ Dangerous territory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:27:52 </td>
   <td style="text-align:left;"> Generational buying opportunity squeeze of a lifetime are you ready $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:27:35 </td>
   <td style="text-align:left;"> $AMD Nice bullish reversal in the latexb8d855e443477159d011b88fa92117ce 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:25:55 </td>
   <td style="text-align:left;"> $TWTR if 60c prints, maybe we won&amp;#39;t run this capalist empire to the ground. $spy $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:24:23 </td>
   <td style="text-align:left;"> Todays price action is exactly the same as every single bottom this year lol.  Its going to go parabolic next. $spy $qqq FOMO &amp;gt; FOLM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:23:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$264M to the SELL side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:22:35 </td>
   <td style="text-align:left;"> $SPY $QQQ after market close Tuesday and Thursday are your mega cap market movers earnings releases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:22:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:22:13 </td>
   <td style="text-align:left;"> $QQQ is this a make up rally? How long this last? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:21:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:21:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 4/26 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:19:36 </td>
   <td style="text-align:left;"> $QQQ $V $PEP $UPS $CMG 
Earnings Tomorrow 
https://www.financegreater.com/earnings-calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:19:01 </td>
   <td style="text-align:left;"> $SPY $QQQ Good work today buyers, kept us in the game on a Monday. Defended the anchored VWAP from the 2020 election pop. (for now) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:18:55 </td>
   <td style="text-align:left;"> $SPY I can hear the woke lefties screaming in the distance $TWTR $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:18:36 </td>
   <td style="text-align:left;"> $MSFT technically MACD close to flipping over and Stoc very low... any good earnings surprise should be a reason for another pop. Held the 272~  support! $QQQ Don&amp;#39;t forget office enterprise price was hiked 20% last year and it should have kicked in this quarter! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:17:43 </td>
   <td style="text-align:left;"> $QQQ $329.26 is the bull/bear battleground through the EOM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:17:34 </td>
   <td style="text-align:left;"> $TWTR $Googl $fb $spy $QQQ  
$54.20 🫶🏼🫶🏼🫶🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:17:23 </td>
   <td style="text-align:left;"> $QQQ bulls need to take out that $370 level... $350 if they want to get back above resistance. $QQQ is down around -17% year-to-date. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:17:08 </td>
   <td style="text-align:left;"> $QQQ dead-cat bounce.  Last two sessions (from the morning peak on Thurs) were down over 7%, we were due for a 2% bounce (2% off today&amp;#39;s lows).  Likely more dumpage tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:16:32 </td>
   <td style="text-align:left;"> $QQQ whipsaw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:16:14 </td>
   <td style="text-align:left;"> $QQQ Oversold on a lot of time frames. 
Not sure this bounce is anything more than that????. 
 
Bulls need a break, earnings will dictate from tomorrow on. 
GL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:14:43 </td>
   <td style="text-align:left;"> Elon took $TWTR out of the shitter for good now $TSLA $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:14:11 </td>
   <td style="text-align:left;"> $QQQ I see up from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:13:56 </td>
   <td style="text-align:left;"> $NKTX What a day for this 🔥📈 New high of day reached consistently. $SPY $QQQ $DIA $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:13:15 </td>
   <td style="text-align:left;"> $SPY $QQQ For me I would much rather invest in Google or Apple than Tesla since I don&amp;#39;t see Pichai or Cook seeking attention or trolling on Twitter like Musk does </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:12:21 </td>
   <td style="text-align:left;"> $QQQ loaded to the tits with 445s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:12:00 </td>
   <td style="text-align:left;"> Market wrap: 
🔷 US indices closed higher on the day:  
$DJIA +0.7%, $SPX +0.6%, $QQQ +1.3% 
🔷 #Gold (-1.8%) and #WTI (-3.0%) both fell. 
🔷 #JPY was the day&amp;#39;s strongest major currency; #AUD was the weakest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:11:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $NVDA nice afternoon, wonder if we see $440 out of spy this week on big tech earnings.

Weary of Twitter — how does a miss there effect the rest of the world 🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:11:02 </td>
   <td style="text-align:left;"> $QQQ nas up 200 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:10:25 </td>
   <td style="text-align:left;"> $TWTR $54.20 this has one more pop to go. ⏰  $spy $qqq $fb $googl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:10:25 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Still holding my 3 MES short from 4290 and ready to add more higher. 
 
gl! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:09:56 </td>
   <td style="text-align:left;"> $QQQ This only went up 1.28%, that&amp;#39;s not exactly rocketing. Trade carefully in whatever direction yall choose this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:09:34 </td>
   <td style="text-align:left;"> $BTC.X Keep an eye on the $QQQ if we clean break above $330 I believe we&amp;#39;ve got a green light for $41,000+ here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:09:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $VIX  market can only go green while interest rates take severe moves to the downside . Market literally can’t go up without more inflation haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:09:06 </td>
   <td style="text-align:left;"> $QQQ Day 1 of rotation into tech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:09:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 73764000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:08:46 </td>
   <td style="text-align:left;"> $QQQ 4 hours ago 🔮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:07:53 </td>
   <td style="text-align:left;"> $QQQ bought $330c for weds. Fuck you bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:07:45 </td>
   <td style="text-align:left;"> $SPY $QQQ  Folks! There is BILLIONS and BILLIONS of Dollars waiting to BUY THIS MARKET...  Dont let the idiots and scammers tell you liquidity is trying up, its all LIES!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:07:36 </td>
   <td style="text-align:left;"> Markets Pare Early Losses As Musk-Twitter Agree On Buyout Deal  $QQQ $SPY $DIA $MRNA $MTCH 

https://newsfilter.io/a/606f4fd18b81954c173bf112462f1175 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:07:08 </td>
   <td style="text-align:left;"> $PYPL $DOCU $ZM $QQQ $XLK 3 Tormented Tech Stocks To Avoid, excellent Seeking Alpha article:https://seekingalpha.com/article/4503153-tech-stocks-to-avoid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:06:23 </td>
   <td style="text-align:left;"> $SPY $QQQ A great close. I think investors are finally realizing that they should not be afraid of the FED at all, the US economy will continue to do well and earnings will continue to rise. If earnings are rising then the market should be rising as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:05:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX i think it’s very safe to say there’s bigger things to worry about rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:04:26 </td>
   <td style="text-align:left;"> $NVDA these MMs are crooks, they cut my 190c in half but robbed my Puts 
this is about to be a fucked up week 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:04:12 </td>
   <td style="text-align:left;"> $SPY $QQQ everything earnings dependent. All the majors report this week. Heat map tells the story. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:03:24 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:03:14 </td>
   <td style="text-align:left;"> $QQQ Record volume across all indexes, and stocks. 
Must have been retail. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:03:14 </td>
   <td style="text-align:left;"> This alert on $TQQQ was delivered today this morning at 7:59AM CDT on 4/25/2022 🎯 

Nice start to the week guys 👍
Next critical level to watch for is $45.75👀

For Real-time Alerts — link is on my bio. $SQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:03:10 </td>
   <td style="text-align:left;"> $QQQ struggling to stay green today, I don&amp;#39;t trust shit! $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:03:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA NO MORE $TWTR ON THE S&amp;amp;P 500 THANK YOU ELON $TSLA I WILL BE DRINKING AFTER WORK 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:02:42 </td>
   <td style="text-align:left;"> $SPY $QQQ stupid bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:02:27 </td>
   <td style="text-align:left;"> $SPY $QQQ CONGRATS  BULLS! AMAZING BEAUTIFUL GREEN FINISH! We will fly all week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:01:36 </td>
   <td style="text-align:left;"> $QQQ let&amp;#39;s short big tech into earnings after a complete clown fucking of it a week before.... Genius guys. Utterly genius. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:01:23 </td>
   <td style="text-align:left;"> $SPY  $QQQ The Goat, Cramer for president!! @JimCramer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:00:49 </td>
   <td style="text-align:left;"> $QQQ Got to have balls to be playing in this market. 
Not for the weak, or the smart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 04:00:41 </td>
   <td style="text-align:left;"> $QQQ In $ELON.X name we trust. He is single-handedly brought the market back to life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:59:15 </td>
   <td style="text-align:left;"> $QQQ my calls for Microsoft, qqq and tqqq from this morning are green green 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:59:10 </td>
   <td style="text-align:left;"> $QQQ here comes the FOMO. What a recovery though nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:58:26 </td>
   <td style="text-align:left;"> $QQQ PUUUUUSSSH!!! $SPY 🤟🏼🙋🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:58:25 </td>
   <td style="text-align:left;"> $SOFI - zoom on the $QQQ - there’s a massive H&amp;amp;S. Left shoulder formed 2/21. 

Good luck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:57:58 </td>
   <td style="text-align:left;"> Shared with Finom Group earlier: 

J.P. Morgan&amp;#39;s Man Who Moves Markets Kolanovic:

Equity rally to begin this week, broad end of quarter positioning favors alongside post peak buyback blackout period $QQQ $SPY $SPX $UVXY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:57:48 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ win win ,see previous comments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:57:46 </td>
   <td style="text-align:left;"> $QQQ Puts now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:57:42 </td>
   <td style="text-align:left;"> triple bottom $QQQ I&amp;#39;m buying here for a bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:57:36 </td>
   <td style="text-align:left;"> $QQQ I know enough now to know that I don&amp;#39;t know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:56:58 </td>
   <td style="text-align:left;"> $QQQ to the mooon *lol* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:56:30 </td>
   <td style="text-align:left;"> $SPY New CEO for Twitter $TWTR $QQQ $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:56:04 </td>
   <td style="text-align:left;"> $QQQ big BULL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:56:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA LINE ES MUY LOCO 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:56:00 </td>
   <td style="text-align:left;"> $QQQ Historically speaking, V bottom is more likely than a crash, especially on no news.  Sell off was just OPEX related riff raff. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:56:00 </td>
   <td style="text-align:left;"> $SPY $QQQ I think Tesla stock is a short now. Elon Musk seems to be an attention seeker now rather than a great innovator/CEO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:55:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Let’s go bulls… if you are alive still </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:55:35 </td>
   <td style="text-align:left;"> $QQQ $SPY  who’s chasing this fake pump? 😀🤑😆😂😅🤣💰💲💰💲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:55:00 </td>
   <td style="text-align:left;"> $QQQ Reversal! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:54:46 </td>
   <td style="text-align:left;"> $QQQ out the add on +6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:54:27 </td>
   <td style="text-align:left;"> $QQQ Short SQUEEEEEEZZEEEEEE! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:53:57 </td>
   <td style="text-align:left;"> $QQQ get fucked shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:53:46 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $NASDAQ Who told ya,a major bounce ahead. Inflation already Peaked, pretty Obvious. Wait April CPI and see by yourselves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:53:37 </td>
   <td style="text-align:left;"> $SQQQ $TQQQ $QQQ $spy  Perma-bears gonna get smashed if they don&amp;#39;t play it safe around major support. Just saying. I rocked nearly $60k being a bear for April, but played it bull today. Wouldn&amp;#39;t surprise me if we bottom today with earnings as a tail wind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:53:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Today&amp;#39;s theta-burning and paint-drying session brought to you by: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:53:06 </td>
   <td style="text-align:left;"> $NKTX Continuing to push to the upside 📈 Do we think this has the ability to reach 180%? I have not seen a lot of momentum plays continue to follow through recently. I’ll keep following the volume and watching for significant buying and selling. $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:51:58 </td>
   <td style="text-align:left;"> $SPY but I thought rates at 3% was going to cause a depression 🤣🤣🤣. Bears you&amp;#39;ve had your time. A double bottom on the $QQQ . Time to go long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:51:43 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Bears fail to take control of the market once again. 
 
They got WRECKED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:50:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $XBI Always trust the charts. $SPX weekly chart says that if Feb 22nd low is broken then we are heading for a secular bear market. It&amp;#39;s too soon for a secular bear market, IMO, that&amp;#39;s why I believe we will have THE devastating rally I&amp;#39;ve been expecting for sometime; $SPX 5300-6000, before a bear maket in Spetembre-October.  We&amp;#39;ll see.  
If we close below 4160, I would hedge; if we go below 4114, I would go short at the first bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:50:12 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY $DJIA $ETH.X  
said this early morning 
buy anything today morning and u will make money 
market going from red to green today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:49:34 </td>
   <td style="text-align:left;"> $QQQ where is bloodbath?😝😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:49:09 </td>
   <td style="text-align:left;"> $SPY  If you took these contracts from entry mentioned, you kinda Banked. 📣💜 Our Live channel is very real $QQQ $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:47:20 </td>
   <td style="text-align:left;"> $QQQ 174 per  contract..out!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:46:39 </td>
   <td style="text-align:left;"> $QQQ cant go down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:46:21 </td>
   <td style="text-align:left;"> $QQQ Liquidity rising with price into the close with MV pinned up ⬆️ with + energy wound 🆙 like clock ⏰ in position for fueling⛽️ the next up cycle (PINKY BAR early in the week) Market is gifting us with range, liquidity and numbers enjoy!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:46:10 </td>
   <td style="text-align:left;"> latexacaac2787b02c8569da88c6246d4f51aQQQ crazy moves.  Congrats Team. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:45:33 </td>
   <td style="text-align:left;"> FOMO!!! FOMO!!! FOMO!!!! 
 
The FEAR of missing out far outweighs the FEAR of losing money!!!! 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:45:22 </td>
   <td style="text-align:left;"> $TWTR $SPY $QQQ $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:45:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA S&amp;amp;P 500 (SPY) Technical Analysis, Forecast, and Trade Ideas:  
https://www.youtube.com/watch?v=-qk9jbiUM4E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:45:05 </td>
   <td style="text-align:left;"> BUY THE DIP NOW OR FOREVER HOLD YOUR PEACE 
 
ITS BLAST OFF TIIIIMMMEEE!!!! 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:44:57 </td>
   <td style="text-align:left;"> $QQQ 100 Week MA acting as resistance. En garde </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:44:57 </td>
   <td style="text-align:left;"> $QQQ wow i got rekt hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:44:48 </td>
   <td style="text-align:left;"> $SPXL $SPY $QQQ $SPX (4280) is here. Capitilize on it. Glta </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:44:41 </td>
   <td style="text-align:left;"> $QQQ easy slingshot BO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:44:34 </td>
   <td style="text-align:left;"> $QQQ what a game.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:44:34 </td>
   <td style="text-align:left;"> The BULL MARKET is BACK!!! 
 
THEY ARE BUYING THE FKN DIP FEVERISHLY 
 
LETS GOOOOOO 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:44:03 </td>
   <td style="text-align:left;"> $QQQ *has one Green Day in tech*

Wow bears rekt! Must suck not being long ! 

*down 2% next day*

🦗🦗🦗🦗🦗🦗🦗🦗🦗🦗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:43:50 </td>
   <td style="text-align:left;"> $QQQ when all of retail is short, wait for the squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:43:20 </td>
   <td style="text-align:left;"> $QQQ Leave the phone on DICKHEADS. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:43:04 </td>
   <td style="text-align:left;"> $SPY   Everything is good????  Hmmmm.... 
 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:42:58 </td>
   <td style="text-align:left;"> $SPY $QQQ Great to see an intraday turnaround like this, the market clearly has bottomed and should be up from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:42:36 </td>
   <td style="text-align:left;"> $QQQ $330 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:41:52 </td>
   <td style="text-align:left;"> $QQQ BEARS ARE FUCKED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:41:50 </td>
   <td style="text-align:left;"> $FB $QQQ $NFLX my calls soaring. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:41:00 </td>
   <td style="text-align:left;"> $QQQ looks like Nas is going for 13,000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:40:57 </td>
   <td style="text-align:left;"> $spy $qqq https://www.youtube.com/watch?v=_NJAeeHdJjE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:40:28 </td>
   <td style="text-align:left;"> $QQQ haven’t been watching all day. Want to gamble. Calls or puts at close? Weeklies only. TELL ME WHAT TO BUY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:40:12 </td>
   <td style="text-align:left;"> $QQQ Could it be the beginning of a I of III? I went very heavy on that assumption... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:40:01 </td>
   <td style="text-align:left;"> $AAPL $AMC $SPY $QQQ the rule still stands. Dow down 1000 and you will see a Green Day the following day! 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:39:43 </td>
   <td style="text-align:left;"> Now THATS what you call a face ripping V rally wooooooow 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:39:36 </td>
   <td style="text-align:left;"> $SPXL $UVXY$SPY $QQQ Folks: Do not underestimate lower 10 yr yield drop, oil pricing &amp;quot;collapse&amp;quot;, commodities deflation, oil&amp;amp;oil service companies correction and yes Twitter purchase for $44 Billion and the provided financing. All are pointing towards a beginning of a strong rebound in the markets. Initiate or add on the cheap. Glta. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:39:36 </td>
   <td style="text-align:left;"> 💥Bulls dip buying: If I&amp;#39;m early I have time. 
 
💥Bears shorting rips: If I&amp;#39;m wrong I lose. 
 
💥The market is not a zero-sum game; use the time  
      value component wisely  
 
$SPY $QQQ $DIA $ $AMZN  $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:39:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $ES_F $BTC.X $ETH.X Weekly candle, so need a Friday close, but it looks pretty sitting on the support. 
 
For me, a bullish trend needs to hold a weekly 9ma. That&amp;#39;s the pending take here, this week and next while the support holds. 
 
Best of luck! 🍪 
 
🎩 
🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:39:08 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIXY $UVXY $SQQQ like I said earlier market looked beyond ready for a nice bull run. Projecting this to continue into tomorrow. Lets go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:38:43 </td>
   <td style="text-align:left;"> $TSLA On Elon, why did you do it. We all know the feeling of wanting that girl or that shiny new toy &amp;amp; once we get it reality sets in. Just ask Kanye 
 
A year from now this will now be good. 
 
Howard Hughes here we come 
 
$TWTR $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:38:18 </td>
   <td style="text-align:left;"> Financial Protection Bureau Has New Supervisory Powers 
 
Read: https://www.channelchek.com/news-channel/Financial_Protection_Bureau_Has_New_Supervisory_Powers  
 
#fednews #fed #inflation #FPB #SEC 
 
$SPY $QQQ $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:38:10 </td>
   <td style="text-align:left;"> $SPY $QQQ very chopy. Text book bear market rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:37:53 </td>
   <td style="text-align:left;"> $TSLA damn this should be trading over $1000 easily with $QQQ running!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:37:48 </td>
   <td style="text-align:left;"> No horoscopes, or fortune tellers needed - just options!!!!!l

I wrote this 1/26, walls appeared in December, bottom was 3/15.

Puts are flagging the market bottom. This appeared early as December, here is proof from January 26th. People who rely only on TA/Macro are trading stocks color blind! $SPY $NASDAQ $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:36:24 </td>
   <td style="text-align:left;"> Quite the rally today 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:34:12 </td>
   <td style="text-align:left;"> $QQQ oh look, a lower high and a lower low on the day and the bulls are throwing a fucking party. what a shock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:33:55 </td>
   <td style="text-align:left;"> $QQQ when retail goes short. You go long and vice versa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:33:26 </td>
   <td style="text-align:left;"> $QQQ Absolute FUCKTARD ANNIHILATION ... Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:32:59 </td>
   <td style="text-align:left;"> $QQQ I can already picture the beautiful W forming on the way to 400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:32:48 </td>
   <td style="text-align:left;"> $QQQ Could this be a bottom?  Yes, yes it could.  Friday (unlike Thursday) has potential to be a capitulation bottom.  I&amp;#39;m betting more weakness after ERs but the market is forcing me to consider the possibility that a bottom has happened.  As I&amp;#39;ve said, I will remain short well after the bottom - giving back a few profits is better than missing out by playing safe on these wild swings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:32:23 </td>
   <td style="text-align:left;"> $NQ_F $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:30:09 </td>
   <td style="text-align:left;"> Opinion: Here’s why you should be wary of buying the stock-market dip https://www.billionaireclubcollc.com/opinion-heres-why-you-should-be-wary-of-buying-the-stock-market-dip/  $DJIA $QQQ $DXY $SPY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:29:40 </td>
   <td style="text-align:left;"> $QQQ 475 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:29:31 </td>
   <td style="text-align:left;"> $SPY clean air social media $SNAP $TWTR $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:29:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL $DIA 

 Setting up outside reversal of the Thursday outside reversal which typically happens on average 10days apart. Last time took a little longer at 15 trading days so if this one is quicker than average… data since 1990 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:29:03 </td>
   <td style="text-align:left;"> NEW POST: Looking for Solid Support https://marketchess.com/blog/view/looking-solid-support $FCX $LAC $MP $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:28:35 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA Man, Michael Burry is the most funny character in Wallstreet. 
 
He&amp;#39;s all acting cryptic, coming to twitter saying stuff like &amp;quot;I warned you guys....&amp;quot;   &amp;quot;At least I tried&amp;quot;.....  &amp;quot;Biggest crash in history coming&amp;quot; 
 
And then literally the next day you get a huge green rally and he deletes his Twitter again. 
 
The dude is a meme at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:27:27 </td>
   <td style="text-align:left;"> $SPY $QQQ   ahuevo cabrones! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:27:06 </td>
   <td style="text-align:left;"> Stocks recover much of their early losses on Wall Street https://www.billionaireclubcollc.com/stocks-recover-much-of-their-early-losses-on-wall-street/  $SPY $DJIA $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:26:13 </td>
   <td style="text-align:left;"> $SPY $QQQ where are those mfing bears flooding here all weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:25:37 </td>
   <td style="text-align:left;"> $QQQ wtf is going on 🤣🤣 love it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:25:28 </td>
   <td style="text-align:left;"> $SPY wondering bears went hibernation lol 🤣 probably their puts went waste!!! 

$IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:25:21 </td>
   <td style="text-align:left;"> $SPY $QQQ patience is everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:25:15 </td>
   <td style="text-align:left;"> $QQQ Bouncing of the weekly 100MA again, bears who didn&amp;#39;t see it and exit their positions now trapped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:24:11 </td>
   <td style="text-align:left;"> $QQQ Bwahahahahaha 
 
MARGIN CALLS 
 
LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:23:57 </td>
   <td style="text-align:left;"> $TWTR $SPY $QQQ $NASDAQ $FB squeeze at Twitter to $54.20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:23:52 </td>
   <td style="text-align:left;"> FRESH!! SESSION!!! HIIIGGHHHSSS!!! 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:23:23 </td>
   <td style="text-align:left;"> $COIN Green trade here contracts went to 6.00+ $SPY $QQQ $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:23:10 </td>
   <td style="text-align:left;"> $QQQ such a WTF kind of day. Woof </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:23:07 </td>
   <td style="text-align:left;"> $qqq 🧠👀.  🐑👀.  🍿👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:22:47 </td>
   <td style="text-align:left;"> $QQQ buy TQQQ calls Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:22:47 </td>
   <td style="text-align:left;"> $QQQ $SPY 

 Yeah, after that bearish scene friday
Recovery was DUE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:22:19 </td>
   <td style="text-align:left;"> US stocks drop as China lockdowns spook already-wary investors

https://www.aljazeera.com/economy/2022/4/25/us-stocks-drop-as-china-lockdowns-spook-already-wary-investors

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:22:13 </td>
   <td style="text-align:left;"> $QQQ $SPY If it rallies from here into a next leg higher omg itll never stop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:22:09 </td>
   <td style="text-align:left;"> $QQQ $SPY

think they’ll let the markets drop like crazy?! by half or so?! to have foreign countries buy the dip? no siree bob… lolololooolol

plus, mm’s will fuck with options to make money and keep things afloat ☕️🐸🤫

LOL let’s see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:21:35 </td>
   <td style="text-align:left;"> $CETY been buying CETY $QQQ $OZSC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:21:16 </td>
   <td style="text-align:left;"> $QQQ $SPY  What&amp;#39;s with this up down up down movement today ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:21:11 </td>
   <td style="text-align:left;"> $QQQ and VXN to the moon I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:19:39 </td>
   <td style="text-align:left;"> $QQQ sell the rips 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:18:57 </td>
   <td style="text-align:left;"> $SPY $ETH.X $QQQ si señor 🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:18:16 </td>
   <td style="text-align:left;"> $QQQ some good strength into the close… $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:17:53 </td>
   <td style="text-align:left;"> $QQQ algos have gone bonkers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:16:43 </td>
   <td style="text-align:left;"> $QQQ Triple bottom on Fed panic? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:16:08 </td>
   <td style="text-align:left;"> What a time to be alive! $TWTR $TSLA $QQQ $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:15:09 </td>
   <td style="text-align:left;"> $QQQ if this thing closes hod jesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:14:54 </td>
   <td style="text-align:left;"> $SPXL $SPY $SPXL $QQQ No pain. No gain. This cycle has reversed, i believe. How high? No one knows. Thinking above 4400 is in cards. Glta </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:14:19 </td>
   <td style="text-align:left;"> $QQQ FED rate hikes, uncertainty in the market and big changes in tech are driving this lower this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:13:58 </td>
   <td style="text-align:left;"> Twitter Nearing Deal With Musk Sinks Trump-Linked SPAC $TWTR $DWAC Also $QQQ $TSLA https://talkmarkets.com/content/stocks--equities/twitter-nearing-deal-with-musk-sinks-trump-linked-spac?post=352633 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:13:26 </td>
   <td style="text-align:left;"> $QQQ $NQ_F Pink liquidity bar these bars mark the lows and right ahead of earnings/big tech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:13:20 </td>
   <td style="text-align:left;"> $TWTR $qqq $SPY $TSLA god bless Elon, fk all you left supporters 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:13:18 </td>
   <td style="text-align:left;"> $QQQ sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:11:42 </td>
   <td style="text-align:left;"> The Russia Ukraine War is Serious and it is not likely to end in with Russia War in Ukraine and it will likely spread to other countries…💡What Will NATO Do ?
The Baltic will be a target for Russia along with Moldova and even Poland Finland Sweden 
$AAPL $QQQ $AMD $SPY $CRM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:11:39 </td>
   <td style="text-align:left;"> $QQQ - I think bully’s got caught dumpster diving </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:11:24 </td>
   <td style="text-align:left;"> $QQQ very bullish week incoming. For all the dummies that shorted on friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:11:24 </td>
   <td style="text-align:left;"> $QQQ why would this dump in twitter news lol wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:10:50 </td>
   <td style="text-align:left;"> $DWAC  we played this what’s up. Went disgustingly green while Twitter halted. Our full. $SPY $QQQ $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:10:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA 

Same stuff everyday, sell off hour at its finest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:10:32 </td>
   <td style="text-align:left;"> $QQQ well, this pretty much proves algos are preset to buy and sell, no way everyone started selling exactly at 3 pm today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:10:30 </td>
   <td style="text-align:left;"> $TWTR $QQQ - I imagine the stock price will rally, and then the woke crowd will hit Musk by tanking the stock. Short term rally, long term decay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:09:58 </td>
   <td style="text-align:left;"> $QQQ $SPY sell the Twitter news, I prefer the opinions of those on SW…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:09:27 </td>
   <td style="text-align:left;"> $QQQ Musk buying $TWTR means the global elites can&amp;#39;t control the masses anymore. They are panicking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:09:27 </td>
   <td style="text-align:left;"> $QQQ $NFLX Long call options here, expect a 4-5 month rally n cool down sept-dec </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:09:18 </td>
   <td style="text-align:left;"> $QQQ this is how you know it’s algo zones and not necessary hard levels.   Vix new high of day by over $1  but no lower lows midday on QQQ  yet a lower low on VIX gave a higher high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:08:49 </td>
   <td style="text-align:left;"> $QQQ a sell off  because the clock hit 3:00 
 
LOL. Unbelievable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:08:39 </td>
   <td style="text-align:left;"> $QQQ $SPY daily artificial pump....15 min of joy for the cheer squad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:07:51 </td>
   <td style="text-align:left;"> $QQQ I give up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:07:49 </td>
   <td style="text-align:left;"> $QQQ $SPY. I am curious to the fighting that’s going to take place on Twitter but it’s virtual bloodshed.  Kinda like the Metaverse, just a buncha cyber bullies acting like they ain’t pussies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:07:08 </td>
   <td style="text-align:left;"> $TWTR $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:07:00 </td>
   <td style="text-align:left;"> $QQQ Elon buy twitter and market go down? What happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:06:59 </td>
   <td style="text-align:left;"> $TSLA Drop was cause of the $SPY and $QQQ i figure… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:06:59 </td>
   <td style="text-align:left;"> $QQQ massive selloff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:06:22 </td>
   <td style="text-align:left;"> $QQQ bull trap lol 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:06:13 </td>
   <td style="text-align:left;"> $TSLA  poor tesla elon gave his love for twitter $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:06:08 </td>
   <td style="text-align:left;"> ETF Sentiment: $QQQ is the #2 ETF that institutions are trading with 116.9K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:05:54 </td>
   <td style="text-align:left;"> $SPY $qqq real selling volume vs the fake pump volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:05:12 </td>
   <td style="text-align:left;"> $QQQ lost a full percent in 10 minutes for nothing lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:04:57 </td>
   <td style="text-align:left;"> $NQ_F $QQQ #NASDAQ #stockmarket #equities #Futures #Trading #marketforecast  
Today&amp;#39;s trading reports bias+1 bullish sent 4/25/22 8:35 AM 
$NQ DUT+5 $14,413 cash high $14,492.75 
Daily Notes: NQ Bullish all day, ES Weakness bought up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:04:39 </td>
   <td style="text-align:left;"> $SPY $QQQ any news or we just selling off hard as hell for fun? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:04:33 </td>
   <td style="text-align:left;"> $QQQ just straight raping option buyers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:04:16 </td>
   <td style="text-align:left;"> $QQQ 😂 the pump and dump continues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:04:12 </td>
   <td style="text-align:left;"> $QQQ wow wtf happened? News? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:04:08 </td>
   <td style="text-align:left;"> $QQQ no reason for this drop!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:03:50 </td>
   <td style="text-align:left;"> $QQQ wow this shit is falling off a cliff lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:03:38 </td>
   <td style="text-align:left;"> $NFLX $SPY $QQQ  Netflix going to bounce  &amp;#39;The pendulum has swung too far to the negative on streaming,&amp;#39; says Guggenheim&amp;#39;s Michael Morris https://www.cnbc.com/video/2022/04/22/the-pendulum-has-swung-too-far-to-the-negative-on-streaming-says-guggenheims-michael-morris.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-26 03:03:26 </td>
   <td style="text-align:left;"> $QQQ If i had to guess, markets will continue to rally into tomorrow, followed by a post-earnings selloff, and a retest of feb/march lows. I&amp;#39;d caution bulls from rushing into calls prematurely here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:43:09 </td>
   <td style="text-align:left;"> $AAPL pre earnings run up. Easy money 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:42:33 </td>
   <td style="text-align:left;"> $AAPL $165 open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:41:46 </td>
   <td style="text-align:left;"> $AAPL nice action before close , open lower and closed higher ,  hope it continues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:36:00 </td>
   <td style="text-align:left;"> $AAPL i said earlier green close glad it exceeded my guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:29:04 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:22:10 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/WfvkzZVV9cw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:21:02 </td>
   <td style="text-align:left;"> $AAPL View @ www.elliottwave-forecast.com along with other tech, is favoured to be moving lower.  However, it will not go in a straight line.  There will be counter trend bounces along the way.  The next leg lower is underway, 4H timeframes, we don’t like to sell it, but in shorter timeframes ,bounces should find resistance in 3, 7 or 11 swing while below the 171.53 peak.    #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:17:18 </td>
   <td style="text-align:left;"> $AAPL Bags to Riches Ep 11 / AMC Squeeze #AAPL Rip MULN FREQ ATER RBLX SPY Rip METX / Stock Market Analysis 
 
https://youtu.be/UXfhFMg2m44 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:04:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $GOOGL $NVDA 
Yellen says U.S. economy being &amp;#39;resilient&amp;#39;, no recession in sight

&amp;quot;I don&amp;#39;t expect a recession,&amp;quot; Yellen told CNBC.

https://www.reuters.com/business/finance/yellen-says-us-economy-being-resilient-no-recession-sight-2022-04-22/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 06:03:39 </td>
   <td style="text-align:left;"> $AAPL Green hammer off the 200 day - inverse head &amp;#39;n shoulders in play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:59:15 </td>
   <td style="text-align:left;"> $NFLX $AAPL $QQQ $SPY  Aapl should buy NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:59:14 </td>
   <td style="text-align:left;"> $AAPL stair stepping lower... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:58:32 </td>
   <td style="text-align:left;"> Updated ratings for Pra( $PRAA ), Apple( $AAPL ),… https://www.macroaxis.com/invest/stock-buy-or-sell?s=PRAA,AAPL,RHI,MUR,ALTR,GME,KEY,EFX,DOV,TRIP #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:58:20 </td>
   <td style="text-align:left;"> $AAPL 

Let’s see those earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:53:32 </td>
   <td style="text-align:left;"> $TWTR $TSLA $SPY $AAPL 
Literally 99% of the people on here. Broke worshiper lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:53:01 </td>
   <td style="text-align:left;"> $TWTR &amp;quot;Upon completion of the transaction, Twitter will become a privately held company. Under the terms of the agreement, Twitter stockholders will receive $54.20 in cash for each share of Twitter common stock that they own upon closing of the proposed transaction&amp;quot;. $SPY $TSLA $AAPL $FB https://www.sec.gov/Archives/edgar/data/1418091/000119312522117743/d319190ddefa14a.htm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:52:11 </td>
   <td style="text-align:left;"> $MSFT $AAPL $GOOGL $FB $AMZN https://youtu.be/QzrVx5kDhac </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:50:25 </td>
   <td style="text-align:left;"> $AAPL https://www.benzinga.com/trading-ideas/technicals/22/04/26791631/why-apple-stock-may-catch-bounce-into-q1-earnings-print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:50:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Equity of 139.79%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:47:13 </td>
   <td style="text-align:left;"> $AMD I still have my core from $44. I sold some for profit at 109 and 127. I bought extra for a swing trade at 88 on last Friday that I sold today at 90. With this incompetent president in place, unfortunately, I see everything taking a dramatic hit. My plan during Brandon&amp;#39;s uncontrolled inflation and economy ruin is, to try to play the swing game and hope to get lucky. As it stands now, am selling everything for a small profit at every pop, cuz am afraid, there will be more pain forthcoming while dementia Joe is at the helm. God help us all! 
$MSFT $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:45:28 </td>
   <td style="text-align:left;"> $AAPL if Apple sets a record quarter then we’re hitting ATH on Friday, then a sell off! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:44:48 </td>
   <td style="text-align:left;"> $AAPL higher or lower end of year people? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:44:34 </td>
   <td style="text-align:left;"> $AAPL $180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:41:04 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:40:39 </td>
   <td style="text-align:left;"> $AAPL need this to pump about 7 dollars tomorrow to load puts at that quad resistance on monthly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:40:21 </td>
   <td style="text-align:left;"> $AAPL nice action before close , open lower and closed higher ,  hope it continues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:33:41 </td>
   <td style="text-align:left;"> $QQQ $AAPL Apple never really &amp;quot;misses&amp;quot; on earnings, the worst they do is maybe just not knocking it out of the park </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:29:06 </td>
   <td style="text-align:left;"> $DWAC Anthem:  DEEEEE DUBBBBBBYA AAAAAAAAY CEEEEEEE, why nooooooo ANDROID APPPPPPP FORRRRRRRRRRRR MEEEEEEEEEE??? I thought we gaaaaaaaaaaaaaayvee you enough MONEEEEEEEEEEEEEEEEE, but your&amp;#39;re all $AAPL fanbois,  PAAAAAAAAARRENTLEEEEEE. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:28:06 </td>
   <td style="text-align:left;"> $AMZN Hard to bet against the giant 🤷🏾‍♂️.. I&amp;#39;m only bearish on the big dogs short term $MSFT latex7b2040027768b4e718f8d0efbe06a9eeFB 
 loses more users the crash will continue the following day. If  
$Aapl misses earnings, a market crash to $400 SPY will happen immediately and a correction to $340 will be the end result before we find out where we are going after that. I know it&amp;#39;s a tall order but just in case it happens that&amp;#39;s what will happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:27:21 </td>
   <td style="text-align:left;"> $AAPL Bags to Riches Ep 11 / AMC Squeeze BB #AAPL Rip MULN FREQ ATER RBLX SPY METX / Stock Market Analysis 
 
Lets go big wins 
https://youtu.be/UXfhFMg2m44 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:27:08 </td>
   <td style="text-align:left;"> $AAPL so how did this close green exactly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:23:16 </td>
   <td style="text-align:left;"> $AAPL hope you all were buying them this was bouncing off the 200day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:21:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Some FAANG names ‘are still high-growth internet companies,&amp;#39; portfolio manager says https://www.stck.pro/news/AAPL/26752280 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:17:09 </td>
   <td style="text-align:left;"> $AAPL $MSFT $SPY $QQQ I’ll leave you with this. So many have grown bearish which translates to we will see a pump. It’s seems as if no one learns their lesson. Rather than profit,  they simply want to be right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:17:02 </td>
   <td style="text-align:left;"> $SPY MASSIVE earnings coming which will set the course for the market the next few weeks or months.
 
If $MSFT  $GOOGL  can set the tone Tuesday with good quarters it can trigger a rally into $AAPL  $AMZN  on Thursday
 
If 3/4 of them can deliver on earnings... $SPY to 469 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:15:56 </td>
   <td style="text-align:left;"> $AAPL almost ready  to pickup more shares. You buy and hold this stock long term. Let’s go!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:15:50 </td>
   <td style="text-align:left;"> $SPY Would have rather seen it be a bit more bloody today since Pros wait for Tues to come back in. Have to think they Sell some of the pop tomorrow &amp;amp; wait for Earnings so,.. prepping for that 
 
$aapl $amzn $msft $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:15:33 </td>
   <td style="text-align:left;"> $TWTR Elon needs to take over $AAPL too 🕵️‍♂️✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:14:41 </td>
   <td style="text-align:left;"> $AAPL   who says I am surprised ... I knew this stock is drunk .. having so many wild up and down swings .. !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:11:39 </td>
   <td style="text-align:left;"> $AAPL Option to look at... 👀 👀  $150.00 Put for Friday, June 17, 2022. Roughly 481 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:09:53 </td>
   <td style="text-align:left;"> $AAPL - Apple Says App Store, Apple Music Issue Is Resolved </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:06:02 </td>
   <td style="text-align:left;"> $AAPL $MSFT $SPY $QQQ Nasdaq will get back to 14k. Dow 35k. It’s a simple game of back and forth! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 05:02:39 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-25 Chart Analysis Video: 
https://www.youtube.com/watch?v=3sXLM4YRJPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:59:22 </td>
   <td style="text-align:left;"> $CRM heading down 138.00 to 130.00 ‘s 
Aging Garbage 
$QQQ $SPY $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:55:35 </td>
   <td style="text-align:left;"> $TWTR $SPY $AAPL $DIS

Commies/Democrats/Lunatics/Chinese Bots -

Your hour of reckoning is upon us. 

Enjoy your long slow defeat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:54:28 </td>
   <td style="text-align:left;"> $AMZN  MM&amp;#39;s remembered about rates incres, $GOOG they forgot, $AAPL they forgot, $FB they are not worried JMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:53:36 </td>
   <td style="text-align:left;"> $AAPL 177+ 
 
https://www.thestreet.com/apple/other-products/apple-pre-earnings-the-mac-should-be-a-winner </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:50:26 </td>
   <td style="text-align:left;"> $AMD $MU $NVDA $MRVL $AAPL Hmmm, based on the &amp;quot;pin-action&amp;quot; today, are people holding their PUTS? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:48:58 </td>
   <td style="text-align:left;"> $AAPL https://www.cnbc.com/2022/04/25/jpmorgan-predicts-iphone-revenue-to-fall-short-when-apple-reports-later-this-week.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:47:08 </td>
   <td style="text-align:left;"> $AAPL 183 and 245 by Christmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:38:38 </td>
   <td style="text-align:left;"> How the largest stocks performed today 
 
Apple $AAPL +0.7% 
Microsoft $MSFT +2.4% 
Google $GOOGL +2.9% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:36:18 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 320.2K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:31:28 </td>
   <td style="text-align:left;"> $AAPL $MSFT get ready for tomorrows  crazy option premium manipulation. Remember, momentum is what shoots the price in either direction on OTM options. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:29:40 </td>
   <td style="text-align:left;"> $AAPL $167 tomorrow during normal trading hours. Then we may see $170 in AH if Microsoft kills it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:27:29 </td>
   <td style="text-align:left;"> $SPY the markets have been controlled by option buying causing the VIX volatility. You need to remember, this selling pressure is caused by option buying and not by LT selling of the underlying stock. We are ending four months of declining stock valuation. It’s unsettling, yes! Political and global news have fueled out buying. HOWEVER, if you own a great stock, you need to ride this out. In my opinion option trading should be banned in the US AS IT IS IN OTHER COUNTRIES. You should not be a seller of any great company… especially ones that drive our day to day human behavior like $AAPL, $MSFT and $GOOGL. A LT investor will always win the race. GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:26:52 </td>
   <td style="text-align:left;"> $V $MA been hammered for a over a year, will break support and hit new highs eoy! $AAPL $WEN $SBUX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:24:40 </td>
   <td style="text-align:left;"> $AAPL The power of JESUS is going to push to to 190 by eow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:18:09 </td>
   <td style="text-align:left;"> $AAPL fucking shorts get ready to squeeze ashes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:12:17 </td>
   <td style="text-align:left;"> $AAPL $SPY $DIS  when the bottom falls out who will be surprised </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:12:15 </td>
   <td style="text-align:left;"> $SPY Classic wealth transfer. Elites control the media, media scares the public into selling....smart money loads up knowing $AAPL and $MSFT gonna rip us to ATH📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:07:53 </td>
   <td style="text-align:left;"> $AAPL calls bought this morning looking good so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:06:49 </td>
   <td style="text-align:left;"> $AAPL I say bullish up til ER .. then tanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:06:48 </td>
   <td style="text-align:left;"> $AAPL wtf with these candles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:06:09 </td>
   <td style="text-align:left;"> $SPY in for $AAPL ER on Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:06:02 </td>
   <td style="text-align:left;"> $AAPL bullish divergence 1hr chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:05:57 </td>
   <td style="text-align:left;"> $AAPL I like when Tesla runs made money on it I just dislike apple because they pump the stock so many times and then they dump it look at the chart and intraday trading seen it going 4 dollars up and then back down to where it started all stock can be amazing but apple doesn’t deserve it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:05:23 </td>
   <td style="text-align:left;"> $MSFT $SPY $AAPL $AMZN “stocks trading higher after early day weakness” 
Super analysis Wall Street 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:05:18 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:04:57 </td>
   <td style="text-align:left;"> $AAPL can still see $154.87- $150.93 area lower but chasing the weakness looks risky in #Apple #Elliottwave #Trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:04:02 </td>
   <td style="text-align:left;"> $AAPL I wanted in at 154 but said F it… I took 162 it should run to 174 quick with earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:03:05 </td>
   <td style="text-align:left;"> $AAPL $167 tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:02:57 </td>
   <td style="text-align:left;"> $AAPL KEEP THE BORDER OPEN JOE…😅😅…SEE YA 😂👋👋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:02:46 </td>
   <td style="text-align:left;"> @QuiverQuant On 2022-03-23 Congress Member Ron Wyden disclosed a Purchase of $AAPL. Follow our Congressional Long-Short strategy to see how other members of congress might be trading $AAPL; https://www.quiverquant.com/strategies?ref=stocktwits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:02:08 </td>
   <td style="text-align:left;"> $AAPL AAPL continues to run up in AH...163.53 on the open for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:01:53 </td>
   <td style="text-align:left;"> $AAPL puts before earnings. Will wait patiently </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:01:08 </td>
   <td style="text-align:left;"> $AAPL closed over 163...AAPL going over 168++ into earnings...175+ post earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 04:00:27 </td>
   <td style="text-align:left;"> @QuiverQuant On 2022-03-23 Congress Member Ron Wyden disclosed a Sale of $AAPL. Follow our Congressional Long-Short strategy to see how other members of congress might be trading $AAPL; https://www.quiverquant.com/strategies?ref=stocktwits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:59:52 </td>
   <td style="text-align:left;"> $SPY secured $aapl $175c too today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:59:22 </td>
   <td style="text-align:left;"> $AAPL higher 🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:58:42 </td>
   <td style="text-align:left;"> $AAPL the MM’s played it smart. Tech rally all week! ✌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:58:38 </td>
   <td style="text-align:left;"> $AAPL $177+ 
 
https://seekingalpha.com/article/4503295-apple-stock-technical-momentum-earnings-wont-disappoint </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:58:26 </td>
   <td style="text-align:left;"> $AAPL gorgeous reversal upon touching da 50WMA where tutes supports price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:57:42 </td>
   <td style="text-align:left;"> $AAPL let’s go!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:56:12 </td>
   <td style="text-align:left;"> $AMD ↗️📈

$AAPL $BTC.x ETH.x $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:55:38 </td>
   <td style="text-align:left;"> $SPY $AAPL please stop me from starting a put position again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:55:21 </td>
   <td style="text-align:left;"> $AAPL volatility at its best! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:53:59 </td>
   <td style="text-align:left;"> $AAPL strong finish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:52:53 </td>
   <td style="text-align:left;"> $AAPL let’s run it fast to $164 before bell🤑🤑🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:52:49 </td>
   <td style="text-align:left;"> $AAPL here comes the 163+ push!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:49:00 </td>
   <td style="text-align:left;"> The industry average ROE is 17.76%. $AAPL outperforms 94% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:46:39 </td>
   <td style="text-align:left;"> $AAPL small time profit takers will get run out into the close 163+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:44:27 </td>
   <td style="text-align:left;"> $AAPL AAPL is the only safe play in tech in a volatile market. ETF and funds will continue to overweight AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:43:21 </td>
   <td style="text-align:left;"> $AAPL LETS GET READY TO RUMBLE!!!!...See you at 175+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:43:09 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : National Securities&amp;#39; Art Hogan likes Apple but not all of tech https://www.stck.pro/news/AAPL/26748042 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:42:33 </td>
   <td style="text-align:left;"> $AAPL AAPL just getting started in breakout to all time high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:42:10 </td>
   <td style="text-align:left;"> $AAPL dance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:41:12 </td>
   <td style="text-align:left;"> $AAPL it’s Apple. Don’t be dumb. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:40:45 </td>
   <td style="text-align:left;"> $AAPL  Shorts cover, $183+ on Friday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:40:27 </td>
   <td style="text-align:left;"> $AAPL will continue to run and close at HOD 163+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:40:01 </td>
   <td style="text-align:left;"> $AAPL $AMC $SPY $QQQ the rule still stands. Dow down 1000 and you will see a Green Day the following day! 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:39:32 </td>
   <td style="text-align:left;"> $AAPL AAPL is last solid place in tech to put money. Inflows will continue and dividend increase and buybacks are announced. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:39:31 </td>
   <td style="text-align:left;"> $AAPL  $164 it 🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:39:17 </td>
   <td style="text-align:left;"> $SPY my money going from brokerage to bank account lol. Not buying this pump lol 😂 $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:37:45 </td>
   <td style="text-align:left;"> $AAPL Impressive recovery today. I thought it was done for sure this morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:36:55 </td>
   <td style="text-align:left;"> $AAPL 👁❤️🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:35:50 </td>
   <td style="text-align:left;"> $AAPL over $163 today I bet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:34:50 </td>
   <td style="text-align:left;"> $AAPL last chance to buy below 160...😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:34:11 </td>
   <td style="text-align:left;"> $AAPL 170 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:33:18 </td>
   <td style="text-align:left;"> $AAPL over $164 by eod 🤞🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:33:15 </td>
   <td style="text-align:left;"> $AAPL this ponzi will collapse soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:32:51 </td>
   <td style="text-align:left;"> $AAPL get them on pay roll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:32:21 </td>
   <td style="text-align:left;"> $AAPL load up the truck...AAPL going back to 170+. Shorts are going to get body slammed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:31:35 </td>
   <td style="text-align:left;"> $AAPL let’s do $164🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:30:52 </td>
   <td style="text-align:left;"> $AAPL any news or just random dudes pumping millions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:29:25 </td>
   <td style="text-align:left;"> $AAPL jeez the money per second here ridiculous amount for this pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:29:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL $DIA 

 Setting up outside reversal of the Thursday outside reversal which typically happens on average 10days apart. Last time took a little longer at 15 trading days so if this one is quicker than average… data since 1990 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:28:37 </td>
   <td style="text-align:left;"> $AAPL the MM’s are keeping it flat till AH. Should see some solid volatility to the upside on calls tomorrow! Especially OTM! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:28:35 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA Man, Michael Burry is the most funny character in Wallstreet. 
 
He&amp;#39;s all acting cryptic, coming to twitter saying stuff like &amp;quot;I warned you guys....&amp;quot;   &amp;quot;At least I tried&amp;quot;.....  &amp;quot;Biggest crash in history coming&amp;quot; 
 
And then literally the next day you get a huge green rally and he deletes his Twitter again. 
 
The dude is a meme at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:28:26 </td>
   <td style="text-align:left;"> $SPY we got 4 trading days before sell in May and go away lol. And this year we got fed raise interest rate by 50 basis points and huge balance sheet debt reduction. Who wants to hold through May lol ? 😂 $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:27:40 </td>
   <td style="text-align:left;"> $AAPL should just buy $Nflx for $340.. the price before this most recent drop.  They need the subscribers and content and this is a drop in the bucket for them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:26:57 </td>
   <td style="text-align:left;"> $AAPL This market is more fun day trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:26:48 </td>
   <td style="text-align:left;"> $AAPL Haha 😂 when it goes Red all bears come out with dooms day thesis and green we see Bulls come out with optimism. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:25:34 </td>
   <td style="text-align:left;"> $AAPL  $163 incoming 🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:25:29 </td>
   <td style="text-align:left;"> $AAPL huge AH pop! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:24:50 </td>
   <td style="text-align:left;"> $AAPL Easy money is easy money, crazy WS or not lol $$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:24:02 </td>
   <td style="text-align:left;"> $AAPL officially retracing back up to 180 range. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:23:40 </td>
   <td style="text-align:left;"> $AAPL 🚀🚀 more upside !!! It hasn’t even started. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:23:19 </td>
   <td style="text-align:left;"> $AAPL back to your regularly scheduled programming - 170+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:22:21 </td>
   <td style="text-align:left;"> $AAPL any buys under $170 will look like a great deal after this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:20:21 </td>
   <td style="text-align:left;"> $AAPL MM’s are really screwing around here. It’s set up for the pop. I’ve seen this too many times! ✌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:19:28 </td>
   <td style="text-align:left;"> Some top tech sector flow coming in above ask today 
 
$GOOGL - $2.4M call sweep 
$AAPL - $632K call sweep 
$PYPL - $461K call sweep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:17:01 </td>
   <td style="text-align:left;"> $AAPL $170+ this week!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:16:25 </td>
   <td style="text-align:left;"> $SPY any one ready for real selling into the close lol? 😂 $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:15:36 </td>
   <td style="text-align:left;"> $AAPL if it doesn’t close green, we may see a nice jump in AH. Either way, I think we see a $3-4 jump tomorrow. I Will sell my calls tomorrow after the pop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:14:13 </td>
   <td style="text-align:left;"> $AAPL who&amp;#39;s betting against it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:13:42 </td>
   <td style="text-align:left;"> $TSLA $NVDA $AMD $AAPL $GOOGL 

🚀💎🚀 Bring That Volatility 🚀💎🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:12:53 </td>
   <td style="text-align:left;"> $SNAP I&amp;#39;m bullish but I&amp;#39;m not buying until I see some of these earnings come through this week.  $ GOOG $FB $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:11:42 </td>
   <td style="text-align:left;"> The Russia Ukraine War is Serious and it is not likely to end in with Russia War in Ukraine and it will likely spread to other countries…💡What Will NATO Do ?
The Baltic will be a target for Russia along with Moldova and even Poland Finland Sweden 
$AAPL $QQQ $AMD $SPY $CRM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:09:43 </td>
   <td style="text-align:left;"> $AAPL 

Bitch won’t stay green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:08:18 </td>
   <td style="text-align:left;"> $AAPL 177+ EOW 
 
Twitter Software built atop iOS so valuable, worth buying for $44B and going private. 
 
Game on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:03:05 </td>
   <td style="text-align:left;"> Twitter $TWTR accepts Elon Musk&amp;#39;s buyout deal 
&amp;gt;https://www.cnbc.com/2022/04/25/twitter-accepts-elon-musks-buyout-deal.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard
$AAPL $AMD ↗️📈 $GOOGL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:01:49 </td>
   <td style="text-align:left;"> $SPY they are waiting for the big dogs to report $NVDA $MSFT $GOOG $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 03:00:22 </td>
   <td style="text-align:left;"> latex7e1bc9346d70a90a4fd7e47a7d0d872eBTC.X  
       40,135.76 📈   42,239.89 PM  
$SPY 
       425.41 📉   421.08 PM 
  
MLB BETS⚾  
SF Giants Vs Brewers         SF Money line +166  
Dodgers: Gavin Lux             2+ hits  +300  
  
NBA BETS🏀  
Parlay  
Mavs &amp;amp; Raptors Moneyline +540  
  
LIVE BET⏰  
CELTIC VS NETS 7PM: ONLY ON STOCKTWITS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:58:21 </td>
   <td style="text-align:left;"> $AAPL Option to look at... 👀 👀  $150.00 Put for Friday, June 17, 2022. Roughly 481 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:57:59 </td>
   <td style="text-align:left;"> $AAPL Deadcat bounce! Will be back down with China lockdown and fed hikes ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:56:57 </td>
   <td style="text-align:left;"> $QQQ $AAPL $CRWD $HOOD $TWTR Everything FKING MOONS this week! We bled through the last 3 1/2 days. Now we take back the power and go to the GOD DAMN MOON!!! LFG!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:55:01 </td>
   <td style="text-align:left;"> $AAPL apple the only stock that is pumped randomly and for no reason if it was one at least </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:54:57 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY TWITTER is boosting the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:54:06 </td>
   <td style="text-align:left;"> $AAPL Pump it up WS $$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:53:12 </td>
   <td style="text-align:left;"> $AAPL  latex91d530233c7970b38592de470b2aa809TWTR 1.060m (67% call/33% put)
$AAPL 660k (43% call/57% put)
$TSLA 508k (53% call/47% put)
$NVDA 318k (56% call/44% put)

For More Info : https://bit.ly/sweepcastoptions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:52:17 </td>
   <td style="text-align:left;"> $TSLA $TWTR $AAPL $AMD $NVDA 

💰Welcome to Twitter Elon Musk 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:52:15 </td>
   <td style="text-align:left;"> $MSFT $GOOG $AAPL hunting for bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:52:01 </td>
   <td style="text-align:left;"> $SPY looks like $AAPL finally woke up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:51:36 </td>
   <td style="text-align:left;"> $NVEI $AAPL Novibet Extends Global Partnership With Nuvei 

https://newsfilter.io/a/bf64c6406169bf8fb8b192fd9d8b812d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:50:27 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $GOOGL $NVDA 
👇 Bears now in denial mode 😙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:49:59 </td>
   <td style="text-align:left;"> $TSLA $AMD $NVDA $AAPL $GOOGL 

🚀📈🚀 Halt it for the Run-up 🚀📈🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:49:39 </td>
   <td style="text-align:left;"> $AAPL bullshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:49:37 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:49:30 </td>
   <td style="text-align:left;"> $SPY .... Correlation of support on trendline and strength From previous reversals.....$UVXY $AAPL $TSLA $ARKK  I can definitely be bearish on this market but Follow the chart💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:49:06 </td>
   <td style="text-align:left;"> $SPY $MSFT $AAPL $GOOGL $NVDA 
Microsoft expects Intelligent Cloud revenues (Azure falls under the segment) between $18.75 billion and $19 billion. Azure’s revenue growth is likely to reflect continued strength in consumption-based services.

The Zacks Consensus Estimate for the Intelligent Cloud segment revenues is currently pegged at $18.82 billion, indicating growth of 24.9% from the figure reported in the year-ago quarter.

https://finance.yahoo.com/news/strength-azure-cloud-aid-microsofts-155303338.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:47:21 </td>
   <td style="text-align:left;"> $SPY 

Bruh, SPY is just an $AAPL ETF.  The weighting is so fucked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:46:19 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $GOOGL $SOXL
When Apple beats, market moves up.

TSMC&amp;#39;s Chip Revenue From Apple Predicted to Grow Nearly 25% in 2022 as Apple Silicon Transition Nears Completion

https://www.macrumors.com/2022/04/25/tsmc-revenue-from-apple-predicted-to-grow-in-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:45:43 </td>
   <td style="text-align:left;"> $AAPL broke or rich by halloween whatre you gonna do you fucking market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:45:31 </td>
   <td style="text-align:left;"> $AAPL power hour coming soon 🔝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:43:04 </td>
   <td style="text-align:left;"> Updated correlation matrix for Apple( $AAPL ),… https://www.macroaxis.com/invest/stock-correlation?s=AAPL,FCX,INTU,HST,DNB,ESGR,AN,AIV,SWK,PM,BLL,EMN #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:42:57 </td>
   <td style="text-align:left;"> $AAPL should take off UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:42:56 </td>
   <td style="text-align:left;"> $DIS $AAPL $AMZN How to tell if it’s a breakout or not..

https://youtu.be/TKi5sttvQkY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:42:03 </td>
   <td style="text-align:left;"> $SPY look like another big selling into close lol 😂 $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:41:44 </td>
   <td style="text-align:left;"> $SPY $QQQ  
All week ping-pong 420-425 til $AAPL reports earnings? 
 
(Then market tanks even if they beat) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:41:35 </td>
   <td style="text-align:left;"> $NVDA $AMD $AAPL $TSLA $GOOGL 
💎💎💎💎💎💎💎💎💎💎💎💎💎💎💎

🚀🚀🚀🚀🚀 T A K E    O F F 🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:39:47 </td>
   <td style="text-align:left;"> $SPY Ahh CNBC Steve Weiss, remember what I said on Friday? 
That trade worked out well as it always does. 
 
He&amp;#39;s close to being as bad as Cramer 
 
$aapl $baba $Msft $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:38:01 </td>
   <td style="text-align:left;"> $AAPL 

🚀📈🚀 Takeoff Monday 🚀📈🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:37:46 </td>
   <td style="text-align:left;"> $FB $AAPL we stabilize now better load up bulls before we take off higher and higher .. and bears lock your gains in $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:37:10 </td>
   <td style="text-align:left;"> $SPY institutions love these bounces give them another chance to unload to retails lol 😂 $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:37:02 </td>
   <td style="text-align:left;"> $AAPL AirPods huge 
 
https://www.youtube.com/shorts/sfvaXm5uKk0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:35:59 </td>
   <td style="text-align:left;"> $AAPL here comes $162🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:33:42 </td>
   <td style="text-align:left;"> $AAPL bought this morning dip near 200 dma 🤞🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:32:24 </td>
   <td style="text-align:left;"> $SPY there is no juice for market to go higher lol. Only bounce and they are selling opportunities lol 😂 $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:32:11 </td>
   <td style="text-align:left;"> $AAPL Sold some May 6 puts few hours ago, strike 145, around .16 delta, i think i will be &amp;quot;ok&amp;quot;, if not, i see this as a bargain, hehe (still have PTSD from paypal) LOL 🍺 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:31:30 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Why Apple Stock Is Falling Today https://www.stck.pro/news/AAPL/26744934 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:31:09 </td>
   <td style="text-align:left;"> $AAPL looks like earning doing its magic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:30:49 </td>
   <td style="text-align:left;"> $POET News and financials this week. Train is leaving. $AAPL  are you our customer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:30:41 </td>
   <td style="text-align:left;"> $AAPL selling all pops </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:30:16 </td>
   <td style="text-align:left;"> $AAPL let’s run it up🚀🚀🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:30:08 </td>
   <td style="text-align:left;"> $AAPL don&amp;#39;t forget... 
 
https://www.youtube.com/watch?v=yKIfi-47RIY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:25:30 </td>
   <td style="text-align:left;"> $AAPL 177+  BULLISH data 
 
https://www.bing.com/news/search?q=airpod+revenue&amp;amp;FORM=HDRSC6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:24:37 </td>
   <td style="text-align:left;"> $AAPL very bullish, perhaps Q2 much stronger than some think... 
 
https://www.itnews.com.au/news/tsmc-sees-q2-sales-surge-578896 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:23:49 </td>
   <td style="text-align:left;"> $AAPL don&amp;#39;t forget; 
 
&amp;#39;Apple Airpods Revenue More than NVIDIA’s Total Revenue and 2x More than AMD’s Revenue&amp;#39; 
 
https://www.hardwaretimes.com/apple-airpods-revenue-more-than-nvidias-total-revenue-and-2x-more-than-amds-revenue/#:~:text=Apple%E2%80%99s%20Airpods%20bring%20in%20around%20%2412%20billion%20a,twice%20as%20much%20as%20AMD%E2%80%99s%20revenue%20for%202020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:23:06 </td>
   <td style="text-align:left;"> $AAPL | Winia Aid IPO Preview

&amp;quot;Winia Aid is getting ready to complete its IPO in June. t has three main businesses including distribution, logistics, and services. The IPO price range is from 14,200 won to 16,200 won.&amp;quot; - Douglas Kim

Key Points:
* Winia Aid is getting ready to complete its IPO in June. According to the bankers&amp;#39; valuation, market cap after the IPO is from 219 billion won to 249 billion won.
* It has three main businesses including distribution, logistics, and services. Distribution and logistics are for Winia and other global products. Service is mainly for Apple&amp;#39;s authorized service provider in Korea. 
* The company has a solid growth in sales and profits. From 2018 to 2021, the company&amp;#39;s revenue and operating profit increased by 39.2% and 86.2% CAGR, respectively. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:22:43 </td>
   <td style="text-align:left;"> $AAPL  $162 incoming 🚀🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:22:40 </td>
   <td style="text-align:left;"> $AAPL it may drop on earnings 90% chances. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:22:05 </td>
   <td style="text-align:left;"> $SPY $AAPL its time 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:21:37 </td>
   <td style="text-align:left;"> $AAPL every dip $$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:19:49 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-25 Chart Analysis Video: 
https://www.youtube.com/watch?v=3sXLM4YRJPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:19:38 </td>
   <td style="text-align:left;"> $AAPL 

Problems in China are next Qtr and Apple sandbags and has 11 weeks of inventory to catch up and plenty left.

Hopefully close to green at close.

Problem is Cook and especially Luca are doom and gloom on forecasts they always beat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:19:03 </td>
   <td style="text-align:left;"> $GGPI $AAPL Birdie told me to listen to Apple Earnings call this week. Announcement of partnership?? Or maybe they will just mention the inclusion of Apple CarPlay into Polestar. Hmmmm… how to play?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:18:20 </td>
   <td style="text-align:left;"> $QQQ $AAPL Wanna see all the people who&amp;#39;ve bet against Apple? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:17:45 </td>
   <td style="text-align:left;"> $SPY Lets see if we can flip some things on the Pop since the MOC Orders should have some Sellers, could set up a Dip Buying opp in a few things 
 
$aapl $dis $bb $jpm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:16:14 </td>
   <td style="text-align:left;"> Narrative changing again for us sh33p.

JPM calls rally now $aapl $SPY $SPX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:15:43 </td>
   <td style="text-align:left;"> $AAPL Be careful with earnings this week, Apple has investors worried with the factory shutdowns and their product refresh cycle coming out this year. Short term Apple may fall possible below $150. They are simply an expensive company right now with their P/E ratio sitting at 27.55. They are a great company but needs some cooling before another massive run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:15:23 </td>
   <td style="text-align:left;"> $AAPL 29-Apr-22 150 Puts Traded 9,966 Times for $1.8 Million in Premium. https://tinyurl.com/y2sbmukd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:14:50 </td>
   <td style="text-align:left;"> $AAPL back to 200ma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:14:24 </td>
   <td style="text-align:left;"> $AAPL EMA 200 daily. 50 weekly and 10 on the monthly. Think Im gonna buy some </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:14:11 </td>
   <td style="text-align:left;"> $SPY Short term bullish to end the day. $QQQ $AAPL $TSLA Tomorrow is a diff story. 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:11:52 </td>
   <td style="text-align:left;"> $AAPL amazing fight Apple 🍎  S&amp;amp;P 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:11:50 </td>
   <td style="text-align:left;"> ✅(2-0) so far this week on signals❌
(CLOSED TODAY) 
🟢 $AAPL PUTS 38% (RISKY) 
🟢 $AMD PUTS 30% (DT) 
(4/25/22 RECAP) 
$SPY Pretty good day with this market volatility. Makes entires and exits particularly difficult. In times like this shifting time frames is really important when intraday trading. Not seeing too much I like for eod so ending the day on a high note. See you all tomorrow. Let’s keep weathering the storm! $TWTR $QQQ

Join us today with the link below! 

https://discord.com/invite/aEvNt6mvyU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:11:36 </td>
   <td style="text-align:left;"> $AAPL fighting hard to hold 160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:09:12 </td>
   <td style="text-align:left;"> $QQQ $AAPL Graveyard is full of bears. Gentle reminder... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:07:51 </td>
   <td style="text-align:left;"> Strong $GOOG bounce back, expecting $AAPL to do the same once we get past earnings. $TSLA still looking frothy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:07:25 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #3 stock that institutions are trading with 17.6K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:02:58 </td>
   <td style="text-align:left;"> $AAPL $ARKK now you know there is something wrong in the world when ARKK is up!  Haha! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 02:02:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL 

silly bulls don’t understand that bears always win in bear markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:59:16 </td>
   <td style="text-align:left;"> $AAPL what is the target price to buy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:55:55 </td>
   <td style="text-align:left;"> $AAPL Big Rome Powell gonna send this to the dirt on Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:55:50 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:52:00 </td>
   <td style="text-align:left;"> $AMD $TSLA $NVDA $AAPL We have the highest inflation, house crises, sky rocketing gas prices and an economy down the toilet. Now we are sending 2 billion per month to Ukraine? Don&amp;#39;t get me wrong, and I do sympathize with the Ukrainians, but what this administration is doing is more aligned to meet their personal agenda vs what is best for americans.  This incompetent president is more concerned about Ukraine than America. If he had spent the fraction of time he spent on Ukraine and Putin, on our economy, we wouldn&amp;#39;t be where we are now. The sad part is, it appears that things will get worse for us, and this idiot will continue putting the blame on &amp;quot;Putin&amp;#39;s price hike&amp;quot;. I’m beginning to ask myself…does Ukraine has something on Biden? B/c this is beginning to look a lot like extortion. 
 
Let&amp;#39;s go Brandon! 
 
https://www.msn.com/en-us/news/politics/ukraine-asks-u-s-for-2-billion-per-month-in-emergency-economic-aid/ar-AAWyhS7?ocid=msedgntp&amp;amp;cvid=70652f2954ae41698a65f45650eb4540 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:49:19 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Reports After The Close On 4/28 -- Options Contracts Expire The Next Day https://www.stck.pro/news/AAPL/26742782 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:49:02 </td>
   <td style="text-align:left;"> $AAPL 200 coming back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:48:20 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;d say this really benefitted from the pandemic and money printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:48:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:43:17 </td>
   <td style="text-align:left;"> $AAPL ok guys…. After a great day of scalping this bitch time to watch this go higher! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:40:13 </td>
   <td style="text-align:left;"> latex66fc0ebf1a993733a092b9a220364fa2NIO has a third party (JAC) manufacturing for them, 
$AAPL uses the same company (Foxconn). 
 
with you lose all your money here, $RIDE to $30 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:39:59 </td>
   <td style="text-align:left;"> Anyone interested in joining a group in discord (trying to make a group of 5-15 people) just to bounce trading ideas off eachother. NOT TRYING TO BE A BIG GROUP. FOLLOW AND DM ME 
 
$TWTR $AMC $NFLX $CCXI $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:36:11 </td>
   <td style="text-align:left;"> Apple Watch to Potentially Gain Satellite Connectivity This Year or 2023 
 
$AAPL 
 
https://wccftech.com/apple-watch-to-potentially-gain-satellite-connectivity-this-year-or-2023/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:35:32 </td>
   <td style="text-align:left;"> $AAPL this price action is legit insane…2+ trillion dollar company up n down, up n down…quite obviously being algo abused, lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:35:05 </td>
   <td style="text-align:left;"> $AAPL Boom! 
 
https://appleinsider.com/articles/22/04/25/now-apple-watch-may-get-satellite-communications-not-just-iphone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:34:43 </td>
   <td style="text-align:left;"> $AAPL (Apple Inc.) 
 
Finding nice support at the 200 day moving average. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:33:32 </td>
   <td style="text-align:left;"> $AAPL new uses 
 
https://www.macrumors.com/2022/04/25/apple-poached-video-shot-on-iphone-13-pro/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:32:38 </td>
   <td style="text-align:left;"> NASDAQ H&amp;amp;S Weekly Forming Possibly BigDrops $QQQ $AAPL $CRM $SPY $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:28:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $XOM $SJT current 10% yield dividend and expected to double to 20%+ yield. Must read. San Juan Trust: A Rare, Pure-Play Natural Gas Trust Owned By Retail And Not Followed By Wall Street https://seekingalpha.com/article/4478362-san-juan-trust-sjt-natural-gas-trust-income-capital-gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:27:36 </td>
   <td style="text-align:left;"> $AAPL  Are we in for a long consolidation/ distribution phase for Apple?  Chart is pointing towards that conclusion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:26:44 </td>
   <td style="text-align:left;"> $AAPL ready for that earnings run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:25:32 </td>
   <td style="text-align:left;"> $AMC 5x your money with my call outs 🙏😇👍❤️🚀🌞💯💵 $GME $AAPL $GOOG $TWTR https://youtu.be/n7ovzGgjBus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:25:26 </td>
   <td style="text-align:left;"> $AAPL all timeframes looking explody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:23:40 </td>
   <td style="text-align:left;"> $AAPL 177+ EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:23:37 </td>
   <td style="text-align:left;"> latex518c1d0ba0be08fc97c433bd8ecf3f06 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:11:49 </td>
   <td style="text-align:left;"> * Musk, Twitter Deal to Be Valued at latexd9a535f14bdc7aa0c1eb30f2c6e0c38fTWTR

$AAPL $AMD $GOOGL latexcf3bcb5a040014d24993e29208cddbf0AAPL : Beat
$AMZN : ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:10:10 </td>
   <td style="text-align:left;"> $AAPL green colour has been removed from the stock market. All my portfolio is red now. See you after the recession. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:10:04 </td>
   <td style="text-align:left;"> $AAPL thank you democrats you are truly the saviors of America. Cry more trumptards! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:09:03 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Why Apple Stock May Catch Bounce Into Q2 Earnings Print https://www.stck.pro/news/AAPL/26741835 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:08:58 </td>
   <td style="text-align:left;"> $AAPL   Build a  position if you arent already in the stock. Apple doesnt fail Earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:07:23 </td>
   <td style="text-align:left;"> $AAPL You elected this corrupt assh0le what did you expect would happen to your investments and 401k’s?  Half of the morons in his admin have never worked a day in their lives. They don’t understand the value of money or basic economics. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:07:00 </td>
   <td style="text-align:left;"> $MSFT $googl 26th $fb 27th $aapl $amzn 28th will surprise 🐻🐻🐻🐻🐻🐻 with huge revenue 🚀🚀🚀🚀🚀 nasdaq 500-700 points move by Friday ?? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:06:59 </td>
   <td style="text-align:left;"> $AAPL 135 for this Chinese company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:06:33 </td>
   <td style="text-align:left;"> $AAPL great time to accumulate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:05:41 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA BTFD?! 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:05:01 </td>
   <td style="text-align:left;"> $SPY i expect all earnings good $AAPL and $AMZN worries me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:04:50 </td>
   <td style="text-align:left;"> $AAPL at 2.6 TRILLION market cap could buy $NFLX at $300 billion (currently 95 billion) and still make good on EPS.    That will be instantaneous 221 subscribers added to Apple TV.  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:02:46 </td>
   <td style="text-align:left;"> $NFLX This going lower and lower increases the chance of $AMZN or $GOOG acquiring Netflix higher and higher.   Try creating the same Netflix content library at today&amp;#39;s inflated production costs.   Netflix is a bargain to someone trying to take the lead.  Maybe $AAPL?  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:02:24 </td>
   <td style="text-align:left;"> $AABB $AAPL $MSFT $GOOGL $TSLA https://investorshub.advfn.com/boards/read_msg.aspx?message_id=168648706 X50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 01:02:06 </td>
   <td style="text-align:left;"> $QQQ $GOOGL $AAPL Here come the Biden short sellers to knock tech stocks down a few more pegs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:58:40 </td>
   <td style="text-align:left;"> Why Apple Stock May Catch Bounce Into Q2 Earnings Print $AAPL https://www.benzinga.com/trading-ideas/technicals/22/04/26791631/why-apple-stock-may-catch-bounce-into-q1-earnings-print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:55:46 </td>
   <td style="text-align:left;"> $AAPL Here&amp;#39;s some data from previous rate hike cycles https://youtu.be/ePBe3zNy50A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:55:04 </td>
   <td style="text-align:left;"> $AAPL welp going balls deep on a play here. might be broke by october </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:51:18 </td>
   <td style="text-align:left;"> $AAPL over VWAP. Let’s close the gap. Held pretty damn good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:51:06 </td>
   <td style="text-align:left;"> $AAPL nice rips $$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:49:16 </td>
   <td style="text-align:left;"> $TWTR $DWAC $SPY $GOOGL $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:48:53 </td>
   <td style="text-align:left;"> $AAPL can apple even release its iphones on time this year given that they are manufacturered in China?
There&amp;#39;s so many China risks involved here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:46:26 </td>
   <td style="text-align:left;"> $AAPL Dividend increase on the way at earnings announcement...has been will continue to be a compounder for years and years 💰💰🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:46:07 </td>
   <td style="text-align:left;"> Take a Bite of Apple Stock Before This Week’s Earnings Event -- article I wrote for @investorplace https://investorplace.com/2022/04/take-a-bite-of-aapl-stock-before-this-weeks-earnings-event/ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:44:43 </td>
   <td style="text-align:left;"> $AAPL say goodbye to 30% revenue in China. Ain’t nobody going to spend money on toys when they can’t afford to buy food lol 😂 $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:44:37 </td>
   <td style="text-align:left;"> $AAPL watching call entry!! 🤤🤤🤤👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:44:16 </td>
   <td style="text-align:left;"> $AAPL this could lose a trillion in market cap and still be double pre Covid when nothing has really changed since then…long way down to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:42:40 </td>
   <td style="text-align:left;"> $NFLX doubled my position. Hey $AAPL what u are waiting for ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:40:44 </td>
   <td style="text-align:left;"> $AAPL 3rd+  200d test in last two months with lower lows each time.... Yeah, no. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:39:59 </td>
   <td style="text-align:left;"> $AAPL I got some news guys: Some Chinese people are hiding in their houses for a couple weeks. It actually doesn&amp;#39;t affect long term outlook for the stock at all though. Think about it :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:37:44 </td>
   <td style="text-align:left;"> $AAPL if it breaks $160.36 its headed to $165 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:36:26 </td>
   <td style="text-align:left;"> $AAPL LOL  ATVI MISSED - </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:35:40 </td>
   <td style="text-align:left;"> $AAPL GONNA MISS BAD ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:34:52 </td>
   <td style="text-align:left;"> $AAPL They want you to sell on Fear so they can buy. Have some balls or don’t invest. 200 by year end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:33:18 </td>
   <td style="text-align:left;"> $AAPL $GOOGL $MSFT https://finance.yahoo.com/news/zacks-investment-ideas-feature-highlights-092409908.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:31:33 </td>
   <td style="text-align:left;"> $AAPL As ugly as the past few weeks have been, still holding in the channel that formed in 2020, bouncing off the bottom of that today in the 158 range, meaning &amp;gt;200 is the next leg up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:28:50 </td>
   <td style="text-align:left;"> $AAPL  🍏 Volume climbing, 48.4 Million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:28:32 </td>
   <td style="text-align:left;"> $QQQ $TSLA $AAPL 

algos are going to destroy both bears and bulls lol 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:28:06 </td>
   <td style="text-align:left;"> $AAPL Sold $147 puts and then bought 172.5 calls, both well in the green currently. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:27:29 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #2 ticker with sweep activity where institutions are trading options urgently with 14.1K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:26:06 </td>
   <td style="text-align:left;"> $AAPL I just soiled my fucking drawers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:25:38 </td>
   <td style="text-align:left;"> $AAPL rocket it 🤑🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:25:22 </td>
   <td style="text-align:left;"> $SPY the pump machine is trying to trick bulls to get in lol. Who wants to bite lol 😂 $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:25:12 </td>
   <td style="text-align:left;"> Unusual Options Activity: $AAPL is the #17 ticker with unusual activity from institutional traders with an average of 13% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:24:46 </td>
   <td style="text-align:left;"> $AAPL big fight for just one dollar lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:24:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $AAPL 
Lots of companies trapped. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:21:20 </td>
   <td style="text-align:left;"> $AAPL $120 by end of week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-26 00:18:23 </td>
   <td style="text-align:left;"> $AAPL come on $151 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:45:34 </td>
   <td style="text-align:left;"> $TSLA This scumbag is obviously going to be selling massive amounts of shares. He has a loan for part of the financing but needs plenty more money. Fuck this asshole. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:45:09 </td>
   <td style="text-align:left;"> $TSLA I could do this all year. Buy at $975-$980. Sell at $1025-$1050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:43:22 </td>
   <td style="text-align:left;"> $TSLA NEWS - TSLA Wall Street Doubts Profit Margin Sustainability: 
https://www.youtube.com/watch?v=6T5vmHOtJCQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:42:36 </td>
   <td style="text-align:left;"> $TWTR Don&amp;#39;t own any Twitter, But I do own $TSLA &amp;amp; $ZNOG and would Love to see this as Twitter&amp;#39;s new logo. LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:41:52 </td>
   <td style="text-align:left;"> $TSLA Just stopping by to see if Los Angeles lefties started pulling their Tesla power inverters out of their walls yet. 
 
$FSR $GOEV $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:40:21 </td>
   <td style="text-align:left;"> $TSLA how is musk paying for this? Tsla shares curious because a little worried about it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:38:29 </td>
   <td style="text-align:left;"> $TSLA the Twitter whip $DOGE.X $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:37:47 </td>
   <td style="text-align:left;"> $DOGE.X $TWTR $TSLA  I love it 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:37:18 </td>
   <td style="text-align:left;"> $NFLX 5x your money with my call outs 🙏😇❤️🌞👍🚀 $TSLA $SPY $NVDA $FB https://youtu.be/n7ovzGgjBus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:36:51 </td>
   <td style="text-align:left;"> $TWTR $TSLA $DOGE.X 🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:35:37 </td>
   <td style="text-align:left;"> $TSLA SOOO WHERE IS HE GOING TO GET THE 43 BILLION FROM?!! ****SELLIING THESE SHARES******

(UNLESS ITS UNDER HIS PILLIOW AT HIS FRIENDS HOUSE) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:32:58 </td>
   <td style="text-align:left;"> $PQEFF Has anyone recently talked to Elon Musk $TSLA? 
In a week or two he&amp;#39;ll be looking for something to get into. Great opportunity in green CORT technology with Petroteq Energy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:32:53 </td>
   <td style="text-align:left;"> $TSLA who is this elon musk guy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:31:18 </td>
   <td style="text-align:left;"> $spy If you&amp;#39;ve never seen the film Sexy Beast you should. One of my fav&amp;#39;s &amp;amp; Sir Ben Kingsley was just so great &amp;amp; crazy 
 
This scene is right after his Broker told him to Buy more $dwac after he had already added at $100 &amp;amp; then $80. 
 
https://www.youtube.com/watch?v=DDLpKrTVJKc 
 
$twtr $fb $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:29:04 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:27:55 </td>
   <td style="text-align:left;"> $TSLA “What about Tesla investors?

If you’re betting on Tesla at $1 trillion, you’re likely betting on Musk to continue working his magic. He has plenty of distractions already. Is this one too big to stomach? Tesla shares fell slightly on Monday and are down 2.3% since Musk’s bid on April 14. The Nasdaq is down more.” 
Elon Musk&amp;#39;s deal to buy Twitter leaves many key questions unanswered https://www.cnbc.com/2022/04/25/elon-musks-deal-to-buy-twitter-leaves-many-key-questions-unanswered.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:27:33 </td>
   <td style="text-align:left;"> Musk’s First Victim: Fisker’s CEO deletes his account minutes after the deal $FSR $TSLA $TWTR 
https://eletric-vehicles.com/fisker/musks-first-victim-fiskers-ceo-deletes-his-account-minutes-after-the-deal/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:26:33 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX SUCH A WEAK FINISH!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:24:14 </td>
   <td style="text-align:left;"> $TSLA $MSFT 

https://www.thesun.co.uk/tech/18372914/inside-elon-musks-feud-with-bill-gates/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:20:19 </td>
   <td style="text-align:left;"> $TSLA Elon .. Elon .. Nobody talks about Tesla 😇 or catalysts near term. China  lockdowns.? To da moon.. They say.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:20:08 </td>
   <td style="text-align:left;"> $TWTR $SPY $FB $TSLA $SNAP 
Most Famous Dona tweet 2.0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:19:58 </td>
   <td style="text-align:left;"> $TSLA this will face major resistance at $975 and then free fall... look for entry in the $800’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:19:50 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;W&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:19:27 </td>
   <td style="text-align:left;"> $TWTR  elon punishing joe for not inviting him to EV summit.  🤣 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:19:16 </td>
   <td style="text-align:left;"> $TSLA TESLA Stock Price  Prediction and Analysis for  Tuesday April 26
https://youtu.be/3gvw8bQ6Ou4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:18:47 </td>
   <td style="text-align:left;"> $TSLA the pump is over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:17:17 </td>
   <td style="text-align:left;"> $TSLA elon would not spend a dime on Facebook until he has a chance to figure out wtf is meta shesh they do with it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:13:39 </td>
   <td style="text-align:left;"> $TSLA This goes to 1100. In a very short amount of time. TWTR goes to $43 to start then $34. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:12:50 </td>
   <td style="text-align:left;"> $TSLA this board is gonna be annoying asf for another week lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:12:43 </td>
   <td style="text-align:left;"> $TSLA elon said biggest company in the 🌍. spacex,tesla,teeter combined will do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:12:27 </td>
   <td style="text-align:left;"> $TSLA $TWTR 

https://www.marketwatch.com/story/twitters-board-accepts-elon-musks-offer-and-users-are-either-celebrating-free-speech-or-saying-rip-twitter-11650916880#:~:text=Musk%20responded%20to%20the%20early,is%20what%20free%20speech%20means.%E2%80%9D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:12:18 </td>
   <td style="text-align:left;"> $TWTR $SPY $FB $SNAP $TSLA 
Most Famous tweets by Dona </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:11:48 </td>
   <td style="text-align:left;"> $TSLA Its not about your love to polish another grown man’s balls. This is the stock market. Cool? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:11:15 </td>
   <td style="text-align:left;"> $TSLA tomorrow 1050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:10:48 </td>
   <td style="text-align:left;"> $TSLA well gotta love the attention. ATH headed your way champ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:10:05 </td>
   <td style="text-align:left;"> $TSLA Ok I get it fan boys. Do more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:09:59 </td>
   <td style="text-align:left;"> $TSLA funny how so many non-billionaires always have so much sh*t to say about how billionaire Musk spends his billions and makes his billions. Free speech, priceless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:09:51 </td>
   <td style="text-align:left;"> $TSLA 

1/3rd of Mr. Free Speech’s company is in China, a country famous for their freedoms. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:09:37 </td>
   <td style="text-align:left;"> $TSLA $MSFT Twitter + Elon = Twitterverse Eruption: How The Social Media Platform&amp;#39;s Denizens Reacted To Musk Buyout 

https://newsfilter.io/a/0ed53548cb51bf2f8c4364380663f80d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:09:27 </td>
   <td style="text-align:left;"> $MSFT Was up Today on the News that Bill Gates is Short on $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:09:24 </td>
   <td style="text-align:left;"> $RKLB $UFO $ARKX $TSLA 
🚀🛰🛸👽
https://youtu.be/74sXa2qySPM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:09:14 </td>
   <td style="text-align:left;"> $TSLA this guy Elon Musk is always a winner.  When will shorts learn not to bet against him.  Now he just bought Twitter.  Who else can do that.  He’s about to screw s Twitter shorts too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:09:04 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-25 Daily Forecast Video: 
https://www.youtube.com/watch?v=ICotjfKHkD8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:08:40 </td>
   <td style="text-align:left;"> $TSLA And yes..bearish on twtr. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:07:27 </td>
   <td style="text-align:left;"> $TSLA 

So now Elon owns the memes to production.     

Prepare for him to be distracted by the dopamine hit he continuously gets from his phone.

Hopefully he doesn’t Roblox next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:07:22 </td>
   <td style="text-align:left;"> $TSLA Let’s see.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:07:22 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:07:01 </td>
   <td style="text-align:left;"> $TWTR $TSLA $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:05:40 </td>
   <td style="text-align:left;"> $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:04:06 </td>
   <td style="text-align:left;"> $TSLA Fascinating price freeze on a Monday WITH $twtr news. Simply. Fascinating. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:01:28 </td>
   <td style="text-align:left;"> $TSLA Elon will not need to sell Tesla shares to buy Titter, according to people much smarter than me: https://twitter.com/TeslaPodcast/status/1518670382529531904?t=_KF23uQcqRIhsrU3Tq5sOw&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:00:25 </td>
   <td style="text-align:left;"> Twitter + Elon = Twitterverse Eruption: How The Social Media Platform&amp;#39;s Denizens Reacted To Musk Buyout $TWTR $TSLA https://benzinga.com/z/26801021#.YmcZ5jpR9g4.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 06:00:10 </td>
   <td style="text-align:left;"> $TSLA Anyone that buys a Tesla in future gets an automatic blue Tick on their Twitter profile. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:59:33 </td>
   <td style="text-align:left;"> $TWTR What about Twitter red for $TSLA owners???🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:59:32 </td>
   <td style="text-align:left;"> $TSLA Where is Elon gonna get the money from to buy twitter? Thats a lot of cash to raise in a hurry... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:59:31 </td>
   <td style="text-align:left;"> $TSLA Timing is everything, so I&amp;#39;ll be paytiently waiting. 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:58:19 </td>
   <td style="text-align:left;"> $TSLA LMAO tesla closing over $1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:58:19 </td>
   <td style="text-align:left;"> $FSR $TSLA $TWTR 
https://eletric-vehicles.com/fisker/musks-first-victim-fiskers-ceo-deletes-his-account-minutes-after-the-deal/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:58:00 </td>
   <td style="text-align:left;"> $TSLA Retesting $1k here in AH 🔎 
- 
https://discord.com/invite/uQ5UXZW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:55:41 </td>
   <td style="text-align:left;"> $TSLA what? Do bulls think Elon is going to rob a bank to pay for $TWTR? No, he’s going to fucking sell Tesla shares, duh! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:55:15 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX FUTURES ALREADY CRASHING!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:53:50 </td>
   <td style="text-align:left;"> $TSLA did elon overpaid and over leveraged buying $TWTR? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:53:46 </td>
   <td style="text-align:left;"> $spy $twtr $tsla 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:53:39 </td>
   <td style="text-align:left;"> $TSLA Musk buying Twitter is a disaster for Tesla.   Once Tesla falls back to earth, Musk will be forced to sell.  It’s going to be hilarious. 

https://twitter.com/peterschiff/status/1518670652533784576?s=21&amp;amp;t=75xnIR8xsJ2QRmew35ZSYQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:53:32 </td>
   <td style="text-align:left;"> $TWTR $TSLA $SPY $AAPL 
Literally 99% of the people on here. Broke worshiper lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:53:22 </td>
   <td style="text-align:left;"> $TSLA Bill Gates probably upped his short. I took profits on a few August puts this morning. Waited for the pump to buy 4 additional November 18 puts. Still have October and August puts. Didn&amp;#39;t want to touch October.  Full meltdown will occur next month when people realize Shanghai is still operating at minimum capacity. Will ride this bubble down to $86/share. Btw, Twitter is an excellent distraction from the continued lock downs in China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:53:11 </td>
   <td style="text-align:left;"> $TSLA Trade it or Fade it 🔎 
 
https://discord.com/invite/uQ5UXZW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:53:01 </td>
   <td style="text-align:left;"> $TWTR &amp;quot;Upon completion of the transaction, Twitter will become a privately held company. Under the terms of the agreement, Twitter stockholders will receive $54.20 in cash for each share of Twitter common stock that they own upon closing of the proposed transaction&amp;quot;. $SPY $TSLA $AAPL $FB https://www.sec.gov/Archives/edgar/data/1418091/000119312522117743/d319190ddefa14a.htm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:51:51 </td>
   <td style="text-align:left;"> $ATER 🚨 Squeeze Data 👀

🐊 ATERIAN Artificial Intelligence 🐊

🌏🌍🌍🛒🛍️📦📊 

There&amp;#39;s a Reason Why Vice Presidents of ( $MSFT $AMZN , HASBRO) $3.5Trillion Companies,  Cynthia Williams &amp;amp;  Anton von Rueden( E-bay) Joined this Company.
&amp;amp;
There&amp;#39;s a Reason Why this is No.1 Short Squeeze Stock on Bloomberg Terminal SI Score:5.5, Fintel,Ortex 🌋🚀🌙✨

Total Open Interest (265K -365K)

Possibly 26Million Shares-36Million Shares could be ITM due to Current Squeezy Data 🌋

That&amp;#39;s Nearly 150% of Free Float 🌋😳
+
 75% Float is on Loan😳
(Nearly 20Million Shares)
=46Million-56Million Shares
(200% of Free Float)😳🌋🚀🌙✨

Shorts still think they know More than 
Her &amp;amp; Him 🤣

( Thanks to ELON $TSLA for saving $TWTR Shareholders &amp;amp; Freedom of Speech 🎙️ by Single Handed Knock Out 
🥊🩳🔥 ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:51:32 </td>
   <td style="text-align:left;"> $TSLA $NKLA New video from one of our traders!

https://youtu.be/2mtg_F582iU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:50:12 </td>
   <td style="text-align:left;"> $TSLA only red on my entire watchlist 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:49:43 </td>
   <td style="text-align:left;"> $TSLA I think Bill Gates if fucked long term with his short position. There is an inverse h&amp;amp;s forming on the daily chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:49:27 </td>
   <td style="text-align:left;"> $TSLA Thinking about buying shares just cause I&amp;#39;m so happy with Elon right now!!!🇺🇲🇺🇲🇺🇲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:48:59 </td>
   <td style="text-align:left;"> $TSLA today raw materials in... car out

Tomorrow

 raw materials in car manufacturing plant out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:46:12 </td>
   <td style="text-align:left;"> $TSLA I’ll be back at $400, remember this post. It’s time to get out of Tesla. Game over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:45:51 </td>
   <td style="text-align:left;"> $TSLA one of best play in 2022!

https://www.reddit.com/r/ATERstock/comments/ubsmmr/ater_is_the_most_mentioned_stock_on/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf

Just look at the facts and dd in this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:45:45 </td>
   <td style="text-align:left;"> $TSLA Elon will get Twitter sparingly profitable in a couple of years and being private he can keep all those billions to himself and the private investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:44:50 </td>
   <td style="text-align:left;"> $TSLA $TWTR  Just like Elon over paid for Twitter, y’all over pay for pretend coffee from Starbucks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:44:44 </td>
   <td style="text-align:left;"> $DOGE.X $TWTR $TSLA Looking Bullish on these 3. $SHIB.X $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:44:35 </td>
   <td style="text-align:left;"> $TWTR $DKNG $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:43:29 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : If Bill Gates Is Shorting TSLA Stock, He&amp;#39;s Making a Big Mistake https://www.stck.pro/news/TSLA/26752832 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:42:49 </td>
   <td style="text-align:left;"> $TSLA Elon will use Twitter all day, he won’t care about Tesla now.. sell! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:42:26 </td>
   <td style="text-align:left;"> $TSLA so elon bought Tesla to promote his own car! Now I know will be the biggest bubble in stock market history. Bill I’m with you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:42:05 </td>
   <td style="text-align:left;"> $TSLA Buch of lunch money gambling Nostradamus&amp;#39;s in here ffs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:41:00 </td>
   <td style="text-align:left;"> The Piotroski-F score of $TSLA is 7.00. This indicates good health for $TSLA. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:40:45 </td>
   <td style="text-align:left;"> $MMAT can Elon finally get the Twitter ap deleted off George’s phone !? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:40:09 </td>
   <td style="text-align:left;"> $TSLA  lol otm puts for Aug expire are cashing.  Bahahhaha. Now I wait for tech wreck week starting tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:39:58 </td>
   <td style="text-align:left;"> $TSLA 1020 tomorrow mark it not saying it’ll finish there but in the morning pump from 10-11 am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:39:43 </td>
   <td style="text-align:left;"> $TSLA  $TWTR  $DOGE.X  ====&amp;gt;  these FUCKERS ABOUT TO EXPLODE !!!! 👀🔥🔥🚀🚀🚀 
. 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:39:24 </td>
   <td style="text-align:left;"> $SPY $TSLA $DWAC $FB $SNAP 
Hes back????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:38:47 </td>
   <td style="text-align:left;"> $TSLA sell now! But none of ya’ll will. 😂 just posting this so I can gloat in a year. Feel free to save it and gloat against me if you believe I’m wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:38:21 </td>
   <td style="text-align:left;"> $TSLA God i love elon. Make me rich brother like last year. Go go go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:38:02 </td>
   <td style="text-align:left;"> $TSLA somehow I don’t think Musk cares about ‘everyone should say whatever they want’ this is too altruistic - I think this about the data that Twitter houses and how the data will help musk with information to drive forward his ambitions - think about the Tesla bot integration with twitter - or with his cars or even when u are in mars, it is the data and technology of twitter like algorithms that really matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:38:01 </td>
   <td style="text-align:left;"> Love the people who sold their tesla stock on the twitter news thinking Elon has to sell some shares. What a gift, tesla under $1000. $TSLA $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:37:49 </td>
   <td style="text-align:left;"> $TSLA What&amp;#39;s a Fikser? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:37:44 </td>
   <td style="text-align:left;"> $TSLA 

Here’s Senator Karen !

“This deal is dangerous for our democracy. Billionaires like Elon Musk play by a different set of rules than everyone else, accumulating power for their own gain. We need a wealth tax and strong rules to hold Big Tech accountable.” 💩

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:37:33 </td>
   <td style="text-align:left;"> $TSLA shorts doing whatever they can to short here.. not that easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:36:58 </td>
   <td style="text-align:left;"> $TSLA trump said he likes elon a lot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:36:51 </td>
   <td style="text-align:left;"> $TSLA donald says fuck elon and twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:36:40 </td>
   <td style="text-align:left;"> Musk’s First Victim: Fisker’s CEO deletes his account  $FSR $TSLA $TWTR 
https://eletric-vehicles.com/fisker/musks-first-victim-fiskers-ceo-deletes-his-account-minutes-after-the-deal/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:35:53 </td>
   <td style="text-align:left;"> $TSLA unfortunately bad news got us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:35:41 </td>
   <td style="text-align:left;"> $TSLA So bears will have to drop the stock about 25% to even trigger a margin call...... good luck bears cause that would mean a market crash and the S&amp;amp;P500 would basically go back to 1960 levels </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:35:06 </td>
   <td style="text-align:left;"> $NFLX $SPY $TSLA BOUGHT PUTS, AND NO DOUBT WILL MAKE MILLIONS THIS WEEK!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:34:43 </td>
   <td style="text-align:left;"> $TSLA What do Tesla, Netflix, and Bank of America all have in common? Yeah, they all finished RED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:34:36 </td>
   <td style="text-align:left;"> $CANG Definitely under the radar with this one…

983 watchers, low volume, +40% in one day!! 

Sharing to the popular boards! 
🚨NO ONE KNOWS ABOUT THIS. 🚨 

Quick DD: 
$1 dividend per share, May 24
$50m buy back announced. 
No 🧢 - it’s free money at this point.

$TWTR $DOGE.X $TSLA $RDBX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:33:10 </td>
   <td style="text-align:left;"> $TSLA Elon doesn&amp;#39;t need to sell Tesla shares. He can use 50% as collateral but that&amp;#39;s about it. Just hope no stop loss for him lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:32:35 </td>
   <td style="text-align:left;"> $TSLA  I&amp;#39;m guessing the twitter hobby won&amp;#39;t hurt TSLA too much.  Elon will be the same amount of stupid as always and it won&amp;#39;t hurt Tesla much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:31:17 </td>
   <td style="text-align:left;"> $TSLA So much misinformation on this site, but am I wrong to assume now that the banks are lending the money for the purchase from Elon&amp;#39;s TESLA shares, that ultimately the two are now somewhat tied together? In other words, if twitter starts failing, TSLA stock would be affected? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:31:08 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 4/25/2022 $SPY $TWTR $TSLA $QQQ $XBI https://www.chartguys.com/daily-market-videos/4219/bulls-stop-the-bleeding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:30:58 </td>
   <td style="text-align:left;"> $TWTR $TSLA technically </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:28:17 </td>
   <td style="text-align:left;"> $TSLA musk had to sell some shares which is why we dropped today a little 

That is what I found in my research </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:28:15 </td>
   <td style="text-align:left;"> $TSLA https://www.barrons.com/articles/tesla-stock-elon-musk-twitter-margin-borrowing-51650918318?mod=bar_RHF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:27:53 </td>
   <td style="text-align:left;"> Musk’s First Victim: Fisker’s CEO deletes his account minutes after the deal — EV $FSR $TSLA $TWTR 
https://eletric-vehicles.com/fisker/musks-first-victim-fiskers-ceo-deletes-his-account-minutes-after-the-deal/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:25:35 </td>
   <td style="text-align:left;"> $TSLA looking a swing trade from $980-$1025 this time. 

170 shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:24:15 </td>
   <td style="text-align:left;"> Dogecoin Soars 26% After Twitter Accepts $44 Billion Bid From ... $TSLA
► https://decrypt.co/?p=98630 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:23:55 </td>
   <td style="text-align:left;"> $TSLA bubble stock, doing bubble stock things </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:23:45 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:22:09 </td>
   <td style="text-align:left;"> $TSLA getting into car insurance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:21:42 </td>
   <td style="text-align:left;"> $TSLA big blocks are being sold right now, check your level2 to confirm!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:21:29 </td>
   <td style="text-align:left;"> $TSLA  THAT BEAR JCCOO IS BIG MAD TODAY.  LMAO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:19:57 </td>
   <td style="text-align:left;"> $GGPI $FSR $TSLA I am curious.  Is this how the Biden Enterprise does their business with say Polestar, by making an overseas phone call.

Hi Thomas, this is Joe Biden, finally we get a chance to speak.  I would rather it was in person in Stockholm, but we can fit that into  our schedules later. 

I have a proposal for you.  I was thinking Polestar would do much better in sales in the U.S.A. if you would install my son Hunter as a member of the Board of Polestar. You would be amazed at what can be done, and how quickly, to get Polestar some relief on the U.S.A. import tarriff of 17% on imported EVs.

If we are both seeing things the same, Hunter would need a luxury suite in Stockholm and he will be in contact with you to direct you on where to wire his salary of shall we say, a modest $100,000 a month.  I am sure this can be mutually beneficial for all involved. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:19:53 </td>
   <td style="text-align:left;"> $TSLA $TWTR so the first Elon’s demand was to hide these two from trending to avoid attacks ? 🤔
Who will sensor Elon now? The SEC 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:19:40 </td>
   <td style="text-align:left;"> If Bill Gates Is Shorting $TSLA Stock, He&amp;#39;s Making a Big Mistake 
 
https://investorplace.com/2022/04/if-bill-gates-is-shorting-tsla-stock-hes-making-a-big-mistake/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:17:53 </td>
   <td style="text-align:left;"> $DWAC guys...its over 
$twtr $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:17:18 </td>
   <td style="text-align:left;"> $TSLA earnings pump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:17:09 </td>
   <td style="text-align:left;"> Musk’s First Victim: Fisker’s CEO deletes his account minutes after the deal  $FSR $TSLA $TWTR 
https://eletric-vehicles.com/fisker/musks-first-victim-fiskers-ceo-deletes-his-account-minutes-after-the-deal/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:16:38 </td>
   <td style="text-align:left;"> $TSLA He’s not going to sell unless he absolutely has to.  This is the guy that lives on his friend’s couch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:16:36 </td>
   <td style="text-align:left;"> Twitter $TWTR Approves Sale to Elon Musk for $54.20/Share. $TSLA https://www.zacks.com/stock/news/1907367/twitter-twtr-approves-sale-to-elon-musk-for-5420share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:15:22 </td>
   <td style="text-align:left;"> $TSLA $TWTR where is the money coming from? Does Elon need to sell tesla shares? Or will he need to borrow against tesla stock? Someone please explain!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:14:40 </td>
   <td style="text-align:left;"> $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:14:36 </td>
   <td style="text-align:left;"> $TSLA bull mode very soon. Don’t waste you time on TWTR… it’s had its bull run. Price is set. Load up on TSLA for EOY run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:14:27 </td>
   <td style="text-align:left;"> Musk’s First Victim: Fisker’s CEO deletes his account minutes after the deal — EV $FSR $TSLA  
https://eletric-vehicles.com/fisker/musks-first-victim-fiskers-ceo-deletes-his-account-minutes-after-the-deal/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:14:15 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:14:03 </td>
   <td style="text-align:left;"> $TWTR $dwac 
$spy  $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:13:48 </td>
   <td style="text-align:left;"> $TSLA Look, I am independent. Not a fan of Trump, not a fan of Biden. What I don&amp;#39;t understand is why the left is trying to make Elon a right icon? I haven&amp;#39;t seen him politically weigh in on anything but production and free speech but now being colored deep red. I don&amp;#39;t understand why this collective hysterical strawmanning is going on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:13:33 </td>
   <td style="text-align:left;"> $TSLA SpoOokY Real-Time          
Trade Action Opportunity Tracking Tool          
          
Current Candlestick Vibration          
Range Potential:          
(1,008.62 / 975.30      
     
Real-Time Tracking Simulation #4     
     
Last Finite Potential Well          
Measurement at: 998.02          
For:          
04/25/22 at 4:00PM EST At Close          
          
Developing Ad Interim Trade Action          
Opportunity Potentials:          
Short-Term = BUY          
Long Term = BUY          
          
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
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:13:30 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboys are so far up Musk&amp;#39;s ass, they can&amp;#39;t even see what&amp;#39;s happening. Musk&amp;#39;s acquisition of Twitter is a conduit to sell billions in Tesla shares. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:13:00 </td>
   <td style="text-align:left;"> $TSLA News Updated: Mon, April 25, 2022, 4:09 PM https://www.zoombull.com/stock/quote/tsla/ Tesla Sinks After CEO Musk Agrees to Buy Twitter in $44 Billion Deal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:12:09 </td>
   <td style="text-align:left;"> $TWTR $TSLA  surely Musk is aware that when you alienate one side or the other you lose engagement. IMO whether you think this move is good or bad depends on your ideology liberal (fact checking) vs conservative (free speach/ censorship). A waste of 44bln unless he just wants to control the town hall which would make more sense than this democracy is in the balance narrative. Even if we have all the correct facts and no bots on social media it&amp;#39;s largely just a dumpster fire of bickering and insults. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:11:56 </td>
   <td style="text-align:left;"> $TSLA 

Taking out Twitter Board, reduce employees and removing all BOTS!!! 

Rebuild Algorithm with open sources , establish payment using crypto and launching sales / Marketing new platforms !!!! 

All good for Tesla !! 

Just to name few …. 🤫

 🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:10:52 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX I BOUGHT PUTS EOD, WILL BECOME A MILLIONAIRE BY TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:09:50 </td>
   <td style="text-align:left;"> $TSLA If Elon is taking Twitter private institutions will have to get rid of shares on their books? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:08:40 </td>
   <td style="text-align:left;"> $TSLA Levels plotted for tomorrow 🔎 
 
https://discord.com/invite/uQ5UXZW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:07:22 </td>
   <td style="text-align:left;"> $TSLA Elon Musk is welcoming all the banned Nazi, Trump terrorist members and criminals back to $TWTR all in the name of Free Speech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:06:34 </td>
   <td style="text-align:left;"> $F $TSLA. 

Hmmmmm, one CEO is laser focused on a strong EV lineup while the other is busy twitting around with several different businesses. Which one looks stronger to you going forward? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:05:58 </td>
   <td style="text-align:left;"> $TWTR 

This business will never be profitable, it doesn’t matter who owns it. Making people pay a subscription to troll and scream at each other can be done for free in many platforms. 
Musk want to sell shares in a real business $TSLA so he can get at laugh at the expense of libtards is reckless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:05:25 </td>
   <td style="text-align:left;"> $TSLA Want to nail the high. Still need to see earnings roll in this week. Undecided but not bullish. The dollar is gaining strength not a good sign for markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:05:21 </td>
   <td style="text-align:left;"> $TSLA very dangerous to use tsla shares to buy twitter. MM are gonna flush this down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:04:55 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $TSLA did max keiser buy some dogecoin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:04:53 </td>
   <td style="text-align:left;"> $CGC $tsla $ogi $vff Elan likes weed....he should buy Canopy Growth or Organigram or Village Farms or all of them for $44 billion.....peanuts for him😸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:03:09 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Elon Musk&amp;#39;s rift with Saudi Arabia stems from spat over Tesla factory https://www.stck.pro/news/TSLA/26751453 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:02:33 </td>
   <td style="text-align:left;"> $TSLA remember how Biden left tesla out,  sweat revenge 😂

Now they have lost control of there cencership platform. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:02:17 </td>
   <td style="text-align:left;"> $TWTR $TSLA They have helped me to grow my account to almost 2.5 million. 100% recommend joining! ++++ 
bestoptiontrading.a0001.net  🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:02:05 </td>
   <td style="text-align:left;"> $TSLA 42b is cheap when he now gets to advertise whatever he wants to the masses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:01:44 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-25 Chart Analysis Video: 
https://www.youtube.com/watch?v=deNh8QdXNw0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:01:23 </td>
   <td style="text-align:left;"> ELON JUST SOLD MORE $TSLA 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:01:00 </td>
   <td style="text-align:left;"> $BTC.X Musk dumping all his btc and $TSLA to pay Twitter . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:00:26 </td>
   <td style="text-align:left;"> $UBER $TWTR $TSLA all combine to create one mega company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 05:00:12 </td>
   <td style="text-align:left;"> $TSLA Elon is a genius,  now them Democrats rats will have to worry about the freedom of speech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:59:47 </td>
   <td style="text-align:left;"> $TSLA Elon mf genious, Twitter bout to be 42 billion $ advertisement  for Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:58:45 </td>
   <td style="text-align:left;"> $TSLA musk has control of the largest EV market and now the 2nd largest social media platform.  you think he&amp;#39;s not going to figure out what to do with your info from twitter. or the ads that come with it. it&amp;#39;s a marketing machine for his ow products lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:56:50 </td>
   <td style="text-align:left;"> $AMD $TWTR $TSLA $NVDA 
why the old dementia and his party so scared now, hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:56:25 </td>
   <td style="text-align:left;"> $TSLA bulls are getting a spoon full of logic tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:55:51 </td>
   <td style="text-align:left;"> $TSLA every 5 years you need new battery .No chans everybody can drive EVs. Musk just did the biggest pump and dump in history .you gave him everything plus Twitter hahaha. EVs will be out next 5-10 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:54:55 </td>
   <td style="text-align:left;"> $TSLA this will be 900 this week mark this post.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:54:47 </td>
   <td style="text-align:left;"> $TSLA bearish catalyst: margin borrowing!! huge gap down tomorrow IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:53:56 </td>
   <td style="text-align:left;"> $TSLA looks like there is lot of selling around 1000, not sure if Elon is doing it for twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:53:34 </td>
   <td style="text-align:left;"> $TSLA expecting Elon to start selling TSLA soon to fund himself again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:52:45 </td>
   <td style="text-align:left;"> $TSLA  Elon is adding risks at the wrong time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:52:25 </td>
   <td style="text-align:left;"> $TSLA Moron Musk Rat loves screwing his investors and share holders. What will this unstable  impulsive man do or buy next? Is he going to buy Disney to &amp;quot;Save&amp;quot; our children from those perverts?! lol.... can we send this ding dong to Mars already? guy is a loser </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:52:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX ABSOLUTELY NO CHANCE OF GOING GREEN TOMORROW!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:52:14 </td>
   <td style="text-align:left;"> $TSLA $TWTR “Free speech is the bedrock of a functioning democracy, and Twitter is the digital town square where matters vital to the future of humanity are debated,” said Musk in a news release. “I also want to make Twitter better than ever by enhancing the product with new features, making the algorithms open source to increase trust, defeating the spam bots, and authenticating all humans.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:51:53 </td>
   <td style="text-align:left;"> $TSLA CEO is so insecure needs to buy twitter to boost his own search rank to feel loved! Massive distraction wasting next year not shipping new cars and pissing of SEC and foreign regulators </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:51:34 </td>
   <td style="text-align:left;"> $SPY $QQQ WILL ELON MUSK BRING BACK THE FAIL WHALE? 🐋🤔 $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:50:18 </td>
   <td style="text-align:left;"> $CENN new kid on the block....strong beat on earnings ..watchout $LCID $TSLA $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:50:00 </td>
   <td style="text-align:left;"> $TSLA high volume here - really close to 1k -  Let&amp;#39;s hit it tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:49:23 </td>
   <td style="text-align:left;"> $TSLA 

Follow my posts !! (🚨🚀) 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:49:02 </td>
   <td style="text-align:left;"> $SPY $TSLA good job ELY u facjing cunt! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:48:20 </td>
   <td style="text-align:left;"> $TSLA buyers step in again at 975. That&amp;#39;s the level to watch. That level has held in the last 6 of 10 trading sessions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:48:06 </td>
   <td style="text-align:left;"> $TSLA wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:47:30 </td>
   <td style="text-align:left;"> $TSLA Elon is no longer at risk of having his Twitter account disabled. His Twitter feed is the only official marketing Tesla has. The risk is gone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:46:17 </td>
   <td style="text-align:left;"> $TSLA do the thing ⬆️ ⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:45:52 </td>
   <td style="text-align:left;"> $TSLA This price action...so boring. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:45:44 </td>
   <td style="text-align:left;"> $TSLA Elon buys Twitter and for some reason market goes green 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:45:11 </td>
   <td style="text-align:left;"> $TSLA The question is will the people upset with Elon start bashing it hard on Twitter to get back at him for buying it and getting him to compromise his free speech platform. Only time will tell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:44:12 </td>
   <td style="text-align:left;"> $TSLA this company is murdering the planet raping it of rare earth minerals to make these goofy batteries. Not to mention all the real trucks to haul them to civilized areas of the world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:43:48 </td>
   <td style="text-align:left;"> $TSLA  great day for blocking trolls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:42:07 </td>
   <td style="text-align:left;"> $TSLA sell your shares b4 elon dump his. selling at this price id better than buying more🫣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:41:56 </td>
   <td style="text-align:left;"> $TSLA fed meeting next Tuesday....earnings sell the news thid week ...what a great time to print puts... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:40:45 </td>
   <td style="text-align:left;"> $TSLA Elon is selling it. Buy it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:40:37 </td>
   <td style="text-align:left;"> Elon is NOT selling $TSLA to buy $TWTR ... No need to panic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:40:29 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #3 stock that institutions are trading over rolling 5 day window with 157.8K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:40:23 </td>
   <td style="text-align:left;"> $TSLA margin borrowing . What happens if Tesla drops to 100.and Musk be forced to sell His shares. And everybody will know a 1/3 of shares will be dumped ? I tell you this goes to 0 BK . Bad bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:40:21 </td>
   <td style="text-align:left;"> $TSLA Donnie just said he’s not going back to $TWTR lmao $DWAC  
 
sounds like Elon is now the king of the libs and we’ll have politically divided Twitter/Truth social… hmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:40:00 </td>
   <td style="text-align:left;"> $TSLA tomorrow 1050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:39:54 </td>
   <td style="text-align:left;"> $TSLA 

We are taking back the country starting with Twitter!! You better believe it 0.02 

🙏🏻🐉🦅
@elonmusk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:38:38 </td>
   <td style="text-align:left;"> $TSLA this looks like fun on the side of a highway at five in the afternoon. Gasoline is the future get used to it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:38:03 </td>
   <td style="text-align:left;"> $TSLA I wonder how he&amp;#39;ll pair Tesla with Twitter. All the tech in the car is about the  experience so not gonna be surprised if Elon does some genius shit with Twitter and Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:37:51 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $TSLA has Elon mention activating Trump Twitter account? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:37:29 </td>
   <td style="text-align:left;"> $TSLA overexaggerated run up can lead to an over exaggerated sell off. I am happy holding June puts. :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:37:17 </td>
   <td style="text-align:left;"> $TSLA Elon crashes TSLA for Twitter!! https://youtu.be/grXUEopIvWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:37:02 </td>
   <td style="text-align:left;"> $TSLA Just because he bought $TWTR doesn’t mean he’ll be the CEO.  All it means is that he can pick who runs the company. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:36:51 </td>
   <td style="text-align:left;"> $TSLA Come on. When $1200? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:36:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Elon Musk proves that he is a GOP person rather than a Dems person, President Biden did the right thing by preferring great companies like GM and Ford over Tesla $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:36:08 </td>
   <td style="text-align:left;"> $TSLA LMAO elon tweet... yall want a stock split ....... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:35:49 </td>
   <td style="text-align:left;"> $SPY last quarter with semi shitty earnings to sell into, next quarter is fckn Hiroshima in the markets, looking for spikes on q’s and $spy to short between now and June. Any baby bull run greatly appreciated. Thank you! $tsla target $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:35:33 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:35:26 </td>
   <td style="text-align:left;"> $TSLA need to test 800 for healthy growth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:34:43 </td>
   <td style="text-align:left;"> $TSLA $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:34:36 </td>
   <td style="text-align:left;"> $TSLA chad investment in this type of market environment. I really hope this collapses to 700 or sub 700 where it really should be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:34:32 </td>
   <td style="text-align:left;"> $VEON $TWTR veon used to be 1.54 before the sanctions. The market overreacted and thought veon was subject to these sanctions. But they’re not! VEON is elon approved. Spacex sent starlinks satellites to help VEON in ukriane. VEON also has earnings coming out april 28! VEON is Deadnsyde approved. And VEON is the number 1 cell phone service provider in Middle East. It ALSO PAYS DIVIDENDS! can you get more bullish than that? Sitting at .61 cents per share! $TSLA $ASTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:34:25 </td>
   <td style="text-align:left;"> $TSLA so elon is going to sell or what? He needs money for that POS $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:33:48 </td>
   <td style="text-align:left;"> $FSR so what. We have a billionaire CEO too just like $TSLA . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:33:42 </td>
   <td style="text-align:left;"> $ATER  🐊💎🙌🤝💸🐊 Reason for 
Squeeze No.1 
By Bloomberg Terminal Fintel Ortex 🌋

Today&amp;#39;s Option Flow 💸👌

Data is SQUEEEZY 🌋🚀🌙✨

There won&amp;#39;t be Enough Shares to cover those  TOTAL ITM calls 20th May  (250K -360K) Approximately (25Million Shares -36Million Shares)🤣

🥊🩳🔥

Congratulations $TWTR &amp;amp; $TSLA ELON Saved Shareholders &amp;amp; Freedom of Speech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:33:41 </td>
   <td style="text-align:left;"> $TSLA Musk just dropped a sloppy &amp;quot;grumpy&amp;quot; all over the Tesla Fanboys with his purchase of Twitter! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:33:27 </td>
   <td style="text-align:left;"> $TSLA $TWTR can it get better than this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:33:24 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-25 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=_TjkBB0Djdw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:33:00 </td>
   <td style="text-align:left;"> $TWTR pretty soon I should be able to tweet using my $TSLA display and go through a $MCD drive through and pay with $AABB $AABBG.X 

It&amp;#39;s all coming together. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:32:58 </td>
   <td style="text-align:left;"> $TSLA underperforming? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:32:45 </td>
   <td style="text-align:left;"> $MULN ALL IN NOW 

https://twitter.com/mullen_usa/status/1518681256170598402?s=21&amp;amp;t=W1gGOKtDzajsq6pHUlZSpg

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:32:18 </td>
   <td style="text-align:left;"> $TSLA  will Elon be selling and/or leverage some shares?  Hell yeah!  Will Elon pump $TSLA first with things like share split announcement and/or other means of share price appreciation talk/actions? Hell yeah! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:31:55 </td>
   <td style="text-align:left;"> $TSLA I don&amp;#39;t get it. Why is anyone excited about the CEO of a massively complicated company finding a rather expensive pet project? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:31:54 </td>
   <td style="text-align:left;"> $TSLA closed lower than Fridays close, probably going lower tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:31:49 </td>
   <td style="text-align:left;"> $TSLA look at strong open tomorrow and 30 min to an hour in buy the hell out of puts. Cause it will make a bigger move down Than today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:31:39 </td>
   <td style="text-align:left;"> $TSLA Risk of CEO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:31:07 </td>
   <td style="text-align:left;"> $SPY I WONDER WHAT WILL REPLACE $TWTR IN THE S&amp;amp;P 500 HOPEFULLY A COMPANY WITH ACTUAL POTENTIAL LIKE $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:30:30 </td>
   <td style="text-align:left;"> $TSLA Bears should be nervous now elon can say whatever he wants about tesla new ideas stock splits ETC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:29:47 </td>
   <td style="text-align:left;"> $TSLA Musk is most likely leaving Tesla. Twitter is his next project. He will also get to run SpaceX unless he ends up in prison. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:29:29 </td>
   <td style="text-align:left;"> $TSLA  Lets get 980 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:29:07 </td>
   <td style="text-align:left;"> $SPY $DJIA $NASDAQ $TSLA $TWTR When cost of Borrowing dropping like that it means Cheaper Re-finance and IPO, actually represent falling interest rates....

Dow stages big reversal Monday, closing up by more than 200 points

https://www.cnbc.com/2022/04/24/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:28:35 </td>
   <td style="text-align:left;"> $TSLA psst.. it&amp;#39;s time to come back to earth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:27:23 </td>
   <td style="text-align:left;"> $TSLA no skin in this one but it’s laughable to read bulls claiming Elon won’t be selling. He absolutely will be selling shares and also leveraging even more. The good thing, Elon will likely be honest and upfront. He definitely pumped the stock during earnings call, smart move. Let’s see if TSLA can hold a poor market and a CEO wanting to raise billions in cash. My guess, TSLA trades much lower the next few weeks. I’ll sit on the sidelines and watch… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:27:22 </td>
   <td style="text-align:left;"> $TSLA 

An EV, Solar, Space, and Social company. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:27:07 </td>
   <td style="text-align:left;"> $TSLA $TWTR gotta say...the guy has some big balls. He does what he wants. I respect. Uncommon these days with the big dogs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:27:05 </td>
   <td style="text-align:left;"> $TSLA premarket this was 950&amp;#39;s. tomorrow bulls won&amp;#39;t get saved. Guaranteed. Manipulation/hype can only last so long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:27:00 </td>
   <td style="text-align:left;"> $TSLA Doesn&amp;#39;t this mean Elon is spread even more thin? Tesla, boring co., SpaceX, and Twitter?

Instead if a great attention on one,  they all will get an OK attention? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:26:38 </td>
   <td style="text-align:left;"> $TSLA I think he is taking $TWTR  private. How exactly do you think it profits us? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:26:16 </td>
   <td style="text-align:left;"> $TSLA $TWTR boringeat deal ever although the last 20 mins of trading for Tesla were a tiny bit exciting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:25:59 </td>
   <td style="text-align:left;"> $TSLA guess where the twitter money comes from? And as TSLA price descends Elon will be forced to sell more and more to collateralize the loans 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:25:55 </td>
   <td style="text-align:left;"> $TWTR if 60c prints, maybe we won&amp;#39;t run this capalist empire to the ground. $spy $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:25:32 </td>
   <td style="text-align:left;"> $TSLA $TWTR  What you wanna bet Twitter makes it to full self-driving status before Tesla does?  Only way Musk can run TSLA is if he can AI the crap outta TWTR.  Rooting for him.  He&amp;#39;s always been a pure data guy, and my hunch is he wants out of the messy car business. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:25:29 </td>
   <td style="text-align:left;"> $SPY is Nancy short $tsla? didn’t check latest portfolio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:23:42 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX PUTS EOD!!!  SHOULD BE AN EASY 2-3x BY MORNING!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:23:19 </td>
   <td style="text-align:left;"> $TSLA will retest $700. Who wants to buy shares there ? I do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:22:32 </td>
   <td style="text-align:left;"> $UPS good stuff on this one. $FDX $F $GM $TSLA  💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:22:25 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m going to start doing 200k in cash secured puts in the 700s. Tesla is going to crush all these other EV companies, especially ones like the Chinese $NIO that copied the battery swaping that Tesla dumped 10 years ago, due to it being inferior, due to fast charging. Tesla pretty much a 4k stock in 5 yrs. NIO a $0.50 stock in 5 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:22:08 </td>
   <td style="text-align:left;"> $TSLA 

This is PayPal 2.0 Elon will turn Twitter to a free speech money making platform up to 10x return  !! 

Tesla shareholders should be excited good things around the corners 0.02!! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:21:46 </td>
   <td style="text-align:left;"> $TSLA Elon is on Tesla Margin. Oh snap 🫰 what if he gets squeezed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:21:02 </td>
   <td style="text-align:left;"> $TSLA Dan Ives said “Tesla shareholders would not be happy about this.” Paraphrasing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:20:48 </td>
   <td style="text-align:left;"> $TSLA boys and girls…, morgan stanley and whatever other bank is involved in this twitter deal are about to take their collateral being primarily tesla, to the moon. whales aren’t fools, ain’t gonna let tesla go down. the launchpad has been confirmed, around $1000. $3000 EOY (if not much earlier post split) my beautiful sweet bitches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:20:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR The inverse Cramer index striked again 🎳. He said the board had no choice but to reject Elon’s offer😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:19:55 </td>
   <td style="text-align:left;"> $TSLA $1,000 in after hours 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:19:33 </td>
   <td style="text-align:left;"> $TSLA Its just a pledge to hold shares hostage to selling bears lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:19:17 </td>
   <td style="text-align:left;"> $TWTR $60 pre market motherfuckers don’t fuck with Elon!🚀🦍🦍🦍📈📈📈 $TSLA $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:18:55 </td>
   <td style="text-align:left;"> $SPY I can hear the woke lefties screaming in the distance $TWTR $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:18:33 </td>
   <td style="text-align:left;"> $TSLA 3pm was just a taste of tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:18:06 </td>
   <td style="text-align:left;"> $TSLA give me a pullback to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:17:18 </td>
   <td style="text-align:left;"> $TSLA yeah. Elons gonna have to sell in order to find Twitter purchase </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:16:43 </td>
   <td style="text-align:left;"> $CANG 983 watchers, low volume, +40% in one day!! 

Sharing to the popular boards! 
🚨NO ONE KNOWS ABOUT THIS. 🚨 

Quick DD: 
$1 dividend per share, May 24
$50m buy back announced. 
No 🧢 - it’s free money at this point.

$TWTR $DOGE.X $TSLA $RDBX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:16:35 </td>
   <td style="text-align:left;"> $FB Jeff Bezos could outdo Elon by buying Facebook and cleaning that up.   Whose penis is bigger?  $AMZN $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:16:31 </td>
   <td style="text-align:left;"> $TSLA passion+commitment= </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:16:20 </td>
   <td style="text-align:left;"> $SPY fed douche bags can’t save markets. But one man can move all asset classes w a few tweets. Scary times. Scary. $BTC.X $TSLA $ETH.X $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:15:02 </td>
   <td style="text-align:left;"> $TSLA will rip down to $500 guarantfcknteed I can almost taste it.  $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:14:43 </td>
   <td style="text-align:left;"> Elon took $TWTR out of the shitter for good now $TSLA $QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:14:37 </td>
   <td style="text-align:left;"> $F about to F all bears when the first all electric truck gets delivered to customers - unlike vapor ware cybertrk from $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:14:32 </td>
   <td style="text-align:left;"> $NIO If you guys sell and get into $TSLA you can 4X your money in 5 yrs. If you stay here you will go bankrupt! Chapter 7! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:14:03 </td>
   <td style="text-align:left;"> $TSLA $TWTR 🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:13:56 </td>
   <td style="text-align:left;"> $TSLA Will open red IMO. Could test the support at 975 and then 940. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:13:50 </td>
   <td style="text-align:left;"> $DWAC  $TSLA $XOM  the USA homeless situation is out of control.    
tax the billy&amp;#39;s!  use the military bases for re-habs in quonset huts. 
get those who can, back to work! 
easy to solve, big gov is too big to do anything,  USA is in decline. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:12:30 </td>
   <td style="text-align:left;"> $TSLA only board bulls talk shit after a day of losing money. what a bunch of clowns. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:12:14 </td>
   <td style="text-align:left;"> $TSLA guys Elon is taking about his Twitter acquisition on his TELSA YouTube channel. In 20 minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:11:31 </td>
   <td style="text-align:left;"> $TSLA clown bears proved wrong again. You gotta fud harder! Your negative b.s. is not working. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:11:29 </td>
   <td style="text-align:left;"> $TSLA  jack Dorsey and Mark Cuban on the twtr board now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:11:14 </td>
   <td style="text-align:left;"> $TSLA 
Well at least I didn’t loose money day trading 2 Put contracts mentioned earlier.  Was stopped out with a $500 gain.  I was up a lot more earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:10:41 </td>
   <td style="text-align:left;"> $TSLA back to 950$ EOD tommorow? lol so elon musk dont have to sell any share.. or give any collateral in exchange to fund 30.5B.. come on..?? Also he would not have 100% focus on TSLA Anymore he will have to split.. So it can just go bad for TSLA long term..  he is the vision, the ambassador, if his not there..  shit happen, Oh and if twitter go bad.. look at tsla Drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:10:06 </td>
   <td style="text-align:left;"> $TSLA Everyone bragging about buying shares at $988 when the Fed  doesn&amp;#39;t raise rates until May 3rd. I&amp;#39;m afraid $988 will look awful expensive about that time. Don&amp;#39;t think it&amp;#39;s already factored in. It&amp;#39;s not. We have a long hard road ahead of us these next 2 quarters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:09:51 </td>
   <td style="text-align:left;"> $TWTR $100
$TSLA $1400

end of the year? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:09:46 </td>
   <td style="text-align:left;"> $TSLA wonder how many percent he sold of tesla to make this purchase ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:08:46 </td>
   <td style="text-align:left;"> $TWTR $SHIB.X $TSLA I great things happening! To the moon!  🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:08:22 </td>
   <td style="text-align:left;"> $TSLA why is it not dropping when the deal is official? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:08:14 </td>
   <td style="text-align:left;"> $TSLA one man moved all stocks, crypto and bonds. Epic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:08:13 </td>
   <td style="text-align:left;"> $BLSP $TSLA Hey Elon, wanna buy us too? Green company turning waste to power. They could use some aggressive leadership! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:08:00 </td>
   <td style="text-align:left;"> $TSLA Honest question, but Elon has literally confirmed that he HAS to dump quite a bit of his Tesla to buy Twitter? Seems natural since it&amp;#39;s so much money even with other partners. So will this go to the shitter? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:07:47 </td>
   <td style="text-align:left;"> $TSLA Elon is king </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:07:41 </td>
   <td style="text-align:left;"> $TWTR $TSLA Lesson learned: none of these left wing libtards who post their nonsense and are threatening to leave Twitter as a user or an employee. They don’t even know what free speech even is… it’s not a safe space because people might disagree with me now and I’ll have to defend my position. That’s my takeaway from all of this. 

😂😂😂

Democrats now will go for “social media reform.” Mark my words. Elon is a fcking legend!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:07:12 </td>
   <td style="text-align:left;"> $ATER Don&amp;#39;t Forget $36Million Shares could be ITM through Options

This Will be Supernova 🌋🚀🌙✨

We Don&amp;#39;t have Enough Float to Cover those shares🤣

$SPY &amp;amp; Entire Market Saved by Elons $TSLA $TWTR Deal, Single Handed Knock Out
🥊🩳🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:06:47 </td>
   <td style="text-align:left;"> $TWTR $TSLA 
Lmfao Cramer can go jump off a cliff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:06:36 </td>
   <td style="text-align:left;"> Trade Ideas $TSLA (delayed) MAY13 800P #quick-swing - still actionable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:05:50 </td>
   <td style="text-align:left;"> $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:05:39 </td>
   <td style="text-align:left;"> $TSLA would be buying ah hard if I could right now, sell tomorrow at the normal 10-11 am spike at 1030. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:05:38 </td>
   <td style="text-align:left;"> $AMC $TSLA $GME $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:05:04 </td>
   <td style="text-align:left;"> $BBKCF $TSLA $TWTR Elon loves Vancouver, I’m sure Mark will run into Elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:04:12 </td>
   <td style="text-align:left;"> @QuiverQuant On 2022-03-21 Congress Member Nancy Pelosi disclosed a Exercise of $TSLA. Follow our Congressional Long-Short strategy to see how other members of congress might be trading $TSLA; https://www.quiverquant.com/strategies?ref=stocktwits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:04:11 </td>
   <td style="text-align:left;"> $TSLA 

CNBC APOLOGIZING OFFICIALLY ABOUT ALL THE TROLL AND MISINFORMATION IN REGARD TO ELON CAPABILITIES OF ACQUIRING $TWTR 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:04:08 </td>
   <td style="text-align:left;"> $TWTR how does this impact the $TSLA - related restrictions on musk’s tweets? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:03:36 </td>
   <td style="text-align:left;"> $TSLA bullish close lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:03:09 </td>
   <td style="text-align:left;"> $TSLA Who got scared and sold there shares to the CROOKS on wall street. This was held back all day SHAME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:03:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA NO MORE $TWTR ON THE S&amp;amp;P 500 THANK YOU ELON $TSLA I WILL BE DRINKING AFTER WORK 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:02:28 </td>
   <td style="text-align:left;"> $TSLA bulls here Lacking brain cells </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-26 04:01:54 </td>
   <td style="text-align:left;"> $TSLA should see 1035 tmmrw </td>
  </tr>
</tbody>
</table></div>

---
