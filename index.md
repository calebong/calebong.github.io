---
output:
  html_document:
    keep_md: true
---

# Investment Analytics Portfoliosss

My portfolio exhibits various examples of the data analytics and financial modelling that I conduct in my daily workflows.

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



Last Updated: 2023-06-09 20:13:30 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 20:13:10 </td>
   <td style="text-align:left;"> Mexico Industrial Output Continues to Slow </td>
   <td style="text-align:left;"> Mexico’s industrial production went up by 0.7% from a year earlier in April 2023, following a downwardly revised 1.5% increase in the prior month and below market forecasts of a 1.3% rise. It marks the 18th consecutive month of growth in industrial activity, albeit the weakest since October 2021, supported by mining &amp; quarrying (1.9% vs 2.2%); manufacturing (1.4% vs 1.1%), and, to a lesser extent, utilities (0.6% vs 3.8%). Meanwhile, output contracted for construction (-2% vs 1.7%). On a seasonally adjusted monthly basis, industrial output rose by 0.4% in April, after a 0.9% fall in March, in line with market estimates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 20:00:47 </td>
   <td style="text-align:left;"> MOEX Holds Gains Despite Hawkish CBR </td>
   <td style="text-align:left;"> The ruble-based MOEX Russia index held slight gains and hovered close to the 2,715 mark, extending the advance from the previous session with support from banks and oil companies, while investors digested the Central Bank of Russia’s interest rate decision. The CBR held borrowing costs unchanged for the sixth consecutive decision but paved the way for rate hikes in the incoming meetings as inflationary risks are higher than before. Banking giant Sberbank hovered flat after its May results were broadly in line with market expectations, while shares in the rest of the sector booked sharp gains on the back of solid results from VTB posted earlier in the week. In the meantime, gains for oil companies were led by a 5% surge for preferred Surgut shares following the announcement of strong 2022 results. Also, Transneft added 1.6% as its board will announce dividends on Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/dealbook/trump-indictment-2024.html </td>
   <td style="text-align:left;"> 2023-06-09 19:55:59 </td>
   <td style="text-align:left;"> Donald Trump’s Latest Indictment May Reshape the 2024 Race - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , DealBook Newsletter                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The former president, who faces seven criminal charges for mishandling classified documents, is expected to surrender to authorities next week.                                                                                                                                                                                                                                                                                                                                         , By Andrew Ross Sorkin, Ravi Mattu, Bernhard Warner, Sarah Kessler, Michael J. de la Merced, Lauren Hirsch and Ephrat Livni                                                                                                                                                                                                                                                                                                                                                              , For the second time in two months, Donald Trump will surrender to the authorities to face legal charges, dropping another bomb into the 2024 presidential race. Within minutes, he was fund-raising on the back of the news.                                                                                                                                                                                                                                                            , The indictment won’t be unsealed until next week, but some details are known. The former president and front-runner for the Republican nomination faces seven criminal charges that he mishandled classified documents from his time in the White House and obstructed the government’s efforts to reclaim them. He is expected to turn himself in to the authorities on Tuesday.                                                                                                       , Mr. Trump himself broke the news last night, a sign his inner circle had been bracing for the indictment for weeks.                                                                                                                                                                                                                                                                                                                                                                     , On his Truth Social platform, Mr. Trump called the charges “election interference at the highest level,” adding, “I’m an innocent man.”                                                                                                                                                                                                                                                                                                                                                 , Mr. Trump’s legal troubles keep piling up. But this indictment holds greater “legal gravity and political peril,” writes The Times’s Peter Baker. It’s not just a first in American history for a former president, but also involves the nation’s secrets.                                                                                                                                                                                                                             , Here’s a recap of the other legal matters he faces:                                                                                                                                                                                                                                                                                                                                                                                                                                     , A federal grand jury last month ordered Mr. Trump to pay $5 million to the journalist E. Jean Carroll in a civil case that he sexually abused and then defamed her; Carroll’s legal team has sued Mr. Trump again over subsequent comments he made about her.                                                                                                                                                                                                                           , In April, the New York authorities charged Mr. Trump with falsifying business documents in connection with hush-money payments to the porn star Stormy Daniels in the run-up to the 2016 presidential election.                                                                                                                                                                                                                                                                         , Mr. Trump is also under investigation in Georgia for possible election tampering in the state; a decision is expected later this summer.                                                                                                                                                                                                                                                                                                                                                , Mr. Trump’s Republican challengers came to his defense. Gov. Ron DeSantis of Florida, his nearest rival in the polls, accused the Biden administration of weaponizing the Justice Department to take on a political rival. And Vivek Ramaswamy, the anti-woke financier, said he would pardon Mr. Trump if elected president.                                                                                                                                                           , Mr. Trump gained in the polls the last time he was charged. It is unclear if the public will be so supportive this time. A Yahoo-YouGov poll showed nearly two-thirds of Americans view the charges of removing classified documents and obstructing the investigation as a serious criminal matter; a similar percentage feel that he should not serve as president if convicted.                                                                                                      , So far, big-money conservative donors have stayed mum on the latest charges. Many have deserted Mr. Trump after backing him in previous election cycles.                                                                                                                                                                                                                                                                                                                                , The wildfire haze is moving on from the Northeast. Cities including New York and Philadelphia have seen air conditions improve, though the noxious smoke is spreading south and west; the F.A.A. has lifted ground stops at LaGuardia and Newark airports. But scientists confirmed that the El Niño weather phenomenon has started, portending hotter temperatures through next year.                                                                                                  , China suffers from a lack of inflation. New monthly data shows that producer prices fell 4.6 percent in May, the sharpest year-on-year drop in seven years, while consumer prices rose just 0.2 percent. Though a contrast from Western countries grappling with rapid inflation, the trend suggests China’s faltering economy may soon suffer from deflation.                                                                                                                          , The White House reportedly braces for the death of its student loan forgiveness program. Biden administration officials are privately worrying that the Supreme Court may strike down its proposal, which would eliminate up to $20,000 in education debt per person for millions of Americans, according to The Wall Street Journal. The White House is preparing less legally risky alternatives to help borrowers.                                                                   , G.M. electric vehicles will gain access to Tesla’s charging network. The move, which follows a similar announcement by Ford, will vastly expand charger accessibility for G.M. But some in the industry fear that wider adoption of Tesla’s plugs, which are now likely to become the industry standard, will give Elon Musk’s company even greater power over the E.V. market.                                                                                                         , Investors shrugged off lousy labor market data and a new round of inflation warnings to push the S&amp;P 500 into bull market territory on Thursday. But that enthusiasm seems to be waning on Friday morning as stock futures suggest markets will open lower.                                                                                                                                                                                                                             , The bear market lasted 248 trading days, the longest such run since 1948. Since its October low, the S&amp;P 500 has gained 20.04 percent, just enough to tip into a bull market. The benchmark index is still roughly 10 percent away from a record high; some market observers say, therefore, that it’s premature to call this a true bull market.                                                                                                                                       , Investor enthusiasm for artificial intelligence has underpinned this rally. According to Deutsche Bank analysts, the FANG+ Index — a collection of big cap tech stocks, many of which are expanding into A.I. — is up nearly 80 percent since ChatGPT debuted in November.                                                                                                                                                                                                              , Now to the bad news … A growing number of economists believe that next week’s Consumer Price Index report will show an uptick in core inflation. That could pressure the Fed to raise interest rates further — if not next week, in July.                                                                                                                                                                                                                                               , And there are signs of economic weakness. The Labor Department on Thursday reported 261,000 new jobless claims, the highest number since October 2021.                                                                                                                                                                                                                                                                                                                                  , Expect a prolonged period of economic uncertainty. That was the message from Mario Draghi, the former Italian prime minister and president of the E.C.B., in a speech on Thursday at M.I.T.                                                                                                                                                                                                                                                                                             , The economist, who once famously vowed to do “whatever it takes” to save the euro, has a bearish view of the future. He warned that industrialized economies face a “volatile cocktail” of persistent inflation, high budget deficits, high interest rates and low potential growth as central banks grapple with a climate crisis, the reshoring of supply chains and the impact of Russia’s war in Ukraine.                                                                           , Regulators and crypto executives are making their cases in the court of public opinion after the S.E.C. sued Binance and Coinbase, two of the sector’s biggest exchanges, this week in an intensifying crackdown on the industry.                                                                                                                                                                                                                                                       , “We’ve seen this story before,” the S.E.C. chairman Gary Gensler said on Thursday at a fintech conference, likening widespread noncompliance in crypto to the era of “hucksters” and fraud a century ago. He rejected claims that digital asset businesses cannot comply with the existing rules or do not realize that they apply: “When crypto asset market participants go on Twitter or TV and say they lacked ‘fair notice’ that their conduct could be illegal, don’t believe it.”, Coinbase’s boss says that new regulations are needed. Its C.E.O., Brian Armstrong, addressed the event on Wednesday, saying the rules are opaque and need to be updated. The S.E.C. case is certainly a drag on his company: Moody’s, the ratings agency, downgraded Coinbase on Thursday to negative from stable because of the charges.                                                                                                                                               , Binance is regrouping. The company’s American division said on Thursday that it would no longer allow customers to trade in U.S. dollars, after banks stopped working with it. At the same time, the S.E.C. says it is trying to find “alternative means” to serve legal papers to Binance and Changpeng Zhao, the company’s C.E.O., telling a federal court that it was difficult to determine where he was.                                                                           , Who’s judging? The S.E.C.’s case against Coinbase in New York was assigned to District Judge Jennifer Rearden. Her nomination last year angered some Democratic lawmakers because she represented Chevron as a lawyer at Gibson, Dunn &amp; Crutcher. She’s also handling the government’s appeal of the sale of the failed crypto broker Voyager to Binance’s U.S. arm and put the deal on hold in March.                                                                                  , Judge Amy Berman Jackson of the Federal District Court for D.C. is presiding over the Binance case, and is best known for overseeing the criminal proceedings against two Mr. Trump advisers, Paul Manafort and Roger Stone. Next week, she will hold a hearing on an S.E.C. request to freeze Binance’s assets.                                                                                                                                                                        , — Steven Schwartz, a lawyer who has practiced in New York for 30 years. He told a federal judge that he regrets using the chatbot to write a legal brief that was found to be filled with fake judicial opinions and legal citations.                                                                                                                                                                                                                                                   , Apple unveiled its first headset for augmented/virtual/mixed reality this week, but none of those words appears in a nine-minute video on its website about the $3,500 Vision Pro goggles. Instead, the company preferred a more obscure term: “spatial computing.”                                                                                                                                                                                                                     , Apple is trying to put its own stamp on the category. When it comes to spatial computing, “no one knows what that is — and that provides Apple the opportunity to define it,” Marcus Collins, the author of “For the Culture: The Power Behind What We Buy, What We Do and Who We Want to Be,” told DealBook.                                                                                                                                                                           , Apple has successfully done this in the past. Before the App Store, people didn’t talk about apps; they talked about “software programs.”                                                                                                                                                                                                                                                                                                                                               , And the iPhone and AirPods were neither the first mobile phone nor the first earbuds, but they became runaway hits (despite being priced at a premium to the competition).                                                                                                                                                                                                                                                                                                              , Jim Posner, a communications consultant who has led teams at Twitter and Google, said that the intended audience may be investors and the media rather than consumers. “They are pitching a product to people,” he said. “For the tech press, industry analysts and investors, they’re pitching a concept.”                                                                                                                                                                             , Elsewhere, Mark Zuckerberg gave his thoughts on Apple’s Vision Pro goggles. “I was really curious to see what they’d ship,” the Meta C.E.O. told employees on Thursday, “and it’s a good sign for our own development that they don’t have any magical solutions to the laws of physics that we haven’t already explored.”                                                                                                                                                              , Deals                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The agricultural commodities giant Bunge is said to be finalizing a deal to buy Viterra, a grain trader, that could value the combined firm at $30 billion. (Reuters)                                                                                                                                                                                                                                                                                                                   , UBS has secured a government backstop for losses tied to its takeover of Credit Suisse, clearing the last hurdle for combining Switzerland’s top two banks. (FT)                                                                                                                                                                                                                                                                                                                        , Permira is reportedly weighing a sale or public listing for Golden Goose, a footwear brand favored by Taylor Swift, at a $2.7 billion valuation. (Bloomberg)                                                                                                                                                                                                                                                                                                                            , Policy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Louisiana passed a bill that would block online services — including Instagram, TikTok and Fortnite — for children under 18 without their parents’ permission. (NYT)                                                                                                                                                                                                                                                                                                                    , The Supreme Court unanimously ruled against a dog-toy maker whose product closely resembles a bottle of Jack Daniels whiskey. (NYT)                                                                                                                                                                                                                                                                                                                                                     , Best of the rest                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Sam Altman of OpenAI, Bob Iger of Disney, Jay Monahan of the PGA Tour, Rupert Murdoch of Fox and Sundar Pichai of Alphabet are all on the guest list for this year’s Allen &amp; Company gathering in Sun Valley, Idaho. (Variety)                                                                                                                                                                                                                                                          , How Taylor Swift is a godsend for Chicago’s hotel industry. (Bloomberg)                                                                                                                                                                                                                                                                                                                                                                                                                 , “What All the Single Ladies (and Men) Say About the Economy” (NYT)                                                                                                                                                                                                                                                                                                                                                                                                                      , We’d like your feedback! Please email thoughts and suggestions to dealbook@nytimes.com.                                                                                                                                                                                                                                                                                                                                                                                                 , Andrew Ross Sorkin is a columnist and the founder and editor at large of DealBook. He is a co-anchor of CNBC’s "Squawk Box" and the author of “Too Big to Fail.” He is also a co-creator of the Showtime drama series "Billions."  @andrewrsorkin • Facebook                                                                                                                                                                                                                            , Ravi Mattu is the managing editor of DealBook, based in London. He joined The New York Times in 2022 from the Financial Times, where he held a number of senior roles in Hong Kong and London.  @ravmattu                                                                                                                                                                                                                                                                               , Bernhard Warner joined the The Times in 2022 as a senior editor for DealBook. Previously he was a senior writer and editor at Fortune focusing on business, the economy and the markets.  @bernhardwarner                                                                                                                                                                                                                                                                               , Sarah Kessler is a senior staff editor for DealBook and the author of “Gigged,” a book about workers in the gig economy.  @sarahfkessler                                                                                                                                                                                                                                                                                                                                                , Michael de la Merced joined The Times as a reporter in 2006, covering Wall Street and finance. Among his main coverage areas are mergers and acquisitions, bankruptcies and the private equity industry.  @m_delamerced • Facebook                                                                                                                                                                                                                                                      , Lauren Hirsch joined The Times from CNBC in 2020, covering deals and the biggest stories on Wall Street.  @laurenshirsch                                                                                                                                                                                                                                                                                                                                                                , Ephrat Livni reports from Washington on the intersection of business and policy for DealBook. Previously, she was a senior reporter at Quartz, covering law and politics, and has practiced law in the public and private sectors.    @el72champs                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/09/stocks-making-the-biggest-moves-premarket-target-tesla-general-motors-docusign-and-more.html </td>
   <td style="text-align:left;"> 2023-06-09 19:47:51 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Target, Tesla, General Motors, DocuSign and more </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                   , Loans                                                                                                                                                                                                                                                                                                                                          , Banking                                                                                                                                                                                                                                                                                                                                        , Mortgages                                                                                                                                                                                                                                                                                                                                      , Insurance                                                                                                                                                                                                                                                                                                                                      , Credit Monitoring                                                                                                                                                                                                                                                                                                                              , Personal Finance                                                                                                                                                                                                                                                                                                                               , Small Business                                                                                                                                                                                                                                                                                                                                 , Taxes                                                                                                                                                                                                                                                                                                                                          , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                     , Investing                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                         , All Credit Cards                                                                                                                                                                                                                                                                                                                               , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                   , Best Credit Cards                                                                                                                                                                                                                                                                                                                              , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                      , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                       , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                       , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                             , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                    , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                               , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                                                                                                                         , All Loans                                                                                                                                                                                                                                                                                                                                      , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                            , Best Personal Loans                                                                                                                                                                                                                                                                                                                            , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                  , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                       , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                   , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                      , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                      , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                            , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                                                         , All Banking                                                                                                                                                                                                                                                                                                                                    , Find the Savings Account for You                                                                                                                                                                                                                                                                                                               , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                               , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                 , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                  , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                             , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                  , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                     , Best CDs                                                                                                                                                                                                                                                                                                                                       , Best Credit Unions                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                         , All Mortgages                                                                                                                                                                                                                                                                                                                                  , Best Mortgages                                                                                                                                                                                                                                                                                                                                 , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                          , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                             , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                         , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                        , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                      , Affording a Mortgage                                                                                                                                                                                                                                                                                                                           , SELECT                                                                                                                                                                                                                                                                                                                                         , All Insurance                                                                                                                                                                                                                                                                                                                                  , Best Life Insurance                                                                                                                                                                                                                                                                                                                            , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                      , Best Renters Insurance                                                                                                                                                                                                                                                                                                                         , Best Car Insurance                                                                                                                                                                                                                                                                                                                             , Travel Insurance                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                         , All Credit Monitoring                                                                                                                                                                                                                                                                                                                          , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                 , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                 , Credit Repair Services                                                                                                                                                                                                                                                                                                                         , SELECT                                                                                                                                                                                                                                                                                                                                         , All Personal Finance                                                                                                                                                                                                                                                                                                                           , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                            , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                      , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                       , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                     , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                  , Best Debt Relief                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                         , All Small Business                                                                                                                                                                                                                                                                                                                             , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                           , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                          , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                           , Best Small Business Loans                                                                                                                                                                                                                                                                                                                      , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                           , SELECT                                                                                                                                                                                                                                                                                                                                         , All Taxes                                                                                                                                                                                                                                                                                                                                      , Best Tax Software                                                                                                                                                                                                                                                                                                                              , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                         , Tax Refunds                                                                                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                                                         , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                 , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                               , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                             , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                   , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                        , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                          , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                   , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                   , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                  , Best Hardship Loans                                                                                                                                                                                                                                                                                                                            , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                         , All Investing                                                                                                                                                                                                                                                                                                                                  , Best IRA Accounts                                                                                                                                                                                                                                                                                                                              , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                         , Best Investing Apps                                                                                                                                                                                                                                                                                                                            , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                              , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                             , Index Funds                                                                                                                                                                                                                                                                                                                                    , Mutual Funds                                                                                                                                                                                                                                                                                                                                   , ETFs                                                                                                                                                                                                                                                                                                                                           , Bonds                                                                                                                                                                                                                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                , Check out the companies making headlines in premarket trading.                                                                                                                                                                                                                                                                                 , Tesla, General Motors -- Both carmaker stocks were climbing in premarket trading, with gains of 5.7% and 5%, respectively. General Motors announced on Thursday plans to utilize Tesla's electric vehicle charging network, and said its vehicles will also utilize Tesla's North American Charging Standard port in its cars starting in 2025., Corning — Shares of the glass materials maker added 3.2% after an upgrade from Morgan Stanley, which labeled the company's business as "derisked."                                                                                                                                                                                             , DocuSign – The e-signature provider's stock rose about 5% premarket after the company reported earnings and revenue that beat analysts estimates for the fiscal quarter ended April 30, issued upbeat guidance and announced a handful of new service offerings and C-suite hires.                                                             , Adobe — Shares of the software company gained more than 3% after Wells Fargo upgraded the stock Friday morning to overweight, according to StreetAccount.                                                                                                                                                                                      , Target — The retail giant slipped 1.3% after Citi downgraded the stock over concerns that sales may have peaked.                                                                                                                                                                                                                               , Nio — Shares of the electric vehicle company dipped 2% in premarket trading after it reported that vehicle sales decreased 0.2% year over year. The company's vehicle margin and net loss also worsened year over year.                                                                                                                        , Sonoma Pharmaceuticals — The company's stock soared nearly 33% after announcing Thursday evening a new application for its intraoperative pulse lavage irrigation treatment that could replace IV bags in some surgical procedures. Sonoma said the treatment will be available in Europe this year and in the U.S. commercially in 2024.      , — CNBC's Tanaya Macheel and Jesse Pound contributed reporting.                                                                                                                                                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                               , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 19:45:41 </td>
   <td style="text-align:left;"> US Futures Point to Mixed Open </td>
   <td style="text-align:left;"> US futures were mixed on Friday, with contracts on the Dow Jones falling nearly 70 points, while the S&amp;P 500 was little changed after entering bull market territory the day before, and Nasdaq 100 futures added 0.1%. Investors refrain from making big bets ahead of key US CPI report and the FOMC decision next week. On the corporate front, Tesla shares rallied 6% and General Motors was up over 4% in premarket trading after the latter announced it will use Tesla technology to charge its electric vehicles. On the other hand, stocks of Target lost over 1% after Citigroup analysts cut their rating. So far on the week, the Dow is up 0.2%, the S&amp;P 500 gained nearly 0.3% to book a fourth straight week of gains while the Nasdaq is little changed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2023-06-09 19:42:50 </td>
   <td style="text-align:left;"> Russian Ruble Sinks to 1-Year Low </td>
   <td style="text-align:left;"> The Russian ruble weakened toward 82.5 per USD in June, the lowest in over one year, and trading below levels before Russia’s invasion of Ukraine amid continued pressure from Russia’s unsustainable fiscal deficit and persistently low energy prices. New data from the Ministry of Finance showed that the Federal government posted a budget deficit of RUB 3.4 trillion in the first five months of the year, the highest on record, as war spending surged and energy revenues plummeted. Consequently, the Ministry announced that it sold four tonnes of gold and CNY 2.6 billion from its National Welfare Fund to finance its budget deficit. The low inflows also forced the Kremlin to continue selling foreign currency. On the other hand, increased inflationary risks in the Russian economy drove the Central Bank to flag interest rate hikes in the upcoming meetings, reigning in losses for the ruble. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macedonia/unemployment-rate </td>
   <td style="text-align:left;"> 2023-06-09 19:36:29 </td>
   <td style="text-align:left;"> Macedonia Jobless Rate Hits New Record Low </td>
   <td style="text-align:left;"> The unemployment Rate in North Macedonia fell further to 13.4 percent in the first quarter of 2023, down from 14 percent in the previous period. This was the lowest jobless rate since comparable records began in 1993, as the number of unemployed declined by 8 thousand to 104.4 thousand and the number of employed was also down by 13 thousand to 683 thousand. Meanwhile, the employment rate edged down to 45.1 percent from 47.2 percent, while the activity rate fell to 52 percent from 54.9 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cocoa </td>
   <td style="text-align:left;"> 2023-06-09 19:21:00 </td>
   <td style="text-align:left;"> Cocoa Hits 4-Week High </td>
   <td style="text-align:left;"> Cocoa futures jumped above $3,170 a tonne, its highest in four weeks, amid growing concerns about tight global supplies. In Ivory Coast, the world’s leading cocoa-producing country, both the volume of cocoa beans and harvest forecasts continue to fall. For the 2022-2023 harvest campaign, the government is predicting a harvest of 450,000 tonnes, or even 500,000 tonnes, which is smaller than the 600,000 tonnes harvested during the 2021-2022 interim campaign. Recent rains have also raised concern over the quality of the mid-crop. Latest data showed that farmers sent a cumulative 2.09 million tonnes of cocoa to Ivory Coast ports for the 2022/23 marketing year, which runs from October 1 through May 28, down 3% from the same period last season. Adding to the bullish tone, fears mount that an El Nino weather event could undercut global cocoa production. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 19:14:28 </td>
   <td style="text-align:left;"> BIST 100 Above 5500 Level </td>
   <td style="text-align:left;"> The Turkish benchmark BIST 100 index has surged nearly 16% since the runoff election, surpassing the 5,500 level and hitting the highest level since January, after the appointment of Hafize Gaye Erkan, formerly a co-CEO at First Republic Bank and a managing director at Goldman Sachs, as the head of Turkey's central bank. Following the assignment of highly respected former banker Mehmet Simsek as Minister of Treasury and Finance, this move indicated a notable signal of President Erdogan's shift from unorthodox economic policies that had resulted to high inflation, low interest rates, a plummeting lira, and negative net foreign exchange reserves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2023-06-09 19:04:00 </td>
   <td style="text-align:left;"> European Natural Gas Prices Up 20% on the Week </td>
   <td style="text-align:left;"> Natural gas futures in Europe surged more than 20% to nearly €29 per megawatt-hour in the second week of June, as concerns about lower supplies outweighed ample gas storage levels and weaker demand. Gas shipments from the US are becoming scarcer as the supply is funneled to Asia, where prices are more competitive in the summer months due to stronger demand for cooling. Meanwhile, France's Montoir LNG terminal will be closed for maintenance until June 10, and Norway's Equinor has postponed the restart of its Hammerfest LNG plant to June 14 due to technical difficulties. Additionally, the Turkstream gas pipeline, which transports gas from Russia through the Black Sea to Turkey, is suspended until June 12 for maintenance work. Currently, Europe's gas storage is 70.4% full, and the European Union aims to achieve a storage inventory target of 90% by November 1. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macedonia/producer-prices-change </td>
   <td style="text-align:left;"> 2023-06-09 19:02:40 </td>
   <td style="text-align:left;"> Macedonia Producer Inflation Lowest Since 2020 </td>
   <td style="text-align:left;"> Macedonia's producer prices rose 1.6% year-on-year in April 2023, easing from a 5% hike in the previous month. This was the lowest producer inflation rate since November 2020, as cost declined significantly for mining &amp; quarrying (-9.8% vs -2.4% in March) and prices also slowed for manufacturing (1.6% vs 5%). On the other hand, prices advanced faster for electricity, gas, steam &amp; air conditioning supply (17.1% vs 5%). On a monthly basis, producer prices went up 0.4% in April, following a 0.1% fall in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/consumer-confidence </td>
   <td style="text-align:left;"> 2023-06-09 19:02:22 </td>
   <td style="text-align:left;"> Spain Consumer Morale Jumps to Over 1-Year High </td>
   <td style="text-align:left;"> The consumer confidence indicator in Spain jumped to 81.5 in May of 2023 from 73 in the previous month, the highest since the start of the Russian invasion of Ukraine in February of 2022 to challenge a series of gloomy economic data in the Eurozone. The subindex measuring current conditions for the Spanish consumer rose by 8.7 points from the previous month to 71.5, while that measuring future expectations jumped by 8.4 points to 91.5. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2023-06-09 19:00:40 </td>
   <td style="text-align:left;"> US Natural Gas Futures Fall, Set for Weekly Gain </td>
   <td style="text-align:left;"> US natural gas futures fell below $2.3/MMBtu after mild weather last week kept demand for the fuel low and allowed utilities to inject more gas into storage. The latest EIA report showed US utilities added 118 billion cubic feet of gas into storage, slightly more than market expectations of a 113 bcf increase. Despite this setback, natural gas prices in the US are on course for an over 5% weekly gain, recovering from two consecutive periods of losses, in anticipation of increased demand from air conditioning usage amid forecasts for warmer weather. The number of cooling degree days (CDDs) in the coming two weeks is expected to rise to 167, above the 30-year normal of 149, according to Refinitiv. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/latvia/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 18:53:00 </td>
   <td style="text-align:left;"> Latvia Trade Deficit Little Changed in April </td>
   <td style="text-align:left;"> Latvia's trade deficit remained almost unchanged at EUR 450.5 million in April 2023, following EUR 455.3 million in the same month of the previous year, as exports dropped faster than imports. Exports plunged by 9.5% yoy to EUR 1.52 billion due to falling sales of wood &amp; wood products (-33.4%), mineral fuels, mineral oils &amp; products of their distillation (-45.3%), and iron &amp; steel (-19.9%). Most shipments went to Lithuania (17.9 % of total exports), Estonia (11.3 %), Germany (6.7 %), and Sweden (5.8 %). Meanwhile, imports decreased at a softer 7.2% to EUR 1.97 billion on lower purchases of mineral fuels, mineral oils &amp; products of their distillation (-52.9%), and products of the chemical and allied industries (-12.3%). The main import partners were Lithuania (18.2 % of total imports), Germany (10.5 %), Poland (10.2 %), and Canada (9.1%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/interest-rate </td>
   <td style="text-align:left;"> 2023-06-09 18:49:00 </td>
   <td style="text-align:left;"> Russia Holds Rate, Flags Possibility of Future Hikes </td>
   <td style="text-align:left;"> The Central Bank of Russia held its key interest rate unchanged at 7.5% for the sixth consecutive decision in its June 2023 meeting, in line with market expectations, but flagged a higher possibility of rate hikes in the upcoming meetings due to higher inflationary risks. The bank noted that inflation is due to rise as base effects from the war will start to fade, while consumer demand recovers from last year’s crash and the effects of a weaker ruble pass through. Inflationary expectations are also higher as war spending and lower energy prices spark a record-high budget deficit for the Federal government, pressuring the ruble and lifting bond yields. Additionally, production costs are higher as the military mobilization caused a crash in the labor force and pressured firms’ capacity. Policymakers also noted that economic activity has picked up at a greater pace than expected. The CBR expects inflation to hover between the 4.5-6.5% range this year before steadying at 4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/malaysia-names-abdul-rasheed-ghaffour-as-central-bank-governor </td>
   <td style="text-align:left;"> 2023-06-09 18:36:21 </td>
   <td style="text-align:left;"> Malaysia Names Abdul Rasheed Ghaffour as Central Bank Governor </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                               , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                             , Bloomberg Quicktake explores the world of technology and the people who power it. From innovative gadgets to ground-breaking science, dive into the advancements changing our daily lives and the business that drives it.            , UBS Chief Ermotti Sees ‘Bumpy’ Months Ahead as Deal Close Nears                                                                                                                                                                       , Ex-Barclays CEO Jes Staley Set to Appear for Epstein Deposition                                                                                                                                                                       , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                      , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                           , Ex-PBOC Deputy Governor Accused of Bribery, Abuse of Power                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                        , Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank                                                                                                                                                                      , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                              , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                      , Mark Zuckerberg Shares AI Products to Reassure Workers of Strategy                                                                                                                                                                    , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                         , Italy Will Keep Blocking EU Bailout Fund Approval, Meloni Says                                                                                                                                                                        , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                           , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                            , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                           , How to Re-Create European Styles of Grilling                                                                                                                                                                                          , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                  , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                     , The Consumer Spending Mystery Is Really No Mystery                                                                                                                                                                                    , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                    , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                 , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                         , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                      , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                       , NY Skies Start Clearing as Rain in Sight: Smoky Air Latest                                                                                                                                                                            , Climate Change and Homeowners’ Insurance Are on a Collision Course                                                                                                                                                                    , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                        , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                      , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                              , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                    , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                      , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                       , Shaik Abdul Rasheed Abdul Ghaffour                                                                                                                                                                                                    , Anisah Shukry                                                                                                                                                                                                                         , Subscriber Benefit                                                                                                                                                                                                                    , Subscribe                                                                                                                                                                                                                             , Malaysia named Shaik Abdul Rasheed Abdul Ghaffour as its new central bank governor, tasked with fostering stability and confidence in an economy under pressure from slowing global demand, volatile inflation and a weakened ringgit., Malaysia’s king approved Abdul Rasheed as the governor from July 1 for a period of five years, Bank Negara Malaysia said Friday. He will replace Nor Shamsiah Mohd Yunus, whose term ends June 30, according to the statement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/zimbabwe-share-prices-daily-limit-raised-after-760-jump </td>
   <td style="text-align:left;"> 2023-06-09 18:27:11 </td>
   <td style="text-align:left;"> Zimbabwe Lifts Daily Share-Move Limit to Cope With Price Surges </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                                               , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                             , Bloomberg Quicktake explores the world of technology and the people who power it. From innovative gadgets to ground-breaking science, dive into the advancements changing our daily lives and the business that drives it.                                                                                                                            , UBS Chief Ermotti Sees ‘Bumpy’ Months Ahead as Deal Close Nears                                                                                                                                                                                                                                                                                       , Ex-Barclays CEO Jes Staley Set to Appear for Epstein Deposition                                                                                                                                                                                                                                                                                       , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                      , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                                           , Ex-PBOC Deputy Governor Accused of Bribery, Abuse of Power                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                        , Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank                                                                                                                                                                                                                                                                                      , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                                              , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                                                      , Mark Zuckerberg Shares AI Products to Reassure Workers of Strategy                                                                                                                                                                                                                                                                                    , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                                         , Italy Will Keep Blocking EU Bailout Fund Approval, Meloni Says                                                                                                                                                                                                                                                                                        , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                           , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                            , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                                           , How to Re-Create European Styles of Grilling                                                                                                                                                                                                                                                                                                          , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                  , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                                                     , The Consumer Spending Mystery Is Really No Mystery                                                                                                                                                                                                                                                                                                    , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                    , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                 , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                         , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                      , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                       , NY Skies Start Clearing as Rain in Sight: Smoky Air Latest                                                                                                                                                                                                                                                                                            , Climate Change and Homeowners’ Insurance Are on a Collision Course                                                                                                                                                                                                                                                                                    , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                        , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                      , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                              , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                    , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                      , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                                                       , Ray Ndlovu                                                                                                                                                                                                                                                                                                                                            , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                    , Subscribe                                                                                                                                                                                                                                                                                                                                             , Share prices are rising so rapidly on Zimbabwe’s main stock exchange that the bourse is increasing the maximum move allowed in a single day.                                                                                                                                                                                                          , A new daily limit of a 15% move in the all-share index — up from 10% — will be implemented from Monday, Justin Bgoni, chief executive officer of the Zimbabwe Stock Exchange in Harare, said by phone Friday. Circuit breakers halted trading on the bourse on three consecutive days this week. “It’s in response to the recent activity,” he said.   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 18:27:04 </td>
   <td style="text-align:left;"> Indian Shares Pare Weekly Gains on Friday </td>
   <td style="text-align:left;"> The BSE Sensex closed 235 points lower at 62,615 on Friday, trimming gains from earlier sessions to notch a broadly flat end to the week as tightening measures for key monetary authorities pressured equity markets. Despite holding rates yesterday, the RBI emphasized that borrowing costs must remain restrictive enough to prevent upside risks to inflation, paring hopes that the central bank could cut rates by the third quarter. Tech shares led the losses for the final session of the week, with Infosys and Mahindra &amp; Mahindra both dropping 1.2% while TCS shares decreased 0.6%. Public sector banks also declined, led by a 1.3% retreat for the State Bank of India. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cyprus/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 18:21:57 </td>
   <td style="text-align:left;"> Cyprus Trade Gap Widens Slightly in April </td>
   <td style="text-align:left;"> The trade deficit in Cyprus widened slightly year-on-year to EUR 570.1 million in April 2023 from EUR 560 million in the corresponding month of the previous year, a preliminary estimate showed. Imports rose by 4 percent to EUR 872.1 million, as purchases were up by 11 percent from the non-EU countries, while inched up by 0.01 percent from EU countries. Meanwhile, exports surged by 8.3 percent to EUR 302.1 million, as sales jumped to non-EU countries 16 percent whereas the ones to EU countries shrank 10.1 percent. From January to April, the trade shortfall expanded to EUR 3.112 million from EUR 2.178 million in the same period of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/iron-ore </td>
   <td style="text-align:left;"> 2023-06-09 18:15:09 </td>
   <td style="text-align:left;"> Iron Ore Rises to 7-Week High </td>
   <td style="text-align:left;"> Prices for iron ore cargoes with a 63.5% iron ore content for delivery in Tianjin jumped past $110 per tonne in June, its highest in seven weeks and extending its rebound from the six-month low of $98.5 touched on May 25th amid expectations of improved demand. Although recent data stretched evidence that China’s economic recovery continues to underwhelm expectations, trade figures from May showed that iron ore imports rose by 4.5% annually, raising hopes of higher purchasing activity from steel producers. Market players continued to bet that the government will soon announce stimulus measures to support the country’s essential property sector and construction activity, shortly after the PBoC chose to inject CNY 2 billion of liquidity into banks. On the other hand, supply remained ample amid strong output for key producers Australia and Brazil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/greece/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 18:10:00 </td>
   <td style="text-align:left;"> Greek Industrial Output Growth Picks Up in April </td>
   <td style="text-align:left;"> Industrial production in Greece surged by 4.2% year-on-year in April 2023, following a revised 0.1% increase in the prior month. It marks the 4th consecutive month of growth in industrial activity and at a solid pace, mainly boosted by electricity supply (9.9% vs -28.5% in March) and mining &amp; quarrying (9.2% vs 22.7%), and, to a lesser extent, manufacturing (3.2% vs 8%). On the other hand, output decreased for water supply (-1.7% vs 2.5%). On a seasonally adjusted monthly basis, industrial activity shrank by 1.9% in April, after a revised flat reading in the previous month. Considering the first four months of the year, industrial production advanced by 2.4% over a year ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/japan-watchdog-seeks-penalty-on-regional-banks-over-bond-sales </td>
   <td style="text-align:left;"> 2023-06-09 18:00:21 </td>
   <td style="text-align:left;"> Japan Watchdog Seeks Penalty On Regional Banks Over Bond Sales </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                                        , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                      , Bloomberg Quicktake explores the world of technology and the people who power it. From innovative gadgets to ground-breaking science, dive into the advancements changing our daily lives and the business that drives it.                                                                                                                     , UBS Chief Ermotti Sees ‘Bumpy’ Months Ahead as Deal Close Nears                                                                                                                                                                                                                                                                                , Ex-Barclays CEO Jes Staley Set to Appear for Epstein Deposition                                                                                                                                                                                                                                                                                , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                               , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                                    , Ex-PBOC Deputy Governor Accused of Bribery, Abuse of Power                                                                                                                                                                                                                                                                                     , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                 , Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank                                                                                                                                                                                                                                                                               , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                                       , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                                               , Mark Zuckerberg Shares AI Products to Reassure Workers of Strategy                                                                                                                                                                                                                                                                             , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                                  , Italy Will Keep Blocking EU Bailout Fund Approval, Meloni Says                                                                                                                                                                                                                                                                                 , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                    , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                     , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                                    , How to Re-Create European Styles of Grilling                                                                                                                                                                                                                                                                                                   , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                           , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                                              , The Consumer Spending Mystery Is Really No Mystery                                                                                                                                                                                                                                                                                             , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                             , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                          , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                  , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                               , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                , NY Skies Start Clearing as Rain in Sight: Smoky Air Latest                                                                                                                                                                                                                                                                                     , Climate Change and Homeowners’ Insurance Are on a Collision Course                                                                                                                                                                                                                                                                             , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                 , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                               , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                       , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                             , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                               , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                                                , Fumio Kishida                                                                                                                                                                                                                                                                                                                                  , Photographer: Kimimasa Mayama/EPA/Bloomberg                                                                                                                                                                                                                                                                                                    , Takashi Nakamichi                                                                                                                                                                                                                                                                                                                              , Subscriber Benefit                                                                                                                                                                                                                                                                                                                             , Subscribe                                                                                                                                                                                                                                                                                                                                      , Japan’s securities watchdog is seeking penalties on two regional banks for improperly selling structured bonds, a rare move that could send a signal to the broader industry about its sales practices.                                                                                                                                        , The Securities and Exchange Surveillance Commission on Friday asked the Financial Services Agency to punish Chiba Bank Ltd. and its brokerage subsidiary, as well as Musashino Bank Ltd. The agency said they sold these products without properly checking customers’ investment preference and experience, or explaining the risks involved.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/hsbc-among-uk-banks-pulling-mortgage-deals-from-the-market-again </td>
   <td style="text-align:left;"> 2023-06-09 17:57:04 </td>
   <td style="text-align:left;"> HSBC Among UK Banks Pulling Mortgage Deals From the Market Again </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                           , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                         , Bloomberg Quicktake explores the world of technology and the people who power it. From innovative gadgets to ground-breaking science, dive into the advancements changing our daily lives and the business that drives it.                                                                                                        , UBS Chief Ermotti Sees ‘Bumpy’ Months Ahead as Deal Close Nears                                                                                                                                                                                                                                                                   , Ex-Barclays CEO Jes Staley Set to Appear for Epstein Deposition                                                                                                                                                                                                                                                                   , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                  , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                       , Ex-PBOC Deputy Governor Accused of Bribery, Abuse of Power                                                                                                                                                                                                                                                                        , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                    , Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank                                                                                                                                                                                                                                                                  , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                          , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                                  , Mark Zuckerberg Shares AI Products to Reassure Workers of Strategy                                                                                                                                                                                                                                                                , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                     , Italy Will Keep Blocking EU Bailout Fund Approval, Meloni Says                                                                                                                                                                                                                                                                    , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                       , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                        , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                       , How to Re-Create European Styles of Grilling                                                                                                                                                                                                                                                                                      , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                              , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                                 , The Consumer Spending Mystery Is Really No Mystery                                                                                                                                                                                                                                                                                , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                             , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                     , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                  , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                   , NY Skies Start Clearing as Rain in Sight: Smoky Air Latest                                                                                                                                                                                                                                                                        , Climate Change and Homeowners’ Insurance Are on a Collision Course                                                                                                                                                                                                                                                                , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                    , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                  , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                          , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                  , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                                   , Estate agents boards outside a block of flats in the Slade Green district of Greater London.                                                                                                                                                                                                                                      , Damian Shepherd and                                                                                                                                                                                                                                                                                                               , William Shaw                                                                                                                                                                                                                                                                                                                      , Subscriber Benefit                                                                                                                                                                                                                                                                                                                , Subscribe                                                                                                                                                                                                                                                                                                                         , UK lenders, led by HSBC Holdings Plc, are removing mortgage deals from the market again as they prepare to reprice home loans to account for inflation.                                                                                                                                                                           , Giving only hours’ notice, HSBC told brokers on Thursday that it would remove all its current new business residential and buy-to-let products the same evening. It said the offerings will be back Monday at increased rates. That triggered a surge in demand, prompting the lender to withdraw them before the scheduled time.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/greece/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 17:44:52 </td>
   <td style="text-align:left;"> Greece Inflation Continues Downward Trend </td>
   <td style="text-align:left;"> Greece annual consumer inflation eased for an eighth straight month to 2.8% in May 2023 from 3% in April, marking the lowest reading since September 2021. The cost rose softer for hotels, cafés &amp; restaurants (7.4% vs 8.5% in the previous period) and household equipment (9.9% vs 10.9%). It also declined for housing (-12.9% vs -13.4%), transport (-3.1% vs 1.4%), and communication (-2.3% vs -1.8%). On the other hand, inflation accelerated for food &amp; non-alcoholic beverages (11.6% vs 11.4%); health (7.8% vs 6.5%); miscellaneous goods &amp; services (6.8% vs 6.4%); and clothing &amp; footwear (11.8% vs 5.6%). On a monthly basis, consumer prices grew by 0.4%, slowing from a 0.6% gain in April. Additionally, harmonized inflation rate decelerated to a 1-1/2 year low of 4.1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/amd-gets-chance-to-show-ai-roadmap-after-87-rally-tech-watch </td>
   <td style="text-align:left;"> 2023-06-09 17:39:32 </td>
   <td style="text-align:left;"> AMD Tracks Nvidia Gains in Wall Street’s AI Frenzy </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                  , Bloomberg Quicktake explores the world of technology and the people who power it. From innovative gadgets to ground-breaking science, dive into the advancements changing our daily lives and the business that drives it.                                                                                                                                                                 , UBS Chief Ermotti Sees ‘Bumpy’ Months Ahead as Deal Close Nears                                                                                                                                                                                                                                                                                                                            , Ex-Barclays CEO Jes Staley Set to Appear for Epstein Deposition                                                                                                                                                                                                                                                                                                                            , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                           , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                                                                                , Ex-PBOC Deputy Governor Accused of Bribery, Abuse of Power                                                                                                                                                                                                                                                                                                                                 , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                             , Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank                                                                                                                                                                                                                                                                                                                           , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                                                                                   , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                                                                                           , Mark Zuckerberg Shares AI Products to Reassure Workers of Strategy                                                                                                                                                                                                                                                                                                                         , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                                                                              , Italy Will Keep Blocking EU Bailout Fund Approval, Meloni Says                                                                                                                                                                                                                                                                                                                             , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                 , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                                                                                , How to Re-Create European Styles of Grilling                                                                                                                                                                                                                                                                                                                                               , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                       , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                                                                                          , The Consumer Spending Mystery Is Really No Mystery                                                                                                                                                                                                                                                                                                                                         , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                         , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                      , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                              , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                           , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                            , NY Skies Start Clearing as Rain in Sight: Smoky Air Latest                                                                                                                                                                                                                                                                                                                                 , Climate Change and Homeowners’ Insurance Are on a Collision Course                                                                                                                                                                                                                                                                                                                         , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                             , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                           , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                   , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                         , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                           , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                                                                                            , AMD will introduce new data center chips next week.                                                                                                                                                                                                                                                                                                                                        , Ian King and                                                                                                                                                                                                                                                                                                                                                                               , Subrat Patnaik                                                                                                                                                                                                                                                                                                                                                                             , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                         , Subscribe                                                                                                                                                                                                                                                                                                                                                                                  , Advanced Micro Devices Inc.’s stellar share-price performance this year reflects its place in the eyes of investors looking to make an artificial intelligence trade: the best backup plan.                                                                                                                                                                                                , The stock’s 87% surge would make it the top performer on the Philadelphia Stock Exchange Semiconductor Index if it wasn’t for the stratospheric gain of rival Nvidia Corp. Nvidia briefly became the first chipmaker to have a trillion-dollar market value after delivering concrete evidence that the rush to develop new AI services is translating into a surge in orders for hardware. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/japan-sushi-chain-sues-teen-480-000-for-soy-sauce-licking-prank </td>
   <td style="text-align:left;"> 2023-06-09 17:37:18 </td>
   <td style="text-align:left;"> Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                  , Bloomberg Quicktake explores the world of technology and the people who power it. From innovative gadgets to ground-breaking science, dive into the advancements changing our daily lives and the business that drives it.                                 , UBS Chief Ermotti Sees ‘Bumpy’ Months Ahead as Deal Close Nears                                                                                                                                                                                            , Ex-Barclays CEO Jes Staley Set to Appear for Epstein Deposition                                                                                                                                                                                            , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                           , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                , Ex-PBOC Deputy Governor Accused of Bribery, Abuse of Power                                                                                                                                                                                                 , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                             , Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank                                                                                                                                                                                           , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                   , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                           , Mark Zuckerberg Shares AI Products to Reassure Workers of Strategy                                                                                                                                                                                         , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                              , Italy Will Keep Blocking EU Bailout Fund Approval, Meloni Says                                                                                                                                                                                             , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                 , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                , How to Re-Create European Styles of Grilling                                                                                                                                                                                                               , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                       , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                          , The Consumer Spending Mystery Is Really No Mystery                                                                                                                                                                                                         , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                         , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                      , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                              , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                           , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                            , NY Skies Start Clearing as Rain in Sight: Smoky Air Latest                                                                                                                                                                                                 , Climate Change and Homeowners’ Insurance Are on a Collision Course                                                                                                                                                                                         , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                             , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                           , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                   , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                         , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                           , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                            , Grace Huang                                                                                                                                                                                                                                                , Subscriber Benefit                                                                                                                                                                                                                                         , Subscribe                                                                                                                                                                                                                                                  , A sushi restaurant chain is suing a customer for ¥67 million ($480,000), saying that a viral online video of the teen licking communal bottles and plates caused a drop in sales, foot traffic and the company’s shares, according to Japanese media.      , Food &amp; Life Cos., which owns Akindo Sushiro, the outlet where the incident occurred, had filed a police report and received an apology from the perpetrator. In the clip, he also touched the sushi as it rolled past with fingers he had put in his mouth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/uk-shares-a-bargain-especially-value-stocks-says-rob-arnott-transcript </td>
   <td style="text-align:left;"> 2023-06-09 17:34:04 </td>
   <td style="text-align:left;"> Transcript: Why UK Value Stocks Are Still the Trade of the Decade </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                              , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                            , Bloomberg Quicktake explores the world of technology and the people who power it. From innovative gadgets to ground-breaking science, dive into the advancements changing our daily lives and the business that drives it.                                                                                                           , UBS Chief Ermotti Sees ‘Bumpy’ Months Ahead as Deal Close Nears                                                                                                                                                                                                                                                                      , Ex-Barclays CEO Jes Staley Set to Appear for Epstein Deposition                                                                                                                                                                                                                                                                      , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                     , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                          , Ex-PBOC Deputy Governor Accused of Bribery, Abuse of Power                                                                                                                                                                                                                                                                           , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                       , Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank                                                                                                                                                                                                                                                                     , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                             , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                                     , Mark Zuckerberg Shares AI Products to Reassure Workers of Strategy                                                                                                                                                                                                                                                                   , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                        , Italy Will Keep Blocking EU Bailout Fund Approval, Meloni Says                                                                                                                                                                                                                                                                       , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                           , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                          , How to Re-Create European Styles of Grilling                                                                                                                                                                                                                                                                                         , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                 , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                                    , The Consumer Spending Mystery Is Really No Mystery                                                                                                                                                                                                                                                                                   , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                      , NY Skies Start Clearing as Rain in Sight: Smoky Air Latest                                                                                                                                                                                                                                                                           , Climate Change and Homeowners’ Insurance Are on a Collision Course                                                                                                                                                                                                                                                                   , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                             , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                     , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                                      , Read the conversation between Research Affiliates founder Rob Arnott and Merryn Talks Money host Merryn Somerset Webb.                                                                                                                                                                                                               , Rob Arnott                                                                                                                                                                                                                                                                                                                           , Sommer Saadi and                                                                                                                                                                                                                                                                                                                     , Merryn Somerset Webb                                                                                                                                                                                                                                                                                                                 , Subscriber Benefit                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                            , In this week’s episode of  Merryn Talks Money, Bloomberg Opinion writer Merryn Somerset Webb interviews famed contrarian investor Rob Arnott, co-founder of Research Affiliates. He has said since the autumn of 2020 that UK shares are a great bargain — in particular so-called value stocks.  He contends that’s still the case. , Here is a lightly edited transcript of the conversation. Listen in full below, learn more about the podcast here, and subscribe on Apple and  Spotify to stay on top of new episodes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malta/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 17:25:25 </td>
   <td style="text-align:left;"> Malta Posts Largest Trade Deficit in 8 Months </td>
   <td style="text-align:left;"> The trade deficit in Malta widened to EUR 480.1 million in April 2023 from EUR 360.4 million in the same month a year earlier. It was the largest trade gap since August 2022, as exports shrank 9.4% year-on-year to EUR 296.6 million, weighed down by lower sales of mineral fuels, lubricants &amp; related materials (-25.4%), semi-manufactured goods (-18.3%), miscellaneous manufactured articles (-9.9%) and machinery &amp; transport equipment (-0.3%). On the other hand, imports climbed 12.9% to EUR 776.6 million, mainly driven by purchases of semi-manufactured goods (33.7%). Considering the four months of the year, the country’s trade deficit increased to EUR 1,174 million from EUR 979.3 million in the corresponding period of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malta/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 17:19:00 </td>
   <td style="text-align:left;"> Malta Industrial Output Up 14.3% in April </td>
   <td style="text-align:left;"> Industrial production in Malta rose 14.3 percent year-on-year in April 2023, following an upwardly revised 13.2 percent growth in the previous month. Output increased sharply for energy (31.9 percent vs 2.7 percent in March), while it slowed for capital goods (4.2 percent vs 7.9 percent) and consumer goods (20.3 percent vs 27.4 percent), In contrast, production dropped for intermediate goods (-0.3 percent vs 0.9 percent). On a seasonally adjusted monthly basis, industrial output fell 2.5 percent, after a 1.3 percent rise in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/total-vehicle-sales </td>
   <td style="text-align:left;"> 2023-06-09 17:15:24 </td>
   <td style="text-align:left;"> China Vehicle Sales Continue to Rise </td>
   <td style="text-align:left;"> Vehicle sales in China increased 27.9% year-on-year to 2.382 million units in May of 2023, following an 82.7% surge in the previous month, according to data from the China Association of Automobile Manufacturers (CAAM). Sales of new energy vehicles jumped 60.2%. Considering the first four months of the year, total car sales rose 11.1% to 10.62 million units and those of new energy vehicles jumped 46.8%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 17:11:15 </td>
   <td style="text-align:left;"> Russian Stocks Advance on Friday </td>
   <td style="text-align:left;"> The ruble-based MOEX Russia index hovered above the flatline at the 2,715 mark on Friday, extending gains from the previous session with support from banks and oil companies ahead of the Central Bank of Russia’s interest rate decision. While the central bank is expected to hold interest rates unchanged, previous hawkish rhetoric from Governor Nabiullina raised small bets of a potential hike or signals of future rate increases. Banking giant Sberbank hovered flat ahead of its release of May corporate results, while shares in the rest of the sector booked sharp gains on the back of strong results from VTB posted earlier in the week. In the meantime, gains for oil companies were led by a 4.5% surge for preferred Surgut stocks following the announcement of strong 2022 results. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 17:03:00 </td>
   <td style="text-align:left;"> Spain Stocks Struggle for Direction </td>
   <td style="text-align:left;"> The IBEX 35 stayed muted at 9,350 on Friday amid prevailing cautiousness ahead of next week's central banks meetings. The top performers in the index were Laboratorios Farma (1.1%) and Melia Hotels (1%). Additionally, traders kept an eye on Inditex (0.8%), which announced joining forces with Jeanologia to recover microfibers in the production of textile garments, and Iberdrola (0.2%) after the company sealed the largest green ammonia framework contract in Europe with Trammo. On the side of losses, Ferrovial dropped the most (-1%). Grifols also surprised with a fall of 0.5% despite signing an agreement with Canadian Plasma Resources to obtain their donated plasma. The index was on track to end week 0.5% higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/china-s-central-bank-governor-reiterates-stable-policy-stance </td>
   <td style="text-align:left;"> 2023-06-09 17:02:56 </td>
   <td style="text-align:left;"> China’s Central Bank Governor Reiterates Stable Policy Stance </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                       , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                     , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.                                                                                                                    , UBS Chief Ermotti Sees ‘Bumpy’ Months Ahead as Deal Close Nears                                                                                                                                                                                                                                                               , Ex-Barclays CEO Jes Staley Set to Appear for Epstein Deposition                                                                                                                                                                                                                                                               , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                              , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                   , Ex-PBOC Deputy Governor Accused of Bribery, Abuse of Power                                                                                                                                                                                                                                                                    , Rising UK Rates Open £9 Billion Hole in Tory and Labour Plans                                                                                                                                                                                                                                                                 , Elliott-Backed Lender Bantry Bay Dares to Take on Distressed UK Retailers                                                                                                                                                                                                                                                     , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                      , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                              , Mark Zuckerberg Shares AI Products to Reassure Workers of Strategy                                                                                                                                                                                                                                                            , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                 , Italy Will Keep Blocking EU Bailout Fund Approval, Meloni Says                                                                                                                                                                                                                                                                , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                   , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                    , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                   , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                         , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                          , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                             , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                            , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                         , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                 , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                              , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                               , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                           , NY Skies Start Clearing as Rain in Sight: Smoky Air Latest                                                                                                                                                                                                                                                                    , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                              , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                      , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                            , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                              , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                               , Yi Gang on June 8.                                                                                                                                                                                                                                                                                                            , Subscriber Benefit                                                                                                                                                                                                                                                                                                            , Subscribe                                                                                                                                                                                                                                                                                                                     , China’s central bank will keep monetary policy targeted and ensure credit growth is stable, Governor Yi Gang said, keeping the policy stance largely unchanged despite rising calls for more stimulus.                                                                                                                        , Speaking to businesses and banks in Shanghai, Yi said he has confidence the official growth target of around 5% can be achieved this year. Inflation is expected to gradually rebound in the second half of the year, he added. The speech was earlier this week and posted on the People’s Bank of China’s website on Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/economy/wedding-engagement-rings-economy.html </td>
   <td style="text-align:left;"> 2023-06-09 17:00:25 </td>
   <td style="text-align:left;"> How Engagement Rings Explain What’s Happening in the Economy - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , A major jeweler claims the pandemic may have prevented people from meeting their future fiancés, cutting demand for engagement rings. Inflation and anxiety among shoppers haven’t helped.                                                                                                                                                                                                                                                                                                                             , By Jeanna Smialek and Jason Karaian                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Aftershocks from the coronavirus pandemic continue to rumble across the U.S. economy, and Signet Jewelers shared a surprising one this week: The company is selling fewer engagement rings this year because, it says, singles who were stuck at home during lockdowns failed to meet their would-be fiancés in 2020.                                                                                                                                                                                                  , “As we predicted, there were fewer engagements in the quarter resulting from Covid’s disruption of dating three years ago,” Virginia C. Drosos, the chief executive at Signet, which owns Kay Jewelers and Zales, told investors on Thursday. Shares of Signet, the largest jewelry retailer in the United States, tumbled after the company cut its forecasts for sales and profit for the rest of the year.                                                                                                          , In a way, the engagement ring has become a sparkly microcosm of the American economy. The bridal jewelry business is being buffeted by the delayed effects of the pandemic, rapid inflation that is squeezing consumers and a growing sense of nervousness among shoppers.                                                                                                                                                                                                                                             , Some of the volatility is owed purely to the pandemic. Weddings were canceled in droves during 2020 lockdowns, but bounced back starting in late 2021 and throughout 2022, and were expected to level off over the coming years as more typical patterns returned. Wedding-related activity does appear to show some early signs of slowing in 2023, but it is unclear whether that’s the result of a 2020 dating dry spell, per Signet, or simply a return to the longstanding shift toward later and fewer marriages., What is clear? Wedding trends are also tied to broader, and potentially longer-lasting, economic forces. Signet may be selling less because fewer people are getting down on one knee, but also because ring shoppers are becoming more cautious and spending less amid rapid inflation and rising uncertainty about the direction of the economy. Both the volume and value of jewelry sold by Signet last quarter declined.                                                                                          , Ms. Drosos said that the company had “expected the low-double-digit decline in engagements that we saw this quarter,” but that other factors were also at play. “Recent consumer confidence, lower tax refunds, economic concerns triggered by regional bank failures and continued inflation led to a weakening trend in spending across the jewelry industry,” she added.                                                                                                                                            , Consumers are contending with big challenges this year. Prices have climbed about 15 percent cumulatively over the past three years, as measured by the Personal Consumption Expenditures index. Inflation has slowed in recent months, but many workers are finding that their wages are falling behind.                                                                                                                                                                                                              , The Federal Reserve has been raising interest rates to try to cool the economy and fight the stubborn price increases. Besides making it more expensive for consumers to shop on credit or take out loans, the rate moves have increased the chance that the economy might tip into a recession. That uncertainty has been compounded by recent turmoil in the banking industry.                                                                                                                                       , As many households watch their savings dwindle and worry about their job security in a weakening economy, they may be less willing to spend a lot on big-ticket items like fancy diamond rings and bespoke wedding dresses.                                                                                                                                                                                                                                                                                            , David’s Bridal, the wedding dress retailer, suggested in a bankruptcy filing this year that some brides had become increasingly budget-conscious.                                                                                                                                                                                                                                                                                                                                                                      , An “increasing number of brides are opting for less-traditional wedding attire, including thrift wedding dresses,” James Marcum, the company’s chief executive, said in a court filing.                                                                                                                                                                                                                                                                                                                                , Like much of the economy, the wedding industry has shown signs of a split, as higher earners find that they are able to reach into their savings and keep spending, and lower-income families that spend a bigger share of their earnings on necessities like food begin to crack under the weight of inflation.                                                                                                                                                                                                       , LVMH, the luxury retail group that owns jewelers including Tiffany, reported continued growth in early 2023, including solid growth in jewelry.                                                                                                                                                                                                                                                                                                                                                                        , “Everybody was expecting 2023 to be a horrendous year for luxury in the U.S.,” Jean-Jacques Guiony, LVMH’s chief financial officer, told investors in April, explaining that a collapse had not materialized. “It’s normalizing, but it’s not bad, either.”                                                                                                                                                                                                                                                            , But at more mass-market brands like Kay Jewelers and Zales, shoppers may be starting to pull back.                                                                                                                                                                                                                                                                                                                                                                                                                     , “We began to see softening at higher price points, which previously had been relatively insulated, and lower price points remained under pressure,” Joan Hilson, Signet’s finance chief, said during Thursday’s call.                                                                                                                                                                                                                                                                                                  , Signet is hoping wedding-ring demand will bounce back: It is predicting 500,000 more engagements in the United States from 2024 to 2026 than the prepandemic trend would suggest, as dating delayed by the lockdowns leads to matches.                                                                                                                                                                                                                                                                                 , But Shane McMurray, founder of the Wedding Report, is skeptical of a big gap year in engagements. He expects weddings to fall 20 percent in 2023 from 2022 levels as trends return to normal. And Lyman Stone, director of research at the consulting firm Demographic Intelligence, agreed that the current slowdown in weddings might reflect a return to previous trends rather than a one-off weakening.                                                                                                           , “It does look like 2023 is going to be a low year,” he said. “I do think that placing the blame for that on lockdowns in 2020 is a little bit strained.”                                                                                                                                                                                                                                                                                                                                                               , Jeanna Smialek writes about the Federal Reserve and the economy for The Times. She previously covered economics at Bloomberg News.   @jeannasmialek                                                                                                                                                                                                                                                                                                                                                                    , Jason Karaian is the business news director, based in London. He was previously the editor of DealBook.  @jkaraian                                                                                                                                                                                                                                                                                                                                                                                                     , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/china-bank-deposit-rate-cuts.html </td>
   <td style="text-align:left;"> 2023-06-09 17:00:23 </td>
   <td style="text-align:left;"> China’s Biggest Banks Cut Deposit Rates to Spur Consumer Spending - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , By Daisuke Wakabayashi                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Reporting from Seoul                                                                                                                                                                                                                                                                                                                                                                                                                                                           , In the latest attempt to boost consumer spending, China’s largest state-run banks lowered interest rates on deposits this week. The rate cuts, the second such reductions since last year, reflect a growing concern that the world’s second-largest economy has not rebounded as strongly as expected after lifting its restrictive “zero-Covid” measures.                                                                                                                    , Six commercial banks all announced that they had lowered the rate for demand deposits, essentially a checking account, to 0.2 percent from 0.25 percent. The banks cut the interest rates on deposits covering a fixed period of time.                                                                                                                                                                                                                                         , The Industrial and Commercial Bank of China, the country’s biggest lender by assets, cut the five-year deposit rate to 2.5 percent from 2.65 percent and lowered the three-year rate to 2.45 percent from 2.6 percent, according to the bank’s website.                                                                                                                                                                                                                        , A reduction in the deposit rates is one lever that policymakers can use to stimulate spending. The hope is that the lower rates will give consumers an incentive to spend or invest money instead of parking their savings in the bank.                                                                                                                                                                                                                                        , The move is an indication that consumer spending, a key driver of economic growth, remains sluggish. After China scrapped its Covid restrictions late last year and reopened the economy, there were expectations that pent-up demand would push consumers to start spending freely — but that has not played out in many sectors of the economy.                                                                                                                              , Larry Hu, chief China economist at the finance firm Macquarie Group, said the change in deposit rates “paves the way for more easing measures.” He added that the People’s Bank of China, the country’s central bank, may lower the benchmark lending rate or take other steps to stimulate the economy in the coming months. Lowering how much banks pay out on deposits can offset some of the financial pressure when China’s central bank lowers the lending rate, he said., China has predicted that its economy will recover from one of the slowest years of growth in decades last year and that gross domestic product will grow at around 5 percent in 2023. But economic weakness continues to persist.                                                                                                                                                                                                                                              , In the first three months of the year, China’s economy grew at 4.5 percent, helped by a pickup in spending on dining out and luxury goods. But the outlook appears less promising. China’s second-quarter gross domestic product figures are expected to be announced next month.                                                                                                                                                                                              , The youth unemployment rate is at a record high. The real estate market, a critical sector of the economy for investment and job creation, continues to slump with little sign of a recovery on the horizon.                                                                                                                                                                                                                                                                   , Betty Rui Wang, senior China economist at the Australia-based bank ANZ, said confidence in the economy is weak across Chinese households and private-sector businesses. She said post-Covid demand helped to push the economy in the early part of the year, but there have been signs that May was a turning point.                                                                                                                                                           , “It’s losing momentum,” said Ms. Wang.                                                                                                                                                                                                                                                                                                                                                                                                                                         , Many economists and analysts are expecting a host of new stimulus measures to be announced after next month’s meeting of the Politburo, the Chinese Communist Party’s top decision-making body.                                                                                                                                                                                                                                                                                , Some new efforts are already rolling out. The Ministry of Commerce said on Thursday that it was starting a campaign to spur more automobile sales. Spending on cars, especially electric vehicles, had been a bright spot in recent years, helped by government subsidies and tax breaks. But as Beijing has rolled back some of those measures, car sales have slowed.                                                                                                        , The ministry said it would support policies to bolster the sale of new cars. It said, for example, that it would expand electric-vehicle charging infrastructure in rural areas to make it more practical to bring the technology to the countryside.                                                                                                                                                                                                                          , Li You contributed research.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Daisuke Wakabayashi is an Asia business correspondent for The Times, based in Seoul.  @daiwaka                                                                                                                                                                                                                                                                                                                                                                                 , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 16:56:23 </td>
   <td style="text-align:left;"> Stocks in France Flat on Friday </td>
   <td style="text-align:left;"> The CAC 40 index traded along the flatline at 7,215 on Friday, tracking a general cautious mood, as markets focus on policy meetings from the US Federal Reserve and the European Central Bank next week. Among single stocks, Dassault Systèmes (-2.4%) posted the biggest losses, despite saying it expects a doubling of its EPS by 2028, and announcing a new CEO. On the flip side, Teleperformance (+2.6%) and Unibail-Rodamco-We (+2%) were leading the gains. China-exposed luxury stocks such as Hermes (+0.1%) and LVMH (+0.2%) were also slightly higher, as the sharp decline in producer prices in China raised bets the authorities will unleave measures to support the economy. On the week, the CAC 40 is on track to lose nearly 0.8%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovenia/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 16:49:51 </td>
   <td style="text-align:left;"> Slovenia Industrial Output Lowest in 4 Months </td>
   <td style="text-align:left;"> Industrial production in Slovenia declined 8.8 percent year-on-year in April of 2023, following an upwardly revised 4.8 percent decrease in the previous month. It was the lowest reading since December 2022, as output dropped further for manufacturing (-7.3 percent vs -1.1 percent in March). Meanwhile, production fell at a slower pace for electricity, gas, steam &amp; air conditioning supply (-20.6 percent vs -37.9 percent) and mining and quarrying (-29.5 percent vs -34 percent). On a seasonally adjusted monthly basis, industrial output shrank 7.9 percent, reversing an upwardly revised 2.5 percent growth in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/tech-stocks-see-outflows-for-first-time-in-8-weeks-bofa-says </td>
   <td style="text-align:left;"> 2023-06-09 16:49:04 </td>
   <td style="text-align:left;"> Tech Stocks See Outflows for First Time in 8 Weeks, BofA Says </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                   , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                 , Bloomberg Quicktake explores the world of technology and the people who power it. From innovative gadgets to ground-breaking science, dive into the advancements changing our daily lives and the business that drives it., UBS Chief Ermotti Sees ‘Bumpy’ Months Ahead as Deal Close Nears                                                                                                                                                           , Ex-Barclays CEO Jes Staley Set to Appear for Epstein Deposition                                                                                                                                                           , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                          , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                               , Ex-PBOC Deputy Governor Accused of Bribery, Abuse of Power                                                                                                                                                                , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                            , Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank                                                                                                                                                          , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                  , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                          , Mark Zuckerberg Shares AI Products to Reassure Workers of Strategy                                                                                                                                                        , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                             , Italy Will Keep Blocking EU Bailout Fund Approval, Meloni Says                                                                                                                                                            , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                               , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                               , How to Re-Create European Styles of Grilling                                                                                                                                                                              , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                      , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                         , The Consumer Spending Mystery Is Really No Mystery                                                                                                                                                                        , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                        , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                     , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                             , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                          , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                           , NY Skies Start Clearing as Rain in Sight: Smoky Air Latest                                                                                                                                                                , Climate Change and Homeowners’ Insurance Are on a Collision Course                                                                                                                                                        , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                            , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                          , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                  , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                        , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                          , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                           , Michael Msika                                                                                                                                                                                                             , Subscriber Benefit                                                                                                                                                                                                        , Subscribe                                                                                                                                                                                                                 , The AI frenzy that has driven massive inflows into tech stocks is marking a pause, Bank of America Corp. says.                                                                                                            , Tech funds sustained $1.2 billion of outflows in the week through June 7, their first in eight weeks, according to the bank, citing EPFR Global data. The move occurred after the group had record inflows last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 16:38:00 </td>
   <td style="text-align:left;"> Hang Seng Books 2.3% Gains Weekly </td>
   <td style="text-align:left;"> Equities in Hong Kong rose 90.77 points or 0.47% to end at two-week peaks of 19,389.95 on Friday, shifting from losses in morning trade, lifted by strong wins from tech and consumers. The Hang Seng also advanced for the third day and posted a 2.3% jump weekly, with investors being upbeat amid growing calls for China's central bank to cut interest rates as a recovery in the economy weakened. May's inflation data showed that the Chinese economy cooled further, while recent reports indicated that factory activity shrank, exports plunged, and a rebound in the housing market faded. A drop in US stock futures limited the gains, however, as worries mounted that the Federal Reserve could stay hawkish in its monetary policy meeting next week following tightening moves from several central banks this week. Among top performers were ESR Group (5.9%), Chow Tai Fook Jewellery (3.9%), H World Group (3.5%),  Wuxi Biologics (3.1%), Meituan (2.8%), and Innovent Biologics (2.7%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 16:35:00 </td>
   <td style="text-align:left;"> South African Stocks Slightly Up </td>
   <td style="text-align:left;"> The JSE FTSE All Share index was slightly up around 77,170 on Friday, its highest in over a week, mainly driven by heavyweight tech Naspers and Prosus, industrials and financials. Meanwhile, global investors keep a cautious stance ahead of the U.S. inflation release for May due next week, and the outcome of the Fed's two-day rate decision meeting, starting Tuesday. On the domestic front, the head of the presidency's project management office stated the energy crisis in South Africa should begin abating toward the end of the year, as repairs to Eskom’s two newest power stations Medupi and Kusile and the completion of maintenance at its Koeberg nuclear plant will be prioritized. The JSE was set to close the week almost flat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/currency </td>
   <td style="text-align:left;"> 2023-06-09 16:33:00 </td>
   <td style="text-align:left;"> Turkish Lira Weakens to Fresh Record Low </td>
   <td style="text-align:left;"> The Turkish lira continued to weaken to a new record low of 23.5 per USD, extending the monthly loss to 13%, and bringing the total depreciation to about 18% since the runoff election on May 28th. Following the appointment of Mehmet Simsek, a former deputy prime minister known for his market-friendly policies, as the new finance minister, President Tayyip Erdogan appointed Hafize Gaye Erkan, formerly a co-CEO at First Republic Bank and a managing director at Goldman Sachs, as the head of Turkey's central bank. These moves were seen as a strong signal of a shift from unorthodox economic policies that had led to high inflation, low interest rates, a plummeting lira, and negative net foreign exchange reserves. Meanwhile, annual inflation rate has eased for the seventh consecutive month to 39.6% in May, mainly due to the government's move to provide unlimited free natural gas for all households for a year but it is still far from the central bank's target rate of 22.3% for 2023. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/retail-sales-annual </td>
   <td style="text-align:left;"> 2023-06-09 16:24:00 </td>
   <td style="text-align:left;"> Bulgaria Retail Sales Shrink the Most in Near 3 Years </td>
   <td style="text-align:left;"> Retail sales in Bulgaria contracted 2 percent year-on-year in April 2023, following a 1.1 percent rise in the previous month. It marked the first decline since July 2022 and the steepest since July 2020, as trade of non-food products decreased (-4.1 percent vs 0.9 percent in March), particularly computers, peripheral units, software and telecommunication equipment. At the same time, sales of food products stalled (vs 1.7%). On a seasonally adjusted monthly basis, retail trade shrank 2 percent, the largest fall since April 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/industrial-production-mom </td>
   <td style="text-align:left;"> 2023-06-09 16:24:00 </td>
   <td style="text-align:left;"> Italy Industrial Production Contracts for 4th Month </td>
   <td style="text-align:left;"> Industrial production in Italy sank by 1.9% from a month earlier in April of 2023, the fourth consecutive monthly contraction and the sharpest since September 2022, missing market forecasts of a 0.1% expansion to underscore that the industrial sector is under heavy pressure from higher borrowing costs set by the ECB. Output contracted for intermediate goods (-2.6% vs -0.4% in March), capital goods (-2.1% vs 0.7%), consumer goods (-0.4% vs -1.5%), and energy (-0.3% vs -1.7%). On a yearly basis, industrial production plummeted by 7.2%, the most since July 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 16:12:22 </td>
   <td style="text-align:left;"> Bulgaria Industrial Output Falls the Most Since 2020 </td>
   <td style="text-align:left;"> Industrial output in Bulgaria slumped 12.6% year-on-year in April 2023, the fourth consecutive month of decline in industrial activity, and from 9% fall in the previous month. It was the steepest contraction since May 2020, as output for manufacturing (-8.2% vs -0.9% in March) continued to fall sharply. Meanwhile, output declined at softer pace for mining &amp; quarrying (-10.5% vs -14.3%) and electricity, gas, steam &amp; air-conditioning supply (-38.7% vs -39.3%). On a monthly basis, industrial production went down to 2.9% in April, from a 1.2% drop in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/construction-output </td>
   <td style="text-align:left;"> 2023-06-09 16:09:00 </td>
   <td style="text-align:left;"> Bulgaria Construction Output Falls in April </td>
   <td style="text-align:left;"> Construction output in Bulgaria decreased by 2.3 percent year-on-year in April of 2023, reversing a 0.3 percent rise in the prior month, as both building construction (-0.5 percent vs 2.4 percent in March) and civil engineering (-4.7 percent vs -2.5 percent) declined. On a seasonally adjusted monthly basis, construction output was down by 1 percent, following a 0.4 percent gain in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 16:07:00 </td>
   <td style="text-align:left;"> Italian Stocks Almost Flat </td>
   <td style="text-align:left;"> The FTSE MIB index traded near the flatline around 27,300 on Friday, in line with its regional peers, as investors continued to assess the outlook for the global economy and interest rates ahead of key central bank meetings from the Fed and the ECB next week. Regarding the domestic economy, latest data showed Italy's industrial activity fell further in April and by more than analysts had anticipated. On the corporate front, Telecom Italia (+1.3%) was in focus as the US fund Kkr and the rival consortium formed by Cassa Depositi e Prestiti and the Australian fund Macquarie are set to present their respective improved offers for the network in view of today's deadline. Erg (+1.1%) and Leonardo (+1%) also advanced firmly, while Moncler (-1.1%), Inwit (-1%) and Interpump Group (-0.9%) posted the biggest losses. For the week, the FTSE MIB was on track to book a nearly 1% gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palm-oil </td>
   <td style="text-align:left;"> 2023-06-09 16:03:00 </td>
   <td style="text-align:left;"> Palm Oil Futures Move Higher </td>
   <td style="text-align:left;"> Malaysian palm oil futures were trading near MYR 3,400 per tonne after falling to around MYR 3,260 earlier in the week, supported by strong demand from China and  India. China reportedly increased its purchases of tropical oil in May, as it tried to replenish its stockpiles ahead of the peak consumption season. For the week, however, the contract was on course for a second weekly drop, with signs of rising production and inventories growing. Investors now await Malaysian Palm Oil Board data due Monday to study the extent of a rise in May production. Reuters projected that the country’s palm oil production jumped 21% to 1.45 metric tons last month, the highest level since last December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/09/ubs-and-the-swiss-governmen-sign-loss-protection-agreement-over-credit-suisse-takeover.html </td>
   <td style="text-align:left;"> 2023-06-09 15:58:42 </td>
   <td style="text-align:left;"> UBS and the Swiss government sign loss protection agreement over Credit Suisse takeover </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Banking                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Taxes                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                                                                , Investing                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                               , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                                                                                                                                                         , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Banking                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Find the Savings Account for You                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                             , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                , Best CDs                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Credit Unions                                                                                                                                                                                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                                   , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Affording a Mortgage                                                                                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Life Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Renters Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Car Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Travel Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                                                                                                                                            , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                                            , Credit Repair Services                                                                                                                                                                                                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                                                                                                                                                , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Debt Relief                                                                                                                                                                                                                                                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Small Business Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Taxes                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Tax Software                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                                                                                                                                                    , Tax Refunds                                                                                                                                                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                              , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                                                                                                                                                   , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                                                                                                                                                     , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                                                              , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Hardship Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                                            , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Investing                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Investing Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Index Funds                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Mutual Funds                                                                                                                                                                                                                                                                                                                                                                                                                                                              , ETFs                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Bonds                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                           , UBS and the Swiss government announced Friday that they had signed a loss protection agreement, which will come into effect once the takeover of Credit Suisse is completed.                                                                                                                                                                                                                                                                                              , The provisions will see the Swiss government cover losses of up to 9 billion Swiss francs ($10 billion) following UBS' acquisition of its former rival. This is guaranteed on a "designated portfolio of Credit Suisse non-core assets," once UBS incurs the first 5 billion Swiss francs in losses.                                                                                                                                                                      , "The priority for the federal government and UBS is to minimise potential losses and risks so that recourse to the federal guarantee is avoided to the greatest extent possible," the Swiss government said in a statement.                                                                                                                                                                                                                                               , The administration added that it had facilitated the deal to "safeguard financial stability and thus avert damage to the Swiss economy," but had always agreed to guarantee a portion of losses due to UBS taking over a portfolio of assets that "do not fit its business and risk profile."                                                                                                                                                                             , In return, the agreement states that, after the takeover, UBS must support the development of Switzerland's status as a financial centre. The bank has confirmed intentions to keep the headquarters of the merged group in Switzerland for the duration of the loss protection provisions.                                                                                                                                                                               , "UBS will manage these assets in a prudent and diligent manner and intends to minimize any losses and maximize value realization on these assets," UBS said.                                                                                                                                                                                                                                                                                                              , UBS Group shares were down 0.2% at 10:00 a.m. London time.                                                                                                                                                                                                                                                                                                                                                                                                                , Last month, the bank disclosed it anticipated a financial hit of around $17 billion as a result of acquiring its rival, in what has been described in some quarters as a "shotgun wedding" to stabilize the Swiss financial system.                                                                                                                                                                                                                                       , The Swiss banking rivals agreed a $3.2 billion takeover deal at the start of spring, at a time of broader volatility in the banking sector that led to the collapse of three U.S. banks. Credit Suisse shares cratered through early March, with years of scandals, losses and alleged mismanagement coming to a head when its largest shareholder, the Saudi National Bank, said it was not able to provide any more cash to the bank because of regulatory restrictions., The merger of the two banking juggernauts has been greeted with some controversy, enraging Credit Suisse shareholders and bondholders as well as raising competition concerns.                                                                                                                                                                                                                                                                                            , The bank expects the Credit Suisse acquisition to complete as early as June 12.                                                                                                                                                                                                                                                                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                          , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 15:45:00 </td>
   <td style="text-align:left;"> British Shares Hover Marginally Lower on Friday </td>
   <td style="text-align:left;"> The FTSE 100 hovered slightly below the flatline at the 7,590 level on Friday, also set to notch slight losses on the week as markets continued to assess the outlook on the economy ahead of incoming interest rate hikes. Energy shares booked losses after the British government announced that the current Energy Profits Levy on oil giants will remain until 2028, while a floor was set on the windfall tax. Both BP and Shell hovered around 0.5% lower. In the meantime, chemicals company Croda sank 12% after issuing a profit warning. On the other hand, miners edged higher with a 0.5% gain for Rio Tinto and Glencore despite the muted session for bullion prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 15:40:14 </td>
   <td style="text-align:left;"> The Shangai Composite Index rose 0.55% </td>
   <td style="text-align:left;"> In China the Shangai Composite Index rose 18 points or 0.55 percent on Friday. Leading the gains are Sh Pharmaceutical (3.65%), Sdic Power (2.50%) and BAIC BluePark (2.44%). Top losers were Poly Real Estate (-4.43%), Sanan Optoelectron (-4.41%) and China CITIC Bank (-3.80%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 15:39:00 </td>
   <td style="text-align:left;"> European Shares Subdued to End the Week </td>
   <td style="text-align:left;"> The DAX lost nearly 0.4% and the pan-European STOXX 600 traded around the flatline on Friday, as investors continue to assess the global economic outlook while awaiting key monetary policy decisions from the Fed and the ECB next week. There are no major economic releases today, so in the absence of further catalysts, trading is likely to remain lacklustre. Shares of chemicals were the worst performers, falling nearly 1.3% after earnings from Croda International disappointed, while tech and utilities were up nearly 0.2%. On the week, the DAX is down about 0.7% and the STOXX 600 lost nearly 0.4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/moldova/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 15:28:09 </td>
   <td style="text-align:left;"> Moldova Inflation Slows for 7th Month </td>
   <td style="text-align:left;"> The annual inflation rate in Moldova dropped to a nearly one-and-a-half-year low of 16.3 percent in May 2023 from 18.3 percent in April, easing for the seventh month, as costs slowed for food products (14 percent vs 16.4 percent in the previous period) and non-food products (8.2 percent vs 10.6 percent ). Meanwhile, services inflation was little changed (33.3 percent vs 33.2 percent). Monthly, consumer prices increased 0.5 percent, following a 2.2 percent jump in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovakia/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 15:24:58 </td>
   <td style="text-align:left;"> Slovakia Trade Balance Swings to Surplus in April </td>
   <td style="text-align:left;"> Slovakia recorded a trade surplus of EUR 292.9 million in April 2023, compared to a deficit of EUR 516.4 million in the corresponding month of the previous year, preliminary estimates showed. Year-on-year, exports increased 7.4% to EUR 8,419 million, largely due to higher sales of machinery and transport equipment (25.9%), in particular motor vehicles and aircraft. Meanwhile, imports declined for the first time in over two years by 2.7% to EUR 8,126.1 million, as purchases dropped for mineral fuels (-45.5%), which includes oil, electricity and natural gas. The majority of goods from both of these sections were destined for EU markets. Considering the January-April period, the country posted a trade surplus of EUR 1,072 million, shifting from a deficit of EUR 1,657.5 million in the same period a year ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 15:24:00 </td>
   <td style="text-align:left;"> Turkey Industrial Output Unexpectedly Drops in April </td>
   <td style="text-align:left;"> Turkey’s industrial production unexpectedly fell by 1.2% year-on-year in April 2023, missing market forecasts of 1.2% gain, and shifting from an upwardly revised 0.4% growth in the previous month. Production continued to decline for mining &amp; quarrying (-12.2% vs -10.4% in March) and electricity, gas, steam &amp; air conditioning supply (-4.3% vs -7.8%). Meanwhile, output in manufacturing activities showed no growth (0% vs 1.9%). On a seasonally adjusted monthly basis, industrial output slumped 0.9%, reversing a downwardly revised 5.8% gain in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/austria/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 15:15:27 </td>
   <td style="text-align:left;"> Austria Industrial Output Accelerates in April </td>
   <td style="text-align:left;"> Industrial production in Austria advanced 1% year-on-year in April 2023, accelerating from an upwardly revised 0.1% rise in the previous month, due to the strong rebound in production of energy (5.5% vs -10% in March). On the other hand, output eased for capital goods (6.7% vs 6.8%), consumer durables (2.7% vs 10.2%) and non-durables (3.2% vs 7.8%), while it fell further for intermediate goods (-4.5% vs -4.2%). On a seasonally adjusted monthly basis, industrial production rose 0.9%, recovering from a 3.4% drop in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovakia/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 15:15:17 </td>
   <td style="text-align:left;"> Slovak Industrial Output Slips in April </td>
   <td style="text-align:left;"> Industrial production in Slovakia shrank 2% year-on-year in April 2023, following a 2.5% rise in the previous month. Output declined for manufacturing (-1.2% vs 3.3% in March), dragged down by the manufacture of textiles, apparel, leather &amp; related products (-10.6% vs 2.6%), manufacture of coke &amp; refined petroleum products (-11.1% vs 20.4%), and other manufacturing and repair &amp; installation of machinery &amp; equipment (-0.3% vs 4.6%). Meanwhile, output rebounded for manufacture of machinery &amp; equipment n.e.c (0.6% vs -1.1%), while increased sharply for manufacture of pharmaceuticals, medicinal chemical &amp; botanical products (43.3% vs 10.9%). On a seasonally adjusted monthly basis, industrial activity tumbled 1.2% in April, from 1.7% gain in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/prime-monster-energy-drinks-caffeine.html </td>
   <td style="text-align:left;"> 2023-06-09 15:00:21 </td>
   <td style="text-align:left;"> Energy Drinks Are Surging. So Are Their Caffeine Levels. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , More companies are pushing low-calorie, sugar-free beverages they say are healthy. Some servings have nearly the same level of caffeine as a six-pack of Coca-Cola.                                                                                                                                                                                                                                                                                                                                                                                                     , By Julie Creswell                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , It has been more than 25 years since Red Bull hit the market and introduced caffeinated energy drinks to the United States. While the company claimed its beverage would “give you wings,” it never said it was actually good for people.                                                                                                                                                                                                                                                                                                                               , Yet as the energy drink market continues to grow rapidly, companies both new and old are trying to attract health-conscious customers with a wave of no-sugar, low-calorie drinks that claim to boost energy as well as replenish fluids with electrolytes and other ingredients.                                                                                                                                                                                                                                                                                       , The offerings include drinks from the popular brand Celsius, which has an investment from PepsiCo and uses the marketing line “Celsius Live Fit.” It claims to be made with “healthier ingredients” like ginger, green tea and vitamins. Likewise, the influencer-backed Prime Energy is sugar-free and has electrolytes, a main ingredient in most sports drinks.                                                                                                                                                                                                      , “All of them are zero sugar or zero calories,” said Jim Watson, a beverage analyst at Rabobank, a bank based in the Netherlands with a focus on food and agriculture. He added that energy drink consumption had increased partly because of the decades-long move away from sugary soda. “They’re going for the healthy image.”                                                                                                                                                                                                                                        , Even Gatorade, which has long marketed beverages to athletes hoping to replenish lost fluids or electrolytes after strenuous exercise, is jumping into the caffeine arms race. This year, Gatorade released Fast Twitch, a sugar-free beverage in flavors like Strawberry Watermelon and Cool Blue — with caffeine levels equivalent to more than two cups of coffee.                                                                                                                                                                                                   , This new focus has helped the energy drink market grow, with sales in the United States surging to $19 billion from $12 billion over the past five years, according to Circana, a market research firm.                                                                                                                                                                                                                                                                                                                                                                 , Last year, PepsiCo paid $550 million for an 8.5 percent stake in Celsius. In May, Celsius said revenues were $260 million in the first quarter of this year, double what they were a year earlier. At that ferocious pace, revenues could cross $1 billion this year, increasing from $314 million just two years ago. Shares of Celsius have shot up to $144 a share from $69 a year ago. Likewise, the stock of the beverage company Monster Energy has increased 31 percent in the past year.                                                                        , But there are concerns that drinks being pitched as healthy are resulting in children and teenagers consuming caffeine in unhealthy amounts.                                                                                                                                                                                                                                                                                                                                                                                                                            , In March, neon-colored Prime Energy cans began appearing in a lunchroom filled with fourth and fifth graders in the Wilmington public school district in Massachusetts. The popular drinks were released in January by the social media stars Logan Paul and Olajide Olayinka Williams Olatunji, better known as KSI.                                                                                                                                                                                                                                                   , For some young students, the Prime Energy drinks, which come in flavors like Strawberry Watermelon and Orange Mango, were delicious liquid gold.                                                                                                                                                                                                                                                                                                                                                                                                                        , “We even had entrepreneurs in fourth and fifth grade who were bringing them to school and selling them to other kids at lunch,” said Rebecca Brown, the health services coordinator for the district.                                                                                                                                                                                                                                                                                                                                                                   , But the eye-popping cans pack a serious punch. A 12-ounce can of Prime Energy contains 200 milligrams of caffeine. That’s roughly equivalent to two Red Bulls, two cups of coffee or six cans of Coca-Cola.                                                                                                                                                                                                                                                                                                                                                             , Some schools in Britain and Australia have already banned the beverages. In the United States, federal regulations say schools cannot sell or provide caffeinated drinks to elementary or middle school students, although many schools do not restrict what students can bring from home.                                                                                                                                                                                                                                                                              , “Not long after drinking them, the students showed up in the health office saying they didn’t feel good and that their hearts were racing,” said Ms. Brown, who inserted a note in the school’s weekly email to parents saying the energy drinks should not be brought to school.                                                                                                                                                                                                                                                                                       , A 12-ounce can of Red Bull contains about 114 milligrams of caffeine — more than three times the amount in a 12-ounce can of Coca-Cola. Prime Energy has more: 200 milligrams in each 12-ounce can. A 16-ounce can of Bang Energy Drink, the size typically sold in convenience stores, has 300 milligrams of caffeine.                                                                                                                                                                                                                                                 , In an email response to questions, representatives for Mr. Paul, the social media personality, and Prime Energy noted that the company’s cans labeled the drink as “not recommended for children under 18.” But parents and school officials are sometimes confusing the drink with Prime Hydration, a caffeine-free sports drink from the social media stars that is sold in bottles. That drink is also immensely popular, with more than $250 million in sales in its first year and customers waiting in line for hours to buy it at some grocery stores in Britain., “Everybody thought Red Bull was the peak of caffeine in energy drinks,” said Dr. Ryan Stanton, an emergency physician in Lexington, Ky., who said he saw patients, especially around finals weeks at local colleges, come in complaining about feeling anxious and experiencing racing heartbeats after consuming too much caffeine. “Now, some of these drinks have two or three times the level of caffeine as Red Bull.”                                                                                                                                             , Studies have shown that consuming caffeine may have health benefits, but that too much could result in cardiovascular and gastric issues. The Food and Drug Administration has investigated a handful of reports over the years involving people dying shortly after consuming energy drinks or five-hour energy shots. But the agency has never established a link between the two, a spokesman for the F.D.A. said in a response to emailed questions.                                                                                                                , Adults are recommended to have no more than 400 milligrams of caffeine per day. Pediatricians recommend that youths ages 12 to 18 should not consume more than 100 milligrams of caffeine per day and that children under 12 should avoid caffeine completely.                                                                                                                                                                                                                                                                                                          , Over the years, there have been efforts to increase government regulation of energy drinks and limit the caffeine allowed in beverages. Lawmakers in several states, including Indiana and Connecticut, have considered banning the sale of energy drinks to minors. But the industry has successfully pushed back, in part by arguing that young people can get caffeine from myriad sources, including soda and coffee. A 16-ounce cinnamon-caramel-cream cold brew from Starbucks, for instance, contains 265 milligrams of caffeine (not to mention 260 calories).  , About a decade ago, the energy drink industry, through its lobbying arm, the American Beverage Association, voluntarily adopted a set of principles, including labeling the amount of caffeine in products and noting on packaging that the beverages were not recommended for children. The industry also agreed not to sell or market its products in schools.                                                                                                                                                                                                        , But critics say some energy drinks are clearly marketed toward younger customers. Last year, the consumer advocacy group Truth in Advertising said companies like C4 Energy, which sells drinks in flavors like Starburst and Skittles, and Ghost Energy, which sells Sour Patch Kids and Swedish Fish-flavored drinks that contain more caffeine than two cups of coffee, were trying to appeal to minors.                                                                                                                                                             , Dan Lourenco, the chief executive and co-founder of Ghost, said in an email that the company’s products were geared toward millennials seeking the nostalgic flavors of their youth. C4 Energy, which is owned by Nutrabolt, did not respond to an email seeking comment.                                                                                                                                                                                                                                                                                               , The U.S. Department of Agriculture, whose Smart Snacks program creates the nutritional standards for foods and beverages sold in schools, said any products sold in elementary and middle schools must be caffeine-free. But for beverages sold in high schools, there are restrictions on the number of calories but none on the level of caffeine.                                                                                                                                                                                                                    , Moreover, the F.D.A. does not have specific regulations around “energy drinks,” deeming it a marketing term. A spokesman for the agency added in an email that companies were still responsible for including a safe amount of caffeine in beverages.                                                                                                                                                                                                                                                                                                                   , Chloe Fitzgibbon, 17, who graduated in May from Lincoln Southeast High School in Lincoln, Neb., questioned whether the school cafeteria should be selling energy drinks in an article published last year on the website of the school’s newspaper, The Clarion. Noting that the school sold Mountain Dew’s version, Kickstart, Ms. Fitzgibbon said students opted for the drink not only for the energy jolt but for the ease of buying it through their student accounts.                                                                                             , The high school cafeteria sells a number of caffeinated beverages, including Kickstart, which has 68 milligrams of caffeine in a 12-ounce can, and Bubbl’r, a sparkling water with 69 milligrams of caffeine in a 12-ounce can. Mindy Burbach, a spokeswoman for Lincoln Public Schools, said in an email that students were limited to buying two caffeinated beverages each day.                                                                                                                                                                                      , “When I took an early-morning class, A.P. Psych, almost everyone came in with a coffee or they would buy the energy drinks that we sell at school,” Ms. Fitzgibbon said.                                                                                                                                                                                                                                                                                                                                                                                                , Pasco County Schools, a Florida district just north of Tampa, also offers Kickstart drinks to high school students in its vending machines. But Stephen Hegarty, a spokesman for the district, noted that PepsiCo, which owns the brand, marketed the beverage as an “enhanced soft drink,” not an “energy drink.” PepsiCo declined to comment.                                                                                                                                                                                                                         , “If you go to any of our high schools, you’ll see students walking in with Starbucks, and some of those drinks have a lot of caffeine,” Mr. Hegarty said. “I’m not sure what the definition of an energy drink is these days.”                                                                                                                                                                                                                                                                                                                                          , Julie Creswell is a New York-based reporter. She has covered banks, private equity, retail and health care. She previously worked for Fortune Magazine and also wrote about debt, monetary policy and mutual funds at Dow Jones.  @julie_creswell                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/tanzania/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 14:51:00 </td>
   <td style="text-align:left;"> Tanzania Inflation Rate Eases to 1-Year Low </td>
   <td style="text-align:left;"> Tanzania's annual inflation rate eased to 4% in May 2023,  the lowest in a year, from 4.3% rise in the previous month. Food inflation surged at the softest pace in 8 months (8.5% vs 9.1% in April). There was also a slowdown in prices of transport (1.3% vs 4.3%) and furnishings &amp; household equipment (2.9% vs 3.1%). On the other hand, inflation accelerated for housing &amp; utilities (0.8% vs 0.3%), clothing &amp; footwear (3.3% vs 2.8%) and recreation, sport &amp; culture (1.9% vs 1.8%). The core rate, which excludes volatile items such as unprocessed food and energy, stood at 2% in May, unchanged from the previous month. On a monthly basis, consumer prices advanced by 0.2%, after rising by 0.4% in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/lithuania/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 14:47:00 </td>
   <td style="text-align:left;"> Lithuania Posts Smallest Trade Gap in 15 Months </td>
   <td style="text-align:left;"> Lithuania's trade deficit fell to EUR 0.31 billion in April 2023 from EUR 0.83 billion in the same month a year earlier. It was the smallest trade gap since January 2022, as exports decreased less than imports. Imports plunged 16% from a year earlier to EUR 3.61 billion, dragged down by lower purchases of mineral fuels, mineral oils and products of their distillation (-41.3%), iron and steel (-55.4%) and organic chemicals (-40.3%). At the same time, exports dropped 5.1% to EUR 3.29 billion, amid declines in sales of mineral fuels, mineral oils and products of their distillation (-32.7%), wood and wood products (-31.9%) and furniture (-18.2%). Considering the first four months of the year, the country's trade deficit narrowed to EUR 1.73 billion from EUR 2.32 billion in the corresponding period of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 14:42:00 </td>
   <td style="text-align:left;"> New Zealand Stocks End Week on Downbeat Note </td>
   <td style="text-align:left;"> New Zealand's shares lost 25.4 points or 0.22% to close at 11,690.34 on Friday after trading slightly higher in early trade, declining for the fifth day in a row while sliding 1.6% for the week, rattled by a drop in US stock futures amid speculation of the Federal Reserve keeping interest rates higher for longer. Meantime, inflation data from China, New Zealand's main trading partner, provided fresh signs that the economy cooled further in May. Traders also took a cautious stance ahead of New Zealand's Q1 GDP readings that will be due next week. Several economists forecast that the domestic economy had already been in recession, while local media said that the GDP print was probably a bit flat after contracting by 0.6% in Q4 of 2022 as efforts to rebuild activity from severe weather events continue. Among the biggest laggards were Delegat Group Ltd. (-3.2%), Fisher &amp; Paykel Healthcare (-2.2%), A2 Milk Co. (-1.6%), PGG Wrightson Ltd. (-1.5%), and Briscoe Group (-1.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 14:30:09 </td>
   <td style="text-align:left;"> The Nikkei 225 Index went up by 1.93% </td>
   <td style="text-align:left;"> In Tokyo the Nikkei 225 Index gained 610 points or 1.93 percent on Friday. Gains were led by Konami (5.66%), Fast Retailing (4.77%) and Marubeni (4.52%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/household-spending-mom </td>
   <td style="text-align:left;"> 2023-06-09 14:27:07 </td>
   <td style="text-align:left;"> Sweden Household Spending Rebounds </td>
   <td style="text-align:left;"> Household Spending in Sweden jumped 1.2% month-over-month in April of 2023, the biggest increase since March of 2022, following a downwardly revised 0.2% decline in the previous month. Compare to a year earlier, household consumption stalled, with retail trade, mostly food and beverages accounting for the largest weighted negative contribution (-6.1%)- On the other hand, retail sales of motor vehicles increased 2.7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/romania/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 14:25:20 </td>
   <td style="text-align:left;"> Romania Trade Gap Narrows </td>
   <td style="text-align:left;"> Romania’s trade deficit decreased to EUR 2.06 billion in April 2023 from EUR 2.84 billion in the same month a year earlier. Exports grew by 4.9% from a year earlier to EUR 7.23 billion, as shipments rose both to EU countries (2.5%) and non-EU countries (11.6%). Meantime, imports fell 4.5% to EUR9.29 billion, amid lower purchases mainly from non-EU countries (-15.1%). Considering the first four months of the year, the trade gap narrowed to EUR 8.86 billion from EUR 10.04 billion in the corresponding period of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/lithuania/producer-prices-change </td>
   <td style="text-align:left;"> 2023-06-09 14:25:00 </td>
   <td style="text-align:left;"> Lithuania Producer Prices Drop for 2nd Month </td>
   <td style="text-align:left;"> Producer prices in Lithuania shrank 5.6% year-on-year in May 2023, extending the revised 0.2% drop in the prior month. It was the second consecutive month of deflation and the lowest reading since January 2021, due to lower cost in manufacturing (-8.8% vs -3.7% in April), particularly coke and refined petroleum products (-29.4% vs -16.4%). Additionally, prices eased for mining and quarrying (8.3% vs 13%), electricity, gas, steam &amp; air-conditioning supply (34.5% vs 45.8%), and water supply, sewerage, waste management &amp; remediation activities (24.7% vs 24.9%). On a monthly basis, producer prices fell by 2.3%, following a revised 2.5% decline in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/new-orders </td>
   <td style="text-align:left;"> 2023-06-09 14:24:49 </td>
   <td style="text-align:left;"> Swedish New Orders Drop 0.1% YoY in April </td>
   <td style="text-align:left;"> Total orders received by Swedish industries fell 0.1 percent year-on-year in April of 2023, following a downwardly revised 8 percent drop in the previous month. Orders from customers in Sweden declined (-4.7 percent vs 2 percent in March) while those from abroad rebounded (2.4 percent vs -14.9 percent). On a seasonally adjusted monthly basis, new orders surged 3 percent, reversing a 0.4 percent decline in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 14:24:00 </td>
   <td style="text-align:left;"> European Markets Set to Open Slightly Higher </td>
   <td style="text-align:left;"> European equity markets were set to open slightly higher on Friday, tracking gains among global peers as US Treasury yields fell after a surge in new unemployment claims in the US reinforced expectations that the Federal Reserve would hold interest rates steady next week. The European Central Bank is also set to decide on monetary policy next week. Meanwhile, investors remain cautious as the IMF urged major central banks to “stay the course” on monetary policy and watch inflation closely. There are no major data and earnings releases on Friday. DAX, Stoxx 600 and FTSE 100 futures drifted flat to slightly positive in premarket trade. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/monthly-gdp-mom </td>
   <td style="text-align:left;"> 2023-06-09 14:17:02 </td>
   <td style="text-align:left;"> Swedish Economy Stalls in April </td>
   <td style="text-align:left;"> The Swedish economy flattened between April and March 2023, after falling 0.1% in the previous period. There were limited changes in several big aggregates. Compared to a year earlier, the GDP was 0.1% lower. April 2023 had one less working day than April 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/norway/producer-prices-change </td>
   <td style="text-align:left;"> 2023-06-09 14:16:06 </td>
   <td style="text-align:left;"> Norway Producer Prices Lowest on Record </td>
   <td style="text-align:left;"> Producer prices in Norway shrank 23.5% year-on-year in May 2023, the fifth consecutive month of decline, and compared with 15.3% fall in the previous month. It was also marked as the lowest reading since records began in 2001, as prices continued to contract for energy goods (-37.8% vs -37.5%). At the same time, prices for electricity, gas &amp; steam declined (-9.2% vs 3.1%), while slowed for manufacturing (3% vs 10.4%). On a monthly basis, producer prices fell sharply to 8.3%, shifting from a 0.8% growth in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/norway/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 14:16:00 </td>
   <td style="text-align:left;"> Norway Inflation Rate Rises to 6.7% in May </td>
   <td style="text-align:left;"> The annual inflation rate in Norway increased to 6.7% in May 2023 from 6.4% in the previous month and above market forecasts of 6.2%. Prices accelerated mainly for food &amp; non-alcoholic beverages (12.7% vs 10.5% in April), housing &amp; utilities (5% vs 4%), clothing &amp; footwear (3.4% vs 2.5%) and alcoholic beverages &amp; tobacco (6% vs 5.2%). On the other hand, inflation primarily slowed for transport (7.5% vs 7.9%), furnishings, household equipment &amp; maintenance (7.1% vs 10.9%) and recreation &amp; culture (7.3% vs 8.2%). Meanwhile, the CPI adjusted for tax changes and excluding energy products, advanced by 6.7% year-on-year, the highest reading since comparable records began in 2003. On a monthly basis, consumer prices rose 0.5%, slowing from a 1.1% jump in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/current-account </td>
   <td style="text-align:left;"> 2023-06-09 14:12:45 </td>
   <td style="text-align:left;"> Danish Current Account Surplus Largest in 8 Months </td>
   <td style="text-align:left;"> Denmark's current account surplus increased to DKK 35.6 billion in April 2023 in seasonally adjusted terms from DKK 33.0 billion in the prior month. It was the largest amount since last August, as the surplus of goods accounts rose to DKK 19.4 billion from DKK 17.6 billion in March and that of services account ticked higher to DKK 6.8 billion from DKK 6.5 billion. Also, the secondary income deficit fell to DKK 1.3 billion from DKK 2.2 billion in March. Meantime, the surplus of primary income surplus edged lower to DKK 10.7 billion from DKK 11.2 billion, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-09 14:11:00 </td>
   <td style="text-align:left;"> China 10-Year Bond Yield Hits 30-week Low </td>
   <td style="text-align:left;"> The yield on the 10-year Chinese government bond has been decreasing since the beginning of the year and fell below 2.7% in June, the lowest in eight months, as concerns mount regarding a sluggish recovery and a weakened outlook for the Chinese economy. Fresh data showed producer prices fell the most since 2016 and inflation rose less than expected, exports sank and imports were also lower while the official manufacturing PMI pointed to a second straight month of contraction in factory activity. These discouraging figures have heightened expectations that Chinese authorities will introduce additional stimulus measures to support the economy, potentially including a reduction in the reserve requirement ratio for banks. Yet, China's biggest banks recently lowered interest rates on a range of deposit products for both yuans and dollars. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 14:11:00 </td>
   <td style="text-align:left;"> Swedish Industrial Output Growth Accelerates in April </td>
   <td style="text-align:left;"> Industrial production in Sweden rose by 3.4% year-on-year in April of 2023, following an upwardly revised 0.6% growth in March. The biggest upward contribution came from the motor vehicle industry (25.5%) while the largest downward contribution came from the pulp and paper industry (-20.4%). On a seasonally adjusted monthly basis, industrial production surged by 1.8%, reversing a 2.8% drop in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 14:05:00 </td>
   <td style="text-align:left;"> Danish Trade Surplus Largest in 3 Months </td>
   <td style="text-align:left;"> Denmark’s goods and services trade surplus increased to a seasonally adjusted DKK 26.2 billion in April 2023 from a downwardly revised DKK 24.1 billion in the prior month, pointing to the largest trade surplus since January as exports dropped less than imports. Exports fell by 1.2 percent from a month earlier to DKK 154.7 billion, due to a decline in the export of services, while imports shrank by 3.1 percent to DKK 128.5 billion. For the first four months of the year, the country's trade surplus widened to DKK 100 billion from DKK 88.5 billion in the corresponding period of the previous year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 13:52:00 </td>
   <td style="text-align:left;"> India Shares Set to Close Week Slightly Higher </td>
   <td style="text-align:left;"> The BSE Sensex dropped 104.7 points or 0.1% to 62,765.3 in morning trade on Friday, down for the second session in a row, amid caution after several major central banks hiked interest rates this week. Market participants also anticipated US inflation data for May, which could provide clues for the Fed's next step next week. Meantime, the annual inflation is expected to ease to a 20-month low of 4.42% in May, staying within the RBI's 2%-6% target range for the second straight month and raising hopes that the RBI will continue to hold the interest rate for the third consecutive meeting. Tech stocks, consumer goods, and metals were mainly lower, amid falls from Hindustan Unilever (-1.7%), Tata Steel (-148%), and Infosys (-1.3%). Still, the index for the week is heading for a  0.3% rise, supported by robust foreign fund inflows, a flourishing service sector, and a narrowing current account deficit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/binance-us-trading-halt.html </td>
   <td style="text-align:left;"> 2023-06-09 13:44:43 </td>
   <td style="text-align:left;"> Binance Halts Trading in Dollars on Binance.US - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                         , Banks have signaled that they will stop working with the company’s American branch, it said, after the Securities and Exchange Commission sued it this week.                                                                                                                                                                                                                                                         , By David Yaffe-Bellany                                                                                                                                                                                                                                                                                                                                                                                               , Reporting from San Francisco                                                                                                                                                                                                                                                                                                                                                                                         , The American branch of Binance, the giant cryptocurrency exchange, said late on Thursday that it would no longer allow customers to trade on its platform using U.S. dollars, after its banking partners cut the firm off in response to a crackdown by federal regulators.                                                                                                                                          , The move is a major blow to Binance.US, the American arm of the world’s largest crypto exchange. One of the main functions of an exchange is allowing users to convert their traditional money into digital currencies like Bitcoin or Ether. Binance will no longer be able to offer that service in the United States.                                                                                             , In a message to customers, Binance.US said it was “taking necessary actions as we transition to a crypto-only exchange.” In recent days, the company said, its banking partners have signaled that they will no longer facilitate the movement of dollars on and off Binance.US’s platform.                                                                                                                          , The announcement comes after the Securities and Exchange Commission sued Binance on Monday, accusing the firm and its chief executive, Changpeng Zhao, of mishandling customer funds and lying to regulators. In a separate filing, the S.E.C. asked a federal judge in Washington to freeze assets related to U.S.-based customers of Binance, citing “the defendants’ years of violative conduct.”                 , Representatives for Binance did not immediately respond to a request for comment.                                                                                                                                                                                                                                                                                                                                    , The crypto industry has been under intense pressure from federal regulators since November, when the collapse of the FTX exchange set off an industrywide crisis. The day after it sued Binance, the S.E.C. filed a separate case against Coinbase, the largest American crypto exchange. Some crypto companies have vowed to fight the crackdown, while others are making plans to leave the United States entirely., In its message to customers on Thursday, Binance.US said it was facing “extremely aggressive and intimidating tactics” from the S.E.C. The company said it was suspending deposits of U.S. dollars and urged users to withdraw any dollars they have been storing on the exchange by June 13.                                                                                                                        , At the same time, the company tried to assure its customers that their savings were backed up by money it holds in reserve.                                                                                                                                                                                                                                                                                          , “To be clear, we maintain 1:1 reserves for all customer assets,” the message said. “Customer funds are always safe, secure, and available.”                                                                                                                                                                                                                                                                          , David Yaffe-Bellany covers cryptocurrencies and financial technology. He graduated from Yale University and previously reported in Texas, Ohio, Connecticut and Washington, D.C.  @yaffebellany                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/finland/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 13:16:23 </td>
   <td style="text-align:left;"> Finish Industrial Output Shrinks 2.4% in April </td>
   <td style="text-align:left;"> Industrial production in Finland dropped by 2.4 percent year-on-year in April 2023, reversing a downwardly revised 4 percent growth in the previous month, amid declines in the manufacturing (-3.8 percent vs 2.8 percent in March) and mining and quarrying (-6.5% vs -7.6%) sectors. At the same time, output slowed sharply for electricity, gas, steam &amp; air conditioning supply (6.6 percent vs 13.9 percent). On a seasonally adjusted monthly basis, industrial production went down by 1.7 percent, after increasing by 2.8 percent in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/estonia/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 13:15:00 </td>
   <td style="text-align:left;"> Estonian Trade Gap Narrows Sharply in April </td>
   <td style="text-align:left;"> The trade deficit in Estonia fell sharply to EUR 227 million in April 2023 from EUR 532 million in the same month of the previous year, amid a slump in imports. Imports plunged by 18% to EUR 1,754 million, mainly dragged down by declines in mineral products (-42%), transport equipment (-76%), and metal &amp; metal products (-32%). Among major partners, Finland accounted for the biggest share at 15%, followed by Germany (11%), and Latvia (10%). Meanwhile, exports shrank by 4% to EUR 1,527 million, led by mineral products (-25%), wood and articles of wood (-18%), and articles of plastics and rubber (-8%). The highest share of exports went to Finland accounting for 15% of the total, followed by Latvia (13%), and Sweden (9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/netherlands/manufacturing-production-mom </td>
   <td style="text-align:left;"> 2023-06-09 13:06:45 </td>
   <td style="text-align:left;"> Dutch Manufacturing Output Drops 3% in April </td>
   <td style="text-align:left;"> The manufacturing production in the Netherlands shrank 3% month-over-month in April 2023, hitting January’s near two-year low and slipping further from a downwardly revised 1.8% drop in the previous month. Output fell for most industries particularly, food (-2.8% vs 0.6% in March), beverage (-12.2% vs -1.8%), clothing (-7.8% vs -6.2%) and rubber &amp; plastic products (-6.1% vs 1.1%). Production also contracted for building materials (-4% vs -2%), basic metals (-12.1% vs 7.1%), metal products (-1.6% vs -2.8%) and electrical (-3.5% vs -1.5%). On a yearly basis, manufacturing output plunged 12.1%, the largest drop since April 2009. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/09/china-cant-rely-on-southeast-asian-exports-to-offset-a-us-slowdown.html </td>
   <td style="text-align:left;"> 2023-06-09 12:40:33 </td>
   <td style="text-align:left;"> China can't rely on Southeast Asian exports to offset a U.S. slowdown </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                  , Loans                                                                                                                                                                                                                                         , Banking                                                                                                                                                                                                                                       , Mortgages                                                                                                                                                                                                                                     , Insurance                                                                                                                                                                                                                                     , Credit Monitoring                                                                                                                                                                                                                             , Personal Finance                                                                                                                                                                                                                              , Small Business                                                                                                                                                                                                                                , Taxes                                                                                                                                                                                                                                         , Help for Low Credit Scores                                                                                                                                                                                                                    , Investing                                                                                                                                                                                                                                     , SELECT                                                                                                                                                                                                                                        , All Credit Cards                                                                                                                                                                                                                              , Find the Credit Card for You                                                                                                                                                                                                                  , Best Credit Cards                                                                                                                                                                                                                             , Best Rewards Credit Cards                                                                                                                                                                                                                     , Best Travel Credit Cards                                                                                                                                                                                                                      , Best 0% APR Credit Cards                                                                                                                                                                                                                      , Best Balance Transfer Credit Cards                                                                                                                                                                                                            , Best Cash Back Credit Cards                                                                                                                                                                                                                   , Best Credit Card Welcome Bonuses                                                                                                                                                                                                              , Best Credit Cards to Build Credit                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                        , All Loans                                                                                                                                                                                                                                     , Find the Best Personal Loan for You                                                                                                                                                                                                           , Best Personal Loans                                                                                                                                                                                                                           , Best Debt Consolidation Loans                                                                                                                                                                                                                 , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                      , Best Loans with Fast Funding                                                                                                                                                                                                                  , Best Small Personal Loans                                                                                                                                                                                                                     , Best Large Personal Loans                                                                                                                                                                                                                     , Best Personal Loans to Apply Online                                                                                                                                                                                                           , Best Student Loan Refinance                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                        , All Banking                                                                                                                                                                                                                                   , Find the Savings Account for You                                                                                                                                                                                                              , Best High Yield Savings Accounts                                                                                                                                                                                                              , Best Big Bank Savings Accounts                                                                                                                                                                                                                , Best Big Bank Checking Accounts                                                                                                                                                                                                               , Best No Fee Checking Accounts                                                                                                                                                                                                                 , No Overdraft Fee Checking Accounts                                                                                                                                                                                                            , Best Checking Account Bonuses                                                                                                                                                                                                                 , Best Money Market Accounts                                                                                                                                                                                                                    , Best CDs                                                                                                                                                                                                                                      , Best Credit Unions                                                                                                                                                                                                                            , SELECT                                                                                                                                                                                                                                        , All Mortgages                                                                                                                                                                                                                                 , Best Mortgages                                                                                                                                                                                                                                , Best Mortgages for Small Down Payment                                                                                                                                                                                                         , Best Mortgages for No Down Payment                                                                                                                                                                                                            , Best Mortgages with No Origination Fee                                                                                                                                                                                                        , Best Mortgages for Average Credit Score                                                                                                                                                                                                       , Adjustable Rate Mortgages                                                                                                                                                                                                                     , Affording a Mortgage                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                        , All Insurance                                                                                                                                                                                                                                 , Best Life Insurance                                                                                                                                                                                                                           , Best Homeowners Insurance                                                                                                                                                                                                                     , Best Renters Insurance                                                                                                                                                                                                                        , Best Car Insurance                                                                                                                                                                                                                            , Travel Insurance                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                        , All Credit Monitoring                                                                                                                                                                                                                         , Best Credit Monitoring Services                                                                                                                                                                                                               , Best Identity Theft Protection                                                                                                                                                                                                                , How to Boost Your Credit Score                                                                                                                                                                                                                , Credit Repair Services                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                        , All Personal Finance                                                                                                                                                                                                                          , Best Budgeting Apps                                                                                                                                                                                                                           , Best Expense Tracker Apps                                                                                                                                                                                                                     , Best Money Transfer Apps                                                                                                                                                                                                                      , Best Resale Apps and Sites                                                                                                                                                                                                                    , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                 , Best Debt Relief                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                        , All Small Business                                                                                                                                                                                                                            , Best Small Business Savings Accounts                                                                                                                                                                                                          , Best Small Business Checking Accounts                                                                                                                                                                                                         , Best Credit Cards for Small Business                                                                                                                                                                                                          , Best Small Business Loans                                                                                                                                                                                                                     , Best Tax Software for Small Business                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                        , All Taxes                                                                                                                                                                                                                                     , Best Tax Software                                                                                                                                                                                                                             , Best Tax Software for Small Businesses                                                                                                                                                                                                        , Tax Refunds                                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                        , All Help for Low Credit Scores                                                                                                                                                                                                                , Best Credit Cards for Bad Credit                                                                                                                                                                                                              , Best Personal Loans for Bad Credit                                                                                                                                                                                                            , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                  , Personal Loans if You Don't Have Credit                                                                                                                                                                                                       , Best Credit Cards for Building Credit                                                                                                                                                                                                         , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                  , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                  , Best Mortgages for Bad Credit                                                                                                                                                                                                                 , Best Hardship Loans                                                                                                                                                                                                                           , How to Boost Your Credit Score                                                                                                                                                                                                                , SELECT                                                                                                                                                                                                                                        , All Investing                                                                                                                                                                                                                                 , Best IRA Accounts                                                                                                                                                                                                                             , Best Roth IRA Accounts                                                                                                                                                                                                                        , Best Investing Apps                                                                                                                                                                                                                           , Best Free Stock Trading Platforms                                                                                                                                                                                                             , Best Robo-Advisors                                                                                                                                                                                                                            , Index Funds                                                                                                                                                                                                                                   , Mutual Funds                                                                                                                                                                                                                                  , ETFs                                                                                                                                                                                                                                          , Bonds                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                               , BEIJING — China can't easily rely on its neighbors as export markets in a global slowdown, the latest trade data show.                                                                                                                        , Exports to the Association of Southeast Asia Nations have been growing. The 10-member bloc surpassed the European Union during the pandemic to become China's largest trading partner on a regional basis.                                    , Data showed that exports to Southeast Asia fell by 16% in May compared to a year ago, dragging down China's overall exports.                                                                                                                  , Exports to the U.S. — China's largest trading partner on a single-country basis — fell by 18% from a year ago in U.S. dollar terms in May. That's according to official figures accessed through Wind Information.                            , At $42.48 billion, the U.S. exports in May were more than the $41.49 billion China exported to Southeast Asia that month, according to customs data.                                                                                          , Southeast Asia can't fully offset the loss from the U.S. market, said Bruce Pang, chief economist and head of research for Greater China at JLL.                                                                                              , ASEAN is made up of 10 countries: Brunei, Cambodia, Indonesia, Laos, Malaysia, Myanmar, the Philippines, Singapore, Thailand and Vietnam.                                                                                                     , The U.S. is one single market versus a grouping of 10 countries, Pang pointed out, adding that companies can also sell at higher profit margins in the U.S. market.                                                                           , Trade has been a key driver of China's growth, especially during the pandemic.                                                                                                                                                                , Exports still account for about 18% of the economy, although that's well below the roughly 30% share it once had, Tao Wang, head of Asia economics and chief China economist at UBS Investment Bank, told reporters Monday.                   , Slowing global growth, especially in the U.S. and Southeast Asia, doesn't bode well for the outlook on Chinese exports.                                                                                                                       , "We expect China's exports will remain subdued, as we anticipate the US economy to enter recession in H2 while global destocking pressures continue to rise," Lloyd Chan, senior economist at Oxford Economics, said in a note Wednesday.     , Businesses in the U.S. have also been working through high inventory that didn't get sold in the second half of last year due to high inflation.                                                                                              , U.S. GDP is expected to slow from 2.1% in 2022 to 1.6% this year, according to the International Monetary Fund.                                                                                                                               , ASEAN's GDP is set to slow to 4.6% growth this year, down from last year's 5.7% pace, the IMF said in April, when it trimmed its forecast for the region's GDP growth by 0.1 percentage points.                                               , "The sizeable slump in May reaffirms our suspicion that China's monthly export data to some ASEAN economies – particularly Vietnam, Singapore, Malaysia and Thailand — may be somewhat distorted," Nomura economists said in a note Wednesday., "Given the apparent plunge, exports to ASEAN has turned from a major driver to a drag, making a negative contribution of -2.4pp to headline growth in May."                                                                                   , The U.S. and ASEAN each accounted for 15% of China's total exports in May, according to CNBC calculations of Wind Information data.                                                                                                           , On a year-to-date basis, the bloc has a slightly higher share, at 16% of China's exports versus the United States' 14% share, the data showed.                                                                                                , "Looking forward, [China's] exports are likely to shrink further on a high base, the deepening global manufacturing downturn and intensifying trade sanctions from the West," the Nomura analysts said.                                       , The export declines come as U.S.-China relations remain tense, and Beijing has sought to bolster trade with the developing countries in Asia Pacific.                                                                                         , "It's 20-25% more expensive to sell lots of stuff to the US, particularly intermediate goods like machine parts," Jack Zhang, assistant professor of political science at the University of Kansas, told CNBC in an email.                    , "Boosting trade with developing countries has gained urgency with the closing of the US market and the EU-China investment deal falling apart after the Ukraine war," he said.                                                                , This fund puts a spin on emerging markets investing with bets from Nvidia to Chinese spirits                                                                                                                                                  , Morgan Stanley names 2 chip stocks with 'significant upside' as China bans Micron                                                                                                                                                             , Tesla vs. BYD: Here's why one fund manager prefers the Buffett-backed automaker                                                                                                                                                               , The 10-nation bloc — along with Japan, South Korea, Australia and New Zealand — signed a free trade agreement with China in 2020. The Regional Comprehensive Economic Partnership or RCEP is the largest such deal in the world.              , Beijing has said it would also like to join another trade bloc — the Comprehensive and Progressive Agreement for Trans-Pacific Partnership. The U.S. is not part of the CPTPP, while the U.K. announced a deal to join it in March.           , RCEP has boosted China's trade with ASEAN, as has the shift of some labor-intensive manufacturing to the region, Zhang said.                                                                                                                  , Meanwhile, he noted that "China has been ramping up negotiations for China-ASEAN FTA (CAFTA 3.0), it's exploring FTAs with Mercusor in LatAm and the Gulf Cooperation Council (GCC)."                                                         , The Mercusor trade bloc includes Argentina, Brazil, Paraguay, and Uruguay.                                                                                                                                                                    , — CNBC's Clement Tan contributed to this report.                                                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                              , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malaysia/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 12:31:00 </td>
   <td style="text-align:left;"> Malaysia Industrial Output Unexpectedly Drops </td>
   <td style="text-align:left;"> Industrial production in Malaysia unexpectedly fell by 3.3% year-on-year in April 2023, missing market forecasts of 2% gain, and shifting from a 3.2% growth in the previous month. It was also the first month of decline in industrial output since August 2021, dragged down by all of the sub-sectors, namely; manufacturing (-3% vs 4.1% in March), mining &amp; quarrying (-4.9% vs 0.8%), and electricity (-2% vs -0.3%). On a seasonally adjusted monthly basis, industrial output tumbled 5.6% in April, shifting from a downwardly revised 0.01% rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/08/banks-to-cut-off-binance-access-to-us-banking-system-exchange-says.html </td>
   <td style="text-align:left;"> 2023-06-09 12:14:38 </td>
   <td style="text-align:left;"> Banks are cutting off Binance's access to U.S. banking system, exchange says </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                     , Loans                                                                                                                                                                                                                                                                                                                                                                                                                            , Banking                                                                                                                                                                                                                                                                                                                                                                                                                          , Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                        , Insurance                                                                                                                                                                                                                                                                                                                                                                                                                        , Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                , Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                 , Small Business                                                                                                                                                                                                                                                                                                                                                                                                                   , Taxes                                                                                                                                                                                                                                                                                                                                                                                                                            , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                       , Investing                                                                                                                                                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                 , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                                                                                                     , Best Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                        , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                         , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                         , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                                                                                                               , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                      , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                                                                                                                 , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                                                                                                                , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Loans                                                                                                                                                                                                                                                                                                                                                                                                                        , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                                                                                                              , Best Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                              , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                                                                                                    , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                                                                                                         , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                                                                                                     , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                        , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                        , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                                                                                                              , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Banking                                                                                                                                                                                                                                                                                                                                                                                                                      , Find the Savings Account for You                                                                                                                                                                                                                                                                                                                                                                                                 , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                 , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                   , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                  , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                    , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                               , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                                                                                                    , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                                                                                                       , Best CDs                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Credit Unions                                                                                                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                   , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                                                                                                            , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                                                                                                               , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                                                                                                           , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                                                                                                          , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                                                                                                        , Affording a Mortgage                                                                                                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Insurance                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Life Insurance                                                                                                                                                                                                                                                                                                                                                                                                              , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                                                                                                        , Best Renters Insurance                                                                                                                                                                                                                                                                                                                                                                                                           , Best Car Insurance                                                                                                                                                                                                                                                                                                                                                                                                               , Travel Insurance                                                                                                                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                            , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                                                                                                  , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                                                                                                   , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                   , Credit Repair Services                                                                                                                                                                                                                                                                                                                                                                                                           , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                             , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                                                                                                              , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                                                                                                        , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                                                                                                         , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                                                                                                       , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                                                                                                    , Best Debt Relief                                                                                                                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Small Business                                                                                                                                                                                                                                                                                                                                                                                                               , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                             , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                            , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                                                                                                             , Best Small Business Loans                                                                                                                                                                                                                                                                                                                                                                                                        , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Taxes                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Tax Software                                                                                                                                                                                                                                                                                                                                                                                                                , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                                                                                                           , Tax Refunds                                                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                   , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                 , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                               , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                     , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                                                                                                          , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                                                                                                            , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                     , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                     , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                    , Best Hardship Loans                                                                                                                                                                                                                                                                                                                                                                                                              , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Investing                                                                                                                                                                                                                                                                                                                                                                                                                    , Best IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                           , Best Investing Apps                                                                                                                                                                                                                                                                                                                                                                                                              , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                                                                                                                , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                                                                                                               , Index Funds                                                                                                                                                                                                                                                                                                                                                                                                                      , Mutual Funds                                                                                                                                                                                                                                                                                                                                                                                                                     , ETFs                                                                                                                                                                                                                                                                                                                                                                                                                             , Bonds                                                                                                                                                                                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                  , Binance.US customers will no longer be able to use U.S. dollars to buy crypto on the platform as early as June 13, hobbling the exchange's ability to do business in the United States, after both payment and banking partners "signaled their intent to pause USD fiat channels," the exchange said.                                                                                                                           , Binance announced the change late Thursday night on Twitter, and blamed the Securities and Exchange Commission's "unjustified civil claims against our business." The exchange said it had preemptively disabled customers' ability to buy and deposit U.S. dollars.                                                                                                                                                             , Binance's banking transactions are the center of immense scrutiny by the SEC, which filed a civil complaint against the exchange and its founder, Changpeng Zhao, alleging both violated U.S. securities laws.                                                                                                                                                                                                                   , Zhao's influence over and ownership of the U.S. and international arms of Binance — an international network of offshore holding companies the SEC alleges have moved billions of dollars of assets between themselves — prompted the SEC to file an emergency motion for a temporary restraining order. That restraining order would have frozen U.S. dollars from the exchange anyway.                                         , Customers won't lose their money — those who haven't withdrawn their money by the shutdown date could still theoretically convert it to a stablecoin such as tether, then withdraw that and convert it back to dollars elsewhere. But it suggests that Binance's banking partners have decided the exchange is too risky a client to keep on, and that the revelations from the SEC case have grown too significant to ignore.   , The exchange's disclosed U.S. banking partners, which have included Axos Bank, Cross River Bank, and the failed Silvergate, Signature, and Silicon Valley Banks, processed billions of dollars in transactions for the U.S. exchange, according to documents Binance provided to the SEC. Multiple banking partners had already stopped serving Binance, and it wasn't immediately clear which banking partners Binance retained., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                 , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malaysia/unemployment-rate </td>
   <td style="text-align:left;"> 2023-06-09 12:14:00 </td>
   <td style="text-align:left;"> Malaysia Jobless Rate Down to 3.5% in April </td>
   <td style="text-align:left;"> The unemployment rate in Malaysia fell to 3.5 percent in April 2023 from 3.9 percent in the corresponding month of the previous year, and pointing to its lowest level since February 2020. The number of unemployed declined by 9.6 percent from a year earlier to 586.9 thousand, while employment rose by 2.5 percent to 16.25 million. Meantime, the labor force participation rate edged up to 70 percent from 69.4 percent in the same month a year ago. In March, the jobless rate stood at 3.5 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/currency </td>
   <td style="text-align:left;"> 2023-06-09 12:07:00 </td>
   <td style="text-align:left;"> South Korean Won Stays Weak </td>
   <td style="text-align:left;"> South Korean won was trading around 1,295 against USD on Friday, falling below the psychological level of 1,300 while heading for the fourth straight fall weekly, as the government recently flagged annual economic growth of below 1.6% this year, much lower than the 3.1% in 2022. The export-driven country logged a 14th successive trade deficit in May, the longest such sequence since 1997, as shipments tumbled on lower global demand and sluggish sales of semiconductors, while imports remained underpinned by higher food and energy commodities costs. On fresh data, South Korea's current account swung to a deficit of USD 790 million in April 2023 from a gain of USD 130 million in the same month of the prior year, marking the third shortfall so far this year.  The weakness in local currency occurred even as the US dollar softened, amid expectations that the Federal Reserve could pause its tightening campaign next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/currency </td>
   <td style="text-align:left;"> 2023-06-09 12:07:00 </td>
   <td style="text-align:left;"> NZD Set to End Week Slightly Higher </td>
   <td style="text-align:left;"> The Kiwi dollar was changing hand around $0.6088 on Friday, staying not far from its highest level in over two weeks hit in the prior session, as traders digested decisions from several central banks to hike interest rates this week. Both the Reserve Bank of Australia and the Bank of Canada surprised markets with a 25bps interest rate hike, respectively, after pausing in the prior meeting. Market participants also anticipated the release of New Zealand's Q1 GDP growth next week, with local media saying that the figures are probably a bit flat after shrinking by 0.6% in the prior quarter amid efforts to rebuild activity from severe weather events earlier this year. For the week, the NZD is heading for a 0.3% rise, which would be the second consecutive increase, as the US dollar softened further, with investors expecting the Fed to pause its tightening path next week following a slowdown in the service sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/currency </td>
   <td style="text-align:left;"> 2023-06-09 11:16:46 </td>
   <td style="text-align:left;"> Chinese Yuan Slips on Soft Inflation Data </td>
   <td style="text-align:left;"> The offshore yuan fell to around 7.13 per dollar, sliding back toward its lowest levels in six months as softer-than-expected Chinese inflation data pointed to underlying weakness in the country’s economy. China’s consumer price index rose 0.2% year-on-year in May, lower than the 0.3% forecast, while producer deflation continued last month. Latest data also showed that Chinese exports fell more than expected in May, pushing the country’s trade surplus to a three-month low. These figures reinforced speculations that the People’s Bank of China could lower interest rates again to boost the world’s second-largest economy. A lack of direct intervention by the central bank also weighed on the currency, even though some major state-owned lenders sold dollars in the spot market to keep the yuan from further losses. Furthermore, Chinese authorities reportedly asked key state-owned banks to lower dollar deposit interest rates to further bolster the local currency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/indonesia/foreign-exchange-reserves </td>
   <td style="text-align:left;"> 2023-06-09 11:10:27 </td>
   <td style="text-align:left;"> Indonesia Forex Reserves Fall to 5-Month Low </td>
   <td style="text-align:left;"> Foreign exchange reserves in Indonesia dropped to a five-month low of USD 139.3 billion in May 2023 from 144.2 billion in the previous month. The decline was linked to payment of the government's external debt and in anticipation of demand for foreign currency liquidity in the banking industry as economic activity continued to accelerate. The central bank noted that the official reserve assets were equivalent to 6.0 months of imports and servicing the government's external debt and remained adequate, supported by stability in both macroeconomic and financial sectors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2023-06-09 11:09:38 </td>
   <td style="text-align:left;"> Gold Set to End Week Higher </td>
   <td style="text-align:left;"> Gold steadied above $1,960 an ounce on Friday and was on track to end the week higher, underpinned by a softer dollar as a surge in US weekly jobless claims reinforced expectations that the Federal Reserve will pause its interest rate hikes next week. Markets now anticipate the Fed to hold rates steady at next week’s policy meeting, before resuming the tightening cycle in July. The European Central Bank and the Bank of Japan are also set to decide on monetary policy next week. Meanwhile, investors remain cautious as the International Monetary Fund urged major central banks to “stay the course” on monetary policy and watch inflation closely. The Reserve Bank of Australia and the Bank of Canada both unexpectedly raised interest rates this week, raising the odds that other advanced economies could follow suit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2023-06-09 10:58:49 </td>
   <td style="text-align:left;"> Dollar Set for Second Weekly Fall </td>
   <td style="text-align:left;"> The dollar index held below 103.5 on Friday after losing 0.8% in the previous session, tracking weakness in Treasury yields as a surge in weekly jobless claims reinforced expectations that the Federal Reserve will pause its interest rate hikes next week. The greenback was also down 0.6% so far this week, on track to decline for the second consecutive week. The number of Americans filing new claims for unemployment benefits jumped to 261K last week, posting the highest reading since October 2021 and exceeding forecasts of 235K. Markets now anticipate the Fed to hold rates steady at next week’s policy meeting, before resuming the tightening cycle in July. Investor also look ahead to US inflation data on Tuesday, as well as interest rate decisions from the European Central Bank and the Bank of Japan next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 10:55:00 </td>
   <td style="text-align:left;"> Hong Kong Stocks Down But Point to Gains Weekly </td>
   <td style="text-align:left;"> The Hang Seng fell 64 points or 0.33% to 19,235 in early deals on Friday after gaining in the prior two sessions, dragged by losses from tech shares, property, and financials. Market participants were cautious as deflation risk in China grew following weaker-than-expected inflation data for May.  Official figures showed that the country's annual inflation rate edged up to 0.2% from April's 26-month low of 0.1%, below market consensus of 0.3%, while producer prices fell by 4.6%, the most since 2016. Locally, recent readings pointed that Hong Kong's forex reserves dropped to a 7-month low in May, while factory activity grew the least in five months amid slowing orders and rising cost burdens. JD Health Intl. shed by 3.3%, followed by Alibaba Health Intl. (-2.5%), Haier Smart Home (-1.7%), Xiaomi Corp. (-1.5%), and AIA Group (-1.2%). Still, the index for the week is set to book a 1.5% rise, encouraged by optimism that Beijing will deliver more stimulus to spur economic recovery in China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 10:35:00 </td>
   <td style="text-align:left;"> China Stocks Rise After Inflation Data </td>
   <td style="text-align:left;"> The Shanghai Composite rose 0.55% to close at 3,231 while the Shenzhen Component gained 0.66% to 10,794 on Friday, extending gains from the previous session as investors reacted to softer-than-expected Chinese inflation data. China’s consumer price index rose 0.2% year-on-year in May, lower than the 0.3% forecast, while producer deflation continued last month. Weakening economic data in China fueled speculations that authorities could introduce more fiscal and monetary stimulus this year, including a possible cut to banks' reserve requirement ratio. High-growth technology stocks led the advance, with strong gains from iFLYTEK (3.3%), Zhongji Innolight (8%), Inspur Electronic (6.1%), Dawning Information (4.5%) and Foxconn Industrial (10%). The Shanghai index inched up 0.04% this week, while the Shenzhen index dropped 1.86%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2023-06-09 10:00:00 </td>
   <td style="text-align:left;"> Oil Heads for Second Weekly Decline </td>
   <td style="text-align:left;"> WTI crude futures traded around $71 per barrel on Friday and were on track to decline for the second straight week, as economic fears and the prospect of higher global supply outweighed Saudi Arabia’s announcement of another output cut in July. Investors continued to grapple with the prospect of further interest rate hikes from major central banks that could negatively impact overall demand, as well as heightened economic uncertainties in top crude importer China. The US oil benchmark also tumbled as much as 4.8% on Thursday following news that the US and Iran reached a temporary nuclear agreement that would allow Iran to resume oil exports of around 1 million barrels per day. However, both countries denied the report, causing oil prices to recoup most of Thursday's losses. Meanwhile, Saudi Arabia announced over the weekend its intention to reduce output by 1 million barrels per day to 9 million bpd in July, the lowest level in years amid an effort to support crude prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/food-inflation </td>
   <td style="text-align:left;"> 2023-06-09 09:51:00 </td>
   <td style="text-align:left;"> China Food Prices Accelerate </td>
   <td style="text-align:left;"> Food prices in China increased by 1.0% year-on-year in May 2023, accelerating sharply from a 0.4% rise a month earlier which was the softest pace since March 2022. This was the 14th straight month of food inflation,  with upward price pressures coming from cooking oils (3.6% vs 4.8%in April), fresh fruit (3.4% vs 5.3%). and milk (0.6% vs 1.1%). At the same time, cost of fresh vegetables declined much softer (-1.7% vs -13.5%). Prices of pork fell by 3.2% after rising 4.0% previously, amid continued efforts from authorities to closely monitor supply and demand in the hog market. Meantime, cost of eggs declined by 1.5% after rising 1.2% in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 09:35:00 </td>
   <td style="text-align:left;"> China Inflation Rate Below Forecasts </td>
   <td style="text-align:left;"> China's annual inflation rate edged up to 0.2% in May 2023 from April's 26-month low of 0.1% but below market estimates of 0.3%. Food inflation picked up from a 13-month low in the prior month (1.0% vs 0.4%) on the back of further rises in prices of both fruit and cooking oil and a softer fall in cost of fresh vegetables. Meanwhile, non-food inflation was flat (at 0.1%), as further falls in prices of both transport (-3.9% vs -3.3%) and housing (-0.2% vs -0.3%) offset rises in cost of health (1.1% vs 1.0%) and education (1.7% vs 1.9%). Core consumer prices, excluding the volatile prices of food and energy, went up 0.6% yoy, after a 0.7% gain in April.  On a monthly basis, consumer prices dropped by 0.2%, the fourth straight month of fall, compared with estimates of a 0.1% decline. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/producer-prices-change </td>
   <td style="text-align:left;"> 2023-06-09 09:35:00 </td>
   <td style="text-align:left;"> China Producer Prices Drop the Most Since 2016 </td>
   <td style="text-align:left;"> China's producer prices fell 4.6% yoy in May 2023, faster than a 3.6% drop in April and worse than market forecasts of a 4.3% drop. It was the eighth straight month of producer deflation and the steepest fall since February 2016 amid weakening demand and moderating commodity prices. A decline in production materials quickened (-5.9% vs -4.7%) due to a faster fall in processing prices (-4.6% vs -3.6%), raw materials (-7.7% vs -6.3%), and extractions (-11.5% vs -8.5%). Also, consumer goods prices edged down (-0.1% vs 0.4%) amid softer rises in prices of food (0.2% vs 1.0%), daily use goods (0.3% vs 0.4%), and clothing (1.4% vs 2.0%). At the same time, the cost of durable goods shrank by 1.1%, following a 0.6% fall in April. On a monthly basis, producer prices decreased by 2.6%, the second straight month of decline, after a 0.5 drop in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/unemployment-rate </td>
   <td style="text-align:left;"> 2023-06-09 09:17:00 </td>
   <td style="text-align:left;"> Philippines Jobless Rate Falls to 4-Month Low </td>
   <td style="text-align:left;"> The unemployment rate in the Philippines declined to a four-month low of 4.5 percent in April 2023 from 5.7 percent in the same month a year earlier, as the economy recovered further from pandemic disruptions. The number of unemployed persons was 2.26 million, down 0.51 million from 2.76 million in April 2022. Meanwhile, the number of employed climbed by 2.43 million to 48.06 million compared to the same period last year. The services sector accounted for the largest share of employment (61.1 percent), followed by the agriculture sector (21.9 percent) and the industry sector (17.0 percent). Meanwhile, labor force participation increased to 65.1 percent from 63.4 percent in April 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/imports-yoy </td>
   <td style="text-align:left;"> 2023-06-09 09:10:00 </td>
   <td style="text-align:left;"> Philippines Imports Drop the Most in Near 3 Years </td>
   <td style="text-align:left;"> Imports to the Philippines slumped by 17.7% yoy to USD 9.43 billion in April 2023, after a downwardly revised 1.2% fall a month earlier. This was the third straight month of decline in purchases and the steepest fall since July 2020 due to weakening domestic demand amid further cost pressures. Imports dropped for electronic products (-17.9%), mineral fuels, lubricants (-42.6%), transport equipment (-25.5%), iron and steel (-16.6%), industrial machinery &amp; equipment (-0.5%), other food and animal (-7.0%). By contrast, purchases grew for cereals &amp; cereal preparations (17.7%), miscellaneous manufacture preparations (25.3%), telecommunication equipment and electrical machinery, and metalliferous ores &amp; metal scrap (281.0%). Purchases were lower from Japan (-14.2%), South Korea (-40.6%), the US (-1.6%), Malaysia (-19.5%), Taiwan (-27.7%), China (-5.9%), Indonesia (-22.0%), the ASEAN (-19.8%), and the EU (-15.9%). By contrast, imports rose from Thailand (7.5%), and Vietnam (18.3%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/exports-yoy </td>
   <td style="text-align:left;"> 2023-06-09 09:06:00 </td>
   <td style="text-align:left;"> Philippines Exports Fall the Most in 35 Months </td>
   <td style="text-align:left;"> Exports from the Philippines tumbled 20.2% year-on-year in April  2023, deepening from a 9.1% drop in the prior month. It was the fifth straight month of fall in shipments and the steepest pace since May 2020, due to further deterioration in foreign demand as the risks of global economic slowdown persisted. Sales fell for electronic products (-17.9%), other mineral products (-5.8%), cathodes, of refined copper (-37.5%), machinery &amp; transport equipment (-10.3%), chemicals (-31.8%), and metal components (-6.2%).  In contrast, exports increased for ignition wiring sets and other wiring sets used in vehicles, aircraft, ships (24.9%), gold (25.2%), and banana (8.0%). By destination, sales shrank to China (-20.7%), the US (-25.3%), Japan (-21.8%), Hong Kong (-18.4%), Singapore (-34.9%), Taiwan (-28.4%), Germany (-0.6%), Netherlands (-25.8%), the ASEAN countries (-30.4%) and the EU (-14.9%). Conversely, they grew to South Korea (18.9%), India (22.2%), and Switzerland (66.8%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 09:03:00 </td>
   <td style="text-align:left;"> Philippines Trade Gap Narrows in April </td>
   <td style="text-align:left;"> The trade deficit in the Philippines decreased to USD 4.53 billion in April 2023 from USD 5.32 billion in the same month a year earlier, as exports dropped more than imports. Shipments tumbled 20.2% from a year earlier to USD 4.90 billion, the fifth straight month of fall, amid weak overseas demand and lingering global headwinds. Meanwhile, purchases fell at a softer 17.7% to USD 9.43 billion, the fourth fall so far this year, as cost pressures continued to rattle domestic demand while commodity prices eased further. Considering the first four months of the year, the trade deficit was at USD 19.28 billion, widening from the USD 18.40 billion shortfall in the same period of 2022. Last year, the trade shortfall increased to USD 58.32 billion from USD 42.23 billion in 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 09:01:00 </td>
   <td style="text-align:left;"> Japanese Shares Track Wall Street Higher </td>
   <td style="text-align:left;"> The Nikkei 225 Index rallied 1.97% to close at 32,265 while the broader Topix Index jumped 1.5% to 2,224 on Friday, rising for the first time in three sessions and taking cues from a strong lead on Wall Street as a sharp fall in Treasury yields boosted technology and other growth stocks. Those moves came as latest data showed that new unemployment claims in the US surged to an over 1-1/2 -year high last week, bolstering the case for a pause in the Federal Reserve’s interest rate hikes this month. Nearly all sectors participated in the rebound, with strong gains from index heavyweights such as Fast Retailing (4.6%), Advantest (2.9%), Keyence (2.1%), Toyota Motor (1.4%) and Sony Group (2.1%). The Nikkei 225 Index gained 2.5% this week, extending its winning streak to nine consecutive weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 08:52:00 </td>
   <td style="text-align:left;"> Australian Shares Rise on Mining Boost </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index rose 0.32% to close at 7,123 on Friday, snapping a three-day decline, with mining stocks leading the advance amid firmer metals prices. Australian shares also tracked gains on Wall Street overnight as a sharp fall in Treasury yields boosted technology and other growth stocks. Iron ore, lithium and gold miners led the charge, with gains from BHP Group (1.2%), Rio Tinto (0.4%), Fortescue Metals (1.4%), Pilbara Minerals (0.5%) and Northern Star Resources (2%). Other index heavyweights also advanced, including ANZ Group (0.9%), Macquarie Group (0.9%) and Goodman Group (1.2%). Meanwhile, energy stocks declined after oil prices tumbled overnight, with sector leaders Woodside Energy and Santos losing 0.3% and 0.7%, respectively. Still, the benchmark index lost 0.32% this week, posting its third straight weekly decline. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2023-06-09 20:13:53 UTC +8

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
   <td style="text-align:left;"> 2023-06-09 20:13:24 </td>
   <td style="text-align:left;"> $SPY in the best case scenario will go to 435 in the worst to at lest 380. You can decide how to position yourself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:23 </td>
   <td style="text-align:left;"> ETF Sentiment: $SPY is the #1 ETF that institutions are trading with 1.1M options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK $META . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:13 </td>
   <td style="text-align:left;"> $SPY gonna happen again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:04 </td>
   <td style="text-align:left;"> $NFLX $SPY  🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:46 </td>
   <td style="text-align:left;"> $SPY $ES_F we&amp;#39;ve minted 4300 short for 7 different scalps for thousands of dollars. Do we believe the short is there again? Well the level is, but eventually they bang the door long enough it gets opened. If it opens, it really opens. I&amp;#39;ll wait and see if number 8 is the opening first. A Rational Thought~ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:30 </td>
   <td style="text-align:left;"> $SPY puts at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:21 </td>
   <td style="text-align:left;"> $SPY Bulls think ATHs are deserved when the world is the worst it&amp;#39;s been since the geopolitical and economic tensions of the 1970s 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:18 </td>
   <td style="text-align:left;"> $SPY shorts ⬇️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:04 </td>
   <td style="text-align:left;"> $spy 4310 and crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:11:55 </td>
   <td style="text-align:left;"> $JPM vs. $SPY vs. $TLT: what will be the best investment? #JPMorganChaseCo https://srnk.us/go/4713903 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:11:54 </td>
   <td style="text-align:left;"> $SPY Appreciate the cheaper puts at open bulls. Take it up higher and higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:11:16 </td>
   <td style="text-align:left;"> $SPY No pullback expected- blue sky to 435 today, trapping bear after bear above 430 fueling our 0dtes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:11:11 </td>
   <td style="text-align:left;"> $SPY $VIX I think J-Pow might need to raise rates another 3% or 4% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:10:41 </td>
   <td style="text-align:left;"> $SPY every week the markets pump non stop or float at resistance .. wtf happen to red days ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:10:35 </td>
   <td style="text-align:left;"> $QQQ $SPY free money day is here!! No downside risk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:10:25 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ $TSLA  do all  nvidia bulls feel safe relying on TSMC? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:10:06 </td>
   <td style="text-align:left;"> $SPY Dancing man keeps dancing boys...you know what that means....no one can stop the dancing man.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:55 </td>
   <td style="text-align:left;"> $SPY not a matter of if but when and how much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:28 </td>
   <td style="text-align:left;"> $SPY Yeah, pull back to 4280 in the morning to make the fake fakeout and then run to 4325 today. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:26 </td>
   <td style="text-align:left;"> $SPY can anything stop this insane melt up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:20 </td>
   <td style="text-align:left;"> $SPY Time to panic bears. You know the drill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:10 </td>
   <td style="text-align:left;"> $SPY Weekly chart with machine learning ma&amp;#39;s. Looking interesting $GOLD $SLV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:03 </td>
   <td style="text-align:left;"> $TSLA $SPY 

They wanted him out of twitter and now they created a monster. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:08:43 </td>
   <td style="text-align:left;"> $SPY if u think this going up I’m sorry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:08:22 </td>
   <td style="text-align:left;"> $NIO $QQQ $SPX $SPY 

And shorts already blasted. They don’t learn 🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:08:03 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:07:37 </td>
   <td style="text-align:left;"> Feels like there’s a hedge fund going broke today on a massive short squeeze break out $SPY $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:07:23 </td>
   <td style="text-align:left;"> $SPY these guys reading the last 24-hour headlines “new Bull Market”.  let’s see what they do… 🤔

https://www.cnbc.com/2023/06/07/millionaires-hoarding-cash-betting-on-higher-rates-cnbc-survey-says.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:07:07 </td>
   <td style="text-align:left;"> $SPY TRUMP 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:06:29 </td>
   <td style="text-align:left;"> $SPY   Only up, up, up!!!
S&amp;amp;P is in a New Bull Run!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:06:13 </td>
   <td style="text-align:left;"> $SPY SoFi has been killing it 🔥 come join the fun 

https://www.sofi.com/invite/invest?gcp=6a8612e3-a8ae-40a0-a482-279de12ecefa&amp;amp;isAliasGcp=false </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:06:01 </td>
   <td style="text-align:left;"> $SPY bulls are delusional..the top is in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:05:58 </td>
   <td style="text-align:left;"> $4750  $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:05:18 </td>
   <td style="text-align:left;"> $SPY top at 430 end at,425? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:05:17 </td>
   <td style="text-align:left;"> 6/9/2023 
 
I&amp;#39;ve been posting ongoing that we are in a bull market but NOW IT&amp;#39;S OFFICIAL 
 
The benchmark S&amp;amp;P 500 is now UP 20% off it&amp;#39;s October lows. 
 
Market winners, market pros have always said the best time to get into the market is at the beginning of a bull market.   
 
6/9/2023  
 
$spy $spx $study $dia $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:04:21 </td>
   <td style="text-align:left;"> $BTC.X $ARKK $SPY  apple has a market cap several multiples of what btc would be at 100k. Apple is traded in the US. Btc is a global asset and is increasingly being adopted. I&amp;#39;m not sire about 1m but a few hundred thousand is certainly a very strong possibility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:04:00 </td>
   <td style="text-align:left;"> $SPY has an average volume of 77863700. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:03:44 </td>
   <td style="text-align:left;"> $SPY oh shit green already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:03:42 </td>
   <td style="text-align:left;"> $SPY hit 430 for God&amp;#39;s sake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:03:11 </td>
   <td style="text-align:left;"> Can test $440 enough hedge funds short get caught up on low volume liquidity. More of them then people paying attention to the market daily bases $SPY $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:03:08 </td>
   <td style="text-align:left;"> $SPY 600 by year end! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:02:38 </td>
   <td style="text-align:left;"> $SPY you know what  to do, hide in apple and NVDA! spin that shit hahaha 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:02:16 </td>
   <td style="text-align:left;"> $SPY team, it appears we are among another Free Money Friday and citygirl will endure more losses as they plow the $vix down to sh*t, but all is not lost as we still are all in $UVIX and one catapult to 100 on the vix will get CG outta the hole.  Love to the fans!  Kiss kiss 💋 MUAH!  $UVXY hi gecko❣️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:02:13 </td>
   <td style="text-align:left;"> $SPY Joe bidens market is clearly strong and better than trump . We will see the biggest run and new ATH .. it will be YUGE, the greatest president in awhile </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:02:01 </td>
   <td style="text-align:left;"> $SPY would like to see another rejection or 2 of 430 to load up on puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:01:24 </td>
   <td style="text-align:left;"> $SPY SPY&amp;#39;s 1-hour chart shows a triple top formation, with 429.6 tested and established as a strong resistance level. Due to the upcoming FOMC meeting next week, the volatility in the recent trading days is expected to be limited. Today, pay attention to the oscillation between 426 and 429.6. Consider selling around 429 and buying around 426, with a stop loss of $0.5. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:01:12 </td>
   <td style="text-align:left;"> $SPY 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:00:52 </td>
   <td style="text-align:left;"> 🛑*PUTIN: RUSSIA TO PLACE NUKE WEAPONS IN BELARUS AFTER JULY 7-8❗
https://twitter.com/PaulVikingGlob1/status/1667135168002260992?t=e3fQ2lRL9nuqVgfvBAAb2A&amp;amp;s=19
$QQQ $SPY $DJIA $ARKK $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:00:47 </td>
   <td style="text-align:left;"> $SPY lol works like a clock… the whole week was green damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:00:46 </td>
   <td style="text-align:left;"> $SPY biggest racket on the planet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:00:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $NVDA $MSTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:00:08 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ ok bulls.
Y’all just need to hold it here for another hour and a half. Hoping to be able to buy puts at this level before the call strikes are printed for today’s expiration. Once that happens  this booger is gonna dip. Just a little longer. Surprise me and run it to $260 so I can add even more. Please.. pretty please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:00:01 </td>
   <td style="text-align:left;"> $SPY $META $SQ $QQQ $SOFI Literal complacency. There is no way to fail. 
 
In game theory, when enough people believe this, is exactly when it cant be true -- otherwise everyone who simply receive free money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:59:34 </td>
   <td style="text-align:left;"> $SPY Cant you pussy bulls get this over 430? I mean my money is sitting on the other side just waiting for you to come get it. Get your bitch ass moving. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:59:26 </td>
   <td style="text-align:left;"> $SPY so there is no news today?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:59:10 </td>
   <td style="text-align:left;"> $SPY  Wen that Lambo?     $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:58:50 </td>
   <td style="text-align:left;"> $MVIS $SPY let her eat!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:58:47 </td>
   <td style="text-align:left;"> $SPY $QQQ  Short squeeze to a record high today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:58:42 </td>
   <td style="text-align:left;"> $SPY are we going to ATH without filings the gaps at $407 and $422? Hmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:58:18 </td>
   <td style="text-align:left;"> $SPY all new 52 week high today, mark this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:58:01 </td>
   <td style="text-align:left;"> $BTC.X Cathie Woods is seriously the most deluded nut job out here. For this to even hit 100k a coin would be some kind of extreme miracle. But 1 million a coin? LMFAO. $ARKK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:57:43 </td>
   <td style="text-align:left;"> $SPY decent pull back and then we gap up over this area. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:57:38 </td>
   <td style="text-align:left;"> $SPY tesla calls and bitcoin&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:57:11 </td>
   <td style="text-align:left;"> $SPY moon market says adct ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:56:43 </td>
   <td style="text-align:left;"> $SPY When do those T-notes hit the street? Asking for a distracted trader... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:55:36 </td>
   <td style="text-align:left;"> $BAOS $MDGS  $SPY $CFRX  $MCOM  Everyone should be following this guy. Insane gains. 🍻 👏🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:54:51 </td>
   <td style="text-align:left;"> $SPY Staying out of this for a few days , just don&amp;#39;t trust it up hear , way to extended with news on the horizon, not to mention there are tons of ,430 calls expiring today I&amp;#39;m sure they might not want in the money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:54:49 </td>
   <td style="text-align:left;"> $tsla with cpi on Tuesday… markets may not rush $spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:54:32 </td>
   <td style="text-align:left;"> $SPY can’t get over 430 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:53:49 </td>
   <td style="text-align:left;"> $SPY IM READY😁🍭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:53:13 </td>
   <td style="text-align:left;"> $SPY First move is usually the wrong move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:53:05 </td>
   <td style="text-align:left;"> $PLTR $17 then $10-$7 for gap fill

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:53:03 </td>
   <td style="text-align:left;"> $SPY The most profitable trade is to… just stop kidding yourself!

Either DCA and hedge, or put a serious effort into a trading education. BTW, Seeking Alpha on ZeroEdge is not education. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:52:55 </td>
   <td style="text-align:left;"> $SPY have a great weekend yall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:52:54 </td>
   <td style="text-align:left;"> $SPY FOMO will grind this higher. Too much scared money sold in 2022 and is now missing the run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:52:39 </td>
   <td style="text-align:left;"> $SPY can we break this $429?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:52:34 </td>
   <td style="text-align:left;"> $SPY https://www.stockilluminati.com/spy/news.php - &amp;#39;Rich Dad&amp;#39; Predicts Crash Worse Than 2008 - Buy Gold And Bitcoin: Our Approach </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:52:24 </td>
   <td style="text-align:left;"> $SPY guess it looks like calks today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:52:12 </td>
   <td style="text-align:left;"> $NA lads AGBA 433 percent revenue increase in one quarter after COVID restrictions lifted....8 million free float, company insiders just bought back 800k shares,
160 million revenue expected per year...undervalued.
Hong Kong play...
Income Statement

$SPY $CARV $BAOS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:51:50 </td>
   <td style="text-align:left;"> $SPY any bear complaining has never traded before. When doesn’t the market run into CPI and the FED? Next week could be totally different </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:51:17 </td>
   <td style="text-align:left;"> @MLinv Wycoff is 100% useless in terms of applying it too $SPY  
 
A better chart is the FU Bears chart.....the ONLY TRUTH about the future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:51:08 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:51:04 </td>
   <td style="text-align:left;"> $SPY how I feel knowing bears are probably gonna get divorced and destory their lives trying to short $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:50:52 </td>
   <td style="text-align:left;"> $SPY $QQQ san other suspicious pump in PM. Let’s see what WS has in agenda for today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:50:45 </td>
   <td style="text-align:left;"> $NIO 😉

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:50:11 </td>
   <td style="text-align:left;"> $SPY wtf is going on with this shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:49:57 </td>
   <td style="text-align:left;"> $SPY green 433 gap up 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:49:09 </td>
   <td style="text-align:left;"> $SPY Breaking News: Stocks making the biggest moves premarket: Target, Tesla, General Motors, DocuSign and more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:48:42 </td>
   <td style="text-align:left;"> $SPY VIX is now $13.67 and we still haven’t got a new 52 wk high? 
  LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:48:41 </td>
   <td style="text-align:left;"> $SPY Wow, turns green. TSLA saved the market. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:48:38 </td>
   <td style="text-align:left;"> $SPY shorts will have trouble here because atleast 90 of the 500 hit 52 week highs, n word on the street is that they wont stop the run until 250 of the 500 hit 52 weeks highs wow. so tsla going to 320 n all these companies until end of july or something. depression delayed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:48:37 </td>
   <td style="text-align:left;"> $SPY Will add to puts. This can’t last much longer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:48:22 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:47:52 </td>
   <td style="text-align:left;"> $SPY lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:47:19 </td>
   <td style="text-align:left;"> $SPY Latest 1hr view from the Post-Market update. Showing a reaction higher taking place as expected. Longs should be risk free by now #Elliottwave #Trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:46:58 </td>
   <td style="text-align:left;"> $SPY just like that magical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:46:26 </td>
   <td style="text-align:left;"> $SPY stock markets move like we are ruled by a Queen or something </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:45:19 </td>
   <td style="text-align:left;"> @Lettingitride $SPY nope 
 
$UVXY reverse split (thanks to someone giving me the link) 
 
https://www.businesswire.com/news/home/20230607005632/en/ProShares-Announces-ETF-Share-Splits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:45:09 </td>
   <td style="text-align:left;"> $SOFI call activity will be interesting as this comes up on a 52 week high bearish to bullish reversal. Could blow through 8.52 to the 9s $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:44:51 </td>
   <td style="text-align:left;"> $CVNA Strap in for the $29 test 🚀🧨 
 
over that, $34--&amp;gt;$39–&amp;gt;$46 
 
$TSLA $SPY $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:44:14 </td>
   <td style="text-align:left;"> $spy levels ♥️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:43:53 </td>
   <td style="text-align:left;"> @Montybonjangles @Learningtoretire $SPY hey if you want a short that makes 10% a month for life just learn how to short $UVXY with puts forever!!! 
 
No spike matters. It will drop 50% or more a year for life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:43:39 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m worried about Tech stocks. They did a bit of rebalancing the other day, dropped the nasdaq by almost 400pts from the days high. It&amp;#39;s likely that was a tranche of movement, and there&amp;#39;ll be another round of it given the recovery of prices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:43:05 </td>
   <td style="text-align:left;"> $SPY sooooo guys if market is still pricing in a cut this year and we don&amp;#39;t get a cut we still go up? Is the bull market truly even though as of now extreme greed is upon this market? Ppl don&amp;#39;t believe we are going to have a recession and if we are not going to have a recession what will be the reason feds cutting rates? Oil been up even though oil stocks are down, wages have been going up even tho unemployment went up I&amp;#39;m sure rents still going up. Some countries took ab early pause and came back hiking again. This is confusing 😕 back to sport betting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:42:45 </td>
   <td style="text-align:left;"> $SOXS loading with both hands. This Friday feels different from recent past Fridays where $VIX crush program was much stronger. Could indices reverse? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:42:29 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
Europe is in STAGFLATION 
US is in STAGFLATION whether you believe or not....once market realise this, its going to rock and roll for everybody.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:42:17 </td>
   <td style="text-align:left;"> @Montybonjangles @Learningtoretire $SPY I even post how to short BETTER Than any bear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:42:17 </td>
   <td style="text-align:left;"> $SPY things are looking great!! We can’t lose! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:41:51 </td>
   <td style="text-align:left;"> @Montybonjangles @Learningtoretire $SPY now you can cry 24/7 about your failed lives, cry about the market or you can make $$ 
 
I post how to trade it every second of the day, every week, every month. 
 
I post the trades that have 100% success rate LONG TERM. 
 
There is NO loss in my strategies. 
 
your choice if you are tired of being losers in life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:41:15 </td>
   <td style="text-align:left;"> $SPY Fighting inflation printing more money. Let’s see how this ends. I’m sidelined </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:40:38 </td>
   <td style="text-align:left;"> $SPY back in 2018, nobody saw this bullish long uptrend. Wonder if it will be the same hmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:40:33 </td>
   <td style="text-align:left;"> @Montybonjangles @Learningtoretire $SPY here is the simple truth. 
 
We have record cash, record bond $$ making 4+ trillion a year. We have a lowest allocation of $$ to the stock market EVER. Its hated, its feared and we have RECORD $$ hedging it every second of the day. 
 
That is not remotely bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:40:31 </td>
   <td style="text-align:left;"> $SOFI hitting a 52 week high ere the. 10.25 on deck. This stock will see 15-20$ in the next 12 months as financials are revised to reflect student loans. Noto has been clear that the resumption of student loans is not in their guidance $SPY $QQQ $KRE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:40:17 </td>
   <td style="text-align:left;"> $SPY $440 on deck! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:40:13 </td>
   <td style="text-align:left;"> $SPY tanking at bell 👀💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:40:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC Time to rally 5%! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:39:41 </td>
   <td style="text-align:left;"> $SPY this looks like it goes down today and tomorrow then goes nuts Tuesday after cpi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:39:18 </td>
   <td style="text-align:left;"> $SPY latex75db7e92a77b8a174d1b50c98561cc71SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:38:45 </td>
   <td style="text-align:left;"> My alerts for LARGE caps.This shows the result of ONLY buying when H% is low.
I have timestamps + buy fills for everything

$TSLA + $AAPL + $NKE are just few of many I&amp;#39;ve traded. $SPY 
I don&amp;#39;t make 100s of trades. I only buy when I get a confirmation. Ask me for the receipts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:37:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA let it be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:37:37 </td>
   <td style="text-align:left;"> @MLinv that shit is STUPID. can I just bet your life into the ground for fun?  
 
Wycoff is a moron and that shit only applies to random failed companies. NOT INDEXES like $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:37:29 </td>
   <td style="text-align:left;"> $SPY $TSLA #PAMPHERTFUP🐂🐂💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:37:13 </td>
   <td style="text-align:left;"> $SPY big red at open today. Bulls got too greedy. It&amp;#39;s done.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:36:50 </td>
   <td style="text-align:left;"> $SPY I do enjoy that all the broke morons posting negative bear shit in $TLSA got SMOKED, I can only hope it chokes them into silence. 
 
Meanwhile FAILED idiots long in $GME and $AMC getting what they deserved. 
 
The market is doing what it should....beating failed humans into the ground CONSTANTLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:36:49 </td>
   <td style="text-align:left;"> $DIA $SPY $IWM Weak China inflation data fuels rate cut speculation. 
 
China&amp;#39;s inflation rate nudged fractionally higher, but at 0.2% remained close to zero and at the same time, PPI inflation dropped to -4.6% from -3.6% y/y. A weaker than expected result and while much of it is due to lower commodity prices, the numbers added to concern that the economy continues to struggle, and that the recovery will be weaker than anticipated. Pressure on the PBOC to cut rates is mounting and a prominent economist and government adviser today called for lower rates to ease the financing burdens on private businesses and support the recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:36:31 </td>
   <td style="text-align:left;"> $WLGS $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:36:19 </td>
   <td style="text-align:left;"> $SPY https://www.stockilluminati.com/spy/news.php - May CPI Report Preview: Inflation Is Settling At 5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:35:47 </td>
   <td style="text-align:left;"> $SPY Tesla is all that is holding this index up lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:35:38 </td>
   <td style="text-align:left;"> $SPY they are gonna push this to a new yearly high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:35:29 </td>
   <td style="text-align:left;"> $SPY The next phase of the bear market will be the most dangerous as everyone is now going long here thinking its over

So many will be trapped for a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:35:27 </td>
   <td style="text-align:left;"> $SPY $QQQ We&amp;#39;re at extreme greed levels (esp. put/call ratio 5 day avg.), but several pundits noting if next week&amp;#39;s CPI has a 3 handle SPX breakout above 4300 likely. Will have the popcorn ready next week CPI, JayDay (78% no hike), PPI on deck. OPEX thereafter and JUL earnings season a month away. 
 
https://www.cnn.com/markets/fear-and-greed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:35:05 </td>
   <td style="text-align:left;"> SEC Filing | CRISPR Therapeutics

$Crsp $spy $gm $vrtx http://ir.crisprtx.com/node/12771/html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:34:53 </td>
   <td style="text-align:left;"> $SPY 1hr view from the yesterday&amp;#39;s Pre-Market update. Called for a pullback towards another blue box area where buyers were expected to appear #Elliottwave #Trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:34:52 </td>
   <td style="text-align:left;"> $DIA latexcc90a8dae2ca432e1c0ae2b33d9fd808META 
$SPY 
 
🔥We Trade LIVE daily for FREE🔥 
📈FOLLOW for Trade-Ideas+📉 
And BE READY!💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:33:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $META $SQ $SOFI money printing machine all warmed up and ready today. We can’t lose in this market. I foresee algos and feds pumping this for months. Makes a bad administration look good. If you’re a bear right now I feel sorry for you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:33:38 </td>
   <td style="text-align:left;"> $DIA $SPY $IWM $OIL Oil Action as of 07:05am: 
 
Oil prices are heading for a weekly loss, despite the unexpected announcement of a further output cut from Saudia Arabia at least through July. China&amp;#39;s sluggish recovery and the prospect of higher for longer scenarios on official rates in many countries have kept a lid on oil prices. Russian oil is also still reaching world markets. Against that background prices have remained capped and the front end WTI contract is currently trading at USD 71.311 per barrel, and is down -0.8% over the week and -1.9% over the month. Brent has fared slightly better, but not much. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:32:42 </td>
   <td style="text-align:left;"> This may be more bearish than any day in history $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:32:32 </td>
   <td style="text-align:left;"> $SPY  ———&amp;gt; if you like making insane money go to $NA same underwriter $AMTD and $HKD.... just saying, can go blue skies meme of the month
1 m float.... if just even a little volume from HKD or AMTD comes this goes berserk.
 They will find it
$NA is at same price as $HKD before it went over $1100... just saying I think that’s Bullish

 $UCAR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:32:28 </td>
   <td style="text-align:left;"> $SPY suppose to be around 426 to be honest, can’t wait </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:32:26 </td>
   <td style="text-align:left;"> $SPY $195BN Time to hedge now that its cheap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:32:25 </td>
   <td style="text-align:left;"> $SPY $ETH.X $UVXY having too many tickers on your watchlist can be a distraction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:32:22 </td>
   <td style="text-align:left;"> $SPY Rocking my SPY 500 hat around town. Dapping it up with bulls, and watching bears scurry away as their bear wives  ask for my number. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:31:22 </td>
   <td style="text-align:left;"> @MLinv $SPY $QQQ meanwhile we have million+ puts shorting the market every day. 
 
Complacency??? lmao......why is there so much ignorance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:31:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK $TLT $GOLD 

Well, $460 here we come. 
What’s that sideline money going to do now?
Have all the shorts covered yet?
I know bull margin has been steadily increasing each month since January. 
October 2022 was our low. 
It’s time to move and shake again!

https://www.marketwatch.com/story/s-p-500-exits-longest-bear-market-since-1948-what-stock-market-history-says-about-what-happens-next-a336a139 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:31:08 </td>
   <td style="text-align:left;"> $SPY https://www.stockilluminati.com/spy/news.php - You May All Be Wrong About Liquidity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:31:04 </td>
   <td style="text-align:left;"> $SPY 1hr view from the Weekend update. Managed to extend higher as expected. Don&amp;#39;t like selling it #Elliottwave #Trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:31:02 </td>
   <td style="text-align:left;"> $SPY https://www.stockilluminati.com/spy/news.php - Big Tech Strikes Back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:30:28 </td>
   <td style="text-align:left;"> $SPY lets see 435 today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:30:25 </td>
   <td style="text-align:left;"> $SPY NEW ARTICLE : You May All Be Wrong About Liquidity https://www.stck.pro/news/SPY/52580035/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:30:06 </td>
   <td style="text-align:left;"> $spy Complacency is the greatest enemy of excellence….just wait for it…. if you look closely you can see it coming.. don’t let it happen to you 🆘🚨

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:29:56 </td>
   <td style="text-align:left;"> When that trap door is unleashed it’s going to be hell to pay $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:29:56 </td>
   <td style="text-align:left;"> $TSLA $CVNA $SPY $NVDA $AI 

Tesla hitting $250 pm 🤣😂😂😂🤣

Bears: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:29:41 </td>
   <td style="text-align:left;"> $SPY hey bears I got the chart you’ve been waiting for. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:29:40 </td>
   <td style="text-align:left;"> @Gamblingwith529 $SPY we have a decade of record incomes to buy the market non-stop 
 
How can you not be bullish long term?? what kind of failed life do you have ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:29:36 </td>
   <td style="text-align:left;"> $TSLA for planning purposes. 🫦 
 
[weekly candles, MAs]. 
 
🎩 
🙌🏻 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:29:29 </td>
   <td style="text-align:left;"> $SPY 1hr view from the 6.01.2023 Midday update. Showing initial reaction higher taking place from the blue box area. Allowed longs to get into a risk-free position #Elliottwave #Trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:29:22 </td>
   <td style="text-align:left;"> $SPY red to green here soon .. just more bear traps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:29:09 </td>
   <td style="text-align:left;"> $SPY https://www.stockilluminati.com/spy/news.php - Bull Market Or Bull Trap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:29:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $DJIA S&amp;amp;P 500 notches highest close for 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:28:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA What a corrupt, POS country this has become at the hands of scumbag Democrats, liberals, Deep State rats, and D.C. careerists.  Selective application of the &amp;quot;law&amp;quot; and &amp;quot;unequitable&amp;quot; investigations.  Need a loose cannon of justice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:28:37 </td>
   <td style="text-align:left;"> $SPY Man, if we have another 11 year bull market, I swear to god </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:28:33 </td>
   <td style="text-align:left;"> $TSLA boys ———&amp;gt; go to $NA same underwriter $AMTD and $HKD.... just saying, can go blue skies meme of the month
1 m float.... if just even a little volume from HKD or AMTD comes this goes berserk.
 They will find it
$NA is at same price as $HKD before it went over $1100... just saying I think that’s Bullish

 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:28:31 </td>
   <td style="text-align:left;"> $SPY i don’t trade on Fridays. If I was $430 calls would be my play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:28:19 </td>
   <td style="text-align:left;"> $SPY 
Next week
Monday 
123BN Bills
40BN 3&amp;#39;s 
32BN 10&amp;#39;s on one day
That&amp;#39;s $195BN total and duration heavy. Reserves will be drained

Tuesday
CPI
83BN bills
18BN 30&amp;#39;s
101 BN,Reserves will be drained 

Wednesday 
FOMC
PPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:28:13 </td>
   <td style="text-align:left;"> $NA  $CVNA ———&amp;gt; lads go to $NA same underwriter $AMTD and $HKD.... just saying, can go blue skies meme of the month
1 m float.... if just even a little volume from HKD or AMTD comes this goes berserk.
 They will find it
$NA is at same price as $HKD before it went over $1100... just saying I think that’s Bullish

$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:27:21 </td>
   <td style="text-align:left;"> if you took this week’s PUTS you should prob just quit tradin 🤣🤡 $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:27:16 </td>
   <td style="text-align:left;"> $SPY Sure is a  lot of bearish on here for the market to be basically flat in premarket hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:27:06 </td>
   <td style="text-align:left;"> $SPY remember to pay the victims </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:27:05 </td>
   <td style="text-align:left;"> @Cad_Bane $SPY The more important fact here is that the endless crazy tiny $$ drama world never stop creating fear bias which makes it easy to wipe more weak $$ out. 
 
Wall St wants this crazy $$ world to never stop, Wall St wants them all to be negative 24/7, wants them all to think they can time their way into wealth WHILE WALL ST beats them into the ground constantly. 
 
Ironic that I post the brutal truth instead of stroking their broke $$ egos and Im the MEAN person that is wrong. 
 
if they listen they make insane $$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:26:52 </td>
   <td style="text-align:left;"> $SPY Calendar - 06.09.2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:26:16 </td>
   <td style="text-align:left;"> $SPY huge sell-off at open. Don&amp;#39;t get caught holding the bag bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:26:13 </td>
   <td style="text-align:left;"> $SPY The 2000 bear market at this exact same point rallied 25% from the initial bottom over 6 months, then the next phase began

Thats where we are </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:26:02 </td>
   <td style="text-align:left;"> $MVIS $NVDA $SPY $MMAT valuations are astronomical... where is this new bull market going?  
all while T bills are at 5% yield 🤣😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:25:43 </td>
   <td style="text-align:left;"> $SPY if you think we are going to stay red today must’ve been hit in the head as baby. Tesla alone push everything green. Momentum is bullish ride it or die going against it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:25:16 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $SOXS &amp;quot;JP Morgan&amp;quot; is talking down markets, just as &amp;quot;Morgan Stanley&amp;quot; is. All about the disconnect beween the Bond&amp;amp; Equities. &amp;quot;If stock markets trade, as bond markets, the result will be -20%&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:25:08 </td>
   <td style="text-align:left;"> $SPY 1hr view from the 5/31/2023 Pre-Market update. The pullback managed to reach the blue box area where buyers were expected to appear #Elliottwave #Trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:25:06 </td>
   <td style="text-align:left;"> $SPY algos are forward looking, 2:10 is 100 periods on the 5m prior to cpi 
 
10:00 is 50p prior on the 15m 
 
Etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:25:06 </td>
   <td style="text-align:left;"> @GraffGripANW @Rangebound500 $SPY  
 
&amp;quot;Better buy opp is guaranteed, market always corrects&amp;quot; 
 
 it sounds like you missed the correction less than 12 months ago. 
 
Also its been proven that TIMING is what failed $$ does and FAILED $$ = FAILED $$$ period. 
 
The more you think you can time the more you fall behind. 
 
Markets can correct but no one in the history of markets has been able to time those corrections. The idiots telling you to short, the Burry &amp;quot;Big SHORT&amp;quot; idiots all collect fees from you. 
 
Ironically Burry was a one hit wonder and never made $$$ after 2009. 
 
TIMING and DRAMA chasing = failed $$$ including BURRY vs those who just buy &amp;quot;BUFFETT&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:25:04 </td>
   <td style="text-align:left;"> $SPY  What’s the source of this manipulation? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:25:00 </td>
   <td style="text-align:left;"> $SPY i think today we breakout higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:24:36 </td>
   <td style="text-align:left;"> This shows the monthly results from only making a trade when H% is low.
Whats the Win/Lose ratio? The result speaks for itself.

May (&amp;#39;23) = 0 loss
April (&amp;#39;23) = 0 loss
March (&amp;#39;23) = 1 loss
February (&amp;#39;23) = 0 loss
January (&amp;#39;23) = 0 loss
December (&amp;#39;22) = 2 losses
November (&amp;#39;22) = 0 loss
October (&amp;#39;22) = 2 losses

Got timestamps for the skeptics
$SPY $QQQ $COST $TGT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:24:33 </td>
   <td style="text-align:left;"> $SPY Wow, bears didn’t do the job last night. It’s not down $10 pre market.  That’s a real bad sign to come. Pure manipulation by ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:24:15 </td>
   <td style="text-align:left;"> $SPY Can we see a breakout today? We have been struggling to break 429.60 area. If we can get a break above this level 431.76 is on table (further continuation is possible).  
 
Love how we bounced off the demand area yesterday around that 425-426 zone. If we get another strong rejection back into demand we go on with continued consolidation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:23:58 </td>
   <td style="text-align:left;"> $SPY is going to be a long Friday today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:23:58 </td>
   <td style="text-align:left;"> Who’s more salty Nvidia or Tesla people that missed the run.

$TSLA $NVDA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:22:22 </td>
   <td style="text-align:left;"> @Montybonjangles @Learningtoretire here is a simple question. 
 
if you are broke and uneducated why the hell are you fighting the TRILLION $$ $SPY machine world ??? why are you shorting an index designed to go higher?? 
 
1000 of better shorts in the market EVERY WEEK 
 
$UVXY is a better short FOREVER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:22:16 </td>
   <td style="text-align:left;"> $SPY be green by open $430 1st hour then fireworks potential $435 today and bears signing over deed to their trailers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:21:25 </td>
   <td style="text-align:left;"> $BENF Who’s your daddy?🥳 Ya’ll nailed that 13 entry short from my alert?
$SPY $CVNA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:20:43 </td>
   <td style="text-align:left;"> $SPY if this breaks upward today there will be a wild technical rally imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:20:28 </td>
   <td style="text-align:left;"> $SPY volume dry as a  👵 where’s this bull market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:20:04 </td>
   <td style="text-align:left;"> $SPY what are you listening to?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:19:03 </td>
   <td style="text-align:left;"> $SPY MMs playing musical pumps to keep this high.. I will never not have puts loaded here. Ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:18:42 </td>
   <td style="text-align:left;"> $SPY you know what happens to the little piggy’s that didn’t fly straight? They all got shot down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:18:42 </td>
   <td style="text-align:left;"> $SPY vs small caps. Long term winner will be _____? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:18:12 </td>
   <td style="text-align:left;"> $SPY  any data this morning that would move the price much in either direction? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:18:01 </td>
   <td style="text-align:left;"> $TSLA $SPY 

I can find hundreds of other companies to short but you aim for tesla. You must like pain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:17:19 </td>
   <td style="text-align:left;"> $SPY $QQQ also low volume Friday.  I guess  it will depend if Tesla keeps pumping or dumps at open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:17:03 </td>
   <td style="text-align:left;"> $SPY another big win yesterday using a proven strategy. That group rocks.
Spy options picks day trading... Meta group </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:17:00 </td>
   <td style="text-align:left;"> Officially in a bull market🐮 $SPY $NVDA $MVIS $MMAT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:16:47 </td>
   <td style="text-align:left;"> $SPY Tesla save the MK today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:16:12 </td>
   <td style="text-align:left;"> $SPY 🧐 I guess none of these holdings move us up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:15:49 </td>
   <td style="text-align:left;"> $SPY Same old same old! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:15:48 </td>
   <td style="text-align:left;"> $SPY 430 almost a guarantee for today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:14:09 </td>
   <td style="text-align:left;"> $SPY back in July last summer the S&amp;amp;P
Officially touched the $380ish price and it was called “the bear market”. Then the markets reversed right after. Let’s see what happens in the next few days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:13:10 </td>
   <td style="text-align:left;"> $SPY sell off starting at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:12:20 </td>
   <td style="text-align:left;"> $TSLA $SPY it’s 6/9 today. It’s time to get some y’all!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:10:50 </td>
   <td style="text-align:left;"> $SPY how long do you believe our civilization lasts for? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:10:45 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$LCID vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:10:05 </td>
   <td style="text-align:left;"> $SPY  What kind of dinosaur can help you find a handy synonym? A thesaurus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:09:51 </td>
   <td style="text-align:left;"> $SPY what the Frick not 500 yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:09:40 </td>
   <td style="text-align:left;"> What are the hottest stocks right now? Pick the best $SPY vs. $UNH vs. $UNIT. https://srnk.us/go/4713728 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:09:04 </td>
   <td style="text-align:left;"> I have a scary joke about math, but I&amp;#39;m 2² to say it...

$spy $qqq $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:07:07 </td>
   <td style="text-align:left;"> $TRIN vs S&amp;amp;P500 $SPX $SPY $VIX 0.36 Current 0.5 TLOW 1.68 THIGH 0.86 RATIO1 2.38 RATIO2 #stocks #trading #markets #finance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:07:06 </td>
   <td style="text-align:left;"> $SPY omg omg omg omg omg for FUCK SAKES can this really be? Is THIS really possible there’s no Way this is happing OMg omg 😳 

Bi Bitching Hour is happening. I can’t believe it 😱 OMG 

There is NO WAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:07:04 </td>
   <td style="text-align:left;"> $SPY ascending triangle from yest session into today.

The squeeze continues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:07:02 </td>
   <td style="text-align:left;"> $SPY   It’s official…S&amp;amp;P enters a Bull Market.  It’s off to the Races!  Bid high, bid fast!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:06:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:05:56 </td>
   <td style="text-align:left;"> $TSLA Winners trade the technicals while LOSERS complain and spit BS into the void $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:05:22 </td>
   <td style="text-align:left;"> @ChartMill $spy $SEV 
🔥🔥🔥🔥💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:04:59 </td>
   <td style="text-align:left;"> $SPY just like yesterdday i will sell puts short again silly silly bear lossing more $$ todays 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:04:24 </td>
   <td style="text-align:left;"> $SEV $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:03:49 </td>
   <td style="text-align:left;"> @GraffGripANW @Rangebound500 at some point you might want to stop losing $$ and learning the truth. Most of that historical PE shit is zero math stupidity pushed from a world that is outdated. 
 
if you think about compounded assets being exponential why the hell are you using a random linear useless number that doesn&amp;#39;t even reflect cash or asset ratios. 
 
If you use 16 PE then at some point the stock market will be 10% of assets while cash/bonds are 90%. 
 
That statement is something no one wants to explain to you. The stupid world of finance uses outdated text books and still draws linear straight lines which is annoying/stupid to the mathematics world. 
 
simple truth, those who wait for 16 PE fail to compound any wealth, live in a broke world and celebrate market proving them right ONCE every 10 years over all. 
 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:03:48 </td>
   <td style="text-align:left;"> $SPY No drop today. GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:03:47 </td>
   <td style="text-align:left;"> * SwX is green and getting stronger (expanding &amp;quot;body&amp;quot;) 
* Daily MoM at 6.8 and climbing. Highest since last August. 
* A 10 month high close and the resistance level at 4325 is still one to watch. 
* Nearly everyone who went Long SPX since May 2022 is now showing a profit.  
$SPY /4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:03:41 </td>
   <td style="text-align:left;"> $SPY seems to get unlimited tries to break resistance and two tries at most to break support. They&amp;#39;ll be chasing a number which is getting above $430. They&amp;#39;ll likely get it. My suspicions are that we&amp;#39;ll probably see $431 - $432, although higher is possible. 
 
When was the last time we closed red on a Friday? May 12th and May 19th closed red. April 14th (slightly red) and 21st (green by one cent) were both a pretty flat close. We were green Mar 31st, April 6th, April 28th, May 5th, May 19th, May 26th, and June 2nd. That makes 70% green and 30% red for the past 10 Fridays. May 12th was the most red at -$1.83. Most of the green closes were up latexa60c24791f38920378f5c03acf1eba49SPY /2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:02:48 </td>
   <td style="text-align:left;"> * 335 SPX stocks in bullish mode = flat. 
* BullsPower keeps the upper hand at 32. 
* The Watershed Envelope is going up at a solid pace, but a touch of the upper bound (currently at 4357) has not been seen in quite a while. 
$SPY /1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:02:00 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ  
 
Only one door to escape out of when the alarm goes off. Hope you make it out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:00:33 </td>
   <td style="text-align:left;"> $SPY I have a werid feeling we&amp;#39;re going to get a &amp;#39;friday sell off&amp;#39;  
special.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:00:13 </td>
   <td style="text-align:left;"> $SPY BEAR TRAP again..LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:00:10 </td>
   <td style="text-align:left;"> $SPY 265$ coming. Wave C </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:00:09 </td>
   <td style="text-align:left;"> $SPY ok, I’m lost. I’m showing futures at $433.60. Why is this trading $5 lower? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 19:00:00 </td>
   <td style="text-align:left;"> $SPY someone did win...but did any1 listen? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:59:30 </td>
   <td style="text-align:left;"> $SPY  $3999 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:58:24 </td>
   <td style="text-align:left;"> $SPY ahhh the vast emptinesss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:57:35 </td>
   <td style="text-align:left;"> $SPY this is why 95% of middle class failures STAY MIDDLE CLASS FAILURES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:55:47 </td>
   <td style="text-align:left;"> $SPY The only FOMO here is when baggies don’t sell for a profit and end up losing it all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:54:02 </td>
   <td style="text-align:left;"> $SPY Someone tell me the game plan for today....anyone here know if it&amp;#39;s going to be a free money friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:53:50 </td>
   <td style="text-align:left;"> Here are today&amp;#39;s $SPY projections. Note Index trend range indicators are getting a false read on uptrend and confirmed down trend read which is a sign markets are overbought. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:53:24 </td>
   <td style="text-align:left;"> $SPY Bear clubs your fearless BEAR leader flipped to bulls side and now FOMOING LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:52:05 </td>
   <td style="text-align:left;"> $AMC  $GME  $SPY  $MULN
 Bears working hard today : </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:50:27 </td>
   <td style="text-align:left;"> $AMZN MMs crunched the data and found retail holding too many naked calls above 120 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:49:25 </td>
   <td style="text-align:left;"> $SPY time to flip the dead bear carcass over and fuck the other hole for a while. Lol shorts are still getting roasted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:48:49 </td>
   <td style="text-align:left;"> $SPY $QQQ no relevant catalyst this morning. It seems that the indexes will be move by Tesla and other tech pumping.  Let’s see what WS has in agenda for today.  Good morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:48:12 </td>
   <td style="text-align:left;"> $SPY NEW ARTICLE : Bull Market Or Bull Trap? https://www.stck.pro/news/SPY/52576808/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:47:05 </td>
   <td style="text-align:left;"> $SPY any data 2 day pm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:46:41 </td>
   <td style="text-align:left;"> $SPY bears getting excited too early. Dip and rip might be in play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:44:34 </td>
   <td style="text-align:left;"> $AMZN amazon news? $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:42:23 </td>
   <td style="text-align:left;"> $SPY same story every time “liquidity crisis shes going down”. Market rips 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:41:45 </td>
   <td style="text-align:left;"> $SPY Imagine questioning the intelligence of people that are actually making money and patting yourself on the back for being smart enough to bet against the market and consistently losing money. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:41:45 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:40:32 </td>
   <td style="text-align:left;"> $SPY bitcoin&amp;gt;puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:39:20 </td>
   <td style="text-align:left;"> $QBTS man I am too bored staying on the sidelines that I ended up buying penny stocks for little excitement. 
Lets go!! Give me some dopamine. 

$SPY break out or drop. Do something interesting. People getting bored to death with sidelines price action. If there is an oscar for your sidelines performance, you will be nominated for a Razzie award for that worst performance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:39:15 </td>
   <td style="text-align:left;"> $SPY $QQQ not too shabby, son. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:38:43 </td>
   <td style="text-align:left;"> $SPY -15 Today is a Must! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:37:50 </td>
   <td style="text-align:left;"> $SPY There’s always something to rally about when your IQ is 70. Everyday locked in a fishbowl seems new. Let’s burn our Wendy’s paychecks to pump this up some </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:36:56 </td>
   <td style="text-align:left;"> $SPY This doesn’t look good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:36:36 </td>
   <td style="text-align:left;"> $SPY TSLA is keeping this up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:36:36 </td>
   <td style="text-align:left;"> $SPY bears are in denial </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:36:07 </td>
   <td style="text-align:left;"> $SPY 420$ today! Heavy sell alert, scam gay alert </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:35:49 </td>
   <td style="text-align:left;"> $SPY watch it rally even today lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:35:46 </td>
   <td style="text-align:left;"> $SPY it’s dropping 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:35:06 </td>
   <td style="text-align:left;"> $SPY  Drops more than $15 dollars today a must </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:34:31 </td>
   <td style="text-align:left;"> $SPY  -$35 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:33:37 </td>
   <td style="text-align:left;"> $SPY dumps or pumps? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:32:50 </td>
   <td style="text-align:left;"> $SPY should drop but will it? Bought some 433 calls for lube in case it tries to rip my face off again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:32:30 </td>
   <td style="text-align:left;"> If this is the new norm $SPY study this. China got rid of pollution with this technology. You may want to look at companies that are involved. They can make clouds, rain and get rid of fire. https://e360.yale.edu/features/can-cloud-seeding-help-quench-the-thirst-of-the-u.s.-west </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:32:24 </td>
   <td style="text-align:left;"> $SPY max pain is 415 this morning just sayin…. They might update at the open but still that’s a BIG DROP if it happens. Ouch wouldn’t want to be holding calls overnight hehe 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:31:08 </td>
   <td style="text-align:left;"> $SPY $NFLX 
Everything $420 today 💨💨💨

SPY pull back and NFLX cup and handle pump to 420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:30:47 </td>
   <td style="text-align:left;"> $SPY caution! Scam alert!! Heavy sell alert!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:30:41 </td>
   <td style="text-align:left;"> $NIO $TSLA $QQQ $SPY  today , my cat Will most likley give birth to small ragdolls. 👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:30:19 </td>
   <td style="text-align:left;"> $SPY Trump most likely will go to the can. I hope they have a large enough orange suit. Keep tuned. Will or maybe affect markets. I told you it was a political year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:29:50 </td>
   <td style="text-align:left;"> @BBWs_Fast_Food_Fund $SPY When boomers send their TRILLIONS down to the next generation there is going to be a massive rush into higher risk assets. 
 
RECORD $$ in cash, RECORD $$ in bonds and an extremely under allocated stock market means one thing in the future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:29:49 </td>
   <td style="text-align:left;"> $SPY Today is already tomorrow in the mind of Kamala </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:29:22 </td>
   <td style="text-align:left;"> $IDEX .12 is the next ceiling! 🔥🔥🚀

Contract announcement last week.
ER expected next week. 

IDEX is getting their sht together! 🤑

$TSLA $RIVN $GM $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:28:45 </td>
   <td style="text-align:left;"> $SPY $527 PUTs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:28:42 </td>
   <td style="text-align:left;"> @BBWs_Fast_Food_Fund $SPY ironically boomers have 4x more $$ in cash/bonds and the stock market is their HEDGE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:27:43 </td>
   <td style="text-align:left;"> @GraffGripANW @Rangebound500 $SPY I would also explain that the following math matters. 
 
480 is 100% fact in the future 
385 is a random stupid guess with lower odds. 
 
I will take the 100% odds trade. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:26:43 </td>
   <td style="text-align:left;"> @GraffGripANW @Rangebound500 my point remains, NOTHING is happening by mid summer for this random 385 shit. 
 
If you said 385 can happen within 12 months then I would say SURE...there is a 5% chance that it happens.  
 
and I would tell you that its practically RISK FREE To hedge for it at the same time. 
 
Im not sure either of you understand the massive TRILLION $$ hedging world that drives $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:25:50 </td>
   <td style="text-align:left;"> $SPY $430 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:24:39 </td>
   <td style="text-align:left;"> $AAPL $META  $SPY  It is time to prepare so we can be ready for the opportunities that will arise today for traders.  Trade what you see and trade the market we have, not the dream market you fantasize about.  Be prepared to act--we get paid for acting, not watching.  Follow the money with @Vegas1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:24:04 </td>
   <td style="text-align:left;"> $SPY Overpumped for the boomer’s retirement accounts? When the boomers pull out their funds, who will capture the sell orders? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:23:05 </td>
   <td style="text-align:left;"> $SPY lmao hunter biden not indicted.  Lmao Hillary not indicted.  Lmao the most corrupt president Biden not indicted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:20:31 </td>
   <td style="text-align:left;"> $SPY sub 425 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:19:46 </td>
   <td style="text-align:left;"> Consumer confidence just tanks’ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:19:45 </td>
   <td style="text-align:left;"> $SPY What a country.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:19:36 </td>
   <td style="text-align:left;"> $SPY way overpumped. Bring it down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:18:35 </td>
   <td style="text-align:left;"> $SPY 385?? Just how many times did your mother drop you on your head when you were little? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:14:50 </td>
   <td style="text-align:left;"> @OldFngGuy $SPY 385 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:14:46 </td>
   <td style="text-align:left;"> Sunday night Futures $3980’ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:14:12 </td>
   <td style="text-align:left;"> Trade idea --&amp;gt; $LABD 
 
Multiple bottom setup, recently hitting $14+ and then retraced back down to the $12s. 
 
Two levels to watch for buyers to step back in are $12 &amp;amp; $11.60s, ideally, we take a position into the momentum (reversal) 
🎯 - $13+ once in position. 
 
🛑 Stop loss recommendation 5% max  
$SPY $QQQ $TSLA $AI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:13:14 </td>
   <td style="text-align:left;"> $SPY WRONG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:13:02 </td>
   <td style="text-align:left;"> @Rangebound500 $SPY you just need to post the bet...you are going to lose and its fun doing this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 18:12:25 </td>
   <td style="text-align:left;"> $SPY  $399 Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:13:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK $META . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:10:58 </td>
   <td style="text-align:left;"> $TSLA $QQQ $ARKK $FNGU $ARKF Cathie&amp;#39;s 24month performance on ARK is a tasty -300%. give her billions boys! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:10:35 </td>
   <td style="text-align:left;"> $QQQ $SPY free money day is here!! No downside risk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:10:25 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ $TSLA  do all  nvidia bulls feel safe relying on TSMC? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:09:47 </td>
   <td style="text-align:left;"> $QQQ never ending pump what could ever go wrong 😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:09:13 </td>
   <td style="text-align:left;"> $TSLA $ARKK $ARKF $QQQ $FNGU Cathie Wood entered her office today 🤑💎😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:08:22 </td>
   <td style="text-align:left;"> $NIO $QQQ $SPX $SPY 

And shorts already blasted. They don’t learn 🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:08:03 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:07:49 </td>
   <td style="text-align:left;"> $QQQ More stupidity that most people thinks the FED needs to pause or cut. Really with this nonstop bullshit mania, nothing has been corrected, if anything need to be raising 100bps each meeting! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:07:37 </td>
   <td style="text-align:left;"> Feels like there’s a hedge fund going broke today on a massive short squeeze break out $SPY $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:05:58 </td>
   <td style="text-align:left;"> $4750  $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:05:17 </td>
   <td style="text-align:left;"> 6/9/2023 
 
I&amp;#39;ve been posting ongoing that we are in a bull market but NOW IT&amp;#39;S OFFICIAL 
 
The benchmark S&amp;amp;P 500 is now UP 20% off it&amp;#39;s October lows. 
 
Market winners, market pros have always said the best time to get into the market is at the beginning of a bull market.   
 
6/9/2023  
 
$spy $spx $study $dia $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:04:04 </td>
   <td style="text-align:left;"> $QQQ help me please 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:03:11 </td>
   <td style="text-align:left;"> Can test $440 enough hedge funds short get caught up on low volume liquidity. More of them then people paying attention to the market daily bases $SPY $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:02:31 </td>
   <td style="text-align:left;"> $QQQ at this rate we will have the lower vix in the history of the VIX. So fucking stupid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:01:07 </td>
   <td style="text-align:left;"> $QQQ QQQ rebounded from the bottom yesterday and entered a relatively indecisive uptrend. On the 4-hour chart, there is a tendency for a head and shoulders pattern, with the neckline around 354, which corresponds to the pink resistance zone in the chart. Today, pay attention to the reaction of the price in this range. It leans towards selling at high levels. If a strong bullish candle breaks above 354.3 and holds steady, it would require following the upward trend and consider going long. Otherwise, 354 could be a medium-term secondary high point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:00:52 </td>
   <td style="text-align:left;"> 🛑*PUTIN: RUSSIA TO PLACE NUKE WEAPONS IN BELARUS AFTER JULY 7-8❗
https://twitter.com/PaulVikingGlob1/status/1667135168002260992?t=e3fQ2lRL9nuqVgfvBAAb2A&amp;amp;s=19
$QQQ $SPY $DJIA $ARKK $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:00:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $NVDA $MSTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:00:08 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ ok bulls.
Y’all just need to hold it here for another hour and a half. Hoping to be able to buy puts at this level before the call strikes are printed for today’s expiration. Once that happens  this booger is gonna dip. Just a little longer. Surprise me and run it to $260 so I can add even more. Please.. pretty please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:00:01 </td>
   <td style="text-align:left;"> $SPY $META $SQ $QQQ $SOFI Literal complacency. There is no way to fail. 
 
In game theory, when enough people believe this, is exactly when it cant be true -- otherwise everyone who simply receive free money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:59:10 </td>
   <td style="text-align:left;"> $SPY  Wen that Lambo?     $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:58:47 </td>
   <td style="text-align:left;"> $SPY $QQQ  Short squeeze to a record high today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:58:40 </td>
   <td style="text-align:left;"> $QQQ find you someone who looks at you the way futures traders look at ndx at 3am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:57:36 </td>
   <td style="text-align:left;"> $QQQ moon market says adct and good morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:54:49 </td>
   <td style="text-align:left;"> $tsla with cpi on Tuesday… markets may not rush $spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:53:41 </td>
   <td style="text-align:left;"> $BODY vs. $QQQ: what will be the best investment? https://srnk.us/go/4713837 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:53:05 </td>
   <td style="text-align:left;"> $PLTR $17 then $10-$7 for gap fill

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:51:16 </td>
   <td style="text-align:left;"> $QQQ Fake pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:50:52 </td>
   <td style="text-align:left;"> $SPY $QQQ san other suspicious pump in PM. Let’s see what WS has in agenda for today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:50:45 </td>
   <td style="text-align:left;"> $NIO 😉

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:42:45 </td>
   <td style="text-align:left;"> $SOXS loading with both hands. This Friday feels different from recent past Fridays where $VIX crush program was much stronger. Could indices reverse? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:42:29 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
Europe is in STAGFLATION 
US is in STAGFLATION whether you believe or not....once market realise this, its going to rock and roll for everybody.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:40:31 </td>
   <td style="text-align:left;"> $SOFI hitting a 52 week high ere the. 10.25 on deck. This stock will see 15-20$ in the next 12 months as financials are revised to reflect student loans. Noto has been clear that the resumption of student loans is not in their guidance $SPY $QQQ $KRE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:40:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC Time to rally 5%! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:39:18 </td>
   <td style="text-align:left;"> $SPY $QQQ don&amp;#39;t be afraid to trade on the OTC market becuz you can make lots of money there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:38:02 </td>
   <td style="text-align:left;"> $QQQ no surprise here. Quietly turn it itself to green over night. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:37:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA let it be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:36:31 </td>
   <td style="text-align:left;"> $WLGS $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:35:27 </td>
   <td style="text-align:left;"> $SPY $QQQ We&amp;#39;re at extreme greed levels (esp. put/call ratio 5 day avg.), but several pundits noting if next week&amp;#39;s CPI has a 3 handle SPX breakout above 4300 likely. Will have the popcorn ready next week CPI, JayDay (78% no hike), PPI on deck. OPEX thereafter and JUL earnings season a month away. 
 
https://www.cnn.com/markets/fear-and-greed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:34:52 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ What will happen first Trump will be convicted or Trump will default ON ANOTHER LOAN??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:34:40 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - May CPI Report Preview: Inflation Is Settling At 5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:33:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $META $SQ $SOFI money printing machine all warmed up and ready today. We can’t lose in this market. I foresee algos and feds pumping this for months. Makes a bad administration look good. If you’re a bear right now I feel sorry for you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:33:00 </td>
   <td style="text-align:left;"> In the last month $QQQ has a been trading in the 322.94 - 357.50 range, which is quite wide. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:32:42 </td>
   <td style="text-align:left;"> This may be more bearish than any day in history $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:31:59 </td>
   <td style="text-align:left;"> $QQQ where is the Tebow guy? He has vanished from twitter 🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:31:22 </td>
   <td style="text-align:left;"> @MLinv $SPY $QQQ meanwhile we have million+ puts shorting the market every day. 
 
Complacency??? lmao......why is there so much ignorance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:31:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK $TLT $GOLD 

Well, $460 here we come. 
What’s that sideline money going to do now?
Have all the shorts covered yet?
I know bull margin has been steadily increasing each month since January. 
October 2022 was our low. 
It’s time to move and shake again!

https://www.marketwatch.com/story/s-p-500-exits-longest-bear-market-since-1948-what-stock-market-history-says-about-what-happens-next-a336a139 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:30:18 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Big Tech Strikes Back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:30:06 </td>
   <td style="text-align:left;"> $spy Complacency is the greatest enemy of excellence….just wait for it…. if you look closely you can see it coming.. don’t let it happen to you 🆘🚨

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:29:36 </td>
   <td style="text-align:left;"> $TSLA for planning purposes. 🫦 
 
[weekly candles, MAs]. 
 
🎩 
🙌🏻 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:29:22 </td>
   <td style="text-align:left;"> $QQQ losing my god damn mind with this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:29:14 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Bull Market Or Bull Trap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:29:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $DJIA S&amp;amp;P 500 notches highest close for 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:28:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA What a corrupt, POS country this has become at the hands of scumbag Democrats, liberals, Deep State rats, and D.C. careerists.  Selective application of the &amp;quot;law&amp;quot; and &amp;quot;unequitable&amp;quot; investigations.  Need a loose cannon of justice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:27:46 </td>
   <td style="text-align:left;"> Lots and lots of gaps to fill up north.

$TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:25:16 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $SOXS &amp;quot;JP Morgan&amp;quot; is talking down markets, just as &amp;quot;Morgan Stanley&amp;quot; is. All about the disconnect beween the Bond&amp;amp; Equities. &amp;quot;If stock markets trade, as bond markets, the result will be -20%&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:24:36 </td>
   <td style="text-align:left;"> This shows the monthly results from only making a trade when H% is low.
Whats the Win/Lose ratio? The result speaks for itself.

May (&amp;#39;23) = 0 loss
April (&amp;#39;23) = 0 loss
March (&amp;#39;23) = 1 loss
February (&amp;#39;23) = 0 loss
January (&amp;#39;23) = 0 loss
December (&amp;#39;22) = 2 losses
November (&amp;#39;22) = 0 loss
October (&amp;#39;22) = 2 losses

Got timestamps for the skeptics
$SPY $QQQ $COST $TGT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:18:21 </td>
   <td style="text-align:left;"> Let’s party 🎊 🎉  I just read the recession is not coming and the bull market just started.  I know a guy who told me that 9 months ago.  Everyone needs that guy in their life. You got a guy? I got a guy.  $QQQ $CVNA $RMBS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:17:28 </td>
   <td style="text-align:left;"> $QQQ cmon Jpowell you rat dog I expect 355 today minimum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:17:19 </td>
   <td style="text-align:left;"> $SPY $QQQ also low volume Friday.  I guess  it will depend if Tesla keeps pumping or dumps at open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:17:04 </td>
   <td style="text-align:left;"> $QQQ EVERY FUCKING DAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:15:34 </td>
   <td style="text-align:left;"> $QQQ so why the pump now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:10:47 </td>
   <td style="text-align:left;"> $QQQ I’m so sick of this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:09:04 </td>
   <td style="text-align:left;"> I have a scary joke about math, but I&amp;#39;m 2² to say it...

$spy $qqq $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:06:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:06:20 </td>
   <td style="text-align:left;"> $QQQ  Would like to see the trend continue here and a retest to 356-357 supply. Yesterday we revisited the demand area of 346.5-348 and followed with strong technical bounce. Look for a break above 353.75 for confirmation back into supply area. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:05:11 </td>
   <td style="text-align:left;"> Wall Street economists are increasingly less worried about a 2023 recession

https://finance.yahoo.com/news/wall-street-economists-are-increasingly-less-worried-about-a-2023-recession-093041009.html

$QQQ $TQQQ $SQQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:04:09 </td>
   <td style="text-align:left;"> $QQQ real sentiment vs stocktwits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:03:49 </td>
   <td style="text-align:left;"> @GraffGripANW @Rangebound500 at some point you might want to stop losing $$ and learning the truth. Most of that historical PE shit is zero math stupidity pushed from a world that is outdated. 
 
if you think about compounded assets being exponential why the hell are you using a random linear useless number that doesn&amp;#39;t even reflect cash or asset ratios. 
 
If you use 16 PE then at some point the stock market will be 10% of assets while cash/bonds are 90%. 
 
That statement is something no one wants to explain to you. The stupid world of finance uses outdated text books and still draws linear straight lines which is annoying/stupid to the mathematics world. 
 
simple truth, those who wait for 16 PE fail to compound any wealth, live in a broke world and celebrate market proving them right ONCE every 10 years over all. 
 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:02:45 </td>
   <td style="text-align:left;"> $QQQ so many cry baby bitches below , jobs are needed by these people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:02:00 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ  
 
Only one door to escape out of when the alarm goes off. Hope you make it out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:50:27 </td>
   <td style="text-align:left;"> $AMZN MMs crunched the data and found retail holding too many naked calls above 120 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:48:49 </td>
   <td style="text-align:left;"> $SPY $QQQ no relevant catalyst this morning. It seems that the indexes will be move by Tesla and other tech pumping.  Let’s see what WS has in agenda for today.  Good morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:44:34 </td>
   <td style="text-align:left;"> $AMZN amazon news? $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:39:15 </td>
   <td style="text-align:left;"> $SPY $QQQ not too shabby, son. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:36:51 </td>
   <td style="text-align:left;"> $QQQ After what you guys have spent in Ukraine that place better look like Japan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:36:07 </td>
   <td style="text-align:left;"> $QQQ gotta tell you during all those presidential rallys those Ukraine cheers were surely the loudest.....Glad we could pull our gov together for the common cause of....focusing on Ukraine forever.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:35:29 </td>
   <td style="text-align:left;"> $QQQ % of Americans concerned with Ukraine......0% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:34:58 </td>
   <td style="text-align:left;"> $QQQ Could you imagine seeing 1 state&amp;#39;s name in the news as much as we&amp;#39;ve seen the word Ukraine? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:33:48 </td>
   <td style="text-align:left;"> $QQQ We are now the United States of Ukraine News. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:30:41 </td>
   <td style="text-align:left;"> $NIO $TSLA $QQQ $SPY  today , my cat Will most likley give birth to small ragdolls. 👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:27:52 </td>
   <td style="text-align:left;"> $QQQ : Looks bullish right, down it goes though. Just a temp pullback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:23:53 </td>
   <td style="text-align:left;"> $QQQ Yesterday I caught on the news that most of you idiots are giving 20k away to nigerian scammers on Grindr....ya thats a common occurrence so says the news yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:19:46 </td>
   <td style="text-align:left;"> Consumer confidence just tanks’ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:18:58 </td>
   <td style="text-align:left;"> $QQQ the way dems blackout the news channels with their daily dribble points is so awful.  Its like instagram news or something. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:14:46 </td>
   <td style="text-align:left;"> Sunday night Futures $3980’ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:14:12 </td>
   <td style="text-align:left;"> Trade idea --&amp;gt; $LABD 
 
Multiple bottom setup, recently hitting $14+ and then retraced back down to the $12s. 
 
Two levels to watch for buyers to step back in are $12 &amp;amp; $11.60s, ideally, we take a position into the momentum (reversal) 
🎯 - $13+ once in position. 
 
🛑 Stop loss recommendation 5% max  
$SPY $QQQ $TSLA $AI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:14:08 </td>
   <td style="text-align:left;"> $QQQ Funny how crowded the board is with Bears early morning. Life must be too stressful to sleep! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:09:33 </td>
   <td style="text-align:left;"> $QQQ VIX? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:09:13 </td>
   <td style="text-align:left;"> $AGQ $DIA $QQQ $SMH Did you swing trade $AGQ? https://makecashwork.com/trading-leveraged-agq-how-to-lock-in-10-profits-in-just-10-days/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:08:19 </td>
   <td style="text-align:left;"> $SPY $QQQ telling people it’s climate change is getting old especially when you refuse to accept the rise in arson and crime. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:02:05 </td>
   <td style="text-align:left;"> $CVNA I have observed this board extensively over the last day and the general consensus of bulls here is that this should hit $50 today.

The delusion of grandeur is unmatched &amp;amp; uncanny. This amount of idiocracy has never been seen before with this many traders agreeing  in harmony on such an outlandish claim.

$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:56:27 </td>
   <td style="text-align:left;"> $SPY finally a friday with 2% red $QQQ $TSLA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:54:48 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:52:31 </td>
   <td style="text-align:left;"> Dropping levels $SPY $NDX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:43:37 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ  high base </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:41:40 </td>
   <td style="text-align:left;"> Carry  sticking forks in $apple for profits, ditto $dis noise re #APPLEVISIONPRO re due diligence at must read @ https://link.cnbc.com/view/5b19cc6124c17c1ee97e3beeiw9qc.8gs/c938855b $dia $spy $qqq 🐻❤😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:32:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $IWMm All you need to know FAAANMG saving the markets! STRONG LONG FOMO alert is still elevated...WOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:29:58 </td>
   <td style="text-align:left;"> Triple top??? $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:23:22 </td>
   <td style="text-align:left;"> $SPY  $QQQ  if you didn’t start selling yet everything at the top and in middle of this koas your worst manipulating investor ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:22:02 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ $TSLA  I don’t think buy algos can read.  Software tricked into leaking data is bearish. Nvidia software is trashy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:20:56 </td>
   <td style="text-align:left;"> $SPY  can you imagine the whip say on the headlines that hasn’t started test and it’s been hours and there’s billions at stake $QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:18:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA ROMAN REIGNS IS BORING THE BLOODLINE STORY IS DUMB HE NEEDS A STONE COLD STUNNER 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:15:04 </td>
   <td style="text-align:left;"> $QQQ looking good today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:14:55 </td>
   <td style="text-align:left;"> $QQQ please pump into open and 10a come crashing down today... Short the world! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:13:03 </td>
   <td style="text-align:left;"> $SPY  Something manipulated Futures $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:11:27 </td>
   <td style="text-align:left;"> It’s very obvious to us all now the stock market is now manipulated by something. Not it’s clear and obvious $QQQ $SPY $DIA 

This should be down 5% over the day and it hasn’t moved .50’cents.  Pure manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:09:37 </td>
   <td style="text-align:left;"> My provider gave me disney+ for a year for free, that ended a few months ago, rarely used it, not missed, unbelievable share price trades over 70$ 🐻❤😈 https://www.google.com/search?ie=UTF-8&amp;amp;client=tablet-android-samsung-rev2&amp;amp;source=android-browser&amp;amp;q=walt+disney+dis $dis ... $nflx $dia $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:06:42 </td>
   <td style="text-align:left;"> $SPY $QQQ What’s funny to me around this time of day, all the bulls and bears come make their predictions… officially you’ve got a 50/50 chance of being right, a little better if you’re paying attention. 

But somehow a majority are always wrong. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:04:39 </td>
   <td style="text-align:left;"> limit down drop $SPY  $QQQ   Days on end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:02:46 </td>
   <td style="text-align:left;"> $SPY should have a bullish day as the 430+ crowd grows. 

Meanwhile, back at Whacko Ranch where the guilty continue to get a great spin from Fox Fake News anchors, the Teflon frying pan is getting more pitted by the day and getting quite sticky in FLA.

OMG  had to laugh at Levins outcry last night.  That drama queen gets a 10! LOL You&amp;#39;d think that he lost his bed partner.

Oh the outrage displayed there.  We must respect the criminal actions that Trump owns. He made his bed and now he gets to lay in it peacefully as more details seal his fate. He should have kept his mouth shut.

Patience is so hard for so many. Doesn&amp;#39;t matter the venue. Justice is finally moving into 2nd gear.

Will markets care a wit?

Peace to all and have a great day!

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:58:41 </td>
   <td style="text-align:left;"> $qqq check out NNOx.  AI company in MedTech.  Outperforming top AI players </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:56:00 </td>
   <td style="text-align:left;"> $QQQ: Both the short term and long term trends are positive. This is a very positive sign. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:54:34 </td>
   <td style="text-align:left;"> $QQQ No reason for this bullshit to be up again today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:47:17 </td>
   <td style="text-align:left;"> $SPY $QQQ a trillion planets and galaxies and we humans think we are the masters...LOL clowns we are just a spec...a tiny piece of molecules ..get ready they are coming.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:46:42 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while 90% of traders lose.
$FSR vs $SPY

This is why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:34:27 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:28:35 </td>
   <td style="text-align:left;"> Market Volume Barometer 6-08-2023 
Sentiment: LIMBO 
Volume: -16% 
Real Feel: CHILLY 
Cycle: BULLISH II 
Portfolio: LONG 
Next Day Move: SIDEWAYS 
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/ 
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:27:08 </td>
   <td style="text-align:left;"> $AAPL $SPYD $QQQ $NVDA $IWM Inspite of the hype and exaggeration, markets are headed lower on &amp;quot;Hard Landing&amp;quot;. Do remember, the &amp;quot;shit hitting the fan&amp;quot; will be sudden and the draw down will be fast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:22:34 </td>
   <td style="text-align:left;"> $COIN woooooooooooooooow 
RED for the futures $SPY $QQQ. Let&amp;#39;s see $BTC.X in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:21:19 </td>
   <td style="text-align:left;"> $QQQ please for the love of god leave all those bulls trapped now and dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:18:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $TSLA

Markets don&amp;#39;t run on technicals.. They run on greed, fear, fomo, algos, and keywords. If you haven&amp;#39;t heard the news lately apparently aliens are coming to Earth for AI 😆 🤖 👽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:16:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Come on! KEEP BUYING!!! 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:14:26 </td>
   <td style="text-align:left;"> $SPY $QQQ to many bears flipping to BULLSIDE FOMO --maybe a big BULLTRAP setup is happening? Markets may flip back to bear side soon LOL ---Market is messed up :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:10:37 </td>
   <td style="text-align:left;"> $SPY $QQQ Lots of positive news today $CS makes a deal, $tsla GM charge deal, NVDA 1000 and still going strong --- FAAANMMG -- severe fomo people missed the bottom LOL --and VIX got destroyed :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:09:49 </td>
   <td style="text-align:left;"> $AZN AstraZeneca signs $2 billion agreement with Quell to develop cell therapies. $SPY $QQQ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:08:35 </td>
   <td style="text-align:left;"> $VIX $SPY $QQQ $DJIA 

Soon the vix will be at 18-19 and stocks will go much lower. Make sure you’re all vaccinated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:08:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Seriously I need to take out all of the payday loans and go all in on futes because this 4am pump is as certain as a sunrise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:06:30 </td>
   <td style="text-align:left;"> $QQQ DisruptiveTechnology just on here talking to themselves hyping themselves up spamming bullish jargin for an hour lol no actual analytics or anything just word vomit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:02:59 </td>
   <td style="text-align:left;"> $SPY $qqqq Shortie massacre Friday --RIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:00:04 </td>
   <td style="text-align:left;"> $SPY $QQQ V shape intact, and severe FOMO from Institutions alert elevated ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:58:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Who held their short position overnight oh boy..its going to be another bloodbath , short squeeze, margin calls..OH NO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:55:53 </td>
   <td style="text-align:left;"> $SPY $QQQ Lots of BEAR flipping to BULL Side -- time short soon :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:50:51 </td>
   <td style="text-align:left;"> $SPY $VIX $QQQ scam market! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:47:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Short to medium BULLISH EVENT too strong ..not many bears left they flipping to FOMO .oh boy .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:47:23 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ - Q the “that’s not happening” 😵‍💫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:46:29 </td>
   <td style="text-align:left;"> $SPY $QQQ all you need to know been holding V since Oct 2022 bottom..bears look silly ..yes that is how long they been pounding bearish sentiment..EPIC FAIL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:44:54 </td>
   <td style="text-align:left;"> $SPY $QQQ Looks like another BEAR TRAP ..LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:39:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:33:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Recession, rates hike, still paused...for now..shorten..make money till the drop ..easy peasy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:28:09 </td>
   <td style="text-align:left;"> $SPY $QQQ  let&amp;#39;s build some Forrest fire bots ..thanks https://www.youtube.com/watch?v=W5ugoiHDaOA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:27:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA  $NVDA $AMZN

Stock futures slip Thursday night after S&amp;amp;P 500 notches highest close for 2023 https://www.cnbc.com/2023/06/08/stock-market-today-live-updates.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard

Remember, the FEDs not saving the day this time, their objective is lowering inflation. QT continues, and retail pays for the bag. The FED is such a scam. And Joe sucks so bad as president! He can’t even stand or walk!   #America #Crumbling #SAD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:22:53 </td>
   <td style="text-align:left;"> $SPY $QQQ ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:20:34 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:14:00 </td>
   <td style="text-align:left;"> $AMD $QQQ This a millennial memester stock worse than GME and AMC.  Your uniform is ready for pickup losers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:08:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA SEE THEM INDICTMENTS 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:06:43 </td>
   <td style="text-align:left;"> 20 mins YouTube Stock Market Technical Analysis:                                              
https://youtu.be/R_76OIZzEzU 
Subscribe on YouTube for daily market updates &amp;amp; plays 
 
- Tesla Stock TSLA CLEAR 12 EMA 4 hour time frame support guide 
- Nvidia Stock NVDA falling Wedge Guide 
- google Stock GOOGL Lead Bear of big tech bull break with no follow through on Monday 
- Amazon Stock AMZN potential setting a lower high on daily 
- Apple Stock AAPL stronger big tech 2 day time frame EMA 12 perfect support guide 
$SPY $QQQ $SPX $IWM $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:05:13 </td>
   <td style="text-align:left;"> $QQQ Lock up Trump now dirtiest stupid President this country ever had. Only white trash support him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:33:48 </td>
   <td style="text-align:left;"> $AAPL $NVDA $QQQ i&amp;#39;m in tech and don&amp;#39;t believe a word these companies are saying. 
 
Y2K all over again. 
 
RIP Google Glass AI 2.0. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:29:25 </td>
   <td style="text-align:left;"> $QQQ great day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:19:00 </td>
   <td style="text-align:left;"> $QQQ  hey GO FUCK 🖕🏻🖕🏻🖕🏻🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:13:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA THE ALIENS STOPPED IN VEGAS BECAUSE THEY WANTED TO GAMBLE DUH WINNING 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:08:12 </td>
   <td style="text-align:left;"> $QQQ crazy how the dollar is even holding up even after everybody talking about 3% being the new inflation target, soon itll be 4% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:06:35 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:00:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $NVDA $TSLA 

How tf is NQ1 already up 1.20% since last closing?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:58:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:57:24 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $SQQQ I’ve been monitoring the AAII weekly survey for years. Sentiment shifts like this do not occur often.

The narrative that the market is too bearish is behind us for now… which from a positioning standpoint can be contrarian, but also means there is a lot of money that can enter the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:51:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X mark this post kids 
the yen crashes soon, or we do 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:47:35 </td>
   <td style="text-align:left;"> $SPY $QQQ lolllllllllll 

https://www.espn.com/nfl/story/_/id/37821339/garett-bolles-russell-wilson-critics-eat-crow-2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:38:39 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - U.S. Weekly FundFlows Insight Report: Conventional Investment Grade Funds Attract Largest Weekly Inflow Of 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:32:03 </td>
   <td style="text-align:left;"> $SPY $QQQ In retaliation for Jabba indictment Repubes vow to boycott Congressional Softball game?

They should the outraged yet it is crickets from the spineless poofdas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:24:29 </td>
   <td style="text-align:left;"> $QQQ please go 357 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:21:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:19:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $TQQQ $IMW Biden found to have accepted over 10m from foreign entities in exchange for policy changes. Time to indict Trump, light the fires, talk about aliens.... Its getting old. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:13:05 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ - and these low iq chit heads still have the nerve to criticize Trump - talk about being in a GAY cult </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:12:39 </td>
   <td style="text-align:left;"> $SPY $QQQ Bear market canceled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:10:07 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ - why ? 🤔🤷‍♂️ I thought they like making loans </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:08:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $TMF $USO 
 
China&amp;#39;s Producer Price index just came in at -4.6% for May, beating -4.3% expectations. This type of price deflation by manufacturers is not what commodity/oil bulls and China reopening bulls want to see. 
 
But it should be good for lower US inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:59:28 </td>
   <td style="text-align:left;"> $SPY $QQQ Zimbabwe, NoKorea, and Venezuela look like they have more legitimate/truthful Govts than the Current USSA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:50:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X MMs the next few weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:47:26 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ 🔴 Market Parties like it&amp;#39;s 2008 |  A little late tonight but I had a friend pop by | That big resistance is in sight... I can&amp;#39;t wait 🤭  
 
https://youtu.be/eedLQwPdRmE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:47:26 </td>
   <td style="text-align:left;"> $QQQ 
 
Interesting selloff with google yesterday. Didn’t break big bear level under 346.7 and now semi bullish over the 200EMA. If 355 breaks tomorrow will long towards 358-360 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:45:45 </td>
   <td style="text-align:left;"> Daily Watchlist!

$SPY $TSLA $QQQ $NVDA $BA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:39:40 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ - a few moments later …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:37:16 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Anatomy Of A Recession Update: U.S. Labor Market Cracks Emerging? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:36:41 </td>
   <td style="text-align:left;"> $QQQ bye felicia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:31:06 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ - I’m fucking dying 😂😂😂 - I identify as trans late ⏰ that is someone who is late but identifies as on time . 

https://twitter.com/cadence4trump/status/1666467526216417280?s=46&amp;amp;t=A6mr-JsI6_Tnk3qqOvXORQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:20:44 </td>
   <td style="text-align:left;"> $AAPL the company that thinks people are going to pay $3500 to walk around town with VR headsets on is carrying the whole market.

They have jumped the shark. Cash out.

$QQQ $NVDA 

Collapse is inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:19:33 </td>
   <td style="text-align:left;"> $SPY $QQQ futes fuckin rippin. Told you. Did you listen? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:16:16 </td>
   <td style="text-align:left;"> $SPY $QQQ the most prosperous country in the world has not started talking about aliens in the White House and the main stream media. Where did things go wrong? Genz is screwed… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:15:07 </td>
   <td style="text-align:left;"> $NIO $QQQ Pre~market updates. NIO. https://pre-market-updates-analysis.blogspot.com/2023/06/nio-and-qqq-updates.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:13:51 </td>
   <td style="text-align:left;"> $SPY  $qqq  just when were making progress against the trans lgbtq crowd Garth Brooks comes out as pro woke and pro bud light </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:12:29 </td>
   <td style="text-align:left;"> ETF Sentiment: $QQQ is the #2 ETF that institutions are trading with 282.9K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:12:14 </td>
   <td style="text-align:left;"> $SPY  $qqq makes me wonder if cramer knows about cash or money markets..  theres such a thing as NOT being in stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:12:11 </td>
   <td style="text-align:left;"> $spy $qqq $tsla

so buffett says there are gonna be amazing investment opportunities due to folks doing stupid things with their money. did he mean because they aren’t buying calls or not holding enough cash / preserving capital? hard to tell haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:05:52 </td>
   <td style="text-align:left;"> $TSLA “GM and Ford supercharging network” 🤣 $SPY $QQQ https://twitter.com/squawksquare/status/1666933564263333889?s=12&amp;amp;t=bB0_ZKAEkBmXPJsLYmyBtQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:05:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $META $NVDA 

OI at close today - way too many calls 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:04:46 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - U.S. Household Wealth Rose $3tn In The First Quarter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:03:41 </td>
   <td style="text-align:left;"> $NQ_F $QQQ Ehaustion price pattern (red dot) pre-market yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:58:23 </td>
   <td style="text-align:left;"> $TSLA fought “the left” and lost NPR on Twitter $SPY $QQQ https://twitter.com/npr/status/1646138100035272704?s=12&amp;amp;t=bB0_ZKAEkBmXPJsLYmyBtQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:56:34 </td>
   <td style="text-align:left;"> $QQQ $SPY https://thehill.com/policy/defense/4041030-taiwan-air-defenses-activated-chinese-military-aircraft/amp/ 
 
 
Every day I read articles like this. Something is going on between these 2 countries that can’t be ignored. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:56:20 </td>
   <td style="text-align:left;"> $TSLA desperate call and make Twitter cash flow positive… maybe just thinking to pump and dump more Tesla shares? $SPY $QQQ https://twitter.com/elonmusk/status/1666945495334256642?s=12&amp;amp;t=bB0_ZKAEkBmXPJsLYmyBtQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:55:36 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:53:18 </td>
   <td style="text-align:left;"> $SPY $QQQ from ABC news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:53:00 </td>
   <td style="text-align:left;"> $QQQ is currently trading near its 52 week high, which is a good sign. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:52:33 </td>
   <td style="text-align:left;"> $QQQ futes up bigly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:51:53 </td>
   <td style="text-align:left;"> $QQQ yes futes green! Nothing to see here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:47:02 </td>
   <td style="text-align:left;"> $SPY Losten, I just need the $QQQ to hit 359, which is six more than we have now. And if it doesn&amp;#39;t, there&amp;#39;s nothing wrong with recalculating it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:44:40 </td>
   <td style="text-align:left;"> $QQQ There&amp;#39;s still one more leg higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:44:18 </td>
   <td style="text-align:left;"> $BTC.X WE ARE ENTERING AN UNPRECEDENTED DEBT CRISIS! | RAY DALIO
https://youtube.com/shorts/L2aHgyw5q78?feature=share
$SPY $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:42:43 </td>
   <td style="text-align:left;"> $QQQ 359 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:32:17 </td>
   <td style="text-align:left;"> @mikesmic @sizzlemytits @HugZnotDrugZz not sure about that kind of gorilla math, but $TQQQ puts are going to light up like the 4th. I’m in for Sept and will load on Dec if $QQQ moves up in July. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:27:27 </td>
   <td style="text-align:left;"> $SPY $qqq  coffee means nothing oil and copper say it all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:25:09 </td>
   <td style="text-align:left;"> $SPY  $qqq you would think CNN would try to lie better than calling the start of a new bull market the day before a recession collapse happens .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:20:22 </td>
   <td style="text-align:left;"> $DWAC $QQQ $SPY $TSLA Whoa good one I&amp;#39;m laughing so hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:17:54 </td>
   <td style="text-align:left;"> $DWAC Obese Orange needs to inquire about toupees available in the slammer $SPY $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:17:42 </td>
   <td style="text-align:left;"> $SPY  $QQQ   happy YahWeh Month . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:17:00 </td>
   <td style="text-align:left;"> $SPY next week is going to be something else. With a Market overvalued on Hype &amp;amp; now at the top we have the Fed, Treasury &amp;amp; now a bunch of poorly educated cult members looking to act up so,.. Where was the VIX? where was the hedges?,... they&amp;#39;re coming! :o) 
 
$aapl $qqq $tsla $nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:16:25 </td>
   <td style="text-align:left;"> Looks like we want to further squeeze shorts and reach all time highs. We are not out of the woods yet tho! $SPY $QQQ $AAPL  https://www.youtube.com/watch?v=P5mgvlo_Xdc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:15:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

What the frack, there’s an actual ticker called $MOON 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:13:52 </td>
   <td style="text-align:left;"> $SPY $QQQ

change the ticker $TSLA to $MOON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:13:50 </td>
   <td style="text-align:left;"> $SPY  The Futures officially broken  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:11:33 </td>
   <td style="text-align:left;"> $QQQ WS knows everything is so fked up. Yet they purposely prop up the market. Pretty sure they will reverse this really hard but it’s hard to catch the top. Musical chair. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:09:07 </td>
   <td style="text-align:left;"> $SPY $QQQ almost nothing to like about the USA right now...every day seems worse than the last </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:08:07 </td>
   <td style="text-align:left;"> $SPY  $QQQ  My friend, the communist 
Holds meetings in his RV 
I can&amp;#39;t afford his gas 
So I&amp;#39;m stuck here watching TV !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:07:42 </td>
   <td style="text-align:left;"> $SPY $QQQ The key takeaway from the Initial jobless claims  report is the bump seen in initial claims indicates some softening in the labor market, although claims levels continue to run well below levels seen in past recessions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:07:12 </td>
   <td style="text-align:left;"> $AAPL $LCID $QQQ $RIVN $TSLA who the duck cares.  This is AAPL board </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:06:53 </td>
   <td style="text-align:left;"> $QQQ debt crisis: check  
wealth gap: check  
Populism taking over this country: check 
 
Beautiful job J powell, nobody does it like you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:06:46 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

$400+! Don’t bet against elon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:05:15 </td>
   <td style="text-align:left;"> $QQQ  $Spy $goof $appl

I told everyone on here Wallstreet is the devil. They aren&amp;#39;t going to give retail 5% while waiting on a recession.  I knew the markets are going much higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:04:48 </td>
   <td style="text-align:left;"> $QQQ $SPY All a bunch of horseshit selective prosecution of a political opponent.  Harbinger of bad things to come this is kicking a hornet&amp;#39;s nest.  Grandpa scared to death of actually having to run against the Don and form sentences and such. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:03:42 </td>
   <td style="text-align:left;"> $QQQ $SPY $appl $goog ALL longterm indicators have reversed Bullish.Igf your short Good Luck! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:59:16 </td>
   <td style="text-align:left;"> Now clearly we all can see market is being manipulated pretty obvious 
$QQQ $NDX $SPY $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:58:57 </td>
   <td style="text-align:left;"> $SPY $QQQ safe to say interest rate increases haven’t done a single thing 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:58:15 </td>
   <td style="text-align:left;"> $SPY BREAKING: Politico Reports That Biden A ’70% Favorite To Win’ 2024 Presidential Election Now That Main Political Opponent To Be Arrested. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:57:53 </td>
   <td style="text-align:left;"> $lcid Lucid Motors already have world class EV tech. They should really execute strategically to grow while controlling cost. China news is very big and promising. Apple and Tesla make most profit out of China production as labor and other cost is cheaper.  
 
Lucid current market cap 13 BN can grow over 100 bn, if they execute well over next 3-5 years.  
 
$tsla $rivn $qqq $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:57:40 </td>
   <td style="text-align:left;"> $GAN  Clear takeover target—matter of who/when—not if. $QQQ $RICK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:57:00 </td>
   <td style="text-align:left;"> $NVDA $QQQ $SPY what bull flag on the NVDA…would be shocked if we don’t see a breakout tomorrow. 💪

This is what you write home to mom about.  🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:56:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $TNX $UUP $VIX what did people do with the forbearance savings. They piled on more credit card debt, mortgages, and auto loans. So not only are people not going to have the $398 (average debt payment) monthly stimulus. They are looking at further personal budget deficits because they piled on more debt over this time period. This is very material for the US consumer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:55:15 </td>
   <td style="text-align:left;"> $SPY $QQQ futures dumping faster than the Mar-a-Lago pool ahead of an FBI search warrant

https://www.salon.com/2023/06/06/very-suspicious-experts-skeptical-after-employee-drains-pool-into-mar-a-lago-server-room/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:53:10 </td>
   <td style="text-align:left;"> $DIS  We are up 4% already. 
*I&amp;#39;m gonna add some swing plays on this ticker tomorrow if you guys are interested* 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:51:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT NBER created a research paper on the effects of the debt moratorium. Which concludes at the end of August. The excerpt is the summation for those who choose to get to the point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:50:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM how high will we gooo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:50:19 </td>
   <td style="text-align:left;"> $TOP volume on watch for tomorrow 🇨🇳📰💰

$SPY $CJET $BOAS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:49:16 </td>
   <td style="text-align:left;"> $QQQ can bear market really end without a single  limit down days? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:48:08 </td>
   <td style="text-align:left;"> $SPY $QQQ &amp;quot;It&amp;#39;s Really Unprecedented&amp;quot;: Solar Power Generation Cut In Half Due To Canada Smoke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:48:08 </td>
   <td style="text-align:left;"> $XBI $IBB $SPY $QQQ.  IBRX Three insiders bought the stock this week!  One was ex cia leader under Obama and BOD John Brennan 🤔🤔.  https://www.linkedin.com/posts/immunitybio_cancer-activity-7072242911928614913-VMV_?utm_source=share&amp;amp;utm_medium=member_ios </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:47:33 </td>
   <td style="text-align:left;"> $SPY $qqq I THINK CNN IS THE SPAWN OF SATAN  . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:47:09 </td>
   <td style="text-align:left;"> $SPY https://www.multpl.com/s-p-500-pe-ratio $QQQ Good times... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:47:04 </td>
   <td style="text-align:left;"> $QQQ markets crave stability, a political indictment of an ex president= instability. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:45:46 </td>
   <td style="text-align:left;"> $SPY $QQQ https://www.zerohedge.com/political/trump-i-have-been-indicted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:44:46 </td>
   <td style="text-align:left;"> $spy $qqq  if you’re in real-state , appraiser, or loan originator you’ve already been in a severe recession for 9 months ! .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:43:33 </td>
   <td style="text-align:left;"> $QQQ mainstream media announcing new bull market. 🤣 They’re preparing for the dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:42:32 </td>
   <td style="text-align:left;"> $SPY $QQQ BULLISH? 
I wouldn’t think so … but Ai is retarded

https://www.zerohedge.com/political/trump-i-have-been-indicted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:42:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUM $DWAC I realize many will be hesitant to boycott the most popular tech giants.   
But considering those who have fought and died worldwide for freedom,INCLUDING FREEDOM OF SPEECH, I don&amp;#39;t believe it is such a big sacrifice and these are immediate,peaceful actions anyone can take to counter censorship and corruption WITHOUT waiting for politicians to do something. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:42:03 </td>
   <td style="text-align:left;"> $SPY  $QQQ  
 
Today&amp;#39;s Headlines&amp;gt;&amp;gt;&amp;gt; 
 
&amp;quot;Stocks rise, S&amp;amp;P 500 enters new bull market: Stock market news today&amp;quot; 
 
Carefull ..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:39:51 </td>
   <td style="text-align:left;"> $QQQ Guy updates on SPY chart https://youtu.be/VWYLOOYhUUw $GOOG $AAPL 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:38:45 </td>
   <td style="text-align:left;"> $SPY $QQQ just remember the feeling of when you lost money and never forget it. If you&amp;#39;re up on positions don&amp;#39;t forget how much it sucks losing money. For me, I forget the emotional pain over time on winning streaks and start increasing risk profile without a plan before putting on a trade. Gotta know your weaknesses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:33:54 </td>
   <td style="text-align:left;"> $TSLA $QQQ 
 Mother of all melts up is coming very soon! 
Very </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:29:35 </td>
   <td style="text-align:left;"> $SPY $QQQ usually when u start screenshotimg your profits its about to turn for the worse. I see a lot of bullish screenshots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:28:15 </td>
   <td style="text-align:left;"> $spy $qqq ok one last pump 🥹🚀🚀🚀🚨 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:27:37 </td>
   <td style="text-align:left;"> $QQQ stay disciplined. 

HOW TO BECOME SUPER DISCIPLINED - Jordan Peterson Motivational Speech 2023
https://youtu.be/-a10xQRUL-E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:26:02 </td>
   <td style="text-align:left;"> TRUMP INDICTMENT

1. Willful retention of NDI (Espionage Act)
2. Conspiracy to obstruct justice
3. Withholding a document or record
4. Corruptly concealing a document or record
5. Concealing a document in a federal investigation
6. Scheme to conceal
7. False statements and representations

If found guilty:
- Minimum sentence: None
- Maximum sentence: 100 years in prison $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:25:26 </td>
   <td style="text-align:left;"> It’s won’t drop $100 tonight $SPX  because it’s going down $255 Friday    $QQQ $NDX $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:23:49 </td>
   <td style="text-align:left;"> $SPY $QQQ futures red at this hour. Maybe it has to do with the worst than expected Chinese CPI.  We will see how things change overnight.  GN bulls and bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:20:50 </td>
   <td style="text-align:left;"> $SPY $QQQ gen z . Please don&amp;#39;t normalize drinking like these boomers do. It&amp;#39;s absolutely poison </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:17:36 </td>
   <td style="text-align:left;"> $QQQ this move today was on such light volume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:17:24 </td>
   <td style="text-align:left;"> $SPY $QQQ I&amp;#39;m not drinking tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:17:14 </td>
   <td style="text-align:left;"> $SPY $QQQ 🤡🤡🤡 did it again deleted all tweets for the second time in a month after calling tops and bear flags every day. Broke and depressed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:16:12 </td>
   <td style="text-align:left;"> $TSLA $DWAC $CVNA $SPY $QQQ  
Trending... like a boss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:16:09 </td>
   <td style="text-align:left;"> $SPY $QQQ  trading advice
Don&amp;#39;t listen 2 women 😤 💯💯💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:13:42 </td>
   <td style="text-align:left;"> $SPY $QQQ just pull the damn rug already and chill with the microscopic pullbacks. $NVDA $META $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:13:37 </td>
   <td style="text-align:left;"> $SPY  $QQQ  DON&amp;#39;T FORGET TO KEEP CELEBRATING YAHWEH MONTH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:11:22 </td>
   <td style="text-align:left;"> $SPY $QQQ can&amp;#39;t even imagine how many people have some insane gains not closed out. Protect yourself and screw what everyone else is doing. Congrats if you&amp;#39;ve banked but don&amp;#39;t overstay ur welcome. WS is savage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:09:51 </td>
   <td style="text-align:left;"> $CVNA You know it is time to go all in with short position when bulls come out with their outlandish price targets of $50, $100, $150 or $1000

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:08:38 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla $meta $aapl 
 
NEXT WEEK GOING to be volatile as FED MEETING on Thursday! 
 
Canada &amp;amp; Australia - Hike Rates.  US will HIKE TOO 
 
TAKE PROFIT and WAITING ON SIDELINE to see what feds decision!!! 
 
We might see MASSIVE PROFIT TAKING from TOMORROW Until Thursday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:05:19 </td>
   <td style="text-align:left;"> $SPY latex365c35417969a7170c75a931b84ba0e1TSLA 250c &amp;gt; 248.85 | 240p &amp;lt; 242.21

$NVDA 390c &amp;gt; 388.50 | 380p &amp;lt; 383.65 

If you want option trade alerts, with set ups like this check the l!nk out! 

The team is banking on a daily basis 🥂✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:01:58 </td>
   <td style="text-align:left;"> $SPY $QQQ so many insiders sell after the massive rise this year. They know what’s coming so they sell while retailers buy in. $NVDA $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 10:01:03 </td>
   <td style="text-align:left;"> $SPY the greatest trick the stock market has is lulling you into complacency $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:59:52 </td>
   <td style="text-align:left;"> $SPY quite the volatility crush. Went on longer than I anticipated. Major reversal likely soon $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:58:25 </td>
   <td style="text-align:left;"> $SPY since this is mainly multiple expansion... many new investors believe they now understand how to trade the equity markets. $QQQ I don&amp;#39;t think it&amp;#39;s going to be easy for much longer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:57:03 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:56:10 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ aint
No recession. Too many folks spending money every where I go. Sunny DAYGO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:54:55 </td>
   <td style="text-align:left;"> $SPY one of the nastiest things they did (the fed) and funds complicit in 2021 when the market ran up 130% from the Covid low with only tiny pullbacks was they’d let the futures run red almost every night and it would get the hopes up of the shorts and by morning or shortly after open they’d run it up big daily. It’s knocked on 4300 multiple times now past week or so and relentlessly keeps coming back after any dip just like I said it would so barring a real drop like 1-2% tomorrow it likely does the ol vix crush Friday breaks 430-433 atleast briefly and continues Monday before any pullback Monday/Tuesday on fed uncertainty and data. If it opens red tomorrow I will take calls odte and scale in. These -.20 to -.60 down days mean nothing when the market just ran from 389 to 439 in such short time. It’s just games they play to reset rsi and bait in puts. God bless see u tomorrow ❤️🙏🏻🔥 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:54:43 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:54:41 </td>
   <td style="text-align:left;"> $CVNA $QQQ $SPY Pumping attempt by Carvana management to pump price so they can dilute and survive. Retail bulls will pay for it of course. Management understand their meme crowd and are playing it how they should. Money never sleeps 🛏️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:54:30 </td>
   <td style="text-align:left;"> $SPY $qqq All news is baked in!!!!!!!!!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:53:19 </td>
   <td style="text-align:left;"> $SPY $QQQ this little piggy went to the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:52:00 </td>
   <td style="text-align:left;"> $QQQ: Both the short term and long term trends are positive. This is a very positive sign. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:51:26 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm  Breakout Friday in one of these at least. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:51:24 </td>
   <td style="text-align:left;"> $CVNA Horrible interest rate environment with massive debt burden for Carvana. Their last desperate attempt to survive by falsely cooking their books and promising $50m dollars in profit for the second quarter. That doesn’t mean anything even if true. They are in deep trouble and will go bankrupt imminently unless they announce offering soon. A tiny $50m profit will not erase the billions of dollar debt.

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:51:24 </td>
   <td style="text-align:left;"> $META $SPY $QQQ $AAPL $TSLA 
 
ZUCK IS PANICKING!!!  
 
BASHING APPLE VR 
 
WANT TO CREATE STANDALONE to FIGHT TWITTER because he knows he can&amp;#39;t compete with PAPA ELON!!!! 
 
INSTAGRAM PROMOTES PEDO NETWORK 
 
GET FINE 1.3 B in EURO 
 
https://www.wsj.com/articles/meta-reveals-twitter-competitor-it-plans-to-launch-as-stand-alone-app-4a9b7721 
 
SELL META, buy AAPLE, TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:49:55 </td>
   <td style="text-align:left;"> $SPY $QQQ headlines when you Google bull market…these shorts don’t stand a chance.  😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:49:25 </td>
   <td style="text-align:left;"> $QQQ head and shoulders 300 PT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:49:18 </td>
   <td style="text-align:left;"> $QQQ Guy updates on SPY charts https://youtu.be/VWYLOOYhUUw $GOOG $AMZN 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:48:38 </td>
   <td style="text-align:left;"> $SPY $QQQ this headline popping everywhere…and I mean everywhere.  Can you imagine sitting in cash and missing out on where this is headed…wait until fomo starts. 💪

Just Google bull market and look at the headlines 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:48:19 </td>
   <td style="text-align:left;"> $SPY $QQQ so how fat are they going to let big cap tech get? Getting out of control, no? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:42:06 </td>
   <td style="text-align:left;"> $QQQ lol not even budging... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:41:39 </td>
   <td style="text-align:left;"> How To Unlock The Power Of Japanese Candlesticks

https://www.chartlearning.com/2021/04/top-5-bullish-candlestick-patterns.html

$SPY $QQQ $IWM $ES_F $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:40:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:40:55 </td>
   <td style="text-align:left;"> $QQQ when is the correction? I sold most today. I think the correlation is coming soon in days and even it still go up not too much tit could </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:40:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT  
 
The other area where banks are getting liquidity is from the Federal Home Loan Bank. Like the Fed&amp;#39;s BTFP, banks post collateral (like a pawn shop) to secure loans. 
 
Data is quarterly and Q1 2023 finally came out. Over $1 trillion now. Highest level since the GFC. Prior mini spike was during covid. 
 
Interesting times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:39:57 </td>
   <td style="text-align:left;"> $QQQ Got the cup and now building a handle. &amp;quot;A bullish pattern&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:38:09 </td>
   <td style="text-align:left;"> $QQQ Free money Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:36:51 </td>
   <td style="text-align:left;"> $QQQ calls above 353.62
Posted by @macrozz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:36:26 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DJIA $RUT $NASDAQ 

Very much a possibility.  If J. Powell has been hiding the numbers and will only admit to a rate hike AT THE LAST MINUTE during the FOMC next week, we ride. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:35:20 </td>
   <td style="text-align:left;"> $SPY  $QQQ  $IWM  $TSLA  $AMD 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 09:35:15 </td>
   <td style="text-align:left;"> $SINT American mask company selling high quality mask/N95
Washington DC turn to suffer for once 😷! Be safe MASK UP! 
6 mill mc with 16.5 mill of cash on hand! Recent RS stock too! 
$APT $MMM $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:12:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 28.40%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:11:29 </td>
   <td style="text-align:left;"> $AAPL since you dropped &amp;quot;i&amp;quot; for vision pro. Vision pro is individual experience.  Why have you dropped it?  Also price tag is expensive and users are going to be stationary. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:07:52 </td>
   <td style="text-align:left;"> $PLTR quick  summary  of  over  $1 billion  in  sales  this  week!!!    $tsla battery  maker  $pc aka  Panasonic!!!   $msft $AAPL @Pocoyo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:04:46 </td>
   <td style="text-align:left;"> $AAPL $SOFI 

👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:04:10 </td>
   <td style="text-align:left;"> $AAPL more magical delays $META $MSFT https://seekingalpha.com/article/4610418-apple-magical-delays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:01:12 </td>
   <td style="text-align:left;"> 🛑*PUTIN: RUSSIA TO PLACE NUKE WEAPONS IN BELARUS AFTER JULY 7-8❗
https://twitter.com/PaulVikingGlob1/status/1667135168002260992?t=e3fQ2lRL9nuqVgfvBAAb2A&amp;amp;s=19
$TSLA $AAPL $AMZN $NVDA $AMD  VSVZV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:00:20 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : The Fintech Industry Will Be Worth $1.5 Trillion By 2030: 2 Magnificent Stocks to Buy Now https://www.stck.pro/news/AAPL/52580305/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:57:14 </td>
   <td style="text-align:left;"> $AAPL $META 

Already printing 🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:56:41 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s hear the bull case vs bear case </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:55:19 </td>
   <td style="text-align:left;"> $AAPL $AMZN $MSFT $GOOGL $TSLA watch this for motivation.

WHY YOU SHOULD NEVER QUIT - Denzel Washington Motivational Speech 2023
https://youtu.be/RBltxXaxgXI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:52:41 </td>
   <td style="text-align:left;"> $META (-0.6% pre) Meta Reveals Twitter Competitor It Plans to Launch as Stand-Alone App - WSJ

Zuckerberg criticizes $AAPL Apple’s Vision Pro headset, saying Meta has tried to make products affordable

https://openoutcrier.com/l/1686311553377408 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:45:49 </td>
   <td style="text-align:left;"> $META $AAPL Meta&amp;#39;s Zuckerberg addresses Apple&amp;#39;s Vision Pro at meeting, The Verge reports 
 
Meta CEO Mark Zuckerberg addressed Apple&amp;#39;s Vision Pro headset at a meeting on Thursday, telling employees that it &amp;quot;could be the vision of the future of computing, but like, it&amp;#39;s not the one that I want,&amp;quot; The Verge&amp;#39;s Alex Heath reports. He also pointed to the fact that Meta&amp;#39;s upcoming Quest 3 headset will be much cheaper, at $499 compared to the Vision Pro&amp;#39;s $3,499 price tag, saying that &amp;quot;I think that their announcement really showcases the difference in the values and the vision that our companies bring to this in a way that I think is really important.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:45:24 </td>
   <td style="text-align:left;"> $AAPL time for this to run back up and hold gains like Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:40:58 </td>
   <td style="text-align:left;"> $META $AAPL 

Ok, Zuckerberg....

I suppose you envisioned all of us standing in the kitchen.

Not the couch! That would be a VR crime, lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:38:45 </td>
   <td style="text-align:left;"> My alerts for LARGE caps.This shows the result of ONLY buying when H% is low.
I have timestamps + buy fills for everything

$TSLA + $AAPL + $NKE are just few of many I&amp;#39;ve traded. $SPY 
I don&amp;#39;t make 100s of trades. I only buy when I get a confirmation. Ask me for the receipts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:37:21 </td>
   <td style="text-align:left;"> $AAPL time to step up apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:36:36 </td>
   <td style="text-align:left;"> $TSLA the new $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:32:00 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - 3 Semiconductor Stocks That Could Skyrocket in the Next 12 Months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:28:51 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #5 stock that institutions are trading with 41.2K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:25:16 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $SOXS &amp;quot;JP Morgan&amp;quot; is talking down markets, just as &amp;quot;Morgan Stanley&amp;quot; is. All about the disconnect beween the Bond&amp;amp; Equities. &amp;quot;If stock markets trade, as bond markets, the result will be -20%&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:21:05 </td>
   <td style="text-align:left;"> $AAPL enters bullish trend https://srnk.us/go/4713757 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:18:44 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple, AI, Metaverse: Meta&amp;#39;s Identity Crisis Is Getting Worse Not Better. https://www.stck.pro/news/AAPL/52579783/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:17:23 </td>
   <td style="text-align:left;"> $AAPL 🆘just look at that 6 month graph of sweet price!!🆘
u short sellers/shorting entities etc are idiots ..
300 shares bought in 1987 are now 67,000 due to splits
12,060,000 bucks now
young folks should buy n hold …dividends are nice as well🏌️‍♂️⛳️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:12:01 </td>
   <td style="text-align:left;"> $AAPL 👁💚🍏⛳️🏌️‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:10:45 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$LCID vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:06:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:00:49 </td>
   <td style="text-align:left;"> 3 Mid Caps You Haven&amp;#39;t Heard Of But Need To Know About $AAPL https://www.marketbeat.com/originals/3-mid-caps-you-havent-heard-of-but-need-t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 18:40:13 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 18:24:39 </td>
   <td style="text-align:left;"> $AAPL $META  latexed2b778936329e84cd326f912790bbcd$ success, $$ privilege = running over inferior humans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 18:14:07 </td>
   <td style="text-align:left;"> $AAPL under 80 coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:58:45 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : NVDA to META: Insiders Capitalise on Tech Stocks Surge https://www.stck.pro/news/AAPL/52573454/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:54:48 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:50:52 </td>
   <td style="text-align:left;"> $AAPL Green or Red today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:45:33 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #5 ticker with sweep activity where institutions are trading options urgently with 29.3K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:42:51 </td>
   <td style="text-align:left;"> DIA DIS SPY QQQ $aapl  ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:34:46 </td>
   <td style="text-align:left;"> My track record for CHIP stocks. I have timestamps + buy fills for everything. What&amp;#39;s my win rate? 

My trading strategy is to buy the dip when Algos are tired of selling. I buy when &amp;quot;Heaviness %&amp;quot; by Algos is low. 

$NVDA + $AMD + $QCOM + $MU + $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:10:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 8.03%. $AAPL outperforms 93% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:04:01 </td>
   <td style="text-align:left;"> $AAPL vision pro bullshit price and ugly gimmick . Shorting PT 50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:03:38 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple&amp;#39;s Face Computer, Crypto Chaos and How Teens Really Feel About Social Media https://www.stck.pro/news/AAPL/52570055/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:55:50 </td>
   <td style="text-align:left;"> $DOCU standouts , why it caters to non corporate mainly small to medium size businesses that can&amp;#39;t afford the hefty SUB cost by$msft $AAPL $ADBE .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:46:42 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while 90% of traders lose.
$FSR vs $SPY

This is why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:44:24 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:27:08 </td>
   <td style="text-align:left;"> $AAPL $SPYD $QQQ $NVDA $IWM Inspite of the hype and exaggeration, markets are headed lower on &amp;quot;Hard Landing&amp;quot;. Do remember, the &amp;quot;shit hitting the fan&amp;quot; will be sudden and the draw down will be fast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:22:17 </td>
   <td style="text-align:left;"> $aapl $dis $TSLA $F $wmt and more Excellent, welcome to crash Friday.  
Enjoy the Armageddon Autogeddon Recession.  
🐻❤😈💲💰🤑✔ 
TOP 10 AT: ▪TRADING ECONOMICS tradingeconomics.com ▪REUTERS U.S. MORNING BID ▪ WSJ MARKETS A.M. ▪WSJ REAL TIME ECONOMICS ▪YAHOO FINANCE MORNING BRIEF ▪JOHN KEMP ENERGY jkempenergy.com/ + REUTERS: Oil prices looked set to post their second straight weekly loss as prices continued to fall over demand concerns and skepticism that the United States and Iran could strike a nuclear deal. ▪TODAY&amp;#39;S WSJ PRINT EDITION 
https://wsjtodaysedition.cmail19.com/t/d-e-vblhjk-judrvtlm-r/   ▪CNBC DAILY OPEN 
https://link.cnbc.com/public/31739636  
▪CNBC BEYOND THE VALLEY 
https://link.cnbc.com/public/31739634   
▪REUTERS EU MORNING BID 
https://newslink.reuters.com/public/31739605  ▪TODAY&amp;#39;S WSJ HEADLINES 
https://intodayspaper.cmail20.com/t/d-e-vbljg-jidrghyo-r/  
▪FUTURES https://www.investing.com/indices/indices-futures 
▪FINVIZ https://finviz.com/news.ashx#  
▪🇨🇦 forest fire update @ https://ca.news.yahoo.com/wildfires-canada-south-africa-edmonton-airport-firefighters-040321703.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:21:22 </td>
   <td style="text-align:left;"> $AAPL average is at 155 why would you purchase at 180???? $VIX also prepared explode up around 18-19, Apple will get sledge hammered lower when that happens, Apple worth 160 if that happens (closer with the average) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:51:17 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Meta&amp;#39;s Zuckerberg shakes off Apple Vision Pro: report https://www.stck.pro/news/AAPL/52564995/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:50:27 </td>
   <td style="text-align:left;"> $AAPL 174 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:39:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:18:34 </td>
   <td style="text-align:left;"> $AAPL $META the more I read about visionpro, the more i want one. 
 
...zucks lost this one imo,.. even before it&amp;#39;s available. 
 
(Both stonks will likely do well regardless). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:16:37 </td>
   <td style="text-align:left;"> Result of ONLY buying when H% is low. Small + Mid cap edition.

$SPY $TSLA $AAPL $MULN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:07:12 </td>
   <td style="text-align:left;"> 20 mins YouTube Stock Market Technical Analysis:                                              
https://youtu.be/R_76OIZzEzU 
Subscribe on YouTube for daily market updates &amp;amp; plays 
 
- Tesla Stock TSLA CLEAR 12 EMA 4 hour time frame support guide 
- Nvidia Stock NVDA falling Wedge Guide 
- google Stock GOOGL Lead Bear of big tech bull break with no follow through on Monday 
- Amazon Stock AMZN potential setting a lower high on daily. 
- Apple Stock AAPL stronger big tech 2 day time frame EMA 12 perfect support guide 
$AAPL $AMZN $MSFT $META $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:33:48 </td>
   <td style="text-align:left;"> $AAPL $NVDA $QQQ i&amp;#39;m in tech and don&amp;#39;t believe a word these companies are saying. 
 
Y2K all over again. 
 
RIP Google Glass AI 2.0. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:21:23 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : The “Magnificent 7” – mega-tech stocks that led the market higher https://www.stck.pro/news/AAPL/52559221/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:20:36 </td>
   <td style="text-align:left;"> @J0hnCandleW1ck yes on $tsla put are worthless

Not $meta 
. Puts very much alive 

Sell meta buy tsla or $aapl 

Meta is promoting pedo network ewwww </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:06:35 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:01:30 </td>
   <td style="text-align:left;"> $TSLA puts are worthless now 

$spy $aapl $meta $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:00:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $NVDA $TSLA 

How tf is NQ1 already up 1.20% since last closing?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:58:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:40:39 </td>
   <td style="text-align:left;"> $CVNA FED will ease by end of year! 
https://truflation.com/ 
Carvana will be $180 by that time and $360+ in next year! 
$AMZN $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:34:13 </td>
   <td style="text-align:left;"> $AAPL $AHI 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:32:49 </td>
   <td style="text-align:left;"> $AMC and $AAPL should engage in a joint venture and offer all of AMC&amp;#39;s movie content on the Apple ProVision headset. This way, AMC can save billions of USD on physical theaters. As for AMC&amp;#39;s profitable popcorn sales, they can utilize Doordash for the delivery of beverages and snacks (including popcorn). By taking these steps, the company should become profitable in less than two years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:29:14 </td>
   <td style="text-align:left;"> $spy $aapl $nvda $meta $goog

Yup!!!

https://www.cnbc.com/2023/06/09/ubs-strategist-theres-too-much-risk-in-big-tech-right-now-heres-where-to-invest-instead.html?__source=androidappshare

Sector rotation is coming... Many sold faang stock and buying other sectors..m

Beware for those still holding, take profit and buy at lower price... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:21:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:20:41 </td>
   <td style="text-align:left;"> SweepCast ⚡ Unusual Options Detected: $AAPL with Unusual Options Activity Alerted on $185 CALL Expiring: 12-15-2023 worth 69K🐂 |🥇 Start Using SweepCast! @SweepCast  🥇 | </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:55:09 </td>
   <td style="text-align:left;"> $AAPL still holding 25yrs later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:25:06 </td>
   <td style="text-align:left;"> $TSLA 👈 Tesla to make 25 Billion alone in super charging revenues. $SPY $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:23:01 </td>
   <td style="text-align:left;"> $AAPL Hard to be bullish here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:20:44 </td>
   <td style="text-align:left;"> $AAPL the company that thinks people are going to pay $3500 to walk around town with VR headsets on is carrying the whole market.

They have jumped the shark. Cash out.

$QQQ $NVDA 

Collapse is inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:13:39 </td>
   <td style="text-align:left;"> $AAPL 
 
Levels and how they’ve played out all week, calls broke early Monday but sold off back into the range, failed to break downside of 177.5 got bought up today. More upside over 182. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:06:00 </td>
   <td style="text-align:left;"> $AAPL has a good Piotroski-F score of 7.00. This indicates a good health and profitability. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:01:05 </td>
   <td style="text-align:left;"> @deltax10 

couldn’t agree more. holding t-bills, $nu shares (dirt cheap &amp;amp; warren buffett backed), &amp;amp; the rest cash. the fib retracement sequence on every tech stock (except $aapl &amp;amp; slightly latex45db8a3a2026f157f1e0c6f18dd019d7SPY latex125ff9b4045585e8f05dd0b62c7c6f0cAAPL 8 wins + NT / 0 loss
$PARA 7 wins + NT / 0 loss

I don&amp;#39;t make 100s of trades. I only buy when I get a confirmation. Ask me for the receipts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:23:10 </td>
   <td style="text-align:left;"> $AAPL $IMMR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:17:00 </td>
   <td style="text-align:left;"> $SPY next week is going to be something else. With a Market overvalued on Hype &amp;amp; now at the top we have the Fed, Treasury &amp;amp; now a bunch of poorly educated cult members looking to act up so,.. Where was the VIX? where was the hedges?,... they&amp;#39;re coming! :o) 
 
$aapl $qqq $tsla $nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:16:25 </td>
   <td style="text-align:left;"> Looks like we want to further squeeze shorts and reach all time highs. We are not out of the woods yet tho! $SPY $QQQ $AAPL  https://www.youtube.com/watch?v=P5mgvlo_Xdc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:14:54 </td>
   <td style="text-align:left;"> $AAPL lovely day for Apple shareholders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:11:23 </td>
   <td style="text-align:left;"> $AAPL $AMD $AMZN How much do you dedicate? Hope you at least spend the 2 mins reading the OP Wire sent each morning 90 mins before the bell…. 😏📈

https://www.instagram.com/reel/CrZyq0Ku-bo/?igshid=YmMyMTA2M2Y= </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:07:12 </td>
   <td style="text-align:left;"> $AAPL $LCID $QQQ $RIVN $TSLA who the duck cares.  This is AAPL board </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:06:34 </td>
   <td style="text-align:left;"> $AAPL Dystopia is coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:04:57 </td>
   <td style="text-align:left;"> $AAPL it’s due to rip. I don’t know for how long. But this is a juicy ass setup. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:04:16 </td>
   <td style="text-align:left;"> $BA Trading Top Range Could B/O if $DIA Up 

$SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:57:53 </td>
   <td style="text-align:left;"> $lcid Lucid Motors already have world class EV tech. They should really execute strategically to grow while controlling cost. China news is very big and promising. Apple and Tesla make most profit out of China production as labor and other cost is cheaper.  
 
Lucid current market cap 13 BN can grow over 100 bn, if they execute well over next 3-5 years.  
 
$tsla $rivn $qqq $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:50:24 </td>
   <td style="text-align:left;"> $HOOD app on $AAPL  Vision Pro will be 🔥 🔥 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:49:10 </td>
   <td style="text-align:left;"> $AAPL They release content on goggles. SELL! Yawn ok, next day, I will buy this dip right here $178.20. Well look at that back into $180s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:39:51 </td>
   <td style="text-align:left;"> $QQQ Guy updates on SPY chart https://youtu.be/VWYLOOYhUUw $GOOG $AAPL 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:28:25 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #5 stock that institutions are trading with 41.2K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:27:06 </td>
   <td style="text-align:left;"> $PLTR $PC aka $tsla battery maker!!!  $aapl Titan needs BATTERIES!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:25:52 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy Jun 16, 2023 $182.5 Calls 
Entry Price: $1.49 - $1.49 
Exit Price: $1.68 
Stop Loss: $1.41 
Potential ROI: 13% 
Estimated Hold Time: 70 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:24:32 </td>
   <td style="text-align:left;"> $SPY  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:24:13 </td>
   <td style="text-align:left;"> $AAPL can we see $185+ Tmr 🤔👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:24:10 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Vision Pro: Everyone Is Missing The Big Picture https://www.stck.pro/news/AAPL/52545921/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:22:21 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Apple Vision Pro: Everyone Is Missing The Big Picture </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:08:38 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla $meta $aapl 
 
NEXT WEEK GOING to be volatile as FED MEETING on Thursday! 
 
Canada &amp;amp; Australia - Hike Rates.  US will HIKE TOO 
 
TAKE PROFIT and WAITING ON SIDELINE to see what feds decision!!! 
 
We might see MASSIVE PROFIT TAKING from TOMORROW Until Thursday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:00:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 81%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:59:37 </td>
   <td style="text-align:left;"> $GOOGL $MSFT such obvious longs buy and hold ignore the noise greatest companies on Earth and you will compound beyond your wildest dreams $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:57:05 </td>
   <td style="text-align:left;"> $AAPL $MSFT $DIS $F $TSLA Confucius say ... fku #fraudstreetboilerroommarketmakersandcronies  ... enjoy crash Friday you unregulated manipulated goons pumping bullshit 24x7 until you can&amp;#39;t  ... China&amp;#39;s producer prices slump 4.6% in May, worse than expected.  This is a developing news story. Please check back for updates:  
https://www.cnbc.com/2023/06/09/chinas-inflation-rises/falls.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:56:47 </td>
   <td style="text-align:left;"> &amp;gt; **MY TOP WATCHES FOR TOMORROW!**

&amp;gt; **Other**

&amp;gt; $COIN
&amp;gt; $DOCU
&amp;gt; $PYPL
&amp;gt; $AAPL
&amp;gt; $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:54:43 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:53:22 </td>
   <td style="text-align:left;"> $AAPL $NVDA $SPY $TSLA $SOFI AI hardware = Y2K. 
 
This ends badly. 
 
In tech.  Channel check yourself, the sales are not there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:51:24 </td>
   <td style="text-align:left;"> $META $SPY $QQQ $AAPL $TSLA 
 
ZUCK IS PANICKING!!!  
 
BASHING APPLE VR 
 
WANT TO CREATE STANDALONE to FIGHT TWITTER because he knows he can&amp;#39;t compete with PAPA ELON!!!! 
 
INSTAGRAM PROMOTES PEDO NETWORK 
 
GET FINE 1.3 B in EURO 
 
https://www.wsj.com/articles/meta-reveals-twitter-competitor-it-plans-to-launch-as-stand-alone-app-4a9b7721 
 
SELL META, buy AAPLE, TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:50:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $SOFI 

&amp;quot;The mother of all melt ups&amp;quot; gonna nice ring to it, I like it!

Let the bull market begin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:40:49 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/bsl9_uJ08uE 
$CVNA $BYND $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:37:29 </td>
   <td style="text-align:left;"> $AAPL calls above 180.84
Posted by @macrozz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:33:43 </td>
   <td style="text-align:left;"> $AAPL officially in bull market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:27:54 </td>
   <td style="text-align:left;"> $SPY $AAPL in spite of being the richest company in the world and talking so much about ESG, Apple pays almost no taxes to the state of California becuz they use loopholes to avoid them 
https://qz.com/apple-sales-tax-deal-cupertino-regulatory-scrutiny-1850331553 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:24:10 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Want to Invest in Republican or Democratic Stocks? Check Out These 2 ETFs https://www.stck.pro/news/AAPL/52542039/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:12:42 </td>
   <td style="text-align:left;"> $SPY    2 more hikes this summer 

groceries and gas have not hardly come off the highs $AAPL $MSFT $NVDA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:07:06 </td>
   <td style="text-align:left;"> $DOCU  docusign beat earnings and mention a.I!! This is apple at $30 situation , look at apple now at $180! buy now and get 6x later for your investments!!! $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:02:26 </td>
   <td style="text-align:left;"> $GOOGL can this POS go green like $MSFT and $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:54:56 </td>
   <td style="text-align:left;"> $DAL Delta Air Lines profit expected to soar 75% per report released today. $UAL $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:54:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:53:09 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m wrong, very bullish going to 190. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:50:39 </td>
   <td style="text-align:left;"> $QQQ Guy updates on SPY https://youtu.be/VWYLOOYhUUw $GOOG $AAPL 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:41:20 </td>
   <td style="text-align:left;"> $META META $AAPL  
https://www.theverge.com/2023/6/8/23754239/mark-zuckerberg-meta-apple-vision-pro-headset </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:40:37 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:37:37 </td>
   <td style="text-align:left;"> @Traidn clearly $AAPL snubbed Roblox.  Only way to win advertising is to team with $META </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:37:34 </td>
   <td style="text-align:left;"> $spy $nvda $aapl $tsla $BTC.X ❗️@MurdaCwrote BRILLIANT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:36:42 </td>
   <td style="text-align:left;"> $AAPL Extremely smart people... they are highly intelligent, these people I mingle with. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:35:29 </td>
   <td style="text-align:left;"> $AAPL I think the trading volume is really important, so I oft talk about it. 
 
Oft, that&amp;#39;s short for often for the really smart people I hang out with. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:35:03 </td>
   <td style="text-align:left;"> @rexman 

as in, $aapl will see $230s? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:34:01 </td>
   <td style="text-align:left;"> $spy $qqq $aapl $tsla

in a time of extreme greed, when news like this are announced, events (recessions, bull/bear markets, etc.) usually have already occurred. meaning, get your money now because it may not last long. apparently, the bull market began in october, which makes sense. stocks generally don’t grow 100%+ in a year either. markets can remain irrational longer than we can stay solvent, so this isn’t surprising. just know when to get off the wave. hold some cash, grab some shares, load some t-bills, and stay vigilant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:32:59 </td>
   <td style="text-align:left;"> $AAPL Elon is right on this one. 
 
Apple made a gigantic mistake. 
 
https://twitter.com/elonmusk/status/1666964082363371520?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:20:46 </td>
   <td style="text-align:left;"> 🐻❤😈🤯💲💰🤑✔ #JustShortIt  ... $aapl $amzn $dis $tsla $F and more ... https://link.cnbc.com/public/31738681 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:16:34 </td>
   <td style="text-align:left;"> $AAPL $META $RBLX disagree. 
 
Always been whack. 
 
Always will be. 
 
https://www.youtube.com/watch?v=qk3PK3W_wvo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:14:35 </td>
   <td style="text-align:left;"> $AAPL not a fan of either headset...but Apple at least gets points for not being as whack as Metaverse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:12:13 </td>
   <td style="text-align:left;"> $RBLX https://youtu.be/BdJdAu2ytNE. Check out this interview, his facial expressions when $AAPL is mentioned.  You can tell there is some bad blood like they were cut out of the goggle launch.  Esp last minute when asked if he would buy it…basically says no.   Because the ZUCK is coming in to team with them  $META   What does he bid 75-90? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:11:11 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA Who’s ready for a collossal dump??! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:04:38 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Apple: Magical Delays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:00:38 </td>
   <td style="text-align:left;"> $BA clears closes &amp;gt; 221
Dow Jones goes up then $BA 238.00 next resistance 
$QQQ $AAPL $MSFT $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:59:00 </td>
   <td style="text-align:left;"> $AAPL is one of the better performing stocks in the Technology Hardware, Storage &amp;amp; Peripherals industry. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:57:54 </td>
   <td style="text-align:left;"> $AAPL 

🍎- should hit $203 if we get a pause next week !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:54:45 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:52:26 </td>
   <td style="text-align:left;"> $META $aapl $tsla $spy $qqq

Zuck whine like a baby over apple VR headset

Infact apple headset much more superior than meta 

Suck it zuck....

Buy aapl tsla DUMP meta

Not to mention meta getting their revenue and traffic from pedo network 

EWWW..... 🤮🤮🤮🤮

https://www.wsj.com/articles/instagram-vast-pedophile-network-4ab7189 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:42:41 </td>
   <td style="text-align:left;"> $PLTR Dr.  Karp  working  with  the  FREE  WORLD!!!    $f $tsla $arkk $AAPL  
 
https://www.mirror.co.uk/news/politics/rishi-sunak-meet-boss-scariest-30178412 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:41:27 </td>
   <td style="text-align:left;"> Who needs $WBD content? 
$AMZN? $AAPL? $CMCSA?  
https://deadline.com/feature/writers-strike-tv-shows-affected-cobra-kai-yellowjackets-abbott-elementary-1235354256/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:40:48 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - 7 Tech Stocks to Avoid Like the Plague in June </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:39:27 </td>
   <td style="text-align:left;"> Incoming crash Friday @ https://www.investing.com/indices/indices-futures  
$dis too sell off @ https://www.marketwatch.com/investing/stock/dis?mod=search_symbol 
You&amp;#39;re welcome 🐻❤😈 $aapl $msft amzn $tsla $f and more goofy overpriced nonsense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:38:50 </td>
   <td style="text-align:left;"> $ROKU $AAPL $BYND 

Bearish reversal 🩸🩸🐻🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:36:53 </td>
   <td style="text-align:left;"> $AAPL i feel bearish short term for stocks. long term is still good. u.s economy wont be as bad as  any greats recession before. technologies makes it better forecast so most companies can adjust themselves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:36:00 </td>
   <td style="text-align:left;"> $TSLA JUST KIDDING, WE ARENT SELLING UNTIL $350 NOW

$GM $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:34:48 </td>
   <td style="text-align:left;"> $TSLA plus chart history never fails on record of days in green..it happened to $AAPL past year that repeated previous record a dropped harder after.. same here tomorrow will be a green day as said it during regular hours to match Jan 8 2021 record (11 days in red) and then it would pull back 8% to around $230.. don&amp;#39;t chase </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:33:56 </td>
   <td style="text-align:left;"> $CVNA $GME $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:33:24 </td>
   <td style="text-align:left;"> $AAPL $NFLX $NVDA $SPY $TSLA LOL.  Just wait till the FED pivots and see what happens. LOL. Clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:30:26 </td>
   <td style="text-align:left;"> $AAPL $DIS $QQQ ever wondered how proven traders (pros) manage their trade plans and portfolios? We teach this at Optionsplayers and the alert plays, mentoring, &amp;amp; premarket news/plans are all free for you for a month with no risk- can stay as long or as little as you wish. Get it all by using the link in bio or this!

https://app.optionsplayers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:28:42 </td>
   <td style="text-align:left;"> $AAPL Hello dumb dumb shorts - this is the gift that keeps on giving ~ Gazoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:23:54 </td>
   <td style="text-align:left;"> $AAPL What&amp;#39;s up with the BiG boUNce? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:21:11 </td>
   <td style="text-align:left;"> $AHI AI Health $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:17:05 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NFLX $NVDA 

shorts are about to get destroyed

A new bull market is about to begin

I warned you... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:15:20 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Zuckerberg: Apple Vision Pro is ‘not the one that I want,&amp;#39; doesn&amp;#39;t have any ‘magical solutions&amp;#39; https://www.stck.pro/news/AAPL/52531701/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:08:44 </td>
   <td style="text-align:left;"> $AAPL $MSFT $NVDA $TSLA 4/4 not too shabbyyyyy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:04:06 </td>
   <td style="text-align:left;"> $PLTR just  signed  deal  with  Panasonic $pc aka  $tsla battery  maker!!!    $aapl has  5,000  people  working on  their  Apple  Car!!!    Apple  needs  BATTERIES!!!    Who  makes  the  best  batteries???    Project  Titan  has  their  own  Wikipedia  page!!! 
 
https://en.wikipedia.org/wiki/Apple_electric_car_project </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:03:19 </td>
   <td style="text-align:left;"> How to trade using Blue Boxes? | Elliott Wave Learning | Elliott Wave Forecast, video tutorial at: https://t.co/LEwTOxOvJq #Elliottwave #Stocks #Trading $DJIA $AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:00:53 </td>
   <td style="text-align:left;"> $SPY Latest 1H view from the Midday update. Showing a reaction higher taking place as expected. Longs should be risk free by now. #Elliottwave #Stocks #Trading $DJIA $AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:00:40 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ $META the result of April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:00:13 </td>
   <td style="text-align:left;"> $SPY 1H view from today&amp;#39;s Pre-Market update. Called for a pullback towards the blue box area where buyers were expected to appear. #Elliottwave #Stocks #Trading $DJIA $AAPL $SPY $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:52:45 </td>
   <td style="text-align:left;"> $SPY $AAPL what was the reason for the pump today again?  Did AAPL come out with a stupid goggle for blind people which will cost $6,499.99? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:51:48 </td>
   <td style="text-align:left;"> $AAPL &amp;#39;bout 40-50 points more to go, imo. 
 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:43:52 </td>
   <td style="text-align:left;"> $AAPL kind of crazy when you think that people are actually buying in at these levels and they will still double their money in 10 years or less </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:41:34 </td>
   <td style="text-align:left;"> $PLTR just  signed  a  deal  with  Panasonic  aka  $pc aka  $tsla battery  maker!!!  COINCIDENCE???  $aapl needs  a  battery  maker  for  their  long  anticipated Apple  Car!!! 
 
https://9to5mac.com/2021/08/09/apple-car-korean-partners/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:36:21 </td>
   <td style="text-align:left;"> $aapl $spy $qqq

exactly why i took profit on long calls and will wait patiently for a pullback. will look juicy @ ~ $150. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:36:15 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #5 ticker with sweep activity where institutions are trading options urgently with 29.3K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:33:33 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : How To Allocate $25,000 Among My Top 20 Dividend Income Stocks For June 2023 https://www.stck.pro/news/AAPL/52528374/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:31:50 </td>
   <td style="text-align:left;"> $SPY $AAPL Apple is very close to its all-time high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:29:28 </td>
   <td style="text-align:left;"> $AAPL 
👁
❤️
🍏👁❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:24:07 </td>
   <td style="text-align:left;"> $SPY $AAPL the camera on the Samsung Galaxy is amazing! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:22:52 </td>
   <td style="text-align:left;"> $TSLA $AAPL 
The games MMs playing is DIRTY af!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:20:35 </td>
   <td style="text-align:left;"> $PLTR just  signed  $tsla battery  maker  $PC aka  Panasonic!!!    YESTERDAY!!!    Does  $aapl need  a  battery  maker  for  the  Apple  Car???    Apple  rolls  with  best  in  class!!    $f Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:19:25 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - 7 Momentum Stocks That Could Skyrocket in the Next 12 Months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:15:37 </td>
   <td style="text-align:left;"> $PLTR is  ENTERPRISE AI  like  $msft $csco $pc not  yet  for  $aapl!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:15:33 </td>
   <td style="text-align:left;"> $TSLA  
 
I called $230+ on May 1st when @ $160, now I am calling $280 ON DECK! 
 
 
$NVDA $QQQ $META $AAPL  
 
LFG, Greedy Index 76! (Extreme Greedy) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:14:05 </td>
   <td style="text-align:left;"> $SPY I have said before. This market is fixed to go up. There are literally a million ways to f with bears. Every time something about to break something else will show up to pump the market up. Unreal lol 😂 $TSLA $CVNA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:13:05 </td>
   <td style="text-align:left;"> Trillion Dollar Stocks $AAPL $MSFT $GOOG $AMZN $NVDA  
 
https://www.dividendpower.org/2023/06/08/trillion-dollar-stocks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:11:27 </td>
   <td style="text-align:left;"> $AAPL  nice average on 15 calls $180June 16 let&amp;#39;s see how much they print after FED meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:09:52 </td>
   <td style="text-align:left;"> $AAPL 250 by xmas no brainer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:08:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
08-June Stock Market Update: Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:06:40 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - How To Allocate $25,000 Among My Top 20 Dividend Income Stocks For June 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:04:00 </td>
   <td style="text-align:left;"> $aapl $msft $amzn $dis $tsla and more ... stfu already #fraudstreetboilerroommarketmakersandcronies with your unregulated manipulated unsubstantiated self serving bullshit rallies in queue to implode is these trying times overflowing with valid socioeconomic concerns in tandem with more coming including higher interest rates.  &amp;quot;China inflation could spoil the weekend party.&amp;quot; @ https://newslink.reuters.com/public/31737940  Welcome to crash Friday and the Armageddon Recession you goons. Thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker 🐻❤🤯😈💲💰🤑✔ 
Stock Futures 
https://www.investing.com/indices/indices-futures 
Stock Market Index 
https://www.investing.com/indices/major-indices 
Energy Futures Prices 
https://www.investing.com/commodities/energy 
Trading Economics 
https://tradingeconomics.com/ 
Finviz News 
https://finviz.com/news.ashx 
Reuters News 
https://www.reuters.com/news/archive/businessNews 
CNBC News 
https://www.cnbc.com/latest/ 
Investingcom News 
https://www.investing.com/news/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:01:24 </td>
   <td style="text-align:left;"> $BABA $JD latex4dc141bca9a8686cb584d0d68df3715eaapl start by banning apple products. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:00:40 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:00:39 </td>
   <td style="text-align:left;"> $AAPL love the LT chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:59:56 </td>
   <td style="text-align:left;"> $TSLA yes the shareholders are really good at pushing the price up with buying 1 share at a time

but if the market starts to sour on rate effects and another rate higher 

then this will see some heavy volatility 

because over 200 has been mostly lower volume 

$AAPL $SPY $IWM $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:55:59 </td>
   <td style="text-align:left;"> $TSLA Holding shares from 130 but i expect a pullback after fed raises again 

they know they have to, because prices aren&amp;#39;t really down hardly 

$SPY $AAPL $NVDA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:53:45 </td>
   <td style="text-align:left;"> $AAPL Reminder #6: $180 new solid support, will test $185 soon, by mid-June. $QQQ $META $TLSA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:53:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 81%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:51:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Meta CEO Mark Zuckerberg takes a dig at Apple&amp;#39;s &amp;#39;Vision Pro&amp;#39; https://www.stck.pro/news/AAPL/52527573/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:50:04 </td>
   <td style="text-align:left;"> $AAPL never really caught a perfect trade but manage to buy a few bucks worth at 134 and riding this up feels good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:48:01 </td>
   <td style="text-align:left;"> $NASDAQ $NQ_F $SPY Disgusting Democrats $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:46:38 </td>
   <td style="text-align:left;"> $PYPL latex46ff6cc93bdb3baac4507bed675b24d8AMZN could be interested in this loser company if their smart management team can tinker with this broken company to merge into Amazon Pay 
 
$JPM could be another potential buyer if they want to speed up fintech business development at a cheap price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:41:47 </td>
   <td style="text-align:left;"> $AAPL $SPY $TSLA  
👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:40:43 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:38:46 </td>
   <td style="text-align:left;"> $PLTR Keith said he is leaving his Palantir shares to his kids!!!  Growth is never going to stop!  Top right of pic… 
 
excellent vid on life 
 
“$msft $amzn $tsla $aapl of our time!!!!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:33:15 </td>
   <td style="text-align:left;"> $AAPL apple vision pro is epic!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:24:28 </td>
   <td style="text-align:left;"> “$PLTR is like $msft $amzn $tsla $aapl”  This is the second time he has said this!!  24 minute mark of vid!!! 
 
https://m.youtube.com/watch?v=Sb-OKbOSUNw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:23:44 </td>
   <td style="text-align:left;"> $SPY I don’t know who needs to hear this but the last time SPY was at $429 it sold off to $356  
 
$AAPL $TSLA $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:21:55 </td>
   <td style="text-align:left;"> $UPST why people are bullish on any other companies other than $TSLA $AAPL $MSFT is beyond me. Companies like upstart will NOT be around. UPST will likely see sub 30 tomorrow morning. After that, who knows. Long term, it won&amp;#39;t be around. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:20:18 </td>
   <td style="text-align:left;"> $AAPL Stocktwits is one of the great SPAM operations of all time. Ads plastered everywhere, feeds filled with ads, pop up ads on the right, now pop up ads in the center on top of the feeds... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:17:56 </td>
   <td style="text-align:left;"> $AAPL https://appleinsider.com/articles/23/06/08/apple-wants-to-build-324000-square-feet-of-office-space-in-north-carolina </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:17:52 </td>
   <td style="text-align:left;"> $spy $qqq $aapl $tsla 

well said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:15:16 </td>
   <td style="text-align:left;"> $IMMR Pump:  Google Apple $AAPL immersion technology </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:13:46 </td>
   <td style="text-align:left;"> $AHI https://www.ahi.tech/products/facescan prob $AAPL buyout, FaceScan aligns exactly with their new Vision Pro headset, just like a few days ago they purchased Mira which does AR — Apple doesn&amp;#39;t need to hide in the shadows anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:13:24 </td>
   <td style="text-align:left;"> $MVIS $MSFT $AAPL 

Hey MicroVision Fams, Good news !!!!

Soon you&amp;#39;ll have an actual excuse instead of fantasies for why Microsoft stopped shipping MicroVision&amp;#39;s ancient tech. After June, it&amp;#39;s only been 12 months 😂

Still waiting for an excuse as to why you bagholders claim MicroVision&amp;#39;s components are so valuable to Microsoft yet you&amp;#39;re praying they have an opportunity to continue their worthless contract with them....

TLDR: If your product is in demand, you charge for it. NOT hope you can continue giving it away for nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:13:24 </td>
   <td style="text-align:left;"> @Benzikamg Any guy who spends their time tolling LGBTQ issues is def Gay 
 
$Bud $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:12:53 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:12:31 </td>
   <td style="text-align:left;"> $AAPL $SPY $VIX Don&amp;#39;t get me wrong. I understand why the market is rallying. I also understand why it shouldn&amp;#39;t be rallying. Good portion of liquidity is entering over levered and high risk portions of the market.  
 
Vegas always has its best year, just before and during a crash and as far as I can see, this entire market acting like a slot machine. smh.  
 
We are playing with peoples pensions and people yelling BEAR SUCKS while they cant just walk away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:11:42 </td>
   <td style="text-align:left;"> $PLTR must see TV!!! ”There is only one $tsla!  There is only one $aapl.  There is only one Palantir!“  The real ai Backbone! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:10:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while 90% of traders lose.
$FSR vs $SPY

This is why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:10:04 </td>
   <td style="text-align:left;"> $TSLA ripping 🦬

$AI $PLTR $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:08:41 </td>
   <td style="text-align:left;"> $JPM $AAPL $TSLA $SPY $BRK.B What is the result of buying when heaviness % is low?
See the Win/Lose ratio.

May (&amp;#39;23) = 0 loss
April (&amp;#39;23) = 0 loss
March (&amp;#39;23) = 1 loss
January (&amp;#39;23) = 0 loss.
December (&amp;#39;22) = 2 losses.
November (&amp;#39;22) = 0 loss
October (&amp;#39;22) = 2 losses

Got timestamps + buy fills for everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:07:13 </td>
   <td style="text-align:left;"> $AAPL  what is a price target to short this stock? , I’m guessing $205 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:06:13 </td>
   <td style="text-align:left;"> $AAPL closing at 180….. 

Tim Cook got them fat nutzzzzzz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:05:29 </td>
   <td style="text-align:left;"> $U $AAPL  What more do you need to know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:02:59 </td>
   <td style="text-align:left;"> $AAPL this graph show the market for 3500 usd VR goggles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:02:38 </td>
   <td style="text-align:left;"> $AAPL June 8th 2022, two day period gapped down 11$. Cmon bro, u don&amp;#39;t think im being literally do you.  
 
Look at the number. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:01:35 </td>
   <td style="text-align:left;"> $TSLA Zuckerberg scared of $AAPL VisionPro. A Steve Ballmer moment for 
$META </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:57:42 </td>
   <td style="text-align:left;"> $aapl added—200+ by soy https://www.youtube.com/live/IULKDv1IaDY?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:56:40 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:56:16 </td>
   <td style="text-align:left;"> $AAPL 
Year to Date up 38.97%!!!
Why would anybody Short this stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:55:46 </td>
   <td style="text-align:left;"> $AAPL . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:55:21 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:52:39 </td>
   <td style="text-align:left;"> $BABA most undervalued stock in the entire market … from all US traded stocks cash balances , this has the 4th highest amount of cash at $75 billion. Only $AAPL $MSFT and $GOOGL have more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:51:14 </td>
   <td style="text-align:left;"> $AAPL  I dare you to find the last time apple went down $11 in a day...I promise you it will be much much tougher than you think. This stock is not volatile so unless there is something you know is happening tomorrow (which you don&amp;#39;t), it is not dropping that low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:50:25 </td>
   <td style="text-align:left;"> $AAPL  it dumped on day of WWDC but now it looks like it&amp;#39;s going back to it&amp;#39;s ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:50:18 </td>
   <td style="text-align:left;"> latex1a2f5dba1fdbf94ceb21bae9b6d20c54AAPL apple is in that same boat 

$SPY $MSFT $JPM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:35:10 </td>
   <td style="text-align:left;"> $AAPL doesn&amp;#39;t this usually dump after wwdc? Also could AAPL realistically buy out DIS like people have been speculating? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:34:49 </td>
   <td style="text-align:left;"> $AAPL Tesla raising the market tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:32:51 </td>
   <td style="text-align:left;"> $AAPL Friday profit taking sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:30:59 </td>
   <td style="text-align:left;"> $AAPL  169 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:30:17 </td>
   <td style="text-align:left;"> $NVDA $AAPL just curious what approximate Year we are expecting these companies to grow to their current valuations? 

2030? 2050? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:29:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Stock Market Update: Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:28:06 </td>
   <td style="text-align:left;"> $AAPL bears desperate we talking about 50 cents lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:27:20 </td>
   <td style="text-align:left;"> $AAPL over 181 you’re dead if you’re short. 177 held three times means support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:27:01 </td>
   <td style="text-align:left;"> $LCID Lucid should open factory in China to reduce cost. That’s how $AAPL is making shit load of profit on IPhone. Lucid can succeed just like $tsla if management can execute well. Tesla turned profitable only after they started operating in China. 

Lucid has best EV technology, longest and fastest car in the world. Execute well and you see sky is the limit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:26:16 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #2 stock that institutions are trading over rolling 5 day window with 588.2K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:23:09 </td>
   <td style="text-align:left;"> $AAPL $177 held three times. Will break below tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:22:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$PLUG vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA latexd486ad33e33c13d4bb3516bfcf8195deAAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:21:47 </td>
   <td style="text-align:left;"> These salty ass MFs are mad. Sound like unhinged little girls. 😂

$TSLA $NVDA $AAPL $SOFI $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:20:55 </td>
   <td style="text-align:left;"> $AAPL $AMZN $NVDA $AMD $TSLA almost time for a new bear market already! 
Wow, time flies  😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:19:58 </td>
   <td style="text-align:left;"> $AAPL Ba Zinggggg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:19:50 </td>
   <td style="text-align:left;"> $AAPL love this stock. Crazy how anyone can bet against it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:18:19 </td>
   <td style="text-align:left;"> $SPY $AAPL hard to believe $3500 for some pair of goggles. Apple running out of ideas? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:17:26 </td>
   <td style="text-align:left;"> THE BEAR MARKET IS OVER ❗❗❗👇
A NEW BULL MARKET HAS STARTED 📈🐃

It&amp;#39;s official.  A new bull market is confirmed.🐃

The S&amp;amp;P 500 is now up 20% from its 10/12/22 closing low.  The prior bear market saw the index fall 25.4% over 282 days.📈

Note that the 2022 bear that lasted 282 days was basically right in-line with the average bear market length of 286 days🏔
$TSLA $AAPL $AMZN $NVDA $AMD  SBBDBDBD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:16:23 </td>
   <td style="text-align:left;"> $AAPL below 180 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:15:42 </td>
   <td style="text-align:left;"> $DOCU be 600 in a few years easy LONG get it while it&amp;#39;s cheap....there SUBs are way more  cheaper then $MSFT and $AAPL  these guys are in a great niche market share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:15:15 </td>
   <td style="text-align:left;"> $AAPL gap up 182 tomorrow 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:15:15 </td>
   <td style="text-align:left;"> $TSLA RSI over 91, but it could go up to 95 history repeating right now. News about Cybertruck estimates 375k per year.
It&amp;#39;s heading over $255 very soon. I just rolled over my call $235 to latexfcbaba73a5f3cf58ce760b0049257eddAAPL Reclaim ATH tomorrow very good chance if makert help.
$AVGO $ADBE Jump back in with some July Call option on opening. I&amp;#39;m just gonna let it run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:13:15 </td>
   <td style="text-align:left;"> $AAPL How likely will this gap up tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:13:15 </td>
   <td style="text-align:left;"> $AAPL So many bears making fun of Vision don’t even understand the space

This can be big </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:06:34 </td>
   <td style="text-align:left;"> Love how analyst are speaking market doom and gloom while their hedge funds keep loading. $SPY $TSLA $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:05:58 </td>
   <td style="text-align:left;"> $AAPL A blood bath sure would be fun tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:03:35 </td>
   <td style="text-align:left;"> $MULN i dont think u people appreciate my honesty and predictions for tomorrow.  Eventhough i been 100% right.  So i will refrain. But go ahead and keep buying 100k to 200k shares at $1 . Eventhough i said to you why buy? If you could wait under .50. Oh well. 
$SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:58:17 </td>
   <td style="text-align:left;"> $AAPL everytime this hits 180 kerplunk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:58:01 </td>
   <td style="text-align:left;"> @SamuelB747 $AAPL introduced the same feature on Tuesday, makes $DOCU obsolete. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:57:28 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:55:39 </td>
   <td style="text-align:left;"> $AAPL it has been a wonderful day today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:54:49 </td>
   <td style="text-align:left;"> $AAPL bought June 9 $177.5 put </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:54:21 </td>
   <td style="text-align:left;"> $AAPL Next week I will be telling bears I told you so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:54:08 </td>
   <td style="text-align:left;"> $SPY this is why they say you can’t time the market . People expected a pullback .. so some probably sold to try and get back n cheaper .. now they will have to buy back higher $TSLA $AMAZ $AAPL or wait for awhile </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:53:56 </td>
   <td style="text-align:left;"> $AAPL lmfao 🤣 🤣🤣🤣🤣🤣‼️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:53:42 </td>
   <td style="text-align:left;"> $AAPL 

Gap up tomorrow… sleep well shorties 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:52:21 </td>
   <td style="text-align:left;"> $AAPL Like I said, Apple going to break 6 T in short term. Forget valuation. This is frenzy.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:52:00 </td>
   <td style="text-align:left;"> $AAPL: The long and short term trends are both positive. This is looking good! https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:51:23 </td>
   <td style="text-align:left;"> $AAPL Who’s selling the $182.5 call for tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:50:42 </td>
   <td style="text-align:left;"> Dumbonomists don&amp;#39;t think ... they jawbone  ... https://www.marketwatch.com/story/fed-might-hike-interest-rates-again-in-june-instead-of-a-skip-some-economists-think-a3c230bd  ... rest assured higher interest rates incoming  ... enjoy the Autogeddon Armageddon Recession long lasting  ... $aapl $msft $amzn $meta $dis and more 🐻❤😈🤑💲💰✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:50:25 </td>
   <td style="text-align:left;"> $AAPL A welcome relief after yesterday&amp;#39;s nonsense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:48:34 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Run away from AAPL, NVDA and the entire tech sector as fast as you can and start buying gold - The High-Tech Strategist&amp;#39;s Fred Hickey https://www.stck.pro/news/AAPL/52518652/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:47:42 </td>
   <td style="text-align:left;"> $AAPL $SPY $TSLA $QQQ lets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:47:32 </td>
   <td style="text-align:left;"> $SPY Trudeau still president ? 
Biden? 
Oh, wait, let me ask the latter after Tuesday Core CPI.

$QQQ $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:45:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

Let’s break that HOD 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:45:34 </td>
   <td style="text-align:left;"> $SPY We&amp;#39;re going to have this odd EOM/EOQ price action as PMs have to chase to try &amp;amp; show they own the Mrkt while those who do will Sell &amp;amp; take profits. 
 
Today we have $aapl up but its on 37m shares at 3:45pm so, its just gaming. If you&amp;#39;re a Bear you should be excited, the bigger the balloon gets blown up the nicer the pop. 
 
Just let it run, you want to see this,.. unless youre too short right now :o) 
 
$qqq $nvda $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:45:09 </td>
   <td style="text-align:left;"> $AAPL tomorrow open $185 will be great. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:44:52 </td>
   <td style="text-align:left;"> $AAPL  OH BOY! I SMELL 181 ON DECK 🥵 SHOW ME THE MONEY! 9 AWAY FROM 190!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:42:54 </td>
   <td style="text-align:left;"> $AAPL ITM ! Roll them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:42:20 </td>
   <td style="text-align:left;"> $AAPL God wrath already came to your parents, he gave them you :o) 
 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:42:19 </td>
   <td style="text-align:left;"> $AAPL daily flag now, notable into tomorrow https://t.co/Dv2jSUDgRT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:42:02 </td>
   <td style="text-align:left;"> $AAPL stc Jun9 180c @ 1.32 (.64) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:42:00 </td>
   <td style="text-align:left;"> $AAPL made it. WOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:41:59 </td>
   <td style="text-align:left;"> $AAPL Loading PUTS for next week. This will tank! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:41:53 </td>
   <td style="text-align:left;"> $SPX $AAPL $NVDA $SPY $QQQ I said this last month and I&amp;#39;ll say it again. 
CPI is going to gap down again on Tuesday and shorts are on the wrong side here AGAIN!!! 
 
Listen to me or lose money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:41:51 </td>
   <td style="text-align:left;"> $AAPL Let’s stay above $180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:41:46 </td>
   <td style="text-align:left;"> $SPY $AAPL wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:41:27 </td>
   <td style="text-align:left;"> $AAPL Biggest LGBTQ donor is Apple, Gods wrath is coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:41:19 </td>
   <td style="text-align:left;"> $AAPL 190 try again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:40:59 </td>
   <td style="text-align:left;"> $AAPL Hello Bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:40:28 </td>
   <td style="text-align:left;"> $SPY $AAPL i wont buy this till its $299. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:40:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
08-June Stock Market Update: Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:40:15 </td>
   <td style="text-align:left;"> $AAPL $200 tomorrow? Reason to get their Vision Pro </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:38:11 </td>
   <td style="text-align:left;"> $AAPL 

$200 a given… new revenue pouring in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:37:08 </td>
   <td style="text-align:left;"> $AAPL haha this is hilarious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:34:42 </td>
   <td style="text-align:left;"> $AAPL if this makes another .50 by EOD tomorrow between 185 and 190. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:33:55 </td>
   <td style="text-align:left;"> $MSFT under daily EMA12 and acted as resistance. $AAPL did the opposite. Who wins over the $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:33:12 </td>
   <td style="text-align:left;"> $AAPL close to last fridays high. wonder where it goes tomorrow. Better to highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:32:54 </td>
   <td style="text-align:left;"> Same bullshit, different day of a #fraudstreetboilerroommarketmakersandcronies unregulated manipulated self serving rally in queue to implode  @ https://www.investing.com/indices/major-indices  ... blow me bulls @ $aapl $msft $amzn $meta $dis and more  ... thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker you&amp;#39;re welcome 🐻❤😈💲🤑💰✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:31:08 </td>
   <td style="text-align:left;"> $AAPL still printing HOD.. This is not as bad as many people said..... I am buying their AR glasses.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:26:58 </td>
   <td style="text-align:left;"> $AAPL $2.3M OTM Put 
 
Strike: 180 
Expiration: 6/30/23 
 
*At the Ask* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:26:04 </td>
   <td style="text-align:left;"> @VTOracle The $AAPL Vision Pro was not disappointing at all, it was only disappointing to idiots who have limiting beliefs!  Just watch as Apple stock goes to 200! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:24:56 </td>
   <td style="text-align:left;"> $SPY shorting $AAPL vision is a bust </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:13:21 </td>
   <td style="text-align:left;"> $TSLA gonna pull back on 250 resistance then back up imho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:13:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK $META . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:13:19 </td>
   <td style="text-align:left;"> @BulliverShagnasty hey there 🌈🐻… how’s your $TSLA  short working out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:12:52 </td>
   <td style="text-align:left;"> $TSLA Cathie pumping TSLA even more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:12:22 </td>
   <td style="text-align:left;"> $TSLA did bears figure out to just buy calls yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:12:19 </td>
   <td style="text-align:left;"> $TSLA Cathie Wood simulations are accurate. $1,000 coming next month!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:12:10 </td>
   <td style="text-align:left;"> $TSLA 275+ day? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:12:07 </td>
   <td style="text-align:left;"> $CHPT @Chargepoint yeah this new $TSLA thing sucks for us but not as much I guess as the one (forgot name) that $GM originally put all its eggs into that basket. 
 
BUT in reality CHPT is more geared to big corps. what WE need is 1 contract with an $XOM $MPC etc to PUT US OUR charging stations at ALL THEIR GAS STATIONS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:11:59 </td>
   <td style="text-align:left;"> $TSLA will break records with the most consecutive days up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:11:54 </td>
   <td style="text-align:left;"> $TSLA investing in  popularity contest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:11:46 </td>
   <td style="text-align:left;"> $TSLA - No indication to sell, maintain position.. https://stocktwits.com/macd_trades/message/530154896 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:11:45 </td>
   <td style="text-align:left;"> Around 80% of $TSLA gap up &amp;gt; 5% fill in 5 days or less. 
Just saying... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:11:32 </td>
   <td style="text-align:left;"> $TSLA Tesla will be feeding all the hungry EVs in the US and around the world at Tesla&amp;#39;s charging station network. Musk is looking far beyond the plans of mortal men and women. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:11:12 </td>
   <td style="text-align:left;"> $TSLA this high!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:11:05 </td>
   <td style="text-align:left;"> $TSLA 

Price target $300
We are serious investors loading up from Asia 

https://www.morningstar.com/news/marketwatch/20230609340/teslas-stock-rises-toward-11th-straight-gain-as-company-seen-playing-chess-while-others-are-playing-checkers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:10:58 </td>
   <td style="text-align:left;"> $TSLA $QQQ $ARKK $FNGU $ARKF Cathie&amp;#39;s 24month performance on ARK is a tasty -300%. give her billions boys! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:10:36 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:10:25 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ $TSLA  do all  nvidia bulls feel safe relying on TSMC? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:10:18 </td>
   <td style="text-align:left;"> $FNGU $TSLA Yes!!~🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:10:02 </td>
   <td style="text-align:left;"> $TSLA 
Not gonna short until 269 right stop.
But I will short 293 full size no stop to 260s.

Free $ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:10:00 </td>
   <td style="text-align:left;"> $TSLA big big day today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:09:39 </td>
   <td style="text-align:left;"> $TSLA man my IRA looking good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:09:13 </td>
   <td style="text-align:left;"> $TSLA $ARKK $ARKF $QQQ $FNGU Cathie Wood entered her office today 🤑💎😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:09:04 </td>
   <td style="text-align:left;"> $TSLA  if its going to 270, then just say that then 🤷🏽‍♂️ LETS GET IT 💰 💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:09:03 </td>
   <td style="text-align:left;"> $TSLA $SPY 

They wanted him out of twitter and now they created a monster. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:09:02 </td>
   <td style="text-align:left;"> $TSLA  and there is 250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:08:53 </td>
   <td style="text-align:left;"> $TSLA if they were not  selling at 210,220,230 they aren’t gonna sell at $300 either. PT 3,000 in a couple of years. Retirement is around the corner </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:08:40 </td>
   <td style="text-align:left;"> $LVWR  $LVWRW warrants the EV motorcycle company backed by Harley Davidson can now use $TSLA chargers. 
 
Electric Motorcycle Tax Credits: Two Senators Try To Expand Program In US. The Electric Motorcycle Parity Act of 2023 would subject bikes to the same rules as the EV credits in the Inflation Reduction Act. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:08:37 </td>
   <td style="text-align:left;"> $TSLA short squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:07:52 </td>
   <td style="text-align:left;"> $PLTR quick  summary  of  over  $1 billion  in  sales  this  week!!!    $tsla battery  maker  $pc aka  Panasonic!!!   $msft $AAPL @Pocoyo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:07:37 </td>
   <td style="text-align:left;"> $TSLA 
Before you know it Tesla pricing is going to surpass $META!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:07:31 </td>
   <td style="text-align:left;"> $TSLA how high do you see this going today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:07:22 </td>
   <td style="text-align:left;"> $TSLA - up $33.00 from next suggested buy entry. Projected price target $268.00 area. Congrats! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:07:18 </td>
   <td style="text-align:left;"> $TSLA meme mode again. It’s everyday!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:07:17 </td>
   <td style="text-align:left;"> $TSLA EV news 
Another EV: UCAR Tripled a week ago. TGT $75 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:07:10 </td>
   <td style="text-align:left;"> $TSLA continuous innovation/invention in patented charging technologies, leveraged with the well-developed energy delivery/storage ecosystem, could create premium charging and related services; as well as points of differentiation for these services over standard charging/related services </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:07:08 </td>
   <td style="text-align:left;"> $TSLA Tesla&amp;gt;Saudi Oil-----bye bye </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:06:59 </td>
   <td style="text-align:left;"> $TSLA Damn! We are rollin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:06:53 </td>
   <td style="text-align:left;"> $TSLA hey bears.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:06:52 </td>
   <td style="text-align:left;"> @OldFngGuy rode $tsla all up. And exit on was on the nose too. I can post endless charts and the gains I made out of it. Yet you reply to me I’m random? Check my profile for any credibility. People that post only opinions on StockTwits without showing their actions are random. I at least can show which action I took while others need to work in an office for a salary, I’m just enjoying freedom in my life and trade and invest both ways making money rather than using StockTwits to vent emotions. Have a nice day!

https://stocktwits.com/MLinv/message/393652078 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:06:43 </td>
   <td style="text-align:left;"> $TSLA Dan Ives and Wedbush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:06:40 </td>
   <td style="text-align:left;"> $TSLA 224 close , news gonna get sold and rug gonna get pulled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:06:28 </td>
   <td style="text-align:left;"> $TSLA To think this is just the start of the run…  $1000 is not farfetched.  Tesla Power - Tesla Solar, Tesla Storage, Tesla Charging, Tesla Battery Manufacturing, Tesla Mining…

I mean HELLO

OH YEAH, THEY MAKE CARS TOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:06:15 </td>
   <td style="text-align:left;"> $TSLA how high we going today boys? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:05:45 </td>
   <td style="text-align:left;"> $TSLA comic short squeeze to $300.00. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:04:51 </td>
   <td style="text-align:left;"> $TSLA super charging short asses to moon. Close $275.00. New upgraded wet bush target is $300.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:04:47 </td>
   <td style="text-align:left;"> $TSLA i go short today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:04:13 </td>
   <td style="text-align:left;"> $TSLA BOOOM, im back in 248.56, looking for 249&amp;#39;s.. Scalp a roonster baby.... anyone anyone, bueller </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:04:02 </td>
   <td style="text-align:left;"> $TSLA  option profit calculator </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:03:58 </td>
   <td style="text-align:left;"> $TSLA decent news , Friday margin calls , oh this baby squeezing hard today on fomo 🚀💰🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:03:45 </td>
   <td style="text-align:left;"> $TSLA watch everyone sell at open then mms pump this to 300 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:03:44 </td>
   <td style="text-align:left;"> $TSLA i know a lot of people thought this bubble had popped at 100. that is why you cannot trust symmetry in trading. humans are drawn to patterns and as a result fall into like minded traps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:03:40 </td>
   <td style="text-align:left;"> $TSLA hahaha this is a true play! “Pump bulls pump!” All so the guy next to you can sell before you do, it’s good to be a massacre once the selling starts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:03:39 </td>
   <td style="text-align:left;"> $TSLA is now  249  180+ in few weeks as I predicted when it was 159 few weeks ago. I have Calls TSLA at 104 in 4 jan for PT 120-130+ 2 months later 216. Can some one msg for me. &amp;quot; @Gdwtvb $TSLA is now 249 as @Omegacy2 Predicted 180+ few Weeks ago. Clown !. &amp;quot;  
 
&amp;quot;When TSLA 180+ If I have Time I will Find Your Post. Clown LOL I have 90% of the Calls to make +5-20% in 1-5 days. Just Check one week only and You will see them easy. You Said TSLA not 180+ in 6 months. TSLA use to do one bad ER and the next one Good. Let see About That. Only a Fool Keep Shorts TSLA at 159.s. I only need one TSLA investors Day or some Some Cars Show and TSLA 180+. GLTA Bullish&amp;quot; 
 
Omegacy2 
Apr 28, 2023 10:12 AM 
$TSLA is now 159.s and will be 180+ in few weeks.  
  
@Gdwtvb Don&amp;#39;t me LOL. I have calls TSLA like 10 times with +5-20% Gains each since April 2022 only (bc I just Post since april). as low as in 104 in early Jan and PT 120+ and 130+.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:03:14 </td>
   <td style="text-align:left;"> $TSLA I wonder how much 240 yolo calls exp today Worth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:02:41 </td>
   <td style="text-align:left;"> $TSLA no one seeing these trades ? 245? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:02:37 </td>
   <td style="text-align:left;"> $TSLA someone trying to trigger a fall... I wonder who that could be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:02:34 </td>
   <td style="text-align:left;"> $TSLA 
CNBC “Bulls back in charge”

Yes we are!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:02:22 </td>
   <td style="text-align:left;"> $TSLA hit 250 resist, RSI at MAX overbot, may hold this line a few days but will go lower from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:02:16 </td>
   <td style="text-align:left;"> $TSLA back by Mongolian Mineral deal ! Once it done, problem solved ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:02:12 </td>
   <td style="text-align:left;"> $TSLA imagine dump on open... bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:02:02 </td>
   <td style="text-align:left;"> $TSLA upgraded with price target $300.00. Today close $275.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:57 </td>
   <td style="text-align:left;"> $TSLA there are no more bears alive. Can’t be. Might reverse next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:55 </td>
   <td style="text-align:left;"> $TSLA party today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:48 </td>
   <td style="text-align:left;"> $TSLA 

One day i’ll own this made possible by my Tesla shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:45 </td>
   <td style="text-align:left;"> $TSLA Elon 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:44 </td>
   <td style="text-align:left;"> $TSLA spasm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:23 </td>
   <td style="text-align:left;"> $TSLA finally $DIS is on the move! 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:22 </td>
   <td style="text-align:left;"> @OldFngGuy Then come April: I posted $tsla to accumulate in the 150s more as it was going higher. I just post all my actions backed up with charts and the gains that come with it, incl. Links to previous post. Rather than just posting opinions. Read April’s post 👇🏽 also on the nose after December’s entry. Time is money: I make it both ways. Not bagholding. 

https://stocktwits.com/MLinv/message/524329258 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:22 </td>
   <td style="text-align:left;"> $TSLA YO WTF!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:17 </td>
   <td style="text-align:left;"> $TSLA March to 300 continues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:15 </td>
   <td style="text-align:left;"> $TSLA looks like my bull army is still sleeping. Needs to wake up cuz it’s time to work here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:01:12 </td>
   <td style="text-align:left;"> 🛑*PUTIN: RUSSIA TO PLACE NUKE WEAPONS IN BELARUS AFTER JULY 7-8❗
https://twitter.com/PaulVikingGlob1/status/1667135168002260992?t=e3fQ2lRL9nuqVgfvBAAb2A&amp;amp;s=19
$TSLA $AAPL $AMZN $NVDA $AMD  VSVZV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:00:52 </td>
   <td style="text-align:left;"> $TSLA i deff won’t short it but i deff don’t want to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:00:13 </td>
   <td style="text-align:left;"> $TSLA just imagine when the fed actually pivots. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:00:11 </td>
   <td style="text-align:left;"> $TSLA longest 1.5 hours of my life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:00:08 </td>
   <td style="text-align:left;"> $TSLA if I wasn’t holding Tesla long I’d be afraid to jump in for a day trade! And I definitely wouldn’t short it either! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:00:08 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ ok bulls.
Y’all just need to hold it here for another hour and a half. Hoping to be able to buy puts at this level before the call strikes are printed for today’s expiration. Once that happens  this booger is gonna dip. Just a little longer. Surprise me and run it to $260 so I can add even more. Please.. pretty please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:00:05 </td>
   <td style="text-align:left;"> $TSLA when do we buy puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:00:00 </td>
   <td style="text-align:left;"> $TSLA has a Return On Assets of 13.58%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:59:43 </td>
   <td style="text-align:left;"> $GM $TSLA $f  here is the irony:  open tsla charging system is a pre-arranged deal back in IRA negotiations with the Biden administration- to let Tesla qualify for $7,500 credit with their non unionized work force.  Now it is perceived as a business achievement and rewarding  $100 billion dollar market cap from the two news to Tesla is almost comic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:59:35 </td>
   <td style="text-align:left;"> @halba1  Elon is a Genius !!  He is now going to make money on Every EV sold ..  Not just $TSLA.  When a GM pulls up it is Tesla Brand Recognition. Free advertising along with income from charger 😊😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:59:23 </td>
   <td style="text-align:left;"> $TSLA Will this pump the market today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:59:18 </td>
   <td style="text-align:left;"> $TSLA RSI kind of warm - </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:59:12 </td>
   <td style="text-align:left;"> $TSLA this stock also has a habit of dumping when it’s open … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:59:07 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:58:53 </td>
   <td style="text-align:left;"> $TSLA Where you going get back up there now so I can sale my calls at the open please Elon please Elon give me 260 at 930… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:58:52 </td>
   <td style="text-align:left;"> SweepCast ⚡ Unusual Options Detected: $TSLA with Unusual Options Activity Alerted on $230 PUT Expiring: 06-09-2023 worth 46K🐻 |🥇 Start Using SweepCast! @SweepCast  🥇 | </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:58:28 </td>
   <td style="text-align:left;"> $TSLA this is where&amp;#39;d it all ends </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:58:25 </td>
   <td style="text-align:left;"> $TSLA $GM $F Morgan Stanley says GM pact may be &amp;#39;profoundly significant&amp;#39; to change narrative 
 
After General Motors announced last night that it is joining Tesla&amp;#39;s Supercharger Network following Ford&amp;#39;s decision two weeks ago to make its EVs compatible with Tesla&amp;#39;s &amp;quot;increasingly ubiquitous supercharging network,&amp;quot; Morgan Stanley analyst Adam Jonas called the news &amp;quot;good for consumers, good for Tesla and quite a good sign for GM in terms of moving the needle on capital discipline and collaboration.&amp;quot; Jonas, who thinks this development is &amp;quot;a significant and a welcomed sign for GM investors,&amp;quot; adds that the firm sees the agreement between GM and Tesla as &amp;quot;potentially profoundly significant in narrative change.&amp;quot; GM being willing to work with &amp;quot;the dominant player in EVs&amp;quot; can allow the company to focus investment in more value added areas, such as business model, brand, customer experience, and return of capital, says the analyst, who keeps an Overweight rating and $38 price target on GM shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:58:18 </td>
   <td style="text-align:left;"> $TSLA its going up like it can&amp;#39;t fail. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:58:13 </td>
   <td style="text-align:left;"> $TSLA almost 4 million shares traded already! Wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:55 </td>
   <td style="text-align:left;"> @DarkMatter1 you are in the good place imo. $TSLA is done at this point. No buyers, only short squeeze. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:55 </td>
   <td style="text-align:left;"> $TSLA one heck of a pre market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:52 </td>
   <td style="text-align:left;"> $TSLA Calls 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:49 </td>
   <td style="text-align:left;"> $TSLA NEVER SELLING… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:48 </td>
   <td style="text-align:left;"> $TSLA sidelined </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:40 </td>
   <td style="text-align:left;"> $TSLA - Just a daily reminder of how we are all being enslaved, extorted and robbed unlawfully by Govt. criminals (Federal, State, Local) in every aspect of our lives!! We are not their F ATM machine!! The enslavement of humanity must end, enough is enough!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:37 </td>
   <td style="text-align:left;"> $TSLA i have no clue watch this deff drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:30 </td>
   <td style="text-align:left;"> @OldFngGuy $tsla last December on the nose. Scaled out gains near the highs as posted at +1200 pres split. Shorted down, then entry long last December. How are you doing? 👇🏽

https://stocktwits.com/MLinv/message/503490363 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:18 </td>
   <td style="text-align:left;"> $TSLA Elon Musk regains title of richest person in the world. 
$220.2 billion 🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:14 </td>
   <td style="text-align:left;"> $TSLA I need a 1000 shares before this hits 2000 a share 😜🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:06 </td>
   <td style="text-align:left;"> $TSLA open the casino. ready to take profits on calls and just chill for the weekend. 🍻🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:57:04 </td>
   <td style="text-align:left;"> $TSLA and if for some reason musk sells more shares here … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:56:57 </td>
   <td style="text-align:left;"> $TSLA moon market says adct👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:56:53 </td>
   <td style="text-align:left;"> $TSLA 142%+ profit!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:56:48 </td>
   <td style="text-align:left;"> $TSLA the problem is chasing here… can cause a loss for now until pullback have to be carful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:56:33 </td>
   <td style="text-align:left;"> @ForeverFREE2024 $TSLA ? All in puts.
Short squeeze at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:56:09 </td>
   <td style="text-align:left;"> $TSLA  Wait don&amp;#39;t sell until all time high. it is getting there  soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:55:58 </td>
   <td style="text-align:left;"> $TSLA I want to get in need healthy pull back though, even NVDA had one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:55:52 </td>
   <td style="text-align:left;"> $TSLA got my orders in. Buying calls at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:55:35 </td>
   <td style="text-align:left;"> $TSLA  we are now equal to haven all.the gasoline in America </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:55:30 </td>
   <td style="text-align:left;"> $TSLA this might pullback to 9.99 then go to around 15-16 points and finish on around 250-252 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:55:19 </td>
   <td style="text-align:left;"> $AAPL $AMZN $MSFT $GOOGL $TSLA watch this for motivation.

WHY YOU SHOULD NEVER QUIT - Denzel Washington Motivational Speech 2023
https://youtu.be/RBltxXaxgXI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:55:12 </td>
   <td style="text-align:left;"> @StockWizard99 me too, but unfortunately sold my $tsla calls prematurely, but this will be a better investment Imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:55:11 </td>
   <td style="text-align:left;"> $TSLA love this squeeze 

GIF isn’t relevant just nice to see early In The morning. Start your day off right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:55:02 </td>
   <td style="text-align:left;"> $TSLA 

There&amp;#39;s got to be, a healthy pull back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:59 </td>
   <td style="text-align:left;"> @CP_T your entire wall is $TSLA. Must be wrong a lot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:55 </td>
   <td style="text-align:left;"> $TSLA 
$300.00 PT BOOM! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:53 </td>
   <td style="text-align:left;"> $TSLA still true </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:52 </td>
   <td style="text-align:left;"> $TSLA 300$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:49 </td>
   <td style="text-align:left;"> $tsla with cpi on Tuesday… markets may not rush $spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:49 </td>
   <td style="text-align:left;"> $TSLA $260 on deck today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:48 </td>
   <td style="text-align:left;"> $FNGD I bought 300 @ $10.21 -- just 300. I think $TSLA is great, but this is pure silliness, expecting another market rug pull... maybe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:45 </td>
   <td style="text-align:left;"> $TSLA Hey dipshits, there will be no pullback. Train has departed. Buy high. Tesla to 300 soon, and beyond. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:12 </td>
   <td style="text-align:left;"> $TSLA got any 220? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:12 </td>
   <td style="text-align:left;"> $TSLA As I previously mentioned 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:54:03 </td>
   <td style="text-align:left;"> $TSLA Just hard to believe in my view great for those making money 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:53:37 </td>
   <td style="text-align:left;"> $TSLA Fake news? A Leaked Tesla Report Shows the Cybertruck Had Basic Design Flaws.

https://news.google.com/s/CBIwp7f0w7YB?sceid=US:en&amp;amp;sceid=US:en&amp;amp;r=0&amp;amp;oc=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:53:19 </td>
   <td style="text-align:left;"> $TSLA do we breach 250? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:53:13 </td>
   <td style="text-align:left;"> $TSLA yay I have margin. Time to gamble.  $300 next week calls. 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:53:06 </td>
   <td style="text-align:left;"> $TSLA I just tell it like it is. That’s all good or bad.  It’s showtime </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:53:05 </td>
   <td style="text-align:left;"> $TSLA everyone is going yo probably sell on open... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:52:58 </td>
   <td style="text-align:left;"> @SheldonB33 a lot of noob shorts here, just like $NVDA and $TSLA 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:52:56 </td>
   <td style="text-align:left;"> $NA 🇨🇳 play with AGBA 433 percent revenue increase in one quarter after COVID restrictions lifted....8 million free float, company insiders just bought back 800k shares,
160 million revenue expected per year...undervalued.
Hong Kong play...
Income Statement
They make microchips like $NVDA 

$TSLA $CVNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:52:47 </td>
   <td style="text-align:left;"> $TSLA now we are crossing into the part of the program where the retail bull starts demonstrating a complete lack of market cap understanding. Maybe Tesla will be 1/4 of the GDP of the US soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:52:45 </td>
   <td style="text-align:left;"> $TSLA 
Large Monetization </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:52:25 </td>
   <td style="text-align:left;"> $TSLA o Btw this is truth that’s all just the truth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:52:23 </td>
   <td style="text-align:left;"> $TSLA I hope we get a fucking short squeezeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:52:16 </td>
   <td style="text-align:left;"> $TSLA 285 before next Friday close and my calls are worth 1 mill. Can we do it?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:51:52 </td>
   <td style="text-align:left;"> $TSLA Stocks making the biggest moves premarket: Tesla, General Motors 
 
 https://cnb.cx/3J6x0TI  
 
General Motors announced on Thursday plans to utilize Tesla’s electric vehicle charging network, and said its vehicles will also utilize Tesla’s North American Charging Standard port in its cars starting in 2025. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:51:51 </td>
   <td style="text-align:left;"> $TSLA .40 to 10.40 overnight 
👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:51:49 </td>
   <td style="text-align:left;"> $TSLA I’m clearly Cathie Woods btw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:51:40 </td>
   <td style="text-align:left;"> $TSLA The deficit of the hedge funds shorting is climbing tremendously minute by minute its growing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:51:38 </td>
   <td style="text-align:left;"> $TSLA was not expecting this much in the AM, kinda scary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:51:30 </td>
   <td style="text-align:left;"> $TSLA This is going to be bloody.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:51:14 </td>
   <td style="text-align:left;"> $TSLA absolutely brilliant move by Musk to invest in the infrastructure than no other car or charging company can match.  This is on its way to ATH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:51:04 </td>
   <td style="text-align:left;"> $SPY how I feel knowing bears are probably gonna get divorced and destory their lives trying to short $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:52 </td>
   <td style="text-align:left;"> $TSLA this isn’t stopping til $300, it’s just the way it is, new trend
, crazy price increases, like….nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:43 </td>
   <td style="text-align:left;"> $TSLA : $260 pls!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:34 </td>
   <td style="text-align:left;"> $TSLA Elon is 20 steps ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:29 </td>
   <td style="text-align:left;"> $TSLA short memory remember was $400 then $108 13 months later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:23 </td>
   <td style="text-align:left;"> $TSLA crazy overbought... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:21 </td>
   <td style="text-align:left;"> $TSLA I AM SO FUCK RICH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:19 </td>
   <td style="text-align:left;"> $TSLA trump indictment pump! Also glen greenwald tweeted about a Ukrainian woman in Germany expressing pro Russian disinformation who faced charges based on a German propaganda law which clearly Elon is not aware of. Elon retweeted it! They ended up letting her go as well. Guy is like a sponge for conspiracy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:13 </td>
   <td style="text-align:left;"> $TSLA $GM plans to utilize Tesla’s electric vehicle charging network, and said its vehicles will also utilize Tesla’s North American Charging Standard port in its cars starting in 2025. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:11 </td>
   <td style="text-align:left;"> $TSLA  This is the type of stuff that bankrupts hedge companies this right now right here today bros </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:06 </td>
   <td style="text-align:left;"> $TSLA will sell with profit taking today but impressive move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:50:03 </td>
   <td style="text-align:left;"> $NIO flat while $TSLA ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:58 </td>
   <td style="text-align:left;"> $TSLA wen 275? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:58 </td>
   <td style="text-align:left;"> $TSLA 

By eoy, we should easily go over the 300 imo. That means even if you bought in at 200  last week, you would be up more than 50 percent within 6 months 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:55 </td>
   <td style="text-align:left;"> $TSLA WOW IM RICH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:46 </td>
   <td style="text-align:left;"> $TSLA Tesla will be the gas’s station for all EV essentially, watch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:39 </td>
   <td style="text-align:left;"> $TSLA Easy $260 today.  ;-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:26 </td>
   <td style="text-align:left;"> $TSLA not a great time to buy it&amp;#39;s very over brought, I&amp;#39;m bullish and bulls can say what they want because they want this run to carry on forever but the rsi never lies it&amp;#39;s dues a pull back. Most likely later today or tomorrow, great time to sell and buy back in a few days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:22 </td>
   <td style="text-align:left;"> $TSLA pov: Bears watching us go on a record high 11 day green streak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:16 </td>
   <td style="text-align:left;"> $TSLA clearing all for now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:15 </td>
   <td style="text-align:left;"> $TSLA and $TSLL who need an alternative to tesla shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:49:11 </td>
   <td style="text-align:left;"> $TSLA does this keep going up today 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:48:56 </td>
   <td style="text-align:left;"> $TSLA There’s too much of a deficit now for anyone one big shot to try to come in and short it back down now for today atleast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:48:42 </td>
   <td style="text-align:left;"> $TSLA is going to dominate the charging stations !! That’s huge!! Hang on to your cajones guys!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:48:34 </td>
   <td style="text-align:left;"> $TSLA Gary Black?????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:48:33 </td>
   <td style="text-align:left;"> $TSLA Tesla profits coming to $AI 4 sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:48:21 </td>
   <td style="text-align:left;"> $TSLA off we go🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:48:16 </td>
   <td style="text-align:left;"> $TSLA Predictions for close? 🤔 

$260 is my guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:48:14 </td>
   <td style="text-align:left;"> $TSLA 300 today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:48:13 </td>
   <td style="text-align:left;"> $TSLA shorties getting crapped on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:47:53 </td>
   <td style="text-align:left;"> $TSLA There’s soo much big money short than even people who pay attention to stocks this could go to $550 today. On the real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:47:32 </td>
   <td style="text-align:left;"> $CVNA  &amp;amp; $TSLA are the main shows to watch. Short coverings will come in bunches. 🧨🚀💥💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:47:25 </td>
   <td style="text-align:left;"> $TSLA bears in tears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:47:23 </td>
   <td style="text-align:left;"> $TSLA  how come my options still didn’t show today gain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:47:05 </td>
   <td style="text-align:left;"> $TSLA damn it feels good to be a bull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:46:59 </td>
   <td style="text-align:left;"> $TSLA (+6.2% pre) $GM (+4.3% pre)  GM to use Tesla charging network, joining Ford in leveraging the EV leader’s tech - CNBC

https://openoutcrier.com/l/1686311196376133 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:46:59 </td>
   <td style="text-align:left;"> $TSLA There’s more big money short than people who even watch stocks daily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:46:49 </td>
   <td style="text-align:left;"> $EVGO Assume this is down cause of the $TSLA and $GM deal.  Typical shoot first reaction.  

From The NY Times 

“Tesla sells cars with a plug known as the North American Charging Standard. Ford, G.M. and most other carmakers have sold cars with plugs using the Combined Charging System plug. The two are not compatible.”

“Fast chargers offered by companies like EVgo or Electrify America typically have both plugs and can charge Teslas as well as cars from manufacturers that use C.C.S., including Mercedes-Benz, Volkswagen and Volvo.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:46:34 </td>
   <td style="text-align:left;"> $TSLA FSD Beta is billions of miles ahead of any other driving software. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:46:20 </td>
   <td style="text-align:left;"> $TSLA Don’t be scared big money is short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:46:19 </td>
   <td style="text-align:left;"> $TSLA looks like we may finally get our 12% run day or more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:46:06 </td>
   <td style="text-align:left;"> $TSLA flag 250+ soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:45:51 </td>
   <td style="text-align:left;"> $TSLA Pop it real quick to $275 then $325 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:45:43 </td>
   <td style="text-align:left;"> $TSLA 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:45:33 </td>
   <td style="text-align:left;"> $TSLA why are calls so cheap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:45:30 </td>
   <td style="text-align:left;"> $TSLA  what is margin on selling usage of charging station?  Bang!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:45:07 </td>
   <td style="text-align:left;"> $TSLA SHARES EXTEND GAINS PREMARKET, LAST UP 6.2%; WEDBUSH RAISES PT TO STREET HIGH OF $300
 $TSLA http://dlvr.it/SqQ29h #NEWS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:45:05 </td>
   <td style="text-align:left;"> $TSLA  This is just </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:57 </td>
   <td style="text-align:left;"> $TSLA This is great </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:57 </td>
   <td style="text-align:left;"> $TSLA no one cares that it could be their payday today 🤣 Tesla making them more money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:51 </td>
   <td style="text-align:left;"> $CVNA Strap in for the $29 test 🚀🧨 
 
over that, $34--&amp;gt;$39–&amp;gt;$46 
 
$TSLA $SPY $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:49 </td>
   <td style="text-align:left;"> $TSLA Aaron is giving softball bitcoin questions for any maxi and she looks north with her eyes. I mean come on. &amp;quot;But you did think bitcoin would be higher today&amp;quot;? Yes. Yes we did. You cannot get a square answer out of that person. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:49 </td>
   <td style="text-align:left;"> My Game Plan: $TSLA Shorts at the bell, but I am out on any quick pop. $CVNA Short at the bell and out with any pop above $26! I will look for two drops, but I will keep the stops very very very close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:34 </td>
   <td style="text-align:left;"> $TSLA $GM $F 
250 PreMarket on news   
eh uhhhhhh 
🐉🐉🐉🐉🐉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:30 </td>
   <td style="text-align:left;"> $TSLA  yea things are getting aggressive now. There will be opportunities on both sides of the market today for scalpers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:13 </td>
   <td style="text-align:left;"> $TSLA buy any share available to double it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:08 </td>
   <td style="text-align:left;"> $TSLA why would anyone short this stock.  This is really laughable and sad that people think that Tesla would significantly drop in price.   
 
Delusional or just plain lack of intelligence? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:44:04 </td>
   <td style="text-align:left;"> $TSLA I’m glad I kept holding ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:43:56 </td>
   <td style="text-align:left;"> $TSLA unbelievable for real…sold too early </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:43:53 </td>
   <td style="text-align:left;"> $TSLA beast mode…while I wouldn’t enter a new long position here atm, I wouldn’t short it either. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:43:42 </td>
   <td style="text-align:left;"> $TSLA all this garbage noise will add 1 to 2 % in tsla revenue at the most according to goldman sachs analysts based on this morning comments.He also said it won&amp;quot;t move the needle in terms of total revenue from $1B to $3B added revenue.TSLA stock already up over $66B in market cap.That&amp;#39;s absurd! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:43:29 </td>
   <td style="text-align:left;"> $TSLA Double the price today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:43:28 </td>
   <td style="text-align:left;"> $TSLA is it really good news for Tesla ? If anything , this would drive adoption of GM vehicles… what y’all think ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:43:16 </td>
   <td style="text-align:left;"> $TSLA 
Shorts will continue to be burned today!!  

SQUEEZE ‘EM HARD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:42:52 </td>
   <td style="text-align:left;"> $TSLA Come on 5.50% is that all you’ve got tesla 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:42:49 </td>
   <td style="text-align:left;"> $PYPL $TSLA going off the chart 
 
Shitty Pal going below 63 today 
 
Hey bulls when does the market come to realize the true value of this great cash generating machine and begin to buy? I was told that bedtime story when it was 190 140 90 75 and yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:42:46 </td>
   <td style="text-align:left;"> $TSLA  I&amp;#39;ll short your mom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:42:11 </td>
   <td style="text-align:left;"> $TSLA is this similar to $VINU.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:41:48 </td>
   <td style="text-align:left;"> $TSLA I’m shorting this at 252.24 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:41:45 </td>
   <td style="text-align:left;"> $TSLA u don’t short Tesla lesson learned. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:41:38 </td>
   <td style="text-align:left;"> $TSLA  260 opening bell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:41:31 </td>
   <td style="text-align:left;"> $TSLA 

Cathy for queen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:41:20 </td>
   <td style="text-align:left;"> $TSLA Look what I got just in time for the short squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:41:16 </td>
   <td style="text-align:left;"> $TSLA saving the whole market again 🥩🥵🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:41:05 </td>
   <td style="text-align:left;"> Going into this morning you are either trading $TSLA or $CVNA, this is where all the volume will be! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:40:52 </td>
   <td style="text-align:left;"> $TSLA long live Reeve ❤️🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:40:47 </td>
   <td style="text-align:left;"> $TSLA wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:40:27 </td>
   <td style="text-align:left;"> $TSLA doing Ellon Musk job on cnbc.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:40:11 </td>
   <td style="text-align:left;"> $TSLA  wait until the upgrades &amp;amp;PT’s come in .. shits gonna get real 💵💵💵💵💵💵🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:40:06 </td>
   <td style="text-align:left;"> $TSLA https://www.stockilluminati.com/tsla/news.php - Today’s Biggest Pre-Market Stock Movers: 10 Top Gainers and Losers on Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:39:49 </td>
   <td style="text-align:left;"> $CJET EVs
Strong $TSLA $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:39:46 </td>
   <td style="text-align:left;"> $TSLA From a bullish side, 250 is the big one, if that breaks it&amp;#39;ll be another run, if it fails and also break 248.80 support, it&amp;#39;ll come down heavy, atleast for short term/scalps! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:39:42 </td>
   <td style="text-align:left;"> $TSLA $233 EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:39:20 </td>
   <td style="text-align:left;"> $TSLA Cathie Wood saying good things about TSLA… $250 and up we goooo. Happy hunting Bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:39:17 </td>
   <td style="text-align:left;"> $TSLA screw it let’s do $420!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:39:07 </td>
   <td style="text-align:left;"> $TSLA just to make sure I have this right, they are sharing their chargers with ford and gm in 2025?  That’s why this is pumping now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:39:05 </td>
   <td style="text-align:left;"> $TSLA should I sell next weeks calls when we open or hold 😑 not sure yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:39:00 </td>
   <td style="text-align:left;"> $TSLA $275 next stop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:38:51 </td>
   <td style="text-align:left;"> $TSLA 🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:38:49 </td>
   <td style="text-align:left;"> $TSLA SHORT squeeze sends Tesla to 500 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:38:48 </td>
   <td style="text-align:left;"> $TSLA just dumb luck for me covered at end of 5/8 and went long after a loosing day.. how do i protect 1000 shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:38:46 </td>
   <td style="text-align:left;"> $TSLA  this stock is no walk is run run to all time high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:38:45 </td>
   <td style="text-align:left;"> My alerts for LARGE caps.This shows the result of ONLY buying when H% is low.
I have timestamps + buy fills for everything

$TSLA + $AAPL + $NKE are just few of many I&amp;#39;ve traded. $SPY 
I don&amp;#39;t make 100s of trades. I only buy when I get a confirmation. Ask me for the receipts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:38:39 </td>
   <td style="text-align:left;"> $TSLA $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:38:12 </td>
   <td style="text-align:left;"> $TSLA What is going on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:38:12 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:56 </td>
   <td style="text-align:left;"> $RAIN 3.40 cash per share with huge insider buy . They will come 

$TSLA $BLPH $BAOS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA let it be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:34 </td>
   <td style="text-align:left;"> $TSLA $300 in a heartbeat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:33 </td>
   <td style="text-align:left;"> $TSLA shorts 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:32 </td>
   <td style="text-align:left;"> $TSLA 400-500 by end of july, retracing nividia movements </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:29 </td>
   <td style="text-align:left;"> $SPY $TSLA #PAMPHERTFUP🐂🐂💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:23 </td>
   <td style="text-align:left;"> $TSLA GM and Ford basically acknowledged Tesla as the king of EVs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:14 </td>
   <td style="text-align:left;"> $NVDA $TSLA 

😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:08 </td>
   <td style="text-align:left;"> $TSLA $260-270 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:37:01 </td>
   <td style="text-align:left;"> $TSLA 

We going over 250 today imo 🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:55 </td>
   <td style="text-align:left;"> $TSLA tell us how you really feel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:48 </td>
   <td style="text-align:left;"> $TSLA getting ready for another pop... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:48 </td>
   <td style="text-align:left;"> $TSLA 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:42 </td>
   <td style="text-align:left;"> $LVWR Livewire motorcycles can also use $TSLA Superchargers 
 
https://electrek.co/2023/03/03/electric-motorcycles-charging-up-at-tesla-superchargers/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:40 </td>
   <td style="text-align:left;"> $TSLA monster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:36 </td>
   <td style="text-align:left;"> $TSLA the new $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:32 </td>
   <td style="text-align:left;"> $TSLA forgotten how quickly this bad boy could run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:22 </td>
   <td style="text-align:left;"> $TSLA playing chess not checkers. Way to go Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:18 </td>
   <td style="text-align:left;"> $TSLA over price!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:16 </td>
   <td style="text-align:left;"> $TSLA Now back at $250! This is quite insane as only a month ago we were at $150! $250 is not going to be easy to break through as this is a strong natural RES line. If we pop above $250 and then fall back under I will look to grab some Shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:16 </td>
   <td style="text-align:left;"> $TSLA it looks obvious that this is going to be a huge day. Only an idiot would stand on the tracks and offer resistance today. Shorts capitulate next week we see 300 book it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:13 </td>
   <td style="text-align:left;"> $TSLA omg that margin talk is just nuts. Wtf is going on? The revenue related to renting out autonomous cars/taxis is literally decades away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:11 </td>
   <td style="text-align:left;"> $TSLA  Patience is the key!!! and always give  a 👍 whenever you see somebody driving a Tesla😎😎💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:03 </td>
   <td style="text-align:left;"> $TSLA 300 minimum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:01 </td>
   <td style="text-align:left;"> $TSLA what’s ur bank account around $100 ? She is a billionaire for gods sake! 
Admit you are dumb and broke! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:36:00 </td>
   <td style="text-align:left;"> $TSLA 

The short squeeze is going to be epic and that idiot Dan Nathan will still say it’s “euphoria”. Meanwhile, us longs will be doing this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:35:51 </td>
   <td style="text-align:left;"> $TSLA everytime I click its up a few buckeroos...😂😂🚀🚀🚀🚀👍👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:35:49 </td>
   <td style="text-align:left;"> $TSLA  shoulda held options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:35:49 </td>
   <td style="text-align:left;"> $TSLA F kidding !!!😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:35:25 </td>
   <td style="text-align:left;"> $TSLA with the buying sentiment this high I can only suspect another huge day with and EOD profit taking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:35:25 </td>
   <td style="text-align:left;"> $TSLA What the fuck.  I have 584 shares of this.  Do I dare buy more at these levels?  Or should I sell some? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:35:09 </td>
   <td style="text-align:left;"> $TSLA Look at that beautiful chart!! 300 today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:35:05 </td>
   <td style="text-align:left;"> Wedbush ups Tesla target to $300, adds to &amp;#39;Best Ideas List&amp;#39; - $TSLA - https://thefly.com/permalinks/entry.php/TSLAid3728916 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:35:05 </td>
   <td style="text-align:left;"> $TSLA  wow! I ❤️ it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:34:53 </td>
   <td style="text-align:left;"> $TSLA By this time next year, we’ll have a +$1T market cap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:34:53 </td>
   <td style="text-align:left;"> $TSLA careful bear, there is a gap around $263 that may fill today. Lots of FOMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:34:46 </td>
   <td style="text-align:left;"> $TSLA this is why it shot up after hours Tuesday ! They knew about the deal 🤫 #scammers #fraud #musk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:34:43 </td>
   <td style="text-align:left;"> $TSLA  coming soon 😇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:34:42 </td>
   <td style="text-align:left;"> $TSLA has to be the most liquid stock as Tesla options market is the biggest casino on the WS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:34:31 </td>
   <td style="text-align:left;"> $TSLA looking for a double digit move up today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:34:25 </td>
   <td style="text-align:left;"> latexd5fcc4ec9e1675afd60995e0d8ed1dfbMETA 
$SPY 
 
🔥We Trade LIVE daily for FREE🔥 
📈FOLLOW for Trade-Ideas+📉 
And BE READY!💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:33:47 </td>
   <td style="text-align:left;"> $TSLA GM allegedly saves ~ $400M with this deal. Tesla gives a competitor an easier market entry and a flexible strategy to manage capital cost 
https://www.cnbc.com/2023/06/08/gm-says-tesla-charging-deal-will-save-the-automaker-up-to-400-million.html 
 
The deal is for the next year BTW. With low EV production volume from GM, the impact is tiny. LOL 
 
Tesla inventory of unsold EVs on the other hand is growing and that will impact margins or growth or both.  It is cyclical. 
 
The next cycle starts with the introduction of new tech like solid state battery or swap infra  and it&amp;#39;s  1-2 years away IMO.  
 
Market will figure all this out eventually and drop it like it&amp;#39;s hot! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:33:40 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s go! Why not $500 today?!!! 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:33:37 </td>
   <td style="text-align:left;"> $CVNA today $NKLA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:33:28 </td>
   <td style="text-align:left;"> $TSLA when they say we entering into bull market, thats when you run for the hills, they not saying that to help you out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:33:28 </td>
   <td style="text-align:left;"> $TSLA welcome to homelessness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:33:24 </td>
   <td style="text-align:left;"> $TSLA lol, this probably will blast through all time high like nvidia, markets can be pretty irrational on both sides, I don’t know why people are so greedy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:33:01 </td>
   <td style="text-align:left;"> $TSLA one word INSANITY 
Congratulations 🎊 to all bulls 
And bears 🐻 as usual f u </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:32:59 </td>
   <td style="text-align:left;"> $TSLA is this really going to run to 350, before a pullback? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:32:58 </td>
   <td style="text-align:left;"> $TSLA so what is the PE here again?  over 100? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:32:57 </td>
   <td style="text-align:left;"> $TSLA shorted at 250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:32:29 </td>
   <td style="text-align:left;"> $TSLA 🔥💎✋🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:32:14 </td>
   <td style="text-align:left;"> $TSLA touch 250pm… then free fall back to reality </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 19:31:50 </td>
   <td style="text-align:left;"> $TSLA ah yes from the low 160s after missing earnings end of april straight up around 250. Yea that&amp;#39;s not another bout of fraud that&amp;#39;s been happening in this name since 2019?? </td>
  </tr>
</tbody>
</table></div>

---
