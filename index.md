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



Last Updated: 2022-03-11 09:14:44 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/balance-of-trade </td>
   <td style="text-align:left;"> 2022-03-11 09:12:57 </td>
   <td style="text-align:left;"> Philippines Trade Gap Widens </td>
   <td style="text-align:left;"> The Philippines' trade deficit increased to USD 4.69 billion in January 2022 from USD 2.88 billion in the same month a year earlier, as exports grew by 8.9% yoy to USD 6.28 billion while imports climbed 27.5% to a fresh record peak of USD 11.55 billion. In 2021, the trade gap widened sharply to USD 43.13 billion from USD 24.60 billion, with exports growing 14.5% from the same period of 2020 to USD 74.64 billion and imports jumping 31.1% to USD 117.78 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 09:06:41 </td>
   <td style="text-align:left;"> Nikkei 225 is down by 2% </td>
   <td style="text-align:left;"> Nikkei 225 decreased 2% to 25176 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 08:54:48 </td>
   <td style="text-align:left;"> Australia Shares Track Wall Street Lower </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index fell 0.4% to around 7,100 on Friday after a two-day advance, as Australian shares tracked a weak overnight finish on Wall Street, with another hot US inflation print, prospects of higher interest rates and a failed first round of Russia-Ukraine talks weighing on sentiment. Australia’s top central bank also cautioned  markets it would be prudent to prepare for a rise in interest rates this year with inflation set to increase due to the recent surge in global commodity prices. High-growth technology and healthcare stocks led the declines, with losses from Aristocrat Leisure (-3.1%), Brainchip Holdings (-2.1%), Xero (-3.5%), CSL Ltd (-1.3%), Anteotech (-8.6%) and Cochlear (-1.1%). Meanwhile, resource-related firms advanced despite softer commodity prices, with gains from BHP Group (1.2%), Rio Tinto (1.9%), Fortescue Metals (2.4%), Woodside Petroleum (0.3%) and Whitehaven Coal (3.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-11 08:36:01 </td>
   <td style="text-align:left;"> China 10Y Bond Yield Hits 11-week High </td>
   <td style="text-align:left;"> China 10 Year Government Bond Yeld increased to a 11-week high of 2.897% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/metal-prices-hit-record-highs-costs-of-consumer-goods-to-rise-russia-ukraine-commodities-steel-nickel-iron </td>
   <td style="text-align:left;"> 2022-03-11 08:29:58 </td>
   <td style="text-align:left;"> Metal prices hit record highs, costs of consumer goods to rise </td>
   <td style="text-align:left;"> FOX Business correspondent Lydia Hu has the latest from Eastchester, New York, on 'Cavuto: Coast to Coast.'                                                                                                                                                                                                                                                                                                                                                                                                                                    , Metal prices are surging to record highs as the commodities remain in short supply exacerbated by the war in Ukraine. The crunch is threatening to increase the costs of goods from cookware to consumer electronics and construction.                                                                                                                                                                                                                                                                                                         , Although metals have not been subject to sanctions yet, manufacturing companies in the U.S. are avoiding Russian goods, sending shock waves to a variety of metal commodities.                                                                                                                                                                                                                                                                                                                                                                 , COMMODITIES HAVE BEST WEEK EVER AS RUSSIA, UKRAINE SPARKS BUYING                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Russia is a key global supplier for metals such as aluminum, nickel and palladium, which soared 52.4%, 211.04% and 29.8%, respectively on Wednesday based on futures settlement prices.                                                                                                                                                                                                                                                                                                                                                        , While both Russia and Ukraine account for 7.5% of global iron and steel exports, Russia makes up for 5% of nickel and 6% of aluminum production.                                                                                                                                                                                                                                                                                                                                                                                               , These metals are used to make stainless steel, lithium-ion batteries and other manufacturing inputs, which are rippling through the construction and auto industries.                                                                                                                                                                                                                                                                                                                                                                          , Construction projects are expected to see incremental price hikes and even cancellations or delays.                                                                                                                                                                                                                                                                                                                                                                                                                                            , "Construction input prices such as steel and copper are already sky high, and this is moving the needle even higher," Associated Builders &amp; Contractors Chief National Economist Anirban Basu told FOX Business. "Equipment is already in short supply and already very expensive. It's really hard for them to deliver projects on budget and on time given labor force dynamics, and this renders that situation even more difficult."                                                                                                       , GOLD FUTURES CLIMB 4% FOR WEEK AS RUSSIA-UKRAINE WAR CONTINUES                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , One metal fabricator based in Manhattan told FOX Business that his suppliers will not quote prices for more aluminum, raising concern over whether he can secure the raw materials.                                                                                                                                                                                                                                                                                                                                                            , "Being able to get the material is the first hurdle, and the pricing is the second part," President and Founder of Hammersmith Metals, Jeffrey Herkes, told FOX Business. "Every 90 days I seem to be getting a price correction, whether it’s for the stainless steel that’s going up because of the nickel, chrome and other materials."                                                                                                                                                                                                     , Metal Fabricating at Hammersmith Metal Fabricators (Scotch View, New Jersey)                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Hammersmith Metal Fabricators specializes in the design, fabrication and manufacture of customized metalworks for urban landscapes throughout New York City, Brooklyn, Staten Island and New Jersey. Their craftsmen create hardscapes and furniture with a variety of materials like copper, stainless, aluminum and steel.                                                                                                                                                                                                                   , Herkse said that a price-free safe zone "doesn’t exist today," as prices for all metals continue to rise across the board.                                                                                                                                                                                                                                                                                                                                                                                                                     , Metal Fabricating at Hammersmith Metal Fabricators (Scotch View, New Jersey)                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , EXXON MOBIL CEO SAYS OIL COMPANIES WERE IN TOUGH POSITION BEFORE UKRAINE-RUSSIA WAR                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Milgo Bukfin, a Brooklyn-based custom metal fabrication company, is having to pass along the costs to clients due to the increase in material costs. The company provides services such as metal bending, laser and waterjet cutting, and full fabrication and finishing for commercial projects including One Vanderbilt, Hudson Yards and LaGuardia Airport.                                                                                                                                                                                 , Scott Kranzler, Vice President of Milgo Bufkin, told FOX Business that his company has not had any delays or cancellations yet, but that does not rule out concern for future disruptions should uncertainty and price increases in the metals markets persist.                                                                                                                                                                                                                                                                                , It’s not just the construction industry grappling with the tailwinds of the commodity market’s volatility and price pops. Automakers already hurting from higher energy costs and the ongoing chip shortage are facing new obstacles that could mean higher prices for drivers.                                                                                                                                                                                                                                                                , WHEAT PRICES HIT 14-YEAR HIGH, FOOD SHORTAGE FEARS RISE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Nickel is one of the main components in the lithium-ion battery cells used in the majority of electric vehicles in the U.S. market.                                                                                                                                                                                                                                                                                                                                                                                                            , The price of nickel spiked triple digits this week before being halted on the London Metal Exchange, one of the most extreme moves ever seen in the metal markets. On Tuesday morning, three-month contract prices more than doubled to over $100,000 per ton. Even though there are other steel and iron producing players in the global economy, such as the U.S., Japan and Germany, there are no practical alternatives to Russia for nickel, underscoring its drastic price compared to other commodities, according to Atlantic Council. , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Morgan Stanley estimates the spike in nickel prices could add an additional $1,000 to the price of electric vehicles.                                                                                                                                                                                                                                                                                                                                                                                                                          , Russia also supplies 35% of the world’s palladium, one of the main components in catalytic converters for both gasoline and diesel models, both of which account for the majority of car sales.                                                                                                                                                                                                                                                                                                                                                , CLICK HERE TO READ MORE ON FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 08:22:28 </td>
   <td style="text-align:left;"> US Futures Mixed as Indexes Head for Weekly Loss </td>
   <td style="text-align:left;"> US stock futures were mixed in Asian trade on Friday as the major indexes headed for a weekly loss, with another hot inflation print, prospects of higher interest rates and a failed first round of Russia-Ukraine talks weighing on sentiment. Dow futures fell 0.15%, S&amp;P 500 futures were flat and Nasdaq 100 futures rose 0.05%. Rivian shares fell 13% in after hours trading after missing revenue and earnings estimates, while DocuSign sank 18% after issuing a weak guidance. In regular trading on Thursday, the Dow lost 0.34%, the S&amp;P 500 fell 0.43% and the Nasdaq Composite dropped 0.95%. The annual inflation rate in the US accelerated to 7.9% in February, matching expectations but rising to a fresh 40-year high. The Federal Reserve is set to raise interest rates by 25 basis points at the March meeting, but Fed chair Jerome Powell opened the door for moving more aggressively down the line should high inflation persist. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/10/us/politics/biden-putin-inflation.html </td>
   <td style="text-align:left;"> 2022-03-11 08:11:42 </td>
   <td style="text-align:left;"> Biden Urges Americans to Blame Rising Prices on Putin. Many Do, for Now. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                         , News that inflation has hit a 40-year high is another blunt reminder of just how much the president is asking voters to sacrifice in an election year.                                                                                                                                                                                                                                                                                                               , By Katie Rogers and Michael D. Shear                                                                                                                                                                                                                                                                                                                                                                                                                                 , WASHINGTON — The price of gasoline has risen every day since Russia invaded Ukraine. Record-high inflation in the United States is causing sticker shock. And now, President Biden is blaming the pinch on Vladimir V. Putin, the Russian president.                                                                                                                                                                                                                 , “There will be costs at home as we impose crippling sanctions in response to Putin’s unprovoked war,” Mr. Biden said in a statement on Thursday.                                                                                                                                                                                                                                                                                                                     , The president is betting that Americans are willing to endure the financial pain that comes from waging an economic war with Russia. But Thursday’s news that inflation has hit a 40-year high is another blunt reminder of just how much he is asking voters to sacrifice in an election year.                                                                                                                                                                      , With the midterm elections eight months away, the urgent political question for Mr. Biden is whether the American people are prepared to go along with blaming the Russians, and not him, for rising costs. Experts have said that prices have risen over the past year primarily because strong demand, stoked in part by government relief spending, outstripped pandemic-disrupted supply. Russia’s invasion of Ukraine is just beginning to compound the problem., “It’s certainly a challenge, but it’s not one that we really have a choice about making,” Josh Schwerin, a Democratic strategist, said about imposing financial penalties on Russia. “There’s broad support for standing up to Putin and putting these sanctions in place, including those that will increase the cost of gas.”                                                                                                                                      , Mr. Biden’s approval ratings have been pulled down for months by frustration among many Americans about inflation and the pandemic. But recent surveys of voter attitudes suggest that many Democrats and Republicans support the administration’s sanctions on Russia, even if the penalties are bad for their pocketbooks.                                                                                                                                         , In an Economist/YouGov poll released this week, 66 percent of Americans said they approved of sanctions aimed at punishing Russia for its invasion. In a Wall Street Journal survey, 79 percent of voters supported a ban on Russian oil even if it meant that energy prices would rise as a result.                                                                                                                                                                 , Those findings are good news for Mr. Biden, who has been the subject of Republican attacks for failing to keep inflation in check. Republicans have blamed him for the rise in gas prices even as they supported his decision to impose a ban on Russian oil.                                                                                                                                                                                                        , Officials familiar with his decision said Mr. Biden had struggled for days over whether to cut off Russian oil amid fears of accelerating the already rapid rise in the price of gasoline.                                                                                                                                                                                                                                                                           , Ronna McDaniel, the chairwoman of the Republican National Committee, accused the Biden administration on Thursday of refusing to take responsibility for rising costs.                                                                                                                                                                                                                                                                                               , “Prices continue to skyrocket under Biden and Democrats’ reckless policies,” Ms. McDaniel said in a statement. “Biden’s attempt to deflect blame is an insult to every American and small-business owner struggling to afford the cost of everyday goods.”                                                                                                                                                                                                           , Jen Psaki, the White House press secretary, told reporters on Thursday that there was “no question that inflation may be higher for the next few months than it would have been” without the Russian invasion of Ukraine, and that the administration’s focus would be to mitigate the long-term effects of rising costs.                                                                                                                                            , Democratic strategists pointed out that much of the criticism of Mr. Biden from Republicans is that he has not done even more to confront Russia. The president has repeatedly said he is unwilling to send American troops into Ukraine, and the United States declined this week to take fighter jets from Poland and station them at an American air base for eventual use in Ukraine.                                                                            , Each decision Mr. Biden is making, the strategists from his party argue, is rooted in strategic decision making, not political calculation.                                                                                                                                                                                                                                                                                                                          , On the ground. As the war in Ukraine enters its third week, the Russian advance appears to have slowed. At the same time, destruction across Ukraine is growing, as Russia increases its targeting of residential areas and civilian infrastructure with long-range missiles.                                                                                                                                                                                        , No agreement. The Foreign Ministers of Ukraine and Russia met in Turkey, for the first time since the start of the war, and failed to stop the fighting. Foreign Minister Sergey V. Lavrov of Russia declared that a cease-fire was never up for discussion.                                                                                                                                                                                                         , Chernobyl nuclear facility. The International Atomic Energy Agency said that the defunct power plant had been disconnected from electricity, though there was no need for immediate alarm. A power loss could affect the facility’s ability to keep the water that cools radioactive material circulating and lead to safety issues.                                                                                                                                 , On the diplomatic front. Vice President Kamala Harris visited Poland, where she repeated U.S. pledges to “defend every inch of NATO territory,” while sidestepping questions about Poland’s offer, rejected by the Pentagon, to hand fighter jets over to the United States to transfer to Ukraine.                                                                                                                                                                  , “Being in the situation he’s in carries a kind of political freedom,” said David Axelrod, a former senior adviser to President Barack Obama. “Virtually every indicator is working against him relative to these midterm elections, and many of them are beyond anyone’s control. The best service that he can perform for himself, for Democrats, is to be intrepid and as strong and as honest as he can be about the situation we’re in.”                         , Biden administration officials have tried to emphasize economic gains, including a streak of strong job growth that persisted even during the latest wave of coronavirus cases. Just last week, Mr. Biden used his State of the Union address to try to refocus the nation on how far the economy has come since the recession caused by the pandemic, and he called fighting inflation his “top priority.”                                                          , The Labor Department reported last week that American employers had added 678,000 jobs in February and that the unemployment rate had fallen to 3.8 percent, its lowest level since the start of the pandemic. Still, Treasury Secretary Janet L. Yellen acknowledged on Thursday that despite economic progress in the United States, inflation continued to be a challenge.                                                                                        , “I don’t want to say that inflation is not a problem,” Ms. Yellen said at an event held by The Washington Post. “Inflation is a problem.”                                                                                                                                                                                                                                                                                                                            , Ms. Yellen noted that Russia’s war in Ukraine was driving up oil prices and causing gasoline prices in the United States to rise sharply. She said the Biden administration was working to insulate American consumers from the impact of the sanctions, but she did not elaborate on any new measures to lower gas prices.                                                                                                                                          , Ms. Yellen pointed to Biden administration policies to reduce the cost of child care and elder care as longer-term remedies for rising prices. She said that in the near term, it would be the responsibility of the Federal Reserve to combat inflation.                                                                                                                                                                                                            , “Inflation is first and foremost the job of the Federal Reserve,” Ms. Yellen said. “We have to look at the Federal Reserve to take steps to bring down inflation and I have confidence the Fed will take the actions that are needed.”                                                                                                                                                                                                                               , Alan Rappeport and Jeanna Smialek contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60381024?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-11 08:09:13 </td>
   <td style="text-align:left;"> Does your boss really care what you think? </td>
   <td style="text-align:left;"> Cato Syversen runs a sober and serious business, providing credit ratings information.                                                                                                                                                                                                                                      , But to keep the 1,300 staff at his firm Creditsafe amused and engaged during the pandemic he revealed his lighter side.                                                                                                                                                                                                     , Working from home during Covid spurred the company to buy software that allowed staff to run their own media operation.                                                                                                                                                                                                     , Mr Syversen joined in with a stint as a DJ and also donned a false moustache and suit to play Ron Burgundy, the title character from the movie, Anchorman.                                                                                                                                                                  , The Norwegian finance executive has embraced these challenges. "I'm an old punk rocker. I wanted to be a rock star, this is a good second."                                                                                                                                                                                 , When Mr Syversen turned to LiveTiles, software that allows a workforce to build their own videos and podcasts together online, he knew what he did not want to see.                                                                                                                                                         , "I did not want a company intranet because in my experience they are boring."                                                                                                                                                                                                                                               , According to him, Creditsafe's employees leapt at the chance to be creative and break the monotony of working from home be creating their own news desk, including Mr Syversen's Anchorman impression, and Safe FM, an internal radio station with studio guests and podcasts.                                              , The videos contain footage of work Christmas parties in Italy or Sweden, tips to beat the January blues, advice and insights from colleagues. And it can get very personal, with staff paying respects to deceased colleagues.                                                                                              , Mr Syversen had wanted to get this kind of informal network up and running before the pandemic, but he discovered that dedicated software was the missing ingredient. "We had something we made ourselves and it was rubbish!"                                                                                              , His first reaction to the pandemic scattering his workforce back to their homes, was to email a daily newsletter around the company. But that didn't strike the right, informal note he was looking for. Freeing up his staff to do their own thing has worked, he insists.                                                 , "Things like seeing the faces of people in other countries, it's not easy to get that sense of belonging. Normally we have a big party every five years, everyone gets together, but not this time."                                                                                                                        , Creditsafe's staff have risen to the opportunity he says. "I like the way they pay attention and share things, like tips on how to use the features of Teams."                                                                                                                                                              , Gothenburg-based employee, Camilla Emring puts it like this: "I feel people open their hearts up more than they would in the queue at the coffee machine."                                                                                                                                                                  , Bringing some lightness to the workplace is probably not a bad idea. But how does an employer find out if their efforts are making any difference?                                                                                                                                                                          , One way to test the water is to use software that canvasses staff sentiment.                                                                                                                                                                                                                                                , Sarah Marrs is an occupational psychologist with Qualtrics. She ensures that the right questions are posed to employees to gauge their true feelings.                                                                                                                                                                       , Employees of a business using Qualtrics's software see a series of statements such as "I feel as if I belong at this company" and rate their level of agreement or disagreement with it. These responses are fed into a dashboard, lighting up indicators of a workforce's emotional state.                                 , More technology of business:                                                                                                                                                                                                                                                                                                , The company says that more businesses were monitoring how employee sentiment shifted during lockdowns, with tools like surveys, because unhappy staff were voting with their feet.                                                                                                                                          , This exodus has been tagged as the Great Resignation by some, with some parts of the workforce reassessing their values and shifting to completely different careers and others retiring early.                                                                                                                             , A A global survey of 14,000 employees by Qualtrics indicated that 35% have plans to move jobs this year.                                                                                                                                                                                                                    , However, not everyone sees this online interaction as a positive. Bogdan Costea left his native Romania to attend a conference at Lancaster University in the UK in 1992 and never left. He found a niche at the university, studying the nature of work and is now a Professor of Management and Society.                  , Professor Costea thinks that feedback from a workforce is not the treasure trove that some view it as. "We have become enthralled by data, as if the more we collect, the more truth comes out. So, there are so many software packages that gauge employee sentiment and claim to allow individual expressions of opinion.", However, he warns that this kind of employee canvassing can lure individuals into a sense that they need to justify their own role.                                                                                                                                                                                         , "After the first three months of working from home during the pandemic, people began to overwork because they wanted to prove they were doing their job. Asking them to talk about how they feel can be dangerous because they may be reluctant to admit their vulnerabilities," he says.                                   , Andrew Pakes, deputy general secretary of professional workers union, Prospect, also has concerns and believes staff may worry about being judged.                                                                                                                                                                          , "Is there a league table? Can an employer use this technology to see the ten least engaged workers? What will that mean for them?"                                                                                                                                                                                          , Prospect is not opposed to this raft of opinion-seeking software, but fears that hitting icons on a screen is no real substitute for human judgement.                                                                                                                                                                       , "We'd like to see mental health becoming more central to management, not delegated to external products."                                                                                                                                                                                                                   , Back at Qualtrics, Ms Marrs understands these concerns but adds that from her experience it's important to remember that senior executives also have feelings invested in the feedback process. "Board members and chief executives take feedback very personally."                                                         , So, if anyone should be able to answer the question of whether your boss really cares what you think, Ms Marrs should. She pauses before replying. "I want to say 'yes', obviously, but the truth is that your employer cares about the bottom line. And, at the moment, employees have the power to stay or leave."        , Stacey Dooley meets victims and perpetrators of a crime that devastates lives                                                                                                                                                                                                                                               , Can aspiring musician Sasha break free from it?                                                                                                                                                                                                                                                                             , Louis Theroux explores the issue with consent in the industry                                                                                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60691719?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-11 08:04:09 </td>
   <td style="text-align:left;"> 'Our collapse would be catastrophic for the war' </td>
   <td style="text-align:left;"> The boss of one of Ukraine's biggest food producers said that if its operations fail, it would have a "catastrophic" impact on the army and the country's wider population.                                                                                                                                                         , MHP is a London listed poultry company with over 30,000 workers in Ukraine.                                                                                                                                                                                                                                                         , It is a big supplier to the Ukrainian military and has been involved in the humanitarian effort.                                                                                                                                                                                                                                    , It has delivered food to isolated communities across the country.                                                                                                                                                                                                                                                                   , These deliveries have often been undertaken for free and at great personal risk to MHP SE's employees.                                                                                                                                                                                                                              , The company's Australian chairman, Dr John Rich, has been running the company from its offices in Slovenia and said its survival is critical to the war effort.                                                                                                                                                                     , The implications of the firm failing in its production or distribution operations would have a "catastrophic effect" on the army and the war effort, Dr Rich explained.                                                                                                                                                             , This would also have an "enormous humanitarian effect" in Ukraine because MHP is last company standing in this area of food supply, according to Dr Rich.                                                                                                                                                                           , "A lot of our competitors, particularly in the east of the country, have ceased to exist", he explained.                                                                                                                                                                                                                            , Dr Rich said that the company is a critical food producer and distributor for the army.                                                                                                                                                                                                                                             , "You've got to put food in the army's belly, and protein in particular. If you don't do that, particularly in cold conditions, you have significant problems."                                                                                                                                                                      , MHP has thousands of vans at its disposal which has made it an important part of the humanitarian effort. Delivering it's own products and other aid has been particularly important for towns and villages that have become isolated following the invasion where Dr Rich said some people have spent up to five days without food., "We've been delivering ready to eat food, because people can't cook outside, and delivering to villages that have become cut off," Dr Rich said.                                                                                                                                                                                    , "At present, the company is operating like a war room. No question," he explained.                                                                                                                                                                                                                                                  , "Frankly the drivers going into those areas - It's like a suicide mission, particularly getting into the cities that have been under heavy attack."                                                                                                                                                                                 , "It's an enormous challenge for our staff and we have to try and incentivise people, pay them more, and guarantee to look after their family if something happens", he added.                                                                                                                                                       , In addition to its poultry operations, MHP has a major presence in the country's agriculture sector, growing wheat and grain on thousands of hectares of land.                                                                                                                                                                      , The firm is also a big exporter of sunflower oil, though the company's exports ground to a halt following the invasion.                                                                                                                                                                                                             , Both Ukraine and Russia are both major exporters of basic foodstuffs, and the war has already hit crop production, driving up prices.                                                                                                                                                                                               , On Monday, one of the world's biggest fertiliser firms, Yara International, warned that the war would deliver a shock to the global supply and cost of food.                                                                                                                                                                        , The next few weeks are critical for sowing wheat and other crops, and Dr Rich said the situation is on a knife edge. At the moment the firm has the ability to sow crops within two to three weeks but this could be impacted by the advances of the Russian army which have occupied 15% of the land so far, Dr Rich explained.    , "If this continues, of course our ability to sow rapidly diminishes, particularly if they (the Russian army) moves into the west of the country where a large part of our operations are based", he added.                                                                                                                          , Dr Rich said this could could lead to the complete failure of Ukraine to produce anything, but also has implications globally.                                                                                                                                                                                                      , "The consequences are unimaginable as far as Ukraine is concerned," he said.                                                                                                                                                                                                                                                        , "For the wider world, it's simple. The price of wheat will continue to rise, the price of corn and other commodities will rise significantly, and you'll have spiralling inflation at a time when we've already had problems with the global supply chain because of COVID," he added.                                              , The head of the World Food Programme, David Beasley, has also warned that the conflict in Ukraine could send global food prices soaring, with a catastrophic impact on the world's poorest.                                                                                                                                         , Analysts have forecasted that the war could even double global wheat prices.                                                                                                                                                                                                                                                        , MHP has appealed for donations to its charitable foundation so they can continue to distribute food. Dr Rich explained he was trying to cover the enormous costs of giving away poultry for free when the firm's input costs were "sky rocketing".                                                                                  , "We cant continue to exist like this without some sort of support. That's the reality."                                                                                                                                                                                                                                             , Stacey Dooley meets victims and perpetrators of a crime that devastates lives                                                                                                                                                                                                                                                       , Can aspiring musician Sasha break free from it?                                                                                                                                                                                                                                                                                     , Louis Theroux explores the issue with consent in the industry                                                                                                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60672278?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-11 08:01:28 </td>
   <td style="text-align:left;"> War in Ukraine: How Asian economies are divided over Russia sanctions </td>
   <td style="text-align:left;"> , Since its invasion of Ukraine, Russia has become the world's most sanctioned country. But only a few governments in Asia have taken tough action against Moscow.                                                                                                                                                                                     , China has refused to outright condemn the invasion of Ukraine and has not imposed any sanctions on Russia.                                                                                                                                                                                                                                           , India, Pakistan, Vietnam, Bangladesh, Sri Lanka, Laos and Mongolia also sat out the vote on a United Nations' resolution to demand the end of Russia's military operations in Ukraine.                                                                                                                                                               , While Western allies like Australia, Japan, South Korea and Taiwan have imposed sanctions, with Tokyo and Seoul blocking some Russian banks from the Swift global payments system, the impact is limited.                                                                                                                                            , That is because the Asian nations who joined western-led sanctions make up only 8% of Russia's global trade.                                                                                                                                                                                                                                         , "Without having the two Asian giants China and India on board on sanctions who account for 18% of Russia's trade, there is unlikely to be any significant impact on Russia," says Professor Syed Munir Khasru, chairman of the international think tank, the Institute for Policy, Advocacy, and Governance.                                         , And President Putin has been preparing in advance. Since Russia annexed Crimea eight years ago, Moscow has been targeted with Western sanctions.                                                                                                                                                                                                     , "After 2014, Russia started cutting down the reliance on US dollars as part of foreign currency reserve and moving to gold and the Chinese yuan," he adds.                                                                                                                                                                                           , For Beijing, it is about weighing up the benefits versus costs of not taking action against Russia.                                                                                                                                                                                                                                                  , China is already Russia's largest trading partner and in the weeks before the invasion, Beijing lifted restrictions on wheat imports and signed a 30-year deal to buy more Russian gas.                                                                                                                                                              , Meanwhile, an increasing number of Russian companies and banks, including the oil arm of Russian gas giant Gazprom, has started using China's currency, the yuan, in settlements.                                                                                                                                                                    , China has three objectives, according to Bilahari Kausikan, Singapore's former ambassador to the UN and Russia.                                                                                                                                                                                                                                      , Firstly, China is quite sensitive about certain principles of international relations, such as sovereignty, territorial integrity and non-interference because of Tibet, Xinjiang and Taiwan.                                                                                                                                                        , "Russia's invasion of Ukraine is a direct and gross violation of these norms but there is a second objective. China has no other partner, anywhere near the strategic weight of Russia," Mr Kausikan says.                                                                                                                                           , They also share a discomfort with a Western-dominated international order but Mr Kausikan adds that "China is much more invested in that order" and "the US, Europe and Japan are more important markets than Russia", which is why Beijing is keen to stabilise the situation in order to avoid becoming collateral damage of the Russian sanctions., This video can not be played                                                                                                                                                                                                                                                                                                                         , For India and Vietnam, Russia is their largest arms supplier while Pakistan's prime minister Imran Khan was in Moscow last month to discuss a major gas pipeline deal with President Putin.                                                                                                                                                          , "India has a very large stock of Soviet era weapons that it needs to keep operational," says Mr Kausikan. "And the reason he needs to keep them operational is China."                                                                                                                                                                               , Despite its strong ties with Russia however, India is also part of the US-led Quad with Japan and Australia, which is seen by many as an alliance against China's growing presence in the region.                                                                                                                                                    , "Whose side is India on?," tweeted the country's former ambassador to Russia, Pankaj Saran. "We are on our side."                                                                                                                                                                                                                                    , In many ways, that is how Asia's actions against Russia can be seen.                                                                                                                                                                                                                                                                                 , Governments here are no stranger to having to pick a side on anything from trade conflicts to human rights issues but they have invariably been pragmatic when it comes to economic issues.                                                                                                                                                          , "India, the largest democracy in the world, you would have expected it to have condemned the Russian invasion," says Professor Munir.                                                                                                                                                                                                                , "But nations are more driven by their own geopolitical and economic interests, and less by principles or respect for international norms."                                                                                                                                                                                                           , And the UN vote on condemning the invasion of Ukraine further highlight divisions in the region.                                                                                                                                                                                                                                                     , North Korea was one of the five countries - which unsurprisingly include Russia - to vote against the resolution.                                                                                                                                                                                                                                    , Myanmar voted to condemn Russia but that can be put down to its UN representative being part of its ousted government in exile. The country's military junta, which grabbed power last year, has been openly supportive of Russia, which continued to supply Yangon with weapons despite the coup.                                                   , Other smaller Asian economies find themselves caught between Russia, China and the West, according to Chong Ja Ian, an associate professor at the NUS Department of Political Science.                                                                                                                                                               , "In general, they avoid criticising major powers like China and Russia which they believe are likely to punish them," says Associate Professor Chong.                                                                                                                                                                                                , "There is recognition that Russian aggression is egregious and also challenges the institution of sovereignty on which they depend, so they choose to keep silent as they do not want to criticise Moscow but also do not support it," he adds.                                                                                                      , He points out that even among western allies, "South Korea is more cautious as they see a need to work with Russia on North Korea issues and because they are also cautious about crossing China unnecessarily".                                                                                                                                     , What worries Asian governments, many of which have territorial disputes with China, is that Beijing is seen as closely watching what happens in Ukraine for what it may or may not be able to achieve in future disputes.                                                                                                                            , "Most Asian countries want a Chinese presence in the Indo-Pacific balanced by the United States," says Manjari Chatterjee Miller, Senior Fellow for India, Pakistan and South Asia at Council on Foreign Relations.                                                                                                                                  , But she says that India and many South East Asian countries want Russia to play a balancing role when it comes to China.                                                                                                                                                                                                                             , While that explains why some countries have chosen not to outright condemn Russia, the flip side is: what lessons could China draw from the Russian invasion?                                                                                                                                                                                        , "What would it spell to China if Russia was unable to be constrained? If sanctions didn't work? What would that mean for Chinese encroachment in the Indo-Pacific or for the future of Taiwan?"                                                                                                                                                      , Where it is going to get tricky, she says, is as oil prices go up, the invasion drags on, and the atrocities pile up, how long the fence sitters can stay silent.                                                                                                                                                                                    , Stacey Dooley meets victims and perpetrators of a crime that devastates lives                                                                                                                                                                                                                                                                        , Can aspiring musician Sasha break free from it?                                                                                                                                                                                                                                                                                                      , Louis Theroux explores the issue with consent in the industry                                                                                                                                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/peru/interest-rate </td>
   <td style="text-align:left;"> 2022-03-11 07:51:05 </td>
   <td style="text-align:left;"> Peru Lifts Key Rate to 4% to Curb Inflation </td>
   <td style="text-align:left;"> Peru’s central bank decided to raise the policy rate for an eight straight month by 50 basis points to 4% on Mar. 10, in line with expectations as it seeks to curb inflation even before the Russia-Ukraine war aggravated global food and energy inflation shocks. Peru’s annual inflation hit a 13-year high in December, and last month stood at 6.2%, still more than triple the 2% mid-point of the bank’s target range. The bank said inflation won’t return to its target band until the first half of 2023, a shift from last month’s forecast for inflation to be back within range by the end of this year. “The board is especially attentive to new information regarding inflation and inflation expectations, and economic activity to consider, if needed, additional adjustments in the monetary stance to guarantee that inflation returns to target over the policy horizon,” the bank said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/household-spending </td>
   <td style="text-align:left;"> 2022-03-11 07:45:18 </td>
   <td style="text-align:left;"> Japan Personal Spending Rebounds More than Expected </td>
   <td style="text-align:left;"> Household spending in Japan increased by 6.9% in real terms from the prior year in January 2022, easily beating market forecasts of 3.6 percent and reversing from a 0.2% fall a month earlier. This was the first rise in personal spending since last July and the strongest pace in eight months, as consumption recovered following soaring vaccinations. Consumption bounced back for food (0.2% vs -1.8% in December), culture &amp; recreation (4.8% vs -2.7%), furniture (2.8% vs -11.7%), and medical care (8.8% vs -0.4%), amid a strong pickup in spending for housing (13.4% vs 4.2%), clothing (5.9% vs 1.7%), and transport (32.2% vs 13.4%). In contrast, there were declines in spending of both fuel, light &amp; water charges (-3.4% vs -6.4%) and education (-3.9% vs 17.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-03-11 07:09:09 </td>
   <td style="text-align:left;"> Stock futures are flat as Dow heads for fifth straight losing week amid Russia-Ukraine war </td>
   <td style="text-align:left;"> , Stock futures were flat ahead of Friday's session as the Dow Jones Industrial Average headed for its fifth losing week in a row amid Russia's invasion of Ukraine.                                                                                                                                                                          , Futures on the Dow Jones Industrial Average rose 50 points. S&amp;P 500 futures rose 0.2% and Nasdaq 100 futures were little unchanged.                                                                                                                                                                                                         , The Dow Jones Industrial Average dipped 112.18 points to 33,174.07 during regular trading on Thursday, after climbing more than 650 points in the previous session, while the S&amp;P 500 shed 0.4%. The technology-heavy Nasdaq Composite dropped 1% to 13,129.96, led by losses from Apple and Meta Platforms.                                , Week to date, the Dow is down 1.31% and headed for its fifth negative week in a row since May 2019. Meanwhile, the S&amp;P is down 1.60% and Nasdaq 1.38% this week.                                                                                                                                                                            , The losses came as negotiations between Russia and Ukraine came to a halt without progress on a cease-fire or passage for civilians attempting to flee the city of Mariupol. The markets have fluctuated in recent weeks as investors weigh the fallout of the conflict between Russia and Ukraine.                                         , Meanwhile, oil prices, which have been volatile amid the conflict, fell again on Thursday with West Texas Intermediate crude sliding to roughly $106 per barrel. Brent crude oil fell 1% to about $109 per barrel. Commodities including gold and silver which have rallied amid the war in Ukraine settled up 0.61% and 1.70% respectively., Wall Street banks name the most exposed global stocks to the Russia-Ukraine conflict                                                                                                                                                                                                                                                        , Fundstrat's Tom Lee sees stocks shaking off rough start and rallying nearly 20% by the end of 2022                                                                                                                                                                                                                                          , After Amazon's split, here's who could be next, according to Bank of America                                                                                                                                                                                                                                                                , "History from an investment point of view is on our side for the long-term," Stephanie Link, Hightower's chief investment strategist told CNBC's "Closing Bell" on Thursday. "The market can recover, and I think eventually we will. We'll have to see how long this goes but eventually, the market will recover."                        , Thursday's inflation report showed the consumer price index reach 7.9% in February, a fresh 40-year high. That was slightly higher than the expected 7.8% for the year, according to Dow Jones estimates. CPI gained month-over-month 0.8%, above estimates of 0.7% for the month.                                                          , Shares of Rivian slipped more than 11% in extended trading after missing estimates for the fourth quarter on the top and bottom lines, while DocuSign sank 18% after issuing weak guidance for the first quarter and fiscal year.                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/food-inflation </td>
   <td style="text-align:left;"> 2022-03-11 06:59:00 </td>
   <td style="text-align:left;"> New Zealand Food Inflation Surpasses 10-Year High </td>
   <td style="text-align:left;"> Food prices in New Zealand increased 6.8 percent year-on-year in February of 2022, accelerating from the 5.9 percent increase in the previous month for the highest reading since July of 2011. Costs rose the most for fruit and vegetables (17 percent), meat, poultry, and fish (7.1 percent), and restaurant and ready-to-eat foods (5.2 percent). On a seasonally adjusted monthly basis, food costs edged 0.1 percent higher from a 1.1 percent gain in January, largely due to restaurant and ready-to-eat-meals (0.3 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 06:48:00 </td>
   <td style="text-align:left;"> Brazilian Equities Close Below the Flatline </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Ibovespa, partially pared earlier losses and closed 0.2% lower at 113,663 on Thursday, as another round of Ukraine-Russia talks failed to make progress while investors weighed on lower commodity prices, principally oil. Domestically, Embraer (-14.9%) led the losses after the aircraft manufacturer lowered its financial guidance for 2022. Meanwhile, Brazilian state-run oil company Petrobras (2.8%) announced it will raise gasoline prices by 18% and diesel by 25% at the refinery gate starting Friday as global oil quotes surged following Russia's invasion of Ukraine. On the economic data front, Brazil's economy added fewer jobs than expected in January; while monthly retail sales recovered more than expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-03-11 06:26:00 </td>
   <td style="text-align:left;"> New Zealand Factory Growth Picks Up in February </td>
   <td style="text-align:left;"> The BusinessNZ Performance of Manufacturing Index in New Zealand rose to 53.6 in February of 2022, picking up from the upwardly revised 52.3 in the prior month and coming above the long term average of 53.1. It was the sixth consecutive month of expansion in the country’s factory sector, lifted by higher levels of production (52.1 vs 51.1 in January), new orders (58.2 vs 53.6), and employment (51.7 vs 49.5), while finished stocks levels remained constant (50 vs 52.5). “Underlying unease will certainly be piqued by the sustained high COVID case numbers as we go into March. The next PMI result may also see fallout from the Russia/Ukraine conflict, whose global impacts will be felt far and wide”, BNZ Senior Economist, Craig Ebert stated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/stocks-making-the-biggest-moves-after-hours-rivian-oracle-and-more.html </td>
   <td style="text-align:left;"> 2022-03-11 06:19:55 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Rivian, Oracle, DocuSign and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                          , Check out the companies making headlines after the bell:                                                                                                                                                                                                                                                                                                                                                 , Rivian — The electric vehicle company's stock sank 12% postmarket on Thursday after missing estimates on the top and bottom lines for the fourth quarter as it grapples with supply chain disruptions. Rivian reported a loss of $2.43 per share on revenue of $54 million, while analysts surveyed by Refinitiv expected a loss of $1.97 per share on revenues of $60 million.                          , Oracle — Shares of Oracle slipped 5% in extended trading Thursday after the company met revenue but missed earnings expectations for the third quarter. The company reported earnings per share of $1.13 on revenues of $10.51 billion. Analysts surveyed by Refinitiv expected earnings of $1.18 per share on revenues of $10.51 billion. The company also said two investments led to a drop in income., DocuSign — DocuSign plummeted 18% during extended trading on Thursday after issuing weak revenue guidance for the first quarter and fiscal year. The e-signature software maker beat analysts' expectations on the top and bottom lines for the fourth quarter and announced a $200 million stock buyback.                                                                                               , Ulta Beauty — Shares of the retailer rose more than 1% in extended trading after beating revenue estimates for the fourth quarter. The company reported revenues of $2.73 billion, while analysts polled by Refinitiv expected $2.69 billion.                                                                                                                                                            , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 06:10:05 </td>
   <td style="text-align:left;"> Canadian Stocks Close Higher </td>
   <td style="text-align:left;"> Canada’s S&amp;P/TSX Composite Index closed 0.4% higher at a one-month high of 21,582 on Thursday, over-performing its North American counterparts amid strong performances from the energy sector and other commodity-backed stocks. Canadian Natural Resources (3.4%) led the gains among the blue chips, while Vermilion Energy closed nearly 5% higher. At the same time, Canadian National Railway gained 2.9% after J.P. Morgan analysts confirmed the title of “neutral”. On the other hand, projections of tighter monetary policy after the publication of US consumer prices led tech stocks to fall 2.1%, led by Shopify (-5.9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/jpmorgan-says-labor-shortage-requires-unconventional-hiring.html </td>
   <td style="text-align:left;"> 2022-03-11 05:53:47 </td>
   <td style="text-align:left;"> JPMorgan says labor shortage requires unconventional hiring, including people with criminal records </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                           , JPMorgan Chase says that companies can deal with global labor shortages in part by tapping the neurodiverse and people with criminal backgrounds.                                                                                                                                                                         , The New York-based bank has hired thousands of people with criminal records and hundreds of people with autism or other conditions, Brian Lamb, JPMorgan's global head of diversity, equity and inclusion, said Thursday during CNBC's Equity and Opportunity forum.                                                      , "There's a labor shortage, I think we're all experiencing that globally," Lamb told CNBC's Sharon Epperson. "It's going to require unconventional approaches" to hiring, he said.                                                                                                                                         , People with criminal backgrounds can face barriers to employment, said Lamb. The bank, which had 271,025 employees as of year end 2021, has eliminated questions about criminal records from initial job applications, he said. The bank has also linked up with external partners on resume and career coaching services., "We're hiring thousands of individuals with criminal backgrounds into the workplace at our firm," Lamb said. "That is another specific example of what we're doing to make progress around tapping into the talent pools that have historically been left behind."                                                        , JPMorgan has also established a pipeline for candidates with disabilities including autism in nine countries, according to Lamb.                                                                                                                                                                                          , "These partners help us identify, select and assess talent that we can move into these programs, hundreds of individuals that we believe can go into over 40 roles across JPMorgan Chase," he said.                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/yellen-says-further-sanctions-against/story.aspx?guid={1F878A82-D4F0-4611-9634-FAE7E1E3D875}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 05:50:44 </td>
   <td style="text-align:left;"> Yellen says further sanctions against Russia being considered - MarketWatch </td>
   <td style="text-align:left;"> U.S. Treasury Secretary Janet Yellen on Thursday said officials "will continue to consider and discuss further sanctions that will really deprive Russia of the resources that they need to conduct war." Speaking during a CNBC interview about the Western response to Russia’s invasion of Ukraine, she said: "We have put in place and could expand sanctions that make it extremely difficult for Russia, its government and its firms to access international capital." Yellen also said: "There's more that we can do, but what we've done has been devastating.", Prices are rising fast and inflation is squeezing family budgets, but a little perspective is in order                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-60700642?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-11 05:39:26 </td>
   <td style="text-align:left;"> Twitter blocks Russian claims on hospital attack </td>
   <td style="text-align:left;"> Twitter has removed two posts by the Russian embassy in London which claimed the bombing of a Ukrainian hospital by Russian forces had been faked.                                                                                                                                                                      , The Mariupol hospital was attacked on Wednesday, leaving three people dead.                                                                                                                                                                                                                                             , But the embassy's tweets made unfounded claims the hospital was not operational at the time, and that injured women pictured at the scene were actors.                                                                                                                                                                  , Twitter told the BBC the tweets violated rules "related to the denial of violent events".                                                                                                                                                                                                                               , Officials at the embassy have offered no proof to back up their claims, and the BBC's disinformation team has found evidence which contradicts the allegations.                                                                                                                                                         , The embassy claimed the hospital had been "long non-operational". However, a week-old post on the hospital's Facebook page asked for fuel to keep operations going.                                                                                                                                                     , Reports from Mariupol last week - from the Associated Press news agency and Sky News - also says it was treating bombing victims, and that the maternity ward had been moved to the basement.                                                                                                                           , The allegation that a beauty blogger was used to fake photos of a pregnant woman at the scene was also called into question, as the woman in question, who lives in the city, is seen heavily pregnant in Instagram posts dating from last month.                                                                       , The initial claims that the bombing was faked by Ukraine did not come from the embassy. They first began trending among Russian users of the Telegram messaging app earlier in the day, and were then mentioned on state television news bulletins and chat shows.                                                      , A further claim circulating that the beauty blogger also pretended to be another woman caught up in the bombing and photographed at the scene is also untrue. A look at high-resolution images of the other woman featured in the claims shows she looks nothing like the beauty blogger. Those are two different women., Finally there were accusations that the hospital had been taken over by a far-right battalion of the Ukrainian army. As yet there is no evidence that this was the case.                                                                                                                                                , These claims all continue to circulate online, despite the tweets being removed.                                                                                                                                                                                                                                        , The pregnant beauty blogger's Instagram account has also now become a target for online trolls and conspiracy theorists.                                                                                                                                                                                                , Social media companies have been trying to tackle misinformation on their platforms, with many big tech companies blocking Russian broadcasters RT and Sputnik.                                                                                                                                                         , But Twitter has not banned several accounts linked to Russian government organisations - including Vladimir Putin's official Twitter account.                                                                                                                                                                           , The Russian embassy account also remains active.                                                                                                                                                                                                                                                                        , Stacey Dooley meets victims and perpetrators of a crime that devastates lives                                                                                                                                                                                                                                           , Can aspiring musician Sasha break free from it?                                                                                                                                                                                                                                                                         , Louis Theroux explores the issue with consent in the industry                                                                                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-11 05:35:00 </td>
   <td style="text-align:left;"> Brent Futures Extend Decline from 14-Year High </td>
   <td style="text-align:left;"> Brent crude futures fell below $110 per barrel on Thursday, remaining highly volatile after declining over 13% in the previous session in its biggest one-day drop in two years, after the Kremlin pledged fulfil its contractual obligations. Investors reevaluated the extent of potential supply constraints after Russian President Putin ensured that Russia, responsible for 7% of global oil and 1/3 of Europe’s gas, would continue to meet its energy sale commitments. Elsewhere, UAE called on its peers to raise output levels to ease the global energy crunch. OPEC and Chevron had already said there is no shortage of oil and Iraq insisted there is no need to ramp up production more than planned. UK oil futures hit their highest level since 2008 at above $139 per barrel as the Russian invasion of Ukraine and ensuing sanctions exacerbated supply chain problems created by the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-11 05:32:00 </td>
   <td style="text-align:left;"> Oil Extends Decline after Wednesday's Selloff </td>
   <td style="text-align:left;"> WTI crude futures fell below $106 per barrel on Thursday, remaining highly volatile after losing over 12% in the previous session in its biggest one-day drop since November, after the Kremlin pledged to fulfil its contractual obligations. Investors reevaluated the extent of potential supply constraints after Russian President Putin ensured that Russia, responsible for 7% of global oil and 1/3 of Europe’s gas, would continue to meet its energy sale commitments. Elsewhere, UAE called on its peers to raise output levels to ease the global energy crunch. OPEC and Chevron had already said there is no shortage of oil and Iraq insisted there is no need to ramp up production more than planned. US oil futures hit their highest level since 2008 at above $130 per barrel early this week, as the Russian invasion and ensuing sanctions exacerbated supply chain problems created by the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/orcl:us </td>
   <td style="text-align:left;"> 2022-03-11 05:29:00 </td>
   <td style="text-align:left;"> Oracle earnings below expectations at 1.13 USD </td>
   <td style="text-align:left;"> Oracle (ORCL) released earnings per share at 1.13 USD, compared to market expectations of 1.17 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/blink-charging-falls-after-mixed/story.aspx?guid={6E6C6824-1D8B-4E8F-8B58-30518E4B50E4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 05:21:35 </td>
   <td style="text-align:left;"> Blink Charging falls after mixed quarterly results - MarketWatch </td>
   <td style="text-align:left;"> Shares of Blink Charging Co. 
        BLNK,
        -1.26%
       fell more than 7% in the late session Thursday after the EV-charging provider reported a fourth-quarter loss that was wider than Wall Street expected, but sales came in above estimates. Blink said it lost $19 million, or 45 cents a  share, in the quarter, compared with a loss of $7.9 million, or 24 cents a share, in the fourth quarter of 2020. Revenue rose to $7.95 million from $2.45 million a year ago, the company said. Analysts polled by FactSet expected Blink to report a loss of 39 cents a share on sales of $6.2 million.  "We have seen strong momentum throughout the year, which reflects not only the growing market recognition for our EV charging technology, but also the increasing commitment from the business community as well as state and federal entities, to promote the establishment of reliable, convenient EV infrastructure nationwide," Chief Executive Michael D. Farkas said in a statement. Blink ended the regular trading day down 1.3%. , Rising interest rates, inflation and the Russia-Ukraine conflict have sapped some investors' willingness to hold high-growth stocks.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 05:06:55 </td>
   <td style="text-align:left;"> US Stocks End in Negative Territory </td>
   <td style="text-align:left;"> Major US stock indices closed lower on Thursday, after having booked significant gains in the prior session, as investors swung back to a risk-off mood amid the war in Ukraine, rising inflation, and prospects of higher interest rates. The annual inflation rate in the US accelerated to 7.9% in February of 2022, the highest since January of 1982 but matching market expectations. Higher price figures came along with a disappointing US jobless claims report, which in turn, eased some concerns about an aggressive monetary tightening. The Dow lost 113 points to close at 33,173, while the S&amp;P 500 and the Nasdaq 100 dropped 0.4% and 1.1%, respectively. Goldman Sachs fell over 1% after becoming one of the first major investment banks to exit Russia, where it has an estimated USD 940 million in total exposure. On the other hand, Amazon shares gained 5.4% after announcing a 20-for-1 stock split and a USD 10 billion buyback. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60691688?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-11 05:06:16 </td>
   <td style="text-align:left;"> Goldman Sachs and Western Union pull out of Russia </td>
   <td style="text-align:left;"> Goldman Sachs has said it will close its operations in Russia, becoming the first Wall Street bank to pull out of the country in response to the invasion of Ukraine.                                                                                            , Money transfer giant Western Union has also said it will suspend operations in Russia and Belarus.                                                                                                                                                               , The firms join a rush of global brands halting operations in Russia.                                                                                                                                                                                             , Earlier on Thursday, the owner of Uniqlo made a U-turn and decided to suspend operations in the country.                                                                                                                                                         , Operating in Moscow has been increasingly difficult for Western financial institutions and other firms amid international sanctions against Russia.                                                                                                              , More than 330 firms have withdrawn or significantly curtailed operations in the country in recent days, according to Yale researchers, who have been tracking the corporate response.                                                                            , On Thursday, Goldman Sachs said it would be "winding down" its business in Russia rather than leaving immediately.                                                                                                                                               , The bank said it was doing so "in compliance with regulatory and licensing requirements".                                                                                                                                                                        , At the end of 2021, Goldman Sachs' total credit exposure in Russia was $650m (£496m).                                                                                                                                                                            , Later Thursday, fellow Wall Street giant JP Morgan Chase also said it was "actively unwinding Russian business", with activities focused on taking care of staff and helping global clients manage risk and close out obligations.                               , Meanwhile Western Union said it "stands with the world in condemning the unprovoked and unjustified invasion of Ukraine".                                                                                                                                        , "Ultimately, in light of the ongoing tragic impact of Russia's prolonged assault on Ukraine, we have arrived at the decision to suspend our operations in Russia and Belarus," the company said.                                                                 , The action is a further blow to flows of money in Russia. Western Union provides international money transfer and payments services in more than 200 countries and 130 currencies.                                                                               , In an interview with the BBC published today, Ukrainain Central Bank Governor Kyrylo Shevchenko had called on Western Union to "cease deliveries of cash to Russian and Belarusian banks."                                                                       , Earlier on Thursday, Uniqlo owner Fast Retailing said it had decided to change its stance on continuing trading in Russia.                                                                                                                                       , It said it was faced with "operational challenges" due to the "worsening of the conflict situation" after Russia's invasion of Ukraine.                                                                                                                          , Earlier in the week it had said it would keep its Russian shops open, saying that clothing is a "necessity of life".                                                                                                                                             , But in its latest statement, it said Uniqlo could "no longer proceed" in Russia.                                                                                                                                                                                 , "Uniqlo has made everyday clothing available to the general public in Russia," it said.                                                                                                                                                                          , "However, we have recently faced a number of difficulties, including operational challenges and the worsening of the conflict situation. For this reason, we will temporarily suspend our operations."                                                           , Among the latest wave of companies to call a halt to trading or pull back from investing in Russia, Rio Tinto became the first major mining company to cut ties with Russian businesses, while Japan's Sony and Nintendo suspended deliveries of gaming consoles., The world's biggest insurance broker, New York-listed Marsh McLennan, also announced it would exit Russia on Thursday. Ownership of its Russian businesses will be transferred to local management that will be independently operated, the group said.          , Japanese firm Hitachi said it would stop exports and cease most operations in Russia except for vital electrical power facilities, following similar moves by US companies such as Caterpillar.                                                                  , "We took multiple factors including the supply chain situation into account," a Hitachi spokesperson said.                                                                                                                                                       , Ukraine's Vice Prime Minister Mykhailo Fedorov had been urging the suspension.                                                                                                                                                                                   , Entertainment giant Sony, which had already stopped releasing films in Russia, suspended the launch of racing game "Gran Turismo 7".                                                                                                                             , Food companies Nestle, Mondelez, Procter &amp; Gamble and Unilever have halted investment in Russia, but said they would continue providing essentials.                                                                                                              , McDonald's said on Tuesday that it would temporarily close its 847 Russian outlets.                                                                                                                                                                              , The fast food giant has said that the move, which includes continuing to pay its 62,000 staff and restaurant employees in Russia, will cost about $50m (£38m) a month.                                                                                           , "This is a really challenging and complex situation for a global company like us," said chief financial officer Kevin Ozan.                                                                                                                                      , A number of other US food retailers, including Starbucks, PepsiCo and Coca-Cola Co, have said they will stop some or all business in Russia following the Ukraine invasion.                                                                                      , Meanwhile Burger King has suspended all of its corporate support, marketing and investment in Russia. But as its Russian outlets are fully franchised, many will remain open as they are managed by local franchisees.                                           , On Thursday, Russia's Izvestia newspaper reported that the Russian government had put together a list of about 60 foreign companies that could be nationalised in response to the suspension of operations.                                                      , It said firms including Apple, Ikea, Microsoft, IBM, Shell, McDonald's, Porsche, Toyota and H&amp;M could have their accounts and assets seized, and "external management" brought in, BBC News Moscow producer Will Vernon said.                                    , It is unclear how the nationalised companies would be able to sell the products associated with those firms.                                                                                                                                                     , In response to Western sanctions, Russia has imposed export bans on a string of products until the end of 2022.                                                                                                                                                  , The ban covers exports of telecoms, medical, vehicle, agricultural, and electrical equipment, as well as some forestry products such as timber.                                                                                                                  , Meanwhile in the UK, the CBI business lobby group called for government support as Western economies cope with the repercussions from Russia's invasion of Ukraine.                                                                                              , The CBI said it "fully supports" the sanctions that have been placed on Russia "despite their cost".                                                                                                                                                             , But its director general Tony Danker said the UK government must help businesses cope with the fallout such as rising energy costs and inflation as well as any impact on investment.                                                                            , He said the UK and other countries "now need to confront the economic consequences of unwinding from Russia".                                                                                                                                                    , The CBI wants the government to "fast-track progress on some of the big policy issues and help firms invest".                                                                                                                                                    , Mr Danker called for an acceleration of renewable energy and government support on energy bills, especially for energy intensive industries.                                                                                                                     , He also asked for the UK government "to stand behind domestic oil and gas in our energy transition" while the country should also "identify new trading partners" for minerals and other commodities, and enhance cyber security.                                , Stacey Dooley meets victims and perpetrators of a crime that devastates lives                                                                                                                                                                                    , Can aspiring musician Sasha break free from it?                                                                                                                                                                                                                  , Louis Theroux explores the issue with consent in the industry                                                                                                                                                                                                    , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/jpmorgan-actively-unwinding-russian-business/story.aspx?guid={B1E9E71D-3C22-49AB-B634-5177E44FB1C9}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 05:05:28 </td>
   <td style="text-align:left;"> JPMorgan 'actively unwinding' Russian business - MarketWatch </td>
   <td style="text-align:left;"> JPMorgan Chase &amp; Co. 
        JPM,
        -1.18%
       said Thursday it is actively unwinding its Russian business and it has not been pursuing any new business there, in compliance with directives by governments around the world. "Current activities are limited, including helping global clients address and close out pre-existing obligations; managing their Russian-related risk; acting as a custodian to our clients; and taking care of our employees," the bank said in an emailed statement. Shares of JPMorgan Chase, a component of the Dow Jones Industrial Average, fell 1.2% on Thursday, compared to a loss of 0.3% by the Dow Jones Industrial Average. 
 
, Ryan Coogler says the bank ‘worked with me and addressed it to my satisfaction,’ but, 'this situation never should have happened’                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/treasury-plans-new-actions-against/story.aspx?guid={63415829-0A77-42E0-BBB3-0D87F2467931}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 05:00:04 </td>
   <td style="text-align:left;"> Treasury plans new actions against North Korea after ballistic missile tests - MarketWatch </td>
   <td style="text-align:left;"> The U.S. Treasury Department plans to announce new actions on Friday that aim to prevent North Korea from accessing foreign items and technology that enable it to advance its prohibited weapons programs, a senior Biden administration told reporters on Thursday. The official said the actions come after the U.S. government concluded that North Korean ballistic missile tests on Feb. 26 and March 4 involved a relatively new intercontinental ballistic missile system that the isolated Asian nation is developing. Those tests represented a "serious escalation" by North Korea, though they didn't demonstrate "ICBM range or capability," the official said. The U.S. has ordered intensified intelligence surveillance and reconnaissance collection activities in the Yellow Sea, as well as "enhanced readiness" for ballistic missile defense forces in the region, the official added., Sergey Lavrov met his Ukrainian counterpart in Turkey on Thursday in the highest-level Russian-Ukrainian talks since the war began last month.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 04:30:20 </td>
   <td style="text-align:left;"> The Dow Jones Index decreasing 1.00% </td>
   <td style="text-align:left;"> United States Stock Market is falling 332 points. Losses were driven by Apple (-3.77%), Intel (-2.84%) and P&amp;G (-2.63%). Biggest rises came from Chevron (2.01%), Walmart (1.56%) and Dow Inc (0.75%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/jpmorgan-is-winding-down-its-russia-operations-amid-widening-business-exodus-over-ukraine-war.html </td>
   <td style="text-align:left;"> 2022-03-11 04:09:45 </td>
   <td style="text-align:left;"> JPMorgan is winding down its Russia operations amid widening business exodus over Ukraine war </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                  , JPMorgan Chase, the biggest U.S. bank by assets, is stepping away from Russia.                                                                                                                                                                                                                                                                   , "In compliance with directives by governments around the world, we have been actively unwinding Russian business and have not been pursuing any new business in Russia," company spokeswoman Tasha Pelio said in an email.                                                                                                                       , The bank's dealings related to Russia were "limited" to "helping global clients address and close out pre-existing obligations; managing their Russian-related risk; acting as a custodian to our clients; and taking care of our employees," she added.                                                                                         , The Russian invasion of Ukraine has prompted global technology, payments and retail companies to recoil from Russia amid U.S. sanctions aimed at applying economic pressure on the country. JPMorgan's move, reported earlier by Bloomberg, follows the announcement earlier Thursday that Goldman Sachs was exiting its business in the country., JPMorgan has fewer than 200 employees in Russia, working mostly in the firm's corporate and investment bank, according to the company.                                                                                                                                                                                                           , Watch: PIMCO stands to lose billions if Russia defaults on its debt                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-post-second/story.aspx?guid={E19E23A9-C94C-485F-80AA-FD171F8368D6}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 03:52:38 </td>
   <td style="text-align:left;"> U.S. oil futures post a second straight session decline - MarketWatch </td>
   <td style="text-align:left;"> Oil futures declined for a second straight session on Thursday, with prices giving up earlier gains in volatile trading against a backdrop of changing headlines on the Russia-Ukraine war. West Texas Intermediate crude for April delivery 
        CLJ22,
        +1.55%
       fell $2.68, or 2.5%, to settle at $106.02 a barrel on the New York Mercantile Exchange, after losing just over 12% on Wednesday. The settlement was the lowest for a front-month contract since March 1, according to Dow Jones Market Data., Optimism over an end to the war in Eastern Europe fades as diplomats from Russia and Ukraine fail to agree on a cease-fire. U.S. inflation hit a 40-year high.                                                                                                                                                                                                                                                                                                                                                                    , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/crypto-poses-serious-401k-risks-biden-administration-warns.html </td>
   <td style="text-align:left;"> 2022-03-11 03:40:22 </td>
   <td style="text-align:left;"> Crypto poses serious 401(k) risks, Biden administration warns </td>
   <td style="text-align:left;"> , Cryptocurrencies, such as bitcoin and other digital assets like non-fungible tokens, pose "significant risks and challenges" to 401(k) investors, including fraud, theft and financial loss, the U.S. Department of Labor said Thursday.                                                                                                                                   , The labor agency warned that employers that add crypto investments to their company 401(k) plans may easily run afoul of their legal obligations to workers who are plan participants.                                                                                                                                                                                     , That counsel comes as financial services firms have begun marketing such investments as retirement-plan options in recent months, playing off growing popularity, the bureau said.                                                                                                                                                                                         , More from Personal Finance:Here's what to know about managing your debt in retirementRetirees likely shielded from inflation hit on some expenses'Nowhere to hide' for consumers as inflation hits food, gas, housing                                                                                                                                                      , "At this early stage in the history of cryptocurrencies ... the U.S. Department of Labor has serious concerns about plans' decisions to expose participants to direct investments in cryptocurrencies or related products, such as NFTs, coins and crypto assets," Ali Khawar, acting assistant secretary at the Employee Benefits Security Administration, wrote Thursday., Employers who offer a 401(k) plan have a fiduciary duty relative to the investments they make available. That legal duty requires them to prudently select investments and monitor them on an ongoing basis.                                                                                                                                                               , This duty has been the crux of a flurry of 401(k) lawsuits filed over the past decade or so, which have alleged workers lost money due to excessive costs and losses from unwise fund choices.                                                                                                                                                                             , Relative to crypto in 401(k) plans, the Labor Department outlined several risks and challenges in a compliance memo on Thursday.                                                                                                                                                                                                                                           , Crypto is speculative, volatile and hard to value, and it may be challenging for investors to make an informed investment decision, according to the bureau. Other properties — like losing the asset forever in the event of forgetting a password — also pose hazards, the agency said.                                                                                  , Regulation may also change swiftly, the Labor Department said. President Joe Biden on Wednesday issued an executive order calling on the government to examine crypto's risks and benefits. However, many crypto proponents viewed the order positively.                                                                                                                   , "The big question coming into the executive order was whether it was going to be balanced, whether it was going to talk about both the risks and the opportunities of crypto," Matt Hougan, chief investment officer at Bitwise Asset Management, told CNBC. "It's pretty close to the outcome we were all hoping for."                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                           , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/epa-chief-denies-biden-admin-discouraging-investment-u-s-energy-production </td>
   <td style="text-align:left;"> 2022-03-11 03:35:21 </td>
   <td style="text-align:left;"> EPA chief denies Biden admin discouraging investment in U.S. energy production </td>
   <td style="text-align:left;"> FOX Business asks EPA Administrator Michael Regan about allegations that the Biden administration is discouraging investment in US energy.                                                                                                                                                                                                                                                                                                                                                          , Environment Protection Agency Administrator Michael Regan Thursday denied that the Biden administration is discouraging investment in U.S. oil and gas development, as energy industry representatives and Republicans politicians say it's doing just that.                                                                                                                                                                                                                                        , "I think that 90% of the natural gas extraction in this country is done on non-federal lands, and that continues to move forward," Regan said when asked about those accusations. "It's indicative of our methane proposal that we're taking a look and we're talking with industry. And there are tons of technologies available that would allow this industry to continue to help transition this country while getting significant reductions from methane and other hazardous air pollutants." , Michael Regan, administrator of the U.S. Environmental Protection Agency (EPA), speaks during the 2022 CERAWeek by S&amp;P Global conference in Houston, Texas, U.S., on Thursday, March 10, 2022. (Photographer: F. Carter Smith/Bloomberg via Getty Imag (Photographer: F. Carter Smith/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                    , Regan made the comments during press briefing at CERAWeek by S&amp;P Global energy conference. He said that private industry is behind green energy, noting that the vast majority of new U.S. energy generation capacity coming online "is renewable – wind, solar and battery."                                                                                                                                                                                                                       , RUSSIA-UKRAINE WAR SHOWS WORLD ‘VERY DEPENDENT ON CARBON,’ RENEWABLES ‘NOT READY YET,’ RUBENSTEIN SAYS                                                                                                                                                                                                                                                                                                                                                                                              , "I think this president is very smartly focused on a transition that is just and equitable but also that is cognizant of the state of play in the world," Regan added. "We all want affordable, reliable energy and electricity. And I think the smart regulatory approaches that really capture where the private sector has been going for the last decade is the right way to go."                                                                                                               , Energy industry insiders at the CERAWeek conference in Houston, however, said part of the reason why new oil and natural gas production is difficult is because of tone coming from Biden officials.                                                                                                                                                                                                                                                                                                , "The exploration and production sector has been hard hit," Port of Corpus Christi CEO Sean Strawbridge told FOX Business. He said Biden's "climate agenda... really took aim at the oil and gas sector," causing, "the subsequent flight of capital from the sector, which has made it more difficult for reinvestment in exploration and production."                                                                                                                                              , US BARRELING TOWARD RECESSION, EXPERTS SAY, AS INFLATION HITS 40-YEAR HIGH                                                                                                                                                                                                                                                                                                                                                                                                                          , Sen. Dan Sullivan, R-Alaska, also said specific Biden officials are discouraging investors from putting capital into domestic energy projects.                                                                                                                                                                                                                                                                                                                                                      , Senator Dan Sullivan, a Republican from Alaska, speaks during the 2022 CERAWeek by S&amp;P Global conference in Houston, Texas, U.S., on Monday, March 7, 2022. (Photographer: F. Carter Smith/Bloomberg via Getty Images) (Photographer: F. Carter Smith/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                    , "You have people like [Special Presidential Envoy for Climate] John Kerry and [National Climate Advisor] Gina McCarthy going around in the American financial community saying, 'Don't invest in American energy,'" he said.                                                                                                                                                                                                                                                                        , New York University professor Steven Koonin, who wrote a 2021 book challenging the idea that climate change will cause catastrophic consequences, said he welcomed a message from Energy Secretary Jennifer Granholm for energy companies to start "producing more right now." But, he told FOX Business, "I think she needs to be talking to her colleagues in Treasury, the SEC and so on to make sure that in fact, they stop discouraging investments."                                         , Jennifer Granholm, U.S. energy secretary, speaks during the 2022 CERAWeek by S&amp;P Global conference in Houston, Texas, U.S., on Wednesday, March 9, 2022.  (Photographer: Aaron M. Sprecher/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                               , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                         , "There's a lack of investment," Energy Workforce and Technology Council CEO Leslie Beyer said. "We need capital to be able to develop these assets. And certainly while that is the choice of the investors, the rhetoric coming from the administration and everything that's anti-fossil fuel informs those choices." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/draftkings-stock-sinks-near-2-year/story.aspx?guid={651F25AE-1E77-4683-9AA1-CD550D18CA57}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 03:22:29 </td>
   <td style="text-align:left;"> DraftKings stock sinks to near 2-year low, as sellers aren't regretting their decision yet - MarketWatch </td>
   <td style="text-align:left;"> Share of DraftKings Inc. 
        DKNG,
        -1.12%
       dropped 3.2% in afternoon trading Thursday, putting them on track for the lowest close since April 2020. The digital sports entertainment and gaming company's stock is now below the 2 1/2-week low close of $17.38 on March 8, which followed a 26.6% tumbled amid a six-day losing streak. It was after that close that Chief Executive Jason Robins tweeted that he was "on a mission" to make sellers of the stock "regret that decision more than any other decision you've ever made in your lift." The stock has now plunged 43.4% over the past three months, and had plummeted 75.2% over the past 12 months, while the S&amp;P 500 
        SPX,
        -0.43%
       has declined 9.8% the past three months and gained 9.1% over the past year., Optimism over an end to the war in Eastern Europe fades as diplomats from Russia and Ukraine fail to agree on a cease-fire. U.S. inflation hit a 40-year high.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/10/politics/us-patriot-missile-defense-system-explainer/index.html </td>
   <td style="text-align:left;"> 2022-03-11 03:19:25 </td>
   <td style="text-align:left;"> These are the missile defense systems the US sent to Poland - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)The two missile defense systems that the US delivered to Poland this week are part of a weapons system upon which the US military has heavily relied for nearly 40 years.                                                                                                                                                                                                                                                                                    , The deployment, announced Thursday by Vice President Kamala Harris, is intended to deter Russia and boost Poland's security amid western concerns that the Ukraine conflict could spill into NATO-aligned nations.                                                                                                                                                                                                                                                 , The Patriot air defense missile system -- Patriot stands for "Phased Array Tracking Radar to Intercept of Target" -- is designed to counter and destroy incoming short-range ballistic missiles, advanced aircraft and cruise missiles.                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The battery includes missiles and launching stations, a radar set that detects and tracks targets, and an engagement control station, according to the Missile Defense Advocacy Alliance.                                                                                                                                                                                                                                                                          , The US, seeking to avoid direct involvement in Ukraine -- which is not a member of NATO and therefore not subject to the pact's collective defense agreement, in which an attack on one aligned nation is considered an attack on all -- has repeatedly stressed that the deployment is only for defensive purposes.                                                                                                                                               , "This defensive deployment is being conducted proactively to counter any potential threat to U.S. and Allied forces and NATO territory," Capt. Adam Miller, spokesman for US European Command, said in a statement Tuesday. "This is a prudent force protection measure that underpins our commitment to Article Five and will in no way support any offensive operations."                                                                                        , The Pentagon's deployment of the Patriot missiles to Poland "wasn't precipitated by one single moment or one single issue or one single act by the Russians," US Defense Department press secretary John Kirby said on Wednesday.                                                                                                                                                                                                                                  , The Patriot missiles had been moved from Germany for what Kirby described as a "temporary deployment."                                                                                                                                                                                                                                                                                                                                                             , Retired US Army Gen. Wesley Clark, a former NATO commander, called the deployment of the two batteries "prudent" and said the Patriot system would be able to intercept many of the missiles Russian President Vladimir Putin has deployed in Russia and Belarus, which borders Poland.                                                                                                                                                                            , "So if there were to be a launch in some provocative way by Mr. Putin to attempt to intimidate us, these missiles have a very good probability of intercepting a Russian missile," Clark, now a CNN military analyst, told CNN's Brianna Keilar.                                                                                                                                                                                                                   , He added that the deployment of the equipment "gives reassurance to the Poles. It also tells Putin that he's not going to be necessarily so successful in trying to blackmail us with nuclear weapons."                                                                                                                                                                                                                                                            , A longtime mainstay of US military operations                                                                                                                                                                                                                                                                                                                                                                                                                      , The Patriot missile system has undergone several improvements and upgrades since it was first deployed in 1982. Its first combat use was in the Gulf War, which was also the first time that an air defense system had destroyed a hostile tactical ballistic missile. The Patriot system was also deployed in 2003 during Operation Iraqi Freedom and was successful in hitting nine incoming missiles, but also were involved in several friendly fire incidents., In recent years, the US has sent Patriot missiles to Saudi Arabia and Iraq to counter threats posed by Iran and its proxies and to the Pacific region to deter North Korea.                                                                                                                                                                                                                                                                                        , Earlier this year, the US military, along with the United Arab Emirates, used the Patriot missiles to intercept attacks by Houthi militants on a military airbase where Americans were stationed and while the Israeli President was visiting the UAE.                                                                                                                                                                                                             , A 2019 Pentagon missile defense review reported that eight battalions with 33 batteries were stationed in the United States while seven battalions with 27 batteries were stationed overseas. More than a dozen US allies, including Germany, Japan, and Israel, have also purchased the US missile defense system.                                                                                                                                                , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-budget-value </td>
   <td style="text-align:left;"> 2022-03-11 03:07:00 </td>
   <td style="text-align:left;"> US Budget Deficit Narrows Less than Expected </td>
   <td style="text-align:left;"> The US budget deficit narrowed to USD 217 billion in February of 2022 from the USD 311 billion gap in the same period last year, well above market expectations of a USD 49.5 billion deficit. Still, it was the highest deficit since July of 2021. Receipts totaled USD 290 billion, 17 percent lower than the record high for a February posted in 2021, as a result of the economic recovery efforts from the pandemic. At the same time, outlays were down by 9 percent to USD 506 billion as a result of lower unemployment compensation and less pandemic benefits. The total deficit for the first five months of the fiscal year totaled USD 476 billion, the Treasury said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nickel </td>
   <td style="text-align:left;"> 2022-03-11 03:06:51 </td>
   <td style="text-align:left;"> Nickel Prices Remain Near All-Time High </td>
   <td style="text-align:left;"> Nickel prices stabilized around $48,000 per tonne after briefly topping the $100,000 mark for the first time on record on March 8th and forcing the London Metal Exchange to halt trading after the brokers were struggling to pay margin calls. As a result, the LME said it would cancel all nickel transactions that had taken place on March 8th and after restarting, trading will only happen in European hours and with a 10% daily limit on price moves. Western sanctions against Russia over its invasion of Ukraine sparked concerns over the metal supply. Russia accounts for about 10% of the global nickel supply, mainly for use in stainless steel and electric vehicle batteries. Nickel was already rallying before Russia’s invasion of Ukraine as robust demand from the stainless steel and battery industry drained inventories, which now stand at 76,830 tonnes in LME-registered warehouses, their lowest since 2019. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-03-11 02:57:00 </td>
   <td style="text-align:left;"> Heating Oil Futures Extend Decline </td>
   <td style="text-align:left;"> Heating oil futures traded lower at $3.3 per gallon, declining from the record-high of $4.7 touched on March 9th and remaining highly volatile as traders reassessed the extent of potential supply concerns. Despite import bans from the US in retaliation to Russia’s invasion of Ukraine, the Kremlin pledged to fulfil its contractual energy supply obligations, while OPEC member UAE called on its peers to raise output levels to ease the global energy crunch. Meanwhile, domestic stocks of distillates, which include heating oil, shrank by 5.2 million barrels last week, much more than market expectations of a 1.9 million barrel draw. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/psaki-pressed-temporary-inflation-how-long </td>
   <td style="text-align:left;"> 2022-03-11 02:52:15 </td>
   <td style="text-align:left;"> Psaki pressed on how long 'temporary' inflation actually will be </td>
   <td style="text-align:left;"> FOX Business’ Stuart Varney argues the Biden administration have ‘no answer’ to the inflation problem which they ‘largely created.’                                                                                                                                                                                                     , White House press secretary Jen Psaki was pressed Friday about just how long Americans can expect high inflation to continue.                                                                                                                                                                                                           , Psaki told reporters that gas prices are expected to continue surging in the coming months due in large part to the ongoing Russian invasion of Ukraine. Psaki communicated that White House experts expect the markets to eventually stabilize and inflation to slow, saying the energy crisis is only "temporary."                    , However, when Fox News' Peter Doocy pressed Psaki on how long "temporary" actually means, she demurred.                                                                                                                                                                                                                                 , LIVE UPDATES: STOCKS FALL, INFLATION JUMPS 7.9%, GAS HITS NEW HIGH                                                                                                                                                                                                                                                                      , "We rely on the assessment of the Federal Reserve and outside economic analysts who give an assessment of how long it will last. The expectations and their assessment at this point is that it will moderate at the end of the year," Psaki said.                                                                                      , "There is also no question that when a foreign dictator invades a foreign country, and when that foreign dictator is the head of a country that is the third-largest supplier of oil in the world, that is going to have an impact. And it is."                                                                                         , White House press secretary Jen Psaki said Friday that inflation should "moderate" by the end of the year.  (Drew Angerer/Getty Images)                                                                                                                                                                                                 , Psaki was further pressed on blaming Russia for the inflation crisis and Democrats' insistence that the U.S. economic downturn is a direct result of Russia ahead of the midterms, Psaki pushed back, saying, "Well we've seen the price of gas go up at least 75 cents since President Putin lined up troops on the border of Ukraine.", Inflation hit a 40-year high in February, and the worst is yet to come as the U.S. economy barrels toward a recession, experts say.                                                                                                                                                                                                     , The consumer price index (CPI) climbed 7.9% on an annual basis, according to data released Thursday by the Bureau of Labor Statistics. Month over month, inflation rose 0.8%.                                                                                                                                                           , Gas jumped 6.6% in February and accounted for almost a third of price hikes. Food rose by 1%.                                                                                                                                                                                                                                           , The February data does not include Russia’s war on Ukraine, which has accelerated the rise in gas prices. As of Thursday, the U.S. national average hit a record high of $4.35 per gallon.                                                                                                                                              , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                 , Geltrude &amp; Co. founder Dan Geltrude told FOX Business he thinks gas prices will hit $5 this month and that it could even go as high as $10 unless the Biden administration expands domestic oil production.                                                                                                                             , White House press secretary Jennifer Psaki faced questions about how long high inflation will continue.  (Saul Loeb/AFP via Getty Images / Getty Images)                                                                                                                                                                                , "It would not surprise me," he said. "So until the United States decides, or this administration decides, that we are going to pump more oil, it is not going to change. It's not. Fuel costs are just going to continue to rise."                                                                                                      , Geltrude said the U.S. is on track to enter a full-blown recession within the year.                                                                                                                                                                                                                                                     , FOX Business' Jessica Chasmar contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-transports-rally-defy-broader/story.aspx?guid={BE5D558F-638C-4D7B-8136-59217896DFE2}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 02:49:25 </td>
   <td style="text-align:left;"> Dow transports rally, to defy broader stock market selloff - MarketWatch </td>
   <td style="text-align:left;"> The Dow Jones Transportation Average 
        DJT,
        +1.18%
       is rallying Thursday, even as most of its components are falling, as the economically sensitive index is defying the selloff in the broader stock market. The index is up 0.5% in afternoon trading with 9 of 20 components rising, while its sister index, the Dow Jones Industrial Average 
        DJIA,
        -0.34%
       sank 335 points, or 1.0%, with just seven of 30 components risingh, and the S&amp;P 500 
        SPX,
        -0.43%
       dove 1.2%. Within the Dow transports, the biggest gainers were shares of diesel engine maker Kirby Corp. 
        KEX,
        +2.76%,
       up 2.8%, and railroad operators Norfolk Southern Corp. 
        NSC,
        +2.30%,
       up 2.3%, and Union Pacific Corp. 
        UNP,
        +2.36%,
       up 2.2%. Meanwhile, the transports' decliners were led by the 1.4% drop in air carrier Delta Air Lines Inc.'s stock 
        DAL,
        -0.64%
       and the 1.3% drop in truck rental company Ryder System Inc.'s stock 
        R,
        -0.82%.
        , Rising interest rates, inflation and the Russia-Ukraine conflict have sapped some investors' willingness to hold high-growth stocks.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-prices-settle-back-above/story.aspx?guid={8C0D2BC5-8943-44ED-8BDB-20AA7D586D42}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 02:40:19 </td>
   <td style="text-align:left;"> Gold prices settle back above $2,000 an ounce - MarketWatch </td>
   <td style="text-align:left;"> Gold futures resumed their climb on Thursday, a day after posting the first loss in five sessions. The precious metal once again climbed above $2,000, with the rise attributable to the Russia-Ukraine war and reports of zero progress towards an end of the conflict, said Jeff Wright, chief investment officer at Wolfpack Capital. Gold should hold "very solid and credible support" for a safe-haven in the war, as "markets are fixated on each headline," he said. However, "gold will need to attract fresh capital and interest if [it] is to hold elevated levels over the longer run." April gold 
        GCJ22,
        -0.16%
       rose $12.20, or 0.6%, to settle at $2,000.40 an ounce. Prices fell Wednesday, but ended Tuesday at a 19-month high., Employees of SE Ranking, the Silicon Valley company whose chief accountant is the first known tech worker to be killed in Russia's invasion of Ukraine, want Tatiana Perebeinis to be remembered as more than a statistic, a co-worker told MarketWatch on Wednesday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/10/investing/banks-russia-exposure/index.html </td>
   <td style="text-align:left;"> 2022-03-11 02:25:41 </td>
   <td style="text-align:left;"> Russia owes Western banks $120 billion. They won't get it back - CNN </td>
   <td style="text-align:left;"> London (CNN Business)Goldman Sachs is the first major Western bank to get out of Russia following the invasion of Ukraine. More are likely to follow at a cost of tens of billions of dollars.                                                                                                                                                                                                 , The Wall Street giant said Thursday that it is "winding down its business in Russia in compliance with regulatory and licensing requirements," a Goldman Sachs spokesperson said.                                                                                                                                                                                                              , The departure follows a scramble by Western banks to tally their exposure to Russia after President Vladimir Putin ordered the invasion of Ukraine, triggering punishing sanctions that cover most of the country's financial system, including its central bank and top commercial lenders — VTB and Sberbank.                                                                                , It also comes after a stampede of Western businesses out of just about every other sector of Russia's economy, and as ratings agencies warn that a Russian debt default is imminent.                                                                                                                                                                                                           , International banks are owed more than $121 billion by Russian entities, according to the Bank for International Settlements, which suspended Russia's membership on Thursday. European banks have over $84 billion total claims, with France, Italy and Austria the most exposed, and US banks owed $14.7 billion.                                                                            , Goldman Sachs (GS) earlier disclosed that it had credit exposure to Russia of $650 million in December 2021.                                                                                                                                                                                                                                                                                   , Other banks with more to lose could soon follow Goldman Sachs out of Russia. Kremlin spokesperson Dmitry Peskov said Thursday that the economic situation in Russia is "absolutely unprecedented" and blamed the West for an "economic war." Moscow has pledged to retaliate for the sanctions, and some banks have suggested that their assets could be seized or nationalized by the Kremlin., Fitch Ratings warned previously that "large western European banks' asset quality will be pressured by the fallout from Russia's invasion of Ukraine," and that their operations also face increased risk as they race to comply with international sanctions.                                                                                                                                 , French bank Societe Generale (SCGLF) said last week it is "rigorously complying with all applicable laws and regulations and is diligently implementing the measures necessary to strictly enforce international sanctions as soon as they are made public."                                                                                                                                   , The bank said it had almost $21 billion in exposure to Russia at the end of last year.                                                                                                                                                                                                                                                                                                         , Societe Generale "has more than enough buffer to absorb the consequences of a potential extreme scenario, in which the group would be stripped of property rights to its banking assets in Russia," it said.                                                                                                                                                                                   , France's BNP Paribas (BNPQF) said on Wednesday that its exposure to both Russia and Ukraine totals €3 billion ($3.3 billion).                                                                                                                                                                                                                                                                  , Italy's UniCredit (UNCFF), which has been operating in Russia since 1989, said last week that its Russian arm was "very liquid and self-funded," and that the franchise accounts for just 3% of the bank's revenue. On Tuesday, it said that its exposure to Russia totals roughly €7.4 billion ($8.1 billion).                                                                                , Credit Suisse (CS) said Thursday that it has exposure to Russia of 1 billion Swiss francs ($1.1 billion).                                                                                                                                                                                                                                                                                      , Deutsche Bank (DB) said in a statement on Wednesday that it has "limited" exposure to Russia, with gross loan exposure of €1.4 billion ($1.5 billion). The German lender said it has significantly reduced its exposure to Russia since 2014, with further action taken over the past two weeks.                                                                                               , US banks could feel pain, too. Citigroup (C) disclosed last week that it had roughly $10 billion in total exposure to Russia.                                                                                                                                                                                                                                                                  , Mark Mason, the bank's chief financial officer, told investors that the bank has been performing tests to evaluate the consequences "under different stress type of scenarios." He said the bank could lose roughly half its exposure in a "severe" scenario.                                                                                                                                  , Citi said Wednesday that it would stick to its plan of exiting its consumer banking business — but it might be very hard to find a buyer given the political and economic climate.                                                                                                                                                                                                             , "As we work toward that exit, we are operating that business on a more limited basis given current circumstances and obligations," it said in a statement. "With the Russian economy in the process of being disconnected from the global financial system as a consequence of the invasion, we continue to assess our operations in the country," it added.                                   , The European Central Bank addressed the risk to the banking sector on Thursday, saying that Europe's financial system has enough liquidity and there were limited signs of stress.                                                                                                                                                                                                             , "Russia is important in terms of energy markets, in terms of commodity prices, but in terms of the exposure of the financial sector, of the European financial sector, Russia is not very relevant." said Luis de Guindos, vice president of the central bank.                                                                                                                                 , "The strains and the tensions that we have seen are not comparable at all to what happened at the beginning of the pandemic," he added.                                                                                                                                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/vita-coco-stock-slumps-freight/story.aspx?guid={E5EA8478-06D9-4863-B146-73B066E40E70}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 02:24:00 </td>
   <td style="text-align:left;"> Vita Coco stock slumps as freight costs take a toll - MarketWatch </td>
   <td style="text-align:left;"> Vita Coco Co. 
        COCO,
        -17.49%
       stock slumped 17% in Thursday trading after the coconut water maker swung to a fourth-quarter loss. Net loss totaled $3.4 million, or 6 cents per share, after net income of $17.1 million, or 29 cents per share, last year. "The decrease was primarily driven by a non-cash gain due to the revaluation of the contingent liability of $16 million related to our Runa brand which occurred in the fourth quarter of 2020," the company said in the earnings release. The per-share result was in line with the FactSet consensus. Sales of $86.6 million were up from $69.5 million last year. The FactSet consensus was for sales of $78.3 million. "Due to ocean freight service and cost challenges to the East Coast, our inventory is out of balance geographically," said Chief Executive Martin Roper in a statement. The company plans to further raise prices and reduce promotions in 2022, but even then, Roper says the actions "do not fully cover the inflationary transportation cost effects." Vita Coco stock began trading in Oct. 2021. Shares are down nearly 16% over the last three months while the S&amp;P 500 index 
        SPX,
        -0.43%
       is down 10.4%., This chart shows how the Batman movies and their Batmobiles match up --- and which actor was paid the most to play the Dark Knight.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/stocks-making-the-biggest-moves-midday-amazon-crowdstrike-micron-and-more-.html </td>
   <td style="text-align:left;"> 2022-03-11 02:22:58 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Amazon, CrowdStrike, Micron and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                        , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                            , Amazon — Amazon shares jumped 5.4% after the company said its board of directors has approved a 20-for-1 stock split, telling investors on Wednesday that they'll receive 20 shares for each share they currently own. The board also approved a $10 billion share buyback program.                                                                                                                                    , CrowdStrike — Shares for the cybersecurity company gained 12.5%, after it disclosed strong quarterly profit and revenue in its earnings report Wednesday. CrowdStrike also has an upbeat forecast for the 2023 fiscal year, saying it will pursue market share as cybersecurity concerns rise.                                                                                                                         , Asana — The collaboration software company's stock cratered 22.1%. On Wednesday, Asana forecast losses that were greater than analysts' expectations for the first quarter. The firm also announced a narrower-than-expected loss for its most recent quarter, as well as revenue that exceeded analysts' estimates.                                                                                                   , Genesco – Genesco shares soared 7.4%, as the footwear retailer reported better-than-expected quarterly revenue and profit. Same-store sales for the firm rose 10% and online sales spiked 36%, compared with the same year-ago period.                                                                                                                                                                                 , Baker Hughes, Halliburton, Chevron— The three energy companies rose together as a group, boosted by demand for greater energy production after the U.S. banned Russian oil. The number of oil rigs working dropped to 250 last year, from 1,077 in 2018, according to industry data from Baker Hughes. Oil field services companies Baker Hughes and Halliburton rose 8.7% and 8.9%, respectively. Chevron gained 2.7%., SolarEdge Technologies, Sunrun, Enphase — The three solar stocks declined as a group, after the sector rallied earlier in the week from rising oil and gas prices. SolarEdge slid 6.3%, Sunrun dipped 1.7%, and Enphase declined 0.6%.                                                                                                                                                                                 , Micron Technology, Advanced Micro Devices — Some semiconductor stocks dropped together. Micron Technology's stock tumbled 4.7%, and Advanced Micro Devices dropped 4.1%. Despite strong demand, chipmakers are facing supply chain issues for key materials stemming from the Russia-Ukraine conflict.                                                                                                                 , — CNBC's Tanaya Macheel contributed reporting.                                                                                                                                                                                                                                                                                                                                                                         , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/google-play-youtube-hit-pause/story.aspx?guid={9A23444C-51D3-4E54-8C9B-0BEB12108307}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-11 02:10:08 </td>
   <td style="text-align:left;"> Google Play, YouTube hit pause on payment-based services in Russia - MarketWatch </td>
   <td style="text-align:left;"> Google parent Alphabet Inc. 
        GOOGL
        GOOG
       on Thursday said it has suspended all payment-based services on YouTube and the Google Play store in Russia as Western sanctions deepen. Additionally, Google said it will pause ads for advertisers based in Russia. Google's move is the latest among U.S. companies in protest of Russia's invasion of Ukraine. Other companies to announce similar actions include Apple Inc. 
        AAPL,
       Meta Platforms Inc. 
        FB,
       Oracle Corp. 
        ORCL,
       McDonald's Corp. 
        MCD,
       Microsoft Corp. 
        MSFT,
       Exxon Mobil Corp. 
        XOM,
       Walt Disney Co. 
        DIS,
       Netflix Inc. 
        NFLX,
       Boeing Co. 
        BA,
       Ford Motor Co. 
        F,
       Airbnb Inc. 
        ABNB,
       Coca-Cola Co. 
        KO,
       Nike Inc. 
        NKE
       and Starbucks Corp. 
        SBUX.
      , Amazon.com Inc. is going to split its stock for the first time in more than 20 years, a period in which its shares have gained more than 4,500%, and expects to repurchase $10 billion in shares.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/pimco-faces-potential-losses-over-exposure-to-more-than-1-billion-in-russian-debt.html </td>
   <td style="text-align:left;"> 2022-03-11 02:03:29 </td>
   <td style="text-align:left;"> Pimco faces potential losses over exposure to more than $1 billion in Russian debt </td>
   <td style="text-align:left;"> , Pimco's billion-dollar exposure to Russian debt came under pressure as the country, which invaded its neighbor Ukraine amid international outrage, faces risk of a sovereign default.                                                                                                                                                                   , The asset manager's $140 billion Pimco Income Fund (PIMIX) held $1.14 billion worth of Russia government international bonds as of the end of 2021, according to the fund's annual report. The fund, co-run by chief investment officer Dan Ivascyn, also had written $942 million of credit-default swaps protection on Russia by the end of last year., These CDS enable investors to swap credit risk and Pimco, who sold these securities, will have to pay out should Russia default on its debt.                                                                                                                                                                                                            , The fund is off by 5.1% so far this year, slightly more than a Bloomberg benchmark bond index.                                                                                                                                                                                                                                                          , Pimco's Total Return bond fund and Emerging Markets bond fund also held similar positions tied to Russia.                                                                                                                                                                                                                                               , The Financial Times first reported on Pimco's Russia exposure earlier Thursday. Pimco declined to comment.                                                                                                                                                                                                                                              , These positions could inflict huge losses on Pimco as Russia could be edging closer to a sovereign debt default amid massive sanctions by the U.S. and other countries over the war in Ukraine.                                                                                                                                                         , Earlier this week, rating agency Fitch downgraded Russia's sovereign rating by six notches further into junk territory to a C grade, saying a default is "imminent."                                                                                                                                                                                    , Moody's and S&amp;P have also slashed the country's sovereign rating to "junk" status, saying Western sanctions could undermine Russia's ability to service its debt.                                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/theres-nowhere-to-hide-for-consumers-as-inflation-hits-food-gas-housing.html </td>
   <td style="text-align:left;"> 2022-03-11 01:50:46 </td>
   <td style="text-align:left;"> There is 'nowhere to hide’ for consumers as inflation hits food, gas, housing </td>
   <td style="text-align:left;"> , Consumer prices are rising at their fastest pace in decades — and that inflation has been most acute in household staple items like food, housing and transportation, making it hard to escape the budgetary sting.                                                                                                                                                   , The Consumer Price Index jumped 7.9% in February relative to a year earlier, the largest 12-month increase since January 1982, the U.S. Department of Labor said Thursday.                                                                                                                                                                                            , The index measures price fluctuations across a broad basket of goods and services. A $100 basket a year ago would cost $107.90 today.                                                                                                                                                                                                                                 , Shelter, gasoline and food were the largest contributors to the increase in overall prices in February, the Labor Department said. (The price index jumped by 0.8% over the month.)                                                                                                                                                                                   , These three categories were the three largest components of household budgets in 2020, respectively. Together, they accounted for 63% of total expenses, according to most recent Labor Department data.                                                                                                                                                              , "There's nowhere to hide," said Greg McBride, chief financial analyst for Bankrate. "This is hitting everybody."                                                                                                                                                                                                                                                      , Inflation "is most pronounced on items that are necessities," he added.                                                                                                                                                                                                                                                                                               , (Gasoline is part of the broader "transportation" category, which also includes public transit costs and vehicle purchases. Car sales have also spiked over the last year.)                                                                                                                                                                                           , More from Personal Finance:How to save money at the grocery store as food prices riseRetirees likely shielded from inflation hit on some expensesThe Great Resignation is still in full swing                                                                                                                                                                         , Of course, inflation doesn't impact all consumers equally. For example, a consumer who commutes by car and has to fill up a gas tank may feel higher prices more acutely than one who works from home or uses public transportation. And American workers have gotten big raises in the past year, reducing (though not always overriding) the sting of higher prices., The Federal Reserve is also expected to start raising interest rates next week in an attempt to tame inflation.                                                                                                                                                                                                                                                       , Household grocery bills swelled by 8.6% in the last 12 months, the largest jump since April 1981, according to the Labor Department.                                                                                                                                                                                                                                  , Costs for all major food groups increased in February; dairy and fruits and vegetables saw prices rise at their fastest monthly pace in over a decade.                                                                                                                                                                                                                , Gasoline price are up 38% in the last year. That statistic doesn't include the recent run-up due to Russia's invasion of Ukraine, which pushed prices at the pump to more than $4 a gallon, on average, on Sunday — the highest since 2008.                                                                                                                           , Overall energy costs (which include items beyond gasoline) are up the most since July 1981, on an annual basis.                                                                                                                                                                                                                                                       , Shelter costs like rents are up 4.7% in the last year, the most since May 1991. While that percentage increase was smaller than in other categories, housing costs account for more than a third of the average household budget — giving it an outsized dollar impact.                                                                                               , "That comparatively benign increase ... is likely to put the biggest squeeze on household budgets for the remainder of the year," McBride said.                                                                                                                                                                                                                       , A 5% increase in a $1,000-a-month apartment lease amounts to much more money than a 20% rise in something that costs $5, for example ($50 a month versus $1, respectively). And a lease locks in that price over a fixed term.                                                                                                                                        , Elevated inflation began emerging in spring 2021 as the U.S. economy came out of its pandemic hibernation.                                                                                                                                                                                                                                                            , Consumers had pent-up demand after staying home for months to reduce the spread of Covid-19. Households were flush with cash; they'd been unable to spend on things like entertainment and travel, and had savings from stimulus checks and enhanced unemployment benefits the federal government issued to prop up the economy.                                      , High consumer demand stressed supply lines already beleaguered by virus-related disruptions. Higher prices followed, though were initially concentrated in just a few categories. Many economists and federal officials thought the phenomenon would be temporary.                                                                                                    , However, inflation has persisted. Consumers may see costs rise even faster in the next few months, according to financial experts.                                                                                                                                                                                                                                    , That's likely to be true of gasoline and other categories negatively affected by the war in Ukraine. Further, the supply-chain snarl "may be worsened by prolonged economic consequences" of the conflict, according to Jason Pride, chief investment officer of private wealth at Philadelphia-based Glenmede Trust Company.                                         , He expects prices to rise at a more modest 4% to 5% annual rate by the end of 2022.                                                                                                                                                                                                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 01:22:00 </td>
   <td style="text-align:left;"> South African Stocks Rise for 2nd Day </td>
   <td style="text-align:left;"> The JSE FTSE All Share index extended gains into a second day and rose 1.7% to close at 73,889 on Thursday, supported by upbeat corporate earnings and strong manufacturing data. Sanlam, South Africa's largest non-bank financial services group, rose 3.6% after it said its operating profit was back at around 2019 levels, it had recovered to pre-pandemic performance on other metrics and annual profits rose 27%. Also, Pay-TV group MultiChoice surged 5.56% after its Nigerian business said it expects a $4.4 billion tax dispute to be resolved "very soon". On the domestic data front, factory output hit a 7-month high in January after falling 0.2% in December, while mining output rose by 0.1% in January compared to a 1% drop in the prior month. Meanwhile, concerns persisted over Russia's war against Ukraine and its impact on global inflation and growth.  Locally, investors feared rotational power cuts in South Africa would derail an economic recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 01:02:00 </td>
   <td style="text-align:left;"> Madrid Stocks Track European Peers Lower </td>
   <td style="text-align:left;"> The Ibex 35 index closed 1.2% down at 8,069 on Thursday, failing to continue yesterday’s record gains, in line with its European peers, after the ECB announced it will speed up the exit from its massive stimulus program, and as ceasefire talks between Moscow and Kyiv made no progress. At the same time, inflation in the US hit almost 8%, its highest in nearly 40 years, likely cementing the case for an interest rate hike by the US Federal Reserve. Among single stocks, the worst performers were Inditex (-4.7%), Siemens Gamesa (-4%), CIE Automotive (-3.6%) and Acerinox (-3.6%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 00:48:00 </td>
   <td style="text-align:left;"> Milan Shares Halt Recovery </td>
   <td style="text-align:left;"> The FTSE MIB index fell 4.2% to close at 22,886 on Thursday, following last session’s 7% jump as investors digested the ECB’s announcement that it will phase out net asset purchases by the third quarter, a faster rate than previously expected. Highly volatile commodity prices and projections of higher inflation pressured banks and consumer goods, with Intesa Sanpaolo (-7.6%), Bper Banca (-7.5%), and Azimut Holding (11%) leading the losses. On the data front, Italy’s producer inflation came at the record high of 32.9% for January, a 9.7% increase on the month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 00:47:00 </td>
   <td style="text-align:left;"> European Shares Fall Sharply </td>
   <td style="text-align:left;"> European equity markets fell sharply on Thursday, with Germany’s DAX down more than 3% as sentiment was rattled by the announcement of a possible early end of asset purchases by the ECB and little progress in diplomatic talks between Ukraine and Russia. Autos led losses with BMW and Volkswagen down more than 4.5%. On the earnings front, Hugo Boss reported profits of €144M in FY2021, switching from a €219M loss the year before. The pan-European Stoxx 600 lost almost 2%, after seeing the strongest rebound since March 2020 in the previous session. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Relapse on Thursday </td>
   <td style="text-align:left;"> The CAC 40 ended 2.83% lower to close at 6,207 on Thursday, tracking its European peers and in response to ECB’s accelerated asset purchase schedule, higher inflation outlook, and failure in peace-talks between Russia and Ukraine.The ECB president confirmed the end of the Pandemic Emergency Purchase Program (PEPP) by the end of this month while she also stated that the Euro area inflation could reach as high as 5.2% in 2022 compared to 3.1% projected earlier before stabilizing around 2% in 2023. At the same time, Russia-Ukraine failed to make any progress to end war on their first high-level peace talks in Turkey, which further raised fears of war-induced inflation. Declines were led primarily by banking and automotive stocks, with losses coming particularly from Credit Agricole (-7%), Valeo (-6%) and Societe Generale (-5.7%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/russia-ukraine-war-carbon-fossil-fuels-renewables-david-rubenstein-carlyle </td>
   <td style="text-align:left;"> 2022-03-11 00:45:26 </td>
   <td style="text-align:left;"> Russia-Ukraine war shows world 'very dependent on carbon,' renewables 'not ready yet,' Rubenstein says </td>
   <td style="text-align:left;"> Renewable energy "not ready yet," Carlyle Group co-chair David Rubenstein tells FOX Business at Houston's CERAWeek conference March 10, 2022.                                                                                                                                                                                                                      , HOUSTON – Russia's brutal war on Ukraine is causing many to concede that fossil fuels are here to stay for at least the immediate future, Carlyle Group cochairman David Rubenstein said Thursday.                                                                                                                                                                 , "The big lesson of Russia-Ukraine with respect to energy is we are still very dependent on carbon, Europe is still very dependent on carbon. And while everyone wants renewables and the environmental benefits from it, we still have a very small percentage of our global energy market really coming from renewables," Rubenstein told FOX Business.           , Carlyle Group co-founder David Rubenstein spoke with FOX Business at the CERAWeek conference in Houston, March 10, 2022. (FOX Business / FOXBusiness)                                                                                                                                                                                                              , RECORD GAS PRICES COULD BE HERE TO STAY, EXPERTS SAY: ‘DRIVEN BY EMOTION’                                                                                                                                                                                                                                                                                          , Rubenstein made the comments at the CERAWeek by S&amp;P Global energy conference in Houston.                                                                                                                                                                                                                                                                           , The annual gathering of global leaders in energy and government was roiled by Russian President Vladimir Putin's invasion of Ukraine, which has caused gas prices to spike to record highs as the West slaps massive sanctions on Russia. Those include a U.S. ban on imports of Russian oil.                                                                      , The Carlyle Group co-chairman, who previously worked in the Carter administration, added that green energy can't yet sustain the West in a situation like the Russia-Ukraine war.                                                                                                                                                                                  , Motorists wait in long lines for gas Tuesday, March 8, 2022, at Sam's Club in San Bernardino. (Will Lester/MediaNews Group/Inland Valley Daily Bulletin via Getty Images / Getty Images)                                                                                                                                                                           , ENERGY INDUSTRY SWIPES BACK AT PSAKI ‘RED HERRING’ COMMENT ON OIL AND GAS LEASES                                                                                                                                                                                                                                                                                   , "When there's a crisis you can't say, 'Let's get more renewables,' because it's not ready yet," he said. "So I think carbon is gonna be important for quite some time. I wish it wasn't the case, but it's the reality."                                                                                                                                           , Rubenstein added: "The big story at CERA this week is that basically people recognize that carbon is still a major factor in the global energy market. And while there's been more discussion on renewables over the last year than carbon, in truth, carbon energy is still here and we still are very dependent on it – and it's not gonna change any time soon.", In the interview with FOX Business Rubenstein also reflected on the "sad situation" of the Russia-Ukraine war. He said his ancestors came from Ukraine, just like many Americans.                                                                                                                                                                                  , Russian President Vladimir Putin attends a meeting in Moscow on Feb. 14, 2022. (Alexei Nikolsky/Sputnik/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                       , Rubinstein continued to laud how the West responded to the threat from Putin with a striking level of unity.                                                                                                                                                                                                                                                       , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                            , "The West has done more than anybody thought it would do, certainly more than Putin thought it would do, and I think Putin completely underestimated what the West has done," he said.                                                                                                                                                                             , "Could the West have done more before the invasion? Historians will debate that," he added. "But on the whole I think the administration should get high marks and NATO should for what it's done."                                                                                                                                                                , Rubenstein said because of the harsh sanctions, he expects that "Putin will ultimately blink" and look for an "off-ramp," even if that does not come until after weeks more of war.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-03-11 00:45:00 </td>
   <td style="text-align:left;"> UK Shares Fall on Thursday </td>
   <td style="text-align:left;"> The FTSE 100 index closed 1.5% lower at 7,080 on Thursday, partially trimming last session’s 3.3% gain, as market sentiment swung bank to risk-aversion when commodity prices treaded upwards once again. Renewed inflation concerns led banks and insurers to drop significantly, led by HSBC (-3.3%). Miners also underperformed, led by Anglo-Australian miner Rio Tinto (-5.7%) on news that it became the first big miner to cut ties with Russian businesses. Also, Evraz closed 10.7% down after being momentarily suspended from trading in the session, following the announcement of UK's sanctions on Russian oligarch Roman Abramovich, who owns 29% of the mining giant. Meanwhile, starting salaries for permanent staff in UK’s businesses rose at an unprecedented rate in February, as the labor market turns significantly tighter and costs of living increase. The upward pressure on wages adds further strength to rate hike bets by the Bank of England later this month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/inflation-out-of-control-when-economy-headed-towards-a-recession-kevin-hassett-warns </td>
   <td style="text-align:left;"> 2022-03-11 00:38:02 </td>
   <td style="text-align:left;"> Inflation 'out of control' when economy 'headed towards a recession,' Kevin Hassett warns </td>
   <td style="text-align:left;"> Former Chairman of the Council of Economic Advisers Kevin Hassett weighs in on the Labor Department's inflation report for February, noting that 'wages aren't keeping up with prices,' which means 'real incomes are going down.'                                                                                                                                                            , Former Chairman of the Council of Economic Advisers Kevin Hassett warned on Thursday that inflation is "out of control" at a time when the economy "is headed towards a recession."                                                                                                                                                                                                           , Hassett provided the insight on "Mornings with Maria" as he weighed in on the Labor Department's inflation report for February, which revealed that prices hit a fresh 40-year high last month, largely driven by higher gas prices.                                                                                                                                                          , The consumer price index climbed 7.9% on an annual basis, according to data released on Thursday by the Bureau of Labor Statistics. Month-over-month, inflation rose 0.8%.                                                                                                                                                                                                                    , The year-over-year reading is in-line with estimates and compares with an annual 7.5% jump in January, marking the fastest increase since February 1982, when inflation hit 7.6%.                                                                                                                                                                                                             , Gas jumped 6.6% in February and accounted for almost a third of price hikes. Food rose by 1%.                                                                                                                                                                                                                                                                                                 , INFLATION, HIRING SLAM SMALL BUSINESSES: NFIB                                                                                                                                                                                                                                                                                                                                                 , The February data does not include the Russia, Ukraine conflict which have pushed prices at the pump to $4.32 per AAA as of today, a record high.                                                                                                                                                                                                                                             , Hassett noted on Thursday, shortly after the release of the report, that "wages aren't keeping up with prices," which means "real incomes are going down."                                                                                                                                                                                                                                    , He warned that the next CPI report will reflect "way worse" data.                                                                                                                                                                                                                                                                                                                             , "The really, really big price spikes started to happen in March," Hassett told host Maria Bartiromo on Thursday.                                                                                                                                                                                                                                                                              , He also noted that there are so many "key things that affect the global economy that have been impacted by this war in Ukraine, like corn."                                                                                                                                                                                                                                                   , Ukraine is a leading producer and exporter of the commodity.                                                                                                                                                                                                                                                                                                                                  , Hassett went on to point out that "all that kind of stuff is going to make the March number way, way worse" than the February data.                                                                                                                                                                                                                                                           , The Schork Group principal Stephen Schork warns that the average price for gas 'is going to remain high' and notes that 'as offshoot, food prices have to remain high.'                                                                                                                                                                                                                       , "The Fed hasn’t even started tightening yet and we’ve got this runaway inflation and a weakening economy," he said, adding that he believes "first quarter GDP [gross domestic product] is looking like it’s going to be negative."                                                                                                                                                           , A recession refers to a contraction in GDP activity, or economic output, for two consecutive quarters.                                                                                                                                                                                                                                                                                        , Hassett argued that one reason why he believes "the odds of recession are getting above 50%, is that you got a couple negative quarters in a row, then you ‘re in a recession and the first quarter is low enough right now, in the real-time data that we have, that it’s plausibly negative or at least really close to zero and so that’s like the first half of the start of a recession.", GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                   , The real-time data set consists of snapshots of major macroeconomic variables and can be used by macroeconomic researchers to forecast, according to the Federal Reserve Bank of Philadelphia.                                                                                                                                                                                                , "I think it’s just we’re in Joe Biden’s economy right now and it is really, really terrible," Hassett went on to say, arguing that "as bad as the exit from Afghanistan was, what he [Biden] has done to economy is probably just as bad."                                                                                                                                                    , CLICK HERE TO READ MORE ON FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/corn </td>
   <td style="text-align:left;"> 2022-03-11 00:12:44 </td>
   <td style="text-align:left;"> Corn Hovers Around 10-Month High </td>
   <td style="text-align:left;"> Chicago corn futures traded close to a 10-month high of around $7.5 per bushel as Russia's invasion of Ukraine has limited supplies from two of the world's biggest exporting regions. Ukraine has suspended commercial shipping at its ports after Russian forces invaded the country, while grain trade from Russia paused as the West imposes fresh sanctions on Moscow. With the conflict likely to continue and workers delegated into the army, transport and logistics in chaos, prices have room for further upside momentum. Meanwhile, the USDA sees 2021/22 global corn ending stocks at 302.2 million, down 0.9 million from last month’s projections as production increases  in India partially offset the declines in Argentina and South Africa. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rice </td>
   <td style="text-align:left;"> 2022-03-11 00:11:00 </td>
   <td style="text-align:left;"> Rice Edges Down after USDA Report </td>
   <td style="text-align:left;"> Rice futures were trading around $15.4 per hundredweight, sliding slightly from a 20-month high $16.5 hit on March 4th on expectations of higher supply. The USDA sees world rice ending stocks at a record 190.5 million, up 4.2 million tons from February, as increased supplies from India and Thailand are set to offset a  rise in global consumption. Traders bet that rice may become a cheap alternative to wheat after global wheat supplies tightened amid war between Russia and Ukraine, the world’s two major wheat exporters. Also, the West’s trade sanctions on Russia are stopping the shipments of fertilizer from Russia pushing its prices higher. Rising costs for farmers could spur a lower fertilizer use, triggering lower crop yields and pushing up the rice prices even higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/10/ukraine-military-airstrike-russian-tanks-kyiv-nr-vpx.cnn </td>
   <td style="text-align:left;"> 2022-03-10 23:57:47 </td>
   <td style="text-align:left;"> Watch: Video appears to show Ukrainian airstrike on Russian tanks outside Kyiv - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/currency </td>
   <td style="text-align:left;"> 2022-03-10 23:56:00 </td>
   <td style="text-align:left;"> Hong Kong Dollar Hits 26-month Low </td>
   <td style="text-align:left;"> The Hong Kong dollar declined to as low as 7.8225 per greenback, a level not seen in over two years and passing the midpoint of its 7.75 to 7.85 allowed trading range against the US currency as ongoing tensions between the West and Russia over Ukraine hurt the appetite for risk assets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/10/business/private-equity.html </td>
   <td style="text-align:left;"> 2022-03-10 23:55:45 </td>
   <td style="text-align:left;"> Private Equity Is the New Financial Supermarket - The New York Times </td>
   <td style="text-align:left;"> , Private-equity firms were once niche players serving big clients. Now they’re trying to be everything to everyone.                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Credit...Igor Bastidas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , By Maureen Farrell                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Three decades ago, Jonathan Gray might have been an unlikely candidate to become Blackstone’s president and expected successor to its chief executive, Stephen A. Schwarzman.                                                                                                                                                                                                                                                                                                                                                                                         , Very little of Mr. Gray’s career at the private equity firm has involved leveraged buyouts — the aggressive deals, often involving large amounts of borrowed money and steep cost-cutting, that gave private equity its rapacious reputation. Instead, he has spent most of his time in Blackstone’s comparatively staid real estate business, helping the firm become one of the biggest property owners in the world.                                                                                                                                               , Mr. Gray’s elevation to president in 2018 reflected Blackstone’s growth into a behemoth with a hand in just about everything: mortgage lending, infrastructure, television and film studios, stakes in entertainment companies, pharmaceuticals, and even the dating app Bumble.                                                                                                                                                                                                                                                                                      , Blackstone is in the vanguard of an industry leaving its roots far behind. Since the 2008 financial crisis, it and its private equity rivals like Apollo Global Management, KKR and Carlyle have refashioned themselves into the supermarkets of the financial industry. They span areas of traditional finance long dominated by banks and investment categories typically dominated by hedge funds and venture capital.                                                                                                                                             , “Private equity firms are the financial conglomerates now,” said Richard Farley, a partner at the law firm Kramer Levin, who works on leveraged buyouts and lending.                                                                                                                                                                                                                                                                                                                                                                                                  , While money continues to pour into their investment funds from traditional clients like pension funds and retirement plans, private equity firms are not only buying up companies with investors’ money but also putting their own money on the line with new business ventures.                                                                                                                                                                                                                                                                                      , Globally, private equity firms managed $6.3 trillion in assets in 2021 — more than four times what they oversaw at the onset of the financial crisis in 2007, according to the data provider Preqin. Blackstone, the largest, told investors this year that it was on track to manage $1 trillion by the end of 2022 — four years ahead of its goal.                                                                                                                                                                                                                  , Even the term private equity is a misnomer, since many big firms are public. Over the past two years, shares of Blackstone are up more than 145 percent, while Apollo and Carlyle are up more than 85 percent and KKR is up about 130 percent. The S&amp;P 500 index, meanwhile, rose more than 55 percent. TPG — a rare company deciding to embark on an initial public offering in the midst of a down and volatile market — is trading only slightly below its January offer price.                                                                                    , The performance of their stocks is a sign of the prospects for growth, said Jim Zelter, an Apollo co-president. “Investors see the business model we’ve created as being at the intersection of companies who need to borrow and investors who need different choices,” he said.                                                                                                                                                                                                                                                                                      , The industry looks far different from its early days.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , In 1982, a private equity firm, Wesray, bought Gibson Greeting Cards, a unit of RCA, for roughly $80 million. Wesray’s two owners contributed just $1 million, using debt and the sale of Gibson’s real estate holdings to fund the rest. A year and a half later, they took the company public for $290 million, but first paid themselves a $900,000 special dividend.                                                                                                                                                                                              , Wall Street financiers were mesmerized by the nascent industry’s ability to create giant profits with very little money down, and over the next two and a half decades, more firms were built to race into these types of deals. Buyouts grew in size until the 2008 financial crisis — when many either fell apart as banks withdrew lending or produced abysmal returns. For many years, leveraged-buyout volume was less than half of what it was before the crisis, according to Dealogic data.                                                                   , But the crisis provided the industry with two key catalysts. First, record-low interest rates for more than a decade have pushed investors to seek out higher returns through riskier investments — particularly after the hits their portfolios took during the mortgage meltdown. Second, as government regulations forced banks to pull back from riskier areas including high-interest lending, private equity firms jumped into the mix.                                                                                                                         , “They’re opportunistic companies,” said Patrick Davitt, a senior analyst with Autonomous Research. “The large alternative asset managers have taken the opportunity to fill that white space left by banks.”                                                                                                                                                                                                                                                                                                                                                          , Apollo, for example, lends to medium and large corporations, but also makes loans for aircraft and mortgages. KKR has also built out its underwriting operation, allowing the industry to take a portion of the lucrative fees associated with pricing these deals.                                                                                                                                                                                                                                                                                                   , Mr. Gray said Blackstone and its rivals could make some lending activity cheaper and more efficient by lending directly, in contrast to the bank approach of syndicating a loan — essentially promising the money but finding others to provide it.                                                                                                                                                                                                                                                                                                                   , But in a hunt for more money to manage, private equity did more than offer a way to bypass banks. Firms became landlords, insurance providers and late-stage equity investors. In 2009, Apollo helped start Athene Holding, which sells retirement products such as annuities — a type of insurance designed to boost retirement savings — and reinvests the premiums Athene collects by selling those products. Other firms followed the same path; KKR bought a life insurance company last year for roughly $4.7 billion.                                          , As the real estate industry teetered after the mortgage crisis, Blackstone used its capital to buy up and rent housing and other real estate, amassing $280 billion in assets, which produce nearly half of the firm’s profits. As interest rates rise, Mr. Gray predicted, real estate will continue to help its performance. Rents in the United States, he noted, have recently risen at two to three times the rate of inflation.                                                                                                                                 , Blackstone also ramped up its business of taking stakes in fast-growing companies, including the women’s shapewear company Spanx and Reese Witherspoon’s media company Hello Sunshine. Its life sciences division has been buying pharmaceutical companies or stakes in them, and also pursuing drug development in cooperation with big drugmakers. And it plans to spend $1 billion to acquire rights to artists’ music through a partnership with Hipgnosis Song Management, which owns rights to the songs of Neil Young, Steve Winwood, Barry Manilow and others., But Mr. Gray said the biggest change for Blackstone had come as the firm realized it could attract clients outside the typical pool of large institutional investors it historically served.                                                                                                                                                                                                                                                                                                                                                                          , “Our industry historically catered to a fairly narrow audience of customers,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Big investors long leaned on a mix of stocks and bonds for reliable returns, and risked only a small slice of their holdings on private equity, which requires investors to commit money for five or 10 years on average. In return, the firms generally aimed for returns of 15 percent or more over longer horizons.                                                                                                                                                                                                                                                , But in recent years, Blackstone found that everyday investors could be lured by the potential for bigger returns than they might get elsewhere, Mr. Gray said.                                                                                                                                                                                                                                                                                                                                                                                                        , The sudden and synchronous growth of private equity’s business lines and client base has added to concerns about the sway of the so-called shadow banking industry, which also includes hedge funds and venture capital firms. The Securities and Exchange Commission is looking at new rules that would require such entities to disclose more information about holdings, fees and returns.                                                                                                                                                                         , While banks that are considered important to the financial system have faced stricter guidelines on lending and risk since the financial crisis — and try to avoid serious problems if a large number of companies were to suddenly default — private equity firms are lightly regulated, even though they don’t have the same governmental backstop. Some critics contend that the combination of more lending and fewer restrictions could rattle the economy if the firms’ bets go south.                                                                          , David Lowery, the head of research insights at Preqin, said private equity firms had been “very good” at selecting companies and avoiding defaults, but during a time of relative stability. “That strength will be tested,” he said.                                                                                                                                                                                                                                                                                                                                 , So far, the unbridled expansion has been good for business. Consider the eye-popping windfall received by Mr. Gray’s boss at Blackstone last month.                                                                                                                                                                                                                                                                                                                                                                                                                   , For 2021, Mr. Schwarzman’s compensation was $160 million — roughly 4.5 times that of the highest-paid bank chiefs, James Gorman of Morgan Stanley and David Solomon of Goldman Sachs, who each received roughly $35 million. And Mr. Schwarzman’s pay package was dwarfed by the dividends he earned, which pushed his total haul to more than of the $1.1 billion.                                                                                                                                                                                                   , Blackstone’s push into seemingly everything is working well for the firm. “Blackstone,” Mr. Schwarzman told investors in late January, “reported the most remarkable results in our history on virtually every metric.”                                                                                                                                                                                                                                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/us-recession-inflation-40-year-high </td>
   <td style="text-align:left;"> 2022-03-10 23:31:43 </td>
   <td style="text-align:left;"> US barreling toward recession, experts say, as inflation hits 40-year-high </td>
   <td style="text-align:left;"> Former Chairman of the Council of Economic Advisers Kevin Hassett weighs in on the Labor Department's inflation report for February, noting that 'wages aren't keeping up with prices,' which means 'real incomes are going down.'                                                                                                                                                                                                             , Inflation hit a 40-year high in February, and the worst is yet to come as the U.S. economy barrels toward a recession, experts say.                                                                                                                                                                                                                                                                                                            , The consumer price index (CPI) climbed 7.9% on an annual basis, according to data released Thursday by the Bureau of Labor Statistics. Month over month, inflation rose 0.8%.                                                                                                                                                                                                                                                                  , LIVE UPDATES: STOCKS FALL, INFLATION JUMPS 7.9%, GAS HITS NEW HIGH                                                                                                                                                                                                                                                                                                                                                                             , Gas jumped 6.6% in February and accounted for almost a third of price hikes. Food rose by 1%.                                                                                                                                                                                                                                                                                                                                                  , The February data does not include Russia’s war on Ukraine, which has accelerated the rise in gas prices. As of Thursday, the U.S. national average hit a record high of $4.35 per gallon.                                                                                                                                                                                                                                                     , Geltrude &amp; Company founder Dan Geltrude told FOX Business he thinks gas prices will hit $5 this month and that it could even go as high as $10 unless the Biden administration expands domestic oil production.                                                                                                                                                                                                                                , "It would not surprise me," he said. "So until the United States decides, or this administration decides that we are going to pump more oil, it is not going to change. It's not. Fuel costs are just going to continue to rise."                                                                                                                                                                                                              , Geltrude said the U.S. is on track to enter a full-blown recession within the year.                                                                                                                                                                                                                                                                                                                                                            , "If nothing were to change, I see that happening within the next six to 12 months," he said. "Fuel costs are skyrocketing, which impacts everything, because all goods and services go from point A to point B using fuel. So as those costs go up, the price of everything goes up."                                                                                                                                                          , Data from the U.S. Bureau of Labor Statistics shows year-over-year rise in indexes from February 2022. (FOX Business / FOXBusiness)                                                                                                                                                                                                                                                                                                            , Geltrude said the Federal Reserve will eventually be forced to take aggressive action by "dramatically" increasing interest rates, which will throw the country into a recession.                                                                                                                                                                                                                                                              , "It happened during the Carter administration," he said. "We seem to be following that, different times, but we seem to be following the same formula. … Back then, what was happening, prices at the pump [were] out of control, inflation [was] out of control, so in order to get those things under control, meaning inflation, the Federal Reserve increased interest rates dramatically. And ultimately, that threw us into a recession.", INFLATION RISES 7.9% IN FEBRUARY, A NEW 40-YEAR-HIGH                                                                                                                                                                                                                                                                                                                                                                                           , Campbell Faulkner, senior vice president at OTC Global Holdings, told FOX Business that gas prices could "easily" rise to $5 in places like Houston, where the average is currently topping $3.96.                                                                                                                                                                                                                                             , "That's a big number, and it really can harm a wide variety of consumers," he said.                                                                                                                                                                                                                                                                                                                                                            , "Really, the problem is we have pipelines that are ready to go, and they're getting re-reviewed," he said. "A lot of a lot of it has to do with removing the red tape and changing the discourse."                                                                                                                                                                                                                                             , Data from the U.S. Bureau of Labor Statistics shows year-over-year rise in the consumer price of common household goods from February 2022. (FOX Business / FOXBusiness)                                                                                                                                                                                                                                                                       , Faulkner said he believes the U.S. is already seeing the beginnings of a recession.                                                                                                                                                                                                                                                                                                                                                            , "I'll be blunt," he said. "I'm basically a data scientist, and I work in commodities, and I think we're already in one. I just think because of the lags in the data, we're not going to see it yet.                                                                                                                                                                                                                                           , "It really seemed around December, I started noticing prices going up. Yes, I knew that they were coming up, I knew CPI and everything else was moving. The problem is, you always know you're in a recession well after it’s already begun. That's going to be the difficult part is to tell when it has happened.                                                                                                                            , "I think we unfortunately slipped into one, and hopefully it's not going to be a particularly egregious one. We have had strong job growth, but that too is going to be lagged as well because a lot of firms are going to have to start rationalizing their input costs and everything else."                                                                                                                                                 , White House press secretary Jen Psaki said Wednesday that the White House was expecting a high inflation report, and she blamed the rise in gas prices on Russia’s military buildup and subsequent invasion of Ukraine.                                                                                                                                                                                                                        , President Biden said earlier this week that he "can’t do much" about the rising prices and also blamed the situation on Russia.                                                                                                                                                                                                                                                                                                                , President Biden speaks about expanding access to health care and benefits for veterans affected by military environmental exposures at the Resource Connection of Tarrant County in Fort Worth, Texas, Tuesday, March 8, 2022.  (AP Photo/Patrick Semansky / AP Newsroom)                                                                                                                                                                      , The president announced Tuesday a ban on Russian oil, gas and energy imports to the U.S. in an effort to weaken Russian President Vladimir Putin, warning that it would contribute to the rise in prices.                                                                                                                                                                                                                                      , Republicans and some Democrats have called for more domestic oil drilling as a solution, but Biden has continued to push his green agenda.                                                                                                                                                                                                                                                                                                     , "Loosening environmental regulations won’t lower prices," the president declared in a tweet Tuesday evening. "But transforming our economy to run on electric vehicles, powered by clean energy, will mean that no one will have to worry about gas prices. It will mean tyrants like Putin won’t be able to use fossil fuels as a weapon."                                                                                                    , Geltrude told FOX Business that while the Biden administration’s push for clean energy is a "noble intention," it’s not rooted in reality.                                                                                                                                                                                                                                                                                                     , "Everybody wants a clean environment," he said. "I don't think anyone can reasonably argue that we don't want to have a cleaner planet. However, that doesn't happen overnight. There needs to be a transition from fossil fuel to clean energy, and in my mind it will happen, but it's going to take decades."                                                                                                                               , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                        , "There are countries on the other side of the world using dirty energy," he added. "We don't have a dome over the United States that keeps us shielded from that. So unless you have a collective effort around the globe, the United States having its noble intentions towards clean energy only puts us behind economically." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-03-10 23:30:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Rises for 5th Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index advanced 5.7% to 2,704 points on Thursday, its highest since December 14th, extending gains into a fifth straight session, supported by gains across all vessel segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, surged 14.5% to 2,613, its highest since December 21; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, was up 39 points to its highest since December 7th at 3,233 points. Among smaller vessels, the supramax index rose 78 points to its highest in more than four months at 2,923 points. "The North Atlantic has been suffering as the Russian invasion of Ukraine has taken out loading areas either directly caused by war or by self-sanctions. Further linked to the war we see much more coal heading towards Europe from destinations which is atypical - replacing Russian coal.," Fearnleys said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60696125?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-10 23:27:12 </td>
   <td style="text-align:left;"> Rising fuel and food costs push US inflation to 7.9% </td>
   <td style="text-align:left;"> Price increases in the US continued to surge last month, pushing the annual inflation rate up 7.9%.                                                                                                                                                               , That is the biggest year-on-year leap since 1982 and up from the 7.5% rate reported in January.                                                                                                                                                                   , Rising costs for energy, food and shelter drove the gains, which are squeezing household incomes.                                                                                                                                                                 , President Joe Biden and central bank officials are under pressure to rein in the increases, which have proven more persistent than many expected.                                                                                                                 , The Federal Reserve - the US central bank - is widely expected to raise interest rates at its meeting this month.                                                                                                                                                 , In the UK - where inflation hit 5.5% in January - the Bank of England has already increased rates, while the European Central Bank on Thursday said it would wind down some of its pandemic-era stimulus sooner than expected in response to the price pressures. , At a news conference, ECB president Christine Lagarde said: "The risks to the economic outlook have increased substantially with the Russian invasion of Ukraine and are tilted to the downside".                                                                 , The war will have "a material impact on economic activity and inflation through higher energy and commodity prices, the disruption of international commerce and weaker confidence", she warned.                                                                  , The US and other parts of the world have already been grappling with high inflation for months, as a surge in demand, fuelled in part by pandemic aid, ran into supply constraints, labour shortages and other issues.                                            , The war in Ukraine has added to the problems, driving a global surge in energy prices as the West and allies shun oil from Russia - typically responsible for about 7% of global supply.                                                                          , Energy prices in the US jumped 3.5% in February, driven by a 6.6% leap in gasoline prices, according to the Labor Department's monthly report on consumer prices.                                                                                                 , Over the past 12 months, the energy index has soared more than 25%, with gasoline surging 38%.                                                                                                                                                                    , Americans who own SUVs are now paying an average of $110 per month more than a year ago to operate their vehicle, according to research from Cox Automotive. Even drivers of hybrids have seen monthly costs jump about $40, the firm estimated.                  , The surge in energy costs will push up prices far beyond the gas pump, said Matt Smith, an oil analyst at Kpler.                                                                                                                                                  , "We're focused on that headline crude number, but that crude is used as an input to produce all manner of products," he said.                                                                                                                                     , Grocery prices in the US jumped 1.4% last month, driven by rising costs for meat, fruits and vegetables. They are up 8.6% year-on-year - the largest annual leap since 1981.                                                                                      , Analysts expect the increased costs of energy and other commodities due to the war will push US inflation even higher in March, hitting 8% or more.                                                                                                               , As the rising costs outpace wage gains, they have hurt consumer sentiment, creating a political problem for President Joe Biden.                                                                                                                                  , He has been criticised by Republicans on the issue, which few economists expect to ease in the near-term.                                                                                                                                                         , "Inflation continues on at a blazing pace," Wells Fargo economist Sarah House said. "Consumers and policymakers remain in a deeply uncomfortable state as a result."                                                                                              , Stacey Dooley meets victims and perpetrators of a crime that devastates lives                                                                                                                                                                                     , Can aspiring musician Sasha break free from it?                                                                                                                                                                                                                   , Louis Theroux explores the issue with consent in the industry                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-03-10 23:10:49 </td>
   <td style="text-align:left;"> Copper Regains Traction </td>
   <td style="text-align:left;"> Copper futures were trading above $4.6 per pound, rebounding from a technically-driven selling as investors refocused again on the bullish outlook for the commodity. On the demand side, customs data showed that copper imports from top consumer China rose 9.6% during the first two months of 2022 compared with the same period a year earlier. Signs of robust demand came against the backdrop of supply disruptions due to war in Ukraine and historically low inventories. Copper stocks held by LME were at 68,825 tonnes, the lowest level since 2005. In February, those in the Shanghai Futures Exchange and Comex were below 200,000 tonnes. Adding to woes, the world's biggest producer Chile, recorded its lowest January output since 2011, with production sinking 15% compared to December and 7.5% from January 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-10 22:58:48 </td>
   <td style="text-align:left;"> Canada Stocks Ease from 3-Week High </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, slipped from a three-week high on Thursday, tracking negative global cues, although losses were limited by gains in heavyweight oil and mining companies. Concerns about the impact of the war in Ukraine remained dominant, as highly awaited cease-fire talks between the foreign ministers of Russia and Ukraine failed. On corporate updates, J.P. Morgan analysts confirmed Canadian National Railway and rival Canadian Pacific Railway with “neutral” and “overweight” ratings, respectively. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/10/technology/disinformation-russia-ukraine.html </td>
   <td style="text-align:left;"> 2022-03-10 22:58:16 </td>
   <td style="text-align:left;"> 4 Falsehoods Russians Are Told About the War - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,  Stuart A. Thompson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Stuart Thompson is a technology reporter covering online information flows.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Russia’s international disinformation campaign seemed to flounder in the early days of the invasion, as narratives about Ukrainian bravery dominated the internet. But in Russia, the country’s propaganda machine was busy churning out a deluge of misinformation aimed at its own citizens.                                                                                                                                                                                                                                                                                                                      , The narrative disseminated online through state-run and unofficial channels has helped create an alternate reality where the invasion is justified and Ukrainians are to blame for violence. To control the narrative at home, Russia also shut down access to several websites and threatened the news media with long prison sentences for criticizing the war. There’s some evidence that the effort has mollified at least some Russians.                                                                                                                                                                       , Here is what the war looks like to Russians, based on a review of state news articles, channels on the popular chat app Telegram, and input from several disinformation watchdogs who are monitoring Russia’s propaganda machine.                                                                                                                                                                                                                                                                                                                                                                                   , Some of the most disturbing images from the war have come from Mariupol, a port city in the southeastern coast. Shelling battered the region, killing several civilians who were trying to flee the area, during what was supposed to be a cease-fire.                                                                                                                                                                                                                                                                                                                                                              , But Russians got a different explanation online: Ukrainians had fired on Russian forces during the cease-fire, and neo-Nazis were “hiding behind civilians as a human shield,” according to the Russian state news website Tass.                                                                                                                                                                                                                                                                                                                                                                                    , Neo-Nazis have been a recurring character in Russian propaganda campaigns for years, used to falsely justify military action against Ukraine in what Russian officials have called “denazification.” Those claims have only continued during the conflict. To explain away attacks on other Ukrainian apartment buildings, the same article by Tass claimed that neo-Nazis had placed “heavy weapons in apartment buildings, while some residents are forcibly kept in their homes,” providing no evidence.                                                                                                         , Russian social media accounts have used a mix of fake and unconfirmed photos showing Ukrainian soldiers holding Nazi flags or photos of Hitler. An analysis by the Center for Information Resilience, a nonprofit focused on identifying disinformation, showed that the number of tweets connecting Ukrainians to Nazis soared after the invasion began.                                                                                                                                                                                                                                                           , “Propaganda works when it coincides with your existing assumptions,” said Pierre Vaux, a senior investigator at the Center for Information Resilience. “The stuff that chimes into the Nazi stuff is really effective.”                                                                                                                                                                                                                                                                                                                                                                                             , After Russia attacked an area near the nuclear complex in Zaporizhzhia, leading to a fire, President Volodymyr Zelensky of Ukraine called it “nuclear terrorism.”                                                                                                                                                                                                                                                                                                                                                                                                                                                   , But according to a Kremlin statement reported in Tass, the military seized the facility to prevent Ukrainians and neo-Nazis from “organizing provocations fraught with catastrophic consequences.” Even though Ukrainians heavily fortified the region against an attack, Russian officials claimed they already had control of the compound before Ukrainians opened fire. They added that Ukrainians set fire to an adjacent building before fleeing, providing no evidence. Western experts said controlling the Zaporizhzhia complex would allow Russia to trigger blackouts or shut down the entire power grid., The image of Russia as a world protector surfaced again after the country’s officials claimed they discovered evidence that Ukraine was working on a nuclear bomb. According to Russian officials, plans for the bomb were uncovered at the abandoned Chernobyl nuclear power plant.                                                                                                                                                                                                                                                                                                                                , “It doesn’t even make sense, because if you’re going to develop a nuclear weapon, you don’t do your secret development in a nuclear power plant,” Mr. Vaux said. “But that kind of thing is just being beamed out on Russian state TV.”                                                                                                                                                                                                                                                                                                                                                                             , An attack on Kharkiv, a northeast Ukraine city bordering Russia, provided additional evidence that Russia had indiscriminately bombed residential neighborhoods and killed civilians, according to the Atlantic Council, an American research group. The International Criminal Court opened an investigation into war crimes after the assault.                                                                                                                                                                                                                                                                    , In one attack that included heavy shelling, 34 civilians were killed and 285 were injured, according to the Ukrainian State Emergency Service.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , But Russians listening to state media or browsing channels on Telegram heard another story: The missiles, those sources claimed, came from Ukrainian territory.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , On the ground. As the war in Ukraine enters its third week, the Russian advance appears to have slowed. At the same time, destruction across Ukraine is growing, as Russia increases its targeting of residential areas and civilian infrastructure with long-range missiles.                                                                                                                                                                                                                                                                                                                                       , No agreement. The Foreign Ministers of Ukraine and Russia met in Turkey, for the first time since the start of the war, and failed to stop the fighting. Foreign Minister Sergey V. Lavrov of Russia declared that a cease-fire was never up for discussion.                                                                                                                                                                                                                                                                                                                                                        , Chernobyl nuclear facility. The International Atomic Energy Agency said that the defunct power plant had been disconnected from electricity, though there was no need for immediate alarm. A power loss could affect the facility’s ability to keep the water that cools radioactive material circulating and lead to safety issues.                                                                                                                                                                                                                                                                                , On the diplomatic front. Vice President Kamala Harris visited Poland, where she repeated U.S. pledges to “defend every inch of NATO territory,” while sidestepping questions about Poland’s offer, rejected by the Pentagon, to hand fighter jets over to the United States to transfer to Ukraine.                                                                                                                                                                                                                                                                                                                 , On a Telegram channel for the Russian news site Readovka, one post described how “Ukrainian missiles” had “arrived from the northwest” — an area controlled by the Ukrainian military.                                                                                                                                                                                                                                                                                                                                                                                                                              , Russia’s defense department said that it never attacked cities, instead targeting “military infrastructure” with “high-precision weapons,” according to an article in the state-owned news agency RIA Novosti.                                                                                                                                                                                                                                                                                                                                                                                                      , A woman who survived a blast at her apartment building became the focus of disinformation efforts after her bloodied and bandaged photograph spread widely through newspapers and Western media.                                                                                                                                                                                                                                                                                                                                                                                                                    , The woman was a resident of an apartment complex in Chuhuiv, near Kharkiv. The photojournalist Alex Lourie captured her portrait after the attack, and the image was soon featured on the front pages of newspapers around the world.                                                                                                                                                                                                                                                                                                                                                                               , But Russian social media channels falsely described her as a member of Ukraine’s psychological operations unit, according to an analysis by the Ukrainian fact-checking website StopFake.                                                                                                                                                                                                                                                                                                                                                                                                                           , A post by “War on Fakes,” a pro-Russian website and Telegram channel that appeared at the start of the invasion, suggested that the blood could be grape juice and that the woman could be “part of the territorial defense.” As evidence, the post included a shot of another woman bearing some resemblance. That image came from a New York Times photograph, which was taken in Kyiv — a seven-hour drive west of Chuhuiv.                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2022-03-10 22:45:10 </td>
   <td style="text-align:left;"> Aussie Strengthens as Commodity Rally Returns </td>
   <td style="text-align:left;"> The Australian dollar gained momentum to $0.733 on Thursday as the Russia-Ukraine summit in Turkey ended with no results and the rally in commodity prices revived. Earlier this week, the Aussie hit a four-month high of $0.744, as US and European allies search for alternatives to Russian energy goods and fears of supply disruptions in the Black Sea region fueled a rally in commodities which are key to the Australian economy. Meanwhile, the Reserve Bank of Australia kept the cash rate unchanged at a record low of 0.1% last week, as widely expected. RBA Governor Lowe also warned Wednesday that the jump in commodity prices would likely lift inflation and said a move was plausible later in the year, but emphasized that the Board had room to be patient before hiking interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-10 22:43:00 </td>
   <td style="text-align:left;"> Brazilian Equities Down on Thursday </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Ibovespa, fell over 1.5% to around 112,020 on Thursday, tracking losses in international markets, as another round of Ukraine-Russia talks failed to make progress on ending the conflict and concerns over global inflation mounted. On the corporate front, planemaker Embraer was the worst performer, with its shares tumbling over 8%, even after upbeat corporate earnings, as financial guidance for 2022 was slightly weaker than expected. By contrast, commodity-linked sectors gained. Meanwhile, Brazilian state-run oil company Petrobras has announced it will raise fuel prices at the refinery gate starting Friday as global oil quotes surged following Russia's invasion of Ukraine. On the economic data front, Brazil's economy added fewer jobs than expected in January; while monthly retail sales recovered more than expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-10 22:39:00 </td>
   <td style="text-align:left;"> Wall Street Faces Renewed Pressure </td>
   <td style="text-align:left;"> The Dow lost over 300 points at the opening bell Thursday, while the S&amp;P 500 and the Nasdaq 100 dropped 1.2% and 1.6%, respectively, as sentiment remains clouded by the war in Ukraine, rising inflation, and prospects of higher interest rates. Recent talks between Russia and Ukraine's foreign ministers in Turkey failed as Moscow's representative once again defended its invasion and said it was going as planned. On the economic front, the annual inflation rate in the US accelerated to 7.9% in February of 2022, the highest since January of 1982 but matching market expectations. The hot inflation reading came along with a disappointing US jobless claims report, which, in turn, eased some concerns about an aggressive monetary tightening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2022-03-10 22:34:00 </td>
   <td style="text-align:left;"> Ruble Recovers Some Ground but Remains Near Record Levels </td>
   <td style="text-align:left;"> The Russian ruble was trading above 120 per USD on Thursday but remained very close to record low of $130 reached early in the month. The first talks between the Russian and Ukrainian foreign ministers since the invasion showed no progress to end the conflict. Meanwhile, new sanctions were announced on Thursday, with the Bank for International Settlements suspending Russia's central bank from all its meetings and services. Early, the US imposed an immediate ban on Russian oil and other energy imports while the UK intends to follow suit. The currency has now lost about 50% of its value since the Russian attack on Ukraine started. The Bank of Russia responded with a more than double policy rate hike to 20% and introduced capital controls to defend its currency from further depreciation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-03-10 22:33:00 </td>
   <td style="text-align:left;"> Euro Loses Steam after Lagarde Conference </td>
   <td style="text-align:left;"> The euro fell to $1.10, erasing a 0.3% gain earlier in the session as investors digest the latest ECB monetary policy decision. President Lagarde said during the press conference that the quicker winding-down of ECB asset purchases can be described as a normalization process due to high inflation not as a tightening or acceleration. The ECB said it may end asset purchases in Q3 as surging inflation more than offset concerns about Russia's shock invasion of Ukraine. The bloc’s inflation is already running at record highs and is now likely to be more persistent on the back of higher commodity prices and a tight labor market. Meanwhile, market participants await European Union leaders to unveil the bloc's policy response to Russia's invasion of Ukraine. On Wednesday, the common currency surged 1.6% in its biggest daily jump since 2016 boosted by improved risk appetite and reports that EU leaders were considering joint bond issuance to finance energy and defense spending. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-10 22:27:55 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield Jumps on Price Pressures </td>
   <td style="text-align:left;"> The yield on the benchmark Japan 10-year JGB jumped more than 4 bps to over 0.20%, not far from a 6-year high of 0.228% hit on February 13th, amid mounting inflationary pressures. Wholesale prices in Japan climbed at an unprecedented pace of 9.3% over a year earlier in February, and reached levels not seen in 37 years, beating analyst expectations of an 8.7% rise. Although the impact of war in Ukraine on commodity prices wasn’t yet reflected, analysts are expecting prices to continue rising, due to Japan’s dependence on imports of raw materials, which will likely push consumer price inflation closer to the Bank of Japan’s 2% target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/goldman-is-closing-down-its-russia-business-making-it-among-the-first-wall-street-banks-to-do-so.html </td>
   <td style="text-align:left;"> 2022-03-10 22:24:52 </td>
   <td style="text-align:left;"> Goldman Sachs shutters Russia business, first major Wall Street bank to leave after Ukraine war </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                           , Goldman Sachs says it is exiting Russia, becoming the first major global investment bank to do so after the country invaded its neighbor Ukraine last month.                                                                                                                                                                                                                                              , The bank said Thursday in an e-mailed statement that it is working to wind down operations in Russia.                                                                                                                                                                                                                                                                                                     , "Goldman Sachs is winding down its business in Russia in compliance with regulatory and licensing requirements," said a bank spokeswoman. "We are focused on supporting our clients across the globe in managing or closing out pre-existing obligations in the market and ensuring the well-being of our people."                                                                                        , The move is the latest sign of Russia's increasing isolation in the third week of President Vladimir Putin's campaign to overthrow the government of Ukraine. Tech firms including Apple and Google and payments firms like Visa and Mastercard were among the first to pull back from Russia, followed by retail brands including McDonald's and Starbucks.                                              , Most big U.S. banks had modest operations in Russia, a geographically large nation with a relatively small economy. Citigroup had the biggest exposure as of year-end 2021 at $9.8 billion, according to filings. Goldman was estimated to have $940 million in total exposure, including $650 million in credit, or less than 10 basis points of its total assets, according to Bank of America analysts., Meanwhile, banks including JPMorgan Chase, Bank of America and Morgan Stanley don't disclose their Russia exposure in filings, suggesting limited dealings with the country, according to the analysts.                                                                                                                                                                                                   , Citigroup had disclosed plans to sell its Russia operations last year as part of a strategic overhaul, well before the conflict began. But the war has forced it to run its consumer banking operations there on a "more limited" basis and could reportedly force Citigroup to simply shutter the business.                                                                                              , While New York-based Goldman is closing its operations in Russia, it still facilitates trades in debt securities tied to the nation, according to Bloomberg, which first reported the bank's move.                                                                                                                                                                                                        , "In our role as market-maker standing between buyers and sellers, we are helping our clients reduce their risk in Russian securities which trade in the secondary market, not seeking to speculate," the bank said.                                                                                                                                                                                       , With reporting from CNBC's Jim Forkin.                                                                                                                                                                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ukraine/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-10 22:14:06 </td>
   <td style="text-align:left;"> Ukraine Inflation Rate at 4-Month High </td>
   <td style="text-align:left;"> The annual inflation rate in Ukraine jumped to 10.7 percent in February of 2022 after remaining steady at 10 percent for the last two months. It was the highest inflation rate since October of 2021 and was much higher than central bank’s medium-term target of 5 percent. Prices advanced at a faster pace for food &amp; non-alcoholic beverages (14.3 percent vs 14 percent in January), transport (13.7 percent vs 11.4 percent), housing &amp; utilities (6.4 percent vs 4.3 percent); health (6.9 percent vs 6.2 percent); and household goods (4.1 percent vs 3.9 percent ). On a monthly basis, consumer prices rose 1.6 percent, accelerating from a 1.3 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/russia-ukraine-economy-sanctions-experts </td>
   <td style="text-align:left;"> 2022-03-10 22:07:31 </td>
   <td style="text-align:left;"> Despite sanctions amid war with Ukraine, Russia's economy not likely to collapse, experts say </td>
   <td style="text-align:left;"> Wall Street legend gauges the financial climate after Russia's invasion of Ukraine on 'The Claman Countdown.'                                                                                                                                                                                                                                                                                                                                                                                                             , Western sanctions are dealing a severe blow to Russia's economy. The ruble is plunging, foreign businesses are fleeing and sharply higher prices are in the offing. Familiar products may disappear from stores, and middle-class achievements like foreign vacations are in doubt.                                                                                                                                                                                                                                       , Beyond the short-term pain, Russia's economy will likely see a deepening of the stagnation that started to set in long before the invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                    , But a total collapse is unlikely, several economists say. Despite the punishing financial sanctions, Russia has built "an economy that’s geared for conflict," said Richard Connolly, an expert on the Russian economy at the Royal United Services Institute in Britain.                                                                                                                                                                                                                                                 , The Russian government’s extensive involvement in the economy and the money it is still making from oil and gas exports — even with bans from the U.S. and Britain — will help soften the blow for many workers, pensioners and government employees in a country that has endured three serious financial crises in the past three decades. And as economists point out, Iran, a much smaller and less diversified economy, has endured sanctions misery for years over its nuclear program without a complete breakdown., Still, the Russian currency has fallen spectacularly, which will drive up prices for imported goods when inflation was already running hot at 9%. It took 80 rubles to get one U.S. dollar on Feb. 23, the day before the invasion. By Thursday, it was 119 — even after Russia's central bank took drastic measures to stop the plunge, including doubling interest rates to 20%.                                                                                                                                        , Women look at a screen displaying exchange rate at a currency exchange office in St. Petersburg, Russia, Tuesday, March 1, 2022.  (AP Photo/Dmitri Lovetsky, File / AP Newsroom)                                                                                                                                                                                                                                                                                                                                          , GOLDMAN SACHS BECOMES FIRST WALL ST. FIRM TO EXIT RUSSIA                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Marina Albee, owner of the Cafe Botanika vegetarian restaurant in St. Petersburg's historic city center, has already heard from her fruit and vegetable supplier that prices will be going up 10% to 50%. Other suppliers can't say how much.                                                                                                                                                                                                                                                                             , The cafe imports dried seaweed and smoked tofu from Japan, mini asparagus from Chile, broccoli from Benin, basmati rice and coconut oil from India.                                                                                                                                                                                                                                                                                                                                                                       , "We're waiting for the tsunami to hit — the tsunami being the price increases for everything we purchase," Albee said. "We need to keep our eye on the situation and, if we need to, take those dishes out of the menu."                                                                                                                                                                                                                                                                                                  , "We can reengineer our menu to make more Russian-based dishes," she said. "You have to be quick on your feet." After surviving two years without tourists because of the COVID-19 pandemic, "it takes a lot to faze us," Albee added.                                                                                                                                                                                                                                                                                     , Although sanctions have frozen a large portion of Russia’s foreign currency reserves, state finances are in good shape with low debt. When the government does need to borrow, its creditors are mostly domestic banks, not foreign investors who could abandon it in a crisis. The government announced support this week for large companies deemed crucial to the economy.                                                                                                                                             , CRUISE TRAVELERS AVOIDING BALTIC REGION DUE TO RUSSIA-UKRAINE WAR                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Estimates of the short-term impact on Russia's economic growth vary widely because more sanctions could come and the fallout from President Vladimir Putin's war are uncertain.                                                                                                                                                                                                                                                                                                                                           , "Russians will be a lot poorer — they won’t have cash to holiday in Turkey or send their kids to school in the West — and even then, because of Putin, they will not be welcome," said Tim Ash, senior emerging market sovereign analyst at BlueBay Asset Management.                                                                                                                                                                                                                                                     , He sees economic growth dropping 10%, while other economists see a drop of as little as 2% or something in between.                                                                                                                                                                                                                                                                                                                                                                                                       , Long-term prospects for a growing economy are not good — for enduring reasons that predate the war: A few favored insiders control major companies and sectors, resulting in a lack of competition and new investment. Russia has failed to diversify away from its dominant oil and gas sector. Per capita income in 2020 was roughly what it was in 2014.                                                                                                                                                               , Foreign investment built up over the 30 years since the collapse of the Soviet Union and the jobs it brought are heading for the door. Big corporations like Volkswagen, Ikea and Apple have idled plants or halted sales, while energy giants BP, Exxon and Shell have said they will stop buying Russian oil and gas or exit partnerships there.                                                                                                                                                                        , On Wednesday, ratings agency Fitch cut its credit rating for the country further into junk status and warned of an imminent default on sovereign debt.                                                                                                                                                                                                                                                                                                                                                                    , Visitors sit in a cafe inside the GUM department store in Moscow, Russia, late Monday, Feb. 14, 2022. (AP Photo/Alexander Zemlianichenko / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The central bank has stepped in to bolster the ruble and the banking system, restrict withdrawals in foreign currency and keep the stock market closed for nearly two weeks. The government also has announced measures to restrict foreign investors from fleeing. While such restrictions shore up the financial system against utter collapse, they also close off the economy to trade and investment that could fuel growth.                                                                                         , Since facing sanctions over its 2014 seizure of Ukraine's Crimea peninsula, the Kremlin has anticipated such measures would be the West's primary weapon in any conflict. In response, it has devised what Connolly, an associate fellow at the Royal United Services Institute and author of a book on Russia’s response to sanctions, calls "the Kalashnikov economy," a reference to the Russian military rifle.                                                                                                       , It's "a durable, in some ways primitive system," he said, based on low debt, government control of most of the banking system and a central bank able to intervene and prop up the currency and banks.                                                                                                                                                                                                                                                                                                                    , While trade will fall and fewer goods will be available, the weaker ruble means the Russian government will earn more of its currency for the oil it sells because oil is priced in dollars. With recently higher prices, Connolly estimates Russia is getting 2.7 times the amount of rubles from oil compared with 2019, money that can cover salaries and pensions.                                                                                                                                                    , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , While U.S. and British officials said they will ban the relatively small amount of oil they import from Russia, Europe, which is much more dependent on Russian energy, has held back.                                                                                                                                                                                                                                                                                                                                    , As it stands, "there's a lot of holes in this, and the Russians will exploit this and develop a way of carrying on," Connolly said.                                                                                                                                                                                                                                                                                                                                                                                       , "I’m not saying they’re going to have a wonderful time. I’m saying they have the resources to deal with these problems," he said.                                                                                                                                                                                                                                                                                                                                                                                         , The long-term impact for Putin's government in domestic politics is hard to predict. Simon Commander, managing partner at Altura Partners advisory firm and a former World Bank official, says "buoyant popularity for the regime fueled by increased prosperity ... seems unattainable."                                                                                                                                                                                                                                 , "That may not translate into open dissension, let alone revolt, but it will hardly bolster support for the autocrat," he said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-10 21:57:58 </td>
   <td style="text-align:left;"> US 10-Year Treasury Yield Picks Up to 2-Week High </td>
   <td style="text-align:left;"> The benchmark 10-year Treasury yield rose to a two-week high above 1.98%, a sharp move from its weekly lows of 1.67% as investors anticipate a looming policy tightening cycle. Prices paid by US consumers jumped 7.9% in February from a year earlier, the highest inflation rate since 1982 and in line with market expectations. Fed Chair Jerome Powell has reassured investors that the central bank remains committed to tame runaway inflation while pointing to a 25 basis point hike on March 16th. Meantime, investors continued to monitor developments in the Russia-Ukraine crisis. Western states implemented harsh sanctions against Russia after the country's move to launch a full-scale invasion of Ukraine last month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-10 21:55:01 </td>
   <td style="text-align:left;"> Wall Street Set to Open lower </td>
   <td style="text-align:left;"> Wall Street was set to open down on Thursday, with futures contracts tied to the three major indices declining over 1% as market sentiment remains clouded by the war in Ukraine, rising inflation and higher interest rates. Recent talks between Russia and Ukraine's foreign ministers in Turkey failed as Moscow's representative once again defended its invasion and said it was going as planned. On the economic front, the annual inflation rate in the US accelerated to 7.9% in February of 2022, the highest since January of 1982 but matching market expectations. The hot inflation reading came along with a disappointing US jobless claims report, which, in turn, eased some concerns about an aggressive monetary tightening.  In regular trading on Wednesday, the Dow rose 2%, the S&amp;P 500 gained 2.57%, and the Nasdaq rallied 3.6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/gas-prices-leading-americans-lifestyle-changes </td>
   <td style="text-align:left;"> 2022-03-10 21:51:01 </td>
   <td style="text-align:left;"> Gas prices surpass $4, leading Americans to make lifestyle changes: AAA </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for March 10.                                                                                                                                                                                                                                                                           , U.S. motorists were reeling over gas prices even before the national average surpassed record highs this week.                                                                                                                                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                , As of Thursday, the national average for a gallon of regular gasoline reached $4.318, according to AAA data. Prices surpassed the $4 mark Sunday for the first time in 14 years.                                                                                                                                                       , However, two-thirds of Americans said gas prices were already too expensive even when the national average hit $3.53 per gallon a few weeks ago, according to a AAA survey. Over half of motorists, 59%, admitted that if prices hit $4 a gallon, they would make changes to their driving habits or lifestyle, according to the data. , Gas prices are advertised at over six dollars a gallon Monday, March 7, 2022, in Los Angeles.  ((AP Photo/Marcio Jose Sanchez) / AP Newsroom)                                                                                                                                                                                          , "Now with the national average at an all-time high of over $4, Americans may have reached a tipping point," according to AAA spokesperson Ellen Edmonds.                                                                                                                                                                               , The national average has continued to rise since the beginning of the year due to strained supply and increased demand, according to Edmonds. However, Russia’s invasion of Ukraine two weeks ago caused oil prices to surge higher, pushing prices at the pump to levels not seen in over a decade.                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                            , If prices continue in this direction, reaching $5 per gallon, three-quarters of motorists surveyed admitted they would have to alter their lifestyle.                                                                                                                                                                                  , It's a reality many are already facing in the western part of the country where some prices at the pump have already surpassed that mark. For instance, the national average for a gallon of regular gasoline in California is roughly 30 cents shy of $6.                                                                             , Alex Reyes, 28, filled his gas tank, Nov. 15, 2021, in Los Angeles. (Al Seib / Los Angeles Times via Getty Images / Getty Images)                                                                                                                                                                                                      , Among the motorists who said they would change their habits, 80% said they would drive less, according to the survey.                                                                                                                                                                                                                  , However, "while many Americans may adapt their daily habits to make up for higher gas prices, it likely won’t have as much of an impact on summer travel," according to Edmonds.                                                                                                                                                       , More than half of motorists, 52%, still plan to take a vacation this summer. The majority of them, 42%, don't plan on changing their travel plans regardless of the price of gas, according to the survey.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-03-10 21:47:00 </td>
   <td style="text-align:left;"> Dollar Remains Under Pressure </td>
   <td style="text-align:left;"> The dollar index bottomed around the 98.00 level on Thursday, moving further away from a nearly two-year peak of 99.40 touched earlier this week as investors continued to monitor the outlook for inflation and developments surrounding the war in Ukraine. The latest CPI data showed that the annual inflation rate in the US accelerated to 7.9% in February of 2022, the highest since January of 1982 but matching market expectations. The hot inflation reading came along with a disappointing US jobless claims report, which, in turn, eased some concerns about an aggressive monetary tightening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/jobless-claims </td>
   <td style="text-align:left;"> 2022-03-10 21:35:00 </td>
   <td style="text-align:left;"> US Weekly Jobless Claims Rise Last Week </td>
   <td style="text-align:left;"> The number of Americans filing new claims for unemployment benefits increased by 11 thousand to 227 thousand in the week ended March 5th, from a revised 216 thousand in the previous period and compared with market expectations of 217 thousand. On a non-seasonally adjusted basis, increased by 22,025 from the previous week to 218,072, with notable rises being recorded in New York (+16,255), California (+6,233) and Kentucky (+3,134). The 4-week moving average which removes week-to-week volatility was 231.25 thousand, an increase of 500 and continuing claims were at 1.49 million, above market expectations of 1.46 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-10 21:31:00 </td>
   <td style="text-align:left;"> US Inflation Rate Hits New 40-Year High of 7.9% </td>
   <td style="text-align:left;"> Annual inflation rate in the US accelerated to 7.9% in February of 2022, the highest since January of 1982, matching market expectations. Energy remained the biggest contributor (25.6% vs 27% in January), with gasoline prices surging 38% (40% in January). Inflation accelerated for shelter (4.7% vs 4.4%); food (7.9% vs 7%, the largest since July of 1981), namely food at home (8.6% vs 7.4%); new vehicles (12.4% vs 12.2%); and used cars and trucks (41.2% vs 40.5%). Excluding volatile energy and food categories, the CPI rose 6.4%, the most in 40 years. Still, the biggest effects of the war in Ukraine and the consequent surge in energy costs are still to come and will worsen with the US ban on oil imports from Russia. The inflation was seen peaking in March but the recent developments in Europe coupled with the ongoing supply constraints, strong demand and labour shortages will likely maintain inflation elevated for longer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/10/christine-lagarde-speaking-after-the-ecbs-latest-rate-decision.html </td>
   <td style="text-align:left;"> 2022-03-10 21:28:12 </td>
   <td style="text-align:left;"> Watch Christine Lagarde speaking after the ECB's latest rate decision </td>
   <td style="text-align:left;"> , [The stream is slated to start at 08:30 a.m. ET. Please refresh the page if you do not see a player above at that time.]                                    , European Central Bank President Christine Lagarde is giving a press conference after the bank's latest monetary policy decision.                            , The ECB announced it will wind down asset purchases faster than planned, before adding that it stands ready to revisit this decision if the outlook changes., Subscribe to CNBC on YouTube.                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/non-farm-payrolls </td>
   <td style="text-align:left;"> 2022-03-10 21:24:00 </td>
   <td style="text-align:left;"> Brazil Economy Adds Fewer Jobs than Expected </td>
   <td style="text-align:left;"> The Brazilian economy created a net 155.2 thousand formal jobs in January of 2022, below market expectations of a 170 thousand increase and following a 265.8 thousand decline in December. It was the highest reading for a January month since 2015. Some 1.78 million positions were added and 1.62 million were cut. Increases were seen in four out of five economic sectors, led by services (+102,000), industry (+51,400), construction (+36,800) and agriculture (+25,014). Meanwhile, jobs were shed in trade (-60,088). The Brazilian Minister of Labour, Onyx Lorenzoni, stated that the country will create between 1.5 million and 2 million jobs in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-10 21:16:00 </td>
   <td style="text-align:left;"> German 10-Year Bund Yield Climbs to 3-Week High </td>
   <td style="text-align:left;"> The yield on the German 10-year Bund surged to an over 3-week high of 0.27%, clawing back all losses from a sell-off due to the war in Ukraine, after a surprisingly hawkish ECB monetary policy decision. The ECB anticipated plans to end asset purchases in the third quarter, as price pressures outweighed risks steaming from the Ukraine conflict. Meanwhile, market participants await European Union leaders to unveil the bloc's policy response to Russia's invasion of Ukraine. There were reports recently that EU leaders were considering joint bond issuance to finance energy and defense spending. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60680787?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-03-10 21:13:47 </td>
   <td style="text-align:left;"> Ukraine war: Oil price rises again due to fears over Russian shortfall </td>
   <td style="text-align:left;"> Oil prices rose on Thursday amid confusion over whether major producers would help to plug a gap in supplies from Russia.                                                                                                                                                                                                           , The United Arab Emirates had appeared to push members of the Opec producer group to raise output, only for the UAE's energy minister to quash hopes.                                                                                                                                                                                , The oil price rose more than 5%, after a 17% fall on Wednesday.                                                                                                                                                                                                                                                                     , "To suggest the oil market is confused would be an understatement," said analyst Stephen Innes.                                                                                                                                                                                                                                     , US President Joe Biden and other leaders have pledged to try to ease the price pressures for households. Officials from the US have been in talks with oil producers aimed at boosting supply.                                                                                                                                      , "We favour production increases and will be encouraging Opec to consider higher production levels," Ambassador Yousuf Al Otaiba said in a statement tweeted by the UAE Embassy in Washington.                                                                                                                                       , But the energy minister Minister Suhail al-Mazrouei said later that the Gulf state remained committed to the existing Opec monthly output agreement, which fixes how much crude is produced by member countries.                                                                                                                    , Oil prices have jumped more than 30% since 24 February, touching $139 (£105) a barrel at one point this week.  The oil price had fallen back to about $106 a barrel at one point on Wednesday, but by Thursday morning it was trading at around $116.                                                                               , On Tuesday, German Economy Minister Robert Habeck issued an "urgent appeal" to Opec oil producers to increase output "to create relief on the market".                                                                                                                                                                              , Saudi Arabia-led Opec and an extended group of oil producers called Opec+ - which includes Russia - have agreed to avoid a price war and keep control over the market.                                                                                                                                                              , Mr Innes, managing partner of SPI Asset Management, said: "To suggest the oil market is confused would be an understatement as we are in an unprecedented situation."                                                                                                                                                               , Commonwealth Bank commodities analyst Vivek Dhar said: "We think it will be challenging for Opec+ to boost production in this environment."                                                                                                                                                                                         , Worries about oil and gas supplies have led to soaring domestic heating bills and fuel prices at the pump. Both petrol and diesel prices hit new records in the UK on Wednesday, according to the RAC motoring group.                                                                                                               , Unleaded petrol was 159.57p a litre on average, while diesel was 167.37p.                                                                                                                                                                                                                                                           , By Sameer Hashmi, Middle East business correspondent                                                                                                                                                                                                                                                                                , Despite the mixed messages coming out from the UAE, there is a broad consensus within Opec+ that there is no immediate need to boost oil production faster. So, even if the UAE tries to convince other members to increase production during the next meeting, it will be difficult to find many backers.                          , While Abu Dhabi is a prominent member of Opec+, Riyadh and Moscow are the leaders of the pack and they are the ones who call the shots. Any decision to increase supplies will essentially boil down to Saudi Arabia.                                                                                                               , While the UAE is keen to increase production, it is very unlikely that it will break ranks and pump more oil unilaterally.  Both the Saudis and the Emiratis have maintained a neutral stance during the course of this war, and the former would be unwilling to take any decision related to Opec+ that the Russians would oppose., Opec+ has attributed the recent rise in prices to market volatility caused by geopolitical tensions and maintained that there is no shortage of supplies in the market.                                                                                                                                                             , RAC fuel spokesman Simon Williams said: "A tank of petrol is now almost £88 while diesel has now gone over £92. Diesel unfortunately appears to be on a clear path to £1.70 a litre.                                                                                                                                                , "As this is an average price, drivers will be seeing some unbelievably high prices on forecourts as retailers pass on their increased wholesale costs."                                                                                                                                                                             , Energy prices have been soaring for more than a year amid a rapid rebound in demand for oil, which had collapsed during the pandemic.                                                                                                                                                                                               , Russia's invasion of Ukraine added new price pressures, as sanctions make it hard for the country - typically the producer of about 7% of global supplies -  to find buyers for its oil.                                                                                                                                            , The US and Canada have also announced bans on Russian oil imports, while the UK said it would phase them out by the end of the year.                                                                                                                                                                                                , The International Energy Agency (IEA) recently agreed to release 60 million barrels of oil from strategic national reserves, but that move is not enough to respond to the recent run-up in prices.                                                                                                                                 , The agency said on Wednesday that oil reserves may be tapped further.                                                                                                                                                                                                                                                               , "If there's a need, if our governments decide so, we can bring more oil to the markets, as one part of the response," said IEA chief Faith Birol.                                                                                                                                                                                   , Stacey Dooley meets victims and perpetrators of a crime that devastates lives                                                                                                                                                                                                                                                       , Can aspiring musician Sasha break free from it?                                                                                                                                                                                                                                                                                     , Louis Theroux explores the issue with consent in the industry                                                                                                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-10 21:08:37 </td>
   <td style="text-align:left;"> Switzerland 10Y Bond Yield Hits 7-year High </td>
   <td style="text-align:left;"> Switzerland 10 Year Government Bond Yeld increased to a 7-year high of 0.356% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-10 20:58:00 </td>
   <td style="text-align:left;"> European Stocks Deepen Losses </td>
   <td style="text-align:left;"> Europe’s major stock indices remained under sharp sell-off on Thursday afternoon, as investors were digesting the latest ECB meeting and the situation in Ukraine. European Central Bank speed up the asset purchase schedule but said any changes to interest rates would be gradual and come after the end of the APP. The DAX shed 3%, while the pan-European Stoxx 600 was down more than 1%, after seeing the strongest rebound since March 2020 in the previous session, with auto stocks leading the decline and basic resources recouping earlier losses. Market sentiment deteriorated as cease-fire talks between Russia and Ukraine’s foreign ministers in Turkey led nowhere. FY 2021 earnings from Hugo Boss showed net income switched to a profit of €144M, from a €219M loss the year before, driven by stronger sales figures. Now, traders await the ECB’s macroeconomic forecasts later in the session. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-10 20:54:27 </td>
   <td style="text-align:left;"> Belgium 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Belgium 10 Year Government Bond Yeld increased to a 3-year high of 0.831% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-03-10 20:54:00 </td>
   <td style="text-align:left;"> Euro Strengthens Further on Hawkish ECB </td>
   <td style="text-align:left;"> The euro appreciated further to above $1.1, after rising 1.6% in its biggest daily jump since 2016 in the previous session, after a more hawkish than expected ECB decision. The ECB said it may end asset purchases in Q3, earlier than previously expected as surging inflation more than offset concerns about Russia's shock invasion of Ukraine. The bloc’s inflation is already running at record highs and is now likely to be more persistent on the back of higher commodity prices and a tight labour market. Meanwhile, market participants await European Union leaders to unveil the bloc's policy response to Russia's invasion of Ukraine. There were reports recently that EU leaders were considering joint bond issuance to finance energy and defense spending. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/austria/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-10 20:51:43 </td>
   <td style="text-align:left;"> Austria 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Austria 10 Year Government Bond Yeld increased to a 3-year high of 0.686% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/10/europe/denmark-refugees-ukraine-syrian-intl/index.html </td>
   <td style="text-align:left;"> 2022-03-10 20:49:47 </td>
   <td style="text-align:left;"> Denmark opens its arms to Ukrainians, while trying to send Syrian refugees home - CNN </td>
   <td style="text-align:left;"> (CNN)When Denmark became the first liberal democracy to tell Syrian refugees to return to their war-torn home in 2019, Russian jets were still dropping missiles in Syria, in an effort to help President Bashar al-Assad's regime regain control of the country.                                                                                                                                                        , Ukraine is now being pummelled by the same Russian military, forcing more than 2.2 million people to flee to neighboring countries, according to the United Nations.                                                                                                                                                                                                                                                      , But instead of being met by xenophobia, detention centers and threats of repatriation in the European Union, Ukrainian refugees are being welcomed by European nations like Denmark with open arms.                                                                                                                                                                                                                       , "When there is war in Europe and a European neighbor is exposed to what we see in Ukraine, there is not the slightest doubt in my mind: We must help as best we can ... by welcoming Ukrainians on Danish soil," said Mattias Tesfaye, the Danish minister for foreign affairs and integration, soon after Russia invaded Ukraine in late February.                                                                       , The Danish government is drafting legislation that will suspend asylum rules for Ukrainians, Rasmus Stoklund, the foreign affairs spokesperson for Denmark's ruling Social Democratic Party, told CNN.                                                                                                                                                                                                                    , "They won't be part of the asylum system," Stocklund told CNN. Instead the proposed law will make it easier for Ukrainians to receive residency permits "so they can quickly start in school, on an education or in a job," according to a statement by the Danish immigration and integration ministry.                                                                                                                  , This would be in line with the European Union granting temporary protection for Ukrainians, allowing them to enter the bloc without a visa and to choose which country to go to.                                                                                                                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                                                                                           , Those eligible would be given protected status -- similar to that of a refugee -- in any EU country for a one-year period, which may be reviewed in future. This is a stark contrast with the EU's asylum rules where refugees must ask for asylum in the first member state they entered. Efforts by the EU to reform this system and help to equitably resettle asylum-seekers around the bloc have been unsuccessful.  , But critics are accusing the Danish government of hypocrisy, since it is currently urging Syrian refugees originating from Damascus and its surrounding countryside to return there, despite the ongoing civil war and the regime's brutal reputation.                                                                                                                                                                    , While fighting has subsided considerably in the region around Damascus, activists say the Danish government is actively putting Syrians in harm's way.                                                                                                                                                                                                                                                                    , In a statement to CNN, the Danish Ministry of Immigration and Integration Affairs said all refugees were treated the same. "Regardless of the law on temporary residence permits for persons expelled from Ukraine, all persons applying for asylum in Denmark have the same rights in the Danish asylum system."                                                                                                         , It added that about 30,000 Syrians who have been granted a residence permit in Denmark since 2014 still live in the country.                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                           , But Michala Clante Bendixen, the head of Refugees Welcome Denmark, which advocates for a streamlined asylum system, said the disparity in treatment suggests the government places a higher value on White lives.                                                                                                                                                                                                         , Bendixen said the 2015 migrant crisis had shown that: "If people arrive from Afghanistan or Syria, they will be met with suspicion, they will be called migrants until they [gain] refugee [status]. But now we immediately call Ukrainians refugees. What's the difference?                                                                                                                                              , "It's so disappointing and so terrible that people are so limited in their empathy with other human beings in the world," she added.                                                                                                                                                                                                                                                                                      , Punitive policies                                                                                                                                                                                                                                                                                                                                                                                                         , Syrian-born siblings Dania and Hussam, who integrated fully into Danish society after arriving in the country as refugees in 2015, have been caught in Denmark's anti-immigrant dragnet, say campaigners.                                                                                                                                                                                                                 , The pair, now in their 20s and fluent Danish speakers, have spent the past year in limbo, after Danish authorities decided not to extend their father's residency permit, which their own visas are linked to. They are appealing the decision.                                                                                                                                                                           , Last year, the siblings told CNN they feared that if they had to return to Syria, they could be punished for "turning our backs" on the regime. Hussam also risks being conscripted into the Syrian army, he said.                                                                                                                                                                                                        , An estimated 600 of the more than 35,000 Syrian refugees who traveled to Denmark have been stripped of their residency status by immigration authorities, Bendixen says.                                                                                                                                                                                                                                                  , While the Danish government cannot repatriate Syrians as it does not have diplomatic relations with Syria, it aims to compel them to leave by making Denmark as inhospitable a place as possible to live in, and covering their travel costs to return, say asylum experts.                                                                                                                                               , In 2021, Tesfaye, the Danish minister for immigration and integration, defended the policy in a statement to CNN, saying that "Denmark has been open and honest from day one" that residence permits for Syrian refugees are "temporary, and that the permit can be revoked if the need for protection ceases to exist.                                                                                                   , "The approach of the Danish government is to provide protection to those in need of it, but when the conditions in their home country have improved, former refugees should return to the home country and reestablish their life there," Tesfaye added.                                                                                                                                                                  , Those who have exhausted all legal avenues to appeal their lost residency status face being sent to deportation facilities, which Bendixen describes as open-air prisons designed to break people down.                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                                                           , The centers are partially open, which means that occupants are able to move in and out freely, but they have to check in every evening, have no income, and no right to work or study. One such center is around four miles from the nearest bus stop, making practically impossible for anyone to leave.                                                                                                                 , The move is just one of a number of policies by Danish authorities that appear to target the country's non-White immigrant community, critics say.                                                                                                                                                                                                                                                                        , In 2019, the government began to control where immigrants lived by forcing social and ethnic change in 15 low-income housing estates across the country. Authorities described them as "hard ghettos," and are defined by Danish regulations partly according to the races of residents.                                                                                                                                  , And as Syrians braved treacherous journeys to reach the safety of Europe, a so-called jewelry bill was rolled out in 2016, allowing the government to take certain assets from asylum-seekers to contribute to the country's welfare state.                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                           , "We might as well be honest about the fact that we would rather help Ukrainian refugees than Somalians and Palestinians," The former Liberal Party immigration minister Inger Stojberg, whose party pushed through the so-called jewelry bill, wrote on Facebook on Wednesday. "No one dares to say it like it is: It's because the Ukrainians are more like us and because they are primarily Christians."               , Stoklund, foreign affairs spokesperson for the ruling Social Democratic Party, told CNN the jewelry law will not apply to Ukrainians as they will not be part of the asylum system if the draft legislation is approved.                                                                                                                                                                                                  , That opt-out is "unfair," according to Bendixen, especially considering the financial burden other non-European refugees face in trying to reach safety. "Ukrainians can just travel as tourists into Europe," since they have enjoyed visa-free status in the EU since 2017.                                                                                                                                             , "They don't need human smugglers," she explained. "They don't need to risk their lives on small sinking boats or in the desert to travel safely to Europe ... they will not have to go through the asylum system -- which is very slow and can easily take a year before you get your case decided."                                                                                                                      , Despite this, descriptions of Ukrainian refugees from politicians and in the media could not be more different to the chaotic response to the 2015 migrant crisis driven largely by the Syrian civil war.                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                           , "Part of the answer has to do with identity," wrote migration and asylum expert Lamis Abdelaaty on Twitter. "Ukrainians are seen as White, Christian. Syrians, Afghans, and others are not perceived this way. People sympathize with refugees who they think share their race, religion, etc."                                                                                                                           , "But identity is not the whole story," said Abdelaaty, an assistant professor at Syracuse University in the US state of New York. "There is a foreign policy dimension to this too. It matters that Ukrainians are fleeing a Russian invasion. Welcoming them is another way for European countries to condemn Putin and to powerfully signal which side of the conflict they are on."                                    , The 2015 migrant crisis saw an estimated 1 million asylum-seekers enter Europe. They were greeted by a skeptical press, a rise in anti-migrant policymaking -- as seen in Denmark -- and a rise in support for far-right parties, following a series of ISIS terrorist attacks over the following year.                                                                                                                   , "And, now, suddenly, even more people are arriving in two weeks and everybody's like: 'Oh, yeah, we can handle it and we have lots of space and they should be welcome,'" Bendixen said.                                                                                                                                                                                                                                  , As Russian airstrikes become more indiscriminate, the United Nations said Tuesday that the outflow of Ukrainian refugees hit 2 million as mainly women, children, and the elderly seek refuge from the unprovoked aggression. Those numbers are expected to swell as attacks intensify on a number of key cities and towns.                                                                                               , The response to Russia's invasion of Ukraine shows that countries like Denmark can take in refugees with compassion. The color of a refugee's skin, or their religion, should not have any bearing on that response, activists say.                                                                                                                                                                                       , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/interest-rate </td>
   <td style="text-align:left;"> 2022-03-10 20:49:00 </td>
   <td style="text-align:left;"> ECB Speeds Up Asset Purchase Schedule </td>
   <td style="text-align:left;"> The ECB surprisingly speed up the asset purchase schedule for the coming months during its March 2022 meting and said that the APP could end in the third quarter if the medium-term inflation outlook will not weaken. Monthly net purchases will now amount to €40 billion in April, €30 billion in May and €20 billion in June, compared to €40 billion in Q2, €30 billion in Q3 and €20 billion in Q4 previously set. Key interest rates were kept at record low levels. During the press conference, President Lagarde said the ECB now sees inflation at 5.1%, higher than 3.2% early projected while GDP growth for this year is now seen slightly lower at 3.7% compared to 4.2%. Lagarde added that the Russia-Ukraine war "will have a material impact on economic activity and inflation through higher energy and commodity prices, the disruption of international commerce and weaker confidence". </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/finland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-10 20:48:29 </td>
   <td style="text-align:left;"> Finland 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Finland 10 Year Government Bond Yeld increased to a 3-year high of 0.689% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/netherlands/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-10 20:48:12 </td>
   <td style="text-align:left;"> Netherlands 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Netherlands 10 Year Government Bond Yeld increased to a 3-year high of 0.525% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/norway/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-10 20:46:48 </td>
   <td style="text-align:left;"> Norway 10Y Bond Yield Hits 7-1/2-year High </td>
   <td style="text-align:left;"> Norway 10 Year Government Bond Yeld increased to a 7-1/2-year high of 2.202% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coal </td>
   <td style="text-align:left;"> 2022-03-10 20:42:00 </td>
   <td style="text-align:left;"> Coal Eases from Record Peak </td>
   <td style="text-align:left;"> Coal prices corrected to below $400 per tonne, moving away from a record high of $425 hit in the previous session amid some technically-driven selling. Fundamentals in the coal complex continue to be supported by fears of further supply-chain disruptions and low inventories. Mounting sanctions on Russia for invading Ukraine led to an international energy crunch and exacerbated concerns about an already tight market. On top of that, limited access to European ports led to a rush by utilities in Asia and Europe to find alternative suppliers, such as Australia. On the demand side, Europe's thermal coal imports reached their post-pandemic peak last October, at 7.5 million tons, bringing total coal inventories to the region's lowest point in many years. Coal prices have more than doubled in value since the beginning of 2022, with earlier bullish sentiment already fueled by supply disruptions in top exporting countries such as Indonesia and Australia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/industrial-production </td>
   <td style="text-align:left;"> 2022-03-10 20:39:00 </td>
   <td style="text-align:left;"> Belgium Industrial Output Growth at 11-Month Low </td>
   <td style="text-align:left;"> Belgium’s industrial production rose 7.1 percent year-on-year in January of 2022, slowing down from an upwardly revised 12.8 percent climb in December. It was the slowest increase in eleven months, as growth in manufacturing industries slowed significantly (7.5 percent vs 13.4 percent in December), along with utilities (3.4 percent vs 7.4 percent), while output in mining and quarrying contracted (-5.7 percent vs 28.3 percent). On a seasonally adjusted monthly basis, production edged up 0.4 percent, slowing from an upwardly revised 2.3 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/croatia/producer-prices-change </td>
   <td style="text-align:left;"> 2022-03-10 20:20:25 </td>
   <td style="text-align:left;"> Croatia Producer Price Inflation at Fresh All-Time High </td>
   <td style="text-align:left;"> Producer price inflation in Croatia edged up to a fresh all-time high of 17.2 percent in February of 2022, from 17.1 percent in the previous month. Upward pressure came mainly from soaring energy costs (59.9 percent vs 58.7 percent in January); followed by robust growth in prices of intermediate goods (11.1 percent vs 11.0 percent); and durable consumer goods (8.4 percent vs 8.0 percent). To a lesser extent, positive contributions also came from capital goods (4.1 percent vs 4.0 percent) and non-durable consumer goods (3.4 percent vs 2.9 percent). On a monthly basis, consumer prices went up 1.5 percent, slowing from a 1.8 percent gain in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/retail-sales </td>
   <td style="text-align:left;"> 2022-03-10 20:16:00 </td>
   <td style="text-align:left;"> Brazil January Retail Sales Rebound More than Expected </td>
   <td style="text-align:left;"> Brazil's retail sales rose 0.8 percent from a month earlier in January of 2022, following a revised 1.9 percent drop in December and beating market expectations of a 0.3 percent increase. Growth was driven by sectors of equipment and supplies for computer and communication office (0.3%), pharmaceutical, medical, orthopaedic and perfumery articles (3.8%), and other articles of personal and domestic use (9, 4%). On an annual basis, retail sales went down 1.9 percent, less than the 2.9 percent contraction in December and market expectations of a 2.65 percent fall. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-03-11 09:15:04 UTC +8

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
   <td style="text-align:left;"> 2022-03-11 09:14:45 </td>
   <td style="text-align:left;"> $TMC what do yall think about the LME freezing the trade of Nickel to protect the Chinese investors that were short?  This is nuts!! How can they just admit that? $NAK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:14:38 </td>
   <td style="text-align:left;"> $DWAC $spy I think this might be on my list of my last meals during nuclear winter week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:14:33 </td>
   <td style="text-align:left;"> $SPY fire sale tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:14:17 </td>
   <td style="text-align:left;"> $SPY The world has just changed forever like after COVID in Feb once the market realize there is no going back to what we just did to russia and russia married to china and eventually a split in the world economies the market will crash , this quick two day war is a spark that eventually leads to the confrontation with China and maybe world war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:13:52 </td>
   <td style="text-align:left;"> $SPY papa Johns, 8 pack of Guinness, bottle of vodka and bottle of sake. No wife, probably with her boyfriend. Imma get more tanked then these futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:13:41 </td>
   <td style="text-align:left;"> $SPY $385 eom! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:13:40 </td>
   <td style="text-align:left;"> $SPY He is not suicidal.

He make Hillary mad? 
PT184 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:13:22 </td>
   <td style="text-align:left;"> $SPY Friday the 13-1 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:13:18 </td>
   <td style="text-align:left;"> $SPY oh very nice !!

BTD !

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:13:16 </td>
   <td style="text-align:left;"> $SPY $AMZN $QQQ &amp;#39;;&amp;#39;;&amp;#39;&amp;#39;; 
 
Account Challenge Update  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $55,749 
Goal: $100,000 by end of May.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 amazing-trading-room.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:13:08 </td>
   <td style="text-align:left;"> $SPY watch this you fucking bull morons </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:13:00 </td>
   <td style="text-align:left;"> $SPY LOOOOOOOL 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:12:44 </td>
   <td style="text-align:left;"> $SPY $BTC.X imagine we had a system of voting in this country backed by block chain where everyone got a vote on packages and legislation preventing corrupt officials from constantly taking bribes and coercion votes  
that would be cool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:12:42 </td>
   <td style="text-align:left;"> $SPY COMMON  MMs    5 to 7 red candles followed by  humongous green candle  
 
do your job </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:56 </td>
   <td style="text-align:left;"> $SPY Anyone remember SPY before 300? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:56 </td>
   <td style="text-align:left;"> $SPY bulls be like btfd inflation is bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:44 </td>
   <td style="text-align:left;"> $SPY tomorrow’s open will be:

a. Beneath today’s low
b. Tomorrow’s high
c.  To the mooooon #SPY500
d.  Both a. and b. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:32 </td>
   <td style="text-align:left;"> $SPY 10am data btw tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:30 </td>
   <td style="text-align:left;"> $SPY is made for day traders. If you are interested in swing trades, go for stocks instead. @stockspastor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:28 </td>
   <td style="text-align:left;"> $SPY the only reasonable thing here is to go short into next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:17 </td>
   <td style="text-align:left;"> $SPY look guys i have it from here. You lost all day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:11 </td>
   <td style="text-align:left;"> $SPY Bitcoin will go to 8k after that executive order $AAPL $AMZN $MSFT $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:10 </td>
   <td style="text-align:left;"> $SPY if we don’t go down -5% tomorrow, I will drive a screwdriver down my urethra </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:11:06 </td>
   <td style="text-align:left;"> $SPY ES1! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:55 </td>
   <td style="text-align:left;"> $SPY reversal with the hammer here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:46 </td>
   <td style="text-align:left;"> $SPY will be so bad calls holders overnight can’t sleep tonight 🤣🤣🤣🤣🤣🤣🤑🤑🤑🩸🩸🩸🩸🩸🤑🩸🩸🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:41 </td>
   <td style="text-align:left;"> $SPY seriously I’m done giving this away … nobody likes me anyway… lol.  If you look back you’ll see I called 100 baggers.  Hit me up if you have good ideas too.  Peace </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:36 </td>
   <td style="text-align:left;"> $SPY poor low this morning just saying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:34 </td>
   <td style="text-align:left;"> $SPY that Jason Haigh though 😂😂 
“I didn’t go there to die. I obviously thought about it but I had a job to do” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:33 </td>
   <td style="text-align:left;"> $CCL $SPY  Added to my short. Not expecting much tomorrow given the current sentiment and it being a Friday. To much uncertainty to hold over the weekend. Will close and add more to my long position if it drops back in the 15/16s. Good luck bulls/bears 👌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:26 </td>
   <td style="text-align:left;"> $SPY What exactly are we spending on billions of dollars to ukraine? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:21 </td>
   <td style="text-align:left;"> $SPY Putin got pee tapes of every politician in the world . He doesn’t have to use nukes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:20 </td>
   <td style="text-align:left;"> $SPY kuroda is like “omg 9% PPI yesterday what do I do?! What do I dooo?” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:09 </td>
   <td style="text-align:left;"> $SPY looks like gap down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:10:01 </td>
   <td style="text-align:left;"> $SPY terrible news… 5000 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:09:52 </td>
   <td style="text-align:left;"> $SPY interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:09:48 </td>
   <td style="text-align:left;"> $SPY Free money Friday is for the puts I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:09:26 </td>
   <td style="text-align:left;"> $SPY why is it dropping AH, any new news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:09:14 </td>
   <td style="text-align:left;"> $SPY more hedge funds getting bailed out and stoped buy and sell . $AMC $GME  open and fair market lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:09:11 </td>
   <td style="text-align:left;"> $SPY 400 or straight to 340 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:09:09 </td>
   <td style="text-align:left;"> Inflation Fiasco: The Devil’s in the Details -- article I wrote for Crush the Street https://www.crushthestreet.com/cts-news/inflation-fiasco-the-devils-in-the-details $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:09:07 </td>
   <td style="text-align:left;"> $SPY I really S&amp;amp;P 3850 is in our future! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:09:03 </td>
   <td style="text-align:left;"> $SPY Imma be so pissed if I was off by 1 day to load puts for fat ass drop, so pissed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:09:02 </td>
   <td style="text-align:left;"> $SPY seems so!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:08:54 </td>
   <td style="text-align:left;"> $SPY why don’t they deploy Jared Kushner and his wife? we need peace </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:08:41 </td>
   <td style="text-align:left;"> $SPY $MULN $AMC    All that you need to know. Shorts haven&amp;#39;t covered a single share; Check it out below 👇  
  
highly recommend everyone to follow them.. 🚀   sweepcast.stockmarketmovers.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:08:37 </td>
   <td style="text-align:left;"> $SPY probably… gonna hold 2000 here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:08:37 </td>
   <td style="text-align:left;"> $spy $qqq Yellen cursed future generations of Americans and Powell is trapped. And delusional or a really convincing liar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:08:33 </td>
   <td style="text-align:left;"> $SPY I gave you the fucking chart an hour ago … done…. Now pay me $100 every week you dumb Fuchs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:08:30 </td>
   <td style="text-align:left;"> $SPY can’t believe people are bullish in this economy what y’all smoking? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:08:14 </td>
   <td style="text-align:left;"> $SPY futes rippin they said 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:08:12 </td>
   <td style="text-align:left;"> $SPY Jessie smollet sentenced to jail! 

Complete perjury in court!

😃 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:08:02 </td>
   <td style="text-align:left;"> $SPY can cancel culture just cancel the war? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:43 </td>
   <td style="text-align:left;"> $SPY $MULN $AMC   $1800 into $40k in the last 30 days,. If you really want to make huge profits on trading then, Join this winning chat:..  sweepcast.stockmarketmovers.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:41 </td>
   <td style="text-align:left;"> $SPY why the tank? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:30 </td>
   <td style="text-align:left;"> $SPY news: half the global wheat for 2022 or so lost if not planted this week in Ukraine, rip the poor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:29 </td>
   <td style="text-align:left;"> $ES_F: Nice rally to close the day but rejected 4260 resistance and produced a lower high on the daily. Bears still in control here unless bulls can take out 4260 and then 4275 level. Above 4275 we see a retest of 4300. Under 4260, we are vulnerable to retest 4220 and then 4200. 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:28 </td>
   <td style="text-align:left;"> $SPY $QQQ Thanks God nobody holding any stocks overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:27 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F 
No more FED QE
China stopping oil exports 
Russia goes offline 
fun time 
https://www.vice.com/en/article/88gevb/russia-is-preparing-to-cut-itself-off-from-the-global-internet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:19 </td>
   <td style="text-align:left;"> $SPY I hate red days but tbh I LOVE day trading with this volatility

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:16 </td>
   <td style="text-align:left;"> $SPY block bath all the way from now to Friday we may see $410 🤑🤑🤑🤑🤑🩸🩸🩸🩸🩸🤑bulls nothing to hope for bad news not come more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:13 </td>
   <td style="text-align:left;"> $SPY lmfao i cant help but ppst this GIF when everyone tried to tell the bulls and their vision was blurred and now they are gonna be crying, wondering why there call option expiring tomorrow is going to get crushed,

here we go bulls, buckle up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:07:11 </td>
   <td style="text-align:left;"> $SPY Bulls think sending $13 billion to Ukraine (soon to be under Russia) is bullish?! LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:06:54 </td>
   <td style="text-align:left;"> $SPY big red dongs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:06:53 </td>
   <td style="text-align:left;"> $SPY friday came early for bulls. totally non existent today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:06:31 </td>
   <td style="text-align:left;"> $SPY what now? lol , these futes are becoming all to familiar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:06:24 </td>
   <td style="text-align:left;"> $SPY Please -100 on futures tonight, just this once </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:06:22 </td>
   <td style="text-align:left;"> $SPY ahhh yes, and so the rug pull begins. A day worse than any we have seen this year may just be upon us </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:06:20 </td>
   <td style="text-align:left;"> $BTC.X that executive order cutting the artery on this $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:06:18 </td>
   <td style="text-align:left;"> $SPY its over bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:06:00 </td>
   <td style="text-align:left;"> $SPY $QQQ  $DIA &amp;quot;War is show business&amp;quot; sheep! Watch this classic movie. I&amp;#39;m telling you.. This shit gets old 🥱🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:05:50 </td>
   <td style="text-align:left;"> $SPY hmm

futes

... looks VERY VERY close to the bottom for the night !!!

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:05:44 </td>
   <td style="text-align:left;"> $SPY want an update bulls?  I mean,…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:05:43 </td>
   <td style="text-align:left;"> $SPY oh?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:05:29 </td>
   <td style="text-align:left;"> $SPY 15k on /es volume.   
I think they messed up the decimal point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:05:18 </td>
   <td style="text-align:left;"> $SPY I knew they’d wait until 8 pm.  I used to always brag about this stuff ahead of time but now I see why the best traders never talk about their trades </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:05:14 </td>
   <td style="text-align:left;"> $SPY $QQQ   
 
https://www.forbes.com/sites/chuckjones/2021/10/30/biden-is-trouncing-trumps-stock-markets-where-it-matters/?sh=6650278d2de4 
 
Despite the recent slump, there is no doubt that stock investors are making more money under Biden than they did under Trump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:05:14 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F $USO $OIL well bulls 
that’s an unpleasant surprise 

https://oilprice.com/Energy/Energy-General/China-Asks-State-Owned-Refiners-To-Halt-Gasoline-Diesel-Exports.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:05:06 </td>
   <td style="text-align:left;"> U.S. SENATE SETS VOTE THURSDAY NIGHT ON PASSAGE OF $1.5 TRILLION GOV&amp;#39;T FUNDING BILL INCLUDING $13.6 BILLION AID FOR UKRAINE 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:55 </td>
   <td style="text-align:left;"> $SPY China drone strike on Saudi Arabia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:46 </td>
   <td style="text-align:left;"> $SPY U.S. SENATE SETS VOTE THURSDAY NIGHT ON PASSAGE OF $1.5 TRILLION GOV&amp;#39;T FUNDING BILL INCLUDING $13.6 BILLION AID FOR UKRAINE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:42 </td>
   <td style="text-align:left;"> $SPY Everyone go fill up your car, lawnmower and anything that uses oil/gas so that the price can be “priced in”… ;) 

That, and the end of QE, should be enough to retest the 405 area. 

The market needs to retest those eras to have solid ground. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:40 </td>
   <td style="text-align:left;"> $SPY 5 months!!!! Pathetic!!!🤮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:34 </td>
   <td style="text-align:left;"> $SPY 2021 monthly highs and lows, I organized the percentage difference. The average for 2021 high/low variance is 5.142% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:31 </td>
   <td style="text-align:left;"> $SPY nato yesterday called putins army weak and starving. I bet tomorrow he does a all out offensive and sacks ukraine overnight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:29 </td>
   <td style="text-align:left;"> $SPY embiid=MVP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:24 </td>
   <td style="text-align:left;"> $SPY we will get a limit down tmrw market it. dow -5% spy -5% qqq -5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:23 </td>
   <td style="text-align:left;"> $SPY I wouldn&amp;#39;t be surprised to see this green tomorrow. CPI came in as expected that they were some prices in there that actually came down. So.. We&amp;#39;ll see 👀 $QQQ $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:21 </td>
   <td style="text-align:left;"> $SPY anybody else held their puts, do you think they are going ti print tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:12 </td>
   <td style="text-align:left;"> $SPY wowza ES dumping harder than futures…. Don’t see it this off very often </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:10 </td>
   <td style="text-align:left;"> $SPY damping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:08 </td>
   <td style="text-align:left;"> $SPY circuit breaker would be fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:06 </td>
   <td style="text-align:left;"> $SPY CHYYYNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:04:01 </td>
   <td style="text-align:left;"> $SPY Sheesh tank it cramer $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:03:49 </td>
   <td style="text-align:left;"> $SPY 2024 40 strike Baba puts because USA is king </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:03:48 </td>
   <td style="text-align:left;"> $SPY covered another NQ 13525 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:03:44 </td>
   <td style="text-align:left;"> $SPY Can you imagine the pea sized balls on Powell if he doesnt raise at all? 

He is going to say gas prices solve inflation and he&amp;#39;s open to a new round of QE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:03:39 </td>
   <td style="text-align:left;"> $SPY seriously I’m going to meme invest. 4/20 puts @ 420 strike. IT CANT GO TITS UP!!!!!! I’ll post daily position updates once they open and I buy em </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:03:34 </td>
   <td style="text-align:left;"> $SPY 🔥😵 My conviction will pay off. 150 handle drip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:03:26 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:03:20 </td>
   <td style="text-align:left;"> $SPY I thought today was supposed to be the big bad sell-off.. bears becoming protected species </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:03:18 </td>
   <td style="text-align:left;"> $SPY nice little night for me, had a couple rough ones this week, stopped swinging hard last night and today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:03:04 </td>
   <td style="text-align:left;"> $SPY we’re gonan tank so hard, its hilarious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:02:56 </td>
   <td style="text-align:left;"> $QQQ $SPY wow, just got a 15% raise at work… guess that takes care of the inflation and gas price problem 😳🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:02:47 </td>
   <td style="text-align:left;"> $SPY we up ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:02:39 </td>
   <td style="text-align:left;"> $SPY $QQQ Sentenced to 5 months jail, 30 months probation 
 
Some advice for anybody trying to stage a hate crime: Don&amp;#39;t come to heavily Democrat Chicago and ask two black guys to wear MAGA hats and pretend to attack you and say &amp;quot;This is MAGA country&amp;quot;... nobody&amp;#39;s gonna believe you, N.O.B.O.D.Y.🤪 
https://www.msn.com/en-us/news/world/brittney-griner-has-been-in-russian-custody-for-3-weeks-congressman-says-as-questions-remain-about-her-whereabouts/ar-AAURYa8?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:02:39 </td>
   <td style="text-align:left;"> $SPY SPY 2022-03-10 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=2szb_VspV2c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:02:34 </td>
   <td style="text-align:left;"> $SPY CHINA... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:02:12 </td>
   <td style="text-align:left;"> $SPY 🔥😵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:02:06 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:02:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Hey Perma-bulls…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:59 </td>
   <td style="text-align:left;"> $SPY covered a NQ at 13550 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:55 </td>
   <td style="text-align:left;"> $SPY dear bears, ya’ll puts printing tomorrow. Yewwwww! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:49 </td>
   <td style="text-align:left;"> $SPY the world vs Russia that&amp;#39;s a tough fight for Putin.  Heavy artillery is old school bio weapons coming up next.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:34 </td>
   <td style="text-align:left;"> $DWAC $SPY $TSLA futures tanking, did Kamala Harris say something stupid again? IMPEACH AND REMOVE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:26 </td>
   <td style="text-align:left;"> $SPY a game I like to play is logging onto ST at night, reading through the posts, and trying to figure out if futes are red or green

🤣🤣📈🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:23 </td>
   <td style="text-align:left;"> $SPY good 2nd close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:22 </td>
   <td style="text-align:left;"> $SPY these bulls tricked me lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:18 </td>
   <td style="text-align:left;"> $SPY Cramer can&amp;#39;t be wrong 100% of the time can he? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:11 </td>
   <td style="text-align:left;"> $SPY back to my chart 😂 white line is current </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:10 </td>
   <td style="text-align:left;"> $SPY 🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:08 </td>
   <td style="text-align:left;"> $spy $dwac $fb $twtr

So Facebook and Twitter will now allow calls for violence against Russians

It&amp;#39;s amazing how their policies adapt to their political stances. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:08 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F Largest outflow ever from European equities </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:01:04 </td>
   <td style="text-align:left;"> $SPY  
 
Based on the playbill, this is supposed to touch 414 tomorrow  
 
Cray-craymer went full Doomsday tho... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:00:53 </td>
   <td style="text-align:left;"> $SPY I’m the most polite way we’re all a bunch of jack asses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:00:45 </td>
   <td style="text-align:left;"> $SPY inflation is transitory, dollar store is going to be renamed as “fitty sents” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:00:37 </td>
   <td style="text-align:left;"> $SPY When OFG returns it will signal the end of this bear market. Like the return of Aslan in Narnia 🦁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:00:28 </td>
   <td style="text-align:left;"> $SPY worst feeling when I’m bearish and I hear on this board that Cramer is also bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:00:26 </td>
   <td style="text-align:left;"> $SPY This is potentially a very bad omen for equities. The 10 year yield broke out of this inverse head and shoulders pattern, retested the breakout as the Ukraine/Russia war unfolded, and is now heading higher. This would make equities significantly less attractive for investors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:00:25 </td>
   <td style="text-align:left;"> $SPY someone post the spy chart projecting a mega drop back to the 5 year tredline </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:00:13 </td>
   <td style="text-align:left;"> $SPY what happen today 🐻 i thought 🖨 was off??? oh ya bulls aren&amp;#39;t broke you wouldn&amp;#39;t understand either way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:00:08 </td>
   <td style="text-align:left;"> $SPY gas prices have me fucked moo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 09:00:00 </td>
   <td style="text-align:left;"> $SPY 
On watch for that .50 rate hike next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:59:50 </td>
   <td style="text-align:left;"> $SPY ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:59:50 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:59:46 </td>
   <td style="text-align:left;"> Largest outflow EVER from European equities  
 
would be nice if come to usa market  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:59:45 </td>
   <td style="text-align:left;"> $SPY I feel bad for bulls … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:59:43 </td>
   <td style="text-align:left;"> $SPY 8pm fear 4am horror 930am burial </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:59:34 </td>
   <td style="text-align:left;"> $SPY waiting for stocktwits to give away teslas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:59:04 </td>
   <td style="text-align:left;"> $SPY 🔥😵 oh this is only getting started. Hundred handle is what I envision. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:59:01 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F just a note worth noting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:58:55 </td>
   <td style="text-align:left;"> $SPY kinda hungry but not really. More sleepy but couldn’t sleep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:58:33 </td>
   <td style="text-align:left;"> $SPY goodnight sweet darling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:58:33 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $BTC.X $AMZN Hillary insurance nobody want to be clintened.😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:58:30 </td>
   <td style="text-align:left;"> $dwac $spy $qqq

Can someone tell me what is a climate refugee?

Why do democrats expect 100 million climate refugees to USA? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:58:06 </td>
   <td style="text-align:left;"> $SPY  
 
It&amp;#39;s distribution.  Let&amp;#39;s see who can learn and apply, lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:57:36 </td>
   <td style="text-align:left;"> $SPY inflation officially at 7.5%, unofficially it&amp;#39;s at 30-50% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:57:29 </td>
   <td style="text-align:left;"> $SPY Every stock boards looking for OFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:57:17 </td>
   <td style="text-align:left;"> $SPY Roll old 401(k) or 403(b) into Fidelity or Scwab.  This way you can buy inverse 3x ETFs to balance out your normal 401k. 

Better yet take a 79(t) and roll without penalty into an after tax ROTH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:57:05 </td>
   <td style="text-align:left;"> Anyone here bullish on $spy and $DIA ?

Besides buying long term calls on these symbols, why not sell short term calls against your position?

Preferably calls with a delta of 0.3?

Selling such calls can help lower the cost basis of your long term calls positions

I’ve done up a YouTube tutorial on the POOR MAN’s COVERED CALL

For those who are keen to know how it works, pls take a look!

The Poor Man&amp;#39;s Covered Call - A Cheaper Alternative to the Covered Call
https://youtu.be/-9VTlFK7mh0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:57:03 </td>
   <td style="text-align:left;"> $SPY cramer says bottom is 328 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:56:53 </td>
   <td style="text-align:left;"> $SPY I don’t know about y’all but Tucker is about to be on, time to light up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:56:51 </td>
   <td style="text-align:left;"> $SPY when limit down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:56:39 </td>
   <td style="text-align:left;"> $SPY  
 
Craymer being ultra bear is fookin with my head </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:56:22 </td>
   <td style="text-align:left;"> $SPY 😂 😂 😂. YOU BULLS ARE FACKED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:56:17 </td>
   <td style="text-align:left;"> $SPY If Russia doesn&amp;#39;t agree to settle its war with Ukraine in diplomatic talks then Russia&amp;#39;s own commanders will turn around and march on Moscow itself to oust Putin you heard it here first. USA and Europe wins in the end regardless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:56:09 </td>
   <td style="text-align:left;"> $SPY       $434 on Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:56:08 </td>
   <td style="text-align:left;"> Morgan Stanley warns more losses in China $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:57 </td>
   <td style="text-align:left;"> $SPY lol fake ass dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:53 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F High DIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:52 </td>
   <td style="text-align:left;"> $SPY nothing like margin calls to end the week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:46 </td>
   <td style="text-align:left;"> $SPY I remember when +/- 0.50% was the extent of gains and losses for a day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:38 </td>
   <td style="text-align:left;"> $SPY oh you thought these lines were for fun? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:24 </td>
   <td style="text-align:left;"> $SPY needs a 200 retest before going back up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:24 </td>
   <td style="text-align:left;"> $SPY futes dippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:21 </td>
   <td style="text-align:left;"> $SPY bounced off indicator </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:16 </td>
   <td style="text-align:left;"> $SPY spy is ripping AH!   Oh ...... nvn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:10 </td>
   <td style="text-align:left;"> $SPY 383 tmrw, and russia conflict is not a war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:55:01 </td>
   <td style="text-align:left;"> $SPY lol why did futes just drop $1 right before AH close? Fuckery. My poor calls 🥵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:54:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Big facts 🩸📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:54:54 </td>
   <td style="text-align:left;"> $SPY death cross by mid march </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:54:54 </td>
   <td style="text-align:left;"> $SPY here we go 🩸🩸🩸🩸overnight more news come more bad news come $415 🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:54:38 </td>
   <td style="text-align:left;"> $SPY pay attention to the war so you don’t see Washington screw the porch on the economy here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:54:38 </td>
   <td style="text-align:left;"> $SPY is this news related here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:54:29 </td>
   <td style="text-align:left;"> $SPY lol short and a half </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:54:22 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:54:06 </td>
   <td style="text-align:left;"> $SPY 415 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:53 </td>
   <td style="text-align:left;"> $SPY in the end it doesn&amp;#39;t even matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:45 </td>
   <td style="text-align:left;"> $SPY boom $420 tomorrow at open 🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:43 </td>
   <td style="text-align:left;"> $SPY the average monthly change in 2021 was 2.05% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:43 </td>
   <td style="text-align:left;"> $SPY futures ain&amp;#39;t got no dandruff with that head and shoulders. Clean </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:42 </td>
   <td style="text-align:left;"> $SPY kyrie Irving is fine. Pause </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:24 </td>
   <td style="text-align:left;"> $SPY LETS ALL JUMP ON MOOOOO  MOBILE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:13 </td>
   <td style="text-align:left;"> $spy $dwac JUICY GETS 5 MONTHS IN JAIL!!!!!! 😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:10 </td>
   <td style="text-align:left;"> $SPY y’all see that head and shoulders on the 15? 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:09 </td>
   <td style="text-align:left;"> $SPY hmmmm which way will it go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:53:06 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $MSFT 

RSI = RELATIVE STRENGTH INDEX

It is intended to chart the current and historical strength or weakness of a stock or market based on the closing prices of a recent trading period.

This is a fantastic tool when used correctly!Study up on this indicator and learn to trade with it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:52:42 </td>
   <td style="text-align:left;"> $SPY LOL so the overnight rug on bulls begins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:52:40 </td>
   <td style="text-align:left;"> $SPY oh yeah drop the futes red lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:52:18 </td>
   <td style="text-align:left;"> $SPY I called 435 today but IT WILL BE 435 tomorrow.  And you can put that in all caps!!!  Such a weak red day, tomorrow is green for sure!!  Hedgies gotta collect that put option premium!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:52:10 </td>
   <td style="text-align:left;"> $SPY we all have levels… where are yours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:52:04 </td>
   <td style="text-align:left;"> $SPY does options expire tmr? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:51:47 </td>
   <td style="text-align:left;"> $SPY flat as fuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:51:41 </td>
   <td style="text-align:left;"> $SPY All this talk, but let&amp;#39;s see who&amp;#39;s holding over the weekend ? Lol. Yack,Yack.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:51:19 </td>
   <td style="text-align:left;"> $SPY back to 15 pe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:50:54 </td>
   <td style="text-align:left;"> $SPY just waiting for lil durk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:50:39 </td>
   <td style="text-align:left;"> $SPY bounced off chartbolt white line </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:50:25 </td>
   <td style="text-align:left;"> Alright! Enough research for tonight. We killed it today. New plays tomorrow. Good night fam $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:50:10 </td>
   <td style="text-align:left;"> $SPY tomorrow is Friday.. what are they going to do? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:50:01 </td>
   <td style="text-align:left;"> $SPY  we got this shit!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:49:58 </td>
   <td style="text-align:left;"> $SPY so $AMZN included to $RIVN stock as part of earnings 4th qtr. that stock has tanked! Now what do you suppose they do for first qtr? Smoke and mirrors. House of cards. It’s all fake! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:49:49 </td>
   <td style="text-align:left;"> $SPY bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:49:36 </td>
   <td style="text-align:left;"> $SPY stay lit 🔥 and btd 🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:49:05 </td>
   <td style="text-align:left;"> $SPY if you open a short dated position when the 3m, 15m, and 1hr are all at an extreme end of RSI and where it&amp;#39;s outside of a Bollinger band, it&amp;#39;s literally free money. Hardly ever all aligns like that, but when it does, you gotta pull the trigger. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:49:03 </td>
   <td style="text-align:left;"> $SPY I went LONG oil again. 10 contracts - 106.80 average cost. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:48:35 </td>
   <td style="text-align:left;"> $SPY On the 30m chart, if it finishes filling up that gap it could be a potential H&amp;amp;S. Chart feedback/critique is welcome 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:48:32 </td>
   <td style="text-align:left;"> $SPY docusign and oracle diving $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:48:27 </td>
   <td style="text-align:left;"> $SPY bro don&amp;#39;t you all see it doesn&amp;#39;t even matter. Bull, Bear, Theta betas, kang gang, boomer hedge fund guy, quant guy, etc, all are being fucked by one single entity.  Once everyone gets mad that this asshole is buying all our orders and fixing it so they always come out ahead (no matter how long it takes). 

Citadel is the exchange, its time they were regulated as one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:48:21 </td>
   <td style="text-align:left;"> $SPY Did someone say something about a… dump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:48:15 </td>
   <td style="text-align:left;"> $SPY perhaps my yolo call will pay out. 😃

If not -&amp;gt; ☹️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:48:13 </td>
   <td style="text-align:left;"> $SPY The sad part is that when they pull the rug, people will act surprised,  but the cheat codes are literally in front of your eyes right now, 

be a rational trader, not a blind one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:48:00 </td>
   <td style="text-align:left;"> $SPY WHAT IS WRONG THE  VIX IS SUPPOSE TO GO DOWN IT IS HEADING  UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:47:49 </td>
   <td style="text-align:left;"> $BTC.X if the digital dollar comes out, this will go to Zero so fast $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:47:45 </td>
   <td style="text-align:left;"> $SPY  
 
I can&amp;#39;t figure out how to switch my charts to the metric system </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:47:36 </td>
   <td style="text-align:left;"> $SPY   $DOCU 
 
Once again the Motley Fool Gang has done well to get their clients to buy a great stock all the way up the mountain and then lose millions.  $DOCU 
 
These guys need to get real and stop losing money for those who paid for a service. Don&amp;#39;t they know we are in a bear market and in a new recession with nasty ramifications? 
 
When the SPY is living in the 410-420 area, maybe some will see the light?  Maybe not.  400 is down the road, not now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:47:26 </td>
   <td style="text-align:left;"> $SPY  take note 📝 not always exact but take note The mid noon prop ups  🕛 &amp;amp; the 2pm prop ups </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:46:55 </td>
   <td style="text-align:left;"> $SPY $QQQ Recession coming your way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:46:44 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m bullish for the next week or two. 

Seriously. Bear market rallies are part of this decline. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:46:30 </td>
   <td style="text-align:left;"> $SPY Any charting apps that allow you to change the chart scale to logarithmic? Maybe it would make the chart look less crazy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:46:27 </td>
   <td style="text-align:left;"> $SPY 03/10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:46:20 </td>
   <td style="text-align:left;"> $SPY bollinger bands tightening, get ready for move to start when NIKKEI opens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:46:15 </td>
   <td style="text-align:left;"> $SPY 03/09 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:46:10 </td>
   <td style="text-align:left;"> $SPY If not for reserve currency status fed will be printing 100000 bill today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:45:59 </td>
   <td style="text-align:left;"> $SPY these guys bought all the fancy IPOs now they’re down 80% lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:45:20 </td>
   <td style="text-align:left;"> $SPY The average target date fund has lost 3.7yrs of its value. 

Thats like losing all your 401(k) match and 30% of your deferrals. 

Americans are subsidizing the rich via 401(k) expenses and a complete lack of anti-correlated assets inside of planned fiduciary control. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:45:13 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:44:29 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:44:12 </td>
   <td style="text-align:left;"> $SPY … I can’t miss on these calls…. ill never financially recover . $6k in may baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:44:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA

Go back to the bull side Crammer, we don’t want you with us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:43:49 </td>
   <td style="text-align:left;"> $SPY It’s right up on this resistance line, even staying at current price through premarket would break through it. Breaking through a 6 day resistance line in premarket usually sends the price down sharply at open to retest that resistance with intraday volume. After that it could go up or down up to 3%, maybe multiple times tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:43:19 </td>
   <td style="text-align:left;"> $SPY Tbis is the worst market. What big nef on the Dow a bit.  A little of everything ?  Slow and grindy?  Looked so shitty.  Every day a new thing.  Saw stocks down grind and make back some.  Nothing looked good. So hard for ken </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:43:02 </td>
   <td style="text-align:left;"> $SPY  
 
I really hope we are not the bad guy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:42:54 </td>
   <td style="text-align:left;"> $SPY I have a feeling my 434/435 bear call spread expiring tomorrow will turn out fine.. Thanks for the freebie! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:42:53 </td>
   <td style="text-align:left;"> $SPY   $QQQ 
 
Crude got some relief this week but the turmoil will continue as the catalysts that dropped it are not etched in stone at all but the speculators could not take the chance. 
 
$108-  $115 until other factors raise the price for crude even more.  High gas prices will be here for quite a while. 
 
Markets and cos will suffer as Putin needs $100+ oil. 
 
Wild days ahead for sure. Trying times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:42:39 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:42:19 </td>
   <td style="text-align:left;"> $SPY why are we putting up with masks for an airborne virus still??? Its fucking nonsense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:42:15 </td>
   <td style="text-align:left;"> $SPY broke the support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:42:02 </td>
   <td style="text-align:left;"> $SPY Ben Simmons is a 🐱 
#TrustTheProcess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:41:57 </td>
   <td style="text-align:left;"> $SPY make America energy independent!!! FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:41:53 </td>
   <td style="text-align:left;"> $SPY 3 down 3 to go on rates hike bluffs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:41:47 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:41:34 </td>
   <td style="text-align:left;"> $SPY nukes ain’t happening stop trying to trick yourself in you worthless puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:41:15 </td>
   <td style="text-align:left;"> $SPY i see 380 becoming the floor in the next few weeks, 

GL bulls, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:40:53 </td>
   <td style="text-align:left;"> $SPY fine print.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:40:39 </td>
   <td style="text-align:left;"> $SPY remember where we are bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:40:14 </td>
   <td style="text-align:left;"> $SPY let’s all sell so my puts print then buy at lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:40:04 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F Better than reality TV 

https://www.dailymail.co.uk/news/article-10597799/Now-Russia-accuses-experimenting-bat-coronavirus-samples-Ukraine.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:40:03 </td>
   <td style="text-align:left;"> $SPY All clear for $410 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:39:52 </td>
   <td style="text-align:left;"> $SPY down the Russian commie govt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:39:45 </td>
   <td style="text-align:left;"> $SPY corporate bonds lulz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:39:36 </td>
   <td style="text-align:left;"> $SPY  could be our last night on Stocktwits earth 🌏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:39:34 </td>
   <td style="text-align:left;"> $SPY Test 427.74 tomorrow 
 
OK 
 
Vulture </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:39:29 </td>
   <td style="text-align:left;"> $SPY that extra $20 drop to the low 400&amp;#39;s looks tasty though. April opex? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:39:13 </td>
   <td style="text-align:left;"> $SPY where are we going tonight boys? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:39:12 </td>
   <td style="text-align:left;"> $SPY You all can have the @ 400s. They’re stupid! @ 300s are way cooler 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:39:01 </td>
   <td style="text-align:left;"> $SPY All good guys. Jessie Smoulet or how ever you spell that fktards name sentences to 5 months in jail! Def limit up. And chargers got Khalil Mack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:39:00 </td>
   <td style="text-align:left;"> Although the technical rating is bad, $SPY does present a nice setup opportunity. https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:38:53 </td>
   <td style="text-align:left;"> $SPY Saddest thing is so many fine women in Ukraine that deserve asylum here in West coast... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:38:53 </td>
   <td style="text-align:left;"> $SPY  
Putin showing receipts tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:38:52 </td>
   <td style="text-align:left;"> $SPY why are the teachers in Minneapolis crying for? They make an average of $71k and have off all summer. If they actually worked all year they would make about $100k and that goes a long way in cheap ass Minneapolis. What am I missing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:38:45 </td>
   <td style="text-align:left;"> $SPY why do i feel like putin is going to do some dumbass shit and use a nuke to try and end the war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:38:29 </td>
   <td style="text-align:left;"> $SPY bongs be hittin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:38:24 </td>
   <td style="text-align:left;"> $SPY inflation too high and fed gonna print, only &amp;#39;there&amp;#39;s an old saying in Tennessee — I know it&amp;#39;s in Texas, probably in Tennessee — that says, fool me once, shame on — shame on you. Fool me — you can&amp;#39;t get fooled again&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:38:20 </td>
   <td style="text-align:left;"> $SPY Im honestly not sure &amp;quot;300&amp;quot;s will happen either. It should, be we all know how &amp;quot;shoulda/couldas&amp;quot; work.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:38:06 </td>
   <td style="text-align:left;"> $SPY flutes be rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:37:57 </td>
   <td style="text-align:left;"> $SPY from today&amp;#39;s action I believe it will more likely go up tomorrow, then sell off second part of day into the weekend, as fear for some bad news over it still high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:37:21 </td>
   <td style="text-align:left;"> $SPY 2022 bulls bought the @ 400s. 

2020 - 2021 bulls bought the @ 300s :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:36:45 </td>
   <td style="text-align:left;"> $SPY https://apple.news/AV9iRKvkjTheLfNzSMEUXRg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:36:36 </td>
   <td style="text-align:left;"> $SPY Do we have jobs reporting tomorrow?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:36:35 </td>
   <td style="text-align:left;"> $SPY @ 300s yummmm!!!!! You all can have the @ 400s ewwwww! 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:36:19 </td>
   <td style="text-align:left;"> $SPY 🔥 ofc US will deny relentlessly but shit is getting real dooky spicy. Send Hunter and Biden to prison, and add Fauci and Pelosi as bonus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:36:08 </td>
   <td style="text-align:left;"> $SPY stfu about 300s not happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:35:53 </td>
   <td style="text-align:left;"> $SPY next weeks forecast, includes tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:35:40 </td>
   <td style="text-align:left;"> $SPY this will go to MA before it goes down. It’s the way it goes. Puts/shorts might have tough time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:35:38 </td>
   <td style="text-align:left;"> $SPY @ 300s are going to be glorious! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:35:26 </td>
   <td style="text-align:left;"> $SPY If the SPY were to be priced equivalent to the hang seng it would be sitting around 180-190 right now. That&amp;#39;s crazy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:35:21 </td>
   <td style="text-align:left;"> $SPY So, guess ww see 416 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:35:10 </td>
   <td style="text-align:left;"> $SPY puts and calls all day. Why you bears and bulls fighting. You fight cause you’re losing. Small positions and still printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:34:46 </td>
   <td style="text-align:left;"> $SPY  385-400 incoming .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:34:41 </td>
   <td style="text-align:left;"> $SPY Who the fuck still supports Biden 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:34:12 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:33:52 </td>
   <td style="text-align:left;"> $SPY  $UWMC so that&amp;#39;s good for shorts right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:33:33 </td>
   <td style="text-align:left;"> $SPY nothing can save the VIX GOIN UNDER 30 25 20  NOTHING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:32:46 </td>
   <td style="text-align:left;"> $SPY  weekly/4hr 

 Scenario for flat open, Options day trade targets  circled in Blue 🤝Up/down pivot (trigger) is the red line just above 422.5 for downside momentum. While 427.5 is trigger for momentum to the upside  @wesjensen @Mrbinks @EaglePowers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:32:40 </td>
   <td style="text-align:left;"> $SARK Sad to hear Cathie Woods is pretty much dead. When funeral for ARK Invest? $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:32:30 </td>
   <td style="text-align:left;"> $SPY Jesus Kremlin relax... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:32:24 </td>
   <td style="text-align:left;"> $SPY $USO   inflation about to fall off cliff.. 10 year rate already at 2%.. market gonna do a lot of it for the fed.  market should like the #Oil mustard dip..  Vix under 25 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:32:18 </td>
   <td style="text-align:left;"> $SPY $VIX the vix looks like it&amp;#39;s breaking down. On he weekly. Interesting to watch tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:32:17 </td>
   <td style="text-align:left;"> $SPY Can you imagine the total stupidity to say, &amp;quot;yes.  I&amp;#39;ve timed it.  Yes, it&amp;#39;s now - Im going bullish.  The entire market goes moon right now. Lambo&amp;quot; 

They are just low class degenerate gamblers with fathers that hate them. So sad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:32:15 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:32:05 </td>
   <td style="text-align:left;"> $SPY meaning like a beautiful flashing nuclear blast in the twilight sky?—————- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:31:39 </td>
   <td style="text-align:left;"> $SPY sketchy... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:31:35 </td>
   <td style="text-align:left;"> $SPY Crude oil is still high, but meaningfully lower than the last couple days. Vix is trending lower as well. Hopefully these 2 trends continue. I pulled this together for those that may find it helpful: https://youtu.be/OHKIsdTgVHQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:31:07 </td>
   <td style="text-align:left;"> $SPY bears are such dumbasses everyone knows stocks only go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:30:26 </td>
   <td style="text-align:left;"> $SPY 3 month chart.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:30:16 </td>
   <td style="text-align:left;"> $QQQ $SPY fill in the blank😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:30:09 </td>
   <td style="text-align:left;"> $SPY I paid for NO adds and still see ads occasionally…I need a no ads ads blocker. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:30:00 </td>
   <td style="text-align:left;"> $SPY im going out. Later dudes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:29:53 </td>
   <td style="text-align:left;"> $SPY feds gotta fix inflation dude it’s bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-03-11 08:29:35 </td>
   <td style="text-align:left;"> $SPY Hang seng close to touching prices from 2001. Them Boyz living in the past. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:13:16 </td>
   <td style="text-align:left;"> $SPY $AMZN $QQQ &amp;#39;;&amp;#39;;&amp;#39;&amp;#39;; 
 
Account Challenge Update  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $55,749 
Goal: $100,000 by end of May.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 amazing-trading-room.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:12:37 </td>
   <td style="text-align:left;"> $QQQ when was the last back to back Green Day’s? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:11:08 </td>
   <td style="text-align:left;"> $QQQ It’s all over, folks. Bloodbath tomorrow as everyone dumps before the weekend in case Putin uses chemical weapons or nukes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:09:33 </td>
   <td style="text-align:left;"> $QQQ Vix dying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:08:51 </td>
   <td style="text-align:left;"> Rihanna’s Lingerie Company Weighs IPO at $3 Billion Valuation $LVMUY $QQQ https://www.bloomberg.com/news/articles/2022-03-11/rihanna-s-lingerie-company-said-to-weigh-ipo-at-3-billion-value </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:08:37 </td>
   <td style="text-align:left;"> $spy $qqq Yellen cursed future generations of Americans and Powell is trapped. And delusional or a really convincing liar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:07:28 </td>
   <td style="text-align:left;"> $SPY $QQQ Thanks God nobody holding any stocks overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:07:09 </td>
   <td style="text-align:left;"> $QQQ why is the vix going to the moon rn? 🚀 🚀 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:06:48 </td>
   <td style="text-align:left;"> $QQQ $SQQQ we get paid tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:06:00 </td>
   <td style="text-align:left;"> $SPY $QQQ  $DIA &amp;quot;War is show business&amp;quot; sheep! Watch this classic movie. I&amp;#39;m telling you.. This shit gets old 🥱🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:05:14 </td>
   <td style="text-align:left;"> $SPY $QQQ   
 
https://www.forbes.com/sites/chuckjones/2021/10/30/biden-is-trouncing-trumps-stock-markets-where-it-matters/?sh=6650278d2de4 
 
Despite the recent slump, there is no doubt that stock investors are making more money under Biden than they did under Trump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:05:06 </td>
   <td style="text-align:left;"> U.S. SENATE SETS VOTE THURSDAY NIGHT ON PASSAGE OF $1.5 TRILLION GOV&amp;#39;T FUNDING BILL INCLUDING $13.6 BILLION AID FOR UKRAINE 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:04:33 </td>
   <td style="text-align:left;"> $QQQ get ready to gap down 3% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:04:23 </td>
   <td style="text-align:left;"> $SPY I wouldn&amp;#39;t be surprised to see this green tomorrow. CPI came in as expected that they were some prices in there that actually came down. So.. We&amp;#39;ll see 👀 $QQQ $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:03:47 </td>
   <td style="text-align:left;"> $UAVS Glad I got my swing avg @.96 can’t wait to see what this has to offer tomorrow after that move into close and with other countries looking to increase defense spending the blue listing news headline from today will definitely give this a huge push into tomorrow and just wait till they realize they’re bigger than JUST a defense stock 📈  $LMT $RTX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:03:18 </td>
   <td style="text-align:left;"> $QQQ Nikkei, Hang Seng and Dax all bloody red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:03:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 81740400. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:02:56 </td>
   <td style="text-align:left;"> $QQQ $SPY wow, just got a 15% raise at work… guess that takes care of the inflation and gas price problem 😳🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:02:39 </td>
   <td style="text-align:left;"> $SPY $QQQ Sentenced to 5 months jail, 30 months probation 
 
Some advice for anybody trying to stage a hate crime: Don&amp;#39;t come to heavily Democrat Chicago and ask two black guys to wear MAGA hats and pretend to attack you and say &amp;quot;This is MAGA country&amp;quot;... nobody&amp;#39;s gonna believe you, N.O.B.O.D.Y.🤪 
https://www.msn.com/en-us/news/world/brittney-griner-has-been-in-russian-custody-for-3-weeks-congressman-says-as-questions-remain-about-her-whereabouts/ar-AAURYa8?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:02:27 </td>
   <td style="text-align:left;"> $QQQ who wants to own stocks over the weekend with an erratic nuclear Putin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:02:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Hey Perma-bulls…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 09:01:26 </td>
   <td style="text-align:left;"> $QQQ futes bleeding badly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:59:50 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:59:46 </td>
   <td style="text-align:left;"> Largest outflow EVER from European equities  
 
would be nice if come to usa market  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:58:40 </td>
   <td style="text-align:left;"> $QQQ Should see a 400-450 point sell off on the NDX tomorrow 

Metals pricing heading up again
Precious metals too
Crude oil and gas headed up again
Putin’s looking for a win and I believe he’s got something big planned for tomorrow 
Profit taking likely tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:58:30 </td>
   <td style="text-align:left;"> $dwac $spy $qqq

Can someone tell me what is a climate refugee?

Why do democrats expect 100 million climate refugees to USA? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:54:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Big facts 🩸📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:46:55 </td>
   <td style="text-align:left;"> $SPY $QQQ Recession coming your way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:44:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA

Go back to the bull side Crammer, we don’t want you with us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:43:24 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:42:53 </td>
   <td style="text-align:left;"> $SPY   $QQQ 
 
Crude got some relief this week but the turmoil will continue as the catalysts that dropped it are not etched in stone at all but the speculators could not take the chance. 
 
$108-  $115 until other factors raise the price for crude even more.  High gas prices will be here for quite a while. 
 
Markets and cos will suffer as Putin needs $100+ oil. 
 
Wild days ahead for sure. Trying times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:40:12 </td>
   <td style="text-align:left;"> $QQQ It&amp;#39;s kinda eerie how flat the futures are. We&amp;#39;re either going sideways or down tomorrow it seems. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:38:39 </td>
   <td style="text-align:left;"> $QQQ futes R.I.P.ping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:38:31 </td>
   <td style="text-align:left;"> $QQQ Saying we can&amp;#39;t when we AmeriCAN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:36:58 </td>
   <td style="text-align:left;"> $QQQ ALL I WANT FOR THIS CHRISTMAS IS TO GAIN BACK MY MONEY MY PORTFOLIO IS CURRENTLY DOWN 70% EVER SINCE LAST NOVEMBER 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:32:16 </td>
   <td style="text-align:left;"> $QQQ Both VIX + Crude lower today. Hoping this trend continues. I pulled this together for those that may find it helpful: https://youtu.be/OHKIsdTgVHQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:30:16 </td>
   <td style="text-align:left;"> $QQQ $SPY fill in the blank😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:28:56 </td>
   <td style="text-align:left;"> $SPY $QQQ the new FAANG! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:28:05 </td>
   <td style="text-align:left;"> $QQQ Option Alert.. 👀 👀  $341 Call for Friday, March 11. Roughly 11 Thousand dollars! 💰💰 Learn more on StockOrbit at https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:27:02 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ $XLE This news could move markets in a big way, but I&amp;#39;m not yet seeing it reflected in the price of crude. Why not? Perhaps preliminary reports of this earlier this week contributed to the huge spike Tuesday, so it&amp;#39;s already priced in somewhat? Or traders just haven&amp;#39;t seen the news. It&amp;#39;s late in Europe.  https://www.politico.eu/article/iran-nuclear-talks-close-to-collapse-over-russian-demands/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:27:00 </td>
   <td style="text-align:left;"> $QQQ $SPY Longs for the last 3 months trying to catch the bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:26:53 </td>
   <td style="text-align:left;"> $QQQ $SPY 10 Yr up 15% from this weeks low but no one is talking about it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:26:38 </td>
   <td style="text-align:left;"> $SPY  $QQQ  - mesa gota bad feeling about this.   
 
 I fear one last good down leg. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:25:51 </td>
   <td style="text-align:left;"> $SPY $QQQ 

REMINDER

And good evening to everyone except the futures crack addicts. We are not actually being mean to them here we just can’t get them to answer the door at their house because of that station in the basement. Take a break that screen will still be red or green I think </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:25:47 </td>
   <td style="text-align:left;"> $QQQ 
I&amp;#39;m waiting for tomorrow evening to buy puts. I&amp;#39;m hoping for an upswing being that we just crossed over into positive territory. Should touch $338. No promises. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:22:32 </td>
   <td style="text-align:left;"> $SPY $QQQ you guys honestly have no idea the magnitude of that IQ increase..

Instead of normally blocking Reddit kids with those god damn rocket emojis 🚀 , yesterday we actually had convos about nuclear reactors. I think we pumped the right market this time. No risk pumping this one, keep that shit up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:21:38 </td>
   <td style="text-align:left;"> $QQQ big drop coming. Brokers are calling put holders... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:21:11 </td>
   <td style="text-align:left;"> $QQQ 317 by next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:15:54 </td>
   <td style="text-align:left;"> $TSLA 

Realistic price targets when this $QQQ bubble actually pops...

(Fair Value)
Share Price: $65
Market Cap: $65.25 Billion
P/E: 12x
P/S: 1.2x

(Justifiable Premium)
Share Price: $75
Market Cap: $77.80 Billion
P/E: 14.5x
P/S: 1.45x

(Bubble)
Share Price: $100
Market Cap: latex64ac648c2a68c7c497c1b9c7d4cb1a52F: 9.15x, 0.48x, 1.39x
$TM: 8.13x, 1.35x, 1.0x
Tesla: 175x, 18.0x, 28.0x

(Margins -- Gross, Operating, Net)
Ford: 15.9%, 3.3%, 13.2%
Toyota: 19.7%, 10.4%, 9.9%
Tesla: 25.3%, 12.1%, 10.2%

(Growth --1 Year Trailing Results)
Ford: 5.0%
Toyota: 12.5%
Tesla: 65.0%

(Growth -- 5Y Forward CAGR Estimates)
Tesla: 21.70%
Toyota: 23.00%
Ford: 74.15% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:13:16 </td>
   <td style="text-align:left;"> $TNX , $QQQ , $RUT : Its coming ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:10:35 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ 

We all know the next few months are gonna be a 🤡 show, but for tomorrow at least…face ripper 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:09:07 </td>
   <td style="text-align:left;"> $SPY  I’m Long Calls here   💲🧞‍♂️💲🚀🚀

I hope it would go red to buy more calls 

I am very bullish on a extraordinary short squeeze in a couple hours  $QQQ $SPX $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:08:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM technical analysis for tomorrow. 
 
https://youtu.be/XboKLsxPO58 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:07:44 </td>
   <td style="text-align:left;"> $QQQ who has been victimized by the stock market this year, please raise your hand 🙋🏾‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:07:04 </td>
   <td style="text-align:left;"> $QQQ nbvvvn up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:06:14 </td>
   <td style="text-align:left;"> $SPY ??? 
 
Yeah!  Hope everyone was able to exit the markets today near the highs. 
 
We are moving slowly into the USA market abyss even though we don&amp;#39;t want it.  The future is just plain bloody and these small rallies are great to unload stocks. 
 
The deep erosion has yet to be respected and that&amp;#39;s OK for those who want to exit on stocks on recent highs. 
 
SPY @ 390 will be very troubling. 
 
 
$QQQ   wild times are here.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:02:15 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-10 Trade Analysis Video: 
https://www.youtube.com/watch?v=aWegW4XkxUs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 08:01:03 </td>
   <td style="text-align:left;"> $QQQ $SPY Futes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:59:47 </td>
   <td style="text-align:left;"> $QQQ $SPY Food inflation global going 300% within 2 years, half the planet is going to starve, but sure keep buying bubble stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:57:52 </td>
   <td style="text-align:left;"> $SPY pump it pump it 🤣 $DIA $QQQ $IWM with death cross already and  $SPY  is next☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:56:35 </td>
   <td style="text-align:left;"> $SPY Long time Bullish Short Term Bullish on a unprecedented short squeeze 

  Rally mode now $QQQ $DIA $NDX $SPX 

It’s the truth guys I’m not playing games </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:56:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL This is a very angry boomer 👉@Partridge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:54:48 </td>
   <td style="text-align:left;"> $SPY $QQQ oh great as if the Russian drama isn&amp;#39;t enough, the China situation heating up, inflation at all time highs. .. Now we got Rocketman here to take down the market. 

CNN: US assesses North Korea launches constitute use of new ICBM system.
https://www.cnn.com/2022/03/10/politics/north-korea-biden-administration/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:53:35 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures higher, market finished well of the intraday lows today and was a very good sign, plus a lot of bears probably don&amp;#39;t want to hold their shorts over the weekend just in case if Ukraine and Russia come up with a compromise to end the war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:53:13 </td>
   <td style="text-align:left;"> $QQQ if you are shorting this set up then you are playing with fire. IMO we are bottoming out. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:52:24 </td>
   <td style="text-align:left;"> $QQQ russia is banning 200 exports. Welp we are all gonna suffer. All for what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:49:41 </td>
   <td style="text-align:left;"> $QQQ $SPY Crude futes may have began to find support. I suspect oil will start ripping again to new highs in the next couple weeks. Who gives a fuck if OPEC says it wants to consider increasing production. I know my gas tank doesn&amp;#39;t. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:49:27 </td>
   <td style="text-align:left;"> $QQQ bought puts at close yesterday and sold for 100% gain at the bell. Bought puts at close today, gonna sell for 100% gain at the bell. Seeeee yaaaaaaa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:48:45 </td>
   <td style="text-align:left;"> $QQQ When some weird rich people stuff happens and I&amp;#39;m happy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:46:18 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA  … so can we retire peaking inflation now. Feds are totally screwed because they sat on they hands for mo the whole inflation keep accelerating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:44:03 </td>
   <td style="text-align:left;"> $SPY $QQQ 

I am buying $5 billion worth tomorrow. Bottom is in! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:42:24 </td>
   <td style="text-align:left;"> $SHLX sitting at a shell right now that has cheaper gas than all the surrounding stations in the area and it is freaking packed… $SPY $SHEL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:42:09 </td>
   <td style="text-align:left;"> $SPY $QQQ 

somehow even the shitposting here on Stocktwits has managed to significantly improve. I’m kinda scared what the hell did we do here?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:40:50 </td>
   <td style="text-align:left;"> $QQQ Futes are flat as hell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:40:47 </td>
   <td style="text-align:left;"> $QQQ Amazing.  Amazon  saves the market,and somehow  managed to save itself  all day long.  Almost a miracle. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:40:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Bouta win this auction on a first edition pack of pokemon cards for $200… lets hope I pull somethin good👌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:39:51 </td>
   <td style="text-align:left;"> $QQQ anyone like how this found support at a premarket support line from a few days ago while halfway filling a gap?😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:39:35 </td>
   <td style="text-align:left;"> $QQQ seems similar to yesterday where it was range bounce until 5pm PST and then started dropping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:37:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Pooots got me iced out ❄️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:35:01 </td>
   <td style="text-align:left;"> $SPY   Everybody      SHORT SQUEEZE 

. $QQQ                $NASDAQ $NDX          $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:33:19 </td>
   <td style="text-align:left;"> $QQQ $SPY forst it was earnings holding up the market now it’s oil going down and cpi hitting expectations…. Smdh. They come up with anything to take your money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:32:17 </td>
   <td style="text-align:left;"> $SPY $QQQ The market is a mirror of all of our flaws. Trading is one of the most  tough and humbling things you will ever experience. There is a reason why 90% of traders fail and give up within the first 3 months. It&amp;#39;s because they come in overhyped, undercapitalized, thinking it&amp;#39;s some get rich quick scheme. The fact is, it&amp;#39;s a long game that takes many years of hard work to be successful at. It&amp;#39;s a serious business.  
 
The market doesn&amp;#39;t care about you, your problems or your dreams.  It will eat you alive if you are not disciplined. It is also always changing, so you have to learn to adapt. You aren&amp;#39;t trading against the market participants, but you are actually trading against yourself. It will be here tomorrow, next week and many years from now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:29:32 </td>
   <td style="text-align:left;"> Daily Market Recap for Thursday 3/10/2022 for trending #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/cQjb0xG8GT0

$SPY $QQQ $IWM $TLT $UUP

Market recap!!  Check it out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:29:09 </td>
   <td style="text-align:left;"> $BTC.X $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:26:47 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Lot of Hopium and Denial out there in the bull camp… You’re right, we’re oversold. But thing is, the market don’t care. There only “is” in the market. No if and’s or but’s. Look at the charts and see the message it is sending. It is definitely different than our accustomed 10%+ average annual return and “stonks only go up” $DOCU $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:25:47 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK

Puts lookin like Arnold Schwarzenger💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:25:28 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F    💲🧞‍♂️💲 $QQQ $DIA 

Word around the Street is S&amp;amp;P May

 Be $4600 by next Friday. That’s the Street 

  I am going with the flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:24:17 </td>
   <td style="text-align:left;"> $SPY $QQQ You know you&amp;#39;ve been blocked by a lot of people when you log out and suddenly see twice as many posts on the SPY thread😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:23:30 </td>
   <td style="text-align:left;"> SELLER EXHAUSTION 
 
RELIEF RALLY TO ENSUE 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:23:08 </td>
   <td style="text-align:left;"> $QQQ hoping for another oil spike , Saudi gonna tell us to get fucked lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:22:10 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Wen green day bulls?!.....🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:19:01 </td>
   <td style="text-align:left;"> $SPY $QQQ I’ve seen this movie before </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:18:58 </td>
   <td style="text-align:left;"> $QQQ $DOCU $CRWD $CVX $SHOP 

Market is extremely short sighted.

2020 it’s pandemic stocks.. to the moon and come back.

2022 it’s oil stocks it’s to the moon &amp;amp; come back By 2024

Stay invested quality. There will always be the reason to SELL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:17:52 </td>
   <td style="text-align:left;"> $QQQ I’m gonna cum!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:17:08 </td>
   <td style="text-align:left;"> $TMC is running AH. 🚀🚀
TMC has worlds largest known NICKEL deposits. It has a resource equivalent to $4,980 per share but trading at $2s. Only few short shares available. Definitely a moonshot play. DD video here. https://vimeo.com/373812645
$DJIA $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:16:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $SPX 

It’s rare we see a President do so many things right this early on in his term.

Biden, you magnificent beast.

Keep up the outstanding work, our economy is roaring. 

Takes notes - Conserva-Tards 🇺🇸✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:16:28 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

You bulls think I fear a little pump, 

ah-ha-ha-ha🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:15:54 </td>
   <td style="text-align:left;"> $QQQ risk on, Janet doesn&amp;#39;t believe we are headed to recession $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:12:41 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Treasury Secretary Yellen says Don&amp;#39;t Expect a Recession in the U.S. &amp;quot;  That&amp;#39;s because we&amp;#39;re in for either depression or hyperinflation.  $uvxy $sqqq $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:12:32 </td>
   <td style="text-align:left;"> $QQQ u know if the Feds actually stayed on top of they 2% inflation mandate instead of letting it run wild and crazy thru the economy we wouldn’t be in this position. By sitting on they hands and saying things will be transitory or peaking they could be saying “because of our heroic actions to raise rates and slow demand, we are able to be flexible and help Americans with price hikes”. But now they gonna raise rates while inflation accelerating causing a worse effect than the pandemic already caused </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:12:14 </td>
   <td style="text-align:left;"> $QQQ dance on bears grave </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:10:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN CANOES SHIPPIN JUST ASK SCOTTIE PIPPEN 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:09:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $BTC.X 

#PUTINPRICEHIKE

If it wasn’t for gosh damn Putin and the international conflict going on right now, gas would still be below $3 per gallon. What a shame what they are doing to our country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:08:39 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm $labu
Market has flushed out a lot of permabull, now it’s over due to flush out all the permabears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:08:18 </td>
   <td style="text-align:left;"> $QQQ china refused to supply Russian with aircraft parts. It&amp;#39;s over russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:08:06 </td>
   <td style="text-align:left;"> $SPY $QQQ the market always does the obvious thing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:06:22 </td>
   <td style="text-align:left;"> $SPY funny that numbers came in right at expectation. It all comes down to politics. Every administration has done but now is getting a little ridiculous. Like I said earlier, The Fed can only keep doing this BS for so long. Once the floor gives and they can&amp;#39;t prop the markets the drop will be epic. For now... Take advantage 💵😎
$AAPL $QQQ $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:04:02 </td>
   <td style="text-align:left;"> $SPY $QQQ im n luv with a stripper ❤️❤️❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:03:24 </td>
   <td style="text-align:left;"> $SPY $QQQ Wen McButts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:02:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 81740400. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 07:01:03 </td>
   <td style="text-align:left;"> $QQQ Emotionless upward channel. With everyone short, a squeeze has potential. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:56:05 </td>
   <td style="text-align:left;"> $SPY $qqq You stupid idiots everything was going great in 2019 2020 and you messed it all up last year and this year now you pray to oil  and pray to the Yields </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:55:07 </td>
   <td style="text-align:left;"> $QQQ $SPY funny how we pick and chose between oil and yeilds to inverse the market. Meanwhile yeilds are running hard on the oil dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:54:57 </td>
   <td style="text-align:left;"> $SPY  Supply and Demand is Tight now

        $nasdaq $ndx $dia $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:53:50 </td>
   <td style="text-align:left;"> $QQQ it&amp;#39;s funny that the bad news was that inflation was almost exactly what it was estimated to be... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:51:02 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:49:18 </td>
   <td style="text-align:left;"> $QQQ extremely weird price action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:46:49 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Wen moon fanboys?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:46:44 </td>
   <td style="text-align:left;"> $SPY $DIA $DJIA $QQQ 

I got the case that indexes can squeeze 1% 

After hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:44:33 </td>
   <td style="text-align:left;"> $SPY SpY is halted at $425.  Haha

$425 Long ABOVE  ⬆️   $QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:44:14 </td>
   <td style="text-align:left;"> $SPY Fed eyeing a 1% raise in its next meeting, prob only gonna get a .75% tho $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:44:06 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ $NDAQ Looks like we are going to NUCLEAR war. My dad said that we are leaving this country next week. GLTA 

https://www.yahoo.com/news/harris-thanks-poland-helping-1-114635502.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:43:56 </td>
   <td style="text-align:left;"> $DPY $QQQ $TLT $TBT The 10yr looks explosive 

7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:41:26 </td>
   <td style="text-align:left;"> $SPY $QQQ and then there is this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:40:12 </td>
   <td style="text-align:left;"> $RIVN $SPY $QQQ 

worthless just like bulls calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:39:04 </td>
   <td style="text-align:left;"> $SPY $QQQ You know it’s bad when the volatility index’s are dumping and most stocks are down or sideways. Everyone is in commodities and doesn’t trust the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:38:50 </td>
   <td style="text-align:left;"> $UPST - long the best tech stock $UPST, but short $QQQ and $IWM going into tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:37:35 </td>
   <td style="text-align:left;"> $QQQ if you bought when RSI dropped to 30s over last four years, these are the times you would have bought! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:36:28 </td>
   <td style="text-align:left;"> $SPY 

Is this a short term short squeeze or long term 1 

    $spx $qqq $dia $ndx   Long or short term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:35:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $AMZN Who all here thinks Amazon should be added to the Dow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:35:29 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY yall ready to see the REAL dip? 😁😁😁😁😁😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:35:11 </td>
   <td style="text-align:left;"> $QQQ Green today, hot tamale. Green is usually hotter though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:33:35 </td>
   <td style="text-align:left;"> $QQQ who is splitting tomorrow? GOOGLE? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:31:34 </td>
   <td style="text-align:left;"> Volkswagen CEO says the Russia Ukraine War will be more devastating than COVID Pandemic 
61% of U.S. S&amp;amp;P500 Companies Revenues are Domestic 
 39% of U.S. S&amp;amp;P500 Companies Revenues are Internatiobal 
The Market will suffer and go lower 

$QQQ $SPY $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:30:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Rivian Automotive is tanking hard in after hours trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:28:46 </td>
   <td style="text-align:left;"> $ROKU no way I&amp;#39;m buying this now when I can get it for $60 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:27:48 </td>
   <td style="text-align:left;"> $SPY WE ARE LONG ABOVE $425 

$es_f $spx $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:24:24 </td>
   <td style="text-align:left;"> $SPY $QQQ lmao what a deal! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:22:33 </td>
   <td style="text-align:left;"> $SPY Squeeze above $4250   LONG $425

SQUEEZE $SPX $ES_F $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:20:35 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F    🧞‍♂️   $DIA $QQQ 

     Long above $4250   Or $425 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:20:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA death crosses happening on all three indices…squeeze plays could start popping off soon $AMC $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:19:10 </td>
   <td style="text-align:left;"> $QQQ  297.50 was a number to look for a year or so ago is it coming back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:17:52 </td>
   <td style="text-align:left;"> $QQQ can we see futes green for once tonight?  So f ing tired of red depressing red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:17:50 </td>
   <td style="text-align:left;"> $SPY $QQQ are there any wall street degen dating services out there? looking for the one that will want to discuss SPY price action 24-7 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:17:46 </td>
   <td style="text-align:left;"> $SPY  $QQQ Looks to me like we are going up. Tomorrow likely to gap up a little but then selloff to today&amp;#39;s lows and reverse to close higher.  
See pic of hourly NQ Futures $ES_F  
$XBI very promising, but you never know.  
 
https://www.tradingview.com/x/xfKx0AiF/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:16:29 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $DJIA $QQQ --- 
 
Finally one  Congressman who has the balls to speak the truth.   
 
https://www.yahoo.com/news/gop-rep-cawthorn-calls-zelensky-a-thug-says-ukraine-pushing-woke-ideologies-185128786.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:14:36 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 3/10/2022 $SPY $XLF $QQQ $AMZN $CCJ https://www.chartguys.com/daily-market-videos/4190/preparing-for-different-scenarios </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:12:47 </td>
   <td style="text-align:left;"> $SPY $QQQ 😁 $DIA $GME $AMC 

It’s going to be a amc gme squeeze on index’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:11:52 </td>
   <td style="text-align:left;"> $QQQ Market makers were playing with this all week. They trap bull and bears. What happens between now and next week. I’m laying in Bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:11:34 </td>
   <td style="text-align:left;"> $QQQ could open $323 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:11:32 </td>
   <td style="text-align:left;"> $SPY $DIA 😁 $QQQ $DIA $SPX 

Everyone got a put.    Super squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:10:40 </td>
   <td style="text-align:left;"> $QQQ  could open $338+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:10:37 </td>
   <td style="text-align:left;"> $SPY it’s a super short squeeze. $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:10:16 </td>
   <td style="text-align:left;"> NASDAQ $QQQ Top Gainers during today $CRWD $AMZN $ABNB $MAR 
  
Learn more: https://www.finscreener.org/screener/top-gainers/stocks/nq100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:09:35 </td>
   <td style="text-align:left;"> $QQQ $338 tomorrow 😜🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:09:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM  
 
Very high risk to just hold stocks as a swing trade. 
 
Bounces everywhere today but action is still (very) questionable. Lower high, lower lows. 
 
I sold most of my long positions today. I just don&amp;#39;t see it worth that risk. 
 
Some exceptions Example: $KR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:09:26 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM bleh...but the next few days &amp;quot;could&amp;quot; get very interesting.  Long or short, be mindful of your stop loss (as the 2/24 low is still in play). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:05:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $NIO $TSLA 

Imagine the violent rally if Putin got a bullet stuck in his head. All it takes is one hitman. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:05:16 </td>
   <td style="text-align:left;"> $QQQ Gap up to yellow line in play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:05:09 </td>
   <td style="text-align:left;"> $SPY $QQQ when this pump and dump will end ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:04:30 </td>
   <td style="text-align:left;"> $QQQ $SPY 5th straight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:03:12 </td>
   <td style="text-align:left;"> $SPY $QQQ Guy Adami is the single cause of the hair gel shortage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:02:05 </td>
   <td style="text-align:left;"> $QQQ Friday sell-off seems likely see $320&amp;#39;s tmw but there&amp;#39;s never been a better time to be a BULL &amp;amp; root for $340&amp;#39;s knowing it means good news for Ukraine/Western world, bear&amp;#39;s are essentially rooting for Putin currently to make a buck rather then switch side&amp;#39;s.. GL$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:00:15 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-10 Options Analysis Video: 
https://www.youtube.com/watch?v=zUt-TfQMCRs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 06:00:01 </td>
   <td style="text-align:left;"> $RIVN Revenue of $54 million and stock is valued at $40 billion. Very nice!  Who says that the market is NOT in a bubble?  lol 
 
I am surprised $ARKK is not holding it or do they?  You never know with Cathie as she loves these kinds of stocks with little to no revenue. smh 
 
Even though $TSLA is overvalued, at least they sell lots of cars and are a leader in the EV market.   
 
Oh well, all the froth in $RIVN and the likes have a long ways to go, imho. 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:56:41 </td>
   <td style="text-align:left;"> $AMZN claimed beat ER because of $RIVN investment and now $RIVN has bad ER. How do we justify this? Fake ER report? $QQQ $SPY this pos will go to $2000 and cancel stock split. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:55:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $SPX 

No Recession.               Pump it up time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:55:35 </td>
   <td style="text-align:left;"> $QQQ Anybody hoping the Feds will bail them out.. it&amp;#39;s done. Feds stopped doing asset purchases. They are not on your side anymore.. in fact they will be removing trillions from their balance sheet starting this year. Do not fight the Feds, this goes both ways! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:54:29 </td>
   <td style="text-align:left;"> $QQQ $DOCU $RIVN  shitty earnings definitely help bring the qqqs lower tommorw. Expecting Amazon profit taking before weekend. Puts goi g to print AGAIN ! Go bears ! 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:52:56 </td>
   <td style="text-align:left;"> How will this affect the market? $QQQ entered Uptrend as Momentum indicator ascends above 0 level. View odds of downtrend. https://srnk.us/go/3483416 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:52:33 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ rocket man waiting for his turn after putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:51:50 </td>
   <td style="text-align:left;"> $SPY $QQQ US Treasury Sec Yellen: Likely To See Inflation Stay Uncomfortably High This Year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:51:28 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 679.9K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:51:17 </td>
   <td style="text-align:left;"> $QQQ 3 tankers already for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:51:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $ARKK 

Growth stocks were the first into the fire back in Feb 2021.  

They will be the first out of the fire in 2022-2023.

Meanwhile big tech, value and bonds will be crushed by another 50-60% as the recession advances. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:50:49 </td>
   <td style="text-align:left;"> $QQQ Bulls are so desperate for good news 😂, the crash is inevitable ; just get with the program lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:50:47 </td>
   <td style="text-align:left;"> $QQQ Can this just die already. Can we just have the bottom? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:48:37 </td>
   <td style="text-align:left;"> $QQQ yellen helping out the bears , lol high inflation and slower growth . Love it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:46:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $IWM watching to Janet Yellen stumble around her words on CNBC is not a good look. Biden, Harris, Yellen, Jen Psaki.. the whole admin makes USA look so weak. Ugh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:44:57 </td>
   <td style="text-align:left;"> $QQQ $AAPL  $MSFT $GOOG  still need to pullback for that bottom to be in , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:40:16 </td>
   <td style="text-align:left;"> $QQQ $SPY Janet Yellen is so hot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:39:55 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ wht kind of BS is this let’s go ATHs+ already wtf these clowns losing back the best companies in the world they don’t give a crap about a war or anything!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:39:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY A Republican President would never do all these outrageous sanctions on Russia 
 
They&amp;#39;re not achieving the desired outcome, and instead are inflicting a lot of damage on innocent Russian people and soon the rest of the world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:38:40 </td>
   <td style="text-align:left;"> $SPY USA owes $142 Trillion in debt to China, Japan, and ...  the Federal Reserve!!!!   Too many people think the Federal Reserve is a federal agency.  Federal Reserve is a PRIVATE BANK that LENDS to US government.   WE, the PEOPLE, owe money to JPOW.   JPOW getting ready to COLLECT, which is called QT or monetary tightening via rate hike.   Rate hike is how THEY make profit.   $UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:38:38 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY $AMD 
Check out this this $CPI Breakout 
Next Month’s Report will be even worse!
Bad for Stonks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:37:05 </td>
   <td style="text-align:left;"> $SPY $ES_F $QQQ $DJIA $DIA 

Janet Yellen will speak the truth 

In five minutes.  Market moving </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:35:08 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX 

Janet Yellen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:34:43 </td>
   <td style="text-align:left;"> $QQQ That was a cute market prop idea with AMZN. Let&amp;#39;s see how long that lasts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:34:43 </td>
   <td style="text-align:left;"> $SPY $QQQ 

My bear senses are tingling of an 
un-godly pump tomorrow...🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:34:30 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY I hope these break in half again. Down another 69% from here pigs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:34:04 </td>
   <td style="text-align:left;"> $QQQ I believe qqq at this level is fair. Not much up and down….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:32:14 </td>
   <td style="text-align:left;"> $SQQQ $QQQ $SPY -$5.00 today lol man what a blood bath out there haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:31:09 </td>
   <td style="text-align:left;"> $SPY They didn&amp;#39;t wanted to be too obvious. Is the only reason it didn&amp;#39;t close green 😬🤭
$AAPL $QQQ $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:31:08 </td>
   <td style="text-align:left;"> $QQQ $SPY $DOCU $ROKU $ZM Cathie be like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:31:06 </td>
   <td style="text-align:left;"> Live updates: UN: 1.9M people displaced inside Ukraine https://www.billionaireclubcollc.com/live-updates-un-1-9m-people-displaced-inside-ukraine/ $SPY $DJIA $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:29:48 </td>
   <td style="text-align:left;"> $QQQ the bounce failed to hit a major point today and looks like the downtrend is still intact. At this point I expect the Feds meeting next week to cause some turmoil and we will hit a new leg down in the next week or so. March inflation numbers will be more troubling.. will be looking at April for possible long positions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:28:59 </td>
   <td style="text-align:left;"> $DOCU As usual, Cathie bought really high and now $ARKK is suffering.   $ARKK will gap down tomorrow to reflect loss in $DOCU.   $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:26:47 </td>
   <td style="text-align:left;"> $SPY latexc03660987c74cc7b06781d2e8be220ffAGRI Ran 2.80s -4.50s+ 50%+ potential
$QQQ puts off VWAP reclaim ran 50% middle of day 

Hope folks traded well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:25:19 </td>
   <td style="text-align:left;"> $SPY $DIA $NASDAQ $QQQ Treasury plans new actions against North Korea after ballistic missile tests

https://www.marketwatch.com/story/treasury-plans-new-actions-against-north-korea-after-ballistic-missile-tests-2022-03-10?mod=bnbh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:24:41 </td>
   <td style="text-align:left;"> $SPY $QQQ A strong bounce into the close and the market finished well off the lows. I think many investors realized that we are getting extremely close to the bottom and they are using any pullback as a buying opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:23:53 </td>
   <td style="text-align:left;"> $QQQ $AAPL $KWEB $SPY kweb graph with Nasdaq.  Uhhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:20:57 </td>
   <td style="text-align:left;"> $SPY $QQQ hey guys we are using this thing correctly and I didn’t think we’d ever do that.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:20:49 </td>
   <td style="text-align:left;"> $QQQ 
Hopefully doesn’t need a government bailout….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:20:25 </td>
   <td style="text-align:left;"> $QQQ  VP is not confident on her work… sadly at this very difficult time of the nation. Biden should have learned from  this and make sure to appoint top cabinets /supreme court judged based on quality, nothing but the quality…. Please …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:20:07 </td>
   <td style="text-align:left;"> $PLTR GOTHAM $QQQ $AAPL $TSLA 

https://www.palantir.com/in-defense-of-europe/en/

🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:18:14 </td>
   <td style="text-align:left;"> Live updates: UN: Ukraine withdrawing peacekeeping personnel https://www.billionaireclubcollc.com/live-updates-un-ukraine-withdrawing-peacekeeping-personnel/ $SPY $QQQ $DJIA $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:18:11 </td>
   <td style="text-align:left;"> $QQQ multiple attempts to break out of the initial down trend line. Looks like we’re holding above and in for rebound. 

📈🖍🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:17:35 </td>
   <td style="text-align:left;"> $AAPL $QQQ $AMD $SPY People will be eating a lot of SPAM and the Price Of Spam will even increase noticeablyX  
Houston we have a serious problem##### in the U.S. Economy and The World. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:17:19 </td>
   <td style="text-align:left;"> $DOCU damn bulls...  Welcome to the gulag 
$qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:16:26 </td>
   <td style="text-align:left;"> Justice Dept. names prosecutor to go after pandemic fraud https://www.billionaireclubcollc.com/justice-dept-names-prosecutor-to-go-after-pandemic-fraud/ $DJIA $QQQ $SPY $PFE $MRNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:15:29 </td>
   <td style="text-align:left;"> $SPY $QQQ I don’t like for tomorrow. Is there a bull case? This is pure gut </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:13:49 </td>
   <td style="text-align:left;"> $SPY  $QQQ  From today&amp;#39;s Department of Defense newswire.  France is assembling a multination battle group in Romania.  $LMT and $RTX will provide the required weapons.  Time to herd up the ruskies and return them to St Petersburg.     
 
Secretary of Defense Lloyd J. Austin III called Romanian Minister of National Defence Vasile Dîncu to continue coordinating our Allied response to Russia’s unprovoked and premeditated invasion of Ukraine.  Both leaders deeply appreciated the bravery of the Ukrainian people, reflected on the unwavering unity among NATO Allies, and commended the broad commitment to provide humanitarian and security assistance to Ukraine.  Secretary Austin also commended Romania’s intent to host a humanitarian assistance logistics hub and discussed the planned French-led multinational battlegroup in Romania. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:13:45 </td>
   <td style="text-align:left;"> $SPY $QQQ Solid green tomorrow.. So abvious.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:12:42 </td>
   <td style="text-align:left;"> Our GREAT American companies are being hurt so badly by Sleepy and Phony. Gas prices totally out of control! Inflation all-time highs. Borders wide open. Far Left running the show. We will have to MAKE AMERICA GREAT AGAIN! $QQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:11:36 </td>
   <td style="text-align:left;"> $QQQ  ongoing bad news on top of bad news plus no more QE; lets gap down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:11:32 </td>
   <td style="text-align:left;"> Markets Have Mixed Day Of Trading As Russia-Ukraine Ceasefire Talks Go Nowhere  $QQQ $SPY $DIA $AMZN $BKR 

https://newsfilter.io/a/f2173f84073afc00a1f6766872da1b1c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:10:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$906M to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:10:53 </td>
   <td style="text-align:left;"> $SPY $QQQ real price comes out soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:10:42 </td>
   <td style="text-align:left;"> $QQQ this up or down tommorw ? Down ? People scared to hold over the weekend ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:10:32 </td>
   <td style="text-align:left;"> Putin totally taking advantage of very weak Biden. OPEC ignoring him. Phony Kamala stepping all over him. Incredible! This would have NEVER happened to your favorite prez ever (Me) SAD! $QQQ $SPY $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:09:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:09:09 </td>
   <td style="text-align:left;"> $QQQ $SPY real moves usually come overnight. Hedgies know the numbers are bad and they tried to fake people by holding up the price and adding shorts in the day. then they will gap it down big and create panic sell the next day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:09:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:08:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 3/11 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:08:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL We want to keep on seeing oil stabilizing and getting Into tighter trading ranges, and we’ll see all of those safety hedges and energy over allocation outflows come back into the riskiest assets of the market.

That’s the only thing that’s going to put volume back into things on a consistent basis, not many whales will buy risk on assets when oil is swinging $20, there’s too much overnight risk.  Calmer oil, calmer commodities, calmer waters to sail in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:07:40 </td>
   <td style="text-align:left;"> $DOCU $SPY $QQQ 

oof... 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:06:15 </td>
   <td style="text-align:left;"> $QQQ $SPY I’m sure the news is shit guys just ignore it. Unless it impacts you fuck it. We have money to stack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:05:23 </td>
   <td style="text-align:left;"> $SPY $QQQ Russia says US has biochem weapons labs in Ukraine. US says the claim is preposterous. But the US unofficial disclosure is that Department of Defense is funding the labs. Yes DoD. 
What to believe? Why is DoD funding and not UNICEF or W-H-O?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:05:21 </td>
   <td style="text-align:left;"> $QQQ first day in a while I didn’t flip to 1 minute after 2:50 CST lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:04:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AMD 

Wow that wasn’t obvious at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:04:44 </td>
   <td style="text-align:left;"> $SPY $QQQ They look so weak and it’s not even funny. The markets already have to price in aprils bad cpi data , so it’s going to get rough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:04:37 </td>
   <td style="text-align:left;"> $SPY and here comes North Korea. It never ends. $IWM $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:04:20 </td>
   <td style="text-align:left;"> Phony Kamala already running the show. Sleepy Joe being put out to pasture with glass of warm milk and blanket. Many people talking. SAD! $QQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:04:19 </td>
   <td style="text-align:left;"> $QQQ $SPY buyers market. 📈🖍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:04:05 </td>
   <td style="text-align:left;"> $SPY $QQQ i guess all bad news got canceled. Highest inflation rate in 40 years? Who cares! Putin bombing childrens hospitals? Doesn’t matter! Interest rates about to jump? It’s PRICED IN!! 

This market is a freaking joke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:03:50 </td>
   <td style="text-align:left;"> $QQQ if you followed that we did a live trend line trade which was super fucking cool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:03:50 </td>
   <td style="text-align:left;"> $AMC apes are good for two things... losing in the market and providing endless comic relief for all of Stocktwits $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:03:45 </td>
   <td style="text-align:left;"> $SPY $QQQ as crazy as it sounds weekly charts don’t lie. Dips are still being bought. $IWM weekly shows it well

Idk where this market is going in the future but it’s gonna make a big move soon. 444 or 400 imo. How long do bears need before they get 400? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:03:19 </td>
   <td style="text-align:left;"> Today&amp;#39;s close $SPY $QQQ $IWM: near the high of the day, still under yesterday&amp;#39;s close, and oh so close to hitting a big squeeze into the final minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:03:15 </td>
   <td style="text-align:left;"> $QQQ good day bulls 😃
We can handle less than 1% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:02:24 </td>
   <td style="text-align:left;"> $QQQ  54.560  tests, and a $1,090 in Net Profit. Automated Trading by UltraAlgo (Available in TradeStation and TradingView). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:02:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $HUSA $NVDA $AGRI what a great day for trading.  very hard to make this many trades and not have any losers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:01:56 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm $labu
Excellent day for the bulls.
We’re way off the lows and little down after a massive rise yesterday. $$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:01:34 </td>
   <td style="text-align:left;"> $QQQ deep red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:01:05 </td>
   <td style="text-align:left;"> $QQQ 600 us tech rejected several times. Pretty sure we will try again tomorrow 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:01:03 </td>
   <td style="text-align:left;"> $QQQ $SPY this tape continues to prove that you can get killed very fast. I cannot remember a time before 2020 that I saw this ever.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 05:01:00 </td>
   <td style="text-align:left;"> $QQQ fake ass pump confirmed. gap down tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:59:37 </td>
   <td style="text-align:left;"> $QQQ bears coming back in at the clock like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:59:31 </td>
   <td style="text-align:left;"> $QQQ This ain’t going no where </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:59:30 </td>
   <td style="text-align:left;"> $QQQ $SPY I would love to hold overnights but I am not comfortable with that right now. Just not doing it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:59:13 </td>
   <td style="text-align:left;"> $SPY $QQQ stonk up baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:58:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Anyone else feeling some victory with nasdaq &amp;quot;only&amp;quot; down 0.88%?  Lol... 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:58:31 </td>
   <td style="text-align:left;"> $QQQ 5 minute chart intraday is my favorite! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:58:22 </td>
   <td style="text-align:left;"> $QQQ about hod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:58:20 </td>
   <td style="text-align:left;"> $QQQ $SPY Amazon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:57:25 </td>
   <td style="text-align:left;"> $SPY $QQQ about to get very ugly. flash dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:56:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM Bit of a truth bomb when it comes to our current &amp;quot;energy crisis,&amp;quot; which was totally not manufactured, by the way. Wink, wink. nudge, nudge.  
 
https://www.youtube.com/watch?v=Qjf3-e1GyZw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:56:36 </td>
   <td style="text-align:left;"> $QQQ  $SPY  #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:56:26 </td>
   <td style="text-align:left;"> $SPY Shorts are screwed.....  
 
Let&amp;#39;s close GREEEN!!!! 
 
$IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:55:44 </td>
   <td style="text-align:left;"> $SPY look at all that oil our prior admin bought from Russia $IWM $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:55:22 </td>
   <td style="text-align:left;"> $QQQ ☕️ https://t.co/VcLiS8wcGR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:54:30 </td>
   <td style="text-align:left;"> $QQQ Tendies acquired have a nice day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:54:14 </td>
   <td style="text-align:left;"> $QQQ wow...the end day chart is literally one of the most suspect I&amp;#39;ve seen in a long time...algos propping up price while unloading as much as the market will bear... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:53:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOXL $UVXY LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:53:48 </td>
   <td style="text-align:left;"> $QQQ looking to be a great daily candle for a red day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:53:47 </td>
   <td style="text-align:left;"> $QQQ 100% cash +1.2% day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:53:29 </td>
   <td style="text-align:left;"> $QQQ that’s what I get for selling my hedge 🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:53:15 </td>
   <td style="text-align:left;"> $QQQ https://twitter.com/the_chartgoat/status/1502024585641869318?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:53:12 </td>
   <td style="text-align:left;"> $QQQ wait no get 332 go do it guys all right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:53:00 </td>
   <td style="text-align:left;"> $QQQ 6 bounces off the exact same point? Nothing to see here..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:52:48 </td>
   <td style="text-align:left;"> $QQQ bear trend potential magnet call scalp closed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:52:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM peace talks going good again?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:52:19 </td>
   <td style="text-align:left;"> $QQQ prediction for tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:52:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 81048000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:51:51 </td>
   <td style="text-align:left;"> $VALE $SBSW $SPY $QQQ $TSLA
WILL WE ROCK TOMORROW OR SLUMP #FREE-NICKEL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:51:11 </td>
   <td style="text-align:left;"> $QQQ just postponing $315 a day, setting up better defense for $319 or will need to double down if want to hit break $339 tomorrow..talking OT pump with promo or a lot more eow Ls unfortunately. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:51:05 </td>
   <td style="text-align:left;"> $QQQ correction 332 test next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:50:51 </td>
   <td style="text-align:left;"> $QQQ Go south </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:50:29 </td>
   <td style="text-align:left;"> $QQQ $SPY most boring power hour ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:50:19 </td>
   <td style="text-align:left;"> $QQQ gap above bear TL 331 test next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:49:13 </td>
   <td style="text-align:left;"> $QQQ Save for retirement only -2% daily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:48:47 </td>
   <td style="text-align:left;"> $MOS Russian fertilizer ban can push Mosaic to 120-150 handle like 2008. It can be better than $TSLA now. $SPY $QQQ might soon move upside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:48:07 </td>
   <td style="text-align:left;"> $QQQ - 2% eod? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:48:05 </td>
   <td style="text-align:left;"> $QQQ bullish TL stronger now test bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:47:43 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:47:14 </td>
   <td style="text-align:left;"> $QQQ bad close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:46:47 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA I guess we just chop around until the first rate hike next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:46:33 </td>
   <td style="text-align:left;"> $SPY $QQQ bear flag is set ready to drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:46:09 </td>
   <td style="text-align:left;"> $SPY $QQQ we should have gone green by lunch. 🤪 Anyway green finish mean what? For tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:46:07 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:45:27 </td>
   <td style="text-align:left;"> $NIO petition to DELIST this China scam. $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:45:26 </td>
   <td style="text-align:left;"> $MRK Extra! Extra! get your dividends! Only 2 trade days remaining for shareholder record! $SPY $QQQ $HOOD $PFE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:45:18 </td>
   <td style="text-align:left;"> $QQQ Print maintains TL with pin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:43:45 </td>
   <td style="text-align:left;"> $QQQ fuck, choose a direction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:43:41 </td>
   <td style="text-align:left;"> $QQQ 330 close, tmr we end the week 335-336 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:43:03 </td>
   <td style="text-align:left;"> $SPY $QQQ  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:42:54 </td>
   <td style="text-align:left;"> $QQQ $TQQQ LOTTO PUTS FOR TOMORROWWWWWWWWWWW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:42:25 </td>
   <td style="text-align:left;"> $QQQ 331.75 or higher close then green tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-03-11 04:41:47 </td>
   <td style="text-align:left;"> $SPY $QQQ  a range bound close.. did not see that one coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 09:12:20 </td>
   <td style="text-align:left;"> Apple $AAPL, Google $GOOGL, Ikea and Others Urge Texas to Drop Transgender Policy.#Ainvest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 09:11:11 </td>
   <td style="text-align:left;"> $SPY Bitcoin will go to 8k after that executive order $AAPL $AMZN $MSFT $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 09:09:52 </td>
   <td style="text-align:left;"> $AAPL that AAPL dark pool is serious!! $691M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 09:08:54 </td>
   <td style="text-align:left;"> $AAPL looking for a bull trap tomorrow morning (best case scenario) to enter the $155P 3/18 . Some put buyers from today will close first thing in the morning. Leg down if it breaks todays lod. pT $149 then final pt (long) $126 after hikes. Bounce up and down for sure but in downtrend.📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 09:08:38 </td>
   <td style="text-align:left;"> $AAPL zero innovation and heavily reliant on China for production. Not liking where this is going. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 09:08:00 </td>
   <td style="text-align:left;"> $AAPL&amp;#39;s ROE of 139.79% is amongst the best returns of the industry https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 09:06:20 </td>
   <td style="text-align:left;"> $BTC.X that executive order cutting the artery on this $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 09:04:23 </td>
   <td style="text-align:left;"> $SPY I wouldn&amp;#39;t be surprised to see this green tomorrow. CPI came in as expected that they were some prices in there that actually came down. So.. We&amp;#39;ll see 👀 $QQQ $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 09:04:01 </td>
   <td style="text-align:left;"> $SPY Sheesh tank it cramer $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:59:07 </td>
   <td style="text-align:left;"> $FSR I own some $rivn and $lcid and still like them long term ie 4-7 years for big gains. I love $fsr and have more in it because those big gains are 1-3 years away. All are good companies, but the asset light model makes Fisker unique like $aapl. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:58:33 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $BTC.X $AMZN Hillary insurance nobody want to be clintened.😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:58:08 </td>
   <td style="text-align:left;"> $AAPL well, it had a chance to close ah at its closing and dropped way back down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:53:06 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $MSFT 

RSI = RELATIVE STRENGTH INDEX

It is intended to chart the current and historical strength or weakness of a stock or market based on the closing prices of a recent trading period.

This is a fantastic tool when used correctly!Study up on this indicator and learn to trade with it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:48:32 </td>
   <td style="text-align:left;"> $SPY docusign and oracle diving $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:47:49 </td>
   <td style="text-align:left;"> $BTC.X if the digital dollar comes out, this will go to Zero so fast $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:43:21 </td>
   <td style="text-align:left;"> $AAPL Prolonged War In Ukraine Could Be Worse For Economy Than Pandemic, VW CEO Fears https://www.carscoops.com/2022/03/prolonged-war-in-ukraine-could-be-worse-for-economy-than-pandemic-vw-ceo-fears/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:41:50 </td>
   <td style="text-align:left;"> $AAPL I really love this stock... I believe it has reduced in price because of the current adverse economy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:40:26 </td>
   <td style="text-align:left;"> $AAPL I give up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:30:26 </td>
   <td style="text-align:left;"> $AAPL Market always red on Friday’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:29:16 </td>
   <td style="text-align:left;"> $AAPL still mid-term bearish, but the idea that you can just straight short this and make money is...foolish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:25:52 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $FB $DWCPF no news is good news these days . You see outside there is no cloud , no speculation go buy calls. If you see a jackrabbit throwing war tantrum. Go get puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:20:02 </td>
   <td style="text-align:left;"> $AAPL French president says conditions set by Russia’s Putin for ceasefire in Ukraine &amp;quot;not acceptable to anyone&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:18:15 </td>
   <td style="text-align:left;"> $AAPL had over $17.80M in Unusual Activity today with several large trades coming in, with a bullish sentiment. See more details on Sweepcast.com #Stockstowatch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:16:15 </td>
   <td style="text-align:left;"> $AAPL now green after hours 🤩🤩🤩🤩🤩🤩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:16:06 </td>
   <td style="text-align:left;"> $AAPL 163 tomorrow or higher! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:14:44 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. 👀 👀  $175 Call for Thursday, April 14. Roughly 440 Thousand dollars! 💰💰 Learn more on StockOrbit at https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:14:39 </td>
   <td style="text-align:left;"> $AAPL Here is the unusual activity on sweepcast.com/ as I mentioned in my previous post. #options #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:13:38 </td>
   <td style="text-align:left;"> latex65cea7a1ff8d3c1b4ecdb3a173ebf293AMD - 53% call flow 
$VIX - 51% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:10:35 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ 

We all know the next few months are gonna be a 🤡 show, but for tomorrow at least…face ripper 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:08:42 </td>
   <td style="text-align:left;"> $SPY $AAPL   extreme distance from cloud equilibirum..  take your Vitamin C for the ride </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:05:36 </td>
   <td style="text-align:left;"> $AAPL why do I feel so bullish for tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:02:51 </td>
   <td style="text-align:left;"> $AAPL With no cease fire and it being Friday tomorrow, we have a fake pop to the upside and a swift sell off into the weekend. Plan accordingly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:01:31 </td>
   <td style="text-align:left;"> $AAPL My friends and fellow long stock holders, Apple 🍎 may go up $20.00. - $40.00 this year and that’s good but, Carnival Cruise lines will at least double x2  before the end of summer.   
     $TSLA  $MSFT  $AMZN  $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:01:05 </td>
   <td style="text-align:left;"> $AAPL Bought 1 more share at 157 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 08:00:08 </td>
   <td style="text-align:left;"> $MSFT $AAPL $SPY $FB  so almost 1600% gain today . Any question ? 😊😊😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:57:54 </td>
   <td style="text-align:left;"> $AAPL Shall we put it? Still on thee stone fence </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:56:42 </td>
   <td style="text-align:left;"> $AAPL $SPY  next week  fed and hike rate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:56:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL This is a very angry boomer 👉@Partridge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:54:49 </td>
   <td style="text-align:left;"> $AAPL new SE looks pretty decent for the price point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:51:36 </td>
   <td style="text-align:left;"> $AAPL WILL SOON HIT $4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:50:44 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 79.5K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:48:42 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $AAPL my favorite FAANGs and in that order. Just heard an interesting point about how the upcoming splits for GOOGL and AMZN will allow more retail investors to own them (obviously), but it will put pressure on their respective legislators to not crack down as hard on their monopolies. The argument is that AAPL/MSFT have avoided some of that legislative regulation due to being widely owned by retail investors 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:37:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Pooots got me iced out ❄️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:33:11 </td>
   <td style="text-align:left;"> Daily Market Recap for Thursday 3/10/2022 for trending #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/cQjb0xG8GT0

$AMD $AAPL $TSLA $RIVN $RBLX

Laggards keep
Lagging </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:30:44 </td>
   <td style="text-align:left;"> $AAPL this really got clobbered but was able to build a pretty good position at a good price. Fingers crossed we pop tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:30:19 </td>
   <td style="text-align:left;"> $AAPL $SPY

https://au.finance.yahoo.com/news/pimco-stands-lose-billions-russia-083233451.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:26:25 </td>
   <td style="text-align:left;"> $SPY Index barely down even though market took a blood bath today.  When these seven stocks tank, we&amp;#39;ll have the crash of our lifetime.  $AMZN $AAPL $GOOG $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:22:00 </td>
   <td style="text-align:left;"> Boo
$SPY $SPX $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:21:45 </td>
   <td style="text-align:left;"> $SPY Load stocks ahead of the recession!! $AAPL lmao meme millenials $IWM $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:20:17 </td>
   <td style="text-align:left;"> $AAPL horrendous performance on the daily today and even ah is red while the indexes are green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:17:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : 7 Web 3.0 Stocks to Buy for Their First-Mover Advantage https://www.stck.pro/news/AAPL/24190219 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:13:06 </td>
   <td style="text-align:left;"> $AAPL so Russia said they are gonna nationalize business’s assets they have in their country if the switch isn’t turned back on in five days. Apple doesn’t have any stores in Russia. They have no real assets there. What a joke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:07:12 </td>
   <td style="text-align:left;"> $AAPL going to $162 tomorrow $165 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:07:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:06:53 </td>
   <td style="text-align:left;"> $AAPL Russia wants to “Nationalize Apple” 😃
This just proves the point that there is no point to do business with dictatorship countries 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:06:22 </td>
   <td style="text-align:left;"> $SPY funny that numbers came in right at expectation. It all comes down to politics. Every administration has done but now is getting a little ridiculous. Like I said earlier, The Fed can only keep doing this BS for so long. Once the floor gives and they can&amp;#39;t prop the markets the drop will be epic. For now... Take advantage 💵😎
$AAPL $QQQ $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:05:36 </td>
   <td style="text-align:left;"> $AAPL what kind of idiots are shorting this 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:03:45 </td>
   <td style="text-align:left;"> $AAPL When APPLE and GOOGL correct, it&amp;#39;s time to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:02:47 </td>
   <td style="text-align:left;"> $AAPL What a joke! How much stock Apple has in Russia?? All revenues in Russia were lower than 1% of total Apple revenues. 😂😂😂
 Russia considering &amp;#39;nationalizing&amp;#39; Apple &amp;amp; others that left the country
https://appleinsider.com/articles/22/03/10/russia-considering-nationalizing-apple-others-that-left-the-country </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:01:14 </td>
   <td style="text-align:left;"> $AAPL big companies go last in a bear Market. Looking at apple very important levels here at $157 it broke below. A significant move downward expected here. Next levels to watch $149 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 07:00:10 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:59:25 </td>
   <td style="text-align:left;"> $AAPL https://stocktwits.com/ElliottwaveForecast/message/443102757 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:58:49 </td>
   <td style="text-align:left;"> $RIVN $AAPL should buy Rivian now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:57:23 </td>
   <td style="text-align:left;"> $PTON Good Job Your putting on great show to get bought out by $AAPL Apple. 
Example like $ATVI Activision Blizzard did for $MSFT Microsoft. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:57:14 </td>
   <td style="text-align:left;"> $aapl led the mkt down today. Turn the page https://youtu.be/1DfrbYHd5g0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:55:57 </td>
   <td style="text-align:left;"> $AAPL I’m long in the $130’s .. (fair value) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:52:58 </td>
   <td style="text-align:left;"> $aapl those covid names are really getting MASSACRED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:51:15 </td>
   <td style="text-align:left;"> $AAPL $155 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:49:03 </td>
   <td style="text-align:left;"> Apple already working on more powerful M2 Ultra chip with 24-core CPU

$AAPL https://appletrack.com/apple-already-working-on-more-powerful-m2-ultra-chip-with-24-core-cpu/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:44:23 </td>
   <td style="text-align:left;"> $AAPL  30% up from last year, do your own math, of course we can’t be at 200 not but wait till eoy. 180 plus 30% we will be around 230 eoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:44:14 </td>
   <td style="text-align:left;"> $SPY Fed eyeing a 1% raise in its next meeting, prob only gonna get a .75% tho $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:43:47 </td>
   <td style="text-align:left;"> $AAPL don’t let the bears win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:41:57 </td>
   <td style="text-align:left;"> $AAPL Any thoughts on tomorrow? It came back to $159 and then dropped back down. Looks like no retailers shopping here. I missed the $155 drop this morning.  I’m at even right at $158.25. Holding for the ride up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:39:29 </td>
   <td style="text-align:left;"> $AAPL $MSFT 

Both about to crash much lower …. Prices about to crash as the fed raises rates and tightens liquidity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:39:17 </td>
   <td style="text-align:left;"> $AAPL I am not a scammer, I am not a pumper, but I strongly recommend buying ASO Academy Sports and Outdoors, as their pre ER run is beginning. 7.50 TTM EPS, 4.9 pe. $WMT $ASO $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:35:41 </td>
   <td style="text-align:left;"> $FSR Fisker light assest strategy is really starting to prove itself. $AAPL will do the same or just take a stake in Fisker. Look at the disaster $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:35:26 </td>
   <td style="text-align:left;"> $AAPL headlines when aapl reaches the outer point of the falling wedge, gains and the whole market follows: 

“Well nothing is as bad as we thought it’d be.”

“We’ve run out of excuses. “

“Ukraine and Russia been fighting for 8 years, not a big deal.”

“Blah, blah, puke, diarrhea.” $DIS $ASO $WMT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:33:11 </td>
   <td style="text-align:left;"> $aapl note to self: follow your own trade ideas 

I ll admit, i think the market maker got me this week smh. Lets see how it closes tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:32:35 </td>
   <td style="text-align:left;"> $SPY Bulls leveraged at historic levels $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:32:09 </td>
   <td style="text-align:left;"> $AAPL thoughts on April 14 long Calls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:31:34 </td>
   <td style="text-align:left;"> Volkswagen CEO says the Russia Ukraine War will be more devastating than COVID Pandemic 
61% of U.S. S&amp;amp;P500 Companies Revenues are Domestic 
 39% of U.S. S&amp;amp;P500 Companies Revenues are Internatiobal 
The Market will suffer and go lower 

$QQQ $SPY $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:30:27 </td>
   <td style="text-align:left;"> $AAPL I haven’t looked but those of you that did the AAPL intraday move and if you closed at the right time or whatever worked for you, personally that would probably be one of the cleanest intraday trades. Maybe you did it both ways? lol wow we killed this shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:29:59 </td>
   <td style="text-align:left;"> $AAPL tempted to pick up more in low 150&amp;#39;s if it gets there for my kids </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:28:12 </td>
   <td style="text-align:left;"> $AMZN $AAPL $TSLA $XOM $MFST

https://news.alertsandnews.com/apple-inc-nasdaqaapl-amazon-com-inc-nasdaqamzn-how-stock-splits-affected-performance-in-apple-tesla-and-more/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:27:35 </td>
   <td style="text-align:left;"> $SPY Valuations at Utopian levels $AAPL $NVDA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:26:55 </td>
   <td style="text-align:left;"> $AAPL $420.69 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:21:03 </td>
   <td style="text-align:left;"> $SPY Negative GDP + Rate Hikes + Fed Selling + Inflation at 40yr high = Bullish right lmao $AAPL $AMZN $IWM $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:21:00 </td>
   <td style="text-align:left;"> $AAPL $SPY $FB $GOOG What metrics are people using to buy stocks, When some  companies have substantial YoY growth and record breaking earnings and they are tanking..BUYING freaking PUTS.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:20:25 </td>
   <td style="text-align:left;"> $RIVN we are basically selling at cash value.  Would be a good fit for $AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:19:19 </td>
   <td style="text-align:left;"> $AAPL possible it goes to $120 over the next year? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:18:52 </td>
   <td style="text-align:left;"> $AAPL did u guy see Kamala in Poland conference ?
What a F joke 
Research her comments </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:16:51 </td>
   <td style="text-align:left;"> $AAPL who let me hold degen calls overnight ??????? This will all be your fault unless I get paid in which case it was my idea </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:15:04 </td>
   <td style="text-align:left;"> $AAPL APPL?

More like this thing handed me an L </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:14:54 </td>
   <td style="text-align:left;"> $AAPL 180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:03:21 </td>
   <td style="text-align:left;"> $AAPL 157.5 seems to be true max pain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:00:40 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-10 Options Analysis Video: 
https://www.youtube.com/watch?v=yA_LaKsIXzY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 06:00:31 </td>
   <td style="text-align:left;"> $AAPL when can we back to $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:55:43 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL In a new fad that is sweeping the nation, millions of couples are having &amp;quot;market sentiment&amp;quot; reveal parties to find out if their child will be bullish or bearish.   
 
This couple found out their child would be Bullish!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:54:15 </td>
   <td style="text-align:left;"> $PLTR even $AAPL drop 2.7% today.  All China stocks waterfall including top tickers $baba $pdd $jd. $Pltr is very bullish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:50:22 </td>
   <td style="text-align:left;"> $AAPL $AMZN $SPY $TSLA $MSFT

Keep compounding, keep investing!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:50:03 </td>
   <td style="text-align:left;"> $TSLA $AAPL $F elections and now biolabs 😔😔🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:45:07 </td>
   <td style="text-align:left;"> $GOOG $NVDA $MSFT $AMZN $AAPL  
Bailouts coming? Are you holding Russian debt?  
 
$1.5T spending package coming to advent a government shutdown?  
 
8% US inflation, a 40 year high  
 
Oil above $100 &amp;amp; likely staying there (recession follows) 
 
Fed&amp;#39;s balance sheet more than doubled since March 2020 (from $4.3T to $9T) QE ended a few days ago 
 
June 2009 end of last recession, 13 yr BULL MARKET RUN (longest in history) Fed&amp;#39;s Balance Sheet was only $2T @ the time 
 
Current federal funds rate as of March 08, 2022 is 0.08%. 
Last time CPI was here @ 8%, the Fed Funds rate was 13% 
 
Yield curve inversion for 90 days or more , recession? 
 
Rate hike into a slowing economy &amp;amp; another Cold War in the background, very likely a fed induced recession  
 
Gold @ ATH &amp;amp; mortgage rates knocking @ 4%  
 
Global debt is out of control @ $300,000,000,000, 000 w/US rates right above 0%. When money becomes &amp;quot;free&amp;quot; the road back might be impossible without breaking parts of the economic system.  
https://youtu.be/ja3CK3XDV5I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:44:57 </td>
   <td style="text-align:left;"> $QQQ $AAPL  $MSFT $GOOG  still need to pullback for that bottom to be in , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:41:59 </td>
   <td style="text-align:left;"> $AAPL $ROKU $PTLO $PF the best advice I ever received about buying stocks was this. Buy into companies you use, trust and believe in. Apple (1000 shares in 2012 is now 28,000 shares), Roku - bought at $45, sold at $410, PF 20,000 shares at $42 and (holding) and PTLO - 30,000 shares at $14 and holding. Use your common sense, don’t listen to non-professionals, and trust your instincts and judgment. You’re smarter than you think. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:39:55 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ wht kind of BS is this let’s go ATHs+ already wtf these clowns losing back the best companies in the world they don’t give a crap about a war or anything!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:39:27 </td>
   <td style="text-align:left;"> $AAPL weekend view @ www.elliottwave-forecast.com. We like looking for a decline further down, where buyers can enter at the blue box for a bounce.  We don’t like to sell it short this close to the blue box though, but we do like to buy it lower at the extreme area where buyers are waiting for a bounce.  Here’s how we saw it this weekend looking for lower.  #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:38:38 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY $AMD 
Check out this this $CPI Breakout 
Next Month’s Report will be even worse!
Bad for Stonks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:38:23 </td>
   <td style="text-align:left;"> $AAPL next stop $200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:37:58 </td>
   <td style="text-align:left;"> To answer the questions of fellows, yes I&amp;#39;d buy or at least hold, things will return to normal soon, and will sky rocket, some folks are just afraid of their own shadow :) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:36:48 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 319.0K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:31:09 </td>
   <td style="text-align:left;"> $SPY They didn&amp;#39;t wanted to be too obvious. Is the only reason it didn&amp;#39;t close green 😬🤭
$AAPL $QQQ $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:29:39 </td>
   <td style="text-align:left;"> $AAPL https://appleinsider.com/articles/22/03/10/russia-considering-nationalizing-apple-others-that-left-the-country </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:29:16 </td>
   <td style="text-align:left;"> $AAPL $SPY everything to the moon tomorrow to trash puts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:28:50 </td>
   <td style="text-align:left;"> ( $RBLX), Apple Inc. (NASDAQ: $AAPL) – Could Roblox Be Coming To PlayStation 5? New Job Posting Suggests ‘Yes’ https://www.billionaireclubcollc.com/rblx-apple-inc-nasdaqaapl-could-roblox-be-coming-to-playstation-5-new-job-posting-suggests-yes/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:23:53 </td>
   <td style="text-align:left;"> $QQQ $AAPL $KWEB $SPY kweb graph with Nasdaq.  Uhhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:21:32 </td>
   <td style="text-align:left;"> $AAPL why is this down so much today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:20:26 </td>
   <td style="text-align:left;"> “*CHINESE STOCKS LISTED IN THE U.S. FALL BY MOST SINCE OCT. 2008”

$AAPL $AMD ↗️ $AMZN $BTC.X $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:20:07 </td>
   <td style="text-align:left;"> $PLTR GOTHAM $QQQ $AAPL $TSLA 

https://www.palantir.com/in-defense-of-europe/en/

🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:19:54 </td>
   <td style="text-align:left;"> $DOCU There&amp;#39;s a HUGE difference between profitable companies like $AAPL doing buybacks and and UNPROFITABLE companies doing buybacks.   One is undervalued, the other is borrowing money to buyback shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:19:04 </td>
   <td style="text-align:left;"> $AAPL idk. I just can’t see them letting all these puts print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:17:35 </td>
   <td style="text-align:left;"> $AAPL $QQQ $AMD $SPY People will be eating a lot of SPAM and the Price Of Spam will even increase noticeablyX  
Houston we have a serious problem##### in the U.S. Economy and The World. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:16:38 </td>
   <td style="text-align:left;"> Our tech companies getting slammed badly by bad policies from WH. China (and others) taking advantage of Sleepy Joe big league. Many people are talking. Not good! $AAPL $TSLA $AMZN $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:16:34 </td>
   <td style="text-align:left;"> $SPY Oracle RIP, yet another &amp;quot;tech&amp;quot; company that shows a contraction in future revenue $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:13:11 </td>
   <td style="text-align:left;"> $AAPL $SPY  Apple had a great press day yesterday!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:11:32 </td>
   <td style="text-align:left;"> How Stock Splits Affected Performance In Apple, Tesla And More  $AMZN $TSLA $AAPL $XOM $MSFT 

https://newsfilter.io/a/e08833fbff3472271641458f2df5257b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:09:20 </td>
   <td style="text-align:left;"> $AAPL I believe some bulls must have gotten trapped before market close if you were hoping to swing a call from now till tomorrow. I feel like this is a repeat from yesterday. I’m gonna wait till tomorrow to go long but for now I believe this is… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:08:41 </td>
   <td style="text-align:left;"> Not terribly active today with  
 
-2 $TQQQ long scalps,  
-1 long $AMZN scalp around core holding 
 -added back some $AAPL and locked in some $WMT profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:08:12 </td>
   <td style="text-align:left;"> $SPY $AAPL Some wild wild order blocks coming in on apples tape AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:08:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL We want to keep on seeing oil stabilizing and getting Into tighter trading ranges, and we’ll see all of those safety hedges and energy over allocation outflows come back into the riskiest assets of the market.

That’s the only thing that’s going to put volume back into things on a consistent basis, not many whales will buy risk on assets when oil is swinging $20, there’s too much overnight risk.  Calmer oil, calmer commodities, calmer waters to sail in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:06:08 </td>
   <td style="text-align:left;"> $AAPL When it get manipulated like $AMZN. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:05:38 </td>
   <td style="text-align:left;"> $AAPL 108 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:05:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:04:34 </td>
   <td style="text-align:left;"> $AAPL 154 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:04:23 </td>
   <td style="text-align:left;"> $AAPL sold some, then added to the April put position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:03:48 </td>
   <td style="text-align:left;"> $AAPL why was this down so much today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:03:18 </td>
   <td style="text-align:left;"> $SOFI dumbass CLOWNS on here trying to blame the market on Sofi demise lol

Sofi is down 45% in 3 months.  

Let’s take a basic “market” darling stock like $AAPL.  It’s down 9%. 

Anyone who thinks 9% and 45% are the same should STOP INVESTING RIGHT NOW 

SOFI IS TRASH.  DONT LISTEN TO THE PUMPER CLOWNS ON THIS BOARD ALL THEY DO IS WANT U TO LOSE MONEY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:03:01 </td>
   <td style="text-align:left;"> $AAPL fully expecting petrified dump tomorrow.  With war getting worse, Fridays are dumpy.  Think APPL can hold its own though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:02:51 </td>
   <td style="text-align:left;"> $AAPL Under $160 is always an easy choice. Any week you hold will be over by the next day or sometime the next week. $160C tomorrow, and next week, and the week after. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:02:35 </td>
   <td style="text-align:left;"> $AAPL yesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:01:56 </td>
   <td style="text-align:left;"> $AAPL $SPY

Gap up tomorrow 🤫😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:01:55 </td>
   <td style="text-align:left;"> $AAPL 1hr view from weekend update presented to members at elliottwave-forecast.com/ #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:01:04 </td>
   <td style="text-align:left;"> $aapl som1 dumped 2.8 M in last 2 mins.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:00:47 </td>
   <td style="text-align:left;"> $AAPL not the best close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 05:00:37 </td>
   <td style="text-align:left;"> There are very few companies that are as singularly focused as $AAPL. They are almost immune to the world around them and are really only affected by their own product cycles. Their “moat” is the whole Apple ecosystem. Companies like this are always the ones you want to own. You just want to own them at a reasonable cost basis. Today the shares are once again below $160. That’s a price that’s very appealing to me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:59:32 </td>
   <td style="text-align:left;"> $AAPL run run run.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:58:50 </td>
   <td style="text-align:left;"> $AAPL degen calls overnight it is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:58:47 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT Please save this royalty free meme I made to use when tagging @ST_Squad_Car  #KansasCashGivesBack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:58:27 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 3/06 weekend update presented to members at elliottwave-forecast.com/ #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:55:31 </td>
   <td style="text-align:left;"> Could Roblox Be Coming To PlayStation 5? New Job Posting Suggests &amp;#39;Yes&amp;#39;  $RBLX $SONY $AAPL $GOOG $GOOGL 

https://newsfilter.io/a/adbc5ad258986d3ea7cae2468364d520 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:54:08 </td>
   <td style="text-align:left;"> $AAPL that was easy $$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:52:24 </td>
   <td style="text-align:left;"> $AAPL calls in for swing... next week 160c.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:51:57 </td>
   <td style="text-align:left;"> $AAPL 4hr view from the 2/27 weekend update. Calling for a move lower towards blue box area where buyers are expected to appear #elliottwave #trading #apple #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:51:52 </td>
   <td style="text-align:left;"> $CCL  
Not Kidding ….. 
 
When a cease fire is declared,  
 
And with the end of the War declaration made. 
 
 watch the cruise lines move up 25% or more in one day! 
 
$AAPL  $TSLA $AMZN $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:50:29 </td>
   <td style="text-align:left;"> $AAPL - Russia considering nationalizing; Apple others that left the country - Apple Insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:48:21 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 2/20 weekend update presented to members at elliottwave-forecast.com/ called for a double correction lower to take place #elliottwave #trading #apple #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:46:17 </td>
   <td style="text-align:left;"> $AAPL hold over night? Thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:45:58 </td>
   <td style="text-align:left;"> Now that baseball is back I can get drunk at Yankee stadium I need some drink partners $amzn $spx $tsla $aapl $msft .. ladies don’t be afraid 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:45:53 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $AAPL guys we are completely foooooked!! 🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:45:28 </td>
   <td style="text-align:left;"> $AAPL Apple kind of lead on this  https://www.channelchek.com/news-channel/ESG_Policies_and_Corporate_Departures_from_Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:43:03 </td>
   <td style="text-align:left;"> $SPY $QQQ  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:42:18 </td>
   <td style="text-align:left;"> $AAPL $160 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:41:44 </td>
   <td style="text-align:left;"> $SPY $ARKK $AAPL tomorrow get ready for margin call hit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:41:43 </td>
   <td style="text-align:left;"> $LCID I thought $AAPL is suppose to have a car by 2025? How? With what infrastructure? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:41:21 </td>
   <td style="text-align:left;"> $AAPL The smart dumped the other day...the greedy ones are still hoping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:41:13 </td>
   <td style="text-align:left;"> $AAPL got fooked oh well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:40:53 </td>
   <td style="text-align:left;"> $AAPL use dips as an opportunity to buy. There is a lot of noise out there but this will rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:40:35 </td>
   <td style="text-align:left;"> $AAPL $160 before close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:40:31 </td>
   <td style="text-align:left;"> $AAPL big move will happen overnight whether thats up or down we’ll see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:40:31 </td>
   <td style="text-align:left;"> $DKNG $PENN $SRAD $AAPL BASEBALL IS BACK. These stocks to the 🌙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:39:54 </td>
   <td style="text-align:left;"> MLB Owners and Players Agree to New Contract, Saving 2022 Season - The Wall Street Journal

$AAPL $AMD ↗️ $AMZN $GOOGL $NFLX  https://apple.news/AKwaYYwc6SUyg7_DLgytNyA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:39:13 </td>
   <td style="text-align:left;"> $AAPL Look out belooooow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:38:09 </td>
   <td style="text-align:left;"> $AAPL GO UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:38:01 </td>
   <td style="text-align:left;"> $AAPL FUCK! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:37:40 </td>
   <td style="text-align:left;"> $AAPL degen call hold overnight or </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:36:31 </td>
   <td style="text-align:left;"> $QQQ hmm $AMZN pumping again but $AAPL looks like it gave up and maybe $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:35:14 </td>
   <td style="text-align:left;"> $AAPL It will be interesting to see how it closes.  So far not looking good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:35:00 </td>
   <td style="text-align:left;"> $XLK  4 Hour chart from 3/09 update to member&amp;#39;s at elliottwave-forecast.com/, showing the idea. #elliottwave #trading $AAPL $AMZN $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:34:40 </td>
   <td style="text-align:left;"> $AAPL massive sell off into close is very possible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:31:22 </td>
   <td style="text-align:left;"> $AAPL no one has money to buy aapl products. Need to save money to buy canned food if they can even find it. Tank city coming for entire market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:30:59 </td>
   <td style="text-align:left;"> $AAPL has made millionaires. Like myself.  Wanna know how?  It’s all in the chart below.  I know what Apple does first hand and so does my Portfolio. Don’t need broke boys on Stock Twits to tell me. 😂😂😂🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:30:42 </td>
   <td style="text-align:left;"> $SPY Lot of Low IQ conditioned bulls on here. Fed has created a dangerous presumption for new investors with constant printing. Not saying we will drop straight to 350 but it is coming $AAPL $NVDA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:29:28 </td>
   <td style="text-align:left;"> $DIS $AAPL  
 
Major League Baseball and the MLB Players Association have reached a tentative agreement on a new labor deal per ESPN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:28:22 </td>
   <td style="text-align:left;"> $AAPL baseball is back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:27:34 </td>
   <td style="text-align:left;"> $AAPL can we get a $155 in the house please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:26:17 </td>
   <td style="text-align:left;"> $AAPL spending most of my paycheck in the App Store to boost sales numbers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:26:06 </td>
   <td style="text-align:left;"> $AAPL 160 please I need ONE OPTION TO WORK OUT FOR ME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:25:41 </td>
   <td style="text-align:left;"> $AAPL WHY YHIS BIHHHH CRASHING BRUH GO TF UP TO 160 FOR PAPA 👴 👴🏾👴🏾👴🏾👴🏾👴🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:25:32 </td>
   <td style="text-align:left;"> $AAPL Russia nationalizing companies that left Russia. Still US stock is holding. If there is war with Taiwan and China, imagine!!  Tech will go to dust!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:25:12 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:25:00 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:21:03 </td>
   <td style="text-align:left;"> $AAPL market is about to crash bank saving rates stink the end is near </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:21:00 </td>
   <td style="text-align:left;"> $AAPL head and shoulders? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:20:49 </td>
   <td style="text-align:left;"> 3000 $AAPL APR2022 $160 Cs trade 5.8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:20:06 </td>
   <td style="text-align:left;"> $AAPL dunno why people bother watching during the day, all the stock movement happens when the market is closed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:19:34 </td>
   <td style="text-align:left;"> $AAPL just have a feeling this surges into close and opens above 160 tomorrow. not a call on next week&amp;#39;s price action but just feels like the way this works. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:19:26 </td>
   <td style="text-align:left;"> $AAPL this company at least 3 to 4 years behind the cell phone market. it lacks in so many areas when it comes to cell phone features. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:18:54 </td>
   <td style="text-align:left;"> $AAPL We are not  at WAR. this political corrupt climate is really drumming up some serious BEARISH SENTIMENT..$SPY $QQQ ,tell the 🤡King in U*kraine to stay PUT.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:17:24 </td>
   <td style="text-align:left;"> $AAPL 1.7 million 4/14 came in ..interesting ,im still getting apple puts for next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:17:00 </td>
   <td style="text-align:left;"> Some top tech sector flow coming in above ask 
 
$AAPL - $692K put sweep 
$SQ - $582K put sweep 
$NVDA - $517K put sweep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:16:38 </td>
   <td style="text-align:left;"> $AAPL you might get your $160. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:15:28 </td>
   <td style="text-align:left;"> $AAPL  iPhone needs more cameras to justify a move up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:15:19 </td>
   <td style="text-align:left;"> $AAPL $160 EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:14:04 </td>
   <td style="text-align:left;"> $AAPL might dip my toes in once it finishes bleeding off down to about.... 35 bucks a share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:11:53 </td>
   <td style="text-align:left;"> $AAPL trying to get all the bulls in before they tank it. This support here is NOT real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:10:51 </td>
   <td style="text-align:left;"> $AAPL the 200 month MA is $42 on this one.  😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:10:07 </td>
   <td style="text-align:left;"> $AAPL Think about the Monthly Market Trend if you are considering buying Stonks 
$AMD $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:09:26 </td>
   <td style="text-align:left;"> $AAPL thank you apple . You bought me a range Rover and vacation to Cuomo Italy. Today was amazing . Sorry to those who lost , market give opportunity every second. Grab it. Flexibility and timing is everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:09:15 </td>
   <td style="text-align:left;"> $AAPL I’m happy selling calls on rips, using the capital to accumulate more shares on dips, and getting dividends from the company with the best cash flow in the world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:08:30 </td>
   <td style="text-align:left;"> The FAANG Stocks: Values or Traps? $AAPL $GOOGL $AMZN $NFLX $FB https://www.zacks.com/stock/news/1880458/the-faang-stocks-values-or-traps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:07:41 </td>
   <td style="text-align:left;"> $AAPL well, that was a call trap and calls get pummeled even further. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:07:18 </td>
   <td style="text-align:left;"> $LCID Breaking Partnership with $AAPL 
Not confirmed yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:07:09 </td>
   <td style="text-align:left;"> $AAPL $QQQ $NDX - Maybe? Haven&amp;#39;t jumped back into the market long yet (besides Nat Gas, oil &amp;amp; energy)  https://twitter.com/BeeeRadstwr/status/1502012685994635272?s=20&amp;amp;t=npIfZL-br4GMrSc-H1byLg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:06:55 </td>
   <td style="text-align:left;"> $AAPL sell the top, sell the top. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:05:13 </td>
   <td style="text-align:left;"> $AAPL that’s quite the dump in less than 5 min </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:03:34 </td>
   <td style="text-align:left;"> $AAPL get to 160 for a nice lil swing today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:02:43 </td>
   <td style="text-align:left;"> $AAPL Who&amp;#39;s ready for the power hour DUMP FESTIVAL..$SPY $QQQ FREE HAIRCUTS $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:02:08 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:02:06 </td>
   <td style="text-align:left;"> $AAPL why it dumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:01:58 </td>
   <td style="text-align:left;"> $AAPL BDCODNBDCNJDKSJSNSNXXNDN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:01:10 </td>
   <td style="text-align:left;"> $TSLA $NVDA $MSFT $FB $AAPL power hour dump it time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:00:47 </td>
   <td style="text-align:left;"> $AMZN $MSFT $AAPL Pandemic pumped bags </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 04:00:13 </td>
   <td style="text-align:left;"> $AAPL 153 or 150 tomorrow which one is it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:59:31 </td>
   <td style="text-align:left;"> $AAPL doing everything it can to hold the market together 🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:58:30 </td>
   <td style="text-align:left;"> $AAPL getting ready to lock profit on the March 11th ones 😬😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:58:09 </td>
   <td style="text-align:left;"> $AAPL geezzzz what a add intra day 👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:57:25 </td>
   <td style="text-align:left;"> $AAPL WOWOWOOWOWOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:55:24 </td>
   <td style="text-align:left;"> $AMZN $SPY $AAPL $MSFT u crazy son of a bitch, u did it, even with WW3 on our doorsteps, horrendous CPI data, supply chain issues you still manage to pump lmaoooooooooooooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:54:06 </td>
   <td style="text-align:left;"> $AAPL Added </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:52:57 </td>
   <td style="text-align:left;"> $SPY   **will post ichimoku charts later.. 
 **caution  bearish wave riders for strong market bounce over resistance as oil dummped and  
$500K on Lockheed Martin PUTS (war stuff) and  
massive $TSLA CALLs into #RIVN earnings 
big SPY  and $AAPL CALLS showing up. the real time $500 Million in SPY and QQQ orders..  (normally they show up in Late darkpool prints from delayed   reporting. i expec huge Darkpool buys  Darkpool prints show up tomorrow ( Darkpool can delay trade reporting a day) 
 
VIX about to break under $30.. market likely surges then..   
&amp;#39;knock knock&amp;#39;   Vix reaper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:52:53 </td>
   <td style="text-align:left;"> $SPY 
$NVDA continuing to carry $AAPL into 160 target </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:52:21 </td>
   <td style="text-align:left;"> $AAPL good timing 🤯🤯🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:51:53 </td>
   <td style="text-align:left;"> Charting class tomorrow at 4 PM EST ALL free no bs algo no bs premium a month just traders helping each other every day. Tired of all these scammers I have a platform to help y’all and we will. $TSLA $SPY $NVDA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:51:49 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:51:16 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Everything Apple Announced This Week: Mac Studio, iPhone SE 3, iPad Air and Studio Display https://www.stck.pro/news/AAPL/24180222 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:50:48 </td>
   <td style="text-align:left;"> $AAPL LOAD EVERYTHING YOU GOT $$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:49:59 </td>
   <td style="text-align:left;"> $AAPL There are over 144K volume for 160$ calls expiring tomorrow. This will be above 160$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:48:32 </td>
   <td style="text-align:left;"> $AAPL Above 160 tomorrow. I stand by this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:47:52 </td>
   <td style="text-align:left;"> $AAPL close above 160 ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:47:26 </td>
   <td style="text-align:left;"> $AAPL $120 is support se ya there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:44:49 </td>
   <td style="text-align:left;"> $AAPL will they cut guidance? Losing russia sales and high inflation hurting domestic purchasing power? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:44:32 </td>
   <td style="text-align:left;"> $AAPL TONR stock will rise power hour. Momentum stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:44:23 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY  PEOPLE…look at where they’ve got apple parked right now going into power hour. How could you not be bullish into tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:42:46 </td>
   <td style="text-align:left;"> $XLK The sector showing a bearish sequences since the peak at 12.28.2021, more downside should be happening  to reach the extreme buying area. Here is the latest 4 Hour chart to member&amp;#39;s at https://elliottwave-forecast.com/, showing the idea. #elliottwave #trading $AAPL $AMZN $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:42:24 </td>
   <td style="text-align:left;"> $AAPL trending along with spy 5min chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:39:53 </td>
   <td style="text-align:left;"> $AAPL told you so, this will move between latexe27b5ee40daa33f46739c26ab0c44a4aX taking profits off into strength 
$CLF taking profits off I to strength 
Really nice day .. again 
Don&amp;#39;t have to trade 50 different stocks with 50 different indicators.. just 500!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:38:41 </td>
   <td style="text-align:left;"> $TSLA $MSFT  $AAPL $BTC.X these market days….It’s like inserting just the tip…………. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:38:38 </td>
   <td style="text-align:left;"> $AAPL wen divi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:38:08 </td>
   <td style="text-align:left;"> $QQQ $AAPL $AMZN $SPY 

POWER HOUR IS SOON TO BE BEAR HOUR, GUARANTEED!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:37:18 </td>
   <td style="text-align:left;"> $AAPL 

Nasdaq futures trying to reclaim 13600... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:35:51 </td>
   <td style="text-align:left;"> $AAPL it’s okay, take your time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:35:28 </td>
   <td style="text-align:left;"> $aapl lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:34:01 </td>
   <td style="text-align:left;"> $AAPL Yolo march 11 160$ calls 😂😂 so far so good hopefully </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:32:55 </td>
   <td style="text-align:left;"> $AAPL ☺️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:32:13 </td>
   <td style="text-align:left;"> $AAPL PUSH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:31:44 </td>
   <td style="text-align:left;"> $AAPL trust the process </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:31:40 </td>
   <td style="text-align:left;"> $SPY taking profits off on $X and $CLF 
Into the end of day right here 
$NVDA $AAPL all working 
Go go green algos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:31:13 </td>
   <td style="text-align:left;"> $AAPL 160 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:30:55 </td>
   <td style="text-align:left;"> $AAPL food or an apple phone I will go with food. Over priced junk apple. Better cheap phones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:30:37 </td>
   <td style="text-align:left;"> $AAPL Red to Green???! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:30:21 </td>
   <td style="text-align:left;"> $AAPL it’s tempting sometimes but you have to stick to the game plan, especially in these times! Timed option plays 20%-30% at a time is all you need..🤤🤤🤤🤑👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:29:41 </td>
   <td style="text-align:left;"> $AAPL is there sale number coming out tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:29:14 </td>
   <td style="text-align:left;"> $SPY $NVDA $AAPL 
Look identical right now
Taking more profits off into end of day here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:28:48 </td>
   <td style="text-align:left;"> $AAPL needs to break 159 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:28:29 </td>
   <td style="text-align:left;"> $AAPL BTFD! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:27:12 </td>
   <td style="text-align:left;"> $ZM good tuck in for $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:24:48 </td>
   <td style="text-align:left;"> It&amp;#39;s #IBD biggest event of the year! Get winning stocks and full trading plans for FREE when you sign up for #LeaderboardFreeAccess. No strings attached and no credit card required. Your portfolio will thank you. Click here --&amp;gt;https://bit.ly/3pVJW5g $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:23:12 </td>
   <td style="text-align:left;"> $AAPL looks like inverted head and shoulder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:22:57 </td>
   <td style="text-align:left;"> $AAPL this will drop like a dead fly pre-market tomorrow, then new lows next week. IMHO.  Any thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:22:55 </td>
   <td style="text-align:left;"> $SPY my only question is: 
 
hold $AAPL and $GOOGL  
 
or $SPY  
 
&amp;quot;invest in the two smartest kids in class? or the whole class overall&amp;quot;? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:22:48 </td>
   <td style="text-align:left;"> Russia considering &amp;#39;nationalizing&amp;#39; Apple &amp;amp; others that left the country 
 
Senator Manchin Pushes Defense Production Act For Natural Gas Pipeline 
 
$SPY $USO $NGS $AAPL 
 
https://appleinsider.com/articles/22/03/10/russia-considering-nationalizing-apple-others-that-left-the-country </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:21:39 </td>
   <td style="text-align:left;"> $AAPL Russia considering &amp;#39;nationalizing&amp;#39; Apple &amp;amp; others that left the country. That&amp;#39;s not really news. These fake pumps are hilarious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:19:54 </td>
   <td style="text-align:left;"> $AAPL breakout 💥💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:19:08 </td>
   <td style="text-align:left;"> $SPY dont trade this garbage .. trade the heavily weighted stocks . Like $NVDA and $AAPL
taking MAR18 160 calls off for 25% profit here
Target 160 .. halfway there!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:18:41 </td>
   <td style="text-align:left;"> $AAPL $160 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:18:35 </td>
   <td style="text-align:left;"> $AAPL heading to 150, increased puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:17:16 </td>
   <td style="text-align:left;"> $AAPL $AMD $F $CCL $NVDA ----All that you need to know. Shorts haven&amp;#39;t covered a single share; Check it out below,  
 
highly recommend everyone to follow them 🚀discord.web1337.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:17:10 </td>
   <td style="text-align:left;"> $AAPL 10 yr yield crawling up slowly. This directly impacts tech sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:16:11 </td>
   <td style="text-align:left;"> $AAPL $155 maybe? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:15:07 </td>
   <td style="text-align:left;"> $NVDA added a bit here and $AAPL here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:15:02 </td>
   <td style="text-align:left;"> $AAPL it’s really not going to 160 today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:14:17 </td>
   <td style="text-align:left;"> $AAPL Market makers in control to try and cruise it into that $157.50 closing range for options. Still can’t believe the market is this strong given 6.9% CPI print. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:13:26 </td>
   <td style="text-align:left;"> $AAPL I think I might have called the bottom for the day.👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:13:05 </td>
   <td style="text-align:left;"> $AMD $SPY $TSLA $AAPL  Tom Clancy Red Storm Rising book predicted this war. &amp;quot;Like, obviously, technology is 40 years more advanced and it isn&amp;#39;t the Soviets anymore, and it&amp;#39;s a limited engagement in Ukraine instead of worldwide total conventional war.  
BUT. 
In Red Storm Rising, the Soviets try to break up NATO by claiming that West Germany carried out terrorist attacks against Soviet citizens, but was found out by US intel. 
 
In real life, Russia tried to limit European and NATO support by claiming Ukraine was harming people in Donbass, and also that Ukraine attacked first. This was also thwarted by US intel. 
 
In Red Storm Rising, the Soviet leaders didn&amp;#39;t tell anyone what they were planning and asked for a bunch of different feasability assessments of different things, and the KGB was surprised when a war actually broke out and Soviet leadership was surprised when their ad hoc plan didn&amp;#39;t work. 
 
Click link to read more... 
 
https://www.reddit.com/r/books/comments/tazjey/im_absolutely_blown_away_by_how_much_tom_clancy/?ref=share&amp;amp;ref_source=link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:12:58 </td>
   <td style="text-align:left;"> $AAPL any news or just everything going on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:11:14 </td>
   <td style="text-align:left;"> $AAPL 💵💵💵💵💵💵💵💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:11:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Expect Renewed Strength In AAPL Stock After the Year’s First Apple Event https://www.stck.pro/news/AAPL/24180006 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:11:02 </td>
   <td style="text-align:left;"> $AAPL  Did anyone think Russia was about to come to an agreement? So...WTF? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:10:50 </td>
   <td style="text-align:left;"> $AAPL lunch hour lull is over. Continue the party down. Most likely we close around 157ish today, but we’re seeing the weekly 50 day ma. Whether you like it or not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:10:25 </td>
   <td style="text-align:left;"> $AAPL up cumulative 40% on calls from that dip 😬😎🙏🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:09:43 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m long apple.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:08:33 </td>
   <td style="text-align:left;"> $AAPL 160-163 you can do this 😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:08:29 </td>
   <td style="text-align:left;"> $AAPL sold thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:08:03 </td>
   <td style="text-align:left;"> $ASTS $TSLA $GSAT $AAPL  https://seekingalpha.com/article/4494178-why-the-ast-space </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:07:42 </td>
   <td style="text-align:left;"> $AAPL pump it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:07:37 </td>
   <td style="text-align:left;"> $AAPL right back down again we print 150 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:06:56 </td>
   <td style="text-align:left;"> $AAPL love me a nice intraday reversal play. Let’s print!!!! $SPY looking solid currently, if this can go green you can see some pretty substantial upside. Taking some off here and holding some for more upside. Never trust the market moves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-03-11 03:06:34 </td>
   <td style="text-align:left;"> $AAPL holding strong 🚀🚀🚀🤩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 09:14:02 </td>
   <td style="text-align:left;"> $TSLA bullish tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 09:12:24 </td>
   <td style="text-align:left;"> $TSLA wtf.......retailers got fked again.....oh no.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 09:10:15 </td>
   <td style="text-align:left;"> $TSLA this is going to hell tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 09:04:19 </td>
   <td style="text-align:left;"> $TSLA 

Futures just died ⚡🔴⚡🔴⚡🔴⚡ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 09:04:06 </td>
   <td style="text-align:left;"> $SQ  $tsla $nvda $shop  some of these are getting so cheap I dont give a fuck ill go down with the ship companies dont change like that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 09:03:14 </td>
   <td style="text-align:left;"> $TSLA zuckerburg and musk are being investigated for election bribery in Wisconsin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 09:02:23 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-10 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=eMp3aKUbf4c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 09:02:06 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla: ICE Vehicles Will Trump EVs in the Near-Term, Says Morgan Stanley https://www.stck.pro/news/TSLA/24193808 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 09:01:34 </td>
   <td style="text-align:left;"> $DWAC $SPY $TSLA futures tanking, did Kamala Harris say something stupid again? IMPEACH AND REMOVE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:58:33 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $BTC.X $AMZN Hillary insurance nobody want to be clintened.😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:58:07 </td>
   <td style="text-align:left;"> $TSLA higher lows on the 4h </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:55:00 </td>
   <td style="text-align:left;"> $TSLA has an Altman-Z score of 17.64, meaning it is financially healthy with little risk of bankruptcy. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:54:58 </td>
   <td style="text-align:left;"> $TSLA go down to 750 and then bounce back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:53:42 </td>
   <td style="text-align:left;"> $TSLA EVs gonna be hit hard tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:53:06 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $MSFT 

RSI = RELATIVE STRENGTH INDEX

It is intended to chart the current and historical strength or weakness of a stock or market based on the closing prices of a recent trading period.

This is a fantastic tool when used correctly!Study up on this indicator and learn to trade with it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:51:47 </td>
   <td style="text-align:left;"> $TSLA 

Filled !! 

🙏🏻🐉🦅😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:51:03 </td>
   <td style="text-align:left;"> $NIO $TSLA $LCID $RIVN $MULN  
 
Breaking News!!! March 10th, 2022. It appears NIO is in discussion with BYD to use their blade batteries! Game Over!! 
 
https://cnevpost.com/2022/03/10/byd-chairman-wang-chuanfu-spotted-visiting-nio-house-meeting-with-william-li/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:50:48 </td>
   <td style="text-align:left;"> $TSLA Thursday’s are now red every day because everyone knows Friday’s are gonna be red too 🤣🤣🤣 what a vicious shit show the bulls have created for themselves 🤣🤣 meanwhile I’m just buying puts and sucking in their money 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:50:09 </td>
   <td style="text-align:left;"> $TSLA that ain&amp;#39;t no retail selling ah that&amp;#39;s fs... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:49:48 </td>
   <td style="text-align:left;"> $TMC Running AH!🚀🚀
EV Metal Industry, particularly NICKEL mining is the hottest sector right now. TMC has the worlds largest known resources worth $1.12 trillion or $5k per TMC share. Trading around $2 per share, TMC is definitely a long term moonshot play. DD video below.
$RIVN $TSLA $NIO $LCID 
https://youtu.be/6AMuA66p7EA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:49:16 </td>
   <td style="text-align:left;"> $TSLA Without government subsidies, there would be no solar or wind. Both are only 20% as efficient max as fossil fuels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:48:42 </td>
   <td style="text-align:left;"> $TSLA this lead will go up as wannabe Tesla’s such $RIVN $NIO and some others going south. I see TR soon, 1200 here I come! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:47:53 </td>
   <td style="text-align:left;"> $TSLA Some of you guys on here petty as hell! In the end, shorts either realize they&amp;#39;re on the wrong side of money or they don&amp;#39;t.  No need in arguing with people that can&amp;#39;t seem to do their own DD and not understand the limited up side vs. UNLIMITED RISKS. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:47:07 </td>
   <td style="text-align:left;"> $TSLA Sen. Bill Hagerty (R-TN) warned the United States’ push toward electric vehicles is not possible without two of its key adversaries, Russia and China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:44:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA

Go back to the bull side Crammer, we don’t want you with us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:42:54 </td>
   <td style="text-align:left;"> $TSLA did putin get bad advice from his generals? He is fucked bases on the evidences </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:41:33 </td>
   <td style="text-align:left;"> $TSLA I see 750 this month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:40:34 </td>
   <td style="text-align:left;"> $TSLA $HYMC 👀⬅️⬅️🚀🚀🚀🌕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:36:16 </td>
   <td style="text-align:left;"> $TSLA other meme stocks have already ranked … the grand daddy of meme stonks is ready to be popped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:36:05 </td>
   <td style="text-align:left;"> $TSLA Tesla: ICE Vehicles Will Trump EVs in the Near-Term, Says Morgan Stanley https://www.tipranks.com/news/article/tesla-ice-vehicles-will-trump-evs-in-the-near-term-says-morgan-stanley/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:35:35 </td>
   <td style="text-align:left;"> $RIVN I’ve seen this movie before with $TSLA.  be patient.  It’s all about production.  Now is when you build a position folks.  Nothing to be bearish about.  Great earnings call. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:35:02 </td>
   <td style="text-align:left;"> $TSLA 800 tmr? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:32:56 </td>
   <td style="text-align:left;"> $TSLA Crude is lower, as is the VIX. Both good signs - hopefully these trends continue. I pulled this together for those that may find it useful: https://youtu.be/OHKIsdTgVHQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:30:27 </td>
   <td style="text-align:left;"> $TSLA 

What if ..that’s if ! @elonmusk Tesla split the stock at this level for another 5:1 ahead of all these catalysts as code of confidence to investors and pan sear these shorts HFs the way I do my filet👇 ! 

Wouldn’t be amazing 🤩 ?!! 

“Just saying - Extraordinary times demand extraordinary measures!!”

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:28:28 </td>
   <td style="text-align:left;"> $TSLA  Tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:28:26 </td>
   <td style="text-align:left;"> Elon Musk from $TSLA is on the side of $TMC.  Just see this: https://electrek.co/2022/03/08/elon-musk-says-drill-for-oil-but-nickel-prices-skyrocketing/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:22:57 </td>
   <td style="text-align:left;"> $TSLA when Tesla Semi? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:21:46 </td>
   <td style="text-align:left;"> $TSLA $HYMC 😱😱😱🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:18:49 </td>
   <td style="text-align:left;"> $TSLA Well, at some point, dr evil needs to stop raising the prices on Twitter With aunt Cathie screaming the same shit! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:16:21 </td>
   <td style="text-align:left;"> $NIO another brilliant call @Figgy1million those idiot $TSLA buyers huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:16:17 </td>
   <td style="text-align:left;"> $TSLA https://www.zerohedge.com/commodities/tesla-increases-vehicle-prices-nickel-squeeze-creates-chaos. ELON MUSK IS EVIL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:15:54 </td>
   <td style="text-align:left;"> $TSLA 

Realistic price targets when this $QQQ bubble actually pops...

(Fair Value)
Share Price: $65
Market Cap: $65.25 Billion
P/E: 12x
P/S: 1.2x

(Justifiable Premium)
Share Price: $75
Market Cap: $77.80 Billion
P/E: 14.5x
P/S: 1.45x

(Bubble)
Share Price: $100
Market Cap: latex64ac648c2a68c7c497c1b9c7d4cb1a52F: 9.15x, 0.48x, 1.39x
$TM: 8.13x, 1.35x, 1.0x
Tesla: 175x, 18.0x, 28.0x

(Margins -- Gross, Operating, Net)
Ford: 15.9%, 3.3%, 13.2%
Toyota: 19.7%, 10.4%, 9.9%
Tesla: 25.3%, 12.1%, 10.2%

(Growth --1 Year Trailing Results)
Ford: 5.0%
Toyota: 12.5%
Tesla: 65.0%

(Growth -- 5Y Forward CAGR Estimates)
Tesla: 21.70%
Toyota: 23.00%
Ford: 74.15% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:13:28 </td>
   <td style="text-align:left;"> $AAPL $TSLA latexe81e23ceaf68b3795dbbef9030444aa1AMD - 53% call flow 
$VIX - 51% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:10:35 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ 

We all know the next few months are gonna be a 🤡 show, but for tomorrow at least…face ripper 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:10:03 </td>
   <td style="text-align:left;"> $TSLA Gonna shave the ballsss again.
https://youtube.com/shorts/qTmnjCiF1wU?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:09:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : As Gas Prices Soar, Consumers Flocking to Electric Vehicles https://www.stck.pro/news/TSLA/24192010 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:08:23 </td>
   <td style="text-align:left;"> $IPOF hey these guys said they want to fight your CEO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:02:21 </td>
   <td style="text-align:left;"> $RIVN they said this and $nio the next $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:01:55 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #4 ticker with sweep activity where institutions are trading options urgently with 21.3K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:01:31 </td>
   <td style="text-align:left;"> $AAPL My friends and fellow long stock holders, Apple 🍎 may go up $20.00. - $40.00 this year and that’s good but, Carnival Cruise lines will at least double x2  before the end of summer.   
     $TSLA  $MSFT  $AMZN  $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 08:00:35 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/rv5579MR_9g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:58:19 </td>
   <td style="text-align:left;"> $TSLA would love a brief visit to 875 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:57:26 </td>
   <td style="text-align:left;"> $TSLA yall ready for 790 tmw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:57:20 </td>
   <td style="text-align:left;"> $TSLA  🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:57:04 </td>
   <td style="text-align:left;"> $TSLA prices on cars raised by 1k. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:57:02 </td>
   <td style="text-align:left;"> $TSLA 905 🤲🏽 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:56:16 </td>
   <td style="text-align:left;"> $TSLA Only big cap with pricing power n no real competition ... just noise from other ev makers. .. should be back above 1k soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:56:12 </td>
   <td style="text-align:left;"> $TSLA Simple bull case for 50% growth this year https://www.msn.com/en-us/money/topstocks/the-simple-bull-case-for-tesla-stock/ar-AAUPpjm?ocid=winp1taskbar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:54:32 </td>
   <td style="text-align:left;"> $TSLA anyone short at the bottom today and get trapped in that forty ripper? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:50:25 </td>
   <td style="text-align:left;"> $TSLA The tea leaves tell me $798 tomorrow at some point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:49:15 </td>
   <td style="text-align:left;"> $RIVN fisker $FSR  is wise as they adapted $MGA as their contract manufacturer. Everyone cannot be Elon Musk $TSLA. If I really wanna put 5k in ev stock, that would be $FSR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:49:00 </td>
   <td style="text-align:left;"> $TSLA bulls got killed today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:48:19 </td>
   <td style="text-align:left;"> $TSLA bears welcome to the future 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:46:54 </td>
   <td style="text-align:left;"> $TSLA 👀🤔🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:46:12 </td>
   <td style="text-align:left;"> $TSLA 13-15% gap up with split rumors coming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:45:19 </td>
   <td style="text-align:left;"> $TSLA Be a bear or bull one thing we need to understand  other than tesla none of the other car makers has a secure supply of rare earth metals (cobalt,nickel,lithium) the prices of them has more than doubled in last few days so any new player will struggle finding capital ... Tesla also will be affected after a certain time but they have secured supply for next 4 years . electric car prices is gonna cost more and more in coming days ..  again gas is also not cheap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:45:19 </td>
   <td style="text-align:left;"> $TSLA Rivian is is following in the footsteps of Tesla. LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:42:09 </td>
   <td style="text-align:left;"> $TSLA I think we see a strong close tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:41:39 </td>
   <td style="text-align:left;"> $MULN Cars looks better than $TSLA $LCID and other EVs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:37:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Pooots got me iced out ❄️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:37:32 </td>
   <td style="text-align:left;"> $TSLA play the down trend till meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:35:23 </td>
   <td style="text-align:left;"> $TSLA Barrons saying this may split again soon. What do you guys think?

Amazon’s Stock Split Follows Alphabet’s. Here’s Who’s Next. https://www.barrons.com/articles/amazon-stock-split-who-next-51646944161?st=xl1n0rpnukojg1y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:34:19 </td>
   <td style="text-align:left;"> $GGPI (Polestar) is the clear winner for an EV stock pick. The only Global EV player in the world besides $TSLA. $RIVN and $LCID still have big promise in the long run but what both RIVN and LCID want to achieve is what Polestar has ALREADY achieved and Polestar has passed all the major hurdles that new companies have to go through. Well done Polestar! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:33:32 </td>
   <td style="text-align:left;"> $TSLA https://www.change.org/p/a-u-s-stamp-to-aid-ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:33:11 </td>
   <td style="text-align:left;"> Daily Market Recap for Thursday 3/10/2022 for trending #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/cQjb0xG8GT0

$AMD $AAPL $TSLA $RIVN $RBLX

Laggards keep
Lagging </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:29:51 </td>
   <td style="text-align:left;"> $SPY $TSLA FUTURES RIPPIN!! Bears gonna eat some dust tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:29:26 </td>
   <td style="text-align:left;"> $TSLA $NIO $RIVN $SOLO  all of you about go get Epic hammered down ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:27:26 </td>
   <td style="text-align:left;"> $TSLA 

FYI:

Nasdaq Fallen Heroes 🦸‍♀️ 
66% ————Fell 35% 
43%————-Fell 50% 

Have we bottomed out ?! Are inflation and interest rate hike fears baked in ?! 

I think so - higher risk to short the market than going long at this point imo 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:25:47 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK

Puts lookin like Arnold Schwarzenger💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:23:56 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:23:21 </td>
   <td style="text-align:left;"> $TSLA there’s levels to this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:23:01 </td>
   <td style="text-align:left;"> U $RIVN $LCID $MULN etc 🤡🤡🤡’s stop putting $TSLA in ur EV “sector”. Anyone who bought Tesla pre split like I did…

SHITS MONEY. I WIPE MY ASS WITH THE BILLS THAT STOCK HAS MADE ME AND 

NO OTHER STOCK WILL EVER DO WHAT IT DID: 

Went to 3500 ish then split and went back to 1200 ATH. Has only dropped to 850 ish in this market. 

The biggest Fukn beast that ever hit Wall Street. And that’s not arguable. 

✌🏼✌🏼✌🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:22:10 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Wen green day bulls?!.....🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:21:51 </td>
   <td style="text-align:left;"> $TSLA looking good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:19:07 </td>
   <td style="text-align:left;"> $TSLA gotta go or shes done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:17:22 </td>
   <td style="text-align:left;"> $TSLA  small pump at opening, then goes sub 800 eod. low 700 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:17:18 </td>
   <td style="text-align:left;"> $TSLA $HYMC ⬅️⬅️😱💥🚀🚀🌕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:16:28 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

You bulls think I fear a little pump, 

ah-ha-ha-ha🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:14:30 </td>
   <td style="text-align:left;"> $TSLA 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:14:14 </td>
   <td style="text-align:left;"> $TSLA not worth the risk of buying any other ev stock other than tesla   $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:13:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Oil and Nickel Crunches Highlight Tesla&amp;#39;s Strength https://www.stck.pro/news/TSLA/24190055 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:11:47 </td>
   <td style="text-align:left;"> $TSLA https://insideevs.com/news/572681/tesla-massive-order-increase-gas-prices/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:10:22 </td>
   <td style="text-align:left;"> $TSLA We are the beast of EV 
All wannabes will fall one by one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:09:30 </td>
   <td style="text-align:left;"> $tsla $49,000 a day keeps the 9 to 5 away; Stay patient and the let the trade play out.  best.livetradechat.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:09:09 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-10 Daily Forecast Video: 
https://www.youtube.com/watch?v=n1KpLMRZUP0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:07:00 </td>
   <td style="text-align:left;"> $SPY so basically Mr Pu yolo&amp;#39;d a weekly military option, literally went all in.
But Ukrainians pinned his army for two weeks and theta burn is killing it. 
At the same time the whole Russian economy got a  margin call... $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:06:22 </td>
   <td style="text-align:left;"> $SPY funny that numbers came in right at expectation. It all comes down to politics. Every administration has done but now is getting a little ridiculous. Like I said earlier, The Fed can only keep doing this BS for so long. Once the floor gives and they can&amp;#39;t prop the markets the drop will be epic. For now... Take advantage 💵😎
$AAPL $QQQ $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:05:54 </td>
   <td style="text-align:left;"> $TSLA Baby girl Y born in December via surrogate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:05:12 </td>
   <td style="text-align:left;"> $F Whole lot of people going to be unemployed at the dealers when Ford starts selling direct to consumers online.  $gm $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:04:58 </td>
   <td style="text-align:left;"> $TSLA or 846 end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:04:31 </td>
   <td style="text-align:left;"> $TSLA late day tomorrow potential 850 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:03:08 </td>
   <td style="text-align:left;"> $SPY  
a last minut $RIVN Call exchange sweep.  
many Unusual $TSLA CAlls, a few puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:02:45 </td>
   <td style="text-align:left;"> $TSLA $FB Zucker Bucks money helped put Biden Harris in power. 
Ukrainians lives lost due to old Biden&amp;#39;s and Obama&amp;#39;s policies. 
https://www.youtube.com/watch?v=rGO7hZwiBwY&amp;amp;t=1047s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:02:22 </td>
   <td style="text-align:left;"> $HYMC there she blows!!!! $TSLA $GOLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:02:12 </td>
   <td style="text-align:left;"> $SPY Biden talks a big game on electric vehicles. Did he even say Tesla or Musks name yet? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:01:56 </td>
   <td style="text-align:left;"> $RIVN Do you really think Rivian should have market cap half of $GM or $F when they can barely produce 5000 cars in a YEAR?   $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 07:01:42 </td>
   <td style="text-align:left;"> $TSLA we need a 1000 point gap down on NQ futs.... all at once. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:59:36 </td>
   <td style="text-align:left;"> $TSLA WOW WTF 😱😱😱😱👀👀👀💥💥💥💥🚀🚀🚀🚀🚀🚀🚀🌕🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨 $HYMC ⬅️⬅️⬅️⬅️⬅️⬅️⬅️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:58:41 </td>
   <td style="text-align:left;"> $TSLA I think Docusign dropping after hours is probably dragging this down as much as $RIVN due to the Ark connection </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:58:08 </td>
   <td style="text-align:left;"> $TMC this looks juicy! Buy low sell high….100%er on deck! $DOGE.X $SHIB.X $TSLA metals soooo hotttt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:58:05 </td>
   <td style="text-align:left;"> $TSLA When does Tesla report? Anybody know? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:57:37 </td>
   <td style="text-align:left;"> $TSLA Ark stocks can’t catch a break, today it was $TSLA and $TDOC, tomorrow looking like $DOCU, they are going to have to shut that fund down, valuation matters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:57:23 </td>
   <td style="text-align:left;"> $TSLA Maybe a small recovery tomorrow? Doubt it though. Once J.Powell sets the rates on Tuesday it will drop but rally back very fast! Have you’re dry powder on hand😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:56:40 </td>
   <td style="text-align:left;"> $MULN waiting she will fly same as $HYMC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:56:10 </td>
   <td style="text-align:left;"> $TSLA 75% premium shred again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:55:53 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMZN $AMC Government really shows their priorities when they want to spend billions on the IRS while our market regulators at the SEC can’t even afford coffee for their employees. And that’s per Gary Gensler on his Jon Stewart interview lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:55:24 </td>
   <td style="text-align:left;"> $TSLA let 880 be the HoD tomorrow, in Jesus name 🙏🙏🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:54:00 </td>
   <td style="text-align:left;"> $TSLA has an Altman-Z score of 17.64, meaning it is financially healthy with little risk of bankruptcy. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:53:46 </td>
   <td style="text-align:left;"> RT @CblastBT: Lotto Friday Triggers 🎯

🇺🇸 $SPY 430c &amp;amp;gt; 427 | 415p &amp;amp;lt; 423
💾 $INTC 47c &amp;amp;gt; 46.78 | 46p &amp;amp;lt; 46.48
🚗 $TSLA 860c &amp;amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:53:41 </td>
   <td style="text-align:left;"> $CRTD  $TSLA  $PHUN $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:53:19 </td>
   <td style="text-align:left;"> $RIVN scaringe is a fraud, scamster, complete cheat .. his reservation numbers are complete lie. Their supply chain problems is just excuse to runaway.. $TSLA was able to absorb all those and could beat estimates always. This is not even worth $10 a share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:52:34 </td>
   <td style="text-align:left;"> $TSLA $HYMC 😱😱😱😱👀👀👀👀💥💥💥💥🚀🚀🚀🚀🚀🚀🚀🌕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:52:28 </td>
   <td style="text-align:left;"> $TSLA  you can’t tell me this car doesn’t look cool! Those doors man!!! Keep almost hitting my head on em lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:51:02 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:49:45 </td>
   <td style="text-align:left;"> $TSLA 

🙏🏻🐉🦅😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:49:16 </td>
   <td style="text-align:left;"> $TSLA why is this down today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:48:56 </td>
   <td style="text-align:left;"> $AABB $BTC.X $ETH.X $TSLA https://www.cnbctv18.com/cryptocurrency/global-gold-backed-crypto-mcap-surpasses-1-billion-nears-all-time-high-12789362.htm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:48:54 </td>
   <td style="text-align:left;"> $TSLA why isn&amp;#39;t Elon pro-free speech in China? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:47:32 </td>
   <td style="text-align:left;"> EV Maker Rivian Came Up Short Everywhere  $RIVN $TSLA $NIO 

https://newsfilter.io/a/d7f15c9c9211c60f73e9acbdf18ee3ca </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:46:49 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Wen moon fanboys?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:45:19 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboy being summoned to scratch Elon&amp;#39;s scrotum.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:44:26 </td>
   <td style="text-align:left;"> $SPY my price target on $tsla is 40 dollars a share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:43:44 </td>
   <td style="text-align:left;"> $TSLA there is nothing bullish 

Technicals bearish
Fundamentals bearish
Economy bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:43:40 </td>
   <td style="text-align:left;"> $TSLA when gasoline party, Tesla Fanboys? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:43:37 </td>
   <td style="text-align:left;"> $TSLA $SPY $ETH.X BILLY DONT CARE ABOUT WW3.BILLY BUILDING THE LONG TERM RIGHT NOW. BILLY UNDERSTANDS YOU GOTTA BUY THE DIP TO ENJOY THR RIP...billy also on adderall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:42:41 </td>
   <td style="text-align:left;"> $SPY Europeans already stopped buying fancy goods and services. Items like iPhones $appl, Tesla&amp;#39;s $tsla, GPU&amp;#39;s/CPU&amp;#39;s $Amd/$nvda. Just to list some examples. The next earnings report will be nothing the market expects, with inflation, the end of QE, higher rates, the Russian war escalating, a barrel of oil over $150, inflation out of control, Two-year Treasury inverting, and so on... This market has no business being this high. You will be lucky if $330 holds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:41:43 </td>
   <td style="text-align:left;"> $TSLA it’s consolidating are these levels, once it breaks that 200EMA on the daily chart, you won’t see these prices for long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:39:46 </td>
   <td style="text-align:left;"> $TSLA likely to perpetuate below the 200 dma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:38:32 </td>
   <td style="text-align:left;"> $TSLA LOOK AT $HYMC AFTER HOURS STOCKWITS NOT EVEN UPDATING 😱👀👀🏃🏃🏃💨💨💨💨💨💨💨💥💥💥💥🚀🚀🚀🚀🚀🚀🌕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:38:00 </td>
   <td style="text-align:left;"> $TSLA No one else see the obvious Head and shoulders followed by another failure at the 200sma. Nothing bullish about it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:37:52 </td>
   <td style="text-align:left;"> $SPY  going to be up $10, because of $TSLA going to $900 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:37:38 </td>
   <td style="text-align:left;"> $RIVN should be $1B company so still needs 90% haircut. 

$TSLA 2021 Deliveries: 935k 
Tesla Market Cap: $866.4B
Per Vehicle Market Cap: $927k

Rivian 2021 Deliveries: 920

920 x 927k = $852 Million Proj Market Cap

Still overvalued by $31.2 BILLION </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:36:40 </td>
   <td style="text-align:left;"> $TSLA when Giga North Korea? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:36:39 </td>
   <td style="text-align:left;"> $TSLA 😂 My puts printing again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:36:26 </td>
   <td style="text-align:left;"> $TSLA how many bears here got scorched on the reversal from 810? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:36:16 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/rweyu3fl6bg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:35:17 </td>
   <td style="text-align:left;"> $TSLA $900 tomm 🚨🚀 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:35:14 </td>
   <td style="text-align:left;"> $TSLA we going to the moooooooooon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:35:13 </td>
   <td style="text-align:left;"> $TSLA who buys a $RIVN seriously this is a pimp,e on Tesla’s ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:34:39 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:34:30 </td>
   <td style="text-align:left;"> $TSLA  $SPY 

 bubble pop near. -40% still due. 

Housing bubble pop due. 

Global economic stress from War following a pandemic.

Inflation like no other . Loans will begin to default since people have to scrape pennies for Little Caesars $5 pizza and a gallon of gas. People will chose to keep their cell phone bill vs paying rent on time . Welcome to the next recession. 

Might as well wait till you lose everything before filing for a divorce that way you have nothing to give her 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:32:14 </td>
   <td style="text-align:left;"> $TSLA 🤓🤤🤤🤤🤑

https://electrek.co/2022/03/10/tesla-tsla-order-rate-surging-us-gas-prices-turning-people-to-electric-cars/?fbclid=IwAR1aU-R5sHsXavGUSI8T7iUhVLZAlU_IvibitODuMfws8DQD_kmCMit1mDM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:30:32 </td>
   <td style="text-align:left;"> $XELA 

Please do your own DD : 
1) 
Jan 26, 2022
Par Chadha, Exela’s Executive Chairman, noted, 
“After deploying more than $400 million of capital in 2021 to substantially reduce debt and extend maturities, we are now deploying capital to unlock shareholder value for our large and growing shareholder base.”

2) 
PAR might obtain his bonuses (see 8k exela 9/16/21) this year. 

https://investors.exelatech.com/static-files/9c592c47-58e9-46c3-a27a-0e445c401637

! PAR is 66 years old

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
   <td style="text-align:left;"> 2022-03-11 06:29:24 </td>
   <td style="text-align:left;"> $TSLA https://people.com/parents/grimes-welcomes-second-baby-a-daughter-with-elon-musk/?amp=true </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:29:09 </td>
   <td style="text-align:left;"> $MULN $TSLA Tesla needs to branch out and make a better quality car...  Now, don&amp;#39;t get me wrong I love Tesla and Elon Musk... amazing company and amazing person.  They are crushing the EV market... nobody comes even close.    
 
However, I do own 2 Tesla vehicles and yes, they run great and are really cool.  But they are not the highest quality like a Lucid.  
 
I think it would be a perfect opportunity for Tesla to buy Mullen... and offer a high end vehicle.   
 
Tesla cars are great but they are way overpriced for what you get. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:28:43 </td>
   <td style="text-align:left;"> $SPY $TSLA 
Hey bulls. This will go lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:28:12 </td>
   <td style="text-align:left;"> $AMZN $AAPL $TSLA $XOM $MFST

https://news.alertsandnews.com/apple-inc-nasdaqaapl-amazon-com-inc-nasdaqamzn-how-stock-splits-affected-performance-in-apple-tesla-and-more/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:27:54 </td>
   <td style="text-align:left;"> YOU&amp;#39;VE BEEN PUNKED!!!! $RIVN $LCID $NKLA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:27:32 </td>
   <td style="text-align:left;"> Rivian Stock Is Plunging. The EV Maker Came Up Short Everywhere.  $RIVN $TSLA $NIO 

https://newsfilter.io/a/e7d313faf05f4de839ac32ac3c0eecaf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:27:23 </td>
   <td style="text-align:left;"> $TSLA $HYMC ⬅️⬅️👀👀🚀🚀🌕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:27:18 </td>
   <td style="text-align:left;"> $TSLA 

Tesla stock is saturated with high short volume + an incredible volume of puts options  (~263B ) 

These massive moves -/+5% with wild swings are totaling more than 100b intraday ! 

How is this going to be fixed ?! 

Well based on my own instruments : 
- SP is too high and must be lowered to ~$150-$170 via 10:1 split allowing over 55M retail investors to hop in ! 
- Mark your long shares not for lending so brokers won’t lend them to Short sellers via liquidity providers aka market makers for the stock 
- HFs are currently owning the game with their unlawful trading tactics - BTD n Hold 
- Funds are underweight Tesla for how long ?! they have to rebalance !! expect a squeeze
- Do not let the psychological fatigue inflicted by HFs get to you swing a little and keep long shares untouched !! 

That’s my opinion and I’m always wrong !! 

🙏🏻🐉🦅😉🔥🚀🌔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:26:58 </td>
   <td style="text-align:left;"> $TSLA Competition misses earnings and lowers guidance and drops, then Tesla drops with it XD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:26:46 </td>
   <td style="text-align:left;"> $TSLA just fluctuating 30 points today five points after hours it’s down shorts already buying yachts Please just STFU lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:26:19 </td>
   <td style="text-align:left;"> $RIVN can&amp;#39;t they learn from $TSLA? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:26:16 </td>
   <td style="text-align:left;"> $SPY $MSFT $TSLA CEO Elon Musk asks a federal judge to remove ST_Patrol_Car restrictions for some of his Stocktwits posts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:25:32 </td>
   <td style="text-align:left;"> $TSLA looking for breakout around $830 tomorrow and next week. If breaks above we should go to sub $875, if not we have a long way down and upside-down cup and handle potentially flying us to $775 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:24:23 </td>
   <td style="text-align:left;"> $TSLA what’s with the drop AH? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:24:08 </td>
   <td style="text-align:left;"> $RIVN $DOCU wtf
Sooner or later, gotta make up for valuation
👀 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:23:55 </td>
   <td style="text-align:left;"> $TSLA I don’t see why it would be any different for Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:23:23 </td>
   <td style="text-align:left;"> $TSLA. Show me 600 baby.. inflation is crazy.chip crisis, war is there...nothing is going well...Sorry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:22:50 </td>
   <td style="text-align:left;"> $LCID $RIVN investors come to daddy $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:22:28 </td>
   <td style="text-align:left;"> $TSLA sell monthly csp 5% down and don’t need to look at market anymore. Collect your premium and laugh at bears as this shuffles $7-900 range every single month. Clock work. Down $30 today but my csp for April 1 is up almost $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:22:12 </td>
   <td style="text-align:left;"> $TSLA 85 PE and $420 price. Keep buying shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:22:04 </td>
   <td style="text-align:left;"> $TSLA did anyone else closed their position before market close? glad my prediction was right (sell off AH) -- good idea to jump back in tomorrow after market open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:22:01 </td>
   <td style="text-align:left;"> $RIVN And this shit was around 175 a while ago. Glad these worthless ev stocks are getting hammered. $7 is the real price for this. Nio, ggpi and tsla are the only reasonable ev stocks at the moment. Ggpi is heavily undervaluated.

$GGPI $NIO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:20:10 </td>
   <td style="text-align:left;"> Anyone here bullish on $f for the long term?

Besides buying long term calls on plays such as $f , $tsla, $gm , $bwa , why not sell calls against these long positions to lower your cost basis?

I’ve done up a YouTube tutorial on the strategy known as the poor man’s covered call

For those keen to know how it works, pls take a look :)

God bless you

The Poor Man&amp;#39;s Covered Call - A Cheaper Alternative to the Covered Call
https://youtu.be/-9VTlFK7mh0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:19:27 </td>
   <td style="text-align:left;"> $TSLA Tesla Increases Vehicle Prices As Nickel Squeeze Sparks Chaos 
$4100 price increase all models. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:18:17 </td>
   <td style="text-align:left;"> $TSLA Banckruptcy news coming.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:18:05 </td>
   <td style="text-align:left;"> $TSLA question for the chart readers, anyone know what daily Tesla candllestick pattern is saying or what formation? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:17:35 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s open at $800 and fall to $750 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:17:31 </td>
   <td style="text-align:left;"> $TSLA Tesla Increases Vehicle Prices As Nickel Squeeze Sparks Chaos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:16:54 </td>
   <td style="text-align:left;"> $TSLA slow bleed down, option seller dream </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:16:33 </td>
   <td style="text-align:left;"> $TSLA why is this selling off? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:13:51 </td>
   <td style="text-align:left;"> $TSLA honestly,  Tesla is crazy for opening in a socialist country like Berlin. Good luck with moving the family of snails off the northeast corner of Grunhuide. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:12:49 </td>
   <td style="text-align:left;"> 100% assured money if we short $RIVN on the day of earnings before close. $TSLA will crush competitors in a financial downturn if any </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:11:09 </td>
   <td style="text-align:left;"> $TSLA $HYMC 👀👀👀🚀🚀🚀🌕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:10:47 </td>
   <td style="text-align:left;"> $TSLA WOW!! Look at this AH STRENGTH! Did some news come out??? This is only down $3 AH… VERY IMPRESSIVE! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:10:43 </td>
   <td style="text-align:left;"> On 2/28/22, Bernstein analyst Toni Sacconaghi increased Tesla $TSLA price target to $450 (from $300) and kept an Underperform rating. The analyst noted that Tesla&amp;#39;s growth attract attention even among tech stocks. Toni has a performance score of 61.96, the 18th out of 39 featured analysts. The analyst has kept his price targets below the stock price, remaining bearish even as TSLA rose. It takes an average time of 129 days before his price target is met. Following Toni&amp;#39;s 2/8/21 price target recommendation would&amp;#39;ve lead to a loss of 7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:10:05 </td>
   <td style="text-align:left;"> $CXOXF $NVNXF $TSLA 
https://twitter.com/ErnestScheyder/status/1502041147996352517?t=853cI99amNZ5zzIas79Mbw&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:09:53 </td>
   <td style="text-align:left;"> $RIVN $LCID going to shit just like $RIDE $NKLA  none of these EV startups can compare to the $TSLA KING! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:08:17 </td>
   <td style="text-align:left;"> $TSLA any chance this goes back to 750? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:07:57 </td>
   <td style="text-align:left;"> $TSLA 860 tomorrow and I’ll eat my sock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:07:32 </td>
   <td style="text-align:left;"> $TSLA is just not innovating. Nothing exciting coming from this company. $FSR is primed to take over this industry for years to come. They have a long term strategy for total domination. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:07:25 </td>
   <td style="text-align:left;"> $RIVN $NIO $TSLA $SPY  
 
TAKE DOWN!!! 
 
Looks like valuations DO matter...especially now that the FED is no longer handing Trillions to Wall Street. 
 
Tesla is next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:06:38 </td>
   <td style="text-align:left;"> $TSLA $875 lvl on watch tmr for break </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:05:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $NIO $TSLA 

Imagine the violent rally if Putin got a bullet stuck in his head. All it takes is one hitman. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:04:12 </td>
   <td style="text-align:left;"> $RIVN $LCID $NIO and every other EV stock that was pumped the last two years and promised to be the next $TSLA is getting slaughtered. Tesla is truly in a league of its own. Competition is literally 5+ years away at best, probably a decade or more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:03:40 </td>
   <td style="text-align:left;"> $MULN Elon Musk and our CEO are friends just wait and see $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:02:33 </td>
   <td style="text-align:left;"> $TSLA Eu will take Tesla down to reality. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:02:19 </td>
   <td style="text-align:left;"> $RIVN  still the next $tsla ??? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:00:11 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-10 Options Analysis Video: 
https://www.youtube.com/watch?v=XDYRwwlnf1Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 06:00:01 </td>
   <td style="text-align:left;"> $RIVN Revenue of $54 million and stock is valued at $40 billion. Very nice!  Who says that the market is NOT in a bubble?  lol 
 
I am surprised $ARKK is not holding it or do they?  You never know with Cathie as she loves these kinds of stocks with little to no revenue. smh 
 
Even though $TSLA is overvalued, at least they sell lots of cars and are a leader in the EV market.   
 
Oh well, all the froth in $RIVN and the likes have a long ways to go, imho. 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:59:53 </td>
   <td style="text-align:left;"> $RIVN company burning 1.1 Billion per quarter, or 4.4 billion per year.  Add to that 2.6 billion capital expense and their 18.4 billion cash suddenly looks NOT ENOUGH.    Within two years, company will need secondary offering, raise cash through debt, or file bankruptcy.  $TSLA $GM $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:59:27 </td>
   <td style="text-align:left;"> $TSLA imagine just imagine if Tesla ever missed earnings holy shit this would fall 25%!!! $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:59:21 </td>
   <td style="text-align:left;"> $DWAC $FB $TSLA Self explanatory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:59:13 </td>
   <td style="text-align:left;"> $TSLA 
V shape was amazing 
Congrats Bulls. $850+ tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:58:38 </td>
   <td style="text-align:left;"> $TSLA Rivian now down 80% from Nov 16 high.  Competition is coming. 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:57:53 </td>
   <td style="text-align:left;"> $TSLA 😉💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:57:36 </td>
   <td style="text-align:left;"> $TSLA 

Aged well ! 🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:56:18 </td>
   <td style="text-align:left;"> $RIVN $LCID $TSLA there is only one undisputed winner. TESLA, and it&amp;#39;s still overpriced! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:55:43 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL In a new fad that is sweeping the nation, millions of couples are having &amp;quot;market sentiment&amp;quot; reveal parties to find out if their child will be bullish or bearish.   
 
This couple found out their child would be Bullish!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:55:41 </td>
   <td style="text-align:left;"> $RIVN $TSLA total over reaction.  If fraud Tesla is valued at almost $900B than RIVN should be a $100B market cap.   🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:55:38 </td>
   <td style="text-align:left;"> $TSLA carnivorous </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:55:18 </td>
   <td style="text-align:left;"> $TMC $TSLA $F $NIO 

“TMC also hopes to be able to announce an offtake with a major consumer brand or automaker in 2022.”

Who will it be?

https://www.spglobal.com/commodity-insights/en/market-insights/latest-news/energy-transition/012822-canadian-developer-the-metals-company-to-start-deep-water-tests-in-q1-2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:54:01 </td>
   <td style="text-align:left;"> $TSLA schmotley </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:53:55 </td>
   <td style="text-align:left;"> $MULN I am anticipating a Buy Out from $TSLA.  Perfect synergy.   
 
$TSLA can buy this stock with its pocket change...   
  
Buyout Price over $80 per share: Just north of $2 Billion.    
  
$MULN already has max bookings on their vehicles.  This stock has no where to go but up and $TSLA can take advantage now to avoid any competitive threat.  It is a perfect alliance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:52:08 </td>
   <td style="text-align:left;"> $RIVN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:51:57 </td>
   <td style="text-align:left;"> $TSLA schlotskys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:51:31 </td>
   <td style="text-align:left;"> $TSLA time to sell it all and buy $AMZN 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:51:10 </td>
   <td style="text-align:left;"> $RIVN Company says &amp;quot;Q1 off to slow start&amp;quot;  and things are going to get even slower as they focus on &amp;quot;quality&amp;quot; instead of &amp;quot;quantity&amp;quot;.    In other words, they have no idea what they&amp;#39;re doing.  $amzn $tsla $nio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:50:30 </td>
   <td style="text-align:left;"> $lac  Sanctions will push Lithium higher. LAC undervalued.    https://seekingalpha.com/article/4493864-lithium-americas-new-russian-sanctions-should-push-lithium-higher 
$F, $RVIN, $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:50:22 </td>
   <td style="text-align:left;"> $AAPL $AMZN $SPY $TSLA $MSFT

Keep compounding, keep investing!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:50:12 </td>
   <td style="text-align:left;"> $SPY this Yellen lady can’t manage taking care of her own teeth, and we’re supposed to trust her with the United States Treasury. 🥴 
 
Whatever. Buy some $AFI because they’re about to get bought. Read the latest filing.  
 
FJB. That is all.  
 
$BABA $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:50:09 </td>
   <td style="text-align:left;"> $TSLA any green tomorrow I’ll add more to my short. This is going to completely collapse. Hopium on low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:50:03 </td>
   <td style="text-align:left;"> $TSLA $AAPL $F elections and now biolabs 😔😔🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:49:07 </td>
   <td style="text-align:left;"> $RIVN $LCID 🗑 just proves $TSLA will always be #1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:47:33 </td>
   <td style="text-align:left;"> $TSLA hope we open green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:47:27 </td>
   <td style="text-align:left;"> $RIVN $TSLA and $NIO are the real deal , everyone else is imitating innovation , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:47:23 </td>
   <td style="text-align:left;"> $SPY  nice $RIVN can it help drag down $TSLA too? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:47:10 </td>
   <td style="text-align:left;"> $TSLA more red AH lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:45:30 </td>
   <td style="text-align:left;"> $TSLA mecca mecca high mecca heiny hoe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:45:11 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #5 stock that institutions are trading over rolling 5 day window with 117.2K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:44:53 </td>
   <td style="text-align:left;"> $RIVN lol the off brand $TSLA but yall dont have the moronic bulls to pump up the price to insane levels. See you in the 20s real soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:44:51 </td>
   <td style="text-align:left;"> $TSLA who snacked on those $850 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:44:46 </td>
   <td style="text-align:left;"> $TSLA not a bad intraday trading! Good job Nasdaq! (not bears 🤣) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:44:32 </td>
   <td style="text-align:left;"> $TSLA 825 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:43:56 </td>
   <td style="text-align:left;"> $TSLA  54.560  tests, and a $5,462 in Net Profit. Automated Trading by UltraAlgo (Available in TradeStation and TradingView). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:43:51 </td>
   <td style="text-align:left;"> $TSLA Watch out for the competition they say lol! $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:43:14 </td>
   <td style="text-align:left;"> $TSLA How can someone be this old like
Janet Yellen be in charge of treasury. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:43:11 </td>
   <td style="text-align:left;"> $TSLA 855 guaranteed tomorrow. anything over is just a present 🤌🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:42:55 </td>
   <td style="text-align:left;"> $TSLA picked the perfect setup. In: $814, Out: $838.85 
 
don&amp;#39;t know what tomorrow will bring, so got to be safe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:41:24 </td>
   <td style="text-align:left;"> $TSLA i want this mf at 950 tomorrow!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:41:23 </td>
   <td style="text-align:left;"> $TSLA Tesla?

More like what a mess-ah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:40:54 </td>
   <td style="text-align:left;"> $RIVN electric is garbage with $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:40:43 </td>
   <td style="text-align:left;"> $RIVN they should just become a reseller for $tsla... may be more profitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:40:01 </td>
   <td style="text-align:left;"> $TSLA when Optimus? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:38:50 </td>
   <td style="text-align:left;"> $TSLA print tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:37:58 </td>
   <td style="text-align:left;"> To answer the questions of fellows, yes I&amp;#39;d buy or at least hold, things will return to normal soon, and will sky rocket, some folks are just afraid of their own shadow :) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:36:31 </td>
   <td style="text-align:left;"> $TSLA 

$RIVN reported ER 👇

EPS of -$2.43 missing expectations -$1.97
Rev of $54M missing expectations of $60.03M

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:33:33 </td>
   <td style="text-align:left;"> $TSLA  unfortunately the odds are stacked against Mr Elon musk I am a big fan I love Tesla automobiles I love SpaceX, starlink satellites far off in the future way ahead. Unfortunately chip shortages inflation is driving the price of his vehicles up they just can&amp;#39;t even supply the vehicles, share price is no doubt going to drop some more, EV sectors are no doubt going to keep falling look at the price of Li  Nio  Lucid Rivian  x-peng all are less than what they used to be. This is going to keep going for the next 3 years. Believe it or not but it&amp;#39;s true the only thing that&amp;#39;s going to save these companies in America is to produce more petroleum products in America. America must be self-sufficient, independent of the rest of the world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:33:07 </td>
   <td style="text-align:left;"> Lithium Extraction | International Battery Metals $tsla 💰💰 https://www.ibatterymetals.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:32:39 </td>
   <td style="text-align:left;"> $TSLA when &amp;quot;funding secured&amp;quot;? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:32:14 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-10 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=eMp3aKUbf4c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:32:04 </td>
   <td style="text-align:left;"> $SPY I did good today. Made a 90 minute $TSLA  call doubler for a couple grand. Sold my $SPY $423 puts for a profit. Still have $435’s that expire tomorrow. 
Been a really nice week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:31:09 </td>
   <td style="text-align:left;"> $SPY They didn&amp;#39;t wanted to be too obvious. Is the only reason it didn&amp;#39;t close green 😬🤭
$AAPL $QQQ $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:28:01 </td>
   <td style="text-align:left;"> $RIVN how about $TSLA once they have their truck out.. rivian will need too put their truck in $WMT on clearance rack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:25:12 </td>
   <td style="text-align:left;"> $TSLA $LCID $RIVN The great NICKEL shortage ....DOWN DOWN... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:24:27 </td>
   <td style="text-align:left;"> $TSLA Elon Musk’s Space X will continue to work towards a permanent base on Mars. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:23:57 </td>
   <td style="text-align:left;"> $TSLA come on board with nuclear, Elon could buy the whole sector with about 1/5 of his money and he’s a fan of it! $UUUU $DNN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:21:17 </td>
   <td style="text-align:left;"> $RIV like this company but they need to produce something!! get your act together!...Nickel shortage maybe a problem for all $LCID $TSLA $FORD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:20:08 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:20:07 </td>
   <td style="text-align:left;"> $PLTR GOTHAM $QQQ $AAPL $TSLA 

https://www.palantir.com/in-defense-of-europe/en/

🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:19:37 </td>
   <td style="text-align:left;"> ( March 10, Motley Fool — $SNAP $TSLA $PLTR ) &amp;quot;3 Meme Stocks That Are Actually Solid Long-Term Picks&amp;quot; Source: https://www.fool.com/investing/2022/03/10/3-meme-stocks-that-are-actually-solid-long-term-pi/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:18:50 </td>
   <td style="text-align:left;"> $DPLS I wish I had found this stock sooner! I will never buy a boring large cap company again $TSLA $AMZN $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:17:37 </td>
   <td style="text-align:left;"> $TSLA i wonder if this will rip tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:17:26 </td>
   <td style="text-align:left;"> $TSLA based on actions from the last few days i think tesla may face short term downturn. its heavy business in china is one of the reason. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:17:05 </td>
   <td style="text-align:left;"> $TSLA big success only down 2.41% let’s celebrate lmfao more red tomorrow and we can celebrate again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:16:38 </td>
   <td style="text-align:left;"> Our tech companies getting slammed badly by bad policies from WH. China (and others) taking advantage of Sleepy Joe big league. Many people are talking. Not good! $AAPL $TSLA $AMZN $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:16:36 </td>
   <td style="text-align:left;"> $TSLA All good news is priced in and then some in to the company. Meanwhile the stock is being choked out below the 200 day moving average on the daily. Dark days ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:15:49 </td>
   <td style="text-align:left;"> $TSLA I was told something different by the bulls 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:13:46 </td>
   <td style="text-align:left;"> $TSLA when stock split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:12:38 </td>
   <td style="text-align:left;"> $TSLA it is killing options in both directions with stupid moves without a reason </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:12:07 </td>
   <td style="text-align:left;"> $ARKK $TSLA $COIN Cathys portfolio looks like she trades off robinhood and listens to a Discord group, why not add $GME and $AMC while your at it Cathy lolol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:11:32 </td>
   <td style="text-align:left;"> How Stock Splits Affected Performance In Apple, Tesla And More  $AMZN $TSLA $AAPL $XOM $MSFT 

https://newsfilter.io/a/e08833fbff3472271641458f2df5257b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:10:44 </td>
   <td style="text-align:left;"> $TSLA you really shorting this idiot? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:10:19 </td>
   <td style="text-align:left;"> $TSLA The most expensive electric igniter on Earth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:09:10 </td>
   <td style="text-align:left;"> $TSLA why the cump after??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:08:43 </td>
   <td style="text-align:left;"> $TSLA so tired of getting effed by cash account. By the time I can sell my options are always worthless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:07:45 </td>
   <td style="text-align:left;"> $TSLA  $F Friend who has a used car dealer said electric cars are super hot right now. Whether or not that translates into new car sales is another thing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:07:26 </td>
   <td style="text-align:left;"> $TSLA  at least I know my Carnival Cruise line will double this year…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:06:44 </td>
   <td style="text-align:left;"> $TSLA TARGET FILLED!🔥 went to 810!
Crazy gains if u got in🎉🎉
Free discord in bio! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:06:42 </td>
   <td style="text-align:left;"> $TSLA every day investors, institutional investors and retail, are given the opportunity to exit this impending train wreck. Yet, these fools continue to hold. smh There is a good chance that Musk is on his way out of this company.  Furthermore, if you haven&amp;#39;t noticed, and will begin to notice later in the month, stock doesn&amp;#39;t appear to have the daily pumps. No more QE for Musk&amp;#39;s affiliates to help pump up his stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:06:40 </td>
   <td style="text-align:left;"> $TSLA imagine not buying this for the next 5-10 years+ 😂💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:06:08 </td>
   <td style="text-align:left;"> $TSLA imagine shorting this how stupid are you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:05:01 </td>
   <td style="text-align:left;"> $TSLA Closed right under 200sma. 

Tomorrow will be interesting for sure. Also people screaming OPEX this has tanked 100pts on Friday and soared before so GTFO with that nonsense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:04:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AMD 

Wow that wasn’t obvious at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:04:48 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:04:08 </td>
   <td style="text-align:left;"> $TSLA once again my puts pay but I can&amp;#39;t sell. Wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:03:55 </td>
   <td style="text-align:left;"> $TSLA still a win for the bears today. Tomorrow we see sub $800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:03:19 </td>
   <td style="text-align:left;"> $TSLA Closed above the 50 on the daily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:03:11 </td>
   <td style="text-align:left;"> $TSLA Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:02:05 </td>
   <td style="text-align:left;"> $TSLA @ CPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:01:57 </td>
   <td style="text-align:left;"> $TSLA Don&amp;#39;t listen to the b*******  all about timing. &amp;quot;were&amp;quot; there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:01:19 </td>
   <td style="text-align:left;"> $TSLA unless we can get 7-8% move tomorrow (very unlikely , not imposible) you can kiss 900 EOW goodbye 😪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:01:08 </td>
   <td style="text-align:left;"> $TSLA 875 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-03-11 05:00:19 </td>
   <td style="text-align:left;"> TSLA Should Follow Amazon Stock Split and Break Up Shares Again

$TSLA $AMZN  

https://investorplace.com/2022/03/tsla-should-follow-amazon-stock-split-and-break-up-tsla-stock-shares-again/ </td>
  </tr>
</tbody>
</table></div>

---
