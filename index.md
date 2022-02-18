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



Last Updated: 2022-02-18 09:50:32 UTC +8

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
   <td style="text-align:left;"> 2022-02-18 09:05:54 </td>
   <td style="text-align:left;"> US Futures Flat After Market Rout </td>
   <td style="text-align:left;"> US stock futures were little changed on Friday after Wall Street sold off in the previous session on recurring geopolitical concerns. Futures contracts tied to the major indices swung between small gains and losses. In regular trading on Thursday, the Dow fell 1.78% for its biggest daily drop since November. The S&amp;P 500 lost 2.12% and the Nasdaq declined 2.88%. Investors were kept on edge amid ongoing tensions in Eastern Europe, after Ukraine accused pro-Russian separatists of attacking a village near the border. US president Joe Biden also said that the threat of a Russian invasion of Ukraine remains high in the coming days and that Russia had not in fact pulled back troops out of Ukraine. On the monetary policy front, St. Louis Fed president James Bullard, a noted hawk, warned that inflation could get out of control without rate hikes. The major averages are on track for their second negative week in a row. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/food-inflation </td>
   <td style="text-align:left;"> 2022-02-18 08:53:00 </td>
   <td style="text-align:left;"> Japan Food Inflation Stays at 16-Month High </td>
   <td style="text-align:left;"> Food inflation in Japan stood at 2.1% yoy in January 2020, unchanged from December's 16-month peak figure while marking the fifth straight month of rises. Main upward pressure came from fresh food (6.5% vs 8% in December), fish &amp; seafood (7.5% vs 6.3%), fresh vegetables (1% vs 6.6%), meats (1.6% vs 1.9%), fresh fruits (11.9% vs 9.1%), dairy products (0.2% vs -0.1%), cakes &amp; candies (1.6% vs 1.9%), oils, fats (3% vs 2.3%), beverages (1.9% vs 2.4%), meals outside the home (1% vs 0.9%), cereal (0.2% vs -1.3%), and cooked food (1.7% vs 1.6%). In contrast, prices of alcoholic beverages declined for the fourth straigh month (-0.4% vs -0.5%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60425727?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-18 08:50:34 </td>
   <td style="text-align:left;"> Global stocks tumble as tensions rise over Ukraine </td>
   <td style="text-align:left;"> Global stock markets have tumbled amid alarm over rising tensions between Washington and Moscow over Ukraine.                                                                                                                         , In Morning trade in Asia, Japan's Nikkei was 1.5% lower, while the ASX in Australia fell by 1%.                                                                                                                                       , Earlier, the Dow Jones dropped 1.8%, the wider S&amp;P 500 slid by more than 2% and the Nasdaq closed nearly 3% lower.                                                                                                                    , The falls came as US President Joe Biden accused Russia of looking for excuses for an invasion, which he said could happen in days.                                                                                                   , European markets also fell in Thursday's trading session, with London's FTSE down almost 0.9%.                                                                                                                                        , "There's a lot of nervousness out there and as we approach the weekend nothing's been settled between Russia and Ukraine," Michael James, managing director of equity trading at Wedbush Securities said.                             , "The continued weakness, especially in the growth names, is indicative of elevated nervousness and sellers continuing to swamp buyers in just about every stock."                                                                     , President Joe Biden said on Thursday that military action could begin imminently.                                                                                                                                                     , Russia called the claims "baseless" and accused the US of stoking tensions.                                                                                                                                                           , But uncertainty surrounding the situation, as Ukrainian forces and Russian-backed separatists traded fire in eastern Ukraine, added to investor worries, prompting the sell-off to accelerate in late afternoon trade.                , Technology and communication firms led the declines, which touched most sectors on the S&amp;P 500 and pushed the Dow to its steepest daily percentage fall since 30 Nov.                                                                 , Oil futures fell more than 2%, and US officials held discussions with Saudi Arabia about a "collaborative approach" to managing potential market pressures stemming from a possible Russian invasion of Ukraine, the White House said., The consumer staples sector was one of the few exempt from the declines, lifted by Walmart.                                                                                                                                           , The discount giant rose 4% after it reported strong holiday sales and executives said they expected more shoppers to turn to it as concerns about the rising cost of living increase.                                                 , Meanwhile some assets considered less risky gained, with gold rising to an eight-month high.                                                                                                                                          , A fresh perspective on how Hitler brutally seized and kept power                                                                                                                                                                      , Get ready for the final series with this sneak peek                                                                                                                                                                                   , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-us-canada-60425457?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-18 08:44:12 </td>
   <td style="text-align:left;"> Judge rules Donald Trump must testify in New York investigation </td>
   <td style="text-align:left;"> Former US President Donald Trump and two of his children must answer questions under oath in a New York investigation into their business practices, a judge has ruled.                                                                                                                                                                                                    , New York's attorney general has accused the Trump Organization of obtaining tax breaks and loans through "fraudulent or misleading asset valuations".                                                                                                                                                                                                                      , Mr Trump must sit for sworn testimony within 21 days.                                                                                                                                                                                                                                                                                                                      , He denies the accusations, and is expected to appeal the decision.                                                                                                                                                                                                                                                                                                         , He could also invoke his right to remain silent in any deposition.                                                                                                                                                                                                                                                                                                         , The Trump Organization said in a statement to the BBC: "The entire system is corrupt."                                                                                                                                                                                                                                                                                     , On Thursday, New York Supreme Court Judge Arthur Engoron said that Mr Trump, his son Donald Trump Jr, 44, and daughter Ivanka Trump, 40, must each comply with legal orders that prosecutors issued in December.                                                                                                                                                           , New York Attorney General Letitia James' investigation had uncovered "copious evidence of possible financial fraud", the judge said, giving her a "clear right" to question under oath the former president and two of his children involved in the business.                                                                                                              , Mr Trump, 75, has called the investigation politically motivated and a "witch-hunt" by Ms James, a Democrat.                                                                                                                                                                                                                                                               , Whether Donald Trump will actually answer questions under oath about his business practices is an open question.                                                                                                                                                                                                                                                           , An appeal is almost certainly forthcoming. And if that is unsuccessful, Mr Trump may decline to answer the questions, as his son Eric Trump did under similar circumstances in 2020.                                                                                                                                                                                       , That's what the former president's lawyers are already recommending. Having their client sit for what would surely be a multi-hour grilling by New York lawyers looking for verbal missteps or contradictory assertions is not their idea of sound legal strategy.                                                                                                         , This is far from the end of the line, but it still was a rough day for the former president. This civil case, and the criminal probe in Manhattan, aren't going away anytime soon. And having a judge, in a written order, say that there is "copious evidence of fraud" isn't a good look - particularly for a man who likes to boast of his unparalleled business acumen., The investigation, which was opened in 2019, aims to prove the government's claims that Mr Trump inflated the value of his assets to banks when seeking loans. The fraud is alleged to have taken place before he took office.                                                                                                                                             , Attorneys for Mr Trump had attempted to sue Ms James in a bid to prevent her from questioning the former president and his children.                                                                                                                                                                                                                                       , Ms James hailed the judge's decision as a victory, saying that "justice has prevailed".                                                                                                                                                                                                                                                                                    , The civil case is separate to a Manhattan criminal investigation into the Trump Organization's practices.                                                                                                                                                                                                                                                                  , In court, attorneys for Mr Trump argued that testifying in the civil case would improperly allow the state to circumvent a law that bars prosecutors from calling someone to testify before a criminal grand jury unless they are granted immunity.                                                                                                                        , "If she [Ms James] wants sworn testimony from my client, he's entitled to immunity," Mr Trump's defence attorney, Ronald Fischetti said.                                                                                                                                                                                                                                   , "He gets immunity for what he says, or he gets nothing".                                                                                                                                                                                                                                                                                                                   , A fresh perspective on how Hitler brutally seized and kept power                                                                                                                                                                                                                                                                                                           , Get ready for the final series with this sneak peek                                                                                                                                                                                                                                                                                                                        , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/17/business/media/oscars-vaccine-mandate-coronavirus.html </td>
   <td style="text-align:left;"> 2022-02-18 08:39:31 </td>
   <td style="text-align:left;"> Oscars Will Require Covid Tests for All, Vaccines for Most - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                               , Vaccine mandates and P.C.R. tests for the event, set for March 27 in Los Angeles.                                                                                                                                                                                                                                                                                                                                                           , By Brooks Barnes                                                                                                                                                                                                                                                                                                                                                                                                                            , After much internal discussion, the Academy of Motion Picture Arts and Sciences has come to an agreement on coronavirus safety measures for attendees of the 94th Oscars, which will be held on March 27 in Los Angeles: The audience of 2,500 invited guests — including all nominees — will be required to show proof of vaccination against the coronavirus and at least two negative P.C.R. tests.                                      , Performers and presenters also must undergo rigorous testing — but those people will not need to show proof of vaccination, a decision that an academy spokeswoman said on Thursday was in keeping with virus safety protocols on some television sets and return-to-work standards set by Los Angeles County.                                                                                                                              , Under an agreement last year between entertainment unions and the Alliance of Motion Picture and Television Producers, production companies (in this case the academy) have the option to mandate vaccinations for cast and crew. But it is not a requirement, and some companies separate productions into zones, with different testing and social distancing requirements depending on how closely casts and crews need to work together., Face covering requirements also will vary, the academy said. Nominees and their guests will be seated in the orchestra and parterre areas of the Dolby Theater and will not be required to wear masks. These attendees will be seated with more spacing than usual. The Dolby seats 3,317 people and 2,500 people will be invited, the academy said.                                                                                        , Those in the mezzanine may be required to wear masks, as they will sit shoulder-to-shoulder. Infections are declining rapidly in Los Angeles County, and the academy said it was consulting with government officials, infectious disease experts and an independent vendor, Cosmos Health Solutions, on a policy.                                                                                                                          , Last week, following a report in The Hollywood Reporter that the academy was planning to forgo a vaccine mandate across the board, the organization was pummeled on social media by fans, stars, politicians and others for what appeared to be an effort to accommodate unvaccinated celebrities. Seth MacFarlane, who hosted the Oscars in 2013, was among those who criticized the academy on Twitter.                                   , The academy declined to say anything publicly about The Hollywood Reporter’s article, but officials insisted that no decisions had been made.                                                                                                                                                                                                                                                                                               , Coronavirus safety protocols have been changing rapidly as infections have declined. On Tuesday, Disney eased its mask mandate for fully vaccinated theme park visitors in California and Florida. This week, the Coachella Valley Music and Arts Festival said attendees (up to 125,000 fans a day in the prepandemic era) would not be required to be vaccinated, tested or masked.                                                       , According to government data, 1,713 coronavirus-positive patients were hospitalized in Los Angeles County as of Thursday, a 54 percent decline since Feb. 1. Over the last week, the county has reported an average of about 4,100 new cases per day, a decline of 77 percent from two weeks ago.                                                                                                                                           , The academy’s decision puts it at odds with some award shows that are scheduled to take place in the weeks before the Oscars, including the Critics Choice Awards on March 13. Joey Berlin, the force behind the awards, told The Hollywood Reporter that everyone involved would be vaccinated. “I can’t invite people to a show where they’re not going to feel safe,” he said.                                                           , The academy emphasized on Thursday that it would be in direct touch with nominees and studios to walk them through the various safety requirements.                                                                                                                                                                                                                                                                                         , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/core-inflation-rate </td>
   <td style="text-align:left;"> 2022-02-18 08:19:00 </td>
   <td style="text-align:left;"> Japan Core Inflation Rate Eases </td>
   <td style="text-align:left;"> The core consumer price index in Japan, which excludes fresh food but includes fuel costs, increased 0.2% in January 2022 over the same month in the previous year, slowing from a 0.5% rise in the preceding month and missing forecasts for a 0.3% increase. The data has posted a year-on-year increase every month since September, but January’s growth marked the slowest rise in three months. Japan’s core inflation rate, which will be among the factors the Bank of Japan will consider in its next policy meeting scheduled at the middle of March, remains well below the central bank’s 2% target. The moderate price increases in the world’s third-largest economy contrasted with sharp gains in other advanced economies, as sluggish wage growth discourages firms from hiking prices in Japan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-18 08:18:00 </td>
   <td style="text-align:left;"> Japan Inflation Rate Slows to 0.5% in January </td>
   <td style="text-align:left;"> Japan's consumer prices rose by 0.5% yoy in January 2022, easing from a 0.8% gain a month earlier which was the highest figure in 2 years but pointing to the fifth straight month of increase. Cost moderated for housing (0.3% vs 0.7% in December), culture &amp; recreation (0.6% vs 3.9%), and  miscellaneous (1.1% vs 1.3%). In addition, prices dropped further for transport (-7.5% vs -7.5%), medical care (-0.1% vs -0.1%), and furniture and household utensils (-0.6% vs -0.8%). By contrast, food inflation stayed at a 16-month high (at 2.1%), while education inflation was unchanged (at 1.2%). Meantime, prices rose faster for both clothes &amp; footwear (1.3% vs 0.3%), fuel, light and water charges (12.7% vs 11.2%), Core consumer prices gained 0.2% yoy, the least in three months, after a 0.5% rise in December, missing market forecasts of 0.3% and remaining well below the BoJ’s 2% target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-18 08:18:00 </td>
   <td style="text-align:left;"> Gold Hits 36-week High </td>
   <td style="text-align:left;"> Gold increased to a 36-week high of 1901 USD/t.oz,  extending its upward momentum to levels not seen since June of 2021, as mounting tensions between Russia and the West over Ukraine lifted bullion's safe-haven appeal.  NATO said it had not seen Russia pulling back troops from Ukraine's borders, while Russian news reported mortars fired in eastern Ukraine. Aside from safe-haven bids, minutes from the Federal Reserve's last meeting showed policymakers might not be as hawkish as investors feared. On top of that, a disappointing US jobless claims report has supercharged existing bullish momentum for the yellow metal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60411616?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-18 07:34:18 </td>
   <td style="text-align:left;"> AirAsia boss calls on governments to be 'brave' and open borders </td>
   <td style="text-align:left;"> The boss of one of Asia's biggest airlines has called on governments in the region to open their borders for the sake of people's livelihoods.                                                                                                                    , "Politicians have to be brave," AirAsia founder Tony Fernandes told the BBC.                                                                                                                                                                                      , Cross-border tourism, which accounted for 12% of South East Asia's GDP in 2019, was hit hard by Covid-19 rules.                                                                                                                                                   , He was speaking at the Singapore Airshow, which returned this week to the city-state after two years of tough travel restrictions.                                                                                                                                , "It's time to take a deep breath and assess the facts... Having borders closed isn't logical anymore because Omicron is in society," the Malaysian low-cost carrier's chief executive said.                                                                       , "Now we have to protect people's livelihoods and economies," he added.                                                                                                                                                                                            , Like most airlines around the world, AirAsia reported a massive loss in 2020. But while low-cost international carriers in Europe and North America enjoyed a rebound in 2021 as travel rules were relaxed, Asian airlines slumped even further.                  , Ireland's Ryanair, for example, more than tripled its year-on-year revenue in the third quarter of 2021. In the same period, AirAsia's dropped by a third.                                                                                                        , According to the International Air Transport Association (IATA), Asia-Pacific was the only region in the world that failed to register any significant improvement in air traffic by the end of 2021.                                                             , While some Asian countries, such as China and Japan have completely sealed off their borders to outsiders, others like Singapore have made tentative moves into less restrictive travel through selected Vaccinated Travel Lanes (VTLs).                          , It guarantees virtually quarantine-free entry into Singapore, but flights are limited and often more expensive.                                                                                                                                                   , Other similar schemes in the region - designed to encourage tourism - involve extensive paperwork as well as multiple costly Covid tests and short periods of compulsory isolation.                                                                               , "To me, opening our borders means no quarantine, no form-filling, no constant testing," Mr Fernandes said.                                                                                                                                                        , "It's time to move on and get on with our lives," he added.                                                                                                                                                                                                       , In spite of the continued restrictions, the return of the Singapore Airshow was hailed by many as a sign of confidence in the region's aviation industry.                                                                                                         , All of the world's biggest aerospace players were in attendance and most were cautiously optimistic that 2022 will be a better year for Asia.                                                                                                                     , "We let governments here take the lead and we follow their pace", said Ted Colbert, the US-based chief executive of Boeing Global Services. "But we're prepared for a comeback and we're excited about that happening."                                           , "We're expecting inter-regional travel to come back soon and for the full market to return to normal by 2023 or 2024," he added.                                                                                                                                  , But regional industry experts say a lot more needs to be done to ensure the industry's full recovery in the short-term, especially when it comes to building a more cohesive travel policy between governments.                                                   , "Each country in Asia sets its own rules, often fast-changing rules, which makes it risky and complicated for travellers," Henk Ombelet from aviation analysts Cirium said. "So it ends up that most opt to just not travel, or at most just travel domestically.", The uncertainty surrounding snap restrictions, or potential new virus variants, means that passenger services have become a less reliable source of income for companies in the long-term.                                                                        , Mr Colbert highlights Boeing's increasing focus on air cargo, something that has been accelerated by high shipping costs and which he says is forecast to grow by 70% by 2040.                                                                                    , Meanwhile, AirAsia moved into new businesses, including food delivery, digital banking and e-commerce, while many of its planes remained grounded.                                                                                                                , To reflect this change the airline's parent company last month changed its name from AirAsia Group to Capital A.                                                                                                                                                  , But Mr Fernandes denies the shift into different areas shows a lack of confidence in AirAsia's core business.                                                                                                                                                     , "People will always need to fly. At the moment people are desperate to spend a weekend in Phuket or Langkawi or wherever. When borders fully open, there's going to be a lot of 'revenge travel'."                                                                , "I believe this is the beginning of the end. I'm aware I've said that a few times before, but I do believe we're on the road to recovery."                                                                                                                        , This video can not be played                                                                                                                                                                                                                                      , A fresh perspective on how Hitler brutally seized and kept power                                                                                                                                                                                                  , Get ready for the final series with this sneak peek                                                                                                                                                                                                               , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/17/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-02-18 07:03:01 </td>
   <td style="text-align:left;"> Stock futures are flat after Dow suffers its worst day of the year </td>
   <td style="text-align:left;"> , Stock futures were flat in overnight trading Thursday following the Dow Jones Industrial Average's worst day of 2022 as investors dumped risk assets amid geopolitical concerns.                                                                                                                                                                                 , Futures on the blue-chip Dow were up by 30 points. S&amp;P 500 futures and Nasdaq 100 futures both edged 0.1% higher.                                                                                                                                                                                                                                                , Wall Street suffered a steep sell-off on Wednesday, with the Dow falling more than 600 points for its biggest daily drop since end of November. The S&amp;P 500 dropped more than 2% to break a two-day winning streak, while the Nasdaq Composite declined 2.9%.                                                                                                    , Investors continued to be on edge about the ongoing tensions between Russia and Ukraine. Ukraine accused pro-Russian separatists of attacking a village near the border. In the U.S., meanwhile, Secretary of State Antony Blinken was headed to the United Nations to make an urgent appeal against an invasion.                                                , "A further escalation of tensions in the near term could roil markets due to the potential impact on a tenuous global supply chain, particularly as the Fed prepares for its first-rate hike in years," said Peter Essele, head of portfolio management at Commonwealth Financial Network. "A perfect storm may be on the horizon if calmer heads don't prevail.", Investors have been grappling with the outlook for Federal Reserve policy. St. Louis Fe President James Bullard, who had just called for aggressive action, warned that inflation could get out of control without rate hikes.                                                                                                                                   , Major averages are on pace for their second negative week in a row. The Dow is down 1.2% week to date, while the S&amp;P 500 and the Nasdaq have fallen 0.9% and 0.5% this week, respectively.                                                                                                                                                                       , "Wall Street is feeling very jittery as it looks to the left and sees intensifying geopolitical risks with the Ukraine situation and then it looks to the right and sees the potential for aggressive Fed tightening," Edward Moya, senior market analyst at Oanda, said in a note.                                                                              , Roku shares dropped as much as 12% in extended trading after the video-streaming company reported a revenue miss and issued a weaker-than-expected guidance.                                                                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/abbott-recalls-some-similac-other/story.aspx?guid={F6BF9678-033B-4B6E-9CE5-D0CCE88D1A0E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 06:54:27 </td>
   <td style="text-align:left;"> Abbott recalls some Similac, other powder baby formulas due to Salmonella, Cronobacter complaints - MarketWatch </td>
   <td style="text-align:left;"> Abbott Laboratories 
        ABT,
        -2.51%
       said late Thursday it is voluntarily recalling powder baby formulas, including its best-selling Similac, made in one plant in Michigan after it received four consumer complaints related to the bacteria Cronobacter sakazakii or Salmonella Newport in infants who had consumed powder infant formula made in the factory. "During testing in our Sturgis, Mich., facility, we found evidence of Cronobacter sakazakii in the plant in non-product contact areas. We found no evidence of Salmonella Newport. This investigation is ongoing," Abbott said. "Importantly, no distributed product has tested positive for the presence of either of these bacteria, and we continue to test." Despite detecting no pathogens, the company is recalling powder formulas manufactured in the plant with an expiration of April 1, 2022 or after, it said. The recall does not affect Abbott liquid formulas, powder formulas, or nutrition products from other facilities, Abbott said. "We're taking this action so parents know they can trust us to meet our high standards, as well as theirs. We deeply regret the concern and inconvenience this situation will cause parents, caregivers and health care professionals," said Joe Manning, executive VP of nutritional products. Shares of Abbott edged higher in the extended session Thursday after ending the regular trading day down 2.5%., Institutional investors haven't held such a small position in tech shares in more than a decade, according to a survey by Bank of America.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/dlr:us </td>
   <td style="text-align:left;"> 2022-02-18 06:27:08 </td>
   <td style="text-align:left;"> Digital Realty earnings above expectations at 3.71 USD </td>
   <td style="text-align:left;"> Digital Realty (DLR) released earnings per share at 3.71 USD, compared to market expectations of 0.32 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-18 06:25:00 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield Slips from 3-Year High </td>
   <td style="text-align:left;"> The yield on Canada's 10-year government bond eased to 1.92% after hitting a three-year high of 1.995% on February 16th, as heightened tensions between Russia and Ukraine reignited a rush to safer investments such as government bonds. President Biden reiterated a warning that Russia could invade Ukraine in the coming days. Earlier, NATO had stated it had not seen Russia pulling back troops from Ukraine's borders, while Russian backed separatists and government forces accused each other of breaking cease-fire rules. On the data front, Canada’s annual inflation rate climbed to a 30-year high of 5.1% in January, adding more pressure on the Bank of Canada to hike interest rates during the next monetary policy meeting in March, which should be followed by five more hikes through the rest of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/producer-price-inflation-mom </td>
   <td style="text-align:left;"> 2022-02-18 06:03:09 </td>
   <td style="text-align:left;"> New Zealand Producer Price Inflation Slows in Q4 </td>
   <td style="text-align:left;"> Producer input prices in New Zealand increased 1.1 percent quarter-over-quarter in the last three months of 2021, slowing from a 1.6 percent advance in the previous period. Main upward pressure came from manufacturing industries (3.7 percent vs 6.0 percent in Q3), transport and warehousing (3.0 percent vs 3.5 percent), and agriculture, forestry, and fishing (2.3 percent vs 2.2 percent). Meanwhile, output prices rose 1.4 percent, slowing from a 1.8 percent gain in the third quarter, mostly underpinned by prices in mining (9.6 percent vs 4.0 percent); agriculture, forestry, and fishing (4.3 percent vs 6.3 percent), and transport and warehousing (3.7 percent vs 2.3 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/17/stocks-making-the-biggest-moves-after-hours-roku-shake-shack-sunrun-more.html </td>
   <td style="text-align:left;"> 2022-02-18 05:57:06 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Roku, Shake Shack, Sunrun &amp; more </td>
   <td style="text-align:left;"> , Check out the companies making headlines after the bell:                                                                                                                                                                                                                                                                                              , Roku — Shares of video-streaming company dropped 12% in extended trading after the firm's fourth-quarter revenue missed expectations. Roku reported revenue of $865 million last quarter, versus $894 million as expected by analysts, according to Refinitiv. The company also issued first-quarter revenue guidance below consensus.                , Shake Shack — The fast food chain saw its shares plunge 10% in after-hours trading after the company forecast quarterly revenue below estimates, as the Omicron variant led to labor shortages and store closures.                                                                                                                                    , Sunrun — Shares of the clean energy company fell 3% in extended trading after a wider-than-expected quarter loss. Sunrun posted a quarterly loss of 19 cents per share, more than the 4 cents per share estimate, according to Refinitiv.                                                                                                             , Dropbox — Shares of the cloud company dipped 1% in after-hours trading even after a better-than-expected quarterly report. Dropbox reported earnings of 32 cents per share in the fiscal fourth-quarter, exceeding Wall Street analysts' forecasts. The company also announced a repurchase of an additional $1.2 billion of its Class A common stock.,                                                                                                                                                                                                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 05:44:10 </td>
   <td style="text-align:left;"> Canada Stocks End at 2-Week Low </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, closed 1% lower at 21,176 on Thursday, the lowest in two weeks amid a rout in global equities, as losses in tech and energy stocks more than offset gains in materials and utilities. Market sentiment continued to be dominated by geopolitical tensions in Ukraine, while protests in Ottawa and new quarterly results also weighed. Russian backed separatists in eastern Ukraine and government forces have accused each other of breaking cease-fire rules, lifting appetite for safe-haven assets. Meanwhile, police officers started distributing warnings to truckers participating in Ottawa’s blockade, as imminent police action is expected to bring an end to the three-week old protest. Earlier, Prime Minister Justin Trudeau had sharpened his tone against the movement, calling it “a threat” to Canada’s democracy. On the earnings front, Canadian Tire beat quarterly revenue and profit estimates, driven by sales of sporting goods, garden equipment and home decor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/shake-shack-stock-heads-lower/story.aspx?guid={FB03DA10-854C-4AB5-A87F-62A0225A4E32}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 05:24:29 </td>
   <td style="text-align:left;"> Shake Shack stock heads lower after wider Q4 loss, ongoing uncertainty - MarketWatch </td>
   <td style="text-align:left;"> Shares of Shake Shack Inc. 
        SHAK,
        -4.55%
       headed more than 6% lower in the extended session Thursday after the fast-casual restaurant reported a fourth-quarter loss that was greater than Wall Street expected and said the timing of a full recovery is still uncertain. Shake Shack said it lost $9.7 million, or 25 cents a share, in the fourth quarter, compared with a loss of $19.4 million, or 50 cents a share, in the year-ago period. Adjusted for one-time items, the company lost 11 cents a share in the quarter. Revenue rose 29% to $203.3 million, the company said. Analysts polled by FactSet expected a loss of 18 cents a share on sales of $203 million. Digital sales, including orders placed on the Shake Shack app, website and third-party delivery platforms, represented 42% of sales, the company said. Shake Shack guided for first-quarter revenue between $196 million and $201.4 million, and said it would not provide full-year guidance due to "uncertainty and resulting material economic impact" caused by the pandemic. "The timing of a return to pre-COVID sales levels is highly dependent upon the return of the high-traffic areas that contributed to many of the strongest Shack sales, including those most reliant on travel, schools, offices and major gatherings. The timing of that recovery remains unknown today," it said. Shake Shack stock ended the regular trading day down 4.6%. , Nvidia Corp. provided a strong forecast despite supply constraints Wednesday, after doubling profits and producing record sales in the holiday quarter.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 05:16:44 </td>
   <td style="text-align:left;"> Brazil Stocks Snap 7-Day Rally </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, finished 1.4% lower at 113,627 on Thursday, snapping a seven-day rally that sent the index to the highest since September 2021. Market sentiment was pulled down by falling commodities prices and heightened caution in global markets following news of clashes between Russian-backed separatists and the Ukrainian government forces in eastern Ukraine. Heavyweight miner Vale suffered its biggest drop in three months, in line with industry peers, as reports that China’s iron ore stocks stood at their highest levels in three years, which pressured prices of the metal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/money/irs-tax-refunds-2022 </td>
   <td style="text-align:left;"> 2022-02-18 05:16:20 </td>
   <td style="text-align:left;"> Where's my tax refund? IRS sheds light on when it will send the money </td>
   <td style="text-align:left;"> Mark Cuban, the billionaire owner of the Dallas Mavericks in a wide-ranging interview on 'Cavuto: Coast-to-Coast,' explains markets, crypto investing, the potential for increased taxes and how the Biden administration is handling the U.S. economy.                                                                                                                                                                                       , With millions of Americans expecting a tax refund this year, the IRS has one request for those looking to get their money faster: File your return electronically and as soon as possible.                                                                                                                                                                                                                                                    , Nearly three-quarters of filers received a tax refund last year, with an average payment of about $2,800, the IRS said recently – a major influx of money for most households that many Americans depend on.                                                                                                                                                                                                                                  , IRS TAX-FILING SEASON TO KICK OFF ON JAN. 24                                                                                                                                                                                                                                                                                                                                                                                                  , The IRS is already warning of a "challenging" tax season that promises to bring complications and potential delays for taxpayers. That's largely due to the deluge of unprocessed paper returns the agency is working its way through: At the end of December, the IRS had 6 million unprocessed individual returns – a significant increase from its usual backlog of about 1 million unprocessed returns around the beginning of tax season., For taxpayers who choose to file their returns via mail, there could be as long as a four-week wait to retrieve your payment status on the site.                                                                                                                                                                                                                                                                                              , There are some steps that taxpayers can take in order to get their money back faster. Experts have urged taxpayers to file their tax returns as soon as possible, noting that individuals do not need previous returns in order to submit their 2021 returns. Americans are encouraged to file electronically with direct deposit in order to avoid potential delays and receive their return within 21 days.                                 , If you file electronically – as most taxpayers do – you can start tracking the status of your tax refund within 24 hours of filing using the IRS' Where’s My Refund tool.                                                                                                                                                                                                                                                                     , However, for taxpayers who choose to file their returns via mail, there could be as long as a four-week wait to retrieve your payment status on the site.                                                                                                                                                                                                                                                                                     , Still, many taxpayers wind up waiting far longer than 21 days for their refund – and it's often due to simple math mistakes on their tax returns or identity theft delays.                                                                                                                                                                                                                                                                    , Eric Bronnenkant, head of tax at online financial adviser Betterment, said Americans should file their returns as soon as they're ready in order to help avoid tax fraud, because there's a "huge problem" where fraudsters find someone's Social Security number, illegally file a return on their behalf and claim the refund.                                                                                                              , "The best way to mitigate someone illegally filing a return on your behalf is to file as soon as possible and to get ahead of the game," Bronnenkant said.                                                                                                                                                                                                                                                                                    , IRS Commissioner Charles Rettig testifies during a Senate Finance Committee hearing June 8, 2021, on Capitol Hill.  (Tom Williams-Pool/Getty Images / Getty Images)                                                                                                                                                                                                                                                                           , There are fresh challenges facing the IRS – and individual filers – this year: Taxpayers will have to reflect the monthly child tax credit payments and the stimulus checks they received in 2021 on their returns, further complicating matters and increasing the likelihood of errors and delays in processing returns.                                                                                                                    , "Any time you get a tax credit, and you need to reconcile that when you file, you want to make sure you put the correct number down when you file, otherwise that may delay your return and your refund that you might otherwise be entitled to," Bronnenkant said. "Knowing what payments you got up front and appropriately recording those will go far in reducing some of the friction in filing."                                        , Families that received monthly installments of the boosted child tax credit last year will receive a letter – called Letter 6419 – from the IRS informing them of the total amount of the advanced payment they received and the number of qualifying children used to calculate the payments.                                                                                                                                                , Because at least half of the enhanced credit will be paid out as a lump sum when parents receive their 2021 tax return, recipients should keep the letter and use it to accurately reconcile the credit they already received when filing their taxes this year. The information is pertinent to determining how much more money families receive from the credit when they fill out Schedule 8812 and Form 1040.                             , IRS headquarters in Washington on April 13, 2014 (AP Photo/J. David Ake, File / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                  , "There are important steps people can take to ensure they avoid processing delays and get their tax refund as quickly as possible," IRS Commissioner Chuck Rettig told reporters last week. "We urge people to carefully review their taxes for accuracy before filing. And they should file electronically with direct deposit if at all possible; filing a paper tax return this year means an extended refund delay."                      , If taxpayers file an electronic return with no issues and opt to receive the refund via direct deposit, the IRS anticipates the money will arrive within 21 days.                                                                                                                                                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                   , The tax-filing season will end on April 18 this year for most individuals, rather than the usual deadline of April 15, because that's when Emancipation Day will be observed in Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dropbox-shares-pop-8-sales/story.aspx?guid={B90FCCA6-3CE7-478A-8E4F-9B1F4E17EDF4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 05:13:10 </td>
   <td style="text-align:left;"> Dropbox shares pop 8% on sales, earnings beat - MarketWatch </td>
   <td style="text-align:left;"> Shares of Dropbox Inc. 
        DBX,
        -5.30%
       initially popped 8% in extended trading Thursday after the software company reported fiscal fourth-quarter results that exceeded Wall Street analysts' forecasts, and it topped $2 billion in annual sales. The company's board also authorized a repurchase of an additional $1.2 billion of its Class A common stock. Dropbox posted net income of $124.6 million, or 32 cents a share, compared with a loss of $345.8 million, or 84 cents a share, in the year-ago quarter. The company recorded an adjusted earnings of 41 cents a share. Revenue soared 12% to $565.5 million from $504.1 million a year ago. Analysts surveyed by FactSet had expected net income of 37 cents a share on revenue of $558 million. Dropbox's stock has dropped 4% so far this year; the broader S&amp;P 500 index 
        SPX,
        -2.12%
       has slid 8%.                                                                                                                                                                                                                                                                                                                                                 , Palantir Technologies Inc. undefined grew revenue more quickly than anticipated in its latest quarter, though earnings per share fell short of expectations. The software company on Thursday reported a fourth-quarter net loss of $156.2 million, or 8 cents a share, compared with a loss of $148.3 million, or 8 cents a share, in the year-prior quarter. After adjusting for stock-based compensation and other expenses, Palantir earned 2 cents a share, down from 3 cents a share a year earlier, while analysts tracked by FactSet were expecting 4 cents a share. Palantir's revenue rose to $432.9 million from $322.1 million, while analysts surveyed by FactSet had been anticipating $418 million. The company saw a 47% bump in U.S. commercial revenue and a 26% increase in government revenue. Palantir added 34 net new customers during the fourth quarter. Looking to the first quarter, the company anticipates $443 million in revenue, whereas the FactSet consensus was for revenue of $439 million. The company expects a 23% adjusted operating margin for the first quarter and a 27% adjusted operating margin for the full year. Shares of Palantir have declined 40% over the past three months as the S&amp;P 500 undefined has lost 5%., Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-books-biggest-drop-since/story.aspx?guid={DDE1E5C0-1BF3-4058-9F9F-4E6287F35E8E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 05:06:21 </td>
   <td style="text-align:left;"> Dow books biggest drop since November as stocks end sharply lower on renewed Ukraine fears - MarketWatch </td>
   <td style="text-align:left;"> U.S. stock benchmarks closed sharply lower Thursday, with the Dow Jones Industrial Average slumping more than 600 points, amid renewed worries that Russia may soon invade Ukraine. The Dow 
        DJIA,
        -1.78%
       ended about 1.8% lower, while the S&amp;P 500 
        SPX,
        -2.12%
       dropped about 2.1% and the tech-laden Nasdaq Composite 
        COMP,
        -2.88%
       slid around 2.9%, according to preliminary FactSet data. President Joe Biden told reporters Thursday morning that a Russian invasion could happen in the next "several days." Nearly all of the S&amp;P 500's 11 sectors finished lower in Thursday's slump, with losses led by information technology, preliminary FactSet data show. The Dow's 1.8% slide was its largest daily drop since Nov. 30, according to Dow Jones Market Data. , U.S. stock indexes fall modestly at Thursday's start of regular trade, as investors wrestle with the threat of military conflict between Ukraine and Russia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 05:03:00 </td>
   <td style="text-align:left;"> US Stocks Close at 3-Week Lows </td>
   <td style="text-align:left;"> US securities deepened losses to close around three-week lows on Thursday, with the Dow Jones ending 623 points lower, the S&amp;P 500 dropping 2.1%, and the Nasdaq slipping 2.5%, as war woes in Eastern Europe intensified after President Biden reiterated a warning that Russia could invade Ukraine in the coming days. Earlier, NATO had stated it had not seen Russia pulling back troops from Ukraine's borders, while Russian news reported mortars fired in eastern Ukraine. As risk-aversion weighed down on bond yields, banking stocks fell, including Goldman Sachs and Wells Fargo, which had released upbeat forward guidance. On the other side earnings from Walmart, Cisco and Applied Materials topped expectations. Traders also digested fresh economic data, with initial claims unexpectedly rising last week and housing starts falling much more than expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/17/business/google-creates-100-million-fund-for-skills-training-program.html </td>
   <td style="text-align:left;"> 2022-02-18 04:44:58 </td>
   <td style="text-align:left;"> Google Invests in Skills Training Program for Low-Income Workers - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The project is a big bet on scaling up programs that have proved effective in lifting low-income workers into middle-class jobs and careers.                                                                                                                                                                                                                                                                                                                                , By Steve Lohr                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Google said on Thursday that it was creating a $100 million fund to sponsor an ambitious project to expand effective skills training and job placement programs for low-income Americans.                                                                                                                                                                                                                                                                                   , The Google-backed initiative is targeting a big problem: how to find, train and create paths to good jobs in the modern economy for the nearly two-thirds of American workers who do not have a four-year college degree.                                                                                                                                                                                                                                                   , “I genuinely think this is one of the important areas for society to figure out,” said Sundar Pichai, the chief executive of Google’s parent company, Alphabet, in an interview. If the project is successful, Mr. Pichai said, he hopes it will be a “template for other companies to do more” and show policymakers that there are better-performing alternatives to traditional government training efforts.                                                             , The tech giant is working with three nonprofit groups on the effort: Year Up, which focuses on upward mobility programs for the disadvantaged; Merit America, an organization that offers tech training programs for adults without a bachelor’s degree; and Social Finance, which designs student-friendly financing and repayment plans.                                                                                                                                  , The training organizations are paid a portion of their costs upfront and receive additional payments only if their graduates land and keep higher-paying jobs. The program will combine Google philanthropy with loan repayments from students. The loans will carry no interest, and students will begin repaying only if they get a job that pays at least $40,000 a year. The payments will be about $100 a month and continue for a maximum of five years.              , The Google fund will pay to start and support the program, since not all students will graduate and secure higher-paying jobs. But loan repayments from successful students will help support training for others in the future. The Google fund hopes to fuel total wage gains of $1 billion for 20,000 training program graduates.                                                                                                                                        , The three organizations working with Google are indicative of newer trends in job training and hiring. They focus on results — graduates getting higher-paying jobs — rather than numbers of people passing through their programs. They are advocates for hiring based on demonstrated skills instead of screening by college degrees. And they are all experimenting with ways to make programs more self-sufficient financially and less dependent on charitable support., “This is a really serious effort to put philanthropic money into programs that have the elements that have proved effective,” said Lawrence Katz, a labor economist at Harvard University.                                                                                                                                                                                                                                                                                  , The job programs, Year Up and Merit America, will receive grants to train students in technical skills with content from Google career certificate courses in information technology support, data analytics, project management and user experience design. Both nonprofits already use the Google coursework, which provides general technical training but does not teach students to master Google software tools.                                                      , But a major part of successful training programs, experts agree, is what they do beyond teaching technical skills. The programs also emphasize so-called soft skills like teamwork, communication and willingness to learn new things. They often provide help with arranging child care and transportation. They have career coaches, social workers and counselors, and foster peer groups and alumni networks.                                                           , “Skills and competencies are important, but so is building up a person’s social capital,” said Gerald Chertavian, founder and chief executive of Year Up.                                                                                                                                                                                                                                                                                                                   , Begun more than two decades ago, Year Up is now a national organization that caters to low-income workers from 18 to 26 years old. It includes three to six months of technical training followed by a six-month internship at a company. Eighty percent of its graduates are placed in jobs within four months, at an average starting salary of $44,000, more than double their previous income, the organization says.                                                   , Social Finance, which is managing the investment program, is looking to add a few more job training groups this year. An independent research firm, MDRC, will evaluate the performance of the training and job placement programs over time.                                                                                                                                                                                                                               , “We’ll allocate more funds to whoever is delivering better results,” said Tracy Palandjian, chief executive of Social Finance, which is not related to the online lender SoFi. “It’s all about impact.”                                                                                                                                                                                                                                                                     , Merit America has grown rapidly since it began offering courses in 2018. From the outset, it was a hybrid program, with self-paced online training, in-person meetings once a week with fellow students and one-on-one sessions with coaches.                                                                                                                                                                                                                               , So when the pandemic shutdowns hit, Merit America was well placed to make the shift to remote training. It is growing rapidly — on track to reach 2,500 students this year, more than double the number in 2021.                                                                                                                                                                                                                                                            , The Google-fund backing “puts jet fuel in our engine, allowing us to scale up as never before,” said Connor Diemand-Yauman, one of the founders of Merit America, where he is co-chief executive.                                                                                                                                                                                                                                                                           , Merit America participants span demographics, but they are typically in their early 30s, with a decade or more of working experience, often in low-paid jobs in restaurants and retail. The program includes three months of skills and workplace training, followed by a job-placement phase of a few months.                                                                                                                                                              , Merit America’s graduation rate is more than 80 percent, and nearly all the graduates are getting jobs, the program says. Graduate starting salaries now average more than $45,000, at least $18,000 more than before the program. Both salaries and wage gains have been rising with recent cohorts.                                                                                                                                                                       , The nonprofit is financed largely by philanthropy and repayments on no-interest loans from graduates in higher-paying jobs, which is the model being adopted for the Google fund.                                                                                                                                                                                                                                                                                           , Sandra Massie, a single mother in Virginia, had worked for nine years in restaurant jobs when she saw an online ad for Merit America. The skills training was based on the Google IT support certificate course, which she completed online while still working at a restaurant chain.                                                                                                                                                                                      , But, Ms. Massie said, the peer learning with students from similar backgrounds and one-on-one sessions with coaches were crucial. “It’s a network of support that really gets you believing that this type of change is possible in your life,” she said.                                                                                                                                                                                                                   , With the nonprofit’s help, Ms. Massie got a job offer in 2019, before she finished her training. She now works for a software consulting firm, Intact Technology, and is transitioning from a tech support role to managing small-team projects for clients.                                                                                                                                                                                                                , Today, Ms. Massie, 34, earns $75,000 a year, about twice as much as in her last restaurant job. She has health care and vacation time, and the company contributes to her 401(k) retirement plan. She has set up a college savings plan for her 9-year-old daughter and owns a home.                                                                                                                                                                                        , “My life has changed a lot,” Ms. Massie said.                                                                                                                                                                                                                                                                                                                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60420157?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-18 04:30:25 </td>
   <td style="text-align:left;"> Elon Musk says US is trying to 'chill' his free speech </td>
   <td style="text-align:left;"> Tesla boss Elon Musk has accused US regulators of targeting him for "unrelenting investigation" because of his criticism of the government.                                                                                             , In a court filing, the billionaire says the Securities and Exchange Commission has engaged in "outsized efforts" to monitor the firm that "seem calculated to chill his exercise" of free speech.                                       , The letter heightens the battle between Mr Musk and financial regulators over his social media activity.                                                                                                                                , His Twitter posts often move markets.                                                                                                                                                                                                   , In 2018, the SEC ordered Mr Musk to submit to increased oversight of his posts about Tesla as part of a settlement into claims that he misled investors in 2018 with a post about taking the electric car company private.              , The SEC has repeatedly raised questions since about Mr Musk running afoul of the agreement, in which Mr Musk agreed to give Tesla officials pre-approval of posts about the company.                                                    , In November, regulators subpoenaed the firm, requesting information about its governance processes related to the order.                                                                                                                , That month, Mr Musk asked his more than 70 million Twitter followers whether he should sell 10% of his Tesla shares, driving shares lower.                                                                                              , In the letter to Judge Alison Nathan, who is overseeing the 2018 settlement, the billionaire's attorney Alex Spiro accused regulators of "weaponizing the consent decree by using it to try to muzzle and harass Mr. Musk and Tesla".   , "The SEC seems to be targeting Mr. Musk and Tesla for unrelenting investigation largely because Mr. Musk remains an outspoken critic of the government," he wrote on behalf of Mr Musk and Tesla.                                       , "The SEC's outsized efforts seem calculated to chill his exercise of First Amendment rights rather than to enforce generally applicable laws in even-handed fashion".                                                                   , He said the SEC had opened "serial investigations" without seeking guidance from the court and that the agency was overdue to distribute to investors the $40m in penalties it collected as part of the 2018 settlement.                , The SEC declined to comment.                                                                                                                                                                                                            , Mr Musk's Twitter musings on topics from Tesla to crypto currency have frequently appeared to move market prices.                                                                                                                       , He has used his perch to criticise the SEC, saying oversight at the agency was "broken".                                                                                                                                                , Mr Musk has also criticised US President Joe Biden for not acknowledging the contributions of SpaceX or Tesla, most recently dismissing the president as a "damp [sock emoji] puppet".                                                  , But Professor James D Cox, who teaches corporate and securities law at Duke University, said the SEC is responding to Mr Musk's decision to repeatedly flout a court order, not his other antics.                                       , Executives at publicly traded companies are bound by protocols governing disclosure of information, he said.                                                                                                                            , "This isn't a question of the SEC targeting him," he said. "They're doing it because he is brazenly ignoring the order of the SEC that has the imprimatur of the federal court system."                                                 , In addition to the financial regulator's subpoena, Tesla faces a racial discrimination lawsuit from the California Department of Fair Employment and Housing and a safety probe from the National Highway Traffic Safety Administration., A fresh perspective on how Hitler brutally seized and kept power                                                                                                                                                                        , Get ready for the final series with this sneak peek                                                                                                                                                                                     , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                  , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 04:30:00 </td>
   <td style="text-align:left;"> US Equities Extend Losses on War Jitters </td>
   <td style="text-align:left;"> US equity securities extended losses towards the end of Thursday’s session, with the Dow Jones erasing almost 600 points, the S&amp;P 500 dropping as much as 1.9%, and the Nasdaq slipping over 2.5%, as war woes in Eastern Europe intensified after President Biden reiterated a warning that Russia could invade Ukraine in the coming days. Earlier, NATO had stated it had not seen Russia pulling back troops from Ukraine's borders, while Russian news reported mortars fired in eastern Ukraine. As risk-aversion weighed down on bond yields, banking stocks fell, including Goldman Sachs and Wells Fargo, which had released upbeat forward guidances. Among other earnings, Walmart, Cisco and Applied Materials topped expectations. Traders also digest fresh economic data, with initial claims unexpectedly rising last week and housing starts falling much more than expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/17/business/economy/could-wages-and-prices-spiral-upward-in-america.html </td>
   <td style="text-align:left;"> 2022-02-18 04:16:24 </td>
   <td style="text-align:left;"> Could Wages and Prices Spiral Upward in America? - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , A labor shortage that began as businesses reopened from pandemic lockdowns is helping to push up pay. The Fed is watching carefully.                                                                                                                                                                                                                                                                                                                                                                                            , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Amazon, Bank of America and Chipotle are among a spate of companies raising wages this year as they compete for workers in a labor market with more open positions than unemployed job seekers.                                                                                                                                                                                                                                                                                                                                 , But that positive development for workers could morph into a challenge for the Federal Reserve if climbing wages help to keep inflation high, prompting employees to ask for even more money and generating an upward spiral.                                                                                                                                                                                                                                                                                                   , So far, many economists think such a situation can be kept at bay. But the Fed is closely monitoring inflation and pay data to assess the risk, because the consequences if wages and prices begin to drive each other steadily higher could be serious, requiring a response from the central bank that could be economically painful.                                                                                                                                                                                         , The Fed is already poised to raise interest rates in March in an attempt to begin cooling off the economy as inflation runs at its fastest pace in 40 years. But if it needed to restrain a self-perpetuating burst in wages and prices, officials might decide to adjust policy more drastically. Higher interest rates could abruptly hit the brakes on lending and spending, potentially sending the United States into recession and foiling central bankers’ hopes of guiding growth gently toward a more sustainable path., “I think we’re much more likely to have something messier than a magical soft landing,” said Olivier Blanchard, an economist at the Peterson Institute for International Economics. “The wage evolutions are going to be the thing to look at.”                                                                                                                                                                                                                                                                                 , Wages are already rising sharply. Pay for restaurant servers and hotel workers began to increase notably in 2021 as companies, reopening after lockdown, struggled to rehire people quickly. Now a wide array of industries are giving raises: The government’s latest employment report showed pay accelerating sharply for education and health workers, manufacturers, and professional and business services.                                                                                                               , Average hourly earnings jumped 5.7 percent in the year through January, a full percentage point more than economists had forecast.                                                                                                                                                                                                                                                                                                                                                                                              , Earnings calls are replete with chief executives explaining that they are increasing pay to attract and retain talent. Unions have won pay bargaining fights. And the White House regularly celebrates signs that power in the work force seems to have shifted toward employees and away from employers.                                                                                                                                                                                                                       , For the most part, that’s good news for labor. But economists have increasingly warned that the confluence of economic trends shaping up now — high inflation, a sense among consumers that prices might stay high for a while and a strong labor market that has handed workers bargaining power — could set the stage for a situation in which wage growth and prices feed off each other.                                                                                                                                    , “The combination of very high inflation, hot wage growth and high short-term inflation expectations means that concerns about falling into a wage-price spiral deserve to be taken seriously,” Goldman Sachs economists wrote in a note last week.                                                                                                                                                                                                                                                                              , That would be a big shift. America has not experienced a wage-price spiral since the 1970s and early 1980s, when rapid inflation and skyrocketing wages seemed to perpetuate each other. The Fed lifted interest rates to double digits and caused a painful recession to bring prices under control. Both wage growth and inflation have been slow in the decades since — until now.                                                                                                                                           , But even if wages and prices are both rising now, it is not clear that they are egging each other on yet, which is a crucial distinction. In fact, labor market experts point out three big reasons to doubt that a wage-price spiral will happen today.                                                                                                                                                                                                                                                                        , Chief among them: Productivity growth looks strong. If each individual worker can churn out more goods and services, companies should be able to pay more without hurting their profit margins and leading them to pass along the higher costs. Nick Bunker, an economist at the Indeed Hiring Lab, said recent productivity data was an encouraging sign but not a definitive one.                                                                                                                                             , “It’s really hard to observe in real time,” he said of the data, noting that the numbers jump around a lot. “I think it’s something to keep an eye on.”                                                                                                                                                                                                                                                                                                                                                                         , It is also unclear just how much wage bargaining power employees have, even with employers eager to hire. Wage growth appears to have been falling behind price increases for many income groups in recent months, suggesting that workers aren’t managing to persuade their companies to compensate them fully for rising costs. Unionization is much lower than in the 1970s, which could leave workers with fewer tools to bargain up pay.                                                                                   , If that begins to crimp consumers’ ability to buy new couches and cars, it could cause demand to moderate, naturally restraining inflation.                                                                                                                                                                                                                                                                                                                                                                                     , And the tie between wages and prices has been tenuous in recent decades. While research has found a link between the two in the 1960s and 1970s, the relationship collapsed after the early 1980s and has remained tame since.                                                                                                                                                                                                                                                                                                  , “The relationship between wage growth and services inflation just isn’t that tight,” said Laura Rosner-Warburton, an economist at MacroPolicy Perspectives. “Yes, you will see more inflation from wages in 2022. The question is how much?”                                                                                                                                                                                                                                                                                    , While a wage-price spiral is on a “large list of risk factors” that the administration is closely watching, the “dominant forecast” is that the labor market will stay strong and price gains will moderate this year, said Jared Bernstein, a member of the White House Council of Economic Advisers.                                                                                                                                                                                                                          , Wall Street economists generally think inflation will fade toward 3 percent this year, based on recent analyst notes and interviews. A recent survey from the Federal Reserve Bank of New York showed that consumers, who had been penciling in higher inflation in the years ahead, have begun to lower their expectations for price increases.                                                                                                                                                                                , But several forecasters said there was room for humility and wariness, because the pandemic economy has repeatedly confounded expectations. It has also drastically changed America’s economic backdrop.                                                                                                                                                                                                                                                                                                                        , “The last 20 years have been years of very low inflation, very stable inflation,” Mr. Blanchard said. Before the coronavirus, inflation had hovered around — and then below — 2.5 percent for decades. Today, it has jumped to 7.5 percent.                                                                                                                                                                                                                                                                                     , As prices for products including gas, steaks, bacon and camping equipment climb rapidly, eating into paychecks and dominating headlines, consumers are more likely to take note and ask for better pay.                                                                                                                                                                                                                                                                                                                         , “Things change completely when inflation is a big number,” Mr. Blanchard said. “Salience changes.”                                                                                                                                                                                                                                                                                                                                                                                                                              , There are signs that wages are feeding into price increases, at the margin. Prices have recently begun to rise sharply for core services, a set of purchases outside of health care, rent and transportation for which wages tend to make up a major cost of production.                                                                                                                                                                                                                                                        , “That was concerning,” said Alan Detmeister, an economist at UBS who formerly led the Fed’s wage and price section. But, he added, it is hardly conclusive.                                                                                                                                                                                                                                                                                                                                                                     , More anecdotally, stories of workers winning big wage increases in a tight labor market abound.                                                                                                                                                                                                                                                                                                                                                                                                                                 , While wages in lower-qualification fields like leisure and hospitality have been rising rapidly for months, professional pay may also be on the cusp of picking up: Banks have been making big base salary increases, and Amazon will raise its maximum base salary for corporate and technology workers to $350,000 from $160,000 as it competes for a limited pool of highly trained employees.                                                                                                                               , Amazon, which has also increased wages for warehouse employees, has raised prices partly in response.                                                                                                                                                                                                                                                                                                                                                                                                                           , “With the continued expansion of Prime member benefits and the increased member usage that we’ve seen, as well as the rise in wages and transportation costs, Amazon will increase the price of our Prime membership in the United States,” Brian T. Olsavsky, the company’s chief financial officer, said on a Feb. 3 earnings call. The monthly price is rising to $14.99 from $12.99, and the annual membership is jumping to $139 from $119.                                                                                , “This is our first price increase since 2018,” Mr. Olsavsky noted.                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Other companies are raising pay but have said they are covering the climbing costs by improving efficiency. That’s the sort of sweet spot the White House and the Fed are hoping for, because it could leave workers earning more without pressuring prices relentlessly up.                                                                                                                                                                                                                                                    , “We do anticipate when we do our annual review process that we will have a nominally higher wage rate increase provided to our associates,” Kevin Hourican, president and chief executive at the food distributor Sysco, said on a Feb. 8 earnings call. “And we have productivity improvement efforts that can help offset those types of increases.”                                                                                                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/wheat </td>
   <td style="text-align:left;"> 2022-02-18 04:04:07 </td>
   <td style="text-align:left;"> Wheat Rebounds on Ukraine-Russia Tensions </td>
   <td style="text-align:left;"> Chicago wheat futures bounced back above to $7.9 per bushel, near a two-week high of $8.1 hit earlier in the week amid heightened tensions in Eastern Europe. Russian backed separatists and government forces accused each other of breaking cease-fire rules, reigniting fears of an imminent war between two of the world’s biggest wheat exporters while it could augur well for US wheat. Additionally, low inventories in Canada and in the US, the third and second-largest exporters globally, added to upside risks. Total stocks of wheat in Canada were 38% down on the year at the end of 2021, as yields were poor due to drought in farms in the Prairie region. Droughts also hampered US production with sales and exports in the week ending February 3rd totaling 17.3 million tonnes, 21% lower than USDA projections of 22.05 million tonnes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/kkr-sees-rotation-credit-2022/story.aspx?guid={A5C618DB-A4BC-4E14-B93F-E5DDDB0EA8F4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 03:46:07 </td>
   <td style="text-align:left;"> KKR sees rotation into credit in 2022 amid volatility, after record leverage loan volume in 2021 - MarketWatch </td>
   <td style="text-align:left;"> U.S. leveraged finance issuance totaled a record $1.08 trillion in 2021, including $465 billion in high yield loans and $615 billion in U.S. institutional loans, according a report to be published Friday by KKR Credit, a unit of KKR &amp; Co. Inc. 
        KKR,
        -5.87%.
       While most of the eight sub-sets of the credit market turned in positive total returns for 2021, only two of the eight were positive in January: European bank loans (up 0.35% in total return) and U.S. bank loans (up 0.36%). Asia high yield credit had the worst January results with a negative 4.81% return. Overall, CCC-rated bonds have held up well in the face of volatility, KKR said. "In January, while broader credit markets started to weaken under pressure, CCCs, the perceived riskiest part of the market, weathered the storm best," KKR said. CCC-rated bonds outperformed equities in January, KKR said. "We have already started to see the market shift in an unambiguous fashion towards credit and we believe the time for increased credit exposure is now," the firm said., Analysts say Uber, Carvana and, yes, Shopify, will increase sales at an annualized pace of 30% or more.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-end-2/story.aspx?guid={06C3E7B9-FA0D-4712-AEF8-A5422D15C358}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 03:45:11 </td>
   <td style="text-align:left;"> U.S. oil futures end with 2% loss as traders weigh Iran nuclear talks, Russia-Ukraine developments - MarketWatch </td>
   <td style="text-align:left;"> Oil futures declined on Thursday, posting a loss of 2% as reports of progress in the Iran nuclear talks raised the potential for a release of more oil into the global market. "As the Iranian nuclear talks enter the final stage, we reiterate our view that if a new agreement is indeed reached, the country's exports would likely climb" by 500,000 barrels in six months, and by 1 million barrels in 12 months, analysts at RBC Capital Markets wrote in a Thursday research note. Traders, however, continued to monitor developments tied to a potential Russian invasion of Ukraine, which could disrupt global energy supplies. West Texas Intermediate crude for March delivery 
        CLH22,
        -0.56%
       fell $1.90, or 2%, to settle at $91.76 a barrel on the New York Mercantile Exchange., Nvidia said revenue jumped 53% in its fiscal fourth quarter to $7.64 billion. The company is projecting better-than-expected results for the current quarter, as well.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-02-18 03:42:59 </td>
   <td style="text-align:left;"> Copper Eases, Eyes on Russia-Ukraine Tensions </td>
   <td style="text-align:left;"> Copper futures traded around $4.5 per pound, trimming gains from earlier this week, as traders weighed geopolitical risks in Eastern Europe against reports of tight inventories and supply issues. Russian backed separatists and government forces accused each other of breaking cease-fire rules, reigniting fears of conflict between Ukraine and Russia. Still, stocks held in LME-approved warehouses declined to 70,125 tonnes, the lowest since November 2005, capping losses. On the supply side, MMG Ltd said production at its Las Bambas copper mine in Peru may stop by February 20th after a local community blocked again a road used by the miner, causing the company to curtail operations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/rihannas-fenty-beauty-heading-ulta/story.aspx?guid={B2AF9A6B-92C6-4A12-8954-372A474FF49C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 03:41:08 </td>
   <td style="text-align:left;"> Rihanna's Fenty Beauty heading to Ulta on March 6 - MarketWatch </td>
   <td style="text-align:left;"> Rihanna's Fenty Beauty brand will be on shelves at Ulta Beauty stores starting March 6th. Both Rihanna and Ulta made the announcement on Twitter, with the Grammy winner posting a snap of herself holding one of Ulta's bright orange shopping bags, and the beauty retailer posting a video clip that plays on the popular Wordle game. Ulta stock slumped on Thursday, like many others, with shares down 3.2%. The shares have run up nearly 14% over the last year while the S&amp;P 500 index 
        SPX,
        -2.12%
       is up almost 12%., Nvidia Corp. shares finished down Thursday for their worst day in a year even as analysts praised the chip maker's stellar results for the holiday quarter and widely expect the company's data-center business to surpass gaming in sales.                                                                                                                                                                                                                                                                                                             , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/mortgage-rates-near-4-percent </td>
   <td style="text-align:left;"> 2022-02-18 03:38:04 </td>
   <td style="text-align:left;"> Home mortgage rates climb to near 4% </td>
   <td style="text-align:left;"> Garman Homes founder and CEO Alaina Money Garman discusses the housing market and what homeowners are looking for as the supply chain crisis rages on.                                                                                                                      , Home mortgage rates continue to climb upward, and the average 30-year fixed-rate is now approaching 4% according to the latest data from Freddie Mac.                                                                                                                       , The organization's Primary Mortgage Market Survey for this week shows the average rate for a 30-year fixed-rate mortgage hit 3.92%, up from 3.69% last week. The average rate for the same product a year ago was at 2.81%.                                                 , Signage stands outside the Freddie Mac headquarters in McLean, Virginia, U.S., on Tuesday, Oct. 1, 2019. (Photographer: Andrew Harrer/Bloomberg via Getty Images / Getty Images)                                                                                            , "Mortgage rates jumped again due to high inflation and stronger than expected consumer spending," Freddie Mac's chief economist, Sam Khater, said in a statement. "The 30-year fixed-rate mortgage is nearing four percent, reaching highs we have not seen since May 2019.", HOUSING INFLATION, SUPPLY CHAIN CREATE BUILDERS' PERFECT STORM                                                                                                                                                                                                              , The average rate for a 15-year fixed-rate mortgage is also up, reaching 3.15% after sitting at 2.93% the week before. The same week in 2021, the 15-year rate averaged 2.21%.                                                                                               , A sale pending sign is displayed outside a residential home for sale in East Derry, N.H. (AP Photo/Charles Krupa, File (AP Photo/Charles Krupa, File / AP Newsroom)                                                                                                         , Adjustable-rate mortgages climbed to an average rate of 2.98%, up from 2.8% from last week's PMMS and from 2.77% a year ago.                                                                                                                                                , CALIFORNIANS HEAD SOUTH OF THE BORDER TO FIND MORE AFFORDABLE HOUSING                                                                                                                                                                                                       , "As rates and house prices rise, affordability has become a substantial hurdle for potential homebuyers," Khater said. "Especially as inflation threatens to place a strain on consumer budgets."                                                                           , People are showing renewed interest in the housing market as the latest figures show a resurgence in mortgage applications last week not seen since last April. (AP Photo/Michael Conroy, File) (Michael Conroy / AP Newsroom)                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                 , Additional data released this week shows the increase in rates has caused a decrease in people interested in filing mortgage applications. The average loan size also hit a new high, showing a continued trend of more would-be buyers being priced out of the market.     , The Mortgage Banker's Association's weekly survey results released Wednesday showed that mortgage loan applications fell 5.4% from last week, but the average loan size hit a new record of $453,000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/justice-department-probing-supply-chain-disruptions </td>
   <td style="text-align:left;"> 2022-02-18 03:31:51 </td>
   <td style="text-align:left;"> Justice Department probing supply-chain disruptions, targeting companies exploiting the crisis to charge more </td>
   <td style="text-align:left;"> Port of Long Beach Executive Director Mario Coredero argues as COVID concerns diminish, ‘definite moderation’ will happen in the supply chain.                                                                                                                                                                                                                                                 , The Justice Department (DOJ) and FBI will be investigating entities that may be exploiting supply chain disruptions caused by the COVID-19 pandemic, the department announced Thursday.                                                                                                                                                                                                        , As part of the new initiative, the DOJ's Antitrust Division will prioritize current investigations into entities that may be exploiting supply chain issues for illicit profit.                                                                                                                                                                                                                , A sign is seen on the shelf at a CVS store in Queens, New York. (Lindsey Nicholson/Universal Images Group via Getty Images)                                                                                                                                                                                                                                                                    , "Temporary supply chain disruptions should not be allowed to conceal illegal conduct," DOJ Antitrust Division Assistant Attorney General Jonathan Kanter said in a Thursday statement. "The Antitrust Division will not allow companies to collude in order to overcharge consumers under the guise of supply chain disruptions."                                                              , SUPPLY CHAIN SHOWING SIGNS ‘THE WORST IS OVER’: PORT OF LONG BEACH DIRECTOR                                                                                                                                                                                                                                                                                                                    , Specifically, the DOJ and FBI will be looking into companies and individuals that have colluded to fix prices or wages, rig bids or allocate markets, DOJ said in a press release.                                                                                                                                                                                                             , The two agencies will work to prosecute those involved in such exploitative behavior.                                                                                                                                                                                                                                                                                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                    , "The lingering challenge of supply chain disruptions from the COVID-19 pandemic has created an opportunity for criminals to fix prices and overcharge customers," FBI Criminal Division Assistant Director Luis Quesada said. "The FBI and our law enforcement partners will continue to collaborate and investigate schemes that violate our antitrust laws and stifle our economic recovery.", FILE - ,Cargo containers sit stacked at the Port of Los Angeles, Wednesday Oct. 20, 2021 in San Pedro, Calif. California Gov. (AP Photo/Ringo H.W. Chiu)                                                                                                                                                                                                                                       , DOJ acknowledged that while businesses across a variety of industries have come up with innovative ways to combat supply chain issues and rising prices resulting from transportation constraints, routine business disruptions and difficulty obtaining raw materials, some bad actors have taken advantage of those disruptions to make more money.                                          , READ MORE FROM FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                    , The department is asking anyone with information about price fixing, bid rigging, market-allocation agreements or otherwise anti-competitive behavior to call the Antitrust Division’s Citizen Complaint Center at 1-888-647-3258 or visit http://www.justice.gov/atr/report-violations.   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/17/health/ba-2-covid-severity/index.html </td>
   <td style="text-align:left;"> 2022-02-18 03:21:48 </td>
   <td style="text-align:left;"> As BA.2 subvariant of Omicron rises, lab studies point to signs of severity - CNN </td>
   <td style="text-align:left;"> (CNN)The BA.2 virus -- a subvariant of the Omicron coronavirus variant -- isn't just spreading faster than its distant cousin, it may also cause more severe disease and appears capable of thwarting some of the key weapons we have against Covid-19, new research suggests.                                                                                                                                                                                                        , New lab experiments from Japan show that BA.2 may have features that make it as capable of causing serious illness as older variants of Covid-19, including Delta.                                                                                                                                                                                                                                                                                                                     , And like Omicron, it appears to largely escape the immunity created by vaccines. A booster shot restores protection, making illness after infection about 74% less likely.                                                                                                                                                                                                                                                                                                             , BA.2 is also resistant to some treatments, including sotrovimab, the monoclonal antibody that's currently being used against Omicron.                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The findings were posted Wednesday as a preprint study on the bioRxiv server, before peer review. Normally, before a study is published in medical journal, it is scrutinized by independent experts. Preprints allow research to be shared more quickly, but they are posted before that additional layer of review.                                                                                                                                                                  , "It might be, from a human's perspective, a worse virus than BA.1 and might be able to transmit better and cause worse disease," says Dr. Daniel Rhoads, section head of microbiology at the Cleveland Clinic in Ohio. Rhoads reviewed the study but was not involved in the research.                                                                                                                                                                                                 , BA.2 is highly mutated compared with the original Covid-causing virus that emerged in Wuhan, China. It also has dozens of gene changes that are different from the original Omicron strain, making it as distinct from the most recent pandemic virus as the Alpha, Beta, Gamma and Delta variants were from each other.                                                                                                                                                               , Kei Sato, a researcher at the University of Tokyo who conducted the study, argues that these findings prove that BA.2 should not be considered a type of Omicron and that it needs to be more closely monitored.                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , "As you may know, BA.2 is called 'stealth Omicron,' " Sato told CNN. That's because it doesn't show up on PCR tests as an S-gene target failure, the way Omicron does.  Labs therefore have to take an extra step and sequence the virus to find this variant.                                                                                                                                                                                                                         , "Establishing a method to detect BA.2 specifically would be the first thing" many countries need to do, he says.                                                                                                                                                                                                                                                                                                                                                                       , "It looks like we might be looking at a new Greek letter here," agreed Deborah Fuller, a virologist at the University of Washington School of Medicine, who reviewed the study but was not part of the research.                                                                                                                                                                                                                                                                       , Mixed real-world data on subvariant's severity                                                                                                                                                                                                                                                                                                                                                                                                                                         , BA.2 is about 30% to 50% more contagious than Omicron. It has been detected in 74 countries and 47 US states.                                                                                                                                                                                                                                                                                                                                                                          , The US Centers for Disease Control and Prevention estimates that about 4% of Americans with Covid-19 now have infections caused by BA.2, but many other parts of the world have more experience with this variant.  It has become dominant in at least 10 other countries: Bangladesh, Brunei, China, Denmark, Guam, India, Montenegro, Nepal, Pakistan and the Philippines, according to World Health Organization's weekly epidemiological report.                                   , But, there's mixed evidence on the severity of BA.2 in the real world.  Hospitalizations continue to decline in countries where BA.2 has gained a foothold, like South Africa and the UK.  But in Denmark, where BA.2 has become the leading cause of infections, hospitalizations and deaths are rising, according to WHO.                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Resistant to monoclonal antibody treatments                                                                                                                                                                                                                                                                                                                                                                                                                                            , The new study found that BA.2 can copy itself in cells more quickly than BA.1, the original version of Omicron.  It's also more adept at causing cells to stick together.  This allows the virus to create larger clumps of cells, called syncytia, than BA.1.  That's concerning because these clumps then become factories for churning out more copies of the virus. Delta was also good at creating syncytia, which is thought to be one reason it was so destructive to the lungs., When the researchers infected hamsters with BA.2 and BA.1, the animals infected with BA.2 got sicker and had worse lung function. In tissues samples, the lungs of BA.2-infected hamsters had more damage than those infected by BA.1.                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Similar to the original Omicron, BA.2 was capable of breaking through antibodies in the blood of people who'd been vaccinated against Covid-19.  It was also resistant to the antibodies of people who'd been infected with Covid-19 early in the pandemic, including Alpha and Delta.  And BA.2 was almost completely resistant to some monoclonal antibody treatments.                                                                                                               , But there was a bright spot:  Antibodies in the blood of people who'd recently had Omicron also seemed to have some protection against BA.2, especially if they'd also been vaccinated.                                                                                                                                                                                                                                                                                                , And that raises an important point, Fuller says.  Even though BA.2 seems more contagious and pathogenic than Omicron, it may not wind up causing a more devastating wave of Covid-19 infections.                                                                                                                                                                                                                                                                                       , "One of the caveats that we have to think about as we get new variants that might seem more dangerous is the fact that there's two sides to the story," Fuller says.                                                                                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The virus matters, she says, but as its would-be hosts, so do we.                                                                                                                                                                                                                                                                                                                                                                                                                      , "Our immune system is evolving as well. And so that's pushing back on things," she said.                                                                                                                                                                                                                                                                                                                                                                                               , Right now, she says, we're in a race against the virus, and the key question is, who's in the lead?                                                                                                                                                                                                                                                                                                                                                                                    , "What we will ultimately want is to have the host be ahead of the virus. In other words, our immunity, be a step ahead of the next variant that comes out, and I don't know that we're quite there yet," she said.                                                                                                                                                                                                                                                                     , For that reason, Fuller says, she feels like it's not quite time for communities to lift mask mandates.                                                                                                                                                                                                                                                                                                                                                                                , "Before this thing came out, we were about 10 feet away from the finish line," she said. "Taking off the masks now is not a good idea. It's just going to extend it. Let's get to the finish line."                                                                                                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/17/health/intimate-partner-violence-lancet-as-equals-intl-cmd/index.html </td>
   <td style="text-align:left;"> 2022-02-18 03:18:39 </td>
   <td style="text-align:left;"> One in four women have experienced domestic violence. Where's the outrage or the plan? - CNN </td>
   <td style="text-align:left;"> This story is part of As Equals, CNN's ongoing series on gender inequality. For information about how the series is funded and more, check out our FAQs.                                                                                                                                                                                                                                                                                                                                                                                                                                              ,  (CNN)On Wednesday, a new study in The Lancet revealed that more than a quarter -- 27% -- of women around the world, aged 15-49, have experienced domestic violence from a male intimate partner at least once in their lifetime.                                                                                                                                                                                                                                                                                                                                                                     , That's approximately one in four women.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , And the abuse starts young: 24% of 15- to 19-year-olds had experienced violence.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The study used estimates based on data capturing the responses of 2 million women between 2000 and 2018, and defines intimate partner violence as "physically, sexually, and psychologically harmful behaviors in the context of marriage, cohabitation, or any other form of union, as well as emotional and economic abuse and controlling behaviors."                                                                                                                                                                                                                                              , The researchers refer to violence against women as a "global public health challenge" but this prevalence speaks of an even greater societal challenge: patriarchy.                                                                                                                                                                                                                                                                                                                                                                                                                                   , Talking to The Guardian in 2020 about what she'd learned in writing her book about power, control and domestic abuse, See What You Made Me Do, Australian investigative journalist Jess Hill said:                                                                                                                                                                                                                                                                                                                                                                                                    , Thousands of years of patriarchy has laid pretty good groundwork for [domestic abuse]. It's not so long since a wife was considered her husband's property and had no legal rights whatsoever. It was only in the 1980s that new laws against marital rape recognised that men didn't have the right to demand sex with their wives anytime they wanted; prior to that, consent was considered to have been given on the wedding day and never revoked. Today, we still live in a society that entrenches women's subordination at every level -- from the home to the boardroom, to our parliament." , "Men don't abuse women because society tells them it's OK," Hill adds. "Men abuse women because society tells them they are entitled to be in control."                                                                                                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , But all hope is not lost. As numerous organizations -- and the authors of the Lancet study -- have said, it is possible to prevent intimate partner violence.                                                                                                                                                                                                                                                                                                                                                                                                                                         , The RESPECT women framework,which is published by the WHO and supported by 13 other UN agencies and governments, identifies seven broad policy priorities that, taken together, can prevent violence against women.                                                                                                                                                                                                                                                                                                                                                                                   , They range from the economic and social empowerment of women; the provision of services by the state such as legal, health or social services; and the transformation of societal attitudes towards gender, "male privilege and female subordination" among others.                                                                                                                                                                                                                                                                                                                                   , The coronavirus pandemic saw all forms of gender-based violence rise the world over, particularly domestic violence, with women stuck at home with their abusers. But the tragedy of The Lancet report is that the numbers were already high before the pandemic. If the demographics are segmented further, we are bound to find worse rates of violence among certain groups of women -- women with disabilities and those with precarious immigration statuses, to name just two.                                                                                                                  , All eyes now need to be on what our governments are going to do about these galling stats. If they -- and us -- need reminding, as the study's authors confirm, intimate partner violence, and arguably all gender-based violence, "can have major short and long-term impacts on the physical and mental health of the victim, leading to substantial social and economic costs for governments, communities, and individuals".                                                                                                                                                                      , Story of the week                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Read this story about two sisters, Fazila and Shagufa Haidary, torn between their yearning for the past, the loved ones they left behind, and their fears for a deeply uncertain future.                                                                                                                                                                                                                                                                                                                                                                                                              , These sisters fled Afghanistan, now they fear war in Ukraine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Women behaving badly: Ismat Chughtai                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Written by Adie Vanessa Offiong                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Ismat Chughtai (1915-1991) alongside three other writers is referred to as "the fourth pillar of modern Urdu fiction", with her work considered by some "the birth of revolutionary feminist politics" with themes that include sexuality and class.                                                                                                                                                                                                                                                                                                                                                  , Following her graduation from Isabella Thoburn College in 1940, she was part of the Progressive Writers Movement which used Urdu literature to critique social injustice.                                                                                                                                                                                                                                                                                                                                                                                                                             , As an essayist, Chughtai was famous for her works Lihaaf  (The Quilt, 1942) which inspired India's first film about lesbianism, Fire; and Chu Mui (1952), which focuses on how women were regarded as only good to produce heirs.                                                                                                                                                                                                                                                                                                                                                                     , But her work was not without criticism. Lihaaf caused a storm in conservative India. She was summoned to court for obscenity -- an experience she documented in her essay, The Lihaaf Trial. This experience did not, however, deter her from writing about taboo topics such as women's sexual desires, male-dominated interpretations of religion and homoeroticism. She was also an advocate for women's rights to education among other causes.                                                                                                                                                   , Also a filmmaker, Chughtai wrote screenplays, dialogues and songs for films. She produced multiple movies with her director husband, Shaheed Latif, in the 1950s and 60s.                                                                                                                                                                                                                                                                                                                                                                                                                             , Chughtai's autobiography Kaghazi Hai Pairahan (The Paper Attire) was published posthumously in 2016.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Other stories worth your time                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , China censors lesbian plotline in 'Friends' -- CNN                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , 'Political choices' expose women to gender-based online disinformation, media freedom conference hears -- Press Gazette                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Gender-critical feminism is not as popular as its supporters may want you to believe -- The New Statesman                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Every Hindi film song by Lata Mangeshkar, in one graphic -- Hindustan Times                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , You auto-complete me: romancing the bot -- Deep Dives                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-02-18 03:15:10 </td>
   <td style="text-align:left;"> Gasoline Futures Fall Further on Iran Deal </td>
   <td style="text-align:left;"> US gasoline futures pulled back below $2.65 a gallon from an over seven-year high of $2.79 reached earlier in the week, amid a broad rout in commodities, as worries over Iranian oil returning to markets more than offset upside risks from geopolitical tensions in Eastern Europe. Iran was reportedly close to accepting a deal on its nuclear programme, which could mean the release of about 1.3 million barrels a day of crude supply and ease a tight global market. Meanwhile, Russian backed separatists and government forces accused each other of breaking cease-fire rules, reigniting fears of an imminent all-out war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/coca-colas-stock-rallies-just-shy/story.aspx?guid={C315A5C4-EB73-4D13-9234-9D78046FC08B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 03:15:07 </td>
   <td style="text-align:left;"> Coca-Cola's stock rallies to just shy of a record after dividend hike, plan to resume share repurchases - MarketWatch </td>
   <td style="text-align:left;"> Shares of Coca-Cola Co. 
        KO,
        +2.00%
       rallied 1.7% in afternoon trading Thursday, and are now a nickel shy of the Feb. 8 record close of $62.00, after the beverage giant raised its dividend and said it planned to resume repurchases this year. The new quarterly dividend of 44 cents a share, up from 42 cents, will be payable April 1 to shareholders of record on March 15. Based on current prices, the new annual dividend rate implies a dividend yield of 2.84%, which compares with the yield for the SPDR Consumer Staples Select Sector ETF 
        XLP,
        +0.77%
       of 2.31% and the implied yield for the S&amp;P 500 
        SPX,
        -2.12%
       of 1.44%. The company said it plans to buy back about $500 million worth of its shares in 2022, which represents about 0.2% of Coca-Cola's current market capitalization of $267.58 billion. The stock has climbed 10.8% over the past three months, while the Dow Jones Industrial Average 
        DJIA,
        -1.78%
       has slipped 4.1%., Nvidia said revenue jumped 53% in its fiscal fourth quarter to $7.64 billion. The company is projecting better-than-expected results for the current quarter, as well.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/mexico-avocado-ban-could-leave-us-lost-for-guac </td>
   <td style="text-align:left;"> 2022-02-18 03:14:02 </td>
   <td style="text-align:left;"> Mexico avocado ban could leave US 'lost' for guacamole </td>
   <td style="text-align:left;"> Garces Group COO Scott Campanella and HipCityVeg CEO Nicole Marquis discuss uncertainties surrounding avocado supply after a U.S. ban on Mexican imports.                                                                                                                                                                             , A U.S. ban on avocados from Mexico could soon have Americans crying "Holy guacamole."                                                                                                                                                                                                                                                 , Up to 80%, or $2.4 billion worth, of the United States’ annual avocado supply is at risk after Mexico confirmed U.S. officials suspended all imports following threatening messages sent to a Department of Agriculture plant safety inspector.                                                                                       , Now, restaurants and business owners are scrambling to secure their supply and plan ahead before the crop is "lost."                                                                                                                                                                                                                  , "We go through a slump every year where we're a little worried about this kind of thing with the avocados," Garces Group COO Scott Campanella told FOX Business’ Jeff Flock. "But we don't know when it's going to end this time."                                                                                                    , U.S. SUSPENDS IMPORTING MEXICAN AVOCADOS ON SUPER BOWL EVE FOLLOWING THREAT                                                                                                                                                                                                                                                           , "We're empathetic both to the restaurateurs in America, but also the farmers in Mexico," Campanella continued. "This crop will be lost if we don't figure this out."                                                                                                                                                                  , Another owner said she’s willing to take avocados completely off the menu if prices hit the pits.                                                                                                                                                                                                                                     , "We can't sell a bowl of guacamole for $20, so we just wait it out," HipCityVeg CEO Nicole Marquis added.                                                                                                                                                                                                                             , Avocados are seen in a grocery market in New York, United States on February 14, 2022. (Tayfun Coskun/Anadolu Agency via Getty Images / Getty Images)                                                                                                                                                                                 , Mexican President Andrés Manuel López Obrador claimed the move signals a trade war, part of a conspiracy to protect American producers from losing to "quality" Mexican products, according to the Associated Press.                                                                                                                  , Michoacan is the only state in Mexico fully authorized to export directly to the U.S. market. It’s also not the first time that the violence in Michoacan — where the Jalisco cartel is fighting turf wars against a collection of local gangs known as the United Cartels — has threatened avocados, the state’s most lucrative crop., After a previous incident in 2019, the USDA had warned about the possible consequences of attacking or threatening U.S. inspectors.                                                                                                                                                                                                   , FOX Business' Jeff Flock reports from Philadelphia, Pennsylvania, where restaurant owners are preparing for an avocado shortage.                                                                                                                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                           , Campanella noted he has enough avocados to get through the next eight to 10 days but isn’t sure how much longer the supply will last after that.                                                                                                                                                                                      , "We’ll wait and see," he said.                                                                                                                                                                                                                                                                                                        , READ MORE FROM FOX BUSINESS                                                                                                                                                                                                                                                                                                           , FOX Business’ Andrew Mark Miller contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-politics-60410844?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-18 02:58:41 </td>
   <td style="text-align:left;"> UK scraps rich foreign investor visa scheme </td>
   <td style="text-align:left;"> Visas offering foreign investors fast-track residency in the UK are being scrapped with immediate effect, the home secretary has confirmed.                                                                                                                                                    , Priti Patel said ending Tier 1 investor visas, for those spending at least £2m, was the start of a "renewed crackdown on illicit finance and fraud".                                                                                                                                           , The scheme was introduced in 2008 to encourage wealthy people from outside the EU to invest in the UK.                                                                                                                                                                                         , It has been under review for some time, after concerns it is open to abuse.                                                                                                                                                                                                                    , The announcement had been expected next week amid pressure on ministers to cut UK ties to Russia over the threat of invasion to Ukraine, with a source confirming the decision to the BBC on Wednesday.                                                                                        , But the move has been brought forward, with the government saying it was part of their "new plan for immigration".                                                                                                                                                                             , The Tier 1 (investor) visa, often called a "golden visa", offers residency to those investing £2m or more in the UK, and allows their families to join them.                                                                                                                                   , Holders of these visas can then apply for permanent residency in the UK, at a speed depending on how much they invest.                                                                                                                                                                         , A £2m investment allows an application within five years, shortened to three years with £5m or two years if £10m is invested.                                                                                                                                                                  , But the route to residency is now being closed with immediate effect, with the government saying it "failed to deliver for the UK people and gave opportunities for corrupt elites to access the UK".                                                                                          , Ms Patel added: "I have zero tolerance for abuse of our immigration system. Under my new plan for Immigration, I want to ensure the British people have confidence in the system, including stopping corrupt elites who threaten our national security and push dirty money around our cities. , "Closing this route is just the start of our renewed crackdown on fraud and illicit finance. We will be publishing a fraud action plan, while the forthcoming Economic Crime Bill will crackdown on people abusing our financial institutions and better protect the taxpayer."                , The Home Office said settlement in the UK will now be conditional on applicants "executing an investment strategy that can show genuine job creation and other tangible economic impacts - passively holding UK investments will no longer be enough to obtain settlement. "                   , Lib Dem foreign affairs spokesperson Layla Moran said: "Shutting the door to Putin's cronies is not enough - too many of them have already walked through it with virtually no questions asked."                                                                                               , She urged the government to publish its report into those who came to the UK on the visas.                                                                                                                                                                                                     , Labour's shadow home secretary Yvette Cooper also called for the review to be published and said a general plan was needed to "stop illicit finance coming into the UK".                                                                                                                       , She said "for years the Conservatives failed to stamp out the influence of Russian money in the UK" adding that it had "taken international condemnation of our failures... for the home secretary to act".                                                                                    , The Home Office has issued 2,581 investor visas to Russian citizens since the scheme was introduced in 2008.                                                                                                                                                                                   , Several changes have been made since the investor visa scheme was launched, including extra checks on how and when applicants acquired their wealth.                                                                                                                                           , Banks are also now required to complete certain checks before opening accounts for applicants - who are also required to submit extra paperwork if their qualifying funds are invested through a chain of different companies.                                                                 , In 2020, Parliament's intelligence and security committee argued for a "more robust" approach to approving Tier 1 visas as part of a report on Russian influence in the UK.                                                                                                                    , Correction: An earlier version of this story incorrectly stated the number of Tier 1 (Investor) visas granted to Russians as 14,516. The correct figure to the end of March 2020 was 2,581.                                                                                                    , A fresh perspective on how Hitler brutally seized and kept power                                                                                                                                                                                                                               , Get ready for the final series with this sneak peek                                                                                                                                                                                                                                            , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-tops-1900-marks-highest/story.aspx?guid={ACA2E311-2F09-4A1E-8A99-A3A5EE42E4F2}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-18 02:48:51 </td>
   <td style="text-align:left;"> Gold tops $1,900, marks highest settlement since June - MarketWatch </td>
   <td style="text-align:left;"> Gold futures climbed sharply on Thursday, topping the key $1,900 mark to settle at their highest since June of last year. "If Russia invades Ukraine, it will come with sanctions that will see the country all but locked out of the global financial system," said Kyle Roda, market analyst at IG, in emailed commentary. "For many, stores of value will be required, and the Russian central bank might be forced to sell dollars and increase its gold reserves." April gold 
        GCJ22,
        -0.38%
       rose $30.50, or 1.6%, to settle at $1,902 an ounce. Prices based on the most-active contract settled at their highest since early June of last year, FactSet data show. , The chip maker delivered what Wall Street was expecting, and more, when it reported fourth-quarter earnings late Wednesday, and yet the stock is falling.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-18 02:34:12 </td>
   <td style="text-align:left;"> Gold Tops $1,900 </td>
   <td style="text-align:left;"> Gold topped the $1,900 mark on Thursday, extending its upward momentum to levels not seen since June of 2021 as investors worried about escalating geopolitical tensions involving the West, Russia, and Ukraine. NATO said it had not seen Russia pulling back troops from Ukraine's borders, while Russian news reported mortars fired in eastern Ukraine. Aside from safe-haven bids, minutes from the Federal Reserve's last meeting showed policymakers might not be as hawkish as investors feared, as it failed to provide any hints on a 50-basis points rate hike, driving the bullion higher. On top of that, a disappointing US jobless claims report has supercharged existing upward momentum for the bullion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/17/feds-bullard-says-inflation-could-get-out-of-control-so-action-is-needed-now.html </td>
   <td style="text-align:left;"> 2022-02-18 02:19:39 </td>
   <td style="text-align:left;"> Fed's Bullard says inflation 'could get out of control,' so action is needed now </td>
   <td style="text-align:left;"> , NEW YORK — St. Louis Federal Reserve President James Bullard cautioned Thursday that without central bank action on interest rates, inflation could become an even more serious problem.                                                                                                                                                                                                                                , "We're at more risk now than we've been in a generation that this could get out of control," he said during a panel talk at Columbia University. "One scenario would be ... a new surprise that hits us that we can't anticipate right now, but we would have even more inflation. That's the kind of situation that we want to ... make sure it doesn't occur."                                                        , Bullard has made news lately with his calls for aggressive Fed action. He has advocated for a full percentage point in rate increases by July in an effort to stem price surges that are running at the fastest pace in 40 years.                                                                                                                                                                                       , In his remarks Thursday, Bullard repeated his assertion that the Fed should "front-load" rate hikes as way to get ahead of inflation running at a 7.5% clip over the past year.                                                                                                                                                                                                                                         , Fed officials had been resisting tightening policy, insisting for much of last year that the current run-up in prices was tied to pandemic-specific factors, such as clogged supply chains and outsized demand for goods over services, and would fade over time.                                                                                                                                                       , "Overall, I'd say there's been too much emphasis and too much mindshare devoted to the idea that inflation will dissipate at some point in the future," Bullard said. "We're at risk that inflation won't dissipate, and 2022 will be the second year in a row of quite high inflation. So that's why given this situation, the Fed should move faster and more aggressively than we would have in other circumstances.", The Fed has indicated it likely will start raising interest rates in March, which would be the first increase in more than three years. After that, markets are looking for an additional five or six increases in 25 basis-point increments. A basis point is equal to 0.01%.                                                                                                                                          , Bullard said the upcoming change in policy shouldn't be viewed as an attempt to restrict the markets and the economy.                                                                                                                                                                                                                                                                                                   , "It's not tight policy. Don't let anybody tell you it's tight policy," he said. "It's removal of accommodation that will signal that we take our responsibility seriously."                                                                                                                                                                                                                                             , Market pricing for rate hikes has tempered over the past day or two, particularly after a release Wednesday of the January meeting minutes of the Federal Open Market Committee showed officials are looking to take a measured approach toward the removal of policy help.                                                                                                                                             , Traders are now pointing to a 25 basis-point hike in March after previously looking to a 50 basis-point move, according to CME data. The probability for seven hikes dropped Thursday to 43% after approaching 70% earlier in the week.                                                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/17/stocks-making-the-biggest-moves-midday-doordash-hasbro-palantir-walmart-and-more.html </td>
   <td style="text-align:left;"> 2022-02-18 02:01:10 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: DoorDash, Hasbro, Palantir, Walmart and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                              , Check out the companies making headlines in midday trading Thursday.                                                                                                                                                                                                                                                                                                                         , DoorDash — Shares of DoorDash jumped 10.6% after the food delivery company's quarterly revenue turned out better than expected. DoorDash reported $1.3 billion in revenue last quarter, beating a Refinitiv estimate of $1.28 billion. The company also posted strong order numbers and added new users, suggesting that demand for food delivery services remains high.                     , Palantir Technologies — Shares of Palantir dropped 15.7% after the company's earnings fell short of forecasts for the fourth quarter, though its revenue beat estimates. Its reported net loss was $156.19 million, wider than the $148.34 million loss seen in the year-earlier period.                                                                                                     , Hasbro — The toymaker saw shares rise 2% after activist investor Alta Fox Capital Management nominated five directors to the company's board. Alta is pushing for Hasbro to spin off its Wizards of the Coast unit and its digital games unit, which include franchise brands like Dungeons and Dragons and Magic: The Gathering. Alta owns a 2.5% stake in Hasbro worth around $325 million., Fastly — The cloud computing company's shares plunged 33.6% on disappointing full year guidance. Fastly reported a fourth quarter loss, though it was narrower than analysts had expected, and revenue beat consensus estimates.                                                                                                                                                             , Nvidia — Shares of the chipmaker fell 7.5% despite the company reporting strong quarterly results. Nvidia noted that its automotive business, which represents a growth market for its chips, had revenue drop 14% to $125 million. It also came under pressure on concerns about its exposure to the cryptocurrency market.                                                                 , Cheesecake Factory — The restaurant chain saw its shares rise 4% before pulling back, despite it reporting earnings that missed analysts' expectations along with increased input costs that negated a beat in revenue. The company is planning a price increase in new menus that could lift prices later this year.                                                                        , Walmart — The retail giant's shares rose 4% after Walmart topped earnings expectations and said it's on track to hit long-term financial targets, calling for adjusted earnings per share growth in the mid single-digits.                                                                                                                                                                   , Tripadvisor — The travel site operator fell 2.5% following an unexpected quarterly loss and a revenue miss. Tripadvisor said it expects the travel market to improve significantly in 2022 following what it called "unexpected periods of virus resurgence" in 2021.                                                                                                                        , Cisco Systems — The software company added 2.7% after it reported a beat on quarterly revenue and earnings and issued an upbeat full-year forecast, citing strong demand from cloud computing companies. Cisco earnings of 84 cents per share beat estimates by 3 cents. Revenue came in at $12.72 billion, versus estimates of $12.65 billion.                                              , Equinix — Digital infrastructure company Equinix gained 2.6% after TD Securities upgraded the stock to buy from hold, citing its recent pullback. The upgrade came a day after the company reported fourth quarter adjusted EBITDA that beat estimates, as well as a slight revenue beat.                                                                                                    , — CNBC's Yun Li contributed reporting.                                                                                                                                                                                                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-02-18 01:36:00 </td>
   <td style="text-align:left;"> US Natural Gas Slides 6% </td>
   <td style="text-align:left;"> US natural gas futures erased more than 5% to trade around $4.46/MMBtu on Thursday, slipping from a two-week high of $4.80/MMBtu hit earlier this week after a smaller-than-expected storage draw. The latest EIA data showed that the working gas held in storage facilities in the United States decreased by 190Bcf last week, while markets were expecting it to drop by 193Bcf. Still, forecasts for colder weather and higher heating demand combined with a continued slow return of US production limited losses. Elsewhere, European natural gas prices jumped amid ongoing concerns over tensions between Russia and Ukraine, as well as the possibility that the violence could stop Russian supplies, but global prices have little effect domestically, as US LNG export plants can't transform any more natural gas into LNG. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 01:35:15 </td>
   <td style="text-align:left;"> Madrid Stocks Close Lower on Thursday </td>
   <td style="text-align:left;"> The Ibex 35 Index fell 0.8% to close at 8,671 on Thursday, pressured by geopolitical tensions as fears of imminent military conflict returned. US and NATO authorities said there are signs of additional Russian troops making way to the Ukrainian border and that there is “every indication” that Russia is planning an invasion, including false flag operations as justifications for attacks. At the same time, investors weighed on the minutes of the Fed’s January meeting, pointing to a rate hike in March, although the magnitude is still unclear. On the corporate front, Repsol closed 0.5% lower after posting quarterly results, despite reporting a 70% annual increase in free cash flow operations, largely due to higher oil prices during the year. At the same time, the petrol company announced it plans to allocate 35% of investments until 2025 in low carbon activities, including the sale of its stake in the firm’s newly created renewable energy generation unit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/17/uk/uk-storm-eunice-dudley-scli-intl-gbr/index.html </td>
   <td style="text-align:left;"> 2022-02-18 01:34:29 </td>
   <td style="text-align:left;"> Eunice: Rare threat-to-life warning issued as back-to-back storms hammer the UK - CNN </td>
   <td style="text-align:left;"> (CNN)Meteorologists in the UK have issued a rare danger-to-life alert as Storm Eunice is forecast to batter parts of the country Friday, potentially creating a "sting jet" that could bring havoc to streets.                                                                                           , On Thursday, the UK's weather service, the Met Office, issued the rare red alert -- the highest weather warning category in the UK -- warning that Eunice is forecast to bring "significant and damaging" gusts of up to 90 mph and threaten life.                                                        , It could also bring high waves and coastal flooding in the west, southwest and south coast of England, the Met Office said.                                                                                                                                                                               , The warnings come as thousands of people remain without power in the UK's north after Storm Dudley brought down trees and cut households from the grid.                                                                                                                                                   , Dudley hit England's north, Scotland's south and Northern Ireland on Wednesday, disrupting railways, roads and businesses with high winds and local flooding.                                                                                                                                             , Peter Inness, a meteorologist at England's University of Reading, said that the back-to-back storms had formed as a result of a strong 200 mph jet steam blowing across the Atlantic Ocean. It is not unusual to see "two or more damaging storms" form in quick succession, he said in a statement.      , But what makes Eunice potentially "rare" and more potent is that it could evolve into a "sting jet" -- a "narrow, focused region of extremely strong winds" amid a "larger area of strong winds."                                                                                                         , The Met Office is urging people to only travel if "necessary" and warned drivers that road closures could be in place on Friday. People across the UK should also secure outdoor furniture and bins, and should avoid parking near trees.                                                                 , Severe storms more frequent                                                                                                                                                                                                                                                                               , Met Office meteorologist Jonathan Vautrey told CNN he expected Friday's storm to have "high impacts," with flying debris and damage to homes likely.                                                                                                                                                      , "It's developing out in the Atlantic at present, [and] it's heading directly for the UK so to speak," he said. "It will clear out of the UK over the course of Friday and travel towards Denmark and the Scandinavian countries."                                                                         , Vautrey said that, while it was "too early" to say whether storms Dudley and Eunice were "aided by climate change," such strong storms were becoming more common.                                                                                                                                         , "We've definitely seen the frequency of severe weather alter due to climate change," he said.                                                                                                                                                                                                             , "Global warming has led to changes in our weather patterns, and that is something we will increasingly have to take note of and be ready to deal with in the future."                                                                                                                                     , Hannah Cloke, a professor of hydrology at the University of Reading, warned people not to take the red alert "lightly."                                                                                                                                                                                   , "Red means you need to act now because there is an imminent danger to life," she said in a statement.                                                                                                                                                                                                     , "Winds of 70 mph will uproot trees, which can block roads and crush cars or buildings. They can pick up roof tiles and hurl them around.  If you're hit by one of those you will be seriously hurt or killed.  Wind that strong will sweep people and vehicles off streets, and topple electricity lines.", </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 01:15:52 </td>
   <td style="text-align:left;"> South African Stocks End Lower </td>
   <td style="text-align:left;"> The JSE FTSE All Share index was down 0.5% to close at 76,155 at the end of a choppy session on Thursday, led by commodity-linked sectors and financials, as global worries over mounting tensions between Russia and Ukraine more than offset upbeat corporate earnings. On the corporate front, South African miner Gold Fields reported a 20% rise in full-year profit, boosted by higher production and firmer prices, but flagged growing cost pressures. Also, fashion retailer Truworths International reported a 32.2% increase in half-year profit, recovering to pre-COVID 19 levels as lockdown restrictions eased. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/17/cathie-wood-says-her-innovation-stocks-are-way-undervalued-and-recent-fund-losses-temporary.html </td>
   <td style="text-align:left;"> 2022-02-18 01:10:53 </td>
   <td style="text-align:left;"> Cathie Wood says her innovation stocks are 'way undervalued' and recent fund losses temporary </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                      , Cathie Wood of Ark Invest said Thursday the technology companies in her innovation-focused portfolio are drastically undervalued, and she believes that her fund's recent sell-off is short-lived.                                                                                                                   , "We've had a significant decline," Wood said Thursday on CNBC's "Halftime Report." "We do believe innovation is in the bargain basement territory. ... Our technology stocks are way undervalued relative to their potential. ... Give us five years, we're running a deep value portfolio."                         , Her flagship fund Ark Innovation ETF was caught in the epicenter of the tech-driven sell-off in 2022, down 26% year to date. Some of her big holdings, including Zoom, Teladoc Health and Roku, have tumbled as much as 70% this year on expectations of rising interest rates.                                      , "Our biggest concern is that our investors turn what we believe are temporary losses into permanent losses," Wood said.                                                                                                                                                                                              , Higher rates typically punish growth pockets of the market that rely on low rates to borrow for investing in innovation. And their future earnings look less attractive when rates are on the rise.                                                                                                                  , Wood said she doesn't invest in any of those mature Big Tech companies like Microsoft. ARKK bets on companies in the forefront of disruptive technology in a variety of industries from DNA to automation, robotics and artificial intelligence. Her top holdings include Tesla, Exact Sciences, UiPath and Coinbase., "Today we have investors doing the opposite of what they did in the late '90s. They are running for the hills. It's risk-off because of inflation and interest rates. And the hills are their benchmarks. They are running to the past," Wood said.                                                                  , "If we are right and the disruptive innovation that is evolving is going to disintermediate and disrupt the traditional world order, those benchmarks are where the risk is. Not our portfolios," she added.                                                                                                         , Despite the big underperformance, her ARKK has attracted more than $70 million in net inflows year to date, according to FactSet.                                                                                                                                                                                    , The innovation investor said she believes the inflationary drag on growth stocks will end ultimately and that deflationary forces will return.                                                                                                                                                                       , "A lot of what's going on is supply chain related," Wood said. "I do think the deflationary forces building in the economy are pretty strong."                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                               , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                               , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                     , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                     , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                   , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/energy/russia-invading-ukraine-will-cause-oil-natural-gas-prices-to-go-up-up-and-away-canary-ceo </td>
   <td style="text-align:left;"> 2022-02-18 01:05:51 </td>
   <td style="text-align:left;"> Russia invading Ukraine will cause oil, natural gas prices to go 'up, up and away': Energy industry insider </td>
   <td style="text-align:left;"> Canary CEO Dan Eberhart warns oil and natural gas prices will soar if the situation overseas escalates, especially given 'Europe gets a big portion of its natural gas from Russia.'                                                                                                                                                                                                                  , Dan Eberhart, CEO of drilling services company Canary, argued on Thursday that oil will likely hit $100 a barrel before the summer driving season regardless of a potential Russian invasion of Ukraine due to macroeconomic factors and the current inflationary environment.                                                                                                                        , He did, however, warn that an invasion would impact oil and natural gas prices and will cause them to go "up, up and away."                                                                                                                                                                                                                                                                           , "Europe gets a big portion of its natural gas from Russia and we will be looking for that to go up as well," Eberhart added.                                                                                                                                                                                                                                                                          , Eberhart provided the insight on "Varney &amp; Co." on Thursday as U.S. stocks retreated as investors continue to monitor tensions between Russia and Ukraine, as well as the Federal Reserve's preparation for a March rate hike.                                                                                                                                                                        , All three of the major averages fell over 1% with the Dow Jones Industrial Average down over 400 points.                                                                                                                                                                                                                                                                                              , The cost of crude oil and gas began to climb over the past month as Russia added troops to the Ukrainian border. On Thursday oil slipped below $90 per barrel.                                                                                                                                                                                                                                        , Defense Secretary Lloyd Austin addressed reports of Ukraine and Russian-backed rebels accusing each other of violating a cease-fire after a shelling incident Thursday, stating that the U.S. is monitoring the situation.                                                                                                                                                                            , Sen. Marco Rubio, R-Fla., weighs in on the Russia-Ukraine conflict and the threat of China.                                                                                                                                                                                                                                                                                                           , At a NATO news conference Thursday morning, Austin said he has been concerned that Russia might try to stage a false flag operation as an excuse to invade Ukraine, but that the U.S. is not jumping to any conclusions at this time.                                                                                                                                                                 , "We've seen the reports of the shelling… and they're certainly troubling. We're still gathering the details, but we've said for some time that the Russians might do something like this in order to justify a military conflict, so we'll be watching this very closely," Austin said.                                                                                                               , The secretary pointed to Russian troops getting closer to the border, additional combat and support aircrafts flying in, activity in the Black Sea, and an increase in blood supplies as evidence that Russia is not withdrawing. Eberhart stressed that regardless of what happens overseas, he believes the macroeconomic factors and the inflationary environment "are going to push oil higher."  , "I would be shocked if oil doesn’t cross $100 before we hit the summer driving season," he continued, adding that he believes "the fundamentals are that $85 or $90 are going to be more than a floor than a ceiling for oil as we move forward even independent of the Russia, Ukrainian situation."                                                                                                 , Inflation surged more than expected in January, notching another four-decade high as strong consumer demand and pandemic-related supply-chain snarls fueled rapid price gains that wiped out the benefits of rising wages for most Americans.                                                                                                                                                         , BIDEN'S INFLATION SWAMPS WAGE GAINS, LEAVING WORKING FAMILIES BEHIND                                                                                                                                                                                                                                                                                                                                  , Dan Eberhart, CEO of drilling services company Canary, argues oil will likely hit $100 a barrel before the summer driving season independent of the Russia, Ukraine situation due to macroeconomic factors and the current inflationary environment.                                                                                                                                                  , The consumer price index rose 7.5% in January from a year ago, according to a new Labor Department report released last Thursday, marking the fastest increase since February 1982, when inflation hit 7.6%. The CPI – which measures a bevy of goods ranging from gasoline and health care to groceries and rents – jumped 0.6% in the one-month period from December.                               , Price increases were widespread: Although energy prices rose just 0.9% in January from the previous month, they're still up 27% from last year. Gasoline, on average, costs 40% more than it did last year.                                                                                                                                                                                           , On Thursday, the national average for gas was $3.52, eight cents higher than the day before and 98 cents more than the same time last year, according to AAA.                                                                                                                                                                                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                           , Eberhart slammed Biden’s energy policies on Thursday, arguing that they are "leading to higher gasoline prices." He stressed that the Biden administration’s energy policies are "pushing the supply down" when demand is growing, causing "the price goes up."                                                                                                                                       , President Biden revoked the permit for the Keystone XL oil pipeline project on his first day in office in a series of orders aimed at combating climate change, ending a project that was expected to employ more than 11,000 Americans this year.                                                                                                                                                    , Biden also temporarily suspended the issuance of oil and gas permits on federal lands and waters.                                                                                                                                                                                                                                                                                                     , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                               , FOX Business’ Megan Henney and Fox News’ Ronn Blitzer contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 01:00:25 </td>
   <td style="text-align:left;"> European Stocks Remain Under Pressure </td>
   <td style="text-align:left;"> The main European bourses finished Thursday's session in the red, led by economically sensitive financials, energy and industrial companies, as concerns over growing tensions in Ukraine eclipsed a slew of upbeat earnings. Russian-backed rebels and Ukrainian forces traded accusations that each had fired across the ceasefire line in eastern Ukraine. At the same time, the US warned of the possibility of a Russian invasion any day, while NATO stated it had not seen Russia pulling back troops from Ukraine's borders. On the corporate side, Commerzbank jumped almost 3% after the German lender's posted a better-than-expected net profit in the fourth quarter. After fourth-quarter solid earnings reports, Dutch engineering firm Arcadis and French luxury goods company Kering gained 9% and 5%, respectively. Domestically, the benchmark DAX fell for a second straight session to end around 15,250. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/17/antony-blinken-united-nations-address-russia-ukraine-border-sot-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-18 00:58:27 </td>
   <td style="text-align:left;"> VIDEO: Sec. Antony Blinken addresses the United Nations on Ukraine-Russia border crisis - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 00:58:00 </td>
   <td style="text-align:left;"> French Stocks Cut Gains </td>
   <td style="text-align:left;"> The CAC 40 Index erased early gains to close 0.3% lower at 6,947 on Thursday, as alarming geopolitical developments in Ukraine offset strong corporate results. NATO defence ministers agreed to consider establishing new forces in eastern Europe, while US and UK authorities stated 7,000 Russian troops are moving towards the Ukrainian border, contrary to Moscow’s claims. On the earnings front, Kering shares jumped 5.1% after the luxury posted a rebound in profitability for 2021, while expecting organic growth to accelerate in the near future on the back of its flagship brand Gucci. At the same time, Carrefour rose 4.6% following earnings results that exceeded market expectations, while maintaining its guidance despite higher food inflation. On the other hand, Air France-KLM plunged 7.6% after announcing it plans to raise EUR 4 billion to repay its pandemic debt, while not making any forecasts past the first quarter of 2022 in its quarterly earnings announcement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ivory-coast/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-18 00:50:26 </td>
   <td style="text-align:left;"> Ivory Coast January Inflation Rate Steady at Over 10-1/2-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in the Ivory Coast stood at 5.6 percent in January of 2022, its highest level since May of 2011, unchanged from the previous month. Main upward pressure came from prices of food &amp; non-alcoholic beverages (11.9 percent vs 12.3 percent in December) and housing &amp; utilities (6.4 percent vs 5.6 percent). On a monthly basis, consumer prices were up 0.2 percent, easing from 1.2 percent in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 00:48:00 </td>
   <td style="text-align:left;"> Italian Stocks Decline on Thursday </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 1.1% lower at 26,669 on Thursday, pressured by heightened geopolitical tension in Ukraine and projections of tighter monetary policy, while investors digested a batch of earnings data in Europe. Concerns of military conflict returned when Russian-backed rebels claimed Ukrainian forces broke a ceasefire agreement, while NATO and US authorities said Moscow is moving an additional 7,000 troops to the Ukrainian border. At the same time, investors weighed on the minutes of the Fed’s January meeting, pointing to a rate hike in March. On the corporate front, Tenaris shares fell 2.8%, despite posting better than expected revenues of USD 2.057 billion compared to expectations of USD 2.013 billion. The steel pipe manufacturer also announced it expects a further increase in sales during the first half of the year. At the same time, Bper Banca fell -4%, underperforming the banking sector, as investors continue to weigh on its acquisition of Banca Carige. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/fbi-forms-crypto-enforcement-team </td>
   <td style="text-align:left;"> 2022-02-18 00:45:03 </td>
   <td style="text-align:left;"> FBI forming crypto enforcement team </td>
   <td style="text-align:left;"> US Securities and Exchange Commission chair discusses regulating the digital money market on 'The Claman Countdown.'                                                                                                                                                                                                                                                                                                                                                           , The Federal Bureau of Investigation is in the process of building a specialized team focused on the enforcement of crimes involving cryptocurrency, a Department of Justice official announced Thursday.                                                                                                                                                                                                                                                                       , Deputy Attorney General Lisa Monaco made the revelation in a speech at the Munich Cyber Security Conference in Germany, saying that the unit will be called the Virtual Asset Exploitation Team (VAXU).                                                                                                                                                                                                                                                                        , Lisa Monaco, deputy U.S. attorney general, speaks during a news conference at the Department of Justice in Washington on Nov. 8, 2021. (Ting Shen/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                   , "This FBI unit will combine cryptocurrency experts into one nerve center that can provide equipment blockchain analysis, virtual asset seizure and training to the rest of the FBI," Monaco explained, saying that the team will join the National Cryptocurrency Enforcement Team (NCET) she announced last October.                                                                                                                                                          , AS RUSSIAN CYBERATTACK LOOMS, CYBERSPACE IS ‘21ST CENTURY BATTLEGROUND’: EXPERTS                                                                                                                                                                                                                                                                                                                                                                                               , In a separate announcement on Thursday, the DOJ said in a press release that seasoned computer crimes prosecutor Eun Young Choi will be the NCET's first director, effective immediately.                                                                                                                                                                                                                                                                                      , The U.S. Department of Justice seal on a podium in Washington on Aug. 5, 2021. (Samuel Corum/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                        , "With the rapid innovation of digital assets and distributed ledger technologies, we have seen a rise in their illicit use by criminals who exploit them to fuel cyberattacks and ransomware and extortion schemes; traffic in narcotics, hacking tools and illicit contraband online; commit thefts and scams; and launder the proceeds of their crimes," Assistant Attorney General Kenneth A. Polite Jr. of the Justice Department’s Criminal Division said in a statement. , SEC CHAIR: EXAMINATION OF CRYPTO PLATFORM BINANCE IS SIMPLY SEEKING ‘BASIC INVESTOR PROTECTION’                                                                                                                                                                                                                                                                                                                                                                                , "The NCET will serve as the focal point for the department’s efforts to tackle the growth of crime involving these technologies," Polite continued. "Eun Young is an accomplished leader on cyber and cryptocurrency issues, and I am pleased that she will continue her service as the NCET’s inaugural Director, spearheading the department’s efforts in this area."                                                                                                        , In this courtroom sketch, Heather Morgan and her husband, Ilya "Dutch" Lichtenstein, right, in federal court. They are accused of conspiring to launder billions of dollars in cryptocurrency stolen from the 2016 hack of a virtual currency exchange. (AP Photo/Elizabeth Williams / AP Newsroom)                                                                                                                                                                            , The announcements come on the heels of the DOJ's largest cryptocurrency bust to date, after the federal law enforcement agency last month seized roughly $4.5 billion in bitcoin from a husband and wife duo accused of laundering the cryptocurrency that was allegedly stolen during the 2016 hack of virtual currency exchange Bitfinex.                                                                                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                    , The Biden administration has ramped up its scrutiny of the cyber industry as a whole as part of an effort to crack down on cybercrimes amid an increase in attacks seeking virtual assets as ransom payments.                                                                                                                                                                                                                                                                  , "We are issuing a clear warning to criminals who use cryptocurrency to fuel their schemes," Monaco said in her speech. "We also call on all companies dealing with cryptocurrency: we need you to root out cryptocurrency abuses. To those who do not, we will hold you accountable where we can."                                                                                                                                                                             , FOX Business' Jake Gibson contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-18 00:45:02 </td>
   <td style="text-align:left;"> Switzerland 10Y Bond Yield Falls from 7-Year High </td>
   <td style="text-align:left;"> The yield on the Swiss 10-year government bond eased to below 0.3% from the 7-year high of 0.35% touched on February 15th, as renewed fears of a Russian invasion in Ukraine increased the demand for safer assets. At the same time, the Swiss National Bank remains committed to its ultra-loose monetary policy, as the latest labor data indicated that unemployment did not increase despite the Covid infection wave in January, while consumer inflation remains moderate. In its latest survey economic survey of Switzerland, the OECD noted that the Swiss economy proved to be very resilient to the ongoing health crisis and should be in no rush to tighten monetary policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-18 00:45:00 </td>
   <td style="text-align:left;"> FTSE 100 Falls for Second Day </td>
   <td style="text-align:left;"> The FTSE 100 ended down 1% on Thursday, tracking a general cautious mood in Europe amid persistent tensions with Russia over Ukraine. Russia denied a claim by the US and the UK that it has added as many as 7,000 troops. NATO defence ministers agreed on Wednesday to consider establishing new battlegroups in central, eastern and south-eastern Europe. Shares of Evraz and IAG were the top losers on the main index today, down about 7.1% and 4.3%, respectively. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/biden-blame-supply-chain-inflation-obama-official </td>
   <td style="text-align:left;"> 2022-02-18 00:29:36 </td>
   <td style="text-align:left;"> Biden claim that supply chain is to blame for inflation is 'totally dishonest,' Obama-era official says </td>
   <td style="text-align:left;"> Moody's Analytics chief economist Mark Zandi joined 'Mornings with Maria' to discuss inflation, the producer price index, and the possibility of a recession.                                                                                                                                                                                                                                              , President Biden has repeatedly blamed tangled supply chains for the surging inflation that has seeped into every part of the U.S. economy – but a former Obama administration official on Thursday dismissed that as a "totally dishonest" argument.                                                                                                                                                       , In an op-ed for The New York Times, Steven Rattner – who served as counselor to the Treasury secretary under then-President Barack Obama – accused Biden of mischaracterizing the once-in-a-generation inflation spurt that Americans are experiencing.                                                                                                                                                    , MOST SMALL BUSINESSES SINCE 1974 ARE HIKING PRICES TO OFFSET INFLATION                                                                                                                                                                                                                                                                                                                                     , "Supply issues are by no means the root cause of our inflation. Blaming inflation on supply lines is like complaining about your sweater keeping you too warm after you’ve added several logs to the fireplace," Rattner wrote. "The bulk of our supply problems are the product of an overstimulated economy, not the cause of it."                                                                       , Rattner was referring to comments that Biden made during an interview last week with NBC News' Lester Holt, in which the president said pandemic-induced bottlenecks in the global supply chain were the largest driver of soaring consumer prices. Biden pointed to semiconductor shortages, which have continued to delay car manufacturing and have contributed to a 12.2% annual rise in vehicle costs., A shopper walks through the aisles of the Dollar Tree store in Alhambra, California on December 10, 2021.  (Photo by FREDERIC J. BROWN/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                                , "The reason for the inflation is the supply chains were cut off, meaning that the products, for example, automobiles — the lack of computer chips to be able to build those automobiles so they could function; they need those computer chips," Biden said during the interview. "They were not available."                                                                                               , Although Rattner acknowledged the pandemic has indeed stretched supply chains, he said the primary inflation source is rapid consumer demand, fueled in large part by unprecedented levels of government spending, including three stimulus payments.                                                                                                                                                      , On top of that, the pandemic has shifted what Americans are purchasing; as they continue to grapple with the virus, many Americans have shifted their spending to goods like cars, electronics and building materials for homes, rather than travel or entertainment. The Labor Department reported that spending on durable goods surged 25% in 2021, compared with 2020.                                 , "It’s a classic economic case of ‘too much money chasing too few goods,’ resulting in both higher prices and, given the extreme surge in demand, shortages," he said.                                                                                                                                                                                                                                      , A container ship is shown at the Port of Los Angeles, Nov. 22, 2021. (REUTERS/Mike Blake / Reuters Photos)                                                                                                                                                                                                                                                                                                 , Biden's comments came as the government reported that the consumer price index rose 7.5% in January from a year ago, marking the fastest increase since February 1982, when inflation hit 7.6%. The CPI – which measures a bevy of goods ranging from gasoline and health care to groceries and rents – jumped 0.6% in the one-month period from December.                                                 , The eye-popping reading marked the eighth consecutive month the gauge has been above 5%.                                                                                                                                                                                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                , In order to tame rising prices, Rattner said that the Biden administration needs to shift its approach; instead of focusing on passing another trillion-dollar spending package, the economist suggested the White House should prioritize reducing the deficit.                                                                                                                                           , "That’s how Bill Clinton pivoted after he took office in 1993," Rattner said. "He unexpectedly raised taxes in his budget to address the pressing matter of the federal budget deficit. That decision served the country well — and ultimately also served him well." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/platinum </td>
   <td style="text-align:left;"> 2022-02-18 00:24:00 </td>
   <td style="text-align:left;"> Platinum Hits 13-week High </td>
   <td style="text-align:left;"> Platinum futures jumped above $1080 per troy ounce for the first in over three months, closing in on its strongest level since July 2021, amid persistent concerns over the Russia-Ukraine conflict. Also, the chip shortage in the car industry is set to ease, boosting the demand for platinum, a cheaper alternative to palladium in the production of autocatalysts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/17/us/paislee-shultis-6-year-old-found-new-york-saugerties/index.html </td>
   <td style="text-align:left;"> 2022-02-18 00:00:17 </td>
   <td style="text-align:left;"> Missing girl found under stairs: Inside the search for Paislee Shultis - CNN </td>
   <td style="text-align:left;"> (CNN)Police had gone up and down the basement stairs several times while searching a home in the Saugerties, New York, area Monday for any trace of 6-year-old Paislee Shultis, who had been missing for more than two years.                                                                                                                                      , Roughly an hour and a half into the search, one detective took a closer look at the wooden staircase. "He couldn't put his finger on it, but there was something about the staircase that bothered him," police Chief Joseph Sinagra told CNN.                                                                                                                      , Det. Erik Thiele pointed his flashlight at the spot where a stair met the riser, Sinagra said. Thiele saw what he believed to be a blanket, and police began to disassemble the staircase.                                                                                                                                                                          , "And as they're removing the steps off the staircase, they see a set of feet," the police chief told CNN. "Little feet."                                                                                                                                                                                                                                            , They were Paislee's. She was hidden under the staircase with her noncustodial mother, the chief said, huddled in a nest of pillows, blankets and clothes, in what police described as a "dark and wet enclosure."                                                                                                                                                   , Today, the girl is safe, having been returned to her legal guardian and reunited with her older sister. But many questions remain unanswered as investigators try to piece together what she's been through over the last two and a half years.                                                                                                                     , The girl was unable to go to school and it was unclear whether she'd seen a doctor since she disappeared, the chief said. And it's unknown what impact living in these conditions has had on her.                                                                                                                                                                   , The mother, Kimberly Cooper, was arrested, along with Paislee's noncustodial father and grandfather, who both denied having knowledge of Paislee's whereabouts when police executed their search warrant this week.                                                                                                                                                 , Cooper was charged with second-degree custodial interference and endangering the welfare of a child, both misdemeanors, according to police. She is out on bail.                                                                                                                                                                                                    , Kirk Shultis Jr. and Kirk Shultis Sr. were each charged with custodial interference in the first degree, a felony, and endangering the welfare of a child, a misdemeanor. Both were arraigned and released on their own recognizance, police said. All three defendants were ordered by the court to stay away from the child.                                      , Lawyers for the men declined to comment, while Carol K. Morgan, an attorney representing Cooper said, "We should all wait until the facts come out. Everyone should be patient before they draw their own conclusions."                                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                     , 'They lied to us for two years'                                                                                                                                                                                                                                                                                                                                     , Paislee Joann Shultis was reported missing on July 13, 2019, from Cayuga Heights, a village on the outskirts of Ithaca, about 160 miles west of Saugerties. Sinagra told CNN that Cooper and Shultis Jr. had lost custody of Paislee and her sister and a legal guardian had been granted custody.                                                                  , Sinagra told CNN that police had received several tips about the home, and they had been there about a dozen times over the last two years. But each time, residents denied knowing where the girl was and were instead "adversarial" with police, Sinagra said. Police made it inside several times but were not allowed in the bedrooms areas or in the basement. , "They lied to us for two years -- including the father stating that he had no idea where his daughter was," the chief said.                                                                                                                                                                                                                                         , It wasn't until Monday that police were able to obtain factual information -- not hearsay -- that helped them secure a search warrant, he told CNN. Uniformed officers were stationed outside the home that afternoon around 4 to ensure no one left or entered before police executed their warrant soon after 8 p.m.                                              , In the basement, they found an apartment that included a bedroom with Paislee's name on a wall, Sinagra said. A bed appeared to have been slept in.                                                                                                                                                                                                                 , "Is she here?" officers asked, according to the chief. But residents denied anyone was living in the room, he said. "They said they had set the room up like that in the event that Paislee should ever return."                                                                                                                                                    , Paislee was hidden under the stairs just 3 or 4 feet away.                                                                                                                                                                                                                                                                                                          , Investigators believe the space beneath the stairs was used more than once, Sinagra said -- maybe each time an officer visited the residence. He pointed to how the staircase was constructed along with how comfortable residents appeared Monday as they insisted they didn't know where Paislee was, an indication to the chief they had done this before.       , Sinagra believes they had been hiding from the time officers arrived outside the home, meaning they could have been in the "wet" and "cold" space for five hours before they were found.                                                                                                                                                                            , Neither the girl nor Cooper made a sound as police took apart the stairs that hid them, Sinagra said. A detective had described the silence as "eerie," the chief said.                                                                                                                                                                                             , While Sinagra is happy that Paislee was found safe, he also said the case was tragic: Whatever the reason Paislee's parents lost custody of her and her sister, he said, that could have "been rectified by now."                                                                                                                                                   , "But this is going to be a major setback for them," he said.                                                                                                                                                                                                                                                                                                        , Correction: The caption on a photo in this story has been updated to correct the date it was taken.                                                                                                                                                                                                                                                                 , CNN's Mirna Alsharif, Christina Maxouris and Ray Sanchez contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-02-17 23:47:00 </td>
   <td style="text-align:left;"> US Natural Gas Eases From 2-Week High </td>
   <td style="text-align:left;"> US natural gas futures were trading around the $4.60/MMBtu level in the third week of February, moving away from a two-week high of $4.80/MMBtu hit earlier this week after a smaller-than-expected storage draw. The latest EIA data showed that the working gas held in storage facilities in the United States decreased by 190Bcf last week, while markets were expecting it to drop by 193Bcf. Still, forecasts for colder weather and higher heating demand combined with a continued slow return of US production limited losses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-17 23:39:00 </td>
   <td style="text-align:left;"> French 10Y Bond Yield Falls from 3-Year High </td>
   <td style="text-align:left;"> The yield on the French 10-year OAT eased to 0.7% from the 3-year high of 0.8% touched on February 16th, in line with its global counterparts as investors fled to safer assets after US and NATO said there is “every indication” that Russia is planning to invade Ukraine, pointing to continued movement of troops to the border and false flag operations as justifications for attacks. Elsewhere, Bank of France Governor Francois de Galhau said that soaring inflation and geopolitical risks mean that the ECB could end net asset purchases in the third quarter of 2022, a step that is deemed necessary before rate hikes began. Meanwhile, preliminary data from INSEE suggests that French GDP growth will slow in the first quarter of 2022 due to restrictions brought by the new wave of coronavirus cases. Early estimates showed the French GDP will grow by 0.3% on the quarter during Q1, and is expected to grow by 0.6% during Q2. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lithium </td>
   <td style="text-align:left;"> 2022-02-17 23:02:00 </td>
   <td style="text-align:left;"> Lithium Carbonate Extends Rally </td>
   <td style="text-align:left;"> Lithium carbonate prices in China extended their rally to 414,500 yuan/tonne in mid-February, marking a gain of 50% so far in 2022, amid high global demand and projections of scarcity. Sales of electric vehicles powered by lithium batteries are soaring amid the transition to greener energy. 
According to Adamas Intelligence, a record 25,921 tonnes of lithium carbonate equivalent batteries were deployed to roads during December 2021, a 68% increase on the year and a 31% increase on the month. At the same time, sales of new energy vehicles in China rose by 157% to 3.2 million units in 2021 and are expected to surpass 5 million in 2022. Meanwhile, battery manufacturers race to secure long-term supply contracts due to mineral scarcity. Benchmark Mineral Intelligence estimates a 26,000-tonne shortfall in 2022 and a 300,000 tonne by 2030, as miners cannot keep up with demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-17 23:01:14 </td>
   <td style="text-align:left;"> Canada Shares Move Sideways on Thursday </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, hovered around the flatline on Thursday, as investors monitored geopolitical tensions in Ukraine, protests in Ottawa, and fresh earnings. Russian backed separatists in eastern Ukraine and government forces have accused each other of breaking cease-fire rules, lifting appetite for safe-haven assets. Meanwhile, police buses were seen entering central Ottawa after authorities promised to end a three-week blockade caused by the “Freedom Convoy” protesters. Earlier, Prime Minister Justin Trudeau had sharpened his tone against the movement, calling it “a threat” to Canada’s democracy. On the earnings front, Canadian Tire beat quarterly revenue and profit estimates, driven by sales of sporting goods, garden equipment and home decor during the holiday season. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/politics/2022/02/17/trump-mazars-response-scannell-newday-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-17 22:54:49 </td>
   <td style="text-align:left;"> Trump's response to accounting firm may get him in trouble - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-17 22:50:00 </td>
   <td style="text-align:left;"> European Stocks Falter in Afternoon Trades </td>
   <td style="text-align:left;"> Europe’s major stock indices traded slightly lower on Thursday afternoon as upbeat earnings reports were not enough to offset lingering tensions in Ukraine. Russian-backed separatists in eastern Ukraine and government forces have accused each other of breaking cease-fire rules, triggering a rush to safe-haven assets. On the corporate front, Airbus posted a record net profit in 2021; Nestle profit increased and the company expects 2022 organic sales growth of around 5%; Commerzbank revenues increased; Orange sees a return to profit in 2022; Schneider Electric profit and revenue beat expectations; and Kering revenue growth surged 35.2% in 2021, boosted by star brand Gucci. Traders also digest the latest FOMC minutes release, with the Fed signaling once again a rate hike next month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-02-17 22:45:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Falls for 3rd Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index was down 0.5% to 1,886 on Thursday, the lowest since February 9th, extending losses for a third straight session. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, fell nearly 2% to 1,447, its lowest in more than a week and extending losses for the sixth straight session. "The capesize index has seen average earnings flatten as routes with major volumes, such as west Australia/China and Brazil/Feast, failed to meet trade-volume expectations, while Brazilian miners battle weather-related production issues and shipping delays.", said shipbroker Fearnleys. At the same time, the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, went down 0.4% to 2,365. Conversely, the supramax index increased 6 points to 2,326, as ongoing geopolitical tensions foster demand for coal shipments on the Indonesia-India routes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/17/business/stock-market-today.html </td>
   <td style="text-align:left;"> 2022-02-17 22:43:48 </td>
   <td style="text-align:left;"> Sell-Off of Stocks Deepens as Concerns Grow Around Ukraine  - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The broad nature of Thursday’s decline pointed to more than one reason. Oil prices and yields on government bonds also fell.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , By Coral Murphy Marcos and William P. Davis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Feb. 16
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Feb. 17
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , 4,380
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,400
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,420
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,440
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,460
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,480
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Data delayed at least 15 minutes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , By: Ella Koeze                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Stocks slid on Thursday, extending a volatile stretch of trading brought on by uncertainty about inflation, rising interest rates and the potential for war in Europe.                                                                                                                                                                                                                                                                                                                                                                                                                                           , The S&amp;P 500 fell 2.1 percent, dropping into negative territory for the week, while the Nasdaq composite fell 2.9 percent.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Tech companies were some of the worst performers, with Meta, Facebook’s parent, down more than 4 percent. Alphabet, Google’s parent, fell 3.8 percent, and Microsoft was down 2.9 percent.                                                                                                                                                                                                                                                                                                                                                                                                                       , Tesla, one of the largest companies in the S&amp;P 500, dropped 5.1 percent. The main auto-safety regulator in the United States said it was investigating reports from Tesla’s customers of “phantom braking” when they were using their vehicles’ driver-assistance system.                                                                                                                                                                                                                                                                                                                                        , Shares of banks also fell, with Morgan Stanley dropping 5 percent and Wells Fargo losing 3.4 percent.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The prospect that President Vladimir V. Putin will order a Russian invasion of Ukraine has weighed on global markets. On Tuesday, the stock market rose after Russian officials announced a partial troop withdrawal from the Ukrainian border. But President Biden said on Thursday that the possibility of an invasion remained “very high,” and shelling between Ukraine and Russia-backed separatists spiked, raising concerns that the conflict was heating up.                                                                                                                                             , “Markets are concerned about the Russian troop buildup and a lack of trust in Putin’s declaration that they are beginning to remove troops from the region,” said Chris Zaccarelli, the chief investment officer for Independent Advisor Alliance, an investment advisory firm.                                                                                                                                                                                                                                                                                                                                  , Investors have also been anticipating that the Federal Reserve will increase interest rates as it looks to fight persistently high inflation. Raising the Fed’s policy rate can lead to higher interest rates for houses and cars, causing spending to slow and inflation to moderate. But it also can increase the return on bonds, making riskier investments like stocks less appealing.                                                                                                                                                                                                                      , Minutes released on Wednesday from the Fed’s January meeting showed that most officials agreed that they might need to withdraw their support for the economy even more quickly if inflation does not cool down as they expect. Investors are now anticipating that the Fed’s policy rate could rise to more than 1.75 percent by the end of the year, up from nearly zero.                                                                                                                                                                                                                                      , Yields on the 10-year Treasury note, which last week crossed 2 percent for the first time since 2019, fell about eight basis points, or 0.08 percentage points, to about 1.96 percent. Yields fall as prices for bonds rise, which happens when investors buy them as they move money out of riskier investments like stocks.                                                                                                                                                                                                                                                                                    , What is inflation? Inflation is a loss of purchasing power over time, meaning your dollar will not go as far tomorrow as it did today. It is typically expressed as the annual change in prices for everyday goods and services such as food, furniture, apparel, transportation and toys.                                                                                                                                                                                                                                                                                                                       , What causes inflation? It can be the result of rising consumer demand. But inflation can also rise and fall based on developments that have little to do with economic conditions, such as limited oil production and supply chain problems.                                                                                                                                                                                                                                                                                                                                                                     , Where is inflation headed? Officials say they do not yet see evidence that rapid inflation is turning into a permanent feature of the economic landscape, even as prices rise very quickly. There are plenty of reasons to believe that the inflationary burst will fade, but some concerning signs suggest it may last.                                                                                                                                                                                                                                                                                         , Is inflation bad? It depends on the circumstances. Fast price increases spell trouble, but moderate price gains can lead to higher wages and job growth.                                                                                                                                                                                                                                                                                                                                                                                                                                                         , How does inflation affect the poor? Inflation can be especially hard to shoulder for poor households because they spend a bigger chunk of their budgets on necessities like food, housing and gas.                                                                                                                                                                                                                                                                                                                                                                                                               , Can inflation affect the stock market? Rapid inflation typically spells trouble for stocks. Financial assets in general have historically fared badly during inflation booms, while tangible assets like houses have held their value better.                                                                                                                                                                                                                                                                                                                                                                    , But the broad nature of Thursday’s sell-off pointed to more than one trigger. Oil has been trading at prices not seen since 2014, and an invasion by Russia, a big oil producer and Europe’s largest supplier of natural gas, would almost certainly push energy prices higher. But on Thursday, oil fell, with West Texas Intermediate, the U.S. crude benchmark, down 2 percent, to $91.76 a barrel. Natural gas fell more than 4 percent.                                                                                                                                                                     , “The concerns for growth going forward and recession risks are new to traders’ minds,” said Edward Moya, a senior market analyst at OANDA. “There’s a lot of fear that the optimistic growth outlook for 2023 is up in the air.”                                                                                                                                                                                                                                                                                                                                                                                 , Markets have been volatile for months, with concerns about the Omicron variant’s impact on the economy in November and December bleeding into uncertainty in January and February about persistently high inflation and how the Fed will react to it. Thursday’s drop was the S&amp;P 500’s worst day in only two weeks, and if the index ends this week in the red it will be its fifth weekly drop just seven weeks into the year. The index is down 8.7 percent since its Jan. 3 high. The Nasdaq composite peaked on Nov. 19, just before the Omicron variant was disclosed, and is down 14.6 percent since then., The consumer staples sector was one of the few that did not fall on Thursday. Walmart was one of the best-performing companies in the S&amp;P 500, climbing 4 percent after it reported that its revenue rose to $152.9 billion, up 0.5 percent in the three months ending in January from a year earlier. The company also said that sales across its U.S. business increased 5.7 percent to about $105 billion in the quarter.                                                                                                                                                                                     , AutoNation fell 3.8 percent, as the company’s chief executive said it was difficult to forecast whether it could sustain its current high profit levels in 2022. The company reported on Thursday a profit of $387 million in its latest quarter, more than double its profit from a year earlier, while revenue rose 14 percent to $6.6 billion.                                                                                                                                                                                                                                                                , In Europe, stock indexes edged lower. The Stoxx Europe 600 fell 0.7 percent on Thursday. Asian markets closed mixed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-17 22:38:00 </td>
   <td style="text-align:left;"> US Stocks Fall, Russia Tensions Weigh </td>
   <td style="text-align:left;"> Wall Street traded lower on Thursday, with the Dow Jones falling around 400 points while both the S&amp;P 500 and the Nasdaq declined over 1% each as worries of escalating geopolitical tensions in Eastern Europe sent shockwaves through equities markets. NATO stated it had not seen Russia pulling back troops from Ukraine's borders, while Russian news reported mortars fired in eastern Ukraine. Traders also digest fresh economic data and corporate results. Initial claims unexpectedly increased last week and housing starts dropped much more than expected. On the earnings front, Walmart, Cisco and Applied Materials topped expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/elon-musk-tesla-sec </td>
   <td style="text-align:left;"> 2022-02-17 22:22:26 </td>
   <td style="text-align:left;"> Elon Musk, Tesla accuse SEC of 'weaponizing' 2018 settlement for 'unrelenting' investigations </td>
   <td style="text-align:left;"> Aeva CEO Soroush Salehian explains the technology on 'Cavuto: Coast to Coast.'                                                                                                                                                                                                                                                                                                                                                              , Tesla and Elon Musk have accused the Securities and Exchange Commission of failing to distribute $40 million to the company's shareholders as part of a 2018 settlement to resolve securities fraud charges.                                                                                                                                                                                                                                , FEDS OPEN INVESTIGATION INTO TESLA ‘PHANTOM BRAKING’ INCIDENTS                                                                                                                                                                                                                                                                                                                                                                              , Instead of releasing the funds to shareholders, the electric vehicle maker claims that the agency has "gone rogue" and is "weaponizing the consent decree by using it to try to muzzle and harass Mr. Musk and Tesla, while ignoring its court-ordered duty to remit $40 million that it continues to hold while Tesla’s shareholders continue to wait."                                                                                    , "The SEC seems to be targeting Mr. Musk and Tesla for unrelenting investigation largely because Mr. Musk remains an outspoken critic of the government," Musk's lawyer, Alex Spiro, wrote in a letter to the U.S. District Court for the Southern District of New York. "The SEC’s outsized efforts seem calculated to chill his exercise of First Amendment rights rather than to enforce generally applicable laws in evenhanded fashion.", Tesla and Elon Musk have accused the SEC of failing to distribute $40 million to the company's shareholders as part of a 2018 settlement to resolve securities fraud charges. (Natan Dvir and Joshua Roberts /Bloomberg via Getty Images)                                                                                                                                                                                                   , According to the letter, the regulator has been in possession of funds owed to Tesla investors for more than 1,200 days and has not yet announced a distribution plan. In May, the court appointed Rust Consulting to dole out the cash to investors. However, the court said in a Dec. 21 filing that the firm had not sent any status reports and ordered it to file one by Jan. 7.                                                       , The letter asks to schedule a hearing in order to look into the matter in the hopes of bringing the agency's "harassment campaign to an end, while ensuring that the SEC finally delivers, at long last, on its commitment to Tesla’s shareholders."                                                                                                                                                                                        , A spokesperson for the SEC declined to comment.                                                                                                                                                                                                                                                                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                 , The charges against Musk came in response to his now infamous tweet in which he claimed he had "funding secured" to take Tesla private at $420 per share. The SEC filed a lawsuit against Musk claiming he intentionally made "false and misleading" statements about Tesla’s privatization plans. The lawsuit also alleged he "knew or was reckless in not knowing" that his statements were false and/or misleading.                      , In addition to Tesla and Musk each paying $20 million in fines, the settlement requires Musk to vet any tweets related to Tesla with a lawyer before sending them out. Tesla was also required to add two new independent board directors and Musk was stripped of his chairman title. Under the terms of the settlement, Musk and Tesla neither admitted nor denied wrongdoing.                                                            , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                     , The letter to the court comes after Tesla revealed in a recent 10-K filing that the agency issued a subpoena in November 2021 seeking information on the company’s "governance processes around compliance with the SEC settlement, as amended."                                                                                                                                                                                            , The subpoena came shortly after Musk issued a poll on Twitter asking if he should sell 10% of his stake in Tesla.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-17 22:10:00 </td>
   <td style="text-align:left;"> Wall Street Set to Open Lower </td>
   <td style="text-align:left;"> US stock index futures slide on Thursday as worries of escalating geopolitical tensions in Eastern Europe and a disappointing US jobless claims report sent shockwaves through equities markets. NATO stated it had not seen Russia pulling back troops from Ukraine's borders, while Russian news reported mortars fired in eastern Ukraine. On the data front, The US labour department said that the number of Americans filing new claims for unemployment benefits increased by 23 thousand to 248 thousand in the week ended February 12th, compared with market expectations of 219 thousand. Investors also focused on less hawkish signals from US Federal Reserve's last meeting minutes. The central bank would not raise interest rates yet but strongly indicated a hike is on the way as soon as March, while it will start unwinding its nearly $9 trillion balance sheet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-17 22:10:00 </td>
   <td style="text-align:left;"> Brazilian Equities Snap 7-Day Rally </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, was down 0.3% to around 114,830 on Thursday, snapping a seven-day rally that sent the index to the highest since September 2021. Market sentiment was pulled down by falling commodities prices and heightened caution in global markets following news of clashes between Russian-backed separatists and the Ukrainian government forces in eastern Ukraine. At the same time, investors digested the latest FOMC minutes which sowed Fed officials were in favor of reining in accommodative monetary policy measures with a faster pace of rate increases and a "significant" reduction in the size of balance sheet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palladium </td>
   <td style="text-align:left;"> 2022-02-17 22:01:37 </td>
   <td style="text-align:left;"> Palladium is up by 5.68% </td>
   <td style="text-align:left;"> Palladium increased 5.68% to 2409 USD/t.oz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/17/goldman-ceo-david-solomon-raises-financial-targets-and-takes-victory-lap-after-exceeding-2020-goals.html </td>
   <td style="text-align:left;"> 2022-02-17 21:48:52 </td>
   <td style="text-align:left;"> Goldman CEO David Solomon raises financial targets, takes victory lap after crushing 2020 goals </td>
   <td style="text-align:left;"> , Goldman Sachs CEO David Solomon took a moment to bask in his firm's recent performance before raising the company's medium-term financial targets.                                                                                                                                                                                                                               , Solomon on Thursday reminded the audience at a Credit Suisse conference that back in 2020, at Goldman's first-ever Investor Day, he faced doubts after revealing a set of goals for a more profitable and efficient firm. But Goldman blew past those targets last year after a historic surge in trading and investment banking activity spurred on by the coronavirus pandemic., "Two years ago now, there was a lot of skepticism around the targets we laid out and what we thought we could accomplish," Solomon said. "When you look at our progress, obviously, we way exceeded the returns."                                                                                                                                                                , Goldman's new guidance for returns on tangible common shareholders' equity is 15% to 17%, up from the 14% target the bank had set in 2020. Still, the firm far exceeded those targets in 2021, when returns topped 24%.                                                                                                                                                          , The bank also increased its 2024 targets for gathering investments and fees in asset management and wealth management as well as transaction and consumer banking revenues.                                                                                                                                                                                                      , Shares of the bank dipped 2.4%, tracking the 2% decline of the KBW Bank Index.                                                                                                                                                                                                                                                                                                   , Solomon, who took over from predecessor Lloyd Blankfein in late 2018, has presided over a revival in the company's focus and share performance. Goldman has gained market share in traditional strengths including trading and investment banking, while building out new digital ventures in corporate cash management and consumer finance.                                    , When Credit Suisse analyst Susan Roth Katzke admitted that she was "probably a skeptic" that Goldman could reach a 60% efficiency ratio when it disclosed the target in 2020, Solomon corrected her.                                                                                                                                                                             , "You weren't probably a skeptic, you were a skeptic," Solomon interjected, before expressing confidence they could maintain the 60% target. The efficiency ratio is an industry metric that looks at expenses as a percentage of revenue; lower ratios show greater efficiency.                                                                                                  , "We feel great about the strategy," Solomon said. "We're very confident about our ability to move forward and continue to deliver very strong returns to shareholders."                                                                                                                                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/foreign-stock-investment </td>
   <td style="text-align:left;"> 2022-02-17 21:38:00 </td>
   <td style="text-align:left;"> Investment in Canadian Securities at 1-1/2-Year High </td>
   <td style="text-align:left;"> Foreign investors acquired C$37.6 billion of Canadian securities in December of 2021, following a downwardly revised C$30.1 billion in November. It was the 17th straight month of net purchases from foreigners and the largest amount since April of 2020. Foreign investors acquired C$20.6 billion in Canadian debt securities, of which C$12.8 billion in money market instruments, while C$7.8 billion were acquired in Canadian bonds, mainly through the federal government. At the same time, non-resident investors increased their overall exposure to the Canadian equity market by C$16.9 billion, the largest monthly gain since February of 2017 and rebounding from a C$1.3 billion reduction in November. Meanwhile, Canadian investors increased their holdings of foreign securities by C$21.3 billion, led by purchases of US instruments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/housing-starts </td>
   <td style="text-align:left;"> 2022-02-17 21:38:00 </td>
   <td style="text-align:left;"> US Housing Starts Post Biggest Drop in 6 Months </td>
   <td style="text-align:left;"> Housing starts in the US fell 4.1% mom to a seasonally adjusted annual rate of 1.638 million in January of 2022, well below forecasts of 1.7 million, and the lowest in 3 months, amid pandemic-related labour shortages while high material costs and supply constraints persist. Starts for single-family units declined 5.6% to 1.116 million and those for buildings with five units or more went down 2.1% to 0.51 million. Starts plunged in the Midwest (-37.7%) and declined 2% in the South, but increased 2.6% in the Northeast and 17.7% in the West. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/philadelphia-fed-manufacturing-index </td>
   <td style="text-align:left;"> 2022-02-17 21:34:00 </td>
   <td style="text-align:left;"> Factory Activity in Philadelphia Slows </td>
   <td style="text-align:left;"> The Philadelphia Fed Manufacturing Index in the US decreased to 16 in February of 2022 from 23.2 in January and missing market expectations of 20. The survey’s current indicators for general activity, new orders, and shipments declined from last month’s readings but remained positive. The employment index rose, and the price indexes remained elevated. The future indexes continue to indicate that the firms expect growth over the next six months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/jobless-claims </td>
   <td style="text-align:left;"> 2022-02-17 21:34:00 </td>
   <td style="text-align:left;"> US Weekly Jobless Claims Unexpectedly Rise </td>
   <td style="text-align:left;"> The number of Americans filing new claims for unemployment benefits increased by 23 thousand to 248 thousand in the week ended February 12th, compared with market expectations of 219 thousand. It was the first rise in 3 weeks with Missouri, Ohio and Kentucky contributing the most to the jump. Still, the level of claims remains significantly below a 3-month high of 290 thousand reached in mid-January, as Omicron infections eased following a surge across the US. The 4-week moving average which removes week-to-week volatility was 243.25 thousand, a decrease of 10.5 thousand and continuing claims were at 1.593 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/building-permits </td>
   <td style="text-align:left;"> 2022-02-17 21:32:00 </td>
   <td style="text-align:left;"> US Building Permits Beat Forecasts at 2006-High </td>
   <td style="text-align:left;"> Building permits in the United States rose 0.7 percent from a month earlier to a seasonally adjusted annual rate of 1.899 million in January of 2022, the highest since May of 2006, and above market expectations of 1.760 million. Single-family authorizations jumped 6.8 percent to a rate of 1,205 thousand while those for buildings with five units or more dropped 8.8 percent to a rate of 629 thousand. Permits increased significantly in the West (13.9 percent to 475 thousand) and the South (11.4 percent to 1,004 thousand). On the other hand, permits fell in the Northeast (-48.3 percent to 155 thousand and in the Midwest (-0.7percent to 265 thousand). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-17 21:29:00 </td>
   <td style="text-align:left;"> Gold Hits 35-week High </td>
   <td style="text-align:left;"> Gold topped the $1,890 mark on Thursday, extending its upward momentum to levels not seen since June of 2021 as investors worried about escalating geopolitical tensions involving the West, Russia, and Ukraine. NATO said it had not seen Russia pulling back troops from Ukraine's borders, while Russian news reported mortars fired in eastern Ukraine. Aside from safe-haven bids, minutes from the Federal Reserve's last meeting showed policymakers might not be as hawkish as investors feared, as it failed to provide any hints on a 50-basis points rate hike, driving the bullion higher. On top of that, a disappointing US jobless claims report has supercharged existing upward momentum for the bullion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/17/stocks-making-the-biggest-moves-premarket-walmart-autonation-cisco-and-others.html </td>
   <td style="text-align:left;"> 2022-02-17 20:57:15 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Walmart, AutoNation, Cisco and others </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                               , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                                                                     , Walmart (WMT) – Walmart stock rose 2.9% in the premarket after the retail giant reported better-than-expected quarterly results. Walmart earned an adjusted $1.53 per share, 3 cents above estimates, issued an upbeat forecast, and announced a dividend hike.                                                                                                                               , AutoNation (AN) – The auto retailer earned an adjusted $5.76 per share for the fourth quarter, beating the consensus estimate of $4.96. Revenue was also above estimates, driven by a 55% surge in used vehicle sales. AutoNation shares jumped 3% in premarket trading.                                                                                                                      , DoorDash (DASH) – DoorDash soared 24.1% in premarket trading after the food delivery service issued an upbeat outlook for the current quarter. Doordash reported a fourth-quarter loss but saw a 69% surge in revenue for 2021 even as restaurants reopened for dine-in service.                                                                                                              , Cisco (CSCO) – Cisco beat estimates by 3 cents with adjusted quarterly earnings of 84 cents per share. The networking equipment and software maker also reported better-than-expected revenue and issued an upbeat full-year forecast as it sees particularly strong demand from cloud computing companies. Cisco rose 3.5% in the premarket.                                                 , Nvidia (NVDA) – Nvidia reported adjusted quarterly earnings of $1.32 per share, 10 cents above estimates. The graphics chip maker also reported better-than-expected revenue for the quarter and gave an upbeat outlook. However, the stock came under pressure on concerns about flat profit margins and its exposure to the cryptocurrency market. Nvidia was down 2.5% in premarket action., Palantir Technologies (PLTR) – The software platform provider's stock slid 8% in premarket trading after quarterly earnings fell short of forecasts. Palantir's adjusted profit of 2 cents per share was half of what analysts predicted, although revenue exceeded forecasts.                                                                                                                , Tripadvisor (TRIP) – Tripadvisor tumbled in the premarket after reporting an unexpected quarterly loss and revenue that fell short of analyst forecasts. The travel review site operator said it expects significant improvement in the travel market this year after what it called "unexpected periods of virus resurgence" in 2021. Shares tumbled 7.9% in premarket trading.              , Fastly (FSLY) – Fastly shares plummeted 31.9% in the premarket after the internet content delivery company gave lower-than-expected 2022 guidance. Fastly reported a narrower-than-expected fourth-quarter loss and revenue that came in above consensus estimates.                                                                                                                           , Hasbro (HAS) – Hasbro rallied 4% in premarket trading after activist investor Alta Fox Capital Management nominated five directors to the toy maker's board. Alta Fox is pushing for Hasbro to spin off its fast-growing games unit.                                                                                                                                                          , Cheesecake Factory (CAKE) – The restaurant operator's shares jumped 4% in the premarket even though earnings came in below forecasts. A revenue beat was negated by increased input costs, but Cheesecake Factory is planning a price hike in new menus now being printed and said it may lift prices further later this year.                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bax:us </td>
   <td style="text-align:left;"> 2022-02-17 20:37:54 </td>
   <td style="text-align:left;"> Baxter International earnings above expectations at 1.04 USD </td>
   <td style="text-align:left;"> Baxter International (BAX) released earnings per share at 1.04 USD, compared to market expectations of 1.03 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/wmt:us </td>
   <td style="text-align:left;"> 2022-02-17 20:37:48 </td>
   <td style="text-align:left;"> Walmart earnings above expectations at 1.53 USD </td>
   <td style="text-align:left;"> Walmart (WMT) released earnings per share at 1.53 USD, compared to market expectations of 1.49 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/live/2022/02/17/business/stock-market-economy-news </td>
   <td style="text-align:left;"> 2022-02-17 20:34:40 </td>
   <td style="text-align:left;"> Stocks, Earnings and Business News: Live Updates - The New York Times </td>
   <td style="text-align:left;"> Vaccine mandates and P.C.R. tests for the event, set for March 27 in Los Angeles.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , S&amp;P 500                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , %                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Dow                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , %                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Nasdaq                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , %                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , As of                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Data delayed at least 15 minutes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , By Brooks Barnes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , After much internal discussion, the Academy of Motion Picture Arts and Sciences has come to an agreement on coronavirus safety measures for attendees of the 94th Oscars, which will be held on March 27 in Los Angeles: The audience of 2,500 invited guests — including all nominees — will be required to show proof of vaccination against the coronavirus and at least two negative P.C.R. tests.                                                                                                                                                                                                           , Performers and presenters also must undergo rigorous testing — but those people will not need to show proof of vaccination, a decision that an academy spokeswoman said on Thursday was in keeping with virus safety protocols on some television sets and return-to-work standards set by Los Angeles County.                                                                                                                                                                                                                                                                                                   , Under an agreement last year between entertainment unions and the Alliance of Motion Picture and Television Producers, production companies (in this case the academy) have the option to mandate vaccinations for cast and crew. But it is not a requirement, and some companies separate productions into zones, with different testing and social distancing requirements depending on how closely casts and crews need to work together.                                                                                                                                                                     , Face covering requirements also will vary, the academy said. Nominees and their guests will be seated in the orchestra and parterre areas of the Dolby Theater and will not be required to wear masks. These attendees will be seated with more spacing than usual. The Dolby seats 3,317 people and 2,500 people will be invited, the academy said.                                                                                                                                                                                                                                                             , Those in the mezzanine may be required to wear masks, as they will sit shoulder-to-shoulder. Infections are declining rapidly in Los Angeles County, and the academy said it was consulting with government officials, infectious disease experts and an independent vendor, Cosmos Health Solutions, on a policy.                                                                                                                                                                                                                                                                                               , Last week, following a report in The Hollywood Reporter that the academy was planning to forgo a vaccine mandate across the board, the organization was pummeled on social media by fans, stars, politicians and others for what appeared to be an effort to accommodate unvaccinated celebrities. Seth MacFarlane, who hosted the Oscars in 2013, was among those who criticized the academy on Twitter.                                                                                                                                                                                                        , Really, Oscars? This would seem, from the outside looking in, a colossal abdication of responsible management. I cannot fathom what piece of information we might be missing that would justify this. https://t.co/9T54TAdIGX                                                                                                                                                                                                                                                                                                                                                                                    , The academy declined to say anything publicly about The Hollywood Reporter’s article, but officials insisted that no decisions had been made.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Coronavirus safety protocols have been changing rapidly as infections have declined. On Tuesday, Disney eased its mask mandate for fully vaccinated theme park visitors in California and Florida. This week, the Coachella Valley Music and Arts Festival said attendees (up to 125,000 fans a day in the prepandemic era) would not be required to be vaccinated, tested or masked.                                                                                                                                                                                                                            , According to government data, 1,713 coronavirus-positive patients were hospitalized in Los Angeles County as of Thursday, a 54 percent decline since Feb. 1. Over the last week, the county has reported an average of about 4,100 new cases per day, a decline of 77 percent from two weeks ago.                                                                                                                                                                                                                                                                                                                , The academy’s decision puts it at odds with some award shows that are scheduled to take place in the weeks before the Oscars, including the Critics Choice Awards on March 13. Joey Berlin, the force behind the awards, told The Hollywood Reporter that everyone involved would be vaccinated. “I can’t invite people to a show where they’re not going to feel safe,” he said.                                                                                                                                                                                                                                , The academy emphasized on Thursday that it would be in direct touch with nominees and studios to walk them through the various safety requirements.                                                                                                                                                                                                                                                                                                                                                                                                                                                              , By Neal E. Boudette                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The federal government’s main auto-safety regulator has opened a preliminary investigation into sudden braking by Tesla cars equipped with an advanced driver-assistance system that the company calls Autopilot.                                                                                                                                                                                                                                                                                                                                                                                                , The National Highway Traffic Safety Administration said in a document posted online this week that it was acting in response to 354 consumer complaints from the last nine months about “phantom braking” — when Teslas brake unexpectedly when no hazards are in the road.                                                                                                                                                                                                                                                                                                                                      , The investigation focuses on Tesla Model 3 compact sedans and Model Y hatchbacks that were made in 2021 and 2022 and sold in the United States. The agency said that covers about 416,000 cars. The preliminary inquiry is intended to determine the scope and severity of the problem.                                                                                                                                                                                                                                                                                                                          , The complaints claim that the vehicle “unexpectedly applies its brakes while driving at highway speeds,” the safety agency wrote in a summary of the investigation. “Complainants report that the rapid deceleration can occur without warning, at random, and often repeatedly.”                                                                                                                                                                                                                                                                                                                                , Tesla did not respond to a request for comment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The investigation is the latest safety concern that Tesla has been confronted with. Separately this year, Tesla recalled 54,000 cars equipped with its Full Self-Driving software to disable a feature that in certain conditions let the vehicles roll slowly through intersections without stopping. Failing to stop at a stop sign can increase the risk of a crash, the safety agency told Tesla in a letter.                                                                                                                                                                                                , The agency also opened a formal investigation last year into Autopilot and how it identifies objects and other vehicles on the road. That inquiry was prompted by 11 incidents in which Teslas operating in Autopilot failed to stop for and crashed into police cars, fire trucks and other emergency vehicles that had flashing lights turned on.                                                                                                                                                                                                                                                              , In the last few months, Tesla recalled 12,000 cars to correct a braking problem and recalled 458,000 others for two separate mechanical defects. It also agreed to turn off a feature that allowed drivers or front passengers to play video games on the dashboard touch-screen while car were in motion. The problem had been highlighted in The New York Times, and the safety agency pressed the company to address it.                                                                                                                                                                                      , By Coral Murphy Marcos and William P. Davis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Feb. 16
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Feb. 17
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , 4,380
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,400
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,420
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,440
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,460
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 4,480
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Data delayed at least 15 minutes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , By: Ella Koeze                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Stocks slid on Thursday, extending a volatile stretch of trading brought on by uncertainty about inflation, rising interest rates and the potential for war in Europe.                                                                                                                                                                                                                                                                                                                                                                                                                                           , The S&amp;P 500 fell 2.1 percent, dropping into negative territory for the week, while the Nasdaq composite fell 2.9 percent.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Tech companies were some of the worst performers, with Meta, Facebook’s parent, down more than 4 percent. Alphabet, Google’s parent, fell 3.8 percent, and Microsoft was down 2.9 percent.                                                                                                                                                                                                                                                                                                                                                                                                                       , Tesla, one of the largest companies in the S&amp;P 500, dropped 5.1 percent. The main auto-safety regulator in the United States said it was investigating reports from Tesla’s customers of “phantom braking” when they were using their vehicles’ driver-assistance system.                                                                                                                                                                                                                                                                                                                                        , Shares of banks also fell, with Morgan Stanley dropping 5 percent and Wells Fargo losing 3.4 percent.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The prospect that President Vladimir V. Putin will order a Russian invasion of Ukraine has weighed on global markets. On Tuesday, the stock market rose after Russian officials announced a partial troop withdrawal from the Ukrainian border. But President Biden said on Thursday that the possibility of an invasion remained “very high,” and shelling between Ukraine and Russia-backed separatists spiked, raising concerns that the conflict was heating up.                                                                                                                                             , “Markets are concerned about the Russian troop buildup and a lack of trust in Putin’s declaration that they are beginning to remove troops from the region,” said Chris Zaccarelli, the chief investment officer for Independent Advisor Alliance, an investment advisory firm.                                                                                                                                                                                                                                                                                                                                  , Investors have also been anticipating that the Federal Reserve will increase interest rates as it looks to fight persistently high inflation. Raising the Fed’s policy rate can lead to higher interest rates for houses and cars, causing spending to slow and inflation to moderate. But it also can increase the return on bonds, making riskier investments like stocks less appealing.                                                                                                                                                                                                                      , Minutes released on Wednesday from the Fed’s January meeting showed that most officials agreed that they might need to withdraw their support for the economy even more quickly if inflation does not cool down as they expect. Investors are now anticipating that the Fed’s policy rate could rise to more than 1.75 percent by the end of the year, up from nearly zero.                                                                                                                                                                                                                                      , Yields on the 10-year Treasury note, which last week crossed 2 percent for the first time since 2019, fell about eight basis points, or 0.08 percentage points, to about 1.96 percent. Yields fall as prices for bonds rise, which happens when investors buy them as they move money out of riskier investments like stocks.                                                                                                                                                                                                                                                                                    , But the broad nature of Thursday’s sell-off pointed to more than one trigger. Oil has been trading at prices not seen since 2014, and an invasion by Russia, a big oil producer and Europe’s largest supplier of natural gas, would almost certainly push energy prices higher. But on Thursday, oil fell, with West Texas Intermediate, the U.S. crude benchmark, down 2 percent, to $91.76 a barrel. Natural gas fell more than 4 percent.                                                                                                                                                                     , “The concerns for growth going forward and recession risks are new to traders’ minds,” said Edward Moya, a senior market analyst at OANDA. “There’s a lot of fear that the optimistic growth outlook for 2023 is up in the air.”                                                                                                                                                                                                                                                                                                                                                                                 , Markets have been volatile for months, with concerns about the Omicron variant’s impact on the economy in November and December bleeding into uncertainty in January and February about persistently high inflation and how the Fed will react to it. Thursday’s drop was the S&amp;P 500’s worst day in only two weeks, and if the index ends this week in the red it will be its fifth weekly drop just seven weeks into the year. The index is down 8.7 percent since its Jan. 3 high. The Nasdaq composite peaked on Nov. 19, just before the Omicron variant was disclosed, and is down 14.6 percent since then., The consumer staples sector was one of the few that did not fall on Thursday. Walmart was one of the best-performing companies in the S&amp;P 500, climbing 4 percent after it reported that its revenue rose to $152.9 billion, up 0.5 percent in the three months ending in January from a year earlier. The company also said that sales across its U.S. business increased 5.7 percent to about $105 billion in the quarter.                                                                                                                                                                                     , AutoNation fell 3.8 percent, as the company’s chief executive said it was difficult to forecast whether it could sustain its current high profit levels in 2022. The company reported on Thursday a profit of $387 million in its latest quarter, more than double its profit from a year earlier, while revenue rose 14 percent to $6.6 billion.                                                                                                                                                                                                                                                                , In Europe, stock indexes edged lower. The Stoxx Europe 600 fell 0.7 percent on Thursday. Asian markets closed mixed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , By Madeleine Ngo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , A coalition of labor unions representing tens of thousands of airline industry workers urged the Justice Department to step up its prosecutions of unruly passengers on Thursday.                                                                                                                                                                                                                                                                                                                                                                                                                                , In a letter to Attorney General Merrick B. Garland, the group asked the department to pursue and prioritize prosecutions of people who assault passenger service agents, many of whom have been attacked at airport gates, ticket and reservation areas and other airport locations during the pandemic.                                                                                                                                                                                                                                                                                                         , The request comes at a turbulent time for the airline industry, which began to see a spike early last year in violent and disruptive passengers who have refused to follow Covid protocols and attempted to interfere with flight crew.                                                                                                                                                                                                                                                                                                                                                                          , “The department has not meaningfully pursued federal penalties against individuals who assault or interfere with passenger service agents,” the letter said. It was signed by six labor organizations, including the A.F.L.-C.I.O.’s Transportation Trades Department, the Association of Flight Attendants-C.W.A. and the International Brotherhood of Teamsters.                                                                                                                                                                                                                                               , Greg Regan, the president of the A.F.L.-C.I.O.’s Transportation Trades Department, said he was pleased to see the Justice Department take some steps to address the rise in violent incidents aboard planes, but that more work needed to be done in response to assaults against passenger service agents.                                                                                                                                                                                                                                                                                                      , “When you see this sort of widespread violence and abuse toward transportation professionals, this is where leadership from the federal government is vital,” Mr. Regan said.                                                                                                                                                                                                                                                                                                                                                                                                                                    , The Justice Department declined to comment on the letter Thursday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The department said in November it would prioritize the prosecution of federal crimes on commercial aircraft, but many airline and airport workers have still been unsatisfied with the federal government’s pace of action. There have been 499 unruly passenger reports since the beginning of the year, but only 80 cases have been referred to the F.B.I. for criminal review as of Feb. 15, according to data from the Federal Aviation Administration. In 2021, there were 5,981 unruly passenger reports.                                                                                                 , Over the past few months, passenger service agents have experienced “serious incidents of physical and verbal assault and harassment,” according to a Feb. 10 letter some of the labor organizations sent to federal officials. The groups pointed to a case at Charlotte Douglas International Airport last year, when an intoxicated passenger physically and verbally assaulted gate agents who had denied him access to a flight.                                                                                                                                                                            , Airline executives and workers have recently implored the federal government to add unruly passengers to a federal no-fly list to bar them from commercial flights. Earlier this month, the chief executive of Delta Air Lines wrote to Mr. Garland arguing that it was a “much-needed step” toward addressing the surge in violence aboard planes and preventing future incidents.                                                                                                                                                                                                                              , But some Republican senators have pushed back on those calls. Eight Republican senators, led by Senator Cynthia Lummis of Wyoming, sent a letter to Mr. Garland on Monday arguing that many of the violent incidents were related to mask mandates on planes and that creating such a list would equate those passengers with terrorists.                                                                                                                                                                                                                                                                        , “The creation of this list by D.O.J. would result in a severe restriction on the ability of citizens to fully exercise their constitutional right to engage in interstate transportation,” the senators wrote. “It also raises serious concerns about future unrelated uses and potential expansions of the list based on political pressures.”                                                                                                                                                                                                                                                                  , Union leaders have condemned the senators’ objections and said that disruptive passengers remain a threat to flight attendants and passengers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , “We’ve been punched, kicked, spit on and sexually assaulted,” Sara Nelson, the president of the Association of Flight Attendants-C.W.A., which represents nearly 50,000 workers at 17 airlines, said in a statement on Tuesday. “This puts everyone at risk and disrupts the safety of flight, which is never acceptable.”                                                                                                                                                                                                                                                                                       , By Lananh Nguyen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Marcus is finally old enough to have a checking account.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , More than five years after Goldman Sachs started its consumer-focused Marcus division, the company said it would begin offering perhaps the most essential of banking services.                                                                                                                                                                                                                                                                                                                                                                                                                                  , “Checking is an important piece that will be added to the puzzle in 2022,” David M. Solomon, the bank’s chief executive, said in an interview Thursday. Such accounts are the starting point for consumers to seek other financial services and will allow Goldman to build “a real digital bank,” he said.                                                                                                                                                                                                                                                                                                      , Long focused on its corporate clientele and deal-making, Goldman started Marcus — named for the bank’s founder, Marcus Goldman — in 2016 with the goal of competing against other Wall Street banks that offer basic services to everyday customers.                                                                                                                                                                                                                                                                                                                                                             , As an online-only division, Marcus initially offered lending and savings products and established a toehold with Main Street customers. It teamed with Apple and General Motors on credit cards. But Goldman’s retail business is still dwarfed by competitors that have trillions of dollars in combined deposits and maintain traditional bank branches with A.T.M.s and tellers.                                                                                                                                                                                                                              , Mr. Solomon said that adding checking accounts would make Marcus easier to use, allowing customers to treat its app as a one-stop shop for all their financial needs.                                                                                                                                                                                                                                                                                                                                                                                                                                            , Goldman reported $1.5 billion in revenue from Marcus last year and aims to increase that to more than $4 billion in 2024, according to a presentation outlining its new financial targets.                                                                                                                                                                                                                                                                                                                                                                                                                       , Goldman has a rosy outlook for its core investment-banking and trading units, which have experienced a windfall during the pandemic. In particular, the bank’s business advising corporate clients on mergers and acquisitions has a strong pipeline of deals in the works, Mr. Solomon said.                                                                                                                                                                                                                                                                                                                    , As companies adapt to rising inflation and the prospect of higher interest rates, Goldman will benefit from its clients’ retooling their businesses, even if financial markets weaken, he said.                                                                                                                                                                                                                                                                                                                                                                                                                  , “That’s the biggest thing that’s shifted at a high level,” Mr. Solomon told investors on Thursday. “We’re moving from an environment of very, very easy money and below-trend inflation, which really hasn’t been a long-term trend, to an environment of tighter money and above-trend inflation.”                                                                                                                                                                                                                                                                                                              , Goldman Sachs reported a record profit of $21.6 billion last year, but its earnings fell in the fourth quarter as it bumped up pay, joining the rest of the industry in raising compensation in an intensifying war for talent.                                                                                                                                                                                                                                                                                                                                                                                  , By Ana Swanson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The Biden administration on Thursday added WeChat’s e-commerce ecosystem and AliExpress, an e-commerce site owned by Alibaba, to an annual list of markets that the United States says engage in counterfeiting and copyright violations.                                                                                                                                                                                                                                                                                                                                                                        , The administration said the activities caused significant financial losses for American businesses and workers and posed risks to consumer safety last year.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The Biden administration also removed from the list several of Amazon’s foreign stores, which the Trump administration had added for the first time to its report released in January last year.                                                                                                                                                                                                                                                                                                                                                                                                                 , The inclusion of Amazon’s stores in Britain, Canada, France, Germany and India prompted an outcry from the company, which claimed that its inclusion was driven by a “personal vendetta” on behalf of the Trump administration, despite consumer complaints about fake products on the platform.                                                                                                                                                                                                                                                                                                                 , The new report, released by the Office of the United States Trade Representative, identified 42 online markets and 35 physical markets that sold or eased trade in a wide array of counterfeit or pirated goods, including fake Nike products, pirated books and academic papers, music files and virtual items like video games.                                                                                                                                                                                                                                                                                , The list included several major Chinese e-commerce businesses, like Taobao, an e-commerce site owned by Alibaba; DHGate, a business-to-business e-commerce platform; and Baidu Wangpan, a cloud storage service that allows users to share pirated movies, TV shows and books.                                                                                                                                                                                                                                                                                                                                   , In a statement, Alibaba said that it looked forward to continuing to work with governments to understand and address concerns about intellectual property protection across its platforms.                                                                                                                                                                                                                                                                                                                                                                                                                       , “We know the challenges in I.P. protection and remain fully committed to advancing our leadership in this area,” the company said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The office said some countries had made progress in cracking down on the sale of counterfeit goods, including Brazil, the Philippines, Thailand and the United Arab Emirates. It also said it had documented a shift of pirated goods from physical marketplaces to online, in part because the pandemic depressed global tourism.                                                                                                                                                                                                                                                                               , The report also identified a new ecosystem: “piracy-as-a-service,” in which operators offer website templates, databases of infringed video content or other features that make it easy for customers to set up pirate operations.                                                                                                                                                                                                                                                                                                                                                                               , “The global trade in counterfeit and pirated goods undermines critical U.S. innovation and creativity and harms American workers,” Katherine Tai, the United States trade representative, said in a statement. “This illicit trade also increases the vulnerability of workers involved in the manufacturing of counterfeit goods to exploitative labor practices, and the counterfeit goods can pose significant risks to the health and safety of consumers and workers around the world.”                                                                                                                     , The report also examined the impact of counterfeit goods on the people who make them, part of the administration’s focus on how trade affects workers. Because these businesses operate outside the law, counterfeiting and piracy often go hand in hand with unsafe working conditions, child labor, forced labor and other issues, the trade representative’s office said.                                                                                                                                                                                                                                     , “Counterfeit manufacturing often occurs in clandestine work places outside the reach of labor market regulations and inspection systems, which increases the vulnerability of workers to exploitative labor practices,” the report said.                                                                                                                                                                                                                                                                                                                                                                         , The report will result in no immediate penalties for the named companies, though it said the goal of publishing such a list was to “motivate appropriate action by the private sector and governments.”                                                                                                                                                                                                                                                                                                                                                                                                          , Congress is mulling some actions that could clamp down on Chinese e-commerce sales, including counterfeit goods, to the United States as part of a major legislative effort at promoting U.S. economic competitiveness with China.                                                                                                                                                                                                                                                                                                                                                                               , One provision, proposed by Representative Earl Blumenauer, Democrat of Oregon, would raise the threshold for the dollar value of a good that could come into the United States duty free from certain countries, namely China.                                                                                                                                                                                                                                                                                                                                                                                   , That level, called de minimis, is set at $800 in the United States. That’s far above the level in many other countries, a policy that critics say has led to an explosion of imported e-commerce packages, including some unsafe and illicit goods.                                                                                                                                                                                                                                                                                                                                                              , By Michael Corkery                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Walmart navigated rising inflation and fickle consumer confidence in its fourth quarter, as sales rose and profit increased, beating analysts’ expectations.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The nation’s largest retailer said on Thursday that its total revenue rose to $152.9 billion in the three months ending in January, up 0.5 percent from a year earlier, while operating income increased 7.3 percent to $5.9 billion.                                                                                                                                                                                                                                                                                                                                                                            , The company reported earnings per share of $1.53, which was higher than the $1.50 many analysts expected.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , “We had another strong quarter to finish off a strong year,” the company’s chief executive, Doug McMillon, said in a statement. “We have momentum in our business in all three segments. We’re being aggressive with our plans and executing on the strategy.”                                                                                                                                                                                                                                                                                                                                                   , A day earlier, the Commerce Department reported that retail sales jumped 3.8 percent in January from the prior month, a sign of the economy’s resilience in the pandemic. The increase was attributed to greater consumer spending but also, in part, to fast-rising prices.                                                                                                                                                                                                                                                                                                                                     , As the largest grocery chain in the country, Walmart is especially susceptible to the effects of inflation, which has reached its highest level in four decades in the United States. The company, which employs more than 1.6 million in the United States, has also been raising wages to compete for workers amid high turnover in the retail industry during the pandemic.                                                                                                                                                                                                                                   , The company’s sales in the quarter across its U.S. business increased 5.7 percent to about $105 billion, while gross profit margins increased slightly. Asked about inflation on a conference call with analysts, Walmart executives said the company was managing inflationary pressures, but did not go into details about whether cost increases were being passed along to customers.                                                                                                                                                                                                                        , Walmart said that it expected total sales growth of about 4 percent in the coming year and that it was raising its annual dividend by 2 percent to $2.24 per share.                                                                                                                                                                                                                                                                                                                                                                                                                                              , Walmart’s stock price was up 4 percent at the close of trading on Thursday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , By Neal E. Boudette                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The tight supplies of new and used cars that have damped auto sales and pushed prices higher have not eased and are likely to linger well into this year, according to AutoNation, the country’s largest automotive retailer.                                                                                                                                                                                                                                                                                                                                                                                    , Half of all new Chevrolets, Fords, Toyotas and other major brands  arriving on dealer lots in the next 90 days are already sold, AutoNation said. The market is even tighter for luxury cars: Nearly three out of four of those cars arriving at dealers in the next three months will be “presold” — meaning a customer has paid a deposit and is waiting to buy the car as soon as it arrives.                                                                                                                                                                                                                 , “This tight-inventory situation is going to be around certainly through the first half,” said AutoNation’s chief executive, Mike Manley. “I’m hoping we do see some improvement in the second half.”                                                                                                                                                                                                                                                                                                                                                                                                             , Selling cars before they arrive from the assembly plant is a substantial change from the traditional industry practice of stocking dealers with hundreds or even thousands of vehicles that can sit for months before they are sold. It also means automakers will have a long road to restocking dealer lots with new vehicles.                                                                                                                                                                                                                                                                                 , The shortage stems from the early days of the pandemic, in 2020, when auto plants shut down for nearly two months. The problem was compounded by a shortage of computer chips, which has forced manufacturers over the last 12 months to idle plants temporarily for weeks at a time.                                                                                                                                                                                                                                                                                                                            , The tight supply has enabled dealers to sell cars at their full list price, or even more.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Those higher prices helped AutoNation reap record earnings in the final quarter of 2021, the company said Thursday. The company reported a profit of $387 million, more than double the profit from a year earlier. Revenue rose 14 percent, to $6.6 billion.                                                                                                                                                                                                                                                                                                                                                    , The profit jumped despite a 20 percent decline in sale of new cars, to 57,601, a reflection of the higher prices. Sales of used cars, prices of which have also risen substantially, increased 21 percent to 74,442.                                                                                                                                                                                                                                                                                                                                                                                             , Mr. Manley said it was difficult to forecast whether AutoNation could sustain such high profit levels this year. The supply of vehicles and the chances of increasing new-vehicle sales depend heavily on whether the computer chip shortage improves, as automakers are hoping. The Federal Reserve has also indicated that it is likely to raise interest rates, which would increase the cost of financing vehicle purchases.                                                                                                                                                                                 , “The profitability that we’ve been able to develop puts us in a good position,” he said. “But one thing I don’t want to predict is what’s going to happen in the full industry, because you have a lot of moving pieces.”                                                                                                                                                                                                                                                                                                                                                                                        , By Madeleine Ngo and Chris Cameron                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , WASHINGTON — Steve Dickson, the administrator of the Federal Aviation Administration, will resign at the end of next month, the agency said on Wednesday night.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The announcement by Mr. Dickson, who was appointed by President Donald J. Trump, cut short a five-year term after a tumultuous period for the F.A.A. In a letter to staff, Mr. Dickson said it was “time to go home” to his family after 43 years in the aviation industry and more than two years leading the agency.                                                                                                                                                                                                                                                                                           , “Over the past several years, my family has been a source of tremendous encouragement, strength and support,” Mr. Dickson said. “Nevertheless, after sometimes long and unavoidable periods of separation from my loved ones during the pandemic, it is time to devote my full time and attention to them.”                                                                                                                                                                                                                                                                                                      , He said the F.A.A. was in a “better place” than it was two years ago, adding that the agency had reinvigorated its safety culture, overcome some of its toughest challenges and “built a stronger, more collaborative, inclusive and open culture.”                                                                                                                                                                                                                                                                                                                                                              , Mr. Dickson sometimes came under heavy criticism from lawmakers as he responded to a series of challenges at the agency, but on Wednesday night, Transportation Secretary Pete Buttigieg praised him as “the F.A.A.’s steady and skilled captain.”                                                                                                                                                                                                                                                                                                                                                               , “His tenure has been marked by steadfast commitment to the F.A.A.’s safety mission and the 45,000 employees who work tirelessly every day to fulfill it,” Mr. Buttigieg said in a statement.                                                                                                                                                                                                                                                                                                                                                                                                                     , Mr. Dickson, a U.S. Air Force Academy graduate and former pilot who rose to become senior vice president of flight operations at Delta Air Lines, took charge of the F.A.A. as it was reeling after two deadly crashes that grounded Boeing’s 737 Max jet for almost two years.                                                                                                                                                                                                                                                                                                                                  , Congress and safety experts condemned the agency for lapses in oversight that helped lead to the crashes, which killed 346 people. Mr. Dickson, who took over the agency months after the Max was grounded, oversaw revisions to the aircraft that allowed the fleet to eventually resume commercial flights.                                                                                                                                                                                                                                                                                                    , He then had to navigate a cascade of disruptions to air travel from the Covid-19 pandemic, including new airline safety regulations, travel restrictions, a severe decline in commercial air traffic and a surge in unruly passengers that has led some airline executives to call for a federal no-fly list for those convicted of disrupting flights.                                                                                                                                                                                                                                                          , The agency had to confront concerns that a nationwide expansion of 5G cellular networks could interfere with sensitive aircraft instruments. The F.A.A. negotiated a compromise with cellular providers in January to partly delay the rollout of 5G service near airport runways.                                                                                                                                                                                                                                                                                                                               , Mr. Dickson was confirmed in an unusually divided Senate vote in July 2019 after some Democrats raised concerns about his involvement in a whistle-blower case at Delta. The agency had been without permanent leadership for more than a year and a half before his confirmation.                                                                                                                                                                                                                                                                                                                               , Representative Peter A. DeFazio, an Oregon Democrat and the chairman of the Transportation and Infrastructure Committee, said that although he “didn’t always see eye to eye” with Mr. Dickson, he thanked him for his leadership during a challenging time for the agency.                                                                                                                                                                                                                                                                                                                                      , “President Biden must now nominate a new leader committed to the highest standards of aviation safety,” Mr. DeFazio said in a statement.                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , By Stacy Cowley                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The Education Department will cancel federal student loans for at least 1,800 students who attended DeVry University, once one of the nation’s largest for-profit college chains, because it fraudulently lured in applicants for years with vastly inflated claims about their career prospects.                                                                                                                                                                                                                                                                                                                , While the department has stepped up its discharges of debts for students who were victimized by their schools, the decision announced on Wednesday is its first approval of fraud claims involving a school that is still operating.                                                                                                                                                                                                                                                                                                                                                                             , The claims approved on Wednesday are just the start, officials said. They want other students who attended DeVry during the time it was making its false promises to apply for relief.                                                                                                                                                                                                                                                                                                                                                                                                                           , Between 2008 and 2015, department officials said, DeVry advertised that 90 percent of its graduates found work in their field of study within six months. In reality, only 58 percent did. School officials knew of the discrepancy and ignored complaints about it from alumni, department officials said.                                                                                                                                                                                                                                                                                                      , Until Wednesday, the department had taken action only against schools that had closed down, including large chains like Corinthian Colleges and smaller ones like the Marinello Schools of Beauty.                                                                                                                                                                                                                                                                                                                                                                                                               , “We do think that it is really important to show that we are willing to take these actions against open schools, and that there will be liabilities for the current owners of open schools,” James Kvaal, the under secretary of education, said at a news conference.                                                                                                                                                                                                                                                                                                                                           , While noting that the claims occurred when DeVry was under different leadership, a school spokeswoman, Donna Shaults, said DeVry believed that the Education Department had mischaracterized the school’s statements about its graduates’ outcomes.                                                                                                                                                                                                                                                                                                                                                              , “We do not agree with the conclusions they have reached,” she said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Officials cast Wednesday’s action as one of several moves to revitalize an Education Department enforcement arm that was eviscerated during the Trump administration. Betsy DeVos, President Donald J. Trump’s education secretary, repeatedly stymied investigations into for-profit schools and appointed Julian Schmoke — a former dean at DeVry — to lead the agency’s enforcement division.                                                                                                                                                                                                                 , For four years, Ms. DeVos’s agency approved no new grounds for claims from defrauded students, and rejected 130,000 in what amounted to rubber-stamp denials. Those rejections, and other stalled claims that sat undecided for years, are now the subject of a class-action lawsuit involving some 200,000 borrowers.                                                                                                                                                                                                                                                                                           , The Education Department said in a court filing last month that it was close to settling that case and hoped to announce a deal by April.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The 1,800 former DeVry students approved for relief through the student fraud claim discharge system, known as “borrower defense to repayment,” will have nearly $72 million in loans forgiven.                                                                                                                                                                                                                                                                                                                                                                                                                  , That means they will not have to repay loans made with taxpayer money. The department said it would pursue DeVry’s current owner, Cogswell Capital, for compensation.                                                                                                                                                                                                                                                                                                                                                                                                                                            , Cogswell Capital is an investment firm run by Bradley Palmer, a venture capitalist and financier. Mr. Palmer, who had no experience working in higher education, bought DeVry in 2018 from Adtalem Global Education, which operated several for-profit schools. Adtalem had called itself DeVry but changed its name in 2017 after a series of scandals involving the school.                                                                                                                                                                                                                                    , In 2016, DeVry agreed to pay $100 million to settle a Federal Trade Commission lawsuit over its misleading claims about its graduates’ careers and earnings. A year later, DeVry settled similar claims brought by New York and Massachusetts.                                                                                                                                                                                                                                                                                                                                                                   , A message left at Palm Ventures, which Mr. Palmer has described as a family office that manages his family’s assets, was not immediately returned. A representative for Adtalem did not immediately return a message seeking comment.                                                                                                                                                                                                                                                                                                                                                                            , The Education Department said it had also approved borrower defense claims from former students at ITT Technical Institute’s nursing program, the Minnesota School of Business (also known as Globe University) and Westwood College. Including DeVry, the approvals announced on Wednesday will wipe out $415 million in debt for 16,000 borrowers.                                                                                                                                                                                                                                                             , By Rebecca Robbins                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The Republican attorney general of Texas on Wednesday sued to strike down the Biden administration’s mandate requiring travelers to wear masks at airports, on airplanes and on commuter bus and rail systems.                                                                                                                                                                                                                                                                                                                                                                                                   , The suit comes as many governors, including in states governed by Democrats, have been rolling back mask mandates for indoor public settings as infections from the Omicron variant of the coronavirus have plummeted following a record-setting surge last month. But forms of public transportation are regulated by the federal government.                                                                                                                                                                                                                                                                   , Since it was first introduced a year ago, the federal mandate requiring travelers to wear masks has been extended several times, most recently until at least March 18. Brief breaks for eating and drinking are permitted. There are exemptions for travelers younger than 2 and for people with certain disabilities who cannot wear masks safely. Travelers who refuse to comply can be fined.                                                                                                                                                                                                                , The suit by the Texas attorney general, Ken Paxton, was filed in federal court in Fort Worth. It argues that the mask mandate is unconstitutional and that the Centers for Disease Control and Prevention lacks the authority to impose the requirement. The Supreme Court recently declined to hear another case that sought to block the mandate.                                                                                                                                                                                                                                                              , Dr. Anthony Fauci, the nation’s top infectious disease expert, said in December that he did not believe the country was approaching a point where masks would no longer be necessary on planes. “Even though you have a good filtration system, I still believe that masks are a prudent thing to do, and we should be doing it,” he said.                                                                                                                                                                                                                                                                       , The C.D.C. declined to comment on the suit in Texas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Some airline executives have questioned the need for the mask mandate for air travel. The top executive of Southwest Airlines, Gary Kelly, said at a Senate hearing in December that he believed that masks do not add substantial protection in airplane cabins and that the filtration on planes was sufficient. Mr. Kelly, who testified unmasked and recently became the company’s executive chairman after many years as chief executive, tested positive for the virus later that week.                                                                                                                    , By Matthew Goldstein                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A key witness in the bribery and money-laundering trial of a former Goldman Sachs executive said the scheme to loot billions of dollars from a Malaysian sovereign wealth fund was laid out a decade ago inside the apartment of a flamboyant Asian businessman who remains on the run.                                                                                                                                                                                                                                                                                                                          , Tim Leissner, a former Goldman partner who has pleaded guilty in the scheme, testified in Brooklyn federal court on Wednesday that the businessman, Jho Low, had told him and the defendant, his former colleague Roger Ng, about the plan to pay up to $1 billion in bribes to foreign officials.                                                                                                                                                                                                                                                                                                               , Mr. Ng’s trial began on Monday and is expected to last several weeks. It will most likely be the only trial that will take place on U.S. soil over the looting of the Malaysian fund known as 1MDB. Mr. Leissner and a Goldman Sachs subsidiary have already pleaded guilty in the case while Mr. Low, a free-spending financier who liked to host lavish parties in Las Vegas and Los Angeles, remains a fugitive.                                                                                                                                                                                              , Mr. Leissner, who said he had been “close friends” with Mr. Ng as well as his supervisor for Goldman in Asia, was the first prosecution witness to draw Mr. Ng into the center of the brazen scheme to loot the 1MDB fund.                                                                                                                                                                                                                                                                                                                                                                                       , Prosecutors around the globe have said the money raised for the fund was supposed to finance infrastructure projects to benefit the Malaysian people, but was instead used to finance lavish spending by Mr. Low and others close to the country’s former prime minister, Najib Razak.                                                                                                                                                                                                                                                                                                                           , Mr. Leissner said Mr. Low hosted the 2012 meeting at his London apartment. There, Mr. Low described in detail all the government officials who would be paid bribes in order for Goldman to secure the rights to arrange billions of dollars in bond offerings for the 1MDB fund, Mr. Leissner testified.                                                                                                                                                                                                                                                                                                        , Mr. Low also told the former Goldman executives that the bribe money would have to come from the proceeds of the bond offering — and that they would get some of those proceeds as well, according to Mr. Leissner.                                                                                                                                                                                                                                                                                                                                                                                              , “Roger and I were told by Jho that we would be taken care of,” Mr. Leissner said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Mr. Leissner said he had known that the scheme was illegal but it did not bother him because securing the bond deals for Goldman would have produced big fees for the Wall Street bank. “I wanted to be a hero at Goldman Sachs,” he said.                                                                                                                                                                                                                                                                                                                                                                       , It was Mr. Ng who originally introduced Mr. Leissner and several others at Goldman to Mr. Low in 2008, Mr. Leissner testified. He added that he and Mr. Ng soon realized that Mr. Low was the key to getting the bond underwriting work for Goldman, even though he had no position at 1MDB.                                                                                                                                                                                                                                                                                                                     , “He never had any official role yet he was the key decision maker,” Mr. Leissner said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Mr. Low, who has also been charged with bribery and money laundering, is believed to be residing in China.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Mr. Leissner said he and Mr. Ng both kept their dealings with Mr. Low from most of their Goldman colleagues after the bank had officially rejected their efforts to bring him in as a wealth management client. While several bankers at Goldman did know that Mr. Low was serving as a middleman on the 1MDB negotiations, only he and Mr. Ng knew the details of the looting of the fund, Mr. Leissner said.                                                                                                                                                                                                   , On cross-examination, lawyers for Mr. Ng are expected to question Mr. Leissner on his character and his claims about the degree of Mr. Ng’s involvement in the 1MDB negotiations.                                                                                                                                                                                                                                                                                                                                                                                                                                , Defense lawyers could draw from a dossier that Goldman had put together presenting Mr. Leissner as a master con artist, while the bank was negotiating its own deal with prosecutors and regulators. In his opening statement on Monday, Marc Agnifilo, one of Mr. Ng’s lawyers, sought to call Mr. Leissner’s character into question, calling him a “double bigamist” and claiming that he was twice married to two women at the same time.                                                                                                                                                                    , Today in the On Tech newsletter, Shira Ovide writes that podcasts have been a freewheeling corner of digital life, but the potential for profits is changing that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-17 20:33:00 </td>
   <td style="text-align:left;"> Ireland Inflation Rate Eases from 20-Year High </td>
   <td style="text-align:left;"> Ireland’s consumer inflation eased to 5 percent year-on-year in January of 2022 from 5.5 percent in the previous month, the first decrease in inflation since February of 2021. Prices rose at a slower pace for transportation (14.1 percent vs 18 percent in December), restaurants and hotels (2.3 percent vs 2.6 percent), and furnishings and household maintenance (2.3 percent vs 2.6 percent), while prices decreased for clothing and textiles (-3.7 percent vs 2.1 percent). On the other hand, inflation picked up for housing and utilities (12 percent vs 11.8 percent), mainly due to higher rents and mortgage rates, and food and non-alcoholic beverages (2.1 percent vs 1.6 percent), driven by breads, cereals, meats, and mineral water. On a monthly basis, consumer prices dropped by 0.4 percent, the first decrease since October of 2020, compared to the 0.5 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/nigeria/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-02-17 20:26:00 </td>
   <td style="text-align:left;"> Nigeria Economy Continues to Recover </td>
   <td style="text-align:left;"> Nigeria's GDP advanced by 3.98% yoy in the fourth quarter of 2021, the fifth consecutive quarter of economic expansion, amid the ongoing recovery from the pandemic crisis which hit hard the country's oil sector. The expansion continued to be driven by the non-oil sector (4.73%), with main positive contributions from agriculture (3.58%), trade (5.34%), information and communication (5.03%) and financial services (24.14%). On the other hand, the oil sector shrank 8.06%, reflecting lower oil output as the average daily crude oil production stood at 1.50 million barrels per day, down from 1.57 mbps in Q3 and 1.56 mbps a year ago. Despite a recovery in oil prices, Nigeria has struggled to meet its production targets due to operational challenges and insecurity coming from pipeline vandalism. On a quarterly basis, the GDP increased 9.63%, following an 11.07% jump in the third quarter. In 2021, Nigeria grew by 3.4%, the fastest expansion since 2014, better than central bank's estimate of 3%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/so:us </td>
   <td style="text-align:left;"> 2022-02-17 20:15:56 </td>
   <td style="text-align:left;"> Southern Co. earnings above expectations at 0.36 USD </td>
   <td style="text-align:left;"> Southern Co. (SO) released earnings per share at 0.36 USD, compared to market expectations of 0.35 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-17 20:04:00 </td>
   <td style="text-align:left;"> Madrid Stocks Trade Lower on Thursday </td>
   <td style="text-align:left;"> The Ibex 35 Index decreased by 0.4% to fall back below the 8,700 mark on Thursday, pressured by geopolitical tensions as fears of an imminent Russian invasion returned when US and NATO authorities said that there are signs of 7,000 additional troops making way to the Ukrainian border, despite Moscow’s denial. At the same time, investors weighed on the minutes of the Fed’s January meeting, pointing to a rate hike in March, although the magnitude is still unclear. On the corporate front, Repsol traded 0.5% lower after posting quarterly results, despite reporting a 70% annual increase in free cash flow operations, largely due to higher oil prices during the year. At the same time, the petrol company announced it plans to allocate 35% of investments until 2025 in low carbon activities, including the sale of its stake in the firm’s newly created renewable energy generation unit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2022-02-17 19:50:45 </td>
   <td style="text-align:left;"> Indian Rupee Holds at 75 </td>
   <td style="text-align:left;"> The Indian rupee remained steady at 75 per USD as traders digested the Fed meeting minutes while remained concerned over the re-escalating tensions between Russia and Ukraine. The Fed meeting minutes showed that while the Fed is prepared to hike rates soon, they would still reassess the rate hike timeline at each meeting. Meanwhile, on the domestic front, India’s producer inflation came at a 4-month low of 12.96% in January while its consumer inflation rose to a 7-month high of 6.01%, topping Central Bank’s upper target of 2-6%. However, the RBI said that such a high figure should not create any panic as it is mostly due to a base effect while maintaining the interest rate at 4% for the 10th time in a row to support economic recovery from the health crisis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2022-02-17 19:26:36 </td>
   <td style="text-align:left;"> BSE Sensex Extends Declines </td>
   <td style="text-align:left;"> The BSE Sensex ended 0.2% lower at 57,892.01 on Thursday amid concerns surrounding Russia-Ukraine geopolitical tensions while investors digested Fed meeting minutes and corporate results. The rate sensitive banks and financials led the declines as the Fed meeting minutes showed that while it would "soon be appropriate" to raise interest rates, the Fed would re-assess the rate hike timeline at each meeting. On the other hand, capital goods, particularly power and technology drove the gains. Among the individual stocks, Nestle India dragged by 0.85% after its net profit dipped 20% in the quarter ending December 2021. In addition, ICICI Bank (-2%), Ultra Cement Company (-1.9%), Axis Bank (-1.79%) and IndusInd Bank (-1.27%) were the other major draggers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60414915?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-17 19:24:56 </td>
   <td style="text-align:left;"> KitKat and Durex makers Nestle and Reckitt warn of price rises </td>
   <td style="text-align:left;"> KitKat and Nescafe-maker Nestle has warned it will increase the prices of its products due to the growing cost of producing its goods.                                                                                        , Mark Schneider, boss of the food group, said it was "safe assumption" that prices would rise this year.                                                                                                                       , He said there was "no place" in the company that was "exempt of inflation".                                                                                                                                                   , Reckitt Benckiser, the consumer goods company behind Durex and Dettol, also said prices would rise, but added it hoped to absorb most of the increases.                                                                       , Reckitt's costs rose 11% in 2021, but chief executive Laxman Narasimhan said that wouldn't mean prices rising by that amount, as the company had ways to "mitigate and manage pricing"                                        , "We care about the competitiveness of our brands," he told a conference call.                                                                                                                                                 , Jeff Carr, chief financial officer, said the firm's costs had increased "across the board", ranging from crude oil and plastic, to shipping and wages.                                                                        , But he said that company was "absorbing a significant part" of higher operating costs through "efficiency" and "better buying".                                                                                               , "We are not passing it on to consumers," he said. "We are passing some pricing onto consumers but we minimise that through the programmes we have…to absorb those cost increases."                                            , Shares rose in the company by as much as 5.4% on Thursday.                                                                                                                                                                    , Meanwhile, Nestle said it had already lifted prices by 3.1% in the fourth quarter of its financial to offset rising operating costs.                                                                                          , "It is a safe assumption that our input cost increases for 2022 will be higher than 2021, that is something that we have to reflect in our pricing," said Mr Schneider                                                        , "There is almost no place in the company that is exempt of inflation now," he added. "Some of these things you can hedge against, some not."                                                                                  , Consumer goods companies have previously warned of price rises for products due the rising costs of raw materials, energy and labour.                                                                                         , It will raise pressure on households who are facing a cost of living crisis.                                                                                                                                                  , Recent data showed that inflation hit a 30-year high of 5.5% in the year to January and the Bank of England forecasts that the cost of living could reach over 7% by spring - far above its 2% inflation target.              , Gas and electricity costs are set to rise in April when the new, higher energy price cap is introduced. At the same time companies, their staff and the self-employed will pay 1.25p more in the pound for National Insurance., Danni Hewson, financial analyst at AJ Bell, said big brand owners were facing an "important test given pressures on the cost of living".                                                                                      , "Consumers may not be able to keep stomaching price increases and so there is a risk they buy less of the popular and more expensive brands and/or trade down to cheaper options," she added.                                 , "The big brand companies therefore face the risk of having to cut their prices just to maintain sales volumes."                                                                                                               , Nestle, which also makes Cheerios and Smarties, revealed total sales increased by 3.3% to SwFr87.1bn (£69.5bn) last year.                                                                                                     , The firm's net profit grew by 38.2% to SwFr16.9bn.                                                                                                                                                                            , It said sales had been driven by strong demand for coffee, pet products and health foods during the pandemic.                                                                                                                 , Meanwhile, Reckitt said its full-year sales had increased by 3.5%, ahead of expectations, on demand for hygiene and health products.                                                                                          , Splitting its divisions, hygiene performed best with sales up 1.6% in the year to £5.9 billion, including strong sales of Air Wick, Lysol, Finish and Vanish.                                                                 , Sales of Durex condoms, KY lubricants and Veet hair removal products were boosted as lockdowns were lifted.                                                                                                                   , The firm added sales of US cleaning and disinfecting spray Lysol were about 90% higher than 2019.                                                                                                                             , It said it expected its health business to benefit from stronger cold and flu treatment sales.                                                                                                                                , Last week, Unilever, the firm behind brands such as Marmite and Dove Soap, said it would put up its prices again this year as its overheads continue to rise.                                                                 , The company, which also makes Ben &amp; Jerry's ice cream and Hellmann's mayonnaise, said it was facing €3.5bn (£2.95bn) of extra costs in 2022 alone.                                                                            , A fresh perspective on how Hitler brutally seized and kept power                                                                                                                                                              , Get ready for the final series with this sneak peek                                                                                                                                                                           , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/currency </td>
   <td style="text-align:left;"> 2022-02-17 19:19:00 </td>
   <td style="text-align:left;"> Turkish Lira Steady Following Unchanged Interest Rate </td>
   <td style="text-align:left;"> The Turkish Lira was little changed at 13.6 per USD after the Central Bank of Turkey held its key borrowing costs steady for the second time since September, while reviewing its policy framework to encourage more lira usage. The central bank had slashed its benchmark rate by 500bps in between September and December to support exports and growth, pressured by President Tayyip Erdogan pledges, despite a plunging lira and surging inflation. The latest data showed that consumer inflation hit a 19-year high of 46.68% in January, the highest under President Erdogan's rule and well above the bank's target of 5%, while inflation expectations for the end of the year jumped to 34.1% from 29.8%, according to the TCMB’s February survey of market participants. In the meantime, the Ministry of Finance announced that TRY 200 billion have been deposited in accounts under the government’s scheme that protects lira deposits from the currency’s volatility. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/building-permits </td>
   <td style="text-align:left;"> 2022-02-17 19:12:00 </td>
   <td style="text-align:left;"> South Africa Building Permits Rise Faster in December </td>
   <td style="text-align:left;"> The value of recorded building plans passed in South Africa larger municipalities surged 24.8% from a year ago to ZAR 8.3 million in December of 2021, after a revised 3.6% increase in the prior month. Building plans increased for all segments: residential building (26.4%), non-residential building (51.2%), and additions &amp; alterations (9.2%). Considering the full year of 2021, building plans jumped 41.2% to ZAR 107 billion, mainly due to low-base effects. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/portugal/producer-prices-change </td>
   <td style="text-align:left;"> 2022-02-17 19:11:33 </td>
   <td style="text-align:left;"> Portugal Producer Inflation at 3-Month Low </td>
   <td style="text-align:left;"> Annual producer inflation in Portugal eased to 17.9% in January of 2022 from 20% in December which was the highest on record since at least 1991. Energy prices continued to soar at double-digit rates (46.5% vs 64.5% in the previous month) and inflation accelerated for intermediate goods (18.9% vs 18.2%) and both durable (4.1% vs 2.9%) and nondurable goods (6.5% vs 5.3%). On the other hand, prices increased 3% for capital goods, the same as in December. On a monthly basis, producer prices edged up 0.3%, the smallest monthly increase since February 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/interest-rate </td>
   <td style="text-align:left;"> 2022-02-17 19:09:00 </td>
   <td style="text-align:left;"> Turkey Holds Interest Rate at 14% </td>
   <td style="text-align:left;"> The Central Bank of Turkey left the key one-week repo rate steady at 14% as expected during its February meeting of 2022 citing rising geopolitical risks and arguing again that the recent surge in prices is not supported by economic fundamentals. The bank said it expects the disinflation process to start on the back of taken measures and fading base effects. The Committee reinforced it will continue to use all available instruments decisively within the framework of liraization strategy until strong indicators point to a permanent fall in inflation and the medium-term 5 percent target is achieved in pursuit of the primary objective of price stability. Since September last year, the bank cut the rates by 500bps, pushing the lira down 44% last year and inflation to near 50% in January. Inflation is expected to peak in April or May at around the 50-55% level due to energy price hikes and salary increases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-02-17 18:41:03 </td>
   <td style="text-align:left;"> Euro Eases Slightly </td>
   <td style="text-align:left;"> The Euro edged down slightly to below $1.137, as investors moved again to safe-haven assets on renewed tensions between Russia and the West over Ukraine. Meanwhile, the latest Fed minutes pointed to increases in the fed funds rate in March although doubts, whether it will be a 25bps or  a 50bps hike remained. In Europe, ECB President Christine Lagarde reinforced that any change in the bank's policy will be gradual. Money markets see a 10bps rate hike at the June meeting and anticipate about 50bps in increases by year-end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60403548?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-17 18:40:56 </td>
   <td style="text-align:left;"> Apple boss Tim Cook faces backlash to £73m pay package </td>
   <td style="text-align:left;"> Investors are being urged to vote against a $99m (£73m) pay package awarded to Apple boss Tim Cook last year.                                                                                                                                              , Institutional Shareholder Services (ISS) said it has "significant concerns" over the size of the award, up from $14.8m the year before.                                                                                                                    , Mr Cook, whose net worth is reportedly more than £1bn, received the pay in shares, salary, and for other costs.                                                                                                                                            , The BBC has contacted Apple for comment.                                                                                                                                                                                                                   , In a letter to shareholders, the ISS said there are "significant concerns" over the "design and magnitude" of the package. "Half of the award lacks performance criteria," ISS said.                                                                       , Mr Cook, 61, who has often spoken publicly about his concerns over equality and human rights issues, said in 2015 that he would give away his entire fortune before he dies.                                                                               , According to ISS, Mr Cook's pay was 1,447 times more than the wage of an average Apple employee.                                                                                                                                                           , His package included $630,600 in personal security costs and $712,500 for personal use of a private jet. ISS said the cost of such perks "significantly exceeded" comparable companies last year.                                                          , Last year, a US Securities and Exchange Commission (SEC) filing showed that Mr Cook donated almost £7.4m worth of Apple shares to charity, without naming the recipient.                                                                                   , The company behind the iPhone, iPad and MacBook became the first company to hit a $3tn (£2.2tn) stock market value in January before dipping to its current value of $2.8tn (£2.1tn).                                                                      , Shareholder returns are now more than 1,000% since Mr Cook took over in 2011.                                                                                                                                                                              , Apple is due to hold its annual meeting for shareholders in the first week of March. However, shareholder votes are only advisory, while Apple's board decide on pay packages.                                                                             , At last year's meeting, 95% of shareholder votes supported Apple's executive compensation programme.                                                                                                                                                       , Companies in the US, and UK, are facing stronger shareholder opposition over pay and compensation.                                                                                                                                                         , General Electric, IBM and Starbucks failed to win a majority of shareholder backing for executive pay in 2021. US oil firms ExxonMobil and Chevron also saw shareholder revolts from climate activists last year.                                          , Asset manager Blackrock, Exxon's second largest shareholder, doubled its votes against executive pay proposals in the Americas in early 2021, compared to 2020.                                                                                            , In the UK, more than twice as many FTSE 100 companies faced shareholder revolts than in 2020, condemning executive pay-outs when many employees faced added financial hardships in the pandemic.                                                           , President Joe Biden and congressional Democrats have called for higher taxes on the billionaires and big business to help pay for a major social spending package. The proposal would raise about $16bn by limiting deductions for executive compensation. , The tax hike plan would pay for federally funded paid family leave, expanded education budgets and climate change problems.                                                                                                                                , A fresh perspective on how Hitler brutally seized and kept power                                                                                                                                                                                           , Get ready for the final series with this sneak peek                                                                                                                                                                                                        , Zara McDermott investigates the impact of revenge porn                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-17 18:31:00 </td>
   <td style="text-align:left;"> WTI Crude Extends Losses to Below $91.5 </td>
   <td style="text-align:left;"> WTI crude futures fell more than 2% to below $91.5 per barrel on Thursday, as investors weigh prospects of new crude supplies from Iran against renewed geopolitical tensions in Ukraine that raised concerns of supply disruptions in major oil producer Russia. Iran is close to accepting a deal on its nuclear programme, which could mean the release of about 1.3 million barrels a day of crude supply, helping to ease a tight global market. Meanwhile, tensions between Russia and the West over Ukraine could escalate after Russian-backed rebels accused Ukrainian forces of shelling their territory. On Wednesday, NATO accused Russia of increasing troops at the Ukrainian border, while Moscow claimed it had begun withdrawing some of its military units. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-02-17 18:27:00 </td>
   <td style="text-align:left;"> Oil Falls by Over 2% </td>
   <td style="text-align:left;"> Brent crude futures fell more than 2% to below $93 per barrel on Thursday, as investors weigh prospects of new crude supplies from Iran against renewed geopolitical tensions in Ukraine that raised concerns of supply disruptions in major oil producer Russia. Iran is close to accepting a deal on its nuclear programme, which could mean the release of about 1.3 million barrels a day of crude supply, helping to ease a tight global market. Meanwhile, tensions between Russia and the West over Ukraine could escalate after Russian-backed rebels accused Ukrainian forces of shelling their territory. On Wednesday, NATO accused Russia of increasing troops at the Ukrainian border, while Moscow claimed it had begun withdrawing some of its military units. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-02-17 18:21:00 </td>
   <td style="text-align:left;"> UK Natural Gas Bounces Off 5-Month Low </td>
   <td style="text-align:left;"> UK natural gas prices rose more than 6% to around 180 pence per therm, rebounding sharply from a five-month low of 156 pence per therm hit in the prior session. NATO said it had not seen Russia pulling back troops from Ukraine's borders, while Russian news reported mortars fired in eastern Ukraine. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-18 09:50:45 UTC +8

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
   <td style="text-align:left;"> 2022-02-18 09:50:24 </td>
   <td style="text-align:left;"> $SPY 460 is coming soon. All companies are doing great. Apple is pumping hard 

Futures are ripping. Bullish candles 😂😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:23 </td>
   <td style="text-align:left;"> $SPY dropping already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:18 </td>
   <td style="text-align:left;"> $SPY we need one more green candle tonight to confirm green push all day tomorrow .. so far one big green candle not enough .. come on !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:16 </td>
   <td style="text-align:left;"> $SPY 447 give us another double sloppy toppy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:13 </td>
   <td style="text-align:left;"> $SPY Bears are big mad right now.. 

Poots go 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:10 </td>
   <td style="text-align:left;"> $spy futures ripping.  war is over. 
lol
bulls gonna run cause they can 
kamala stopped the war with one look </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:09 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:05 </td>
   <td style="text-align:left;"> $SPY I grew up poor, getting rich now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:04 </td>
   <td style="text-align:left;"> $SPY Endless grind up all night now

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:02 </td>
   <td style="text-align:left;"> $SPY 

A “F*ck you!” green candle to regain a support level?! Mmhm

———- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:50:00 </td>
   <td style="text-align:left;"> $SPY the delusion is real

Is Secretary of State gonna fix inflation and interest rates by talking to Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:59 </td>
   <td style="text-align:left;"> $SPY J Powell working late tonight trying to pamp it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:52 </td>
   <td style="text-align:left;"> $QQQ $SPY If Putin fucks all you bulls overnight… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:41 </td>
   <td style="text-align:left;"> $SPY So... no news? just a random pump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:41 </td>
   <td style="text-align:left;"> $SPY Yay no war for a week! Sure that will stop inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:40 </td>
   <td style="text-align:left;"> $SPY 444 to 447 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:36 </td>
   <td style="text-align:left;"> $SPY just another opportunity for pajama traders to short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:32 </td>
   <td style="text-align:left;"> $SPY the only thing thats left to price in is literally a meteor crashing into earth and taking it out of the sun&amp;#39;s orbit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:32 </td>
   <td style="text-align:left;"> $SPY Russia has nothing to do with us. The mm sold off today from the fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:30 </td>
   <td style="text-align:left;"> $SPY 

Fading already… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:28 </td>
   <td style="text-align:left;"> $SPY “IT’S RIGGED” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:25 </td>
   <td style="text-align:left;"> $SPY futures grass green? war cancelled? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:15 </td>
   <td style="text-align:left;"> $SPY 460 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:14 </td>
   <td style="text-align:left;"> $SPY 2% rally minimum. I might have loaded $50k in calls that expire tomorrow lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:11 </td>
   <td style="text-align:left;"> $SPY it would have to drop like 10 pts for me to think bears have a chance tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:09 </td>
   <td style="text-align:left;"> $SPY So many bulls 🥰😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:03 </td>
   <td style="text-align:left;"> $SPY let’s open at 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:03 </td>
   <td style="text-align:left;"> $SPY Whoa. 👀 
Big move coming. 
Hold on to your butts!!
Futures bouncing and bright green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:49:02 </td>
   <td style="text-align:left;"> $SPY $UVXY By EU open the only red, will be VIX and RTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:58 </td>
   <td style="text-align:left;"> $SPY 💥🤣🤣🤣 448 tomorrow. Easy peasy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:55 </td>
   <td style="text-align:left;"> $SPY its already coming back down. Bears still in play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:52 </td>
   <td style="text-align:left;"> $SPY bears shut their traps real quick. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:52 </td>
   <td style="text-align:left;"> $SPY 
Well, bought my first couple bac on the news…I’m sure they’ll start the war in 20mins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:51 </td>
   <td style="text-align:left;"> $SPY the news ain’t enough to turn market bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:49 </td>
   <td style="text-align:left;"> $SPY nope .. they will have to pump all major global indexes with the most companies within. It won&amp;#39;t happen.. APPL and Google can&amp;#39;t be alone pumped anymore it becomes too obvious and not politically correct. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:48 </td>
   <td style="text-align:left;"> $SPY Houston Rockets or Clippers? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:47 </td>
   <td style="text-align:left;"> $SPY goodnight guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:37 </td>
   <td style="text-align:left;"> $SPY what’s the news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:30 </td>
   <td style="text-align:left;"> $SPY Can we get some transparency regarding foreign investment activity in our markets? There must be Russian oligarchs colluding with Putin and just switching between calls and puts every day. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:29 </td>
   <td style="text-align:left;"> $SPY correction to 340 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:26 </td>
   <td style="text-align:left;"> $SPY 4444 test all night. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:20 </td>
   <td style="text-align:left;"> $SPY Biden shouldn’t have been allowed to say things like “war is imminent” if they haven’t even had a face to face talk…

Classless and frankly ridiculous office in America right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:18 </td>
   <td style="text-align:left;"> $SPY 

Russia says Russian troops will return to their home bases after completion of joint exercises this Sunday with Belarus, Russian Ministry of Defense says tonight. 

Tomorrow will be a big day in Ukraine/Russia news

Lukashenko to meet with Putin in Moscow
 
Munich conference 

high number of ceasefire violations today

Russian troops and equipment are still arriving at the border despite what the kremlin says </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:06 </td>
   <td style="text-align:left;"> $SPY well I was pretty mean to the bulls yesterday - gotta be mean to the bears now. fck your puts lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:04 </td>
   <td style="text-align:left;"> $SPY Im hungry.. where is moo?
Markets are in turmoil tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:48:03 </td>
   <td style="text-align:left;"> $SPY BEARS ARE DONE. NO WAR. WE ARE TALKING TO RUSSIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:59 </td>
   <td style="text-align:left;"> $SPY market manipulation. I’ve been doing calls and outs for weeks now boom! Big money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:55 </td>
   <td style="text-align:left;"> $SPY FUTES RIPPIN&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:53 </td>
   <td style="text-align:left;"> $SPY $QQQ Putin must be making some money from the stock market lately lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:49 </td>
   <td style="text-align:left;"> $SPY Holy puking sh*t that is a nasty nasty green candle...it&amp;#39;s beautiful in a sick way... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:49 </td>
   <td style="text-align:left;"> $SPY entire market is a penny stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:48 </td>
   <td style="text-align:left;"> $SPY y’all trusting Futes rn? 
They said they’d have a conversation next week lol. How many ceasefires will happen by then? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:46 </td>
   <td style="text-align:left;"> $SPY I’m convinced Russia was only going to invade if they didn’t get the gold medal in woman’s figure skating 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:45 </td>
   <td style="text-align:left;"> $SPY FUTES LMFAO!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:45 </td>
   <td style="text-align:left;"> $SPY bulls be like  
&amp;quot;LiMiT uP. beArS are Fukt. Lollll.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:42 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s the most over sold market market in 20 years and that&amp;#39;s a fact </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:41 </td>
   <td style="text-align:left;"> $SPY  here we go good news bad news. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:40 </td>
   <td style="text-align:left;"> $SPY I’m beyond bullish but it shows you how manipulated market is! Let’s go bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:37 </td>
   <td style="text-align:left;"> $SPY When you can afford to be wrong, you are doing it right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:32 </td>
   <td style="text-align:left;"> $SPY random moon after shitting all day 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:26 </td>
   <td style="text-align:left;"> $SPY y’all do realize that last last time we went from $440 to $420 we had a pop at 8pm and bled down from there right 😂 Go back and look at the 24th if you want to fact check. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:24 </td>
   <td style="text-align:left;"> $TSLA $SPY whats the news? ‘Futes rippin’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:21 </td>
   <td style="text-align:left;"> $SPY Can&amp;#39;t trust this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:20 </td>
   <td style="text-align:left;"> $SPY $DJIA $UVXY 

Unpopular opinion: The Russia Ukraine tension play is being smartly utilized by the Fed/Biden. Think about it, just on threats of imminent attack and threats of imminent rate hikes, we are able to get the market to correct itself. 

We don&amp;#39;t know when but the rebound will be, that depends on how &amp;quot;heavy&amp;quot; the equity market is but surely, the recovery will be absolutely beautiful. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:16 </td>
   <td style="text-align:left;"> $SPY $BTC.X $SKLZ we gotta start taking in Canadian refugees but keep away their celebrities. So many Canadians made in show biz pretending to be Americans it’s ridiculous same goes for biz like mr wonderful and such . Take in the refugees from that commie regime to our less a little commie regime but start putting a warning label on movies and such like that dude is actually a Canadian that learned that New Jersey accent by mistake 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:13 </td>
   <td style="text-align:left;"> $SPY limit up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:07 </td>
   <td style="text-align:left;"> $SPY Why would they wait a week?  Like, dafuq else those rwo have to do?  Weird. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:07 </td>
   <td style="text-align:left;"> $SPY wtf futes just pumped in 1 minute? I checked 5 minutes ago and they were red, now they are big green wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:04 </td>
   <td style="text-align:left;"> $SPY futures ripping - should be a great sign for bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:04 </td>
   <td style="text-align:left;"> $SPY Put holders waking up to a $439 gap up is going to call this market manipulated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:02 </td>
   <td style="text-align:left;"> $SPY Uhh why is futes popping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:47:01 </td>
   <td style="text-align:left;"> $SPY Futes are ripping Johnny!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:55 </td>
   <td style="text-align:left;"> $SPY atleast the march 2020 drop was 1 day. This market has been getting decimated since feb 2021. It&amp;#39;s priced in for like 10 hikes, 10 year at 5% and World War 3 now... Growth and small caps at 20 year lows on multiples. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:52 </td>
   <td style="text-align:left;"> $SPY Not bearish or in a position right now but these seems odd. Don’t trust it or get excited. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:51 </td>
   <td style="text-align:left;"> $SPY $UVXY Powell jedi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:48 </td>
   <td style="text-align:left;"> Now that retail loaded up on puts and bought $UVXY at a 20% premium get ready for a mega rally tomorrow! It&amp;#39;s coming and the futures knows it!

$SPY $QQQ $DJIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:43 </td>
   <td style="text-align:left;"> $SPY futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:39 </td>
   <td style="text-align:left;"> $SPY no war for a week with this meeting on the books! RIPPPPPP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:37 </td>
   <td style="text-align:left;"> $SPY just give the 2%back tomorrow.  I promise I will be out of the market lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:34 </td>
   <td style="text-align:left;"> $SPY 

Not really ripping… it would have been up 1+% by now… hmm.

Perhaps Russian worry was only half the problems. The other, of course, is the Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:29 </td>
   <td style="text-align:left;"> $SPY dummies cheerleading a 0.4% move up.   It’s called a bear flag morons </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:21 </td>
   <td style="text-align:left;"> $SPY cool ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:20 </td>
   <td style="text-align:left;"> latexbd271a82425434608f94cf72f7d83cdbKOLD 
$XOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:20 </td>
   <td style="text-align:left;"> $SPY Tomorrow could get crazy 

https://stocktwits.com/erice579/message/437372851 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:12 </td>
   <td style="text-align:left;"> $SPY 💥🤣🤣 Ruh Roh - Futes ripping. For now. Gotcha bitch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:11 </td>
   <td style="text-align:left;"> $SPY I refuse to believe Russia an Ukraine news have this much of an effect on the US stock market. . I&amp;#39;ll take it though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:46:04 </td>
   <td style="text-align:left;"> $SPY 
Yeah cause you can definitely trust the Russians </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:59 </td>
   <td style="text-align:left;"> $SPY swinging calls overnight but don’t think this pump will hold overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:53 </td>
   <td style="text-align:left;"> $SPY I’m Johnny Knoxville and I’m buying more 0dte 4400 puts here. 
 
I always think positive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:46 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s times like these I&amp;#39;m glad I don&amp;#39;t buy and hold puts/calls overnight. Satisfying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:46 </td>
   <td style="text-align:left;"> $SPY cash is and will always be

trash!

gov has been devaluing ur money for a century and bears think people don&amp;#39;t prefer assets 😭😭😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:36 </td>
   <td style="text-align:left;"> $SPY only 45% stocks above 200ma #study  https://www.tradingview.com/chart/S5TH/SkQHC5m5-S-P-500-just-45-of-stocks-above-their-200D-MA/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:35 </td>
   <td style="text-align:left;"> $SPY this is a bit much over a conversation that won’t solve anything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:32 </td>
   <td style="text-align:left;"> $SPY anyone actually have an article?

Can’t find shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:31 </td>
   <td style="text-align:left;"> $SPY bulls thought the sell off was about war lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:23 </td>
   <td style="text-align:left;"> $SPY let the record show that the bears already kinda won no matter what happens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:22 </td>
   <td style="text-align:left;"> $SPY Oh, oh, the two sides who are both entrenched with their clearly stated and massively divergent objectives are going to meet a week from now, and what the fuck do you think is gonna happen? 😆  
 
I seriously would not be surprised if this still further escalated long before any alleged talks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:45:07 </td>
   <td style="text-align:left;"> $SPY Honestly we probably should&amp;#39;ve figured they would try to resume talks or something </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:59 </td>
   <td style="text-align:left;"> $SPY &amp;quot;bears will get raped tomorrow&amp;quot;. 

I bet you tomorrow doesn&amp;#39;t reverse today&amp;#39;s loss. 

You wanna bet me? Sell me some $SPXS calls. 

Watch yo ass go broke. 

420 incoming. 

I already predicted tomorrow up to 443 to burn puts. Calls already burnt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:58 </td>
   <td style="text-align:left;"> $SPY link to news anyone por favor? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:57 </td>
   <td style="text-align:left;"> $SPY Russia wants to talk next week lmao after they invade lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:55 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures surging all of the sudden, did we get the Russian withdrawing their troops or something lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:55 </td>
   <td style="text-align:left;"> $SPY that candle will attract sellers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:51 </td>
   <td style="text-align:left;"> $SPY LMAOOO NO WAR US TALKS TO RUSSIA IN A WEEK LOL THEY AINT DOING SHIT LFG FUCK JOE BIDEN $460 BY LUNCH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:50 </td>
   <td style="text-align:left;"> $SPY why are futures up now. Any news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:49 </td>
   <td style="text-align:left;"> $SPY Putin Playing Futures lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:44 </td>
   <td style="text-align:left;"> $SPY Ukraine to fed.... Fed to Ukraine.... Ukrain to fed.  Yikes y&amp;#39;all be careful bearish is smart but when your up x percent. They&amp;#39;ll fuckin not pay everyone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:38 </td>
   <td style="text-align:left;"> U.S. SECRETARY OF STATE BLINKEN HAS ACCEPTED INVITATION TO MEET RUSSIA&amp;#39;S LAVROV LATE NEXT WEEK -STATE DEPARTMENT SPOKESMAN 
 
sorry but not sorry bears 😂 
 
$spy $qqq $sofi $tsla $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:34 </td>
   <td style="text-align:left;"> $SPY lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:31 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE  🔥 
🎯LOTTO FRIDAY PICK LIST 
IM GOING TO BREAK DOWN 👇 
📈TRADE IDEAS  
🔫TRIGGERS  
🎯TARGETS  
CLICK 👉 https://us02web.zoom.us/j/85366560330  $SPY  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:31 </td>
   <td style="text-align:left;"> $SPY Russia invades when Olympics is over. He can’t make his Chinese daddy mad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:27 </td>
   <td style="text-align:left;"> $SPY Putin bought calls right before close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:22 </td>
   <td style="text-align:left;"> $SPY will be $430 by the morning… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:21 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:21 </td>
   <td style="text-align:left;"> $QQQ $SPY If Lavrov and Blinken meeting end of next week, little chance of invasion happening over the long weekend.  Applying game theory, Putin gets max benefit pushing to the brink of war, but not actually invading.  Just the tip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:15 </td>
   <td style="text-align:left;"> $SPY big bazooka candles everywhere someone cured cancer 
Oh well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:13 </td>
   <td style="text-align:left;"> $SPY U.S. ACCEPTS TALKS WITH RUSSIA&amp;#39;S LAVROV NEXT WEEK - FX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:10 </td>
   <td style="text-align:left;"> $SPY 
And we back in the game homies, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:10 </td>
   <td style="text-align:left;"> $SPY mother of all short squeezes tmrw . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:09 </td>
   <td style="text-align:left;"> $SPY I bought calls into close 2.2 trillion in puts sheeeeesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:02 </td>
   <td style="text-align:left;"> $SPY  little pump 15 minutes ago, most likely from this and not about war ? https://www.msn.com/en-us/news/politics/senate-sends-biden-bill-averting-federal-government-shutdown-on-friday/ar-AAU0yvs?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:44:00 </td>
   <td style="text-align:left;"> $SPY great news!!!ground hog day is over!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:55 </td>
   <td style="text-align:left;"> $SPY yesss…go higher..rest that RSI for Fridays sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:55 </td>
   <td style="text-align:left;"> $SPY I was waiting for this to go to the strip club

Bears like
“We’re stuck in a trap
I can’t walk out 
Because I love puts too much baby” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:52 </td>
   <td style="text-align:left;"> $SPY even if u are a bull why would u hold over the weekend with Russian invasion looming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:52 </td>
   <td style="text-align:left;"> $SPY calls for next week ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:51 </td>
   <td style="text-align:left;"> $SPY HOT. WATCHING: USAF C-130 Commando Solo II. Clandestine PSYOPS missions. Wondering if it stays in the region or heads north. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:45 </td>
   <td style="text-align:left;"> $SPY dow lost over 600 today and bulls cheering because futes are up a little 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:37 </td>
   <td style="text-align:left;"> $SPY BOOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:37 </td>
   <td style="text-align:left;"> $SPY get in the trenches bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:35 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:34 </td>
   <td style="text-align:left;"> $SPY bulls down almost ten bucks on the day and think a schedule meeting means limit up in am . What fools </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:32 </td>
   <td style="text-align:left;"> $SPY bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:31 </td>
   <td style="text-align:left;"> $SPY bulls still talking about war lol. We know the real issue is the economy and the fed😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:16 </td>
   <td style="text-align:left;"> $SPY omg. This market is fixed if Russia just said that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:43:04 </td>
   <td style="text-align:left;"> latex5c23d25baf34a5046d1295d3752868baPYPL Bears will get F**k bigly tomorrow 💕💕 gals I loaded up 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:58 </td>
   <td style="text-align:left;"> $SPY bear rape tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:57 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:52 </td>
   <td style="text-align:left;"> $SPY 
Nobody holding anything over a 3 day weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:47 </td>
   <td style="text-align:left;"> $SPY Clippers or Rockets? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:45 </td>
   <td style="text-align:left;"> $SPY Never buy puts on this chumps as anything other than a hedge. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:43 </td>
   <td style="text-align:left;"> $SPY 

Who BTD today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:39 </td>
   <td style="text-align:left;"> $SPY yeah accepts talk after the shell the shit out of Ukraine. Whatever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:34 </td>
   <td style="text-align:left;"> $SPY war cancelled 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:33 </td>
   <td style="text-align:left;"> $SPY Just a falling wedge. I missed this. What a pretty setup. Sheesh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:32 </td>
   <td style="text-align:left;"> $SPY future are ripping and breaking every resistance..... DUMP UR LIFE SAVING IN, YOUR KIDS COLLEGE FUND, GO BULLS  
(please only use what you can afford to lose, if you need help there are gambling addicting helpline on google) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:31 </td>
   <td style="text-align:left;"> $QQQ $SPY Riot on Wall Street? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:29 </td>
   <td style="text-align:left;"> $SPY I was with the bears today...but futes are actually rippin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:23 </td>
   <td style="text-align:left;"> $SPY  why are the algos going nuts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:18 </td>
   <td style="text-align:left;"> $SPY wtf just happened? i just went to go pee... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:17 </td>
   <td style="text-align:left;"> $SPY ripping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:16 </td>
   <td style="text-align:left;"> $SPY Nice Gap up on that news!! Let’s see if we can have some fun tomorrow shorting the pops lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:15 </td>
   <td style="text-align:left;"> Markets just reacting to any kind of headlines while main focus should be on rates and balance sheet deduction $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:14 </td>
   <td style="text-align:left;"> $SPY I’ll be honest, if you didn’t close out your puts then you deserve this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:14 </td>
   <td style="text-align:left;"> $SPY Call buying time isn’t here. Be prepared to lose those lotto calls. Trade the chart and profit. Hope and a prayer isn’t DD. Study and get paid.😉🥃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:10 </td>
   <td style="text-align:left;"> $SPY absolute fuckery how Biden goes from “war is imminent” to “nah it’s cool me and Putin gonna hash things out next week”

Fucking crazy old man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:09 </td>
   <td style="text-align:left;"> $SPY anyone know what the pop in futures is for? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:03 </td>
   <td style="text-align:left;"> $SPY thatta girl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:42:00 </td>
   <td style="text-align:left;"> $SPY what a pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:58 </td>
   <td style="text-align:left;"> $SPY phase 1 looks good! Buy buy buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:49 </td>
   <td style="text-align:left;"> $SPY bears just took a shat on themselves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:46 </td>
   <td style="text-align:left;"> $SPY futures flat telling me a direction won’t be found until this Ukraine thing reaches a definitive action, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:41 </td>
   <td style="text-align:left;"> $SPY 448 calls for tomorrow were mere pennies, I picked up a few </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:41 </td>
   <td style="text-align:left;"> $SPY Lol this market is an absolute joke $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:35 </td>
   <td style="text-align:left;"> $SPY bears just what themself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:26 </td>
   <td style="text-align:left;"> $SPY Never ever ever listen to the losers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:19 </td>
   <td style="text-align:left;"> $SPY wow typical. Never a gap down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:14 </td>
   <td style="text-align:left;"> $QQQ $SPY there needs to be some type of regulation this has literally flip flopped everyday overnight this week. Can’t overnight swing at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:09 </td>
   <td style="text-align:left;"> $SPY hope you not swinging puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:41:05 </td>
   <td style="text-align:left;"> $SPY UP DOWN UP DOWN UP DOWN UP DOWN UP DOWN BULLISH BEARISH BULLISH BEARISH BULLISH BEARISH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:57 </td>
   <td style="text-align:left;"> $SPY Lol bears waking up to a gap up to $439 tomorrow will say this is manipulated and fake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:48 </td>
   <td style="text-align:left;"> $SPY this is why I don’t play options as u can see it’s a shitshow for both sides </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:43 </td>
   <td style="text-align:left;"> $SPY whoa what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:41 </td>
   <td style="text-align:left;"> $SPY there was way too many puts bought today to have red market tomorrow.. 
448 tomorrow . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:41 </td>
   <td style="text-align:left;"> $SPY 🇷🇺  💥 watch them do some shit overnight. Putin collaborating with hedge funds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:38 </td>
   <td style="text-align:left;"> $SPY climb the wall of worry u little dyk3z, $450 Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:37 </td>
   <td style="text-align:left;"> $SPY im so ready to be a bull this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:32 </td>
   <td style="text-align:left;"> $SPY Cathie Wood is a typical bull cheerleader..Every rip will be sold from now on until new fiscal stimulus. I don&amp;#39;t think it will ever happen again due to the inflation highest in the last 40 years.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:32 </td>
   <td style="text-align:left;"> $SPY Russia withdraws for 70th time!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:26 </td>
   <td style="text-align:left;"> $SPY oh my god I hope we RAGE higher tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:25 </td>
   <td style="text-align:left;"> $SPY that time they claimed WW3 was inevitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:25 </td>
   <td style="text-align:left;"> $SPY whats the vix drop for?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:20 </td>
   <td style="text-align:left;"> $SPY HOL UP HOL UP HOLI UP 
WE DEM BOYZ. 
All bulls unite at my favorite place. U should know by now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:19 </td>
   <td style="text-align:left;"> U.S. ACCEPTS TALKS WITH RUSSIA&amp;#39;S LAVROV NEXT WEEK 
 
Sorry bears 🐻 ; many big puts will burn tomorrow 😁 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:08 </td>
   <td style="text-align:left;"> $SPY 

If Biden kept his fucking mouth shut, we would have held $440… idiot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:03 </td>
   <td style="text-align:left;"> $SPY lol Russia and us have been talking for over a month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:03 </td>
   <td style="text-align:left;"> $SPY futes headed down. They’re still flat but just wait. Gonna get hit hard still IMO. Daily chart is in a gross h&amp;amp;s prob will bounce around 427-430 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:40:02 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:50 </td>
   <td style="text-align:left;"> $SPY Putin and his cronies are not going to be influenced by anything Blinken says….They have no respect for any American diplomat…they are gangsters and act accordingly…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:49 </td>
   <td style="text-align:left;"> $SPY it’s a prank , relax </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:47 </td>
   <td style="text-align:left;"> $SPY PUT HOLDERS COMMITTING SUICIDE TONIGHT FOR BEING GREEDY ILL ADMIT I WANTED TO KEEP HOLDING MY PUTS TOO 🚨🚨🚨🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:46 </td>
   <td style="text-align:left;"> $SPY latexa42f8c6f472d82bcd5e7d7b92affbe78BA Bear 🪤😂
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:37 </td>
   <td style="text-align:left;"> $SPY LOCK HER UP,LOCK HER UP

https://hannity.com/media-room/watch-new-trump-ad-justice-is-coming-for-hillary/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:36 </td>
   <td style="text-align:left;"> $SPY looks like a gap up tomorrow.  Fed must be continuing QE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:32 </td>
   <td style="text-align:left;"> $SPY no ones going to want to hold  through the 3 day weekend with Russia poised to invade at any time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:26 </td>
   <td style="text-align:left;"> $SPY they literally had a conversation today and released the news in cahoots after 8 pm lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:25 </td>
   <td style="text-align:left;"> $SPY  
 
SPY Choppy day in the markets. Pretty much everything was red today, except for a few runners.  Depends on your time horizon, but I see this as a long-term hold. So just remember to keep that in perspective. 
  
Investing is hard, but it shouldn’t be. We built this platform to provide personalized and actionable investment ideas and insights through artificial intelligence and a community of investors. Join the future of intelligent investing. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_202202017 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:24 </td>
   <td style="text-align:left;"> $SPY HAHAHAHAHAHAHA BEARS

HAHAHAHAHAHHAHAHAHAHAHAH

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:18 </td>
   <td style="text-align:left;"> $SPY futures might not hold. Looks like trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:14 </td>
   <td style="text-align:left;"> $SPY Futures criminal as *****🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:13 </td>
   <td style="text-align:left;"> $SPY i got 1st degree theta burns regardless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:09 </td>
   <td style="text-align:left;"> $SPY THIS IS WHY I BOUGHT CALLS ON TECH TOWARDS CLOSING JUST LIKE HOW I BOUGHT PUTS TOWARDS CLOSING YESTERDAY LFG BABY LFG BABY 🚨🚨🚨🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:06 </td>
   <td style="text-align:left;"> $SPY everyone is excited but hate to tell you it is just doing this to kill puts on a Friday and will sell off the end of the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:39:06 </td>
   <td style="text-align:left;"> $SPY shorts go from look out for 430 tommarow to ceiling for tommarow is 444 hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:53 </td>
   <td style="text-align:left;"> $SPY freaky </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:49 </td>
   <td style="text-align:left;"> $SPY lol does anyone have answers as to why? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:47 </td>
   <td style="text-align:left;"> $SPY putin said he likes his new puppy dog biden!! We have been saved!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:40 </td>
   <td style="text-align:left;"> $SPY who wants war anyways? except miserable broke bears with no assets and a few puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:39 </td>
   <td style="text-align:left;"> latexf5e50fa443fbae1d12da26cdec334a64FB/$PYPL damn what happens futures are spiking Big did Russia withdraw? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:38 </td>
   <td style="text-align:left;"> $SPY +2% get it right back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:34 </td>
   <td style="text-align:left;"> $SPY 

While full-scale invasion remains possible, Russia could also hit Ukraine with paralyzing cyberattacks, hobble its economy or even poison the Ukrainian president, Hill said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:33 </td>
   <td style="text-align:left;"> $SPY ceiling for tomorrow is 444. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:31 </td>
   <td style="text-align:left;"> $QQQ $SPY markets may be saved for tomorrow.  This is hilarious.  Putin must be trading futures.  https://twitter.com/livesquawk/status/1494484516169306114?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:25 </td>
   <td style="text-align:left;"> $SPY 
LMAO

This current market absolutely favors day trading strategy. Don’t hold any position overnight!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:23 </td>
   <td style="text-align:left;"> News $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:15 </td>
   <td style="text-align:left;"> $SPY yeah I guess it was unlikely to just keep dropping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:14 </td>
   <td style="text-align:left;"> $SPY 3% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:09 </td>
   <td style="text-align:left;"> Futures moving up on news $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:07 </td>
   <td style="text-align:left;"> #lottofriday tomorrow and looking forward to it. Can expect some range. Either $SPY and $QQQ confirm the bear flag and we puke Tech or we h </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:06 </td>
   <td style="text-align:left;"> $SPY Futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:38:06 </td>
   <td style="text-align:left;"> $SPY Blinkin agrees to meet with Russia&amp;#39;s Lavrov next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:59 </td>
   <td style="text-align:left;"> $SPY haha bulls tonight think a meeting means no war . Idiots . Spy bulls are hands down the dumbest around </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:40 </td>
   <td style="text-align:left;"> $SPY today’s session erased tomorrow ——— 🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:37 </td>
   <td style="text-align:left;"> $SPY When you loaded calls on that pump and dump yesterday.😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:36 </td>
   <td style="text-align:left;"> $SPY the pump will sell off quickly…NBD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:26 </td>
   <td style="text-align:left;"> $SPY BLOOMBERG TERMINAL - &amp;quot;BIDEN ADMITS HE SUCKS AND ASKS TRUMP TO RESUME PRESIDENCY&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:24 </td>
   <td style="text-align:left;"> $SPY now let’s go green 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:24 </td>
   <td style="text-align:left;"> $SPY Futures are ripping. Greats news from Russia and US Talks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:23 </td>
   <td style="text-align:left;"> $SPY LOOOOOOOOOOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:21 </td>
   <td style="text-align:left;"> $SPY  
 
Past precedent of principals, press and priests, pushing puts on powerless peasants, peaked by potential payment 
 
There is a war going on for your mind 
 
https://youtu.be/UDf2r9DnVGU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:20 </td>
   <td style="text-align:left;"> $SPY the bubble is just looking to go up up up pump  pump pump. Any little news or gets it&amp;#39;ll grasp up as high as possible. Still has that bubble mentality to screw shorts and go straight upppppppp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:20 </td>
   <td style="text-align:left;"> $SPY What is now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:12 </td>
   <td style="text-align:left;"> $SPY LMFAO well I guess the v or w ( whatever suck nut ) recovery did come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:11 </td>
   <td style="text-align:left;"> $SPY released at 8.02 pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:11 </td>
   <td style="text-align:left;"> $SPY people on this app r dumb  futures don&amp;#39;t mean anything lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:10 </td>
   <td style="text-align:left;"> $SPY Oh I thought bulls were extinct. Celebrating 8:30 mild futes. If it gets to .6 green, then I&amp;#39;ll give you props </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:09 </td>
   <td style="text-align:left;"> $SPY Everyone has AIDS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:07 </td>
   <td style="text-align:left;"> $AAPL $SPY green in futures?! Feels like it’s been while even though it’ll likely be red by open if not sooner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:06 </td>
   <td style="text-align:left;"> $SPY crazy pump going on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:05 </td>
   <td style="text-align:left;"> $DKNG May dump, may not dump. That&amp;#39;s what earnings YOLOS are for. Calls in honor of 0dte degenerates. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:03 </td>
   <td style="text-align:left;"> $SPY THANK YOU GOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:01 </td>
   <td style="text-align:left;"> $SPY NEW: China Air Force Xi&amp;#39;an Y-20 coming out of Chengdu. Military transport. WATCHING. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:00 </td>
   <td style="text-align:left;"> $SPY putin just wanted to buy bitcoin at 40k $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:37:00 </td>
   <td style="text-align:left;"> $SPY don’t worry. It will be red by 8:45 lol this shit is broken </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:59 </td>
   <td style="text-align:left;"> $SPY $SPX $DJIA  
Well i&amp;#39;m guessing something has just happened. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:53 </td>
   <td style="text-align:left;"> $SPY no warrrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:52 </td>
   <td style="text-align:left;"> $QQQ $SPY lol no news just rippinggngngngng </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:50 </td>
   <td style="text-align:left;"> $SPY am I saved for tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:49 </td>
   <td style="text-align:left;"> $SPY  no way this happens ….. right ? 😄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:46 </td>
   <td style="text-align:left;"> $SPY wow, huge news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:39 </td>
   <td style="text-align:left;"> $SPY war has been cancelled for the 50th time!! Biden is a war hero for the 51st time!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:38 </td>
   <td style="text-align:left;"> $SPY futures ripping

Who knows what will happen tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:37 </td>
   <td style="text-align:left;"> $SPY nice green hulk dick candles. Let’s hope they last. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:34 </td>
   <td style="text-align:left;"> $SPY 453 tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:32 </td>
   <td style="text-align:left;"> $SPY must be news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:28 </td>
   <td style="text-align:left;"> $SPY HAHAHAHA LETS SEE TOMORROE BOYS. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:22 </td>
   <td style="text-align:left;"> $SPY Putin &amp;quot;Russia does not want war&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:21 </td>
   <td style="text-align:left;"> $SPY HAHAHAHA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:19 </td>
   <td style="text-align:left;"> $SPY poor bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:11 </td>
   <td style="text-align:left;"> $SPY OH OH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:36:06 </td>
   <td style="text-align:left;"> $SPY i dont trust this shit no more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:59 </td>
   <td style="text-align:left;"> $SPY gapped the fuck up wow!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:54 </td>
   <td style="text-align:left;"> $SPY holy moly mother fucking shit that excited tf outta my ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:53 </td>
   <td style="text-align:left;"> $BTC.X fucking thank you Bitcoin I can breathe now $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:52 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/unusual_whales/status/1494484862333595654?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:51 </td>
   <td style="text-align:left;"> $SPY $QQQ best news for the market just came out https://twitter.com/BreakingLive_/status/1494484539883892759?s=20&amp;amp;t=e2tNZRbZJaahuEbJBoMw6g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:51 </td>
   <td style="text-align:left;"> $SPY lol looks like the puts are fckd tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:45 </td>
   <td style="text-align:left;"> $SPY if they pump all I know is a lot ppl shorting can cause a squeeze baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:44 </td>
   <td style="text-align:left;"> $SPY US AND RUSSIA TALK next week no war at least through next week or none at all!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:41 </td>
   <td style="text-align:left;"> $SPY the mirei see this the more I feel like it truly is a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:39 </td>
   <td style="text-align:left;"> $SPY some funny ass shiet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:36 </td>
   <td style="text-align:left;"> $SPY lol wow why </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:28 </td>
   <td style="text-align:left;"> $SPY wow!!!! whats goin on???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:22 </td>
   <td style="text-align:left;"> $SPY lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:18 </td>
   <td style="text-align:left;"> $SPY HAHAHAHAH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:16 </td>
   <td style="text-align:left;"> $SPY War cancelled? That gap up was nuts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:15 </td>
   <td style="text-align:left;"> $SPY news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:15 </td>
   <td style="text-align:left;"> $SPY  $ES_F  $NQ_F  #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:11 </td>
   <td style="text-align:left;"> $SPY why futures tipping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:09 </td>
   <td style="text-align:left;"> $SPY whose got a Bloomberg terminal lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:05 </td>
   <td style="text-align:left;"> $SPY Any news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:00 </td>
   <td style="text-align:left;"> $SPY i hope greedy wallst lose their ass on market turmoil and russia war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:35:00 </td>
   <td style="text-align:left;"> $SPY what just happened futures reversed 20 handles in 2 minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:48 </td>
   <td style="text-align:left;"> $SPY lol war, how archaic. Cyberwar ok cool, real war? In this era? Nahhhh stop it.. gap up n melt up tomorrow. They got enough of u scared with that low volume “sell-off” today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:45 </td>
   <td style="text-align:left;"> $SPY well dang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:43 </td>
   <td style="text-align:left;"> $SPY something just happened. But what the fuck was it???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:42 </td>
   <td style="text-align:left;"> $ROKU Uncle Ben Noooooo $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:39 </td>
   <td style="text-align:left;"> $SPY that move isn&amp;#39;t &amp;quot;fake.&amp;quot;  I tried to tell ya... 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:37 </td>
   <td style="text-align:left;"> $SPY I hope Stocktwits eventually mandates screenshots of your option plays one day. So we can expose all these gurus lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:37 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/j6-9p9O-nYw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:36 </td>
   <td style="text-align:left;"> $SPY think the market will react the day the war starts… naive to say the very least, major selloff tomorrow.. if nothing happens over the long weekend expecting a potential relief bullish rally on Tuesday… remember, Olympics are finished up on Feb 22, a lot can wrong over a long weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:36 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
MASSIVE GREEN DILDO  
 
Blinken accepts invitation to meet with Russia&amp;#39;s Lavrov next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:35 </td>
   <td style="text-align:left;"> $ETH.X $BTC.X $QQQ $SPY 

Biden has done a hell of a job stopping the hate in this world, equality and helping grow green energy.   Just killing it going into Presidents Day weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:26 </td>
   <td style="text-align:left;"> $SPY  
 
Honestly, why not keep it simple? 
Follow the trend 
Follow the FED 
Follow the FUD 
 
Then use technicals for your entry points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:25 </td>
   <td style="text-align:left;"> $SPY now we 50 pts down red candle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:18 </td>
   <td style="text-align:left;"> $SPY US SECRETARY OF STATE BLINKEN HAS AGREED TO MEET RUSSIAN FOREIGN MINISTER LAVROV TOWARDS THE END OF NEXT WEEK - STATE DEPARTMENT SPOKESMAN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:16 </td>
   <td style="text-align:left;"> $SPY lol putin backing off or something? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-18 09:34:14 </td>
   <td style="text-align:left;"> $SPY &amp;quot; U.S. SECRETARY OF STATE BLINKEN HAS ACCEPTED INVITATION TO MEET RUSSIA&amp;#39;S LAVROV LATE NEXT WEEK -STATE DEPARTMENT SPOKESMAN &amp;quot; i read this and boom candles? df </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:50:25 </td>
   <td style="text-align:left;"> $QQQ I want to open +3%😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:50:04 </td>
   <td style="text-align:left;"> $QQQ  People will dump before end of day tomorrow. Hold over the long weekend with Putin in attack mode. Open green close red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:49:57 </td>
   <td style="text-align:left;"> $QQQ ironcondor are the best during this period, you make money on both sides. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:49:52 </td>
   <td style="text-align:left;"> $QQQ $SPY If Putin fucks all you bulls overnight… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:48:20 </td>
   <td style="text-align:left;"> $QQQ Who up for calls😁? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:47:53 </td>
   <td style="text-align:left;"> $SPY $QQQ Putin must be making some money from the stock market lately lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:47:48 </td>
   <td style="text-align:left;"> $QQQ None of this Russian war bs should be moving the market at all, bear or bull. Wonder what is really going on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:47:42 </td>
   <td style="text-align:left;"> $QQQ kinda curious how a conversation is bullish. It’s not like there’s a cease fire? They been talking the past few weeks so what’s new? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:47:37 </td>
   <td style="text-align:left;"> $QQQ bears desperate for a war 😂😂🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:47:17 </td>
   <td style="text-align:left;"> $QQQ lol who gives a sh*t if Blinken meets Lavrov next week? This pump will dump morning, blood tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:47:01 </td>
   <td style="text-align:left;"> $QQQ this news means nothing...just a pump and dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:46:48 </td>
   <td style="text-align:left;"> Now that retail loaded up on puts and bought $UVXY at a 20% premium get ready for a mega rally tomorrow! It&amp;#39;s coming and the futures knows it!

$SPY $QQQ $DJIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:46:15 </td>
   <td style="text-align:left;"> $QQQ support at 190✌ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:45:44 </td>
   <td style="text-align:left;"> $QQQ Forced me to close a short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:45:14 </td>
   <td style="text-align:left;"> $QQQ again there will be another news of shelling in Ukraine and mkt down !! Any news is popping or tanking 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:44:55 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures surging all of the sudden, did we get the Russian withdrawing their troops or something lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:44:53 </td>
   <td style="text-align:left;"> $QQQ tomorrow bears will regret not selling their puts. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:44:38 </td>
   <td style="text-align:left;"> U.S. SECRETARY OF STATE BLINKEN HAS ACCEPTED INVITATION TO MEET RUSSIA&amp;#39;S LAVROV LATE NEXT WEEK -STATE DEPARTMENT SPOKESMAN 
 
sorry but not sorry bears 😂 
 
$spy $qqq $sofi $tsla $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:44:21 </td>
   <td style="text-align:left;"> $QQQ $SPY If Lavrov and Blinken meeting end of next week, little chance of invasion happening over the long weekend.  Applying game theory, Putin gets max benefit pushing to the brink of war, but not actually invading.  Just the tip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:44:12 </td>
   <td style="text-align:left;"> $QQQ bulls better sell by the end of the day tomorrow because the next day will be red and then the day after will be green😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:43:45 </td>
   <td style="text-align:left;"> $QQQ Lmao why do people celebrate futes at 8 pm. You’ve got more than 12 hours to get wrecked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:43:41 </td>
   <td style="text-align:left;"> $QQQ lol it doesn&amp;#39;t matter...bad news will come later tonight to negate this move... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:43:29 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:42:38 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:42:31 </td>
   <td style="text-align:left;"> $QQQ $SPY Riot on Wall Street? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:42:08 </td>
   <td style="text-align:left;"> $QQQ bulls have boners cuz blinken meeting with some russian dude late next week. i guess inflation gone. 
what did biden and putin accomplish on their phone last saturday? bull logic, we going to all time highs now cuz we have a meeting with russia next friday!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:41:22 </td>
   <td style="text-align:left;"> $QQQ 
Futes rocketing.  WTH just happened? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:41:14 </td>
   <td style="text-align:left;"> $QQQ $SPY there needs to be some type of regulation this has literally flip flopped everyday overnight this week. Can’t overnight swing at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:40:48 </td>
   <td style="text-align:left;"> $QQQ welcome to fraud street where the masses get screwed over. Stay poor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:40:19 </td>
   <td style="text-align:left;"> U.S. ACCEPTS TALKS WITH RUSSIA&amp;#39;S LAVROV NEXT WEEK 
 
Sorry bears 🐻 ; many big puts will burn tomorrow 😁 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:38:31 </td>
   <td style="text-align:left;"> $QQQ $SPY markets may be saved for tomorrow.  This is hilarious.  Putin must be trading futures.  https://twitter.com/livesquawk/status/1494484516169306114?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:38:07 </td>
   <td style="text-align:left;"> #lottofriday tomorrow and looking forward to it. Can expect some range. Either $SPY and $QQQ confirm the bear flag and we puke Tech or we h </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:37:17 </td>
   <td style="text-align:left;"> $AMPL $QQQ brrrrrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:36:52 </td>
   <td style="text-align:left;"> $QQQ $SPY lol no news just rippinggngngngng </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:36:01 </td>
   <td style="text-align:left;"> $QQQ 😂 420 volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:35:51 </td>
   <td style="text-align:left;"> $SPY $QQQ best news for the market just came out https://twitter.com/BreakingLive_/status/1494484539883892759?s=20&amp;amp;t=e2tNZRbZJaahuEbJBoMw6g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:34:48 </td>
   <td style="text-align:left;"> $QQQ da fuq?  I loaded up on futures for a scalp but just caught a whale </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:34:36 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
MASSIVE GREEN DILDO  
 
Blinken accepts invitation to meet with Russia&amp;#39;s Lavrov next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:34:35 </td>
   <td style="text-align:left;"> $ETH.X $BTC.X $QQQ $SPY 

Biden has done a hell of a job stopping the hate in this world, equality and helping grow green energy.   Just killing it going into Presidents Day weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:34:23 </td>
   <td style="text-align:left;"> $QQQ brrrrrrrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:34:08 </td>
   <td style="text-align:left;"> $QQQ major up moves in the last minute </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:33:27 </td>
   <td style="text-align:left;"> $SPY $QQQ Tomorrow is Friday and next Monday is holiday, hardly anyone would want to hold their shorts ahead of the long weekend since if there is no war over the weekend, the futures are gonna soar on Monday evening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:33:18 </td>
   <td style="text-align:left;"> $QQQ what&amp;#39;s the good news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:25:24 </td>
   <td style="text-align:left;"> $spy price action overview 👁💎

💎So just briefly overlooking the SPY chart, very noticeable large downward channel indicating a drop to the low 400s // 414 to 406 area .. Two things could happen in the morning if Russia does invade, we should immediately gap down to that $430, $429 area.. once it bounces off that demand zone we should see a upward movement of .8% then a catastrophic blow down to that low to that lower trigger. 

💎Now on the other hand if we do get good news and Russia does backtrack and does NOT invade the spy will immediately push up to that 443//444 resistant area test draw down then push back up to that 452 area this is all best case scenario imo. 

💎 current window range for the SPY is 3.76% which is showing extreme volatility for the next 7-8 trading sessions. 

$spx $qqq $spxs $spxl GL traders may you trade green in ANY condition ❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:24:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA stocks going to rip higher tomorrow . Lots of fear but there’s also opportunities..: take some risk in the morning you’ll make money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:23:55 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
https://nypost.com/2022/02/15/biden-to-deliver-remarks-on-ukraine-russia-tensions/ 
 
That&amp;#39;s exactly how a US President and the leader of the most powerful country in the world should act like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:22:01 </td>
   <td style="text-align:left;"> $QQQ tomorrow going to be green bc i bought puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:19:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUT looks like Russia is invading Ukraine!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:18:34 </td>
   <td style="text-align:left;"> $qqq $spy everyday is groundhog day.  Russia will invade, and Bullard will be on CNBC taking up hikes and QT.  Eventually we’ll price it in.  Till then enjoy the volatility. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:17:46 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Buy gold/ silver big move coming 
https://youtu.be/yP4Too1nKY0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:17:45 </td>
   <td style="text-align:left;"> LMAO! The only misallocation was $ARKK buying overvalued junks
 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:17:34 </td>
   <td style="text-align:left;"> $QQQ $ARKK  the disrespect Jim Cramer showed on national television towards Cathie Wood today was absolutely disgusting. 

She has consistently told people her holdings are 5+ years and has never misled people. 

She is literally bringing innovation herself to the market by exposing her trades for the public - THATS probably why there are so many shorts against her.

Big money makes money by deceiving the public. Cathy is exposing her investments and that should be applauded! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:17:01 </td>
   <td style="text-align:left;"> $QQQ It’s like watching an ass whooping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:15:33 </td>
   <td style="text-align:left;"> $QQQ better get a Costco run in soon:

https://www.theepochtimes.com/california-truckers-to-let-freedom-roll-in-peoples-convoy-to-d-c_4283423.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:14:49 </td>
   <td style="text-align:left;"> $QQQ please bring us down to sub 13700. I need cheap shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:14:45 </td>
   <td style="text-align:left;"> $QQQ what’s the realistic chance it will be a Green Day tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:14:41 </td>
   <td style="text-align:left;"> $QQQ Boy a lot of bearish posts here! I&amp;#39;m always the contrarian because 95% of people don&amp;#39;t know how to read charts accurately. 
 
$APPS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:14:13 </td>
   <td style="text-align:left;"> $PALL $SPY $QQQ while everyone was distracted with bloodbath growth stocks. Palladium bottomed at $1800 an ounce at one point this year. A YOLO into Palladium was one of the best plays this year. Who knew? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:13:14 </td>
   <td style="text-align:left;"> $QQQ ... picking up on the fear trade in short-term.. just waiting for some more &amp;quot;confirmation&amp;quot; to sell the bottom 1/2 of yet another Iron Condor on this market.. then go shopping.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:13:08 </td>
   <td style="text-align:left;"> $QQQ I wish Cathie Wood would just shut up already...You&amp;#39;re a &amp;quot;has been&amp;quot; girl and you coulda bought stocks with a blind fold on in 2021 and still made a killing... Hope shes learning what the term &amp;quot;value&amp;quot; means cause she definitely doesn&amp;#39;t own any... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:11:48 </td>
   <td style="text-align:left;"> $QQQ Based on the chart, we are definitely heading lower. We break $343 we are heading towards $339 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:11:39 </td>
   <td style="text-align:left;"> $QQQ 
Only the NASDAQ Futes started off red !🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:10:52 </td>
   <td style="text-align:left;"> $QQQ only need this up 13 dollars tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:10:28 </td>
   <td style="text-align:left;"> $NVDA Major selling before unknown 3 day weekend tomorrow! When markets open Tuesday will there be a war in Ukraine? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:09:27 </td>
   <td style="text-align:left;"> $QQQ Tomm will be another ye ol&amp;#39;  Big $hit Sandwich as Wall St reprices bloated helium inflated tech stocks... No one wanted to hear back in November that inflation would pin that pops this bubble even greater than that of the Dot Com Era... Pigs always get slaughtered in the end sadly.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:09:22 </td>
   <td style="text-align:left;"> $QQQ I’m seeing a similar pattern start to play out now as did in Oct’ 2018 the last time Feds raised rates. In a span of 3 months we had a dip followed by three lower lows before getting back on course. Fast forward to the present year rate hike we had a dip Jan 10th to $370 followed by a lower low to $335 Jan 24th. Now here we are headed for our second lower low EOM of $320 or $300 support. I believe our third and final lower low will be around March 16th give or take a day or two, which would take us to either the $300 or $260 support line. I don’t see us going below $260 as tutes would start loading the boat as retail is throwing up. Hindsight is 20/20 but thinking back, there’s no way the markets could continue a 100% increase in equity year over year. This reset was bound to happen. I know the day traders could care less but for the LT traders, stay strong &amp;amp; emotionless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:09:01 </td>
   <td style="text-align:left;"> $spy $qqq $sqqq $vixy $ung
War follows recession and one of the things that cause recession is inflation, saying this, make your own conclusions… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:08:47 </td>
   <td style="text-align:left;"> $IWM $DOW  $QQQ  $SPY anyone thinks Market has no effect from politics is a complete moron...  You have Russia about to invade, North Korea launching missiles nonstop, Afghan takeover, Iran stepping up etc etc etc. Because Trump was a loose cannon. Most feared what he &amp;quot;might&amp;quot; do. They all think he was crazy and would  set off napalm and nukes in a heartbeat.  Yet no country advanced. North Korea stopped sending bombs in water. Iran cooled off. Russia stayed afoot. Isis hid in bunkers.  ... Biden is a laughing stock of the world right now and they all know it.  And Biden is acting like a tough guy trying to step up to Putin.  Can&amp;#39;t wait when Biden says &amp;quot; oh I can one punch Putin in the face and knock him out&amp;quot; ... Biden is trash. Market is dead for a while. Until usa smartens up in their voting.  /end rant 

Also will not reply back because I could care less with your opinion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:08:32 </td>
   <td style="text-align:left;"> $QQQ $SPY so many bubbles have finally popped as we all knew would eventually happen. Probably some good deals now, but which ones? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:08:10 </td>
   <td style="text-align:left;"> Bought $SPY $QQQ $DIA put options today. I buy at least 3 months out and at least one strike in the money.   #stockmarket #stocks #stocktrading #options #optionstading #putoptions  #money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:07:28 </td>
   <td style="text-align:left;"> $QQQ 
Now that the market finished AH weak, × for red Futes to lead us into the next red PM! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:07:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures higher, looks like at least we will have a modest bounce back tomorrow if not a strong one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:07:05 </td>
   <td style="text-align:left;"> $ARKK 
Benjamin Graham
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:06:09 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA Russian war has nothing to do with the US economy testa di minchia shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:05:01 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DJIA $USO  
 
You have to remember something. Russia makes most of its money from oil. Having a lot of troops near Ukraine border makes oil prices go UP. So dont think Russia is just going to remove all troops and watch oil price fall even if they have no intension to invade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:04:55 </td>
   <td style="text-align:left;"> $SPY $QQQ /ES Max Daily  - “h” not good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:04:20 </td>
   <td style="text-align:left;"> $SPY $QQQ 
They need to drop the SPY to 400 already I mean what’s another 30 points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:03:08 </td>
   <td style="text-align:left;"> $QQQ should I buy futures right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:02:32 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA See the guy in this picture?  He&amp;#39;s an investing legend.  He was  buying stocks in January.  As was Bill Ackman and Michael Burry. 
 
See all the bears jacking each other off?  They&amp;#39;re nobodies.  Most of them are wagecucks and can&amp;#39;t even get by on what they earn in the market.  Options junkies who regularly sacrifice long-term profits for short-term excitement. 
 
Whose advice would you sooner follow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:02:06 </td>
   <td style="text-align:left;"> $QQQ $SPY  Yields dropped after fed minutes. Oil dropped because of excess supply in case Russia stops exporting. Neighboring countries keep fighting forever. Ukraine Russia do not export any significant to effect global economy although may supply gas to neighbors. Because of Mid term elections Biden naming Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:00:50 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA $IWM Better to get out before your portfolio turns to ashes! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 09:00:03 </td>
   <td style="text-align:left;"> $SPY $qqq $dia why is everyone saying bloodbath? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:59:59 </td>
   <td style="text-align:left;"> $TSLA $QQQ $NASDAQ Maybe Russia will invade after the Olympics ends.    Thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:59:05 </td>
   <td style="text-align:left;"> I’d love to know how selling puts to kids is working out for some geniuses out there. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:58:36 </td>
   <td style="text-align:left;"> $QQQ Mutha Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:57:18 </td>
   <td style="text-align:left;"> $QQQ if russia taking over Ukraine can derail our stock market, still not sure how then will if the media says GLOBAL WAR CHINA VS USA WW3. Would this tank markets badly. If so pooots on China </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:56:31 </td>
   <td style="text-align:left;"> $QQQ Biden has been weak day 1 and this is what you get, jimmy Carter 2.0!  sad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:56:13 </td>
   <td style="text-align:left;"> $QQQ ugly day but still within support. $344-$345 is a huge area to hold. Should test $348 in the coming days, unless …. Russians </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:55:18 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY $TQQQ This headlines saying stuff like the War in Ukraine is causing this sell off. 🗣Newsflash CNN. It’s not the war, it’s inflation!!! Freaking inflation stop creating a false sense of comfort that is not true. @CNNMoney </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:54:54 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … so sad fed killing T.I.N.A. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:53:41 </td>
   <td style="text-align:left;"> Charts of Interest $SPY $QQQ $GLD $NEM $FNV etc 
 
https://fearlessnotreckless.com/chartaddict/2022/2/17/charts-of-interest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:52:04 </td>
   <td style="text-align:left;"> $QQQ $SPY well I guess we gonna keep dropping, FUD production machine at full capacity while money printer is jammed, drop it to $300 and $400. It’s a crisis out there, where’s the reset button??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:51:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY what most traders are screaming to Putin… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:50:51 </td>
   <td style="text-align:left;"> $NASDAQ $DJIA $QQQ 

Hitting overbought levels is essential for keeping a trend going.. because like, math &amp;amp; stuff. So not hitting overbought levels while MACD is green… well, you get the picture. 

🔮 🔮 the more you know 🌈 ☀️ 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:50:24 </td>
   <td style="text-align:left;"> $qqq $spy $uvxy $ung $KOLD

https://www.fidelity.com/learning-center/trading-investing/ukraine-russia?ccsource=email_weekly_0217 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:49:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Who wants to hold over the long weekend? Unless we get a really good headline this will tank tomm. Thinking about buying an equal amount of puts and calls tomm. Will make money if no war or a war. (Praying for no war unlike some sick fu(ks here) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:47:49 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA so the market is running out of coke and it’s aching for a fix. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:47:26 </td>
   <td style="text-align:left;"> $QQQ The daily looks telling.  The gap up Tuesday closed right below resistance.  Failed to break above resistance Wednesday.  RSI did not get above 46 even on the Tuesday gap up.  Ideally I like to see 50+ for strength.  True direction is evident. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:42:35 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.youtube.com/watch?v=WHv12wOWX08 
 
Cramer is right, I can&amp;#39;t believe anyone would be giving their money to Wood to invest for them, she trades recklessly and buy names that might never be profitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:41:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $SPX

Biden to host meeting on #Ukraine on Friday with leaders of Canada, France, Germany, Italy, Poland, Romania, Britain, EU and NATO - RTRS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:41:26 </td>
   <td style="text-align:left;"> 1-Minute Market Recap &amp;amp; Trade Plan For Tomorrow:  
2.17.22 - 2.18.22  
$ES_F $NQ_F $SPY $QQQ $NVDA  
 
https://www.youtube.com/watch?v=1NDJE4tC5Tk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:41:15 </td>
   <td style="text-align:left;"> $QQQ I am not a republican, I am not a conservative. I am firmly left wing and I&amp;#39;m from Ireland. But I knew this shit would happen when Biden got in, back to the good old war mongering games. Like I dislike Trump for many reason but he was the best president USA has had in years in terms of world peace. He de-escalated tensions with Russia, North Korea and everyone else, he was against war and wanted to solve things via business deals and trade. As soon as the dems and a good ol&amp;#39; tool of the system like Biden got in you just new the military industrial complex and the propaganda would go into overdrive again and here we are. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:40:19 </td>
   <td style="text-align:left;"> $QQQ the market will start recovering when the bears become very greedy. We are very close to this situation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:39:31 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … 

♦️if u r still bullish on this market thats a tell u did not make enough last 2 yrs ✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:39:10 </td>
   <td style="text-align:left;"> $QQQ  $AAPL  #Any Thoughts  on 162 Tomorrow  $SPY  $ES_F  $NQ_F #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:35:24 </td>
   <td style="text-align:left;"> $UVXY $QQQ $ES $NVDA ;; 
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $87,569 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 topgainer.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:35:16 </td>
   <td style="text-align:left;"> $QQQ $DKNG Who&amp;#39;s long on DraftKings headed into earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:33:17 </td>
   <td style="text-align:left;"> $QQQ , $SPY , $IWM , $RUT : People those haven&amp;#39;t seen 2008 or before =&amp;gt; It&amp;#39;s for them !! In free money world , everyone is a hero $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:30:57 </td>
   <td style="text-align:left;"> $QQQ its getting very crowded with shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:28:58 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DJIA $BTC.X  … 

👇🏻I tried♦️ .. maybe I need to spell it out loud ⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:28:05 </td>
   <td style="text-align:left;"> Stocks take it on the chin again. $QQQ $DJIA https://www.billionaireclubcollc.com/stocks-take-it-on-the-chin-again/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:25:46 </td>
   <td style="text-align:left;"> $JPM $SPY $QQQ $DJIA 

Senate passes bill to prevent government shutdown, sends it to Biden https://www.cnbc.com/2022/02/17/government-shutdown-senate-passes-funding-bill-sends-it-to-biden.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard

This is great news . Stocks going to crash much lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:25:37 </td>
   <td style="text-align:left;"> $QQQ 🇷🇺 🇷🇺 🇷🇺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:25:30 </td>
   <td style="text-align:left;"> $QQQ ALEXA! Do large increases in etf&amp;#39;s follow large decreases? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:25:29 </td>
   <td style="text-align:left;"> $QQQ  remember kiddos do inverse stocktwits and short Cathie. :D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:25:18 </td>
   <td style="text-align:left;"> Daily $QQQ stock analysis based on closing price 

https://youtu.be/ILiKJ1bxVPM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:25:14 </td>
   <td style="text-align:left;"> $CENN $NVDA $SPY $QQQ 
Incase you miss him 😘
https://youtu.be/5aBSwld6SIE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:24:41 </td>
   <td style="text-align:left;"> $QQQ The only way from here is down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:23:41 </td>
   <td style="text-align:left;"> $QQQ $SPY the reason we had a V shape recovery after the covid crash is because the fed bailed the market out by putting in trillions of dollars into the market. 
i am not betting on a V shape recovery, the fed is not going to be accommodating anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:23:31 </td>
   <td style="text-align:left;"> $QQQ what is happening to my retirement??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:22:23 </td>
   <td style="text-align:left;"> $BBIG $QQQ For a limited time,, we are opening our trading chatroom to the public  
 
most-profitable.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:22:05 </td>
   <td style="text-align:left;"> $BTC.X helllo I’m Becky and I’m bearish $SPY.X $QQQ $ETH.X $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:20:56 </td>
   <td style="text-align:left;"> $QQQ get ready for additional supply shortages as truckers start a convoy in the US this weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:18:04 </td>
   <td style="text-align:left;"> $QQQ Biden is sending in the CIA to start a false flag war for the bears. Shorting is gonna be good money but the fallout probably make dicks not work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:17:51 </td>
   <td style="text-align:left;"> $MNMD i bought the dip. I hope this goes lower again. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:16:48 </td>
   <td style="text-align:left;"> $QQQ Killer today

https://t.me/+jzSoLm3xsOw0NTgx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:16:05 </td>
   <td style="text-align:left;"> $QQQ 

https://t.me/+jzSoLm3xsOw0NTgx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:15:06 </td>
   <td style="text-align:left;"> $QQQ wait for that v shape recovery $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:14:21 </td>
   <td style="text-align:left;"> $QQQ  absolutely  ZERO reason to hold into this long weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:12:25 </td>
   <td style="text-align:left;"> $SPY $QQQ 
A growth Bull market for over a decade will take much longer than a few months to unwind.

March of 2020 lows are by no means a back stop

Do not use past ATH’s as a reference for position entries </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:10:54 </td>
   <td style="text-align:left;"> $ROKU $ARKK A good time for another reminder...$QQQ $SPY $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:10:33 </td>
   <td style="text-align:left;"> $SPY $QQQ ….  $RSX is the buy. 

Not Tech/S&amp;amp;P </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:10:21 </td>
   <td style="text-align:left;"> $QQQ Inflate or not. Raise rate or not. We are all doomed. 
https://youtu.be/UsxAAbpkMWc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:08:56 </td>
   <td style="text-align:left;"> $SPY $qqq Gold for sale </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:08:17 </td>
   <td style="text-align:left;"> $QQQ the insanity 

&amp;quot;Bullard Says Fed May Need to Raise Rates Above 2% to Curb Prices&amp;quot;

https://ca.investing.com/news/economy/bullard-says-fed-may-need-to-raise-rates-above-2-to-curb-prices-2641035 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:07:19 </td>
   <td style="text-align:left;"> Fed’s Mester says the FOMC should act more quickly than in the previous tightening episode $DJIA $QQQ https://www.billionaireclubcollc.com/feds-mester-says-the-fomc-should-act-more-quickly-than-in-the-previous-tightening-episode/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:06:26 </td>
   <td style="text-align:left;"> $QQQ desperation when retail bulls excited about after hours being up 0.09% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:06:24 </td>
   <td style="text-align:left;"> $NASDAQ $DJIA $QQQ $SPY $VXX 

🤭🤭🤭🤭 rut-roh.. considering it changed behavior &amp;amp; ramped up last week &amp;amp; is now.. yeeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:05:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $DJIA $UVXY

Dozens of artillery strikes committed by Russian-led militants in #Donbas left 2 Ukrainian soldiers injured and 3 civilians concussed.

Over 47 incidents of enemy shelling have been registered along the 420-km frontline, as of 7 p.m. on Feb. 17. 

https://kyivindependent.com/national/over-40-shelling-incidents-leave-5-injured-in-donbas/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:04:50 </td>
   <td style="text-align:left;"> $QQQ Geez that Biden, ruining everything for everyone... accept for those billionaires who keep getting richer, Trump was better at least the billion dollar babies had a green light ... as a matter of fact can&amp;#39;t remember the president who made poor rich and the wealthy poorer, who to blame?,  need answers ASAP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:04:34 </td>
   <td style="text-align:left;"> $SPY big liquidity issues, kids

$QQQ $FB $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:03:43 </td>
   <td style="text-align:left;"> $QQQ $NQ_F this is going to be an outside year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:03:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL   after 2 weeks at ichimoku cloud top magnet resistance.. retested old flat white line. 26 day candle average line.. when it goes flat. that level is important.. and strong.. buyers have huge opportunity to bounce and breakout of cloud top.  sellers again will retest flat cloud bottom support again.. doesnt have to..  still favoring blow off top tacos.. (a break below ichimoku cloud changes that for near term) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 08:02:43 </td>
   <td style="text-align:left;"> More from Fed’s Mester – Fed will take action to keep inflation under control  $QQQ $DJIA https://www.billionaireclubcollc.com/more-from-feds-mester-fed-will-take-action-to-keep-inflation-under-control/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:59:50 </td>
   <td style="text-align:left;"> $qqq them futes rippin’ 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:59:46 </td>
   <td style="text-align:left;"> $ROKU $SHOP $PINS $QQQ I said this 11 months ago and shorted meme garbage. Roku and shop and pins down 70% plus from that day. Just as predicted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:59:01 </td>
   <td style="text-align:left;"> $QQQ honestly Joe Biden has ruined this country </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:58:09 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : Causeway Capital: Introducing Causeway Global Sustainable Leaders Equity Strategy https://www.stck.pro/news/QQQ/23070432 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:55:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $XXII The US should just say the Russians will invade “tomorrow”. That way the Russians will not invade Ukraine “tomorrow” to prove America wrong. Repeat every day to prevent war.  #strategery </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:55:32 </td>
   <td style="text-align:left;"> $QQQ ok so we’re back to shitty ERs absolutely wrecking equities. Who is ready to revisit January lows??!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:55:30 </td>
   <td style="text-align:left;"> $QQQ Y&amp;#39;know the stock market doesn&amp;#39;t tank every time Israel and Palestine have conflict.  Why is this any different?  Russia and Ukraine have been fighting since 2014 - it will never stop. 
 
This is a non-event people.  Biden is trying to turn the shift away from the inflation quagmire that he is responsible for. 
 
Mainstream media and Wall Street playing games.  This will have very little effect on the US. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:55:23 </td>
   <td style="text-align:left;"> $QQQ one bounce, please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:55:09 </td>
   <td style="text-align:left;"> $QQQ retest 334? My $SQQQ calls may pay handsomly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:53:47 </td>
   <td style="text-align:left;"> $SPY  $QQQ I noticed  around  $19M  put for tomorrow  
Lets get rebound some to burn that puts !!  
 
Also $tsla call we’re bougth about 50M due tomorrow .. so far that call is toasted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:51:32 </td>
   <td style="text-align:left;"> $QQQ Don’t fight the Fed and Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:51:25 </td>
   <td style="text-align:left;"> $QQQ $SPY well of course it will bounce a little bit after BLEEDING ALL DAY. y’all need to chill out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:51:10 </td>
   <td style="text-align:left;"> $VIX VX futures hourly chart. One big bull flag inside of a rising channel… quite the inception. All I can see here is that it’s due for a VIX crush. Overbought on several timeframes. Otherwise a bullish uptrend. 
Don’t tell me you can’t chart volatility -
If it has candles, you can chart it. 

$SPY $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:50:11 </td>
   <td style="text-align:left;"> UK Times reports that senior UK government figures ” convinced Putin is about to invade” $SPY $DJIA $QQQ  https://www.billionaireclubcollc.com/uk-times-reports-that-senior-uk-government-figures-convinced-putin-is-about-to-invade/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:49:59 </td>
   <td style="text-align:left;"> $SPY $QQQ had puts sold them at open for 40% they went 320% by close felt sick loaded calls to counter it and now down 28% going into tomorrow expiry. Double sickness 🤮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:47:19 </td>
   <td style="text-align:left;"> $SPY $QQQ I miss the circuit breaker🤨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:46:47 </td>
   <td style="text-align:left;"> $QQQ futures are up should I go bullish $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:46:37 </td>
   <td style="text-align:left;"> $QQQ Anyone think this could be up tomorrow?  I for one think there’s a shot at it happening. Anyone else? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:46:36 </td>
   <td style="text-align:left;"> $ROKU total garbage Down $255 bucks or 69% since I shorted $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:46:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $ROKU $ARKK No such thing as price action trading, right? Its all a fugazi like Matthew McConaughey&amp;#39;s lunch scene in the wolf of wall street, riiiiggghhtt?? Learning to read a chart will take you A LOT of screen time.... way longer than you think. Always go looking for confirmation. Never try and enter a trade first. You have two options IF you&amp;#39;re serious. Either A, trade simulated money or B, risk very little. $5-10 a trade. Be careful out there and stay objective.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:44:30 </td>
   <td style="text-align:left;"> $QQQ Don&amp;#39;t let the BS futures lead you on to something, this will be down another 2/3% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:43:54 </td>
   <td style="text-align:left;"> $SPY $QQQ I bet not very smart people will be watching overnight ES futures like an indicator for tomorrow implied action hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:43:37 </td>
   <td style="text-align:left;"> $QQQ $FB Facebook needs to ease up on their Metaverse spending, 10 billion dollars?!?! It should be $1 billion AT MOST and they should treat it like a side project like Google Maps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:43:27 </td>
   <td style="text-align:left;"> $QQQ we good? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:42:48 </td>
   <td style="text-align:left;"> $QQQ war or no war? What are doing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:42:15 </td>
   <td style="text-align:left;"> $QQQ now biden and NATO strategy is to buy time with Putin as after March Putin will miss a good chance to attack Ukraine once the snow on the ground melts.
If they can buy time with Putin for another month, the war tensions could be put off until winter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:41:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  the Quadruple higher corndog pattern..   buyers have to get over 9 day candle average line( red). then white 26 day candle average line..  at etreme distance form cloud.. needs retest.   
 
will update the AAPL chart.. mentioned target was cloud top resistance.. it hit and sold off..  saw massive CALLS so looked primed for immediate breakout.. now needed a bounce off strong support to get over ichimoku cloud top resistance.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:40:22 </td>
   <td style="text-align:left;"> $spy $qqq $ETH.X remember when US satellite intelligence said that Iraq had weapons of mass destruction? Yeah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:38:29 </td>
   <td style="text-align:left;"> $QQQ let me guess teh stupid bull that chased yesterday and today is screaming market rebound tomorrow lmao. Sorry to break it to you all but the bull market run its over, for months now its been the pump and dump market not bull market. Now we enter the BEAR market $SPY $DYD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:36:44 </td>
   <td style="text-align:left;"> $qqq $spy don’t worry! let’s buy globally cannabis stocks  $TLRY $acb $sndl wooooffff🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🤑🤑🤑🤑🤑🤑🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:36:22 </td>
   <td style="text-align:left;"> $QQQ no one is holding over the weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:36:17 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:36pm)

⦿ $QQQ is down 0.0% in the last 5 mins. 

⦿ There are 21 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 10.5% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:35:27 </td>
   <td style="text-align:left;"> $QQQ sorry fellow bears but I called it. Too obvious that they were going to bounce this back up for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:34:40 </td>
   <td style="text-align:left;"> $QQQ The war is imminent boys. Putin’s main demand is for NATO to withdraw from neighboring countries and go back to what they verbally agreed on in 1997. That’s not gonna happen. They know it, US and NATO knows it, so it’s just a matter of time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:33:42 </td>
   <td style="text-align:left;"> $QQQ March puts on tap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:33:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Bird Flu Detected In Kentucky, Virginia, Indiana As Outbreak Spreads: Officials

I SURE HOPE THEY DON’T MANDATE VACCINES FOR THE PUBLIC

COMBO  (COVID/N1H1) ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:33:03 </td>
   <td style="text-align:left;"> $QQQ there will be a sympathy bounce tomorrow. Then we will continue our leg down to visit January lows next week.  I think in March we will hit new lows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:32:58 </td>
   <td style="text-align:left;"> $QQQ Energy, specifically oil will be the top performing sector of 2022 and it won&amp;#39;t even be close. Dump the bloated Tech stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:31:34 </td>
   <td style="text-align:left;"> $SPY $QQQ If 14000 gets taken out overnight or by open you better start praying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:31:18 </td>
   <td style="text-align:left;"> $QQQ Ukraine rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:31:11 </td>
   <td style="text-align:left;"> $QQQ all in at 300 dollar😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:31:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX Easy money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:28:08 </td>
   <td style="text-align:left;"> $QQQ $ARKK It seems like every stock in ARK&amp;#39;s Innovation Fund tanks after announcing earnings, may this fund R.I.P.💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:27:16 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm $labu
Today was a low volume selling.
That’s very bullish.
Not to many people left to sell.
Expect a massive rebound $$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:26:45 </td>
   <td style="text-align:left;"> $QQQ woooooweeeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:23:49 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $UPST $ROKU this market bout to go stoopi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:23:35 </td>
   <td style="text-align:left;"> $PLTR wtf 
this company gona bankrupt or what? 
there are many stocks hurt badly... still people dont think there is recession $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:22:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN CANOES SHIPPIN OARS DIPPIN AND FLIPPIN SCOTTIE PIPPEN 🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:18:11 </td>
   <td style="text-align:left;"> $SPY $NASDAQ $QQQ $TSLA $AMZN It it only me, or do others see 10,000 coming? 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:17:16 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : Dalio: Where We Are in the Big Cycle of Money, Credit, Debt &amp;amp; Economic Activity https://www.stck.pro/news/QQQ/23070248 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:17:09 </td>
   <td style="text-align:left;"> $SPY $QQQ Retailers holding onto their cash... will be kicking themselves when they miss out on the upside 
https://www.youtube.com/watch?v=EVALoIuwfak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:16:48 </td>
   <td style="text-align:left;"> $QQQ 340 test coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:16:29 </td>
   <td style="text-align:left;"> $QQQ I better get my war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:16:09 </td>
   <td style="text-align:left;"> $QQQ it’s gonna bounce to like 347-349 tomorrow and then flush into Tuesday to 340 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:14:46 </td>
   <td style="text-align:left;"> $SPY $QQQ like i said before... i have no idea what the markets were thinking running the way they did these last few weeks....but it was great averaged up ...you bulls were just holding my money for me...now its mine again.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:14:04 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA lmao who was the bulls believing Tom Lee like he’s the holiest of markets gods 🤣🤣

Every time that dude said some shit the bubble bursted right after the DOT.com and the housing crash 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:13:56 </td>
   <td style="text-align:left;"> $RBLX $dbx $nvda $qqq

Market does not make sense anymore!!!

You you beat er you down when

Dbx and NVDA beat er top and bottom yet still down

😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:12:52 </td>
   <td style="text-align:left;"> $QQQ back to 230–where it was before the Fed created a stock bubble by cutting rates and pumping trillions of dollars into the economy. You guys are gonna be in the poor house if you stay long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:12:02 </td>
   <td style="text-align:left;"> $spy $qqq $dia government shutting down tomorrow. Strap in boys. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:11:59 </td>
   <td style="text-align:left;"> $PYPL to $QQQ ratio lowest in the stocks trading history what does everyone think about this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:11:25 </td>
   <td style="text-align:left;"> $QQQ $TSLA $GM What do you guys think of GM bringing back the EV1 with its lead-acid battery pack? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:11:17 </td>
   <td style="text-align:left;"> $QQQ all Fed bubble gains during COVID will evaporate. Expect QQQ to drop 25% from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:11:08 </td>
   <td style="text-align:left;"> $QQQ it’s in front of your face. EVERY SINGLE DAY. Yet you ignore it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:10:58 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
https://washingtonmonthly.com/2022/01/19/the-biden-jobs-boom-is-bigger-than-we-thought/ 
 
Bottom line, ignore the war headlines. The US economy is doing very well right now and as long as the economy continues to do well, earnings are going to rise and it means stock prices are going to rise as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:10:42 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM 1 step forward, 2 steps back...and closing at the low...I&amp;#39;m still long...smh 
One possible good news is that sentiments are so bad, that they could be interpreted as &amp;quot;good&amp;quot; (contrarian indicator). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:10:34 </td>
   <td style="text-align:left;"> $QQQ we gonna fresh start with 0 in 2022 with this speed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:10:29 </td>
   <td style="text-align:left;"> $QQQ https://imgur.com/a/9J2vGOB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:09:38 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-17 Daily Forecast Video: 
https://www.youtube.com/watch?v=CV47OKiDe5w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:09:01 </td>
   <td style="text-align:left;"> $QQQ $SPY Who gambled and got calls?  Who is buying to reverse the market at this condition?  The fed?  Damn idiots. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:08:25 </td>
   <td style="text-align:left;"> $ARKK $$QQQ I like a lot of the picks… def not all. But I feel like this market is just trying to sink the ArK funds really badly (see what I did there?) and then it’ll recover. Maybe big funds really don’t like her style and uncharacteristic transparency with investors… I dunno 🤷‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:08:01 </td>
   <td style="text-align:left;"> $QQQ just imagine how powerful our ecobony will get once king joe successfully annexes russia! ATHs after we win the war! make sure your sons and daughters are registered for the draft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:07:07 </td>
   <td style="text-align:left;"> $ARKK $QQQ the most idiotic thing is people who are buying now expect another bounce similar to 2021 ... no you will have to wait to 2033 just to break even bozos lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:06:40 </td>
   <td style="text-align:left;"> How this silent crash is unfolding:
First small caps got killed
Then mid caps slaughtered 
Now large caps being demolished 
Last mega caps 🔪 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:06:39 </td>
   <td style="text-align:left;"> $QQQ  This is at the bottom of the linear regression channel where reversals always &amp;amp; imminently occur right at neckline support &amp;amp; about to enter an Elliott wave 1 up.  ADX is rising indicating a strong trend about to commence. This is going to bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:06:38 </td>
   <td style="text-align:left;"> $ARKK lol repost from a while ago $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:06:30 </td>
   <td style="text-align:left;"> $QQQ $SPY I have a lot of respect for Biden, the man has seen a wife and son die and continued on to become Vice President/President. Meanwhile, plenty of people would be looking for rope by simply losing money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:05:45 </td>
   <td style="text-align:left;"> $QQQ $SPY Futes are sharting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:05:32 </td>
   <td style="text-align:left;"> $QQQ 50%⬇️⬇️⬇️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:05:23 </td>
   <td style="text-align:left;"> $QQQ $SPY market will dump so hard into the weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:05:19 </td>
   <td style="text-align:left;"> $SPY Are we gonna volmageddon? $UVXY $VIX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:05:08 </td>
   <td style="text-align:left;"> $QQQ who&amp;#39;s ready to go to the moon tomorrow? futes rippin, ATHs again at open baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:04:38 </td>
   <td style="text-align:left;"> $SPY $QQQ even Acorns on that FUD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:03:43 </td>
   <td style="text-align:left;"> $QQQ feels like the pandemic was a plan for the rich to get richer and sell at the top…lots of portfolios lost… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:03:40 </td>
   <td style="text-align:left;"> $QQQ Futes is Strippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:03:37 </td>
   <td style="text-align:left;"> $spy $qqq aaLat:1243 trigger . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:03:25 </td>
   <td style="text-align:left;"> $QQQ Fute is pissing, dipping shitting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:03:16 </td>
   <td style="text-align:left;"> $QQQ futes ripin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:02:50 </td>
   <td style="text-align:left;"> $QQQ BIGGGG negative deltas. It’s not good, at all! Good news is, if Russia news backs off sharply we could get a beautiful squeeze with so much negative delta.  
 
In this market just keep scalping what you can. 🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:02:39 </td>
   <td style="text-align:left;"> $QQQ  
 
QQQ Key Levels Grid For Feb 18 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:02:26 </td>
   <td style="text-align:left;"> $TSLA what was the last upgrade price on this name and by who??? lmao 600 coming $QQQ $SPY sell off... #MarketTrade #LookOutBelow wait to buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:02:21 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $DJIA Frankly, there was no news Today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:01:13 </td>
   <td style="text-align:left;"> $SPY $qqq me scalping all this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:00:29 </td>
   <td style="text-align:left;"> $QQQ short till Biden’s out of office </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:00:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM we should all just give the crooks what they want and sell. Look at $AMPL and $FSLY . You’re telling me they deserve haircuts of 30 and 50% just on guidance misses? This has to be the worst market in over 20 years . We should all be absolutely embarrassed to be apart of it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 07:00:10 </td>
   <td style="text-align:left;"> $QQQ glad I still held some puts for March from last week 😋 $SPY 
Always nice holding onto some runners with free money. I’ll probably lose on my dumb long butterfly spreads though. I need 440, 445 or 450 lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:59:56 </td>
   <td style="text-align:left;"> $QQQ WW3 and hyperinflation officially priced in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:58:45 </td>
   <td style="text-align:left;"> $QQQ there goes my calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:58:17 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 2/17/2022 $SPY $XLF $QQQ $GDX $FB https://www.chartguys.com/daily-market-videos/4140/market-bear-flush-to-support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:58:09 </td>
   <td style="text-align:left;"> $QQQ you should look at qqq max pain this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:56:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $RBLX pull up wit a drone like I’m Tommy Lee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:54:26 </td>
   <td style="text-align:left;"> $QQQ $NQ_F #NASDAQ #stockmarket #equities #Futures #Trading #marketforecast Short term data has plenty of room to support further weakness.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:53:55 </td>
   <td style="text-align:left;"> $QQQ short term traders turned into long term investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:52:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $ETH.X The staggering amount of puts bought today must be burned at the stake.  TOSS THEM IN THE TRASH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:52:01 </td>
   <td style="text-align:left;"> $SPY $QQQ  is it concerning that many stocks 90% off highs have another 90% drop to go? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:51:43 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://twitter.com/ARKInvest/status/1494391052022829057?cxt=HHwWgsC-tdCvkr0pAAAA 
 
Cathie Wood taking a shot at CNBC, guess she wasn&amp;#39;t happy with the interview lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:51:36 </td>
   <td style="text-align:left;"> $QQQ violent rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:49:46 </td>
   <td style="text-align:left;"> $SPY $QQQ futes goin down tonight like a girl from Staten Island! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:48:29 </td>
   <td style="text-align:left;"> $QQQ you guys miss Trump yet? At least he was good for your money. Now you have a senile 80 year old fuck as a captain. Putin shits on old farts. Have fun riotting again soon as the market will steal are your money! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:48:21 </td>
   <td style="text-align:left;"> $QQQ $SPY this market smells like joe Biden’s pussy 🐟 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:48:00 </td>
   <td style="text-align:left;"> $QQQ Whether this goes up or down will depend on Russia&amp;#39;s move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:45:49 </td>
   <td style="text-align:left;"> $QQQ $SPY $WOOF this market is dogshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:45:25 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:45:15 </td>
   <td style="text-align:left;"> $ROKU shot of hitting under 100 tomorrow if $QQQ bleeds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:44:07 </td>
   <td style="text-align:left;"> $QQQ just down 70% these  past 4 months. I’m so broke lol. I swear I won’t invest again in my life once I recover. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:43:53 </td>
   <td style="text-align:left;"> $QQQ $NQ_F #NASDAQ #stockmarket #equities #Futures #Trading #marketforecast Its the same here. Price has so much room to drop, and still be bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:42:52 </td>
   <td style="text-align:left;"> $SPY $QQQ Just checked the state run propaganda network CNN and The NYT who are still pushing the Russia Fear Porn. Good. This should give me a chance to get some $GOOG at $2600, $FB $199.99,  $CRM  $199 and maybe catch a few other sales tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:42:19 </td>
   <td style="text-align:left;"> $QQQ still plunging after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:41:37 </td>
   <td style="text-align:left;"> $QQQ can anyone tell me how the charts look bullish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:41:32 </td>
   <td style="text-align:left;"> $AAPL Ok so if China invaded Taiwan, goods will freely flow from mainland China to the US?  And chips will freely flow from Taiwan to US companies? OK. Apple will be a mushroom cloud. $QQQ $BABA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:41:28 </td>
   <td style="text-align:left;"> $SPY Just follow the big money... You&amp;#39;ll do much better when you trade with those who move the market
$QQQ $AAPL $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:39:37 </td>
   <td style="text-align:left;"> $QQQ ordered myself 2 minute noodles in bulk for the next 6 months, does the media ever give any good news fuck them... at least I know $OPEN  will blow earnings I’ll eat salmon that day😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:39:35 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.usatoday.com/story/opinion/columnists/2022/02/15/ukraine-russia-invasion-biden-test/6788565001/?gnt-cfr=1 
 
A good reminder of why Americans made a great choice by voting for Biden over Trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:39:21 </td>
   <td style="text-align:left;"> $QQQ $SPY chance of low volume throwback, but we’re not looking too good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:38:27 </td>
   <td style="text-align:left;"> Looks like there was a late lunch special 🤔 #stocks #bitcoin #economist #trader $SPY latex9cf49abf69532676e351dfe9f7552fc4SPY PUTS ALL THE WAY DOWN 1.16➡️2.10 over 100% if you held 🔥💵

$MRO ER TRADE OVER 150% AT PEAK 0.1➡️0.21 ✅🤑

DISCORD LINK IN BIO $ROKU $DKNG $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:37:20 </td>
   <td style="text-align:left;"> $QQQ $SPY just wait for March madness!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:37:18 </td>
   <td style="text-align:left;"> $SPY $QQQ this POS market better gap down tomorrow. 3% close at low of day. don&amp;#39;t want to see no stupid gap up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:36:57 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA there is no point to have 1 country to be ruled by 2 parties. 1 creates, another demolishes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:36:46 </td>
   <td style="text-align:left;"> $ARKK As bad as this is it still outperforms $SPY and $QQQ for the last 5 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:36:22 </td>
   <td style="text-align:left;"> $QQQ $SPY  $QQQ  TODAY FLUSHED THE CALLS.  MARKET MAKERS NEED TO FLUSH THE PUTS 2-1 TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:36:06 </td>
   <td style="text-align:left;"> $QQQ $PLTR $SPY  is anyone even making money anymore in this market lol. Hedge funds and govt working together to make it as confusing as possible and make most retail loose as much money as possible so they’ll never come back . Jobs are also going down so they want people to come back into the rat race. You can call it conspiracy but I think everything is connected . It was too easy to make money 2020-2021. They reversing it all to take it all back. $AMC $GME fucked up the whole market for everyone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:34:42 </td>
   <td style="text-align:left;"> $QQQ you know what&amp;#39;s nice? Shorts have to time this perfectly. They&amp;#39;re up, sure, but when do they sell? The stress there is actually just as bad as it is for us on the long side. But the difference is, over the long haul, I know markets go up. So I can dollar cost average forever and not have to worry about timing it perfectly like the bears do.

Much scarier on the other side. 

$ENPH $QLD $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:34:32 </td>
   <td style="text-align:left;"> $QQQ march is coming = bloody sheesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:33:51 </td>
   <td style="text-align:left;"> $QQQ fun market… how long is it going to bleed out for? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:33:49 </td>
   <td style="text-align:left;"> $SPY  $QQQ  $AAPL BUY FEAR. 🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁💝💝💝💝💝💝YOURE WELCOME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:33:41 </td>
   <td style="text-align:left;"> $SPY $QQQ were so at war with russia and China.. https://youtu.be/JWR8JUB0jN8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:30:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Probably will bounce back hard tomorrow. Shorts will cover into the close of a 3 day weekend. 

https://youtu.be/qwe00TZVfd0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:30:26 </td>
   <td style="text-align:left;"> I&amp;#39;m getting tired of this Russia-Ukraine shit.. You know what.. Why would we (US) care about Russia invading Ukraine?  Let them be... Let EU settle their shit.

We&amp;#39;ve got too many problems ourselves.. Focus on fixing them.. geez..

$SPY $QQQ $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:27:14 </td>
   <td style="text-align:left;"> $QQQ any chance $357 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:26:24 </td>
   <td style="text-align:left;"> $ISPO Bingo! Crazy mover today… I didn’t even catch it early and I will ALWAYS admit that.. I watched it half at $14.00 and just saw the move happen the next few hours. Big calls on $DASH $COIN $QQQ tho. IF YOU MISSED THE ALERTS SEE MY BIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:25:58 </td>
   <td style="text-align:left;"> $AMD $spy  $qqq

https://www.theregister.com/2022/02/17/amd_doit_google/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:25:54 </td>
   <td style="text-align:left;"> $SPY $QQQ what’s better than an Alyeska power day?a day the mkt shits the bed and your puts pay bigly! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:25:52 </td>
   <td style="text-align:left;"> $QQQ retesting lows just in time for payday tomorrow? please go ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:25:32 </td>
   <td style="text-align:left;"> Any one has real idea why this bs drop ? FED already known about rate and inflation … so Russia said no war yesterday and now war ? Tomorrow again no ? Next day war ? 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:25:26 </td>
   <td style="text-align:left;"> $QQQ 
Moon now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:25:22 </td>
   <td style="text-align:left;"> $SPY  $QQQ $AAPL  
 
IF ITS IN THE NEWS, ITS IN THE STOCK.  
 
🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁YOURE WELCOME 🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:24:22 </td>
   <td style="text-align:left;"> $SPY $QQQ most leftists are incapable of thinking outside the official narrative propaganda so they&amp;#39;ll likely never know what it&amp;#39;s like to be silenced. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:22:17 </td>
   <td style="text-align:left;"> $QQQ we&amp;#39;ll see what the future brings - no idea. But  the present tells us quite some red flags (1) PPI, (2) CPI, (3) consumer dept, (4) margin debt, (5) 2nd economy collapsing right now, (6) 20st economy completely devastated, (7) main investors over past few months were retail and corporates  buy backs net outflow for institutions - except last few weeks (8) world&amp;#39;s supply chain a mess and will not recover before 2023 (9) interest rates rising leading and might lead to a real estate crash (10) inflation at historic levels (11) increasing geopolitical tension (12) liquidity scarcity (13) consumer confidence (14) lagging FED can only choose between crashing the economy or the markets - in other words &amp;#39;the trend is you friend until the end&amp;#39;..,I don&amp;#39;t know anything but I am not as optimistic as before...but yes one day there will be a new ATH for the QQQ for sure let&amp;#39;s make sure we both profit from that! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:22:13 </td>
   <td style="text-align:left;"> $QQQ I would say to put your money on movies because movie theater stocks are going to be doing really really good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:20:22 </td>
   <td style="text-align:left;"> $SPY $qqq I’d rather fight Putin than Covid. Stimulus for all NATO countries woopie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:17:25 </td>
   <td style="text-align:left;"> $SPY $QQQ The headlines tonight will be tensions easing between Ukraine and Russia, market soars tomorrow. We are all being played by the media and the politicians 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:17:10 </td>
   <td style="text-align:left;"> $SPY $AAPl $QQQ mass artillery planned for 0030 Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:16:28 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:16:06 </td>
   <td style="text-align:left;"> $QQQ Let&amp;#39;s see if we see a hammer tomorrow to shake out 92% retail. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:15:15 </td>
   <td style="text-align:left;"> $Qqq this could go down for years couldn’t it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-18 06:14:23 </td>
   <td style="text-align:left;"> $SPY $QQQ people wondering about @OldFngGuy and @sonicmerlin don&amp;#39;t realize how easy it is to be banned by ST. I&amp;#39;ll probably be banned by ST just for pointing this out. Old and Sonic were leftists which is the only reason they lasted as long as they did. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:46:32 </td>
   <td style="text-align:left;"> $AAPL Biden uses Iphone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:44:38 </td>
   <td style="text-align:left;"> U.S. SECRETARY OF STATE BLINKEN HAS ACCEPTED INVITATION TO MEET RUSSIA&amp;#39;S LAVROV LATE NEXT WEEK -STATE DEPARTMENT SPOKESMAN 
 
sorry but not sorry bears 😂 
 
$spy $qqq $sofi $tsla $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:43:33 </td>
   <td style="text-align:left;"> $AAPL Im never wrong ever! Thats what I tell myself! We rip tomorrow am after that no telling! Truth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:42:18 </td>
   <td style="text-align:left;"> $AAPL      🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:42:09 </td>
   <td style="text-align:left;"> $AAPL FYI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:41:31 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy: February 25, 2022 $170.00 Calls 
Entry Price: $2.27 - $2.29 
Exit Price: $3.02 
Stop Loss: $2.00 
Potential ROI: 33% 
Estimated Hold Time: 70 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:38:34 </td>
   <td style="text-align:left;"> $AAPL 

Date Brokerage Analyst Name Action Rating Price Target Upside/Downside on Report Date Details
2/17/2022 JPMorgan Chase &amp;amp; Co.
Subscribe to MarketBeat All Access for the recommendation accuracy rating Samik Chatterjee
Subscribe to MarketBeat All Access for the recommendation accuracy rating Set Price Target  $210.00 +24.35 

https://www.marketbeat.com/stocks/NASDAQ/AAPL/price-target/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:37:07 </td>
   <td style="text-align:left;"> $AAPL $SPY green in futures?! Feels like it’s been while even though it’ll likely be red by open if not sooner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:36:50 </td>
   <td style="text-align:left;"> $AAPL 171-172 tomorrow trust me! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:31:01 </td>
   <td style="text-align:left;"> $AAPL I got call $170 for January 2024 
$30 . I believe it’s all noise and market will be green soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:23:34 </td>
   <td style="text-align:left;"> $SPY Roku 🙀 $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:22:51 </td>
   <td style="text-align:left;"> $AAPL buying the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:21:41 </td>
   <td style="text-align:left;"> $AAPL laugh it off! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:21:31 </td>
   <td style="text-align:left;"> $AAPL $MSFT $AMZN Learn how these Price Action Patterns determine what your next trade plan should be…
Be sure to LIKE and SUBSCRIBE if you want ALL of our videos 💪

https://youtu.be/7NZ0OTdFvsE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:17:34 </td>
   <td style="text-align:left;"> $AAPL Still buying calls? 🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:14:08 </td>
   <td style="text-align:left;"> $MSFT $AAPL $WIMI What Does The Institutional Ownership Tell Us About WiMi Hologram Cloud? 
Institutional investors commonly compare their own returns to the returns of a commonly followed index. So they generally do consider buying larger companies that are included in the relevant benchmark index. 
WiMi Hologram Cloud already has institutions on the share registry. Indeed, they own a respectable stake in the company. This suggests some credibility amongst professional investors. Apple, Microsoft, Facebook build AR Cloud to take the lead,WiMi holographic AI vision 5G market bloom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:11:09 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG putin laughing at these lost Americans!! 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:10:45 </td>
   <td style="text-align:left;"> $AAPL …well Putin just punked Sleepy Joe making this idiot believing Russia was to invade Ukraine. Just on Foxnews! Hilarious! Lmao…$200 here we go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:04:55 </td>
   <td style="text-align:left;"> $AAPL Putin shorting the market makes sense huh? Ponder that! Genius </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:02:06 </td>
   <td style="text-align:left;"> $AAPL -  So Putin is eating popcorn and watching TV as the Dow drops 600 points a day - he’s got nothing but time on his hands. He can leave those tanks parked on the Ukrainian border for ever - the Cold War lasted 22 years. I think the markets are gonna have to get over this Ukrainian thing - it ain’t going away by next Tuesday and we can’t keep having days like today. Markets will collapse long before Putin runs out of Popcorn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:01:46 </td>
   <td style="text-align:left;"> $AAPL 🍏🏆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:01:36 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:01:18 </td>
   <td style="text-align:left;"> $AAPL Dont kid yourself...We green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 09:01:11 </td>
   <td style="text-align:left;"> $AAPL 🍏💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:59:59 </td>
   <td style="text-align:left;"> @NewsChartsVolume $aapl gap 162 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:59:39 </td>
   <td style="text-align:left;"> $AAPL it will hit the 🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:50:51 </td>
   <td style="text-align:left;"> $AAPL strength is really impressive, it’s as if it doesn’t realize what’s going on in the market lol… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:46:59 </td>
   <td style="text-align:left;"> $AAPL shorting this bloated pig as it’s high tmrw morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:43:15 </td>
   <td style="text-align:left;"> $SQQQ  $AAPL For a limited time,, we are opening our trading chatroom to the public  
 
most-profitable.optionsmarketmovers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:41:39 </td>
   <td style="text-align:left;"> $AAPL $MSFT $AMZN You WONT want to miss this episode!
Link below for access… Enjoy!

https://instagram.com/stories/optionsplayers/2775997634204072460?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:39:10 </td>
   <td style="text-align:left;"> $QQQ  $AAPL  #Any Thoughts  on 162 Tomorrow  $SPY  $ES_F  $NQ_F #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:37:02 </td>
   <td style="text-align:left;"> $SPY So if you&amp;#39;re sacred now how do you think WS is going to play tomorrow? Markets always fool the most &amp;amp; I think we&amp;#39;re way too Bearish but w/ teh media pushing the War narrative I don&amp;#39;t know what &amp;quot;smart money&amp;quot; is going to be Buying big into the wknd. 
 
$aapl $bb $amzn $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:34:21 </td>
   <td style="text-align:left;"> $TSLA  $spy $aapl $roku how is it that many MAJOR stocks crash 40% yet the media has zero reference to the market crashing...

Hmmmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:32:24 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMD puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:32:15 </td>
   <td style="text-align:left;"> $AAPL  📈 or 📉 to finish out the week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:30:06 </td>
   <td style="text-align:left;"> $AAPL please green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:28:16 </td>
   <td style="text-align:left;"> $DE $AAPL $PYPL $PT  
 
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $87,569 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 topgainer.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:25:18 </td>
   <td style="text-align:left;"> @GoodieGoodStockOptions 
Day trading Ranges every morning premarket 9am🤙🏾 news  @NewsChartsvolume 9am
We play ranges and market sentiment eryday $amzn $tsla $aapl. Simple as that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:23:46 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG you clowns still listening to some useless media channel that thinks they know anything 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:23:11 </td>
   <td style="text-align:left;"> $AAPL bloodbath tomorrow https://www.google.com/amp/s/www.cnbc.com/amp/2022/02/18/asia-markets-russia-ukraine-tensions-continue-to-rattle-investors.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:20:45 </td>
   <td style="text-align:left;"> If big momma rolls over….Look. Out. Below. $AAPL https://t.co/i22wvpOgdC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:20:01 </td>
   <td style="text-align:left;"> 📊 $AAPL 
🚀 94% Profitable 
🤖 AI-Driven Machine Learning 
🏆 SwingTradePro Strategy 
Join Our Premium Room For Live Trade Alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:18:21 </td>
   <td style="text-align:left;"> $ROKU $TSLA $AAPL nobody is gonna want to hold any stocks over the weekend with the looming fear of Russia/Ukraine. More selling tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:18:08 </td>
   <td style="text-align:left;"> $AAPL $SPY god help anyone who thought it was a good idea to go long into tomorrow.  Not to help their positions, but to help them survive in this world because they are top candidates for the Darwin awards. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:17:33 </td>
   <td style="text-align:left;"> $ES_F https://www.nytimes.com/2022/02/17/world/europe/ukraine-conflict-russia-military.html $SPY  $AAPL  #WhosKnow???  $ND_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:16:30 </td>
   <td style="text-align:left;"> $SPY When to short the last hold outs like $AAPL etc? Those will be the last to flush down with this market wipeout. Crazy how the giants are holding the indexes from collapsing while everything else is getting obliterated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:14:08 </td>
   <td style="text-align:left;"> $SPY $AAPL $PYPL puts doing a good job protecting my stock..... 
I can&amp;#39;t comprehend why everyone doesn&amp;#39;t just purchase the appropriate number of puts to protect their stock value in what seems to be an obvious crash!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:03:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL   after 2 weeks at ichimoku cloud top magnet resistance.. retested old flat white line. 26 day candle average line.. when it goes flat. that level is important.. and strong.. buyers have huge opportunity to bounce and breakout of cloud top.  sellers again will retest flat cloud bottom support again.. doesnt have to..  still favoring blow off top tacos.. (a break below ichimoku cloud changes that for near term) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 08:02:09 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #4 ticker with sweep activity where institutions are trading options urgently with 29.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:59:22 </td>
   <td style="text-align:left;"> $AAPL Hasn&amp;#39;t been hurt, barely touched so far. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:56:17 </td>
   <td style="text-align:left;"> $AAPL don&amp;#39;t be a hero, take your profit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:52:28 </td>
   <td style="text-align:left;"> $SPY $TQQQ $UVXY $AAPL   
 
Getting some after hours profits. Bought and sold $AMZN after hours for another profit on the day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:51:50 </td>
   <td style="text-align:left;"> $AAPL futes jumping!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:51:00 </td>
   <td style="text-align:left;"> $AAPL breaking news ! FB will be bankrupt ! Imho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:49:07 </td>
   <td style="text-align:left;"> $AAPL come on futes!  A big bounce on Friday is what all weekly call buyers dream of!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:46:14 </td>
   <td style="text-align:left;"> $AAPL      🍏 Wayyyy early…but, just putting it out there…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:45:36 </td>
   <td style="text-align:left;"> $AAPL Something about this screams $160 eod tomorrow, but my charts are saying $150 by next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:41:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  the Quadruple higher corndog pattern..   buyers have to get over 9 day candle average line( red). then white 26 day candle average line..  at etreme distance form cloud.. needs retest.   
 
will update the AAPL chart.. mentioned target was cloud top resistance.. it hit and sold off..  saw massive CALLS so looked primed for immediate breakout.. now needed a bounce off strong support to get over ichimoku cloud top resistance.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:41:02 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:38:31 </td>
   <td style="text-align:left;"> 2/17  RECAP

✅ $NVDA 230p 2/18 +32%

✅ $AAPL 160p 2/22 +60%

✅ $UVXY +5%

✅ $MYNZ +6% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:32:16 </td>
   <td style="text-align:left;"> Unusual Options Activity: $AAPL is the #25 ticker with unusual activity from institutional traders with an average of 19% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:27:23 </td>
   <td style="text-align:left;"> $AAPL Found a support right at the support line of the uptrend channel. Nice set-up for Next week 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:27:17 </td>
   <td style="text-align:left;"> Apple given $210.00 PT by JPMorgan Chase &amp;amp; Co.. https://www.marketbeat.com/r/1715553 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:26:48 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:26pm)

⦿ $AAPL is down 0.0% in the last 5 mins. 

⦿ There are 3 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 5.8% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:24:17 </td>
   <td style="text-align:left;"> $SPY ... $aapl is going to DESTROY everyone tomorrow. The blood of  the blue shirts will paint the malls red   &amp;gt;=) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:20:00 </td>
   <td style="text-align:left;"> $SPY $SPX $TSLA $AAPL $GME Does anyone else see 10000 coming? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:19:31 </td>
   <td style="text-align:left;"> $AAPL soo no artillery fire in Ukraine eh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:18:47 </td>
   <td style="text-align:left;"> $AAPL anyone retarded enough as me to short this pig ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:13:53 </td>
   <td style="text-align:left;"> $SPY $AAPL this market is simple .. tomorrow GAP UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:11:27 </td>
   <td style="text-align:left;"> $aapl i think this is god punishing me for laughing @ $pltr $roku $arkk $fb 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:11:13 </td>
   <td style="text-align:left;"> $ROKU BUYOUT COMING BUY NOW YOU WILL NEVER SEE THIS PRICE AGAIN $AAPL $NVDA $AMD $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:10:27 </td>
   <td style="text-align:left;"> $AAPL biden and cathie wood should join forces.   Itd be the stupidest power couple in the world to take on russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:10:14 </td>
   <td style="text-align:left;"> $arkk should buy $rblx $twtr $snap  $aapl!!! Stop loses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:08:05 </td>
   <td style="text-align:left;"> $AAPL I’m considering sharing 1-2 calls a day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:07:21 </td>
   <td style="text-align:left;"> $AAPL $164 soon inshallah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:07:02 </td>
   <td style="text-align:left;"> $AAPL blood in the water </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:06:00 </td>
   <td style="text-align:left;"> $AAPL  flat????   After a day like that??????  Wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 07:00:18 </td>
   <td style="text-align:left;"> $AAPL  futes up 1 pt!!!!   Yes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:57:49 </td>
   <td style="text-align:left;"> $AAPL 3 mins baby!!!!    Futes gonna rip.     No war!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:57:42 </td>
   <td style="text-align:left;"> $AAPL magnet at $129. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:55:59 </td>
   <td style="text-align:left;"> $IWM  Front -Load i.e.  1%=&amp;gt; .5%=&amp;gt; .25% =&amp;gt; .25% $AAPL 

Fed&amp;#39;s Bullard says inflation &amp;#39;could get out of control,&amp;#39; so action is needed now

https://www.cnbc.com/2022/02/17/feds-bullard-says-inflation-could-get-out-of-control-so-action-is-needed-now.html?__source=androidappshare </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:55:05 </td>
   <td style="text-align:left;"> $AAPL im going nuts waiting.   8k shares on margin.   Gonna sell if if pops </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:54:25 </td>
   <td style="text-align:left;"> $AAPL will futes be ripping!!!!    6 mins till countdown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:53:46 </td>
   <td style="text-align:left;"> $SPY man this market is just absolutely primed for scalpers!  
 
Had a nice short side scalp on SPY after that bear flag setup on the 5 min.  
 
Was watching $AAPL all day, as it was lagging the market. Went short as soon as it lost its bottom.  
 
Ill be watching both tmr and many other tickers with great scalping opportunities.  
 
Was thinking about holding Apple positions over night since I’m still bearish on but too risky. 
 
Good luck everyone get that 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:46:38 </td>
   <td style="text-align:left;"> Updated correlation matrix for Apple( $AAPL ),… https://www.macroaxis.com/invest/stock-correlation?s=AAPL,MKC,VMC,NWL,BDX,CB,SYK,LEG,SLM,TCBI,CNX,SRE #correlations #stocks #stockratings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:43:15 </td>
   <td style="text-align:left;"> $AAPL https://macdailynews.com/2022/02/17/zacks-upgrades-apple-stock-to-strong-buy/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:41:42 </td>
   <td style="text-align:left;"> $AAPL https://appleinsider.com/articles/22/02/17/january-iphone-shipments-much-higher-than-average-in-china-data-suggests </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:41:32 </td>
   <td style="text-align:left;"> $AAPL Ok so if China invaded Taiwan, goods will freely flow from mainland China to the US?  And chips will freely flow from Taiwan to US companies? OK. Apple will be a mushroom cloud. $QQQ $BABA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:41:28 </td>
   <td style="text-align:left;"> $SPY Just follow the big money... You&amp;#39;ll do much better when you trade with those who move the market
$QQQ $AAPL $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:39:26 </td>
   <td style="text-align:left;"> $AAPL  Hate to tell you guys but for the last 150-175 years,  markets frequently get to between 5 and 10 before the bear market reaches a bottom.  $amzn $msft $SHOP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:38:34 </td>
   <td style="text-align:left;"> $TSLA $AAPL $NVDA $GOOGL $FB - Why do you think there are so many subscriptions and alert services are there? Because it is REALLY hard to make money by trading! Anyone selling these services or posting youtube videos is the one who makes money LOL!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:38:19 </td>
   <td style="text-align:left;"> $AAPL  weekly.  still lot of room to 50 day.. blue line. thinking 150s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:37:39 </td>
   <td style="text-align:left;"> $AAPL tomorrow might be ugly. the market being closed on monday with the uncertainty of UKR is not ideal. except if you&amp;#39;re a bear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:37:29 </td>
   <td style="text-align:left;"> $GOOGL $GOOG $AAPL $NVDA  
 
Google&amp;#39;s stock split is perfect for investors 
 
https://utradea.com/blog/Googles-stock-split-is-perfect-for-investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:33:55 </td>
   <td style="text-align:left;"> $AAPL bears really think everyday is a crash opp dont they </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:33:49 </td>
   <td style="text-align:left;"> $SPY  $QQQ  $AAPL BUY FEAR. 🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁💝💝💝💝💝💝YOURE WELCOME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:30:11 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-17 Largest Trades Data: 
https://www.youtube.com/watch?v=DkIsD5GC68o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:28:48 </td>
   <td style="text-align:left;"> $AAPL #162  Ready to Fall Macd Cross  WhosKnow??? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:28:44 </td>
   <td style="text-align:left;"> $Aapl missed opps on 2x inverse H&amp;amp;S </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:28:23 </td>
   <td style="text-align:left;"> $AAPL Brandon letting Russ’s do whatever they want - trump would have had the guts to stand up to them .  Now the depression begins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:27:52 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $HOOD almost there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:25:22 </td>
   <td style="text-align:left;"> $SPY  $QQQ $AAPL  
 
IF ITS IN THE NEWS, ITS IN THE STOCK.  
 
🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁🎁YOURE WELCOME 🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:25:16 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Easy to spot them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:25:15 </td>
   <td style="text-align:left;"> $IWM  PT..168. 🤑🤑🤑🤑🤑 $AAPL  PT....154 GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:24:18 </td>
   <td style="text-align:left;"> $GOOGL $AAPL $AMZN $FB $NFLX They will probably oscillate these down to accumulate maximum profit before the flush. Wait for it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:22:54 </td>
   <td style="text-align:left;"> $AAPL maybe they want to keep oil prices up so they talk about the war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:17:10 </td>
   <td style="text-align:left;"> $SPY $AAPl $QQQ mass artillery planned for 0030 Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:14:20 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $DIS Behind the scenes footage of Spiderman 6.  MJ learns about the ugly side of Peters investments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:13:58 </td>
   <td style="text-align:left;"> $AAPL 160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:13:43 </td>
   <td style="text-align:left;"> $AAPL NEXT TIME YOU SEE AN ARBYS HAT PATTERN YOU WILL KNOW WHAT TO DO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:12:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL But the guy on youtube made 10,000 bucks in 30 minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:10:37 </td>
   <td style="text-align:left;"> Ever notice when you post on stock twits .. bots with fake accounts copy and paste on Twitter $aapl $spy $TSLA $SPX $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:09:15 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL The crew of the Enterprise never recovered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:08:00 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL If anyone needs a gut punch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:07:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL $WMT  
 
Ode To Hedging: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 06:04:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Punctuation matters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:58:40 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $170.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:57:31 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL  BTFD 🍎 🍎🍎🍎🍎🍎🍎🍎🍎🍎🍎🍎🍎🍎🍎🍎💝💝💝💝💝💝💝💝💝💝💝💝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:57:23 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple (AAPL) Stock: Why It Is Trending Today https://www.stck.pro/news/AAPL/23066751 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:56:57 </td>
   <td style="text-align:left;"> $SPY $goog $aapl all these had drops on huge volume in the last 15mins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:55:19 </td>
   <td style="text-align:left;"> $AAPL are we still talking about protecting money in overvalued companies or has the race to cash begun? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:51:18 </td>
   <td style="text-align:left;"> $AAPL at some point during this year, Wall Street will have to give apple a valuation content company between $175 to $265 billion for Apple TV content inventory, after they are able to shoot these new series and movies, without major COVID huddle. Built up valuable content and no rubbish contents. Adding to their Sum of Parts with higher margin between 67-76% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:48:15 </td>
   <td style="text-align:left;"> $AAPL https://appleinsider.com/articles/21/04/08/tom-holland-returning-to-apple-tv-in-the-crowded-room </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:47:35 </td>
   <td style="text-align:left;"> $SPY my puts weren’t looking so good early this week. I held my mud and didn’t sweat it. I have puts in $DIA Feb 25 $349 strike. I doubled my position today on Mar4 $AAPL $170 strikes today. I also hold some $3.50 strike puts in $WKHS . Altogether I have a good position. Haven’t sold a thing. Today was very good to me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:46:49 </td>
   <td style="text-align:left;"> $AAPL https://appleinsider.com/articles/22/02/17/amanda-seyfried-joins-apple-tv-anthology-series-the-crowded-room </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:46:32 </td>
   <td style="text-align:left;"> $AAPL regardless of what people want to think, their cash trove will lose value wherever they put it. It’s the only thing that has kept the stock outperforming of late…yes they can buy back shares, but there’s a point at which investors will see they are losing alpha regardless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:46:06 </td>
   <td style="text-align:left;"> $SPY $SPX $AAPL $TSLA Inflation, rate hike all are priced in. The fear of war is the last bad news for the bottom, smart bears already started to cover. You should know that the market is a roller coaster, when the institutions decide it will start to go up. Psychology plays an important role also. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:45:08 </td>
   <td style="text-align:left;"> $AAPL https://macdailynews.com/2022/02/17/apple-tv-reveals-teaser-video-for-the-problem-with-jon-stewart-premiering-weekly-starting-march-3rd/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:44:15 </td>
   <td style="text-align:left;"> $AAPL Biden and Putin working to cool inflation by first cooling the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:42:58 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Didn&amp;#39;t moo say that if she was banned she would become more powerful than ever before!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:42:16 </td>
   <td style="text-align:left;"> $NIO $AAPL $TSLA https://youtu.be/Ng-HE9Chq4I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:41:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMD $NVDA The real false flag is being rolled out by our own media and political establishment.  I’m not a conspiracy theorist, but we all know Putin is watching this all laughing that he can crash the US market with just the threat of invasion.  We are basically telling him he has all the power, if he invaded, we would be at his every whim as far as negotiations were concerned-our markets would take another hit, they have energy and semi conductor production raw materials on lockdown.  But no, Putin isn’t taking the bait—but man does this feel like a media false flag egging him on and giving him every reason to be the bad guy.  Weird times we are in, is it 2024 yet?  🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:39:47 </td>
   <td style="text-align:left;"> $AAPL damn people still so bullish here. This is funny. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:38:38 </td>
   <td style="text-align:left;"> $AAPL puts signal paid 🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:38:34 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Holding about 85 UNO cards at this point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:37:02 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Just don&amp;#39;t answer the phone for the rest of the week.  #Protip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:36:01 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 260.3K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:33:50 </td>
   <td style="text-align:left;"> $AAPL this is the last one left. Indexes are weighted heavily and held up by Apple. If she goes, then start buying cans of tuna </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:33:50 </td>
   <td style="text-align:left;"> $ROKU Wasn&amp;#39;t a bad  quarter or year.  Great growth and expansion. Roku channel doing great too. I got a put to hedge but this was actually a good report and year. It will prob sell off bc of the environment but solid company wiht  great growth. $spy $aapl $amzn $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:32:56 </td>
   <td style="text-align:left;"> $AAPL Let’s go 159 tomorrow. Here’s some fear porn YouTube recommended the other day..  $GOOG … enjoy! 
 
 https://youtu.be/bluUxKIB4pA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:31:42 </td>
   <td style="text-align:left;"> $AAPL  you bulls do understand this market is tanking because of inflation and our sluggish economy and not Ukraine, right ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:30:06 </td>
   <td style="text-align:left;"> $AMPL $GOOG $AAPL $MSFT $FB  Ukraine economy is much less the destruction happening in market .. fk You politks, leaders and manipulators !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:28:21 </td>
   <td style="text-align:left;"> $AAPL everyone is getting whacked….you’re next, me thinks. 🔪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:27:00 </td>
   <td style="text-align:left;"> $AAPL, $MA and $ALSN showing up in our technical breakout setup screen. https://www.chartmill.com/stock/stock-screener?sid=202&amp;amp;f=v1_50b500,atrpct_a_1,sl_ta_7_X,sl_se_7_X,p_pg20,exch_us&amp;amp;s=se&amp;amp;v=3&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_Technical_Breakout_Setups&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:25:42 </td>
   <td style="text-align:left;"> Looking At Apple’s Recent Whale Trades  $AAPL https://www.billionaireclubcollc.com/looking-at-apples-recent-whale-trades/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:25:00 </td>
   <td style="text-align:left;"> $AAPL CNBC will regain their credibility when they issue a corporate memorandum that requires them to lynch Jim Cramer from the nearest lamp post.  In the mean time, be prepared to be screwed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:21:11 </td>
   <td style="text-align:left;"> $AAPL serious question….if China invaded Taiwan where would apple close that day?   I would say down 35% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:11:59 </td>
   <td style="text-align:left;"> $AAPL 5% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:11:05 </td>
   <td style="text-align:left;"> $AAPL $SPY …errr….ya’ll know the market gonna crash tomorrow right? Unless Biden shoots a rainbow out of his ass and organizes a bbq (family and friends invited) with all the eastern block  leaders, there is no goddamn way PMs won’t trim heading into a long weekend. And every 401k and pension manager will do the same. Because we have too much to lose now. This is how bubbles burst. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:09:57 </td>
   <td style="text-align:left;"> $WFC … $AAPL truck 🛻 loads of buy !!!!
Yugreeeeede </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:07:29 </td>
   <td style="text-align:left;"> $AAPL what happens post a sell of on below average volumes? Not everyone participated in this sell off. set up for a squeeze. is this the final fuel they needed to break the 176 resistance? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:06:34 </td>
   <td style="text-align:left;"> $AAPL share your call options 💚 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:04:57 </td>
   <td style="text-align:left;"> $AAPL $$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:03:52 </td>
   <td style="text-align:left;"> 992.9k $AAPL @ 168.88 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:03:25 </td>
   <td style="text-align:left;"> $AAPL    🍏!  👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:03:18 </td>
   <td style="text-align:left;"> $AMZN $GOOG $NVDA $AAPL $NVDA WTF is with this Brandon guy??? 

Why is he creating more fears by warmongering? Distract Americans from real issues like inflation and worst economic policies? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:02:52 </td>
   <td style="text-align:left;"> $AAPL https://www.bbc.com/news/business-60403548 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:01:29 </td>
   <td style="text-align:left;"> $AAPL ngl i am upset. was up $3k before this BS. Closed the day at fucking 10 dollars down SMH. But worry not, tomorrow will be up double that! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:01:07 </td>
   <td style="text-align:left;"> 02/17/22  Today’s day 7 of the Small Account Challenge Results. +$190 Feel free to follow along.  
 
$DIS  $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:00:33 </td>
   <td style="text-align:left;"> $AAPL  
Old dog Biden is using Russia to spook the market so that he could buy it really low, don&amp;#39;t fall for his trap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:00:22 </td>
   <td style="text-align:left;"> Invest with an outcome based approach on $AAPL. Accelerate gains by 2.0x and make up to 25.9% (23.8% annualized) on $AAPL through 03/17/2023.

Buy 2 $175 calls
Sell 2 $195 calls
Sell 1 $175 put
 3/17/23 expiration
https://o.oliveinvest.com/e2nj6m </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 05:00:15 </td>
   <td style="text-align:left;"> $AAPL strong company. Only buy monthly calls. Tune out the bear noise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:59:23 </td>
   <td style="text-align:left;"> $AAPL I think this goes to 185 to make me feel like an idiot for not buying and pumping bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:59:19 </td>
   <td style="text-align:left;"> $aapl hehe, first they get  google to remove the dislike counter on Youtube, and now nothing against Demonrats on this platform? Cant wait for $dwac &amp;#39;s version of stocktwits.. SHEESH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:59:13 </td>
   <td style="text-align:left;"> $AAPL doesn’t know what direction it wants to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:59:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Call buyers today LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:57:20 </td>
   <td style="text-align:left;"> $AAPL …. Get used to this shit economy, liberals. You voted for it. I hope you weren’t planning to retire anytime soon. It’s not like we didn’t warn you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:56:33 </td>
   <td style="text-align:left;"> $AAPL ”Hi Tim?…..This is Warren Buffet….Just a quick question…how long would it take to completely in-house Apple manufacturing and do it in the US?….oh…it’s impossible? ok Thanks”.  “SELLL IT ALLLLLLLLL” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:56:14 </td>
   <td style="text-align:left;"> $AAPL BIDENS ECONOMY. Get used to it. Libtards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:55:34 </td>
   <td style="text-align:left;"> $AAPL bought some calls for overnight with that knee jerk dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:54:42 </td>
   <td style="text-align:left;"> $AAPL BEARS! QUICK! Buy $170 Puts expiring tomorrow!!! URGENT!! DO IT !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:54:38 </td>
   <td style="text-align:left;"> $AAPL this is one of those 5 minutes huge red and 5 minutes huge green to close her out things, huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:54:37 </td>
   <td style="text-align:left;"> $AAPL appears to be some selling out there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:54:31 </td>
   <td style="text-align:left;"> $AAPL STANDING HERE, I REALIZE THAT YOU WERE JUST LIKE ME TRYING TO MAKE HISTORYYYY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:54:14 </td>
   <td style="text-align:left;"> $AAPL bye calls! hahahahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:54:10 </td>
   <td style="text-align:left;"> $AAPL still looking overpriced af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:54:09 </td>
   <td style="text-align:left;"> $AAPL what’s going on in the market today. I’m out of the loop being at work </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:53:09 </td>
   <td style="text-align:left;"> $AAPL oooo my yeeeesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:52:54 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:52:47 </td>
   <td style="text-align:left;"> $AAPL someone&amp;#39;s got a trigger finger! hahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:52:15 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:52:13 </td>
   <td style="text-align:left;"> $AAPL oh now there’s the panic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:52:10 </td>
   <td style="text-align:left;"> $AAPL 165 puts Yolo? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:52:08 </td>
   <td style="text-align:left;"> The F1 viewership numbers for 2021 are wild.

$AMD ↗️ Sponsors a vehicle 
💰🥇🏁 🏎💨….. $INTC 

The total TV audience was 1.55 billion &amp;amp; they averaged over 70 million viewers per Grand Prix.

But nearly 450 million people watched at least one race.

That&amp;#39;s the size of the United States, Canada, Spain, and Australia...combined.

$AAPL $NVDA $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:52:05 </td>
   <td style="text-align:left;"> $AAPL omg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:51:19 </td>
   <td style="text-align:left;"> $AAPL wow huge 3.69M on the sell imbalances </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:50:47 </td>
   <td style="text-align:left;"> $AAPL uh oh! getting pinned down! hahahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:50:41 </td>
   <td style="text-align:left;"> $AAPL oh shit that was violent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:50:36 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:50:14 </td>
   <td style="text-align:left;"> $AAPL just go up $2 tomorrow lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:50:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $VIX $AAPL 
 
Bears buying the war-mongering rhetoric that is being pushed, to drive gold/oil prices and Putin finds it hysterical. Bears are making putin rich. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:49:20 </td>
   <td style="text-align:left;"> $SPY $AAPL manipulation at its best. So much darkpool trading and major orders gonna sell in the last 10 min. This is just a dead cat bounce to give them the best bang for their buck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:47:50 </td>
   <td style="text-align:left;"> $AAPL as predicted. Thursday and Fridays. Red on expectation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:47:41 </td>
   <td style="text-align:left;"> $AAPL Wow when retailers lose money the MEDIA say they&amp;#39;re Gambling, when Corporations lose money the media claim retailers are  SHORTING..$FB $GOOG $AMZN $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:47:14 </td>
   <td style="text-align:left;"> I should’ve jumped on those $AAPL puts today been holding off lost track of the chart today 😴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:45:55 </td>
   <td style="text-align:left;"> $AAPL This war is total BS. Crack -addict Hunter and the big guy sold us out. This is the result. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:45:32 </td>
   <td style="text-align:left;"> $AAPL Shorting the pops, like I did with ARK.  Wouldn&amp;#39;t be surprised to see this bloat trading sub 100 in a year, bear markets are magical mean reversion mechanisms </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:43:40 </td>
   <td style="text-align:left;"> $AAPL Headed back $120.   https://www.cnn.com/2022/02/17/investing/apple-tim-cook-compensation/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:42:48 </td>
   <td style="text-align:left;"> $GOOG how does war badly affect Google? … wouldn’t that make MORE people search google for news? More eye balls = more revenue ….

Buying this dip.. thank you for the shares 
💰 

🚨 $AAPL $TSLA $FB $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:42:45 </td>
   <td style="text-align:left;"> $AAPL this is the only stock that didn’t drop much with markets crashing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:41:45 </td>
   <td style="text-align:left;"> $FB What I want to know is why $AAPL is untouchable in this market.  Now I think they &amp;amp; $GOOGL need breaking up!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:40:58 </td>
   <td style="text-align:left;"> $AAPL I got one more day before my call expires. 
 
Pull a Hail Mary. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:40:52 </td>
   <td style="text-align:left;"> $AAPL $176 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:40:28 </td>
   <td style="text-align:left;"> $AAPL  🍏 Today:  Mkt/WallSt Games, on “Pre-War Jitters”.  When Mkt Indices move lower in sync in “anticipation” of an Event, Traders/Investors “know” why, &amp;amp; who benefits.  On a Day like today…longtime Traders/Investors of AAPL also know, that this movement does not effect AAPL’s Strength or its position as the Mkt leader.  Today’s trade action:  AAPL is merely an “Algo tool”, used to channel the Mkt’s desire.  At the moment, the Mkt’s mood is a manufactured “gloomy”.  “Gloomy”, is an emotional evocation.  Mkt’s, always survive   “gloomy” reactions.  So tonight, pray that Russia chooses peace over war.  And that in the Days to come, should Russia chose the to the contrary, know that as relates to the Mkt…”History” is on the side of the Mkt Investor.  America, always rallies in the face of Millitary Conflict &amp;amp; Restoration. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:40:12 </td>
   <td style="text-align:left;"> Russia invasion is always &amp;quot;days away&amp;quot; 
 
Putin makes billions when oil &amp;amp; gas are this elevated. 
 
Its all bullshit.  Putin playing everybody. 
 
$spy $aapl $nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:39:12 </td>
   <td style="text-align:left;"> $AAPL $10 coming? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:38:30 </td>
   <td style="text-align:left;"> $AAPL 150 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:38:08 </td>
   <td style="text-align:left;"> $SOFI Why you never go all in. I’m just waiting on $AAPL to touch 150 and $AMD 100. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:36:48 </td>
   <td style="text-align:left;"> $AAPL 300 shares in 1987 is now 72,000
Go figure why smart folks buy everyday no matter the price! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:36:15 </td>
   <td style="text-align:left;"> $FB Big blow from $AAPL and now huge blow from $GOOG …… major hit to their ad business… not sure if they can come back from This… the Metaverse will have to save them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:35:30 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:34:19 </td>
   <td style="text-align:left;"> $Sq $AAPL $msft $NVDA  you ever heard of The never ending story? That&amp;#39;s what this market is. The never ending excuse to sell. Reason after reason to just bring the market lower. #wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:33:56 </td>
   <td style="text-align:left;"> $AAPL What do you do when you wake up one morning, kiss your boyfriend, and realize that you based the entire operating model of the company Steve Jobs trusted you with on an unsustainable geopolitical offshoring model without a backup plan? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:33:36 </td>
   <td style="text-align:left;"> $AAPL somehow people really think that aapl can sit on top of a pile of burning garbage without falling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:33:20 </td>
   <td style="text-align:left;"> $QQQ $aapl $msft $tsla any puts now is working in this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:33:02 </td>
   <td style="text-align:left;"> $SQ $TSLA $SOFI $UPST $AAPL  
Are we in the brink of WW3? Russia keeps boosting the amount of troops.. even president Biden said it was a high likely hood. How many people would die in the transition?  
Will england declare war and it basically be everyone vs russia and china? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:32:06 </td>
   <td style="text-align:left;"> $AAPL $SPY dead cat bounce. Please and thank you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:32:04 </td>
   <td style="text-align:left;"> $AAPL 8 Trades executed, trade Profitability of 75% and Profit Factor of 7. https://pbs.twimg.com/media/FLxvwAjXwAAavQx.jpg? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:30:17 </td>
   <td style="text-align:left;"> $AAPL let’s run this back to VWAP!  That’s $170.72 JIC you didn’t know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:29:45 </td>
   <td style="text-align:left;"> $AAPL vix has peyronies from the booster. FYI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:28:35 </td>
   <td style="text-align:left;"> $UVXY $SPY $AAPL $MSFT $ARKK  This is what idiocy looks like. Glad her fund tanked even more after that comment. Pride comes before the fall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:28:27 </td>
   <td style="text-align:left;"> $AAPL Changed my next buy target to 155 to add some more shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:27:17 </td>
   <td style="text-align:left;"> $AAPL We rally tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:25:42 </td>
   <td style="text-align:left;"> $AAPL desperation buys right now, bad news for aapl bulls tomorrow and Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:24:40 </td>
   <td style="text-align:left;"> $AAPL buy the dip! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:24:26 </td>
   <td style="text-align:left;"> $AAPL a quick slide to 140&amp;#39;s may create some fear we need for a short term bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:22:50 </td>
   <td style="text-align:left;"> $MSFT $AAPL These still have barely corrected compared to rest of the market. Big drops coming here before market can move forward </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:22:19 </td>
   <td style="text-align:left;"> $ZS $CRWD  $STNE  Perma 🐂  everything will be 80%-90% discount from their ATH in 2022. The only exceptions in tech are cash cows that can buy significant portions of their shares without flinching $MSFT  $$AAPL safe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:22:17 </td>
   <td style="text-align:left;"> $AMD does not want to go below 113.20 wow. Reminds me of $AAPL a buffer for the ETF 
If we don’t close above 114.30 or 115.50 still bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:22:09 </td>
   <td style="text-align:left;"> $AAPL LETS GO 🔥🔥🔥🔥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:20:41 </td>
   <td style="text-align:left;"> okay out for now $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:19:31 </td>
   <td style="text-align:left;"> $AAPL where is the bump? Wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:19:19 </td>
   <td style="text-align:left;"> $AAPL When the covid scam no longer works, they push the “fake” war news…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:17:20 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m buying 20 shares here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:17:17 </td>
   <td style="text-align:left;"> $AAPL A good communist would nationalize the means of production.  🇨🇳 you help the Chinese worker and hurt the capitalist dogs $SPY $TSM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:16:20 </td>
   <td style="text-align:left;"> $AAPL especially horrible conditions for aapl atm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:16:19 </td>
   <td style="text-align:left;"> $AAPL thank you for flying lord quas airlines. We apologize for the brief detour taken to 172. That was a bullshit pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:13:26 </td>
   <td style="text-align:left;"> $AAPL  tomorrow.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:13:22 </td>
   <td style="text-align:left;"> $AAPL Fuck Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:12:46 </td>
   <td style="text-align:left;"> $SPY again... Mark this post... At or below 400 by the end of March. $QQQ $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:12:10 </td>
   <td style="text-align:left;"> $AAPL Putin to Xie…”How about I take Ukraine on the 20th and you take Taiwan on the same day? We both get political wins at home and the US can’t fight us both at the same time”. $MSFT $TSM $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:11:56 </td>
   <td style="text-align:left;"> $AAPL buying some share right here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:11:47 </td>
   <td style="text-align:left;"> $AAPL biden making America shit again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:10:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL look like there will really be a war, eve the MMs can smell it  so that&amp;#39;s why theyre  selling.. hmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:10:19 </td>
   <td style="text-align:left;"> $AAPL who&amp;#39;s buying now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:09:46 </td>
   <td style="text-align:left;"> $AAPL opened csp $162.5 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:08:13 </td>
   <td style="text-align:left;"> $SPY the only thing working right now is $GOLD 🪙🪙🪙🪙

join the party $TSLA $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:07:52 </td>
   <td style="text-align:left;"> $AAPL 02.08 chart presented to members. The stock has given us nice reaction from the blue box. Long positions are risk free ( SL put at BE) and partial profit has been taken.      #elliottwave #trading #stocks #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:07:52 </td>
   <td style="text-align:left;"> $AAPL another day signaling a healthy market and a great opportunity to buy.  I don&amp;#39;t see blood in the streets, I just see piles of Bullsh1t. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:07:21 </td>
   <td style="text-align:left;"> $AAPL 01/19 chart presented to members. We were buying the dips at 162.1-152.8 area. #elliottwave #trading #stocks #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:07:00 </td>
   <td style="text-align:left;"> $AAPL imagine buying 169, what an obtuse number </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:06:36 </td>
   <td style="text-align:left;"> We have identified an unusual $AAPL block that expires on March 18, 2022 with a strike price of $135.00.

15,000 PUT contracts with a price of $0.40 (Ask) were purchased at a $600,000 premium. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:05:38 </td>
   <td style="text-align:left;"> $PLTR 
Maybe I’ll just buy $AAPL like everyone else.  This company is $HIT! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:05:16 </td>
   <td style="text-align:left;"> $MSFT $AAPL $AMZN   I still see a lot of overvaluation for many fancy names. These names have to come down on Earth, specially with NORMAL NOT MANIPULATED RATES. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:05:07 </td>
   <td style="text-align:left;"> $spy It&amp;#39;s all over now. $aapl cracked. Go home little $$$ bull. Come back next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:04:10 </td>
   <td style="text-align:left;"> $SPY Finally $aapl   &amp;gt;=) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 04:03:36 </td>
   <td style="text-align:left;"> $QQQ latex2da578fbb456505145e5b7f150aef53cT
$DISCA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:59:56 </td>
   <td style="text-align:left;"> $AAPL This is my only life vest! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:59:10 </td>
   <td style="text-align:left;"> $AAPL just remember, the most intelligent &amp;amp; creative people buy MacBooks. Apple can’t sell them fast enough. Everyone else is just lower middle class or ignorant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:56:46 </td>
   <td style="text-align:left;"> $AAPL The more people cling on to this, the longer the sideways trading range. We all know this is touching 200 dma at 151 by march </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:54:17 </td>
   <td style="text-align:left;"> $AAPL watch nothing will happen with Ukraine except a lot of bears will get crushed here! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:52:42 </td>
   <td style="text-align:left;"> $AAPL vanguard and buffet adding to their positions and there are still bears… smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:52:27 </td>
   <td style="text-align:left;"> $SPY $AMC $GME $AAPL $TLT memes are going to run soon...apple to $90 and spy tanking. I’ll turn bullish in the market overall after amc is done with the squeeze🚀🤝💰🇺🇸🏄‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:52:18 </td>
   <td style="text-align:left;"> $AAPL I didn&amp;#39;t know that U.S Stock market and all these companies were tied up with Russia and Ukraine. Just another BS reason for some magical insider trading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:51:00 </td>
   <td style="text-align:left;"> $AAPL, $TSLA, $FB, $PLTR: Why Are Stocks Crashing Today? https://investorplace.com/2022/02/aapl-tsla-fb-pltr-why-are-stocks-crashing-today/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:49:59 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:49:27 </td>
   <td style="text-align:left;"> $AAPL bought next weeks $172.50 calls at $1.24 for scalp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:48:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL this is clear controlled selling and very bearish. God speed longs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:47:21 </td>
   <td style="text-align:left;"> $AAPL $90 will come, give it time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:46:52 </td>
   <td style="text-align:left;"> $AAPL 2.7% total loss today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:46:19 </td>
   <td style="text-align:left;"> $spy ... $aapl Just a little more... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:46:15 </td>
   <td style="text-align:left;"> $SPY Lets see the MOC Orders &amp;amp; if they are just PMs running for the door. 
 
Low Bids for Options is how I play that so low bids in for $baba $aapl $bb $jpm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:45:55 </td>
   <td style="text-align:left;"> $AAPL Ongoing manipulation, any excuse is good to bring down the markets with these algos controlled by CROOKS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:45:42 </td>
   <td style="text-align:left;"> $SPY but def what you want to see as a bear. $QQQ $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:45:40 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $AMZN   what up 👊🏻

https://music.amazon.com/albums/B005GSXTOA?do=play&amp;amp;trackAsin=B005GSXU1M&amp;amp;ref=dm_sh_rwVoTh77wgYipImJPZ2RVlvKz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:44:21 </td>
   <td style="text-align:left;"> Just want to point out that $MSFT and $AAPL which make up a sizable portion of the $QQQ and are two of the most widely owned names have not materially sold off yet. Exercise caution... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:44:16 </td>
   <td style="text-align:left;"> $AAPL Why are the Chinese just letting Americans get rich off of Chinese labor?  Will it last? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:44:04 </td>
   <td style="text-align:left;"> $SPY 3/18 419P MASSIVE sweepers  $10M+ $tsla $amzn $AAPL $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:43:57 </td>
   <td style="text-align:left;"> $AAPL  
 
Thrilled to see it&amp;#39;s crashing, my puts I accumulated for couple week finally started printing. 
 
$AAPL hided the much slower revenue growth in 2022, misled the public! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:42:42 </td>
   <td style="text-align:left;"> $AAPL Where would apple trade if China decided to nationalize the means of production across the board?  They already 1) shut down for profit education, 2) shut down $BABA and other huge tech companies 3) invaded Hong Hong 4) enslaved minorities.  Why not just take Foxconn cut the price of iPhones and sell only to Chinese.  Plus, keep all profits that remain and distribute to the masses.  $BABA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:40:40 </td>
   <td style="text-align:left;"> $AAPL buy buy buy 
divies. shares. all u need. buy buy buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:40:12 </td>
   <td style="text-align:left;"> $AAPL $165 March puts printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:39:51 </td>
   <td style="text-align:left;"> $AAPL $150 to start… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:39:45 </td>
   <td style="text-align:left;"> $AAPL is apple filling gaps at 168? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:39:26 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : BofA Analyst Is Bullish On Apple - See Why https://www.stck.pro/news/AAPL/23061846 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:39:19 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL) – BofA Analyst Is Bullish On Apple – See Why https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-bofa-analyst-is-bullish-on-apple-see-why/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:39:05 </td>
   <td style="text-align:left;"> $IWM 🤑🤑🤑🤑🤑🤑 $AAPL  shout out to all the m************ intuitive traders !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:38:58 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:38:56 </td>
   <td style="text-align:left;"> $AAPL oof </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:38:17 </td>
   <td style="text-align:left;"> $SPY $AAPL Exceptionally dumpy today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:38:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $TSLA $AAPL  
 
Don&amp;#39;t worry bulls, just another 15% haircut and we&amp;#39;re half way to fair market value! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:37:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL looks like an abandoned baby forming! don&amp;#39;t worry, daddy puts-tin won&amp;#39;t abandon you! hahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:37:32 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMZN $MSFT $FB big tech is going under like everyone else this is just the beginning. Blame Biden his base, whomever but the market is FUKD. All these tickers about to get Zucked and Shopified. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:37:27 </td>
   <td style="text-align:left;"> $AAPL absolutely no volume here. Why? Because it shouldn’t be dropping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:37:20 </td>
   <td style="text-align:left;"> $MSFT $AAPL $AMZN $GOOGL next week is the time for these piggies, and then market is back to normal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:37:20 </td>
   <td style="text-align:left;"> $AAPL make sure you guys buy this gap fill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:37:08 </td>
   <td style="text-align:left;"> $AAPL BofA Analyst Is Bullish On Apple - See Why 

https://newsfilter.io/a/4aa85142a1badd84a7673c4699aa58ad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:36:12 </td>
   <td style="text-align:left;"> shame on $MSFT and $AAPL, we have the best of the $AXP .. unscratched during all the turbulence for the past 1 month… 💪💪💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-18 03:35:34 </td>
   <td style="text-align:left;"> $AAPL I can’t believe this is dropping yo be honest with you. What’s not to like? PE of 28 is definitely acceptable. I can’t believe buyers are not knocking down the door to buy shares. It’s almost more of a value company than a growth company now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:49:09 </td>
   <td style="text-align:left;"> $NWBO is the $TSLA of cancer treatment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:47:24 </td>
   <td style="text-align:left;"> $TSLA $SPY whats the news? ‘Futes rippin’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:45:35 </td>
   <td style="text-align:left;"> $BA $TSLA $AMZN $UVXY $SARK Just here to remind everyone one to short the spikes … that is all … okay bye ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:44:38 </td>
   <td style="text-align:left;"> U.S. SECRETARY OF STATE BLINKEN HAS ACCEPTED INVITATION TO MEET RUSSIA&amp;#39;S LAVROV LATE NEXT WEEK -STATE DEPARTMENT SPOKESMAN 
 
sorry but not sorry bears 😂 
 
$spy $qqq $sofi $tsla $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:44:37 </td>
   <td style="text-align:left;"> $TSLA tomorrow green day ..🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:44:31 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE  🔥 
🎯LOTTO FRIDAY PICK LIST 
IM GOING TO BREAK DOWN 👇 
📈TRADE IDEAS  
🔫TRIGGERS  
🎯TARGETS  
CLICK 👉 https://us02web.zoom.us/j/85366560330  $SPY  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:42:06 </td>
   <td style="text-align:left;"> $TSLA FUTIES ARE RIPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:40:40 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA Choppy day in the markets. Pretty much everything was red today, except for a few runners.  Depends on your time horizon, but I see this as a long-term hold. So just remember to keep that in perspective. 
  
Investing is hard, but it shouldn’t be. We built this platform to provide personalized and actionable investment ideas and insights through artificial intelligence and a community of investors. Join the future of intelligent investing. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_202202017 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:37:48 </td>
   <td style="text-align:left;"> $TSLA worth more than .77 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:37:13 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!!

U.S. ACCEPTS TALKS WITH RUSSIA&amp;#39;S LAVROV NEXT WEEK

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:34:15 </td>
   <td style="text-align:left;"> $SKLZ kick Cathie out of this. She’s a day trader and not a long term investor. Tesla was her top best pick that carried her profile while everything else is going to shit in the short term $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:32:24 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-17 Options Analysis Video: 
https://www.youtube.com/watch?v=8NvpsUK_LMg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:32:07 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s open up -30 tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:31:09 </td>
   <td style="text-align:left;"> $TSLA futs looking lovely!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:30:48 </td>
   <td style="text-align:left;"> latex1b7c5f3be1a1ec8d35db7640e2f5f097NRGV Long 1pt
$LFLY Long +.80

L </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:24:33 </td>
   <td style="text-align:left;"> $TSLA Can someone tell Putin to chill. I&amp;#39;m trying to make some money here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:24:10 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:24:09 </td>
   <td style="text-align:left;"> $TSLA The support broke today. Looks like we are going back to the 850s and hopefully that resistance line holds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:23:04 </td>
   <td style="text-align:left;"> $TSLA The ONLY bull case here is that the U.S. government has an interest in Tesla pushing through so that America can dominate the EV sector and diversify away from tech. Tesla is in a strong position to do so but is headed by a clown CEO that throws audacious claims. &amp;quot;million robotaxis by 2019&amp;quot; loool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:22:58 </td>
   <td style="text-align:left;"> $TSLA 568 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:20:26 </td>
   <td style="text-align:left;"> $TSLA It literally only ran up because of Cathie Wood&amp;#39;s ambitious price target. She then raised the target and the market followed because they thought she had a crystal ball. All funds and stocks eventually revert to the mean. Just buy the haystack.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:20:22 </td>
   <td style="text-align:left;"> $TSLA everyone gets mad when you say something is guaranteed in this market like the market gods will punish you for saying it 😂😂😂 WELL HERE IS MY GUARENTEE that the markets WILL obey:

This will dump far more than it has already AND will guaranteed NEVER see over $1,200 again this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:20:20 </td>
   <td style="text-align:left;"> $TSLA all I know is that when everything feels like it can’t get much worse, that’s peak fear.  Nividia and Palantir reported incredible earnings and guidance, and both tanked. It might take a few months, but after March 15-16 FED meeting is when I’d say we start to rise.   Tesla will report Q1 numbers April 2nd and could be 330-340 k vehicles. Stay hopeful friends!!  It’s always darkest before the dawn! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:19:17 </td>
   <td style="text-align:left;"> $TSLA say goodbye to this overvalued stock... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:19:01 </td>
   <td style="text-align:left;"> $TSLA fund managers lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:19:01 </td>
   <td style="text-align:left;"> $TSLA Don&amp;#39;t you love how all the clickbait fukw1ts on days like today like to come up with articles with specific reasons why a company is down when the ONLY reason anything is down today is macro... aka the market is full of retards! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:18:06 </td>
   <td style="text-align:left;"> Arkk loading more $TSLA $PATH $TXG $TER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:16:42 </td>
   <td style="text-align:left;"> $XELA 

3)
Par warned Shorts (see twit of Feb 15th👇🏼)

Par Chadha@par_chadha
43M+ $XELA shares borrowed by shorts; cost to borrow up 15x YTD (source: ORTEX). IMO huge risk to bet against the house with 90k+ shareholders. Reminds me of early days when shorts loved $TSLA for its debt etc.

4)
Exela is in much better situation than in Feb 2021, bc it reduced 454mio of dept! 
In Feb we were around $7.8
- almost daily contract
- 17k employees 
- know how in many area (see web site)

For the above reasons, I think $30 is possible this year (= 4000%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:16:00 </td>
   <td style="text-align:left;"> $ARKK So all of her magical stocks ran to the sky but turned out to be turds? Just $TSLA left now. It&amp;#39;ll fall to 150-300 eventually. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:15:42 </td>
   <td style="text-align:left;"> $TSLA it really seems like tesla is under attack from all sides right now, can&amp;#39;t catch a break with germany purposely screwing him and getting crushed by our own government. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:12:34 </td>
   <td style="text-align:left;"> $TSLA I advise everyone to read Elon&amp;#39;s letter filed with the federal court recently. It sounds like the guy is in a boat load of trouble with the SEC and he is desperate.  I think criminal charges are coming in the near future.  If he is charged, he will be removed as CEO of Tesla and the government is likely to rescind its contracts with SpaceX. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:12:07 </td>
   <td style="text-align:left;"> $TSLA overreaction as usual 
Got some </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:11:55 </td>
   <td style="text-align:left;"> $TSLA a part of all this market downtrend has to be the big boys trying to get rid of all the newbies who started trading during Covid and don’t know how to handle seeing their money go down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:11:22 </td>
   <td style="text-align:left;"> $TSLA 800 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:11:05 </td>
   <td style="text-align:left;"> $TSLA yeah it’s probably time to share this again just in case! Going to be a disgusting day tomorrow too so remember that money isn’t everything bulls and you have so many people in your life that still care about you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:06:38 </td>
   <td style="text-align:left;"> $TSLA bulls on suicide watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:06:33 </td>
   <td style="text-align:left;"> $TSLA where’s all the 1200 bag holders? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:03:46 </td>
   <td style="text-align:left;"> $ARKK Last one to fumble would be $TSLA  and that would get this under 50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:03:21 </td>
   <td style="text-align:left;"> $TSLA just wait until this actually starts selling off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:03:13 </td>
   <td style="text-align:left;"> $TSLA :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:02:17 </td>
   <td style="text-align:left;"> $TSLA If your long and hold shares, your good.  We&amp;#39;ll see 1300, 1400 this year once the correction is over. Too many catalysts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:02:15 </td>
   <td style="text-align:left;"> @NewsChartsVolume $tsla gap filled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:02:00 </td>
   <td style="text-align:left;"> $TSLA  
below 872 with a test for resistance at/near that level it would make 840-852 very possible 
chart:https://www.tradingview.com/chart/TSLA/jKQmWQNY-TSLA-trading-it-2-18/ 
#intradaytrading #optionstrading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:01:38 </td>
   <td style="text-align:left;"> $TSLA Waiting for the collapse here to officially put the nail in the coffin to Cathie&amp;#39;s grossly overvalued funds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 09:01:19 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $880.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:59:59 </td>
   <td style="text-align:left;"> $TSLA $QQQ $NASDAQ Maybe Russia will invade after the Olympics ends.    Thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:59:41 </td>
   <td style="text-align:left;"> $TSLA close below 870? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:59:16 </td>
   <td style="text-align:left;"> $TSLA 

Remember this !  

Tesla longs profits are unlimited so are Tesla shorts  losses .. keep this in mind plz!

Super huge short volume- literally north of 140b 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:59:07 </td>
   <td style="text-align:left;"> $TSLA Russian’s started invading! 
! This means WAR! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:58:11 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m not asking for much just $770 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:56:50 </td>
   <td style="text-align:left;"> $TSLA definitely gonna blow up like all other growth names </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:55:05 </td>
   <td style="text-align:left;"> $TSLA 780 could break by tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:55:04 </td>
   <td style="text-align:left;"> $TSLA bigger the dip, bigger the rip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:54:45 </td>
   <td style="text-align:left;"> $TSLA all Tesla Fanboys must be left in complete shambles after this year, including their cult leader. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:52:35 </td>
   <td style="text-align:left;"> $TSLA pt $86/share. We need to fill that gap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:52:09 </td>
   <td style="text-align:left;"> $TSLA phantom braking? Never had that issue. What I do know is a lot of people don&amp;#39;t know how to drive properly and use the tesla right. Maybe new owners and current owners need a lesson on how to use your vehicle. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:52:04 </td>
   <td style="text-align:left;"> $TSLA limit down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:51:51 </td>
   <td style="text-align:left;"> $tsla is due for a big dump retest that 780 asap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:51:37 </td>
   <td style="text-align:left;"> $TSLA looking soooooper boolish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:51:20 </td>
   <td style="text-align:left;"> $TSLA come on bulls, you gotta atleast admit this is phuccin hilarious 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:50:50 </td>
   <td style="text-align:left;"> $SPY $TSLA $ROKU $PLTR 

Nasdaq would be 11k if the big dogs weren’t holding this up right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:49:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Who wants to hold over the long weekend? Unless we get a really good headline this will tank tomm. Thinking about buying an equal amount of puts and calls tomm. Will make money if no war or a war. (Praying for no war unlike some sick fu(ks here) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:49:31 </td>
   <td style="text-align:left;"> $TSLA 
-950$ tomorrow Captain? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:49:29 </td>
   <td style="text-align:left;"> $TSLA  HOW MUCH THIS PORTFOLIO KILLER GONNA PUKE TOMORROW? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:47:23 </td>
   <td style="text-align:left;"> $TSLA Reserve your Fisker Ocean/PEAR today for only $250 on the first, and $100 (fully refundable) on the second! Use reservation code TV9WEU and you will earn yourself loyalty points towards free Fisker swag.   fiskerinc.com/reserve </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:46:36 </td>
   <td style="text-align:left;"> $TSLA love Elon!!!  Says it like it is! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:46:30 </td>
   <td style="text-align:left;"> $SPY $TSLA $SPCE $RKLB $GGPI To all the bears who are convinced that Russia will invade over the long weekend, just reminding that its a long weekend in USA only, not in Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:45:40 </td>
   <td style="text-align:left;"> $TSLA damn Elon just fucked up with that hitler tweet, mans a wildcard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:42:39 </td>
   <td style="text-align:left;"> $TSLA where&amp;#39;s @bigsteve2200  at? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:41:43 </td>
   <td style="text-align:left;"> $TSLA what are we going to blame the drop on this time?  It’s the market valuation kids.  Fuck this sp.  down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:39:15 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #13 ticker with sweep activity where institutions are trading options urgently with 11.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:39:13 </td>
   <td style="text-align:left;"> $TSLA not this time little .. i leave it for cathy timber ... I&amp;#39;ll wait for 819 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:39:11 </td>
   <td style="text-align:left;"> $TSLA “Tsar Bomba?” 
-Vladimir Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:37:46 </td>
   <td style="text-align:left;"> $TSLA it will be back  $1200 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:37:14 </td>
   <td style="text-align:left;"> $TSLA one of these days your going too see a 10 percent pop . This is a great company . Short term price movement is nothing . Long term 🤙. Be greedy when others are fearful and fearful when others are greedy . This market is bottoming out . Way too much fear in the market which is extremely bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:36:03 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:34:30 </td>
   <td style="text-align:left;"> $SPY human invasion is nothing compare to alien invasion. Human brain  are evil, especially those with power and money! Disagreement over money, power , land, when you all can live peacefully and join together for bigger purpose or fight . Like space race or technology race to get us out of planet earth . One day the sun or black hole kill us all, u will regret not doing anything ! Elon mus the only one who’s trying ! He’s god sent . The rest is my ass crack even if your a billionaire, go to hell crooks! $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:34:26 </td>
   <td style="text-align:left;"> $AMZN $TSLA $M biden tomorrow or on Monday:
During my administration, markets reached ATH that nobody ever seen before or done before..
Also you will see the bottom where u started for just for fun.. again never  done before </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:34:21 </td>
   <td style="text-align:left;"> $TSLA  $spy $aapl $roku how is it that many MAJOR stocks crash 40% yet the media has zero reference to the market crashing...

Hmmmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:33:20 </td>
   <td style="text-align:left;"> $ROKU $FB $TSLA $PLTR $NVDA just close the entire fucking market man. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:33:08 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : The family of a 20-year-old killed in a Tesla crash last year is suing the company, alleging suspension failure https://www.stck.pro/news/TSLA/23073081 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:33:01 </td>
   <td style="text-align:left;"> $SPY  $SQ  $SHOP  $TSLA 

I honestly dont want russia/ukraine  war to happen.

No winners in wars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:32:34 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-17 Technical Analysis Video: 
https://www.youtube.com/watch?v=xUwPYO2ndCs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:32:24 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMD puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:29:16 </td>
   <td style="text-align:left;"> $TSLA Take a good look at ticker ILUS my fellow investors - they are NASDAQ bound!  
The Nasdaq uplist is approved and will be taking place in the first half of 2022!  
Patented firefighting technology and UAV&amp;#39;s / EV&amp;#39;s!  .  .  . . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:28:01 </td>
   <td style="text-align:left;"> $TSLA  Cathy avg price: $325 strong 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:25:18 </td>
   <td style="text-align:left;"> @GoodieGoodStockOptions 
Day trading Ranges every morning premarket 9am🤙🏾 news  @NewsChartsvolume 9am
We play ranges and market sentiment eryday $amzn $tsla $aapl. Simple as that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:22:24 </td>
   <td style="text-align:left;"> $F Here&amp;#39;s Why Lucid and Ford Could Be 2022&amp;#39;s Top EV Growth ...https://www.fool.com › investing › 2022/01/09 › heres-... 
Tesla Motors, Inc. (NASDAQ: $TSLA), Ford Motor Company (NYSE: $F) – Tesla Secures 5-year Lithium Supply Deal Starting Next Year With Australia’s Liontown billionaireclubcollc.com/te... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:20:59 </td>
   <td style="text-align:left;"> $ZM $ARKK SHOCKING: CATHIE WOODS TALKS $ARKK $ZM $TSLA SAYS IT WILL RISE TO ALL TIME HIGHS
https://youtu.be/X0_4KtJbUyc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:20:46 </td>
   <td style="text-align:left;"> $TSLA February 17, 2022
https://youtu.be/X0_4KtJbUyc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:19:14 </td>
   <td style="text-align:left;"> $RDFN $BRCC $SPY $TSLA  
 
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $87,569 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 topgainer.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:18:21 </td>
   <td style="text-align:left;"> $ROKU $TSLA $AAPL nobody is gonna want to hold any stocks over the weekend with the looming fear of Russia/Ukraine. More selling tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:17:54 </td>
   <td style="text-align:left;"> $TSLA Perna bulls eat dicks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:12:22 </td>
   <td style="text-align:left;"> $TSLA 🤬 if you still buy a $F  or $GM product after this news, you are crazy. 

These companies have been profiting off the back of killing the earth for years, and now they want to squeeze you during tough times for a quick buck. 

Unreal. 

I&amp;#39;ll stick to buying Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:12:13 </td>
   <td style="text-align:left;"> $TSLA time to return to the moooooon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:10:29 </td>
   <td style="text-align:left;"> $NVDA $TSLA Putin does not respect biden. It is just that simple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:07:58 </td>
   <td style="text-align:left;"> $TSLA Bullish above $863, monthly 10 day moving average.  If that fails, next level to watch is $517 (yikes) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:07:19 </td>
   <td style="text-align:left;"> $TSLA elon for prime minister </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:07:14 </td>
   <td style="text-align:left;"> $TSLA 

@ARKinvest 

CNBC may have a 40 minute time horizon, but ARK&amp;#39;s is 5 years. Thanks for having us on @CNBC, we&amp;#39;re happy to pay for your upgraded Zoom account. You can&amp;#39;t be a knowledge worker without it! 😉

🙏🏻🐉🦅🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:06:02 </td>
   <td style="text-align:left;"> $AMC My mom says she can take us to the war with Russia tomorrow.. but we gotta find a ride back home 🏡 $SPY $TSLA $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:04:20 </td>
   <td style="text-align:left;"> $TSLA just wanted to remind everyone that the stock market is the greatest place to lose your money as it&amp;#39;s designed to hurt the bears and the bulls just as bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:02:37 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-17 Trade Analysis Video: 
https://www.youtube.com/watch?v=wTE8Pl7nwEQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:01:11 </td>
   <td style="text-align:left;"> $TSLA Elon Musk is a morron </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:00:26 </td>
   <td style="text-align:left;"> $TSLA This stock will trade in a range of 860-890 tomorrow.  It is Friday before a 3-day weekend.  I don&amp;#39;t see big moves being made here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:00:18 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:00:11 </td>
   <td style="text-align:left;"> $SPY $BTC.X $ROKU $TSLA $SPCE 

🤣😆🤣😆🤣😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 08:00:01 </td>
   <td style="text-align:left;"> $DWAC $tsla $twtr this is how it works guys, Durham files a brief, then indictments, indictments are next from the bottom up, 3 people are already in jail pay attention sussman will be the scapegoat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:59:11 </td>
   <td style="text-align:left;"> $TSLA 200 SMA on the daily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:58:07 </td>
   <td style="text-align:left;"> $TSLA Sleepy  Jose said.. Voted for me... hahaha. I made American virus ... hahah.. and cleR sky.. Hhah. In coffin ⚰️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:56:02 </td>
   <td style="text-align:left;"> $TSLA TESLA YOU POS YOU OWE ME 600.00 - BISH BETTER HAVE MY MONEY TOMORROW WHEN WE BLEED DOWN TO 840.00 or less. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:54:28 </td>
   <td style="text-align:left;"> $TSLA Elon stop being a meanie and leave Justin Trudeau alone. You’ll never be the virtuous man he is! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:53:47 </td>
   <td style="text-align:left;"> $SPY  $QQQ I noticed  around  $19M  put for tomorrow  
Lets get rebound some to burn that puts !!  
 
Also $tsla call we’re bougth about 50M due tomorrow .. so far that call is toasted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:53:46 </td>
   <td style="text-align:left;"> $TSLA maybe of Tesla cars were not so ugly they may sell a few </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:53:46 </td>
   <td style="text-align:left;"> $TSLA long way to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:52:25 </td>
   <td style="text-align:left;"> $TSLA $GME $AMC

https://www.cnbc.com/2022/02/17/tesla-ceo-musk-accuses-sec-of-calculated-effort-to-chill-his-right-to-free-speech.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:52:11 </td>
   <td style="text-align:left;"> $TSLA wen stock split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:51:49 </td>
   <td style="text-align:left;"> $TSLA wen moon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:49:48 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/IJ21kOPc8fc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:49:46 </td>
   <td style="text-align:left;"> $TSLA breaking news FB will be bankrupt ! Imho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:49:29 </td>
   <td style="text-align:left;"> $TSLA 

I see great alignment between Biden Administration and MSM (main stream media) in treating the public like fools ! 

🙏🏻🐉🦅👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:48:58 </td>
   <td style="text-align:left;"> $SPY hahah Elon $TSLA  😂 $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:48:05 </td>
   <td style="text-align:left;"> $TSLA Awfully fortunate for Elon that he was able to unload all those shares back when the share price was $200 higher. And having W$ pump some scam-assed Hertz deal to inflate the price before he dumped. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:47:24 </td>
   <td style="text-align:left;"> $SPY $TSLA lol love it 

  https://nypost.com/2022/02/17/elon-musk-tweet-compares-justin-trudeau-to-adolf-hitler/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:44:52 </td>
   <td style="text-align:left;"> $TSLA some speculate we might be declining all the way to March 16th. That&amp;#39;s a huge decline ahead. Lots of money to be lost. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:44:52 </td>
   <td style="text-align:left;"> $TSLA Going to probably test that small $840 level support tomorrow, if that fails god help us it&amp;#39;s back to around $800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:44:18 </td>
   <td style="text-align:left;"> $TSLA those block buys are just so we can sell in the morning 😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:41:41 </td>
   <td style="text-align:left;"> $TSLA https://teslanorth.com/2022/02/17/tesla-app-hints-yearly-subscriptions-coming-soon-new-actionable-notifications-debut/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:40:40 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $880.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:40:05 </td>
   <td style="text-align:left;"> $TSLA TSLA Stock Price Prediction and analysis for Tomorrow Friday  February 18th
https://youtu.be/YGkrY9caCf0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:39:24 </td>
   <td style="text-align:left;"> $TSLA I bought Feb 25 $905 calls today. Lord I need a miracle. 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:38:34 </td>
   <td style="text-align:left;"> $TSLA can’t wait to start buying puts omg never buying calls here again what a shit decision!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:38:26 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla plunges seven spots in annual Consumer Reports ranking https://www.stck.pro/news/TSLA/23070997 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:37:21 </td>
   <td style="text-align:left;"> $SPY $TSLA $ARKK $IWM bloody Friday 🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:36:57 </td>
   <td style="text-align:left;"> $TSLA 12 hours from now people will resurface to say 1000 eod LOLLLLLL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:35:56 </td>
   <td style="text-align:left;"> $TSLA 

Russia 🇷🇺 Ukraine tension has ZERO effect on US, literally our Economy doesn’t give flying f**- it’s just a cover for criminals to naked short the market just like inflation &amp;amp; interest fears ! 

More of the same BS with endless manipulation uncensored !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:35:40 </td>
   <td style="text-align:left;"> $ROKU $TSLA $ARKK 
https://youtu.be/sGgvW-U8R7o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:35:22 </td>
   <td style="text-align:left;"> $DWAC MSM and their audience $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:34:43 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow. 
 
https://youtu.be/Ez0CWyo2WDs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:33:40 </td>
   <td style="text-align:left;"> Breaking News: Can&amp;#39;t wait for Direxion&amp;#39;s $TSLA Leveraged ETFs (2x Bull and 1x/2x Bear). It&amp;#39;s going to be fun and most likely could increase the volatility in Tesla shares offering another great way to trade the stock: https://seekingalpha.com/news/3801784-bullish-or-bearish-on-tesla-direxion-looks-to-have-you-covered-either-way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:31:00 </td>
   <td style="text-align:left;"> $NVDA Nothing to do with companies. This is causing a market wide crash! $CRM $TSLA $RBLX 
 futures are flat after Dow suffers its worst day of the year https://www.cnbc.com/2022/02/17/stock-market-futures-open-to-close-news.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:30:25 </td>
   <td style="text-align:left;"> $TSLA 877? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:29:36 </td>
   <td style="text-align:left;"> $ALB I hate to say it but the PE is just too damn high.  This has to trade down to 100 to get interesting again. latex4e3f571b4375ed7f5e7344ebd27d2586DWAC 
$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:26:39 </td>
   <td style="text-align:left;"> $TSLA Super low volume, not worried. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:26:18 </td>
   <td style="text-align:left;"> $SHIB.X $TSLA $DKNG $AMC $BRK.B HOLD ON TO YOUR SHIBA INU! JUST HIT THE STREET WESTERN UNION IS DEAD! IN TEXAS ALL EMPLOYERS ARE PAYING WITH SHIBA DEBIT CARDS. IMMIGRANTS ARE SENDING MONEY HOME WITH NO FEES! ALL ATMS IN THE SOUTH ARE NOW SET FOR DOING SHIBA AND BANKS TOO! BRAZIL JUST LEGALIZED SHIBA AND BUFFET BOUGHT 1 TRILLION YESTERDAY! DON&amp;#39;T MISS THE NEXT BITCOIN! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:25:37 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:25pm)

⦿ $TSLA is down 0.1% in the last 5 mins. 

⦿ There are 3 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 5.8% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:25:24 </td>
   <td style="text-align:left;"> $TSLA 861 .. 831 .... 785 / 851 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:25:18 </td>
   <td style="text-align:left;"> $TSLA bought calls, should have bought puts. Manhattan avenue in Greenpoint Brooklyn literally right now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:24:39 </td>
   <td style="text-align:left;"> $TSLA Surprise! Surprise! Head of Consumer Reports used to be a top executive at Ford foundation. See caption. $SPY $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:23:49 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $UPST $ROKU this market bout to go stoopi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:23:08 </td>
   <td style="text-align:left;"> $TSLA I think we can see 550 by end of March </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:21:37 </td>
   <td style="text-align:left;"> latexf840aabe6d5f5776c4e30e3c1d22f66b$ media, government, manipulators etc.!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:21:22 </td>
   <td style="text-align:left;"> $TSLA the grim sleeper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:20:00 </td>
   <td style="text-align:left;"> $SPY $SPX $TSLA $AAPL $GME Does anyone else see 10000 coming? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:19:53 </td>
   <td style="text-align:left;"> $TSLA uh oh is she gonna bounce here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:18:11 </td>
   <td style="text-align:left;"> $SPY $NASDAQ $QQQ $TSLA $AMZN It it only me, or do others see 10,000 coming? 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:18:03 </td>
   <td style="text-align:left;"> $TSLA rising EPS at exponential growth is going take tesla forward. It ain’t no crappy company like Roku </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:17:28 </td>
   <td style="text-align:left;"> $TSLA lol slept all day the put is even deeper green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:16:23 </td>
   <td style="text-align:left;"> $TSLA if Putin drops the hammer things could get baddddddd… got some lotto 650 puts for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:16:15 </td>
   <td style="text-align:left;"> $TSLA baggies need push up bras rofl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:14:20 </td>
   <td style="text-align:left;"> $TSLA added to my $600 March puts. Now have 150 contracts at $0.76 avg cost. Keep BTFD peasants. Wen moon LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:13:29 </td>
   <td style="text-align:left;"> $spy $tsla $spx $amzn $roku </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:12:10 </td>
   <td style="text-align:left;"> $TSLA former trillion mc company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:11:57 </td>
   <td style="text-align:left;"> $TSLA how long is this bs market will be do normal again
F*** joe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:11:25 </td>
   <td style="text-align:left;"> $QQQ latex3e596dabdecc0b823edd7c900ab46ad6AMC 
$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:11:04 </td>
   <td style="text-align:left;"> $TSLA nasdaq 12k tesla $600 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:10:58 </td>
   <td style="text-align:left;"> $VUZI is the $TSLA of AR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:09:23 </td>
   <td style="text-align:left;"> $TSLA Let me daydream a bit to lessen my pain: 
- Comes March 
- Inflation data not too bad for Feb 
- The fed shocks us and only go up 0.25% and not 0.5% 
- Giga Berlin gets its permit  
 
- We rally to $950 ,maybe $1000  
 
 
Hold the line 😭😭😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:09:16 </td>
   <td style="text-align:left;"> $PLTR is the $TSLA of AI software
Use these absurd market valuation discrepancies to accumulate shares for the long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:08:51 </td>
   <td style="text-align:left;"> $TSLA back over $900 tomorrow 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:07:18 </td>
   <td style="text-align:left;"> $TSLA Trading Ideas | 9 Trades executed, trade Profitability of 77% and Profit Factor of 5. 15 minute chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:07:06 </td>
   <td style="text-align:left;"> latex42013d890949dde9de207778e1cf18baROKU -76% 
$ZM -70% 
COIN -55% 
EXAS -50% 
U -51% 
NTLA -55% 
PATH -60% 
SQ -64% 
TWLO -63% 
SPOT -59% 
BEAM -50% 
CRSP -65% 
PLTR -60% 
DKNG -70% 
SHOP -63% 
PD -38% 
HOOD -85% 
FATE -71% 
Here you go, I fixed the Forbes cover for you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:06:17 </td>
   <td style="text-align:left;"> $TSLA if your a bull, you are just as autistic as musk! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:03:54 </td>
   <td style="text-align:left;"> $SPY $BTC.X  $TSLA  would you guys consider $5500 too much for a 1.5month long vacation for 1person  with everything included? I’m really unsure if the price would be worth it but this vacation has been a dream of mine(this vacation is also a once in a lifetime opportunity, I will NEVER get this opportunity again, it’s more than just a “vacation”). Honest opinions please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:02:38 </td>
   <td style="text-align:left;"> $SPY $TSLA I dont want to sound gay bear but hedge bro </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:02:26 </td>
   <td style="text-align:left;"> $TSLA what was the last upgrade price on this name and by who??? lmao 600 coming $QQQ $SPY sell off... #MarketTrade #LookOutBelow wait to buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 07:00:28 </td>
   <td style="text-align:left;"> $TSLA $MSFT NICE CALLS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:58:47 </td>
   <td style="text-align:left;"> Market just decided to kill the swings. I talked to my team, and I will be going Cash Heavy until mid March and just okaying aggressive scalps!

It’s hard to alert the quick moves here, luckily we installed Live Trading in our group and it’s working extremely well!

Anywho, today’s W’s and L’s:

-  $SPY we had 8 trades here today, 5 hits, one break even and some small losses 

- $AMD and latex4be69036eca878104c185c5f04bf6a98AMZN 
$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:56:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $RBLX pull up wit a drone like I’m Tommy Lee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:56:01 </td>
   <td style="text-align:left;"> $ARKK $RBLX $TSLA  
The &amp;quot;market is never wrong&amp;quot; has been around for 40 years.  So, maybe it isn&amp;#39;t true anymore and Jim Cramer hasn&amp;#39;t caught up -OR- maybe it is still true because the real saying is the &amp;quot;market is never wrong for very long!!&amp;quot;  Everyone leaves of the part that say&amp;#39;s it can be wrong for a short time.  Chears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:48:26 </td>
   <td style="text-align:left;"> latexd239bea939a8a0702079a5fbcf8b6718AMZN 
$AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:46:48 </td>
   <td style="text-align:left;"> $TSLA 

We have no idea yet what the consequences of having kids in masks 😷 for 2 yrs .. no idea ! 

~Jordan Peterson 

🙏🏻🐉🦅

https://youtu.be/UuCBP-3tGcI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:45:31 </td>
   <td style="text-align:left;"> $SPY not to be redundant with this (I hate the way posting videos makes me look), but I talked about where &amp;amp; why the $SPY was going today, as well as $TSLA (stated a &amp;quot;range&amp;quot;) and $AMD... 
 
If you skip forward to about the 25:31 mark within the video, that&amp;#39;s where I&amp;#39;m breaking down the TA on said moves. 
 
When people tell you &amp;quot;technical analysis doesn&amp;#39;t work,&amp;quot; it&amp;#39;s because THEY fail to use it properly.   
 
If a casino can make money on a game of chance, such as craps (dice), then a Trader CAN leverage basic math &amp;amp; statistics (aka, &amp;quot;techncals&amp;quot;) to extract money from the markets.   
 
STOP listening to the naysayers...  They&amp;#39;re naysayers, because they&amp;#39;ve FAILED at what you&amp;#39;re trying to do.   
 
95% of this game is psychology...the other 5% is basic math 🤷‍♂️ 
 
https://www.youtube.com/watch?v=dA7eUPlDVz4&amp;amp;t=9s 
 
ps... I call moves on stuff like $ISPO EVERYDAY.  Again...not rocket science.  It&amp;#39;s EMOTIONS and BASIC MATH... ✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:43:39 </td>
   <td style="text-align:left;"> Tesla Motors, Inc. (NASDAQ: $TSLA), ( $ARKK) – Want To Bet Against Tesla? There Could Be A New Inverse ETF For Traders https://www.billionaireclubcollc.com/tesla-motors-inc-nasdaqtsla-arkk-want-to-bet-against-tesla-there-could-be-a-new-inverse-etf-for-traders/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:43:39 </td>
   <td style="text-align:left;"> $TSLA https://www.investors.com/market-trend/stock-market-today/dow-jones-futures-stock-market-is-minefield-as-biden-sees-very-high-russia-invasion-risk-roku-plunges/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:43:22 </td>
   <td style="text-align:left;"> $ROKU sell and buy $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:43:17 </td>
   <td style="text-align:left;"> $TSLA How many Trillion $$$ Company’s Exist ?? 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:43:02 </td>
   <td style="text-align:left;"> $TSLA so powerful there going create s etf to short it 😂🙌🏾  game on assholes ! Momma always said follow the rich white man😂🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:42:52 </td>
   <td style="text-align:left;"> $TSLA https://driveteslacanada.ca/model-y/more-than-100-tesla-model-ys-spotted-under-car-covers-outside-giga-texas-looking-very-ready-for-delivery/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:42:44 </td>
   <td style="text-align:left;"> 🚨 Watchlist From Last Night Going Into Today! 🚨  
 
$NVDA (earnings play)  
📉 $258.60: 🎯 $248.36, $241.75 
 
$NVDA hit a low of $241.42 WHAT A DAY and trade off the short at open.  
 
$TSLA  
📉 $905.29: 🎯 $896.72, $870.46 
 
$TSLA $905.30 short hit $873 😮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:39:10 </td>
   <td style="text-align:left;"> Want To Bet Against Tesla? There Could Be A New Inverse ETF For Traders  $TSLA $BA $COP $NKE $NVDA 

https://newsfilter.io/a/15dd56b249963abf11defda5910fdb55 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:38:34 </td>
   <td style="text-align:left;"> $TSLA $AAPL $NVDA $GOOGL $FB - Why do you think there are so many subscriptions and alert services are there? Because it is REALLY hard to make money by trading! Anyone selling these services or posting youtube videos is the one who makes money LOL!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:38:01 </td>
   <td style="text-align:left;"> $TSLA Lmaoo u kno tbh we didn’t do bad 😂 u kno under 800 I would been like fuck my mother 😂 but now we good now after this dip it only up from here 👏🏾 ain’t no fuckin war going happen let’s get back to reality and this money Covid done omicron done mask been lift at jobs schools events after this Russia bull shit it going back a trillion dollar company </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:37:16 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!!

@kwtts 

Just got a ride in a @Uber owned by Tesla.
Yes you read that right, my Uber driver told me that the Model 3 he is driving isn’t his or owned by @Hertz, but rather a pilot program being run by @Tesla with a small number of highly ranked Uber drivers in California! @elonmusk

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:37:01 </td>
   <td style="text-align:left;"> $TSLA Nobody will be buying a Tesla when there is nobody who can fix or maintain them. Enjoy the next banker war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:36:59 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $TSLA did I miss something? Did Russia invade or something? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:35:51 </td>
   <td style="text-align:left;"> Want To Bet Against Tesla? There Could Be A New Inverse ETF For Traders $TSLA $ARKK $SARK https://benzinga.com/z/25705320#.Yg7NmlpmnBM.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:34:20 </td>
   <td style="text-align:left;"> $TSLA times are changing... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:32:12 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-17 Largest Trades Data: 
https://www.youtube.com/watch?v=KWREaoRE6M0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:32:02 </td>
   <td style="text-align:left;"> $SQ $TSLA $TQQQ F#ck Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:29:54 </td>
   <td style="text-align:left;"> $SPY anyone trading for the dot com bubb? me niether. but from what i see, all the shitty ones started to fall first, one by one, then dominoed, till finally the monsters went down. see a similarity with tech today? $TSLA $NFLX $ROKU I&amp;#39;ll name it now:  the Great Tech Bubble. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:29:25 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT My cat has had some extra money lately. . . . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:28:33 </td>
   <td style="text-align:left;"> $TSLA after $SHOP today, I&amp;#39;m convinced valuation will matter one day and Tesla better keep up with this valuation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:27:52 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $HOOD almost there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:27:41 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA tough day in the markets - mostly red across the board. A lot of chatter across social, sentiment was mixed overall though. Will be watching this in pre-market tomorrow - should set the stage to close out the week. 
 
You can keep track of the real-time social moment and social trends with this dashboard. It&amp;#39;s useful alternative data. Remember, the market is driven by emotion... 
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_202202017 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:26:46 </td>
   <td style="text-align:left;"> $TSLA Even the people on the Titanic were the time of their lives. Until it hit an iceberg. Watch those margin accounts, just an opinion 😌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:26:37 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT Billy could be the next Tom Lee!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:25:16 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Easy to spot them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:24:02 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT Wordle 2/45 
➖🟫🟫➖➖🟫🟫 
➖🟫🟫🟫🟫🟫🟫 
🟫🟫🟫🟫🟫🟫🟫🟫 
🟫⬜️⬛️⬜️⬜️⬛️⬜️🟫 
🟫🟫🟫🟫🟫🟫🟫🟫 
🟫🟫🟫🟫⬛️🟫🟫🟫 
🟫🟫🟫🟫🟫🟫🟫🟫 
🟫🟫🟫⬛️⬛️⬛️🟫🟫 
➖🟫🟫🟫🟫🟫🟫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:22:46 </td>
   <td style="text-align:left;"> $TSLA “Phantom Braking” ☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:22:13 </td>
   <td style="text-align:left;"> $SPY $TSLA The new safehaven for mixed market pivot points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:21:59 </td>
   <td style="text-align:left;"> $TSLA shoulda known - anything Cathie woods guys drops 20% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:21:50 </td>
   <td style="text-align:left;"> $TSLA !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:20:12 </td>
   <td style="text-align:left;"> $TSLA $ARKK $ROKU 
Oweeee! Shots fired! 😆

https://youtu.be/WHv12wOWX08 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:20:03 </td>
   <td style="text-align:left;"> $TSLA All accounts crashing except my Tesla car loan. Thank goodness 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:19:53 </td>
   <td style="text-align:left;"> $TSLA .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:18:10 </td>
   <td style="text-align:left;"> $TSLA another $50 billion home!! Poof!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:17:59 </td>
   <td style="text-align:left;"> $TSLA 700 march </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:17:50 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT My tendies this week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:17:06 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla lawyers accuse SEC of chilling Elon Musk&amp;#39;s right to free speech https://www.stck.pro/news/TSLA/23067603 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:15:58 </td>
   <td style="text-align:left;"> $TSLA where is the bottom? ultimately I think it may be around $130-150, but probably won&amp;#39;t get there all at once. Maybe around $520 for a more intermediate resistance level? Or $480? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:15:11 </td>
   <td style="text-align:left;"> $TSLA yeah make it an even $50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:14:37 </td>
   <td style="text-align:left;"> $TSLA roku no bueno </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:14:34 </td>
   <td style="text-align:left;"> $TSLA 

So Elon’s Lawyer sends a letter to SEC in a response to their unlawful subpoena telling these clowns to FUCK off !! 

“You’re in violation of 2018 agreement” 

Clowns corrupt take orders from corrupt administration!!

🙏🏻🐉🦅😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:14:20 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $DIS Behind the scenes footage of Spiderman 6.  MJ learns about the ugly side of Peters investments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:14:04 </td>
   <td style="text-align:left;"> $TSLA if cathy knows what shes doing, shes already created a short position greater in size than the long position she announced last week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:13:21 </td>
   <td style="text-align:left;"> $TSLA wow! This is dumping so hard AH it’s going backwards in time 🤯 wow! This must be bullish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:12:27 </td>
   <td style="text-align:left;"> $TSLA did anyone happen to read the letter Elon&amp;#39;s lawyer filed in federal court? I think Elon is about to be prosecuted. The letter sounded desperate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:12:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL But the guy on youtube made 10,000 bucks in 30 minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:10:58 </td>
   <td style="text-align:left;"> $TSLA did Cathy really just jump out of a window? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:10:39 </td>
   <td style="text-align:left;"> $MSFT $TSLA $GOOGL $FB $AMZN … ⚠️

JPM: 

18% chance of a recession over the next 12 months but rises to:

♦️40% over the next 2 years, 
♦️60% over the next 3 years, 
♦️80% over the next 4 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:10:37 </td>
   <td style="text-align:left;"> Ever notice when you post on stock twits .. bots with fake accounts copy and paste on Twitter $aapl $spy $TSLA $SPX $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:10:19 </td>
   <td style="text-align:left;"> $SPY $MSFT $TSLA Many folks don&amp;#39;t believe in JPOW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:09:57 </td>
   <td style="text-align:left;"> $TSLA $FUBO God please bring back Trump before we all become homeless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:09:44 </td>
   <td style="text-align:left;"> $TSLA take it where it belongs $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:09:19 </td>
   <td style="text-align:left;"> $TSLA pretty soon someone will have to do a wellness check on Cathie! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:09:15 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL The crew of the Enterprise never recovered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:08:51 </td>
   <td style="text-align:left;"> $TSLA How in hell can you be bullish? I mean seriously 😐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:08:08 </td>
   <td style="text-align:left;"> $TSLA Anytime you see those insanely long wicks in AH the next day is normally (100pts) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:08:00 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL If anyone needs a gut punch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:07:59 </td>
   <td style="text-align:left;"> $TSLA did Trudeau just sell his Tesla shares? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:07:26 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT So much exposure this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:06:39 </td>
   <td style="text-align:left;"> $tsla big red candle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:06:37 </td>
   <td style="text-align:left;"> $TSLA dumping in AH, should of bought some puts for a swing…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:06:34 </td>
   <td style="text-align:left;"> $TSLA held it all day drop it AH. Typical wall st. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:06:24 </td>
   <td style="text-align:left;"> $TSLA  Elon&amp;#39;s unemployment benefits would be $0 just like his 3 different alimony obligations that&amp;#39;s how Tesla sustains failure through shareholder mitigated risk taking just like Elon&amp;#39;s ex-families. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:05:45 </td>
   <td style="text-align:left;"> $TSLA I got u ELON I GOTCHYA LARRY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:04:43 </td>
   <td style="text-align:left;"> $TSLA I would ❤️ to $800 tomorrow come on tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:04:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Punctuation matters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:04:17 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ  Nasdaq potential bull flag. all Biden has to do is open his mouth and nasdaq is at 12k though smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:04:04 </td>
   <td style="text-align:left;"> $TSLA is 300 possible tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:03:31 </td>
   <td style="text-align:left;"> $TSLA my life was better when I just bought and held stocks instead of buying options haha.  I’m over it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:03:13 </td>
   <td style="text-align:left;"> $TSLA Cathie must be killing it. 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:02:39 </td>
   <td style="text-align:left;"> $TSLA considering how $SPY got slaughtered, I would say this showed some strength even tho down 5 points. I think I’m switching back to bullish. This is starting to seem like a long consolidation at this point. We have to go green tmrw or this may be headed back to $840-50 range. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:02:08 </td>
   <td style="text-align:left;"> $TSLA Left unchecked, two adult rodents can be responsible for the birth of up to 15,000 pups over the course of a year. In other words, all it takes is two rats to bring an infestation back to its original size or larger. ContraPest works by counteracting this rebound effect, significantly reducing their ability to reproduce. Once deployed, your furry, unwanted visitors’ departure is simply a matter of time....80 cents $SNES ...Rats love Tesla&amp;#39;s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:00:45 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-17 Options Analysis Video: 
https://www.youtube.com/watch?v=8NvpsUK_LMg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 06:00:43 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT Don&amp;#39;t get caught off guard if your wife asks about your trades.  Be ready with one of these top notch answers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:59:35 </td>
   <td style="text-align:left;"> $TSLA Bitcoin is on track to lose $4k today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:58:15 </td>
   <td style="text-align:left;"> $TSLA this shit is getting hammered everybday with negative articles recalls, investigations, etc, cant catch a break rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:58:14 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $880.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:57:57 </td>
   <td style="text-align:left;"> $SPY $ADBE Certainly a buy.  Taking $TSLA too.  Fu. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:57:04 </td>
   <td style="text-align:left;"> $TSLA why this website is garbage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:56:51 </td>
   <td style="text-align:left;"> $TSLA @GManBull46  Friends the pain is almost over. I see an $860 to $850 turn around. Keep your smile. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:56:40 </td>
   <td style="text-align:left;"> $TSLA remind me again why the market corrected so hard wiping out years worth of Nasdaq gains again ..with some actual facts instead of the daily FUD on cnbc? 

Did we miss earnings.. stop growing? Did a war really happen?  Any interest rate hikes happen yet that we don’t know about? 🤷🏻‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:56:04 </td>
   <td style="text-align:left;"> $TSLA I’ll never buy calls here again. Absolute garbage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:55:42 </td>
   <td style="text-align:left;"> $TSLA 858.82 tomorrow. Will go long on calls there. Will buy 870 calls when it gets there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:55:35 </td>
   <td style="text-align:left;"> $TSLA see you at $700 by April </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:55:10 </td>
   <td style="text-align:left;"> $TSLA invasion about to begin.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:55:01 </td>
   <td style="text-align:left;"> $TSLA ever since elon opened his stupid mouth, stock has been slaughtered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:52:07 </td>
   <td style="text-align:left;"> $TSLA opens high I buy puts opens low I buy puts opens flat I buy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:51:55 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT Working on a sixth edition now about how to lose it all, again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:51:18 </td>
   <td style="text-align:left;"> $TSLA Calls made great profits today!🤑😈
Free discord in bio if u want to learn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:50:41 </td>
   <td style="text-align:left;"> $TSLA Here we go … danish TV ;-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:49:32 </td>
   <td style="text-align:left;"> $SPY $ROKU $TSLA 
Markets closed on Monday. Will everything sell off into the 3 day weekend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:49:29 </td>
   <td style="text-align:left;"> $TSLA you effing retards. https://www.youtube.com/watch?v=b6H5ZDUwVSI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:49:23 </td>
   <td style="text-align:left;"> $TSLA bottle of tabasco squirted up the ass type of day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:49:00 </td>
   <td style="text-align:left;"> $TSLA oh boy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:48:55 </td>
   <td style="text-align:left;"> $TSLA damn if I held my $905 put till today it would be money 😭🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:47:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $NVDA Friday before a 3-day weekend with market closed Monday during a geo-political crisis? Yeah, I&amp;#39;ll stay on the sidelines for now. Buy lower next week some time. Adios. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:46:31 </td>
   <td style="text-align:left;"> $TSLA down trend..todays red candle is predicting back into the blue channel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:46:06 </td>
   <td style="text-align:left;"> $SPY $SPX $AAPL $TSLA Inflation, rate hike all are priced in. The fear of war is the last bad news for the bottom, smart bears already started to cover. You should know that the market is a roller coaster, when the institutions decide it will start to go up. Psychology plays an important role also. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:45:48 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT Soooooo transitory it&amp;#39;s really not worth talking about babe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:44:23 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #5 stock that institutions are trading over rolling 5 day window with 112.0K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:44:14 </td>
   <td style="text-align:left;"> $TSLA another 40$ haircut tomm would be nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:43:46 </td>
   <td style="text-align:left;"> $SPY $TSLA $DIS . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-18 05:43:28 </td>
   <td style="text-align:left;"> $TSLA 1 year chart looks real bad.. the ALL chart looks like a giant pump and dump </td>
  </tr>
</tbody>
</table></div>

---
